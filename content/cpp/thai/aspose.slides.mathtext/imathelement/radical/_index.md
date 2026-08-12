---
title: Radical()
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: ระบุรากคณิตศาสตร์ของดีกรีที่กำหนดจากอาร์กิวเมนต์ที่ระบุ
type: docs
weight: 131
url: /th/aspose.slides.mathtext/imathelement/radical/
---
## IMathElement::Radical(System::SharedPtr\<IMathElement\>) เมธอด

ระบุรากคณิตศาสตร์ของดีกรีที่กำหนดจากอาร์กิวเมนต์ที่ระบุ

```cpp
virtual System::SharedPtr<IMathRadical> Aspose::Slides::MathText::IMathElement::Radical(System::SharedPtr<IMathElement> degree)=0
```

### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| degree | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../)\> | อาร์กิวเมนต์ของ Radical |

### ค่าที่ส่งคืน

อินสแตนซ์ใหม่ของประเภท [IMathRadical](../../imathradical/)

## หมายเหตุ



ตัวอย่าง: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"2px");
auto degree = System::MakeObject<MathematicalText>(u"y");
auto radical = baseElement->Radical(degree);
```

## IMathElement::Radical(System::String) เมธอด

ระบุรากคณิตศาสตร์ของดีกรีที่กำหนดจากอาร์กิวเมนต์ที่ระบุ

```cpp
virtual System::SharedPtr<IMathRadical> Aspose::Slides::MathText::IMathElement::Radical(System::String degree)=0
```

### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| degree | [System::String](../../../system/string/) | อาร์กิวเมนต์ของ Radical |

### ค่าที่ส่งคืน

อินสแตนซ์ใหม่ของประเภท [IMathRadical](../../imathradical/)

## หมายเหตุ



ตัวอย่าง: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"2px");
auto radical = baseElement->Radical(u"3");
```

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [IMathRadical](../../imathradical/)
* คลาส [IMathElement](../)
* คลาส [String](../../../system/string/)
* เนมสเปซ [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)