---
title: SetSuperscript()
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: สร้างซูเปอร์สคริปต์
type: docs
weight: 79
url: /th/aspose.slides.mathtext/mathelementbase/setsuperscript/
---
## MathElementBase::SetSuperscript(System::SharedPtr\<IMathElement\>) เมธอด

สร้างซูเปอร์สคริปต์

```cpp
System::SharedPtr<IMathSuperscriptElement> Aspose::Slides::MathText::MathElementBase::SetSuperscript(System::SharedPtr<IMathElement> superscript) override
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| superscript | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | ซูเปอร์สคริปต์ (ดัชนีบนขวา) |

### ค่าที่ส่งกลับ

อิลิเมนต์คณิตศาสตร์ใหม่ชนิด [IMathSuperscriptElement](../../imathsuperscriptelement/)
## หมายเหตุ



ตัวอย่าง: 
```cpp
auto element = System::MakeObject<MathematicalText>(u"N");
auto index = System::MakeObject<MathematicalText>(u"4");
auto superscript = element->SetSuperscript(index);
```

## MathElementBase::SetSuperscript(System::String) เมธอด

สร้างซูเปอร์สคริปต์

```cpp
System::SharedPtr<IMathSuperscriptElement> Aspose::Slides::MathText::MathElementBase::SetSuperscript(System::String superscript) override
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| superscript | [System::String](../../../system/string/) | ซูเปอร์สคริปต์ (ดัชนีบนขวา) |

### ค่าที่ส่งกลับ

อิลิเมนต์คณิตศาสตร์ใหม่ชนิด [IMathSuperscriptElement](../../imathsuperscriptelement/)
## หมายเหตุ



ตัวอย่าง: 
```cpp
auto element = System::MakeObject<MathematicalText>(u"N");
auto superscript = element->SetSuperscript(u"4");
```

## ดูเพิ่มเติม

* กำหนดค่า [SharedPtr](../../../system/sharedptr/)
* คลาส [IMathSuperscriptElement](../../imathsuperscriptelement/)
* คลาส [IMathElement](../../imathelement/)
* คลาส [MathElementBase](../)
* คลาส [String](../../../system/string/)
* เนมสเปซ [Aspose::Slides::MathText](../../)
* ไลบรารี [Aspose.Slides](../../../)