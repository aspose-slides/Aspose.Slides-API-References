---
title: XpsOptions
second_title: مرجع API Aspose.Slides للغة Java
description: يوفر خيارات تتحكم في طريقة حفظ العرض التقديمي بتنسيق XPS.
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

يوفر خيارات تتحكم في كيفية حفظ العرض التقديمي بتنسيق XPS.

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
>      // حفظ ملفات الميتا بصيغة PNG
>      options.setSaveMetafilesAsPng(true);
>      // حفظ العرض التقديمي إلى مستند XPS
>      pres.save("XPS_With_Options_out.xps", SaveFormat.Xps, options);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [XpsOptions()](#XpsOptions--) | المنشئ الافتراضي. |
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getShowHiddenSlides()](#getShowHiddenSlides--) | يحدد ما إذا كان ينبغي أن يتضمن المستند المُولَّد الشرائح المخفيّة أم لا. |
| [setShowHiddenSlides(boolean value)](#setShowHiddenSlides-boolean-) | يحدد ما إذا كان ينبغي أن يتضمن المستند المُولَّد الشرائح المخفيّة أم لا. |
| [getSaveMetafilesAsPng()](#getSaveMetafilesAsPng--) | صحيح لتحويل جميع ملفات الميتا المستخدمة في عرض تقديمي إلى صور PNG. |
| [setSaveMetafilesAsPng(boolean value)](#setSaveMetafilesAsPng-boolean-) | صحيح لتحويل جميع ملفات الميتا المستخدمة في عرض تقديمي إلى صور PNG. |
| [getDrawSlidesFrame()](#getDrawSlidesFrame--) | صحيح لرسم إطار أسود حول كل شريحة. |
| [setDrawSlidesFrame(boolean value)](#setDrawSlidesFrame-boolean-) | صحيح لرسم إطار أسود حول كل شريحة. |
### XpsOptions() {#XpsOptions--}
```
public XpsOptions()
```

المنشئ الافتراضي.

### getShowHiddenSlides() {#getShowHiddenSlides--}
```
public final boolean getShowHiddenSlides()
```

يحدد ما إذا كان ينبغي أن يتضمن المستند المُولَّد الشرائح المخفيّة أم لا. القيمة الافتراضية هي false.

**الإرجاع:**
boolean
### setShowHiddenSlides(boolean value) {#setShowHiddenSlides-boolean-}
```
public final void setShowHiddenSlides(boolean value)
```

يحدد ما إذا كان ينبغي أن يتضمن المستند المُولَّد الشرائح المخفيّة أم لا. القيمة الافتراضية هي false.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getSaveMetafilesAsPng() {#getSaveMetafilesAsPng--}
```
public final boolean getSaveMetafilesAsPng()
```

صحيح لتحويل جميع ملفات الميتا المستخدمة في عرض تقديمي إلى صور PNG. قابل للقراءة والكتابة boolean.

--------------------

القيمة الافتراضية هي **true**.

**الإرجاع:**
boolean
### setSaveMetafilesAsPng(boolean value) {#setSaveMetafilesAsPng-boolean-}
```
public final void setSaveMetafilesAsPng(boolean value)
```

صحيح لتحويل جميع ملفات الميتا المستخدمة في عرض تقديمي إلى صور PNG. قابل للقراءة والكتابة boolean.

--------------------

القيمة الافتراضية هي **true**.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getDrawSlidesFrame() {#getDrawSlidesFrame--}
```
public final boolean getDrawSlidesFrame()
```

صحيح لرسم إطار أسود حول كل شريحة. قابل للقراءة والكتابة boolean.

--------------------

القيمة الافتراضية هي **false**.

**الإرجاع:**
boolean
### setDrawSlidesFrame(boolean value) {#setDrawSlidesFrame-boolean-}
```
public final void setDrawSlidesFrame(boolean value)
```

صحيح لرسم إطار أسود حول كل شريحة. قابل للقراءة والكتابة boolean.

--------------------

القيمة الافتراضية هي **false**.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |