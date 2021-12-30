---
marp: true
footer: 'Regresión Lineal'
paginate: true


title: "Regresión Lineal"
author: "Palazzo Tomas Alejandro"

---

# Regresión Lineal Simple
<br/><br/>

## Palazzo Tomas Alejandro 
### Analisis Avanzado - FCEN - UBA

---


# Precios de propiedades

<p align="center" class='left'>
  <img width="800" height="500" src="flores_propelati.png" />
 
 
---

# Objetivo

Nuestro objetivo es poder encontrar una funcion lineal $\hat{y}$ que aproxime lo mejor posible a nuestros datos dados por $y$

Como $\hat{y}$ es lineal, entonces la vamos a escribir de la siguiente forma:
<br></br>

$$\hat{y} = \beta + \alpha x$$


---


##  $\hat{y} = \beta + \alpha x$

<br></br>

| $\alpha = 0, \beta=2$ | $\alpha = 1, \beta=0$ | $\alpha = -1, \beta=3$ |
| :---:        |     :---:      |          :---: |
| ![](grafico_vacio.png)  | ![](grafico_vacio.png)     | ![](grafico_vacio.png)    |


---
# Función de Costo

<p align="center" class='left'>
  <img width="1000" height="600" src="datos_crudos.png" />
 

---

# Función de Costo

Lo que tratamos de buscar es que nuestro modelo tenga *el menor error posible*.
Pero, ¿como calculamos ese error? Una forma es la siguiente:

<br></br>

$$\min_{\alpha, \beta}L(y, \hat{y}) = \min_{\alpha, \beta} \frac{1}{2n}\sum_{i=1}^n (y_i - \hat{y_i})^2$$


---
##  $\hat{y} = \beta + \alpha x$


<img width="600" height="500" src="datos_crudos.png" />        |  $min_{\alpha, \beta}  \frac{1}{2n}\sum_{i=1}^n (y_i - \hat{y_i})^2$ 
:-------------------------:|:-------------------------:


---

<p align="center" class='left'>
  <img width="1000" height="600" src="datos_fiteados.png" />



---

<p align="center" class='left'>
  <img width="1000" height="600" src="flores_propelati_fiteado.png" />