---
title: ISlideCollection
second_title: Aspose.Slides voor Android via Java API-referentie
description: Stelt een collectie van dia's voor.
type: docs
url: /nl/com.aspose.slides/islidecollection/
---
**Alle geïmplementeerde interfaces:**
com.aspose.slides.IGenericCollection
```
public interface ISlideCollection extends IGenericCollection<ISlide>
```

Stelt een collectie van dia's voor.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Haalt het element op op de opgegeven index. |
| [addClone(ISlide sourceSlide)](#addClone-com.aspose.slides.ISlide-) | Voegt een kopie van een opgegeven dia toe aan het einde van de collectie. |
| [addClone(ISlide sourceSlide, ISection section)](#addClone-com.aspose.slides.ISlide-com.aspose.slides.ISection-) | Voegt een kopie van een opgegeven dia toe aan het einde van de opgegeven sectie. |
| [insertClone(int index, ISlide sourceSlide)](#insertClone-int-com.aspose.slides.ISlide-) | Voegt een kopie van een opgegeven dia in op de opgegeven positie in de collectie. |
| [addEmptySlide(ILayoutSlide layout)](#addEmptySlide-com.aspose.slides.ILayoutSlide-) | Voegt een nieuwe lege dia toe aan het einde van de collectie. |
| [insertEmptySlide(int index, ILayoutSlide layout)](#insertEmptySlide-int-com.aspose.slides.ILayoutSlide-) | Voegt een kopie van een opgegeven dia in op de opgegeven positie in de collectie. |
| [addClone(ISlide sourceSlide, ILayoutSlide destLayout)](#addClone-com.aspose.slides.ISlide-com.aspose.slides.ILayoutSlide-) | Voegt een kopie van een opgegeven dia toe aan het einde van de collectie. |
| [insertClone(int index, ISlide sourceSlide, ILayoutSlide destLayout)](#insertClone-int-com.aspose.slides.ISlide-com.aspose.slides.ILayoutSlide-) | Voegt een kopie van een opgegeven dia in op de opgegeven positie in de collectie. |
| [addClone(ISlide sourceSlide, IMasterSlide destMaster, boolean allowCloneMissingLayout)](#addClone-com.aspose.slides.ISlide-com.aspose.slides.IMasterSlide-boolean-) | Voegt een kopie van een opgegeven bron-dia toe aan het einde van de collectie. |
| [insertClone(int index, ISlide sourceSlide, IMasterSlide destMaster, boolean allowCloneMissingLayout)](#insertClone-int-com.aspose.slides.ISlide-com.aspose.slides.IMasterSlide-boolean-) | Voegt een kopie van een opgegeven bron-dia in op de opgegeven positie in de collectie. |
| [remove(ISlide value)](#remove-com.aspose.slides.ISlide-) | Verwijdert de eerste voorkoming van een specifiek object uit de collectie. |
| [removeAt(int index)](#removeAt-int-) | Verwijdert het element op de opgegeven index van de collectie. |
| [toArray()](#toArray--) | Maakt een array met alle dia's en retourneert deze. |
| [toArray(int startIndex, int count)](#toArray-int-int-) | Maakt een array met alle dia's uit het opgegeven bereik en retourneert deze. |
| [reorder(int index, ISlide slide)](#reorder-int-com.aspose.slides.ISlide-) | Verplaatst een dia uit de collectie naar de opgegeven positie. |
| [reorder(int index, ISlide[] slides)](#reorder-int-com.aspose.slides.ISlide...-) | Verplaatst dia's uit de collectie naar de opgegeven positie. Dia's worden geplaatst beginnend bij de index in de volgorde waarin ze in de lijst voorkomen. |
| [indexOf(ISlide slide)](#indexOf-com.aspose.slides.ISlide-) | Retourneert een index van de opgegeven dia in de collectie. |
| [addFromPdf(String path)](#addFromPdf-java.lang.String-) | Maakt dia's van het PDF-document en voegt ze toe aan het einde van de collectie. |
| [addFromPdf(String path, PdfImportOptions pdfImportOptions)](#addFromPdf-java.lang.String-com.aspose.slides.PdfImportOptions-) | Maakt dia's van het PDF-document en voegt ze toe aan het einde van de collectie met inachtneming van de PDF-importopties. |
| [addFromPdf(InputStream pdfStream, PdfImportOptions pdfImportOptions)](#addFromPdf-java.io.InputStream-com.aspose.slides.PdfImportOptions-) | Maakt dia's van het PDF-document en voegt ze toe aan het einde van de collectie. |
| [addFromPdf(InputStream pdfStream)](#addFromPdf-java.io.InputStream-) | Maakt dia's van het PDF-document en voegt ze toe aan het einde van de collectie. |
| [addFromHtml(String htmlText, IExternalResourceResolver resolver, String uri)](#addFromHtml-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-) | Maakt dia's van HTML-tekst en voegt ze toe aan het einde van de collectie. |
| [addFromHtml(String htmlText)](#addFromHtml-java.lang.String-) | Maakt dia's van HTML-tekst en voegt ze toe aan het einde van de collectie. |
| [addFromHtml(InputStream htmlStream, IExternalResourceResolver resolver, String uri)](#addFromHtml-java.io.InputStream-com.aspose.slides.IExternalResourceResolver-java.lang.String-) | Maakt dia's van HTML-tekst en voegt ze toe aan het einde van de collectie. |
| [addFromHtml(InputStream htmlStream)](#addFromHtml-java.io.InputStream-) | Maakt dia's van HTML-tekst en voegt ze toe aan het einde van de collectie. |
| [insertFromHtml(int index, String htmlText, IExternalResourceResolver resolver, String uri)](#insertFromHtml-int-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-) | Maakt dia's van HTML-tekst en voegt ze in op de opgegeven positie in de collectie. |
| [insertFromHtml(int index, String htmlText)](#insertFromHtml-int-java.lang.String-) | Maakt dia's van HTML-tekst en voegt ze in op de opgegeven positie in de collectie. |
| [insertFromHtml(int index, InputStream htmlStream, IExternalResourceResolver resolver, String uri)](#insertFromHtml-int-java.io.InputStream-com.aspose.slides.IExternalResourceResolver-java.lang.String-) | Maakt dia's van HTML-tekst en voegt ze in op de opgegeven positie in de collectie. |
| [insertFromHtml(int index, InputStream htmlStream)](#insertFromHtml-int-java.io.InputStream-) | Maakt dia's van HTML-tekst en voegt ze in op de opgegeven positie in de collectie. |
| [insertFromHtml(int index, String htmlText, boolean useSlideWithIndexAsStart)](#insertFromHtml-int-java.lang.String-boolean-) | Maakt dia's van HTML-tekst en voegt ze in op de opgegeven positie in de collectie. |
| [insertFromHtml(int index, String htmlText, IExternalResourceResolver resolver, String uri, boolean useSlideWithIndexAsStart)](#insertFromHtml-int-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-boolean-) | Maakt dia's van HTML-tekst en voegt ze in op de opgegeven positie in de collectie. |
| [insertFromHtml(int index, InputStream htmlStream, boolean useSlideWithIndexAsStart)](#insertFromHtml-int-java.io.InputStream-boolean-) | Maakt dia's van HTML-tekst en voegt ze in op de opgegeven positie in de collectie. |
| [insertFromHtml(int index, InputStream htmlStream, IExternalResourceResolver resolver, String uri, boolean useSlideWithIndexAsStart)](#insertFromHtml-int-java.io.InputStream-com.aspose.slides.IExternalResourceResolver-java.lang.String-boolean-) | Maakt dia's van HTML-tekst en voegt ze in op de opgegeven positie in de collectie. |
### get_Item(int index) {#get-Item-int-}
```
public abstract ISlide get_Item(int index)
```

Haalt het element op op de opgegeven index. Alleen-lezen [ISlide](../../com.aspose.slides/islide).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| index | int |  |

**Retour:**
[ISlide](../../com.aspose.slides/islide)
### addClone(ISlide sourceSlide) {#addClone-com.aspose.slides.ISlide-}
```
public abstract ISlide addClone(ISlide sourceSlide)
```

Voegt een kopie van een opgegeven dia toe aan het einde van de collectie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| sourceSlide | [ISlide](../../com.aspose.slides/islide) | Dia om te klonen.

--------------------

Bij het klonen van een dia tussen verschillende presentaties kan ook de master van de dia worden gekloond. Een interne register wordt gebruikt om automatisch gekloonde masters bij te houden om te voorkomen dat meerdere klonen van dezelfde masterdia worden gemaakt. Handmatig klonen van masterdia's wordt noch voorkomen noch geregistreerd. Als u meer controle over het kloonproces nodig heeft, gebruik dan \#addClone(ISlide,ILayoutSlide).addClone(ISlide,ILayoutSlide) of \#addClone(ISlide,IMasterSlide,boolean).addClone(ISlide,IMasterSlide,boolean) om dia's te klonen, [IGlobalLayoutSlideCollection.addClone(ILayoutSlide)](../../com.aspose.slides/igloballayoutslidecollection\#addClone-ILayoutSlide-) of [IGlobalLayoutSlideCollection.addClone(ILayoutSlide,IMasterSlide)](../../com.aspose.slides/igloballayoutslidecollection\#addClone-ILayoutSlide-IMasterSlide-) om lay-outs te klonen en [IMasterSlideCollection.addClone(IMasterSlide)](../../com.aspose.slides/imasterslidecollection\#addClone-IMasterSlide-) om masters te klonen.

**Retour:**
[ISlide](../../com.aspose.slides/islide) - Nieuwe dia.
### addClone(ISlide sourceSlide, ISection section) {#addClone-com.aspose.slides.ISlide-com.aspose.slides.ISection-}
```
public abstract ISlide addClone(ISlide sourceSlide, ISection section)
```

Voegt een kopie van een opgegeven dia toe aan het einde van de opgegeven sectie.

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
>      // Nu bevat de tweede sectie een kopie van de eerste dia.
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| sourceSlide | [ISlide](../../com.aspose.slides/islide) | Dia om te klonen. |
| section | [ISection](../../com.aspose.slides/isection) | Sectie voor een nieuwe dia. |

**Retour:**
[ISlide](../../com.aspose.slides/islide) - Nieuwe dia.
### insertClone(int index, ISlide sourceSlide) {#insertClone-int-com.aspose.slides.ISlide-}
```
public abstract ISlide insertClone(int index, ISlide sourceSlide)
```

Voegt een kopie van een opgegeven dia in op de opgegeven positie in de collectie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| index | int | Index van nieuwe dia. |
| sourceSlide | [ISlide](../../com.aspose.slides/islide) | Dia om te klonen.

--------------------

Bij het klonen van een dia tussen verschillende presentaties kan ook de master van de dia worden gekloond. Een interne register wordt gebruikt om automatisch gekloonde masters bij te houden om te voorkomen dat meerdere klonen van dezelfde masterdia worden gemaakt. Handmatig klonen van masterdia's wordt noch voorkomen noch geregistreerd. Als u meer controle over het kloonproces nodig heeft, gebruik dan \#insertClone(int,ISlide,ILayoutSlide).insertClone(int,ISlide,ILayoutSlide) of \#insertClone(int,ISlide,IMasterSlide,boolean).insertClone(int,ISlide,IMasterSlide,boolean) voor het klonen van dia's en [IMasterSlideCollection.addClone(IMasterSlide)](../../com.aspose.slides/imasterslidecollection\#addClone-IMasterSlide-) voor het klonen van masters.

**Retour:**
[ISlide](../../com.aspose.slides/islide) - Ingevoegde dia.
### addEmptySlide(ILayoutSlide layout) {#addEmptySlide-com.aspose.slides.ILayoutSlide-}
```
public abstract ISlide addEmptySlide(ILayoutSlide layout)
```

Voegt een nieuwe lege dia toe aan het einde van de collectie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| layout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | Lay-out voor een dia. |

**Retour:**
[ISlide](../../com.aspose.slides/islide) - Toegevoegde dia.
### insertEmptySlide(int index, ILayoutSlide layout) {#insertEmptySlide-int-com.aspose.slides.ILayoutSlide-}
```
public abstract ISlide insertEmptySlide(int index, ILayoutSlide layout)
```

Voegt een kopie van een opgegeven dia in op de opgegeven positie in de collectie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| index | int | Index van een nieuwe dia. |
| layout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | Lay-out voor een dia. |

**Retour:**
[ISlide](../../com.aspose.slides/islide) - Ingevoegde dia.
### addClone(ISlide sourceSlide, ILayoutSlide destLayout) {#addClone-com.aspose.slides.ISlide-com.aspose.slides.ILayoutSlide-}
```
public abstract ISlide addClone(ISlide sourceSlide, ILayoutSlide destLayout)
```

Voegt een kopie van een opgegeven dia toe aan het einde van de collectie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| sourceSlide | [ISlide](../../com.aspose.slides/islide) | Dia om te klonen. |
| destLayout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | Lay-outdia voor een nieuwe dia. |

**Retour:**
[ISlide](../../com.aspose.slides/islide) - Nieuwe dia.
### insertClone(int index, ISlide sourceSlide, ILayoutSlide destLayout) {#insertClone-int-com.aspose.slides.ISlide-com.aspose.slides.ILayoutSlide-}
```
public abstract ISlide insertClone(int index, ISlide sourceSlide, ILayoutSlide destLayout)
```

Voegt een kopie van een opgegeven dia in op de opgegeven positie in de collectie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| index | int | Index van nieuwe dia. |
| sourceSlide | [ISlide](../../com.aspose.slides/islide) | Dia om te klonen. |
| destLayout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | Lay-outdia voor een nieuwe dia. |

**Retour:**
[ISlide](../../com.aspose.slides/islide) - Ingevoegde dia.
### addClone(ISlide sourceSlide, IMasterSlide destMaster, boolean allowCloneMissingLayout) {#addClone-com.aspose.slides.ISlide-com.aspose.slides.IMasterSlide-boolean-}
```
public abstract ISlide addClone(ISlide sourceSlide, IMasterSlide destMaster, boolean allowCloneMissingLayout)
```

Voegt een kopie van een opgegeven bron-dia toe aan het einde van de collectie. Een geschikte lay-out wordt automatisch geselecteerd uit de opgegeven master (een geschikte lay-out is de lay-out met hetzelfde Type of dezelfde Naam als de lay-out van de bron-dia). Als er geen geschikte lay-out is, wordt de lay-out van de bron-dia gekloond (als allowCloneMissingLayout true is) of wordt er een PptxEditException gegooid (als allowCloneMissingLayout false is).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| sourceSlide | [ISlide](../../com.aspose.slides/islide) | Dia om te klonen. |
| destMaster | [IMasterSlide](../../com.aspose.slides/imasterslide) | Masterdia voor een nieuwe dia. |
| allowCloneMissingLayout | boolean | Als er geen geschikte lay-out in de opgegeven master is, wordt de lay-out van de bron-dia gekloond (als allowCloneMissingLayout true is) of wordt er een PptxEditException gegooid (als allowCloneMissingLayout false is). |

**Retour:**
[ISlide](../../com.aspose.slides/islide) - Nieuwe dia.
### insertClone(int index, ISlide sourceSlide, IMasterSlide destMaster, boolean allowCloneMissingLayout) {#insertClone-int-com.aspose.slides.ISlide-com.aspose.slides.IMasterSlide-boolean-}
```
public abstract ISlide insertClone(int index, ISlide sourceSlide, IMasterSlide destMaster, boolean allowCloneMissingLayout)
```

Voegt een kopie van een opgegeven bron-dia in op de opgegeven positie in de collectie. Een geschikte lay-out wordt automatisch geselecteerd uit de opgegeven master (een geschikte lay-out is de lay-out met hetzelfde Type of dezelfde Naam als de lay-out van de bron-dia). Als er geen geschikte lay-out is, wordt de lay-out van de bron-dia gekloond (als allowCloneMissingLayout true is) of wordt er een PptxEditException gegooid (als allowCloneMissingLayout false is).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| index | int | Index van nieuwe dia. |
| sourceSlide | [ISlide](../../com.aspose.slides/islide) | Dia om te klonen. |
| destMaster | [IMasterSlide](../../com.aspose.slides/imasterslide) | Masterdia voor een nieuwe dia. |
| allowCloneMissingLayout | boolean | Als er geen geschikte lay-out in de opgegeven master is, wordt de lay-out van de bron-dia gekloond (als allowCloneMissingLayout true is) of wordt er een PptxEditException gegooid (als allowCloneMissingLayout false is). |

**Retour:**
[ISlide](../../com.aspose.slides/islide) - Ingevoegde dia.
### remove(ISlide value) {#remove-com.aspose.slides.ISlide-}
```
public abstract void remove(ISlide value)
```

Verwijdert de eerste voorkoming van een specifiek object uit de collectie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [ISlide](../../com.aspose.slides/islide) | De dia die uit de collectie moet worden verwijderd. |

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

Verwijdert het element op de opgegeven index van de collectie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| index | int | De nulgebaseerde index van het te verwijderen element. |

### toArray() {#toArray--}
```
public abstract ISlide[] toArray()
```

Maakt een array met alle dia's en retourneert deze.

**Retour:**
com.aspose.slides.ISlide[] - Array van [ISlide](../../com.aspose.slides/islide)
### toArray(int startIndex, int count) {#toArray-int-int-}
```
public abstract ISlide[] toArray(int startIndex, int count)
```

Maakt een array met alle dia's uit het opgegeven bereik en retourneert deze.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| startIndex | int | Een index van de eerste dia om toe te voegen. |
| count | int | Een aantal dia's om toe te voegen. |

**Retour:**
com.aspose.slides.ISlide[] - Array van [ISlide](../../com.aspose.slides/islide)
### reorder(int index, ISlide slide) {#reorder-int-com.aspose.slides.ISlide-}
```
public abstract void reorder(int index, ISlide slide)
```

Verplaatst een dia uit de collectie naar de opgegeven positie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| index | int | Doel-index. |
| slide | [ISlide](../../com.aspose.slides/islide) | Dia om te verplaatsen. |

### reorder(int index, ISlide[] slides) {#reorder-int-com.aspose.slides.ISlide...-}
```
public abstract void reorder(int index, ISlide[] slides)
```

Verplaatst dia's uit de collectie naar de opgegeven positie. Dia's worden geplaatst beginnend bij de index in de volgorde waarin ze in de lijst voorkomen.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| index | int | Doel-index. |
| slides | [ISlide\[\]](../../com.aspose.slides/islide) | Dia's om te verplaatsen. |

### indexOf(ISlide slide) {#indexOf-com.aspose.slides.ISlide-}
```
public abstract int indexOf(ISlide slide)
```

Retourneert een index van de opgegeven dia in de collectie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| slide | [ISlide](../../com.aspose.slides/islide) | Dia om te vinden. |

**Retour:**
int - Index van een dia of -1 als de dia niet tot deze collectie behoort.
### addFromPdf(String path) {#addFromPdf-java.lang.String-}
```
public abstract ISlide[] addFromPdf(String path)
```

Maakt dia's van het PDF-document en voegt ze toe aan het einde van de collectie.

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

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| path | java.lang.String | Een pad naar het PDF-document |

**Retour:**
com.aspose.slides.ISlide[] - Toegevoegde dia's
### addFromPdf(String path, PdfImportOptions pdfImportOptions) {#addFromPdf-java.lang.String-com.aspose.slides.PdfImportOptions-}
```
public abstract ISlide[] addFromPdf(String path, PdfImportOptions pdfImportOptions)
```

Maakt dia's van het PDF-document en voegt ze toe aan het einde van de collectie met inachtneming van de PDF-importopties.

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

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| path | java.lang.String | Een pad naar het PDF-document |
| pdfImportOptions | [PdfImportOptions](../../com.aspose.slides/pdfimportoptions) | Opties voor PDF-import |

**Retour:**
com.aspose.slides.ISlide[] - Toegevoegde dia's
### addFromPdf(InputStream pdfStream, PdfImportOptions pdfImportOptions) {#addFromPdf-java.io.InputStream-com.aspose.slides.PdfImportOptions-}
```
public abstract ISlide[] addFromPdf(InputStream pdfStream, PdfImportOptions pdfImportOptions)
```

Maakt dia's van het PDF-document en voegt ze toe aan het einde van de collectie.

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

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| pdfStream | java.io.InputStream | Een stream die wordt gebruikt als bron van het PDF-document |
| pdfImportOptions | [PdfImportOptions](../../com.aspose.slides/pdfimportoptions) | Opties voor PDF-import |

**Retour:**
com.aspose.slides.ISlide[] - Toegevoegde dia's
### addFromPdf(InputStream pdfStream) {#addFromPdf-java.io.InputStream-}
```
public abstract ISlide[] addFromPdf(InputStream pdfStream)
```

Maakt dia's van het PDF-document en voegt ze toe aan het einde van de collectie.

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

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| pdfStream | java.io.InputStream | Een stream die wordt gebruikt als bron van het PDF-document |

**Retour:**
com.aspose.slides.ISlide[] - Toegevoegde dia's
### addFromHtml(String htmlText, IExternalResourceResolver resolver, String uri) {#addFromHtml-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-}
```
public abstract ISlide[] addFromHtml(String htmlText, IExternalResourceResolver resolver, String uri)
```

Maakt dia's van HTML-tekst en voegt ze toe aan het einde van de collectie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| htmlText | java.lang.String | HTML om toe te voegen. |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | Een callback-object dat wordt gebruikt om externe objecten op te halen. Als deze parameter null is, worden alle externe objecten genegeerd. |
| uri | java.lang.String | Een URI van de opgegeven HTML. Gebruikt om relatieve koppelingen op te lossen. |

**Retour:**
com.aspose.slides.ISlide[] - Toegevoegde dia's.
### addFromHtml(String htmlText) {#addFromHtml-java.lang.String-}
```
public abstract ISlide[] addFromHtml(String htmlText)
```

Maakt dia's van HTML-tekst en voegt ze toe aan het einde van de collectie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| htmlText | java.lang.String | HTML om toe te voegen. |

**Retour:**
com.aspose.slides.ISlide[] - Toegevoegde dia's
### addFromHtml(InputStream htmlStream, IExternalResourceResolver resolver, String uri) {#addFromHtml-java.io.InputStream-com.aspose.slides.IExternalResourceResolver-java.lang.String-}
```
public abstract ISlide[] addFromHtml(InputStream htmlStream, IExternalResourceResolver resolver, String uri)
```

Maakt dia's van HTML-tekst en voegt ze toe aan het einde van de collectie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| htmlStream | java.io.InputStream | Een Stream-object dat wordt gebruikt als bron van een HTML-bestand. |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | Een callback-object dat wordt gebruikt om externe objecten op te halen. Als deze parameter null is, worden alle externe objecten genegeerd. |
| uri | java.lang.String | Een URI van de opgegeven HTML. Gebruikt om relatieve koppelingen op te lossen. |

**Retour:**
com.aspose.slides.ISlide[] - Toegevoegde dia's.
### addFromHtml(InputStream htmlStream) {#addFromHtml-java.io.InputStream-}
```
public abstract ISlide[] addFromHtml(InputStream htmlStream)
```

Maakt dia's van HTML-tekst en voegt ze toe aan het einde van de collectie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| htmlStream | java.io.InputStream | Een Stream-object dat wordt gebruikt als bron van een HTML-bestand. |

**Retour:**
com.aspose.slides.ISlide[] - Toegevoegde dia's
### insertFromHtml(int index, String htmlText, IExternalResourceResolver resolver, String uri) {#insertFromHtml-int-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-}
```
public abstract ISlide[] insertFromHtml(int index, String htmlText, IExternalResourceResolver resolver, String uri)
```

Maakt dia's van HTML-tekst en voegt ze in op de collection op de opgegeven positie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| index | int | Positie om in te voegen. |
| htmlText | java.lang.String | HTML om toe te voegen. |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | Een callback-object dat wordt gebruikt om externe objecten op te halen. Als deze parameter null is, worden alle externe objecten genegeerd. |
| uri | java.lang.String | Een URI van de opgegeven HTML. Gebruikt om relatieve koppelingen op te lossen. |

**Retour:**
com.aspose.slides.ISlide[] - Toegevoegde dia's.
### insertFromHtml(int index, String htmlText) {#insertFromHtml-int-java.lang.String-}
```
public abstract ISlide[] insertFromHtml(int index, String htmlText)
```

Maakt dia's van HTML-tekst en voegt ze in op de collection op de opgegeven positie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| index | int | Positie om in te voegen. |
| htmlText | java.lang.String | HTML om toe te voegen. |

**Retour:**
com.aspose.slides.ISlide[] - Toegevoegde dia's
### insertFromHtml(int index, InputStream htmlStream, IExternalResourceResolver resolver, String uri) {#insertFromHtml-int-java.io.InputStream-com.aspose.slides.IExternalResourceResolver-java.lang.String-}
```
public abstract ISlide[] insertFromHtml(int index, InputStream htmlStream, IExternalResourceResolver resolver, String uri)
```

Maakt dia's van HTML-tekst en voegt ze in op de collection op de opgegeven positie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| index | int | Positie om in te voegen. |
| htmlStream | java.io.InputStream | Een Stream-object dat wordt gebruikt als bron van een HTML-bestand. |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | Een callback-object dat wordt gebruikt om externe objecten op te halen. Als deze parameter null is, worden alle externe objecten genegeerd. |
| uri | java.lang.String | Een URI van de opgegeven HTML. Gebruikt om relatieve koppelingen op te lossen. |

**Retour:**
com.aspose.slides.ISlide[] - Toegevoegde dia's.
### insertFromHtml(int index, InputStream htmlStream) {#insertFromHtml-int-java.io.InputStream-}
```
public abstract ISlide[] insertFromHtml(int index, InputStream htmlStream)
```

Maakt dia's van HTML-tekst en voegt ze in op de collection op de opgegeven positie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| index | int | Positie om in te voegen. |
| htmlStream | java.io.InputStream | Een Stream-object dat wordt gebruikt als bron van een HTML-bestand. |

**Retour:**
com.aspose.slides.ISlide[] - Toegevoegde dia's
### insertFromHtml(int index, String htmlText, boolean useSlideWithIndexAsStart) {#insertFromHtml-int-java.lang.String-boolean-}
```
public abstract ISlide[] insertFromHtml(int index, String htmlText, boolean useSlideWithIndexAsStart)
```

Maakt dia's van HTML-tekst en voegt ze in op de collection op de opgegeven positie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| index | int | Positie om in te voegen. |
| htmlText | java.lang.String | HTML om toe te voegen. |
| useSlideWithIndexAsStart | boolean | Deze vlag bepaalt hoe de invoeging begint: vanaf een nieuwe dia of vanaf de dia met de opgegeven index. Als **true**, begint de gegevensinvoer vanaf een lege ruimte op de dia met de opgegeven index. Als **false**, worden de gegevens toegevoegd aan de aangemaakte dia's. |

**Retour:**
com.aspose.slides.ISlide[] - Toegevoegde dia's
### insertFromHtml(int index, String htmlText, IExternalResourceResolver resolver, String uri, boolean useSlideWithIndexAsStart) {#insertFromHtml-int-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-boolean-}
```
public abstract ISlide[] insertFromHtml(int index, String htmlText, IExternalResourceResolver resolver, String uri, boolean useSlideWithIndexAsStart)
```

Maakt dia's van HTML-tekst en voegt ze in op de collection op de opgegeven positie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| index | int | Positie om in te voegen. |
| htmlText | java.lang.String | HTML om toe te voegen. |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | Een callback-object dat wordt gebruikt om externe objecten op te halen. Als deze parameter null is, worden alle externe objecten genegeerd. |
| uri | java.lang.String | Een URI van de opgegeven HTML. Gebruikt om relatieve koppelingen op te lossen. |
| useSlideWithIndexAsStart | boolean | Deze vlag bepaalt hoe de invoeging begint: vanaf een nieuwe dia of vanaf de dia met de opgegeven index. Als **true**, begint de gegevensinvoer vanaf een lege ruimte op de dia met de opgegeven index. Als **false**, worden de gegevens toegevoegd aan de aangemaakte dia's. |

**Retour:**
com.aspose.slides.ISlide[] - Toegevoegde dia's.
### insertFromHtml(int index, InputStream htmlStream, boolean useSlideWithIndexAsStart) {#insertFromHtml-int-java.io.InputStream-boolean-}
```
public abstract ISlide[] insertFromHtml(int index, InputStream htmlStream, boolean useSlideWithIndexAsStart)
```

Maakt dia's van HTML-tekst en voegt ze in op de collection op de opgegeven positie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| index | int | Positie om in te voegen. |
| htmlStream | java.io.InputStream | Een Stream-object dat wordt gebruikt als bron van een HTML-bestand. |
| useSlideWithIndexAsStart | boolean | Deze vlag bepaalt hoe de invoeging begint: vanaf een nieuwe dia of vanaf de dia met de opgegeven index. Als **true**, begint de gegevensinvoer vanaf een lege ruimte op de dia met de opgegeven index. Als **false**, worden de gegevens toegevoegd aan de aangemaakte dia's. |

**Retour:**
com.aspose.slides.ISlide[] - Toegevoegde dia's
### insertFromHtml(int index, InputStream htmlStream, IExternalResourceResolver resolver, String uri, boolean useSlideWithIndexAsStart) {#insertFromHtml-int-java.io.InputStream-com.aspose.slides.IExternalResourceResolver-java.lang.String-boolean-}
```
public abstract ISlide[] insertFromHtml(int index, InputStream htmlStream, IExternalResourceResolver resolver, String uri, boolean useSlideWithIndexAsStart)
```

Maakt dia's van HTML-tekst en voegt ze in op de collection op de opgegeven positie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| index | int | Positie om in te voegen. |
| htmlStream | java.io.InputStream | Een Stream-object dat wordt gebruikt als bron van een HTML-bestand. |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | Een callback-object dat wordt gebruikt om externe objecten op te halen. Als deze parameter null is, worden alle externe objecten genegeerd. |
| uri | java.lang.String | Een URI van de opgegeven HTML. Gebruikt om relatieve koppelingen op te lossen. |
| useSlideWithIndexAsStart | boolean | Deze vlag bepaalt hoe de invoeging begint: vanaf een nieuwe dia of vanaf de dia met de opgegeven index. Als **true**, begint de gegevensinvoer vanaf een lege ruimte op de dia met de opgegeven index. Als **false**, worden de gegevens toegevoegd aan de aangemaakte dia's. |

**Retour:**
com.aspose.slides.ISlide[] - Toegevoegde dia's.