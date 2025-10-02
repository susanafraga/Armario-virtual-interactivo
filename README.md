# Smart Wardrobe  

## Descripción del problema  
La elección diaria de un *outfit* puede parecer una tarea simple, pero para muchas personas supone dedicar tiempo y esfuerzo: revisar el clima, pensar en la ocasión (trabajo, universidad, fin de semana, cena…), considerar el estado de ánimo o buscar armonía en colores y estilos.
En la práctica, gran parte de esta información se encuentra dispersa en la propia mente del usuario, lo que obliga a tener en cuenta múltiples factores de manera no estructurada. A esto se suma la necesidad de consultar aplicaciones externas, como la del tiempo, para completar la decisión. El resultado suele ser un proceso lento y poco eficiente.  

**Smart Wardrobe** propone un prototipo de aplicación que actúe como un “armario inteligente”, capaz de recomendar outfits combinando un catálogo digital de prendas con datos de contexto (meteorología, tipo de día, ocasión, preferencias del usuario).  

---

## Objetivos principales  
- Digitalizar un catálogo de ropa online con atributos básicos (tipo, color, formalidad, temporada).  
- Integrar datos externos de contexto como el clima (temperatura, lluvia, viento) y la ocasión (día laboral/fin de semana, día/noche).  
- Permitir que el usuario seleccione parámetros personales (estado de ánimo, preferencias de estilo o color).  
- Desarrollar un motor de reglas de recomendación que sugiera combinaciones de outfits adaptadas al contexto.  
- Presentar las recomendaciones en una interfaz clara, mostrando varias opciones junto con explicaciones sencillas.  

---

## Plan inicial de trabajo  

### Fase 1 – Diseño del prototipo  
- Definir modelo de datos para prendas (tipo, color, temporada, etc.).  
- Seleccionar catálogo digital de ropa online (dataset abierto o API).  

### Fase 2 – Integración de contexto  
- Conectar con API meteorológica (ej. Open-Meteo).  
- Definir inputs de usuario (estado de ánimo, día/ocasión).  

### Fase 3 – Motor de recomendación  
- Implementar reglas duras (restricciones: clima, formalidad, etc.).  
- Definir criterios de afinidad (colores, estilos, mood).  
- Generar recomendaciones automáticas (top-N outfits).  

### Fase 4 – Interfaz y visualización  
- Desarrollar interfaz para mostrar las sugerencias de outfits.  
- Incluir explicaciones de por qué se recomienda cada combinación.
- Visualizaciones pertinentes  
 
