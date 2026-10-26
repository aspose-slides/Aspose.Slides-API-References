---
title: ITextStyle
second_title: Aspose.Slides for Android via Java API Reference
description: Text style formatting properties.
type: docs
url: /zh/com.aspose.slides/itextstyle/
---```
public interface ITextStyle
```

文本样式格式属性。
## 方法

| 方法 | 描述 |
| --- | --- |
| [getLevel(int index)](#getLevel-int-) | 如果样式级别存在，则返回该级别；否则返回 null。 |
| [getDefaultParagraphFormat()](#getDefaultParagraphFormat--) | 默认段落属性。 |
| [getEffective()](#getEffective--) | 获取应用了继承的有效文本样式格式数据。 |
### getLevel(int index) {#getLevel-int-}
```
public abstract IParagraphFormat getLevel(int index)
```

如果样式级别存在，则返回该级别；否则返回 null。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 级别的零基索引。必须在 0..8 区间内。 |

**返回值：**
[IParagraphFormat](../../com.aspose.slides/iparagraphformat) - 级别 [IParagraphFormat](../../com.aspose.slides/iparagraphformat) 的格式。

### getDefaultParagraphFormat() {#getDefaultParagraphFormat--}
```
public abstract IParagraphFormat getDefaultParagraphFormat()
```

默认段落属性。只读 [IParagraphFormat](../../com.aspose.slides/iparagraphformat)。

**返回值：**
[IParagraphFormat](../../com.aspose.slides/iparagraphformat)

### getEffective() {#getEffective--}
```
public abstract ITextStyleEffectiveData getEffective()
```

获取应用了继承的有效文本样式格式数据。

**返回值：**
[ITextStyleEffectiveData](../../com.aspose.slides/itextstyleeffectivedata) - 一个 [ITextStyleEffectiveData](../../com.aspose.slides/itextstyleeffectivedata)。