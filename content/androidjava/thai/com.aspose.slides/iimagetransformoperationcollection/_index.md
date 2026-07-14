---
title: IImageTransformOperationCollection
second_title: Aspose.Slides สำหรับ Android ผ่านอ้างอิง API ของ Java
description: แสดงถึงคอลเลกชันของเอฟเฟ็กต์ที่ใช้กับรูปภาพ.
type: docs
url: /th/com.aspose.slides/iimagetransformoperationcollection/
---
**อินเทอร์เฟสที่ทำทั้งหมด:**
com.aspose.ms.System.Collections.Generic.IGenericCollection
```
public interface IImageTransformOperationCollection extends System.Collections.Generic.IGenericCollection<IImageTransformOperation>
```

แสดงถึงคอลเลกชันของเอฟเฟ็กต์ที่ใช้กับรูปภาพ.
## วิธีการ

| วิธีการ | คำอธิบาย |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | ส่งคืน [IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation) จากคอลเลกชันโดยใช้ดัชนีของมัน |
| [removeAt(int index)](#removeAt-int-) | ลบเอฟเฟ็กต์รูปภาพออกจากคอลเลกชันที่ดัชนีที่ระบุ |
| [addAlphaBiLevelEffect(float threshold)](#addAlphaBiLevelEffect-float-) | เพิ่มเอฟเฟ็กต์ Alpha Bi-Level ใหม่ที่ส่วนท้ายของคอลเลกชัน |
| [addAlphaCeilingEffect()](#addAlphaCeilingEffect--) | เพิ่มเอฟเฟ็กต์ Alpha Ceiling ใหม่ที่ส่วนท้ายของคอลเลกชัน |
| [addAlphaFloorEffect()](#addAlphaFloorEffect--) | เพิ่มเอฟเฟ็กต์ Alpha Floor ใหม่ที่ส่วนท้ายของคอลเลกชัน |
| [addAlphaInverseEffect()](#addAlphaInverseEffect--) | เพิ่มเอฟเฟ็กต์ Alpha Inverse ใหม่ที่ส่วนท้ายของคอลเลกชัน |
| [addAlphaModulateEffect()](#addAlphaModulateEffect--) | เพิ่มเอฟเฟ็กต์ Alpha Modulate ใหม่ที่ส่วนท้ายของคอลเลกชัน |
| [addAlphaModulateFixedEffect(float amount)](#addAlphaModulateFixedEffect-float-) | เพิ่มเอฟเฟ็กต์ Alpha Modulate Fixed ใหม่ที่ส่วนท้ายของคอลเลกชัน |
| [addAlphaReplaceEffect(float alpha)](#addAlphaReplaceEffect-float-) | เพิ่มเอฟเฟ็กต์ Alpha Replace ใหม่ที่ส่วนท้ายของคอลเลกชัน |
| [addBiLevelEffect(float threshold)](#addBiLevelEffect-float-) | เพิ่มเอฟเฟ็กต์ Bi-Level (ขาว/ดำ) ใหม่ที่ส่วนท้ายของคอลเลกชัน |
| [addBlurEffect(double radius, boolean grow)](#addBlurEffect-double-boolean-) | เพิ่มเอฟเฟ็กต์ Blur ใหม่ที่ส่วนท้ายของคอลเลกชัน |
| [addColorChangeEffect()](#addColorChangeEffect--) | เพิ่มเอฟเฟ็กต์ Color Change ใหม่ที่ส่วนท้ายของคอลเลกชัน |
| [addColorReplaceEffect()](#addColorReplaceEffect--) | เพิ่มเอฟเฟ็กต์ Color Replacement ใหม่ที่ส่วนท้ายของคอลเลกชัน |
| [addDuotoneEffect()](#addDuotoneEffect--) | เพิ่มเอฟเฟ็กต์ Duotone ใหม่ที่ส่วนท้ายของคอลเลกชัน |
| [addFillOverlayEffect()](#addFillOverlayEffect--) | เพิ่มเอฟเฟ็กต์ Fill Overlay ใหม่ที่ส่วนท้ายของคอลเลกชัน |
| [addGrayScaleEffect()](#addGrayScaleEffect--) | เพิ่มเอฟเฟ็กต์ Gray Scale ใหม่ที่ส่วนท้ายของคอลเลกชัน |
| [addHSLEffect(float hue, float saturation, float luminance)](#addHSLEffect-float-float-float-) | เพิ่มเอฟเฟ็กต์ Hue/Saturation/Luminance ใหม่ที่ส่วนท้ายของคอลเลกชัน |
| [addLuminanceEffect(float brightness, float contrast)](#addLuminanceEffect-float-float-) | เพิ่มเอฟเฟ็กต์ Luminance ใหม่ที่ส่วนท้ายของคอลเลกชัน |
| [addTintEffect(float hue, float amount)](#addTintEffect-float-float-) | เพิ่มเอฟเฟ็กต์ Tint ใหม่ที่ส่วนท้ายของคอลเลกชัน |
| [addBrightnessContrastEffect(float brightness, float contrast)](#addBrightnessContrastEffect-float-float-) | เพิ่มเอฟเฟ็กต์ BrightnessContrast ใหม่ที่ส่วนท้ายของคอลเลกชัน |
### get_Item(int index) {#get-Item-int-}
```
public abstract IImageTransformOperation get_Item(int index)
```

ส่งคืน [IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation) จากคอลเลกชันโดยใช้ดัชนีของมัน

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| index | int | ดัชนีของรายการ |

**ส่งคืน:**
[IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation) - วัตถุ [IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation)
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

ลบเอฟเฟ็กต์รูปภาพออกจากคอลเลกชันที่ดัชนีที่ระบุ

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| index | int | ดัชนีของเอฟเฟ็กต์รูปภาพที่ต้องการลบ |
### addAlphaBiLevelEffect(float threshold) {#addAlphaBiLevelEffect-float-}
```
public abstract IAlphaBiLevel addAlphaBiLevelEffect(float threshold)
```

เพิ่มเอฟเฟ็กต์ Alpha Bi-Level ใหม่ที่ส่วนท้ายของคอลเลกชัน

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| threshold | float | ค่าขีดจำกัดสำหรับเอฟเฟ็กต์ Alpha Bi-Level |

**ส่งคืน:**
[IAlphaBiLevel](../../com.aspose.slides/ialphabilevel) - ดัชนีของเอฟเฟ็กต์รูปภาพใหม่ในคอลเลกชัน
### addAlphaCeilingEffect() {#addAlphaCeilingEffect--}
```
public abstract IAlphaCeiling addAlphaCeilingEffect()
```

เพิ่มเอฟเฟ็กต์ Alpha Ceiling ใหม่ที่ส่วนท้ายของคอลเลกชัน

**ส่งคืน:**
[IAlphaCeiling](../../com.aspose.slides/ialphaceiling) - ดัชนีของเอฟเฟ็กต์รูปภาพใหม่ในคอลเลกชัน
### addAlphaFloorEffect() {#addAlphaFloorEffect--}
```
public abstract IAlphaFloor addAlphaFloorEffect()
```

เพิ่มเอฟเฟ็กต์ Alpha Floor ใหม่ที่ส่วนท้ายของคอลเลกชัน

**ส่งคืน:**
[IAlphaFloor](../../com.aspose.slides/ialphafloor) - ดัชนีของเอฟเฟ็กต์รูปภาพใหม่ในคอลเลกชัน
### addAlphaInverseEffect() {#addAlphaInverseEffect--}
```
public abstract IAlphaInverse addAlphaInverseEffect()
```

เพิ่มเอฟเฟ็กต์ Alpha Inverse ใหม่ที่ส่วนท้ายของคอลเลกชัน

**ส่งคืน:**
[IAlphaInverse](../../com.aspose.slides/ialphainverse) - ดัชนีของเอฟเฟ็กต์รูปภาพใหม่ในคอลเลกชัน
### addAlphaModulateEffect() {#addAlphaModulateEffect--}
```
public abstract IAlphaModulate addAlphaModulateEffect()
```

เพิ่มเอฟเฟ็กต์ Alpha Modulate ใหม่ที่ส่วนท้ายของคอลเลกชัน

**ส่งคืน:**
[IAlphaModulate](../../com.aspose.slides/ialphamodulate) - ดัชนีของเอฟเฟ็กต์รูปภาพใหม่ในคอลเลกชัน
### addAlphaModulateFixedEffect(float amount) {#addAlphaModulateFixedEffect-float-}
```
public abstract IAlphaModulateFixed addAlphaModulateFixedEffect(float amount)
```

เพิ่มเอฟเฟ็กต์ Alpha Modulate Fixed ใหม่ที่ส่วนท้ายของคอลเลกชัน

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| amount | float | จำนวนเปอร์เซ็นต์ที่จะสเกลค่าอัลฟา |

**ส่งคืน:**
[IAlphaModulateFixed](../../com.aspose.slides/ialphamodulatefixed) - ดัชนีของเอฟเฟ็กต์รูปภาพใหม่ในคอลเลกชัน
### addAlphaReplaceEffect(float alpha) {#addAlphaReplaceEffect-float-}
```
public abstract IAlphaReplace addAlphaReplaceEffect(float alpha)
```

เพิ่มเอฟเฟ็กต์ Alpha Replace ใหม่ที่ส่วนท้ายของคอลเลกชัน

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| alpha | float | ค่าความทึบใหม่ |

**ส่งคืน:**
[IAlphaReplace](../../com.aspose.slides/ialphareplace) - ดัชนีของเอฟเฟ็กต์รูปภาพใหม่ในคอลเลกชัน
### addBiLevelEffect(float threshold) {#addBiLevelEffect-float-}
```
public abstract IBiLevel addBiLevelEffect(float threshold)
```

เพิ่มเอฟเฟ็กต์ Bi-Level (ขาว/ดำ) ใหม่ที่ส่วนท้ายของคอลเลกชัน

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| threshold | float | ขีดจำกัดความสว่างสำหรับเอฟเฟ็กต์ Bi-Level ค่าที่มากกว่าหรือเท่ากับจะตั้งเป็นสีขาว ค่าที่น้อยกว่าจะตั้งเป็นสีดำ |

**ส่งคืน:**
[IBiLevel](../../com.aspose.slides/ibilevel) - ดัชนีของเอฟเฟ็กต์รูปภาพใหม่ในคอลเลกชัน
### addBlurEffect(double radius, boolean grow) {#addBlurEffect-double-boolean-}
```
public abstract IBlur addBlurEffect(double radius, boolean grow)
```

เพิ่มเอฟเฟ็กต์ Blur ใหม่ที่ส่วนท้ายของคอลเลกชัน

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| radius | double | รัศมีของการเบลอ |
| grow | boolean | ระบุว่าขอบเขตของวัตถุควรขยายจากการเบลอหรือไม่ ค่าจริงหมายถึงขยาย ค่เท็จหมายถึงไม่ขยาย |

**ส่งคืน:**
[IBlur](../../com.aspose.slides/iblur) - ดัชนีของเอฟเฟ็กต์รูปภาพใหม่ในคอลเลกชัน
### addColorChangeEffect() {#addColorChangeEffect--}
```
public abstract IColorChange addColorChangeEffect()
```

เพิ่มเอฟเฟ็กต์ Color Change ใหม่ที่ส่วนท้ายของคอลเลกชัน

**ส่งคืน:**
[IColorChange](../../com.aspose.slides/icolorchange) - ดัชนีของเอฟเฟ็กต์รูปภาพใหม่ในคอลเลกชัน
### addColorReplaceEffect() {#addColorReplaceEffect--}
```
public abstract IColorReplace addColorReplaceEffect()
```

เพิ่มเอฟเฟ็กต์ Color Replacement ใหม่ที่ส่วนท้ายของคอลเลกชัน

**ส่งคืน:**
[IColorReplace](../../com.aspose.slides/icolorreplace) - ดัชนีของเอฟเฟ็กต์รูปภาพใหม่ในคอลเลกชัน
### addDuotoneEffect() {#addDuotoneEffect--}
```
public abstract IDuotone addDuotoneEffect()
```

เพิ่มเอฟเฟ็กต์ Duotone ใหม่ที่ส่วนท้ายของคอลเลกชัน

**ส่งคืน:**
[IDuotone](../../com.aspose.slides/iduotone) - ดัชนีของเอฟเฟ็กต์รูปภาพใหม่ในคอลเลกชัน
### addFillOverlayEffect() {#addFillOverlayEffect--}
```
public abstract IFillOverlay addFillOverlayEffect()
```

เพิ่มเอฟเฟ็กต์ Fill Overlay ใหม่ที่ส่วนท้ายของคอลเลกชัน

**ส่งคืน:**
[IFillOverlay](../../com.aspose.slides/ifilloverlay) - ดัชนีของเอฟเฟ็กต์รูปภาพใหม่ในคอลเลกชัน
### addGrayScaleEffect() {#addGrayScaleEffect--}
```
public abstract IGrayScale addGrayScaleEffect()
```

เพิ่มเอฟเฟ็กต์ Gray Scale ใหม่ที่ส่วนท้ายของคอลเลกชัน

**ส่งคืน:**
[IGrayScale](../../com.aspose.slides/igrayscale) - ดัชนีของเอฟเฟ็กต์รูปภาพใหม่ในคอลเลกชัน
### addHSLEffect(float hue, float saturation, float luminance) {#addHSLEffect-float-float-float-}
```
public abstract IHSL addHSLEffect(float hue, float saturation, float luminance)
```

เพิ่มเอฟเฟ็กต์ Hue/Saturation/Luminance ใหม่ที่ส่วนท้ายของคอลเลกชัน

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| hue | float | จำนวนองศาที่ปรับค่า hue |
| saturation | float | เปอร์เซ็นต์ที่ปรับค่า saturation |
| luminance | float | เปอร์เซ็นต์ที่ปรับค่า luminance |

**ส่งคืน:**
[IHSL](../../com.aspose.slides/ihsl) - ดัชนีของเอฟเฟ็กต์รูปภาพใหม่ในคอลเลกชัน
### addLuminanceEffect(float brightness, float contrast) {#addLuminanceEffect-float-float-}
```
public abstract ILuminance addLuminanceEffect(float brightness, float contrast)
```

เพิ่มเอฟเฟ็กต์ Luminance ใหม่ที่ส่วนท้ายของคอลเลกชัน

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| brightness | float | เปอร์เซ็นต์ที่เปลี่ยนความสว่าง |
| contrast | float | เปอร์เซ็นต์ที่เปลี่ยนความต่างระดับสี |

**ส่งคืน:**
[ILuminance](../../com.aspose.slides/iluminance) - ดัชนีของเอฟเฟ็กต์รูปภาพใหม่ในคอลเลกชัน
### addTintEffect(float hue, float amount) {#addTintEffect-float-float-}
```
public abstract ITint addTintEffect(float hue, float amount)
```

เพิ่มเอฟเฟ็กต์ Tint ใหม่ที่ส่วนท้ายของคอลเลกชัน

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| hue | float | สี hue ที่จะทำการทินท์ |
| amount | float | ระบุว่าค่าของสีจะถูกย้ายไปเท่าใด |

**ส่งคืน:**
[ITint](../../com.aspose.slides/itint) - ดัชนีของเอฟเฟ็กต์รูปภาพใหม่ในคอลเลกชัน
### addBrightnessContrastEffect(float brightness, float contrast) {#addBrightnessContrastEffect-float-float-}
```
public abstract IBrightnessContrast addBrightnessContrastEffect(float brightness, float contrast)
```

เพิ่มเอฟเฟ็กต์ BrightnessContrast ใหม่ที่ส่วนท้ายของคอลเลกชัน

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| brightness | float | เปอร์เซ็นต์ที่เปลี่ยนความสว่าง |
| contrast | float | เปอร์เซ็นต์ที่เปลี่ยนความต่างระดับสี |

**ส่งคืน:**
[IBrightnessContrast](../../com.aspose.slides/ibrightnesscontrast) - ดัชนีของเอฟเฟ็กต์รูปภาพใหม่ในคอลเลกชัน