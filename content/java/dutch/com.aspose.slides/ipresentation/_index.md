---
title: IPresentation
second_title: Aspose.Slides voor Java API-referentie
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
| [getCurrentDateTime()](#getCurrentDateTime--) | Geeft de datum en tijd terug of stelt deze in die de inhoud van datetime-velden zal vervangen. |
| [setCurrentDateTime(Date value)](#setCurrentDateTime-java.util.Date-) | Geeft de datum en tijd terug of stelt deze in die de inhoud van datetime-velden zal vervangen. |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | Geeft de HeaderFooter-beheerder van de presentatie terug. |
| [getProtectionManager()](#getProtectionManager--) | Krijgt de beheerder van de permissies voor deze presentatie. |
| [getSlides()](#getSlides--) | Geeft een lijst met alle dia's die in de presentatie zijn gedefinieerd. |
| [getSections()](#getSections--) | Geeft een lijst met alle secties van dia's die in de presentatie zijn gedefinieerd. |
| [getSlideSize()](#getSlideSize--) | Geeft een object met de dia-grootte terug. |
| [getNotesSize()](#getNotesSize--) | Geeft een object met de grootte van notitiedia's terug. |
| [getLayoutSlides()](#getLayoutSlides--) | Geeft een lijst met alle lay-outdia's die in de presentatie zijn gedefinieerd. |
| [getMasters()](#getMasters--) | Geeft een lijst met alle masterslides die in de presentatie zijn gedefinieerd. |
| [getMasterNotesSlideManager()](#getMasterNotesSlideManager--) | Geeft de notitie-masterbeheerder terug. |
| [getMasterHandoutSlideManager()](#getMasterHandoutSlideManager--) | Geeft de handout-masterbeheerder terug. |
| [getFontsManager()](#getFontsManager--) | Geeft de lettertype-beheerder terug. |
| [getDefaultTextStyle()](#getDefaultTextStyle--) | Geeft de standaardtekstopmaak voor vormen terug. |
| [getCommentAuthors()](#getCommentAuthors--) | Geeft de verzameling van commenta(auteurs) terug. |
| [getDocumentProperties()](#getDocumentProperties--) | Geeft een DocumentProperties-object terug dat standaard- en aangepaste documenteigenschappen bevat. |
| [getImages()](#getImages--) | Geeft de verzameling van alle afbeeldingen in de presentatie terug. |
| [getAudios()](#getAudios--) | Geeft de verzameling van alle ingesloten audiobestanden in de presentatie terug. |
| [getVideos()](#getVideos--) | Geeft de verzameling van alle ingesloten videobestanden in de presentatie terug. |
| [getCustomData()](#getCustomData--) | Geeft de aangepaste gegevens van de presentatie terug. |
| [getVbaProject()](#getVbaProject--) | Krijgt het VBA-project met presentatiemacro's. |
| [setVbaProject(IVbaProject value)](#setVbaProject-com.aspose.slides.IVbaProject-) | Krijgt het VBA-project met presentatiemacro's. |
| [getSourceFormat()](#getSourceFormat--) | Geeft informatie terug over het formaat waarin de presentatie is geladen. |
| [getMasterTheme()](#getMasterTheme--) | Geeft het master-thema van de presentatie terug. |
| [getHyperlinkQueries()](#getHyperlinkQueries--) | Biedt gemakkelijke toegang tot alle hyperlinks die in alle presentatiedia's voorkomen (niet in master-, lay-out- of notitiedia's). |
| [getViewProperties()](#getViewProperties--) | Krijgt de weergave-eigenschappen voor de volledige presentatie. |
| [getFirstSlideNumber()](#getFirstSlideNumber--) | Stelt het eerste dianummer in de presentatie voor. |
| [setFirstSlideNumber(int value)](#setFirstSlideNumber-int-) | Stelt het eerste dianummer in de presentatie voor. |
| [getAllCustomXmlParts()](#getAllCustomXmlParts--) | Geeft alle aangepaste gegevensonderdelen in de presentie terug. |
| [getDigitalSignatures()](#getDigitalSignatures--) | Geeft de verzameling van ondertekeningen die gebruikt zijn om de presentatie te ondertekenen terug. |
| [getSensitivityLabels()](#getSensitivityLabels--) | Geeft de verzameling van gevoeligheidslabels die op het presentatiedocument zijn toegepast terug. |
| [save(String fname, int format)](#save-java.lang.String-int-) | Slaat alle dia's van een presentatie op in een bestand met het opgegeven formaat. |
| [save(OutputStream stream, int format)](#save-java.io.OutputStream-int-) | Slaat alle dia's van een presentatie op in een stream met het opgegeven formaat. |
| [save(String fname, int format, ISaveOptions options)](#save-java.lang.String-int-com.aspose.slides.ISaveOptions-) | Slaat alle dia's van een presentatie op in een bestand met het opgegeven formaat en met extra opties. |
| [save(OutputStream stream, int format, ISaveOptions options)](#save-java.io.OutputStream-int-com.aspose.slides.ISaveOptions-) | Slaat alle dia's van een presentatie op in een stream met het opgegeven formaat en met extra opties. |
| [save(String fname, int[] slides, int format)](#save-java.lang.String-int---int-) | Slaat opgegeven dia's van een presentatie op in een bestand met het opgegeven formaat. |
| [save(String fname, int[] slides, int format, ISaveOptions options)](#save-java.lang.String-int---int-com.aspose.slides.ISaveOptions-) | Slaat opgegeven dia's van een presentatie op in een bestand met het opgegeven formaat. |
| [save(OutputStream stream, int[] slides, int format)](#save-java.io.OutputStream-int---int-) | Slaat opgegeven dia's van een presentatie op in een stream met het opgegeven formaat. |
| [save(OutputStream stream, int[] slides, int format, ISaveOptions options)](#save-java.io.OutputStream-int---int-com.aspose.slides.ISaveOptions-) | Slaat opgegeven dia's van een presentatie op in een stream met het opgegeven formaat. |
| [save(IXamlOptions options)](#save-com.aspose.slides.IXamlOptions-) | Slaat alle dia's van een presentatie op in een set bestanden die XAML-markup vertegenwoordigen. |
| [getImages(IRenderingOptions options)](#getImages-com.aspose.slides.IRenderingOptions-) | Geeft miniatuur-afbeeldingsobjecten voor alle dia's van een presentatie terug. |
| [getImages(IRenderingOptions options, int[] slides)](#getImages-com.aspose.slides.IRenderingOptions-int---) | Geeft miniatuur-IImage-objecten terug voor opgegeven dia's van een presentatie. |
| [getImages(IRenderingOptions options, float scaleX, float scaleY)](#getImages-com.aspose.slides.IRenderingOptions-float-float-) | Geeft miniatuur-afbeeldingsobjecten voor alle dia's van een presentatie terug met aangepaste schaal. |
| [getImages(IRenderingOptions options, int[] slides, float scaleX, float scaleY)](#getImages-com.aspose.slides.IRenderingOptions-int---float-float-) | Geeft miniatuur-afbeeldingsobjecten terug voor opgegeven dia's van een presentatie met aangepaste schaal. |
| [getImages(IRenderingOptions options, Dimension imageSize)](#getImages-com.aspose.slides.IRenderingOptions-java.awt.Dimension-) | Geeft miniatuur-afbeeldingsobjecten voor alle dia's van een presentatie terug met opgegeven grootte. |
| [getImages(IRenderingOptions options, int[] slides, Dimension imageSize)](#getImages-com.aspose.slides.IRenderingOptions-int---java.awt.Dimension-) | Geeft miniatuur-afbeeldingsobjecten terug voor opgegeven dia's van een presentatie met opgegeven grootte. |
| [getSlideById(long id)](#getSlideById-long-) | Geeft een Slide, MasterSlide of LayoutSlide terug op basis van Id. |
| [joinPortionsWithSameFormatting()](#joinPortionsWithSameFormatting--) | Voegt runs met dezelfde opmaak samen in alle alinea's in alle acceptabele vormen in alle dia's. |
| [highlightText(String text, Color highlightColor)](#highlightText-java.lang.String-java.awt.Color-) | Markeert alle overeenkomsten van de voorbeeldtekst met de opgegeven kleur. |
| [highlightText(String text, Color highlightColor, ITextSearchOptions options, IFindResultCallback callback)](#highlightText-java.lang.String-java.awt.Color-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-) | Markeert alle overeenkomsten van de voorbeeldtekst met de opgegeven kleur. |
| [highlightRegex(Pattern regex, Color highlightColor, IFindResultCallback callback)](#highlightRegex-java.util.regex.Pattern-java.awt.Color-com.aspose.slides.IFindResultCallback-) | Markeert alle overeenkomsten van de reguliere expressie met de opgegeven kleur. |
| [replaceText(String oldText, String newText, ITextSearchOptions options, IFindResultCallback callback)](#replaceText-java.lang.String-java.lang.String-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-) | Vervangt alle voorkomens van de opgegeven tekst door een andere opgegeven tekst. |
| [replaceRegex(Pattern regex, String newText, IFindResultCallback callback)](#replaceRegex-java.util.regex.Pattern-java.lang.String-com.aspose.slides.IFindResultCallback-) | Vervangt alle overeenkomsten van de reguliere expressie door de opgegeven string. |

### getCurrentDateTime() {#getCurrentDateTime--}
```
public abstract Date getCurrentDateTime()
```

Geeft de datum en tijd terug of stelt deze in die de inhoud van datetime-velden zal vervangen. Tijd van creatie van dit Presentation-object standaard. Lezen/Schrijven java.util.Date.

**Retourneert:**
java.util.Date

### setCurrentDateTime(Date value) {#setCurrentDateTime-java.util.Date-}
```
public abstract void setCurrentDateTime(Date value)
```

Geeft de datum en tijd terug of stelt deze in die de inhoud van datetime-velden zal vervangen. Tijd van creatie van dit Presentation-object standaard. Lezen/Schrijven java.util.Date.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | java.util.Date |  |

### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public abstract IPresentationHeaderFooterManager getHeaderFooterManager()
```

Geeft de HeaderFooter-beheerder van de presentatie terug. Alleen-lezen [IPresentationHeaderFooterManager](../../com.aspose.slides/ipresentationheaderfootermanager).

**Retourneert:**
[IPresentationHeaderFooterManager](../../com.aspose.slides/ipresentationheaderfootermanager)

### getProtectionManager() {#getProtectionManager--}
```
public abstract IProtectionManager getProtectionManager()
```

Krijgt de beheerder van de permissies voor deze presentatie. Alleen-lezen [IProtectionManager](../../com.aspose.slides/iprotectionmanager).

**Retourneert:**
[IProtectionManager](../../com.aspose.slides/iprotectionmanager)

### getSlides() {#getSlides--}
```
public abstract ISlideCollection getSlides()
```

Geeft een lijst met alle dia's die in de presentatie zijn gedefinieerd. Alleen-lezen [ISlideCollection](../../com.aspose.slides/islidecollection).

**Retourneert:**
[ISlideCollection](../../com.aspose.slides/islidecollection)

### getSections() {#getSections--}
```
public abstract ISectionCollection getSections()
```

Geeft een lijst met alle secties van dia's die in de presentatie zijn gedefinieerd. Alleen-lezen [ISectionCollection](../../com.aspose.slides/isectioncollection).

**Retourneert:**
[ISectionCollection](../../com.aspose.slides/isectioncollection)

### getSlideSize() {#getSlideSize--}
```
public abstract ISlideSize getSlideSize()
```

Geeft een object met de dia-grootte terug. Alleen-lezen [ISlideSize](../../com.aspose.slides/islidesize).

**Retourneert:**
[ISlideSize](../../com.aspose.slides/islidesize)

### getNotesSize() {#getNotesSize--}
```
public abstract INotesSize getNotesSize()
```

Geeft een object met de grootte van notitiedia's terug. Alleen-lezen [INotesSize](../../com.aspose.slides/inotessize).

**Retourneert:**
[INotesSize](../../com.aspose.slides/inotessize)

### getLayoutSlides() {#getLayoutSlides--}
```
public abstract IGlobalLayoutSlideCollection getLayoutSlides()
```

Geeft een lijst met alle lay-outdia's die in de presentatie zijn gedefinieerd. Alleen-lezen [IGlobalLayoutSlideCollection](../../com.aspose.slides/igloballayoutslidecollection).

--------------------

U kunt alternatieve API gebruiken om lay-outdia's toe te voegen/in te voegen/te verwijderen/kloon door de eigenschap IMasterSlide.LayoutSlides te gebruiken.

**Retourneert:**
[IGlobalLayoutSlideCollection](../../com.aspose.slides/igloballayoutslidecollection)

### getMasters() {#getMasters--}
```
public abstract IMasterSlideCollection getMasters()
```

Geeft een lijst met alle masterslides die in de presentatie zijn gedefinieerd. Alleen-lezen [IMasterSlideCollection](../../com.aspose.slides/imasterslidecollection).

**Retourneert:**
[IMasterSlideCollection](../../com.aspose.slides/imasterslidecollection)

### getMasterNotesSlideManager() {#getMasterNotesSlideManager--}
```
public abstract IMasterNotesSlideManager getMasterNotesSlideManager()
```

Geeft de notitie-masterbeheerder terug. Alleen-lezen [IMasterNotesSlideManager](../../com.aspose.slides/imasternotesslidemanager).

**Retourneert:**
[IMasterNotesSlideManager](../../com.aspose.slides/imasternotesslidemanager)

### getMasterHandoutSlideManager() {#getMasterHandoutSlideManager--}
```
public abstract IMasterHandoutSlideManager getMasterHandoutSlideManager()
```

Geeft de handout-masterbeheerder terug. Alleen-lezen [IMasterHandoutSlideManager](../../com.aspose.slides/imasterhandoutslidemanager).

**Retourneert:**
[IMasterHandoutSlideManager](../../com.aspose.slides/imasterhandoutslidemanager)

### getFontsManager() {#getFontsManager--}
```
public abstract IFontsManager getFontsManager()
```

Geeft de lettertype-beheerder terug. Alleen-lezen [IFontsManager](../../com.aspose.slides/ifontsmanager).

**Retourneert:**
[IFontsManager](../../com.aspose.slides/ifontsmanager)

### getDefaultTextStyle() {#getDefaultTextStyle--}
```
public abstract ITextStyle getDefaultTextStyle()
```

Geeft de standaardtekstopmaak voor vormen terug. Alleen-lezen [ITextStyle](../../com.aspose.slides/itextstyle).

**Retourneert:**
[ITextStyle](../../com.aspose.slides/itextstyle)

### getCommentAuthors() {#getCommentAuthors--}
```
public abstract ICommentAuthorCollection getCommentAuthors()
```

Geeft de verzameling van commenta(auteurs) terug. Alleen-lezen [ICommentAuthorCollection](../../com.aspose.slides/icommentauthorcollection).

**Retourneert:**
[ICommentAuthorCollection](../../com.aspose.slides/icommentauthorcollection)

### getDocumentProperties() {#getDocumentProperties--}
```
public abstract IDocumentProperties getDocumentProperties()
```

Geeft een DocumentProperties-object terug dat standaard- en aangepaste documenteigenschappen bevat. Alleen-lezen [IDocumentProperties](../../com.aspose.slides/idocumentproperties).

**Retourneert:**
[IDocumentProperties](../../com.aspose.slides/idocumentproperties)

### getImages() {#getImages--}
```
public abstract IImageCollection getImages()
```

Geeft de verzameling van alle afbeeldingen in de presentatie terug. Alleen-lezen [IImageCollection](../../com.aspose.slides/iimagecollection).

**Retourneert:**
[IImageCollection](../../com.aspose.slides/iimagecollection)

### getAudios() {#getAudios--}
```
public abstract IAudioCollection getAudios()
```

Geeft de verzameling van alle ingesloten audiobestanden in de presentatie terug. Alleen-lezen [IAudioCollection](../../com.aspose.slides/iaudiocollection).

**Retourneert:**
[IAudioCollection](../../com.aspose.slides/iaudiocollection)

### getVideos() {#getVideos--}
```
public abstract IVideoCollection getVideos()
```

Geeft de verzameling van alle ingesloten videobestanden in de presentatie terug. Alleen-lezen [IVideoCollection](../../com.aspose.slides/ivideocollection).

**Retourneert:**
[IVideoCollection](../../com.aspose.slides/ivideocollection)

### getCustomData() {#getCustomData--}
```
public abstract ICustomData getCustomData()
```

Geeft de aangepaste gegevens van de presentatie terug. Alleen-lezen [ICustomData](../../com.aspose.slides/icustomdata).

**Retourneert:**
[ICustomData](../../com.aspose.slides/icustomdata)

### getVbaProject() {#getVbaProject--}
```
public abstract IVbaProject getVbaProject()
```

Krijgt het VBA-project met presentatiemacro's. Lezen/Schrijven [IVbaProject](../../com.aspose.slides/ivbaproject).

**Retourneert:**
[IVbaProject](../../com.aspose.slides/ivbaproject)

### setVbaProject(IVbaProject value) {#setVbaProject-com.aspose.slides.IVbaProject-}
```
public abstract void setVbaProject(IVbaProject value)
```

Krijgt het VBA-project met presentatiemacro's. Lezen/Schrijven [IVbaProject](../../com.aspose.slides/ivbaproject).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [IVbaProject](../../com.aspose.slides/ivbaproject) |  |

### getSourceFormat() {#getSourceFormat--}
```
public abstract int getSourceFormat()
```

Geeft informatie terug over het formaat waarin de presentatie is geladen. Alleen-lezen [SourceFormat](../../com.aspose.slides/sourceformat).

**Retourneert:**
int

### getMasterTheme() {#getMasterTheme--}
```
public abstract IMasterTheme getMasterTheme()
```

Geeft het master-thema van de presentatie terug. Alleen-lezen [IMasterTheme](../../com.aspose.slides/imastertheme).

**Retourneert:**
[IMasterTheme](../../com.aspose.slides/imastertheme)

### getHyperlinkQueries() {#getHyperlinkQueries--}
```
public abstract IHyperlinkQueries getHyperlinkQueries()
```

Biedt gemakkelijke toegang tot alle hyperlinks die in alle presentatiedia's voorkomen (niet in master-, lay-out- of notitiedia's). Alleen-lezen [IHyperlinkQueries](../../com.aspose.slides/ihyperlinkqueries).

**Retourneert:**
[IHyperlinkQueries](../../com.aspose.slides/ihyperlinkqueries)

### getViewProperties() {#getViewProperties--}
```
public abstract IViewProperties getViewProperties()
```

Krijgt de weergave-eigenschappen voor de volledige presentatie. Alleen-lezen [IViewProperties](../../com.aspose.slides/iviewproperties).

**Retourneert:**
[IViewProperties](../../com.aspose.slides/iviewproperties)

### getFirstSlideNumber() {#getFirstSlideNumber--}
```
public abstract int getFirstSlideNumber()
```

Stelt het eerste dianummer in de presentatie voor. Lezen/Schrijven int.

**Retourneert:**
int

### setFirstSlideNumber(int value) {#setFirstSlideNumber-int-}
```
public abstract void setFirstSlideNumber(int value)
```

Stelt het eerste dianummer in de presentatie voor. Lezen/Schrijven int.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | int |  |

### getAllCustomXmlParts() {#getAllCustomXmlParts--}
```
public abstract ICustomXmlPart[] getAllCustomXmlParts()
```

Geeft alle aangepaste gegevensonderdelen in de presentie terug. Alleen-lezen ICustomXmlPart[].

**Retourneert:**
com.aspose.slides.ICustomXmlPart[]

### getDigitalSignatures() {#getDigitalSignatures--}
```
public abstract IDigitalSignatureCollection getDigitalSignatures()
```

Geeft de verzameling van ondertekeningen die gebruikt zijn om de presentatie te ondertekenen terug. Alleen-lezen [IDigitalSignatureCollection](../../com.aspose.slides/idigitalsignaturecollection).

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


**Retourneert:**
[IDigitalSignatureCollection](../../com.aspose.slides/idigitalsignaturecollection)

### getSensitivityLabels() {#getSensitivityLabels--}
```
public abstract ISensitivityLabelCollection getSensitivityLabels()
```

Geeft de verzameling van gevoeligheidslabels die op het presentatiedocument zijn toegepast terug. Alleen-lezen [ISensitivityLabelCollection](../../com.aspose.slides/isensitivitylabelcollection).

--------------------

> ```
> Presentation pres = new Presentation("SomePresentation.pptx");
>  try {
>      ISensitivityLabelCollection sensitivityLabels = pres.getSensitivityLabels();
> 
>      // Print de toegepaste labels
>      for (ISensitivityLabel sensitivityLabel : sensitivityLabels)
>          System.out.println("Label Id " + sensitivityLabel.getId() + " from Azure AD site " + sensitivityLabel.getSiteId());
> 
>      // Voeg het nieuwe label toe
>      String labelIdString = "{xxxxxxxx-xxxx-xxxx-xxxx-xxxxxxxxxxxx}"; // Haal de sensitiviteitslabel-Id op uit het beleid
>      UUID siteIdGuid = UUID.fromString("{xxxxxxxx-xxxx-xxxx-xxxx-xxxxxxxxxxxx}"); // Haal de Azure AD-site-identifier op uit het beleid
>      ISensitivityLabel label = sensitivityLabels.add(labelIdString, siteIdGuid, true, SensitivityLabelAssignmentType.Privileged);
>      label.getContentMarkTypes().addItem(SensitivityLabelContentType.Footer);
> 
>      pres.save("SensitivityLabel.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Retourneert:**
[ISensitivityLabelCollection](../../com.aspose.slides/isensitivitylabelcollection)

### save(String fname, int format) {#save-java.lang.String-int-}
```
public abstract void save(String fname, int format)
```

Slaat alle dia's van een presentatie op in een bestand met het opgegeven formaat.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| fname | java.lang.String | Pad naar het te maken bestand. |
| format | int | Formaat van de geëxporteerde gegevens. |

### save(OutputStream stream, int format) {#save-java.io.OutputStream-int-}
```
public abstract void save(OutputStream stream, int format)
```

Slaat alle dia's van een presentatie op in een stream met het opgegeven formaat.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| stream | java.io.OutputStream | Uitvoerstroom. |
| format | int | Formaat van de geëxporteerde gegevens. |

### save(String fname, int format, ISaveOptions options) {#save-java.lang.String-int-com.aspose.slides.ISaveOptions-}
```
public abstract void save(String fname, int format, ISaveOptions options)
```

Slaat alle dia's van een presentatie op in een bestand met het opgegeven formaat en met extra opties.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| fname | java.lang.String | Pad naar het te maken bestand. |

| format | int | Formaat van de geëxporteerde gegevens. |
| options | [ISaveOptions](../../com.aspose.slides/isaveoptions) | Aanvullende formatopties. |

### save(OutputStream stream, int format, ISaveOptions options) {#save-java.io.OutputStream-int-com.aspose.slides.ISaveOptions-}
```
public abstract void save(OutputStream stream, int format, ISaveOptions options)
```

Slaat alle dia's van een presentatie op in een stream in het opgegeven formaat en met aanvullende opties.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| stream | java.io.OutputStream | Uitvoerstream. |
| format | int | Formaat van de geëxporteerde gegevens. |
| options | [ISaveOptions](../../com.aspose.slides/isaveoptions) | Aanvullende formatopties. |

### save(String fname, int[] slides, int format) {#save-java.lang.String-int---int-}
```
public abstract void save(String fname, int[] slides, int format)
```

Slaat opgegeven dia's van een presentatie op in een bestand met het opgegeven formaat.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| fname | java.lang.String | Pad naar het gemaakte bestand. |
| slides | int[] | Array met dia-posities, beginnend bij 1. |
| format | int | Formaat van de geëxporteerde gegevens. |

### save(String fname, int[] slides, int format, ISaveOptions options) {#save-java.lang.String-int---int-com.aspose.slides.ISaveOptions-}
```
public abstract void save(String fname, int[] slides, int format, ISaveOptions options)
```

Slaat opgegeven dia's van een presentatie op in een bestand met het opgegeven formaat.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| fname | java.lang.String | Pad naar het gemaakte bestand. |
| slides | int[] | Array met dia-posities, beginnend bij 1. |
| format | int | Formaat van de geëxporteerde gegevens. |
| options | [ISaveOptions](../../com.aspose.slides/isaveoptions) | Aanvullende formatopties. |

### save(OutputStream stream, int[] slides, int format) {#save-java.io.OutputStream-int---int-}
```
public abstract void save(OutputStream stream, int[] slides, int format)
```

Slaat opgegeven dia's van een presentatie op in een stream in het opgegeven formaat.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| stream | java.io.OutputStream | Uitvoerstream. |
| slides | int[] | Array met dia-posities, beginnend bij 1. |
| format | int | Formaat van de geëxporteerde gegevens. |

### save(OutputStream stream, int[] slides, int format, ISaveOptions options) {#save-java.io.OutputStream-int---int-com.aspose.slides.ISaveOptions-}
```
public abstract void save(OutputStream stream, int[] slides, int format, ISaveOptions options)
```

Slaat opgegeven dia's van een presentatie op in een stream in het opgegeven formaat.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| stream | java.io.OutputStream | Uitvoerstream. |
| slides | int[] | Array met dia-posities, beginnend bij 1. |
| format | int | Formaat van de geëxporteerde gegevens. |
| options | [ISaveOptions](../../com.aspose.slides/isaveoptions) | Aanvullende formatopties. |

### save(IXamlOptions options) {#save-com.aspose.slides.IXamlOptions-}
```
public abstract void save(IXamlOptions options)
```

Slaat alle dia's van een presentatie op in een set bestanden die XAML-markup vertegenwoordigen.

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
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| options | [IXamlOptions](../../com.aspose.slides/ixamloptions) | De XAML-formatopties. |

### getImages(IRenderingOptions options) {#getImages-com.aspose.slides.IRenderingOptions-}
```
public abstract IImage[] getImages(IRenderingOptions options)
```

Retourneert miniatuur-beeldobjecten voor alle dia's van een presentatie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Renderopties. |

**Retour:**
com.aspose.slides.IImage[] - IImage-objecten.

### getImages(IRenderingOptions options, int[] slides) {#getImages-com.aspose.slides.IRenderingOptions-int---}
```
public abstract IImage[] getImages(IRenderingOptions options, int[] slides)
```

Retourneert miniatuur-IImage-objecten voor opgegeven dia's van een presentatie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Renderopties. |
| slides | int[] | Array met dia-posities, beginnend bij 1. |

**Retour:**
com.aspose.slides.IImage[] - IImage-objecten.

### getImages(IRenderingOptions options, float scaleX, float scaleY) {#getImages-com.aspose.slides.IRenderingOptions-float-float-}
```
public abstract IImage[] getImages(IRenderingOptions options, float scaleX, float scaleY)
```

Retourneert miniatuur-beeldobjecten voor alle dia's van een presentatie met aangepaste schaal.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Renderopties. |
| scaleX | float | De waarde waarmee deze miniatuur in de x-as wordt geschaald. |
| scaleY | float | De waarde waarmee deze miniatuur in de y-as wordt geschaald. |

**Retour:**
com.aspose.slides.IImage[] - Bitmap-objecten.

### getImages(IRenderingOptions options, int[] slides, float scaleX, float scaleY) {#getImages-com.aspose.slides.IRenderingOptions-int---float-float-}
```
public abstract IImage[] getImages(IRenderingOptions options, int[] slides, float scaleX, float scaleY)
```

Retourneert miniatuur-beeldobjecten voor opgegeven dia's van een presentatie met aangepaste schaal.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Renderopties. |
| slides | int[] | Array met dia-posities, beginnend bij 1. |
| scaleX | float | De waarde waarmee deze miniatuur in de x-as wordt geschaald. |
| scaleY | float | De waarde waarmee deze miniatuur in de y-as wordt geschaald. |

**Retour:**
com.aspose.slides.IImage[] - IImage-objecten.

### getImages(IRenderingOptions options, Dimension imageSize) {#getImages-com.aspose.slides.IRenderingOptions-java.awt.Dimension-}
```
public abstract IImage[] getImages(IRenderingOptions options, Dimension imageSize)
```

Retourneert miniatuur-beeldobjecten voor alle dia's van een presentatie met opgegeven grootte.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Renderopties. |
| imageSize | java.awt.Dimension | Grootte van het te maken beeld. |

**Retour:**
com.aspose.slides.IImage[] - IImage-objecten.

### getImages(IRenderingOptions options, int[] slides, Dimension imageSize) {#getImages-com.aspose.slides.IRenderingOptions-int---java.awt.Dimension-}
```
public abstract IImage[] getImages(IRenderingOptions options, int[] slides, Dimension imageSize)
```

Retourneert miniatuur-beeldobjecten voor opgegeven dia's van een presentatie met opgegeven grootte.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Renderopties. |
| slides | int[] | Array met dia-posities, beginnend bij 1. |
| imageSize | java.awt.Dimension | Grootte van het te maken beeld. |

**Retour:**
com.aspose.slides.IImage[] - IImage-objecten.

### getSlideById(long id) {#getSlideById-long-}
```
public abstract IBaseSlide getSlideById(long id)
```

Retourneert een Slide, MasterSlide of LayoutSlide op Id.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| id | long | Id van een dia. |

**Retour:**
[IBaseSlide](../../com.aspose.slides/ibaseslide) - IBaseSlide-object.

### joinPortionsWithSameFormatting() {#joinPortionsWithSameFormatting--}
```
public abstract void joinPortionsWithSameFormatting()
```

Voegt runs samen met dezelfde opmaak in alle alinea's in alle acceptabele shapes in alle dia's.

### highlightText(String text, Color highlightColor) {#highlightText-java.lang.String-java.awt.Color-}
```
public abstract void highlightText(String text, Color highlightColor)
```

Markeert alle overeenkomsten van de voorbeeldtekst met de opgegeven kleur.

--------------------

> ```
> The following code sample shows how to highlight text in a PowerPoint presentation.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      // markeert alle afzonderlijke 'the' voorkomen
>      presentation.highlightText("the", Color.MAGENTA);
>      presentation.save("SomePresentation-out2.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| text | java.lang.String | De te markeren tekst. |
| highlightColor | java.awt.Color | De kleur om de tekst te markeren. |

### highlightText(String text, Color highlightColor, ITextSearchOptions options, IFindResultCallback callback) {#highlightText-java.lang.String-java.awt.Color-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-}
```
public abstract void highlightText(String text, Color highlightColor, ITextSearchOptions options, IFindResultCallback callback)
```

Markeert alle overeenkomsten van de voorbeeldtekst met de opgegeven kleur.

--------------------

> ```
> The following code sample shows how to highlight text in a PowerPoint presentation.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      // markeert alle afzonderlijke 'the' voorkomens
>      presentation.highlightText("the", Color.MAGENTA);
>      presentation.save("SomePresentation-out2.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| text | java.lang.String | De te markeren tekst. |
| highlightColor | java.awt.Color | De kleur om de tekst te markeren. |
| options | [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions) | Tekstzoekopties [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions). |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | Het callback-object voor het ontvangen van zoekresultaten [IFindResultCallback](../../com.aspose.slides/ifindresultcallback). |

### highlightRegex(Pattern regex, Color highlightColor, IFindResultCallback callback) {#highlightRegex-java.util.regex.Pattern-java.awt.Color-com.aspose.slides.IFindResultCallback-}
```
public abstract void highlightRegex(Pattern regex, Color highlightColor, IFindResultCallback callback)
```

Markeert alle overeenkomsten van de reguliere expressie met de opgegeven kleur.

--------------------

> ```
> The following code sample shows how to highlight text in a PowerPoint Presentation using a regular expression.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      // markeert alle afzonderlijke 'the' voorkomens
>      presentation.highlightText("the", Color.MAGENTA);
>      presentation.save("SomePresentation-out2.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| regex | java.util.regex.Pattern | De reguliere expressie java.util.regex.Pattern om te markeren strings te verkrijgen. |
| highlightColor | java.awt.Color | De kleur om de tekst te markeren. |
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
>      // Vervang alle afzonderlijke 'the' voorkomens door '***'
>      presentation.replaceText("the", "***", textSearchOptions, null);
>      presentation.save("SomePresentation-out2.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| oldText | java.lang.String | De te vervangen tekenreeks. |
| newText | java.lang.String | De tekenreeks om alle voorkomens van oldText te vervangen. |
| options | [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions) | Tekstzoekopties [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions). |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | Het callback-object voor het ontvangen van zoekresultaten [IFindResultCallback](../../com.aspose.slides/ifindresultcallback). |

### replaceRegex(Pattern regex, String newText, IFindResultCallback callback) {#replaceRegex-java.util.regex.Pattern-java.lang.String-com.aspose.slides.IFindResultCallback-}
```
public abstract void replaceRegex(Pattern regex, String newText, IFindResultCallback callback)
```

Vervangt alle overeenkomsten van de reguliere expressie door de opgegeven tekenreeks.

--------------------

> ```
> The following code sample shows how to replace text using regular expression with the specified string.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx")
>  try {
>      TextSearchOptions textSearchOptions = new TextSearchOptions();
>      textSearchOptions.setWholeWordsOnly(true);
>      // Vervang alle afzonderlijke 'the' voorkomens door '***'
>      presentation.replaceText("the", "***", textSearchOptions, null);
>      presentation.save("SomePresentation-out2.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| regex | java.util.regex.Pattern | De reguliere expressie java.util.regex.Pattern om te vervangen tekenreeksen te verkrijgen. |
| newText | java.lang.String | De tekenreeks om alle voorkomens van de te vervangen tekenreeksen te vervangen. |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | Het callback-object voor het ontvangen van zoekresultaten [IFindResultCallback](../../com.aspose.slides/ifindresultcallback). |