---
title: Presentation
second_title: Aspose.Slides for Java API-referencia
description: Microsoft PowerPoint prezentációt képvisel.
type: docs
url: /hu/com.aspose.slides/presentation/
---
**Öröklés:**
java.lang.Object

**Összes megvalósított interfész:**
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
>      // Lekérdezi az első diát
>      ISlide slide = pres.getSlides().get_Item(0);
>      // Sor típusú autóforma hozzáadása
>      slide.getShapes().addAutoShape(ShapeType.Line, 50, 150, 300, 0);
>      // Mentse a prezentációfájlt.
>      pres.save("NewPresentation_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>   
>   The following example shows how to open and save Presentation.
>   
>  // Töltsön be bármely támogatott fájlt a Presentation-be, pl. ppt, pptx, odp stb.
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
| [Presentation()](#Presentation--) | Ez a konstruktor új prezentációt hoz létre az alapoktól. |
| [Presentation(LoadOptions loadOptions)](#Presentation-com.aspose.slides.LoadOptions-) | Ez a konstruktor új prezentációt hoz létre az alapoktól. |
| [Presentation(InputStream stream)](#Presentation-java.io.InputStream-) | Ez a konstruktor az elsődleges mechanizmus egy meglévő Presentation beolvasásához. |
| [Presentation(InputStream stream, LoadOptions loadOptions)](#Presentation-java.io.InputStream-com.aspose.slides.LoadOptions-) | Ez a konstruktor az elsődleges mechanizmus egy meglévő Presentation beolvasásához. |
| [Presentation(String file)](#Presentation-java.lang.String-) | Ez a konstruktor egy forrásfájl útvonalat kap, amelyből a Presentation tartalma beolvasásra kerül. |
| [Presentation(String file, LoadOptions loadOptions)](#Presentation-java.lang.String-com.aspose.slides.LoadOptions-) | Ez a konstruktor egy forrásfájl útvonalat kap, amelyből a Presentation tartalma beolvasásra kerül. |

## Metódusok

| Metódus | Leírás |
| --- | --- |
| [getCurrentDateTime()](#getCurrentDateTime--) | Visszaadja vagy beállítja a dátumot és időt, amely a datetime mezők tartalmát helyettesíti. |
| [setCurrentDateTime(Date value)](#setCurrentDateTime-java.util.Date-) | Visszaadja vagy beállítja a dátumot és időt, amely a datetime mezők tartalmát helyettesíti. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | Visszaadja a tényleges HeaderFooter kezelőt. |
| [getProtectionManager()](#getProtectionManager--) | Lekéri ennek a prezentációnak a jogosultságkezelőjét. |
| [getSlides()](#getSlides--) | Visszaad egy listát az összes prezentációban definiált diáról. |
| [getSections()](#getSections--) | Visszaad egy listát az összes prezentációban definiált dia szekcióról. |
| [getSlideSize()](#getSlideSize--) | Visszaadja a dia méret objektumot. |
| [getNotesSize()](#getNotesSize--) | Visszaadja a jegyzet dia méret objektumot. |
| [getLayoutSlides()](#getLayoutSlides--) | Visszaad egy listát az összes prezentációban definiált elrendezési diákról. |
| [getMasters()](#getMasters--) | Visszaad egy listát az összes prezentációban definiált fő diákról. |
| [getMasterNotesSlideManager()](#getMasterNotesSlideManager--) | Visszaadja a jegyzet fő kezelőt. |
| [getMasterHandoutSlideManager()](#getMasterHandoutSlideManager--) | Visszaadja a kézjegyzet fő kezelőt. |
| [getFontsManager()](#getFontsManager--) | Visszaadja a betűkészlet kezelőt. |
| [getDefaultTextStyle()](#getDefaultTextStyle--) | Visszaadja az alakzatok alapértelmezett szövegstílusát. |
| [getCommentAuthors()](#getCommentAuthors--) | Visszaadja a megjegyzés szerzők gyűjteményét. |
| [getDocumentProperties()](#getDocumentProperties--) | Visszaadja a DocumentProperties objektumot, amely szabványos és egyedi dokumentum tulajdonságokat tartalmaz. |
| [getImages()](#getImages--) | Visszaadja a prezentációban szereplő összes kép gyűjteményét. |
| [getAudios()](#getAudios--) | Visszaadja a prezentációban beágyazott összes hangfájl gyűjteményét. |
| [getVideos()](#getVideos--) | Visszaadja a prezentációban beágyazott összes videofájl gyűjteményét. |
| [getSlideShowSettings()](#getSlideShowSettings--) | Visszaadja a prezentáció diavetítés beállításait. |
| [getDigitalSignatures()](#getDigitalSignatures--) | Visszaadja a prezentáció aláírásához használt aláírások gyűjteményét. |
| [getCustomData()](#getCustomData--) | Visszaadja a prezentáció egyedi adatait. |
| [getAllCustomXmlParts()](#getAllCustomXmlParts--) | Visszaadja a prezentáció összes egyedi adat részét. |
| [getVbaProject()](#getVbaProject--) | Lekéri vagy beállítja a VBA projektet a prezentáció makróival. |
| [setVbaProject(IVbaProject value)](#setVbaProject-com.aspose.slides.IVbaProject-) | Lekéri vagy beállítja a VBA projektet a prezentáció makróival. |
| [getHyperlinkQueries()](#getHyperlinkQueries--) | Egyszerű hozzáférést biztosít az összes hiperhivatkozáshoz, amely a prezentáció diáin található (nem a fő, elrendezési vagy jegyzet diáknál). |
| [getViewProperties()](#getViewProperties--) | Lekéri a prezentáció szintű nézeti tulajdonságokat. |
| [getFirstSlideNumber()](#getFirstSlideNumber--) | A prezentáció első dia számát reprezentálja |
| [setFirstSlideNumber(int value)](#setFirstSlideNumber-int-) | A prezentáció első dia számát reprezentálja |
| [getSensitivityLabels()](#getSensitivityLabels--) | Visszaadja a prezentáció dokumentumra alkalmazott érzékenységi címkék gyűjteményét. |
| [getSlideById(long id)](#getSlideById-long-) | Visszaad egy Slide, MasterSlide vagy LayoutSlide elemet azonosító alapján. |
| [getSourceFormat()](#getSourceFormat--) | Visszaad információt arról, milyen formátumból lett betöltve a prezentáció. |
| [getMasterTheme()](#getMasterTheme--) | Visszaadja a fő témát. |
| [save(String fname, int format)](#save-java.lang.String-int-) | Elmenti a prezentáció összes diáját a megadott formátumú fájlba. |
| [save(OutputStream stream, int format)](#save-java.io.OutputStream-int-) | Elmenti a prezentáció összes diáját a megadott formátumú adatfolyamra. |
| [save(String fname, int format, ISaveOptions options)](#save-java.lang.String-int-com.aspose.slides.ISaveOptions-) | Elmenti a prezentáció összes diáját a megadott formátumú fájlba, további beállításokkal. |
| [save(OutputStream stream, int format, ISaveOptions options)](#save-java.io.OutputStream-int-com.aspose.slides.ISaveOptions-) | Elmenti a prezentáció összes diáját a megadott formátumú adatfolyamra, további beállításokkal. |
| [save(IXamlOptions options)](#save-com.aspose.slides.IXamlOptions-) | Elmenti a prezentáció összes diáját egy XAML jelölést reprezentáló fájlok készletébe. |
| [getImages(IRenderingOptions options)](#getImages-com.aspose.slides.IRenderingOptions-) | Visszaad egy Image objektumot a prezentáció minden diájához. |
| [getImages(IRenderingOptions options, int[] slides)](#getImages-com.aspose.slides.IRenderingOptions-int---) | Visszaad egy Miniatűr Image objektumot a megadott diákhoz a prezentációban. |
| [getImages(IRenderingOptions options, float scaleX, float scaleY)](#getImages-com.aspose.slides.IRenderingOptions-float-float-) | Visszaad egy Miniatűr Image objektumot a prezentáció összes diájához egyéni méretezéssel. |
| [getImages(IRenderingOptions options, int[] slides, float scaleX, float scaleY)](#getImages-com.aspose.slides.IRenderingOptions-int---float-float-) | Visszaad egy Miniatűr Image objektumot a megadott diákhoz a prezentációban egyéni méretezéssel. |
| [getImages(IRenderingOptions options, Dimension imageSize)](#getImages-com.aspose.slides.IRenderingOptions-java.awt.Dimension-) | Visszaad egy Miniatűr Image objektumot a prezentáció összes diájához a megadott mérettel. |
| [getImages(IRenderingOptions options, int[] slides, Dimension imageSize)](#getImages-com.aspose.slides.IRenderingOptions-int---java.awt.Dimension-) | Visszaad egy Miniatűr Image objektumot a megadott diákhoz a prezentációban a megadott mérettel. |
| [save(String fname, int[] slides, int format)](#save-java.lang.String-int---int-) | Elmenti a megadott diákat a prezentációból egy fájlba a megadott formátummal, az oldalszám megtartásával. |
| [save(String fname, int[] slides, int format, ISaveOptions options)](#save-java.lang.String-int---int-com.aspose.slides.ISaveOptions-) | Elmenti a megadott diákat a prezentációból egy fájlba a megadott formátummal, az oldalszám megtartásával. |
| [save(OutputStream stream, int[] slides, int format)](#save-java.io.OutputStream-int---int-) | Elmenti a megadott diákat a prezentációból egy adatfolyamra a megadott formátummal, az oldalszám megtartásával. |
| [save(OutputStream stream, int[] slides, int format, ISaveOptions options)](#save-java.io.OutputStream-int---int-com.aspose.slides.ISaveOptions-) | Elmenti a megadott diákat a prezentációból egy adatfolyamra a megadott formátummal, az oldalszám megtartásával. |
| [joinPortionsWithSameFormatting()](#joinPortionsWithSameFormatting--) | Egyesíti a ugyanazt a formázást tartalmazó futamokat az összes bekezdésben minden elfogadható alakzatban minden dián. |
| [dispose()](#dispose--) | Felszabadítja az ebben a Presentation objektumban használt összes erőforrást. |
| [getPresentation()](#getPresentation--) | Visszaadja a szöveg szülő prezentációját. |
| [highlightText(String text, Color highlightColor)](#highlightText-java.lang.String-java.awt.Color-) | Kiemeli a mintaszöveg összes találatát a megadott színnel. |
| [highlightText(String text, Color highlightColor, ITextSearchOptions options, IFindResultCallback callback)](#highlightText-java.lang.String-java.awt.Color-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-) | Kiemeli a mintaszöveg összes találatát a megadott színnel. |
| [highlightRegex(Pattern regex, Color highlightColor, IFindResultCallback callback)](#highlightRegex-java.util.regex.Pattern-java.awt.Color-com.aspose.slides.IFindResultCallback-) | Kiemeli a reguláris kifejezés összes találatát a megadott színnel. |
| [replaceText(String oldText, String newText, ITextSearchOptions options, IFindResultCallback callback)](#replaceText-java.lang.String-java.lang.String-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-) | Lecseréli a megadott szöveg összes előfordulását egy másik megadott szövegre. |
| [replaceRegex(Pattern regex, String newText, IFindResultCallback callback)](#replaceRegex-java.util.regex.Pattern-java.lang.String-com.aspose.slides.IFindResultCallback-) | Lecseréli a reguláris kifejezés összes találatát a megadott karakterláncra. |

### Presentation() {#Presentation--}
```
public Presentation()
```

Ez a konstruktor új prezentációt hoz létre az alapoktól. A létrehozott prezentáció egy üres diát tartalmaz.

### Presentation(LoadOptions loadOptions) {#Presentation-com.aspose.slides.LoadOptions-}
```
public Presentation(LoadOptions loadOptions)
```

Ez a konstruktor új prezentációt hoz létre az alapoktól. A létrehozott prezentáció egy üres diát tartalmaz.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| loadOptions | [LoadOptions](../../com.aspose.slides/loadoptions) | További betöltési beállítások. |

### Presentation(InputStream stream) {#Presentation-java.io.InputStream-}
```
public Presentation(InputStream stream)
```

Ez a konstruktor az elsődleges mechanizmus egy meglévő Presentation beolvasásához.

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

Ez a konstruktor az elsődleges mechanizmus egy meglévő Presentation beolvasásához.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| stream | java.io.InputStream | Bemeneti adatfolyam. |
| loadOptions | [LoadOptions](../../com.aspose.slides/loadoptions) | További betöltési beállítások. |

### Presentation(String file) {#Presentation-java.lang.String-}
```
public Presentation(String file)
```

Ez a konstruktor egy forrásfájl útvonalat kap, amelyből a Presentation tartalma beolvasásra kerül.

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

Ez a konstruktor egy forrásfájl útvonalat kap, amelyből a Presentation tartalma beolvasásra kerül.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| file | java.lang.String | Bemeneti fájl. |
| loadOptions | [LoadOptions](../../com.aspose.slides/loadoptions) | További betöltési beállítások. |

### getCurrentDateTime() {#getCurrentDateTime--}
```
public final Date getCurrentDateTime()
```

Visszaadja vagy beállítja a dátumot és időt, amely a datetime mezők tartalmát helyettesíti. Alapértelmezés szerint a jelen Presentation objektum létrehozásának időpontja. Olvasás/írás java.util.Date.

**Visszatér:**
java.util.Date

### setCurrentDateTime(Date value) {#setCurrentDateTime-java.util.Date-}
```
public final void setCurrentDateTime(Date value)
```

Visszaadja vagy beállítja a dátumot és időt, amely a datetime mezők tartalmát helyettesíti. Alapértelmezés szerint a jelen Presentation objektum létrehozásának időpontja. Olvasás/írás java.util.Date.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | java.util.Date |  |

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Visszaadja a Parent_Immediate objektumot. Csak olvasható IDOMObject.

**Visszatér:**
com.aspose.slides.IDOMObject

### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public final IPresentationHeaderFooterManager getHeaderFooterManager()
```

Visszaadja a tényleges HeaderFooter kezelőt. Csak olvasható [IPresentationHeaderFooterManager](../../com.aspose.slides/ipresentationheaderfootermanager).

--------------------

> ```
> The following example shows how to set footer visibility inside Slide of PowerPoint Presentation.
>  
>  Presentation pres = new Presentation("presentation.ppt");
>  try
>  {
>      IBaseSlideHeaderFooterManager headerFooterManager = pres.getSlides().get_Item(0).getHeaderFooterManager();
>      if (!headerFooterManager.isFooterVisible()) // Az IsFooterVisible tulajdonság arra szolgál, hogy jelezze, ha a dián nincs lábléc helyőrző.
>      {
>          headerFooterManager.setFooterVisibility(true); // A SetFooterVisibility metódus arra szolgál, hogy lábléc helyőrzőt láthatóvá tegye a dián.
>      }
>      if (!headerFooterManager.isSlideNumberVisible()) // Az IsSlideNumberVisible tulajdonság arra szolgál, hogy jelezze, ha a dián nincs oldalszám helyőrző.
>      {
>          headerFooterManager.setSlideNumberVisibility(true); // A SetSlideNumberVisibility metódus arra szolgál, hogy láthatóvá tegye a dián az oldalszám helyőrzőt.
>      }
>      if (!headerFooterManager.isDateTimeVisible()) // Az IsDateTimeVisible tulajdonság arra szolgál, hogy jelezze, ha a dián nincs dátum-idő helyőrző.
>      {
>          headerFooterManager.setDateTimeVisibility(true); // A SetFooterVisibility metódus arra szolgál, hogy láthatóvá tegye a dián a dátum-idő helyőrzőt.
>      }
>      headerFooterManager.setFooterText("Footer text"); // A SetFooterText metódus a dián lévő lábléc helyőrző szövegének beállítására szolgál.
>      headerFooterManager.setDateTimeText("Date and time text"); // A SetDateTimeText metódus a dián lévő dátum-idő helyőrző szövegének beállítására szolgál.
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
>      headerFooterManager.setFooterAndChildFootersVisibility(true); // A SetFooterAndChildFootersVisibility metódus arra szolgál, hogy a mester dia és az összes gyermek lábléc helyőrző látható legyen.
>      headerFooterManager.setSlideNumberAndChildSlideNumbersVisibility(true); // A SetSlideNumberAndChildSlideNumbersVisibility metódus arra szolgál, hogy a mester dia és az összes gyermek oldalszám helyőrző látható legyen.
>      headerFooterManager.setDateTimeAndChildDateTimesVisibility(true); // A SetDateTimeAndChildDateTimesVisibility metódus arra szolgál, hogy a mester dia és az összes gyermek dátum-idő helyőrző látható legyen.
> 
>      headerFooterManager.setFooterAndChildFootersText("Footer text"); // A SetFooterAndChildFootersText metódus a mester dia és az összes gyermek lábléc helyőrző szövegének beállítására szolgál.
>      headerFooterManager.setDateTimeAndChildDateTimesText("Date and time text"); // A SetDateTimeAndChildDateTimesText metódus a mester dia és az összes gyermek dátum-idő helyőrző szövegének beállítására szolgál.
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

Lekéri ennek a prezentációnak a jogosultságkezelőjét. Csak olvasható [IProtectionManager](../../com.aspose.slides/iprotectionmanager).

**Visszatér:**
[IProtectionManager](../../com.aspose.slides/iprotectionmanager)

### getSlides() {#getSlides--}
```
public final ISlideCollection getSlides()
```

Visszaad egy listát az összes prezentációban definiált diáról. Csak olvasható [ISlideCollection](../../com.aspose.slides/islidecollection).

--------------------

> ```
> The following example shows how to set slides' background color of PowerPoint Presentation.
>  
>  // Példányosítja a Presentation osztályt, amely a prezentációfájlt reprezentálja
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
>  // Példányosítja a Presentation osztályt, amely a prezentációfájlt reprezentálja
>  Presentation pres = new Presentation("SetImageAsBackground.pptx");
>  try {
>      // A háttér beállítása képpel
>      pres.getSlides().get_Item(0).getBackground().setType(BackgroundType.OwnBackground);
>      pres.getSlides().get_Item(0).getBackground().getFillFormat().setFillType(FillType.Picture);
>      pres.getSlides().get_Item(0).getBackground().getFillFormat().getPictureFillFormat().setPictureFillMode(PictureFillMode.Stretch);
>      // Beállítja a képet
>      BufferedImage img = ImageIO.read(new File("Tulips.jpg"));
>      // A képet hozzáadja a prezentáció képkollekciójához
>      IPPImage imgx = pres.getImages().addImage(img);
>      pres.getSlides().get_Item(0).getBackground().getFillFormat().getPictureFillFormat().getPicture().setImage(imgx);
>      // Mentés a lemezre
>      pres.save("ContentBG_Img_out.pptx", SaveFormat.Pptx);
>  } catch (IOException e) { }
>  finally
>  {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to add slide transition Presentation.
>  
>  // Példányosítja a Presentation osztályt a forrásprezentáció betöltéséhez
>  Presentation pres = new Presentation("AccessSlides.pptx");
>  try
>  {
>      // Kör típusú átmenetet alkalmaz a 1. dián
>      pres.getSlides().get_Item(0).getSlideShowTransition().setType(TransitionType.Circle);
>      // Fűrész típusú átmenetet alkalmaz a 2. dián
>      pres.getSlides().get_Item(1).getSlideShowTransition().setType(TransitionType.Comb);
>      // Mentés a lemezre
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
>      // Kör típusú átmenetet alkalmaz a 1. dián
>      pres.getSlides().get_Item(0).getSlideShowTransition().setType(TransitionType.Circle);
>      // Beállítja az átmenet időtartamát 3 másodpercre
>      pres.getSlides().get_Item(0).getSlideShowTransition().setAdvanceOnClick(true);
>      pres.getSlides().get_Item(0).getSlideShowTransition().setAdvanceAfterTime(3000);
>      // Fűrész típusú átmenetet alkalmaz a 2. dián
>      pres.getSlides().get_Item(1).getSlideShowTransition().setType(TransitionType.Comb);
>      // Beállítja az átmenet időtartamát 5 másodpercre
>      pres.getSlides().get_Item(1).getSlideShowTransition().setAdvanceOnClick(true);
>      pres.getSlides().get_Item(1).getSlideShowTransition().setAdvanceAfterTime(5000);
>      // Nagyítás típusú átmenetet alkalmaz a 3. dián
>      pres.getSlides().get_Item(2).getSlideShowTransition().setType(TransitionType.Zoom);
>      // Beállítja az átmenet időtartamát 7 másodpercre
>      pres.getSlides().get_Item(2).getSlideShowTransition().setAdvanceOnClick(true);
>      pres.getSlides().get_Item(2).getSlideShowTransition().setAdvanceAfterTime(7000);
>      // Mentés a lemezre
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

Visszaad egy listát az összes prezentációban definiált dia szekcióról. Csak olvasható [ISectionCollection](../../com.aspose.slides/isectioncollection).

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
>      // a section1 a newSlide2-nél fejeződik be, és utána a section2 kezdődik
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

Visszaadja a dia méret objektumot. Csak olvasható [ISlideSize](../../com.aspose.slides/islidesize).

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
>          // Beállítja a generált prezentációk dia méretét a forráséval megegyezőre
>          presentation.getSlideSize().setSize(540, 720, SlideSizeScaleType.EnsureFit); // A SetSize metódust a dia méretének beállítására használják, a tartalom méretezésével a megfelelő illeszkedés érdekében
>          presentation.getSlideSize().setSize(SlideSizeType.A4Paper, SlideSizeScaleType.Maximize); // A SetSize metódust a dia méretének beállítására használják, a tartalom méretének maximalizálásával
>          // A prezentáció mentése a lemezre
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

**Visszatér:**
[ISlideSize](../../com.aspose.slides/islidesize)

### getNotesSize() {#getNotesSize--}
```
public final INotesSize getNotesSize()
```

Visszaadja a jegyzet dia méret objektumot. Csak olvasható [INotesSize](../../com.aspose.slides/inotessize).

**Visszatér:**
[INotesSize](../../com.aspose.slides/inotessize)

### getLayoutSlides() {#getLayoutSlides--}
```
public final IGlobalLayoutSlideCollection getLayoutSlides()
```

Visszaad egy listát az összes prezentációban definiált elrendezési diákról. Csak olvasható [IGlobalLayoutSlideCollection](../../com.aspose.slides/igloballayoutslidecollection).

--------------------

A IMasterSlide.LayoutSlides tulajdonság segítségével hozzáférhet alternatív API-hoz az elrendezési diák hozzáadásához/ beszúrásához/ eltávolításához/ klónozásához.

**Visszatér:**
[IGlobalLayoutSlideCollection](../../com.aspose.slides/igloballayoutslidecollection)

### getMasters() {#getMasters--}
```
public final IMasterSlideCollection getMasters()
```

Visszaad egy listát az összes prezentációban definiált fő diákról. Csak olvasható [IMasterSlideCollection](../../com.aspose.slides/imasterslidecollection).

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
>  // Példányosítja a Presentation osztályt, amely a prezentációfájlt reprezentálja
>  Presentation pres = new Presentation();
>  try
>  {
>      // Beállítja a Master ISlide háttérszínét erdőzöldre
>      pres.getMasters().get_Item(0).getBackground().setType(BackgroundType.OwnBackground);
>      pres.getMasters().get_Item(0).getBackground().getFillFormat().setFillType(FillType.Solid);
>      pres.getMasters().get_Item(0).getBackground().getFillFormat().getSolidFillColor().setColor(Color.GREEN);
>      // Mentés a lemezre
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
>      // Megpróbálja a diatervezeti típust keresni
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
>          // A prezentációfájl csak Üres és Egyedi elrendezési típust tartalmaz.
>          // De az Egyedi típusú elrendezési diák különböző dia nevekkel rendelkeznek,
>          // például "Cím", "Cím és tartalom", stb. És ezek a nevek használhatók
>          // elrendezési dia kiválasztásához.
>          // Továbbá lehetséges a helyőrző alakzat típusok halmazát használni. Például,
>          // a cím dia csak Cím helyőrző típust tartalmazzon, stb.
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
>      // Üres dia hozzáadása a hozzáadott elrendezési diával
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

Visszaadja a jegyzet fő kezelőt. Csak olvasható [IMasterNotesSlideManager](../../com.aspose.slides/imasternotesslidemanager).

**Visszatér:**
[IMasterNotesSlideManager](../../com.aspose.slides/imasternotesslidemanager)

### getMasterHandoutSlideManager() {#getMasterHandoutSlideManager--}
```
public final IMasterHandoutSlideManager getMasterHandoutSlideManager()
```

Visszaadja a kézjegyzet fő kezelőt. Csak olvasható [IMasterHandoutSlideManager](../../com.aspose.slides/imasterhandoutslidemanager).

**Visszatér:**
[IMasterHandoutSlideManager](../../com.aspose.slides/imasterhandoutslidemanager)

### getFontsManager() {#getFontsManager--}
```
public final IFontsManager getFontsManager()
```

Visszaadja a betűkészlet kezelőt. Csak olvasható [IFontsManager](../../com.aspose.slides/ifontsmanager).

--------------------

> ```
> The following example shows how to add embedded fonts to PowerPoint Presentation.
>  
>  // Betölti a prezentációt
>  Presentation pres = new Presentation("Fonts.pptx");
>  try {
>      // Betölti a helyettesítendő forrásbetűtípust
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

Visszaadja az alakzatok alapértelmezett szövegstílusát. Csak olvasható [ITextStyle](../../com.aspose.slides/itextstyle).

**Visszatér:**
[ITextStyle](../../com.aspose.slides/itextstyle)

### getCommentAuthors() {#getCommentAuthors--}
```
public final ICommentAuthorCollection getCommentAuthors()
```

Visszaadja a megjegyzés szerzők gyűjteményét. Csak olvasható [ICommentAuthorCollection](../../com.aspose.slides/icommentauthorcollection).

**Visszatér:**
[ICommentAuthorCollection](../../com.aspose.slides/icommentauthorcollection)

### getDocumentProperties() {#getDocumentProperties--}
```
public final IDocumentProperties getDocumentProperties()
```

Visszaadja a DocumentProperties objektumot, amely szabványos és egyedi dokumentum tulajdonságokat tartalmaz. Csak olvasható [IDocumentProperties](../../com.aspose.slides/idocumentproperties).

**Visszatér:**
[IDocumentProperties](../../com.aspose.slides/idocumentproperties)

### getImages() {#getImages--}
```
public 
```

Visszaadja a prezentációban szereplő összes kép gyűjteményét. Csak olvasható [IImageCollection](../../com.aspose.slides/iimagecollection).

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
>          // Adjunk hozzá egy képet a prezentációhoz – a KeepLocked viselkedést választjuk, mert
>          // nem szándékozunk hozzáférni a \"largeImage.png\" fájlhoz.
>          IPPImage img = pres.getImages().addImage(fip, LoadingStreamBehavior.KeepLocked);
>          pres.getSlides().get_Item(0).getShapes().addPictureFrame(ShapeType.Rectangle, 0, 0, 300, 200, img);
>          // Mentse a prezentációt. Egy nagy prezentáció kimeneti fájlja közben a memóriahasználat
>          // alacsony marad a pres objektum életciklusa során
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
>      // Képet ad hozzá a prezentációhoz
>      IPPImage image = pres.getImages().addImage(Files.readAllBytes(Paths.get("image.png")));
>      // Létrehozza a képkockát az 1. dián a korábban hozzáadott kép alapján
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

Visszaadja a prezentációban beágyazott összes hangfájl gyűjteményét. Csak olvasható [IAudioCollection](../../com.aspose.slides/iaudiocollection).

--------------------

> ```
> A következő példák bemutatják, hogyan lehet hiperhivatkozást hozzáadni egy audio fájlhoz.
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
Visszaadja a prezentációban beágyazott összes videofájl gyűjteményét. Csak olvasható [IVideoCollection](../../com.aspose.slides/ivideocollection).

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
>          // Adjunk hozzá egy képet a prezentációhoz – a KeepLocked viselkedést választjuk, mert
>          // NEM szándékozunk hozzáférni a "largeImage.png" fájlhoz.
>          IPPImage img = pres.getImages().addImage(fip, LoadingStreamBehavior.KeepLocked);
>          pres.getSlides().get_Item(0).getShapes().addPictureFrame(ShapeType.Rectangle, 0, 0, 300, 200, img);
>          // Mentés a prezentációhoz. Egy nagy prezentáció kiírása közben a memóriahasználat
>          // alacsony marad a pres objektum életciklusa során
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
>      // Képet ad hozzá a prezentációhoz
>      IPPImage image = pres.getImages().addImage(Files.readAllBytes(Paths.get("image.png")));
>      // Létrehozza a képkockát az 1. dián a korábban hozzáadott kép alapján
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
[IVideoCollection](../../com.aspose.slides/ivideocollection)
### getSlideShowSettings() {#getSlideShowSettings--}
```
public final SlideShowSettings getSlideShowSettings()
```


Visszaadja a prezentáció diavetítési beállításait.

**Visszatér:**
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


**Visszatér:**
[IDigitalSignatureCollection](../../com.aspose.slides/idigitalsignaturecollection)
### getCustomData() {#getCustomData--}
```
public final ICustomData getCustomData()
```


Visszaadja a prezentáció egyedi adatát. Csak olvasható [ICustomData](../../com.aspose.slides/icustomdata).

**Visszatér:**
[ICustomData](../../com.aspose.slides/icustomdata)
### getAllCustomXmlParts() {#getAllCustomXmlParts--}
```
public final ICustomXmlPart[] getAllCustomXmlParts()
```


Visszaadja a prezentáció összes egyedi XML részét. Csak olvasható ICustomXmlPart[].

--------------------

> ```
> The following examples show how to clear all custom xml parts from PowerPoint Presentation.
>  
>  Presentation pres = new Presentation("PresentationWithCustomXml.pptx");
>  try {
>      // Az összes egyéni XML rész iterálása
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


Visszaadja vagy beállítja a VBA projektet a prezentáció makróival. Olvasás/írás [IVbaProject](../../com.aspose.slides/ivbaproject).

**Visszatér:**
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


Könnyű hozzáférést biztosít az összes hiperhivatkozáshoz, amely az összes prezentációs diához tartozik (kivéve a mester-, elrendezés- és jegyzetdiákat). Csak olvasható [IHyperlinkQueries](../../com.aspose.slides/ihyperlinkqueries).

**Visszatér:**
[IHyperlinkQueries](../../com.aspose.slides/ihyperlinkqueries)
### getViewProperties() {#getViewProperties--}
```
public final IViewProperties getViewProperties()
```


Visszaadja a prezentációra vonatkozó nézeti tulajdonságokat. Csak olvasható [IViewProperties](../../com.aspose.slides/iviewproperties).

**Visszatér:**
[IViewProperties](../../com.aspose.slides/iviewproperties)
### getFirstSlideNumber() {#getFirstSlideNumber--}
```
public final int getFirstSlideNumber()
```


A prezentáció első diaszámát jelöli

**Visszatér:**
int
### setFirstSlideNumber(int value) {#setFirstSlideNumber-int-}
```
public final void setFirstSlideNumber(int value)
```


A prezentáció első diaszámát jelöli

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
>      // Kiírja a felhasznált címkéket
>      for (ISensitivityLabel sensitivityLabel : sensitivityLabels)
>          System.out.println("Label Id " + sensitivityLabel.getId() + " from Azure AD site " + sensitivityLabel.getSiteId());
> 
>      // Új címke hozzáadása
>      String labelIdString = "{xxxxxxxx-xxxx-xxxx-xxxx-xxxxxxxxxxxx}"; // A szabályzatból lekéri a szenzitivitási címke azonosítóját
>      UUID siteIdGuid = UUID.fromString("{xxxxxxxx-xxxx-xxxx-xxxx-xxxxxxxxxxxx}"); // A szabályzatból lekéri az Azure AD hely azonosítóját
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


Visszaad egy Slide, MasterSlide vagy LayoutSlide elemet azonosító alapján.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| id | long | Diának azonosítója. |

**Visszatér:**
[IBaseSlide](../../com.aspose.slides/ibaseslide) - IBaseSlide object.
### getSourceFormat() {#getSourceFormat--}
```
public final int getSourceFormat()
```


Visszaadja, hogy milyen formátumból lett betöltve a prezentáció. Csak olvasható [SourceFormat](../../com.aspose.slides/sourceformat).

**Visszatér:**
int
### getMasterTheme() {#getMasterTheme--}
```
public final IMasterTheme getMasterTheme()
```


Visszaadja a mester sablont. Csak olvasható [IMasterTheme](../../com.aspose.slides/imastertheme).

--------------------

> ```
> The following examples shows how to change a theme effect by altering parts of elements of PowerPoint Presentation.
>  
>  //Példányosít egy Presentation objektumot, amely egy prezentációfájlt képvisel
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


Ment minden diát egy fájlba a megadott formátummal.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| fname | java.lang.String | A létrehozandó fájl elérési útja. |
| format | int | Az exportált adat formátuma. |

### save(OutputStream stream, int format) {#save-java.io.OutputStream-int-}
```
public final void save(OutputStream stream, int format)
```


Ment minden diát egy folyamba a megadott formátummal.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| stream | java.io.OutputStream | Kimeneti folyam. |
| format | int | Az exportált adat formátuma. |

### save(String fname, int format, ISaveOptions options) {#save-java.lang.String-int-com.aspose.slides.ISaveOptions-}
```
public final void save(String fname, int format, ISaveOptions options)
```


Ment minden diát egy fájlba a megadott formátummal és további beállításokkal.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| fname | java.lang.String | A létrehozandó fájl elérési útja. |
| format | int | Az exportált adat formátuma. |
| options | [ISaveOptions](../../com.aspose.slides/isaveoptions) | További formátum beállítások. |

### save(OutputStream stream, int format, ISaveOptions options) {#save-java.io.OutputStream-int-com.aspose.slides.ISaveOptions-}
```
public final void save(OutputStream stream, int format, ISaveOptions options)
```


Ment minden diát egy folyamba a megadott formátummal és további beállításokkal.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| stream | java.io.OutputStream | Kimeneti folyam. |
| format | int | Az exportált adat formátuma. |
| options | [ISaveOptions](../../com.aspose.slides/isaveoptions) | További formátum beállítások. |

### save(IXamlOptions options) {#save-com.aspose.slides.IXamlOptions-}
```
public final void save(IXamlOptions options)
```


Ment minden diát egy fájlkészletbe, amely XAML jelölést tartalmaz.

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


Visszaadja az összes diáról a kép objektumokat.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Tiff beállítások. |

**Visszatér:**
com.aspose.slides.IImage[] - Kép objektumok.
### getImages(IRenderingOptions options, int[] slides) {#getImages-com.aspose.slides.IRenderingOptions-int---}
```
public final IImage[] getImages(IRenderingOptions options, int[] slides)
```


Visszaad egy bélyegkép-kép objektumot a megadott diákról.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Tiff beállítások. |
| slides | int[] | Diapozíciókat tartalmazó tömb, 1-től kezdve. |

**Visszatér:**
com.aspose.slides.IImage[] - Kép objektumok.
### getImages(IRenderingOptions options, float scaleX, float scaleY) {#getImages-com.aspose.slides.IRenderingOptions-float-float-}
```
public final IImage[] getImages(IRenderingOptions options, float scaleX, float scaleY)
```


Visszaad egy bélyegkép-kép objektumot az összes diáról egyéni méretezéssel.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Tiff beállítások. |
| scaleX | float | Az X-tengelyen való méretezés értéke. |
| scaleY | float | Az Y-tengelyen való méretezés értéke. |

**Visszatér:**
com.aspose.slides.IImage[] - Kép objektumok.
### getImages(IRenderingOptions options, int[] slides, float scaleX, float scaleY) {#getImages-com.aspose.slides.IRenderingOptions-int---float-float-}
```
public final IImage[] getImages(IRenderingOptions options, int[] slides, float scaleX, float scaleY)
```


Visszaad egy bélyegkép-kép objektumot a megadott diákról egyéni méretezéssel.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Tiff beállítások. |
| slides | int[] | Diapozíciókat tartalmazó tömb, 1-től kezdve. |
| scaleX | float | Az X-tengelyen való méretezés értéke. |
| scaleY | float | Az Y-tengelyen való méretezés értéke. |

**Visszatér:**
com.aspose.slides.IImage[] - Kép objektumok.
### getImages(IRenderingOptions options, Dimension imageSize) {#getImages-com.aspose.slides.IRenderingOptions-java.awt.Dimension-}
```
public final IImage[] getImages(IRenderingOptions options, Dimension imageSize)
```


Visszaad egy bélyegkép-kép objektumot az összes diáról a megadott mérettel.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Tiff beállítások. |
| imageSize | java.awt.Dimension | A létrehozandó kép mérete. |

**Visszatér:**
com.aspose.slides.IImage[] - Kép objektumok.
### getImages(IRenderingOptions options, int[] slides, Dimension imageSize) {#getImages-com.aspose.slides.IRenderingOptions-int---java.awt.Dimension-}
```
public final IImage[] getImages(IRenderingOptions options, int[] slides, Dimension imageSize)
```


Visszaad egy bélyegkép-kép objektumot a megadott diákról a megadott mérettel.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Tiff beállítások. |
| slides | int[] | Diapozíciókat tartalmazó tömb, 1-től kezdve. |
| imageSize | java.awt.Dimension | A létrehozandó kép mérete. |

**Visszatér:**
com.aspose.slides.IImage[] - Kép objektumok.
### save(String fname, int[] slides, int format) {#save-java.lang.String-int---int-}
```
public final void save(String fname, int[] slides, int format)
```


Ment a megadott diákat egy fájlba a megadott formátummal, oldal számmal együtt.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| fname | java.lang.String | A létrehozandó fájl elérési útja. |
| slides | int[] | Diapozíciókat tartalmazó tömb, 1-től kezdve. |
| format | int | Az exportált adat formátuma. |

### save(String fname, int[] slides, int format, ISaveOptions options) {#save-java.lang.String-int---int-com.aspose.slides.ISaveOptions-}
```
public final void save(String fname, int[] slides, int format, ISaveOptions options)
```


Ment a megadott diákat egy fájlba a megadott formátummal, oldal számmal együtt.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| fname | java.lang.String | A létrehozandó fájl elérési útja. |
| slides | int[] | Diapozíciókat tartalmazó tömb, 1-től kezdve. |
| format | int | Az exportált adat formátuma. |
| options | [ISaveOptions](../../com.aspose.slides/isaveoptions) | További formátum beállítások. |

### save(OutputStream stream, int[] slides, int format) {#save-java.io.OutputStream-int---int-}
```
public final void save(OutputStream stream, int[] slides, int format)
```


Ment a megadott diákat egy folyamba a megadott formátummal, oldal számmal együtt.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| stream | java.io.OutputStream | Kimeneti folyam. |
| slides | int[] | Diapozíciókat tartalmazó tömb, 1-től kezdve. |
| format | int | Az exportált adat formátuma. |

### save(OutputStream stream, int[] slides, int format, ISaveOptions options) {#save-java.io.OutputStream-int---int-com.aspose.slides.ISaveOptions-}
```
public final void save(OutputStream stream, int[] slides, int format, ISaveOptions options)
```


Ment a megadott diákat egy folyamba a megadott formátummal, oldal számmal együtt.

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
| stream | java.io.OutputStream | Kimeneti folyam. |
| slides | int[] | Diapozíciókat tartalmazó tömb, 1-től kezdve. |
| format | int | Az exportált adat formátuma. |
| options | [ISaveOptions](../../com.aspose.slides/isaveoptions) | További formátum beállítások. |

### joinPortionsWithSameFormatting() {#joinPortionsWithSameFormatting--}
```
public final void joinPortionsWithSameFormatting()
```


Összekapcsolja a hasonló formázású szakaszokat az összes bekezdésben az összes elfogadható alakzatban minden dián.

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

**Visszatér:**
[IPresentation](../../com.aspose.slides/ipresentation)
### highlightText(String text, Color highlightColor) {#highlightText-java.lang.String-java.awt.Color-}
```
public final void highlightText(String text, Color highlightColor)
```


Kiemeli a mintaszöveg összes előfordulását a megadott színnel.

--------------------

> ```
> The following code sample shows how to highlight text in a PowerPoint presentation.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      // kiemeli az összes különálló 'the' előfordulást
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


Kiemeli a mintaszöveg összes előfordulását a megadott színnel.

--------------------

> ```
> The following code sample shows how to highlight text in a PowerPoint presentation.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      TextSearchOptions textSearchOptions = new TextSearchOptions();
>      textSearchOptions.setWholeWordsOnly(true);
>      // kiemeli az összes különálló 'the' előfordulást
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
| options | [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions) | Szövegkeresési beállítások [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions). |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | A találatok fogadásához használt visszahívási objektum [IFindResultCallback](../../com.aspose.slides/ifindresultcallback). |

### highlightRegex(Pattern regex, Color highlightColor, IFindResultCallback callback) {#highlightRegex-java.util.regex.Pattern-java.awt.Color-com.aspose.slides.IFindResultCallback-}
```
public final void highlightRegex(Pattern regex, Color highlightColor, IFindResultCallback callback)
```


Kiemeli a reguláris kifejezés összes előfordulását a megadott színnel.

--------------------

> ```
> The following code sample shows how to highlight text in a PowerPoint Presentation using a regular expression.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      Pattern regex = Pattern.compile("\\b[^\\s]{10,}\\b");
>      // az összes 10 vagy több szimbólumú szó kiemelése
>      presentation.highlightRegex(regex, Color.BLUE, null);
>      presentation.save("SomePresentation-out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| regex | java.util.regex.Pattern | A reguláris kifejezés, amelynek megfelelő szöveget ki kell emelni. |
| highlightColor | java.awt.Color | A szöveg kiemeléséhez használt szín. |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | A találatok fogadásához használt visszahívási objektum [IFindResultCallback](../../com.aspose.slides/ifindresultcallback). |

### replaceText(String oldText, String newText, ITextSearchOptions options, IFindResultCallback callback) {#replaceText-java.lang.String-java.lang.String-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-}
```
public final void replaceText(String oldText, String newText, ITextSearchOptions options, IFindResultCallback callback)
```


A megadott szöveg összes előfordulását egy másik megadott szöveggel helyettesíti.

--------------------

> ```
> The following sample code shows how to replace one specified string with another specified string.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx")
>  try {
>      TextSearchOptions textSearchOptions = new TextSearchOptions();
>      textSearchOptions.setWholeWordsOnly(true);
>      // Cseréli az összes különálló 'the' előfordulást '***'-re
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
| newText | java.lang.String | Az a karakterlánc, amely a oldText összes előfordulását helyettesíti. |
| options | [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions) | Szövegkeresési beállítások [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions). |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | A visszahívási objektum a keresési eredmények fogadásához [IFindResultCallback](../../com.aspose.slides/ifindresultcallback). |

### replaceRegex(Pattern regex, String newText, IFindResultCallback callback) {#replaceRegex-java.util.regex.Pattern-java.lang.String-com.aspose.slides.IFindResultCallback-}
```
public final void replaceRegex(Pattern regex, String newText, IFindResultCallback callback)
```


A reguláris kifejezés minden egyezését a megadott karakterlánccal helyettesíti.

--------------------

> ```
> The following code sample shows how to replace text using regular expression with the specified string.
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      Pattern regex = Pattern.compile("\\b[^\\s]{10,}\\b");
>      // Az összes 10 vagy több szimbólumú szót '***'-re cseréli
>      presentation.replaceRegex(regex, "***", null);
>      presentation.save("SomePresentation-out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| regex | java.util.regex.Pattern | A reguláris kifejezés java.util.regex.Pattern a helyettesítendő karakterláncok lekéréséhez. |
| newText | java.lang.String | Az a karakterlánc, amely a helyettesítendő karakterláncok összes előfordulását helyettesíti. |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | A visszahívási objektum a keresési eredmények fogadásához [IFindResultCallback](../../com.aspose.slides/ifindresultcallback). |