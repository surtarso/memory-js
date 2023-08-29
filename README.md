## <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/0/05/Flag_of_Brazil.svg/20px-Flag_of_Brazil.svg.png" alt="Brazil Flag"> Jogo da Memória em HTML, CSS & JavaScript

<img src='./memoria.png' width='50%' height='50%' />

#### Modificações do exemplo dado em aula:
    - Reconstrução completa do código [js]
    - Feature: Aumento do numero de cartas jogáveis de 6 para 9 pares [js, css, html]
    - Feature: Temas e botão para mudar de tema [js, css, html]
    - Feature: Tela de vitória com contagem de erros [js]
    - Animações de abertura, background e hover das cartas [css]
    - QoL: Remoção de dragging das cartas [html]

### Uso:
- [ABRA O JOGO AGORA MESMO](https://tarsogalvao.ddns.net/games/memoria/), ou:
- Clone o repositório ou baixe o .zip
- Abra o index.html no seu navegador.

#### Para adicionar novos temas:
- Baixe as imagens desejadas, sendo elas 9 imagens frente + 1 imagem verso
- Coloque as imagens em uma pasta "img-nometema" dentro da pasta assets (assets/img-nometema/)
- (opcional 1a) Renomeie o arquivo de verso para ser o primeiro da lista (ex. 0.jpg)
- (opcional 1b) Dentro da pasta do tema rode o comando: convert -resize 138x203 -strip ./* card.jpg
- Renomeie o arquivo com o verso para box.jpg e card1.jpg...card9.jpg para as frentes
- Abra assets/js/scripts.js e adicione o nome dado na array "temas" (temas = ['img', 'img-nometema', 'img-etc'])
- Jogue com seu novo tema! =)

## <img src="https://upload.wikimedia.org/wikipedia/en/thumb/a/a4/Flag_of_the_United_States.svg/20px-Flag_of_the_United_States.svg.png" alt="United States Flag"> Memory Match game in HTML, CSS and JavaScript
### Usage:
- [OPEN THE GAME RIGHT NOW](https://tarsogalvao.ddns.net/games/memoria/), or:
- Clone the repository or download the .zip
- Open index.html in your browser.

#### To add new themes:
- Download the desired images, 9 front images + 1 back image
- Put the images in a folder "img-themename" inside the assets folder (assets/img-themename/)
- (optional step 1a) Rename the back image file to be the first in the list (ex. 0.jpg)
- (optional step 1b) Inside the theme folder, run the command: convert -resize 138x203 -strip ./* card.jpg
- Rename the back image file to box.jpg and card1.jpg...card9.jpg for the fronts
- Open assets/js/scripts.js and add the given name to the "temas" array (temas = ['img', 'img-themename', 'img-etc'])
- Play with your new theme! =)
