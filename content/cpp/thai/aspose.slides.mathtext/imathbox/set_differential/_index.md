---
title: set_Differential()
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: "อนุพันธ์. เมื่อค่าเป็น true, กล่องทำหน้าที่เป็นอนุพันธ์ (เช่น \\uD835\\uDC51\\uD835\\uDC65 ในตัวอินทิกรัล), และได้รับการเว้นระยะแนวนอนที่เหมาะสมสำหรับอนุพันธ์ทางคณิตศาสตร์. ค่าเริ่มต้น: false"
type: docs
weight: 79
url: /th/aspose.slides.mathtext/imathbox/set_differential/
---
## IMathBox::set_Differential(bool) method


อนุพันธ์. เมื่อค่าเป็น true, กล่องทำหน้าที่เป็นอนุพันธ์ (เช่น \\uD835\\uDC51\\uDC65 ในตัวอินทิกรัล), และได้รับการเว้นระยะแนวนอนที่เหมาะสมสำหรับอนุพันธ์ทางคณิตศาสตร์. ค่าเริ่มต้น: false

```cpp
virtual void Aspose::Slides::MathText::IMathBox::set_Differential(bool value)=0
```

## หมายเหตุ


ตัวอย่าง: 
```cpp
auto differential = System::MakeObject<MathematicalText>(u"dx")->ToBox();
differential->set_Differential(true);
auto baseArg = System::MakeObject<MathematicalText>(u"x")->Join(differential);
auto integral = baseArg->Integral(MathIntegralTypes::Simple, u"0", u"1");
```

## ดูเพิ่มเติม

* คลาส [IMathBox](../)
* เนมสเปซ [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)