---
title: Presentation
second_title: Aspose.Slides voor Java API-referentie
description: Stelt een Microsoft PowerPoint-presentatie voor.
type: docs
url: /nl/com.aspose.slides/presentation/
---
**Erfenis:**
java.lang.Object

**Alle geïmplementeerde interfaces:**
[com.aspose.slides.IPresentation](../../com.aspose.slides/ipresentation), com.aspose.slides.IDOMObject
```
public final class Presentation implements IPresentation, IDOMObject
```

Stelt een Microsoft PowerPoint-presentatie voor.

--------------------

> ```
> The following example shows how to create PowerPoint Presentation.
>   
>  // Instantieer een Presentation-object dat een presentatiebestand vertegenwoordigt
>  Presentation pres = new Presentation();
>  try {
>      // Haal de eerste dia op
>      ISlide slide = pres.getSlides().get_Item(0);
>      // Voeg een autoshape van type lijn toe
>      slide.getShapes().addAutoShape(ShapeType.Line, 50, 150, 300, 0);
>      // Sla het presentatiebestand op.
>      pres.save("NewPresentation_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>   
>   The following example shows how to open and save Presentation.
>   
>  // Laad elk ondersteund bestand in Presentation, bijv. ppt, pptx, odp etc.
>  Presentation pres = new Presentation("Sample.odp");
>  try {
>      // Sla het presentatiebestand op.
>      pres.save("OutputPresenation.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [Presentation()](#Presentation--) | Deze constructor maakt een nieuwe presentatie vanaf nul. |
| [Presentation(LoadOptions loadOptions)](#Presentation-com.aspose.slides.LoadOptions-) | Deze constructor maakt een nieuwe presentatie vanaf nul. |
| [Presentation(InputStream stream)](#Presentation-java.io.InputStream-) | Deze constructor is het primaire mechanisme om een bestaande presentatie te lezen. |
| [Presentation(InputStream stream, LoadOptions loadOptions)](#Presentation-java.io.InputStream-com.aspose.slides.LoadOptions-) | Deze constructor is het primaire mechanisme om een bestaande presentatie te lezen. |
| [Presentation(String file)](#Presentation-java.lang.String-) | Deze constructor krijgt een bronbestandspad waarvan de inhoud van de presentatie wordt gelezen. |
| [Presentation(String file, LoadOptions loadOptions)](#Presentation-java.lang.String-com.aspose.slides.LoadOptions-) | Deze constructor krijgt een bronbestandspad waarvan de inhoud van de presentatie wordt gelezen. |
## Methods

| Methode | Beschrijving |
| --- | --- |
| [getCurrentDateTime()](#getCurrentDateTime--) | Geeft datum en tijd terug of stelt ze in, die de inhoud van datum/tijd-velden zal vervangen. |
| [setCurrentDateTime(Date value)](#setCurrentDateTime-java.util.Date-) | Geeft datum en tijd terug of stelt ze in, die de inhoud van datum/tijd-velden zal vervangen. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | Geeft de werkelijke HeaderFooter-beheerder terug. |
| [getProtectionManager()](#getProtectionManager--) | Haalt de beheerder van de permissies voor deze presentatie op. |
| [getSlides()](#getSlides--) | Geeft een lijst van alle dia's die zijn gedefinieerd in de presentatie. |
| [getSections()](#getSections--) | Geeft een lijst van alle secties van dia's die zijn gedefinieerd in de presentatie. |
| [getSlideSize()](#getSlideSize--) | Geeft een slide-grootte-object terug. |
| [getNotesSize()](#getNotesSize--) | Geeft een notitie-slide-grootte-object terug. |
| [getLayoutSlides()](#getLayoutSlides--) | Geeft een lijst van alle lay-out-dia's die zijn gedefinieerd in de presentatie. |
| [getMasters()](#getMasters--) | Geeft een lijst van alle master-dia's die zijn gedefinieerd in de presentatie. |
| [getMasterNotesSlideManager()](#getMasterNotesSlideManager--) | Geeft de notitie-master-beheerder terug. |
| [getMasterHandoutSlideManager()](#getMasterHandoutSlideManager--) | Geeft de handout-master-beheerder terug. |
| [getFontsManager()](#getFontsManager--) | Geeft de lettertype-beheerder terug. |
| [getDefaultTextStyle()](#getDefaultTextStyle--) | Geeft de standaard tekststijl voor vormen terug. |
| [getCommentAuthors()](#getCommentAuthors--) | Geeft de verzameling van commentaarauteurs terug. |
| [getDocumentProperties()](#getDocumentProperties--) | Geeft een DocumentProperties-object terug dat standaard- en aangepaste documenteigenschappen bevat. |
| [getImages()](#getImages--) | Geeft de verzameling van alle afbeeldingen in de presentatie terug. |
| [getAudios()](#getAudios--) | Geeft de verzameling van alle ingesloten audiobestanden in de presentatie terug. |
| [getVideos()](#getVideos--) | Geeft de verzameling van alle ingesloten videobestanden in de presentatie terug. |
| [getSlideShowSettings()](#getSlideShowSettings--) | Geeft de diavoorstelling-instellingen voor de presentatie terug. |
| [getDigitalSignatures()](#getDigitalSignatures--) | Geeft de verzameling van handtekeningen terug die gebruikt worden om de presentatie te ondertekenen. |
| [getCustomData()](#getCustomData--) | Geeft de aangepaste gegevens van de presentatie terug. |
| [getAllCustomXmlParts()](#getAllCustomXmlParts--) | Geeft alle aangepaste datagedeelten in de presentatie terug. |
| [getVbaProject()](#getVbaProject--) | Haalt op of stelt het VBA-project met presentatie-macro's in. |
| [setVbaProject(IVbaProject value)](#setVbaProject-com.aspose.slides.IVbaProject-) | Haalt op of stelt het VBA-project met presentatie-macro's in. |
| [getHyperlinkQueries()](#getHyperlinkQueries--) | Biedt gemakkelijke toegang tot alle hyperlinks die in alle presentatiedia's staan (niet in master-, lay-out- of notitiedia's). |
| [getViewProperties()](#getViewProperties--) | Haalt de weergave-eigenschappen voor de hele presentatie op. |
| [getFirstSlideNumber()](#getFirstSlideNumber--) | Stelt het eerste dia-nummer in de presentatie voor |
| [setFirstSlideNumber(int value)](#setFirstSlideNumber-int-) | Stelt het eerste dia-nummer in de presentatie voor |
| [getSensitivityLabels()](#getSensitivityLabels--) | Geeft de verzameling van gevoeligheidslabels terug die op het presentatiedocument zijn toegepast. |
| [getSlideById(long id)](#getSlideById-long-) | Geeft een Slide, MasterSlide of LayoutSlide terug op basis van Id. |
| [getSourceFormat()](#getSourceFormat--) | Geeft informatie terug over uit welk formaat de presentatie is geladen. |
| [getMasterTheme()](#getMasterTheme--) | Geeft het master-thema terug. |
| [save(String fname, int format)](#save-java.lang.String-int-) | Slaat alle dia's van een presentatie op in een bestand met het opgegeven formaat. |
| [save(OutputStream stream, int format)](#save-java.io.OutputStream-int-) | Slaat alle dia's van een presentatie op in een stream in het opgegeven formaat. |
| [save(String fname, int format, ISaveOptions options)](#save-java.lang.String-int-com.aspose.slides.ISaveOptions-) | Slaat alle dia's van een presentatie op in een bestand met het opgegeven formaat en met extra opties. |
| [save(OutputStream stream, int format, ISaveOptions options)](#save-java.io.OutputStream-int-com.aspose.slides.ISaveOptions-) | Slaat alle dia's van een presentatie op in een stream in het opgegeven formaat en met extra opties. |
| [save(IXamlOptions options)](#save-com.aspose.slides.IXamlOptions-) | Slaat alle dia's van een presentatie op in een set bestanden die XAML-markup representeren. |
| [getImages(IRenderingOptions options)](#getImages-com.aspose.slides.IRenderingOptions-) | Geeft Image-objecten terug voor alle dia's van een presentatie. |
| [getImages(IRenderingOptions options, int[] slides)](#getImages-com.aspose.slides.IRenderingOptions-int---) | Geeft Thumbnail Image-objecten terug voor opgegeven dia's van een presentatie. |
| [getImages(IRenderingOptions options, float scaleX, float scaleY)](#getImages-com.aspose.slides.IRenderingOptions-float-float-) | Geeft Thumbnail Image-objecten terug voor alle dia's van een presentatie met aangepaste schaal. |
| [getImages(IRenderingOptions options, int[] slides, float scaleX, float scaleY)](#getImages-com.aspose.slides.IRenderingOptions-int---float-float-) | Geeft Thumbnail Image-objecten terug voor opgegeven dia's van een presentatie met aangepaste schaal. |
| [getImages(IRenderingOptions options, Dimension imageSize)](#getImages-com.aspose.slides.IRenderingOptions-java.awt.Dimension-) | Geeft Thumbnail Image-objecten terug voor alle dia's van een presentatie met opgegeven grootte. |
| [getImages(IRenderingOptions options, int[] slides, Dimension imageSize)](#getImages-com.aspose.slides.IRenderingOptions-int---java.awt.Dimension-) | Geeft Thumbnail Image-objecten terug voor opgegeven dia's van een presentatie met opgegeven grootte. |
| [save(String fname, int[] slides, int format)](#save-java.lang.String-int---int-) | Slaat opgegeven dia's van een presentatie op in een bestand met het opgegeven formaat met behoud van paginanummering. |
| [save(String fname, int[] slides, int format, ISaveOptions options)](#save-java.lang.String-int---int-com.aspose.slides.ISaveOptions-) | Slaat opgegeven dia's van een presentatie op in een bestand met het opgegeven formaat met behoud van paginanummering. |
| [save(OutputStream stream, int[] slides, int format)](#save-java.io.OutputStream-int---int-) | Slaat opgegeven dia's van een presentatie op in een stream in het opgegeven formaat met behoud van paginanummering. |
| [save(OutputStream stream, int[] slides, int format, ISaveOptions options)](#save-java.io.OutputStream-int---int-com.aspose.slides.ISaveOptions-) | Slaat opgegeven dia's van een presentatie op in een stream in het opgegeven formaat met behoud van paginanummering. |
| [joinPortionsWithSameFormatting()](#joinPortionsWithSameFormatting--) | Voegt runs met dezelfde opmaak samen in alle alinea’s in alle acceptabele vormen in alle dia's. |
| [dispose()](#dispose--) | Vrijgeeft alle bronnen die door dit Presentation-object worden gebruikt. |
| [getPresentation()](#getPresentation--) | Geeft de bovenliggende presentatie van een tekst terug. |
| [highlightText(String text, Color highlightColor)](#highlightText-java.lang.String-java.awt.Color-) | Markeert alle overeenkomsten van de voorbeeldtekst met de opgegeven kleur. |
| [highlightText(String text, Color highlightColor, ITextSearchOptions options, IFindResultCallback callback)](#highlightText-java.lang.String-java.awt.Color-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-) | Markeert alle overeenkomsten van de voorbeeldtekst met de opgegeven kleur. |
| [highlightRegex(Pattern regex, Color highlightColor, IFindResultCallback callback)](#highlightRegex-java.util.regex.Pattern-java.awt.Color-com.aspose.slides.IFindResultCallback-) | Markeert alle overeenkomsten van de reguliere expressie met de opgegeven kleur. |
| [replaceText(String oldText, String newText, ITextSearchOptions options, IFindResultCallback callback)](#replaceText-java.lang.String-java.lang.String-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-) | Vervangt alle voorkomens van de opgegeven tekst door een andere opgegeven tekst. |
| [replaceRegex(Pattern regex, String newText, IFindResultCallback callback)](#replaceRegex-java.util.regex.Pattern-java.lang.String-com.aspose.slides.IFindResultCallback-) | Vervangt alle overeenkomsten van de reguliere expressie door de opgegeven string. |
| [refreshChartsData()](#refreshChartsData--) | Laadt de gegevens voor alle grafieken in de presentatie opnieuw vanuit hun bronwerkboeken. |
| [refreshChartsData(boolean skipFailedCharts)](#refreshChartsData-boolean-) | Laadt de gegevens voor alle grafieken in de presentatie opnieuw vanuit hun bronwerkboeken. |
### Presentation() {#Presentation--}
```
public Presentation()
```

Deze constructor maakt een nieuwe presentatie vanaf nul. De gemaakte presentatie bevat één lege dia.

### Presentation(LoadOptions loadOptions) {#Presentation-com.aspose.slides.LoadOptions-}
```
public Presentation(LoadOptions loadOptions)
```

Deze constructor maakt een nieuwe presentatie vanaf nul. De gemaakte presentatie bevat één lege dia.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| loadOptions | [LoadOptions](../../com.aspose.slides/loadoptions) | Aanvullende laadinopties. |

### Presentation(InputStream stream) {#Presentation-java.io.InputStream-}
```
public Presentation(InputStream stream)
```

Deze constructor is het primaire mechanisme om een bestaande presentatie te lezen.

--------------------

> ```
> FileInputStream fis = new FileInputStream("demo.pptx");
>  Presentation pres = new Presentation(fis);
>  fis.close();
> ```


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.InputStream | Invoerstroom. |

### Presentation(InputStream stream, LoadOptions loadOptions) {#Presentation-java.io.InputStream-com.aspose.slides.LoadOptions-}
```
public Presentation(InputStream stream, LoadOptions loadOptions)
```

Deze constructor is het primaire mechanisme om een bestaande presentatie te lezen.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.InputStream | Invoerstroom. |
| loadOptions | [LoadOptions](../../com.aspose.slides/loadoptions) | Aanvullende laadinopties. |

### Presentation(String file) {#Presentation-java.lang.String-}
```
public Presentation(String file)
```

Deze constructor krijgt een bronbestandspad waarvan de inhoud van de presentatie wordt gelezen.

--------------------

> ```
> Presentation pres = new Presentation("demo.pptx");
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| file | java.lang.String | Invoerbestand. |

