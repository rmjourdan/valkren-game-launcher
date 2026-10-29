<p align="center">
  <img src="docs/valkren.png" alt="Valkren" width="128">
</p>

<h1 align="center">Valkren</h1>

<p align="center">
  Tus juegos de Steam, Epic, EA, GOG y RetroBat en una sola biblioteca,<br>
  con un Modo TV pensado para jugar con mando desde el sillón.
</p>

<p align="center">
  <a href="https://github.com/rmjourdan/valkren-game-launcher/releases/latest"><img src="https://img.shields.io/github/v/release/rmjourdan/valkren-game-launcher?label=versi%C3%B3n&color=f0a030" alt="Última versión"></a>
  <img src="https://img.shields.io/badge/Windows-10%20%7C%2011-0078D4?logo=windows&logoColor=white" alt="Windows 10 y 11">
  <a href="https://github.com/rmjourdan/valkren-game-launcher/releases"><img src="https://img.shields.io/github/downloads/rmjourdan/valkren-game-launcher/total?label=descargas&color=4c9a6a" alt="Descargas"></a>
</p>

<p align="center">
  <a href="https://github.com/rmjourdan/valkren-game-launcher/releases/latest"><b>Descargar para Windows</b></a>
  ·
  <a href="#instalar">Instalar</a>
  ·
  <a href="#tus-datos">Tus datos</a>
</p>

![Modo TV de Valkren: Inicio con Red Dead Redemption 2 destacado y la fila de juegos fijados](docs/screenshots/tv-inicio.webp)

## Qué es Valkren

Valkren es un centro de mando para tu colección de juegos en Windows. Encuentra solo los juegos de tus tiendas, los junta en una biblioteca con portadas, estados y tiempo jugado, y te deja abrir cualquiera desde un mismo lugar, con el mouse o con el mando.

No vende nada ni tiene servidores propios: lee lo que ya está en tu PC y consulta directamente los servicios que tú configuras.

## Funciones

### Una biblioteca para todas tus tiendas

Steam, Epic Games, EA app, GOG y los juegos de RetroBat aparecen juntos, con su portada y su estado. El Inicio te muestra lo que estabas jugando, lo que dejaste a medias, recomendaciones de tu propia biblioteca y tus juegos fijados.

![Inicio de escritorio con las filas Fijados y Seguir jugando](docs/screenshots/desktop-inicio.webp)

### Ordena, filtra y agrupa

Marca cada juego como pendiente, jugando, terminado o recurrente. Filtra por tienda, género, duración o nota, ordena por horas, por Metacritic o por lo último que jugaste, y arma tus propias colecciones. También puedes elegir varios juegos a la vez para agregarlos a una colección.

![Biblioteca en cuadrícula ordenada por Metacritic, con juegos de PC y de consolas clásicas](docs/screenshots/desktop-biblioteca.webp)

### Todo sobre cada juego

La ficha reúne capturas y tráiler, tus logros de Steam o RetroAchievements, cuánto lleva terminarlo (IGDB, con enlace a HowLongToBeat), reseñas de Steam, juegos parecidos de tu biblioteca y el desglose de tu tiempo jugado. Desde ahí lo abres o lo instalas con su tienda.

![Ficha de Hades con capturas, duración estimada y logros](docs/screenshots/desktop-ficha.webp)

### Modo TV

Una interfaz a pantalla completa para jugar desde el sillón: se maneja entera con el mando y suma video de fondo, el nivel de batería del mando y, si lo activas, un menú para suspender o apagar el equipo. Entras con el botón Modo TV, con F11 o manteniendo Start en el mando.

![Página de Baldur's Gate 3 en Modo TV, con Jugar, estados y pestañas de información](docs/screenshots/tv-juego.webp)

### Ofertas y lista de deseos

Ofertas de Steam en tu moneda, ordenadas según lo que juegas, con el historial de precios de IsThereAnyDeal para saber si es el mínimo histórico o una oferta que se repite seguido. Tu lista de deseos te marca cuando un juego llega a su precio más bajo.

![Página de Ofertas con descuentos, precios en pesos chilenos y etiquetas de historial de precios](docs/screenshots/desktop-ofertas.webp)

### Y además

- **Tiempo jugado real:** cuando abres un juego desde Valkren, mide la sesión y la suma a tu historial.
- **Descargas:** instalaciones en curso y actualizaciones pendientes de tus tiendas en una sola página.
- **Tu año y Estadísticas:** horas por mes, géneros, plataformas y cómo puntúas frente a la crítica.
- **Tier list** de tus juegos puntuados, de S a D.
- **Avisos de Windows** opcionales: instalación lista, actualización disponible, logro desbloqueado.
- **Inicio con Windows**, bandeja del sistema, accesos directos por juego y juegos recientes en la barra de tareas.
- **Carpetas de juegos:** suma juegos que no vienen de ninguna tienda eligiendo su carpeta.

## Instalar

Requiere Windows 10 u 11 de 64 bits.

1. Abre la [última versión](https://github.com/rmjourdan/valkren-game-launcher/releases/latest).
2. Descarga `Valkren-Setup-<versión>.exe` y ábrelo. Se instala solo para tu usuario, sin permisos de administrador.
3. Windows puede mostrar «Windows protegió tu PC», porque el instalador todavía no está firmado. Elige **Más información → Ejecutar de todos modos**.

La primera vez, un asistente te guía para conectar tus tiendas.

## Actualizaciones

Valkren busca versiones nuevas al abrirse, cada hora y cuando vuelves a su ventana, y las descarga sola. Cuando una está lista, aparece el botón **Actualizar** en la barra superior; si no lo usas, se instala al cerrar la app. También puedes buscarlas en **Ajustes → Ayuda y créditos**.

## Tus datos

Tu biblioteca, tus ajustes y tus claves se guardan en tu PC (`%APPDATA%\game-tracker`) y nunca se suben a ningún lado. Desinstalar Valkren no los borra.

Algunas funciones usan claves gratuitas de cada servicio (Steam, SteamGridDB, IGDB, IsThereAnyDeal, RetroAchievements). Son personales: cada persona carga las suyas en **Ajustes**.

---

<sub>Este repositorio publica los instaladores y las actualizaciones de Valkren. El código fuente es privado. Los nombres e imágenes de los juegos pertenecen a sus respectivos dueños.</sub>
