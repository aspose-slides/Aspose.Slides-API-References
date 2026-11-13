---
title: Presentation
second_title: Riferimento API di Aspose.Slides per Java
description: Rappresenta una presentazione Microsoft PowerPoint.
type: docs
url: /it/com.aspose.slides/presentation/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.slides.IPresentation](../../com.aspose.slides/ipresentation), com.aspose.slides.IDOMObject
```
public final class Presentation implements IPresentation, IDOMObject
```

Rappresenta una presentazione Microsoft PowerPoint.

--------------------

> ```
> The following example shows how to create PowerPoint Presentation.
>   
>  // Crea un'istanza di un oggetto Presentation che rappresenta un file di presentazione
>  Presentation pres = new Presentation();
>  try {
>      // Ottieni la prima diapositiva
>      ISlide slide = pres.getSlides().get_Item(0);
>      // Aggiungi una forma automatica di tipo linea
>      slide.getShapes().addAutoShape(ShapeType.Line, 50, 150, 300, 0);
>      // Salva il file di presentazione.
>      pres.save("NewPresentation_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>   
>   The following example shows how to open and save Presentation.
>   
>  // Carica qualsiasi file supportato in Presentation, ad es. ppt, pptx, odp ecc.
>  Presentation pres = new Presentation("Sample.odp");
>  try {
>      // Salva il file di presentazione.
>      pres.save("OutputPresenation.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [Presentation()](#Presentation--) | Questo costruttore crea una nuova presentazione da zero. |
| [Presentation(LoadOptions loadOptions)](#Presentation-com.aspose.slides.LoadOptions-) | Questo costruttore crea una nuova presentazione da zero. |
| [Presentation(InputStream stream)](#Presentation-java.io.InputStream-) | Questo costruttore è il meccanismo primario per leggere una Presentazione esistente. |
| [Presentation(InputStream stream, LoadOptions loadOptions)](#Presentation-java.io.InputStream-com.aspose.slides.LoadOptions-) | Questo costruttore è il meccanismo primario per leggere una Presentazione esistente. |
| [Presentation(String file)](#Presentation-java.lang.String-) | Questo costruttore ottiene il percorso del file sorgente da cui vengono letti i contenuti della Presentazione. |
| [Presentation(String file, LoadOptions loadOptions)](#Presentation-java.lang.String-com.aspose.slides.LoadOptions-) | Questo costruttore ottiene il percorso del file sorgente da cui vengono letti i contenuti della Presentazione. |

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getCurrentDateTime()](#getCurrentDateTime--) | Restituisce o imposta data e ora che sostituiranno il contenuto dei campi datetime. |
| [setCurrentDateTime(Date value)](#setCurrentDateTime-java.util.Date-) | Restituisce o imposta data e ora che sostituiranno il contenuto dei campi datetime. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | Restituisce il gestore HeaderFooter attuale. |
| [getProtectionManager()](#getProtectionManager--) | Ottiene il gestore delle autorizzazioni per questa presentazione. |
| [getSlides()](#getSlides--) | Restituisce un elenco di tutte le diapositive definite nella presentazione. |
| [getSections()](#getSections--) | Restituisce un elenco di tutte le sezioni diapositive definite nella presentazione. |
| [getSlideSize()](#getSlideSize--) | Restituisce l'oggetto dimensione diapositiva. |
| [getNotesSize()](#getNotesSize--) | Restituisce l'oggetto dimensione diapositiva note. |
| [getLayoutSlides()](#getLayoutSlides--) | Restituisce un elenco di tutte le diapositive layout definite nella presentazione. |
| [getMasters()](#getMasters--) | Restituisce un elenco di tutte le diapositive master definite nella presentazione. |
| [getMasterNotesSlideManager()](#getMasterNotesSlideManager--) | Restituisce il gestore master delle note. |
| [getMasterHandoutSlideManager()](#getMasterHandoutSlideManager--) | Restituisce il gestore master dei dispense. |
| [getFontsManager()](#getFontsManager--) | Restituisce il gestore dei font. |
| [getDefaultTextStyle()](#getDefaultTextStyle--) | Restituisce lo stile di testo predefinito per le forme. |
| [getCommentAuthors()](#getCommentAuthors--) | Restituisce la collezione degli autori dei commenti. |
| [getDocumentProperties()](#getDocumentProperties--) | Restituisce l'oggetto DocumentProperties che contiene le proprietà del documento standard e personalizzate. |
| [getImages()](#getImages--) | Restituisce la collezione di tutte le immagini nella presentazione. |
| [getAudios()](#getAudios--) | Restituisce la collezione di tutti i file audio incorporati nella presentazione. |
| [getVideos()](#getVideos--) | Restituisce la collezione di tutti i file video incorporati nella presentazione. |
| [getSlideShowSettings()](#getSlideShowSettings--) | Restituisce le impostazioni della presentazione. |
| [getDigitalSignatures()](#getDigitalSignatures--) | Restituisce la collezione di firme usate per firmare la presentazione. |
| [getCustomData()](#getCustomData--) | Restituisce i dati personalizzati della presentazione. |
| [getAllCustomXmlParts()](#getAllCustomXmlParts--) | Restituisce tutte le parti di dati personalizzati nella presentazione. |
| [getVbaProject()](#getVbaProject--) | Ottiene o imposta il progetto VBA con le macro della presentazione. |
| [setVbaProject(IVbaProject value)](#setVbaProject-com.aspose.slides.IVbaProject-) | Ottiene o imposta il progetto VBA con le macro della presentazione. |
| [getHyperlinkQueries()](#getHyperlinkQueries--) | Fornisce un facile accesso a tutti i collegamenti ipertestuali contenuti in tutte le diapositive della presentazione (non nelle diapositive master, layout, note). |
| [getViewProperties()](#getViewProperties--) | Ottiene le proprietà di visualizzazione a livello di presentazione. |
| [getFirstSlideNumber()](#getFirstSlideNumber--) | Rappresenta il numero della prima diapositiva nella presentazione |
| [setFirstSlideNumber(int value)](#setFirstSlideNumber-int-) | Rappresenta il numero della prima diapositiva nella presentazione |
| [getSensitivityLabels()](#getSensitivityLabels--) | Restituisce la collezione di etichette di sensibilità applicate al documento della presentazione. |
| [getSlideById(long id)](#getSlideById-long-) | Restituisce una Slide, MasterSlide o LayoutSlide per Id. |
| [getSourceFormat()](#getSourceFormat--) | Restituisce informazioni sul formato da cui è stata caricata la presentazione. |
| [getMasterTheme()](#getMasterTheme--) | Restituisce il tema master. |
| [save(String fname, int format)](#save-java.lang.String-int-) | Salva tutte le diapositive di una presentazione in un file con il formato specificato. |
| [save(OutputStream stream, int format)](#save-java.io.OutputStream-int-) | Salva tutte le diapositive di una presentazione in uno stream nel formato specificato. |
| [save(String fname, int format, ISaveOptions options)](#save-java.lang.String-int-com.aspose.slides.ISaveOptions-) | Salva tutte le diapositive di una presentazione in un file con il formato specificato e con opzioni aggiuntive. |
| [save(OutputStream stream, int format, ISaveOptions options)](#save-java.io.OutputStream-int-com.aspose.slides.ISaveOptions-) | Salva tutte le diapositive di una presentazione in uno stream nel formato specificato e con opzioni aggiuntive. |
| [save(IXamlOptions options)](#save-com.aspose.slides.IXamlOptions-) | Salva tutte le diapositive di una presentazione in un set di file che rappresentano il markup XAML. |
| [getImages(IRenderingOptions options)](#getImages-com.aspose.slides.IRenderingOptions-) | Restituisce oggetti Image per tutte le diapositive di una presentazione. |
| [getImages(IRenderingOptions options, int[] slides)](#getImages-com.aspose.slides.IRenderingOptions-int---) | Restituisce oggetti Image Thumbnail per le diapositive specificate di una presentazione. |
| [getImages(IRenderingOptions options, float scaleX, float scaleY)](#getImages-com.aspose.slides.IRenderingOptions-float-float-) | Restituisce oggetti Image Thumbnail per tutte le diapositive di una presentazione con scala personalizzata. |
| [getImages(IRenderingOptions options, int[] slides, float scaleX, float scaleY)](#getImages-com.aspose.slides.IRenderingOptions-int---float-float-) | Restituisce oggetti Image Thumbnail per le diapositive specificate di una presentazione con scala personalizzata. |
| [getImages(IRenderingOptions options, Dimension imageSize)](#getImages-com.aspose.slides.IRenderingOptions-java.awt.Dimension-) | Restituisce oggetti Image Thumbnail per tutte le diapositive di una presentazione con dimensioni specificate. |
| [getImages(IRenderingOptions options, int[] slides, Dimension imageSize)](#getImages-com.aspose.slides.IRenderingOptions-int---java.awt.Dimension-) | Restituisce oggetti Image Thumbnail per le diapositive specificate di una presentazione con dimensioni specificate. |
| [save(String fname, int[] slides, int format)](#save-java.lang.String-int---int-) | Salva le diapositive specificate di una presentazione in un file con il formato specificato mantenendo il numero di pagina. |
| [save(String fname, int[] slides, int format, ISaveOptions options)](#save-java.lang.String-int---int-com.aspose.slides.ISaveOptions-) | Salva le diapositive specificate di una presentazione in un file con il formato specificato mantenendo il numero di pagina. |
| [save(OutputStream stream, int[] slides, int format)](#save-java.io.OutputStream-int---int-) | Salva le diapositive specificate di una presentazione in uno stream nel formato specificato mantenendo il numero di pagina. |
| [save(OutputStream stream, int[] slides, int format, ISaveOptions options)](#save-java.io.OutputStream-int---int-com.aspose.slides.ISaveOptions-) | Salva le diapositive specificate di una presentazione in uno stream nel formato specificato mantenendo il numero di pagina. |
| [joinPortionsWithSameFormatting()](#joinPortionsWithSameFormatting--) | Unisce i run con la stessa formattazione in tutti i paragrafi in tutte le forme accettabili in tutte le diapositive. |
| [dispose()](#dispose--) | Rilascia tutte le risorse utilizzate da questo oggetto Presentation. |
| [getPresentation()](#getPresentation--) | Restituisce la presentazione genitore di un testo. |
| [highlightText(String text, Color highlightColor)](#highlightText-java.lang.String-java.awt.Color-) | Evidenzia tutte le occorrenze del testo di esempio con il colore specificato. |
| [highlightText(String text, Color highlightColor, ITextSearchOptions options, IFindResultCallback callback)](#highlightText-java.lang.String-java.awt.Color-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-) | Evidenzia tutte le occorrenze del testo di esempio con il colore specificato. |
| [highlightRegex(Pattern regex, Color highlightColor, IFindResultCallback callback)](#highlightRegex-java.util.regex.Pattern-java.awt.Color-com.aspose.slides.IFindResultCallback-) | Evidenzia tutte le occorrenze dell'espressione regolare con il colore specificato. |
| [replaceText(String oldText, String newText, ITextSearchOptions options, IFindResultCallback callback)](#replaceText-java.lang.String-java.lang.String-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-) | Sostituisce tutte le occorrenze del testo specificato con un altro testo specificato. |
| [replaceRegex(Pattern regex, String newText, IFindResultCallback callback)](#replaceRegex-java.util.regex.Pattern-java.lang.String-com.aspose.slides.IFindResultCallback-) | Sostituisce tutte le corrispondenze dell'espressione regolare con la stringa specificata. |
| [refreshChartsData()](#refreshChartsData--) | Ricarica i dati per tutti i grafici nella presentazione dai loro workbook di origine. |
| [refreshChartsData(boolean skipFailedCharts)](#refreshChartsData-boolean-) | Ricarica i dati per tutti i grafici nella presentazione dai loro workbook di origine. |

### Presentation() {#Presentation--}
```
public Presentation()
```

Questo costruttore crea una nuova presentazione da zero. La presentazione creata ha una diapositiva vuota.

### Presentation(LoadOptions loadOptions) {#Presentation-com.aspose.slides.LoadOptions-}
```
public Presentation(LoadOptions loadOptions)
```

Questo costruttore crea una nuova presentazione da zero. La presentazione creata ha una diapositiva vuota.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| loadOptions | [LoadOptions](../../com.aspose.slides/loadoptions) | Opzioni di caricamento aggiuntive. |

### Presentation(InputStream stream) {#Presentation-java.io.InputStream-}
```
public Presentation(InputStream stream)
```

Questo costruttore è il meccanismo primario per leggere una Presentazione esistente.

--------------------

> ```
> FileInputStream fis = new FileInputStream("demo.pptx");
>  Presentation pres = new Presentation(fis);
>  fis.close();
> ```


**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| stream | java.io.InputStream | Stream di input. |

### Presentation(InputStream stream, LoadOptions loadOptions) {#Presentation-java.io.InputStream-com.aspose.slides.LoadOptions-}
```
public Presentation(InputStream stream, LoadOptions loadOptions)
```

Questo costruttore è il meccanismo primario per leggere una Presentazione esistente.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| stream | java.io.InputStream | Stream di input. |
| loadOptions | [LoadOptions](../../com.aspose.slides/loadoptions) | Opzioni di caricamento aggiuntive. |

### Presentation(String file) {#Presentation-java.lang.String-}
```
public Presentation(String file)
```

Questo costruttore ottiene il percorso del file sorgente da cui vengono letti i contenuti della Presentazione.

--------------------

> ```
> Presentation pres = new Presentation("demo.pptx");
> ```

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| file | java.lang.String | File di input. |

### Presentation(String file, LoadOptions loadOptions) {#Presentation-java.lang.String-com.aspose.slides.LoadOptions-}
```
public Presentation(String file, LoadOptions loadOptions)
```

Questo costruttore ottiene il percorso del file sorgente da cui vengono letti i contenuti della Presentazione.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| file | java.lang.String | File di input. |
| loadOptions | [LoadOptions](../../com.aspose.slides/loadoptions) | Opzioni di caricamento aggiuntive. |

### getCurrentDateTime() {#getCurrentDateTime--}
```
public final Date getCurrentDateTime()
```

Restituisce o imposta data e ora che sostituiranno il contenuto dei campi datetime. L'ora di creazione di questo oggetto Presentation per impostazione predefinita. Lettura/scrittura java.util.Date.

**Restituisce:**
java.util.Date

### setCurrentDateTime(Date value) {#setCurrentDateTime-java.util.Date-}
```
public final void setCurrentDateTime(Date value)
```

Restituisce o imposta data e ora che sostituiranno il contenuto dei campi datetime. L'ora di creazione di questo oggetto Presentation per impostazione predefinita. Lettura/scrittura java.util.Date.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | java.util.Date |  |

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Restituisce l'oggetto Parent_Immediate. Solo lettura IDOMObject.

**Restituisce:**
com.aspose.slides.IDOMObject

### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public final IPresentationHeaderFooterManager getHeaderFooterManager()
```

