---
title: Presentation
second_title: Aspose.Slides för Java API-referens
description: Representerar en Microsoft PowerPoint-presentation.
type: docs
url: /sv/com.aspose.slides/presentation/
---
**Arv:**  
java.lang.Object

**Alla implementerade gränssnitt:**  
[com.aspose.slides.IPresentation](../../com.aspose.slides/ipresentation), com.aspose.slides.IDOMObject  
```
public final class Presentation implements IPresentation, IDOMObject
```

Representerar en Microsoft PowerPoint-presentation.

--------------------

> ```
> The following example shows how to create PowerPoint Presentation.
>   
>  // Instansiera ett Presentation-objekt som representerar en presentationsfil
>  Presentation pres = new Presentation();
>  try {
>      // Hämta den första bilden
>      ISlide slide = pres.getSlides().get_Item(0);
>      // Lägg till en autoshape av typen linje
>      slide.getShapes().addAutoShape(ShapeType.Line, 50, 150, 300, 0);
>      // Spara presentationsfilen.
>      pres.save("NewPresentation_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>   
>   The following example shows how to open and save Presentation.
>   
>  // Läs in någon stödjande fil i Presentation e.g. ppt, pptx, odp etc.
>  Presentation pres = new Presentation("Sample.odp");
>  try {
>      // Spara presentationsfilen.
>      pres.save("OutputPresenation.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [Presentation()](#Presentation--) | Denna konstruktor skapar en ny presentation från början. |
| [Presentation(LoadOptions loadOptions)](#Presentation-com.aspose.slides.LoadOptions-) | Denna konstruktor skapar en ny presentation från början. |
| [Presentation(InputStream stream)](#Presentation-java.io.InputStream-) | Denna konstruktor är den primära mekanismen för att läsa en befintlig Presentation. |
| [Presentation(InputStream stream, LoadOptions loadOptions)](#Presentation-java.io.InputStream-com.aspose.slides.LoadOptions-) | Denna konstruktor är den primära mekanismen för att läsa en befintlig Presentation. |
| [Presentation(String file)](#Presentation-java.lang.String-) | Denna konstruktor får en källfilssökväg varifrån innehållet i Presentationen läses. |
| [Presentation(String file, LoadOptions loadOptions)](#Presentation-java.lang.String-com.aspose.slides.LoadOptions-) | Denna konstruktor får en källfilssökväg varifrån innehållet i Presentationen läses. |

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getCurrentDateTime()](#getCurrentDateTime--) | Returnerar eller anger datum och tid som kommer att ersätta innehållet i datum/tidsfält. |
| [setCurrentDateTime(Date value)](#setCurrentDateTime-java.util.Date-) | Returnerar eller anger datum och tid som kommer att ersätta innehållet i datum/tidsfält. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | Returnerar den faktiska HeaderFooter-hanteraren. |
| [getProtectionManager()](#getProtectionManager--) | Hämtar hanteraren för behörigheterna för denna presentation. |
| [getSlides()](#getSlides--) | Returnerar en lista med alla bilder som definierats i presentationen. |
| [getSections()](#getSections--) | Returnerar en lista med alla bildsektioner som definierats i presentationen. |
| [getSlideSize()](#getSlideSize--) | Returnerar objektet för bildstorlek. |
| [getNotesSize()](#getNotesSize--) | Returnerar objektet för notbildens storlek. |
| [getLayoutSlides()](#getLayoutSlides--) | Returnerar en lista med alla layout-bilder som definierats i presentationen. |
| [getMasters()](#getMasters--) | Returnerar en lista med alla master-bilder som definierats i presentationen. |
| [getMasterNotesSlideManager()](#getMasterNotesSlideManager--) | Returnerar notmaster-hanteraren. |
| [getMasterHandoutSlideManager()](#getMasterHandoutSlideManager--) | Returnerar handout-master-hanteraren. |
| [getFontsManager()](#getFontsManager--) | Returnerar teckensnittshanteraren. |
| [getDefaultTextStyle()](#getDefaultTextStyle--) | Returnerar standardtextstilen för former. |
| [getCommentAuthors()](#getCommentAuthors--) | Returnerar samlingen av kommentar-författare. |
| [getDocumentProperties()](#getDocumentProperties--) | Returnerar DocumentProperties-objektet som innehåller standard- och anpassade dokumentegenskaper. |
| [getImages()](#getImages--) | Returnerar samlingen av alla bilder i presentationen. |
| [getAudios()](#getAudios--) | Returnerar samlingen av alla inbäddade ljudfiler i presentationen. |
| [getVideos()](#getVideos--) | Returnerar samlingen av alla inbäddade videofiler i presentationen. |
| [getSlideShowSettings()](#getSlideShowSettings--) | Returnerar bildspelsinställningarna för presentationen. |
| [getDigitalSignatures()](#getDigitalSignatures--) | Returnerar samlingen av signaturer som används för att signera presentationen. |
| [getCustomData()](#getCustomData--) | Returnerar presentationens anpassade data. |
| [getAllCustomXmlParts()](#getAllCustomXmlParts--) | Returnerar alla anpassade dataparts i presentationen. |
| [getVbaProject()](#getVbaProject--) | Hämtar eller anger VBA-projekt med presentationsmakron. |
| [setVbaProject(IVbaProject value)](#setVbaProject-com.aspose.slides.IVbaProject-) | Hämtar eller anger VBA-projekt med presentationsmakron. |
| [getHyperlinkQueries()](#getHyperlinkQueries--) | Tillhandahåller enkel åtkomst till alla hyperlänkar som finns i alla presentationsbilder (inte i master-, layout- eller notbilder). |
| [getViewProperties()](#getViewProperties--) | Hämtar presentationsomfattande visningsegenskaper. |
| [getFirstSlideNumber()](#getFirstSlideNumber--) | Representerar det första bildnumret i presentationen |
| [setFirstSlideNumber(int value)](#setFirstSlideNumber-int-) | Representerar det första bildnumret i presentationen |
| [getSensitivityLabels()](#getSensitivityLabels--) | Returnerar samlingen av känslighetsetiketter som tillämpats på presentationsdokumentet. |
| [getSlideById(long id)](#getSlideById-long-) | Returnerar en Slide, MasterSlide eller LayoutSlide via Id. |
| [getSourceFormat()](#getSourceFormat--) | Returnerar information om från vilket format presentationen laddades. |
| [getMasterTheme()](#getMasterTheme--) | Returnerar mastertema. |
| [save(String fname, int format)](#save-java.lang.String-int-) | Sparar alla bilder i en presentation till en fil med det angivna formatet. |
| [save(OutputStream stream, int format)](#save-java.io.OutputStream-int-) | Sparar alla bilder i en presentation till en ström i det angivna formatet. |
| [save(String fname, int format, ISaveOptions options)](#save-java.lang.String-int-com.aspose.slides.ISaveOptions-) | Sparar alla bilder i en presentation till en fil med det angivna formatet och med extra alternativ. |
| [save(OutputStream stream, int format, ISaveOptions options)](#save-java.io.OutputStream-int-com.aspose.slides.ISaveOptions-) | Sparar alla bilder i en presentation till en ström i det angivna formatet och med extra alternativ. |
| [save(IXamlOptions options)](#save-com.aspose.slides.IXamlOptions-) | Sparar alla bilder i en presentation till ett set av filer som representerar XAML-markup. |
| [getImages(IRenderingOptions options)](#getImages-com.aspose.slides.IRenderingOptions-) | Returnerar Image-objekt för alla bilder i en presentation. |
| [getImages(IRenderingOptions options, int[] slides)](#getImages-com.aspose.slides.IRenderingOptions-int---) | Returnerar miniatyrbilder för angivna bilder i en presentation. |
| [getImages(IRenderingOptions options, float scaleX, float scaleY)](#getImages-com.aspose.slides.IRenderingOptions-float-float-) | Returnerar miniatyrbilder för alla bilder i en presentation med anpassad skalning. |
| [getImages(IRenderingOptions options, int[] slides, float scaleX, float scaleY)](#getImages-com.aspose.slides.IRenderingOptions-int---float-float-) | Returnerar miniatyrbilder för angivna bilder i en presentation med anpassad skalning. |
| [getImages(IRenderingOptions options, Dimension imageSize)](#getImages-com.aspose.slides.IRenderingOptions-java.awt.Dimension-) | Returnerar miniatyrbilder för alla bilder i en presentation med angiven storlek. |
| [getImages(IRenderingOptions options, int[] slides, Dimension imageSize)](#getImages-com.aspose.slides.IRenderingOptions-int---java.awt.Dimension-) | Returnerar miniatyrbilder för angivna bilder i en presentation med angiven storlek. |
| [save(String fname, int[] slides, int format)](#save-java.lang.String-int---int-) | Sparar angivna bilder i en presentation till en fil med det angivna formatet med bevarande av sidnummer. |
| [save(String fname, int[] slides, int format, ISaveOptions options)](#save-java.lang.String-int---int-com.aspose.slides.ISaveOptions-) | Sparar angivna bilder i en presentation till en fil med det angivna formatet med bevarande av sidnummer. |
| [save(OutputStream stream, int[] slides, int format)](#save-java.io.OutputStream-int---int-) | Sparar angivna bilder i en presentation till en ström i det angivna formatet med bevarande av sidnummer. |
| [save(OutputStream stream, int[] slides, int format, ISaveOptions options)](#save-java.io.OutputStream-int---int-com.aspose.slides.ISaveOptions-) | Sparar angivna bilder i en presentation till en ström i det angivna formatet med bevarande av sidnummer. |
| [joinPortionsWithSameFormatting()](#joinPortionsWithSameFormatting--) | Sammanfogar körningar med samma formatering i alla stycken i alla accepterade former i alla bilder. |
| [dispose()](#dispose--) | Frigör alla resurser som används av detta Presentation-objekt. |
| [getPresentation()](#getPresentation--) | Returnerar den överordnade presentationen för en text. |
| [highlightText(String text, Color highlightColor)](#highlightText-java.lang.String-java.awt.Color-) | Markerar alla träffar av exempeltexten med den angivna färgen. |
| [highlightText(String text, Color highlightColor, ITextSearchOptions options, IFindResultCallback callback)](#highlightText-java.lang.String-java.awt.Color-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-) | Markerar alla träffar av exempeltexten med den angivna färgen. |
| [highlightRegex(Pattern regex, Color highlightColor, IFindResultCallback callback)](#highlightRegex-java.util.regex.Pattern-java.awt.Color-com.aspose.slides.IFindResultCallback-) | Markerar alla träffar av det reguljära uttrycket med den angivna färgen. |
| [replaceText(String oldText, String newText, ITextSearchOptions options, IFindResultCallback callback)](#replaceText-java.lang.String-java.lang.String-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-) | Ersätter alla förekomster av den angivna texten med en annan angiven text. |
| [replaceRegex(Pattern regex, String newText, IFindResultCallback callback)](#replaceRegex-java.util.regex.Pattern-java.lang.String-com.aspose.slides.IFindResultCallback-) | Ersätter alla träffar av det reguljära uttrycket med den angivna strängen. |

### Presentation() {#Presentation--}
```
public Presentation()
```

Denna konstruktor skapar en ny presentation från början. Den skapade presentationen har en tom bild.

### Presentation(LoadOptions loadOptions) {#Presentation-com.aspose.slides.LoadOptions-}
```
public Presentation(LoadOptions loadOptions)
```

Denna konstruktor skapar en ny presentation från början. Den skapade presentationen har en tom bild.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| loadOptions | [LoadOptions](../../com.aspose.slides/loadoptions) | Ytterligare laddningsalternativ. |

### Presentation(InputStream stream) {#Presentation-java.io.InputStream-}
```
public Presentation(InputStream stream)
```

Denna konstruktor är den primära mekanismen för att läsa en befintlig Presentation.

--------------------

> ```
> FileInputStream fis = new FileInputStream("demo.pptx");
>  Presentation pres = new Presentation(fis);
>  fis.close();
> ```


**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| stream | java.io.InputStream | Ingångsström. |

### Presentation(InputStream stream, LoadOptions loadOptions) {#Presentation-java.io.InputStream-com.aspose.slides.LoadOptions-}
```
public Presentation(InputStream stream, LoadOptions loadOptions)
```

Denna konstruktor är den primära mekanismen för att läsa en befintlig Presentation.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| stream | java.io.InputStream | Ingångsström. |
| loadOptions | [LoadOptions](../../com.aspose.slides/loadoptions) | Ytterligare laddningsalternativ. |

### Presentation(String file) {#Presentation-java.lang.String-}
```
public Presentation(String file)
```

Denna konstruktor får en källfilssökväg varifrån innehållet i Presentationen läses.

--------------------

> ```
> Presentation pres = new Presentation("demo.pptx");
> ```


**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| file | java.lang.String | Indatafil. |

### Presentation(String file, LoadOptions loadOptions) {#Presentation-java.lang.String-com.aspose.slides.LoadOptions-}
```
public Presentation(String file, LoadOptions loadOptions)
```

Denna konstruktor får en källfilssökväg varifrån innehållet i Presentationen läses.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| file | java.lang.String | Indatafil. |
| loadOptions | [LoadOptions](../../com.aspose.slides/loadoptions) | Ytterligare laddningsalternativ. |

### getCurrentDateTime() {#getCurrentDateTime--}
```
public final Date getCurrentDateTime()
```

Returnerar eller anger datum och tid som kommer att ersätta innehållet i datum/tidsfält. Tiden för detta Presentation-objekts skapande som standard. Läs/skriv java.util.Date.

**Returnerar:**
java.util.Date

### setCurrentDateTime(Date value) {#setCurrentDateTime-java.util.Date-}
```
public final void setCurrentDateTime(Date value)
```

Returnerar eller anger datum och tid som kommer att ersätta innehållet i datum/tidsfält. Tiden för detta Presentation-objekts skapande som standard. Läs/skriv java.util.Date.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | java.util.Date |  |

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Returnerar Parent_Immediate-objektet. Skrivskyddad IDOMObject.

**Returnerar:**
com.aspose.slides.IDOMObject

### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public final IPresentationHeaderFooterManager getHeaderFooterManager()
```

