# Rueda Libre | Alquiler y Rutas de Bicicletas

Rueda Libre es una plataforma web orientada a la movilidad sostenible en la ciudad de Medellín. Ofrece servicios de alquiler de diferentes tipos de bicicletas (urbanas, de montaña, eléctricas, etc.), recorridos guiados y un taller de mantenimiento.

Este proyecto forma parte de las prácticas de desarrollo web utilizando HTML5, CSS3, diseño responsivo y **Bootstrap 5.3**.

---

##  Estructura del Proyecto y Páginas

El proyecto está organizado de la siguiente manera para facilitar la navegación entre secciones:

* **`index.html` (Página de Inicio)**
  * **Sección de presentación (Hero):** Bienvenida general y eslogan del servicio.
  * **¿Quiénes somos?:** Breve descripción del negocio y enlace directo a la ubicación en el mapa.
  * **Nuestra Flota:** Tarjetas interactivas con la variedad de bicicletas disponibles (urbana, plegable, montaña, gravel, eléctrica, infantil y tándem) junto con sus precios por hora.
  * **Nuestros Servicios:** Alquiler, rutas guiadas y taller de reparación.
  * **Nuestras Rutas:** Vista previa de los recorridos temáticos guiados (Río y parques, Sabores de barrios, Reto las Palmas).
  * **Cómo alquilar y Beneficios:** Guía rápida de requisitos y ventajas de elegirnos.
  * **Encuéntranos y Reservas:** Dirección física (DeModa Outlet), correo de contacto y botón de acceso rápido para reservar por WhatsApp.

* **`tarifas.html` (Página de Tarifas)**
  * **Tarifas de alquiler:** Tabla detallada con los precios por hora, medio día (4 horas) y día completo para cada modelo de bicicleta.
  * **Tarifas de recorridos guiados:** Tabla informativa con distancia, duración, nivel de dificultad y precio por persona de cada ruta.
  * **Información adicional:** Aviso importante con lo que incluyen las tarifas y recomendaciones de qué llevar.

* **`reservas.html` (Página de Reservas)**
  * *Nota:* Contiene el formulario interactivo para que los usuarios puedan apartar su bicicleta o ruta seleccionando fechas, tipo de vehículo y datos de contacto (conectado con accesibilidad de formularios y validaciones).

---

## Tecnologías y Herramientas Utilizadas

* **HTML5:** Marcador semántico estructurado.
* **CSS3 & Variables (`:root`):** Estilos personalizados, paleta de colores corporativa y diseño adaptativo (*Responsive Design* con Media Queries).
* **Bootstrap (v5.3):** Framework CSS utilizado para componentes estructurados (como las tablas responsivas y sistemas de filas/columnas).
* **Google Fonts:** Tipografías *Montserrat* y *Open Sans*.

---

## Cómo ver el proyecto localmente

1. Clona este repositorio o descarga los archivos en tu computador.
2. Abre la carpeta del proyecto en tu editor de código favorito (ej. **VS Code**).
3. Asegúrate de tener la extensión **Live Server** instalada en VS Code.
4. Haz clic derecho sobre el archivo `index.html` y selecciona **"Open with Live Server"** para visualizar el sitio web completo en tu navegador.