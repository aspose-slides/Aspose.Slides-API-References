---
title: Divide()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: สร้างเศษส่วนโดยใช้ตัวเศษนี้และตัวส่วนที่ระบุ
type: docs
weight: 27
url: /th/aspose.slides.mathtext/imathelement/divide/
---
## IMathElement::Divide(System::SharedPtr\<IMathElement\>) เมธอด

สร้างเศษส่วนด้วยตัวเศษนี้และตัวส่วนที่ระบุ

```cpp
virtual System::SharedPtr<IMathFraction> Aspose::Slides::MathText::IMathElement::Divide(System::SharedPtr<IMathElement> denominator)=0
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| denominator | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../)\> | ตัวส่วน |

### ค่าที่คืนค่า

เศษส่วนใหม่
## หมายเหตุ



ตัวอย่าง: 
```cpp
auto numerator = System::MakeObject<MathematicalText>(u"x");
auto denumerator = System::MakeObject<MathematicalText>(u"y");
auto fraction = numerator->Divide(denumerator);
```

## IMathElement::Divide(System::String) เมธอด

สร้างเศษส่วนด้วยตัวเศษนี้และตัวส่วนที่ระบุ

```cpp
virtual System::SharedPtr<IMathFraction> Aspose::Slides::MathText::IMathElement::Divide(System::String denominator)=0
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| denominator | [System::String](../../../system/string/) | ตัวส่วน |

### ค่าที่คืนค่า

เศษส่วนใหม่
## หมายเหตุ



ตัวอย่าง: 
```cpp
System::SharedPtr<IMathElement> numerator = System::MakeObject<MathematicalText>(u"x");
auto fraction = numerator->Divide(u"y");
```

## IMathElement::Divide(System::SharedPtr\<IMathElement\>, MathFractionTypes) เมธอด

สร้างเศษส่วนประเภทที่ระบุด้วยตัวเศษนี้และตัวส่วนที่ระบุ

```cpp
virtual System::SharedPtr<IMathFraction> Aspose::Slides::MathText::IMathElement::Divide(System::SharedPtr<IMathElement> denominator, MathFractionTypes fractionType)=0
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| denominator | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../)\> | ตัวส่วน |
| fractionType | [MathFractionTypes](../../mathfractiontypes/) | ประเภทเศษส่วน: Bar, NoBar, Skewed, Linear |

### ค่าที่คืนค่า

เศษส่วนใหม่
## หมายเหตุ



ตัวอย่าง: 
```cpp
auto numerator = System::MakeObject<MathematicalText>(u"x");
auto denumerator = System::MakeObject<MathematicalText>(u"y");
auto fraction = numerator->Divide(denumerator, MathFractionTypes::Linear);
```

## IMathElement::Divide(System::String, MathFractionTypes) เมธอด

สร้างเศษส่วนประเภทที่ระบุด้วยตัวเศษนี้และตัวส่วนที่ระบุ

```cpp
virtual System::SharedPtr<IMathFraction> Aspose::Slides::MathText::IMathElement::Divide(System::String denominator, MathFractionTypes fractionType)=0
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| denominator | [System::String](../../../system/string/) | ตัวส่วน |
| fractionType | [MathFractionTypes](../../mathfractiontypes/) | ประเภทเศษส่วน: Bar, NoBar, Skewed, Linear |

### ค่าที่คืนค่า

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
* คลาส [IMathFraction](../../imathfraction/)
* คลาส [IMathElement](../)
* คลาส [String](../../../system/string/)
* เนมสเปซ [Aspose::Slides::MathText](../../)
* ไลบรารี [Aspose.Slides](../../../)