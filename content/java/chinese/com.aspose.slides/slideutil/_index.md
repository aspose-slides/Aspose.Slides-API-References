---
title: SlideUtil
second_title: Aspose.Slides 的 Java API 参考
description: 提供帮助在演示文稿中搜索形状和文本的方法。
type: docs
url: /zh/com.aspose.slides/slideutil/
---
**继承：**
java.lang.Object
```
public class SlideUtil
```

提供帮助在演示文稿中搜索形状和文本的方法。

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [SlideUtil()](#SlideUtil--) |  |

## 方法

| 方法 | 描述 |
| --- | --- |
| [findShape(IPresentation pres, String altText)](#findShape-com.aspose.slides.IPresentation-java.lang.String-) | 在 PPTX 演示文稿中通过替代文本查找形状。 |
| [findShape(IBaseSlide slide, String altText)](#findShape-com.aspose.slides.IBaseSlide-java.lang.String-) | 在 PPTX 演示文稿的幻灯片上通过替代文本查找形状。 |
| [findShapesByPlaceholderType(IBaseSlide slide, byte placeholderType)](#findShapesByPlaceholderType-com.aspose.slides.IBaseSlide-byte-) | 搜索指定幻灯片上所有匹配给定占位符类型的形状。 |
| [alignShapes(int alignmentType, boolean alignToSlide, IBaseSlide slide)](#alignShapes-int-boolean-com.aspose.slides.IBaseSlide-) | 更改幻灯片上所有形状的位置。 |
| [alignShapes(int alignmentType, boolean alignToSlide, IBaseSlide slide, int[] shapeIndexes)](#alignShapes-int-boolean-com.aspose.slides.IBaseSlide-int---) | 更改选定形状在幻灯片上的位置。 |
| [alignShapes(int alignmentType, boolean alignToSlide, IGroupShape groupShape)](#alignShapes-int-boolean-com.aspose.slides.IGroupShape-) | 更改组形状内所有形状的位置。 |
| [alignShapes(int alignmentType, boolean alignToSlide, IGroupShape groupShape, int[] shapeIndexes)](#alignShapes-int-boolean-com.aspose.slides.IGroupShape-int---) | 更改组形状内选定形状的位置。 |
| [findAndReplaceText(IPresentation presentation, boolean withMasters, String find, String replace)](#findAndReplaceText-com.aspose.slides.IPresentation-boolean-java.lang.String-java.lang.String-) | 在演示文稿中查找并替换具有给定格式的文本 |
| [findAndReplaceText(IPresentation presentation, boolean withMasters, String find, String replace, PortionFormat format)](#findAndReplaceText-com.aspose.slides.IPresentation-boolean-java.lang.String-java.lang.String-com.aspose.slides.PortionFormat-) | 在演示文稿中查找并替换具有给定格式的文本 |
| [getAllTextBoxes(IBaseSlide slide)](#getAllTextBoxes-com.aspose.slides.IBaseSlide-) | 返回 PPTX 演示文稿中幻灯片上的所有文本框。 |
| [getTextBoxesContainsText(IBaseSlide slide, String text, boolean checkPlaceholderText)](#getTextBoxesContainsText-com.aspose.slides.IBaseSlide-java.lang.String-boolean-) | 返回指定幻灯片上包含给定文本的所有文本框。 |
| [getAllTextFrames(IPresentation pres, boolean withMasters)](#getAllTextFrames-com.aspose.slides.IPresentation-boolean-) | 返回 PPTX 演示文稿中的所有文本框。 |
| [toSaveFormat(int format)](#toSaveFormat-int-) | 将源文件格式转换为相应的 [SaveFormat](../../com.aspose.slides/saveformat)。 |

### SlideUtil() {#SlideUtil--}
```
public SlideUtil()
```

### findShape(IPresentation pres, String altText) {#findShape-com.aspose.slides.IPresentation-java.lang.String-}
```
public static IShape findShape(IPresentation pres, String altText)
```

在 PPTX 演示文稿中通过替代文本查找形状。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| pres | [IPresentation](../../com.aspose.slides/ipresentation) | 已扫描的演示文稿。 |
| altText | java.lang.String | 形状的替代文本。 |

**返回：**
[IShape](../../com.aspose.slides/ishape) - 形状或 null。

### findShape(IBaseSlide slide, String altText) {#findShape-com.aspose.slides.IBaseSlide-java.lang.String-}
```
public static IShape findShape(IBaseSlide slide, String altText)
```

在 PPTX 演示文稿的幻灯片上通过替代文本查找形状。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| slide | [IBaseSlide](../../com.aspose.slides/ibaseslide) | 已扫描的幻灯片。 |
| altText | java.lang.String | 形状的替代文本。 |

**返回：**
[IShape](../../com.aspose.slides/ishape) - 形状或 null。

### findShapesByPlaceholderType(IBaseSlide slide, byte placeholderType) {#findShapesByPlaceholderType-com.aspose.slides.IBaseSlide-byte-}
```
public static IShape[] findShapesByPlaceholderType(IBaseSlide slide, byte placeholderType)
```

搜索指定幻灯片上所有匹配给定占位符类型的形状。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| slide | [IBaseSlide](../../com.aspose.slides/ibaseslide) | 用于搜索形状的幻灯片。 |
| placeholderType | byte | 用于过滤形状的占位符类型。 |

**返回：**
com.aspose.slides.IShape[] - 一个与指定占位符类型匹配的 [IShape](../../com.aspose.slides/ishape) 对象数组。

### alignShapes(int alignmentType, boolean alignToSlide, IBaseSlide slide) {#alignShapes-int-boolean-com.aspose.slides.IBaseSlide-}
```
public static void alignShapes(int alignmentType, boolean alignToSlide, IBaseSlide slide)
```

更改幻灯片上所有形状的位置。将形状对齐到幻灯片的边距或边缘，或相互对齐。

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

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| alignmentType | int | 确定要应用的对齐类型。 |
| alignToSlide | boolean | 如果为 true，形状将相对于幻灯片边缘对齐。 |
| slide | [IBaseSlide](../../com.aspose.slides/ibaseslide) | 父幻灯片。 |

### alignShapes(int alignmentType, boolean alignToSlide, IBaseSlide slide, int[] shapeIndexes) {#alignShapes-int-boolean-com.aspose.slides.IBaseSlide-int---}
```
public static void alignShapes(int alignmentType, boolean alignToSlide, IBaseSlide slide, int[] shapeIndexes)
```

更改选定形状在幻灯片上的位置。将形状对齐到幻灯片的边距或边缘，或相互对齐。

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

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| alignmentType | int | 确定要应用的对齐类型。 |
| alignToSlide | boolean | 如果为 true，形状将相对于幻灯片边缘对齐。 |
| slide | [IBaseSlide](../../com.aspose.slides/ibaseslide) | 父幻灯片。 |
| shapeIndexes | int[] | 要对齐的形状索引。 |

### alignShapes(int alignmentType, boolean alignToSlide, IGroupShape groupShape) {#alignShapes-int-boolean-com.aspose.slides.IGroupShape-}
```
public static void alignShapes(int alignmentType, boolean alignToSlide, IGroupShape groupShape)
```

更改组形状内所有形状的位置。将形状对齐到幻灯片的边距或边缘，或相互对齐。

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

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| alignmentType | int | 确定要应用的对齐类型。 |
| alignToSlide | boolean | 如果为 true，形状将相对于幻灯片边缘对齐。 |
| groupShape | [IGroupShape](../../com.aspose.slides/igroupshape) | 父组形状。 |

### alignShapes(int alignmentType, boolean alignToSlide, IGroupShape groupShape, int[] shapeIndexes) {#alignShapes-int-boolean-com.aspose.slides.IGroupShape-int---}
```
public static void alignShapes(int alignmentType, boolean alignToSlide, IGroupShape groupShape, int[] shapeIndexes)
```

更改组形状内选定形状的位置。将形状对齐到幻灯片的边距或边缘，或相互对齐。

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

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| alignmentType | int | 确定要应用的对齐类型。 |
| alignToSlide | boolean | 如果为 true，形状将相对于幻灯片边缘对齐。 |
| groupShape | [IGroupShape](../../com.aspose.slides/igroupshape) | 父组形状。 |
| shapeIndexes | int[] | 要对齐的形状索引。 |

### findAndReplaceText(IPresentation presentation, boolean withMasters, String find, String replace) {#findAndReplaceText-com.aspose.slides.IPresentation-boolean-java.lang.String-java.lang.String-}
```
public static void findAndReplaceText(IPresentation presentation, boolean withMasters, String find, String replace)
```

在演示文稿中查找并替换具有给定格式的文本

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

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| presentation | [IPresentation](../../com.aspose.slides/ipresentation) | 已扫描的演示文稿。 |
| withMasters | boolean | 确定是否应扫描母版幻灯片。 |
| find | java.lang.String | 要查找的字符串值。 |
| replace | java.lang.String | 用于替换的字符串值。已找到字符串的字符 |

### findAndReplaceText(IPresentation presentation, boolean withMasters, String find, String replace, PortionFormat format) {#findAndReplaceText-com.aspose.slides.IPresentation-boolean-java.lang.String-java.lang.String-com.aspose.slides.PortionFormat-}
```
public static void findAndReplaceText(IPresentation presentation, boolean withMasters, String find, String replace, PortionFormat format)
```

在演示文稿中查找并替换具有给定格式的文本

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

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| presentation | [IPresentation](../../com.aspose.slides/ipresentation) | 已扫描的演示文稿。 |
| withMasters | boolean | 确定是否应扫描母版幻灯片。 |
| find | java.lang.String | 要查找的字符串值。 |
| replace | java.lang.String | 用于替换的字符串值。 |
| format | [PortionFormat](../../com.aspose.slides/portionformat) | 替换文本段的格式。如果为 null，则使用已找到字符串第一个字符的格式 |

### getAllTextBoxes(IBaseSlide slide) {#getAllTextBoxes-com.aspose.slides.IBaseSlide-}
```
public static ITextFrame[] getAllTextBoxes(IBaseSlide slide)
```

返回 PPTX 演示文稿中幻灯片上的所有文本框。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| slide | [IBaseSlide](../../com.aspose.slides/ibaseslide) | 已扫描的幻灯片。 |

**返回：**
com.aspose.slides.ITextFrame[] - [TextFrame](../../com.aspose.slides/textframe) 对象数组。

### getTextBoxesContainsText(IBaseSlide slide, String text, boolean checkPlaceholderText) {#getTextBoxesContainsText-com.aspose.slides.IBaseSlide-java.lang.String-boolean-}
```
public static ITextFrame[] getTextBoxesContainsText(IBaseSlide slide, String text, boolean checkPlaceholderText)
```

返回指定幻灯片上包含给定文本的所有文本框。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| slide | [IBaseSlide](../../com.aspose.slides/ibaseslide) | 要搜索的幻灯片。 |
| text | java.lang.String | 要在文本框中搜索的文本。 |
| checkPlaceholderText | boolean | 指示是否应包括占位符文本包含搜索文本但本身为空的文本框。 |

**返回：**
com.aspose.slides.ITextFrame[] - 包含指定文本的 [ITextFrame](../../com.aspose.slides/itextframe) 对象数组。

### getAllTextFrames(IPresentation pres, boolean withMasters) {#getAllTextFrames-com.aspose.slides.IPresentation-boolean-}
```
public static ITextFrame[] getAllTextFrames(IPresentation pres, boolean withMasters)
```

返回 PPTX 演示文稿中的所有文本框。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| pres | [IPresentation](../../com.aspose.slides/ipresentation) | 已扫描的演示文稿。 |
| withMasters | boolean | 确定是否应扫描母版幻灯片。 |

**返回：**
com.aspose.slides.ITextFrame[] - [TextFrame](../../com.aspose.slides/textframe) 对象数组。

### toSaveFormat(int format) {#toSaveFormat-int-}
```
public static int toSaveFormat(int format)
```

将源文件格式转换为相应的 [SaveFormat](../../com.aspose.slides/saveformat)。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| format | int | 源文件格式。 |

**返回：**
int - 相应的 [SaveFormat](../../com.aspose.slides/saveformat) 值。