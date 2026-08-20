---
title: IFontSubstRule
second_title: Aspose.Slides for Java API Reference
description: 表示字體替換資訊
type: docs
url: /zh-hant/com.aspose.slides/ifontsubstrule/
---```
public interface IFontSubstRule
```

表示字體替換資訊
## 方法

| 方法 | 描述 |
| --- | --- |
| [getSourceFont()](#getSourceFont--) | 要替代的字體，唯讀 [IFontData](../../com.aspose.slides/ifontdata)。 |
| [getDestFont()](#getDestFont--) | 用於替代的字體，唯讀 [IFontData](../../com.aspose.slides/ifontdata)。 |
| [getReplaceFontCondition()](#getReplaceFontCondition--) | 套用的替代規則，唯讀 [FontSubstCondition](../../com.aspose.slides/fontsubstcondition)。 |
### getSourceFont() {#getSourceFont--}
```
public abstract IFontData getSourceFont()
```

要替代的字體，唯讀 [IFontData](../../com.aspose.slides/ifontdata).

**傳回值:**
[IFontData](../../com.aspose.slides/ifontdata)
### getDestFont() {#getDestFont--}
```
public abstract IFontData getDestFont()
```

用於替代的字體，唯讀 [IFontData](../../com.aspose.slides/ifontdata)。

**傳回值:**
[IFontData](../../com.aspose.slides/ifontdata)
### getReplaceFontCondition() {#getReplaceFontCondition--}
```
public abstract int getReplaceFontCondition()
```

套用的替代規則，唯讀 [FontSubstCondition](../../com.aspose.slides/fontsubstcondition)。

**傳回值:**
int