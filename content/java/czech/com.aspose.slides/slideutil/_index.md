---
title: SlideUtil
second_title: Aspose.Slides pro Java – referenční příručka API
description: Nabízí metody, které pomáhají vyhledávat tvary a text v prezentaci.
type: docs
url: /cs/com.aspose.slides/slideutil/
---
**Dědičnost:**
java.lang.Object
```
public class SlideUtil
```

Nabízí metody, které pomáhají vyhledávat tvary a text v prezentaci.
## Konstruktory

| Konstruktor | Popis |
| --- | --- |
| [SlideUtil()](#SlideUtil--) |  |
## Metody

| Metoda | Popis |
| --- | --- |
| [findShape(IPresentation pres, String altText)](#findShape-com.aspose.slides.IPresentation-java.lang.String-) | Najde tvar podle alternativního textu v prezentaci PPTX. |
| [findShape(IBaseSlide slide, String altText)](#findShape-com.aspose.slides.IBaseSlide-java.lang.String-) | Najde tvar podle alternativního textu na snímku v prezentaci PPTX. |
| [findShapesByPlaceholderType(IBaseSlide slide, byte placeholderType)](#findShapesByPlaceholderType-com.aspose.slides.IBaseSlide-byte-) | Vyhledá všechny tvary na určeném snímku, které odpovídají zadanému typu zástupce. |
| [alignShapes(int alignmentType, boolean alignToSlide, IBaseSlide slide)](#alignShapes-int-boolean-com.aspose.slides.IBaseSlide-) | Změní umístění všech tvarů na snímku. |
| [alignShapes(int alignmentType, boolean alignToSlide, IBaseSlide slide, int[] shapeIndexes)](#alignShapes-int-boolean-com.aspose.slides.IBaseSlide-int---) | Změní umístění vybraných tvarů na snímku. |
| [alignShapes(int alignmentType, boolean alignToSlide, IGroupShape groupShape)](#alignShapes-int-boolean-com.aspose.slides.IGroupShape-) | Změní umístění všech tvarů ve skupinovém tvaru. |
| [alignShapes(int alignmentType, boolean alignToSlide, IGroupShape groupShape, int[] shapeIndexes)](#alignShapes-int-boolean-com.aspose.slides.IGroupShape-int---) | Změní umístění vybraných tvarů ve skupinovém tvaru. |
| [findAndReplaceText(IPresentation presentation, boolean withMasters, String find, String replace)](#findAndReplaceText-com.aspose.slides.IPresentation-boolean-java.lang.String-java.lang.String-) | Vyhledá a nahradí text v prezentaci s daným formátem |
| [findAndReplaceText(IPresentation presentation, boolean withMasters, String find, String replace, PortionFormat format)](#findAndReplaceText-com.aspose.slides.IPresentation-boolean-java.lang.String-java.lang.String-com.aspose.slides.PortionFormat-) | Vyhledá a nahradí text v prezentaci s daným formátem |
| [getAllTextBoxes(IBaseSlide slide)](#getAllTextBoxes-com.aspose.slides.IBaseSlide-) | Vrací všechny textové rámy na snímku v prezentaci PPTX. |
| [getTextBoxesContainsText(IBaseSlide slide, String text, boolean checkPlaceholderText)](#getTextBoxesContainsText-com.aspose.slides.IBaseSlide-java.lang.String-boolean-) | Vrací všechny textové rámy na určeném snímku, které obsahují zadaný text. |
| [getAllTextFrames(IPresentation pres, boolean withMasters)](#getAllTextFrames-com.aspose.slides.IPresentation-boolean-) | Vrací všechny textové rámy v prezentaci PPTX. |
| [toSaveFormat(int format)](#toSaveFormat-int-) | Převede formát zdrojového souboru na odpovídající [SaveFormat](../../com.aspose.slides/saveformat). |
### SlideUtil() {#SlideUtil--}
```
public SlideUtil()
```


### findShape(IPresentation pres, String altText) {#findShape-com.aspose.slides.IPresentation-java.lang.String-}
```
public static IShape findShape(IPresentation pres, String altText)
```


Najde tvar podle alternativního textu v prezentaci PPTX.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| pres | [IPresentation](../../com.aspose.slides/ipresentation) | Prohledávaná prezentace. |
| altText | java.lang.String | Alternativní text tvaru. |

**Vrací:**
[IShape](../../com.aspose.slides/ishape) - Shape nebo null.
### findShape(IBaseSlide slide, String altText) {#findShape-com.aspose.slides.IBaseSlide-java.lang.String-}
```
public static IShape findShape(IBaseSlide slide, String altText)
```


Najde tvar podle alternativního textu na snímku v prezentaci PPTX.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| slide | [IBaseSlide](../../com.aspose.slides/ibaseslide) | Prohledávaný snímek. |
| altText | java.lang.String | Alternativní text tvaru. |

**Vrací:**
[IShape](../../com.aspose.slides/ishape) - Shape nebo null.
### findShapesByPlaceholderType(IBaseSlide slide, byte placeholderType) {#findShapesByPlaceholderType-com.aspose.slides.IBaseSlide-byte-}
```
public static IShape[] findShapesByPlaceholderType(IBaseSlide slide, byte placeholderType)
```


Vyhledá všechny tvary na určeném snímku, které odpovídají zadanému typu zástupce.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| slide | [IBaseSlide](../../com.aspose.slides/ibaseslide) | Snímek, ve kterém se vyhledávají tvary. |
| placeholderType | byte | Typ zástupce, podle kterého se tvary filtrují. |

**Vrací:**
com.aspose.slides.IShape[] - Pole objektů [IShape](../../com.aspose.slides/ishape) odpovídajících zadanému typu zástupce.
### alignShapes(int alignmentType, boolean alignToSlide, IBaseSlide slide) {#alignShapes-int-boolean-com.aspose.slides.IBaseSlide-}
```
public static void alignShapes(int alignmentType, boolean alignToSlide, IBaseSlide slide)
```


Změní umístění všech tvarů na snímku. Zarovná tvary k okrajům či k hraně snímku, nebo je zarovná relativně k sobě navzájem.

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

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| alignmentType | int | Určuje, jaký typ zarovnání bude použit. |
| alignToSlide | boolean | Pokud je true, tvary budou zarovnány relativně k okrajům snímku. |
| slide | [IBaseSlide](../../com.aspose.slides/ibaseslide) | Nadřazený snímek. |

### alignShapes(int alignmentType, boolean alignToSlide, IBaseSlide slide, int[] shapeIndexes) {#alignShapes-int-boolean-com.aspose.slides.IBaseSlide-int---}
```
public static void alignShapes(int alignmentType, boolean alignToSlide, IBaseSlide slide, int[] shapeIndexes)
```


Změní umístění vybraných tvarů na snímku. Zarovná tvary k okrajům či k hraně snímku, nebo je zarovná relativně k sobě navzájem.

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

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| alignmentType | int | Určuje, jaký typ zarovnání bude použit. |
| alignToSlide | boolean | Pokud je true, tvary budou zarovnány relativně k okrajům snímku. |
| slide | [IBaseSlide](../../com.aspose.slides/ibaseslide) | Nadřazený snímek. |
| shapeIndexes | int[] | Indexy tvarů, které mají být zarovnány. |

### alignShapes(int alignmentType, boolean alignToSlide, IGroupShape groupShape) {#alignShapes-int-boolean-com.aspose.slides.IGroupShape-}
```
public static void alignShapes(int alignmentType, boolean alignToSlide, IGroupShape groupShape)
```


Změní umístění všech tvarů ve skupinovém tvaru. Zarovná tvary k okrajům či k hraně snímku, nebo je zarovná relativně k sobě navzájem.

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

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| alignmentType | int | Určuje, jaký typ zarovnání bude použit. |
| alignToSlide | boolean | Pokud je true, tvary budou zarovnány relativně k okrajům snímku. |
| groupShape | [IGroupShape](../../com.aspose.slides/igroupshape) | Nadřazený skupinový tvar. |

### alignShapes(int alignmentType, boolean alignToSlide, IGroupShape groupShape, int[] shapeIndexes) {#alignShapes-int-boolean-com.aspose.slides.IGroupShape-int---}
```
public static void alignShapes(int alignmentType, boolean alignToSlide, IGroupShape groupShape, int[] shapeIndexes)
```


Změní umístění vybraných tvarů ve skupinovém tvaru. Zarovná tvary k okrajům či k hraně snímku, nebo je zarovná relativně k sobě navzájem.

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

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| alignmentType | int | Určuje, jaký typ zarovnání bude použit. |
| alignToSlide | boolean | Pokud je true, tvary budou zarovnány relativně k okrajům snímku. |
| groupShape | [IGroupShape](../../com.aspose.slides/igroupshape) | Nadřazený skupinový tvar. |
| shapeIndexes | int[] | Indexy tvarů, které mají být zarovnány. |

### findAndReplaceText(IPresentation presentation, boolean withMasters, String find, String replace) {#findAndReplaceText-com.aspose.slides.IPresentation-boolean-java.lang.String-java.lang.String-}
```
public static void findAndReplaceText(IPresentation presentation, boolean withMasters, String find, String replace)
```


Vyhledá a nahradí text v prezentaci s daným formátem

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

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| presentation | [IPresentation](../../com.aspose.slides/ipresentation) | Prohledávaná prezentace. |
| withMasters | boolean | Určuje, zda mají být skenovány master snímky. |
| find | java.lang.String | Řetězcová hodnota k nalezení. |
| replace | java.lang.String | Řetězcová hodnota pro nahrazení. znak nalezeného řetězce |

### findAndReplaceText(IPresentation presentation, boolean withMasters, String find, String replace, PortionFormat format) {#findAndReplaceText-com.aspose.slides.IPresentation-boolean-java.lang.String-java.lang.String-com.aspose.slides.PortionFormat-}
```
public static void findAndReplaceText(IPresentation presentation, boolean withMasters, String find, String replace, PortionFormat format)
```


Vyhledá a nahradí text v prezentaci s daným formátem

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

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| presentation | [IPresentation](../../com.aspose.slides/ipresentation) | Prohledávaná prezentace. |
| withMasters | boolean | Určuje, zda mají být skenovány master snímky. |
| find | java.lang.String | Řetězcová hodnota k nalezení. |
| replace | java.lang.String | Řetězcová hodnota pro nahrazení. |
| format | [PortionFormat](../../com.aspose.slides/portionformat) | Formát pro nahrazení části textu. Pokud je null, bude použit formát prvního znaku nalezeného řetězce. |

### getAllTextBoxes(IBaseSlide slide) {#getAllTextBoxes-com.aspose.slides.IBaseSlide-}
```
public static ITextFrame[] getAllTextBoxes(IBaseSlide slide)
```


Vrací všechny textové rámy na snímku v prezentaci PPTX.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| slide | [IBaseSlide](../../com.aspose.slides/ibaseslide) | Prohledávaný snímek. |

**Vrací:**
com.aspose.slides.ITextFrame[] - Pole objektů [TextFrame](../../com.aspose.slides/textframe).

### getTextBoxesContainsText(IBaseSlide slide, String text, boolean checkPlaceholderText) {#getTextBoxesContainsText-com.aspose.slides.IBaseSlide-java.lang.String-boolean-}
```
public static ITextFrame[] getTextBoxesContainsText(IBaseSlide slide, String text, boolean checkPlaceholderText)
```


Vrací všechny textové rámy na určeném snímku, které obsahují zadaný text.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| slide | [IBaseSlide](../../com.aspose.slides/ibaseslide) | Snímek, ve kterém se hledá. |
| text | java.lang.String | Text, který se má vyhledat v textových rámech. |
| checkPlaceholderText | boolean | Určuje, zda zahrnout textové rámy, které jsou prázdné, ale jejichž text zástupce obsahuje hledaný text. |

**Vrací:**
com.aspose.slides.ITextFrame[] - Pole objektů [ITextFrame](../../com.aspose.slides/itextframe) obsahujících zadaný text.

### getAllTextFrames(IPresentation pres, boolean withMasters) {#getAllTextFrames-com.aspose.slides.IPresentation-boolean-}
```
public static ITextFrame[] getAllTextFrames(IPresentation pres, boolean withMasters)
```


Vrací všechny textové rámy v prezentaci PPTX.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| pres | [IPresentation](../../com.aspose.slides/ipresentation) | Prohledávaná prezentace. |
| withMasters | boolean | Určuje, zda mají být skenovány master snímky. |

**Vrací:**
com.aspose.slides.ITextFrame[] - Pole objektů [TextFrame](../../com.aspose.slides/textframe).

### toSaveFormat(int format) {#toSaveFormat-int-}
```
public static int toSaveFormat(int format)
```


Převede formát zdrojového souboru na odpovídající [SaveFormat](../../com.aspose.slides/saveformat).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| format | int | Formát zdrojového souboru. |

**Vrací:**
int - Odpovídající hodnotu [SaveFormat](../../com.aspose.slides/saveformat).