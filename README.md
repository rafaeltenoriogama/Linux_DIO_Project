# Hospedagem de Site com Apache

Este repositório contém arquivos necessários para hospedar um site utilizando o servidor Apache. Além disso, inclui um script em bash para automatizar a instalação dos componentes necessários.

O repositório tem como finalidade finalizar a terceira etapa do cursoo **Linux Fundamentals** da Dio Innovantion One.

## Instalação

Para hospedar o site, siga as instruções abaixo:

1. Clone este repositório:

   ```bash
   git clone https://github.com/rafaeltenoriogama/Linux_DIO_Project
   ```

2. Execute o script de infraestrutura como código (IaC) `iac.sh`:

   ```bash
   cd Linux_DIO_Project
   chmod +x iac.sh
   .iac.sh
   ```

   Este script irá atualizar a máquina, instalar o Apache e configurar os arquivos do site para a pasta padrão **/var/www/html**.

3. Após a execução bem-sucedida do script, o site estará disponível no seu servidor Apache.

## Estrutura de Arquivos

- **css/**: Estilos CSS do site.
- **img/**: Imagens utilizadas no site.
- **js/**: Scripts JavaScript do site.
- **scss/**: Arquivos SCSS (Sass) para estilização.
- **vendor/**: Bibliotecas de terceiros utilizadas no site.
- **.DS_Store**: Arquivo específico do sistema MacOS, geralmente ignorado.
- **about.html**: Página "Sobre nós".
- **blog-single.html**: Página individual de postagem no blog.
- **blog.html**: Página do blog.
- **contact.html**: Página de contato.
- **elements.html**: Página com elementos diversos.
- **index.html**: Página inicial do site.
- **projects.html**: Página de projetos.
- **service.html**: Página de serviços.

## Licença

Este projeto está licenciado sob a [Licença MIT](LICENSE).
