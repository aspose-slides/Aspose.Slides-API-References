---
title: Function()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: รับฟังก์ชันของอาร์กิวเมนต์โดยใช้อินสแตนซ์นี้เป็นชื่อฟังก์ชัน
type: docs
weight: 53
url: /th/aspose.slides.mathtext/imathelement/function/
---
## IMathElement::Function(System::SharedPtr\<IMathElement\>) เมธอด


รับฟังก์ชันของอาร์กิวเมนต์โดยใช้อินสแตนซ์นี้เป็นชื่อฟังก์ชัน

```cpp
virtual System::SharedPtr<IMathFunction> Aspose::Slides::MathText::IMathElement::Function(System::SharedPtr<IMathElement> functionArgument)=0
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| functionArgument | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../)\> | อาร์กิวเมนต์ของฟังก์ชัน |

### ค่าที่ส่งกลับ

New math element of type [IMathFunction](../../imathfunction/)
## หมายเหตุ



ตัวอย่าง: 
```cpp
auto functionName = System::MakeObject<MathematicalText>(u"sin");
auto functionArg = System::MakeObject<MathematicalText>(u"x");
auto func = functionName->Function(functionArg);
```

## IMathElement::Function(System::String) เมธอด


รับฟังก์ชันของอาร์กิวเมนต์โดยใช้อินสแตนซ์นี้เป็นชื่อฟังก์ชัน

```cpp
virtual System::SharedPtr<IMathFunction> Aspose::Slides::MathText::IMathElement::Function(System::String functionArgument)=0
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| functionArgument | [System::String](../../../system/string/) | อาร์กิวเมนต์ของฟังก์ชัน |

### ค่าที่ส่งกลับ

New math element of type [IMathFunction](../../imathfunction/)
## หมายเหตุ



ตัวอย่าง: 
```cpp
auto functionName = System::MakeObject<MathematicalText>(u"sin");
auto func = functionName->Function(u"x");
```

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IMathFunction](../../imathfunction/)
* Class [IMathElement](../)
* Class [String](../../../system/string/)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)