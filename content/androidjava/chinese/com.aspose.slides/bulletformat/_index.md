---
title: BulletFormat
second_title: Aspose.Slides for Android via Java API 参考
description: 表示段落项目符号格式属性。
type: docs
url: /zh/com.aspose.slides/bulletformat/
---
**继承：**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**所有已实现的接口：**
[com.aspose.slides.IBulletFormat](../../com.aspose.slides/ibulletformat)
```
public final class BulletFormat extends PVIObject implements IBulletFormat
```

表示段落项目符号格式属性。

## 方法

| 方法 | 描述 |
| --- | --- |
| [getType()](#getType--) | 返回或设置段落的 bullet type（无继承）。 |
| [setType(byte value)](#setType-byte-) | 返回或设置段落的 bullet type（无继承）。 |
| [getChar()](#getChar--) | 返回或设置段落的 bullet char（无继承）。 |
| [setChar(char value)](#setChar-char-) | 返回或设置段落的 bullet char（无继承）。 |
| [getFont()](#getFont--) | 返回或设置段落的 bullet font（无继承）。 |
| [setFont(IFontData value)](#setFont-com.aspose.slides.IFontData-) | 返回或设置段落的 bullet font（无继承）。 |
| [getHeight()](#getHeight--) | 返回或设置段落的 bullet height（无继承）。 |
| [setHeight(float value)](#setHeight-float-) | 返回或设置段落的 bullet height（无继承）。 |
| [getColor()](#getColor--) | 返回段落中 bullet 的颜色格式（无继承）。 |
| [getNumberedBulletStartWith()](#getNumberedBulletStartWith--) | 返回或设置用于编号 bullet 组的起始数字（无继承）。 |
| [setNumberedBulletStartWith(short value)](#setNumberedBulletStartWith-short-) | 返回或设置用于编号 bullet 组的起始数字（无继承）。 |
| [getNumberedBulletStyle()](#getNumberedBulletStyle--) | 返回或设置编号 bullet 的样式（无继承）。 |
| [setNumberedBulletStyle(byte value)](#setNumberedBulletStyle-byte-) | 返回或设置编号 bullet 的样式（无继承）。 |
| [isBulletHardColor()](#isBulletHardColor--) | 确定 bullet 是否具有独立颜色或从段落的第一部分继承颜色。 |
| [setBulletHardColor(byte value)](#setBulletHardColor-byte-) | 确定 bullet 是否具有独立颜色或从段落的第一部分继承颜色。 |
| [isBulletHardFont()](#isBulletHardFont--) | 确定 bullet 是否具有独立字体或从段落的第一部分继承字体。 |
| [setBulletHardFont(byte value)](#setBulletHardFont-byte-) | 确定 bullet 是否具有独立字体或从段落的第一部分继承字体。 |
| [getPicture()](#getPicture--) | 返回段落中用作 bullet 的图片（无继承）。 |
| [applyDefaultParagraphIndentsShifts()](#applyDefaultParagraphIndentsShifts--) | 当启用 bullet 时，为有效段落的 Indent 和 MarginLeft 设置默认的非零偏移（类似 PowerPoint 在启用段落项目符号/编号时的行为）。 |
| [getEffective()](#getEffective--) | 获取已应用继承的有效 bullet 格式数据。 |
| [getVersion()](#getVersion--) |  |

### getType() {#getType--}
```
public final byte getType()
```

返回或设置段落的 bullet type（无继承）。读/写 [BulletType](../../com.aspose.slides/bullettype)。

**返回：**
byte

### setType(byte value) {#setType-byte-}
```
public final void setType(byte value)
```

返回或设置段落的 bullet type（无继承）。读/写 [BulletType](../../com.aspose.slides/bullettype)。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | byte |  |

### getChar() {#getChar--}
```
public final char getChar()
```

返回或设置段落的 bullet char（无继承）。读/写 char 。

**返回：**
char

### setChar(char value) {#setChar-char-}
```
public final void setChar(char value)
```

返回或设置段落的 bullet char（无继承）。读/写 char 。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | char |  |

### getFont() {#getFont--}
```
public final IFontData getFont()
```

返回或设置段落的 bullet font（无继承）。读/写 [IFontData](../../com.aspose.slides/ifontdata)。

**返回：**
[IFontData](../../com.aspose.slides/ifontdata)

### setFont(IFontData value) {#setFont-com.aspose.slides.IFontData-}
```
public final void setFont(IFontData value)
```

返回或设置段落的 bullet font（无继承）。读/写 [IFontData](../../com.aspose.slides/ifontdata)。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |

### getHeight() {#getHeight--}
```
public final float getHeight()
```

返回或设置段落的 bullet height（无继承）。值 Float.NaN 表示 bullet 从段落的第一部分继承高度。读/写 float 。

---

负值表示以点为单位的高度，正值表示相对于周围文本的百分比。

**返回：**
float

### setHeight(float value) {#setHeight-float-}
```
public final void setHeight(float value)
```

返回或设置段落的 bullet height（无继承）。值 Float.NaN 表示 bullet 从段落的第一部分继承高度。读/写 float 。

---

负值表示以点为单位的高度，正值表示相对于周围文本的百分比。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | float |  |

### getColor() {#getColor--}
```
public final IColorFormat getColor()
```

返回段落中 bullet 的颜色格式（无继承）。只读 [IColorFormat](../../com.aspose.slides/icolorformat)。

**返回：**
[IColorFormat](../../com.aspose.slides/icolorformat)

### getNumberedBulletStartWith() {#getNumberedBulletStartWith--}
```
public final short getNumberedBulletStartWith()
```

返回或设置用于编号 bullet 组的起始数字（无继承）。读/写 short 。

**返回：**
short

### setNumberedBulletStartWith(short value) {#setNumberedBulletStartWith-short-}
```
public final void setNumberedBulletStartWith(short value)
```

返回或设置用于编号 bullet 组的起始数字（无继承）。读/写 short 。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | short |  |

### getNumberedBulletStyle() {#getNumberedBulletStyle--}
```
public final byte getNumberedBulletStyle()
```

返回或设置编号 bullet 的样式（无继承）。读/写 [NumberedBulletStyle](../../com.aspose.slides/numberedbulletstyle)。

**返回：**
byte

### setNumberedBulletStyle(byte value) {#setNumberedBulletStyle-byte-}
```
public final void setNumberedBulletStyle(byte value)
```

返回或设置编号 bullet 的样式（无继承）。读/写 [NumberedBulletStyle](../../com.aspose.slides/numberedbulletstyle)。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | byte |  |

### isBulletHardColor() {#isBulletHardColor--}
```
public final byte isBulletHardColor()
```

确定 bullet 是否具有独立颜色或从段落的第一部分继承颜色。**NullableBool.True** 表示 bullet 有独立颜色，**NullableBool.False** 表示继承颜色。读/写 [NullableBool](../../com.aspose.slides/nullablebool)。

**返回：**
byte

### setBulletHardColor(byte value) {#setBulletHardColor-byte-}
```
public final void setBulletHardColor(byte value)
```

确定 bullet 是否具有独立颜色或从段落的第一部分继承颜色。**NullableBool.True** 表示 bullet 有独立颜色，**NullableBool.False** 表示继承颜色。读/写 [NullableBool](../../com.aspose.slides/nullablebool)。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | byte |  |

### isBulletHardFont() {#isBulletHardFont--}
```
public final byte isBulletHardFont()
```

确定 bullet 是否具有独立字体或从段落的第一部分继承字体。**NullableBool.True** 表示 bullet 有独立字体，**NullableBool.False** 表示继承字体。读/写 [NullableBool](../../com.aspose.slides/nullablebool)。

**返回：**
byte

### setBulletHardFont(byte value) {#setBulletHardFont-byte-}
```
public final void setBulletHardFont(byte value)
```

确定 bullet 是否具有独立字体或从段落的第一部分继承字体。**NullableBool.True** 表示 bullet 有独立字体，**NullableBool.False** 表示继承字体。读/写 [NullableBool](../../com.aspose.slides/nullablebool)。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | byte |  |

### getPicture() {#getPicture--}
```
public final ISlidesPicture getPicture()
```

返回段落中用作 bullet 的图片（无继承）。只读 [ISlidesPicture](../../com.aspose.slides/islidespicture)。

**返回：**
[ISlidesPicture](../../com.aspose.slides/islidespicture)

### applyDefaultParagraphIndentsShifts() {#applyDefaultParagraphIndentsShifts--}
```
public final void applyDefaultParagraphIndentsShifts()
```

当启用 bullet 时，为有效段落的 Indent 和 MarginLeft 设置默认的非零偏移（类似 PowerPoint 在启用段落项目符号/编号时的行为）。如果禁用 bullet，则仅重置段落的 Indent 和 MarginLeft（类似 PowerPoint 在禁用段落项目符号/编号时的行为）。缩进偏移依据当前 bullet 上下文——IBulletFormat.Type、.NumberedBulletStyle 和第一部分的 FontHeight——进行应用。非零缩进偏移会应用到当前段落的有效 Indent 和 MarginLeft（使结果值为局部值）。

### getEffective() {#getEffective--}
```
public final IBulletFormatEffectiveData getEffective()
```

获取已应用继承的有效 bullet 格式数据。

---

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

**Returns:**
[IBulletFormatEffectiveData](../../com.aspose.slides/ibulletformateffectivedata) - A [IBulletFormatEffectiveData](../../com.aspose.slides/ibulletformateffectivedata).
### getVersion() {#getVersion--}
```
public long getVersion()


Version. 只读 long.

**返回：**
long