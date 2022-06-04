# nehashome.github.io
@@ -0,0 +1,202 @@
@charset "utf-8";
body{
    margin: 0px;
    padding: 0px;
    background-color: #030303;
}
html{
    scroll-behavior: smooth;
}
ul{
    list-style: none;
}
a{
    text-decoration: none;
}
#main{
    width:100%;
    height:100vh;
    box-sizing: border-box;
    background-color: #edf1fd;
    position: relative;
    background-image: url("https://images.rawpixel.com/image_800/czNmcy1wcml2YXRlL3Jhd3BpeGVsX2ltYWdlcy93ZWJzaXRlX2NvbnRlbnQvbHIvdjg5Ny13YW4tMDFfMS5qcGc.jpg?s=H0mhwIN-4lczT47Nkfu1AUMFYbi6w80CNeSyvjiRPL8");
    background-repeat: no-repeat;
    background-size: cover;
    background-position: right bottom;
}
nav{
    display: flex;
    justify-content: space-between;
    align-items: center;
    text-transform: capitalize;
    font-weight: 600;
    letter-spacing: 2px;
    font-family: Arial, Helvetica, sans-serif;
    position: fixed;
    top: 0;
    left: 0;
    width: 100%;
    box-sizing: border-box;
    padding: 10px 50px;
    background-color: #ebfafb;
    box-shadow: 2px 2px 12px rgba(0,0,0,0.5);
    z-index: l;
}
.menu{
    display: flex;
}
.menu li a{
    padding: 10px 50px;
    color: cadetblue;
    font-size: 16px;
}
.logo{
    font-size: 25px;
    font-weight: bold;
    color: rgb(57, 102, 104);
    font-family: Cambria, Cochin, Georgia, Times, 'Times New Roman', serif;
}
.menu li a:hover,
.active{
    background-color: #559397;
    color:rgb(231, 252, 234) !important;
    font-weight: 600;
     transition: all ease 0.4s;  
}
.name{
    font-family: calibri;
    width: 600px;
    position: absolute;
    left: 20%;
    top: 50%;
    transform: translate(-20%, -50%);

}

.arrow{
    align-self: end;
    width: 50%;
    height: 15%;
    margin-bottom: 4em;
    position: absolute;
    bottom: 0px;
    left: -3%;
    border-right: 1px solid #559397;
}
.arrow::after{
    content:'' ;
    position: absolute;
    width: 0;
    height: 0;
    border-style: solid;
    border-width: 11px 11px 0px 11px;
    border-color: #559397 transparent transparent transparent;
    right: -0.7em;
    bottom: -2px;
}
#about{
  width: 100%;
  height: 100vh;
  box-sizing: border-box;
  display: flex;
  align-items: center;
  justify-content: space-between;
  padding: 50px 5% 0px 5%;
}
.about-text{
    font-family: calibri;
    width:50%
}
.about-text h1{
  font-size: 5rem;
  color: #17d1ac;
}
.about-text h2{
    font-size: 3rem;
    color: #FFFFFF;
    font-weight: 400;
}
.about-text h1,h2{
    margin: 0px;
    padding: 0px;

}
.about-text p{
    font-size: 1.2rem;
    color: rgba(251,251,251,0.90);
}
#portfolio{
    width: 100%;
    box-sizing: border-box;
    font-family: calibri;
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    padding: 60px 2% 20px 2%;
}
.p-heading{
    font-family: calibri;
    font-size: 1.7rem;
    text-align: center;
    color: #FFFFFF;
    font-weight: 400;
    padding: 10px 20px;
    background-color: #734949;
    letter-spacing: 2px;
    border-radius: 2px 2px 20px;
    box-shadow: 2px 2px 20px rgba(253, 204, 204, 0.673);
}
.p-box{
    background-color: #1f1f1f1f;
    overflow: hidden;
    border-radius: 10px;
    box-shadow: 2px 2px 13px rgba(0,0,0,0.3);
    position: relative;
}
.p-b-container{
    width: 90%;
    height: 70vh;
    display: grid;
    grid-template-rows: auto auto;
    grid-template-columns: 1fr 1fr 1fr;
    grid-gap: 10px;
}
.text-overlay{
    font-family: calibri;
    position: absolute;
    left: 0;
    top: 0;
    width: 100%;
    height: 100%;
    display: flex;
    justify-content: center;
    align-items: center;
    flex-direction: column;
    background-color: rgba(23,209,172,0.89);
    display: none;
}
.text-overlay h1,p{
    color: #FFFFFF;
}

.text-overlay h1{
    font-size: 2.2rem;
    margin: 0px;
    padding: 0px;
    letter-spacing: 2px;
}
.text-overlay p{
    font-size: 1.2rem;
    margin: 0px;
}
.p-box:hover .text-overlay{
    display: flex;
}
.p-box img{
    width:100%;
    height: 100%;
    object-fit: cover;
}

