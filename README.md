# Portofolio
<!DOCTYPE html > 
<html > 
Khead> 
<title>Belajar Bootstrap</title> 
<!-- Required meta tags --> 
<meta charset="utf-8"> 
<meta name="viewport" content="width=device-width, initial-scale=1, shrink-to fit=no"> 
<!-- Bootstrap CSS --> 
<link rel="stylesheet" href="css/bootstrap. min. css"> 
<!-- Optional JavaSript --> 
<!-- Jika Anda tidak punya file jquery dan popper silahkan download terlebih dahulu atau gunakan CDN jika tidak mau repot Lihat pada bab 1--> 
<link rel="stylesheet" href="js/bootstrap.min.js"> <script src="js/jquery-slim.min.js"></script> 
<script src="js/popper. min.js"></script> <script src="js/bootstrap.min.js"></script> 
<style> 
body { 
font: 20px Montserrat, sans-serif; line-height: 1.8; 
color: #000000; 
} 
p {
font-size: 16px; 
}
.margin {
margin-bottom: 45px; 
} 
.bg-1 { 
background-color: orangered; 
color: #ffffff; 
} 
.bg-2 { 
background-color: #000000; 
color: #ffffff; 
} 
.bg-3 { 
background-color: #ffffff; 
}
.bg-4 { 
background-color: #2f2f2f; 
color: #fff; 
} 
.container-fluid { 
padding-top: 70px; 
padding-bottom: 70px; 
} 
.navbar-nav { 
padding-top: 15px; 
padding-bottom: 15px; 
border: 0; 
border-radius: 0; 
margin-bottom: 0; 
font-size: 12px; 
letter-spacing: 5px; 
} 
.navbar-nav li a:hover { 
color: orangered !important; 
} 
</style> 
</head> 
<body> 
<!-- Navbar --> 
<nav class="navbar navbar-fixed-top navbar-light bg-light"> <div class="container"> 
<a class="navbar-brand" href="#">SHARE28S</a> 
<button class="navbar-toggler" type="button" data-toggle="collapse" data target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria expanded="false" aria-label="Toggle navigation">
<span class="navbar-toggler-icon"></span> </button> 
<div class="collapse navbar-collapse" id="navbarSupportedContent"> 
<ul class="navbar-nav ml-auto"> 
<li class="nav-item "> <a class="nav-link" href="#profile">PROFILE <span class="sr only">(current)</span></a> </li> 
<li class="nav-item"> <a class="nav-link" href="#contact">CONTACT</a> </li> 
<li class="nav-item"> <a class="nav-link" href="#portofolio">PORTOfOLIO</a> </li> </div> 
</nav> 
<!-- Background 1 profile --> 
<div class="container-fluid bg-1 text-center"> 
<h3 class="margin" id="profile">Who Am I?</h3>
<img src="img/me.png" class="img-responsive img-circle margin" style="display:inline" alt="Bird" width="350" height="350"> 
<h3>I'm an Programmer</h3> 
<p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. </p> 
</div> 
<!-- Background 2 Contact --> 
<div class="container-fluid bg-2 text-center"> 
<span class="text-white"> 
<h3 class="margin" id="contact">My Contact</h3> 
<p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. </p> 
<a href="#" class="btn btn-light btn-lg" data-toggle="modal" data target="#exampleModal" data-whatever="@getbootstrap"> Message </a></span> </div> 
<!-- Modal --> 
<div class="modal fade" id="exampleModal" tabindex="-1" role="dialog" aria labelledby="exampleModalLabel" aria-hidden="true"> 
<div class="modal-dialog" role="document"> 
<div class="modal-content">
<div class="modal-header"> 
<h5 class="modal-title" id="exampleModalLabel">New message to share28s@mail.com</h5> 
<button type="button" class="close" data-dismiss="modal" aria label="Close"> <span aria-hidden="true">&times;</span> </button> 
</div> 
<div class="modal-body"> 
<form> 
<div class="form-group"> 
<label for="recipient-name" class="col-form label">Recipient:</label> 
<input type="text" class="form-control" id="recipient name"> </div> 
<div class="form-group"> 
<label for="message-text" class="col-form label">Message:</label> 
<textarea class="form-control" id="message text"></textarea> </div> </form> </div>
<div class="modal-footer"> 
<button type="button" class="btn btn-secondary" data dismiss="modal">Close</button>
<button type="button" class="btn btn-primary">Send message</button> 
</div> 
</div> 
</div> 
</div> 
<!-- Background 3 portofolio --> 
<div class="container-fluid bg-3 text-center "> 
<h3 class="margin" id="portofolio">PORTOPOLIO</h3>
<br> 
<div class="row"> 
<div class="col-sm-4"> 
<p>Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.</p> 
<img src="img/cake.png" class="img-responsive margin" style="width:100%" alt="Image"> 
</div> 
<div class="col-sm-4"> 
<p>Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.</p> 
<img src="img/circus.png" class="img-responsive margin" style="width:100%" alt="Image"> 
</div> 
<div class="col-sm-4"> 
<p>Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.</p> 
<img src="img/game.png" class="img-responsive margin" style="width:100%" alt="Image"> 
</div> 
</div> 
</div> 
<!-- Footer --> 
<footer class="container-fluid bg-4 text-center"> 
<p>Bootstrap Theme Made By 
<a href="https://www.share28s.com" target="_blank">www.share28s.com</a></p>

</footer>

</body>

</html>
