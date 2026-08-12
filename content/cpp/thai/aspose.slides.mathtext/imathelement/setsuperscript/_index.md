---
title: SetSuperscript()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: สร้างซูเปอร์สคริปต์
type: docs
weight: 92
url: /th/aspose.slides.mathtext/imathelement/setsuperscript/
---
## IMathElement::SetSuperscript(System::SharedPtr\<IMathElement\>) method

สร้างซูเปอร์สคริปต์

```cpp
virtual System::SharedPtr<IMathSuperscriptElement> Aspose::Slides::MathText::IMathElement::SetSuperscript(System::SharedPtr<IMathElement> superscript)=0
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| superscript | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../)\> | ซูเปอร์สคริปต์ (ดัชนีบนด้านขวา) |

### ค่าที่คืน

อิลิเมนต์คณิตศาสตร์ใหม่ชนิด [IMathSuperscriptElement](../../imathsuperscriptelement/)
## หมายเหตุ



ตัวอย่าง: 
```cpp
auto element = System::MakeObject<MathematicalText>(u"N");
auto index = System::MakeObject<MathematicalText>(u"4");
auto superscript = element->SetSuperscript(index);
```

## IMathElement::SetSuperscript(System::String) method

สร้างซูเปอร์สคริปต์

```cpp
virtual System::SharedPtr<IMathSuperscriptElement> Aspose::Slides::MathText::IMathElement::SetSuperscript(System::String superscript)=0
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| superscript | [System::String](../../../system/string/) | ซูเปอร์สคริปต์ (ดัชนีบนด้านขวา) |

### ค่าที่คืน

อิลิเมนต์คณิตศาสตร์ใหม่ชนิด [IMathSuperscriptElement](../../imathsuperscriptelement/)
## หมายเหตุ



ตัวอย่าง: 
```cpp
auto element = System::MakeObject<MathematicalText>(u"N");
auto superscript = element->SetSuperscript(u"4");
```

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [IMathSuperscriptElement](../../imathsuperscriptelement/)
* คลาส [IMathElement](../)
* คลาส [String](../../../system/string/)
* เนมสเปซ [Aspose::Slides::MathText](../../)
* ไลบรารี [Aspose.Slides](../../../)