---
title: CreateMathFraction()
second_title: Aspose.Slides สำหรับการอ้างอิง API ของ C++
description: สร้างเศษส่วนคณิตศาสตร์
type: docs
weight: 1
url: /th/aspose.slides.mathtext/imathfractionfactory/createmathfraction/
---
## IMathFractionFactory::CreateMathFraction(System::SharedPtr\<IMathElement\>, System::SharedPtr\<IMathElement\>, MathFractionTypes) เมธอด


สร้างเศษส่วนคณิตศาสตร์

```cpp
virtual System::SharedPtr<IMathFraction> Aspose::Slides::MathText::IMathFractionFactory::CreateMathFraction(System::SharedPtr<IMathElement> numerator, System::SharedPtr<IMathElement> denominator, MathFractionTypes fractionType)=0
```


### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| numerator | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | ตัวเศษ |
| denominator | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | ตัวส่วน |
| fractionType | [MathFractionTypes](../../mathfractiontypes/) | ประเภทเศษส่วน |

### ค่าที่ส่งกลับ

เศษส่วนคณิตศาสตร์ใหม่ [IMathFraction](../../imathfraction/)

## IMathFractionFactory::CreateMathFraction(System::SharedPtr\<IMathElement\>, System::SharedPtr\<IMathElement\>) เมธอด


สร้างเศษส่วนคณิตศาสตร์

```cpp
virtual System::SharedPtr<IMathFraction> Aspose::Slides::MathText::IMathFractionFactory::CreateMathFraction(System::SharedPtr<IMathElement> numerator, System::SharedPtr<IMathElement> denominator)=0
```


### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| numerator | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | ตัวเศษ |
| denominator | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | ตัวส่วน |

### ค่าที่ส่งกลับ

เศษส่วนคณิตศาสตร์ใหม่ [IMathFraction](../../imathfraction/)

## ดูเพิ่มเติม

* Enum [MathFractionTypes](../../mathfractiontypes/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IMathFraction](../../imathfraction/)
* Class [IMathElement](../../imathelement/)
* Class [IMathFractionFactory](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)