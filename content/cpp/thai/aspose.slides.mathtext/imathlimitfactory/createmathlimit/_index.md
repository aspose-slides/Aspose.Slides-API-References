---
title: CreateMathLimit()
second_title: Aspose.Slides สำหรับ C++ เอกสารอ้างอิง API
description: สร้าง IMathLimit
type: docs
weight: 1
url: /th/aspose.slides.mathtext/imathlimitfactory/createmathlimit/
---
## IMathLimitFactory::CreateMathLimit(System::SharedPtr\<IMathElement\>, System::SharedPtr\<IMathElement\>, bool) เมธอด


สร้าง [IMathLimit](../../imathlimit/)

```cpp
virtual System::SharedPtr<IMathLimit> Aspose::Slides::MathText::IMathLimitFactory::CreateMathLimit(System::SharedPtr<IMathElement> baseArg, System::SharedPtr<IMathElement> limit, bool upperLimit)=0
```


### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| baseArg | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | อาร์กิวเมนต์ฐานสำหรับใช้จำกัด |
| limit | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | องค์ประกอบจำกัด |
| upperLimit | **bool** | กำหนดตำแหน่งของจำกัดที่ด้านบน |

### ค่าที่คืน

การจำกัดคณิตศาสตร์ใหม่

## IMathLimitFactory::CreateMathLimit(System::SharedPtr\<IMathElement\>, System::SharedPtr\<IMathElement\>) เมธอด


สร้าง [IMathLimit](../../imathlimit/) พร้อมจำกัดที่ด้านล่าง

```cpp
virtual System::SharedPtr<IMathLimit> Aspose::Slides::MathText::IMathLimitFactory::CreateMathLimit(System::SharedPtr<IMathElement> baseArg, System::SharedPtr<IMathElement> limit)=0
```


### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| baseArg | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | อาร์กิวเมนต์ฐานสำหรับใช้จำกัด |
| limit | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | องค์ประกอบจำกัด |

### ค่าที่คืน

การจำกัดคณิตศาสตร์ใหม่

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [IMathLimit](../../imathlimit/)
* คลาส [IMathElement](../../imathelement/)
* คลาส [IMathLimitFactory](../)
* เนมสเปซ [Aspose::Slides::MathText](../../)
* ไลบรารี [Aspose.Slides](../../../)