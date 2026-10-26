---
title: Integral()
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: รับอินทิกรัล
type: docs
weight: 196
url: /th/aspose.slides.mathtext/imathelement/integral/
---
## IMathElement::Integral(MathIntegralTypes, System::SharedPtr\<IMathElement\>, System::SharedPtr\<IMathElement\>, MathLimitLocations) เมธอด

รับอินทิกรัล

```cpp
virtual System::SharedPtr<IMathNaryOperator> Aspose::Slides::MathText::IMathElement::Integral(MathIntegralTypes integralType, System::SharedPtr<IMathElement> lowerLimit, System::SharedPtr<IMathElement> upperLimit, MathLimitLocations limitLocations)=0
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| integralType | [MathIntegralTypes](../../mathintegraltypes/) | ประเภทอินทิกรัล |
| lowerLimit | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../)\> | ขอบล่างของอินทิกลัล |
| upperLimit | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../)\> | ขอบบนของอินทิกลัล |
| limitLocations | [MathLimitLocations](../../mathlimitlocations/) | ตำแหน่งของขอบ |

### ค่าที่ส่งกลับ

อินสแตนซ์ใหม่ของประเภท [IMathNaryOperator](../../imathnaryoperator/)

## หมายเหตุ



ตัวอย่าง: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"\U0001d465");
auto lowerLimit = System::MakeObject<MathematicalText>(u"1");
auto upperLimit = System::MakeObject<MathematicalText>(u"2");
auto integral = baseElement->Integral(MathIntegralTypes::Simple, lowerLimit, upperLimit, MathLimitLocations::UnderOver);
```

## IMathElement::Integral(MathIntegralTypes, System::SharedPtr\<IMathElement\>, System::SharedPtr\<IMathElement\>) เมธอด

รับอินทิกรัล

```cpp
virtual System::SharedPtr<IMathNaryOperator> Aspose::Slides::MathText::IMathElement::Integral(MathIntegralTypes integralType, System::SharedPtr<IMathElement> lowerLimit, System::SharedPtr<IMathElement> upperLimit)=0
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| integralType | [MathIntegralTypes](../../mathintegraltypes/) | ประเภทอินทิกรัล |
| lowerLimit | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../)\> | ขอบล่างของอินทิกลัล |
| upperLimit | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../)\> | ขอบบนของอินทิกลัล |

### ค่าที่ส่งกลับ

อินสแตนซ์ใหม่ของประเภท [IMathNaryOperator](../../imathnaryoperator/)

## หมายเหตุ



ตัวอย่าง: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"\U0001d465");
auto lowerLimit = System::MakeObject<MathematicalText>(u"1");
auto upperLimit = System::MakeObject<MathematicalText>(u"2");
auto integral = baseElement->Integral(MathIntegralTypes::Simple, lowerLimit, upperLimit, MathLimitLocations::UnderOver);
```

## IMathElement::Integral(MathIntegralTypes) เมธอด

รับอินทิกรัลโดยไม่มีขอบ

```cpp
virtual System::SharedPtr<IMathNaryOperator> Aspose::Slides::MathText::IMathElement::Integral(MathIntegralTypes integralType)=0
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| integralType | [MathIntegralTypes](../../mathintegraltypes/) | ประเภทอินทิกรัล |

### ค่าที่ส่งกลับ

อินสแตนซ์ใหม่ของประเภท [IMathNaryOperator](../../imathnaryoperator/)

## หมายเหตุ



ตัวอย่าง: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"\U0001d465");
auto integral = baseElement->Integral(MathIntegralTypes::Contour);
```

## IMathElement::Integral(MathIntegralTypes, System::String, System::String, MathLimitLocations) เมธอด

รับอินทิกรัล

```cpp
virtual System::SharedPtr<IMathNaryOperator> Aspose::Slides::MathText::IMathElement::Integral(MathIntegralTypes integralType, System::String lowerLimit, System::String upperLimit, MathLimitLocations limitLocations)=0
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| integralType | [MathIntegralTypes](../../mathintegraltypes/) | ประเภทอินทิกรัล |
| lowerLimit | [System::String](../../../system/string/) | ขอบล่างของอินทิกลัล |
| upperLimit | [System::String](../../../system/string/) | ขอบบนของอินทิกลัล |
| limitLocations | [MathLimitLocations](../../mathlimitlocations/) | ตำแหน่งของขอบ |

### ค่าที่ส่งกลับ

อินสแตนซ์ใหม่ของประเภท [IMathNaryOperator](../../imathnaryoperator/)

## หมายเหตุ



ตัวอย่าง: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"\U0001d465");
auto integral = baseElement->Integral(MathIntegralTypes::Simple, u"1", u"5", MathLimitLocations::UnderOver);
```

## IMathElement::Integral(MathIntegralTypes, System::String, System::String) เมธอด

รับอินทิกรัล

```cpp
virtual System::SharedPtr<IMathNaryOperator> Aspose::Slides::MathText::IMathElement::Integral(MathIntegralTypes integralType, System::String lowerLimit, System::String upperLimit)=0
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| integralType | [MathIntegralTypes](../../mathintegraltypes/) | ประเภทอินทิกรัล |
| lowerLimit | [System::String](../../../system/string/) | ขอบล่างของอินทิกลัล |
| upperLimit | [System::String](../../../system/string/) | ขอบบนของอินทิกลัล |

### ค่าที่ส่งกลับ

อินสแตนซ์ใหม่ของประเภท [IMathNaryOperator](../../imathnaryoperator/)

## หมายเหตุ



ตัวอย่าง: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"\U0001d465");
auto integral = baseElement->Integral(MathIntegralTypes::Simple, u"1", u"5");
```

## ดูเพิ่มเติม

* Enum [MathIntegralTypes](../../mathintegraltypes/)
* Enum [MathLimitLocations](../../mathlimitlocations/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [IMathNaryOperator](../../imathnaryoperator/)
* คลาส [IMathElement](../)
* คลาส [String](../../../system/string/)
* เนมสเปซ [Aspose::Slides::MathText](../../)
* ไลบรารี [Aspose.Slides](../../../)