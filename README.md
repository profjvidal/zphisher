# Zphisher — Ferramenta para Estudos de Segurança Cibernética

<p align="left">
<a href="#"><img title="Made in Bangladesh" src="https://img.shields.io/badge/MADE%20IN-BANGLADESH-green?colorA=%23ff0000&colorB=%23017e40&style=for-the-badge"></a>
</p>

<p align="center">
<a href="#"><img title="Zphisher" src="https://raw.githubusercontent.com/htr-tech/release-download/master/images/banner/zphisher.png"></a>
</p>

<p align="center">
<a href="https://github.com/htr-tech"><img title="Author" src="https://img.shields.io/badge/Author-htr--tech-red.svg?style=for-the-badge&logo=github"></a>
<a href="#"><img title="Open Source" src="https://img.shields.io/badge/Open%20Source-%E2%9D%A4-green?style=for-the-badge"></a>
</p>

<p align="center">
<a href="#"><img title="Version" src="https://img.shields.io/badge/Version-2.0-green.svg?style=flat-square"></a>
<a href="#"><img title="Language" src="https://badges.frapsoft.com/bash/v1/bash.png?v=103"></a>
<a href="https://github.com/htr-tech/followers"><img title="Followers" src="https://img.shields.io/github/followers/htr-tech?color=blue&style=flat-square"></a>
<a href="https://github.com/htr-tech/zphisher/stargazers/"><img title="Stars" src="https://img.shields.io/github/stars/htr-tech/zphisher?color=red&style=flat-square"></a>
<a href="https://github.com/htr-tech/zphisher/network/members"><img title="Forks" src="https://img.shields.io/github/forks/htr-tech/zphisher?color=red&style=flat-square"></a>
<a href="https://github.com/htr-tech/zphisher/watchers"><img title="Watching" src="https://img.shields.io/github/watchers/htr-tech/zphisher?label=Watchers&color=blue&style=flat-square"></a>
</p>

---

## 📖 Sobre o projeto

O **Zphisher** é uma ferramenta de código aberto, desenvolvida principalmente em Bash, utilizada para demonstrar técnicas relacionadas ao phishing, uma modalidade de ataque baseada em engenharia social.

O phishing consiste na utilização de páginas, mensagens ou recursos fraudulentos para induzir usuários a fornecer informações confidenciais, como nomes de usuário, senhas e dados pessoais.

O projeto pode ser estudado em disciplinas de Redes de Computadores, Segurança da Informação e Segurança Cibernética, contribuindo para a compreensão das ameaças digitais e dos mecanismos de proteção.

> [!IMPORTANT]
> **FINALIDADE EXCLUSIVAMENTE EDUCACIONAL E ACADÊMICA**
>
> Este projeto deve ser utilizado somente em ambientes controlados, redes próprias ou laboratórios devidamente autorizados.
>
> A utilização para obtenção indevida de credenciais, realização de fraudes ou comprometimento de contas de terceiros é proibida e pode resultar em responsabilização civil e criminal.

---

## 🎯 Objetivos educacionais

- Compreender o funcionamento de ataques de phishing.
- Estudar técnicas de engenharia social.
- Identificar páginas fraudulentas e tentativas de roubo de credenciais.
- Reconhecer riscos associados à utilização de links desconhecidos.
- Conhecer mecanismos de proteção e autenticação.
- Desenvolver práticas de conscientização em segurança digital.
- Compreender os aspectos éticos e legais da segurança cibernética.

---

## ⚙️ Instalação

O Zphisher foi desenvolvido principalmente em Bash e utiliza ferramentas disponíveis em ambientes GNU/Linux e Termux.

### 📦 Pré-requisitos

Antes de iniciar, recomenda-se possuir conhecimentos básicos de terminal e instalar as seguintes dependências:

- Git
- cURL
- PHP
- OpenSSH
- Bash

### 🐧 Instalação no Linux

**1. Atualize os repositórios:**

```bash
sudo apt update
```

**2. Instale as dependências:**

```bash
sudo apt install git curl php openssh-server -y
```

**3. Clone o repositório:**

```bash
git clone https://github.com/profjvidal/zphisher.git
```

**4. Acesse o diretório:**

```bash
cd zphisher
```

**5. Inspecione o script antes de executá-lo:**

```bash
less zphisher.sh
```

**6. Execute a ferramenta somente em laboratório isolado e autorizado:**

```bash
bash zphisher.sh
```

### 📱 Instalação no Android — Termux

**1. Atualize os pacotes:**

```bash
pkg update && pkg upgrade -y
```

**2. Instale as dependências disponíveis:**

```bash
pkg install git curl php openssh -y
```

**3. Clone o repositório:**

```bash
git clone https://github.com/profjvidal/zphisher.git
```

**4. Acesse o diretório:**

```bash
cd zphisher
```

**5. Analise o código-fonte:**

```bash
less zphisher.sh
```

**6. Execute somente em ambiente de testes autorizado:**

```bash
bash zphisher.sh
```

> [!NOTE]
> A disponibilidade dos pacotes e a compatibilidade da ferramenta podem variar conforme a versão do sistema operacional e do repositório.

---

## 🚀 Instalação por comando único

O projeto original também apresenta um procedimento de instalação e inicialização por comando único:

```bash
apt update && apt install git curl php openssh-server -y && git clone https://github.com/profjvidal/zphisher.git && cd zphisher && bash zphisher.sh
```

