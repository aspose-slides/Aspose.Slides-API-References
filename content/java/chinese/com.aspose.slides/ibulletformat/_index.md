---
title: IBulletFormat
second_title: Aspose.Slides for Java API 参考
description: 表示段落项目符号格式属性。
type: docs
url: /zh/com.aspose.slides/ibulletformat/
---```
public interface IBulletFormat
```

表示段落项目符号格式属性。
## 方法

| 方法 | 描述 |
| --- | --- |
| [getType()](#getType--) | 返回或设置段落的项目符号类型（不继承）。 |
| [setType(byte value)](#setType-byte-) | 返回或设置段落的项目符号类型（不继承）。 |
| [getChar()](#getChar--) | 返回或设置段落的项目符号字符（不继承）。 |
| [setChar(char value)](#setChar-char-) | 返回或设置段落的项目符号字符（不继承）。 |
| [getFont()](#getFont--) | 返回或设置段落的项目符号字体（不继承）。 |
| [setFont(IFontData value)](#setFont-com.aspose.slides.IFontData-) | 返回或设置段落的项目符号字体（不继承）。 |
| [getHeight()](#getHeight--) | 返回或设置段落的项目符号高度（不继承）。 |
| [setHeight(float value)](#setHeight-float-) | 返回或设置段落的项目符号高度（不继承）。 |
| [getColor()](#getColor--) | 返回段落中项目符号的颜色格式（不继承）。 |
| [getPicture()](#getPicture--) | 返回段落中用作项目符号的图片（不继承）。 |
| [getNumberedBulletStartWith()](#getNumberedBulletStartWith--) | 返回或设置用于编号项目符号组的第一个数字（不继承）。 |
| [setNumberedBulletStartWith(short value)](#setNumberedBulletStartWith-short-) | 返回或设置用于编号项目符号组的第一个数字（不继承）。 |
| [getNumberedBulletStyle()](#getNumberedBulletStyle--) | 返回或设置编号项目符号的样式（不继承）。 |
| [setNumberedBulletStyle(byte value)](#setNumberedBulletStyle-byte-) | 返回或设置编号项目符号的样式（不继承）。 |
| [isBulletHardColor()](#isBulletHardColor--) | 确定项目符号是否拥有自定义颜色，或从段落的第一部分继承颜色。 |
| [setBulletHardColor(byte value)](#setBulletHardColor-byte-) | 确定项目符号是否拥有自定义颜色，或从段落的第一部分继承颜色。 |
| [isBulletHardFont()](#isBulletHardFont--) | 确定项目符号是否拥有自定义字体，或从段落的第一部分继承字体。 |
| [setBulletHardFont(byte value)](#setBulletHardFont-byte-) | 确定项目符号是否拥有自定义字体，或从段落的第一部分继承字体。 |
| [applyDefaultParagraphIndentsShifts()](#applyDefaultParagraphIndentsShifts--) | 当启用项目符号时（如 PowerPoint 在启用段落项目符号/编号时的行为），为有效段落的缩进和左边距设置默认的非零偏移。 |
| [getEffective()](#getEffective--) | 获取应用继承后的有效项目符号格式数据。 |
### getType() {#getType--}
```
public abstract byte getType()
```

返回或设置段落的项目符号类型（不继承）。读/写 [BulletType](../../com.aspose.slides/bullettype)。

**返回：**
byte
### setType(byte value) {#setType-byte-}
```
public abstract void setType(byte value)
```

返回或设置段落的项目符号类型（不继承）。读/写 [BulletType](../../com.aspose.slides/bullettype)。

**参数：**
| 参数 | 类型 | 说明 |
| --- | --- | --- |
| value | byte |  |
### getChar() {#getChar--}
```
public abstract char getChar()
```

返回或设置段落的项目符号字符（不继承）。读/写 char。

**返回：**
char
### setChar(char value) {#setChar-char-}
```
public abstract void setChar(char value)
```

返回或设置段落的项目符号字符（不继承）。读/写 char。

**参数：**
| 参数 | 类型 | 说明 |
| --- | --- | --- |
| value | char |  |
### getFont() {#getFont--}
```
public abstract IFontData getFont()
```

返回或设置段落的项目符号字体（不继承）。读/写 [IFontData](../../com.aspose.slides/ifontdata)。

**返回：**
[IFontData](../../com.aspose.slides/ifontdata)
### setFont(IFontData value) {#setFont-com.aspose.slides.IFontData-}
```
public abstract void setFont(IFontData value)
```

返回或设置段落的项目符号字体（不继承）。读/写 [IFontData](../../com.aspose.slides/ifontdata)。

**参数：**
| 参数 | 类型 | 说明 |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |
### getHeight() {#getHeight--}
```
public abstract float getHeight()
```

返回或设置段落的项目符号高度（不继承）。值 Float.NaN 表示项目符号从段落的第一部分继承高度。读/写 float。

**返回：**
float
### setHeight(float value) {#setHeight-float-}
```
public abstract void setHeight(float value)
```

返回或设置段落的项目符号高度（不继承）。值 Float.NaN 表示项目符号从段落的第一部分继承高度。读/写 float。

**参数：**
| 参数 | 类型 | 说明 |
| --- | --- | --- |
| value | float |  |
### getColor() {#getColor--}
```
public abstract IColorFormat getColor()
```

返回段落中项目符号的颜色格式（不继承）。只读 [IColorFormat](../../com.aspose.slides/icolorformat)。

**返回：**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getPicture() {#getPicture--}
```
public abstract ISlidesPicture getPicture()
```

返回段落中用作项目符号的图片（不继承）。只读 [ISlidesPicture](../../com.aspose.slides/islidespicture)。

**返回：**
[ISlidesPicture](../../com.aspose.slides/islidespicture)
### getNumberedBulletStartWith() {#getNumberedBulletStartWith--}
```
public abstract short getNumberedBulletStartWith()
```

返回或设置用于编号项目符号组的第一个数字（不继承）。读/写 short。

**返回：**
short
### setNumberedBulletStartWith(short value) {#setNumberedBulletStartWith-short-}
```
public abstract void setNumberedBulletStartWith(short value)
```

返回或设置用于编号项目符号组的第一个数字（不继承）。读/写 short。

**参数：**
| 参数 | 类型 | 说明 |
| --- | --- | --- |
| value | short |  |
### getNumberedBulletStyle() {#getNumberedBulletStyle--}
```
public abstract byte getNumberedBulletStyle()
```

返回或设置编号项目符号的样式（不继承）。读/写 [NumberedBulletStyle](../../com.aspose.slides/numberedbulletstyle)(\#getNumberedBulletStyle.getNumberedBulletStyle/\#setNumberedBulletStyle(byte).setNumberedBulletStyle(byte))。

**返回：**
byte
### setNumberedBulletStyle(byte value) {#setNumberedBulletStyle-byte-}
```
public abstract void setNumberedBulletStyle(byte value)
```

返回或设置编号项目符号的样式（不继承）。读/写 [NumberedBulletStyle](../../com.aspose.slides/numberedbulletstyle)(\#getNumberedBulletStyle.getNumberedBulletStyle/\#setNumberedBulletStyle(byte).setNumberedBulletStyle(byte))。

**参数：**
| 参数 | 类型 | 说明 |
| --- | --- | --- |
| value | byte |  |
### isBulletHardColor() {#isBulletHardColor--}
```
public abstract byte isBulletHardColor()
```

确定项目符号是否拥有自定义颜色，或从段落的第一部分继承颜色。**NullableBool#True** 表示项目符号拥有自定义颜色，**NullableBool#False** 表示项目符号从段落的第一部分继承颜色。读/写 [NullableBool](../../com.aspose.slides/nullablebool)。

**返回：**
byte
### setBulletHardColor(byte value) {#setBulletHardColor-byte-}
```
public abstract void setBulletHardColor(byte value)
```

确定项目符号是否拥有自定义颜色，或从段落的第一部分继承颜色。**NullableBool#True** 表示项目符号拥有自定义颜色，**NullableBool#False** 表示项目符号从段落的第一部分继承颜色。读/写 [NullableBool](../../com.aspose.slides/nullablebool)。

**参数：**
| 参数 | 类型 | 说明 |
| --- | --- | --- |
| value | byte |  |
### isBulletHardFont() {#isBulletHardFont--}
```
public abstract byte isBulletHardFont()
```

确定项目符号是否拥有自定义字体，或从段落的第一部分继承字体。**NullableBool#True** 表示项目符号拥有自定义字体，**NullableBool#False** 表示项目符号从段落的第一部分继承字体。读/写 [NullableBool](../../com.aspose.slides/nullablebool)。

**返回：**
byte
### setBulletHardFont(byte value) {#setBulletHardFont-byte-}
```
public abstract void setBulletHardFont(byte value)
```

确定项目符号是否拥有自定义字体，或从段落的第一部分继承字体。**NullableBool#True** 表示项目符号拥有自定义字体，**NullableBool#False** 表示项目符号从段落的第一部分继承字体。读/写 [NullableBool](../../com.aspose.slides/nullablebool)。

**参数：**
| 参数 | 类型 | 说明 |
| --- | --- | --- |
| value | byte |  |
### applyDefaultParagraphIndentsShifts() {#applyDefaultParagraphIndentsShifts--}
```
public abstract void applyDefaultParagraphIndentsShifts()
```

当启用项目符号时（如 PowerPoint 在启用段落项目符号/编号时的行为），为有效段落的缩进和左边距设置默认的非零偏移。如果禁用项目符号，则仅重置段落的缩进和左边距（如 PowerPoint 在禁用段落项目符号/编号时的行为）。缩进偏移会根据当前项目符号上下文——IBulletFormat.Type、.NumberedBulletStyle 和第一部分的 FontHeight——进行应用。非零的缩进偏移会作用于当前段落的有效 Indent 和 MarginLeft（使结果值成为局部值）。
### getEffective() {#getEffective--}
```
public abstract IBulletFormatEffectiveData getEffective()
```

获取应用继承后的有效项目符号格式数据。

--------------------

> ```
> This example demonstrates getting some effective bullet format properties.
>  
>  Presentation pres = new Presentation("MyPresentation.pptx");
>  try {
>      IAutoShape shape = (IAutoShape)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      IBulletFormatEffectiveData effectiveBulletFormat = shape.getTextFrame().getParagraphs().get_Item(0).getParagraphFormat().getBullet().getEffective();
>      System.out.println("Bullet type: " + effectiveBulletFormat.getType());
>      if (effectiveBulletFormat.getType() == BulletType.Numbered)
>      {
>          System.out.println("Numbered style: " + effectiveBulletFormat.getNumberedBulletStyle());
>          System.out.println("Starting number: " + effectiveBulletFormat.getNumberedBulletStartWith());
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**返回：**
[IBulletFormatEffectiveData](../../com.aspose.slides/ibulletformateffectivedata) - A [IBulletFormatEffectiveData](../../com.aspose.slides/ibulletformateffectivedata).