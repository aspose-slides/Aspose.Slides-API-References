---
title: Join()
second_title: Aspose.Slides สำหรับ C++ เอกสารอ้างอิง API
description: รวมองค์ประกอบคณิตศาสตร์และสร้างบล็อกคณิตศาสตร์
type: docs
weight: 14
url: /th/aspose.slides.mathtext/imathelement/join/
---
## IMathElement::Join(System::SharedPtr\<IMathElement\>) เมธอด


รวมองค์ประกอบคณิตศาสตร์และสร้างบล็อกคณิตศาสตร์

```cpp
virtual System::SharedPtr<IMathBlock> Aspose::Slides::MathText::IMathElement::Join(System::SharedPtr<IMathElement> mathElement)=0
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| mathElement | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../)\> | องค์ประกอบที่ต้องรวม |

### Return Value

อ็อบเจ็กต์ [IMathBlock](../../imathblock/) ใหม่ที่ประกอบด้วยอินสแตนซ์นี้และอาร์กิวเมนต์ที่ระบุ
## Remarks



ตัวอย่าง: 
```cpp
auto element1 = System::MakeObject<MathematicalText>(u"x");
auto element2 = System::MakeObject<MathematicalText>(u"y");
auto block = element1->Join(element2);
```

## IMathElement::Join(System::String) เมธอด


รวมข้อความคณิตศาสตร์และสร้างบล็อกคณิตศาสตร์

```cpp
virtual System::SharedPtr<IMathBlock> Aspose::Slides::MathText::IMathElement::Join(System::String mathText)=0
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| mathText | [System::String](../../../system/string/) | ข้อความคณิตศาสตร์ที่ต้องรวม |

### Return Value

อ็อบเจ็กต์ [IMathBlock](../../imathblock/) ใหม่ที่ประกอบด้วยอินสแตนซ์นี้และอาร์กิวเมนต์ที่ระบุ
## Remarks



ตัวอย่าง: 
```cpp
System::SharedPtr<IMathElement> element = System::MakeObject<MathematicalText>(u"x");
auto block = element->Join(u"+y");
```

## ดูเพิ่มเติม

* ชนิดนิยาม [SharedPtr](../../../system/sharedptr/)
* คลาส [IMathBlock](../../imathblock/)
* คลาส [IMathElement](../)
* คลาส [String](../../../system/string/)
* เนมสเปซ [Aspose::Slides::MathText](../../)
* ไลบรารี [Aspose.Slides](../../../)