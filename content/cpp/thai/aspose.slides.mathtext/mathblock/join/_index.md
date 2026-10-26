---
title: Join()
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: ผสานส่วนประกอบคณิตศาสตร์เข้ากับบล็อกคณิตศาสตร์นี้
type: docs
weight: 183
url: /th/aspose.slides.mathtext/mathblock/join/
---
## MathBlock::Join(System::SharedPtr\<IMathElement\>) เมธอด


ผสานส่วนประกอบคณิตศาสตร์เข้ากับบล็อกคณิตศาสตร์นี้

```cpp
System::SharedPtr<IMathBlock> Aspose::Slides::MathText::MathBlock::Join(System::SharedPtr<IMathElement> mathElement) override
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| mathElement | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | ส่วนประกอบที่จะถูกผสาน |

### ค่าที่ส่งกลับ

อินสแตนซ์ปัจจุบันของ [IMathBlock](../../imathblock/)
## หมายเหตุ



ตัวอย่าง: 
```cpp
auto element1 = System::MakeObject<MathematicalText>(u"x");
auto element2 = System::MakeObject<MathematicalText>(u"y");
auto block = element1->Join(element2);
```

## MathBlock::Join(System::String) เมธอด


ผสานข้อความคณิตศาสตร์เข้ากับบล็อกคณิตศาสตร์นี้

```cpp
System::SharedPtr<IMathBlock> Aspose::Slides::MathText::MathBlock::Join(System::String mathText) override
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| mathText | [System::String](../../../system/string/) | ข้อความคณิตศาสตร์ที่จะถูกผสาน |

### ค่าที่ส่งกลับ

[IMathBlock](../../imathblock/) ใหม่ที่มีอินสแตนซ์นี้และอาร์กิวเมนต์ที่ระบุ
## หมายเหตุ



ตัวอย่าง: 
```cpp
System::SharedPtr<IMathElement> element = System::MakeObject<MathematicalText>(u"x");
auto block = element->Join(u"+y");
```

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [IMathBlock](../../imathblock/)
* คลาส [IMathElement](../../imathelement/)
* คลาส [MathBlock](../)
* คลาส [String](../../../system/string/)
* เนมสเปซ [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)