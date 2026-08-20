---
title: ITextFrameFormatEffectiveData
second_title: Aspose.Slides for Java API Reference
description: Immutable object which contains effective text frame formatting properties.
type: docs
url: /ar/com.aspose.slides/itextframeformateffectivedata/
---```
public interface ITextFrameFormatEffectiveData
```

كائن غير قابل للتغيير يحتوي على خصائص تنسيق إطار النص الفعّالة.

--------------------

يُستخدم هذا الواجهة مع واجهة [ITextFrameFormat](../../com.aspose.slides/itextframeformat) لإرجاع قيم التنسيق الفعّالة مع تطبيق الوراثة.
## الأساليب

| الطريقة | الوصف |
| --- | --- |
| [getTextStyle()](#getTextStyle--) | يعيد نمط النص الفعّال. |
| [getMarginLeft()](#getMarginLeft--) | يعيد الهامش الأيسر (نقاط) في TextFrame. |
| [getMarginRight()](#getMarginRight--) | يعيد الهامش الأيمن (نقاط) في TextFrame. |
| [getMarginTop()](#getMarginTop--) | يعيد الهامش العلوي (نقاط) في TextFrame. |
| [getMarginBottom()](#getMarginBottom--) | يعيد الهامش السفلي (نقاط) في TextFrame. |
| [getWrapText()](#getWrapText--) | يعيد ما إذا كان النص مَلفًّا على هوامش TextFrame. |
| [getAnchoringType()](#getAnchoringType--) | يعيد نص التثبيت العمودي في TextFrame. |
| [getCenterText()](#getCenterText--) | يعيد ما إذا كان ينبغي توسيط النص داخل الصندوق أفقيًا. |
| [getTextVerticalType()](#getTextVerticalType--) | يعيد توجيه النص. |
| [getAutofitType()](#getAutofitType--) | يعيد وضعية ملاءمة النص التلقائية. |
| [getColumnCount()](#getColumnCount--) | يحدد عدد أعمدة النص في المستطيل المحدد. |
| [getColumnSpacing()](#getColumnSpacing--) | يحدد المسافة بين أعمدة النص في منطقة النص (نقاط). |
### getTextStyle() {#getTextStyle--}
```
public abstract ITextStyleEffectiveData getTextStyle()
```

يعيد نمط النص الفعّال. قراءة فقط [ITextStyleEffectiveData](../../com.aspose.slides/itextstyleeffectivedata).

**الإرجاع:**  
[ITextStyleEffectiveData](../../com.aspose.slides/itextstyleeffectivedata)
### getMarginLeft() {#getMarginLeft--}
```
public abstract double getMarginLeft()
```

يعيد الهامش الأيسر (نقاط) في TextFrame. قراءة فقط double.

**الإرجاع:**  
double
### getMarginRight() {#getMarginRight--}
```
public abstract double getMarginRight()
```

يعيد الهامش الأيمن (نقاط) في TextFrame. قراءة فقط double.

**الإرجاع:**  
double
### getMarginTop() {#getMarginTop--}
```
public abstract double getMarginTop()
```

يعيد الهامش العلوي (نقاط) في TextFrame. قراءة فقط double.

**الإرجاع:**  
double
### getMarginBottom() {#getMarginBottom--}
```
public abstract double getMarginBottom()
```

يعيد الهامش السفلي (نقاط) في TextFrame. قراءة فقط double.

**الإرجاع:**  
double
### getWrapText() {#getWrapText--}
```
public abstract boolean getWrapText()
```

يعيد ما إذا كان النص مَلفًّا على هوامش TextFrame. قراءة فقط boolean.

**الإرجاع:**  
boolean
### getAnchoringType() {#getAnchoringType--}
```
public abstract byte getAnchoringType()
```

يعيد نص التثبيت العمودي في TextFrame. قراءة فقط [TextAnchorType](../../com.aspose.slides/textanchortype).

**الإرجاع:**  
byte
### getCenterText() {#getCenterText--}
```
public abstract boolean getCenterText()
```

يعيد ما إذا كان ينبغي توسيط النص داخل الصندوق أفقيًا. قراءة فقط boolean.

**الإرجاع:**  
boolean
### getTextVerticalType() {#getTextVerticalType--}
```
public abstract byte getTextVerticalType()
```

يعيد توجيه النص. قراءة فقط [TextVerticalType](../../com.aspose.slides/textverticaltype).

**الإرجاع:**  
byte
### getAutofitType() {#getAutofitType--}
```
public abstract byte getAutofitType()
```

يعيد وضعية ملاءمة النص التلقائية. قراءة فقط [TextAutofitType](../../com.aspose.slides/textautofittype).

**الإرجاع:**  
byte
### getColumnCount() {#getColumnCount--}
```
public abstract int getColumnCount()
```

يحدد عدد أعمدة النص في المستطيل المحدد. قراءة فقط int.

**الإرجاع:**  
int
### getColumnSpacing() {#getColumnSpacing--}
```
public abstract float getColumnSpacing()
```

يحدد المسافة بين أعمدة النص في منطقة النص (نقاط). قراءة فقط float.

**الإرجاع:**  
float