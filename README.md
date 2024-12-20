# Administrador de Servidores Minecraft

Este proyecto es un script diseñado para facilitar la instalación y gestión de servidores Minecraft utilizando diferentes versiones y regiones de conexión.

## Versiones Disponibles
El script soporta las siguientes versiones de Minecraft:

- **Forge**
- **Mohist** (instalable desde el menú de gestión después de instalar Forge)
- **Fabric**
- **Vanilla**
- **Paper** (instalable desde el menú de gestión después de instalar Vanilla)
- **Purpur** (instalable desde el menú de gestión después de instalar Fabric)

## Regiones de Ngrok
El script utiliza Ngrok para exponer los servidores. A continuación se muestra una lista de las regiones disponibles:

| Código  | Región                        |
|---------|-------------------------------|
| ap      | Asia / Pacífico (Singapur)    |
| au      | Australia (Sídney)           |
| eu      | Europa (Frankfurt)           |
| in      | India (Mumbai)               |
| jp      | Japón (Tokio)                |
| sa      | Sudamérica (São Paulo)       |
| us      | Estados Unidos (Ohio)        |
| us-cal-1| Estados Unidos (California)  |

## Cómo usar el script

1. **Requisitos previos**:
   - Asegúrate de tener Python 3 instalado en tu sistema.
   - Conexión a Internet para descargar las últimas versiones y dependencias.

2. **Ejecución inicial**:
   Descarga y ejecuta el script para gestionar tu servidor:
   ```bash
   python3 script.py
   ```

3. **Selección de versión y región**:
   Sigue las instrucciones del menú de gestión para instalar la versión deseada y configurar la región de Ngrok.

4. **Actualización automática**:
   El script se encargará de verificar y descargar la última versión disponible automáticamente.

## Archivos importantes
- **.gitignore**: Se genera automáticamente para excluir archivos sensibles o temporales del repositorio.
- **servidor.py**: El script descargará automáticamente este archivo si es necesario, pero se eliminará previamente si ya existe.

## Advertencia
> **No modifiques la sección del código marcada como "No toques nada de aquí para abajo".** Alterar esta sección podría dañar el funcionamiento del script.

## Contribuciones
¡Las contribuciones son bienvenidas! Por favor, crea un *fork* del proyecto, realiza tus cambios y envía un *pull request*.

---

### Contacto
Para preguntas o reportar errores, abre un *issue* en este repositorio.
