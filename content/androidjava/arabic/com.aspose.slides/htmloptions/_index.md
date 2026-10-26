---
title: HtmlOptions
second_title: Aspose.Slides لنظام Android عبر مرجع API للجاوة
description: يمثل خيارات تصدير HTML.
type: docs
url: /ar/com.aspose.slides/htmloptions/
---
**الوراثة:**
java.lang.Object, [com.aspose.slides.SaveOptions](../../com.aspose.slides/saveoptions)

**جميع الواجهات المُنفذة:**
[com.aspose.slides.IHtmlOptions](../../com.aspose.slides/ihtmloptions)
```
public class HtmlOptions extends SaveOptions implements IHtmlOptions
```

يمثل خيارات تصدير HTML.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [HtmlOptions(ILinkEmbedController linkEmbedController)](#HtmlOptions-com.aspose.slides.ILinkEmbedController-) | ينشئ كائن HtmlOptions جديد يحدد رد النداء. |
| [HtmlOptions()](#HtmlOptions--) | ينشئ كائن HtmlOptions جديد للحفظ في ملف HTML واحد. |
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getSlidesLayoutOptions()](#getSlidesLayoutOptions--) | يجلب أو يحدد الوضع الذي توضع فيه الشرائح على الصفحة عند تصدير عرض تقديمي [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). |
| [setSlidesLayoutOptions(ISlidesLayoutOptions value)](#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-) | يجلب أو يحدد الوضع الذي توضع فيه الشرائح على الصفحة عند تصدير عرض تقديمي [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). |
| [getInkOptions()](#getInkOptions--) | يقدم خيارات تتحكم في مظهر كائنات الحبر في المستند المُصدّر. |
| [getShowHiddenSlides()](#getShowHiddenSlides--) | يحدد ما إذا كان يجب أن يتضمن المستند المُولد شرائح مخفية أم لا. |
| [setShowHiddenSlides(boolean value)](#setShowHiddenSlides-boolean-) | يحدد ما إذا كان يجب أن يتضمن المستند المُولد شرائح مخفية أم لا. |
| [getHtmlFormatter()](#getHtmlFormatter--) | يرجع أو يحدد قالب HTML. |
| [setHtmlFormatter(IHtmlFormatter value)](#setHtmlFormatter-com.aspose.slides.IHtmlFormatter-) | يرجع أو يحدد قالب HTML. |
| [getDisableFontLigatures()](#getDisableFontLigatures--) | يجلب أو يحدد قيمة تشير إلى ما إذا كان النص يُعرض دون استخدام الأحرف المتصلة. |
| [setDisableFontLigatures(boolean value)](#setDisableFontLigatures-boolean-) | يجلب أو يحدد قيمة تشير إلى ما إذا كان النص يُعرض دون استخدام الأحرف المتصلة. |
| [getSlideImageFormat()](#getSlideImageFormat--) | يرجع أو يحدد خيارات تنسيق صورة الشريحة. |
| [setSlideImageFormat(ISlideImageFormat value)](#setSlideImageFormat-com.aspose.slides.ISlideImageFormat-) | يرجع أو يحدد خيارات تنسيق صورة الشريحة. |
| [getJpegQuality()](#getJpegQuality--) | يرجع أو يحدد قيمة تحدد جودة صور JPEG داخل مستند PDF. |
| [setJpegQuality(byte value)](#setJpegQuality-byte-) | يرجع أو يحدد قيمة تحدد جودة صور JPEG داخل مستند PDF. |
| [getPicturesCompression()](#getPicturesCompression--) | يمثل مستوى ضغط الصور |
| [setPicturesCompression(int value)](#setPicturesCompression-int-) | يمثل مستوى ضغط الصور |
| [getDeletePicturesCroppedAreas()](#getDeletePicturesCroppedAreas--) | علم منطقي يشير إلى ما إذا كانت الأجزاء المقصوصة تظل جزءًا من المستند. |
| [setDeletePicturesCroppedAreas(boolean value)](#setDeletePicturesCroppedAreas-boolean-) | علم منطقي يشير إلى ما إذا كانت الأجزاء المقصوصة تظل جزءًا من المستند. |
| [getSvgResponsiveLayout()](#getSvgResponsiveLayout--) | true لاستبعاد سمة العرض والارتفاع من حاوية svg - سيجعل التخطيط استجابياً. |
| [setSvgResponsiveLayout(boolean value)](#setSvgResponsiveLayout-boolean-) | true لاستبعاد سمة العرض والارتفاع من حاوية svg - سيجعل التخطيط استجابياً. |
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

ينشئ كائن HtmlOptions جديد للحفظ في ملف HTML واحد.

### getSlidesLayoutOptions() {#getSlidesLayoutOptions--}
```
public final ISlidesLayoutOptions getSlidesLayoutOptions()
```

يجلب أو يحدد الوضع الذي توضع فيه الشرائح على الصفحة عند تصدير عرض تقديمي [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions).

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

**الإ رجاع:**
[ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions)
### setSlidesLayoutOptions(ISlidesLayoutOptions value) {#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-}
```
public final void setSlidesLayoutOptions(ISlidesLayoutOptions value)
```

يجلب أو يحدد الوضع الذي توضع فيه الشرائح على الصفحة عند تصدير عرض تقديمي [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions).

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

يقدم خيارات تتحكم في مظهر كائنات الحبر في المستند المُصدّر. للقراءة فقط [IInkOptions](../../com.aspose.slides/iinkoptions)

**الإرجاع:**
[IInkOptions](../../com.aspose.slides/iinkoptions)
### getShowHiddenSlides() {#getShowHiddenSlides--}
```
public final boolean getShowHiddenSlides()
```

يحدد ما إذا كان يجب أن يتضمن المستند المُولد شرائح مخفية أم لا. القيمة الافتراضية هي false.

**الإرجاع:**
boolean
### setShowHiddenSlides(boolean value) {#setShowHiddenSlides-boolean-}
```
public final void setShowHiddenSlides(boolean value)
```

يحدد ما إذا كان يجب أن يتضمن المستند المُولد شرائح مخفية أم لا. القيمة الافتراضية هي false.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getHtmlFormatter() {#getHtmlFormatter--}
```
public final IHtmlFormatter getHtmlFormatter()
```

يرجع أو يحدد قالب HTML. قراءة/كتابة [IHtmlFormatter](../../com.aspose.slides/ihtmlformatter).

**الإرجاع:**
[IHtmlFormatter](../../com.aspose.slides/ihtmlformatter)
### setHtmlFormatter(IHtmlFormatter value) {#setHtmlFormatter-com.aspose.slides.IHtmlFormatter-}
```
public final void setHtmlFormatter(IHtmlFormatter value)
```

يرجع أو يحدد قالب HTML. قراءة/كتابة [IHtmlFormatter](../../com.aspose.slides/ihtmlformatter).

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | [IHtmlFormatter](../../com.aspose.slides/ihtmlformatter) |  |

### getDisableFontLigatures() {#getDisableFontLigatures--}
```
public final boolean getDisableFontLigatures()
```

يجلب أو يحدد قيمة تشير إلى ما إذا كان النص يُعرض دون استخدام الأحرف المتصلة. عندما تكون true، سيتم تعطيل الأحرف المتصلة في الإخراج. بشكل افتراضي، هذه الخاصية false.

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

**الإرجاع:**
boolean
### setDisableFontLigatures(boolean value) {#setDisableFontLigatures-boolean-}
```
public final void setDisableFontLigatures(boolean value)
```

يجلب أو يحدد قيمة تشير إلى ما إذا كان النص يُعرض دون استخدام الأحرف المتصلة. عندما تكون true، سيتم تعطيل الأحرف المتصلة في الإخراج. بشكل افتراضي، هذه الخاصية false.

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

يرجع أو يحدد خيارات تنسيق صورة الشريحة. قراءة/كتابة [ISlideImageFormat](../../com.aspose.slides/islideimageformat).

**الإرجاع:**
[ISlideImageFormat](../../com.aspose.slides/islideimageformat)
### setSlideImageFormat(ISlideImageFormat value) {#setSlideImageFormat-com.aspose.slides.ISlideImageFormat-}
```
public final void setSlideImageFormat(ISlideImageFormat value)
```

يرجع أو يحدد خيارات تنسيق صورة الشريحة. قراءة/كتابة [ISlideImageFormat](../../com.aspose.slides/islideimageformat).

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | [ISlideImageFormat](../../com.aspose.slides/islideimageformat) |  |

### getJpegQuality() {#getJpegQuality--}
```
public final byte getJpegQuality()
```

يرجع أو يحدد قيمة تحدد جودة صور JPEG داخل مستند PDF. قراءة/كتابة بايت.

--------------------

لها تأثير فقط عندما يحتوي المستند على صور JPEG.

استخدم هذه الخاصية للحصول على أو ضبط جودة الصور داخل مستند عند الحفظ بصيغة PDF. قد تتراوح القيمة من 0 إلى 100 حيث يعني 0 أسوأ جودة ولكن أقصى ضغط و 100 أفضل جودة ولكن أقل ضغط.

القيمة الافتراضية هي **95**.

**الإرجاع:**
byte
### setJpegQuality(byte value) {#setJpegQuality-byte-}
```
public final void setJpegQuality(byte value)
```

يرجع أو يحدد قيمة تحدد جودة صور JPEG داخل مستند PDF. قراءة/كتابة بايت.

--------------------

لها تأثير فقط عندما يحتوي المستند على صور JPEG.

استخدم هذه الخاصية للحصول على أو ضبط جودة الصور داخل مستند عند الحفظ بصيغة PDF. قد تتراوح القيمة من 0 إلى 100 حيث يعني 0 أسوأ جودة ولكن أقصى ضغط و 100 أفضل جودة ولكن أقل ضغط.

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

**الإرجاع:**
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

علم منطقي يشير إلى ما إذا كانت الأجزاء المقصوصة تظل جزءًا من المستند. إذا كان true ستُحذف الأجزاء المقصوصة، إذا كان false سيتم تسلسلها في المستند (مما قد يؤدي إلى ملف أكبر)

**الإرجاع:**
boolean
### setDeletePicturesCroppedAreas(boolean value) {#setDeletePicturesCroppedAreas-boolean-}
```
public final void setDeletePicturesCroppedAreas(boolean value)
```

علم منطقي يشير إلى ما إذا كانت الأجزاء المقصوصة تظل جزءًا من المستند. إذا كان true ستُحذف الأجزاء المقصوصة، إذا كان false سيتم تسلسلها في المستند (مما قد يؤدي إلى ملف أكبر)

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getSvgResponsiveLayout() {#getSvgResponsiveLayout--}
```
public final boolean getSvgResponsiveLayout()
```

true لاستبعاد سمة العرض والارتفاع من حاوية svg - سيجعل التخطيط استجابياً. false - غير ذلك. قراءة/كتابة منطقية.

**الإرجاع:**
boolean
### setSvgResponsiveLayout(boolean value) {#setSvgResponsiveLayout-boolean-}
```
public final void setSvgResponsiveLayout(boolean value)
```

true لاستبعاد سمة العرض والارتفاع من حاوية svg - سيج جعل التخطيط استجابياً. false - غير ذلك. قراءة/كتابة منطقية.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |