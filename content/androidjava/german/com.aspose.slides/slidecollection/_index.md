---
title: SlideCollection
second_title: Aspose.Slides für Android über die Java-API-Referenz
description: Stellt eine Sammlung von Folien dar.
type: docs
url: /de/com.aspose.slides/slidecollection/
---
**Vererbung:**
java.lang.Object, com.aspose.slides.DomObject

**Alle implementierten Schnittstellen:**
[com.aspose.slides.ISlideCollection](../../com.aspose.slides/islidecollection)
```
public final class SlideCollection extends DomObject<Presentation> implements ISlideCollection
```

Stellt eine Sammlung von Folien dar.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [size()](#size--) | Gibt die tatsächlich in der Sammlung enthaltene Anzahl von Elementen zurück. |
| [get_Item(int index)](#get-Item-int-) | Gibt das Element am angegebenen Index zurück. |
| [addClone(ISlide sourceSlide)](#addClone-com.aspose.slides.ISlide-) | Fügt eine Kopie einer angegebenen Folie am Ende der Sammlung hinzu. |
| [addClone(ISlide sourceSlide, ISection section)](#addClone-com.aspose.slides.ISlide-com.aspose.slides.ISection-) | Fügt eine Kopie einer angegebenen Folie am Ende des angegebenen Abschnitts hinzu. |
| [insertClone(int index, ISlide sourceSlide)](#insertClone-int-com.aspose.slides.ISlide-) | Fügt eine Kopie einer angegebenen Folie an der angegebenen Position in die Sammlung ein. |
| [addEmptySlide(ILayoutSlide layout)](#addEmptySlide-com.aspose.slides.ILayoutSlide-) | Fügt eine neue leere Folie am Ende der Sammlung hinzu. |
| [insertEmptySlide(int index, ILayoutSlide layout)](#insertEmptySlide-int-com.aspose.slides.ILayoutSlide-) | Fügt eine Kopie einer angegebenen Folie an der angegebenen Position in die Sammlung ein. |
| [addClone(ISlide sourceSlide, ILayoutSlide destLayout)](#addClone-com.aspose.slides.ISlide-com.aspose.slides.ILayoutSlide-) | Fügt eine Kopie einer angegebenen Folie am Ende der Sammlung hinzu. |
| [insertClone(int index, ISlide sourceSlide, ILayoutSlide destLayout)](#insertClone-int-com.aspose.slides.ISlide-com.aspose.slides.ILayoutSlide-) | Fügt eine Kopie einer angegebenen Folie an der angegebenen Position in die Sammlung ein. |
| [addClone(ISlide sourceSlide, IMasterSlide destMaster, boolean allowCloneMissingLayout)](#addClone-com.aspose.slides.ISlide-com.aspose.slides.IMasterSlide-boolean-) | Fügt eine Kopie einer angegebenen Quellfolie am Ende der Sammlung hinzu. |
| [insertClone(int index, ISlide sourceSlide, IMasterSlide destMaster, boolean allowCloneMissingLayout)](#insertClone-int-com.aspose.slides.ISlide-com.aspose.slides.IMasterSlide-boolean-) | Fügt eine Kopie einer angegebenen Quellfolie an der angegebenen Position in die Sammlung ein. |
| [remove(ISlide value)](#remove-com.aspose.slides.ISlide-) | Entfernt das erste Vorkommen eines bestimmten Objekts aus der Sammlung. |
| [removeAt(int index)](#removeAt-int-) | Entfernt das Element am angegebenen Index der Sammlung. |
| [iterator()](#iterator--) | Gibt einen Enumerator zurück, der durch die Sammlung iteriert. |
| [iteratorJava()](#iteratorJava--) | Gibt einen Java-Iterator für die gesamte Sammlung zurück. |
| [toArray()](#toArray--) | Erstellt und gibt ein Array zurück, das alle Folien enthält. |
| [toArray(int startIndex, int count)](#toArray-int-int-) | Erstellt und gibt ein Array zurück, das alle Folien aus dem angegebenen Bereich enthält. |
| [reorder(int index, ISlide slide)](#reorder-int-com.aspose.slides.ISlide-) | Verschiebt eine Folie aus der Sammlung an die angegebene Position. |
| [reorder(int index, ISlide[] slides)](#reorder-int-com.aspose.slides.ISlide...-) | Verschiebt Folien aus der Sammlung an die angegebene Position. Folien werden beginnend mit dem Index in der Reihenfolge, in der sie in der Liste erscheinen, platziert. |
| [indexOf(ISlide slide)](#indexOf-com.aspose.slides.ISlide-) | Gibt den Index der angegebenen Folie in der Sammlung zurück. |
| [addFromPdf(String path)](#addFromPdf-java.lang.String-) | Erstellt Folien aus dem PDF-Dokument und fügt sie am Ende der Sammlung hinzu. |
| [addFromPdf(String path, PdfImportOptions pdfImportOptions)](#addFromPdf-java.lang.String-com.aspose.slides.PdfImportOptions-) | Erstellt Folien aus dem PDF-Dokument und fügt sie am Ende der Sammlung unter Berücksichtigung der PDF-Importoptionen hinzu. |
| [addFromPdf(InputStream pdfStream)](#addFromPdf-java.io.InputStream-) | Erstellt Folien aus dem PDF-Dokument und fügt sie am Ende der Sammlung hinzu. |
| [addFromPdf(InputStream pdfStream, PdfImportOptions pdfImportOptions)](#addFromPdf-java.io.InputStream-com.aspose.slides.PdfImportOptions-) | Erstellt Folien aus dem PDF-Dokument und fügt sie am Ende der Sammlung hinzu. |
| [addFromHtml(String htmlText, IExternalResourceResolver resolver, String uri)](#addFromHtml-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-) | Erstellt Folien aus HTML-Text und fügt sie am Ende der Sammlung hinzu. |
| [addFromHtml(String htmlText)](#addFromHtml-java.lang.String-) | Erstellt Folien aus HTML-Text und fügt sie am Ende der Sammlung hinzu. |
| [addFromHtml(InputStream htmlStream, IExternalResourceResolver resolver, String uri)](#addFromHtml-java.io.InputStream-com.aspose.slides.IExternalResourceResolver-java.lang.String-) | Erstellt Folien aus HTML-Text und fügt sie am Ende der Sammlung hinzu. |
| [addFromHtml(InputStream htmlStream)](#addFromHtml-java.io.InputStream-) | Erstellt Folien aus HTML-Text und fügt sie am Ende der Sammlung hinzu. |
| [insertFromHtml(int index, String htmlText, IExternalResourceResolver resolver, String uri)](#insertFromHtml-int-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-) | Erstellt Folien aus HTML-Text und fügt sie an der angegebenen Position in die Sammlung ein. |
| [insertFromHtml(int index, String htmlText, IExternalResourceResolver resolver, String uri, boolean useSlideWithIndexAsStart)](#insertFromHtml-int-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-boolean-) | Erstellt Folien aus HTML-Text und fügt sie an der angegebenen Position in die Sammlung ein. |
| [insertFromHtml(int index, String htmlText)](#insertFromHtml-int-java.lang.String-) | Erstellt Folien aus HTML-Text und fügt sie an der angegebenen Position in die Sammlung ein. |
| [insertFromHtml(int index, String htmlText, boolean useSlideWithIndexAsStart)](#insertFromHtml-int-java.lang.String-boolean-) | Erstellt Folien aus HTML-Text und fügt sie an der angegebenen Position in die Sammlung ein. |
| [insertFromHtml(int index, InputStream htmlStream, IExternalResourceResolver resolver, String uri)](#insertFromHtml-int-java.io.InputStream-com.aspose.slides.IExternalResourceResolver-java.lang.String-) | Erstellt Folien aus HTML-Text und fügt sie an der angegebenen Position in die Sammlung ein. |
| [insertFromHtml(int index, InputStream htmlStream, IExternalResourceResolver resolver, String uri, boolean useSlideWithIndexAsStart)](#insertFromHtml-int-java.io.InputStream-com.aspose.slides.IExternalResourceResolver-java.lang.String-boolean-) | Erstellt Folien aus HTML-Text und fügt sie an der angegebenen Position in die Sammlung ein. |
| [insertFromHtml(int index, InputStream htmlStream)](#insertFromHtml-int-java.io.InputStream-) | Erstellt Folien aus HTML-Text und fügt sie an der angegebenen Position in die Sammlung ein. |
| [insertFromHtml(int index, InputStream htmlStream, boolean useSlideWithIndexAsStart)](#insertFromHtml-int-java.io.InputStream-boolean-) | Erstellt Folien aus HTML-Text und fügt sie an der angegebenen Position in die Sammlung ein. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Kopiert alle Elemente aus der Sammlung in das angegebene Array. |
| [isSynchronized()](#isSynchronized--) | Gibt einen Wert zurück, der angibt, ob der Zugriff auf die Sammlung synchronisiert ist (thread-sicher). |
| [getSyncRoot()](#getSyncRoot--) | Gibt die Synchronisationswurzel zurück. |

### size() {#size--}
```
public final int size()
```

Gibt die tatsächlich in der Sammlung enthaltene Anzahl von Elementen zurück. Nur-Lesen int.

### get_Item(int index) {#get-Item-int-}
```
public final ISlide get_Item(int index)
```

Gibt das Element am angegebenen Index zurück. Nur-Lesen [Slide](../../com.aspose.slides/slide).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | int |  |

**Rückgabewert:**
[ISlide](../../com.aspose.slides/islide)

### addClone(ISlide sourceSlide) {#addClone-com.aspose.slides.ISlide-}
```
public final ISlide addClone(ISlide sourceSlide)
```

Fügt eine Kopie einer angegebenen Folie am Ende der Sammlung hinzu.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| sourceSlide | [ISlide](../../com.aspose.slides/islide) | Zu klonende Folie. |

--------------------

Wenn Sie eine Folie zwischen verschiedenen Präsentationen klonen, kann auch die Masterfolie geklont werden. Ein internes Register wird verwendet, um automatisch geklonte Master zu verfolgen, um die Erstellung mehrerer Klone derselben Masterfolie zu verhindern. Das manuelle Klonen von Masterfolien wird weder verhindert noch registriert. Wenn Sie mehr Kontrolle über den Klonvorgang benötigen, verwenden Sie \#addClone(ISlide,ILayoutSlide).addClone(ISlide,ILayoutSlide) oder \#addClone(ISlide,IMasterSlide,boolean).addClone(ISlide,IMasterSlide,boolean) zum Klonen von Folien, [IGlobalLayoutSlideCollection.addClone(ILayoutSlide)](../../com.aspose.slides/igloballayoutslidecollection\#addClone-ILayoutSlide-) oder [IGlobalLayoutSlideCollection.addClone(ILayoutSlide,IMasterSlide)](../../com.aspose.slides/igloballayoutslidecollection\#addClone-ILayoutSlide-IMasterSlide-) zum Klonen von Layouts und [IMasterSlideCollection.addClone(IMasterSlide)](../../com.aspose.slides/imasterslidecollection\#addClone-IMasterSlide-) zum Klonen von Masterfolien.

**Rückgabewert:**
[ISlide](../../com.aspose.slides/islide) - Neue Folie.

### addClone(ISlide sourceSlide, ISection section) {#addClone-com.aspose.slides.ISlide-com.aspose.slides.ISection-}
```
public final ISlide addClone(ISlide sourceSlide, ISection section)
```

Fügt eine Kopie einer angegebenen Folie am Ende des angegebenen Abschnitts hinzu.

--------------------

> ```
> IPresentation presentation = new Presentation();
>  try
>  {
>      presentation.getSlides().get_Item(0).getShapes().addAutoShape(ShapeType.Rectangle, 200, 50, 300, 100);
>      presentation.getSections().addSection("Section 1", presentation.getSlides().get_Item(0));
>      
>      ISection section2 = presentation.getSections().appendEmptySection("Section 2");
>      presentation.getSlides().addClone(presentation.getSlides().get_Item(0), section2);
>      
>      // Jetzt enthält der zweite Abschnitt eine Kopie der ersten Folie.
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| sourceSlide | [ISlide](../../com.aspose.slides/islide) | Zu klonende Folie. |
| section | [ISection](../../com.aspose.slides/isection) | Abschnitt für die neue Folie. |

**Rückgabewert:**
[ISlide](../../com.aspose.slides/islide) - Neue Folie.

### insertClone(int index, ISlide sourceSlide) {#insertClone-int-com.aspose.slides.ISlide-}
```
public final ISlide insertClone(int index, ISlide sourceSlide)
```

Fügt eine Kopie einer angegebenen Folie an der angegebenen Position in die Sammlung ein.

--------------------

> ```
> The following example shows how to clone at another position within Presentation.
>  
>  // Instanziiert die Presentation-Klasse, die eine Präsentationsdatei darstellt
>  Presentation pres = new Presentation("CloneWithInSamePresentation.pptx");
>  try {
>      // Klont die gewünschte Folie an das Ende der Foliensammlung in derselben Präsentation
>      ISlideCollection slds = pres.getSlides();
>      // Klont die gewünschte Folie an den angegebenen Index in derselben Präsentation
>      slds.insertClone(2, pres.getSlides().get_Item(1));
>      // Schreibt die modifizierte Präsentation auf die Festplatte
>      pres.save("Aspose_CloneWithInSamePresentation_out.pptx", SaveFormat.Pptx);
>  }
>  finally
>  {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to clone at another position within Presentation.
>  
>  // Instanziiert die Presentation-Klasse, um die Quellpräsentationsdatei zu laden
>  Presentation srcPres = new Presentation("CloneAtEndOfAnother.pptx");
>  try {
>      // Instanziiert die Presentation-Klasse für die Ziel-PPTX (wo die Folie geklont werden soll)
>      Presentation destPres = new Presentation();
>      try {
>          ISlideCollection slds = destPres.getSlides();
>          slds.insertClone(2, srcPres.getSlides().get_Item(0));
>          // Schreibt die Zielpräsentation auf die Festplatte
>          destPres.save("Aspose2_out.pptx", SaveFormat.Pptx);
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
| sourceSlide | [ISlide](../../com.aspose.slides/islide) | Zu klonende Folie. |

--------------------

Wenn Sie eine Folie zwischen verschiedenen Präsentationen klonen, kann auch die Masterfolie geklont werden. Ein internes Register wird verwendet, um automatisch geklonte Master zu verfolgen, um die Erstellung mehrerer Klone derselben Masterfolie zu verhindern. Das manuelle Klonen von Masterfolien wird weder verhindert noch registriert. Wenn Sie mehr Kontrolle über den Klonvorgang benötigen, verwenden Sie \#insertClone(int,ISlide,ILayoutSlide).insertClone(int,ISlide,ILayoutSlide) oder \#insertClone(int,ISlide,IMasterSlide,boolean).insertClone(int,ISlide,IMasterSlide,boolean) zum Klonen von Folien und [IMasterSlideCollection.addClone(IMasterSlide)](../../com.aspose.slides/imasterslidecollection\#addClone-IMasterSlide-) zum Klonen von Masterfolien.

**Rückgabewert:**
[ISlide](../../com.aspose.slides/islide) - Eingefügte Folie.

### addEmptySlide(ILayoutSlide layout) {#addEmptySlide-com.aspose.slides.ILayoutSlide-}
```
public final ISlide addEmptySlide(ILayoutSlide layout)
```

Fügt eine neue leere Folie am Ende der Sammlung hinzu.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| layout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | Layout für die Folie. |

**Rückgabewert:**
[ISlide](../../com.aspose.slides/islide) - Hinzugefügte Folie.

### insertEmptySlide(int index, ILayoutSlide layout) {#insertEmptySlide-int-com.aspose.slides.ILayoutSlide-}
```
public final ISlide insertEmptySlide(int index, ILayoutSlide layout)
```

Fügt eine Kopie einer angegebenen Folie an der angegebenen Position in die Sammlung ein.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | int | Index der neuen Folie. |
| layout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | Layout für die Folie. |

**Rückgabewert:**
[ISlide](../../com.aspose.slides/islide) - Eingefügte Folie.

### addClone(ISlide sourceSlide, ILayoutSlide destLayout) {#addClone-com.aspose.slides.ISlide-com.aspose.slides.ILayoutSlide-}
```
public final ISlide addClone(ISlide sourceSlide, ILayoutSlide destLayout)
```

Fügt eine Kopie einer angegebenen Folie am Ende der Sammlung hinzu.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| sourceSlide | [ISlide](../../com.aspose.slides/islide) | Zu klonende Folie. |
| destLayout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | Layoutfolie für die neue Folie. |

**Rückgabewert:**
[ISlide](../../com.aspose.slides/islide) - Neue Folie.

### insertClone(int index, ISlide sourceSlide, ILayoutSlide destLayout) {#insertClone-int-com.aspose.slides.ISlide-com.aspose.slides.ILayoutSlide-}
```
public final ISlide insertClone(int index, ISlide sourceSlide, ILayoutSlide destLayout)
```

Fügt eine Kopie einer angegebenen Folie an der angegebenen Position in die Sammlung ein.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | int | Index der neuen Folie. |
| sourceSlide | [ISlide](../../com.aspose.slides/islide) | Zu klonende Folie. |
| destLayout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | Layoutfolie für die neue Folie. |

**Rückgabewert:**
[ISlide](../../com.aspose.slides/islide) - Eingefügte Folie.

### addClone(ISlide sourceSlide, IMasterSlide destMaster, boolean allowCloneMissingLayout) {#addClone-com.aspose.slides.ISlide-com.aspose.slides.IMasterSlide-boolean-}
```
public final ISlide addClone(ISlide sourceSlide, IMasterSlide destMaster, boolean allowCloneMissingLayout)
```

Fügt eine Kopie einer angegebenen Quellfolie am Ende der Sammlung hinzu. Das passende Layout wird automatisch aus dem angegebenen Master ausgewählt (passendes Layout ist das Layout mit dem gleichen Typ oder Namen wie das Layout der Quellfolie). Wenn kein passendes Layout vorhanden ist, wird das Layout der Quellfolie geklont (wenn allowCloneMissingLayout true ist) oder es wird eine PptxEditException geworfen (wenn allowCloneMissingLayout false ist).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| sourceSlide | [ISlide](../../com.aspose.slides/islide) | Zu klonende Folie. |
| destMaster | [IMasterSlide](../../com.aspose.slides/imasterslide) | Masterfolie für die neue Folie. |
| allowCloneMissingLayout | boolean | Wenn im angegebenen Master kein passendes Layout existiert, wird das Layout der Quellfolie geklont (wenn allowCloneMissingLayout true ist) oder es wird eine PptxEditException geworfen (wenn allowCloneMissingLayout false ist). |

**Rückgabewert:**
[ISlide](../../com.aspose.slides/islide) - Neue Folie.

### insertClone(int index, ISlide sourceSlide, IMasterSlide destMaster, boolean allowCloneMissingLayout) {#insertClone-int-com.aspose.slides.ISlide-com.aspose.slides.IMasterSlide-boolean-}
```
public final ISlide insertClone(int index, ISlide sourceSlide, IMasterSlide destMaster, boolean allowCloneMissingLayout)
```

Fügt eine Kopie einer angegebenen Quellfolie an der angegebenen Position in die Sammlung ein. Das passende Layout wird automatisch aus dem angegebenen Master ausgewählt (passendes Layout ist das Layout mit dem gleichen Typ oder Namen wie das Layout der Quellfolie). Wenn kein passendes Layout vorhanden ist, wird das Layout der Quellfolie geklont (wenn allowCloneMissingLayout true ist) oder es wird eine PptxEditException geworfen (wenn allowCloneMissingLayout false ist).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | int | Index der neuen Folie. |
| sourceSlide | [ISlide](../../com.aspose.slides/islide) | Zu klonende Folie. |
| destMaster | [IMasterSlide](../../com.aspose.slides/imasterslide) | Masterfolie für die neue Folie. |
| allowCloneMissingLayout | boolean | Wenn im angegebenen Master kein passendes Layout existiert, wird das Layout der Quellfolie geklont (wenn allowCloneMissingLayout true ist) oder es wird eine PptxEditException geworfen (wenn allowCloneMissingLayout false ist). |

**Rückgabewert:**
[ISlide](../../com.aspose.slides/islide) - Eingefügte Folie.

### remove(ISlide value) {#remove-com.aspose.slides.ISlide-}
```
public final void remove(ISlide value)
```

Entfernt das erste Vorkommen eines bestimmten Objekts aus der Sammlung.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [ISlide](../../com.aspose.slides/islide) | Die zu entfernende Folie aus der Sammlung. |

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

Entfernt das Element am angegebenen Index der Sammlung.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | int | Der nullbasierte Index des zu entfernenden Elements. |

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<ISlide> iterator()
```

Gibt einen Enumerator zurück, der durch die Sammlung iteriert.

**Rückgabewert:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ISlide> - Ein IGenericEnumerator, der zum Durchlaufen der Sammlung verwendet werden kann.

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<ISlide> iteratorJava()
```

Gibt einen Java-Iterator für die gesamte Sammlung zurück.

**Rückgabewert:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ISlide> - Ein java.util.Iterator für die gesamte Sammlung.

### toArray() {#toArray--}
```
public final ISlide[] toArray()
```

Erstellt und gibt ein Array zurück, das alle Folien enthält.

**Rückgabewert:**
com.aspose.slides.ISlide[] - Array von [Slide](../../com.aspose.slides/slide)

### toArray(int startIndex, int count) {#toArray-int-int-}
```
public final ISlide[] toArray(int startIndex, int count)
```

Erstellt und gibt ein Array zurück, das alle Folien aus dem angegebenen Bereich enthält.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| startIndex | int | Index der ersten hinzuzufügenden Folie. |
| count | int | Anzahl der hinzuzufügenden Folien. |

**Rückgabewert:**
com.aspose.slides.ISlide[] - Array von [Slide](../../com.aspose.slides/slide)

### reorder(int index, ISlide slide) {#reorder-int-com.aspose.slides.ISlide-}
```
public final void reorder(int index, ISlide slide)
```

Verschiebt eine Folie aus der Sammlung an die angegebene Position.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | int | Zielindex. |
| slide | [ISlide](../../com.aspose.slides/islide) | Zu verschiebende Folie.

### reorder(int index, ISlide[] slides) {#reorder-int-com.aspose.slides.ISlide...-}
```
public final void reorder(int index, ISlide[] slides)
```

Verschiebt Folien aus der Sammlung an die angegebene Position. Folien werden beginnend mit dem Index in der Reihenfolge, in der sie in der Liste erscheinen, platziert.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | int | Zielindex. |
| slides | [ISlide\[\]](../../com.aspose.slides/islide) | Zu verschiebende Folien.

### indexOf(ISlide slide) {#indexOf-com.aspose.slides.ISlide-}
```
public final int indexOf(ISlide slide)
```

Gibt den Index der angegebenen Folie in der Sammlung zurück.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| slide | [ISlide](../../com.aspose.slides/islide) | Zu findende Folie.

**Rückgabewert:**
int - Index einer Folie oder -1, wenn die Folie nicht aus dieser Sammlung stammt.

### addFromPdf(String path) {#addFromPdf-java.lang.String-}
```
public final ISlide[] addFromPdf(String path)
```

Erstellt Folien aus dem PDF-Dokument und fügt sie am Ende der Sammlung hinzu.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>      pres.getSlides().addFromPdf("document.pdf");
>      pres.save("fromPdfDocument.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| path | java.lang.String | Pfad zum PDF-Dokument |

**Rückgabewert:**
com.aspose.slides.ISlide[] - Hinzugefügte Folien

### addFromPdf(String path, PdfImportOptions pdfImportOptions) {#addFromPdf-java.lang.String-com.aspose.slides.PdfImportOptions-}
```
public final ISlide[] addFromPdf(String path, PdfImportOptions pdfImportOptions)
```

Erstellt Folien aus dem PDF-Dokument und fügt sie am Ende der Sammlung unter Berücksichtigung der PDF-Importoptionen hinzu.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>      PdfImportOptions pdfImportOptions = new PdfImportOptions();
>      pdfImportOptions.setDetectTables(true);
>      pres.getSlides().addFromPdf("document.pdf", pdfImportOptions);
>      pres.save("fromPdfDocument.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| path | java.lang.String | Pfad zum PDF-Dokument |
| pdfImportOptions | [PdfImportOptions](../../com.aspose.slides/pdfimportoptions) | Optionen für den PDF-Import |

**Rückgabewert:**
com.aspose.slides.ISlide[] - Hinzugefügte Folien

### addFromPdf(InputStream pdfStream) {#addFromPdf-java.io.InputStream-}
```
public final ISlide[] addFromPdf(InputStream pdfStream)
```

Erstellt Folien aus dem PDF-Dokument und fügt sie am Ende der Sammlung hinzu.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream stream = new FileInputStream("document.pdf");
>      pres.getSlides().addFromPdf(stream);
> 
>      pres.save("fromPdfDocument.pptx", SaveFormat.Pptx);
>  } catch (IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| pdfStream | java.io.InputStream | Ein Stream, der als Quelle des PDF-Dokuments verwendet wird |

**Rückgabewert:**
com.aspose.slides.ISlide[] - Hinzugefügte Folien

### addFromPdf(InputStream pdfStream, PdfImportOptions pdfImportOptions) {#addFromPdf-java.io.InputStream-com.aspose.slides.PdfImportOptions-}
```
public final ISlide[] addFromPdf(InputStream pdfStream, PdfImportOptions pdfImportOptions)
```

Erstellt Folien aus dem PDF-Dokument und fügt sie am Ende der Sammlung hinzu.

--------------------

> ```
> Beispiel:
>  
>  Presentation pres = new Presentation();
>  try {
>      PdfImportOptions pdfImportOptions = new PdfImportOptions();
>      pdfImportOptions.setDetectTables(true);
> 
>      FileInputStream stream = new FileInputStream("document.pdf");
>      pres.getSlides().addFromPdf(stream, pdfImportOptions);
> 
>      pres.save("fromPdfDocument.pptx", SaveFormat.Pptx);
>  } catch (IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| pdfStream | java.io.InputStream | Ein Stream, der als Quelle des PDF-Dokuments verwendet wird |
| pdfImportOptions | [PdfImportOptions](../../com.aspose.slides/pdfimportoptions) | Optionen für den PDF-Import |

**Rückgabewert:**
com.aspose.slides.ISlide[] - Hinzugefügte Folien

### addFromHtml(String htmlText, IExternalResourceResolver resolver, String uri) {#addFromHtml-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-}
```
public final ISlide[] addFromHtml(String htmlText, IExternalResourceResolver resolver, String uri)
```

Erstellt Folien aus HTML-Text und fügt sie am Ende der Sammlung hinzu.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| htmlText | java.lang.String | HTML zum Hinzufügen. |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | Ein Callback-Objekt zum Abrufen externer Objekte. Wenn dieser Parameter null ist, werden alle externen Objekte ignoriert. |
| uri | java.lang.String | Eine URI des angegebenen HTML. Wird verwendet, um relative Links aufzulösen. |

**Rückgabewert:**
com.aspose.slides.ISlide[] - Hinzugefügte Folien.

### addFromHtml(String htmlText) {#addFromHtml-java.lang.String-}
```
public final ISlide[] addFromHtml(String htmlText)
```

Erstellt Folien aus HTML-Text und fügt sie am Ende der Sammlung hinzu.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| htmlText | java.lang.String | HTML zum Hinzufügen. |

**Rückgabewert:**
com.aspose.slides.ISlide[] - Hinzugefügte Folien

### addFromHtml(InputStream htmlStream, IExternalResourceResolver resolver, String uri) {#addFromHtml-java.io.InputStream-com.aspose.slides.IExternalResourceResolver-java.lang.String-}
```
public final ISlide[] addFromHtml(InputStream htmlStream, IExternalResourceResolver resolver, String uri)
```

Erstellt Folien aus HTML-Text und fügt sie am Ende der Sammlung hinzu.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| htmlStream | java.io.InputStream | Ein Stream-Objekt, das als Quelle einer HTML-Datei verwendet wird. |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | Ein Callback-Objekt zum Abrufen externer Objekte. Wenn dieser Parameter null ist, werden alle externen Objekte ignoriert. |
| uri | java.lang.String | Eine URI des angegebenen HTML. Wird verwendet, um relative Links aufzulösen. |

**Rückgabewert:**
com.aspose.slides.ISlide[] - Hinzugefügte Folien.

### addFromHtml(InputStream htmlStream) {#addFromHtml-java.io.InputStream-}
```
public final ISlide[] addFromHtml(InputStream htmlStream)
```

Erstellt Folien aus HTML-Text und fügt sie am Ende der Sammlung hinzu.

--------------------

> ```
> // Erstelle eine Instanz der Presentation-Klasse.
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream fos = null;
>      try {
>          fos = new FileInputStream("file.html");
>          // Rufe die AddFromHtml-Methode auf und übergebe die HTML-Datei.
>          pres.getSlides().addFromHtml(fos);
>          // Verwende die Save-Methode, um die Datei als PowerPoint-Dokument zu speichern.
>          pres.save("MyPresentation.pptx", SaveFormat.Pptx);
>      } finally {
>          if (fos != null) fos.close();
>      }
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| htmlStream | java.io.InputStream | Ein Stream-Objekt, das als Quelle einer HTML-Datei verwendet wird. |

**Rückgabewert:**
com.aspose.slides.ISlide[] - Hinzugefügte Folien

### insertFromHtml(int index, String htmlText, IExternalResourceResolver resolver, String uri) {#insertFromHtml-int-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-}
```
public final ISlide[] insertFromHtml(int index, String htmlText, IExternalResourceResolver resolver, String uri)
```

Erstellt Folien aus HTML-Text und fügt sie an der angegebenen Position in die Sammlung ein.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | int | Position zum Einfügen. |
| htmlText | java.lang.String | HTML zum Hinzufügen. |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | Ein Callback-Objekt zum Abrufen externer Objekte. Wenn dieser Parameter null ist, werden alle externen Objekte ignoriert. |
| uri | java.lang.String | Eine URI des angegebenen HTML. Wird verwendet, um relative Links aufzulösen. |

**Rückgabewert:**
com.aspose.slides.ISlide[] - Hinzugefügte Folien.

### insertFromHtml(int index, String htmlText, IExternalResourceResolver resolver, String uri, boolean useSlideWithIndexAsStart) {#insertFromHtml-int-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-boolean-}
```
public final ISlide[] insertFromHtml(int index, String htmlText, IExternalResourceResolver resolver, String uri, boolean useSlideWithIndexAsStart)
```

Erstellt Folien aus HTML-Text und fügt sie an der angegebenen Position in die Sammlung ein.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | int | Position zum Einfügen. |
| htmlText | java.lang.String | HTML zum Hinzufügen. |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | Ein Callback-Objekt zum Abrufen externer Objekte. Wenn dieser Parameter null ist, werden alle externen Objekte ignoriert. |
| uri | java.lang.String | Eine URI des angegebenen HTML. Wird verwendet, um relative Links aufzulösen. |
| useSlideWithIndexAsStart | boolean | Dieser Parameter bestimmt, wie die Einfügung beginnt: von einer neuen Folie oder von der Folie mit dem angegebenen Index. Wenn **true**, beginnt die Dateneinfügung in einem leeren Bereich der Folie mit dem angegebenen Index. Wenn **false**, werden die Daten zu den erstellten Folien hinzugefügt. |

**Rückgabewert:**
com.aspose.slides.ISlide[] - Hinzugefügte Folien.

### insertFromHtml(int index, String htmlText) {#insertFromHtml-int-java.lang.String-}
```
public final ISlide[] insertFromHtml(int index, String htmlText)
```

Erstellt Folien aus HTML-Text und fügt sie an der angegebenen Position in die Sammlung ein.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | int | Position zum Einfügen. |
| htmlText | java.lang.String | HTML zum Hinzufügen. |

**Rückgabewert:**
com.aspose.slides.ISlide[] - Hinzugefügte Folien

### insertFromHtml(int index, String htmlText, boolean useSlideWithIndexAsStart) {#insertFromHtml-int-java.lang.String-boolean-}
```
public final ISlide[] insertFromHtml(int index, String htmlText, boolean useSlideWithIndexAsStart)
```

Erstellt Folien aus HTML-Text und fügt sie an der angegebenen Position in die Sammlung ein.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | int | Position zum Einfügen. |
| htmlText | java.lang.String | HTML zum Hinzufügen. |
| useSlideWithIndexAsStart | boolean | Dieser Parameter bestimmt, wie die Einfügung beginnt: von einer neuen Folie oder von der Folie mit dem angegebenen Index. Wenn **true**, beginnt die Dateneinfügung in einem leeren Bereich der Folie mit dem angegebenen Index. Wenn **false**, werden die Daten zu den erstellten Folien hinzugefügt. |

**Rückgabewert:**
com.aspose.slides.ISlide[] - Hinzugefügte Folien

### insertFromHtml(int index, InputStream htmlStream, IExternalResourceResolver resolver, String uri) {#insertFromHtml-int-java.io.InputStream-com.aspose.slides.IExternalResourceResolver-java.lang.String-}
```
public final ISlide[] insertFromHtml(int index, InputStream htmlStream, IExternalResourceResolver resolver, String uri)
```

Erstellt Folien aus HTML-Text und fügt sie an der angegebenen Position in die Sammlung ein.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | int | Position zum Einfügen. |
| htmlStream | java.io.InputStream | Ein Stream-Objekt, das als Quelle einer HTML-Datei verwendet wird. |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | Ein Callback-Objekt zum Abrufen externer Objekte. Wenn dieser Parameter null ist, werden alle externen Objekte ignoriert. |
| uri | java.lang.String | Eine URI des angegebenen HTML. Wird verwendet, um relative Links aufzulösen. |

**Rückgabewert:**
com.aspose.slides.ISlide[] - Hinzugefügte Folien.

### insertFromHtml(int index, InputStream htmlStream, IExternalResourceResolver resolver, String uri, boolean useSlideWithIndexAsStart) {#insertFromHtml-int-java.io.InputStream-com.aspose.slides.IExternalResourceResolver-java.lang.String-boolean-}
```
public final ISlide[] insertFromHtml(int index, InputStream htmlStream, IExternalResourceResolver resolver, String uri, boolean useSlideWithIndexAsStart)
```

Erstellt Folien aus HTML-Text und fügt sie an der angegebenen Position in die Sammlung ein.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | int | Position zum Einfügen. |
| htmlStream | java.io.InputStream | Ein Stream-Objekt, das als Quelle einer HTML-Datei verwendet wird. |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | Ein Callback-Objekt zum Abrufen externer Objekte. Wenn dieser Parameter null ist, werden alle externen Objekte ignoriert. |
| uri | java.lang.String | Eine URI des angegebenen HTML. Wird verwendet, um relative Links aufzulösen. |
| useSlideWithIndexAsStart | boolean | Dieser Parameter bestimmt, wie die Einfügung beginnt: von einer neuen Folie oder von der Folie mit dem angegebenen Index. Wenn **true**, beginnt die Dateneinfügung in einem leeren Bereich der Folie mit dem angegebenen Index. Wenn **false**, werden die Daten zu den erstellten Folien hinzugefügt. |

**Rückgabewert:**
com.aspose.slides.ISlide[] - Hinzugefügte Folien.

### insertFromHtml(int index, InputStream htmlStream) {#insertFromHtml-int-java.io.InputStream-}
```
public final ISlide[] insertFromHtml(int index, InputStream htmlStream)
```

Erstellt Folien aus HTML-Text und fügt sie an der angegebenen Position in die Sammlung ein.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | int | Position zum Einfügen. |
| htmlStream | java.io.InputStream | Ein Stream-Objekt, das als Quelle einer HTML-Datei verwendet wird. |

**Rückgabewert:**
com.aspose.slides.ISlide[] - Hinzugefügte Folien

### insertFromHtml(int index, InputStream htmlStream, boolean useSlideWithIndexAsStart) {#insertFromHtml-int-java.io.InputStream-boolean-}
```
public final ISlide[] insertFromHtml(int index, InputStream htmlStream, boolean useSlideWithIndexAsStart)
```

Erstellt Folien aus HTML-Text und fügt sie an der angegebenen Position in die Sammlung ein.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | int | Position zum Einfügen. |
| htmlStream | java.io.InputStream | Ein Stream-Objekt, das als Quelle einer HTML-Datei verwendet wird. |
| useSlideWithIndexAsStart | boolean | Dieser Parameter bestimmt, wie die Einfügung beginnt: von einer neuen Folie oder von der Folie mit dem angegebenen Index. Wenn **true**, beginnt die Dateneinfügung in einem leeren Bereich der Folie mit dem angegebenen Index. Wenn **false**, werden die Daten zu den erstellten Folien hinzugefügt. |

**Rückgabewert:**
com.aspose.slides.ISlide[] - Hinzugefügte Folien

### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

Kopiert alle Elemente aus der Sammlung in das angegebene Array.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Zielarray. |
| index | int | Startindex im Zielarray.

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

Gibt einen Wert zurück, der angibt, ob der Zugriff auf die Sammlung synchronisiert ist (thread-sicher). Nur-Lesen boolean.

**Rückgabewert:**
boolean

### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

Gibt die Synchronisationswurzel zurück. Nur-Lesen Object.

**Rückgabewert:**
java.lang.Object