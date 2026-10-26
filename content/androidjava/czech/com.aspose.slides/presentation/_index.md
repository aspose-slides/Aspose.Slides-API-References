---
title: Presentation
second_title: Aspose.Slides pro Android přes Java API Reference
description: Representuje prezentaci Microsoft PowerPoint.
type: docs
url: /cs/com.aspose.slides/presentation/
---
**Dědičnost:**
java.lang.Object

**Všechny implementované rozhraní:**
[com.aspose.slides.IPresentation](../../com.aspose.slides/ipresentation), com.aspose.slides.IDOMObject
```
public final class Presentation implements IPresentation, IDOMObject
```

Reprezentuje prezentaci Microsoft PowerPoint.

--------------------

> ```
> The following example shows how to create PowerPoint Presentation.
>   
>  // Vytvořte objekt Presentation, který představuje soubor prezentace
>  Presentation pres = new Presentation();
>  try {
>      // Získat první snímek
>      ISlide slide = pres.getSlides().get_Item(0);
>      // Přidat automatický tvar typu čára
>      slide.getShapes().addAutoShape(ShapeType.Line, 50, 150, 300, 0);
>      // Uložit soubor prezentace.
>      pres.save("NewPresentation_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>   
>   The following example shows how to open and save Presentation.
>   
>  // Načíst jakýkoli podporovaný soubor v Presentation, např. ppt, pptx, odp atd.
>  Presentation pres = new Presentation("Sample.odp");
>  try {
>      // Uložit soubor prezentace.
>      pres.save("OutputPresenation.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

## Konstruktory

| Constructor | Description |
| --- | --- |
| [Presentation()](#Presentation--) | Tento konstruktor vytváří novou prezentaci od základů. |
| [Presentation(LoadOptions loadOptions)](#Presentation-com.aspose.slides.LoadOptions-) | Tento konstruktor vytváří novou prezentaci od základů. |
| [Presentation(InputStream stream)](#Presentation-java.io.InputStream-) | Tento konstruktor je hlavním mechanismem pro načtení existující prezentace. |
| [Presentation(InputStream stream, LoadOptions loadOptions)](#Presentation-java.io.InputStream-com.aspose.slides.LoadOptions-) | Tento konstruktor je hlavním mechanismem pro načtení existující prezentace. |
| [Presentation(String file)](#Presentation-java.lang.String-) | Tento konstruktor získává cestu ke zdrojovému souboru, ze kterého jsou načteny obsah prezentace. |
| [Presentation(String file, LoadOptions loadOptions)](#Presentation-java.lang.String-com.aspose.slides.LoadOptions-) | Tento konstruktor získává cestu ke zdrojovému souboru, ze kterého jsou načteny obsah prezentace. |
## Metody

| Method | Description |
| --- | --- |
| [getCurrentDateTime()](#getCurrentDateTime--) | Vrací nebo nastavuje datum a čas, které budou nahrazovat obsah polí datetime. |
| [setCurrentDateTime(Date value)](#setCurrentDateTime-java.util.Date-) | Vrací nebo nastavuje datum a čas, které budou nahrazovat obsah polí datetime. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | Vrací aktuální správce HeaderFooter. |
| [getProtectionManager()](#getProtectionManager--) | Získá správce oprávnění pro tuto prezentaci. |
| [getSlides()](#getSlides--) | Vrací seznam všech snímků definovaných v prezentaci. |
| [getSections()](#getSections--) | Vrací seznam všech sekcí snímků definovaných v prezentaci. |
| [getSlideSize()](#getSlideSize--) | Vrací objekt velikosti snímku. |
| [getNotesSize()](#getNotesSize--) | Vrací objekt velikosti poznámkového snímku. |
| [getLayoutSlides()](#getLayoutSlides--) | Vrací seznam všech rozvržných snímků definovaných v prezentaci. |
| [getMasters()](#getMasters--) | Vrací seznam všech hlavních snímků definovaných v prezentaci. |
| [getMasterNotesSlideManager()](#getMasterNotesSlideManager--) | Vrací správce hlavních poznámek. |
| [getMasterHandoutSlideManager()](#getMasterHandoutSlideManager--) | Vrací správce hlavních výtisků. |
| [getFontsManager()](#getFontsManager--) | Vrací správce fontů. |
| [getDefaultTextStyle()](#getDefaultTextStyle--) | Vrací výchozí styl textu pro tvary. |
| [getCommentAuthors()](#getCommentAuthors--) | Vrací kolekci autorů komentářů. |
| [getDocumentProperties()](#getDocumentProperties--) | Vrací objekt DocumentProperties, který obsahuje standardní a vlastní vlastnosti dokumentu. |
| [getImages()](#getImages--) | Vrací kolekci všech obrázků v prezentaci. |
| [getAudios()](#getAudios--) | Vrací kolekci všech vložených zvukových souborů v prezentaci. |
| [getVideos()](#getVideos--) | Vrací kolekci všech vložených video souborů v prezentaci. |
| [getSlideShowSettings()](#getSlideShowSettings--) | Vrací nastavení prezentace (slide show). |
| [getDigitalSignatures()](#getDigitalSignatures--) | Vrací kolekci podpisů použité k podepsání prezentace. |
| [getCustomData()](#getCustomData--) | Vrací vlastní data prezentace. |
| [getAllCustomXmlParts()](#getAllCustomXmlParts--) | Vrací všechny vlastní datové části v prezentaci. |
| [getVbaProject()](#getVbaProject--) | Získá nebo nastaví projekt VBA s makry prezentace. |
| [setVbaProject(IVbaProject value)](#setVbaProject-com.aspose.slides.IVbaProject-) | Získá nebo nastaví projekt VBA s makry prezentace. |
| [getHyperlinkQueries()](#getHyperlinkQueries--) | Poskytuje snadný přístup ke všem hypertextovým odkazům obsaženým ve všech snímcích prezentace (ne v hlavních, rozvržných, poznámkových snímcích). |
| [getViewProperties()](#getViewProperties--) | Získá vlastnosti zobrazení platné pro celou prezentaci. |
| [getFirstSlideNumber()](#getFirstSlideNumber--) | Reprezentuje první číslo snímku v prezentaci |
| [setFirstSlideNumber(int value)](#setFirstSlideNumber-int-) | Reprezentuje první číslo snímku v prezentaci |
| [getSensitivityLabels()](#getSensitivityLabels--) | Vrací kolekci štítků citlivosti aplikovaných na dokument prezentace. |
| [getSlideById(long id)](#getSlideById-long-) | Vrací Slide, MasterSlide nebo LayoutSlide podle Id. |
| [getSourceFormat()](#getSourceFormat--) | Vrací informace o formátu, ze kterého byla prezentace načtena. |
| [getMasterTheme()](#getMasterTheme--) | Vrací hlavní motiv. |
| [save(String fname, int format)](#save-java.lang.String-int-) | Uloží všechny snímky prezentace do souboru ve specifikovaném formátu. |
| [save(OutputStream stream, int format)](#save-java.io.OutputStream-int-) | Uloží všechny snímky prezentace do proudu ve specifikovaném formátu. |
| [save(String fname, int format, ISaveOptions options)](#save-java.lang.String-int-com.aspose.slides.ISaveOptions-) | Uloží všechny snímky prezentace do souboru ve specifikovaném formátu a s dalšími možnostmi. |
| [save(OutputStream stream, int format, ISaveOptions options)](#save-java.io.OutputStream-int-com.aspose.slides.ISaveOptions-) | Uloží všechny snímky prezentace do proudu ve specifikovaném formátu a s dalšími možnostmi. |
| [save(IXamlOptions options)](#save-com.aspose.slides.IXamlOptions-) | Uloží všechny snímky prezentace do sady souborů představujících XAML značky. |
| [getImages(IRenderingOptions options)](#getImages-com.aspose.slides.IRenderingOptions-) | Vrací objekty Image pro všechny snímky prezentace. |
| [getImages(IRenderingOptions options, int[] slides)](#getImages-com.aspose.slides.IRenderingOptions-int---) | Vrací miniatury Image pro specifické snímky prezentace. |
| [getImages(IRenderingOptions options, float scaleX, float scaleY)](#getImages-com.aspose.slides.IRenderingOptions-float-float-) | Vrací miniatury Image pro všechny snímky prezentace s vlastní škálou. |
| [getImages(IRenderingOptions options, int[] slides, float scaleX, float scaleY)](#getImages-com.aspose.slides.IRenderingOptions-int---float-float-) | Vrací miniatury Image pro specifické snímky prezentace s vlastní škálou. |
| [getImages(IRenderingOptions options, Size imageSize)](#getImages-com.aspose.slides.IRenderingOptions-com.aspose.slides.android.Size-) | Vrací miniatury Image pro všechny snímky prezentace s určenou velikostí. |
| [getImages(IRenderingOptions options, int[] slides, Size imageSize)](#getImages-com.aspose.slides.IRenderingOptions-int---com.aspose.slides.android.Size-) | Vrací miniatury Image pro specifické snímky prezentace s určenou velikostí. |
| [save(String fname, int[] slides, int format)](#save-java.lang.String-int---int-) | Uloží specifikované snímky prezentace do souboru ve specifikovaném formátu s zachováním číslování stránek. |
| [save(String fname, int[] slides, int format, ISaveOptions options)](#save-java.lang.String-int---int-com.aspose.slides.ISaveOptions-) | Uloží specifikované snímky prezentace do souboru ve specifikovaném formátu s zachováním číslování stránek. |
| [save(OutputStream stream, int[] slides, int format)](#save-java.io.OutputStream-int---int-) | Uloží specifikované snímky prezentace do proudu ve specifikovaném formátu s zachováním číslování stránek. |
| [save(OutputStream stream, int[] slides, int format, ISaveOptions options)](#save-java.io.OutputStream-int---int-com.aspose.slides.ISaveOptions-) | Uloží specifikované snímky prezentace do proudu ve specifikovaném formátu s zachováním číslování stránek. |
| [joinPortionsWithSameFormatting()](#joinPortionsWithSameFormatting--) | Spojuje běhy s identickým formátováním ve všech odstavcích ve všech vhodných tvarech ve všech snímcích. |
| [dispose()](#dispose--) | Uvolňuje všechny zdroje používané tímto objektem Presentation. |
| [getPresentation()](#getPresentation--) | Vrací nadřazenou prezentaci textu. |
| [highlightText(String text, Integer highlightColor)](#highlightText-java.lang.String-java.lang.Integer-) | Zvětrazní všechny výskyty ukázkového textu zadanou barvou. |
| [highlightText(String text, Integer highlightColor, ITextSearchOptions options, IFindResultCallback callback)](#highlightText-java.lang.String-java.lang.Integer-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-) | Zvětrazní všechny výskyty ukázkového textu zadanou barvou. |
| [highlightRegex(Pattern regex, Integer highlightColor, IFindResultCallback callback)](#highlightRegex-java.util.regex.Pattern-java.lang.Integer-com.aspose.slides.IFindResultCallback-) | Zvětrazní všechny výskyty regulárního výrazu zadanou barvou. |
| [replaceText(String oldText, String newText, ITextSearchOptions options, IFindResultCallback callback)](#replaceText-java.lang.String-java.lang.String-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-) | Nahrazuje všechny výskyty zadaného textu jiným zadaným textem. |
| [replaceRegex(Pattern regex, String newText, IFindResultCallback callback)](#replaceRegex-java.util.regex.Pattern-java.lang.String-com.aspose.slides.IFindResultCallback-) | Nahrazuje všechny výskyty regulárního výrazu zadaným řetězcem. |
### Presentation() {#Presentation--}
```
public Presentation()
```

Tento konstruktor vytváří novou prezentaci od základů. Vytvořená prezentace má jeden prázdný snímek.

### Presentation(LoadOptions loadOptions) {#Presentation-com.aspose.slides.LoadOptions-}
```
public Presentation(LoadOptions loadOptions)
```

Tento konstruktor vytváří novou prezentaci od základů. Vytvořená prezentace má jeden prázdný snímek.

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| loadOptions | [LoadOptions](../../com.aspose.slides/loadoptions) | Další možnosti načtení. |

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
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.InputStream | Vstupní proud. |

### Presentation(InputStream stream, LoadOptions loadOptions) {#Presentation-java.io.InputStream-com.aspose.slides.LoadOptions-}
```
public Presentation(InputStream stream, LoadOptions loadOptions)
```

Tento konstruktor je hlavním mechanismem pro načtení existující prezentace.

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.InputStream | Vstupní proud. |
| loadOptions | [LoadOptions](../../com.aspose.slides/loadoptions) | Další možnosti načtení. |

### Presentation(String file) {#Presentation-java.lang.String-}
```
public Presentation(String file)
```

Tento konstruktor získává cestu ke zdrojovému souboru, ze kterého jsou načteny obsah prezentace.

--------------------

> ```
> Presentation pres = new Presentation("demo.pptx");
> ```

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| file | java.lang.String | Vstupní soubor. |

### Presentation(String file, LoadOptions loadOptions) {#Presentation-java.lang.String-com.aspose.slides.LoadOptions-}
```
public Presentation(String file, LoadOptions loadOptions)
```

Tento konstruktor získává cestu ke zdrojovému souboru, ze kterého jsou načteny obsah prezentace.

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| file | java.lang.String | Vstupní soubor. |
| loadOptions | [LoadOptions](../../com.aspose.slides/loadoptions) | Další možnosti načtení. |

### getCurrentDateTime() {#getCurrentDateTime--}
```
public final Date getCurrentDateTime()
```

Vrací nebo nastavuje datum a čas, které budou nahrazovat obsah polí datetime. Výchozí nastavení je čas vytvoření tohoto objektu Presentation. Čtení/zápis java.util.Date.

**Vrací:**
java.util.Date
### setCurrentDateTime(Date value) {#setCurrentDateTime-java.util.Date-}
```
public final void setCurrentDateTime(Date value)
```

Vrací nebo nastavuje datum a čas, které budou nahrazovat obsah polí datetime. Výchozí nastavení je čas vytvoření tohoto objektu Presentation. Čtení/zápis java.util.Date.

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.util.Date |  |

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Vrací objekt Parent_Immediate. Pouze ke čtení IDOMObject.

**Vrací:**
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
>          headerFooterManager.setFooterVisibility(true); // Metoda SetFooterVisibility se používá k tomu, aby byl zástupný prvek zápatí snímku viditelný.
>      }
>      if (!headerFooterManager.isSlideNumberVisible()) // Vlastnost IsSlideNumberVisible se používá k označení, že zástupný prvek čísla stránky snímku není přítomen.
>      {
>          headerFooterManager.setSlideNumberVisibility(true); // Metoda SetSlideNumberVisibility se používá k tomu, aby byl zástupný prvek čísla stránky snímku viditelný.
>      }
>      if (!headerFooterManager.isDateTimeVisible()) // Vlastnost IsDateTimeVisible se používá k označení, že zástupný prvek data a času snímku není přítomen.
>      {
>          headerFooterManager.setDateTimeVisibility(true); // Metoda SetFooterVisibility se používá k tomu, aby byl zástupný prvek data a času snímku viditelný.
>      }
>      headerFooterManager.setFooterText("Footer text"); // Metoda SetFooterText se používá k nastavení textu do zástupného prvku zápatí snímku.
>      headerFooterManager.setDateTimeText("Date and time text"); // Metoda SetDateTimeText se používá k nastavení textu do zástupného prvku data a času snímku.
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
>      headerFooterManager.setFooterAndChildFootersVisibility(true); // Metoda SetFooterAndChildFootersVisibility se používá k tomu, aby byl hlavní snímek a všechny podřízené zástupné prvky zápatí viditelné.
>      headerFooterManager.setSlideNumberAndChildSlideNumbersVisibility(true); // Metoda SetSlideNumberAndChildSlideNumbersVisibility se používá k tomu, aby byl hlavní snímek a všechny podřízené zástupné prvky čísel stránek viditelné.
>      headerFooterManager.setDateTimeAndChildDateTimesVisibility(true); // Metoda SetDateTimeAndChildDateTimesVisibility se používá k tomu, aby byl hlavní snímek a všechny podřízené zástupné prvky data a času viditelné.
> 
>      headerFooterManager.setFooterAndChildFootersText("Footer text"); // Metoda SetFooterAndChildFootersText se používá k nastavení textu do hlavního snímku a všech podřízených zástupných prvků zápatí.
>      headerFooterManager.setDateTimeAndChildDateTimesText("Date and time text"); // Metoda SetDateTimeAndChildDateTimesText se používá k nastavení textu do hlavního snímku a všech podřízených zástupných prvků data a času.
>  }
>  finally
>  {
>      if (pres != null) pres.dispose();
>  }
> ```