### Presentation(String file, LoadOptions loadOptions) {#Presentation-java.lang.String-com.aspose.slides.LoadOptions-}
```
public Presentation(String file, LoadOptions loadOptions)
```

Deze constructor krijgt een bronbestandspad waarvan de inhoud van de presentatie wordt gelezen.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| file | java.lang.String | Invoerbestand. |
| loadOptions | [LoadOptions](../../com.aspose.slides/loadoptions) | Aanvullende laadinopties. |

### getCurrentDateTime() {#getCurrentDateTime--}
```
public final Date getCurrentDateTime()
```

Geeft datum en tijd terug of stelt ze in, die de inhoud van datum/tijd-velden zal vervangen. Standaard de tijd van de creatie van dit Presentation-object. Lezen/Schrijven java.util.Date.

**Returns:**
java.util.Date
### setCurrentDateTime(Date value) {#setCurrentDateTime-java.util.Date-}
```
public final void setCurrentDateTime(Date value)
```

Geeft datum en tijd terug of stelt ze in, die de inhoud van datum/tijd-velden zal vervangen. Standaard de tijd van de creatie van dit Presentation-object. Lezen/Schrijven java.util.Date.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.util.Date |  |

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Geeft Parent_Immediate-object terug. Alleen-lezen IDOMObject.

