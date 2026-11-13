---
title: IPresentation
second_title: Riferimento API Aspose.Slides per Java
description: Documento di presentazione
type: docs
url: /it/com.aspose.slides/ipresentation/
---
**Tutte le interfacce implementate:**
[com.aspose.slides.IPresentationComponent](../../com.aspose.slides/ipresentationcomponent), com.aspose.ms.System.IDisposable
```
public interface IPresentation extends IPresentationComponent, System.IDisposable
```

Documento di presentazione
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getCurrentDateTime()](#getCurrentDateTime--) | Restituisce o imposta data e ora che sostituiranno il contenuto dei campi datetime. |
| [setCurrentDateTime(Date value)](#setCurrentDateTime-java.util.Date-) | Restituisce o imposta data e ora che sostituiranno il contenuto dei campi datetime. |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | Restituisce il gestore HeaderFooter della presentazione. |
| [getProtectionManager()](#getProtectionManager--) | Ottiene il gestore delle autorizzazioni per questa presentazione. |
| [getSlides()](#getSlides--) | Restituisce un elenco di tutte le diapositive definite nella presentazione. |
| [getSections()](#getSections--) | Restituisce un elenco di tutte le sezioni diapositive definite nella presentazione. |
| [getSlideSize()](#getSlideSize--) | Restituisce l'oggetto di dimensione della diapositiva. |
| [getNotesSize()](#getNotesSize--) | Restituisce l'oggetto di dimensione delle note della diapositiva. |
| [getLayoutSlides()](#getLayoutSlides--) | Restituisce un elenco di tutte le diapositive di layout definite nella presentazione. |
| [getMasters()](#getMasters--) | Restituisce un elenco di tutte le diapositive master definite nella presentazione. |
| [getMasterNotesSlideManager()](#getMasterNotesSlideManager--) | Restituisce il gestore delle note master. |
| [getMasterHandoutSlideManager()](#getMasterHandoutSlideManager--) | Restituisce il gestore del master della stampa. |
| [getFontsManager()](#getFontsManager--) | Restituisce il gestore dei caratteri. |
| [getDefaultTextStyle()](#getDefaultTextStyle--) | Restituisce lo stile di testo predefinito per le forme. |
| [getCommentAuthors()](#getCommentAuthors--) | Restituisce la raccolta di autori dei commenti. |
| [getDocumentProperties()](#getDocumentProperties--) | Restituisce l'oggetto DocumentProperties che contiene le proprietà standard e personalizzate del documento. |
| [getImages()](#getImages--) | Restituisce la raccolta di tutte le immagini nella presentazione. |
| [getAudios()](#getAudios--) | Restituisce la raccolta di tutti i file audio incorporati nella presentazione. |
| [getVideos()](#getVideos--) | Restituisce la raccolta di tutti i file video incorporati nella presentazione. |
| [getCustomData()](#getCustomData--) | Restituisce i dati personalizzati della presentazione. |
| [getVbaProject()](#getVbaProject--) | Ottiene il progetto VBA con le macro della presentazione. |
| [setVbaProject(IVbaProject value)](#setVbaProject-com.aspose.slides.IVbaProject-) | Ottiene il progetto VBA con le macro della presentazione. |
| [getSourceFormat()](#getSourceFormat--) | Restituisce informazioni sul formato da cui è stata caricata la presentazione. |
| [getMasterTheme()](#getMasterTheme--) | Restituisce il tema master della presentazione. |
| [getHyperlinkQueries()](#getHyperlinkQueries--) | Fornisce un facile accesso a tutti i collegamenti ipertestuali contenuti in tutte le diapositive della presentazione (non nei master, layout, diapositive note). |
| [getViewProperties()](#getViewProperties--) | Ottiene le proprietà di visualizzazione a livello di presentazione. |
| [getFirstSlideNumber()](#getFirstSlideNumber--) | Rappresenta il numero della prima diapositiva nella presentazione. |
| [setFirstSlideNumber(int value)](#setFirstSlideNumber-int-) | Rappresenta il numero della prima diapositiva nella presentazione. |
| [getAllCustomXmlParts()](#getAllCustomXmlParts--) | Restituisce tutte le parti di dati personalizzati nella presentazione. |
| [getDigitalSignatures()](#getDigitalSignatures--) | Restituisce la raccolta di firme utilizzate per firmare la presentazione. |
| [getSensitivityLabels()](#getSensitivityLabels--) | Restituisce la raccolta di etichette di sensibilità applicate al documento della presentazione. |
| [save(String fname, int format)](#save-java.lang.String-int-) | Salva tutte le diapositive di una presentazione in un file con il formato specificato. |
| [save(OutputStream stream, int format)](#save-java.io.OutputStream-int-) | Salva tutte le diapositive di una presentazione in uno stream nel formato specificato. |
| [save(String fname, int format, ISaveOptions options)](#save-java.lang.String-int-com.aspose.slides.ISaveOptions-) | Salva tutte le diapositive di una presentazione in un file con il formato specificato e con opzioni aggiuntive. |
| [save(OutputStream stream, int format, ISaveOptions options)](#save-java.io.OutputStream-int-com.aspose.slides.ISaveOptions-) | Salva tutte le diapositive di una presentazione in uno stream nel formato specificato e con opzioni aggiuntive. |
| [save(String fname, int[] slides, int format)](#save-java.lang.String-int---int-) | Salva le diapositive specificate di una presentazione in un file con il formato specificato. |
| [save(String fname, int[] slides, int format, ISaveOptions options)](#save-java.lang.String-int---int-com.aspose.slides.ISaveOptions-) | Salva le diapositive specificate di una presentazione in un file con il formato specificato. |
| [save(OutputStream stream, int[] slides, int format)](#save-java.io.OutputStream-int---int-) | Salva le diapositive specificate di una presentazione in uno stream nel formato specificato. |
| [save(OutputStream stream, int[] slides, int format, ISaveOptions options)](#save-java.io.OutputStream-int---int-com.aspose.slides.ISaveOptions-) | Salva le diapositive specificate di una presentazione in uno stream nel formato specificato. |
| [save(IXamlOptions options)](#save-com.aspose.slides.IXamlOptions-) | Salva tutte le diapositive di una presentazione in un insieme di file che rappresentano il markup XAML. |
| [getImages(IRenderingOptions options)](#getImages-com.aspose.slides.IRenderingOptions-) | Restituisce oggetti Image Thumbnail per tutte le diapositive della presentazione. |
| [getImages(IRenderingOptions options, int[] slides)](#getImages-com.aspose.slides.IRenderingOptions-int---) | Restituisce oggetti IImage Thumbnail per le diapositive specificate della presentazione. |
| [getImages(IRenderingOptions options, float scaleX, float scaleY)](#getImages-com.aspose.slides.IRenderingOptions-float-float-) | Restituisce oggetti Image Thumbnail per tutte le diapositive della presentazione con scala personalizzata. |
| [getImages(IRenderingOptions options, int[] slides, float scaleX, float scaleY)](#getImages-com.aspose.slides.IRenderingOptions-int---float-float-) | Restituisce oggetti Image Thumbnail per le diapositive specificate della presentazione con scala personalizzata. |
| [getImages(IRenderingOptions options, Dimension imageSize)](#getImages-com.aspose.slides.IRenderingOptions-java.awt.Dimension-) | Restituisce oggetti Image Thumbnail per tutte le diapositive della presentazione con dimensione specificata. |
| [getImages(IRenderingOptions options, int[] slides, Dimension imageSize)](#getImages-com.aspose.slides.IRenderingOptions-int---java.awt.Dimension-) | Restituisce oggetti Image Thumbnail per le diapositive specificate della presentazione con dimensione specificata. |
| [getSlideById(long id)](#getSlideById-long-) | Restituisce una Slide, MasterSlide o LayoutSlide per Id. |
| [joinPortionsWithSameFormatting()](#joinPortionsWithSameFormatting--) | Unisce le run con la stessa formattazione in tutti i paragrafi in tutte le forme accettabili in tutte le diapositive. |
| [highlightText(String text, Color highlightColor)](#highlightText-java.lang.String-java.awt.Color-) | Evidenzia tutte le corrispondenze del testo di esempio con il colore specificato. |
| [highlightText(String text, Color highlightColor, ITextSearchOptions options, IFindResultCallback callback)](#highlightText-java.lang.String-java.awt.Color-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-) | Evidenzia tutte le corrispondenze del testo di esempio con il colore specificato. |
| [highlightRegex(Pattern regex, Color highlightColor, IFindResultCallback callback)](#highlightRegex-java.util.regex.Pattern-java.awt.Color-com.aspose.slides.IFindResultCallback-) | Evidenzia tutte le corrispondenze dell'espressione regolare con il colore specificato. |
| [replaceText(String oldText, String newText, ITextSearchOptions options, IFindResultCallback callback)](#replaceText-java.lang.String-java.lang.String-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-) | Sostituisce tutte le occorrenze del testo specificato con un altro testo specificato. |
| [replaceRegex(Pattern regex, String newText, IFindResultCallback callback)](#replaceRegex-java.util.regex.Pattern-java.lang.String-com.aspose.slides.IFindResultCallback-) | Sostituisce tutte le corrispondenze dell'espressione regolare con la stringa specificata. |
| [refreshChartsData()](#refreshChartsData--) | Ricarica i dati per tutti i grafici nella presentazione dai relativi workbook di origine. |
| [refreshChartsData(boolean skipFailedCharts)](#refreshChartsData-boolean-) | Ricarica i dati per tutti i grafici nella presentazione dai relativi workbook di origine. |

### getCurrentDateTime() {#getCurrentDateTime--}
```
public abstract Date getCurrentDateTime()
```

Restituisce o imposta data e ora che sostituiranno il contenuto dei campi datetime. Ora di creazione di questo oggetto Presentation per impostazione predefinita. Lettura/scrittura java.util.Date.

**Restituisce:**
java.util.Date

### setCurrentDateTime(Date value) {#setCurrentDateTime-java.util.Date-}
```
public abstract void setCurrentDateTime(Date value)
```

Restituisce o imposta data e ora che sostituiranno il contenuto dei campi datetime. Ora di creazione di questo oggetto Presentation per impostazione predefinita. Lettura/scrittura java.util.Date.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | java.util.Date |  |

### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public abstract IPresentationHeaderFooterManager getHeaderFooterManager()
```

Restituisce il gestore HeaderFooter della presentazione. Sola lettura [IPresentationHeaderFooterManager](../../com.aspose.slides/ipresentationheaderfootermanager).

**Restituisce:**
[IPresentationHeaderFooterManager](../../com.aspose.slides/ipresentationheaderfootermanager)

### getProtectionManager() {#getProtectionManager--}
```
public abstract IProtectionManager getProtectionManager()
```

Ottiene il gestore delle autorizzazioni per questa presentazione. Sola lettura [IProtectionManager](../../com.aspose.slides/iprotectionmanager).

**Restituisce:**
[IProtectionManager](../../com.aspose.slides/iprotectionmanager)

### getSlides() {#getSlides--}
```
public abstract ISlideCollection getSlides()
```

Restituisce un elenco di tutte le diapositive definite nella presentazione. Sola lettura [ISlideCollection](../../com.aspose.slides/islidecollection).

**Restituisce:**
[ISlideCollection](../../com.aspose.slides/islidecollection)

### getSections() {#getSections--}
```
public abstract ISectionCollection getSections()
```

Restituisce un elenco di tutte le sezioni diapositive definite nella presentazione. Sola lettura [ISectionCollection](../../com.aspose.slides/isectioncollection).

**Restituisce:**
[ISectionCollection](../../com.aspose.slides/isectioncollection)

### getSlideSize() {#getSlideSize--}
```
public abstract ISlideSize getSlideSize()
```

Restituisce l'oggetto di dimensione della diapositiva. Sola lettura [ISlideSize](../../com.aspose.slides/islidesize).

**Restituisce:**
[ISlideSize](../../com.aspose.slides/islidesize)

### getNotesSize() {#getNotesSize--}
```
public abstract INotesSize getNotesSize()
```

Restituisce l'oggetto di dimensione delle note della diapositiva. Sola lettura [INotesSize](../../com.aspose.slides/inotessize).

**Restituisce:**
[INotesSize](../../com.aspose.slides/inotessize)

### getLayoutSlides() {#getLayoutSlides--}
```
public abstract IGlobalLayoutSlideCollection getLayoutSlides()
```

Restituisce un elenco di tutte le diapositive di layout definite nella presentazione. Sola lettura [IGlobalLayoutSlideCollection](../../com.aspose.slides/igloballayoutslidecollection).

--------------------

È possibile accedere a un'API alternativa per aggiungere/inserire/rimuovere/clonare diapositive di layout utilizzando la proprietà IMasterSlide.LayoutSlides.

**Restituisce:**
[IGlobalLayoutSlideCollection](../../com.aspose.slides/igloballayoutslidecollection)

### getMasters() {#getMasters--}
```
public abstract IMasterSlideCollection getMasters()
```

Restituisce un elenco di tutte le diapositive master definite nella presentazione. Sola lettura [IMasterSlideCollection](../../com.aspose.slides/imasterslidecollection).

**Restituisce:**
[IMasterSlideCollection](../../com.aspose.slides/imasterslidecollection)

### getMasterNotesSlideManager() {#getMasterNotesSlideManager--}
```
public abstract IMasterNotesSlideManager getMasterNotesSlideManager()
```

Restituisce il gestore delle note master. Sola lettura [IMasterNotesSlideManager](../../com.aspose.slides/imasternotesslidemanager).

**Restituisce:**
[IMasterNotesSlideManager](../../com.aspose.slides/imasternotesslidemanager)

### getMasterHandoutSlideManager() {#getMasterHandoutSlideManager--}
```
public abstract IMasterHandoutSlideManager getMasterHandoutSlideManager()
```

Restituisce il gestore del master della stampa. Sola lettura [IMasterHandoutSlideManager](../../com.aspose.slides/imasterhandoutslidemanager).

**Restituisce:**
[IMasterHandoutSlideManager](../../com.aspose.slides/imasterhandoutslidemanager)

### getFontsManager() {#getFontsManager--}
```
public abstract IFontsManager getFontsManager()
```

Restituisce il gestore dei caratteri. Sola lettura [IFontsManager](../../com.aspose.slides/ifontsmanager).

**Restituisce:**
[IFontsManager](../../com.aspose.slides/ifontsmanager)

### getDefaultTextStyle() {#getDefaultTextStyle--}
```
public abstract ITextStyle getDefaultTextStyle()
```

Restituisce lo stile di testo predefinito per le forme. Sola lettura [ITextStyle](../../com.aspose.slides/itextstyle).

**Restituisce:**
[ITextStyle](../../com.aspose.slides/itextstyle)

### getCommentAuthors() {#getCommentAuthors--}
```
public abstract ICommentAuthorCollection getCommentAuthors()
```

Restituisce la raccolta di autori dei commenti. Sola lettura [ICommentAuthorCollection](../../com.aspose.slides/icommentauthorcollection).

**Restituisce:**
[ICommentAuthorCollection](../../com.aspose.slides/icommentauthorcollection)

### getDocumentProperties() {#getDocumentProperties--}
```
public abstract IDocumentProperties getDocumentProperties()
```

Restituisce l'oggetto DocumentProperties che contiene le proprietà standard e personalizzate del documento. Sola lettura [IDocumentProperties](../../com.aspose.slides/idocumentproperties).

**Restituisce:**
[IDocumentProperties](../../com.aspose.slides/idocumentproperties)

### getImages() {#getImages--}
```
public abstract IImageCollection getImages()
```

Restituisce la raccolta di tutte le immagini nella presentazione. Sola lettura [IImageCollection](../../com.aspose.slides/iimagecollection).

**Restituisce:**
[IImageCollection](../../com.aspose.slides/iimagecollection)

### getAudios() {#getAudios--}
```
public abstract IAudioCollection getAudios()
```

Restituisce la raccolta di tutti i file audio incorporati nella presentazione. Sola lettura [IAudioCollection](../../com.aspose.slides/iaudiocollection).

**Restituisce:**
[IAudioCollection](../../com.aspose.slides/iaudiocollection)

### getVideos() {#getVideos--}
```
public abstract IVideoCollection getVideos()
```

Restituisce la raccolta di tutti i file video incorporati nella presentazione. Sola lettura [IVideoCollection](../../com.aspose.slides/ivideocollection).

**Restituisce:**
[IVideoCollection](../../com.aspose.slides/ivideocollection)

### getCustomData() {#getCustomData--}
```
public abstract ICustomData getCustomData()
```

Restituisce i dati personalizzati della presentazione. Sola lettura [ICustomData](../../com.aspose.slides/icustomdata).

**Restituisce:**
[ICustomData](../../com.aspose.slides/icustomdata)

### getVbaProject() {#getVbaProject--}
```
public abstract IVbaProject getVbaProject()
```

Ottiene il progetto VBA con le macro della presentazione. Lettura/scrittura [IVbaProject](../../com.aspose.slides/ivbaproject).

**Restituisce:**
[IVbaProject](../../com.aspose.slides/ivbaproject)

### setVbaProject(IVbaProject value) {#setVbaProject-com.aspose.slides.IVbaProject-}
```
public abstract void setVbaProject(IVbaProject value)
```

Ottiene il progetto VBA con le macro della presentazione. Lettura/scrittura [IVbaProject](../../com.aspose.slides/ivbaproject).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [IVbaProject](../../com.aspose.slides/ivbaproject) |  |

### getSourceFormat() {#getSourceFormat--}
```
public abstract int getSourceFormat()
```

Restituisce informazioni sul formato da cui è stata caricata la presentazione. Sola lettura [SourceFormat](../../com.aspose.slides/sourceformat).

**Restituisce:**
int

### getMasterTheme() {#getMasterTheme--}
```
public abstract IMasterTheme getMasterTheme()
```

Restituisce il tema master della presentazione. Sola lettura [IMasterTheme](../../com.aspose.slides/imastertheme).

**Restituisce:**
[IMasterTheme](../../com.aspose.slides/imastertheme)

### getHyperlinkQueries() {#getHyperlinkQueries--}
```
public abstract IHyperlinkQueries getHyperlinkQueries()
```

Fornisce un facile accesso a tutti i collegamenti ipertestuali contenuti in tutte le diapositive della presentazione (non nei master, layout, diapositive note). Sola lettura [IHyperlinkQueries](../../com.aspose.slides/ihyperlinkqueries).

**Restituisce:**
[IHyperlinkQueries](../../com.aspose.slides/ihyperlinkqueries)

### getViewProperties() {#getViewProperties--}
```
public abstract IViewProperties getViewProperties()
```

Ottiene le proprietà di visualizzazione a livello di presentazione. Sola lettura [IViewProperties](../../com.aspose.slides/iviewproperties).

**Restituisce:**
[IViewProperties](../../com.aspose.slides/iviewproperties)

### getFirstSlideNumber() {#getFirstSlideNumber--}
```
public abstract int getFirstSlideNumber()
```

Rappresenta il numero della prima diapositiva nella presentazione. Lettura/scrittura int.

**Restituisce:**
int

### setFirstSlideNumber(int value) {#setFirstSlideNumber-int-}
```
public abstract void setFirstSlideNumber(int value)
```

Rappresenta il numero della prima diapositiva nella presentazione. Lettura/scrittura int.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | int |  |

### getAllCustomXmlParts() {#getAllCustomXmlParts--}
```
public abstract ICustomXmlPart[] getAllCustomXmlParts()
```

Restituisce tutte le parti di dati personalizzati nella presentazione. Sola lettura ICustomXmlPart[].

**Restituisce:**
com.aspose.slides.ICustomXmlPart[]

### getDigitalSignatures() {#getDigitalSignatures--}
```
public abstract IDigitalSignatureCollection getDigitalSignatures()
```

Restituisce la raccolta di firme utilizzate per firmare la presentazione. Sola lettura [IDigitalSignatureCollection](../../com.aspose.slides/idigitalsignaturecollection).

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
>                    + signature.getSignTime().toString() + " -- " + (signature.isValid() ? "VALID" : "INVALID"));
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

### getSensitivityLabels() {#getSensitivityLabels--}
```
public abstract ISensitivityLabelCollection getSensitivityLabels()
```

Restituisce la raccolta di etichette di sensibilità applicate al documento della presentazione. Sola lettura [ISensitivityLabelCollection](../../com.aspose.slides/isensitivitylabelcollection).

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

### save(String fname, int format) {#save-java.lang.String-int-}
```
public abstract void save(String fname, int format)
```

Salva tutte le diapositive di una presentazione in un file con il formato specificato.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| fname | java.lang.String | Percorso del file da creare. |
| format | int | Formato dei dati esportati. |

### save(OutputStream stream, int format) {#save-java.io.OutputStream-int-}
```
public abstract void save(OutputStream stream, int format)
```

Salva tutte le diapositive di una presentazione in uno stream nel formato specificato.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| stream | java.io.OutputStream | Stream di output. |
| format | int | Formato dei dati esportati. |

### save(String fname, int format, ISaveOptions options) {#save-java.lang.String-int-com.aspose.slides.ISaveOptions-}
```
public abstract void save(String fname, int format, ISaveOptions options)
```

Saves all slides of a presentation to a file with the specified format and with additional options.
Saves all slides of a presentation to a file with the specified format and with additional options.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| fname | java.lang.String | Percorso del file creato. |
| format | int | Formato dei dati esportati. |
| options | [ISaveOptions](../../com.aspose.slides/isaveoptions) | Opzioni di formato aggiuntive. |

### save(OutputStream stream, int format, ISaveOptions options) {#save-java.io.OutputStream-int-com.aspose.slides.ISaveOptions-}
```
public abstract void save(OutputStream stream, int format, ISaveOptions options)
```

Saves all slides of a presentation to a stream in the specified format and with additional options.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| stream | java.io.OutputStream | Stream di output. |
| format | int | Formato dei dati esportati. |
| options | [ISaveOptions](../../com.aspose.slides/isaveoptions) | Opzioni di formato aggiuntive. |

### save(String fname, int[] slides, int format) {#save-java.lang.String-int---int-}
```
public abstract void save(String fname, int[] slides, int format)
```

Saves specified slides of a presentation to a file with the specified format.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| fname | java.lang.String | Percorso del file creato. |
| slides | int[] | Array con le posizioni delle diapositive, a partire da 1. |
| format | int | Formato dei dati esportati. |

### save(String fname, int[] slides, int format, ISaveOptions options) {#save-java.lang.String-int---int-com.aspose.slides.ISaveOptions-}
```
public abstract void save(String fname, int[] slides, int format, ISaveOptions options)
```

Saves specified slides of a presentation to a file with the specified format.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| fname | java.lang.String | Percorso del file creato. |
| slides | int[] | Array con le posizioni delle diapositive, a partire da 1. |
| format | int | Formato dei dati esportati. |
| options | [ISaveOptions](../../com.aspose.slides/isaveoptions) | Opzioni di formato aggiuntive. |

### save(OutputStream stream, int[] slides, int format) {#save-java.io.OutputStream-int---int-}
```
public abstract void save(OutputStream stream, int[] slides, int format)
```

Saves specified slides of a presentation to a stream in the specified format.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| stream | java.io.OutputStream | Stream di output. |
| slides | int[] | Array con le posizioni delle diapositive, a partire da 1. |
| format | int | Formato dei dati esportati. |

### save(OutputStream stream, int[] slides, int format, ISaveOptions options) {#save-java.io.OutputStream-int---int-com.aspose.slides.ISaveOptions-}
```
public abstract void save(OutputStream stream, int[] slides, int format, ISaveOptions options)
```

Saves specified slides of a presentation to a stream in the specified format.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| stream | java.io.OutputStream | Stream di output. |
| slides | int[] | Array con le posizioni delle diapositive, a partire da 1. |
| format | int | Formato dei dati esportati. |
| options | [ISaveOptions](../../com.aspose.slides/isaveoptions) | Opzioni di formato aggiuntive. |

### save(IXamlOptions options) {#save-com.aspose.slides.IXamlOptions-}
```
public abstract void save(IXamlOptions options)
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

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| options | [IXamlOptions](../../com.aspose.slides/ixamloptions) | Le opzioni di formato XAML. |

### getImages(IRenderingOptions options) {#getImages-com.aspose.slides.IRenderingOptions-}
```
public abstract IImage[] getImages(IRenderingOptions options)
```

Returns a Thumbnail Image objects for all slides of a presentation.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Opzioni di rendering. |

**Restituisce:**
com.aspose.slides.IImage[] - IImage objects.
### getImages(IRenderingOptions options, int[] slides) {#getImages-com.aspose.slides.IRenderingOptions-int---}
```
public abstract IImage[] getImages(IRenderingOptions options, int[] slides)
```

Returns a Thumbnail IImage objects for specified slides of a presentation.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Opzioni di rendering. |
| slides | int[] | Array con le posizioni delle diapositive, a partire da 1. |

**Restituisce:**
com.aspose.slides.IImage[] - IImage objects.
### getImages(IRenderingOptions options, float scaleX, float scaleY) {#getImages-com.aspose.slides.IRenderingOptions-float-float-}
```
public abstract IImage[] getImages(IRenderingOptions options, float scaleX, float scaleY)
```

Returns a Thumbnail Image objects for all slides of a presentation with custom scaling.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Opzioni di rendering. |
| scaleX | float | Il valore con cui scalare questa miniatura nella direzione dell'asse x. |
| scaleY | float | Il valore con cui scalare questa miniatura nella direzione dell'asse y. |

**Restituisce:**
com.aspose.slides.IImage[] - Bitmap objects.
### getImages(IRenderingOptions options, int[] slides, float scaleX, float scaleY) {#getImages-com.aspose.slides.IRenderingOptions-int---float-float-}
```
public abstract IImage[] getImages(IRenderingOptions options, int[] slides, float scaleX, float scaleY)
```

Returns a Thumbnail Image objects for specified slides of a presentation with custom scaling.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Opzioni di rendering. |
| slides | int[] | Array con le posizioni delle diapositive, a partire da 1. |
| scaleX | float | Il valore con cui scalare questa miniatura nella direzione dell'asse x. |
| scaleY | float | Il valore con cui scalare questa miniatura nella direzione dell'asse y. |

**Restituisce:**
com.aspose.slides.IImage[] - IImage objects.
### getImages(IRenderingOptions options, Dimension imageSize) {#getImages-com.aspose.slides.IRenderingOptions-java.awt.Dimension-}
```
public abstract IImage[] getImages(IRenderingOptions options, Dimension imageSize)
```

Returns a Thumbnail Image objects for all slides of a presentation with specified size.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Opzioni di rendering. |
| imageSize | java.awt.Dimension | Dimensione dell'immagine da creare. |

**Restituisce:**
com.aspose.slides.IImage[] - IImage objects.
### getImages(IRenderingOptions options, int[] slides, Dimension imageSize) {#getImages-com.aspose.slides.IRenderingOptions-int---java.awt.Dimension-}
```
public abstract IImage[] getImages(IRenderingOptions options, int[] slides, Dimension imageSize)
```

Returns a Thumbnail Image objects for specified slides of a presentation with specified size.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Opzioni di rendering. |
| slides | int[] | Array con le posizioni delle diapositive, a partire da 1. |
| imageSize | java.awt.Dimension | Dimensione dell'immagine da creare. |

**Restituisce:**
com.aspose.slides.IImage[] - IImage objects.
### getSlideById(long id) {#getSlideById-long-}
```
public abstract IBaseSlide getSlideById(long id)
```

Returns a Slide, MasterSlide or LayoutSlide by Id.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| id | long | Id di una diapositiva. |

**Restituisce:**
[IBaseSlide](../../com.aspose.slides/ibaseslide) - IBaseSlide object.
### joinPortionsWithSameFormatting() {#joinPortionsWithSameFormatting--}
```
public abstract void joinPortionsWithSameFormatting()
```

Joins runs with same formatting in all paragraphs in all acceptable shapes in all slides.

### highlightText(String text, Color highlightColor) {#highlightText-java.lang.String-java.awt.Color-}
```
public abstract void highlightText(String text, Color highlightColor)
```

Highlights all matches of the sample text with the specified color.

--------------------

> ```
> The following code sample shows how to highlight text in a PowerPoint presentation.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      // evidenziare tutte le occorrenze separate di 'the'
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
public abstract void highlightText(String text, Color highlightColor, ITextSearchOptions options, IFindResultCallback callback)
```

Highlights all matches of the sample text with the specified color.

--------------------

> ```
> The following code sample shows how to highlight text in a PowerPoint presentation.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      // evidenziare tutte le occorrenze separate di 'the'
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
| options | [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions) | Opzioni di ricerca del testo [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions). |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | L'oggetto callback per ricevere i risultati della ricerca [IFindResultCallback](../../com.aspose.slides/ifindresultcallback). |

### highlightRegex(Pattern regex, Color highlightColor, IFindResultCallback callback) {#highlightRegex-java.util.regex.Pattern-java.awt.Color-com.aspose.slides.IFindResultCallback-}
```
public abstract void highlightRegex(Pattern regex, Color highlightColor, IFindResultCallback callback)
```

Highlights all matches of the regular expression with the specified color.

--------------------

> ```
> The following code sample shows how to highlight text in a PowerPoint Presentation using a regular expression.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      // evidenziare tutte le occorrenze separate di 'the'
>      presentation.highlightText("the", Color.MAGENTA);
>      presentation.save("SomePresentation-out2.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| regex | java.util.regex.Pattern | L'espressione regolare java.util.regex.Pattern per ottenere le stringhe da evidenziare. |
| highlightColor | java.awt.Color | Il colore per evidenziare il testo. |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | L'oggetto callback per ricevere i risultati della ricerca [IFindResultCallback](../../com.aspose.slides/ifindresultcallback). |

### replaceText(String oldText, String newText, ITextSearchOptions options, IFindResultCallback callback) {#replaceText-java.lang.String-java.lang.String-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-}
```
public abstract void replaceText(String oldText, String newText, ITextSearchOptions options, IFindResultCallback callback)
```

Replaces all occurrences of the specified text with another specified text.

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
| newText | java.lang.String | La stringa per sostituire tutte le occorrenze di oldText. |
| options | [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions) | Opzioni di ricerca del testo [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions). |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | L'oggetto callback per ricevere i risultati della ricerca [IFindResultCallback](../../com.aspose.slides/ifindresultcallback). |

### replaceRegex(Pattern regex, String newText, IFindResultCallback callback) {#replaceRegex-java.util.regex.Pattern-java.lang.String-com.aspose.slides.IFindResultCallback-}
```
public abstract void replaceRegex(Pattern regex, String newText, IFindResultCallback callback)
```

Replaces all matches of the regular expression with the specified string.

--------------------

> ```
> The following code sample shows how to replace text using regular expression with the specified string.
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
| regex | java.util.regex.Pattern | L'espressione regolare java.util.regex.Pattern per ottenere le stringhe da sostituire. |
| newText | java.lang.String | La stringa per sostituire tutte le occorrenze delle stringhe da sostituire. |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | L'oggetto callback per ricevere i risultati della ricerca [IFindResultCallback](../../com.aspose.slides/ifindresultcallback). |

### refreshChartsData() {#refreshChartsData--}
```
public abstract void refreshChartsData()
```

Reloads the data for all charts in the presentation from their source workbooks.

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
public abstract void refreshChartsData(boolean skipFailedCharts)
```

Reloads the data for all charts in the presentation from their source workbooks.

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
| skipFailedCharts | boolean | Determina se il processo di aggiornamento continua nel caso un grafico non riesca ad aggiornarsi. Se true, i grafici che causano un'eccezione vengono omessi; altrimenti l'eccezione viene propagata. |