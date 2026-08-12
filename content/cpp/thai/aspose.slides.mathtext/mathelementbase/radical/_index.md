---
title: Radical()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: ระบุรากคณิตศาสตร์ของดีกรีที่กำหนดจากอาร์กิวเมนต์ที่ระบุ
type: docs
weight: 118
url: /th/aspose.slides.mathtext/mathelementbase/radical/
---
## MathElementBase::Radical(System::SharedPtr\<IMathElement\>) เมธอด

ระบุรากคณิตศาสตร์ของดีกรีที่กำหนดจากอาร์กิวเมนต์ที่ระบุ

```cpp
System::SharedPtr<IMathRadical> Aspose::Slides::MathText::MathElementBase::Radical(System::SharedPtr<IMathElement> degree) override
```

### อาร์กิวเมนท์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| degree | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Argument of Radical |

### ค่าที่ส่งกลับ

New instance of type [IMathRadical](../../imathradical/)
## หมายเหตุ



ตัวอย่าง: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"2px");
auto degree = System::MakeObject<MathematicalText>(u"y");
auto radical = baseElement->Radical(degree);
```

## MathElementBase::Radical(System::String) เมธอด

ระบุรากคณิตศาสตร์ของดีกรีที่กำหนดจากอาร์กิวเมนต์ที่ระบุ

```cpp
System::SharedPtr<IMathRadical> Aspose::Slides::MathText::MathElementBase::Radical(System::String degree) override
```

### อาร์กิวเมนท์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| degree | [System::String](../../../system/string/) | Argument of Radical |

### ค่าที่ส่งกลับ

New instance of type [IMathRadical](../../imathradical/)
## หมายเหตุ



ตัวอย่าง: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"2px");
auto radical = baseElement->Radical(u"3");
```

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [IMathRadical](../../imathradical/)
* คลาส [IMathElement](../../imathelement/)
* คลาส [MathElementBase](../)
* คลาส [String](../../../system/string/)
* เนมสเปซ [Aspose::Slides::MathText](../../)
* ไลบรารี [Aspose.Slides](../../../)