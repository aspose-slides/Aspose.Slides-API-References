---
title: IFontSubstRule
second_title: Aspose.Slides for Android عبر مرجع API جافا
description: يمثل معلومات استبدال الخط
type: docs
url: /ar/com.aspose.slides/ifontsubstrule/
---```
public interface IFontSubstRule
```

يمثل معلومات استبدال الخط
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getSourceFont()](#getSourceFont--) | الخط لاستبداله للقراءة فقط [IFontData](../../com.aspose.slides/ifontdata). |
| [getDestFont()](#getDestFont--) | الخط لاستخدامه في الاستبدال للقراءة فقط [IFontData](../../com.aspose.slides/ifontdata). |
| [getReplaceFontCondition()](#getReplaceFontCondition--) | القاعدة التي سيتم تطبيقها للاستبدال للقراءة فقط [FontSubstCondition](../../com.aspose.slides/fontsubstcondition). |
### getSourceFont() {#getSourceFont--}
```
public abstract IFontData getSourceFont()
```


الخط المراد استبداله للقراءة فقط [IFontData](../../com.aspose.slides/ifontdata).

**الإرجاع:**
[IFontData](../../com.aspose.slides/ifontdata)
### getDestFont() {#getDestFont--}
```
public abstract IFontData getDestFont()
```


الخط لاستخدامه في الاستبدال للقراءة فقط [IFontData](../../com.aspose.slides/ifontdata).

**الإرجاع:**
[IFontData](../../com.aspose.slides/ifontdata)
### getReplaceFontCondition() {#getReplaceFontCondition--}
```
public abstract int getReplaceFontCondition()
```


القاعدة التي سيتم تطبيقها للاستبدال للقراءة فقط [FontSubstCondition](../../com.aspose.slides/fontsubstcondition).

**الإرجاع:**
int