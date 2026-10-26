---
title: IXpsOptions
second_title: مرجع API لـ Aspose.Slides للـ Java
description: يوفر خيارات تتحكم في كيفية حفظ عرض تقديمي بتنسيق XPS.
type: docs
url: /ar/com.aspose.slides/ixpsoptions/
---
**جميع الواجهات المُطبَّقة:**
[com.aspose.slides.ISaveOptions](../../com.aspose.slides/isaveoptions)
```
public interface IXpsOptions extends ISaveOptions
```

يوفر خيارات تتحكم في كيفية حفظ العرض التقديمي بتنسيق XPS.
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getSaveMetafilesAsPng()](#getSaveMetafilesAsPng--) | True لتحويل جميع ملفات الميتا المستخدمة في العرض إلى صور PNG. |
| [setSaveMetafilesAsPng(boolean value)](#setSaveMetafilesAsPng-boolean-) | True لتحويل جميع ملفات الميتا المستخدمة في العرض إلى صور PNG. |
| [getDrawSlidesFrame()](#getDrawSlidesFrame--) | True لرسم إطار أسود حول كل شريحة. |
| [setDrawSlidesFrame(boolean value)](#setDrawSlidesFrame-boolean-) | True لرسم إطار أسود حول كل شريحة. |
| [getShowHiddenSlides()](#getShowHiddenSlides--) | يحدد ما إذا كان المستند المُنشأ يجب أن يتضمن الشرائح المخفية أم لا. |
| [setShowHiddenSlides(boolean value)](#setShowHiddenSlides-boolean-) | يحدد ما إذا كان المستند المُنشأ يجب أن يتضمن الشرائح المخفية أم لا. |
### getSaveMetafilesAsPng() {#getSaveMetafilesAsPng--}
```
public abstract boolean getSaveMetafilesAsPng()
```

True لتحويل جميع ملفات الميتا المستخدمة في العرض إلى صور PNG. قابل للقراءة/الكتابة من نوع boolean.

--------------------

الافتراضي هو **true**.

**القيمة المرجعة:**
boolean
### setSaveMetafilesAsPng(boolean value) {#setSaveMetafilesAsPng-boolean-}
```
public abstract void setSaveMetafilesAsPng(boolean value)
```

True لتحويل جميع ملفات الميتا المستخدمة في العرض إلى صور PNG. قابل للقراءة/الكتابة من نوع boolean.

--------------------

الافتراضي هو **true**.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |
### getDrawSlidesFrame() {#getDrawSlidesFrame--}
```
public abstract boolean getDrawSlidesFrame()
```

True لرسم إطار أسود حول كل شريحة. قابل للقراءة/الكتابة من نوع boolean.

--------------------

الافتراضي هو **false**.

**القيمة المرجعة:**
boolean
### setDrawSlidesFrame(boolean value) {#setDrawSlidesFrame-boolean-}
```
public abstract void setDrawSlidesFrame(boolean value)
```

True لرسم إطار أسود حول كل شريحة. قابل للقراءة/الكتابة من نوع boolean.

--------------------

الافتراضي هو **false**.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |
### getShowHiddenSlides() {#getShowHiddenSlides--}
```
public abstract boolean getShowHiddenSlides()
```

يحدد ما إذا كان المستند المُنشأ يجب أن يتضمن الشرائح المخفية أم لا. الافتراضي هو false.

**القيمة المرجعة:**
boolean
### setShowHiddenSlides(boolean value) {#setShowHiddenSlides-boolean-}
```
public abstract void setShowHiddenSlides(boolean value)
```

يحدد ما إذا كان المستند المُنشأ يجب أن يتضمن الشرائح المخفية أم لا. الافتراضي هو false.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |