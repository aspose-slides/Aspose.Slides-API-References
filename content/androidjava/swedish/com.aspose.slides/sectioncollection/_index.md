---
title: SectionCollection
second_title: Aspose.Slides för Android via Java API-referens
description: Representerar en samling sektioner.
type: docs
url: /sv/com.aspose.slides/sectioncollection/
---
**Arv:**
java.lang.Object, com.aspose.slides.DomObject

**Alla implementerade gränssnitt:**
[com.aspose.slides.ISectionCollection](../../com.aspose.slides/isectioncollection)
```
public final class SectionCollection extends DomObject<Presentation> implements ISectionCollection
```

Representerar en samling sektioner.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Hämtar elementet på det angivna indexet. |
| [addSection(String name, ISlide startedFromSlide)](#addSection-java.lang.String-com.aspose.slides.ISlide-) | Lägg till avsnitt av bilder som startar från en specifik bild. |
| [appendEmptySection(String name)](#appendEmptySection-java.lang.String-) | Lägg till ett tomt avsnitt i slutet av samlingen. |
| [addEmptySection(String name, int index)](#addEmptySection-java.lang.String-int-) | Lägg till ett tomt avsnitt på angiven position i samlingen. |
| [size()](#size--) | Hämtar antalet element som faktiskt finns i samlingen. |
| [indexOf(ISection section)](#indexOf-com.aspose.slides.ISection-) | Returnerar ett index för det angivna avsnittet i samlingen. |
| [removeSectionWithSlides(ISection section)](#removeSectionWithSlides-com.aspose.slides.ISection-) | Ta bort avsnittet och bilderna som finns i avsnittet. |
| [removeSection(ISection section)](#removeSection-com.aspose.slides.ISection-) | Ta bort avsnitt. |
| [reorderSectionWithSlides(ISection section, int index)](#reorderSectionWithSlides-com.aspose.slides.ISection-int-) | Flyttar avsnittet och dess bilder från samlingen till den angivna positionen. |
| [clear()](#clear--) | Tar bort alla avsnitt från samlingen. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Kopierar hela samlingen till den angivna arrayen. |
| [isSynchronized()](#isSynchronized--) | Returnerar ett värde som indikerar om åtkomst till samlingen är synkroniserad (trådsäker). |
| [getSyncRoot()](#getSyncRoot--) | Returnerar ett synkroniseringsrot. |
| [iterator()](#iterator--) | Returnerar en enumerator som itererar genom samlingen. |
| [iteratorJava()](#iteratorJava--) | Returnerar en java-iterator för hela samlingen. |
### get_Item(int index) {#get-Item-int-}
```
public final ISection get_Item(int index)
```

Hämtar elementet på det angivna indexet. Läs-endast [ISection](../../com.aspose.slides/isection).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | int |  |

**Returnerar:**
[ISection](../../com.aspose.slides/isection)
### addSection(String name, ISlide startedFromSlide) {#addSection-java.lang.String-com.aspose.slides.ISlide-}
```
public final ISection addSection(String name, ISlide startedFromSlide)
```

Lägg till avsnitt av bilder som startar från en specifik bild.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| name | java.lang.String | Namnet på avsnittet |
| startedFromSlide | [ISlide](../../com.aspose.slides/islide) | Första bild i avsnittet |

**Returnerar:**
[ISection](../../com.aspose.slides/isection) - Lagt till avsnitt.
### appendEmptySection(String name) {#appendEmptySection-java.lang.String-}
```
public final ISection appendEmptySection(String name)
```

Lägg till ett tomt avsnitt i slutet av samlingen.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| name | java.lang.String | Namnet på avsnittet |

**Returnerar:**
[ISection](../../com.aspose.slides/isection) - Lagt till avsnitt.
### addEmptySection(String name, int index) {#addEmptySection-java.lang.String-int-}
```
public final ISection addEmptySection(String name, int index)
```

Lägg till ett tomt avsnitt på angiven position i samlingen.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| name | java.lang.String | Namnet på avsnittet |
| index | int | Index för det nya avsnittet. |

**Returnerar:**
[ISection](../../com.aspose.slides/isection) - Lagt till avsnitt.
### size() {#size--}
```
public final int size()
```

Hämtar antalet element som faktiskt finns i samlingen. Läs-endast int.

**Returnerar:**
int
### indexOf(ISection section) {#indexOf-com.aspose.slides.ISection-}
```
public final int indexOf(ISection section)
```

Returnerar ett index för det angivna avsnittet i samlingen.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| section | [ISection](../../com.aspose.slides/isection) | Avsnitt att hitta. |

**Returnerar:**
int - Index för ett avsnitt eller -1 om avsnittet inte finns i den här samlingen.
### removeSectionWithSlides(ISection section) {#removeSectionWithSlides-com.aspose.slides.ISection-}
```
public final void removeSectionWithSlides(ISection section)
```

Ta bort avsnittet och bilderna som finns i avsnittet.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| section | [ISection](../../com.aspose.slides/isection) | Avsnittet att ta bort från samlingen. |
### removeSection(ISection section) {#removeSection-com.aspose.slides.ISection-}
```
public final void removeSection(ISection section)
```

Ta bort avsnitt. Bilder som finns i avsnittet kommer att slås ihop med föregående avsnitt.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| section | [ISection](../../com.aspose.slides/isection) | Avsnittet att ta bort från samlingen. |
### reorderSectionWithSlides(ISection section, int index) {#reorderSectionWithSlides-com.aspose.slides.ISection-int-}
```
public final void reorderSectionWithSlides(ISection section, int index)
```

Flyttar avsnittet och dess bilder från samlingen till den angivna positionen.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| section | [ISection](../../com.aspose.slides/isection) | Avsnitt att flytta. |
| index | int | Målindex. |
### clear() {#clear--}
```
public final void clear()
```

Tar bort alla avsnitt från samlingen.
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

Kopierar hela samlingen till den angivna arrayen.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Målararray |
| index | int | Index i målararrayen. |
### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

Returnerar ett värde som indikerar om åtkomst till samlingen är synkroniserad (trådsäker). Läs-endast boolean.

**Returnerar:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

Returnerar ett synkroniseringsrot. Läs-endast java.lang.Object.

**Returnerar:**
java.lang.Object
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<ISection> iterator()
```

Returnerar en enumerator som itererar genom samlingen.

**Returnerar:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ISection> - En IGenericEnumerator som kan användas för att iterera genom samlingen.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<ISection> iteratorJava()
```

Returnerar en java-iterator för hela samlingen.

**Returnerar:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ISection> - En java.util.Iterator för hela samlingen.