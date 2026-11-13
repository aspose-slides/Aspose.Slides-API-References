---
title: Presentation
second_title: Aspose.Slides Java API referenciája
description: Microsoft PowerPoint prezentációt reprezentál.
type: docs
url: /hu/com.aspose.slides/presentation/
---
**Öröklődés:**
java.lang.Object

**Az összes megvalósított interfész:**
[com.aspose.slides.IPresentation](../../com.aspose.slides/ipresentation), com.aspose.slides.IDOMObject
```
public final class Presentation implements IPresentation, IDOMObject
```

Microsoft PowerPoint prezentációt reprezentál.

--------------------

> ```
> The following example shows how to create PowerPoint Presentation.
>   
>  // Példányosít egy Presentation objektumot, amely egy prezentációfájlt képvisel
>  Presentation pres = new Presentation();
>  try {
>      // Lekéri az első dia
>      ISlide slide = pres.getSlides().get_Item(0);
>      // Hozzáad egy vonal típusú autoformát
>      slide.getShapes().addAutoShape(ShapeType.Line, 50, 150, 300, 0);
>      // Mentse a prezentációfájlt.
>      pres.save("NewPresentation_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>   
>   The following example shows how to open and save Presentation.
>   
>  // Betölt egy bármely támogatott fájlt a Presentation-ben, pl. ppt, pptx, odp stb.
>  Presentation pres = new Presentation("Sample.odp");
>  try {
>      // Mentse a prezentációfájlt.
>      pres.save("OutputPresenation.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

## Konstruktorok

| Konstruktor | Leírás |
| --- | --- |
| [Presentation()](#Presentation--) | Ez a konstruktor új prezentációt hoz létre a semmiből. |
| [Presentation(LoadOptions loadOptions)](#Presentation-com.aspose.slides.LoadOptions-) | Ez a konstruktor új prezentációt hoz létre a semmiből. |
| [Presentation(InputStream stream)](#Presentation-java.io.InputStream-) | Ez a konstruktor az elsődleges módja egy meglévő Presentation beolvasásának. |
| [Presentation(InputStream stream, LoadOptions loadOptions)](#Presentation-java.io.InputStream-com.aspose.slides.LoadOptions-) | Ez a konstruktor az elsődleges módja egy meglévő Presentation beolvasásának. |
| [Presentation(String file)](#Presentation-java.lang.String-) | Ez a konstruktor megkapja a forrásfájl útvonalát, ahonnan a Presentation tartalma beolvasásra kerül. |
| [Presentation(String file, LoadOptions loadOptions)](#Presentation-java.lang.String-com.aspose.slides.LoadOptions-) | Ez a konstruktor megkapja a forrásfájl útvonalát, ahonnan a Presentation tartalma beolvasásra kerül. |
## Metódusok

| Metódus | Leírás |
| --- | --- |
| [getCurrentDateTime()](#getCurrentDateTime--) | Visszaadja vagy beállítja a dátumot és időt, amely a datetime mezők tartalmát helyettesíti. |
| [setCurrentDateTime(Date value)](#setCurrentDateTime-java.util.Date-) | Visszaadja vagy beállítja a dátumot és időt, amely a datetime mezők tartalmát helyettesíti. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | Visszaadja a tényleges HeaderFooter kezelőt. |
| [getProtectionManager()](#getProtectionManager--) | Megkapja a prezentáció jogosultságkezelőjét. |
| [getSlides()](#getSlides--) | Visszaad egy listát a prezentációban definiált összes diáról. |
| [getSections()](#getSections--) | Visszaad egy listát a prezentációban definiált összes diaszekcióról. |
| [getSlideSize()](#getSlideSize--) | Visszaad egy diaméret objektumot. |
| [getNotesSize()](#getNotesSize--) | Visszaad egy jegyzetdia méret objektumot. |
| [getLayoutSlides()](#getLayoutSlides--) | Visszaad egy listát a prezentációban definiált összes elrendezési diáról. |
| [getMasters()](#getMasters--) | Visszaad egy listát a prezentációban definiált összes mester diáról. |
| [getMasterNotesSlideManager()](#getMasterNotesSlideManager--) | Visszaadja a jegyzetmester kezelőt. |
| [getMasterHandoutSlideManager()](#getMasterHandoutSlideManager--) | Visszaadja a kiadványmester kezelőt. |
| [getFontsManager()](#getFontsManager--) | Visszaadja a betűtípus kezelőt. |
| [getDefaultTextStyle()](#getDefaultTextStyle--) | Visszaadja az alakzatok alapértelmezett szövegstílusát. |
| [getCommentAuthors()](#getCommentAuthors--) | Visszaadja a megjegyzések szerzőinek gyűjteményét. |
| [getDocumentProperties()](#getDocumentProperties--) | Visszaad egy DocumentProperties objektumot, amely szabványos és egyedi dokumentumtulajdonságokat tartalmaz. |
| [getImages()](#getImages--) | Visszaadja a prezentációban lévő összes kép gyűjteményét. |
| [getAudios()](#getAudios--) | Visszaadja a prezentációban beágyazott összes hangfájl gyűjteményét. |
| [getVideos()](#getVideos--) | Visszaadja a prezentációban beágyazott összes videófájl gyűjteményét. |
| [getSlideShowSettings()](#getSlideShowSettings--) | Visszaadja a prezentáció diavetítés beállításait. |
| [getDigitalSignatures()](#getDigitalSignatures--) | Visszaadja a prezentáció aláírásához használt aláírások gyűjteményét. |
| [getCustomData()](#getCustomData--) | Visszaadja a prezentáció egyéni adatait. |
| [getAllCustomXmlParts()](#getAllCustomXmlParts--) | Visszaadja a prezentáció összes egyéni adat részét. |
| [getVbaProject()](#getVbaProject--) | Megkapja vagy beállítja a VBA projektet a prezentáció makróival. |
| [setVbaProject(IVbaProject value)](#setVbaProject-com.aspose.slides.IVbaProject-) | Megkapja vagy beállítja a VBA projektet a prezentáció makróival. |
| [getHyperlinkQueries()](#getHyperlinkQueries--) | Egyszerű hozzáférést biztosít az összes hiperhivatkozáshoz, amely a prezentáció diáin található (kivéve a mester-, elrendezés- és jegyzetdiákban). |
| [getViewProperties()](#getViewProperties--) | Megkapja a prezentációra kiterjedő nézet tulajdonságait. |
| [getFirstSlideNumber()](#getFirstSlideNumber--) | A prezentáció első dia számát reprezentálja. |
| [setFirstSlideNumber(int value)](#setFirstSlideNumber-int-) | A prezentáció első dia számát reprezentálja. |
| [getSensitivityLabels()](#getSensitivityLabels--) | Visszaadja a prezentációra alkalmazott érzékenységi címkék gyűjteményét. |
| [getSlideById(long id)](#getSlideById-long-) | Visszaad egy Slide, MasterSlide vagy LayoutSlide objektumot azonosító alapján. |
| [getSourceFormat()](#getSourceFormat--) | Visszaad információt arról, milyen formátumból lett betöltve a prezentáció. |
| [getMasterTheme()](#getMasterTheme--) | Visszaadja a mester témát. |
| [save(String fname, int format)](#save-java.lang.String-int-) | Elmenti a prezentáció összes diáját egy fájlba a megadott formátummal. |
| [save(OutputStream stream, int format)](#save-java.io.OutputStream-int-) | Elmenti a prezentáció összes diáját egy adatfolyamra a megadott formátummal. |
| [save(String fname, int format, ISaveOptions options)](#save-java.lang.String-int-com.aspose.slides.ISaveOptions-) | Elmenti a prezentáció összes diáját egy fájlba a megadott formátummal és további beállításokkal. |
| [save(OutputStream stream, int format, ISaveOptions options)](#save-java.io.OutputStream-int-com.aspose.slides.ISaveOptions-) | Elmenti a prezentáció összes diáját egy adatfolyamra a megadott formátummal és további beállításokkal. |
| [save(IXamlOptions options)](#save-com.aspose.slides.IXamlOptions-) | Elmenti a prezentáció összes diáját egy XAML jelölő nyelvet reprezentáló fájlkészletbe. |
| [getImages(IRenderingOptions options)](#getImages-com.aspose.slides.IRenderingOptions-) | Visszaad egy Image objektumot a prezentáció minden dia számára. |
| [getImages(IRenderingOptions options, int[] slides)](#getImages-com.aspose.slides.IRenderingOptions-int---) | Visszaad egy Bélyegkép Image objektumot a prezentáció megadott diáihoz. |
| [getImages(IRenderingOptions options, float scaleX, float scaleY)](#getImages-com.aspose.slides.IRenderingOptions-float-float-) | Visszaad egy Bélyegkép Image objektumot a prezentáció összes diájához egyedi méretezéssel. |
| [getImages(IRenderingOptions options, int[] slides, float scaleX, float scaleY)](#getImages-com.aspose.slides.IRenderingOptions-int---float-float-) | Visszaad egy Bélyegkép Image objektumot a megadott diákhoz egyedi méretezéssel. |
| [getImages(IRenderingOptions options, Dimension imageSize)](#getImages-com.aspose.slides.IRenderingOptions-java.awt.Dimension-) | Visszaad egy Bélyegkép Image objektumot a prezentáció összes diájához a megadott mérettel. |
| [getImages(IRenderingOptions options, int[] slides, Dimension imageSize)](#getImages-com.aspose.slides.IRenderingOptions-int---java.awt.Dimension-) | Visszaad egy Bélyegkép Image objektumot a megadott diákhoz a megadott mérettel. |
| [save(String fname, int[] slides, int format)](#save-java.lang.String-int---int-) | Elmenti a prezentáció megadott diáit egy fájlba a megadott formátummal, megtartva az oldalszámot. |
| [save(String fname, int[] slides, int format, ISaveOptions options)](#save-java.lang.String-int---int-com.aspose.slides.ISaveOptions-) | Elmenti a prezentáció megadott diáit egy fájlba a megadott formátummal, megtartva az oldalszámot. |
| [save(OutputStream stream, int[] slides, int format)](#save-java.io.OutputStream-int---int-) | Elmenti a prezentáció megadott diáit egy adatfolyamra a megadott formátummal, megtartva az oldalszámot. |
| [save(OutputStream stream, int[] slides, int format, ISaveOptions options)](#save-java.io.OutputStream-int---int-com.aspose.slides.ISaveOptions-) | Elmenti a prezentáció megadott diáit egy adatfolyamra a megadott formátummal, megtartva az oldalszámot. |
| [joinPortionsWithSameFormatting()](#joinPortionsWithSameFormatting--) | Összevonja az azonos formázású futásokat az összes bekezdésben az összes megfelelő alakzatban az összes dián. |
| [dispose()](#dispose--) | Felszabadítja a Presentation objektum által használt összes erőforrást. |
| [getPresentation()](#getPresentation--) | Visszaadja a szöveg szülő prezentációját. |
| [highlightText(String text, Color highlightColor)](#highlightText-java.lang.String-java.awt.Color-) | Kiemeli a minta szöveg összes egyezését a megadott színnel. |
| [highlightText(String text, Color highlightColor, ITextSearchOptions options, IFindResultCallback callback)](#highlightText-java.lang.String-java.awt.Color-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-) | Kiemeli a minta szöveg összes egyezését a megadott színnel. |
| [highlightRegex(Pattern regex, Color highlightColor, IFindResultCallback callback)](#highlightRegex-java.util.regex.Pattern-java.awt.Color-com.aspose.slides.IFindResultCallback-) | Kiemeli a reguláris kifejezés összes egyezését a megadott színnel. |
| [replaceText(String oldText, String newText, ITextSearchOptions options, IFindResultCallback callback)](#replaceText-java.lang.String-java.lang.String-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-) | Lecseréli a megadott szöveg összes előfordulását egy másik megadott szövegre. |
| [replaceRegex(Pattern regex, String newText, IFindResultCallback callback)](#replaceRegex-java.util.regex.Pattern-java.lang.String-com.aspose.slides.IFindResultCallback-) | Lecseréli a reguláris kifejezés összes egyezését a megadott karakterláncra. |
| [refreshChartsData()](#refreshChartsData--) | Újratölti a prezentáció minden diagramjának adatait a forrás munkafüzetekből. |
| [refreshChartsData(boolean skipFailedCharts)](#refreshChartsData-boolean-) | Újratölti a prezentáció minden diagramjának adatait a forrás munkafüzetekből. |

### Presentation() {#Presentation--}
```
public Presentation()
```

Ez a konstruktor új prezentációt hoz létre a semmiből. A létrehozott prezentáció egy üres diával rendelkezik.

### Presentation(LoadOptions loadOptions) {#Presentation-com.aspose.slides.LoadOptions-}
```
public Presentation(LoadOptions loadOptions)
```

Ez a konstruktor új prezentációt hoz létre a semmiből. A létrehozott prezentáció egy üres diával rendelkezik.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| loadOptions | [LoadOptions](../../com.aspose.slides/loadoptions) | További betöltési beállítások. |

### Presentation(InputStream stream) {#Presentation-java.io.InputStream-}
```
public Presentation(InputStream stream)
```

Ez a konstruktor az elsődleges módja egy meglévő Presentation beolvasásának.

--------------------

> ```
> FileInputStream fis = new FileInputStream("demo.pptx");
>  Presentation pres = new Presentation(fis);
>  fis.close();
> ```


**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| stream | java.io.InputStream | Bemeneti adatfolyam. |

### Presentation(InputStream stream, LoadOptions loadOptions) {#Presentation-java.io.InputStream-com.aspose.slides.LoadOptions-}
```
public Presentation(InputStream stream, LoadOptions loadOptions)
```

Ez a konstruktor az elsődleges módja egy meglévő Presentation beolvasásának.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| stream | java.io.InputStream | Bemeneti adatfolyam. |
| loadOptions | [LoadOptions](../../com.aspose.slides/loadoptions) | További betöltési beállítások. |

### Presentation(String file) {#Presentation-java.lang.String-}
```
public Presentation(String file)
```

Ez a konstruktor megkapja a forrásfájl útvonalát, ahonnan a Presentation tartalma beolvasásra kerül.

--------------------

> ```
> Presentation pres = new Presentation("demo.pptx");
> ```


**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| file | java.lang.String | Bemeneti fájl. |

### Presentation(String file, LoadOptions loadOptions) {#Presentation-java.lang.String-com.aspose.slides.LoadOptions-}
```
public Presentation(String file, LoadOptions loadOptions)
```

Ez a konstruktor megkapja a forrásfájl útvonalát, ahonnan a Presentation tartalma beolvasásra kerül.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| file | java.lang.String | Bemeneti fájl. |
| loadOptions | [LoadOptions](../../com.aspose.slides/loadoptions) | További betöltési beállítások. |

### getCurrentDateTime() {#getCurrentDateTime--}
```
public final Date getCurrentDateTime()
```

Visszaadja vagy beállítja a dátumot és időt, amely a datetime mezők tartalmát helyettesíti. Alapértelmezés szerint a Presentation objektum létrehozásának időpontja. **Olvasás/írás** java.util.Date.

**Visszatér:**
java.util.Date

### setCurrentDateTime(Date value) {#setCurrentDateTime-java.util.Date-}
```
public final void setCurrentDateTime(Date value)
```

Visszaadja vagy beállítja a dátumot és időt, amely a datetime mezők tartalmát helyettesíti. Alapértelmezés szerint a Presentation objektum létrehozásának időpontja. **Olvasás/írás** java.util.Date.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | java.util.Date |  |

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Visszaadja a Parent_Immediate objektumot. **Csak olvasható** IDOMObject.

**Visszatér:**
com.aspose.slides.IDOMObject

### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public final IPresentationHeaderFooterManager getHeaderFooterManager()
```

