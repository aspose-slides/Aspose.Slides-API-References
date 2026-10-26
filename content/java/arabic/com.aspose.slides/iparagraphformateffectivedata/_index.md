---
title: IParagraphFormatEffectiveData
second_title: Aspose.Slides for Java API Reference
description: كائن غير قابل للتغيير يحتوي على خصائص تنسيق الفقرة الفعّالة.
type: docs
url: /ar/com.aspose.slides/iparagraphformateffectivedata/
---```
public interface IParagraphFormatEffectiveData
```

كائن غير قابل للتغيير يحتوي على خصائص تنسيق الفقرة الفعّالة.

--------------------

تُستخدم هذه الواجهة مع واجهة [IParagraphFormat](../../com.aspose.slides/iparagraphformat) لإرجاع قيم التنسيق الفعّالة مع تطبيق الوراثة.

## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getBullet()](#getBullet--) | يعيد تنسيق نقطي للفقرة. |
| [getDepth()](#getDepth--) | يعيد عمق الفقرة. |
| [getAlignment()](#getAlignment--) | يعيد محاذاة النص في الفقرة. |
| [getSpaceWithin()](#getSpaceWithin--) | يعيد مقدار المسافة بين الأسطر الأساس في الفقرة. |
| [getSpaceBefore()](#getSpaceBefore--) | يعيد مقدار المسافة قبل السطر الأول في الفقرة. |
| [getSpaceAfter()](#getSpaceAfter--) | يعيد مقدار المسافة بعد السطر الأخير في الفقرة. |
| [getEastAsianLineBreak()](#getEastAsianLineBreak--) | يحدد ما إذا كان كسر السطر الآسيوي الشرقي يُستخدم في الفقرة. |
| [getRightToLeft()](#getRightToLeft--) | يحدد ما إذا كان الكتابة من اليمين إلى اليسار يُستخدم في الفقرة. |
| [getLatinLineBreak()](#getLatinLineBreak--) | يحدد ما إذا كان كسر السطر اللاتيني يُستخدم في الفقرة. |
| [getHangingPunctuation()](#getHangingPunctuation--) | يحدد ما إذا كان علامات الترقيم المتدلية تُستخدم في الفقرة. |
| [getMarginLeft()](#getMarginLeft--) | يعيد الهامش الأيسر في الفقرة. |
| [getMarginRight()](#getMarginRight--) | يعيد الهامش الأيمن في الفقرة. |
| [getIndent()](#getIndent--) | يعيد إزاحة السطر الأول/الإزاحة المتدلية للفقرة. |
| [getDefaultTabSize()](#getDefaultTabSize--) | يعيد حجم التبويب الافتراضي. |
| [getTabs()](#getTabs--) | يعيد تبويبات الفقرة. |
| [getFontAlignment()](#getFontAlignment--) | يعيد محاذاة الخط في الفقرة. |
| [getDefaultPortionFormat()](#getDefaultPortionFormat--) | يعيد تنسيق الجزء الافتراضي للفقرة. |
### getBullet() {#getBullet--}
```
public abstract IBulletFormatEffectiveData getBullet()
```


يعيد تنسيق نقطي للفقرة. للقراءة فقط [IBulletFormatEffectiveData](../../com.aspose.slides/ibulletformateffectivedata).

**الإرجاع:**
[IBulletFormatEffectiveData](../../com.aspose.slides/ibulletformateffectivedata)
### getDepth() {#getDepth--}
```
public abstract short getDepth()
```


يعيد عمق الفقرة. للقراءة فقط short.

**الإرجاع:**
short
### getAlignment() {#getAlignment--}
```
public abstract int getAlignment()
```


يعيد محاذاة النص في الفقرة. للقراءة فقط [TextAlignment](../../com.aspose.slides/textalignment).

**الإرجاع:**
int
### getSpaceWithin() {#getSpaceWithin--}
```
public abstract float getSpaceWithin()
```


يعيد مقدار المسافة بين الأسطر الأساس في الفقرة. للقراءة فقط float.

**الإرجاع:**
float
### getSpaceBefore() {#getSpaceBefore--}
```
public abstract float getSpaceBefore()
```


يعيد مقدار المسافة قبل السطر الأول في الفقرة. للقراءة فقط float.

**الإرجاع:**
float
### getSpaceAfter() {#getSpaceAfter--}
```
public abstract float getSpaceAfter()
```


يعيد مقدار المسافة بعد السطر الأخير في الفقرة. للقراءة فقط float.

**الإرجاع:**
float
### getEastAsianLineBreak() {#getEastAsianLineBreak--}
```
public abstract boolean getEastAsianLineBreak()
```


يحدد ما إذا كان كسر السطر الآسيوي الشرقي يُستخدم في الفقرة. للقراءة فقط boolean.

**الإرجاع:**
boolean
### getRightToLeft() {#getRightToLeft--}
```
public abstract boolean getRightToLeft()
```


يحدد ما إذا كان الكتابة من اليمين إلى اليسار يُستخدم في الفقرة. للقراءة فقط boolean.

**الإرجاع:**
boolean
### getLatinLineBreak() {#getLatinLineBreak--}
```
public abstract boolean getLatinLineBreak()
```


يحدد ما إذا كان كسر السطر اللاتيني يُستخدم في الفقرة. للقراءة فقط boolean.

**الإرجاع:**
boolean
### getHangingPunctuation() {#getHangingPunctuation--}
```
public abstract boolean getHangingPunctuation()
```


يحدد ما إذا كان علامات الترقيم المتدلية تُستخدم في الفقرة. للقراءة فقط boolean.

**الإرجاع:**
boolean
### getMarginLeft() {#getMarginLeft--}
```
public abstract float getMarginLeft()
```


يعيد الهامش الأيسر في الفقرة. للقراءة فقط float.

**الإرجاع:**
float
### getMarginRight() {#getMarginRight--}
```
public abstract float getMarginRight()
```


يعيد الهامش الأيمن في الفقرة. للقراءة فقط float.

**الإرجاع:**
float
### getIndent() {#getIndent--}
```
public abstract float getIndent()
```


يعيد إزاحة السطر الأول/الإزاحة المتدلية للفقرة. يمكن تعريف الإزاحة المتدلية بقيم سالبة. للقراءة فقط float.

**الإرجاع:**
float
### getDefaultTabSize() {#getDefaultTabSize--}
```
public abstract float getDefaultTabSize()
```


يعيد حجم التبويب الافتراضي. للقراءة فقط float.

**الإرجاع:**
float
### getTabs() {#getTabs--}
```
public abstract ITabEffectiveData[] getTabs()
```


يعيد تبويبات الفقرة. للقراءة فقط ITabEffectiveData[].

**الإرجاع:**
com.aspose.slides.ITabEffectiveData[]
### getFontAlignment() {#getFontAlignment--}
```
public abstract int getFontAlignment()
```


يعيد محاذاة الخط في الفقرة. للقراءة فقط [FontAlignment](../../com.aspose.slides/fontalignment).

**الإرجاع:**
int
### getDefaultPortionFormat() {#getDefaultPortionFormat--}
```
public abstract IPortionFormatEffectiveData getDefaultPortionFormat()
```


يعيد تنسيق الجزء الافتراضي للفقرة. للقراءة فقط [IPortionFormatEffectiveData](../../com.aspose.slides/iportionformateffectivedata).

**الإرجاع:**
[IPortionFormatEffectiveData](../../com.aspose.slides/iportionformateffectivedata)