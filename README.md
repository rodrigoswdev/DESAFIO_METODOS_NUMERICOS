# Métodos Numéricos Web  
### Bisección • Newton–Raphson • Secante  
### Gráficas Interactivas + Exportación a Excel  
---

Este proyecto es una aplicación **HTML + JavaScript** totalmente interactiva que permite:

✔ Resolver **cualquier ecuación no lineal f(x)=0**  
✔ Aplicar los métodos:  
   - **Bisección**  
   - **Newton–Raphson**  
   - **Secante**  
✔ Graficar:
   - La función ingresada  
   - Las trayectorias de iteración de cada método  
✔ Exportar las iteraciones a un archivo **Excel (.xlsx)**  
✔ Funcionamiento completamente **local**, sin servidor  
✔ Uso de librerías externas ligeras (**Plotly.js** y **SheetJS**)  

---

## 🚀 Características Principales

### 🔢 **Resolución de ecuaciones no lineales**
El usuario puede ingresar *cualquier función* utilizando sintaxis válida de JavaScript, por ejemplo:

- `x**3 - Math.exp(0.8*x) - 20`
- `3*Math.sin(0.5*x) - 0.5*x + 2`
- `x**3 - x**2*Math.exp(-0.5*x) - 3*x + 1`
- `Math.cos(x)**2 - 0.5*x*Math.exp(0.3*x) + 5`

La aplicación evalúa la función usando **Function()**, permitiendo expresiones dinámicas.

---

## 📈 **Gráficas Interactivas**
Con **Plotly.js** se generan:

### 1️⃣ Gráfica de la función f(x)
- Permite visualizar raíces y comportamiento global.  
- Interactiva: zoom, paneo, hover, exportar a imagen.

### 2️⃣ Gráfica de trayectoria de iteración
- Para comparar el comportamiento de los métodos:  
  - Velocidad de convergencia  
  - Estabilidad  
  - Oscilaciones o divergencias  

---

## 📤 **Exportación completa a Excel**
Gracias a **SheetJS (XLSX.js)** se genera un archivo:


