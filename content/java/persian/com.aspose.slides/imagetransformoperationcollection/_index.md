---
title: ImageTransformOperationCollection
second_title: مرجع API Aspose.Slides برای Java
description: نمایش‌دهنده‌ی مجموعه‌ای از افکت‌های اعمال‌شده بر یک تصویر.
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

نمایش‌دهنده‌ی مجموعه‌ای از افکت‌های اعمال‌شده بر یک تصویر.

## روش‌ها

| متد | توضیح |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [get_Item(int index)](#get-Item-int-) | یک [ImageTransformOperation](../../com.aspose.slides/imagetransformoperation) را از مجموعه بر اساس شاخص آن بر می‌گرداند. |
| [removeAt(int index)](#removeAt-int-) | یک اثر تصویر را از مجموعه در شاخص مشخص حذف می‌کند. |
| [addAlphaBiLevelEffect(float threshold)](#addAlphaBiLevelEffect-float-) | اثر Alpha Bi-Level جدید را به انتهای یک مجموعه اضافه می‌کند. |
| [addAlphaCeilingEffect()](#addAlphaCeilingEffect--) | اثر Alpha Ceiling جدید را به انتهای یک مجموعه اضافه می‌کند. |
| [addAlphaFloorEffect()](#addAlphaFloorEffect--) | اثر Alpha Floor جدید را به انتهای یک مجموعه اضافه می‌کند. |
| [addAlphaInverseEffect()](#addAlphaInverseEffect--) | اثر Alpha Inverse جدید را به انتهای یک مجموعه اضافه می‌کند. |
| [addAlphaModulateEffect()](#addAlphaModulateEffect--) | اثر Alpha Modulate جدید را به انتهای یک مجموعه اضافه می‌کند. |
| [addAlphaModulateFixedEffect(float amount)](#addAlphaModulateFixedEffect-float-) | اثر Alpha Modulate Fixed جدید را به انتهای یک مجموعه اضافه می‌کند. |
| [addAlphaReplaceEffect(float alpha)](#addAlphaReplaceEffect-float-) | اثر Alpha Replace جدید را به انتهای یک مجموعه اضافه می‌کند. |
| [addBiLevelEffect(float threshold)](#addBiLevelEffect-float-) | اثر Bi-Level (black/white) جدید را به انتهای یک مجموعه اضافه می‌کند. |
| [addBlurEffect(double radius, boolean grow)](#addBlurEffect-double-boolean-) | اثر Blur جدید را به انتهای یک مجموعه اضافه می‌کند. |
| [addColorChangeEffect()](#addColorChangeEffect--) | اثر Color Change جدید را به انتهای یک مجموعه اضافه می‌کند. |
| [addColorReplaceEffect()](#addColorReplaceEffect--) | اثر Color Replacement جدید را به انتهای یک مجموعه اضافه می‌کند. |
| [addDuotoneEffect()](#addDuotoneEffect--) | اثر Duotone جدید را به انتهای یک مجموعه اضافه می‌کند. |
| [addFillOverlayEffect()](#addFillOverlayEffect--) | اثر Fill Overlay جدید را به انتهای یک مجموعه اضافه می‌کند. |
| [addGrayScaleEffect()](#addGrayScaleEffect--) | اثر Gray Scale جدید را به انتهای یک مجموعه اضافه می‌کند. |
| [addHSLEffect(float hue, float saturation, float luminance)](#addHSLEffect-float-float-float-) | اثر Hue/Saturation/Luminance جدید را به انتهای یک مجموعه اضافه می‌کند. |
| [addLuminanceEffect(float brightness, float contrast)](#addLuminanceEffect-float-float-) | اثر Luminance جدید را به انتهای یک مجموعه اضافه می‌کند. |
| [addTintEffect(float hue, float amount)](#addTintEffect-float-float-) | اثر Tint جدید را به انتهای یک مجموعه اضافه می‌کند. |
| [addBrightnessContrastEffect(float brightness, float contrast)](#addBrightnessContrastEffect-float-float-) | اثر BrightnessContrast جدید را به انتهای یک مجموعه اضافه می‌کند. |
| [size()](#size--) | تعداد اثرهای تصویر در یک مجموعه را بر می‌گرداند. |
| [isReadOnly()](#isReadOnly--) | مقدار نشان‌دهنده این که [IGenericCollection](../../com.aspose.slides/igenericcollection) فقط-خواندنی است را بر می‌گیرد. |
| [addItem(IImageTransformOperation operation)](#addItem-com.aspose.slides.IImageTransformOperation-) | اثر تصویر جدید را به انتهای یک مجموعه اضافه می‌کند. |
| [clear()](#clear--) | تمام اثرهای تصویر را از یک مجموعه حذف می‌کند. |
| [containsItem(IImageTransformOperation item)](#containsItem-com.aspose.slides.IImageTransformOperation-) | تعیین می‌کند که [IGenericCollection](../../com.aspose.slides/igenericcollection) شامل مقدار خاصی است یا نه. |
| [copyToTArray(IImageTransformOperation[] array, int arrayIndex)](#copyToTArray-com.aspose.slides.IImageTransformOperation---int-) | عناصر [IGenericCollection](../../com.aspose.slides/igenericcollection) را به یک Array کپی می‌کند، شروع از یک شاخص Array خاص. |
| [removeItem(IImageTransformOperation item)](#removeItem-com.aspose.slides.IImageTransformOperation-) | اولین رخداد یک شی خاص را از [IGenericCollection](../../com.aspose.slides/igenericcollection) حذف می‌کند. |
| [iterator()](#iterator--) | یک enumerator که در مجموعه تکرار می‌کند را بر می‌گرداند. |
| [iteratorJava()](#iteratorJava--) | یک iterator جاوا برای کل مجموعه بر می‌گرداند. |

### getVersion() {#getVersion--}
```
public long getVersion()
```

نسخه. فقط-خواندنی long.

**بازگشت:**  
long

### get_Item(int index) {#get-Item-int-}
```
public final IImageTransformOperation get_Item(int index)
```

یک [ImageTransformOperation](../../com.aspose.slides/imagetransformoperation) را از مجموعه بر اساس شاخص آن بر می‌گرداند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int | شاخص عنصر. |

**بازگشت:**  
[IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation) - شی [IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation).

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

یک اثر تصویر را از مجموعه در شاخص مشخص حذف می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int | شاخص یک اثر تصویر که باید حذف شود. |

### addAlphaBiLevelEffect(float threshold) {#addAlphaBiLevelEffect-float-}
```
public final IAlphaBiLevel addAlphaBiLevelEffect(float threshold)
```

اثر Alpha Bi-Level جدید را به انتهای یک مجموعه اضافه می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| threshold | float | مقدار آستانه برای اثر Alpha Bi-Level. |

**بازگشت:**  
[IAlphaBiLevel](../../com.aspose.slides/ialphabilevel) - شاخص اثر تصویر جدید در مجموعه.

### addAlphaCeilingEffect() {#addAlphaCeilingEffect--}
```
public final IAlphaCeiling addAlphaCeilingEffect()
```

اثر Alpha Ceiling جدید را به انتهای یک مجموعه اضافه می‌کند.

**بازگشت:**  
[IAlphaCeiling](../../com.aspose.slides/ialphaceiling) - شاخص اثر تصویر جدید در مجموعه.

### addAlphaFloorEffect() {#addAlphaFloorEffect--}
```
public final IAlphaFloor addAlphaFloorEffect()
```

اثر Alpha Floor جدید را به انتهای یک مجموعه اضافه می‌کند.

**بازگشت:**  
[IAlphaFloor](../../com.aspose.slides/ialphafloor) - شاخص اثر تصویر جدید در مجموعه.

### addAlphaInverseEffect() {#addAlphaInverseEffect--}
```
public final IAlphaInverse addAlphaInverseEffect()
```

اثر Alpha Inverse جدید را به انتهای یک مجموعه اضافه می‌کند.

**بازگشت:**  
[IAlphaInverse](../../com.aspose.slides/ialphainverse) - شاخص اثر تصویر جدید در مجموعه.

### addAlphaModulateEffect() {#addAlphaModulateEffect--}
```
public final IAlphaModulate addAlphaModulateEffect()
```

اثر Alpha Modulate جدید را به انتهای یک مجموعه اضافه می‌کند.

**بازگشت:**  
[IAlphaModulate](../../com.aspose.slides/ialphamodulate) - شاخص اثر تصویر جدید در مجموعه.

### addAlphaModulateFixedEffect(float amount) {#addAlphaModulateFixedEffect-float-}
```
public final IAlphaModulateFixed addAlphaModulateFixedEffect(float amount)
```

اثر Alpha Modulate Fixed جدید را به انتهای یک مجموعه اضافه می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| amount | float | درصد مقدار برای مقیاس‌بندی آلفا. |

**بازگشت:**  
[IAlphaModulateFixed](../../com.aspose.slides/ialphamodulatefixed) - شاخص اثر تصویر جدید در مجموعه.

### addAlphaReplaceEffect(float alpha) {#addAlphaReplaceEffect-float-}
```
public final IAlphaReplace addAlphaReplaceEffect(float alpha)
```

اثر Alpha Replace جدید را به انتهای یک مجموعه اضافه می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| alpha | float | مقدار شفافیت جدید. |

**بازگشت:**  
[IAlphaReplace](../../com.aspose.slides/ialphareplace) - شاخص اثر تصویر جدید در مجموعه.

### addBiLevelEffect(float threshold) {#addBiLevelEffect-float-}
```
public final IBiLevel addBiLevelEffect(float threshold)
```

اثر Bi-Level (black/white) جدید را به انتهای یک مجموعه اضافه می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| threshold | float | آستانه روشنایی برای اثر Bi-Level. مقادیر بزرگتر یا مساوی آستانه به سفید تنظیم می‌شوند. مقادیر کمتر به سیاه تنظیم می‌شوند. |

**بازگشت:**  
[IBiLevel](../../com.aspose.slides/ibilevel) - شاخص اثر تصویر جدید در مجموعه.

### addBlurEffect(double radius, boolean grow) {#addBlurEffect-double-boolean-}
```
public final IBlur addBlurEffect(double radius, boolean grow)
```

اثر Blur جدید را به انتهای یک مجموعه اضافه می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| radius | double | شعاع تاری. |
| grow | boolean | تعیین می‌کند که مرزهای شی در نتیجه‌ی تاری افزایش یابد یا نه. مقدار true مرزها را افزایش می‌دهد، false نه. |

**بازگشت:**  
[IBlur](../../com.aspose.slides/iblur) - شاخص اثر تصویر جدید در مجموعه.

### addColorChangeEffect() {#addColorChangeEffect--}
```
public final IColorChange addColorChangeEffect()
```

اثر Color Change جدید را به انتهای یک مجموعه اضافه می‌کند.

**بازگشت:**  
[IColorChange](../../com.aspose.slides/icolorchange) - شاخص اثر تصویر جدید در مجموعه.

### addColorReplaceEffect() {#addColorReplaceEffect--}
```
public final IColorReplace addColorReplaceEffect()
```

اثر Color Replacement جدید را به انتهای یک مجموعه اضافه می‌کند.

**بازگشت:**  
[IColorReplace](../../com.aspose.slides/icolorreplace) - شاخص اثر تصویر جدید در مجموعه.

### addDuotoneEffect() {#addDuotoneEffect--}
```
public final IDuotone addDuotoneEffect()
```

اثر Duotone جدید را به انتهای یک مجموعه اضافه می‌کند.

**بازگشت:**  
[IDuotone](../../com.aspose.slides/iduotone) - شاخص اثر تصویر جدید در مجموعه.

### addFillOverlayEffect() {#addFillOverlayEffect--}
```
public final IFillOverlay addFillOverlayEffect()
```

اثر Fill Overlay جدید را به انتهای یک مجموعه اضافه می‌کند.

**بازگشت:**  
[IFillOverlay](../../com.aspose.slides/ifilloverlay) - شاخص اثر تصویر جدید در مجموعه.

### addGrayScaleEffect() {#addGrayScaleEffect--}
```
public final IGrayScale addGrayScaleEffect()
```

اثر Gray Scale جدید را به انتهای یک مجموعه اضافه می‌کند.

**بازگشت:**  
[IGrayScale](../../com.aspose.slides/igrayscale) - شاخص اثر تصویر جدید در مجموعه.

### addHSLEffect(float hue, float saturation, float luminance) {#addHSLEffect-float-float-float-}
```
public final IHSL addHSLEffect(float hue, float saturation, float luminance)
```

اثر Hue/Saturation/Luminance جدید را به انتهای یک مجموعه اضافه می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| hue | float | تعداد درجه‌ای که hue تنظیم می‌شود. |
| saturation | float | درصدی که saturation تنظیم می‌شود. |
| luminance | float | درصدی که luminance تنظیم می‌شود. |

**بازگشت:**  
[IHSL](../../com.aspose.slides/ihsl) - شاخص اثر تصویر جدید در مجموعه.

### addLuminanceEffect(float brightness, float contrast) {#addLuminanceEffect-float-float-}
```
public final ILuminance addLuminanceEffect(float brightness, float contrast)
```

اثر Luminance جدید را به انتهای یک مجموعه اضافه می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| brightness | float | درصد تغییر روشنایی. |
| contrast | float | درصد تغییر کنتراست. |

**بازگشت:**  
[ILuminance](../../com.aspose.slides/iluminance) - شاخص اثر تصویر جدید در مجموعه.

### addTintEffect(float hue, float amount) {#addTintEffect-float-float-}
```
public final ITint addTintEffect(float hue, float amount)
```

اثر Tint جدید را به انتهای یک مجموعه اضافه می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| hue | float | hue که به سمت آن رنگ می‌شود. |
| amount | float | مقدار جابجایی مقدار رنگ را مشخص می‌کند. |

**بازگشت:**  
[ITint](../../com.aspose.slides/itint) - شاخص اثر تصویر جدید در مجموعه.

### addBrightnessContrastEffect(float brightness, float contrast) {#addBrightnessContrastEffect-float-float-}
```
public final IBrightnessContrast addBrightnessContrastEffect(float brightness, float contrast)
```

اثر BrightnessContrast جدید را به انتهای یک مجموعه اضافه می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| brightness | float | درصد تغییر روشنایی. |
| contrast | float | درصد تغییر کنتراست. |

**بازگشت:**  
[IBrightnessContrast](../../com.aspose.slides/ibrightnesscontrast) - شاخص اثر تصویر جدید در مجموعه.

### size() {#size--}
```
public final int size()
```

تعداد اثرهای تصویر در یک مجموعه را بر می‌گرداند. فقط-خواندنی int.

**بازگشت:**  
int

### isReadOnly() {#isReadOnly--}
```
public final boolean isReadOnly()
```

مقدار نشان‌دهنده این که [IGenericCollection](../../com.aspose.slides/igenericcollection) فقط-خواندنی است را بر می‌گیرد. فقط-خواندنی boolean.

**بازگشت:**  
boolean - true اگر [IGenericCollection](../../com.aspose.slides/igenericcollection) فقط-خواندنی باشد؛ در غیر این صورت false.

### addItem(IImageTransformOperation operation) {#addItem-com.aspose.slides.IImageTransformOperation-}
```
public final void addItem(IImageTransformOperation operation)
```

اثر تصویر جدید را به انتهای یک مجموعه اضافه می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| operation | [IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation) | اثر تصویر برای اضافه شدن به انتهای یک مجموعه. |

### clear() {#clear--}
```
public final void clear()
```

تمام اثرهای تصویر را از یک مجموعه حذف می‌کند.

### containsItem(IImageTransformOperation item) {#containsItem-com.aspose.slides.IImageTransformOperation-}
```
public final boolean containsItem(IImageTransformOperation item)
```

تعیین می‌کند که [IGenericCollection](../../com.aspose.slides/igenericcollection) شامل مقدار خاصی است یا نه.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| item | [IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation) | شی برای یافتن در [IGenericCollection](../../com.aspose.slides/igenericcollection). |

**بازگشت:**  
boolean - true اگر مورد در [IGenericCollection](../../com.aspose.slides/igenericcollection) یافت شود؛ در غیر این صورت false.

### copyToTArray(IImageTransformOperation[] array, int arrayIndex) {#copyToTArray-com.aspose.slides.IImageTransformOperation---int-}
```
public final void copyToTArray(IImageTransformOperation[] array, int arrayIndex)
```

عناصر [IGenericCollection](../../com.aspose.slides/igenericcollection) را به یک Array کپی می‌کند، شروع از یک شاخص Array خاص.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| array | [IImageTransformOperation\[\]](../../com.aspose.slides/iimagetransformoperation) | Array یک‌بعدی که مقصد عناصر کپی‌شده از [IGenericCollection](../../com.aspose.slides/igenericcollection) است. Array باید دارای ایندکس صفر-محور باشد. |
| arrayIndex | int | ایندکس صفر-محور در array که کپی از آن شروع می‌شود. |

### removeItem(IImageTransformOperation item) {#removeItem-com.aspose.slides.IImageTransformOperation-}
```
public final boolean removeItem(IImageTransformOperation item)
```

اولین رخداد یک شی خاص را از [IGenericCollection](../../com.aspose.slides/igenericcollection) حذف می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| item | [IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation) | شی برای حذف از [IGenericCollection](../../com.aspose.slides/igenericcollection). |

**بازگشت:**  
boolean - true اگر  item  با موفقیت از [IGenericCollection](../../com.aspose.slides/igenericcollection) حذف شد؛ در غیر این صورت false. این متد همچنین false برمی‌گرداند اگر مورد در [IGenericCollection](../../com.aspose.slides/igenericcollection) اصلی یافت نشود.

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IImageTransformOperation> iterator()
```

یک enumerator که در مجموعه تکرار می‌کند را بر می‌گرداند.

**بازگشت:**  
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IImageTransformOperation> - یک IGenericEnumerator که می‌تواند برای تکرار در مجموعه استفاده شود.

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IImageTransformOperation> iteratorJava()
```

یک iterator جاوا برای کل مجموعه بر می‌گرداند.

**بازگشت:**  
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IImageTransformOperation> - یک java.util.Iterator برای کل مجموعه.