---
title: TextStyle
second_title: Aspose.Slides for Android via Java API 參考文件
description: 此類別包含文字樣式格式設定屬性。
type: docs
url: /zh-hant/com.aspose.slides/textstyle/
---
**Inheritance:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**All Implemented Interfaces:**
[com.aspose.slides.ITextStyle](../../com.aspose.slides/itextstyle), com.aspose.slides.IStyleColorOwner
```
public final class TextStyle extends PVIObject implements ITextStyle, IStyleColorOwner
```

此類別包含文字樣式格式設定屬性。

## 方法

| 方法 | 說明 |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getLevel(int index)](#getLevel-int-) | 如果樣式層級存在，則返回它；否則返回 null。 |
| [getDefaultParagraphFormat()](#getDefaultParagraphFormat--) | 預設段落屬性。 |
| [getEffective()](#getEffective--) | 取得套用繼承後的有效文字樣式格式資料。 |

### getVersion() {#getVersion--}
```
public long getVersion()
```

版本。唯讀 long。

**返回：**
long

### getLevel(int index) {#getLevel-int-}
```
public final IParagraphFormat getLevel(int index)
```

如果樣式層級存在，則返回它；否則返回 null。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| index | int | 層級的零基索引。必須在 0..8 範圍內。 |

**返回：**
[IParagraphFormat](../../com.aspose.slides/iparagraphformat) - 第 [IParagraphFormat](../../com.aspose.slides/iparagraphformat) 級的格式。

### getDefaultParagraphFormat() {#getDefaultParagraphFormat--}
```
public final IParagraphFormat getDefaultParagraphFormat()
```

預設段落屬性。唯讀 [IParagraphFormat](../../com.aspose.slides/iparagraphformat)。

**返回：**
[IParagraphFormat](../../com.aspose.slides/iparagraphformat)

### getEffective() {#getEffective--}
```
public final ITextStyleEffectiveData getEffective()
```

取得套用繼承後的有效文字樣式格式資料。

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


**返回：**
[ITextStyleEffectiveData](../../com.aspose.slides/itextstyleeffectivedata) - 一個 [ITextStyleEffectiveData](../../com.aspose.slides/itextstyleeffectivedata)。