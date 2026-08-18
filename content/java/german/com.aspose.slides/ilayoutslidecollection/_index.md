---
title: ILayoutSlideCollection
second_title: Aspose.Slides für Java API-Referenz
description: Stellt eine Basisklasse für die Sammlung von Layout-Folien dar.
type: docs
url: /de/com.aspose.slides/ilayoutslidecollection/
---
**Alle implementierten Schnittstellen:**
com.aspose.slides.IGenericCollection
```
public interface ILayoutSlideCollection extends IGenericCollection<ILayoutSlide>
```

Stellt eine Basisklasse für die Sammlung von Layout-Folien dar.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Gibt die Layout-Folie anhand des Index zurück. |
| [getByType(byte type)](#getByType-byte-) | Gibt die erste Layout-Folie des angegebenen Typs zurück. |
| [remove(ILayoutSlide value)](#remove-com.aspose.slides.ILayoutSlide-) | Entfernt ein Layout aus der Sammlung. |
| [removeUnused()](#removeUnused--) | Entfernt nicht verwendete Layout-Folien (Layout-Folien, deren HasDependingSlides false ist). |
### get_Item(int index) {#get-Item-int-}
```
public abstract ILayoutSlide get_Item(int index)
```

Gibt die Layout-Folie anhand des Index zurück. Nur lesbar [ILayoutSlide](../../com.aspose.slides/ilayoutslide).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | int |  |

**Rückgabe:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide)
### getByType(byte type) {#getByType-byte-}
```
public abstract ILayoutSlide getByType(byte type)
```

Gibt die erste Layout-Folie des angegebenen Typs zurück.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| type | byte | Der Typ der zu findenden Layout-Folien. |

**Rückgabe:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - [ILayoutSlide](../../com.aspose.slides/ilayoutslide) mit angegebenem Typ oder null, wenn keine Layouts gefunden wurden.
### remove(ILayoutSlide value) {#remove-com.aspose.slides.ILayoutSlide-}
```
public abstract void remove(ILayoutSlide value)
```

Entfernt ein Layout aus der Sammlung.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | Die zu entfernende Layout-Folie aus der Sammlung.

--------------------

1) Um das Werfen von PptxEditException zu vermeiden, prüfen Sie vorab die Eigenschaft HasDependingSlides des Layouts. 2) Sie können auch die Methode [ILayoutSlide.remove](../../com.aspose.slides/ilayoutslide\#remove) verwenden, um den Code zu vereinfachen. |
### removeUnused() {#removeUnused--}
```
public abstract void removeUnused()
```

Entfernt nicht verwendete Layout-Folien (Layout-Folien, deren HasDependingSlides false ist).