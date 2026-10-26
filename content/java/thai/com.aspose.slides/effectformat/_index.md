---
title: EffectFormat
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ Java
description: แสดงคุณสมบัติของเอฟเฟกต์ของรูปร่าง.
type: docs
url: /th/com.aspose.slides/effectformat/
---
**การสืบทอด:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**อินเทอร์เฟซที่ทำการ Implement ทั้งหมด:**
[com.aspose.slides.IEffectFormat](../../com.aspose.slides/ieffectformat)
```
public final class EffectFormat extends PVIObject implements IEffectFormat
```

แสดงคุณสมบัติของเอฟเฟกต์ของรูปร่าง.
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [isNoEffects()](#isNoEffects--) | ส่งคืน true หากเอฟเฟกต์ทั้งหมดถูกปิดใช้งาน (เช่นเดียวกับที่เพิ่งสร้าง, วัตถุ EffectFormat เริ่มต้น). |
| [getBlurEffect()](#getBlurEffect--) | เอฟเฟกต์เบลอ. |
| [setBlurEffect(IBlur value)](#setBlurEffect-com.aspose.slides.IBlur-) | เอฟเฟกต์เบลอ. |
| [getFillOverlayEffect()](#getFillOverlayEffect--) | เอฟเฟกต์การเติมทับ. |
| [setFillOverlayEffect(IFillOverlay value)](#setFillOverlayEffect-com.aspose.slides.IFillOverlay-) | เอฟเฟกต์การเติมทับ. |
| [getGlowEffect()](#getGlowEffect--) | เอฟเฟกต์เรืองแสง. |
| [setGlowEffect(IGlow value)](#setGlowEffect-com.aspose.slides.IGlow-) | เอฟเฟกต์เรืองแสง. |
| [getInnerShadowEffect()](#getInnerShadowEffect--) | เงาภายใน. |
| [setInnerShadowEffect(IInnerShadow value)](#setInnerShadowEffect-com.aspose.slides.IInnerShadow-) | เงาภายใน. |
| [getOuterShadowEffect()](#getOuterShadowEffect--) | เงาภายนอก. |
| [setOuterShadowEffect(IOuterShadow value)](#setOuterShadowEffect-com.aspose.slides.IOuterShadow-) | เงาภายนอก. |
| [getPresetShadowEffect()](#getPresetShadowEffect--) | เงาตั้งค่าเริ่มต้น. |
| [setPresetShadowEffect(IPresetShadow value)](#setPresetShadowEffect-com.aspose.slides.IPresetShadow-) | เงาตั้งค่าเริ่มต้น. |
| [getReflectionEffect()](#getReflectionEffect--) | การสะท้อน. |
| [setReflectionEffect(IReflection value)](#setReflectionEffect-com.aspose.slides.IReflection-) | การสะท้อน. |
| [getSoftEdgeEffect()](#getSoftEdgeEffect--) | ขอบนุ่ม. |
| [setSoftEdgeEffect(ISoftEdge value)](#setSoftEdgeEffect-com.aspose.slides.ISoftEdge-) | ขอบนุ่ม. |
| [setBlurEffect(double radius, boolean grow)](#setBlurEffect-double-boolean-) | ตั้งค่าเอฟเฟกต์เบลอ. |
| [enableFillOverlayEffect()](#enableFillOverlayEffect--) | เปิดใช้งานเอฟเฟกต์การเติมทับ. |
| [enableGlowEffect()](#enableGlowEffect--) | เปิดใช้งานเอฟเฟกต์เรืองแสง. |
| [enableInnerShadowEffect()](#enableInnerShadowEffect--) | เปิดใช้งานเอฟเฟกต์เงาภายใน. |
| [enableOuterShadowEffect()](#enableOuterShadowEffect--) | เปิดใช้งานเอฟเฟกต์เงาภายนอก. |
| [enablePresetShadowEffect()](#enablePresetShadowEffect--) | เปิดใช้งานเอฟเฟกต์เงาตั้งค่าเริ่มต้น. |
| [enableReflectionEffect()](#enableReflectionEffect--) | เปิดใช้งานเอฟเฟกต์การสะท้อน. |
| [enableSoftEdgeEffect()](#enableSoftEdgeEffect--) | เปิดใช้งานเอฟเฟกต์ขอบนุ่ม. |
| [disableBlurEffect()](#disableBlurEffect--) | ปิดการใช้งานเอฟเฟกต์เบลอ. |
| [disableFillOverlayEffect()](#disableFillOverlayEffect--) | ปิดการใช้งานเอฟเฟกต์การเติมทับ. |
| [disableGlowEffect()](#disableGlowEffect--) | ปิดการใช้งานเอฟเฟกต์เรืองแสง. |
| [disableInnerShadowEffect()](#disableInnerShadowEffect--) | ปิดการใช้งานเอฟเฟกต์เงาภายใน. |
| [disableOuterShadowEffect()](#disableOuterShadowEffect--) | ปิดการใช้งานเอฟเฟกต์เงาภายนอก. |
| [disablePresetShadowEffect()](#disablePresetShadowEffect--) | ปิดการใช้งานเอฟเฟกต์เงาตั้งค่าเริ่มต้น. |
| [disableReflectionEffect()](#disableReflectionEffect--) | ปิดการใช้งานเอฟเฟกต์การสะท้อน. |
| [disableSoftEdgeEffect()](#disableSoftEdgeEffect--) | ปิดการใช้งานเอฟเฟกต์ขอบนุ่ม. |
| [getEffective()](#getEffective--) | รับข้อมูลการจัดรูปแบบเอฟเฟกต์ที่มีผลโดยใช้การสืบทอด. |

### getVersion() {#getVersion--}
```
public long getVersion()
```

เวอร์ชัน. อ่านอย่างเดียว long.

**คืนค่า:**
long

### isNoEffects() {#isNoEffects--}
```
public final boolean isNoEffects()
```

ส่งคืน true หากเอฟเฟกต์ทั้งหมดถูกปิดใช้งาน (เช่นเดียวกับที่เพิ่งสร้าง, วัตถุ EffectFormat เริ่มต้น). อ่านอย่างเดียว boolean .

**คืนค่า:**
boolean

### getBlurEffect() {#getBlurEffect--}
```
public final IBlur getBlurEffect()
```

เอฟเฟกต์เบลอ. อ่าน/เขียน [IBlur](../../com.aspose.slides/iblur).

**คืนค่า:**
[IBlur](../../com.aspose.slides/iblur)

### setBlurEffect(IBlur value) {#setBlurEffect-com.aspose.slides.IBlur-}
```
public final void setBlurEffect(IBlur value)
```

เอฟเฟกต์เบลอ. อ่าน/เขียน [IBlur](../../com.aspose.slides/iblur).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | [IBlur](../../com.aspose.slides/iblur) |  |

### getFillOverlayEffect() {#getFillOverlayEffect--}
```
public final IFillOverlay getFillOverlayEffect()
```

เอฟเฟกต์การเติมทับ. อ่าน/เขียน [IFillOverlay](../../com.aspose.slides/ifilloverlay).

**คืนค่า:**
[IFillOverlay](../../com.aspose.slides/ifilloverlay)

### setFillOverlayEffect(IFillOverlay value) {#setFillOverlayEffect-com.aspose.slides.IFillOverlay-}
```
public final void setFillOverlayEffect(IFillOverlay value)
```

เอฟเฟกต์การเติมทับ. อ่าน/เขียน [IFillOverlay](../../com.aspose.slides/ifilloverlay).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | [IFillOverlay](../../com.aspose.slides/ifilloverlay) |  |

### getGlowEffect() {#getGlowEffect--}
```
public final IGlow getGlowEffect()
```

เอฟเฟกต์เรืองแสง. อ่าน/เขียน [IGlow](../../com.aspose.slides/iglow).

**คืนค่า:**
[IGlow](../../com.aspose.slides/iglow)

### setGlowEffect(IGlow value) {#setGlowEffect-com.aspose.slides.IGlow-}
```
public final void setGlowEffect(IGlow value)
```

เอฟเฟกต์เรืองแสง. อ่าน/เขียน [IGlow](../../com.aspose.slides/iglow).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | [IGlow](../../com.aspose.slides/iglow) |  |

### getInnerShadowEffect() {#getInnerShadowEffect--}
```
public final IInnerShadow getInnerShadowEffect()
```

เงาภายใน. อ่าน/เขียน [IInnerShadow](../../com.aspose.slides/iinnershadow).

**คืนค่า:**
[IInnerShadow](../../com.aspose.slides/iinnershadow)

### setInnerShadowEffect(IInnerShadow value) {#setInnerShadowEffect-com.aspose.slides.IInnerShadow-}
```
public final void setInnerShadowEffect(IInnerShadow value)
```

เงาภายใน. อ่าน/เขียน [IInnerShadow](../../com.aspose.slides/iinnershadow).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | [IInnerShadow](../../com.aspose.slides/iinnershadow) |  |

### getOuterShadowEffect() {#getOuterShadowEffect--}
```
public final IOuterShadow getOuterShadowEffect()
```

เงาภายนอก. อ่าน/เขียน [IOuterShadow](../../com.aspose.slides/ioutershadow).

**คืนค่า:**
[IOuterShadow](../../com.aspose.slides/ioutershadow)

### setOuterShadowEffect(IOuterShadow value) {#setOuterShadowEffect-com.aspose.slides.IOuterShadow-}
```
public final void setOuterShadowEffect(IOuterShadow value)
```

เงาภายนอก. อ่าน/เขียน [IOuterShadow](../../com.aspose.slides/ioutershadow).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | [IOuterShadow](../../com.aspose.slides/ioutershadow) |  |

### getPresetShadowEffect() {#getPresetShadowEffect--}
```
public final IPresetShadow getPresetShadowEffect()
```

เงาตั้งค่าเริ่มต้น. อ่าน/เขียน [IPresetShadow](../../com.aspose.slides/ipresetshadow).

**คืนค่า:**
[IPresetShadow](../../com.aspose.slides/ipresetshadow)

### setPresetShadowEffect(IPresetShadow value) {#setPresetShadowEffect-com.aspose.slides.IPresetShadow-}
```
public final void setPresetShadowEffect(IPresetShadow value)
```

เงาตั้งค่าเริ่มต้น. อ่าน/เขียน [IPresetShadow](../../com.aspose.slides/ipresetshadow).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | [IPresetShadow](../../com.aspose.slides/ipresetshadow) |  |

### getReflectionEffect() {#getReflectionEffect--}
```
public final IReflection getReflectionEffect()
```

การสะท้อน. อ่าน/เขียน [IReflection](../../com.aspose.slides/ireflection).

**คืนค่า:**
[IReflection](../../com.aspose.slides/ireflection)

### setReflectionEffect(IReflection value) {#setReflectionEffect-com.aspose.slides.IReflection-}
```
public final void setReflectionEffect(IReflection value)
```

การสะท้อน. อ่าน/เขียน [IReflection](../../com.aspose.slides/ireflection).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | [IReflection](../../com.aspose.slides/ireflection) |  |

### getSoftEdgeEffect() {#getSoftEdgeEffect--}
```
public final ISoftEdge getSoftEdgeEffect()
```

ขอบนุ่ม. อ่าน/เขียน [ISoftEdge](../../com.aspose.slides/isoftedge).

**คืนค่า:**
[ISoftEdge](../../com.aspose.slides/isoftedge)

### setSoftEdgeEffect(ISoftEdge value) {#setSoftEdgeEffect-com.aspose.slides.ISoftEdge-}
```
public final void setSoftEdgeEffect(ISoftEdge value)
```

ขอบนุ่ม. อ่าน/เขียน [ISoftEdge](../../com.aspose.slides/isoftedge).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | [ISoftEdge](../../com.aspose.slides/isoftedge) |  |

### setBlurEffect(double radius, boolean grow) {#setBlurEffect-double-boolean-}
```
public final void setBlurEffect(double radius, boolean grow)
```

ตั้งค่าเอฟเฟกต์เบลอ.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| radius | double | รัศมี. |
| grow | boolean | ขยาย. |

### enableFillOverlayEffect() {#enableFillOverlayEffect--}
```
public final void enableFillOverlayEffect()
```

เปิดใช้งานเอฟเฟกต์การเติมทับ.

### enableGlowEffect() {#enableGlowEffect--}
```
public final void enableGlowEffect()
```

เปิดใช้งานเอฟเฟกต์เรืองแสง.

### enableInnerShadowEffect() {#enableInnerShadowEffect--}
```
public final void enableInnerShadowEffect()
```

เปิดใช้งานเอฟเฟกต์เงาภายใน.

### enableOuterShadowEffect() {#enableOuterShadowEffect--}
```
public final void enableOuterShadowEffect()
```

เปิดใช้งานเอฟเฟกต์เงาภายนอก.

### enablePresetShadowEffect() {#enablePresetShadowEffect--}
```
public final void enablePresetShadowEffect()
```

เปิดใช้งานเอฟเฟกต์เงาตั้งค่าเริ่มต้น.

### enableReflectionEffect() {#enableReflectionEffect--}
```
public final void enableReflectionEffect()
```

เปิดใช้งานเอฟเฟกต์การสะท้อน.

### enableSoftEdgeEffect() {#enableSoftEdgeEffect--}
```
public final void enableSoftEdgeEffect()
```

เปิดใช้งานเอฟเฟกต์ขอบนุ่ม.

### disableBlurEffect() {#disableBlurEffect--}
```
public final void disableBlurEffect()
```

ปิดการใช้งานเอฟเฟกต์เบลอ.

### disableFillOverlayEffect() {#disableFillOverlayEffect--}
```
public final void disableFillOverlayEffect()
```

ปิดการใช้งานเอฟเฟกต์การเติมทับ.

### disableGlowEffect() {#disableGlowEffect--}
```
public final void disableGlowEffect()
```

ปิดการใช้งานเอฟเฟกต์เรืองแสง.

### disableInnerShadowEffect() {#disableInnerShadowEffect--}
```
public final void disableInnerShadowEffect()
```

ปิดการใช้งานเอฟเฟกต์เงาภายใน.

### disableOuterShadowEffect() {#disableOuterShadowEffect--}
```
public final void disableOuterShadowEffect()
```

ปิดการใช้งานเอฟเฟกต์เงาภายนอก.

### disablePresetShadowEffect() {#disablePresetShadowEffect--}
```
public final void disablePresetShadowEffect()
```

ปิดการใช้งานเอฟเฟกต์เงาตั้งค่าเริ่มต้น.

### disableReflectionEffect() {#disableReflectionEffect--}
```
public final void disableReflectionEffect()
```

ปิดการใช้งานเอฟเฟกต์การสะท้อน.

### disableSoftEdgeEffect() {#disableSoftEdgeEffect--}
```
public final void disableSoftEdgeEffect()
```

ปิดการใช้งานเอฟเฟกต์ขอบนุ่ม.

### getEffective() {#getEffective--}
```
public final IEffectFormatEffectiveData getEffective()
```

รับข้อมูลการจัดรูปแบบเอฟเฟกต์ที่มีผลโดยใช้การสืบทอด.

--------------------

> ```
> This example demonstrates getting some of shape's effective effect properties.
>  
>  Presentation pres = new Presentation("MyPresentation.pptx");
>  try
>  {
>  	IEffectFormatEffectiveData effectiveEffectFormat = pres.getSlides().get_Item(0).Shapes().get_Item(0).getEffectFormat().getEffective();
>  	if (effectiveEffectFormat.isNoEffects())
>  	{
>  		System.out.println("The shape has not effects applied.");
>  	}
>  	else
>  	{
>  		if (effectiveEffectFormat.getBlurEffect() != null)
>  			System.out.println("Blur effect radius: " + effectiveEffectFormat.getBlurEffect().getRadius());
>  		if (effectiveEffectFormat.getFillOverlayEffect() != null)
>  			System.out.println("Fill overlay effect fill type: " + effectiveEffectFormat.getFillOverlayEffect().getFillFormat().getFillType());
>  		if (effectiveEffectFormat.getGlowEffect() != null)
>  			System.out.println("Glow effect color: " + effectiveEffectFormat.getGlowEffect().getColor());
>  		if (effectiveEffectFormat.getInnerShadowEffect() != null)
>  			System.out.println("Inner shadow effect shadow color: " + effectiveEffectFormat.getInnerShadowEffect().getShadowColor());
>  		if (effectiveEffectFormat.getOuterShadowEffect() != null)
>  			System.out.println("Outer shadow effect shadow color: " + effectiveEffectFormat.getOuterShadowEffect().getShadowColor());
>  		if (effectiveEffectFormat.getPresetShadowEffect() != null)
>  			System.out.println("Preset shadow effect shadow color: " + effectiveEffectFormat.getPresetShadowEffect().getShadowColor());
>  		if (effectiveEffectFormat.getReflectionEffect() != null)
>  			System.out.println("Reflection effect distance: " + effectiveEffectFormat.getReflectionEffect().getDistance());
>  		if (effectiveEffectFormat.getSoftEdgeEffect() != null)
>  			System.out.println("Soft edge effect radius: " + effectiveEffectFormat.getSoftEdgeEffect().getRadius());
>  	}
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**คืนค่า:**
[IEffectFormatEffectiveData](../../com.aspose.slides/ieffectformateffectivedata) - หนึ่ง [IEffectFormatEffectiveData](../../com.aspose.slides/ieffectformateffectivedata).