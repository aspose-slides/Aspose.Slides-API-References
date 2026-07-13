---
title: ISectionCollection
second_title: Aspose.Slides voor Android via Java API-referentie
description: Stelt een collectie van secties voor.
type: docs
url: /nl/com.aspose.slides/isectioncollection/
---
**Alle geïmplementeerde interfaces:**
com.aspose.slides.IGenericCollection
```
public interface ISectionCollection extends IGenericCollection<ISection>
```

Stelt een collectie van secties voor.
## Methoden

| Method | Description |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Haalt het element op op de opgegeven index. |
| [addSection(String name, ISlide startedFromSlide)](#addSection-java.lang.String-com.aspose.slides.ISlide-) | Voeg een nieuwe sectie toe die begint vanaf een specifieke dia. |
| [addEmptySection(String name, int index)](#addEmptySection-java.lang.String-int-) | Voeg een lege sectie toe op de opgegeven positie in de collectie. |
| [removeSectionWithSlides(ISection section)](#removeSectionWithSlides-com.aspose.slides.ISection-) | Verwijder de sectie en de dia's die in de sectie zijn opgenomen. |
| [removeSection(ISection section)](#removeSection-com.aspose.slides.ISection-) | Verwijder de sectie. |
| [reorderSectionWithSlides(ISection section, int index)](#reorderSectionWithSlides-com.aspose.slides.ISection-int-) | Verplaatst de sectie en de bijbehorende dia's van de collectie naar de opgegeven positie. |
| [appendEmptySection(String name)](#appendEmptySection-java.lang.String-) | Voeg een lege sectie toe aan het einde van de collectie. |
| [indexOf(ISection section)](#indexOf-com.aspose.slides.ISection-) | Retourneert een index van de opgegeven sectie in de collectie. |
| [clear()](#clear--) | Verwijdert alle secties uit de collectie. |
### get_Item(int index) {#get-Item-int-}
```
public abstract ISection get_Item(int index)
```


Haalt het element op op de opgegeven index. Alleen-lezen [ISection](../../com.aspose.slides/isection).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int |  |

**Retour:**
[ISection](../../com.aspose.slides/isection)
### addSection(String name, ISlide startedFromSlide) {#addSection-java.lang.String-com.aspose.slides.ISlide-}
```
public abstract ISection addSection(String name, ISlide startedFromSlide)
```


Voeg een nieuwe sectie toe die begint vanaf een specifieke dia.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | Naam van de sectie |
| startedFromSlide | [ISlide](../../com.aspose.slides/islide) | Eerste dia van de sectie |

**Retour:**
[ISection](../../com.aspose.slides/isection) - Toegevoegde sectie.
### addEmptySection(String name, int index) {#addEmptySection-java.lang.String-int-}
```
public abstract ISection addEmptySection(String name, int index)
```


Voeg een lege sectie toe op de opgegeven positie in de collectie.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | Naam van de sectie |
| index | int | Index van de nieuwe sectie. |

**Retour:**
[ISection](../../com.aspose.slides/isection) - Toegevoegde sectie.
### removeSectionWithSlides(ISection section) {#removeSectionWithSlides-com.aspose.slides.ISection-}
```
public abstract void removeSectionWithSlides(ISection section)
```


Verwijder de sectie en de dia's die in de sectie zijn opgenomen.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| section | [ISection](../../com.aspose.slides/isection) | De sectie die uit de collectie moet worden verwijderd. |

### removeSection(ISection section) {#removeSection-com.aspose.slides.ISection-}
```
public abstract void removeSection(ISection section)
```


Verwijder de sectie. De in de sectie opgenomen dia's worden samengevoegd met de vorige sectie.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| section | [ISection](../../com.aspose.slides/isection) | De sectie die uit de collectie moet worden verwijderd. |

### reorderSectionWithSlides(ISection section, int index) {#reorderSectionWithSlides-com.aspose.slides.ISection-int-}
```
public abstract void reorderSectionWithSlides(ISection section, int index)
```


Verplaatst de sectie en de bijbehorende dia's van de collectie naar de opgegeven positie.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| section | [ISection](../../com.aspose.slides/isection) | Sectie om te verplaatsen. |
| index | int | Doel-index. |

### appendEmptySection(String name) {#appendEmptySection-java.lang.String-}
```
public abstract ISection appendEmptySection(String name)
```


Voeg een lege sectie toe aan het einde van de collectie.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | Naam van de sectie |

**Retour:**
[ISection](../../com.aspose.slides/isection) - Toegevoegde sectie.
### indexOf(ISection section) {#indexOf-com.aspose.slides.ISection-}
```
public abstract int indexOf(ISection section)
```


Retourneert een index van de opgegeven sectie in de collectie.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| section | [ISection](../../com.aspose.slides/isection) | Sectie om te vinden. |

**Retour:**
int - Index van een sectie of -1 als de sectie niet tot deze collectie behoort.
### clear() {#clear--}
```
public abstract void clear()
```


Verwijdert alle secties uit de collectie.