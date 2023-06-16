# Desafio1-DNC-LP

 Resolução do primeiro desafio da escola DNC, modulo base

 Link da Landing Page do desafio 1: https://victor-realizou-desafio1-lp-escoladnc.netlify.app/ <br>
 Link da Mailing List do desafio 1: https://docs.google.com/spreadsheets/d/15jTv_bx8oZr_6xtTMkA_V1simcGi2e0XS5BgouQbGLQ/edit?usp=sharing
<br>


Códigos HTML: <br>
<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@100;200;300;400;500;600;700;800;900&display=swap" rel="stylesheet">
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@600;700;800;900&family=Raleway:wght@100;200;300;400;500;600;700&display=swap" rel="stylesheet">
    <link rel="stylesheet" href="style.css"></link>
    <title>Desafio1-DNC=LP</title>
</head>
<body>

    <script src="index.js"></script>
    
    <!--Seção 1 - Menu Superior-->
    <div id="menuSuperior">
        <h1 id="titulo-menuSuperior">Tradição em projetos de arquitetura</h1>
        <p id="sub-titulo-menuSuperior">Arquitetura residencial e comercial.</p>
    </div>

    <!--Seção 2 - Menu Informacional-->
    <div id="menuInformacional">
        <div>
            <p class="infNum">850</p>
            <p class="infTxt">empreendimentos construídos</p>
        </div>
        <div>
            <p class="infNum">40</p>    
            <p class="infTxt">anos de mercado e experiência</p>
        </div>
        <div>
            <p class="infNum">2,000,000</p>
            <p class="infTxt">m² em projetos construídos</p>
        </div>
    </div>
    
    <!--Seção 3 - Promoção da atividade-->
    <div id="promoAtividade">
        <p class="promoAtiv"> <img id="txtPromoAtividade" src="./imagens/txtPromoAtividade.svg" alt="" srcset=""></p>
        <p class="promoAtiv"> <img class="promoAtiv" id="layoutAP" src="./imagens/layoutAP.svg" alt="" srcset=""></p>
    </div>

    <!--Seção 4 - Formulário-->
    <div id="formulario">
        <h1 id="tituloFormulario">Conheça mais sobre nossos serviços:</h1>
        <form action="https://api.sheetmonkey.io/form/jbg1DyMtCPFhKmRdfiSS1B" method="post">
            <input type="text" placeholder="Nome" name="Name" required> <br>
            <input type="e-mail" placeholder="Email" name="Email" required> <br>
            <input type="hidden" name="Created" value="x-sheetmonkey-current-date-time" />
            <button type="submit">Fale Conosco</button>
        </form>
    </div>
</body>
</html>
<br>


Códigos CSS:<br>
*{
    margin: 0px;   
    font-family: "inter";
}
#titulo-menuSuperior{
    margin-top: 185px;
    margin-left: 65px;
    width: 1050px;
    height: 75px;
    font-size: 57.5px;
}
#sub-titulo-menuSuperior{
    margin-top: 25px;
    margin-left: 65px;
    width: 1050px;
    height: 30px;
    font-size: 20px;
}
#menuSuperior{
    background-color: #303030;
    color: white;
    position: absolute;
    width: 1440px;
    height: 475px;
}
#menuInformacional{
    margin-top: 475px;
    position: absolute;
    width: 1440px;
    height: 230px;
    background-color: #F9F9F9;
    color: black;
    display: grid;
    grid-auto-flow: column;
    columns: auto;
}
.infNum{
    display: flex;
    font-size: 40px;
    font-style: normal;
    padding-left: 65px;
    padding-top: 75px;
}
.infTxt{
    display: flex;
    font-size: 20px;
    margin-top: 10px;
    padding-left: 65px;
}
#promoAtividade{
    margin-top: 705px;
    position: absolute;
    width: 1440px;
    height: 775px;
    background-color: #F5F5F5;
    display: grid;
    grid-auto-flow: column;
    columns: auto;
}
.promoAtiv{
    display: flex;
    align-items: center;
}
#txtPromoAtividade{
    width: 735px;
    height: 200px;
}
#layoutAP{
    display: flex;
    width: 480px;
    height: 600px;
}
#formulario{
    margin-top: 1480px;
    position: absolute;
    width: 1440px;
    height: 640px;
    background-color: #303030;
    text-align: center;
}
#tituloFormulario{
    font-size: 32px;
    margin-top: 100px;
    margin-bottom: 50px;
    color: #FFFFFF;
}
input{
    font-family: "raleway";
    width: 510px;
    height: 72px;
    margin: 20px;
    padding-left: 10px;
    border: 0px;
    border-radius: 10px;
    background-color: #FFFFFF;
}
button{
    font-family: "raleway";
    width: 285px;
    height: 75px;
    margin: 20px;
    margin-bottom: 40px;
    border: 0px;
    border-radius: 10px;
    color: white;
    background-color: #C07212;
    font-weight: bolder;
    font-size: 28px;
    cursor: pointer;
}
button:hover{
    font-family: "raleway";
    transform:scale(105%);
    transition-duration: 0.6s;
    background-color: #C07212;
    color: white;
    box-shadow: -2px 7.5px 4px #995b0f5b;
}
<br>
