---
title: ImageTransformOperationCollection
second_title: Aspose.Slides برای Android از طریق مرجع API جاوا
description: نمایش‌دهنده یک مجموعه از افکت‌های اعمال‌شده به یک تصویر.
type: docs
url: /fa/com.aspose.slides/imagetransformoperationcollection/
---
**وراثت:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**تمام رابط‌های پیاده‌سازی‌شده:**
[com.aspose.slides.IImageTransformOperationCollection](../../com.aspose.slides/iimagetransformoperationcollection)
```
public final class ImageTransformOperationCollection extends PVIObject implements IImageTransformOperationCollection
```

نمایش‌دهنده مجموعه‌ای از افکت‌های اعمال‌شده به یک تصویر.
## متدها

| متد | توضیح |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [get_Item(int index)](#get-Item-int-) | یک [ImageTransformOperation](../../com.aspose.slides/imagetransformoperation) را از مجموعه با شاخص آن برمی‌گرداند. |
| [removeAt(int index)](#removeAt-int-) | یک افکت تصویر را از مجموعه در شاخص مشخص حذف می‌کند. |
| [addAlphaBiLevelEffect(float threshold)](#addAlphaBiLevelEffect-float-) | افکت جدید Alpha Bi-Level را به انتهای یک مجموعه اضافه می‌کند. |
| [addAlphaCeilingEffect()](#addAlphaCeilingEffect--) | افکت جدید Alpha Ceiling را به انتهای یک مجموعه اضافه می‌کند. |
| [addAlphaFloorEffect()](#addAlphaFloorEffect--) | افکت جدید Alpha Floor را به انتهای یک مجموعه اضافه می‌کند. |
| [addAlphaInverseEffect()](#addAlphaInverseEffect--) | افکت جدید Alpha Inverse را به انتهای یک مجموعه اضافه می‌کند. |
| [addAlphaModulateEffect()](#addAlphaModulateEffect--) | افکت جدید Alpha Modulate را به انتهای یک مجموعه اضافه می‌کند. |
| [addAlphaModulateFixedEffect(float amount)](#addAlphaModulateFixedEffect-float-) | افکت جدید Alpha Modulate Fixed را به انتهای یک مجموعه اضافه می‌کند. |
| [addAlphaReplaceEffect(float alpha)](#addAlphaReplaceEffect-float-) | افکت جدید Alpha Replace را به انتهای یک مجموعه اضافه می‌کند. |
| [addBiLevelEffect(float threshold)](#addBiLevelEffect-float-) | افکت جدید Bi-Level (black/white) را به انتهای یک مجموعه اضافه می‌کند. |
| [addBlurEffect(double radius, boolean grow)](#addBlurEffect-double-boolean-) | افکت جدید Blur را به انتهای یک مجموعه اضافه می‌کند. |
| [addColorChangeEffect()](#addColorChangeEffect--) | افکت جدید Color Change را به انتهای یک مجموعه اضافه می‌کند. |
| [addColorReplaceEffect()](#addColorReplaceEffect--) | افکت جدید Color Replacement را به انتهای یک مجموعه اضافه می‌کند. |
| [addDuotoneEffect()](#addDuotoneEffect--) | افکت جدید Duotone را به انتهای یک مجموعه اضافه می‌کند. |
| [addFillOverlayEffect()](#addFillOverlayEffect--) | افکت جدید Fill Overlay را به انتهای یک مجموعه اضافه می‌کند. |
| [addGrayScaleEffect()](#addGrayScaleEffect--) | افکت جدید Gray Scale را به انتهای یک مجموعه اضافه می‌کند. |
| [addHSLEffect(float hue, float saturation, float luminance)](#addHSLEffect-float-float-float-) | افکت جدید Hue/Saturation/Luminance را به انتهای یک مجموعه اضافه می‌کند. |
| [addLuminanceEffect(float brightness, float contrast)](#addLuminanceEffect-float-float-) | افکت جدید Luminance را به انتهای یک مجموعه اضافه می‌کند. |
| [addTintEffect(float hue, float amount)](#addTintEffect-float-float-) | افکت جدید Tint را به انتهای یک مجموعه اضافه می‌کند. |
| [addBrightnessContrastEffect(float brightness, float contrast)](#addBrightnessContrastEffect-float-float-) | افکت جدید BrightnessContrast را به انتهای یک مجموعه اضافه می‌کند. |
| [size()](#size--) | تعداد افکت‌های تصویر در یک مجموعه را برمی‌گرداند. |
| [isReadOnly()](#isReadOnly--) | مقدار نشان‌دهنده اینکه آیا [IGenericCollection](../../com.aspose.slides/igenericcollection) فقط‌قابل‌خواندن است را دریافت می‌کند. |
| [addItem(IImageTransformOperation operation)](#addItem-com.aspose.slides.IImageTransformOperation-) | افکت تصویر جدید را به انتهای یک مجموعه اضافه می‌کند. |
| [clear()](#clear--) | تمام افکت‌های تصویر را از یک مجموعه حذف می‌کند. |
| [containsItem(IImageTransformOperation item)](#containsItem-com.aspose.slides.IImageTransformOperation-) | تعیین می‌کند آیا [IGenericCollection](../../com.aspose.slides/igenericcollection) شامل مقدار خاصی است یا خیر. |
| [copyToTArray(IImageTransformOperation[] array, int arrayIndex)](#copyToTArray-com.aspose.slides.IImageTransformOperation---int-) | عناصر [IGenericCollection](../../com.aspose.slides/igenericcollection) را به آرایه‌ای کپی می‌کند، شروع از ایندکس مشخص آرایه. |
| [removeItem(IImageTransformOperation item)](#removeItem-com.aspose.slides.IImageTransformOperation-) | اولین رخداد شیء خاص را از [IGenericCollection](../../com.aspose.slides/igenericcollection) حذف می‌کند. |
| [iterator()](#iterator--) | یک شمارنده برمی‌گرداند که از مجموعه پیمایش می‌کند. |
| [iteratorJava()](#iteratorJava--) | یک iterator جاوا برای تمام مجموعه برمی‌گرداند. |

### getVersion() {#getVersion--}
```
public long getVersion()
```

نسخه. long فقط‌قابل‌خواندن.

**برمی‌گرداند:**
long

### get_Item(int index) {#get-Item-int-}
```
public final IImageTransformOperation get_Item(int index)
```

یک [ImageTransformOperation](../../com.aspose.slides/imagetransformoperation) را از مجموعه با شاخص آن برمی‌گرداند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int | شاخص عنصر. |

**برمی‌گرداند:**
[IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation) - شیء [IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation)

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

یک افکت تصویر را از مجموعه در شاخص مشخص حذف می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int | شاخص افکت تصویری که باید حذف شود. |

### addAlphaBiLevelEffect(float threshold) {#addAlphaBiLevelEffect-float-}
```
public final IAlphaBiLevel addAlphaBiLevelEffect(float threshold)
```

افکت جدید Alpha Bi-Level را به انتهای یک مجموعه اضافه می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| threshold | float | مقدار آستانه برای افکت Alpha Bi-Level. |

**برمی‌گرداند:**
[IAlphaBiLevel](../../com.aspose.slides/ialphabilevel) - ایندکس افکت تصویر جدید در مجموعه.

### addAlphaCeilingEffect() {#addAlphaCeilingEffect--}
```
public final IAlphaCeiling addAlphaCeilingEffect()
```

افکت جدید Alpha Ceiling را به انتهای یک مجموعه اضافه می‌کند.

**برمی‌گرداند:**
[IAlphaCeiling](../../com.aspose.slides/ialphaceiling) - ایندکس افکت تصویر جدید در مجموعه.

### addAlphaFloorEffect() {#addAlphaFloorEffect--}
```
public final IAlphaFloor addAlphaFloorEffect()
```

افکت جدید Alpha Floor را به انتهای یک مجموعه اضافه می‌کند.

**برمی‌گرداند:**
[IAlphaFloor](../../com.aspose.slides/ialphafloor) - ایندکس افکت تصویر جدید در مجموعه.

### addAlphaInverseEffect() {#addAlphaInverseEffect--}
```
public final IAlphaInverse addAlphaInverseEffect()
```

افکت جدید Alpha Inverse را به انتهای یک مجموعه اضافه می‌کند.

**برمی‌گرداند:**
[IAlphaInverse](../../com.aspose.slides/ialphainverse) - ایندکس افکت تصویر جدید در مجموعه.

### addAlphaModulateEffect() {#addAlphaModulateEffect--}
```
public final IAlphaModulate addAlphaModulateEffect()
```

افکت جدید Alpha Modulate را به انتهای یک مجموعه اضافه می‌کند.

**برمی‌گرداند:**
[IAlphaModulate](../../com.aspose.slides/ialphamodulate) - ایندکس افکت تصویر جدید در مجموعه.

### addAlphaModulateFixedEffect(float amount) {#addAlphaModulateFixedEffect-float-}
```
public final IAlphaModulateFixed addAlphaModulateFixedEffect(float amount)
```

افکت جدید Alpha Modulate Fixed را به انتهای یک مجموعه اضافه می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| amount | float | مقدار درصدی برای مقیاس‌بندی آلفا. |

**برمی‌گرداند:**
[IAlphaModulateFixed](../../com.aspose.slides/ialphamodulatefixed) - ایندکس افکت تصویر جدید در مجموعه.

### addAlphaReplaceEffect(float alpha) {#addAlphaReplaceEffect-float-}
```
public final IAlphaReplace addAlphaReplaceEffect(float alpha)
```

افکت جدید Alpha Replace را به انتهای یک مجموعه اضافه می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| alpha | float | مقدار جدید شفافیت. |

**برمی‌گرداند:**
[IAlphaReplace](../../com.aspose.slides/ialphareplace) - ایندکس افکت تصویر جدید در مجموعه.

### addBiLevelEffect(float threshold) {#addBiLevelEffect-float-}
```
public final IBiLevel addBiLevelEffect(float threshold)
```

افکت جدید Bi-Level (black/white) را به انتهای یک مجموعه اضافه می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| threshold | float | آستانه روشنایی برای افکت Bi-Level. مقادیر برابر یا بزرگ‌تر از آستانه به سفید تنظیم می‌شوند. مقادیر کمتر به سیاه تنظیم می‌شوند. |

**برمی‌گرداند:**
[IBiLevel](../../com.aspose.slides/ibilevel) - ایندکس افکت تصویر جدید در مجموعه.

### addBlurEffect(double radius, boolean grow) {#addBlurEffect-double-boolean-}
```
public final IBlur addBlurEffect(double radius, boolean grow)
```

افکت جدید Blur را به انتهای یک مجموعه اضافه می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| radius | double | شعاع تاری. |
| grow | boolean | مشخص می‌کند که مرزهای شیء پس از تاری بزرگ شوند یا نه. مقدار true مرزها را بزرگ می‌کند؛ false مرزها را ثابت نگه می‌دارد. |

**برمی‌گرداند:**
[IBlur](../../com.aspose.slides/iblur) - ایندکس افکت تصویر جدید در مجموعه.

### addColorChangeEffect() {#addColorChangeEffect--}
```
public final IColorChange addColorChangeEffect()
```

افکت جدید Color Change را به انتهای یک مجموعه اضافه می‌کند.

**برمی‌گرداند:**
[IColorChange](../../com.aspose.slides/icolorchange) - ایندکس افکت تصویر جدید در مجموعه.

### addColorReplaceEffect() {#addColorReplaceEffect--}
```
public final IColorReplace addColorReplaceEffect()
```

افکت جدید Color Replacement را به انتهای یک مجموعه اضافه می‌کند.

**برمی‌گرداند:**
[IColorReplace](../../com.aspose.slides/icolorreplace) - ایندکس افکت تصویر جدید در مجموعه.

### addDuotoneEffect() {#addDuotoneEffect--}
```
public final IDuotone addDuotoneEffect()
```

افکت جدید Duotone را به انتهای یک مجموعه اضافه می‌کند.

**برمی‌گرداند:**
[IDuotone](../../com.aspose.slides/iduotone) - ایندکس افکت تصویر جدید در مجموعه.

### addFillOverlayEffect() {#addFillOverlayEffect--}
```
public final IFillOverlay addFillOverlayEffect()
```

افکت جدید Fill Overlay را به انتهای یک مجموعه اضافه می‌کند.

**برمی‌گرداند:**
[IFillOverlay](../../com.aspose.slides/ifilloverlay) - ایندکس افکت تصویر جدید در مجموعه.

### addGrayScaleEffect() {#addGrayScaleEffect--}
```
public final IGrayScale addGrayScaleEffect()
```

افکت جدید Gray Scale را به انتهای یک مجموعه اضافه می‌کند.

**برمی‌گرداند:**
[IGrayScale](../../com.aspose.slides/igrayscale) - ایندکس افکت تصویر جدید در مجموعه.

### addHSLEffect(float hue, float saturation, float luminance) {#addHSLEffect-float-float-float-}
```
public final IHSL addHSLEffect(float hue, float saturation, float luminance)
```

افکت جدید Hue/Saturation/Luminance را به انتهای یک مجموعه اضافه می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| hue | float | تعداد درجه‌های تنظیم شدنی هیو. |
| saturation | float | درصد تنظیم شدنی اشباع. |
| luminance | float | درصد تنظیم شدنی روشنایی. |

**برمی‌گرداند:**
[IHSL](../../com.aspose.slides/ihsl) - ایندکس افکت تصویر جدید در مجموعه.

### addLuminanceEffect(float brightness, float contrast) {#addLuminanceEffect-float-float-}
```
public final ILuminance addLuminanceEffect(float brightness, float contrast)
```

افکت جدید Luminance را به انتهای یک مجموعه اضافه می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| brightness | float | درصد تغییر روشنایی. |
| contrast | float | درصد تغییر کنتراست. |

**برمی‌گرداند:**
[ILuminance](../../com.aspose.slides/iluminance) - ایندکس افکت تصویر جدید در مجموعه.

### addTintEffect(float hue, float amount) {#addTintEffect-float-float-}
```
public final ITint addTintEffect(float hue, float amount)
```

افکت جدید Tint را به انتهای یک مجموعه اضافه می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| hue | float | هیو جهت رنگ‌آمیزی. |
| amount | float | میزان جابه‌جایی مقدار رنگ. |

**برمی‌گرداند:**
[ITint](../../com.aspose.slides/itint) - ایندکس افکت تصویر جدید در مجموعه.

### addBrightnessContrastEffect(float brightness, float contrast) {#addBrightnessContrastEffect-float-float-}
```
public final IBrightnessContrast addBrightnessContrastEffect(float brightness, float contrast)
```

افکت جدید BrightnessContrast را به انتهای یک مجموعه اضافه می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| brightness | float | درصد تغییر روشنایی. |
| contrast | float | درصد تغییر کنتراست. |

**برمی‌گرداند:**
[IBrightnessContrast](../../com.aspose.slides/ibrightnesscontrast) - ایندکس افکت تصویر جدید در مجموعه.

### size() {#size--}
```
public final int size()
```

تعداد افکت‌های تصویر در یک مجموعه را برمی‌گرداند. int فقط‌قابل‌خواندن.

**برمی‌گرداند:**
int

### isReadOnly() {#isReadOnly--}
```
public final boolean isReadOnly()
```

مقداری که نشان می‌دهد آیا [IGenericCollection](../../com.aspose.slides/igenericcollection) فقط‌قابل‌خواندن است را دریافت می‌کند. boolean فقط‌قابل‌خواندن.

**برمی‌گرداند:**
boolean - درست اگر [IGenericCollection](../../com.aspose.slides/igenericcollection) فقط‌قابل‌خواندن باشد؛ در غیر این صورت، نادرست.

### addItem(IImageTransformOperation operation) {#addItem-com.aspose.slides.IImageTransformOperation-}
```
public final void addItem(IImageTransformOperation operation)
```

افکت تصویر جدید را به انتهای یک مجموعه اضافه می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| operation | [IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation) | افکت تصویر برای افزودن به انتهای مجموعه. |

### clear() {#clear--}
```
public final void clear()
```

تمام افکت‌های تصویر را از یک مجموعه حذف می‌کند.

### containsItem(IImageTransformOperation item) {#containsItem-com.aspose.slides.IImageTransformOperation-}
```
public final boolean containsItem(IImageTransformOperation item)
```

تعیین می‌کند آیا [IGenericCollection](../../com.aspose.slides/igenericcollection) شامل مقدار خاصی است یا خیر.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| item | [IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation) | شیء برای جستجو در [IGenericCollection](../../com.aspose.slides/igenericcollection). |

**برمی‌گرداند:**
boolean - درست اگر شیء در [IGenericCollection](../../com.aspose.slides/igenericcollection) یافت شد؛ در غیر این صورت، نادرست.

### copyToTArray(IImageTransformOperation[] array, int arrayIndex) {#copyToTArray-com.aspose.slides.IImageTransformOperation---int-}
```
public final void copyToTArray(IImageTransformOperation[] array, int arrayIndex)
```

عناصر [IGenericCollection](../../com.aspose.slides/igenericcollection) را به آرایه‌ای کپی می‌کند، شروع از ایندکس مشخص آرایه.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| array | [IImageTransformOperation\[\]](../../com.aspose.slides/iimagetransformoperation) | آرایهٔ تک‌بعدی مقصد برای عناصری که از [IGenericCollection](../../com.aspose.slides/igenericcollection) کپی می‌شوند. آرایه باید ایندکس مبتنی بر صفر داشته باشد. |
| arrayIndex | int | ایندکس مبتنی بر صفر در آرایه که از آن کپی آغاز می‌شود. |

### removeItem(IImageTransformOperation item) {#removeItem-com.aspose.slides.IImageTransformOperation-}
```
public final boolean removeItem(IImageTransformOperation item)
```

اولین رخداد شیء خاص را از [IGenericCollection](../../com.aspose.slides/igenericcollection) حذف می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| item | [IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation) | شیء برای حذف از [IGenericCollection](../../com.aspose.slides/igenericcollection). |

**برمی‌گرداند:**
boolean - درست اگر شیء با موفقیت از [IGenericCollection](../../com.aspose.slides/igenericcollection) حذف شد؛ در غیر این صورت، نادرست. این متد همچنین در صورتی که شیء در [IGenericCollection](../../com.aspose.slides/igenericcollection) اصلی یافت نشود، false باز می‌گرداند.

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IImageTransformOperation> iterator()
```

یک شمارنده برمی‌گرداند که از مجموعه پیمایش می‌کند.

**برمی‌گرداند:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IImageTransformOperation> - یک IGenericEnumerator که می‌تواند برای پیمایش مجموعه استفاده شود.

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IImageTransformOperation> iteratorJava()
```

یک iterator جاوا برای تمام مجموعه برمی‌گرداند.

**برمی‌گرداند:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IImageTransformOperation> - یک java.util.Iterator برای تمام مجموعه.