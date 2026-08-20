---
title: IAutoShape
second_title: مرجع API لـ Aspose.Slides للغة Java
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

| طريقة | الوصف |
| --- | --- |
| [getAutoShapeLock()](#getAutoShapeLock--) | إرجاع أقفال AutoShape. |
| [getTextFrame()](#getTextFrame--) | إرجاع كائن TextFrame للـ AutoShape. |
| [getUseBackgroundFill()](#getUseBackgroundFill--) | يحدد ما إذا كان هذا autoshape يجب أن يُملأ بملء خلفية الشريحة بدلاً من ما تم تحديده بواسطة style أو fill format. |
| [setUseBackgroundFill(boolean value)](#setUseBackgroundFill-boolean-) | يحدد ما إذا كان هذا autoshape يجب أن يُملأ بملء خلفية الشريحة بدلاً من ما تم تحديده بواسطة style أو fill format. |
| [addTextFrame(String text)](#addTextFrame-java.lang.String-) | يضيف TextFrame جديدًا إلى شكل. |
| [isTextBox()](#isTextBox--) | يحدد ما إذا كان الشكل صندوق نص. |
### getAutoShapeLock() {#getAutoShapeLock--}
```
public abstract IAutoShapeLock getAutoShapeLock()
```

إرجاع أقفال AutoShape. قراءة فقط [IAutoShapeLock](../../com.aspose.slides/iautoshapelock).

**الإرجاع:**
[IAutoShapeLock](../../com.aspose.slides/iautoshapelock)
### getTextFrame() {#getTextFrame--}
```
public abstract ITextFrame getTextFrame()
```

إرجاع كائن TextFrame للـ AutoShape. قراءة فقط [ITextFrame](../../com.aspose.slides/itextframe).

**الإرجاع:**
[ITextFrame](../../com.aspose.slides/itextframe)
### getUseBackgroundFill() {#getUseBackgroundFill--}
```
public abstract boolean getUseBackgroundFill()
```

يحدد ما إذا كان هذا autoshape يجب أن يُملأ بملء خلفية الشريحة بدلاً من ما تم تحديده بواسطة style أو fill format. قابل للقراءة والكتابة boolean.

**الإرجاع:**
boolean
### setUseBackgroundFill(boolean value) {#setUseBackgroundFill-boolean-}
```
public abstract void setUseBackgroundFill(boolean value)
```

يحدد ما إذا كان هذا autoshape يجب أن يُملأ بملء خلفية الشريحة بدلاً من ما تم تحديده بواسطة style أو fill format. قابل للقراءة والكتابة boolean.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |
### addTextFrame(String text) {#addTextFrame-java.lang.String-}
```
public abstract ITextFrame addTextFrame(String text)
```

يضيف TextFrame جديدًا إلى شكل. إذا كان الشكل يحتوي بالفعل على TextFrame فسيتم تغيير نصه ببساطة.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| text | java.lang.String | النص الافتراضي لـ TextFrame الجديد. |

**الإرجاع:**
[ITextFrame](../../com.aspose.slides/itextframe) - كائن [ITextFrame](../../com.aspose.slides/itextframe) جديد.
### isTextBox() {#isTextBox--}
```
public abstract boolean isTextBox()
```

يحدد ما إذا كان الشكل صندوق نص.

--------------------

إذا لم يتم تحديد الشكل على أنه صندوق نص فهذا لا يعني أنه لا يمكن إرفاق نص به. صندوق النص هو مجرد شكل متخصص بخصائص محددة.

**الإرجاع:**
boolean