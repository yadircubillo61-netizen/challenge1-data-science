# 📊 Análisis de Tiendas - Recomendación para el Sr. Juan

## 🎯 Propósito del análisis
Este proyecto busca ayudar al **Sr. Juan** a decidir en qué tienda debería vender sus productos.  
Se analizaron cuatro tiendas distintas tomando en cuenta factores como los ingresos totales, las categorías más vendidas, las calificaciones promedio de los clientes y el costo de envío.  
El objetivo fue identificar la tienda más conveniente para vender, no necesariamente la más rentable, sino la que ofrezca el mejor equilibrio general.

---

## 🧩 Estructura del proyecto
- **analisis_tiendas.ipynb** → Notebook principal con todo el análisis y las visualizaciones.  
- **dataset/** → Carpeta que contiene los archivos CSV con los datos de las tiendas.  
- **README.md** → Archivo con la descripción general del proyecto y las conclusiones.

---

## 📈 Ejemplos de gráficos e insights
En el notebook se generaron varios gráficos con **Matplotlib** y **Pandas**, entre ellos:
- Gráfico de pastel para comparar las categorías más vendidas entre las cuatro tiendas.  
- Gráfico de dispersión para observar el costo de envío promedio por tienda y ciudad.  
- Gráfico de barras horizontales para comparar las calificaciones promedio de los clientes.  

Tras analizar los resultados, se concluyó que **la Tienda 1** es la mejor opción para el Sr. Juan, por su buena relación entre ingresos, satisfacción del cliente y costos de envío.

---

## ⚙️ Instrucciones para ejecutar el notebook
1. Abre el archivo `analisis_tiendas.ipynb` en **Google Colab** o **Jupyter Notebook**.  
2. Instala las librerías necesarias:
   ```python
   pip install pandas matplotlib seaborn numpy
