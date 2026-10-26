---
title: SectionCollection
second_title: Aspose.Slides voor Java API-referentie
description: Stelt een verzameling van secties voor.
type: docs
url: /nl/com.aspose.slides/sectioncollection/
---
**Overerving:**
java.lang.Object, com.aspose.slides.DomObject

**Alle geïmplementeerde interfaces:**
[com.aspose.slides.ISectionCollection](../../com.aspose.slides/isectioncollection)
```
public final class SectionCollection extends DomObject<Presentation> implements ISectionCollection
```

Stelt een verzameling van secties voor.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Haalt het element op op de opgegeven index. |
| [addSection(String name, ISlide startedFromSlide)](#addSection-java.lang.String-com.aspose.slides.ISlide-) | Voegt een sectie met dia's toe die is gestart vanaf een specifieke dia. |
| [appendEmptySection(String name)](#appendEmptySection-java.lang.String-) | Voegt een lege sectie toe aan het einde van de verzameling. |
| [addEmptySection(String name, int index)](#addEmptySection-java.lang.String-int-) | Voegt een lege sectie toe op de opgegeven positie in de verzameling. |
| [size()](#size--) | Haalt het aantal elementen op dat daadwerkelijk in de verzameling zit. |
| [indexOf(ISection section)](#indexOf-com.aspose.slides.ISection-) | Retourneert een index van de opgegeven sectie in de verzameling. |
| [removeSectionWithSlides(ISection section)](#removeSectionWithSlides-com.aspose.slides.ISection-) | Verwijdert de sectie en de dia's die in de sectie zitten. |
| [removeSection(ISection section)](#removeSection-com.aspose.slides.ISection-) | Verwijdert de sectie. |
| [reorderSectionWithSlides(ISection section, int index)](#reorderSectionWithSlides-com.aspose.slides.ISection-int-) | Verplaatst de sectie en de bijbehorende dia's van de verzameling naar de opgegeven positie. |
| [clear()](#clear--) | Verwijdert alle secties uit de verzameling. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Kopieert de volledige verzameling naar de opgegeven array. |
| [isSynchronized()](#isSynchronized--) | Retourneert een waarde die aangeeft of de toegang tot de verzameling gesynchroniseerd is (thread-safe). |
| [getSyncRoot()](#getSyncRoot--) | Retourneert een synchronisatiewortel. |
| [iterator()](#iterator--) | Retourneert een enumerator die door de verzameling iterereert. |
| [iteratorJava()](#iteratorJava--) | Retourneert een java-iterator voor de volledige verzameling. |
### get_Item(int index) {#get-Item-int-}
```
public final ISection get_Item(int index)
```

Haalt het element op op de opgegeven index. Alleen-lezen [ISection](../../com.aspose.slides/isection).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| index | int |  |

**Retourwaarde:**
[ISection](../../com.aspose.slides/isection)
### addSection(String name, ISlide startedFromSlide) {#addSection-java.lang.String-com.aspose.slides.ISlide-}
```
public final ISection addSection(String name, ISlide startedFromSlide)
```

Voegt een sectie met dia's toe die is gestart vanaf een specifieke dia.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| name | java.lang.String | Naam van de sectie |
| startedFromSlide | [ISlide](../../com.aspose.slides/islide) | Eerste dia van de sectie |

**Retourwaarde:**
[ISection](../../com.aspose.slides/isection) - Toegevoegde sectie.
### appendEmptySection(String name) {#appendEmptySection-java.lang.String-}
```
public final ISection appendEmptySection(String name)
```

Voegt een lege sectie toe aan het einde van de verzameling.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| name | java.lang.String | Naam van de sectie |

**Retourwaarde:**
[ISection](../../com.aspose.slides/isection) - Toegevoegde sectie.
### addEmptySection(String name, int index) {#addEmptySection-java.lang.String-int-}
```
public final ISection addEmptySection(String name, int index)
```

Voegt een lege sectie toe op de opgegeven positie in de verzameling.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| name | java.lang.String | Naam van de sectie |
| index | int | Index van de nieuwe sectie. |

**Retourwaarde:**
[ISection](../../com.aspose.slides/isection) - Toegevoegde sectie.
### size() {#size--}
```
public final int size()
```

Haalt het aantal elementen op dat daadwerkelijk in de verzameling zit. Alleen-lezen int.

**Retourwaarde:**
int
### indexOf(ISection section) {#indexOf-com.aspose.slides.ISection-}
```
public final int indexOf(ISection section)
```

Retourneert een index van de opgegeven sectie in de verzameling.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| section | [ISection](../../com.aspose.slides/isection) | Sectie om te vinden. |

**Retourwaarde:**
int - Index van een sectie of -1 als de sectie niet uit deze verzameling komt.
### removeSectionWithSlides(ISection section) {#removeSectionWithSlides-com.aspose.slides.ISection-}
```
public final void removeSectionWithSlides(ISection section)
```

Verwijdert de sectie en de dia's die in de sectie zitten.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| section | [ISection](../../com.aspose.slides/isection) | De sectie die uit de verzameling moet worden verwijderd. |

### removeSection(ISection section) {#removeSection-com.aspose.slides.ISection-}
```
public final void removeSection(ISection section)
```

Verwijdert de sectie. Dia's die in de sectie zitten, worden samengevoegd met de vorige sectie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| section | [ISection](../../com.aspose.slides/isection) | De sectie die uit de verzameling moet worden verwijderd. |

### reorderSectionWithSlides(ISection section, int index) {#reorderSectionWithSlides-com.aspose.slides.ISection-int-}
```
public final void reorderSectionWithSlides(ISection section, int index)
```

Verplaatst de sectie en de bijbehorende dia's van de verzameling naar de opgegeven positie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| section | [ISection](../../com.aspose.slides/isection) | Sectie om te verplaatsen. |
| index | int | Doel-index. |

### clear() {#clear--}
```
public final void clear()
```

Verwijdert alle secties uit de verzameling.

### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

Kopieert de volledige verzameling naar de opgegeven array.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Doel-array |
| index | int | Index in de doel-array. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

Retourneert een waarde die aangeeft of de toegang tot de verzameling gesynchroniseerd is (thread-safe). Alleen-lezen boolean.

**Retourwaarde:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

Retourneert een synchronisatiewortel. Alleen-lezen Object.

**Retourwaarde:**
java.lang.Object
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<ISection> iterator()
```

Retourneert een enumerator die door de verzameling iterereert.

**Retourwaarde:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ISection> - Een IGenericEnumerator die kan worden gebruikt om door de verzameling te itereren.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<ISection> iteratorJava()
```

Retourneert een java-iterator voor de volledige verzameling.

**Retourwaarde:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ISection> - Een java.util.Iterator voor de volledige verzameling.