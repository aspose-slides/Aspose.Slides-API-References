---
title: IPresentation
second_title: Aspose.Slides pro Android přes Java API Reference
description: Dokument prezentace
type: docs
url: /cs/com.aspose.slides/ipresentation/
---
**All Implemented Interfaces:**  
[com.aspose.slides.IPresentationComponent](../../com.aspose.slides/ipresentationcomponent), com.aspose.ms.System.IDisposable
```
public interface IPresentation extends IPresentationComponent, System.IDisposable
```

Dokument prezentace
## Metody

| Metoda | Popis |
| --- | --- |
| [getCurrentDateTime()](#getCurrentDateTime--) | Vrací nebo nastavuje datum a čas, který nahradí obsah polí datum/čas. |
| [setCurrentDateTime(Date value)](#setCurrentDateTime-java.util.Date-) | Vrací nebo nastavuje datum a čas, který nahradí obsah polí datum/čas. |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | Vrací správce HeaderFooter prezentace. |
| [getProtectionManager()](#getProtectionManager--) | Vrací správce oprávnění pro tuto prezentaci. |
| [getSlides()](#getSlides--) | Vrací seznam všech snímků, které jsou definovány v prezentaci. |
| [getSections()](#getSections--) | Vrací seznam všech oddílů snímků, které jsou definovány v prezentaci. |
| [getSlideSize()](#getSlideSize--) | Vrací objekt velikosti snímku. |
| [getNotesSize()](#getNotesSize--) | Vrací objekt velikosti poznámkového snímku. |
| [getLayoutSlides()](#getLayoutSlides--) | Vrací seznam všech rozložení snímků, které jsou definovány v prezentaci. |
| [getMasters()](#getMasters--) | Vrací seznam všech hlavních snímků, které jsou definovány v prezentaci. |
| [getMasterNotesSlideManager()](#getMasterNotesSlideManager--) | Vrací správce hlavních poznámek. |
| [getMasterHandoutSlideManager()](#getMasterHandoutSlideManager--) | Vrací správce hlavních výtisků. |
| [getFontsManager()](#getFontsManager--) | Vrací správce písem. |
| [getDefaultTextStyle()](#getDefaultTextStyle--) | Vrací výchozí styl textu pro tvary. |
| [getCommentAuthors()](#getCommentAuthors--) | Vrací kolekci autorů komentářů. |
| [getDocumentProperties()](#getDocumentProperties--) | Vrací objekt DocumentProperties, který obsahuje standardní a vlastní vlastnosti dokumentu. |
| [getImages()](#getImages--) | Vrací kolekci všech obrázků v prezentaci. |
| [getAudios()](#getAudios--) | Vrací kolekci všech vložených zvukových souborů v prezentaci. |
| [getVideos()](#getVideos--) | Vrací kolekci všech vložených video souborů v prezentaci. |
| [getCustomData()](#getCustomData--) | Vrací vlastní data prezentace. |
| [getVbaProject()](#getVbaProject--) | Vrací VBA projekt s makry prezentace. |
| [setVbaProject(IVbaProject value)](#setVbaProject-com.aspose.slides.IVbaProject-) | Vrací VBA projekt s makry prezentace. |
| [getSourceFormat()](#getSourceFormat--) | Vrací informaci o formátu, ze kterého byla prezentace načtena. |
| [getMasterTheme()](#getMasterTheme--) | Vrací hlavní motiv prezentace. |
| [getHyperlinkQueries()](#getHyperlinkQueries--) | Poskytuje snadný přístup ke všem hypertextovým odkazům obsaženým ve všech snímcích prezentace (ne v hlavních, rozložení nebo poznámkových snímcích). |
| [getViewProperties()](#getViewProperties--) | Vrací celkové vlastnosti zobrazení prezentace. |
| [getFirstSlideNumber()](#getFirstSlideNumber--) | Reprezentuje číslo prvního snímku v prezentaci. |
| [setFirstSlideNumber(int value)](#setFirstSlideNumber-int-) | Reprezentuje číslo prvního snímku v prezentaci. |
| [getAllCustomXmlParts()](#getAllCustomXmlParts--) | Vrací všechny vlastní části dat v prezentaci. |
| [getDigitalSignatures()](#getDigitalSignatures--) | Vrací kolekci podpisů použité k podepsání prezentace. |
| [getSensitivityLabels()](#getSensitivityLabels--) | Vrací kolekci štítků citlivosti aplikovaných na dokument prezentace. |
| [save(String fname, int format)](#save-java.lang.String-int-) | Ukládá všechny snímky prezentace do souboru ve zvoleném formátu. |
| [save(OutputStream stream, int format)](#save-java.io.OutputStream-int-) | Ukládá všechny snímky prezentace do proudu ve zvoleném formátu. |
| [save(String fname, int format, ISaveOptions options)](#save-java.lang.String-int-com.aspose.slides.ISaveOptions-) | Ukládá všechny snímky prezentace do souboru ve zvoleném formátu s dodatečnými možnostmi. |
| [save(OutputStream stream, int format, ISaveOptions options)](#save-java.io.OutputStream-int-com.aspose.slides.ISaveOptions-) | Ukládá všechny snímky prezentace do proudu ve zvoleném formátu s dodatečnými možnostmi. |
| [save(String fname, int[] slides, int format)](#save-java.lang.String-int---int-) | Ukládá určené snímky prezentace do souboru ve zvoleném formátu. |
| [save(String fname, int[] slides, int format, ISaveOptions options)](#save-java.lang.String-int---int-com.aspose.slides.ISaveOptions-) | Ukládá určené snímky prezentace do souboru ve zvoleném formátu. |
| [save(OutputStream stream, int[] slides, int format)](#save-java.io.OutputStream-int---int-) | Ukládá určené snímky prezentace do proudu ve zvoleném formátu. |
| [save(OutputStream stream, int[] slides, int format, ISaveOptions options)](#save-java.io.OutputStream-int---int-com.aspose.slides.ISaveOptions-) | Ukládá určené snímky prezentace do proudu ve zvoleném formátu. |
| [save(IXamlOptions options)](#save-com.aspose.slides.IXamlOptions-) | Ukládá všechny snímky prezentace do sady souborů představujících XAML markup. |
| [getImages(IRenderingOptions options)](#getImages-com.aspose.slides.IRenderingOptions-) | Vrací objekty Miniatury obrázku pro všechny snímky prezentace. |
| [getImages(IRenderingOptions options, int[] slides)](#getImages-com.aspose.slides.IRenderingOptions-int---) | Vrací objekty Miniatury IImage pro určené snímky prezentace. |
| [getImages(IRenderingOptions options, float scaleX, float scaleY)](#getImages-com.aspose.slides.IRenderingOptions-float-float-) | Vrací objekty Miniatury obrázku pro všechny snímky prezentace s vlastním měřítkem. |
| [getImages(IRenderingOptions options, int[] slides, float scaleX, float scaleY)](#getImages-com.aspose.slides.IRenderingOptions-int---float-float-) | Vrací objekty Miniatury obrázku pro určené snímky prezentace s vlastním měřítkem. |
| [getImages(IRenderingOptions options, Size imageSize)](#getImages-com.aspose.slides.IRenderingOptions-com.aspose.slides.android.Size-) | Vrací objekty Miniatury obrázku pro všechny snímky prezentace se zadanou velikostí. |
| [getImages(IRenderingOptions options, int[] slides, Size imageSize)](#getImages-com.aspose.slides.IRenderingOptions-int---com.aspose.slides.android.Size-) | Vrací objekty Miniatury obrázku pro určené snímky prezentace se zadanou velikostí. |
| [getSlideById(long id)](#getSlideById-long-) | Vrací Slide, MasterSlide nebo LayoutSlide podle Id. |
| [joinPortionsWithSameFormatting()](#joinPortionsWithSameFormatting--) | Spojuje úseky se stejným formátováním ve všech odstavcích ve všech vhodných tvarech ve všech snímcích. |
| [highlightText(String text, Integer highlightColor)](#highlightText-java.lang.String-java.lang.Integer-) | Zvýrazní všechny shody ukázkového textu zadanou barvou. |
| [highlightText(String text, Integer highlightColor, ITextSearchOptions options, IFindResultCallback callback)](#highlightText-java.lang.String-java.lang.Integer-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-) | Zvýrazní všechny shody ukázkového textu zadanou barvou. |
| [highlightRegex(Pattern regex, Integer highlightColor, IFindResultCallback callback)](#highlightRegex-java.util.regex.Pattern-java.lang.Integer-com.aspose.slides.IFindResultCallback-) | Zvýrazní všechny shody regulárního výrazu zadanou barvou. |
| [replaceText(String oldText, String newText, ITextSearchOptions options, IFindResultCallback callback)](#replaceText-java.lang.String-java.lang.String-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-) | Nahrazuje všechny výskyty zadaného textu jiným zadaným textem. |
| [replaceRegex(Pattern regex, String newText, IFindResultCallback callback)](#replaceRegex-java.util.regex.Pattern-java.lang.String-com.aspose.slides.IFindResultCallback-) | Nahrazuje všechny shody regulárního výrazu zadaným řetězcem. |

### getCurrentDateTime() {#getCurrentDateTime--}
```
public abstract Date getCurrentDateTime()
```

**Vrací nebo nastavuje datum a čas, který nahradí obsah polí datum/čas.** Výchozí je čas vytvoření tohoto objektu Presentation. **Čtení/Zápis** `java.util.Date`.

**Vrací:**
`java.util.Date`

### setCurrentDateTime(Date value) {#setCurrentDateTime-java.util.Date-}
```
public abstract void setCurrentDateTime(Date value)
```

**Vrací nebo nastavuje datum a čas, který nahradí obsah polí datum/čas.** Výchozí je čas vytvoření tohoto objektu Presentation. **Čtení/Zápis** `java.util.Date`.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | `java.util.Date` |  |

### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public abstract IPresentationHeaderFooterManager getHeaderFooterManager()
```

**Vrací správce HeaderFooter prezentace.** **Pouze ke čtení** [IPresentationHeaderFooterManager](../../com.aspose.slides/ipresentationheaderfootermanager).

**Vrací:**
[IPresentationHeaderFooterManager](../../com.aspose.slides/ipresentationheaderfootermanager)

### getProtectionManager() {#getProtectionManager--}
```
public abstract IProtectionManager getProtectionManager()
```

**Vrací správce oprávnění pro tuto prezentaci.** **Pouze ke čtení** [IProtectionManager](../../com.aspose.slides/iprotectionmanager).

**Vrací:**
[IProtectionManager](../../com.aspose.slides/iprotectionmanager)

### getSlides() {#getSlides--}
```
public abstract ISlideCollection getSlides()
```

**Vrací seznam všech snímků, které jsou definovány v prezentaci.** **Pouze ke čtení** [ISlideCollection](../../com.aspose.slides/islidecollection).

**Vrací:**
[ISlideCollection](../../com.aspose.slides/islidecollection)

### getSections() {#getSections--}
```
public abstract ISectionCollection getSections()
```

**Vrací seznam všech oddílů snímků, které jsou definovány v prezentaci.** **Pouze ke čtení** [ISectionCollection](../../com.aspose.slides/isectioncollection).

**Vrací:**
[ISectionCollection](../../com.aspose.slides/isectioncollection)

### getSlideSize() {#getSlideSize--}
```
public abstract ISlideSize getSlideSize()
```

**Vrací objekt velikosti snímku.** **Pouze ke čtení** [ISlideSize](../../com.aspose.slides/islidesize).

**Vrací:**
[ISlideSize](../../com.aspose.slides/islidesize)

### getNotesSize() {#getNotesSize--}
```
public abstract INotesSize getNotesSize()
```

**Vrací objekt velikosti poznámkového snímku.** **Pouze ke čtení** [INotesSize](../../com.aspose.slides/inotessize).

**Vrací:**
[INotesSize](../../com.aspose.slides/inotessize)

### getLayoutSlides() {#getLayoutSlides--}
```
public abstract IGlobalLayoutSlideCollection getLayoutSlides()
```

**Vrací seznam všech rozložení snímků, které jsou definovány v prezentaci.** **Pouze ke čtení** [IGlobalLayoutSlideCollection](../../com.aspose.slides/igloballayoutslidecollection).

--------------------

Můžete použít alternativní API pro přidávání/vkládání/odstraňování/klonování rozložení snímků pomocí vlastnosti `IMasterSlide.LayoutSlides`.

**Vrací:**
[IGlobalLayoutSlideCollection](../../com.aspose.slides/igloballayoutslidecollection)

### getMasters() {#getMasters--}
```
public abstract IMasterSlideCollection getMasters()
```

**Vrací seznam všech hlavních snímků, které jsou definovány v prezentaci.** **Pouze ke čtení** [IMasterSlideCollection](../../com.aspose.slides/imasterslidecollection).

**Vrací:**
[IMasterSlideCollection](../../com.aspose.slides/imasterslidecollection)

### getMasterNotesSlideManager() {#getMasterNotesSlideManager--}
```
public abstract IMasterNotesSlideManager getMasterNotesSlideManager()
```

**Vrací správce hlavních poznámek.** **Pouze ke čtení** [IMasterNotesSlideManager](../../com.aspose.slides/imasternotesslidemanager).

**Vrací:**
[IMasterNotesSlideManager](../../com.aspose.slides/imasternotesslidemanager)

### getMasterHandoutSlideManager() {#getMasterHandoutSlideManager--}
```
public abstract IMasterHandoutSlideManager getMasterHandoutSlideManager()
```

**Vrací správce hlavních výtisků.** **Pouze ke čtení** [IMasterHandoutSlideManager](../../com.aspose.slides/imasterhandoutslidemanager).

**Vrací:**
[IMasterHandoutSlideManager](../../com.aspose.slides/imasterhandoutslidemanager)

### getFontsManager() {#getFontsManager--}
```
public abstract IFontsManager getFontsManager()
```

**Vrací správce písem.** **Pouze ke čtení** [IFontsManager](../../com.aspose.slides/ifontsmanager).

**Vrací:**
[IFontsManager](../../com.aspose.slides/ifontsmanager)

### getDefaultTextStyle() {#getDefaultTextStyle--}
```
public abstract ITextStyle getDefaultTextStyle()
```

**Vrací výchozí styl textu pro tvary.** **Pouze ke čtení** [ITextStyle](../../com.aspose.slides/itextstyle).

**Vrací:**
[ITextStyle](../../com.aspose.slides/itextstyle)

### getCommentAuthors() {#getCommentAuthors--}
```
public abstract ICommentAuthorCollection getCommentAuthors()
```

**Vrací kolekci autorů komentářů.** **Pouze ke čtení** [ICommentAuthorCollection](../../com.aspose.slides/icommentauthorcollection).

**Vrací:**
[ICommentAuthorCollection](../../com.aspose.slides/icommentauthorcollection)

### getDocumentProperties() {#getDocumentProperties--}
```
public abstract IDocumentProperties getDocumentProperties()
```

**Vrací objekt DocumentProperties, který obsahuje standardní a vlastní vlastnosti dokumentu.** **Pouze ke čtení** [IDocumentProperties](../../com.aspose.slides/idocumentproperties).

**Vrací:**
[IDocumentProperties](../../com.aspose.slides/idocumentproperties)

### getImages() {#getImages--}
```
public abstract IImageCollection getImages()
```

**Vrací kolekci všech obrázků v prezentaci.** **Pouze ke čtení** [IImageCollection](../../com.aspose.slides/iimagecollection).

**Vrací:**
[IImageCollection](../../com.aspose.slides/iimagecollection)

### getAudios() {#getAudios--}
```
public abstract IAudioCollection getAudios()
```

**Vrací kolekci všech vložených zvukových souborů v prezentaci.** **Pouze ke čtení** [IAudioCollection](../../com.aspose.slides/iaudiocollection).

**Vrací:**
[IAudioCollection](../../com.aspose.slides/iaudiocollection)

### getVideos() {#getVideos--}
```
public abstract IVideoCollection getVideos()
```

**Vrací kolekci všech vložených video souborů v prezentaci.** **Pouze ke čtení** [IVideoCollection](../../com.aspose.slides/ivideocollection).

**Vrací:**
[IVideoCollection](../../com.aspose.slides/ivideocollection)

### getCustomData() {#getCustomData--}
```
public abstract ICustomData getCustomData()
```

**Vrací vlastní data prezentace.** **Pouze ke čtení** [ICustomData](../../com.aspose.slides/icustomdata).

**Vrací:**
[ICustomData](../../com.aspose.slides/icustomdata)

### getVbaProject() {#getVbaProject--}
```
public abstract IVbaProject getVbaProject()
```

**Vrací VBA projekt s makry prezentace.** **Čtení/Zápis** [IVbaProject](../../com.aspose.slides/ivbaproject).

**Vrací:**
[IVbaProject](../../com.aspose.slides/ivbaproject)

### setVbaProject(IVbaProject value) {#setVbaProject-com.aspose.slides.IVbaProject-}
```
public abstract void setVbaProject(IVbaProject value)
```

**Vrací VBA projekt s makry prezentace.** **Čtení/Zápis** [IVbaProject](../../com.aspose.slides/ivbaproject).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | [IVbaProject](../../com.aspose.slides/ivbaproject) |  |

### getSourceFormat() {#getSourceFormat--}
```
public abstract int getSourceFormat()
```

**Vrací informaci o formátu, ze kterého byla prezentace načtena.** **Pouze ke čtení** [SourceFormat](../../com.aspose.slides/sourceformat).

**Vrací:**
`int`

### getMasterTheme() {#getMasterTheme--}
```
public abstract IMasterTheme getMasterTheme()
```

**Vrací hlavní motiv prezentace.** **Pouze ke čtení** [IMasterTheme](../../com.aspose.slides/imastertheme).

**Vrací:**
[IMasterTheme](../../com.aspose.slides/imastertheme)

### getHyperlinkQueries() {#getHyperlinkQueries--}
```
public abstract IHyperlinkQueries getHyperlinkQueries()
```

**Poskytuje snadný přístup ke všem hypertextovým odkazům obsaženým ve všech snímcích prezentace (ne v hlavních, rozložení nebo poznámkových snímcích).** **Pouze ke čtení** [IHyperlinkQueries](../../com.aspose.slides/ihyperlinkqueries).

**Vrací:**
[IHyperlinkQueries](../../com.aspose.slides/ihyperlinkqueries)

### getViewProperties() {#getViewProperties--}
```
public abstract IViewProperties getViewProperties()
```

**Vrací celkové vlastnosti zobrazení prezentace.** **Pouze ke čtení** [IViewProperties](../../com.aspose.slides/iviewproperties).

**Vrací:**
[IViewProperties](../../com.aspose.slides/iviewproperties)

### getFirstSlideNumber() {#getFirstSlideNumber--}
```
public abstract int getFirstSlideNumber()
```

**Reprezentuje číslo prvního snímku v prezentaci.** **Čtení/Zápis** `int`.

**Vrací:**
`int`

### setFirstSlideNumber(int value) {#setFirstSlideNumber-int-}
```
public abstract void setFirstSlideNumber(int value)
```

**Reprezentuje číslo prvního snímku v prezentaci.** **Čtení/Zápis** `int`.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | `int` |  |

### getAllCustomXmlParts() {#getAllCustomXmlParts--}
```
public abstract ICustomXmlPart[] getAllCustomXmlParts()
```

**Vrací všechny vlastní části dat v prezentaci.** **Pouze ke čtení** `ICustomXmlPart[]`.

**Vrací:**
`com.aspose.slides.ICustomXmlPart[]`

### getDigitalSignatures() {#getDigitalSignatures--}
```
public abstract IDigitalSignatureCollection getDigitalSignatures()
```

**Vrací kolekci podpisů použitých k podepsání prezentace.** **Pouze ke čtení** [IDigitalSignatureCollection](../../com.aspose.slides/idigitalsignaturecollection).

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

**Vrací kolekci štítků citlivosti aplikovaných na dokument prezentace.** **Pouze ke čtení** [ISensitivityLabelCollection](../../com.aspose.slides/isensitivitylabelcollection).

--------------------

> ```
> Presentation pres = new Presentation("SomePresentation.pptx");
>  try {
>      ISensitivityLabelCollection sensitivityLabels = pres.getSensitivityLabels();
> 
>      // Vytiskne použité štítky
>      for (ISensitivityLabel sensitivityLabel : sensitivityLabels)
>          System.out.println("Label Id " + sensitivityLabel.getId() + " from Azure AD site " + sensitivityLabel.getSiteId());
> 
>      // Přidá nový štítek
>      String labelIdString = "{xxxxxxxx-xxxx-xxxx-xxxx-xxxxxxxxxxxx}"; // Získá Id štítku citlivosti ze zásady
>      UUID siteIdGuid = UUID.fromString("{xxxxxxxx-xxxx-xxxx-xxxx-xxxxxxxxxxxx}"); // Získá identifikátor Azure AD webu ze zásady
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

**Ukládá všechny snímky prezentace do souboru ve zvoleném formátu.**

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| fname | `java.lang.String` | Cesta k vytvořenému souboru. |
| format | `int` | Formát exportovaných dat. |

### save(OutputStream stream, int format) {#save-java.io.OutputStream-int-}
```
public abstract void save(OutputStream stream, int format)
```

**Ukládá všechny snímky prezentace do proudu ve zvoleném formátu.**

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| stream | `java.io.OutputStream` | Výstupní proud. |
| format | `int` | Formát exportovaných dat. |

### save(String fname, int format, ISaveOptions options) {#save-java.lang.String-int-com.aspose.slides.ISaveOptions-}
```
public abstract void save(String fname, int format, ISaveOptions options)
```

**Ukládá všechny snímky prezentace do souboru ve zvoleném formátu s dodatečnými možnostmi.**

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| fname | `java.lang.String` | Cesta k vytvořenému souboru. |
| format | `int` | Formát exportovaných dat. |
| options | [ISaveOptions](../../com.aspose.slides/isaveoptions) | Dodatečné možnosti formátu. |

### save(OutputStream stream, int format, ISaveOptions options) {#save-java.io.OutputStream-int-com.aspose.slides.ISaveOptions-}
```
public abstract void save(OutputStream stream, int format, ISaveOptions options)
```

**Ukládá všechny snímky prezentace do proudu ve zvoleném formátu s dodatečnými možnostmi.**

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| stream | `java.io.OutputStream` | Výstupní proud. |
| format | `int` | Formát exportovaných dat. |
| options | [ISaveOptions](../../com.aspose.slides/isaveoptions) | Dodatečné možnosti formátu. |

### save(String fname, int[] slides, int format) {#save-java.lang.String-int---int-}
```
public abstract void save(String fname, int[] slides, int format)
```

**Ukládá určené snímky prezentace do souboru ve zvoleném formátu.**

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| fname | `java.lang.String` | Cesta k vytvořenému souboru. |
| slides | `int[]` | Pole s pozicemi snímků, počínaje 1. |
| format | `int` | Formát exportovaných dat. |

### save(String fname, int[] slides, int format, ISaveOptions options) {#save-java.lang.String-int---int-com.aspose.slides.ISaveOptions-}
```
public abstract void save(String fname, int[] slides, int format, ISaveOptions options)
```

**Ukládá určené snímky prezentace do souboru ve zvoleném formátu.**

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| fname | `java.lang.String` | Cesta k vytvořenému souboru. |
| slides | `int[]` | Pole s pozicemi snímků, počínaje 1. |
| format | `int` | Formát exportovaných dat. |
| options | [ISaveOptions](../../com.aspose.slides/isaveoptions) | Dodatečné možnosti formátu. |

### save(OutputStream stream, int[] slides, int format) {#save-java.io.OutputStream-int---int-}
```
public abstract void save(OutputStream stream, int[] slides, int format)
```

**Ukládá určené snímky prezentace do proudu ve zvoleném formátu.**

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| stream | `java.io.OutputStream` | Výstupní proud. |
| slides | `int[]` | Pole s pozicemi snímků, počínaje 1. |
| format | `int` | Formát exportovaných dat. |

### save(OutputStream stream, int[] slides, int format, ISaveOptions options) {#save-java.io.OutputStream-int---int-com.aspose.slides.ISaveOptions-}
```
public abstract void save(OutputStream stream, int[] slides, int format, ISaveOptions options)
```

**Ukládá určené snímky prezentace do proudu ve zvoleném formátu.**

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| stream | `java.io.OutputStream` | Výstupní proud. |
| slides | `int[]` | Pole s pozicemi snímků, počínaje 1. |
| format | `int` | Formát exportovaných dat. |
| options | [ISaveOptions](../../com.aspose.slides/isaveoptions) | Dodatečné možnosti formátu. |

### save(IXamlOptions options) {#save-com.aspose.slides.IXamlOptions-}
```
public abstract void save(IXamlOptions options)
```

**Ukládá všechny snímky prezentace do sady souborů představujících XAML markup.**

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

**Vrací objekty Miniatury Image pro všechny snímky prezentace.**

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Možnosti renderování. |

**Vrací:**
`com.aspose.slides.IImage[]` – objekty IImage.

### getImages(IRenderingOptions options, int[] slides) {#getImages-com.aspose.slides.IRenderingOptions-int---}
```
public abstract IImage[] getImages(IRenderingOptions options, int[] slides)
```

**Vrací objekty Miniatury IImage pro určené snímky prezentace.**

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Možnosti renderování. |
| slides | `int[]` | Pole s pozicemi snímků, počínaje 1. |

**Vrací:**
`com.aspose.slides.IImage[]` – objekty IImage.

### getImages(IRenderingOptions options, float scaleX, float scaleY) {#getImages-com.aspose.slides.IRenderingOptions-float-float-}
```
public abstract IImage[] getImages(IRenderingOptions options, float scaleX, float scaleY)
```

**Vrací objekty Miniatury Image pro všechny snímky prezentace s vlastním měřítkem.**

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Možnosti renderování. |
| scaleX | `float` | Hodnota, o kterou se má Miniatura měřítkovat ve směru osy X. |
| scaleY | `float` | Hodnota, o kterou se má Miniatura měřítkovat ve směru osy Y. |

**Vrací:**
`com.aspose.slides.IImage[]` – objekty Bitmap.

### getImages(IRenderingOptions options, int[] slides, float scaleX, float scaleY) {#getImages-com.aspose.slides.IRenderingOptions-int---float-float-}
```
public abstract IImage[] getImages(IRenderingOptions options, int[] slides, float scaleX, float scaleY)
```

**Vrací objekty Miniatury Image pro určené snímky prezentace s vlastním měřítkem.**

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Možnosti renderování. |
| slides | `int[]` | Pole s pozicemi snímků, počínaje 1. |
| scaleX | `float` | Hodnota, o kterou se má Miniatura měřítkovat ve směru osy X. |
| scaleY | `float` | Hodnota, o kterou se má Miniatura měřítkovat ve směru osy Y. |

**Vrací:**
`com.aspose.slides.IImage[]` – objekty IImage.

### getImages(IRenderingOptions options, Size imageSize) {#getImages-com.aspose.slides.IRenderingOptions-com.aspose.slides.android.Size-}
```
public abstract IImage[] getImages(IRenderingOptions options, Size imageSize)
```

**Vrací objekty Miniatury Image pro všechny snímky prezentace se zadanou velikostí.**

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Možnosti renderování. |
| imageSize | [Size](../../com.aspose.slides.android/size) | Velikost vytvářeného obrázku. |

**Vrací:**
`com.aspose.slides.IImage[]` – objekty IImage.

### getImages(IRenderingOptions options, int[] slides, Size imageSize) {#getImages-com.aspose.slides.IRenderingOptions-int---com.aspose.slides.android.Size-}
```
public abstract IImage[] getImages(IRenderingOptions options, int[] slides, Size imageSize)
```

**Vrací objekty Miniatury Image pro určené snímky prezentace se zadanou velikostí.**

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Možnosti renderování. |
| slides | `int[]` | Pole s pozicemi snímků, počínaje 1. |
| imageSize | [Size](../../com.aspose.slides.android/size) | Velikost vytvářeného obrázku. |

**Vrací:**
`com.aspose.slides.IImage[]` – objekty IImage.

### getSlideById(long id) {#getSlideById-long-}
```
public abstract IBaseSlide getSlideById(long id)
```

**Vrací Slide, MasterSlide nebo LayoutSlide podle Id.**

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| id | `long` | Id snímku. |

**Vrací:**
[IBaseSlide](../../com.aspose.slides/ibaseslide) – objekt `IBaseSlide`.

### joinPortionsWithSameFormatting() {#joinPortionsWithSameFormatting--}
```
public abstract void joinPortionsWithSameFormatting()
```

**Spojuje úseky se stejným formátováním ve všech odstavcích ve všech vhodných tvarech ve všech snímcích.**

### highlightText(String text, Integer highlightColor) {#highlightText-java.lang.String-java.lang.Integer-}
```
public abstract void highlightText(String text, Integer highlightColor)
```

**Zvýrazní všechny shody ukázkového textu zadanou barvou.**

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
| text | `java.lang.String` | Text, který má být zvýrazněn. |
| highlightColor | `java.lang.Integer` | Barva, kterou má být text zvýrazněn. |

### highlightText(String text, Integer highlightColor, ITextSearchOptions options, IFindResultCallback callback) {#highlightText-java.lang.String-java.lang.Integer-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-}
```
public abstract void highlightText(String text, Integer highlightColor, ITextSearchOptions options, IFindResultCallback callback)
```

**Zvýrazní všechny shody ukázkového textu zadanou barvou.**

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
| text | `java.lang.String` | Text, který má být zvýrazněn. |
| highlightColor | `java.lang.Integer` | Barva, kterou má být text zvýrazněn. |
| options | [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions) | Možnosti vyhledávání textu [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions). |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | Objekt zpětného volání pro přijímání výsledků vyhledávání [IFindResultCallback](../../com.aspose.slides/ifindresultcallback). |

### highlightRegex(Pattern regex, Integer highlightColor, IFindResultCallback callback) {#highlightRegex-java.util.regex.Pattern-java.lang.Integer-com.aspose.slides.IFindResultCallback-}
```
public abstract void highlightRegex(Pattern regex, Integer highlightColor, IFindResultCallback callback)
```

**Zvýrazní všechny shody regulárního výrazu zadanou barvou.**

--------------------

> ```
> The following code sample shows how to highlight text in a PowerPoint Presentation using a regular expression.
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
| regex | `java.util.regex.Pattern` | Regulární výraz, ze kterého se získají řetězce k zvýraznění. |
| highlightColor | `java.lang.Integer` | Barva, kterou má být text zvýrazněn. |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | Objekt zpětného volání pro přijímání výsledků vyhledávání [IFindResultCallback](../../com.aspose.slides/ifindresultcallback). |

### replaceText(String oldText, String newText, ITextSearchOptions options, IFindResultCallback callback) {#replaceText-java.lang.String-java.lang.String-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-}
```
public abstract void replaceText(String oldText, String newText, ITextSearchOptions options, IFindResultCallback callback)
```

**Nahradí všechny výskyty zadaného textu jiným zadaným textem.**

--------------------

> ```
> The following sample code shows how to replace one specified string with another specified string.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx")
>  try {
>      TextSearchOptions textSearchOptions = new TextSearchOptions();
>      textSearchOptions.setWholeWordsOnly(true);
>      // Nahraď všechny samostatné výskyty 'the' řetězcem '***'
>      presentation.replaceText("the", "***", textSearchOptions, null);
>      presentation.save("SomePresentation-out2.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| oldText | `java.lang.String` | Řetězec, který má být nahrazen. |
| newText | `java.lang.String` | Řetězec, kterým se nahradí všechny výskyty oldText. |
| options | [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions) | Možnosti vyhledávání textu [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions). |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | Objekt zpětného volání pro přijímání výsledků vyhledávání [IFindResultCallback](../../com.aspose.slides/ifindresultcallback). |

### replaceRegex(Pattern regex, String newText, IFindResultCallback callback) {#replaceRegex-java.util.regex.Pattern-java.lang.String-com.aspose.slides.IFindResultCallback-}
```
public abstract void replaceRegex(Pattern regex, String newText, IFindResultCallback callback)
```

**Nahradí všechny shody regulárního výrazu zadaným řetězcem.**

--------------------

> ```
> The following code sample shows how to replace text using regular expression with the specified string.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx")
>  try {
>      TextSearchOptions textSearchOptions = new TextSearchOptions();
>      textSearchOptions.setWholeWordsOnly(true);
>      // Nahraď všechny samostatné výskyty 'the' řetězcem '***'
>      presentation.replaceText("the", "***", textSearchOptions, null);
>      presentation.save("SomePresentation-out2.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| regex | `java.util.regex.Pattern` | Regulární výraz, ze kterého se získají řetězce k náhradě. |
| newText | `java.lang.String` | Řetězec, kterým se nahradí všechny výskyty řetězců k náhradě. |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | Objekt zpětného volání pro přijímání výsledků vyhledávání [IFindResultCallback](../../com.aspose.slides/ifindresultcallback). |