---
title: MathBox()
second_title: Aspose.Slides สำหรับ C++ การอ้างอิง API
description: เริ่มต้น MathBox กับอิลิเมนต์ที่ระบุเป็นอาร์กิวเมนต์
type: docs
weight: 144
url: /th/aspose.slides.mathtext/mathbox/mathbox/
---
## MathBox::MathBox(System::SharedPtr\<IMathElement\>) คอนสตรัคเตอร์


เริ่มต้นค่า [MathBox](../) ด้วยอิลิเมนต์ที่ระบุเป็นอาร์กิวเมนต์

```cpp
Aspose::Slides::MathText::MathBox::MathBox(System::SharedPtr<IMathElement> element)
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | อิลิเมนต์ฐานที่กล่องถูกนำไปใช้. สามารถเป็นค่า null ได้ |
## หมายเหตุ



ตัวอย่าง: 
```cpp
auto box = System::MakeObject<MathBox>(System::MakeObject<MathematicalText>(u"=="));
```

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [IMathElement](../../imathelement/)
* คลาส [MathBox](../)
* เนมสเปซ [Aspose::Slides::MathText](../../)
* ไลบรารี [Aspose.Slides](../../../)