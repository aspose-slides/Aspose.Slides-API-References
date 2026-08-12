---
title: SetSubSuperscriptOnTheRight()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: สร้างตัวห้อยล่างและตัวห้อยบนด้านขวา
type: docs
weight: 92
url: /th/aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright/
---
## MathElementBase::SetSubSuperscriptOnTheRight(System::SharedPtr\<IMathElement\>, System::SharedPtr\<IMathElement\>) เมธอด

สร้างตัวห้อยล่างและตัวห้อยบนด้านขวา

```cpp
System::SharedPtr<IMathRightSubSuperscriptElement> Aspose::Slides::MathText::MathElementBase::SetSubSuperscriptOnTheRight(System::SharedPtr<IMathElement> subscript, System::SharedPtr<IMathElement> superscript) override
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| subscript | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | ตัวห้อยล่าง (ดัชนีล่างทางขวา) |
| superscript | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | ตัวห้อยบน (ดัชนีบนทางขวา) |

### ค่าที่ส่งคืน

องค์ประกอบคณิตศาสตร์ใหม่ประเภท [IMathRightSubSuperscriptElement](../../imathrightsubsuperscriptelement/)
## หมายเหตุ



ตัวอย่าง: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"N");
auto subscript = System::MakeObject<MathematicalText>(u"i");
auto superscript = System::MakeObject<MathematicalText>(u"j");
auto subsuperscript = baseElement->SetSubSuperscriptOnTheRight(subscript, superscript);
```

## MathElementBase::SetSubSuperscriptOnTheRight(System::String, System::String) เมธอด

สร้างตัวห้อยล่างและตัวห้อยบนด้านขวา

```cpp
System::SharedPtr<IMathRightSubSuperscriptElement> Aspose::Slides::MathText::MathElementBase::SetSubSuperscriptOnTheRight(System::String subscript, System::String superscript) override
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| subscript | [System::String](../../../system/string/) | ตัวห้อยล่าง (ดัชนีล่างทางขวา) |
| superscript | [System::String](../../../system/string/) | ตัวห้อยบน (ดัชนีบนทางขวา) |

### ค่าที่ส่งคืน

องค์ประกอบคณิตศาสตร์ใหม่ประเภท [IMathRightSubSuperscriptElement](../../imathrightsubsuperscriptelement/)
## หมายเหตุ



ตัวอย่าง: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"N");
auto subsuperscript = baseElement->SetSubSuperscriptOnTheRight(u"i", u"j");
```

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [IMathRightSubSuperscriptElement](../../imathrightsubsuperscriptelement/)
* คลาส [IMathElement](../../imathelement/)
* คลาส [MathElementBase](../)
* คลาส [String](../../../system/string/)
* เนมสเปซ [Aspose::Slides::MathText](../../)
* ไลบรารี [Aspose.Slides](../../../)