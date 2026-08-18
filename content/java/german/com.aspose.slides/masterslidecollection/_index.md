---
title: MasterSlideCollection
second_title: Aspose.Slides für Java API Referenz
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
| [size()](#size--) | Ermittelt die tatsächlich in der Sammlung enthaltene Elementanzahl. |
| [get_Item(int index)](#get-Item-int-) | Ermittelt das Element am angegebenen Index. |
| [remove(IMasterSlide value)](#remove-com.aspose.slides.IMasterSlide-) | Entfernt das erste Vorkommen eines bestimmten Objekts aus der Sammlung. |
| [removeAt(int index)](#removeAt-int-) | Entfernt das Element am angegebenen Index der Sammlung. |
| [removeUnused(boolean ignorePreserveField)](#removeUnused-boolean-) | Entfernt nicht verwendete Masterfolien. |
| [addClone(IMasterSlide sourceMaster)](#addClone-com.aspose.slides.IMasterSlide-) | Fügt eine Kopie einer angegebenen Masterfolie am Ende der Sammlung hinzu. |
| [insertClone(int index, IMasterSlide sourceMaster)](#insertClone-int-com.aspose.slides.IMasterSlide-) | Fügt eine Kopie einer angegebenen Masterfolie an einer angegebenen Position in die Sammlung ein. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Kopiert alle Elemente der Sammlung in das angegebene Array. |
| [isSynchronized()](#isSynchronized--) | Gibt einen Wert zurück, der angibt, ob der Zugriff auf die Sammlung synchronisiert ist (thread-sicher). |
| [getSyncRoot()](#getSyncRoot--) | Gibt ein Synchronisationsobjekt zurück. |
| [iterator()](#iterator--) | Gibt einen Enumerator zurück, der durch die Sammlung iteriert. |
| [iteratorJava()](#iteratorJava--) | Gibt einen Java-Iterator für die gesamte Sammlung zurück. |
### size() {#size--}
```
public final int size()
```

Ermittelt die tatsächlich in der Sammlung enthaltene Elementanzahl. Nur-Lesen int.

**Rückgabe:**
int
### get_Item(int index) {#get-Item-int-}
```
public final IMasterSlide get_Item(int index)
```

Ermittelt das Element am angegebenen Index. Nur-Lesen [MasterSlide](../../com.aspose.slides/masterslide).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | int |  |

**Rückgabe:**
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
| index | int | Der nullbasierte Index des zu entfernenden Elements. |

--------------------

Um das Werfen einer PptxEditException zu vermeiden, prüfen Sie vorher die Eigenschaft HasDependingSlides des Masters. |

### removeUnused(boolean ignorePreserveField) {#removeUnused-boolean-}
```
public final void removeUnused(boolean ignorePreserveField)
```

Entfernt nicht verwendete Masterfolien.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| ignorePreserveField | boolean | Bestimmt, ob diese Methode nicht verwendete Master entfernen soll, selbst wenn die Eigenschaft [MasterSlide.getPreserve](../../com.aspose.slides/masterslide\#getPreserve)/[MasterSlide.setPreserve(boolean)](../../com.aspose.slides/masterslide\#setPreserve-boolean-) auf true gesetzt ist. |

### addClone(IMasterSlide sourceMaster) {#addClone-com.aspose.slides.IMasterSlide-}
```
public final IMasterSlide addClone(IMasterSlide sourceMaster)
```

Fügt eine Kopie einer angegebenen Masterfolie am Ende der Sammlung hinzu. Verknüpfte Layoutfolien werden ebenfalls kopiert.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| sourceMaster | [IMasterSlide](../../com.aspose.slides/imasterslide) | Folien zum Klonen. |

**Rückgabe:**
[IMasterSlide](../../com.aspose.slides/imasterslide) - Hinzugefügte Folie.
### insertClone(int index, IMasterSlide sourceMaster) {#insertClone-int-com.aspose.slides.IMasterSlide-}
```
public final IMasterSlide insertClone(int index, IMasterSlide sourceMaster)
```

Fügt eine Kopie einer angegebenen Masterfolie an einer angegebenen Position in die Sammlung ein. Verknüpfte Layoutfolien werden ebenfalls kopiert.

--------------------

> ```
> The following example shows how to clone master slide in another PowerPoint Presentation.
>  
>  // Instantiate Presentation class to load the source presentation file
>  Presentation srcPres = new Presentation("CloneToAnotherPresentationWithMaster.pptx");
>  try {
>      // Instantiate Presentation class for destination presentation (where slide is to be cloned)
>      Presentation destPres = new Presentation();
>      try {
>          // Instantiate ISlide from the collection of slides in source presentation along with
>          // Master slide
>          ISlide SourceSlide = srcPres.getSlides().get_Item(0);
>          IMasterSlide SourceMaster = SourceSlide.getLayoutSlide().getMasterSlide();
>          // Get Master Slides of destination presentation
>          IMasterSlideCollection masters = destPres.getMasters();
>          // Clone the desired master slide from the source presentation to the collection of masters in the
>          // Destination presentation
>          IMasterSlide iSlide = masters.addClone(SourceMaster);
>          // Collection of slides in the destination presentation
>          ISlideCollection slds = destPres.getSlides();
>          // Clone source slide to destination slides collection.
>          slds.addClone(SourceSlide, iSlide, true);
>          // Save the destination presentation to disk
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
| sourceMaster | [IMasterSlide](../../com.aspose.slides/imasterslide) | Folien zum Klonen. |

**Rückgabe:**
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

Gibt einen Wert zurück, der angibt, ob der Zugriff auf die Sammlung synchronisiert ist (thread-sicher). Nur-Lesen boolean.

**Rückgabe:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

Gibt ein Synchronisationsobjekt zurück. Nur-Lesen Object.

**Rückgabe:**
java.lang.Object
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IMasterSlide> iterator()
```

Gibt einen Enumerator zurück, der durch die Sammlung iteriert.

**Rückgabe:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IMasterSlide> - Ein IGenericEnumerator, der zum Iterieren durch die Sammlung verwendet werden kann.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IMasterSlide> iteratorJava()
```

Gibt einen Java-Iterator für die gesamte Sammlung zurück.

**Rückgabe:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IMasterSlide> - Ein java.util.Iterator für die gesamte Sammlung.