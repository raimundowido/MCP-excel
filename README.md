# Excel Analysis MCP

Servidor de Model Context Protocol (MCP) que conecta la Inteligencia Artificial con archivos de Excel locales para facilitar el análisis exploratorio de datos académicos.

## Requisitos
- Node.js instalado en el computador.
- Dependencias del proyecto (`npm install`).

## Instalación paso a paso
1. Clonar este repositorio.
2. Ejecutar `npm install` para instalar las dependencias (incluyendo `xlsx`).
3. Compilar el proyecto con `npm run build`.

## Lista de Herramientas
- `leer_info_excel`: Inspecciona las hojas de un archivo y muestra las primeras filas.
- `analizar_columna_excel`: Obtiene estadísticas descriptivas (suma, promedio, máximo, mínimo).
- `filtrar_datos_excel`: Busca y filtra filas bajo criterios específicos.

## Ejemplo de Uso
"Por favor, analiza el archivo `datos_investigacion.xlsx` en la hoja 'Muestra1' y calcúlame el promedio y máximo de la columna 'Calificaciones'."
