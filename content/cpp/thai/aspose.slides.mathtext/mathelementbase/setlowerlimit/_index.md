---
title: SetLowerLimit()
second_title: Aspose.Slides สำหรับ C++ เอกสารอ้างอิง API
description: รับขอบล่าง
type: docs
weight: 144
url: /th/aspose.slides.mathtext/mathelementbase/setlowerlimit/
---
## MathElementBase::SetLowerLimit(System::SharedPtr\<IMathElement\>) เมธอด


รับขอบล่าง

```cpp
System::SharedPtr<IMathLimit> Aspose::Slides::MathText::MathElementBase::SetLowerLimit(System::SharedPtr<IMathElement> limit) override
```


### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| limit | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | limit |

### ค่าที่คืนค่า

อินสแตนซ์ใหม่ของประเภท [IMathLimit](../../imathlimit/)
## หมายเหตุ



ตัวอย่าง: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"lim");
auto limitValue = System::MakeObject<MathematicalText>(u"\U0001d45b→∞");
auto limitElement = baseElement->SetLowerLimit(limitValue);
```

## MathElementBase::SetLowerLimit(System::String) เมธอด


รับขอบล่าง

```cpp
System::SharedPtr<IMathLimit> Aspose::Slides::MathText::MathElementBase::SetLowerLimit(System::String limit) override
```


### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| limit | [System::String](../../../system/string/) | limit |

### ค่าที่คืนค่า

อินสแตนซ์ใหม่ของประเภท [IMathLimit](../../imathlimit/)
## หมายเหตุ



ตัวอย่าง: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"lim");
auto limitElement = baseElement->SetLowerLimit(u"\U0001d45b→∞");
```

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [IMathLimit](../../imathlimit/)
* คลาส [IMathElement](../../imathelement/)
* คลาส [MathElementBase](../)
* คลาส [String](../../../system/string/)
* เนมสเปซ [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)