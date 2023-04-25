<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
   <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0-alpha3/dist/css/bootstrap.min.css" rel="stylesheet"
        integrity="sha384-KK94CHFLLe+nY2dmCWGMq91rCGa5gtU4mk92HdvYe+M/SXH301p5ILy+dN9+nJOZ" crossorigin="anonymous">
    <link rel="stylesheet" href="estilos/estilos.css">
    <link rel="stylesheet" href="imagenes">
    <title>bootstrap</title>
</head>

<body>
    <div id="navegador">
    <nav class="navbar navbar-expand-lg bg-body-tertiary">
        <div class="container-fluid" style="border: 30px;">
            <a class="navbar-brand" href="#" style="font-family: Verdana, Geneva, Tahoma, sans-serif;">Navbar</a>
            <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav"
                aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
                <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse" id="navbarNav">
                <ul class="navbar-nav">
                    <li class="nav-item">
                        <a class="nav-link active" aria-current="page" href="#">Inicio</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#">Productos</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#">servicios</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link disabled" href="#">registro</a>
                    </li>
                </ul>
            </div>
        </div>
    </nav>
</div>
<center>
            <div class="container">
            <h1>REGISTRATE</h1><br>
            <form>
            <label for="ingrese su nombre:">Primer Nombre:</label><br>
            <input type="text" name="name" id="name" required><br>
            <label for="ingrese su nombre">Segundo Nombre:</label><br>
            <input type="text" name="name" id="name" required><br>
            <label for="ingrese su apellido1:">Primer Apellido:</label><br>
            <input type="text" name="firstname" id="firstname" required><br>
            <label for="ingrese su apellido2">Segundo Apellido:</label><br>
            <input type="text" name="firstname" id="firstname" required><br>
            <label for="ingrese su telefono:">telefono:</label><br>
            <input type="number" name="phone" id="phone" required><br>
            <label for="ingrese su tipo de documento:">tipo de documento:</label><br>
            <select name="document" id="document" required>
            <option value=""></option>
            <option value="C.C">Cedula de ciudania</option>
            <option value="passaport">pasaporte</option>
            <option value="tarjeta de identidad">tarjeta de identidad</option>
            </select><br>
            <label for="number">Numero de identificación:</label><br>
            <input type="number" name="number" id="number" required><br>
            <label for="email">Correo electronico:</label><br>
            <input type="email" name="email" id="email" required><br>
            <label for="password">Contraseña:</label><br>
            <input type="password" name="password" id="password" required><br>
            <label for="password">Confirmar contraseña:</label><br>
            <input type="password" name="password" id="password"><br>
            <center>
            <button type="submit">enviar </button>
            </center>
        </form>
        </div>
    </center>

</body>
<script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0-alpha3/dist/js/bootstrap.bundle.min.js"
    integrity="sha384-ENjdO4Dr2bkBIFxQpeoTz1HIcje39Wm4jDKdf19U8gI4ddQ3GYNS7NTKfAdVQSZe"
    crossorigin="anonymous"></script>

</html>