**Vrací:**
[IPresentationHeaderFooterManager](../../com.aspose.slides/ipresentationheaderfootermanager)
### getProtectionManager() {#getProtectionManager--}
```
public final IProtectionManager getProtectionManager()
```

Získá správce oprávnění pro tuto prezentaci. Pouze ke čtení [IProtectionManager](../../com.aspose.slides/iprotectionmanager).

**Vrací:**
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
>  // Instancujte třídu Presentation, která představuje soubor prezentace
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
>  // Instancujte třídu Presentation, která představuje soubor prezentace
>  Presentation pres = new Presentation("SetImageAsBackground.pptx");
>  try {
>      // Nastavte pozadí pomocí obrázku
>      pres.getSlides().get_Item(0).getBackground().setType(BackgroundType.OwnBackground);
>      pres.getSlides().get_Item(0).getBackground().getFillFormat().setFillType(FillType.Picture);
>      pres.getSlides().get_Item(0).getBackground().getFillFormat().getPictureFillFormat().setPictureFillMode(PictureFillMode.Stretch);
>      // Nastavte obrázek
>      FileInputStream fos = null;
>      try {
>          fos = new FileInputStream("Tulips.jpg");
>          // Přidejte obrázek do kolekce obrázků prezentace
>          IPPImage imgx = pres.getImages().addImage(fos);
>          pres.getSlides().get_Item(0).getBackground().getFillFormat().getPictureFillFormat().getPicture().setImage(imgx);
>      } finally {
>          if (fos != null) fos.close();
>      }
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
>  // Instancujte třídu Presentation pro načtení zdrojového souboru prezentace
>  Presentation pres = new Presentation("AccessSlides.pptx");
>  try
>  {
>      // Aplikujte přechod typu kruh na snímku 1
>      pres.getSlides().get_Item(0).getSlideShowTransition().setType(TransitionType.Circle);
>      // Aplikujte přechod typu hřeben na snímku 2
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
>  // Instancujte třídu Presentation, která představuje soubor prezentace
>  Presentation pres = new Presentation("BetterSlideTransitions.pptx");
>  try
>  {
>      // Aplikujte přechod typu kruh na snímku 1
>      pres.getSlides().get_Item(0).getSlideShowTransition().setType(TransitionType.Circle);
>      // Nastavte dobu trvání přechodu na 3 sekundy
>      pres.getSlides().get_Item(0).getSlideShowTransition().setAdvanceOnClick(true);
>      pres.getSlides().get_Item(0).getSlideShowTransition().setAdvanceAfterTime(3000);
>      // Aplikujte přechod typu hřeben na snímku 2
>      pres.getSlides().get_Item(1).getSlideShowTransition().setType(TransitionType.Comb);
>      // Nastavte dobu trvání přechodu na 5 sekund
>      pres.getSlides().get_Item(1).getSlideShowTransition().setAdvanceOnClick(true);
>      pres.getSlides().get_Item(1).getSlideShowTransition().setAdvanceAfterTime(5000);
>      // Aplikujte přechod typu zoom na snímku 3
>      pres.getSlides().get_Item(2).getSlideShowTransition().setType(TransitionType.Zoom);
>      // Nastavte dobu trvání přechodu na 7 sekund
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


**Vrací:**
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


**Vrací:**
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
>  // Instancujte objekt Presentation, který představuje soubor prezentace
>  Presentation presentation = new Presentation("AccessSlides.pptx");
>  try {
>      Presentation auxPresentation = new Presentation();
>      try {
>          ISlide slide = presentation.getSlides().get_Item(0);
>          // Nastavte velikost snímku vygenerovaných prezentací na velikost zdrojové
>          presentation.getSlideSize().setSize(540, 720, SlideSizeScaleType.EnsureFit); // Metoda SetSize se používá k nastavení velikosti snímku se škálováním obsahu pro zajištění vložení
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


**Vrací:**
[ISlideSize](../../com.aspose.slides/islidesize)
### getNotesSize() {#getNotesSize--}
```
public final INotesSize getNotesSize()
```

Vrací objekt velikosti poznámkového snímku. Pouze ke čtení [INotesSize](../../com.aspose.slides/inotessize).

**Vrací:**
[INotesSize](../../com.aspose.slides/inotessize)
### getLayoutSlides() {#getLayoutSlides--}
```
public final IGlobalLayoutSlideCollection getLayoutSlides()
```

Vrací seznam všech rozvržných snímků definovaných v prezentaci. Pouze ke čtení [IGlobalLayoutSlideCollection](../../com.aspose.slides/igloballayoutslidecollection).

--------------------

Můžete přistupovat k alternativnímu API pro přidávání/vkládání/odstraňování/klonování rozvržných snímků pomocí vlastnosti IMasterSlide.LayoutSlides.

**Vrací:**
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
>  // Instancujte třídu Presentation, která představuje soubor prezentace
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
>  // Instancujte třídu Presentation, která představuje soubor prezentace
>  Presentation presentation = new Presentation("AccessSlides.pptx");
>  try
>  {
>      // Zkuste vyhledat podle typu rozvržení snímku
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
>          // Ale rozvržné snímky s typy Custom mají různá jména snímků,
>          // např. "Title", "Title and Content" atd. A je možné použít tyto
>          // jména pro výběr rozvržného snímku.
>          // Také je možné použít sadu typů placeholder tvarů. Například,
>          // Titulek snímku by měl mít jen typ placeholder Title, atd.
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
>      // Přidání prázdného snímku s přidaným rozvržným snímkem
>      presentation.getSlides().insertEmptySlide(0, layoutSlide);
>      // Uložit prezentaci
>      presentation.save("AddLayoutSlides_out.pptx", SaveFormat.Pptx);
>  }
>  finally
>  {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Vrací:**
[IMasterSlideCollection](../../com.aspose.slides/imasterslidecollection)
### getMasterNotesSlideManager() {#getMasterNotesSlideManager--}
```
public final IMasterNotesSlideManager getMasterNotesSlideManager()
```

Vrací správce hlavních poznámek. Pouze ke čtení [IMasterNotesSlideManager](../../com.aspose.slides/imasternotesslidemanager).

**Vrací:**
[IMasterNotesSlideManager](../../com.aspose.slides/imasternotesslidemanager)
### getMasterHandoutSlideManager() {#getMasterHandoutSlideManager--}
```
public final IMasterHandoutSlideManager getMasterHandoutSlideManager()
```

Vrací správce hlavních výtisků. Pouze ke čtení [IMasterHandoutSlideManager](../../com.aspose.slides/imasterhandoutslidemanager).

**Vrací:**
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
>      // Načíst zdrojové písmo, které má být nahrazeno
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
>      // Uložit prezentaci
>      pres.save("AddEmbeddedFont_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Vrací:**
[IFontsManager](../../com.aspose.slides/ifontsmanager)
### getDefaultTextStyle() {#getDefaultTextStyle--}
```
public final ITextStyle getDefaultTextStyle()
```

Vrací výchozí styl textu pro tvary. Pouze ke čtení [ITextStyle](../../com.aspose.slides/itextstyle).

**Vrací:**
[ITextStyle](../../com.aspose.slides/itextstyle)
### getCommentAuthors() {#getCommentAuthors--}
```
public final ICommentAuthorCollection getCommentAuthors()
```

Vrací kolekci autorů komentářů. Pouze ke čtení [ICommentAuthorCollection](../../com.aspose.slides/icommentauthorcollection).

**Vrací:**
[ICommentAuthorCollection](../../com.aspose.slides/icommentauthorcollection)
### getDocumentProperties() {#getDocumentProperties--}
```
public final IDocumentProperties getDocumentProperties()
```

Vrací objekt DocumentProperties, který obsahuje standardní a vlastní vlastnosti dokumentu. Pouze ke čtení [IDocumentProperties](../../com.aspose.slides/idocumentproperties).

**Vrací:**
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
>  // vytvoří novou prezentaci, do které bude obrázek přidán.
>  Presentation pres = new Presentation();
>  try
>  {
>      // předpokládejme, že máme velký soubor obrázku, který chceme zahrnout do prezentace
>      FileInputStream fip = new FileInputStream("large_image.jpg");
>      try
>      {
>          // Přidejme obrázek do prezentace - zvolíme chování KeepLocked, protože
>          // NENÍ záměrem přistupovat k souboru "largeImage.png".
>          IPPImage img = pres.getImages().addImage(fip, LoadingStreamBehavior.KeepLocked);
>          pres.getSlides().get_Item(0).getShapes().addPictureFrame(ShapeType.Rectangle, 0, 0, 300, 200, img);
>          // Uloží prezentaci. I když je vytvořena velká prezentace, spotřeba paměti
>          // zůstává nízká během životního cyklu objektu pres
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
>          // Přidá obrázek do prezentace
>          IPPImage image = pres.getImages().addImage(fos);
>          // Vytvoří obrázkový rám na snímku 1 na základě dříve přidaného obrázku
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


**Vrací:**
[IImageCollection](../../com.aspose.slides/iimagecollection)
### getAudios() {#getAudios--}
```
public final IAudioCollection getAudios()
```

Vrací kolekci všech vložených zvukových souborů v prezentaci. Pouze ke čtení [IAudioCollection](../../com.aspose.slides/iaudiocollection).

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


**Vrací:**
[IAudioCollection](../../com.aspose.slides/iaudiocollection)
### getVideos() {#getVideos--}
```
public final IVideoCollection getVideos()
```

Vrací kolekci všech vložených video souborů v prezentaci. Pouze ke čtení [IVideoCollection](../../com.aspose.slides/ivideocollection).

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
> 
>  The following examples shows how to create embedded Video Frame in a PowerPoint Presentation.
>  
>  >  // Instancujte třídu Presentation, která představuje PPTX
>  Presentation pres = new Presentation();
>  try {
>      >  // Získat první snímek
>      ISlide sld = pres.getSlides().get_Item(0);
>      >  // Vložit video do prezentace
>      IVideo vid = pres.getVideos().addVideo(new FileInputStream("Wildlife.mp4"));
>      >  // Přidat video rám
>      IVideoFrame vf = sld.getShapes().addVideoFrame(50, 150, 300, 350, vid);
>      >  // Nastavit video do video rámu
>      vf.setEmbeddedVideo(vid);
>      >  // Nastavit režim přehrávání a hlasitost videa
>      vf.setPlayMode(VideoPlayModePreset.Auto);
>      vf.setVolume(AudioVolumeMode.Loud);
>      >  // Zapsat soubor PPTX na disk
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
>  >  // Vytvoří novou prezentaci, do které bude video přidáno
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream fileStream = new FileInputStream("veryLargeVideo.avi");
>      try {
>          >  // Přidejme video do prezentace - zvolili jsme chování KeepLocked,
>          >  // protože neplánujeme přistupovat k souboru "veryLargeVideo.avi".
>          IVideo video = pres.getVideos().addVideo(fileStream, LoadingStreamBehavior.KeepLocked);
>          pres.getSlides().get_Item(0).getShapes().addVideoFrame(0, 0, 480, 270, video);
>          >  // Uloží prezentaci. Při výstupu velké prezentace zůstává spotřeba paměti
>          >  // nízká po celou dobu životního cyklu objektu pres
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
>  >  // Uzamkne zdrojový soubor a NEnačítá jej do paměti
>  loadOptions.getBlobManagementOptions().setPresentationLockingBehavior(PresentationLockingBehavior.KeepLocked);
>  >  // Vytvoří instanci Presentation, uzamkne soubor "hugePresentationWithAudiosAndVideos.pptx".
>  Presentation pres = new Presentation("Large  Video File Test1.pptx", loadOptions);
>  try {
>      >  // Uložme každé video do souboru. Abychom předešli vysoké spotřebě paměti, potřebujeme buffer,
>      >  // který bude použit k přenosu dat z video proudu prezentace do proudu pro nově vytvořený video soubor.
>      byte[] buffer = new byte[81024];
>      >  // Procházíme videa
>      for (int index = 0; index < pres.getVideos().size(); index++) {
>          IVideo video = pres.getVideos().get_Item(index);
>          >  // Otevře video proud prezentace. Všimněte si, že úmyslně nevyužíváme vlastnosti
>          >  // jako video.BinaryData - protože tato vlastnost vrací pole bytů obsahující celé video,
>          >  // což by načetlo data do paměti. Používáme video.getStream, který vrátí Stream a NEvyžaduje načtení celého videa do paměti.
>          InputStream presVideoStream = video.getStream();
>          try {
>              FileOutputStream outputFileStream = new FileOutputStream("video" + index + ".avi");
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
>          >  // Spotřeba paměti zůstane nízká bez ohledu na velikost videa nebo prezentace,
>      }
>      >  // V případě potřeby můžete stejný postup aplikovat i na audio soubory.
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
>      >  // Přidat video rám
>      IVideoFrame videoFrame = pres.getSlides().get_Item(0).getShapes().addVideoFrame(10, 10, 427, 240, "https://www.youtube.com/embed/" + videoId);
>      videoFrame.setPlayMode(VideoPlayModePreset.Auto);
> 
>      >  // Načíst miniaturu
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
>  // Instancujte objekt Presentation, který představuje soubor prezentace
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


**Vrací:**
[IVideoCollection](../../com.aspose.slides/ivideocollection)
### getSlideShowSettings() {#getSlideShowSettings--}
```
public final SlideShowSettings getSlideShowSettings()
```

Vrací nastavení prezentace (slide show).

**Vrací:**
[SlideShowSettings](../../com.aspose.slides/slideshowsettings)
### getDigitalSignatures() {#getDigitalSignatures--}
```
public final IDigitalSignatureCollection getDigitalSignatures()
```

Vrací kolekci podpisů použité k podepsání prezentace. Pouze ke čtení [IDigitalSignatureCollection](../../com.aspose.slides/idigitalsignaturecollection).

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

Vrací vlastní data prezentace. Pouze ke čtení [ICustomData](../../com.aspose.slides/icustomdata).

**Vrací:**
[ICustomData](../../com.aspose.slides/icustomdata)
### getAllCustomXmlParts() {#getAllCustomXmlParts--}
```
public final ICustomXmlPart[] getAllCustomXmlParts()
```

Vrací všechny vlastní datové části v prezentaci. Pouze ke čtení ICustomXmlPart[].

--------------------

> ```
> The following examples show how to clear all custom xml parts from PowerPoint Presentation.
>  
>  Presentation pres = new Presentation("PresentationWithCustomXml.pptx");
>  try {
>      // Projít všechny vlastní XML části
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

Získá nebo nastaví projekt VBA s makry prezentace. Čtení/zápis [IVbaProject](../../com.aspose.slides/ivbaproject).

**Vrací:**
[IVbaProject](../../com.aspose.slides/ivbaproject)
### setVbaProject(IVbaProject value) {#setVbaProject-com.aspose.slides.IVbaProject-}
```
public final void setVbaProject(IVbaProject value)
```

Získá nebo nastaví projekt VBA s makry prezentace. Čtení/zápis [IVbaProject](../../com.aspose.slides/ivbaproject).

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IVbaProject](../../com.aspose.slides/ivbaproject) |  |

### getHyperlinkQueries() {#getHyperlinkQueries--}
```
public final IHyperlinkQueries getHyperlinkQueries()
```

Poskytuje snadný přístup ke všem hypertextovým odkazům obsaženým ve všech snímcích prezentace (ne v hlavních, rozvržných, poznámkových snímcích). Pouze ke čtení [IHyperlinkQueries](../../com.aspose.slides/ihyperlinkqueries).

**Vrací:**
[IHyperlinkQueries](../../com.aspose.slides/ihyperlinkqueries)
### getViewProperties() {#getViewProperties--}
```
public final IViewProperties getViewProperties()
```

Získá vlastnosti zobrazení platné pro celou prezentaci. Pouze ke čtení [IViewProperties](../../com.aspose.slides/iviewproperties).

**Vrací:**
[IViewProperties](../../com.aspose.slides/iviewproperties)
### getFirstSlideNumber() {#getFirstSlideNumber--}
```
public final int getFirstSlideNumber()
```

Reprezentuje první číslo snímku v prezentaci

**Vrací:**
int
### setFirstSlideNumber(int value) {#setFirstSlideNumber-int-}
```
public final void setFirstSlideNumber(int value)
```

Reprezentuje první číslo snímku v prezentaci

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getSensitivityLabels() {#getSensitivityLabels--}
```
public final ISensitivityLabelCollection getSensitivityLabels()
```

Vrací kolekci štítků citlivosti aplikovaných na dokument prezentace. Pouze ke čtení [ISensitivityLabelCollection](../../com.aspose.slides/isensitivitylabelcollection).

--------------------

> ```
> Presentation pres = new Presentation("SomePresentation.pptx");
>  try {
>      ISensitivityLabelCollection sensitivityLabels = pres.getSensitivityLabels();
> 
>      // Vytiskněte použité štítky
>      for (ISensitivityLabel sensitivityLabel : sensitivityLabels)
>          System.out.println("Label Id " + sensitivityLabel.getId() + " from Azure AD site " + sensitivityLabel.getSiteId());
> 
>      // Přidejte nový štítek
>      String labelIdString = "{xxxxxxxx-xxxx-xxxx-xxxx-xxxxxxxxxxxx}"; // Získat ID štítku citlivosti z politiky
>      UUID siteIdGuid = UUID.fromString("{xxxxxxxx-xxxx-xxxx-xxxx-xxxxxxxxxxxx}"); // Získat identifikátor Azure AD stránky z politiky
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
| Parameter | Type | Description |
| --- | --- | --- |
| id | long | Id snímku. |

**Vrací:**
[IBaseSlide](../../com.aspose.slides/ibaseslide) - IBaseSlide object.
### getSourceFormat() {#getSourceFormat--}
```
public final int getSourceFormat()
```

Vrací informace o formátu, ze kterého byla prezentace načtena. Pouze ke čtení [SourceFormat](../../com.aspose.slides/sourceformat).

**Vrací:**
int
### getMasterTheme() {#getMasterTheme--}
```
public final IMasterTheme getMasterTheme()
```

Vrací hlavní motiv. Pouze ke čtení [IMasterTheme](../../com.aspose.slides/imastertheme).

--------------------

> ```
> The following examples shows how to change a theme effect by altering parts of elements of PowerPoint Presentation.
>  
>  //Instancujte objekt Presentation, který představuje soubor prezentace
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
| Parameter | Type | Description |
| --- | --- | --- |
| fname | java.lang.String | Cesta k vytvářenému souboru. |
| format | int | Formát exportovaných dat. |

### save(OutputStream stream, int format) {#save-java.io.OutputStream-int-}
```
public final void save(OutputStream stream, int format)
```

Uloží všechny snímky prezentace do proudu ve specifikovaném formátu.

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.OutputStream | Výstupní proud. |
| format | int | Formát exportovaných dat. |

### save(String fname, int format, ISaveOptions options) {#save-java.lang.String-int-com.aspose.slides.ISaveOptions-}
```
public final void save(String fname, int format, ISaveOptions options)
```

Uloží všechny snímky prezentace do souboru ve specifikovaném formátu a s dalšími možnostmi.

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| fname | java.lang.String | Cesta k vytvářenému souboru. |
| format | int | Formát exportovaných dat. |
| options | [ISaveOptions](../../com.aspose.slides/isaveoptions) | Další možnosti formátu. |

### save(OutputStream stream, int format, ISaveOptions options) {#save-java.io.OutputStream-int-com.aspose.slides.ISaveOptions-}
```
public final void save(OutputStream stream, int format, ISaveOptions options)
```

Uloží všechny snímky prezentace do proudu ve specifikovaném formátu a s dalšími možnostmi.

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.OutputStream | Výstupní proud. |
| format | int | Formát exportovaných dat. |
| options | [ISaveOptions](../../com.aspose.slides/isaveoptions) | Další možnosti formátu. |

### save(IXamlOptions options) {#save-com.aspose.slides.IXamlOptions-}
```
public final void save(IXamlOptions options)
```

Uloží všechny snímky prezentace do sady souborů představujících XAML značky.

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
| Parameter | Type | Description |
| --- | --- | --- |
| options | [IXamlOptions](../../com.aspose.slides/ixamloptions) | Možnosti formátu XAML. |

### getImages(IRenderingOptions options) {#getImages-com.aspose.slides.IRenderingOptions-}
```
public final IImage[] getImages(IRenderingOptions options)
```

Vrací objekty Image pro všechny snímky prezentace.

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Tiff možnosti. |

**Vrací:**
com.aspose.slides.IImage[] - Image objects.
### getImages(IRenderingOptions options, int[] slides) {#getImages-com.aspose.slides.IRenderingOptions-int---}
```
public final IImage[] getImages(IRenderingOptions options, int[] slides)
```

Vrací miniatury Image pro specifické snímky prezentace.

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Tiff možnosti. |
| slides | int[] | Pole s pozicemi snímků, počínaje 1. |

**Vrací:**
com.aspose.slides.IImage[] - Image objects.
### getImages(IRenderingOptions options, float scaleX, float scaleY) {#getImages-com.aspose.slides.IRenderingOptions-float-float-}
```
public final IImage[] getImages(IRenderingOptions options, float scaleX, float scaleY)
```

Vrací miniatury Image pro všechny snímky prezentace s vlastní škálou.

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Tiff možnosti. |
| scaleX | float | Hodnota pro škálování této miniatury ve směru osy X. |
| scaleY | float | Hodnota pro škálování této miniatury ve směru osy Y. |

**Vrací:**
com.aspose.slides.IImage[] - Image objects.
### getImages(IRenderingOptions options, int[] slides, float scaleX, float scaleY) {#getImages-com.aspose.slides.IRenderingOptions-int---float-float-}
```
public final IImage[] getImages(IRenderingOptions options, int[] slides, float scaleX, float scaleY)
```

Vrací miniatury Image pro specifické snímky prezentace s vlastní škálou.

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Tiff možnosti. |
| slides | int[] | Pole s pozicemi snímků, počínaje 1. |
| scaleX | float | Hodnota pro škálování této miniatury ve směru osy X. |
| scaleY | float | Hodnota pro škálování této miniatury ve směru osy Y. |

**Vrací:**
com.aspose.slides.IImage[] - Image objects.
### getImages(IRenderingOptions options, Size imageSize) {#getImages-com.aspose.slides.IRenderingOptions-com.aspose.slides.android.Size-}
```
public final IImage[] getImages(IRenderingOptions options, Size imageSize)
```

Vrací miniatury Image pro všechny snímky prezentace s určenou velikostí.

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Tiff možnosti. |
| imageSize | [Size](../../com.aspose.slides.android/size) | Velikost vytvářeného obrázku. |

**Vrací:**
com.aspose.slides.IImage[] - Image objects.
### getImages(IRenderingOptions options, int[] slides, Size imageSize) {#getImages-com.aspose.slides.IRenderingOptions-int---com.aspose.slides.android.Size-}
```
public final IImage[] getImages(IRenderingOptions options, int[] slides, Size imageSize)
```

Vrací miniatury Image pro specifické snímky prezentace s určenou velikostí.

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Tiff možnosti. |
| slides | int[] | Pole s pozicemi snímků, počínaje 1. |
| imageSize | [Size](../../com.aspose.slides.android/size) | Velikost vytvářeného obrázku. |

**Vrací:**
com.aspose.slides.IImage[] - Image objects.
### save(String fname, int[] slides, int format) {#save-java.lang.String-int---int-}
```
public final void save(String fname, int[] slides, int format)
```

Uloží specifikované snímky prezentace do souboru ve specifikovaném formátu s zachováním číslování stránek.

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| fname | java.lang.String | Cesta k vytvářenému souboru. |
| slides | int[] | Pole s pozicemi snímků, počínaje 1. |
| format | int | Formát exportovaných dat. |

### save(String fname, int[] slides, int format, ISaveOptions options) {#save-java.lang.String-int---int-com.aspose.slides.ISaveOptions-}
```
public final void save(String fname, int[] slides, int format, ISaveOptions options)
```

Uloží specifikované snímky prezentace do souboru ve specifikovaném formátu s zachováním číslování stránek.

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| fname | java.lang.String | Cesta k vytvářenému souboru. |
| slides | int[] | Pole s pozicemi snímků, počínaje 1. |
| format | int | Formát exportovaných dat. |
| options | [ISaveOptions](../../com.aspose.slides/isaveoptions) | Další možnosti formátu. |

### save(OutputStream stream, int[] slides, int format) {#save-java.io.OutputStream-int---int-}
```
public final void save(OutputStream stream, int[] slides, int format)
```

Uloží specifikované snímky prezentace do proudu ve specifikovaném formátu s zachováním číslování stránek.

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.OutputStream | Výstupní proud. |
| slides | int[] | Pole s pozicemi snímků, počínaje 1. |
| format | int | Formát exportovaných dat. |

### save(OutputStream stream, int[] slides, int format, ISaveOptions options) {#save-java.io.OutputStream-int---int-com.aspose.slides.ISaveOptions-}
```
public final void save(OutputStream stream, int[] slides, int format, ISaveOptions options)
```

Uloží specifikované snímky prezentace do proudu ve specifikovaném formátu s zachováním číslování stránek.

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


**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.OutputStream | Výstupní proud. |
| slides | int[] | Pole s pozicemi snímků, počínaje 1. |
| format | int | Formát exportovaných dat. |
| options | [ISaveOptions](../../com.aspose.slides/isaveoptions) | Další možnosti formátu. |

### joinPortionsWithSameFormatting() {#joinPortionsWithSameFormatting--}
```
public final void joinPortionsWithSameFormatting()
```

Spojuje běhy s identickým formátováním ve všech odstavcích ve všech vhodných tvarech ve všech snímcích.

### dispose() {#dispose--}
```
public final void dispose()
```

Uvolňuje všechny zdroje používané tímto objektem Presentation.

### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

Vrací nadřazenou prezentaci textu. Pouze ke čtení [IPresentation](../../com.aspose.slides/ipresentation).

**Vrací:**
[IPresentation](../../com.aspose.slides/ipresentation)
### highlightText(String text, Integer highlightColor) {#highlightText-java.lang.String-java.lang.Integer-}
```
public final void highlightText(String text, Integer highlightColor)
```

Zvětrazní všechny výskyty ukázkového textu zadanou barvou.

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
| Parameter | Type | Description |
| --- | --- | --- |
| text | java.lang.String | Text k zvýraznění. |
| highlightColor | java.lang.Integer | Barva pro zvýraznění textu. |

### highlightText(String text, Integer highlightColor, ITextSearchOptions options, IFindResultCallback callback) {#highlightText-java.lang.String-java.lang.Integer-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-}
```
public final void highlightText(String text, Integer highlightColor, ITextSearchOptions options, IFindResultCallback callback)
```

Zvětrazní všechny výskyty ukázkového textu zadanou barvou.

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
| Parameter | Type | Description |
| --- | --- | --- |
| text | java.lang.String | Text k zvýraznění. |
| highlightColor | java.lang.Integer | Barva pro zvýraznění textu. |
| options | [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions) | Možnosti hledání textu [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions). |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | Objekt zpětného volání pro přijímání výsledků vyhledávání [IFindResultCallback](../../com.aspose.slides/ifindresultcallback). |

### highlightRegex(Pattern regex, Integer highlightColor, IFindResultCallback callback) {#highlightRegex-java.util.regex.Pattern-java.lang.Integer-com.aspose.slides.IFindResultCallback-}
```
public final void highlightRegex(Pattern regex, Integer highlightColor, IFindResultCallback callback)
```

Zvětrazní všechny výskyty regulárního výrazu zadanou barvou.

> ```
> The following code sample shows how to highlight text in a PowerPoint Presentation using a regular expression.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      Pattern regex = Pattern.compile("\\b[^\\s]{10,}\\b");
>      // zvýraznění všech slov dlouhých 10 a více znaků
>      presentation.highlightRegex(regex, Color.BLUE, null);
>      presentation.save("SomePresentation-out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| regex | java.util.regex.Pattern | Regulární výraz java.util.regex.Pattern pro získání řetězců k zvýraznění. |
| highlightColor | java.lang.Integer | Barva pro zvýraznění textu. |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | Objekt zpětného volání pro přijímání výsledků vyhledávání [IFindResultCallback](../../com.aspose.slides/ifindresultcallback). |

### replaceText(String oldText, String newText, ITextSearchOptions options, IFindResultCallback callback) {#replaceText-java.lang.String-java.lang.String-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-}
```
public final void replaceText(String oldText, String newText, ITextSearchOptions options, IFindResultCallback callback)
```

Nahrazuje všechny výskyty zadaného textu jiným zadaným textem.

> ```
> The following sample code shows how to replace one specified string with another specified string.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx")
>  try {
>      TextSearchOptions textSearchOptions = new TextSearchOptions();
>      textSearchOptions.setWholeWordsOnly(true);
>      // Nahradí všechny samostatné výskyty 'the' řetězcem '***'
>      presentation.replaceText("the", "***", textSearchOptions, null);
>      presentation.save("SomePresentation-out2.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| oldText | java.lang.String | Řetězec, který má být nahrazen. |
| newText | java.lang.String | Řetězec, který nahradí všechny výskyty oldText. |
| options | [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions) | Možnosti hledání textu [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions). |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | Objekt zpětného volání pro přijímání výsledků vyhledávání [IFindResultCallback](../../com.aspose.slides/ifindresultcallback). |

### replaceRegex(Pattern regex, String newText, IFindResultCallback callback) {#replaceRegex-java.util.regex.Pattern-java.lang.String-com.aspose.slides.IFindResultCallback-}
```
public final void replaceRegex(Pattern regex, String newText, IFindResultCallback callback)
```

Nahrazuje všechny výskyty regulárního výrazu zadaným řetězcem.

> ```
> The following code sample shows how to replace text using regular expression with the specified string.
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      Pattern regex = Pattern.compile("\\b[^\\s]{10,}\\b");
>      // Nahraďte všechna slova s 10 a více znaky řetězcem '***'
>      presentation.replaceRegex(regex, "***", null);
>      presentation.save("SomePresentation-out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| regex | java.util.regex.Pattern | Regulární výraz java.util.regex.Pattern pro získání řetězců k nahrazení. |
| newText | java.lang.String | Řetězec, který nahradí všechny výskyty řetězců, které mají být nahrazeny. |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | Objekt zpětného volání pro přijímání výsledků vyhledávání [IFindResultCallback](../../com.aspose.slides/ifindresultcallback). |