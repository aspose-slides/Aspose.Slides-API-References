---
title: SlideCollection
second_title: Aspose.Slides för Android via Java API-referens
description: Representerar en samling av bilder.
type: docs
url: /sv/com.aspose.slides/slidecollection/
---
**Arv:**  
java.lang.Object, com.aspose.slides.DomObject

**Alla implementerade gränssnitt:**  
[com.aspose.slides.ISlideCollection](../../com.aspose.slides/islidecollection)
```
public final class SlideCollection extends DomObject<Presentation> implements ISlideCollection
```

Representerar en samling av bilder.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [size()](#size--) | Hämtar antalet element som faktiskt finns i samlingen. |
| [get_Item(int index)](#get-Item-int-) | Hämtar elementet på det angivna indexet. |
| [addClone(ISlide sourceSlide)](#addClone-com.aspose.slides.ISlide-) | Lägger till en kopia av en angiven bild i slutet av samlingen. |
| [addClone(ISlide sourceSlide, ISection section)](#addClone-com.aspose.slides.ISlide-com.aspose.slides.ISection-) | Lägger till en kopia av en angiven bild i slutet av den angivna sektionen. |
| [insertClone(int index, ISlide sourceSlide)](#insertClone-int-com.aspose.slides.ISlide-) | Infogar en kopia av en angiven bild på en angiven plats i samlingen. |
| [addEmptySlide(ILayoutSlide layout)](#addEmptySlide-com.aspose.slides.ILayoutSlide-) | Lägger till en ny tom bild i slutet av samlingen. |
| [insertEmptySlide(int index, ILayoutSlide layout)](#insertEmptySlide-int-com.aspose.slides.ILayoutSlide-) | Infogar en kopia av en angiven bild på en angiven plats i samlingen. |
| [addClone(ISlide sourceSlide, ILayoutSlide destLayout)](#addClone-com.aspose.slides.ISlide-com.aspose.slides.ILayoutSlide-) | Lägger till en kopia av en angiven bild i slutet av samlingen. |
| [insertClone(int index, ISlide sourceSlide, ILayoutSlide destLayout)](#insertClone-int-com.aspose.slides.ISlide-com.aspose.slides.ILayoutSlide-) | Infogar en kopia av en angiven bild på en angiven plats i samlingen. |
| [addClone(ISlide sourceSlide, IMasterSlide destMaster, boolean allowCloneMissingLayout)](#addClone-com.aspose.slides.ISlide-com.aspose.slides.IMasterSlide-boolean-) | Lägger till en kopia av en angiven källbild i slutet av samlingen. |
| [insertClone(int index, ISlide sourceSlide, IMasterSlide destMaster, boolean allowCloneMissingLayout)](#insertClone-int-com.aspose.slides.ISlide-com.aspose.slides.IMasterSlide-boolean-) | Infogar en kopia av en angiven källbild på en angiven plats i samlingen. |
| [remove(ISlide value)](#remove-com.aspose.slides.ISlide-) | Tar bort den första förekomsten av ett specifikt objekt från samlingen. |
| [removeAt(int index)](#removeAt-int-) | Tar bort elementet på det angivna indexet i samlingen. |
| [iterator()](#iterator--) | Returnerar en enumerator som itererar genom samlingen. |
| [iteratorJava()](#iteratorJava--) | Returnerar en java iterator för hela samlingen. |
| [toArray()](#toArray--) | Skapar och returnerar en array med alla bilder i den. |
| [toArray(int startIndex, int count)](#toArray-int-int-) | Skapar och returnerar en array med alla bilder från det angivna intervallet. |
| [reorder(int index, ISlide slide)](#reorder-int-com.aspose.slides.ISlide-) | Flyttar bild från samlingen till den angivna positionen. |
| [reorder(int index, ISlide[] slides)](#reorder-int-com.aspose.slides.ISlide...-) | Flyttar bilder från samlingen till den angivna positionen. |
| [indexOf(ISlide slide)](#indexOf-com.aspose.slides.ISlide-) | Returnerar ett index för den angivna bilden i samlingen. |
| [addFromPdf(String path)](#addFromPdf-java.lang.String-) | Skapar bilder från PDF-dokumentet och lägger till dem i slutet av samlingen. |
| [addFromPdf(String path, PdfImportOptions pdfImportOptions)](#addFromPdf-java.lang.String-com.aspose.slides.PdfImportOptions-) | Skapar bilder från PDF-dokumentet och lägger till dem i slutet av samlingen med hänsyn till PDF-importalternativen. |
| [addFromPdf(InputStream pdfStream)](#addFromPdf-java.io.InputStream-) | Skapar bilder från PDF-dokumentet och lägger till dem i slutet av samlingen. |
| [addFromPdf(InputStream pdfStream, PdfImportOptions pdfImportOptions)](#addFromPdf-java.io.InputStream-com.aspose.slides.PdfImportOptions-) | Skapar bilder från PDF-dokumentet och lägger till dem i slutet av samlingen. |
| [addFromHtml(String htmlText, IExternalResourceResolver resolver, String uri)](#addFromHtml-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-) | Skapar bilder från HTML-text och lägger till dem i slutet av samlingen. |
| [addFromHtml(String htmlText)](#addFromHtml-java.lang.String-) | Skapar bilder från HTML-text och lägger till dem i slutet av samlingen. |
| [addFromHtml(InputStream htmlStream, IExternalResourceResolver resolver, String uri)](#addFromHtml-java.io.InputStream-com.aspose.slides.IExternalResourceResolver-java.lang.String-) | Skapar bilder från HTML-text och lägger till dem i slutet av samlingen. |
| [addFromHtml(InputStream htmlStream)](#addFromHtml-java.io.InputStream-) | Skapar bilder från HTML-text och lägger till dem i slutet av samlingen. |
| [insertFromHtml(int index, String htmlText, IExternalResourceResolver resolver, String uri)](#insertFromHtml-int-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-) | Skapar bilder från HTML-text och infogar dem i samlingen på den angivna positionen. |
| [insertFromHtml(int index, String htmlText, IExternalResourceResolver resolver, String uri, boolean useSlideWithIndexAsStart)](#insertFromHtml-int-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-boolean-) | Skapar bilder från HTML-text och infogar dem i samlingen på den angivna positionen. |
| [insertFromHtml(int index, String htmlText)](#insertFromHtml-int-java.lang.String-) | Skapar bilder från HTML-text och infogar dem i samlingen på den angivna positionen. |
| [insertFromHtml(int index, String htmlText, boolean useSlideWithIndexAsStart)](#insertFromHtml-int-java.lang.String-boolean-) | Skapar bilder från HTML-text och infogar dem i samlingen på den angivna positionen. |
| [insertFromHtml(int index, InputStream htmlStream, IExternalResourceResolver resolver, String uri)](#insertFromHtml-int-java.io.InputStream-com.aspose.slides.IExternalResourceResolver-java.lang.String-) | Skapar bilder från HTML-text och infogar dem i samlingen på den angivna positionen. |
| [insertFromHtml(int index, InputStream htmlStream, IExternalResourceResolver resolver, String uri, boolean useSlideWithIndexAsStart)](#insertFromHtml-int-java.io.InputStream-com.aspose.slides.IExternalResourceResolver-java.lang.String-boolean-) | Skapar bilder från HTML-text och infogar dem i samlingen på den angivna positionen. |
| [insertFromHtml(int index, InputStream htmlStream)](#insertFromHtml-int-java.io.InputStream-) | Skapar bilder från HTML-text och infogar dem i samlingen på den angivna positionen. |
| [insertFromHtml(int index, InputStream htmlStream, boolean useSlideWithIndexAsStart)](#insertFromHtml-int-java.io.InputStream-boolean-) | Skapar bilder från HTML-text och infogar dem i samlingen på den angivna positionen. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Kopierar alla element från samlingen till den angivna arrayen. |
| [isSynchronized()](#isSynchronized--) | Returnerar ett värde som anger om åtkomst till samlingen är synkroniserad (trådsäker). |
| [getSyncRoot()](#getSyncRoot--) | Returnerar ett synkroniseringsrot. |

### size() {#size--}
```
public final int size()
```

Hämtar antalet element som faktiskt finns i samlingen. Skrivskyddad int.

**Returnerar:**
int

### get_Item(int index) {#get-Item-int-}
```
public final ISlide get_Item(int index)
```

Hämtar elementet på det angivna indexet. Skrivskyddad [Slide](../../com.aspose.slides/slide).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | int |  |

**Returnerar:**
[ISlide](../../com.aspose.slides/islide)

### addClone(ISlide sourceSlide) {#addClone-com.aspose.slides.ISlide-}
```
public final ISlide addClone(ISlide sourceSlide)
```

Lägger till en kopia av en angiven bild i slutet av samlingen.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| sourceSlide | [ISlide](../../com.aspose.slides/islide) | Bild att klona.

--------------------

När en bild klonas mellan olika presentationer kan bildens master också klonas. Ett internt register används för att spåra automatiskt klonade masters för att förhindra skapandet av flera kloner av samma masterbild. Manuell kloning av masterbilder kommer varken att förhindras eller registreras. Om du behöver mer kontroll över kloningsprocessen använd \#addClone(ISlide,ILayoutSlide).addClone(ISlide,ILayoutSlide) eller \#addClone(ISlide,IMasterSlide,boolean).addClone(ISlide,IMasterSlide,boolean) för att klona bilder, [IGlobalLayoutSlideCollection.addClone(ILayoutSlide)](../../com.aspose.slides/igloballayoutslidecollection\#addClone-ILayoutSlide-) eller [IGlobalLayoutSlideCollection.addClone(ILayoutSlide,IMasterSlide)](../../com.aspose.slides/igloballayoutslidecollection\#addClone-ILayoutSlide-IMasterSlide-) för att klona layouter och [IMasterSlideCollection.addClone(IMasterSlide)](../../com.aspose.slides/imasterslidecollection\#addClone-IMasterSlide-) för att klona masters. |

**Returnerar:**
[ISlide](../../com.aspose.slides/islide) - Ny bild.

### addClone(ISlide sourceSlide, ISection section) {#addClone-com.aspose.slides.ISlide-com.aspose.slides.ISection-}
```
public final ISlide addClone(ISlide sourceSlide, ISection section)
```

Lägger till en kopia av en angiven bild i slutet av den angivna sektionen.

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
>      // Nu innehåller den andra sektionen en kopia av den första bilden.
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| sourceSlide | [ISlide](../../com.aspose.slides/islide) | Bild att klona. |
| section | [ISection](../../com.aspose.slides/isection) | Sektion för den nya bilden. |

**Returnerar:**
[ISlide](../../com.aspose.slides/islide) - Ny bild.

### insertClone(int index, ISlide sourceSlide) {#insertClone-int-com.aspose.slides.ISlide-}
```
public final ISlide insertClone(int index, ISlide sourceSlide)
```

Infogar en kopia av en angiven bild på en angiven plats i samlingen.

--------------------

> ```
> The following example shows how to clone at another position within Presentation.
>  
>  // Instansiera Presentation-klassen som representerar en presentationsfil
>  Presentation pres = new Presentation("CloneWithInSamePresentation.pptx");
>  try {
>      // Klona den önskade bilden till slutet av samlingen av bilder i samma presentation
>      ISlideCollection slds = pres.getSlides();
>      // Klona den önskade bilden till det angivna indexet i samma presentation
>      slds.insertClone(2, pres.getSlides().get_Item(1));
>      // Skriv den modifierade presentationen till disk
>      pres.save("Aspose_CloneWithInSamePresentation_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to clone at another position within Presentation.
>  
>  // Instansiera Presentation-klassen för att läsa in källpresentationsfilen
>  Presentation srcPres = new Presentation("CloneAtEndOfAnother.pptx");
>  try {
>      // Instansiera Presentation-klassen för destinations-PPTX (där bilden ska klonas)
>      Presentation destPres = new Presentation();
>      try {
>          ISlideCollection slds = destPres.getSlides();
>          slds.insertClone(2, srcPres.getSlides().get_Item(0));
>          // Skriv destinationspresentationen till disk
>          destPres.save("Aspose2_out.pptx", SaveFormat.Pptx);
>      } finally {
>          if (destPres != null) destPres.dispose();
>      }
>  } finally {
>      if (srcPres != null) srcPres.dispose();
>  }
> ```


**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | int | Index för den nya bilden. |
| sourceSlide | [ISlide](../../com.aspose.slides/islide) | Bild att klona.

--------------------

När en bild klonas mellan olika presentationer kan bildens master också klonas. Ett internt register används för att spåra automatiskt klonade masters för att förhindra skapandet av flera kloner av samma masterbild. Manuell kloning av masterbilder kommer varken att förhindras eller registreras. Om du behöver mer kontroll över kloningsprocessen använd \#insertClone(int,ISlide,ILayoutSlide).insertClone(int,ISlide,ILayoutSlide) eller \#insertClone(int,ISlide,IMasterSlide,boolean).insertClone(int,ISlide,IMasterSlide,boolean) för att klona bilder och [IMasterSlideCollection.addClone(IMasterSlide)](../../com.aspose.slides/imasterslidecollection\#addClone-IMasterSlide-) för att klona masters. |

**Returnerar:**
[ISlide](../../com.aspose.slides/islide) - Infogad bild.

### addEmptySlide(ILayoutSlide layout) {#addEmptySlide-com.aspose.slides.ILayoutSlide-}
```
public final ISlide addEmptySlide(ILayoutSlide layout)
```

Lägger till en ny tom bild i slutet av samlingen.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| layout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | Layout för bilden. |

**Returnerar:**
[ISlide](../../com.aspose.slides/islide) - Tillagd bild.

### insertEmptySlide(int index, ILayoutSlide layout) {#insertEmptySlide-int-com.aspose.slides.ILayoutSlide-}
```
public final ISlide insertEmptySlide(int index, ILayoutSlide layout)
```

Infogar en kopia av en angiven bild på en angiven plats i samlingen.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | int | Index för den nya bilden. |
| layout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | Layout för bilden. |

**Returnerar:**
[ISlide](../../com.aspose.slides/islide) - Infogad bild.

### addClone(ISlide sourceSlide, ILayoutSlide destLayout) {#addClone-com.aspose.slides.ISlide-com.aspose.slides.ILayoutSlide-}
```
public final ISlide addClone(ISlide sourceSlide, ILayoutSlide destLayout)
```

Lägger till en kopia av en angiven bild i slutet av samlingen.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| sourceSlide | [ISlide](../../com.aspose.slides/islide) | Bild att klona. |
| destLayout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | Layout för den nya bilden. |

**Returnerar:**
[ISlide](../../com.aspose.slides/islide) - Ny bild.

### insertClone(int index, ISlide sourceSlide, ILayoutSlide destLayout) {#insertClone-int-com.aspose.slides.ISlide-com.aspose.slides.ILayoutSlide-}
```
public final ISlide insertClone(int index, ISlide sourceSlide, ILayoutSlide destLayout)
```

Infogar en kopia av en angiven bild på en angiven plats i samlingen.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | int | Index för den nya bilden. |
| sourceSlide | [ISlide](../../com.aspose.slides/islide) | Bild att klona. |
| destLayout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | Layout för den nya bilden. |

**Returnerar:**
[ISlide](../../com.aspose.slides/islide) - Infogad bild.

### addClone(ISlide sourceSlide, IMasterSlide destMaster, boolean allowCloneMissingLayout) {#addClone-com.aspose.slides.ISlide-com.aspose.slides.IMasterSlide-boolean-}
```
public final ISlide addClone(ISlide sourceSlide, IMasterSlide destMaster, boolean allowCloneMissingLayout)
```

Lägger till en kopia av en angiven källbild i slutet av samlingen. Lämplig layout väljs automatiskt från den angivna mastern (lämplig layout är den layout som har samma Typ eller Namn som layouten för källbilden). Om ingen lämplig layout finns klonas layouten för källbilden (om allowCloneMissingLayout är true) eller så kastas PptxEditException (om allowCloneMissingLayout är false).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| sourceSlide | [ISlide](../../com.aspose.slides/islide) | Bild att klona. |
| destMaster | [IMasterSlide](../../com.aspose.slides/imasterslide) | Masterbild för den nya bilden. |
| allowCloneMissingLayout | boolean | Om det inte finns någon lämplig layout i angiven master klonas layouten för källbilden (om allowCloneMissingLayout är true) eller så kastas PptxEditException (om allowCloneMissingLayout är false). |

**Returnerar:**
[ISlide](../../com.aspose.slides/islide) - Ny bild.

### insertClone(int index, ISlide sourceSlide, IMasterSlide destMaster, boolean allowCloneMissingLayout) {#insertClone-int-com.aspose.slides.ISlide-com.aspose.slides.IMasterSlide-boolean-}
```
public final ISlide insertClone(int index, ISlide sourceSlide, IMasterSlide destMaster, boolean allowCloneMissingLayout)
```

Infogar en kopia av en angiven källbild på en angiven plats i samlingen. Lämplig layout väljs automatiskt från den angivna mastern (lämplig layout är den layout som har samma Typ eller Namn som layouten för källbilden). Om ingen lämplig layout finns klonas layouten för källbilden (om allowCloneMissingLayout är true) eller så kastas PptxEditException (om allowCloneMissingLayout är false).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | int | Index för den nya bilden. |
| sourceSlide | [ISlide](../../com.aspose.slides/islide) | Bild att klona. |
| destMaster | [IMasterSlide](../../com.aspose.slides/imasterslide) | Masterbild för den nya bilden. |
| allowCloneMissingLayout | boolean | Om det inte finns någon lämplig layout i angiven master klonas layouten för källbilden (om allowCloneMissingLayout är true) eller så kastas PptxEditException (om allowCloneMissingLayout är false). |

**Returnerar:**
[ISlide](../../com.aspose.slides/islide) - Infogad bild.

### remove(ISlide value) {#remove-com.aspose.slides.ISlide-}
```
public final void remove(ISlide value)
```

Tar bort den första förekomsten av ett specifikt objekt från samlingen.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [ISlide](../../com.aspose.slides/islide) | Bilden som ska tas bort från samlingen. |

### removeAt(int index) {#removeAt-int-}
```
public final void remove(ISlide value)
```

Tar bort elementet på det angivna indexet i samlingen.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | int | Det nollbaserade indexet för elementet som ska tas bort. |

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<ISlide> iterator()
```

Returnerar en enumerator som itererar genom samlingen.

**Returnerar:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ISlide> - En IGenericEnumerator som kan användas för att iterera genom samlingen.

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<ISlide> iteratorJava()
```

Returnerar en java iterator för hela samlingen.

**Returnerar:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ISlide> - En java.util.Iterator för hela samlingen.

### toArray() {#toArray--}
```
public final ISlide[] toArray()
```

Skapar och returnerar en array med alla bilder i den.

**Returnerar:**
com.aspose.slides.ISlide[] - Array av [Slide](../../com.aspose.slides/slide)

### toArray(int startIndex, int count) {#toArray-int-int-}
```
public final ISlide[] toArray(int startIndex, int count)
```

Skapar och returnerar en array med alla bilder från det angivna intervallet.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| startIndex | int | Index för den första bilden som ska läggas till. |
| count | int | Antal bilder som ska läggas till. |

**Returnerar:**
com.aspose.slides.ISlide[] - Array av [Slide](../../com.aspose.slides/slide)

### reorder(int index, ISlide slide) {#reorder-int-com.aspose.slides.ISlide-}
```
public final void reorder(int index, ISlide slide)
```

Flyttar bild från samlingen till den angivna positionen.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | int | Målindex. |
| slide | [ISlide](../../com.aspose.slides/islide) | Bild att flytta. |

### reorder(int index, ISlide[] slides) {#reorder-int-com.aspose.slides.ISlide...-}
```
public final void reorder(int index, ISlide[] slides)
```

Flyttar bilder från samlingen till den angivna positionen. Bilderna placeras med början på indexet i den ordning de förekommer i listan.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | int | Målindex. |
| slides | [ISlide\[\]](../../com.aspose.slides/islide) | Bilder att flytta. |

### indexOf(ISlide slide) {#indexOf-com.aspose.slides.ISlide-}
```
public final int indexOf(ISlide slide)
```

Returnerar ett index för den angivna bilden i samlingen.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| slide | [ISlide](../../com.aspose.slides/islide) | Bild att söka efter. |

**Returnerar:**
int - Index för en bild eller -1 om bilden inte finns i denna samling.

### addFromPdf(String path) {#addFromPdf-java.lang.String-}
```
public final ISlide[] addFromPdf(String path)
```

Skapar bilder från PDF-dokumentet och lägger till dem i slutet av samlingen.

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

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| path | java.lang.String | Sökväg till PDF-dokumentet |

**Returnerar:**
com.aspose.slides.ISlide[] - Tillagda bilder

### addFromPdf(String path, PdfImportOptions pdfImportOptions) {#addFromPdf-java.lang.String-com.aspose.slides.PdfImportOptions-}
```
public final ISlide[] addFromPdf(String path, PdfImportOptions pdfImportOptions)
```

Skapar bilder från PDF-dokumentet och lägger till dem i slutet av samlingen med hänsyn till PDF-importalternativen.

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

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| path | java.lang.String | Sökväg till PDF-dokumentet |
| pdfImportOptions | [PdfImportOptions](../../com.aspose.slides/pdfimportoptions) | Alternativ för PDF-import |

**Returnerar:**
com.aspose.slides.ISlide[] - Tillagda bilder

### addFromPdf(InputStream pdfStream) {#addFromPdf-java.io.InputStream-}
```
public final ISlide[] addFromPdf(InputStream pdfStream)
```

Skapar bilder från PDF-dokumentet och lägger till dem i slutet av samlingen.

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

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| pdfStream | java.io.InputStream | En ström som kommer att användas som källa för PDF-dokumentet |

**Returnerar:**
com.aspose.slides.ISlide[] - Tillagda bilder

### addFromPdf(InputStream pdfStream, PdfImportOptions pdfImportOptions) {#addFromPdf-java.io.InputStream-com.aspose.slides.PdfImportOptions-}
```
public final ISlide[] addFromPdf(InputStream pdfStream, PdfImportOptions pdfImportOptions)
```

Skapar bilder från PDF-dokumentet och lägger till dem i slutet av samlingen.

--------------------

> ```
> Example:
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

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| pdfStream | java.io.InputStream | En ström som kommer att användas som källa för PDF-dokumentet |
| pdfImportOptions | [PdfImportOptions](../../com.aspose.slides/pdfimportoptions) | Alternativ för PDF-import |

**Returnerar:**
com.aspose.slides.ISlide[] - Tillagda bilder

### addFromHtml(String htmlText, IExternalResourceResolver resolver, String uri) {#addFromHtml-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-}
```
public final ISlide[] addFromHtml(String htmlText, IExternalResourceResolver resolver, String uri)
```

Skapar bilder från HTML-text och lägger till dem i slutet av samlingen.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| htmlText | java.lang.String | HTML att lägga till. |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | Ett återanropsobjekt som används för att hämta externa objekt. Om detta argument är null ignoreras alla externa objekt. |
| uri | java.lang.String | En URI för den angivna HTML-texten. Används för att lösa relativa länkar. |

**Returnerar:**
com.aspose.slides.ISlide[] - Tillagda bilder.

### addFromHtml(String htmlText) {#addFromHtml-java.lang.String-}
```
public final ISlide[] addFromHtml(String htmlText)
```

Skapar bilder från HTML-text och lägger till dem i slutet av samlingen.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| htmlText | java.lang.String | HTML att lägga till. |

**Returnerar:**
com.aspose.slides.ISlide[] - Tillagda bilder

### addFromHtml(InputStream htmlStream, IExternalResourceResolver resolver, String uri) {#addFromHtml-java.io.InputStream-com.aspose.slides.IExternalResourceResolver-java.lang.String-}
```
public final ISlide[] addFromHtml(InputStream htmlStream, IExternalResourceResolver resolver, String uri)
```

Skapar bilder från HTML-text och lägger till dem i slutet av samlingen.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| htmlStream | java.io.InputStream | En Stream-objekt som kommer att användas som källa för en HTML-fil. |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | Ett återanropsobjekt som används för att hämta externa objekt. Om detta argument är null ignoreras alla externa objekt. |
| uri | java.lang.String | En URI för den angivna HTML-texten. Används för att lösa relativa länkar. |

**Returnerar:**
com.aspose.slides.ISlide[] - Tillagda bilder.

### addFromHtml(InputStream htmlStream) {#addFromHtml-java.io.InputStream-}
```
public final ISlide[] addFromHtml(InputStream htmlStream)
```

Skapar bilder från HTML-text och lägger till dem i slutet av samlingen.

--------------------

> ```
> // Skapa en instans av Presentation-klassen.
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream fos = null;
>      try {
>          fos = new FileInputStream("file.html");
>          // Anropa AddFromHtml-metoden och skicka HTML-filen.
>          pres.getSlides().addFromHtml(fos);
>          // Använd Save-metoden för att spara filen som ett PowerPoint-dokument.
>          pres.save("MyPresentation.pptx", SaveFormat.Pptx);
>      } finally {
>          if (fos != null) fos.close();
>      }
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| htmlStream | java.io.InputStream | En Stream-objekt som kommer att användas som källa för en HTML-fil. |

**Returnerar:**
com.aspose.slides.ISlide[] - Tillagda bilder

### insertFromHtml(int index, String htmlText, IExternalResourceResolver resolver, String uri) {#insertFromHtml-int-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-}
```
public final ISlide[] insertFromHtml(int index, String htmlText, IExternalResourceResolver resolver, String uri)
```

Skapar bilder från HTML-text och infogar dem i samlingen på den angivna positionen.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | int | Position att infoga. |
| htmlText | java.lang.String | HTML att lägga till. |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | Ett återanropsobjekt som används för att hämta externa objekt. Om detta argument är null ignoreras alla externa objekt. |
| uri | java.lang.String | En URI för den angivna HTML-texten. Används för att lösa relativa länkar. |

**Returnerar:**
com.aspose.slides.ISlide[] - Tillagda bilder.

### insertFromHtml(int index, String htmlText, IExternalResourceResolver resolver, String uri, boolean useSlideWithIndexAsStart) {#insertFromHtml-int-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-boolean-}
```
public final ISlide[] insertFromHtml(int index, String htmlText, IExternalResourceResolver resolver, String uri, boolean useSlideWithIndexAsStart)
```

Skapar bilder från HTML-text och infogar dem i samlingen på den angivna positionen.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | int | Position att infoga. |
| htmlText | java.lang.String | HTML att lägga till. |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | Ett återanropsobjekt som används för att hämta externa objekt. Om detta argument är null ignoreras alla externa objekt. |
| uri | java.lang.String | En URI för den angivna HTML-texten. Används för att lösa relativa länkar. |
| useSlideWithIndexAsStart | boolean | Denna flagga bestämmer hur infogningen ska starta: från en ny bild eller från bilden med det angivna indexet. Om **true** startar infogningen från ett tomt utrymme på bilden med det angivna indexet. Om **false** läggs data till i de skapade bilderna. |

**Returnerar:**
com.aspose.slides.ISlide[] - Tillagda bilder.

### insertFromHtml(int index, String htmlText) {#insertFromHtml-int-java.lang.String-}
```
public final ISlide[] insertFromHtml(int index, String htmlText)
```

Skapar bilder från HTML-text och infogar dem i samlingen på den angivna positionen.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | int | Position att infoga. |
| htmlText | java.lang.String | HTML att lägga till. |

**Returnerar:**
com.aspose.slides.ISlide[] - Tillagda bilder

### insertFromHtml(int index, String htmlText, boolean useSlideWithIndexAsStart) {#insertFromHtml-int-java.lang.String-boolean-}
```
public final ISlide[] insertFromHtml(int index, String htmlText, boolean useSlideWithIndexAsStart)
```

Skapar bilder från HTML-text och infogar dem i samlingen på den angivna positionen.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | int | Position att infoga. |
| htmlText | java.lang.String | HTML att lägga till. |
| useSlideWithIndexAsStart | boolean | Denna flagga bestämmer hur infogningen ska starta: från en ny bild eller från bilden med det angivna indexet. Om **true** startar infogningen från ett tomt utrymme på bilden med det angivna indexet. Om **false** läggs data till i de skapade bilderna. |

**Returnerar:**
com.aspose.slides.ISlide[] - Tillagda bilder

### insertFromHtml(int index, InputStream htmlStream, IExternalResourceResolver resolver, String uri) {#insertFromHtml-int-java.io.InputStream-com.aspose.slides.IExternalResourceResolver-java.lang.String-}
```
public final ISlide[] insertFromHtml(int index, InputStream htmlStream, IExternalResourceResolver resolver, String uri)
```

Skapar bilder från HTML-text och infogar dem i samlingen på den angivna positionen.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | int | Position att infoga. |
| htmlStream | java.io.InputStream | En Stream-objekt som kommer att användas som källa för en HTML-fil. |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | Ett återanropsobjekt som används för att hämta externa objekt. Om detta argument är null ignoreras alla externa objekt. |
| uri | java.lang.String | En URI för den angivna HTML-texten. Används för att lösa relativa länkar. |

**Returnerar:**
com.aspose.slides.ISlide[] - Tillagda bilder.

### insertFromHtml(int index, InputStream htmlStream, IExternalResourceResolver resolver, String uri, boolean useSlideWithIndexAsStart) {#insertFromHtml-int-java.io.InputStream-com.aspose.slides.IExternalResourceResolver-java.lang.String-boolean-}
```
public final ISlide[] insertFromHtml(int index, InputStream htmlStream, IExternalResourceResolver resolver, String uri, boolean useSlideWithIndexAsStart)
```

Skapar bilder från HTML-text och infogar dem i samlingen på den angivna positionen.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | int | Position att infoga. |
| htmlStream | java.io.InputStream | En Stream-objekt som kommer att användas som källa för en HTML-fil. |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | Ett återanropsobjekt som används för att hämta externa objekt. Om detta argument är null ignoreras alla externa objekt. |
| uri | java.lang.String | En URI för den angivna HTML-texten. Används för att lösa relativa länkar. |
| useSlideWithIndexAsStart | boolean | Denna flagga bestämmer hur infogningen ska starta: från en ny bild eller från bilden med det angivna indexet. Om **true** startar infogningen från ett tomt utrymme på bilden med det angivna indexet. Om **false** läggs data till i de skapade bilderna. |

**Returnerar:**
com.aspose.slides.ISlide[] - Tillagda bilder.

### insertFromHtml(int index, InputStream htmlStream) {#insertFromHtml-int-java.io.InputStream-}
```
public final ISlide[] insertFromHtml(int index, InputStream htmlStream)
```

Skapar bilder från HTML-text och infogar dem i samlingen på den angivna positionen.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | int | Position att infoga. |
| htmlStream | java.io.InputStream | En Stream-objekt som kommer att användas som källa för en HTML-fil. |

**Returnerar:**
com.aspose.slides.ISlide[] - Tillagda bilder

### insertFromHtml(int index, InputStream htmlStream, boolean useSlideWithIndexAsStart) {#insertFromHtml-int-java.io.InputStream-boolean-}
```
public final ISlide[] insertFromHtml(int index, InputStream htmlStream, boolean useSlideWithIndexAsStart)
```

Skapar bilder från HTML-text och infogar dem i samlingen på den angivna positionen.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | int | Position att infoga. |
| htmlStream | java.io.InputStream | En Stream-objekt som kommer att användas som källa för en HTML-fil. |
| useSlideWithIndexAsStart | boolean | Denna flagga bestämmer hur infogningen ska starta: från en ny bild eller från bilden med det angivna indexet. Om **true** startar infogningen från ett tomt utrymme på bilden med det angivna indexet. Om **false** läggs data till i de skapade bilderna. |

**Returnerar:**
com.aspose.slides.ISlide[] - Tillagda bilder

### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

Kopierar alla element från samlingen till den angivna arrayen.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Målarry. |
| index | int | Startindex i målarry. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

Returnerar ett värde som anger om åtkomst till samlingen är synkroniserad (trådsäker). Skrivskyddad boolean.

**Returnerar:**
boolean

### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

Returnerar ett synkroniseringsrot. Skrivskyddad Object.

**Returnerar:**
java.lang.Object