Visszaadja a tényleges HeaderFooter kezelőt. **Csak olvasható** [IPresentationHeaderFooterManager](../../com.aspose.slides/ipresentationheaderfootermanager).

--------------------

> ```
> The following example shows how to set footer visibility inside Slide of PowerPoint Presentation.
>  
>  Presentation pres = new Presentation("presentation.ppt");
>  try
>  {
>      IBaseSlideHeaderFooterManager headerFooterManager = pres.getSlides().get_Item(0).getHeaderFooterManager();
>      if (!headerFooterManager.isFooterVisible()) // Az IsFooterVisible tulajdonság azt jelzi, hogy a dia lábléc helyfoglalója nincs jelen.
>      {
>          headerFooterManager.setFooterVisibility(true); // A SetFooterVisibility metódus azt teszi lehetővé, hogy a dia lábléc helyfoglalója látható legyen.
>      }
>      if (!headerFooterManager.isSlideNumberVisible()) // Az IsSlideNumberVisible tulajdonság azt jelzi, hogy a dia oldalszám helyfoglalója nincs jelen.
>      {
>          headerFooterManager.setSlideNumberVisibility(true); // A SetSlideNumberVisibility metódus azt teszi lehetővé, hogy a dia oldalszám helyfoglalója látható legyen.
>      }
>      if (!headerFooterManager.isDateTimeVisible()) // Az IsDateTimeVisible tulajdonság azt jelzi, hogy a dia dátum-idő helyfoglalója nincs jelen.
>      {
>          headerFooterManager.setDateTimeVisibility(true); // A SetFooterVisibility metódus azt teszi lehetővé, hogy a dia dátum-idő helyfoglalója látható legyen.
>      }
>      headerFooterManager.setFooterText("Footer text"); // A SetFooterText metódus a dia lábléc helyfoglalójához szöveget állít be.
>      headerFooterManager.setDateTimeText("Date and time text"); // A SetDateTimeText metódus a dia dátum-idő helyfoglalójához szöveget állít be.
>      pres.save("Presentation.ppt", SaveFormat.Ppt);
>  }
>  finally
>  {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to set child footer visibility inside Slide.
>  
>  Presentation pres = new Presentation("presentation.ppt");
>  try
>  {
>      IMasterSlideHeaderFooterManager headerFooterManager = pres.getMasters().get_Item(0).getHeaderFooterManager();
>      headerFooterManager.setFooterAndChildFootersVisibility(true); // A SetFooterAndChildFootersVisibility metódus azt teszi lehetővé, hogy a mester dia és az összes gyermek lábléc helyfoglaló látható legyen.
>      headerFooterManager.setSlideNumberAndChildSlideNumbersVisibility(true); // A SetSlideNumberAndChildSlideNumbersVisibility metódus azt teszi lehetővé, hogy a mester dia és az összes gyermek oldalszám helyfoglaló látható legyen.
>      headerFooterManager.setDateTimeAndChildDateTimesVisibility(true); // A SetDateTimeAndChildDateTimesVisibility metódus azt teszi lehetővé, hogy a mester dia és az összes gyermek dátum-idő helyfoglaló látható legyen.
> 
>      headerFooterManager.setFooterAndChildFootersText("Footer text"); // A SetFooterAndChildFootersText metódus a mester diára és az összes gyermek lábléc helyfoglalóra szöveget állít be.
>      headerFooterManager.setDateTimeAndChildDateTimesText("Date and time text"); // A SetDateTimeAndChildDateTimesText metódus a mester diára és az összes gyermek dátum-idő helyfoglalóra szöveget állít be.
>  }
>  finally
>  {
>      if (pres != null) pres.dispose();
>  }
> ```


