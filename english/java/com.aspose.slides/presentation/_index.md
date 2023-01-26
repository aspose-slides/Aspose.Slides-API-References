---
title: Presentation
second_title: Aspose.Slides for Java API Reference
description: Represents a Microsoft PowerPoint presentation.
type: docs
weight: 444
url: /java/com.aspose.slides/presentation/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.slides.IPresentation](../../com.aspose.slides/ipresentation), com.aspose.slides.IDOMObject
```
public final class Presentation implements IPresentation, IDOMObject
```

Represents a Microsoft PowerPoint presentation.

--------------------

> ```
> The following example shows how to create PowerPoint Presentation.
>   
>  // Instantiate a Presentation object that represents a presentation file
>  Presentation pres = new Presentation();
>  try {
>      // Get the first slide
>      ISlide slide = pres.getSlides().get_Item(0);
>      // Add an autoshape of type line
>      slide.getShapes().addAutoShape(ShapeType.Line, 50, 150, 300, 0);
>      // Save the presentation file.
>      pres.save("NewPresentation_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>   
>   The following example shows how to open and save Presentation.
>   
>  // Load any supported file in Presentation e.g. ppt, pptx, odp etc.
>  Presentation pres = new Presentation("Sample.odp");
>  try {
>      // Save the presentation file.
>      pres.save("OutputPresenation.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```
## Constructors

