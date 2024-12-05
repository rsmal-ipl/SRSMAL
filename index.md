---
layout: default
#title: Home
#permalink: /
---

<style>

   /* Estilo para o menu de navegação */
  nav ul {
    display: flex;
    list-style: none;
    padding: 0;
    margin: 0;
    font-size: 18px; /* Aumenta o tamanho da fonte */
    font-family: Arial, sans-serif; /* Define uma fonte sem serifa */
  }

  nav ul li {
    margin-right: 10px; /* Espaçamento entre itens do menu */
  }

  nav ul a {
    padding: 10px;
    text-decoration: none;
    color: inherit;
  }

  nav ul a:hover {
    text-decoration: underline; /* Sublinhado ao passar o mouse */
  }

  /* Destaca a aba da página atual usando o atributo aria-current */
  nav ul a[aria-current="page"] {
    color: #ff6600; /* Cor destacada para a aba ativa */
    font-weight: bold;
  }
  
  /* Estilo para o contêiner flex principal */
  .content-container {
    display: flex;
    align-items: flex-start;
    margin-bottom: 20px;
  }
  <link rel="icon" type="image/x-icon" href="RM.ico">
  
  /* Ajustar o tamanho da fonte para parágrafos 
  .page-content p {
    font-size: 1.3em;
    line-height: 1.6em;
  }*/

  /* Estilo para a coluna de imagem */
  .side-content {
    margin-right: 40px;
    /*flex: 0 0 auto;
    padding-right: 40px;  Aumentar a distância entre a imagem e os contatos */
  }
  
  
  /* Ajustar imagem na página index.md */
  .index-image {
    width: 200px;  /*Pode ajustar conforme necessário */
    border-radius: 10%;
  }

  
  /* Estilo para a seção de contatos à direita da imagem */
  .contacts {
    display: flex;
    flex-direction: column;
    justify-content: flex-start; /* Garante que o conteúdo de contatos começa no topo */
    font-size: 1.3em;
    line-height: 1em;
    /*margin-top: 0;
    font-size: 1.3em;
    margin-left: 20px;  Aumentar a distância entre a imagem e os contatos */
  }

  /* Estilo para remover bullets e melhorar a aparência dos contatos */
  .contact-item {
    margin-bottom: 10px;
  }

  /* Estilo para o texto principal */
  .main-text {
    margin-top: 30px;  /*Espaço para iniciar abaixo da imagem e dos contatos*/ 
    font-size: 1.3em;
    line-height: 1.6em;
  }
</style>

<div style="font-size: 0.9em;">
  
 <br><br>


  <div class="content-container">
    <!-- Imagem -->
    <div class="side-content">
      <img src="RM.JPG" alt="Ricardo Malheiro" class="index-image">
    </div>

    <!-- Contatos ao lado direito da imagem -->
    <div class="contacts">
      <h2>Contacts</h2>
	  
      <div class="contact-item">Email (IPLeiria): <a href="mailto:ricardo.malheiro@ipleiria.pt">ricardo.malheiro@ipleiria.pt</a></div>
      <div class="contact-item">Email (University of Coimbra): <a href="mailto:rsmal@dei.uc.pt">rsmal@dei.uc.pt</a></div>
      <div class="contact-item">Skype ID: rsmal2010</div>
      <div class="contact-item">Github: <a href="https://github.com/rsmal-ipl" target="_blank">rsmal-ipl</a> (ricardo.malheiro@ipleiria.pt)</div>
	  <div class="contact-item">LinkedIn <a href="https://www.linkedin.com/in/ricardosilvamalheiro/" target="_blank">ricardosilvamalheiro</a></div>
    </div>
  </div>

  <!-- Texto principal abaixo da imagem e dos contatos -->
  <div class="main-text">
    <p>I have a PhD from the <a href="https://www.uc.pt/" target="_blank">University of Coimbra</a> (in Information Science and Technology). I completed, at the same University, my Master and Bachelor's (Licenciatura - 5 years) degrees, respectively in Informatics Engineering and Mathematics (branch of Computer Graphics). I am a full member of the Cognitive and Media Systems (<a href="https://www.cisuc.uc.pt/en/CMS" target="_blank">CMS</a>) research group and the <a href="https://mir.dei.uc.pt/" target="_blank">MIR</a> Lab at the Center for Informatics and Systems of the University of Coimbra (<a href="https://www.cisuc.uc.pt/" target="_blank">CISUC</a>).</p>

    <p>My main research interests and projects are in the areas of Natural Language Processing, Detection of Emotions in Music Lyrics and Text, Text/Data Mining, Feature Engineering, Applied Machine/Deep Learning, LLM, and Data Science.</p>

    <p>I am currently an Adjunct Professor at the Polytechnic Institute of Leiria (<a href="https://www.ipleiria.pt/estg/" target="_blank">IPLeiria - ESTG</a>), Department of Informatics. I teach courses such as Decision Support Systems (Bach. in Informatics Engineering), Knowledge Engineering (Bach. in Informatics Engineering), Data Mining (MSc in Data Science), Text Mining (MSc in Data Science), and Software Engineering (Bach. in Informatics Engineering).</p>

    <p>I supervise several students at the PhD, MSc, and Bachelor's levels. Currently (2024/2025), I am supervising 3 PhD students and 11 MSc students. Most of these students are part of the <a href="https://www.cisuc.uc.pt/en/projects/MERGE" target="_blank">MERGE</a> project (Music Emotion Recognition, Next Generation 2022-2025), funded by FCT (PTDC/CCI-COM/3171/2021), for which I serve as the Technical Coordinator and lead several tasks.</p>

    <br>
    <h2>Important Links</h2>
    <ul>
      <li><a href="https://www.cisuc.uc.pt/en/people/ricardo-malheiro" target="_blank">CISUC Page</a></li>
      <li><a href="https://mir.dei.uc.pt/index.html" target="_blank">CISUC-MIR Page</a></li>
      <li><a href="https://www.cienciavitae.pt/B81A-CB99-A4DF" target="_blank">Ciência Vitae: B81A-CB99-A4DF</a></li>
      <li><a href="https://orcid.org/0000-0002-3010-2732" target="_blank">ORCID: 0000-0002-3010-2732</a></li>
      <li><a href="https://www.webofscience.com/wos/author/record/L-9369-2017" target="_blank">Researcher ID: L-9369-2017</a></li>
      <li><a href="https://www.researchgate.net/profile/Ricardo-Malheiro" target="_blank">ResearchGate Page</a></li>
      <li><a href="https://www.scopus.com/authid/detail.uri?authorId=6508214140" target="_blank">Scopus</a></li>
      <li><a href="https://scholar.google.com/citations?user=km30M3UAAAAJ&hl=en" target="_blank">Google Scholar</a></li>
    </ul>

    <br>
    <h2>Affiliation</h2>
    <ul>
      <li>School of Technology and Management of the Polytechnic Institute of Leiria</li>
      <li>University of Coimbra, Centre for Informatics and Systems of the University of Coimbra</li>
    </ul>
  </div>
</div>
