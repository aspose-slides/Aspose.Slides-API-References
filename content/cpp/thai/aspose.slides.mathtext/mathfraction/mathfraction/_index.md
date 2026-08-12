---
title: MathFraction()
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: กำหนดค่า MathFraction ด้วยตัวเศษ ตัวส่วนและประเภทที่ระบุ
type: docs
weight: 53
url: /th/aspose.slides.mathtext/mathfraction/mathfraction/
---
## MathFraction::MathFraction(System::SharedPtr\<IMathElement\>, System::SharedPtr\<IMathElement\>, MathFractionTypes) คอนสตรัคเตอร์

กำหนดค่า [MathFraction](../) ด้วยตัวเศษ ตัวส่วนและประเภทที่ระบุ

```cpp
Aspose::Slides::MathText::MathFraction::MathFraction(System::SharedPtr<IMathElement> numerator, System::SharedPtr<IMathElement> denominator, MathFractionTypes fractionType)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| numerator | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | ตัวเศษ |
| denominator | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | ตัวส่วน |
| fractionType | [MathFractionTypes](../../mathfractiontypes/) | ประเภทเศษส่วน |
## หมายเหตุ



ตัวอย่าง: 
```cpp
auto mathFraction = System::MakeObject<MathFraction>(System::MakeObject<MathematicalText>(u"x"), System::MakeObject<MathematicalText>(u"y"), MathFractionTypes::Linear);
```

## MathFraction::MathFraction(System::SharedPtr\<IMathElement\>, System::SharedPtr\<IMathElement\>) คอนสตรัคเตอร์

กำหนดค่า [MathFraction](../) ชนิด 'Bar' ด้วยตัวเศษและตัวส่วนที่ระบุ

```cpp
Aspose::Slides::MathText::MathFraction::MathFraction(System::SharedPtr<IMathElement> numerator, System::SharedPtr<IMathElement> denominator)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| numerator | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | ตัวเศษ |
| denominator | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | ตัวส่วน |
## หมายเหตุ



ตัวอย่าง: 
```cpp
auto mathFraction = System::MakeObject<MathFraction>(System::MakeObject<MathematicalText>(u"x"), System::MakeObject<MathematicalText>(u"y"));
```

## ดูเพิ่มเติม

* Enum [MathFractionTypes](../../mathfractiontypes/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IMathElement](../../imathelement/)
* Class [MathFraction](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)