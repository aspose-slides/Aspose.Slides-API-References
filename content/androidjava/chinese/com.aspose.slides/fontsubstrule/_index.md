---
title: FontSubstRule
second_title: Aspose.Slides Android 通过 Java API 参考
description: 表示字体替换信息
type: docs
url: /zh/com.aspose.slides/fontsubstrule/
---
**继承:**
java.lang.Object

**实现的所有接口:**
[com.aspose.slides.IFontSubstRule](../../com.aspose.slides/ifontsubstrule)
```
public class FontSubstRule implements IFontSubstRule
```

表示字体替换信息
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [FontSubstRule(IFontData sourceFont, IFontData destFont)](#FontSubstRule-com.aspose.slides.IFontData-com.aspose.slides.IFontData-) | 创建新实例。 |
| [FontSubstRule(IFontData sourceFont, IFontData destFont, int fontSubstRule)](#FontSubstRule-com.aspose.slides.IFontData-com.aspose.slides.IFontData-int-) | 创建新实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getSourceFont()](#getSourceFont--) | 要替换的字体。 |
| [getDestFont()](#getDestFont--) | 用于替换的字体。 |
| [getReplaceFontCondition()](#getReplaceFontCondition--) | 用于替换的规则。 |
### FontSubstRule(IFontData sourceFont, IFontData destFont) {#FontSubstRule-com.aspose.slides.IFontData-com.aspose.slides.IFontData-}
```
public FontSubstRule(IFontData sourceFont, IFontData destFont)
```

创建新实例。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| sourceFont | [IFontData](../../com.aspose.slides/ifontdata) | 源字体。 |
| destFont | [IFontData](../../com.aspose.slides/ifontdata) | 目标字体。 |

### FontSubstRule(IFontData sourceFont, IFontData destFont, int fontSubstRule) {#FontSubstRule-com.aspose.slides.IFontData-com.aspose.slides.IFontData-int-}
```
public FontSubstRule(IFontData sourceFont, IFontData destFont, int fontSubstRule)
```

创建新实例。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| sourceFont | [IFontData](../../com.aspose.slides/ifontdata) | 源字体。 |
| destFont | [IFontData](../../com.aspose.slides/ifontdata) | 目标字体。 |
| fontSubstRule | int | 字体替换规则。 |

### getSourceFont() {#getSourceFont--}
```
public final IFontData getSourceFont()
```

要替换的字体。只读 [IFontData](../../com.aspose.slides/ifontdata)。

**返回值:**
[IFontData](../../com.aspose.slides/ifontdata)
### getDestFont() {#getDestFont--}
```
public final IFontData getDestFont()
```

用于替换的字体。只读 [IFontData](../../com.aspose.slides/ifontdata)。

**返回值:**
[IFontData](../../com.aspose.slides/ifontdata)
### getReplaceFontCondition() {#getReplaceFontCondition--}
```
public final int getReplaceFontCondition()
```

用于替换的规则。只读 [FontSubstCondition](../../com.aspose.slides/fontsubstcondition)。

**返回值:**
int