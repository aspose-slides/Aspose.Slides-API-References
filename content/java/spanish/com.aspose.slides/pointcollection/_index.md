---
title: PointCollection
second_title: Referencia de API de Aspose.Slides para Java
description: Representa una colección de puntos de animación.
type: docs
url: /es/com.aspose.slides/pointcollection/
---
**Herencia:**
java.lang.Object

**Todas las interfaces implementadas:**
[com.aspose.slides.IPointCollection](../../com.aspose.slides/ipointcollection)
```
public class PointCollection implements IPointCollection
```

Representa una colección de puntos de animación.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [PointCollection()](#PointCollection--) |  |
## Métodos

| Método | Descripción |
| --- | --- |
| [getCount()](#getCount--) | Devuelve el número de puntos en la colección. |
| [get_Item(int index)](#get-Item-int-) | Devuelve un punto en el índice especificado. |
| [iterator()](#iterator--) | Devuelve un enumerador que itera a través de la colección. |
| [iteratorJava()](#iteratorJava--) | Devuelve un iterador java para toda la colección. |
### PointCollection() {#PointCollection--}
```
public PointCollection()
```

### getCount() {#getCount--}
```
public final int getCount()
```

Devuelve el número de puntos en la colección. int de solo lectura.

**Devuelve:**
int
### get_Item(int index) {#get-Item-int-}
```
public final IPoint get_Item(int index)
```

Devuelve un punto en el índice especificado.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index | int | Índice del elemento. |

**Devuelve:**
[IPoint](../../com.aspose.slides/ipoint) - El objeto [IPoint](../../com.aspose.slides/ipoint).
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IPoint> iterator()
```

Devuelve un enumerador que itera a través de la colección.

**Devuelve:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IPoint> - Un IGenericEnumerator que puede usarse para iterar a través de la colección.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IPoint> iteratorJava()
```

Devuelve un iterador java para toda la colección.

**Devuelve:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IPoint> - Un java.util.Iterator para toda la colección.