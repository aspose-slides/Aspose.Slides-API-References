---
title: SVGOptions
second_title: Aspose.Slides للـ Java – مرجع API
description: يمثل خيارات SVG.
type: docs
url: /ar/com.aspose.slides/svgoptions/
---
**الوراثة:**  
java.lang.Object, [com.aspose.slides.SaveOptions](../../com.aspose.slides/saveoptions)

**جميع الواجهات المنفذة:**  
[com.aspose.slides.ISVGOptions](../../com.aspose.slides/isvgoptions), java.lang.Cloneable  
```
public final class SVGOptions extends SaveOptions implements ISVGOptions, Cloneable
```

يمثل خيارات SVG.

## البُنَاؤُ

| المنشئ | الوصف |
| --- | --- |
| [SVGOptions()](#SVGOptions--) | يَنشئ نسخة جديدة من فئة SVGOptions. |
| [SVGOptions(ILinkEmbedController linkEmbedController)](#SVGOptions-com.aspose.slides.ILinkEmbedController-) | يَنشئ نسخة جديدة من فئة SVGOptions مُحدِّدًا كائن وحدة تحكم تضمين الروابط. |

## الأساليب

| الطريقة | الوصف |
| --- | --- |
| [getInkOptions()](#getInkOptions--) | يُوفر خيارات تتحكم في مظهر كائنات الحبر في المستند المُصدَّر. |
| [getUseFrameSize()](#getUseFrameSize--) | يحدِّد ما إذا كان إطار النص سيُضمَّن في منطقة العرض أم لا. |
| [setUseFrameSize(boolean value)](#setUseFrameSize-boolean-) | يحدِّد ما إذا كان إطار النص سيُضمَّن في منطقة العرض أم لا. |
| [getUseFrameRotation()](#getUseFrameRotation--) | يحدِّد ما إذا كان سيتم تنفيذ الدوران المحدد للشكل عند العرض أم لا. |
| [setUseFrameRotation(boolean value)](#setUseFrameRotation-boolean-) | يحدِّد ما إذا كان سيتم تنفيذ الدوران المحدد للشكل عند العرض أم لا. |
| [getVectorizeText()](#getVectorizeText--) | يحدِّد ما إذا كان النص على الشريحة سيُحفظ كرسومات. |
| [setVectorizeText(boolean value)](#setVectorizeText-boolean-) | يحدِّد ما إذا كان النص على الشريحة سيُحفظ كرسومات. |
| [getMetafileRasterizationDpi()](#getMetafileRasterizationDpi--) | يَعيد أو يضبط الحد الأدنى للدقة لتصوير ملفات الميتا. |
| [setMetafileRasterizationDpi(int value)](#setMetafileRasterizationDpi-int-) | يَعيد أو يضبط الحد الأدنى للدقة لتصوير ملفات الميتا. |
| [getDisable3DText()](#getDisable3DText--) | يحدِّد ما إذا كان نص ثلاثي الأبعاد مُعطلًا في SVG. |
| [setDisable3DText(boolean value)](#setDisable3DText-boolean-) | يحدِّد ما إذا كان نص ثلاثي الأبعاد مُعطلًا في SVG. |
| [getDisableGradientSplit()](#getDisableGradientSplit--) | يعطل تقسيم التدرجات FromCornerX و FromCenter. |
| [setDisableGradientSplit(boolean value)](#setDisableGradientSplit-boolean-) | يعطل تقسيم التدرجات FromCornerX و FromCenter. |
| [getDisableLineEndCropping()](#getDisableLineEndCropping--) | تفتقر SVG 1.1 إلى القدرة على تعريف الهوامش للعلامات. |
| [setDisableLineEndCropping(boolean value)](#setDisableLineEndCropping-boolean-) | تفتقر SVG 1.1 إلى القدرة على تعريف الهوامش للعلامات. |
| [getDefault()](#getDefault--) | يَرجع الإعدادات الافتراضية. |
| [getSimple()](#getSimple--) | يَرجع الإعدادات لتوليد أصغر وأبسط ملف SVG. |
| [getWYSIWYG()](#getWYSIWYG--) | يَرجع الإعدادات لتوليد ملف SVG بأعلى دقة. |
| [getJpegQuality()](#getJpegQuality--) | يحدِّد جودة ترميز JPEG. |
| [setJpegQuality(int value)](#setJpegQuality-int-) | يحدِّد جودة ترميز JPEG. |
| [getShapeFormattingController()](#getShapeFormattingController--) | يَرجع ويضبط واجهة رد نداء تتيح للمستخدم التحكم في تحويل الشكل. |
| [setShapeFormattingController(ISvgShapeFormattingController value)](#setShapeFormattingController-com.aspose.slides.ISvgShapeFormattingController-) | يَرجع ويضبط واجهة رد نداء تتيح للمستخدم التحكم في تحويل الشكل. |
| [getPicturesCompression()](#getPicturesCompression--) | يُمثِّل مستوى ضغط الصور. |
| [setPicturesCompression(int value)](#setPicturesCompression-int-) | يُمثِّل مستوى ضغط الصور. |
| [getDeletePicturesCroppedAreas()](#getDeletePicturesCroppedAreas--) | علامة منطقية تُشير إلى ما إذا كانت الأجزاء المقتصّة ستبقى جزءًا من المستند. |
| [setDeletePicturesCroppedAreas(boolean value)](#setDeletePicturesCroppedAreas-boolean-) | علامة منطقية تُشير إلى ما إذا كانت الأجزاء المقتصّة ستبقى جزءًا من المستند. |
| [getExternalFontsHandling()](#getExternalFontsHandling--) | يحدِّد طريقة التعامل مع الخطوط المحمَّلة خارجيًا. |
| [setExternalFontsHandling(int value)](#setExternalFontsHandling-int-) | يحدِّد طريقة التعامل مع الخطوط المحمَّلة خارجيًا. |
| [getDisableFontLigatures()](#getDisableFontLigatures--) | يحصل أو يضبط قيمة تُشير إلى ما إذا كان النص يُعرض دون استخدام الارتباطات. |
| [setDisableFontLigatures(boolean value)](#setDisableFontLigatures-boolean-) | يحصل أو يضبط قيمة تُشير إلى ما إذا كان النص يُعرض دون استخدام الارتباطات. |

### SVGOptions() {#SVGOptions--}
```
public SVGOptions()
```

يُنشئ نسخة جديدة من فئة SVGOptions.

### SVGOptions(ILinkEmbedController linkEmbedController) {#SVGOptions-com.aspose.slides.ILinkEmbedController-}
```
public SVGOptions(ILinkEmbedController linkEmbedController)
```

يُنشئ نسخة جديدة من فئة SVGOptions مُحدِّدًا كائن وحدة تحكم تضمين الروابط.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| linkEmbedController | [ILinkEmbedController](../../com.aspose.slides/ilinkembedcontroller) | مرجع وحدة تحكم تضمين الروابط. |

--------------------

وحدة تحكم تضمين الروابط هي كائن تفويض مسؤول عن اتخاذ القرار ما إذا كانت الموارد (مثل الصور) تحتاج إلى تضمينها أو الإشارة إليها كموارد خارجية.

### getInkOptions() {#getInkOptions--}
```
public final IInkOptions getInkOptions()
```

يُوفر خيارات تتحكم في مظهر كائنات الحبر في المستند المُصدَّر. للقراءة فقط [IInkOptions](../../com.aspose.slides/iinkoptions)

**القيمة المرجعة:**
[IInkOptions](../../com.aspose.slides/iinkoptions)

### getUseFrameSize() {#getUseFrameSize--}
```
public final boolean getUseFrameSize()
```

يحدِّد ما إذا كان إطار النص سيُضمَّن في منطقة العرض أم لا. قراءة/كتابة boolean. القيمة الافتراضية هي false.

**القيمة المرجعة:**
boolean

### setUseFrameSize(boolean value) {#setUseFrameSize-boolean-}
```
public final void setUseFrameSize(boolean value)
```

يحدِّد ما إذا كان إطار النص سيُضمَّن في منطقة العرض أم لا. قراءة/كتابة boolean. القيمة الافتراضية هي false.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getUseFrameRotation() {#getUseFrameRotation--}
```
public final boolean getUseFrameRotation()
```

يحدِّد ما إذا كان سيتم تنفيذ الدوران المحدد للشكل عند العرض أم لا. قراءة/كتابة boolean. القيمة الافتراضية هي true.

**القيمة المرجعة:**
boolean

### setUseFrameRotation(boolean value) {#setUseFrameRotation-boolean-}
```
public final void setUseFrameRotation(boolean value)
```

يحدِّد ما إذا كان سيتم تنفيذ الدوران المحدد للشكل عند العرض أم لا. قراءة/كتابة boolean. القيمة الافتراضية هي true.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getVectorizeText() {#getVectorizeText--}
```
public final boolean getVectorizeText()
```

يحدِّد ما إذا كان النص على الشريحة سيُحفظ كرسومات. قراءة/كتابة boolean.

**القيمة المرجعة:**
boolean

### setVectorizeText(boolean value) {#setVectorizeText-boolean-}
```
public final void setVectorizeText(boolean value)
```

يحدِّد ما إذا كان النص على الشريحة سيُحفظ كرسومات. قراءة/كتابة boolean.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getMetafileRasterizationDpi() {#getMetafileRasterizationDpi--}
```
public final int getMetafileRasterizationDpi()
```

يَعيد أو يضبط الحد الأدنى للدقة لتصوير ملفات الميتا. قراءة/كتابة int.

**القيمة المرجعة:**
int

### setMetafileRasterizationDpi(int value) {#setMetafileRasterizationDpi-int-}
```
public final void setMetafileRasterizationDpi(int value)
```

يَعيد أو يضبط الحد الأدنى للدقة لتصوير ملفات الميتا. قراءة/كتابة int.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getDisable3DText() {#getDisable3DText--}
```
public final boolean getDisable3DText()
```

يحدِّد ما إذا كان نص ثلاثي الأبعاد مُعطلًا في SVG. قراءة/كتابة boolean.

**القيمة المرجعة:**
boolean

### setDisable3DText(boolean value) {#setDisable3DText-boolean-}
```
public final void setDisable3DText(boolean value)
```

يحدِّد ما إذا كان نص ثلاثي الأبعاد مُعطلًا في SVG. قراءة/كتابة boolean.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getDisableGradientSplit() {#getDisableGradientSplit--}
```
public final boolean getDisableGradientSplit()
```

يعطل تقسيم التدرجات FromCornerX و FromCenter. قراءة/كتابة boolean.

**القيمة المرجعة:**
boolean

### setDisableGradientSplit(boolean value) {#setDisableGradientSplit-boolean-}
```
public final void setDisableGradientSplit(boolean value)
```

يعطل تقسيم التدرجات FromCornerX و FromCenter. قراءة/كتابة boolean.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getDisableLineEndCropping() {#getDisableLineEndCropping--}
```
public final boolean getDisableLineEndCropping()
```

تفتقر SVG 1.1 إلى القدرة على تعريف الهوامش للعلامات. محرك كتابة SVG في Aspose.Slides لديه حل بديل لهذه المشكلة: يقتص نهاية الخط بالسهم، لذا لا يتقاطع الخط مع العلامات. هذا الخيار يعطّل هذا السلوك. قراءة/كتابة boolean.

**القيمة المرجعة:**
boolean

### setDisableLineEndCropping(boolean value) {#setDisableLineEndCropping-boolean-}
```
public final void setDisableLineEndCropping(boolean value)
```

تفتقر SVG 1.1 إلى القدرة على تعريف الهوامش للعلامات. محرك كتابة SVG في Aspose.Slides لديه حل بديل لهذه المشكلة: يقتص نهاية الخط بالسهم، لذا لا يتقاطع الخط مع العلامات. هذا الخيار يعطّل هذا السلوك. قراءة/كتابة boolean.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getDefault() {#getDefault--}
```
public static SVGOptions getDefault()
```

يرجع الإعدادات الافتراضية. للقراءة فقط [SVGOptions](../../com.aspose.slides/svgoptions).

**القيمة المرجعة:**
[SVGOptions](../../com.aspose.slides/svgoptions)

### getSimple() {#getSimple--}
```
public static SVGOptions getSimple()
```

يرجع الإعدادات لتوليد أصغر وأبسط ملف SVG. للقراءة فقط [SVGOptions](../../com.aspose.slides/svgoptions).

**القيمة المرجعة:**
[SVGOptions](../../com.aspose.slides/svgoptions)

### getWYSIWYG() {#getWYSIWYG--}
```
public static SVGOptions getWYSIWYG()
```

يرجع الإعدادات لتوليد ملف SVG بأعلى دقة. للقراءة فقط [SVGOptions](../../com.aspose.slides/svgoptions).

**القيمة المرجعة:**
[SVGOptions](../../com.aspose.slides/svgoptions)

### getJpegQuality() {#getJpegQuality--}
```
public final int getJpegQuality()
```

يحدِّد جودة ترميز JPEG. قراءة/كتابة int.

**القيمة المرجعة:**
int

### setJpegQuality(int value) {#setJpegQuality-int-}
```
public final void setJpegQuality(int value)
```

يحدِّد جودة ترميز JPEG. قراءة/كتابة int.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getShapeFormattingController() {#getShapeFormattingController--}
```
public final ISvgShapeFormattingController getShapeFormattingController()
```

يَرجع ويضبط واجهة رد نداء تتيح للمستخدم التحكم في تحويل الشكل. قراءة/كتابة [ISvgShapeFormattingController](../../com.aspose.slides/isvgshapeformattingcontroller).

**القيمة المرجعة:**
[ISvgShapeFormattingController](../../com.aspose.slides/isvgshapeformattingcontroller)

### setShapeFormattingController(ISvgShapeFormattingController value) {#setShapeFormattingController-com.aspose.slides.ISvgShapeFormattingController-}
```
public final void setShapeFormattingController(ISvgShapeFormattingController value)
```

يَرجع ويضبط واجهة رد نداء تتيح للمستخدم التحكم في تحويل الشكل. قراءة/كتابة [ISvgShapeFormattingController](../../com.aspose.slides/isvgshapeformattingcontroller).

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | [ISvgShapeFormattingController](../../com.aspose.slides/isvgshapeformattingcontroller) |  |

### getPicturesCompression() {#getPicturesCompression--}
```
public final int getPicturesCompression()
```

يمثل مستوى ضغط الصور

**القيمة المرجعة:**
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

علامة منطقية تُشير إلى ما إذا كانت الأجزاء المقتصّة ستبقى جزءًا من المستند. إذا كان true ستُحذف الأجزاء المقتصّة، وإذا كان false ستُسلسَل في المستند (مما قد يؤدي إلى ملف أكبر).

**القيمة المرجعة:**
boolean

### setDeletePicturesCroppedAreas(boolean value) {#setDeletePicturesCroppedAreas-boolean-}
```
public final void setDeletePicturesCroppedAreas(boolean value)
```

علامة منطقية تُشير إلى ما إذا كانت الأجزاء المقتصّة ستبقى جزءًا من المستند. إذا كان true ستُحذف الأجزاء المقتصّة، وإذا كان false ستُسلسَل في المستند (مما قد يؤدي إلى ملف أكبر).

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getExternalFontsHandling() {#getExternalFontsHandling--}
```
public final int getExternalFontsHandling()
```

يحدِّد طريقة التعامل مع الخطوط المحمَّلة خارجيًا. قراءة/كتابة [SvgExternalFontsHandling](../../com.aspose.slides/svgexternalfontshandling).

**القيمة المرجعة:**
int

### setExternalFontsHandling(int value) {#setExternalFontsHandling-int-}
```
public final void setExternalFontsHandling(int value)
```

يحدِّد طريقة التعامل مع الخطوط المحمَّلة خارجيًا. قراءة/كتابة [SvgExternalFontsHandling](../../com.aspose.slides/svgexternalfontshandling).

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getDisableFontLigatures() {#getDisableFontLigatures--}
```
public final boolean getDisableFontLigatures()
```

يحصل أو يضبط قيمة تُشير إلى ما إذا كان النص يُعرض دون استخدام الارتباطات. عندما تُضبط على true، سيتم تعطيل الارتباطات في المخرجات المُعروضة. بشكل افتراضي، تُضبط هذه الخاصية على false.

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      SVGOptions options = new SVGOptions();
>      options.setDisableFontLigatures(true);
> 
>      FileOutputStream fileStream = new FileOutputStream("slide-0.svg");
>      pres.getSlides().get_Item(0).writeAsSvg(fileStream);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**القيمة المرجعة:**
boolean

### setDisableFontLigatures(boolean value) {#setDisableFontLigatures-boolean-}
```
public final void setDisableFontLigatures(boolean value)
```

يحصل أو يضبط قيمة تُشير إلى ما إذا كان النص يُعرض دون استخدام الارتباطات. عندما تُضبط على true، سيتم تعطيل الارتباطات في المخرجات المُعروضة. بشكل افتراضي، تُضبط هذه الخاصية على false.

> ```
> مثال:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      SVGOptions options = new SVGOptions();
>      options.setDisableFontLigatures(true);
> 
>      FileOutputStream fileStream = new FileOutputStream("slide-0.svg");
>      pres.getSlides().get_Item(0).writeAsSvg(fileStream);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |