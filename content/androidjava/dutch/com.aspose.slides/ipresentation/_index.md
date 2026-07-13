---
title: IPresentation
second_title: Aspose.Slides voor Android via Java API Referentie
description: Presentatiedocument
type: docs
url: /nl/com.aspose.slides/ipresentation/
---
**Alle geïmplementeerde interfaces:**
[com.aspose.slides.IPresentationComponent](../../com.aspose.slides/ipresentationcomponent), com.aspose.ms.System.IDisposable
```
public interface IPresentation extends IPresentationComponent, System.IDisposable
```

Presentatiedocument
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getCurrentDateTime()](#getCurrentDateTime--) | Retourneert of stelt datum en tijd in die de inhoud van datetime-velden zal vervangen. |
| [setCurrentDateTime(Date value)](#setCurrentDateTime-java.util.Date-) | Retourneert of stelt datum en tijd in die de inhoud van datetime-velden zal vervangen. |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | Retourneert de HeaderFooter-beheerder van de presentatie. |
| [getProtectionManager()](#getProtectionManager--) | Haalt de beheerder van de machtigingen voor deze presentatie op. |
| [getSlides()](#getSlides--) | Retourneert een lijst van alle dia's die in de presentatie zijn gedefinieerd. |
| [getSections()](#getSections--) | Retourneert een lijst van alle secties van dia's die in de presentatie zijn gedefinieerd. |
| [getSlideSize()](#getSlideSize--) | Retourneert een slide-grootte-object. |
| [getNotesSize()](#getNotesSize--) | Retourneert een notitie-slide-grootte-object. |
| [getLayoutSlides()](#getLayoutSlides--) | Retourneert een lijst van alle lay-outdia's die in de presentatie zijn gedefinieerd. |
| [getMasters()](#getMasters--) | Retourneert een lijst van alle masterdia's die in de presentatie zijn gedefinieerd. |
| [getMasterNotesSlideManager()](#getMasterNotesSlideManager--) | Retourneert de notitie-masterbeheerder. |
| [getMasterHandoutSlideManager()](#getMasterHandoutSlideManager--) | Retourneert de hand-out masterbeheerder. |
| [getFontsManager()](#getFontsManager--) | Retourneert de lettertypebeheerder. |
| [getDefaultTextStyle()](#getDefaultTextStyle--) | Retourneert de standaard tekststijl voor vormen. |
| [getCommentAuthors()](#getCommentAuthors--) | Retourneert de collectie van commentaarauteurs. |
| [getDocumentProperties()](#getDocumentProperties--) | Retourneert een DocumentProperties-object dat standaard- en aangepaste documenteigenschappen bevat. |
| [getImages()](#getImages--) | Retourneert de collectie van alle afbeeldingen in de presentatie. |
| [getAudios()](#getAudios--) | Retourneert de collectie van alle ingesloten audiobestanden in de presentatie. |
| [getVideos()](#getVideos--) | Retourneert de collectie van alle ingesloten videobestanden in de presentatie. |
| [getCustomData()](#getCustomData--) | Retourneert de aangepaste gegevens van de presentatie. |
| [getVbaProject()](#getVbaProject--) | Haalt het VBA-project met presentatie-macro's op. |
| [setVbaProject(IVbaProject value)](#setVbaProject-com.aspose.slides.IVbaProject-) | Haalt het VBA-project met presentatie-macro's op. |
| [getSourceFormat()](#getSourceFormat--) | Retourneert informatie over het formaat waarmee de presentatie is geladen. |
| [getMasterTheme()](#getMasterTheme--) | Retourneert het master-thema van de presentatie. |
| [getHyperlinkQueries()](#getHyperlinkQueries--) | Biedt gemakkelijke toegang tot alle hyperlinks die in alle presentatiedia's zitten (niet in master-, lay-out- of notitiedia's). |
| [getViewProperties()](#getViewProperties--) | Haalt de weergave-eigenschappen voor de gehele presentatie op. |
| [getFirstSlideNumber()](#getFirstSlideNumber--) | Stelt het eerste dia-nummer in de presentatie voor. |
| [setFirstSlideNumber(int value)](#setFirstSlideNumber-int-) | Stelt het eerste dia-nummer in de presentatie voor. |
| [getAllCustomXmlParts()](#getAllCustomXmlParts--) | Retourneert alle aangepaste gegevensonderdelen in de presentatie. |
| [getDigitalSignatures()](#getDigitalSignatures--) | Retourneert de collectie van handtekeningen die gebruikt zijn om de presentatie te ondertekenen. |
| [getSensitivityLabels()](#getSensitivityLabels--) | Retourneert de collectie van gevoeligheidslabels die op het presentatiedocument zijn toegepast. |
| [save(String fname, int format)](#save-java.lang.String-int-) | Slaat alle dia's van een presentatie op in een bestand met het opgegeven formaat. |
| [save(OutputStream stream, int format)](#save-java.io.OutputStream-int-) | Slaat alle dia's van een presentatie op in een stroom in het opgegeven formaat. |
| [save(String fname, int format, ISaveOptions options)](#save-java.lang.String-int-com.aspose.slides.ISaveOptions-) | Slaat alle dia's van een presentatie op in een bestand met het opgegeven formaat en met extra opties. |
| [save(OutputStream stream, int format, ISaveOptions options)](#save-java.io.OutputStream-int-com.aspose.slides.ISaveOptions-) | Slaat alle dia's van een presentatie op in een stroom in het opgegeven formaat en met extra opties. |
| [save(String fname, int[] slides, int format)](#save-java.lang.String-int---int-) | Slaat opgegeven dia's van een presentatie op in een bestand met het opgegeven formaat. |
| [save(String fname, int[] slides, int format, ISaveOptions options)](#save-java.lang.String-int---int-com.aspose.slides.ISaveOptions-) | Slaat opgegeven dia's van een presentatie op in een bestand met het opgegeven formaat. |
| [save(OutputStream stream, int[] slides, int format)](#save-java.io.OutputStream-int---int-) | Slaat opgegeven dia's van een presentatie op in een stroom in het opgegeven formaat. |
| [save(OutputStream stream, int[] slides, int format, ISaveOptions options)](#save-java.io.OutputStream-int---int-com.aspose.slides.ISaveOptions-) | Slaat opgegeven dia's van een presentatie op in een stroom in het opgegeven formaat. |
| [save(IXamlOptions options)](#save-com.aspose.slides.IXamlOptions-) | Slaat alle dia's van een presentatie op in een reeks bestanden die XAML-markup representeren. |
| [getImages(IRenderingOptions options)](#getImages-com.aspose.slides.IRenderingOptions-) | Retourneert miniatuur-afbeeldingsobjecten voor alle dia's van een presentatie. |
| [getImages(IRenderingOptions options, int[] slides)](#getImages-com.aspose.slides.IRenderingOptions-int---) | Retourneert miniatuur-IImage-objecten voor opgegeven dia's van een presentatie. |
| [getImages(IRenderingOptions options, float scaleX, float scaleY)](#getImages-com.aspose.slides.IRenderingOptions-float-float-) | Retourneert miniatuur-afbeeldingsobjecten voor alle dia's van een presentatie met aangepaste schaal. |
| [getImages(IRenderingOptions options, int[] slides, float scaleX, float scaleY)](#getImages-com.aspose.slides.IRenderingOptions-int---float-float-) | Retourneert miniatuur-afbeeldingsobjecten voor opgegeven dia's van een presentatie met aangepaste schaal. |
| [getImages(IRenderingOptions options, Size imageSize)](#getImages-com.aspose.slides.IRenderingOptions-com.aspose.slides.android.Size-) | Retourneert miniatuur-afbeeldingsobjecten voor alle dia's van een presentatie met opgegeven grootte. |
| [getImages(IRenderingOptions options, int[] slides, Size imageSize)](#getImages-com.aspose.slides.IRenderingOptions-int---com.aspose.slides.android.Size-) | Retourneert miniatuur-afbeeldingsobjecten voor opgegeven dia's van een presentatie met opgegeven grootte. |
| [getSlideById(long id)](#getSlideById-long-) | Retourneert een Slide, MasterSlide of LayoutSlide op Id. |
| [joinPortionsWithSameFormatting()](#joinPortionsWithSameFormatting--) | Voegt runs met dezelfde opmaak samen in alle alinea's in alle acceptabele vormen in alle dia's. |
| [highlightText(String text, Integer highlightColor)](#highlightText-java.lang.String-java.lang.Integer-) | Markeert alle overeenkomsten van de voorbeeldtekst met de opgegeven kleur. |
| [highlightText(String text, Integer highlightColor, ITextSearchOptions options, IFindResultCallback callback)](#highlightText-java.lang.String-java.lang.Integer-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-) | Markeert alle overeenkomsten van de voorbeeldtekst met de opgegeven kleur. |
| [highlightRegex(Pattern regex, Integer highlightColor, IFindResultCallback callback)](#highlightRegex-java.util.regex.Pattern-java.lang.Integer-com.aspose.slides.IFindResultCallback-) | Markeert alle overeenkomsten van de reguliere expressie met de opgegeven kleur. |
| [replaceText(String oldText, String newText, ITextSearchOptions options, IFindResultCallback callback)](#replaceText-java.lang.String-java.lang.String-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-) | Vervangt alle voorkomens van de opgegeven tekst door een andere opgegeven tekst. |
| [replaceRegex(Pattern regex, String newText, IFindResultCallback callback)](#replaceRegex-java.util.regex.Pattern-java.lang.String-com.aspose.slides.IFindResultCallback-) | Vervangt alle overeenkomsten van de reguliere expressie door de opgegeven tekenreeks. |

### getCurrentDateTime() {#getCurrentDateTime--}
```
public abstract Date getCurrentDateTime()
```

Retourneert of stelt datum en tijd in die de inhoud van datetime-velden zal vervangen. Tijd van de creatie van dit Presentation-object standaard. Lezen/Schrijven java.util.Date.

**Returns:**
java.util.Date

### setCurrentDateTime(Date value) {#setCurrentDateTime-java.util.Date-}
```
public abstract void setCurrentDateTime(Date value)
```

Retourneert of stelt datum en tijd in die de inhoud van datetime-velden zal vervangen. Tijd van de creatie van dit Presentation-object standaard. Lezen/Schrijven java.util.Date.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.util.Date |  |

### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public abstract IPresentationHeaderFooterManager getHeaderFooterManager()
```

Retourneert de HeaderFooter-beheerder van de presentatie. Alleen-lezen [IPresentationHeaderFooterManager](../../com.aspose.slides/ipresentationheaderfootermanager).

**Returns:**
[IPresentationHeaderFooterManager](../../com.aspose.slides/ipresentationheaderfootermanager)

### getProtectionManager() {#getProtectionManager--}
```
public abstract IProtectionManager getProtectionManager()
```

Haalt de beheerder van de machtigingen voor deze presentatie op. Alleen-lezen [IProtectionManager](../../com.aspose.slides/iprotectionmanager).

**Returns:**
[IProtectionManager](../../com.aspose.slides/iprotectionmanager)

### getSlides() {#getSlides--}
```
public abstract ISlideCollection getSlides()
```

Retourneert een lijst van alle dia's die in de presentatie zijn gedefinieerd. Alleen-lezen [ISlideCollection](../../com.aspose.slides/islidecollection).

**Returns:**
[ISlideCollection](../../com.aspose.slides/islidecollection)

### getSections() {#getSections--}
```
public abstract ISectionCollection getSections()
```

Retourneert een lijst van alle secties van dia's die in de presentatie zijn gedefinieerd. Alleen-lezen [ISectionCollection](../../com.aspose.slides/isectioncollection).

**Returns:**
[ISectionCollection](../../com.aspose.slides/isectioncollection)

### getSlideSize() {#getSlideSize--}
```
public abstract ISlideSize getSlideSize()
```

Retourneert een slide-grootte-object. Alleen-lezen [ISlideSize](../../com.aspose.slides/islidesize).

**Returns:**
[ISlideSize](../../com.aspose.slides/islidesize)

### getNotesSize() {#getNotesSize--}
```
public abstract INotesSize getNotesSize()
```

Retourneert een notitie-slide-grootte-object. Alleen-lezen [INotesSize](../../com.aspose.slides/inotessize).

**Returns:**
[INotesSize](../../com.aspose.slides/inotessize)

### getLayoutSlides() {#getLayoutSlides--}
```
public abstract IGlobalLayoutSlideCollection getLayoutSlides()
```

Retourneert een lijst van alle lay-outdia's die in de presentatie zijn gedefinieerd. Alleen-lezen [IGlobalLayoutSlideCollection](../../com.aspose.slides/igloballayoutslidecollection).

--------------------

U kunt via de eigenschap IMasterSlide.LayoutSlides toegang krijgen tot alternatieve API’s voor het toevoegen/invoegen/verwijderen/kopiëren van lay-outdia's.

**Returns:**
[IGlobalLayoutSlideCollection](../../com.aspose.slides/igloballayoutslidecollection)

### getMasters() {#getMasters--}
```
public abstract IMasterSlideCollection getMasters()
```

Retourneert een lijst van alle masterdia's die in de presentatie zijn gedefinieerd. Alleen-lezen [IMasterSlideCollection](../../com.aspose.slides/imasterslidecollection).

**Returns:**
[IMasterSlideCollection](../../com.aspose.slides/imasterslidecollection)

### getMasterNotesSlideManager() {#getMasterNotesSlideManager--}
```
public abstract IMasterNotesSlideManager getMasterNotesSlideManager()
```

Retourneert de notitie-masterbeheerder. Alleen-lezen [IMasterNotesSlideManager](../../com.aspose.slides/imasternotesslidemanager).

**Returns:**
[IMasterNotesSlideManager](../../com.aspose.slides/imasternotesslidemanager)

### getMasterHandoutSlideManager() {#getMasterHandoutSlideManager--}
```
public abstract IMasterHandoutSlideManager getMasterHandoutSlideManager()
```

Retourneert de hand-out masterbeheerder. Alleen-lezen [IMasterHandoutSlideManager](../../com.aspose.slides/imasterhandoutslidemanager).

**Returns:**
[IMasterHandoutSlideManager](../../com.aspose.slides/imasterhandoutslidemanager)

### getFontsManager() {#getFontsManager--}
```
public abstract IFontsManager getFontsManager()
```

Retourneert de lettertypebeheerder. Alleen-lezen [IFontsManager](../../com.aspose.slides/ifontsmanager).

**Returns:**
[IFontsManager](../../com.aspose.slides/ifontsmanager)

### getDefaultTextStyle() {#getDefaultTextStyle--}
```
public abstract ITextStyle getDefaultTextStyle()
```

Retourneert de standaard tekststijl voor vormen. Alleen-lezen [ITextStyle](../../com.aspose.slides/itextstyle).

**Returns:**
[ITextStyle](../../com.aspose.slides/itextstyle)

### getCommentAuthors() {#getCommentAuthors--}
```
public abstract ICommentAuthorCollection getCommentAuthors()
```

Retourneert de collectie van commentaarauteurs. Alleen-lezen [ICommentAuthorCollection](../../com.aspose.slides/icommentauthorcollection).

**Returns:**
[ICommentAuthorCollection](../../com.aspose.slides/icommentauthorcollection)

### getDocumentProperties() {#getDocumentProperties--}
```
public abstract IDocumentProperties getDocumentProperties()
```

Retourneert een DocumentProperties-object dat standaard- en aangepaste documenteigenschappen bevat. Alleen-lezen [IDocumentProperties](../../com.aspose.slides/idocumentproperties).

**Returns:**
[IDocumentProperties](../../com.aspose.slides/idocumentproperties)

### getImages() {#getImages--}
```
public abstract IImageCollection getImages()
```

Retourneert de collectie van alle afbeeldingen in de presentatie. Alleen-lezen [IImageCollection](../../com.aspose.slides/iimagecollection).

**Returns:**
[IImageCollection](../../com.aspose.slides/iimagecollection)

### getAudios() {#getAudios--}
```
public abstract IAudioCollection getAudios()
```

Retourneert de collectie van alle ingesloten audiobestanden in de presentatie. Alleen-lezen [IAudioCollection](../../com.aspose.slides/iaudiocollection).

**Returns:**
[IAudioCollection](../../com.aspose.slides/iaudiocollection)

### getVideos() {#getVideos--}
```
public abstract IVideoCollection getVideos()
```

Retourneert de collectie van alle ingesloten videobestanden in de presentatie. Alleen-lezen [IVideoCollection](../../com.aspose.slides/ivideocollection).

**Returns:**
[IVideoCollection](../../com.aspose.slides/ivideocollection)

### getCustomData() {#getCustomData--}
```
public abstract ICustomData getCustomData()
```

Retourneert de aangepaste gegevens van de presentatie. Alleen-lezen [ICustomData](../../com.aspose.slides/icustomdata).

**Returns:**
[ICustomData](../../com.aspose.slides/icustomdata)

### getVbaProject() {#getVbaProject--}
```
public abstract IVbaProject getVbaProject()
```

Haalt het VBA-project met presentatie-macro's op. Lezen/Schrijven [IVbaProject](../../com.aspose.slides/ivbaproject).

**Returns:**
[IVbaProject](../../com.aspose.slides/ivbaproject)

### setVbaProject(IVbaProject value) {#setVbaProject-com.aspose.slides.IVbaProject-}
```
public abstract void setVbaProject(IVbaProject value)
```

Haalt het VBA-project met presentatie-macro's op. Lezen/Schrijven [IVbaProject](../../com.aspose.slides/ivbaproject).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IVbaProject](../../com.aspose.slides/ivbaproject) |  |

### getSourceFormat() {#getSourceFormat--}
```
public abstract int getSourceFormat()
```

Retourneert informatie over het formaat waarmee de presentatie is geladen. Alleen-lezen [SourceFormat](../../com.aspose.slides/sourceformat).

**Returns:**
int

### getMasterTheme() {#getMasterTheme--}
```
public abstract IMasterTheme getMasterTheme()
```

Retourneert het master-thema van de presentatie. Alleen-lezen [IMasterTheme](../../com.aspose.slides/imastertheme).

**Returns:**
[IMasterTheme](../../com.aspose.slides/imastertheme)

### getHyperlinkQueries() {#getHyperlinkQueries--}
```
public abstract IHyperlinkQueries getHyperlinkQueries()
```

Biedt gemakkelijke toegang tot alle hyperlinks die in alle presentatiedia's zitten (niet in master-, lay-out- of notitiedia's). Alleen-lezen [IHyperlinkQueries](../../com.aspose.slides/ihyperlinkqueries).

**Returns:**
[IHyperlinkQueries](../../com.aspose.slides/ihyperlinkqueries)

### getViewProperties() {#getViewProperties--}
```
public abstract IViewProperties getViewProperties()
```

Haalt de weergave-eigenschappen voor de gehele presentatie op. Alleen-lezen [IViewProperties](../../com.aspose.slides/iviewproperties).

**Returns:**
[IViewProperties](../../com.aspose.slides/iviewproperties)

### getFirstSlideNumber() {#getFirstSlideNumber--}
```
public abstract int getFirstSlideNumber()
```

Stelt het eerste dia-nummer in de presentatie voor. Lezen/Schrijven int.

**Returns:**
int

### setFirstSlideNumber(int value) {#setFirstSlideNumber-int-}
```
public abstract void setFirstSlideNumber(int value)
```

Stelt het eerste dia-nummer in de presentatie voor. Lezen/Schrijven int.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getAllCustomXmlParts() {#getAllCustomXmlParts--}
```
public abstract ICustomXmlPart[] getAllCustomXmlParts()
```

Retourneert alle aangepaste gegevensonderdelen in de presentatie. Alleen-lezen ICustomXmlPart[].

**Returns:**
com.aspose.slides.ICustomXmlPart[]

### getDigitalSignatures() {#getDigitalSignatures--}
```
public abstract IDigitalSignatureCollection getDigitalSignatures()
```

Retourneert de collectie van handtekeningen die gebruikt zijn om de presentatie te ondertekenen. Alleen-lezen [IDigitalSignatureCollection](../../com.aspose.slides/idigitalsignaturecollection).

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


**Returns:**
[IDigitalSignatureCollection](../../com.aspose.slides/idigitalsignaturecollection)

### getSensitivityLabels() {#getSensitivityLabels--}
```
public abstract ISensitivityLabelCollection getSensitivityLabels()
```

Retourneert de collectie van gevoeligheidslabels die op het presentatiedocument zijn toegepast. Alleen-lezen [ISensitivityLabelCollection](../../com.aspose.slides/isensitivitylabelcollection).

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

**Returns:**
[ISensitivityLabelCollection](../../com.aspose.slides/isensitivitylabelcollection)

### save(String fname, int format) {#save-java.lang.String-int-}
```
public abstract void save(String fname, int format)
```

Slaat alle dia's van een presentatie op in een bestand met het opgegeven formaat.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fname | java.lang.String | Pad naar het te maken bestand. |
| format | int | Formaat van de geëxporteerde gegevens. |

### save(OutputStream stream, int format) {#save-java.io.OutputStream-int-}
```
public abstract void save(OutputStream stream, int format)
```

Slaat alle dia's van een presentatie op in een stroom in het opgegeven formaat.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.OutputStream | Output-stroom. |
| format | int | Formaat van de geëxporteerde gegevens. |

### save(String fname, int format, ISaveOptions options) {#save-java.lang.String-int-com.aspose.slides.ISaveOptions-}
```
public abstract void save(String fname, int format, ISaveOptions options)
```

Slaat alle dia's van een presentatie op in een bestand met het opgegeven formaat en met extra opties.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fname | java.lang.String | Pad naar het te maken bestand. |
| format | int | Formaat van de geëxporteerde gegevens. |
| options | [ISaveOptions](../../com.aspose.slides/isaveoptions) | Extra formaatopties. |

### save(OutputStream stream, int format, ISaveOptions options) {#save-java.io.OutputStream-int-com.aspose.slides.ISaveOptions-}
```
public abstract void save(OutputStream stream, int format, ISaveOptions options)
```

Slaat alle dia's van een presentatie op in een stroom in het opgegeven formaat en met extra opties.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.OutputStream | Output-stroom. |
| format | int | Formaat van de geëxporteerde gegevens. |
| options | [ISaveOptions](../../com.aspose.slides/isaveoptions) | Extra formaatopties. |

### save(String fname, int[] slides, int format) {#save-java.lang.String-int---int-}
```
public abstract void save(String fname, int[] slides, int format)
```

Slaat opgegeven dia's van een presentatie op in een bestand met het opgegeven formaat.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fname | java.lang.String | Pad naar het te maken bestand. |
| slides | int[] | Array met dia-posities, startende bij 1. |
| format | int | Formaat van de geëxporteerde gegevens. |

### save(String fname, int[] slides, int format, ISaveOptions options) {#save-java.lang.String-int---int-com.aspose.slides.ISaveOptions-}
```
public abstract void save(String fname, int[] slides, int format, ISaveOptions options)
```

Slaat opgegeven dia's van een presentatie op in een bestand met het opgegeven formaat.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fname | java.lang.String | Pad naar het te maken bestand. |
| slides | int[] | Array met dia-posities, startende bij 1. |
| format | int | Formaat van de geëxporteerde gegevens. |
| options | [ISaveOptions](../../com.aspose.slides/isaveoptions) | Extra formaatopties. |

### save(OutputStream stream, int[] slides, int format) {#save-java.io.OutputStream-int---int-}
```
public abstract void save(OutputStream stream, int[] slides, int format)
```

Slaat opgegeven dia's van een presentatie op in een stroom in het opgegeven formaat.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.OutputStream | Output-stroom. |
| slides | int[] | Array met dia-posities, startende bij 1. |
| format | int | Formaat van de geëxporteerde gegevens. |

### save(OutputStream stream, int[] slides, int format, ISaveOptions options) {#save-java.io.OutputStream-int---int-com.aspose.slides.ISaveOptions-}
```
public abstract void save(OutputStream stream, int[] slides, int format, ISaveOptions options)
```

Slaat opgegeven dia's van een presentatie op in een stroom in het opgegeven formaat.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.OutputStream | Output-stroom. |
| slides | int[] | Array met dia-posities, startende bij 1. |
| format | int | Formaat van de geëxporteerde gegevens. |
| options | [ISaveOptions](../../com.aspose.slides/isaveoptions) | Extra formaatopties. |

### save(IXamlOptions options) {#save-com.aspose.slides.IXamlOptions-}
```
public abstract void save(IXamlOptions options)
```

Slaat alle dia's van een presentatie op in een reeks bestanden die XAML-markup representeren.

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
| options | [IXamlOptions](../../com.aspose.slides/ixamloptions) | De XAML-formaatopties. |

### getImages(IRenderingOptions options) {#getImages-com.aspose.slides.IRenderingOptions-}
```
public abstract IImage[] getImages(IRenderingOptions options)
```

Retourneert miniatuur-afbeeldingsobjecten voor alle dia's van een presentatie.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Rendering-opties. |

**Returns:**
com.aspose.slides.IImage[] - IImage-objecten.

### getImages(IRenderingOptions options, int[] slides) {#getImages-com.aspose.slides.IRenderingOptions-int---}
```
public abstract IImage[] getImages(IRenderingOptions options, int[] slides)
```

Retourneert miniatuur-IImage-objecten voor opgegeven dia's van een presentatie.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Rendering-opties. |
| slides | int[] | Array met dia-posities, startende bij 1. |

**Returns:**
com.aspose.slides.IImage[] - IImage-objecten.

### getImages(IRenderingOptions options, float scaleX, float scaleY) {#getImages-com.aspose.slides.IRenderingOptions-float-float-}
```
public abstract IImage[] getImages(IRenderingOptions options, float scaleX, float scaleY)
```

Retourneert miniatuur-afbeeldingsobjecten voor alle dia's van een presentatie met aangepaste schaal.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Rendering-opties. |
| scaleX | float | De waarde waarmee de miniatuur in de x-as wordt geschaald. |
| scaleY | float | De waarde waarmee de miniatuur in de y-as wordt geschaald. |

**Returns:**
com.aspose.slides.IImage[] - Bitmap-objecten.

### getImages(IRenderingOptions options, int[] slides, float scaleX, float scaleY) {#getImages-com.aspose.slides.IRenderingOptions-int---float-float-}
```
public abstract IImage[] getImages(IRenderingOptions options, int[] slides, float scaleX, float scaleY)
```

Retourneert miniatuur-afbeeldingsobjecten voor opgegeven dia's van een presentatie met aangepaste schaal.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Rendering-opties. |
| slides | int[] | Array met dia-posities, startende bij 1. |
| scaleX | float | De waarde waarmee de miniatuur in de x-as wordt geschaald. |
| scaleY | float | De waarde waarmee de miniatuur in de y-as wordt geschaald. |

**Returns:**
com.aspose.slides.IImage[] - IImage-objecten.

### getImages(IRenderingOptions options, Size imageSize) {#getImages-com.aspose.slides.IRenderingOptions-com.aspose.slides.android.Size-}
```
public abstract IImage[] getImages(IRenderingOptions options, Size imageSize)
```

Retourneert miniatuur-afbeeldingsobjecten voor alle dia's van een presentatie met opgegeven grootte.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Rendering-opties. |
| imageSize | [Size](../../com.aspose.slides.android/size) | Grootte van de te maken afbeelding. |

**Returns:**
com.aspose.slides.IImage[] - IImage-objecten.

### getImages(IRenderingOptions options, int[] slides, Size imageSize) {#getImages-com.aspose.slides.IRenderingOptions-int---com.aspose.slides.android.Size-}
```
public abstract IImage[] getImages(IRenderingOptions options, int[] slides, Size imageSize)
```

Retourneert miniatuur-afbeeldingsobjecten voor opgegeven dia's van een presentatie met opgegeven grootte.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Rendering-opties. |
| slides | int[] | Array met dia-posities, startende bij 1. |
| imageSize | [Size](../../com.aspose.slides.android/size) | Grootte van de te maken afbeelding. |

**Returns:**
com.aspose.slides.IImage[] - IImage-objecten.

### getSlideById(long id) {#getSlideById-long-}
```
public abstract IBaseSlide getSlideById(long id)
```

Retourneert een Slide, MasterSlide of LayoutSlide op Id.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| id | long | Id van een dia. |

**Returns:**
[IBaseSlide](../../com.aspose.slides/ibaseslide) - IBaseSlide-object.

### joinPortionsWithSameFormatting() {#joinPortionsWithSameFormatting--}
```
public abstract void joinPortionsWithSameFormatting()
```

Voegt runs met dezelfde opmaak samen in alle alinea's in alle acceptabele vormen in alle dia's.

### highlightText(String text, Integer highlightColor) {#highlightText-java.lang.String-java.lang.Integer-}
```
public abstract void highlightText(String text, Integer highlightColor)
```

Markeert alle overeenkomsten van de voorbeeldtekst met de opgegeven kleur.

--------------------

> ```
> The following code sample shows how to highlight text in a PowerPoint presentation.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      // markeren van alle afzonderlijke 'the' voorkomen
>      presentation.highlightText("the", Color.MAGENTA);
>      presentation.save("SomePresentation-out2.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| text | java.lang.String | De te markeren tekst. |
| highlightColor | java.lang.Integer | De kleur waarmee de tekst gemarkeerd wordt. |

### highlightText(String text, Integer highlightColor, ITextSearchOptions options, IFindResultCallback callback) {#highlightText-java.lang.String-java.lang.Integer-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-}
```
public abstract void highlightText(String text, Integer highlightColor, ITextSearchOptions options, IFindResultCallback callback)
```

Markeert alle overeenkomsten van de voorbeeldtekst met de opgegeven kleur.

--------------------

> ```
> The following code sample shows how to highlight text in a PowerPoint presentation.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      // markeren van alle afzonderlijke 'the' voorkomen
>      presentation.highlightText("the", Color.MAGENTA);
>      presentation.save("SomePresentation-out2.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| text | java.lang.String | De te markeren tekst. |
| highlightColor | java.lang.Integer | De kleur waarmee de tekst gemarkeerd wordt. |
| options | [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions) | Tekst-zoekopties [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions). |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | Het callback-object voor het ontvangen van zoekresultaten [IFindResultCallback](../../com.aspose.slides/ifindresultcallback). |

### highlightRegex(Pattern regex, Integer highlightColor, IFindResultCallback callback) {#highlightRegex-java.util.regex.Pattern-java.lang.Integer-com.aspose.slides.IFindResultCallback-}
```
public abstract void highlightRegex(Pattern regex, Integer highlightColor, IFindResultCallback callback)
```

Markeert alle overeenkomsten van de reguliere expressie met de opgegeven kleur.

--------------------

> ```
> The following code sample shows how to highlight text in a PowerPoint Presentation using a regular expression.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      // markeren van alle afzonderlijke 'the' voorkomen
>      presentation.highlightText("the", Color.MAGENTA);
>      presentation.save("SomePresentation-out2.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| regex | java.util.regex.Pattern | De reguliere expressie java.util.regex.Pattern om strings te verkrijgen die gemarkeerd moeten worden. |
| highlightColor | java.lang.Integer | De kleur waarmee de tekst gemarkeerd wordt. |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | Het callback-object voor het ontvangen van zoekresultaten [IFindResultCallback](../../com.aspose.slides/ifindresultcallback). |

### replaceText(String oldText, String newText, ITextSearchOptions options, IFindResultCallback callback) {#replaceText-java.lang.String-java.lang.String-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-}
```
public abstract void replaceText(String oldText, String newText, ITextSearchOptions options, IFindResultCallback callback)
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
>      // Vervang alle afzonderlijke 'the' voorkomen door '***'
>      presentation.replaceText("the", "***", textSearchOptions, null);
>      presentation.save("SomePresentation-out2.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| oldText | java.lang.String | De te vervangen tekenreeks. |
| newText | java.lang.String | De tekenreeks die alle voorkomens van oldText vervangt. |
| options | [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions) | Tekst-zoekopties [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions). |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | Het callback-object voor het ontvangen van zoekresultaten [IFindResultCallback](../../com.aspose.slides/ifindresultcallback). |

### replaceRegex(Pattern regex, String newText, IFindResultCallback callback) {#replaceRegex-java.util.regex.Pattern-java.lang.String-com.aspose.slides.IFindResultCallback-}
```
public abstract void replaceRegex(Pattern regex, String newText, IFindResultCallback callback)
```

Vervangt alle overeenkomsten van de reguliere expressie door de opgegeven tekenreeks.

--------------------

> ```
> The following code sample shows how to replace one specified string with another specified string.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx")
>  try {
>      TextSearchOptions textSearchOptions = new TextSearchOptions();
>      textSearchOptions.setWholeWordsOnly(true);
>      // Vervang alle afzonderlijke 'the' voorkomen door '***'
>      presentation.replaceText("the", "***", textSearchOptions, null);
>      presentation.save("SomePresentation-out2.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| regex | java.util.regex.Pattern | De reguliere expressie java.util.regex.Pattern om strings te verkrijgen die vervangen moeten worden. |
| newText | java.lang.String | De tekenreeks die alle voorkomens van de te vervangen strings vervangt. |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | Het callback-object voor het ontvangen van zoekresultaten [IFindResultCallback](../../com.aspose.slides/ifindresultcallback). |