---
title: IBulletFormatEffectiveData
second_title: Aspose.Slides for Java API 參考文件
description: 不可變的物件，包含有效的段落項目符號格式屬性。
type: docs
url: /zh-hant/com.aspose.slides/ibulletformateffectivedata/
---```
public interface IBulletFormatEffectiveData
```

不可變的物件，包含有效的段落項目符號格式屬性。

--------------------

此介面用作 [IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata) 的一部分。
## 方法

| 方法 | 描述 |
| --- | --- |
| [getType()](#getType--) | 傳回段落的項目符號類型。 |
| [getChar()](#getChar--) | 傳回段落的項目符號字元。 |
| [getActualBulletValue()](#getActualBulletValue--) | 傳回父段落的實際項目符號值。 |
| [getFont()](#getFont--) | 傳回段落的項目符號字型。 |
| [getHeight()](#getHeight--) | 傳回段落的項目符號高度。 |
| [getNumberedBulletStartWith()](#getNumberedBulletStartWith--) | 傳回用於編號項目符號群組的第一個數字。 |
| [getNumberedBulletStyle()](#getNumberedBulletStyle--) | 傳回編號項目符號的樣式。 |
| [isBulletHardColor()](#isBulletHardColor--) | 判斷項目符號是否具有自身顏色或從段落的第一段落部分繼承顏色。 |
| [isBulletHardFont()](#isBulletHardFont--) | 判斷項目符號是否具有自身字型或從段落的第一段落部分繼承字型。 |
| [getPicture()](#getPicture--) | 傳回段落中用作項目符號的圖片。 |
| [getFillFormat()](#getFillFormat--) | 傳回段落的項目符號填充格式。 |
### getType() {#getType--}
```
public abstract byte getType()
```


傳回段落的項目符號類型。唯讀 [BulletType](../../com.aspose.slides/bullettype)。

**Returns:**
byte
### getChar() {#getChar--}
```
public abstract char getChar()
```


傳回段落的項目符號字元。唯讀 char。

**Returns:**
char
### getActualBulletValue() {#getActualBulletValue--}
```
public abstract String getActualBulletValue()
```


傳回父段落的實際項目符號值。唯讀 String。

**Returns:**
java.lang.String
### getFont() {#getFont--}
```
public abstract IFontData getFont()
```


傳回段落的項目符號字型。唯讀 [IFontData](../../com.aspose.slides/ifontdata)。

**Returns:**
[IFontData](../../com.aspose.slides/ifontdata)
### getHeight() {#getHeight--}
```
public abstract float getHeight()
```


傳回段落的項目符號高度。唯讀 float。

**Returns:**
float
### getNumberedBulletStartWith() {#getNumberedBulletStartWith--}
```
public abstract short getNumberedBulletStartWith()
```


傳回用於編號項目符號群組的第一個數字。唯讀 short。

**Returns:**
short
### getNumberedBulletStyle() {#getNumberedBulletStyle--}
```
public abstract byte getNumberedBulletStyle()
```


傳回編號項目符號的樣式。唯讀 [NumberedBulletStyle](../../com.aspose.slides/numberedbulletstyle)。

**Returns:**
byte
### isBulletHardColor() {#isBulletHardColor--}
```
public abstract boolean isBulletHardColor()
```


判斷項目符號是否具有自身顏色或從段落的第一段落部分繼承顏色。若項目符號具有自身顏色，則傳回 **true**，若項目符號從段落的第一段落部分繼承顏色，則傳回 **false**。唯讀 boolean。

**Returns:**
boolean
### isBulletHardFont() {#isBulletHardFont--}
```
public abstract boolean isBulletHardFont()
```


判斷項目符號是否具有自身字型或從段落的第一段落部分繼承字型。若項目符號具有自身字型，則傳回 **true**，若項目符號從段落的第一段落部分繼承字型，則傳回 **true**。唯讀 boolean。

**Returns:**
boolean
### getPicture() {#getPicture--}
```
public abstract IPictureEffectiveData getPicture()
```


傳回段落中用作項目符號的圖片。唯讀 [IPictureEffectiveData](../../com.aspose.slides/ipictureeffectivedata)。

**Returns:**
[IPictureEffectiveData](../../com.aspose.slides/ipictureeffectivedata)
### getFillFormat() {#getFillFormat--}
```
public abstract IFillFormatEffectiveData getFillFormat()
```


傳回段落的項目符號填充格式。唯讀 [IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata)。

--------------------

> ```
> This example demonstrates retrieving bullet's fill effective data.
>  
>  Presentation pres = new Presentation("SomePresentation.pptx");
>  try {
>      // Assume that the first shape on the first slide is AutoShape with some text...
>      // Output information about text paragraphs' bullets
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

**傳回:** [IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata)