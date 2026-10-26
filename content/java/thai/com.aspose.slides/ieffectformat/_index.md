---
title: IEffectFormat
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ Java
description: แทนคุณสมบัติของเอฟเฟกต์ของรูปร่าง.
type: docs
url: /th/com.aspose.slides/ieffectformat/
---
**อินเทอร์เฟซที่นำไปใช้ทั้งหมด:**
[com.aspose.slides.IEffectParamSource](../../com.aspose.slides/ieffectparamsource)
```
public interface IEffectFormat extends IEffectParamSource
```

แสดงคุณสมบัติของเอฟเฟกต์ของรูปร่าง.
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [isNoEffects()](#isNoEffects--) | คืนค่า true หากเอฟเฟกต์ทั้งหมดถูกปิด (เช่น เพิ่งสร้าง, วัตถุ EffectFormat เริ่มต้น). |
| [getBlurEffect()](#getBlurEffect--) | เอฟเฟกต์เบลอ. |
| [setBlurEffect(IBlur value)](#setBlurEffect-com.aspose.slides.IBlur-) | เอฟเฟกต์เบลอ. |
| [getFillOverlayEffect()](#getFillOverlayEffect--) | เอฟเฟกต์การซ้อนเติม. |
| [setFillOverlayEffect(IFillOverlay value)](#setFillOverlayEffect-com.aspose.slides.IFillOverlay-) | เอฟเฟกต์การซ้อนเติม. |
| [getGlowEffect()](#getGlowEffect--) | เอฟเฟกต์เรืองแสง. |
| [setGlowEffect(IGlow value)](#setGlowEffect-com.aspose.slides.IGlow-) | เอฟเฟกต์เรืองแสง. |
| [getInnerShadowEffect()](#getInnerShadowEffect--) | เงาภายใน. |
| [setInnerShadowEffect(IInnerShadow value)](#setInnerShadowEffect-com.aspose.slides.IInnerShadow-) | เงาภายใน. |
| [getOuterShadowEffect()](#getOuterShadowEffect--) | เงาภายนอก. |
| [setOuterShadowEffect(IOuterShadow value)](#setOuterShadowEffect-com.aspose.slides.IOuterShadow-) | เงาภายนอก. |
| [getPresetShadowEffect()](#getPresetShadowEffect--) | เงาที่ตั้งค่าล่วงหน้า. |
| [setPresetShadowEffect(IPresetShadow value)](#setPresetShadowEffect-com.aspose.slides.IPresetShadow-) | เงาที่ตั้งค่าล่วงหน้า. |
| [getReflectionEffect()](#getReflectionEffect--) | การสะท้อน. |
| [setReflectionEffect(IReflection value)](#setReflectionEffect-com.aspose.slides.IReflection-) | การสะท้อน. |
| [getSoftEdgeEffect()](#getSoftEdgeEffect--) | ขอบนุ่ม. |
| [setSoftEdgeEffect(ISoftEdge value)](#setSoftEdgeEffect-com.aspose.slides.ISoftEdge-) | ขอบนุ่ม. |
| [setBlurEffect(double radius, boolean grow)](#setBlurEffect-double-boolean-) | ตั้งค่าเอฟเฟกต์เบลอ. |
| [enableFillOverlayEffect()](#enableFillOverlayEffect--) | เปิดใช้งานเอฟเฟกต์การซ้อนเติม. |
| [enableGlowEffect()](#enableGlowEffect--) | เปิดใช้งานเอฟเฟกต์เรืองแสง. |
| [enableInnerShadowEffect()](#enableInnerShadowEffect--) | เปิดใช้งานเอฟเฟกต์เงาภายใน. |
| [enableOuterShadowEffect()](#enableOuterShadowEffect--) | เปิดใช้งานเอฟเฟกต์เงาภายนอก. |
| [enablePresetShadowEffect()](#enablePresetShadowEffect--) | เปิดใช้งานเอฟเฟกต์เงาที่ตั้งค่าล่วงหน้า. |
| [enableReflectionEffect()](#enableReflectionEffect--) | เปิดใช้งานเอฟเฟกต์การสะท้อน. |
| [enableSoftEdgeEffect()](#enableSoftEdgeEffect--) | เปิดใช้งานเอฟเฟกต์ขอบนุ่ม. |
| [disableBlurEffect()](#disableBlurEffect--) | ปิดการใช้งานเอฟเฟกต์เบลอ. |
| [disableFillOverlayEffect()](#disableFillOverlayEffect--) | ปิดการใช้งานเอฟเฟกต์การซ้อนเติม. |
| [disableGlowEffect()](#disableGlowEffect--) | ปิดการใช้งานเอฟเฟกต์เรืองแสง. |
| [disableInnerShadowEffect()](#disableInnerShadowEffect--) | ปิดการใช้งานเอฟเฟกต์เงาภายใน. |
| [disableOuterShadowEffect()](#disableOuterShadowEffect--) | ปิดการใช้งานเอฟเฟกต์เงาภายนอก. |
| [disablePresetShadowEffect()](#disablePresetShadowEffect--) | ปิดการใช้งานเอฟเฟกต์เงาที่ตั้งค่าล่วงหน้า. |
| [disableReflectionEffect()](#disableReflectionEffect--) | ปิดการใช้งานเอฟเฟกต์การสะท้อน. |
| [disableSoftEdgeEffect()](#disableSoftEdgeEffect--) | ปิดการใช้งานเอฟเฟกต์ขอบนุ่ม. |
| [getEffective()](#getEffective--) | ดึงข้อมูลการจัดรูปแบบเอฟเฟกต์ที่มีผลโดยคำนึงถึงการสืบทอด. |

### isNoEffects() {#isNoEffects--}
```
public abstract boolean isNoEffects()
```

คืนค่า true หากเอฟเฟกต์ทั้งหมดถูกปิด (เช่น เพิ่งสร้าง, วัตถุ EffectFormat เริ่มต้น) ตัวแปร boolean แบบอ่านอย่างเดียว.

**คืนค่า:**
boolean

### getBlurEffect() {#getBlurEffect--}
```
public abstract IBlur getBlurEffect()
```

เอฟเฟกต์เบลอ. อ่าน/เขียน [IBlur](../../com.aspose.slides/iblur).

**คืนค่า:**
[IBlur](../../com.aspose.slides/iblur)

### setBlurEffect(IBlur value) {#setBlurEffect-com.aspose.slides.IBlur-}
```
public abstract void setBlurEffect(IBlur value)
```

เอฟเฟกต์เบลอ. อ่าน/เขียน [IBlur](../../com.aspose.slides/iblur).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | [IBlur](../../com.aspose.slides/iblur) |  |

### getFillOverlayEffect() {#getFillOverlayEffect--}
```
public abstract IFillOverlay getFillOverlayEffect()
```

เอฟเฟกต์การซ้อนเติม. อ่าน/เขียน [IFillOverlay](../../com.aspose.slides/ifilloverlay).

**คืนค่า:**
[IFillOverlay](../../com.aspose.slides/ifilloverlay)

### setFillOverlayEffect(IFillOverlay value) {#setFillOverlayEffect-com.aspose.slides.IFillOverlay-}
```
public abstract void setFillOverlayEffect(IFillOverlay value)
```

เอฟเฟกต์การซ้อนเติม. อ่าน/เขียน [IFillOverlay](../../com.aspose.slides/ifilloverlay).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | [IFillOverlay](../../com.aspose.slides/ifilloverlay) |  |

### getGlowEffect() {#getGlowEffect--}
```
public abstract IGlow getGlowEffect()
```

เอฟเฟกต์เรืองแสง. อ่าน/เขียน [IGlow](../../com.aspose.slides/iglow).

**คืนค่า:**
[IGlow](../../com.aspose.slides/iglow)

### setGlowEffect(IGlow value) {#setGlowEffect-com.aspose.slides.IGlow-}
```
public abstract void setGlowEffect(IGlow value)
```

เอฟเฟกต์เรืองแสง. อ่าน/เขียน [IGlow](../../com.aspose.slides/iglow).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | [IGlow](../../com.aspose.slides/iglow) |  |

### getInnerShadowEffect() {#getInnerShadowEffect--}
```
public abstract IInnerShadow getInnerShadowEffect()
```

เงาภายใน. อ่าน/เขียน [IInnerShadow](../../com.aspose.slides/iinnershadow).

**คืนค่า:**
[IInnerShadow](../../com.aspose.slides/iinnershadow)

### setInnerShadowEffect(IInnerShadow value) {#setInnerShadowEffect-com.aspose.slides.IInnerShadow-}
```
public abstract void setInnerShadowEffect(IInnerShadow value)
```

เงาภายใน. อ่าน/เขียน [IInnerShadow](../../com.aspose.slides/iinnershadow).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | [IInnerShadow](../../com.aspose.slides/iinnershadow) |  |

### getOuterShadowEffect() {#getOuterShadowEffect--}
```
public abstract IOuterShadow getOuterShadowEffect()
```

เงาภายนอก. อ่าน/เขียน [IOuterShadow](../../com.aspose.slides/ioutershadow).

**คืนค่า:**
[IOuterShadow](../../com.aspose.slides/ioutershadow)

### setOuterShadowEffect(IOuterShadow value) {#setOuterShadowEffect-com.aspose.slides.IOuterShadow-}
```
public abstract void setOuterShadowEffect(IOuterShadow value)
```

เงาภายนอก. อ่าน/เขียน [IOuterShadow](../../com.aspose.slides/ioutershadow).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | [IOuterShadow](../../com.aspose.slides/ioutershadow) |  |

### getPresetShadowEffect() {#getPresetShadowEffect--}
```
public abstract IPresetShadow getPresetShadowEffect()
```

เงาที่ตั้งค่าล่วงหน้า. อ่าน/เขียน [IPresetShadow](../../com.aspose.slides/ipresetshadow).

**คืนค่า:**
[IPresetShadow](../../com.aspose.slides/ipresetshadow)

### setPresetShadowEffect(IPresetShadow value) {#setPresetShadowEffect-com.aspose.slides.IPresetShadow-}
```
public abstract void setPresetShadowEffect(IPresetShadow value)
```

เงาที่ตั้งค่าล่วงหน้า. อ่าน/เขียน [IPresetShadow](../../com.aspose.slides/ipresetshadow).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | [IPresetShadow](../../com.aspose.slides/ipresetshadow) |  |

### getReflectionEffect() {#getReflectionEffect--}
```
public abstract IReflection getReflectionEffect()
```

การสะท้อน. อ่าน/เขียน [IReflection](../../com.aspose.slides/ireflection).

**คืนค่า:**
[IReflection](../../com.aspose.slides/ireflection)

### setReflectionEffect(IReflection value) {#setReflectionEffect-com.aspose.slides.IReflection-}
```
public abstract void setReflectionEffect(IReflection value)
```

การสะท้อน. อ่าน/เขียน [IReflection](../../com.aspose.slides/ireflection).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | [IReflection](../../com.aspose.slides/ireflection) |  |

### getSoftEdgeEffect() {#getSoftEdgeEffect--}
```
public abstract ISoftEdge getSoftEdgeEffect()
```

ขอบนุ่ม. อ่าน/เขียน [ISoftEdge](../../com.aspose.slides/isoftedge).

**คืนค่า:**
[ISoftEdge](../../com.aspose.slides/isoftedge)

### setSoftEdgeEffect(ISoftEdge value) {#setSoftEdgeEffect-com.aspose.slides.ISoftEdge-}
```
public abstract void setSoftEdgeEffect(ISoftEdge value)
```

ขอบนุ่ม. อ่าน/เขียน [ISoftEdge](../../com.aspose.slides/isoftedge).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | [ISoftEdge](../../com.aspose.slides/isoftedge) |  |

### setBlurEffect(double radius, boolean grow) {#setBlurEffect-double-boolean-}
```
public abstract void setBlurEffect(double radius, boolean grow)
```

ตั้งค่าเอฟเฟกต์เบลอ.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| radius | double | รัศมี. |
| grow | boolean | ขยาย. |

### enableFillOverlayEffect() {#enableFillOverlayEffect--}
```
public abstract void enableFillOverlayEffect()
```

เปิดใช้งานเอฟเฟกต์การซ้อนเติม.

### enableGlowEffect() {#enableGlowEffect--}
```
public abstract void enableGlowEffect()
```

เปิดใช้งานเอฟเฟกต์เรืองแสง.

### enableInnerShadowEffect() {#enableInnerShadowEffect--}
```
public abstract void enableInnerShadowEffect()
```

เปิดใช้งานเอฟเฟกต์เงาภายใน.

### enableOuterShadowEffect() {#enableOuterShadowEffect--}
```
public abstract void enableOuterShadowEffect()
```

เปิดใช้งานเอฟเฟกต์เงาภายนอก.

### enablePresetShadowEffect() {#enablePresetShadowEffect--}
```
public abstract void enablePresetShadowEffect()
```

เปิดใช้งานเอฟเฟกต์เงาที่ตั้งค่าล่วงหน้า.

### enableReflectionEffect() {#enableReflectionEffect--}
```
public abstract void enableReflectionEffect()
```

เปิดใช้งานเอฟเฟกต์การสะท้อน.

### enableSoftEdgeEffect() {#enableSoftEdgeEffect--}
```
public abstract void enableSoftEdgeEffect()
```

เปิดใช้งานเอฟเฟกต์ขอบนุ่ม.

### disableBlurEffect() {#disableBlurEffect--}
```
public abstract void disableBlurEffect()
```

ปิดการใช้งานเอฟเฟกต์เบลอ.

### disableFillOverlayEffect() {#disableFillOverlayEffect--}
```
public abstract void disableFillOverlayEffect()
```

ปิดการใช้งานเอฟเฟกต์การซ้อนเติม.

### disableGlowEffect() {#disableGlowEffect--}
```
public abstract void disableGlowEffect()
```

ปิดการใช้งานเอฟเฟกต์เรืองแสง.

### disableInnerShadowEffect() {#disableInnerShadowEffect--}
```
public abstract void disableInnerShadowEffect()
```

ปิดการใช้งานเอฟเฟกต์เงาภายใน.

### disableOuterShadowEffect() {#disableOuterShadowEffect--}
```
public abstract void disableOuterShadowEffect()
```

ปิดการใช้งานเอฟเฟกต์เงาภายนอก.

### disablePresetShadowEffect() {#disablePresetShadowEffect--}
```
public abstract void disablePresetShadowEffect()
```

ปิดการใช้งานเอฟเฟกต์เงาที่ตั้งค่าล่วงหน้า.

### disableReflectionEffect() {#disableReflectionEffect--}
```
public abstract void disableReflectionEffect()
```

ปิดการใช้งานเอฟเฟกต์การสะท้อน.

### disableSoftEdgeEffect() {#disableSoftEdgeEffect--}
```
public abstract void disableSoftEdgeEffect()
```

ปิดการใช้งานเอฟเฟกต์ขอบนุ่ม.

### getEffective() {#getEffective--}
```
public abstract IEffectFormatEffectiveData getEffective()
```

ดึงข้อมูลการจัดรูปแบบเอฟเฟกต์ที่มีผลโดยคำนึงถึงการสืบทอด.

**คืนค่า:**
[IEffectFormatEffectiveData](../../com.aspose.slides/ieffectformateffectivedata) - หนึ่ง [IEffectFormatEffectiveData](../../com.aspose.slides/ieffectformateffectivedata).