Returnerar den faktiska HeaderFooter-hanteraren. Skrivskyddad [IPresentationHeaderFooterManager](../../com.aspose.slides/ipresentationheaderfootermanager).

--------------------

> ```
> The following example shows how to set footer visibility inside Slide of PowerPoint Presentation.
>  
>  Presentation pres = new Presentation("presentation.ppt");
>  try
>  {
>      IBaseSlideHeaderFooterManager headerFooterManager = pres.getSlides().get_Item(0).getHeaderFooterManager();
>      if (!headerFooterManager.isFooterVisible()) // Egenskapen IsFooterVisible används för att indikera att en bildfotplats inte finns.
>      {
>          headerFooterManager.setFooterVisibility(true); // Metoden SetFooterVisibility används för att göra en bildfotplats synlig.
>      }
>      if (!headerFooterManager.isSlideNumberVisible()) // Egenskapen IsSlideNumberVisible används för att indikera att en bildsidnummerplats inte finns.
>      {
>          headerFooterManager.setSlideNumberVisibility(true); // Metoden SetSlideNumberVisibility används för att göra en bildsidnummerplats synlig.
>      }
>      if (!headerFooterManager.isDateTimeVisible()) // Egenskapen IsDateTimeVisible används för att indikera att en bilddatum-tid-plats inte finns.
>      {
>          headerFooterManager.setDateTimeVisibility(true); // Metoden SetFooterVisibility används för att göra en bilddatum-tid-plats synlig.
>      }
>      headerFooterManager.setFooterText("Footer text"); // Metoden SetFooterText används för att sätta text till bildfotplatsen.
>      headerFooterManager.setDateTimeText("Date and time text"); // Metoden SetDateTimeText används för att sätta text till bildens datum-tid-plats.
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
>      headerFooterManager.setFooterAndChildFootersVisibility(true); // Metoden SetFooterAndChildFootersVisibility används för att göra en master-bild och alla underordnade fotplaceringar synliga.
>      headerFooterManager.setSlideNumberAndChildSlideNumbersVisibility(true); // Metoden SetSlideNumberAndChildSlideNumbersVisibility används för att göra en master-bild och alla underordnade sidnummerplaceringar synliga.
>      headerFooterManager.setDateTimeAndChildDateTimesVisibility(true); // Metoden SetDateTimeAndChildDateTimesVisibility används för att göra en master-bild och alla underordnade datum-tid-placeringar synliga.
> 
>      headerFooterManager.setFooterAndChildFootersText("Footer text"); // Metoden SetFooterAndChildFootersText används för att sätta text till master-bilden och alla underordnade fotplaceringar.
>      headerFooterManager.setDateTimeAndChildDateTimesText("Date and time text"); // Metoden SetDateTimeAndChildDateTimesText används för att sätta text till master-bilden och alla underordnade datum-tid-placeringar.
>  }
>  finally
>  {
>      if (pres != null) pres.dispose();
>  }
> ```


