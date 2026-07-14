---
title: ImageTransformOperationCollection
second_title: Aspose.Slides สำหรับ Android ผ่าน Java API Reference
description: แสดงคอลเลกชันของเอฟเฟกต์ที่ใช้กับภาพ.
type: docs
url: /th/com.aspose.slides/imagetransformoperationcollection/
---
**การสืบทอด:**  
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**ทุกอินเทอร์เฟซที่นำไปใช้:**  
[com.aspose.slides.IImageTransformOperationCollection](../../com.aspose.slides/iimagetransformoperationcollection)  
```
public final class ImageTransformOperationCollection extends PVIObject implements IImageTransformOperationCollection
```

แสดงถึงคอลเลกชันของเอฟเฟกต์ที่นำไปใช้กับภาพ  

## วิธีการ

| Method | Description |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [get_Item(int index)](#get-Item-int-) | คืนค่า [ImageTransformOperation](../../com.aspose.slides/imagetransformoperation) จากคอลเลกชันโดยใช้ดัชนีของมัน. |
| [removeAt(int index)](#removeAt-int-) | ลบเอฟเฟกต์ภาพออกจากคอลเลกชันที่ตำแหน่งที่ระบุ. |
| [addAlphaBiLevelEffect(float threshold)](#addAlphaBiLevelEffect-float-) | เพิ่มเอฟเฟกต์ Alpha Bi-Level ใหม่ลงในส่วนท้ายของคอลเลกชัน. |
| [addAlphaCeilingEffect()](#addAlphaCeilingEffect--) | เพิ่มเอฟเฟกต์ Alpha Ceiling ใหม่ลงในส่วนท้ายของคอลเลกชัน. |
| [addAlphaFloorEffect()](#addAlphaFloorEffect--) | เพิ่มเอฟเฟกต์ Alpha Floor ใหม่ลงในส่วนท้ายของคอลเลกชัน. |
| [addAlphaInverseEffect()](#addAlphaInverseEffect--) | เพิ่มเอฟเฟกต์ Alpha Inverse ใหม่ลงในส่วนท้ายของคอลเลกชัน. |
| [addAlphaModulateEffect()](#addAlphaModulateEffect--) | เพิ่มเอฟเฟกต์ Alpha Modulate ใหม่ลงในส่วนท้ายของคอลเลกชัน. |
| [addAlphaModulateFixedEffect(float amount)](#addAlphaModulateFixedEffect-float-) | เพิ่มเอฟเฟกต์ Alpha Modulate Fixed ใหม่ลงในส่วนท้ายของคอลเลกชัน. |
| [addAlphaReplaceEffect(float alpha)](#addAlphaReplaceEffect-float-) | เพิ่มเอฟเฟกต์ Alpha Replace ใหม่ลงในส่วนท้ายของคอลเลกชัน. |
| [addBiLevelEffect(float threshold)](#addBiLevelEffect-float-) | เพิ่มเอฟเฟกต์ Bi-Level (ขาวดํา) ใหม่ลงในส่วนท้ายของคอลเลกชัน. |
| [addBlurEffect(double radius, boolean grow)](#addBlurEffect-double-boolean-) | เพิ่มเอฟเฟกต์ Blur ใหม่ลงในส่วนท้ายของคอลเลกชัน. |
| [addColorChangeEffect()](#addColorChangeEffect--) | เพิ่มเอฟเฟกต์ Color Change ใหม่ลงในส่วนท้ายของคอลเลกชัน. |
| [addColorReplaceEffect()](#addColorReplaceEffect--) | เพิ่มเอฟเฟกต์ Color Replacement ใหม่ลงในส่วนท้ายของคอลเลกชัน. |
| [addDuotoneEffect()](#addDuotoneEffect--) | เพิ่มเอฟเฟกต์ Duotone ใหม่ลงในส่วนท้ายของคอลเลกชัน. |
| [addFillOverlayEffect()](#addFillOverlayEffect--) | เพิ่มเอฟเฟกต์ Fill Overlay ใหม่ลงในส่วนท้ายของคอลเลกชัน. |
| [addGrayScaleEffect()](#addGrayScaleEffect--) | เพิ่มเอฟเฟกต์ Gray Scale ใหม่ลงในส่วนท้ายของคอลเลกชัน. |
| [addHSLEffect(float hue, float saturation, float luminance)](#addHSLEffect-float-float-float-) | เพิ่มเอฟเฟกต์ Hue/Saturation/Luminance ใหม่ลงในส่วนท้ายของคอลเลกชัน. |
| [addLuminanceEffect(float brightness, float contrast)](#addLuminanceEffect-float-float-) | เพิ่มเอฟเฟกต์ Luminance ใหม่ลงในส่วนท้ายของคอลเลกชัน. |
| [addTintEffect(float hue, float amount)](#addTintEffect-float-float-) | เพิ่มเอฟเฟกต์ Tint ใหม่ลงในส่วนท้ายของคอลเลกชัน. |
| [addBrightnessContrastEffect(float brightness, float contrast)](#addBrightnessContrastEffect-float-float-) | เพิ่มเอฟเฟกต์ BrightnessContrast ใหม่ลงในส่วนท้ายของคอลเลกชัน. |
| [size()](#size--) | คืนจำนวนเอฟเฟกต์ภาพในคอลเลกชัน. |
| [isReadOnly()](#isReadOnly--) | รับค่าที่บ่งบอกว่า [IGenericCollection](../../com.aspose.slides/igenericcollection) เป็นแบบอ่านอย่างเดียวหรือไม่. |
| [addItem(IImageTransformOperation operation)](#addItem-com.aspose.slides.IImageTransformOperation-) | เพิ่มเอฟเฟกต์ภาพใหม่ลงในส่วนท้ายของคอลเลกชัน. |
| [clear()](#clear--) | ลบเอฟเฟกต์ภาพทั้งหมดออกจากคอลเลกชัน. |
| [containsItem(IImageTransformOperation item)](#containsItem-com.aspose.slides.IImageTransformOperation-) | กำหนดว่ามี [IGenericCollection](../../com.aspose.slides/igenericcollection) มีค่าที่ระบุหรือไม่. |
| [copyToTArray(IImageTransformOperation[] array, int arrayIndex)](#copyToTArray-com.aspose.slides.IImageTransformOperation---int-) | คัดลอกองค์ประกอบของ [IGenericCollection](../../com.aspose.slides/igenericcollection) ไปยังอาเรย์, เริ่มต้นที่ดัชนีอาเรย์ที่กำหนด. |
| [removeItem(IImageTransformOperation item)](#removeItem-com.aspose.slides.IImageTransformOperation-) | ลบการปรากฏครั้งแรกของอ็อบเจกต์ที่ระบุจาก [IGenericCollection](../../com.aspose.slides/igenericcollection). |
| [iterator()](#iterator--) | คืน enumerator ที่วนผ่านคอลเลกชัน. |
| [iteratorJava()](#iteratorJava--) | คืน java iterator สำหรับคอลเลกชันทั้งหมด. |

### getVersion() {#getVersion--}
```
public long getVersion()
```

เวอร์ชัน. อ่านอย่างเดียว long.

**คืนค่า:**  
long

### get_Item(int index) {#get-Item-int-}
```
public final IImageTransformOperation get_Item(int index)
```

คืนค่า [ImageTransformOperation](../../com.aspose.slides/imagetransformoperation) จากคอลเลกชันโดยใช้ดัชนีของมัน.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| index | int | ดัชนีขององค์ประกอบ. |

**คืนค่า:**  
[IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation) - วัตถุ [IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation).

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

ลบเอฟเฟกต์ภาพออกจากคอลเลกชันที่ตำแหน่งที่ระบุ.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| index | int | ดัชนีของเอฟเฟกต์ภาพที่ต้องการลบ. |

### addAlphaBiLevelEffect(float threshold) {#addAlphaBiLevelEffect-float-}
```
public final IAlphaBiLevel addAlphaBiLevelEffect(float threshold)
```

เพิ่มเอฟเฟกต์ Alpha Bi-Level ใหม่ลงในส่วนท้ายของคอลเลกชัน.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| threshold | float | ค่าระดับเกณฑ์สำหรับเอฟเฟกต์ alpha bi-level. |

**คืนค่า:**  
[IAlphaBiLevel](../../com.aspose.slides/ialphabilevel) - ดัชนีของเอฟเฟกต์ภาพใหม่ในคอลเลกชัน.

### addAlphaCeilingEffect() {#addAlphaCeilingEffect--}
```
public final IAlphaCeiling addAlphaCeilingEffect()
```

เพิ่มเอฟเฟกต์ Alpha Ceiling ใหม่ลงในส่วนท้ายของคอลเลกชัน.

**คืนค่า:**  
[IAlphaCeiling](../../com.aspose.slides/ialphaceiling) - ดัชนีของเอฟเฟกต์ภาพใหม่ในคอลเลกชัน.

### addAlphaFloorEffect() {#addAlphaFloorEffect--}
```
public final IAlphaFloor addAlphaFloorEffect()
```

เพิ่มเอฟเฟกต์ Alpha Floor ใหม่ลงในส่วนท้ายของคอลเลกชัน.

**คืนค่า:**  
[IAlphaFloor](../../com.aspose.slides/ialphafloor) - ดัชนีของเอฟเฟกต์ภาพใหม่ในคอลเลกชัน.

### addAlphaInverseEffect() {#addAlphaInverseEffect--}
```
public final IAlphaInverse addAlphaInverseEffect()
```

เพิ่มเอฟเฟกต์ Alpha Inverse ใหม่ลงในส่วนท้ายของคอลเลกชัน.

**คืนค่า:**  
[IAlphaInverse](../../com.aspose.slides/ialphainverse) - ดัชนีของเอฟเฟกต์ภาพใหม่ในคอลเลกชัน.

### addAlphaModulateEffect() {#addAlphaModulateEffect--}
```
public final IAlphaModulate addAlphaModulateEffect()
```

เพิ่มเอฟเฟกต์ Alpha Modulate ใหม่ลงในส่วนท้ายของคอลเลกชัน.

**คืนค่า:**  
[IAlphaModulate](../../com.aspose.slides/ialphamodulate) - ดัชนีของเอฟเฟกต์ภาพใหม่ในคอลเลกชัน.

### addAlphaModulateFixedEffect(float amount) {#addAlphaModulateFixedEffect-float-}
```
public final IAlphaModulateFixed addAlphaModulateFixedEffect(float amount)
```

เพิ่มเอฟเฟกต์ Alpha Modulate Fixed ใหม่ลงในส่วนท้ายของคอลเลกชัน.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| amount | float | เปอร์เซ็นต์ที่ใช้ปรับสเกลค่า alpha. |

**คืนค่า:**  
[IAlphaModulateFixed](../../com.aspose.slides/ialphamodulatefixed) - ดัชนีของเอฟเฟกต์ภาพใหม่ในคอลเลกชัน.

### addAlphaReplaceEffect(float alpha) {#addAlphaReplaceEffect-float-}
```
public final IAlphaReplace addAlphaReplaceEffect(float alpha)
```

เพิ่มเอฟเฟกต์ Alpha Replace ใหม่ลงในส่วนท้ายของคอลเลกชัน.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| alpha | float | ค่าความทึบใหม่. |

**คืนค่า:**  
[IAlphaReplace](../../com.aspose.slides/ialphareplace) - ดัชนีของเอฟเฟกต์ภาพใหม่ในคอลเลกชัน.

### addBiLevelEffect(float threshold) {#addBiLevelEffect-float-}
```
public final IBiLevel addBiLevelEffect(float threshold)
```

เพิ่มเอฟเฟกต์ Bi-Level (ขาวดํา) ใหม่ลงในส่วนท้ายของคอลเลกชัน.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| threshold | float | ค่าระดับความสว่างสำหรับเอฟเฟกต์ Bi-Level. ค่าที่มากกว่าหรือเท่ากับเกณฑ์จะตั้งเป็นสีขาว, ค่าที่น้อยกว่าจะตั้งเป็นสีดำ. |

**คืนค่า:**  
[IBiLevel](../../com.aspose.slides/ibilevel) - ดัชนีของเอฟเฟกต์ภาพใหม่ในคอลเลกชัน.

### addBlurEffect(double radius, boolean grow) {#addBlurEffect-double-boolean-}
```
public final IBlur addBlurEffect(double radius, boolean grow)
```

เพิ่มเอฟเฟกต์ Blur ใหม่ลงในส่วนท้ายของคอลเลกชัน.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| radius | double | รัศมีของการเบลอ. |
| grow | boolean | ระบุว่าขอบของออบเจกต์จะขยายตามการเบลอหรือไม่. true หมายถึงขอบจะขยาย, false หมายถึงไม่ขยาย. |

**คืนค่า:**  
[IBlur](../../com.aspose.slides/iblur) - ดัชนีของเอฟเฟกต์ภาพใหม่ในคอลเลกชัน.

### addColorChangeEffect() {#addColorChangeEffect--}
```
public final IColorChange addColorChangeEffect()
```

เพิ่มเอฟเฟกต์ Color Change ใหม่ลงในส่วนท้ายของคอลเลกชัน.

**คืนค่า:**  
[IColorChange](../../com.aspose.slides/icolorchange) - ดัชนีของเอฟเฟกต์ภาพใหม่ในคอลเลกชัน.

### addColorReplaceEffect() {#addColorReplaceEffect--}
```
public final IColorReplace addColorReplaceEffect()
```

เพิ่มเอฟเฟกต์ Color Replacement ใหม่ลงในส่วนท้ายของคอลเลกชัน.

**คืนค่า:**  
[IColorReplace](../../com.aspose.slides/icolorreplace) - ดัชนีของเอฟเฟกต์ภาพใหม่ในคอลเลกชัน.

### addDuotoneEffect() {#addDuotoneEffect--}
```
public final IDuotone addDuotoneEffect()
```

เพิ่มเอฟเฟกต์ Duotone ใหม่ลงในส่วนท้ายของคอลเลกชัน.

**คืนค่า:**  
[IDuotone](../../com.aspose.slides/iduotone) - ดัชนีของเอฟเฟกต์ภาพใหม่ในคอลเลกชัน.

### addFillOverlayEffect() {#addFillOverlayEffect--}
```
public final IFillOverlay addFillOverlayEffect()
```

เพิ่มเอฟเฟกต์ Fill Overlay ใหม่ลงในส่วนท้ายของคอลเลกชัน.

**คืนค่า:**  
[IFillOverlay](../../com.aspose.slides/ifilloverlay) - ดัชนีของเอฟเฟกต์ภาพใหม่ในคอลเลกชัน.

### addGrayScaleEffect() {#addGrayScaleEffect--}
```
public final IGrayScale addGrayScaleEffect()
```

เพิ่มเอฟเฟกต์ Gray Scale ใหม่ลงในส่วนท้ายของคอลเลกชัน.

**คืนค่า:**  
[IGrayScale](../../com.aspose.slides/igrayscale) - ดัชนีของเอฟเฟกต์ภาพใหม่ในคอลเลกชัน.

### addHSLEffect(float hue, float saturation, float luminance) {#addHSLEffect-float-float-float-}
```
public final IHSL addHSLEffect(float hue, float saturation, float luminance)
```

เพิ่มเอฟเฟกต์ Hue/Saturation/Luminance ใหม่ลงในส่วนท้ายของคอลเลกชัน.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| hue | float | จำนวนองศาที่ปรับค่า hue. |
| saturation | float | เปอร์เซ็นต์ที่ปรับค่า saturation. |
| luminance | float | เปอร์เซ็นต์ที่ปรับค่า luminance. |

**คืนค่า:**  
[IHSL](../../com.aspose.slides/ihsl) - ดัชนีของเอฟเฟกต์ภาพใหม่ในคอลเลกชัน.

### addLuminanceEffect(float brightness, float contrast) {#addLuminanceEffect-float-float-}
```
public final ILuminance addLuminanceEffect(float brightness, float contrast)
```

เพิ่มเอฟเฟกต์ Luminance ใหม่ลงในส่วนท้ายของคอลเลกชัน.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| brightness | float | เปอร์เซ็นต์ที่เปลี่ยนความสว่าง. |
| contrast | float | เปอร์เซ็นต์ที่เปลี่ยนความคอนทราสต์. |

**คืนค่า:**  
[ILuminance](../../com.aspose.slides/iluminance) - ดัชนีของเอฟเฟกต์ภาพใหม่ในคอลเลกชัน.

### addTintEffect(float hue, float amount) {#addTintEffect-float-float-}
```
public final ITint addTintEffect(float hue, float amount)
```

เพิ่มเอฟเฟกต์ Tint ใหม่ลงในส่วนท้ายของคอลเลกชัน.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| hue | float | ค่า hue ที่ใช้ในการทินท์. |
| amount | float | ระบุว่าค่าสีจะถูกปรับเท่าใด. |

**คืนค่า:**  
[ITint](../../com.aspose.slides/itint) - ดัชนีของเอฟเฟกต์ภาพใหม่ในคอลเลกชัน.

### addBrightnessContrastEffect(float brightness, float contrast) {#addBrightnessContrastEffect-float-float-}
```
public final IBrightnessContrast addBrightnessContrastEffect(float brightness, float contrast)
```

เพิ่มเอฟเฟกต์ BrightnessContrast ใหม่ลงในส่วนท้ายของคอลเลกชัน.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| brightness | float | เปอร์เซ็นต์ที่เปลี่ยนความสว่าง. |
| contrast | float | เปอร์เซ็นต์ที่เปลี่ยนความคอนทราสต. |

**คืนค่า:**  
[IBrightnessContrast](../../com.aspose.slides/ibrightnesscontrast) - ดัชนีของเอฟเฟกต์ภาพใหม่ในคอลเลกชัน.

### size() {#size--}
```
public final int size()
```

คืนจำนวนเอฟเฟกต์ภาพในคอลเลกชัน. อ่านอย่างเดียว int .

**คืนค่า:**  
int

### isReadOnly() {#isReadOnly--}
```
public final boolean isReadOnly()
```

รับค่าที่บ่งบอกว่า [IGenericCollection](../../com.aspose.slides/igenericcollection) เป็นแบบอ่านอย่างเดียวหรือไม่. อ่านอย่างเดียว boolean.

**คืนค่า:**  
boolean - true หาก [IGenericCollection](../../com.aspose.slides/igenericcollection) เป็นแบบอ่านอย่างเดียว; otherwise, false.

### addItem(IImageTransformOperation operation) {#addItem-com.aspose.slides.IImageTransformOperation-}
```
public final void addItem(IImageTransformOperation operation)
```

เพิ่มเอฟเฟกต์ภาพใหม่ลงในส่วนท้ายของคอลเลกชัน.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| operation | [IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation) | เอฟเฟกต์ภาพที่จะเพิ่มลงในส่วนท้ายของคอลเลกชัน. |

### clear() {#clear--}
```
public final void clear()
```

ลบเอฟเฟกต์ภาพทั้งหมดออกจากคอลเลกชัน.

### containsItem(IImageTransformOperation item) {#containsItem-com.aspose.slides.IImageTransformOperation-}
```
public final boolean containsItem(IImageTransformOperation item)
```

กำหนดว่ามี [IGenericCollection](../../com.aspose.slides/igenericcollection) มีค่าที่ระบุหรือไม่.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| item | [IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation) | อ็อบเจกต์ที่ต้องการค้นหาใน [IGenericCollection](../../com.aspose.slides/igenericcollection). |

**คืนค่า:**  
boolean - true หากพบ item ใน [IGenericCollection](../../com.aspose.slides/igenericcollection); otherwise, false.

### copyToTArray(IImageTransformOperation[] array, int arrayIndex) {#copyToTArray-com.aspose.slides.IImageTransformOperation---int-}
```
public final void copyToTArray(IImageTransformOperation[] array, int arrayIndex)
```

คัดลอกองค์ประกอบของ [IGenericCollection](../../com.aspose.slides/igenericcollection) ไปยังอาเรย์, เริ่มต้นที่ดัชนีอาเรย์ที่กำหนด.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| array | [IImageTransformOperation\[\]](../../com.aspose.slides/iimagetransformoperation) | อาเรย์มิติเดียวที่เป็นปลายทางขององค์ประกอบที่คัดลอกจาก [IGenericCollection](../../com.aspose.slides/igenericcollection). อาเรย์ต้องมีการจัดทำดัชนีตั้งแต่ศูนย์. |
| arrayIndex | int | ดัชนีเริ่มต้นในอาเรย์ที่การคัดลอกเริ่มต้น. |

### removeItem(IImageTransformOperation item) {#removeItem-com.aspose.slides.IImageTransformOperation-}
```
public final boolean removeItem(IImageTransformOperation item)
```

ลบการปรากฏครั้งแรกของอ็อบเจกต์ที่ระบุจาก [IGenericCollection](../../com.aspose.slides/igenericcollection).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| item | [IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation) | อ็อบเจกต์ที่จะลบออกจาก [IGenericCollection](../../com.aspose.slides/igenericcollection). |

**คืนค่า:**  
boolean - true หาก item ถูกลบสำเร็จจาก [IGenericCollection](../../com.aspose.slides/igenericcollection); otherwise, false. วิธีนี้ยังคืน false หากไม่พบ item ใน [IGenericCollection](../../com.aspose.slides/igenericcollection) ดั้งเดิม.

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IImageTransformOperation> iterator()
```

คืน enumerator ที่วนผ่านคอลเลกชัน.

**คืนค่า:**  
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IImageTransformOperation> - IGenericEnumerator ที่สามารถใช้วนผ่านคอลเลกชัน.

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IImageTransformOperation> iteratorJava()
```

คืน java iterator สำหรับคอลเลกชันทั้งหมด.

**คืนค่า:**  
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IImageTransformOperation> - java.util.Iterator สำหรับคอลเลกชันทั้งหมด.