# Guía Interactiva de HTTP (MDN Web Docs)

Aplicación web interactiva creada para comprender en profundidad el protocolo **HTTP** y sus **aspectos básicos**, basada en la documentación oficial de Mozilla Developer Network (MDN).

## 🚀 Características incluidas

1. **Arquitectura y Componentes**:
   - Visualización y animación de paquetes entre el *User-Agent (Cliente)*, *Intermediarios (Proxies, Caching, WAF, Balanceadores)* y el *Servidor Web*.
   - Explicación de capacidades controladas por HTTP (Caché, Sesiones/Cookies, CORS).

2. **Anatomía de Mensajes HTTP**:
   - Desglose interactivo con clic para inspeccionar cada elemento: *Start line*, *Headers*, *Línea vacía (CRLF)* y *Body / Payload*.

3. **Simulador de Peticiones y Respuestas en Vivo**:
   - Configura métodos (`GET`, `POST`, `PUT`, `DELETE`), URLs, cabeceras y cuerpo JSON.
   - Plantillas rápidas para simular respuestas `200 OK`, `201 Created`, `304 Not Modified` y `404 Not Found`.
   - Visualización de latencia, negociación de conexión y análisis pedagógico de cada respuesta.

4. **Explorador y Buscador de Códigos de Estado**:
   - Filtros por familias: `1xx`, `2xx`, `3xx`, `4xx`, `5xx`.
   - Búsqueda en tiempo real por número, nombre o descripción.
   - Botón directo para cargar el código en el simulador.

5. **Línea de Evolución de HTTP**:
   - Comparativa de `HTTP/1.0 - HTTP/1.1`, `HTTP/2` (multiplexación) y `HTTP/3` (QUIC sobre UDP).

6. **Quiz Interactivo**:
   - Preguntas de validación técnica con feedback explicativo inmediato.

---

## 🌐 Cómo desplegarlo en Vercel

1. **Subir a GitHub**:
   - Sube esta carpeta a un nuevo repositorio en GitHub.
2. **Importar en Vercel**:
   - Entra en [vercel.com/new](https://vercel.com/new).
   - Selecciona el repositorio e impórtalo (Framework Preset: **Other**).
   - Haz clic en **Deploy**.
   - En segundos tendrás tu URL pública `https://tu-proyecto.vercel.app` para compartirla con cualquier persona.
