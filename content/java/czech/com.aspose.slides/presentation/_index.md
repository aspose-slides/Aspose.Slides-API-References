---
title: Presentation
second_title: Aspose.Slides pro Java - referenční příručka API
description: Reprezentuje prezentaci Microsoft PowerPoint.
type: docs
url: /cs/com.aspose.slides/presentation/
---
**Dědičnost:**
java.lang.Object

**Všechna implementovaná rozhraní:**
[com.aspose.slides.IPresentation](../../com.aspose.slides/ipresentation), com.aspose.slides.IDOMObject
```
public final class Presentation implements IPresentation, IDOMObject
```

Representuje prezentaci Microsoft PowerPoint.

--------------------

> ```
> The following example shows how to create PowerPoint Presentation.
>   
>  // Vytvořte objekt Presentation, který představuje soubor prezentace
>  Presentation pres = new Presentation();
>  try {
>      // Získejte první snímek
>      ISlide slide = pres.getSlides().get_Item(0);
>      // Přidejte autoshape typu čára
>      slide.getShapes().addAutoShape(ShapeType.Line, 50, 150, 300, 0);
>      // Uložte soubor prezentace.
>      pres.save("NewPresentation_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>   
>   The following example shows how to open and save Presentation.
>   
>  // Načtěte jakýkoli podporovaný soubor v Presentation, např. ppt, pptx, odp atd.
>  Presentation pres = new Presentation("Sample.odp");
>  try {
>      // Uložte soubor prezentace.
>      pres.save("OutputPresenation.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

## Konstruktory

| Konstruktor | Popis |
| --- | --- |
| [Presentation()](#Presentation--) | Tento konstruktor vytvoří novou prezentaci od nuly. |
| [Presentation(LoadOptions loadOptions)](#Presentation-com.aspose.slides.LoadOptions-) | Tento konstruktor vytvoří novou prezentaci od nuly. |
| [Presentation(InputStream stream)](#Presentation-java.io.InputStream-) | Tento konstruktor je hlavním mechanismem pro načtení existující prezentace. |
| [Presentation(InputStream stream, LoadOptions loadOptions)](#Presentation-java.io.InputStream-com.aspose.slides.LoadOptions-) | Tento konstruktor je hlavním mechanismem pro načtení existující prezentace. |
| [Presentation(String file)](#Presentation-java.lang.String-) | Tento konstruktor získá cestu ke zdrojovému souboru, ze kterého jsou načteny obsahy prezentace. |
| [Presentation(String file, LoadOptions loadOptions)](#Presentation-java.lang.String-com.aspose.slides.LoadOptions-) | Tento konstruktor získá cestu ke zdrojovému souboru, ze kterého jsou načteny obsahy prezentace. |
## Metody

| Metoda | Popis |
| --- | --- |
| [getCurrentDateTime()](#getCurrentDateTime--) | Vrací nebo nastavuje datum a čas, které nahradí obsah polí datum/čas. |
| [setCurrentDateTime(Date value)](#setCurrentDateTime-java.util.Date-) | Vrací nebo nastavuje datum a čas, které nahradí obsah polí datum/čas. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | Vrací aktuální správce HeaderFooter. |
| [getProtectionManager()](#getProtectionManager--) | Získá správce oprávnění pro tuto prezentaci. |
| [getSlides()](#getSlides--) | Vrací seznam všech snímků definovaných v prezentaci. |
| [getSections()](#getSections--) | Vrací seznam všech sekcí snímků definovaných v prezentaci. |
| [getSlideSize()](#getSlideSize--) | Vrací objekt velikosti snímku. |
| [getNotesSize()](#getNotesSize--) | Vrací objekt velikosti poznámkových snímků. |
| [getLayoutSlides()](#getLayoutSlides--) | Vrací seznam všech rozložení snímků definovaných v prezentaci. |
| [getMasters()](#getMasters--) | Vrací seznam všech hlavních snímků definovaných v prezentaci. |
| [getMasterNotesSlideManager()](#getMasterNotesSlideManager--) | Vrací správce hlavních poznámek. |
| [getMasterHandoutSlideManager()](#getMasterHandoutSlideManager--) | Vrací správce hlavních výstřižků. |
| [getFontsManager()](#getFontsManager--) | Vrací správce fontů. |
| [getDefaultTextStyle()](#getDefaultTextStyle--) | Vrací výchozí styl textu pro tvary. |
| [getCommentAuthors()](#getCommentAuthors--) | Vrací kolekci autorů komentářů. |
| [getDocumentProperties()](#getDocumentProperties--) | Vrací objekt DocumentProperties, který obsahuje standardní a vlastní vlastnosti dokumentu. |
| [getImages()](#getImages--) | Vrací kolekci všech obrázků v prezentaci. |
| [getAudios()](#getAudios--) | Vrací kolekci všech vložených zvukových souborů v prezentaci. |
| [getVideos()](#getVideos--) | Vrací kolekci všech vložených video souborů v prezentaci. |
| [getSlideShowSettings()](#getSlideShowSettings--) | Vrací nastavení prezentace. |
| [getDigitalSignatures()](#getDigitalSignatures--) | Vrací kolekci podpisů použité k podepsání prezentace. |
| [getCustomData()](#getCustomData--) | Vrací vlastní data prezentace. |
| [getAllCustomXmlParts()](#getAllCustomXmlParts--) | Vrací všechny vlastní datové části v prezentaci. |
| [getVbaProject()](#getVbaProject--) | Získá nebo nastaví projekt VBA s makry prezentace. |
| [setVbaProject(IVbaProject value)](#setVbaProject-com.aspose.slides.IVbaProject-) | Získá nebo nastaví projekt VBA s makry prezentace. |
| [getHyperlinkQueries()](#getHyperlinkQueries--) | Poskytuje snadný přístup ke všem hypertextovým odkazům obsaženým ve všech snímcích prezentace (ne v hlavních, rozložení, poznámkových snímcích). |
| [getViewProperties()](#getViewProperties--) | Získá vlastnosti zobrazení na úrovni celé prezentace. |
| [getFirstSlideNumber()](#getFirstSlideNumber--) | Reprezentuje číslo prvního snímku v prezentaci |
| [setFirstSlideNumber(int value)](#setFirstSlideNumber-int-) | Reprezentuje číslo prvního snímku v prezentaci |
| [getSensitivityLabels()](#getSensitivityLabels--) | Vrací kolekci štítků citlivosti aplikovaných na dokument prezentace. |
| [getSlideById(long id)](#getSlideById-long-) | Vrací Slide, MasterSlide nebo LayoutSlide podle Id. |
| [getSourceFormat()](#getSourceFormat--) | Vrací informace o formátu, ze kterého byla prezentace načtena. |
| [getMasterTheme()](#getMasterTheme--) | Vrací hlavní téma. |
| [save(String fname, int format)](#save-java.lang.String-int-) | Uloží všechny snímky prezentace do souboru ve zvoleném formátu. |
| [save(OutputStream stream, int format)](#save-java.io.OutputStream-int-) | Uloží všechny snímky prezentace do proudu ve zvoleném formátu. |
| [save(String fname, int format, ISaveOptions options)](#save-java.lang.String-int-com.aspose.slides.ISaveOptions-) | Uloží všechny snímky prezentace do souboru ve zvoleném formátu s dalšími možnostmi. |
| [save(OutputStream stream, int format, ISaveOptions options)](#save-java.io.OutputStream-int-com.aspose.slides.ISaveOptions-) | Uloží všechny snímky prezentace do proudu ve zvoleném formátu s dalšími možnostmi. |
| [save(IXamlOptions options)](#save-com.aspose.slides.IXamlOptions-) | Uloží všechny snímky prezentace do sady souborů představujících XAML markup. |
| [getImages(IRenderingOptions options)](#getImages-com.aspose.slides.IRenderingOptions-) | Vrací objekty Image pro všechny snímky prezentace. |
| [getImages(IRenderingOptions options, int[] slides)](#getImages-com.aspose.slides.IRenderingOptions-int---) | Vrací objekty Thumbnail Image pro určené snímky prezentace. |
| [getImages(IRenderingOptions options, float scaleX, float scaleY)](#getImages-com.aspose.slides.IRenderingOptions-float-float-) | Vrací objekty Thumbnail Image pro všechny snímky prezentace s vlastní škálou. |
| [getImages(IRenderingOptions options, int[] slides, float scaleX, float scaleY)](#getImages-com.aspose.slides.IRenderingOptions-int---float-float-) | Vrací objekty Thumbnail Image pro určené snímky prezentace s vlastní škálou. |
| [getImages(IRenderingOptions options, Dimension imageSize)](#getImages-com.aspose.slides.IRenderingOptions-java.awt.Dimension-) | Vrací objekty Thumbnail Image pro všechny snímky prezentace s určenou velikostí. |
| [getImages(IRenderingOptions options, int[] slides, Dimension imageSize)](#getImages-com.aspose.slides.IRenderingOptions-int---java.awt.Dimension-) | Vrací objekty Thumbnail Image pro určené snímky prezentace s určenou velikostí. |
| [save(String fname, int[] slides, int format)](#save-java.lang.String-int---int-) | Uloží určené snímky prezentace do souboru ve zvoleném formátu se zachováním čísla stránky. |
| [save(String fname, int[] slides, int format, ISaveOptions options)](#save-java.lang.String-int---int-com.aspose.slides.ISaveOptions-) | Uloží určené snímky prezentace do souboru ve zvoleném formátu se zachováním čísla stránky. |
| [save(OutputStream stream, int[] slides, int format)](#save-java.io.OutputStream-int---int-) | Uloží určené snímky prezentace do proudu ve zvoleném formátu se zachováním čísla stránky. |
| [save(OutputStream stream, int[] slides, int format, ISaveOptions options)](#save-java.io.OutputStream-int---int-com.aspose.slides.ISaveOptions-) | Uloží určené snímky prezentace do proudu ve zvoleném formátu se zachováním čísla stránky. |
| [joinPortionsWithSameFormatting()](#joinPortionsWithSameFormatting--) | Spojí běhy se stejným formátováním ve všech odstavcích ve všech přijatelých tvarech ve všech snímcích. |
| [dispose()](#dispose--) | Uvolní všechny prostředky používané tímto objektem Presentation. |
| [getPresentation()](#getPresentation--) | Vrací nadřazenou prezentaci textu. |
| [highlightText(String text, Color highlightColor)](#highlightText-java.lang.String-java.awt.Color-) | Zvýrazní všechny shody vzorového textu zadanou barvou. |
| [highlightText(String text, Color highlightColor, ITextSearchOptions options, IFindResultCallback callback)](#highlightText-java.lang.String-java.awt.Color-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-) | Zvýrazní všechny shody vzorového textu zadanou barvou. |
| [highlightRegex(Pattern regex, Color highlightColor, IFindResultCallback callback)](#highlightRegex-java.util.regex.Pattern-java.awt.Color-com.aspose.slides.IFindResultCallback-) | Zvýrazní všechny shody regulárního výrazu zadanou barvou. |
| [replaceText(String oldText, String newText, ITextSearchOptions options, IFindResultCallback callback)](#replaceText-java.lang.String-java.lang.String-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-) | Nahradí všechny výskyty zadaného textu jiným zadaným textem. |
| [replaceRegex(Pattern regex, String newText, IFindResultCallback callback)](#replaceRegex-java.util.regex.Pattern-java.lang.String-com.aspose.slides.IFindResultCallback-) | Nahradí všechny shody regulárního výrazu zadaným řetězcem. |
| [refreshChartsData()](#refreshChartsData--) | Znovu načte data pro všechny grafy v prezentaci z jejich zdrojových sešitů. |
| [refreshChartsData(boolean skipFailedCharts)](#refreshChartsData-boolean-) | Znovu načte data pro všechny grafy v prezentaci z jejich zdrojových sešitů. |
### Presentation() {#Presentation--}
```
public Presentation()
```

Tento konstruktor vytvoří novou prezentaci od nuly. Vytvořená prezentace má jeden prázdný snímek.

### Presentation(LoadOptions loadOptions) {#Presentation-com.aspose.slides.LoadOptions-}
```
public Presentation(LoadOptions loadOptions)
```

Tento konstruktor vytvoří novou prezentaci od nuly. Vytvořená prezentace má jeden prázdný snímek.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| loadOptions | [LoadOptions](../../com.aspose.slides/loadoptions) | Další možnosti načítání. |

### Presentation(InputStream stream) {#Presentation-java.io.InputStream-}
```
public Presentation(InputStream stream)
```

Tento konstruktor je hlavním mechanismem pro načtení existující prezentace.

--------------------

> ```
> FileInputStream fis = new FileInputStream("demo.pptx");
>  Presentation pres = new Presentation(fis);
>  fis.close();
> ```


**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| stream | java.io.InputStream | Vstupní proud. |

### Presentation(InputStream stream, LoadOptions loadOptions) {#Presentation-java.io.InputStream-com.aspose.slides.LoadOptions-}
```
public Presentation(InputStream stream, LoadOptions loadOptions)
```

Tento konstruktor je hlavním mechanismem pro načtení existující prezentace.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| stream | java.io.InputStream | Vstupní proud. |
| loadOptions | [LoadOptions](../../com.aspose.slides/loadoptions) | Další možnosti načítání. |

### Presentation(String file) {#Presentation-java.lang.String-}
```
public Presentation(String file)
```

Tento konstruktor získá cestu ke zdrojovému souboru, ze kterého jsou načteny obsahy prezentace.

--------------------

> ```
> Presentation pres = new Presentation("demo.pptx");
> ```


**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| file | java.lang.String | Vstupní soubor. |

### Presentation(String file, LoadOptions loadOptions) {#Presentation-java.lang.String-com.aspose.slides.LoadOptions-}
```
public Presentation(String file, LoadOptions loadOptions)
```

Tento konstruktor získá cestu ke zdrojovému souboru, ze kterého jsou načteny obsahy prezentace.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| file | java.lang.String | Vstupní soubor. |
| loadOptions | [LoadOptions](../../com.aspose.slides/loadoptions) | Další možnosti načítání. |

### getCurrentDateTime() {#getCurrentDateTime--}
```
public final Date getCurrentDateTime()
```

Vrací nebo nastavuje datum a čas, které nahradí obsah polí datum/čas. Výchozí je čas vytvoření tohoto objektu Presentation. Číst/zapisovat java.util.Date.

**Návratová hodnota:**
java.util.Date
### setCurrentDateTime(Date value) {#setCurrentDateTime-java.util.Date-}
```
public final void setCurrentDateTime(Date value)
```

Vrací nebo nastavuje datum a čas, které nahradí obsah polí datum/čas. Výchozí je čas vytvoření tohoto objektu Presentation. Číst/zapisovat java.util.Date.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | java.util.Date |  |

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Vrací objekt Parent_Immediate. Pouze ke čtení IDOMObject.

**Návratová hodnota:**
com.aspose.slides.IDOMObject
### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public final IPresentationHeaderFooterManager getHeaderFooterManager()
```