> [!CAUTION]
> O comando acima instala dependências, obtém o código-fonte e inicia a ferramenta.
>
> Antes de utilizá-lo, verifique o conteúdo do repositório e certifique-se de que a execução ocorrerá exclusivamente em um laboratório isolado e autorizado.
>
> Em ambientes que exigem privilégios administrativos, os comandos de gerenciamento de pacotes podem precisar de `sudo`.

---

## 🖥️ Demonstração da ferramenta

As imagens abaixo pertencem à documentação original e são mantidas para fins de identificação visual e estudo.

<p align="center">
<img width="40%" src="https://raw.githubusercontent.com/htr-tech/release-download/master/images/zphisher1.png"/>
<img width="51%" src="https://raw.githubusercontent.com/htr-tech/release-download/master/images/zphisher2.png"/>
</p>

---

## ✨ Funcionalidades

O projeto original apresenta as seguintes características:

### [+] Modelos de páginas de autenticação

Disponibiliza modelos que reproduzem visualmente interfaces de login, permitindo estudar como páginas fraudulentas podem ser utilizadas em ataques de phishing.

### [+] Modelos de páginas de redes sociais

Inclui modelos relacionados a plataformas sociais, utilizados para demonstrar técnicas de engenharia social e riscos associados a páginas falsas.

### [+] Quatro opções de encaminhamento de portas

A documentação original apresenta alternativas para encaminhamento de conexões e acesso a serviços locais.

### [+] Facilidade de utilização

A ferramenta possui interface baseada em terminal e menus, facilitando a navegação por usuários com conhecimentos básicos de sistemas GNU/Linux.

> [!WARNING]
> As funcionalidades devem ser estudadas exclusivamente para compreensão de riscos, identificação de ameaças e desenvolvimento de mecanismos de defesa.

---

## 🌐 Opções de tunelamento

A documentação original menciona as seguintes tecnologias:

| Tecnologia | Endereço |
|---|---|
| Localhost | `127.0.0.1` |
| NGROK | https://ngrok.com |
| SERVEO | https://serveo.net |
| LOCALHOSTRUN | https://localhost.run |

Essas tecnologias estão relacionadas ao encaminhamento de conexões e ao acesso a serviços de rede.

Para atividades acadêmicas, recomenda-se utilizar ambientes locais, isolados e sem exposição pública.

A disponibilidade atual desses serviços deve ser verificada nos respectivos sites oficiais.

---

## 🧪 Aplicações educacionais

O estudo do Zphisher pode complementar atividades nas seguintes disciplinas:

| Disciplina | Aplicação |
|---|---|
| Redes de Computadores | Protocolos e comunicação de rede |
| Segurança da Informação | Identificação de ameaças |
| Sistemas Operacionais | Scripts e processos |
| Desenvolvimento Web | Formulários e autenticação |
| Segurança Cibernética | Engenharia social e phishing |
| Ética em Tecnologia | Responsabilidade digital |

### Boas práticas em laboratório

1. Utilizar exclusivamente redes e equipamentos próprios ou autorizados.
2. Trabalhar com informações e contas fictícias.
3. Não coletar senhas ou dados pessoais reais.
4. Evitar a exposição pública de páginas simuladas.
5. Monitorar as atividades desenvolvidas.
6. Documentar os resultados para fins acadêmicos.
7. Respeitar as normas institucionais e a legislação vigente.

---

## ⚖️ Legislação brasileira aplicável

O estudo e a utilização de ferramentas de segurança cibernética devem observar a legislação brasileira.

### 📜 Lei nº 12.737/2012 — Lei Carolina Dieckmann

Introduziu disposições relacionadas aos crimes informáticos no Código Penal brasileiro, incluindo o artigo 154-A, referente à invasão de dispositivo informático.

[Consultar legislação](https://www.planalto.gov.br/ccivil_03/_ato2011-2014/2012/lei/l12737.htm)

### 📜 Lei nº 14.155/2021

Alterou dispositivos do Código Penal relacionados à invasão de dispositivos informáticos, furto mediante fraude e estelionato eletrônico.

[Consultar legislação](https://www.planalto.gov.br/ccivil_03/_ato2019-2022/2021/lei/l14155.htm)

### 📜 Lei nº 12.965/2014 — Marco Civil da Internet

Estabelece princípios, garantias, direitos e deveres para o uso da Internet no Brasil.

[Consultar legislação](https://www.planalto.gov.br/ccivil_03/_ato2011-2014/2014/lei/l12965.htm)

### 📜 Lei nº 13.709/2018 — LGPD

A Lei Geral de Proteção de Dados Pessoais estabelece regras para o tratamento de dados pessoais, inclusive em meios digitais.

[Consultar legislação](https://www.planalto.gov.br/ccivil_03/_ato2015-2018/2018/lei/l13709.htm)

### 📜 Decreto-Lei nº 2.848/1940 — Código Penal

A utilização fraudulenta de páginas de autenticação para obtenção de informações ou vantagens ilícitas pode, dependendo das circunstâncias, envolver dispositivos como o artigo 171, referente ao estelionato, entre outros.

[Consultar Código Penal](https://www.planalto.gov.br/ccivil_03/decreto-lei/del2848compilado.htm)

> [!WARNING]
> **RESPONSABILIDADE LEGAL**
>
> A criação ou utilização de páginas fraudulentas para obter indevidamente credenciais, informações pessoais ou vantagens ilícitas pode gerar responsabilização civil e criminal
