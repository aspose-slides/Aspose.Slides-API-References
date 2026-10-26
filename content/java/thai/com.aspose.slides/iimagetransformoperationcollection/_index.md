---
title: IImageTransformOperationCollection
second_title: เอกสารอ้างอิง API ของ Aspose.Slides สำหรับ Java
description: เป็นคอลเลกชันของเอฟเฟกต์ที่ใช้กับภาพ.
type: docs
url: /th/com.aspose.slides/iimagetransformoperationcollection/
---
**ส่วนติดต่อที่ทำการดำเนินการทั้งหมด:**
com.aspose.ms.System.Collections.Generic.IGenericCollection
```
public interface IImageTransformOperationCollection extends System.Collections.Generic.IGenericCollection<IImageTransformOperation>
```

เป็นคอลเลกชันของเอฟเฟกต์ที่ใช้กับภาพ
## วิธีการ

| เมธอด | คำอธิบาย |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | คืนค่า [IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation) จากคอลเลกชันโดยใช้ดัชนีของมัน. |
| [removeAt(int index)](#removeAt-int-) | ลบเอฟเฟกต์รูปภาพจากคอลเลกชันตามดัชนีที่ระบุ. |
| [addAlphaBiLevelEffect(float threshold)](#addAlphaBiLevelEffect-float-) | เพิ่มเอฟเฟกต์ Alpha Bi-Level ใหม่ที่ส่วนท้ายของคอลเลกชัน. |
| [addAlphaCeilingEffect()](#addAlphaCeilingEffect--) | เพิ่มเอฟเฟกต์ Alpha Ceiling ใหม่ที่ส่วนท้ายของคอลเลกชัน. |
| [addAlphaFloorEffect()](#addAlphaFloorEffect--) | เพิ่มเอฟเฟกต์ Alpha Floor ใหม่ที่ส่วนท้ายของคอลเลกชัน. |
| [addAlphaInverseEffect()](#addAlphaInverseEffect--) | เพิ่มเอฟเฟกต์ Alpha Inverse ใหม่ที่ส่วนท้ายของคอลเลกชัน. |
| [addAlphaModulateEffect()](#addAlphaModulateEffect--) | เพิ่มเอฟเฟกต์ Alpha Modulate ใหม่ที่ส่วนท้ายของคอลเลกชัน. |
| [addAlphaModulateFixedEffect(float amount)](#addAlphaModulateFixedEffect-float-) | เพิ่มเอฟเฟกต์ Alpha Modulate Fixed ใหม่ที่ส่วนท้ายของคอลเลกชัน. |
| [addAlphaReplaceEffect(float alpha)](#addAlphaReplaceEffect-float-) | เพิ่มเอฟเฟกต์ Alpha Replace ใหม่ที่ส่วนท้ายของคอลเลกชัน. |
| [addBiLevelEffect(float threshold)](#addBiLevelEffect-float-) | เพิ่มเอฟเฟกต์ Bi-Level (black/white) ใหม่ที่ส่วนท้ายของคอลเลกชัน. |
| [addBlurEffect(double radius, boolean grow)](#addBlurEffect-double-boolean-) | เพิ่มเอฟเฟกต์ Blur ใหม่ที่ส่วนท้ายของคอลเลกชัน. |
| [addColorChangeEffect()](#addColorChangeEffect--) | เพิ่มเอฟเฟกต์ Color Change ใหม่ที่ส่วนท้ายของคอลเลกชัน. |
| [addColorReplaceEffect()](#addColorReplaceEffect--) | เพิ่มเอฟเฟกต์ Color Replacement ใหม่ที่ส่วนท้ายของคอลเลกชัน. |
| [addDuotoneEffect()](#addDuotoneEffect--) | เพิ่มเอฟเฟกต์ Duotone ใหม่ที่ส่วนท้ายของคอลเลกชัน. |
| [addFillOverlayEffect()](#addFillOverlayEffect--) | เพิ่มเอฟเฟกต์ Fill Overlay ใหม่ที่ส่วนท้ายของคอลเลกชัน. |
| [addGrayScaleEffect()](#addGrayScaleEffect--) | เพิ่มเอฟเฟกต์ Gray Scale ใหม่ที่ส่วนท้ายของคอลเลกชัน. |
| [addHSLEffect(float hue, float saturation, float luminance)](#addHSLEffect-float-float-float-) | เพิ่มเอฟเฟกต์ Hue/Saturation/Luminance ใหม่ที่ส่วนท้ายของคอลเลกชัน. |
| [addLuminanceEffect(float brightness, float contrast)](#addLuminanceEffect-float-float-) | เพิ่มเอฟเฟกต์ Luminance ใหม่ที่ส่วนท้ายของคอลเลกชัน. |
| [addTintEffect(float hue, float amount)](#addTintEffect-float-float-) | เพิ่มเอฟเฟกต์ Tint ใหม่ที่ส่วนท้ายของคอลเลกชัน. |
| [addBrightnessContrastEffect(float brightness, float contrast)](#addBrightnessContrastEffect-float-float-) | เพิ่มเอฟเฟกต์ BrightnessContrast ใหม่ที่ส่วนท้ายของคอลเลกชัน. |

### get_Item(int index) {#get-Item-int-}
```
public abstract IImageTransformOperation get_Item(int index)
```

คืนค่า [IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation) จากคอลเลกชันโดยใช้ดัชนีของมัน.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| index | int | ดัชนีของรายการ. |

**คืนค่า:**
[IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation) - วัตถุ [IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation)

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

ลบเอฟเฟกต์รูปภาพจากคอลเลกชันตามดัชนีที่ระบุ.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| index | int | ดัชนีของเอฟเฟกต์รูปภาพที่ต้องการลบ. |

### addAlphaBiLevelEffect(float threshold) {#addAlphaBiLevelEffect-float-}
```
public abstract IAlphaBiLevel addAlphaBiLevelEffect(float threshold)
```

เพิ่มเอฟเฟกต์ Alpha Bi-Level ใหม่ที่ส่วนท้ายของคอลเลกชัน.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| threshold | float | ค่าขีดจำกัดสำหรับเอฟเฟกต์ Alpha Bi-Level. |

**คืนค่า:**
[IAlphaBiLevel](../../com.aspose.slides/ialphabilevel) - ดัชนีของเอฟเฟกต์รูปภาพใหม่ในคอลเลกชัน.

### addAlphaCeilingEffect() {#addAlphaCeilingEffect--}
```
public abstract IAlphaCeiling addAlphaCeilingEffect()
```

เพิ่มเอฟเฟกต์ Alpha Ceiling ใหม่ที่ส่วนท้ายของคอลเลกชัน.

**คืนค่า:**
[IAlphaCeiling](../../com.aspose.slides/ialphaceiling) - ดัชนีของเอฟเฟกต์รูปภาพใหม่ในคอลเลกชัน.

### addAlphaFloorEffect() {#addAlphaFloorEffect--}
```
public abstract IAlphaFloor addAlphaFloorEffect()
```

เพิ่มเอฟเฟกต์ Alpha Floor ใหม่ที่ส่วนท้ายของคอลเลกชัน.

**คืนค่า:**
[IAlphaFloor](../../com.aspose.slides/ialphafloor) - ดัชนีของเอฟเฟกต์รูปภาพใหม่ในคอลเลกชัน.

### addAlphaInverseEffect() {#addAlphaInverseEffect--}
```
public abstract IAlphaInverse addAlphaInverseEffect()
```

เพิ่มเอฟเฟกต์ Alpha Inverse ใหม่ที่ส่วนท้ายของคอลเลกชัน.

**คืนค่า:**
[IAlphaInverse](../../com.aspose.slides/ialphainverse) - ดัชนีของเอฟเฟกต์รูปภาพใหม่ในคอลเลกชัน.

### addAlphaModulateEffect() {#addAlphaModulateEffect--}
```
public abstract IAlphaModulate addAlphaModulateEffect()
```

เพิ่มเอฟเฟกต์ Alpha Modulate ใหม่ที่ส่วนท้ายของคอลเลกชัน.

**คืนค่า:**
[IAlphaModulate](../../com.aspose.slides/ialphamodulate) - ดัชนีของเอฟเฟกต์รูปภาพใหม่ในคอลเลกชัน.

### addAlphaModulateFixedEffect(float amount) {#addAlphaModulateFixedEffect-float-}
```
public abstract IAlphaModulateFixed addAlphaModulateFixedEffect(float amount)
```

เพิ่มเอฟเฟกต์ Alpha Modulate Fixed ใหม่ที่ส่วนท้ายของคอลเลกชัน.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| amount | float | จำนวนเปอร์เซ็นต์ที่ใช้ปรับสเกลค่า alpha. |

**คืนค่า:**
[IAlphaModulateFixed](../../com.aspose.slides/ialphamodulatefixed) - ดัชนีของเอฟเฟกต์รูปภาพใหม่ในคอลเลกชัน.

### addAlphaReplaceEffect(float alpha) {#addAlphaReplaceEffect-float-}
```
public abstract IAlphaReplace addAlphaReplaceEffect(float alpha)
```

เพิ่มเอฟเฟกต์ Alpha Replace ใหม่ที่ส่วนท้ายของคอลเลกชัน.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| alpha | float | ค่าความทึบใหม่. |

**คืนค่า:**
[IAlphaReplace](../../com.aspose.slides/ialphareplace) - ดัชนีของเอฟเฟกต์รูปภาพใหม่ในคอลเลกชัน.

### addBiLevelEffect(float threshold) {#addBiLevelEffect-float-}
```
public abstract IBiLevel addBiLevelEffect(float threshold)
```

เพิ่มเอฟเฟกต์ Bi-Level (black/white) ใหม่ที่ส่วนท้ายของคอลเลกชัน.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| threshold | float | ค่าขีดจำกัดความสว่างสำหรับเอฟเฟกต์ Bi-Level. ค่าที่เท่ากับหรือมากกว่าเกณฑ์จะตั้งเป็นสีขาว ค่าที่น้อยกว่าจะตั้งเป็นสีดำ. |

**คืนค่า:**
[IBiLevel](../../com.aspose.slides/ibilevel) - ดัชนีของเอฟเฟกต์รูปภาพใหม่ในคอลเลกชัน.

### addBlurEffect(double radius, boolean grow) {#addBlurEffect-double-boolean-}
```
public abstract IBlur addBlurEffect(double radius, boolean grow)
```

เพิ่มเอฟเฟกต์ Blur ใหม่ที่ส่วนท้ายของคอลเลกชัน.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| radius | double | รัศมีของการเบลอ. |
| grow | boolean | ระบุว่าขอบเขตของวัตถุควรขยายออกตามการเบลอหรือไม่. true หมายถึงขอบเขตขยาย, false หมายถึงไม่ขยาย. |

**คืนค่า:**
[IBlur](../../com.aspose.slides/iblur) - ดัชนีของเอฟเฟกต์รูปภาพใหม่ในคอลเลกชัน.

### addColorChangeEffect() {#addColorChangeEffect--}
```
public abstract IColorChange addColorChangeEffect()
```

เพิ่มเอฟเฟกต์ Color Change ใหม่ที่ส่วนท้ายของคอลเลกชัน.

**คืนค่า:**
[IColorChange](../../com.aspose.slides/icolorchange) - ดัชนีของเอฟเฟกต์รูปภาพใหม่ในคอลเลกชัน.

### addColorReplaceEffect() {#addColorReplaceEffect--}
```
public abstract IColorReplace addColorReplaceEffect()
```

เพิ่มเอฟเฟกต์ Color Replacement ใหม่ที่ส่วนท้ายของคอลเลกชัน.

**คืนค่า:**
[IColorReplace](../../com.aspose.slides/icolorreplace) - ดัชนีของเอฟเฟกต์รูปภาพใหม่ในคอลเลกชัน.

### addDuotoneEffect() {#addDuotoneEffect--}
```
public abstract IDuotone addDuotoneEffect()
```

เพิ่มเอฟเฟกต์ Duotone ใหม่ที่ส่วนท้ายของคอลเลกชัน.

**คืนค่า:**
[IDuotone](../../com.aspose.slides/iduotone) - ดัชนีของเอฟเฟกต์รูปภาพใหม่ในคอลเลกชัน.

### addFillOverlayEffect() {#addFillOverlayEffect--}
```
public abstract IFillOverlay addFillOverlayEffect()
```

เพิ่มเอฟเฟกต์ Fill Overlay ใหม่ที่ส่วนท้ายของคอลเลกชัน.

**คืนค่า:**
[IFillOverlay](../../com.aspose.slides/ifilloverlay) - ดัชนีของเอฟเฟกต์รูปภาพใหม่ในคอลเลกชัน.

### addGrayScaleEffect() {#addGrayScaleEffect--}
```
public abstract IGrayScale addGrayScaleEffect()
```

เพิ่มเอฟเฟกต์ Gray Scale ใหม่ที่ส่วนท้ายของคอลเลกชัน.

**คืนค่า:**
[IGrayScale](../../com.aspose.slides/igrayscale) - ดัชนีของเอฟเฟกต์รูปภาพใหม่ในคอลเลกชัน.

### addHSLEffect(float hue, float saturation, float luminance) {#addHSLEffect-float-float-float-}
```
public abstract IHSL addHSLEffect(float hue, float saturation, float luminance)
```

เพิ่มเอฟเฟกต์ Hue/Saturation/Luminance ใหม่ที่ส่วนท้ายของคอลเลกชัน.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| hue | float | จำนวนองศาที่ปรับค่า hue. |
| saturation | float | เปอร์เซ็นต์ที่ปรับค่า saturation. |
| luminance | float | เปอร์เซ็นต์ที่ปรับค่า luminance. |

**คืนค่า:**
[IHSL](../../com.aspose.slides/ihsl) - ดัชนีของเอฟเฟกต์รูปภาพใหม่ในคอลเลกชัน.

### addLuminanceEffect(float brightness, float contrast) {#addLuminanceEffect-float-float-}
```
public abstract ILuminance addLuminanceEffect(float brightness, float contrast)
```

เพิ่มเอฟเฟกต์ Luminance ใหม่ที่ส่วนท้ายของคอลเลกชัน.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| brightness | float | เปอร์เซ็นต์ที่ปรับความสว่าง. |
| contrast | float | เปอร์เซ็นต์ที่ปรับความคอนทราสต์. |

**คืนค่า:**
[ILuminance](../../com.aspose.slides/iluminance) - ดัชนีของเอฟเฟกต์รูปภาพใหม่ในคอลเลกชัน.

### addTintEffect(float hue, float amount) {#addTintEffect-float-float-}
```
public abstract ITint addTintEffect(float hue, float amount)
```

เพิ่มเอฟเฟกต์ Tint ใหม่ที่ส่วนท้ายของคอลเลกชัน.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| hue | float | สี hue ที่ใช้ในการทำ tint. |
| amount | float | ระบุปริมาณที่ค่าของสีถูกเลื่อน. |

**คืนค่า:**
[ITint](../../com.aspose.slides/itint) - ดัชนีของเอฟเฟกต์รูปภาพใหม่ในคอลเลกชัน.

### addBrightnessContrastEffect(float brightness, float contrast) {#addBrightnessContrastEffect-float-float-}
```
public abstract IBrightnessContrast addBrightnessContrastEffect(float brightness, float contrast)
```

เพิ่มเอฟเฟกต์ BrightnessContrast ใหม่ที่ส่วนท้ายของคอลเลกชัน.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| brightness | float | เปอร์เซ็นต์ที่ปรับความสว่าง. |
| contrast | float | เปอร์เซ็นต์ที่ปรับความคอนทราสต์. |

**คืนค่า:**
[IBrightnessContrast](../../com.aspose.slides/ibrightnesscontrast) - ดัชนีของเอฟเฟกต์รูปภาพใหม่ในคอลเลกชัน.