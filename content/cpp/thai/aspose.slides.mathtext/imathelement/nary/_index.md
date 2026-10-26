---
title: Nary()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: สร้างตัวดำเนินการ N-ary
type: docs
weight: 170
url: /th/aspose.slides.mathtext/imathelement/nary/
---
## IMathElement::Nary(MathNaryOperatorTypes, System::SharedPtr\<IMathElement\>, System::SharedPtr\<IMathElement\>) เมธอด

สร้างตัวดำเนินการ N-ary

```cpp
virtual System::SharedPtr<IMathNaryOperator> Aspose::Slides::MathText::IMathElement::Nary(MathNaryOperatorTypes type, System::SharedPtr<IMathElement> lowerLimit, System::SharedPtr<IMathElement> upperLimit)=0
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| type | [MathNaryOperatorTypes](../../mathnaryoperatortypes/) | ประเภทของตัวดำเนินการ N-ary |
| lowerLimit | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../)\> | ขอบล่าง |
| upperLimit | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../)\> | ขอบบน |

### ค่าที่ส่งกลับ

อินสแตนซ์ใหม่ของประเภท [IMathNaryOperator](../../imathnaryoperator/)
## หมายเหตุ



ตัวอย่าง: 
```cpp
System::SharedPtr<IMathElement> baseElement = System::MakeObject<MathematicalText>(u"i-1");
System::SharedPtr<IMathElement> lowerLimit = System::MakeObject<MathematicalText>(u"i=0");
System::SharedPtr<IMathElement> upperLimit = System::MakeObject<MathematicalText>(u"\U0001d45b");
auto naryOperator = baseElement->Nary(MathNaryOperatorTypes::Summation, lowerLimit, upperLimit);
```

## IMathElement::Nary(MathNaryOperatorTypes, System::String, System::String) เมธอด

สร้างตัวดำเนินการ N-ary

```cpp
virtual System::SharedPtr<IMathNaryOperator> Aspose::Slides::MathText::IMathElement::Nary(MathNaryOperatorTypes type, System::String lowerLimit, System::String upperLimit)=0
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| type | [MathNaryOperatorTypes](../../mathnaryoperatortypes/) | ประเภทของตัวดำเนินการ N-ary |
| lowerLimit | [System::String](../../../system/string/) | ขอบล่าง |
| upperLimit | [System::String](../../../system/string/) | ขอบบน |

### ค่าที่ส่งกลับ

อินสแตนซ์ใหม่ของประเภท [IMathNaryOperator](../../imathnaryoperator/)
## หมายเหตุ



ตัวอย่าง: 
```cpp
auto naryOperator = System::MakeObject<MathematicalText>(u"i")->Nary(MathNaryOperatorTypes::Summation, u"i=0", u"\U0001d45b");
```

## ดูเพิ่มเติม

* Enum [MathNaryOperatorTypes](../../mathnaryoperatortypes/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [IMathNaryOperator](../../imathnaryoperator/)
* คลาส [IMathElement](../)
* คลาส [String](../../../system/string/)
* เนมสเปซ [Aspose::Slides::MathText](../../)
* ไลบรารี [Aspose.Slides](../../../)