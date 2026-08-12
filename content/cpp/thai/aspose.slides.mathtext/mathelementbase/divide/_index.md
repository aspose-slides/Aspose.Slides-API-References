---
title: Divide()
second_title: Aspose.Slides สำหรับ C++ API เอกสารอ้างอิง
description: สร้างเศษส่วนโดยใช้ตัวเศษนี้และตัวหารที่ระบุ
type: docs
weight: 14
url: /th/aspose.slides.mathtext/mathelementbase/divide/
---
## MathElementBase::Divide(System::SharedPtr\<IMathElement\>) เมธอด


สร้างเศษส่วนโดยมีตัวเศษนี้และตัวหารที่ระบุ

```cpp
System::SharedPtr<IMathFraction> Aspose::Slides::MathText::MathElementBase::Divide(System::SharedPtr<IMathElement> denominator) override
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| denominator | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | ตัวหาร |

### ค่าที่ส่งกลับ

เศษส่วนใหม่
## หมายเหตุ



ตัวอย่าง: 
```cpp
auto numerator = System::MakeObject<MathematicalText>(u"x");
auto denumerator = System::MakeObject<MathematicalText>(u"y");
auto fraction = numerator->Divide(denumerator);
```

## MathElementBase::Divide(System::String) เมธอด


สร้างเศษส่วนโดยมีตัวเศษนี้และตัวหารที่ระบุ

```cpp
System::SharedPtr<IMathFraction> Aspose::Slides::MathText::MathElementBase::Divide(System::String denominator) override
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| denominator | [System::String](../../../system/string/) | ตัวหาร |

### ค่าที่ส่งกลับ

เศษส่วนใหม่
## หมายเหตุ



ตัวอย่าง: 
```cpp
auto numerator = System::MakeObject<MathematicalText>(u"x");
auto fraction = numerator->Divide(u"y");
```

## MathElementBase::Divide(System::SharedPtr\<IMathElement\>, MathFractionTypes) เมธอด


สร้างเศษส่วนประเภทที่ระบุโดยมีตัวเศษนี้และตัวหารที่ระบุ

```cpp
System::SharedPtr<IMathFraction> Aspose::Slides::MathText::MathElementBase::Divide(System::SharedPtr<IMathElement> denominator, MathFractionTypes fractionType) override
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| denominator | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | ตัวหาร |
| fractionType | [MathFractionTypes](../../mathfractiontypes/) | ประเภทเศษส่วน: Bar, NoBar, Skewed, Linear |

### ค่าที่ส่งกลับ

เศษส่วนใหม่
## หมายเหตุ



ตัวอย่าง: 
```cpp
auto numerator = System::MakeObject<MathematicalText>(u"x");
auto denumerator = System::MakeObject<MathematicalText>(u"y");
auto fraction = numerator->Divide(denumerator, MathFractionTypes::Linear);
```

## MathElementBase::Divide(System::String, MathFractionTypes) เมธอด


สร้างเศษส่วนประเภทที่ระบุโดยมีตัวเศษนี้และตัวหารที่ระบุ

```cpp
System::SharedPtr<IMathFraction> Aspose::Slides::MathText::MathElementBase::Divide(System::String denominator, MathFractionTypes fractionType) override
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| denominator | [System::String](../../../system/string/) | ตัวหาร |
| fractionType | [MathFractionTypes](../../mathfractiontypes/) | ประเภทเศษส่วน: Bar, NoBar, Skewed, Linear |

### ค่าที่ส่งกลับ

เศษส่วนใหม่
## หมายเหตุ



ตัวอย่าง: 
```cpp
auto numerator = System::MakeObject<MathematicalText>(u"x");
auto fraction = numerator->Divide(u"y", MathFractionTypes::Linear);
```

## ดูเพิ่มเติม

* Enum [MathFractionTypes](../../mathfractiontypes/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IMathFraction](../../imathfraction/)
* Class [IMathElement](../../imathelement/)
* Class [MathElementBase](../)
* Class [String](../../../system/string/)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)