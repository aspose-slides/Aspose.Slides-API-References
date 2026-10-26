---
title: IBulletFormatEffectiveData
second_title: Aspose.Slides for Android via Java API 參考文件
description: 包含有效段落項目符號格式屬性的不可變物件。
type: docs
url: /zh-hant/com.aspose.slides/ibulletformateffectivedata/
---```
public interface IBulletFormatEffectiveData
```

包含有效段落項目符號格式屬性的不可變物件。

--------------------

This interface is used as a part of [IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata).
## Methods

| Method | Description |
| --- | --- |
| [getType()](#getType--) | 返回段落的項目符號類型。 |
| [getChar()](#getChar--) | 返回段落的項目符號字元。 |
| [getActualBulletValue()](#getActualBulletValue--) | 返回父段落的實際項目符號值。 |
| [getFont()](#getFont--) | 返回段落的項目符號字體。 |
| [getHeight()](#getHeight--) | 返回段落的項目符號高度。 |
| [getNumberedBulletStartWith()](#getNumberedBulletStartWith--) | 返回用於編號項目符號組的第一個數字。 |
| [getNumberedBulletStyle()](#getNumberedBulletStyle--) | 返回編號項目符號的樣式。 |
| [isBulletHardColor()](#isBulletHardColor--) | 判斷項目符號是否具有自訂顏色，或繼承自段落中的第一個部分。 |
| [isBulletHardFont()](#isBulletHardFont--) | 判斷項目符號是否具有自訂字型，或繼承自段落中的第一個部分。 |
| [getPicture()](#getPicture--) | 返回段落中用作項目符號的圖片。 |
| [getFillFormat()](#getFillFormat--) | 返回段落的項目符號填充格式。 |
### getType() {#getType--}
```
public abstract byte getType()
```

返回段落的項目符號類型。唯讀 [BulletType](../../com.aspose.slides/bullettype)。

**返回：**
byte

### getChar() {#getChar--}
```
public abstract char getChar()
```

返回段落的項目符號字元。唯讀 char。

**返回：**
char

### getActualBulletValue() {#getActualBulletValue--}
```
public abstract String getActualBulletValue()
```

返回父段落的實際項目符號值。唯讀 String。

**返回：**
java.lang.String

### getFont() {#getFont--}
```
public abstract IFontData getFont()
```

返回段落的項目符號字體。唯讀 [IFontData](../../com.aspose.slides/ifontdata)。

**返回：**
[IFontData](../../com.aspose.slides/ifontdata)

### getHeight() {#getHeight--}
```
public abstract float getHeight()
```

返回段落的項目符號高度。唯讀 float。

**返回：**
float

### getNumberedBulletStartWith() {#getNumberedBulletStartWith--}
```
public abstract short getNumberedBulletStartWith()
```

返回用於編號項目符號組的第一個數字。唯讀 short。

**返回：**
short

### getNumberedBulletStyle() {#getNumberedBulletStyle--}
```
public abstract byte getNumberedBulletStyle()
```

返回編號項目符號的樣式。唯讀 [NumberedBulletStyle](../../com.aspose.slides/numberedbulletstyle)。

**返回：**
byte

### isBulletHardColor() {#isBulletHardColor--}
```
public abstract boolean isBulletHardColor()
```

判斷項目符號是否具有自訂顏色，或繼承自段落中的第一個部分。若項目符號具有自訂顏色則返回 **true**，若繼承則返回 **false**。唯讀 boolean。

**返回：**
boolean

### isBulletHardFont() {#isBulletHardFont--}
```
public abstract boolean isBulletHardFont()
```

判斷項目符號是否具有自訂字型，或繼承自段落中的第一個部分。若項目符號具有自訂字型則返回 **true**，若繼承則返回 **true**。唯讀 boolean。

**返回：**
boolean

### getPicture() {#getPicture--}
```
public abstract IPictureEffectiveData getPicture()
```

返回段落中用作項目符號的圖片。唯讀 [IPictureEffectiveData](../../com.aspose.slides/ipictureeffectivedata)。

**返回：**
[IPictureEffectiveData](../../com.aspose.slides/ipictureeffectivedata)

### getFillFormat() {#getFillFormat--}
```
public abstract IFillFormatEffectiveData getFillFormat()
```

返回段落的項目符號填充格式。唯讀 [IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata)。

--------------------

> ```
> This example demonstrates retrieving bullet's fill effective data.
>  
>  Presentation pres = new Presentation("SomePresentation.pptx");
>  try {
>      // 假設第一張投影片上的第一個形狀是帶有文字的 AutoShape...
>      // 輸出有關文字段落項目符號的資訊
>      AutoShape autoShape = (AutoShape)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      for (IParagraph para : autoShape.getTextFrame().getParagraphs())
>      {
>          IBulletFormatEffectiveData bulletFormatEffective = para.getParagraphFormat().getBullet().getEffective();
>          System.out.println("Bullet type: " + bulletFormatEffective.getType());
>          if (bulletFormatEffective.getType() != BulletType.None)
>          {
>              System.out.println("Bullet fill type: " + bulletFormatEffective.getFillFormat().getFillType());
>              switch (bulletFormatEffective.getFillFormat().getFillType())
>              {
>                  case FillType.Solid:
>                      System.out.println("Solid fill color: " + bulletFormatEffective.getFillFormat().getSolidFillColor());
>                      break;
>                  case FillType.Gradient:
>                      System.out.println("Gradient stops count: " + bulletFormatEffective.getFillFormat().getGradientFormat().getGradientStops().size());
>                      for (IGradientStopEffectiveData gradStop : bulletFormatEffective.getFillFormat().getGradientFormat().getGradientStops())
>                          System.out.println(gradStop.getPosition() + ": " + gradStop.getColor());
>                      break;
>                  case FillType.Pattern:
>                      System.out.println("Pattern style: " + bulletFormatEffective.getFillFormat().getPatternFormat().getPatternStyle());
>                      System.out.println("Fore color: " + bulletFormatEffective.getFillFormat().getPatternFormat().getForeColor());
>                      System.out.println("Back color: " + bulletFormatEffective.getFillFormat().getPatternFormat().getBackColor());
>                      break;
>              }
>          }
>          System.out.println();
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**返回：**
[IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata)