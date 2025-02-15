# amazon-mini-project
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Amazon</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.7.2/css/all.min.css" integrity="sha512-Evv84Mr4kqVGRNSgIGL/F/aIDqQb7xQ2vcrdIwxfjThSH8CSR7PBEakCr51Ck+w+/U6swU2Im1vVX0SVk9ABhg==" crossorigin="anonymous" referrerpolicy="no-referrer" />
    <link rel="stylesheet" href="style.css">

</head>
<body>
    <header>
        <div class="navbar">
        <div class="nav-logo border">
            <div class="logo"></div>
        </div>
        <div class="nav.address border">
            <p class="add-first"> Deliver to</p>
            <div class="add-icon">
                <i class="fa-solid fa-location-dot"></i>
                <p class="add-second">India</p>
            </div>
        </div>
        <div class="nav-search">
            <select class="search-select">
                <option>All</option>
            </select>
            <input placeholder="Search Amazon" class="search-input">
            <div class="Search-icon">
                <i class="fa-solid fa-magnifying-glass"></i>
            </div>
        </div>
        <div class="nac-signin border">
            <p><span>Hello,sign in</span></p>
            <p class="nav-third">Account & Lists</p>
        </div>
            <div class="nac-return border">
                <p><span>Returns</span></p>
                <p class="nav-fourth">& Orders</p>
            </div>
            <div class="nav-cart border">
                <i class="fa-solid fa-cart-shopping"></i>
                Cart
            </div>
        </div>
        <div class="panel">
            <div class="panel-all">
                <i class="fa-solid fa-bars"></i>
                All
            </div>
            <div class="panel-options">
                <p>Todays Deals</p>
                <p>Customer Service</p>
                <p>Registry</p>
                <p>Gift Cards</P>
                <p>sell</p>
            </div>
            <div class="panel-deals">
                shop deals in Electronics
            </div>
        </div>
    </header>
    <div class="hero-section">
        <div class="hero-message">
            <p>Lorem ipsum dolor sit amet consectetur adipisicing elit.<a href="#">click on this link</a></p>
    </div>
</div>
    <div class="shop-section">
        <div class="box1 box">
          <div class="box-contain">
            <h2>Health care</h2>
            <div class="box-img" style="background-image: url('2.jpg');"></div>
        </div>
    </div>
    <div class="box2 box"><div class="box-contain">
        <h2>Blankets</h2>
        <div class="box-img" style="background-image: url('1.jpg');"></div>
        </div>
    </div>
    <div class="box3 box"><div class="box-contain">
        <h2>Furniture</h2>
        <div class="box-img" style="background-image: url('3.jpg');"></div>
        </div>
    </div>
    <div class="box4 box"><div class="box-contain">
        <h2>Smart phones</h2>
        <div class="box-img" style="background-image: url('4.jpg');"></div>
         </div>
    </div>
    <div class="box1 box">
        <div class="box-contain">
          <h2>Beuty produts</h2>
          <div class="box-img" style="background-image: url('5.jpg');"></div>
      </div>
  </div>
  <div class="box2 box"><div class="box-contain">
      <h2>Books</h2>
      <div class="box-img" style="background-image: url('6.jpg');"></div>
      </div>
    </div>
  <div class="box3 box"><div class="box-contain">
      <h2>kids toys</h2>
      <div class="box-img" style="background-image: url('7.jpg');"></div>
      </div>
    </div>
  <div class="box4 box"><div class="box-contain">
      <h2>Women wear</h2>
      <div class="box-img" style="background-image: url('8.jpg');"></div>
      </div>
    </div>      
 </div> 
 
 <footer>
    <div class="foot-pannel1">
        Back to Top
    </div>
    <div class="foot-pannel2">
        <ul>
            <p> Get to know us</p>
            <a>Careers</a>
            <a>Blog</a> 
            <a>About Amazon</a>
            <a>Investor Relations</a> 
            <a>Amazon Devices</a>  
            <a>Amazon Science</a>  
        </ul>
        <ul>
            <p> Get to know us</p>
            <a>Careers</a>
            <a>Blog</a> 
            <a>About Amazon</a>
            <a>Investor Relations</a> 
            <a>Amazon Devices</a>  
            <a>Amazon Science</a>  
        </ul>
        <ul>
            <p> Get to know us</p>
            <a>Careers</a>
            <a>Blog</a> 
            <a>About Amazon</a>
            <a>Investor Relations</a> 
            <a>Amazon Devices</a>  
            <a>Amazon Science</a>  
        </ul>
        <ul>
            <p> Get to know us</p>
            <a>Careers</a>
            <a>Blog</a> 
            <a>About Amazon</a>
            <a>Investor Relations</a> 
            <a>Amazon Devices</a>  
            <a>Amazon Science</a>  
        </ul>
    </div>
    <div class="foot-pannel3">
        <div class="logo"></div>
    </div>
    <div class="foot-pannel4">
        <div class="pages">
            <a>conditions of use</a>
            <a>privancy Notice</a>
            <a>Your ads privancy choices</a>
        </div>
        <div class="copyright">
            © 1996-2025, Amazon.com, Inc. or its affiliates
        </div>
    </div>
 </footer>
