---
title: IEffectFormatEffectiveData
second_title: Aspose.Slides สำหรับ Android ผ่านการอ้างอิง Java API
description: อ็อบเจกต์ที่ไม่เปลี่ยนแปลงซึ่งมีคุณสมบัติการจัดรูปแบบเอฟเฟกต์ที่มีผล
type: docs
url: /th/com.aspose.slides/ieffectformateffectivedata/
---
**ส่วนต่อประสานที่นำไปใช้ทั้งหมด:**
[com.aspose.slides.IEffectParamSource](../../com.aspose.slides/ieffectparamsource)
```
public interface IEffectFormatEffectiveData extends IEffectParamSource
```

อ็อบเจกต์ที่ไม่เปลี่ยนแปลงซึ่งมีคุณสมบัติการจัดรูปแบบเอฟเฟกต์ที่มีผล

--------------------

ส่วนต่อประสานนี้ใช้ร่วมกับส่วนต่อประสาน [IEffectFormat](../../com.aspose.slides/ieffectformat) เพื่อคืนค่า formatting ที่มีประสิทธิภาพโดยมีการสืบทอด

## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [isNoEffects()](#isNoEffects--) | Returns true if all effects are disabled (as just created, default EffectFormat object). |
| [getBlurEffect()](#getBlurEffect--) | Blur effect. |
| [getFillOverlayEffect()](#getFillOverlayEffect--) | Fill overlay effect. |
| [getGlowEffect()](#getGlowEffect--) | Glow effect. |
| [getInnerShadowEffect()](#getInnerShadowEffect--) | Inner shadow. |
| [getOuterShadowEffect()](#getOuterShadowEffect--) | Outer shadow. |
| [getPresetShadowEffect()](#getPresetShadowEffect--) | Preset shadow. |
| [getReflectionEffect()](#getReflectionEffect--) | Reflection. |
| [getSoftEdgeEffect()](#getSoftEdgeEffect--) | Soft edge. |

### isNoEffects() {#isNoEffects--}
```
public abstract boolean isNoEffects()
```

คืนค่า true หากเอฟเฟกต์ทั้งหมดถูกปิดการใช้งาน (เช่นเดียวกับเมื่อสร้างใหม่, วัตถุ EffectFormat เริ่มต้น) แบบอ่านอย่างเดียวบูลีน

**คืนค่า:**
boolean

### getBlurEffect() {#getBlurEffect--}
```
public abstract IBlurEffectiveData getBlurEffect()
```

เอฟเฟกต์เบลอ แบบอ่านอย่างเดียว [IBlurEffectiveData](../../com.aspose.slides/iblureffectivedata)

**คืนค่า:**
[IBlurEffectiveData](../../com.aspose.slides/iblureffectivedata)

### getFillOverlayEffect() {#getFillOverlayEffect--}
```
public abstract IFillOverlayEffectiveData getFillOverlayEffect()
```

เอฟเฟกต์การวางซ้อนเติม แบบอ่านอย่างเดียว [IFillOverlayEffectiveData](../../com.aspose.slides/ifilloverlayeffectivedata)

**คืนค่า:**
[IFillOverlayEffectiveData](../../com.aspose.slides/ifilloverlayeffectivedata)

### getGlowEffect() {#getGlowEffect--}
```
public abstract IGlowEffectiveData getGlowEffect()
```

เอฟเฟกต์เรืองแสง แบบอ่านอย่างเดียว [IGlowEffectiveData](../../com.aspose.slides/igloweffectivedata)

**คืนค่า:**
[IGlowEffectiveData](../../com.aspose.slides/igloweffectivedata)

### getInnerShadowEffect() {#getInnerShadowEffect--}
```
public abstract IInnerShadowEffectiveData getInnerShadowEffect()
```

เงาภายใน แบบอ่านอย่างเดียว [IInnerShadowEffectiveData](../../com.aspose.slides/iinnershadoweffectivedata)

**คืนค่า:**
[IInnerShadowEffectiveData](../../com.aspose.slides/iinnershadoweffectivedata)

### getOuterShadowEffect() {#getOuterShadowEffect--}
```
public abstract IOuterShadowEffectiveData getOuterShadowEffect()
```

เงาภายนอก แบบอ่านอย่างเดียว [IOuterShadowEffectiveData](../../com.aspose.slides/ioutershadoweffectivedata)

**คืนค่า:**
[IOuterShadowEffectiveData](../../com.aspose.slides/ioutershadoweffectivedata)

### getPresetShadowEffect() {#getPresetShadowEffect--}
```
public abstract IPresetShadowEffectiveData getPresetShadowEffect()
```

เงาตั้งค่าเดิม แบบอ่านอย่างเดียว [IPresetShadowEffectiveData](../../com.aspose.slides/ipresetshadoweffectivedata)

**คืนค่า:**
[IPresetShadowEffectiveData](../../com.aspose.slides/ipresetshadoweffectivedata)

### getReflectionEffect() {#getReflectionEffect--}
```
public abstract IReflectionEffectiveData getReflectionEffect()
```

การสะท้อน แบบอ่านอย่างเดียว [IReflectionEffectiveData](../../com.aspose.slides/ireflectioneffectivedata)

**คืนค่า:**
[IReflectionEffectiveData](../../com.aspose.slides/ireflectioneffectivedata)

### getSoftEdgeEffect() {#getSoftEdgeEffect--}
```
public abstract ISoftEdgeEffectiveData getSoftEdgeEffect()
```

ขอบนุ่มนวล แบบอ่านอย่างเดียว [ISoftEdgeEffectiveData](../../com.aspose.slides/isoftedgeeffectivedata)

**คืนค่า:**
[ISoftEdgeEffectiveData](../../com.aspose.slides/isoftedgeeffectivedata)