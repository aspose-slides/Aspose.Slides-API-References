---
title: ITextStyle
second_title: Aspose.Slides for Java API 参考
description: 文本样式格式属性。
type: docs
url: /zh/com.aspose.slides/itextstyle/
---```
public interface ITextStyle
```

文本样式格式属性。
## 方法

| 方法 | 描述 |
| --- | --- |
| [getLevel(int index)](#getLevel-int-) | 如果样式级别存在则返回它，否则返回 null。 |
| [getDefaultParagraphFormat()](#getDefaultParagraphFormat--) | 默认段落属性。 |
| [getEffective()](#getEffective--) | 获取应用继承后的有效文本样式格式数据。 |
### getLevel(int index) {#getLevel-int-}
```
public abstract IParagraphFormat getLevel(int index)
```

如果样式级别存在则返回它，否则返回 null。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 级别的零基索引。必须位于 0..8 区间。 |

**返回值:**
[IParagraphFormat](../../com.aspose.slides/iparagraphformat) - 级别 [IParagraphFormat](../../com.aspose.slides/iparagraphformat) 的格式。

### getDefaultParagraphFormat() {#getDefaultParagraphFormat--}
```
public abstract IParagraphFormat getDefaultParagraphFormat()
```

默认段落属性。只读 [IParagraphFormat](../../com.aspose.slides/iparagraphformat)。

**返回值:**
[IParagraphFormat](../../com.aspose.slides/iparagraphformat)

### getEffective() {#getEffective--}
```
public abstract ITextStyleEffectiveData getEffective()
```

获取应用继承后的有效文本样式格式数据。

**返回值:**
[ITextStyleEffectiveData](../../com.aspose.slides/itextstyleeffectivedata) - 一个 [ITextStyleEffectiveData](../../com.aspose.slides/itextstyleeffectivedata)。