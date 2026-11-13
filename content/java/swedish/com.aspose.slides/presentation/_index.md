---
title: Presentation
second_title: Aspose.Slides för Java API-referens
description: Representerar en Microsoft PowerPoint-presentation.
type: docs
url: /sv/com.aspose.slides/presentation/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
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
>      // Hämta den första sliden
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
>  // Läs in en valfri stödd fil i Presentation t.ex. ppt, pptx, odp etc.
>  Presentation pres = new Presentation("Sample.odp");
>  try {
>      // Spara presentationsfilen.
>      pres.save("OutputPresenation.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

## Konstruktorer

| Konstruktor | Beskrivning |
| --- | --- |
| [Presentation()](#Presentation--) | Denna konstruktor skapar en ny presentation från grunden. |
| [Presentation(LoadOptions loadOptions)](#Presentation-com.aspose.slides.LoadOptions-) | Denna konstruktor skapar en ny presentation från grunden. |
| [Presentation(InputStream stream)](#Presentation-java.io.InputStream-) | Denna konstruktor är huvudmekanismen för att läsa en befintlig Presentation. |
| [Presentation(InputStream stream, LoadOptions loadOptions)](#Presentation-java.io.InputStream-com.aspose.slides.LoadOptions-) | Denna konstruktor är huvudmekanismen för att läsa en befintlig Presentation. |
| [Presentation(String file)](#Presentation-java.lang.String-) | Denna konstruktor får en källfilssökväg som presentationens innehåll läses från. |
| [Presentation(String file, LoadOptions loadOptions)](#Presentation-java.lang.String-com.aspose.slides.LoadOptions-) | Denna konstruktor får en källfilssökväg som presentationens innehåll läses från. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getCurrentDateTime()](#getCurrentDateTime--) | Returnerar eller sätter datum och tid som kommer att ersätta innehållet i datetime-fält. |
| [setCurrentDateTime(Date value)](#setCurrentDateTime-java.util.Date-) | Returnerar eller sätter datum och tid som kommer att ersätta innehållet i datetime-fält. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | Returnerar den faktiska HeaderFooter-hanteraren. |
| [getProtectionManager()](#getProtectionManager--) | Hämtar hanteraren för behörigheter för denna presentation. |
| [getSlides()](#getSlides--) | Returnerar en lista med alla bilder som definieras i presentationen. |
| [getSections()](#getSections--) | Returnerar en lista med alla avsnitt av bilder som definieras i presentationen. |
| [getSlideSize()](#getSlideSize--) | Returnerar objektet för bildstorlek. |
| [getNotesSize()](#getNotesSize--) | Returnerar objektet för notes-bildstorlek. |
| [getLayoutSlides()](#getLayoutSlides--) | Returnerar en lista med alla layout-bilder som definieras i presentationen. |
| [getMasters()](#getMasters--) | Returnerar en lista med alla master-bilder som definieras i presentationen. |
| [getMasterNotesSlideManager()](#getMasterNotesSlideManager--) | Returnerar notes-master-hanteraren. |
| [getMasterHandoutSlideManager()](#getMasterHandoutSlideManager--) | Returnerar handout-master-hanteraren. |
| [getFontsManager()](#getFontsManager--) | Returnerar teckensnittshanteraren. |
| [getDefaultTextStyle()](#getDefaultTextStyle--) | Returnerar standardtextstil för former. |
| [getCommentAuthors()](#getCommentAuthors--) | Returnerar samlingen av kommentarer-författare. |
| [getDocumentProperties()](#getDocumentProperties--) | Returnerar DocumentProperties-objektet som innehåller standard- och anpassade dokumentegenskaper. |
| [getImages()](#getImages--) | Returnerar samlingen av alla bilder i presentationen. |
| [getAudios()](#getAudios--) | Returnerar samlingen av alla inbäddade ljudfiler i presentationen. |
| [getVideos()](#getVideos--) | Returnerar samlingen av alla inbäddade videofiler i presentationen. |
| [getSlideShowSettings()](#getSlideShowSettings--) | Returnerar bildspelsinställningarna för presentationen. |
| [getDigitalSignatures()](#getDigitalSignatures--) | Returnerar samlingen av signaturer som används för att signera presentationen. |
| [getCustomData()](#getCustomData--) | Returnerar presentationens anpassade data. |
| [getAllCustomXmlParts()](#getAllCustomXmlParts--) | Returnerar alla anpassade dataposter i presentationen. |
| [getVbaProject()](#getVbaProject--) | Hämtar eller sätter VBA-projektet med presentationens makron. |
| [setVbaProject(IVbaProject value)](#setVbaProject-com.aspose.slides.IVbaProject-) | Hämtar eller sätter VBA-projektet med presentationens makron. |
| [getHyperlinkQueries()](#getHyperlinkQueries--) | Ger enkel åtkomst till alla hyperlänkar som finns i alla presentationsbilder (ej i master-, layout- eller notes-bilder). |
| [getViewProperties()](#getViewProperties--) | Hämtar presentationsomfattande vyegenskaper. |
| [getFirstSlideNumber()](#getFirstSlideNumber--) | Representerar det första bildnumret i presentationen |
| [setFirstSlideNumber(int value)](#setFirstSlideNumber-int-) | Representerar det första bildnumret i presentationen |
| [getSensitivityLabels()](#getSensitivityLabels--) | Returnerar samlingen av känslighetsetiketter som tillämpas på presentationsdokumentet. |
| [getSlideById(long id)](#getSlideById-long-) | Returnerar en Slide, MasterSlide eller LayoutSlide efter Id. |
| [getSourceFormat()](#getSourceFormat--) | Returnerar information om från vilket format presentationen laddades. |
| [getMasterTheme()](#getMasterTheme--) | Returnerar master-tema. |
| [save(String fname, int format)](#save-java.lang.String-int-) | Sparar alla bilder i en presentation till en fil i angivet format. |
| [save(OutputStream stream, int format)](#save-java.io.OutputStream-int-) | Sparar alla bilder i en presentation till en ström i angivet format. |
| [save(String fname, int format, ISaveOptions options)](#save-java.lang.String-int-com.aspose.slides.ISaveOptions-) | Sparar alla bilder i en presentation till en fil i angivet format och med ytterligare alternativ. |
| [save(OutputStream stream, int format, ISaveOptions options)](#save-java.io.OutputStream-int-com.aspose.slides.ISaveOptions-) | Sparar alla bilder i en presentation till en ström i angivet format och med ytterligare alternativ. |
| [save(IXamlOptions options)](#save-com.aspose.slides.IXamlOptions-) | Sparar alla bilder i en presentation till en uppsättning filer som representerar XAML-markup. |
| [getImages(IRenderingOptions options)](#getImages-com.aspose.slides.IRenderingOptions-) | Returnerar Image-objekt för alla bilder i en presentation. |
| [getImages(IRenderingOptions options, int[] slides)](#getImages-com.aspose.slides.IRenderingOptions-int---) | Returnerar Thumbnail-Image-objekt för angivna bilder i en presentation. |
| [getImages(IRenderingOptions options, float scaleX, float scaleY)](#getImages-com.aspose.slides.IRenderingOptions-float-float-) | Returnerar Thumbnail-Image-objekt för alla bilder i en presentation med anpassad skalning. |
| [getImages(IRenderingOptions options, int[] slides, float scaleX, float scaleY)](#getImages-com.aspose.slides.IRenderingOptions-int---float-float-) | Returnerar Thumbnail-Image-objekt för angivna bilder i en presentation med anpassad skalning. |
| [getImages(IRenderingOptions options, Dimension imageSize)](#getImages-com.aspose.slides.IRenderingOptions-java.awt.Dimension-) | Returnerar Thumbnail-Image-objekt för alla bilder i en presentation med specificerad storlek. |
| [getImages(IRenderingOptions options, int[] slides, Dimension imageSize)](#getImages-com.aspose.slides.IRenderingOptions-int---java.awt.Dimension-) | Returnerar Thumbnail-Image-objekt för angivna bilder i en presentation med specificerad storlek. |
| [save(String fname, int[] slides, int format)](#save-java.lang.String-int---int-) | Sparar angivna bilder i en presentation till en fil i angivet format med sidnummerbevarande. |
| [save(String fname, int[] slides, int format, ISaveOptions options)](#save-java.lang.String-int---int-com.aspose.slides.ISaveOptions-) | Sparar angivna bilder i en presentation till en fil i angivet format med sidnummerbevarande. |
| [save(OutputStream stream, int[] slides, int format)](#save-java.io.OutputStream-int---int-) | Sparar angivna bilder i en presentation till en ström i angivet format med sidnummerbevarande. |
| [save(OutputStream stream, int[] slides, int format, ISaveOptions options)](#save-java.io.OutputStream-int---int-com.aspose.slides.ISaveOptions-) | Sparar angivna bilder i en presentation till en ström i angivet format med sidnummerbevarande. |
| [joinPortionsWithSameFormatting()](#joinPortionsWithSameFormatting--) | Slår ihop körningar med samma formatering i alla stycken i alla accepterade former i alla bilder. |
| [dispose()](#dispose--) | Frigör alla resurser som används av detta Presentation-objekt. |
| [getPresentation()](#getPresentation--) | Returnerar föräldrapresentationen för en text. |
| [highlightText(String text, Color highlightColor)](#highlightText-java.lang.String-java.awt.Color-) | Markerar alla matchningar av exempeltexten med den angivna färgen. |
| [highlightText(String text, Color highlightColor, ITextSearchOptions options, IFindResultCallback callback)](#highlightText-java.lang.String-java.awt.Color-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-) | Markerar alla matchningar av exempeltexten med den angivna färgen. |
| [highlightRegex(Pattern regex, Color highlightColor, IFindResultCallback callback)](#highlightRegex-java.util.regex.Pattern-java.awt.Color-com.aspose.slides.IFindResultCallback-) | Markerar alla matchningar av reguljära uttrycket med den angivna färgen. |
| [replaceText(String oldText, String newText, ITextSearchOptions options, IFindResultCallback callback)](#replaceText-java.lang.String-java.lang.String-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-) | Ersätter alla förekomster av den angivna texten med en annan angiven text. |
| [replaceRegex(Pattern regex, String newText, IFindResultCallback callback)](#replaceRegex-java.util.regex.Pattern-java.lang.String-com.aspose.slides.IFindResultCallback-) | Ersätter alla matchningar av reguljära uttrycket med den angivna strängen. |
| [refreshChartsData()](#refreshChartsData--) | Laddar om data för alla diagram i presentationen från deras källarbetsböcker. |
| [refreshChartsData(boolean skipFailedCharts)](#refreshChartsData-boolean-) | Laddar om data för alla diagram i presentationen från deras källarbetsböcker. |
### Presentation() {#Presentation--}
```
public Presentation()
```

Denna konstruktor skapar en ny presentation från grunden. Den skapade presentationen har en tom bild.

### Presentation(LoadOptions loadOptions) {#Presentation-com.aspose.slides.LoadOptions-}
```
public Presentation(LoadOptions loadOptions)
```

Denna konstruktor skapar en ny presentation från grunden. Den skapade presentationen har en tom bild.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| loadOptions | [LoadOptions](../../com.aspose.slides/loadoptions) | Ytterligare inläsningsalternativ. |
### Presentation(InputStream stream) {#Presentation-java.io.InputStream-}
```
public Presentation(InputStream stream)
```

Denna konstruktor är huvudmekanismen för att läsa en befintlig Presentation.

> ```
> FileInputStream fis = new FileInputStream("demo.pptx");
>  Presentation pres = new Presentation(fis);
>  fis.close();
> ```


**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| stream | java.io.InputStream | Inmatningsström. |
### Presentation(InputStream stream, LoadOptions loadOptions) {#Presentation-java.io.InputStream-com.aspose.slides.LoadOptions-}
```
public Presentation(InputStream stream, LoadOptions loadOptions)
```

Denna konstruktor är huvudmekanismen för att läsa en befintlig Presentation.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| stream | java.io.InputStream | Inmatningsström. |
| loadOptions | [LoadOptions](../../com.aspose.slides/loadoptions) | Ytterligare inläsningsalternativ. |
### Presentation(String file) {#Presentation-java.lang.String-}
```
public Presentation(String file)
```

Denna konstruktor får en källfilssökväg som presentationens innehåll läses från.

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

Denna konstruktor får en källfilssökväg som presentationens innehåll läses från.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| file | java.lang.String | Indatafil. |
| loadOptions | [LoadOptions](../../com.aspose.slides/loadoptions) | Ytterligare inläsningsalternativ. |
### getCurrentDateTime() {#getCurrentDateTime--}
```
public final Date getCurrentDateTime()
```

Returnerar eller anger datum och tid som kommer att ersätta innehållet i datetime-fält. Standardvärdet är tidpunkten för skapandet av detta Presentation-objekt. Läs/skriv java.util.Date.

**Returnerar:**
java.util.Date
### setCurrentDateTime(Date value) {#setCurrentDateTime-java.util.Date-}
```
public final void setCurrentDateTime(Date value)
```

Returnerar eller anger datum och tid som kommer att ersätta innehållet i datetime-fält. Standardvärdet är tidpunkten för skapandet av detta Presentation-objekt. Läs/skriv java.util.Date.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | java.util.Date |  |
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Returnerar Parent_Immediate-objektet. Endast läsning IDOMObject.

**Returnerar:**
com.aspose.slides.IDOMObject
### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public final IPresentationHeaderFooterManager getHeaderFooterManager()
```

Returnerar den faktiska HeaderFooter-hanteraren. Endast läsning [IPresentationHeaderFooterManager](../../com.aspose.slides/ipresentationheaderfootermanager).

> ```
> The following example shows how to set footer visibility inside Slide of PowerPoint Presentation.
>  
>  Presentation pres = new Presentation("presentation.ppt");
>  try
>  {
>      IBaseSlideHeaderFooterManager headerFooterManager = pres.getSlides().get_Item(0).getHeaderFooterManager();
>      if (!headerFooterManager.isFooterVisible()) // Property IsFooterVisible används för att indikera att en slide-fotoplats inte finns.
>      {
>          headerFooterManager.setFooterVisibility(true); // Method SetFooterVisibility används för att göra en slide-fotoplats synlig.
>      }
>      if (!headerFooterManager.isSlideNumberVisible()) // Property IsSlideNumberVisible används för att indikera att en slide-sidnummer-platshållare inte finns.
>      {
>          headerFooterManager.setSlideNumberVisibility(true); // Method SetSlideNumberVisibility används för att göra en slide-sidnummer-platshållare synlig.
>      }
>      if (!headerFooterManager.isDateTimeVisible()) // Property IsDateTimeVisible används för att indikera att en slide-datum-tid-platshållare inte finns.
>      {
>          headerFooterManager.setDateTimeVisibility(true); // Method SetFooterVisibility används för att göra en slide-datum-tid-platshållare synlig.
>      }
>      headerFooterManager.setFooterText("Footer text"); // Method SetFooterText används för att ange text till slide-fotoplats.
>      headerFooterManager.setDateTimeText("Date and time text"); // Method SetDateTimeText används för att ange text till slide-datum-tid-platshållare.
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
>      headerFooterManager.setFooterAndChildFootersVisibility(true); // Method SetFooterAndChildFootersVisibility används för att göra en master-slide och alla underordnade fotoplats-platshållare synliga.
>      headerFooterManager.setSlideNumberAndChildSlideNumbersVisibility(true); // Method SetSlideNumberAndChildSlideNumbersVisibility används för att göra en master-slide och alla underordnade sidnummer-platshållare synliga.
>      headerFooterManager.setDateTimeAndChildDateTimesVisibility(true); // Method SetDateTimeAndChildDateTimesVisibility används för att göra en master-slide och alla underordnade datum-tid-platshållare synliga.
> 
>      headerFooterManager.setFooterAndChildFootersText("Footer text"); // Method SetFooterAndChildFootersText används för att ange text till master-slide och alla underordnade fotoplats-platshållare.
>      headerFooterManager.setDateTimeAndChildDateTimesText("Date and time text"); // Method SetDateTimeAndChildDateTimesText används för att ange text till master-slide och alla underordnade datum-tid-platshållare.
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

Hämtar hanteraren för behörigheter för denna presentation. Endast läsning [IProtectionManager](../../com.aspose.slides/iprotectionmanager).

**Returnerar:**
[IProtectionManager](../../com.aspose.slides/iprotectionmanager)
### getSlides() {#getSlides--}
```
public final ISlideCollection getSlides()
```

Returnerar en lista med alla bilder som definieras i presentationen. Endast läsning [ISlideCollection](../../com.aspose.slides/islidecollection).

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
>      // Lägg till bild i presentationens bildsamling
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
>      // Applicera cirkeltyp övergång på bild 1
>      pres.getSlides().get_Item(0).getSlideShowTransition().setType(TransitionType.Circle);
>      // Applicera kamtyp övergång på bild 2
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
>      // Applicera cirkeltyp övergång på bild 1
>      pres.getSlides().get_Item(0).getSlideShowTransition().setType(TransitionType.Circle);
>      // Ställ in övergångstiden till 3 sekunder
>      pres.getSlides().get_Item(0).getSlideShowTransition().setAdvanceOnClick(true);
>      pres.getSlides().get_Item(0).getSlideShowTransition().setAdvanceAfterTime(3000);
>      // Applicera kamtyp övergång på bild 2
>      pres.getSlides().get_Item(1).getSlideShowTransition().setType(TransitionType.Comb);
>      // Ställ in övergångstiden till 5 sekunder
>      pres.getSlides().get_Item(1).getSlideShowTransition().setAdvanceOnClick(true);
>      pres.getSlides().get_Item(1).getSlideShowTransition().setAdvanceAfterTime(5000);
>      // Applicera zoomtyp övergång på bild 3
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

Returnerar en lista med alla bildavsnitt som definieras i presentationen. Endast läsning [ISectionCollection](../../com.aspose.slides/isectioncollection).

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

Returnerar bildstorleksobjektet. Endast läsning [ISlideSize](../../com.aspose.slides/islidesize).

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
>          // Ställ in bildstorleken för genererade presentationer till den från källan
>          presentation.getSlideSize().setSize(540, 720, SlideSizeScaleType.EnsureFit); // Metoden SetSize används för att sätta bildstorlek med skalning av innehållet för att säkerställa passning
>          presentation.getSlideSize().setSize(SlideSizeType.A4Paper, SlideSizeScaleType.Maximize); // Metoden SetSize används för att sätta bildstorlek med maximal storlek på innehållet
>          // Spara presentation till disk
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

Returnerar notbildsstorleksobjektet. Endast läsning [INotesSize](../../com.aspose.slides/inotessize).

**Returnerar:**
[INotesSize](../../com.aspose.slides/inotessize)
### getLayoutSlides() {#getLayoutSlides--}
```
public final IGlobalLayoutSlideCollection getLayoutSlides()
```

Returnerar en lista med alla layout-bilder som definieras i presentationen. Endast läsning [IGlobalLayoutSlideCollection](../../com.aspose.slides/igloballayoutslidecollection).

Du kan komma åt ett alternativt API för att lägga till/infoga/ta bort/klona layout-bilder genom att använda IMasterSlide.LayoutSlides-egenskapen.

**Returnerar:**
[IGlobalLayoutSlideCollection](../../com.aspose.slides/igloballayoutslidecollection)
### getMasters() {#getMasters--}
```
public final IMasterSlideCollection getMasters()
```

Returnerar en lista med alla master-bilder som definieras i presentationen. Endast läsning [IMasterSlideCollection](../../com.aspose.slides/imasterslidecollection).

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

**Returnerar:**
[IMasterSlideCollection](../../com.aspose.slides/imasterslidecollection)
### getMasterNotesSlideManager() {#getMasterNotesSlideManager--}
```
public final IMasterNotesSlideManager getMasterNotesSlideManager()
```

Returnerar notes-master-hanteraren. Endast läsning [IMasterNotesSlideManager](../../com.aspose.slides/imasternotesslidemanager).

**Returnerar:**
[IMasterNotesSlideManager](../../com.aspose.slides/imasternotesslidemanager)
### getMasterHandoutSlideManager() {#getMasterHandoutSlideManager--}
```
public final IMasterHandoutSlideManager getMasterHandoutSlideManager()
```

Returnerar handout-master-hanteraren. Endast läsning [IMasterHandoutSlideManager](../../com.aspose.slides/imasterhandoutslidemanager).

**Returnerar:**
[IMasterHandoutSlideManager](../../com.aspose.slides/imasterhandoutslidemanager)
### getFontsManager() {#getFontsManager--}
```
public final IFontsManager getFontsManager()
```

Returnerar teckensnittshanteraren. Endast läsning [IFontsManager](../../com.aspose.slides/ifontsmanager).

> ```
> The following example shows how to add embedded fonts to PowerPoint Presentation.
>  
>  // Läs in presentationen
>  Presentation pres = new Presentation("Fonts.pptx");
>  try {
>      // Läs in källtypsnittet som ska ersättas
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

Returnerar standardtextstil för former. Endast läsning [ITextStyle](../../com.aspose.slides/itextstyle).

**Returnerar:**
[ITextStyle](../../com.aspose.slides/itextstyle)
### getCommentAuthors() {#getCommentAuthors--}
```
public final ICommentAuthorCollection getCommentAuthors()
```

Returnerar samlingen av kommentarer-författare. Endast läsning [ICommentAuthorCollection](../../com.aspose.slides/icommentauthorcollection).

**Returnerar:**
[ICommentAuthorCollection](../../com.aspose.slides/icommentauthorcollection)
### getDocumentProperties() {#getDocumentProperties--}
```
public final IDocumentProperties getDocumentProperties()
```

Returnerar DocumentProperties-objektet som innehåller standard- och anpassade dokumentegenskaper. Endast läsning [IDocumentProperties](../../com.aspose.slides/idocumentproperties).

**Returnerar:**
[IDocumentProperties](../../com.aspose.slides/idocumentproperties)
### getImages() {#getImages--}
```
public final IImageCollection getImages()
```

Returnerar samlingen av alla bilder i presentationen. Endast läsning [IImageCollection](../../com.aspose.slides/iimagecollection).

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
> The following examples shows how to add image as BLOB in PowerPoint Presentation.
>  
>  // skapar en ny presentation som bilden kommer att läggas till.
>  Presentation pres = new Presentation();
>  try
>  {
>      // anta att vi har den stora bildfilen som vi vill inkludera i presentationen
>      FileInputStream fip = new FileInputStream("large_image.jpg");
>      try
>      {
>          // Låt oss lägga till bilden i presentationen - vi väljer KeepLocked-beteende eftersom vi
>          // INTE avser att komma åt \"largeImage.png\"-filen.
>          IPPImage img = pres.getImages().addImage(fip, LoadingStreamBehavior.KeepLocked);
>          pres.getSlides().get_Item(0).getShapes().addPictureFrame(ShapeType.Rectangle, 0, 0, 300, 200, img);
>          // Sparar presentationen. Medan en stor presentation skrivs ut, är minnesförbrukningen
>          // låg under pres-objektets livscykel
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
>      // Lägger till bild i presentationen
>      IPPImage image = pres.getImages().addImage(Files.readAllBytes(Paths.get("image.png")));
>      // Skapar bildruta på bild 1 baserat på tidigare tillagd bild
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
[IVideoCollection](../../com.aspose.slides/ivideocollection)
### getSlideShowSettings() {#getSlideShowSettings--}
```
public  SlideShowSettings getSlideShowSettings()
```


Returnerar bildspelinställningarna för presentationen.

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


Returnerar alla anpassade dataparts i presentationen. Skrivskyddad ICustomXmlPart[].

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


Hämtar eller ställer in VBA-projekt med presentationsmakron. Läs/skriv [IVbaProject](../../com.aspose.slides/ivbaproject).

**Returnerar:**
[IVbaProject](../../com.aspose.slides/ivbaproject)
### setVbaProject(IVbaProject value) {#setVbaProject-com.aspose.slides.IVbaProject-}
```
public final void setVbaProject(IVbaProject value)
```


Hämtar eller ställer in VBA-projekt med presentationsmakron. Läs/skriv [IVbaProject](../../com.aspose.slides/ivbaproject).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [IVbaProject](../../com.aspose.slides/ivbaproject) |  |

### getHyperlinkQueries() {#getHyperlinkQueries--}
```
public       I         
```


Tillhandahåller enkel åtkomst till alla hyperlänkar som finns i alla presentationsbilder (ej i master, layout, notes-bilder). Skrivskyddad [IHyperlinkQueries](../../com.aspose.slides/ihyperlinkqueries).

**Returnerar:**
[IHyperlinkQueries](../../com.aspose.slides/ihyperlinkqueries)
### getViewProperties() {#getViewProperties--}
```
public final IViewProperties getViewProperties()
```


Hämtar presentationsomfattande vyegenskaper. Skrivskyddad [IViewProperties](../../com.aspose.slides/iviewproperties).

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
>      // Print the applied labels
>      for (ISensitivityLabel sensitivityLabel : sensitivityLabels)
>          System.out.println("Label Id " + sensitivityLabel.getId() + " from Azure AD site " + sensitivityLabel.getSiteId());
> 
>      // Add the new label
>      String labelIdString = "{xxxxxxxx-xxxx-xxxx-xxxx-xxxxxxxxxxxx}"; // Get the sensitivity label Id from the policy
>      UUID siteIdGuid = UUID.fromString("{xxxxxxxx-xxxx-xxxx-xxxx-xxxxxxxxxxxx}"); // Get the Azure AD site identifier from the policy
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


Returnerar en Slide, MasterSlide eller LayoutSlide med Id.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| id | long | Id för en bild. |

**Returnerar:**
[IBaseSlide](../../com.aspose.slides/ibaseslide) - IBaseSlide-objekt.
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


Sparar alla bilder i en presentation till en fil med angivet format.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fname | java.lang.String | Sökväg till den skapade filen. |
| format | int | Format för de exporterade data. |

### save(OutputStream stream, int format) {#save-java.io.OutputStream-int-}
```
public final void save(OutputStream stream, int format)
```


Sparar alla bilder i en presentation till en ström i angivet format.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| stream | java.io.OutputStream | Utmatningsström. |
| format | int | Format för de exporterade data. |

### save(String fname, int format, ISaveOptions options) {#save-java.lang.String-int-com.aspose.slides.ISaveOptions-}
```
public final void save(String fname, int format, ISaveOptions options)
```


Sparar alla bilder i en presentation till en fil med angivet format och med ytterligare alternativ.

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


Sparar alla bilder i en presentation till en ström i angivet format och med ytterligare alternativ.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| stream | java.io.OutputStream | Utmatningsström. |
| format | int | Format för de exporterade data. |
| options | [ISaveOptions](../../com.aspose.slides/isaveoptions) | Ytterligare formatalternativ. |

### save(IXamlOptions options) {#save-com.aspose.slides.IXamlOptions-}
```
public final void save(IXamlOptions options)
```


Sparar alla bilder i en presentation till en uppsättning filer som representerar XAML-markering.

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


Returnerar Image-objekt för alla bilder i en presentation.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Tiff-alternativ. |

**Returnerar:**
com.aspose.slides.IImage[] - Bildobjekt.
### getImages(IRenderingOptions options, int[] slides) {#getImages-com.aspose.slides.IRenderingOptions-int---}
```
public final IImage[] getImages(IRenderingOptions options, int[] slides)
```


Returnerar miniatyrbild-objekt för angivna bilder i en presentation.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Tiff-alternativ. |
| slides | int[] | Array med bildpositioner, startande från 1. |

**Returnerar:**
com.aspose.slides.IImage[] - Bildobjekt.
### getImages(IRenderingOptions options, float scaleX, float scaleY) {#getImages-com.aspose.slides.IRenderingOptions-float-float-}
```
public final IImage[] getImages(IRenderingOptions options, float scaleX, float scaleY)
```


Returnerar miniatyrbild-objekt för alla bilder i en presentation med anpassad skalning.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Tiff-alternativ. |
| scaleX | float | Värdet med vilket den här miniatyren skalas i x-axelns riktning. |
| scaleY | float | Värdet med vilket den här miniatyren skalas i y-axelns riktning. |

**Returnerar:**
com.aspose.slides.IImage[] - Bildobjekt.
### getImages(IRenderingOptions options, int[] slides, float scaleX, float scaleY) {#getImages-com.aspose.slides.IRenderingOptions-int---float-float-}
```
public final IImage[] getImages(IRenderingOptions options, int[] slides, float scaleX, float scaleY)
```


Returnerar miniatyrbild-objekt för angivna bilder i en presentation med anpassad skalning.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Tiff-alternativ. |
| slides | int[] | Array med bildpositioner, startande från 1. |
| scaleX | float | Värdet med vilket den här miniatyren skalas i x-axelns riktning. |
| scaleY | float | Värdet med vilket den här miniatyren skalas i y-axelns riktning. |

**Returnerar:**
com.aspose.slides.IImage[] - Bildobjekt.
### getImages(IRenderingOptions options, Dimension imageSize) {#getImages-com.aspose.slides.IRenderingOptions-java.awt.Dimension-}
```
public final IImage[] getImages(IRenderingOptions options, Dimension imageSize)
```


Returnerar miniatyrbild-objekt för alla bilder i en presentation med angiven storlek.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Tiff-alternativ. |
| imageSize | java.awt.Dimension | Storlek på bilden som ska skapas. |

**Returnerar:**
com.aspose.slides.IImage[] - Bildobjekt.
### getImages(IRenderingOptions options, int[] slides, Dimension imageSize) {#getImages-com.aspose.slides.IRenderingOptions-int---java.awt.Dimension-}
```
public final IImage[] getImages(IRenderingOptions options, int[] slides, Dimension imageSize)
```


Returnerar miniatyrbild-objekt för angivna bilder i en presentation med angiven storlek.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Tiff-alternativ. |
| slides | int[] | Array med bildpositioner, startande från 1. |
| imageSize | java.awt.Dimension | Storlek på bilden som ska skapas. |

**Returnerar:**
com.aspose.slides.IImage[] - Bildobjekt.
### save(String fname, int[] slides, int format) {#save-java.lang.String-int---int-}
```
public final void save(String fname, int[] slides, int format)
```


Sparar angivna bilder i en presentation till en fil med angivet format med sidnummerbehållning.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fname | java.lang.String | Sökväg till den skapade filen. |
| slides | int[] | Array med bildpositioner, startande från 1. |
| format | int | Format för de exporterade data. |

### save(String fname, int[] slides, int format, ISaveOptions options) {#save-java.lang.String-int---int-com.aspose.slides.ISaveOptions-}
```
public final void save(String fname, int[] slides, int format, ISaveOptions options)
```


Sparar angivna bilder i en presentation till en fil med angivet format med sidnummerbehållning.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fname | java.lang.String | Sökväg till den skapade filen. |
| slides | int[] | Array med bildpositioner, startande från 1. |
| format | int | Format för de exporterade data. |
| options | [ISaveOptions](../../com.aspose.slides/isaveoptions) | Ytterligare formatalternativ. |

### save(OutputStream stream, int[] slides, int format) {#save-java.io.OutputStream-int---int-}
```
public final void save(OutputStream stream, int[] slides, int format)
```


Sparar angivna bilder i en presentation till en ström i angivet format med sidnummerbehållning.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| stream | java.io.OutputStream | Utmatningsström. |
| slides | int[] | Array med bildpositioner, startande från 1. |
| format | int | Format för de exporterade data. |

### save(OutputStream stream, int[] slides, int format, ISaveOptions options) {#save-java.io.OutputStream-int---int-com.aspose.slides.ISaveOptions-}
```
public final void save(OutputStream stream, int[] slides, int format, ISaveOptions options)
```


Sparar angivna bilder i en presentation till en ström i angivet format med sidnummerbehållning.

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
| stream | java.io.OutputStream | Utmatningsström. |
| slides | int[] | Array med bildpositioner, startande från 1. |
| format | int | Format för de exporterade data. |
| options | [ISaveOptions](../../com.aspose.slides/isaveoptions) | Ytterligare formatalternativ. |

### joinPortionsWithSameFormatting() {#joinPortionsWithSameFormatting--}
```
public final void joinPortionsWithSameFormatting()
```


Sammanfogar körningar med samma formatering i alla stycken i alla accepterade former i alla bilder.

### dispose() {#dispose--}
```
public final void dispose()
```


Frigör alla resurser som används av detta Presentation-objekt.

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


Markerar alla matchningar av exempeltexten med den angivna färgen.

--------------------

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
| highlightColor | java.awt.Color | Färgen som ska användas för att markera texten. |

### highlightText(String text, Color highlightColor, ITextSearchOptions options, IFindResultCallback callback) {#highlightText-java.lang.String-java.awt.Color-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-}
```
public final void highlightText(String text, Color highlightColor, ITextSearchOptions options, IFindResultCallback callback)
```


Markerar alla matchningar av exempeltexten med den angivna färgen.

--------------------

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
| highlightColor | java.awt.Color | Färgen som ska användas för att markera texten. |
| options | [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions) | Textsökalternativ [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions). |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | Återuppringningsobjekt för att ta emot sökresultat [IFindResultCallback](../../com.aspose.slides/ifindresultcallback). |

### highlightRegex(Pattern regex, Color highlightColor, IFindResultCallback callback) {#highlightRegex-java.util.regex.Pattern-java.awt.Color-com.aspose.slides.IFindResultCallback-}
```
public final void highlightRegex(Pattern regex, Color highlightColor, IFindResultCallback callback)
```


Markerar alla matchningar av reguljära uttrycket med den angivna färgen.

--------------------

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
| regex | java.util.regex.Pattern | Reguljärt uttryck java.util.regex.Pattern för att hämta strängar att markera. |
| highlightColor | java.awt.Color | Färgen för att markera texten. |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | Callback-objektet för att ta emot sökresultat [IFindResultCallback](../../com.aspose.slides/ifindresultcallback). |

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
| options | [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions) | Alternativ för textsökning [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions). |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | Callback-objektet för att ta emot sökresultat [IFindResultCallback](../../com.aspose.slides/ifindresultcallback). |

### replaceRegex(Pattern regex, String newText, IFindResultCallback callback) {#replaceRegex-java.util.regex.Pattern-java.lang.String-com.aspose.slides.IFindResultCallback-}
```
public final void replaceRegex(Pattern regex, String newText, IFindResultCallback callback)
```

Ersätter alla träffar av det reguljära uttrycket med den angivna strängen.

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
| regex | java.util.regex.Pattern | Reguljärt uttryck java.util.regex.Pattern för att hämta strängar att ersätta. |
| newText | java.lang.String | Strängen som ersätter alla förekomster av de strängar som ska ersättas. |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | Callback-objektet för att ta emot sökresultat [IFindResultCallback](../../com.aspose.slides/ifindresultcallback). |

### refreshChartsData() {#refreshChartsData--}
```
public final void refreshChartsData()
```

Laddar om data för alla diagram i presentationen från deras källarbok.

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

Laddar om data för alla diagram i presentationen från deras källarbok.

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


**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| skipFailedCharts | boolean | Bestämmer om uppdateringsprocessen fortsätter om ett diagram misslyckas med att uppdateras. Om true hoppas diagram som orsakar ett undantag över; annars propageras undantaget. |