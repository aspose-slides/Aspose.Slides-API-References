---
title: XpsOptions
second_title: Aspose.Slides لنظام Android عبر مرجع Java API
description: يوفر خيارات تتحكم في كيفية حفظ العرض التقديمي بصيغة XPS.
type: docs
url: /ar/com.aspose.slides/xpsoptions/
---
**الوراثة:**
java.lang.Object, [com.aspose.slides.SaveOptions](../../com.aspose.slides/saveoptions)

**جميع الواجهات المنفذة:**
[com.aspose.slides.IXpsOptions](../../com.aspose.slides/ixpsoptions)
```
public class XpsOptions extends SaveOptions implements IXpsOptions
```

يوفر خيارات تتحكم في كيفية حفظ العرض التقديمي بصيغة XPS.

--------------------

> ```
> The following example shows how to converting presentations to XPS using default settings.
>  
>  // إنشاء كائن Presentation يمثل ملف عرض تقديمي
>  Presentation pres = new Presentation("Convert_XPS.pptx");
>  try {
>      // حفظ العرض التقديمي إلى مستند XPS
>      pres.save("XPS_Output_Without_XPSOption_out.xps", SaveFormat.Xps);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to converting presentations to XPS using custom settings.
>  
>  // إنشاء كائن Presentation يمثل ملف عرض تقديمي
>  Presentation pres = new Presentation("Convert_XPS_Options.pptx");
>  try {
>      // إنشاء فئة TiffOptions
>      XpsOptions options = new XpsOptions();
>      // حفظ ملفات MetaFiles بصيغة PNG
>      options.setSaveMetafilesAsPng(true);
>      // حفظ العرض التقديمي إلى مستند XPS
>      pres.save("XPS_With_Options_out.xps", SaveFormat.Xps, options);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

## المنشئات

| منشئ | الوصف |
| --- | --- |
| [XpsOptions()](#XpsOptions--) | منشئ افتراضي. |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getShowHiddenSlides()](#getShowHiddenSlides--) | يحدد ما إذا كان المستند المُولَّد يجب أن يتضمن شرائح مخفية أم لا. |
| [setShowHiddenSlides(boolean value)](#setShowHiddenSlides-boolean-) | يحدد ما إذا كان المستند المُولَّد يجب أن يتضمن شرائح مخفية أم لا. |
| [getSaveMetafilesAsPng()](#getSaveMetafilesAsPng--) | True لتحويل جميع ملفات الميتا المستخدمة في العرض إلى صور PNG. |
| [setSaveMetafilesAsPng(boolean value)](#setSaveMetafilesAsPng-boolean-) | True لتحويل جميع ملفات الميتا المستخدمة في العرض إلى صور PNG. |
| [getDrawSlidesFrame()](#getDrawSlidesFrame--) | True لرسم إطار أسود حول كل شريحة. |
| [setDrawSlidesFrame(boolean value)](#setDrawSlidesFrame-boolean-) | True لرسم إطار أسود حول كل شريحة. |
### XpsOptions() {#XpsOptions--}
```
public XpsOptions()
```


منشئ افتراضي.

### getShowHiddenSlides() {#getShowHiddenSlides--}
```
public final boolean getShowHiddenSlides()
```


يحدد ما إذا كان المستند المُولَّد يجب أن يتضمن شرائح مخفية أم لا. الافتراضي هو false.

**الإرجاع:**
boolean
### setShowHiddenSlides(boolean value) {#setShowHiddenSlides-boolean-}
```
public final void setShowHiddenSlides(boolean value)
```


يحدد ما إذا كان المستند المُولَّد يجب أن يتضمن شرائح مخفية أم لا. الافتراضي هو false.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getSaveMetafilesAsPng() {#getSaveMetafilesAsPng--}
```
public final boolean getSaveMetafilesAsPng()
```


True لتحويل جميع ملفات الميتا المستخدمة في العرض إلى صور PNG. قابل للقراءة والكتابة boolean.

--------------------

الافتراضي هو **true**.

**الإرجاع:**
boolean
### setSaveMetafilesAsPng(boolean value) {#setSaveMetafilesAsPng-boolean-}
```
public final void setSaveMetafilesAsPng(boolean value)
```


True لتحويل جميع ملفات الميتا المستخدمة في العرض إلى صور PNG. قابل للقراءة والكتابة boolean.

--------------------

الافتراضي هو **true**.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getDrawSlidesFrame() {#getDrawSlidesFrame--}
```
public final boolean getDrawSlidesFrame()
```


True لرسم إطار أسود حول كل شريحة. قابل للقراءة والكتابة boolean.

--------------------

الافتراضي هو **false**.

**الإرجاع:**
boolean
### setDrawSlidesFrame(boolean value) {#setDrawSlidesFrame-boolean-}
```
public final void setDrawSlidesFrame(boolean value)
```


True لرسم إطار أسود حول كل شريحة. قابل للقراءة والكتابة boolean.

--------------------

الافتراضي هو **false**.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |