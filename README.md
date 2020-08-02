# Buscador de Gifs

Utilizando a API do site https://developers.giphy.com/explorer

Fiz um aplicativo para buscar e compartilhar gifs.

## Sobre o Aplicativo

Quando o aplicativo carrega ele busca os 20 primeiros gifs que estão no top trending do site.

<img width="300px" src="https://raw.githubusercontent.com/tiagomartinscc/flutter_buscador_gifs/master/docs/Screenshot_1596378065.png" />

Existe uma barra de busca que faz a pesquisa por palavra chave no site.

<img width="300px" src="https://raw.githubusercontent.com/tiagomartinscc/flutter_buscador_gifs/master/docs/Screenshot_1596378086.png" />

São carregadas 19 imagens por vez.

<img width="300px" src="https://raw.githubusercontent.com/tiagomartinscc/flutter_buscador_gifs/master/docs/Screenshot_1596378090.png" />

Ao clicar em um gif, ele é exibido em uma nova página, sendo o título do pagina o nome do gif e um botão de compartilhar no topo.

<img width="300px" src="https://raw.githubusercontent.com/tiagomartinscc/flutter_buscador_gifs/master/docs/Screenshot_1596378130.png" />

Clicando no botão de compartilhar aparece as opções instaladas no smartphone.

<img width="300px" src="https://raw.githubusercontent.com/tiagomartinscc/flutter_buscador_gifs/master/docs/Screenshot_1596378134.png" />

Na página principal, ao segurar o clique por um tempo em um gif, abre também a opção de compartilhar sem a necessidade de abrir em outra página.

<img width="300px" src="https://raw.githubusercontent.com/tiagomartinscc/flutter_buscador_gifs/master/docs/Screenshot_1596378144.png" />

## Tecnologias

### Plugins utilizados

 * share: ^0.6.1+1 (Para compartilhamento)
 * transparent_image: ^1.0.0 (Para carregar as imagens de uma forma mais suave)
 * http: ^0.12.0+2 (Para conectar a API do giphy)

### Principais componentes

 * Scaffold - Layout
 * FutureBuilder - Container dinâmico
 * CircularProgressIndicator - Indicação de Carregamento
 * SliverGridDelegateWithFixedCrossAxisCount - Grid utilizado para a página principal
 * GestureDetector - Links (onTap) e Segurar apertado (onLongPress)

This project is a starting point for a Flutter application.

A few resources to get you started if this is your first Flutter project:

- [Lab: Write your first Flutter app](https://flutter.dev/docs/get-started/codelab)
- [Cookbook: Useful Flutter samples](https://flutter.dev/docs/cookbook)

For help getting started with Flutter, view our
[online documentation](https://flutter.dev/docs), which offers tutorials,
samples, guidance on mobile development, and a full API reference.
