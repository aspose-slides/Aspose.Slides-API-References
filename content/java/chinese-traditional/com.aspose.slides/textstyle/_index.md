---
title: TextStyle
second_title: Aspose.Slides for Java API 參考文件
description: 此類別包含文字樣式格式設定屬性。
type: docs
url: /zh-hant/com.aspose.slides/textstyle/
---
**繼承:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**所有已實作的介面:**
[com.aspose.slides.ITextStyle](../../com.aspose.slides/itextstyle), com.aspose.slides.IStyleColorOwner
```
public final class TextStyle extends PVIObject implements ITextStyle, IStyleColorOwner
```

此類別包含文字樣式格式設定屬性。
## 方法

| 方法 | 描述 |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getLevel(int index)](#getLevel-int-) | 若樣式層級存在則回傳，否則回傳 null。 |
| [getDefaultParagraphFormat()](#getDefaultParagraphFormat--) | 預設段落屬性。 |
| [getEffective()](#getEffective--) | 取得套用繼承後的有效文字樣式格式化資料。 |
### getVersion() {#getVersion--}
```
public long getVersion()
```


版本。唯讀 long。

**傳回值:**
long
### getLevel(int index) {#getLevel-int-}
```
public final IParagraphFormat getLevel(int index)
```


若樣式層級存在則回傳，否則回傳 null。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| index | int | 層級的零基索引。必須位於 0..8 之間。 |

**傳回值:**
[IParagraphFormat](../../com.aspose.slides/iparagraphformat) - 第 [IParagraphFormat](../../com.aspose.slides/iparagraphformat) 級的格式化。
### getDefaultParagraphFormat() {#getDefaultParagraphFormat--}
```
public final IParagraphFormat getDefaultParagraphFormat()
```


預設段落屬性。唯讀 [IParagraphFormat](../../com.aspose.slides/iparagraphformat)。

**傳回值:**
[IParagraphFormat](../../com.aspose.slides/iparagraphformat)
### getEffective() {#getEffective--}
```
public final ITextStyleEffectiveData getEffective()
```


取得套用繼承後的有效文字樣式格式化資料。

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


**傳回值:**
[ITextStyleEffectiveData](../../com.aspose.slides/itextstyleeffectivedata) - 一個 [ITextStyleEffectiveData](../../com.aspose.slides/itextstyleeffectivedata)。