**Returnerar:**
[IPresentationHeaderFooterManager](../../com.aspose.slides/ipresentationheaderfootermanager)

### getProtectionManager() {#getProtectionManager--}
```
public final IProtectionManager getProtectionManager()
```

Hämtar hanteraren för behörigheterna för denna presentation. Skrivskyddad [IProtectionManager](../../com.aspose.slides/iprotectionmanager).

**Returnerar:**
[IProtectionManager](../../com.aspose.slides/iprotectionmanager)

### getSlides() {#getSlides--}
```
public final ISlideCollection getSlides()
```

Returnerar en lista med alla bilder som definierats i presentationen. Skrivskyddad [ISlideCollection](../../com.aspose.slides/islidecollection).

--------------------

> ```
> The following example shows how to set slides' background color of PowerPoint Presentation.
>  
>  // Instansiera Presentation-klassen som representerar presentationsfilen
>  Presentation pres = new Presentation();
>  try
>  {
>      // Ställ in bakgrundsfärgen för den första ISlide till blå
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
>  // Instansiera Presentation-klassen som representerar presentationsfilen
>  Presentation pres = new Presentation("SetImageAsBackground.pptx");
>  try {
>      // Ställ in bakgrunden med bild
>      pres.getSlides().get_Item(0).getBackground().setType(BackgroundType.OwnBackground);
>      pres.getSlides().get_Item(0).getBackground().getFillFormat().setFillType(FillType.Picture);
>      pres.getSlides().get_Item(0).getBackground().getFillFormat().getPictureFillFormat().setPictureFillMode(PictureFillMode.Stretch);
>      // Ställ in bilden
>      BufferedImage img = ImageIO.read(new File("Tulips.jpg"));
>      // Lägg till bilden i presentationens bildsamling
>      IPPImage imgx = pres.getImages().addImage(img);
>      pres.getSlides().get_Item(0).getBackground().getFillFormat().getPictureFillFormat().getPicture().setImage(imgx);
>      // Skriv presentationen till disk
>      pres.save("ContentBG_Img_out.pptx", SaveFormat.Pptx);
>  } catch (IOException e) { }
>  finally
>  {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to add slide transition Presentation.
>  
>  // Instansiera Presentation-klassen för att läsa in källpresentationsfilen
>  Presentation pres = new Presentation("AccessSlides.pptx");
>  try
>  {
>      // Applicera cirkelövergång på bild 1
>      pres.getSlides().get_Item(0).getSlideShowTransition().setType(TransitionType.Circle);
>      // Applicera kamtypens övergång på bild 2
>      pres.getSlides().get_Item(1).getSlideShowTransition().setType(TransitionType.Comb);
>      // Skriv presentationen till disk
>      pres.save("SampleTransition_out.pptx", SaveFormat.Pptx);
>  }
>  finally
>  {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to add advanced slide Transition.
>  
>  // Instansiera Presentation-klassen som representerar en presentationsfil
>  Presentation pres = new Presentation("BetterSlideTransitions.pptx");
>  try
>  {
>      // Applicera cirkelövergång på bild 1
>      pres.getSlides().get_Item(0).getSlideShowTransition().setType(TransitionType.Circle);
>      // Ställ in övergångstiden till 3 sekunder
>      pres.getSlides().get_Item(0).getSlideShowTransition().setAdvanceOnClick(true);
>      pres.getSlides().get_Item(0).getSlideShowTransition().setAdvanceAfterTime(3000);
>      // Applicera kamtypens övergång på bild 2
>      pres.getSlides().get_Item(1).getSlideShowTransition().setType(TransitionType.Comb);
>      // Ställ in övergångstiden till 5 sekunder
>      pres.getSlides().get_Item(1).getSlideShowTransition().setAdvanceOnClick(true);
>      pres.getSlides().get_Item(1).getSlideShowTransition().setAdvanceAfterTime(5000);
>      // Applicera zoom-övergång på bild 3
>      pres.getSlides().get_Item(2).getSlideShowTransition().setType(TransitionType.Zoom);
>      // Ställ in övergångstiden till 7 sekunder
>      pres.getSlides().get_Item(2).getSlideShowTransition().setAdvanceOnClick(true);
>      pres.getSlides().get_Item(2).getSlideShowTransition().setAdvanceAfterTime(7000);
>      // Skriv presentationen till disk
>      pres.save("SampleTransition_out.pptx", SaveFormat.Pptx);
>  }
>  finally
>  {
>      if (pres != null) pres.dispose();
>  }
> ```


