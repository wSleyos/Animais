<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Animais Diferentes</title>
    <link rel="stylesheet" href="index.html">
    <link rel="stylesheet" href="projeto.css">

</head>
<body>

    <header>
        <h1>Tipos de Animais diferentes</h1>
        <nav>
           
         <img src="img/amais.webp" width="90" height="50" alt="Logo de animais">


        
        </nav>
    </header>
 
<div class="grid">
    <!-- Polvo-Dumbo -->
  <div class="coluna">
    <h1>Polvo-Dumbo</h1>
    <p>    Grimpoteuthis, conhecido como polvo-dumbo, é um gênero de polvos pelágicos da família Opisthoteuthidae. Seu nome popular vem da semelhança com o personagem Dumbo da Disney, devido às barbatanas semelhantes a orelhas que se projetam acima dos olhos. Existem 13 espécies reconhecidas desse gênero. Eles se alimentam de crustáceos, bivalves e copépodes, e seu tempo médio de vida varia entre 3 a 5 anos.
</p>

 <!-- Tubarão-duende-->
  <h1>Tubarão-duende</h1>
  <p>  O tubarão-duende se destaca por seu focinho longo e achatado, repleto de sensores que detectam campos elétricos, ajudando-o a caçar nas águas profundas e escuras. Possui mandíbulas protrusíveis, que se projetam rapidamente para capturar presas em movimento. Seu corpo mole e flácido é adaptado à vida em profundidades entre 200 e 1.200 metros, onde a pressão é alta e a comida escassa. Com nadadeiras pequenas e movimentação lenta, ele usa táticas de emboscada para atacar.
</p>

<!-- Saolae-->
<h1>Saola</h1>
<p>O saola é um bovino encontrado no Vietnã e também no Laos. A Reserva Natural de Vu Quang é uma zona semi-protegida para estes animais. O nome saola fuso significa chifres no Vietnã. </p>
<p>

</div>
  <div class="coluna">
     <h1>Polvo-Dumbo</h1>
  <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/b/b0/Dumbo-hires_%28cropped%29.jpg/1024px-Dumbo-hires_%28cropped%29.jpg" width="300" height="200"  alt="">

<h1>Tubarão-duende</h1>
    <img src="https://res.cloudinary.com/dr0zfbman/images/w_960,h_565,c_scale/f_auto,q_auto:good/v1744261259/WordPress%20Content/Goblin-shark/Goblin-shark.jpg?_i=AA" width="300" height="200" alt="">

  <h1>Saola</h1>
  <img src="https://oeco.org.br/wp-content/uploads/oeco-migration/images/stories/fev2015/13022015-saola.jpg" width="300" height="200" alt="">

</div>
  
 <div class="coluna">

        <form action="#" method="post">
    <label for="nome">Nome:</label><br>
    <input type="text" id="nome" name="nome" required><br><br>

    <label for="email">E-mail:</label><br>
    <input type="email" id="email" name="email" required><br><br>

    <input type="checkbox" id="termos" name="termos" required>
    <label for="termos">Aceito os termos e condições</label><br><br>

    <button type="submit">Cadastrar</button>
  </form>
  </div>
</div>

<script>
    const footer = document.createElement('footer');
    
    footer.innerHTML = '<p>&copy; 2025 - contato:(31)96325-9862 endereço:Rua Denise Cristina,853 Todos os direitos reservados.</p>';
    
    document.body.appendChild(footer);
  </script>
    
</body>
</html>