Restituisce il gestore HeaderFooter attuale. Solo lettura [IPresentationHeaderFooterManager](../../com.aspose.slides/ipresentationheaderfootermanager).

--------------------

> ```
> The following example shows how to set footer visibility inside Slide of PowerPoint Presentation.
>  
>  Presentation pres = new Presentation("presentation.ppt");
>  try
>  {
>      IBaseSlideHeaderFooterManager headerFooterManager = pres.getSlides().get_Item(0).getHeaderFooterManager();
>      if (!headerFooterManager.isFooterVisible()) // La proprietà IsFooterVisible indica che il segnaposto del piè di pagina della diapositiva non è presente.
>      {
>          headerFooterManager.setFooterVisibility(true); // Il metodo SetFooterVisibility rende visibile il segnaposto del piè di pagina della diapositiva.
>      }
>      if (!headerFooterManager.isSlideNumberVisible()) // La proprietà IsSlideNumberVisible indica che il segnaposto del numero di pagina della diapositiva non è presente.
>      {
>          headerFooterManager.setSlideNumberVisibility(true); // Il metodo SetSlideNumberVisibility rende visibile il segnaposto del numero di pagina della diapositiva.
>      }
>      if (!headerFooterManager.isDateTimeVisible()) // La proprietà IsDateTimeVisible indica che il segnaposto della data/ora della diapositiva non è presente.
>      {
>          headerFooterManager.setDateTimeVisibility(true); // Il metodo SetFooterVisibility rende visibile il segnaposto della data/ora della diapositiva.
>      }
>      headerFooterManager.setFooterText("Footer text"); // Il metodo SetFooterText imposta il testo nel segnaposto del piè di pagina della diapositiva.
>      headerFooterManager.setDateTimeText("Date and time text"); // Il metodo SetDateTimeText imposta il testo nel segnaposto della data/ora della diapositiva.
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
>      headerFooterManager.setFooterAndChildFootersVisibility(true); // Il metodo SetFooterAndChildFootersVisibility rende visibili il master slide e tutti i segnaposti del piè di pagina dei figli.
>      headerFooterManager.setSlideNumberAndChildSlideNumbersVisibility(true); // Il metodo SetSlideNumberAndChildSlideNumbersVisibility rende visibili il master slide e tutti i segnaposti dei numeri di pagina dei figli.
>      headerFooterManager.setDateTimeAndChildDateTimesVisibility(true); // Il metodo SetDateTimeAndChildDateTimesVisibility rende visibili il master slide e tutti i segnaposti di data/ora dei figli.
> 
>      headerFooterManager.setFooterAndChildFootersText("Footer text"); // Il metodo SetFooterAndChildFootersText imposta il testo nel master slide e in tutti i segnaposti del piè di pagina dei figli.
>      headerFooterManager.setDateTimeAndChildDateTimesText("Date and time text"); // Il metodo SetDateTimeAndChildDateTimesText imposta il testo nel master slide e in tutti i segnaposti di data/ora dei figli.
>  }
>  finally
>  {
>      if (pres != null) pres.dispose();
>  }
> ```


