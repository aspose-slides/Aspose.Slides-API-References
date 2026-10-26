---
title: DrawingGuidesCollection
second_title: Aspose.Slides för Android via Java API-referens
description: Representerar en samling av de justerbara ritguiderna.
type: docs
url: /sv/com.aspose.slides/drawingguidescollection/
---
**Arv:**
java.lang.Object

**Alla implementerade gränssnitt:**
[com.aspose.slides.IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)
```
public final class DrawingGuidesCollection implements IDrawingGuidesCollection
```

Representerar en samling av justerbara ritguider.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Returnerar ritguiden efter index. |
| [add(byte orientation, float position)](#add-byte-float-) | Lägger till ritguiden i slutet av samlingen. |
| [removeAt(int index)](#removeAt-int-) | Tar bort ritguiden på det angivna indexet. |
| [clear()](#clear--) | Tar bort alla element från samlingen. |
| [iterator()](#iterator--) | Returnerar en enumerator som itererar igenom samlingen. |
| [iteratorJava()](#iteratorJava--) | Returnerar en java-iterator för hela samlingen. |
| [getCount()](#getCount--) | Returnerar antalet element i samlingen. |
| [copyTo(IDrawingGuide[] array, int index)](#copyTo-com.aspose.slides.IDrawingGuide---int-) | Kopierar alla element från samlingen till den angivna arrayen. |
### get_Item(int index) {#get-Item-int-}
```
public final IDrawingGuide get_Item(int index)
```


Returnerar ritguiden efter index. Skrivskyddad [IDrawingGuide](../../com.aspose.slides/idrawingguide).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | int |  |

**Returnerar:**
[IDrawingGuide](../../com.aspose.slides/idrawingguide)
### add(byte orientation, float position) {#add-byte-float-}
```
public final IDrawingGuide add(byte orientation, float position)
```


Lägger till ritguiden i slutet av samlingen.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| orientation | byte | Orientering av ritguiden. |
| position | float | Position för ritguiden i punkter. |

**Returnerar:**
[IDrawingGuide](../../com.aspose.slides/idrawingguide)
### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```


Tar bort ritguiden på det angivna indexet.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | int | Index för den ritguide som ska raderas. |

### clear() {#clear--}
```
public final void clear()
```


Tar bort alla element från samlingen.

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IDrawingGuide> iterator()
```


Returnerar en enumerator som itererar igenom samlingen.

**Returnerar:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IDrawingGuide> - A IGenericEnumerator that can be used to iterate through the collection.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IDrawingGuide> iteratorJava()
```


Returnerar en java-iterator för hela samlingen.

**Returnerar:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IDrawingGuide> - An java.util.Iterator for the entire collection.
### getCount() {#getCount--}
```
public final int getCount()
```


Returnerar antalet element i samlingen. Skrivskyddad int.

**Returnerar:**
int
### copyTo(IDrawingGuide[] array, int index) {#copyTo-com.aspose.slides.IDrawingGuide---int-}
```
public final void copyTo(IDrawingGuide[] array, int index)
```


Kopierar alla element från samlingen till den angivna arrayen.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| array | [IDrawingGuide\[\]](../../com.aspose.slides/idrawingguide) | Målarray. |
| index | int | Startindex i målarrayen. |