---
title: IPresentation
second_title: Aspose.Slides for Java API referenciája
description: Prezentációs dokumentum
type: docs
url: /hu/com.aspose.slides/ipresentation/
---
**Az összes megvalósított interfész:**
[com.aspose.slides.IPresentationComponent](../../com.aspose.slides/ipresentationcomponent), com.aspose.ms.System.IDisposable
```
public interface IPresentation extends IPresentationComponent, System.IDisposable
```

Prezentációs dokumentum
## Módszerek

| Metódus | Leírás |
| --- | --- |
| [getCurrentDateTime()](#getCurrentDateTime--) | Visszaadja vagy beállítja a dátumot és időt, amely helyettesíti a datetime mezők tartalmát. |
| [setCurrentDateTime(Date value)](#setCurrentDateTime-java.util.Date-) | Visszaadja vagy beállítja a dátumot és időt, amely helyettesíti a datetime mezők tartalmát. |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | Visszaadja a prezentáció HeaderFooter kezelőjét. |
| [getProtectionManager()](#getProtectionManager--) | Visszaadja a jogosultságok kezelőjét ehhez a prezentációhoz. |
| [getSlides()](#getSlides--) | Visszaadja az összes diát tartalmazó listát, amely a prezentációban definiálva van. |
| [getSections()](#getSections--) | Visszaadja az összes diarészlet listáját, amely a prezentációban definiálva van. |
| [getSlideSize()](#getSlideSize--) | Visszaadja a dia méret objektumát. |
| [getNotesSize()](#getNotesSize--) | Visszaadja a jegyzet diák méret objektumát. |
| [getLayoutSlides()](#getLayoutSlides--) | Visszaadja az összes elrendezési dia listáját, amely a prezentációban definiálva van. |
| [getMasters()](#getMasters--) | Visszaadja az összes mesterdia listáját, amely a prezentációban definiálva van. |
| [getMasterNotesSlideManager()](#getMasterNotesSlideManager--) | Visszaadja a jegyzet mester kezelőt. |
| [getMasterHandoutSlideManager()](#getMasterHandoutSlideManager--) | Visszaadja a kiosztmány mester kezelőt. |
| [getFontsManager()](#getFontsManager--) | Visszaadja a betűtípusok kezelőjét. |
| [getDefaultTextStyle()](#getDefaultTextStyle--) | Visszaadja az alapértelmezett szövegstílust a formákhoz. |
| [getCommentAuthors()](#getCommentAuthors--) | Visszaadja a megjegyzés szerzők gyűjteményét. |
| [getDocumentProperties()](#getDocumentProperties--) | Visszaadja a DocumentProperties objektumot, amely a szabványos és egyedi dokumentum tulajdonságokat tartalmazza. |
| [getImages()](#getImages--) | Visszaadja a prezentáció összes képének gyűjteményét. |
| [getAudios()](#getAudios--) | Visszaadja a prezentációban beágyazott összes hangfájl gyűjteményét. |
| [getVideos()](#getVideos--) | Visszaadja a prezentációban beágyazott összes videófájl gyűjteményét. |
| [getCustomData()](#getCustomData--) | Visszaadja a prezentáció egyéni adatát. |
| [getVbaProject()](#getVbaProject--) | Visszaadja a VBA projektet a prezentáció makrókkal. |
| [setVbaProject(IVbaProject value)](#setVbaProject-com.aspose.slides.IVbaProject-) | Visszaadja a VBA projektet a prezentáció makrókkal. |
| [getSourceFormat()](#getSourceFormat--) | Visszaadja a prezentáció betöltésének formátumáról szóló információt. |
| [getMasterTheme()](#getMasterTheme--) | Visszaadja a prezentáció mester témáját. |
| [getHyperlinkQueries()](#getHyperlinkQueries--) | Könnyű hozzáférést biztosít az összes hiperhivatkozáshoz, amely az összes prezentációs dián található (nem a mester, elrendezés, jegyzet diákon). |
| [getViewProperties()](#getViewProperties--) | Visszaadja a prezentációra vonatkozó nézeti tulajdonságokat. |
| [getFirstSlideNumber()](#getFirstSlideNumber--) | A prezentáció első diájának számát jelöli. |
| [setFirstSlideNumber(int value)](#setFirstSlideNumber-int-) | A prezentáció első diájának számát jelöli. |
| [getAllCustomXmlParts()](#getAllCustomXmlParts--) | Visszaadja a prezentáció összes egyéni adat részét. |
| [getDigitalSignatures()](#getDigitalSignatures--) | Visszaadja a prezentáció aláírásához használt aláírások gyűjteményét. |
| [getSensitivityLabels()](#getSensitivityLabels--) | Visszaadja a prezentáció dokumentumra alkalmazott érzékenységi címkék gyűjteményét. |
| [save(String fname, int format)](#save-java.lang.String-int-) | Elmenti a prezentáció összes diáját egy fájlba a megadott formátummal. |
| [save(OutputStream stream, int format)](#save-java.io.OutputStream-int-) | Elmenti a prezentáció összes diáját egy adatfolyamra a megadott formátummal. |
| [save(String fname, int format, ISaveOptions options)](#save-java.lang.String-int-com.aspose.slides.ISaveOptions-) | Elmenti a prezentáció összes diáját egy fájlba a megadott formátummal és további beállításokkal. |
| [save(OutputStream stream, int format, ISaveOptions options)](#save-java.io.OutputStream-int-com.aspose.slides.ISaveOptions-) | Elmenti a prezentáció összes diáját egy adatfolyamra a megadott formátummal és további beállításokkal. |
| [save(String fname, int[] slides, int format)](#save-java.lang.String-int---int-) | Saves specified slides of a presentation to a file with the specified format. |
| [save(String fname, int[] slides, int format, ISaveOptions options)](#save-java.lang.String-int---int-com.aspose.slides.ISaveOptions-) | Saves specified slides of a presentation to a file with the specified format. |
| [save(OutputStream stream, int[] slides, int format)](#save-java.io.OutputStream-int---int-) | Saves specified slides of a presentation to a stream in the specified format. |
| [save(OutputStream stream, int[] slides, int format, ISaveOptions options)](#save-java.io.OutputStream-int---int-com.aspose.slides.ISaveOptions-) | Saves specified slides of a presentation to a stream in the specified format. |
| [save(IXamlOptions options)](#save-com.aspose.slides.IXamlOptions-) | Elmenti a prezentáció összes diáját egy XAML jelölést ábrázoló fájlkészletbe. |
| [getImages(IRenderingOptions options)](#getImages-com.aspose.slides.IRenderingOptions-) | Visszaadja az összes diasorhoz tartozó bélyegkép kép objektumot. |
| [getImages(IRenderingOptions options, int[] slides)](#getImages-com.aspose.slides.IRenderingOptions-int---) | Visszaadja a megadott prezentációs diák bélyegkép IImage objektumait. |
| [getImages(IRenderingOptions options, float scaleX, float scaleY)](#getImages-com.aspose.slides.IRenderingOptions-float-float-) | Visszaadja az összes prezentációs dia bélyegkép kép objektumát egyéni skálázással. |
| [getImages(IRenderingOptions options, int[] slides, float scaleX, float scaleY)](#getImages-com.aspose.slides.IRenderingOptions-int---float-float-) | Visszaadja a megadott prezentációs diák bélyegkép IImage objektumait egyéni skálázással. |
| [getImages(IRenderingOptions options, Dimension imageSize)](#getImages-com.aspose.slides.IRenderingOptions-java.awt.Dimension-) | Visszaadja az összes prezentációs dia bélyegkép kép objektumát a megadott mérettel. |
| [getImages(IRenderingOptions options, int[] slides, Dimension imageSize)](#getImages-com.aspose.slides.IRenderingOptions-int---java.awt.Dimension-) | Visszaadja a megadott prezentációs diák bélyegkép IImage objektumait a megadott mérettel. |
| [getSlideById(long id)](#getSlideById-long-) | Visszaadja a Slide, MasterSlide vagy LayoutSlide elemet az Azonosító alapján. |
| [joinPortionsWithSameFormatting()](#joinPortionsWithSameFormatting--) | Összevonja a ugyanazon formázással rendelkező futamokat az összes bekezdésben minden elfogadható alakzatban az összes dián. |
| [highlightText(String text, Color highlightColor)](#highlightText-java.lang.String-java.awt.Color-) | Kiemeli a mintaszöveg összes egyezését a megadott színnel. |
| [highlightText(String text, Color highlightColor, ITextSearchOptions options, IFindResultCallback callback)](#highlightText-java.lang.String-java.awt.Color-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-) | Kiemeli a mintaszöveg összes egyezését a megadott színnel. |
| [highlightRegex(Pattern regex, Color highlightColor, IFindResultCallback callback)](#highlightRegex-java.util.regex.Pattern-java.awt.Color-com.aspose.slides.IFindResultCallback-) | Kiemeli a reguláris kifejezés összes egyezését a megadott színnel. |
| [replaceText(String oldText, String newText, ITextSearchOptions options, IFindResultCallback callback)](#replaceText-java.lang.String-java.lang.String-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-) | Lecseréli a megadott szöveg összes előfordulását egy másik megadott szövegre. |
| [replaceRegex(Pattern regex, String newText, IFindResultCallback callback)](#replaceRegex-java.util.regex.Pattern-java.lang.String-com.aspose.slides.IFindResultCallback-) | Lecseréli a reguláris kifejezés összes egyezését a megadott karakterláncra. |
| [refreshChartsData()](#refreshChartsData--) | Újratölti a prezentáció összes diagramjának adatait a forrás munkafüzetekből. |
| [refreshChartsData(boolean skipFailedCharts)](#refreshChartsData-boolean-) | Újratölti a prezentáció összes diagramjának adatait a forrás munkafüzetekből. |

### getCurrentDateTime() {#getCurrentDateTime--}
```
public abstract Date getCurrentDateTime()
```

Visszaadja vagy beállítja a dátumot és időt, amely helyettesíti a datetime mezők tartalmát. Alapértelmezés szerint a Presentation objektum létrehozásának időpontja. **Olvasás/írás** java.util.Date.

**Visszatér:**
java.util.Date

### setCurrentDateTime(Date value) {#setCurrentDateTime-java.util.Date-}
```
public abstract void setCurrentDateTime(Date value)
```

Visszaadja vagy beállítja a dátumot és időt, amely helyettesíti a datetime mezők tartalmát. Alapértelmezés szerint a Presentation objektum létrehozásának időpontja. **Olvasás/írás** java.util.Date.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | java.util.Date |  |

### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public abstract IPresentationHeaderFooterManager getHeaderFooterManager()
```

Visszaadja a prezentáció HeaderFooter kezelőjét. **Csak olvasható** [IPresentationHeaderFooterManager](../../com.aspose.slides/ipresentationheaderfootermanager).

**Visszatér:**
[IPresentationHeaderFooterManager](../../com.aspose.slides/ipresentationheaderfootermanager)

### getProtectionManager() {#getProtectionManager--}
```
public abstract IProtectionManager getProtectionManager()
```

Visszaadja a jogosultságok kezelőjét ehhez a prezentációhoz. **Csak olvasható** [IProtectionManager](../../com.aspose.slides/iprotectionmanager).

**Visszatér:**
[IProtectionManager](../../com.aspose.slides/iprotectionmanager)

### getSlides() {#getSlides--}
```
public abstract ISlideCollection getSlides()
```

Visszaadja az összes diát tartalmazó listát, amely a prezentációban definiálva van. **Csak olvasható** [ISlideCollection](../../com.aspose.slides/islidecollection).

**Visszatér:**
[ISlideCollection](../../com.aspose.slides/islidecollection)

### getSections() {#getSections--}
```
public abstract ISectionCollection getSections()
```

Visszaadja az összes diarészlet listáját, amely a prezentációban definiálva van. **Csak olvasható** [ISectionCollection](../../com.aspose.slides/isectioncollection).

**Visszatér:**
[ISectionCollection](../../com.aspose.slides/isectioncollection)

### getSlideSize() {#getSlideSize--}
```
public abstract ISlideSize getSlideSize()
```

Visszaadja a dia méret objektumát. **Csak olvasható** [ISlideSize](../../com.aspose.slides/islidesize).

**Visszatér:**
[ISlideSize](../../com.aspose.slides/islidesize)

### getNotesSize() {#getNotesSize--}
```
public abstract INotesSize getNotesSize()
```

Visszaadja a jegyzet diák méret objektumát. **Csak olvasható** [INotesSize](../../com.aspose.slides/inotessize).

**Visszatér:**
[INotesSize](../../com.aspose.slides/inotessize)

### getLayoutSlides() {#getLayoutSlides--}
```
public abstract IGlobalLayoutSlideCollection getLayoutSlides()
```

Visszaadja az összes elrendezési dia listáját, amely a prezentációban definiálva van. **Csak olvasható** [IGlobalLayoutSlideCollection](../../com.aspose.slides/igloballayoutslidecollection).

--------------------

Az alternatív API-t a layout diák hozzáadásához/beszúrásához/eltávolításához/kettőzéséhez az IMasterSlide.LayoutSlides tulajdonságon keresztül érheti el.

**Visszatér:**
[IGlobalLayoutSlideCollection](../../com.aspose.slides/igloballayoutslidecollection)

### getMasters() {#getMasters--}
```
public abstract IMasterSlideCollection getMasters()
```

Visszaadja az összes mesterdia listáját, amely a prezentációban definiálva van. **Csak olvasható** [IMasterSlideCollection](../../com.aspose.slides/imasterslidecollection).

**Visszatér:**
[IMasterSlideCollection](../../com.aspose.slides/imasterslidecollection)

### getMasterNotesSlideManager() {#getMasterNotesSlideManager--}
```
public abstract IMasterNotesSlideManager getMasterNotesSlideManager()
```

Visszaadja a jegyzet mester kezelőt. **Csak olvasható** [IMasterNotesSlideManager](../../com.aspose.slides/imasternotesslidemanager).

**Visszatér:**
[IMasterNotesSlideManager](../../com.aspose.slides/imasternotesslidemanager)

### getMasterHandoutSlideManager() {#getMasterHandoutSlideManager--}
```
public abstract IMasterHandoutSlideManager getMasterHandoutSlideManager()
```

Visszaadja a kiosztmány mester kezelőt. **Csak olvasható** [IMasterHandoutSlideManager](../../com.aspose.slides/imasterhandoutslidemanager).

**Visszatér:**
[IMasterHandoutSlideManager](../../com.aspose.slides/imasterhandoutslidemanager)

### getFontsManager() {#getFontsManager--}
```
public abstract IFontsManager getFontsManager()
```

Visszaadja a betűtípusok kezelőjét. **Csak olvasható** [IFontsManager](../../com.aspose.slides/ifontsmanager).

**Visszatér:**
[IFontsManager](../../com.aspose.slides/ifontsmanager)

### getDefaultTextStyle() {#getDefaultTextStyle--}
```
public abstract ITextStyle getDefaultTextStyle()
```

Visszaadja az alapértelmezett szövegstílust a formákhoz. **Csak olvasható** [ITextStyle](../../com.aspose.slides/itextstyle).

**Visszatér:**
[ITextStyle](../../com.aspose.slides/itextstyle)

### getCommentAuthors() {#getCommentAuthors--}
```
public abstract ICommentAuthorCollection getCommentAuthors()
```

Visszaadja a megjegyzés szerzők gyűjteményét. **Csak olvasható** [ICommentAuthorCollection](../../com.aspose.slides/icommentauthorcollection).

**Visszatér:**
[ICommentAuthorCollection](../../com.aspose.slides/icommentauthorcollection)

### getDocumentProperties() {#getDocumentProperties--}
```
public abstract IDocumentProperties getDocumentProperties()
```

Visszaadja a DocumentProperties objektumot, amely a szabványos és egyedi dokumentum tulajdonságokat tartalmazza. **Csak olvasható** [IDocumentProperties](../../com.aspose.slides/idocumentproperties).

**Visszatér:**
[IDocumentProperties](../../com.aspose.slides/idocumentproperties)

### getImages() {#getImages--}
```
public abstract IImageCollection getImages()
```

Visszaadja a prezentáció összes képének gyűjteményét. **Csak olvasható** [IImageCollection](../../com.aspose.slides/iimagecollection).

**Visszatér:**
[IImageCollection](../../com.aspose.slides/iimagecollection)

### getAudios() {#getAudios--}
```
public abstract IAudioCollection getAudios()
```

Visszaadja a prezentációban beágyazott összes hangfájl gyűjteményét. **Csak olvasható** [IAudioCollection](../../com.aspose.slides/iaudiocollection).

**Visszatér:**
[IAudioCollection](../../com.aspose.slides/iaudiocollection)

### getVideos() {#getVideos--}
```
public abstract IVideoCollection getVideos()
```

Visszaadja a prezentációban beágyazott összes videófájl gyűjteményét. **Csak olvasható** [IVideoCollection](../../com.aspose.slides/ivideocollection).

**Visszatér:**
[IVideoCollection](../../com.aspose.slides/ivideocollection)

### getCustomData() {#getCustomData--}
```
public abstract ICustomData getCustomData()
```

Visszaadja a prezentáció egyéni adatát. **Csak olvasható** [ICustomData](../../com.aspose.slides/icustomdata).

**Visszatér:**
[ICustomData](../../com.aspose.slides/icustomdata)

### getVbaProject() {#getVbaProject--}
```
public abstract IVbaProject getVbaProject()
```

Visszaadja a VBA projektet a prezentáció makrókkal. **Olvasás/írás** [IVbaProject](../../com.aspose.slides/ivbaproject).

**Visszatér:**
[IVbaProject](../../com.aspose.slides/ivbaproject)

### setVbaProject(IVbaProject value) {#setVbaProject-com.aspose.slides.IVbaProject-}
```
public abstract void setVbaProject(IVbaProject value)
```

Visszaadja a VBA projektet a prezentáció makrókkal. **Olvasás/írás** [IVbaProject](../../com.aspose.slides/ivbaproject).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | [IVbaProject](../../com.aspose.slides/ivbaproject) |  |

### getSourceFormat() {#getSourceFormat--}
```
public abstract int getSourceFormat()
```

Visszaadja a prezentáció betöltésének formátumáról szóló információt. **Csak olvasható** [SourceFormat](../../com.aspose.slides/sourceformat).

**Visszatér:**
int

### getMasterTheme() {#getMasterTheme--}
```
public abstract IMasterTheme getMasterTheme()
```

Visszaadja a prezentáció mester témáját. **Csak olvasható** [IMasterTheme](../../com.aspose.slides/imastertheme).

**Visszatér:**
[IMasterTheme](../../com.aspose.slides/imastertheme)

### getHyperlinkQueries() {#getHyperlinkQueries--}
```
public abstract IHyperlinkQueries getHyperlinkQueries()
```

Könnyű hozzáférést biztosít az összes hiperhivatkozáshoz, amely az összes prezentációs dián található (nem a mester, elrendezés, jegyzet diákon). **Csak olvasható** [IHyperlinkQueries](../../com.aspose.slides/ihyperlinkqueries).

**Visszatér:**
[IHyperlinkQueries](../../com.aspose.slides/ihyperlinkqueries)

### getViewProperties() {#getViewProperties--}
```
public abstract IViewProperties getViewProperties()
```

Visszaadja a prezentációra vonatkozó nézeti tulajdonságokat. **Csak olvasható** [IViewProperties](../../com.aspose.slides/iviewproperties).

**Visszatér:**
[IViewProperties](../../com.aspose.slides/iviewproperties)

### getFirstSlideNumber() {#getFirstSlideNumber--}
```
public abstract int getFirstSlideNumber()
```

A prezentáció első diájának számát jelöli. **Olvasás/írás** int.

**Visszatér:**
int

### setFirstSlideNumber(int value) {#setFirstSlideNumber-int-}
```
public abstract void setFirstSlideNumber(int value)
```

A prezentáció első diájának számát jelöli. **Olvasás/írás** int.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |

### getAllCustomXmlParts() {#getAllCustomXmlParts--}
```
public abstract ICustomXmlPart[] getAllCustomXmlParts()
```

Visszaadja a prezentáció összes egyéni adat részét. **Csak olvasható** ICustomXmlPart[].

**Visszatér:**
com.aspose.slides.ICustomXmlPart[]

### getDigitalSignatures() {#getDigitalSignatures--}
```
public abstract IDigitalSignatureCollection getDigitalSignatures()
```

Visszaadja a prezentáció aláírásához használt aláírások gyűjteményét. **Csak olvasható** [IDigitalSignatureCollection](../../com.aspose.slides/idigitalsignaturecollection).

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


**Visszatér:**
[IDigitalSignatureCollection](../../com.aspose.slides/idigitalsignaturecollection)

### getSensitivityLabels() {#getSensitivityLabels--}
```
public abstract ISensitivityLabelCollection getSensitivityLabels()
```

Visszaadja a prezentáció dokumentumra alkalmazott érzékenységi címkék gyűjteményét. **Csak olvasható** [ISensitivityLabelCollection](../../com.aspose.slides/isensitivitylabelcollection).

--------------------

> ```
> Presentation pres = new Presentation("SomePresentation.pptx");
>  try {
>      ISensitivityLabelCollection sensitivityLabels = pres.getSensitivityLabels();
> 
>      // Írja ki a használt címkéket
>      for (ISensitivityLabel sensitivityLabel : sensitivityLabels)
>          System.out.println("Label Id " + sensitivityLabel.getId() + " from Azure AD site " + sensitivityLabel.getSiteId());
> 
>      // Új címke hozzáadása
>      String labelIdString = "{xxxxxxxx-xxxx-xxxx-xxxx-xxxxxxxxxxxx}"; // A szenzitivitási címke azonosítóját a szabályzatból kapja
>      UUID siteIdGuid = UUID.fromString("{xxxxxxxx-xxxx-xxxx-xxxx-xxxxxxxxxxxx}"); // Az Azure AD hely azonosítóját a szabályzatból kapja
>      ISensitivityLabel label = sensitivityLabels.add(labelIdString, siteIdGuid, true, SensitivityLabelAssignmentType.Privileged);
>      label.getContentMarkTypes().addItem(SensitivityLabelContentType.Footer);
> 
>      pres.save("SensitivityLabel.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Visszatér:**
[ISensitivityLabelCollection](../../com.aspose.slides/isensitivitylabelcollection)

### save(String fname, int format) {#save-java.lang.String-int-}
```
public abstract void save(String fname, int format)
```

Elmenti a prezentáció összes diáját egy fájlba a megadott formátummal.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| fname | java.lang.String | A létrehozott fájl elérési útja. |
| format | int | Az exportált adat formátuma. |

### save(OutputStream stream, int format) {#save-java.io.OutputStream-int-}
```
public abstract void save(OutputStream stream, int format)
```

Elmenti a prezentáció összes diáját egy adatfolyamra a megadott formátummal.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| stream | java.io.OutputStream | Kimeneti adatfolyam. |
| format | int | Az exportált adat formátuma. |

### save(String fname, int format, ISaveOptions options) {#save-java.lang.String-int-com.aspose.slides.ISaveOptions-}
```
public abstract void save(String fname, int format, ISaveOptions options)
```
Ment minden diát egy prezentációból egy fájlba a megadott formátummal és további opciókkal.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| fname | java.lang.String | A létrehozott fájl elérési útja. |
| format | int | Az exportált adatok formátuma. |
| options | [ISaveOptions](../../com.aspose.slides/isaveoptions) | További formátum opciók. |

### save(OutputStream stream, int format, ISaveOptions options) {#save-java.io.OutputStream-int-com.aspose.slides.ISaveOptions-}
```
public abstract void save(OutputStream stream, int format, ISaveOptions options)
```

Ment minden diát egy prezentációból egy adatfolyamra a megadott formátumban és további opciókkal.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| stream | java.io.OutputStream | Kimeneti adatfolyam. |
| format | int | Az exportált adatok formátuma. |
| options | [ISaveOptions](../../com.aspose.slides/isaveoptions) | További formátum opciók. |

### save(String fname, int[] slides, int format) {#save-java.lang.String-int---int-}
```
public abstract void save(String fname, int[] slides, int format)
```

Ment megadott diákat egy prezentációból egy fájlba a megadott formátummal.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| fname | java.lang.String | A létrehozott fájl elérési útja. |
| slides | int[] | Diapozíciókat tartalmazó tömb, 1-től kezdve. |
| format | int | Az exportált adatok formátuma. |

### save(String fname, int[] slides, int format, ISaveOptions options) {#save-java.lang.String-int---int-com.aspose.slides.ISaveOptions-}
```
public abstract void save(String fname, int[] slides, int format, ISaveOptions options)
```

Ment megadott diákat egy prezentációból egy fájlba a megadott formátummal.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| fname | java.lang.String | A létrehozott fájl elérési útja. |
| slides | int[] | Diapozíciókat tartalmazó tömb, 1-től kezdve. |
| format | int | Az exportált adatok formátuma. |
| options | [ISaveOptions](../../com.aspose.slides/isaveoptions) | További formátum opciók. |

### save(OutputStream stream, int[] slides, int format) {#save-java.io.OutputStream-int---int-}
```
public abstract void save(OutputStream stream, int[] slides, int format)
```

Ment megadott diákat egy prezentációból egy adatfolyamra a megadott formátumban.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| stream | java.io.OutputStream | Kimeneti adatfolyam. |
| slides | int[] | Diapozíciókat tartalmazó tömb, 1-től kezdve. |
| format | int | Az exportált adatok formátuma. |

### save(OutputStream stream, int[] slides, int format, ISaveOptions options) {#save-java.io.OutputStream-int---int-com.aspose.slides.ISaveOptions-}
```
public abstract void save(OutputStream stream, int[] slides, int format, ISaveOptions options)
```

Ment megadott diákat egy prezentációból egy adatfolyamra a megadott formátumban.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| stream | java.io.OutputStream | Kimeneti adatfolyam. |
| slides | int[] | Diapozíciókat tartalmazó tömb, 1-től kezdve. |
| format | int | Az exportált adatok formátuma. |
| options | [ISaveOptions](../../com.aspose.slides/isaveoptions) | További formátum opciók. |

### save(IXamlOptions options) {#save-com.aspose.slides.IXamlOptions-}
```
public abstract void save(IXamlOptions options)
```

Ment minden diát egy prezentációból egy sor fájlba, amely XAML jelölést képvisel.

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


**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| options | [IXamlOptions](../../com.aspose.slides/ixamloptions) | Az XAML formátum opciói. |

### getImages(IRenderingOptions options) {#getImages-com.aspose.slides.IRenderingOptions-}
```
public abstract IImage[] getImages(IRenderingOptions options)
```

Visszaad miniatűr Image objektumokat az összes diáról a prezentációban.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Megjelenítési beállítások. |

**Visszatérési érték:**
com.aspose.slides.IImage[] - IImage objektumok.

### getImages(IRenderingOptions options, int[] slides) {#getImages-com.aspose.slides.IRenderingOptions-int---}
```
public abstract IImage[] getImages(IRenderingOptions options, int[] slides)
```

Visszaad miniatűr IImage objektumokat a megadott diákhoz a prezentációban.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Megjelenítési beállítások. |
| slides | int[] | Diapozíciókat tartalmazó tömb, 1-től kezdve. |

**Visszatérési érték:**
com.aspose.slides.IImage[] - IImage objektumok.

### getImages(IRenderingOptions options, float scaleX, float scaleY) {#getImages-com.aspose.slides.IRenderingOptions-float-float-}
```
public abstract IImage[] getImages(IRenderingOptions options, float scaleX, float scaleY)
```

Visszaad miniatűr Image objektumokat az összes diáról a prezentációban egyéni méretezéssel.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Megjelenítési beállítások. |
| scaleX | float | Az az érték, amellyel a miniatűrt az x tengelyen skálázzuk. |
| scaleY | float | Az az érték, amellyel a miniatűrt az y tengelyen skálázzuk. |

**Visszatérési érték:**
com.aspose.slides.IImage[] - Bitmap objektumok.

### getImages(IRenderingOptions options, int[] slides, float scaleX, float scaleY) {#getImages-com.aspose.slides.IRenderingOptions-int---float-float-}
```
public abstract IImage[] getImages(IRenderingOptions options, int[] slides, float scaleX, float scaleY)
```

Visszaad miniatűr Image objektumokat a megadott diákhoz a prezentációban egyéni méretezéssel.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Megjelenítési beállítások. |
| slides | int[] | Diapozíciókat tartalmazó tömb, 1-től kezdve. |
| scaleX | float | Az az érték, amellyel a miniatűrt az x tengelyen skálázzuk. |
| scaleY | float | Az az érték, amellyel a miniatűrt az y tengelyen skálázzuk. |

**Visszatérési érték:**
com.aspose.slides.IImage[] - IImage objektumok.

### getImages(IRenderingOptions options, Dimension imageSize) {#getImages-com.aspose.slides.IRenderingOptions-java.awt.Dimension-}
```
public abstract IImage[] getImages(IRenderingOptions options, Dimension imageSize)
```

Visszaad miniatűr Image objektumokat az összes diáról a prezentációban a megadott mérettel.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Megjelenítési beállítások. |
| imageSize | java.awt.Dimension | A létrehozandó kép mérete. |

**Visszatérési érték:**
com.aspose.slides.IImage[] - IImage objektumok.

### getImages(IRenderingOptions options, int[] slides, Dimension imageSize) {#getImages-com.aspose.slides.IRenderingOptions-int---java.awt.Dimension-}
```
public abstract IImage[] getImages(IRenderingOptions options, int[] slides, Dimension imageSize)
```

Visszaad miniatűr Image objektumokat a megadott diákhoz a prezentációban a megadott mérettel.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Megjelenítési beállítások. |
| slides | int[] | Diapozíciókat tartalmazó tömb, 1-től kezdve. |
| imageSize | java.awt.Dimension | A létrehozandó kép mérete. |

**Visszatérési érték:**
com.aspose.slides.IImage[] - IImage objektumok.

### getSlideById(long id) {#getSlideById-long-}
```
public abstract IBaseSlide getSlideById(long id)
```

Visszaad egy Slide, MasterSlide vagy LayoutSlide azonosító alapján.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| id | long | Egy dia azonosítója. |

**Visszatérési érték:**
[IBaseSlide](../../com.aspose.slides/ibaseslide) - IBaseSlide objektum.

### joinPortionsWithSameFormatting() {#joinPortionsWithSameFormatting--}
```
public abstract void joinPortionsWithSameFormatting()
```

Összevonja az egységes formázású szakaszokat az összes bekezdésben, minden elfogadható alakzatban, minden dián.

### highlightText(String text, Color highlightColor) {#highlightText-java.lang.String-java.awt.Color-}
```
public abstract void highlightText(String text, Color highlightColor)
```

Kiemeli a mintaszöveg összes egyezését a megadott színnel.

--------------------

> ```
> The following code sample shows how to highlight text in a PowerPoint presentation.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      // az összes különálló 'the' előfordulás kiemelése
>      presentation.highlightText("the", Color.MAGENTA);
>      presentation.save("SomePresentation-out2.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| text | java.lang.String | A kiemelendő szöveg. |
| highlightColor | java.awt.Color | A szöveg kiemeléséhez használt szín. |

### highlightText(String text, Color highlightColor, ITextSearchOptions options, IFindResultCallback callback) {#highlightText-java.lang.String-java.awt.Color-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-}
```
public abstract void highlightText(String text, Color highlightColor, ITextSearchOptions options, IFindResultCallback callback)
```

Kiemeli a mintaszöveg összes egyezését a megadott színnel.

--------------------

> ```
> The following code sample shows how to highlight text in a PowerPoint presentation.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      // az összes különálló 'the' előfordulás kiemelése
>      presentation.highlightText("the", Color.MAGENTA);
>      presentation.save("SomePresentation-out2.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| text | java.lang.String | A kiemelendő szöveg. |
| highlightColor | java.awt.Color | A szöveg kiemeléséhez használt szín. |
| options | [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions) | Szövegkeresési opciók [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions). |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | A visszahívási objektum a keresési eredmények fogadásához [IFindResultCallback](../../com.aspose.slides/ifindresultcallback). |

### highlightRegex(Pattern regex, Color highlightColor, IFindResultCallback callback) {#highlightRegex-java.util.regex.Pattern-java.awt.Color-com.aspose.slides.IFindResultCallback-}
```
public abstract void highlightRegex(Pattern regex, Color highlightColor, IFindResultCallback callback)
```

Kiemeli a reguláris kifejezés összes egyezését a megadott színnel.

--------------------

> ```
> The following code sample shows how to highlight text in a PowerPoint Presentation using a regular expression.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      // az összes különálló 'the' előfordulás kiemelése
>      presentation.highlightText("the", Color.MAGENTA);
>      presentation.save("SomePresentation-out2.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| regex | java.util.regex.Pattern | A java.util.regex.Pattern reguláris kifejezés a kiemelendő karakterláncok meghatározásához. |
| highlightColor | java.awt.Color | A szöveg kiemeléséhez használt szín. |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | A visszahívási objektum a keresési eredmények fogadásához [IFindResultCallback](../../com.aspose.slides/ifindresultcallback). |

### replaceText(String oldText, String newText, ITextSearchOptions options, IFindResultCallback callback) {#replaceText-java.lang.String-java.lang.String-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-}
```
public abstract void replaceText(String oldText, String newText, ITextSearchOptions options, IFindResultCallback callback)
```

Lecseréli a megadott szöveg összes előfordulását egy másik megadott szövegre.

--------------------

> ```
> The following sample code shows how to replace one specified string with another specified string.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx")
>  try {
>      TextSearchOptions textSearchOptions = new TextSearchOptions();
>      textSearchOptions.setWholeWordsOnly(true);
>      // Az összes különálló 'the' előfordulás cseréje '***'-ra
>      presentation.replaceText("the", "***", textSearchOptions, null);
>      presentation.save("SomePresentation-out2.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| oldText | java.lang.String | A cserélendő karakterlánc. |
| newText | java.lang.String | A karakterlánc, amelyre az oldText összes előfordulását cserélni kell. |
| options | [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions) | Szövegkeresési opciók [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions). |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | A visszahívási objektum a keresési eredmények fogadásához [IFindResultCallback](../../com.aspose.slides/ifindresultcallback). |

### replaceRegex(Pattern regex, String newText, IFindResultCallback callback) {#replaceRegex-java.util.regex.Pattern-java.lang.String-com.aspose.slides.IFindResultCallback-}
```
public abstract void replaceRegex(Pattern regex, String newText, IFindResultCallback callback)
```

Lecseréli a reguláris kifejezés összes egyezését a megadott karakterláncra.

--------------------

> ```
> The following code sample shows how to replace text using regular expression with the specified string.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx")
>  try {
>      TextSearchOptions textSearchOptions = new TextSearchOptions();
>      textSearchOptions.setWholeWordsOnly(true);
>      // Az összes különálló 'the' előfordulás cseréje '***'-ra
>      presentation.replaceText("the", "***", textSearchOptions, null);
>      presentation.save("SomePresentation-out2.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| regex | java.util.regex.Pattern | A java.util.regex.Pattern reguláris kifejezés a cserélendő karakterláncok meghatározásához. |
| newText | java.lang.String | A karakterlánc, amelyre a cserélendő karakterláncok összes előfordulását cserélni kell. |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | A visszahívási objektum a keresési eredmények fogadásához [IFindResultCallback](../../com.aspose.slides/ifindresultcallback). |

### refreshChartsData() {#refreshChartsData--}
```
public abstract void refreshChartsData()
```

Újratölti az adatokat az összes diagramhoz a prezentációban az eredeti munkafüzetekből.

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

Újratölti az adatokat az összes diagramhoz a prezentációban az eredeti munkafüzetekből.

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


**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| skipFailedCharts | boolean | Megadja, hogy a frissítési folyamat folytatódjon-e, ha egy diagram frissítése sikertelen. Ha true, a kivételt okozó diagramok kihagyásra kerülnek; ellenkező esetben a kivétel továbbadódik. |