Vrací aktuální správce HeaderFooter. Pouze ke čtení [IPresentationHeaderFooterManager](../../com.aspose.slides/ipresentationheaderfootermanager).

--------------------

> ```
> The following example shows how to set footer visibility inside Slide of PowerPoint Presentation.
>  
>  Presentation pres = new Presentation("presentation.ppt");
>  try
>  {
>      IBaseSlideHeaderFooterManager headerFooterManager = pres.getSlides().get_Item(0).getHeaderFooterManager();
>      if (!headerFooterManager.isFooterVisible()) // Vlastnost IsFooterVisible se používá k označení, že zástupný prvek zápatí snímku není přítomen.
>      {
>          headerFooterManager.setFooterVisibility(true); // Metoda SetFooterVisibility se používá k zpřístupnění zástupného prvku zápatí snímku.
>      }
>      if (!headerFooterManager.isSlideNumberVisible()) // Vlastnost IsSlideNumberVisible se používá k označení, že zástupný prvek čísla stránky snímku není přítomen.
>      {
>          headerFooterManager.setSlideNumberVisibility(true); // Metoda SetSlideNumberVisibility se používá k zpřístupnění zástupného prvku čísla stránky snímku.
>      }
>      if (!headerFooterManager.isDateTimeVisible()) // Vlastnost IsDateTimeVisible se používá k označení, že zástupný prvek data a času snímku není přítomen.
>      {
>          headerFooterManager.setDateTimeVisibility(true); // Metoda SetFooterVisibility se používá k zpřístupnění zástupného prvku data a času snímku.
>      }
>      headerFooterManager.setFooterText("Footer text"); // Metoda SetFooterText se používá pro nastavení textu do zástupného prvku zápatí snímku.
>      headerFooterManager.setDateTimeText("Date and time text"); // Metoda SetDateTimeText se používá pro nastavení textu do zástupného prvku data a času snímku.
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
>      headerFooterManager.setFooterAndChildFootersVisibility(true); // Metoda SetFooterAndChildFootersVisibility se používá k zpřístupnění hlavního snímku a všech podřízených zástupných prvků zápatí.
>      headerFooterManager.setSlideNumberAndChildSlideNumbersVisibility(true); // Metoda SetSlideNumberAndChildSlideNumbersVisibility se používá k zpřístupnění hlavního snímku a všech podřízených zástupných prvků čísel stránek.
>      headerFooterManager.setDateTimeAndChildDateTimesVisibility(true); // Metoda SetDateTimeAndChildDateTimesVisibility se používá k zpřístupnění hlavního snímku a všech podřízených zástupných prvků data a času.
> 
>      headerFooterManager.setFooterAndChildFootersText("Footer text"); // Metoda SetFooterAndChildFootersText se používá pro nastavení textu do hlavního snímku a všech podřízených zástupných prvků zápatí.
>      headerFooterManager.setDateTimeAndChildDateTimesText("Date and time text"); // Metoda SetDateTimeAndChildDateTimesText se používá pro nastavení textu do hlavního snímku a všech podřízených zástupných prvků data a času.
>  }
>  finally
>  {
>      if (pres != null) pres.dispose();
>  }
> ```


