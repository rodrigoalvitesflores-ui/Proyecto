# Grupo Aragón — Prototipo Web de Alta Fidelidad

## ¿Qué contiene este proyecto?

```
GrupoAragon/
├── pom.xml                          ← Configuración Maven (Java)
├── README.md                        ← Este archivo
└── src/
    └── main/
        ├── java/com/grupoaragon/
        │   ├── App.java             ← Clase principal (inicia el servidor)
        │   └── ContactController.java ← API REST del formulario
        └── resources/
            ├── application.properties
            └── static/
                └── index.html       ← Tu página web (prototipo)
```

---

## OPCIÓN 1 — Abrir directamente en el navegador (más simple)

Solo abre el archivo `index.html` en tu navegador (doble clic).
✅ No necesitas instalar nada. Perfecto para presentar el prototipo.

---

## OPCIÓN 2 — Ejecutar con Java + Spring Boot (para la presentación técnica)

### Requisitos:
- Java 17 o superior → https://adoptium.net
- Maven → https://maven.apache.org/download.cgi
  (O usar el wrapper incluido en VS Code)

### Pasos:
1. Abre la carpeta `GrupoAragon` en **Visual Studio Code**
2. Instala la extensión: **"Extension Pack for Java"** (de Microsoft)
3. Abre el archivo `App.java`
4. Haz clic en el botón ▶ **Run** que aparece sobre el método `main`
5. Abre tu navegador en: **http://localhost:8080**

### O desde la terminal:
```bash
cd GrupoAragon
mvn spring-boot:run
```

---

## Tecnologías utilizadas

| Capa       | Tecnología              |
|------------|-------------------------|
| Frontend   | HTML5, CSS3, JavaScript |
| Backend    | Java 17 + Spring Boot 3 |
| Servidor   | Apache Tomcat (embebido)|
| Build tool | Maven                   |

---

**Grupo Aragón** — Tecnología · Confianza · Compromiso  
RUC: 20606494085 | Lima, Perú
