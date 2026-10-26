---
title: ISVGOptions
second_title: مرجع Aspose.Slides للـ Java API
description: يمثل خيارات SVG.
type: docs
url: /ar/com.aspose.slides/isvgoptions/
---
**جميع الواجهات المنفذة:**
[com.aspose.slides.ISaveOptions](../../com.aspose.slides/isaveoptions)
```
public interface ISVGOptions extends ISaveOptions
```

يمثل خيارات SVG.
## الأساليب

| الطريقة | الوصف |
| --- | --- |
| [getVectorizeText()](#getVectorizeText--) | يحدد ما إذا كان النص على الشريحة سيُحفظ كرسومات. |
| [setVectorizeText(boolean value)](#setVectorizeText-boolean-) | يحدد ما إذا كان النص على الشريحة سيُحفظ كرسومات. |
| [getMetafileRasterizationDpi()](#getMetafileRasterizationDpi--) | يرجع أو يحدد الحد الأدنى لدقة تحويل ملفات الميتافايل إلى نقطية. |
| [setMetafileRasterizationDpi(int value)](#setMetafileRasterizationDpi-int-) | يرجع أو يحدد الحد الأدنى لدقة تحويل ملفات الميتافايل إلى نقطية. |
| [getDisable3DText()](#getDisable3DText--) | يحدد ما إذا كان النص ثلاثي الأبعاد معطلًا في SVG. |
| [setDisable3DText(boolean value)](#setDisable3DText-boolean-) | يحدد ما إذا كان النص ثلاثي الأبعاد معطلًا في SVG. |
| [getDisableGradientSplit()](#getDisableGradientSplit--) | يعطل تقسيم التدرجات FromCornerX و FromCenter. |
| [setDisableGradientSplit(boolean value)](#setDisableGradientSplit-boolean-) | يعطل تقسيم التدرجات FromCornerX و FromCenter. |
| [getDisableLineEndCropping()](#getDisableLineEndCropping--) | لا يدعم SVG 1.1 القدرة على تعريف الهوامش للعلامات. |
| [setDisableLineEndCropping(boolean value)](#setDisableLineEndCropping-boolean-) | لا يدعم SVG 1.1 القدرة على تعريف الهوامش للعلامات. |
| [getJpegQuality()](#getJpegQuality--) | يحدد جودة ترميز JPEG. |
| [setJpegQuality(int value)](#setJpegQuality-int-) | يحدد جودة ترميز JPEG. |
| [getShapeFormattingController()](#getShapeFormattingController--) | يرجع ويضبط واجهة رد النداء التي تسمح للمستخدم بالتحكم في تحويل الشكل. |
| [setShapeFormattingController(ISvgShapeFormattingController value)](#setShapeFormattingController-com.aspose.slides.ISvgShapeFormattingController-) | يرجع ويضبط واجهة رد النداء التي تسمح للمستخدم بالتحكم في تحويل الشكل. |
| [getPicturesCompression()](#getPicturesCompression--) | يمثل مستوى ضغط الصور قراءة/كتابة \#getPicturesCompression.getPicturesCompression/\#setPicturesCompression(int).setPicturesCompression(int). |
| [setPicturesCompression(int value)](#setPicturesCompression-int-) | يمثل مستوى ضغط الصور قراءة/كتابة \#getPicturesCompression.getPicturesCompression/\#setPicturesCompression(int).setPicturesCompression(int). |
| [getDeletePicturesCroppedAreas()](#getDeletePicturesCroppedAreas--) | علم منطقي يشير إلى ما إذا كانت الأجزاء المقصوصة تبقى كجزء من المستند. |
| [setDeletePicturesCroppedAreas(boolean value)](#setDeletePicturesCroppedAreas-boolean-) | علم منطقي يشير إلى ما إذا كانت الأجزاء المقصوصة تبقى كجزء من المستند. |
| [getUseFrameSize()](#getUseFrameSize--) | يحدد ما إذا كان إطار النص سيُضمّن في مساحة العرض أم لا. |
| [setUseFrameSize(boolean value)](#setUseFrameSize-boolean-) | يحدد ما إذا كان إطار النص سيُضمّن في مساحة العرض أم لا. |
| [getUseFrameRotation()](#getUseFrameRotation--) | يحدد ما إذا كان سيتم تنفيذ الدوران المحدد للشكل عند العرض أم لا. |
| [setUseFrameRotation(boolean value)](#setUseFrameRotation-boolean-) | يحدد ما إذا كان سيتم تنفيذ الدوران المحدد للشكل عند العرض أم لا. |
| [getExternalFontsHandling()](#getExternalFontsHandling--) | يحدد طريقة التعامل مع الخطوط المحمّلة خارجياً. |
| [setExternalFontsHandling(int value)](#setExternalFontsHandling-int-) | يحدد طريقة التعامل مع الخطوط المحمّلة خارجياً. |
| [getInkOptions()](#getInkOptions--) | يوفر خيارات تتحكم في مظهر كائنات الحبر في المستند المصدَّر. |
| [getDisableFontLigatures()](#getDisableFontLigatures--) | يحصل أو يضبط قيمة تشير إلى ما إذا كان النص يُعرض بدون استعمال الأحرف المتصلة. |
| [setDisableFontLigatures(boolean value)](#setDisableFontLigatures-boolean-) | يحصل أو يضبط قيمة تشير إلى ما إذا كان النص يُعرض بدون استعمال الأحرف المتصلة. |

### getVectorizeText() {#getVectorizeText--}
```
public abstract boolean getVectorizeText()
```

يحدد ما إذا كان النص على الشريحة سيُحفظ كرسومات. قراءة/كتابة منطقي.

**الإرجاع:**
boolean

### setVectorizeText(boolean value) {#setVectorizeText-boolean-}
```
public abstract void setVectorizeText(boolean value)
```

يحدد ما إذا كان النص على الشريحة سيُحفظ كرسومات. قراءة/كتابة منطقي.

**الوسائط:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getMetafileRasterizationDpi() {#getMetafileRasterizationDpi--}
```
public abstract int getMetafileRasterizationDpi()
```

يرجع أو يحدد الحد الأدنى لدقة تحويل ملفات الميتافايل إلى نقطية. قراءة/كتابة int.

**الإرجاع:**
int

### setMetafileRasterizationDpi(int value) {#setMetafileRasterizationDpi-int-}
```
public abstract void setMetafileRasterizationDpi(int value)
```

يرجع أو يحدد الحد الأدنى لدقة تحويل ملفات الميتافايل إلى نقطية. قراءة/كتابة int.

**الوسائط:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getDisable3DText() {#getDisable3DText--}
```
public abstract boolean getDisable3DText()
```

يحدد ما إذا كان النص ثلاثي الأبعاد معطلًا في SVG. قراءة/كتابة منطقي.

**الإرجاع:**
boolean

### setDisable3DText(boolean value) {#setDisable3DText-boolean-}
```
public abstract void setDisable3DText(boolean value)
```

يحدد ما إذا كان النص ثلاثي الأبعاد معطلًا في SVG. قراءة/كتابة منطقي.

**الوسائط:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getDisableGradientSplit() {#getDisableGradientSplit--}
```
public abstract boolean getDisableGradientSplit()
```

يعطل تقسيم التدرجات FromCornerX و FromCenter. قراءة/كتابة منطقي.

**الإرجاع:**
boolean

### setDisableGradientSplit(boolean value) {#setDisableGradientSplit-boolean-}
```
public abstract void setDisableGradientSplit(boolean value)
```

يعطل تقسيم التدرجات FromCornerX و FromCenter. قراءة/كتابة منطقي.

**الوسائط:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getDisableLineEndCropping() {#getDisableLineEndCropping--}
```
public abstract boolean getDisableLineEndCropping()
```

لا يدعم SVG 1.1 القدرة على تعريف الهوامش للعلامات. محرك كتابة SVG في Aspose.Slides لديه حل بديل لهذه المشكلة: يقتطع نهاية الخط مع السهم، لذا لا يتقاطع الخط مع العلامات. هذا الخيار يوقف هذا السلوك. قراءة/كتابة منطقي.

**الإرجاع:**
boolean

### setDisableLineEndCropping(boolean value) {#setDisableLineEndCropping-boolean-}
```
public abstract void setDisableLineEndCropping(boolean value)
```

لا يدعم SVG 1.1 القدرة على تعريف الهوامش للعلامات. محرك كتابة SVG في Aspose.Slides لديه حل بديل لهذه المشكلة: يقتطع نهاية الخط مع السهم، لذا لا يتقاطع الخط مع العلامات. هذا الخيار يوقف هذا السلوك. قراءة/كتابة منطقي.

**الوسائط:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getJpegQuality() {#getJpegQuality--}
```
public abstract int getJpegQuality()
```

يحدد جودة ترميز JPEG. قراءة/كتابة int.

**الإرجاع:**
int

### setJpegQuality(int value) {#setJpegQuality-int-}
```
public abstract void setJpegQuality(int value)
```

يحدد جودة ترميز JPEG. قراءة/كتابة int.

**الوسائط:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getShapeFormattingController() {#getShapeFormattingController--}
```
public abstract ISvgShapeFormattingController getShapeFormattingController()
```

يرجع ويضبط واجهة رد النداء التي تسمح للمستخدم بالتحكم في تحويل الشكل. قراءة/كتابة [ISvgShapeFormattingController](../../com.aspose.slides/isvgshapeformattingcontroller).

**الإرجاع:**
[ISvgShapeFormattingController](../../com.aspose.slides/isvgshapeformattingcontroller)

### setShapeFormattingController(ISvgShapeFormattingController value) {#setShapeFormattingController-com.aspose.slides.ISvgShapeFormattingController-}
```
public abstract void setShapeFormattingController(ISvgShapeFormattingController value)
```

يرجع ويضبط واجهة رد النداء التي تسمح للمستخدم بالتحكم في تحويل الشكل. قراءة/كتابة [ISvgShapeFormattingController](../../com.aspose.slides/isvgshapeformattingcontroller).

**الوسائط:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | [ISvgShapeFormattingController](../../com.aspose.slides/isvgshapeformattingcontroller) |  |

### getPicturesCompression() {#getPicturesCompression--}
```
public abstract int getPicturesCompression()
```

يمثل مستوى ضغط الصور قراءة/كتابة \#getPicturesCompression.getPicturesCompression/\#setPicturesCompression(int).setPicturesCompression(int).

**الإرجاع:**
int

### setPicturesCompression(int value) {#setPicturesCompression-int-}
```
public abstract void setPicturesCompression(int value)
```

يمثل مستوى ضغط الصور قراءة/كتابة \#getPicturesCompression.getPicturesCompression/\#setPicturesCompression(int).setPicturesCompression(int).

**الوسائط:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getDeletePicturesCroppedAreas() {#getDeletePicturesCroppedAreas--}
```
public abstract boolean getDeletePicturesCroppedAreas()
```

علم منطقي يشير إلى ما إذا كانت الأجزاء المقصوصة تبقى كجزء من المستند. إذا كان true ستُحذف الأجزاء المقصوصة، إذا كان false ستُسلسِل في المستند (مما قد يؤدي إلى ملف أكبر). قراءة/كتابة منطقي.

**الإرجاع:**
boolean

### setDeletePicturesCroppedAreas(boolean value) {#setDeletePicturesCroppedAreas-boolean-}
```
public abstract void setDeletePicturesCroppedAreas(boolean value)
```

علم منطقي يشير إلى ما إذا كانت الأجزاء المقصوصة تبقى كجزء من المستند. إذا كان true ستُحذف الأجزاء المقصوصة، إذا كان false ستُسلسِل في المستند (مما قد يؤدي إلى ملف أكبر). قراءة/كتابة منطقي.

**الوسائط:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getUseFrameSize() {#getUseFrameSize--}
```
public abstract boolean getUseFrameSize()
```

يحدد ما إذا كان إطار النص سيُضمّن في مساحة العرض أم لا. قراءة/كتابة  منطقي . القيمة الافتراضية هي false.

**الإرجاع:**
boolean

### setUseFrameSize(boolean value) {#setUseFrameSize-boolean-}
```
public abstract void setUseFrameSize(boolean value)
```

يحدد ما إذا كان إطار النص سيُضمّن في مساحة العرض أم لا. قراءة/كتابة  منطقي . القيمة الافتراضية هي false.

**الوسائط:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getUseFrameRotation() {#getUseFrameRotation--}
```
public abstract boolean getUseFrameRotation()
```

يحدد ما إذا كان سيتم تنفيذ الدوران المحدد للشكل عند العرض أم لا. قراءة/كتابة  منطقي . القيمة الافتراضية هي true.

**الإرجاع:**
boolean

### setUseFrameRotation(boolean value) {#setUseFrameRotation-boolean-}
```
public abstract void setUseFrameRotation(boolean value)
```

يحدد ما إذا كان سيتم تنفيذ الدوران المحدد للشكل عند العرض أم لا. قراءة/كتابة  منطقي . القيمة الافتراضية هي true.

**الوسائط:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getExternalFontsHandling() {#getExternalFontsHandling--}
```
public abstract int getExternalFontsHandling()
```

يحدد طريقة التعامل مع الخطوط المحمّلة خارجياً. قراءة/كتابة [SvgExternalFontsHandling](../../com.aspose.slides/svgexternalfontshandling).

**الإرجاع:**
int

### setExternalFontsHandling(int value) {#setExternalFontsHandling-int-}
```
public abstract void setExternalFontsHandling(int value)
```

يحدد طريقة التعامل مع الخطوط المحمّلة خارجياً. قراءة/كتابة [SvgExternalFontsHandling](../../com.aspose.slides/svgexternalfontshandling).

**الوسائط:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getInkOptions() {#getInkOptions--}
```
public abstract IInkOptions getInkOptions()
```

يوفر خيارات تتحكم في مظهر كائنات الحبر في المستند المصدَّر. قراءة فقط [IInkOptions](../../com.aspose.slides/iinkoptions)

**الإرجاع:**
[IInkOptions](../../com.aspose.slides/iinkoptions)

### getDisableFontLigatures() {#getDisableFontLigatures--}
```
public abstract boolean getDisableFontLigatures()
```

يحصل أو يضبط قيمة تشير إلى ما إذا كان النص يُعرض بدون استعمال الأحرف المتصلة. عند الضبط إلى true، ستُعطل الأحرف المتصلة في الناتج المعروض. بشكل افتراضي، هذه الخاصية مضبوطة على false.

--------------------

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


**الإرجاع:**
boolean

### setDisableFontLigatures(boolean value) {#setDisableFontLigatures-boolean-}
```
public abstract void setDisableFontLigatures(boolean value)
```

يحصل أو يضبط قيمة تشير إلى ما إذا كان النص يُعرض بدون استعمال الأحرف المتصلة. عند الضبط إلى true، ستُعطل الأحرف المتصلة في الناتج المعروض. بشكل افتراضي، هذه الخاصية مضبوطة على false.

--------------------

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


**الوسائط:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |