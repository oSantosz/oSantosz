### Fala meu amigo(a), Eu sou Thiago Santos 👋

- 🔭 Hoje trabalho com frond-end, entrando no back-end
- 🌱 EStudando JavaScript
- 😄 Pronouns: ele/dele

<h1 align="center">Olá, Eu sou Thiago! 👋</h1>

<p align="center">
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" alt="HTML5">
  <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white" alt="CSS3">
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" alt="JavaScript">
</p>

<p align="center">Bem-vindo ao meu perfil do GitHub! Aqui você encontrará alguns dos meus projetos e trabalhos relacionados a HTML, CSS e JavaScript.</p>

<h2 align="center">Sobre mim</h2>

<p align="center">Sou um entusiasta da programação web, apaixonado por criar experiências incríveis na web. Estou sempre aprendendo e aprimorando minhas habilidades em desenvolvimento web.</p>

<h2 align="center">Habilidades</h2>

<p align="center">
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" alt="HTML5">
  <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white" alt="CSS3">
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" alt="JavaScript">
</p>

<h2 align="center">Projetos Destacados</h2>

<p align="center">
  <a href="link-para-o-projeto-1">
    <img src="https://img.shields.io/badge/Projeto%201-000000?style=for-the-badge&logo=github&logoColor=white" alt="Projeto 1">
  </a>
  <a href="link-para-o-projeto-2">
    <img src="https://img.shields.io/badge/Projeto%202-000000?style=for-the-badge&logo=github&logoColor=white" alt="Projeto 2">
  </a>
</p>

<h2 align="center">Contato</h2>

<p align="center">Sinta-se à vontade para entrar em contato comigo através das seguintes redes sociais:</p>

<p align="center">
  <a href="link-para-o-seu-linkedin">
    <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn">
  </a>
  <a href="link-para-o-seu-twitter">
    <img src="https://img.shields.io/badge/Twitter-1DA1F2?style=for-the-badge&logo=twitter&logoColor=white" alt="Twitter">
  </a>
  <a href="link-para-o-seu-website">
    <img src="https://img.shields.io/badge/Website-000000?style=for-the-badge&logo=react&logoColor=white" alt="Website">
  </a>
</p>

<p align="center">Vamos nos conectar e colaborar em alguns projetos incríveis juntos! 💻✨</p>

---

<h2 align="center">Gráfico com HTML, CSS e JavaScript</h2>

```html
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Gráfico com HTML, CSS e JavaScript</title>
<style>
    /* Estilo do gráfico */
    .chart {
        width: 400px;
        height: 300px;
        background-color: #f0f0f0;
        border: 1px solid #ccc;
        position: relative;
    }

    .bar {
        width: 20px;
        background-color: #007bff;
        position: absolute;
        bottom: 0;
    }
</style>
</head>
<body>
    <div class="chart">
        <div class="bar" style="left: 20px; height: 100px;"></div>
        <div class="bar" style="left: 60px; height: 150px;"></div>
        <div class="bar" style="left: 100px; height: 80px;"></div>
        <div class="bar" style="left: 140px; height: 200px;"></div>
        <div class="bar" style="left: 180px; height: 120px;"></div>
    </div>

    <script>
        // Adiciona uma animação de crescimento suave às barras
        document.querySelectorAll('.bar').forEach(bar => {
            const height = bar.style.height;
            bar.style.height = '0';
            bar.style.transition = 'height 1s';
            setTimeout(() => {
                bar.style.height = height;
            }, 100);
        });
    </script>
</body>
</html>

