---
title: BulletFormat
second_title: Aspose.Sildes for PHP 通过 Java API 参考
description: 
type: docs

url: /zh/aspose.slides/bulletformat/
---
## BulletFormat 类

 表示段落项目符号格式属性。

### applyDefaultParagraphIndentsShifts {#applyDefaultParagraphIndentsShifts}

| 名称 | 描述 |
| --- | --- |
| applyDefaultParagraphIndentsShifts () | 在启用项目符号时，为有效段落的 Indent 和 MarginLeft 设置默认的非零偏移（类似 PowerPoint 在启用段落项目符号/编号时的行为）。如果禁用项目符号，则仅重置段落的 Indent 和 MarginLeft（类似 PowerPoint 在禁用段落项目符号/编号时的行为）。缩进偏移依据当前项目符号上下文 - IBulletFormat.Type、.NumberedBulletStyle 和第一段落部分的 FontHeight 来应用。非零缩进偏移会应用到当前段落的有效 Indent 和 MarginLeft（使结果值为局部值）。 |

**返回:**
void

**异常**

| 错误 | 条件 |
| --- | --- |
| InvalidOperationException | 在以下情况下调用此方法会抛出 InvalidOperationException：如果父格式化对象不是段落（例如调用 ITextStyle.DefaultParagraphFormat.Bullet.ApplyDefaultParagraphIndentsShifts() 将抛出异常）；或如果段落未添加到任何 ITextFrame.Paragraphs 集合中（请先添加）； |

---


### getChar {#getChar}

| 名称 | 描述 |
| --- | --- |
| getChar () | 返回或设置段落的项目符号字符，且不继承。读/写 char。 |

**返回:**
char

---


### getColor {#getColor}

| 名称 | 描述 |
| --- | --- |
| getColor () | 返回段落中项目符号的颜色格式，且不继承。只读 IColorFormat。 |

**返回:**
[ColorFormat](../colorformat)

---


### getEffective {#getEffective}

| 名称 | 描述 |
| --- | --- |
| getEffective () | 获取在应用继承后的有效项目符号格式数据。 |

**返回:**
BulletFormatEffectiveData

---


### getFont {#getFont}

| 名称 | 描述 |
| --- | --- |
| getFont () | 返回或设置段落的项目符号字体，且不继承。读/写 IFontData。 |

**返回:**
[FontData](../fontdata)

---


### getHeight {#getHeight}

| 名称 | 描述 |
| --- | --- |
| getHeight () | 返回或设置段落的项目符号高度，且不继承。值 Float.NaN 表示项目符号从段落的第一部分继承高度。读/写 float。负数高度值表示以点为单位，正数高度值表示相对于周围文本的百分比。 |

**返回:**
float

---


### getNumberedBulletStartWith {#getNumberedBulletStartWith}

| 名称 | 描述 |
| --- | --- |
| getNumberedBulletStartWith () | 返回或设置用于编号项目符号组的起始数字，且不继承。读/写 short。 |

**返回:**
short

---


### getNumberedBulletStyle {#getNumberedBulletStyle}

| 名称 | 描述 |
| --- | --- |
| getNumberedBulletStyle () | 返回或设置编号项目符号的样式，且不继承。读/写 NumberedBulletStyle。 |

**返回:**
byte

---


### getPicture {#getPicture}

| 名称 | 描述 |
| --- | --- |
| getPicture () | 返回段落中用作项目符号的图片，且不继承。只读 ISlidesPicture。 |

**返回:**
[Picture](../picture)

---


### getType {#getType}

| 名称 | 描述 |
| --- | --- |
| getType () | 返回或设置段落的项目符号类型，且不继承。读/写 BulletType。 |

**返回:**
byte

---


### getVersion {#getVersion}

| 名称 | 描述 |
| --- | --- |
| getVersion () |  |


**返回:**
long

---


### isBulletHardColor {#isBulletHardColor}

| 名称 | 描述 |
| --- | --- |
| isBulletHardColor () | 确定项目符号是否拥有独立颜色，或从段落的第一部分继承颜色。若项目符号拥有独立颜色则为 NullableBool.True，若从段落的第一部分继承颜色则为 NullableBool.False。读/写 NullableBool。 |

**返回:**
byte

---


### isBulletHardFont {#isBulletHardFont}

| 名称 | 描述 |
| --- | --- |
| isBulletHardFont () | 确定项目符号是否拥有独立字体，或从段落的第一部分继承字体。若项目符号拥有独立字体则为 NullableBool.True，若从段落的第一部分继承字体则为 NullableBool.False。读/写 NullableBool。 |

**返回:**
byte

---


### setBulletHardColor {#setBulletHardColor}

| 名称 | 描述 |
| --- | --- |
| setBulletHardColor (byte) | 确定项目符号是否拥有独立颜色，或从段落的第一部分继承颜色。若项目符号拥有独立颜色则为 NullableBool.True，若从段落的第一部分继承颜色则为 NullableBool.False。读/写 NullableBool。 |

**返回:**
void

---


### setBulletHardFont {#setBulletHardFont}

| 名称 | 描述 |
| --- | --- |
| setBulletHardFont (byte) | 确定项目符号是否拥有独立字体，或从段落的第一部分继承字体。若项目符号拥有独立字体则为 NullableBool.True，若从段落的第一部分继承字体则为 NullableBool.False。读/写 NullableBool。 |

**返回:**
void

---


### setChar {#setChar}

| 名称 | 描述 |
| --- | --- |
| setChar (char) | 返回或设置段落的项目符号字符，且不继承。读/写 char。 |

**返回:**
void

---


### setFont {#setFont}

| 名称 | 描述 |
| --- | --- |
| setFont ([FontData](../fontdata)) | 返回或设置段落的项目符号字体，且不继承。读/写 IFontData。 |

**返回:**
void

---


### setHeight {#setHeight}

| 名称 | 描述 |
| --- | --- |
| setHeight (float) | 返回或设置段落的项目符号高度，且不继承。值 Float.NaN 表示项目符号从段落的第一部分继承高度。读/写 float。负数高度值表示以点为单位，正数高度值表示相对于周围文本的百分比。 |

**返回:**
void

---


### setNumberedBulletStartWith {#setNumberedBulletStartWith}

| 名称 | 描述 |
| --- | --- |
| setNumberedBulletStartWith (short) | 返回或设置用于编号项目符号组的起始数字，且不继承。读/写 short。 |

**返回:**
void

---


### setNumberedBulletStyle {#setNumberedBulletStyle}

| 名称 | 描述 |
| --- | --- |
| setNumberedBulletStyle (byte) | 返回或设置编号项目符号的样式，且不继承。读/写 NumberedBulletStyle。 |

**返回:**
void

---


### setType {#setType}

| 名称 | 描述 |
| --- | --- |
| setType (byte) | 返回或设置段落的项目符号类型，且不继承。读/写 BulletType。 |

**返回:**
void

---