---
title: IXpsOptions
second_title: Aspose.Slides لنظام Android عبر مرجع API لجافا
description: يوفر خيارات تتحكم في كيفية حفظ العرض التقديمي بتنسيق XPS.
type: docs
url: /ar/com.aspose.slides/ixpsoptions/
---
**جميع الواجهات المنفذة:**
[com.aspose.slides.ISaveOptions](../../com.aspose.slides/isaveoptions)
```
public interface IXpsOptions extends ISaveOptions
```

توفر خيارات تتحكم في كيفية حفظ العرض التقديمي بتنسيق XPS.
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getSaveMetafilesAsPng()](#getSaveMetafilesAsPng--) | صحيح لتحويل جميع ملفات الميتا المستخدمة في العرض التقديمي إلى صور PNG. |
| [setSaveMetafilesAsPng(boolean value)](#setSaveMetafilesAsPng-boolean-) | صحيح لتحويل جميع ملفات الميتا المستخدمة في العرض التقديمي إلى صور PNG. |
| [getDrawSlidesFrame()](#getDrawSlidesFrame--) | صحيح لرسم إطار أسود حول كل شريحة. |
| [setDrawSlidesFrame(boolean value)](#setDrawSlidesFrame-boolean-) | صحيح لرسم إطار أسود حول كل شريحة. |
| [getShowHiddenSlides()](#getShowHiddenSlides--) | يحدد ما إذا كان المستند المُولد يجب أن يتضمن الشرائح المخفية أم لا. |
| [setShowHiddenSlides(boolean value)](#setShowHiddenSlides-boolean-) | يحدد ما إذا كان المستند المُولد يجب أن يتضمن الشرائح المخفية أم لا. |
### getSaveMetafilesAsPng() {#getSaveMetafilesAsPng--}
```
public abstract boolean getSaveMetafilesAsPng()
```


صحيح لتحويل جميع ملفات الميتا المستخدمة في العرض التقديمي إلى صور PNG. قراءة/كتابة boolean.

--------------------

الافتراضي هو **true**.

**القيمة المرجعة:**
boolean
### setSaveMetafilesAsPng(boolean value) {#setSaveMetafilesAsPng-boolean-}
```
public abstract void setSaveMetafilesAsPng(boolean value)
```


صحيح لتحويل جميع ملفات الميتا المستخدمة في العرض التقديمي إلى صور PNG. قراءة/كتابة boolean.

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


صحيح لرسم إطار أسود حول كل شريحة. قراءة/كتابة boolean.

--------------------

الافتراضي هو **false**.

**القيمة المرجعة:**
boolean
### setDrawSlidesFrame(boolean value) {#setDrawSlidesFrame-boolean-}
```
public abstract void setDrawSlidesFrame(boolean value)
```


صحيح لرسم إطار أسود حول كل شريحة. قراءة/كتابة boolean.

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


يحدد ما إذا كان المستند المُولد يجب أن يتضمن الشرائح المخفية أم لا. الافتراضي هو false.

**القيمة المرجعة:**
boolean
### setShowHiddenSlides(boolean value) {#setShowHiddenSlides-boolean-}
```
public abstract void setShowHiddenSlides(boolean value)
```


يحدد ما إذا كان المستند المُولد يجب أن يتضمن الشرائح المخفية أم لا. الافتراضي هو false.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |