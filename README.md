<!DOCTYPE html>
<html lang="en">
<head>
    <title>ursila-developer portfolio</title>
</head>
<style>
*{
    margin: 0;
    padding: 0;
}
body {
    background-color: rgb(1, 1, 46);
    color: white;
}
nav{
    display: flex;
    justify-content: space-around;
    align-items: center;
    padding: 10px;
    height: 70px;
    background-color: rgb(7, 7, 32);
}
nav ul {
    display: flex;
    justify-content: center;
}
nav ul li {
    list-style: none;
    margin: 0 23px;
    cursor: pointer;
}
nav ul li a {
    text-decoration: none;
    color: white;
    font-size: 20px;
}
nav ul li a:hover {
    color: rgb(231, 6, 6);
    font-size: 19px;
}
.left {
    font-size: 24px;
    font-weight: bold;
}
.firstsection {
    display: flex;
    justify-content: space-around;
    margin: 50px 0;
    align-items: center;
}
.firstsection div {
    width: 70%;
}
.leftsection {
    font-size: 40px;
    margin-left: 80px ;
    margin-top: 0;
}
.rightsection img{
    width: 80%;
    
}
.name {
    color: rgb(82, 184, 224);
    font-weight: bold;
}
#element {
    color: rgb(82, 184, 224);
}
.secondsection {
    max-width: 80vw;
    margin: 80px;;
}
main hr {
   border: 0;
   background-color: rgba(12, 98, 197, 0.74);
   height: 2px;
   margin: 40px 84px;
}
secoundsection h1 {
    font-size: 36px;
}
.textgrey {
    color: grey;
    font-size: 12px;
}
</style>
<body>
    <header>
        <nav>
            <div class="left">ursila's portfolio</div>
            <div class="right">
                <ul>
                  <li><a href="/"> Home</a></li>
                   <li><a href="/"> About</a></li>
                    <li><a href="/"> skills </a></li>
                    <li><a href="/"> Contact me</a></li>
                </ul>
            </div>
        </nav>
    </header>

    <main>
        <section class="firstsection">
            <div class="leftsection">Hi! my name is <span class="name">Ursila</span>
            <div>and I am a passinate  </div>
            <span id="element"></span> 

            </div>
            
             
            <div class="rightsection">
<img src="https://static.vecteezy.com/system/resources/thumbnails/044/448/931/small/cartoon-character-with-the-desk-working-concept-illustration-free-png.png" alt="">
            </div>
        </section>
        <hr>
        <section class="secondsection">
            <span class="textgrey">What i have done so far</span>
            <h1>Work Experiences</h1>
        </section>
    </main>
    
    <script src="https://unpkg.com/typed.js@2.1.0/dist/typed.umd.js"></script>
     <script>
    var typed = new Typed('#element', {
      strings: ['Web Developer', ' Digital Marketer ', 'Video Editer'],
      typeSpeed: 50,
    });
  </script>
</body>
</html>
