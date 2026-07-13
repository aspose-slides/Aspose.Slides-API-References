---
title: ISlideCollection
second_title: Aspose.Slides för Android via Java API-referens
description: Representerar en samling av bilder.
type: docs
url: /sv/com.aspose.slides/islidecollection/
---
**Alla implementerade gränssnitt:**  
com.aspose.slides.IGenericCollection  
```
public interface ISlideCollection extends IGenericCollection<ISlide>
```

Representerar en samling av bilder.

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Hämtar elementet på angivet index. |
| [addClone(ISlide sourceSlide)](#addClone-com.aspose.slides.ISlide-) | Lägger till en kopia av en specificerad bild i slutet av samlingen. |
| [addClone(ISlide sourceSlide, ISection section)](#addClone-com.aspose.slides.ISlide-com.aspose.slides.ISection-) | Lägger till en kopia av en specificerad bild i slutet av den specificerade sektionen. |
| [insertClone(int index, ISlide sourceSlide)](#insertClone-int-com.aspose.slides.ISlide-) | Infogar en kopia av en specificerad bild på angiven position i samlingen. |
| [addEmptySlide(ILayoutSlide layout)](#addEmptySlide-com.aspose.slides.ILayoutSlide-) | Lägger till en ny tom bild i slutet av samlingen. |
| [insertEmptySlide(int index, ILayoutSlide layout)](#insertEmptySlide-int-com.aspose.slides.ILayoutSlide-) | Infogar en kopia av en specificerad bild på angiven position i samlingen. |
| [addClone(ISlide sourceSlide, ILayoutSlide destLayout)](#addClone-com.aspose.slides.ISlide-com.aspose.slides.ILayoutSlide-) | Lägger till en kopia av en specificerad bild i slutet av samlingen. |
| [insertClone(int index, ISlide sourceSlide, ILayoutSlide destLayout)](#insertClone-int-com.aspose.slides.ISlide-com.aspose.slides.ILayoutSlide-) | Infogar en kopia av en specificerad bild på angiven position i samlingen. |
| [addClone(ISlide sourceSlide, IMasterSlide destMaster, boolean allowCloneMissingLayout)](#addClone-com.aspose.slides.ISlide-com.aspose.slides.IMasterSlide-boolean-) | Lägger till en kopia av en specificerad källbild i slutet av samlingen. |
| [insertClone(int index, ISlide sourceSlide, IMasterSlide destMaster, boolean allowCloneMissingLayout)](#insertClone-int-com.aspose.slides.ISlide-com.aspose.slides.IMasterSlide-boolean-) | Infogar en kopia av en specificerad källbild på angiven position i samlingen. |
| [remove(ISlide value)](#remove-com.aspose.slides.ISlide-) | Tar bort den första förekomsten av ett specifikt objekt från samlingen. |
| [removeAt(int index)](#removeAt-int-) | Tar bort elementet på det angivna indexet i samlingen. |
| [toArray()](#toArray--) | Skapar och returnerar en matris med alla bilder i den. |
| [toArray(int startIndex, int count)](#toArray-int-int-) | Skapar och returnerar en matris med alla bilder från det angivna intervallet i den. |
| [reorder(int index, ISlide slide)](#reorder-int-com.aspose.slides.ISlide-) | Flyttar bild från samlingen till den specificerade positionen. |
| [reorder(int index, ISlide[] slides)](#reorder-int-com.aspose.slides.ISlide...-) | Flyttar bilder från samlingen till den specificerade positionen. |
| [indexOf(ISlide slide)](#indexOf-com.aspose.slides.ISlide-) | Returnerar ett index för den specificerade bilden i samlingen. |
| [addFromPdf(String path)](#addFromPdf-java.lang.String-) | Skapar bilder från PDF-dokumentet och lägger till dem i slutet av samlingen. |
| [addFromPdf(String path, PdfImportOptions pdfImportOptions)](#addFromPdf-java.lang.String-com.aspose.slides.PdfImportOptions-) | Skapar bilder från PDF-dokumentet och lägger till dem i slutet av samlingen med hänsyn till pdf-importalternativen. |
| [addFromPdf(InputStream pdfStream, PdfImportOptions pdfImportOptions)](#addFromPdf-java.io.InputStream-com.aspose.slides.PdfImportOptions-) | Skapar bilder från PDF-dokumentet och lägger till dem i slutet av samlingen. |
| [addFromPdf(InputStream pdfStream)](#addFromPdf-java.io.InputStream-) | Skapar bilder från PDF-dokumentet och lägger till dem i slutet av samlingen. |
| [addFromHtml(String htmlText, IExternalResourceResolver resolver, String uri)](#addFromHtml-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-) | Skapar bilder från HTML-text och lägger till dem i slutet av samlingen. |
| [addFromHtml(String htmlText)](#addFromHtml-java.lang.String-) | Skapar bilder från HTML-text och lägger till dem i slutet av samlingen. |
| [addFromHtml(InputStream htmlStream, IExternalResourceResolver resolver, String uri)](#addFromHtml-java.io.InputStream-com.aspose.slides.IExternalResourceResolver-java.lang.String-) | Skapar bilder från HTML-text och lägger till dem i slutet av samlingen. |
| [addFromHtml(InputStream htmlStream)](#addFromHtml-java.io.InputStream-) | Skapar bilder från HTML-text och lägger till dem i slutet av samlingen. |
| [insertFromHtml(int index, String htmlText, IExternalResourceResolver resolver, String uri)](#insertFromHtml-int-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-) | Skapar bilder från HTML-text och infogar dem i samlingen på den angivna positionen. |
| [insertFromHtml(int index, String htmlText)](#insertFromHtml-int-java.lang.String-) | Skapar bilder från HTML-text och infogar dem i samlingen på den angivna positionen. |
| [insertFromHtml(int index, InputStream htmlStream, IExternalResourceResolver resolver, String uri)](#insertFromHtml-int-java.io.InputStream-com.aspose.slides.IExternalResourceResolver-java.lang.String-) | Skapar bilder från HTML-text och infogar dem i samlingen på den angivna positionen. |
| [insertFromHtml(int index, InputStream htmlStream)](#insertFromHtml-int-java.io.InputStream-) | Skapar bilder från HTML-text och infogar dem i samlingen på den angivna positionen. |
| [insertFromHtml(int index, String htmlText, boolean useSlideWithIndexAsStart)](#insertFromHtml-int-java.lang.String-boolean-) | Skapar bilder från HTML-text och infogar dem i samlingen på den angivna positionen. |
| [insertFromHtml(int index, String htmlText, IExternalResourceResolver resolver, String uri, boolean useSlideWithIndexAsStart)](#insertFromHtml-int-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-boolean-) | Skapar bilder från HTML-text och infogar dem i samlingen på den angivna positionen. |
| [insertFromHtml(int index, InputStream htmlStream, boolean useSlideWithIndexAsStart)](#insertFromHtml-int-java.io.InputStream-boolean-) | Skapar bilder från HTML-text och infogar dem i samlingen på den angivna positionen. |
| [insertFromHtml(int index, InputStream htmlStream, IExternalResourceResolver resolver, String uri, boolean useSlideWithIndexAsStart)](#insertFromHtml-int-java.io.InputStream-com.aspose.slides.IExternalResourceResolver-java.lang.String-boolean-) | Skapar bilder från HTML-text och infogar dem i samlingen på den angivna positionen. |

### get_Item(int index) {#get-Item-int-}
```
public abstract ISlide get_Item(int index)
```

Hämtar elementet på det angivna indexet. Skrivskyddad [ISlide](../../com.aspose.slides/islide).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | int |  |

**Returnerar:**
[ISlide](../../com.aspose.slides/islide)

### addClone(ISlide sourceSlide) {#addClone-com.aspose.slides.ISlide-}
```
public abstract ISlide addClone(ISlide sourceSlide)
```

Lägger till en kopia av en specificerad bild i slutet av samlingen.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| sourceSlide | [ISlide](../../com.aspose.slides/islide) | Bild att klona. |

---

När en bild klonas mellan olika presentationer kan också bildens master klonas. Ett internt register används för att spåra automatiskt klonade master för att förhindra skapandet av flera kloner av samma masterbild. Manuell kloning av masterbilder kommer varken att hindras eller registreras. Om du behöver mer kontroll över kloningsprocessen, använd \#addClone(ISlide,ILayoutSlide).addClone(ISlide,ILayoutSlide) eller \#addClone(ISlide,IMasterSlide,boolean).addClone(ISlide,IMasterSlide,boolean) för att klona bilder, [IGlobalLayoutSlideCollection.addClone(ILayoutSlide)](../../com.aspose.slides/igloballayoutslidecollection\#addClone-ILayoutSlide-) eller [IGlobalLayoutSlideCollection.addClone(ILayoutSlide,IMasterSlide)](../../com.aspose.slides/igloballayoutslidecollection\#addClone-ILayoutSlide-IMasterSlide-) för att klona layouter och [IMasterSlideCollection.addClone(IMasterSlide)](../../com.aspose.slides/imasterslidecollection\#addClone-IMasterSlide-) för att klona master.

**Returnerar:**
[ISlide](../../com.aspose.slides/islide) - Ny bild.

### addClone(ISlide sourceSlide, ISection section) {#addClone-com.aspose.slides.ISlide-com.aspose.slides.ISection-}
```
public abstract ISlide addClone(ISlide sourceSlide, ISection section)
```

Lägger till en kopia av en specificerad bild i slutet av den specificerade sektionen.

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
| section | [ISection](../../com.aspose.slides/isection) | Sektion för en ny bild. |

**Returnerar:**
[ISlide](../../com.aspose.slides/islide) - Ny bild.

### insertClone(int index, ISlide sourceSlide) {#insertClone-int-com.aspose.slides.ISlide-}
```
public abstract ISlide insertClone(int index, ISlide sourceSlide)
```

Infogar en kopia av en specificerad bild på angiven position i samlingen.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | int | Index för den nya bilden. |
| sourceSlide | [ISlide](../../com.aspose.slides/islide) | Bild att klona. |

---

När en bild klonas mellan olika presentationer kan också bildens master klonas. Ett internt register används för att spåra automatiskt klonade master för att förhindra skapandet av flera kloner av samma masterbild. Manuell kloning av masterbilder kommer varken att hindras eller registreras. Om du behöver mer kontroll över kloningsprocessen, använd \#insertClone(int,ISlide,ILayoutSlide).insertClone(int,ISlide,ILayoutSlide) eller \#insertClone(int,ISlide,IMasterSlide,boolean).insertClone(int,ISlide,IMasterSlide,boolean) för att klona bilder och [IMasterSlideCollection.addClone(IMasterSlide)](../../com.aspose.slides/imasterslidecollection\#addClone-IMasterSlide-) för att klona master.

**Returnerar:**
[ISlide](../../com.aspose.slides/islide) - Infogad bild.

### addEmptySlide(ILayoutSlide layout) {#addEmptySlide-com.aspose.slides.ILayoutSlide-}
```
public abstract ISlide addEmptySlide(ILayoutSlide layout)
```

Lägger till en ny tom bild i slutet av samlingen.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| layout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | Layout för en bild. |

**Returnerar:**
[ISlide](../../com.aspose.slides/islide) - Tillagd bild.

### insertEmptySlide(int index, ILayoutSlide layout) {#insertEmptySlide-int-com.aspose.slides.ILayoutSlide-}
```
public abstract ISlide insertEmptySlide(int index, ILayoutSlide layout)
```

Infogar en kopia av en specificerad bild på angiven position i samlingen.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | int | Index för en ny bild. |
| layout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | Layout för en bild. |

**Returnerar:**
[ISlide](../../com.aspose.slides/islide) - Infogad bild.

### addClone(ISlide sourceSlide, ILayoutSlide destLayout) {#addClone-com.aspose.slides.ISlide-com.aspose.slides.ILayoutSlide-}
```
public abstract ISlide addClone(ISlide sourceSlide, ILayoutSlide destLayout)
```

Lägger till en kopia av en specificerad bild i slutet av samlingen.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| sourceSlide | [ISlide](../../com.aspose.slides/islide) | Bild att klona. |
| destLayout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | Layoutbild för en ny bild. |

**Returnerar:**
[ISlide](../../com.aspose.slides/islide) - Ny bild.

### insertClone(int index, ISlide sourceSlide, ILayoutSlide destLayout) {#insertClone-int-com.aspose.slides.ISlide-com.aspose.slides.ILayoutSlide-}
```
public abstract ISlide insertClone(int index, ISlide sourceSlide, ILayoutSlide destLayout)
```

Infogar en kopia av en specificerad bild på angiven position i samlingen.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | int | Index för den nya bilden. |
| sourceSlide | [ISlide](../../com.aspose.slides/islide) | Bild att klona. |
| destLayout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | Layoutbild för en ny bild. |

**Returnerar:**
[ISlide](../../com.aspose.slides/islide) - Infogad bild.

### addClone(ISlide sourceSlide, IMasterSlide destMaster, boolean allowCloneMissingLayout) {#addClone-com.aspose.slides.ISlide-com.aspose.slides.IMasterSlide-boolean-}
```
public abstract ISlide addClone(ISlide sourceSlide, IMasterSlide destMaster, boolean allowCloneMissingLayout)
```

Lägger till en kopia av en specificerad källbild i slutet av samlingen. Lämplig layout väljs automatiskt från den specificerade master (lämplig layout är den layout som har samma Type eller Name som layouten för källbilden). Om det inte finns någon lämplig layout kommer layouten för källbilden att klonas (om allowCloneMissingLayout är true) eller så kastas ett PptxEditException (om allowCloneMissingLayout är false).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| sourceSlide | [ISlide](../../com.aspose.slides/islide) | Bild att klona. |
| destMaster | [IMasterSlide](../../com.aspose.slides/imasterslide) | Masterbild för en ny bild. |
| allowCloneMissingLayout | boolean | Om det inte finns någon lämplig layout i den specificerade master så kommer layouten för källbilden att klonas (om allowCloneMissingLayout är true) eller så kastas ett PptxEditException (om allowCloneMissingLayout är false). |

**Returnerar:**
[ISlide](../../com.aspose.slides/islide) - Ny bild.

### insertClone(int index, ISlide sourceSlide, IMasterSlide destMaster, boolean allowCloneMissingLayout) {#insertClone-int-com.aspose.slides.ISlide-com.aspose.slides.IMasterSlide-boolean-}
```
public abstract ISlide insertClone(int index, ISlide sourceSlide, IMasterSlide destMaster, boolean allowCloneMissingLayout)
```

Infogar en kopia av en specificerad källbild på angiven position i samlingen. Lämplig layout väljs automatiskt från den specificerade master (lämplig layout är den layout som har samma Type eller Name som layouten för källbilden). Om det inte finns någon lämplig layout kommer layouten för källbilden att klonas (om allowCloneMissingLayout är true) eller så kastas ett PptxEditException (om allowCloneMissingLayout är false).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | int | Index för den nya bilden. |
| sourceSlide | [ISlide](../../com.aspose.slides/islide) | Bild att klona. |
| destMaster | [IMasterSlide](../../com.aspose.slides/imasterslide) | Masterbild för en ny bild. |
| allowCloneMissingLayout | boolean | Om det inte finns någon lämplig layout i den specificerade master så kommer layouten för källbilden att klonas (om allowCloneMissingLayout är true) eller så kastas ett PptxEditException (om allowCloneMissingLayout är false). |

**Returnerar:**
[ISlide](../../com.aspose.slides/islide) - Infogad bild.

### remove(ISlide value) {#remove-com.aspose.slides.ISlide-}
```
public abstract void remove(ISlide value)
```

Tar bort den första förekomsten av ett specifikt objekt från samlingen.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [ISlide](../../com.aspose.slides/islide) | Bilden som ska tas bort från samlingen. |

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

Tar bort elementet på det angivna indexet i samlingen.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | int | Det nollbaserade indexet för elementet som ska tas bort. |

### toArray() {#toArray--}
```
public abstract ISlide[] toArray()
```

Skapar och returnerar en matris med alla bilder i den.

**Returnerar:**
com.aspose.slides.ISlide[] - Array of [ISlide](../../com.aspose.slides/islide)

### toArray(int startIndex, int count) {#toArray-int-int-}
```
public abstract ISlide[] toArray(int startIndex, int count)
```

Skapar och returnerar en matris med alla bilder från det angivna intervallet i den.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| startIndex | int | Ett index för den första bilden att lägga till. |
| count | int | Antalet bilder att lägga till. |

**Returnerar:**
com.aspose.slides.ISlide[] - Array of [ISlide](../../com.aspose.slides/islide)

### reorder(int index, ISlide slide) {#reorder-int-com.aspose.slides.ISlide-}
```
public abstract void reorder(int index, ISlide slide)
```

Flyttar bild från samlingen till den specificerade positionen.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | int | Målindex. |
| slide | [ISlide](../../com.aspose.slides/islide) | Bild att flytta. |

### reorder(int index, ISlide[] slides) {#reorder-int-com.aspose.slides.ISlide...-}
```
public abstract void reorder(int index, ISlide[] slides)
```

Flyttar bilder från samlingen till den specificerade positionen. Bilderna placeras med start från index i den ordning de visas i listan.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | int | Målindex. |
| slides | [ISlide\[\]](../../com.aspose.slides/islide) | Bilder att flytta. |

### indexOf(ISlide slide) {#indexOf-com.aspose.slides.ISlide-}
```
public abstract int indexOf(ISlide slide)
```

Returnerar ett index för den specificerade bilden i samlingen.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| slide | [ISlide](../../com.aspose.slides/islide) | Bild att hitta. |

**Returnerar:**
int - Index för en bild eller -1 om bilden inte kommer från den här samlingen.

### addFromPdf(String path) {#addFromPdf-java.lang.String-}
```
public abstract ISlide[] addFromPdf(String path)
```

Skapar bilder från PDF-dokumentet och lägger till dem i slutet av samlingen.

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
| path | java.lang.String | En sökväg till PDF-dokumentet |

**Returnerar:**
com.aspose.slides.ISlide[] - Added slides

### addFromPdf(String path, PdfImportOptions pdfImportOptions) {#addFromPdf-java.lang.String-com.aspose.slides.PdfImportOptions-}
```
public abstract ISlide[] addFromPdf(String path, PdfImportOptions pdfImportOptions)
```

Skapar bilder från PDF-dokumentet och lägger till dem i slutet av samlingen med hänsyn till pdf-importalternativen.

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
| path | java.lang.String | En sökväg till PDF-dokumentet |
| pdfImportOptions | [PdfImportOptions](../../com.aspose.slides/pdfimportoptions) | Alternativ för pdf-import |

**Returnerar:**
com.aspose.slides.ISlide[] - Added slides

### addFromPdf(InputStream pdfStream, PdfImportOptions pdfImportOptions) {#addFromPdf-java.io.InputStream-com.aspose.slides.PdfImportOptions-}
```
public abstract ISlide[] addFromPdf(InputStream pdfStream, PdfImportOptions pdfImportOptions)
```

Skapar bilder från PDF-dokumentet och lägger till dem i slutet av samlingen.

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
| pdfStream | java.io.InputStream | En ström som ska användas som källa för PDF-dokumentet |
| pdfImportOptions | [PdfImportOptions](../../com.aspose.slides/pdfimportoptions) | Alternativ för pdf-import |

**Returnerar:**
com.aspose.slides.ISlide[] - Added slides

### addFromPdf(InputStream pdfStream) {#addFromPdf-java.io.InputStream-}
```
public abstract ISlide[] addFromPdf(InputStream pdfStream)
```

Skapar bilder från PDF-dokumentet och lägger till dem i slutet av samlingen.

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
| pdfStream | java.io.InputStream | En ström som ska användas som källa för PDF-dokumentet |

**Returnerar:**
com.aspose.slides.ISlide[] - Added slides

### addFromHtml(String htmlText, IExternalResourceResolver resolver, String uri) {#addFromHtml-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-}
```
public abstract ISlide[] addFromHtml(String htmlText, IExternalResourceResolver resolver, String uri)
```

Skapar bilder från HTML-text och lägger till dem i slutet av samlingen.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| htmlText | java.lang.String | Html att lägga till. |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | Ett återuppringningsobjekt som används för att hämta externa objekt. Om den här parametern är null kommer alla externa objekt att ignoreras. |
| uri | java.lang.String | En URI för den specificerade HTML:n. Används för att lösa relativa länkar. |

**Returnerar:**
com.aspose.slides.ISlide[] - Added slides.

### addFromHtml(String htmlText) {#addFromHtml-java.lang.String-}
```
public abstract ISlide[] addFromHtml(String htmlText)
```

Skapar bilder från HTML-text och lägger till dem i slutet av samlingen.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| htmlText | java.lang.String | Html att lägga till. |

**Returnerar:**
com.aspose.slides.ISlide[] - Added slides

### addFromHtml(InputStream htmlStream, IExternalResourceResolver resolver, String uri) {#addFromHtml-java.io.InputStream-com.aspose.slides.IExternalResourceResolver-java.lang.String-}
```
public abstract ISlide[] addFromHtml(InputStream htmlStream, IExternalResourceResolver resolver, String uri)
```

Skapar bilder från HTML-text och lägger till dem i slutet av samlingen.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| htmlStream | java.io.InputStream | Ett Stream-objekt som kommer att användas som källa för en HTML-fil. |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | Ett återuppringningsobjekt som används för att hämta externa objekt. Om den här parametern är null kommer alla externa objekt att ignoreras. |
| uri | java.lang.String | En URI för den specificerade HTML:n. Används för att lösa relativa länkar. |

**Returnerar:**
com.aspose.slides.ISlide[] - Added slides.

### addFromHtml(InputStream htmlStream) {#addFromHtml-java.io.InputStream-}
```
public abstract ISlide[] addFromHtml(InputStream htmlStream)
```

Skapar bilder från HTML-text och lägger till dem i slutet av samlingen.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| htmlStream | java.io.InputStream | Ett Stream-objekt som kommer att användas som källa för en HTML-fil. |

**Returnerar:**
com.aspose.slides.ISlide[] - Added slides

### insertFromHtml(int index, String htmlText, IExternalResourceResolver resolver, String uri) {#insertFromHtml-int-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-}
```
public abstract ISlide[] insertFromHtml(int index, String htmlText, IExternalResourceResolver resolver, String uri)
```

Skapar bilder från HTML-text och infogar dem i samlingen på den angivna positionen.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | int | Position att infoga. |
| htmlText | java.lang.String | Html att lägga till. |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | Ett återuppringningsobjekt som används för att hämta externa objekt. Om den här parametern är null kommer alla externa objekt att ignoreras. |
| uri | java.lang.String | En URI för den specificerade HTML:n. Används för att lösa relativa länkar. |

**Returnerar:**
com.aspose.slides.ISlide[] - Added slides.

### insertFromHtml(int index, String htmlText) {#insertFromHtml-int-java.lang.String-}
```
public abstract ISlide[] insertFromHtml(int index, String htmlText)
```

Skapar bilder från HTML-text och infogar dem i samlingen på den angivna positionen.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | int | Position att infoga. |
| htmlText | java.lang.String | Html att lägga till. |

**Returnerar:**
com.aspose.slides.ISlide[] - Added slides

### insertFromHtml(int index, InputStream htmlStream, IExternalResourceResolver resolver, String uri) {#insertFromHtml-int-java.io.InputStream-com.aspose.slides.IExternalResourceResolver-java.lang.String-}
```
public abstract ISlide[] insertFromHtml(int index, InputStream htmlStream, IExternalResourceResolver resolver, String uri)
```

Skapar bilder från HTML-text och infogar dem i samlingen på den angivna positionen.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | int | Position att infoga. |
| htmlStream | java.io.InputStream | Ett Stream-objekt som kommer att användas som källa för en HTML-fil. |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | Ett återuppringningsobjekt som används för att hämta externa objekt. Om den här parametern är null kommer alla externa objekt att ignoreras. |
| uri | java.lang.String | En URI för den specificerade HTML:n. Används för att lösa relativa länkar. |

**Returnerar:**
com.aspose.slides.ISlide[] - Added slides.

### insertFromHtml(int index, InputStream htmlStream) {#insertFromHtml-int-java.io.InputStream-}
```
public abstract ISlide[] insertFromHtml(int index, InputStream htmlStream)
```

Skapar bilder från HTML-text och infogar dem i samlingen på den angivna positionen.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | int | Position att infoga. |
| htmlStream | java.io.InputStream | Ett Stream-objekt som kommer att användas som källa för en HTML-fil. |

**Returnerar:**
com.aspose.slides.ISlide[] - Added slides

### insertFromHtml(int index, String htmlText, boolean useSlideWithIndexAsStart) {#insertFromHtml-int-java.lang.String-boolean-}
```
public abstract ISlide[] insertFromHtml(int index, String htmlText, boolean useSlideWithIndexAsStart)
```

Skapar bilder från HTML-text och infogar dem i samlingen på den angivna positionen.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | int | Position att infoga. |
| htmlText | java.lang.String | Html att lägga till. |
| useSlideWithIndexAsStart | boolean | Denna flagga bestämmer hur insättningen ska startas: från en ny bild eller från bilden med det angivna indexet. Om **true**, startas datainmatning från ett tomt utrymme på bilden med det angivna indexet. Om **false**, läggs data till i de skapade bilderna. |

**Returnerar:**
com.aspose.slides.ISlide[] - Added slides

### insertFromHtml(int index, String htmlText, IExternalResourceResolver resolver, String uri, boolean useSlideWithIndexAsStart) {#insertFromHtml-int-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-boolean-}
```
public abstract ISlide[] insertFromHtml(int index, String htmlText, IExternalResourceResolver resolver, String uri, boolean useSlideWithIndexAsStart)
```

Skapar bilder från HTML-text och infogar dem i samlingen på den angivna positionen.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | int | Position att infoga. |
| htmlText | java.lang.String | Html att lägga till. |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | Ett återuppringningsobjekt som används för att hämta externa objekt. Om den här parametern är null kommer alla externa objekt att ignoreras. |
| uri | java.lang.String | En URI för den specificerade HTML:n. Används för att lösa relativa länkar. |
| useSlideWithIndexAsStart | boolean | Denna flagga bestämmer hur insättningen ska startas: från en ny bild eller från bilden med det angivna indexet. Om **true**, startas datainmatning från ett tomt utrymme på bilden med det angivna indexet. Om **false**, läggs data till i de skapade bilderna. |

**Returnerar:**
com.aspose.slides.ISlide[] - Added slides.

### insertFromHtml(int index, InputStream htmlStream, boolean useSlideWithIndexAsStart) {#insertFromHtml-int-java.io.InputStream-boolean-}
```
public abstract ISlide[] insertFromHtml(int index, InputStream htmlStream, boolean useSlideWithIndexAsStart)
```

Skapar bilder från HTML-text och infogar dem i samlingen på den angivna positionen.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | int | Position att infoga. |
| htmlStream | java.io.InputStream | Ett Stream-objekt som kommer att användas som källa för en HTML-fil. |
| useSlideWithIndexAsStart | boolean | Denna flagga bestämmer hur insättningen ska startas: från en ny bild eller från bilden med det angivna indexet. Om **true**, startas datainmatning från ett tomt utrymme på bilden med det angivna indexet. Om **false**, läggs data till i de skapade bilderna. |

**Returnerar:**
com.aspose.slides.ISlide[] - Added slides

### insertFromHtml(int index, InputStream htmlStream, IExternalResourceResolver resolver, String uri, boolean useSlideWithIndexAsStart) {#insertFromHtml-int-java.io.InputStream-com.aspose.slides.IExternalResourceResolver-java.lang.String-boolean-}
```
public abstract ISlide[] insertFromHtml(int index, InputStream htmlStream, IExternalResourceResolver resolver, String uri, boolean useSlideWithIndexAsStart)
```

Skapar bilder från HTML-text och infogar dem i samlingen på den angivna positionen.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | int | Position att infoga. |
| htmlStream | java.io.InputStream | Ett Stream-objekt som kommer att användas som källa för en HTML-fil. |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | Ett återuppringningsobjekt som används för att hämta externa objekt. Om den här parametern är null kommer alla externa objekt att ignoreras. |
| uri | java.lang.String | En URI för den specificerade HTML:n. Används för att lösa relativa länkar. |
| useSlideWithIndexAsStart | boolean | Denna flagga bestämmer hur insättningen ska startas: från en ny bild eller från bilden med det angivna indexet. Om **true**, startas datainmatning från ett tomt utrymme på bilden med det angivna indexet. Om **false**, läggs data till i de skapade bilderna. |

**Returnerar:**
com.aspose.slides.ISlide[] - Added slides.