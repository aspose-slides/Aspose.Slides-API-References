---
title: Join()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: เชื่อมต่อส่วนประกอบคณิตศาสตร์และสร้างบล็อกคณิตศาสตร์
type: docs
weight: 1
url: /th/aspose.slides.mathtext/mathelementbase/join/
---
## MathElementBase::Join(System::SharedPtr\<IMathElement\>) เมธอด

เชื่อมต่อส่วนประกอบคณิตศาสตร์และสร้างบล็อกคณิตศาสตร์

```cpp
System::SharedPtr<IMathBlock> Aspose::Slides::MathText::MathElementBase::Join(System::SharedPtr<IMathElement> mathElement) override
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| mathElement | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | ส่วนประกอบที่ต้องการเชื่อมต่อ |

### ค่าที่คืนกลับ

อ็อบเจกต์ใหม่ [IMathBlock](../../imathblock/) ที่มีอินสแตนซ์นี้และอาร์กิวเมนต์ที่ระบุ
## หมายเหตุ



ตัวอย่าง: 
```cpp
auto element1 = System::MakeObject<MathematicalText>(u"x");
auto element2 = System::MakeObject<MathematicalText>(u"y");
auto block = element1->Join(element2);
```

## MathElementBase::Join(System::String) เมธอด


เชื่อมต่อข้อความคณิตศาสตร์และสร้างบล็อกคณิตศาสตร์

```cpp
System::SharedPtr<IMathBlock> Aspose::Slides::MathText::MathElementBase::Join(System::String mathText) override
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| mathText | [System::String](../../../system/string/) | ข้อความคณิตศาสตร์ที่ต้องการเชื่อมต่อ |

### ค่าที่คืนกลับ

อ็อบเจกต์ใหม่ [IMathBlock](../../imathblock/) ที่มีอินสแตนซ์นี้และอาร์กิวเมนต์ที่ระบุ
## หมายเหตุ



ตัวอย่าง: 
```cpp
auto element = System::MakeObject<MathematicalText>(u"x");
auto block = element->Join(u"+y");
```

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [IMathBlock](../../imathblock/)
* คลาส [IMathElement](../../imathelement/)
* คลาส [MathElementBase](../)
* คลาส [String](../../../system/string/)
* เนมสเปซ [Aspose::Slides::MathText](../../)
* ไลบรารี [Aspose.Slides](../../../)