---
title: JoinBlock()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: เชื่อมต่อบล็อกคณิตศาสตร์อื่นกับบล็อกนี้
type: docs
weight: 27
url: /th/aspose.slides.mathtext/imathblock/joinblock/
---
## IMathBlock::JoinBlock(System::SharedPtr\<IMathBlock\>) เมธอด

เชื่อมต่อบล็อกคณิตศาสตร์อื่นกับบล็อกนี้

```cpp
virtual System::SharedPtr<IMathBlock> Aspose::Slides::MathText::IMathBlock::JoinBlock(System::SharedPtr<IMathBlock> other)=0
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| other | [System::SharedPtr](../../../system/sharedptr/)\<[IMathBlock](../)\> | บล็อกที่เชื่อมต่อ |

### ค่าที่ส่งคืน

บล็อกคณิตศาสตร์นี้หลังการเชื่อมต่อ
## หมายเหตุ



ตัวอย่าง: 
```cpp
auto block1 = System::MakeObject<MathSuperscriptElement>(
    System::MakeObject<MathematicalText>(u"c"),
    System::MakeObject<MathematicalText>(u"2")
)->Join(System::MakeObject<MathematicalText>(u"="));
auto block2 = System::MakeObject<MathSuperscriptElement>(
    System::MakeObject<MathematicalText>(u"a"),
    System::MakeObject<MathematicalText>(u"2")
)->Join(System::MakeObject<MathematicalText>(u"+"))->Join(System::MakeObject<MathSuperscriptElement>(System::MakeObject<MathematicalText>(u"b"), System::MakeObject<MathematicalText>(u"2")));
auto block3 = block1->JoinBlock(block2);
```

## ดูเพิ่ม

* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [IMathBlock](../)
* เนมสเปซ [Aspose::Slides::MathText](../../)
* ไลบรารี [Aspose.Slides](../../../)