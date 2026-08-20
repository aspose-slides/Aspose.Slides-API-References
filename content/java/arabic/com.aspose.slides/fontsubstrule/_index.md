---
title: FontSubstRule
second_title: Aspose.Slides للغة Java مرجع API
description: يمثل معلومات استبدال الخط
type: docs
url: /ar/com.aspose.slides/fontsubstrule/
---
**الوراثة:**
java.lang.Object

**جميع الواجهات المنفذة:**
[com.aspose.slides.IFontSubstRule](../../com.aspose.slides/ifontsubstrule)
```
public class FontSubstRule implements IFontSubstRule
```

يمثل معلومات استبدال الخط
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [FontSubstRule(IFontData sourceFont, IFontData destFont)](#FontSubstRule-com.aspose.slides.IFontData-com.aspose.slides.IFontData-) | ينشئ مثالا جديدًا. |
| [FontSubstRule(IFontData sourceFont, IFontData destFont, int fontSubstRule)](#FontSubstRule-com.aspose.slides.IFontData-com.aspose.slides.IFontData-int-) | ينشئ مثالا جديدًا. |
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getSourceFont()](#getSourceFont--) | الخط المراد استبداله. |
| [getDestFont()](#getDestFont--) | الخط المستخدم للاستبدال. |
| [getReplaceFontCondition()](#getReplaceFontCondition--) | القاعدة التي تُطبق للاستبدال. |
### FontSubstRule(IFontData sourceFont, IFontData destFont) {#FontSubstRule-com.aspose.slides.IFontData-com.aspose.slides.IFontData-}
```
public FontSubstRule(IFontData sourceFont, IFontData destFont)
```

ينشئ مثالا جديدًا.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| sourceFont | [IFontData](../../com.aspose.slides/ifontdata) | خط المصدر. |
| destFont | [IFontData](../../com.aspose.slides/ifontdata) | خط الوجهة. |

### FontSubstRule(IFontData sourceFont, IFontData destFont, int fontSubstRule) {#FontSubstRule-com.aspose.slides.IFontData-com.aspose.slides.IFontData-int-}
```
public FontSubstRule(IFontData sourceFont, IFontData destFont, int fontSubstRule)
```

ينشئ مثالا جديدًا.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| sourceFont | [IFontData](../../com.aspose.slides/ifontdata) | خط المصدر. |
| destFont | [IFontData](../../com.aspose.slides/ifontdata) | خط الوجهة. |
| fontSubstRule | int | قاعدة استبدال الخط. |

### getSourceFont() {#getSourceFont--}
```
public final IFontData getSourceFont()
```

الخط المراد استبداله. قراءة فقط [IFontData](../../com.aspose.slides/ifontdata).

**الإرجاع:**
[IFontData](../../com.aspose.slides/ifontdata)
### getDestFont() {#getDestFont--}
```
public final IFontData getDestFont()
```

الخط المستخدم للاستبدال. قراءة فقط [IFontData](../../com.aspose.slides/ifontdata).

**الإرجاع:**
[IFontData](../../com.aspose.slides/ifontdata)
### getReplaceFontCondition() {#getReplaceFontCondition--}
```
public final int getReplaceFontCondition()
```

القاعدة التي تُطبق للاستبدال. قراءة فقط [FontSubstCondition](../../com.aspose.slides/fontsubstcondition).

**الإرجاع:**
int