</body>
</html>



css style sheet
*{
    margin: 0%;
    font-family: Arial ;
    border: border-box;
 }

 .navbar{
    height: 60px;
    background-color: #0F1111;
    color: white;
    display: flex;
    align-items: center;
    justify-content: space-evenly;
     
 }
 .nav-logo{
    height: 50px;
    width: 100px;
 }
 .logo{
    background-image: url("amazon_logo (1).png");
    background-size: cover;
    height: 50px;
    width: 100px;
 }
 .border{
   border: 2px solid transparent;
 }
 .border:hover{
   border: 2px solid white;
 }

 .add-first{
   color: #cccccc;
   font-size: 0.85rem;
   margin-left: 15px;
 }
 .add-icon{
   display: flex;
   align-items: center;
}
.add-second{
   margin-left: 3px;
}
.nav-search{
   display: flex;
   justify-content: space-evenly;
   background-color: rgb(240, 168, 13);
   width: 620px;
   height: 40px;
   border-radius: 4px;
}
.nav-search:hover{
   border: 2px solid orange;
}
.search-select{
   background-color: #f3f3f3;
   width: 50px;
   border-top-left-radius: 4px;
   border-bottom-left-radius:4px ;
   border: none;
}
.search-input{
   width: 100%;
   font-size: 1rem;
   border: none;
}
.Search-icon{
   width: 45px;
 display: flex;
 justify-content: center;
 align-items: center;
 font-size: 1.2rem;
 background-color: #febd68;
 border-top-right-radius: 4px;
 border-bottom-right-radius:4px;
 color: #0F1111;
}
span{
   font-size: 0.7rem;
}
.nav-third{
   font-size: 0.85rem;
   font-weight: 700;
}
 .nav-cart i{
   font-size: 30px;
 }
 .nav-cart{
   font-size: 0.85;
   font-weight: 700;
 }
 .panel{
   height: 40px;
   background-color: #222f3d;
   display: flex;
   color: white;
   align-items: center;
   justify-content: space-evenly;
 }
 .panel-options p {
   display: inline;
   margin-left: 10px;
 }
 .panel-options{
   width: 70%;
   font-size: 0.85rem;
    
 }
.panel-deals{
   font-size: 0.9rem;
   font-weight: 700;
}
.hero-section{
   background-image: url("image.jpg");
   background-size: cover;
   height: 380px;
   display: flex;
   justify-content: center;
   align-items: flex-end;

}
.hero-message{
   background-color: white;
   color: black;
   height: 40px;
   display: flex;
   align-items: center;
   justify-content: center;
   font-size: 0.85rem;
   bottom: 25px;
   position: relative;
   width: 80%;
   margin-bottom: 25px;
   
}
.hero-message a {
   color: #007185;
}
.shop-section{
    display: flex;
    flex-wrap: wrap;
    justify-content: space-evenly;
    background-color: #ecec85;
}
.box{
    /border: 2px solid black none;/
    height: 400px;
    width: 23%;
    background-color: white;
    padding: 20px 0px 15px;
    margin-top: 15px;
}
.box-img{
    height: 350px;
    background-size: cover;
    margin-top: 1rem;
    margin-bottom: 1rem;
}
.box-contain{
    margin-left: 1rem;
    margin-right: 1rem;
}
.box-contain p{
    color: #007185;
}
footer{
    margin-top: 15px;
}
.foot-pannel1{
    background-color: #37475a;
    color: white;
    height: 50px;
    display: flex;
    justify-content: center;
    align-items: center;
    font-size: 0.8rem;
}
.foot-pannel2{
    background-color: #222f3d;
    color: white;
    height: 500px;
    display: flex;
    justify-content: space-evenly;

}
ul{
    margin-top: 20px;
}
ul a{
    display: block;
    font-size: 0.8rem;
    margin-top: 10px;
    color: #dddddd;
}
.foot-pannel3{
    background-color: #222f3d;
    border-top: 0.5px solid white;
    color: white;
    height: 70px;
    display: flex;
    justify-content: center;
    align-items: center;
}
.logo{
   background-image:url("amazon_logo (1).png");
   background-size: cover;
   height: 50px;
   width: 100px;
}
.foot-pannel4{
   background-color:#0F1111 ;
   color: white;
   height: 100px;
   font-size: 0.7rem;
   text-align: center;
}
.pages{
   padding-top: 25px;
}
.copyright{
   padding-top: 5px;
}
