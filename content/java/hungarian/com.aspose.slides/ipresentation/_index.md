---
title: IPresentation
second_title: Aspose.Slides a Java API referencia
description: Prezentációs dokumentum
type: docs
url: /hu/com.aspose.slides/ipresentation/
---
**Az összes megvalósított interfész:**
[com.aspose.slides.IPresentationComponent](../../com.aspose.slides/ipresentationcomponent), com.aspose.ms.System.IDisposable
```
public interface IPresentation extends IPresentationComponent, System.IDisposable
```

Presentation document
## Módszerek

| Módszer | Leírás |
| --- | --- |
| [getCurrentDateTime()](#getCurrentDateTime--) | Visszaadja vagy beállítja a dátumot és az időt, amely helyettesíti a datetime mezők tartalmát. |
| [setCurrentDateTime(Date value)](#setCurrentDateTime-java.util.Date-) | Visszaadja vagy beállítja a dátumot és az időt, amely helyettesíti a datetime mezők tartalmát. |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | Visszaadja a prezentáció HeaderFooter kezelőjét. |
| [getProtectionManager()](#getProtectionManager--) | Megkapja a jogosultságok kezelőjét ehhez a prezentációhoz. |
| [getSlides()](#getSlides--) | Visszaad egy listát az összes diáról, amely a prezentációban van definiálva. |
| [getSections()](#getSections--) | Visszaad egy listát az összes dia szekcióról, amely a prezentációban van definiálva. |
| [getSlideSize()](#getSlideSize--) | Visszaadja a dia méret objektumot. |
| [getNotesSize()](#getNotesSize--) | Visszaadja a jegyzet dia méret objektumot. |
| [getLayoutSlides()](#getLayoutSlides--) | Visszaad egy listát az összes elrendezés diáról, amely a prezentációban van definiálva. |
| [getMasters()](#getMasters--) | Visszaad egy listát az összes mester diáról, amely a prezentációban van definiálva. |
| [getMasterNotesSlideManager()](#getMasterNotesSlideManager--) | Visszaadja a jegyzet mester kezelőt. |
| [getMasterHandoutSlideManager()](#getMasterHandoutSlideManager--) | Visszaadja a kézbesítő mester kezelőt. |
| [getFontsManager()](#getFontsManager--) | Visszaadja a betűtípusok kezelőjét. |
| [getDefaultTextStyle()](#getDefaultTextStyle--) | Visszaadja az alakzatok alapértelmezett szövegstílusát. |
| [getCommentAuthors()](#getCommentAuthors--) | Visszaadja a hozzászólások szerzőinek gyűjteményét. |
| [getDocumentProperties()](#getDocumentProperties--) | Visszaad egy DocumentProperties objektumot, amely szabványos és egyedi dokumentum tulajdonságokat tartalmaz. |
| [getImages()](#getImages--) | Visszaadja az összes kép gyűjteményét a prezentációban. |
| [getAudios()](#getAudios--) | Visszaadja az összes beágyazott audio fájl gyűjteményét a prezentációban. |
| [getVideos()](#getVideos--) | Visszaadja az összes beágyazott video fájl gyűjteményét a prezentációban. |
| [getCustomData()](#getCustomData--) | Visszaadja a prezentáció egyedi adatait. |
| [getVbaProject()](#getVbaProject--) | Megkapja a VBA projektet a prezentáció makrókkal. |
| [setVbaProject(IVbaProject value)](#setVbaProject-com.aspose.slides.IVbaProject-) | Megkapja a VBA projektet a prezentáció makrókkal. |
| [getSourceFormat()](#getSourceFormat--) | Visszaad információt arról, hogy melyik formátumból lett betöltve a prezentáció. |
| [getMasterTheme()](#getMasterTheme--) | Visszaadja a prezentáció mester témáját. |
| [getHyperlinkQueries()](#getHyperlinkQueries--) | Könnyű hozzáférést biztosít az összes hiperhivatkozáshoz, amely az összes prezentációs dián található (nem a mester, elrendezés vagy jegyzet diákon). |
| [getViewProperties()](#getViewProperties--) | Megkapja a prezentáció szintű nézeti tulajdonságokat. |
| [getFirstSlideNumber()](#getFirstSlideNumber--) | A prezentáció első dia számát jelöli. |
| [setFirstSlideNumber(int value)](#setFirstSlideNumber-int-) | A prezentáció első dia számát jelöli. |
| [getAllCustomXmlParts()](#getAllCustomXmlParts--) | Visszaadja az összes egyedi adat részt a prezentációban. |
| [getDigitalSignatures()](#getDigitalSignatures--) | Visszaadja a prezentáció aláírásához használt aláírások gyűjteményét. |
| [getSensitivityLabels()](#getSensitivityLabels--) | Visszaadja a prezentáció dokumentumra alkalmazott érzékenységi címkék gyűjteményét. |
| [save(String fname, int format)](#save-java.lang.String-int-) | Ment minden diát a prezentációból egy fájlba a megadott formátummal. |
| [save(OutputStream stream, int format)](#save-java.io.OutputStream-int-) | Ment minden diát a prezentációból egy adatfolyamra a megadott formátummal. |
| [save(String fname, int format, ISaveOptions options)](#save-java.lang.String-int-com.aspose.slides.ISaveOptions-) | Ment minden diát a prezentációból egy fájlba a megadott formátummal és további beállításokkal. |
| [save(OutputStream stream, int format, ISaveOptions options)](#save-java.io.OutputStream-int-com.aspose.slides.ISaveOptions-) | Ment minden diát a prezentációból egy adatfolyamra a megadott formátummal és további beállításokkal. |
| [save(String fname, int[] slides, int format)](#save-java.lang.String-int---int-) | Ment megadott diákat a prezentációból egy fájlba a megadott formátummal. |
| [save(String fname, int[] slides, int format, ISaveOptions options)](#save-java.lang.String-int---int-com.aspose.slides.ISaveOptions-) | Ment megadott diákat a prezentációból egy fájlba a megadott formátummal. |
| [save(OutputStream stream, int[] slides, int format)](#save-java.io.OutputStream-int---int-) | Ment megadott diákat a prezentációból egy adatfolyamra a megadott formátummal. |
| [save(OutputStream stream, int[] slides, int format, ISaveOptions options)](#save-java.io.OutputStream-int---int-com.aspose.slides.ISaveOptions-) | Ment megadott diákat a prezentációból egy adatfolyamra a megadott formátummal. |
| [save(IXamlOptions options)](#save-com.aspose.slides.IXamlOptions-) | Ment minden diát a prezentációból egy sor fájlba, amely XAML markup-ot képvisel. |
| [getImages(IRenderingOptions options)](#getImages-com.aspose.slides.IRenderingOptions-) | Visszaad egy Thumbnail Image objektumot minden prezentációs dia számára. |
| [getImages(IRenderingOptions options, int[] slides)](#getImages-com.aspose.slides.IRenderingOptions-int---) | Visszaad egy Thumbnail IImage objektumot a megadott diákhoz a prezentációban. |
| [getImages(IRenderingOptions options, float scaleX, float scaleY)](#getImages-com.aspose.slides.IRenderingOptions-float-float-) | Visszaad egy Thumbnail Image objektumot minden prezentációs diára egyedi méretezéssel. |
| [getImages(IRenderingOptions options, int[] slides, float scaleX, float scaleY)](#getImages-com.aspose.slides.IRenderingOptions-int---float-float-) | Visszaad egy Thumbnail Image objektumot a megadott diákhoz a prezentációban egyedi méretezéssel. |
| [getImages(IRenderingOptions options, Dimension imageSize)](#getImages-com.aspose.slides.IRenderingOptions-java.awt.Dimension-) | Visszaad egy Thumbnail Image objektumot minden prezentációs diára a megadott mérettel. |
| [getImages(IRenderingOptions options, int[] slides, Dimension imageSize)](#getImages-com.aspose.slides.IRenderingOptions-int---java.awt.Dimension-) | Visszaad egy Thumbnail Image objektumot a megadott diákhoz a prezentációban a megadott mérettel. |
| [getSlideById(long id)](#getSlideById-long-) | Visszaad egy Slide, MasterSlide vagy LayoutSlide objektumot az azonosító alapján. |
| [joinPortionsWithSameFormatting()](#joinPortionsWithSameFormatting--) | Egyesíti a futamokat azonos formázással az összes bekezdésben az összes megfelelő alakzatban minden dián. |
| [highlightText(String text, Color highlightColor)](#highlightText-java.lang.String-java.awt.Color-) | Kiemeli a mintaszöveg összes egyezését a megadott színnel. |
| [highlightText(String text, Color highlightColor, ITextSearchOptions options, IFindResultCallback callback)](#highlightText-java.lang.String-java.awt.Color-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-) | Kiemeli a mintaszöveg összes egyezését a megadott színnel. |
| [highlightRegex(Pattern regex, Color highlightColor, IFindResultCallback callback)](#highlightRegex-java.util.regex.Pattern-java.awt.Color-com.aspose.slides.IFindResultCallback-) | Kiemeli a reguláris kifejezés összes egyezését a megadott színnel. |
| [replaceText(String oldText, String newText, ITextSearchOptions options, IFindResultCallback callback)](#replaceText-java.lang.String-java.lang.String-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-) | Lecseréli a megadott szöveg összes előfordulását egy másik megadott szövegre. |
| [replaceRegex(Pattern regex, String newText, IFindResultCallback callback)](#replaceRegex-java.util.regex.Pattern-java.lang.String-com.aspose.slides.IFindResultCallback-) | Lecseréli a reguláris kifejezés összes egyezését a megadott karakterláncra. |

### getCurrentDateTime() {#getCurrentDateTime--}
```
public abstract Date getCurrentDateTime()
```

Visszaadja vagy beállítja a dátumot és az időt, amely helyettesíti a datetime mezők tartalmát. Alapértelmezés szerint a Presentation objektum létrehozásának ideje. Olvasás/írás java.util.Date.

**Visszatér:**
java.util.Date

### setCurrentDateTime(Date value) {#setCurrentDateTime-java.util.Date-}
```
public abstract void setCurrentDateTime(Date value)
```

Visszaadja vagy beállítja a dátumot és az időt, amely helyettesíti a datetime mezők tartalmát. Alapértelmezés szerint a Presentation objektum létrehozásának ideje. Olvasás/írás java.util.Date.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | java.util.Date |  |

### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public abstract IPresentationHeaderFooterManager getHeaderFooterManager()
```

Visszaadja a prezentáció HeaderFooter kezelőjét. Csak olvasható [IPresentationHeaderFooterManager](../../com.aspose.slides/ipresentationheaderfootermanager).

**Visszatér:**
[IPresentationHeaderFooterManager](../../com.aspose.slides/ipresentationheaderfootermanager)

### getProtectionManager() {#getProtectionManager--}
```
public abstract IProtectionManager getProtectionManager()
```

Megkapja a jogosultságok kezelőjét ehhez a prezentációhoz. Csak olvasható [IProtectionManager](../../com.aspose.slides/iprotectionmanager).

**Visszatér:**
[IProtectionManager](../../com.aspose.slides/iprotectionmanager)

### getSlides() {#getSlides--}
```
public abstract ISlideCollection getSlides()
```

Visszaad egy listát az összes diáról, amely a prezentációban van definiálva. Csak olvasható [ISlideCollection](../../com.aspose.slides/islidecollection).

**Visszatér:**
[ISlideCollection](../../com.aspose.slides/islidecollection)

### getSections() {#getSections--}
```
public abstract ISectionCollection getSections()
```

Visszaad egy listát az összes dia szekcióról, amely a prezentációban van definiálva. Csak olvasható [ISectionCollection](../../com.aspose.slides/isectioncollection).

**Visszatér:**
[ISectionCollection](../../com.aspose.slides/isectioncollection)

### getSlideSize() {#getSlideSize--}
```
public abstract ISlideSize getSlideSize()
```

Visszaadja a dia méret objektumot. Csak olvasható [ISlideSize](../../com.aspose.slides/islidesize).

**Visszatér:**
[ISlideSize](../../com.aspose.slides/islidesize)

### getNotesSize() {#getNotesSize--}
```
public abstract INotesSize getNotesSize()
```

Visszaadja a jegyzet dia méret objektumot. Csak olvasható [INotesSize](../../com.aspose.slides/inotessize).

**Visszatér:**
[INotesSize](../../com.aspose.slides/inotessize)

### getLayoutSlides() {#getLayoutSlides--}
```
public abstract IGlobalLayoutSlideCollection getLayoutSlides()
```

Visszaad egy listát az összes elrendezés diáról, amely a prezentációban van definiálva. Csak olvasható [IGlobalLayoutSlideCollection](../../com.aspose.slides/igloballayoutslidecollection).

--------------------

Alternatív API-t a layout diákat hozzáadásához/beszúrásához/eltávolításhoz/klónozáshoz a **IMasterSlide.LayoutSlides** tulajdonság használatával érheti el.

**Visszatér:**
[IGlobalLayoutSlideCollection](../../com.aspose.slides/igloballayoutslidecollection)

### getMasters() {#getMasters--}
```
public abstract IMasterSlideCollection getMasters()
```

Visszaad egy listát az összes mester diáról, amely a prezentációban van definiálva. Csak olvasható [IMasterSlideCollection](../../com.aspose.slides/imasterslidecollection).

**Visszatér:**
[IMasterSlideCollection](../../com.aspose.slides/imasterslidecollection)

### getMasterNotesSlideManager() {#getMasterNotesSlideManager--}
```
public abstract IMasterNotesSlideManager getMasterNotesSlideManager()
```

Visszaadja a jegyzet mester kezelőt. Csak olvasható [IMasterNotesSlideManager](../../com.aspose.slides/imasternotesslidemanager).

**Visszatér:**
[IMasterNotesSlideManager](../../com.aspose.slides/imasternotesslidemanager)

### getMasterHandoutSlideManager() {#getMasterHandoutSlideManager--}
```
public abstract IMasterHandoutSlideManager getMasterHandoutSlideManager()
```

Visszaadja a kézbesítő mester kezelőt. Csak olvasható [IMasterHandoutSlideManager](../../com.aspose.slides/imasterhandoutslidemanager).

**Visszatér:**
[IMasterHandoutSlideManager](../../com.aspose.slides/imasterhandoutslidemanager)

### getFontsManager() {#getFontsManager--}
```
public abstract IFontsManager getFontsManager()
```

Visszaadja a betűtípusok kezelőjét. Csak olvasható [IFontsManager](../../com.aspose.slides/ifontsmanager).

**Visszatér:**
[IFontsManager](../../com.aspose.slides/ifontsmanager)

### getDefaultTextStyle() {#getDefaultTextStyle--}
```
public abstract ITextStyle getDefaultTextStyle()
```

Visszaadja az alakzatok alapértelmezett szövegstílusát. Csak olvasható [ITextStyle](../../com.aspose.slides/itextstyle).

**Visszatér:**
[ITextStyle](../../com.aspose.slides/itextstyle)

### getCommentAuthors() {#getCommentAuthors--}
```
public abstract ICommentAuthorCollection getCommentAuthors()
```

Visszaadja a hozzászólások szerzőinek gyűjteményét. Csak olvasható [ICommentAuthorCollection](../../com.aspose.slides/icommentauthorcollection).

**Visszatér:**
[ICommentAuthorCollection](../../com.aspose.slides/icommentauthorcollection)

### getDocumentProperties() {#getDocumentProperties--}
```
public abstract IDocumentProperties getDocumentProperties()
```

Visszaad egy DocumentProperties objektumot, amely szabványos és egyedi dokumentum tulajdonságokat tartalmaz. Csak olvasható [IDocumentProperties](../../com.aspose.slides/idocumentproperties).

**Visszatér:**
[IDocumentProperties](../../com.aspose.slides/idocumentproperties)

### getImages() {#getImages--}
```
public abstract IImageCollection getImages()
```

Visszaadja az összes kép gyűjteményét a prezentációban. Csak olvasható [IImageCollection](../../com.aspose.slides/iimagecollection).

**Visszatér:**
[IImageCollection](../../com.aspose.slides/iimagecollection)

### getAudios() {#getAudios--}
```
public abstract IAudioCollection getAudios()
```

Visszaadja az összes beágyazott audio fájl gyűjteményét a prezentációban. Csak olvasható [IAudioCollection](../../com.aspose.slides/iaudiocollection).

**Visszatér:**
[IAudioCollection](../../com.aspose.slides/iaudiocollection)

### getVideos() {#getVideos--}
```
public abstract IVideoCollection getVideos()
```

Visszaadja az összes beágyazott video fájl gyűjteményét a prezentációban. Csak olvasható [IVideoCollection](../../com.aspose.slides/ivideocollection).

**Visszatér:**
[IVideoCollection](../../com.aspose.slides/ivideocollection)

### getCustomData() {#getCustomData--}
```
public abstract ICustomData getCustomData()
```

Visszaadja a prezentáció egyedi adatait. Csak olvasható [ICustomData](../../com.aspose.slides/icustomdata).

**Visszatér:**
[ICustomData](../../com.aspose.slides/icustomdata)

### getVbaProject() {#getVbaProject--}
```
public abstract IVbaProject getVbaProject()
```

Megkapja a VBA projektet a prezentáció makrókkal. Olvasás/írás [IVbaProject](../../com.aspose.slides/ivbaproject).

**Visszatér:**
[IVbaProject](../../com.aspose.slides/ivbaproject)

### setVbaProject(IVbaProject value) {#setVbaProject-com.aspose.slides.IVbaProject-}
```
public abstract void setVbaProject(IVbaProject value)
```

Megkapja a VBA projektet a prezentáció makrókkal. Olvasás/írás [IVbaProject](../../com.aspose.slides/ivbaproject).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | [IVbaProject](../../com.aspose.slides/ivbaproject) |  |

### getSourceFormat() {#getSourceFormat--}
```
public abstract int getSourceFormat()
```

Visszaad információt arról, hogy melyik formátumból lett betöltve a prezentáció. Csak olvasható [SourceFormat](../../com.aspose.slides/sourceformat).

**Visszatér:**
int

### getMasterTheme() {#getMasterTheme--}
```
public abstract IMasterTheme getMasterTheme()
```

Visszaadja a prezentáció mester témáját. Csak olvasható [IMasterTheme](../../com.aspose.slides/imastertheme).

**Visszatér:**
[IMasterTheme](../../com.aspose.slides/imastertheme)

### getHyperlinkQueries() {#getHyperlinkQueries--}
```
public abstract IHyperlinkQueries getHyperlinkQueries()
```

Könnyű hozzáférést biztosít az összes hiperhivatkozáshoz, amely az összes prezentációs dián található (nem a mester, elrendezés vagy jegyzet diákon). Csak olvasható [IHyperlinkQueries](../../com.aspose.slides/ihyperlinkqueries).

**Visszatér:**
[IHyperlinkQueries](../../com.aspose.slides/ihyperlinkqueries)

### getViewProperties() {#getViewProperties--}
```
public abstract IViewProperties getViewProperties()
```

Megkapja a prezentáció szintű nézeti tulajdonságokat. Csak olvasható [IViewProperties](../../com.aspose.slides/iviewproperties).

**Visszatér:**
[IViewProperties](../../com.aspose.slides/iviewproperties)

### getFirstSlideNumber() {#getFirstSlideNumber--}
```
public abstract int getFirstSlideNumber()
```

A prezentáció első dia számát jelöli. Olvasás/írás int.

**Visszatér:**
int

### setFirstSlideNumber(int value) {#setFirstSlideNumber-int-}
```
public abstract void setFirstSlideNumber(int value)
```

A prezentáció első dia számát jelöli. Olvasás/írás int.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |

### getAllCustomXmlParts() {#getAllCustomXmlParts--}
```
public abstract ICustomXmlPart[] getAllCustomXmlParts()
```

Visszaadja az összes egyedi adat részt a prezentációban. Csak olvasható ICustomXmlPart[].

**Visszatér:**
com.aspose.slides.ICustomXmlPart[]

### getDigitalSignatures() {#getDigitalSignatures--}
```
public abstract IDigitalSignatureCollection getDigitalSignatures()
```

Visszaadja a prezentáció aláírásához használt aláírások gyűjteményét. Csak olvasható [IDigitalSignatureCollection](../../com.aspose.slides/idigitalsignaturecollection).

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

Visszaadja a prezentáció dokumentumra alkalmazott érzékenységi címkék gyűjteményét. Csak olvasható [ISensitivityLabelCollection](../../com.aspose.slides/isensitivitylabelcollection).

--------------------

> ```
> Presentation pres = new Presentation("SomePresentation.pptx");
>  try {
>      ISensitivityLabelCollection sensitivityLabels = pres.getSensitivityLabels();
> 
>      // Írja ki a alkalmazott címkéket
>      for (ISensitivityLabel sensitivityLabel : sensitivityLabels)
>          System.out.println("Label Id " + sensitivityLabel.getId() + " from Azure AD site " + sensitivityLabel.getSiteId());
> 
>      // Adja hozzá az új címkét
>      String labelIdString = "{xxxxxxxx-xxxx-xxxx-xxxx-xxxxxxxxxxxx}"; // Szerezze be az érzékenységi címke azonosítóját a szabályzatból
>      UUID siteIdGuid = UUID.fromString("{xxxxxxxx-xxxx-xxxx-xxxx-xxxxxxxxxxxx}"); // Szerezze be az Azure AD oldal azonosítóját a szabályzatból
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

Ment minden diát a prezentációból egy fájlba a megadott formátummal.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| fname | java.lang.String | A létrehozandó fájl elérési útja. |
| format | int | Az exportált adatok formátuma. |

### save(OutputStream stream, int format) {#save-java.io.OutputStream-int-}
```
public abstract void save(OutputStream stream, int format)
```

Ment minden diát a prezentációból egy adatfolyamra a megadott formátummal.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| stream | java.io.OutputStream | Kimeneti adatfolyam. |
| format | int | Az exportált adatok formátuma. |

### save(String fname, int format, ISaveOptions options) {#save-java.lang.String-int-com.aspose.slides.ISaveOptions-}
```
public abstract void save(String fname, int format, ISaveOptions options)
```

Ment minden diát a prezentációból egy fájlba a megadott formátummal és további opciókkal.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| fname | java.lang.String | A létrehozandó fájl elérési útja. |
| format | int | Az exportált adatok formátuma. |
| options | [ISaveOptions](../../com.aspose.slides/isaveoptions) | További formátumbeállítások. |

### save(OutputStream stream, int format, ISaveOptions options) {#save-java.io.OutputStream-int-com.aspose.slides.ISaveOptions-}
```
public abstract void save(OutputStream stream, int format, ISaveOptions options)
```

Ment minden diát egy prezentációból egy adatfolyamra a megadott formátumban, további beállításokkal.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| stream | java.io.OutputStream | Kimeneti adatfolyam. |
| format | int | Az exportált adatok formátuma. |
| options | [ISaveOptions](../../com.aspose.slides/isaveoptions) | További formátumbeállítások. |

### save(String fname, int[] slides, int format) {#save-java.lang.String-int---int-}
```
public abstract void save(String fname, int[] slides, int format)
```

A megadott diák egy prezentációból egy fájlba menti a megadott formátummal.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| fname | java.lang.String | Az elkészített fájl elérési útja. |
| slides | int[] | Diapozíciókat tartalmazó tömb, 1-től kezdve. |
| format | int | Az exportált adatok formátuma. |

### save(String fname, int[] slides, int format, ISaveOptions options) {#save-java.lang.String-int---int-com.aspose.slides.ISaveOptions-}
```
public abstract void save(String fname, int[] slides, int format, ISaveOptions options)
```

A megadott diák egy prezentációból egy fájlba menti a megadott formátummal.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| fname | java.lang.String | Az elkészített fájl elérési útja. |
| slides | int[] | Diapozíciókat tartalmazó tömb, 1-től kezdve. |
| format | int | Az exportált adatok formátuma. |
| options | [ISaveOptions](../../com.aspose.slides/isaveoptions) | További formátumbeállítások. |

### save(OutputStream stream, int[] slides, int format) {#save-java.io.OutputStream-int---int-}
```
public abstract void save(OutputStream stream, int[] slides, int format)
```

A megadott diák egy prezentációból egy adatfolyamra menti a megadott formátummal.

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

A megadott diák egy prezentációból egy adatfolyamra menti a megadott formátummal.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| stream | java.io.OutputStream | Kimeneti adatfolyam. |
| slides | int[] | Diapozíciókat tartalmazó tömb, 1-től kezdve. |
| format | int | Az exportált adatok formátuma. |
| options | [ISaveOptions](../../com.aspose.slides/isaveoptions) | További formátumbeállítások. |

### save(IXamlOptions options) {#save-com.aspose.slides.IXamlOptions-}
```
public abstract void save(IXamlOptions options)
```

Ment minden diát egy prezentációból egy XAML jelölőnyelvet képviselő fájlkészletbe.

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
| options | [IXamlOptions](../../com.aspose.slides/ixamloptions) | A XAML formátum opciói. |

### getImages(IRenderingOptions options) {#getImages-com.aspose.slides.IRenderingOptions-}
```
public abstract IImage[] getImages(IRenderingOptions options)
```

Visszaad Miniatűr kép objektumokat minden diához a prezentációban.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Renderelési opciók. |

**Visszatérési érték:**
com.aspose.slides.IImage[] - IImage objects.

### getImages(IRenderingOptions options, int[] slides) {#getImages-com.aspose.slides.IRenderingOptions-int---}
```
public abstract IImage[] getImages(IRenderingOptions options, int[] slides)
```

Visszaad Miniatűr IImage objektumokat a megadott diákhoz egy prezentációban.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Renderelési opciók. |
| slides | int[] | Diapozíciókat tartalmazó tömb, 1-től kezdve. |

**Visszatérési érték:**
com.aspose.slides.IImage[] - IImage objects.

### getImages(IRenderingOptions options, float scaleX, float scaleY) {#getImages-com.aspose.slides.IRenderingOptions-float-float-}
```
public abstract IImage[] getImages(IRenderingOptions options, float scaleX, float scaleY)
```

Visszaad Miniatűr kép objektumokat minden diához egy prezentációban, egyedi méretezéssel.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Renderelési opciók. |
| scaleX | float | Az érték, amellyel az X tengelyen méretezi a Miniatűrt. |
| scaleY | float | Az érték, amellyel az Y tengelyen méretezi a Miniatűrt. |

**Visszatérési érték:**
com.aspose.slides.IImage[] - Bitmap objects.

### getImages(IRenderingOptions options, int[] slides, float scaleX, float scaleY) {#getImages-com.aspose.slides.IRenderingOptions-int---float-float-}
```
public abstract IImage[] getImages(IRenderingOptions options, int[] slides, float scaleX, float scaleY)
```

Visszaad Miniatűr kép objektumokat a megadott diákhoz egy prezentációban, egyedi méretezéssel.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Renderelési opciók. |
| slides | int[] | Diapozíciókat tartalmazó tömb, 1-től kezdve. |
| scaleX | float | Az érték, amellyel az X tengelyen méretezi a Miniatűrt. |
| scaleY | float | Az érték, amellyel az Y tengelyen méretezi a Miniatűrt. |

**Visszatérési érték:**
com.aspose.slides.IImage[] - IImage objects.

### getImages(IRenderingOptions options, Dimension imageSize) {#getImages-com.aspose.slides.IRenderingOptions-java.awt.Dimension-}
```
public abstract IImage[] getImages(IRenderingOptions options, Dimension imageSize)
```

Visszaad Miniatűr kép objektumokat minden diához egy prezentációban a megadott mérettel.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Renderelési opciók. |
| imageSize | java.awt.Dimension | A létrehozandó kép mérete. |

**Visszatérési érték:**
com.aspose.slides.IImage[] - IImage objects.

### getImages(IRenderingOptions options, int[] slides, Dimension imageSize) {#getImages-com.aspose.slides.IRenderingOptions-int---java.awt.Dimension-}
```
public abstract IImage[] getImages(IRenderingOptions options, int[] slides, Dimension imageSize)
```

Visszaad Miniatűr kép objektumokat a megadott diákhoz egy prezentációban a megadott mérettel.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Renderelési opciók. |
| slides | int[] | Diapozíciókat tartalmazó tömb, 1-től kezdve. |
| imageSize | java.awt.Dimension | A létrehozandó kép mérete. |

**Visszatérési érték:**
com.aspose.slides.IImage[] - IImage objects.

### getSlideById(long id) {#getSlideById-long-}
```
public abstract IBaseSlide getSlideById(long id)
```

Visszaad egy Slide, MasterSlide vagy LayoutSlide objektumot azonosító alapján.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| id | long | A dia azonosítója. |

**Visszatérési érték:**
[IBaseSlide](../../com.aspose.slides/ibaseslide) - IBaseSlide object.

### joinPortionsWithSameFormatting() {#joinPortionsWithSameFormatting--}
```
public abstract void joinPortionsWithSameFormatting()
```

Azonos formázású szövegrészeket egyesíti az összes bekezdésben, minden elfogadható alakzatban, minden dián.

### highlightText(String text, Color highlightColor) {#highlightText-java.lang.String-java.awt.Color-}
```
public abstract void highlightText(String text, Color highlightColor)
```

Kiemeli a minta szövegre illeszkedő összes találatot a megadott színnel.

--------------------

> ```
> The following code sample shows how to highlight text in a PowerPoint presentation.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      // összes különálló 'the' előfordulás kiemelése
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
| highlightColor | java.awt.Color | A szöveget kiemelő szín. |

### highlightText(String text, Color highlightColor, ITextSearchOptions options, IFindResultCallback callback) {#highlightText-java.lang.String-java.awt.Color-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-}
```
public abstract void highlightText(String text, Color highlightColor, ITextSearchOptions options, IFindResultCallback callback)
```

Kiemeli a minta szövegre illeszkedő összes találatot a megadott színnel.

--------------------

> ```
> The following code sample shows how to highlight text in a PowerPoint presentation.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      // összes különálló 'the' előfordulás kiemelése
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
| highlightColor | java.awt.Color | A szöveget kiemelő szín. |
| options | [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions) | Szövegkeresési opciók [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions). |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | A visszahívási objektum a keresési eredmények fogadásához [IFindResultCallback](../../com.aspose.slides/ifindresultcallback). |

### highlightRegex(Pattern regex, Color highlightColor, IFindResultCallback callback) {#highlightRegex-java.util.regex.Pattern-java.awt.Color-com.aspose.slides.IFindResultCallback-}
```
public abstract void highlightRegex(Pattern regex, Color highlightColor, IFindResultCallback callback)
```

Kiemeli a reguláris kifejezés összes találatát a megadott színnel.

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

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| regex | java.util.regex.Pattern | A kiemelendő karakterláncokhoz használt reguláris kifejezés java.util.regex.Pattern. |
| highlightColor | java.awt.Color | A szöveget kiemelő szín. |
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
| oldText | java.lang.String | A lecserélendő karakterlánc. |
| newText | java.lang.String | A karakterlánc, amely az oldText összes előfordulását helyettesíti. |
| options | [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions) | Szövegkeresési opciók [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions). |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | A visszahívási objektum a keresési eredmények fogadásához [IFindResultCallback](../../com.aspose.slides/ifindresultcallback). |

### replaceRegex(Pattern regex, String newText, IFindResultCallback callback) {#replaceRegex-java.util.regex.Pattern-java.lang.String-com.aspose.slides.IFindResultCallback-}
```
public abstract void replaceRegex(Pattern regex, String newText, IFindResultCallback callback)
```

Lecseréli a reguláris kifejezés összes találatát a megadott karakterláncra.

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
| regex | java.util.regex.Pattern | A lecserélendő karakterláncokhoz használt reguláris kifejezés java.util.regex.Pattern. |
| newText | java.lang.String | A karakterlánc, amely a lecserélendő karakterláncok összes előfordulását helyettesíti. |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | A visszahívási objektum a keresési eredmények fogadásához [IFindResultCallback](../../com.aspose.slides/ifindresultcallback). |