**Restituisce:**
[IPresentationHeaderFooterManager](../../com.aspose.slides/ipresentationheaderfootermanager)

### getProtectionManager() {#getProtectionManager--}
```
public final IProtectionManager getProtectionManager()
```

Ottiene il gestore delle autorizzazioni per questa presentazione. Solo lettura [IProtectionManager](../../com.aspose.slides/iprotectionmanager).

**Restituisce:**
[IProtectionManager](../../com.aspose.slides/iprotectionmanager)

### getSlides() {#getSlides--}
```
public final ISlideCollection getSlides()
```

Restituisce un elenco di tutte le diapositive definite nella presentazione. Solo lettura [ISlideCollection](../../com.aspose.slides/islidecollection).

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

**Restituisce:**
[ISlideCollection](../../com.aspose.slides/islidecollection)

### getSections() {#getSections--}
```
public final ISectionCollection getSections()
```

Restituisce un elenco di tutte le sezioni diapositive definite nella presentazione. Solo lettura [ISectionCollection](../../com.aspose.slides/isectioncollection).

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
>      // section1 terminerà a newSlide2 e dopo di essa inizierà section2
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


**Restituisce:**
[ISectionCollection](../../com.aspose.slides/isectioncollection)

### getSlideSize() {#getSlideSize--}
```
public final ISlideSize getSlideSize()
```

