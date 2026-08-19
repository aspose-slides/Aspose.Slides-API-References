---
title: PointCollection
second_title: Aspose.Slides för Java API-referens
description: Representerar en samling av animeringspunkter.
type: docs
url: /sv/com.aspose.slides/pointcollection/
---
**Arv:**
java.lang.Object

**Alla implementerade gränssnitt:**
[com.aspose.slides.IPointCollection](../../com.aspose.slides/ipointcollection)
```
public class PointCollection implements IPointCollection
```

Representerar en samling av animeringspunkter.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [PointCollection()](#PointCollection--) |  |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getCount()](#getCount--) | Returnerar antalet punkter i samlingen. |
| [get_Item(int index)](#get-Item-int-) | Returnerar en punkt på det angivna indexet. |
| [iterator()](#iterator--) | Returnerar en enumerator som itererar genom samlingen. |
| [iteratorJava()](#iteratorJava--) | Returnerar en java-iterator för hela samlingen. |
### PointCollection() {#PointCollection--}
```
public PointCollection()
```


### getCount() {#getCount--}
```
public final int getCount()
```


Returnerar antalet punkter i samlingen. Skrivskyddad int.

**Returnerar:**
int
### get_Item(int index) {#get-Item-int-}
```
public final IPoint get_Item(int index)
```


Returnerar en punkt på det angivna indexet.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | int | Index för elementet. |

**Returnerar:**
[IPoint](../../com.aspose.slides/ipoint) - [IPoint](../../com.aspose.slides/ipoint)-objektet.
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IPoint> iterator()
```


Returnerar en enumerator som itererar genom samlingen.

**Returnerar:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IPoint> - A IGenericEnumerator that can be used to iterate through the collection.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IPoint> iteratorJava()
```


Returnerar en java-iterator för hela samlingen.

**Returnerar:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IPoint> - An java.util.Iterator for the entire collection.