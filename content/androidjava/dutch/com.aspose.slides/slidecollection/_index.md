---
title: SlideCollection
second_title: Aspose.Slides voor Android via Java API-referentie
description: Stelt een collectie van dia's voor.
type: docs
url: /nl/com.aspose.slides/slidecollection/
---
**Inheritance:**
java.lang.Object, com.aspose.slides.DomObject

**All Implemented Interfaces:**
[com.aspose.slides.ISlideCollection](../../com.aspose.slides/islidecollection)
```
public final class SlideCollection extends DomObject<Presentation> implements ISlideCollection
```

Stelt een verzameling van dia's voor.

## Methoden

| Methode | Beschrijving |
| --- | --- |
| [size()](#size--) | Haalt het aantal elementen op dat daadwerkelijk in de collectie aanwezig is. |
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
| [remove(ISlide value)](#remove-com.aspose.slides.ISlide-) | Verwijdert het eerste voorkomen van een specifiek object uit de collectie. |
| [removeAt(int index)](#removeAt-int-) | Verwijdert het element op de opgegeven index van de collectie. |
| [iterator()](#iterator--) | Retourneert een enumerator die door de collectie itereert. |
| [iteratorJava()](#iteratorJava--) | Retourneert een java-iterator voor de gehele collectie. |
| [toArray()](#toArray--) | Maakt een array met alle dia's en retourneert deze. |
| [toArray(int startIndex, int count)](#toArray-int-int-) | Maakt een array met alle dia's uit het opgegeven bereik en retourneert deze. |
| [reorder(int index, ISlide slide)](#reorder-int-com.aspose.slides.ISlide-) | Verplaatst een dia van de collectie naar de opgegeven positie. |
| [reorder(int index, ISlide[] slides)](#reorder-int-com.aspose.slides.ISlide...-) | Verplaatst dia's van de collectie naar de opgegeven positie. Dia's worden geplaatst vanaf de index in de volgorde waarin ze in de lijst voorkomen. |
| [indexOf(ISlide slide)](#indexOf-com.aspose.slides.ISlide-) | Retourneert een index van de opgegeven dia in de collectie. |
| [addFromPdf(String path)](#addFromPdf-java.lang.String-) | Maakt dia's aan vanuit het PDF-document en voegt ze toe aan het einde van de collectie. |
| [addFromPdf(String path, PdfImportOptions pdfImportOptions)](#addFromPdf-java.lang.String-com.aspose.slides.PdfImportOptions-) | Maakt dia’s aan vanuit het PDF-document en voegt ze toe aan het einde van de collectie rekening houdend met de PDF-importopties. |
| [addFromPdf(InputStream pdfStream)](#addFromPdf-java.io.InputStream-) | Maakt dia’s aan vanuit het PDF-document en voegt ze toe aan het einde van de collectie. |
| [addFromPdf(InputStream pdfStream, PdfImportOptions pdfImportOptions)](#addFromPdf-java.io.InputStream-com.aspose.slides.PdfImportOptions-) | Maakt dia’s aan vanuit het PDF-document en voegt ze toe aan het einde van de collectie. |
| [addFromHtml(String htmlText, IExternalResourceResolver resolver, String uri)](#addFromHtml-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-) | Maakt dia’s aan vanuit HTML-tekst en voegt ze toe aan het einde van de collectie. |
| [addFromHtml(String htmlText)](#addFromHtml-java.lang.String-) | Maakt dia’s aan vanuit HTML-tekst en voegt ze toe aan het einde van de collectie. |
| [addFromHtml(InputStream htmlStream, IExternalResourceResolver resolver, String uri)](#addFromHtml-java.io.InputStream-com.aspose.slides.IExternalResourceResolver-java.lang.String-) | Maakt dia’s aan vanuit HTML-tekst en voegt ze toe aan het einde van de collectie. |
| [addFromHtml(InputStream htmlStream)](#addFromHtml-java.io.InputStream-) | Maakt dia’s aan vanuit HTML-tekst en voegt ze toe aan het einde van de collectie. |
| [insertFromHtml(int index, String htmlText, IExternalResourceResolver resolver, String uri)](#insertFromHtml-int-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-) | Maakt dia’s aan vanuit HTML-tekst en voegt ze in op de opgegeven positie in de collectie. |
| [insertFromHtml(int index, String htmlText, IExternalResourceResolver resolver, String uri, boolean useSlideWithIndexAsStart)](#insertFromHtml-int-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-boolean-) | Maakt dia’s aan vanuit HTML-tekst en voegt ze in op de opgegeven positie in de collectie. |
| [insertFromHtml(int index, String htmlText)](#insertFromHtml-int-java.lang.String-) | Maakt dia’s aan vanuit HTML-tekst en voegt ze in op de opgegeven positie in de collectie. |
| [insertFromHtml(int index, String htmlText, boolean useSlideWithIndexAsStart)](#insertFromHtml-int-java.lang.String-boolean-) | Maakt dia’s aan vanuit HTML-tekst en voegt ze in op de opgegeven positie in de collectie. |
| [insertFromHtml(int index, InputStream htmlStream, IExternalResourceResolver resolver, String uri)](#insertFromHtml-int-java.io.InputStream-com.aspose.slides.IExternalResourceResolver-java.lang.String-) | Maakt dia’s aan vanuit HTML-tekst en voegt ze in op de opgegeven positie in de collectie. |
| [insertFromHtml(int index, InputStream htmlStream, IExternalResourceResolver resolver, String uri, boolean useSlideWithIndexAsStart)](#insertFromHtml-int-java.io.InputStream-com.aspose.slides.IExternalResourceResolver-java.lang.String-boolean-) | Maakt dia’s aan vanuit HTML-tekst en voegt ze in op de opgegeven positie in de collectie. |
| [insertFromHtml(int index, InputStream htmlStream)](#insertFromHtml-int-java.io.InputStream-) | Maakt dia’s aan vanuit HTML-tekst en voegt ze in op de opgegeven positie in de collectie. |
| [insertFromHtml(int index, InputStream htmlStream, boolean useSlideWithIndexAsStart)](#insertFromHtml-int-java.io.InputStream-boolean-) | Maakt dia’s aan vanuit HTML-tekst en voegt ze in op de opgegeven positie in de collectie. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Kopieert alle elementen van de collectie naar de opgegeven array. |
| [isSynchronized()](#isSynchronized--) | Retourneert een waarde die aangeeft of de toegang tot de collectie gesynchroniseerd (thread-safe) is. |
| [getSyncRoot()](#getSyncRoot--) | Retourneert een synchronisatiewortel. |

### size() {#size--}
```
public final int size()
```

Haalt het aantal elementen op dat daadwerkelijk in de collectie aanwezig is. Alleen-lezen int.

**Retourneert:**
int

### get_Item(int index) {#get-Item-int-}
```
public final ISlide get_Item(int index)
```

Haalt het element op op de opgegeven index. Alleen-lezen [Slide](../../com.aspose.slides/slide).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int |  |

**Retourneert:**
[ISlide](../../com.aspose.slides/islide)

### addClone(ISlide sourceSlide) {#addClone-com.aspose.slides.ISlide-}
```
public final ISlide addClone(ISlide sourceSlide)
```

Voegt een kopie van een opgegeven dia toe aan het einde van de collectie.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| sourceSlide | [ISlide](../../com.aspose.slides/islide) | Dia om te klonen.

--------------------

Wanneer een dia tussen verschillende presentaties wordt gekloond, kan de master van de dia ook gekloond worden. Een intern register wordt gebruikt om automatisch gekloonde masters bij te houden en zo het maken van meerdere klonen van dezelfde masterdia te voorkomen. Handmatig klonen van masterdia’s wordt niet voorkomen of geregistreerd. Als u meer controle over het kloonproces nodig heeft, gebruik dan \#addClone(ISlide,ILayoutSlide).addClone(ISlide,ILayoutSlide) of \#addClone(ISlide,IMasterSlide,boolean).addClone(ISlide,IMasterSlide,boolean) voor het klonen van dia’s, [IGlobalLayoutSlideCollection.addClone(ILayoutSlide)](../../com.aspose.slides/igloballayoutslidecollection\#addClone-ILayoutSlide-) of [IGlobalLayoutSlideCollection.addClone(ILayoutSlide,IMasterSlide)](../../com.aspose.slides/igloballayoutslidecollection\#addClone-ILayoutSlide-IMasterSlide-) voor het klonen van lay-outs en [IMasterSlideCollection.addClone(IMasterSlide)](../../com.aspose.slides/imasterslidecollection\#addClone-IMasterSlide-) voor het klonen van masters. |

**Retourneert:**
[ISlide](../../com.aspose.slides/islide) - Nieuwe dia.

### addClone(ISlide sourceSlide, ISection section) {#addClone-com.aspose.slides.ISlide-com.aspose.slides.ISection-}
```
public final ISlide addClone(ISlide sourceSlide, ISection section)
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
| Parameter | Type | Description |
| --- | --- | --- |
| sourceSlide | [ISlide](../../com.aspose.slides/islide) | Dia om te klonen. |
| section | [ISection](../../com.aspose.slides/isection) | Sectie voor een nieuwe dia. |

**Retourneert:**
[ISlide](../../com.aspose.slides/islide) - Nieuwe dia.

### insertClone(int index, ISlide sourceSlide) {#insertClone-int-com.aspose.slides.ISlide-}
```
public final ISlide insertClone(int index, ISlide sourceSlide)
```

Voegt een kopie van een opgegeven dia in op de opgegeven positie in de collectie.

--------------------

> ```
> The following example shows how to clone at another position within Presentation.
>  
>  // Instantieer de Presentation-klasse die een presentatiebestand vertegenwoordigt
>  Presentation pres = new Presentation("CloneWithInSamePresentation.pptx");
>  try {
>      // Kloon de gewenste dia naar het einde van de dia-collectie in dezelfde presentatie
>      ISlideCollection slds = pres.getSlides();
>      // Kloon de gewenste dia naar de opgegeven index in dezelfde presentatie
>      slds.insertClone(2, pres.getSlides().get_Item(1));
>      // Schrijf de aangepaste presentatie naar schijf
>      pres.save("Aspose_CloneWithInSamePresentation_out.pptx", SaveFormat.Pptx);
>  }
>  finally
>  {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to clone at another position within Presentation.
>  
>  // Instantieer de Presentation-klasse om het bronpresentatiebestand te laden
>  Presentation srcPres = new Presentation("CloneAtEndOfAnother.pptx");
>  try {
>      // Instantieer de Presentation-klasse voor de doel-PPTX (waarin de dia moet worden gekloond)
>      Presentation destPres = new Presentation();
>      try {
>          ISlideCollection slds = destPres.getSlides();
>          slds.insertClone(2, srcPres.getSlides().get_Item(0));
>          // Schrijf de bestemmingspresentatie naar schijf
>          destPres.save("Aspose2_out.pptx", SaveFormat.Pptx);
>      } finally {
>          if (destPres != null) destPres.dispose();
>      }
>  } finally {
>      if (srcPres != null) srcPres.dispose();
>  }
> ```


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Index van de nieuwe dia. |
| sourceSlide | [ISlide](../../com.aspose.slides/islide) | Dia om te klonen.

--------------------

Wanneer een dia tussen verschillende presentaties wordt gekloond, kan de master van de dia ook gekloond worden. Een intern register wordt gebruikt om automatisch gekloonde masters bij te houden en zo het maken van meerdere klonen van dezelfde masterdia te voorkomen. Handmatig klonen van masterdia’s wordt niet voorkomen of geregistreerd. Als u meer controle over het kloonproces nodig heeft, gebruik dan \#insertClone(int,ISlide,ILayoutSlide).insertClone(int,ISlide,ILayoutSlide) of \#insertClone(int,ISlide,IMasterSlide,boolean).insertClone(int,ISlide,IMasterSlide,boolean) voor het klonen van dia’s en [IMasterSlideCollection.addClone(IMasterSlide)](../../com.aspose.slides/imasterslidecollection\#addClone-IMasterSlide-) voor het klonen van masters. |

**Retourneert:**
[ISlide](../../com.aspose.slides/islide) - Ingevoegde dia.

### addEmptySlide(ILayoutSlide layout) {#addEmptySlide-com.aspose.slides.ILayoutSlide-}
```
public final ISlide addEmptySlide(ILayoutSlide layout)
```

Voegt een nieuwe lege dia toe aan het einde van de collectie.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| layout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | Layout voor een dia. |

**Retourneert:**
[ISlide](../../com.aspose.slides/islide) - Toegevoegde dia.

### insertEmptySlide(int index, ILayoutSlide layout) {#insertEmptySlide-int-com.aspose.slides.ILayoutSlide-}
```
public final ISlide insertEmptySlide(int index, ILayoutSlide layout)
```

Voegt een kopie van een opgegeven dia in op de opgegeven positie in de collectie.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Index van een nieuwe dia. |
| layout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | Layout voor een dia. |

**Retourneert:**
[ISlide](../../com.aspose.slides/islide) - Ingevoegde dia.

### addClone(ISlide sourceSlide, ILayoutSlide destLayout) {#addClone-com.aspose.slides.ISlide-com.aspose.slides.ILayoutSlide-}
```
public final ISlide addClone(ISlide sourceSlide, ILayoutSlide destLayout)
```

Voegt een kopie van een opgegeven dia toe aan het einde van de collectie.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| sourceSlide | [ISlide](../../com.aspose.slides/islide) | Dia om te klonen. |
| destLayout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | Layout-dia voor een nieuwe dia. |

**Retourneert:**
[ISlide](../../com.aspose.slides/islide) - Nieuwe dia.

### insertClone(int index, ISlide sourceSlide, ILayoutSlide destLayout) {#insertClone-int-com.aspose.slides.ISlide-com.aspose.slides.ILayoutSlide-}
```
public final ISlide insertClone(int index, ISlide sourceSlide, ILayoutSlide destLayout)
```

Voegt een kopie van een opgegeven dia in op de opgegeven positie in de collectie.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Index van de nieuwe dia. |
| sourceSlide | [ISlide](../../com.aspose.slides/islide) | Dia om te klonen. |
| destLayout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | Layout-dia voor een nieuwe dia. |

**Retourneert:**
[ISlide](../../com.aspose.slides/islide) - Ingevoegde dia.

### addClone(ISlide sourceSlide, IMasterSlide destMaster, boolean allowCloneMissingLayout) {#addClone-com.aspose.slides.ISlide-com.aspose.slides.IMasterSlide-boolean-}
```
public final ISlide addClone(ISlide sourceSlide, IMasterSlide destMaster, boolean allowCloneMissingLayout)
```

Voegt een kopie van een opgegeven bron-dia toe aan het einde van de collectie. Een geschikte layout wordt automatisch geselecteerd uit de opgegeven master (een geschikte layout is de layout met hetzelfde Type of dezelfde Naam als de layout van de bron-dia). Als er geen geschikte layout bestaat, wordt de layout van de bron-dia gekloond (als allowCloneMissingLayout true is) of wordt een PptxEditException gegooid (als allowCloneMissingLayout false is).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| sourceSlide | [ISlide](../../com.aspose.slides/islide) | Dia om te klonen. |
| destMaster | [IMasterSlide](../../com.aspose.slides/imasterslide) | Master-dia voor een nieuwe dia. |
| allowCloneMissingLayout | boolean | Als er geen geschikte layout in de opgegeven master bestaat, wordt de layout van de bron-dia gekloond (als allowCloneMissingLayout true is) of wordt een PptxEditException gegooid (als allowCloneMissingLayout false is). |

**Retourneert:**
[ISlide](../../com.aspose.slides/islide) - Nieuwe dia.

### insertClone(int index, ISlide sourceSlide, IMasterSlide destMaster, boolean allowCloneMissingLayout) {#insertClone-int-com.aspose.slides.ISlide-com.aspose.slides.IMasterSlide-boolean-}
```
public final ISlide insertClone(int index, ISlide sourceSlide, IMasterSlide destMaster, boolean allowCloneMissingLayout)
```

Voegt een kopie van een opgegeven bron-dia in op de opgegeven positie in de collectie. Een geschikte layout wordt automatisch geselecteerd uit de opgegeven master (een geschikte layout is de layout met hetzelfde Type of dezelfde Naam als de layout van de bron-dia). Als er geen geschikte layout bestaat, wordt de layout van de bron-dia gekloond (als allowCloneMissingLayout true is) of wordt een PptxEditException gegooid (als allowCloneMissingLayout false is).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Index van de nieuwe dia. |
| sourceSlide | [ISlide](../../com.aspose.slides/islide) | Dia om te klonen. |
| destMaster | [IMasterSlide](../../com.aspose.slides/imasterslide) | Master-dia voor een nieuwe dia. |
| allowCloneMissingLayout | boolean | Als er geen geschikte layout in de opgegeven master bestaat, wordt de layout van de bron-dia gekloond (als allowCloneMissingLayout true is) of wordt een PptxEditException gegooid (als allowCloneMissingLayout false is). |

**Retourneert:**
[ISlide](../../com.aspose.slides/islide) - Ingevoegde dia.

### remove(ISlide value) {#remove-com.aspose.slides.ISlide-}
```
public final void remove(ISlide value)
```

Verwijdert het eerste voorkomen van een specifiek object uit de collectie.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [ISlide](../../com.aspose.slides/islide) | De dia die uit de collectie moet worden verwijderd.

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

Verwijdert het element op de opgegeven index van de collectie.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | De nul-gebaseerde index van het te verwijderen element.

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<ISlide> iterator()
```

Retourneert een enumerator die door de collectie itereert.

**Retourneert:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ISlide> - Een IGenericEnumerator die kan worden gebruikt om door de collectie te itereren.

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<ISlide> iteratorJava()
```

Retourneert een java-iterator voor de gehele collectie.

**Retourneert:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ISlide> - Een java.util.Iterator voor de gehele collectie.

### toArray() {#toArray--}
```
public final ISlide[] toArray()
```

Maakt een array met alle dia's en retourneert deze.

**Retourneert:**
com.aspose.slides.ISlide[] - Array van [Slide](../../com.aspose.slides/slide)

### toArray(int startIndex, int count) {#toArray-int-int-}
```
public final ISlide[] toArray(int startIndex, int count)
```

Maakt een array met alle dia's uit het opgegeven bereik en retourneert deze.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| startIndex | int | Index van de eerste toe te voegen dia. |
| count | int | Aantal toe te voegen dia’s.

**Retourneert:**
com.aspose.slides.ISlide[] - Array van [Slide](../../com.aspose.slides/slide)

### reorder(int index, ISlide slide) {#reorder-int-com.aspose.slides.ISlide-}
```
public final void reorder(int index, ISlide slide)
```

Verplaatst een dia van de collectie naar de opgegeven positie.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Doel-index. |
| slide | [ISlide](../../com.aspose.slides/islide) | Dia om te verplaatsen.

### reorder(int index, ISlide[] slides) {#reorder-int-com.aspose.slides.ISlide...-}
```
public final void reorder(int index, ISlide[] slides)
```

Verplaatst dia's van de collectie naar de opgegeven positie. Dia's worden geplaatst vanaf de index in de volgorde waarin ze in de lijst voorkomen.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Doel-index. |
| slides | [ISlide\[\]](../../com.aspose.slides/islide) | Dia's om te verplaatsen.

### indexOf(ISlide slide) {#indexOf-com.aspose.slides.ISlide-}
```
public final int indexOf(ISlide slide)
```

Retourneert een index van de opgegeven dia in de collectie.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| slide | [ISlide](../../com.aspose.slides/islide) | Dia om te vinden.

**Retourneert:**
int - Index van een dia of -1 als de dia niet uit deze collectie komt.

### addFromPdf(String path) {#addFromPdf-java.lang.String-}
```
public final ISlide[] addFromPdf(String path)
```

Maakt dia’s aan vanuit het PDF-document en voegt ze toe aan het einde van de collectie.

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
| Parameter | Type | Description |
| --- | --- | --- |
| path | java.lang.String | Een pad naar het PDF-document |

**Retourneert:**
com.aspose.slides.ISlide[] - Toegevoegde dia’s

### addFromPdf(String path, PdfImportOptions pdfImportOptions) {#addFromPdf-java.lang.String-com.aspose.slides.PdfImportOptions-}
```
public final ISlide[] addFromPdf(String path, PdfImportOptions pdfImportOptions)
```

Maakt dia’s aan vanuit het PDF-document en voegt ze toe aan het einde van de collectie rekening houdend met de PDF-importopties.

--------------------

> ```
> Voorbeeld:
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
| Parameter | Type | Description |
| --- | --- | --- |
| path | java.lang.String | Een pad naar het PDF-document |
| pdfImportOptions | [PdfImportOptions](../../com.aspose.slides/pdfimportoptions) | Opties voor PDF-import |

**Retourneert:**
com.aspose.slides.ISlide[] - Toegevoegde dia’s

### addFromPdf(InputStream pdfStream) {#addFromPdf-java.io.InputStream-}
```
public final ISlide[] addFromPdf(InputStream pdfStream)
```

Maakt dia’s aan vanuit het PDF-document en voegt ze toe aan het einde van de collectie.

--------------------

> ```
> Voorbeeld:
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
| Parameter | Type | Description |
| --- | --- | --- |
| pdfStream | java.io.InputStream | Een stream die wordt gebruikt als bron van het PDF-document |

**Retourneert:**
com.aspose.slides.ISlide[] - Toegevoegde dia’s

### addFromPdf(InputStream pdfStream, PdfImportOptions pdfImportOptions) {#addFromPdf-java.io.InputStream-com.aspose.slides.PdfImportOptions-}
```
public final ISlide[] addFromPdf(InputStream pdfStream, PdfImportOptions pdfImportOptions)
```

Maakt dia’s aan vanuit het PDF-document en voegt ze toe aan het einde van de collectie.

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
| Parameter | Type | Description |
| --- | --- | --- |
| pdfStream | java.io.InputStream | Een stream die wordt gebruikt als bron van het PDF-document |
| pdfImportOptions | [PdfImportOptions](../../com.aspose.slides/pdfimportoptions) | Opties voor PDF-import |

**Retourneert:**
com.aspose.slides.ISlide[] - Toegevoegde dia’s

### addFromHtml(String htmlText, IExternalResourceResolver resolver, String uri) {#addFromHtml-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-}
```
public final ISlide[] addFromHtml(String htmlText, IExternalResourceResolver resolver, String uri)
```

Maakt dia’s aan vanuit HTML-tekst en voegt ze toe aan het einde van de collectie.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| htmlText | java.lang.String | HTML om toe te voegen. |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | Een callback-object dat externe objecten ophaalt. Als deze parameter null is, worden alle externe objecten genegeerd. |
| uri | java.lang.String | Een URI van de opgegeven HTML. Wordt gebruikt om relatieve links op te lossen. |

**Retourneert:**
com.aspose.slides.ISlide[] - Toegevoegde dia’s.

### addFromHtml(String htmlText) {#addFromHtml-java.lang.String-}
```
public final ISlide[] addFromHtml(String htmlText)
```

Maakt dia’s aan vanuit HTML-tekst en voegt ze toe aan het einde van de collectie.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| htmlText | java.lang.String | HTML om toe te voegen.

**Retourneert:**
com.aspose.slides.ISlide[] - Toegevoegde dia’s

### addFromHtml(InputStream htmlStream, IExternalResourceResolver resolver, String uri) {#addFromHtml-java.io.InputStream-com.aspose.slides.IExternalResourceResolver-java.lang.String-}
```
public final ISlide[] addFromHtml(InputStream htmlStream, IExternalResourceResolver resolver, String uri)
```

Maakt dia’s aan vanuit HTML-tekst en voegt ze toe aan het einde van de collectie.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| htmlStream | java.io.InputStream | Een Stream-object dat wordt gebruikt als bron van een HTML-bestand. |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | Een callback-object dat externe objecten ophaalt. Als deze parameter null is, worden alle externe objecten genegeerd. |
| uri | java.lang.String | Een URI van de opgegeven HTML. Wordt gebruikt om relatieve links op te lossen. |

**Retourneert:**
com.aspose.slides.ISlide[] - Toegevoegde dia’s.

### addFromHtml(InputStream htmlStream) {#addFromHtml-java.io.InputStream-}
```
public final ISlide[] addFromHtml(InputStream htmlStream)
```

Maakt dia’s aan vanuit HTML-tekst en voegt ze toe aan het einde van de collectie.

--------------------

> ```
> // Maak een instantie van de Presentation-klasse.
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream fos = null;
>      try {
>          fos = new FileInputStream("file.html");
>          // Roep de AddFromHtml-methode aan en geef het HTML-bestand door.
>          pres.getSlides().addFromHtml(fos);
>          // Gebruik de Save-methode om het bestand op te slaan als een PowerPoint-document.
>          pres.save("MyPresentation.pptx", SaveFormat.Pptx);
>      } finally {
>          if (fos != null) fos.close();
>      }
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| htmlStream | java.io.InputStream | Een Stream-object dat wordt gebruikt als bron van een HTML-bestand.

**Retourneert:**
com.aspose.slides.ISlide[] - Toegevoegde dia’s

### insertFromHtml(int index, String htmlText, IExternalResourceResolver resolver, String uri) {#insertFromHtml-int-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-}
```
public final ISlide[] insertFromHtml(int index, String htmlText, IExternalResourceResolver resolver, String uri)
```

Maakt dia’s aan vanuit HTML-tekst en voegt ze in op de opgegeven positie in de collectie.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Positie om in te voegen. |
| htmlText | java.lang.String | HTML om toe te voegen. |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | Een callback-object dat externe objecten ophaalt. Als deze parameter null is, worden alle externe objecten genegeerd. |
| uri | java.lang.String | Een URI van de opgegeven HTML. Wordt gebruikt om relatieve links op te lossen.

**Retourneert:**
com.aspose.slides.ISlide[] - Toegevoegde dia’s.

### insertFromHtml(int index, String htmlText, IExternalResourceResolver resolver, String uri, boolean useSlideWithIndexAsStart) {#insertFromHtml-int-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-boolean-}
```
public final ISlide[] insertFromHtml(int index, String htmlText, IExternalResourceResolver resolver, String uri, boolean useSlideWithIndexAsStart)
```

Maakt dia’s aan vanuit HTML-tekst en voegt ze in op de opgegeven positie in de collectie.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Positie om in te voegen. |
| htmlText | java.lang.String | HTML om toe te voegen. |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | Een callback-object dat externe objecten ophaalt. Als deze parameter null is, worden alle externe objecten genegeerd. |
| uri | java.lang.String | Een URI van de opgegeven HTML. Wordt gebruikt om relatieve links op te lossen. |
| useSlideWithIndexAsStart | boolean | Deze vlag bepaalt hoe de invoeging begint: vanaf een nieuwe dia of vanaf de dia met de opgegeven index. Als **true**, begint de invoeging vanaf een lege ruimte op de dia met de opgegeven index. Als **false**, worden de gegevens toegevoegd aan de aangemaakte dia’s.

**Retourneert:**
com.aspose.slides.ISlide[] - Toegevoegde dia’s.

### insertFromHtml(int index, String htmlText) {#insertFromHtml-int-java.lang.String-}
```
public final ISlide[] insertFromHtml(int index, String htmlText)
```

Maakt dia’s aan vanuit HTML-tekst en voegt ze in op de opgegeven positie in de collectie.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Positie om in te voegen. |
| htmlText | java.lang.String | HTML om toe te voegen.

**Retourneert:**
com.aspose.slides.ISlide[] - Toegevoegde dia’s

### insertFromHtml(int index, String htmlText, boolean useSlideWithIndexAsStart) {#insertFromHtml-int-java.lang.String-boolean-}
```
public int size ()
```

Maakt dia’s aan vanuit HTML-tekst en voegt ze in op de opgegeven positie in de collectie.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Positie om in te voegen. |
| htmlText | java.lang.String | HTML om toe te voegen. |
| useSlideWithIndexAsStart | boolean | Deze vlag bepaalt hoe de invoeging begint: vanaf een nieuwe dia of vanaf de dia met de opgegeven index. Als **true**, begint de invoeging vanaf een lege ruimte op de dia met de opgegeven index. Als **false**, worden de gegevens toegevoegd aan de aangemaakte dia’s.

**Retourneert:**
com.aspose.slides.ISlide[] - Toegevoegde dia’s

### insertFromHtml(int index, InputStream htmlStream, IExternalResourceResolver resolver, String uri) {#insertFromHtml-int-java.io.InputStream-com.aspose.slides.IExternalResourceResolver-java.lang.String-}
```
public final ISlide[] insertFromHtml(int index, InputStream htmlStream, IExternalResourceResolver resolver, String uri)
```

Maakt dia’s aan vanuit HTML-tekst en voegt ze in op de opgegeven positie in de collectie.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Positie om in te voegen. |
| htmlStream | java.io.InputStream | Een Stream-object dat wordt gebruikt als bron van een HTML-bestand. |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | Een callback-object dat externe objecten ophaalt. Als deze parameter null is, worden alle externe objecten genegeerd. |
| uri | java.lang.String | Een URI van de opgegeven HTML. Wordt gebruikt om relatieve links op te lossen.

**Retourneert:**
com.aspose.slides.ISlide[] - Toegevoegde dia’s.

### insertFromHtml(int index, InputStream htmlStream, IExternalResourceResolver resolver, String uri, boolean useSlideWithIndexAsStart) {#insertFromHtml-int-java.io.InputStream-com.aspose.slides.IExternalResourceResolver-java.lang.String-boolean-}
```
public final ISlide[] insertFromHtml(int index, InputStream htmlStream, IExternalResourceResolver resolver, String uri, boolean useSlideWithIndexAsStart)
```

Maakt dia’s aan vanuit HTML-tekst en voegt ze in op de opgegeven positie in de collectie.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Positie om in te voegen. |
| htmlStream | java.io.InputStream | Een Stream-object dat wordt gebruikt als bron van een HTML-bestand. |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | Een callback-object dat externe objecten ophaalt. Als deze parameter null is, worden alle externe objecten genegeerd. |
| uri | java.lang.String | Een URI van de opgegeven HTML. Wordt gebruikt om relatieve links op te lossen. |
| useSlideWithIndexAsStart | boolean | Deze vlag bepaalt hoe de invoeging begint: vanaf een nieuwe dia of vanaf de dia met de opgegeven index. Als **true**, begint de invoeging vanaf een lege ruimte op de dia met de opgegeven index. Als **false**, worden de gegevens toegevoegd aan de aangemaakte dia’s.

**Retourneert:**
com.aspose.slides.ISlide[] - Toegevoegde dia’s.

### insertFromHtml(int index, InputStream htmlStream) {#insertFromHtml-int-java.io.InputStream-}
```
public final ISlide[] insertFromHtml(int index, InputStream htmlStream)
```

Maakt dia’s aan vanuit HTML-tekst en voegt ze in op de opgegeven positie in de collectie.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Positie om in te voegen. |
| htmlStream | java.io.InputStream | Een Stream-object dat wordt gebruikt als bron van een HTML-bestand.

**Retourneert:**
com.aspose.slides.ISlide[] - Toegevoegde dia’s

### insertFromHtml(int index, InputStream htmlStream, boolean useSlideWithIndexAsStart) {#insertFromHtml-int-java.io.InputStream-boolean-}
```
public final ISlide[] insertFromHtml(int index, InputStream htmlStream, boolean useSlideWithIndexAsStart)
```

Maakt dia’s aan vanuit HTML-tekst en voegt ze in op de opgegeven positie in de collectie.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Positie om in te voegen. |
| htmlStream | java.io.InputStream | Een Stream-object dat wordt gebruikt als bron van een HTML-bestand. |
| useSlideWithIndexAsStart | boolean | Deze vlag bepaalt hoe de invoeging begint: vanaf een nieuwe dia of vanaf de dia met de opgegeven index. Als **true**, begint de invoeging vanaf een lege ruimte op de dia met de opgegeven index. Als **false**, worden de gegevens toegevoegd aan de aangemaakte dia’s.

**Retourneert:**
com.aspose.slides.ISlide[] - Toegevoegde dia’s

### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

Kopieert alle elementen van de collectie naar de opgegeven array.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Doel-array. |
| index | int | Start-index in de doel-array.

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

Retourneert een waarde die aangeeft of de toegang tot de collectie gesynchroniseerd (thread-safe) is. Alleen-lezen boolean.

**Retourneert:**
boolean

### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

Retourneert een synchronisatiewortel. Alleen-lezen Object.

**Retourneert:**
java.lang.Object