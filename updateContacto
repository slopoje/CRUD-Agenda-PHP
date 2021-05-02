<html>
<head>
</head>
<body>


<?php
$servername = "fdb27.runhosting.com";
$basededatos = "3802606_wpressa36b517a";
$username = "3802606_wpressa36b517a";
$password = "Qwertyui1";

// Crear conexion con la base de datos
$conexion = new mysqli($servername, $username, $password, $basededatos);

//Si no se puede conectar salir
if ($conexion->connect_error) {
  die("ERROR: no se pudo conectar con la base de datos " . $conn->connect_error);
}

//Esto es para que utilice los caracteres con tildes
$conexion->set_charset("utf8");

$conexion -> query ("UPDATE CONTACTO SET ".
                    "telefono='".$_GET['telefono']."',".
                    "direccion='".$_GET['direccion']."',".
                    "email='".$_GET['email']."' ".
                    "WHERE nombre='".$_GET['nombre']."'");
                    
mysqli_close($conexion);
                    
?>

<script>
window.location.href = 'http://1daw.onlinewebshop.net/agenda.php';
</script>

</body>
</html>
