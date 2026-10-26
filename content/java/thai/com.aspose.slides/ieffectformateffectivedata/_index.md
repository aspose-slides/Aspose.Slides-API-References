---
title: IEffectFormatEffectiveData
second_title: Aspose.Slides สำหรับ Java การอ้างอิง API
description: อ็อบเจกต์ที่ไม่เปลี่ยนแปลงซึ่งมีคุณสมบัติการจัดรูปแบบเอฟเฟ็กต์ที่มีผลจริง.
type: docs
url: /th/com.aspose.slides/ieffectformateffectivedata/
---
**อินเทอร์เฟซที่ใช้งานทั้งหมด:**
[com.aspose.slides.IEffectParamSource](../../com.aspose.slides/ieffectparamsource)
```
public interface IEffectFormatEffectiveData extends IEffectParamSource
```

อ็อบเจกต์ที่ไม่เปลี่ยนแปลงซึ่งมีคุณสมบัติการจัดรูปแบบเอฟเฟ็กต์ที่มีผลจริง.

--------------------

อินเทอร์เฟซนี้ใช้ร่วมกับอินเทอร์เฟซ [IEffectFormat](../../com.aspose.slides/ieffectformat) เพื่อคืนค่าการจัดรูปแบบที่มีผลโดยใช้การสืบทอด
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [isNoEffects()](#isNoEffects--) | คืนค่า true หากเอฟเฟ็กต์ทั้งหมดถูกปิด (เช่น เมื่อสร้างใหม่, อ็อบเจกต์ EffectFormat เริ่มต้น). |
| [getBlurEffect()](#getBlurEffect--) | เอฟเฟ็กต์เบลอร์. |
| [getFillOverlayEffect()](#getFillOverlayEffect--) | เอฟเฟ็กต์การทับด้วยสีเติม. |
| [getGlowEffect()](#getGlowEffect--) | เอฟเฟ็กต์เรืองแสง. |
| [getInnerShadowEffect()](#getInnerShadowEffect--) | เงาภายใน. |
| [getOuterShadowEffect()](#getOuterShadowEffect--) | เงาภายนอก. |
| [getPresetShadowEffect()](#getPresetShadowEffect--) | เงาที่ตั้งล่วงหน้า. |
| [getReflectionEffect()](#getReflectionEffect--) | การสะท้อน. |
| [getSoftEdgeEffect()](#getSoftEdgeEffect--) | ขอบนุ่มนวล. |
### isNoEffects() {#isNoEffects--}
```
public abstract boolean isNoEffects()
```


คืนค่า true หากเอฟเฟ็กต์ทั้งหมดถูกปิด (เช่น เมื่อสร้างใหม่, อ็อบเจกต์ EffectFormat เริ่มต้น). Boolean แบบอ่านอย่างเดียว.

**คืนค่า:**
boolean
### getBlurEffect() {#getBlurEffect--}
```
public abstract IBlurEffectiveData getBlurEffect()
```


เอฟเฟ็กต์เบลอร์. แบบอ่านอย่างเดียว [IBlurEffectiveData](../../com.aspose.slides/iblureffectivedata).

**คืนค่า:**
[IBlurEffectiveData](../../com.aspose.slides/iblureffectivedata)
### getFillOverlayEffect() {#getFillOverlayEffect--}
```
public abstract IFillOverlayEffectiveData getFillOverlayEffect()
```


เอฟเฟ็กต์การทับด้วยสีเติม. แบบอ่านอย่างเดียว [IFillOverlayEffectiveData](../../com.aspose.slides/ifilloverlayeffectivedata).

**คืนค่า:**
[IFillOverlayEffectiveData](../../com.aspose.slides/ifilloverlayeffectivedata)
### getGlowEffect() {#getGlowEffect--}
```
public abstract IGlowEffectiveData getGlowEffect()
```


เอฟเฟ็กต์เรืองแสง. แบบอ่านอย่างเดียว [IGlowEffectiveData](../../com.aspose.slides/igloweffectivedata).

**คืนค่า:**
[IGlowEffectiveData](../../com.aspose.slides/igloweffectivedata)
### getInnerShadowEffect() {#getInnerShadowEffect--}
```
public abstract IInnerShadowEffectiveData getInnerShadowEffect()
```


เงาภายใน. แบบอ่านอย่างเดียว [IInnerShadowEffectiveData](../../com.aspose.slides/iinnershadoweffectivedata).

**คืนค่า:**
[IInnerShadowEffectiveData](../../com.aspose.slides/iinnershadoweffectivedata)
### getOuterShadowEffect() {#getOuterShadowEffect--}
```
public abstract IOuterShadowEffectiveData getOuterShadowEffect()
```


เงาภายนอก. แบบอ่านอย่างเดียว [IOuterShadowEffectiveData](../../com.aspose.slides/ioutershadoweffectivedata).

**คืนค่า:**
[IOuterShadowEffectiveData](../../com.aspose.slides/ioutershadoweffectivedata)
### getPresetShadowEffect() {#getPresetShadowEffect--}
```
public abstract IPresetShadowEffectiveData getPresetShadowEffect()
```


เงาที่ตั้งล่วงหน้า. แบบอ่านอย่างเดียว [IPresetShadowEffectiveData](../../com.aspose.slides/ipresetshadoweffectivedata).

**คืนค่า:**
[IPresetShadowEffectiveData](../../com.aspose.slides/ipresetshadoweffectivedata)
### getReflectionEffect() {#getReflectionEffect--}
```
public abstract IReflectionEffectiveData getReflectionEffect()
```


การสะท้อน. แบบอ่านอย่างเดียว [IReflectionEffectiveData](../../com.aspose.slides/ireflectioneffectivedata).

**คืนค่า:**
[IReflectionEffectiveData](../../com.aspose.slides/ireflectioneffectivedata)
### getSoftEdgeEffect() {#getSoftEdgeEffect--}
```
public abstract ISoftEdgeEffectiveData getSoftEdgeEffect()
```


ขอบนุ่มนวล. แบบอ่านอย่างเดียว [ISoftEdgeEffectiveData](../../com.aspose.slides/isoftedgeeffectivedata).

**คืนค่า:**
[ISoftEdgeEffectiveData](../../com.aspose.slides/isoftedgeeffectivedata)