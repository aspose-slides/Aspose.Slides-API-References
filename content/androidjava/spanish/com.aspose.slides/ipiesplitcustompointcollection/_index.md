---
title: IPieSplitCustomPointCollection
second_title: Aspose.Slides para Android vía Referencia de API Java
description: Representa una colección de puntos que se dibujarán en el segundo pastel o barra de un gráfico de barra-sobre-pastel o pastel-sobre-pastel con una división personalizada.
type: docs
url: /es/com.aspose.slides/ipiesplitcustompointcollection/
---
**Todas las interfaces implementadas:**
com.aspose.ms.System.Collections.Generic.IGenericCollection
```
public interface IPieSplitCustomPointCollection extends System.Collections.Generic.IGenericCollection<IChartDataPoint>
```

Representa una colección de puntos que se dibujarán en el segundo pastel o barra de un gráfico de barra-sobre-pastel o pastel-sobre-pastel con una división personalizada.
## Métodos

| Método | Descripción |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Devuelve el punto de datos del gráfico por índice. |
| [add(int dataPointIndex)](#add-int-) | Agrega un punto de datos por su índice en la colección de puntos de la serie principal. |
| [remove(int dataPointIndex)](#remove-int-) | Elimina el elemento de la colección por su índice en la colección de puntos de la serie principal. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IChartDataPoint get_Item(int index)
```


Devuelve el punto de datos del gráfico por índice.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index | int | Índice del punto de datos. |

**Devuelve:**
[IChartDataPoint](../../com.aspose.slides/ichartdatapoint) - Punto de datos del gráfico.
### add(int dataPointIndex) {#add-int-}
```
public abstract void add(int dataPointIndex)
```


Agrega un punto de datos por su índice en la colección de puntos de la serie principal.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| dataPointIndex | int | Índice del punto de datos en la colección de puntos de la serie principal. |

### remove(int dataPointIndex) {#remove-int-}
```
public abstract void remove(int dataPointIndex)
```


Elimina el elemento de la colección por su índice en la colección de puntos de la serie principal.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| dataPointIndex | int | Índice del punto de datos en la colección de puntos de la serie principal.. |