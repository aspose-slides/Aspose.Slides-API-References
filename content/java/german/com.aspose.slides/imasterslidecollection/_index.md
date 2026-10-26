---
title: IMasterSlideCollection
second_title: Aspose.Slides für Java API-Referenz
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
| [get_Item(int index)](#get-Item-int-) | Ruft das Element am angegebenen Index ab. |
| [remove(IMasterSlide value)](#remove-com.aspose.slides.IMasterSlide-) | Entfernt das erste Vorkommen eines bestimmten Objekts aus der Sammlung. |
| [removeAt(int index)](#removeAt-int-) | Entfernt das Element am angegebenen Index der Sammlung. |
| [removeUnused(boolean ignorePreserveField)](#removeUnused-boolean-) | Entfernt ungenutzte Masterfolien. |
| [addClone(IMasterSlide sourceMaster)](#addClone-com.aspose.slides.IMasterSlide-) | Fügt eine Kopie einer angegebenen Masterfolie am Ende der Sammlung hinzu. |
| [insertClone(int index, IMasterSlide sourceMaster)](#insertClone-int-com.aspose.slides.IMasterSlide-) | Fügt eine Kopie einer angegebenen Masterfolie an der angegebenen Position der Sammlung ein. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IMasterSlide get_Item(int index)
```

Ruft das Element am angegebenen Index ab. Nur lesbar [IMasterSlide](../../com.aspose.slides/imasterslide).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | int |  |

**Rückgabe:**
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

Entfernt das Element am angegebenen Index der Sammlung.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | int | Der nullbasierte Index des zu entfernenden Elements. |

### removeUnused(boolean ignorePreserveField) {#removeUnused-boolean-}
```
public abstract void removeUnused(boolean ignorePreserveField)
```

Entfernt ungenutzte Masterfolien.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| ignorePreserveField | boolean | Bestimmt, ob diese Methode ungenutzte Master entfernen soll, selbst wenn deren [IMasterSlide.getPreserve](../../com.aspose.slides/imasterslide\#getPreserve)/[IMasterSlide.setPreserve(boolean)](../../com.aspose.slides/imasterslide\#setPreserve-boolean-)-Eigenschaft auf true gesetzt ist. |

### addClone(IMasterSlide sourceMaster) {#addClone-com.aspose.slides.IMasterSlide-}
```
public abstract IMasterSlide addClone(IMasterSlide sourceMaster)
```

Fügt eine Kopie einer angegebenen Masterfolie am Ende der Sammlung hinzu. Zugehörige Layoutfolien werden ebenfalls kopiert.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| sourceMaster | [IMasterSlide](../../com.aspose.slides/imasterslide) | Zu klonende Folie. |

**Rückgabe:**
[IMasterSlide](../../com.aspose.slides/imasterslide) - Hinzugefügte Folie.
### insertClone(int index, IMasterSlide sourceMaster) {#insertClone-int-com.aspose.slides.IMasterSlide-}
```
public abstract IMasterSlide insertClone(int index, IMasterSlide sourceMaster)
```

Fügt eine Kopie einer angegebenen Masterfolie an einer angegebenen Position der Sammlung ein. Zugehörige Layoutfolien werden ebenfalls kopiert.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | int | Index der neuen Folie. |
| sourceMaster | [IMasterSlide](../../com.aspose.slides/imasterslide) | Zu klonende Folie. |

**Rückgabe:**
[IMasterSlide](../../com.aspose.slides/imasterslide) - Eingefügte Masterfolie.