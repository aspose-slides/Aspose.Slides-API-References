---
title: SetSubscript()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: สร้างตัวห้อย
type: docs
weight: 66
url: /th/aspose.slides.mathtext/mathelementbase/setsubscript/
---
## MathElementBase::SetSubscript(System::SharedPtr\<IMathElement\>) เมธอด

สร้างตัวห้อย

```cpp
System::SharedPtr<IMathSubscriptElement> Aspose::Slides::MathText::MathElementBase::SetSubscript(System::SharedPtr<IMathElement> subscript) override
```

### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| subscript | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | ตัวห้อย (ดัชนีล่างที่ด้านขวา) |

### ค่าที่คืน

New math element of type [IMathSubscriptElement](../../imathsubscriptelement/)

## หมายเหตุ



ตัวอย่าง: 
```cpp
auto element = System::MakeObject<MathematicalText>(u"N");
auto index = System::MakeObject<MathematicalText>(u"i");
auto subscript = element->SetSubscript(index);
```

## MathElementBase::SetSubscript(System::String) เมธอด

สร้างตัวห้อย

```cpp
System::SharedPtr<IMathSubscriptElement> Aspose::Slides::MathText::MathElementBase::SetSubscript(System::String subscript) override
```

### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| subscript | [System::String](../../../system/string/) | ตัวห้อย (ดัชนีล่างที่ด้านขวา) |

### ค่าที่คืน

New math element of type [IMathSubscriptElement](../../imathsubscriptelement/)

## หมายเหตุ



ตัวอย่าง: 
```cpp
auto element = System::MakeObject<MathematicalText>(u"N");
auto subscript = element->SetSubscript(u"i");
```

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [IMathSubscriptElement](../../imathsubscriptelement/)
* คลาส [IMathElement](../../imathelement/)
* คลาส [MathElementBase](../)
* คลาส [String](../../../system/string/)
* เนมสเปซ [Aspose::Slides::MathText](../../)
* ไลบรารี [Aspose.Slides](../../../)