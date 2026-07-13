---
title: IPresentation
second_title: Aspose.Slides för Android via Java API-referens
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
| [getProtectionManager()](#getProtectionManager--) | Hämtar hanteraren för behörigheterna för denna presentation. |
| [getSlides()](#getSlides--) | Returnerar en lista med alla bilder som är definierade i presentationen. |
| [getSections()](#getSections--) | Returnerar en lista med alla bildsektioner som är definierade i presentationen. |
| [getSlideSize()](#getSlideSize--) | Returnerar ett objekt för bildstorlek. |
| [getNotesSize()](#getNotesSize--) | Returnerar ett objekt för noteringsbildens storlek. |
| [getLayoutSlides()](#getLayoutSlides--) | Returnerar en lista med alla layoutbilder som är definierade i presentationen. |
| [getMasters()](#getMasters--) | Returnerar en lista med alla masterbilder som är definierade i presentationen. |
| [getMasterNotesSlideManager()](#getMasterNotesSlideManager--) | Returnerar noterings-master-hanteraren. |
| [getMasterHandoutSlideManager()](#getMasterHandoutSlideManager--) | Returnerar handout-master-hanteraren. |
| [getFontsManager()](#getFontsManager--) | Returnerar typsnitts-hanteraren. |
| [getDefaultTextStyle()](#getDefaultTextStyle--) | Returnerar standardtextstil för former. |
| [getCommentAuthors()](#getCommentAuthors--) | Returnerar samlingen av kommentarsförfattare. |
| [getDocumentProperties()](#getDocumentProperties--) | Returnerar ett DocumentProperties-objekt som innehåller standard- och anpassade dokumentegenskaper. |
| [getImages()](#getImages--) | Returnerar samlingen av alla bilder i presentationen. |
| [getAudios()](#getAudios--) | Returnerar samlingen av alla inbäddade ljudfiler i presentationen. |
| [getVideos()](#getVideos--) | Returnerar samlingen av alla inbäddade videofiler i presentationen. |
| [getCustomData()](#getCustomData--) | Returnerar presentationens anpassade data. |
| [getVbaProject()](#getVbaProject--) | Hämtar VBA-projektet med presentationsmakron. |
| [setVbaProject(IVbaProject value)](#setVbaProject-com.aspose.slides.IVbaProject-) | Hämtar VBA-projektet med presentationsmakron. |
| [getSourceFormat()](#getSourceFormat--) | Returnerar information om från vilket format presentationen laddades. |
| [getMasterTheme()](#getMasterTheme--) | Returnerar master-temat för presentationen. |
| [getHyperlinkQueries()](#getHyperlinkQueries--) | Ger enkel åtkomst till alla hyperlänkar som finns i alla presentationsbilder (inte i master-, layout- eller noteringsbilder). |
| [getViewProperties()](#getViewProperties--) | Hämtar presentationsomfattande vy-egenskaper. |
| [getFirstSlideNumber()](#getFirstSlideNumber--) | Representerar det första bildnumret i presentationen. |
| [setFirstSlideNumber(int value)](#setFirstSlideNumber-int-) | Representerar det första bildnumret i presentationen. |
| [getAllCustomXmlParts()](#getAllCustomXmlParts--) | Returnerar alla anpassade datapartier i presentationen. |
| [getDigitalSignatures()](#getDigitalSignatures--) | Returnerar samlingen av signaturer som används för att signera presentationen. |
| [getSensitivityLabels()](#getSensitivityLabels--) | Returnerar samlingen av känslighetsetiketter som tillämpas på presentationsdokumentet. |
| [save(String fname, int format)](#save-java.lang.String-int-) | Sparar alla bilder i en presentation till en fil med angivet format. |
| [save(OutputStream stream, int format)](#save-java.io.OutputStream-int-) | Sparar alla bilder i en presentation till en ström i angivet format. |
| [save(String fname, int format, ISaveOptions options)](#save-java.lang.String-int-com.aspose.slides.ISaveOptions-) | Sparar alla bilder i en presentation till en fil med angivet format och med ytterligare alternativ. |
| [save(OutputStream stream, int format, ISaveOptions options)](#save-java.io.OutputStream-int-com.aspose.slides.ISaveOptions-) | Sparar alla bilder i en presentation till en ström i angivet format och med ytterligare alternativ. |
| [save(String fname, int[] slides, int format)](#save-java.lang.String-int---int-) | Sparar angivna bilder i en presentation till en fil med angivet format. |
| [save(String fname, int[] slides, int format, ISaveOptions options)](#save-java.lang.String-int---int-com.aspose.slides.ISaveOptions-) | Sparar angivna bilder i en presentation till en fil med angivet format. |
| [save(OutputStream stream, int[] slides, int format)](#save-java.io.OutputStream-int---int-) | Sparar angivna bilder i en presentation till en ström i angivet format. |
| [save(OutputStream stream, int[] slides, int format, ISaveOptions options)](#save-java.io.OutputStream-int---int-com.aspose.slides.ISaveOptions-) | Sparar angivna bilder i en presentation till en ström i angivet format. |
| [save(IXamlOptions options)](#save-com.aspose.slides.IXamlOptions-) | Sparar alla bilder i en presentation till en uppsättning filer som representerar XAML-markup. |
| [getImages(IRenderingOptions options)](#getImages-com.aspose.slides.IRenderingOptions-) | Returnerar miniatyrbilds-objekt för alla bilder i en presentation. |
| [getImages(IRenderingOptions options, int[] slides)](#getImages-com.aspose.slides.IRenderingOptions-int---) | Returnerar miniatyr-IImage-objekt för angivna bilder i en presentation. |
| [getImages(IRenderingOptions options, float scaleX, float scaleY)](#getImages-com.aspose.slides.IRenderingOptions-float-float-) | Returnerar miniatyr-bild-objekt för alla bilder i en presentation med anpassad skalning. |
| [getImages(IRenderingOptions options, int[] slides, float scaleX, float scaleY)](#getImages-com.aspose.slides.IRenderingOptions-int---float-float-) | Returnerar miniatyr-bild-objekt för angivna bilder i en presentation med anpassad skalning. |
| [getImages(IRenderingOptions options, Size imageSize)](#getImages-com.aspose.slides.IRenderingOptions-com.aspose.slides.android.Size-) | Returnerar miniatyr-bild-objekt för alla bilder i en presentation med angiven storlek. |
| [getImages(IRenderingOptions options, int[] slides, Size imageSize)](#getImages-com.aspose.slides.IRenderingOptions-int---com.aspose.slides.android.Size-) | Returnerar miniatyr-bild-objekt för angivna bilder i en presentation med angiven storlek. |
| [getSlideById(long id)](#getSlideById-long-) | Returnerar en Slide, MasterSlide eller LayoutSlide med Id. |
| [joinPortionsWithSameFormatting()](#joinPortionsWithSameFormatting--) | Slår ihop körningar med samma formatering i alla stycken i alla godkända former i alla bilder. |
| [highlightText(String text, Integer highlightColor)](#highlightText-java.lang.String-java.lang.Integer-) | Markerar alla träffar av exempeltexten med angiven färg. |
| [highlightText(String text, Integer highlightColor, ITextSearchOptions options, IFindResultCallback callback)](#highlightText-java.lang.String-java.lang.Integer-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-) | Markerar alla träffar av exempeltexten med angiven färg. |
| [highlightRegex(Pattern regex, Integer highlightColor, IFindResultCallback callback)](#highlightRegex-java.util.regex.Pattern-java.lang.Integer-com.aspose.slides.IFindResultCallback-) | Markerar alla träffar av det reguljära uttrycket med angiven färg. |
| [replaceText(String oldText, String newText, ITextSearchOptions options, IFindResultCallback callback)](#replaceText-java.lang.String-java.lang.String-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-) | Ersätter alla förekomster av den angivna texten med en annan angiven text. |
| [replaceRegex(Pattern regex, String newText, IFindResultCallback callback)](#replaceRegex-java.util.regex.Pattern-java.lang.String-com.aspose.slides.IFindResultCallback-) | Ersätter alla träffar av det reguljära uttrycket med den angivna strängen. |

### getCurrentDateTime() {#getCurrentDateTime--}
```
public abstract Date getCurrentDateTime()
```

Returnerar eller anger datum och tid som kommer att ersätta innehållet i datetime-fält. Tid för detta Presentation-objekts skapande som standard. Läs/skriv java.util.Date.

**Returnerar:**
java.util.Date

### setCurrentDateTime(Date value) {#setCurrentDateTime-java.util.Date-}
```
public abstract void setCurrentDateTime(Date value)
```

Returnerar eller anger datum och tid som kommer att ersätta innehållet i datetime-fält. Tid för detta Presentation-objekts skapande som standard. Läs/skriv java.util.Date.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | java.util.Date |  |

### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public abstract IPresentationHeaderFooterManager getHeaderFooterManager()
```

Returnerar HeaderFooter-hanteraren för presentationen. Läs-endast [IPresentationHeaderFooterManager](../../com.aspose.slides/ipresentationheaderfootermanager).

**Returnerar:**
[IPresentationHeaderFooterManager](../../com.aspose.slides/ipresentationheaderfootermanager)

### getProtectionManager() {#getProtectionManager--}
```
public abstract IProtectionManager getProtectionManager()
```

Hämtar hanteraren för behörigheterna för denna presentation. Läs-endast [IProtectionManager](../../com.aspose.slides/iprotectionmanager).

**Returnerar:**
[IProtectionManager](../../com.aspose.slides/iprotectionmanager)

### getSlides() {#getSlides--}
```
public abstract ISlideCollection getSlides()
```

Returnerar en lista med alla bilder som är definierade i presentationen. Läs-endast [ISlideCollection](../../com.aspose.slides/islidecollection).

**Returnerar:**
[ISlideCollection](../../com.aspose.slides/islidecollection)

### getSections() {#getSections--}
```
public abstract ISectionCollection getSections()
```

Returnerar en lista med alla bildsektioner som är definierade i presentationen. Läs-endast [ISectionCollection](../../com.aspose.slides/isectioncollection).

**Returnerar:**
[ISectionCollection](../../com.aspose.slides/isectioncollection)

### getSlideSize() {#getSlideSize--}
```
public abstract ISlideSize getSlideSize()
```

Returnerar ett objekt för bildstorlek. Läs-endast [ISlideSize](../../com.aspose.slides/islidesize).

**Returnerar:**
[ISlideSize](../../com.aspose.slides/islidesize)

### getNotesSize() {#getNotesSize--}
```
public abstract INotesSize getNotesSize()
```

Returnerar ett objekt för noteringsbildens storlek. Läs-endast [INotesSize](../../com.aspose.slides/inotessize).

**Returnerar:**
[INotesSize](../../com.aspose.slides/inotessize)

### getLayoutSlides() {#getLayoutSlides--}
```
public abstract IGlobalLayoutSlideCollection getLayoutSlides()
```

Returnerar en lista med alla layoutbilder som är definierade i presentationen. Läs-endast [IGlobalLayoutSlideCollection](../../com.aspose.slides/igloballayoutslidecollection).

--------------------

Du kan få åtkomst till ett alternativt API för att lägga till/infoga/ta bort/klona layoutbilder genom att använda IMasterSlide.LayoutSlides-egenskapen.

**Returnerar:**
[IGlobalLayoutSlideCollection](../../com.aspose.slides/igloballayoutslidecollection)

### getMasters() {#getMasters--}
```
public abstract IMasterSlideCollection getMasters()
```

Returnerar en lista med alla masterbilder som är definierade i presentationen. Läs-endast [IMasterSlideCollection](../../com.aspose.slides/imasterslidecollection).

**Returnerar:**
[IMasterSlideCollection](../../com.aspose.slides/imasterslidecollection)

### getMasterNotesSlideManager() {#getMasterNotesSlideManager--}
```
public abstract IMasterNotesSlideManager getMasterNotesSlideManager()
```

Returnerar noterings-master-hanteraren. Läs-endast [IMasterNotesSlideManager](../../com.aspose.slides/imasternotesslidemanager).

**Returnerar:**
[IMasterNotesSlideManager](../../com.aspose.slides/imasternotesslidemanager)

### getMasterHandoutSlideManager() {#getMasterHandoutSlideManager--}
```
public abstract IMasterHandoutSlideManager getMasterHandoutSlideManager()
```

Returnerar handout-master-hanteraren. Läs-endast [IMasterHandoutSlideManager](../../com.aspose.slides/imasterhandoutslidemanager).

**Returnerar:**
[IMasterHandoutSlideManager](../../com.aspose.slides/imasterhandoutslidemanager)

### getFontsManager() {#getFontsManager--}
```
public abstract IFontsManager getFontsManager()
```

Returnerar typsnitts-hanteraren. Läs-endast [IFontsManager](../../com.aspose.slides/ifontsmanager).

**Returnerar:**
[IFontsManager](../../com.aspose.slides/ifontsmanager)

### getDefaultTextStyle() {#getDefaultTextStyle--}
```
public abstract ITextStyle getDefaultTextStyle()
```

Returnerar standardtextstil för former. Läs-endast [ITextStyle](../../com.aspose.slides/itextstyle).

**Returnerar:**
[ITextStyle](../../com.aspose.slides/itextstyle)

### getCommentAuthors() {#getCommentAuthors--}
```
public abstract ICommentAuthorCollection getCommentAuthors()
```

Returnerar samlingen av kommentarsförfattare. Läs-endast [ICommentAuthorCollection](../../com.aspose.slides/icommentauthorcollection).

**Returnerar:**
[ICommentAuthorCollection](../../com.aspose.slides/icommentauthorcollection)

### getDocumentProperties() {#getDocumentProperties--}
```
public abstract IDocumentProperties getDocumentProperties()
```

Returnerar ett DocumentProperties-objekt som innehåller standard- och anpassade dokumentegenskaper. Läs-endast [IDocumentProperties](../../com.aspose.slides/idocumentproperties).

**Returnerar:**
[IDocumentProperties](../../com.aspose.slides/idocumentproperties)

### getImages() {#getImages--}
```
public abstract IImageCollection getImages()
```

Returnerar samlingen av alla bilder i presentationen. Läs-endast [IImageCollection](../../com.aspose.slides/iimagecollection).

**Returnerar:**
[IImageCollection](../../com.aspose.slides/iimagecollection)

### getAudios() {#getAudios--}
```
public abstract IAudioCollection getAudios()
```

Returnerar samlingen av alla inbäddade ljudfiler i presentationen. Läs-endast [IAudioCollection](../../com.aspose.slides/iaudiocollection).

**Returnerar:**
[IAudioCollection](../../com.aspose.slides/iaudiocollection)

### getVideos() {#getVideos--}
```
public abstract IVideoCollection getVideos()
```

Returnerar samlingen av alla inbäddade videofiler i presentationen. Läs-endast [IVideoCollection](../../com.aspose.slides/ivideocollection).

**Returnerar:**
[IVideoCollection](../../com.aspose.slides/ivideocollection)

### getCustomData() {#getCustomData--}
```
public abstract ICustomData getCustomData()
```

Returnerar presentationens anpassade data. Läs-endast [ICustomData](../../com.aspose.slides/icustomdata).

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

Returnerar information om från vilket format presentationen laddades. Läs-endast [SourceFormat](../../com.aspose.slides/sourceformat).

**Returnerar:**
int

### getMasterTheme() {#getMasterTheme--}
```
public abstract IMasterTheme getMasterTheme()
```

Returnerar master-temat för presentationen. Läs-endast [IMasterTheme](../../com.aspose.slides/imastertheme).

**Returnerar:**
[IMasterTheme](../../com.aspose.slides/imastertheme)

### getHyperlinkQueries() {#getHyperlinkQueries--}
```
public abstract IHyperlinkQueries getHyperlinkQueries()
```

Ger enkel åtkomst till alla hyperlänkar som finns i alla presentationsbilder (inte i master-, layout- eller noteringsbilder). Läs-endast [IHyperlinkQueries](../../com.aspose.slides/ihyperlinkqueries).

**Returnerar:**
[IHyperlinkQueries](../../com.aspose.slides/ihyperlinkqueries)

### getViewProperties() {#getViewProperties--}
```
public abstract IViewProperties getViewProperties()
```

Hämtar presentationsomfattande vy-egenskaper. Läs-endast [IViewProperties](../../com.aspose.slides/iviewproperties).

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

Returnerar alla anpassade datapartier i presentationen. Läs-endast ICustomXmlPart[].

**Returnerar:**
com.aspose.slides.ICustomXmlPart[]

### getDigitalSignatures() {#getDigitalSignatures--}
```
public abstract IDigitalSignatureCollection getDigitalSignatures()
```

Returnerar samlingen av signaturer som används för att signera presentationen. Läs-endast [IDigitalSignatureCollection](../../com.aspose.slides/idigitalsignaturecollection).

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

Returnerar samlingen av känslighetsetiketter som tillämpas på presentationsdokumentet. Läs-endast [ISensitivityLabelCollection](../../com.aspose.slides/isensitivitylabelcollection).

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
| format | int | Format för den exporterade datan. |

### save(OutputStream stream, int format) {#save-java.io.OutputStream-int-}
```
public abstract void save(OutputStream stream, int format)
```

Sparar alla bilder i en presentation till en ström i angivet format.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| stream | java.io.OutputStream | Utdatastream. |
| format | int | Format för den exporterade datan. |

### save(String fname, int format, ISaveOptions options) {#save-java.lang.String-int-com.aspose.slides.ISaveOptions-}
```
public abstract void save(String fname, int format, ISaveOptions options)
```

Sparar alla bilder i en presentation till en fil med angivet format och med ytterligare alternativ.

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

Sparar alla bilder i en presentation till en ström i angivet format och med ytterligare alternativ.

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

Sparar angivna bilder i en presentation till en fil med angivet format.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fname | java.lang.String | Sökväg till den skapade filen. |
| slides | int[] | Array med bildpositioner, startande från 1. |
| format | int | Format för den exporterade datan. |

### save(String fname, int[] slides, int format, ISaveOptions options) {#save-java.lang.String-int---int-com.aspose.slides.ISaveOptions-}
```
public abstract void save(String fname, int[] slides, int format, ISaveOptions options)
```

Sparar angivna bilder i en presentation till en fil med angivet format.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fname | java.lang.String | Sökväg till den skapade filen. |
| slides | int[] | Array med bildpositioner, startande från 1. |
| format | int | Format för den exporterade datan. |
| options | [ISaveOptions](../../com.aspose.slides/isaveoptions) | Ytterligare formatalternativ. |

### save(OutputStream stream, int[] slides, int format) {#save-java.io.OutputStream-int---int-}
```
public abstract void save(OutputStream stream, int[] slides, int format)
```

Sparar angivna bilder i en presentation till en ström i angivet format.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| stream | java.io.OutputStream | Utdatastream. |
| slides | int[] | Array med bildpositioner, startande från 1. |
| format | int | Format för den exporterade datan. |

### save(OutputStream stream, int[] slides, int format, ISaveOptions options) {#save-java.io.OutputStream-int---int-com.aspose.slides.ISaveOptions-}
```
public abstract void save(OutputStream stream, int[] slides, int format, ISaveOptions options)
```

Sparar angivna bilder i en presentation till en ström i angivet format.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| stream | java.io.OutputStream | Utdatastream. |
| slides | int[] | Array med bildpositioner, startande från 1. |
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
| options | [IXamlOptions](../../com.aspose.slides/ixamloptions) | XAML-formatalternativen. |

### getImages(IRenderingOptions options) {#getImages-com.aspose.slides.IRenderingOptions-}
```
public abstract IImage[] getImages(IRenderingOptions options)
```

Returnerar miniatyrbilds-objekt för alla bilder i en presentation.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Rendering-alternativ. |

**Returnerar:**
com.aspose.slides.IImage[] - IImage-objekt.

### getImages(IRenderingOptions options, int[] slides) {#getImages-com.aspose.slides.IRenderingOptions-int---}
```
public abstract IImage[] getImages(IRenderingOptions options, int[] slides)
```

Returnerar miniatyr-IImage-objekt för angivna bilder i en presentation.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Rendering-alternativ. |
| slides | int[] | Array med bildpositioner, startande från 1. |

**Returnerar:**
com.aspose.slides.IImage[] - IImage-objekt.

### getImages(IRenderingOptions options, float scaleX, float scaleY) {#getImages-com.aspose.slides.IRenderingOptions-float-float-}
```
public abstract IImage[] getImages(IRenderingOptions options, float scaleX, float scaleY)
```

Returnerar miniatyr-bild-objekt för alla bilder i en presentation med anpassad skalning.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Rendering-alternativ. |
| scaleX | float | Värdet för att skala miniatyren i x-axelriktning. |
| scaleY | float | Värdet för att skala miniatyren i y-axelriktning. |

**Returnerar:**
com.aspose.slides.IImage[] - Bitmap-objekt.

### getImages(IRenderingOptions options, int[] slides, float scaleX, float scaleY) {#getImages-com.aspose.slides.IRenderingOptions-int---float-float-}
```
public abstract IImage[] getImages(IRenderingOptions options, int[] slides, float scaleX, float scaleY)
```

Returnerar miniatyr-bild-objekt för angivna bilder i en presentation med anpassad skalning.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Rendering-alternativ. |
| slides | int[] | Array med bildpositioner, startande från 1. |
| scaleX | float | Värdet för att skala miniatyren i x-axelriktning. |
| scaleY | float | Värdet för att skala miniatyren i y-axelriktning. |

**Returnerar:**
com.aspose.slides.IImage[] - IImage-objekt.

### getImages(IRenderingOptions options, Size imageSize) {#getImages-com.aspose.slides.IRenderingOptions-com.aspose.slides.android.Size-}
```
public abstract IImage[] getImages(IRenderingOptions options, Size imageSize)
```

Returnerar miniatyr-bild-objekt för alla bilder i en presentation med angiven storlek.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Rendering-alternativ. |
| imageSize | [Size](../../com.aspose.slides.android/size) | Storleken på bilden som ska skapas. |

**Returnerar:**
com.aspose.slides.IImage[] - IImage-objekt.

### getImages(IRenderingOptions options, int[] slides, Size imageSize) {#getImages-com.aspose.slides.IRenderingOptions-int---com.aspose.slides.android.Size-}
```
public abstract IImage[] getImages(IRenderingOptions options, int[] slides, Size imageSize)
```

Returnerar miniatyr-bild-objekt för angivna bilder i en presentation med angiven storlek.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Rendering-alternativ. |
| slides | int[] | Array med bildpositioner, startande från 1. |
| imageSize | [Size](../../com.aspose.slides.android/size) | Storleken på bilden som ska skapas. |

**Returnerar:**
com.aspose.slides.IImage[] - IImage-objekt.

### getSlideById(long id) {#getSlideById-long-}
```
public abstract IBaseSlide getSlideById(long id)
```

Returnerar en Slide, MasterSlide eller LayoutSlide med Id.

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

### highlightText(String text, Integer highlightColor) {#highlightText-java.lang.String-java.lang.Integer-}
```
public abstract void highlightText(String text, Integer highlightColor)
```

Markerar alla träffar av exempeltexten med angiven färg.

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

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| text | java.lang.String | Texten att markera. |
| highlightColor | java.lang.Integer | Färgen att markera texten med. |

### highlightText(String text, Integer highlightColor, ITextSearchOptions options, IFindResultCallback callback) {#highlightText-java.lang.String-java.lang.Integer-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-}
```
public abstract void highlightText(String text, Integer highlightColor, ITextSearchOptions options, IFindResultCallback callback)
```

Markerar alla träffar av exempeltexten med angiven färg.

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

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| text | java.lang.String | Texten att markera. |
| highlightColor | java.lang.Integer | Färgen att markera texten med. |
| options | [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions) | Textsökningsalternativ [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions). |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | Callback-objektet för att ta emot sökresultat [IFindResultCallback](../../com.aspose.slides/ifindresultcallback). |

### highlightRegex(Pattern regex, Integer highlightColor, IFindResultCallback callback) {#highlightRegex-java.util.regex.Pattern-java.lang.Integer-com.aspose.slides.IFindResultCallback-}
```
public abstract void highlightRegex(Pattern regex, Integer highlightColor, IFindResultCallback callback)
```

Markerar alla träffar av det reguljära uttrycket med angiven färg.

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

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| regex | java.util.regex.Pattern | Det reguljära uttrycket java.util.regex.Pattern för att hämta strängar att markera. |
| highlightColor | java.lang.Integer | Färgen att markera texten med. |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | Callback-objektet för att ta emot sökresultat [IFindResultCallback](../../com.aspose.slides/ifindresultcallback). |

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
>      // Replace all separate 'the' occurrences with '***'
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
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | Callback-objektet för att ta emot sökresultat [IFindResultCallback](../../com.aspose.slides/ifindresultcallback). |

### replaceRegex(Pattern regex, String newText, IFindResultCallback callback) {#replaceRegex-java.util.regex.Pattern-java.lang.String-com.aspose.slides.IFindResultCallback-}
```
public abstract void replaceRegex(Pattern regex, String newText, IFindResultCallback callback)
```

Ersätter alla träffar av det reguljära uttrycket med den angivna strängen.

--------------------

> ```
> The following code sample shows how to replace text using regular expression with the specified string.
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

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| regex | java.util.regex.Pattern | Det reguljära uttrycket java.util.regex.Pattern för att hämta strängar att ersätta. |
| newText | java.lang.String | Strängen som ersätter alla förekomster av strängarna som ska ersättas. |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | Callback-objektet för att ta emot sökresultat [IFindResultCallback](../../com.aspose.slides/ifindresultcallback). |