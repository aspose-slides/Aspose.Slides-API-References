---
title: FontSubstRule
second_title: Aspose.Slides for Java API 參考文件
description: 表示字型替代資訊
type: docs
url: /zh-hant/com.aspose.slides/fontsubstrule/
---
**繼承：**
java.lang.Object

**所有已實作介面：**
[com.aspose.slides.IFontSubstRule](../../com.aspose.slides/ifontsubstrule)
```
public class FontSubstRule implements IFontSubstRule
```

表示字型替代資訊
## 建構子

| 建構子 | 說明 |
| --- | --- |
| [FontSubstRule(IFontData sourceFont, IFontData destFont)](#FontSubstRule-com.aspose.slides.IFontData-com.aspose.slides.IFontData-) | 建立新實例。 |
| [FontSubstRule(IFontData sourceFont, IFontData destFont, int fontSubstRule)](#FontSubstRule-com.aspose.slides.IFontData-com.aspose.slides.IFontData-int-) | 建立新實例。 |
## 方法

| 方法 | 說明 |
| --- | --- |
| [getSourceFont()](#getSourceFont--) | 要替代的字型。 |
| [getDestFont()](#getDestFont--) | 用於替代的字型。 |
| [getReplaceFontCondition()](#getReplaceFontCondition--) | 套用於替代的規則。 |
### FontSubstRule(IFontData sourceFont, IFontData destFont) {#FontSubstRule-com.aspose.slides.IFontData-com.aspose.slides.IFontData-}
```
public FontSubstRule(IFontData sourceFont, IFontData destFont)
```

建立新實例。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| sourceFont | [IFontData](../../com.aspose.slides/ifontdata) | 來源字型。 |
| destFont | [IFontData](../../com.aspose.slides/ifontdata) | 目標字型。 |

### FontSubstRule(IFontData sourceFont, IFontData destFont, int fontSubstRule) {#FontSubstRule-com.aspose.slides.IFontData-com.aspose.slides.IFontData-int-}
```
public FontSubstRule(IFontData sourceFont, IFontData destFont, int fontSubstRule)
```

建立新實例。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| sourceFont | [IFontData](../../com.aspose.slides/ifontdata) | 來源字型。 |
| destFont | [IFontData](../../com.aspose.slides/ifontdata) | 目標字型。 |
| fontSubstRule | int | 字型替代規則。 |

### getSourceFont() {#getSourceFont--}
```
public final IFontData getSourceFont()
```

要替代的字型。唯讀 [IFontData](../../com.aspose.slides/ifontdata)。

**返回值：**
[IFontData](../../com.aspose.slides/ifontdata)
### getDestFont() {#getDestFont--}
```
public final IFontData getDestFont()
```

用於替代的字型。唯讀 [IFontData](../../com.aspose.slides/ifontdata)。

**返回值：**
[IFontData](../../com.aspose.slides/ifontdata)
### getReplaceFontCondition() {#getReplaceFontCondition--}
```
public final int getReplaceFontCondition()
```

套用於替代的規則。唯讀 [FontSubstCondition](../../com.aspose.slides/fontsubstcondition)。

**返回值：**
int