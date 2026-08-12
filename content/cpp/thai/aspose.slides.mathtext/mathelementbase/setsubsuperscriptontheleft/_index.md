---
title: SetSubSuperscriptOnTheLeft()
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: สร้างตัวห้อยและตัวยกบนฝั่งซ้าย
type: docs
weight: 105
url: /th/aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft/
---
## MathElementBase::SetSubSuperscriptOnTheLeft(System::SharedPtr\<IMathElement\>, System::SharedPtr\<IMathElement\>) เมธอด

สร้างตัวห้อยและตัวยกบนฝั่งซ้าย

```cpp
System::SharedPtr<IMathLeftSubSuperscriptElement> Aspose::Slides::MathText::MathElementBase::SetSubSuperscriptOnTheLeft(System::SharedPtr<IMathElement> subscript, System::SharedPtr<IMathElement> superscript) override
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| subscript | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | ตัวห้อย (เลขดัชนีล่างบนฝั่งซ้าย) |
| superscript | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | ตัวยก (เลขดัชนีบนบนฝั่งซ้าย) |

### ค่าที่ส่งกลับ

อิลิเมนต์คณิตศาสตร์ใหม่ชนิด [IMathLeftSubSuperscriptElement](../../imathleftsubsuperscriptelement/)

## หมายเหตุ



ตัวอย่าง: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"N");
auto subscript = System::MakeObject<MathematicalText>(u"i");
auto superscript = System::MakeObject<MathematicalText>(u"j");
auto leftSubsuperscript = baseElement->SetSubSuperscriptOnTheLeft(subscript, superscript);
```

## MathElementBase::SetSubSuperscriptOnTheLeft(System::String, System::String) เมธอด

สร้างตัวห้อยและตัวยกบนฝั่งซ้าย

```cpp
System::SharedPtr<IMathLeftSubSuperscriptElement> Aspose::Slides::MathText::MathElementBase::SetSubSuperscriptOnTheLeft(System::String subscript, System::String superscript) override
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| subscript | [System::String](../../../system/string/) | ตัวห้อย (เลขดัชนีล่างบนฝั่งซ้าย) |
| superscript | [System::String](../../../system/string/) | ตัวยก (เลขดัชนีบนบนฝั่งซ้าย) |

### ค่าที่ส่งกลับ

อิลิเมนต์คณิตศาสตร์ใหม่ชนิด [IMathLeftSubSuperscriptElement](../../imathleftsubsuperscriptelement/)

## หมายเหตุ



ตัวอย่าง: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"N");
auto leftSubsuperscript = baseElement->SetSubSuperscriptOnTheLeft(u"i", u"j");
```

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [IMathLeftSubSuperscriptElement](../../imathleftsubsuperscriptelement/)
* คลาส [IMathElement](../../imathelement/)
* คลาส [MathElementBase](../)
* คลาส [String](../../../system/string/)
* เนมสเปซ [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)