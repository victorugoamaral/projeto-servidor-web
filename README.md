# Provisionamento de Servidor Web (Apache2)

Este projeto contém um script de automação para provisionar um servidor web no Linux usando o Apache2.

O script realiza as seguintes etapas:
- Atualiza o servidor.
- Instala o servidor web Apache2.
- Instala o utilitário `unzip`.
- Faz o download de uma aplicação web de um repositório público.
- Descompacta e copia os arquivos para o diretório padrão do Apache (`/var/www/html`).

## Requisitos

- Sistema operacional Linux (Debian/Ubuntu)
- Acesso como usuário root ou permissões de `sudo`
- Git instalado

## Como usar

Clone o repositório:

```bash
git clone https://github.com/victorugoamaral/projeto-servidor-web.git
cd projeto-servidor-web
