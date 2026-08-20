---
title: ImageTransformOperationCollection
second_title: مرجع API لـ Aspose.Slides للغة Java
description: يمثل مجموعة من التأثيرات المطبقة على صورة.
type: docs
url: /ar/com.aspose.slides/imagetransformoperationcollection/
---
**الوراثة:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**جميع الواجهات المُنفذة:**
[com.aspose.slides.IImageTransformOperationCollection](../../com.aspose.slides/iimagetransformoperationcollection)
```
public final class ImageTransformOperationCollection extends PVIObject implements IImageTransformOperationCollection
```

يمثل مجموعة من التأثيرات المطبقة على صورة.
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [get_Item(int index)](#get-Item-int-) | يعيد [ImageTransformOperation](../../com.aspose.slides/imagetransformoperation) من المجموعة وفقًا لفهرسه. |
| [removeAt(int index)](#removeAt-int-) | يزيل تأثير صورة من مجموعة في الفهرس المحدد. |
| [addAlphaBiLevelEffect(float threshold)](#addAlphaBiLevelEffect-float-) | يضيف تأثير Alpha Bi-Level الجديد إلى نهاية المجموعة. |
| [addAlphaCeilingEffect()](#addAlphaCeilingEffect--) | يضيف تأثير Alpha Ceiling الجديد إلى نهاية المجموعة. |
| [addAlphaFloorEffect()](#addAlphaFloorEffect--) | يضيف تأثير Alpha Floor الجديد إلى نهاية المجموعة. |
| [addAlphaInverseEffect()](#addAlphaInverseEffect--) | يضيف تأثير Alpha Inverse الجديد إلى نهاية المجموعة. |
| [addAlphaModulateEffect()](#addAlphaModulateEffect--) | يضيف تأثير Alpha Modulate الجديد إلى نهاية المجموعة. |
| [addAlphaModulateFixedEffect(float amount)](#addAlphaModulateFixedEffect-float-) | يضيف تأثير Alpha Modulate Fixed الجديد إلى نهاية المجموعة. |
| [addAlphaReplaceEffect(float alpha)](#addAlphaReplaceEffect-float-) | يضيف تأثير Alpha Replace الجديد إلى نهاية المجموعة. |
| [addBiLevelEffect(float threshold)](#addBiLevelEffect-float-) | يضيف تأثير Bi-Level (أسود/أبيض) الجديد إلى نهاية المجموعة. |
| [addBlurEffect(double radius, boolean grow)](#addBlurEffect-double-boolean-) | يضيف تأثير Blur الجديد إلى نهاية المجموعة. |
| [addColorChangeEffect()](#addColorChangeEffect--) | يضيف تأثير Color Change الجديد إلى نهاية المجموعة. |
| [addColorReplaceEffect()](#addColorReplaceEffect--) | يضيف تأثير Color Replacement الجديد إلى نهاية المجموعة. |
| [addDuotoneEffect()](#addDuotoneEffect--) | يضيف تأثير Duotone الجديد إلى نهاية المجموعة. |
| [addFillOverlayEffect()](#addFillOverlayEffect--) | يضيف تأثير Fill Overlay الجديد إلى نهاية المجموعة. |
| [addGrayScaleEffect()](#addGrayScaleEffect--) | يضيف تأثير Gray Scale الجديد إلى نهاية المجموعة. |
| [addHSLEffect(float hue, float saturation, float luminance)](#addHSLEffect-float-float-float-) | يضيف تأثير Hue/Saturation/Luminance الجديد إلى نهاية المجموعة. |
| [addLuminanceEffect(float brightness, float contrast)](#addLuminanceEffect-float-float-) | يضيف تأثير Luminance الجديد إلى نهاية المجموعة. |
| [addTintEffect(float hue, float amount)](#addTintEffect-float-float-) | يضيف تأثير Tint الجديد إلى نهاية المجموعة. |
| [addBrightnessContrastEffect(float brightness, float contrast)](#addBrightnessContrastEffect-float-float-) | يضيف تأثير BrightnessContrast الجديد إلى نهاية المجموعة. |
| [size()](#size--) | يعيد عدد تأثيرات الصورة في مجموعة. |
| [isReadOnly()](#isReadOnly--) | يحصل على قيمة تشير إلى ما إذا كان [IGenericCollection](../../com.aspose.slides/igenericcollection) قراءة فقط. |
| [addItem(IImageTransformOperation operation)](#addItem-com.aspose.slides.IImageTransformOperation-) | يضيف تأثير الصورة الجديد إلى نهاية مجموعة. |
| [clear()](#clear--) | يزيل جميع تأثيرات الصورة من مجموعة. |
| [containsItem(IImageTransformOperation item)](#containsItem-com.aspose.slides.IImageTransformOperation-) | يحدد ما إذا كان [IGenericCollection](../../com.aspose.slides/igenericcollection) يحتوي على قيمة معينة. |
| [copyToTArray(IImageTransformOperation[] array, int arrayIndex)](#copyToTArray-com.aspose.slides.IImageTransformOperation---int-) | ينسخ عناصر [IGenericCollection](../../com.aspose.slides/igenericcollection) إلى مصفوفة، بدءًا من فهرس مصفوفة معين. |
| [removeItem(IImageTransformOperation item)](#removeItem-com.aspose.slides.IImageTransformOperation-) | يزيل أول حدوث لكائن محدد من [IGenericCollection](../../com.aspose.slides/igenericcollection). |
| [iterator()](#iterator--) | يعيد كيانًا يكرر عبر المجموعة. |
| [iteratorJava()](#iteratorJava--) | يعيد مكرر جافا للمجموعة بأكملها. |
### getVersion() {#getVersion--}
```
public long getVersion()
```

الإصدار. قراءة فقط long.

**الإرجاع:**
long
### get_Item(int index) {#get-Item-int-}
```
public final IImageTransformOperation get_Item(int index)
```

يعيد [ImageTransformOperation](../../com.aspose.slides/imagetransformoperation) من المجموعة وفقًا لفهرسه.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| index | int | فهرس العنصر. |

**الإرجاع:**
[IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation) - كائن [IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation).
### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

يزيل تأثير صورة من مجموعة في الفهرس المحدد.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| index | int | فهرس تأثير الصورة الذي يجب حذفه. |
### addAlphaBiLevelEffect(float threshold) {#addAlphaBiLevelEffect-float-}
```
public final IAlphaBiLevel addAlphaBiLevelEffect(float threshold)
```

يضيف تأثير Alpha Bi-Level الجديد إلى نهاية مجموعة.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| threshold | float | قيمة العتبة لتأثير Alpha Bi-Level. |

**الإرجاع:**
[IAlphaBiLevel](../../com.aspose.slides/ialphabilevel) - فهرس تأثير الصورة الجديد في مجموعة.
### addAlphaCeilingEffect() {#addAlphaCeilingEffect--}
```
public final IAlphaCeiling addAlphaCeilingEffect()
```

يضيف تأثير Alpha Ceiling الجديد إلى نهاية مجموعة.

**الإرجاع:**
[IAlphaCeiling](../../com.aspose.slides/ialphaceiling) - فهرس تأثير الصورة الجديد في مجموعة.
### addAlphaFloorEffect() {#addAlphaFloorEffect--}
```
public final IAlphaFloor addAlphaFloorEffect()
```

يضيف تأثير Alpha Floor الجديد إلى نهاية مجموعة.

**الإرجاع:**
[IAlphaFloor](../../com.aspose.slides/ialphafloor) - فهرس تأثير الصورة الجديد في مجموعة.
### addAlphaInverseEffect() {#addAlphaInverseEffect--}
```
public final IAlphaInverse addAlphaInverseEffect()
```

يضيف تأثير Alpha Inverse الجديد إلى نهاية مجموعة.

**الإرجاع:**
[IAlphaInverse](../../com.aspose.slides/ialphainverse) - فهرس تأثير الصورة الجديد في مجموعة.
### addAlphaModulateEffect() {#addAlphaModulateEffect--}
```
public final IAlphaModulate addAlphaModulateEffect()
```

يضيف تأثير Alpha Modulate الجديد إلى نهاية مجموعة.

**الإرجاع:**
[IAlphaModulate](../../com.aspose.slides/ialphamodulate) - فهرس تأثير الصورة الجديد في مجموعة.
### addAlphaModulateFixedEffect(float amount) {#addAlphaModulateFixedEffect-float-}
```
public final IAlphaModulateFixed addAlphaModulateFixedEffect(float amount)
```

يضيف تأثير Alpha Modulate Fixed الجديد إلى نهاية مجموعة.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| amount | float | النسبة المئوية لتقليل أو زيادة قيمة ألفا. |

**الإرجاع:**
[IAlphaModulateFixed](../../com.aspose.slides/ialphamodulatefixed) - فهرس تأثير الصورة الجديد في مجموعة.
### addAlphaReplaceEffect(float alpha) {#addAlphaReplaceEffect-float-}
```
public final IAlphaReplace addAlphaReplaceEffect(float alpha)
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
public final IBiLevel addBiLevelEffect(float threshold)
```

يضيف تأثير Bi-Level (أسود/أبيض) الجديد إلى نهاية مجموعة.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| threshold | float | عتبة الإضاءة لتأثير Bi-Level. القيم الأكبر أو المساوية للعتبة تُصبح بيضاء. القيم الأقل تُصبح سوداء. |

**الإرجاع:**
[IBiLevel](../../com.aspose.slides/ibilevel) - فهرس تأثير الصورة الجديد في مجموعة.
### addBlurEffect(double radius, boolean grow) {#addBlurEffect-double-boolean-}
```
public final IBlur addBlurEffect(double radius, boolean grow)
```

يضيف تأثير Blur الجديد إلى نهاية مجموعة.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| radius | double | نصف قطر الضبابية. |
| grow | boolean | يحدد ما إذا كان يجب توسيع حدود الكائن نتيجة للضبابية. true يعني توسيع الحدود، false يعني عدم التوسيع. |

**الإرجاع:**
[IBlur](../../com.aspose.slides/iblur) - فهرس تأثير الصورة الجديد في مجموعة.
### addColorChangeEffect() {#addColorChangeEffect--}
```
public final IColorChange addColorChangeEffect()
```

يضيف تأثير Color Change الجديد إلى نهاية مجموعة.

**الإرجاع:**
[IColorChange](../../com.aspose.slides/icolorchange) - فهرس تأثير الصورة الجديد في مجموعة.
### addColorReplaceEffect() {#addColorReplaceEffect--}
```
public final IColorReplace addColorReplaceEffect()
```

يضيف تأثير Color Replacement الجديد إلى نهاية مجموعة.

**الإرجاع:**
[IColorReplace](../../com.aspose.slides/icolorreplace) - فهرس تأثير الصورة الجديد في مجموعة.
### addDuotoneEffect() {#addDuotoneEffect--}
```
public final IDuotone addDuotoneEffect()
```

يضيف تأثير Duotone الجديد إلى نهاية مجموعة.

**الإرجاع:**
[IDuotone](../../com.aspose.slides/iduotone) - فهرس تأثير الصورة الجديد في مجموعة.
### addFillOverlayEffect() {#addFillOverlayEffect--}
```
public final IFillOverlay addFillOverlayEffect()
```

يضيف تأثير Fill Overlay الجديد إلى نهاية مجموعة.

**الإرجاع:**
[IFillOverlay](../../com.aspose.slides/ifilloverlay) - فهرس تأثير الصورة الجديد في مجموعة.
### addGrayScaleEffect() {#addGrayScaleEffect--}
```
public final IGrayScale addGrayScaleEffect()
```

يضيف تأثير Gray Scale الجديد إلى نهاية مجموعة.

**الإرجاع:**
[IGrayScale](../../com.aspose.slides/igrayscale) - فهرس تأثير الصورة الجديد في مجموعة.
### addHSLEffect(float hue, float saturation, float luminance) {#addHSLEffect-float-float-float-}
```
public final IHSL addHSLEffect(float hue, float saturation, float luminance)
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
public final ILuminance addLuminanceEffect(float brightness, float contrast)
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
public final ITint addTintEffect(float hue, float amount)
```

يضيف تأثير Tint الجديد إلى نهاية مجموعة.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| hue | float | الصبغة التي يُصبغ نحوها. |
| amount | float | يحدد مقدار إزاحة قيمة اللون. |

**الإرجاع:**
[ITint](../../com.aspose.slides/itint) - فهرس تأثير الصورة الجديد في مجموعة.
### addBrightnessContrastEffect(float brightness, float contrast) {#addBrightnessContrastEffect-float-float-}
```
public final IBrightnessContrast addBrightnessContrastEffect(float brightness, float contrast)
```

يضيف تأثير BrightnessContrast الجديد إلى نهاية مجموعة.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| brightness | float | النسبة المئوية لتغيير السطوع. |
| contrast | float | النسبة المئوية لتغيير التباين. |

**الإرجاع:**
[IBrightnessContrast](../../com.aspose.slides/ibrightnesscontrast) - فهرس تأثير الصورة الجديد في مجموعة.
### size() {#size--}
```
public final int size()
```

يعيد عدد تأثيرات الصورة في مجموعة. قراءة فقط int.

**الإرجاع:**
int
### isReadOnly() {#isReadOnly--}
```
public final boolean isReadOnly()
```

يحصل على قيمة تشير إلى ما إذا كان [IGenericCollection](../../com.aspose.slides/igenericcollection) قراءة فقط. قراءة فقط boolean.

**الإرجاع:**
boolean - true إذا كان [IGenericCollection](../../com.aspose.slides/igenericcollection) قراءة فقط؛ وإلا false.
### addItem(IImageTransformOperation operation) {#addItem-com.aspose.slides.IImageTransformOperation-}
```
public final void addItem(IImageTransformOperation operation)
```

يضيف تأثير الصورة الجديد إلى نهاية مجموعة.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| operation | [IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation) | تأثير الصورة الذي يضيف إلى نهاية مجموعة. |
### clear() {#clear--}
```
public final void clear()
```

يزيل جميع تأثيرات الصورة من مجموعة.
### containsItem(IImageTransformOperation item) {#containsItem-com.aspose.slides.IImageTransformOperation-}
```
public final boolean containsItem(IImageTransformOperation item)
```

يحدد ما إذا كان [IGenericCollection](../../com.aspose.slides/igenericcollection) يحتوي على قيمة معينة.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| item | [IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation) | الكائن الذي يُبحث عنه في [IGenericCollection](../../com.aspose.slides/igenericcollection). |

**الإرجاع:**
boolean - true إذا وُجد العنصر في [IGenericCollection](../../com.aspose.slides/igenericcollection)؛ وإلا false.
### copyToTArray(IImageTransformOperation[] array, int arrayIndex) {#copyToTArray-com.aspose.slides.IImageTransformOperation---int-}
```
public final void copyToTArray(IImageTransformOperation[] array, int arrayIndex)
```

ينسخ عناصر [IGenericCollection](../../com.aspose.slides/igenericcollection) إلى مصفوفة، بدءًا من فهرس مصفوفة معين.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| array | [IImageTransformOperation\[\]](../../com.aspose.slides/iimagetransformoperation) | المصفوفة الأحادية البعد التي هي وجهة العناصر المنسوخة من [IGenericCollection](../../com.aspose.slides/igenericcollection). يجب أن تكون المصفوفة ذات فهرسة صفرية. |
| arrayIndex | int | الفهرس الصفري في المصفوفة الذي يبدأ منه النسخ. |
### removeItem(IImageTransformOperation item) {#removeItem-com.aspose.slides.IImageTransformOperation-}
```
public final boolean removeItem(IImageTransformOperation item)
```

يزيل أول حدوث لكائن معين من [IGenericCollection](../../com.aspose.slides/igenericcollection).

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| item | [IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation) | الكائن الذي يُزيل من [IGenericCollection](../../com.aspose.slides/igenericcollection). |

**الإرجاع:**
boolean - true إذا تم إزالة العنصر بنجاح من [IGenericCollection](../../com.aspose.slides/igenericcollection)؛ وإلا false. تُعيد هذه الطريقة false أيضًا إذا لم يُعثر على العنصر في [IGenericCollection](../../com.aspose.slides/igenericcollection) الأصلي.
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IImageTransformOperation> iterator()
```

يعيد كيانًا يكرر عبر المجموعة.

**الإرجاع:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IImageTransformOperation> - IGenericEnumerator يمكن استخدامه لتكرار عبر المجموعة.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IImageTransformOperation> iteratorJava()
```

يعيد مكرر جافا للمجموعة بأكملها.

**الإرجاع:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IImageTransformOperation> - java.util.Iterator للمجموعة بأكملها.