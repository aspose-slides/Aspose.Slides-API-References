---
title: DrawingGuidesCollection
second_title: Referencia de la API Java de Aspose.Slides para Android
description: Representa una colección de las guías de dibujo ajustables.
type: docs
url: /es/com.aspose.slides/drawingguidescollection/
---
**Herencia:**
java.lang.Object

**Todas las interfaces implementadas:**
[com.aspose.slides.IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)
```
public final class DrawingGuidesCollection implements IDrawingGuidesCollection
```

Representa una colección de guías de dibujo ajustables.
## Métodos

| Método | Descripción |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Devuelve la guía de dibujo por índice. |
| [add(byte orientation, float position)](#add-byte-float-) | Agrega la guía de dibujo al final de la colección. |
| [removeAt(int index)](#removeAt-int-) | Elimina la guía de dibujo en el índice especificado. |
| [clear()](#clear--) | Elimina todos los elementos de la colección. |
| [iterator()](#iterator--) | Devuelve un enumerador que recorre la colección. |
| [iteratorJava()](#iteratorJava--) | Devuelve un iterador java para toda la colección. |
| [getCount()](#getCount--) | Devuelve el número de elementos en la colección. |
| [copyTo(IDrawingGuide[] array, int index)](#copyTo-com.aspose.slides.IDrawingGuide---int-) | Copia todos los elementos de la colección al arreglo especificado. |
### get_Item(int index) {#get-Item-int-}
```
public final IDrawingGuide get_Item(int index)
```


Devuelve la guía de dibujo por índice. Solo lectura [IDrawingGuide](../../com.aspose.slides/idrawingguide).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index | int |  |

**Devuelve:**
[IDrawingGuide](../../com.aspose.slides/idrawingguide)
### add(byte orientation, float position) {#add-byte-float-}
```
public final IDrawingGuide add(byte orientation, float position)
```


Agrega la guía de dibujo al final de la colección.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| orientation | byte | Orientación de la guía de dibujo. |
| position | float | Posición de la guía de dibujo en puntos. |

**Devuelve:**
[IDrawingGuide](../../com.aspose.slides/idrawingguide)
### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```


Elimina la guía de dibujo en el índice especificado.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index | int | Índice de la guía de dibujo que debe eliminarse. |

### clear() {#clear--}
```
public final void clear()
```


Elimina todos los elementos de la colección.

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IDrawingGuide> iterator()
```


Devuelve un enumerador que recorre la colección.

**Devuelve:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IDrawingGuide> - A IGenericEnumerator that can be used to iterate through the collection.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IDrawingGuide> iteratorJava()
```


Devuelve un iterador java para toda la colección.

**Devuelve:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IDrawingGuide> - An java.util.Iterator for the entire collection.
### getCount() {#getCount--}
```
public final int getCount()
```


Devuelve el número de elementos en la colección. Solo lectura int.

**Devuelve:**
int
### copyTo(IDrawingGuide[] array, int index) {#copyTo-com.aspose.slides.IDrawingGuide---int-}
```
public final void copyTo(IDrawingGuide[] array, int index)
```


Copia todos los elementos de la colección al arreglo especificado.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| array | [IDrawingGuide\[\]](../../com.aspose.slides/idrawingguide) | Arreglo de destino. |
| index | int | Índice inicial en el arreglo de destino. |