**Návratová hodnota:**
[IPresentationHeaderFooterManager](../../com.aspose.slides/ipresentationheaderfootermanager)
### getProtectionManager() {#getProtectionManager--}
```
public final IProtectionManager getProtectionManager()
```

Získá správce oprávnění pro tuto prezentaci. Pouze ke čtení [IProtectionManager](../../com.aspose.slides/iprotectionmanager).

**Návratová hodnota:**
[IProtectionManager](../../com.aspose.slides/iprotectionmanager)
### getSlides() {#getSlides--}
```
public final ISlideCollection getSlides()
```

Vrací seznam všech snímků definovaných v prezentaci. Pouze ke čtení [ISlideCollection](../../com.aspose.slides/islidecollection).

--------------------

> ```
> The following example shows how to set slides' background color of PowerPoint Presentation.
>  
>  // Vytvořte instanci třídy Presentation, která představuje soubor prezentace
>  Presentation pres = new Presentation();
>  try
>  {
>      // Nastavte barvu pozadí prvního ISlide na modrou
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
>  // Vytvořte instanci třídy Presentation, která představuje soubor prezentace
>  Presentation pres = new Presentation("SetImageAsBackground.pptx");
>  try {
>      // Nastavte pozadí pomocí obrázku
>      pres.getSlides().get_Item(0).getBackground().setType(BackgroundType.OwnBackground);
>      pres.getSlides().get_Item(0).getBackground().getFillFormat().setFillType(FillType.Picture);
>      pres.getSlides().get_Item(0).getBackground().getFillFormat().getPictureFillFormat().setPictureFillMode(PictureFillMode.Stretch);
>      // Nastavte obrázek
>      BufferedImage img = ImageIO.read(new File("Tulips.jpg"));
>      // Přidejte obrázek do kolekce obrázků prezentace
>      IPPImage imgx = pres.getImages().addImage(img);
>      pres.getSlides().get_Item(0).getBackground().getFillFormat().getPictureFillFormat().getPicture().setImage(imgx);
>      // Uložte prezentaci na disk
>      pres.save("ContentBG_Img_out.pptx", SaveFormat.Pptx);
>  } catch (IOException e) { }
>  finally
>  {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to add slide transition Presentation.
>  
>  // Vytvořte instanci třídy Presentation pro načtení zdrojového souboru prezentace
>  Presentation pres = new Presentation("AccessSlides.pptx");
>  try
>  {
>      // Použijte přechod typu kruh na snímku 1
>      pres.getSlides().get_Item(0).getSlideShowTransition().setType(TransitionType.Circle);
>      // Použijte přechod typu hřeben na snímku 2
>      pres.getSlides().get_Item(1).getSlideShowTransition().setType(TransitionType.Comb);
>      // Uložte prezentaci na disk
>      pres.save("SampleTransition_out.pptx", SaveFormat.Pptx);
>  }
>  finally
>  {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to add advanced slide Transition.
>  
>  // Vytvořte instanci třídy Presentation, která představuje soubor prezentace
>  Presentation pres = new Presentation("BetterSlideTransitions.pptx");
>  try
>  {
>      // Použijte přechod typu kruh na snímku 1
>      pres.getSlides().get_Item(0).getSlideShowTransition().setType(TransitionType.Circle);
>      // Nastavte dobu přechodu na 3 sekundy
>      pres.getSlides().get_Item(0).getSlideShowTransition().setAdvanceOnClick(true);
>      pres.getSlides().get_Item(0).getSlideShowTransition().setAdvanceAfterTime(3000);
>      // Použijte přechod typu hřeben na snímku 2
>      pres.getSlides().get_Item(1).getSlideShowTransition().setType(TransitionType.Comb);
>      // Nastavte dobu přechodu na 5 sekund
>      pres.getSlides().get_Item(1).getSlideShowTransition().setAdvanceOnClick(true);
>      pres.getSlides().get_Item(1).getSlideShowTransition().setAdvanceAfterTime(5000);
>      // Použijte přechod typu zoom na snímku 3
>      pres.getSlides().get_Item(2).getSlideShowTransition().setType(TransitionType.Zoom);
>      // Nastavte dobu přechodu na 7 sekund
>      pres.getSlides().get_Item(2).getSlideShowTransition().setAdvanceOnClick(true);
>      pres.getSlides().get_Item(2).getSlideShowTransition().setAdvanceAfterTime(7000);
>      // Uložte prezentaci na disk
>      pres.save("SampleTransition_out.pptx", SaveFormat.Pptx);
>  }
>  finally
>  {
>      if (pres != null) pres.dispose();
>  }
> ```


