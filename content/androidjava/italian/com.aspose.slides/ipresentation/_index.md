---
title: IPresentation
second_title: Aspose.Slides per Android via Java API Reference
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
| [getProtectionManager()](#getProtectionManager--) | Restituisce il gestore dei permessi per questa presentazione. |
| [getSlides()](#getSlides--) | Restituisce un elenco di tutte le diapositive definite nella presentazione. |
| [getSections()](#getSections--) | Restituisce un elenco di tutte le sezioni di diapositive definite nella presentazione. |
| [getSlideSize()](#getSlideSize--) | Restituisce l'oggetto dimensione diapositiva. |
| [getNotesSize()](#getNotesSize--) | Restituisce l'oggetto dimensione diapositiva note. |
| [getLayoutSlides()](#getLayoutSlides--) | Restituisce un elenco di tutte le diapositive layout definite nella presentazione. |
| [getMasters()](#getMasters--) | Restituisce un elenco di tutte le diapositive master definite nella presentazione. |
| [getMasterNotesSlideManager()](#getMasterNotesSlideManager--) | Restituisce il gestore master delle note. |
| [getMasterHandoutSlideManager()](#getMasterHandoutSlideManager--) | Restituisce il gestore master del documento di stampa. |
| [getFontsManager()](#getFontsManager--) | Restituisce il gestore dei font. |
| [getDefaultTextStyle()](#getDefaultTextStyle--) | Restituisce lo stile di testo predefinito per le forme. |
| [getCommentAuthors()](#getCommentAuthors--) | Restituisce la collezione degli autori dei commenti. |
| [getDocumentProperties()](#getDocumentProperties--) | Restituisce l'oggetto DocumentProperties che contiene le proprietà standard e personalizzate del documento. |
| [getImages()](#getImages--) | Restituisce la collezione di tutte le immagini nella presentazione. |
| [getAudios()](#getAudios--) | Restituisce la collezione di tutti i file audio incorporati nella presentazione. |
| [getVideos()](#getVideos--) | Restituisce la collezione di tutti i file video incorporati nella presentazione. |
| [getCustomData()](#getCustomData--) | Restituisce i dati personalizzati della presentazione. |
| [getVbaProject()](#getVbaProject--) | Restituisce il progetto VBA con le macro della presentazione. |
| [setVbaProject(IVbaProject value)](#setVbaProject-com.aspose.slides.IVbaProject-) | Restituisce il progetto VBA con le macro della presentazione. |
| [getSourceFormat()](#getSourceFormat--) | Restituisce informazioni sul formato da cui è stata caricata la presentazione. |
| [getMasterTheme()](#getMasterTheme--) | Restituisce il tema master della presentazione. |
| [getHyperlinkQueries()](#getHyperlinkQueries--) | Fornisce un facile accesso a tutti i collegamenti ipertestuali contenuti in tutte le diapositive della presentazione (non in master, layout, diapositive note). |
| [getViewProperties()](#getViewProperties--) | Restituisce le proprietà di visualizzazione dell'intera presentazione. |
| [getFirstSlideNumber()](#getFirstSlideNumber--) | Rappresenta il numero della prima diapositiva nella presentazione. |
| [setFirstSlideNumber(int value)](#setFirstSlideNumber-int-) | Rappresenta il numero della prima diapositiva nella presentazione. |
| [getAllCustomXmlParts()](#getAllCustomXmlParts--) | Restituisce tutte le parti di dati personalizzati nella presentazione. |
| [getDigitalSignatures()](#getDigitalSignatures--) | Restituisce la collezione delle firme utilizzate per firmare la presentazione. |
| [getSensitivityLabels()](#getSensitivityLabels--) | Restituisce la collezione delle etichette di sensibilità applicate al documento di presentazione. |
| [save(String fname, int format)](#save-java.lang.String-int-) | Salva tutte le diapositive di una presentazione in un file con il formato specificato. |
| [save(OutputStream stream, int format)](#save-java.io.OutputStream-int-) | Salva tutte le diapositive di una presentazione in un flusso nel formato specificato. |
| [save(String fname, int format, ISaveOptions options)](#save-java.lang.String-int-com.aspose.slides.ISaveOptions-) | Salva tutte le diapositive di una presentazione in un file con il formato specificato e con opzioni aggiuntive. |
| [save(OutputStream stream, int format, ISaveOptions options)](#save-java.io.OutputStream-int-com.aspose.slides.ISaveOptions-) | Salva tutte le diapositive di una presentazione in un flusso nel formato specificato e con opzioni aggiuntive. |
| [save(String fname, int[] slides, int format)](#save-java.lang.String-int---int-) | Salva le diapositive specificate di una presentazione in un file con il formato specificato. |
| [save(String fname, int[] slides, int format, ISaveOptions options)](#save-java.lang.String-int---int-com.aspose.slides.ISaveOptions-) | Salva le diapositive specificate di una presentazione in un file con il formato specificato. |
| [save(OutputStream stream, int[] slides, int format)](#save-java.io.OutputStream-int---int-) | Salva le diapositive specificate di una presentazione in un flusso nel formato specificato. |
| [save(OutputStream stream, int[] slides, int format, ISaveOptions options)](#save-java.io.OutputStream-int---int-com.aspose.slides.ISaveOptions-) | Salva le diapositive specificate di una presentazione in un flusso nel formato specificato. |
| [save(IXamlOptions options)](#save-com.aspose.slides.IXamlOptions-) | Salva tutte le diapositive di una presentazione in un insieme di file che rappresentano il markup XAML. |
| [getImages(IRenderingOptions options)](#getImages-com.aspose.slides.IRenderingOptions-) | Restituisce oggetti Image Thumbnail per tutte le diapositive di una presentazione. |
| [getImages(IRenderingOptions options, int[] slides)](#getImages-com.aspose.slides.IRenderingOptions-int---) | Restituisce oggetti IImage Thumbnail per le diapositive specificate di una presentazione. |
| [getImages(IRenderingOptions options, float scaleX, float scaleY)](#getImages-com.aspose.slides.IRenderingOptions-float-float-) | Restituisce oggetti Image Thumbnail per tutte le diapositive di una presentazione con scala personalizzata. |
| [getImages(IRenderingOptions options, int[] slides, float scaleX, float scaleY)](#getImages-com.aspose.slides.IRenderingOptions-int---float-float-) | Restituisce oggetti Image Thumbnail per le diapositive specificate di una presentazione con scala personalizzata. |
| [getImages(IRenderingOptions options, Size imageSize)](#getImages-com.aspose.slides.IRenderingOptions-com.aspose.slides.android.Size-) | Restituisce oggetti Image Thumbnail per tutte le diapositive di una presentazione con dimensione specificata. |
| [getImages(IRenderingOptions options, int[] slides, Size imageSize)](#getImages-com.aspose.slides.IRenderingOptions-int---com.aspose.slides.android.Size-) | Restituisce oggetti Image Thumbnail per le diapositive specificate di una presentazione con dimensione specificata. |
| [getSlideById(long id)](#getSlideById-long-) | Restituisce una Slide, MasterSlide o LayoutSlide per Id. |
| [joinPortionsWithSameFormatting()](#joinPortionsWithSameFormatting--) | Unisce le porzioni con lo stesso formato in tutti i paragrafi di tutte le forme accettabili in tutte le diapositive. |
| [highlightText(String text, Integer highlightColor)](#highlightText-java.lang.String-java.lang.Integer-) | Evidenzia tutte le corrispondenze del testo di esempio con il colore specificato. |
| [highlightText(String text, Integer highlightColor, ITextSearchOptions options, IFindResultCallback callback)](#highlightText-java.lang.String-java.lang.Integer-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-) | Evidenzia tutte le corrispondenze del testo di esempio con il colore specificato. |
| [highlightRegex(Pattern regex, Integer highlightColor, IFindResultCallback callback)](#highlightRegex-java.util.regex.Pattern-java.lang.Integer-com.aspose.slides.IFindResultCallback-) | Evidenzia tutte le corrispondenze dell'espressione regolare con il colore specificato. |
| [replaceText(String oldText, String newText, ITextSearchOptions options, IFindResultCallback callback)](#replaceText-java.lang.String-java.lang.String-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-) | Sostituisce tutte le occorrenze del testo specificato con un altro testo specificato. |
| [replaceRegex(Pattern regex, String newText, IFindResultCallback callback)](#replaceRegex-java.util.regex.Pattern-java.lang.String-com.aspose.slides.IFindResultCallback-) | Sostituisce tutte le corrispondenze dell'espressione regolare con la stringa specificata. |

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

Restituisce il gestore HeaderFooter della presentazione. Solo lettura [IPresentationHeaderFooterManager](../../com.aspose.slides/ipresentationheaderfootermanager).

**Restituisce:**
[IPresentationHeaderFooterManager](../../com.aspose.slides/ipresentationheaderfootermanager)

### getProtectionManager() {#getProtectionManager--}
```
public abstract IProtectionManager getProtectionManager()
```

Restituisce il gestore dei permessi per questa presentazione. Solo lettura [IProtectionManager](../../com.aspose.slides/iprotectionmanager).

**Restituisce:**
[IProtectionManager](../../com.aspose.slides/iprotectionmanager)

### getSlides() {#getSlides--}
```
public abstract ISlideCollection getSlides()
```

Restituisce un elenco di tutte le diapositive definite nella presentazione. Solo lettura [ISlideCollection](../../com.aspose.slides/islidecollection).

**Restituisce:**
[ISlideCollection](../../com.aspose.slides/islidecollection)

### getSections() {#getSections--}
```
public abstract ISectionCollection getSections()
```

Restituisce un elenco di tutte le sezioni di diapositive definite nella presentazione. Solo lettura [ISectionCollection](../../com.aspose.slides/isectioncollection).

**Restituisce:**
[ISectionCollection](../../com.aspose.slides/isectioncollection)

### getSlideSize() {#getSlideSize--}
```
public abstract ISlideSize getSlideSize()
```

Restituisce l'oggetto dimensione diapositiva. Solo lettura [ISlideSize](../../com.aspose.slides/islidesize).

**Restituisce:**
[ISlideSize](../../com.aspose.slides/islidesize)

### getNotesSize() {#getNotesSize--}
```
public abstract INotesSize getNotesSize()
```

Restituisce l'oggetto dimensione diapositiva note. Solo lettura [INotesSize](../../com.aspose.slides/inotessize).

**Restituisce:**
[INotesSize](../../com.aspose.slides/inotessize)

### getLayoutSlides() {#getLayoutSlides--}
```
public abstract IGlobalLayoutSlideCollection getLayoutSlides()
```

Restituisce un elenco di tutte le diapositive layout definite nella presentazione. Solo lettura [IGlobalLayoutSlideCollection](../../com.aspose.slides/igloballayoutslidecollection).

--------------------

È possibile accedere a un'API alternativa per aggiungere/inserire/rimuovere/duplicare diapositive layout usando la proprietà IMasterSlide.LayoutSlides.

**Restituisce:**
[IGlobalLayoutSlideCollection](../../com.aspose.slides/igloballayoutslidecollection)

### getMasters() {#getMasters--}
```
public abstract IMasterSlideCollection getMasters()
```

Restituisce un elenco di tutte le diapositive master definite nella presentazione. Solo lettura [IMasterSlideCollection](../../com.aspose.slides/imasterslidecollection).

**Restituisce:**
[IMasterSlideCollection](../../com.aspose.slides/imasterslidecollection)

### getMasterNotesSlideManager() {#getMasterNotesSlideManager--}
```
public abstract IMasterNotesSlideManager getMasterNotesSlideManager()
```

Restituisce il gestore master delle note. Solo lettura [IMasterNotesSlideManager](../../com.aspose.slides/imasternotesslidemanager).

**Restituisce:**
[IMasterNotesSlideManager](../../com.aspose.slides/imasternotesslidemanager)

### getMasterHandoutSlideManager() {#getMasterHandoutSlideManager--}
```
public abstract IMasterHandoutSlideManager getMasterHandoutSlideManager()
```

Restituisce il gestore master del documento di stampa. Solo lettura [IMasterHandoutSlideManager](../../com.aspose.slides/imasterhandoutslidemanager).

**Restituisce:**
[IMasterHandoutSlideManager](../../com.aspose.slides/imasterhandoutslidemanager)

### getFontsManager() {#getFontsManager--}
```
public abstract IFontsManager getFontsManager()
```

Restituisce il gestore dei font. Solo lettura [IFontsManager](../../com.aspose.slides/ifontsmanager).

**Restituisce:**
[IFontsManager](../../com.aspose.slides/ifontsmanager)

### getDefaultTextStyle() {#getDefaultTextStyle--}
```
public abstract ITextStyle getDefaultTextStyle()
```

Restituisce lo stile di testo predefinito per le forme. Solo lettura [ITextStyle](../../com.aspose.slides/itextstyle).

**Restituisce:**
[ITextStyle](../../com.aspose.slides/itextstyle)

### getCommentAuthors() {#getCommentAuthors--}
```
public abstract ICommentAuthorCollection getCommentAuthors()
```

Restituisce la collezione degli autori dei commenti. Solo lettura [ICommentAuthorCollection](../../com.aspose.slides/icommentauthorcollection).

**Restituisce:**
[ICommentAuthorCollection](../../com.aspose.slides/icommentauthorcollection)

### getDocumentProperties() {#getDocumentProperties--}
```
public abstract IDocumentProperties getDocumentProperties()
```

Restituisce l'oggetto DocumentProperties che contiene le proprietà standard e personalizzate del documento. Solo lettura [IDocumentProperties](../../com.aspose.slides/idocumentproperties).

**Restituisce:**
[IDocumentProperties](../../com.aspose.slides/idocumentproperties)

### getImages() {#getImages--}
```
public abstract IImageCollection getImages()
```

Restituisce la collezione di tutte le immagini nella presentazione. Solo lettura [IImageCollection](../../com.aspose.slides/iimagecollection).

**Restituisce:**
[IImageCollection](../../com.aspose.slides/iimagecollection)

### getAudios() {#getAudios--}
```
public abstract IAudioCollection getAudios()
```

Restituisce la collezione di tutti i file audio incorporati nella presentazione. Solo lettura [IAudioCollection](../../com.aspose.slides/iaudiocollection).

**Restituisce:**
[IAudioCollection](../../com.aspose.slides/iaudiocollection)

### getVideos() {#getVideos--}
```
public abstract IVideoCollection getVideos()
```

Restituisce la collezione di tutti i file video incorporati nella presentazione. Solo lettura [IVideoCollection](../../com.aspose.slides/ivideocollection).

**Restituisce:**
[IVideoCollection](../../com.aspose.slides/ivideocollection)

### getCustomData() {#getCustomData--}
```
public abstract ICustomData getCustomData()
```

Restituisce i dati personalizzati della presentazione. Solo lettura [ICustomData](../../com.aspose.slides/icustomdata).

**Restituisce:**
[ICustomData](../../com.aspose.slides/icustomdata)

### getVbaProject() {#getVbaProject--}
```
public abstract IVbaProject getVbaProject()
```

Restituisce il progetto VBA con le macro della presentazione. Lettura/scrittura [IVbaProject](../../com.aspose.slides/ivbaproject).

**Restituisce:**
[IVbaProject](../../com.aspose.slides/ivbaproject)

### setVbaProject(IVbaProject value) {#setVbaProject-com.aspose.slides.IVbaProject-}
```
public abstract void setVbaProject(IVbaProject value)
```

Restituisce il progetto VBA con le macro della presentazione. Lettura/scrittura [IVbaProject](../../com.aspose.slides/ivbaproject).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [IVbaProject](../../com.aspose.slides/ivbaproject) |  |

### getSourceFormat() {#getSourceFormat--}
```
public abstract int getSourceFormat()
```

Restituisce informazioni sul formato da cui è stata caricata la presentazione. Solo lettura [SourceFormat](../../com.aspose.slides/sourceformat).

**Restituisce:**
int

### getMasterTheme() {#getMasterTheme--}
```
public abstract IMasterTheme getMasterTheme()
```

Restituisce il tema master della presentazione. Solo lettura [IMasterTheme](../../com.aspose.slides/imastertheme).

**Restituisce:**
[IMasterTheme](../../com.aspose.slides/imastertheme)

### getHyperlinkQueries() {#getHyperlinkQueries--}
```
public abstract IHyperlinkQueries getHyperlinkQueries()
```

Fornisce un facile accesso a tutti i collegamenti ipertestuali contenuti in tutte le diapositive della presentazione (non in master, layout, diapositive note). Solo lettura [IHyperlinkQueries](../../com.aspose.slides/ihyperlinkqueries).

**Restituisce:**
[IHyperlinkQueries](../../com.aspose.slides/ihyperlinkqueries)

### getViewProperties() {#getViewProperties--}
```
public abstract IViewProperties getViewProperties()
```

Restituisce le proprietà di visualizzazione dell'intera presentazione. Solo lettura [IViewProperties](../../com.aspose.slides/iviewproperties).

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

Restituisce tutte le parti di dati personalizzati nella presentazione. Solo lettura ICustomXmlPart[].

**Restituisce:**
com.aspose.slides.ICustomXmlPart[]

### getDigitalSignatures() {#getDigitalSignatures--}
```
public abstract IDigitalSignatureCollection getDigitalSignatures()
```

Restituisce la collezione delle firme utilizzate per firmare la presentazione. Solo lettura [IDigitalSignatureCollection](../../com.aspose.slides/idigitalsignaturecollection).

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

Restituisce la collezione delle etichette di sensibilità applicate al documento di presentazione. Solo lettura [ISensitivityLabelCollection](../../com.aspose.slides/isensitivitylabelcollection).

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

Salva tutte le diapositive di una presentazione in un flusso nel formato specificato.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| stream | java.io.OutputStream | Flusso di output. |
| format | int | Formato dei dati esportati. |

### save(String fname, int format, ISaveOptions options) {#save-java.lang.String-int-com.aspose.slides.ISaveOptions-}
```
public abstract void save(String fname, int format, ISaveOptions options)
```

Salva tutte le diapositive di una presentazione in un file con il formato specificato e con opzioni aggiuntive.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| fname | java.lang.String | Percorso del file da creare. |
| format | int | Formato dei dati esportati. |
| options | [ISaveOptions](../../com.aspose.slides/isaveoptions) | Opzioni aggiuntive del formato. |

### save(OutputStream stream, int format, ISaveOptions options) {#save-java.io.OutputStream-int-com.aspose.slides.ISaveOptions-}
```
public abstract void save(OutputStream stream, int format, ISaveOptions options)
```

Salva tutte le diapositive di una presentazione in un flusso nel formato specificato e con opzioni aggiuntive.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| stream | java.io.OutputStream | Flusso di output. |
| format | int | Formato dei dati esportati. |
| options | [ISaveOptions](../../com.aspose.slides/isaveoptions) | Opzioni aggiuntive del formato. |

### save(String fname, int[] slides, int format) {#save-java.lang.String-int---int-}
```
public abstract void save(String fname, int[] slides, int format)
```

Salva le diapositive specificate di una presentazione in un file con il formato specificato.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| fname | java.lang.String | Percorso del file da creare. |
| slides | int[] | Array con le posizioni delle diapositive, a partire da 1. |
| format | int | Formato dei dati esportati. |

### save(String fname, int[] slides, int format, ISaveOptions options) {#save-java.lang.String-int---int-com.aspose.slides.ISaveOptions-}
```
public abstract void save(String fname, int[] slides, int format, ISaveOptions options)
```

Salva le diapositive specificate di una presentazione in un file con il formato specificato.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| fname | java.lang.String | Percorso del file da creare. |
| slides | int[] | Array con le posizioni delle diapositive, a partire da 1. |
| format | int | Formato dei dati esportati. |
| options | [ISaveOptions](../../com.aspose.slides/isaveoptions) | Opzioni aggiuntive del formato. |

### save(OutputStream stream, int[] slides, int format) {#save-java.io.OutputStream-int---int-}
```
public abstract void save(OutputStream stream, int[] slides, int format)
```

Salva le diapositive specificate di una presentazione in un flusso nel formato specificato.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| stream | java.io.OutputStream | Flusso di output. |
| slides | int[] | Array con le posizioni delle diapositive, a partire da 1. |
| format | int | Formato dei dati esportati. |

### save(OutputStream stream, int[] slides, int format, ISaveOptions options) {#save-java.io.OutputStream-int---int-com.aspose.slides.ISaveOptions-}
```
public abstract void save(OutputStream stream, int[] slides, int format, ISaveOptions options)
```

Salva le diapositive specificate di una presentazione in un flusso nel formato specificato.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| stream | java.io.OutputStream | Flusso di output. |
| slides | int[] | Array con le posizioni delle diapositive, a partire da 1. |
| format | int | Formato dei dati esportati. |
| options | [ISaveOptions](../../com.aspose.slides/isaveoptions) | Opzioni aggiuntive del formato. |

### save(IXamlOptions options) {#save-com.aspose.slides.IXamlOptions-}
```
public abstract void save(IXamlOptions options)
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
public abstract IImage[] getImages(IRenderingOptions options)
```

Restituisce oggetti Image Thumbnail per tutte le diapositive di una presentazione.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Opzioni di rendering. |

**Restituisce:**
com.aspose.slides.IImage[] - oggetti IImage.

### getImages(IRenderingOptions options, int[] slides) {#getImages-com.aspose.slides.IRenderingOptions-int---}
```
public abstract IImage[] getImages(IRenderingOptions options, int[] slides)
```

Restituisce oggetti IImage Thumbnail per le diapositive specificate di una presentazione.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Opzioni di rendering. |
| slides | int[] | Array con le posizioni delle diapositive, a partire da 1. |

**Restituisce:**
com.aspose.slides.IImage[] - oggetti IImage.

### getImages(IRenderingOptions options, float scaleX, float scaleY) {#getImages-com.aspose.slides.IRenderingOptions-float-float-}
```
public abstract IImage[] getImages(IRenderingOptions options, float scaleX, float scaleY)
```

Restituisce oggetti Image Thumbnail per tutte le diapositive di una presentazione con scala personalizzata.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Opzioni di rendering. |
| scaleX | float | Valore di scala sull'asse x. |
| scaleY | float | Valore di scala sull'asse y. |

**Restituisce:**
com.aspose.slides.IImage[] - oggetti Bitmap.

### getImages(IRenderingOptions options, int[] slides, float scaleX, float scaleY) {#getImages-com.aspose.slides.IRenderingOptions-int---float-float-}
```
public abstract IImage[] getImages(IRenderingOptions options, int[] slides, float scaleX, float scaleY)
```

Restituisce oggetti Image Thumbnail per le diapositive specificate di una presentazione con scala personalizzata.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Opzioni di rendering. |
| slides | int[] | Array con le posizioni delle diapositive, a partire da 1. |
| scaleX | float | Valore di scala sull'asse x. |
| scaleY | float | Valore di scala sull'asse y. |

**Restituisce:**
com.aspose.slides.IImage[] - oggetti IImage.

### getImages(IRenderingOptions options, Size imageSize) {#getImages-com.aspose.slides.IRenderingOptions-com.aspose.slides.android.Size-}
```
public abstract IImage[] getImages(IRenderingOptions options, Size imageSize)
```

Restituisce oggetti Image Thumbnail per tutte le diapositive di una presentazione con dimensione specificata.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Opzioni di rendering. |
| imageSize | [Size](../../com.aspose.slides.android/size) | Dimensione dell'immagine da creare. |

**Restituisce:**
com.aspose.slides.IImage[] - oggetti IImage.

### getImages(IRenderingOptions options, int[] slides, Size imageSize) {#getImages-com.aspose.slides.IRenderingOptions-int---com.aspose.slides.android.Size-}
```
public abstract IImage[] getImages(IRenderingOptions options, int[] slides, Size imageSize)
```

Restituisce oggetti Image Thumbnail per le diapositive specificate di una presentazione con dimensione specificata.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Opzioni di rendering. |
| slides | int[] | Array con le posizioni delle diapositive, a partire da 1. |
| imageSize | [Size](../../com.aspose.slides.android/size) | Dimensione dell'immagine da creare. |

**Restituisce:**
com.aspose.slides.IImage[] - oggetti IImage.

### getSlideById(long id) {#getSlideById-long-}
```
public abstract IBaseSlide getSlideById(long id)
```

Restituisce una Slide, MasterSlide o LayoutSlide per Id.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| id | long | Id di una diapositiva. |

**Restituisce:**
[IBaseSlide](../../com.aspose.slides/ibaseslide) - oggetto IBaseSlide.

### joinPortionsWithSameFormatting() {#joinPortionsWithSameFormatting--}
```
public abstract void joinPortionsWithSameFormatting()
```

Unisce le porzioni con lo stesso formato in tutti i paragrafi di tutte le forme accettabili in tutte le diapositive.

### highlightText(String text, Integer highlightColor) {#highlightText-java.lang.String-java.lang.Integer-}
```
public abstract void highlightText(String text, Integer highlightColor)
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
| highlightColor | java.lang.Integer | Il colore per evidenziare il testo. |

### highlightText(String text, Integer highlightColor, ITextSearchOptions options, IFindResultCallback callback) {#highlightText-java.lang.String-java.lang.Integer-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-}
```
public abstract void highlightText(String text, Integer highlightColor, ITextSearchOptions options, IFindResultCallback callback)
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
| highlightColor | java.lang.Integer | Il colore per evidenziare il testo. |
| options | [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions) | Opzioni di ricerca del testo [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions). |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | Oggetto di callback per ricevere i risultati della ricerca [IFindResultCallback](../../com.aspose.slides/ifindresultcallback). |

### highlightRegex(Pattern regex, Integer highlightColor, IFindResultCallback callback) {#highlightRegex-java.util.regex.Pattern-java.lang.Integer-com.aspose.slides.IFindResultCallback-}
```
public abstract void highlightRegex(Pattern regex, Integer highlightColor, IFindResultCallback callback)
```

Evidenzia tutte le corrispondenze dell'espressione regolare con il colore specificato.

--------------------

> ```
> The following code sample shows how to highlight text in a PowerPoint Presentation using a regular expression.
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
| regex | java.util.regex.Pattern | L'espressione regolare java.util.regex.Pattern per ottenere le stringhe da evidenziare. |
| highlightColor | java.lang.Integer | Il colore per evidenziare il testo. |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | Oggetto di callback per ricevere i risultati della ricerca [IFindResultCallback](../../com.aspose.slides/ifindresultcallback). |

### replaceText(String oldText, String newText, ITextSearchOptions options, IFindResultCallback callback) {#replaceText-java.lang.String-java.lang.String-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-}
```
public abstract void replaceText(String oldText, String newText, ITextSearchOptions options, IFindResultCallback callback)
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
| newText | java.lang.String | La stringa che sostituirà tutte le occorrenze di oldText. |
| options | [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions) | Opzioni di ricerca del testo [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions). |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | Oggetto di callback per ricevere i risultati della ricerca [IFindResultCallback](../../com.aspose.slides/ifindresultcallback). |

### replaceRegex(Pattern regex, String newText, IFindResultCallback callback) {#replaceRegex-java.util.regex.Pattern-java.lang.String-com.aspose.slides.IFindResultCallback-}
```
public abstract void replaceRegex(Pattern regex, String newText, IFindResultCallback callback)
```

Sostituisce tutte le corrispondenze dell'espressione regolare con la stringa specificata.

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
| newText | java.lang.String | La stringa che sostituirà tutte le occorrenze delle stringhe da sostituire. |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | Oggetto di callback per ricevere i risultati della ricerca [IFindResultCallback](../../com.aspose.slides/ifindresultcallback). |