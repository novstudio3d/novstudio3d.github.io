# Nov Studio 3D — Site

Site institucional + catálogo da Nov Studio 3D (impressão 3D sob encomenda, Montes Claros/MG).

## Arquivos

- `index.html` — site completo, autocontido (CSS, JS e imagens embutidos). Funciona aberto no computador ou hospedado.
- `index.template.html` — fonte do site sem as imagens embutidas (para editar o conteúdo e regerar o `index.html` rodando o trocador de imagens).
- `img/` — fotos de exemplo dos produtos (geradas por IA; troque pelas fotos reais dos seus produtos).
- `novstudio3d-fotos.zip` — as mesmas fotos em um pacote.

## Publicar no GitHub Pages (grátis)

1. Crie uma conta gratuita em https://github.com
2. Clique em **New repository** → nome sugerido: `novstudio3d` → marque **Public** → **Create repository**
3. Na página do repo: **Add file** → **Upload files** → arraste o `index.html` → **Commit changes**
4. **Settings** → **Pages** → em *Source*, escolha **Deploy from a branch** → Branch: **main**, pasta **/ (root)** → **Save**
5. Aguarde 1–2 minutos. O site fica no ar em `https://SEU-USUARIO.github.io/novstudio3d/`
6. (Opcional) Domínio próprio: **Settings** → **Pages** → *Custom domain* → digite seu domínio → **Save**.
   Depois, no painel do seu registrador de domínio, crie:
   - Domínio raiz (ex.: novstudio3d.com.br): quatro registros **A** → `185.199.108.153`, `185.199.109.153`, `185.199.110.153`, `185.199.111.153`
   - Subdomínio www (ex.: www.novstudio3d.com.br): um registro **CNAME** → `SEU-USUARIO.github.io`
   - No Registro.br: acesse o painel → seu domínio → **Editar Zona** → adicione os registros acima.
7. De volta em **Settings → Pages**, marque **Enforce HTTPS** quando a opção liberar (o certificado pode levar de minutos a algumas horas para ser emitido).

## Alternativa ainda mais rápida: Netlify Drop

Acesse https://app.netlify.com/drop e arraste o `index.html` — o site sobe na hora com um endereço grátis (ex.: `nome-aleatorio.netlify.app`) e você pode apontar seu domínio próprio depois em **Domain settings**.

## Trocar pelas fotos reais

Substitua os arquivos em `img/` pelas fotos reais mantendo os mesmos nomes, e regere o `index.html` (ou me peça para trocar). Os textos, cores e nomes de produtos podem ser editados diretamente no `index.html`.

## Contatos exibidos no site

- WhatsApp: (38) 99994-0272 → links `https://wa.me/5538999940272?text=...`
- Instagram: https://www.instagram.com/novstudio3d

## Nomes das fotos (importante)

As fotos ficam na pasta `img/` e **os nomes precisam ser exatamente estes** para o site reconhecer:

| Arquivo | Onde aparece no site |
|---|---|
| `img/hero.jpg` | Imagem grande do topo (bancada de impressão 3D) |
| `img/suporte-celular.jpg` | Card "Suporte Ajustável para Celular" |
| `img/organizador-cabos.jpg` | Card "Kit Organizador de Cabos" |
| `img/vaso-geometrico.jpg` | Card "Vaso Geométrico Iridescente" |
| `img/suporte-fone.jpg` | Card "Suporte para Fones" |
| `img/abridor-pote.jpg` | Card "Abridor de Pote Ergonômico" |
| `img/gancho-parede.jpg` | Card "Gancho de Parede Minimalista" |
| `img/organizador-tempero.jpg` | Card "Organizador Giratório de Temperos" |

**Como trocar pelas fotos reais:** salve suas fotos com esses mesmos nomes dentro de `img/` (proporção retrato 2:3 funciona melhor nos cards). Duas opções:

1. **Versão editável** (`index-editavel.html` + pasta `img/`): basta trocar os arquivos das fotos, sem mexer no código. Para publicar, envie a pasta inteira (index-editavel.html → renomeie para index.html) junto com `img/`.
2. **Versão única** (`index.html`): as fotos já estão embutidas dentro do arquivo. Para trocar, edite os textos/preços no código e peça a atualização das imagens (ou regere o arquivo).

**Formatos aceitos:** JPG/PNG/WebP. Recomendado: largura de 800–1400 px, até ~300 KB por foto.

## Versão editável vs. embutida

- `index.html` — um único arquivo completo (923 KB). Arraste e solte no GitHub Pages / Netlify e pronto.
- `index-editavel.html` — código limpo (65 KB) que lê as fotos de `img/`. Melhor para quem vai mexer bastante.

## Identidade visual

Paleta atual baseada no Instagram da marca: preto `#050806`, grafite esverdeado `#0c120e`, verde-limão `#9dff27`, verde de apoio `#53d600` e branco `#f3f7f4`.
