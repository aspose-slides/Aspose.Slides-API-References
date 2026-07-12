---
title: TrendlineCollection
second_title: Aspose.Slides para Android mediante la Referencia de la API Java
description: Representa una colección de Trendline
type: docs
url: /es/com.aspose.slides/trendlinecollection/
---
**Herencia:**
java.lang.Object, com.aspose.slides.DomObject

**Todas las interfaces implementadas:**
[com.aspose.slides.ITrendlineCollection](../../com.aspose.slides/itrendlinecollection)
```
public class TrendlineCollection extends DomObject<ChartSeries> implements ITrendlineCollection
```

Representa una colección de Trendline
## Métodos

| Método | Descripción |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Obtiene el elemento en el índice especificado. |
| [add(int trendlineType)](#add-int-) | Añade el nuevo Trendline al final de la colección y lo devuelve. |
| [remove(ITrendline value)](#remove-com.aspose.slides.ITrendline-) | Elimina el valor especificado. |
| [iterator()](#iterator--) | Devuelve un enumerador que recorre la colección. |
| [iteratorJava()](#iteratorJava--) | Devuelve un iterador java para toda la colección. |
| [getCount()](#getCount--) | Obtiene el número de elementos realmente contenidos en la colección. |
### get_Item(int index) {#get-Item-int-}
```
public final ITrendline get_Item(int index)
```


Obtiene el elemento en el índice especificado. Solo lectura [Trendline](../../com.aspose.slides/trendline).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index | int |  |

**Devuelve:**
[ITrendline](../../com.aspose.slides/itrendline)
### add(int trendlineType) {#add-int-}
```
public final ITrendline add(int trendlineType)
```


Añade el nuevo Trendline al final de la colección y lo devuelve.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| trendlineType | int |  |

**Devuelve:**
[ITrendline](../../com.aspose.slides/itrendline)
### remove(ITrendline value) {#remove-com.aspose.slides.ITrendline-}
```
public final void remove(ITrendline value)
```


Elimina el valor especificado.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [ITrendline](../../com.aspose.slides/itrendline) |  |

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<ITrendline> iterator()
```


Devuelve un enumerador que recorre la colección.

**Devuelve:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ITrendline> - Un IGenericEnumerator que puede usarse para recorrer la colección.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<ITrendline> iteratorJava()
```


Devuelve un iterador java para toda la colección.

**Devuelve:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ITrendline> - Un java.util.Iterator para toda la colección.
### getCount() {#getCount--}
```
public final int getCount()
```


Obtiene el número de elementos realmente contenidos en la colección. int de solo lectura.

**Devuelve:**
int