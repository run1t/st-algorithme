<!doctype html>
<html lang="fr">
<head>
  <meta charset="utf-8">
  <title>Algorithme Package Sublime Text </title>
  <link rel="stylesheet" href="bootstrap/css/bootstrap.css">
<body>
<div class="container">
	<h2>Algorithme Package Sublime Text</h2>
	<hr>
	<p>Ce package comprend la coloration syntaxique pour la syntaxe algorithmique plus quelques snippets listés ci-dessous. </p>	
<center><form action="https://www.paypal.com/cgi-bin/webscr" method="post" target="_top" class="form-inline">
<input type="hidden" name="cmd" value="_s-xclick">
<input type="hidden" name="hosted_button_id" value="QGYDVWYV64E7W">
<a href="dl/sublime-algo-V1.0.3.zip"><button id="download"  type="button" class="btn btn-large btn-success">Télécharger</button></a> 
<button type="submit"  class="btn btn-large btn-success" border="0" name="submit" >Faire un don</button>
<img alt="" border="0" src="https://www.paypalobjects.com/fr_FR/i/scr/pixel.gif" width="1" height="1">
</form></center>
	<h4>Installation</h4>
	  Téléchargez puis decompressez le fichier .zip<br>
	  Allez dans :
	  <pre>Preference->Browse Package</pre> 
	  Copier-coller le dossier ALGO dans le dossier récemment ouvert.<br>
	  Ensuite il faut créer un nouveau fichier .algo puis faire un set syntax ALGORITHME<br>
	  Installation finie !
	
	<h4>Snippets</h4>
	<p>Vous ne connaissez pas les snippets ! Vous allez voir, cela va vous simplifier la vie. Pour faire la base d'un algorithme il vous suffira de taper 'pr' puis d'appuyer sur la touche TAB. Ce qui vous donne en trois touches de clavier ceci :
	<p>
	<img src="2.png" width = "195px" height="106px">
	<h6>Voici la liste des snippets :</h6>
	<ul>
	<li>pr  -> PROGRAMME</li>
	<li>if  -> CONDITION SI</li>
	<li>ife -> CONDITION SINON</li>
	<li>wh  -> TANT QUE</li>
	<li>dwh -> JUSQU'A</li>
	<li>pro -> PROCEDURE</li>
	<li>st  -> STRUCTURE</li>
	<li>sw  -> CASPARMI</li>
	</ul>
	<h4>screenshots</h4>
	<img src="3.png" width="300px"> 
	<img src="4.png" width="300px">
	<img src="5.png" width="300px">
	</br>
	</br>
		
	<h3>Logs</h3>

	<h4>Version 1.0</h4>
<script type="text/javascript" src="js/jquery.js"></script>	
<script type="text/javascript">
	$("#download").click(function(){
		 $.ajax({
       type: "POST",
       url: "compteur.php",
       data: "name=John&location=Boston&foo=bar",
       success: function(msg){
         console.log(val(msg)); // je sais plus si c'est val() ou html() qu'il faut utiliser pour un textarea, à toi de voir :)
      }

     });

window.open('dl/sublime-algo-V1.0.3.zip','Download');

     });
return false;
	});

</script>
</div>
</head>
</body>
</html>