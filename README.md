# Souza Clima — Site institucional

Projeto estático pronto para deploy na Vercel.

## Conteúdo

- `index.html` — página única do site (HTML + CSS + JavaScript, com as imagens da marca já embutidas). É o arquivo principal e deve ficar na raiz do projeto.
- `vercel.json` — configuração simples que garante que a Vercel sirva o site como página estática.

Não é necessário nenhum passo de build (sem Node, sem dependências) — é HTML puro.

## Como publicar na Vercel

1. Acesse [vercel.com](https://vercel.com) e crie uma conta (gratuita, plano Hobby).
2. No painel, clique em **Add New → Project**.
3. Escolha a opção de importar esta pasta (ou arraste a pasta inteira na tela de deploy manual).
4. A Vercel detecta automaticamente que é um site estático — não precisa configurar comando de build nem diretório de saída. Clique em **Deploy**.
5. Em poucos segundos o site estará no ar em um endereço temporário (ex: `souza-clima.vercel.app`).
6. Para usar o domínio próprio (registrado no registro.br):
   - No projeto, vá em **Settings → Domains**.
   - Digite o domínio (ex: `souzaclima.com.br`) e adicione.
   - A Vercel vai mostrar os registros DNS (A record e/ou CNAME) para configurar.
   - Copie esses registros no painel do registro.br, em **Editar Zona DNS** do domínio.
   - Aguarde a propagação (minutos a algumas horas) e teste o domínio no navegador.

## Observações

- O plano gratuito (Hobby) da Vercel é destinado a uso pessoal/não comercial. Para um site de negócio, o uso recomendado pela Vercel é o plano Pro — avalie conforme sua necessidade.
- Nenhum conteúdo, texto ou design do site foi alterado neste empacotamento — apenas a organização dos arquivos para o deploy.