**Visszatér:**
[IPresentationHeaderFooterManager](../../com.aspose.slides/ipresentationheaderfootermanager)
### getProtectionManager() {#getProtectionManager--}
```
public final IProtectionManager getProtectionManager()
```

Megkapja a prezentáció jogosultságkezelőjét. **Csak olvasható** [IProtectionManager](../../com.aspose.slides/iprotectionmanager).

**Visszatér:**
[IProtectionManager](../../com.aspose.slides/iprotectionmanager)
### getSlides() {#getSlides--}
```
public final ISlideCollection getSlides()
```

Visszaad egy listát a prezentációban definiált összes diáról. **Csak olvasható** [ISlideCollection](../../com.aspose.slides/islidecollection).

--------------------

> ```
> The following example shows how to set slides' background color of PowerPoint Presentation.
>  
>  // Példányosítja a Presentation osztályt, amely a prezentációfájlt képviseli
>  Presentation pres = new Presentation();
>  try
>  {
>      // Beállítja az első ISlide háttérszínét kékre
>      pres.getSlides().get_Item(0).getBackground().setType(BackgroundType.OwnBackground);
>      pres.getSlides().get_Item(0).getBackground().getFillFormat().setFillType(FillType.Solid);
>      pres.getSlides().get_Item(0).getBackground().getFillFormat().getSolidFillColor().setColor(Color.BLUE);
>      pres.save("ContentBG_out.pptx", SaveFormat.Pptx);
>  }
>  finally
>  {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to set slides' background image of PowerPoint Presentation.
>  
>  // Példányosítja a Presentation osztályt, amely a prezentációfájlt képviseli
>  Presentation pres = new Presentation("SetImageAsBackground.pptx");
>  try {
>      // Beállítja a hátteret képpel
>      pres.getSlides().get_Item(0).getBackground().setType(BackgroundType.OwnBackground);
>      pres.getSlides().get_Item(0).getBackground().getFillFormat().setFillType(FillType.Picture);
>      pres.getSlides().get_Item(0).getBackground().getFillFormat().getPictureFillFormat().setPictureFillMode(PictureFillMode.Stretch);
>      // Beállítja a képet
>      BufferedImage img = ImageIO.read(new File("Tulips.jpg"));
>      // Képet ad a prezentáció képgyűjteményéhez
>      IPPImage imgx = pres.getImages().addImage(img);
>      pres.getSlides().get_Item(0).getBackground().getFillFormat().getPictureFillFormat().getPicture().setImage(imgx);
>      // A prezentációt lemezre írja
>      pres.save("ContentBG_Img_out.pptx", SaveFormat.Pptx);
>  } catch (IOException e) { }
>  finally
>  {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to add slide transition Presentation.
>  
>  // Példányosítja a Presentation osztályt a forrás prezentációfájl betöltéséhez
>  Presentation pres = new Presentation("AccessSlides.pptx");
>  try
>  {
>      // Kör típusú áttűnést alkalmaz az 1. dián
>      pres.getSlides().get_Item(0).getSlideShowTransition().setType(TransitionType.Circle);
>      // Comb típusú áttűnést alkalmaz a 2. dián
>      pres.getSlides().get_Item(1).getSlideShowTransition().setType(TransitionType.Comb);
>      // A prezentációt lemezre írja
>      pres.save("SampleTransition_out.pptx", SaveFormat.Pptx);
>  }
>  finally
>  {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to add advanced slide Transition.
>  
>  // Példányosítja a Presentation osztályt, amely egy prezentációfájlt képvisel
>  Presentation pres = new Presentation("BetterSlideTransitions.pptx");
>  try
>  {
>      // Kör típusú áttűnést alkalmaz az 1. dián
>      pres.getSlides().get_Item(0).getSlideShowTransition().setType(TransitionType.Circle);
>      // Beállítja a 3 másodperces áttűnési időt
>      pres.getSlides().get_Item(0).getSlideShowTransition().setAdvanceOnClick(true);
>      pres.getSlides().get_Item(0).getSlideShowTransition().setAdvanceAfterTime(3000);
>      // Comb típusú áttűnést alkalmaz a 2. dián
>      pres.getSlides().get_Item(1).getSlideShowTransition().setType(TransitionType.Comb);
>      // Beállítja az 5 másodperces áttűnési időt
>      pres.getSlides().get_Item(1).getSlideShowTransition().setAdvanceOnClick(true);
>      pres.getSlides().get_Item(1).getSlideShowTransition().setAdvanceAfterTime(5000);
>      // Zoom típusú áttűnést alkalmaz a 3. dián
>      pres.getSlides().get_Item(2).getSlideShowTransition().setType(TransitionType.Zoom);
>      // Beállítja a 7 másodperces áttűnési időt
>      pres.getSlides().get_Item(2).getSlideShowTransition().setAdvanceOnClick(true);
>      pres.getSlides().get_Item(2).getSlideShowTransition().setAdvanceAfterTime(7000);
>      // A prezentációt lemezre írja
>      pres.save("SampleTransition_out.pptx", SaveFormat.Pptx);
>  }
>  finally
>  {
>      if (pres != null) pres.dispose();
>  }
> ```


**Visszatér:**
[ISlideCollection](../../com.aspose.slides/islidecollection)
### getSections() {#getSections--}
```
public final ISectionCollection getSections()
```

Visszaad egy listát a prezentációban definiált összes diaszekcióról. **Csak olvasható** [ISectionCollection](../../com.aspose.slides/isectioncollection).

--------------------

