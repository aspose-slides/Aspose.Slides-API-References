---
title: SetSubSuperscriptOnTheLeft()
second_title: Aspose.Slides สำหรับ C++ API อ้างอิง
description: สร้างตัวห้อยและตัวยกทางซ้าย
type: docs
weight: 118
url: /th/aspose.slides.mathtext/imathelement/setsubsuperscriptontheleft/
---
## IMathElement::SetSubSuperscriptOnTheLeft(System::SharedPtr\<IMathElement\>, System::SharedPtr\<IMathElement\>) เมธอด


สร้างตัวห้อยและตัวยกทางซ้าย

```cpp
virtual System::SharedPtr<IMathLeftSubSuperscriptElement> Aspose::Slides::MathText::IMathElement::SetSubSuperscriptOnTheLeft(System::SharedPtr<IMathElement> subscript, System::SharedPtr<IMathElement> superscript)=0
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| subscript | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../)\> | ตัวห้อย (ดัชนีล่างทางซ้าย) |
| superscript | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../)\> | ตัวยก (ดัชนีบนทางซ้าย) |

### ค่าที่ส่งคืน

อิลิเมนต์คณิตศาสตร์ใหม่ประเภท [IMathLeftSubSuperscriptElement](../../imathleftsubsuperscriptelement/)
## หมายเหตุ



ตัวอย่าง: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"N");
auto subscript = System::MakeObject<MathematicalText>(u"i");
auto superscript = System::MakeObject<MathematicalText>(u"j");
auto leftSubsuperscript = baseElement->SetSubSuperscriptOnTheLeft(subscript, superscript);
```

## IMathElement::SetSubSuperscriptOnTheLeft(System::String, System::String) เมธอด


สร้างตัวห้อยและตัวยกทางซ้าย

```cpp
virtual System::SharedPtr<IMathLeftSubSuperscriptElement> Aspose::Slides::MathText::IMathElement::SetSubSuperscriptOnTheLeft(System::String subscript, System::String superscript)=0
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| subscript | [System::String](../../../system/string/) | ตัวห้อย (ดัชนีล่างทางซ้าย) |
| superscript | [System::String](../../../system/string/) | ตัวยก (ดัชนีบนทางซ้าย) |

### ค่าที่ส่งคืน

อิลิเมนต์คณิตศาสตร์ใหม่ประเภท [IMathLeftSubSuperscriptElement](../../imathleftsubsuperscriptelement/)
## หมายเหตุ



ตัวอย่าง: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"N");
auto leftSubsuperscript = baseElement->SetSubSuperscriptOnTheLeft(u"i", u"j");
```

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [IMathLeftSubSuperscriptElement](../../imathleftsubsuperscriptelement/)
* คลาส [IMathElement](../)
* คลาส [String](../../../system/string/)
* เนมสเปซ [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)