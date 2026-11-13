---
title: CachedChartValue
second_title: Aspose.Slides para la referencia de la API de Java
description: Representa un valor de gráfico almacenado en caché, por ejemplo X, Y, tamaño de burbuja o el valor principal.
type: docs
url: /es/com.aspose.slides/cachedchartvalue/
---
**Herencia:**
java.lang.Object

**Todas las interfaces implementadas:**
[com.aspose.slides.ICachedChartValue](../../com.aspose.slides/icachedchartvalue)
```
public class CachedChartValue implements ICachedChartValue
```

Representa un valor de gráfico almacenado en caché (p. ej., X, Y, tamaño de burbuja o el valor principal).
## Constructores

| Constructor | Descripción |
| --- | --- |
| [CachedChartValue()](#CachedChartValue--) |  |
## Métodos

| Método | Descripción |
| --- | --- |
| [toString()](#toString--) | Devuelve una representación en forma de cadena del valor almacenado en caché. |
| [toDouble()](#toDouble--) | Convierte el valor almacenado en caché a un double. |
| [getData()](#getData--) | Obtiene el objeto de datos almacenado en caché. |
### CachedChartValue() {#CachedChartValue--}
```
public CachedChartValue()
```


### toString() {#toString--}
```
public String toString()
```


Devuelve una representación en forma de cadena del valor almacenado en caché.

**Devuelve:**
java.lang.String
### toDouble() {#toDouble--}
```
public final double toDouble()
```


Convierte el valor almacenado en caché a un double.

**Devuelve:**
double - La representación numérica, o Double.NaN si Data (\#getData.getData/\#setData(Object).setData(Object)) es nulo o no se puede convertir a un double.
### getData() {#getData--}
```
public final Object getData()
```


Obtiene el objeto de datos almacenado en caché. Solo lectura  Object .

**Devuelve:**
java.lang.Object