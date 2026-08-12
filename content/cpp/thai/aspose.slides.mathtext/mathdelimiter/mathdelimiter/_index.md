---
title: MathDelimiter()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: เริ่มต้น MathDelimiter ด้วยอิลิเมนต์ที่ระบุเป็นอาร์กิวเมนต์ฐานเดียว
type: docs
weight: 144
url: /th/aspose.slides.mathtext/mathdelimiter/mathdelimiter/
---
## MathDelimiter::MathDelimiter(System::SharedPtr\<IMathElement\>) ตัวสร้าง


เริ่มต้น [MathDelimiter](../) ด้วยอิลิเมนต์ที่ระบุเป็นอาร์กิวเมนต์ฐานเดียว

```cpp
Aspose::Slides::MathText::MathDelimiter::MathDelimiter(System::SharedPtr<IMathElement> element)
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | อิลิเมนต์ฐานที่ใช้กับดอลล่าร์นี้ สามารถเป็นค่า null ได้ |
## หมายเหตุ



ตัวอย่าง: 
```cpp
auto element = System::MakeObject<MathematicalText>(u"x");
auto delimiter = System::MakeObject<MathDelimiter>(element);
```

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [IMathElement](../../imathelement/)
* คลาส [MathDelimiter](../)
* เนมสเปซ [Aspose::Slides::MathText](../../)
* ไลบรารี [Aspose.Slides](../../../)