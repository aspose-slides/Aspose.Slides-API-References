---
title: HtmlOptions
second_title: مرجع واجهة برمجة تطبيقات Aspose.Slides للغة Java
description: يمثل خيارات تصدير HTML.
type: docs
url: /ar/com.aspose.slides/htmloptions/
---
**الوراثة:**  
java.lang.Object, [com.aspose.slides.SaveOptions](../../com.aspose.slides/saveoptions)

**جميع الواجهات المنفذة:**  
[com.aspose.slides.IHtmlOptions](../../com.aspose.slides/ihtmloptions)  
```
public class HtmlOptions extends SaveOptions implements IHtmlOptions
```

يمثل خيارات تصدير HTML.

## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [HtmlOptions(ILinkEmbedController linkEmbedController)](#HtmlOptions-com.aspose.slides.ILinkEmbedController-) | ينشئ كائن HtmlOptions جديد يحدد رد النداء. |
| [HtmlOptions()](#HtmlOptions--) | ينشئ كائن HtmlOptions جديد لحفظه في ملف HTML واحد. |

## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getSlidesLayoutOptions()](#getSlidesLayoutOptions--) | يجلب أو يحدد الوضع الذي تُوضع فيه الشرائح على الصفحة عند تصدير عرض تقديمي [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). |
| [setSlidesLayoutOptions(ISlidesLayoutOptions value)](#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-) | يجلب أو يحدد الوضع الذي تُوضع فيه الشرائح على الصفحة عند تصدير عرض تقديمي [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). |
| [getInkOptions()](#getInkOptions--) | يوفر خيارات تتحكم في مظهر كائنات الحبر في المستند المصدر. |
| [getShowHiddenSlides()](#getShowHiddenSlides--) | يحدد ما إذا كان المستند المُولد يجب أن يتضمن شرائح مخفية أم لا. |
| [setShowHiddenSlides(boolean value)](#setShowHiddenSlides-boolean-) | يحدد ما إذا كان المستند المُولد يجب أن يتضمن شرائح مخفية أم لا. |
| [getHtmlFormatter()](#getHtmlFormatter--) | يجلب أو يحدد قالب HTML. |
| [setHtmlFormatter(IHtmlFormatter value)](#setHtmlFormatter-com.aspose.slides.IHtmlFormatter-) | يجلب أو يحدد قالب HTML. |
| [getDisableFontLigatures()](#getDisableFontLigatures--) | يجلب أو يحدد قيمة تشير إلى ما إذا كان النص يُعرض دون استخدام الروابط الحرفية. |
| [setDisableFontLigatures(boolean value)](#setDisableFontLigatures-boolean-) | يجلب أو يحدد قيمة تشير إلى ما إذا كان النص يُعرض دون استخدام الروابط الحرفية. |
| [getSlideImageFormat()](#getSlideImageFormat--) | يجلب أو يحدد خيارات تنسيق صورة الشريحة. |
| [setSlideImageFormat(ISlideImageFormat value)](#setSlideImageFormat-com.aspose.slides.ISlideImageFormat-) | يجلب أو يحدد خيارات تنسيق صورة الشريحة. |
| [getJpegQuality()](#getJpegQuality--) | يجلب أو يحدد قيمة تحدد جودة صور JPEG داخل مستند PDF. |
| [setJpegQuality(byte value)](#setJpegQuality-byte-) | يجلب أو يحدد قيمة تحدد جودة صور JPEG داخل مستند PDF. |
| [getPicturesCompression()](#getPicturesCompression--) | يمثل مستوى ضغط الصور |
| [setPicturesCompression(int value)](#setPicturesCompression-int-) | يمثل مستوى ضغط الصور |
| [getDeletePicturesCroppedAreas()](#getDeletePicturesCroppedAreas--) | علامة منطقية تشير إلى ما إذا كانت الأجزاء المقتصة تبقى كجزء من المستند. |
| [setDeletePicturesCroppedAreas(boolean value)](#setDeletePicturesCroppedAreas-boolean-) | علامة منطقية تشير إلى ما إذا كانت الأجزاء المقتصة تبقى كجزء من المستند. |
| [getSvgResponsiveLayout()](#getSvgResponsiveLayout--) | صحيح لاستبعاد سمات العرض والارتفاع من حاوية SVG - سيجعل التخطيط مستجيباً. |
| [setSvgResponsiveLayout(boolean value)](#setSvgResponsiveLayout-boolean-) | صحيح لاستبعاد سمات العرض والارتفاع من حاوية SVG - سيجعل التخطيط مستجيباً. |

### HtmlOptions(ILinkEmbedController linkEmbedController) {#HtmlOptions-com.aspose.slides.ILinkEmbedController-}
```
public HtmlOptions(ILinkEmbedController linkEmbedController)
```

ينشئ كائن HtmlOptions جديد يحدد رد النداء.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| linkEmbedController | [ILinkEmbedController](../../com.aspose.slides/ilinkembedcontroller) | كائن رد النداء الذي يتحكم في حفظ المشروع. |

### HtmlOptions() {#HtmlOptions--}
```
public HtmlOptions()
```

ينشئ كائن HtmlOptions جديد لحفظه في ملف HTML واحد.

### getSlidesLayoutOptions() {#getSlidesLayoutOptions--}
```
public final ISlidesLayoutOptions getSlidesLayoutOptions()
```

يجلب أو يحدد الوضع الذي تُوضع فيه الشرائح على الصفحة عند تصدير عرض تقديمي [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions).

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      HtmlOptions options = new HtmlOptions();
>      HandoutLayoutingOptions slidesLayoutOptions = new HandoutLayoutingOptions();
>      slidesLayoutOptions.setHandout(HandoutType.Handouts4Horizontal);
>      options.setSlidesLayoutOptions(slidesLayoutOptions);
> 
>      pres.save("pres.html", SaveFormat.Html, options);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**القيمة المرجعية:**
[ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions)

### setSlidesLayoutOptions(ISlidesLayoutOptions value) {#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-}
```
public final void setSlidesLayoutOptions(ISlidesLayoutOptions value)
```

يجلب أو يحدد الوضع الذي تُوضع فيه الشرائح على الصفحة عند تصدير عرض تقديمي [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions).

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      HtmlOptions options = new HtmlOptions();
>      HandoutLayoutingOptions slidesLayoutOptions = new HandoutLayoutingOptions();
>      slidesLayoutOptions.setHandout(HandoutType.Handouts4Horizontal);
>      options.setSlidesLayoutOptions(slidesLayoutOptions);
> 
>      pres.save("pres.html", SaveFormat.Html, options);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions) |  |

### getInkOptions() {#getInkOptions--}
```
public final IInkOptions getInkOptions()
```

يوفر خيارات تتحكم في مظهر كائنات الحبر في المستند المصدر. قراءة فقط [IInkOptions](../../com.aspose.slides/iinkoptions)

**القيمة المرجعية:**
[IInkOptions](../../com.aspose.slides/iinkoptions)

### getShowHiddenSlides() {#getShowHiddenSlides--}
```
public final boolean getShowHiddenSlides()
```

يحدد ما إذا كان المستند المُولد يجب أن يتضمن شرائح مخفية أم لا. القيمة الافتراضية هي false.

**القيمة المرجعية:**
boolean

### setShowHiddenSlides(boolean value) {#setShowHiddenSlides-boolean-}
```
public final void setShowHiddenSlides(boolean value)
```

يحدد ما إذا كان المستند المُولد يجب أن يتضمن شرائح مخفية أم لا. القيمة الافتراضية هي false.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getHtmlFormatter() {#getHtmlFormatter--}
```
public final IHtmlFormatter getHtmlFormatter()
```

يجلب أو يحدد قالب HTML. قراءة/كتابة [IHtmlFormatter](../../com.aspose.slides/ihtmlformatter).

**القيمة المرجعية:**
[IHtmlFormatter](../../com.aspose.slides/ihtmlformatter)

### setHtmlFormatter(IHtmlFormatter value) {#setHtmlFormatter-com.aspose.slides.IHtmlFormatter-}
```
public final void setHtmlFormatter(IHtmlFormatter value)
```

يجلب أو يحدد قالب HTML. قراءة/كتابة [IHtmlFormatter](../../com.aspose.slides/ihtmlformatter).

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | [IHtmlFormatter](../../com.aspose.slides/ihtmlformatter) |  |

### getDisableFontLigatures() {#getDisableFontLigatures--}
```
public final boolean getDisableFontLigatures()
```

يجلب أو يحدد قيمة تشير إلى ما إذا كان النص يُعرض دون استخدام الروابط الحرفية. عند تعيينها إلى true، سيتم إلغاء الروابط الحرفية في الإخراج المعروض. بشكل افتراضي، تُضبط هذه الخاصية على false.

--------------------
> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      HtmlOptions options = new HtmlOptions();
>      options.setDisableFontLigatures(true);
>      pres.save("presentation.html", SaveFormat.Html, options);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**القيمة المرجعية:**
boolean

### setDisableFontLigatures(boolean value) {#setDisableFontLigatures-boolean-}
```
public final void setDisableFontLigatures(boolean value)
```

يجلب أو يحدد قيمة تشير إلى ما إذا كان النص يُعرض دون استخدام الروابط الحرفية. عند تعيينها إلى true، سيتم إلغاء الروابط الحرفية في الإخراج المعروض. بشكل افتراضي، تُضبط هذه الخاصية على false.

--------------------
> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      HtmlOptions options = new HtmlOptions();
>      options.setDisableFontLigatures(true);
>      pres.save("presentation.html", SaveFormat.Html, options);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getSlideImageFormat() {#getSlideImageFormat--}
```
public final ISlideImageFormat getSlideImageFormat()
```

يجلب أو يحدد خيارات تنسيق صورة الشريحة. قراءة/كتابة [ISlideImageFormat](../../com.aspose.slides/islideimageformat).

**القيمة المرجعية:**
[ISlideImageFormat](../../com.aspose.slides/islideimageformat)

### setSlideImageFormat(ISlideImageFormat value) {#setSlideImageFormat-com.aspose.slides.ISlideImageFormat-}
```
public final void setSlideImageFormat(ISlideImageFormat value)
```

يجلب أو يحدد خيارات تنسيق صورة الشريحة. قراءة/كتابة [ISlideImageFormat](../../com.aspose.slides/islideimageformat).

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | [ISlideImageFormat](../../com.aspose.slides/islideimageformat) |  |

### getJpegQuality() {#getJpegQuality--}
```
public final byte getJpegQuality()
```

يجلب أو يحدد قيمة تحدد جودة صور JPEG داخل مستند PDF. قراءة/كتابة byte.

لها تأثير فقط عندما يحتوي المستند على صور JPEG.

استخدم هذه الخاصية للحصول على جودة الصور داخل المستند أو لتحديدها عند الحفظ بصيغة PDF. يمكن أن تتراوح القيمة من 0 إلى 100 حيث 0 تعني أسوأ جودة مع أقصى ضغط و100 تعني أفضل جودة مع أقل ضغط.

القيمة الافتراضية هي **95**.

**القيمة المرجعية:**
byte

### setJpegQuality(byte value) {#setJpegQuality-byte-}
```
public final void setJpegQuality(byte value)
```

يجلب أو يحدد قيمة تحدد جودة صور JPEG داخل مستند PDF. قراءة/كتابة byte.

لها تأثير فقط عندما يحتوي المستند على صور JPEG.

استخدم هذه الخاصية للحصول على جودة الصور داخل المستند أو لتحديدها عند الحفظ بصيغة PDF. يمكن أن تتراوح القيمة من 0 إلى 100 حيث 0 تعني أسوأ جودة مع أقصى ضغط و100 تعني أفضل جودة مع أقل ضغط.

القيمة الافتراضية هي **95**.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | byte |  |

### getPicturesCompression() {#getPicturesCompression--}
```
public final int getPicturesCompression()
```

يمثل مستوى ضغط الصور

**القيمة المرجعية:**
int

### setPicturesCompression(int value) {#setPicturesCompression-int-}
```
public final void setPicturesCompression(int value)
```

يمثل مستوى ضغط الصور

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getDeletePicturesCroppedAreas() {#getDeletePicturesCroppedAreas--}
```
public final boolean getDeletePicturesCroppedAreas()
```

علامة منطقية تشير إلى ما إذا كانت الأجزاء المقتصة تبقى كجزء من المستند. إذا كانت true سيتم إزالة الأجزاء المقتصة، وإذا كانت false ستُسلسَل في المستند (مما قد يؤدي إلى ملف أكبر).

**القيمة المرجعية:**
boolean

### setDeletePicturesCroppedAreas(boolean value) {#setDeletePicturesCroppedAreas-boolean-}
```
public final void setDeletePicturesCroppedAreas(boolean value)
```

علامة منطقية تشير إلى ما إذا كانت الأجزاء المقتصة تبقى كجزء من المستند. إذا كانت true سيتم إزالة الأجزاء المقتصة، وإذا كانت false ستُسلسَل في المستند (مما قد يؤدي إلى ملف أكبر).

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getSvgResponsiveLayout() {#getSvgResponsiveLayout--}
```
public final boolean getSvgResponsiveLayout()
```

صحيح لاستبعاد سمات العرض والارتفاع من حاوية SVG - سيجعل التخطيط مستجيباً. خطأ - غير ذلك. قراءة/كتابة boolean.

**القيمة المرجعية:**
boolean

### setSvgResponsiveLayout(boolean value) {#setSvgResponsiveLayout-boolean-}
```
public final void setSvgResponsiveLayout(boolean value)
```

صحيح لاستبعاد سمات العرض والارتفاع من حاوية SVG - سيجعل التخطيط مستجيباً. خطأ - غير ذلك. قراءة/كتابة boolean.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |