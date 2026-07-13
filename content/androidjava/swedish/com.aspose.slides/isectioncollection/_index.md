---
title: ISectionCollection
second_title: Aspose.Slides för Android via Java API-referens
description: Representerar en samling av sektioner.
type: docs
url: /sv/com.aspose.slides/isectioncollection/
---
**Alla implementerade gränssnitt:**
com.aspose.slides.IGenericCollection
```
public interface ISectionCollection extends IGenericCollection<ISection>
```

Representerar en samling av avsnitt.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Hämtar elementet på det angivna indexet. |
| [addSection(String name, ISlide startedFromSlide)](#addSection-java.lang.String-com.aspose.slides.ISlide-) | Lägg till en ny sektion som startas från en specifik bild. |
| [addEmptySection(String name, int index)](#addEmptySection-java.lang.String-int-) | Lägg till en tom sektion på den angivna positionen i samlingen. |
| [removeSectionWithSlides(ISection section)](#removeSectionWithSlides-com.aspose.slides.ISection-) | Ta bort sektion och bilder som finns i sektionen. |
| [removeSection(ISection section)](#removeSection-com.aspose.slides.ISection-) | Ta bort sektion. |
| [reorderSectionWithSlides(ISection section, int index)](#reorderSectionWithSlides-com.aspose.slides.ISection-int-) | Flyttar sektion och dess bilder från samlingen till den angivna positionen. |
| [appendEmptySection(String name)](#appendEmptySection-java.lang.String-) | Lägg till en tom sektion i slutet av samlingen. |
| [indexOf(ISection section)](#indexOf-com.aspose.slides.ISection-) | Returnerar ett index för den angivna sektionen i samlingen. |
| [clear()](#clear--) | Tar bort alla sektioner från samlingen. |
### get_Item(int index) {#get-Item-int-}
```
public abstract ISection get_Item(int index)
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
public abstract ISection addSection(String name, ISlide startedFromSlide)
```


Lägg till en ny sektion som startas från en specifik bild.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| name | java.lang.String | Namnet på sektionen |
| startedFromSlide | [ISlide](../../com.aspose.slides/islide) | Första bilden i sektionen |

**Returnerar:**
[ISection](../../com.aspose.slides/isection) - Tillagd sektion.
### addEmptySection(String name, int index) {#addEmptySection-java.lang.String-int-}
```
public abstract ISection addEmptySection(String name, int index)
```


Lägg till en tom sektion på den angivna positionen i samlingen.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| name | java.lang.String | Namnet på sektionen |
| index | int | Index för den nya sektionen. |

**Returnerar:**
[ISection](../../com.aspose.slides/isection) - Tillagd sektion.
### removeSectionWithSlides(ISection section) {#removeSectionWithSlides-com.aspose.slides.ISection-}
```
public abstract void removeSectionWithSlides(ISection section)
```


Ta bort sektion och bilder som finns i sektionen.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| section | [ISection](../../com.aspose.slides/isection) | Sektionen som ska tas bort från samlingen. |
### removeSection(ISection section) {#removeSection-com.aspose.slides.ISection-}
```
public abstract void removeSection(ISection section)
```


Ta bort sektion. Bilder som finns i sektionen kommer att slås ihop med föregående sektion.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| section | [ISection](../../com.aspose.slides/isection) | Sektionen som ska tas bort från samlingen. |
### reorderSectionWithSlides(ISection section, int index) {#reorderSectionWithSlides-com.aspose.slides.ISection-int-}
```
public abstract void reorderSectionWithSlides(ISection section, int index)
```


Flyttar sektion och dess bilder från samlingen till den angivna positionen.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| section | [ISection](../../com.aspose.slides/isection) | Sektion att flytta. |
| index | int | Målindex. |
### appendEmptySection(String name) {#appendEmptySection-java.lang.String-}
```
public abstract ISection appendEmptySection(String name)
```


Lägg till en tom sektion i slutet av samlingen.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| name | java.lang.String | Namnet på sektionen |

**Returnerar:**
[ISection](../../com.aspose.slides/isection) - Tillagd sektion.
### indexOf(ISection section) {#indexOf-com.aspose.slides.ISection-}
```
public abstract int indexOf(ISection section)
```


Returnerar ett index för den angivna sektionen i samlingen.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| section | [ISection](../../com.aspose.slides/isection) | Sektionen att hitta. |

**Returnerar:**
int - Index för en sektion eller -1 om sektionen inte är från den här samlingen.
### clear() {#clear--}
```
public abstract void clear()
```


Tar bort alla sektioner från samlingen.