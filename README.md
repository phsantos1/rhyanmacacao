# Rhyan Martins — Running & Performance

Site estático pronto para GitHub e Netlify. O arquivo `index.html` fica na raiz; não é necessário instalar dependências nem rodar uma etapa de build.

## Publicar pelo GitHub e Netlify

1. Baixe e extraia este pacote no computador.
2. No GitHub, crie um repositório novo e vazio.
3. Envie **o conteúdo desta pasta** para a raiz do repositório: `index.html`, `netlify.toml`, `robots.txt` e as imagens. Não envie apenas o ZIP nem deixe os arquivos dentro de uma segunda pasta.
4. No Netlify, escolha **Add new site → Import an existing project** e conecte sua conta do GitHub.
5. Selecione o repositório. O `netlify.toml` configura a publicação; confirme que o diretório de publicação é `.` e que o comando de build está vazio.
6. Clique em **Deploy site**. Depois, novos commits no GitHub serão publicados pelo Netlify.

## Arquivos de imagem

As fotos fornecidas para o hero, apresentação, cartões de corrida e chamada final estão na raiz e são referenciadas localmente pelo `index.html`. As demais imagens e as fontes tipográficas continuam carregando do Unsplash e do Google Fonts pela internet.

## Agendamento

O formulário abre uma mensagem pré-preenchida no WhatsApp; a pessoa precisa tocar em “Enviar”. Ele não grava pedidos nem consulta disponibilidade. Configure um serviço de backend, armazenamento, autenticação administrativa, disponibilidade real, WhatsApp oficial e a política de privacidade antes de divulgar o agendamento como funcional.
