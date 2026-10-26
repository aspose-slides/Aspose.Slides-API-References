---
title: FontSubstRule
second_title: Aspose.Slides for Android via Java API 參考文件
description: 代表字型替代資訊
type: docs
url: /zh-hant/com.aspose.slides/fontsubstrule/
---
**繼承：**
java.lang.Object

**所有已實作的介面：**
[com.aspose.slides.IFontSubstRule](../../com.aspose.slides/ifontsubstrule)
```
public class FontSubstRule implements IFontSubstRule
```

代表字型替代資訊
## 建構函式

| 建構函式 | 描述 |
| --- | --- |
| [FontSubstRule(IFontData sourceFont, IFontData destFont)](#FontSubstRule-com.aspose.slides.IFontData-com.aspose.slides.IFontData-) | 建立新實例。 |
| [FontSubstRule(IFontData sourceFont, IFontData destFont, int fontSubstRule)](#FontSubstRule-com.aspose.slides.IFontData-com.aspose.slides.IFontData-int-) | 建立新實例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getSourceFont()](#getSourceFont--) | 要替代的字型。 |
| [getDestFont()](#getDestFont--) | 用於替代的字型。 |
| [getReplaceFontCondition()](#getReplaceFontCondition--) | 用於替代的規則。 |
### FontSubstRule(IFontData sourceFont, IFontData destFont) {#FontSubstRule-com.aspose.slides.IFontData-com.aspose.slides.IFontData-}
```
public FontSubstRule(IFontData sourceFont, IFontData destFont)
```


建立新實例。

**參數：**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| sourceFont | [IFontData](../../com.aspose.slides/ifontdata) | 來源字型。 |
| destFont | [IFontData](../../com.aspose.slides/ifontdata) | 目標字型。 |

### FontSubstRule(IFontData sourceFont, IFontData destFont, int fontSubstRule) {#FontSubstRule-com.aspose.slides.IFontData-com.aspose.slides.IFontData-int-}
```
public FontSubstRule(IFontData sourceFont, IFontData destFont, int fontSubstRule)
```


建立新實例。

**參數：**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| sourceFont | [IFontData](../../com.aspose.slides/ifontdata) | 來源字型。 |
| destFont | [IFontData](../../com.aspose.slides/ifontdata) | 目標字型。 |
| fontSubstRule | int | 字型替代規則。 |

### getSourceFont() {#getSourceFont--}
```
public final IFontData getSourceFont()
```


要替代的字型。唯讀 [IFontData](../../com.aspose.slides/ifontdata)。

**回傳：**
[IFontData](../../com.aspose.slides/ifontdata)
### getDestFont() {#getDestFont--}
```
public final IFontData getDestFont()
```


用於替代的字型。唯讀 [IFontData](../../com.aspose.slides/ifontdata)。

**回傳：**
[IFontData](../../com.aspose.slides/ifontdata)
### getReplaceFontCondition() {#getReplaceFontCondition--}
```
public final int getReplaceFontCondition()
```


用於替代的規則。唯讀 [FontSubstCondition](../../com.aspose.slides/fontsubstcondition)。

**回傳：**
int