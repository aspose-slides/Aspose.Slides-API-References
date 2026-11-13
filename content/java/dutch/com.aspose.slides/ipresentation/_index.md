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
| [getCurrentDateTime()](#getCurrentDateTime--) | Retourneert of stelt datum en tijd in die de inhoud van datetime-velden vervangt. |
| [setCurrentDateTime(Date value)](#setCurrentDateTime-java.util.Date-) | Retourneert of stelt datum en tijd in die de inhoud van datetime-velden vervangt. |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | Retourneert HeaderFooter-manager van de presentatie. |
| [getProtectionManager()](#getProtectionManager--) | Verkrijgt manager van de permissies voor deze presentatie. |
| [getSlides()](#getSlides--) | Retourneert een lijst van alle dia's die in de presentatie zijn gedefinieerd. |
| [getSections()](#getSections--) | Retourneert een lijst van alle secties van dia's die in de presentatie zijn gedefinieerd. |
| [getSlideSize()](#getSlideSize--) | Retourneert slide-grootteobject. |
| [getNotesSize()](#getNotesSize--) | Retourneert notitieslide-grootteobject. |
| [getLayoutSlides()](#getLayoutSlides--) | Retourneert een lijst van alle layout-dia's die in de presentatie zijn gedefinieerd. |
| [getMasters()](#getMasters--) | Retourneert een lijst van alle master-dia's die in de presentatie zijn gedefinieerd. |
| [getMasterNotesSlideManager()](#getMasterNotesSlideManager--) | Retourneert notitie-master manager. |
| [getMasterHandoutSlideManager()](#getMasterHandoutSlideManager--) | Retourneert handout master manager. |
| [getFontsManager()](#getFontsManager--) | Retourneert lettertype-manager. |
| [getDefaultTextStyle()](#getDefaultTextStyle--) | Retourneert standaard tekststijl voor vormen. |
| [getCommentAuthors()](#getCommentAuthors--) | Retourneert de verzameling van commentaarauteurs. |
| [getDocumentProperties()](#getDocumentProperties--) | Retourneert DocumentProperties-object dat standaard en aangepaste documenteigenschappen bevat. |
| [getImages()](#getImages--) | Retourneert de verzameling van alle afbeeldingen in de presentatie. |
| [getAudios()](#getAudios--) | Retourneert de verzameling van alle ingesloten audiobestanden in de presentatie. |
| [getVideos()](#getVideos--) | Retourneert de verzameling van alle ingesloten videobestanden in de presentatie. |
| [getCustomData()](#getCustomData--) | Retourneert de aangepaste data van de presentatie. |
| [getVbaProject()](#getVbaProject--) | Haalt VBA-project met presentatiemacro's op. |
| [setVbaProject(IVbaProject value)](#setVbaProject-com.aspose.slides.IVbaProject-) | Haalt VBA-project met presentatiemacro's op. |
| [getSourceFormat()](#getSourceFormat--) | Retourneert informatie over uit welk formaat de presentatie is geladen. |
| [getMasterTheme()](#getMasterTheme--) | Retourneert masterthema van de presentatie. |
| [getHyperlinkQueries()](#getHyperlinkQueries--) | Biedt eenvoudige toegang tot alle hyperlinks die in alle presentatiedia's zitten (niet in master-, layout- of notitieslides). |
| [getViewProperties()](#getViewProperties--) | Haalt weergave-eigenschappen voor de hele presentatie op. |
| [getFirstSlideNumber()](#getFirstSlideNumber--) | Stelt het eerste dianummer in de presentatie voor. |
| [setFirstSlideNumber(int value)](#setFirstSlideNumber-int-) | Stelt het eerste dianummer in de presentatie voor. |
| [getAllCustomXmlParts()](#getAllCustomXmlParts--) | Retourneert alle aangepaste dataparts in de presentatie. |
| [getDigitalSignatures()](#getDigitalSignatures--) | Retourneert de verzameling van handtekeningen die gebruikt worden om de presentatie te ondertekenen. |
| [getSensitivityLabels()](#getSensitivityLabels--) | Retourneert de verzameling van gevoeligheidslabels die op het presentatiedocument zijn toegepast. |
| [save(String fname, int format)](#save-java.lang.String-int-) | Slaat alle dia's van een presentatie op in een bestand met het opgegeven formaat. |
| [save(OutputStream stream, int format)](#save-java.io.OutputStream-int-) | Slaat alle dia's van een presentatie op in een stream in het opgegeven formaat. |
| [save(String fname, int format, ISaveOptions options)](#save-java.lang.String-int-com.aspose.slides.ISaveOptions-) | Slaat alle dia's van een presentatie op in een bestand met het opgegeven formaat en met extra opties. |
| [save(OutputStream stream, int format, ISaveOptions options)](#save-java.io.OutputStream-int-com.aspose.slides.ISaveOptions-) | Slaat alle dia's van een presentatie op in een stream in het opgegeven formaat en met extra opties. |
| [save(String fname, int[] slides, int format)](#save-java.lang.String-int---int-) | Slaat opgegeven dia's van een presentatie op in een bestand met het opgegeven formaat. |
| [save(String fname, int[] slides, int format, ISaveOptions options)](#save-java.lang.String-int---int-com.aspose.slides.ISaveOptions-) | Slaat opgegeven dia's van een presentatie op in een bestand met het opgegeven formaat. |
| [save(OutputStream stream, int[] slides, int format)](#save-java.io.OutputStream-int---int-) | Slaat opgegeven dia's van een presentatie op in een stream in het opgegeven formaat. |
| [save(OutputStream stream, int[] slides, int format, ISaveOptions options)](#save-java.io.OutputStream-int---int-com.aspose.slides.ISaveOptions-) | Slaat opgegeven dia's van een presentatie op in een stream in het opgegeven formaat. |
| [save(IXamlOptions options)](#save-com.aspose.slides.IXamlOptions-) | Slaat alle dia's van een presentatie op in een reeks bestanden die XAML-markup vertegenwoordigen. |
| [getImages(IRenderingOptions options)](#getImages-com.aspose.slides.IRenderingOptions-) | Retourneert miniatuur-afbeeldingsobjecten voor alle dia's van een presentatie. |
| [getImages(IRenderingOptions options, int[] slides)](#getImages-com.aspose.slides.IRenderingOptions-int---) | Retourneert miniatuur-IImage-objecten voor opgegeven dia's van een presentatie. |
| [getImages(IRenderingOptions options, float scaleX, float scaleY)](#getImages-com.aspose.slides.IRenderingOptions-float-float-) | Retourneert miniatuur-afbeeldingsobjecten voor alle dia's van een presentatie met aangepaste schaal. |
| [getImages(IRenderingOptions options, int[] slides, float scaleX, float scaleY)](#getImages-com.aspose.slides.IRenderingOptions-int---float-float-) | Retourneert miniatuur-afbeeldingsobjecten voor opgegeven dia's van een presentatie met aangepaste schaal. |
| [getImages(IRenderingOptions options, Dimension imageSize)](#getImages-com.aspose.slides.IRenderingOptions-java.awt.Dimension-) | Retourneert miniatuur-afbeeldingsobjecten voor alle dia's van een presentatie met opgegeven grootte. |
| [getImages(IRenderingOptions options, int[] slides, Dimension imageSize)](#getImages-com.aspose.slides.IRenderingOptions-int---java.awt.Dimension-) | Retourneert miniatuur-afbeeldingsobjecten voor opgegeven dia's van een presentatie met opgegeven grootte. |
| [getSlideById(long id)](#getSlideById-long-) | Retourneert een Slide, MasterSlide of LayoutSlide op Id. |
| [joinPortionsWithSameFormatting()](#joinPortionsWithSameFormatting--) | Voegt runs met dezelfde opmaak samen in alle alinea's in alle acceptabele vormen in alle dia's. |
| [highlightText(String text, Color highlightColor)](#highlightText-java.lang.String-java.awt.Color-) | Markeert alle overeenkomsten van de voorbeeldtekst met de opgegeven kleur. |
| [highlightText(String text, Color highlightColor, ITextSearchOptions options, IFindResultCallback callback)](#highlightText-java.lang.String-java.awt.Color-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-) | Markeert alle overeenkomsten van de voorbeeldtekst met de opgegeven kleur. |
| [highlightRegex(Pattern regex, Color highlightColor, IFindResultCallback callback)](#highlightRegex-java.util.regex.Pattern-java.awt.Color-com.aspose.slides.IFindResultCallback-) | Markeert alle overeenkomsten van de reguliere expressie met de opgegeven kleur. |
| [replaceText(String oldText, String newText, ITextSearchOptions options, IFindResultCallback callback)](#replaceText-java.lang.String-java.lang.String-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-) | Vervangt alle voorkomens van de opgegeven tekst door een andere opgegeven tekst. |
| [replaceRegex(Pattern regex, String newText, IFindResultCallback callback)](#replaceRegex-java.util.regex.Pattern-java.lang.String-com.aspose.slides.IFindResultCallback-) | Vervangt alle overeenkomsten van de reguliere expressie door de opgegeven tekenreeks. |
| [refreshChartsData()](#refreshChartsData--) | Laadt de gegevens voor alle grafieken in de presentatie opnieuw vanuit hun bronwerkboeken. |
| [refreshChartsData(boolean skipFailedCharts)](#refreshChartsData-boolean-) | Laadt de gegevens voor alle grafieken in de presentatie opnieuw vanuit hun bronwerkboeken. |

### getCurrentDateTime() {#getCurrentDateTime--}
```
public abstract Date getCurrentDateTime()
```

Retourneert of stelt datum en tijd in die de inhoud van datetime-velden vervangt. Tijd van de creatie van dit Presentation-object standaard. Lezen/schrijven java.util.Date.

**Retourneert:**
java.util.Date

### setCurrentDateTime(Date value) {#setCurrentDateTime-java.util.Date-}
```
public abstract void setCurrentDateTime(Date value)
```

Retourneert of stelt datum en tijd in die de inhoud van datetime-velden vervangt. Tijd van de creatie van dit Presentation-object standaard. Lezen/schrijven java.util.Date.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | java.util.Date |  |

### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public abstract IPresentationHeaderFooterManager getHeaderFooterManager()
```

Retourneert HeaderFooter-manager van de presentatie. Alleen-lezen [IPresentationHeaderFooterManager](../../com.aspose.slides/ipresentationheaderfootermanager).

**Retourneert:**
[IPresentationHeaderFooterManager](../../com.aspose.slides/ipresentationheaderfootermanager)

### getProtectionManager() {#getProtectionManager--}
```
public abstract IProtectionManager getProtectionManager()
```

Verkrijgt manager van de permissies voor deze presentatie. Alleen-lezen [IProtectionManager](../../com.aspose.slides/iprotectionmanager).

**Retourneert:**
[IProtectionManager](../../com.aspose.slides/iprotectionmanager)

### getSlides() {#getSlides--}
```
public abstract ISlideCollection getSlides()
```

Retourneert een lijst van alle dia's die in de presentatie zijn gedefinieerd. Alleen-lezen [ISlideCollection](../../com.aspose.slides/islidecollection).

**Retourneert:**
[ISlideCollection](../../com.aspose.slides/islidecollection)

### getSections() {#getSections--}
```
public abstract ISectionCollection getSections()
```

Retourneert een lijst van alle secties van dia's die in de presentatie zijn gedefinieerd. Alleen-lezen [ISectionCollection](../../com.aspose.slides/isectioncollection).

**Retourneert:**
[ISectionCollection](../../com.aspose.slides/isectioncollection)

### getSlideSize() {#getSlideSize--}
```
public abstract ISlideSize getSlideSize()
```

Retourneert slide-grootteobject. Alleen-lezen [ISlideSize](../../com.aspose.slides/islidesize).

**Retourneert:**
[ISlideSize](../../com.aspose.slides/islidesize)

### getNotesSize() {#getNotesSize--}
```
public abstract INotesSize getNotesSize()
```

Retourneert notitieslide-grootteobject. Alleen-lezen [INotesSize](../../com.aspose.slides/inotessize).

**Retourneert:**
[INotesSize](../../com.aspose.slides/inotessize)

### getLayoutSlides() {#getLayoutSlides--}
```
public abstract IGlobalLayoutSlideCollection getLayoutSlides()
```

Retourneert een lijst van alle layout-dia's die in de presentatie zijn gedefinieerd. Alleen-lezen [IGlobalLayoutSlideCollection](../../com.aspose.slides/igloballayoutslidecollection).

--------------------

U kunt toegang krijgen tot een alternatieve API voor het toevoegen/invoegen/verwijderen/kloont van layout-dia's via de eigenschap IMasterSlide.LayoutSlides property.

**Retourneert:**
[IGlobalLayoutSlideCollection](../../com.aspose.slides/igloballayoutslidecollection)

### getMasters() {#getMasters--}
```
public abstract IMasterSlideCollection getMasters()
```

Retourneert een lijst van alle master-dia's die in de presentatie zijn gedefinieerd. Alleen-lezen [IMasterSlideCollection](../../com.aspose.slides/imasterslidecollection).

**Retourneert:**
[IMasterSlideCollection](../../com.aspose.slides/imasterslidecollection)

### getMasterNotesSlideManager() {#getMasterNotesSlideManager--}
```
public abstract IMasterNotesSlideManager getMasterNotesSlideManager()
```

Retourneert notitie-master manager. Alleen-lezen [IMasterNotesSlideManager](../../com.aspose.slides/imasternotesslidemanager).

**Retourneert:**
[IMasterNotesSlideManager](../../com.aspose.slides/imasternotesslidemanager)

### getMasterHandoutSlideManager() {#getMasterHandoutSlideManager--}
```
public abstract IMasterHandoutSlideManager getMasterHandoutSlideManager()
```

Retourneert handout master manager. Alleen-lezen [IMasterHandoutSlideManager](../../com.aspose.slides/imasterhandoutslidemanager).

**Retourneert:**
[IMasterHandoutSlideManager](../../com.aspose.slides/imasterhandoutslidemanager)

### getFontsManager() {#getFontsManager--}
```
public abstract IFontsManager getFontsManager()
```

Retourneert lettertype-manager. Alleen-lezen [IFontsManager](../../com.aspose.slides/ifontsmanager).

**Retourneert:**
[IFontsManager](../../com.aspose.slides/ifontsmanager)

### getDefaultTextStyle() {#getDefaultTextStyle--}
```
public abstract ITextStyle getDefaultTextStyle()
```

Retourneert standaard tekststijl voor vormen. Alleen-lezen [ITextStyle](../../com.aspose.slides/itextstyle).

**Retourneert:**
[ITextStyle](../../com.aspose.slides/itextstyle)

### getCommentAuthors() {#getCommentAuthors--}
```
public abstract ICommentAuthorCollection getCommentAuthors()
```

Retourneert de verzameling van commentaarauteurs. Alleen-lezen [ICommentAuthorCollection](../../com.aspose.slides/icommentauthorcollection).

**Retourneert:**
[ICommentAuthorCollection](../../com.aspose.slides/icommentauthorcollection)

### getDocumentProperties() {#getDocumentProperties--}
```
public abstract IDocumentProperties getDocumentProperties()
```

Retourneert DocumentProperties-object dat standaard en aangepaste documenteigenschappen bevat. Alleen-lezen [IDocumentProperties](../../com.aspose.slides/idocumentproperties).

**Retourneert:**
[IDocumentProperties](../../com.aspose.slides/idocumentproperties)

### getImages() {#getImages--}
```
public abstract IImageCollection getImages()
```

Retourneert de verzameling van alle afbeeldingen in de presentatie. Alleen-lezen [IImageCollection](../../com.aspose.slides/iimagecollection).

**Retourneert:**
[IImageCollection](../../com.aspose.slides/iimagecollection)

### getAudios() {#getAudios--}
```
public abstract IAudioCollection getAudios()
```

Retourneert de verzameling van alle ingesloten audiobestanden in de presentatie. Alleen-lezen [IAudioCollection](../../com.aspose.slides/iaudiocollection).

**Retourneert:**
[IAudioCollection](../../com.aspose.slides/iaudiocollection)

### getVideos() {#getVideos--}
```
public abstract IVideoCollection getVideos()
```

Retourneert de verzameling van alle ingesloten videobestanden in de presentatie. Alleen-lezen [IVideoCollection](../../com.aspose.slides/ivideocollection).

**Retourneert:**
[IVideoCollection](../../com.aspose.slides/ivideocollection)

### getCustomData() {#getCustomData--}
```
public abstract ICustomData getCustomData()
```

Retourneert de aangepaste data van de presentatie. Alleen-lezen [ICustomData](../../com.aspose.slides/icustomdata).

**Retourneert:**
[ICustomData](../../com.aspose.slides/icustomdata)

### getVbaProject() {#getVbaProject--}
```
public abstract IVbaProject getVbaProject()
```

Haalt VBA-project met presentatiemacro's op. Lezen/schrijven [IVbaProject](../../com.aspose.slides/ivbaproject).

**Retourneert:**
[IVbaProject](../../com.aspose.slides/ivbaproject)

### setVbaProject(IVbaProject value) {#setVbaProject-com.aspose.slides.IVbaProject-}
```
public abstract void setVbaProject(IVbaProject value)
```

Stelt VBA-project met presentatiemacro's in. Lezen/schrijven [IVbaProject](../../com.aspose.slides/ivbaproject).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [IVbaProject](../../com.aspose.slides/ivbaproject) |  |

### getSourceFormat() {#getSourceFormat--}
```
public abstract int getSourceFormat()
```

Retourneert informatie over uit welk formaat de presentatie is geladen. Alleen-lezen [SourceFormat](../../com.aspose.slides/sourceformat).

**Retourneert:**
int

### getMasterTheme() {#getMasterTheme--}
```
public abstract IMasterTheme getMasterTheme()
```

Retourneert masterthema van de presentatie. Alleen-lezen [IMasterTheme](../../com.aspose.slides/imastertheme).

**Retourneert:**
[IMasterTheme](../../com.aspose.slides/imastertheme)

### getHyperlinkQueries() {#getHyperlinkQueries--}
```
public abstract IHyperlinkQueries getHyperlinkQueries()
```

Biedt eenvoudige toegang tot alle hyperlinks in alle presentatiedia's (niet in master-, layout- of notitieslides). Alleen-lezen [IHyperlinkQueries](../../com.aspose.slides/ihyperlinkqueries).

**Retourneert:**
[IHyperlinkQueries](../../com.aspose.slides/ihyperlinkqueries)

### getViewProperties() {#getViewProperties--}
```
public abstract IViewProperties getViewProperties()
```

Haalt weergave-eigenschappen voor de hele presentatie op. Alleen-lezen [IViewProperties](../../com.aspose.slides/iviewproperties).

**Retourneert:**
[IViewProperties](../../com.aspose.slides/iviewproperties)

### getFirstSlideNumber() {#getFirstSlideNumber--}
```
public abstract int getFirstSlideNumber()
```

Stelt het eerste dianummer in de presentatie voor. Lezen/schrijven int.

**Retourneert:**
int

### setFirstSlideNumber(int value) {#setFirstSlideNumber-int-}
```
public abstract void setFirstSlideNumber(int value)
```

Stelt het eerste dianummer in de presentatie voor. Lezen/schrijven int.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | int |  |

### getAllCustomXmlParts() {#getAllCustomXmlParts--}
```
public abstract ICustomXmlPart[] getAllCustomXmlParts()
```

Retourneert alle aangepaste dataparts in de presentatie. Alleen-lezen ICustomXmlPart[].

**Retourneert:**
com.aspose.slides.ICustomXmlPart[]

### getDigitalSignatures() {#getDigitalSignatures--}
```
public abstract IDigitalSignatureCollection getDigitalSignatures()
```

Retourneert de verzameling van handtekeningen die worden gebruikt om de presentatie te ondertekenen. Alleen-lezen [IDigitalSignatureCollection](../../com.aspose.slides/idigitalsignaturecollection).

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

Retourneert de verzameling van gevoeligheidslabels die op het presentatiedocument zijn toegepast. Alleen-lezen [ISensitivityLabelCollection](../../com.aspose.slides/isensitivitylabelcollection).

--------------------

> ```
> Presentation pres = new Presentation("SomePresentation.pptx");
>  try {
>      ISensitivityLabelCollection sensitivityLabels = pres.getSensitivityLabels();
> 
>      // Druk de toegepaste labels af
>      for (ISensitivityLabel sensitivityLabel : sensitivityLabels)
>          System.out.println("Label Id " + sensitivityLabel.getId() + " from Azure AD site " + sensitivityLabel.getSiteId());
> 
>      // Voeg het nieuwe label toe
>      String labelIdString = "{xxxxxxxx-xxxx-xxxx-xxxx-xxxxxxxxxxxx}"; // Haal de gevoeligheidslabel-ID op uit het beleid
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
| fname | java.lang.String | Pad naar het aangemaakte bestand. |
| format | int | Formaat van de geëxporteerde gegevens. |

### save(OutputStream stream, int format) {#save-java.io.OutputStream-int-}
```
public abstract void save(OutputStream stream, int format)
```

Slaat alle dia's van een presentatie op in een stream in het opgegeven formaat.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| stream | java.io.OutputStream | Uitvoerstroom. |
| format | int | Formaat van de geëxporteerde gegevens. |

### save(String fname, int format, ISaveOptions options) {#save-java.lang.String-int-com.aspose.slides.ISaveOptions-}
```
public abstract void save(String fname, int format, ISaveOptions options)
```
Slaat alle dia’s van een presentatie op in een bestand met het opgegeven formaat en met extra opties.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| fname | java.lang.String | Pad naar het aangemaakte bestand. |
| format | int | Formaat van de geëxporteerde gegevens. |
| options | [ISaveOptions](../../com.aspose.slides/isaveoptions) | Aanvullende formaatopties. |

### save(OutputStream stream, int format, ISaveOptions options) {#save-java.io.OutputStream-int-com.aspose.slides.ISaveOptions-}
```
public abstract void save(OutputStream stream, int format, ISaveOptions options)
```

Slaat alle dia’s van een presentatie op in een stream in het opgegeven formaat en met extra opties.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| stream | java.io.OutputStream | Output-stream. |
| format | int | Formaat van de geëxporteerde gegevens. |
| options | [ISaveOptions](../../com.aspose.slides/isaveoptions) | Aanvullende formaatopties. |

### save(String fname, int[] slides, int format) {#save-java.lang.String-int---int-}
```
public abstract void save(String fname, int[] slides, int format)
```

Slaat opgegeven dia’s van een presentatie op in een bestand met het opgegeven formaat.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| fname | java.lang.String | Pad naar het aangemaakte bestand. |
| slides | int[] | Array met dia-posities, beginnend bij 1. |
| format | int | Formaat van de geëxporteerde gegevens. |

### save(String fname, int[] slides, int format, ISaveOptions options) {#save-java.lang.String-int---int-com.aspose.slides.ISaveOptions-}
```
public abstract void save(String fname, int[] slides, int format, ISaveOptions options)
```

Slaat opgegeven dia’s van een presentatie op in een bestand met het opgegeven formaat.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| fname | java.lang.String | Pad naar het aangemaakte bestand. |
| slides | int[] | Array met dia-posities, beginnend bij 1. |
| format | int | Formaat van de geëxporteerde gegevens. |
| options | [ISaveOptions](../../com.aspose.slides/isaveoptions) | Aanvullende formaatopties. |

### save(OutputStream stream, int[] slides, int format) {#save-java.io.OutputStream-int---int-}
```
public abstract void save(OutputStream stream, int[] slides, int format)
```

Slaat opgegeven dia’s van een presentatie op in een stream in het opgegeven formaat.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| stream | java.io.OutputStream | Output-stream. |
| slides | int[] | Array met dia-posities, beginnend bij 1. |
| format | int | Formaat van de geëxporteerde gegevens. |

### save(OutputStream stream, int[] slides, int format, ISaveOptions options) {#save-java.io.OutputStream-int---int-com.aspose.slides.ISaveOptions-}
```
public abstract void save(OutputStream stream, int[] slides, int format, ISaveOptions options)
```

Slaat opgegeven dia’s van een presentatie op in een stream in het opgegeven formaat.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| stream | java.io.OutputStream | Output-stream. |
| slides | int[] | Array met dia-posities, beginnend bij 1. |
| format | int | Formaat van de geëxporteerde gegevens. |
| options | [ISaveOptions](../../com.aspose.slides/isaveoptions) | Aanvullende formaatopties. |

### save(IXamlOptions options) {#save-com.aspose.slides.IXamlOptions-}
```
public abstract void save(IXamlOptions options)
```

Slaat alle dia’s van een presentatie op in een reeks bestanden die XAML-markup vertegenwoordigen.

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
| options | [IXamlOptions](../../com.aspose.slides/ixamloptions) | De XAML-formaatopties. |

### getImages(IRenderingOptions options) {#getImages-com.aspose.slides.IRenderingOptions-}
```
public abstract IImage[] getImages(IRenderingOptions options)
```

Retourneert Thumbnail Image objects voor alle dia’s van een presentatie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Rendering-opties. |

**Returns:**
com.aspose.slides.IImage[] - IImage objects.

### getImages(IRenderingOptions options, int[] slides) {#getImages-com.aspose.slides.IRenderingOptions-int---}
```
public abstract IImage[] getImages(IRenderingOptions options, int[] slides)
```

Retourneert Thumbnail IImage objects voor opgegeven dia’s van een presentatie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Rendering-opties. |
| slides | int[] | Array met dia-posities, beginnend bij 1. |

**Returns:**
com.aspose.slides.IImage[] - IImage objects.

### getImages(IRenderingOptions options, float scaleX, float scaleY) {#getImages-com.aspose.slides.IRenderingOptions-float-float-}
```
public abstract IImage[] getImages(IRenderingOptions options, float scaleX, float scaleY)
```

Retourneert Thumbnail Image objects voor alle dia’s van een presentatie met aangepaste schaal.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Rendering-opties. |
| scaleX | float | De waarde waarmee deze thumbnail in de x-richting wordt geschaald. |
| scaleY | float | De waarde waarmee deze thumbnail in de y-richting wordt geschaald. |

**Returns:**
com.aspose.slides.IImage[] - Bitmap objects.

### getImages(IRenderingOptions options, int[] slides, float scaleX, float scaleY) {#getImages-com.aspose.slides.IRenderingOptions-int---float-float-}
```
public abstract IImage[] getImages(IRenderingOptions options, int[] slides, float scaleX, float scaleY)
```

Retourneert Thumbnail Image objects voor opgegeven dia’s van een presentatie met aangepaste schaal.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Rendering-opties. |
| slides | int[] | Array met dia-posities, beginnend bij 1. |
| scaleX | float | De waarde waarmee deze thumbnail in de x-richting wordt geschaald. |
| scaleY | float | De waarde waarmee deze thumbnail in de y-richting wordt geschaald. |

**Returns:**
com.aspose.slides.IImage[] - IImage objects.

### getImages(IRenderingOptions options, Dimension imageSize) {#getImages-com.aspose.slides.IRenderingOptions-java.awt.Dimension-}
```
public abstract IImage[] getImages(IRenderingOptions options, Dimension imageSize)
```

Retourneert Thumbnail Image objects voor alle dia’s van een presentatie met opgegeven grootte.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Rendering-opties. |
| imageSize | java.awt.Dimension | Grootte van de te maken afbeelding. |

**Returns:**
com.aspose.slides.IImage[] - IImage objects.

### getImages(IRenderingOptions options, int[] slides, Dimension imageSize) {#getImages-com.aspose.slides.IRenderingOptions-int---java.awt.Dimension-}
```
public abstract IImage[] getImages(IRenderingOptions options, int[] slides, Dimension imageSize)
```

Retourneert Thumbnail Image objects voor opgegeven dia’s van een presentatie met opgegeven grootte.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Rendering-opties. |
| slides | int[] | Array met dia-posities, beginnend bij 1. |
| imageSize | java.awt.Dimension | Grootte van de te maken afbeelding. |

**Returns:**
com.aspose.slides.IImage[] - IImage objects.

### getSlideById(long id) {#getSlideById-long-}
```
public abstract IBaseSlide getSlideById(long id)
```

Retourneert een Slide, MasterSlide of LayoutSlide op Id.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| id | long | Id van een dia. |

**Returns:**
[IBaseSlide](../../com.aspose.slides/ibaseslide) - IBaseSlide object.

### joinPortionsWithSameFormatting() {#joinPortionsWithSameFormatting--}
```
public abstract void joinPortionsWithSameFormatting()
```

Voegt runs met dezelfde opmaak samen in alle alinea’s in alle acceptabele vormen in alle dia’s.

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
>      // markeren van alle afzonderlijke 'the'-voorkomens
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
>      // markeren van alle afzonderlijke 'the'-voorkomens
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
> Het volgende codevoorbeeld laat zien hoe je tekst kunt markeren in een PowerPoint-presentatie met behulp van een reguliere expressie.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      // markeren van alle afzonderlijke 'the'-voorkomens
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
> De volgende voorbeeldcode toont hoe je een opgegeven string kunt vervangen door een andere opgegeven string.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx")
>  try {
>      TextSearchOptions textSearchOptions = new TextSearchOptions();
>      textSearchOptions.setWholeWordsOnly(true);
>      // Vervang alle afzonderlijke 'the'-voorkomens door '***'
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
> Het volgende codevoorbeeld laat zien hoe je tekst kunt vervangen met een reguliere expressie door de opgegeven string.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx")
>  try {
>      TextSearchOptions textSearchOptions = new TextSearchOptions();
>      textSearchOptions.setWholeWordsOnly(true);
>      // Vervang alle afzonderlijke 'the'-voorkomens door '***'
>      presentation.replaceText("the", "***", textSearchOptions, null);
>      presentation.save("SomePresentation-out2.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| regex | java.util.regex.Pattern | De reguliere expressie java.util.regex.Pattern om te vervangen strings te verkrijgen. |
| newText | java.lang.String | De tekenreeks om alle voorkomens van de te vervangen tekenreeksen te vervangen. |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | Het callback-object voor het ontvangen van zoekresultaten [IFindResultCallback](../../com.aspose.slides/ifindresultcallback). |

### refreshChartsData() {#refreshChartsData--}
```
public abstract void refreshChartsData()
```

Laadt de gegevens voor alle grafieken in de presentatie opnieuw vanuit hun bron-werkboeken.

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

Laadt de gegevens voor alle grafieken in de presentatie opnieuw vanuit hun bron-werkboeken.

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

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| skipFailedCharts | boolean | Bepaalt of het vernieuwingsproces doorgaat als een grafiek niet kan worden bijgewerkt. Indien true worden grafieken die een uitzondering veroorzaken overgeslagen; anders wordt de uitzondering doorgegeven. |