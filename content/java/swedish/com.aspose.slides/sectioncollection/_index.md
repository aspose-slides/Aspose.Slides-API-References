---
title: SectionCollection
second_title: Aspose.Slides för Java API-referens
description: Representerar en samling av sektioner.
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

Representerar en samling av sektioner.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Hämtar elementet på det angivna indexet. |
| [addSection(String name, ISlide startedFromSlide)](#addSection-java.lang.String-com.aspose.slides.ISlide-) | Lägger till ett avsnitt för bildspel som startar från en specifik bild. |
| [appendEmptySection(String name)](#appendEmptySection-java.lang.String-) | Lägg till tomt avsnitt i slutet av samlingen. |
| [addEmptySection(String name, int index)](#addEmptySection-java.lang.String-int-) | Lägg till tomt avsnitt på angiven position i samlingen. |
| [size()](#size--) | Hämtar antalet element som faktiskt finns i samlingen. |
| [indexOf(ISection section)](#indexOf-com.aspose.slides.ISection-) | Returnerar indexet för det angivna avsnittet i samlingen. |
| [removeSectionWithSlides(ISection section)](#removeSectionWithSlides-com.aspose.slides.ISection-) | Tar bort avsnittet och bilderna som finns i avsnittet. |
| [removeSection(ISection section)](#removeSection-com.aspose.slides.ISection-) | Tar bort avsnitt. |
| [reorderSectionWithSlides(ISection section, int index)](#reorderSectionWithSlides-com.aspose.slides.ISection-int-) | Flyttar avsnittet och dess bilder från samlingen till den angivna positionen. |
| [clear()](#clear--) | Tar bort alla avsnitt från samlingen. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Kopierar hela samlingen till den angivna arrayen. |
| [isSynchronized()](#isSynchronized--) | Returnerar ett värde som indikerar om åtkomst till samlingen är synkroniserad (trådsäker). |
| [getSyncRoot()](#getSyncRoot--) | Returnerar ett synkroniseringsrot. |
| [iterator()](#iterator--) | Returnerar en enumerator som itererar igenom samlingen. |
| [iteratorJava()](#iteratorJava--) | Returnerar en java-iterator för hela samlingen. |
### get_Item(int index) {#get-Item-int-}
```
public final ISection get_Item(int index)
```

Hämtar elementet på det angivna indexet. Skrivskyddad [ISection](../../com.aspose.slides/isection).

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

Lägg till ett bildspelsavsnitt som startas från en specifik bild.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| name | java.lang.String | Namn på avsnittet |
| startedFromSlide | [ISlide](../../com.aspose.slides/islide) | Första bilden i avsnittet |

**Returnerar:**
[ISection](../../com.aspose.slides/isection) - Tillagt avsnitt.
### appendEmptySection(String name) {#appendEmptySection-java.lang.String-}
```
public final ISection appendEmptySection(String name)
```

Lägg till tomt avsnitt i slutet av samlingen.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| name | java.lang.String | Namn på avsnittet |

**Returnerar:**
[ISection](../../com.aspose.slides/isection) - Tillagt avsnitt.
### addEmptySection(String name, int index) {#addEmptySection-java.lang.String-int-}
```
public final ISection addEmptySection(String name, int index)
```

Lägg till tomt avsnitt på angiven position i samlingen.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| name | java.lang.String | Namn på avsnittet |
| index | int | Index för det nya avsnittet. |

**Returnerar:**
[ISection](../../com.aspose.slides/isection) - Tillagt avsnitt.
### size() {#size--}
```
public final int size()
```

Hämtar antalet element som faktiskt finns i samlingen. Skrivskyddad int.

**Returnerar:**
int
### indexOf(ISection section) {#indexOf-com.aspose.slides.ISection-}
```
public final int indexOf(ISection section)
```

Returnerar indexet för det angivna avsnittet i samlingen.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| section | [ISection](../../com.aspose.slides/isection) | Section att hitta. |

**Returnerar:**
int - Index för ett avsnitt eller -1 om avsnittet inte är från denna samling.
### removeSectionWithSlides(ISection section) {#removeSectionWithSlides-com.aspose.slides.ISection-}
```
public final void removeSectionWithSlides(ISection section)
```

Tar bort avsnittet och bilderna som finns i avsnittet.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| section | [ISection](../../com.aspose.slides/isection) | Avsnittet att ta bort från samlingen. |

### removeSection(ISection section) {#removeSection-com.aspose.slides.ISection-}
```
public final void removeSection(ISection section)
```

Tar bort avsnittet. Bilderna i avsnittet kommer att slås ihop med föregående avsnitt.

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

Returnerar ett värde som indikerar om åtkomst till samlingen är synkroniserad (trådsäker). Skrivskyddad boolean.

**Returnerar:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

Returnerar ett synkroniseringsrot. Skrivskyddad Object.

**Returnerar:**
java.lang.Object
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<ISection> iterator()
```

Returnerar en enumerator som itererar igenom samlingen.

**Returnerar:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ISection> - En IGenericEnumerator som kan användas för att iterera genom samlingen.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<ISection> iteratorJava()
```

Returnerar en java-iterator för hela samlingen.

**Returnerar:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ISection> - En java.util.Iterator för hela samlingen.