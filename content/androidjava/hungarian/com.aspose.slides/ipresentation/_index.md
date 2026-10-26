---
title: IPresentation
second_title: Aspose.Slides for Android Java API-referencia
description: Prezentációs dokumentum
type: docs
url: /hu/com.aspose.slides/ipresentation/
---
**Minden megvalósított interfész:**
[com.aspose.slides.IPresentationComponent](../../com.aspose.slides/ipresentationcomponent), com.aspose.ms.System.IDisposable
```
public interface IPresentation extends IPresentationComponent, System.IDisposable
```

Prezentáció dokumentum
## Metódusok

| Metódus | Leírás |
| --- | --- |
| [getCurrentDateTime()](#getCurrentDateTime--) | Visszaadja vagy beállítja a dátumot és időt, amely helyettesíti a datetime mezők tartalmát. |
| [setCurrentDateTime(Date value)](#setCurrentDateTime-java.util.Date-) | Visszaadja vagy beállítja a dátumot és időt, amely helyettesíti a datetime mezők tartalmát. |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | Visszaadja a prezentáció HeaderFooter kezelőjét. |
| [getProtectionManager()](#getProtectionManager--) | Lekéri a prezentáció jogosultságkezelőjét. |
| [getSlides()](#getSlides--) | Visszaadja az összes diát, amely a prezentációban definiálva van. |
| [getSections()](#getSections--) | Visszaadja az összes diarészletet, amely a prezentációban definiálva van. |
| [getSlideSize()](#getSlideSize--) | Visszaadja a dia méret objektumát. |
| [getNotesSize()](#getNotesSize--) | Visszaadja a jegyzetdia méret objektumát. |
| [getLayoutSlides()](#getLayoutSlides--) | Visszaadja az összes elrendezési diát, amely a prezentációban definiálva van. |
| [getMasters()](#getMasters--) | Visszaadja az összes mesterdiát, amely a prezentációban definiálva van. |
| [getMasterNotesSlideManager()](#getMasterNotesSlideManager--) | Visszaadja a jegyzet-mester kezelőt. |
| [getMasterHandoutSlideManager()](#getMasterHandoutSlideManager--) | Visszaadja a szórólap-mester kezelőt. |
| [getFontsManager()](#getFontsManager--) | Visszaadja a betűtípusok kezelőjét. |
| [getDefaultTextStyle()](#getDefaultTextStyle--) | Visszaadja az alakzatok alapértelmezett szövegstílusát. |
| [getCommentAuthors()](#getCommentAuthors--) | Visszaadja a megjegyzés szerzők gyűjteményét. |
| [getDocumentProperties()](#getDocumentProperties--) | Visszaadja a DocumentProperties objektumot, amely szabványos és egyedi dokumentumtulajdonságokat tartalmaz. |
| [getImages()](#getImages--) | Visszaadja a prezentáció összes képének gyűjteményét. |
| [getAudios()](#getAudios--) | Visszaadja a prezentációba ágyazott összes hangfájl gyűjteményét. |
| [getVideos()](#getVideos--) | Visszaadja a prezentációba ágyazott összes videofájl gyűjteményét. |
| [getCustomData()](#getCustomData--) | Visszaadja a prezentáció egyéni adatait. |
| [getVbaProject()](#getVbaProject--) | Lekéri a VBA projektet a prezentáció makróival. |
| [setVbaProject(IVbaProject value)](#setVbaProject-com.aspose.slides.IVbaProject-) | Lekéri a VBA projektet a prezentáció makróival. |
| [getSourceFormat()](#getSourceFormat--) | Visszaadja, melyik formátumból lett betöltve a prezentáció. |
| [getMasterTheme()](#getMasterTheme--) | Visszaadja a prezentáció mester témáját. |
| [getHyperlinkQueries()](#getHyperlinkQueries--) | Könnyű hozzáférést biztosít az összes hiperhivatkozáshoz, amely minden prezentációs dián található (kivéve a mestert, elrendezést és jegyzetdiákat). |
| [getViewProperties()](#getViewProperties--) | Lekéri a prezentációra kiterjedő nézeti tulajdonságokat. |
| [getFirstSlideNumber()](#getFirstSlideNumber--) | A prezentáció első diája számát jelöli. |
| [setFirstSlideNumber(int value)](#setFirstSlideNumber-int-) | A prezentáció első diája számát jelöli. |
| [getAllCustomXmlParts()](#getAllCustomXmlParts--) | Visszaadja a prezentáció összes egyéni adat részét. |
| [getDigitalSignatures()](#getDigitalSignatures--) | Visszaadja a prezentáció aláírásához használt aláírások gyűjteményét. |
| [getSensitivityLabels()](#getSensitivityLabels--) | Visszaadja a prezentáció dokumentumra alkalmazott érzékenységi címkék gyűjteményét. |
| [save(String fname, int format)](#save-java.lang.String-int-) | Elmenti a prezentáció összes diát a megadott formátumban egy fájlba. |
| [save(OutputStream stream, int format)](#save-java.io.OutputStream-int-) | Elmenti a prezentáció összes diát a megadott formátumban egy stream-be. |
| [save(String fname, int format, ISaveOptions options)](#save-java.lang.String-int-com.aspose.slides.ISaveOptions-) | Elmenti a prezentáció összes diát a megadott formátumban egy fájlba, további opciókkal. |
| [save(OutputStream stream, int format, ISaveOptions options)](#save-java.io.OutputStream-int-com.aspose.slides.ISaveOptions-) | Elmenti a prezentáció összes diát a megadott formátumban egy stream-be, további opciókkal. |
| [save(String fname, int[] slides, int format)](#save-java.lang.String-int---int-) | Elmenti a megadott diákat a prezentációból a megadott formátumban egy fájlba. |
| [save(String fname, int[] slides, int format, ISaveOptions options)](#save-java.lang.String-int---int-com.aspose.slides.ISaveOptions-) | Elmenti a megadott diákat a prezentációból a megadott formátumban egy fájlba. |
| [save(OutputStream stream, int[] slides, int format)](#save-java.io.OutputStream-int---int-) | Elmenti a megadott diákat a prezentációból a megadott formátumban egy stream-be. |
| [save(OutputStream stream, int[] slides, int format, ISaveOptions options)](#save-java.io.OutputStream-int---int-com.aspose.slides.ISaveOptions-) | Elmenti a megadott diákat a prezentációból a megadott formátumban egy stream-be. |
| [save(IXamlOptions options)](#save-com.aspose.slides.IXamlOptions-) | Elmenti a prezentáció összes diát XAML jelölőnyelvnek megfelelő fájlkészletbe. |
| [getImages(IRenderingOptions options)](#getImages-com.aspose.slides.IRenderingOptions-) | Visszaadja a Miniatűr kép objektumokat a prezentáció összes diájához. |
| [getImages(IRenderingOptions options, int[] slides)](#getImages-com.aspose.slides.IRenderingOptions-int---) | Visszaadja a Miniatűr IImage objektumokat a megadott diákhoz. |
| [getImages(IRenderingOptions options, float scaleX, float scaleY)](#getImages-com.aspose.slides.IRenderingOptions-float-float-) | Visszaadja a Miniatűr kép objektumokat a prezentáció összes diájához egyedi méretezéssel. |
| [getImages(IRenderingOptions options, int[] slides, float scaleX, float scaleY)](#getImages-com.aspose.slides.IRenderingOptions-int---float-float-) | Visszaadja a Miniatűr kép objektumokat a megadott diákhoz egyedi méretezéssel. |
| [getImages(IRenderingOptions options, Size imageSize)](#getImages-com.aspose.slides.IRenderingOptions-com.aspose.slides.android.Size-) | Visszaadja a Miniatűr kép objektumokat a prezentáció összes diájához a megadott mérettel. |
| [getImages(IRenderingOptions options, int[] slides, Size imageSize)](#getImages-com.aspose.slides.IRenderingOptions-int---com.aspose.slides.android.Size-) | Visszaadja a Miniatűr kép objektumokat a megadott diákhoz a megadott mérettel. |
| [getSlideById(long id)](#getSlideById-long-) | Visszaadja a diát, MasterSlide-t vagy LayoutSlide-t azonosító alapján. |
| [joinPortionsWithSameFormatting()](#joinPortionsWithSameFormatting--) | Egyesíti a hasonló formázású futamokat az összes bekezdésben és elfogadható alakzatban az összes dián. |
| [highlightText(String text, Integer highlightColor)](#highlightText-java.lang.String-java.lang.Integer-) | Kiemeli a mintaszöveg összes egyezését a megadott színnel. |
| [highlightText(String text, Integer highlightColor, ITextSearchOptions options, IFindResultCallback callback)](#highlightText-java.lang.String-java.lang.Integer-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-) | Kiemeli a mintaszöveg összes egyezését a megadott színnel. |
| [highlightRegex(Pattern regex, Integer highlightColor, IFindResultCallback callback)](#highlightRegex-java.util.regex.Pattern-java.lang.Integer-com.aspose.slides.IFindResultCallback-) | Kiemeli a reguláris kifejezés összes egyezését a megadott színnel. |
| [replaceText(String oldText, String newText, ITextSearchOptions options, IFindResultCallback callback)](#replaceText-java.lang.String-java.lang.String-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-) | Lecseréli a megadott szöveg összes előfordulását egy másik megadott szövegre. |
| [replaceRegex(Pattern regex, String newText, IFindResultCallback callback)](#replaceRegex-java.util.regex.Pattern-java.lang.String-com.aspose.slides.IFindResultCallback-) | Lecseréli a reguláris kifejezés összes egyezését a megadott karakterláncra. |

### getCurrentDateTime() {#getCurrentDateTime--}
```
public abstract Date getCurrentDateTime()
```

Olvasás/írás java.util.Date.

**Visszatér:**
java.util.Date

### setCurrentDateTime(Date value) {#setCurrentDateTime-java.util.Date-}
```
public abstract void setCurrentDateTime(Date value)
```

Olvasás/írás java.util.Date.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | java.util.Date |  |

### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public abstract IPresentationHeaderFooterManager getHeaderFooterManager()
```

Csak olvasható [IPresentationHeaderFooterManager](../../com.aspose.slides/ipresentationheaderfootermanager).

**Visszatér:**
[IPresentationHeaderFooterManager](../../com.aspose.slides/ipresentationheaderfootermanager)

### getProtectionManager() {#getProtectionManager--}
```
public abstract IProtectionManager getProtectionManager()
```

Csak olvasható [IProtectionManager](../../com.aspose.slides/iprotectionmanager).

**Visszatér:**
[IProtectionManager](../../com.aspose.slides/iprotectionmanager)

### getSlides() {#getSlides--}
```
public abstract ISlideCollection getSlides()
```

Csak olvasható [ISlideCollection](../../com.aspose.slides/islidecollection).

**Visszatér:**
[ISlideCollection](../../com.aspose.slides/islidecollection)

### getSections() {#getSections--}
```
public abstract ISectionCollection getSections()
```

Csak olvasható [ISectionCollection](../../com.aspose.slides/isectioncollection).

**Visszatér:**
[ISectionCollection](../../com.aspose.slides/isectioncollection)

### getSlideSize() {#getSlideSize--}
```
public abstract ISlideSize getSlideSize()
```

Csak olvasható [ISlideSize](../../com.aspose.slides/islidesize).

**Visszatér:**
[ISlideSize](../../com.aspose.slides/islidesize)

### getNotesSize() {#getNotesSize--}
```
public abstract INotesSize getNotesSize()
```

Csak olvasható [INotesSize](../../com.aspose.slides/inotessize).

**Visszatér:**
[INotesSize](../../com.aspose.slides/inotessize)

### getLayoutSlides() {#getLayoutSlides--}
```
public abstract IGlobalLayoutSlideCollection getLayoutSlides()
```

Csak olvasható [IGlobalLayoutSlideCollection](../../com.aspose.slides/igloballayoutslidecollection).

--------------------

Alternatív API-t érhet el az elrendezési diák hozzáadásához/beszúrásához/eltávolításához/klónozásához az IMasterSlide.LayoutSlides tulajdonság használatával.

**Visszatér:**
[IGlobalLayoutSlideCollection](../../com.aspose.slides/igloballayoutslidecollection)

### getMasters() {#getMasters--}
```
public abstract IMasterSlideCollection getMasters()
```

Csak olvasható [IMasterSlideCollection](../../com.aspose.slides/imasterslidecollection).

**Visszatér:**
[IMasterSlideCollection](../../com.aspose.slides/imasterslidecollection)

### getMasterNotesSlideManager() {#getMasterNotesSlideManager--}
```
public abstract IMasterNotesSlideManager getMasterNotesSlideManager()
```

Csak olvasható [IMasterNotesSlideManager](../../com.aspose.slides/imasternotesslidemanager).

**Visszatér:**
[IMasterNotesSlideManager](../../com.aspose.slides/imasternotesslidemanager)

### getMasterHandoutSlideManager() {#getMasterHandoutSlideManager--}
```
public abstract IMasterHandoutSlideManager getMasterHandoutSlideManager()
```

Csak olvasható [IMasterHandoutSlideManager](../../com.aspose.slides/imasterhandoutslidemanager).

**Visszatér:**
[IMasterHandoutSlideManager](../../com.aspose.slides/imasterhandoutslidemanager)

### getFontsManager() {#getFontsManager--}
```
public abstract IFontsManager getFontsManager()
```

Csak olvasható [IFontsManager](../../com.aspose.slides/ifontsmanager).

**Visszatér:**
[IFontsManager](../../com.aspose.slides/ifontsmanager)

### getDefaultTextStyle() {#getDefaultTextStyle--}
```
public abstract ITextStyle getDefaultTextStyle()
```

Csak olvasható [ITextStyle](../../com.aspose.slides/itextstyle).

**Visszatér:**
[ITextStyle](../../com.aspose.slides/itextstyle)

### getCommentAuthors() {#getCommentAuthors--}
```
public abstract ICommentAuthorCollection getCommentAuthors()
```

Csak olvasható [ICommentAuthorCollection](../../com.aspose.slides/icommentauthorcollection).

**Visszatér:**
[ICommentAuthorCollection](../../com.aspose.slides/icommentauthorcollection)

### getDocumentProperties() {#getDocumentProperties--}
```
public abstract IDocumentProperties getDocumentProperties()
```

Csak olvasható [IDocumentProperties](../../com.aspose.slides/idocumentproperties).

**Visszatér:**
[IDocumentProperties](../../com.aspose.slides/idocumentproperties)

### getImages() {#getImages--}
```
public abstract IImageCollection getImages()
```

Csak olvasható [IImageCollection](../../com.aspose.slides/iimagecollection).

**Visszatér:**
[IImageCollection](../../com.aspose.slides/iimagecollection)

### getAudios() {#getAudios--}
```
public abstract IAudioCollection getAudios()
```

Csak olvasható [IAudioCollection](../../com.aspose.slides/iaudiocollection).

**Visszatér:**
[IAudioCollection](../../com.aspose.slides/iaudiocollection)

### getVideos() {#getVideos--}
```
public abstract IVideoCollection getVideos()
```

Csak olvasható [IVideoCollection](../../com.aspose.slides/ivideocollection).

**Visszatér:**
[IVideoCollection](../../com.aspose.slides/ivideocollection)

### getCustomData() {#getCustomData--}
```
public abstract ICustomData getCustomData()
```

Csak olvasható [ICustomData](../../com.aspose.slides/icustomdata).

**Visszatér:**
[ICustomData](../../com.aspose.slides/icustomdata)

### getVbaProject() {#getVbaProject--}
```
public abstract IVbaProject getVbaProject()
```

Olvasás/írás [IVbaProject](../../com.aspose.slides/ivbaproject).

**Visszatér:**
[IVbaProject](../../com.aspose.slides/ivbaproject)

### setVbaProject(IVbaProject value) {#setVbaProject-com.aspose.slides.IVbaProject-}
```
public abstract void setVbaProject(IVbaProject value)
```

Olvasás/írás [IVbaProject](../../com.aspose.slides/ivbaproject).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | [IVbaProject](../../com.aspose.slides/ivbaproject) |  |

### getSourceFormat() {#getSourceFormat--}
```
public abstract int getSourceFormat()
```

Csak olvasható [SourceFormat](../../com.aspose.slides/sourceformat).

**Visszatér:**
int

### getMasterTheme() {#getMasterTheme--}
```
public abstract IMasterTheme getMasterTheme()
```

Csak olvasható [IMasterTheme](../../com.aspose.slides/imastertheme).

**Visszatér:**
[IMasterTheme](../../com.aspose.slides/imastertheme)

### getHyperlinkQueries() {#getHyperlinkQueries--}
```
public abstract IHyperlinkQueries getHyperlinkQueries()
```

Csak olvasható [IHyperlinkQueries](../../com.aspose.slides/ihyperlinkqueries).

**Visszatér:**
[IHyperlinkQueries](../../com.aspose.slides/ihyperlinkqueries)

### getViewProperties() {#getViewProperties--}
```
public abstract IViewProperties getViewProperties()
```

Csak olvasható [IViewProperties](../../com.aspose.slides/iviewproperties).

**Visszatér:**
[IViewProperties](../../com.aspose.slides/iviewproperties)

### getFirstSlideNumber() {#getFirstSlideNumber--}
```
public abstract int getFirstSlideNumber()
```

Olvasás/írás int.

**Visszatér:**
int

### setFirstSlideNumber(int value) {#setFirstSlideNumber-int-}
```
public abstract void setFirstSlideNumber(int value)
```

Olvasás/írás int.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |

### getAllCustomXmlParts() {#getAllCustomXmlParts--}
```
public abstract ICustomXmlPart[] getAllCustomXmlParts()
```

Csak olvasható ICustomXmlPart[].

**Visszatér:**
com.aspose.slides.ICustomXmlPart[]

### getDigitalSignatures() {#getDigitalSignatures--}
```
public abstract IDigitalSignatureCollection getDigitalSignatures()
```

Csak olvasható [IDigitalSignatureCollection](../../com.aspose.slides/idigitalsignaturecollection).

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

Csak olvasható [ISensitivityLabelCollection](../../com.aspose.slides/isensitivitylabelcollection).

--------------------

> ```
> Presentation pres = new Presentation("SomePresentation.pptx");
>  try {
>      ISensitivityLabelCollection sensitivityLabels = pres.getSensitivityLabels();
> 
>      // A felhasznált címkék kiírása
>      for (ISensitivityLabel sensitivityLabel : sensitivityLabels)
>          System.out.println("Label Id " + sensitivityLabel.getId() + " from Azure AD site " + sensitivityLabel.getSiteId());
> 
>      // Az új címke hozzáadása
>      String labelIdString = "{xxxxxxxx-xxxx-xxxx-xxxx-xxxxxxxxxxxx}"; // A szenzitivitási címke azonosítójának lekérése a szabályzatból
>      UUID siteIdGuid = UUID.fromString("{xxxxxxxx-xxxx-xxxx-xxxx-xxxxxxxxxxxx}"); // Az Azure AD helyazonosító lekérése a szabályzatból
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

Elmenti a prezentáció összes diát a megadott formátumban egy fájlba.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| fname | java.lang.String | A létrehozott fájl elérési útja. |
| format | int | Az exportált adat formátuma. |

### save(OutputStream stream, int format) {#save-java.io.OutputStream-int-}
```
public abstract void save(OutputStream stream, int format)
```

Elmenti a prezentáció összes diát a megadott formátumban egy stream-be.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| stream | java.io.OutputStream | Kimeneti stream. |
| format | int | Az exportált adat formátuma. |

### save(String fname, int format, ISaveOptions options) {#save-java.lang.String-int-com.aspose.slides.ISaveOptions-}
```
public abstract void save(String fname, int format, ISaveOptions options)
```

Elmenti a prezentáció összes diát a megadott formátumban egy fájlba, további opciókkal.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| fname | java.lang.String | A létrehozott fájl elérési útja. |
| format | int | Az exportált adat formátuma. |
| options | [ISaveOptions](../../com.aspose.slides/isaveoptions) | További formátum opciók. |

### save(OutputStream stream, int format, ISaveOptions options) {#save-java.io.OutputStream-int-com.aspose.slides.ISaveOptions-}
```
public abstract void save(OutputStream stream, int format, ISaveOptions options)
```

Elmenti a prezentáció összes diát a megadott formátumban egy stream-be, további opciókkal.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| stream | java.io.OutputStream | Kimeneti stream. |
| format | int | Az exportált adat formátuma. |
| options | [ISaveOptions](../../com.aspose.slides/isaveoptions) | További formátum opciók. |

### save(String fname, int[] slides, int format) {#save-java.lang.String-int---int-}
```
public abstract void save(String fname, int[] slides, int format)
```

Elmenti a megadott diákat a prezentációból a megadott formátumban egy fájlba.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| fname | java.lang.String | A létrehozott fájl elérési útja. |
| slides | int[] | A diák pozíciói, 1-től kezdődően. |
| format | int | Az exportált adat formátuma. |

### save(String fname, int[] slides, int format, ISaveOptions options) {#save-java.lang.String-int---int-com.aspose.slides.ISaveOptions-}
```
public abstract void save(String fname, int[] slides, int format, ISaveOptions options)
```

Elmenti a megadott diákat a prezentációból a megadott formátumban egy fájlba.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| fname | java.lang.String | A létrehozott fájl elérési útja. |
| slides | int[] | A diák pozíciói, 1-től kezdődően. |
| format | int | Az exportált adat formátuma. |
| options | [ISaveOptions](../../com.aspose.slides/isaveoptions) | További formátum opciók. |

### save(OutputStream stream, int[] slides, int format) {#save-java.io.OutputStream-int---int-}
```
public abstract void save(OutputStream stream, int[] slides, int format)
```

Elmenti a megadott diákat a prezentációból a megadott formátumban egy stream-be.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| stream | java.io.OutputStream | Kimeneti stream. |
| slides | int[] | A diák pozíciói, 1-től kezdődően. |
| format | int | Az exportált adat formátuma. |

### save(OutputStream stream, int[] slides, int format, ISaveOptions options) {#save-java.io.OutputStream-int---int-com.aspose.slides.ISaveOptions-}
```
public abstract void save(OutputStream stream, int[] slides, int format, ISaveOptions options)
```

Elmenti a megadott diákat a prezentációból a megadott formátumban egy stream-be.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| stream | java.io.OutputStream | Kimeneti stream. |
| slides | int[] | A diák pozíciói, 1-től kezdődően. |
| format | int | Az exportált adat formátuma. |
| options | [ISaveOptions](../../com.aspose.slides/isaveoptions) | További formátum opciók. |

### save(IXamlOptions options) {#save-com.aspose.slides.IXamlOptions-}
```
public abstract void save(IXamlOptions options)
```

Elmenti a prezentáció összes diát XAML jelölőnyelvnek megfelelő fájlkészletbe.

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

Visszaad egy Miniatűr kép objektumot a prezentáció összes diájához.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Renderelési opciók. |

**Visszatér:**
com.aspose.slides.IImage[] - IImage objektumok.

### getImages(IRenderingOptions options, int[] slides) {#getImages-com.aspose.slides.IRenderingOptions-int---}
```
public abstract IImage[] getImages(IRenderingOptions options, int[] slides)
```

Visszaad egy Miniatűr IImage objektumot a megadott diákhoz.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Renderelési opciók. |
| slides | int[] | A diák pozíciói, 1-től kezdődően. |

**Visszatér:**
com.aspose.slides.IImage[] - IImage objektumok.

### getImages(IRenderingOptions options, float scaleX, float scaleY) {#getImages-com.aspose.slides.IRenderingOptions-float-float-}
```
public abstract IImage[] getImages(IRenderingOptions options, float scaleX, float scaleY)
```

Visszaad egy Miniatűr kép objektumot a prezentáció összes diájához egyedi méretezéssel.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Renderelési opciók. |
| scaleX | float | A Thumbnail X-tengelyen való méretezésének értéke. |
| scaleY | float | A Thumbnail Y-tengelyen való méretezésének értéke. |

**Visszatér:**
com.aspose.slides.IImage[] - Bitmap objektumok.

### getImages(IRenderingOptions options, int[] slides, float scaleX, float scaleY) {#getImages-com.aspose.slides.IRenderingOptions-int---float-float-}
```
public abstract IImage[] getImages(IRenderingOptions options, int[] slides, float scaleX, float scaleY)
```

Visszaad egy Miniatűr kép objektumot a megadott diákhoz egyedi méretezéssel.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Renderelési opciók. |
| slides | int[] | A diák pozíciói, 1-től kezdődően. |
| scaleX | float | A Thumbnail X-tengelyen való méretezésének értéke. |
| scaleY | float | A Thumbnail Y-tengelyen való méretezésének értéke. |

**Visszatér:**
com.aspose.slides.IImage[] - IImage objektumok.

### getImages(IRenderingOptions options, Size imageSize) {#getImages-com.aspose.slides.IRenderingOptions-com.aspose.slides.android.Size-}
```
public abstract IImage[] getImages(IRenderingOptions options, Size imageSize)
```

Visszaad egy Miniatűr kép objektumot a prezentáció összes diájához a megadott mérettel.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Renderelési opciók. |
| imageSize | [Size](../../com.aspose.slides.android/size) | A létrehozandó kép mérete. |

**Visszatér:**
com.aspose.slides.IImage[] - IImage objektumok.

### getImages(IRenderingOptions options, int[] slides, Size imageSize) {#getImages-com.aspose.slides.IRenderingOptions-int---com.aspose.slides.android.Size-}
```
public abstract IImage[] getImages(IRenderingOptions options, int[] slides, Size imageSize)
```

Visszaad egy Miniatűr kép objektumot a megadott diákhoz a megadott mérettel.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Renderelési opciók. |
| slides | int[] | A diák pozíciói, 1-től kezdődően. |
| imageSize | [Size](../../com.aspose.slides.android/size) | A létrehozandó kép mérete. |

**Visszatér:**
com.aspose.slides.IImage[] - IImage objektumok.

### getSlideById(long id) {#getSlideById-long-}
```
public abstract IBaseSlide getSlideById(long id)
```

Visszaadja a diát, MasterSlide-t vagy LayoutSlide-t azonosító alapján.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| id | long | A dia azonosítója. |

**Visszatér:**
[IBaseSlide](../../com.aspose.slides/ibaseslide) - IBaseSlide objektum.

### joinPortionsWithSameFormatting() {#joinPortionsWithSameFormatting--}
```
public abstract void joinPortionsWithSameFormatting()
```

Egyesíti a hasonló formázású futamokat az összes bekezdésben és elfogadható alakzatban az összes dián.

### highlightText(String text, Integer highlightColor) {#highlightText-java.lang.String-java.lang.Integer-}
```
public abstract void highlightText(String text, Integer highlightColor)
```

Kiemeli a mintaszöveg összes egyezését a megadott színnel.

--------------------

> ```
> The following code sample shows how to highlight text in a PowerPoint presentation.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      // a 'the' szó összes különálló előfordulásának kiemelése
>      presentation.highlightText("the", Color.MAGENTA);
>      presentation.save("SomePresentation-out2.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| text | java.lang.String | A kiemelni kívánt szöveg. |
| highlightColor | java.lang.Integer | A szöveg kiemeléséhez használt szín. |

### highlightText(String text, Integer highlightColor, ITextSearchOptions options, IFindResultCallback callback) {#highlightText-java.lang.String-java.lang.Integer-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-}
```
public abstract void highlightText(String text, Integer highlightColor, ITextSearchOptions options, IFindResultCallback callback)
```

Kiemeli a mintaszöveg összes egyezését a megadott színnel.

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

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| text | java.lang.String | A kiemelni kívánt szöveg. |
| highlightColor | java.lang.Integer | A szöveg kiemeléséhez használt szín. |
| options | [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions) | Szövegkeresési opciók [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions). |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | A keresési eredményeket fogadó visszahívási objektum [IFindResultCallback](../../com.aspose.slides/ifindresultcallback). |

### highlightRegex(Pattern regex, Integer highlightColor, IFindResultCallback callback) {#highlightRegex-java.util.regex.Pattern-java.lang.Integer-com.aspose.slides.IFindResultCallback-}
```
public abstract void highlightRegex(Pattern regex, Integer highlightColor, IFindResultCallback callback)
```

Kiemeli a reguláris kifejezés összes egyezését a megadott színnel.

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
| regex | java.util.regex.Pattern | A reguláris kifejezés, amelynek a találatait ki szeretné emelni. |
| highlightColor | java.lang.Integer | A szöveg kiemeléséhez használt szín. |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | A keresési eredményeket fogadó visszahívási objektum [IFindResultCallback](../../com.aspose.slides/ifindresultcallback). |

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
>      // Replace all separate 'the' occurrences with '***'
>      presentation.replaceText("the", "***", textSearchOptions, null);
>      presentation.save("SomePresentation-out2.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| oldText | java.lang.String | A cserélni kívánt karakterlánc. |
| newText | java.lang.String | A karakterlánc, amelyre az összes előfordulást cserélni kell. |
| options | [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions) | Szövegkeresési opciók [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions). |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | A keresési eredményeket fogadó visszahívási objektum [IFindResultCallback](../../com.aspose.slides/ifindresultcallback). |

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
>      // Az összes különálló 'the' előfordulást '***'-val helyettesíti
>      presentation.replaceText("the", "***", textSearchOptions, null);
>      presentation.save("SomePresentation-out2.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| regex | java.util.regex.Pattern | A reguláris kifejezés, amelynek a találatait cserélni szeretné. |
| newText | java.lang.String | A karakterlánc, amelyre az összes előfordulást cserélni kell. |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | A keresési eredményeket fogadó visszahívási objektum [IFindResultCallback](../../com.aspose.slides/ifindresultcallback). |