# Outubro Rosa Digital

Centro Técnico AlfaUnipac de Sarzedo · Projeto educativo · 2026

## Abrir e usar

Abra `index.html` em qualquer navegador moderno. Todos os arquivos de imagem, estilos, conteúdo e jogos são locais: a pasta completa funciona sem internet, inclusive por duplo clique. Links para fontes e compartilhamento público precisam de conexão. Não há instalação, conta, banco de dados ou serviço pago.

- `index.html`: portal educativo, biblioteca de 60 respostas, busca, filtros, impressão e compartilhamento.
- `quiz.html`: rodadas de até 10 perguntas, filtro de nível e tema, explicações e revisão de respostas.
- `evento.html`: Torta na Cara, placar manual de duas equipes, sorteio sem repetição, cronômetro com pausa e tela cheia.
- `perguntas.js`: banco de 60 perguntas, 20 por nível e 10 por tema.
- `style.css`, `script.js`, `jogos.js`: apresentação e interações.
- `img/`: logo institucional, imagem da campanha e ícone.

## Publicar gratuitamente no GitHub Pages

1. Crie um repositório público chamado `outubro-rosa-digital` na conta escolhida.
2. Envie **o conteúdo desta pasta** à raiz do repositório. `index.html` deve ficar na raiz, não dentro de outra pasta.
3. Em **Settings → Pages → Build and deployment**, selecione **Deploy from a branch**, branch **main**, pasta **/ (root)**, e salve.
4. Aguarde a publicação. O GitHub exibirá o endereço final em Pages, no formato `https://SEU-USUARIO.github.io/outubro-rosa-digital/`.
5. Abra o endereço publicado no celular. Gere o QR Code somente com o endereço final confirmado.

Documentação: https://docs.github.com/pt/pages/getting-started-with-github-pages/creating-a-github-pages-site

A publicação externa ainda precisa ser feita; os arquivos locais não criam um repositório automaticamente. Não é necessário configurar domínio, Actions, Node ou compilação.

## Evento e contingência offline

Copie a pasta completa para o notebook e um pendrive antes do evento. Teste `index.html`, `quiz.html` e `evento.html` com a internet desligada. No modo evento, ajuste equipes, nível, tema e duração; sorteie, inicie o cronômetro, revele a resposta e atribua pontos manualmente. A resposta não aparece automaticamente quando o tempo acaba. O placar é temporário: recarregar a página reinicia o jogo. Não há classificação global ou transmissão de dados.

## Editar perguntas

Cada linha em `perguntas.js` contém: tema, nível, pergunta, resposta correta, duas respostas incorretas e explicação. O jogo embaralha a posição da resposta correta. O portal usa o mesmo banco para manter as respostas disponíveis no guia. Use os níveis `facil`, `medio` e `avancado`. Os temas estão no objeto `TOPICOS`.

## Fontes, marca e imagens

Conteúdo educativo baseado em INCA e Ministério da Saúde, consultados em 29/10/2026. Não fornece diagnóstico ou prescrição. A recomendação populacional de mamografia adotada é 50 a 74 anos, bienal, conforme orientação atualizada consultada. Sintomas e risco elevado exigem avaliação individual. Revise orientações antes de reutilizar a campanha em outros anos.

- INCA, população: https://www.gov.br/inca/pt-br/assuntos/cancer/tipos/mama/versao-para-populacao
- INCA, detecção precoce: https://www.gov.br/inca/pt-br/assuntos/gestor-e-profissional-de-saude/controle-do-cancer-de-mama/acoes/deteccao-precoce
- INCA, prevenção: https://www.gov.br/inca/pt-br/assuntos/causas-e-prevencao-do-cancer
- Ministério da Saúde, saúde digital: https://www.gov.br/saude/pt-br/assuntos/saude-de-a-a-z/s/saude-digital

Marca AlfaUnipac: arquivo oficial obtido de https://www.unipacto.com.br/site/images/logo-white-orange.png para o projeto institucional solicitado. A marca pertence à instituição. Não há alegação de revisão médica institucional.

Laço rosa: imagem ilustrativa original criada com a ferramenta Imagegen integrada. Arquivo final: `img/laco-rosa.jpg`. Prompt: “A single exquisite large pink satin awareness ribbon, sculptural realistic 3D silk with rich folds, loop at top, crossing tails at bottom, standing floating diagonally above a soft blush pink studio ground. Warm ivory to blush background, soft rounded shadow, subtle fine grain, soft cinematic light from upper left, refined compassionate optimistic atmosphere. Ribbon fills central 75 percent, portrait 4:5 composition. No words, no logos, no extra objects. Pink and burgundy satin, elegant premium campaign art.”

## Acessibilidade

Layout responsivo, navegação por teclado, foco visível, link para pular navegação, respeito a movimento reduzido, controles rotulados e estados de respostas expressos em texto e cor. O portal principal mantém o conteúdo essencial sem JavaScript; biblioteca e jogos exigem JavaScript.

