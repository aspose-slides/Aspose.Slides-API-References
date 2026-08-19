---
title: IImageTransformOperationCollection
second_title: مرجع API Aspose.Slides برای Java
description: نمایانگر مجموعه‌ای از افکت‌های اعمال‌شده به یک تصویر.
type: docs
url: /fa/com.aspose.slides/iimagetransformoperationcollection/
---
**تمام رابط‌های پیاده‌سازی‌شده:**  
com.aspose.ms.System.Collections.Generic.IGenericCollection
```
public interface IImageTransformOperationCollection extends System.Collections.Generic.IGenericCollection<IImageTransformOperation>
```

نمایانگر یک مجموعه از افکت‌های اعمال‌شده به یک تصویر.
## متدها

| متد | توضیح |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | یک [IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation) را از مجموعه با ایندکس داده شده برمی‌گرداند. |
| [removeAt(int index)](#removeAt-int-) | یک افکت تصویر را از مجموعه در ایندکس مشخص حذف می‌کند. |
| [addAlphaBiLevelEffect(float threshold)](#addAlphaBiLevelEffect-float-) | افکت Alpha Bi-Level جدید را به انتهای یک مجموعه اضافه می‌کند. |
| [addAlphaCeilingEffect()](#addAlphaCeilingEffect--) | افکت Alpha Ceiling جدید را به انتهای یک مجموعه اضافه می‌کند. |
| [addAlphaFloorEffect()](#addAlphaFloorEffect--) | افکت Alpha Floor جدید را به انتهای یک مجموعه اضافه می‌کند. |
| [addAlphaInverseEffect()](#addAlphaInverseEffect--) | افکت Alpha Inverse جدید را به انتهای یک مجموعه اضافه می‌کند. |
| [addAlphaModulateEffect()](#addAlphaModulateEffect--) | افکت Alpha Modulate جدید را به انتهای یک مجموعه اضافه می‌کند. |
| [addAlphaModulateFixedEffect(float amount)](#addAlphaModulateFixedEffect-float-) | افکت Alpha Modulate Fixed جدید را به انتهای یک مجموعه اضافه می‌کند. |
| [addAlphaReplaceEffect(float alpha)](#addAlphaReplaceEffect-float-) | افکت Alpha Replace جدید را به انتهای یک مجموعه اضافه می‌کند. |
| [addBiLevelEffect(float threshold)](#addBiLevelEffect-float-) | افکت Bi-Level (black/white) جدید را به انتهای یک مجموعه اضافه می‌کند. |
| [addBlurEffect(double radius, boolean grow)](#addBlurEffect-double-boolean-) | افکت Blur جدید را به انتهای یک مجموعه اضافه می‌کند. |
| [addColorChangeEffect()](#addColorChangeEffect--) | افکت Color Change جدید را به انتهای یک مجموعه اضافه می‌کند. |
| [addColorReplaceEffect()](#addColorReplaceEffect--) | افکت Color Replacement جدید را به انتهای یک مجموعه اضافه می‌کند. |
| [addDuotoneEffect()](#addDuotoneEffect--) | افکت Duotone جدید را به انتهای یک مجموعه اضافه می‌کند. |
| [addFillOverlayEffect()](#addFillOverlayEffect--) | افکت Fill Overlay جدید را به انتهای یک مجموعه اضافه می‌کند. |
| [addGrayScaleEffect()](#addGrayScaleEffect--) | افکت Gray Scale جدید را به انتهای یک مجموعه اضافه می‌کند. |
| [addHSLEffect(float hue, float saturation, float luminance)](#addHSLEffect-float-float-float-) | افکت Hue/Saturation/Luminance جدید را به انتهای یک مجموعه اضافه می‌کند. |
| [addLuminanceEffect(float brightness, float contrast)](#addLuminanceEffect-float-float-) | افکت Luminance جدید را به انتهای یک مجموعه اضافه می‌کند. |
| [addTintEffect(float hue, float amount)](#addTintEffect-float-float-) | افکت Tint جدید را به انتهای یک مجموعه اضافه می‌کند. |
| [addBrightnessContrastEffect(float brightness, float contrast)](#addBrightnessContrastEffect-float-float-) | افکت BrightnessContrast جدید را به انتهای یک مجموعه اضافه می‌کند. |

### get_Item(int index) {#get-Item-int-}
```
public abstract IImageTransformOperation get_Item(int index)
```

یک [IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation) را از مجموعه با ایندکس داده شده برمی‌گرداند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int | ایندکس مورد. |

**بازگشت:**
[IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation) - شیء [IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation).

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

یک افکت تصویر را از مجموعه در ایندکس مشخص حذف می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int | ایندکس افکت تصویری که باید حذف شود. |

### addAlphaBiLevelEffect(float threshold) {#addAlphaBiLevelEffect-float-}
```
public abstract IAlphaBiLevel addAlphaBiLevelEffect(float threshold)
```

افکت Alpha Bi-Level جدید را به انتهای یک مجموعه اضافه می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| threshold | float | مقدار آستانه برای افکت Alpha Bi-Level. |

**بازگشت:**
[IAlphaBiLevel](../../com.aspose.slides/ialphabilevel) - ایندکس افکت تصویر جدید در یک مجموعه.

### addAlphaCeilingEffect() {#addAlphaCeilingEffect--}
```
public abstract IAlphaCeiling addAlphaCeilingEffect()
```

افکت Alpha Ceiling جدید را به انتهای یک مجموعه اضافه می‌کند.

**بازگشت:**
[IAlphaCeiling](../../com.aspose.slides/ialphaceiling) - ایندکس افکت تصویر جدید در یک مجموعه.

### addAlphaFloorEffect() {#addAlphaFloorEffect--}
```
public abstract IAlphaFloor addAlphaFloorEffect()
```

افکت Alpha Floor جدید را به انتهای یک مجموعه اضافه می‌کند.

**بازگشت:**
[IAlphaFloor](../../com.aspose.slides/ialphafloor) - ایندکس افکت تصویر جدید در یک مجموعه.

### addAlphaInverseEffect() {#addAlphaInverseEffect--}
```
public abstract IAlphaInverse addAlphaInverseEffect()
```

افکت Alpha Inverse جدید را به انتهای یک مجموعه اضافه می‌کند.

**بازگشت:**
[IAlphaInverse](../../com.aspose.slides/ialphainverse) - ایندکس افکت تصویر جدید در یک مجموعه.

### addAlphaModulateEffect() {#addAlphaModulateEffect--}
```
public abstract IAlphaModulate addAlphaModulateEffect()
```

افکت Alpha Modulate جدید را به انتهای یک مجموعه اضافه می‌کند.

**بازگشت:**
[IAlphaModulate](../../com.aspose.slides/ialphamodulate) - ایندکس افکت تصویر جدید در یک مجموعه.

### addAlphaModulateFixedEffect(float amount) {#addAlphaModulateFixedEffect-float-}
```
public abstract IAlphaModulateFixed addAlphaModulateFixedEffect(float amount)
```

افکت Alpha Modulate Fixed جدید را به انتهای یک مجموعه اضافه می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| amount | float | درصد مقدار برای مقیاس‌بندی آلفا. |

**بازگشت:**
[IAlphaModulateFixed](../../com.aspose.slides/ialphamodulatefixed) - ایندکس افکت تصویر جدید در یک مجموعه.

### addAlphaReplaceEffect(float alpha) {#addAlphaReplaceEffect-float-}
```
public abstract IAlphaReplace addAlphaReplaceEffect(float alpha)
```

افکت Alpha Replace جدید را به انتهای یک مجموعه اضافه می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| alpha | float | مقدار شفافیت جدید. |

**بازگشت:**
[IAlphaReplace](../../com.aspose.slides/ialphareplace) - ایندکس افکت تصویر جدید در یک مجموعه.

### addBiLevelEffect(float threshold) {#addBiLevelEffect-float-}
```
public abstract IBiLevel addBiLevelEffect(float threshold)
```

افکت Bi-Level (black/white) جدید را به انتهای یک مجموعه اضافه می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| threshold | float | آستانه روشنایی برای افکت Bi-Level. مقادیر برابر یا بزرگتر از آستانه به سفید تنظیم می‌شوند. مقادیر کمتر از آستانه به سیاه تنظیم می‌شوند. |

**بازگشت:**
[IBiLevel](../../com.aspose.slides/ibilevel) - ایندکس افکت تصویر جدید در یک مجموعه.

### addBlurEffect(double radius, boolean grow) {#addBlurEffect-double-boolean-}
```
public abstract IBlur addBlurEffect(double radius, boolean grow)
```

افکت Blur جدید را به انتهای یک مجموعه اضافه می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| radius | double | شعاع تار شدن. |
| grow | boolean | مشخص می‌کند که مرزهای شیء پس از تار شدن بزرگ شوند یا نه. مقدار true نشان می‌دهد مرزها بزرگ می‌شوند و false نشان می‌دهد که بزرگ نمی‌شوند. |

**بازگشت:**
[IBlur](../../com.aspose.slides/iblur) - ایندکس افکت تصویر جدید در یک مجموعه.

### addColorChangeEffect() {#addColorChangeEffect--}
```
public abstract IColorChange addColorChangeEffect()
```

افکت Color Change جدید را به انتهای یک مجموعه اضافه می‌کند.

**بازگشت:**
[IColorChange](../../com.aspose.slides/icolorchange) - ایندکس افکت تصویر جدید در یک مجموعه.

### addColorReplaceEffect() {#addColorReplaceEffect--}
```
public abstract IColorReplace addColorReplaceEffect()
```

افکت Color Replacement جدید را به انتهای یک مجموعه اضافه می‌کند.

**بازگشت:**
[IColorReplace](../../com.aspose.slides/icolorreplace) - ایندکس افکت تصویر جدید در یک مجموعه.

### addDuotoneEffect() {#addDuotoneEffect--}
```
public abstract IDuotone addDuotoneEffect()
```

افکت Duotone جدید را به انتهای یک مجموعه اضافه می‌کند.

**بازگشت:**
[IDuotone](../../com.aspose.slides/iduotone) - ایندکس افکت تصویر جدید در یک مجموعه.

### addFillOverlayEffect() {#addFillOverlayEffect--}
```
public abstract IFillOverlay addFillOverlayEffect()
```

افکت Fill Overlay جدید را به انتهای یک مجموعه اضافه می‌کند.

**بازگشت:**
[IFillOverlay](../../com.aspose.slides/ifilloverlay) - ایندکس افکت تصویر جدید در یک مجموعه.

### addGrayScaleEffect() {#addGrayScaleEffect--}
```
public abstract IGrayScale addGrayScaleEffect()
```

افکت Gray Scale جدید را به انتهای یک مجموعه اضافه می‌کند.

**بازگشت:**
[IGrayScale](../../com.aspose.slides/igrayscale) - ایندکس افکت تصویر جدید در یک مجموعه.

### addHSLEffect(float hue, float saturation, float luminance) {#addHSLEffect-float-float-float-}
```
public abstract IHSL addHSLEffect(float hue, float saturation, float luminance)
```

افکت Hue/Saturation/Luminance جدید را به انتهای یک مجموعه اضافه می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| hue | float | تعداد درجه‌هایی که هیو تنظیم می‌شود. |
| saturation | float | درصد تنظیم اشباع. |
| luminance | float | درصد تنظیم روشنایی. |

**بازگشت:**
[IHSL](../../com.aspose.slides/ihsl) - ایندکس افکت تصویر جدید در یک مجموعه.

### addLuminanceEffect(float brightness, float contrast) {#addLuminanceEffect-float-float-}
```
public abstract ILuminance addLuminanceEffect(float brightness, float contrast)
```

افکت Luminance جدید را به انتهای یک مجموعه اضافه می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| brightness | float | درصد تغییر روشنایی. |
| contrast | float | درصد تغییر کنتراست. |

**بازگشت:**
[ILuminance](../../com.aspose.slides/iluminance) - ایندکس افکت تصویر جدید در یک مجموعه.

### addTintEffect(float hue, float amount) {#addTintEffect-float-float-}
```
public abstract ITint addTintEffect(float hue, float amount)
```

افکت Tint جدید را به انتهای یک مجموعه اضافه می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| hue | float | هیو جهت رنگ‌زنی. |
| amount | float | مقدار جابجایی مقدار رنگ. |

**بازگشت:**
[ITint](../../com.aspose.slides/itint) - ایندکس افکت تصویر جدید در یک مجموعه.

### addBrightnessContrastEffect(float brightness, float contrast) {#addBrightnessContrastEffect-float-float-}
```
public abstract IBrightnessContrast addBrightnessContrastEffect(float brightness, float contrast)
```

افکت BrightnessContrast جدید را به انتهای یک مجموعه اضافه می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| brightness | float | درصد تغییر روشنایی. |
| contrast | float | درصد تغییر کنتراست. |

**بازگشت:**
[IBrightnessContrast](../../com.aspose.slides/ibrightnesscontrast) - ایندکس افکت تصویر جدید در یک مجموعه.