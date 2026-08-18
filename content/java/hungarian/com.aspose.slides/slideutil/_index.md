---
title: SlideUtil
second_title: Aspose.Slides for Java API Referencia
description: Olyan metódusokat kínál, amelyek segítenek alakzatok és szöveg keresésében egy bemutatóban.
type: docs
url: /hu/com.aspose.slides/slideutil/
---
**Öröklődés:**
java.lang.Object
```
public class SlideUtil
```

Olyan metódusokat kínál, amelyek segítenek alakzatok és szöveg keresésében egy bemutatóban.
## Konstruktorok

| Konstruktor | Leírás |
| --- | --- |
| [SlideUtil()](#SlideUtil--) |  |
## Metódusok

| Metódus | Leírás |
| --- | --- |
| [findShape(IPresentation pres, String altText)](#findShape-com.aspose.slides.IPresentation-java.lang.String-) | Alakzat keresése alternatív szöveggel PPTX bemutatóban. |
| [findShape(IBaseSlide slide, String altText)](#findShape-com.aspose.slides.IBaseSlide-java.lang.String-) | Alakzat keresése alternatív szöveggel egy dián egy PPTX bemutatóban. |
| [findShapesByPlaceholderType(IBaseSlide slide, byte placeholderType)](#findShapesByPlaceholderType-com.aspose.slides.IBaseSlide-byte-) | Az adott dián található összes alakzat keresése, amelyek megfelelnek a megadott helyőrző típusnak. |
| [alignShapes(int alignmentType, boolean alignToSlide, IBaseSlide slide)](#alignShapes-int-boolean-com.aspose.slides.IBaseSlide-) | Az összes alakzat elhelyezésének módosítása a dián. |
| [alignShapes(int alignmentType, boolean alignToSlide, IBaseSlide slide, int[] shapeIndexes)](#alignShapes-int-boolean-com.aspose.slides.IBaseSlide-int---) | Az összes alakzat elhelyezésének módosítása a dián. |
| [alignShapes(int alignmentType, boolean alignToSlide, IGroupShape groupShape)](#alignShapes-int-boolean-com.aspose.slides.IGroupShape-) | Az összes alakzat elhelyezésének módosítása a csoport alakzaton belül. |
| [alignShapes(int alignmentType, boolean alignToSlide, IGroupShape groupShape, int[] shapeIndexes)](#alignShapes-int-boolean-com.aspose.slides.IGroupShape-int---) | Az összes alakzat elhelyezésének módosítása a csoport alakzaton belül. |
| [findAndReplaceText(IPresentation presentation, boolean withMasters, String find, String replace)](#findAndReplaceText-com.aspose.slides.IPresentation-boolean-java.lang.String-java.lang.String-) | Szöveg keresése és cseréje a bemutatóban a megadott formátummal |
| [findAndReplaceText(IPresentation presentation, boolean withMasters, String find, String replace, PortionFormat format)](#findAndReplaceText-com.aspose.slides.IPresentation-boolean-java.lang.String-java.lang.String-com.aspose.slides.PortionFormat-) | Szöveg keresése és cseréje a bemutatóban a megadott formátummal |
| [getAllTextBoxes(IBaseSlide slide)](#getAllTextBoxes-com.aspose.slides.IBaseSlide-) | Visszaadja az összes szövegdobozt egy dián egy PPTX bemutatóban. |
| [getTextBoxesContainsText(IBaseSlide slide, String text, boolean checkPlaceholderText)](#getTextBoxesContainsText-com.aspose.slides.IBaseSlide-java.lang.String-boolean-) | Visszaadja az összes szövegdobozt az adott dián, amely tartalmazza a megadott szöveget. |
| [getAllTextFrames(IPresentation pres, boolean withMasters)](#getAllTextFrames-com.aspose.slides.IPresentation-boolean-) | Visszaadja az összes szövegdobozt egy PPTX bemutatóban. |
| [toSaveFormat(int format)](#toSaveFormat-int-) | Átalakítja a forrás fájlformátumot a megfelelő [SaveFormat](../../com.aspose.slides/saveformat)-ra. |
### SlideUtil() {#SlideUtil--}
```
public SlideUtil()
```


### findShape(IPresentation pres, String altText) {#findShape-com.aspose.slides.IPresentation-java.lang.String-}
```
public static IShape findShape(IPresentation pres, String altText)
```


Alakzat keresése alternatív szöveggel egy PPTX bemutatóban.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| pres | [IPresentation](../../com.aspose.slides/ipresentation) | Beolvasott bemutató. |
| altText | java.lang.String | Alakzat alternatív szövege. |

**Visszatérési érték:**
[IShape](../../com.aspose.slides/ishape) - Shape vagy null.
### findShape(IBaseSlide slide, String altText) {#findShape-com.aspose.slides.IBaseSlide-java.lang.String-}
```
public static IShape findShape(IBaseSlide slide, String altText)
```


Alakzat keresése alternatív szöveggel egy dián egy PPTX bemutatóban.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| slide | [IBaseSlide](../../com.aspose.slides/ibaseslide) | Beolvasott dia. |
| altText | java.lang.String | Alakzat alternatív szövege. |

**Visszatérési érték:**
[IShape](../../com.aspose.slides/ishape) - Shape vagy null.
### findShapesByPlaceholderType(IBaseSlide slide, byte placeholderType) {#findShapesByPlaceholderType-com.aspose.slides.IBaseSlide-byte-}
```
public static IShape[] findShapesByPlaceholderType(IBaseSlide slide, byte placeholderType)
```


Az adott dián található összes alakzat keresése, amelyek megfelelnek a megadott helyőrző típusnak.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| slide | [IBaseSlide](../../com.aspose.slides/ibaseslide) | A dia, ahol alakzatokat keres. |
| placeholderType | byte | A helyőrző típusa, amellyel az alakzatok szűrésre kerülnek. |

**Visszatérési érték:**
com.aspose.slides.IShape[] - A megadott helyőrző típusnak megfelelő [IShape](../../com.aspose.slides/ishape) objektumok tömbje.
### alignShapes(int alignmentType, boolean alignToSlide, IBaseSlide slide) {#alignShapes-int-boolean-com.aspose.slides.IBaseSlide-}
```
public static void alignShapes(int alignmentType, boolean alignToSlide, IBaseSlide slide)
```


Az összes alakzat elhelyezésének módosítása a dián. Az alakzatokat a margókhoz vagy a dia széléhez igazítja, vagy egymáshoz viszonyítva igazítja őket.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      SlideUtil.alignShapes(ShapesAlignmentType.AlignBottom, true, pres.getSlides().get_Item(0));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| alignmentType | int | Meghatározza, hogy milyen típusú igazítást alkalmazzák. |
| alignToSlide | boolean | Ha igaz, az alakzatok a dia széleihez képest lesznek igazítva. |
| slide | [IBaseSlide](../../com.aspose.slides/ibaseslide) | Szülő dia. |

### alignShapes(int alignmentType, boolean alignToSlide, IBaseSlide slide, int[] shapeIndexes) {#alignShapes-int-boolean-com.aspose.slides.IBaseSlide-int---}
```
public static void alignShapes(int alignmentType, boolean alignToSlide, IBaseSlide slide, int[] shapeIndexes)
```


Az összes alakzat elhelyezésének módosítása a dián. Az alakzatokat a margókhoz vagy a dia széléhez igazítja, vagy egymáshoz viszonyítva igazítja őket.

--------------------

> ```
> Example:
>   
>   Presentation pres = new Presentation("pres.pptx");
>   try {
>      ISlide slide = pres.getSlides().get_Item(0);
>      IShape shape1 = slide.getShapes().get_Item(0);
>      IShape shape2 = slide.getShapes().get_Item(1);
>      SlideUtil.alignShapes(ShapesAlignmentType.AlignBottom, false, pres.getSlides().get_Item(0), new int[]
>      {
>          slide.getShapes().indexOf(shape1),
>          slide.getShapes().indexOf(shape2)
>      });
>   } finally {
>      if (pres != null) pres.dispose();
>   }
> ```

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| alignmentType | int | Meghatározza, hogy milyen típusú igazítást alkalmazzák. |
| alignToSlide | boolean | Ha igaz, az alakzatok a dia széleihez képest lesznek igazítva. |
| slide | [IBaseSlide](../../com.aspose.slides/ibaseslide) | Szülő dia. |
| shapeIndexes | int[] | Az igazítandó alakzatok indexei. |

### alignShapes(int alignmentType, boolean alignToSlide, IGroupShape groupShape) {#alignShapes-int-boolean-com.aspose.slides.IGroupShape-}
```
public static void alignShapes(int alignmentType, boolean alignToSlide, IGroupShape groupShape)
```


Az összes alakzat elhelyezésének módosítása a csoport alakzaton belül. Az alakzatokat a margókhoz vagy a dia széléhez igazítja, vagy egymáshoz viszonyítva igazítja őket.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      ISlide slide = pres.getSlides().get_Item(0);
>      SlideUtil.alignShapes(ShapesAlignmentType.AlignLeft, false, (GroupShape) slide.getShapes().get_Item(0));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| alignmentType | int | Meghatározza, hogy milyen típusú igazítást alkalmazzák. |
| alignToSlide | boolean | Ha igaz, az alakzatok a dia széleihez képest lesznek igazítva. |
| groupShape | [IGroupShape](../../com.aspose.slides/igroupshape) | Szülő csoport alakzat. |

### alignShapes(int alignmentType, boolean alignToSlide, IGroupShape groupShape, int[] shapeIndexes) {#alignShapes-int-boolean-com.aspose.slides.IGroupShape-int---}
```
public static void alignShapes(int alignmentType, boolean alignToSlide, IGroupShape groupShape, int[] shapeIndexes)
```


Az összes alakzat elhelyezésének módosítása a csoport alakzaton belül. Az alakzatokat a margókhoz vagy a dia széléhez igazítja, vagy egymáshoz viszonyítva igazítja őket.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      ISlide slide = pres.getSlides().get_Item(0);
>      SlideUtil.alignShapes(ShapesAlignmentType.AlignLeft, false, (GroupShape)slide.getShapes().get_Item(0), new int[] { 0, 2 });
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| alignmentType | int | Meghatározza, hogy milyen típusú igazítást alkalmazzák. |
| alignToSlide | boolean | Ha igaz, az alakzatok a dia széleihez képest lesznek igazítva. |
| groupShape | [IGroupShape](../../com.aspose.slides/igroupshape) | Szülő csoport alakzat. |
| shapeIndexes | int[] | Az igazítandó alakzatok indexei. |

### findAndReplaceText(IPresentation presentation, boolean withMasters, String find, String replace) {#findAndReplaceText-com.aspose.slides.IPresentation-boolean-java.lang.String-java.lang.String-}
```
public static void findAndReplaceText(IPresentation presentation, boolean withMasters, String find, String replace)
```


Szöveg keresése és cseréje a bemutatóban a megadott formátummal

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      PortionFormat format = new PortionFormat();
>      format.setFontHeight(24f);
>      format.setFontItalic(NullableBool.True);
>      format.getFillFormat().setFillType(FillType.Solid);
>      format.getFillFormat().getSolidFillColor().setColor(Color.RED);
> 
>      SlideUtil.findAndReplaceText(pres, true, "[this block] ", "my text ", format);
>      pres.save("replaced.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| presentation | [IPresentation](../../com.aspose.slides/ipresentation) | Beolvasott bemutató. |
| withMasters | boolean | Meghatározza, hogy a minta diák is legyenek beolvasva. |
| find | java.lang.String | A keresendő karakterlánc. |
| replace | java.lang.String | A cserélendő karakterlánc. |

### findAndReplaceText(IPresentation presentation, boolean withMasters, String find, String replace, PortionFormat format) {#findAndReplaceText-com.aspose.slides.IPresentation-boolean-java.lang.String-java.lang.String-com.aspose.slides.PortionFormat-}
```
public static void findAndReplaceText(IPresentation presentation, boolean withMasters, String find, String replace, PortionFormat format)
```


Szöveg keresése és cseréje a bemutatóban a megadott formátummal

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      PortionFormat format = new PortionFormat();
>      format.setFontHeight(24f);
>      format.setFontItalic(NullableBool.True);
>      format.getFillFormat().setFillType(FillType.Solid);
>      format.getFillFormat().getSolidFillColor().setColor(Color.RED);
> 
>      SlideUtil.findAndReplaceText(pres, true, "[this block] ", "my text ", format);
>      pres.save("replaced.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| presentation | [IPresentation](../../com.aspose.slides/ipresentation) | Beolvasott bemutató. |
| withMasters | boolean | Meghatározza, hogy a minta diák is legyenek beolvasva. |
| find | java.lang.String | A keresendő karakterlánc. |
| replace | java.lang.String | A cserélendő karakterlánc. |
| format | [PortionFormat](../../com.aspose.slides/portionformat) | A cserélt szövegrész formátuma. Ha null, akkor a megtalált szöveg első karakterének formátuma lesz használva. |

### getAllTextBoxes(IBaseSlide slide) {#getAllTextBoxes-com.aspose.slides.IBaseSlide-}
```
public static ITextFrame[] getAllTextBoxes(IBaseSlide slide)
```


Visszaadja az összes szövegdobozt egy dián egy PPTX bemutatóban.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| slide | [IBaseSlide](../../com.aspose.slides/ibaseslide) | Beolvasott dia. |

**Visszatérési érték:**
com.aspose.slides.ITextFrame[] - A [TextFrame](../../com.aspose.slides/textframe) objektumok tömbje.
### getTextBoxesContainsText(IBaseSlide slide, String text, boolean checkPlaceholderText) {#getTextBoxesContainsText-com.aspose.slides.IBaseSlide-java.lang.String-boolean-}
```
public static ITextFrame[] getTextBoxesContainsText(IBaseSlide slide, String text, boolean checkPlaceholderText)
```


Visszaadja az összes szövegdobozt az adott dián, amely tartalmazza a megadott szöveget.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| slide | [IBaseSlide](../../com.aspose.slides/ibaseslide) | A dia, ahol keres. |
| text | java.lang.String | A szöveg, amelyet a szövegdobozokban keresnek. |
| checkPlaceholderText | boolean | Megadja, hogy üres szövegdobozokat is bele kell-e venni, ha azok helyőrző szövege tartalmazza a keresett szöveget. |

**Visszatérési érték:**
com.aspose.slides.ITextFrame[] - A [ITextFrame](../../com.aspose.slides/itextframe) objektumok tömbje, amely a megadott szöveget tartalmazza.
### getAllTextFrames(IPresentation pres, boolean withMasters) {#getAllTextFrames-com.aspose.slides.IPresentation-boolean-}
```
public static ITextFrame[] getAllTextFrames(IPresentation pres, boolean withMasters)
```


Visszaadja az összes szövegdobozt egy PPTX bemutatóban.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| pres | [IPresentation](../../com.aspose.slides/ipresentation) | Beolvasott bemutató. |
| withMasters | boolean | Meghatározza, hogy a minta diák is legyenek beolvasva. |

**Visszatérési érték:**
com.aspose.slides.ITextFrame[] - A [TextFrame](../../com.aspose.slides/textframe) objektumok tömbje.
### toSaveFormat(int format) {#toSaveFormat-int-}
```
public static int toSaveFormat(int format)
```


Átalakítja a forrás fájlformátumot a megfelelő [SaveFormat](../../com.aspose.slides/saveformat)-ra.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| format | int | A forrás fájlformátuma. |

**Visszatérési érték:**
int - A megfelelő [SaveFormat](../../com.aspose.slides/saveformat) érték.