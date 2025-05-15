# AutoPeças Express

Este repositório contém o código-fonte de uma página web para uma loja de autopeças fictícia chamada **AutoPeças Express**. A página foi projetada para ser simples, funcional e responsiva, apresentando seções como produtos, categorias, depoimentos de clientes, newsletter e informações de contato.

## Tecnologias Utilizadas

- **HTML5** para a marcação do conteúdo.
- **CSS3** (importado via arquivo externo `style.css`) para estilização das seções e do layout.
- **JavaScript** para funcionalidades de exibição do menu mobile e botão "voltar ao topo".
- **Google Fonts** (Montserrat) para fontes personalizadas.
- **SVG** ícones em linha, utilizados para ilustrações de redes sociais e diferenciais.

## Estrutura de Pastas e Arquivos

- `index.html`: Página principal contendo todo o conteúdo estático.
- `style.css`: Arquivo CSS externo que contém todas as regras de estilização.
- Imagens (padrão sugerido):
  - `/img/carro.jpg` (imagem de destaque para cartões de categorias).
  - `/img/amortecedor.jpg` (imagem de exemplo para produtos).
  - `/img/foto-perfil-profissional-02.jpg`, `/img/perfil-mulher.jpeg`, `/img/perfil-3.jpg` (fotos de exemplo para depoimentos).

**Obs.:** Certifique-se de usar o caminho correto para as imagens conforme sua organização de pastas.

## Recursos e Sessões da Página

### Header

- Logo da loja e nome (AutoPeçasExpress).
- Navegação principal com links para Home, Sobre, Produtos e Contato.
- Menu mobile para telas pequenas, que ao ser clicado ativa/desativa a exibição do menu.

### Hero

- Seção com destaque inicial (“banner”) para apresentar a marca e chamar o usuário a conhecer os produtos.

### Categorias Populares

- Três cartões de categoria (Motor, Suspensão e Acessórios) com botão para seções de produtos específicas.

### Produtos em Destaque

- Grade de quatro produtos com nome, preço e botão de compra.
- Botão que direciona para a página “Produtos” com catálogo completo.

### Diferenciais

- Destaque de benefícios (Entrega rápida, Garantia de qualidade, Segurança, Suporte Técnico) com ícones em SVG.

### Depoimentos

- Seção de depoimentos com avaliações (estrelas), texto, nome do cliente e cidade.

### Newsletter

- Formulário de inscrição por e-mail para receber ofertas e lançamentos.

### Footer (Rodapé)

- Informações de contato, incluindo endereço, telefone, e e-mail.
- Links rápidos para navegação e categorias.
- Ícones de redes sociais para Facebook, Instagram e WhatsApp.

### Botão Voltar ao Topo

- Ícone em SVG que surge ao rolar a página e, ao ser clicado, faz a página voltar ao topo.

## Configuração e Uso

1. Clone ou baixe este repositório.
2. Garanta que todas as imagens estejam referenciadas corretamente (ajuste os caminhos se necessário).
3. Abra o arquivo `index.html` em um navegador para visualizar a página.
4. Caso deseje, você pode subir esse projeto para um servidor web ou usar extensões do VSCode para rodar localmente (ex.: Live Server).