Restituisce l'oggetto dimensione diapositiva. Solo lettura [ISlideSize](../../com.aspose.slides/islidesize).

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
>  // Istanzia un oggetto Presentation che rappresenta un file di presentazione
>  Presentation presentation = new Presentation("AccessSlides.pptx");
>  try {
>      Presentation auxPresentation = new Presentation();
>      try {
>          ISlide slide = presentation.getSlides().get_Item(0);
>          // Imposta la dimensione della diapositiva delle presentazioni generate a quella della sorgente
>          presentation.getSlideSize().setSize(540, 720, SlideSizeScaleType.EnsureFit); // Il metodo SetSize è usato per impostare la dimensione della diapositiva con contenuto scalato per garantire l'adattamento
>          presentation.getSlideSize().setSize(SlideSizeType.A4Paper, SlideSizeScaleType.Maximize); // Il metodo SetSize è usato per impostare la dimensione della diapositiva massimizzando il contenuto
>          // Salva la presentazione su disco
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
>      pres.getSlideSize().setSize(780, 540, SlideSizeScaleType.DoNotScale); // Dimensione carta A4
>      pres.save("pres-a4-slide-size.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Restituisce:**
[ISlideSize](../../com.aspose.slides/islidesize)

### getNotesSize() {#getNotesSize--}
```
public final INotesSize getNotesSize()
```

Restituisce l'oggetto dimensione diapositiva note. Solo lettura [INotesSize](../../com.aspose.slides/inotessize).

**Restituisce:**
[INotesSize](../../com.aspose.slides/inotessize)

### getLayoutSlides() {#getLayoutSlides--}
```
public final IGlobalLayoutSlideCollection getLayoutSlides()
```

Restituisce un elenco di tutte le diapositive layout definite nella presentazione. Solo lettura [IGlobalLayoutSlideCollection](../../com.aspose.slides/igloballayoutslidecollection).

--------------------

È possibile accedere all'API alternativa per aggiungere/inserire/rimuovere/duplicare diapositive layout tramite la proprietà IMasterSlide.LayoutSlides.

**Restituisce:**
[IGlobalLayoutSlideCollection](../../com.aspose.slides/igloballayoutslidecollection)

### getMasters() {#getMasters--}
```
public final IMasterSlideCollection getMasters()
```

Restituisce un elenco di tutte le diapositive master definite nella presentazione. Solo lettura [IMasterSlideCollection](../../com.aspose.slides/imasterslidecollection).

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

**Restituisce:**
[IMasterSlideCollection](../../com.aspose.slides/imasterslidecollection)

### getMasterNotesSlideManager() {#getMasterNotesSlideManager--}
```
public final IMasterNotesSlideManager getMasterNotesSlideManager()
```

Restituisce il gestore master delle note. Solo lettura [IMasterNotesSlideManager](../../com.aspose.slides/imasternotesslidemanager).

**Restituisce:**
[IMasterNotesSlideManager](../../com.aspose.slides/imasternotesslidemanager)

### getMasterHandoutSlideManager() {#getMasterHandoutSlideManager--}
```
public final IMasterHandoutSlideManager getMasterHandoutSlideManager()
```

Restituisce il gestore master dei dispense. Solo lettura [IMasterHandoutSlideManager](../../com.aspose.slides/imasterhandoutslidemanager).

**Restituisce:**
[IMasterHandoutSlideManager](../../com.aspose.slides/imasterhandoutslidemanager)

### getFontsManager() {#getFontsManager--}
```
public final IFontsManager getFontsManager()
```

Restituisce il gestore dei font. Solo lettura [IFontsManager](../../com.aspose.slides/ifontsmanager).

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

**Restituisce:**
[IFontsManager](../../com.aspose.slides/ifontsmanager)

### getDefaultTextStyle() {#getDefaultTextStyle--}
```
public final ITextStyle getDefaultTextStyle()
```

Restituisce lo stile di testo predefinito per le forme. Solo lettura [ITextStyle](../../com.aspose.slides/itextstyle).

**Restituisce:**
[ITextStyle](../../com.aspose.slides/itextstyle)

### getCommentAuthors() {#getCommentAuthors--}
```
public final ICommentAuthorCollection getCommentAuthors()
```

Restituisce la collezione degli autori dei commenti. Solo lettura [ICommentAuthorCollection](../../com.aspose.slides/icommentauthorcollection).

**Restituisce:**
[ICommentAuthorCollection](../../com.aspose.slides/icommentauthorcollection)

### getDocumentProperties() {#getDocumentProperties--}
```
public final IDocumentProperties getDocumentProperties()
```

Restituisce l'oggetto DocumentProperties che contiene le proprietà del documento standard e personalizzate. Solo lettura [IDocumentProperties](../../com.aspose.slides/idocumentproperties).

**Restituisce:**
[IDocumentProperties](../../com.aspose.slides/idocumentproperties)

### getImages() {#getImages--}
```
public final IImageCollection getImages()
```

Restituisce la collezione di tutte le immagini nella presentazione. Solo lettura [IImageCollection](../../com.aspose.slides/iimagecollection).

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

**Restituisce:**
[IImageCollection](../../com.aspose.slides/iimagecollection)

### getAudios() {#getAudios--}
```
public final IAudioCollection getAudios()
```
Restituisce la collezione di tutti i file audio incorporati nella presentazione. Sola lettura [IAudioCollection](../../com.aspose.slides/iaudiocollection).

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


**Restituisce:**
[IAudioCollection](../../com.aspose.slides/iaudiocollection)
### getVideos() {#getVideos--}
```
public final IVideoCollection getVideos()
```


Restituisce la collezione di tutti i file video incorporati nella presentazione. Sola lettura [IVideoCollection](../../com.aspose.slides/ivideocollection).

--------------------

> ```
> The following examples shows how to create embedded Video Frame in a PowerPoint Presentation.
>  
  
>  // Istanzia la classe Presentation che rappresenta il PPTX
>  Presentation pres = new Presentation();
>  try {
>      // Ottieni la prima diapositiva
>      ISlide sld = pres.getSlides().get_Item(0);
>      // Inserisci il video nella presentazione
>      IVideo vid = pres.getVideos().addVideo(new FileInputStream("Wildlife.mp4"));
>      // Aggiungi Video Frame
>      IVideoFrame vf = sld.getShapes().addVideoFrame(50, 150, 300, 350, vid);
>      // Imposta il video nel Video Frame
>      vf.setEmbeddedVideo(vid);
>      // Imposta modalità di riproduzione e volume del video
>      vf.setPlayMode(VideoPlayModePreset.Auto);
>      vf.setVolume(AudioVolumeMode.Loud);
>      // Scrivi il file PPTX su disco
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
  
>  // Crea una nuova presentazione a cui verrà aggiunto il video
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream fileStream = new FileInputStream("veryLargeVideo.avi");
>      try {
>          // Aggiungiamo il video alla presentazione - scegliamo il comportamento KeepLocked perché noi
>          // non intendiamo accedere al file "veryLargeVideo.avi" file.
>          IVideo video = pres.getVideos().addVideo(fileStream, LoadingStreamBehavior.KeepLocked);
>          pres.getSlides().get_Item(0).getShapes().addVideoFrame(0, 0, 480, 270, video);
>          // Salva la presentazione. Mentre viene generata una presentazione grande, il consumo di memoria
>          // rimane basso per l'intero ciclo di vita dell'oggetto pres
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
>  // Blocca il file sorgente e NON lo carica in memoria
>  loadOptions.getBlobManagementOptions().setPresentationLockingBehavior(PresentationLockingBehavior.KeepLocked);
>  // Crea un'istanza di Presentation, blocca il file "hugePresentationWithAudiosAndVideos.pptx".
>  Presentation pres = new Presentation("Large  Video File Test1.pptx", loadOptions);
>  try {
>      // Salviamo ogni video in un file. Per prevenire un elevato utilizzo di memoria, è necessario un buffer che sarà usato
>      // per trasferire i dati dallo stream video della presentazione a uno stream per un nuovo file video.
>      byte[] buffer = new byte[81024];
>      // Itera attraverso i video
>      for (int index = 0; index < pres.getVideos().size(); index++) {
>          IVideo video = pres.getVideos().get_Item(index);
>          // Apre lo stream video della presentazione. Nota, abbiamo evitato intenzionalmente l'accesso alle proprietà
>          // come video.BinaryData - poiché questa proprietà restituisce un array di byte contenente l'intero video, che poi
>          // causa il caricamento dei byte in memoria. Usiamo video.GetStream, che restituisce uno Stream - e NON
>          //  richiede di caricare l'intero video in memoria.
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
>          // Il consumo di memoria rimarrà basso indipendentemente dalla dimensione del video o della presentazione,
>      }
>      // Se necessario, è possibile applicare gli stessi passaggi ai file audio.
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
>      // aggiungi videoFrame
>      IVideoFrame videoFrame = pres.getSlides().get_Item(0).getShapes().addVideoFrame(10, 10, 427, 240, "https://www.youtube.com/embed/" + videoId);
>      videoFrame.setPlayMode(VideoPlayModePreset.Auto);
> 
>      // carica thumbnail
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
>  // Istanzia un oggetto Presentation che rappresenta un file di presentazione
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


**Restituisce:**
[IVideoCollection](../../com.aspose.slides/ivideocollection)
### getSlideShowSettings() {#getSlideShowSettings--}
```
public final SlideShowSettings getSlideShowSettings()
```


Restituisce le impostazioni dello slide show per la presentazione.

**Restituisce:**
[SlideShowSettings](../../com.aspose.slides/slideshowsettings)
### getDigitalSignatures() {#getDigitalSignatures--}
```
public final IDigitalSignatureCollection getDigitalSignatures()
```


Restituisce la collezione di firme utilizzate per firmare la presentazione. Sola lettura [IDigitalSignatureCollection](../../com.aspose.slides/idigitalsignaturecollection).

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


**Restituisce:**
[IDigitalSignatureCollection](../../com.aspose.slides/idigitalsignaturecollection)
### getCustomData() {#getCustomData--}
```
public final ICustomData getCustomData()
```


Restituisce i dati personalizzati della presentazione. Sola lettura [ICustomData](../../com.aspose.slides/icustomdata).

**Restituisce:**
[ICustomData](../../com.aspose.slides/icustomdata)
### getAllCustomXmlParts() {#getAllCustomXmlParts--}
```
public final ICustomXmlPart[] getAllCustomXmlParts()
```


Restituisce tutte le parti di dati personalizzati nella presentazione. Sola lettura ICustomXmlPart[].

--------------------

> ```
> The following examples show how to clear all custom xml parts from PowerPoint Presentation.
>  
>  Presentation pres = new Presentation("PresentationWithCustomXml.pptx");
>  try {
>      // Itera tutti gli XML personalizzati
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


**Restituisce:**
com.aspose.slides.ICustomXmlPart[]
### getVbaProject() {#getVbaProject--}
```
public final IVbaProject getVbaProject()
```


Ottiene o imposta il progetto VBA con macro della presentazione. Lettura/scrittura [IVbaProject](../../com.aspose.slides/ivbaproject).

**Restituisce:**
[IVbaProject](../../com.aspose.slides/ivbaproject)
### setVbaProject(IVbaProject value) {#setVbaProject-com.aspose.slides.IVbaProject-}
```
public final void setVbaProject(IVbaProject value)
```


Ottiene o imposta il progetto VBA con macro della presentazione. Lettura/scrittura [IVbaProject](../../com.aspose.slides/ivbaproject).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [IVbaProject](../../com.aspose.slides/ivbaproject) |  |
### getHyperlinkQueries() {#getHyperlinkQueries--}
```
public final IHyperlinkQueries getHyperlinkQueries()
```


Fornisce un accesso facile a tutti i collegamenti ipertestuali contenuti in tutte le diapositive della presentazione (non in master, layout, diapositive note). Sola lettura [IHyperlinkQueries](../../com.aspose.slides/ihyperlinkqueries).

**Restituisce:**
[IHyperlinkQueries](../../com.aspose.slides/ihyperlinkqueries)
### getViewProperties() {#getViewProperties--}
```
public final IViewProperties getViewProperties()
```


Ottiene le proprietà di visualizzazione dell'intera presentazione. Sola lettura [IViewProperties](../../com.aspose.slides/iviewproperties).

**Restituisce:**
[IViewProperties](../../com.aspose.slides/iviewproperties)
### getFirstSlideNumber() {#getFirstSlideNumber--}
```
public final int getFirstSlideNumber()
```


Rappresenta il numero della prima diapositiva nella presentazione

**Restituisce:**
int
### setFirstSlideNumber(int value) {#setFirstSlideNumber-int-}
```
public final void setFirstSlideNumber(int value)
```


Rappresenta il numero della prima diapositiva nella presentazione

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | int |  |
### getSensitivityLabels() {#getSensitivityLabels--}
```
public final ISensitivityLabelCollection getSensitivityLabels()
```


Restituisce la collezione di etichette di sensibilità applicate al documento di presentazione. Sola lettura [ISensitivityLabelCollection](../../com.aspose.slides/isensitivitylabelcollection).

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

**Restituisce:**
[ISensitivityLabelCollection](../../com.aspose.slides/isensitivitylabelcollection)
### getSlideById(long id) {#getSlideById-long-}
```
public final IBaseSlide getSlideById(long id)
```


Restituisce una Slide, MasterSlide o LayoutSlide per Id.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| id | long | Id di una diapositiva. |

**Restituisce:**
[IBaseSlide](../../com.aspose.slides/ibaseslide) - IBaseSlide object.
### getSourceFormat() {#getSourceFormat--}
```
public final int getSourceFormat()
```


Restituisce informazioni su da quale formato è stata caricata la presentazione. Sola lettura [SourceFormat](../../com.aspose.slides/sourceformat).

**Restituisce:**
int
### getMasterTheme() {#getMasterTheme--}
```
public final IMasterTheme getMasterTheme()
```


Restituisce il tema master. Sola lettura [IMasterTheme](../../com.aspose.slides/imastertheme).

--------------------

> ```
> The following examples shows how to change a theme effect by altering parts of elements of PowerPoint Presentation.
>  
>  //Istanzia un oggetto Presentation che rappresenta un file di presentazione
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


**Restituisce:**
[IMasterTheme](../../com.aspose.slides/imastertheme)
### save(String fname, int format) {#save-java.lang.String-int-}
```
public final void save(String fname, int format)
```


Salva tutte le diapositive di una presentazione in un file con il formato specificato.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| fname | java.lang.String | Percorso del file creato. |
| format | int | Formato dei dati esportati. |
### save(OutputStream stream, int format) {#save-java.io.OutputStream-int-}
```
public final void save(OutputStream stream, int format)
```


Salva tutte le diapositive di una presentazione in uno stream nel formato specificato.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| stream | java.io.OutputStream | Stream di output. |
| format | int | Formato dei dati esportati. |
### save(String fname, int format, ISaveOptions options) {#save-java.lang.String-int-com.aspose.slides.ISaveOptions-}
```
public final void save(String fname, int format, ISaveOptions options)
```


Salva tutte le diapositive di una presentazione in un file con il formato specificato e con opzioni aggiuntive.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| fname | java.lang.String | Percorso del file creato. |
| format | int | Formato dei dati esportati. |
| options | [ISaveOptions](../../com.aspose.slides/isaveoptions) | Opzioni di formato aggiuntive. |
### save(OutputStream stream, int format, ISaveOptions options) {#save-java.io.OutputStream-int-com.aspose.slides.ISaveOptions-}
```
public final void save(OutputStream stream, int format, ISaveOptions options)
```


Salva tutte le diapositive di una presentazione in uno stream nel formato specificato e con opzioni aggiuntive.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| stream | java.io.OutputStream | Stream di output. |
| format | int | Formato dei dati esportati. |
| options | [ISaveOptions](../../com.aspose.slides/isaveoptions) | Opzioni di formato aggiuntive. |
### save(IXamlOptions options) {#save-com.aspose.slides.IXamlOptions-}
```
public final void save(IXamlOptions options)
```


Salva tutte le diapositive di una presentazione in un insieme di file che rappresentano il markup XAML.

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

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| options | [IXamlOptions](../../com.aspose.slides/ixamloptions) | Le opzioni del formato XAML. |
### getImages(IRenderingOptions options) {#getImages-com.aspose.slides.IRenderingOptions-}
```
public final IImage[] getImages(IRenderingOptions options)
```


Restituisce oggetti Image per tutte le diapositive di una presentazione.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Opzioni Tiff. |

**Restituisce:**
com.aspose.slides.IImage[] - Image objects.
### getImages(IRenderingOptions options, int[] slides) {#getImages-com.aspose.slides.IRenderingOptions-int---}
```
public final IImage[] getImages(IRenderingOptions options, int[] slides)
```


Restituisce oggetti Image miniature per le diapositive specificate di una presentazione.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Opzioni Tiff. |
| slides | int[] | Array con le posizioni delle diapositive, a partire da 1. |

**Restituisce:**
com.aspose.slides.IImage[] - Image objects.
### getImages(IRenderingOptions options, float scaleX, float scaleY) {#getImages-com.aspose.slides.IRenderingOptions-float-float-}
```
public final IImage[] getImages(IRenderingOptions options, float scaleX, float scaleY)
```


Restituisce oggetti Image miniature per tutte le diapositive di una presentazione con scala personalizzata.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Opzioni Tiff. |
| scaleX | float | Il valore con cui ridimensionare questa miniatura nella direzione dell'asse x. |
| scaleY | float | Il valore con cui ridimensionare questa miniatura nella direzione dell'asse y. |

**Restituisce:**
com.aspose.slides.IImage[] - Image objects.
### getImages(IRenderingOptions options, int[] slides, float scaleX, float scaleY) {#getImages-com.aspose.slides.IRenderingOptions-int---float-float-}
```
public final IImage[] getImages(IRenderingOptions options, int[] slides, float scaleX, float scaleY)
```


Restituisce oggetti Image miniature per le diapositive specificate di una presentazione con scala personalizzata.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Opzioni Tiff. |
| slides | int[] | Array con le posizioni delle diapositive, a partire da 1. |
| scaleX | float | Il valore con cui ridimensionare questa miniatura nella direzione dell'asse x. |
| scaleY | float | Il valore con cui ridimensionare questa miniatura nella direzione dell'asse y. |

**Restituisce:**
com.aspose.slides.IImage[] - Image objects.
### getImages(IRenderingOptions options, Dimension imageSize) {#getImages-com.aspose.slides.IRenderingOptions-java.awt.Dimension-}
```
public final IImage[] getImages(IRenderingOptions options, Dimension imageSize)
```


Restituisce oggetti Image miniature per tutte le diapositive di una presentazione con dimensione specificata.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Opzioni Tiff. |
| imageSize | java.awt.Dimension | Dimensione dell'immagine da creare. |

**Restituisce:**
com.aspose.slides.IImage[] - Image objects.
### getImages(IRenderingOptions options, int[] slides, Dimension imageSize) {#getImages-com.aspose.slides.IRenderingOptions-int---java.awt.Dimension-}
```
public final IImage[] getImages(IRenderingOptions options, int[] slides, Dimension imageSize)
```


Restituisce oggetti Image miniature per le diapositive specificate di una presentazione con dimensione specificata.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Opzioni Tiff. |
| slides | int[] | Array con le posizioni delle diapositive, a partire da 1. |
| imageSize | java.awt.Dimension | Dimensione dell'immagine da creare. |

**Restituisce:**
com.aspose.slides.IImage[] - Image objects.
### save(String fname, int[] slides, int format) {#save-java.lang.String-int---int-}
```
public final void save(String fname, int[] slides, int format)
```


Salva le diapositive specificate di una presentazione in un file con il formato specificato mantenendo il numero di pagina.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| fname | java.lang.String | Percorso del file creato. |
| slides | int[] | Array con le posizioni delle diapositive, a partire da 1. |
| format | int | Formato dei dati esportati. |
### save(String fname, int[] slides, int format, ISaveOptions options) {#save-java.lang.String-int---int-com.aspose.slides.ISaveOptions-}
```
public final void save(String fname, int[] slides, int format, ISaveOptions options)
```


Salva le diapositive specificate di una presentazione in un file con il formato specificato mantenendo il numero di pagina.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| fname | java.lang.String | Percorso del file creato. |
| slides | int[] | Array con le posizioni delle diapositive, a partire da 1. |
| format | int | Formato dei dati esportati. |
| options | [ISaveOptions](../../com.aspose.slides/isaveoptions) | Opzioni di formato aggiuntive. |
### save(OutputStream stream, int[] slides, int format) {#save-java.io.OutputStream-int---int-}
```
public final void save(OutputStream stream, int[] slides, int format)
```


Salva le diapositive specificate di una presentazione in uno stream nel formato specificato mantenendo il numero di pagina.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| stream | java.io.OutputStream | Stream di output. |
| slides | int[] | Array con le posizioni delle diapositive, a partire da 1. |
| format | int | Formato dei dati esportati. |
### save(OutputStream stream, int[] slides, int format, ISaveOptions options) {#save-java.io.OutputStream-int---int-com.aspose.slides.ISaveOptions-}
```
public final void save(OutputStream stream, int[] slides, int format, ISaveOptions options)
```


Salva le diapositive specificate di una presentazione in uno stream nel formato specificato mantenendo il numero di pagina.

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

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| stream | java.io.OutputStream | Stream di output. |
| slides | int[] | Array con le posizioni delle diapositive, a partire da 1. |
| format | int | Formato dei dati esportati. |
| options | [ISaveOptions](../../com.aspose.slides/isaveoptions) | Opzioni di formato aggiuntive. |
### joinPortionsWithSameFormatting() {#joinPortionsWithSameFormatting--}
```
public final void joinPortionsWithSameFormatting()
```


Unisce le esecuzioni con la stessa formattazione in tutti i paragrafi in tutte le forme accettabili in tutte le diapositive.
### dispose() {#dispose--}
```
public final void dispose()
```


Rilascia tutte le risorse utilizzate da questo oggetto Presentation.
### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```


Restituisce la presentazione principale di un testo. Sola lettura [IPresentation](../../com.aspose.slides/ipresentation).

**Restituisce:**
[IPresentation](../../com.aspose.slides/ipresentation)
### highlightText(String text, Color highlightColor) {#highlightText-java.lang.String-java.awt.Color-}
```
public final void highlightText(String text, Color highlightColor)
```


Evidenzia tutte le corrispondenze del testo di esempio con il colore specificato.

--------------------

> ```
> The following code sample shows how to highlight text in a PowerPoint presentation.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      // highlighting all separate 'the' occurrences
>      presentation.highlightText("the", Color.MAGENTA);
>      presentation.save("SomePresentation-out2.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| text | java.lang.String | Il testo da evidenziare. |
| highlightColor | java.awt.Color | Il colore per evidenziare il testo. |
### highlightText(String text, Color highlightColor, ITextSearchOptions options, IFindResultCallback callback) {#highlightText-java.lang.String-java.awt.Color-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-}
```
public final void highlightText(String text, Color highlightColor, ITextSearchOptions options, IFindResultCallback callback)
```


Evidenzia tutte le corrispondenze del testo di esempio con il colore specificato.

--------------------

> ```
> The following code sample shows how to highlight text in a PowerPoint presentation.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      TextSearchOptions textSearchOptions = new TextSearchOptions();
>      textSearchOptions.setWholeWordsOnly(true);
>      // evidenzia tutte le occorrenze separate di 'the'
>      presentation.highlightText("the", Color.MAGENTA, textSearchOptions, null);
>      presentation.save("SomePresentation-out2.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| text | java.lang.String | Il testo da evidenziare. |
| highlightColor | java.awt.Color | Il colore per evidenziare il testo. |
| options | [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions) | Opzioni di ricerca del testo [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions). |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | L'oggetto callback per ricevere i risultati della ricerca [IFindResultCallback](../../com.aspose.slides/ifindresultcallback). |
### highlightRegex(Pattern regex, Color highlightColor, IFindResultCallback callback) {#highlightRegex-java.util.regex.Pattern-java.awt.Color-com.aspose.slides.IFindResultCallback-}
```
public final void highlightRegex(Pattern regex, Color highlightColor, IFindResultCallback callback)
```


Evidenzia tutte le corrispondenze dell'espressione regolare con il colore specificato.

--------------------

> ```
> The following code sample shows how to highlight text in a PowerPoint Presentation using a regular expression.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      Pattern regex = Pattern.compile("\\b[^\\s]{10,}\\b");
>      // evidenzia tutte le parole di 10 o più caratteri
>      presentation.highlightRegex(regex, Color.BLUE, null);
>      presentation.save("SomePresentation-out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Parametri:**
| regex | java.util.regex.Pattern | L'espressione regolare java.util.regex.Pattern per ottenere le stringhe da evidenziare. |
| highlightColor | java.awt.Color | Il colore per evidenziare il testo. |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | L'oggetto callback per ricevere i risultati della ricerca [IFindResultCallback](../../com.aspose.slides/ifindresultcallback). |

### replaceText(String oldText, String newText, ITextSearchOptions options, IFindResultCallback callback) {#replaceText-java.lang.String-java.lang.String-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-}
```
public final void replaceText(String oldText, String newText, ITextSearchOptions options, IFindResultCallback callback)
```

Sostituisce tutte le occorrenze del testo specificato con un altro testo specificato.

--------------------

> ```
> The following sample code shows how to replace one specified string with another specified string.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx")
>  try {
>      TextSearchOptions textSearchOptions = new TextSearchOptions();
>      textSearchOptions.setWholeWordsOnly(true);
>      // Sostituisci tutte le occorrenze separate di 'the' con '***'
>      presentation.replaceText("the", "***", textSearchOptions, null);
>      presentation.save("SomePresentation-out2.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| oldText | java.lang.String | La stringa da sostituire. |
| newText | java.lang.String | La stringa con cui sostituire tutte le occorrenze di oldText. |
| options | [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions) | Opzioni di ricerca del testo [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions). |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | L'oggetto callback per ricevere i risultati della ricerca [IFindResultCallback](../../com.aspose.slides/ifindresultcallback). |

### replaceRegex(Pattern regex, String newText, IFindResultCallback callback) {#replaceRegex-java.util.regex.Pattern-java.lang.String-com.aspose.slides.IFindResultCallback-}
```
public final void replaceRegex(Pattern regex, String newText, IFindResultCallback callback)
```

Sostituisce tutte le corrispondenze dell'espressione regolare con la stringa specificata.

--------------------

> ```
> The following code sample shows how to replace text using regular expression with the specified string.
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      Pattern regex = Pattern.compile("\\b[^\\s]{10,}\\b");
>      // Sostituisci tutte le parole di 10 o più caratteri con '***'
>      presentation.replaceRegex(regex, "***", null);
>      presentation.save("SomePresentation-out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| regex | java.util.regex.Pattern | L'espressione regolare java.util.regex.Pattern per ottenere le stringhe da sostituire. |
| newText | java.lang.String | La stringa con cui sostituire tutte le occorrenze delle stringhe da sostituire. |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | L'oggetto callback per ricevere i risultati della ricerca [IFindResultCallback](../../com.aspose.slides/ifindresultcallback). |

### refreshChartsData() {#refreshChartsData--}
```
public final void refreshChartsData()
```

Ricarica i dati per tutti i grafici nella presentazione dai rispettivi workbook di origine.

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

Ricarica i dati per tutti i grafici nella presentazione dai rispettivi workbook di origine.

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


**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| skipFailedCharts | boolean | Determina se il processo di aggiornamento continua nel caso un grafico non venga aggiornato. Se true, i grafici che generano un'eccezione vengono ignorati; altrimenti l'eccezione viene propagata. |