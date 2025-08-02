# Lesson 01 - Aula inaugural (acolhimento e apresentação da disciplina) - Surgimento da Internet e Padrões Web, Arquitetura Cliente-servidor, CSS 3

## Surgimento da Internet

> Nessa semana você deverá ter condições de contextualizar o histórico da Internet, surgimento, caminhos, limites tecnológicos e a evolução rápida nos últimos anos, tendo como foco a era da informação baseada nas interações em redes sociais e a necessidade de uso de padrões Web.

A internet surgiu no contexto da guerra fria (geo-política), por conta da carrida espacial, e a ativação das supostas bombas atômica entre capitalistas e socialistas. Ela perdurou até 89 com a queda do muro de Berlin.

O ponto da história é, o temor de que a infromação concentrada fosse distruída e tal preocupação gerou tentativas de preservar esses dados gerando discussões, conceituações e o surgimento da um primeiro esboço de rede que eventualmente originou a WWW - word wide web.

Video 01
<https://www.youtube.com/watch?v=9hIQjrMHTv4&pp=ygUXaGlzdG9yeSBvZiB0aGUgaW50ZXJuZXQ%3D>

DARPA created a network that would become ARPANET, military, academic and comercial effort.

Network control protocol - TCP + OSI = TCP/IP

Packet switching

Decentralised architecture was developed to avoid missing sata in case of an attack to the kernel of the network, that was centralised.

The conpect of the Internet asose when different decentralised networks were conected.

O DNS traduz um endereço em forma de domínio em um endreço de IP

Video 02 - Alvorada da internet
<https://www.youtube.com/watch?v=Qu0j35LvViQ&pp=ygUUYWx2b3JhZGEgZGEgaW50ZXJuZXQ%3D>

_O que acontece quando digito um domínio na barra de endereços e aperto enter?_

Você digita o domínio e aperta Enter
↓
Verifica se já sabe o IP (cache)
↓
Consulta o DNS (se não souber)
↓
Conecta ao servidor (TCP + HTTPS)
↓
Pede a página (HTTP request)
↓
Recebe os arquivos (HTML, CSS, JS)
↓
O navegador monta a página
↓
Você vê o site!

O que você digitou é chamado de **URL** (Uniform Resource Locator), e a parte que identifica o site é o **domínio** (`www.exemplo.com`).

---

Antes de sair procurando esse site pelo mundo, o navegador pergunta:

> "Já vimos esse site recentemente?"

Ele verifica:

- **Cache do navegador**
- **Cache do sistema operacional**
- **Cache do roteador**
- **Cache do provedor de internet (ISP)**

> Se o computador já souber o caminho (o **endereço IP** do site), ele pode pular direto para a etapa 5.

---

Se ninguém tiver o endereço guardado, o navegador faz uma pergunta para o mundo:

> "Quem sabe onde encontrar `www.exemplo.com`?"

Essa pergunta vai para um **servidor DNS** (Domain Name System), que é como uma lista telefônica da internet. Ele responde:

> "`www.exemplo.com` está no IP `192.0.2.123`"

Pronto, agora o navegador sabe **onde** encontrar o site.

---

Quando o navegador tem o endereço IP, ele envia uma mensagem para o servidor que está naquele IP. Essa conexão é feita usando um protocolo chamado **TCP** (Transmission Control Protocol).

Se o site usa HTTPS (quase todos hoje em dia), também acontece uma **negociação de segurança** chamada **SSL/TLS handshake**, garantindo que a comunicação será **segura e criptografada**.

---

O navegador envia um pedido para o servidor dizendo:

> "Olá, por favor, me envie a página `www.exemplo.com`!"

Esse pedido segue um padrão chamado **HTTP** ou **HTTPS**.

---

O servidor processa o pedido e responde com os arquivos que formam a página:

- Um arquivo HTML (estrutura da página)
- Arquivos CSS (cores, fontes, estilo)
- Arquivos JavaScript (comportamento dinâmico)
- Imagens, vídeos, ícones etc.

---

Agora que recebeu os arquivos, o navegador começa a **interpretar e exibir** a página para você:

1. Lê o HTML e monta a estrutura da página.
2. Aplica o estilo usando CSS.
3. Executa os scripts JavaScript.
4. Vai carregando imagens e conteúdos conforme necessário.

---

Tudo pronto! Agora você vê a página no seu navegador, como se fosse mágica. Mas por trás dessa mágica, existe muita tecnologia trabalhando em conjunto!

---

## Atividade 1

Fazer um item para o glossário da turma sobre

1. **TCP**
2. **intranet**.

TCP (Transmission Control Protocol) – s.m. protocolo de comunicação que garante que dados enviados por uma rede cheguem ao destino de integral.

Fontes:

Cloudflare – <https://www.cloudflare.com/pt-br/learning/ddos/glossary/transmission-control-protocol-tcp/>

Intranet – s.f. rede privada de uma empresa usada para compartilhar informações, sistemas e serviços, é acessível apenas para membros autorizados.

Fontes:

TechSlang – <https://www.techslang.com/definition/what-is-an-intranet/>

## Atividade 02

Assistir ao vídeo disponível em <https://www.youtube.com/watch?v=xSGhV3ynmm4>
Ler o artigo: Porque validar páginas Web disponível no Moodle - <https://animated-memory-v79xw9prp4q3vxx.github.dev/>

Responder às questões disponível em: <https://moodle.poa.ifrs.edu.br/mod/lesson/view.php?id=476603> a partir de 04/08 às 15:42.
