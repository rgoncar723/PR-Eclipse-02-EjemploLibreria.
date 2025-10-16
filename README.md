# PR-Eclipse-02-EjemploLibreria.
ENDES 1º DAM; 2025/2026
# REFLEXIÓN
1. ¿Qué pasa si exporto el proyecto a un .zip y se lo paso a un amigo o me lo llevo a otro ordenador?
Solo funcionará en otro ordenador si las librerías están dentro del proyecto exportado.
2. ¿Qué pasa si eliminas el archivo .jar de la carpeta lib?
Ya no encontrará las clases y métodos de esa librería. Verás errores rojos en el código.
Porque el proyecto tiene una referencia al archivo .jar, pero el archivo ya no existe.
Eclipse busca ese .jar para compilar, y al no encontrarlo, rompe la referencia del Build Path.
3. Si agregas la librería con Add External JARs..., ¿qué pasa?
Eclipse no copia el .jar dentro del proyecto. Solo crea una referencia absoluta al lugar donde está el archivo en tu disco.
4. ¿Por qué no es recomendable usar Add External JARs… en proyectos que vas a compartir?
Porque el proyecto depende de rutas locales de tu ordenador. Cuando alguien más lo abre, esas rutas ya no existen.
   
   
