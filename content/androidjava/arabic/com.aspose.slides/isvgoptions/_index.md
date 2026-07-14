---
title: ISVGOptions
second_title: Aspose.Slides لنظام Android عبر مرجع API Java
description: يمثل خيارات SVG.
type: docs
url: /ar/com.aspose.slides/isvgoptions/
---
**جميع الواجهات المُنفذة:**
[com.aspose.slides.ISaveOptions](../../com.aspose.slides/isaveoptions)
```
public interface ISVGOptions extends ISaveOptions
```

يمثل خيارات SVG.
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getVectorizeText()](#getVectorizeText--) | يحدد ما إذا كان سيتم حفظ النص على الشريحة كرسومات. |
| [setVectorizeText(boolean value)](#setVectorizeText-boolean-) | يحدد ما إذا كان سيتم حفظ النص على الشريحة كرسومات. |
| [getMetafileRasterizationDpi()](#getMetafileRasterizationDpi--) | يرجع أو يضبط الحد الأدنى لدقة تصيير ملف الميتا. |
| [setMetafileRasterizationDpi(int value)](#setMetafileRasterizationDpi-int-) | يرجع أو يضبط الحد الأدنى لدقة تصيير ملف الميتا. |
| [getDisable3DText()](#getDisable3DText--) | يحدد ما إذا كان نص ثلاثي الأبعاد معطلًا في SVG. |
| [setDisable3DText(boolean value)](#setDisable3DText-boolean-) | يحدد ما إذا كان نص ثلاثي الأبعاد معطلًا في SVG. |
| [getDisableGradientSplit()](#getDisableGradientSplit--) | يعطل تقسيم التدرجات FromCornerX و FromCenter. |
| [setDisableGradientSplit(boolean value)](#setDisableGradientSplit-boolean-) | يعطل تقسيم التدرجات FromCornerX و FromCenter. |
| [getDisableLineEndCropping()](#getDisableLineEndCropping--) | لا تدعم SVG 1.1 إمكانية تعريف الهوامش للعلامات. |
| [setDisableLineEndCropping(boolean value)](#setDisableLineEndCropping-boolean-) | لا تدعم SVG 1.1 إمكانية تعريف الهوامش للعلامات. |
| [getJpegQuality()](#getJpegQuality--) | يحدد جودة ترميز JPEG. |
| [setJpegQuality(int value)](#setJpegQuality-int-) | يحدد جودة ترميز JPEG. |
| [getShapeFormattingController()](#getShapeFormattingController--) | يرجع ويضبط واجهة رد الاتصال التي تسمح للمستخدم بالتحكم في تحويل الشكل. |
| [setShapeFormattingController(ISvgShapeFormattingController value)](#setShapeFormattingController-com.aspose.slides.ISvgShapeFormattingController-) | يرجع ويضبط واجهة رد الاتصال التي تسمح للمستخدم بالتحكم في تحويل الشكل. |
| [getPicturesCompression()](#getPicturesCompression--) | يمثل مستوى ضغط الصور قابل للقراءة والكتابة \#getPicturesCompression.getPicturesCompression/\#setPicturesCompression(int).setPicturesCompression(int). |
| [setPicturesCompression(int value)](#setPicturesCompression-int-) | يمثل مستوى ضغط الصور قابل للقراءة والكتابة \#getPicturesCompression.getPicturesCompression/\#setPicturesCompression(int).setPicturesCompression(int). |
| [getDeletePicturesCroppedAreas()](#getDeletePicturesCroppedAreas--) | علامة منطقية تشير إلى ما إذا كانت الأجزاء المقصوصة تبقى كجزء من المستند. |
| [setDeletePicturesCroppedAreas(boolean value)](#setDeletePicturesCroppedAreas-boolean-) | علامة منطقية تشير إلى ما إذا كانت الأجزاء المقصوصة تبقى كجزء من المستند. |
| [getUseFrameSize()](#getUseFrameSize--) | يحدد ما إذا كان إطار النص سيُدرج في منطقة التصيير أم لا. |
| [setUseFrameSize(boolean value)](#setUseFrameSize-boolean-) | يحدد ما إذا كان إطار النص سيُدرج في منطقة التصيير أم لا. |
| [getUseFrameRotation()](#getUseFrameRotation--) | يحدد ما إذا كان سيتم تنفيذ الدوران المحدد للشكل عند التصيير أم لا. |
| [setUseFrameRotation(boolean value)](#setUseFrameRotation-boolean-) | يحدد ما إذا كان سيتم تنفيذ الدوران المحدد للشكل عند التصيير أم لا. |
| [getExternalFontsHandling()](#getExternalFontsHandling--) | يحدد طريقة التعامل مع الخطوط المحملة خارجيًا. |
| [setExternalFontsHandling(int value)](#setExternalFontsHandling-int-) | يحدد طريقة التعامل مع الخطوط المحملة خارجيًا. |
| [getInkOptions()](#getInkOptions--) | يوفر خيارات تتحكم في مظهر كائنات الحبر في المستند المُصدّر. |
| [getDisableFontLigatures()](#getDisableFontLigatures--) | يحصل أو يضبط قيمة تشير إلى ما إذا كان النص يُصَنع دون استخدام التحام الحروف. |
| [setDisableFontLigatures(boolean value)](#setDisableFontLigatures-boolean-) | يحصل أو يضبط قيمة تشير إلى ما إذا كان النص يُصَنع دون استخدام التحام الحروف. |
### getVectorizeText() {#getVectorizeText--}
```
public abstract boolean getVectorizeText()
```

يحدد ما إذا كان سيتم حفظ النص على الشريحة كرسومات. قابل للقراءة والكتابة boolean.

**القيمة المرجعة:**  
boolean
### setVectorizeText(boolean value) {#setVectorizeText-boolean-}
```
public abstract void setVectorizeText(boolean value)
```

يحدد ما إذا كان سيتم حفظ النص على الشريحة كرسومات. قابل للقراءة والكتابة boolean.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |
### getMetafileRasterizationDpi() {#getMetafileRasterizationDpi--}
```
public abstract int getMetafileRasterizationDpi()
```

يرجع أو يضبط الحد الأدنى لدقة تصيير ملف الميتا. قابل للقراءة والكتابة int.

**القيمة المرجعة:**  
int
### setMetafileRasterizationDpi(int value) {#setMetafileRasterizationDpi-int-}
```
public abstract void setMetafileRasterizationDpi(int value)
```

يرجع أو يضبط الحد الأدنى لدقة تصيير ملف الميتا. قابل للقراءة والكتابة int.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | int |  |
### getDisable3DText() {#getDisable3DText--}
```
public abstract boolean getDisable3DText()
```

يحدد ما إذا كان نص ثلاثي الأبعاد معطلًا في SVG. قابل للقراءة والكتابة boolean.

**القيمة المرجعة:**  
boolean
### setDisable3DText(boolean value) {#setDisable3DText-boolean-}
```
public abstract void setDisable3DText(boolean value)
```

يحدد ما إذا كان نص ثلاثي الأبعاد معطلًا في SVG. قابل للقراءة والكتابة boolean.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |
### getDisableGradientSplit() {#getDisableGradientSplit--}
```
public abstract boolean getDisableGradientSplit()
```

يعطل تقسيم التدرجات FromCornerX و FromCenter. قابل للقراءة والكتابة boolean.

**القيمة المرجعة:**  
boolean
### setDisableGradientSplit(boolean value) {#setDisableGradientSplit-boolean-}
```
public abstract void setDisableGradientSplit(boolean value)
```

يعطل تقسيم التدرجات FromCornerX و FromCenter. قابل للقراءة والكتابة boolean.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |
### getDisableLineEndCropping() {#getDisableLineEndCropping--}
```
public abstract boolean getDisableLineEndCropping()
```

لا تدعم SVG 1.1 إمكانية تعريف الهوامش للعلامات. محرك كتابة SVG في Aspose.Slides يحتوي على حل لهذه المشكلة: يقتطع نهاية الخط مع السهم، بحيث لا يتقاطع الخط مع العلامات. هذا الخيار يوقف هذا السلوك. قابل للقراءة والكتابة boolean.

**القيمة المرجعة:**  
boolean
### setDisableLineEndCropping(boolean value) {#setDisableLineEndCropping-boolean-}
```
public abstract void setDisableLineEndCropping(boolean value)
```

لا تدعم SVG 1.1 إمكانية تعريف الهوامش للعلامات. محرك كتابة SVG في Aspose.Slides يحتوي على حل لهذه المشكلة: يقتطع نهاية الخط مع السهم، بحيث لا يتقاطع الخط مع العلامات. هذا الخيار يوقف هذا السلوك. قابل للقراءة والكتابة boolean.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |
### getJpegQuality() {#getJpegQuality--}
```
public abstract int getJpegQuality()
```

يحدد جودة ترميز JPEG. قابل للقراءة والكتابة int.

**القيمة المرجعة:**  
int
### setJpegQuality(int value) {#setJpegQuality-int-}
```
public abstract void setJpegQuality(int value)
```

يحدد جودة ترميز JPEG. قابل للقراءة والكتابة int.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | int |  |
### getShapeFormattingController() {#getShapeFormattingController--}
```
public abstract ISvgShapeFormattingController getShapeFormattingController()
```

يرجع ويضبط واجهة رد الاتصال التي تسمح للمستخدم بالتحكم في تحويل الشكل. قابل للقراءة والكتابة [ISvgShapeFormattingController](../../com.aspose.slides/isvgshapeformattingcontroller).

**القيمة المرجعة:**  
[ISvgShapeFormattingController](../../com.aspose.slides/isvgshapeformattingcontroller)
### setShapeFormattingController(ISvgShapeFormattingController value) {#setShapeFormattingController-com.aspose.slides.ISvgShapeFormattingController-}
```
public abstract void setShapeFormattingController(ISvgShapeFormattingController value)
```

يرجع ويضبط واجهة رد الاتصال التي تسمح للمستخدم بالتحكم في تحويل الشكل. قابل للقراءة والكتابة [ISvgShapeFormattingController](../../com.aspose.slides/isvgshapeformattingcontroller).

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | [ISvgShapeFormattingController](../../com.aspose.slides/isvgshapeformattingcontroller) |  |
### getPicturesCompression() {#getPicturesCompression--}
```
public abstract int getPicturesCompression()
```

يمثل مستوى ضغط الصور قابل للقراءة والكتابة \#getPicturesCompression.getPicturesCompression/\#setPicturesCompression(int).setPicturesCompression(int).

**القيمة المرجعة:**  
int
### setPicturesCompression(int value) {#setPicturesCompression-int-}
```
public abstract void setPicturesCompression(int value)
```

يمثل مستوى ضغط الصور قابل للقراءة والكتابة \#getPicturesCompression.getPicturesCompression/\#setPicturesCompression(int).setPicturesCompression(int).

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | int |  |
### getDeletePicturesCroppedAreas() {#getDeletePicturesCroppedAreas--}
```
public abstract boolean getDeletePicturesCroppedAreas()
```

علامة منطقية تشير إلى ما إذا كانت الأجزاء المقصوصة تبقى كجزء من المستند. إذا كان true ستُزال الأجزاء المقصوصة، وإذا كان false سيُسجلون في المستند (مما قد يؤدي إلى ملف أكبر) قابل للقراءة والكتابة boolean.

**القيمة المرجعة:**  
boolean
### setDeletePicturesCroppedAreas(boolean value) {#setDeletePicturesCroppedAreas-boolean-}
```
public abstract void setDeletePicturesCroppedAreas(boolean value)
```

علامة منطقية تشير إلى ما إذا كانت الأجزاء المقصوصة تبقى كجزء من المستند. إذا كان true ستُزال الأجزاء المقصوصة، وإذا كان false سيُسجلون في المستند (مما قد يؤدي إلى ملف أكبر) قابل للقراءة والكتابة boolean.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |
### getUseFrameSize() {#getUseFrameSize--}
```
public abstract boolean getUseFrameSize()
```

يحدد ما إذا كان إطار النص سيُدرج في منطقة التصيير أم لا. قابل للقراءة والكتابة boolean. القيمة الافتراضية هي false.

**القيمة المرجعة:**  
boolean
### setUseFrameSize(boolean value) {#setUseFrameSize-boolean-}
```
public abstract void setUseFrameSize(boolean value)
```

يحدد ما إذا كان إطار النص سيُدرج في منطقة التصيير أم لا. قابل للقراءة والكتابة boolean. القيمة الافتراضية هي false.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |
### getUseFrameRotation() {#getUseFrameRotation--}
```
public abstract boolean getUseFrameRotation()
```

يحدد ما إذا كان سيتم تنفيذ الدوران المحدد للشكل عند التصيير أم لا. قابل للقراءة والكتابة boolean. القيمة الافتراضية هي true.

**القيمة المرجعة:**  
boolean
### setUseFrameRotation(boolean value) {#setUseFrameRotation-boolean-}
```
public abstract void setUseFrameRotation(boolean value)
```

يحدد ما إذا كان سيتم تنفيذ الدوران المحدد للشكل عند التصيير أم لا. قابل للقراءة والكتابة boolean. القيمة الافتراضية هي true.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |
### getExternalFontsHandling() {#getExternalFontsHandling--}
```
public abstract int getExternalFontsHandling()
```

يحدد طريقة التعامل مع الخطوط المحملة خارجيًا. قابل للقراءة والكتابة [SvgExternalFontsHandling](../../com.aspose.slides/svgexternalfontshandling).

**القيمة المرجعة:**  
int
### setExternalFontsHandling(int value) {#setExternalFontsHandling-int-}
```
public abstract void setExternalFontsHandling(int value)
```

يحدد طريقة التعامل مع الخطوط المحملة خارجيًا. قابل للقراءة والكتابة [SvgExternalFontsHandling](../../com.aspose.slides/svgexternalfontshandling).

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | int |  |
### getInkOptions() {#getInkOptions--}
```
public abstract IInkOptions getInkOptions()
```

يوفر خيارات تتحكم في مظهر كائنات الحبر في المستند المُصدّر. للقراءة فقط [IInkOptions](../../com.aspose.slides/iinkoptions)

**القيمة المرجعة:**  
[IInkOptions](../../com.aspose.slides/iinkoptions)
### getDisableFontLigatures() {#getDisableFontLigatures--}
```
public abstract boolean getDisableFontLigatures()
```

يحصل أو يضبط قيمة تشير إلى ما إذا كان النص يُصَنع دون استخدام التحام الحروف. عند تعيينه إلى true، سيتم تعطيل التحام الحروف في الناتج المُصَنع. بشكل افتراضي، يتم تعيين هذه الخاصية إلى false.

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

**القيمة المرجعة:**  
boolean
### setDisableFontLigatures(boolean value) {#setDisableFontLigatures-boolean-}
```
public abstract void setDisableFontLigatures(boolean value)
```

يحصل أو يضبط قيمة تشير إلى ما إذا كان النص يُصَنع دون استخدام التحام الحروف. عند تعيينه إلى true، سيتم تعطيل التحام الحروف في الناتج المُصَنع. بشكل افتراضي، يتم تعيين هذه الخاصية إلى false.

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