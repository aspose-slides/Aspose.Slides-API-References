---
title: SetSubSuperscriptOnTheRight()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: สร้างตัวห้อยและตัวยกบนด้านขวา
type: docs
weight: 105
url: /th/aspose.slides.mathtext/imathelement/setsubsuperscriptontheright/
---
## IMathElement::SetSubSuperscriptOnTheRight(System::SharedPtr\<IMathElement\>, System::SharedPtr\<IMathElement\>) เมธอด

สร้างตัวห้อยและตัวยกบนด้านขวา

```cpp
virtual System::SharedPtr<IMathRightSubSuperscriptElement> Aspose::Slides::MathText::IMathElement::SetSubSuperscriptOnTheRight(System::SharedPtr<IMathElement> subscript, System::SharedPtr<IMathElement> superscript)=0
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| subscript | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../)\> | ตัวห้อย (ดัชนีล่างด้านขวา) |
| superscript | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../)\> | ตัวยกบน (ดัชนีบนด้านขวา) |

### ค่าที่คืนกลับ

อิลิเมนต์คณิตศาสตร์ใหม่ประเภท [IMathRightSubSuperscriptElement](../../imathrightsubsuperscriptelement/)

## หมายเหตุ

ตัวอย่าง: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"N");
auto subscript = System::MakeObject<MathematicalText>(u"i");
auto superscript = System::MakeObject<MathematicalText>(u"j");
auto subsuperscript = baseElement->SetSubSuperscriptOnTheRight(subscript, superscript);
```

## IMathElement::SetSubSuperscriptOnTheRight(System::String, System::String) เมธอด

สร้างตัวห้อยและตัวยกบนด้านขวา

```cpp
virtual System::SharedPtr<IMathRightSubSuperscriptElement> Aspose::Slides::MathText::IMathElement::SetSubSuperscriptOnTheRight(System::String subscript, System::String superscript)=0
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| subscript | [System::String](../../../system/string/) | ตัวห้อย (ดัชนีล่างด้านขวา) |
| superscript | [System::String](../../../system/string/) | ตัวยกบน (ดัชนีบนด้านขวา) |

### ค่าที่คืนกลับ

อิลิเมนต์คณิตศาสตร์ใหม่ประเภท [IMathRightSubSuperscriptElement](../../imathrightsubsuperscriptelement/)

## หมายเหตุ

ตัวอย่าง: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"N");
auto subsuperscript = baseElement->SetSubSuperscriptOnTheRight(u"i", u"j");
```

## ดูเพิ่มเติม

* ชนิดนิยาม [SharedPtr](../../../system/sharedptr/)
* คลาส [IMathRightSubSuperscriptElement](../../imathrightsubsuperscriptelement/)
* คลาส [IMathElement](../)
* คลาส [String](../../../system/string/)
* เนมสเปซ [Aspose::Slides::MathText](../../)
* ไลบรารี [Aspose.Slides](../../../)