| Constructor | Description |
| --- | --- |
| [Presentation()](#Presentation--) | This constructor creates new presentation from scratch. |
| [Presentation(LoadOptions loadOptions)](#Presentation-com.aspose.slides.LoadOptions-) | This constructor creates new presentation from scratch. |
| [Presentation(InputStream stream)](#Presentation-java.io.InputStream-) | This constructor is the primary mechanism for reading an existing Presentation. |
| [Presentation(InputStream stream, LoadOptions loadOptions)](#Presentation-java.io.InputStream-com.aspose.slides.LoadOptions-) | This constructor is the primary mechanism for reading an existing Presentation. |
| [Presentation(String file)](#Presentation-java.lang.String-) | This constructor gets a source file path from which the contents of the Presentation are read. |
| [Presentation(String file, LoadOptions loadOptions)](#Presentation-java.lang.String-com.aspose.slides.LoadOptions-) | This constructor gets a source file path from which the contents of the Presentation are read. |
## Methods

| Method | Description |
| --- | --- |
| [getCurrentDateTime()](#getCurrentDateTime--) | Returns or sets date and time which will substitute content of datetime fields. |
| [setCurrentDateTime(Date value)](#setCurrentDateTime-java.util.Date-) | Returns or sets date and time which will substitute content of datetime fields. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | Returns actual HeaderFooter manager. |
| [getProtectionManager()](#getProtectionManager--) | Gets manager of the permissions for this presentation. |
| [getSlides()](#getSlides--) | Returns a list of all slides that are defined in the presentation. |
| [getSections()](#getSections--) | Returns a list of all slides sections that are defined in the presentation. |
| [getSlideSize()](#getSlideSize--) | Returns slide size object. |
| [getNotesSize()](#getNotesSize--) | Returns notes slide size object. |
| [getLayoutSlides()](#getLayoutSlides--) | Returns a list of all layout slides that are defined in the presentation. |
| [getMasters()](#getMasters--) | Returns a list of all master slides that are defined in the presentation. |
| [getMasterNotesSlideManager()](#getMasterNotesSlideManager--) | Returns notes master manager. |
| [getMasterHandoutSlideManager()](#getMasterHandoutSlideManager--) | Returns handout master manager. |
| [getFontsManager()](#getFontsManager--) | Returns fonts manager. |
| [getDefaultTextStyle()](#getDefaultTextStyle--) | Returns default text style for shapes. |
| [getCommentAuthors()](#getCommentAuthors--) | Returns the collection of comments autors. |
| [getDocumentProperties()](#getDocumentProperties--) | Returns DocumentProperties object which contains standard and custom document properties. |
| [getImages()](#getImages--) | Returns the collection of all images in the presentation. |
| [getAudios()](#getAudios--) | Returns the collection of all embedded audio files in the presentation. |
| [getVideos()](#getVideos--) | Returns the collection of all embedded video files in the presentation. |
| [getSlideShowSettings()](#getSlideShowSettings--) | Returns the slide show settings for the presentation. |
| [getDigitalSignatures()](#getDigitalSignatures--) | Returns the collection of signatures used to sign the presentation. |
| [getCustomData()](#getCustomData--) | Returns the presentation's custom data. |
| [getAllCustomXmlParts()](#getAllCustomXmlParts--) | Returns all custom data parts in the presentaion. |
| [getVbaProject()](#getVbaProject--) | Gets or sets VBA project with presentation macros. |
| [setVbaProject(IVbaProject value)](#setVbaProject-com.aspose.slides.IVbaProject-) | Gets or sets VBA project with presentation macros. |
| [getHyperlinkQueries()](#getHyperlinkQueries--) | Provides easy access to all hyperlinks contained in all presentation slides (not in master, layout, notes slides). |
| [getViewProperties()](#getViewProperties--) | Gets presentation wide view properties. |
| [getFirstSlideNumber()](#getFirstSlideNumber--) | Represents the first slide number in the presentation |
| [setFirstSlideNumber(int value)](#setFirstSlideNumber-int-) | Represents the first slide number in the presentation |
| [getSlideById(long id)](#getSlideById-long-) | Returns a Slide, MasterSlide or LayoutSlide by Id. |
| [getSourceFormat()](#getSourceFormat--) | Returns information about from which format presentation was loaded. |
| [getMasterTheme()](#getMasterTheme--) | Returns master theme. |
| [save(String fname, int format)](#save-java.lang.String-int-) | Saves all slides of a presentation to a file with the specified format. |
| [save(OutputStream stream, int format)](#save-java.io.OutputStream-int-) | Saves all slides of a presentation to a stream in the specified format. |
| [save(String fname, int format, ISaveOptions options)](#save-java.lang.String-int-com.aspose.slides.ISaveOptions-) | Saves all slides of a presentation to a file with the specified format and with additional options. |
| [save(OutputStream stream, int format, ISaveOptions options)](#save-java.io.OutputStream-int-com.aspose.slides.ISaveOptions-) | Saves all slides of a presentation to a stream in the specified format and with additional options. |
| [save(IXamlOptions options)](#save-com.aspose.slides.IXamlOptions-) | Saves all slides of a presentation to a set of files representing XAML markup. |
| [getThumbnails(INotesCommentsLayoutingOptions notesCommentsLayouting)](#getThumbnails-com.aspose.slides.INotesCommentsLayoutingOptions-) | Returns a Thumbnail BufferedImage objects for all slides of a presentation. |
| [getThumbnails(INotesCommentsLayoutingOptions notesCommentsLayouting, int[] slides)](#getThumbnails-com.aspose.slides.INotesCommentsLayoutingOptions-int---) | Returns a Thumbnail BufferedImage objects for specified slides of a presentation. |
| [getThumbnails(INotesCommentsLayoutingOptions notesCommentsLayouting, float scaleX, float scaleY)](#getThumbnails-com.aspose.slides.INotesCommentsLayoutingOptions-float-float-) | Returns a Thumbnail BufferedImage objects for all slides of a presentation with custom scaling. |
| [getThumbnails(INotesCommentsLayoutingOptions notesCommentsLayouting, int[] slides, float scaleX, float scaleY)](#getThumbnails-com.aspose.slides.INotesCommentsLayoutingOptions-int---float-float-) | Returns a Thumbnail BufferedImage objects for specified slides of a presentation with custom scaling. |
| [getThumbnails(INotesCommentsLayoutingOptions notesCommentsLayouting, Dimension imageSize)](#getThumbnails-com.aspose.slides.INotesCommentsLayoutingOptions-java.awt.Dimension-) | Returns a Thumbnail BufferedImage objects for all slides of a presentation with specified size. |
| [getThumbnails(INotesCommentsLayoutingOptions notesCommentsLayouting, int[] slides, Dimension imageSize)](#getThumbnails-com.aspose.slides.INotesCommentsLayoutingOptions-int---java.awt.Dimension-) | Returns a Thumbnail BufferedImage objects for specified slides of a presentation with specified size. |
| [getThumbnails(IRenderingOptions options)](#getThumbnails-com.aspose.slides.IRenderingOptions-) | Returns a Thumbnail BufferedImage objects for all slides of a presentation. |
| [getThumbnails(IRenderingOptions options, int[] slides)](#getThumbnails-com.aspose.slides.IRenderingOptions-int---) | Returns a Thumbnail BufferedImage objects for specified slides of a presentation. |
| [getThumbnails(IRenderingOptions options, float scaleX, float scaleY)](#getThumbnails-com.aspose.slides.IRenderingOptions-float-float-) | Returns a Thumbnail BufferedImage objects for all slides of a presentation with custom scaling. |
| [getThumbnails(IRenderingOptions options, int[] slides, float scaleX, float scaleY)](#getThumbnails-com.aspose.slides.IRenderingOptions-int---float-float-) | Returns a Thumbnail BufferedImage objects for specified slides of a presentation with custom scaling. |
| [getThumbnails(IRenderingOptions options, Dimension imageSize)](#getThumbnails-com.aspose.slides.IRenderingOptions-java.awt.Dimension-) | Returns a Thumbnail BufferedImage objects for all slides of a presentation with specified size. |
| [getThumbnails(IRenderingOptions options, int[] slides, Dimension imageSize)](#getThumbnails-com.aspose.slides.IRenderingOptions-int---java.awt.Dimension-) | Returns a Thumbnail BufferedImage objects for specified slides of a presentation with specified size. |
| [save(String fname, int[] slides, int format)](#save-java.lang.String-int---int-) | Saves specified slides of a presentation to a file with the specified format with page number keeping. |
| [save(String fname, int[] slides, int format, ISaveOptions options)](#save-java.lang.String-int---int-com.aspose.slides.ISaveOptions-) | Saves specified slides of a presentation to a file with the specified format with page number keeping. |
| [save(OutputStream stream, int[] slides, int format)](#save-java.io.OutputStream-int---int-) | Saves specified slides of a presentation to a stream in the specified format with page number keeping. |
| [save(OutputStream stream, int[] slides, int format, ISaveOptions options)](#save-java.io.OutputStream-int---int-com.aspose.slides.ISaveOptions-) | Saves specified slides of a presentation to a stream in the specified format with page number keeping. |
| [joinPortionsWithSameFormatting()](#joinPortionsWithSameFormatting--) | Joins runs with same formatting in all paragraphs in all acceptable shapes in all slides. |
| [dispose()](#dispose--) | Releases all resources used by this Presentation object. |
| [getPresentation()](#getPresentation--) | Returns the parent presentation of a text. |
### Presentation() {#Presentation--}
```
public Presentation()
```


This constructor creates new presentation from scratch. Created presentation has one empty slide.

### Presentation(LoadOptions loadOptions) {#Presentation-com.aspose.slides.LoadOptions-}
```
public Presentation(LoadOptions loadOptions)
```


This constructor creates new presentation from scratch. Created presentation has one empty slide.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| loadOptions | [LoadOptions](../../com.aspose.slides/loadoptions) | Additional load options. |

### Presentation(InputStream stream) {#Presentation-java.io.InputStream-}
```
public Presentation(InputStream stream)
```


This constructor is the primary mechanism for reading an existing Presentation.

--------------------

> ```
> FileInputStream fis = new FileInputStream("demo.pptx");
>  Presentation pres = new Presentation(fis);
>  fis.close();
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.InputStream | Input stream. |

### Presentation(InputStream stream, LoadOptions loadOptions) {#Presentation-java.io.InputStream-com.aspose.slides.LoadOptions-}
```
public Presentation(InputStream stream, LoadOptions loadOptions)
```


This constructor is the primary mechanism for reading an existing Presentation.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.InputStream | Input stream. |
| loadOptions | [LoadOptions](../../com.aspose.slides/loadoptions) | Additional load options. |

### Presentation(String file) {#Presentation-java.lang.String-}
```
public Presentation(String file)
```


This constructor gets a source file path from which the contents of the Presentation are read.

--------------------

> ```
> Presentation pres = new Presentation("demo.pptx");
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| file | java.lang.String | Input file. |

### Presentation(String file, LoadOptions loadOptions) {#Presentation-java.lang.String-com.aspose.slides.LoadOptions-}
```
public Presentation(String file, LoadOptions loadOptions)
```


This constructor gets a source file path from which the contents of the Presentation are read.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| file | java.lang.String | Input file. |
| loadOptions | [LoadOptions](../../com.aspose.slides/loadoptions) | Additional load options. |

### getCurrentDateTime() {#getCurrentDateTime--}
```
public final Date getCurrentDateTime()
```


Returns or sets date and time which will substitute content of datetime fields. Time of this Presentation object creation by default. Read/write java.util.Date.

**Returns:**
java.util.Date
### setCurrentDateTime(Date value) {#setCurrentDateTime-java.util.Date-}
```
public final void setCurrentDateTime(Date value)
```


Returns or sets date and time which will substitute content of datetime fields. Time of this Presentation object creation by default. Read/write java.util.Date.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.util.Date |  |

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```


Returns Parent\_Immediate object. Read-only IDOMObject.

**Returns:**
com.aspose.slides.IDOMObject
### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public final IPresentationHeaderFooterManager getHeaderFooterManager()
```


Returns actual HeaderFooter manager. Read-only [IPresentationHeaderFooterManager](../../com.aspose.slides/ipresentationheaderfootermanager).

--------------------

> ```
> The following example shows how to set footer visibility inside Slide of PowerPoint Presentation.
>  
>  Presentation pres = new Presentation("presentation.ppt");
>  try
>  {
>      IBaseSlideHeaderFooterManager headerFooterManager = pres.getSlides().get_Item(0).getHeaderFooterManager();
>      if (!headerFooterManager.isFooterVisible()) // Property IsFooterVisible is used for indicating that a slide footer placeholder is not present.
>      {
>          headerFooterManager.setFooterVisibility(true); // Method SetFooterVisibility is used for making a slide footer placeholder visible.
>      }
>      if (!headerFooterManager.isSlideNumberVisible()) // Property IsSlideNumberVisible is used for indicating that a slide page number placeholder is not present.
>      {
>          headerFooterManager.setSlideNumberVisibility(true); // Method SetSlideNumberVisibility is used for making a slide page number placeholder visible.
>      }
>      if (!headerFooterManager.isDateTimeVisible()) // Property IsDateTimeVisible is used for indicating that a slide date-time placeholder is not present.
>      {
>          headerFooterManager.setDateTimeVisibility(true); // Method SetFooterVisibility is used for making a slide date-time placeholder visible.
>      }
>      headerFooterManager.setFooterText("Footer text"); // Method SetFooterText is used for setting text to slide footer placeholder.
>      headerFooterManager.setDateTimeText("Date and time text"); // Method SetDateTimeText is used for setting text to slide date-time placeholder.
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
>      headerFooterManager.setFooterAndChildFootersVisibility(true); // Method SetFooterAndChildFootersVisibility is used for making a master slide and all child footer placeholders visible.
>      headerFooterManager.setSlideNumberAndChildSlideNumbersVisibility(true); // Method SetSlideNumberAndChildSlideNumbersVisibility is used for making a master slide and all child page number placeholders visible.
>      headerFooterManager.setDateTimeAndChildDateTimesVisibility(true); // Method SetDateTimeAndChildDateTimesVisibility is used for making a master slide and all child date-time placeholders visible.
> 
>      headerFooterManager.setFooterAndChildFootersText("Footer text"); // Method SetFooterAndChildFootersText is used for setting text to master slide and all child footer placeholders.
>      headerFooterManager.setDateTimeAndChildDateTimesText("Date and time text"); // Method SetDateTimeAndChildDateTimesText is used for setting text to master slide and all child date-time placeholders.
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


Gets manager of the permissions for this presentation. Read-only [IProtectionManager](../../com.aspose.slides/iprotectionmanager).

**Returns:**
[IProtectionManager](../../com.aspose.slides/iprotectionmanager)
### getSlides() {#getSlides--}
```
public final ISlideCollection getSlides()
```


Returns a list of all slides that are defined in the presentation. Read-only [ISlideCollection](../../com.aspose.slides/islidecollection).

--------------------

> ```
> The following example shows how to set slides' background color of PowerPoint Presentation.
>  
>  // Instantiate the Presentation class that represents the presentation file
>  Presentation pres = new Presentation();
>  try
>  {
>      // Set the background color of the first ISlide to Blue
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
>  // Instantiate the Presentation class that represents the presentation file
>  Presentation pres = new Presentation("SetImageAsBackground.pptx");
>  try {
>      // Set the background with Image
>      pres.getSlides().get_Item(0).getBackground().setType(BackgroundType.OwnBackground);
>      pres.getSlides().get_Item(0).getBackground().getFillFormat().setFillType(FillType.Picture);
>      pres.getSlides().get_Item(0).getBackground().getFillFormat().getPictureFillFormat().setPictureFillMode(PictureFillMode.Stretch);
>      // Set the picture
>      BufferedImage img = ImageIO.read(new File("Tulips.jpg"));
>      // Add image to presentation's images collection
>      IPPImage imgx = pres.getImages().addImage(img);
>      pres.getSlides().get_Item(0).getBackground().getFillFormat().getPictureFillFormat().getPicture().setImage(imgx);
>      // Write the presentation to disk
>      pres.save("ContentBG_Img_out.pptx", SaveFormat.Pptx);
>  } catch (IOException e) { }
>  finally
>  {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to add slide transition Presentation.
>  
>  // Instantiate Presentation class to load the source presentation file
>  Presentation pres = new Presentation("AccessSlides.pptx");
>  try
>  {
>      // Apply circle type transition on slide 1
>      pres.getSlides().get_Item(0).getSlideShowTransition().setType(TransitionType.Circle);
>      // Apply comb type transition on slide 2
>      pres.getSlides().get_Item(1).getSlideShowTransition().setType(TransitionType.Comb);
>      // Write the presentation to disk
>      pres.save("SampleTransition_out.pptx", SaveFormat.Pptx);
>  }
>  finally
>  {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to add advanced slide Transition.
>  
>  // Instantiate Presentation class that represents a presentation file
>  Presentation pres = new Presentation("BetterSlideTransitions.pptx");
>  try
>  {
>      // Apply circle type transition on slide 1
>      pres.getSlides().get_Item(0).getSlideShowTransition().setType(TransitionType.Circle);
>      // Set the transition time of 3 seconds
>      pres.getSlides().get_Item(0).getSlideShowTransition().setAdvanceOnClick(true);
>      pres.getSlides().get_Item(0).getSlideShowTransition().setAdvanceAfterTime(3000);
>      // Apply comb type transition on slide 2
>      pres.getSlides().get_Item(1).getSlideShowTransition().setType(TransitionType.Comb);
>      // Set the transition time of 5 seconds
>      pres.getSlides().get_Item(1).getSlideShowTransition().setAdvanceOnClick(true);
>      pres.getSlides().get_Item(1).getSlideShowTransition().setAdvanceAfterTime(5000);
>      // Apply zoom type transition on slide 3
>      pres.getSlides().get_Item(2).getSlideShowTransition().setType(TransitionType.Zoom);
>      // Set the transition time of 7 seconds
>      pres.getSlides().get_Item(2).getSlideShowTransition().setAdvanceOnClick(true);
>      pres.getSlides().get_Item(2).getSlideShowTransition().setAdvanceAfterTime(7000);
>      // Write the presentation to disk
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


Returns a list of all slides sections that are defined in the presentation. Read-only [ISectionCollection](../../com.aspose.slides/isectioncollection).

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
>      // section1 will be ended at newSlide2 and after it section2 will start
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


Returns slide size object. Read-only [ISlideSize](../../com.aspose.slides/islidesize).

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

**Returns:**
[ISlideSize](../../com.aspose.slides/islidesize)
### getNotesSize() {#getNotesSize--}
```
public final INotesSize getNotesSize()
```


Returns notes slide size object. Read-only [INotesSize](../../com.aspose.slides/inotessize).

**Returns:**
[INotesSize](../../com.aspose.slides/inotessize)
### getLayoutSlides() {#getLayoutSlides--}
```
public final IGlobalLayoutSlideCollection getLayoutSlides()
```


Returns a list of all layout slides that are defined in the presentation. Read-only [IGlobalLayoutSlideCollection](../../com.aspose.slides/igloballayoutslidecollection).

--------------------

You can access to alternative API for adding/inserting/removing/cloning layout slides by using IMasterSlide.LayoutSlides property.

**Returns:**
[IGlobalLayoutSlideCollection](../../com.aspose.slides/igloballayoutslidecollection)
### getMasters() {#getMasters--}
```
public final IMasterSlideCollection getMasters()
```


Returns a list of all master slides that are defined in the presentation. Read-only [IMasterSlideCollection](../../com.aspose.slides/imasterslidecollection).

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


Returns notes master manager. Read-only [IMasterNotesSlideManager](../../com.aspose.slides/imasternotesslidemanager).

**Returns:**
[IMasterNotesSlideManager](../../com.aspose.slides/imasternotesslidemanager)
### getMasterHandoutSlideManager() {#getMasterHandoutSlideManager--}
```
public final IMasterHandoutSlideManager getMasterHandoutSlideManager()
```


Returns handout master manager. Read-only [IMasterHandoutSlideManager](../../com.aspose.slides/imasterhandoutslidemanager).

**Returns:**
[IMasterHandoutSlideManager](../../com.aspose.slides/imasterhandoutslidemanager)
### getFontsManager() {#getFontsManager--}
```
public final IFontsManager getFontsManager()
```


Returns fonts manager. Read-only [IFontsManager](../../com.aspose.slides/ifontsmanager).

--------------------

> ```
> The following example shows how to add embedded fonts to PowerPoint Presentation.
>  
>  // Load presentation
>  Presentation pres = new Presentation("Fonts.pptx");
>  try {
>      // Load source font to be replaced
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
>      // Save the presentation
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


Returns default text style for shapes. Read-only [ITextStyle](../../com.aspose.slides/itextstyle).

**Returns:**
[ITextStyle](../../com.aspose.slides/itextstyle)
### getCommentAuthors() {#getCommentAuthors--}
```
public final ICommentAuthorCollection getCommentAuthors()
```


Returns the collection of comments autors. Read-only [ICommentAuthorCollection](../../com.aspose.slides/icommentauthorcollection).

**Returns:**
[ICommentAuthorCollection](../../com.aspose.slides/icommentauthorcollection)
### getDocumentProperties() {#getDocumentProperties--}
```
public final IDocumentProperties getDocumentProperties()
```


Returns DocumentProperties object which contains standard and custom document properties. Read-only [IDocumentProperties](../../com.aspose.slides/idocumentproperties).

**Returns:**
[IDocumentProperties](../../com.aspose.slides/idocumentproperties)
### getImages() {#getImages--}
```
public final IImageCollection getImages()
```


Returns the collection of all images in the presentation. Read-only [IImageCollection](../../com.aspose.slides/iimagecollection).

--------------------

> ```
> The following examples shows how to add image as BLOB in PowerPoint Presentation.
>  
>  // create a new presentation which will contain this image
>  Presentation pres = new Presentation();
>  try
>  {
>      // supposed we have the large image file we want to include into the presentation
>      FileInputStream fip = new FileInputStream("large_image.jpg");
>      try
>      {
>          // let's add the image to the presentation - we choose KeepLocked behavior, because we not
>          // have an intent to access the "largeImage.png" file.
>          IPPImage img = pres.getImages().addImage(fip, LoadingStreamBehavior.KeepLocked);
>          pres.getSlides().get_Item(0).getShapes().addPictureFrame(ShapeType.Rectangle, 0, 0, 300, 200, img);
>          // save the presentation. Despite that the output presentation will be
>          // large, the memory consumption will be low the whole lifetime of the pres object
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

**Returns:**
[IImageCollection](../../com.aspose.slides/iimagecollection)
### getAudios() {#getAudios--}
```
public final IAudioCollection getAudios()
```


Returns the collection of all embedded audio files in the presentation. Read-only [IAudioCollection](../../com.aspose.slides/iaudiocollection).

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

**Returns:**
[IAudioCollection](../../com.aspose.slides/iaudiocollection)
### getVideos() {#getVideos--}
```
public final IVideoCollection getVideos()
```


Returns the collection of all embedded video files in the presentation. Read-only [IVideoCollection](../../com.aspose.slides/ivideocollection).

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

**Returns:**
[IVideoCollection](../../com.aspose.slides/ivideocollection)
### getSlideShowSettings() {#getSlideShowSettings--}
```
public final SlideShowSettings getSlideShowSettings()
```


Returns the slide show settings for the presentation.

**Returns:**
[SlideShowSettings](../../com.aspose.slides/slideshowsettings)
### getDigitalSignatures() {#getDigitalSignatures--}
```
public final IDigitalSignatureCollection getDigitalSignatures()
```


Returns the collection of signatures used to sign the presentation. Read-only [IDigitalSignatureCollection](../../com.aspose.slides/idigitalsignaturecollection).

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

**Returns:**
[IDigitalSignatureCollection](../../com.aspose.slides/idigitalsignaturecollection)
### getCustomData() {#getCustomData--}
```
public final ICustomData getCustomData()
```


Returns the presentation's custom data. Read-only [ICustomData](../../com.aspose.slides/icustomdata).

**Returns:**
[ICustomData](../../com.aspose.slides/icustomdata)
### getAllCustomXmlParts() {#getAllCustomXmlParts--}
```
public final ICustomXmlPart[] getAllCustomXmlParts()
```


Returns all custom data parts in the presentaion. Read-only ICustomXmlPart[].

--------------------

> ```
> The following examples show how to clear all custom xml parts from PowerPoint Presentation.
>  
>  Presentation pres = new Presentation("PresentationWithCustomXml.pptx");
>  try {
>      // Iterate all custom XML Parts
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

**Returns:**
com.aspose.slides.ICustomXmlPart[]
### getVbaProject() {#getVbaProject--}
```
public final IVbaProject getVbaProject()
```


Gets or sets VBA project with presentation macros. Read/write [IVbaProject](../../com.aspose.slides/ivbaproject).

**Returns:**
[IVbaProject](../../com.aspose.slides/ivbaproject)
### setVbaProject(IVbaProject value) {#setVbaProject-com.aspose.slides.IVbaProject-}
```
public final void setVbaProject(IVbaProject value)
```


Gets or sets VBA project with presentation macros. Read/write [IVbaProject](../../com.aspose.slides/ivbaproject).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IVbaProject](../../com.aspose.slides/ivbaproject) |  |

### getHyperlinkQueries() {#getHyperlinkQueries--}
```
public final IHyperlinkQueries getHyperlinkQueries()
```


Provides easy access to all hyperlinks contained in all presentation slides (not in master, layout, notes slides). Read-only [IHyperlinkQueries](../../com.aspose.slides/ihyperlinkqueries).

**Returns:**
[IHyperlinkQueries](../../com.aspose.slides/ihyperlinkqueries)
### getViewProperties() {#getViewProperties--}
```
public final IViewProperties getViewProperties()
```


Gets presentation wide view properties. Read-only [IViewProperties](../../com.aspose.slides/iviewproperties).

**Returns:**
[IViewProperties](../../com.aspose.slides/iviewproperties)
### getFirstSlideNumber() {#getFirstSlideNumber--}
```
public final int getFirstSlideNumber()
```


Represents the first slide number in the presentation

**Returns:**
int
### setFirstSlideNumber(int value) {#setFirstSlideNumber-int-}
```
public final void setFirstSlideNumber(int value)
```


Represents the first slide number in the presentation

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getSlideById(long id) {#getSlideById-long-}
```
public final IBaseSlide getSlideById(long id)
```


Returns a Slide, MasterSlide or LayoutSlide by Id.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| id | long | Id of a slide. |

**Returns:**
[IBaseSlide](../../com.aspose.slides/ibaseslide) - IBaseSlide object.
### getSourceFormat() {#getSourceFormat--}
```
public final int getSourceFormat()
```


Returns information about from which format presentation was loaded. Read-only [SourceFormat](../../com.aspose.slides/sourceformat).

**Returns:**
int
### getMasterTheme() {#getMasterTheme--}
```
public final IMasterTheme getMasterTheme()
```


Returns master theme. Read-only [IMasterTheme](../../com.aspose.slides/imastertheme).

--------------------

> ```
> The following examples shows how to change a theme effect by altering parts of elements of PowerPoint Presentation.
>  
>  //Instantiate a presentation object that represents a presentation file
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

**Returns:**
[IMasterTheme](../../com.aspose.slides/imastertheme)
### save(String fname, int format) {#save-java.lang.String-int-}
```
public final void save(String fname, int format)
```


Saves all slides of a presentation to a file with the specified format.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fname | java.lang.String | Path to the created file. |
| format | int | Format of the exported data. |

### save(OutputStream stream, int format) {#save-java.io.OutputStream-int-}
```
public final void save(OutputStream stream, int format)
```


Saves all slides of a presentation to a stream in the specified format.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.OutputStream | Output stream. |
| format | int | Format of the exported data. |

### save(String fname, int format, ISaveOptions options) {#save-java.lang.String-int-com.aspose.slides.ISaveOptions-}
```
public final void save(String fname, int format, ISaveOptions options)
```


Saves all slides of a presentation to a file with the specified format and with additional options.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fname | java.lang.String | Path to the created file. |
| format | int | Format of the exported data. |
| options | [ISaveOptions](../../com.aspose.slides/isaveoptions) | Additional format options. |

### save(OutputStream stream, int format, ISaveOptions options) {#save-java.io.OutputStream-int-com.aspose.slides.ISaveOptions-}
```
public final void save(OutputStream stream, int format, ISaveOptions options)
```


Saves all slides of a presentation to a stream in the specified format and with additional options.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.OutputStream | Output stream. |
| format | int | Format of the exported data. |
| options | [ISaveOptions](../../com.aspose.slides/isaveoptions) | Additional format options. |

### save(IXamlOptions options) {#save-com.aspose.slides.IXamlOptions-}
```
public final void save(IXamlOptions options)
```


Saves all slides of a presentation to a set of files representing XAML markup.

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
| options | [IXamlOptions](../../com.aspose.slides/ixamloptions) | The XAML format options. |

### getThumbnails(INotesCommentsLayoutingOptions notesCommentsLayouting) {#getThumbnails-com.aspose.slides.INotesCommentsLayoutingOptions-}
```
public final BufferedImage[] getThumbnails(INotesCommentsLayoutingOptions notesCommentsLayouting)
```


Returns a Thumbnail BufferedImage objects for all slides of a presentation.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| notesCommentsLayouting | [INotesCommentsLayoutingOptions](../../com.aspose.slides/inotescommentslayoutingoptions) | Options for notes and comments layouting. |

**Returns:**
java.awt.image.BufferedImage[] - BufferedImage objects.
### getThumbnails(INotesCommentsLayoutingOptions notesCommentsLayouting, int[] slides) {#getThumbnails-com.aspose.slides.INotesCommentsLayoutingOptions-int---}
```
public final BufferedImage[] getThumbnails(INotesCommentsLayoutingOptions notesCommentsLayouting, int[] slides)
```


Returns a Thumbnail BufferedImage objects for specified slides of a presentation.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| notesCommentsLayouting | [INotesCommentsLayoutingOptions](../../com.aspose.slides/inotescommentslayoutingoptions) | Options for notes and comments layouting. |
| slides | int[] | Array with slide positions, starting from 1. |

**Returns:**
java.awt.image.BufferedImage[] - BufferedImage objects.
### getThumbnails(INotesCommentsLayoutingOptions notesCommentsLayouting, float scaleX, float scaleY) {#getThumbnails-com.aspose.slides.INotesCommentsLayoutingOptions-float-float-}
```
public final BufferedImage[] getThumbnails(INotesCommentsLayoutingOptions notesCommentsLayouting, float scaleX, float scaleY)
```


Returns a Thumbnail BufferedImage objects for all slides of a presentation with custom scaling.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| notesCommentsLayouting | [INotesCommentsLayoutingOptions](../../com.aspose.slides/inotescommentslayoutingoptions) | Options for notes and comments layouting. |
| scaleX | float | The value by which to scale this Thumbnail in the x-axis direction. |
| scaleY | float | The value by which to scale this Thumbnail in the y-axis direction. |

**Returns:**
java.awt.image.BufferedImage[] - BufferedImage objects.
### getThumbnails(INotesCommentsLayoutingOptions notesCommentsLayouting, int[] slides, float scaleX, float scaleY) {#getThumbnails-com.aspose.slides.INotesCommentsLayoutingOptions-int---float-float-}
```
public final BufferedImage[] getThumbnails(INotesCommentsLayoutingOptions notesCommentsLayouting, int[] slides, float scaleX, float scaleY)
```


Returns a Thumbnail BufferedImage objects for specified slides of a presentation with custom scaling.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| notesCommentsLayouting | [INotesCommentsLayoutingOptions](../../com.aspose.slides/inotescommentslayoutingoptions) | Options for notes and comments layouting. |
| slides | int[] | Array with slide positions, starting from 1. |
| scaleX | float | The value by which to scale this Thumbnail in the x-axis direction. |
| scaleY | float | The value by which to scale this Thumbnail in the y-axis direction. |

**Returns:**
java.awt.image.BufferedImage[] - BufferedImage objects.
### getThumbnails(INotesCommentsLayoutingOptions notesCommentsLayouting, Dimension imageSize) {#getThumbnails-com.aspose.slides.INotesCommentsLayoutingOptions-java.awt.Dimension-}
```
public final BufferedImage[] getThumbnails(INotesCommentsLayoutingOptions notesCommentsLayouting, Dimension imageSize)
```


Returns a Thumbnail BufferedImage objects for all slides of a presentation with specified size.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| notesCommentsLayouting | [INotesCommentsLayoutingOptions](../../com.aspose.slides/inotescommentslayoutingoptions) | Options for notes and comments layouting. |
| imageSize | java.awt.Dimension | Size of the image to create. |

**Returns:**
java.awt.image.BufferedImage[] - BufferedImage objects.
### getThumbnails(INotesCommentsLayoutingOptions notesCommentsLayouting, int[] slides, Dimension imageSize) {#getThumbnails-com.aspose.slides.INotesCommentsLayoutingOptions-int---java.awt.Dimension-}
```
public final BufferedImage[] getThumbnails(INotesCommentsLayoutingOptions notesCommentsLayouting, int[] slides, Dimension imageSize)
```


Returns a Thumbnail BufferedImage objects for specified slides of a presentation with specified size.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| notesCommentsLayouting | [INotesCommentsLayoutingOptions](../../com.aspose.slides/inotescommentslayoutingoptions) | Options for notes and comments layouting. |
| slides | int[] | Array with slide positions, starting from 1. |
| imageSize | java.awt.Dimension | Size of the image to create. |

**Returns:**
java.awt.image.BufferedImage[] - BufferedImage objects.
### getThumbnails(IRenderingOptions options) {#getThumbnails-com.aspose.slides.IRenderingOptions-}
```
public final BufferedImage[] getThumbnails(IRenderingOptions options)
```


Returns a Thumbnail BufferedImage objects for all slides of a presentation.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Tiff options. |

**Returns:**
java.awt.image.BufferedImage[] - BufferedImage objects.
### getThumbnails(IRenderingOptions options, int[] slides) {#getThumbnails-com.aspose.slides.IRenderingOptions-int---}
```
public final BufferedImage[] getThumbnails(IRenderingOptions options, int[] slides)
```


Returns a Thumbnail BufferedImage objects for specified slides of a presentation.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Tiff options. |
| slides | int[] | Array with slide positions, starting from 1. |

**Returns:**
java.awt.image.BufferedImage[] - BufferedImage objects.
### getThumbnails(IRenderingOptions options, float scaleX, float scaleY) {#getThumbnails-com.aspose.slides.IRenderingOptions-float-float-}
```
public final BufferedImage[] getThumbnails(IRenderingOptions options, float scaleX, float scaleY)
```


Returns a Thumbnail BufferedImage objects for all slides of a presentation with custom scaling.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Tiff options. |
| scaleX | float | The value by which to scale this Thumbnail in the x-axis direction. |
| scaleY | float | The value by which to scale this Thumbnail in the y-axis direction. |

**Returns:**
java.awt.image.BufferedImage[] - BufferedImage objects.
### getThumbnails(IRenderingOptions options, int[] slides, float scaleX, float scaleY) {#getThumbnails-com.aspose.slides.IRenderingOptions-int---float-float-}
```
public final BufferedImage[] getThumbnails(IRenderingOptions options, int[] slides, float scaleX, float scaleY)
```


Returns a Thumbnail BufferedImage objects for specified slides of a presentation with custom scaling.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Tiff options. |
| slides | int[] | Array with slide positions, starting from 1. |
| scaleX | float | The value by which to scale this Thumbnail in the x-axis direction. |
| scaleY | float | The value by which to scale this Thumbnail in the y-axis direction. |

**Returns:**
java.awt.image.BufferedImage[] - BufferedImage objects.
### getThumbnails(IRenderingOptions options, Dimension imageSize) {#getThumbnails-com.aspose.slides.IRenderingOptions-java.awt.Dimension-}
```
public final BufferedImage[] getThumbnails(IRenderingOptions options, Dimension imageSize)
```


Returns a Thumbnail BufferedImage objects for all slides of a presentation with specified size.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Tiff options. |
| imageSize | java.awt.Dimension | Size of the image to create. |

**Returns:**
java.awt.image.BufferedImage[] - BufferedImage objects.
### getThumbnails(IRenderingOptions options, int[] slides, Dimension imageSize) {#getThumbnails-com.aspose.slides.IRenderingOptions-int---java.awt.Dimension-}
```
public final BufferedImage[] getThumbnails(IRenderingOptions options, int[] slides, Dimension imageSize)
```


Returns a Thumbnail BufferedImage objects for specified slides of a presentation with specified size.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Tiff options. |
| slides | int[] | Array with slide positions, starting from 1. |
| imageSize | java.awt.Dimension | Size of the image to create. |

**Returns:**
java.awt.image.BufferedImage[] - BufferedImage objects.
### save(String fname, int[] slides, int format) {#save-java.lang.String-int---int-}
```
public final void save(String fname, int[] slides, int format)
```


Saves specified slides of a presentation to a file with the specified format with page number keeping.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fname | java.lang.String | Path to the created file. |
| slides | int[] | Array with slide positions, starting from 1. |
| format | int | Format of the exported data. |

### save(String fname, int[] slides, int format, ISaveOptions options) {#save-java.lang.String-int---int-com.aspose.slides.ISaveOptions-}
```
public final void save(String fname, int[] slides, int format, ISaveOptions options)
```


Saves specified slides of a presentation to a file with the specified format with page number keeping.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fname | java.lang.String | Path to the created file. |
| slides | int[] | Array with slide positions, starting from 1. |
| format | int | Format of the exported data. |
| options | [ISaveOptions](../../com.aspose.slides/isaveoptions) | Additional format options. |

### save(OutputStream stream, int[] slides, int format) {#save-java.io.OutputStream-int---int-}
```
public final void save(OutputStream stream, int[] slides, int format)
```


Saves specified slides of a presentation to a stream in the specified format with page number keeping.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.OutputStream | Output stream. |
| slides | int[] | Array with slide positions, starting from 1. |
| format | int | Format of the exported data. |

### save(OutputStream stream, int[] slides, int format, ISaveOptions options) {#save-java.io.OutputStream-int---int-com.aspose.slides.ISaveOptions-}
```
public final void save(OutputStream stream, int[] slides, int format, ISaveOptions options)
```


Saves specified slides of a presentation to a stream in the specified format with page number keeping.

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
| stream | java.io.OutputStream | Output stream. |
| slides | int[] | Array with slide positions, starting from 1. |
| format | int | Format of the exported data. |
| options | [ISaveOptions](../../com.aspose.slides/isaveoptions) | Additional format options. |

### joinPortionsWithSameFormatting() {#joinPortionsWithSameFormatting--}
```
public final void joinPortionsWithSameFormatting()
```


Joins runs with same formatting in all paragraphs in all acceptable shapes in all slides.

### dispose() {#dispose--}
```
public final void dispose()
```


Releases all resources used by this Presentation object.

### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```


Returns the parent presentation of a text. Read-only [IPresentation](../../com.aspose.slides/ipresentation).

**Returns:**
[IPresentation](../../com.aspose.slides/ipresentation)
