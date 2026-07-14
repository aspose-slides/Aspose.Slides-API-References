---
title: SVGOptions
second_title: Aspose.Slides لنظام Android عبر مرجع API لجافا
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
## المُنشئات

| المنشئ | الوصف |
| --- | --- |
| [SVGOptions()](#SVGOptions--) | ينشئ نسخةً جديدةً من فئة SVGOptions. |
| [SVGOptions(ILinkEmbedController linkEmbedController)](#SVGOptions-com.aspose.slides.ILinkEmbedController-) | ينشئ نسخةً جديدةً من فئة SVGOptions مع تحديد كائن مراقب تضمين الروابط. |
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getInkOptions()](#getInkOptions--) | يوفر خيارات تتحكم في مظهر كائنات Ink في المستند المُصدر. |
| [getUseFrameSize()](#getUseFrameSize--) | يحدد ما إذا كان إطار النص سيُدرج في منطقة العرض أم لا. |
| [setUseFrameSize(boolean value)](#setUseFrameSize-boolean-) | يحدد ما إذا كان إطار النص سيُدرج في منطقة العرض أم لا. |
| [getUseFrameRotation()](#getUseFrameRotation--) | يحدد ما إذا كان سيتم تنفيذ الدوران المحدد للشكل أثناء العرض أم لا. |
| [setUseFrameRotation(boolean value)](#setUseFrameRotation-boolean-) | يحدد ما إذا كان سيتم تنفيذ الدوران المحدد للشكل أثناء العرض أم لا. |
| [getVectorizeText()](#getVectorizeText--) | يحدد ما إذا كان النص على الشريحة سيُحفظ كرسومات. |
| [setVectorizeText(boolean value)](#setVectorizeText-boolean-) | يحدد ما إذا كان النص على الشريحة سيُحفظ كرسومات. |
| [getMetafileRasterizationDpi()](#getMetafileRasterizationDpi--) | يرجع أو يضبط الحد الأدنى للدقة لتتبع صورة الميتافايل. |
| [setMetafileRasterizationDpi(int value)](#setMetafileRasterizationDpi-int-) | يرجع أو يضبط الحد الأدنى للدقة لتتبع صورة الميتافايل. |
| [getDisable3DText()](#getDisable3DText--) | يحدد ما إذا كان النص ثلاثي الأبعاد مُعطلًا في SVG. |
| [setDisable3DText(boolean value)](#setDisable3DText-boolean-) | يحدد ما إذا كان النص ثلاثي الأبعاد مُعطلًا في SVG. |
| [getDisableGradientSplit()](#getDisableGradientSplit--) | يعطل تقسيم التدرجات FromCornerX و FromCenter. |
| [setDisableGradientSplit(boolean value)](#setDisableGradientSplit-boolean-) | يعطل تقسيم التدرجات FromCornerX و FromCenter. |
| [getDisableLineEndCropping()](#getDisableLineEndCropping--) | SVG 1.1 يفتقر إلى القدرة على تعريف الهوامش للعلامات. |
| [setDisableLineEndCropping(boolean value)](#setDisableLineEndCropping-boolean-) | SVG 1.1 يفتقر إلى القدرة على تعريف الهوامش للعلامات. |
| [getDefault()](#getDefault--) | يرجع الإعدادات الافتراضية. |
| [getSimple()](#getSimple--) | يرجع الإعدادات لتوليد أصغر ملف SVG بسيط. |
| [getWYSIWYG()](#getWYSIWYG--) | يرجع الإعدادات لتوليد ملف SVG بأعلى دقة. |
| [getJpegQuality()](#getJpegQuality--) | يحدد جودة ترميز JPEG. |
| [setJpegQuality(int value)](#setJpegQuality-int-) | يحدد جودة ترميز JPEG. |
| [getShapeFormattingController()](#getShapeFormattingController--) | يرجع ويضبط واجهة رد نداء تسمح للمستخدم بالتحكم في تحويل الشكل. |
| [setShapeFormattingController(ISvgShapeFormattingController value)](#setShapeFormattingController-com.aspose.slides.ISvgShapeFormattingController-) | يرجع ويضبط واجهة رد نداء تسمح للمستخدم بالتحكم في تحويل الشكل. |
| [getPicturesCompression()](#getPicturesCompression--) | يمثل مستوى ضغط الصور |
| [setPicturesCompression(int value)](#setPicturesCompression-int-) | يمثل مستوى ضغط الصور |
| [getDeletePicturesCroppedAreas()](#getDeletePicturesCroppedAreas--) | علامة منطقية تشير إلى ما إذا كانت الأجزاء المقصوصة تظل جزءًا من المستند. |
| [setDeletePicturesCroppedAreas(boolean value)](#setDeletePicturesCroppedAreas-boolean-) | علامة منطقية تشير إلى ما إذا كانت الأجزاء المقصوصة تظل جزءًا من المستند. |
| [getExternalFontsHandling()](#getExternalFontsHandling--) | يحدد طريقة التعامل مع الخطوط المحملة خارجيًا. |
| [setExternalFontsHandling(int value)](#setExternalFontsHandling-int-) | يحدد طريقة التعامل مع الخطوط المحملة خارجيًا. |
| [getDisableFontLigatures()](#getDisableFontLigatures--) | يحصل أو يضبط قيمة تشير إلى ما إذا كان النص يُعرض دون استخدام الأحرف المتصلة. |
| [setDisableFontLigatures(boolean value)](#setDisableFontLigatures-boolean-) | يحصل أو يضبط قيمة تشير إلى ما إذا كان النص يُعرض دون استخدام الأحرف المتصلة. |

### SVGOptions() {#SVGOptions--}
```
public SVGOptions()
```

ينشئ نسخةً جديدةً من فئة SVGOptions.

### SVGOptions(ILinkEmbedController linkEmbedController) {#SVGOptions-com.aspose.slides.ILinkEmbedController-}
```
public SVGOptions(ILinkEmbedController linkEmbedController)
```

ينشئ نسخةً جديدةً من فئة SVGOptions مع تحديد كائن مراقب تضمين الروابط.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| linkEmbedController | [ILinkEmbedController](../../com.aspose.slides/ilinkembedcontroller) | مرجع مراقب تضمين الروابط.

--------------------

Link embedding controller is a delegate object that is responsible for making decisions if resources (such as images) need to be embedded or referenced as external resources. |

### getInkOptions() {#getInkOptions--}
```
public final IInkOptions getInkOptions()
```

يوفر خيارات تتحكم في مظهر كائنات Ink في المستند المُصدر. قراءة فقط [IInkOptions](../../com.aspose.slides/iinkoptions)

**الإرجاع:**
[IInkOptions](../../com.aspose.slides/iinkoptions)
### getUseFrameSize() {#getUseFrameSize--}
```
public final boolean getUseFrameSize()
```

يحدد ما إذا كان إطار النص سيُدرج في منطقة العرض أم لا. قراءة/كتابة منطقية. القيمة الافتراضية هي false.

**الإرجاع:**
boolean
### setUseFrameSize(boolean value) {#setUseFrameSize-boolean-}
```
public final void setUseFrameSize(boolean value)
```

يحدد ما إذا كان إطار النص سيُدرج في منطقة العرض أم لا. قراءة/كتابة منطقية. القيمة الافتراضية هي false.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getUseFrameRotation() {#getUseFrameRotation--}
```
public final boolean getUseFrameRotation()
```

يحدد ما إذا كان سيتم تنفيذ الدوران المحدد للشكل أثناء العرض أم لا. قراءة/كتابة منطقية. القيمة الافتراضية هي true.

**الإرجاع:**
boolean
### setUseFrameRotation(boolean value) {#setUseFrameRotation-boolean-}
```
public final void setUseFrameRotation(boolean value)
```

يحدد ما إذا كان سيتم تنفيذ الدوران المحدد للشكل أثناء العرض أم لا. قراءة/كتابة منطقية. القيمة الافتراضية هي true.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getVectorizeText() {#getVectorizeText--}
```
public final boolean getVectorizeText()
```

يحدد ما إذا كان النص على الشريحة سيُحفظ كرسومات. قراءة/كتابة منطقية.

**الإرجاع:**
boolean
### setVectorizeText(boolean value) {#setVectorizeText-boolean-}
```
public final void setVectorizeText(boolean value)
```

يحدد ما إذا كان النص على الشريحة سيُحفظ كرسومات. قراءة/كتابة منطقية.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getMetafileRasterizationDpi() {#getMetafileRasterizationDpi--}
```
public final int getMetafileRasterizationDpi()
```

يرجع أو يضبط الحد الأدنى للدقة لتتبع صورة الميتافايل. قراءة/كتابة عدد صحيح.

**الإرجاع:**
int
### setMetafileRasterizationDpi(int value) {#setMetafileRasterizationDpi-int-}
```
public final void setMetafileRasterizationDpi(int value)
```

يرجع أو يضبط الحد الأدنى للدقة لتتبع صورة الميتافايل. قراءة/كتابة عدد صحيح.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getDisable3DText() {#getDisable3DText--}
```
public final boolean getDisable3DText()
```

يحدد ما إذا كان النص ثلاثي الأبعاد مُعطلًا في SVG. قراءة/كتابة منطقية.

**الإرجاع:**
boolean
### setDisable3DText(boolean value) {#setDisable3DText-boolean-}
```
public final void setDisable3DText(boolean value)
```

يحدد ما إذا كان النص ثلاثي الأبعاد مُعطلًا في SVG. قراءة/كتابة منطقية.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getDisableGradientSplit() {#getDisableGradientSplit--}
```
public final boolean getDisableGradientSplit()
```

يعطل تقسيم التدرجات FromCornerX و FromCenter. قراءة/كتابة منطقية.

**الإرجاع:**
boolean
### setDisableGradientSplit(boolean value) {#setDisableGradientSplit-boolean-}
```
public final void setDisableGradientSplit(boolean value)
```

يعطل تقسيم التدرجات FromCornerX و FromCenter. قراءة/كتابة منطقية.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getDisableLineEndCropping() {#getDisableLineEndCropping--}
```
public final boolean getDisableLineEndCropping()
```

SVG 1.1 يفتقر إلى القدرة على تعريف الهوامش للعلامات. محرك كتابة SVG في Aspose.Slides لديه حل بديل لتلك المشكلة: يقوم بقص نهاية الخط مع السهم، بحيث لا يتداخل الخط مع العلامات. هذا الخيار يوقف هذا السلوك. قراءة/كتابة منطقية.

**الإرجاع:**
boolean
### setDisableLineEndCropping(boolean value) {#setDisableLineEndCropping-boolean-}
```
public final void setDisableLineEndCropping(boolean value)
```

SVG 1.1 يفتقر إلى القدرة على تعريف الهوامش للعلامات. محرك كتابة SVG في Aspose.Slides لديه حل بديل لتلك المشكلة: يقوم بقص نهاية الخط مع السهم، بحيث لا يتداخل الخط مع العلامات. هذا الخيار يوقف هذا السلوك. قراءة/كتابة منطقية.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getDefault() {#getDefault--}
```
public static SVGOptions getDefault()
```

يرجع الإعدادات الافتراضية. قراءة فقط [SVGOptions](../../com.aspose.slides/svgoptions).

**الإرجاع:**
[SVGOptions](../../com.aspose.slides/svgoptions)
### getSimple() {#getSimple--}
```
public static SVGOptions getSimple()
```

يرجع الإعدادات لتوليد أصغر ملف SVG بسيط. قراءة فقط [SVGOptions](../../com.aspose.slides/svgoptions).

**الإرجاع:**
[SVGOptions](../../com.aspose.slides/svgoptions)
### getWYSIWYG() {#getWYSIWYG--}
```
public static SVGOptions getWYSIWYG()
```

يرجع الإعدادات لتوليد ملف SVG بأعلى دقة. قراءة فقط [SVGOptions](../../com.aspose.slides/svgoptions).

**الإرجاع:**
[SVGOptions](../../com.aspose.slides/svgoptions)
### getJpegQuality() {#getJpegQuality--}
```
public final int getJpegQuality()
```

يحدد جودة ترميز JPEG. قراءة/كتابة عدد صحيح.

**الإرجاع:**
int
### setJpegQuality(int value) {#setJpegQuality-int-}
```
public final void setJpegQuality(int value)
```

يحدد جودة ترميز JPEG. قراءة/كتابة عدد صحيح.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getShapeFormattingController() {#getShapeFormattingController--}
```
public final ISvgShapeFormattingController getShapeFormattingController()
```

يرجع ويضبط واجهة رد نداء تسمح للمستخدم بالتحكم في تحويل الشكل. قراءة/كتابة [ISvgShapeFormattingController](../../com.aspose.slides/isvgshapeformattingcontroller).

**الإرجاع:**
[ISvgShapeFormattingController](../../com.aspose.slides/isvgshapeformattingcontroller)
### setShapeFormattingController(ISvgShapeFormattingController value) {#setShapeFormattingController-com.aspose.slides.ISvgShapeFormattingController-}
```
public final void setShapeFormattingController(ISvgShapeFormattingController value)
```

يرجع ويضبط واجهة رد نداء تسمح للمستخدم بالتحكم في تحويل الشكل. قراءة/كتابة [ISvgShapeFormattingController](../../com.aspose.slides/isvgshapeformattingcontroller).

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | [ISvgShapeFormattingController](../../com.aspose.slides/isvgshapeformattingcontroller) |  |

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
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getDeletePicturesCroppedAreas() {#getDeletePicturesCroppedAreas--}
```
public final boolean getDeletePicturesCroppedAreas()
```

علامة منطقية تشير إلى ما إذا كانت الأجزاء المقصوصة تظل جزءًا من المستند. إذا كانت true ستُزال الأجزاء المقصوصة، إذا كانت false سيتم تسلسلها في المستند (مما قد يؤدي إلى ملف أكبر)

**الإرجاع:**
boolean
### setDeletePicturesCroppedAreas(boolean value) {#setDeletePicturesCroppedAreas-boolean-}
```
public final void setDeletePicturesCroppedAreas(boolean value)
```

علامة منطقية تشير إلى ما إذا كانت الأجزاء المقصوصة تظل جزءًا من المستند. إذا كانت true ستُزال الأجزاء المقصوصة، إذا كانت false سيتم تسلسلها في المستند (مما قد يؤدي إلى ملف أكبر)

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getExternalFontsHandling() {#getExternalFontsHandling--}
```
public final int getExternalFontsHandling()
```

يحدد طريقة التعامل مع الخطوط المحملة خارجيًا. قراءة/كتابة [SvgExternalFontsHandling](../../com.aspose.slides/svgexternalfontshandling).

**الإرجاع:**
int
### setExternalFontsHandling(int value) {#setExternalFontsHandling-int-}
```
public final void setExternalFontsHandling(int value)
```

يحدد طريقة التعامل مع الخطوط المحملة خارجيًا. قراءة/كتابة [SvgExternalFontsHandling](../../com.aspose.slides/svgexternalfontshandling).

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getDisableFontLigatures() {#getDisableFontLigatures--}
```
public final boolean getDisableFontLigatures()
```

يحصل أو يضبط قيمة تشير إلى ما إذا كان النص يُعرض دون استخدام الأحرف المتصلة. عند الضبط إلى true، سيتم تعطيل الأحرف المتصلة في المخرجات المعروضة. بشكل افتراضي، هذه الخاصية مضبوطة على false.

--------------------

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

**الإرجاع:**
boolean
### setDisableFontLigatures(boolean value) {#setDisableFontLigatures-boolean-}
```
public final void setDisableFontLigatures(boolean value)
```

يحصل أو يضبط قيمة تشير إلى ما إذا كان النص يُعرض دون استخدام الأحرف المتصلة. عند الضبط إلى true، سيتم تعطيل الأحرف المتصلة في المخرجات المعروضة. بشكل افتراضي، هذه الخاصية مضبوطة على false.

--------------------

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
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |