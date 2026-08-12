---
title: SetLowerLimit()
second_title: Aspose.Slides สำหรับ C++ API อ้างอิง
description: รับค่าขอบล่าง
type: docs
weight: 157
url: /th/aspose.slides.mathtext/imathelement/setlowerlimit/
---
## IMathElement::SetLowerLimit(System::SharedPtr\<IMathElement\>) เมธอด

รับค่าขอบล่าง

```cpp
virtual System::SharedPtr<IMathLimit> Aspose::Slides::MathText::IMathElement::SetLowerLimit(System::SharedPtr<IMathElement> limit)=0
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| limit | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../)\> | limit |

### ค่าที่ส่งคืน

อินสแตนซ์ใหม่ของประเภท [IMathLimit](../../imathlimit/)
## หมายเหตุ



ตัวอย่าง: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"lim");
auto limitValue = System::MakeObject<MathematicalText>(u"\U0001d45b→∞");
auto limitElement = baseElement->SetLowerLimit(limitValue);
```

## IMathElement::SetLowerLimit(System::String) เมธอด

รับค่าขอบล่าง

```cpp
virtual System::SharedPtr<IMathLimit> Aspose::Slides::MathText::IMathElement::SetLowerLimit(System::String limit)=0
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| limit | [System::String](../../../system/string/) | limit |

### ค่าที่ส่งคืน

อินสแตนซ์ใหม่ของประเภท [IMathLimit](../../imathlimit/)
## หมายเหตุ



ตัวอย่าง: 
```cpp
System::SharedPtr<IMathElement> baseElement = System::MakeObject<MathematicalText>(u"lim");
auto limitElement = baseElement->SetLowerLimit(u"\U0001d45b→∞");
```

## ดูเพิ่มเติม

* การกำหนดชนิด [SharedPtr](../../../system/sharedptr/)
* คลาส [IMathLimit](../../imathlimit/)
* คลาส [IMathElement](../)
* คลาส [String](../../../system/string/)
* เนมสเปซ [Aspose::Slides::MathText](../../)
* ไลบรารี [Aspose.Slides](../../../)