**Returnerar:**
[ISlideCollection](../../com.aspose.slides/islidecollection)

### getSections() {#getSections--}
```
public final ISectionCollection getSections()
```

Returnerar en lista med alla bildsektioner som definierats i presentationen. Skrivskyddad [ISectionCollection](../../com.aspose.slides/isectioncollection).

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
>      // section1 avslutas vid newSlide2 och därefter startar section2
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


**Returnerar:**
[ISectionCollection](../../com.aspose.slides/isectioncollection)

### getSlideSize() {#getSlideSize--}
```
public final ISlideSize getSlideSize()
```

Returnerar objektet för bildstorlek. Skrivskyddad [ISlideSize](../../com.aspose.slides/islidesize).

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
>  // Instansiera ett Presentation-objekt som representerar en presentationsfil
>  Presentation presentation = new Presentation("AccessSlides.pptx");
>  try {
>      Presentation auxPresentation = new Presentation();
>      try {
>          ISlide slide = presentation.getSlides().get_Item(0);
>          // Ställ in bildstorleken för genererade presentationer till den i källan
>          presentation.getSlideSize().setSize(540, 720, SlideSizeScaleType.EnsureFit); // Metoden SetSize används för att ställa in bildstorlek med skalning av innehåll för att säkerställa passning
>          presentation.getSlideSize().setSize(SlideSizeType.A4Paper, SlideSizeScaleType.Maximize); // Metoden SetSize används för att ställa in bildstorlek med maximal storlek på innehållet
>          // Spara presentationen till disk
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
>      pres.getSlideSize().setSize(780, 540, SlideSizeScaleType.DoNotScale); // A4-pappersstorlek
>      pres.save("pres-a4-slide-size.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Returnerar:**
[ISlideSize](../../com.aspose.slides/islidesize)

### getNotesSize() {#getNotesSize--}
```
public final INotesSize getNotesSize()
```

Returnerar objektet för notbildens storlek. Skrivskyddad [INotesSize](../../com.aspose.slides/inotessize).

**Returnerar:**
[INotesSize](../../com.aspose.slides/inotessize)

### getLayoutSlides() {#getLayoutSlides--}
```
public final IGlobalLayoutSlideCollection getLayoutSlides()
```

Returnerar en lista med alla layout-bilder som definierats i presentationen. Skrivskyddad [IGlobalLayoutSlideCollection](../../com.aspose.slides/igloballayoutslidecollection).

--------------------

Du kan komma åt ett alternativt API för att lägga till/infoga/ta bort/klona layout-bilder genom att använda IMasterSlide.LayoutSlides-egenskapen.

**Returnerar:**
[IGlobalLayoutSlideCollection](../../com.aspose.slides/igloballayoutslidecollection)

### getMasters() {#getMasters--}
```
public final IMasterSlideCollection getMasters()
```

Returnerar en lista med alla master-bilder som definierats i presentationen. Skrivskyddad [IMasterSlideCollection](../../com.aspose.slides/imasterslidecollection).

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
>  // Instansiera Presentation-klassen som representerar presentationsfilen
>  Presentation pres = new Presentation();
>  try
>  {
>      // Ställ in bakgrundsfärgen för Master-ISlide till skogsgrön
>      pres.getMasters().get_Item(0).getBackground().setType(BackgroundType.OwnBackground);
>      pres.getMasters().get_Item(0).getBackground().getFillFormat().setFillType(FillType.Solid);
>      pres.getMasters().get_Item(0).getBackground().getFillFormat().getSolidFillColor().setColor(Color.GREEN);
>      // Skriv presentationen till disk
>      pres.save("SetSlideBackgroundMaster_out.pptx", SaveFormat.Pptx);
>  }
>  finally
>  {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following examples shows how to add slide layout to PowerPoint Presentation.
>  
>  // Instansiera Presentation-klassen som representerar presentationsfilen
>  Presentation presentation = new Presentation("AccessSlides.pptx");
>  try
>  {
>      // Försök att söka efter layout-bildtyp
>      IMasterLayoutSlideCollection layoutSlides = presentation.getMasters().get_Item(0).getLayoutSlides();
>      ILayoutSlide layoutSlide = null;
>      if (layoutSlides.getByType(SlideLayoutType.TitleAndObject) != null)
>          layoutSlide = layoutSlides.getByType(SlideLayoutType.TitleAndObject);
>      else
>          layoutSlide = layoutSlides.getByType(SlideLayoutType.Title);
> 
>      if (layoutSlide == null)
>      {
>          // Situationen när en presentation inte innehåller vissa typer av layouter.
>          // presentationsfilen innehåller endast tomma och anpassade layouttyper.
>          // Men layoutbilder med anpassade typer har olika bildnamn,
>          // såsom "Title", "Title and Content" osv. Och det är möjligt att använda dessa
>          // namn för val av layoutbilder.
>          // Det är också möjligt att använda uppsättningen av platshållartyper. Till exempel,
>          // Titelfliken bör bara ha typ av Titel-platshållare, osv.
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
>      // Lägg till en tom bild med den tillagda layout-bilden
>      presentation.getSlides().insertEmptySlide(0, layoutSlide);
>      // Save presentation
>      presentation.save("AddLayoutSlides_out.pptx", SaveFormat.Pptx);
>  }
>  finally
>  {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Returnerar:**
[IMasterSlideCollection](../../com.aspose.slides/imasterslidecollection)

### getMasterNotesSlideManager() {#getMasterNotesSlideManager--}
```
public final IMasterNotesSlideManager getMasterNotesSlideManager()
```

Returnerar notmaster-hanteraren. Skrivskyddad [IMasterNotesSlideManager](../../com.aspose.slides/imasternotesslidemanager).

**Returnerar:**
[IMasterNotesSlideManager](../../com.aspose.slides/imasternotesslidemanager)

### getMasterHandoutSlideManager() {#getMasterHandoutSlideManager--}
```
public final IMasterHandoutSlideManager getMasterHandoutSlideManager()
```

Returnerar handout-master-hanteraren. Skrivskyddad [IMasterHandoutSlideManager](../../com.aspose.slides/imasterhandoutslidemanager).

**Returnerar:**
[IMasterHandoutSlideManager](../../com.aspose.slides/imasterhandoutslidemanager)

### getFontsManager() {#getFontsManager--}
```
public final IFontsManager getFontsManager()
```

Returnerar teckensnittshanteraren. Skrivskyddad [IFontsManager](../../com.aspose.slides/ifontsmanager).

--------------------

> ```
> The following example shows how to add embedded fonts to PowerPoint Presentation.
>  
>  // Läs in presentationen
>  Presentation pres = new Presentation("Fonts.pptx");
>  try {
>      // Läs in källfonten som ska ersättas
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
>      // Spara presentationen
>      pres.save("AddEmbeddedFont_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Returnerar:**
[IFontsManager](../../com.aspose.slides/ifontsmanager)

### getDefaultTextStyle() {#getDefaultTextStyle--}
```
public final ITextStyle getDefaultTextStyle()
```

Returnerar standardtextstilen för former. Skrivskyddad [ITextStyle](../../com.aspose.slides/itextstyle).

**Returnerar:**
[ITextStyle](../../com.aspose.slides/itextstyle)

### getCommentAuthors() {#getCommentAuthors--}
```
public final ICommentAuthorCollection getCommentAuthors()
```

Returnerar samlingen av kommentar-författare. Skrivskyddad [ICommentAuthorCollection](../../com.aspose.slides/icommentauthorcollection).

**Returnerar:**
[ICommentAuthorCollection](../../com.aspose.slides/icommentauthorcollection)

### getDocumentProperties() {#getDocumentProperties--}
```
public final IDocumentProperties getDocumentProperties()
```

Returnerar DocumentProperties-objektet som innehåller standard- och anpassade dokumentegenskaper. Skrivskyddad [IDocumentProperties](../../com.aspose.slides/idocumentproperties).

**Returnerar:**
[IDocumentProperties](../../com.aspose.slides/idocumentproperties)

### getImages() {#getImages--}
```
public final IImageCollection getImages()
```

Returnerar samlingen av alla bilder i presentationen. Skrivskyddad [IImageCollection](../../com.aspose.slides/iimagecollection).

--------------------

> ```
> The following examples shows how to add image as BLOB in PowerPoint Presentation.
>  
>  // creates a new presentation to which the image will be added.
>  Presentation pres = new Presentation();
>  try
>  {
>      // supposed we have the large image file we want to include into the presentation
>      FileInputStream fip = new FileInputStream("large_image.jpg");
>      try
>      {
>          // Let's add the image to the presentation - we choose KeepLocked behavior because we do
>          // NOT intend to access the "largeImage.png" file.
>          IPPImage img = pres.getImages().addImage(fip, LoadingStreamBehavior.KeepLocked);
>          pres.getSlides().get_Item(0).getShapes().addPictureFrame(ShapeType.Rectangle, 0, 0, 300, 200, img);
>          // Saves the presentation. While a large presentation gets outputted, the memory consumption
>          // stays low through the pres object's lifecycle
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
>      // Adds image to presentation
>      IPPImage image = pres.getImages().addImage(Files.readAllBytes(Paths.get("image.png")));
>      // Creates picture frame on slide 1 based on previously added image
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


**Returnerar:**
[IImageCollection](../../com.aspose.slides/iimagecollection)

### getAudios() {#getAudios--}
```
public final IAudioCollection getAudios()
```

Returnerar samlingen av alla inbäddade ljudfiler i presentationen. Skrivskyddad [IAudioCollection](../../com.aspose.slides/iaudiocollection).

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


**Returnerar:**
[IAudioCollection](../../com.aspose.slides/iaudiocollection)

### getVideos() {#getVideos--}
```
public final IVideoCollection getVideos()
```
Returnerar samlingen av alla inbäddade videofiler i presentationen. Skrivskyddad [IVideoCollection](../../com.aspose.slides/ivideocollection).

--------------------

> ```
> The following examples shows how to create embedded Video Frame in a PowerPoint Presentation.
>  
>  // Instansiera Presentation-klassen som representerar PPTX-filen
>  Presentation pres = new Presentation();
>  try {
>      // Hämta den första bilden
>      ISlide sld = pres.getSlides().get_Item(0);
>      // Bädda in video i presentationen
>      IVideo vid = pres.getVideos().addVideo(new FileInputStream("Wildlife.mp4"));
>      // Lägg till videoram
>      IVideoFrame vf = sld.getShapes().addVideoFrame(50, 150, 300, 350, vid);
>      // Ställ in video på videoramen
>      vf.setEmbeddedVideo(vid);
>      // Ställ in uppspelningsläge och volym för videon
>      vf.setPlayMode(VideoPlayModePreset.Auto);
>      vf.setVolume(AudioVolumeMode.Loud);
>      // Skriv PPTX-filen till disk
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
>  // Skapar en ny presentation som videon ska läggas till
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream fileStream = new FileInputStream("veryLargeVideo.avi");
>      try {
>          // Låt oss lägga till videon i presentationen - vi valde KeepLocked-beteendet eftersom vi
>          // inte avser att komma åt filen "veryLargeVideo.avi".
>          IVideo video = pres.getVideos().addVideo(fileStream, LoadingStreamBehavior.KeepLocked);
>          pres.getSlides().get_Item(0).getShapes().addVideoFrame(0, 0, 480, 270, video);
>          // Sparar presentationen. Medan en stor presentation genereras, förblir minnesanvändningen
>          // låg under hela pres-objektets livscykel
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
>  // Låser källfilen och läser INTE in den i minnet
>  loadOptions.getBlobManagementOptions().setPresentationLockingBehavior(PresentationLockingBehavior.KeepLocked);
>  // Skapar en Presentation-instans, låser filen "hugePresentationWithAudiosAndVideos.pptx".
>  Presentation pres = new Presentation("Large  Video File Test1.pptx", loadOptions);
>  try {
>      // Låt oss spara varje video till en fil. För att undvika hög minnesanvändning behöver vi en buffer som kommer att användas
>      // för att överföra data från presentationens videoström till en ström för en ny skapad videofil.
>      byte[] buffer = new byte[81024];
>      // Itererar genom videorna
>      for (int index = 0; index < pres.getVideos().size(); index++) {
>          IVideo video = pres.getVideos().get_Item(index);
>          // Öppnar presentationens videoström. Observera att vi avsiktligt undvek att komma åt egenskaper
>          // som video.BinaryData - eftersom denna egenskap returnerar en bytearray som innehåller hela videon, vilket sedan
>          // får att bytes läses in i minnet. Vi använder video.GetStream, som returnerar en Stream - och läser INTE
>          //  kräver att vi laddar hela videon i minnet.
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
>          // Minnesanvändning kommer att förbli låg oavsett storleken på videon eller presentationen,
>      }
>      // Vid behov kan du tillämpa samma steg för ljudfiler.
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
>      // lägg till videoram
>      IVideoFrame videoFrame = pres.getSlides().get_Item(0).getShapes().addVideoFrame(10, 10, 427, 240, "https://www.youtube.com/embed/" + videoId);
>      videoFrame.setPlayMode(VideoPlayModePreset.Auto);
> 
>      // ladda miniatyrbild
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
>  // Instansiera ett Presentation-objekt som representerar en presentationsfil
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


**Returnerar:**
[IVideoCollection](../../com.aspose.slides/ivideocollection)
### getSlideShowSettings() {#getSlideShowSettings--}
```
public final SlideShowSettings getSlideShowSettings()
```

Returnerar bildspelsinställningarna för presentationen.

**Returnerar:**
[SlideShowSettings](../../com.aspose.slides/slideshowsettings)
### getDigitalSignatures() {#getDigitalSignatures--}
```
public final IDigitalSignatureCollection getDigitalSignatures()
```

Returnerar samlingen av signaturer som används för att signera presentationen. Skrivskyddad [IDigitalSignatureCollection](../../com.aspose.slides/idigitalsignaturecollection).

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


**Returnerar:**
[IDigitalSignatureCollection](../../com.aspose.slides/idigitalsignaturecollection)
### getCustomData() {#getCustomData--}
```
public final ICustomData getCustomData()
```

Returnerar presentationens anpassade data. Skrivskyddad [ICustomData](../../com.aspose.slides/icustomdata).

**Returnerar:**
[ICustomData](../../com.aspose.slides/icustomdata)
### getAllCustomXmlParts() {#getAllCustomXmlParts--}
```
public final ICustomXmlPart[] getAllCustomXmlParts()
```

Returnerar alla anpassade datapartelement i presentationen. Skrivskyddad ICustomXmlPart[].

--------------------

> ```
> The following examples show how to clear all custom xml parts from PowerPoint Presentation.
>  
>  Presentation pres = new Presentation("PresentationWithCustomXml.pptx");
>  try {
>      // Iterera alla anpassade XML-delar
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


**Returnerar:**
com.aspose.slides.ICustomXmlPart[]
### getVbaProject() {#getVbaProject--}
```
public final IVbaProject getVbaProject()
```

Hämtar eller anger VBA-projekt med presentationsmakron. Läs/skriv [IVbaProject](../../com.aspose.slides/ivbaproject).

**Returnerar:**
[IVbaProject](../../com.aspose.slides/ivbaproject)
### setVbaProject(IVbaProject value) {#setVbaProject-com.aspose.slides.IVbaProject-}
```
public final void setVbaProject(IVbaProject value)
```

Hämtar eller anger VBA-projekt med presentationsmakron. Läs/skriv [IVbaProject](../../com.aspose.slides/ivbaproject).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [IVbaProject](../../com.aspose.slides/ivbaproject) |  |
### getHyperlinkQueries() {#getHyperlinkQueries--}
```
public final IHyperlinkQueries getHyperlinkQueries()
```

Tillhandahåller enkel åtkomst till alla hyperlänkar som finns i alla presentationsbilder (ej i master-, layout- eller notbildsidor). Skrivskyddad [IHyperlinkQueries](../../com.aspose.slides/ihyperlinkqueries).

**Returnerar:**
[IHyperlinkQueries](../../com.aspose.slides/ihyperlinkqueries)
### getViewProperties() {#getViewProperties--}
```
public final IViewProperties getViewProperties()
```

Hämtar presentationsövergripande visningsegenskaper. Skrivskyddad [IViewProperties](../../com.aspose.slides/iviewproperties).

**Returnerar:**
[IViewProperties](../../com.aspose.slides/iviewproperties)
### getFirstSlideNumber() {#getFirstSlideNumber--}
```
public final int getFirstSlideNumber()
```

Representerar det första bildnumret i presentationen

**Returnerar:**
int
### setFirstSlideNumber(int value) {#setFirstSlideNumber-int-}
```
public final void setFirstSlideNumber(int value)
```

Representerar det första bildnumret i presentationen

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | int |  |
### getSensitivityLabels() {#getSensitivityLabels--}
```
public final ISensitivityLabelCollection getSensitivityLabels()
```

Returnerar samlingen av känslighetsetiketter som tillämpas på presentationsdokumentet. Skrivskyddad [ISensitivityLabelCollection](../../com.aspose.slides/isensitivitylabelcollection).

--------------------

> ```
> Presentation pres = new Presentation("SomePresentation.pptx");
>  try {
>      ISensitivityLabelCollection sensitivityLabels = pres.getSensitivityLabels();
> 
>      // Skriv ut de tillämpade etiketterna
>      for (ISensitivityLabel sensitivityLabel : sensitivityLabels)
>          System.out.println("Label Id " + sensitivityLabel.getId() + " from Azure AD site " + sensitivityLabel.getSiteId());
> 
>      // Lägg till den nya etiketten
>      String labelIdString = "{xxxxxxxx-xxxx-xxxx-xxxx-xxxxxxxxxxxx}"; // Hämta känslighetsetikettens ID från policyn
>      UUID siteIdGuid = UUID.fromString("{xxxxxxxx-xxxx-xxxx-xxxx-xxxxxxxxxxxx}"); // Hämta Azure AD-platsidentifieraren från policyn
>      ISensitivityLabel label = sensitivityLabels.add(labelIdString, siteIdGuid, true, SensitivityLabelAssignmentType.Privileged);
>      label.getContentMarkTypes().addItem(SensitivityLabelContentType.Footer);
> 
>      pres.save("SensitivityLabel.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Returnerar:**
[ISensitivityLabelCollection](../../com.aspose.slides/isensitivitylabelcollection)
### getSlideById(long id) {#getSlideById-long-}
```
public final IBaseSlide getSlideById(long id)
```

Returnerar en Slide, MasterSlide eller LayoutSlide enligt Id.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| id | long | Id för en bild. |

**Returnerar:**
[IBaseSlide](../../com.aspose.slides/ibaseslide) - IBaseSlide object.
### getSourceFormat() {#getSourceFormat--}
```
public final int getSourceFormat()
```

Returnerar information om från vilket format presentationen laddades. Skrivskyddad [SourceFormat](../../com.aspose.slides/sourceformat).

**Returnerar:**
int
### getMasterTheme() {#getMasterTheme--}
```
public final IMasterTheme getMasterTheme()
```

Returnerar mastertema. Skrivskyddad [IMasterTheme](../../com.aspose.slides/imastertheme).

--------------------

> ```
> The following examples shows how to change a theme effect by altering parts of elements of PowerPoint Presentation.
>  
>  //Instansiera ett presentationsobjekt som representerar en presentationsfil
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


**Returnerar:**
[IMasterTheme](../../com.aspose.slides/imastertheme)
### save(String fname, int format) {#save-java.lang.String-int-}
```
public final void save(String fname, int format)
```

Sparar alla bilder i en presentation till en fil med det angivna formatet.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fname | java.lang.String | Sökväg till den skapade filen. |
| format | int | Format för de exporterade data. |
### save(OutputStream stream, int format) {#save-java.io.OutputStream-int-}
```
public final void save(OutputStream stream, int format)
```

Sparar alla bilder i en presentation till ett flöde i det angivna formatet.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| stream | java.io.OutputStream | Utdataflöde. |
| format | int | Format för de exporterade data. |
### save(String fname, int format, ISaveOptions options) {#save-java.lang.String-int-com.aspose.slides.ISaveOptions-}
```
public final void save(String fname, int format, ISaveOptions options)
```

Sparar alla bilder i en presentation till en fil med det angivna formatet och med ytterligare alternativ.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fname | java.lang.String | Sökväg till den skapade filen. |
| format | int | Format för de exporterade data. |
| options | [ISaveOptions](../../com.aspose.slides/isaveoptions) | Ytterligare formatalternativ. |
### save(OutputStream stream, int format, ISaveOptions options) {#save-java.io.OutputStream-int-com.aspose.slides.ISaveOptions-}
```
public final void save(OutputStream stream, int format, ISaveOptions options)
```

Sparar alla bilder i en presentation till ett flöde i det angivna formatet och med ytterligare alternativ.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| stream | java.io.OutputStream | Utdataflöde. |
| format | int | Format för de exporterade data. |
| options | [ISaveOptions](../../com.aspose.slides/isaveoptions) | Ytterligare formatalternativ. |
### save(IXamlOptions options) {#save-com.aspose.slides.IXamlOptions-}
```
public final void save(IXamlOptions options)
```

Sparar alla bilder i en presentation till en uppsättning filer som representerar XAML-markup.

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


**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| options | [IXamlOptions](../../com.aspose.slides/ixamloptions) | XAML-formatalternativen. |
### getImages(IRenderingOptions options) {#getImages-com.aspose.slides.IRenderingOptions-}
```
public final IImage[] getImages(IRenderingOptions options)
```

Returnerar Bild-objekt för alla bilder i en presentation.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Tiff-alternativ. |
**Returnerar:**
com.aspose.slides.IImage[] - Image objects.
### getImages(IRenderingOptions options, int[] slides) {#getImages-com.aspose.slides.IRenderingOptions-int---}
```
public final IImage[] getImages(IRenderingOptions options, int[] slides)
```

Returnerar miniatyrbild-objekt för angivna bilder i en presentation.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Tiff-alternativ. |
| slides | int[] | Array med bildpositioner, med början från 1. |
**Returnerar:**
com.aspose.slides.IImage[] - Image objects.
### getImages(IRenderingOptions options, float scaleX, float scaleY) {#getImages-com.aspose.slides.IRenderingOptions-float-float-}
```
public final IImage[] getImages(IRenderingOptions options, float scaleX, float scaleY)
```

Returnerar miniatyrbild-objekt för alla bilder i en presentation med anpassad skalning.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Tiff-alternativ. |
| scaleX | float | Värdet med vilket skalningen sker i x-axelns riktning. |
| scaleY | float | Värdet med vilket skalningen sker i y-axelns riktning. |
**Returnerar:**
com.aspose.slides.IImage[] - Image objects.
### getImages(IRenderingOptions options, int[] slides, float scaleX, float scaleY) {#getImages-com.aspose.slides.IRenderingOptions-int---float-float-}
```
public final IImage[] getImages(IRenderingOptions options, int[] slides, float scaleX, float scaleY)
```

Returnerar miniatyrbild-objekt för angivna bilder i en presentation med anpassad skalning.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Tiff-alternativ. |
| slides | int[] | Array med bildpositioner, med början från 1. |
| scaleX | float | Värdet med vilket skalningen sker i x-axelns riktning. |
| scaleY | float | Värdet med vilket skalningen sker i y-axelns riktning. |
**Returnerar:**
com.aspose.slides.IImage[] - Image objects.
### getImages(IRenderingOptions options, Dimension imageSize) {#getImages-com.aspose.slides.IRenderingOptions-java.awt.Dimension-}
```
public final IImage[] getImages(IRenderingOptions options, Dimension imageSize)
```

Returnerar miniatyrbild-objekt för alla bilder i en presentation med specificerad storlek.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Tiff-alternativ. |
| imageSize | java.awt.Dimension | Storleken på bilden som ska skapas. |
**Returnerar:**
com.aspose.slides.IImage[] - Image objects.
### getImages(IRenderingOptions options, int[] slides, Dimension imageSize) {#getImages-com.aspose.slides.IRenderingOptions-int---java.awt.Dimension-}
```
public final IImage[] getImages(IRenderingOptions options, int[] slides, Dimension imageSize)
```

Returnerar miniatyrbild-objekt för angivna bilder i en presentation med specificerad storlek.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Tiff-alternativ. |
| slides | int[] | Array med bildpositioner, med början från 1. |
| imageSize | java.awt.Dimension | Storleken på bilden som ska skapas. |
**Returnerar:**
com.aspose.slides.IImage[] - Image objects.
### save(String fname, int[] slides, int format) {#save-java.lang.String-int---int-}
```
public final void save(String fname, int[] slides, int format)
```

Sparar angivna bilder i en presentation till en fil med det angivna formatet med sidnumrering bevarad.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fname | java.lang.String | Sökväg till den skapade filen. |
| slides | int[] | Array med bildpositioner, med början från 1. |
| format | int | Format för de exporterade data. |
### save(String fname, int[] slides, int format, ISaveOptions options) {#save-java.lang.String-int---int-com.aspose.slides.ISaveOptions-}
```
public final void save(String fname, int[] slides, int format, ISaveOptions options)
```

Sparar angivna bilder i en presentation till en fil med det angivna formatet med sidnumrering bevarad.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fname | java.lang.String | Sökväg till den skapade filen. |
| slides | int[] | Array med bildpositioner, med början från 1. |
| format | int | Format för de exporterade data. |
| options | [ISaveOptions](../../com.aspose.slides/isaveoptions) | Ytterligare formatalternativ. |
### save(OutputStream stream, int[] slides, int format) {#save-java.io.OutputStream-int---int-}
```
public final void save(OutputStream stream, int[] slides, int format)
```

Sparar angivna bilder i en presentation till ett flöde i det angivna formatet med sidnumrering bevarad.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| stream | java.io.OutputStream | Utdataflöde. |
| slides | int[] | Array med bildpositioner, med början från 1. |
| format | int | Format för de exporterade data. |
### save(OutputStream stream, int[] slides, int format, ISaveOptions options) {#save-java.io.OutputStream-int---int-com.aspose.slides.ISaveOptions-}
```
public final void save(OutputStream stream, int[] slides, int format, ISaveOptions options)
```

Sparar angivna bilder i en presentation till ett flöde i det angivna formatet med sidnumrering bevarad.

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


**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| stream | java.io.OutputStream | Utdataflöde. |
| slides | int[] | Array med bildpositioner, med början från 1. |
| format | int | Format för de exporterade data. |
| options | [ISaveOptions](../../com.aspose.slides/isaveoptions) | Ytterligare formatalternativ. |
### joinPortionsWithSameFormatting() {#joinPortionsWithSameFormatting--}
```
public final void joinPortionsWithSameFormatting()
```

Slår ihop textdelar med samma formatering i alla stycken i alla acceptabla former i alla bilder.

### dispose() {#dispose--}
```
public final void dispose()
```

Frigir alla resurser som används av detta Presentation-objekt.

### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

Returnerar den överordnade presentationen för en text. Skrivskyddad [IPresentation](../../com.aspose.slides/ipresentation).

**Returnerar:**
[IPresentation](../../com.aspose.slides/ipresentation)
### highlightText(String text, Color highlightColor) {#highlightText-java.lang.String-java.awt.Color-}
```
public final void highlightText(String text, Color highlightColor)
```

Markerar alla träffar av exempeltexten med den angivna färgen.

> ```
> The following code sample shows how to highlight text in a PowerPoint presentation.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      // markerar alla separata 'the'-förekomster
>      presentation.highlightText("the", Color.MAGENTA);
>      presentation.save("SomePresentation-out2.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| text | java.lang.String | Texten som ska markeras. |
| highlightColor | java.awt.Color | Färgen för att markera texten. |
### highlightText(String text, Color highlightColor, ITextSearchOptions options, IFindResultCallback callback) {#highlightText-java.lang.String-java.awt.Color-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-}
```
public final void highlightText(String text, Color highlightColor, ITextSearchOptions options, IFindResultCallback callback)
```

Markerar alla träffar av exempeltexten med den angivna färgen.

> ```
> The following code sample shows how to highlight text in a PowerPoint presentation.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      TextSearchOptions textSearchOptions = new TextSearchOptions();
>      textSearchOptions.setWholeWordsOnly(true);
>      // markerar alla separata 'the'-förekomster
>      presentation.highlightText("the", Color.MAGENTA, textSearchOptions, null);
>      presentation.save("SomePresentation-out2.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| text | java.lang.String | Texten som ska markeras. |
| highlightColor | java.awt.Color | Färgen för att markera texten. |
| options | [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions) | Textsökalternativ [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions). |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | Återuppringningsobjekt för att ta emot sökresultat [IFindResultCallback](../../com.aspose.slides/ifindresultcallback). |
### highlightRegex(Pattern regex, Color highlightColor, IFindResultCallback callback) {#highlightRegex-java.util.regex.Pattern-java.awt.Color-com.aspose.slides.IFindResultCallback-}
```
public final void highlightRegex(Pattern regex, Color highlightColor, IFindResultCallback callback)
```

Markerar alla träffar av reguljära uttrycket med den angivna färgen.

> ```
> The following code sample shows how to highlight text in a PowerPoint Presentation using a regular expression.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      Pattern regex = Pattern.compile("\\b[^\\s]{10,}\\b");
>      // markerar alla ord med 10 tecken eller längre
>      presentation.highlightRegex(regex, Color.BLUE, null);
>      presentation.save("SomePresentation-out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| regex | java.util.regex.Pattern | Det reguljära uttrycket java.util.regex.Pattern för att få strängar att markera. |
| highlightColor | java.awt.Color | Färgen för att markera texten. |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | Återuppringningsobjekt för att ta emot sökresultat [IFindResultCallback](../../com.aspose.slides/ifindresultcallback).
### replaceText(String oldText, String newText, ITextSearchOptions options, IFindResultCallback callback) {#replaceText-java.lang.String-java.lang.String-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-}
```
public final void replaceText(String oldText, String newText, ITextSearchOptions options, IFindResultCallback callback)
```


Ersätter alla förekomster av den angivna texten med en annan angiven text.

--------------------

> ```
> The following sample code shows how to replace one specified string with another specified string.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx")
>  try {
>      TextSearchOptions textSearchOptions = new TextSearchOptions();
>      textSearchOptions.setWholeWordsOnly(true);
>      // Ersätt alla separata 'the'-förekomster med '***'
>      presentation.replaceText("the", "***", textSearchOptions, null);
>      presentation.save("SomePresentation-out2.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| oldText | java.lang.String | Strängen som ska ersättas. |
| newText | java.lang.String | Strängen som ersätter alla förekomster av oldText. |
| options | [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions) | Textsökalternativ [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions). |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | Callback-objektet för att ta emot sökresultat [IFindResultCallback](../../com.aspose.slides/ifindresultcallback). |

### replaceRegex(Pattern regex, String newText, IFindResultCallback callback) {#replaceRegex-java.util.regex.Pattern-java.lang.String-com.aspose.slides.IFindResultCallback-}
```
public final void replaceRegex(Pattern regex, String newText, IFindResultCallback callback)
```


Ersätter alla träffar av reguljära uttrycket med den angivna strängen.

--------------------

> ```
> The following code sample shows how to replace text using regular expression with the specified string.
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      Pattern regex = Pattern.compile("\\b[^\\s]{10,}\\b");
>      // Ersätt alla ord med 10 tecken eller längre med '***'
>      presentation.replaceRegex(regex, "***", null);
>      presentation.save("SomePresentation-out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| regex | java.util.regex.Pattern | Det reguljära uttrycket java.util.regex.Pattern för att hämta strängar att ersätta. |
| newText | java.lang.String | Strängen som ersätter alla förekomster av de strängar som ska ersättas. |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | Callback-objektet för att ta emot sökresultat [IFindResultCallback](../../com.aspose.slides/ifindresultcallback). |