---
title: ITextStyleEffectiveData
second_title: Aspose.Slides for Android via Java API Reference
description: 包含有效文本样式属性的不可变对象。
type: docs
url: /zh/com.aspose.slides/itextstyleeffectivedata/
---```
public interface ITextStyleEffectiveData
```

包含有效文本样式属性的不可变对象。

--------------------

此接口与 [ITextStyle](../../com.aspose.slides/itextstyle) 接口一起使用，以在应用继承后返回有效的格式化值。
## 方法

| 方法 | 描述 |
| --- | --- |
| [getLevel(int index)](#getLevel-int-) | 返回有效样式的级别。 |
| [getDefaultParagraphFormat()](#getDefaultParagraphFormat--) | 返回有效的默认段落属性。 |
### getLevel(int index) {#getLevel-int-}
```
public abstract IParagraphFormatEffectiveData getLevel(int index)
```


返回有效样式的级别。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 级别的零基索引。必须位于 0..8 区间。 |

**返回:**
[IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata) - [IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata) 级别的有效格式化。
### getDefaultParagraphFormat() {#getDefaultParagraphFormat--}
```
public abstract IParagraphFormatEffectiveData getDefaultParagraphFormat()
```


返回有效的默认段落属性。只读 [IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata)。

**返回:**
[IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata)