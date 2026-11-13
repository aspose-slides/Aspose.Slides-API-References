---
title: IPresentation
second_title: Aspose.Slides för Java API-referens
description: Presentationsdokument
type: docs
url: /sv/com.aspose.slides/ipresentation/
---
**Alla implementerade gränssnitt:**
[com.aspose.slides.IPresentationComponent](../../com.aspose.slides/ipresentationcomponent), com.aspose.ms.System.IDisposable
```
public interface IPresentation extends IPresentationComponent, System.IDisposable
```

Presentationsdokument
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getCurrentDateTime()](#getCurrentDateTime--) | Returnerar eller anger datum och tid som kommer att ersätta innehållet i datetime-fält. |
| [setCurrentDateTime(Date value)](#setCurrentDateTime-java.util.Date-) | Returnerar eller anger datum och tid som kommer att ersätta innehållet i datetime-fält. |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | Returnerar HeaderFooter-hanteraren för presentationen. |
| [getProtectionManager()](#getProtectionManager--) | Hämtar hanteraren för behörigheter för denna presentation. |
| [getSlides()](#getSlides--) | Returnerar en lista med alla bilder som är definierade i presentationen. |
| [getSections()](#getSections--) | Returnerar en lista med alla bildsektioner som är definierade i presentationen. |
| [getSlideSize()](#getSlideSize--) | Returnerar bildstorleksobjekt. |
| [getNotesSize()](#getNotesSize--) | Returnerar anteckningsbildens storleksobjekt. |
| [getLayoutSlides()](#getLayoutSlides--) | Returnerar en lista med alla layoutbilder som är definierade i presentationen. |
| [getMasters()](#getMasters--) | Returnerar en lista med alla masterbilder som är definierade i presentationen. |
| [getMasterNotesSlideManager()](#getMasterNotesSlideManager--) | Returnerar manager för antecknings-master. |
| [getMasterHandoutSlideManager()](#getMasterHandoutSlideManager--) | Returnerar manager för handout-master. |
| [getFontsManager()](#getFontsManager--) | Returnerar manager för typsnitt. |
| [getDefaultTextStyle()](#getDefaultTextStyle--) | Returnerar standardtextstil för former. |
| [getCommentAuthors()](#getCommentAuthors--) | Returnerar samlingen av kommentarautörer. |
| [getDocumentProperties()](#getDocumentProperties--) | Returnerar DocumentProperties-objektet som innehåller standard- och anpassade dokumentegenskaper. |
| [getImages()](#getImages--) | Returnerar samlingen av alla bilder i presentationen. |
| [getAudios()](#getAudios--) | Returnerar samlingen av alla inbäddade ljudfiler i presentationen. |
| [getVideos()](#getVideos--) | Returnerar samlingen av alla inbäddade videofiler i presentationen. |
| [getCustomData()](#getCustomData--) | Returnerar presentationens anpassade data. |
| [getVbaProject()](#getVbaProject--) | Hämtar VBA-projektet med presentationsmakron. |
| [setVbaProject(IVbaProject value)](#setVbaProject-com.aspose.slides.IVbaProject-) | Hämtar VBA-projektet med presentationsmakron. |
| [getSourceFormat()](#getSourceFormat--) | Returnerar information om vilket format presentationen laddades från. |
| [getMasterTheme()](#getMasterTheme--) | Returnerar mastertema för presentationen. |
| [getHyperlinkQueries()](#getHyperlinkQueries--) | Ger enkel åtkomst till alla hyperlänkar som finns i alla presentationsbilder (inte i master-, layout- eller anteckningsbilder). |
| [getViewProperties()](#getViewProperties--) | Hämtar presentationsomfattande vyegenskaper. |
| [getFirstSlideNumber()](#getFirstSlideNumber--) | Representerar det första bildnumret i presentationen. |
| [setFirstSlideNumber(int value)](#setFirstSlideNumber-int-) | Representerar det första bildnumret i presentationen. |
| [getAllCustomXmlParts()](#getAllCustomXmlParts--) | Returnerar alla anpassade datapartier i presentationen. |
| [getDigitalSignatures()](#getDigitalSignatures--) | Returnerar samlingen av signaturer som används för att signera presentationen. |
| [getSensitivityLabels()](#getSensitivityLabels--) | Returnerar samlingen av känslighetsetiketter som tillämpats på presentationsdokumentet. |
| [save(String fname, int format)](#save-java.lang.String-int-) | Sparar alla bilder i en presentation till en fil med angivet format. |
| [save(OutputStream stream, int format)](#save-java.io.OutputStream-int-) | Sparar alla bilder i en presentation till en ström i angivet format. |
| [save(String fname, int format, ISaveOptions options)](#save-java.lang.String-int-com.aspose.slides.ISaveOptions-) | Sparar alla bilder i en presentation till en fil med angivet format och med ytterligare alternativ. |
| [save(OutputStream stream, int format, ISaveOptions options)](#save-java.io.OutputStream-int-com.aspose.slides.ISaveOptions-) | Sparar alla bilder i en presentation till en ström i angivet format och med ytterligare alternativ. |
| [save(String fname, int[] slides, int format)](#save-java.lang.String-int---int-) | Sparar angivna bilder i en presentation till en fil med angivet format. |
| [save(String fname, int[] slides, int format, ISaveOptions options)](#save-java.lang.String-int---int-com.aspose.slides.ISaveOptions-) | Sparar angivna bilder i en presentation till en fil med angivet format. |
| [save(OutputStream stream, int[] slides, int format)](#save-java.io.OutputStream-int---int-) | Sparar angivna bilder i en presentation till en ström i angivet format. |
| [save(OutputStream stream, int[] slides, int format, ISaveOptions options)](#save-java.io.OutputStream-int---int-com.aspose.slides.ISaveOptions-) | Sparar angivna bilder i en presentation till en ström i angivet format. |
| [save(IXamlOptions options)](#save-com.aspose.slides.IXamlOptions-) | Sparar alla bilder i en presentation till en uppsättning filer som representerar XAML-markering. |
| [getImages(IRenderingOptions options)](#getImages-com.aspose.slides.IRenderingOptions-) | Returnerar en miniatyrbild för alla bilder i en presentation. |
| [getImages(IRenderingOptions options, int[] slides)](#getImages-com.aspose.slides.IRenderingOptions-int---) | Returnerar en miniatyr-IImage-objekt för angivna bilder i en presentation. |
| [getImages(IRenderingOptions options, float scaleX, float scaleY)](#getImages-com.aspose.slides.IRenderingOptions-float-float-) | Returnerar en miniatyrbild för alla bilder i en presentation med anpassad skalning. |
| [getImages(IRenderingOptions options, int[] slides, float scaleX, float scaleY)](#getImages-com.aspose.slides.IRenderingOptions-int---float-float-) | Returnerar en miniatyrbild för angivna bilder i en presentation med anpassad skalning. |
| [getImages(IRenderingOptions options, Dimension imageSize)](#getImages-com.aspose.slides.IRenderingOptions-java.awt.Dimension-) | Returnerar en miniatyrbild för alla bilder i en presentation med angiven storlek. |
| [getImages(IRenderingOptions options, int[] slides, Dimension imageSize)](#getImages-com.aspose.slides.IRenderingOptions-int---java.awt.Dimension-) | Returnerar en miniatyrbild för angivna bilder i en presentation med angiven storlek. |
| [getSlideById(long id)](#getSlideById-long-) | Returnerar en Slide, MasterSlide eller LayoutSlide efter Id. |
| [joinPortionsWithSameFormatting()](#joinPortionsWithSameFormatting--) | Slår ihop körningar med samma formatering i alla stycken i alla acceptabla former i alla bilder. |
| [highlightText(String text, Color highlightColor)](#highlightText-java.lang.String-java.awt.Color-) | Markerar alla matchningar av provtexten med angiven färg. |
| [highlightText(String text, Color highlightColor, ITextSearchOptions options, IFindResultCallback callback)](#highlightText-java.lang.String-java.awt.Color-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-) | Markerar alla matchningar av provtexten med angiven färg. |
| [highlightRegex(Pattern regex, Color highlightColor, IFindResultCallback callback)](#highlightRegex-java.util.regex.Pattern-java.awt.Color-com.aspose.slides.IFindResultCallback-) | Markerar alla matchningar av reguljära uttrycket med angiven färg. |
| [replaceText(String oldText, String newText, ITextSearchOptions options, IFindResultCallback callback)](#replaceText-java.lang.String-java.lang.String-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-) | Ersätter alla förekomster av den angivna texten med en annan angiven text. |
| [replaceRegex(Pattern regex, String newText, IFindResultCallback callback)](#replaceRegex-java.util.regex.Pattern-java.lang.String-com.aspose.slides.IFindResultCallback-) | Ersätter alla matchningar av reguljära uttrycket med den angivna strängen. |
| [refreshChartsData()](#refreshChartsData--) | Laddar om data för alla diagram i presentationen från deras källarbokföringar. |
| [refreshChartsData(boolean skipFailedCharts)](#refreshChartsData-boolean-) | Laddar om data för alla diagram i presentationen från deras källarbokföringar. |

### getCurrentDateTime() {#getCurrentDateTime--}
```
public abstract Date getCurrentDateTime()
```

Returnerar eller anger datum och tid som kommer att ersätta innehållet i datetime-fält. Tid för skapandet av detta Presentation-objekt som standard. Läs/skriv java.util.Date.

**Returnerar:**
java.util.Date

### setCurrentDateTime(Date value) {#setCurrentDateTime-java.util.Date-}
```
public abstract void setCurrentDateTime(Date value)
```

Returnerar eller anger datum och tid som kommer att ersätta innehållet i datetime-fält. Tid för skapandet av detta Presentation-objekt som standard. Läs/skriv java.util.Date.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | java.util.Date |  |

### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public abstract IPresentationHeaderFooterManager getHeaderFooterManager()
```

Returnerar HeaderFooter-hanteraren för presentationen. Endast läsning [IPresentationHeaderFooterManager](../../com.aspose.slides/ipresentationheaderfootermanager).

**Returnerar:**
[IPresentationHeaderFooterManager](../../com.aspose.slides/ipresentationheaderfootermanager)

### getProtectionManager() {#getProtectionManager--}
```
public abstract IProtectionManager getProtectionManager()
```

Hämtar hanteraren för behörigheter för denna presentation. Endast läsning [IProtectionManager](../../com.aspose.slides/iprotectionmanager).

**Returnerar:**
[IProtectionManager](../../com.aspose.slides/iprotectionmanager)

### getSlides() {#getSlides--}
```
public abstract ISlideCollection getSlides()
```

Returnerar en lista med alla bilder som är definierade i presentationen. Endast läsning [ISlideCollection](../../com.aspose.slides/islidecollection).

**Returnerar:**
[ISlideCollection](../../com.aspose.slides/islidecollection)

### getSections() {#getSections--}
```
public abstract ISectionCollection getSections()
```

Returnerar en lista med alla bildsektioner som är definierade i presentationen. Endast läsning [ISectionCollection](../../com.aspose.slides/isectioncollection).

**Returnerar:**
[ISectionCollection](../../com.aspose.slides/isectioncollection)

### getSlideSize() {#getSlideSize--}
```
public abstract ISlideSize getSlideSize()
```

Returnerar bildstorleksobjekt. Endast läsning [ISlideSize](../../com.aspose.slides/islidesize).

**Returnerar:**
[ISlideSize](../../com.aspose.slides/islidesize)

### getNotesSize() {#getNotesSize--}
```
public abstract INotesSize getNotesSize()
```

Returnerar anteckningsbildens storleksobjekt. Endast läsning [INotesSize](../../com.aspose.slides/inotessize).

**Returnerar:**
[INotesSize](../../com.aspose.slides/inotessize)

### getLayoutSlides() {#getLayoutSlides--}
```
public abstract IGlobalLayoutSlideCollection getLayoutSlides()
```

Returnerar en lista med alla layoutbilder som är definierade i presentationen. Endast läsning [IGlobalLayoutSlideCollection](../../com.aspose.slides/igloballayoutslidecollection).

--------------------

Du kan få tillgång till ett alternativt API för att lägga till/infoga/ta bort/klona layoutbilder via egenskapen IMasterSlide.LayoutSlides.

**Returnerar:**
[IGlobalLayoutSlideCollection](../../com.aspose.slides/igloballayoutslidecollection)

### getMasters() {#getMasters--}
```
public abstract IMasterSlideCollection getMasters()
```

Returnerar en lista med alla masterbilder som är definierade i presentationen. Endast läsning [IMasterSlideCollection](../../com.aspose.slides/imasterslidecollection).

**Returnerar:**
[IMasterSlideCollection](../../com.aspose.slides/imasterslidecollection)

### getMasterNotesSlideManager() {#getMasterNotesSlideManager--}
```
public abstract IMasterNotesSlideManager getMasterNotesSlideManager()
```

Returnerar manager för antecknings-master. Endast läsning [IMasterNotesSlideManager](../../com.aspose.slides/imasternotesslidemanager).

**Returnerar:**
[IMasterNotesSlideManager](../../com.aspose.slides/imasternotesslidemanager)

### getMasterHandoutSlideManager() {#getMasterHandoutSlideManager--}
```
public abstract IMasterHandoutSlideManager getMasterHandoutSlideManager()
```

Returnerar manager för handout-master. Endast läsning [IMasterHandoutSlideManager](../../com.aspose.slides/imasterhandoutslidemanager).

**Returnerar:**
[IMasterHandoutSlideManager](../../com.aspose.slides/imasterhandoutslidemanager)

### getFontsManager() {#getFontsManager--}
```
public abstract IFontsManager getFontsManager()
```

Returnerar manager för typsnitt. Endast läsning [IFontsManager](../../com.aspose.slides/ifontsmanager).

**Returnerar:**
[IFontsManager](../../com.aspose.slides/ifontsmanager)

### getDefaultTextStyle() {#getDefaultTextStyle--}
```
public abstract ITextStyle getDefaultTextStyle()
```

Returnerar standardtextstil för former. Endast läsning [ITextStyle](../../com.aspose.slides/itextstyle).

**Returnerar:**
[ITextStyle](../../com.aspose.slides/itextstyle)

### getCommentAuthors() {#getCommentAuthors--}
```
public abstract ICommentAuthorCollection getCommentAuthors()
```

Returnerar samlingen av kommentarautörer. Endast läsning [ICommentAuthorCollection](../../com.aspose.slides/icommentauthorcollection).

**Returnerar:**
[ICommentAuthorCollection](../../com.aspose.slides/icommentauthorcollection)

### getDocumentProperties() {#getDocumentProperties--}
```
public abstract IDocumentProperties getDocumentProperties()
```

Returnerar DocumentProperties-objektet som innehåller standard- och anpassade dokumentegenskaper. Endast läsning [IDocumentProperties](../../com.aspose.slides/idocumentproperties).

**Returnerar:**
[IDocumentProperties](../../com.aspose.slides/idocumentproperties)

### getImages() {#getImages--}
```
public abstract IImageCollection getImages()
```

Returnerar samlingen av alla bilder i presentationen. Endast läsning [IImageCollection](../../com.aspose.slides/iimagecollection).

**Returnerar:**
[IImageCollection](../../com.aspose.slides/iimagecollection)

### getAudios() {#getAudios--}
```
public abstract IAudioCollection getAudios()
```

Returnerar samlingen av alla inbäddade ljudfiler i presentationen. Endast läsning [IAudioCollection](../../com.aspose.slides/iaudiocollection).

**Returnerar:**
[IAudioCollection](../../com.aspose.slides/iaudiocollection)

### getVideos() {#getVideos--}
```
public abstract IVideoCollection getVideos()
```

Returnerar samlingen av alla inbäddade videofiler i presentationen. Endast läsning [IVideoCollection](../../com.aspose.slides/ivideocollection).

**Returnerar:**
[IVideoCollection](../../com.aspose.slides/ivideocollection)

### getCustomData() {#getCustomData--}
```
public abstract ICustomData getCustomData()
```

Returnerar presentationens anpassade data. Endast läsning [ICustomData](../../com.aspose.slides/icustomdata).

**Returnerar:**
[ICustomData](../../com.aspose.slides/icustomdata)

### getVbaProject() {#getVbaProject--}
```
public abstract IVbaProject getVbaProject()
```

Hämtar VBA-projektet med presentationsmakron. Läs/skriv [IVbaProject](../../com.aspose.slides/ivbaproject).

**Returnerar:**
[IVbaProject](../../com.aspose.slides/ivbaproject)

### setVbaProject(IVbaProject value) {#setVbaProject-com.aspose.slides.IVbaProject-}
```
public abstract void setVbaProject(IVbaProject value)
```

Hämtar VBA-projektet med presentationsmakron. Läs/skriv [IVbaProject](../../com.aspose.slides/ivbaproject).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [IVbaProject](../../com.aspose.slides/ivbaproject) |  |

### getSourceFormat() {#getSourceFormat--}
```
public abstract int getSourceFormat()
```

Returnerar information om vilket format presentationen laddades från. Endast läsning [SourceFormat](../../com.aspose.slides/sourceformat).

**Returnerar:**
int

### getMasterTheme() {#getMasterTheme--}
```
public abstract IMasterTheme getMasterTheme()
```

Returnerar mastertema för presentationen. Endast läsning [IMasterTheme](../../com.aspose.slides/imastertheme).

**Returnerar:**
[IMasterTheme](../../com.aspose.slides/imastertheme)

### getHyperlinkQueries() {#getHyperlinkQueries--}
```
public abstract IHyperlinkQueries getHyperlinkQueries()
```

Ger enkel åtkomst till alla hyperlänkar som finns i alla presentationsbilder (inte i master-, layout- eller anteckningsbilder). Endast läsning [IHyperlinkQueries](../../com.aspose.slides/ihyperlinkqueries).

**Returnerar:**
[IHyperlinkQueries](../../com.aspose.slides/ihyperlinkqueries)

### getViewProperties() {#getViewProperties--}
```
public abstract IViewProperties getViewProperties()
```

Hämtar presentationsomfattande vyegenskaper. Endast läsning [IViewProperties](../../com.aspose.slides/iviewproperties).

**Returnerar:**
[IViewProperties](../../com.aspose.slides/iviewproperties)

### getFirstSlideNumber() {#getFirstSlideNumber--}
```
public abstract int getFirstSlideNumber()
```

Representerar det första bildnumret i presentationen. Läs/skriv int.

**Returnerar:**
int

### setFirstSlideNumber(int value) {#setFirstSlideNumber-int-}
```
public abstract void setFirstSlideNumber(int value)
```

Representerar det första bildnumret i presentationen. Läs/skriv int.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | int |  |

### getAllCustomXmlParts() {#getAllCustomXmlParts--}
```
public abstract ICustomXmlPart[] getAllCustomXmlParts()
```

Returnerar alla anpassade datapartier i presentationen. Endast läsning ICustomXmlPart[].

**Returnerar:**
com.aspose.slides.ICustomXmlPart[]

### getDigitalSignatures() {#getDigitalSignatures--}
```
public abstract IDigitalSignatureCollection getDigitalSignatures()
```

Returnerar samlingen av signaturer som används för att signera presentationen. Endast läsning [IDigitalSignatureCollection](../../com.aspose.slides/idigitalsignaturecollection).

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

**Returnerar:**
[IDigitalSignatureCollection](../../com.aspose.slides/idigitalsignaturecollection)

### getSensitivityLabels() {#getSensitivityLabels--}
```
public abstract ISensitivityLabelCollection getSensitivityLabels()
```

Returnerar samlingen av känslighetsetiketter som tillämpats på presentationsdokumentet. Endast läsning [ISensitivityLabelCollection](../../com.aspose.slides/isensitivitylabelcollection).

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

### save(String fname, int format) {#save-java.lang.String-int-}
```
public abstract void save(String fname, int format)
```

Sparar alla bilder i en presentation till en fil med angivet format.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fname | java.lang.String | Sökväg till den skapade filen. |
| format | int | Format för de exporterade data. |

### save(OutputStream stream, int format) {#save-java.io.OutputStream-int-}
```
public abstract void save(OutputStream stream, int format)
```

Sparar alla bilder i en presentation till en ström i angivet format.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| stream | java.io.OutputStream | Utmatningsström. |
| format | int | Format för de exporterade data. |

### save(String fname, int format, ISaveOptions options) {#save-java.lang.String-int-com.aspose.slides.ISaveOptions-}
```
public abstract void save(String fname, int format, ISaveOptions options)
```
Sparar alla bilder i en presentation till en fil med det angivna formatet och med ytterligare alternativ.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fname | java.lang.String | Sökväg till den skapade filen. |
| format | int | Format för den exporterade datan. |
| options | [ISaveOptions](../../com.aspose.slides/isaveoptions) | Ytterligare formatalternativ. |

### save(OutputStream stream, int format, ISaveOptions options) {#save-java.io.OutputStream-int-com.aspose.slides.ISaveOptions-}
```
public abstract void save(OutputStream stream, int format, ISaveOptions options)
```

Sparar alla bilder i en presentation till en ström i det angivna formatet och med ytterligare alternativ.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| stream | java.io.OutputStream | Utdatastream. |
| format | int | Format för den exporterade datan. |
| options | [ISaveOptions](../../com.aspose.slides/isaveoptions) | Ytterligare formatalternativ. |

### save(String fname, int[] slides, int format) {#save-java.lang.String-int---int-}
```
public abstract void save(String fname, int[] slides, int format)
```

Sparar angivna bilder i en presentation till en fil med det angivna formatet.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fname | java.lang.String | Sökväg till den skapade filen. |
| slides | int[] | Array med bildpositioner, med början från 1. |
| format | int | Format för den exporterade datan. |

### save(String fname, int[] slides, int format, ISaveOptions options) {#save-java.lang.String-int---int-com.aspose.slides.ISaveOptions-}
```
public abstract void save(String fname, int[] slides, int format, ISaveOptions options)
```

Sparar angivna bilder i en presentation till en fil med det angivna formatet.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fname | java.lang.String | Sökväg till den skapade filen. |
| slides | int[] | Array med bildpositioner, med början från 1. |
| format | int | Format för den exporterade datan. |
| options | [ISaveOptions](../../com.aspose.slides/isaveoptions) | Ytterligare formatalternativ. |

### save(OutputStream stream, int[] slides, int format) {#save-java.io.OutputStream-int---int-}
```
public abstract void save(OutputStream stream, int[] slides, int format)
```

Sparar angivna bilder i en presentation till en ström i det angivna formatet.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| stream | java.io.OutputStream | Utdatastream. |
| slides | int[] | Array med bildpositioner, med början från 1. |
| format | int | Format för den exporterade datan. |

### save(OutputStream stream, int[] slides, int format, ISaveOptions options) {#save-java.io.OutputStream-int---int-com.aspose.slides.ISaveOptions-}
```
public abstract void save(OutputStream stream, int[] slides, int format, ISaveOptions options)
```

Sparar angivna bilder i en presentation till en ström i det angivna formatet.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| stream | java.io.OutputStream | Utdatastream. |
| slides | int[] | Array med bildpositioner, med början från 1. |
| format | int | Format för den exporterade datan. |
| options | [ISaveOptions](../../com.aspose.slides/isaveoptions) | Ytterligare formatalternativ. |

### save(IXamlOptions options) {#save-com.aspose.slides.IXamlOptions-}
```
public abstract void save(IXamlOptions options)
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
| options | [IXamlOptions](../../com.aspose.slides/ixamloptions) | XAML-formatalternativ. |

### getImages(IRenderingOptions options) {#getImages-com.aspose.slides.IRenderingOptions-}
```
public abstract IImage[] getImages(IRenderingOptions options)
```

Returnerar Thumbnail Image-objekt för alla bilder i en presentation.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Renderingsalternativ. |

**Returnerar:**
com.aspose.slides.IImage[] - IImage-objekt.

### getImages(IRenderingOptions options, int[] slides) {#getImages-com.aspose.slides.IRenderingOptions-int---}
```
public abstract IImage[] getImages(IRenderingOptions options, int[] slides)
```

Returnerar Thumbnail IImage-objekt för angivna bilder i en presentation.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Renderingsalternativ. |
| slides | int[] | Array med bildpositioner, med början från 1. |

**Returnerar:**
com.aspose.slides.IImage[] - IImage-objekt.

### getImages(IRenderingOptions options, float scaleX, float scaleY) {#getImages-com.aspose.slides.IRenderingOptions-float-float-}
```
public abstract IImage[] getImages(IRenderingOptions options, float scaleX, float scaleY)
```

Returnerar Thumbnail Image-objekt för alla bilder i en presentation med anpassad skalning.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Renderingsalternativ. |
| scaleX | float | Värdet med vilket denna Thumbnail skalas i x-axelns riktning. |
| scaleY | float | Värdet med vilket denna Thumbnail skalas i y-axelns riktning. |

**Returnerar:**
com.aspose.slides.IImage[] - Bitmap-objekt.

### getImages(IRenderingOptions options, int[] slides, float scaleX, float scaleY) {#getImages-com.aspose.slides.IRenderingOptions-int---float-float-}
```
public abstract IImage[] getImages(IRenderingOptions options, int[] slides, float scaleX, float scaleY)
```

Returnerar Thumbnail Image-objekt för angivna bilder i en presentation med anpassad skalning.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Renderingsalternativ. |
| slides | int[] | Array med bildpositioner, med början från 1. |
| scaleX | float | Värdet med vilket denna Thumbnail skalas i x-axelns riktning. |
| scaleY | float | Värdet med vilket denna Thumbnail skalas i y-axelns riktning. |

**Returnerar:**
com.aspose.slides.IImage[] - IImage-objekt.

### getImages(IRenderingOptions options, Dimension imageSize) {#getImages-com.aspose.slides.IRenderingOptions-java.awt.Dimension-}
```
public abstract IImage[] getImages(IRenderingOptions options, Dimension imageSize)
```

Returnerar Thumbnail Image-objekt för alla bilder i en presentation med angiven storlek.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Renderingsalternativ. |
| imageSize | java.awt.Dimension | Storleken på den bild som ska skapas. |

**Returnerar:**
com.aspose.slides.IImage[] - IImage-objekt.

### getImages(IRenderingOptions options, int[] slides, Dimension imageSize) {#getImages-com.aspose.slides.IRenderingOptions-int---java.awt.Dimension-}
```
public abstract IImage[] getImages(IRenderingOptions options, int[] slides, Dimension imageSize)
```

Returnerar Thumbnail Image-objekt för angivna bilder i en presentation med angiven storlek.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Renderingsalternativ. |
| slides | int[] | Array med bildpositioner, med början från 1. |
| imageSize | java.awt.Dimension | Storleken på den bild som ska skapas. |

**Returnerar:**
com.aspose.slides.IImage[] - IImage-objekt.

### getSlideById(long id) {#getSlideById-long-}
```
public abstract IBaseSlide getSlideById(long id)
```

Returnerar en Slide, MasterSlide eller LayoutSlide efter Id.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| id | long | Id för en bild. |

**Returnerar:**
[IBaseSlide](../../com.aspose.slides/ibaseslide) - IBaseSlide-objekt.

### joinPortionsWithSameFormatting() {#joinPortionsWithSameFormatting--}
```
public abstract void joinPortionsWithSameFormatting()
```

Slår ihop körningar med samma formatering i alla stycken i alla godkända former i alla bilder.

### highlightText(String text, Color highlightColor) {#highlightText-java.lang.String-java.awt.Color-}
```
public abstract void highlightText(String text, Color highlightColor)
```

Markerar alla matchningar av exempeltexten med den angivna färgen.

--------------------

> ```
> The following code sample shows how to highlight text in a PowerPoint presentation.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      // markerar alla separata förekomster av 'the'
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
public abstract void highlightText(String text, Color highlightColor, ITextSearchOptions options, IFindResultCallback callback)
```

Markerar alla matchningar av exempeltexten med den angivna färgen.

--------------------

> ```
> The following code sample shows how to highlight text in a PowerPoint presentation.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      // markerar alla separata förekomster av 'the'
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
| options | [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions) | Textsökningsalternativ [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions). |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | Återuppringningsobjektet för att ta emot sökresultat [IFindResultCallback](../../com.aspose.slides/ifindresultcallback). |

### highlightRegex(Pattern regex, Color highlightColor, IFindResultCallback callback) {#highlightRegex-java.util.regex.Pattern-java.awt.Color-com.aspose.slides.IFindResultCallback-}
```
public abstract void highlightRegex(Pattern regex, Color highlightColor, IFindResultCallback callback)
```

Markerar alla matchningar av reguljärt uttryck med den angivna färgen.

--------------------

> ```
> The following code sample shows how to highlight text in a PowerPoint Presentation using a regular expression.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      // markerar alla separata förekomster av 'the'
>      presentation.highlightText("the", Color.MAGENTA);
>      presentation.save("SomePresentation-out2.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| regex | java.util.regex.Pattern | Reguljärt uttryck java.util.regex.Pattern för att hämta strängar att markera. |
| highlightColor | java.awt.Color | Färgen som ska användas för att markera texten. |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | Återuppringningsobjektet för att ta emot sökresultat [IFindResultCallback](../../com.aspose.slides/ifindresultcallback). |

### replaceText(String oldText, String newText, ITextSearchOptions options, IFindResultCallback callback) {#replaceText-java.lang.String-java.lang.String-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-}
```
public abstract void replaceText(String oldText, String newText, ITextSearchOptions options, IFindResultCallback callback)
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
| options | [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions) | Textsökningsalternativ [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions). |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | Återuppringningsobjektet för att ta emot sökresultat [IFindResultCallback](../../com.aspose.slides/ifindresultcallback). |

### replaceRegex(Pattern regex, String newText, IFindResultCallback callback) {#replaceRegex-java.util.regex.Pattern-java.lang.String-com.aspose.slides.IFindResultCallback-}
```
public abstract void replaceRegex(Pattern regex, String newText, IFindResultCallback callback)
```

Ersätter alla matchningar av reguljärt uttryck med den angivna strängen.

--------------------

> ```
> The following code sample shows how to replace text using regular expression with the specified string.
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
| regex | java.util.regex.Pattern | Reguljärt uttryck java.util.regex.Pattern för att hämta strängar att ersätta. |
| newText | java.lang.String | Strängen som ersätter alla förekomster av de strängar som ska ersättas. |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | Återuppringningsobjektet för att ta emot sökresultat [IFindResultCallback](../../com.aspose.slides/ifindresultcallback). |

### refreshChartsData() {#refreshChartsData--}
```
public abstract void refreshChartsData()
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
public abstract void refreshChartsData(boolean skipFailedCharts)
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
| skipFailedCharts | boolean | Anger om uppdateringsprocessen fortsätter när ett diagram misslyckas med att uppdateras. Om true, hoppas diagram som orsakar ett undantag över; annars propageras undantaget. |