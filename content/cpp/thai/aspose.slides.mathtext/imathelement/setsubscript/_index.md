---
title: SetSubscript()
second_title: เอกสารอ้างอิง API ของ Aspose.Slides สำหรับ C++
description: สร้างตัวห้อย
type: docs
weight: 79
url: /th/aspose.slides.mathtext/imathelement/setsubscript/
---
## IMathElement::SetSubscript(System::SharedPtr\<IMathElement\>) เมธอด

สร้างตัวห้อย

```cpp
virtual System::SharedPtr<IMathSubscriptElement> Aspose::Slides::MathText::IMathElement::SetSubscript(System::SharedPtr<IMathElement> subscript)=0
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| subscript | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../)\> | ตัวห้อย (ดัชนีล่างที่ด้านขวา) |

### ค่าที่ส่งกลับ

อีเลเมนต์คณิตศาสตร์ใหม่ประเภท [IMathSubscriptElement](../../imathsubscriptelement/)
## หมายเหตุ



ตัวอย่าง: 
```cpp
auto element = System::MakeObject<MathematicalText>(u"N");
auto index = System::MakeObject<MathematicalText>(u"i");
auto subscript = element->SetSubscript(index);
```

## IMathElement::SetSubscript(System::String) เมธอด

สร้างตัวห้อย

```cpp
virtual System::SharedPtr<IMathSubscriptElement> Aspose::Slides::MathText::IMathElement::SetSubscript(System::String subscript)=0
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| subscript | [System::String](../../../system/string/) | ตัวห้อย (ดัชนีล่างที่ด้านขวา) |

### ค่าที่ส่งกลับ

อีเลเมนต์คณิตศาสตร์ใหม่ประเภท [IMathSubscriptElement](../../imathsubscriptelement/)
## หมายเหตุ



ตัวอย่าง: 
```cpp
auto element = System::MakeObject<MathematicalText>(u"N");
auto subscript = element->SetSubscript(u"i");
```

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [IMathSubscriptElement](../../imathsubscriptelement/)
* คลาส [IMathElement](../)
* คลาส [String](../../../system/string/)
* เนมสเปซ [Aspose::Slides::MathText](../../)
* ไลบรารี [Aspose.Slides](../../../)