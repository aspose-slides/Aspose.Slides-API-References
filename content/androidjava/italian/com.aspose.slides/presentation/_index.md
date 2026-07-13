---
title: Presentation
second_title: Riferimento API Java di Aspose.Slides per Android
description: Rappresenta una presentazione Microsoft PowerPoint.
type: docs
url: /it/com.aspose.slides/presentation/
---
**Eredità:**
java.lang.Object

**Tutte le interfacce implementate:**
[com.aspose.slides.IPresentation](../../com.aspose.slides/ipresentation), com.aspose.slides.IDOMObject
```
public final class Presentation implements IPresentation, IDOMObject
```

Rappresenta una presentazione Microsoft PowerPoint.

--------------------

> ```
> The following example shows how to create PowerPoint Presentation.
>   
>  // Istanzia un oggetto Presentation che rappresenta un file di presentazione
>  Presentation pres = new Presentation();
>  try {
>      // Ottieni la prima diapositiva
>      ISlide slide = pres.getSlides().get_Item(0);
>      // Aggiungi un'autoshape di tipo linea
>      slide.getShapes().addAutoShape(ShapeType.Line, 50, 150, 300, 0);
>      // Salva il file della presentazione.
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
>      // Salva il file della presentazione.
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
| [Presentation(InputStream stream)](#Presentation-java.io.InputStream-) | Questo costruttore è il meccanismo principale per leggere una presentazione esistente. |
| [Presentation(InputStream stream, LoadOptions loadOptions)](#Presentation-java.io.InputStream-com.aspose.slides.LoadOptions-) | Questo costruttore è il meccanismo principale per leggere una presentazione esistente. |
| [Presentation(String file)](#Presentation-java.lang.String-) | Questo costruttore ottiene un percorso di file sorgente da cui vengono letti i contenuti della presentazione. |
| [Presentation(String file, LoadOptions loadOptions)](#Presentation-java.lang.String-com.aspose.slides.LoadOptions-) | Questo costruttore ottiene un percorso di file sorgente da cui vengono letti i contenuti della presentazione. |

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getCurrentDateTime()](#getCurrentDateTime--) | Restituisce o imposta data e ora che sostituiranno il contenuto dei campi datetime. |
| [setCurrentDateTime(Date value)](#setCurrentDateTime-java.util.Date-) | Restituisce o imposta data e ora che sostituiranno il contenuto dei campi datetime. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | Restituisce l’attuale gestore HeaderFooter. |
| [getProtectionManager()](#getProtectionManager--) | Ottiene il gestore delle autorizzazioni per questa presentazione. |
| [getSlides()](#getSlides--) | Restituisce un elenco di tutte le diapositive definite nella presentazione. |
| [getSections()](#getSections--) | Restituisce un elenco di tutte le sezioni di diapositive definite nella presentazione. |
| [getSlideSize()](#getSlideSize--) | Restituisce l’oggetto dimensione diapositiva. |
| [getNotesSize()](#getNotesSize--) | Restituisce l’oggetto dimensione note diapositiva. |
| [getLayoutSlides()](#getLayoutSlides--) | Restituisce un elenco di tutte le diapositive layout definite nella presentazione. |
| [getMasters()](#getMasters--) | Restituisce un elenco di tutte le diapositive master definite nella presentazione. |
| [getMasterNotesSlideManager()](#getMasterNotesSlideManager--) | Restituisce il gestore master delle note. |
| [getMasterHandoutSlideManager()](#getMasterHandoutSlideManager--) | Restituisce il gestore master dei fogli illustrativi. |
| [getFontsManager()](#getFontsManager--) | Restituisce il gestore dei caratteri. |
| [getDefaultTextStyle()](#getDefaultTextStyle--) | Restituisce lo stile di testo predefinito per le forme. |
| [getCommentAuthors()](#getCommentAuthors--) | Restituisce la collezione degli autori dei commenti. |
| [getDocumentProperties()](#getDocumentProperties--) | Restituisce l’oggetto DocumentProperties che contiene le proprietà standard e personalizzate del documento. |
| [getImages()](#getImages--) | Restituisce la collezione di tutte le immagini nella presentazione. |
| [getAudios()](#getAudios--) | Restituisce la collezione di tutti i file audio incorporati nella presentazione. |
| [getVideos()](#getVideos--) | Restituisce la collezione di tutti i file video incorporati nella presentazione. |
| [getSlideShowSettings()](#getSlideShowSettings--) | Restituisce le impostazioni dello slideshow per la presentazione. |
| [getDigitalSignatures()](#getDigitalSignatures--) | Restituisce la collezione delle firme usate per firmare la presentazione. |
| [getCustomData()](#getCustomData--) | Restituisce i dati personalizzati della presentazione. |
| [getAllCustomXmlParts()](#getAllCustomXmlParts--) | Restituisce tutte le parti di dati personalizzati nella presentazione. |
| [getVbaProject()](#getVbaProject--) | Ottiene o imposta il progetto VBA con le macro della presentazione. |
| [setVbaProject(IVbaProject value)](#setVbaProject-com.aspose.slides.IVbaProject-) | Ottiene o imposta il progetto VBA con le macro della presentazione. |
| [getHyperlinkQueries()](#getHyperlinkQueries--) | Fornisce un facile accesso a tutti i collegamenti ipertestuali contenuti in tutte le diapositive della presentazione (non in master, layout, note). |
| [getViewProperties()](#getViewProperties--) | Ottiene le proprietà di visualizzazione a livello di presentazione. |
| [getFirstSlideNumber()](#getFirstSlideNumber--) | Rappresenta il numero della prima diapositiva nella presentazione |
| [setFirstSlideNumber(int value)](#setFirstSlideNumber-int-) | Rappresenta il numero della prima diapositiva nella presentazione |
| [getSensitivityLabels()](#getSensitivityLabels--) | Restituisce la collezione di etichette di sensibilità applicate al documento della presentazione. |
| [getSlideById(long id)](#getSlideById-long-) | Restituisce una Slide, MasterSlide o LayoutSlide per Id. |
| [getSourceFormat()](#getSourceFormat--) | Restituisce informazioni sul formato da cui è stata caricata la presentazione. |
| [getMasterTheme()](#getMasterTheme--) | Restituisce il tema master. |
| [save(String fname, int format)](#save-java.lang.String-int-) | Salva tutte le diapositive di una presentazione in un file con il formato specificato. |
| [save(OutputStream stream, int format)](#save-java.io.OutputStream-int-) | Salva tutte le diapositive di una presentazione in un flusso nel formato specificato. |
| [save(String fname, int format, ISaveOptions options)](#save-java.lang.String-int-com.aspose.slides.ISaveOptions-) | Salva tutte le diapositive di una presentazione in un file con il formato specificato e con opzioni aggiuntive. |
| [save(OutputStream stream, int format, ISaveOptions options)](#save-java.io.OutputStream-int-com.aspose.slides.ISaveOptions-) | Salva tutte le diapositive di una presentazione in un flusso nel formato specificato e con opzioni aggiuntive. |
| [save(IXamlOptions options)](#save-com.aspose.slides.IXamlOptions-) | Salva tutte le diapositive di una presentazione in un insieme di file che rappresentano markup XAML. |
| [getImages(IRenderingOptions options)](#getImages-com.aspose.slides.IRenderingOptions-) | Restituisce oggetti Image per tutte le diapositive di una presentazione. |
| [getImages(IRenderingOptions options, int[] slides)](#getImages-com.aspose.slides.IRenderingOptions-int---) | Restituisce oggetti Image Thumbnail per le diapositive specificate di una presentazione. |
| [getImages(IRenderingOptions options, float scaleX, float scaleY)](#getImages-com.aspose.slides.IRenderingOptions-float-float-) | Restituisce oggetti Image Thumbnail per tutte le diapositive di una presentazione con scaling personalizzato. |
| [getImages(IRenderingOptions options, int[] slides, float scaleX, float scaleY)](#getImages-com.aspose.slides.IRenderingOptions-int---float-float-) | Restituisce oggetti Image Thumbnail per le diapositive specificate di una presentazione con scaling personalizzato. |
| [getImages(IRenderingOptions options, Size imageSize)](#getImages-com.aspose.slides.IRenderingOptions-com.aspose.slides.android.Size-) | Restituisce oggetti Image Thumbnail per tutte le diapositive di una presentazione con dimensione specificata. |
| [getImages(IRenderingOptions options, int[] slides, Size imageSize)](#getImages-com.aspose.slides.IRenderingOptions-int---com.aspose.slides.android.Size-) | Restituisce oggetti Image Thumbnail per le diapositive specificate di una presentazione con dimensione specificata. |
| [save(String fname, int[] slides, int format)](#save-java.lang.String-int---int-) | Salva le diapositive specificate di una presentazione in un file con il formato specificato mantenendo il numero di pagina. |
| [save(String fname, int[] slides, int format, ISaveOptions options)](#save-java.lang.String-int---int-com.aspose.slides.ISSaveOptions-) | Salva le diapositive specificate di una presentazione in un file con il formato specificato mantenendo il numero di pagina. |
| [save(OutputStream stream, int[] slides, int format)](#save-java.io.OutputStream-int---int-) | Salva le diapositive specificate di una presentazione in un flusso nel formato specificato mantenendo il numero di pagina. |
| [save(OutputStream stream, int[] slides, int format, ISaveOptions options)](#save-java.io.OutputStream-int---int-com.aspose.slides.ISSaveOptions-) | Salva le diapositive specificate di una presentazione in un flusso nel formato specificato mantenendo il numero di pagina. |
| [joinPortionsWithSameFormatting()](#joinPortionsWithSameFormatting--) | Unisce i run con la stessa formattazione in tutti i paragrafi di tutte le forme accettabili in tutte le diapositive. |
| [dispose()](#dispose--) | Rilascia tutte le risorse usate da questo oggetto Presentation. |
| [getPresentation()](#getPresentation--) | Restituisce la presentazione padre di un testo. |
| [highlightText(String text, Integer highlightColor)](#highlightText-java.lang.String-java.lang.Integer-) | Evidenzia tutte le occorrenze del testo di esempio con il colore specificato. |
| [highlightText(String text, Integer highlightColor, ITextSearchOptions options, IFindResultCallback callback)](#highlightText-java.lang.String-java.lang.Integer-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-) | Evidenzia tutte le occorrenze del testo di esempio con il colore specificato. |
| [highlightRegex(Pattern regex, Integer highlightColor, IFindResultCallback callback)](#highlightRegex-java.util.regex.Pattern-java.lang.Integer-com.aspose.slides.IFindResultCallback-) | Evidenzia tutte le occorrenze dell’espressione regolare con il colore specificato. |
| [replaceText(String oldText, String newText, ITextSearchOptions options, IFindResultCallback callback)](#replaceText-java.lang.String-java.lang.String-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-) | Sostituisce tutte le occorrenze del testo specificato con un altro testo specificato. |
| [replaceRegex(Pattern regex, String newText, IFindResultCallback callback)](#replaceRegex-java.util.regex.Pattern-java.lang.String-com.aspose.slides.IFindResultCallback-) | Sostituisce tutte le occorrenze dell’espressione regolare con la stringa specificata. |

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

Questo costruttore è il meccanismo principale per leggere una presentazione esistente.

--------------------

> ```
> FileInputStream fis = new FileInputStream("demo.pptx");
>  Presentation pres = new Presentation(fis);
>  fis.close();
> ```


**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| stream | java.io.InputStream | Flusso di input. |

### Presentation(InputStream stream, LoadOptions loadOptions) {#Presentation-java.io.InputStream-com.aspose.slides.LoadOptions-}
```
public Presentation(InputStream stream, LoadOptions loadOptions)
```

Questo costruttore è il meccanismo principale per leggere una presentazione esistente.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| stream | java.io.InputStream | Flusso di input. |
| loadOptions | [LoadOptions](../../com.aspose.slides/loadoptions) | Opzioni di caricamento aggiuntive. |

### Presentation(String file) {#Presentation-java.lang.String-}
```
public Presentation(String file)
```

Questo costruttore ottiene un percorso di file sorgente da cui vengono letti i contenuti della presentazione.

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

Questo costruttore ottiene un percorso di file sorgente da cui vengono letti i contenuti della presentazione.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| file | java.lang.String | File di input. |
| loadOptions | [LoadOptions](../../com.aspose.slides/loadoptions) | Opzioni di caricamento aggiuntive. |

### getCurrentDateTime() {#getCurrentDateTime--}
```
public final Date getCurrentDateTime()
```

Restituisce o imposta data e ora che sostituiranno il contenuto dei campi datetime. È l’ora di creazione di questo oggetto Presentation per impostazione predefinita. Lettura/Scrittura java.util.Date.

**Restituisce:**
java.util.Date

### setCurrentDateTime(Date value) {#setCurrentDateTime-java.util.Date-}
```
public final void setCurrentDateTime(Date value)
```

Restituisce o imposta data e ora che sostituiranno il contenuto dei campi datetime. È l’ora di creazione di questo oggetto Presentation per impostazione predefinita. Lettura/Scrittura java.util.Date.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | java.util.Date |  |

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Restituisce l’oggetto Parent_Immediate. Sola lettura IDOMObject.

**Restituisce:**
com.aspose.slides.IDOMObject

### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public final IPresentationHeaderFooterManager getHeaderFooterManager()
```

