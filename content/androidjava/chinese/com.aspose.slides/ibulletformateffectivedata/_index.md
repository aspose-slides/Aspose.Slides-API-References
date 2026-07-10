---
title: IBulletFormatEffectiveData
second_title: Aspose.Slides for Android via Java API Reference
description: Immutable object which contains effective paragraph bullet formatting properties.
type: docs
url: /zh/com.aspose.slides/ibulletformateffectivedata/
---```
public interface IBulletFormatEffectiveData
```

不可变对象，包含有效的段落项目符号格式属性。

--------------------

此接口用作 [IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata) 的一部分。

## 方法

| 方法 | 描述 |
| --- | --- |
| [getType()](#getType--) | 返回段落的项目符号类型。 |
| [getChar()](#getChar--) | 返回段落的项目符号字符。 |
| [getActualBulletValue()](#getActualBulletValue--) | 返回父段落的实际项目符号值。 |
| [getFont()](#getFont--) | 返回段落的项目符号字体。 |
| [getHeight()](#getHeight--) | 返回段落的项目符号高度。 |
| [getNumberedBulletStartWith()](#getNumberedBulletStartWith--) | 返回用于编号项目符号组的起始数字。 |
| [getNumberedBulletStyle()](#getNumberedBulletStyle--) | 返回编号项目符号的样式。 |
| [isBulletHardColor()](#isBulletHardColor--) | 确定项目符号是否拥有自定义颜色，或从段落的第一段继承颜色。 |
| [isBulletHardFont()](#isBulletHardFont--) | 确定项目符号是否拥有自定义字体，或从段落的第一段继承字体。 |
| [getPicture()](#getPicture--) | 返回段落中用作项目符号的图片。 |
| [getFillFormat()](#getFillFormat--) | 返回段落的项目符号填充格式。 |

### getType() {#getType--}
```
public abstract byte getType()
```

返回段落的项目符号类型。只读 [BulletType](../../com.aspose.slides/bullettype)。

**返回:**
byte

### getChar() {#getChar--}
```
public abstract char getChar()
```

返回段落的项目符号字符。只读 char。

**返回:**
char

### getActualBulletValue() {#getActualBulletValue--}
```
public abstract String getActualBulletValue()
```

返回父段落的实际项目符号值。只读 String。

**返回:**
java.lang.String

### getFont() {#getFont--}
```
public abstract IFontData getFont()
```

返回段落的项目符号字体。只读 [IFontData](../../com.aspose.slides/ifontdata)。

**返回:**
[IFontData](../../com.aspose.slides/ifontdata)

### getHeight() {#getHeight--}
```
public abstract float getHeight()
```

返回段落的项目符号高度。只读 float。

**返回:**
float

### getNumberedBulletStartWith() {#getNumberedBulletStartWith--}
```
public abstract short getNumberedBulletStartWith()
```

返回用于编号项目符号组的起始数字。只读 short。

**返回:**
short

### getNumberedBulletStyle() {#getNumberedBulletStyle--}
```
public abstract byte getNumberedBulletStyle()
```

返回编号项目符号的样式。只读 [NumberedBulletStyle](../../com.aspose.slides/numberedbulletstyle)。

**返回:**
byte

### isBulletHardColor() {#isBulletHardColor--}
```
public abstract boolean isBulletHardColor()
```

确定项目符号是否拥有自定义颜色，或从段落的第一段继承颜色。返回 **true** 表示项目符号拥有自定义颜色，返回 **false** 表示项目符号从段落的第一段继承颜色。只读 boolean。

**返回:**
boolean

### isBulletHardFont() {#isBulletHardFont--}
```
public abstract boolean isBulletHardFont()
```

确定项目符号是否拥有自定义字体，或从段落的第一段继承字体。返回 **true** 表示项目符号拥有自定义字体，返回 **true** 表示项目符号从段落的第一段继承字体。只读 boolean。

**返回:**
boolean

### getPicture() {#getPicture--}
```
public abstract IPictureEffectiveData getPicture()
```

返回段落中用作项目符号的图片。只读 [IPictureEffectiveData](../../com.aspose.slides/ipictureeffectivedata)。

**返回:**
[IPictureEffectiveData](../../com.aspose.slides/ipictureeffectivedata)

### getFillFormat() {#getFillFormat--}
```
public abstract IFillFormatEffectiveData getFillFormat()
```

返回段落的项目符号填充格式。只读 [IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata)。

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

**返回:**
[IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata)