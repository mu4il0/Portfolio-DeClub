<h1>DevClub - Portfólio com Carrossel Animado </h1>
Este projeto é uma página de portfólio simples desenvolvida com HTML e CSS, apresentando um carrossel animado que exibe imagens de forma dinâmica e responsiva.

<h2>Funcionalidades </h2>
<h3>Carrossel Animado: </h3> As imagens são exibidas em sequência, deslizando horizontalmente, com um tempo de atraso entre cada uma. A animação é contínua e suave.
<h3>Efeito Hover: </h3> Quando o usuário passa o mouse sobre o carrossel, a animação pausa, e as imagens são descoloridas. Ao passar o mouse sobre uma imagem específica, ela retorna às cores originais.
<h3>Animação Bidirecional: </h3> Existem dois carrosséis na página. Um desliza as imagens da direita para a esquerda, enquanto o outro faz o movimento contrário (esquerda para direita).
<h3>Responsividade: </h3> A largura e altura dos itens do carrossel são controladas por variáveis CSS personalizadas, permitindo fácil ajuste de layout.

<h1>Estrutura do Código </h1>
<h2>HTML </h2>
A página é estruturada usando a tag <main>, que contém dois carrosséis em containers distintos. <br>
Cada container define variáveis como --width (largura) e --height (altura) para configurar as dimensões das imagens. <br>
As imagens são carregadas dinamicamente dentro de divs com a classe item, cada uma com um tempo de animação individualizado.

<h2>CSS </h2>
O estilo geral usa box-sizing para garantir um layout consistente e background-color para definir o fundo da página. <br>
O carrossel usa position: absolute para criar uma animação suave das imagens deslizando da borda da tela. <br>
As animações são controladas com keyframes: autoRun para o movimento padrão (direita para esquerda) e reverseRun para o movimento invertido. <br>
O efeito de pausa e descoloração nas imagens é ativado com :hover, adicionando uma interação visual interessante.
