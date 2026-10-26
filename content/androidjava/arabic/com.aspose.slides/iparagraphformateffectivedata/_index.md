---
title: IParagraphFormatEffectiveData
second_title: Aspose.Slides for Android عبر مرجع Java API
description: كائن غير قابل للتغيير يحتوي على خصائص تنسيق الفقرة الفعّالة.
type: docs
url: /ar/com.aspose.slides/iparagraphformateffectivedata/
---```
public interface IParagraphFormatEffectiveData
```

كائن غير قابل للتغيير يحتوي على خصائص تنسيق الفقرة الفعّالة.

--------------------

يتم استخدام هذه الواجهة مع الواجهة [IParagraphFormat](../../com.aspose.slides/iparagraphformat) لإرجاع قيم التنسيق الفعّالة مع تطبيق الوراثة.
## الأساليب

| الطريقة | الوصف |
| --- | --- |
| [getBullet()](#getBullet--) | يرجع تنسيق نقطي للفقرة. |
| [getDepth()](#getDepth--) | يرجع عمق الفقرة. |
| [getAlignment()](#getAlignment--) | يرجع محاذاة النص في الفقرة. |
| [getSpaceWithin()](#getSpaceWithin--) | يرجع مقدار المسافة بين الخطوط الأساسية في الفقرة. |
| [getSpaceBefore()](#getSpaceBefore--) | يرجع مقدار المسافة قبل السطر الأول في الفقرة. |
| [getSpaceAfter()](#getSpaceAfter--) | يرجع مقدار المسافة بعد السطر الأخير في الفقرة. |
| [getEastAsianLineBreak()](#getEastAsianLineBreak--) | يحدد ما إذا كان يتم استخدام فاصل السطر الشرقي الآسيوي في الفقرة. |
| [getRightToLeft()](#getRightToLeft--) | يحدد ما إذا كان يتم استخدام الكتابة من اليمين إلى اليسار في الفقرة. |
| [getLatinLineBreak()](#getLatinLineBreak--) | يحدد ما إذا كان يتم استخدام فاصل السطر اللاتيني في الفقرة. |
| [getHangingPunctuation()](#getHangingPunctuation--) | يحدد ما إذا كان يتم استخدام علامات الترقيم المتدلية في الفقرة. |
| [getMarginLeft()](#getMarginLeft--) | يرجع الهامش الأيسر في الفقرة. |
| [getMarginRight()](#getMarginRight--) | يرجع الهامش الأيمن في الفقرة. |
| [getIndent()](#getIndent--) | يرجع إزاحة السطر الأول/الإزاحة المتدلية للفقرة. |
| [getDefaultTabSize()](#getDefaultTabSize--) | يرجع حجم التبويب الافتراضي. |
| [getTabs()](#getTabs--) | يرجع تبويبات الفقرة. |
| [getFontAlignment()](#getFontAlignment--) | يرجع محاذاة الخط في الفقرة. |
| [getDefaultPortionFormat()](#getDefaultPortionFormat--) | يرجع تنسيق الجزء الافتراضي للفقرة. |
### getBullet() {#getBullet--}
```
public abstract IBulletFormatEffectiveData getBullet()
```

يرجع تنسيق نقطي للفقرة. للقراءة فقط [IBulletFormatEffectiveData](../../com.aspose.slides/ibulletformateffectivedata).

**الإرجاع:**
[IBulletFormatEffectiveData](../../com.aspose.slides/ibulletformateffectivedata)
### getDepth() {#getDepth--}
```
public abstract short getDepth()
```

يرجع عمق الفقرة. للقراءة فقط short.

**الإرجاع:**
short
### getAlignment() {#getAlignment--}
```
public abstract int getAlignment()
```

يرجع محاذاة النص في الفقرة. للقراءة فقط [TextAlignment](../../com.aspose.slides/textalignment).

**الإرجاع:**
int
### getSpaceWithin() {#getSpaceWithin--}
```
public abstract float getSpaceWithin()
```

يرجع مقدار المسافة بين الخطوط الأساسية في الفقرة. للقراءة فقط float.

**الإرجاع:**
float
### getSpaceBefore() {#getSpaceBefore--}
```
public abstract float getSpaceBefore()
```

يرجع مقدار المسافة قبل السطر الأول في الفقرة. للقراءة فقط float.

**الإرجاع:**
float
### getSpaceAfter() {#getSpaceAfter--}
```
public abstract float getSpaceAfter()
```

يرجع مقدار المسافة بعد السطر الأخير في الفقرة. للقراءة فقط float.

**الإرجاع:**
float
### getEastAsianLineBreak() {#getEastAsianLineBreak--}
```
public abstract boolean getEastAsianLineBreak()
```

يحدد ما إذا كان يتم استخدام فاصل السطر الشرقي الآسيوي في الفقرة. للقراءة فقط boolean.

**الإرجاع:**
boolean
### getRightToLeft() {#getRightToLeft--}
```
public abstract boolean getRightToLeft()
```

يحدد ما إذا كان يتم استخدام الكتابة من اليمين إلى اليسار في الفقرة. للقراءة فقط boolean.

**الإرجاع:**
boolean
### getLatinLineBreak() {#getLatinLineBreak--}
```
public abstract boolean getLatinLineBreak()
```

يحدد ما إذا كان يتم استخدام فاصل السطر اللاتيني في الفقرة. للقراءة فقط boolean.

**الإرجاع:**
boolean
### getHangingPunctuation() {#getHangingPunctuation--}
```
public abstract boolean getHangingPunctuation()
```

يحدد ما إذا كان يتم استخدام علامات الترقيم المتدلية في الفقرة. للقراءة فقط boolean.

**الإرجاع:**
boolean
### getMarginLeft() {#getMarginLeft--}
```
public abstract float getMarginLeft()
```

يرجع الهامش الأيسر في الفقرة. للقراءة فقط float.

**الإرجاع:**
float
### getMarginRight() {#getMarginRight--}
```
public abstract float getMarginRight()
```

يرجع الهامش الأيمن في الفقرة. للقراءة فقط float.

**الإرجاع:**
float
### getIndent() {#getIndent--}
```
public abstract float getIndent()
```

يرجع إزاحة السطر الأول/الإزاحة المتدلية للفقرة. يمكن تعريف الإزاحة المتدلية بقيم سالبة. للقراءة فقط float.

**الإرجاع:**
float
### getDefaultTabSize() {#getDefaultTabSize--}
```
public abstract float getDefaultTabSize()
```

يرجع حجم التبويب الافتراضي. للقراءة فقط float.

**الإرجاع:**
float
### getTabs() {#getTabs--}
```
public abstract ITabEffectiveData[] getTabs()
```

يرجع تبويبات الفقرة. للقراءة فقط ITabEffectiveData[].

**الإرجاع:**
com.aspose.slides.ITabEffectiveData[]
### getFontAlignment() {#getFontAlignment--}
```
public abstract int getFontAlignment()
```

يرجع محاذاة الخط في الفقرة. للقراءة فقط [FontAlignment](../../com.aspose.slides/fontalignment).

**الإرجاع:**
int
### getDefaultPortionFormat() {#getDefaultPortionFormat--}
```
public abstract IPortionFormatEffectiveData getDefaultPortionFormat()
```

يرجع تنسيق الجزء الافتراضي للفقرة. للقراءة فقط [IPortionFormatEffectiveData](../../com.aspose.slides/iportionformateffectivedata).

**الإرجاع:**
[IPortionFormatEffectiveData](../../com.aspose.slides/iportionformateffectivedata)