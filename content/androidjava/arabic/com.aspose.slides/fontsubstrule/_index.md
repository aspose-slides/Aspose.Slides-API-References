---
title: FontSubstRule
second_title: Aspose.Slides لنظام Android عبر مرجع API لجاوة
description: يمثل معلومات استبدال الخط
type: docs
url: /ar/com.aspose.slides/fontsubstrule/
---
**الوراثة:**
java.lang.Object

**جميع الواجهات التي تم تنفيذها:**
[com.aspose.slides.IFontSubstRule](../../com.aspose.slides/ifontsubstrule)
```
public class FontSubstRule implements IFontSubstRule
```

يمثل معلومات استبدال الخط
## المُنشئات

| المُنشئ | الوصف |
| --- | --- |
| [FontSubstRule(IFontData sourceFont, IFontData destFont)](#FontSubstRule-com.aspose.slides.IFontData-com.aspose.slides.IFontData-) | إنشاء نسخة جديدة. |
| [FontSubstRule(IFontData sourceFont, IFontData destFont, int fontSubstRule)](#FontSubstRule-com.aspose.slides.IFontData-com.aspose.slides.IFontData-int-) | إنشاء نسخة جديدة. |
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getSourceFont()](#getSourceFont--) | الخط المستبدل. |
| [getDestFont()](#getDestFont--) | الخط المستخدم للاستبدال. |
| [getReplaceFontCondition()](#getReplaceFontCondition--) | القاعدة التي تُطبق للاستبدال. |
### FontSubstRule(IFontData sourceFont, IFontData destFont) {#FontSubstRule-com.aspose.slides.IFontData-com.aspose.slides.IFontData-}
```
public FontSubstRule(IFontData sourceFont, IFontData destFont)
```


إنشاء نسخة جديدة.

**الوسائط:**
| الوسيط | النوع | الوصف |
| --- | --- | --- |
| sourceFont | [IFontData](../../com.aspose.slides/ifontdata) | خط المصدر. |
| destFont | [IFontData](../../com.aspose.slides/ifontdata) | خط الوجهة. |

### FontSubstRule(IFontData sourceFont, IFontData destFont, int fontSubstRule) {#FontSubstRule-com.aspose.slides.IFontData-com.aspose.slides.IFontData-int-}
```
public FontSubstRule(IFontData sourceFont, IFontData destFont, int fontSubstRule)
```


إنشاء نسخة جديدة.

**الوسائط:**
| الوسيط | النوع | الوصف |
| --- | --- | --- |
| sourceFont | [IFontData](../../com.aspose.slides/ifontdata) | خط المصدر. |
| destFont | [IFontData](../../com.aspose.slides/ifontdata) | خط الوجهة. |
| fontSubstRule | int | قاعدة استبدال الخط. |

### getSourceFont() {#getSourceFont--}
```
public final IFontData getSourceFont()
```


الخط المستبدل. للقراءة فقط [IFontData](../../com.aspose.slides/ifontdata).

**القيمة المرجعة:**
[IFontData](../../com.aspose.slides/ifontdata)
### getDestFont() {#getDestFont--}
```
public final IFontData getDestFont()
```


الخط المستخدم للاستبدال. للقراءة فقط [IFontData](../../com.aspose.slides/ifontdata).

**القيمة المرجعة:**
[IFontData](../../com.aspose.slides/ifontdata)
### getReplaceFontCondition() {#getReplaceFontCondition--}
```
public final int getReplaceFontCondition()
```


القاعدة التي تُطبق للاستبدال. للقراءة فقط [FontSubstCondition](../../com.aspose.slides/fontsubstcondition).

**القيمة المرجعة:**
int