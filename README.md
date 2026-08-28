

	


## 👑 Administradores

| Usuario  | Email                | Contraseña   |
|----------|----------------------|--------------|
| yc       | yc27@gcloud.ua.es     | amina1234    |
| rc       | rc75@gcloud.ua.es     | rahma1234    |

---

## 👤 Usuarios Normales Activos  
Estos usuarios han realizado compras, tienen productos en carrito y/o en favoritos.

| Usuario     | Email                   | Contraseña |
|-------------|--------------------------|------------|
| user2025    | carlosn@gmail.com        | 98765      |
| javier_g    | javierg@gmail.com        | 11234      |
| maria27     | maria.romero@gmail.com   | 44556      |
| elena76     | elenamoreno@gmail.com    | 11223      |


   
# 🛒 MovilGo - Plataforma de Compraventa de Tecnología

## 📝 Descripción General del Proyecto

**MovilGo** es una plataforma dedicada a la **compraventa de dispositivos tecnológicos** reacondicionados y nuevos. A través de nuestro marketplace, los usuarios pueden:

🔍 **Buscar** dispositivos como móviles, tablets, portátiles, smartwatches y más.

⭐ **Consultar valoraciones y comentarios** antes de comprar, obteniendo una visión real de la experiencia de otros usuarios.

📢 **Publicar anuncios** fácilmente para vender cualquier dispositivo tecnológico.

🧭 Navegar una página con **estructura clara y sencilla**, accesible para todo tipo de usuarios.

🤝 **Contactar directamente con nosotros**, lo que garantiza seguridad y confianza antes de realizar la compra.

🧾 **Gestionar su perfil** como usuario registrado, donde pueden:
- actualizar contraseña y editar y actualizar cuenta 📢


📌 Nuestro objetivo es ofrecer una experiencia **segura, confiable y de calidad**, tanto para compradores como para vendedores.

---

## 🌍 Parte Pública

Accesible a cualquier visitante del sitio web. Las funcionalidades incluyen:

📬 **Página de Contacto**  
Información sobre cómo comunicarse con la empresa: dirección, teléfono, redes sociales y correo electrónico.

🛍️ **Catálogo de Productos**  
Explora los dispositivos disponibles aplicando filtros como:
- Categoría 📱 (smartphones, tablets, etc.)
- Marca 🏷️
- Modelo
- Sistema Operativo 🧠
- Estado del producto ⚙️

📦 **Detalle del Artículo**  
Cada producto muestra:
- Valoración media ⭐
- Comentarios de usuarios 💬
- Cantidad disponible (stock) 📦
- Estado y características técnicas 🧾



### 🧩 Entidades de Negocio - Parte Pública

| 📦 **Entidad**     | 📝 **Descripción**                                                                                    		  |
|--------------------|--------------------------------------------------------------------------------------------------------------------|
| **ENContacto**     | Contiene los métodos de contacto con la empresa, incluyendo dirección, teléfono y redes sociales.   		  |
| **ENCatalogo**     | Muestra el catálogo de dispositivos reacondicionados, con filtros por categoría, marca, estado, etc. 		  |	  |
| **ENArticulo**     | Muestra el estado del producto , el stock , la media de valoraciones , el vendedor la descripción del producto,etc.|

## 🔐 Parte Privada

Accesible únicamente para **usuarios registrados**, esta sección permite una gestión completa de la actividad en la plataforma:

🛒 **Venta de dispositivos** y administración de anuncios.  
🧾 **Compra de productos**, pagos, financiación y contacto con el vendedor.  
👥 **Gestión de usuarios**: tipo (empresa, particular), datos fiscales y de contacto.  
📦 **Administración de artículos**, carritos, favoritos, comentarios y valoraciones.  
🏢 **Gestión de proveedores**: se puede consultar nombre, CIF, dirección y sus artículos publicados.

---

### 🔧 Funcionalidades Específicas

- 🛍️ Métodos para realizar la **venta** de productos, controlar anuncios, precios y detalles técnicos.
- 💳 Métodos para realizar la **compra**, incluyendo formas de pago, financiación y contacto con el vendedor.
- 👤 Entidad de los **usuarios**: nombre , dirección, teléfono, email y datos fiscales.
- 📱 Entidad de los **artículos**: categoría (móvil, portátil, tablet…), marca, modelo, año, sistema operativo, estado, memoria, batería, precio, etc.
- 🛒 Entidad de los **carritos de compra**: productos añadidos, precio total y usuario que los añadió.
- 💳 Entidad de los **métodos de pago**: número de tarjeta, fecha de caducidad, CVV, etc.
- ❤️ Entidad de los **favoritos**: productos guardados por cada usuario.
- 💬 Entidad de los **comentarios** sobre los productos y su autor.
- 🌟 Entidad de las **valoraciones** entre usuarios (comprador/vendedor).

---

### 🧩 Entidades de Negocio - Parte Privada

| 📦 **Entidad**         | 📝 **Descripción**                                                                 |
|------------------------|-------------------------------------------------------------------------------------|
| **ENVenta**            | Gestión de venta de productos, anuncios y precios.                                |
| **ENUsuario**          | Información detallada del usuario: tipo, dirección, contacto, datos fiscales.     |
| **ENArticulo**         | Detalles técnicos de los dispositivos: marca, modelo, memoria, precio, etc.       |
| **ENCarrito**          | Productos añadidos al carrito y el usuario correspondiente.                        |
| **ENMetodoPago**       | Gestión segura de los métodos de pago.                                             |
| **ENListaFavorito**    | Control de los productos marcados como favoritos por los usuarios.                |
| **ENComentario**       | Comentarios sobre productos publicados por usuarios registrados.                   |
| **ENPedido**           | Registro de compras realizadas, productos incluidos y datos del comprador.         |


