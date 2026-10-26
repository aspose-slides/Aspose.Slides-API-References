---
title: DrawingGuidesCollection
second_title: Aspose.Slides för Java API-referens
description: Representerar en samling av de justerbara ritningsguiderna.
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

Representerar en samling av de justerbara ritningsguiderna.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Returnerar ritningsguiden efter index. |
| [add(byte orientation, float position)](#add-byte-float-) | Lägger till ritningsguiden i slutet av samlingen. |
| [removeAt(int index)](#removeAt-int-) | Tar bort ritningsguiden på det angivna indexet. |
| [clear()](#clear--) | Tar bort alla element från samlingen. |
| [iterator()](#iterator--) | Returnerar en enumerator som itererar genom samlingen. |
| [iteratorJava()](#iteratorJava--) | Returnerar en java-iterator för hela samlingen. |
| [getCount()](#getCount--) | Returnerar antalet element i samlingen. |
| [copyTo(IDrawingGuide[] array, int index)](#copyTo-com.aspose.slides.IDrawingGuide---int-) | Copies all elements from the collection to the specified array. |
### get_Item(int index) {#get-Item-int-}
```
public final IDrawingGuide get_Item(int index)
```

Returnerar ritningsguiden efter index. Skrivskyddad [IDrawingGuide](../../com.aspose.slides/idrawingguide).

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

Lägger till ritningsguiden i slutet av samlingen.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| orientation | byte | Orientation of the drawing guide. |
| position | float | Position of the the drawing guide in points. |

**Returnerar:**
[IDrawingGuide](../../com.aspose.slides/idrawingguide)
### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

Tar bort ritningsguiden på det angivna indexet.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | int | Index of the drawing guide that should be deleted. |

### clear() {#clear--}
```
public final void clear()
```

Tar bort alla element från samlingen.

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IDrawingGuide> iterator()
```

Returnerar en enumerator som itererar genom samlingen.

**Returnerar:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IDrawingGuide> - En IGenericEnumerator som kan användas för att iterera genom samlingen.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IDrawingGuide> iteratorJava()
```

Returnerar en java-iterator för hela samlingen.

**Returnerar:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IDrawingGuide> - En java.util.Iterator för hela samlingen.
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