---
title: ToBox()
second_title: Aspose.Slides สำหรับ C++ เอกสารอ้างอิง API
description: วางองค์ประกอบนี้ในกล่องที่ไม่แสดงผล (การจัดกลุ่มเชิงตรรกะ) ซึ่งใช้เพื่อจัดกลุ่มส่วนประกอบของสมการหรือข้อความคณิตศาสตร์อื่น ๆ วัตถุที่อยู่ในกล่องสามารถ (เช่น) ทำหน้าที่เป็นออเปอเรเตอร์จำลองพร้อมหรือไม่มีจุดจัดตำแหน่ง ทำหน้าที่เป็นจุดตัดบรรทัด หรือถูกจัดกลุ่มเพื่อไม่ให้เกิดการตัดบรรทัดภายใน
type: docs
weight: 274
url: /th/aspose.slides.mathtext/imathelement/tobox/
---
## IMathElement::ToBox() method


วางองค์ประกอบนี้ในกล่องที่ไม่แสดงผล (การจัดกลุ่มเชิงตรรกะ) ซึ่งใช้สำหรับจัดกลุ่มส่วนประกอบของสมการหรือข้อความคณิตศาสตร์อื่น ๆ วัตถุที่อยู่ในกล่องสามารถ (เช่น) ทำหน้าที่เป็นออเปอเรเตอร์จำลองพร้อมหรือไม่มีจุดจัดตำแหน่ง ทำหน้าที่เป็นจุดตัดบรรทัด หรือถูกจัดกลุ่มเพื่อไม่ให้เกิดการตัดบรรทัดภายใน

```cpp
virtual System::SharedPtr<IMathBox> Aspose::Slides::MathText::IMathElement::ToBox()=0
```


### ค่าที่ส่งคืน

Logical box with this element placed inside
## หมายเหตุ



ตัวอย่าง: 
```cpp
auto box = System::MakeObject<MathematicalText>(u"x:=y")->ToBox();
```

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [IMathBox](../../imathbox/)
* คลาส [IMathElement](../)
* เนมสเปซ [Aspose::Slides::MathText](../../)
* ไลบรารี [Aspose.Slides](../../../)