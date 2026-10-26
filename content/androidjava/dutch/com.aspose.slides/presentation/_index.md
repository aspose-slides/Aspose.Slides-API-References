---
title: Presentation
second_title: Aspose.Slides voor Android via Java API-referentie
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
>      // Voeg een autovorm van het type lijn toe
>      slide.getShapes().addAutoShape(ShapeType.Line, 50, 150, 300, 0);
>      // Sla het presentatiebestand op.
>      pres.save("NewPresentation_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>   
>   The following example shows how to open and save Presentation.
>   
>  // Laad elk ondersteund bestand in Presentation, bv. ppt, pptx, odp enz.
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
| [Presentation(InputStream stream)](#Presentation-java.io.InputStream-) | Deze constructor is de primaire methode voor het lezen van een bestaande presentatie. |
| [Presentation(InputStream stream, LoadOptions loadOptions)](#Presentation-java.io.InputStream-com.aspose.slides.LoadOptions-) | Deze constructor is de primaire methode voor het lezen van een bestaande presentatie. |
| [Presentation(String file)](#Presentation-java.lang.String-) | Deze constructor haalt een bron-bestandspad op waarvan de inhoud van de presentatie wordt gelezen. |
| [Presentation(String file, LoadOptions loadOptions)](#Presentation-java.lang.String-com.aspose.slides.LoadOptions-) | Deze constructor haalt een bron-bestandspad op waarvan de inhoud van de presentatie wordt gelezen. |
## Methods

| Method | Beschrijving |
| --- | --- |
| [getCurrentDateTime()](#getCurrentDateTime--) | Retourneert of stelt datum en tijd in die de inhoud van datetime-velden zal vervangen. |
| [setCurrentDateTime(Date value)](#setCurrentDateTime-java.util.Date-) | Retourneert of stelt datum en tijd in die de inhoud van datetime-velden zal vervangen. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | Retourneert de huidige HeaderFooter-manager. |
| [getProtectionManager()](#getProtectionManager--) | Haalt de beheerder van de permissies voor deze presentatie op. |
| [getSlides()](#getSlides--) | Retourneert een lijst van alle dia's die in de presentatie zijn gedefinieerd. |
| [getSections()](#getSections--) | Retourneert een lijst van alle dia-secties die in de presentatie zijn gedefinieerd. |
| [getSlideSize()](#getSlideSize--) | Retourneert het dia-grootte-object. |
| [getNotesSize()](#getNotesSize--) | Retourneert het notitie-dia-grootte-object. |
| [getLayoutSlides()](#getLayoutSlides--) | Retourneert een lijst van alle lay-out dia's die in de presentatie zijn gedefinieerd. |
| [getMasters()](#getMasters--) | Retourneert een lijst van alle master-dia's die in de presentatie zijn gedefinieerd. |
| [getMasterNotesSlideManager()](#getMasterNotesSlideManager--) | Retourneert de notitie-master-manager. |
| [getMasterHandoutSlideManager()](#getMasterHandoutSlideManager--) | Retourneert de hand-out-master-manager. |
| [getFontsManager()](#getFontsManager--) | Retourneert de lettertype-manager. |
| [getDefaultTextStyle()](#getDefaultTextStyle--) | Retourneert de standaard-tekstopmaak voor vormen. |
| [getCommentAuthors()](#getCommentAuthors--) | Retourneert de verzameling van commentaarauteurs. |
| [getDocumentProperties()](#getDocumentProperties--) | Retourneert een DocumentProperties-object dat standaard- en aangepaste documenteigenschappen bevat. |
| [getImages()](#getImages--) | Retourneert de verzameling van alle afbeeldingen in de presentatie. |
| [getAudios()](#getAudios--) | Retourneert de verzameling van alle ingesloten audiobestanden in de presentatie. |
| [getVideos()](#getVideos--) | Retourneert de verzameling van alle ingesloten videobestanden in de presentatie. |
| [getSlideShowSettings()](#getSlideShowSettings--) | Retourneert de diavoorstellings-instellingen voor de presentatie. |
| [getDigitalSignatures()](#getDigitalSignatures--) | Retourneert de verzameling van handtekeningen die worden gebruikt om de presentatie te ondertekenen. |
| [getCustomData()](#getCustomData--) | Retourneert de aangepaste gegevens van de presentatie. |
| [getAllCustomXmlParts()](#getAllCustomXmlParts--) | Retourneert alle aangepaste gegevens-onderdelen in de presentatie. |
| [getVbaProject()](#getVbaProject--) | Haalt of stelt het VBA-project met presentatiemacro’s in. |
| [setVbaProject(IVbaProject value)](#setVbaProject-com.aspose.slides.IVbaProject-) | Haalt of stelt het VBA-project met presentatiemacro’s in. |
| [getHyperlinkQueries()](#getHyperlinkQueries--) | Biedt gemakkelijke toegang tot alle hyperlinks die in alle presentatiedia’s staan (niet in master-, lay-out- of notitiedia’s). |
| [getViewProperties()](#getViewProperties--) | Haalt algehele weergave-eigenschappen van de presentatie op. |
| [getFirstSlideNumber()](#getFirstSlideNumber--) | Vertegenwoordigt het eerste dia-nummer in de presentatie. |
| [setFirstSlideNumber(int value)](#setFirstSlideNumber-int-) | Vertegenwoordigt het eerste dia-nummer in de presentatie. |
| [getSensitivityLabels()](#getSensitivityLabels--) | Retourneert de verzameling van gevoeligheidslabels die op het presentatiedocument zijn toegepast. |
| [getSlideById(long id)](#getSlideById-long-) | Retourneert een Slide, MasterSlide of LayoutSlide op basis van Id. |
| [getSourceFormat()](#getSourceFormat--) | Retourneert informatie over het formaat waarmee de presentatie is geladen. |
| [getMasterTheme()](#getMasterTheme--) | Retourneert het master-thema. |
| [save(String fname, int format)](#save-java.lang.String-int-) | Slaat alle dia's van een presentatie op naar een bestand met het opgegeven formaat. |
| [save(OutputStream stream, int format)](#save-java.io.OutputStream-int-) | Slaat alle dia's van een presentatie op naar een stream in het opgegeven formaat. |
| [save(String fname, int format, ISaveOptions options)](#save-java.lang.String-int-com.aspose.slides.ISaveOptions-) | Slaat alle dia's van een presentatie op naar een bestand met het opgegeven formaat en met extra opties. |
| [save(OutputStream stream, int format, ISaveOptions options)](#save-java.io.OutputStream-int-com.aspose.slides.ISaveOptions-) | Slaat alle dia's van een presentatie op naar een stream in het opgegeven formaat en met extra opties. |
| [save(IXamlOptions options)](#save-com.aspose.slides.IXamlOptions-) | Slaat alle dia's van een presentatie op naar een reeks bestanden die XAML-opmaak vertegenwoordigen. |
| [getImages(IRenderingOptions options)](#getImages-com.aspose.slides.IRenderingOptions-) | Retourneert Image-objecten voor alle dia's van een presentatie. |
| [getImages(IRenderingOptions options, int[] slides)](#getImages-com.aspose.slides.IRenderingOptions-int---) | Retourneert een Thumbnail-Image-object voor gespecificeerde dia's van een presentatie. |
| [getImages(IRenderingOptions options, float scaleX, float scaleY)](#getImages-com.aspose.slides.IRenderingOptions-float-float-) | Retourneert een Thumbnail-Image-object voor alle dia's van een presentatie met aangepaste schaal. |
| [getImages(IRenderingOptions options, int[] slides, float scaleX, float scaleY)](#getImages-com.aspose.slides.IRenderingOptions-int---float-float-) | Retourneert een Thumbnail-Image-object voor gespecificeerde dia's van een presentatie met aangepaste schaal. |
| [getImages(IRenderingOptions options, Size imageSize)](#getImages-com.aspose.slides.IRenderingOptions-com.aspose.slides.android.Size-) | Retourneert een Thumbnail-Image-object voor alle dia's van een presentatie met opgegeven grootte. |
| [getImages(IRenderingOptions options, int[] slides, Size imageSize)](#getImages-com.aspose.slides.IRenderingOptions-int---com.aspose.slides.android.Size-) | Retourneert een Thumbnail-Image-object voor gespecificeerde dia's van een presentatie met opgegeven grootte. |
| [save(String fname, int[] slides, int format)](#save-java.lang.String-int---int-) | Slaat gespecificeerde dia's van een presentatie op naar een bestand met het opgegeven formaat en behoudt paginanummers. |
| [save(String fname, int[] slides, int format, ISaveOptions options)](#save-java.lang.String-int---int-com.aspose.slides.ISaveOptions-) | Slaat gespecificeerde dia's van een presentatie op naar een bestand met het opgegeven formaat en behoudt paginanummers. |
| [save(OutputStream stream, int[] slides, int format)](#save-java.io.OutputStream-int---int-) | Slaat gespecificeerde dia's van een presentatie op naar een stream in het opgegeven formaat en behoudt paginanummers. |
| [save(OutputStream stream, int[] slides, int format, ISaveOptions options)](#save-java.io.OutputStream-int---int-com.aspose.slides.ISaveOptions-) | Slaat gespecificeerde dia's van een presentatie op naar een stream in het opgegeven formaat en behoudt paginanummers. |
| [joinPortionsWithSameFormatting()](#joinPortionsWithSameFormatting--) | Voegt runs met dezelfde opmaak samen in alle alinea’s in alle toegestane vormen in alle dia’s. |
| [dispose()](#dispose--) | Geeft alle bronnen vrij die door dit Presentation-object worden gebruikt. |
| [getPresentation()](#getPresentation--) | Retourneert de bovenliggende presentatie van een tekst. |
| [highlightText(String text, Integer highlightColor)](#highlightText-java.lang.String-java.lang.Integer-) | Markeert alle overeenkomsten van de voorbeeldtekst met de opgegeven kleur. |
| [highlightText(String text, Integer highlightColor, ITextSearchOptions options, IFindResultCallback callback)](#highlightText-java.lang.String-java.lang.Integer-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-) | Markeert alle overeenkomsten van de voorbeeldtekst met de opgegeven kleur. |
| [highlightRegex(Pattern regex, Integer highlightColor, IFindResultCallback callback)](#highlightRegex-java.util.regex.Pattern-java.lang.Integer-com.aspose.slides.IFindResultCallback-) | Markeert alle overeenkomsten van de reguliere expressie met de opgegeven kleur. |
| [replaceText(String oldText, String newText, ITextSearchOptions options, IFindResultCallback callback)](#replaceText-java.lang.String-java.lang.String-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-) | Vervangt alle voorkomens van de opgegeven tekst door een andere opgegeven tekst. |
| [replaceRegex(Pattern regex, String newText, IFindResultCallback callback)](#replaceRegex-java.util.regex.Pattern-java.lang.String-com.aspose.slides.IFindResultCallback-) | Vervangt alle overeenkomsten van de reguliere expressie door de opgegeven tekenreeks. |
### Presentation() {#Presentation--}
```
public Presentation()
```

Deze constructor maakt een nieuwe presentatie vanaf nul. De aangemaakte presentatie bevat één lege dia.

### Presentation(LoadOptions loadOptions) {#Presentation-com.aspose.slides.LoadOptions-}
```
public Presentation(LoadOptions loadOptions)
```

Deze constructor maakt een nieuwe presentatie vanaf nul. De aangemaakte presentatie bevat één lege dia.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| loadOptions | [LoadOptions](../../com.aspose.slides/loadoptions) | Extra laadopties. |

### Presentation(InputStream stream) {#Presentation-java.io.InputStream-}
```
public Presentation(InputStream stream)
```

Deze constructor is de primaire methode voor het lezen van een bestaande presentatie.

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

Deze constructor is de primaire methode voor het lezen van een bestaande presentatie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| stream | java.io.InputStream | Invoerstroom. |
| loadOptions | [LoadOptions](../../com.aspose.slides/loadoptions) | Extra laadopties. |

### Presentation(String file) {#Presentation-java.lang.String-}
```
public Presentation(String file)
```

Deze constructor haalt een bron-bestandspad op waarvan de inhoud van de presentatie wordt gelezen.

--------------------

> ```
> Presentation pres = new Presentation("demo.pptx");
> ```


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| file | java.lang.String | Invoerbestand. |

### Presentation(String file, LoadOptions loadOptions) {#Presentation-java.lang.String-com.aspose.slides.LoadOptions-}
```
public Presentation(String file, LoadOptions loadOptions)
```

Deze constructor haalt een bron-bestandspad op waarvan de inhoud van de presentatie wordt gelezen.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| file | java.lang.String | Invoerbestand. |
| loadOptions | [LoadOptions](../../com.aspose.slides/loadoptions) | Extra laadopties. |

### getCurrentDateTime() {#getCurrentDateTime--}
```
public final Date getCurrentDateTime()
```

Retourneert of stelt datum en tijd in die de inhoud van datetime-velden zal vervangen. Standaard de tijd waarop dit Presentation-object is gemaakt. Lezen/Schrijven java.util.Date.

**Retourneert:**
java.util.Date
### setCurrentDateTime(Date value) {#setCurrentDateTime-java.util.Date-}
```
public final void setCurrentDateTime(Date value)
```

Retourneert of stelt datum en tijd in die de inhoud van datetime-velden zal vervangen. Standaard de tijd waarop dit Presentation-object is gemaakt. Lezen/Schrijven java.util.Date.

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

Retourneert de huidige HeaderFooter-manager. Alleen-lezen [IPresentationHeaderFooterManager](../../com.aspose.slides/ipresentationheaderfootermanager).

--------------------

> ```
> The following example shows how to set footer visibility inside Slide of PowerPoint Presentation.
>  
>  Presentation pres = new Presentation("presentation.ppt");
>  try
>  {
>      IBaseSlideHeaderFooterManager headerFooterManager = pres.getSlides().get_Item(0).getHeaderFooterManager();
>      if (!headerFooterManager.isFooterVisible()) // Property IsFooterVisible wordt gebruikt om aan te geven dat een slide footer placeholder niet aanwezig is.
>      {
>          headerFooterManager.setFooterVisibility(true); // Method SetFooterVisibility wordt gebruikt om een slide footer placeholder zichtbaar te maken.
>      }
>      if (!headerFooterManager.isSlideNumberVisible()) // Property IsSlideNumberVisible wordt gebruikt om aan te geven dat een slide page number placeholder niet aanwezig is.
>      {
>          headerFooterManager.setSlideNumberVisibility(true); // Method SetSlideNumberVisibility wordt gebruikt om een slide page number placeholder zichtbaar te maken.
>      }
>      if (!headerFooterManager.isDateTimeVisible()) // Property IsDateTimeVisible wordt gebruikt om aan te geven dat een slide date-time placeholder niet aanwezig is.
>      {
>          headerFooterManager.setDateTimeVisibility(true); // Method SetFooterVisibility wordt gebruikt om een slide date-time placeholder zichtbaar te maken.
>      }
>      headerFooterManager.setFooterText("Footer text"); // Method SetFooterText wordt gebruikt om tekst in slide footer placeholder in te stellen.
>      headerFooterManager.setDateTimeText("Date and time text"); // Method SetDateTimeText wordt gebruikt om tekst in slide date-time placeholder in te stellen.
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
>      headerFooterManager.setFooterAndChildFootersVisibility(true); // Method SetFooterAndChildFootersVisibility wordt gebruikt om een master slide en alle child footer placeholders zichtbaar te maken.
>      headerFooterManager.setSlideNumberAndChildSlideNumbersVisibility(true); // Method SetSlideNumberAndChildSlideNumbersVisibility wordt gebruikt om een master slide en alle child page number placeholders zichtbaar te maken.
>      headerFooterManager.setDateTimeAndChildDateTimesVisibility(true); // Method SetDateTimeAndChildDateTimesVisibility wordt gebruikt om een master slide en alle child date-time placeholders zichtbaar te maken.
> 
>      headerFooterManager.setFooterAndChildFootersText("Footer text"); // Method SetFooterAndChildFootersText wordt gebruikt om tekst in master slide en alle child footer placeholders in te stellen.
>      headerFooterManager.setDateTimeAndChildDateTimesText("Date and time text"); // Method SetDateTimeAndChildDateTimesText wordt gebruikt om tekst in master slide en alle child date-time placeholders in te stellen.
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

Haalt de beheerder van de permissies voor deze presentatie op. Alleen-lezen [IProtectionManager](../../com.aspose.slides/iprotectionmanager).

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
>  // Instantieer de Presentation-klasse die het presentatie-bestand vertegenwoordigt
>  Presentation pres = new Presentation();
>  try
>  {
>      // Stel de achtergrondkleur van de eerste ISlide in op blauw
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
>  // Instantieer de Presentation-klasse die het presentatie-bestand vertegenwoordigt
>  Presentation pres = new Presentation("SetImageAsBackground.pptx");
>  try {
>      // Stel de achtergrond in met een afbeelding
>      pres.getSlides().get_Item(0).getBackground().setType(BackgroundType.OwnBackground);
>      pres.getSlides().get_Item(0).getBackground().getFillFormat().setFillType(FillType.Picture);
>      pres.getSlides().get_Item(0).getBackground().getFillFormat().getPictureFillFormat().setPictureFillMode(PictureFillMode.Stretch);
>      // Stel de afbeelding in
>      FileInputStream fos = null;
>      try {
>          fos = new FileInputStream("Tulips.jpg");
>          // Voeg afbeelding toe aan de afbeeldingencollectie van de presentatie
>          IPPImage imgx = pres.getImages().addImage(fos);
>          pres.getSlides().get_Item(0).getBackground().getFillFormat().getPictureFillFormat().getPicture().setImage(imgx);
>      } finally {
>          if (fos != null) fos.close();
>      }
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
>  // Instantieer de Presentation-klasse om het bron-presentatie-bestand te laden
>  Presentation pres = new Presentation("AccessSlides.pptx");
>  try
>  {
>      // Pas cirkeltype-overgang toe op dia 1
>      pres.getSlides().get_Item(0).getSlideShowTransition().setType(TransitionType.Circle);
>      // Pas kamtype-overgang toe op dia 2
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
>  // Instantieer de Presentation-klasse die een presentatie-bestand vertegenwoordigt
>  Presentation pres = new Presentation("BetterSlideTransitions.pptx");
>  try
>  {
>      // Pas cirkeltype-overgang toe op dia 1
>      pres.getSlides().get_Item(0).getSlideShowTransition().setType(TransitionType.Circle);
>      // Stel de overgangstijd in op 3 seconden
>      pres.getSlides().get_Item(0).getSlideShowTransition().setAdvanceOnClick(true);
>      pres.getSlides().get_Item(0).getSlideShowTransition().setAdvanceAfterTime(3000);
>      // Pas kamtype-overgang toe op dia 2
>      pres.getSlides().get_Item(1).getSlideShowTransition().setType(TransitionType.Comb);
>      // Stel de overgangstijd in op 5 seconden
>      pres.getSlides().get_Item(1).getSlideShowTransition().setAdvanceOnClick(true);
>      pres.getSlides().get_Item(1).getSlideShowTransition().setAdvanceAfterTime(5000);
>      // Pas zoomtype-overgang toe op dia 3
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


**Retourneert:**
[ISectionCollection](../../com.aspose.slides/isectioncollection)
### getSlideSize() {#getSlideSize--}
```
public final ISlideSize getSlideSize()
```

Retourneert het dia-grootte-object. Alleen-lezen [ISlideSize](../../com.aspose.slides/islidesize).

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
>  // Instantieer een Presentation-object dat een presentatiebestand vertegenwoordigt
>  Presentation presentation = new Presentation("AccessSlides.pptx");
>  try {
>      Presentation auxPresentation = new Presentation();
>      try {
>          ISlide slide = presentation.getSlides().get_Item(0);
>          // Stel de dia-grootte van gegenereerde presentaties in op die van de bron
>          presentation.getSlideSize().setSize(540, 720, SlideSizeScaleType.EnsureFit); // Methode SetSize wordt gebruikt om de dia-grootte in te stellen met inhoudsschaal om te passen
>          presentation.getSlideSize().setSize(SlideSizeType.A4Paper, SlideSizeScaleType.Maximize); // Methode SetSize wordt gebruikt om de dia-grootte in te stellen met maximale inhoudsgrootte
>          // Sla de presentatie op schijf
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
>      pres.getSlideSize().setSize(780, 540, SlideSizeScaleType.DoNotScale); // A4-papiergrootte
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

Retourneert het notitie-dia-grootte-object. Alleen-lezen [INotesSize](../../com.aspose.slides/inotessize).

**Retourneert:**
[INotesSize](../../com.aspose.slides/inotessize)
### getLayoutSlides() {#getLayoutSlides--}
```
public final IGlobalLayoutSlideCollection getLayoutSlides()
```

Retourneert een lijst van alle lay-out dia's die in de presentatie zijn gedefinieerd. Alleen-lezen [IGlobalLayoutSlideCollection](../../com.aspose.slides/igloballayoutslidecollection).

--------------------

U kunt alternatieve API gebruiken voor het toevoegen/invoegen/verwijderen/kopiëren van lay-out dia's via de eigenschap IMasterSlide.LayoutSlides.

**Retourneert:**
[IGlobalLayoutSlideCollection](../../com.aspose.slides/igloballayoutslidecollection)
### getMasters() {#getMasters--}
```
public final IMasterSlideCollection getMasters()
```

Retourneert een lijst van alle master-dia's die in de presentatie zijn gedefinieerd. Alleen-lezen [IMasterSlideCollection](../../com.aspose.slides/imasterslidecollection).

--------------------

> ```
> The following examples shows how to adding Images to Master Slides of PowerPoint Presentation.
>  
>  Presentation pres = new Presentation();
>  try {
>      ISlide slide = pres.getSlides().get_Item(0);
>      IMasterSlide masterSlide = slide.getLayoutSlide().getMasterSlide();
>      FileInputStream fos = null;
>      try {
>          fos = new FileInputStream("image.png");
>          IPPImage image = pres.getImages().addImage(fos);
>          masterSlide.getShapes().addPictureFrame(ShapeType.Rectangle, 10, 10, 100, 100, image);
>      } finally {
>          if (fos != null) fos.close();
>      }
>      pres.save("pres.pptx", SaveFormat.Pptx);
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following examples shows how to change the background color of the master slide of PowerPoint Presentation.
>  
>  // Instantieer de Presentation-klasse die het presentatiebestand vertegenwoordigt
>  Presentation pres = new Presentation();
>  try
>  {
>      // Stel de achtergrondkleur van de Master ISlide in op Forest Green
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
>  // Instantieer de Presentation-klasse die het presentatiebestand vertegenwoordigt
>  Presentation presentation = new Presentation("AccessSlides.pptx");
>  try
>  {
>      // Probeer te zoeken op lay-outdia-type
>      IMasterLayoutSlideCollection layoutSlides = presentation.getMasters().get_Item(0).getLayoutSlides();
>      ILayoutSlide layoutSlide = null;
>      if (layoutSlides.getByType(SlideLayoutType.TitleAndObject) != null)
>          layoutSlide = layoutSlides.getByType(SlideLayoutType.TitleAndObject);
>      else
>          layoutSlide = layoutSlides.getByType(SlideLayoutType.Title);
> 
>      if (layoutSlide == null)
>      {
>          // De situatie wanneer een presentatie niet sommige type lay-outs bevat.
>          // presentatiebestand bevat alleen Blank en Custom layout types.
>          // Maar lay-outdia's met Custom types hebben verschillende slide-namen,
>          // zoals "Title", "Title and Content", enz. En het is mogelijk om deze
>          // namen te gebruiken voor lay-outdia-selectie.
>          // Ook is het mogelijk om de set van placeholder-vormtypes te gebruiken. Bijvoorbeeld,
>          // Titeldia zou alleen Title placeholder type moeten hebben, enz.
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

Retourneert de notitie-master-manager. Alleen-lezen [IMasterNotesSlideManager](../../com.aspose.slides/imasternotesslidemanager).

**Retourneert:**
[IMasterNotesSlideManager](../../com.aspose.slides/imasternotesslidemanager)
### getMasterHandoutSlideManager() {#getMasterHandoutSlideManager--}
```
public final IMasterHandoutSlideManager getMasterHandoutSlideManager()
```

Retourneert de hand-out-master-manager. Alleen-lezen [IMasterHandoutSlideManager](../../com.aspose.slides/imasterhandoutslidemanager).

**Retourneert:**
[IMasterHandoutSlideManager](../../com.aspose.slides/imasterhandoutslidemanager)
### getFontsManager() {#getFontsManager--}
```
public final IFontsManager getFontsManager()
```

Retourneert de lettertype-manager. Alleen-lezen [IFontsManager](../../com.aspose.slides/ifontsmanager).

--------------------

> ```
>   // Laad presentatie
>   Presentation pres = new Presentation("Fonts.pptx");
>   try {
>       // Laad bronlettertype om te vervangen
>       IFontData sourceFont = new FontData("Arial");
>       IFontData[] allFonts = pres.getFontsManager().getFonts();
>       for (IFontData font : allFonts)
>       {
>           boolean fontAlreadyEmbedded = false;
>           IFontData[] embeddedFonts = pres.getFontsManager().getEmbeddedFonts();
>           for (int i = 0; i < embeddedFonts.length; i++)
>           {
>               if (embeddedFonts[i].equals(font))
>               {
>                   fontAlreadyEmbedded = true;
>                   break;
>               }
>           }
>           if (!fontAlreadyEmbedded) {
>               pres.getFontsManager().addEmbeddedFont(font, EmbedFontCharacters.All);
>           }
>       }
>       // Sla de presentatie op
>       pres.save("AddEmbeddedFont_out.pptx", SaveFormat.Pptx);
>   } finally {
>       if (pres != null) pres.dispose();
>   }
> ```

**Retourneert:**
[IFontsManager](../../com.aspose.slides/ifontsmanager)
### getDefaultTextStyle() {#getDefaultTextStyle--}
```
public final ITextStyle getDefaultTextStyle()
```

Retourneert de standaard-tekstopmaak voor vormen. Alleen-lezen [ITextStyle](../../com.aspose.slides/itextstyle).

**Retourneert:**
[ITextStyle](../../com.aspose.slides/itextstyle)
### getCommentAuthors() {#getCommentAuthors--}
```
public final ICommentAuthorCollection getCommentAuthors()
```

Retourneert de verzameling van commentaarauteurs. Alleen-lezen [ICommentAuthorCollection](../../com.aspose.slides/icommentauthorcollection).

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

Retourneert de verzameling van alle afbeeldingen in de presentatie. Alleen-lezen [IImageCollection](../../com.aspose.slides/iimagecollection).

--------------------

> ```
> The following examples shows how to add image as BLOB in PowerPoint Presentation.
>  
>  // maakt een nieuwe presentatie aan waaraan de afbeelding zal worden toegevoegd.
>  Presentation pres = new Presentation();
>  try
>  {
>      // veronderstel dat we het grote afbeeldingsbestand hebben dat we in de presentatie willen opnemen
>      FileInputStream fip = new FileInputStream("large_image.jpg");
>      try
>      {
>          // Voeg de afbeelding toe aan de presentatie - we kiezen KeepLocked-gedrag omdat we
>          // NIET van plan het "largeImage.png" bestand te benaderen.
>          IPPImage img = pres.getImages().addImage(fip, LoadingStreamBehavior.KeepLocked);
>          pres.getSlides().get_Item(0).getShapes().addPictureFrame(ShapeType.Rectangle, 0, 0, 300, 200, img);
>          // Slaat de presentatie op. Terwijl een grote presentatie wordt gegenereerd, blijft het geheugenverbruik
>          // laag gedurende de levensduur van het pres-object.
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
>      FileInputStream fos = null;
>      try {
>          fos = new FileInputStream("image.png");
>          // Voegt afbeelding toe aan presentatie
>          IPPImage image = pres.getImages().addImage(fos);
>          // Maakt een afbeeldingkader op dia 1 op basis van de eerder toegevoegde afbeelding
>          IPictureFrame pictureFrame = pres.getSlides().get_Item(0).getShapes().addPictureFrame(ShapeType.Rectangle, 10, 10, 100, 100, image);
>          pictureFrame.setHyperlinkClick(new Hyperlink("https://www.aspose.com/"));
>          pictureFrame.getHyperlinkClick().setTooltip("More than 70% Fortune 100 companies trust Aspose APIs");
>      } finally {
>          if (fos != null) fos.close();
>      }
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

Retourneert de verzameling van alle ingesloten audiobestanden in de presentatie. Alleen-lezen [IAudioCollection](../../com.aspose.slides/iaudiocollection).

--------------------

> ```
> The following examples shows how to add a hyperlink to an audio file.
>  
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream fos = null;
>      try {
>          fos = new FileInputStream("audio.mp3");
>          IAudio audio = pres.getAudios().addAudio(fos);
>          IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(10, 10, 100, 100, audio);
>          audioFrame.setHyperlinkClick(new Hyperlink("https://www.aspose.com/"));
>          audioFrame.getHyperlinkClick().setTooltip("More than 70% Fortune 100 companies trust Aspose APIs");
>      } finally {
>          if (fos != null) fos.close();
>      }
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

Retourneert de verzameling van alle ingesloten videobestanden in de presentatie. Alleen-lezen [IVideoCollection](../../com.aspose.slides/ivideocollection).

--------------------

> ```
> The following examples shows how to add image as BLOB in PowerPoint Presentation.
>  
>  // maakt een nieuwe presentatie aan waaraan de afbeelding zal worden toegevoegd.
>  Presentation pres = new Presentation();
>  try
>  {
>      // veronderstel dat we het grote afbeeldingsbestand hebben dat we in de presentatie willen opnemen
>      FileInputStream fip = new FileInputStream("large_image.jpg");
>      try
>      {
>          // Voeg de afbeelding toe aan de presentatie - we kiezen KeepLocked-gedrag omdat we
>          // NIET van plan het "largeImage.png" bestand te benaderen.
>          IPPImage img = pres.getImages().addImage(fip, LoadingStreamBehavior.KeepLocked);
>          pres.getSlides().get_Item(0).getShapes().addPictureFrame(ShapeType.Rectangle, 0, 0, 300, 200, img);
>          // Slaat de presentatie op. Terwijl een grote presentatie wordt gegenereerd, blijft het geheugenverbruik
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
>      FileInputStream fos = null;
>      try {
>          fos = new FileInputStream("image.png");
>          // Voegt afbeelding toe aan presentatie
>          IPPImage image = pres.getImages().addImage(fos);
>          // Maakt een afbeeldingkader op dia 1 op basis van de eerder toegevoegde afbeelding
>          IPictureFrame pictureFrame = pres.getSlides().get_Item(0).getShapes().addPictureFrame(ShapeType.Rectangle, 10, 10, 100, 100, image);
>          pictureFrame.setHyperlinkClick(new Hyperlink("https://www.aspose.com/"));
>          pictureFrame.getHyperlinkClick().setTooltip("More than 70% Fortune 100 companies trust Aspose APIs");
>      } finally {
>          if (fos != null) fos.close();
>      }
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

Retourneert de diavoorstellings-instellingen voor de presentatie.

**Retourneert:**
[SlideShowSettings](../../com.aspose.slides/slideshowsettings)
### getDigitalSignatures() {#getDigitalSignatures--}
```
public final IDigitalSignatureCollection getDigitalSignatures()
```

Retourneert de verzameling van handtekeningen die worden gebruikt om de presentatie te ondertekenen. Alleen-lezen [IDigitalSignatureCollection](../../com.aspose.slides/idigitalsignaturecollection).

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

Retourneert alle aangepaste gegevens-onderdelen in de presentatie. Alleen-lezen ICustomXmlPart[].

--------------------

> ```
> The following examples show how to clear all custom xml parts from PowerPoint Presentation.
>  
>  Presentation pres = new Presentation("PresentationWithCustomXml.pptx");
>  try {
>      // Doorloop alle aangepaste XML-onderdelen
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

Haalt of stelt het VBA-project met presentatiemacro’s in. Lezen/Schrijven [IVbaProject](../../com.aspose.slides/ivbaproject).

**Retourneert:**
[IVbaProject](../../com.aspose.slides/ivbaproject)
### setVbaProject(IVbaProject value) {#setVbaProject-com.aspose.slides.IVbaProject-}
```
public final void setVbaProject(IVbaProject value)
```

Haalt of stelt het VBA-project met presentatiemacro’s in. Lezen/Schrijven [IVbaProject](../../com.aspose.slides/ivbaproject).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [IVbaProject](../../com.aspose.slides/ivbaproject) |  |

### getHyperlinkQueries() {#getHyperlinkQueries--}
```
public final IHyperlinkQueries getHyperlinkQueries()
```

Biedt gemakkelijke toegang tot alle hyperlinks die in alle presentatiedia’s staan (niet in master-, lay-out- of notitiedia’s). Alleen-lezen [IHyperlinkQueries](../../com.aspose.slides/ihyperlinkqueries).

**Retourneert:**
[IHyperlinkQueries](../../com.aspose.slides/ihyperlinkqueries)
### getViewProperties() {#getViewProperties--}
```
public final IViewProperties getViewProperties()
```

Haalt algehele weergave-eigenschappen van de presentatie op. Alleen-lezen [IViewProperties](../../com.aspose.slides/iviewproperties).

**Retourneert:**
[IViewProperties](../../com.aspose.slides/iviewproperties)
### getFirstSlideNumber() {#getFirstSlideNumber--}
```
public final int getFirstSlideNumber()
```

Vertegenwoordigt het eerste dia-nummer in de presentatie.

**Retourneert:**
int
### setFirstSlideNumber(int value) {#setFirstSlideNumber-int-}
```
public final void setFirstSlideNumber(int value)
```

Vertegenwoordigt het eerste dia-nummer in de presentatie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | int |  |

### getSensitivityLabels() {#getSensitivityLabels--}
```
public final ISensitivityLabelCollection getSensitivityLabels()
```

Retourneert de verzameling van gevoeligheidslabels die op het presentatiedocument zijn toegepast. Alleen-lezen [ISensitivityLabelCollection](../../com.aspose.slides/isensitivitylabelcollection).

--------------------

> ```
> Presentation pres = new Presentation("SomePresentation.pptx");
>  try {
>      ISensitivityLabelCollection sensitivityLabels = pres.getSensitivityLabels();
> 
>      // Druk de toegepaste labels af
>      for (ISensitivityLabel sensitivityLabel : sensitivityLabels)
>          System.out.println("Label Id " + sensitivityLabel.getId() + " from Azure AD site " + sensitivityLabel.getSiteId());
> 
>      // Voeg het nieuwe label toe
>      String labelIdString = "{xxxxxxxx-xxxx-xxxx-xxxx-xxxxxxxxxxxx}"; // Haal het gevoeligheidslabel Id op uit het beleid
>      UUID siteIdGuid = UUID.fromString("{xxxxxxxx-xxxx-xxxx-xxxx-xxxxxxxxxxxx}"); // Haal de Azure AD site-identificatie op uit het beleid
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
| id | long | Id van een dia. |

**Retourneert:**
[IBaseSlide](../../com.aspose.slides/ibaseslide) - IBaseSlide-object.
### getSourceFormat() {#getSourceFormat--}
```
public final int getSourceFormat()
```

Retourneert informatie over het formaat waarmee de presentatie is geladen. Alleen-lezen [SourceFormat](../../com.aspose.slides/sourceformat).

**Retourneert:**
int
### getMasterTheme() {#getMasterTheme--}
```
public final IMmartTheme getMasterTheme()
```

Retourneert master-thema. Alleen-lezen [IMasterTheme](../../com.aspose.slides/imastertheme).

--------------------

> ```
> The following examples shows how to change a theme effect by altering parts of elements of PowerPoint Presentation.
>  
>  //Instantieer een presentatie-object dat een presentatie-bestand vertegenwoordigt
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

Slaat alle dia's van een presentatie op naar een bestand met het opgegeven formaat.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| fname | java.lang.String | Pad naar het te maken bestand. |
| format | int | Formaat van de geëxporteerde gegevens. |

### save(OutputStream stream, int format) {#save-java.io.OutputStream-int-}
```
public final void save(OutputStream stream, int format)
```

Slaat alle dia's van een presentatie op naar een stream in het opgegeven formaat.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| stream | java.io.OutputStream | Uitvoerstroom. |
| format | int | Formaat van de geëxporteerde gegevens. |

### save(String fname, int format, ISaveOptions options) {#save-java.lang.String-int-com.aspose.slides.ISaveOptions-}
```
public final void save(String fname, int format, ISaveOptions options)
```

Slaat alle dia's van een presentatie op naar een bestand met het opgegeven formaat en met extra opties.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| fname | java.lang.String | Pad naar het te maken bestand. |
| format | int | Formaat van de geëxporteerde gegevens. |
| options | [ISaveOptions](../../com.aspose.slides/isaveoptions) | Extra formaatopties. |

### save(OutputStream stream, int format, ISaveOptions options) {#save-java.io.OutputStream-int-com.aspose.slides.ISaveOptions-}
```
public final void save(OutputStream stream, int format, ISaveOptions options)
```

Slaat alle dia's van een presentatie op naar een stream in het opgegeven formaat en met extra opties.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| stream | java.io.OutputStream | Uitvoerstroom. |
| format | int | Formaat van de geëxporteerde gegevens. |
| options | [ISaveOptions](../../com.aspose.slides/isaveoptions) | Extra formaatopties. |

### save(IXamlOptions options) {#save-com.aspose.slides.IXamlOptions-}
```
public final void save(IXamlOptions options)
```

Slaat alle dia's van een presentatie op naar een reeks bestanden die XAML-opmaak vertegenwoordigen.

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

Retourneert Image-objecten voor alle dia's van een presentatie.

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

Retourneert een Thumbnail-Image-object voor gespecificeerde dia's van een presentatie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Tiff-opties. |
| slides | int[] | Array met dia-posities, beginnend bij 1. |

**Retourneert:**
com.aspose.slides.IImage[] - Image-objecten.
### getImages(IRenderingOptions options, float scaleX, float scaleY) {#getImages-com.aspose.slides.IRenderingOptions-float-float-}
```
public final IImage[] getImages(IRenderingOptions options, float scaleX, float scaleY)
```

Retourneert een Thumbnail-Image-object voor alle dia's van een presentatie met aangepaste schaal.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Tiff-opties. |
| scaleX | float | De waarde waarmee de thumbnail in de x-as wordt geschaald. |
| scaleY | float | De waarde waarmee de thumbnail in de y-as wordt geschaald. |

**Retourneert:**
com.aspose.slides.IImage[] - Image-objecten.
### getImages(IRenderingOptions options, int[] slides, float scaleX, float scaleY) {#getImages-com.aspose.slides.IRenderingOptions-int---float-float-}
```
public final IImage[] getImages(IRenderingOptions options, int[] slides, float scaleX, float scaleY)
```

Retourneert een Thumbnail-Image-object voor gespecificeerde dia's van een presentatie met aangepaste schaal.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Tiff-opties. |
| slides | int[] | Array met dia-posities, beginnend bij 1. |
| scaleX | float | De waarde waarmee de thumbnail in de x-as wordt geschaald. |
| scaleY | float | De waarde waarmee de thumbnail in de y-as wordt geschaald. |

**Retourneert:**
com.aspose.slides.IImage[] - Image-objecten.
### getImages(IRenderingOptions options, Size imageSize) {#getImages-com.aspose.slides.IRenderingOptions-com.aspose.slides.android.Size-}
```
public final IImage[] getImages(IRenderingOptions options, Size imageSize)
```

Retourneert een Thumbnail-Image-object voor alle dia's van een presentatie met opgegeven grootte.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Tiff-opties. |
| imageSize | [Size](../../com.aspose.slides.android/size) | Grootte van de te maken afbeelding. |

**Retourneert:**
com.aspose.slides.IImage[] - Image-objecten.
### getImages(IRenderingOptions options, int[] slides, Size imageSize) {#getImages-com.aspose.slides.IRenderingOptions-int---com.aspose.slides.android.Size-}
```
public final IImage[] getImages(IRenderingOptions options, int[] slides, Size imageSize)
```

Retourneert een Thumbnail-Image-object voor gespecificeerde dia's van een presentatie met opgegeven grootte.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Tiff-opties. |
| slides | int[] | Array met dia-posities, beginnend bij 1. |
| imageSize | [Size](../../com.aspose.slides.android/size) | Grootte van de te maken afbeelding. |

**Retourneert:**
com.aspose.slides.IImage[] - Image-objecten.
### save(String fname, int[] slides, int format) {#save-java.lang.String-int---int-}
```
public final void save(String fname, int[] slides, int format)
```

Slaat gespecificeerde dia's van een presentatie op naar een bestand met het opgegeven formaat en behoudt paginanummers.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| fname | java.lang.String | Pad naar het te maken bestand. |
| slides | int[] | Array met dia-posities, beginnend bij 1. |
| format | int | Formaat van de geëxporteerde gegevens. |

### save(String fname, int[] slides, int format, ISaveOptions options) {#save-java.lang.String-int---int-com.aspose.slides.ISaveOptions-}
```
public final void save(String fname, int[] slides, int format, ISaveOptions options)
```

Slaat gespecificeerde dia's van een presentatie op naar een bestand met het opgegeven formaat en behoudt paginanummers.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| fname | java.lang.String | Pad naar het te maken bestand. |
| slides | int[] | Array met dia-posities, beginnend bij 1. |
| format | int | Formaat van de geëxporteerde gegevens. |
| options | [ISaveOptions](../../com.aspose.slides/isaveoptions) | Extra formaatopties. |

### save(OutputStream stream, int[] slides, int format) {#save-java.io.OutputStream-int---int-}
```
public final void save(OutputStream stream, int[] slides, int format)
```

Slaat gespecificeerde dia's van een presentatie op naar een stream in het opgegeven formaat en behoudt paginanummers.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| stream | java.io.OutputStream | Uitvoerstroom. |
| slides | int[] | Array met dia-posities, beginnend bij 1. |
| format | int | Formaat van de geëxporteerde gegevens. |

### save(OutputStream stream, int[] slides, int format, ISaveOptions options) {#save-java.io.OutputStream-int---int-com.aspose.slides.ISaveOptions-}
```
public final void save(OutputStream stream, int[] slides, int format, ISaveOptions options)
```

Slaat gespecificeerde dia's van een presentatie op naar een stream in het opgegeven formaat en behoudt paginanummers.

--------------------

> ```
> The following example shows how to convert PowerPoint to PNG.
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      for (int index = 0; index < pres.getSlides().size(); index++) {
>          ISlide slide = pres.getSlides().get_Item(index);
>          FileOutputStream out = new FileOutputStream("slide_" + index + ".png");
>          slide.getThumbnail().compress(android.graphics.Bitmap.CompressFormat.PNG, 100, out);
>          out.flush();
>          out.close();
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
>          FileOutputStream out = new FileOutputStream("slide_" + index + ".png");
>          slide.getThumbnail(scaleX, scaleY).compress(android.graphics.Bitmap.CompressFormat.PNG, 100, out);
>          out.flush();
>          out.close();
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
>      com.aspose.slides.android.Size size = new com.aspose.slides.android.Size(960, 720);
>      for (int index = 0; index < pres.getSlides().size(); index++) {
>          ISlide slide = pres.getSlides().get_Item(index);
>          FileOutputStream out = new FileOutputStream("slide_" + index + ".png");
>          slide.getThumbnail(size).compress(android.graphics.Bitmap.CompressFormat.PNG, 100, out);
>          out.flush();
>          out.close();
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
| slides | int[] | Array met dia-posities, beginnend bij 1. |
| format | int | Formaat van de geëxporteerde gegevens. |
| options | [ISaveOptions](../../com.aspose.slides/isaveoptions) | Extra formaatopties. |

### joinPortionsWithSameFormatting() {#joinPortionsWithSameFormatting--}
```
public final void joinPortionsWithSameFormatting()
```

Voegt runs met dezelfde opmaak samen in alle alinea’s in alle toegestane vormen in alle dia’s.

### dispose() {#dispose--}
```
public final void dispose()
```

Geeft alle bronnen vrij die door dit Presentation-object worden gebruikt.

### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

Retourneert de bovenliggende presentatie van een tekst. Alleen-lezen [IPresentation](../../com.aspose.slides/ipresentation).

**Retourneert:**
[IPresentation](../../com.aspose.slides/ipresentation)
### highlightText(String text, Integer highlightColor) {#highlightText-java.lang.String-java.lang.Integer-}
```
public final void highlightText(String text, Integer highlightColor)
```

Markeert alle overeenkomsten van de voorbeeldtekst met de opgegeven kleur.

--------------------

> ```
> The following code sample shows how to highlight text in a PowerPoint presentation.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      // markeert alle afzonderlijke 'the' voorkomens
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
| highlightColor | java.lang.Integer | De kleur om de tekst te markeren. |

### highlightText(String text, Integer highlightColor, ITextSearchOptions options, IFindResultCallback callback) {#highlightText-java.lang.String-java.lang.Integer-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-}
```
public final void highlightText(String text, Integer highlightColor, ITextSearchOptions options, IFindResultCallback callback)
```

Markeert alle overeenkomsten van de voorbeeldtekst met de opgegeven kleur.

--------------------

> ```
> The following code sample shows how to highlight text in a PowerPoint presentation.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      // markeert alle afzonderlijke 'the' voorkomens
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
| highlightColor | java.lang.Integer | De kleur om de tekst te markeren. |
| options | [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions) | Tekstzoek-opties [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions). |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | Callback-object voor het ontvangen van zoekresultaten [IFindResultCallback](../../com.aspose.slides/ifindresultcallback). |

### highlightRegex(Pattern regex, Integer highlightColor, IFindResultCallback callback) {#highlightRegex-java.util.regex.Pattern-java.lang.Integer-com.aspose.slides.IFindResultCallback-}
```
public final void highlightRegex(Pattern regex, Integer highlightColor, IFindResultCallback callback)
```

Markeert alle overeenkomsten van de reguliere expressie met de opgegeven kleur.

--------------------

> ```
> The following code sample shows how to highlight text in a PowerPoint Presentation using a regular expression.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      Pattern regex = Pattern.compile("\\b[^\\s]{10,}\\b");
>      // markeert alle woorden met 10 tekens of langer
>      presentation.highlightRegex(regex, Color.BLUE, null);
>      presentation.save("SomePresentation-out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| regex | java.util.regex.Pattern | De reguliere expressie java.util.regex.Pattern om de te markeren tekenreeksen te verkrijgen. |
| highlightColor | java.lang.Integer | De kleur om de tekst te markeren. |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | Callback-object voor het ontvangen van zoekresultaten [IFindResultCallback](../../com.aspose.slides/ifindresultcallback). |

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
>      // Vervang alle afzonderlijke 'the' voorkomens door '***'
>      presentation.replaceText("the", "***", textSearchOptions, null);
>      presentation.save("SomePresentation-out2.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| oldText | java.lang.String | De te vervangen tekenreeks. |
| newText | java.lang.String | De tekenreeks waarmee alle voorkomens van oldText worden vervangen. |
| options | [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions) | Tekstzoek-opties [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions). |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | Callback-object voor het ontvangen van zoekresultaten [IFindResultCallback](../../com.aspose.slides/ifindresultcallback). |

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
| regex | java.util.regex.Pattern | De reguliere expressie java.util.regex.Pattern om de te vervangen tekenreeksen te verkrijgen. |
| newText | java.lang.String | De tekenreeks waarmee alle voorkomens van de te vervangen tekenreeksen worden vervangen. |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | Callback-object voor het ontvangen van zoekresultaten [IFindResultCallback](../../com.aspose.slides/ifindresultcallback). |