> ```
> The following examples shows how to create Sections in a PowerPoint Presentation.
>  
>  Presentation pres = new Presentation();
>  try {
>      ISlide defaultSlide = pres.getSlides().get_Item(0);
>      ISlide newSlide1 = pres.getSlides().addEmptySlide(pres.getLayoutSlides().get_Item(0));
>      ISlide newSlide2 = pres.getSlides().addEmptySlide(pres.getLayoutSlides().get_Item(0));
>      ISlide newSlide3 = pres.getSlides().addEmptySlide(pres.getLayoutSlides().get_Item(0));
>      ISlide newSlide4 = pres.getSlides().addEmptySlide(pres.getLayoutSlides().get_Item(0));
>      ISection section1 = pres.getSections().addSection("Section 1", newSlide1);
>      // a section1 a newSlide2-nél lesz befejezve, és utána a section2 kezdődik
>      ISection section2 = pres.getSections().addSection("Section 2", newSlide3);
>      pres.save("pres-sections.pptx", SaveFormat.Pptx);
>      pres.getSections().reorderSectionWithSlides(section2, 0);
>      pres.save("pres-sections-moved.pptx", SaveFormat.Pptx);
>      pres.getSections().removeSectionWithSlides(section2);
>      pres.getSections().appendEmptySection("Last empty section");
>      pres.save("pres-section-with-empty.pptx",SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following examples shows how to changing the names of Sections.
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      ISection section = pres.getSections().get_Item(0);
>      section.setName("My section");
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Visszatér:**
[ISectionCollection](../../com.aspose.slides/isectioncollection)
### getSlideSize() {#getSlideSize--}
```
public final ISlideSize getSlideSize()
```

Visszaad egy diaméret objektumot. **Csak olvasható** [ISlideSize](../../com.aspose.slides/islidesize).

--------------------

> ```
> The following example shows how to change the slide size in a PowerPoint Presentation.
>  
>  Presentation pres = new Presentation("pres-4x3-aspect-ratio.pptx");
>  try {
>      pres.getSlideSize().setSize(SlideSizeType.OnScreen16x9, SlideSizeScaleType.DoNotScale);
>      pres.save("pres-4x3-aspect-ratio.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to set slide size with respect to content scaling for a PowerPoint Presentation.
>  
>  // Példányosít egy Presentation objektumot, amely egy prezentációfájlt képvisel
>  Presentation presentation = new Presentation("AccessSlides.pptx");
>  try {
>      Presentation auxPresentation = new Presentation();
>      try {
>          ISlide slide = presentation.getSlides().get_Item(0);
>          // Beállítja a generált prezentációk diaméretét a forráséhoz
>          presentation.getSlideSize().setSize(540, 720, SlideSizeScaleType.EnsureFit); // Az SetSize metódus a diaméret beállításához használható, a tartalmat méretezve, hogy biztosan illeszkedjen
>          presentation.getSlideSize().setSize(SlideSizeType.A4Paper, SlideSizeScaleType.Maximize); // Az SetSize metódus a diaméret beállításához használható, a tartalom maximális méretére
>          // A prezentációt lemezre menti
>          auxPresentation.save("Set_Size&Type_out.pptx", SaveFormat.Pptx);
>      } finally {
>          if (auxPresentation != null) auxPresentation.dispose();
>      }
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
>  
>  The following example shows how to specifying custom slide sizes in a PowerPoint Presentation.
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      pres.getSlideSize().setSize(780, 540, SlideSizeScaleType.DoNotScale); // A4 papír méret
>      pres.save("pres-a4-slide-size.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Visszatér:**
[ISlideSize](../../com.aspose.slides/islidesize)
### getNotesSize() {#getNotesSize--}
```
public final INotesSize getNotesSize()
```

Visszaad egy jegyzetdia méret objektumot. **Csak olvasható** [INotesSize](../../com.aspose.slides/inotessize).

**Visszatér:**
[INotesSize](../../com.aspose.slides/inotessize)
### getLayoutSlides() {#getLayoutSlides--}
```
public final IGlobalLayoutSlideCollection getLayoutSlides()
```

Visszaad egy listát a prezentációban definiált összes elrendezési diáról. **Csak olvasható** [IGlobalLayoutSlideCollection](../../com.aspose.slides/igloballayoutslidecollection).

--------------------

Alternatív API-hoz az elrendezési diák hozzáadásához/beszúrásához/eltávolításához/klónozásához használja az IMasterSlide.LayoutSlides tulajdonságot.

**Visszatér:**
[IGlobalLayoutSlideCollection](../../com.aspose.slides/igloballayoutslidecollection)
### getMasters() {#getMasters--}
```
public final IMasterSlideCollection getMasters()
```

Visszaad egy listát a prezentációban definiált összes mester diáról. **Csak olvasható** [IMasterSlideCollection](../../com.aspose.slides/imasterslidecollection).

--------------------

> ```
> The following examples shows how to adding Images to Master Slides of PowerPoint Presentation.
>  
>  Presentation pres = new Presentation();
>  try {
>      ISlide slide = pres.getSlides().get_Item(0);
>      IMasterSlide masterSlide = slide.getLayoutSlide().getMasterSlide();
>      IPPImage image = pres.getImages().addImage(Files.readAllBytes(Paths.get("image.png")));
>      masterSlide.getShapes().addPictureFrame(ShapeType.Rectangle, 10, 10, 100, 100, image);
>      pres.save("pres.pptx", SaveFormat.Pptx);
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following examples shows how to change the background color of the master slide of PowerPoint Presentation.
>  
>  // Példányosítja a Presentation osztályt, amely a prezentációfájlt képviseli
>  Presentation pres = new Presentation();
>  try
>  {
>      // Beállítja a Master ISlide háttérszínét Forest Green-re
>      pres.getMasters().get_Item(0).getBackground().setType(BackgroundType.OwnBackground);
>      pres.getMasters().get_Item(0).getBackground().getFillFormat().setFillType(FillType.Solid);
>      pres.getMasters().get_Item(0).getBackground().getFillFormat().getSolidFillColor().setColor(Color.GREEN);
>      // A prezentációt lemezre írja
>      pres.save("SetSlideBackgroundMaster_out.pptx", SaveFormat.Pptx);
>  }
>  finally
>  {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following examples shows how to add slide layout to PowerPoint Presentation.
>  
>  // Példányosítja a Presentation osztályt, amely a prezentációfájlt képviseli
>  Presentation presentation = new Presentation("AccessSlides.pptx");
>  try
>  {
>      // Kísérlet a layout dia típus szerinti keresésre
>      IMasterLayoutSlideCollection layoutSlides = presentation.getMasters().get_Item(0).getLayoutSlides();
>      ILayoutSlide layoutSlide = null;
>      if (layoutSlides.getByType(SlideLayoutType.TitleAndObject) != null)
>          layoutSlide = layoutSlides.getByType(SlideLayoutType.TitleAndObject);
>      else
>          layoutSlide = layoutSlides.getByType(SlideLayoutType.Title);
> 
>      if (layoutSlide == null)
>      {
>          // Az a helyzet, amikor egy prezentáció nem tartalmaz bizonyos típusú elrendezéseket.
>          // A prezentációfájl csak Üres és Egyedi elrendezéstípusokat tartalmaz.
>          // Azonban az Egyedi típusú elrendezési diák különböző dia nevekkel rendelkeznek,
>          // például "Title", "Title and Content", stb. És ezek használata lehetséges
>          // neveket a layout diák kiválasztásához.
>          // Emellett lehetséges a helyfoglaló alakzat típusok halmazának használata. Például,
>          // A cím dia csak Title helyfoglaló típussal rendelkezhet, stb.
>          for (ILayoutSlide titleAndObjectLayoutSlide : (Iterable) layoutSlides)
>          {
>              if ("Title and Object".equals(titleAndObjectLayoutSlide.getName()))
>              {
>                  layoutSlide = titleAndObjectLayoutSlide;
>                  break;
>              }
>          }
>          if (layoutSlide == null)
>          {
>              for (ILayoutSlide titleLayoutSlide : (Iterable) layoutSlides)
>              {
>                  if ("Title".equals(titleLayoutSlide.getName()))
>                  {
>                      layoutSlide = titleLayoutSlide;
>                      break;
>                  }
>              }
>              if (layoutSlide == null)
>              {
>                  layoutSlide = layoutSlides.getByType(SlideLayoutType.Blank);
>                  if (layoutSlide == null)
>                  {
>                      layoutSlide = layoutSlides.add(SlideLayoutType.TitleAndObject, "Title and Object");
>                  }
>              }
>          }
>      }
>      // Üres dia hozzáadása a hozzáadott layout diával
>      presentation.getSlides().insertEmptySlide(0, layoutSlide);
>      // A prezentáció mentése
>      presentation.save("AddLayoutSlides_out.pptx", SaveFormat.Pptx);
>  }
>  finally
>  {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Visszatér:**
[IMasterSlideCollection](../../com.aspose.slides/imasterslidecollection)
### getMasterNotesSlideManager() {#getMasterNotesSlideManager--}
```
public final IMasterNotesSlideManager getMasterNotesSlideManager()
```

Visszaadja a jegyzetmester kezelőt. **Csak olvasható** [IMasterNotesSlideManager](../../com.aspose.slides/imasternotesslidemanager).

**Visszatér:**
[IMasterNotesSlideManager](../../com.aspose.slides/imasternotesslidemanager)
### getMasterHandoutSlideManager() {#getMasterHandoutSlideManager--}
```
public final IMasterHandoutSlideManager getMasterHandoutSlideManager()
```

Visszaadja a kiadványmester kezelőt. **Csak olvasható** [IMasterHandoutSlideManager](../../com.aspose.slides/imasterhandoutslidemanager).

**Visszatér:**
[IMasterHandoutSlideManager](../../com.aspose.slides/imasterhandoutslidemanager)
### getFontsManager() {#getFontsManager--}
```
public final IFontsManager getFontsManager()
```

Visszaadja a betűtípus kezelőt. **Csak olvasható** [IFontsManager](../../com.aspose.slides/ifontsmanager).

--------------------

> ```
> The following example shows how to add embedded fonts to PowerPoint Presentation.
>  
>  // Betölti a prezentációt
>  Presentation pres = new Presentation("Fonts.pptx");
>  try {
>      // Betölti a forrásbetűtípust, amelyet cserélni kell
>      IFontData sourceFont = new FontData("Arial");
>      IFontData[] allFonts = pres.getFontsManager().getFonts();
>      for (IFontData font : allFonts)
>      {
>          boolean fontAlreadyEmbedded = false;
>          IFontData[] embeddedFonts = pres.getFontsManager().getEmbeddedFonts();
>          for (int i = 0; i < embeddedFonts.length; i++)
>          {
>              if (embeddedFonts[i].equals(font))
>              {
>                  fontAlreadyEmbedded = true;
>                  break;
>              }
>          }
>          if (!fontAlreadyEmbedded) {
>              pres.getFontsManager().addEmbeddedFont(font, EmbedFontCharacters.All);
>          }
>      }
>      // Mentse a prezentációt
>      pres.save("AddEmbeddedFont_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Visszatér:**
[IFontsManager](../../com.aspose.slides/ifontsmanager)
### getDefaultTextStyle() {#getDefaultTextStyle--}
```
public final ITextStyle getDefaultTextStyle()
```

Visszaadja az alakzatok alapértelmezett szövegstílusát. **Csak olvasható** [ITextStyle](../../com.aspose.slides/itextstyle).

**Visszatér:**
[ITextStyle](../../com.aspose.slides/itextstyle)
### getCommentAuthors() {#getCommentAuthors--}
```
public final ICommentAuthorCollection getCommentAuthors()
```

Visszaadja a megjegyzések szerzőinek gyűjteményét. **Csak olvasható** [ICommentAuthorCollection](../../com.aspose.slides/icommentauthorcollection).

**Visszatér:**
[ICommentAuthorCollection](../../com.aspose.slides/icommentauthorcollection)
### getDocumentProperties() {#getDocumentProperties--}
```
public final IDocumentProperties getDocumentProperties()
```

Visszaad egy DocumentProperties objektumot, amely szabványos és egyedi dokumentumtulajdonságokat tartalmaz. **Csak olvasható** [IDocumentProperties](../../com.aspose.slides/idocumentproperties).

**Visszatér:**
[IDocumentProperties](../../com.aspose.slides/idocumentproperties)
### getImages() {#getImages--}
```
public final IImageCollection getImages()
```

Visszaadja a prezentációban lévő összes kép gyűjteményét. **Csak olvasható** [IImageCollection](../../com.aspose.slides/iimagecollection).

--------------------

> ```
> The following examples shows how to add image as BLOB in PowerPoint Presentation.
>  
>  // létrehoz egy új prezentációt, amelyhez a képet hozzáadjuk.
>  Presentation pres = new Presentation();
>  try
>  {
>      // feltételezzük, hogy van egy nagy képfájl, amelyet be szeretnénk illeszteni a prezentációba
>      FileInputStream fip = new FileInputStream("large_image.jpg");
>      try
>      {
>          // Adjunk hozzá képet a prezentációhoz - a KeepLocked viselkedést választjuk, mert nem akarunk
>          // hozzáférni a "largeImage.png" fájlhoz.
>          IPPImage img = pres.getImages().addImage(fip, LoadingStreamBehavior.KeepLocked);
>          pres.getSlides().get_Item(0).getShapes().addPictureFrame(ShapeType.Rectangle, 0, 0, 300, 200, img);
>          // Mentés a prezentáció. Amíg egy nagy prezentáció kerül kimenetre, a memóriahasználat
>          // alacsony marad a pres objektum életciklusa alatt.
>          pres.save("presentationWithLargeImage.pptx", SaveFormat.Pptx);
>      }
>      finally
>      {
>          fip.close();
>      }
>  }
>  catch (java.io.IOException e) { }
>  finally
>  {
>      pres.dispose();
>  }
>  
>  The following examples add a hyperlink to an image in a PowerPoint Presentation.
>  
>  Presentation pres = new Presentation();
>  try {
>      // Hozzáadja a képet a prezentációhoz
>      IPPImage image = pres.getImages().addImage(Files.readAllBytes(Paths.get("image.png")));
>      // Létrehozza a képkeretet az 1. dián az előzőleg hozzáadott kép alapján
>      IPictureFrame pictureFrame = pres.getSlides().get_Item(0).getShapes().addPictureFrame(ShapeType.Rectangle, 10, 10, 100, 100, image);
>      pictureFrame.setHyperlinkClick(new Hyperlink("https://www.aspose.com/"));
>      pictureFrame.getHyperlinkClick().setTooltip("More than 70% Fortune 100 companies trust Aspose APIs");
>      pres.save("pres-out.pptx", SaveFormat.Pptx);
>  } catch (IOException e){ }
>  finally
>  {
>      if (pres != null) pres.dispose();
>  }
> ```


**Visszatér:**
[IImageCollection](../../com.aspose.slides/iimagecollection)
### getAudios() {#getAudios--}
```
public final IAudioCollection getAudios()
```
Visszaadja a bemutatóban beágyazott összes hangfájl gyűjteményét. Csak olvasható [IAudioCollection](../../com.aspose.slides/iaudiocollection).

--------------------

> ```
> The following examples shows how to add a hyperlink to an audio file.
>  
>  Presentation pres = new Presentation();
>  try {
>      IAudio audio = pres.getAudios().addAudio(Files.readAllBytes(Paths.get("audio.mp3")));
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(10, 10, 100, 100, audio);
>      audioFrame.setHyperlinkClick(new Hyperlink("https://www.aspose.com/"));
>      audioFrame.getHyperlinkClick().setTooltip("More than 70% Fortune 100 companies trust Aspose APIs");
>      pres.save("pres-out.pptx", SaveFormat.Pptx);
>  }
>  catch (IOException e) {}
>  finally
>  {
>      if (pres != null) pres.dispose();
>  }
> ```

**Visszatér:**
[IAudioCollection](../../com.aspose.slides/iaudiocollection)
### getVideos() {#getVideos--}
```
public final IVideoCollection getVideos()
```


Visszaadja a bemutatóban beágyazott összes videofájl gyűjteményét. Csak olvasható [IVideoCollection](../../com.aspose.slides/ivideocollection).

--------------------

> ```
> The following examples shows how to create embedded Video Frame in a PowerPoint Presentation.
>  
>  // Instantiate Presentation class that represents the PPTX
>  Presentation pres = new Presentation();
>  try {
>      // Get the first slide
>      ISlide sld = pres.getSlides().get_Item(0);
>      // Embedd vide inside presentation
>      IVideo vid = pres.getVideos().addVideo(new FileInputStream("Wildlife.mp4"));
>      // Add Video Frame
>      IVideoFrame vf = sld.getShapes().addVideoFrame(50, 150, 300, 350, vid);
>      // Set video to Video Frame
>      vf.setEmbeddedVideo(vid);
>      // Set Play Mode and Volume of the Video
>      vf.setPlayMode(VideoPlayModePreset.Auto);
>      vf.setVolume(AudioVolumeMode.Loud);
>      // Write the PPTX file to disk
>      pres.save("VideoFrame_out.pptx", SaveFormat.Pptx);
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following examples shows how to add a video passing path to the video file directly into AddVideoFrame method for PowerPoint Presentation.
>  
>  Presentation pres = new Presentation();
>  try {
>      ISlide sld = pres.getSlides().get_Item(0);
>      IVideoFrame vf = sld.getShapes().addVideoFrame(50, 150, 300, 150, "video1.avi");
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following examples shows how to add large file through BLOB to a Presentation.
>  
>  // Creates a new presentation to which the video will be added
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream fileStream = new FileInputStream("veryLargeVideo.avi");
>      try {
>          // Let's add the video to the presentation - we chose the KeepLocked behavior because we do
>          //not intend to access the "veryLargeVideo.avi" file.
>          IVideo video = pres.getVideos().addVideo(fileStream, LoadingStreamBehavior.KeepLocked);
>          pres.getSlides().get_Item(0).getShapes().addVideoFrame(0, 0, 480, 270, video);
>          // Saves the presentation. While a large presentation gets outputted, the memory consumption
>          // stays low through the pres object's lifecycle
>          pres.save("presentationWithLargeVideo.pptx", SaveFormat.Pptx);
>      } finally {
>          if (fileStream != null) fileStream.close();
>      }
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following examples shows how to export large file through BLOB from PowerPoint Presentation.
>  
>  LoadOptions loadOptions = new LoadOptions();
>  // Locks the source file and does NOT load it into memory
>  loadOptions.getBlobManagementOptions().setPresentationLockingBehavior(PresentationLockingBehavior.KeepLocked);
>  // Creates a Presentation's instance, locks the "hugePresentationWithAudiosAndVideos.pptx" file.
>  Presentation pres = new Presentation("Large  Video File Test1.pptx", loadOptions);
>  try {
>      // Let's save each video to a file. To prevent high memory usage, we need a buffer that will be used
>      // to transfer the data from the presentation's video stream to a stream for a newly created video file.
>      byte[] buffer = new byte[81024];
>      // Iterates through the videos
>      for (int index = 0; index < pres.getVideos().size(); index++) {
>          IVideo video = pres.getVideos().get_Item(index);
>          // Opens the presentation video stream. Please, note that we intentionally avoided accessing properties
>          // like video.BinaryData - because this property returns a byte array containing a full video, which then
>          // causes bytes to be loaded into memory. We use video.GetStream, which will return Stream - and does NOT
>          //  require us to load the whole video into the memory.
>          InputStream presVideoStream = video.getStream();
>          try {
>              FileOutputStream outputFileStream = new FileOutputStream("video{index}.avi");
>              try {
>                  int bytesRead;
>                  while ((bytesRead = presVideoStream.read(buffer, 0, buffer.length)) > 0) {
>                      outputFileStream.write(buffer, 0, bytesRead);
>                  }
>              } finally {
>                  if (outputFileStream != null) outputFileStream.close();
>              }
>          } finally {
>              if (presVideoStream != null) presVideoStream.close();
>          }
>          // Memory consumption will remain low regardless of the size of the video or presentation,
>      }
>      // If necessary, you can apply the same steps for audio files.
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following examples shows how to add a hyperlink to a video in a PowerPoint Presentation.
>  
>  Presentation pres = new Presentation();
>  try {
>      IVideo video = pres.getVideos().addVideo(Files.readAllBytes(Paths.get("video.avi")));
>      IVideoFrame videoFrame = pres.getSlides().get_Item(0).getShapes().addVideoFrame(10, 10, 100, 100, video);
>      videoFrame.setHyperlinkClick(new Hyperlink("https://www.aspose.com/"));
>      videoFrame.getHyperlinkClick().setTooltip("More than 70% Fortune 100 companies trust Aspose APIs");
>      pres.save("pres-out.pptx", SaveFormat.Pptx);
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following examples shows how to create Video Frame with Video from Web Source in a PowerPoint Presentation.
>  
>  public static void run()
>  {
>      Presentation pres = new Presentation();
>      try {
>          addVideoFromYouTube(pres, "Tj75Arhq5ho");
>          pres.save("AddVideoFrameFromWebSource_out.pptx", SaveFormat.Pptx);
>      } catch(IOException e) {
>      } finally {
>          if (pres != null) pres.dispose();
>      }
>  }
>  private static void addVideoFromYouTube(Presentation pres, String videoId) throws IOException
>  {
>      //add videoFrame
>      IVideoFrame videoFrame = pres.getSlides().get_Item(0).getShapes().addVideoFrame(10, 10, 427, 240, "https://www.youtube.com/embed/" + videoId);
>      videoFrame.setPlayMode(VideoPlayModePreset.Auto);
> 
>      //load thumbnail
>      String thumbnailUri = "http://img.youtube.com/vi/" + videoId + "/hqdefault.jpg";
>      URL url = new URL(thumbnailUri);
>      URLConnection connection = url.openConnection();
>      connection.setConnectTimeout(5000);
>      connection.setReadTimeout(10000);
>      InputStream input = connection.getInputStream();
>      ByteArrayOutputStream output = new ByteArrayOutputStream();
>      try
>      {
>          byte[] buffer = new byte[8192];
>          for (int count; (count = input.read(buffer)) > 0; )
>          {
>              output.write(buffer, 0, count);
>          }
>          videoFrame.getPictureFormat().getPicture().setImage(pres.getImages().addImage(output.toByteArray()));
>      } finally {
>          if (input != null) input.close();
>          if (output != null) output.close();
>      }
>  }
>  
>  The following examples shows how to extract Video from slide of PowerPoint Presentation.
>  
>  // Instantiate a Presentation object that represents a presentation file
>  Presentation presentation = new Presentation("Video.pptx");
>  try {
>      for (ISlide slide : presentation.getSlides())
>      {
>          for (IShape shape : presentation.getSlides().get_Item(0).getShapes())
>          {
>              if (shape instanceof VideoFrame)
>              {
>                  IVideoFrame vf = (IVideoFrame) shape;
>                  String type = vf.getEmbeddedVideo().getContentType();
>                  int ss = type.lastIndexOf('/');
>                  type = type.substring(ss + 1);
>                  byte[] buffer = vf.getEmbeddedVideo().getBinaryData();
>                  FileOutputStream fop = new FileOutputStream("NewVideo_out." + type);
>                  try
>                  {
>                      fop.write(buffer);
>                      fop.flush();
>                      fop.close();
>                  }
>                  finally
>                  {
>                      if (presentation != null) presentation.dispose();
>                  }
>              }
>          }
>      }
>  } catch(IOException e) {
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Visszatér:**
[IVideoCollection](../../com.aspose.slides/ivideocollection)
### getSlideShowSettings() {#getSlideShowSettings--}
```
public final SlideShowSettings getSlideShowSettings()
```


Visszaadja a bemutató diavetítésének beállításait.

**Visszatér:**
[SlideShowSettings](../../com.aspose.slides/slideshowsettings)
### getDigitalSignatures() {#getDigitalSignatures--}
```
public final IDigitalSignatureCollection getDigitalSignatures()
```


Visszaadja a bemutató aláírásához használt aláírások gyűjteményét. Csak olvasható [IDigitalSignatureCollection](../../com.aspose.slides/idigitalsignaturecollection).

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
>                   + signature.getSignTime().toString() + " -- " + (signature.isValid() ? "VALID" : "INVALID"));
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
### getCustomData() {#getCustomData--}
```
public final ICustomData getCustomData()
```


Visszaadja a bemutató egyedi adatait. Csak olvasható [ICustomData](../../com.aspose.slides/icustomdata).

**Visszatér:**
[ICustomData](../../com.aspose.slides/icustomdata)
### getAllCustomXmlParts() {#getAllCustomXmlParts--}
```
public final ICustomXmlPart[] getAllCustomXmlParts()
```


Visszaadja a bemutató összes egyedi adat részét. Csak olvasható ICustomXmlPart[].

--------------------

> ```
> The following examples show how to clear all custom xml parts from PowerPoint Presentation.
>  
>  Presentation pres = new Presentation("PresentationWithCustomXml.pptx");
>  try {
>      // Iterálja az összes egyedi XML részt
>      for (ICustomXmlPart item : pres.getAllCustomXmlParts())
>      {
>          item.remove();
>      }
>      pres.save("out.pptx", SaveFormat.Pptx);
>  }
>  finally
>  {
>      if (pres != null) pres.dispose();
>  }
> ```


**Visszatér:**
com.aspose.slides.ICustomXmlPart[]
### getVbaProject() {#getVbaProject--}
```
public final IVbaProject getVbaProject()
```


Lekéri vagy beállítja a VBA projektet a bemutató makróival. Olvasás/írás [IVbaProject](../../com.aspose.slides/ivbaproject).

**Visszatér:**
[IVbaProject](../../com.aspose.slides/ivbaproject)
### setVbaProject(IVbaProject value) {#setVbaProject-com.aspose.slides.IVbaProject-}
```
public final void setVbaProject(IVbaProject value)
```


Lekéri vagy beállítja a VBA projektet a bemutató makróival. Olvasás/írás [IVbaProject](../../com.aspose.slides/ivbaproject).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | [IVbaProject](../../com.aspose.slides/ivbaproject) |  |

### getHyperlinkQueries() {#getHyperlinkQueries--}
```
public final IHyperlinkQueries getHyperlinkQueries()
```


Egyszerű hozzáférést biztosít az összes hiperhivatkozáshoz, amely az összes bemutatódián szerepel (kivéve a master, layout, notes diákon). Csak olvasható [IHyperlinkQueries](../../com.aspose.slides/ihyperlinkqueries).

**Visszatér:**
[IHyperlinkQueries](../../com.aspose.slides/ihyperlinkqueries)
### getViewProperties() {#getViewProperties--}
```
public final IViewProperties getViewProperties()
```


Lekéri a bemutató általános nézetbeállításait. Csak olvasható [IViewProperties](../../com.aspose.slides/iviewproperties).

**Visszatér:**
[IViewProperties](../../com.aspose.slides/iviewproperties)
### getFirstSlideNumber() {#getFirstSlideNumber--}
```
public final int getFirstSlideNumber()
```


A bemutató első dia számát jelöli

**Visszatér:**
int
### setFirstSlideNumber(int value) {#setFirstSlideNumber-int-}
```
public final void setFirstSlideNumber(int value)
```


A bemutató első dia számát jelöli

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |

### getSensitivityLabels() {#getSensitivityLabels--}
```
public final ISensitivityLabelCollection getSensitivityLabels()
```


Visszaadja a bemutató dokumentumára alkalmazott érzékenységi címkék gyűjteményét. Csak olvasható [ISensitivityLabelCollection](../../com.aspose.slides/isensitivitylabelcollection).

--------------------

> ```
> Presentation pres = new Presentation("SomePresentation.pptx");
>  try {
>      ISensitivityLabelCollection sensitivityLabels = pres.getSensitivityLabels();
> 
>      // Kiírja a alkalmazott címkéket
>      for (ISensitivityLabel sensitivityLabel : sensitivityLabels)
>          System.out.println("Label Id " + sensitivityLabel.getId() + " from Azure AD site " + sensitivityLabel.getSiteId());
> 
>      // Hozzáadja az új címkét
>      String labelIdString = "{xxxxxxxx-xxxx-xxxx-xxxx-xxxxxxxxxxxx}"; // A politika által megadott érzékenységi címke azonosítója
>      UUID siteIdGuid = UUID.fromString("{xxxxxxxx-xxxx-xxxx-xxxx-xxxxxxxxxxxx}"); // A politika alapján kapott Azure AD oldal azonosítója
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
### getSlideById(long id) {#getSlideById-long-}
```
public final IBaseSlide getSlideById(long id)
```


Visszaad egy Slide, MasterSlide vagy LayoutSlide objektumot az azonosító alapján.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| id | long | A dia azonosítója. |

**Visszatér:**
[IBaseSlide](../../com.aspose.slides/ibaseslide) - IBaseSlide object.
### getSourceFormat() {#getSourceFormat--}
```
public final int getSourceFormat()
```


Visszaad információt arról, hogy melyik formátumból lett betöltve a bemutató. Csak olvasható [SourceFormat](../../com.aspose.slides/sourceformat).

**Visszatér:**
int
### getMasterTheme() {#getMasterTheme--}
```
public final IMasterTheme getMasterTheme()
```


Visszaadja a mester témát. Csak olvasható [IMasterTheme](../../com.aspose.slides/imastertheme).

--------------------

> ```
> The following examples shows how to change a theme effect by altering parts of elements of PowerPoint Presentation.
>  
>  //Példányosít egy prezentáció objektumot, amely egy prezentációfájlt képvisel
>  Presentation pres = new Presentation("Subtle_Moderate_Intense.pptx");
>  try {
>      pres.getMasterTheme().getFormatScheme().getLineStyles().get_Item(0).getFillFormat().getSolidFillColor().setColor(Color.RED);
>      ((FillFormat)pres.getMasterTheme().getFormatScheme().getLineStyles().get_Item(2)).setFillType(FillType.Solid);
>      ((FillFormat)pres.getMasterTheme().getFormatScheme().getLineStyles().get_Item(2)).getSolidFillColor().setColor(Color.GREEN);
>      ((EffectStyle)pres.getMasterTheme().getFormatScheme().getLineStyles().get_Item(2)).getEffectFormat().getOuterShadowEffect().setDistance(10f);
>      pres.save("Design_04_Subtle_Moderate_Intense-out.pptx", SaveFormat.Pptx);
>  }
>  finally
>  {
>      if (pres != null) pres.dispose();
>  }
> ```


**Visszatér:**
[IMasterTheme](../../com.aspose.slides/imastertheme)
### save(String fname, int format) {#save-java.lang.String-int-}
```
public final void save(String fname, int format)
```


Ment minden diát a bemutatóból egy fájlba a megadott formátummal.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| fname | java.lang.String | Az elkészített fájl elérési útja. |
| format | int | Az exportált adat formátuma. |

### save(OutputStream stream, int format) {#save-java.io.OutputStream-int-}
```
public final void save(OutputStream stream, int format)
```


Ment minden diát a bemutatóból egy streambe a megadott formátumban.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| stream | java.io.OutputStream | Kimeneti stream. |
| format | int | Az exportált adat formátuma. |

### save(String fname, int format, ISaveOptions options) {#save-java.lang.String-int-com.aspose.slides.ISaveOptions-}
```
public final void save(String fname, int format, ISaveOptions options)
```


Ment minden diát a bemutatóból egy fájlba a megadott formátummal és további beállításokkal.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| fname | java.lang.String | Az elkészített fájl elérési útja. |
| format | int | Az exportált adat formátuma. |
| options | [ISaveOptions](../../com.aspose.slides/isaveoptions) | További formátum opciók. |

### save(OutputStream stream, int format, ISaveOptions options) {#save-java.io.OutputStream-int-com.aspose.slides.ISaveOptions-}
```
public final void save(OutputStream stream, int format, ISaveOptions options)
```


Ment minden diát a bemutatóból egy streambe a megadott formátumban és további beállításokkal.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| stream | java.io.OutputStream | Kimeneti stream. |
| format | int | Az exportált adat formátuma. |
| options | [ISaveOptions](../../com.aspose.slides/isaveoptions) | További formátum opciók. |

### save(IXamlOptions options) {#save-com.aspose.slides.IXamlOptions-}
```
public final void save(IXamlOptions options)
```


Ment minden diát a bemutatóból egy fájlkészletbe, amely XAML megjelölést tartalmaz.

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
public final IImage[] getImages(IRenderingOptions options)
```


Visszaad egy Image objektumot a bemutató minden diájához.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Tiff opciók. |

**Visszatér:**
com.aspose.slides.IImage[] - Image objects.
### getImages(IRenderingOptions options, int[] slides) {#getImages-com.aspose.slides.IRenderingOptions-int---}
```
public final IImage[] getImages(IRenderingOptions options, int[] slides)
```


Visszaad egy bélyegkép Image objektumot a megadott diákhoz a bemutatóban.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Tiff opciók. |
| slides | int[] | A diák helyzetét tartalmazó tömb, 1-től kezdve. |

**Visszatér:**
com.aspose.slides.IImage[] - Image objects.
### getImages(IRenderingOptions options, float scaleX, float scaleY) {#getImages-com.aspose.slides.IRenderingOptions-float-float-}
```
public final IImage[] getImages(IRenderingOptions options, float scaleX, float scaleY)
```


Visszaad egy bélyegkép Image objektumot a bemutató minden diájához egyedi skálázással.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Tiff opciók. |
| scaleX | float | Az érték, amellyel a bélyegképet az X tengely mentén skálázzuk. |
| scaleY | float | Az érték, amellyel a bélyegképet az Y tengely mentén skálázzuk. |

**Visszatér:**
com.aspose.slides.IImage[] - Image objects.
### getImages(IRenderingOptions options, int[] slides, float scaleX, float scaleY) {#getImages-com.aspose.slides.IRenderingOptions-int---float-float-}
```
public final IImage[] getImages(IRenderingOptions options, int[] slides, float scaleX, float scaleY)
```


Visszaad egy bélyegkép Image objektumot a megadott diákhoz egyedi skálázással.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Tiff opciók. |
| slides | int[] | A diák helyzetét tartalmazó tömb, 1-től kezdve. |
| scaleX | float | Az érték, amellyel a bélyegképet az X tengely mentén skálázzuk. |
| scaleY | float | Az érték, amellyel a bélyegképet az Y tengely mentén skálázzuk. |

**Visszatér:**
com.aspose.slides.IImage[] - Image objects.
### getImages(IRenderingOptions options, Dimension imageSize) {#getImages-com.aspose.slides.IRenderingOptions-java.awt.Dimension-}
```
public final IImage[] getImages(IRenderingOptions options, Dimension imageSize)
```


Visszaad egy bélyegkép Image objektumot a bemutató minden diájához megadott mérettel.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Tiff opciók. |
| imageSize | java.awt.Dimension | A létrehozni kívánt kép mérete. |

**Visszatér:**
com.aspose.slides.IImage[] - Image objects.
### getImages(IRenderingOptions options, int[] slides, Dimension imageSize) {#getImages-com.aspose.slides.IRenderingOptions-int---java.awt.Dimension-}
```
public final IImage[] getImages(IRenderingOptions options, int[] slides, Dimension imageSize)
```


Visszaad egy bélyegkép Image objektumot a megadott diákhoz megadott mérettel.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Tiff opciók. |
| slides | int[] | A diák helyzetét tartalmazó tömb, 1-től kezdve. |
| imageSize | java.awt.Dimension | A létrehozni kívánt kép mérete. |

**Visszatér:**
com.aspose.slides.IImage[] - Image objects.
### save(String fname, int[] slides, int format) {#save-java.lang.String-int---int-}
```
public final void save(String fname, int[] slides, int format)
```


Ment a bemutató megadott diáit egy fájlba a megadott formátummal, megőrizve az oldalszámot.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| fname | java.lang.String | Az elkészített fájl elérési útja. |
| slides | int[] | A diák helyzetét tartalmazó tömb, 1-től kezdve. |
| format | int | Az exportált adat formátuma. |

### save(String fname, int[] slides, int format, ISaveOptions options) {#save-java.lang.String-int---int-com.aspose.slides.ISaveOptions-}
```
public final void save(String fname, int[] slides, int format, ISaveOptions options)
```


Ment a bemutató megadott diáit egy fájlba a megadott formátummal, megőrizve az oldalszámot.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| fname | java.lang.String | Az elkészített fájl elérési útja. |
| slides | int[] | A diák helyzetét tartalmazó tömb, 1-től kezdve. |
| format | int | Az exportált adat formátuma. |
| options | [ISaveOptions](../../com.aspose.slides/isaveoptions) | További formátum opciók. |

### save(OutputStream stream, int[] slides, int format) {#save-java.io.OutputStream-int---int-}
```
public final void save(OutputStream stream, int[] slides, int format)
```


Ment a bemutató megadott diáit egy streambe a megadott formátummal, megőrizve az oldalszámot.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| stream | java.io.OutputStream | Kimeneti stream. |
| slides | int[] | A diák helyzetét tartalmazó tömb, 1-től kezdve. |
| format | int | Az exportált adat formátuma. |

### save(OutputStream stream, int[] slides, int format, ISaveOptions options) {#save-java.io.OutputStream-int---int-com.aspose.slides.ISaveOptions-}
```
public final void save(OutputStream stream, int[] slides, int format, ISaveOptions options)
```


Ment a bemutató megadott diáit egy streambe a megadott formátummal, megőrizve az oldalszámot.

--------------------

> ```
> The following example shows how to convert PowerPoint to PNG.
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      for (int index = 0; index < pres.getSlides().size(); index++) {
>          ISlide slide = pres.getSlides().get_Item(index);
>          ImageIO.write(slide.getThumbnail(), "PNG", new java.io.File("slide_" + index + ".png"));
>      }
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to convert PowerPoint to PNG with custom dimensions.
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      float scaleX = 2f;
>      float scaleY = 2f;
>      for (int index = 0; index < pres.getSlides().size(); index++) {
>          ISlide slide = pres.getSlides().get_Item(index);
>          ImageIO.write(slide.getThumbnail(scaleX, scaleY), "PNG", new java.io.File("slide_" + index + ".png"));
>      }
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to convert PowerPoint to PNG with custom size.
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      Dimension size = new Dimension(960, 720);
>      for (int index = 0; index < pres.getSlides().size(); index++) {
>          ISlide slide = pres.getSlides().get_Item(index);
>          ImageIO.write(slide.getThumbnail(size), "PNG", new java.io.File("slide_" + index + ".png"));
>      }
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| stream | java.io.OutputStream | Kimeneti stream. |
| slides | int[] | A diák helyzetét tartalmazó tömb, 1-től kezdve. |
| format | int | Az exportált adat formátuma. |
| options | [ISaveOptions](../../com.aspose.slides/isaveoptions) | További formátum opciók. |

### joinPortionsWithSameFormatting() {#joinPortionsWithSameFormatting--}
```
public final void joinPortionsWithSameFormatting()
```


Egyesíti a futamokat (runs) azonos formázással minden bekezdésben, az összes alkalmas alakzatban, minden dián.

### dispose() {#dispose--}
```
public final void dispose()
```


Felszabadítja a Presentation objektum által használt összes erőforrást.

### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```


Visszaadja a szöveg szülő bemutatóját. Csak olvasható [IPresentation](../../com.aspose.slides/ipresentation).

**Visszatér:**
[IPresentation](../../com.aspose.slides/ipresentation)
### highlightText(String text, Color highlightColor) {#highlightText-java.lang.String-java.awt.Color-}
```
public final void highlightText(String text, Color highlightColor)
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
public final void highlightText(String text, Color highlightColor, ITextSearchOptions options, IFindResultCallback callback)
```


Kiemeli a mintaszöveg összes egyezését a megadott színnel.

--------------------

> ```
> The following code sample shows how to highlight text in a PowerPoint presentation.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      TextSearchOptions textSearchOptions = new TextSearchOptions();
>      textSearchOptions.setWholeWordsOnly(true);
>      // az összes különálló 'the' előfordulás kiemelése
>      presentation.highlightText("the", Color.MAGENTA, textSearchOptions, null);
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
public final void highlightRegex(Pattern regex, Color highlightColor, IFindResultCallback callback)
```


Kiemeli a reguláris kifejezés összes egyezését a megadott színnel.

--------------------

> ```
> The following code sample shows how to highlight text in a PowerPoint Presentation using a regular expression.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      Pattern regex = Pattern.compile("\\b[^\\s]{10,}\\b");
>      // kiemeli az összes 10 vagy több karakterből álló szót
>      presentation.highlightRegex(regex, Color.BLUE, null);
>      presentation.save("SomePresentation-out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| regex | java.util.regex.Pattern | A kiemelendő karakterláncok lekéréséhez használt reguláris kifejezés java.util.regex.Pattern. |
| highlightColor | java.awt.Color | A szöveg kiemeléséhez használt szín. |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | A visszahívási objektum a keresési eredmények fogadásához [IFindResultCallback](../../com.aspose.slides/ifindresultcallback). |

### replaceText(String oldText, String newText, ITextSearchOptions options, IFindResultCallback callback) {#replaceText-java.lang.String-java.lang.String-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-}
```
public final void replaceText(String oldText, String newText, ITextSearchOptions options, IFindResultCallback callback)
```

Lecseréli a megadott szöveg minden előfordulását egy másik megadott szöveggel.

--------------------

> ```
> A következő mintakód megmutatja, hogyan lehet az egyik megadott karakterláncot egy másik megadott karakterláncra cserélni.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx")
>  try {
>      TextSearchOptions textSearchOptions = new TextSearchOptions();
>      textSearchOptions.setWholeWordsOnly(true);
>      // Lecseréli az összes különálló 'the' előfordulást '***'-ra
>      presentation.replaceText("the", "***", textSearchOptions, null);
>      presentation.save("SomePresentation-out2.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| oldText | java.lang.String | A helyettesítendő karakterlánc. |
| newText | java.lang.String | A karakterlánc, amely a oldText minden előfordulását helyettesíti. |
| options | [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions) | A szövegkeresési beállítások [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions). |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | A visszahívási objektum a keresési eredmények fogadásához [IFindResultCallback](../../com.aspose.slides/ifindresultcallback). |

### replaceRegex(Pattern regex, String newText, IFindResultCallback callback) {#replaceRegex-java.util.regex.Pattern-java.lang.String-com.aspose.slides.IFindResultCallback-}
```
public final void replaceRegex(Pattern regex, String newText, IFindResultCallback callback)
```

Lecseréli a reguláris kifejezés összes egyezését a megadott karakterláncra.

--------------------

> ```
> The following code sample shows how to replace text using regular expression with the specified string.
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      Pattern regex = Pattern.compile("\\b[^\\s]{10,}\\b");
>      // Cseréli az összes 10 vagy több szimbólumból álló szót '***'-ra
>      presentation.replaceRegex(regex, "***", null);
>      presentation.save("SomePresentation-out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| regex | java.util.regex.Pattern | A cserélendő karakterláncok lekéréséhez használt reguláris kifejezés java.util.regex.Pattern. |
| newText | java.lang.String | A karakterlánc, amely a cserélendő karakterláncok minden előfordulását helyettesíti. |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | A visszahívási objektum a keresési eredmények fogadásához [IFindResultCallback](../../com.aspose.slides/ifindresultcallback). |

### refreshChartsData() {#refreshChartsData--}
```
public final void refreshChartsData()
```

Újratölti a bemutatóban lévő összes diagram adatát a forrásmunkafüzetekből.

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
public final void refreshChartsData(boolean skipFailedCharts)
```

Újratölti a bemutatóban lévő összes diagram adatát a forrásmunkafüzetekből.

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
| skipFailedCharts | boolean | Meghatározza, hogy a frissítési folyamat folytatódik-e, ha egy diagram nem frissíthető. Ha true, a kivételt okozó diagramok kihagyásra kerülnek; különben a kivétel továbbadható. |