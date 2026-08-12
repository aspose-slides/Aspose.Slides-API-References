---
title: JoinBlock()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: เชื่อมบล็อกทางคณิตศาสตร์อื่นกับบล็อกนี้
type: docs
weight: 196
url: /th/aspose.slides.mathtext/mathblock/joinblock/
---
## MathBlock::JoinBlock(System::SharedPtr\<IMathBlock\>) เมธอด


เชื่อมบล็อกทางคณิตศาสตร์อื่นกับบล็อกนี้

```cpp
System::SharedPtr<IMathBlock> Aspose::Slides::MathText::MathBlock::JoinBlock(System::SharedPtr<IMathBlock> other) override
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| other | [System::SharedPtr](../../../system/sharedptr/)\<[IMathBlock](../../imathblock/)\> | บล็อกที่เชื่อม |

### ค่าที่ส่งกลับ

บล็อกทางคณิตศาสตร์นี้หลังจากการเชื่อม
## หมายเหตุ



ตัวอย่าง: 
```cpp
auto block1 = System::MakeObject<MathSuperscriptElement>(System::MakeObject<MathematicalText>(u"c"), System::MakeObject<MathematicalText>(u"2"))->Join(System::MakeObject<MathematicalText>(u"="));
auto block2 = System::MakeObject<MathSuperscriptElement>(System::MakeObject<MathematicalText>(u"a"), System::MakeObject<MathematicalText>(u"2"))->Join(System::MakeObject<MathematicalText>(u"+"))->Join(System::MakeObject<MathSuperscriptElement>(System::MakeObject<MathematicalText>(u"b"), System::MakeObject<MathematicalText>(u"2")));
auto block3 = block1->JoinBlock(block2);
```

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [IMathBlock](../../imathblock/)
* คลาส [MathBlock](../)
* เนมสเปซ [Aspose::Slides::MathText](../../)
* ห้องสมุด [Aspose.Slides](../../../)