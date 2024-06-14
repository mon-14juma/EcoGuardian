<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>EcoGuardian</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <!-- Encabezado -->
    <header>
        <!-- Barra Superior -->
        <div class="top-bar">
            <div class="contact-info">
                <span>Tel: +1-800-123-4567</span>
                <span>Email: info@ecoguardian.com</span>
            </div>
            <div class="language-switch">
                <a href="#">Español</a> | <a href="#">Inglés</a>
            </div>
        </div>

        <!-- Logo y Menú de Navegación -->
        <div class="header-main">
            <div class="logo">
                <a href="inicio.html"><img src="logo.png" alt="EcoGuardian Logo">EcoGuardian</a>
            </div>
            <nav>
                <ul class="nav-links">
                    <li><a href="inicio.html">Inicio</a></li>
                    <li class="dropdown">
                        <a href="articulos.html">Artículos</a>
                        <ul class="dropdown-content">
                            <li><a href="articulos/cambio-climatico.html">Cambio Climático</a></li>
                            <li><a href="articulos/energias-renovables.html">Energías Renovables</a></li>
                            <li><a href="articulos/conservacion.html">Conservación</a></li>
                        </ul>
                    </li>
                    <li class="dropdown">
                        <a href="guias-practicas.html">Guías Prácticas</a>
                        <ul class="dropdown-content">
                            <li><a href="guias-practicas/reciclaje.html">Reciclaje</a></li>
                            <li><a href="guias-practicas/huertos-urbanos.html">Huertos Urbanos</a></li>
                            <li><a href="guias-practicas/reduccion-de-residuos.html">Reducción de Residuos</a></li>
                        </ul>
                    </li>
                    <li class="dropdown">
                        <a href="recursos.html">Recursos</a>
                        <ul class="dropdown-content">
                            <li><a href="recursos/calculadora-huella-carbono.html">Calculadora de Huella de Carbono</a></li>
                            <li><a href="recursos/productos-ecologicos.html">Productos Ecológicos</a></li>
                            <li><a href="recursos/puntos-de-reciclaje.html">Puntos de Reciclaje</a></li>
                        </ul>
                    </li>
                    <li class="dropdown">
                        <a href="comunidad.html">Comunidad</a>
                        <ul class="dropdown-content">
                            <li><a href="comunidad/foros.html">Foros de Discusión</a></li>
                            <li><a href="comunidad/eventos.html">Eventos y Talleres</a></li>
                            <li><a href="comunidad/historias.html">Historias de la Comunidad</a></li>
                        </ul>
                    </li>
                    <li><a href="sobre-nosotros.html">Sobre Nosotros</a></li>
                    <li><a href="contacto.html">Contacto</a></li>
                </ul>
            </nav>
            <div class="search-social">
                <input type="text" placeholder="Buscar...">
                <button><img src="search-icon.png" alt="Buscar"></button>
                <a href="#"><img src="facebook-icon.png" alt="Facebook"></a>
                <a href="#"><img src="twitter-icon.png" alt="Twitter"></a>
                <a href="#"><img src="instagram-icon.png" alt="Instagram"></a>
                <a href="#"><img src="youtube-icon.png" alt="YouTube"></a>
            </div>
        </div>
    </header>
</body>
</html>

/* Estilos generales */
body {
    font-family: Arial, Helvetica, sans-serif;
    margin: 0;
    padding: 0;
}

/* Barra Superior */
.top-bar {
    background-color: #f2f2f2;
    color: #333;
    display: flex;
    justify-content: space-between;
    padding: 10px 20px;
    font-size: 14px;
}

.top-bar .contact-info span {
    margin-right: 20px;
}

.top-bar .language-switch a {
    text-decoration: none;
    color: #333;
}

.top-bar .language-switch a:hover {
    text-decoration: underline;
}

/* Encabezado Principal */
.header-main {
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding: 20px;
    background-color: #fff;
    box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
}

.header-main .logo img {
    height: 40px;
    vertical-align: middle;
}

.header-main .logo a {
    text-decoration: none;
    color: #333;
    font-size: 24px;
    font-weight: bold;
}

.header-main nav ul {
    list-style: none;
    margin: 0;
    padding: 0;
    display: flex;
    gap: 20px;
}

.header-main nav ul li {
    position: relative;
}

.header-main nav ul li a {
    text-decoration: none;
    color: #333;
    font-size: 16px;
    padding: 10px 15px;
}

.header-main nav ul li a:hover {
    background-color: #f2f2f2;
    border-radius: 4px;
}

/* Dropdown */
.header-main nav ul .dropdown:hover .dropdown-content {
    display: block;
}

.header-main nav ul .dropdown .dropdown-content {
    display: none;
    position: absolute;
    background-color: #fff;
    box-shadow: 0 8px 16px rgba(0, 0, 0, 0.1);
    z-index: 1;
    top: 100%;
    left: 0;
    min-width: 200px;
}

.header-main nav ul .dropdown .dropdown-content li {
    width: 100%;
}

.header-main nav ul .dropdown .dropdown-content li a {
    padding: 10px;
    display: block;
}

.header-main nav ul .dropdown .dropdown-content li a:hover {
    background-color: #f2f2f2;
}

/* Búsqueda y Redes Sociales */
.search-social {
    display: flex;
    align-items: center;
    gap: 10px;
}

.search-social input {
    padding: 5px;
    border: 1px solid #ccc;
    border-radius: 4px;
}

.search-social button {
    background: none;
    border: none;
    cursor: pointer;
}

.search-social button img {
    height: 20px;
}

.search-social a img {
    height: 20px;
}
