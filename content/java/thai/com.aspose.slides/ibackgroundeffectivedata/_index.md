---
title: IBackgroundEffectiveData
second_title: Aspose.Slides สำหรับอ้างอิง API ของ Java
description: อ็อบเจ็กต์ที่ไม่สามารถแก้ไขได้ซึ่งบรรจุคุณสมบัติพื้นหลังที่มีผลจริง
type: docs
url: /th/com.aspose.slides/ibackgroundeffectivedata/
---
**อินเทอร์เฟซที่ทำการใช้งานทั้งหมด:**
[com.aspose.slides.IFillParamSource](../../com.aspose.slides/ifillparamsource)
```
public interface IBackgroundEffectiveData extends IFillParamSource
```

อ็อบเจกต์ที่ไม่สามารถแก้ไขได้ซึ่งบรรจุคุณสมบัติพื้นหลังที่มีผลจริง

--------------------

อินเทอร์เฟซนี้ใช้ร่วมกับอินเทอร์เฟซ [IBackground](../../com.aspose.slides/ibackground) เพื่อคืนค่าการจัดรูปแบบที่มีผลโดยมีการสืบทอดที่ใช้
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getFillFormat()](#getFillFormat--) | คืนค่า fill format ที่มีผล. |
| [getEffectFormat()](#getEffectFormat--) | คืนค่า effect format ที่มีผล. |
### getFillFormat() {#getFillFormat--}
```
public abstract IFillFormatEffectiveData getFillFormat()
```


คืนค่า fill format ที่มีผล. อ่านอย่างเดียว [IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata).

**คืนค่า:**
[IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata)
### getEffectFormat() {#getEffectFormat--}
```
public abstract IEffectFormatEffectiveData getEffectFormat()
```


คืนค่า effect format ที่มีผล. อ่านอย่างเดียว [IEffectFormatEffectiveData](../../com.aspose.slides/ieffectformateffectivedata).

**คืนค่า:**
[IEffectFormatEffectiveData](../../com.aspose.slides/ieffectformateffectivedata)