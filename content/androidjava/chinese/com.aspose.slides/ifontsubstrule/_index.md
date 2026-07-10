---
title: IFontSubstRule
second_title: Aspose.Slides for Android via Java API Reference
description: 表示字体替换信息
type: docs
url: /zh/com.aspose.slides/ifontsubstrule/
---```
public interface IFontSubstRule
```

表示字体替换信息

## 方法

| 方法 | 描述 |
| --- | --- |
| [getSourceFont()](#getSourceFont--) | 要替换的字体（只读） [IFontData](../../com.aspose.slides/ifontdata)。 |
| [getDestFont()](#getDestFont--) | 用于替换的字体（只读） [IFontData](../../com.aspose.slides/ifontdata)。 |
| [getReplaceFontCondition()](#getReplaceFontCondition--) | 用于替换的规则（只读） [FontSubstCondition](../../com.aspose.slides/fontsubstcondition)。 |

### getSourceFont() {#getSourceFont--}
```
public abstract IFontData getSourceFont()
```

要替换的字体（只读） [IFontData](../../com.aspose.slides/ifontdata)。

**返回：**
[IFontData](../../com.aspose.slides/ifontdata)

### getDestFont() {#getDestFont--}
```
public abstract IFontData getDestFont()
```

用于替换的字体（只读） [IFontData](../../com.aspose.slides/ifontdata)。

**返回：**
[IFontData](../../com.aspose.slides/ifontdata)

### getReplaceFontCondition() {#getReplaceFontCondition--}
```
public abstract int getReplaceFontCondition()
```

用于替换的规则（只读） [FontSubstCondition](../../com.aspose.slides/fontsubstcondition)。

**返回：**
int