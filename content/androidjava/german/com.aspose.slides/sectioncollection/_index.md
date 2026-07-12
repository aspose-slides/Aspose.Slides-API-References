---
title: SectionCollection
second_title: Aspose.Slides für Android via Java API Referenz
description: Stellt eine Sammlung von Abschnitten dar.
type: docs
url: /de/com.aspose.slides/sectioncollection/
---
**Vererbung:**
java.lang.Object, com.aspose.slides.DomObject

**Alle implementierten Schnittstellen:**
[com.aspose.slides.ISectionCollection](../../com.aspose.slides/isectioncollection)
```
public final class SectionCollection extends DomObject<Presentation> implements ISectionCollection
```

Stellt eine Sammlung von Abschnitten dar.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Ruft das Element am angegebenen Index ab. |
| [addSection(String name, ISlide startedFromSlide)](#addSection-java.lang.String-com.aspose.slides.ISlide-) | Fügt einen Abschnitt von Folien hinzu, der von einer bestimmten Folie aus startet. |
| [appendEmptySection(String name)](#appendEmptySection-java.lang.String-) | Fügt einen leeren Abschnitt am Ende der Sammlung hinzu. |
| [addEmptySection(String name, int index)](#addEmptySection-java.lang.String-int-) | Fügt einen leeren Abschnitt an der angegebenen Position der Sammlung hinzu. |
| [size()](#size--) | Ermittelt die tatsächlich in der Sammlung enthaltene Anzahl von Elementen. |
| [indexOf(ISection section)](#indexOf-com.aspose.slides.ISection-) | Gibt den Index des angegebenen Abschnitts in der Sammlung zurück. |
| [removeSectionWithSlides(ISection section)](#removeSectionWithSlides-com.aspose.slides.ISection-) | Entfernt den Abschnitt und die darin enthaltenen Folien. |
| [removeSection(ISection section)](#removeSection-com.aspose.slides.ISection-) | Entfernt den Abschnitt. |
| [reorderSectionWithSlides(ISection section, int index)](#reorderSectionWithSlides-com.aspose.slides.ISection-int-) | Verschiebt den Abschnitt und seine Folien von der Sammlung an die angegebene Position. |
| [clear()](#clear--) | Entfernt alle Abschnitte aus der Sammlung. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Kopiert die gesamte Sammlung in das angegebene Array. |
| [isSynchronized()](#isSynchronized--) | Gibt einen Wert zurück, der angibt, ob der Zugriff auf die Sammlung synchronisiert (thread-sicher) ist. |
| [getSyncRoot()](#getSyncRoot--) | Gibt die Synchronisationswurzel zurück. |
| [iterator()](#iterator--) | Gibt einen Enumerator zurück, der die Sammlung durchläuft. |
| [iteratorJava()](#iteratorJava--) | Gibt einen Java-Iterator für die gesamte Sammlung zurück. |
### get_Item(int index) {#get-Item-int-}
```
public final ISection get_Item(int index)
```

Ruft das Element am angegebenen Index ab. Nur lesbar [ISection](../../com.aspose.slides/isection).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | int |  |

**Rückgabewert:**
[ISection](../../com.aspose.slides/isection)
### addSection(String name, ISlide startedFromSlide) {#addSection-java.lang.String-com.aspose.slides.ISlide-}
```
public final ISection addSection(String name, ISlide startedFromSlide)
```

Fügt einen Abschnitt von Folien hinzu, der von einer bestimmten Folie aus startet.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| name | java.lang.String | Name des Abschnitts |
| startedFromSlide | [ISlide](../../com.aspose.slides/islide) | Erste Folie des Abschnitts |

**Rückgabewert:**
[ISection](../../com.aspose.slides/isection) - Hinzugefügter Abschnitt.
### appendEmptySection(String name) {#appendEmptySection-java.lang.String-}
```
public final ISection appendEmptySection(String name)
```

Fügt einen leeren Abschnitt am Ende der Sammlung hinzu.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| name | java.lang.String | Name des Abschnitts |

**Rückgabewert:**
[ISection](../../com.aspose.slides/isection) - Hinzugefügter Abschnitt.
### addEmptySection(String name, int index) {#addEmptySection-java.lang.String-int-}
```
public final ISection addEmptySection(String name, int index)
```

Fügt einen leeren Abschnitt an der angegebenen Position der Sammlung hinzu.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| name | java.lang.String | Name des Abschnitts |
| index | int | Index des neuen Abschnitts. |

**Rückgabewert:**
[ISection](../../com.aspose.slides/isection) - Hinzugefügter Abschnitt.
### size() {#size--}
```
public final int size()
```

Ermittelt die tatsächlich in der Sammlung enthaltene Anzahl von Elementen. Nur lesbar int.

**Rückgabewert:**
int
### indexOf(ISection section) {#indexOf-com.aspose.slides.ISection-}
```
public final int indexOf(ISection section)
```

Gibt den Index des angegebenen Abschnitts in der Sammlung zurück.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| section | [ISection](../../com.aspose.slides/isection) | Zu findender Abschnitt. |

**Rückgabewert:**
int - Index eines Abschnitts oder -1, falls der Abschnitt nicht aus dieser Sammlung stammt.
### removeSectionWithSlides(ISection section) {#removeSectionWithSlides-com.aspose.slides.ISection-}
```
public final void removeSectionWithSlides(ISection section)
```

Entfernt den Abschnitt und die darin enthaltenen Folien.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| section | [ISection](../../com.aspose.slides/isection) | Der zu entfernende Abschnitt aus der Sammlung. |
### removeSection(ISection section) {#removeSection-com.aspose.slides.ISection-}
```
public final void removeSection(ISection section)
```

Entfernt den Abschnitt. Folien, die im Abschnitt enthalten sind, werden in den vorherigen Abschnitt zusammengeführt.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| section | [ISection](../../com.aspose.slides/isection) | Der zu entfernende Abschnitt aus der Sammlung. |
### reorderSectionWithSlides(ISection section, int index) {#reorderSectionWithSlides-com.aspose.slides.ISection-int-}
```
public final void reorderSectionWithSlides(ISection section, int index)
```

Verschiebt den Abschnitt und seine Folien von der Sammlung an die angegebene Position.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| section | [ISection](../../com.aspose.slides/isection) | Zu verschiebender Abschnitt. |
| index | int | Zielindex. |
### clear() {#clear--}
```
public final void clear()
```

Entfernt alle Abschnitte aus der Sammlung.
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

Kopiert die gesamte Sammlung in das angegebene Array.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Zielarray |
| index | int | Index im Zielarray. |
### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

Gibt einen Wert zurück, der angibt, ob der Zugriff auf die Sammlung synchronisiert (thread-sicher) ist. Nur lesbar boolean.

**Rückgabewert:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

Gibt die Synchronisationswurzel zurück. Nur lesbar Object.

**Rückgabewert:**
java.lang.Object
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<ISection> iterator()
```

Gibt einen Enumerator zurück, der die Sammlung durchläuft.

**Rückgabewert:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ISection> - A IGenericEnumerator that can be used to iterate through the collection.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<ISection> iteratorJava()
```

Gibt einen Java-Iterator für die gesamte Sammlung zurück.

**Rückgabewert:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ISection> - An java.util.Iterator for the entire collection.