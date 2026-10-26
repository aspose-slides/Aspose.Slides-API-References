---
title: SlideUtil
second_title: Aspose.Slides pro Android prostřednictvím Java API Reference
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
| [findShape(IPresentation pres, String altText)](#findShape-com.aspose.slides.IPresentation-java.lang.String-) | Najde tvar podle alternativního textu v PPTX prezentaci. |
| [findShape(IBaseSlide slide, String altText)](#findShape-com.aspose.slides.IBaseSlide-java.lang.String-) | Najde tvar podle alternativního textu na snímku v PPTX prezentaci. |
| [findShapesByPlaceholderType(IBaseSlide slide, byte placeholderType)](#findShapesByPlaceholderType-com.aspose.slides.IBaseSlide-byte-) | Vyhledá všechny tvary na určeném snímku, které odpovídají zadanému typu zástupce. |
| [alignShapes(int alignmentType, boolean alignToSlide, IBaseSlide slide)](#alignShapes-int-boolean-com.aspose.slides.IBaseSlide-) | Mění umístění všech tvarů na snímku. |
| [alignShapes(int alignmentType, boolean alignToSlide, IBaseSlide slide, int[] shapeIndexes)](#alignShapes-int-boolean-com.aspose.slides.IBaseSlide-int---) | Mění umístění vybraných tvarů na snímku. |
| [alignShapes(int alignmentType, boolean alignToSlide, IGroupShape groupShape)](#alignShapes-int-boolean-com.aspose.slides.IGroupShape-) | Mění umístění všech tvarů uvnitř skupinového tvaru. |
| [alignShapes(int alignmentType, boolean alignToSlide, IGroupShape groupShape, int[] shapeIndexes)](#alignShapes-int-boolean-com.aspose.slides.IGroupShape-int---) | Mění umístění vybraných tvarů uvnitř skupinového tvaru. |
| [findAndReplaceText(IPresentation presentation, boolean withMasters, String find, String replace)](#findAndReplaceText-com.aspose.slides.IPresentation-boolean-java.lang.String-java.lang.String-) | Najde a nahradí text v prezentaci s daným formátem |
| [findAndReplaceText(IPresentation presentation, boolean withMasters, String find, String replace, PortionFormat format)](#findAndReplaceText-com.aspose.slides.IPresentation-boolean-java.lang.String-java.lang.String-com.aspose.slides.PortionFormat-) | Najde a nahradí text v prezentaci s daným formátem |
| [getAllTextBoxes(IBaseSlide slide)](#getAllTextBoxes-com.aspose.slides.IBaseSlide-) | Vrací všechny textové rámečky na snímku v PPTX prezentaci. |
| [getTextBoxesContainsText(IBaseSlide slide, String text, boolean checkPlaceholderText)](#getTextBoxesContainsText-com.aspose.slides.IBaseSlide-java.lang.String-boolean-) | Vrací všechny textové rámečky na určeném snímku, které obsahují daný text. |
| [getAllTextFrames(IPresentation pres, boolean withMasters)](#getAllTextFrames-com.aspose.slides.IPresentation-boolean-) | Vrací všechny textové rámečky v PPTX prezentaci. |
| [toSaveFormat(int format)](#toSaveFormat-int-) | Převádí formát zdrojového souboru na odpovídající [SaveFormat](../../com.aspose.slides/saveformat). |
### SlideUtil() {#SlideUtil--}
```
public SlideUtil()
```

### findShape(IPresentation pres, String altText) {#findShape-com.aspose.slides.IPresentation-java.lang.String-}
```
public static IShape findShape(IPresentation pres, String altText)
```

Najde tvar podle alternativního textu v PPTX prezentaci.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| pres | [IPresentation](../../com.aspose.slides/ipresentation) | Prohledaná prezentace. |
| altText | java.lang.String | Alternativní text tvaru. |

**Návratová hodnota:**
[IShape](../../com.aspose.slides/ishape) - Tvar nebo null.
### findShape(IBaseSlide slide, String altText) {#findShape-com.aspose.slides.IBaseSlide-java.lang.String-}
```
public static IShape findShape(IBaseSlide slide, String altText)
```

Najde tvar podle alternativního textu na snímku v PPTX prezentaci.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| slide | [IBaseSlide](../../com.aspose.slides/ibaseslide) | Prohledaný snímek. |
| altText | java.lang.String | Alternativní text tvaru. |

**Návratová hodnota:**
[IShape](../../com.aspose.slides/ishape) - Tvar nebo null.
### findShapesByPlaceholderType(IBaseSlide slide, byte placeholderType) {#findShapesByPlaceholderType-com.aspose.slides.IBaseSlide-byte-}
```
public static IShape[] findShapesByPlaceholderType(IBaseSlide slide, byte placeholderType)
```

Vyhledá všechny tvary na určeném snímku, které odpovídají zadanému typu zástupce.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| slide | [IBaseSlide](../../com.aspose.slides/ibaseslide) | Snímek k vyhledání tvarů. |
| placeholderType | byte | Typ zástupce pro filtrování tvarů. |

**Návratová hodnota:**
com.aspose.slides.IShape[] - Pole objektů [IShape](../../com.aspose.slides/ishape), které odpovídají zadanému typu zástupce.
### alignShapes(int alignmentType, boolean alignToSlide, IBaseSlide slide) {#alignShapes-int-boolean-com.aspose.slides.IBaseSlide-}
```
public static void alignShapes(int alignmentType, boolean alignToSlide, IBaseSlide slide)
```

Mění umístění všech tvarů na snímku. Zarovnává tvary k okrajům nebo k okrajům snímku nebo je zarovnává relativně k sobě navzájem.

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
| alignmentType | int | Určuje, který typ zarovnání se použije. |
| alignToSlide | boolean | Pokud je true, tvary budou zarovnány vzhledem k okrajům snímku. |
| slide | [IBaseSlide](../../com.aspose.slides/ibaseslide) | Nadřazený snímek. |

### alignShapes(int alignmentType, boolean alignToSlide, IBaseSlide slide, int[] shapeIndexes) {#alignShapes-int-boolean-com.aspose.slides.IBaseSlide-int---}
```
public static void alignShapes(int alignmentType, boolean alignToSlide, IBaseSlide slide, int[] shapeIndexes)
```

Mění umístění vybraných tvarů na snímku. Zarovnává tvary k okrajům nebo k okrajům snímku nebo je zarovnává relativně k sobě navzájem.

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
| alignmentType | int | Určuje, který typ zarovnání se použije. |
| alignToSlide | boolean | Pokud je true, tvary budou zarovnány vzhledem k okrajům snímku. |
| slide | [IBaseSlide](../../com.aspose.slides/ibaseslide) | Nadřazený snímek. |
| shapeIndexes | int[] | Indexy tvarů, které mají být zarovnány. |

### alignShapes(int alignmentType, boolean alignToSlide, IGroupShape groupShape) {#alignShapes-int-boolean-com.aspose.slides.IGroupShape-}
```
public static void alignShapes(int alignmentType, boolean alignToSlide, IGroupShape groupShape)
```

Mění umístění všech tvarů uvnitř skupinového tvaru. Zarovnává tvary k okrajům nebo k okrajům snímku nebo je zarovnává relativně k sobě navzájem.

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
| alignmentType | int | Určuje, který typ zarovnání se použije. |
| alignToSlide | boolean | Pokud je true, tvary budou zarovnány vzhledem k okrajům snímku. |
| groupShape | [IGroupShape](../../com.aspose.slides/igroupshape) | Nadřazený skupinový tvar. |

### alignShapes(int alignmentType, boolean alignToSlide, IGroupShape groupShape, int[] shapeIndexes) {#alignShapes-int-boolean-com.aspose.slides.IGroupShape-int---}
```
public static void alignShapes(int alignmentType, boolean alignToSlide, IGroupShape groupShape, int[] shapeIndexes)
```

Mění umístění vybraných tvarů uvnitř skupinového tvaru. Zarovnává tvary k okrajům nebo k okrajům snímku nebo je zarovnává relativně k sobě navzájem.

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
| alignmentType | int | Určuje, který typ zarovnání se použije. |
| alignToSlide | boolean | Pokud je true, tvary budou zarovnány vzhledem k okrajům snímku. |
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
| presentation | [IPresentation](../../com.aspose.slides/ipresentation) | Prohledaná prezentace. |
| withMasters | boolean | Určuje, zda mají být prohledány hlavní snímky. |
| find | java.lang.String | Řetězcová hodnota k vyhledání. |
| replace | java.lang.String | Řetězcová hodnota k nahrazení. znak nalezeného řetězce |

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
| presentation | [IPresentation](../../com.aspose.slides/ipresentation) | Prohledaná prezentace. |
| withMasters | boolean | Určuje, zda mají být prohledány hlavní snímky. |
| find | java.lang.String | Řetězcová hodnota k vyhledání. |
| replace | java.lang.String | Řetězcová hodnota k nahrazení. |
| format | [PortionFormat](../../com.aspose.slides/portionformat) | Formát pro nahrazení části textu. Pokud je null, bude použit formát prvního znaku nalezeného řetězce |

### getAllTextBoxes(IBaseSlide slide) {#getAllTextBoxes-com.aspose.slides.IBaseSlide-}
```
public static ITextFrame[] getAllTextBoxes(IBaseSlide slide)
```

Vrací všechny textové rámečky na snímku v PPTX prezentaci.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| slide | [IBaseSlide](../../com.aspose.slides/ibaseslide) | Prohledaný snímek. |

**Návratová hodnota:**
com.aspose.slides.ITextFrame[] - Pole objektů [TextFrame](../../com.aspose.slides/textframe).

### getTextBoxesContainsText(IBaseSlide slide, String text, boolean checkPlaceholderText) {#getTextBoxesContainsText-com.aspose.slides.IBaseSlide-java.lang.String-boolean-}
```
public static ITextFrame[] getTextBoxesContainsText(IBaseSlide slide, String text, boolean checkPlaceholderText)
```

Vrací všechny textové rámečky na určeném snímku, které obsahují daný text.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| slide | [IBaseSlide](../../com.aspose.slides/ibaseslide) | Snímek k vyhledání. |
| text | java.lang.String | Text, který se má hledat v textových rámečcích. |
| checkPlaceholderText | boolean | Určuje, zda zahrnout textové rámečky, které jsou prázdné, ale jejich zástupný text obsahuje hledaný text. |

**Návratová hodnota:**
com.aspose.slides.ITextFrame[] - Pole objektů [ITextFrame](../../com.aspose.slides/itextframe), které obsahují zadaný text.

### getAllTextFrames(IPresentation pres, boolean withMasters) {#getAllTextFrames-com.aspose.slides.IPresentation-boolean-}
```
public static ITextFrame[] getAllTextFrames(IPresentation pres, boolean withMasters)
```

Vrací všechny textové rámečky v PPTX prezentaci.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| pres | [IPresentation](../../com.aspose.slides/ipresentation) | Prohledaná prezentace. |
| withMasters | boolean | Určuje, zda mají být prohledány hlavní snímky. |

**Návratová hodnota:**
com.aspose.slides.ITextFrame[] - Pole objektů [TextFrame](../../com.aspose.slides/textframe).

### toSaveFormat(int format) {#toSaveFormat-int-}
```
public static int toSaveFormat(int format)
```

Převádí formát zdrojového souboru na odpovídající [SaveFormat](../../com.aspose.slides/saveformat).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| format | int | Zdrojový formát souboru. |

**Návratová hodnota:**
int - Odpovídající hodnota [SaveFormat](../../com.aspose.slides/saveformat).