---
title: IImageTransformOperationCollection
second_title: Aspose.Slides برای Android از طریق مرجع API جاوا
description: نمایش‌دهنده مجموعه‌ای از افکت‌های اعمال‌شده بر یک تصویر.
type: docs
url: /fa/com.aspose.slides/iimagetransformoperationcollection/
---
**تمام رابط‌های پیاده‌سازی‌شده:**
com.aspose.ms.System.Collections.Generic.IGenericCollection
``` 
public interface IImageTransformOperationCollection extends System.Collections.Generic.IGenericCollection<IImageTransformOperation>
```

نمایش‌دهنده مجموعه‌ای از افکت‌های اعمال‌شده بر یک تصویر.
## متدها

| متد | توضیح |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | یک [IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation) را از مجموعه بر اساس ایندکس آن باز می‌گرداند. |
| [removeAt(int index)](#removeAt-int-) | یک افکت تصویر را از مجموعه در ایندکس مشخص‌شده حذف می‌کند. |
| [addAlphaBiLevelEffect(float threshold)](#addAlphaBiLevelEffect-float-) | افکت جدید Alpha Bi-Level را به انتهای مجموعه اضافه می‌کند. |
| [addAlphaCeilingEffect()](#addAlphaCeilingEffect--) | افکت جدید Alpha Ceiling را به انتهای مجموعه اضافه می‌کند. |
| [addAlphaFloorEffect()](#addAlphaFloorEffect--) | افکت جدید Alpha Floor را به انتهای مجموعه اضافه می‌کند. |
| [addAlphaInverseEffect()](#addAlphaInverseEffect--) | افکت جدید Alpha Inverse را به انتهای مجموعه اضافه می‌کند. |
| [addAlphaModulateEffect()](#addAlphaModulateEffect--) | افکت جدید Alpha Modulate را به انتهای مجموعه اضافه می‌کند. |
| [addAlphaModulateFixedEffect(float amount)](#addAlphaModulateFixedEffect-float-) | افکت جدید Alpha Modulate Fixed را به انتهای مجموعه اضافه می‌کند. |
| [addAlphaReplaceEffect(float alpha)](#addAlphaReplaceEffect-float-) | افکت جدید Alpha Replace را به انتهای مجموعه اضافه می‌کند. |
| [addBiLevelEffect(float threshold)](#addBiLevelEffect-float-) | افکت جدید Bi-Level (سیاه/سفید) را به انتهای مجموعه اضافه می‌کند. |
| [addBlurEffect(double radius, boolean grow)](#addBlurEffect-double-boolean-) | افکت جدید Blur را به انتهای مجموعه اضافه می‌کند. |
| [addColorChangeEffect()](#addColorChangeEffect--) | افکت جدید Color Change را به انتهای مجموعه اضافه می‌کند. |
| [addColorReplaceEffect()](#addColorReplaceEffect--) | افکت جدید Color Replacement را به انتهای مجموعه اضافه می‌کند. |
| [addDuotoneEffect()](#addDuotoneEffect--) | افکت جدید Duotone را به انتهای مجموعه اضافه می‌کند. |
| [addFillOverlayEffect()](#addFillOverlayEffect--) | افکت جدید Fill Overlay را به انتهای مجموعه اضافه می‌کند. |
| [addGrayScaleEffect()](#addGrayScaleEffect--) | افکت جدید Gray Scale را به انتهای مجموعه اضافه می‌کند. |
| [addHSLEffect(float hue, float saturation, float luminance)](#addHSLEffect-float-float-float-) | افکت جدید Hue/Saturation/Luminance را به انتهای مجموعه اضافه می‌کند. |
| [addLuminanceEffect(float brightness, float contrast)](#addLuminanceEffect-float-float-) | افکت جدید Luminance را به انتهای مجموعه اضافه می‌کند. |
| [addTintEffect(float hue, float amount)](#addTintEffect-float-float-) | افکت جدید Tint را به انتهای مجموعه اضافه می‌کند. |
| [addBrightnessContrastEffect(float brightness, float contrast)](#addBrightnessContrastEffect-float-float-) | افکت جدید BrightnessContrast را به انتهای مجموعه اضافه می‌کند. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IImageTransformOperation get_Item(int index)
```

یک [IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation) را از مجموعه بر اساس ایندکس آن باز می‌گرداند.

**پارامترها:**
| پارامتر | نوع | شرح |
| --- | --- | --- |
| index | int | ایندکس مورد. |

**مقدار بازگشت:**
[IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation) - شی [IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation).
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

یک افکت تصویر را از مجموعه در ایندکس مشخص‌شده حذف می‌کند.

**پارامترها:**
| پارامتر | نوع | شرح |
| --- | --- | --- |
| index | int | ایندکس افکت تصویری که باید حذف شود. |
### addAlphaBiLevelEffect(float threshold) {#addAlphaBiLevelEffect-float-}
```
public abstract IAlphaBiLevel addAlphaBiLevelEffect(float threshold)
```

افکت جدید Alpha Bi-Level را به انتهای مجموعه اضافه می‌کند.

**پارامترها:**
| پارامتر | نوع | شرح |
| --- | --- | --- |
| threshold | float | مقدار آستانه برای افکت Alpha Bi-Level. |

**مقدار بازگشت:**
[IAlphaBiLevel](../../com.aspose.slides/ialphabilevel) - ایندکس افکت جدید تصویر در مجموعه.
### addAlphaCeilingEffect() {#addAlphaCeilingEffect--}
```
public abstract IAlphaCeiling addAlphaCeilingEffect()
```

افکت جدید Alpha Ceiling را به انتهای مجموعه اضافه می‌کند.

**مقدار بازگشت:**
[IAlphaCeiling](../../com.aspose.slides/ialphaceiling) - ایندکس افکت جدید تصویر در مجموعه.
### addAlphaFloorEffect() {#addAlphaFloorEffect--}
```
public abstract IAlphaFloor addAlphaFloorEffect()
```

افکت جدید Alpha Floor را به انتهای مجموعه اضافه می‌کند.

**مقدار بازگشت:**
[IAlphaFloor](../../com.aspose.slides/ialphafloor) - ایندکس افکت جدید تصویر در مجموعه.
### addAlphaInverseEffect() {#addAlphaInverseEffect--}
```
public abstract IAlphaInverse addAlphaInverseEffect()
```

افکت جدید Alpha Inverse را به انتهای مجموعه اضافه می‌کند.

**مقدار بازگشت:**
[IAlphaInverse](../../com.aspose.slides/ialphainverse) - ایندکس افکت جدید تصویر در مجموعه.
### addAlphaModulateEffect() {#addAlphaModulateEffect--}
```
public abstract IAlphaModulate addAlphaModulateEffect()
```

افکت جدید Alpha Modulate را به انتهای مجموعه اضافه می‌کند.

**مقدار بازگشت:**
[IAlphaModulate](../../com.aspose.slides/ialphamodulate) - ایندکس افکت جدید تصویر در مجموعه.
### addAlphaModulateFixedEffect(float amount) {#addAlphaModulateFixedEffect-float-}
```
public abstract IAlphaModulateFixed addAlphaModulateFixedEffect(float amount)
```

افکت جدید Alpha Modulate Fixed را به انتهای مجموعه اضافه می‌کند.

**پارامترها:**
| پارامتر | نوع | شرح |
| --- | --- | --- |
| amount | float | درصدی که مقدار آلفا را مقیاس می‌کند. |

**مقدار بازگشت:**
[IAlphaModulateFixed](../../com.aspose.slides/ialphamodulatefixed) - ایندکس افکت جدید تصویر در مجموعه.
### addAlphaReplaceEffect(float alpha) {#addAlphaReplaceEffect-float-}
```
public abstract IAlphaReplace addAlphaReplaceEffect(float alpha)
```

افکت جدید Alpha Replace را به انتهای مجموعه اضافه می‌کند.

**پارامترها:**
| پارامتر | نوع | شرح |
| --- | --- | --- |
| alpha | float | مقدار شفافیت جدید. |

**مقدار بازگشت:**
[IAlphaReplace](../../com.aspose.slides/ialphareplace) - ایندکس افکت جدید تصویر در مجموعه.
### addBiLevelEffect(float threshold) {#addBiLevelEffect-float-}
```
public abstract IBiLevel addBiLevelEffect(float threshold)
```

افکت جدید Bi-Level (سیاه/سفید) را به انتهای مجموعه اضافه می‌کند.

**پارامترها:**
| پارامتر | نوع | شرح |
| --- | --- | --- |
| threshold | float | آستانه روشنایی برای افکت Bi-Level. مقدارهای برابر یا بالای آستانه به سفید تنظیم می‌شوند؛ مقدارهای کمتر به سیاه تنظیم می‌شوند. |

**مقدار بازگشت:**
[IBiLevel](../../com.aspose.slides/ibilevel) - ایندکس افکت جدید تصویر در مجموعه.
### addBlurEffect(double radius, boolean grow) {#addBlurEffect-double-boolean-}
```
public abstract IBlur addBlurEffect(double radius, boolean grow)
```

افکت جدید Blur را به انتهای مجموعه اضافه می‌کند.

**پارامترها:**
| پارامتر | نوع | شرح |
| --- | --- | --- |
| radius | double | شعاع محو کردن. |
| grow | boolean | مشخص می‌کند آیا مرزهای شی به عنوان نتیجه محو شدن بزرگ می‌شوند یا نه. مقدار true به معنای بزرگ شدن مرزها و false به معنای عدم بزرگ شدن است. |

**مقدار بازگشت:**
[IBlur](../../com.aspose.slides/iblur) - ایندکس افکت جدید تصویر در مجموعه.
### addColorChangeEffect() {#addColorChangeEffect--}
```
public abstract IColorChange addColorChangeEffect()
```

افکت جدید Color Change را به انتهای مجموعه اضافه می‌کند.

**مقدار بازگشت:**
[IColorChange](../../com.aspose.slides/icolorchange) - ایندکس افکت جدید تصویر در مجموعه.
### addColorReplaceEffect() {#addColorReplaceEffect--}
```
public abstract IColorReplace addColorReplaceEffect()
```

افکت جدید Color Replacement را به انتهای مجموعه اضافه می‌کند.

**مقدار بازگشت:**
[IColorReplace](../../com.aspose.slides/icolorreplace) - ایندکس افکت جدید تصویر در مجموعه.
### addDuotoneEffect() {#addDuotoneEffect--}
```
public abstract IDuotone addDuotoneEffect()
```

افکت جدید Duotone را به انتهای مجموعه اضافه می‌کند.

**مقدار بازگشت:**
[IDuotone](../../com.aspose.slides/iduotone) - ایندکس افکت جدید تصویر در مجموعه.
### addFillOverlayEffect() {#addFillOverlayEffect--}
```
public abstract IFillOverlay addFillOverlayEffect()
```

افکت جدید Fill Overlay را به انتهای مجموعه اضافه می‌کند.

**مقدار بازگشت:**
[IFillOverlay](../../com.aspose.slides/ifilloverlay) - ایندکس افکت جدید تصویر در مجموعه.
### addGrayScaleEffect() {#addGrayScaleEffect--}
```
public abstract IGrayScale addGrayScaleEffect()
```

افکت جدید Gray Scale را به انتهای مجموعه اضافه می‌کند.

**مقدار بازگشت:**
[IGrayScale](../../com.aspose.slides/igrayscale) - ایندکس افکت جدید تصویر در مجموعه.
### addHSLEffect(float hue, float saturation, float luminance) {#addHSLEffect-float-float-float-}
```
public abstract IHSL addHSLEffect(float hue, float saturation, float luminance)
```

افکت جدید Hue/Saturation/Luminance را به انتهای مجموعه اضافه می‌کند.

**پارامترها:**
| پارامتر | نوع | شرح |
| --- | --- | --- |
| hue | float | عدد درجه‌هایی که هیو تنظیم می‌شود. |
| saturation | float | درصدی که اشباع تنظیم می‌شود. |
| luminance | float | درصدی که روشنایی تنظیم می‌شود. |

**مقدار بازگشت:**
[IHSL](../../com.aspose.slides/ihsl) - ایندکس افکت جدید تصویر در مجموعه.
### addLuminanceEffect(float brightness, float contrast) {#addLuminanceEffect-float-float-}
```
public abstract ILuminance addLuminanceEffect(float brightness, float contrast)
```

افکت جدید Luminance را به انتهای مجموعه اضافه می‌کند.

**پارامترها:**
| پارامتر | نوع | شرح |
| --- | --- | --- |
| brightness | float | درصدی برای تغییر روشنایی. |
| contrast | float | درصدی برای تغییر کنتراست. |

**مقدار بازگشت:**
[ILuminance](../../com.aspose.slides/iluminance) - ایندکس افکت جدید تصویر در مجموعه.
### addTintEffect(float hue, float amount) {#addTintEffect-float-float-}
```
public abstract ITint addTintEffect(float hue, float amount)
```

افکت جدید Tint را به انتهای مجموعه اضافه می‌کند.

**پارامترها:**
| پارامتر | نوع | شرح |
| --- | --- | --- |
| hue | float | هیو جهت رنگ‌آمیزی. |
| amount | float | میزان جابه‌جایی مقدار رنگ را مشخص می‌کند. |

**مقدار بازگشت:**
[ITint](../../com.aspose.slides/itint) - ایندکس افکت جدید تصویر در مجموعه.
### addBrightnessContrastEffect(float brightness, float contrast) {#addBrightnessContrastEffect-float-float-}
```
public abstract IBrightnessContrast addBrightnessContrastEffect(float brightness, float contrast)
```

افکت جدید BrightnessContrast را به انتهای مجموعه اضافه می‌کند.

**پارامترها:**
| پارامتر | نوع | شرح |
| --- | --- | --- |
| brightness | float | درصدی برای تغییر روشنایی. |
| contrast | float | درصدی برای تغییر کنتراست. |

**مقدار بازگشت:**
[IBrightnessContrast](../../com.aspose.slides/ibrightnesscontrast) - ایندکس افکت جدید تصویر در مجموعه.