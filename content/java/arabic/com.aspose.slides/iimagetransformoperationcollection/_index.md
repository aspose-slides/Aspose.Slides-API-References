---
title: IImageTransformOperationCollection
second_title: مرجع API Aspose.Slides for Java
description: يمثل مجموعة من التأثيرات المطبقة على صورة.
type: docs
url: /ar/com.aspose.slides/iimagetransformoperationcollection/
---
**جميع الواجهات المنفذة:**
com.aspose.ms.System.Collections.Generic.IGenericCollection
```
public interface IImageTransformOperationCollection extends System.Collections.Generic.IGenericCollection<IImageTransformOperation>
```

يمثل مجموعة من التأثيرات المطبقة على صورة.
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | يرجع [IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation) من المجموعة حسب فهرسه. |
| [removeAt(int index)](#removeAt-int-) | يزيل تأثير صورة من مجموعة عند الفهرس المحدد. |
| [addAlphaBiLevelEffect(float threshold)](#addAlphaBiLevelEffect-float-) | يضيف تأثير Alpha Bi-Level الجديد إلى نهاية مجموعة. |
| [addAlphaCeilingEffect()](#addAlphaCeilingEffect--) | يضيف تأثير Alpha Ceiling الجديد إلى نهاية مجموعة. |
| [addAlphaFloorEffect()](#addAlphaFloorEffect--) | يضيف تأثير Alpha Floor الجديد إلى نهاية مجموعة. |
| [addAlphaInverseEffect()](#addAlphaInverseEffect--) | يضيف تأثير Alpha Inverse الجديد إلى نهاية مجموعة. |
| [addAlphaModulateEffect()](#addAlphaModulateEffect--) | يضيف تأثير Alpha Modulate الجديد إلى نهاية مجموعة. |
| [addAlphaModulateFixedEffect(float amount)](#addAlphaModulateFixedEffect-float-) | يضيف تأثير Alpha Modulate Fixed الجديد إلى نهاية مجموعة. |
| [addAlphaReplaceEffect(float alpha)](#addAlphaReplaceEffect-float-) | يضيف تأثير Alpha Replace الجديد إلى نهاية مجموعة. |
| [addBiLevelEffect(float threshold)](#addBiLevelEffect-float-) | يضيف تأثير Bi-Level (black/white) الجديد إلى نهاية مجموعة. |
| [addBlurEffect(double radius, boolean grow)](#addBlurEffect-double-boolean-) | يضيف تأثير Blur الجديد إلى نهاية مجموعة. |
| [addColorChangeEffect()](#addColorChangeEffect--) | يضيف تأثير Color Change الجديد إلى نهاية مجموعة. |
| [addColorReplaceEffect()](#addColorReplaceEffect--) | يضيف تأثير Color Replacement الجديد إلى نهاية مجموعة. |
| [addDuotoneEffect()](#addDuotoneEffect--) | يضيف تأثير Duotone الجديد إلى نهاية مجموعة. |
| [addFillOverlayEffect()](#addFillOverlayEffect--) | يضيف تأثير Fill Overlay الجديد إلى نهاية مجموعة. |
| [addGrayScaleEffect()](#addGrayScaleEffect--) | يضيف تأثير Gray Scale الجديد إلى نهاية مجموعة. |
| [addHSLEffect(float hue, float saturation, float luminance)](#addHSLEffect-float-float-float-) | يضيف تأثير Hue/Saturation/Luminance الجديد إلى نهاية مجموعة. |
| [addLuminanceEffect(float brightness, float contrast)](#addLuminanceEffect-float-float-) | يضيف تأثير Luminance الجديد إلى نهاية مجموعة. |
| [addTintEffect(float hue, float amount)](#addTintEffect-float-float-) | يضيف تأثير Tint الجديد إلى نهاية مجموعة. |
| [addBrightnessContrastEffect(float brightness, float contrast)](#addBrightnessContrastEffect-float-float-) | يضيف تأثير BrightnessContrast الجديد إلى نهاية مجموعة. |

### get_Item(int index) {#get-Item-int-}
```
public abstract IImageTransformOperation get_Item(int index)
```

يرجع [IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation) من المجموعة حسب فهرسه.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| index | int | فهرس العنصر. |

**الإرجاع:**
[IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation) - كائن [IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation)

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

يزيل تأثير صورة من مجموعة عند الفهرس المحدد.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| index | int | فهرس تأثير صورة يجب حذفه. |

### addAlphaBiLevelEffect(float threshold) {#addAlphaBiLevelEffect-float-}
```
public abstract IAlphaBiLevel addAlphaBiLevelEffect(float threshold)
```

يضيف تأثير Alpha Bi-Level الجديد إلى نهاية مجموعة.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| threshold | float | قيمة العتبة لتأثير alpha bi-level. |

**الإرجاع:**
[IAlphaBiLevel](../../com.aspose.slides/ialphabilevel) - فهرس تأثير الصورة الجديد في مجموعة.

### addAlphaCeilingEffect() {#addAlphaCeilingEffect--}
```
public abstract IAlphaCeiling addAlphaCeilingEffect()
```

يضيف تأثير Alpha Ceiling الجديد إلى نهاية مجموعة.

**الإرجاع:**
[IAlphaCeiling](../../com.aspose.slides/ialphaceiling) - فهرس تأثير الصورة الجديد في مجموعة.

### addAlphaFloorEffect() {#addAlphaFloorEffect--}
```
public abstract IAlphaFloor addAlphaFloorEffect()
```

يضيف تأثير Alpha Floor الجديد إلى نهاية مجموعة.

**الإرجاع:**
[IAlphaFloor](../../com.aspose.slides/ialphafloor) - فهرس تأثير الصورة الجديد في مجموعة.

### addAlphaInverseEffect() {#addAlphaInverseEffect--}
```
public abstract IAlphaInverse addAlphaInverseEffect()
```

يضيف تأثير Alpha Inverse الجديد إلى نهاية مجموعة.

**الإرجاع:**
[IAlphaInverse](../../com.aspose.slides/ialphainverse) - فهرس تأثير الصورة الجديد في مجموعة.

### addAlphaModulateEffect() {#addAlphaModulateEffect--}
```
public abstract IAlphaModulate addAlphaModulateEffect()
```

يضيف تأثير Alpha Modulate الجديد إلى نهاية مجموعة.

**الإرجاع:**
[IAlphaModulate](../../com.aspose.slides/ialphamodulate) - فهرس تأثير الصورة الجديد في مجموعة.

### addAlphaModulateFixedEffect(float amount) {#addAlphaModulateFixedEffect-float-}
```
public abstract IAlphaModulateFixed addAlphaModulateFixedEffect(float amount)
```

يضيف تأثير Alpha Modulate Fixed الجديد إلى نهاية مجموعة.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| amount | float | النسبة المئوية لتعديل قيمة alpha. |

**الإرجاع:**
[IAlphaModulateFixed](../../com.aspose.slides/ialphamodulatefixed) - فهرس تأثير الصورة الجديد في مجموعة.

### addAlphaReplaceEffect(float alpha) {#addAlphaReplaceEffect-float-}
```
public abstract IAlphaReplace addAlphaReplaceEffect(float alpha)
```

يضيف تأثير Alpha Replace الجديد إلى نهاية مجموعة.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| alpha | float | قيمة الشفافية الجديدة. |

**الإرجاع:**
[IAlphaReplace](../../com.aspose.slides/ialphareplace) - فهرس تأثير الصورة الجديد في مجموعة.

### addBiLevelEffect(float threshold) {#addBiLevelEffect-float-}
```
public abstract IBiLevel addBiLevelEffect(float threshold)
```

يضيف تأثير Bi-Level (black/white) الجديد إلى نهاية مجموعة.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| threshold | float | عتبة الإضاءة لتأثير Bi-Level. القيم التي تكون أكبر أو مساوية للعتبة تُضبط إلى الأبيض. القيم الأقل من العتبة تُضبط إلى الأسود. |

**الإرجاع:**
[IBiLevel](../../com.aspose.slides/ibilevel) - فهرس تأثير الصورة الجديد في مجموعة.

### addBlurEffect(double radius, boolean grow) {#addBlurEffect-double-boolean-}
```
public abstract IBlur addBlurEffect(double radius, boolean grow)
```

يضيف تأثير Blur الجديد إلى نهاية مجموعة.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| radius | double | نصف قطر الضبابية. |
| grow | boolean | يحدد ما إذا كان يجب توسيع حدود الكائن نتيجة الضبابية. true يعني توسيع الحدود بينما false يعني عدم توسيعها. |

**الإرجاع:**
[IBlur](../../com.aspose.slides/iblur) - فهرس تأثير الصورة الجديد في مجموعة.

### addColorChangeEffect() {#addColorChangeEffect--}
```
public abstract IColorChange addColorChangeEffect()
```

يضيف تأثير Color Change الجديد إلى نهاية مجموعة.

**الإرجاع:**
[IColorChange](../../com.aspose.slides/icolorchange) - فهرس تأثير الصورة الجديد في مجموعة.

### addColorReplaceEffect() {#addColorReplaceEffect--}
```
public abstract IColorReplace addColorReplaceEffect()
```

يضيف تأثير Color Replacement الجديد إلى نهاية مجموعة.

**الإرجاع:**
[IColorReplace](../../com.aspose.slides/icolorreplace) - فهرس تأثير الصورة الجديد في مجموعة.

### addDuotoneEffect() {#addDuotoneEffect--}
```
public abstract IDuotone addDuotoneEffect()
```

يضيف تأثير Duotone الجديد إلى نهاية مجموعة.

**الإرجاع:**
[IDuotone](../../com.aspose.slides/iduotone) - فهرس تأثير الصورة الجديد في مجموعة.

### addFillOverlayEffect() {#addFillOverlayEffect--}
```
public abstract IFillOverlay addFillOverlayEffect()
```

يضيف تأثير Fill Overlay الجديد إلى نهاية مجموعة.

**الإرجاع:**
[IFillOverlay](../../com.aspose.slides/ifilloverlay) - فهرس تأثير الصورة الجديد في مجموعة.

### addGrayScaleEffect() {#addGrayScaleEffect--}
```
public abstract IGrayScale addGrayScaleEffect()
```

يضيف تأثير Gray Scale الجديد إلى نهاية مجموعة.

**الإرجاع:**
[IGrayScale](../../com.aspose.slides/igrayscale) - فهرس تأثير الصورة الجديد في مجموعة.

### addHSLEffect(float hue, float saturation, float luminance) {#addHSLEffect-float-float-float-}
```
public abstract IHSL addHSLEffect(float hue, float saturation, float luminance)
```

يضيف تأثير Hue/Saturation/Luminance الجديد إلى نهاية مجموعة.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| hue | float | عدد الدرجات التي يتم تعديل الصبغة بها. |
| saturation | float | النسبة المئوية التي يتم تعديل التشبع بها. |
| luminance | float | النسبة المئوية التي يتم تعديل الإضاءة بها. |

**الإرجاع:**
[IHSL](../../com.aspose.slides/ihsl) - فهرس تأثير الصورة الجديد في مجموعة.

### addLuminanceEffect(float brightness, float contrast) {#addLuminanceEffect-float-float-}
```
public abstract ILuminance addLuminanceEffect(float brightness, float contrast)
```

يضيف تأثير Luminance الجديد إلى نهاية مجموعة.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| brightness | float | النسبة المئوية لتغيير السطوع. |
| contrast | float | النسبة المئوية لتغيير التباين. |

**الإرجاع:**
[ILuminance](../../com.aspose.slides/iluminance) - فهرس تأثير الصورة الجديد في مجموعة.

### addTintEffect(float hue, float amount) {#addTintEffect-float-float-}
```
public abstract ITint addTintEffect(float hue, float amount)
```

يضيف تأثير Tint الجديد إلى نهاية مجموعة.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| hue | float | الصبغة التي يُضاف اللون إليها. |
| amount | float | يحدد مقدار إزاحة قيمة اللون. |

**الإرجاع:**
[ITint](../../com.aspose.slides/itint) - فهرس تأثير الصورة الجديد في مجموعة.

### addBrightnessContrastEffect(float brightness, float contrast) {#addBrightnessContrastEffect-float-float-}
```
public abstract IBrightnessContrast addBrightnessContrastEffect(float brightness, float contrast)
```

يضيف تأثير BrightnessContrast الجديد إلى نهاية مجموعة.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| brightness | float | النسبة المئوية لتغيير السطوع. |
| contrast | float | النسبة المئوية لتغيير التباين. |

**الإرجاع:**
[IBrightnessContrast](../../com.aspose.slides/ibrightnesscontrast) - فهرس تأثير الصورة الجديد في مجموعة.