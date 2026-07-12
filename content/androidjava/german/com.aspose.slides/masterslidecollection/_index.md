---
title: MasterSlideCollection
second_title: Aspose.Slides für Android über die Java-API-Referenz
description: Stellt eine Sammlung von Masterfolien dar.
type: docs
url: /de/com.aspose.slides/masterslidecollection/
---
**Vererbung:**
java.lang.Object, com.aspose.slides.DomObject

**Alle implementierten Schnittstellen:**
[com.aspose.slides.IMasterSlideCollection](../../com.aspose.slides/imasterslidecollection)
```
public final class MasterSlideCollection extends DomObject<Presentation> implements IMasterSlideCollection
```

Stellt eine Sammlung von Masterfolien dar.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [size()](#size--) | Gets the number of elements actually contained in the collection. |
| [get_Item(int index)](#get-Item-int-) | Gets the element at the specified index. |
| [remove(IMasterSlide value)](#remove-com.aspose.slides.IMasterSlide-) | Removes the first occurrence of a specific object from the collection. |
| [removeAt(int index)](#removeAt-int-) | Removes the element at the specified index of the collection. |
| [removeUnused(boolean ignorePreserveField)](#removeUnused-boolean-) | Removes unused master slides. |
| [addClone(IMasterSlide sourceMaster)](#addClone-com.aspose.slides.IMasterSlide-) | Adds a copy of a specified master slide to the end of the collection. |
| [insertClone(int index, IMasterSlide sourceMaster)](#insertClone-int-com.aspose.slides.IMasterSlide-) | Inserts a copy of a specified master slide to specified position of the collection. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Copies all elements from the collection to the specified array. |
| [isSynchronized()](#isSynchronized--) | Returns a value indicating whether access to the collection is synchronized (thread-safe). |
| [getSyncRoot()](#getSyncRoot--) | Returns a synchronization root. |
| [iterator()](#iterator--) | Returns an enumerator that iterates through the collection. |
| [iteratorJava()](#iteratorJava--) | Returns a java iterator for the entire collection. |
### size() {#size--}
```
public final int size()
```

Gibt die tatsächlich in der Sammlung enthaltene Anzahl von Elementen zurück. Nur-Lese int.

**Rückgabewert:**
int
### get_Item(int index) {#get-Item-int-}
```
public final IMasterSlide get_Item(int index)
```

Gibt das Element am angegebenen Index zurück. Nur-Lese [MasterSlide](../../com.aspose.slides/masterslide).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | int |  |

**Rückgabewert:**
[IMasterSlide](../../com.aspose.slides/imasterslide)
### remove(IMasterSlide value) {#remove-com.aspose.slides.IMasterSlide-}
```
public final void remove(IMasterSlide value)
```

Entfernt das erste Vorkommen eines bestimmten Objekts aus der Sammlung.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [IMasterSlide](../../com.aspose.slides/imasterslide) | Die Masterfolie, die aus der Sammlung entfernt werden soll. |

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

Entfernt das Element am angegebenen Index der Sammlung.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | int | Der nullbasierte Index des zu entfernenden Elements.

--------------------

Um das Auslösen einer PptxEditException zu vermeiden, prüfen Sie vorher die Eigenschaft HasDependingSlides des Masters. |

### removeUnused(boolean ignorePreserveField) {#removeUnused-boolean-}
```
public final void removeUnused(boolean ignorePreserveField)
```

Entfernt ungenutzte Masterfolien.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| ignorePreserveField | boolean | Bestimmt, ob diese Methode ungenutzte Master entfernen soll, selbst wenn ihre [MasterSlide.getPreserve](../../com.aspose.slides/masterslide\#getPreserve)/[MasterSlide.setPreserve(boolean)](../../com.aspose.slides/masterslide\#setPreserve-boolean-)-Eigenschaft auf true gesetzt ist. |

### addClone(IMasterSlide sourceMaster) {#addClone-com.aspose.slides.IMasterSlide-}
```
public final IMasterSlide addClone(IMasterSlide sourceMaster)
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
public final IMasterSlide insertClone(int index, IMasterSlide sourceMaster)
```

Fügt eine Kopie einer angegebenen Masterfolie an der angegebenen Position der Sammlung ein. Verknüpfte Layoutfolien werden ebenfalls kopiert.

> ```
> The following example shows how to clone master slide in another PowerPoint Presentation.
>  
>  // Instanziieren der Presentation-Klasse, um die Quellpräsentationsdatei zu laden
>  Presentation srcPres = new Presentation("CloneToAnotherPresentationWithMaster.pptx");
>  try {
>      // Instanziieren der Presentation-Klasse für die Zielpräsentation (wo die Folie geklont werden soll)
>      Presentation destPres = new Presentation();
>      try {
>          // Instanziieren von ISlide aus der Folien-sammlung der Quellpräsentation zusammen mit
>          // Masterfolie
>          ISlide SourceSlide = srcPres.getSlides().get_Item(0);
>          IMasterSlide SourceMaster = SourceSlide.getLayoutSlide().getMasterSlide();
>          // Masterfolien der Zielpräsentation abrufen
>          IMasterSlideCollection masters = destPres.getMasters();
>          // Gewünschte Masterfolie aus der Quellpräsentation in die Master-sammlung der Zielpräsentation klonen
>          // Destination presentation
>          IMasterSlide iSlide = masters.addClone(SourceMaster);
>          // Sammlung von Folien in der Zielpräsentation
>          ISlideCollection slds = destPres.getSlides();
>          // Quellfolie in die Ziel-Folien-Sammlung klonen.
>          slds.addClone(SourceSlide, iSlide, true);
>          // Zielpräsentation auf das Laufwerk speichern
>          destPres.save("CloneToAnotherPresentationWithMaster_out.pptx", SaveFormat.Pptx);
>      } finally {
>          if (destPres != null) destPres.dispose();
>      }
>  } finally {
>      if (srcPres != null) srcPres.dispose();
>  }
> ```

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | int | Index der neuen Folie. |
| sourceMaster | [IMasterSlide](../../com.aspose.slides/imasterslide) | Folie zum Klonen. |

**Rückgabewert:**
[IMasterSlide](../../com.aspose.slides/imasterslide) - Eingefügte Masterfolie.
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

Kopiert alle Elemente der Sammlung in das angegebene Array.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Ziel-Array. |
| index | int | Startindex im Ziel-Array. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

Gibt einen Wert zurück, der angibt, ob der Zugriff auf die Sammlung synchronisiert (Thread-sicher) ist. Nur-Lese boolean.

**Rückgabewert:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

Gibt ein Synchronisations-Root zurück. Nur-Lese Object.

**Rückgabewert:**
java.lang.Object
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IMasterSlide> iterator()
```

Gibt einen Enumerator zurück, der die Sammlung durchläuft.

**Rückgabewert:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IMasterSlide> - Ein IGenericEnumerator, der zum Durchlaufen der Sammlung verwendet werden kann.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IMasterSlide> iteratorJava()
```

Gibt einen Java-Iterator für die gesamte Sammlung zurück.

**Rückgabewert:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IMasterSlide> - Ein java.util.Iterator für die gesamte Sammlung.