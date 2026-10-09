# You GPS Proteção — Protótipo acadêmico

Site estático para apresentação acadêmica sobre tecnologia e medidas protetivas na violência doméstica.

## Publicação
1. Crie um repositório GitHub separado, por exemplo `you-gps-protecao`.
2. Envie `index.html` e `README.md` para a raiz do repositório e faça commit.
3. Em Vercel, importe o repositório; Framework Preset: Other; Root Directory: `./`; publique.

## Funcionalidades
- Mapa OpenStreetMap com Leaflet.
- Área de exclusão fictícia e simulação local de aproximação.
- Painel institucional, painel de proteção e fundamentos jurídicos.
- Layout adaptado a celulares.

## Limites de segurança
**Não rastreia pessoas**, não solicita GPS, não tem contas reais, não envia alertas, não grava dados e não é adequado para uso operacional. O cenário é inteiramente simulado e a posição do ponto no mapa é fictícia. A futura utilização institucional dependerá de autorização legal, projeto de segurança, governança de dados, testes e integração com órgãos competentes.

## Dependências
Leaflet e tiles OpenStreetMap são carregados pela internet. O uso operacional de tiles requer respeito à política do provedor e eventual infraestrutura própria.


Atualização 1.3: avatar fictício no mapa, identificação DEMO-001, aproximação com zoom 17 para facilitar a leitura das ruas no celular. Nomes das ruas são desenhados nas imagens do OpenStreetMap e não podem ter sua fonte alterada individualmente via CSS; o zoom ajuda a leitura.
