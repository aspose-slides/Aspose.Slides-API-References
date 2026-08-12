---
title: MathPhantom()
second_title: Aspose.Slides สำหรับอ้างอิง API ของ C++
description: เริ่มต้นอินสแตนซ์ใหม่ของคลาส MathPhantom โดยใช้ base math element ที่ระบุ
type: docs
weight: 144
url: /th/aspose.slides.mathtext/mathphantom/mathphantom/
---
## MathPhantom::MathPhantom(System::SharedPtr\<IMathElement\>) คอนสตรัคเตอร์

เริ่มต้นอินสแตนซ์ใหม่ของคลาส [MathPhantom](../) โดยใช้ base math element ที่ระบุ

```cpp
Aspose::Slides::MathText::MathPhantom::MathPhantom(System::SharedPtr<IMathElement> element)
```


### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | ฐาน [IMathElement](../../imathelement/) ที่การมองเห็นและการจัดวางจะถูกควบคุมโดย phantom. องค์ประกอบนี้กำหนดเนื้อหาที่อาจซ่อนหรือแสดง, ในขณะที่ยังส่งผลต่อการจัดแนวเรขาคณิตของคณิตศาสตร์ที่ล้อมรอบ |

## หมายเหตุ

phantom element ถูกใช้เพื่อสงวนหรือกดดันพื้นที่ภาพของนิพจน์ฐานโดยไม่จำเป็นต้องแสดงผล. มันสอดคล้องกับองค์ประกอบ OMML **<m:phant>**.

ตัวอย่าง:
```cpp
System::SharedPtr<IMathElement> fraction = System::MakeObject<MathFraction>(
    System::MakeObject<MathematicalText>(u"1"),
    System::MakeObject<MathematicalText>(u"2"));
```

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [IMathElement](../../imathelement/)
* คลาส [MathPhantom](../)
* เนมสเปซ [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)