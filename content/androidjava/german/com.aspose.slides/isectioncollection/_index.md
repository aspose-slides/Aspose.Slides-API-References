---
title: ISectionCollection
second_title: Aspose.Slides für Android über Java API-Referenz
description: Stellt eine Sammlung von Abschnitten dar.
type: docs
url: /de/com.aspose.slides/isectioncollection/
---
**Alle implementierten Schnittstellen:**
com.aspose.slides.IGenericCollection
```
public interface ISectionCollection extends IGenericCollection<ISection>
```

Stellt eine Sammlung von Abschnitten dar.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Gibt das Element am angegebenen Index zurück. |
| [addSection(String name, ISlide startedFromSlide)](#addSection-java.lang.String-com.aspose.slides.ISlide-) | Fügt einen neuen Abschnitt hinzu, der von einer bestimmten Folie aus startet. |
| [addEmptySection(String name, int index)](#addEmptySection-java.lang.String-int-) | Fügt einen leeren Abschnitt an der angegebenen Position der Sammlung hinzu. |
| [removeSectionWithSlides(ISection section)](#removeSectionWithSlides-com.aspose.slides.ISection-) | Entfernt den Abschnitt und die darin enthaltenen Folien. |
| [removeSection(ISection section)](#removeSection-com.aspose.slides.ISection-) | Entfernt den Abschnitt. |
| [reorderSectionWithSlides(ISection section, int index)](#reorderSectionWithSlides-com.aspose.slides.ISection-int-) | Verschiebt den Abschnitt und seine Folien von der Sammlung an die angegebene Position. |
| [appendEmptySection(String name)](#appendEmptySection-java.lang.String-) | Fügt einen leeren Abschnitt am Ende der Sammlung hinzu. |
| [indexOf(ISection section)](#indexOf-com.aspose.slides.ISection-) | Gibt den Index des angegebenen Abschnitts in der Sammlung zurück. |
| [clear()](#clear--) | Entfernt alle Abschnitte aus der Sammlung. |
### get_Item(int index) {#get-Item-int-}
```
public abstract ISection get_Item(int index)
```


Gibt das Element am angegebenen Index zurück. Nur lesbar [ISection](../../com.aspose.slides/isection).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | int |  |

**Rückgabe:**
[ISection](../../com.aspose.slides/isection)
### addSection(String name, ISlide startedFromSlide) {#addSection-java.lang.String-com.aspose.slides.ISlide-}
```
public abstract ISection addSection(String name, ISlide startedFromSlide)
```


Fügt einen neuen Abschnitt hinzu, der von einer bestimmten Folie aus startet.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| name | java.lang.String | Name des Abschnitts |
| startedFromSlide | [ISlide](../../com.aspose.slides/islide) | Erste Folie des Abschnitts |

**Rückgabe:**
[ISection](../../com.aspose.slides/isection) - Hinzugefügter Abschnitt.
### addEmptySection(String name, int index) {#addEmptySection-java.lang.String-int-}
```
public abstract ISection addEmptySection(String name, int index)
```


Fügt einen leeren Abschnitt an der angegebenen Position der Sammlung hinzu.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| name | java.lang.String | Name des Abschnitts |
| index | int | Index des neuen Abschnitts. |

**Rückgabe:**
[ISection](../../com.aspose.slides/isection) - Hinzugefügter Abschnitt.
### removeSectionWithSlides(ISection section) {#removeSectionWithSlides-com.aspose.slides.ISection-}
```
public abstract void removeSectionWithSlides(ISection section)
```


Entfernt den Abschnitt und die darin enthaltenen Folien.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| section | [ISection](../../com.aspose.slides/isection) | Der Abschnitt, der aus der Sammlung entfernt werden soll. |

### removeSection(ISection section) {#removeSection-com.aspose.slides.ISection-}
```
public abstract void removeSection(ISection section)
```


Entfernt den Abschnitt. Die im Abschnitt enthaltenen Folien werden in den vorherigen Abschnitt zusammengeführt.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| section | [ISection](../../com.aspose.slides/isection) | Der Abschnitt, der aus der Sammlung entfernt werden soll. |

### reorderSectionWithSlides(ISection section, int index) {#reorderSectionWithSlides-com.aspose.slides.ISection-int-}
```
public abstract void reorderSectionWithSlides(ISection section, int index)
```


Verschiebt den Abschnitt und seine Folien von der Sammlung an die angegebene Position.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| section | [ISection](../../com.aspose.slides/isection) | Abschnitt, der verschoben werden soll. |
| index | int | Zielindex. |

### appendEmptySection(String name) {#appendEmptySection-java.lang.String-}
```
public abstract ISection appendEmptySection(String name)
```


Fügt einen leeren Abschnitt am Ende der Sammlung hinzu.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| name | java.lang.String | Name des Abschnitts |

**Rückgabe:**
[ISection](../../com.aspose.slides/isection) - Hinzugefügter Abschnitt.
### indexOf(ISection section) {#indexOf-com.aspose.slides.ISection-}
```
public abstract int indexOf(ISection section)
```


Gibt den Index des angegebenen Abschnitts in der Sammlung zurück.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| section | [ISection](../../com.aspose.slides/isection) | Abschnitt, der gefunden werden soll. |

**Rückgabe:**
int - Index eines Abschnitts oder -1, wenn der Abschnitt nicht aus dieser Sammlung stammt.
### clear() {#clear--}
```
public abstract void clear()
```


Entfernt alle Abschnitte aus der Sammlung.