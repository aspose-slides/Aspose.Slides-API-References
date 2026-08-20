---
title: ImageTransformOperationCollection
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ Java
description: แสดงคอลเลกชันของเอฟเฟกต์ที่นำไปใช้กับภาพ.
type: docs
url: /th/com.aspose.slides/imagetransformoperationcollection/
---
**Inheritance:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**All Implemented Interfaces:**
[com.aspose.slides.IImageTransformOperationCollection](../../com.aspose.slides/iimagetransformoperationcollection)
```
public final class ImageTransformOperationCollection extends PVIObject implements IImageTransformOperationCollection
```

แสดงคอลเลกชันของเอฟเฟกต์ที่นำไปใช้กับภาพ

## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [get_Item(int index)](#get-Item-int-) | คืนค่า [ImageTransformOperation](../../com.aspose.slides/imagetransformoperation) จากคอลเลกชันตามดัชนีของมัน |
| [removeAt(int index)](#removeAt-int-) | ลบเอฟเฟกต์รูปภาพจากคอลเลกชันที่ดัชนีที่ระบุ |
| [addAlphaBiLevelEffect(float threshold)](#addAlphaBiLevelEffect-float-) | เพิ่มเอฟเฟกต์ Alpha Bi-Level ใหม่ที่ส่วนท้ายของคอลเลกชัน |
| [addAlphaCeilingEffect()](#addAlphaCeilingEffect--) | เพิ่มเอฟเฟกต์ Alpha Ceiling ใหม่ที่ส่วนท้ายของคอลเลกชัน |
| [addAlphaFloorEffect()](#addAlphaFloorEffect--) | เพิ่มเอฟเฟกต์ Alpha Floor ใหม่ที่ส่วนท้ายของคอลเลกชัน |
| [addAlphaInverseEffect()](#addAlphaInverseEffect--) | เพิ่มเอฟเฟกต์ Alpha Inverse ใหม่ที่ส่วนท้ายของคอลเลกชัน |
| [addAlphaModulateEffect()](#addAlphaModulateEffect--) | เพิ่มเอฟเฟกต์ Alpha Modulate ใหม่ที่ส่วนท้ายของคอลเลกชัน |
| [addAlphaModulateFixedEffect(float amount)](#addAlphaModulateFixedEffect-float-) | เพิ่มเอฟเฟกต์ Alpha Modulate Fixed ใหม่ที่ส่วนท้ายของคอลเลกชัน |
| [addAlphaReplaceEffect(float alpha)](#addAlphaReplaceEffect-float-) | เพิ่มเอฟเฟกต์ Alpha Replace ใหม่ที่ส่วนท้ายของคอลเลกชัน |
| [addBiLevelEffect(float threshold)](#addBiLevelEffect-float-) | เพิ่มเอฟเฟกต์ Bi-Level (ขาว/ดำ) ใหม่ที่ส่วนท้ายของคอลเลกชัน |
| [addBlurEffect(double radius, boolean grow)](#addBlurEffect-double-boolean-) | เพิ่มเอฟเฟกต์ Blur ใหม่ที่ส่วนท้ายของคอลเลกชัน |
| [addColorChangeEffect()](#addColorChangeEffect--) | เพิ่มเอฟเฟกต์ Color Change ใหม่ที่ส่วนท้ายของคอลเลกชัน |
| [addColorReplaceEffect()](#addColorReplaceEffect--) | เพิ่มเอฟเฟกต์ Color Replacement ใหม่ที่ส่วนท้ายของคอลเลกชัน |
| [addDuotoneEffect()](#addDuotoneEffect--) | เพิ่มเอฟเฟกต์ Duotone ใหม่ที่ส่วนท้ายของคอลเลกชัน |
| [addFillOverlayEffect()](#addFillOverlayEffect--) | เพิ่มเอฟเฟกต์ Fill Overlay ใหม่ที่ส่วนท้ายของคอลเลกชัน |
| [addGrayScaleEffect()](#addGrayScaleEffect--) | เพิ่มเอฟเฟกต์ Gray Scale ใหม่ที่ส่วนท้ายของคอลเลกชัน |
| [addHSLEffect(float hue, float saturation, float luminance)](#addHSLEffect-float-float-float-) | เพิ่มเอฟเฟกต์ Hue/Saturation/Luminance ใหม่ที่ส่วนท้ายของคอลเลกชัน |
| [addLuminanceEffect(float brightness, float contrast)](#addLuminanceEffect-float-float-) | เพิ่มเอฟเฟกต์ Luminance ใหม่ที่ส่วนท้ายของคอลเลกชัน |
| [addTintEffect(float hue, float amount)](#addTintEffect-float-float-) | เพิ่มเอฟเฟกต์ Tint ใหม่ที่ส่วนท้ายของคอลเลกชัน |
| [addBrightnessContrastEffect(float brightness, float contrast)](#addBrightnessContrastEffect-float-float-) | เพิ่มเอฟเฟกต์ BrightnessContrast ใหม่ที่ส่วนท้ายของคอลเลกชัน |
| [size()](#size--) | คืนจำนวนเอฟเฟกต์รูปภาพในคอลเลกชัน |
| [isReadOnly()](#isReadOnly--) | ได้ค่าที่บ่งชี้ว่า [IGenericCollection](../../com.aspose.slides/igenericcollection) เป็นแบบอ่านอย่างเดียว |
| [addItem(IImageTransformOperation operation)](#addItem-com.aspose.slides.IImageTransformOperation-) | เพิ่มเอฟเฟกต์รูปภาพใหม่ที่ส่วนท้ายของคอลเลกชัน |
| [clear()](#clear--) | ลบเอฟเฟกต์รูปภาพทั้งหมดจากคอลเลกชัน |
| [containsItem(IImageTransformOperation item)](#containsItem-com.aspose.slides.IImageTransformOperation-) | ตรวจสอบว่า [IGenericCollection](../../com.aspose.slides/igenericcollection) มีค่าที่ระบุหรือไม่ |
| [copyToTArray(IImageTransformOperation[] array, int arrayIndex)](#copyToTArray-com.aspose.slides.IImageTransformOperation---int-) | คัดลอกองค์ประกอบของ [IGenericCollection](../../com.aspose.slides/igenericcollection) ไปยัง Array เริ่มต้นที่ดัชนีของ Array ที่กำหนด |
| [removeItem(IImageTransformOperation item)](#removeItem-com.aspose.slides.IImageTransformOperation-) | ลบการเกิดครั้งแรกของอ็อบเจ็กต์ที่ระบุจาก [IGenericCollection](../../com.aspose.slides/igenericcollection) |
| [iterator()](#iterator--) | คืน enumerator ที่วนผ่านคอลเลกชัน |
| [iteratorJava()](#iteratorJava--) | คืน java iterator สำหรับคอลเลกชันทั้งหมด |
### getVersion() {#getVersion--}
```
public long getVersion()
```

เวอร์ชัน อ่านอย่างเดียว long

**ค่าที่ส่งคืน:**
long
### get_Item(int index) {#get-Item-int-}
```
public final IImageTransformOperation get_Item(int index)
```

คืนค่า [ImageTransformOperation](../../com.aspose.slides/imagetransformoperation) จากคอลเลกชันตามดัชนีของมัน

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| index | int | ดัชนีขององค์ประกอบ |

**ค่าที่ส่งคืน:**
[IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation) - วัตถุ [IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation)
### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

ลบเอฟเฟกต์รูปภาพจากคอลเลกชันที่ดัชนีที่ระบุ

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| index | int | ดัชนีของเอฟเฟกต์รูปภาพที่ต้องการลบ |

### addAlphaBiLevelEffect(float threshold) {#addAlphaBiLevelEffect-float-}
```
public final IAlphaBiLevel addAlphaBiLevelEffect(float threshold)
```

เพิ่มเอฟเฟกต์ Alpha Bi-Level ใหม่ที่ส่วนท้ายของคอลเลกชัน

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| threshold | float | ค่าขีด จำกัดสำหรับเอฟเฟกต์ alpha bi-level |

**ค่าที่ส่งคืน:**
[IAlphaBiLevel](../../com.aspose.slides/ialphabilevel) - ดัชนีของเอฟเฟกต์รูปภาพใหม่ในคอลเลกชัน
### addAlphaCeilingEffect() {#addAlphaCeilingEffect--}
```
public final IAlphaCeiling addAlphaCeilingEffect()
```

เพิ่มเอฟเฟกต์ Alpha Ceiling ใหม่ที่ส่วนท้ายของคอลเลกชัน

**ค่าที่ส่งคืน:**
[IAlphaCeiling](../../com.aspose.slides/ialphaceiling) - ดัชนีของเอฟเฟกต์รูปภาพใหม่ในคอลเลกชัน
### addAlphaFloorEffect() {#addAlphaFloorEffect--}
```
public final IAlphaFloor addAlphaFloorEffect()
```

เพิ่มเอฟเฟกต์ Alpha Floor ใหม่ที่ส่วนท้ายของคอลเลกชัน

**ค่าที่ส่งคืน:**
[IAlphaFloor](../../com.aspose.slides/ialphafloor) - ดัชนีของเอฟเฟกต์รูปภาพใหม่ในคอลเลกชัน
### addAlphaInverseEffect() {#addAlphaInverseEffect--}
```
public final IAlphaInverse addAlphaInverseEffect()
```

เพิ่มเอฟเฟกต์ Alpha Inverse ใหม่ที่ส่วนท้ายของคอลเลกชัน

**ค่าที่ส่งคืน:**
[IAlphaInverse](../../com.aspose.slides/ialphainverse) - ดัชนีของเอฟเฟกต์รูปภาพใหม่ในคอลเลกชัน
### addAlphaModulateEffect() {#addAlphaModulateEffect--}
```
public final IAlphaModulate addAlphaModulateEffect()
```

เพิ่มเอฟเฟกต์ Alpha Modulate ใหม่ที่ส่วนท้ายของคอลเลกชัน

**ค่าที่ส่งคืน:**
[IAlphaModulate](../../com.aspose.slides/ialphamodulate) - ดัชนีของเอฟเฟกต์รูปภาพใหม่ในคอลเลกชัน
### addAlphaModulateFixedEffect(float amount) {#addAlphaModulateFixedEffect-float-}
```
public final IAlphaModulateFixed addAlphaModulateFixedEffect(float amount)
```

เพิ่มเอฟเฟกต์ Alpha Modulate Fixed ใหม่ที่ส่วนท้ายของคอลเลกชัน

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| amount | float | จำนวนเปอร์เซ็นต์ที่ปรับสเกลค่า alpha |

**ค่าที่ส่งคืน:**
[IAlphaModulateFixed](../../com.aspose.slides/ialphamodulatefixed) - ดัชนีของเอฟเฟกต์รูปภาพใหม่ในคอลเลกชัน
### addAlphaReplaceEffect(float alpha) {#addAlphaReplaceEffect-float-}
```
public final IAlphaReplace addAlphaReplaceEffect(float alpha)
```

เพิ่มเอฟเฟกต์ Alpha Replace ใหม่ที่ส่วนท้ายของคอลเลกชัน

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| alpha | float | ค่าความทึบใหม่ |

**ค่าที่ส่งคืน:**
[IAlphaReplace](../../com.aspose.slides/ialphareplace) - ดัชนีของเอฟเฟกต์รูปภาพใหม่ในคอลเลกชัน
### addBiLevelEffect(float threshold) {#addBiLevelEffect-float-}
```
public final IBiLevel addBiLevelEffect(float threshold)
```

เพิ่มเอฟเฟกต์ Bi-Level (ขาว/ดำ) ใหม่ที่ส่วนท้ายของคอลเลกชัน

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| threshold | float | ค่าเกณฑ์ความสว่างสำหรับเอฟเฟกต์ Bi-Level ค่าที่มากกว่าหรือเท่ากับเกณฑ์จะตั้งเป็นสีขาว ค่าที่น้อยกว่าจะตั้งเป็นสีดำ |

**ค่าที่ส่งคืน:**
[IBiLevel](../../com.aspose.slides/ibilevel) - ดัชนีของเอฟเฟกต์รูปภาพใหม่ในคอลเลกชัน
### addBlurEffect(double radius, boolean grow) {#addBlurEffect-double-boolean-}
```
public final IBlur addBlurEffect(double radius, boolean grow)
```

เพิ่มเอฟเฟกต์ Blur ใหม่ที่ส่วนท้ายของคอลเลกชัน

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| radius | double | รัศมีของการเบลอ |
| grow | boolean | ระบุว่าขอบเขตของอ็อบเจ็กต์จะขยายขนาดตามการเบลอหรือไม่ true หมายถึงขอบเขตขยาย false หมายถึงไม่ขยาย |

**ค่าที่ส่งคืน:**
[IBlur](../../com.aspose.slides/iblur) - ดัชนีของเอฟเฟกต์รูปภาพใหม่ในคอลเลกชัน
### addColorChangeEffect() {#addColorChangeEffect--}
```
public final IColorChange addColorChangeEffect()
```

เพิ่มเอฟเฟกต์ Color Change ใหม่ที่ส่วนท้ายของคอลเลกชัน

**ค่าที่ส่งคืน:**
[IColorChange](../../com.aspose.slides/icolorchange) - ดัชนีของเอฟเฟกต์รูปภาพใหม่ในคอลเลกชัน
### addColorReplaceEffect() {#addColorReplaceEffect--}
```
public final IColorReplace addColorReplaceEffect()
```

เพิ่มเอฟเฟกต์ Color Replacement ใหม่ที่ส่วนท้ายของคอลเลกชัน

**ค่าที่ส่งคืน:**
[IColorReplace](../../com.aspose.slides/icolorreplace) - ดัชนีของเอฟเฟกต์รูปภาพใหม่ในคอลเลกชัน
### addDuotoneEffect() {#addDuotoneEffect--}
```
public final IDuotone addDuotoneEffect()
```

เพิ่มเอฟเฟกต์ Duotone ใหม่ที่ส่วนท้ายของคอลเลกชัน

**ค่าที่ส่งคืน:**
[IDuotone](../../com.aspose.slides/iduotone) - ดัชนีของเอฟเฟกต์รูปภาพใหม่ในคอลเลกชัน
### addFillOverlayEffect() {#addFillOverlayEffect--}
```
public final IFillOverlay addFillOverlayEffect()
```

เพิ่มเอฟเฟกต์ Fill Overlay ใหม่ที่ส่วนท้ายของคอลเลกชัน

**ค่าที่ส่งคืน:**
[IFillOverlay](../../com.aspose.slides/ifilloverlay) - ดัชนีของเอฟเฟกต์รูปภาพใหม่ในคอลเลกชัน
### addGrayScaleEffect() {#addGrayScaleEffect--}
```
public final IGrayScale addGrayScaleEffect()
```

เพิ่มเอฟเฟกต์ Gray Scale ใหม่ที่ส่วนท้ายของคอลเลกชัน

**ค่าที่ส่งคืน:**
[IGrayScale](../../com.aspose.slides/igrayscale) - ดัชนีของเอฟเฟกต์รูปภาพใหม่ในคอลเลกชัน
### addHSLEffect(float hue, float saturation, float luminance) {#addHSLEffect-float-float-float-}
```
public final IHSL addHSLEffect(float hue, float saturation, float luminance)
```

เพิ่มเอฟเฟกต์ Hue/Saturation/Luminance ใหม่ที่ส่วนท้ายของคอลเลกชัน

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| hue | float | จำนวนองศาที่ปรับค่า hue |
| saturation | float | เปอร์เซ็นต์ที่ปรับค่า saturation |
| luminance | float | เปอร์เซ็นต์ที่ปรับค่า luminance |

**ค่าที่ส่งคืน:**
[IHSL](../../com.aspose.slides/ihsl) - ดัชนีของเอฟเฟกต์รูปภาพใหม่ในคอลเลกชัน
### addLuminanceEffect(float brightness, float contrast) {#addLuminanceEffect-float-float-}
```
public final ILuminance addLuminanceEffect(float brightness, float contrast)
```

เพิ่มเอฟเฟกต์ Luminance ใหม่ที่ส่วนท้ายของคอลเลกชัน

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| brightness | float | เปอร์เซ็นต์การเปลี่ยนแปลงความสว่าง |
| contrast | float | เปอร์เซ็นต์การเปลี่ยนแปลงความคอนทราสต์ |

**ค่าที่ส่งคืน:**
[ILuminance](../../com.aspose.slides/iluminance) - ดัชนีของเอฟเฟกต์รูปภาพใหม่ในคอลเลกชัน
### addTintEffect(float hue, float amount) {#addTintEffect-float-float-}
```
public final ITint addTintEffect(float hue, float amount)
```

เพิ่มเอฟเฟกต์ Tint ใหม่ที่ส่วนท้ายของคอลเลกชัน

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| hue | float | hue ที่จะทำให้สีเปลี่ยนเป็นสีที่กำหนด |
| amount | float | ระบุว่าค่าสีจะถูกเปลี่ยนเท่าใด |

**ค่าที่ส่งคืน:**
[ITint](../../com.aspose.slides/itint) - ดัชนีของเอฟเฟกต์รูปภาพใหม่ในคอลเลกชัน
### addBrightnessContrastEffect(float brightness, float contrast) {#addBrightnessContrastEffect-float-float-}
```
public final IBrightnessContrast addBrightnessContrastEffect(float brightness, float contrast)
```

เพิ่มเอฟเฟกต์ BrightnessContrast ใหม่ที่ส่วนท้ายของคอลเลกชัน

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| brightness | float | เปอร์เซ็นต์การเปลี่ยนแปลงความสว่าง |
| contrast | float | เปอร์เซ็นต์การเปลี่ยนแปลงความคอนทราสต์ |

**ค่าที่ส่งคืน:**
[IBrightnessContrast](../../com.aspose.slides/ibrightnesscontrast) - ดัชนีของเอฟเฟกต์รูปภาพใหม่ในคอลเลกชัน
### size() {#size--}
```
public final int size()
```

คืนจำนวนเอฟเฟกต์รูปภาพในคอลเลกชัน อ่านอย่างเดียว int

**ค่าที่ส่งคืน:**
int
### isReadOnly() {#isReadOnly--}
```
public final boolean isReadOnly()
```

ได้ค่าที่บ่งชี้ว่า [IGenericCollection](../../com.aspose.slides/igenericcollection) เป็นแบบอ่านอย่างเดียว อ่านอย่างเดียว boolean

**ค่าที่ส่งคืน:**
boolean - true หาก [IGenericCollection](../../com.aspose.slides/igenericcollection) เป็นแบบอ่านอย่างเดียว; มิฉะนั้น false
### addItem(IImageTransformOperation operation) {#addItem-com.aspose.slides.IImageTransformOperation-}
```
public final void addItem(IImageTransformOperation operation)
```

เพิ่มเอฟเฟกต์รูปภาพใหม่ที่ส่วนท้ายของคอลเลกชัน

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| operation | [IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation) | เอฟเฟกต์รูปภาพที่ต้องการเพิ่มที่ส่วนท้ายของคอลเลกชัน |

### clear() {#clear--}
```
public final void clear()
```

ลบเอฟเฟกต์รูปภาพทั้งหมดจากคอลเลกชัน

### containsItem(IImageTransformOperation item) {#containsItem-com.aspose.slides.IImageTransformOperation-}
```
public final boolean containsItem(IImageTransformOperation item)
```

ตรวจสอบว่า [IGenericCollection](../../com.aspose.slides/igenericcollection) มีค่าที่ระบุหรือไม่

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| item | [IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation) | อ็อบเจ็กต์ที่ต้องการค้นหาใน [IGenericCollection](../../com.aspose.slides/igenericcollection) |

**ค่าที่ส่งคืน:**
boolean - true หากพบ item ใน [IGenericCollection](../../com.aspose.slides/igenericcollection); มิฉะนั้น false
### copyToTArray(IImageTransformOperation[] array, int arrayIndex) {#copyToTArray-com.aspose.slides.IImageTransformOperation---int-}
```
public final void copyToTArray(IImageTransformOperation[] array, int arrayIndex)
```

คัดลอกองค์ประกอบของ [IGenericCollection](../../com.aspose.slides/igenericcollection) ไปยัง Array เริ่มต้นที่ดัชนีของ Array ที่กำหนด

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| array | [IImageTransformOperation\[\]](../../com.aspose.slides/iimagetransformoperation) | Array หนึ่งมิติที่เป็นปลายทางขององค์ประกอบที่คัดลอกจาก [IGenericCollection](../../com.aspose.slides/igenericcollection) Array ต้องมีการจัดทำดัชนีตั้งแต่ศูนย์ |
| arrayIndex | int | ดัชนีเริ่มต้นใน array ที่การคัดลอกเริ่มต้น |

### removeItem(IImageTransformOperation item) {#removeItem-com.aspose.slides.IImageTransformOperation-}
```
public final boolean removeItem(IImageTransformOperation item)
```

ลบการเกิดครั้งแรกของอ็อบเจ็กต์ที่ระบุจาก [IGenericCollection](../../com.aspose.slides/igenericcollection)

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| item | [IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation) | อ็อบเจ็กต์ที่ต้องการลบจาก [IGenericCollection](../../com.aspose.slides/igenericcollection) |

**ค่าที่ส่งคืน:**
boolean - true หาก  item  ถูกลบสำเร็จจาก [IGenericCollection](../../com.aspose.slides/igenericcollection); มิฉะนั้น false วิธีนี้ยังคืนค่า false หากไม่พบ item ใน [IGenericCollection](../../com.aspose.slides/igenericcollection) ดั้งเดิม
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IImageTransformOperation> iterator()
```

คืน enumerator ที่วนผ่านคอลเลกชัน

**ค่าที่ส่งคืน:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IImageTransformOperation> - IGenericEnumerator ที่ใช้ในการวนผ่านคอลเลกชัน
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IImageTransformOperation> iteratorJava()
```

คืน java iterator สำหรับคอลเลกชันทั้งหมด

**ค่าที่ส่งคืน:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IImageTransformOperation> - java.util.Iterator สำหรับคอลเลกชันทั้งหมด