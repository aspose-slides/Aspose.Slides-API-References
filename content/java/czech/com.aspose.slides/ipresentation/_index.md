---
title: IPresentation
second_title: Aspose.Slides pro Java API Reference
description: Dokument prezentace
type: docs
url: /cs/com.aspose.slides/ipresentation/
---
**Všechny implementované rozhraní:**
[com.aspose.slides.IPresentationComponent](../../com.aspose.slides/ipresentationcomponent), com.aspose.ms.System.IDisposable
```
public interface IPresentation extends IPresentationComponent, System.IDisposable
```

Dokument prezentace
## Metody

| Metoda | Popis |
| --- | --- |
| [getCurrentDateTime()](#getCurrentDateTime--) | Vrací nebo nastavuje datum a čas, který nahradí obsah polí datetime. |
| [setCurrentDateTime(Date value)](#setCurrentDateTime-java.util.Date-) | Vrací nebo nastavuje datum a čas, který nahradí obsah polí datetime. |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | Vrací správce HeaderFooter prezentace. |
| [getProtectionManager()](#getProtectionManager--) | Získá správce oprávnění pro tuto prezentaci. |
| [getSlides()](#getSlides--) | Vrací seznam všech snímků, které jsou v prezentaci definovány. |
| [getSections()](#getSections--) | Vrací seznam všech sekcí snímků, které jsou v prezentaci definovány. |
| [getSlideSize()](#getSlideSize--) | Vrací objekt velikosti snímku. |
| [getNotesSize()](#getNotesSize--) | Vrací objekt velikosti poznámkových snímků. |
| [getLayoutSlides()](#getLayoutSlides--) | Vrací seznam všech rozložení snímků, které jsou v prezentaci definovány. |
| [getMasters()](#getMasters--) | Vrací seznam všech hlavních snímků, které jsou v prezentaci definovány. |
| [getMasterNotesSlideManager()](#getMasterNotesSlideManager--) | Vrací správce hlavních poznámkových snímků. |
| [getMasterHandoutSlideManager()](#getMasterHandoutSlideManager--) | Vrací správce hlavních výtisků. |
| [getFontsManager()](#getFontsManager--) | Vrací správce písem. |
| [getDefaultTextStyle()](#getDefaultTextStyle--) | Vrací výchozí styl textu pro tvary. |
| [getCommentAuthors()](#getCommentAuthors--) | Vrací kolekci autorů komentářů. |
| [getDocumentProperties()](#getDocumentProperties--) | Vrací objekt DocumentProperties, který obsahuje standardní a vlastní vlastnosti dokumentu. |
| [getImages()](#getImages--) | Vrací kolekci všech obrázků v prezentaci. |
| [getAudios()](#getAudios--) | Vrací kolekci všech vložených audio souborů v prezentaci. |
| [getVideos()](#getVideos--) | Vrací kolekci všech vložených video souborů v prezentaci. |
| [getCustomData()](#getCustomData--) | Vrací vlastní data prezentace. |
| [getVbaProject()](#getVbaProject--) | Získá projekt VBA s makry prezentace. |
| [setVbaProject(IVbaProject value)](#setVbaProject-com.aspose.slides.IVbaProject-) | Získá projekt VBA s makry prezentace. |
| [getSourceFormat()](#getSourceFormat--) | Vrací informace o formátu, ze kterého byla prezentace načtena. |
| [getMasterTheme()](#getMasterTheme--) | Vrací hlavní téma prezentace. |
| [getHyperlinkQueries()](#getHyperlinkQueries--) | Poskytuje snadný přístup ke všem hypertextovým odkazům obsaženým ve všech snímcích prezentace (ne v hlavních, rozložení, poznámkových snímcích). |
| [getViewProperties()](#getViewProperties--) | Získá globální vlastnosti zobrazení prezentace. |
| [getFirstSlideNumber()](#getFirstSlideNumber--) | Zastupuje první číslo snímku v prezentaci. |
| [setFirstSlideNumber(int value)](#setFirstSlideNumber-int-) | Zastupuje první číslo snímku v prezentaci. |
| [getAllCustomXmlParts()](#getAllCustomXmlParts--) | Vrací všechny vlastní datové části v prezentaci. |
| [getDigitalSignatures()](#getDigitalSignatures--) | Vrací kolekci podpisů použité k podepsání prezentace. |
| [getSensitivityLabels()](#getSensitivityLabels--) | Vrací kolekci štítků citlivosti aplikovaných na dokument prezentace. |
| [save(String fname, int format)](#save-java.lang.String-int-) | Uloží všechny snímky prezentace do souboru ve zvoleném formátu. |
| [save(OutputStream stream, int format)](#save-java.io.OutputStream-int-) | Uloží všechny snímky prezentace do proudu ve zvoleném formátu. |
| [save(String fname, int format, ISaveOptions options)](#save-java.lang.String-int-com.aspose.slides.ISaveOptions-) | Uloží všechny snímky prezentace do souboru ve zvoleném formátu s dalšími možnostmi. |
| [save(OutputStream stream, int format, ISaveOptions options)](#save-java.io.OutputStream-int-com.aspose.slides.ISaveOptions-) | Uloží všechny snímky prezentace do proudu ve zvoleném formátu s dalšími možnostmi. |
| [save(String fname, int[] slides, int format)](#save-java.lang.String-int---int-) | Saves specified slides of a presentation to a file with the specified format. |
| [save(String fname, int[] slides, int format, ISaveOptions options)](#save-java.lang.String-int---int-com.aspose.slides.ISaveOptions-) | Saves specified slides of a presentation to a file with the specified format. |
| [save(OutputStream stream, int[] slides, int format)](#save-java.io.OutputStream-int---int-) | Saves specified slides of a presentation to a stream in the specified format. |
| [save(OutputStream stream, int[] slides, int format, ISaveOptions options)](#save-java.io.OutputStream-int---int-com.aspose.slides.ISaveOptions-) | Saves specified slides of a presentation to a stream in the specified format. |
| [save(IXamlOptions options)](#save-com.aspose.slides.IXamlOptions-) | Uloží všechny snímky prezentace do sady souborů představujících XAML markup. |
| [getImages(IRenderingOptions options)](#getImages-com.aspose.slides.IRenderingOptions-) | Vrací miniatury obrázků pro všechny snímky prezentace. |
| [getImages(IRenderingOptions options, int[] slides)](#getImages-com.aspose.slides.IRenderingOptions-int---) | Returns a Thumbnail IImage objects for specified slides of a presentation. |
| [getImages(IRenderingOptions options, float scaleX, float scaleY)](#getImages-com.aspose.slides.IRenderingOptions-float-float-) | Vrací miniatury obrázků pro všechny snímky prezentace s vlastním měřítkem. |
| [getImages(IRenderingOptions options, int[] slides, float scaleX, float scaleY)](#getImages-com.aspose.slides.IRenderingOptions-int---float-float-) | Returns a Thumbnail Image objects for specified slides of a presentation with custom scaling. |
| [getImages(IRenderingOptions options, Dimension imageSize)](#getImages-com.aspose.slides.IRenderingOptions-java.awt.Dimension-) | Vrací miniatury obrázků pro všechny snímky prezentace se specifikovanou velikostí. |
| [getImages(IRenderingOptions options, int[] slides, Dimension imageSize)](#getImages-com.aspose.slides.IRenderingOptions-int---java.awt.Dimension-) | Returns a Thumbnail Image objects for specified slides of a presentation with specified size. |
| [getSlideById(long id)](#getSlideById-long-) | Vrací Slide, MasterSlide nebo LayoutSlide podle Id. |
| [joinPortionsWithSameFormatting()](#joinPortionsWithSameFormatting--) | Spojí běhy se stejným formátováním ve všech odstavcích ve všech akceptovatelných tvarech ve všech snímcích. |
| [highlightText(String text, Color highlightColor)](#highlightText-java.lang.String-java.awt.Color-) | Zvýrazní všechny shody ukázkového textu zadanou barvou. |
| [highlightText(String text, Color highlightColor, ITextSearchOptions options, IFindResultCallback callback)](#highlightText-java.lang.String-java.awt.Color-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-) | Zvýrazní všechny shody ukázkového textu zadanou barvou. |
| [highlightRegex(Pattern regex, Color highlightColor, IFindResultCallback callback)](#highlightRegex-java.util.regex.Pattern-java.awt.Color-com.aspose.slides.IFindResultCallback-) | Zvýrazní všechny shody regulárního výrazu zadanou barvou. |
| [replaceText(String oldText, String newText, ITextSearchOptions options, IFindResultCallback callback)](#replaceText-java.lang.String-java.lang.String-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-) | Nahradí všechny výskyty zadaného textu jiným zadaným textem. |
| [replaceRegex(Pattern regex, String newText, IFindResultCallback callback)](#replaceRegex-java.util.regex.Pattern-java.lang.String-com.aspose.slides.IFindResultCallback-) | Nahradí všechny shody regulárního výrazu zadaným řetězcem. |
| [refreshChartsData()](#refreshChartsData--) | Znovu načte data pro všechny grafy v prezentaci z jejich zdrojových sešitů. |
| [refreshChartsData(boolean skipFailedCharts)](#refreshChartsData-boolean-) | Znovu načte data pro všechny grafy v prezentaci z jejich zdrojových sešitů. |

### getCurrentDateTime() {#getCurrentDateTime--}
```
public abstract Date getCurrentDateTime()
```

Vrací nebo nastavuje datum a čas, který nahradí obsah polí datetime. Čas vytvoření tohoto objektu Presentation je výchozí. Čtení/zápis java.util.Date.

**Vrací:**
java.util.Date

### setCurrentDateTime(Date value) {#setCurrentDateTime-java.util.Date-}
```
public abstract void setCurrentDateTime(Date value)
```

Vrací nebo nastavuje datum a čas, který nahradí obsah polí datetime. Čas vytvoření tohoto objektu Presentation je výchozí. Čtení/zápis java.util.Date.

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.util.Date |  |

### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public abstract IPresentationHeaderFooterManager getHeaderFooterManager()
```

Vrací správce HeaderFooter prezentace. Pouze pro čtení [IPresentationHeaderFooterManager](../../com.aspose.slides/ipresentationheaderfootermanager).

**Vrací:**
[IPresentationHeaderFooterManager](../../com.aspose.slides/ipresentationheaderfootermanager)

### getProtectionManager() {#getProtectionManager--}
```
public abstract IProtectionManager getProtectionManager()
```

Získá správce oprávnění pro tuto prezentaci. Pouze pro čtení [IProtectionManager](../../com.aspose.slides/iprotectionmanager).

**Vrací:**
[IProtectionManager](../../com.aspose.slides/iprotectionmanager)

### getSlides() {#getSlides--}
```
public abstract ISlideCollection getSlides()
```

Vrací seznam všech snímků, které jsou v prezentaci definovány. Pouze pro čtení [ISlideCollection](../../com.aspose.slides/islidecollection).

**Vrací:**
[ISlideCollection](../../com.aspose.slides/islidecollection)

### getSections() {#getSections--}
```
public abstract ISectionCollection getSections()
```

Vrací seznam všech sekcí snímků, které jsou v prezentaci definovány. Pouze pro čtení [ISectionCollection](../../com.aspose.slides/isectioncollection).

**Vrací:**
[ISectionCollection](../../com.aspose.slides/isectioncollection)

### getSlideSize() {#getSlideSize--}
```
public abstract ISlideSize getSlideSize()
```

Vrací objekt velikosti snímku. Pouze pro čtení [ISlideSize](../../com.aspose.slides/islidesize).

**Vrací:**
[ISlideSize](../../com.aspose.slides/islidesize)

### getNotesSize() {#getNotesSize--}
```
public abstract INotesSize getNotesSize()
```

Vrací objekt velikosti poznámkových snímků. Pouze pro čtení [INotesSize](../../com.aspose.slides/inotessize).

**Vrací:**
[INotesSize](../../com.aspose.slides/inotessize)

### getLayoutSlides() {#getLayoutSlides--}
```
public abstract IGlobalLayoutSlideCollection getLayoutSlides()
```

Vrací seznam všech rozložení snímků, které jsou v prezentaci definovány. Pouze pro čtení [IGlobalLayoutSlideCollection](../../com.aspose.slides/igloballayoutslidecollection).

--------------------

Můžete získat alternativní API pro přidávání/vkládání/odstraňování/klonování rozložení snímků pomocí vlastnosti IMasterSlide.LayoutSlides.

**Vrací:**
[IGlobalLayoutSlideCollection](../../com.aspose.slides/igloballayoutslidecollection)

### getMasters() {#getMasters--}
```
public abstract IMasterSlideCollection getMasters()
```

Vrací seznam všech hlavních snímků, které jsou v prezentaci definovány. Pouze pro čtení [IMasterSlideCollection](../../com.aspose.slides/imasterslidecollection).

**Vrací:**
[IMasterSlideCollection](../../com.aspose.slides/imasterslidecollection)

### getMasterNotesSlideManager() {#getMasterNotesSlideManager--}
```
public abstract IMasterNotesSlideManager getMasterNotesSlideManager()
```

Vrací správce hlavních poznámkových snímků. Pouze pro čtení [IMasterNotesSlideManager](../../com.aspose.slides/imasternotesslidemanager).

**Vrací:**
[IMasterNotesSlideManager](../../com.aspose.slides/imasternotesslidemanager)

### getMasterHandoutSlideManager() {#getMasterHandoutSlideManager--}
```
public abstract IMasterHandoutSlideManager getMasterHandoutSlideManager()
```

Vrací správce hlavních výtisků. Pouze pro čtení [IMasterHandoutSlideManager](../../com.aspose.slides/imasterhandoutslidemanager).

**Vrací:**
[IMasterHandoutSlideManager](../../com.aspose.slides/imasterhandoutslidemanager)

### getFontsManager() {#getFontsManager--}
```
public abstract IFontsManager getFontsManager()
```

Vrací správce písem. Pouze pro čtení [IFontsManager](../../com.aspose.slides/ifontsmanager).

**Vrací:**
[IFontsManager](../../com.aspose.slides/ifontsmanager)

### getDefaultTextStyle() {#getDefaultTextStyle--}
```
public abstract ITextStyle getDefaultTextStyle()
```

Vrací výchozí styl textu pro tvary. Pouze pro čtení [ITextStyle](../../com.aspose.slides/itextstyle).

**Vrací:**
[ITextStyle](../../com.aspose.slides/itextstyle)

### getCommentAuthors() {#getCommentAuthors--}
```
public abstract ICommentAuthorCollection getCommentAuthors()
```

Vrací kolekci autorů komentářů. Pouze pro čtení [ICommentAuthorCollection](../../com.aspose.slides/icommentauthorcollection).

**Vrací:**
[ICommentAuthorCollection](../../com.aspose.slides/icommentauthorcollection)

### getDocumentProperties() {#getDocumentProperties--}
```
public abstract IDocumentProperties getDocumentProperties()
```

Vrací objekt DocumentProperties, který obsahuje standardní a vlastní vlastnosti dokumentu. Pouze pro čtení [IDocumentProperties](../../com.aspose.slides/idocumentproperties).

**Vrací:**
[IDocumentProperties](../../com.aspose.slides/idocumentproperties)

### getImages() {#getImages--}
```
public abstract IImageCollection getImages()
```

Vrací kolekci všech obrázků v prezentaci. Pouze pro čtení [IImageCollection](../../com.aspose.slides/iimagecollection).

**Vrací:**
[IImageCollection](../../com.aspose.slides/iimagecollection)

### getAudios() {#getAudios--}
```
public abstract IAudioCollection getAudios()
```

Vrací kolekci všech vložených audio souborů v prezentaci. Pouze pro čtení [IAudioCollection](../../com.aspose.slides/iaudiocollection).

**Vrací:**
[IAudioCollection](../../com.aspose.slides/iaudiocollection)

### getVideos() {#getVideos--}
```
public abstract IVideoCollection getVideos()
```

Vrací kolekci všech vložených video souborů v prezentaci. Pouze pro čtení [IVideoCollection](../../com.aspose.slides/ivideocollection).

**Vrací:**
[IVideoCollection](../../com.aspose.slides/ivideocollection)

### getCustomData() {#getCustomData--}
```
public abstract ICustomData getCustomData()
```

Vrací vlastní data prezentace. Pouze pro čtení [ICustomData](../../com.aspose.slides/icustomdata).

**Vrací:**
[ICustomData](../../com.aspose.slides/icustomdata)

### getVbaProject() {#getVbaProject--}
```
public abstract IVbaProject getVbaProject()
```

Získá projekt VBA s makry prezentace. Čtení/zápis [IVbaProject](../../com.aspose.slides/ivbaproject).

**Vrací:**
[IVbaProject](../../com.aspose.slides/ivbaproject)

### setVbaProject(IVbaProject value) {#setVbaProject-com.aspose.slides.IVbaProject-}
```
public abstract void setVbaProject(IVbaProject value)
```

Získá projekt VBA s makry prezentace. Čtení/zápis [IVbaProject](../../com.aspose.slides/ivbaproject).

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IVbaProject](../../com.aspose.slides/ivbaproject) |  |

### getSourceFormat() {#getSourceFormat--}
```
public abstract int getSourceFormat()
```

Vrací informace o formátu, ze kterého byla prezentace načtena. Pouze pro čtení [SourceFormat](../../com.aspose.slides/sourceformat).

**Vrací:**
int

### getMasterTheme() {#getMasterTheme--}
```
public abstract IMasterTheme getMasterTheme()
```

Vrací hlavní téma prezentace. Pouze pro čtení [IMasterTheme](../../com.aspose.slides/imastertheme).

**Vrací:**
[IMasterTheme](../../com.aspose.slides/imastertheme)

### getHyperlinkQueries() {#getHyperlinkQueries--}
```
public abstract IHyperlinkQueries getHyperlinkQueries()
```

Poskytuje snadný přístup ke všem hypertextovým odkazům obsaženým ve všech snímcích prezentace (ne v hlavních, rozložení, poznámkových snímcích). Pouze pro čtení [IHyperlinkQueries](../../com.aspose.slides/ihyperlinkqueries).

**Vrací:**
[IHyperlinkQueries](../../com.aspose.slides/ihyperlinkqueries)

### getViewProperties() {#getViewProperties--}
```
public abstract IViewProperties getViewProperties()
```

Získá globální vlastnosti zobrazení prezentace. Pouze pro čtení [IViewProperties](../../com.aspose.slides/iviewproperties).

**Vrací:**
[IViewProperties](../../com.aspose.slides/iviewproperties)

### getFirstSlideNumber() {#getFirstSlideNumber--}
```
public abstract int getFirstSlideNumber()
```

Zastupuje první číslo snímku v prezentaci. Čtení/zápis int.

**Vrací:**
int

### setFirstSlideNumber(int value) {#setFirstSlideNumber-int-}
```
public abstract void setFirstSlideNumber(int value)
```

Zastupuje první číslo snímku v prezentaci. Čtení/zápis int.

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getAllCustomXmlParts() {#getAllCustomXmlParts--}
```
public abstract ICustomXmlPart[] getAllCustomXmlParts()
```

Vrací všechny vlastní datové části v prezentaci. Pouze pro čtení ICustomXmlPart[].

**Vrací:**
com.aspose.slides.ICustomXmlPart[]

### getDigitalSignatures() {#getDigitalSignatures--}
```
public abstract IDigitalSignatureCollection getDigitalSignatures()
```

Vrací kolekci podpisů použité k podepsání prezentace. Pouze pro čtení [IDigitalSignatureCollection](../../com.aspose.slides/idigitalsignaturecollection).

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


**Vrací:**
[IDigitalSignatureCollection](../../com.aspose.slides/idigitalsignaturecollection)

### getSensitivityLabels() {#getSensitivityLabels--}
```
public abstract ISensitivityLabelCollection getSensitivityLabels()
```

Vrací kolekci štítků citlivosti aplikovaných na dokument prezentace. Pouze pro čtení [ISensitivityLabelCollection](../../com.aspose.slides/isensitivitylabelcollection).

--------------------

> ```
> Presentation pres = new Presentation("SomePresentation.pptx");
>  try {
>      ISensitivityLabelCollection sensitivityLabels = pres.getSensitivityLabels();
> 
>      // Vytisknout aplikované štítky
>      for (ISensitivityLabel sensitivityLabel : sensitivityLabels)
>          System.out.println("Label Id " + sensitivityLabel.getId() + " from Azure AD site " + sensitivityLabel.getSiteId());
> 
>      // Přidat nový štítek
>      String labelIdString = "{xxxxxxxx-xxxx-xxxx-xxxx-xxxxxxxxxxxx}"; // Získat ID citlivostního štítku z politiky
>      UUID siteIdGuid = UUID.fromString("{xxxxxxxx-xxxx-xxxx-xxxx-xxxxxxxxxxxx}"); // Získat identifikátor Azure AD lokality z politiky
>      ISensitivityLabel label = sensitivityLabels.add(labelIdString, siteIdGuid, true, SensitivityLabelAssignmentType.Privileged);
>      label.getContentMarkTypes().addItem(SensitivityLabelContentType.Footer);
> 
>      pres.save("SensitivityLabel.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Vrací:**
[ISensitivityLabelCollection](../../com.aspose.slides/isensitivitylabelcollection)

### save(String fname, int format) {#save-java.lang.String-int-}
```
public abstract void save(String fname, int format)
```

Uloží všechny snímky prezentace do souboru ve zvoleném formátu.

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| fname | java.lang.String | Path to the created file. |
| format | int | Format of the exported data. |

### save(OutputStream stream, int format) {#save-java.io.OutputStream-int-}
```
public abstract void save(OutputStream stream, int format)
```

Uloží všechny snímky prezentace do proudu ve zvoleném formátu.

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.OutputStream | Output stream. |
| format | int | Format of the exported data. |

### save(String fname, int format, ISaveOptions options) {#save-java.lang.String-int-com.aspose.slides.ISaveOptions-}
```
public abstract void save(String fname, int format, ISaveOptions options)
```
Uloží všechny snímky prezentace do souboru ve zvoleném formátu a s doplňkovými možnostmi.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| fname | java.lang.String | Cesta k vytvořenému souboru. |
| format | int | Formát exportovaných dat. |
| options | [ISaveOptions](../../com.aspose.slides/isaveoptions) | Dodatečné volby formátu. |

### save(OutputStream stream, int format, ISaveOptions options) {#save-java.io.OutputStream-int-com.aspose.slides.ISaveOptions-}
```
public abstract void save(OutputStream stream, int format, ISaveOptions options)
```

Uloží všechny snímky prezentace do proudu ve zvoleném formátu a s doplňkovými možnostmi.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| stream | java.io.OutputStream | Výstupní proud. |
| format | int | Formát exportovaných dat. |
| options | [ISaveOptions](../../com.aspose.slides/isaveoptions) | Dodatečné volby formátu. |

### save(String fname, int[] slides, int format) {#save-java.lang.String-int---int-}
```
public abstract void save(String fname, int[] slides, int format)
```

Uloží zadané snímky prezentace do souboru ve zvoleném formátu.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| fname | java.lang.String | Cesta k vytvořenému souboru. |
| slides | int[] | Pole s pozicemi snímků, počítáno od 1. |
| format | int | Formát exportovaných dat. |

### save(String fname, int[] slides, int format, ISaveOptions options) {#save-java.lang.String-int---int-com.aspose.slides.ISaveOptions-}
```
public abstract void save(String fname, int[] slides, int format, ISaveOptions options)
```

Uloží zadané snímky prezentace do souboru ve zvoleném formátu.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| fname | java.lang.String | Cesta k vytvořenému souboru. |
| slides | int[] | Pole s pozicemi snímků, počítáno od 1. |
| format | int | Formát exportovaných dat. |
| options | [ISaveOptions](../../com.aspose.slides/isaveoptions) | Dodatečné volby formátu. |

### save(OutputStream stream, int[] slides, int format) {#save-java.io.OutputStream-int---int-}
```
public abstract void save(OutputStream stream, int[] slides, int format)
```

Uloží zadané snímky prezentace do proudu ve zvoleném formátu.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| stream | java.io.OutputStream | Výstupní proud. |
| slides | int[] | Pole s pozicemi snímků, počítáno od 1. |
| format | int | Formát exportovaných dat. |

### save(OutputStream stream, int[] slides, int format, ISaveOptions options) {#save-java.io.OutputStream-int---int-com.aspose.slides.ISaveOptions-}
```
public abstract void save(OutputStream stream, int[] slides, int format, ISaveOptions options)
```

Uloží zadané snímky prezentace do proudu ve zvoleném formátu.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| stream | java.io.OutputStream | Výstupní proud. |
| slides | int[] | Pole s pozicemi snímků, počítáno od 1. |
| format | int | Formát exportovaných dat. |
| options | [ISaveOptions](../../com.aspose.slides/isaveoptions) | Dodatečné volby formátu. |

### save(IXamlOptions options) {#save-com.aspose.slides.IXamlOptions-}
```
public abstract void save(IXamlOptions options)
```

Uloží všechny snímky prezentace do sady souborů představujících XAML značkování.

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

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| options | [IXamlOptions](../../com.aspose.slides/ixamloptions) | Možnosti formátu XAML. |

### getImages(IRenderingOptions options) {#getImages-com.aspose.slides.IRenderingOptions-}
```
public abstract IImage[] getImages(IRenderingOptions options)
```

Vrací objekty náhledových obrázků pro všechny snímky prezentace.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Možnosti renderování. |

**Vrací:**
com.aspose.slides.IImage[] - IImage objects.

### getImages(IRenderingOptions options, int[] slides) {#getImages-com.aspose.slides.IRenderingOptions-int---}
```
public abstract IImage[] getImages(IRenderingOptions options, int[] slides)
```

Vrací objekty náhledových obrázků pro zadané snímky prezentace.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Možnosti renderování. |
| slides | int[] | Pole s pozicemi snímků, počítáno od 1. |

**Vrací:**
com.aspose.slides.IImage[] - IImage objects.

### getImages(IRenderingOptions options, float scaleX, float scaleY) {#getImages-com.aspose.slides.IRenderingOptions-float-float-}
```
public abstract IImage[] getImages(IRenderingOptions options, float scaleX, float scaleY)
```

Vrací objekty náhledových obrázků pro všechny snímky prezentace s vlastní měřítkem.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Možnosti renderování. |
| scaleX | float | Hodnota, o kterou se má tento náhled škálovat ve směru osy x. |
| scaleY | float | Hodnota, o kterou se má tento náhled škálovat ve směru osy y. |

**Vrací:**
com.aspose.slides.IImage[] - Bitmap objects.

### getImages(IRenderingOptions options, int[] slides, float scaleX, float scaleY) {#getImages-com.aspose.slides.IRenderingOptions-int---float-float-}
```
public abstract IImage[] getImages(IRenderingOptions options, int[] slides, float scaleX, float scaleY)
```

Vrací objekty náhledových obrázků pro zadané snímky prezentace s vlastní měřítkem.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Možnosti renderování. |
| slides | int[] | Pole s pozicemi snímků, počítáno od 1. |
| scaleX | float | Hodnota, o kterou se má tento náhled škálovat ve směru osy x. |
| scaleY | float | Hodnota, o kterou se má tento náhled škálovat ve směru osy y. |

**Vrací:**
com.aspose.slides.IImage[] - IImage objects.

### getImages(IRenderingOptions options, Dimension imageSize) {#getImages-com.aspose.slides.IRenderingOptions-java.awt.Dimension-}
```
public abstract IImage[] getImages(IRenderingOptions options, Dimension imageSize)
```

Vrací objekty náhledových obrázků pro všechny snímky prezentace se specifikovanou velikostí.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Možnosti renderování. |
| imageSize | java.awt.Dimension | Velikost vytvářeného obrázku. |

**Vrací:**
com.aspose.slides.IImage[] - IImage objects.

### getImages(IRenderingOptions options, int[] slides, Dimension imageSize) {#getImages-com.aspose.slides.IRenderingOptions-int---java.awt.Dimension-}
```
public abstract IImage[] getImages(IRenderingOptions options, int[] slides, Dimension imageSize)
```

Vrací objekty náhledových obrázků pro zadané snímky prezentace se specifikovanou velikostí.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Možnosti renderování. |
| slides | int[] | Pole s pozicemi snímků, počítáno od 1. |
| imageSize | java.awt.Dimension | Velikost vytvářeného obrázku. |

**Vrací:**
com.aspose.slides.IImage[] - IImage objects.

### getSlideById(long id) {#getSlideById-long-}
```
public abstract IBaseSlide getSlideById(long id)
```

Vrací Slide, MasterSlide nebo LayoutSlide podle Id.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| id | long | Id snímku. |

**Vrací:**
[IBaseSlide](../../com.aspose.slides/ibaseslide) - IBaseSlide object.

### joinPortionsWithSameFormatting() {#joinPortionsWithSameFormatting--}
```
public abstract void joinPortionsWithSameFormatting()
```

Spojí běhy se stejným formátováním ve všech odstavcích ve všech podporovaných tvarech ve všech snímcích.

### highlightText(String text, Color highlightColor) {#highlightText-java.lang.String-java.awt.Color-}
```
public abstract void highlightText(String text, Color highlightColor)
```

Zvýrazní všechny výskyty vzorového textu zadanou barvou.

--------------------

> ```
> The following code sample shows how to highlight text in a PowerPoint presentation.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      // zvýraznění všech samostatných výskytů 'the'
>      presentation.highlightText("the", Color.MAGENTA);
>      presentation.save("SomePresentation-out2.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| text | java.lang.String | Text, který se má zvýraznit. |
| highlightColor | java.awt.Color | Barva pro zvýraznění textu. |

### highlightText(String text, Color highlightColor, ITextSearchOptions options, IFindResultCallback callback) {#highlightText-java.lang.String-java.awt.Color-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-}
```
public abstract void highlightText(String text, Color highlightColor, ITextSearchOptions options, IFindResultCallback callback)
```

Zvýrazní všechny výskyty vzorového textu zadanou barvou.

--------------------

> ```
> The following code sample shows how to highlight text in a PowerPoint presentation.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      // zvýraznění všech samostatných výskytů 'the'
>      presentation.highlightText("the", Color.MAGENTA);
>      presentation.save("SomePresentation-out2.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| text | java.lang.String | Text, který se má zvýraznit. |
| highlightColor | java.awt.Color | Barva pro zvýraznění textu. |
| options | [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions) | Možnosti vyhledávání textu [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions). |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | Objekt zpětného volání pro přijímání výsledků vyhledávání [IFindResultCallback](../../com.aspose.slides/ifindresultcallback). |

### highlightRegex(Pattern regex, Color highlightColor, IFindResultCallback callback) {#highlightRegex-java.util.regex.Pattern-java.awt.Color-com.aspose.slides.IFindResultCallback-}
```
public abstract void highlightRegex(Pattern regex, Color highlightColor, IFindResultCallback callback)
```

Zvýrazní všechny výskyty regulárního výrazu zadanou barvou.

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

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| regex | java.util.regex.Pattern | Regulární výraz java.util.regex.Pattern pro získání řetězců k zvýraznění. |
| highlightColor | java.awt.Color | Barva pro zvýraznění textu. |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | Objekt zpětného volání pro přijímání výsledků vyhledávání [IFindResultCallback](../../com.aspose.slides/ifindresultcallback). |

### replaceText(String oldText, String newText, ITextSearchOptions options, IFindResultCallback callback) {#replaceText-java.lang.String-java.lang.String-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-}
```
public abstract void replaceText(String oldText, String newText, ITextSearchOptions options, IFindResultCallback callback)
```

Nahradí všechny výskyty zadaného textu jiným zadaným textem.

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

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| oldText | java.lang.String | Řetězec, který se má nahradit. |
| newText | java.lang.String | Řetězec, kterým se nahradí všechny výskyty oldText. |
| options | [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions) | Možnosti vyhledávání textu [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions). |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | Objekt zpětného volání pro přijímání výsledků vyhledávání [IFindResultCallback](../../com.aspose.slides/ifindresultcallback). |

### replaceRegex(Pattern regex, String newText, IFindResultCallback callback) {#replaceRegex-java.util.regex.Pattern-java.lang.String-com.aspose.slides.IFindResultCallback-}
```
public abstract void replaceRegex(Pattern regex, String newText, IFindResultCallback callback)
```

Nahradí všechny výskyty regulárního výrazu zadaným řetězcem.

--------------------

> ```
> The following code sample shows how to replace text using regular expression with the specified string.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx")
>  try {
>      TextSearchOptions textSearchOptions = new TextSearchOptions();
>      textSearchOptions.setWholeWordsOnly(true);
>      // Nahrazení všech samostatných výskytů 'the' řetězcem '***'
>      presentation.replaceText("the", "***", textSearchOptions, null);
>      presentation.save("SomePresentation-out2.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| regex | java.util.regex.Pattern | Regulární výraz java.util.regex.Pattern pro získání řetězců k nahrazení. |
| newText | java.lang.String | Řetězec, kterým se nahradí všechny výskyty řetězců k nahrazení. |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | Objekt zpětného volání pro přijímání výsledků vyhledávání [IFindResultCallback](../../com.aspose.slides/ifindresultcallback). |

### refreshChartsData() {#refreshChartsData--}
```
public abstract void refreshChartsData()
```

Znovu načte data pro všechny grafy v prezentaci ze zdrojových sešitů.

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

Znovu načte data pro všechny grafy v prezentaci ze zdrojových sešitů.

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

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| skipFailedCharts | boolean | Určuje, zda proces obnovení pokračuje, pokud graf selže při aktualizaci. Pokud je true, grafy způsobující výjimku jsou přeskočeny; jinak je výjimka propagována. |