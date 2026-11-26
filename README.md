# Dra. Ju Ribeiro — Prévia não oficial

Pediatria V13.3 — Editorial Orgânico + diretrizes técnicas do Chicote. Refinamento da prévia existente, mantendo estrutura, contatos e fotos. Personalização cromática centralizada em `palette.css`, Allo como fonte principal.

Publicação: GitHub Pages, branch `main`, raiz.

Endereço da Enfance sujeito a confirmação. Projeto O Pediatra na Escola divulgado como em construção. Sem formação ou convênios não confirmados. Fotografia de atendimento recortada para excluir paciente. A fonte e o mapa dependem de conexão externa.

## Auditoria V13.3
- Chromium isolado: 360, 390, 768, 1024, 1280 e 1440 px; sem overflow horizontal, sem erros JS, imagens carregadas, âncoras válidas, um H1 e controles principais >=44 px. Menu móvel e FAQ testados.
- Testes com fontes fallback e recursos externos bloqueados: não validam Allo via CDN, iframe, destinos externos ou desempenho em produção. Auditoria WCAG integral e Chicote automatizado não executados.

## Refinamento da hero
- Copy reduzido e ornamentos SVG de coração, ramo, girafa e círculo com animações de entrada de até 4,6 s; `prefers-reduced-motion` desativa os movimentos.
- Teste isolado da hero nas seis larguras de referência, sem overflow ou erros JS; fontes externas e publicação não verificadas.