Restituisce l’attuale gestore HeaderFooter. Sola lettura [IPresentationHeaderFooterManager](../../com.aspose.slides/ipresentationheaderfootermanager).

--------------------

> ```
> The following example shows how to set footer visibility inside Slide of PowerPoint Presentation.
>  
>  Presentation pres = new Presentation("presentation.ppt");
>  try
>  {
>      IBaseSlideHeaderFooterManager headerFooterManager = pres.getSlides().get_Item(0).getHeaderFooterManager();
>      if (!headerFooterManager.isFooterVisible()) // La proprietà IsFooterVisible viene usata per indicare che un segnaposto di piè di diapositiva non è presente.
>      {
>          headerFooterManager.setFooterVisibility(true); // Il metodo SetFooterVisibility viene usato per rendere visibile un segnaposto di piè di diapositiva.
>      }
>      if (!headerFooterManager.isSlideNumberVisible()) // La proprietà IsSlideNumberVisible viene usata per indicare che un segnaposto di numero di diapositiva non è presente.
>      {
>          headerFooterManager.setSlideNumberVisibility(true); // Il metodo SetSlideNumberVisibility viene usato per rendere visibile un segnaposto di numero di diapositiva.
>      }
>      if (!headerFooterManager.isDateTimeVisible()) // La proprietà IsDateTimeVisible viene usata per indicare che un segnaposto di data e ora della diapositiva non è presente.
>      {
>          headerFooterManager.setDateTimeVisibility(true); // Il metodo SetFooterVisibility viene usato per rendere visibile un segnaposto di data e ora della diapositiva.
>      }
>      headerFooterManager.setFooterText("Footer text"); // Il metodo SetFooterText viene usato per impostare il testo del segnaposto di piè di diapositiva.
>      headerFooterManager.setDateTimeText("Date and time text"); // Il metodo SetDateTimeText viene usato per impostare il testo del segnaposto di data e ora della diapositiva.
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
>      headerFooterManager.setFooterAndChildFootersVisibility(true); // Il metodo SetFooterAndChildFootersVisibility viene usato per rendere visibili la diapositiva master e tutti i segnaposti di piè dei figli.
>      headerFooterManager.setSlideNumberAndChildSlideNumbersVisibility(true); // Il metodo SetSlideNumberAndChildSlideNumbersVisibility viene usato per rendere visibili la diapositiva master e tutti i segnaposti di numero di pagina dei figli.
>      headerFooterManager.setDateTimeAndChildDateTimesVisibility(true); // Il metodo SetDateTimeAndChildDateTimesVisibility viene usato per rendere visibili la diapositiva master e tutti i segnaposti di data e ora dei figli.
> 
>      headerFooterManager.setFooterAndChildFootersText("Footer text"); // Il metodo SetFooterAndChildFootersText viene usato per impostare il testo del segnaposto di piè della diapositiva master e di tutti i figli.
>      headerFooterManager.setDateTimeAndChildDateTimesText("Date and time text"); // Il metodo SetDateTimeAndChildDateTimesText viene usato per impostare il testo del segnaposto di data e ora della diapositiva master e di tutti i figli.
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

Ottiene il gestore delle autorizzazioni per questa presentazione. Sola lettura [IProtectionManager](../../com.aspose.slides/iprotectionmanager).

**Restituisce:**
[IProtectionManager](../../com.aspose.slides/iprotectionmanager)

### getSlides() {#getSlides--}
```
public final ISlideCollection getSlides()
```

Restituisce un elenco di tutte le diapositive definite nella presentazione. Sola lettura [ISlideCollection](../../com.aspose.slides/islidecollection).

--------------------

> ```
> The following example shows how to set slides' background color of PowerPoint Presentation.
>  
>  // Istanzia la classe Presentation che rappresenta il file di presentazione
>  Presentation pres = new Presentation();
>  try
>  {
>      // Imposta il colore di sfondo della prima ISlide a Blu
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
>  // Istanzia la classe Presentation che rappresenta il file di presentazione
>  Presentation pres = new Presentation("SetImageAsBackground.pptx");
>  try {
>      // Imposta lo sfondo con immagine
>      pres.getSlides().get_Item(0).getBackground().setType(BackgroundType.OwnBackground);
>      pres.getSlides().get_Item(0).getBackground().getFillFormat().setFillType(FillType.Picture);
>      pres.getSlides().get_Item(0).getBackground().getFillFormat().getPictureFillFormat().setPictureFillMode(PictureFillMode.Stretch);
>      // Imposta l'immagine
>      FileInputStream fos = null;
>      try {
>          fos = new FileInputStream("Tulips.jpg");
>          // Aggiungi l'immagine alla collezione di immagini della presentazione
>          IPPImage imgx = pres.getImages().addImage(fos);
>          pres.getSlides().get_Item(0).getBackground().getFillFormat().getPictureFillFormat().getPicture().setImage(imgx);
>      } finally {
>          if (fos != null) fos.close();
>      }
>      // Scrivi la presentazione su disco
>      pres.save("ContentBG_Img_out.pptx", SaveFormat.Pptx);
>  } catch (IOException e) { }
>  finally
>  {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to add slide transition Presentation.
>  
>  // Istanzia la classe Presentation per caricare il file di presentazione sorgente
>  Presentation pres = new Presentation("AccessSlides.pptx");
>  try
>  {
>      // Applica la transizione tipo cerchio alla diapositiva 1
>      pres.getSlides().get_Item(0).getSlideShowTransition().setType(TransitionType.Circle);
>      // Applica la transizione tipo pettine alla diapositiva 2
>      pres.getSlides().get_Item(1).getSlideShowTransition().setType(TransitionType.Comb);
>      // Scrivi la presentazione su disco
>      pres.save("SampleTransition_out.pptx", SaveFormat.Pptx);
>  }
>  finally
>  {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to add advanced slide Transition.
>  
>  // Istanzia la classe Presentation che rappresenta un file di presentazione
>  Presentation pres = new Presentation("BetterSlideTransitions.pptx");
>  try
>  {
>      // Applica la transizione tipo cerchio alla diapositiva 1
>      pres.getSlides().get_Item(0).getSlideShowTransition().setType(TransitionType.Circle);
>      // Imposta la durata della transizione a 3 secondi
>      pres.getSlides().get_Item(0).getSlideShowTransition().setAdvanceOnClick(true);
>      pres.getSlides().get_Item(0).getSlideShowTransition().setAdvanceAfterTime(3000);
>      // Applica la transizione tipo pettine alla diapositiva 2
>      pres.getSlides().get_Item(1).getSlideShowTransition().setType(TransitionType.Comb);
>      // Imposta la durata della transizione a 5 secondi
>      pres.getSlides().get_Item(1).getSlideShowTransition().setAdvanceOnClick(true);
>      pres.getSlides().get_Item(1).getSlideShowTransition().setAdvanceAfterTime(5000);
>      // Applica la transizione tipo zoom alla diapositiva 3
>      pres.getSlides().get_Item(2).getSlideShowTransition().setType(TransitionType.Zoom);
>      // Imposta la durata della transizione a 7 secondi
>      pres.getSlides().get_Item(2).getSlideShowTransition().setAdvanceOnClick(true);
>      pres.getSlides().get_Item(2).getSlideShowTransition().setAdvanceAfterTime(7000);
>      // Scrivi la presentazione su disco
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

Restituisce un elenco di tutte le sezioni di diapositive definite nella presentazione. Sola lettura [ISectionCollection](../../com.aspose.slides/isectioncollection).

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
>      // section1 terminerà in newSlide2 e dopo di essa inizierà section2
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

Restituisce l’oggetto dimensione diapositiva. Sola lettura [ISlideSize](../../com.aspose.slides/islidesize).

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
>          presentation.getSlideSize().setSize(540, 720, SlideSizeScaleType.EnsureFit); // Il metodo SetSize è usato per impostare la dimensione della diapositiva con il contenuto scalato per garantire l'adattamento
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

Restituisce l’oggetto dimensione note diapositiva. Sola lettura [INotesSize](../../com.aspose.slides/inotessize).

**Restituisce:**
[INotesSize](../../com.aspose.slides/inotessize)

### getLayoutSlides() {#getLayoutSlides--}
```
public final IGlobalLayoutSlideCollection getLayoutSlides()
```

Restituisce un elenco di tutte le diapositive layout definite nella presentazione. Sola lettura [IGlobalLayoutSlideCollection](../../com.aspose.slides/igloballayoutslidecollection).

--------------------

È possibile accedere all’API alternativa per aggiungere/inserire/rimuovere/clonare diapositive layout usando la proprietà IMasterSlide.LayoutSlides.

**Restituisce:**
[IGlobalLayoutSlideCollection](../../com.aspose.slides/igloballayoutslidecollection)

### getMasters() {#getMasters--}
```
public final IMasterSlideCollection getMasters()
```

Restituisce un elenco di tutte le diapositive master definite nella presentazione. Sola lettura [IMasterSlideCollection](../../com.aspose.slides/imasterslidecollection).

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
>  // Istanzia la classe Presentation che rappresenta il file di presentazione
>  Presentation pres = new Presentation();
>  try
>  {
>      // Imposta il colore di sfondo della Master ISlide a Verde foresta
>      pres.getMasters().get_Item(0).getBackground().setType(BackgroundType.OwnBackground);
>      pres.getMasters().get_Item(0).getBackground().getFillFormat().setFillType(FillType.Solid);
>      pres.getMasters().get_Item(0).getBackground().getFillFormat().getSolidFillColor().setColor(Color.GREEN);
>      // Scrivi la presentazione su disco
>      pres.save("SetSlideBackgroundMaster_out.pptx", SaveFormat.Pptx);
>  }
>  finally
>  {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following examples shows how to add slide layout to PowerPoint Presentation.
>  
>  // Istanzia la classe Presentation che rappresenta il file di presentazione
>  Presentation presentation = new Presentation("AccessSlides.pptx");
>  try
>  {
>      // Prova a cercare per tipo di diapositiva layout
>      IMasterLayoutSlideCollection layoutSlides = presentation.getMasters().get_Item(0).getLayoutSlides();
>      ILayoutSlide layoutSlide = null;
>      if (layoutSlides.getByType(SlideLayoutType.TitleAndObject) != null)
>          layoutSlide = layoutSlides.getByType(SlideLayoutType.TitleAndObject);
>      else
>          layoutSlide = layoutSlides.getByType(SlideLayoutType.Title);
> 
>      if (layoutSlide == null)
>      {
>          // La situazione in cui una presentazione non contiene alcuni tipi di layout.
>          // Il file di presentazione contiene solo layout di tipo Blank e Custom.
>          // Ma le diapositive layout con tipi Custom hanno nomi diversi,
>          // come "Title", "Title and Content", ecc. Ed è possibile utilizzare questi
>          // nomi per la selezione della diapositiva layout.
>          // È anche possibile usare l'insieme dei tipi di forma segnaposto. Per esempio,
>          // La diapositiva Title dovrebbe avere solo il tipo di segnaposto Title, ecc.
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
>      // Aggiunta di una diapositiva vuota con il layout slide aggiunto
>      presentation.getSlides().insertEmptySlide(0, layoutSlide);
>      // Salva la presentazione
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

Restituisce il gestore master delle note. Sola lettura [IMasterNotesSlideManager](../../com.aspose.slides/imasternotesslidemanager).

**Restituisce:**
[IMasterNotesSlideManager](../../com.aspose.slides/imasternotesslidemanager)

### getMasterHandoutSlideManager() {#getMasterHandoutSlideManager--}
```
public final IMasterHandoutSlideManager getMasterHandoutSlideManager()
```

Restituisce il gestore master dei fogli illustrativi. Sola lettura [IMasterHandoutSlideManager](../../com.aspose.slides/imasterhandoutslidemanager).

**Restituisce:**
[IMasterHandoutSlideManager](../../com.aspose.slides/imasterhandoutslidemanager)

### getFontsManager() {#getFontsManager--}
```
public final IFontsManager getFontsManager()
```

Restituisce il gestore dei caratteri. Sola lettura [IFontsManager](../../com.aspose.slides/ifontsmanager).

--------------------

> ```
> The following example shows how to add embedded fonts to PowerPoint Presentation.
>  
>  // Carica presentazione
>  Presentation pres = new Presentation("Fonts.pptx");
>  try {
>      // Carica il font sorgente da sostituire
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
>      // Salva la presentazione
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

Restituisce lo stile di testo predefinito per le forme. Sola lettura [ITextStyle](../../com.aspose.slides/itextstyle).

**Restituisce:**
[ITextStyle](../../com.aspose.slides/itextstyle)

### getCommentAuthors() {#getCommentAuthors--}
```
public final ICommentAuthorCollection getCommentAuthors()
```

Restituisce la collezione degli autori dei commenti. Sola lettura [ICommentAuthorCollection](../../com.aspose.slides/icommentauthorcollection).

**Restituisce:**
[ICommentAuthorCollection](../../com.aspose.slides/icommentauthorcollection)

### getDocumentProperties() {#getDocumentProperties--}
```
public final IDocumentProperties getDocumentProperties()
```

Restituisce l’oggetto DocumentProperties che contiene le proprietà standard e personalizzate del documento. Sola lettura [IDocumentProperties](../../com.aspose.slides/idocumentproperties).

**Restituisce:**
[IDocumentProperties](../../com.aspose.slides/idocumentproperties)

### getImages() {#getImages--}
```
public final IImageCollection getImages()
```

Restituisce la collezione di tutte le immagini nella presentazione. Sola lettura [IImageCollection](../../com.aspose.slides/iimagecollection).

--------------------

> ```
> The following examples shows how to add image as BLOB in PowerPoint Presentation.
>  
>  // crea una nuova presentazione a cui verrà aggiunta l'immagine.
>  Presentation pres = new Presentation();
>  try
>  {
>      // supponiamo di avere il file immagine grande che vogliamo includere nella presentazione
>      FileInputStream fip = new FileInputStream("large_image.jpg");
>      try
>      {
>          // Aggiungiamo l'immagine alla presentazione - scegliamo il comportamento KeepLocked perché noi
>          // NON intendiamo accedere al file "largeImage.png" file.
>          IPPImage img = pres.getImages().addImage(fip, LoadingStreamBehavior.KeepLocked);
>          pres.getSlides().get_Item(0).getShapes().addPictureFrame(ShapeType.Rectangle, 0, 0, 300, 200, img);
>          // Salva la presentazione. Mentre una presentazione grande viene esportata, il consumo di memoria
>          // rimane basso per tutto il ciclo di vita dell'oggetto pres
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
>          // Aggiunge l'immagine alla presentazione
>          IPPImage image = pres.getImages().addImage(fos);
>          // Crea un frame immagine sulla diapositiva 1 basato sull'immagine aggiunta in precedenza
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

**Restituisce:**
[IVideoCollection](../../com.aspose.slides/ivideocollection)

### getSlideShowSettings() {#getSlideShowSettings--}
```
public final SlideShowSettings getSlideShowSettings()
```

Restituisce le impostazioni dello slideshow per la presentazione.

**Restituisce:**
[SlideShowSettings](../../com.aspose.slides/slideshowsettings)

### getDigitalSignatures() {#getDigitalSignatures--}
```
public final IDigitalSignatureCollection getDigitalSignatures()
```

Restituisce la collezione di firme usate per firmare la presentazione. Sola lettura [IDigitalSignatureCollection](../../com.aspose.slides/idigitalsignaturecollection).

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
>      // Itera tutti i componenti XML personalizzati
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

Ottiene o imposta il progetto VBA con le macro della presentazione. Lettura/Scrittura [IVbaProject](../../com.aspose.slides/ivbaproject).

**Restituisce:**
[IVbaProject](../../com.aspose.slides/ivbaproject)

### setVbaProject(IVbaProject value) {#setVbaProject-com.aspose.slides.IVbaProject-}
```
public final void setVbaProject(IVbaProject value)
```

Ottiene o imposta il progetto VBA con le macro della presentazione. Lettura/Scrittura [IVbaProject](../../com.aspose.slides/ivbaproject).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [IVbaProject](../../com.aspose.slides/ivbaproject) |  |

### getHyperlinkQueries() {#getHyperlinkQueries--}
```
public final IHyperlinkQueries getHyperlinkQueries()
```

Fornisce un facile accesso a tutti i collegamenti ipertestuali contenuti in tutte le diapositive della presentazione (non in master, layout, note). Sola lettura [IHyperlinkQueries](../../com.aspose.slides/ihyperlinkqueries).

**Restituisce:**
[IHyperlinkQueries](../../com.aspose.slides/ihyperlinkqueries)

### getViewProperties() {#getViewProperties--}
```
public final IViewProperties getViewProperties()
```

Ottiene le proprietà di visualizzazione a livello di presentazione. Sola lettura [IViewProperties](../../com.aspose.slides/iviewproperties).

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

Restituisce la collezione di etichette di sensibilità applicate al documento della presentazione. Sola lettura [ISensitivityLabelCollection](../../com.aspose.slides/isensitivitylabelcollection).

--------------------

> ```
> Presentation pres = new Presentation("SomePresentation.pptx");
>  try {
>      ISensitivityLabelCollection sensitivityLabels = pres.getSensitivityLabels();
> 
>      // Stampa le etichette applicate
>      for (ISensitivityLabel sensitivityLabel : sensitivityLabels)
>          System.out.println("Label Id " + sensitivityLabel.getId() + " from Azure AD site " + sensitivityLabel.getSiteId());
> 
>      // Aggiungi la nuova etichetta
>      String labelIdString = "{xxxxxxxx-xxxx-xxxx-xxxx-xxxxxxxxxxxx}"; // Ottieni l'Id dell'etichetta di sensibilità dalla policy
>      UUID siteIdGuid = UUID.fromString("{xxxxxxxx-xxxx-xxxx-xxxx-xxxxxxxxxxxx}"); // Ottieni l'identificatore del sito Azure AD dalla policy
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
[IBaseSlide](../../com.aspose.slides/ibaseslide) - oggetto IBaseSlide.

### getSourceFormat() {#getSourceFormat--}
```
public final int getSourceFormat()
```

Restituisce informazioni sul formato da cui è stata caricata la presentazione. Sola lettura [SourceFormat](../../com.aspose.slides/sourceformat).

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
> //Istanzia un oggetto Presentation che rappresenta un file di presentazione
> Presentation pres = new Presentation("Subtle_Moderate_Intense.pptx");
> try {
>     pres.getMasterTheme().getFormatScheme().getLineStyles().get_Item(0).getFillFormat().getSolidFillColor().setColor(Color.RED);
>     ((FillFormat)pres.getMasterTheme().getFormatScheme().getLineStyles().get_Item(2)).setFillType(FillType.Solid);
>     ((FillFormat)pres.getMasterTheme().getFormatScheme().getLineStyles().get_Item(2)).getSolidFillColor().setColor(Color.GREEN);
>     ((EffectStyle)pres.getMasterTheme().getFormatScheme().getLineStyles().get_Item(2)).getEffectFormat().getOuterShadowEffect().setDistance(10f);
>     pres.save("Design_04_Subtle_Moderate_Intense-out.pptx", SaveFormat.Pptx);
> }
> finally
> {
>     if (pres != null) pres.dispose();
> }
```

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
| fname | java.lang.String | Percorso del file da creare. |
| format | int | Formato dei dati esportati. |

### save(OutputStream stream, int format) {#save-java.io.OutputStream-int-}
```
public final void save(OutputStream stream, int format)
```

Salva tutte le diapositive di una presentazione in un flusso nel formato specificato.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| stream | java.io.OutputStream | Flusso di output. |
| format | int | Formato dei dati esportati. |

### save(String fname, int format, ISaveOptions options) {#save-java.lang.String-int-com.aspose.slides.ISaveOptions-}
```
public final void save(String fname, int format, ISaveOptions options)
```

Salva tutte le diapositive di una presentazione in un file con il formato specificato e con opzioni aggiuntive.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| fname | java.lang.String | Percorso del file da creare. |
| format | int | Formato dei dati esportati. |
| options | [ISaveOptions](../../com.aspose.slides/isaveoptions) | Opzioni di formato aggiuntive. |

### save(OutputStream stream, int format, ISaveOptions options) {#save-java.io.OutputStream-int-com.aspose.slides.ISSaveOptions-}
```
public final void save(OutputStream stream, int format, ISaveOptions options)
```

Salva tutte le diapositive di una presentazione in un flusso nel formato specificato e con opzioni aggiuntive.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| stream | java.io.OutputStream | Flusso di output. |
| format | int | Formato dei dati esportati. |
| options | [ISaveOptions](../../com.aspose.slides/isaveoptions) | Opzioni di formato aggiuntive. |

### save(IXamlOptions options) {#save-com.aspose.slides.IXamlOptions-}
```
public final void save(IXamlOptions options)
```

Salva tutte le diapositive di una presentazione in un insieme di file che rappresentano markup XAML.

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
com.aspose.slides.IImage[] - Oggetti Image.

### getImages(IRenderingOptions options, int[] slides) {#getImages-com.aspose.slides.IRenderingOptions-int---}
```
public final IImage[] getImages(IRenderingOptions options, int[] slides)
```

Restituisce oggetti Image Thumbnail per le diapositive specificate di una presentazione.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Opzioni Tiff. |
| slides | int[] | Array con le posizioni delle diapositive, a partire da 1. |

**Restituisce:**
com.aspose.slides.IImage[] - Oggetti Image.

### getImages(IRenderingOptions options, float scaleX, float scaleY) {#getImages-com.aspose.slides.IRenderingOptions-float-float-}
```
public final IImage[] getImages(IRenderingOptions options, float scaleX, float scaleY)
```

Restituisce oggetti Image Thumbnail per tutte le diapositive di una presentazione con scaling personalizzato.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Opzioni Tiff. |
| scaleX | float | Valore di scaling sull’asse x. |
| scaleY | float | Valore di scaling sull’asse y. |

**Restituisce:**
com.aspose.slides.IImage[] - Oggetti Image.

### getImages(IRenderingOptions options, int[] slides, float scaleX, float scaleY) {#getImages-com.aspose.slides.IRenderingOptions-int---float-float-}
```
public final IImage[] getImages(IRenderingOptions options, int[] slides, float scaleX, float scaleY)
```

Restituisce oggetti Image Thumbnail per le diapositive specificate di una presentazione con scaling personalizzato.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Opzioni Tiff. |
| slides | int[] | Array con le posizioni delle diapositive, a partire da 1. |
| scaleX | float | Valore di scaling sull’asse x. |
| scaleY | float | Valore di scaling sull’asse y. |

**Restituisce:**
com.aspose.slides.IImage[] - Oggetti Image.

### getImages(IRenderingOptions options, Size imageSize) {#getImages-com.aspose.slides.IRenderingOptions-com.aspose.slides.android.Size-}
```
public final IImage[] getImages(IRenderingOptions options, Size imageSize)
```

Restituisce oggetti Image Thumbnail per tutte le diapositive di una presentazione con dimensione specificata.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Opzioni Tiff. |
| imageSize | [Size](../../com.aspose.slides.android/size) | Dimensione dell’immagine da creare. |

**Restituisce:**
com.aspose.slides.IImage[] - Oggetti Image.

### getImages(IRenderingOptions options, int[] slides, Size imageSize) {#getImages-com.aspose.slides.IRenderingOptions-int---com.aspose.slides.android.Size-}
```
public final IImage[] getImages(IRenderingOptions options, int[] slides, Size imageSize)
```

Restituisce oggetti Image Thumbnail per le diapositive specificate di una presentazione con dimensione specificata.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Opzioni Tiff. |
| slides | int[] | Array con le posizioni delle diapositive, a partire da 1. |
| imageSize | [Size](../../com.aspose.slides.android/size) | Dimensione dell’immagine da creare. |

**Restituisce:**
com.aspose.slides.IImage[] - Oggetti Image.

### save(String fname, int[] slides, int format) {#save-java.lang.String-int---int-}
```
public final void save(String fname, int[] slides, int format)
```

Salva le diapositive specificate di una presentazione in un file con il formato specificato mantenendo il numero di pagina.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| fname | java.lang.String | Percorso del file da creare. |
| slides | int[] | Array con le posizioni delle diapositive, a partire da 1. |
| format | int | Formato dei dati esportati. |

### save(String fname, int[] slides, int format, ISaveOptions options) {#save-java.lang.String-int---int-com.aspose.slides.ISSaveOptions-}
```
public final void save(String fname, int[] slides, int format, ISaveOptions options)
```

Salva le diapositive specificate di una presentazione in un file con il formato specificato mantenendo il numero di pagina.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| fname | java.lang.String | Percorso del file da creare. |
| slides | int[] | Array con le posizioni delle diapositive, a partire da 1. |
| format | int | Formato dei dati esportati. |
| options | [ISaveOptions](../../com.aspose.slides/isaveoptions) | Opzioni di formato aggiuntive. |

### save(OutputStream stream, int[] slides, int format) {#save-java.io.OutputStream-int---int-}
```
public final void save(OutputStream stream, int[] slides, int format)
```

Salva le diapositive specificate di una presentazione in un flusso nel formato specificato mantenendo il numero di pagina.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| stream | java.io.OutputStream | Flusso di output. |
| slides | int[] | Array con le posizioni delle diapositive, a partire da 1. |
| format | int | Formato dei dati esportati. |

### save(OutputStream stream, int[] slides, int format, ISaveOptions options) {#save-java.io.OutputStream-int---int-com.aspose.slides.ISSaveOptions-}
```
public final void save(OutputStream stream, int[] slides, int format, ISaveOptions options)
```

Salva le diapositive specificate di una presentazione in un flusso nel formato specificato mantenendo il numero di pagina.

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


**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| stream | java.io.OutputStream | Flusso di output. |
| slides | int[] | Array con le posizioni delle diapositive, a partire da 1. |
| format | int | Formato dei dati esportati. |
| options | [ISaveOptions](../../com.aspose.slides/isaveoptions) | Opzioni di formato aggiuntive. |

### joinPortionsWithSameFormatting() {#joinPortionsWithSameFormatting--}
```
public final void joinPortionsWithSameFormatting()
```

Unisce i run con la stessa formattazione in tutti i paragrafi di tutte le forme accettabili in tutte le diapositive.

### dispose() {#dispose--}
```
public final void dispose()
```

Rilascia tutte le risorse usate da questo oggetto Presentation.

### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

Restituisce la presentazione padre di un testo. Sola lettura [IPresentation](../../com.aspose.slides/ipresentation).

**Restituisce:**
[IPresentation](../../com.aspose.slides/ipresentation)

### highlightText(String text, Integer highlightColor) {#highlightText-java.lang.String-java.lang.Integer-}
```
public final void highlightText(String text, Integer highlightColor)
```

Evidenzia tutte le occorrenze del testo di esempio con il colore specificato.

> ```
> The following code sample shows how to highlight text in a PowerPoint presentation.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      // evidenzia tutte le occorrenze separate di 'the'
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
| highlightColor | java.lang.Integer | Il colore con cui evidenziare il testo. |

### highlightText(String text, Integer highlightColor, ITextSearchOptions options, IFindResultCallback callback) {#highlightText-java.lang.String-java.lang.Integer-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-}
```
public final void highlightText(String text, Integer highlightColor, ITextSearchOptions options, IFindResultCallback callback)
```

Evidenzia tutte le occorrenze del testo di esempio con il colore specificato.

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
| highlightColor | java.lang.Integer | Il colore con cui evidenziare il testo. |
| options | [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions) | Opzioni di ricerca testo [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions). |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | L’oggetto di callback per ricevere i risultati della ricerca [IFindResultCallback](../../com.aspose.slides/ifindresultcallback). |

### highlightRegex(Pattern regex, Integer highlightColor, IFindResultCallback callback) {#highlightRegex-java.util.regex.Pattern-java.lang.Integer-com.aspose.slides.IFindResultCallback-}
```
public final void highlightRegex(Pattern regex, Integer highlightColor, IFindResultCallback callback)
```

Evidenzia tutte le occorrenze dell’espressione regolare con il colore specificato.

> ```
> The following code sample shows how to highlight text in a PowerPoint Presentation using a regular expression.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      Pattern regex = Pattern.compile("\\b[^\\s]{10,}\\b");
>      // evidenzia tutte le parole con 10 o più caratteri
>      presentation.highlightRegex(regex, Color.BLUE, null);
>      presentation.save("SomePresentation-out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| regex | java.util.regex.Pattern | L’espressione regolare da evidenziare. |
| highlightColor | java.lang.Integer | Il colore con cui evidenziare il testo. |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | L’oggetto di callback per ricevere i risultati della ricerca [IFindResultCallback](../../com.aspose.slides/ifindresultcallback). |

### replaceText(String oldText, String newText, ITextSearchOptions options, IFindResultCallback callback) {#replaceText-java.lang.String-java.lang.String-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-}
```
public final void replaceText(String oldText, String newText, ITextSearchOptions options, IFindResultCallback callback)
```

Sostituisce tutte le occorrenze del testo specificato con un altro testo specificato.

> ```
> The following sample code shows how to replace one specified string with another specified string.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx")
>  try {
>      TextSearchOptions textSearchOptions = new TextSearchOptions();
>      textSearchOptions.setWholeWordsOnly(true);
>      // Sostituisce tutte le occorrenze separate di 'the' con '***'
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
| options | [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions) | Opzioni di ricerca testo [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions). |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | L’oggetto di callback per ricevere i risultati della ricerca [IFindResultCallback](../../com.aspose.slides/ifindresultcallback). |

### replaceRegex(Pattern regex, String newText, IFindResultCallback callback) {#replaceRegex-java.util.regex.Pattern-java.lang.String-com.aspose.slides.IFindResultCallback-}
```
public final void replaceRegex(Pattern regex, String newText, IFindResultCallback callback)
```

Sostituisce tutte le occorrenze dell’espressione regolare con la stringa specificata.

> ```
> The following code sample shows how to replace text using regular expression with the specified string.
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      Pattern regex = Pattern.compile("\\b[^\\s]{10,}\\b");
>      // Sostituisce tutte le parole con 10 o più simboli con '***'
>      presentation.replaceRegex(regex, "***", null);
>      presentation.save("SomePresentation-out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| regex | java.util.regex.Pattern | L’espressione regolare da sostituire. |
| newText | java.lang.String | La stringa con cui sostituire tutte le occorrenze della stringa da sostituire. |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | L’oggetto di callback per ricevere i risultati della ricerca [IFindResultCallback](../../com.aspose.slides/ifindresultcallback). |