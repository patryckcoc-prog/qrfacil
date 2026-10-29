FluxoPTX QR — versão com downloads corrigidos

Arquivos:
- index.html: aplicação de página única.

Como testar localmente:
1. Abra index.html no navegador para testar geração e downloads básicos.
2. Para testar leitor por câmera, publique via HTTPS ou use localhost.

Como publicar na Vercel:
1. Crie um projeto novo ou use um repositório separado para não sobrescrever o site atual.
2. Coloque index.html na raiz do projeto.
3. Faça deploy como projeto estático.

Observações:
- O site original da Vercel não foi alterado.
- As bibliotecas QR Code Styling, jsQR e JSZip continuam sendo carregadas por CDN nesta versão.
- O download de PNG, SVG e ZIP usa a API padrão do navegador.
