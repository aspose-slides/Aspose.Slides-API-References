---
title: IHtmlOptions
second_title: Aspose.Slides لنظام Android عبر مرجع API لجافا
description: يمثل خيارات تصدير HTML.
type: docs
url: /ar/com.aspose.slides/ihtmloptions/
---
**جميع الواجهات المُنفذة:**
[com.aspose.slides.ISaveOptions](../../com.aspose.slides/isaveoptions)
```
public interface IHtmlOptions extends ISaveOptions
```

يمثل خيارات تصدير HTML.
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getHtmlFormatter()](#getHtmlFormatter--) | إرجاع أو تعيين قالب HTML. |
| [setHtmlFormatter(IHtmlFormatter value)](#setHtmlFormatter-com.aspose.slides.IHtmlFormatter-) | إرجاع أو تعيين قالب HTML. |
| [getSlideImageFormat()](#getSlideImageFormat--) | إرجاع أو تعيين خيارات تنسيق صورة الشريحة. |
| [setSlideImageFormat(ISlideImageFormat value)](#setSlideImageFormat-com.aspose.slides.ISlideImageFormat-) | إرجاع أو تعيين خيارات تنسيق صورة الشريحة. |
| [getShowHiddenSlides()](#getShowHiddenSlides--) | تحديد ما إذا كان المستند المُولد يجب أن يتضمن الشرائح المخفية أم لا. |
| [setShowHiddenSlides(boolean value)](#setShowHiddenSlides-boolean-) | تحديد ما إذا كان المستند المُولد يجب أن يتضمن الشرائح المخفية أم لا. |
| [getJpegQuality()](#getJpegQuality--) | إرجاع أو تعيين قيمة تحدد جودة صور JPEG داخل مستند PDF. |
| [setJpegQuality(byte value)](#setJpegQuality-byte-) | إرجاع أو تعيين قيمة تحدد جودة صور JPEG داخل مستند PDF. |
| [getPicturesCompression()](#getPicturesCompression--) | يمثل مستوى ضغط الصور قراءة/كتابة [PicturesCompression](../../com.aspose.slides/picturescompression)(\#getPicturesCompression.getPicturesCompression/\#setPicturesCompression(int).setPicturesCompression(int)). |
| [setPicturesCompression(int value)](#setPicturesCompression-int-) | يمثل مستوى ضغط الصور قراءة/كتابة [PicturesCompression](../../com.aspose.slides/picturescompression)(\#getPicturesCompression.getPicturesCompression/\#setPicturesCompression(int).setPicturesCompression(int)). |
| [getDeletePicturesCroppedAreas()](#getDeletePicturesCroppedAreas--) | علامة منطقية تشير إلى ما إذا كانت الأجزاء المقتصة تظل جزءًا من المستند. |
| [setDeletePicturesCroppedAreas(boolean value)](#setDeletePicturesCroppedAreas-boolean-) | علامة منطقية تشير إلى ما إذا كانت الأجزاء المقتصة تظل جزءًا من المستند. |
| [getSvgResponsiveLayout()](#getSvgResponsiveLayout--) | صحيح لاستبعاد سمات العرض والارتفاع من حاوية SVG - سيجعل التخطيط مستجيبًا. |
| [setSvgResponsiveLayout(boolean value)](#setSvgResponsiveLayout-boolean-) | صحيح لاستبعاد سمات العرض والارتفاع من حاوية SVG - سيجعل التخطيط مستجيبًا. |
| [getDisableFontLigatures()](#getDisableFontLigatures--) | الحصول أو تعيين قيمة تشير إلى ما إذا كان النص يُعرض دون استخدام الروابط الأحرفية. |
| [setDisableFontLigatures(boolean value)](#setDisableFontLigatures-boolean-) | الحصول أو تعيين قيمة تشير إلى ما إذا كان النص يُعرض دون استخدام الروابط الأحرفية. |
| [getSlidesLayoutOptions()](#getSlidesLayoutOptions--) | الحصول أو تعيين الوضع الذي تُوضع فيه الشرائح على الصفحة عند تصدير عرض تقديمي [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). |
| [setSlidesLayoutOptions(ISlidesLayoutOptions value)](#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-) | الحصول أو تعيين الوضع الذي تُوضع فيه الشرائح على الصفحة عند تصدير عرض تقديمي [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). |
| [getInkOptions()](#getInkOptions--) | يوفر خيارات تتحكم في مظهر كائنات الحبر في المستند المُصدّر. |
### getHtmlFormatter() {#getHtmlFormatter--}
```
public abstract IHtmlFormatter getHtmlFormatter()
```

إرجاع أو تعيين قالب HTML. قراءة/كتابة [IHtmlFormatter](../../com.aspose.slides/ihtmlformatter).

**الإرجاع:**
[IHtmlFormatter](../../com.aspose.slides/ihtmlformatter)
### setHtmlFormatter(IHtmlFormatter value) {#setHtmlFormatter-com.aspose.slides.IHtmlFormatter-}
```
public abstract void setHtmlFormatter(IHtmlFormatter value)
```

إرجاع أو تعيين قالب HTML. قراءة/كتابة [IHtmlFormatter](../../com.aspose.slides/ihtmlformatter).

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | [IHtmlFormatter](../../com.aspose.slides/ihtmlformatter) |  |

### getSlideImageFormat() {#getSlideImageFormat--}
```
public abstract ISlideImageFormat getSlideImageFormat()
```

إرجاع أو تعيين خيارات تنسيق صورة الشريحة. قراءة/كتابة [ISlideImageFormat](../../com.aspose.slides/islideimageformat).

**الإرجاع:**
[ISlideImageFormat](../../com.aspose.slides/islideimageformat)
### setSlideImageFormat(ISlideImageFormat value) {#setSlideImageFormat-com.aspose.slides.ISlideImageFormat-}
```
public abstract void setSlideImageFormat(ISlideImageFormat value)
```

إرجاع أو تعيين خيارات تنسيق صورة الشريحة. قراءة/كتابة [ISlideImageFormat](../../com.aspose.slides/islideimageformat).

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | [ISlideImageFormat](../../com.aspose.slides/islideimageformat) |  |

### getShowHiddenSlides() {#getShowHiddenSlides--}
```
public abstract boolean getShowHiddenSlides()
```

تحديد ما إذا كان المستند المُولد يجب أن يتضمن الشرائح المخفية أم لا. القيمة الافتراضية false.

**الإرجاع:**
boolean
### setShowHiddenSlides(boolean value) {#setShowHiddenSlides-boolean-}
```
public abstract void setShowHiddenSlides(boolean value)
```

تحديد ما إذا كان المستند المُولد يجب أن يتضمن الشرائح المخفية أم لا. القيمة الافتراضية false.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getJpegQuality() {#getJpegQuality--}
```
public abstract byte getJpegQuality()
```

إرجاع أو تعيين قيمة تحدد جودة صور JPEG داخل مستند PDF. قراءة/كتابة byte.

--------------------

لها تأثير فقط عندما يحتوي المستند على صور JPEG.

استخدم هذه الخاصية للحصول أو ضبط جودة الصور داخل المستند عند الحفظ بتنسيق PDF. قد تتراوح القيمة من 0 إلى 100 حيث 0 تعني أسوأ جودة لكن أقصى ضغط و100 تعني أفضل جودة لكن أقل ضغط.

القيمة الافتراضية هي **95**.

**الإرجاع:**
byte
### setJpegQuality(byte value) {#setJpegQuality-byte-}
```
public abstract void setJpegQuality(byte value)
```

إرجاع أو تعيين قيمة تحدد جودة صور JPEG داخل مستند PDF. قراءة/كتابة byte.

--------------------

لها تأثير فقط عندما يحتوي المستند على صور JPEG.

استخدم هذه الخاصية للحصول أو ضبط جودة الصور داخل المستند عند الحفظ بتنسيق PDF. قد تتراوح القيمة من 0 إلى 100 حيث 0 تعني أسوأ جودة لكن أقصى ضغط و100 تعني أفضل جودة لكن أقل ضغط.

القيمة الافتراضية هي **95**.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | byte |  |

### getPicturesCompression() {#getPicturesCompression--}
```
public abstract int getPicturesCompression()
```

يمثل مستوى ضغط الصور قراءة/كتابة [PicturesCompression](../../com.aspose.slides/picturescompression)(\#getPicturesCompression.getPicturesCompression/\#setPicturesCompression(int).setPicturesCompression(int)).

**الإرجاع:**
int
### setPicturesCompression(int value) {#setPicturesCompression-int-}
```
public abstract void setPicturesCompression(int value)
```

يمثل مستوى ضغط الصور قراءة/كتابة [PicturesCompression](../../com.aspose.slides/picturescompression)(\#getPicturesCompression.getPicturesCompression/\#setPicturesCompression(int).setPicturesCompression(int)).

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getDeletePicturesCroppedAreas() {#getDeletePicturesCroppedAreas--}
```
public abstract boolean getDeletePicturesCroppedAreas()
```

علامة منطقية تشير إلى ما إذا كانت الأجزاء المقتصة تظل جزءًا من المستند. إذا كان true سيتم إزالة الأجزاء المقتصة، إذا كان false سيتم تسلسلها في المستند (مما قد يؤدي إلى ملف أكبر) قراءة/كتابة boolean.

**الإرجاع:**
boolean
### setDeletePicturesCroppedAreas(boolean value) {#setDeletePicturesCroppedAreas-boolean-}
```
public abstract void setDeletePicturesCroppedAreas(boolean value)
```

علامة منطقية تشير إلى ما إذا كانت الأجزاء المقتصة تظل جزءًا من المستند. إذا كان true سيتم إزالة الأجزاء المقتصة، إذا كان false سيتم تسلسلها في المستند (مما قد يؤدي إلى ملف أكبر) قراءة/كتابة boolean.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getSvgResponsiveLayout() {#getSvgResponsiveLayout--}
```
public abstract boolean getSvgResponsiveLayout()
```

صحيح لاستبعاد سمات العرض والارتفاع من حاوية SVG - سيجعل التخطيط مستجيبًا. false - غير ذلك. قراءة/كتابة boolean.

**الإرجاع:**
boolean
### setSvgResponsiveLayout(boolean value) {#setSvgResponsiveLayout-boolean-}
```
public abstract void setSvgResponsiveLayout(boolean value)
```

صحيح لاستبعاد سمات العرض والارتفاع من حاوية SVG - سيجعل التخطيط مستجيبًا. false - غير ذلك. قراءة/كتابة boolean.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getDisableFontLigatures() {#getDisableFontLigatures--}
```
public abstract boolean getDisableFontLigatures()
```

الحصول أو تعيين قيمة تشير إلى ما إذا كان النص يُعرض دون استخدام الروابط الأحرفية. عندما تكون true، سيتم تعطيل الروابط الأحرفية في المخرجات. القيمة الافتراضية false.

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
public abstract void setDisableFontLigatures(boolean value)
```

الحصول أو تعيين قيمة تشير إلى ما إذا كان النص يُعرض دون استخدام الروابط الأحرفية. عندما تكون true، سيتم تعطيل الروابط الأحرفية في المخرجات. القيمة الافتراضية false.

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

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getSlidesLayoutOptions() {#getSlidesLayoutOptions--}
```
public abstract ISlidesLayoutOptions getSlidesLayoutOptions()
```

الحصول أو تعيين الوضع الذي تُوضع فيه الشرائح على الصفحة عند تصدير عرض تقديمي [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions).

--------------------

> ```
> مثال:
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

**الإرجاع:**
[ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions)
### setSlidesLayoutOptions(ISlidesLayoutOptions value) {#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-}
```
public abstract void setSlidesLayoutOptions(ISlidesLayoutOptions value)
```

الحصول أو تعيين الوضع الذي تُوضع فيه الشرائح على الصفحة عند تصدير عرض تقديمي [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions).

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

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions) |  |

### getInkOptions() {#getInkOptions--}
```
public abstract IInkOptions getInkOptions()
```

يوفر خيارات تتحكم في مظهر كائنات الحبر في المستند المُصدّر. قراءة فقط [IInkOptions](../../com.aspose.slides/iinkoptions)

**الإرجاع:**
[IInkOptions](../../com.aspose.slides/iinkoptions)