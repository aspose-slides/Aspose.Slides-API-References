---
title: Presentation
second_title: Aspose.Slides Android-hoz Java API hivatkozás
description: Microsoft PowerPoint prezentációt reprezentál.
type: docs
url: /hu/com.aspose.slides/presentation/
---
**Öröklés:**
java.lang.Object

**Minden megvalósított interfész:**
[com.aspose.slides.IPresentation](../../com.aspose.slides/ipresentation), com.aspose.slides.IDOMObject
```
public final class Presentation implements IPresentation, IDOMObject
```

Microsoft PowerPoint prezentációt reprezentál.

--------------------

> ```
> The following example shows how to create PowerPoint Presentation.
>   
>  // Hozzon létre egy Presentation objektumot, amely egy prezentációfájlt reprezentál
>  Presentation pres = new Presentation();
>  try {
>      // Szerezze meg az első diát
>      ISlide slide = pres.getSlides().get_Item(0);
>      // Adjon hozzá egy line típusú autoshape-et
>      slide.getShapes().addAutoShape(ShapeType.Line, 50, 150, 300, 0);
>      // Mentse a prezentációfájlt.
>      pres.save("NewPresentation_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>   
>   The following example shows how to open and save Presentation.
>   
>  // Töltsön be bármilyen támogatott fájlt a Presentation-ben, pl. ppt, pptx, odp stb.
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
| [Presentation(InputStream stream)](#Presentation-java.io.InputStream-) | Ez a konstruktor a meglévő Presentation beolvasásának elsődleges módja. |
| [Presentation(InputStream stream, LoadOptions loadOptions)](#Presentation-java.io.InputStream-com.aspose.slides.LoadOptions-) | Ez a konstruktor a meglévő Presentation beolvasásának elsődleges módja. |
| [Presentation(String file)](#Presentation-java.lang.String-) | Ez a konstruktor egy forrásfájl útvonalát kapja, amelyből a Presentation tartalma beolvasásra kerül. |
| [Presentation(String file, LoadOptions loadOptions)](#Presentation-java.lang.String-com.aspose.slides.LoadOptions-) | Ez a konstruktor egy forrásfájl útvonalát kapja, amelyből a Presentation tartalma beolvasásra kerül. |

## Módszerek

| Módszer | Leírás |
| --- | --- |
| [getCurrentDateTime()](#getCurrentDateTime--) | Visszaadja vagy beállítja a dátumot és időt, amely helyettesíti a datetime mezők tartalmát. |
| [setCurrentDateTime(Date value)](#setCurrentDateTime-java.util.Date-) | Visszaadja vagy beállítja a dátumot és időt, amely helyettesíti a datetime mezők tartalmát. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | Visszaadja az aktuális HeaderFooter kezelőt. |
| [getProtectionManager()](#getProtectionManager--) | Visszaadja a prezentáció jogosultságainak kezelőjét. |
| [getSlides()](#getSlides--) | Visszaad egy listát az összes, a prezentációban definiált diáról. |
| [getSections()](#getSections--) | Visszaad egy listát az összes diaszekcióról, amely a prezentációban definiált. |
| [getSlideSize()](#getSlideSize--) | Visszaad egy dia méret objektumot. |
| [getNotesSize()](#getNotesSize--) | Visszaad egy jegyzet diák méret objektumot. |
| [getLayoutSlides()](#getLayoutSlides--) | Visszaad egy listát az összes elrendezés diáról, amely a prezentációban definiált. |
| [getMasters()](#getMasters--) | Visszaad egy listát az összes mester diáról, amely a prezentációban definiált. |
| [getMasterNotesSlideManager()](#getMasterNotesSlideManager--) | Visszaadja a jegyzet mester kezelőt. |
| [getMasterHandoutSlideManager()](#getMasterHandoutSlideManager--) | Visszaadja a kiosztó mester kezelőt. |
| [getFontsManager()](#getFontsManager--) | Visszaadja a betűtípusok kezelőjét. |
| [getDefaultTextStyle()](#getDefaultTextStyle--) | Visszaadja az alakzatok alapértelmezett szövegstílusát. |
| [getCommentAuthors()](#getCommentAuthors--) | Visszaadja a megjegyzés szerzők gyűjteményét. |
| [getDocumentProperties()](#getDocumentProperties--) | Visszaad egy DocumentProperties objektumot, amely tartalmazza a szabványos és egyéni dokumentumtulajdonságokat. |
| [getImages()](#getImages--) | Visszaadja a prezentációban lévő összes kép gyűjteményét. |
| [getAudios()](#getAudios--) | Visszaadja a prezentációba beágyazott összes hangfájl gyűjteményét. |
| [getVideos()](#getVideos--) | Visszaadja a prezentációba beágyazott összes videófájl gyűjteményét. |
| [getSlideShowSettings()](#getSlideShowSettings--) | Visszaadja a prezentáció diavetítés beállításait. |
| [getDigitalSignatures()](#getDigitalSignatures--) | Visszaadja a prezentáció aláírásához használt aláírások gyűjteményét. |
| [getCustomData()](#getCustomData--) | Visszaadja a prezentáció egyéni adatait. |
| [getAllCustomXmlParts()](#getAllCustomXmlParts--) | Visszaadja a prezentáció összes egyéni adat részét. |
| [getVbaProject()](#getVbaProject--) | Visszaadja vagy beállítja a VBA projektet a prezentáció makróival. |
| [setVbaProject(IVbaProject value)](#setVbaProject-com.aspose.slides.IVbaProject-) | Visszaadja vagy beállítja a VBA projektet a prezentáció makróival. |
| [getHyperlinkQueries()](#getHyperlinkQueries--) | Könnyű hozzáférést biztosít az összes hiperhivatkozáshoz, amelyek minden prezentációs dián megtalálhatók (kivéve mester, elrendezés és jegyzet diákat). |
| [getViewProperties()](#getViewProperties--) | Visszaadja a prezentációra kiterjedő nézeti tulajdonságokat. |
| [getFirstSlideNumber()](#getFirstSlideNumber--) | A prezentáció első diájának számát reprezentálja |
| [setFirstSlideNumber(int value)](#setFirstSlideNumber-int-) | A prezentáció első diájának számát reprezentálja |
| [getSensitivityLabels()](#getSensitivityLabels--) | Visszaadja a prezentáció dokumentumára alkalmazott érzékenységi címkék gyűjteményét. |
| [getSlideById(long id)](#getSlideById-long-) | Visszaad egy Slide, MasterSlide vagy LayoutSlide objektumot azonosító alapján. |
| [getSourceFormat()](#getSourceFormat--) | Visszaad információt arról, hogy melyik formátumból lett betöltve a prezentáció. |
| [getMasterTheme()](#getMasterTheme--) | Visszaadja a mester témát. |
| [save(String fname, int format)](#save-java.lang.String-int-) | Az összes prezentációs diát a megadott formátumú fájlba menti. |
| [save(OutputStream stream, int format)](#save-java.io.OutputStream-int-) | Az összes prezentációs diát a megadott formátumú adatfolyamba menti. |
| [save(String fname, int format, ISaveOptions options)](#save-java.lang.String-int-com.aspose.slides.ISaveOptions-) | Az összes prezentációs diát a megadott formátummal és további beállításokkal menti fájlba. |
| [save(OutputStream stream, int format, ISaveOptions options)](#save-java.io.OutputStream-int-com.aspose.slides.ISaveOptions-) | Az összes prezentációs diát a megadott formátummal és további beállításokkal menti adatfolyamba. |
| [save(IXamlOptions options)](#save-com.aspose.slides.IXamlOptions-) | Az összes prezentációs diát XAML jelölőnyelvet képviselő fájlok halmazába menti. |
| [getImages(IRenderingOptions options)](#getImages-com.aspose.slides.IRenderingOptions-) | Visszaad egy Image objektumot az összes prezentációs diához. |
| [getImages(IRenderingOptions options, int[] slides)](#getImages-com.aspose.slides.IRenderingOptions-int---) | Visszaad egy Thumbnail Image objektumot a megadott diáknál. |
| [getImages(IRenderingOptions options, float scaleX, float scaleY)](#getImages-com.aspose.slides.IRenderingOptions-float-float-) | Visszaad egy Thumbnail Image objektumot az összes diához egyéni méretezéssel. |
| [getImages(IRenderingOptions options, int[] slides, float scaleX, float scaleY)](#getImages-com.aspose.slides.IRenderingOptions-int---float-float-) | Visszaad egy Thumbnail Image objektumot a megadott diáknál egyéni méretezéssel. |
| [getImages(IRenderingOptions options, Size imageSize)](#getImages-com.aspose.slides.IRenderingOptions-com.aspose.slides.android.Size-) | Visszaad egy Thumbnail Image objektumot az összes diához megadott mérettel. |
| [getImages(IRenderingOptions options, int[] slides, Size imageSize)](#getImages-com.aspose.slides.IRenderingOptions-int---com.aspose.slides.android.Size-) | Visszaad egy Thumbnail Image objektumot a megadott diáknál megadott mérettel. |
| [save(String fname, int[] slides, int format)](#save-java.lang.String-int---int-) | A megadott diákat a prezentációból a megadott formátumú fájlba menti, megtartva az oldalszámot. |
| [save(String fname, int[] slides, int format, ISaveOptions options)](#save-java.lang.String-int---int-com.aspose.slides.ISaveOptions-) | A megadott diákat a prezentációból a megadott formátumú fájlba menti, megtartva az oldalszámot. |
| [save(OutputStream stream, int[] slides, int format)](#save-java.io.OutputStream-int---int-) | A megadott diákat a prezentációból a megadott formátumú adatfolyamba menti, megtartva az oldalszámot. |
| [save(OutputStream stream, int[] slides, int format, ISaveOptions options)](#save-java.io.OutputStream-int---int-com.aspose.slides.ISaveOptions-) | A megadott diákat a prezentációból a megadott formátumú adatfolyamba menti, megtartva az oldalszámot. |
| [joinPortionsWithSameFormatting()](#joinPortionsWithSameFormatting--) | Összevonja az azonos formázású futamokat minden bekezdésben, minden alkalmas alakzatban, minden dián. |
| [dispose()](#dispose--) | Felszabadítja a Presentation objektum által használt összes erőforrást. |
| [getPresentation()](#getPresentation--) | Visszaadja a szöveg szülő prezentációját. |
| [highlightText(String text, Integer highlightColor)](#highlightText-java.lang.String-java.lang.Integer-) | Kiemeli a mintaszöveg összes előfordulását a megadott színnel. |
| [highlightText(String text, Integer highlightColor, ITextSearchOptions options, IFindResultCallback callback)](#highlightText-java.lang.String-java.lang.Integer-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-) | Kiemeli a mintaszöveg összes előfordulását a megadott színnel. |
| [highlightRegex(Pattern regex, Integer highlightColor, IFindResultCallback callback)](#highlightRegex-java.util.regex.Pattern-java.lang.Integer-com.aspose.slides.IFindResultCallback-) | Kiemeli a reguláris kifejezés összes előfordulását a megadott színnel. |
| [replaceText(String oldText, String newText, ITextSearchOptions options, IFindResultCallback callback)](#replaceText-java.lang.String-java.lang.String-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-) | Lecseréli a megadott szöveg összes előfordulását egy másik megadott szövegre. |
| [replaceRegex(Pattern regex, String newText, IFindResultCallback callback)](#replaceRegex-java.util.regex.Pattern-java.lang.String-com.aspose.slides.IFindResultCallback-) | Lecseréli a reguláris kifejezés összes előfordulását a megadott karakterláncra. |

### Presentation() {#Presentation--}
```
public Presentation()
```

Ez a konstruktor új prezentációt hoz létre a semmiből. A létrehozott prezentáció egy üres diát tartalmaz.

### Presentation(LoadOptions loadOptions) {#Presentation-com.aspose.slides.LoadOptions-}
```
public Presentation(LoadOptions loadOptions)
```

Ez a konstruktor új prezentációt hoz létre a semmiből. A létrehozott prezentáció egy üres diát tartalmaz.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| loadOptions | [LoadOptions](../../com.aspose.slides/loadoptions) | További betöltési beállítások. |

### Presentation(InputStream stream) {#Presentation-java.io.InputStream-}
```
public Presentation(InputStream stream)
```

Ez a konstruktor a meglévő Presentation beolvasásának elsődleges módja.

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

Ez a konstruktor a meglévő Presentation beolvasásának elsődleges módja.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| stream | java.io.InputStream | Bemeneti adatfolyam. |
| loadOptions | [LoadOptions](../../com.aspose.slides/loadoptions) | További betöltési beállítások. |

### Presentation(String file) {#Presentation-java.lang.String-}
```
public Presentation(String file)
```

Ez a konstruktor egy forrásfájl útvonalát kapja, amelyből a Presentation tartalma beolvasásra kerül.

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

Ez a konstruktor egy forrásfájl útvonalát kapja, amelyből a Presentation tartalma beolvasásra kerül.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| file | java.lang.String | Bemeneti fájl. |
| loadOptions | [LoadOptions](../../com.aspose.slides/loadoptions) | További betöltési beállítások. |

### getCurrentDateTime() {#getCurrentDateTime--}
```
public final Date getCurrentDateTime()
```

Visszaadja vagy beállítja a dátumot és időt, amely helyettesíti a datetime mezők tartalmát. Alapértelmezés szerint a Presentation objektum létrehozásának ideje. Olvasás/írás java.util.Date.

**Visszatérési érték:**
java.util.Date

### setCurrentDateTime(Date value) {#setCurrentDateTime-java.util.Date-}
```
public final void setCurrentDateTime(Date value)
```

Visszaadja vagy beállítja a dátumot és időt, amely helyettesíti a datetime mezők tartalmát. Alapértelmezés szerint a Presentation objektum létrehozásának ideje. Olvasás/írás java.util.Date.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | java.util.Date |  |

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Visszaadja a Parent_Immediate objektumot. Csak olvasható IDOMObject.

**Visszatérési érték:**
com.aspose.slides.IDOMObject

### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public final IPresentationHeaderFooterManager getHeaderFooterManager()
```

Visszaadja az aktuális HeaderFooter kezelőt. Csak olvasható [IPresentationHeaderFooterManager](../../com.aspose.slides/ipresentationheaderfootermanager).

--------------------

> ```
> The following example shows how to set footer visibility inside Slide of PowerPoint Presentation.
>  
>  Presentation pres = new Presentation("presentation.ppt");
>  try
>  {
>      IBaseSlideHeaderFooterManager headerFooterManager = pres.getSlides().get_Item(0).getHeaderFooterManager();
>      if (!headerFooterManager.isFooterVisible()) // Az IsFooterVisible tulajdonság azt jelzi, hogy egy dia lábléchelyőrző nincs jelen.
>      {
>          headerFooterManager.setFooterVisibility(true); // A SetFooterVisibility metódus arra szolgál, hogy a dia lábléchelyőrző láthatóvá váljon.
>      }
>      if (!headerFooterManager.isSlideNumberVisible()) // Az IsSlideNumberVisible tulajdonság azt jelzi, hogy egy dia oldalszámhelyőrző nincs jelen.
>      {
>          headerFooterManager.setSlideNumberVisibility(true); // A SetSlideNumberVisibility metódus arra szolgál, hogy a dia oldalszámhelyőrző láthatóvá váljon.
>      }
>      if (!headerFooterManager.isDateTimeVisible()) // Az IsDateTimeVisible tulajdonság azt jelzi, hogy egy dia dátum-idő helyőrző nincs jelen.
>      {
>          headerFooterManager.setDateTimeVisibility(true); // A SetFooterVisibility metódus arra szolgál, hogy a dia dátum-idő helyőrző láthatóvá váljon.
>      }
>      headerFooterManager.setFooterText("Footer text"); // A SetFooterText metódus a szöveg beállítására szolgál a dia lábléchelyőrzőben.
>      headerFooterManager.setDateTimeText("Date and time text"); // A SetDateTimeText metódus a szöveg beállítására szolgál a dia dátum-idő helyőrzőben.
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
>      headerFooterManager.setFooterAndChildFootersVisibility(true); // A SetFooterAndChildFootersVisibility metódus arra szolgál, hogy a mesterdia és az összes gyermek lábléchelyőrző láthatóvá váljon.
>      headerFooterManager.setSlideNumberAndChildSlideNumbersVisibility(true); // A SetSlideNumberAndChildSlideNumbersVisibility metódus arra szolgál, hogy a mesterdia és az összes gyermek oldalszámhelyőrző láthatóvá váljon.
>      headerFooterManager.setDateTimeAndChildDateTimesVisibility(true); // A SetDateTimeAndChildDateTimesVisibility metódus arra szolgál, hogy a mesterdia és az összes gyermek dátum-idő helyőrző láthatóvá váljon.
> 
>      headerFooterManager.setFooterAndChildFootersText("Footer text"); // A SetFooterAndChildFootersText metódus a szöveg beállítására szolgál a mesterdián és az összes gyermek lábléchelyőrzőben.
>      headerFooterManager.setDateTimeAndChildDateTimesText("Date and time text"); // A SetDateTimeAndChildDateTimesText metódus a szöveg beállítására szolgál a mesterdián és az összes gyermek dátum-idő helyőrzőben.
>  }
>  finally
>  {
>      if (pres != null) pres.dispose();
>  }
> ```


**Visszatérési érték:**
[IPresentationHeaderFooterManager](../../com.aspose.slides/ipresentationheaderfootermanager)

### getProtectionManager() {#getProtectionManager--}
```
public final IProtectionManager getProtectionManager()
```

Visszaadja a prezentáció jogosultságainak kezelőjét. Csak olvasható [IProtectionManager](../../com.aspose.slides/iprotectionmanager).

**Visszatérési érték:**
[IProtectionManager](../../com.aspose.slides/iprotectionmanager)

### getSlides() {#getSlides--}
```
public final ISlideCollection getSlides()
```

Visszaad egy listát az összes, a prezentációban definiált diáról. Csak olvasható [ISlideCollection](../../com.aspose.slides/islidecollection).

--------------------

> ```
> The following example shows how to set slides' background color of PowerPoint Presentation.
>  
>  // Példányosítja a Presentation osztályt, amely a prezentációfájlt reprezentálja
>  Presentation pres = new Presentation();
>  try
>  {
>      // Az első ISlide háttérszínét kékre állítja
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
>  // Példányosítja a Presentation osztályt, amely a prezentációfájlt reprezentálja
>  Presentation pres = new Presentation("SetImageAsBackground.pptx");
>  try {
>      // Háttér beállítása képpel
>      pres.getSlides().get_Item(0).getBackground().setType(BackgroundType.OwnBackground);
>      pres.getSlides().get_Item(0).getBackground().getFillFormat().setFillType(FillType.Picture);
>      pres.getSlides().get_Item(0).getBackground().getFillFormat().getPictureFillFormat().setPictureFillMode(PictureFillMode.Stretch);
>      // Kép beállítása
>      FileInputStream fos = null;
>      try {
>          fos = new FileInputStream("Tulips.jpg");
>          // Kép hozzáadása a prezentáció képgyűjteményéhez
>          IPPImage imgx = pres.getImages().addImage(fos);
>          pres.getSlides().get_Item(0).getBackground().getFillFormat().getPictureFillFormat().getPicture().setImage(imgx);
>      } finally {
>          if (fos != null) fos.close();
>      }
>      // A prezentáció írása lemezre
>      pres.save("ContentBG_Img_out.pptx", SaveFormat.Pptx);
>  } catch (IOException e) { }
>  finally
>  {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to add slide transition Presentation.
>  
>  // Példányosítja a Presentation osztályt a forrás prezentáció betöltéséhez
>  Presentation pres = new Presentation("AccessSlides.pptx");
>  try
>  {
>      // Kör típusú átmenet alkalmazása az 1. diára
>      pres.getSlides().get_Item(0).getSlideShowTransition().setType(TransitionType.Circle);
>      // Comb típusú átmenet alkalmazása a 2. diára
>      pres.getSlides().get_Item(1).getSlideShowTransition().setType(TransitionType.Comb);
>      // A prezentáció írása lemezre
>      pres.save("SampleTransition_out.pptx", SaveFormat.Pptx);
>  }
>  finally
>  {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to add advanced slide Transition.
>  
>  // Példányosítja a Presentation osztályt, amely egy prezentációfájlt reprezentál
>  Presentation pres = new Presentation("BetterSlideTransitions.pptx");
>  try
>  {
>      // Kör típusú átmenet alkalmazása az 1. diára
>      pres.getSlides().get_Item(0).getSlideShowTransition().setType(TransitionType.Circle);
>      // Az átmenet időtartamának beállítása 3 másodperc
>      pres.getSlides().get_Item(0).getSlideShowTransition().setAdvanceOnClick(true);
>      pres.getSlides().get_Item(0).getSlideShowTransition().setAdvanceAfterTime(3000);
>      // Comb típusú átmenet alkalmazása a 2. diára
>      pres.getSlides().get_Item(1).getSlideShowTransition().setType(TransitionType.Comb);
>      // Az átmenet időtartamának beállítása 5 másodperc
>      pres.getSlides().get_Item(1).getSlideShowTransition().setAdvanceOnClick(true);
>      pres.getSlides().get_Item(1).getSlideShowTransition().setAdvanceAfterTime(5000);
>      // Zoom típusú átmenet alkalmazása a 3. diára
>      pres.getSlides().get_Item(2).getSlideShowTransition().setType(TransitionType.Zoom);
>      // Az átmenet időtartamának beállítása 7 másodperc
>      pres.getSlides().get_Item(2).getSlideShowTransition().setAdvanceOnClick(true);
>      pres.getSlides().get_Item(2).getSlideShowTransition().setAdvanceAfterTime(7000);
>      // A prezentáció írása lemezre
>      pres.save("SampleTransition_out.pptx", SaveFormat.Pptx);
>  }
>  finally
>  {
>      if (pres != null) pres.dispose();
>  }
> ```


**Visszatérési érték:**
[ISlideCollection](../../com.aspose.slides/islidecollection)

### getSections() {#getSections--}
```
public final ISectionCollection getSections()
```

Visszaad egy listát az összes diaszekcióról, amely a prezentációban definiált. Csak olvasható [ISectionCollection](../../com.aspose.slides/isectioncollection).

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
>      // section1 befejeződik a newSlide2-nél, és utána a section2 kezdődik
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


**Visszatérési érték:**
[ISectionCollection](../../com.aspose.slides/isectioncollection)

### getSlideSize() {#getSlideSize--}
```
public final ISlideSize getSlideSize()
```

Visszaad egy dia méret objektumot. Csak olvasható [ISlideSize](../../com.aspose.slides/islidesize).

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
>  // Példányosít egy Presentation objektumot, amely egy prezentációfájlt reprezentál
>  Presentation presentation = new Presentation("AccessSlides.pptx");
>  try {
>      Presentation auxPresentation = new Presentation();
>      try {
>          ISlide slide = presentation.getSlides().get_Item(0);
>          // Állítsa be a generált prezentációk diaméretét a forráséval megegyezőre
>          presentation.getSlideSize().setSize(540, 720, SlideSizeScaleType.EnsureFit); // A SetSize metódus a diaméret beállítására szolgál, a tartalom méretezésével, hogy biztosan illeszkedjen
>          presentation.getSlideSize().setSize(SlideSizeType.A4Paper, SlideSizeScaleType.Maximize); // A SetSize metódus a diaméret beállítására szolgál, a tartalom méretének maximalizálásával
>          // Mentse a prezentációt a lemezre
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
>      pres.getSlideSize().setSize(780, 540, SlideSizeScaleType.DoNotScale); // A4 papírméret
>      pres.save("pres-a4-slide-size.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Visszatérési érték:**
[ISlideSize](../../com.aspose.slides/islidesize)

### getNotesSize() {#getNotesSize--}
```
public final INotesSize getNotesSize()
```

Visszaad egy jegyzet dia méret objektumot. Csak olvasható [INotesSize](../../com.aspose.slides/inotessize).

**Visszatérési érték:**
[INotesSize](../../com.aspose.slides/inotessize)

### getLayoutSlides() {#getLayoutSlides--}
```
public final IGlobalLayoutSlideCollection getLayoutSlides()
```

Visszaad egy listát az összes elrendezés diáról, amely a prezentációban definiált. Csak olvasható [IGlobalLayoutSlideCollection](../../com.aspose.slides/igloballayoutslidecollection).

--------------------

Használhatja az IMasterSlide.LayoutSlides tulajdonságot a layout diák hozzáadásához/beszúrásához/eltávolításához/klónozásához.

**Visszatérési érték:**
[IGlobalLayoutSlideCollection](../../com.aspose.slides/igloballayoutslidecollection)

### getMasters() {#getMasters--}
```
public final IMasterSlideCollection getMasters()
```

Visszaad egy listát az összes mester diáról, amely a prezentációban definiált. Csak olvasható [IMasterSlideCollection](../../com.aspose.slides/imasterslidecollection).

--------------------

> ```
> The following examples shows how to adding Images to Master Slides of PowerPoint Presentation.
>  
>  Presentation pres = new Presentation();
>  try {
>      ISlide slide = pres.getSlides().get_Item(0);
>      IMasterSlide masterSlide = slide.getLayoutSlide().getMasterSlide();
>      FileInputStream fos = null;
>      try {
>          fos = new FileInputStream("image.png");
>          IPPImage image = pres.getImages().addImage(fos);
>          masterSlide.getShapes().addPictureFrame(ShapeType.Rectangle, 10, 10, 100, 100, image);
>      } finally {
>          if (fos != null) fos.close();
>      }
>      pres.save("pres.pptx", SaveFormat.Pptx);
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following examples shows how to change the background color of the master slide of PowerPoint Presentation.
>  
>  // Példányosítja a Presentation osztályt, amely a prezentációfájlt reprezentálja
>  Presentation pres = new Presentation();
>  try
>  {
>      // A Master ISlide háttérszínét erdei zöldre állítja
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
>  // Példányosítja a Presentation osztályt, amely a prezentációfájlt reprezentálja
>  Presentation presentation = new Presentation("AccessSlides.pptx");
>  try
>  {
>      // Megpróbálja keresni a layout dia típus alapján
>      IMasterLayoutSlideCollection layoutSlides = presentation.getMasters().get_Item(0).getLayoutSlides();
>      ILayoutSlide layoutSlide = null;
>      if (layoutSlides.getByType(SlideLayoutType.TitleAndObject) != null)
>          layoutSlide = layoutSlides.getByType(SlideLayoutType.TitleAndObject);
>      else
>          layoutSlide = layoutSlides.getByType(SlideLayoutType.Title);
> 
>      if (layoutSlide == null)
>      {
>          // Olyan helyzet, amikor egy prezentáció nem tartalmaz bizonyos típusú elrendezéseket.
>          // A prezentációfájl csak Üres és Egyéni elrendezés típusokat tartalmaz.
>          // De az Egyéni típusú layout diák különböző dianevekkel rendelkeznek,
>          // például "Title", "Title and Content", stb. És ezek használata lehetséges
>          // nevek a layout dia kiválasztásához.
>          // Továbbá lehetséges a helyőrző alakzat típusok készletének használata. Például,
>          // A Title diának csak Title helyőrző típusa kell legyen
>          // stb.
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


**Visszatérési érték:**
[IMasterSlideCollection](../../com.aspose.slides/imasterslidecollection)

### getMasterNotesSlideManager() {#getMasterNotesSlideManager--}
```
public final IMasterNotesSlideManager getMasterNotesSlideManager()
```

Visszaadja a jegyzet mester kezelőt. Csak olvasható [IMasterNotesSlideManager](../../com.aspose.slides/imasternotesslidemanager).

**Visszatérési érték:**
[IMasterNotesSlideManager](../../com.aspose.slides/imasternotesslidemanager)

### getMasterHandoutSlideManager() {#getMasterHandoutSlideManager--}
```
public final IMasterHandoutSlideManager getMasterHandoutSlideManager()
```

Visszaadja a kiosztó mester kezelőt. Csak olvasható [IMasterHandoutSlideManager](../../com.aspose.slides/imasterhandoutslidemanager).

**Visszatérési érték:**
[IMasterHandoutSlideManager](../../com.aspose.slides/imasterhandoutslidemanager)

### getFontsManager() {#getFontsManager--}
```
public final IFontsManager getFontsManager()
```

Visszaadja a betűtípusok kezelőjét. Csak olvasható [IFontsManager](../../com.aspose.slides/ifontsmanager).

--------------------

> ```
> The following example shows how to add embedded fonts to PowerPoint Presentation.
>  
>  // Betölti a prezentációt
>  Presentation pres = new Presentation("Fonts.pptx");
>  try {
>      // Betölti a cserélendő forrásbetűtípust
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


**Visszatérési érték:**
[IFontsManager](../../com.aspose.slides/ifontsmanager)

### getDefaultTextStyle() {#getDefaultTextStyle--}
```
public final ITextStyle getDefaultTextStyle()
```

Visszaadja az alakzatok alapértelmezett szövegstílusát. Csak olvasható [ITextStyle](../../com.aspose.slides/itextstyle).

**Visszatérési érték:**
[ITextStyle](../../com.aspose.slides/itextstyle)

### getCommentAuthors() {#getCommentAuthors--}
```
public int ????
```

Visszaadja a megjegyzés szerzők gyűjteményét. Csak olvasható [ICommentAuthorCollection](../../com.aspose.slides/icommentauthorcollection).

**Visszatérési érték:**
[ICommentAuthorCollection](../../com.aspose.slides/icommentauthorcollection)

### getDocumentProperties() {#getDocumentProperties--}
```
public final IDocumentProperties getDocumentProperties()
```

Visszaad egy DocumentProperties objektumot, amely tartalmazza a szabványos és egyéni dokumentumtulajdonságokat. Csak olvasható [IDocumentProperties](../../com.aspose.slides/idocumentproperties).

**Visszatérési érték:**
[IDocumentProperties](../../com.aspose.slides/idocumentproperties)

### getImages() {#getImages--}
```
public final IImageCollection getImages()
```

Visszaadja a prezentációban lévő összes kép gyűjteményét. Csak olvasható [IImageCollection](../../com.aspose.slides/iimagecollection).

--------------------

> ```
> The following examples shows how to add image as BLOB in PowerPoint Presentation.
>  
>  // létrehozza az új prezentációt, amelyhez a képet hozzáadjuk.
>  Presentation pres = new Presentation();
>  try
>  {
>      // feltételezve, hogy rendelkezünk a nagy képfájllal, amelyet a prezentációba szeretnénk beleilleszteni
>      FileInputStream fip = new FileInputStream("large_image.jpg");
>      try
>      {
>          // Adjunk hozzá képet a prezentációhoz - a KeepLocked viselkedést választjuk, mert
>          // NEM szándékozzuk elérni a "largeImage.png" fájlt.
>          IPPImage img = pres.getImages().addImage(fip, LoadingStreamBehavior.KeepLocked);
>          pres.getSlides().get_Item(0).getShapes().addPictureFrame(ShapeType.Rectangle, 0, 0, 300, 200, img);
>          // Mentse a prezentációt. Míg egy nagy prezentáció kerül kiírásra, a memóriahasználat
>          // alacsony marad a pres objektum élettartama alatt
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
>      FileInputStream fos = null;
>      try {
>          fos = new FileInputStream("image.png");
>          // Hozzáadja a képet a prezentációhoz
>          IPPImage image = pres.getImages().addImage(fos);
>          // Létrehozza a képkeretet az 1. dián a korábban hozzáadott kép alapján
>          IPictureFrame pictureFrame = pres.getSlides().get_Item(0).getShapes().addPictureFrame(ShapeType.Rectangle, 10, 10, 100, 100, image);
>          pictureFrame.setHyperlinkClick(new Hyperlink("https://www.aspose.com/"));
>          pictureFrame.getHyperlinkClick().setTooltip("More than 70% Fortune 100 companies trust Aspose APIs");
>      } finally {
>          if (fos != null) fos.close();
>      }
>      pres.save("pres-out.pptx", SaveFormat.Pptx);
>  } catch (IOException e){ }
>  finally
>  {
>      if (pres != null) pres.dispose();
>  }
> ```


**Visszatérési érték:**
[IImageCollection](../../com.aspose.slides/iimagecollection)

### getAudios() {#getAudios--}
```
public final IAudioCollection getAudios()
```

Visszaadja a prezentációba beágyazott összes hangfájl gyűjteményét. Csak olvasható [IAudioCollection](../../com.aspose.slides/iaudiocollection).

--------------------

> ```
> The following examples shows how to add a hyperlink to an audio file.
>  
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream fos = null;
>      try {
>          fos = new FileInputStream("audio.mp3");
>          IAudio audio = pres.getAudios().addAudio(fos);
>          IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(10, 10, 100, 100, audio);
>          audioFrame.setHyperlinkClick(new Hyperlink("https://www.aspose.com/"));
>          audioFrame.getHyperlinkClick().setTooltip("More than 70% Fortune 100 companies trust Aspose APIs");
>      } finally {
>          if (fos != null) fos.close();
>      }
>      pres.save("pres-out.pptx", SaveFormat.Pptx);
>  }
>  catch (IOException e) {}
>  finally
>  {
>      if (pres != null) pres.dispose();
>  }
> ```


**Visszatérési érték:**
[IAudioCollection](../../com.aspose.slides/iaudiocollection)

### getVideos() {#getVideos--}
```
public final IVideoCollection getVideos()
```

Visszaadja a prezentációba beágyazott összes videófájl gyűjteményét. Csak olvasható [IVideoCollection](../../com.aspose.slides/ivideocollection).

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

**Visszatérési érték:**
[IVideoCollection](../../com.aspose.slides/ivideocollection)

### getSlideShowSettings() {#getSlideShowSettings--}
```
public final SlideShowSettings getSlideShowSettings()
```

Visszaadja a prezentáció diavetítés beállításait.

**Visszatérési érték:**
[SlideShowSettings](../../com.aspose.slides/slideshowsettings)

### getDigitalSignatures() {#getDigitalSignatures--}
```
public final IDigitalSignatureCollection getDigitalSignatures()
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


**Visszatérési érték:**
[IDigitalSignatureCollection](../../com.aspose.slides/idigitalsignaturecollection)

### getCustomData() {#getCustomData--}
```
public final ICustomData getCustomData()
```

Visszaadja a prezentáció egyéni adatait. Csak olvasható [ICustomData](../../com.aspose.slides/icustomdata).

**Visszatérési érték:**
[ICustomData](../../com.aspose.slides/icustomdata)

### getAllCustomXmlParts() {#getAllCustomXmlParts--}
```
public final ICustomXmlPart[] getAllCustomXmlParts()
```

Visszaadja a prezentáció összes egyéni adat részét. Csak olvasható ICustomXmlPart[].

--------------------

> ```
> The following examples show how to clear all custom xml parts from PowerPoint Presentation.
>  
>  Presentation pres = new Presentation("PresentationWithCustomXml.pptx");
>  try {
>      // Iterálja az összes egyéni XML részt
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


**Visszatérési érték:**
com.aspose.slides.ICustomXmlPart[]

### getVbaProject() {#getVbaProject--}
```
public final IVbaProject getVbaProject()
```

Visszaadja vagy beállítja a VBA projektet a prezentáció makróival. Olvasás/írás [IVbaProject](../../com.aspose.slides/ivbaproject).

**Visszatérési érték:**
[IVbaProject](../../com.aspose.slides/ivbaproject)

### setVbaProject(IVbaProject value) {#setVbaProject-com.aspose.slides.IVbaProject-}
```
public final void setVbaProject(IVbaProject value)
```

Visszaadja vagy beállítja a VBA projektet a prezentáció makróival. Olvasás/írás [IVbaProject](../../com.aspose.slides/ivbaproject).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | [IVbaProject](../../com.aspose.slides/ivbaproject) |  |

### getHyperlinkQueries() {#getHyperlinkQueries--}
```
public final IHyperlinkQueries getHyperlinkQueries()
```

Könnyű hozzáférést biztosít az összes hiperhivatkozáshoz, amelyek minden prezentációs dián megtalálhatók (kivéve mester, elrendezés és jegyzet diákat). Csak olvasható [IHyperlinkQueries](../../com.aspose.slides/ihyperlinkqueries).

**Visszatérési érték:**
[IHyperlinkQueries](../../com.aspose.slides/ihyperlinkqueries)

### getViewProperties() {#getViewProperties--}
```
public final IViewProperties getViewProperties()
```

Visszaadja a prezentációra kiterjedő nézeti tulajdonságokat. Csak olvasható [IViewProperties](../../com.aspose.slides/iviewproperties).

**Visszatérési érték:**
[IViewProperties](../../com.aspose.slides/iviewproperties)

### getFirstSlideNumber() {#getFirstSlideNumber--}
```
public final int getFirstSlideNumber()
```

A prezentáció első diájának számát reprezentálja

**Visszatérési érték:**
int

### setFirstSlideNumber(int value) {#setFirstSlideNumber-int-}
```
public final void setFirstSlideNumber(int value)
```

A prezentáció első diájának számát reprezentálja

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |

### getSensitivityLabels() {#getSensitivityLabels--}
```
public final ISensitivityLabelCollection getSensitivityLabels()
```

Visszaadja a prezentáció dokumentumára alkalmazott érzékenységi címkék gyűjteményét. Csak olvasható [ISensitivityLabelCollection](../../com.aspose.slides/isensitivitylabelcollection).

--------------------

> ```
> Presentation pres = new Presentation("SomePresentation.pptx");
>  try {
>      ISensitivityLabelCollection sensitivityLabels = pres.getSensitivityLabels();
> 
>      // Az alkalmazott címkék kiíratása
>      for (ISensitivityLabel sensitivityLabel : sensitivityLabels)
>          System.out.println("Label Id " + sensitivityLabel.getId() + " from Azure AD site " + sensitivityLabel.getSiteId());
> 
>      // Új címke hozzáadása
>      String labelIdString = "{xxxxxxxx-xxxx-xxxx-xxxx-xxxxxxxxxxxx}"; // A bizalmasítási címke azonosítóját kérdezi le a szabályzóból
>      UUID siteIdGuid = UUID.fromString("{xxxxxxxx-xxxx-xxxx-xxxx-xxxxxxxxxxxx}"); // Az Azure AD hely azonosítóját kérdezi le a szabályzóból
>      ISensitivityLabel label = sensitivityLabels.add(labelIdString, siteIdGuid, true, SensitivityLabelAssignmentType.Privileged);
>      label.getContentMarkTypes().addItem(SensitivityLabelContentType.Footer);
> 
>      pres.save("SensitivityLabel.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Visszatérési érték:**
[ISensitivityLabelCollection](../../com.aspose.slides/isensitivitylabelcollection)

### getSlideById(long id) {#getSlideById-long-}
```
public final IBaseSlide getSlideById(long id)
```

Visszaad egy Slide, MasterSlide vagy LayoutSlide objektumot azonosító alapján.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| id | long | A dia azonosítója. |

**Visszatérési érték:**
[IBaseSlide](../../com.aspose.slides/ibaseslide) - IBaseSlide objektum.

### getSourceFormat() {#getSourceFormat--}
```
public final int getSourceFormat()
```

Visszaad információt arról, hogy melyik formátumból lett betöltve a prezentáció. Csak olvasható [SourceFormat](../../com.aspose.slides/sourceformat).

**Visszatérési érték:**
int

### getMasterTheme() {#getMasterTheme--}
```
public final IMasterTheme getPower ...
```

Visszaadja a mester témát. Csak olvasható [IMasterTheme](../../com.aspose.slides/imastertheme).

--------------------

> ```
> The following examples shows how to change a theme effect by altering parts of elements of PowerPoint Presentation.
>  
>  // Létrehozza a Presentation objektumot, amely egy prezentációfájlt reprezentál
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


**Visszatérési érték:**
[IMasterTheme](../../com.aspose.slides/imastertheme)

### save(String fname, int format) {#save-java.lang.String-int-}
```
public final void save(String fname, int format)
```

Az összes prezentációs diát a megadott formátumú fájlba menti.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| fname | java.lang.String | A létrehozott fájl útvonala. |
| format | int | A exportált adatok formátuma. |

### save(OutputStream stream, int format) {#save-java.io.OutputStream-int-}
```
public final void save(OutputStream stream, int format)
```

Az összes prezentációs diát a megadott formátumú adatfolyamba menti.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| stream | java.io.OutputStream | Kimeneti adatfolyam. |
| format | int | A exportált adatok formátuma. |

### save(String fname, int format, ISaveOptions options) {#save-java.lang.String-int-com.aspose.slides.ISaveOptions-}
```
public final void save(String fname, int format, ISaveOptions options)
```

Az összes prezentációs diát a megadott formátummal és további beállításokkal menti fájlba.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| fname | java.lang.String | A létrehozott fájl útvonala. |
| format | int | A exportált adatok formátuma. |
| options | [ISaveOptions](../../com.aspose.slides/isaveoptions) | További formátum beállítások. |

### save(OutputStream stream, int format, ISaveOptions options) {#save-java.io.OutputStream-int-com.aspose.slides.ISaveOptions-}
```
public final void save(OutputStream stream, int format, ISaveOptions options)
```

Az összes prezentációs diát a megadott formátummal és további beállításokkal menti adatfolyamba.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| stream | java.io.OutputStream | Kimeneti adatfolyam. |
| format | int | A exportált adatok formátuma. |
| options | [ISaveOptions](../../com.aspose.slides/isaveoptions) | További formátum beállítások. |

### save(IXamlOptions options) {#save-com.aspose.slides.IXamlOptions-}
```
public final void save(IXamlOptions options)
```

Az összes prezentációs diát XAML jelölőnyelvet képviselő fájlok halmazába menti.

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
| options | [IXamlOptions](../../com.aspose.slides/ixamloptions) | A XAML formátum beállításai. |

### getImages(IRenderingOptions options) {#getImages-com.aspose.slides.IRenderingOptions-}
```
public final IImage[] getImages(IRenderingOptions options)
```

Visszaad egy Image objektumot az összes prezentációs diához.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Tiff beállítások. |

**Visszatérési érték:**
com.aspose.slides.IImage[] - Image objektumok.

### getImages(IRenderingOptions options, int[] slides) {#getImages-com.aspose.slides.IRenderingOptions-int---}
```
public final IImage[] getImages(IRenderingOptions options, int[] slides)
```

Visszaad egy Thumbnail Image objektumot a megadott diáknál.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Tiff beállítások. |
| slides | int[] | A diák pozícióit tartalmazó tömb, 1-től indulva. |

**Visszatérési érték:**
com.aspose.slides.IImage[] - Image objektumok.

### getImages(IRenderingOptions options, float scaleX, float scaleY) {#getImages-com.aspose.slides.IRenderingOptions-float-float-}
```
public final IImage[] getImages(IRenderingOptions options, float scaleX, float scaleY)
```

Visszaad egy Thumbnail Image objektumot az összes diához egyéni méretezéssel.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Tiff beállítások. |
| scaleX | float | Az x-tengelyen alkalmazott méretezés értéke. |
| scaleY | float | Az y-tengelyen alkalmazott méretezés értéke. |

**Visszatérési érték:**
com.aspose.slides.IImage[] - Image objektumok.

### getImages(IRenderingOptions options, int[] slides, float scaleX, float scaleY) {#getImages-com.aspose.slides.IRenderingOptions-int---float-float-}
```
public final IImage[] getImages(IRenderingOptions options, int[] slides, float scaleX, float scaleY)
```

Visszaad egy Thumbnail Image objektumot a megadott diáknál egyéni méretezéssel.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Tiff beállítások. |
| slides | int[] | A diák pozícióit tartalmazó tömb, 1-től indulva. |
| scaleX | float | Az x-tengelyen alkalmazott méretezés értéke. |
| scaleY | float | Az y-tengelyen alkalmazott méretezés értéke. |

**Visszatérési érték:**
com.aspose.slides.IImage[] - Image objektumok.

### getImages(IRenderingOptions options, Size imageSize) {#getImages-com.aspose.slides.IRenderingOptions-com.aspose.slides.android.Size-}
```
public final IImage[] getImages(IRenderingOptions options, Size imageSize)
```

Visszaad egy Thumbnail Image objektumot az összes diához megadott mérettel.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Tiff beállítások. |
| imageSize | [Size](../../com.aspose.slides.android/size) | A létrehozandó kép mérete. |

**Visszatérési érték:**
com.aspose.slides.IImage[] - Image objektumok.

### getImages(IRenderingOptions options, int[] slides, Size imageSize) {#getImages-com.aspose.slides.IRenderingOptions-int---com.aspose.slides.android.Size-}
```
public final IImage[] getImages(IRenderingOptions options, int[] slides, Size imageSize)
```

Visszaad egy Thumbnail Image objektumot a megadott diáknál megadott mérettel.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Tiff beállítások. |
| slides | int[] | A diák pozícióit tartalmazó tömb, 1-től indulva. |
| imageSize | [Size](../../com.aspose.slides.android/size) | A létrehozandó kép mérete. |

**Visszatérési érték:**
com.aspose.slides.IImage[] - Image objektumok.

### save(String fname, int[] slides, int format) {#save-java.lang.String-int---int-}
```
public final void save(String fname, int[] slides, int format)
```

A megadott diákat a prezentációból a megadott formátumú fájlba menti, megtartva az oldalszámot.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| fname | java.lang.String | A létrehozott fájl útvonala. |
| slides | int[] | A diák pozícióit tartalmazó tömb, 1-től indulva. |
| format | int | A exportált adatok formátuma. |

### save(String fname, int[] slides, int format, ISaveOptions options) {#save-java.lang.String-int---int-com.aspose.slides.ISaveOptions-}
```
public final void save(String fname, int[] slides, int format, ISaveOptions options)
```

A megadott diákat a prezentációból a megadott formátumú fájlba menti, megtartva az oldalszámot.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| fname | java.lang.String | A létrehozott fájl útvonala. |
| slides | int[] | A diák pozícióit tartalmazó tömb, 1-től indulva. |
| format | int | A exportált adatok formátuma. |
| options | [ISaveOptions](../../com.aspose.slides/isaveoptions) | További formátum beállítások. |

### save(OutputStream stream, int[] slides, int format) {#save-java.io.OutputStream-int---int-}
```
public final void save(OutputStream stream, int[] slides, int format)
```

A megadott diákat a prezentációból a megadott formátumú adatfolyamba menti, megtartva az oldalszámot.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| stream | java.io.OutputStream | Kimeneti adatfolyam. |
| slides | int[] | A diák pozícióit tartalmazó tömb, 1-től indulva. |
| format | int | A exportált adatok formátuma. |

### save(OutputStream stream, int[] slides, int format, ISaveOptions options) {#save-java.io.OutputStream-int---int-com.aspose.slides.ISaveOptions-}
```
public final void save(OutputStream stream, int[] slides, int format, ISaveOptions options)
```

A megadott diákat a prezentációból a megadott formátumú adatfolyamba menti, megtartva az oldalszámot.

--------------------

> ```
> The following example shows how to convert PowerPoint to PNG.
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      for (int index = 0; index < pres.getSlides().size(); index++) {
>          ISlide slide = pres.getSlides().get_Item(index);
>          FileOutputStream out = new FileOutputStream("slide_" + index + ".png");
>          slide.getThumbnail().compress(android.graphics.Bitmap.CompressFormat.PNG, 100, out);
>          out.flush();
>          out.close();
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
>          FileOutputStream out = new FileOutputStream("slide_" + index + ".png");
>          slide.getThumbnail(scaleX, scaleY).compress(android.graphics.Bitmap.CompressFormat.PNG, 100, out);
>          out.flush();
>          out.close();
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
>      com.aspose.slides.android.Size size = new com.aspose.slides.android.Size(960, 720);
>      for (int index = 0; index < pres.getSlides().size(); index++) {
>          ISlide slide = pres.getSlides().get_Item(index);
>          FileOutputStream out = new FileOutputStream("slide_" + index + ".png");
>          slide.getThumbnail(size).compress(android.graphics.Bitmap.CompressFormat.PNG, 100, out);
>          out.flush();
>          out.close();
>      }
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| stream | java.io.OutputStream | Kimeneti adatfolyam. |
| slides | int[] | A diák pozícióit tartalmazó tömb, 1-től indulva. |
| format | int | A exportált adatok formátuma. |
| options | [ISaveOptions](../../com.aspose.slides/isaveoptions) | További formátum beállítások. |

### joinPortionsWithSameFormatting() {#joinPortionsWithSameFormatting--}
```
public final void joinPortionsWithSameFormatting()
```

Összevonja az azonos formázású futamokat minden bekezdésben, minden alkalmas alakzatban, minden dián.

### dispose() {#dispose--}
```
public final void dispose()
```

Felszabadítja a Presentation objektum által használt összes erőforrást.

### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

Visszaadja a szöveg szülő prezentációját. Csak olvasható [IPresentation](../../com.aspose.slides/ipresentation).

**Visszatérési érték:**
[IPresentation](../../com.aspose.slides/ipresentation)

### highlightText(String text, Integer highlightColor) {#highlightText-java.lang.String-java.lang.Integer-}
```
public final void highlightText(String text, Integer highlightColor)
```

Kiemeli a mintaszöveg összes előfordulását a megadott színnel.

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
| highlightColor | java.lang.Integer | A szöveg kiemelésének színe. |

### highlightText(String text, Integer highlightColor, ITextSearchOptions options, IFindResultCallback callback) {#highlightText-java.lang.String-java.lang.Integer-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-}
```
public final void highlightText(String text, Integer highlightColor, ITextSearchOptions options, IFindResultCallback callback)
```

Kiemeli a mintaszöveg összes előfordulását a megadott színnel.

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
| highlightColor | java.lang.Integer | A szöveg kiemelésének színe. |
| options | [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions) | Szövegkeresési beállítások [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions). |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | A keresési eredmények fogadásáért felelős callback objektum [IFindResultCallback](../../com.aspose.slides/ifindresultcallback). |

### highlightRegex(Pattern regex, Integer highlightColor, IFindResultCallback callback) {#highlightRegex-java.util.regex.Pattern-java.lang.Integer-com.aspose.slides.IFindResultCallback-}
```
public final void highlightRegex(Pattern regex, Integer highlightColor, IFindResultCallback callback)
```

Kiemeli a reguláris kifejezés összes előfordulását a megadott színnel.

--------------------

> ```
> A következő kódminta megmutatja, hogyan lehet szöveget kiemelni egy PowerPoint prezentációban reguláris kifejezés használatával.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      Pattern regex = Pattern.compile("\\b[^\\s]{10,}\\b");
>      // minden 10 vagy több karakterből álló szó kiemelése
>      presentation.highlightRegex(regex, Color.BLUE, null);
>      presentation.save("SomePresentation-out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| regex | java.util.regex.Pattern | A reguláris kifejezés, amelynek előfordulásait ki kell emelni. |
| highlightColor | java.lang.Integer | A szöveg kiemelésének színe. |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | A keresési eredmények fogadásáért felelős callback objektum [IFindResultCallback](../../com.aspose.slides/ifindresultcallback). |

### replaceText(String oldText, String newText, ITextSearchOptions options, IFindResultCallback callback) {#replaceText-java.lang.String-java.lang.String-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-}
```
public final void replaceText(String oldText, String newText, ITextSearchOptions options, IFindResultCallback callback)
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
| oldText | java.lang.String | A cserélendő karakterlánc. |
| newText | java.lang.String | A karakterlánc, amelyre a cserét végzi. |
| options | [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions) | Szövegkeresési beállítások [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions). |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | A keresési eredmények fogadásáért felelős callback objektum [IFindResultCallback](../../com.aspose.slides/ifindresultcallback). |

### replaceRegex(Pattern regex, String newText, IFindResultCallback callback) {#replaceRegex-java.util.regex.Pattern-java.lang.String-com.aspose.slides.IFindResultCallback-}
```
public final void replaceRegex(Pattern regex, String newText, IFindResultCallback callback)
```

Lecseréli a reguláris kifejezés összes előfordulását a megadott karakterláncra.

--------------------

> ```
> The following code sample shows how to replace text using regular expression with the specified string.
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      Pattern regex = Pattern.compile("\\b[^\\s]{10,}\\b");
>      // Cserélje az összes 10 vagy több szimbólumú szót '***'-ra
>      presentation.replaceRegex(regex, "***", null);
>      presentation.save("SomePresentation-out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| regex | java.util.regex.Pattern | A reguláris kifejezés, amelynek előfordulásait cserélni kell. |
| newText | java.lang.String | A karakterlánc, amelyre a cserét végzi. |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | A keresési eredmények fogadásáért felelős callback objektum [IFindResultCallback](../../com.aspose.slides/ifindresultcallback). |