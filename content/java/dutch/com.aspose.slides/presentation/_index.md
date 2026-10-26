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
>      // Voeg een autoshape van het type lijn toe
>      slide.getShapes().addAutoShape(ShapeType.Line, 50, 150, 300, 0);
>      // Sla het presentatiebestand op.
>      pres.save("NewPresentation_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>   
>   The following example shows how to open and save Presentation.
>   
>  // Laad een ondersteund bestand in Presentation, bijv. ppt, pptx, odp enz.
>  Presentation pres = new Presentation("Sample.odp");
>  try {
>      // Sla het presentatiebestand op.
>      pres.save("OutputPresenation.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

## Constructeurs

| Constructor | Beschrijving |
| --- | --- |
| [Presentation()](#Presentation--) | Deze constructor maakt een nieuwe presentatie vanaf nul. |
| [Presentation(LoadOptions loadOptions)](#Presentation-com.aspose.slides.LoadOptions-) | Deze constructor maakt een nieuwe presentatie vanaf nul. |
| [Presentation(InputStream stream)](#Presentation-java.io.InputStream-) | Deze constructor is de primaire methode om een bestaande presentatie te lezen. |
| [Presentation(InputStream stream, LoadOptions loadOptions)](#Presentation-java.io.InputStream-com.aspose.slides.LoadOptions-) | Deze constructor is de primaire methode om een bestaande presentatie te lezen. |
| [Presentation(String file)](#Presentation-java.lang.String-) | Deze constructor krijgt een bronbestandspad waarvan de inhoud van de presentatie wordt gelezen. |
| [Presentation(String file, LoadOptions loadOptions)](#Presentation-java.lang.String-com.aspose.slides.LoadOptions-) | Deze constructor krijgt een bronbestandspad waarvan de inhoud van de presentatie wordt gelezen. |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getCurrentDateTime()](#getCurrentDateTime--) | Retourneert of stelt de datum en tijd in die de inhoud van datum-tijdvelden zal vervangen. |
| [setCurrentDateTime(Date value)](#setCurrentDateTime-java.util.Date-) | Retourneert of stelt de datum en tijd in die de inhoud van datum-tijdvelden zal vervangen. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | Retourneert de actuele HeaderFooter-manager. |
| [getProtectionManager()](#getProtectionManager--) | Haalt de manager van de machtigingen voor deze presentatie. |
| [getSlides()](#getSlides--) | Retourneert een lijst van alle dia's die in de presentatie zijn gedefinieerd. |
| [getSections()](#getSections--) | Retourneert een lijst van alle dia-secties die in de presentatie zijn gedefinieerd. |
| [getSlideSize()](#getSlideSize--) | Retourneert een dia-groottobject. |
| [getNotesSize()](#getNotesSize--) | Retourneert een notities-dia-groottobject. |
| [getLayoutSlides()](#getLayoutSlides--) | Retourneert een lijst van alle lay-outdia's die in de presentatie zijn gedefinieerd. |
| [getMasters()](#getMasters--) | Retourneert een lijst van alle masterdia's die in de presentatie zijn gedefinieerd. |
| [getMasterNotesSlideManager()](#getMasterNotesSlideManager--) | Retourneert notities-master-manager. |
| [getMasterHandoutSlideManager()](#getMasterHandoutSlideManager--) | Retourneert handout-master-manager. |
| [getFontsManager()](#getFontsManager--) | Retourneert lettertype-manager. |
| [getDefaultTextStyle()](#getDefaultTextStyle--) | Retourneert standaardtekstopmaak voor vormen. |
| [getCommentAuthors()](#getCommentAuthors--) | Retourneert de collectie van commentaarauteurs. |
| [getDocumentProperties()](#getDocumentProperties--) | Retourneert een DocumentProperties-object dat standaard- en aangepaste documenteigenschappen bevat. |
| [getImages()](#getImages--) | Retourneert de collectie van alle afbeeldingen in de presentatie. |
| [getAudios()](#getAudios--) | Retourneert de collectie van alle ingebedde audiobestanden in de presentatie. |
| [getVideos()](#getVideos--) | Retourneert de collectie van alle ingebedde videobestanden in de presentatie. |
| [getSlideShowSettings()](#getSlideShowSettings--) | Retourneert de diavoorstelling-instellingen voor de presentatie. |
| [getDigitalSignatures()](#getDigitalSignatures--) | Retourneert de collectie van handtekeningen die worden gebruikt om de presentatie te ondertekenen. |
| [getCustomData()](#getCustomData--) | Retourneert de aangepaste gegevens van de presentatie. |
| [getAllCustomXmlParts()](#getAllCustomXmlParts--) | Retourneert alle aangepaste gegevensonderdelen in de presentatie. |
| [getVbaProject()](#getVbaProject--) | Haalt of stelt het VBA-project met presentatiemacro's in. |
| [setVbaProject(IVbaProject value)](#setVbaProject-com.aspose.slides.IVbaProject-) | Haalt of stelt het VBA-project met presentatiemacro's in. |
| [getHyperlinkQueries()](#getHyperlinkQueries--) | Biedt gemakkelijke toegang tot alle koppelingen die in alle presentatiedia's staan (niet in master-, lay-out- of notitiesdia's). |
| [getViewProperties()](#getViewProperties--) | Haalt weergave-eigenschappen voor de hele presentatie. |
| [getFirstSlideNumber()](#getFirstSlideNumber--) | Stelt het eerste dia-nummer in de presentatie voor. |
| [setFirstSlideNumber(int value)](#setFirstSlideNumber-int-) | Stelt het eerste dia-nummer in de presentatie voor. |
| [getSensitivityLabels()](#getSensitivityLabels--) | Retourneert de collectie van gevoeligheidslabels die op het presentatiedocument zijn toegepast. |
| [getSlideById(long id)](#getSlideById-long-) | Retourneert een Slide, MasterSlide of LayoutSlide op basis van Id. |
| [getSourceFormat()](#getSourceFormat--) | Retourneert informatie over het formaat waarvan de presentatie is geladen. |
| [getMasterTheme()](#getMasterTheme--) | Retourneert het master-thema. |
| [save(String fname, int format)](#save-java.lang.String-int-) | Slaat alle dia's van een presentatie op in een bestand met het opgegeven formaat. |
| [save(OutputStream stream, int format)](#save-java.io.OutputStream-int-) | Slaat alle dia's van een presentatie op in een stream in het opgegeven formaat. |
| [save(String fname, int format, ISaveOptions options)](#save-java.lang.String-int-com.aspose.slides.ISaveOptions-) | Slaat alle dia's van een presentatie op in een bestand met het opgegeven formaat en met extra opties. |
| [save(OutputStream stream, int format, ISaveOptions options)](#save-java.io.OutputStream-int-com.aspose.slides.ISaveOptions-) | Slaat alle dia's van een presentatie op in een stream in het opgegeven formaat en met extra opties. |
| [save(IXamlOptions options)](#save-com.aspose.slides.IXamlOptions-) | Slaat alle dia's van een presentatie op in een reeks bestanden die XAML-markup vertegenwoordigen. |
| [getImages(IRenderingOptions options)](#getImages-com.aspose.slides.IRenderingOptions-) | Retourneert Image-objecten voor alle dia's van een presentatie. |
| [getImages(IRenderingOptions options, int[] slides)](#getImages-com.aspose.slides.IRenderingOptions-int---) | Retourneert thumbnail-Image-objecten voor opgegeven dia's van een presentatie. |
| [getImages(IRenderingOptions options, float scaleX, float scaleY)](#getImages-com.aspose.slides.IRenderingOptions-float-float-) | Retourneert thumbnail-Image-objecten voor alle dia's van een presentatie met aangepaste schaal. |
| [getImages(IRenderingOptions options, int[] slides, float scaleX, float scaleY)](#getImages-com.aspose.slides.IRenderingOptions-int---float-float-) | Retourneert thumbnail-Image-objecten voor opgegeven dia's van een presentatie met aangepaste schaal. |
| [getImages(IRenderingOptions options, Dimension imageSize)](#getImages-com.aspose.slides.IRenderingOptions-java.awt.Dimension-) | Retourneert thumbnail-Image-objecten voor alle dia's van een presentatie met opgegeven grootte. |
| [getImages(IRenderingOptions options, int[] slides, Dimension imageSize)](#getImages-com.aspose.slides.IRenderingOptions-int---java.awt.Dimension-) | Retourneert thumbnail-Image-objecten voor opgegeven dia's van een presentatie met opgegeven grootte. |
| [save(String fname, int[] slides, int format)](#save-java.lang.String-int---int-) | Slaat opgegeven dia's van een presentatie op in een bestand met het opgegeven formaat met paginanummerbehoud. |
| [save(String fname, int[] slides, int format, ISaveOptions options)](#save-java.lang.String-int---int-com.aspose.slides.ISaveOptions-) | Slaat opgegeven dia's van een presentatie op in een bestand met het opgegeven formaat met paginanummerbehoud. |
| [save(OutputStream stream, int[] slides, int format)](#save-java.io.OutputStream-int---int-) | Slaat opgegeven dia's van een presentatie op in een stream in het opgegeven formaat met paginanummerbehoud. |
| [save(OutputStream stream, int[] slides, int format, ISaveOptions options)](#save-java.io.OutputStream-int---int-com.aspose.slides.ISaveOptions-) | Slaat opgegeven dia's van een presentatie op in een stream in het opgegeven formaat met paginanummerbehoud. |
| [joinPortionsWithSameFormatting()](#joinPortionsWithSameFormatting--) | Voegt runs met dezelfde opmaak samen in alle alinea's in alle toegestane vormen in alle dia's. |
| [dispose()](#dispose--) | Geeft alle bronnen vrij die door dit Presentation-object worden gebruikt. |
| [getPresentation()](#getPresentation--) | Retourneert de bovenliggende presentatie van een tekst. |
| [highlightText(String text, Color highlightColor)](#highlightText-java.lang.String-java.awt.Color-) | Markeert alle overeenkomsten van de voorbeeldtekst met de opgegeven kleur. |
| [highlightText(String text, Color highlightColor, ITextSearchOptions options, IFindResultCallback callback)](#highlightText-java.lang.String-java.awt.Color-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-) | Markeert alle overeenkomsten van de voorbeeldtekst met de opgegeven kleur. |
| [highlightRegex(Pattern regex, Color highlightColor, IFindResultCallback callback)](#highlightRegex-java.util.regex.Pattern-java.awt.Color-com.aspose.slides.IFindResultCallback-) | Markeert alle overeenkomsten van de reguliere expressie met de opgegeven kleur. |
| [replaceText(String oldText, String newText, ITextSearchOptions options, IFindResultCallback callback)](#replaceText-java.lang.String-java.lang.String-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-) | Vervangt alle voorkomens van de opgegeven tekst door een andere opgegeven tekst. |
| [replaceRegex(Pattern regex, String newText, IFindResultCallback callback)](#replaceRegex-java.util.regex.Pattern-java.lang.String-com.aspose.slides.IFindResultCallback-) | Vervangt alle overeenkomsten van de reguliere expressie door de opgegeven tekenreeks. |

### Presentation() {#Presentation--}
```
public Presentation()
```

Deze constructor maakt een nieuwe presentatie vanaf nul. De gemaakte presentatie heeft één lege dia.

### Presentation(LoadOptions loadOptions) {#Presentation-com.aspose.slides.LoadOptions-}
```
public Presentation(LoadOptions loadOptions)
```

Deze constructor maakt een nieuwe presentatie vanaf nul. De gemaakte presentatie heeft één lege dia.

**Parameters:**  
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| loadOptions | [LoadOptions](../../com.aspose.slides/loadoptions) | Extra laadopties. |

### Presentation(InputStream stream) {#Presentation-java.io.InputStream-}
```
public Presentation(InputStream stream)
```

Deze constructor is de primaire methode om een bestaande presentatie te lezen.

--------------------

> ```
> FileInputStream fis = new FileInputStream("demo.pptx");
>  Presentation pres = new Presentation(fis);
>  fis.close();
> ```


**Parameters:**  
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| stream | java.io.InputStream | Invoerstroom. |

### Presentation(InputStream stream, LoadOptions loadOptions) {#Presentation-java.io.InputStream-com.aspose.slides.LoadOptions-}
```
public Presentation(InputStream stream, LoadOptions loadOptions)
```

Deze constructor is de primaire methode om een bestaande presentatie te lezen.

**Parameters:**  
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| stream | java.io.InputStream | Invoerstroom. |
| loadOptions | [LoadOptions](../../com.aspose.slides/loadoptions) | Extra laadopties. |

### Presentation(String file) {#Presentation-java.lang.String-}
```
public Presentation(String file)
```

Deze constructor krijgt een bronbestandspad waarvan de inhoud van de presentatie wordt gelezen.

--------------------

> ```
> Presentation pres = new Presentation("demo.pptx");
```

**Parameters:**  
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| file | java.lang.String | Invoebestand. |

### Presentation(String file, LoadOptions loadOptions) {#Presentation-java.lang.String-com.aspose.slides.LoadOptions-}
```
public Presentation(String file, LoadOptions loadOptions)
```

Deze constructor krijgt een bronbestandspad waarvan de inhoud van de presentatie wordt gelezen.

**Parameters:**  
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| file | java.lang.String | Invoebestand. |
| loadOptions | [LoadOptions](../../com.aspose.slides/loadoptions) | Extra laadopties. |

### getCurrentDateTime() {#getCurrentDateTime--}
```
public final Date getCurrentDateTime()
```

Retourneert of stelt de datum en tijd in die de inhoud van datum-tijdvelden zal vervangen. Tijd van creatie van dit Presentation-object als standaard. Lezen/Schrijven java.util.Date.

**Retourneert:**  
java.util.Date

### setCurrentDateTime(Date value) {#setCurrentDateTime-java.util.Date-}
```
public final void setCurrentDateTime(Date value)
```

Retourneert of stelt de datum en tijd in die de inhoud van datum-tijdvelden zal vervangen. Tijd van creatie van dit Presentation-object als standaard. Lezen/Schrijven java.util.Date.

**Parameters:**  
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | java.util.Date |  |

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Retourneert Parent_Immediate-object. Alleen-lezen IDOMObject.

**Retourneert:**  
com.aspose.slides.IDOMObject

### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public final IPresentationHeaderFooterManager getHeaderFooterManager()
```

Retourneert de actuele HeaderFooter-manager. Alleen-lezen [IPresentationHeaderFooterManager](../../com.aspose.slides/ipresentationheaderfootermanager).

--------------------

> ```
> The following example shows how to set footer visibility inside Slide of PowerPoint Presentation.
>  
>  Presentation pres = new Presentation("presentation.ppt");
>  try
>  {
>      IBaseSlideHeaderFooterManager headerFooterManager = pres.getSlides().get_Item(0).getHeaderFooterManager();
>      if (!headerFooterManager.isFooterVisible()) // Property IsFooterVisible wordt gebruikt om aan te geven dat een slide-voetnoot-placeholder niet aanwezig is.
>      {
>          headerFooterManager.setFooterVisibility(true); // Methode SetFooterVisibility wordt gebruikt om een slide-voetnoot-placeholder zichtbaar te maken.
>      }
>      if (!headerFooterManager.isSlideNumberVisible()) // Property IsSlideNumberVisible wordt gebruikt om aan te geven dat een slide-paginanummer-placeholder niet aanwezig is.
>      {
>          headerFooterManager.setSlideNumberVisibility(true); // Methode SetSlideNumberVisibility wordt gebruikt om een slide-paginanummer-placeholder zichtbaar te maken.
>      }
>      if (!headerFooterManager.isDateTimeVisible()) // Property IsDateTimeVisible wordt gebruikt om aan te geven dat een slide-datum-tijd-placeholder niet aanwezig is.
>      {
>          headerFooterManager.setDateTimeVisibility(true); // Methode SetFooterVisibility wordt gebruikt om een slide-datum-tijd-placeholder zichtbaar te maken.
>      }
>      headerFooterManager.setFooterText("Footer text"); // Methode SetFooterText wordt gebruikt om tekst in te stellen voor de slide-voetnoot-placeholder.
>      headerFooterManager.setDateTimeText("Date and time text"); // Methode SetDateTimeText wordt gebruikt om tekst in te stellen voor de slide-datum-tijd-placeholder.
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
>      headerFooterManager.setFooterAndChildFootersVisibility(true); // Methode SetFooterAndChildFootersVisibility wordt gebruikt om een master-slide en alle onderliggende voetnoot-placeholders zichtbaar te maken.
>      headerFooterManager.setSlideNumberAndChildSlideNumbersVisibility(true); // Methode SetSlideNumberAndChildSlideNumbersVisibility wordt gebruikt om een master-slide en alle onderliggende paginanummer-placeholders zichtbaar te maken.
>      headerFooterManager.setDateTimeAndChildDateTimesVisibility(true); // Methode SetDateTimeAndChildDateTimesVisibility wordt gebruikt om een master-slide en alle onderliggende datum-tijd-placeholders zichtbaar te maken.
> 
>      headerFooterManager.setFooterAndChildFootersText("Footer text"); // Methode SetFooterAndChildFootersText wordt gebruikt om tekst in te stellen voor de master-slide en alle onderliggende voetnoot-placeholders.
>      headerFooterManager.setDateTimeAndChildDateTimesText("Date and time text"); // Methode SetDateTimeAndChildDateTimesText wordt gebruikt om tekst in te stellen voor de master-slide en alle onderliggende datum-tijd-placeholders.
>  }
>  finally
>  {
>      if (pres != null) pres.dispose();
>  }
> ```


**Retourneert:**  
[IPresentationHeaderFooterManager](../../com.aspose.slides/ipresentationheaderfootermanager)

### getProtectionManager() {#getProtectionManager--}
```
public final IProtectionManager getProtectionManager()
```

Haalt manager van de machtigingen voor deze presentatie. Alleen-lezen [IProtectionManager](../../com.aspose.slides/iprotectionmanager).

**Retourneert:**  
[IProtectionManager](../../com.aspose.slides/iprotectionmanager)

### getSlides() {#getSlides--}
```
public final ISlideCollection getSlides()
```

Retourneert een lijst van alle dia's die in de presentatie zijn gedefinieerd. Alleen-lezen [ISlideCollection](../../com.aspose.slides/islidecollection).

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
>      // Stel de achtergrond in met een afbeelding
>      pres.getSlides().get_Item(0).getBackground().setType(BackgroundType.OwnBackground);
>      pres.getSlides().get_Item(0).getBackground().getFillFormat().setFillType(FillType.Picture);
>      pres.getSlides().get_Item(0).getBackground().getFillFormat().getPictureFillFormat().setPictureFillMode(PictureFillMode.Stretch);
>      // Stel de afbeelding in
>      BufferedImage img = ImageIO.read(new File("Tulips.jpg"));
>      // Voeg afbeelding toe aan de afbeeldingencollectie van de presentatie
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
>  // Instantieer Presentation-klasse om het bronpresentatiebestand te laden
>  Presentation pres = new Presentation("AccessSlides.pptx");
>  try
>  {
>      // Pas een cirkeltype overgang toe op dia 1
>      pres.getSlides().get_Item(0).getSlideShowTransition().setType(TransitionType.Circle);
>      // Pas een kamtype overgang toe op dia 2
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
>  // Instantieer Presentation-klasse die een presentatiebestand vertegenwoordigt
>  Presentation pres = new Presentation("BetterSlideTransitions.pptx");
>  try
>  {
>      // Pas een cirkeltype overgang toe op dia 1
>      pres.getSlides().get_Item(0).getSlideShowTransition().setType(TransitionType.Circle);
>      // Stel de overgangstijd in op 3 seconden
>      pres.getSlides().get_Item(0).getSlideShowTransition().setAdvanceOnClick(true);
>      pres.getSlides().get_Item(0).getSlideShowTransition().setAdvanceAfterTime(3000);
>      // Pas een kamtype overgang toe op dia 2
>      pres.getSlides().get_Item(1).getSlideShowTransition().setType(TransitionType.Comb);
>      // Stel de overgangstijd in op 5 seconden
>      pres.getSlides().get_Item(1).getSlideShowTransition().setAdvanceOnClick(true);
>      pres.getSlides().get_Item(1).getSlideShowTransition().setAdvanceAfterTime(5000);
>      // Pas een zoomtype overgang toe op dia 3
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


**Retourneert:**  
[ISlideCollection](../../com.aspose.slides/islidecollection)

### getSections() {#getSections--}
```
public final ISectionCollection getSections()
```

Retourneert een lijst van alle dia-secties die in de presentatie zijn gedefinieerd. Alleen-lezen [ISectionCollection](../../com.aspose.slides/isectioncollection).

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
>      // section1 zal eindigen bij newSlide2 en daarna start section2
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


**Retourneert:**  
[ISectionCollection](../../com.aspose.slides/isectioncollection)

### getSlideSize() {#getSlideSize--}
```
public final ISlideSize getSlideSize()
```

Retourneert dia-groottobject. Alleen-lezen [ISlideSize](../../com.aspose.slides/islidesize).

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
>  // Instantiate a Presentation object that represents a presentation file
>  Presentation presentation = new Presentation("AccessSlides.pptx");
>  try {
>      Presentation auxPresentation = new Presentation();
>      try {
>          ISlide slide = presentation.getSlides().get_Item(0);
>          // Set the slide size of generated presentations to that of source
>          presentation.getSlideSize().setSize(540, 720, SlideSizeScaleType.EnsureFit); // Method SetSize is used for set slide size with scale content to ensure fit
>          presentation.getSlideSize().setSize(SlideSizeType.A4Paper, SlideSizeScaleType.Maximize); // Method SetSize is used for set slide size with maximize size of content
>          // Save Presentation to disk
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
>      pres.getSlideSize().setSize(780, 540, SlideSizeScaleType.DoNotScale); // A4 paper size
>      pres.save("pres-a4-slide-size.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Retourneert:**  
[ISlideSize](../../com.aspose.slides/islidesize)

### getNotesSize() {#getNotesSize--}
```
public final INotesSize getNotesSize()
```

Retourneert notities-dia-groottobject. Alleen-lezen [INotesSize](../../com.aspose.slides/inotessize).

**Retourneert:**  
[INotesSize](../../com.aspose.slides/inotessize)

### getLayoutSlides() {#getLayoutSlides--}
```
public final IGlobalLayoutSlideCollection getLayoutSlides()
```

Retourneert een lijst van alle lay-outdia's die in de presentatie zijn gedefinieerd. Alleen-lezen [IGlobalLayoutSlideCollection](../../com.aspose.slides/igloballayoutslidecollection).

--------------------

U kunt alternatieve API’s gebruiken om lay-outdia's toe te voegen/in te voegen/verwijderen/kopiëren via de eigenschap IMasterSlide.LayoutSlides.

**Retourneert:**  
[IGlobalLayoutSlideCollection](../../com.aspose.slides/igloballayoutslidecollection)

### getMasters() {#getMasters--}
```
public final IMasterSlideCollection getMasters()
```

Retourneert een lijst van alle masterdia's die in de presentatie zijn gedefinieerd. Alleen-lezen [IMasterSlideCollection](../../com.aspose.slides/imasterslidecollection).

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
>  // Instantieer de Presentation-klasse die het presentiebestand vertegenwoordigt
>  Presentation pres = new Presentation();
>  try
>  {
>      // Stel de achtergrondkleur van de Master ISlide in op Bosgroen
>      pres.getMasters().get_Item(0).getBackground().setType(BackgroundType.OwnBackground);
>      pres.getMasters().get_Item(0).getBackground().getFillFormat().setFillType(FillType.Solid);
>      pres.getMasters().get_Item(0).getBackground().getFillFormat().getSolidFillColor().setColor(Color.GREEN);
>      // Schrijf de presentatie naar schijf
>      pres.save("SetSlideBackgroundMaster_out.pptx", SaveFormat.Pptx);
>  }
>  finally
>  {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following examples shows how to add slide layout to PowerPoint Presentation.
>  
>  // Instantieer de Presentation-klasse die een presentiebestand vertegenwoordigt
>  Presentation presentation = new Presentation("AccessSlides.pptx");
>  try
>  {
>      // Probeer te zoeken op lay-out-dia type
>      IMasterLayoutSlideCollection layoutSlides = presentation.getMasters().get_Item(0).getLayoutSlides();
>      ILayoutSlide layoutSlide = null;
>      if (layoutSlides.getByType(SlideLayoutType.TitleAndObject) != null)
>          layoutSlide = layoutSlides.getByType(SlideLayoutType.TitleAndObject);
>      else
>          layoutSlide = layoutSlides.getByType(SlideLayoutType.Title);
> 
>      if (layoutSlide == null)
>      {
>          // De situatie wanneer een presentatie niet enkele type lay-outs bevat.
>          // Presentatiebestand bevat alleen lege en aangepaste lay-outtypen.
>          // Maar lay-outdia's met aangepaste typen hebben verschillende dia-namen,
>          // zoals "Title", "Title and Content", etc. En het is mogelijk deze te gebruiken
>          // voor lay-out-diaselectie.
>          // Ook is het mogelijk om de set van placeholder-vormtypen te gebruiken. Bijvoorbeeld,
>          // Titel-dia moet alleen het Title-placeholder type hebben, etc.
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
>      // Voeg lege dia toe met toegevoegde lay-outdia
>      presentation.getSlides().insertEmptySlide(0, layoutSlide);
>      // Sla presentatie op
>      presentation.save("AddLayoutSlides_out.pptx", SaveFormat.Pptx);
>  }
>  finally
>  {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Retourneert:**  
[IMasterSlideCollection](../../com.aspose.slides/imasterslidecollection)

### getMasterNotesSlideManager() {#getMasterNotesSlideManager--}
```
public final IMasterNotesSlideManager getMasterNotesSlideManager()
```

Retourneert notities-master-manager. Alleen-lezen [IMasterNotesSlideManager](../../com.aspose.slides/imasternotesslidemanager).

**Retourneert:**  
[IMasterNotesSlideManager](../../com.aspose.slides/imasternotesslidemanager)

### getMasterHandoutSlideManager() {#getMasterHandoutSlideManager--}
```
public final IMasterHandoutSlideManager getMasterHandoutSlideManager()
```

Retourneert handout-master-manager. Alleen-lezen [IMasterHandoutSlideManager](../../com.aspose.slides/imasterhandoutslidemanager).

**Retourneert:**  
[IMasterHandoutSlideManager](../../com.aspose.slides/imasterhandoutslidemanager)

### getFontsManager() {#getFontsManager--}
```
public final IFontsManager getFontsManager()
```

Retourneert lettertype-manager. Alleen-lezen [IFontsManager](../../com.aspose.slides/ifontsmanager).

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


**Retourneert:**  
[IFontsManager](../../com.aspose.slides/ifontsmanager)

### getDefaultTextStyle() {#getDefaultTextStyle--}
```
public final ITextStyle getDefaultTextStyle()
```

Retourneert standaardtekstopmaak voor vormen. Alleen-lezen [ITextStyle](../../com.aspose.slides/itextstyle).

**Retourneert:**  
[ITextStyle](../../com.aspose.slides/itextstyle)

### getCommentAuthors() {#getCommentAuthors--}
```
public final ICommentAuthorCollection getCommentAuthors()
```

Retourneert de collectie van commentaarauteurs. Alleen-lezen [ICommentAuthorCollection](../../com.aspose.slides/icommentauthorcollection).

**Retourneert:**  
[ICommentAuthorCollection](../../com.aspose.slides/icommentauthorcollection)

### getDocumentProperties() {#getDocumentProperties--}
```
public final IDocumentProperties getDocumentProperties()
```

Retourneert een DocumentProperties-object dat standaard- en aangepaste documenteigenschappen bevat. Alleen-lezen [IDocumentProperties](../../com.aspose.slides/idocumentproperties).

**Retourneert:**  
[IDocumentProperties](../../com.aspose.slides/idocumentproperties)

### getImages() {#getImages--}
```
public final IImageCollection getImages()
```

Retourneert de collectie van alle afbeeldingen in de presentatie. Alleen-lezen [IImageCollection](../../com.aspose.slides/iimagecollection).

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
>          // Laten we de afbeelding aan de presentatie toevoegen - we kiezen KeepLocked-gedrag omdat we
>          // NIET van plan zijn het "largeImage.png" bestand te benaderen.
>          IPPImage img = pres.getImages().addImage(fip, LoadingStreamBehavior.KeepLocked);
>          pres.getSlides().get_Item(0).getShapes().addPictureFrame(ShapeType.Rectangle, 0, 0, 300, 200, img);
>          // Slaat de presentatie op. Terwijl een grote presentatie wordt geëxporteerd, blijft het geheugenverbruik
>          // laag gedurende de levensduur van het pres-object
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
>      // Voegt afbeelding toe aan de presentatie
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
[IImageCollection](../../com.aspose.slides/iimagecollection)

### getAudios() {#getAudios--}
```
public final IAudioCollection getAudios()
```

Retourneert de collectie van alle ingebedde audiobestanden in de presentatie. Alleen-lezen [IAudioCollection](../../com.aspose.slides/iaudiocollection).

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
Returns de collectie van alle ingesloten videobestanden in de presentatie. Alleen-lezen [IVideoCollection](../../com.aspose.slides/ivideocollection).

--------------------

> ```
> The following examples shows how to create embedded Video Frame in a PowerPoint Presentation.
>  
>  // Instantiate Presentation class that represents the PPTX
>  Presentation pres = new Presentation();
>  try {
>      // Get the first slide
>      ISlide sld = pres.getSlides().get_Item(0);
>      // Embedd vide inside presentation
>      IVideo vid = pres.getVideos().addVideo(new FileInputStream("Wildlife.mp4"));
>      // Add Video Frame
>      IVideoFrame vf = sld.getShapes().addVideoFrame(50, 150, 300, 350, vid);
>      // Set video to Video Frame
>      vf.setEmbeddedVideo(vid);
>      // Set Play Mode and Volume of the Video
>      vf.setPlayMode(VideoPlayModePreset.Auto);
>      vf.setVolume(AudioVolumeMode.Loud);
>      // Write the PPTX file to disk
>      pres.save("VideoFrame_out.pptx", SaveFormat.Pptx);
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following examples shows how to add a video passing path to the video file directly into AddVideoFrame method for PowerPoint Presentation.
>  
>  Presentation pres = new Presentation();
>  try {
>      ISlide sld = pres.getSlides().get_Item(0);
>      IVideoFrame vf = sld.getShapes().addVideoFrame(50, 150, 300, 150, "video1.avi");
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following examples shows how to add large file through BLOB to a Presentation.
>  
>  // Creates a new presentation to which the video will be added
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream fileStream = new FileInputStream("veryLargeVideo.avi");
>      try {
>          // Let's add the video to the presentation - we chose the KeepLocked behavior because we do
>          //not intend to access the "veryLargeVideo.avi" file.
>          IVideo video = pres.getVideos().addVideo(fileStream, LoadingStreamBehavior.KeepLocked);
>          pres.getSlides().get_Item(0).getShapes().addVideoFrame(0, 0, 480, 270, video);
>          // Saves the presentation. While a large presentation gets outputted, the memory consumption
>          // stays low through the pres object's lifecycle
>          pres.save("presentationWithLargeVideo.pptx", SaveFormat.Pptx);
>      } finally {
>          if (fileStream != null) fileStream.close();
>      }
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following examples shows how to export large file through BLOB from PowerPoint Presentation.
>  
>  LoadOptions loadOptions = new LoadOptions();
>  // Locks the source file and does NOT load it into memory
>  loadOptions.getBlobManagementOptions().setPresentationLockingBehavior(PresentationLockingBehavior.KeepLocked);
>  // Creates a Presentation's instance, locks the "hugePresentationWithAudiosAndVideos.pptx" file.
>  Presentation pres = new Presentation("Large  Video File Test1.pptx", loadOptions);
>  try {
>      // Let's save each video to a file. To prevent high memory usage, we need a buffer that will be used
>      // to transfer the data from the presentation's video stream to a stream for a newly created video file.
>      byte[] buffer = new byte[81024];
>      // Iterates through the videos
>      for (int index = 0; index < pres.getVideos().size(); index++) {
>          IVideo video = pres.getVideos().get_Item(index);
>          // Opens the presentation video stream. Please, note that we intentionally avoided accessing properties
>          // like video.BinaryData - because this property returns a byte array containing a full video, which then
>          // causes bytes to be loaded into memory. We use video.GetStream, which will return Stream - and does NOT
>          //  require us to load the whole video into the memory.
>          InputStream presVideoStream = video.getStream();
>          try {
>              FileOutputStream outputFileStream = new FileOutputStream("video{index}.avi");
>              try {
>                  int bytesRead;
>                  while ((bytesRead = presVideoStream.read(buffer, 0, buffer.length)) > 0) {
>                      outputFileStream.write(buffer, 0, bytesRead);
>                  }
>              } finally {
>                  if (outputFileStream != null) outputFileStream.close();
>              }
>          } finally {
>              if (presVideoStream != null) presVideoStream.close();
>          }
>          // Memory consumption will remain low regardless of the size of the video or presentation,
>      }
>      // If necessary, you can apply the same steps for audio files.
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following examples shows how to add a hyperlink to a video in a PowerPoint Presentation.
>  
>  Presentation pres = new Presentation();
>  try {
>      IVideo video = pres.getVideos().addVideo(Files.readAllBytes(Paths.get("video.avi")));
>      IVideoFrame videoFrame = pres.getSlides().get_Item(0).getShapes().addVideoFrame(10, 10, 100, 100, video);
>      videoFrame.setHyperlinkClick(new Hyperlink("https://www.aspose.com/"));
>      videoFrame.getHyperlinkClick().setTooltip("More than 70% Fortune 100 companies trust Aspose APIs");
>      pres.save("pres-out.pptx", SaveFormat.Pptx);
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following examples shows how to create Video Frame with Video from Web Source in a PowerPoint Presentation.
>  
>  public static void run()
>  {
>      Presentation pres = new Presentation();
>      try {
>          addVideoFromYouTube(pres, "Tj75Arhq5ho");
>          pres.save("AddVideoFrameFromWebSource_out.pptx", SaveFormat.Pptx);
>      } catch(IOException e) {
>      } finally {
>          if (pres != null) pres.dispose();
>      }
>  }
>  private static void addVideoFromYouTube(Presentation pres, String videoId) throws IOException
>  {
>      //add videoFrame
>      IVideoFrame videoFrame = pres.getSlides().get_Item(0).getShapes().addVideoFrame(10, 10, 427, 240, "https://www.youtube.com/embed/" + videoId);
>      videoFrame.setPlayMode(VideoPlayModePreset.Auto);
> 
>      //load thumbnail
>      String thumbnailUri = "http://img.youtube.com/vi/" + videoId + "/hqdefault.jpg";
>      URL url = new URL(thumbnailUri);
>      URLConnection connection = url.openConnection();
>      connection.setConnectTimeout(5000);
>      connection.setReadTimeout(10000);
>      InputStream input = connection.getInputStream();
>      ByteArrayOutputStream output = new ByteArrayOutputStream();
>      try
>      {
>          byte[] buffer = new byte[8192];
>          for (int count; (count = input.read(buffer)) > 0; )
>          {
>              output.write(buffer, 0, count);
>          }
>          videoFrame.getPictureFormat().getPicture().setImage(pres.getImages().addImage(output.toByteArray()));
>      } finally {
>          if (input != null) input.close();
>          if (output != null) output.close();
>      }
>  }
>  
>  The following examples shows how to extract Video from slide of PowerPoint Presentation.
>  
>  // Instantiate a Presentation object that represents a presentation file
>  Presentation presentation = new Presentation("Video.pptx");
>  try {
>      for (ISlide slide : presentation.getSlides())
>      {
>          for (IShape shape : presentation.getSlides().get_Item(0).getShapes())
>          {
>              if (shape instanceof VideoFrame)
>              {
>                  IVideoFrame vf = (IVideoFrame) shape;
>                  String type = vf.getEmbeddedVideo().getContentType();
>                  int ss = type.lastIndexOf('/');
>                  type = type.substring(ss + 1);
>                  byte[] buffer = vf.getEmbeddedVideo().getBinaryData();
>                  FileOutputStream fop = new FileOutputStream("NewVideo_out." + type);
>                  try
>                  {
>                      fop.write(buffer);
>                      fop.flush();
>                      fop.close();
>                  }
>                  finally
>                  {
>                      if (presentation != null) presentation.dispose();
>                  }
>              }
>          }
>      }
>  } catch(IOException e) {
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Retourneert:**
[IVideoCollection](../../com.aspose.slides/ivideocollection)
### getSlideShowSettings() {#getSlideShowSettings--}
```
public final SlideShowSettings getSlideShowSettings()
```


Retourneert de diavoorstelling-instellingen voor de presentatie.

**Retourneert:**
[SlideShowSettings](../../com.aspose.slides/slideshowsettings)
### getDigitalSignatures() {#getDigitalSignatures--}
```
public final IDigitalSignatureCollection getDigitalSignatures()
```


Retourneert de collectie handtekeningen die worden gebruikt om de presentatie te ondertekenen. Alleen-lezen [IDigitalSignatureCollection](../../com.aspose.slides/idigitalsignaturecollection).

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
>      // Itereer over alle aangepaste XML-onderdelen
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


Haalt of stelt VBA-project met presentatiemacro's in. Lezen/Schrijven [IVbaProject](../../com.aspose.slides/ivbaproject).

**Retourneert:**
[IVbaProject](../../com.aspose.slides/ivbaproject)
### setVbaProject(IVbaProject value) {#setVbaProject-com.aspose.slides.IVbaProject-}
```
public final void setVbaProject(IVbaProject value)
```


Haalt of stelt VBA-project met presentatiemacro's in. Lezen/Schrijven [IVbaProject](../../com.aspose.slides/ivbaproject).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IVbaProject](../../com.aspose.slides/ivbaproject) |  |

### getHyperlinkQueries() {#getHyperlinkQueries--}
```
public final IHyperlinkQueries getHyperlinkQueries()
```


Biedt gemakkelijke toegang tot alle hyperlinks die in alle presentatieslides staan (niet in master-, lay-out- of notitieslides). Alleen-lezen [IHyperlinkQueries](../../com.aspose.slides/ihyperlinkqueries).

**Retourneert:**
[IHyperlinkQueries](../../com.aspose.slides/ihyperlinkqueries)
### getViewProperties() {#getViewProperties--}
```
public final IViewProperties getViewProperties()
```


Haalt presentatiewijde weergave-eigenschappen op. Alleen-lezen [IViewProperties](../../com.aspose.slides/iviewproperties).

**Retourneert:**
[IViewProperties](../../com.aspose.slides/iviewproperties)
### getFirstSlideNumber() {#getFirstSlideNumber--}
```
public final int getFirstSlideNumber()
```


Geeft het eerste slide-nummer in de presentatie weer

**Retourneert:**
int
### setFirstSlideNumber(int value) {#setFirstSlideNumber-int-}
```
public final void setFirstSlideNumber(int value)
```


Geeft het eerste slide-nummer in de presentatie weer

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getSensitivityLabels() {#getSensitivityLabels--}
```
public final ISensitivityLabelCollection getSensitivityLabels()
```


Retourneert de collectie gevoeligheidslabels die op het presentatiedocument zijn toegepast. Alleen-lezen [ISensitivityLabelCollection](../../com.aspose.slides/isensitivitylabelcollection).

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
>      UUID siteIdGuid = UUID.fromString("{xxxxxxxx-xxxx-xxxx-xxxx-xxxxxxxxxxxx}"); // Haal de Azure AD-site-id op uit het beleid
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
| Parameter | Type | Description |
| --- | --- | --- |
| id | long | Id van een slide. |

**Retourneert:**
[IBaseSlide](../../com.aspose.slides/ibaseslide) - IBaseSlide object.
### getSourceFormat() {#getSourceFormat--}
```
public final int getSourceFormat()
```


Retourneert informatie over vanuit welk formaat de presentatie is geladen. Alleen-lezen [SourceFormat](../../com.aspose.slides/sourceformat).

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
>  //Instantieer een presentatie-object dat een presentiebestand vertegenwoordigt
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
| Parameter | Type | Description |
| --- | --- | --- |
| fname | java.lang.String | Pad naar het aangemaakte bestand. |
| format | int | Formaat van de geëxporteerde gegevens. |

### save(OutputStream stream, int format) {#save-java.io.OutputStream-int-}
```
public final void save(OutputStream stream, int format)
```


Slaat alle slides van een presentatie op in een stream in het opgegeven formaat.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.OutputStream | Output-stream. |
| format | int | Formaat van de geëxporteerde gegevens. |

### save(String fname, int format, ISaveOptions options) {#save-java.lang.String-int-com.aspose.slides.ISaveOptions-}
```
public final void save(String fname, int format, ISaveOptions options)
```


Slaat alle slides van een presentatie op in een bestand met het opgegeven formaat en met aanvullende opties.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fname | java.lang.String | Pad naar het aangemaakte bestand. |
| format | int | Formaat van de geëxporteerde gegevens. |
| options | [ISaveOptions](../../com.aspose.slides/isaveoptions) | Aanvullende formaat-opties. |

### save(OutputStream stream, int format, ISaveOptions options) {#save-java.io.OutputStream-int-com.aspose.slides.ISaveOptions-}
```
public final void save(OutputStream stream, int format, ISaveOptions options)
```


Slaat alle slides van een presentatie op in een stream in het opgegeven formaat en met aanvullende opties.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.OutputStream | Output-stream. |
| format | int | Formaat van de geëxporteerde gegevens. |
| options | [ISaveOptions](../../com.aspose.slides/isaveoptions) | Aanvullende formaat-opties. |

### save(IXamlOptions options) {#save-com.aspose.slides.IXamlOptions-}
```
public final void save(IXamlOptions options)
```


Slaat alle slides van een presentatie op in een reeks bestanden die XAML-markup vertegenwoordigen.

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
| Parameter | Type | Description |
| --- | --- | --- |
| options | [IXamlOptions](../../com.aspose.slides/ixamloptions) | De XAML-formaatopties. |

### getImages(IRenderingOptions options) {#getImages-com.aspose.slides.IRenderingOptions-}
```
public final IImage[] getImages(IRenderingOptions options)
```


Retourneert Image-objecten voor alle slides van een presentatie.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Tiff-opties. |

**Retourneert:**
com.aspose.slides.IImage[] - Image-objecten.
### getImages(IRenderingOptions options, int[] slides) {#getImages-com.aspose.slides.IRenderingOptions-int---}
```
public final IImage[] getImages(IRenderingOptions options, int[] slides)
```


Retourneert miniatuur-Image-objecten voor opgegeven slides van een presentatie.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Tiff-opties. |
| slides | int[] | Array met slide-posities, beginnend vanaf 1. |

**Retourneert:**
com.aspose.slides.IImage[] - Image-objecten.
### getImages(IRenderingOptions options, float scaleX, float scaleY) {#getImages-com.aspose.slides.IRenderingOptions-float-float-}
```
public final IImage[] getImages(IRenderingOptions options, float scaleX, float scaleY)
```


Retourneert miniatuur-Image-objecten voor alle slides van een presentatie met aangepaste schaal.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Tiff-opties. |
| scaleX | float | De waarde waarmee deze miniatuur in de x-as wordt geschaald. |
| scaleY | float | De waarde waarmee deze miniatuur in de y-as wordt geschaald. |

**Retourneert:**
com.aspose.slides.IImage[] - Image-objecten.
### getImages(IRenderingOptions options, int[] slides, float scaleX, float scaleY) {#getImages-com.aspose.slides.IRenderingOptions-int---float-float-}
```
public final IImage[] getImages(IRenderingOptions options, int[] slides, float scaleX, float scaleY)
```


Retourneert miniatuur-Image-objecten voor opgegeven slides van een presentatie met aangepaste schaal.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Tiff-opties. |
| slides | int[] | Array met slide-posities, beginnend vanaf 1. |
| scaleX | float | De waarde waarmee deze miniatuur in de x-as wordt geschaald. |
| scaleY | float | De waarde waarmee deze miniatuur in de y-as wordt geschaald. |

**Retourneert:**
com.aspose.slides.IImage[] - Image-objecten.
### getImages(IRenderingOptions options, Dimension imageSize) {#getImages-com.aspose.slides.IRenderingOptions-java.awt.Dimension-}
```
public final IImage[] getImages(IRenderingOptions options, Dimension imageSize)
```


Retourneert miniatuur-Image-objecten voor alle slides van een presentatie met opgegeven grootte.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Tiff-opties. |
| imageSize | java.awt.Dimension | Grootte van de te maken afbeelding. |

**Retourneert:**
com.aspose.slides.IImage[] - Image-objecten.
### getImages(IRenderingOptions options, int[] slides, Dimension imageSize) {#getImages-com.aspose.slides.IRenderingOptions-int---java.awt.Dimension-}
```
public final IImage[] getImages(IRenderingOptions options, int[] slides, Dimension imageSize)
```


Retourneert miniatuur-Image-objecten voor opgegeven slides van een presentatie met opgegeven grootte.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Tiff-opties. |
| slides | int[] | Array met slide-posities, beginnend vanaf 1. |
| imageSize | java.awt.Dimension | Grootte van de te maken afbeelding. |

**Retourneert:**
com.aspose.slides.IImage[] - Image-objecten.
### save(String fname, int[] slides, int format) {#save-java.lang.String-int---int-}
```
public final void save(String fname, int[] slides, int format)
```


Slaat opgegeven slides van een presentatie op in een bestand met het opgegeven formaat met behoud van paginanummer.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fname | java.lang.String | Pad naar het aangemaakte bestand. |
| slides | int[] | Array met slide-posities, beginnend vanaf 1. |
| format | int | Formaat van de geëxporteerde gegevens. |

### save(String fname, int[] slides, int format, ISaveOptions options) {#save-java.lang.String-int---int-com.aspose.slides.ISaveOptions-}
```
public final void save(String fname, int[] slides, int format, ISaveOptions options)
```


Slaat opgegeven slides van een presentatie op in een bestand met het opgegeven formaat met behoud van paginanummer.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fname | java.lang.String | Pad naar het aangemaakte bestand. |
| slides | int[] | Array met slide-posities, beginnend vanaf 1. |
| format | int | Formaat van de geëxporteerde gegevens. |
| options | [ISaveOptions](../../com.aspose.slides/isaveoptions) | Aanvullende formaat-opties. |

### save(OutputStream stream, int[] slides, int format) {#save-java.io.OutputStream-int---int-}
```
public final void save(OutputStream stream, int[] slides, int format)
```


Slaat opgegeven slides van een presentatie op in een stream in het opgegeven formaat met behoud van paginanummer.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.OutputStream | Output-stream. |
| slides | int[] | Array met slide-posities, beginnend vanaf 1. |
| format | int | Formaat van de geëxporteerde gegevens. |

### save(OutputStream stream, int[] slides, int format, ISaveOptions options) {#save-java.io.OutputStream-int---int-com.aspose.slides.ISaveOptions-}
```
public final void save(OutputStream stream, int[] slides, int format, ISaveOptions options)
```


Slaat opgegeven slides van een presentatie op in een stream in het opgegeven formaat met behoud van paginanummer.

--------------------

> ```
> The following example shows how to convert PowerPoint to PNG.
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
>  The following example shows how to convert PowerPoint to PNG with custom dimensions.
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
>  The following example shows how to convert PowerPoint to PNG with custom size.
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
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.OutputStream | Output-stream. |
| slides | int[] | Array met slide-posities, beginnend vanaf 1. |
| format | int | Formaat van de geëxporteerde gegevens. |
| options | [ISaveOptions](../../com.aspose.slides/isaveoptions) | Aanvullende formaat-opties. |

### joinPortionsWithSameFormatting() {#joinPortionsWithSameFormatting--}
```
public final void joinPortionsWithSameFormatting()
```


Voegt runs samen met dezelfde opmaak in alle alinea's in alle aanvaardbare shapes in alle slides.

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
>      // markeren van alle afzonderlijke 'the' voorkomens
>      presentation.highlightText("the", Color.MAGENTA);
>      presentation.save("SomePresentation-out2.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| text | java.lang.String | De tekst om te markeren. |
| highlightColor | java.awt.Color | De kleur om de tekst te markeren. |

### highlightText(String text, Color highlightColor, ITextSearchOptions options, IFindResultCallback callback) {#highlightText-java.lang.String-java.awt.Color-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-}
```
public final void highlightText(String text, Color highlightColor, ITextSearchOptions options, IFindResultCallback callback)
```


Markeert alle overeenkomsten van de voorbeeldtekst met de opgegeven kleur.

--------------------

> ```
> Het volgende codevoorbeeld toont hoe tekst kan worden gemarkeerd in een PowerPoint-presentatie.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      TextSearchOptions textSearchOptions = new TextSearchOptions();
>      textSearchOptions.setWholeWordsOnly(true);
>      // markeren van alle afzonderlijke 'the' voorkomens
>      presentation.highlightText("the", Color.MAGENTA, textSearchOptions, null);
>      presentation.save("SomePresentation-out2.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| text | java.lang.String | De tekst om te markeren. |
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
>      // highlighting all words with 10 symbols or longer
>      presentation.highlightRegex(regex, Color.BLUE, null);
>      presentation.save("SomePresentation-out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| regex | java.util.regex.Pattern | De reguliere expressie java.util.regex.Pattern om strings te krijgen die gemarkeerd moeten worden. |
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
>      // Replace all separate 'the' occurrences with '***'
>      presentation.replaceText("the", "***", textSearchOptions, null);
>      presentation.save("SomePresentation-out2.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| oldText | java.lang.String | De string die moet worden vervangen. |
| newText | java.lang.String | De string om alle voorkomens van oldText te vervangen. |
| options | [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions) | Tekstzoekopties [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions). |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | Het callback-object voor het ontvangen van zoekresultaten [IFindResultCallback](../../com.aspose.slides/ifindresultcallback). |

### replaceRegex(Pattern regex, String newText, IFindResultCallback callback) {#replaceRegex-java.util.regex.Pattern-java.lang.String-com.aspose.slides.IFindResultCallback-}
```
public final void replaceRegex(Pattern regex, String newText, IFindResultCallback callback)
```

Vervangt alle overeenkomsten van de reguliere expressie door de opgegeven string.

--------------------

> ```
> The following code sample shows how to replace text using regular expression with the specified string.
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      Pattern regex = Pattern.compile("\\b[^\\s]{10,}\\b");
>      // Vervang alle woorden met 10 tekens of langer door '***'
>      presentation.replaceRegex(regex, "***", null);
>      presentation.save("SomePresentation-out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| regex | java.util.regex.Pattern | De reguliere expressie java.util.regex.Pattern om strings te verkrijgen die moeten worden vervangen. |
| newText | java.lang.String | De string om alle voorkomens van de te vervangen strings te vervangen. |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | Het callback-object voor het ontvangen van zoekresultaten [IFindResultCallback](../../com.aspose.slides/ifindresultcallback). |