---
title: IImageTransformOperationCollection
second_title: Aspose.Slides لنظام Android عبر مرجع API لجافا
description: يمثل مجموعة من المؤثرات المطبقة على صورة.
type: docs
url: /ar/com.aspose.slides/iimagetransformoperationcollection/
---
**جميع الواجهات المنفذة:**
com.aspose.ms.System.Collections.Generic.IGenericCollection
```
public interface IImageTransformOperationCollection extends System.Collections.Generic.IGenericCollection<IImageTransformOperation>
```

يمثل مجموعة من المؤثرات المطبقة على صورة.

## الطرق

| الطريقة | الوصف |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | تُرجع [IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation) من المجموعة وفقًا لمؤشرها. |
| [removeAt(int index)](#removeAt-int-) | يزيل مؤثر صورة من مجموعة عند الفهرس المحدد. |
| [addAlphaBiLevelEffect(float threshold)](#addAlphaBiLevelEffect-float-) | يضيف مؤثر Alpha Bi-Level الجديد إلى نهاية مجموعة. |
| [addAlphaCeilingEffect()](#addAlphaCeilingEffect--) | يضيف مؤثر Alpha Ceiling الجديد إلى نهاية مجموعة. |
| [addAlphaFloorEffect()](#addAlphaFloorEffect--) | يضيف مؤثر Alpha Floor الجديد إلى نهاية مجموعة. |
| [addAlphaInverseEffect()](#addAlphaInverseEffect--) | يضيف مؤثر Alpha Inverse الجديد إلى نهاية مجموعة. |
| [addAlphaModulateEffect()](#addAlphaModulateEffect--) | يضيف مؤثر Alpha Modulate الجديد إلى نهاية مجموعة. |
| [addAlphaModulateFixedEffect(float amount)](#addAlphaModulateFixedEffect-float-) | يضيف مؤثر Alpha Modulate Fixed الجديد إلى نهاية مجموعة. |
| [addAlphaReplaceEffect(float alpha)](#addAlphaReplaceEffect-float-) | يضيف مؤثر Alpha Replace الجديد إلى نهاية مجموعة. |
| [addBiLevelEffect(float threshold)](#addBiLevelEffect-float-) | يضيف مؤثر Bi-Level (أسود/أبيض) الجديد إلى نهاية مجموعة. |
| [addBlurEffect(double radius, boolean grow)](#addBlurEffect-double-boolean-) | يضيف مؤثر Blur الجديد إلى نهاية مجموعة. |
| [addColorChangeEffect()](#addColorChangeEffect--) | يضيف مؤثر Color Change الجديد إلى نهاية مجموعة. |
| [addColorReplaceEffect()](#addColorReplaceEffect--) | يضيف مؤثر Color Replacement الجديد إلى نهاية مجموعة. |
| [addDuotoneEffect()](#addDuotoneEffect--) | يضيف مؤثر Duotone الجديد إلى نهاية مجموعة. |
| [addFillOverlayEffect()](#addFillOverlayEffect--) | يضيف مؤثر Fill Overlay الجديد إلى نهاية مجموعة. |
| [addGrayScaleEffect()](#addGrayScaleEffect--) | يضيف مؤثر Gray Scale الجديد إلى نهاية مجموعة. |
| [addHSLEffect(float hue, float saturation, float luminance)](#addHSLEffect-float-float-float-) | يضيف مؤثر Hue/Saturation/Luminance الجديد إلى نهاية مجموعة. |
| [addLuminanceEffect(float brightness, float contrast)](#addLuminanceEffect-float-float-) | يضيف مؤثر Luminance الجديد إلى نهاية مجموعة. |
| [addTintEffect(float hue, float amount)](#addTintEffect-float-float-) | يضيف مؤثر Tint الجديد إلى نهاية مجموعة. |
| [addBrightnessContrastEffect(float brightness, float contrast)](#addBrightnessContrastEffect-float-float-) | يضيف مؤثر BrightnessContrast الجديد إلى نهاية مجموعة. |

### get_Item(int index) {#get-Item-int-}
```
public abstract IImageTransformOperation get_Item(int index)
```

تُرجع [IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation) من المجموعة وفقًا لمؤشرها.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| index | int | فهرس العنصر. |

**القيمة المرجعة:**
[IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation) - كائن [IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation).

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

يزيل مؤثر صورة من مجموعة عند الفهرس المحدد.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| index | int | فهرس مؤثر الصورة الذي يجب حذفه. |

### addAlphaBiLevelEffect(float threshold) {#addAlphaBiLevelEffect-float-}
```
public abstract IAlphaBiLevel addAlphaBiLevelEffect(float threshold)
```

يضيف مؤثر Alpha Bi-Level الجديد إلى نهاية مجموعة.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| threshold | float | قيمة العتبة لمؤثر Alpha Bi-Level. |

**القيمة المرجعة:**
[IAlphaBiLevel](../../com.aspose.slides/ialphabilevel) - فهرس المؤثر الجديد في مجموعة.

### addAlphaCeilingEffect() {#addAlphaCeilingEffect--}
```
public abstract IAlphaCeiling addAlphaCeilingEffect()
```

يضيف مؤثر Alpha Ceiling الجديد إلى نهاية مجموعة.

**القيمة المرجعة:**
[IAlphaCeiling](../../com.aspose.slides/ialphaceiling) - فهرس المؤثر الجديد في مجموعة.

### addAlphaFloorEffect() {#addAlphaFloorEffect--}
```
public abstract IAlphaFloor addAlphaFloorEffect()
```

يضيف مؤثر Alpha Floor الجديد إلى نهاية مجموعة.

**القيمة المرجعة:**
[IAlphaFloor](../../com.aspose.slides/ialphafloor) - فهرس المؤثر الجديد في مجموعة.

### addAlphaInverseEffect() {#addAlphaInverseEffect--}
```
public abstract IAlphaInverse addAlphaInverseEffect()
```

يضيف مؤثر Alpha Inverse الجديد إلى نهاية مجموعة.

**القيمة المرجعة:**
[IAlphaInverse](../../com.aspose.slides/ialphainverse) - فهرس المؤثر الجديد في مجموعة.

### addAlphaModulateEffect() {#addAlphaModulateEffect--}
```
public abstract IAlphaModulate addAlphaModulateEffect()
```

يضيف مؤثر Alpha Modulate الجديد إلى نهاية مجموعة.

**القيمة المرجعة:**
[IAlphaModulate](../../com.aspose.slides/ialphamodulate) - فهرس المؤثر الجديد في مجموعة.

### addAlphaModulateFixedEffect(float amount) {#addAlphaModulateFixedEffect-float-}
```
public abstract IAlphaModulateFixed addAlphaModulateFixedEffect(float amount)
```

يضيف مؤثر Alpha Modulate Fixed الجديد إلى نهاية مجموعة.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| amount | float | النسبة المئوية لتعديل قيمة alpha. |

**القيمة المرجعة:**
[IAlphaModulateFixed](../../com.aspose.slides/ialphamodulatefixed) - فهرس المؤثر الجديد في مجموعة.

### addAlphaReplaceEffect(float alpha) {#addAlphaReplaceEffect-float-}
```
public abstract IAlphaReplace addAlphaReplaceEffect(float alpha)
```

يضيف مؤثر Alpha Replace الجديد إلى نهاية مجموعة.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| alpha | float | قيمة الشفافية الجديدة. |

**القيمة المرجعة:**
[IAlphaReplace](../../com.aspose.slides/ialphareplace) - فهرس المؤثر الجديد في مجموعة.

### addBiLevelEffect(float threshold) {#addBiLevelEffect-float-}
```
public abstract IBiLevel addBiLevelEffect(float threshold)
```

يضيف مؤثر Bi-Level (أسود/أبيض) الجديد إلى نهاية مجموعة.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| threshold | float | عتبة الإضاءة لمؤثر Bi-Level. القيم الأكبر أو المساوية للعتبة تتحول إلى أبيض. القيم الأقل من العتبة تتحول إلى أسود. |

**القيمة المرجعة:**
[IBiLevel](../../com.aspose.slides/ibilevel) - فهرس المؤثر الجديد في مجموعة.

### addBlurEffect(double radius, boolean grow) {#addBlurEffect-double-boolean-}
```
public abstract IBlur addBlurEffect(double radius, boolean grow)
```

يضيف مؤثر Blur الجديد إلى نهاية مجموعة.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| radius | double | نصف قطر التشويش. |
| grow | boolean | يحدد ما إذا كان يجب توسيع حدود الكائن نتيجة التشويش. true يعني توسيع الحدود، false يعني عدم توسيعها. |

**القيمة المرجعة:**
[IBlur](../../com.aspose.slides/iblur) - فهرس المؤثر الجديد في مجموعة.

### addColorChangeEffect() {#addColorChangeEffect--}
```
public abstract IColorChange addColorChangeEffect()
```

يضيف مؤثر Color Change الجديد إلى نهاية مجموعة.

**القيمة المرجعة:**
[IColorChange](../../com.aspose.slides/icolorchange) - فهرس المؤثر الجديد في مجموعة.

### addColorReplaceEffect() {#addColorReplaceEffect--}
```
public abstract IColorReplace addColorReplaceEffect()
```

يضيف مؤثر Color Replacement الجديد إلى نهاية مجموعة.

**القيمة المرجعة:**
[IColorReplace](../../com.aspose.slides/icolorreplace) - فهرس المؤثر الجديد في مجموعة.

### addDuotoneEffect() {#addDuotoneEffect--}
```
public abstract IDuotone addDuotoneEffect()
```

يضيف مؤثر Duotone الجديد إلى نهاية مجموعة.

**القيمة المرجعة:**
[IDuotone](../../com.aspose.slides/iduotone) - فهرس المؤثر الجديد في مجموعة.

### addFillOverlayEffect() {#addFillOverlayEffect--}
```
public abstract IFillOverlay addFillOverlayEffect()
```

يضيف مؤثر Fill Overlay الجديد إلى نهاية مجموعة.

**القيمة المرجعة:**
[IFillOverlay](../../com.aspose.slides/ifilloverlay) - فهرس المؤثر الجديد في مجموعة.

### addGrayScaleEffect() {#addGrayScaleEffect--}
```
public abstract IGrayScale addGrayScaleEffect()
```

يضيف مؤثر Gray Scale الجديد إلى نهاية مجموعة.

**القيمة المرجعة:**
[IGrayScale](../../com.aspose.slides/igrayscale) - فهرس المؤثر الجديد في مجموعة.

### addHSLEffect(float hue, float saturation, float luminance) {#addHSLEffect-float-float-float-}
```
public abstract IHSL addHSLEffect(float hue, float saturation, float luminance)
```

يضيف مؤثر Hue/Saturation/Luminance الجديد إلى نهاية مجموعة.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| hue | float | عدد الدرجات التي يتم تعديل الصبغة بها. |
| saturation | float | النسبة المئوية التي يتم تعديل التشبع بها. |
| luminance | float | النسبة المئوية التي يتم تعديل الإضاءة بها. |

**القيمة المرجعة:**
[IHSL](../../com.aspose.slides/ihsl) - فهرس المؤثر الجديد في مجموعة.

### addLuminanceEffect(float brightness, float contrast) {#addLuminanceEffect-float-float-}
```
public abstract ILuminance addLuminanceEffect(float brightness, float contrast)
```

يضيف مؤثر Luminance الجديد إلى نهاية مجموعة.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| brightness | float | النسبة المئوية لتغيير السطوع. |
| contrast | float | النسبة المئوية لتغيير التباين. |

**القيمة المرجعة:**
[ILuminance](../../com.aspose.slides/iluminance) - فهرس المؤثر الجديد في مجموعة.

### addTintEffect(float hue, float amount) {#addTintEffect-float-float-}
```
public abstract ITint addTintEffect(float hue, float amount)
```

يضيف مؤثر Tint الجديد إلى نهاية مجموعة.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| hue | float | الصبغة التي سيتم تعديل اللون نحوها. |
| amount | float | يحدد مقدار إزاحة قيمة اللون. |

**القيمة المرجعة:**
[ITint](../../com.aspose.slides/itint) - فهرس المؤثر الجديد في مجموعة.

### addBrightnessContrastEffect(float brightness, float contrast) {#addBrightnessContrastEffect-float-float-}
```
public abstract IBrightnessContrast addBrightnessContrastEffect(float brightness, float contrast)
```

يضيف مؤثر BrightnessContrast الجديد إلى نهاية مجموعة.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| brightness | float | النسبة المئوية لتغيير السطوع. |
| contrast | float | النسبة المئوية لتغيير التباين. |

**القيمة المرجعة:**
[IBrightnessContrast](../../com.aspose.slides/ibrightnesscontrast) - فهرس المؤثر الجديد في مجموعة.