**Návratová hodnota:**
[ISlideCollection](../../com.aspose.slides/islidecollection)
### getSections() {#getSections--}
```
public final ISectionCollection getSections()
```

Vrací seznam všech sekcí snímků definovaných v prezentaci. Pouze ke čtení [ISectionCollection](../../com.aspose.slides/isectioncollection).

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
>      // section1 bude ukončena na newSlide2 a po ní začne section2
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


**Návratová hodnota:**
[ISectionCollection](../../com.aspose.slides/isectioncollection)
### getSlideSize() {#getSlideSize--}
```
public final ISlideSize getSlideSize()
```

Vrací objekt velikosti snímku. Pouze ke čtení [ISlideSize](../../com.aspose.slides/islidesize).

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
>  // Vytvořte objekt Presentation, který představuje soubor prezentace
>  Presentation presentation = new Presentation("AccessSlides.pptx");
>  try {
>      Presentation auxPresentation = new Presentation();
>      try {
>          ISlide slide = presentation.getSlides().get_Item(0);
>          // Nastavte velikost snímku generovaných prezentací na velikost zdrojové
>          presentation.getSlideSize().setSize(540, 720, SlideSizeScaleType.EnsureFit); // Metoda SetSize se používá k nastavení velikosti snímku se škálováním obsahu tak, aby se vešel
>          presentation.getSlideSize().setSize(SlideSizeType.A4Paper, SlideSizeScaleType.Maximize); // Metoda SetSize se používá k nastavení velikosti snímku s maximalizací velikosti obsahu
>          // Uložte prezentaci na disk
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
>      pres.getSlideSize().setSize(780, 540, SlideSizeScaleType.DoNotScale); // Formát papíru A4
>      pres.save("pres-a4-slide-size.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Návratová hodnota:**
[ISlideSize](../../com.aspose.slides/islidesize)
### getNotesSize() {#getNotesSize--}
```
public final INotesSize getNotesSize()
```

Vrací objekt velikosti poznámkových snímků. Pouze ke čtení [INotesSize](../../com.aspose.slides/inotessize).

**Návratová hodnota:**
[INotesSize](../../com.aspose.slides/inotessize)
### getLayoutSlides() {#getLayoutSlides--}
```
public final IGlobalLayoutSlideCollection getLayoutSlides()
```

Vrací seznam všech rozložení snímků definovaných v prezentaci. Pouze ke čtení [IGlobalLayoutSlideCollection](../../com.aspose.slides/igloballayoutslidecollection).

--------------------

Můžete použít alternativní API pro přidávání/vkládání/odstraňování/klonování rozložení snímků pomocí vlastnosti IMasterSlide.LayoutSlides.

**Návratová hodnota:**
[IGlobalLayoutSlideCollection](../../com.aspose.slides/igloballayoutslidecollection)
### getMasters() {#getMasters--}
```
public final IMasterSlideCollection getMasters()
```

Vrací seznam všech hlavních snímků definovaných v prezentaci. Pouze ke čtení [IMasterSlideCollection](../../com.aspose.slides/imasterslidecollection).

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
>  // Vytvořte třídu Presentation, která představuje soubor prezentace
>  Presentation pres = new Presentation();
>  try
>  {
>      // Nastavte barvu pozadí hlavního ISlide na lesní zelenou
>      pres.getMasters().get_Item(0).getBackground().setType(BackgroundType.OwnBackground);
>      pres.getMasters().get_Item(0).getBackground().getFillFormat().setFillType(FillType.Solid);
>      pres.getMasters().get_Item(0).getBackground().getFillFormat().getSolidFillColor().setColor(Color.GREEN);
>      // Uložte prezentaci na disk
>      pres.save("SetSlideBackgroundMaster_out.pptx", SaveFormat.Pptx);
>  }
>  finally
>  {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following examples shows how to add slide layout to PowerPoint Presentation.
>  
>  // Vytvořte třídu Presentation, která představuje soubor prezentace
>  Presentation presentation = new Presentation("AccessSlides.pptx");
>  try
>  {
>      // Pokuste se vyhledat podle typu rozvržení snímku
>      IMasterLayoutSlideCollection layoutSlides = presentation.getMasters().get_Item(0).getLayoutSlides();
>      ILayoutSlide layoutSlide = null;
>      if (layoutSlides.getByType(SlideLayoutType.TitleAndObject) != null)
>          layoutSlide = layoutSlides.getByType(SlideLayoutType.TitleAndObject);
>      else
>          layoutSlide = layoutSlides.getByType(SlideLayoutType.Title);
> 
>      if (layoutSlide == null)
>      {
>          // Situace, kdy prezentace neobsahuje některé typy rozvržení.
>          // Soubor prezentace obsahuje pouze typy rozvržení Blank a Custom.
>          // Avšak rozvržení snímků s typem Custom mají různé názvy snímků,
>          // například "Title", "Title and Content" atd. A je možné tyto použít
>          // názvy pro výběr rozvržení snímku.
>          // Také je možné použít sadu typů placeholder tvarů. Například,
>          // Slide s názvem Title by měl mít jen typ Title placeholder, atd.
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
>      // Přidání prázdného snímku s přidaným rozvržením snímku
>      presentation.getSlides().insertEmptySlide(0, layoutSlide);
>      // Uložení prezentace
>      presentation.save("AddLayoutSlides_out.pptx", SaveFormat.Pptx);
>  }
>  finally
>  {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Návratová hodnota:**
[IMasterSlideCollection](../../com.aspose.slides/imasterslidecollection)
### getMasterNotesSlideManager() {#getMasterNotesSlideManager--}
```
public final IMasterNotesSlideManager getMasterNotesSlideManager()
```

Vrací správce hlavních poznámek. Pouze ke čtení [IMasterNotesSlideManager](../../com.aspose.slides/imasternotesslidemanager).

**Návratová hodnota:**
[IMasterNotesSlideManager](../../com.aspose.slides/imasternotesslidemanager)
### getMasterHandoutSlideManager() {#getMasterHandoutSlideManager--}
```
public final IMasterHandoutSlideManager getMasterHandoutSlideManager()
```

Vrací správce hlavních výstřižků. Pouze ke čtení [IMasterHandoutSlideManager](../../com.aspose.slides/imasterhandoutslidemanager).

**Návratová hodnota:**
[IMasterHandoutSlideManager](../../com.aspose.slides/imasterhandoutslidemanager)
### getFontsManager() {#getFontsManager--}
```
public final IFontsManager getFontsManager()
```

Vrací správce fontů. Pouze ke čtení [IFontsManager](../../com.aspose.slides/ifontsmanager).

--------------------

> ```
> The following example shows how to add embedded fonts to PowerPoint Presentation.
>  
>  // Načtěte prezentaci
>  Presentation pres = new Presentation("Fonts.pptx");
>  try {
>      // Načtěte zdrojové písmo, které má být nahrazeno
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
>      // Uložte prezentaci
>      pres.save("AddEmbeddedFont_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Návratová hodnota:**
[IFontsManager](../../com.aspose.slides/ifontsmanager)
### getDefaultTextStyle() {#getDefaultTextStyle--}
```
public final ITextStyle getDefaultTextStyle()
```

Vrací výchozí styl textu pro tvary. Pouze ke čtení [ITextStyle](../../com.aspose.slides/itextstyle).

**Návratová hodnota:**
[ITextStyle](../../com.aspose.slides/itextstyle)
### getCommentAuthors() {#getCommentAuthors--}
```
public final ICommentAuthorCollection getCommentAuthors()
```

Vrací kolekci autorů komentářů. Pouze ke čtení [ICommentAuthorCollection](../../com.aspose.slides/icommentauthorcollection).

**Návratová hodnota:**
[ICommentAuthorCollection](../../com.aspose.slides/icommentauthorcollection)
### getDocumentProperties() {#getDocumentProperties--}
```
public final IDocumentProperties getDocumentProperties()
```

Vrací objekt DocumentProperties, který obsahuje standardní a vlastní vlastnosti dokumentu. Pouze ke čtení [IDocumentProperties](../../com.aspose.slides/idocumentproperties).

**Návratová hodnota:**
[IDocumentProperties](../../com.aspose.slides/idocumentproperties)
### getImages() {#getImages--}
```
public final IImageCollection getImages()
```

Vrací kolekci všech obrázků v prezentaci. Pouze ke čtení [IImageCollection](../../com.aspose.slides/iimagecollection).

--------------------

> ```
> The following examples shows how to add image as BLOB in PowerPoint Presentation.
>  
>  // vytvoří novou prezentaci, ke které bude obrázek přidán.
>  Presentation pres = new Presentation();
>  try
>  {
>      // předpokládejme, že máme velký soubor obrázku, který chceme zahrnout do prezentace
>      FileInputStream fip = new FileInputStream("large_image.jpg");
>      try
>      {
>          // Přidáme obrázek do prezentace - zvolíme chování KeepLocked, protože...
>          // NE plánujeme přistupovat k souboru "largeImage.png" file.
>          IPPImage img = pres.getImages().addImage(fip, LoadingStreamBehavior.KeepLocked);
>          pres.getSlides().get_Item(0).getShapes().addPictureFrame(ShapeType.Rectangle, 0, 0, 300, 200, img);
>          // Uloží prezentaci. Během výstupu velké prezentace zůstává spotřeba paměti
>          // nízká po celou dobu životního cyklu objektu pres
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
>      // Přidá obrázek do prezentace
>      IPPImage image = pres.getImages().addImage(Files.readAllBytes(Paths.get("image.png")));
>      // Vytvoří rámeček obrázku na snímku 1 na základě předtím přidaného obrázku
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


**Návratová hodnota:**
[IImageCollection](../../com.aspose.slides/iimagecollection)
### getAudios() {#getAudios--}
```
public final IAudioCollection getAudios()
```
Vrací kolekci všech vložených zvukových souborů v prezentaci. Pouze pro čtení [IAudioCollection](../../com.aspose.slides/iaudiocollection).

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


**Vrací:**
[IAudioCollection](../../com.aspose.slides/iaudiocollection)
### getVideos() {#getVideos--}
```
public final IVideoCollection getVideos()
```


Vrací kolekci všech vložených video souborů v prezentaci. Pouze pro čtení [IVideoCollection](../../com.aspose.slides/ivideocollection).

--------------------

> ```
> The following examples shows how to add image as BLOB in PowerPoint Presentation.
>  
>  // vytvoří novou prezentaci, ke které bude obrázek přidán.
>  Presentation pres = new Presentation();
>  try
>  {
>      // předpokládejme, že máme velký soubor obrázku, který chceme zahrnout do prezentace
>      FileInputStream fip = new FileInputStream("large_image.jpg");
>      try
>      {
>          // Přidáme obrázek do prezentace - zvolíme chování KeepLocked, protože...
>          // NE plánujeme přistupovat k souboru "largeImage.png" file.
>          IPPImage img = pres.getImages().addImage(fip, LoadingStreamBehavior.KeepLocked);
>          pres.getSlides().get_Item(0).getShapes().addPictureFrame(ShapeType.Rectangle, 0, 0, 300, 200, img);
>          // Ukládá prezentaci. Během výstupu velké prezentace...
>          // ... zůstává nízká po celou dobu životního cyklu objektu pres.
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
>      // Přidá obrázek do prezentace
>      IPPImage image = pres.getImages().addImage(Files.readAllBytes(Paths.get("image.png")));
>      // Vytvoří rámeček obrázku na snímku 1 na základě dříve přidaného obrázku
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


**Vrací:**
[IVideoCollection](../../com.aspose.slides/ivideocollection)
### getSlideShowSettings() {#getSlideShowSettings--}
```
public final SlideShowSettings getSlideShowSettings()
```


Vrací nastavení prezentace pro promítání.

**Vrací:**
[SlideShowSettings](../../com.aspose.slides/slideshowsettings)
### getDigitalSignatures() {#getDigitalSignatures--}
```
public final IDigitalSignatureCollection getDigitalSignatures()
```


Vrací kolekci podpisů použitých k podepsání prezentace. Pouze pro čtení [IDigitalSignatureCollection](../../com.aspose.slides/idigitalsignaturecollection).

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


**Vrací:**
[IDigitalSignatureCollection](../../com.aspose.slides/idigitalsignaturecollection)
### getCustomData() {#getCustomData--}
```
public final ICustomData getCustomData()
```


Vrací vlastní data prezentace. Pouze pro čtení [ICustomData](../../com.aspose.slides/icustomdata).

**Vrací:**
[ICustomData](../../com.aspose.slides/icustomdata)
### getAllCustomXmlParts() {#getAllCustomXmlParts--}
```
public final ICustomXmlPart[] getAllCustomXmlParts()
```


Vrací všechny části vlastních dat v prezentaci. Pouze pro čtení ICustomXmlPart[].

--------------------

> ```
> The following examples show how to clear all custom xml parts from PowerPoint Presentation.
>  
>  Presentation pres = new Presentation("PresentationWithCustomXml.pptx");
>  try {
>      // Procházejte všechny vlastní XML části
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


**Vrací:**
com.aspose.slides.ICustomXmlPart[]
### getVbaProject() {#getVbaProject--}
```
public final IVbaProject getVbaProject()
```


Získá nebo nastaví projekt VBA s makry prezentace. Čtení / zápis [IVbaProject](../../com.aspose.slides/ivbaproject).

**Vrací:**
[IVbaProject](../../com.aspose.slides/ivbaproject)
### setVbaProject(IVbaProject value) {#setVbaProject-com.aspose.slides.IVbaProject-}
```
public final void setVbaProject(IVbaProject value)
```


Získá nebo nastaví projekt VBA s makry prezentace. Čtení / zápis [IVbaProject](../../com.aspose.slides/ivbaproject).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | [IVbaProject](../../com.aspose.slides/ivbaproject) |  |
### getHyperlinkQueries() {#getHyperlinkQueries--}
```
public final IHyperlinkQueries getHyperlinkQueries()
```


Poskytuje snadný přístup ke všem hyperodkazům obsaženým ve všech snímcích prezentace (ne v hlavních, rozložení, poznámkových snímcích). Pouze pro čtení [IHyperlinkQueries](../../com.aspose.slides/ihyperlinkqueries).

**Vrací:**
[IHyperlinkQueries](../../com.aspose.slides/ihyperlinkqueries)
### getViewProperties() {#getViewProperties--}
```
public final IViewProperties getViewProperties()
```


Získá vlastnosti zobrazení napříč prezentací. Pouze pro čtení [IViewProperties](../../com.aspose.slides/iviewproperties).

**Vrací:**
[IViewProperties](../../com.aspose.slides/iviewproperties)
### getFirstSlideNumber() {#getFirstSlideNumber--}
```
public final int getFirstSlideNumber()
```


Reprezentuje číslo prvního snímku v prezentaci

**Vrací:**
int
### setFirstSlideNumber(int value) {#setFirstSlideNumber-int-}
```
public final void setFirstSlideNumber(int value)
```


Reprezentuje číslo prvního snímku v prezentaci

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | int |  |
### getSensitivityLabels() {#getSensitivityLabels--}
```
public final ISensitivityLabelCollection getSensitivityLabels()
```


Vrací kolekci štítků citlivosti aplikovaných na dokument prezentace. Pouze pro čtení [ISensitivityLabelCollection](../../com.aspose.slides/isensitivitylabelcollection).

--------------------

> ```
> Presentation pres = new Presentation("SomePresentation.pptx");
>  try {
>      ISensitivityLabelCollection sensitivityLabels = pres.getSensitivityLabels();
> 
>      // Vytisknout použité štítky
>      for (ISensitivityLabel sensitivityLabel : sensitivityLabels)
>          System.out.println("Label Id " + sensitivityLabel.getId() + " from Azure AD site " + sensitivityLabel.getSiteId());
> 
>      // Přidejte nový štítek
>      String labelIdString = "{xxxxxxxx-xxxx-xxxx-xxxx-xxxxxxxxxxxx}"; // Získat ID citlivostního štítku z politiky
>      UUID siteIdGuid = UUID.fromString("{xxxxxxxx-xxxx-xxxx-xxxx-xxxxxxxxxxxx}"); // Získat identifikátor Azure AD lokace z politiky
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
### getSlideById(long id) {#getSlideById-long-}
```
public final IBaseSlide getSlideById(long id)
```


Vrací Slide, MasterSlide nebo LayoutSlide podle Id.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| id | long | Id snímku. |

**Vrací:**
[IBaseSlide](../../com.aspose.slides/ibaseslide) - IBaseSlide object.
### getSourceFormat() {#getSourceFormat--}
```
public final int getSourceFormat()
```


Vrací informace o formátu, ze kterého byla prezentace načtena. Pouze pro čtení [SourceFormat](../../com.aspose.slides/sourceformat).

**Vrací:**
int
### getMasterTheme() {#getMasterTheme--}
```
public final IMasterTheme getMasterTheme()
```


Vrací hlavní motiv. Pouze pro čtení [IMasterTheme](../../com.aspose.slides/imastertheme).

--------------------

> ```
> The following examples shows how to change a theme effect by altering parts of elements of PowerPoint Presentation.
>  
>  // Vytvořte objekt prezentace, který představuje soubor prezentace
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


**Vrací:**
[IMasterTheme](../../com.aspose.slides/imastertheme)
### save(String fname, int format) {#save-java.lang.String-int-}
```
public final void save(String fname, int format)
```


Uloží všechny snímky prezentace do souboru ve specifikovaném formátu.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| fname | java.lang.String | Cesta k vytvořenému souboru. |
| format | int | Formát exportovaných dat. |

### save(OutputStream stream, int format) {#save-java.io.OutputStream-int-}
```
public final void save(OutputStream stream, int format)
```


Uloží všechny snímky prezentace do proudu ve specifikovaném formátu.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| stream | java.io.OutputStream | Výstupní proud. |
| format | int | Formát exportovaných dat. |

### save(String fname, int format, ISaveOptions options) {#save-java.lang.String-int-com.aspose.slides.ISaveOptions-}
```
public final void save(String fname, int format, ISaveOptions options)
```


Uloží všechny snímky prezentace do souboru ve specifikovaném formátu s dalšími možnostmi.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| fname | java.lang.String | Cesta k vytvořenému souboru. |
| format | int | Formát exportovaných dat. |
| options | [ISaveOptions](../../com.aspose.slides/isaveoptions) | Další možnosti formátu. |

### save(OutputStream stream, int format, ISaveOptions options) {#save-java.io.OutputStream-int-com.aspose.slides.ISaveOptions-}
```
public final void save(OutputStream stream, int format, ISaveOptions options)
```


Uloží všechny snímky prezentace do proudu ve specifikovaném formátu s dalšími možnostmi.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| stream | java.io.OutputStream | Výstupní proud. |
| format | int | Formát exportovaných dat. |
| options | [ISaveOptions](../../com.aspose.slides/isaveoptions) | Další možnosti formátu. |

### save(IXamlOptions options) {#save-com.aspose.slides.IXamlOptions-}
```
public final void save(IXamlOptions options)
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
public final IImage[] getImages(IRenderingOptions options)
```


Vrací objekty Image pro všechny snímky prezentace.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Možnosti Tiff. |

**Vrací:**
com.aspose.slides.IImage[] - Image objects.
### getImages(IRenderingOptions options, int[] slides) {#getImages-com.aspose.slides.IRenderingOptions-int---}
```
public final IImage[] getImages(IRenderingOptions options, int[] slides)
```


Vrací objekty Thumbnail Image pro specifikované snímky prezentace.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Možnosti Tiff. |
| slides | int[] | Pole s pozicemi snímků, počínaje 1. |

**Vrací:**
com.aspose.slides.IImage[] - Image objects.
### getImages(IRenderingOptions options, float scaleX, float scaleY) {#getImages-com.aspose.slides.IRenderingOptions-float-float-}
```
public final IImage[] getImages(IRenderingOptions options, float scaleX, float scaleY)
```


Vrací objekty Thumbnail Image pro všechny snímky prezentace s vlastním měřítkem.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Možnosti Tiff. |
| scaleX | float | Hodnota, o kterou se tento Thumbnail v ose x zvětší. |
| scaleY | float | Hodnota, o kterou se tento Thumbnail v ose y zvětší. |

**Vrací:**
com.aspose.slides.IImage[] - Image objects.
### getImages(IRenderingOptions options, int[] slides, float scaleX, float scaleY) {#getImages-com.aspose.slides.IRenderingOptions-int---float-float-}
```
public final IImage[] getImages(IRenderingOptions options, int[] slides, float scaleX, float scaleY)
```


Vrací objekty Thumbnail Image pro specifikované snímky prezentace s vlastním měřítkem.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Možnosti Tiff. |
| slides | int[] | Pole s pozicemi snímků, počínaje 1. |
| scaleX | float | Hodnota, o kterou se tento Thumbnail v ose x zvětší. |
| scaleY | float | Hodnota, o kterou se tento Thumbnail v ose y zvětší. |

**Vrací:**
com.aspose.slides.IImage[] - Image objects.
### getImages(IRenderingOptions options, Dimension imageSize) {#getImages-com.aspose.slides.IRenderingOptions-java.awt.Dimension-}
```
public final IImage[] getImages(IRenderingOptions options, Dimension imageSize)
```


Vrací objekty Thumbnail Image pro všechny snímky prezentace se specifikovanou velikostí.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Možnosti Tiff. |
| imageSize | java.awt.Dimension | Velikost vytvářeného obrázku. |

**Vrací:**
com.aspose.slides.IImage[] - Image objects.
### getImages(IRenderingOptions options, int[] slides, Dimension imageSize) {#getImages-com.aspose.slides.IRenderingOptions-int---java.awt.Dimension-}
```
public final IImage[] getImages(IRenderingOptions options, int[] slides, Dimension imageSize)
```


Vrací objekty Thumbnail Image pro specifikované snímky prezentace se specifikovanou velikostí.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Možnosti Tiff. |
| slides | int[] | Pole s pozicemi snímků, počínaje 1. |
| imageSize | java.awt.Dimension | Velikost vytvářeného obrázku. |

**Vrací:**
com.aspose.slides.IImage[] - Image objects.
### save(String fname, int[] slides, int format) {#save-java.lang.String-int---int-}
```
public final void save(String fname, int[] slides, int format)
```


Uloží specifikované snímky prezentace do souboru ve specifikovaném formátu se zachováním číslování stránek.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| fname | java.lang.String | Cesta k vytvořenému souboru. |
| slides | int[] | Pole s pozicemi snímků, počínaje 1. |
| format | int | Formát exportovaných dat. |

### save(String fname, int[] slides, int format, ISaveOptions options) {#save-java.lang.String-int---int-com.aspose.slides.ISaveOptions-}
```
public final void save(String fname, int[] slides, int format, ISaveOptions options)
```


Uloží specifikované snímky prezentace do souboru ve specifikovaném formátu se zachováním číslování stránek.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| fname | java.lang.String | Cesta k vytvořenému souboru. |
| slides | int[] | Pole s pozicemi snímků, počínaje 1. |
| format | int | Formát exportovaných dat. |
| options | [ISaveOptions](../../com.aspose.slides/isaveoptions) | Další možnosti formátu. |

### save(OutputStream stream, int[] slides, int format) {#save-java.io.OutputStream-int---int-}
```
public final void save(OutputStream stream, int[] slides, int format)
```


Uloží specifikované snímky prezentace do proudu ve specifikovaném formátu se zachováním číslování stránek.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| stream | java.io.OutputStream | Výstupní proud. |
| slides | int[] | Pole s pozicemi snímků, počínaje 1. |
| format | int | Formát exportovaných dat. |

### save(OutputStream stream, int[] slides, int format, ISaveOptions options) {#save-java.io.OutputStream-int---int-com.aspose.slides.ISaveOptions-}
```
public final void save(OutputStream stream, int[] slides, int format, ISaveOptions options)
```


Uloží specifikované snímky prezentace do proudu ve specifikovaném formátu se zachováním číslování stránek.

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

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| stream | java.io.OutputStream | Výstupní proud. |
| slides | int[] | Pole s pozicemi snímků, počínaje 1. |
| format | int | Formát exportovaných dat. |
| options | [ISaveOptions](../../com.aspose.slides/isaveoptions) | Další možnosti formátu. |

### joinPortionsWithSameFormatting() {#joinPortionsWithSameFormatting--}
```
public final void joinPortionsWithSameFormatting()
```


Spojí běhy se stejným formátováním ve všech odstavcích ve všech přijatelých tvarech ve všech snímcích.

### dispose() {#dispose--}
```
public final void dispose()
```


Uvolní všechny zdroje použité tímto objektem Presentation.

### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```


Vrací nadřazenou prezentaci textu. Pouze pro čtení [IPresentation](../../com.aspose.slides/ipresentation).

**Vrací:**
[IPresentation](../../com.aspose.slides/ipresentation)
### highlightText(String text, Color highlightColor) {#highlightText-java.lang.String-java.awt.Color-}
```
public final void highlightText(String text, Color highlightColor)
```


Zvýrazní všechny shody ukázkového textu zadanou barvou.

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
| text | java.lang.String | Text k zvýraznění. |
| highlightColor | java.awt.Color | Barva pro zvýraznění textu. |

### highlightText(String text, Color highlightColor, ITextSearchOptions options, IFindResultCallback callback) {#highlightText-java.lang.String-java.awt.Color-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-}
```
public final void highlightText(String text, Color highlightColor, ITextSearchOptions options, IFindResultCallback callback)
```


Zvýrazní všechny shody ukázkového textu zadanou barvou.

--------------------

> ```
> The following code sample shows how to highlight text in a PowerPoint presentation.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      TextSearchOptions textSearchOptions = new TextSearchOptions();
>      textSearchOptions.setWholeWordsOnly(true);
>      // zvýraznění všech samostatných výskytů 'the'
>      presentation.highlightText("the", Color.MAGENTA, textSearchOptions, null);
>      presentation.save("SomePresentation-out2.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| text | java.lang.String | Text k zvýraznění. |
| highlightColor | java.awt.Color | Barva pro zvýraznění textu. |
| options | [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions) | Možnosti vyhledávání textu [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions). |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | Objekt zpětného volání pro přijímání výsledků vyhledávání [IFindResultCallback](../../com.aspose.slides/ifindresultcallback). |

### highlightRegex(Pattern regex, Color highlightColor, IFindResultCallback callback) {#highlightRegex-java.util.regex.Pattern-java.awt.Color-com.aspose.slides.IFindResultCallback-}
```
public final void highlightRegex(Pattern regex, Color highlightColor, IFindResultCallback callback)
```


Zvýrazní všechny shody regulárního výrazu zadanou barvou.

--------------------

> ```
> The following code sample shows how to highlight text in a PowerPoint Presentation using a regular expression.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      Pattern regex = Pattern.compile("\\b[^\\s]{10,}\\b");
>      // zvýraznění všech slov s 10 nebo více znaky
>      presentation.highlightRegex(regex, Color.BLUE, null);
>      presentation.save("SomePresentation-out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

| regex | java.util.regex.Pattern | Regulární výraz java.util.regex.Pattern pro získání řetězců k zvýraznění. |
| highlightColor | java.awt.Color | Barva pro zvýraznění textu. |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | Objekt callback pro přijímání výsledků vyhledávání [IFindResultCallback](../../com.aspose.slides/ifindresultcallback). |

### replaceText(String oldText, String newText, ITextSearchOptions options, IFindResultCallback callback) {#replaceText-java.lang.String-java.lang.String-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-}
```
public final void replaceText(String oldText, String newText, ITextSearchOptions options, IFindResultCallback callback)
```

Nahrazuje všechny výskyty zadaného textu jiným zadaným textem.

--------------------

> ```
> The following sample code shows how to replace one specified string with another specified string.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx")
>  try {
>      TextSearchOptions textSearchOptions = new TextSearchOptions();
>      textSearchOptions.setWholeWordsOnly(true);
>      // Nahraďte všechny samostatné výskyty 'the' řetězcem '***'
>      presentation.replaceText("the", "***", textSearchOptions, null);
>      presentation.save("SomePresentation-out2.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| oldText | java.lang.String | Řetězec, který má být nahrazen. |
| newText | java.lang.String | Řetězec, který nahradí všechny výskyty oldText. |
| options | [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions) | Možnosti vyhledávání textu [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions). |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | Objekt callback pro přijímání výsledků vyhledávání [IFindResultCallback](../../com.aspose.slides/ifindresultcallback). |

### replaceRegex(Pattern regex, String newText, IFindResultCallback callback) {#replaceRegex-java.util.regex.Pattern-java.lang.String-com.aspose.slides.IFindResultCallback-}
```
public final void replaceRegex(Pattern regex, String newText, IFindResultCallback callback)
```

Nahrazuje všechny shody regulárního výrazu zadaným řetězcem.

--------------------

> ```
> The following code sample shows how to replace text using regular expression with the specified string.
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      Pattern regex = Pattern.compile("\\b[^\\s]{10,}\\b");
>      // Nahraďte všechna slova s 10 nebo více znaky řetězcem '***'
>      presentation.replaceRegex(regex, "***", null);
>      presentation.save("SomePresentation-out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| regex | java.util.regex.Pattern | Regulární výraz java.util.regex.Pattern pro získání řetězců k nahrazení. |
| newText | java.lang.String | Řetězec, který nahradí všechny výskyty řetězců, které mají být nahrazeny. |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | Objekt callback pro přijímání výsledků vyhledávání [IFindResultCallback](../../com.aspose.slides/ifindresultcallback). |

### refreshChartsData() {#refreshChartsData--}
```
public final void refreshChartsData()
```

Znovu načte data pro všechny grafy v prezentaci z jejich zdrojových sešitů.

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

Znovu načte data pro všechny grafy v prezentaci z jejich zdrojových sešitů.

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
| skipFailedCharts | boolean | Určuje, zda proces obnovy pokračuje, pokud se grafu nepodaří aktualizovat. Pokud je true, grafy, které způsobí výjimku, jsou přeskočeny; jinak je výjimka propagována. |