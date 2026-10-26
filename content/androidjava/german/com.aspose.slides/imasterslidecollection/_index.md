---
title: IMasterSlideCollection
second_title: Aspose.Slides für Android über die Java-API-Referenz
description: Stellt eine Sammlung von Masterfolien dar.
type: docs
url: /de/com.aspose.slides/imasterslidecollection/
---
**Alle implementierten Schnittstellen:**
com.aspose.slides.IGenericCollection
```
public interface IMasterSlideCollection extends IGenericCollection<IMasterSlide>
```

Stellt eine Sammlung von Masterfolien dar.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Gibt das Element am angegebenen Index zurück. |
| [remove(IMasterSlide value)](#remove-com.aspose.slides.IMasterSlide-) | Entfernt das erste Vorkommen eines bestimmten Objekts aus der Sammlung. |
| [removeAt(int index)](#removeAt-int-) | Entfernt das Element am angegebenen Index aus der Sammlung. |
| [removeUnused(boolean ignorePreserveField)](#removeUnused-boolean-) | Entfernt unbenutzte Masterfolien. |
| [addClone(IMasterSlide sourceMaster)](#addClone-com.aspose.slides.IMasterSlide-) | Fügt eine Kopie einer angegebenen Masterfolie am Ende der Sammlung hinzu. |
| [insertClone(int index, IMasterSlide sourceMaster)](#insertClone-int-com.aspose.slides.IMasterSlide-) | Fügt eine Kopie einer angegebenen Masterfolie an einer angegebenen Position in die Sammlung ein. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IMasterSlide get_Item(int index)
```


Gibt das Element am angegebenen Index zurück. Nur-Lesen [IMasterSlide](../../com.aspose.slides/imasterslide).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | int |  |

**Rückgabewert:**
[IMasterSlide](../../com.aspose.slides/imasterslide)
### remove(IMasterSlide value) {#remove-com.aspose.slides.IMasterSlide-}
```
public abstract void remove(IMasterSlide value)
```


Entfernt das erste Vorkommen eines bestimmten Objekts aus der Sammlung.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [IMasterSlide](../../com.aspose.slides/imasterslide) | Die Masterfolie, die aus der Sammlung entfernt werden soll. |

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```


Entfernt das Element am angegebenen Index aus der Sammlung.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | int | Der nullbasierte Index des zu entfernenden Elements. |

### removeUnused(boolean ignorePreserveField) {#removeUnused-boolean-}
```
public abstract void removeUnused(boolean ignorePreserveField)
```


Entfernt unbenutzte Masterfolien.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| ignorePreserveField | boolean | Bestimmt, ob diese Methode unbenutzte Master entfernen soll, selbst wenn die Eigenschaft [IMasterSlide.getPreserve](../../com.aspose.slides/imasterslide\#getPreserve)/[IMasterSlide.setPreserve(boolean)](../../com.aspose.slides/imasterslide\#setPreserve-boolean-) auf true gesetzt ist. |

### addClone(IMasterSlide sourceMaster) {#addClone-com.aspose.slides.IMasterSlide-}
```
public abstract IMasterSlide addClone(IMasterSlide sourceMaster)
```


Fügt eine Kopie einer angegebenen Masterfolie am Ende der Sammlung hinzu. Verknüpfte Layoutfolien werden ebenfalls kopiert.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| sourceMaster | [IMasterSlide](../../com.aspose.slides/imasterslide) | Folie zum Klonen. |

**Rückgabewert:**
[IMasterSlide](../../com.aspose.slides/imasterslide) - Hinzugefügte Folie.
### insertClone(int index, IMasterSlide sourceMaster) {#insertClone-int-com.aspose.slides.IMasterSlide-}
```
public abstract IMasterSlide insertClone(int index, IMasterSlide sourceMaster)
```


Fügt eine Kopie einer angegebenen Masterfolie an einer angegebenen Position in die Sammlung ein. Verknüpfte Layoutfolien werden ebenfalls kopiert.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | int | Index der neuen Folie. |
| sourceMaster | [IMasterSlide](../../com.aspose.slides/imasterslide) | Folie zum Klonen. |

**Rückgabewert:**
[IMasterSlide](../../com.aspose.slides/imasterslide) - Eingefügte Masterfolie.