---
title: IFontSubstRule
second_title: Aspose.Slides for Java API Reference
description: Represents font subtituition information
type: docs
url: /ar/com.aspose.slides/ifontsubstrule/
---```
public interface IFontSubstRule
```

يمثل معلومات استبدال الخط
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getSourceFont()](#getSourceFont--) | الخط المراد استبداله للقراءة فقط [IFontData](../../com.aspose.slides/ifontdata). |
| [getDestFont()](#getDestFont--) | الخط المستخدم للاستبدال للقراءة فقط [IFontData](../../com.aspose.slides/ifontdata). |
| [getReplaceFontCondition()](#getReplaceFontCondition--) | القاعدة التي تُطبق للاستبدال للقراءة فقط [FontSubstCondition](../../com.aspose.slides/fontsubstcondition). |
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

الخط المستخدم للاستبدال للقراءة فقط [IFontData](../../com.aspose.slides/ifontdata).

**الإرجاع:**
[IFontData](../../com.aspose.slides/ifontdata)
### getReplaceFontCondition() {#getReplaceFontCondition--}
```
public abstract int getReplaceFontCondition()
```

القاعدة التي تُطبق للاستبدال للقراءة فقط [FontSubstCondition](../../com.aspose.slides/fontsubstcondition).

**الإرجاع:**
int