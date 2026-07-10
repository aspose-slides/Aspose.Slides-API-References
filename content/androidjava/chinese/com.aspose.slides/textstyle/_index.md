---
title: TextStyle
second_title: Aspose.Slides for Android via Java API 参考
description: 此类包含文本样式格式属性。
type: docs
url: /zh/com.aspose.slides/textstyle/
---
**继承:**  
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**所有实现的接口:**  
[com.aspose.slides.ITextStyle](../../com.aspose.slides/itextstyle), com.aspose.slides.IStyleColorOwner  
```
public final class TextStyle extends PVIObject implements ITextStyle, IStyleColorOwner
```

此类包含文本样式格式属性。

## 方法

| 方法 | 描述 |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getLevel(int index)](#getLevel-int-) | 如果样式级别存在，则返回它；否则返回 null。 |
| [getDefaultParagraphFormat()](#getDefaultParagraphFormat--) | 默认段落属性。 |
| [getEffective()](#getEffective--) | 获取在应用继承后的有效文本样式格式数据。 |

### getVersion() {#getVersion--}
```
public long getVersion()
```

版本。只读 long.

**返回:**  
long

### getLevel(int index) {#getLevel-int-}
```
public final IParagraphFormat getLevel(int index)
```

如果样式级别存在，则返回它；否则返回 null。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 级别的零基索引。必须位于 0..8 区间。 |

**返回:**  
[IParagraphFormat](../../com.aspose.slides/iparagraphformat) - 级别 [IParagraphFormat](../../com.aspose.slides/iparagraphformat) 的格式。

### getDefaultParagraphFormat() {#getDefaultParagraphFormat--}
```
public final IParagraphFormat getDefaultParagraphFormat()
```

默认段落属性。只读 [IParagraphFormat](../../com.aspose.slides/iparagraphformat)。

**返回:**  
[IParagraphFormat](../../com.aspose.slides/iparagraphformat)

### getEffective() {#getEffective--}
```
public final ITextStyleEffectiveData getEffective()
```

获取在应用继承后的有效文本样式格式数据。

--------------------

> ```
> This example demonstrates getting some of effective text style properties.
>  
>  Presentation pres = new Presentation("MyPresentation.pptx");
>  try
>  {
>      IAutoShape shape = (IAutoShape)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      ITextStyleEffectiveData effectiveTextStyle = shape.getTextFrame().getTextFrameFormat().getTextStyle().getEffective();
>      for (int i = 0; i <= 8; i++)
>      {
>          IParagraphFormatEffectiveData effectiveStyleLevel = effectiveTextStyle.getLevel(i);
>          System.out.println("= Effective paragraph formatting for style level #" + i + " =");
>          System.out.println("Depth: " + effectiveStyleLevel.getDepth());
>          System.out.println("Indent: " + effectiveStyleLevel.getIndent());
>          System.out.println("Alignment: " + effectiveStyleLevel.getAlignment());
>          System.out.println("Font alignment: " + effectiveStyleLevel.getFontAlignment());
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**返回:**  
[ITextStyleEffectiveData](../../com.aspose.slides/itextstyleeffectivedata) - 一个 [ITextStyleEffectiveData](../../com.aspose.slides/itextstyleeffectivedata).