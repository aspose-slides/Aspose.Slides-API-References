---
title: SlideUtil
second_title: Aspose.Slides for Java API 參考
description: 提供協助在簡報中搜尋形狀和文字的方法。
type: docs
url: /zh-hant/com.aspose.slides/slideutil/
---
**Inheritance:**
java.lang.Object
```
public class SlideUtil
```

提供有助於在簡報中搜尋形狀和文字的方法。

## 建構函式

| 建構函式 | 說明 |
| --- | --- |
| [SlideUtil()](#SlideUtil--) |  |

## 方法

| 方法 | 說明 |
| --- | --- |
| [findShape(IPresentation pres, String altText)](#findShape-com.aspose.slides.IPresentation-java.lang.String-) | Find shape by alternative text in a PPTX presentation. |
| [findShape(IBaseSlide slide, String altText)](#findShape-com.aspose.slides.IBaseSlide-java.lang.String-) | Find shape by alternative text on a slide in a PPTX presentation. |
| [findShapesByPlaceholderType(IBaseSlide slide, byte placeholderType)](#findShapesByPlaceholderType-com.aspose.slides.IBaseSlide-byte-) | Searches for all shapes on the specified slide that match the given placeholder type. |
| [alignShapes(int alignmentType, boolean alignToSlide, IBaseSlide slide)](#alignShapes-int-boolean-com.aspose.slides.IBaseSlide-) | Changes the placement of all shapes on the slide. |
| [alignShapes(int alignmentType, boolean alignToSlide, IBaseSlide slide, int[] shapeIndexes)](#alignShapes-int-boolean-com.aspose.slides.IBaseSlide-int---) | Changes the placement of selected shapes on the slide. |
| [alignShapes(int alignmentType, boolean alignToSlide, IGroupShape groupShape)](#alignShapes-int-boolean-com.aspose.slides.IGroupShape-) | Changes the placement of all shapes within group shape. |
| [alignShapes(int alignmentType, boolean alignToSlide, IGroupShape groupShape, int[] shapeIndexes)](#alignShapes-int-boolean-com.aspose.slides.IGroupShape-int---) | Changes the placement of selected shapes within group shape. |
| [findAndReplaceText(IPresentation presentation, boolean withMasters, String find, String replace)](#findAndReplaceText-com.aspose.slides.IPresentation-boolean-java.lang.String-java.lang.String-) | Finds and replaces text in presentation with given format |
| [findAndReplaceText(IPresentation presentation, boolean withMasters, String find, String replace, PortionFormat format)](#findAndReplaceText-com.aspose.slides.IPresentation-boolean-java.lang.String-java.lang.String-com.aspose.slides.PortionFormat-) | Finds and replaces text in presentation with given format |
| [getAllTextBoxes(IBaseSlide slide)](#getAllTextBoxes-com.aspose.slides.IBaseSlide-) | Returns all text frames on a slide in a PPTX presentation. |
| [getTextBoxesContainsText(IBaseSlide slide, String text, boolean checkPlaceholderText)](#getTextBoxesContainsText-com.aspose.slides.IBaseSlide-java.lang.String-boolean-) | Returns all text frames on the specified slide that contain the given text. |
| [getAllTextFrames(IPresentation pres, boolean withMasters)](#getAllTextFrames-com.aspose.slides.IPresentation-boolean-) | Returns all text frames in a PPTX presentation. |
| [toSaveFormat(int format)](#toSaveFormat-int-) | Converts a source file format to the corresponding [SaveFormat](../../com.aspose.slides/saveformat). |

### SlideUtil() {#SlideUtil--}
```
public SlideUtil()
```

### findShape(IPresentation pres, String altText) {#findShape-com.aspose.slides.IPresentation-java.lang.String-}
```
public static IShape findShape(IPresentation pres, String altText)
```

在 PPTX 簡報中依替代文字尋找形狀。

**參數：**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| pres | [IPresentation](../../com.aspose.slides/ipresentation) | Scanned presentation. |
| altText | java.lang.String | Alternative text of a shape. |

**傳回值：**
[IShape](../../com.aspose.slides/ishape) - Shape or null.

### findShape(IBaseSlide slide, String altText) {#findShape-com.aspose.slides.IBaseSlide-java.lang.String-}
```
public static IShape findShape(IBaseSlide slide, String altText)
```

在投影片上依替代文字尋找形狀。

**參數：**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| slide | [IBaseSlide](../../com.aspose.slides/ibaseslide) | Scanned slide. |
| altText | java.lang.String | Alternative text of a shape. |

**傳回值：**
[IShape](../../com.aspose.slides/ishape) - Shape or null.

### findShapesByPlaceholderType(IBaseSlide slide, byte placeholderType) {#findShapesByPlaceholderType-com.aspose.slides.IBaseSlide-byte-}
```
public static IShape[] findShapesByPlaceholderType(IBaseSlide slide, byte placeholderType)
```

搜尋指定投影片上符合給定佔位符類型的所有形狀。

**參數：**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| slide | [IBaseSlide](../../com.aspose.slides/ibaseslide) | The slide to search for shapes. |
| placeholderType | byte | The type of placeholder to filter shapes by. |

**傳回值：**
com.aspose.slides.IShape[] - An array of [IShape](../../com.aspose.slides/ishape) objects that match the specified placeholder type.

### alignShapes(int alignmentType, boolean alignToSlide, IBaseSlide slide) {#alignShapes-int-boolean-com.aspose.slides.IBaseSlide-}
```
public static void alignShapes(int alignmentType, boolean alignToSlide, IBaseSlide slide)
```

變更投影片上所有形狀的位置。將形狀對齊至邊緣或投影片的邊緣，或相互對齊。

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

**參數：**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| alignmentType | int | Determines which type of alignment will be applied. |
| alignToSlide | boolean | If true, shapes will be aligned relative to the slide edges. |
| slide | [IBaseSlide](../../com.aspose.slides/ibaseslide) | Parent slide. |

### alignShapes(int alignmentType, boolean alignToSlide, IBaseSlide slide, int[] shapeIndexes) {#alignShapes-int-boolean-com.aspose.slides.IBaseSlide-int---}
```
public static void alignShapes(int alignmentType, boolean alignToSlide, IBaseSlide slide, int[] shapeIndexes)
```

變更投影片上所選形狀的位置。將形狀對齊至邊緣或投影片的邊緣，或相互對齊。

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

**參數：**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| alignmentType | int | Determines which type of alignment will be applied. |
| alignToSlide | boolean | If true, shapes will be aligned relative to the slide edges. |
| slide | [IBaseSlide](../../com.aspose.slides/ibaseslide) | Parent slide. |
| shapeIndexes | int[] | Indexes of shapes to be aligned. |

### alignShapes(int alignmentType, boolean alignToSlide, IGroupShape groupShape) {#alignShapes-int-boolean-com.aspose.slides.IGroupShape-}
```
public static void alignShapes(int alignmentType, boolean alignToSlide, IGroupShape groupShape)
```

變更群組形狀內所有形狀的位置。將形狀對齊至邊緣或投影片的邊緣，或相互對齊。

--------------------

> ```
> 範例：
>  
>   Presentation pres = new Presentation("pres.pptx");
>   try {
>      ISlide slide = pres.getSlides().get_Item(0);
>      SlideUtil.alignShapes(ShapesAlignmentType.AlignLeft, false, (GroupShape) slide.getShapes().get_Item(0));
>   } finally {
>      if (pres != null) pres.dispose();
>   }
> ```

**參數：**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| alignmentType | int | Determines which type of alignment will be applied. |
| alignToSlide | boolean | If true, shapes will be aligned relative to the slide edges. |
| groupShape | [IGroupShape](../../com.aspose.slides/igroupshape) | Parent group shape. |

### alignShapes(int alignmentType, boolean alignToSlide, IGroupShape groupShape, int[] shapeIndexes) {#alignShapes-int-boolean-com.aspose.slides.IGroupShape-int---}
```
public static void alignShapes(int alignmentType, boolean alignToSlide, IGroupShape groupShape, int[] shapeIndexes)
```

變更群組形狀內所選形狀的位置。將形狀對齊至邊緣或投影片的邊緣，或相互對齊。

--------------------

> ```
> 範例：
>  
>   Presentation pres = new Presentation("pres.pptx");
>   try {
>      ISlide slide = pres.getSlides().get_Item(0);
>      SlideUtil.alignShapes(ShapesAlignmentType.AlignLeft, false, (GroupShape)slide.getShapes().get_Item(0), new int[] { 0, 2 });
>   } finally {
>      if (pres != null) pres.dispose();
>   }
> ```

**參數：**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| alignmentType | int | Determines which type of alignment will be applied. |
| alignToSlide | boolean | If true, shapes will be aligned relative to the slide edges. |
| groupShape | [IGroupShape](../../com.aspose.slides/igroupshape) | Parent group shape. |
| shapeIndexes | int[] | Indexes of shapes to be aligned. |

### findAndReplaceText(IPresentation presentation, boolean withMasters, String find, String replace) {#findAndReplaceText-com.aspose.slides.IPresentation-boolean-java.lang.String-java.lang.String-}
```
public static void findAndReplaceText(IPresentation presentation, boolean withMasters, String find, String replace)
```

在簡報中以指定格式尋找並取代文字。

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


**參數：**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| presentation | [IPresentation](../../com.aspose.slides/ipresentation) | Scanned presentation. |
| withMasters | boolean | Determines whether master slides should be scanned. |
| find | java.lang.String | String value to find. |
| replace | java.lang.String | String value to replace. character of the found string |

### findAndReplaceText(IPresentation presentation, boolean withMasters, String find, String replace, PortionFormat format) {#findAndReplaceText-com.aspose.slides.IPresentation-boolean-java.lang.String-java.lang.String-com.aspose.slides.PortionFormat-}
```
public static void findAndReplaceText(IPresentation presentation, boolean withMasters, String find, String replace, PortionFormat format)
```

在簡報中以指定格式尋找並取代文字。

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


**參數：**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| presentation | [IPresentation](../../com.aspose.slides/ipresentation) | Scanned presentation. |
| withMasters | boolean | Determines whether master slides should be scanned. |
| find | java.lang.String | String value to find. |
| replace | java.lang.String | String value to replace. |
| format | [PortionFormat](../../com.aspose.slides/portionformat) | Format for replacing text portion. If null then will be used format of the first character of the found string |

### getAllTextBoxes(IBaseSlide slide) {#getAllTextBoxes-com.aspose.slides.IBaseSlide-}
```
public static ITextFrame[] getAllTextBoxes(IBaseSlide slide)
```

傳回投影片中所有文字框。

**參數：**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| slide | [IBaseSlide](../../com.aspose.slides/ibaseslide) | Scanned slide. |

**傳回值：**
com.aspose.slides.ITextFrame[] - Array of [TextFrame](../../com.aspose.slides/textframe) objects.

### getTextBoxesContainsText(IBaseSlide slide, String text, boolean checkPlaceholderText) {#getTextBoxesContainsText-com.aspose.slides.IBaseSlide-java.lang.String-boolean-}
```
public static ITextFrame[] getTextBoxesContainsText(IBaseSlide slide, String text, boolean checkPlaceholderText)
```

傳回指定投影片中包含給定文字的所有文字框。

**參數：**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| slide | [IBaseSlide](../../com.aspose.slides/ibaseslide) | The slide to search. |
| text | java.lang.String | The text to search for within text frames. |
| checkPlaceholderText | boolean | Indicates whether to include text frames that are empty, but whose placeholder text contains the search text. |

**傳回值：**
com.aspose.slides.ITextFrame[] - An array of [ITextFrame](../../com.aspose.slides/itextframe) objects that contain the specified text.

### getAllTextFrames(IPresentation pres, boolean withMasters) {#getAllTextFrames-com.aspose.slides.IPresentation-boolean-}
```
public static ITextFrame[] getAllTextFrames(IPresentation pres, boolean withMasters)
```

傳回 PPTX 簡報中所有文字框。

**參數：**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| pres | [IPresentation](../../com.aspose.slides/ipresentation) | Scanned presentation. |
| withMasters | boolean | Determines whether master slides should be scanned. |

**傳回值：**
com.aspose.slides.ITextFrame[] - Array of [TextFrame](../../com.aspose.slides/textframe) objects.

### toSaveFormat(int format) {#toSaveFormat-int-}
```
public static int toSaveFormat(int format)
```

將來源檔案格式轉換為相對應的 [SaveFormat](../../com.aspose.slides/saveformat)。

**參數：**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| format | int | The source file format. |

**傳回值：**
int - The corresponding [SaveFormat](../../com.aspose.slides/saveformat) value.