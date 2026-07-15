---
title: IFontSubstRule
second_title: Aspose.Slides for Android via Java API 參考
description: 表示字體置換資訊
type: docs
url: /zh-hant/com.aspose.slides/ifontsubstrule/
---```
public interface IFontSubstRule
```

表示字體置換資訊
## 方法

| 方法 | 說明 |
| --- | --- |
| [getSourceFont()](#getSourceFont--) | 要替換的字體（唯讀） [IFontData](../../com.aspose.slides/ifontdata). |
| [getDestFont()](#getDestFont--) | 用於置換的字體（唯讀） [IFontData](../../com.aspose.slides/ifontdata). |
| [getReplaceFontCondition()](#getReplaceFontCondition--) | 應用於置換的規則（唯讀） [FontSubstCondition](../../com.aspose.slides/fontsubstcondition). |
### getSourceFont() {#getSourceFont--}
```
public abstract IFontData getSourceFont()
```

要替換的字體（唯讀） [IFontData](../../com.aspose.slides/ifontdata).

**返回值:** 
[IFontData](../../com.aspose.slides/ifontdata)
### getDestFont() {#getDestFont--}
```
public abstract IFontData getDestFont()
```

用於置換的字體（唯讀） [IFontData](../../com.aspose.slides/ifontdata).

**返回值:** 
[IFontData](../../com.aspose.slides/ifontdata)
### getReplaceFontCondition() {#getReplaceFontCondition--}
```
public abstract int getReplaceFontCondition()
```

應用於置換的規則（唯讀） [FontSubstCondition](../../com.aspose.slides/fontsubstcondition).

**返回值:** 
int