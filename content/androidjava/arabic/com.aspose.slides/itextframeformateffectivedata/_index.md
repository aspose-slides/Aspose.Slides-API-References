---
title: ITextFrameFormatEffectiveData
second_title: Aspose.Slides for Android via Java API Reference
description: Immutable object which contains effective text frame formatting properties.
type: docs
url: /ar/com.aspose.slides/itextframeformateffectivedata/
---```
public interface ITextFrameFormatEffectiveData
```

كائن ثابت يحتوي على خصائص تنسيق إطار النص الفعّال.

--------------------

يُستخدم هذا الواجهة مع واجهة [ITextFrameFormat](../../com.aspose.slides/itextframeformat) لإرجاع قيم التنسيق الفعّالة مع تطبيق الوراثة.

## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getTextStyle()](#getTextStyle--) | إرجاع نمط النص الفعّال. |
| [getMarginLeft()](#getMarginLeft--) | إرجاع الهامش الأيسر (نقطة) في TextFrame. |
| [getMarginRight()](#getMarginRight--) | إرجاع الهامش الأيمن (نقطة) في TextFrame. |
| [getMarginTop()](#getMarginTop--) | إرجاع الهامش العلوي (نقطة) في TextFrame. |
| [getMarginBottom()](#getMarginBottom--) | إرجاع الهامش السفلي (نقطة) في TextFrame. |
| [getWrapText()](#getWrapText--) | إرجاع ما إذا كان النص مُلتفًا عند هوامش TextFrame. |
| [getAnchoringType()](#getAnchoringType--) | إرجاع النص المربوط عموديًا في TextFrame. |
| [getCenterText()](#getCenterText--) | إرجاع ما إذا كان ينبغي تمركز النص أفقيًا داخل الصندوق. |
| [getTextVerticalType()](#getTextVerticalType--) | إرجاع اتجاه النص. |
| [getAutofitType()](#getAutofitType--) | إرجاع وضع تعديل حجم النص تلقائيًا. |
| [getColumnCount()](#getColumnCount--) | يحدد عدد أعمدة النص في المستطيل المحيط. |
| [getColumnSpacing()](#getColumnSpacing--) | يحدد المسافة بين أعمدة النص في مساحة النص (نقطة). |

### getTextStyle() {#getTextStyle--}
```
public abstract ITextStyleEffectiveData getTextStyle()
```

إرجاع نمط النص الفعّال. قراءة فقط [ITextStyleEffectiveData](../../com.aspose.slides/itextstyleeffectivedata).

**الإرجاع:**
[ITextStyleEffectiveData](../../com.aspose.slides/itextstyleeffectivedata)

### getMarginLeft() {#getMarginLeft--}
```
public abstract double getMarginLeft()
```

إرجاع الهامش الأيسر (نقطة) في TextFrame. قراءة فقط double.

**الإرجاع:**
double

### getMarginRight() {#getMarginRight--}
```
public abstract double getMarginRight()
```

إرجاع الهامش الأيمن (نقطة) في TextFrame. قراءة فقط double.

**الإرجاع:**
double

### getMarginTop() {#getMarginTop--}
```
public abstract double getMarginTop()
```

إرجاع الهامش العلوي (نقطة) في TextFrame. قراءة فقط double.

**الإرجاع:**
double

### getMarginBottom() {#getMarginBottom--}
```
public abstract double getMarginBottom()
```

إرجاع الهامش السفلي (نقطة) في TextFrame. قراءة فقط double.

**الإرجاع:**
double

### getWrapText() {#getWrapText--}
```
public abstract boolean getWrapText()
```

إرجاع ما إذا كان النص مُلتفًا عند هوامش TextFrame. قراءة فقط boolean.

**الإرجاع:**
boolean

### getAnchoringType() {#getAnchoringType--}
```
public abstract byte getAnchoringType()
```

إرجاع النص المربوط عموديًا في TextFrame. قراءة فقط [TextAnchorType](../../com.aspose.slides/textanchortype).

**الإرجاع:**
byte

### getCenterText() {#getCenterText--}
```
public abstract boolean getCenterText()
```

إرجاع ما إذا كان ينبغي تمركز النص أفقيًا داخل الصندوق. قراءة فقط boolean.

**الإرجاع:**
boolean

### getTextVerticalType() {#getTextVerticalType--}
```
public abstract byte getTextVerticalType()
```

إرجاع اتجاه النص. قراءة فقط [TextVerticalType](../../com.aspose.slides/textverticaltype).

**الإرجاع:**
byte

### getAutofitType() {#getAutofitType--}
```
public abstract byte getAutofitType()
```

إرجاع وضع تعديل حجم النص تلقائيًا. قراءة فقط [TextAutofitType](../../com.aspose.slides/textautofittype).

**الإرجاع:**
byte

### getColumnCount() {#getColumnCount--}
```
public abstract int getColumnCount()
```

يحدد عدد أعمدة النص في المستطيل المحيط. قراءة فقط int.

**الإرجاع:**
int

### getColumnSpacing() {#getColumnSpacing--}
```
public abstract float getColumnSpacing()
```

يحدد المسافة بين أعمدة النص في مساحة النص (نقطة). قراءة فقط float.

**الإرجاع:**
float