---
title: IAutoShape
second_title: Aspose.Slides لنظام Android عبر مرجع API جافا
description: يمثل AutoShape.
type: docs
url: /ar/com.aspose.slides/iautoshape/
---
**جميع الواجهات المنفذة:**
[com.aspose.slides.IGeometryShape](../../com.aspose.slides/igeometryshape)
```
public interface IAutoShape extends IGeometryShape
```

يمثل AutoShape.
## الطرق

| Method | Description |
| --- | --- |
| [getAutoShapeLock()](#getAutoShapeLock--) | يعيد أقفال AutoShape. |
| [getTextFrame()](#getTextFrame--) | يعيد كائن TextFrame الخاص بـ AutoShape. |
| [getUseBackgroundFill()](#getUseBackgroundFill--) | يحدد ما إذا كان يجب ملء هذا autoshape بملء خلفية الشريحة بدلاً من ما تم تحديده بواسطة النمط أو تنسيق الملء. |
| [setUseBackgroundFill(boolean value)](#setUseBackgroundFill-boolean-) | يحدد ما إذا كان يجب ملء هذا autoshape بملء خلفية الشريحة بدلاً من ما تم تحديده بواسطة النمط أو تنسيق الملء. |
| [addTextFrame(String text)](#addTextFrame-java.lang.String-) | يضيف TextFrame جديد إلى الشكل. |
| [isTextBox()](#isTextBox--) | يحدد ما إذا كان الشكل هو مربع نص. |
### getAutoShapeLock() {#getAutoShapeLock--}
```
public abstract IAutoShapeLock getAutoShapeLock()
```


يعيد أقفال AutoShape. للقراءة فقط [IAutoShapeLock](../../com.aspose.slides/iautoshapelock).

**الإرجاع:**
[IAutoShapeLock](../../com.aspose.slides/iautoshapelock)
### getTextFrame() {#getTextFrame--}
```
public abstract ITextFrame getTextFrame()
```


يعيد كائن TextFrame الخاص بـ AutoShape. للقراءة فقط [ITextFrame](../../com.aspose.slides/itextframe).

**الإرجاع:**
[ITextFrame](../../com.aspose.slides/itextframe)
### getUseBackgroundFill() {#getUseBackgroundFill--}
```
public abstract boolean getUseBackgroundFill()
```


يحدد ما إذا كان يجب ملء هذا autoshape بملء خلفية الشريحة بدلاً من ما تم تحديده بواسطة النمط أو تنسيق الملء. قراءة/كتابة boolean.

**الإرجاع:**
boolean
### setUseBackgroundFill(boolean value) {#setUseBackgroundFill-boolean-}
```
public abstract void setUseBackgroundFill(boolean value)
```


يحدد ما إذا كان يجب ملء هذا autoshape بملء خلفية الشريحة بدلاً من ما تم تحديده بواسطة النمط أو تنسيق الملء. قراءة/كتابة boolean.

**المعلمات:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### addTextFrame(String text) {#addTextFrame-java.lang.String-}
```
public abstract ITextFrame addTextFrame(String text)
```


يضيف TextFrame جديد إلى الشكل. إذا كان الشكل يحتوي بالفعل على TextFrame فسيتم تعديل نصه فقط.

**المعلمات:**
| Parameter | Type | Description |
| --- | --- | --- |
| text | java.lang.String | النص الافتراضي لـ TextFrame الجديد. |

**الإرجاع:**
[ITextFrame](../../com.aspose.slides/itextframe) - كائن [ITextFrame](../../com.aspose.slides/itextframe) جديد.
### isTextBox() {#isTextBox--}
```
public abstract boolean isTextBox()
```


يحدد ما إذا كان الشكل هو مربع نص.

--------------------

إذا لم يتم تحديد الشكل كمربع نص فهذا لا يعني أنه لا يمكن أن يحتوي على نص. مربع النص هو مجرد شكل متخصص له خصائص محددة.

**الإرجاع:**
boolean