**Returns:**
com.aspose.slides.IDOMObject
### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public final IPresentationHeaderFooterManager getHeaderFooterManager()
```

Geeft de werkelijke HeaderFooter-beheerder terug. Alleen-lezen [IPresentationHeaderFooterManager](../../com.aspose.slides/ipresentationheaderfootermanager).

--------------------

> ```
> The following example shows how to set footer visibility inside Slide of PowerPoint Presentation.
>  
>  Presentation pres = new Presentation("presentation.ppt");
>  try
>  {
>      IBaseSlideHeaderFooterManager headerFooterManager = pres.getSlides().get_Item(0).getHeaderFooterManager();
>      if (!headerFooterManager.isFooterVisible()) // Eigenschap IsFooterVisible wordt gebruikt om aan te geven dat er geen slide-voettekstplaceholder aanwezig is.
>      {
>          headerFooterManager.setFooterVisibility(true); // Methode SetFooterVisibility wordt gebruikt om een slide-voettekstplaceholder zichtbaar te maken.
>      }
>      if (!headerFooterManager.isSlideNumberVisible()) // Eigenschap IsSlideNumberVisible wordt gebruikt om aan te geven dat er geen slide-paginanummerplaceholder aanwezig is.
>      {
>          headerFooterManager.setSlideNumberVisibility(true); // Methode SetSlideNumberVisibility wordt gebruikt om een slide-paginanummerplaceholder zichtbaar te maken.
>      }
>      if (!headerFooterManager.isDateTimeVisible()) // Eigenschap IsDateTimeVisible wordt gebruikt om aan te geven dat er geen slide-datum-tijdplaceholder aanwezig is.
>      {
>          headerFooterManager.setDateTimeVisibility(true); // Methode SetFooterVisibility wordt gebruikt om een slide-datum-tijdplaceholder zichtbaar te maken.
>      }
>      headerFooterManager.setFooterText("Footer text"); // Methode SetFooterText wordt gebruikt om tekst in de slide-voettekstplaceholder te zetten.
>      headerFooterManager.setDateTimeText("Date and time text"); // Methode SetDateTimeText wordt gebruikt om tekst in de slide-datum-tijdplaceholder te zetten.
>      pres.save("Presentation.ppt", SaveFormat.Ppt);
>  }
>  finally
>  {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to set child footer visibility inside Slide.
>  
>  Presentation pres = new Presentation("presentation.ppt");
>  try
>  {
>      IMasterSlideHeaderFooterManager headerFooterManager = pres.getMasters().get_Item(0).getHeaderFooterManager();
>      headerFooterManager.setFooterAndChildFootersVisibility(true); // Methode SetFooterAndChildFootersVisibility wordt gebruikt om een master-slide en alle onderliggende voettekstplaceholders zichtbaar te maken.
>      headerFooterManager.setSlideNumberAndChildSlideNumbersVisibility(true); // Methode SetSlideNumberAndChildSlideNumbersVisibility wordt gebruikt om een master-slide en alle onderliggende paginanummerplaceholders zichtbaar te maken.
>      headerFooterManager.setDateTimeAndChildDateTimesVisibility(true); // Methode SetDateTimeAndChildDateTimesVisibility wordt gebruikt om een master-slide en alle onderliggende datum-tijdplaceholders zichtbaar te maken.
> 
>      headerFooterManager.setFooterAndChildFootersText("Footer text"); // Methode SetFooterAndChildFootersText wordt gebruikt om tekst in de master-slide en alle onderliggende voettekstplaceholders te zetten.
>      headerFooterManager.setDateTimeAndChildDateTimesText("Date and time text"); // Methode SetDateTimeAndChildDateTimesText wordt gebruikt om tekst in de master-slide en alle onderliggende datum-tijdplaceholders te zetten.
>  }
>  finally
>  {
>      if (pres != null) pres.dispose();
>  }
> ```


**Returns:**
[IPresentationHeaderFooterManager](../../com.aspose.slides/ipresentationheaderfootermanager)
### getProtectionManager() {#getProtectionManager--}
```
public final IProtectionManager getProtectionManager()
```

Haalt de beheerder van de permissies voor deze presentatie op. Alleen-lezen [IProtectionManager](../../com.aspose.slides/iprotectionmanager).

**Returns:**
[IProtectionManager](../../com.aspose.slides/iprotectionmanager)
### getSlides() {#getSlides--}
```
public final ISlideCollection getSlides()
```

Geeft een lijst van alle dia's die zijn gedefinieerd in de presentatie. Alleen-lezen [ISlideCollection](../../com.aspose.slides/islidecollection).

--------------------

> ```
> The following example shows how to set slides' background color of PowerPoint Presentation.
>  
>  // Instantieer de Presentation-klasse die het presentiebestand vertegenwoordigt
>  Presentation pres = new Presentation();
>  try
>  {
>      // Stel de achtergrondkleur van de eerste ISlide in op Blauw
>      pres.getSlides().get_Item(0).getBackground().setType(BackgroundType.OwnBackground);
>      pres.getSlides().get_Item(0).getBackground().getFillFormat().setFillType(FillType.Solid);
>      pres.getSlides().get_Item(0).getBackground().getFillFormat().getSolidFillColor().setColor(Color.BLUE);
>      pres.save("ContentBG_out.pptx", SaveFormat.Pptx);
>  }
>  finally
>  {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to set slides' background image of PowerPoint Presentation.
>  
>  // Instantieer de Presentation-klasse die het presentiebestand vertegenwoordigt
>  Presentation pres = new Presentation("SetImageAsBackground.pptx");
>  try {
>      // Stel de achtergrond in met Afbeelding
>      pres.getSlides().get_Item(0).getBackground().setType(BackgroundType.OwnBackground);
>      pres.getSlides().get_Item(0).getBackground().getFillFormat().setFillType(FillType.Picture);
>      pres.getSlides().get_Item(0).getBackground().getFillFormat().getPictureFillFormat().setPictureFillMode(PictureFillMode.Stretch);
>      // Stel de afbeelding in
>      BufferedImage img = ImageIO.read(new File("Tulips.jpg"));
>      // Voeg de afbeelding toe aan de afbeeldingencollectie van de presentatie
>      IPPImage imgx = pres.getImages().addImage(img);
>      pres.getSlides().get_Item(0).getBackground().getFillFormat().getPictureFillFormat().getPicture().setImage(imgx);
>      // Schrijf de presentatie naar schijf
>      pres.save("ContentBG_Img_out.pptx", SaveFormat.Pptx);
>  } catch (IOException e) { }
>  finally
>  {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to add slide transition Presentation.
>  
>  // Instantieer de Presentation-klasse om het bronpresentiebestand te laden
>  Presentation pres = new Presentation("AccessSlides.pptx");
>  try
>  {
>      // Pas cirkeltypeovergang toe op dia 1
>      pres.getSlides().get_Item(0).getSlideShowTransition().setType(TransitionType.Circle);
>      // Pas kamtypeovergang toe op dia 2
>      pres.getSlides().get_Item(1).getSlideShowTransition().setType(TransitionType.Comb);
>      // Schrijf de presentatie naar schijf
>      pres.save("SampleTransition_out.pptx", SaveFormat.Pptx);
>  }
>  finally
>  {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to add advanced slide Transition.
>  
>  // Instantieer de Presentation-klasse die een presentiebestand vertegenwoordigt
>  Presentation pres = new Presentation("BetterSlideTransitions.pptx");
>  try
>  {
>      // Pas cirkeltypeovergang toe op dia 1
>      pres.getSlides().get_Item(0).getSlideShowTransition().setType(TransitionType.Circle);
>      // Stel de overgangstijd in op 3 seconden
>      pres.getSlides().get_Item(0).getSlideShowTransition().setAdvanceOnClick(true);
>      pres.getSlides().get_Item(0).getSlideShowTransition().setAdvanceAfterTime(3000);
>      // Pas kamtypeovergang toe op dia 2
>      pres.getSlides().get_Item(1).getSlideShowTransition().setType(TransitionType.Comb);
>      // Stel de overgangstijd in op 5 seconden
>      pres.getSlides().get_Item(1).getSlideShowTransition().setAdvanceOnClick(true);
>      pres.getSlides().get_Item(1).getSlideShowTransition().setAdvanceAfterTime(5000);
>      // Pas zoomtypeovergang toe op dia 3
>      pres.getSlides().get_Item(2).getSlideShowTransition().setType(TransitionType.Zoom);
>      // Stel de overgangstijd in op 7 seconden
>      pres.getSlides().get_Item(2).getSlideShowTransition().setAdvanceOnClick(true);
>      pres.getSlides().get_Item(2).getSlideShowTransition().setAdvanceAfterTime(7000);
>      // Schrijf de presentatie naar schijf
>      pres.save("SampleTransition_out.pptx", SaveFormat.Pptx);
>  }
>  finally
>  {
>      if (pres != null) pres.dispose();
>  }
> ```


**Returns:**
[ISlideCollection](../../com.aspose.slides/islidecollection)
### getSections() {#getSections--}
```
public final ISectionCollection getSections()
```

Geeft een lijst van alle secties van dia's die zijn gedefinieerd in de presentatie. Alleen-lezen [ISectionCollection](../../com.aspose.slides/isectioncollection).

--------------------

> ```
> The following examples shows how to create Sections in a PowerPoint Presentation.
>  
>  Presentation pres = new Presentation();
>  try {
>      ISlide defaultSlide = pres.getSlides().get_Item(0);
>      ISlide newSlide1 = pres.getSlides().addEmptySlide(pres.getLayoutSlides().get_Item(0));
>      ISlide newSlide2 = pres.getSlides().addEmptySlide(pres.getLayoutSlides().get_Item(0));
>      ISlide newSlide3 = pres.getSlides().addEmptySlide(pres.getLayoutSlides().get_Item(0));
>      ISlide newSlide4 = pres.getSlides().addEmptySlide(pres.getLayoutSlides().get_Item(0));
>      ISection section1 = pres.getSections().addSection("Section 1", newSlide1);
>      // section1 wordt beëindigd bij newSlide2 en daarna start section2
>      ISection section2 = pres.getSections().addSection("Section 2", newSlide3);
>      pres.save("pres-sections.pptx", SaveFormat.Pptx);
>      pres.getSections().reorderSectionWithSlides(section2, 0);
>      pres.save("pres-sections-moved.pptx", SaveFormat.Pptx);
>      pres.getSections().removeSectionWithSlides(section2);
>      pres.getSections().appendEmptySection("Last empty section");
>      pres.save("pres-section-with-empty.pptx",SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following examples shows how to changing the names of Sections.
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      ISection section = pres.getSections().get_Item(0);
>      section.setName("My section");
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Returns:**
[ISectionCollection](../../com.aspose.slides/isectioncollection)
### getSlideSize() {#getSlideSize--}
```
public final ISlideSize getSlideSize()
```

Geeft een slide-grootte-object terug. Alleen-lezen [ISlideSize](../../com.aspose.slides/islidesize).

--------------------

> ```
> The following example shows how to change the slide size in a PowerPoint Presentation.
>  
>  Presentation pres = new Presentation("pres-4x3-aspect-ratio.pptx");
>  try {
>      pres.getSlideSize().setSize(SlideSizeType.OnScreen16x9, SlideSizeScaleType.DoNotScale);
>      pres.save("pres-4x3-aspect-ratio.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to set slide size with respect to content scaling for a PowerPoint Presentation.
>  
>  // Instantieer een Presentation-object dat een presentiebestand vertegenwoordigt
>  Presentation presentation = new Presentation("AccessSlides.pptx");
>  try {
>      Presentation auxPresentation = new Presentation();
>      try {
>          ISlide slide = presentation.getSlides().get_Item(0);
>          // Stel de dia-afmeting van gegenereerde presentaties in op die van de bron
>          presentation.getSlideSize().setSize(540, 720, SlideSizeScaleType.EnsureFit); // Methode SetSize wordt gebruikt om de dia-afmeting in te stellen met geschaalde inhoud zodat deze past
>          presentation.getSlideSize().setSize(SlideSizeType.A4Paper, SlideSizeScaleType.Maximize); // Methode SetSize wordt gebruikt om de dia-afmeting in te stellen met maximale grootte van de inhoud
>          // Sla de presentatie op naar schijf
>          auxPresentation.save("Set_Size&Type_out.pptx", SaveFormat.Pptx);
>      } finally {
>          if (auxPresentation != null) auxPresentation.dispose();
>      }
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
>  
>  The following example shows how to specifying custom slide sizes in a PowerPoint Presentation.
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      pres.getSlideSize().setSize(780, 540, SlideSizeScaleType.DoNotScale); // A4-papierformaat
>      pres.save("pres-a4-slide-size.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Returns:**
[ISlideSize](../../com.aspose.slides/islidesize)
### getNotesSize() {#getNotesSize--}
```
public final INotesSize getNotesSize()
```

Geeft een notitie-slide-grootte-object terug. Alleen-lezen [INotesSize](../../com.aspose.slides/inotessize).

**Returns:**
[INotesSize](../../com.aspose.slides/inotessize)
### getLayoutSlides() {#getLayoutSlides--}
```
public final IGlobalLayoutSlideCollection getLayoutSlides()
```

Geeft een lijst van alle lay-out-dia's die zijn gedefinieerd in de presentatie. Alleen-lezen [IGlobalLayoutSlideCollection](../../com.aspose.slides/igloballayoutslidecollection).

--------------------

U kunt toegang krijgen tot een alternatieve API voor het toevoegen/invoegen/verwijderen/kopiëren van lay-out-dia's via de eigenschap IMasterSlide.LayoutSlides.

**Returns:**
[IGlobalLayoutSlideCollection](../../com.aspose.slides/igloballayoutslidecollection)
### getMasters() {#getMasters--}
```
public final IMasterSlideCollection getMasters()
```

Geeft een lijst van alle master-dia's die zijn gedefinieerd in de presentatie. Alleen-lezen [IMasterSlideCollection](../../com.aspose.slides/imasterslidecollection).

--------------------

> ```
> The following examples shows how to adding Images to Master Slides of PowerPoint Presentation.
>  
>  Presentation pres = new Presentation();
>  try {
>      ISlide slide = pres.getSlides().get_Item(0);
>      IMasterSlide masterSlide = slide.getLayoutSlide().getMasterSlide();
>      IPPImage image = pres.getImages().addImage(Files.readAllBytes(Paths.get("image.png")));
>      masterSlide.getShapes().addPictureFrame(ShapeType.Rectangle, 10, 10, 100, 100, image);
>      pres.save("pres.pptx", SaveFormat.Pptx);
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following examples shows how to change the background color of the master slide of PowerPoint Presentation.
>  
>  // Instantiate the Presentation class that represents the presentation file
>  Presentation pres = new Presentation();
>  try
>  {
>      // Set the background color of the Master ISlide to Forest Green
>      pres.getMasters().get_Item(0).getBackground().setType(BackgroundType.OwnBackground);
>      pres.getMasters().get_Item(0).getBackground().getFillFormat().setFillType(FillType.Solid);
>      pres.getMasters().get_Item(0).getBackground().getFillFormat().getSolidFillColor().setColor(Color.GREEN);
>      // Write the presentation to disk
>      pres.save("SetSlideBackgroundMaster_out.pptx", SaveFormat.Pptx);
>  }
>  finally
>  {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following examples shows how to add slide layout to PowerPoint Presentation.
>  
>  // Instantiate Presentation class that represents the presentation file
>  Presentation presentation = new Presentation("AccessSlides.pptx");
>  try
>  {
>      // Try to search by layout slide type
>      IMasterLayoutSlideCollection layoutSlides = presentation.getMasters().get_Item(0).getLayoutSlides();
>      ILayoutSlide layoutSlide = null;
>      if (layoutSlides.getByType(SlideLayoutType.TitleAndObject) != null)
>          layoutSlide = layoutSlides.getByType(SlideLayoutType.TitleAndObject);
>      else
>          layoutSlide = layoutSlides.getByType(SlideLayoutType.Title);
> 
>      if (layoutSlide == null)
>      {
>          // The situation when a presentation doesn't contain some type of layouts.
>          // presentation File only contains Blank and Custom layout types.
>          // But layout slides with Custom types has different slide names,
>          // like "Title", "Title and Content", etc. And it is possible to use these
>          // names for layout slide selection.
>          // Also it is possible to use the set of placeholder shape types. For example,
>          // Title slide should have only Title pleceholder type, etc.
>          for (ILayoutSlide titleAndObjectLayoutSlide : (Iterable) layoutSlides)
>          {
>              if ("Title and Object".equals(titleAndObjectLayoutSlide.getName()))
>              {
>                  layoutSlide = titleAndObjectLayoutSlide;
>                  break;
>              }
>          }
>          if (layoutSlide == null)
>          {
>              for (ILayoutSlide titleLayoutSlide : (Iterable) layoutSlides)
>              {
>                  if ("Title".equals(titleLayoutSlide.getName()))
>                  {
>                      layoutSlide = titleLayoutSlide;
>                      break;
>                  }
>              }
>              if (layoutSlide == null)
>              {
>                  layoutSlide = layoutSlides.getByType(SlideLayoutType.Blank);
>                  if (layoutSlide == null)
>                  {
>                      layoutSlide = layoutSlides.add(SlideLayoutType.TitleAndObject, "Title and Object");
>                  }
>              }
>          }
>      }
>      // Adding empty slide with added layout slide
>      presentation.getSlides().insertEmptySlide(0, layoutSlide);
>      // Save presentation
>      presentation.save("AddLayoutSlides_out.pptx", SaveFormat.Pptx);
>  }
>  finally
>  {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Returns:**
[IMasterSlideCollection](../../com.aspose.slides/imasterslidecollection)
### getMasterNotesSlideManager() {#getMasterNotesSlideManager--}
```
public final IMasterNotesSlideManager getMasterNotesSlideManager()
```

Geeft notitie-master-beheerder terug. Alleen-lezen [IMasterNotesSlideManager](../../com.aspose.slides/imasternotesslidemanager).

**Returns:**
[IMasterNotesSlideManager](../../com.aspose.slides/imasternotesslidemanager)
### getMasterHandoutSlideManager() {#getMasterHandoutSlideManager--}
```
public final IMasterHandoutSlideManager getMasterHandoutSlideManager()
```

Geeft handout-master-beheerder terug. Alleen-lezen [IMasterHandoutSlideManager](../../com.aspose.slides/imasterhandoutslidemanager).

**Returns:**
[IMasterHandoutSlideManager](../../com.aspose.slides/imasterhandoutslidemanager)
### getFontsManager() {#getFontsManager--}
```
public final IFontsManager getFontsManager()
```

Geeft de lettertype-beheerder terug. Alleen-lezen [IFontsManager](../../com.aspose.slides/ifontsmanager).

--------------------

> ```
> The following example shows how to add embedded fonts to PowerPoint Presentation.
>  
>  // Laad presentatie
>  Presentation pres = new Presentation("Fonts.pptx");
>  try {
>      // Laad bronlettertype om te vervangen
>      IFontData sourceFont = new FontData("Arial");
>      IFontData[] allFonts = pres.getFontsManager().getFonts();
>      for (IFontData font : allFonts)
>      {
>          boolean fontAlreadyEmbedded = false;
>          IFontData[] embeddedFonts = pres.getFontsManager().getEmbeddedFonts();
>          for (int i = 0; i < embeddedFonts.length; i++)
>          {
>              if (embeddedFonts[i].equals(font))
>              {
>                  fontAlreadyEmbedded = true;
>                  break;
>              }
>          }
>          if (!fontAlreadyEmbedded) {
>              pres.getFontsManager().addEmbeddedFont(font, EmbedFontCharacters.All);
>          }
>      }
>      // Sla de presentatie op
>      pres.save("AddEmbeddedFont_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Returns:**
[IFontsManager](../../com.aspose.slides/ifontsmanager)
### getDefaultTextStyle() {#getDefaultTextStyle--}
```
public final ITextStyle getDefaultTextStyle()
```

Geeft de standaard tekststijl voor vormen terug. Alleen-lezen [ITextStyle](../../com.aspose.slides/itextstyle).

**Returns:**
[ITextStyle](../../com.aspose.slides/itextstyle)
### getCommentAuthors() {#getCommentAuthors--}
```
public final ICommentAuthorCollection getCommentAuthors()
```

Geeft de verzameling van commentaarauteurs terug. Alleen-lezen [ICommentAuthorCollection](../../com.aspose.slides/icommentauthorcollection).

**Returns:**
[ICommentAuthorCollection](../../com.aspose.slides/icommentauthorcollection)
### getDocumentProperties() {#getDocumentProperties--}
```
public final IDocumentProperties getDocumentProperties()
```

Geeft een DocumentProperties-object terug dat standaard- en aangepaste documenteigenschappen bevat. Alleen-lezen [IDocumentProperties](../../com.aspose.slides/idocumentproperties).

**Returns:**
[IDocumentProperties](../../com.aspose.slides/idocumentproperties)
### getImages() {#getImages--}
```
public final IImageCollection getImages()
```

Geeft de verzameling van alle afbeeldingen in de presentatie terug. Alleen-lezen [IImageCollection](../../com.aspose.slides/iimagecollection).

--------------------

> ```
> The following examples shows how to add image as BLOB in PowerPoint Presentation.
>  
>  // maakt een nieuwe presentatie waaraan de afbeelding wordt toegevoegd.
>  Presentation pres = new Presentation();
>  try
>  {
>      // ervan uitgaande dat we het grote afbeeldingsbestand hebben dat we in de presentatie willen opnemen
>      FileInputStream fip = new FileInputStream("large_image.jpg");
>      try
>      {
>          // Laten we de afbeelding aan de presentatie toevoegen - we kiezen KeepLocked gedrag omdat we
>          // NIET van plan zijn om het "largeImage.png" bestand te benaderen.
>          IPPImage img = pres.getImages().addImage(fip, LoadingStreamBehavior.KeepLocked);
>          pres.getSlides().get_Item(0).getShapes().addPictureFrame(ShapeType.Rectangle, 0, 0, 300, 200, img);
>          // Slaat de presentatie op. Terwijl een grote presentatie wordt gegenereerd, blijft het geheugenverbruik
>          // laag gedurende de levenscyclus van het pres-object
>          pres.save("presentationWithLargeImage.pptx", SaveFormat.Pptx);
>      }
>      finally
>      {
>          fip.close();
>      }
>  }
>  catch (java.io.IOException e) { }
>  finally
>  {
>      pres.dispose();
>  }
>  
>  The following examples add a hyperlink to an image in a PowerPoint Presentation.
>  
>  Presentation pres = new Presentation();
>  try {
>      // Voegt afbeelding toe aan presentatie
>      IPPImage image = pres.getImages().addImage(Files.readAllBytes(Paths.get("image.png")));
>      // Maakt een afbeeldingframe op dia 1 op basis van de eerder toegevoegde afbeelding
>      IPictureFrame pictureFrame = pres.getSlides().get_Item(0).getShapes().addPictureFrame(ShapeType.Rectangle, 10, 10, 100, 100, image);
>      pictureFrame.setHyperlinkClick(new Hyperlink("https://www.aspose.com/"));
>      pictureFrame.getHyperlinkClick().setTooltip("More than 70% Fortune 100 companies trust Aspose APIs");
>      pres.save("pres-out.pptx", SaveFormat.Pptx);
>  } catch (IOException e){ }
>  finally
>  {
>      if (pres != null) pres.dispose();
>  }
> ```


**Returns:**
[IImageCollection](../../com.aspose.slides/iimagecollection)
### getAudios() {#getAudios--}
```
public final IAudioCollection getAudios()
```
Retourneert de collectie van alle ingesloten audiobestanden in de presentatie. Alleen-lezen [IAudioCollection](../../com.aspose.slides/iaudiocollection).

--------------------

> ```
> The following examples shows how to add a hyperlink to an audio file.
>  
>  Presentation pres = new Presentation();
>  try {
>      IAudio audio = pres.getAudios().addAudio(Files.readAllBytes(Paths.get("audio.mp3")));
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(10, 10, 100, 100, audio);
>      audioFrame.setHyperlinkClick(new Hyperlink("https://www.aspose.com/"));
>      audioFrame.getHyperlinkClick().setTooltip("More than 70% Fortune 100 companies trust Aspose APIs");
>      pres.save("pres-out.pptx", SaveFormat.Pptx);
>  }
>  catch (IOException e) {}
>  finally
>  {
>      if (pres != null) pres.dispose();
>  }
> ```


**Retourneert:**
[IAudioCollection](../../com.aspose.slides/iaudiocollection)
### getVideos() {#getVideos--}
```
public final IVideoCollection getVideos()
```


Retourneert de collectie van alle ingesloten videobestanden in de presentatie. Alleen-lezen [IVideoCollection](../../com.aspose.slides/ivideocollection).

--------------------

> ```
> The following examples shows how to add image as BLOB in PowerPoint Presentation.
>  
>  // maakt een nieuwe presentatie waaraan de afbeelding wordt toegevoegd.
>  Presentation pres = new Presentation();
>  try
>  {
>      // ervan uitgaande dat we het grote afbeeldingsbestand hebben dat we in de presentatie willen opnemen
>      FileInputStream fip = new FileInputStream("large_image.jpg");
>      try
>      {
>          // Laten we de afbeelding aan de presentatie toevoegen - we kiezen KeepLocked gedrag omdat we
>          // NIET van plan zijn om het "largeImage.png" bestand te benaderen.
>          IPPImage img = pres.getImages().addImage(fip, LoadingStreamBehavior.KeepLocked);
>          pres.getSlides().get_Item(0).getShapes().addPictureFrame(ShapeType.Rectangle, 0, 0, 300, 200, img);
>          // Slaat de presentatie op. Terwijl een grote presentatie wordt gegenereerd, blijft het geheugenverbruik
>          // laag gedurende de levenscyclus van het pres-object
>          pres.save("presentationWithLargeImage.pptx", SaveFormat.Pptx);
>      }
>      finally
>      {
>          fip.close();
>      }
>  }
>  catch (java.io.IOException e) { }
>  finally
>  {
>      pres.dispose();
>  }
>  
>  The following examples add a hyperlink to an image in a PowerPoint Presentation.
>  
>  Presentation pres = new Presentation();
>  try {
>      // Voegt afbeelding toe aan presentatie
>      IPPImage image = pres.getImages().addImage(Files.readAllBytes(Paths.get("image.png")));
>      // Maakt een afbeeldingframe op dia 1 op basis van de eerder toegevoegde afbeelding
>      IPictureFrame pictureFrame = pres.getSlides().get_Item(0).getShapes().addPictureFrame(ShapeType.Rectangle, 10, 10, 100, 100, image);
>      pictureFrame.setHyperlinkClick(new Hyperlink("https://www.aspose.com/"));
>      pictureFrame.getHyperlinkClick().setTooltip("More than 70% Fortune 100 companies trust Aspose APIs");
>      pres.save("pres-out.pptx", SaveFormat.Pptx);
>  } catch (IOException e){ }
>  finally
>  {
>      if (pres != null) pres.dispose();
>  }
> ```


**Retourneert:**
[IVideoCollection](../../com.aspose.slides/ivideocollection)
### getSlideShowSettings() {#getSlideShowSettings--}
```
public final SlideShowSettings getSlideShowSettings()
```


Retourneert de instellingen voor de diavoorstelling van de presentatie.

**Retourneert:**
[SlideShowSettings](../../com.aspose.slides/slideshowsettings)
### getDigitalSignatures() {#getDigitalSignatures--}
```
public final IDigitalSignatureCollection getDigitalSignatures()
```


Retourneert de collectie van handtekeningen die zijn gebruikt om de presentatie te ondertekenen. Alleen-lezen [IDigitalSignatureCollection](../../com.aspose.slides/idigitalsignaturecollection).

--------------------

> ```
> Presentation pres = new Presentation("SomePresentationSigned.pptx");
>  try
>  {
>      if (pres.getDigitalSignatures().size() > 0)
>      {
>          boolean allSignaturesAreValid = true;
>          System.out.println("Signatures used to sign the presentation: ");
>          for (IDigitalSignature signature : pres.getDigitalSignatures())
>          {
>             System.out.println(signature.getCertificate().hashCode() + ", "
>                   + signature.getSignTime().toString() + " -- " + (signature.isValid() ? "VALID" : "INVALID"));
>             allSignaturesAreValid &= signature.isValid();
>          }
>          if (allSignaturesAreValid)
>             System.out.println("Presentation is genuine, all signatures are valid.");
>          else
>             System.out.println("Presentation has been modified since signing.");
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Retourneert:**
[IDigitalSignatureCollection](../../com.aspose.slides/idigitalsignaturecollection)
### getCustomData() {#getCustomData--}
```
public final ICustomData getCustomData()
```


Retourneert de aangepaste gegevens van de presentatie. Alleen-lezen [ICustomData](../../com.aspose.slides/icustomdata).

**Retourneert:**
[ICustomData](../../com.aspose.slides/icustomdata)
### getAllCustomXmlParts() {#getAllCustomXmlParts--}
```
public final ICustomXmlPart[] getAllCustomXmlParts()
```


Retourneert alle aangepaste gegevensonderdelen in de presentatie. Alleen-lezen ICustomXmlPart[].

--------------------

> ```
> The following examples show how to clear all custom xml parts from PowerPoint Presentation.
>  
>  Presentation pres = new Presentation("PresentationWithCustomXml.pptx");
>  try {
>      // Itereren over alle aangepaste XML-onderdelen
>      for (ICustomXmlPart item : pres.getAllCustomXmlParts())
>      {
>          item.remove();
>      }
>      pres.save("out.pptx", SaveFormat.Pptx);
>  }
>  finally
>  {
>      if (pres != null) pres.dispose();
>  }
> ```


**Retourneert:**
com.aspose.slides.ICustomXmlPart[]
### getVbaProject() {#getVbaProject--}
```
public final IVbaProject getVbaProject()
```


Haalt het VBA-project op of stelt het in met presentatiemacro’s. Lezen/Schrijven [IVbaProject](../../com.aspose.slides/ivbaproject).

**Retourneert:**
[IVbaProject](../../com.aspose.slides/ivbaproject)
### setVbaProject(IVbaProject value) {#setVbaProject-com.aspose.slides.IVbaProject-}
```
public final void setVbaProject(IVbaProject value)
```


Stelt het VBA-project met presentatiemacro’s in. Lezen/Schrijven [IVbaProject](../../com.aspose.slides/ivbaproject).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [IVbaProject](../../com.aspose.slides/ivbaproject) |  |

### getHyperlinkQueries() {#getHyperlinkQueries--}
```
public              
```


Biedt eenvoudige toegang tot alle hyperlinks die voorkomen in alle presentatieslides (niet in master-, lay- of notitieslides). Alleen-lezen [IHyperlinkQueries](../../com.aspose.slides/ihyperlinkqueries).

**Retourneert:**
[IHyperlinkQueries](../../com.aspose.slides/ihyperlinkqueries)
### getViewProperties() {#getViewProperties--}
```
public final IViewProperties getViewProperties()
```


Haalt de weergave-eigenschappen voor de gehele presentatie op. Alleen-lezen [IViewProperties](../../com.aspose.slides/iviewproperties).

**Retourneert:**
[IViewProperties](../../com.aspose.slides/iviewproperties)
### getFirstSlideNumber() {#getFirstSlideNumber--}
```
public final int getFirstSlideNumber()
```


Geeft het eerste slidennummer in de presentatie weer

**Retourneert:**
int
### setFirstSlideNumber(int value) {#setFirstSlideNumber-int-}
```
public final void setFirstSlideNumber(int value)
```


Stelt het eerste slidennummer in de presentatie in

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | int |  |

### getSensitivityLabels() {#getSensitivityLabels--}
```
public final ISensitivityLabelCollection getSensitivityLabels()
```


Retourneert de collectie van gevoeligheids-labels die op het presentatiedocument zijn toegepast. Alleen-lezen [ISensitivityLabelCollection](../../com.aspose.slides/isensitivitylabelcollection).

--------------------

> ```
> Presentation pres = new Presentation("SomePresentation.pptx");
>  try {
>      ISensitivityLabelCollection sensitivityLabels = pres.getSensitivityLabels();
> 
>      // Print de toegepaste labels
>      for (ISensitivityLabel sensitivityLabel : sensitivityLabels)
>          System.out.println("Label Id " + sensitivityLabel.getId() + " from Azure AD site " + sensitivityLabel.getSiteId());
> 
>      // Voeg het nieuwe label toe
>      String labelIdString = "{xxxxxxxx-xxxx-xxxx-xxxx-xxxxxxxxxxxx}"; // Haal de gevoeligheidslabel-ID op uit het beleid
>      UUID siteIdGuid = UUID.fromString("{xxxxxxxx-xxxx-xxxx-xxxx-xxxxxxxxxxxx}"); // Haal de Azure AD-site-identificator op uit het beleid
>      ISensitivityLabel label = sensitivityLabels.add(labelIdString, siteIdGuid, true, SensitivityLabelAssignmentType.Privileged);
>      label.getContentMarkTypes().addItem(SensitivityLabelContentType.Footer);
> 
>      pres.save("SensitivityLabel.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Retourneert:**
[ISensitivityLabelCollection](../../com.aspose.slides/isensitivitylabelcollection)
### getSlideById(long id) {#getSlideById-long-}
```
public final IBaseSlide getSlideById(long id)
```


Retourneert een Slide, MasterSlide of LayoutSlide op basis van Id.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| id | long | Id van een slide. |

**Retourneert:**
[IBaseSlide](../../com.aspose.slides/ibaseslide) - IBaseSlide object.
### getSourceFormat() {#getSourceFormat--}
```
public final int getSourceFormat()
```


Retourneert informatie over uit welk formaat de presentatie is geladen. Alleen-lezen [SourceFormat](../../com.aspose.slides/sourceformat).

**Retourneert:**
int
### getMasterTheme() {#getMasterTheme--}
```
public final IMasterTheme getMasterTheme()
```


Retourneert het master-thema. Alleen-lezen [IMasterTheme](../../com.aspose.slides/imastertheme).

--------------------

> ```
> The following examples shows how to change a theme effect by altering parts of elements of PowerPoint Presentation.
>  
>  // Instantieer een Presentation-object dat een presentiebestand vertegenwoordigt
>  Presentation pres = new Presentation("Subtle_Moderate_Intense.pptx");
>  try {
>      pres.getMasterTheme().getFormatScheme().getLineStyles().get_Item(0).getFillFormat().getSolidFillColor().setColor(Color.RED);
>      ((FillFormat)pres.getMasterTheme().getFormatScheme().getLineStyles().get_Item(2)).setFillType(FillType.Solid);
>      ((FillFormat)pres.getMasterTheme().getFormatScheme().getLineStyles().get_Item(2)).getSolidFillColor().setColor(Color.GREEN);
>      ((EffectStyle)pres.getMasterTheme().getFormatScheme().getLineStyles().get_Item(2)).getEffectFormat().getOuterShadowEffect().setDistance(10f);
>      pres.save("Design_04_Subtle_Moderate_Intense-out.pptx", SaveFormat.Pptx);
>  }
>  finally
>  {
>      if (pres != null) pres.dispose();
>  }
> ```


**Retourneert:**
[IMasterTheme](../../com.aspose.slides/imastertheme)
### save(String fname, int format) {#save-java.lang.String-int-}
```
public final void save(String fname, int format)
```


Slaat alle slides van een presentatie op in een bestand met het opgegeven formaat.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| fname | java.lang.String | Pad naar het te maken bestand. |
| format | int | Formaat van de geëxporteerde gegevens. |

### save(OutputStream stream, int format) {#save-java.io.OutputStream-int-}
```
public final void save(OutputStream stream, int format)
```


Slaat alle slides van een presentatie op in een stream met het opgegeven formaat.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| stream | java.io.OutputStream | Uitvoerstroom. |
| format | int | Formaat van de geëxporteerde gegevens. |

### save(String fname, int format, ISaveOptions options) {#save-java.lang.String-int-com.aspose.slides.ISaveOptions-}
```
public final void save(String fname, int format, ISaveOptions options)
```


Slaat alle slides van een presentatie op in een bestand met het opgegeven formaat en met extra opties.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| fname | java.lang.String | Pad naar het te maken bestand. |
| format | int | Formaat van de geëxporteerde gegevens. |
| options | [ISaveOptions](../../com.aspose.slides/isaveoptions) | Extra opmaakopties. |

### save(OutputStream stream, int format, ISaveOptions options) {#save-java.io.OutputStream-int-com.aspose.slides.ISaveOptions-}
```
public final void save(OutputStream stream, int format, ISaveOptions options)
```


Slaat alle slides van een presentatie op in een stream met het opgegeven formaat en met extra opties.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| stream | java.io.OutputStream | Uitvoerstroom. |
| format | int | Formaat van de geëxporteerde gegevens. |
| options | [ISaveOptions](../../com.aspose.slides/isaveoptions) | Extra opmaakopties. |

### save(IXamlOptions options) {#save-com.aspose.slides.IXamlOptions-}
```
public final void save(IXamlOptions options)
```


Slaat alle slides van een presentatie op in een set bestanden die XAML-markering vertegenwoordigen.

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      XamlOptions xamlOptions = new XamlOptions();
>      xamlOptions.setExportHiddenSlides(true);
> 
>      pres.save(xamlOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| options | [IXamlOptions](../../com.aspose.slides/ixamloptions) | De XAML-formaatopties. |

### getImages(IRenderingOptions options) {#getImages-com.aspose.slides.IRenderingOptions-}
```
public final IImage[] getImages(IRenderingOptions options)
```


Retourneert Image-objecten voor alle slides van een presentatie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Tiff-opties. |

**Retourneert:**
com.aspose.slides.IImage[] - Image-objecten.
### getImages(IRenderingOptions options, int[] slides) {#getImages-com.aspose.slides.IRenderingOptions-int---}
```
public final IImage[] getImages(IRenderingOptions options, int[] slides)
```


Retourneert Thumbnail-Image-objecten voor de opgegeven slides van een presentatie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Tiff-opties. |
| slides | int[] | Array met slide-posities, beginnend bij 1. |

**Retourneert:**
com.aspose.slides.IImage[] - Image-objecten.
### getImages(IRenderingOptions options, float scaleX, float scaleY) {#getImages-com.aspose.slides.IRenderingOptions-float-float-}
```
public final IImage[] getImages(IRenderingOptions options, float scaleX, float scaleY)
```


Retourneert Thumbnail-Image-objecten voor alle slides van een presentatie met aangepaste schaal.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Tiff-opties. |
| scaleX | float | De waarde waarmee deze Thumbnail in x-richting wordt geschaald. |
| scaleY | float | De waarde waarmee deze Thumbnail in y-richting wordt geschaald. |

**Retourneert:**
com.aspose.slides.IImage[] - Image-objecten.
### getImages(IRenderingOptions options, int[] slides, float scaleX, float scaleY) {#getImages-com.aspose.slides.IRenderingOptions-int---float-float-}
```
public final IImage[] getImages(IRenderingOptions options, int[] slides, float scaleX, float scaleY)
```


Retourneert Thumbnail-Image-objecten voor de opgegeven slides van een presentatie met aangepaste schaal.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Tiff-opties. |
| slides | int[] | Array met slide-posities, beginnend bij 1. |
| scaleX | float | De waarde waarmee deze Thumbnail in x-richting wordt geschaald. |
| scaleY | float | De waarde waarmee deze Thumbnail in y-richting wordt geschaald. |

**Retourneert:**
com.aspose.slides.IImage[] - Image-objecten.
### getImages(IRenderingOptions options, Dimension imageSize) {#getImages-com.aspose.slides.IRenderingOptions-java.awt.Dimension-}
```
public final IImage[] getImages(IRenderingOptions options, Dimension imageSize)
```


Retourneert Thumbnail-Image-objecten voor alle slides van een presentatie met opgegeven grootte.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Tiff-opties. |
| imageSize | java.awt.Dimension | Grootte van de te creëren afbeelding. |

**Retourneert:**
com.aspose.slides.IImage[] - Image-objecten.
### getImages(IRenderingOptions options, int[] slides, Dimension imageSize) {#getImages-com.aspose.slides.IRenderingOptions-int---java.awt.Dimension-}
```
public final IImage[] getImages(IRenderingOptions options, int[] slides, Dimension imageSize)
```


Retourneert Thumbnail-Image-objecten voor de opgegeven slides van een presentatie met opgegeven grootte.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Tiff-opties. |
| slides | int[] | Array met slide-posities, beginnend bij 1. |
| imageSize | java.awt.Dimension | Grootte van de te creëren afbeelding. |

**Retourneert:**
com.aspose.slides.IImage[] - Image-objecten.
### save(String fname, int[] slides, int format) {#save-java.lang.String-int---int-}
```
public final void save(String fname, int[] slides, int format)
```


Slaat de opgegeven slides van een presentatie op in een bestand met het opgegeven formaat met behoud van paginanummering.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| fname | java.lang.String | Pad naar het te maken bestand. |
| slides | int[] | Array met slide-posities, beginnend bij 1. |
| format | int | Formaat van de geëxporteerde gegevens. |

### save(String fname, int[] slides, int format, ISaveOptions options) {#save-java.lang.String-int---int-com.aspose.slides.ISaveOptions-}
```
public final void save(String fname, int[] slides, int format, ISaveOptions options)
```


Slaat de opgegeven slides van een presentatie op in een bestand met het opgegeven formaat met behoud van paginanummering.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| fname | java.lang.String | Pad naar het te maken bestand. |
| slides | int[] | Array met slide-posities, beginnend bij 1. |
| format | int | Formaat van de geëxporteerde gegevens. |
| options | [ISaveOptions](../../com.aspose.slides/isaveoptions) | Extra opmaakopties. |

### save(OutputStream stream, int[] slides, int format) {#save-java.io.OutputStream-int---int-}
```
public final void save(OutputStream stream, int[] slides, int format)
```


Slaat de opgegeven slides van een presentatie op in een stream met het opgegeven formaat met behoud van paginanummering.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| stream | java.io.OutputStream | Uitvoerstroom. |
| slides | int[] | Array met slide-posities, beginnend bij 1. |
| format | int | Formaat van de geëxporteerde gegevens. |

### save(OutputStream stream, int[] slides, int format, ISaveOptions options) {#save-java.io.OutputStream-int---int-com.aspose.slides.ISaveOptions-}
```
public final void save(OutputStream stream, int[] slides, int format, ISaveOptions options)
```


Slaat de opgegeven slides van een presentatie op in een stream met het opgegeven formaat met behoud van paginanummering.

--------------------

> ```
> Het volgende voorbeeld laat zien hoe je PowerPoint naar PNG converteert.
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      for (int index = 0; index < pres.getSlides().size(); index++) {
>          ISlide slide = pres.getSlides().get_Item(index);
>          ImageIO.write(slide.getThumbnail(), "PNG", new java.io.File("slide_" + index + ".png"));
>      }
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  Het volgende voorbeeld laat zien hoe je PowerPoint naar PNG converteert met aangepaste dimensies.
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      float scaleX = 2f;
>      float scaleY = 2f;
>      for (int index = 0; index < pres.getSlides().size(); index++) {
>          ISlide slide = pres.getSlides().get_Item(index);
>          ImageIO.write(slide.getThumbnail(scaleX, scaleY), "PNG", new java.io.File("slide_" + index + ".png"));
>      }
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  Het volgende voorbeeld laat zien hoe je PowerPoint naar PNG converteert met aangepaste grootte.
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      Dimension size = new Dimension(960, 720);
>      for (int index = 0; index < pres.getSlides().size(); index++) {
>          ISlide slide = pres.getSlides().get_Item(index);
>          ImageIO.write(slide.getThumbnail(size), "PNG", new java.io.File("slide_" + index + ".png"));
>      }
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| stream | java.io.OutputStream | Uitvoerstroom. |
| slides | int[] | Array met slide-posities, beginnend bij 1. |
| format | int | Formaat van de geëxporteerde gegevens. |
| options | [ISaveOptions](../../com.aspose.slides/isaveoptions) | Extra opmaakopties. |

### joinPortionsWithSameFormatting() {#joinPortionsWithSameFormatting--}
```
public final void joinPortionsWithSameFormatting()
```


Voegt runs met dezelfde opmaak samen in alle alinea’s in alle aanvaardbare shapes in alle slides.

### dispose() {#dispose--}
```
public final void dispose()
```


Vrijgeeft alle bronnen die door dit Presentation-object worden gebruikt.

### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```


Retourneert de bovenliggende presentatie van een tekst. Alleen-lezen [IPresentation](../../com.aspose.slides/ipresentation).

**Retourneert:**
[IPresentation](../../com.aspose.slides/ipresentation)
### highlightText(String text, Color highlightColor) {#highlightText-java.lang.String-java.awt.Color-}
```
public final void highlightText(String text, Color highlightColor)
```


Markeert alle overeenkomsten van de voorbeeldtekst met de opgegeven kleur.

--------------------

> ```
> The following code sample shows how to highlight text in a PowerPoint presentation.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      // markeert alle afzonderlijke 'the' vermeldingen
>      presentation.highlightText("the", Color.MAGENTA);
>      presentation.save("SomePresentation-out2.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| text | java.lang.String | De te markeren tekst. |
| highlightColor | java.awt.Color | De kleur om de tekst te markeren. |

### highlightText(String text, Color highlightColor, ITextSearchOptions options, IFindResultCallback callback) {#highlightText-java.lang.String-java.awt.Color-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-}
```
public final void highlightText(String text, Color highlightColor, ITextSearchOptions options, IFindResultCallback callback)
```


Markeert alle overeenkomsten van de voorbeeldtekst met de opgegeven kleur.

--------------------

> ```
> The following code sample shows how to highlight text in a PowerPoint presentation.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      TextSearchOptions textSearchOptions = new TextSearchOptions();
>      textSearchOptions.setWholeWordsOnly(true);
>      // markeert alle afzonderlijke 'the' vermeldingen
>      presentation.highlightText("the", Color.MAGENTA, textSearchOptions, null);
>      presentation.save("SomePresentation-out2.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| text | java.lang.String | De te markeren tekst. |
| highlightColor | java.awt.Color | De kleur om de tekst te markeren. |
| options | [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions) | Tekst-zoekopties [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions). |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | Het callback-object voor het ontvangen van zoekresultaten [IFindResultCallback](../../com.aspose.slides/ifindresultcallback). |

### highlightRegex(Pattern regex, Color highlightColor, IFindResultCallback callback) {#highlightRegex-java.util.regex.Pattern-java.awt.Color-com.aspose.slides.IFindResultCallback-}
```
public final void highlightRegex(Pattern regex, Color highlightColor, IFindResultCallback callback)
```


Markeert alle overeenkomsten van de reguliere expressie met de opgegeven kleur.

--------------------

> ```
> The following code sample shows how to highlight text in a PowerPoint Presentation using a regular expression.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      Pattern regex = Pattern.compile("\\b[^\\s]{10,}\\b");
>      // markeren van alle woorden met 10 tekens of langer
>      presentation.highlightRegex(regex, Color.BLUE, null);
>      presentation.save("SomePresentation-out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |

| regex | java.util.regex.Pattern | De reguliere expressie java.util.regex.Pattern om tekenreeksen te markeren. |
| highlightColor | java.awt.Color | De kleur om de tekst te markeren. |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | Het callback-object voor het ontvangen van zoekresultaten [IFindResultCallback](../../com.aspose.slides/ifindresultcallback). |

### replaceText(String oldText, String newText, ITextSearchOptions options, IFindResultCallback callback) {#replaceText-java.lang.String-java.lang.String-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-}
```
public final void replaceText(String oldText, String newText, ITextSearchOptions options, IFindResultCallback callback)
```


Vervangt alle voorkomens van de opgegeven tekst door een andere opgegeven tekst.

--------------------

> ```
> The following sample code shows how to replace one specified string with another specified string.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx")
>  try {
>      TextSearchOptions textSearchOptions = new TextSearchOptions();
>      textSearchOptions.setWholeWordsOnly(true);
>      // Vervang alle afzonderlijke 'the' vermeldingen door '***'
>      presentation.replaceText("the", "***", textSearchOptions, null);
>      presentation.save("SomePresentation-out2.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| oldText | java.lang.String | De tekenreeks die vervangen moet worden. |
| newText | java.lang.String | De tekenreeks om alle voorkomens van oldText te vervangen. |
| options | [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions) | Tekstzoekopties [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions). |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | Het callback-object voor het ontvangen van zoekresultaten [IFindResultCallback](../../com.aspose.slides/ifindresultcallback). |

### replaceRegex(Pattern regex, String newText, IFindResultCallback callback) {#replaceRegex-java.util.regex.Pattern-java.lang.String-com.aspose.slides.IFindResultCallback-}
```
public final void replaceRegex(Pattern regex, String newText, IFindResultCallback callback)
```


Vervangt alle overeenkomsten van de reguliere expressie door de opgegeven tekenreeks.

--------------------

> ```
> The following code sample shows how to replace text using regular expression with the specified string.
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      Pattern regex = Pattern.compile("\\b[^\\s]{10,}\\b");
>      // Replace all words with 10 symbols or longer with '***'
>      presentation.replaceRegex(regex, "***", null);
>      presentation.save("SomePresentation-out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| regex | java.util.regex.Pattern | De reguliere expressie java.util.regex.Pattern om tekenreeksen te vervangen. |
| newText | java.lang.String | De tekenreeks om alle voorkomens van de te vervangen tekenreeksen te vervangen. |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | Het callback-object voor het ontvangen van zoekresultaten [IFindResultCallback](../../com.aspose.slides/ifindresultcallback). |

### refreshChartsData() {#refreshChartsData--}
```
public final void refreshChartsData()
```


Laadt de gegevens voor alle grafieken in de presentatie opnieuw vanuit hun bronwerkboeken.

--------------------

> ```
> Presentation presentation = new Presentation("PresentationWithCharts.pptx");
>  try {
>      presentation.refreshChartsData();
>      presentation.save("PresentationWithCharts-out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


### refreshChartsData(boolean skipFailedCharts) {#refreshChartsData-boolean-}
```
public final void refreshChartsData(boolean skipFailedCharts)
```


Laadt de gegevens voor alle grafieken in de presentatie opnieuw vanuit hun bronwerkboeken.

--------------------

> ```
> Presentation presentation = new Presentation("PresentationWithCharts.pptx");
>  try {
>      presentation.refreshChartsData();
>      presentation.save("PresentationWithCharts-out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| skipFailedCharts | boolean | Bepaalt of het vernieuwingsproces doorgaat als een grafiek niet kan worden bijgewerkt. Indien true worden grafieken die een uitzondering veroorzaken overgeslagen; anders wordt de uitzondering doorgegeven. |