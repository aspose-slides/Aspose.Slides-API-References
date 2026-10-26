---
title: PointCollection
second_title: Aspose.Slides voor Android via Java API-referentie
description: Stelt een verzameling animatiepunten voor.
type: docs
url: /nl/com.aspose.slides/pointcollection/
---
**Erfenis:**
java.lang.Object

**Alle geïmplementeerde interfaces:**
[com.aspose.slides.IPointCollection](../../com.aspose.slides/ipointcollection)
```
public class PointCollection implements IPointCollection
```

Stelt een verzameling animatiepunten voor.
## Constructoren

| Constructor | Description |
| --- | --- |
| [PointCollection()](#PointCollection--) |  |
## Methoden

| Method | Description |
| --- | --- |
| [getCount()](#getCount--) | Retourneert het aantal punten in de collectie. |
| [get_Item(int index)](#get-Item-int-) | Retourneert een punt op de opgegeven index. |
| [iterator()](#iterator--) | Retourneert een enumerator die door de collectie itereert. |
| [iteratorJava()](#iteratorJava--) | Retourneert een java-iterator voor de gehele collectie. |
### PointCollection() {#PointCollection--}
```
public PointCollection()
```


### getCount() {#getCount--}
```
public final int getCount()
```


Retourneert het aantal punten in de collectie. Alleen-lezen int.

**Retour:**
int
### get_Item(int index) {#get-Item-int-}
```
public final IPoint get_Item(int index)
```


Retourneert een punt op de opgegeven index.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| index | int | Index van element. |

**Retour:**
[IPoint](../../com.aspose.slides/ipoint) - Het [IPoint](../../com.aspose.slides/ipoint) object.
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IPoint> iterator()
```


Retourneert een enumerator die door de collectie itereert.

**Retour:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IPoint> - Een IGenericEnumerator die kan worden gebruikt om door de collectie te itereren.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IPoint> iteratorJava()
```


Retourneert een java-iterator voor de gehele collectie.

**Retour:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IPoint> - Een java.util.Iterator voor de gehele collectie.