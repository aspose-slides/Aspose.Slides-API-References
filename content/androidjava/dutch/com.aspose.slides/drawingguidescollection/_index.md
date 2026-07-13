---
title: DrawingGuidesCollection
second_title: Aspose.Slides voor Android via Java API-referentie
description: Stelt een collectie van de aanpasbare tekengidsen voor.
type: docs
url: /nl/com.aspose.slides/drawingguidescollection/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.slides.IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)
```
public final class DrawingGuidesCollection implements IDrawingGuidesCollection
```

Stelt een collectie van de aanpasbare tekengidsen voor.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Retourneert de tekengids op index. |
| [add(byte orientation, float position)](#add-byte-float-) | Voegt de tekengids toe aan het einde van de collectie. |
| [removeAt(int index)](#removeAt-int-) | Verwijdert de tekengids op de opgegeven index. |
| [clear()](#clear--) | Verwijdert alle elementen uit de collectie. |
| [iterator()](#iterator--) | Retourneert een enumerator die door de collectie itereert. |
| [iteratorJava()](#iteratorJava--) | Retourneert een java-iterator voor de volledige collectie. |
| [getCount()](#getCount--) | Retourneert het aantal elementen in de collectie. |
| [copyTo(IDrawingGuide[] array, int index)](#copyTo-com.aspose.slides.IDrawingGuide---int-) | Kopieert alle elementen van de collectie naar de opgegeven array. |
### get_Item(int index) {#get-Item-int-}
```
public final IDrawingGuide get_Item(int index)
```

Retourneert de tekengids op index. Alleen-lezen [IDrawingGuide](../../com.aspose.slides/idrawingguide).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| index | int |  |

**Retour:**
[IDrawingGuide](../../com.aspose.slides/idrawingguide)
### add(byte orientation, float position) {#add-byte-float-}
```
public final IDrawingGuide add(byte orientation, float position)
```

Voegt de tekengids toe aan het einde van de collectie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| orientation | byte | Oriëntatie van de tekengids. |
| position | float | Positie van de tekengids in points. |

**Retour:**
[IDrawingGuide](../../com.aspose.slides/idrawingguide)
### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

Verwijdert de tekengids op de opgegeven index.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| index | int | Index van de te verwijderen tekengids. |

### clear() {#clear--}
```
public final void clear()
```

Verwijdert alle elementen uit de collectie.

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IDrawingGuide> iterator()
```

Retourneert een enumerator die door de collectie itereert.

**Retour:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IDrawingGuide> - Een IGenericEnumerator die kan worden gebruikt om door de collectie te itereren.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IDrawingGuide> iteratorJava()
```

Retourneert een java-iterator voor de volledige collectie.

**Retour:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IDrawingGuide> - Een java.util.Iterator voor de volledige collectie.
### getCount() {#getCount--}
```
public final int getCount()
```

Retourneert het aantal elementen in de collectie. Alleen-lezen int.

**Retour:**
int
### copyTo(IDrawingGuide[] array, int index) {#copyTo-com.aspose.slides.IDrawingGuide---int-}
```
public final void copyTo(IDrawingGuide[] array, int index)
```

Kopieert alle elementen van de collectie naar de opgegeven array.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| array | [IDrawingGuide\[\]](../../com.aspose.slides/idrawingguide) | Doel-array. |
| index | int | Startindex in de doel-array. |