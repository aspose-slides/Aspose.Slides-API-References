---
title: SlideUtil
second_title: Aspose.Slides for Android via Java API 參考
description: 提供可協助在簡報中搜尋圖形與文字的方法。
type: docs
url: /zh-hant/com.aspose.slides/slideutil/
---
**繼承：**
java.lang.Object
```
public class SlideUtil
```

提供可協助在簡報中搜尋圖形與文字的方法。

## 建構式

| 建構子 | 說明 |
| --- | --- |
| [SlideUtil()](#SlideUtil--) |  |

## 方法

| 方法 | 說明 |
| --- | --- |
| [findShape(IPresentation pres, String altText)](#findShape-com.aspose.slides.IPresentation-java.lang.String-) | 在 PPTX 簡報中依替代文字尋找圖形。 |
| [findShape(IBaseSlide slide, String altText)](#findShape-com.aspose.slides.IBaseSlide-java.lang.String-) | 在 PPTX 簡報的投影片上依替代文字尋找圖形。 |
| [findShapesByPlaceholderType(IBaseSlide slide, byte placeholderType)](#findShapesByPlaceholderType-com.aspose.slides.IBaseSlide-byte-) | 搜尋指定投影片上符合給定佔位類型的所有圖形。 |
| [alignShapes(int alignmentType, boolean alignToSlide, IBaseSlide slide)](#alignShapes-int-boolean-com.aspose.slides.IBaseSlide-) | 變更投影片上所有圖形的位置。 |
| [alignShapes(int alignmentType, boolean alignToSlide, IBaseSlide slide, int[] shapeIndexes)](#alignShapes-int-boolean-com.aspose.slides.IBaseSlide-int---) | 變更投影片上所選圖形的位置。 |
| [alignShapes(int alignmentType, boolean alignToSlide, IGroupShape groupShape)](#alignShapes-int-boolean-com.aspose.slides.IGroupShape-) | 變更群組圖形內所有圖形的位置。 |
| [alignShapes(int alignmentType, boolean alignToSlide, IGroupShape groupShape, int[] shapeIndexes)](#alignShapes-int-boolean-com.aspose.slides.IGroupShape-int---) | 變更群組圖形內所選圖形的位置。 |
| [findAndReplaceText(IPresentation presentation, boolean withMasters, String find, String replace)](#findAndReplaceText-com.aspose.slides.IPresentation-boolean-java.lang.String-java.lang.String-) | 在簡報中搜尋並取代文字（使用指定格式）。 |
| [findAndReplaceText(IPresentation presentation, boolean withMasters, String find, String replace, PortionFormat format)](#findAndReplaceText-com.aspose.slides.IPresentation-boolean-java.lang.String-java.lang.String-com.aspose.slides.PortionFormat-) | 在簡報中搜尋並取代文字（使用指定格式）。 |
| [getAllTextBoxes(IBaseSlide slide)](#getAllTextBoxes-com.aspose.slides.IBaseSlide-) | 傳回 PPTX 簡報中投影片上的所有文字框。 |
| [getTextBoxesContainsText(IBaseSlide slide, String text, boolean checkPlaceholderText)](#getTextBoxesContainsText-com.aspose.slides.IBaseSlide-java.lang.String-boolean-) | 傳回指定投影片上含有給定文字的所有文字框。 |
| [getAllTextFrames(IPresentation pres, boolean withMasters)](#getAllTextFrames-com.aspose.slides.IPresentation-boolean-) | 傳回 PPTX 簡報中所有文字框。 |
| [toSaveFormat(int format)](#toSaveFormat-int-) | 將來源檔案格式轉換為相對應的 [SaveFormat](../../com.aspose.slides/saveformat)。 |

### SlideUtil() {#SlideUtil--}
```
public SlideUtil()
```

### findShape(IPresentation pres, String altText) {#findShape-com.aspose.slides.IPresentation-java.lang.String-}
```
public static IShape findShape(IPresentation pres, String altText)
```

在 PPTX 簡報中依替代文字尋找圖形。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| pres | [IPresentation](../../com.aspose.slides/ipresentation) | 已掃描的簡報。 |
| altText | java.lang.String | 圖形的替代文字。 |

**傳回值：**
[IShape](../../com.aspose.slides/ishape) - 形狀或 null。

### findShape(IBaseSlide slide, String altText) {#findShape-com.aspose.slides.IBaseSlide-java.lang.String-}
```
public static IShape findShape(IBaseSlide slide, String altText)
```

在 PPTX 簡報的投影片上依替代文字尋找圖形。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| slide | [IBaseSlide](../../com.aspose.slides/ibaseslide) | 已掃描的投影片。 |
| altText | java.lang.String | 圖形的替代文字。 |

**傳回值：**
[IShape](../../com.aspose.slides/ishape) - 形狀或 null。

### findShapesByPlaceholderType(IBaseSlide slide, byte placeholderType) {#findShapesByPlaceholderType-com.aspose.slides.IBaseSlide-byte-}
```
public static IShape[] findShapesByPlaceholderType(IBaseSlide slide, byte placeholderType)
```

搜尋指定投影片上符合給定佔位類型的所有圖形。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| slide | [IBaseSlide](../../com.aspose.slides/ibaseslide) | 要搜尋圖形的投影片。 |
| placeholderType | byte | 用於過濾圖形的佔位類型。 |

**傳回值：**
com.aspose.slides.IShape[] - 與指定佔位類型相符的 [IShape](../../com.aspose.slides/ishape) 物件陣列。

### alignShapes(int alignmentType, boolean alignToSlide, IBaseSlide slide) {#alignShapes-int-boolean-com.aspose.slides.IBaseSlide-}
```
public static void alignShapes(int alignmentType, boolean alignToSlide, IBaseSlide slide)
```

變更投影片上所有圖形的位置。將圖形對齊至投影片的邊界或相互之間對齊。

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
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| alignmentType | int | 決定將套用哪種對齊類型。 |
| alignToSlide | boolean | 若為 true，圖形將相對於投影片邊緣對齊。 |
| slide | [IBaseSlide](../../com.aspose.slides/ibaseslide) | 父層投影片。 |

### alignShapes(int alignmentType, boolean alignToSlide, IBaseSlide slide, int[] shapeIndexes) {#alignShapes-int-boolean-com.aspose.slides.IBaseSlide-int---}
```
public static void alignShapes(int alignmentType, boolean alignToSlide, IBaseSlide slide, int[] shapeIndexes)
```

變更投影片上所選圖形的位置。將圖形對齊至投影片的邊界或相互之間對齊。

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
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| alignmentType | int | 決定將套用哪種對齊類型。 |
| alignToSlide | boolean | 若為 true，圖形將相對於投影片邊緣對齊。 |
| slide | [IBaseSlide](../../com.aspose.slides/ibaseslide) | 父層投影片。 |
| shapeIndexes | int[] | 要對齊的圖形索引。 |

### alignShapes(int alignmentType, boolean alignToSlide, IGroupShape groupShape) {#alignShapes-int-boolean-com.aspose.slides.IGroupShape-}
```
public static void alignShapes(int alignmentType, boolean alignToSlide, IGroupShape groupShape)
```

變更群組圖形內所有圖形的位置。將圖形對齊至投影片的邊界或相互之間對齊。

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

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| alignmentType | int | 決定將套用哪種對齊類型。 |
| alignToSlide | boolean | 若為 true，圖形將相對於投影片邊緣對齊。 |
| groupShape | [IGroupShape](../../com.aspose.slides/igroupshape) | 父層群組圖形。 |

### alignShapes(int alignmentType, boolean alignToSlide, IGroupShape groupShape, int[] shapeIndexes) {#alignShapes-int-boolean-com.aspose.slides.IGroupShape-int---}
```
public static void alignShapes(int alignmentType, boolean alignToSlide, IGroupShape groupShape, int[] shapeIndexes)
```

變更群組圖形內所選圖形的位置。將圖形對齊至投影片的邊界或相互之間對齊。

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

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| alignmentType | int | 決定將套用哪種對齊類型。 |
| alignToSlide | boolean | 若為 true，圖形將相對於投影片邊緣對齊。 |
| groupShape | [IGroupShape](../../com.aspose.slides/igroupshape) | 父層群組圖形。 |
| shapeIndexes | int[] | 要對齊的圖形索引。 |

### findAndReplaceText(IPresentation presentation, boolean withMasters, String find, String replace) {#findAndReplaceText-com.aspose.slides.IPresentation-boolean-java.lang.String-java.lang.String-}
```
public static void findAndReplaceText(IPresentation presentation, boolean withMasters, String find, String replace)
```

在簡報中搜尋並取代文字（使用指定格式）。

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
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| presentation | [IPresentation](../../com.aspose.slides/ipresentation) | 已掃描的簡報。 |
| withMasters | boolean | 是否要掃描母版投影片。 |
| find | java.lang.String | 要搜尋的字串值。 |
| replace | java.lang.String | 用於取代的字串值（找到的字串之字元）。 |

### findAndReplaceText(IPresentation presentation, boolean withMasters, String find, String replace, PortionFormat format) {#findAndReplaceText-com.aspose.slides.IPresentation-boolean-java.lang.String-java.lang.String-com.aspose.slides.PortionFormat-}
```
public static void findAndReplaceText(IPresentation presentation, boolean withMasters, String find, String replace, PortionFormat format)
```

在簡報中搜尋並取代文字（使用指定格式）。

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
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| presentation | [IPresentation](../../com.aspose.slides/ipresentation) | 已掃描的簡報。 |
| withMasters | boolean | 是否要掃描母版投影片。 |
| find | java.lang.String | 要搜尋的字串值。 |
| replace | java.lang.String | 用於取代的字串值。 |
| format | [PortionFormat](../../com.aspose.slides/portionformat) | 取代文字片段的格式。若為 null，則使用找到字串第一個字元的格式。 |

### getAllTextBoxes(IBaseSlide slide) {#getAllTextBoxes-com.aspose.slides.IBaseSlide-}
```
public static ITextFrame[] getAllTextBoxes(IBaseSlide slide)
```

傳回投影片上所有文字框。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| slide | [IBaseSlide](../../com.aspose.slides/ibaseslide) | 已掃描的投影片。 |

**傳回值：**
com.aspose.slides.ITextFrame[] - [TextFrame](../../com.aspose.slides/textframe) 物件陣列。

### getTextBoxesContainsText(IBaseSlide slide, String text, boolean checkPlaceholderText) {#getTextBoxesContainsText-com.aspose.slides.IBaseSlide-java.lang.String-boolean-}
```
public static ITextFrame[] getTextBoxesContainsText(IBaseSlide slide, String text, boolean checkPlaceholderText)
```

傳回指定投影片上包含給定文字的所有文字框。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| slide | [IBaseSlide](../../com.aspose.slides/ibaseslide) | 要搜尋的投影片。 |
| text | java.lang.String | 要在文字框中搜尋的文字。 |
| checkPlaceholderText | boolean | 是否包含佔位文字中包含搜尋文字的空白文字框。 |

**傳回值：**
com.aspose.slides.ITextFrame[] - 包含指定文字的 [ITextFrame](../../com.aspose.slides/itextframe) 物件陣列。

### getAllTextFrames(IPresentation pres, boolean withMasters) {#getAllTextFrames-com.aspose.slides.IPresentation-boolean-}
```
public static ITextFrame[] getAllTextFrames(IPresentation pres, boolean withMasters)
```

傳回 PPTX 簡報中所有文字框。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| pres | [IPresentation](../../com.aspose.slides/ipresentation) | 已掃描的簡報。 |
| withMasters | boolean | 是否要掃描母版投影片。 |

**傳回值：**
com.aspose.slides.ITextFrame[] - [TextFrame](../../com.aspose.slides/textframe) 物件陣列。

### toSaveFormat(int format) {#toSaveFormat-int-}
```
public static int toSaveFormat(int format)
```

將來源檔案格式轉換為相對應的 [SaveFormat](../../com.aspose.slides/saveformat)。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| format | int | 來源檔案格式。 |

**傳回值：**
int - 相對應的 [SaveFormat](../../com.aspose.slides/saveformat) 值。