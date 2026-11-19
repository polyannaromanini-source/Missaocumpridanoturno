# Missão Cumprida — Noturno (sem Firebase)

Jogo digital estático para a IV Mentoria de Professores Articuladores do Noturno. Pode ser publicado gratuitamente na Vercel como site estático.

## Publicar na Vercel
1. No repositório `missao-cumprida-noturno` do GitHub, substitua `index.html` e `app.js` pelos arquivos deste pacote.
2. Na Vercel, importe o repositório. Framework: Other; diretório raiz: `./`; sem build.
3. Abra o link de produção. Cada equipe utiliza um notebook e um nome próprio.

## Funcionamento
- Quatro semanas, nove cartas e registro de decisões.
- Sem imprevisto na quarta semana e sem prestação de contas administrativa.
- Revelação automática apenas após a quarta rodada.
- Exportação CSV por equipe e opção de imprimir/salvar PDF.
- Dados armazenados no navegador local (`localStorage`).

## Limitação importante
**Sem Firebase ou outro servidor, não há painel central em tempo real.** O endereço `?painel=1` mostra apenas equipes salvas no mesmo navegador/computador. Para reunir os resultados de notebooks diferentes, cada equipe deve baixar seu CSV e enviá-lo ao formador. Não limpe os dados do navegador antes de exportar.

Não insira dados pessoais reais de estudantes.
