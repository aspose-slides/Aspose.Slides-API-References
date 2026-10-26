---
title: IHtmlOptions
second_title: مرجع واجهة برمجة التطبيقات Aspose.Slides للـ Java
description: يمثل خيارات تصدير HTML.
type: docs
url: /ar/com.aspose.slides/ihtmloptions/
---
**جميع الواجهات المنفذة:**
[com.aspose.slides.ISaveOptions](../../com.aspose.slides/isaveoptions)
```
public interface IHtmlOptions extends ISaveOptions
```

يمثل خيارات تصدير HTML.
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getHtmlFormatter()](#getHtmlFormatter--) | يرجع أو يعيّن قالب HTML. |
| [setHtmlFormatter(IHtmlFormatter value)](#setHtmlFormatter-com.aspose.slides.IHtmlFormatter-) | يرجع أو يعيّن قالب HTML. |
| [getSlideImageFormat()](#getSlideImageFormat--) | يرجع أو يعيّن خيارات تنسيق صورة الشريحة. |
| [setSlideImageFormat(ISlideImageFormat value)](#setSlideImageFormat-com.aspose.slides.ISlideImageFormat-) | يرجع أو يعيّن خيارات تنسيق صورة الشريحة. |
| [getShowHiddenSlides()](#getShowHiddenSlides--) | يحدد ما إذا كان المستند المُولَّد يجب أن يتضمن شرائح مخفية أم لا. |
| [setShowHiddenSlides(boolean value)](#setShowHiddenSlides-boolean-) | يحدد ما إذا كان المستند المُولَّد يجب أن يتضمن شرائح مخفية أم لا. |
| [getJpegQuality()](#getJpegQuality--) | يرجع أو يعيّن قيمة تحدد جودة صور JPEG داخل مستند PDF. |
| [setJpegQuality(byte value)](#setJpegQuality-byte-) | يرجع أو يعيّن قيمة تحدد جودة صور JPEG داخل مستند PDF. |
| [getPicturesCompression()](#getPicturesCompression--) | يمثل مستوى ضغط الصور Read/write [PicturesCompression](../../com.aspose.slides/picturescompression)(\#getPicturesCompression.getPicturesCompression/\#setPicturesCompression(int).setPicturesCompression(int)). |
| [setPicturesCompression(int value)](#setPicturesCompression-int-) | يمثل مستوى ضغط الصور Read/write [PicturesCompression](../../com.aspose.slides/picturescompression)(\#getPicturesCompression.getPicturesCompression/\#setPicturesCompression(int).setPicturesCompression(int)). |
| [getDeletePicturesCroppedAreas()](#getDeletePicturesCroppedAreas--) | علامة منطقية تشير إلى ما إذا كانت الأجزاء المقصوصة ستبقى كجزء من المستند. |
| [setDeletePicturesCroppedAreas(boolean value)](#setDeletePicturesCroppedAreas-boolean-) | علامة منطقية تشير إلى ما إذا كانت الأجزاء المقصوصة ستبقى كجزء من المستند. |
| [getSvgResponsiveLayout()](#getSvgResponsiveLayout--) | صحيح لاستبعاد سمات العرض والارتفاع من حاوية SVG - سيجعل ذلك التخطيط مستجيبًا. |
| [setSvgResponsiveLayout(boolean value)](#setSvgResponsiveLayout-boolean-) | صحيح لاستبعاد سمات العرض والارتفاع من حاوية SVG - سيجعل ذلك التخطيط مستجيبًا. |
| [getDisableFontLigatures()](#getDisableFontLigatures--) | يحصل أو يعيّن قيمة تشير إلى ما إذا كان النص يُعرض دون استخدام الأحرف المربوطة. |
| [setDisableFontLigatures(boolean value)](#setDisableFontLigatures-boolean-) | يحصل أو يعيّن قيمة تشير إلى ما إذا كان النص يُعرض دون استخدام الأحرف المربوطة. |
| [getSlidesLayoutOptions()](#getSlidesLayoutOptions--) | يحصل أو يعيّن الوضع الذي تُوضع فيه الشرائح على الصفحة عند تصدير عرض تقديمي [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). |
| [setSlidesLayoutOptions(ISlidesLayoutOptions value)](#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-) | يحصل أو يعيّن الوضع الذي تُوضع فيه الشرائح على الصفحة عند تصدير عرض تقديمي [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). |
| [getInkOptions()](#getInkOptions--) | يوفر خيارات تتحكم في مظهر كائنات الحبر في المستند المُصدّر. |

### getHtmlFormatter() {#getHtmlFormatter--}
```
public abstract IHtmlFormatter getHtmlFormatter()
```

يرجع أو يعيّن قالب HTML. Read/write [IHtmlFormatter](../../com.aspose.slides/ihtmlformatter).

**القيمة المرجعة:**
[IHtmlFormatter](../../com.aspose.slides/ihtmlformatter)
### setHtmlFormatter(IHtmlFormatter value) {#setHtmlFormatter-com.aspose.slides.IHtmlFormatter-}
```
public abstract void setHtmlFormatter(IHtmlFormatter value)
```

يرجع أو يعيّن قالب HTML. Read/write [IHtmlFormatter](../../com.aspose.slides/ihtmlformatter).

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | [IHtmlFormatter](../../com.aspose.slides/ihtmlformatter) |  |

### getSlideImageFormat() {#getSlideImageFormat--}
```
public abstract ISlideImageFormat getSlideImageFormat()
```

يرجع أو يعيّن خيارات تنسيق صورة الشريحة. Read/write [ISlideImageFormat](../../com.aspose.slides/islideimageformat).

**القيمة المرجعة:**
[ISlideImageFormat](../../com.aspose.slides/islideimageformat)
### setSlideImageFormat(ISlideImageFormat value) {#setSlideImageFormat-com.aspose.slides.ISlideImageFormat-}
```
public abstract void setSlideImageFormat(ISlideImageFormat value)
```

يرجع أو يعيّن خيارات تنسيق صورة الشريحة. Read/write [ISlideImageFormat](../../com.aspose.slides/islideimageformat).

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | [ISlideImageFormat](../../com.aspose.slides/islideimageformat) |  |

### getShowHiddenSlides() {#getShowHiddenSlides--}
```
public abstract boolean getShowHiddenSlides()
```

يحدد ما إذا كان المستند المُولَّد يجب أن يتضمن شرائح مخفية أم لا. القيمة الافتراضية هي false.

**القيمة المرجعة:**
boolean
### setShowHiddenSlides(boolean value) {#setShowHiddenSlides-boolean-}
```
public abstract void setShowHiddenSlides(boolean value)
```

يحدد ما إذا كان المستند المُولَّد يجب أن يتضمن شرائح مخفية أم لا. القيمة الافتراضية هي false.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getJpegQuality() {#getJpegQuality--}
```
public abstract byte getJpegQuality()
```

يرجع أو يعيّن قيمة تحدد جودة صور JPEG داخل مستند PDF. Read/write byte.

--------------------

له تأثير فقط عندما يحتوي المستند على صور JPEG.

استخدم هذه الخاصية للحصول على أو تعيين جودة الصور داخل المستند عند الحفظ بتنسيق PDF. قد تتراوح القيمة من 0 إلى 100 حيث 0 تعني أسوأ جودة لكن أقصى ضغط و100 تعني أفضل جودة لكن أقل ضغط.

القيمة الافتراضية هي **95**.

**القيمة المرجعة:**
byte
### setJpegQuality(byte value) {#setJpegQuality-byte-}
```
public abstract void setJpegQuality(byte value)
```

يرجع أو يعيّن قيمة تحدد جودة صور JPEG داخل مستند PDF. Read/write byte.

--------------------

له تأثير فقط عندما يحتوي المستند على صور JPEG.

استخدم هذه الخاصية للحصول على أو تعيين جودة الصور داخل المستند عند الحفظ بتنسيق PDF. قد تتراوح القيمة من 0 إلى 100 حيث 0 تعني أسوأ جودة لكن أقصى ضغط و100 تعني أفضل جودة لكن أقل ضغط.

القيمة الافتراضية هي **95**.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | byte |  |

### getPicturesCompression() {#getPicturesCompression--}
```
public abstract int getPicturesCompression()
```

يمثل مستوى ضغط الصور Read/write [PicturesCompression](../../com.aspose.slides/picturescompression)(\#getPicturesCompression.getPicturesCompression/\#setPicturesCompression(int).setPicturesCompression(int)).

**القيمة المرجعة:**
int
### setPicturesCompression(int value) {#setPicturesCompression-int-}
```
public abstract void setPicturesCompression(int value)
```

يمثل مستوى ضغط الصور Read/write [PicturesCompression](../../com.aspose.slides/picturescompression)(\#getPicturesCompression.getPicturesCompression/\#setPicturesCompression(int).setPicturesCompression(int)).

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getDeletePicturesCroppedAreas() {#getDeletePicturesCroppedAreas--}
```
public abstract boolean getDeletePicturesCroppedAreas()
```

علامة منطقية تشير إلى ما إذا كانت الأجزاء المقتطعة ستبقى كجزء من المستند. إذا كانت true سيتم إزالة الأجزاء المقتطعة، وإذا كانت false سيتم تسلسلها في المستند (مما قد يؤدي إلى ملف أكبر) Read/write boolean.

**القيمة المرجعة:**
boolean
### setDeletePicturesCroppedAreas(boolean value) {#setDeletePicturesCroppedAreas-boolean-}
```
public abstract void setDeletePicturesCroppedAreas(boolean value)
```

علامة منطقية تشير إلى ما إذا كانت الأجزاء المقتطعة ستبقى كجزء من المستند. إذا كانت true سيتم إزالة الأجزاء المقتطعة، وإذا كانت false سيتم تسلسلها في المستند (مما قد يؤدي إلى ملف أكبر) Read/write boolean.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getSvgResponsiveLayout() {#getSvgResponsiveLayout--}
```
public abstract boolean getSvgResponsiveLayout()
```

صحيح لاستبعاد سمات العرض والارتفاع من حاوية SVG - سيجعل ذلك التخطيط مستجيبًا. false - خلاف ذلك. Read/write boolean.

**القيمة المرجعة:**
boolean
### setSvgResponsiveLayout(boolean value) {#setSvgResponsiveLayout-boolean-}
```
public abstract void setSvgResponsiveLayout(boolean value)
```

صحيح لاستبعاد سمات العرض والارتفاع من حاوية SVG - سيجعل ذلك التخطيط مستجيبًا. false - خلاف ذلك. Read/write boolean.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getDisableFontLigatures() {#getDisableFontLigatures--}
```
public abstract boolean getDisableFontLigatures()
```

يحصل أو يعيّن قيمة تشير إلى ما إذا كان النص يُعرض دون استخدام الأحرف المربوطة. عند ضبطها على true، سيتم إلغاء تفعيل الأحرف المربوطة في المخرجات المعروضة. بشكل افتراضي، تكون هذه الخاصية مضبوطة على false.

--------------------

> ```
> مثال:
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


**القيمة المرجعة:**
boolean
### setDisableFontLigatures(boolean value) {#setDisableFontLigatures-boolean-}
```
public abstract void setDisableFontLigatures(boolean value)
```

يحصل أو يعيّن قيمة تشير إلى ما إذا كان النص يُعرض دون استخدام الأحرف المربوطة. عند ضبطها على true، سيتم إلغاء تفعيل الأحرف المربوطة في المخرجات المعروضة. بشكل افتراضي، تكون هذه الخاصية مضبوطة على false.

--------------------

> ```
> مثال:
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

يحصل أو يعيّن الوضع الذي تُوضع فيه الشرائح على الصفحة عند تصدير عرض تقديمي [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions).

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


**القيمة المرجعة:**
[ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions)
### setSlidesLayoutOptions(ISlidesLayoutOptions value) {#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-}
```
public abstract void setSlidesLayoutOptions(ISlidesLayoutOptions value)
```

يحصل أو يعيّن الوضع الذي تُوضع فيه الشرائح على الصفحة عند تصدير عرض تقديمي [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions).

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


**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions) |  |

### getInkOptions() {#getInkOptions--}
```
public abstract IInkOptions getInkOptions()
```

يوفر خيارات تتحكم في مظهر كائنات الحبر في المستند المُصدّر. Read-only [IInkOptions](../../com.aspose.slides/iinkoptions)

**القيمة المرجعة:**
[IInkOptions](../../com.aspose.slides/iinkoptions)