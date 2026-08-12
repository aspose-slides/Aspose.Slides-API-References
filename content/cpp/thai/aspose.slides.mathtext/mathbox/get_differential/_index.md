---
title: get_Differential()
second_title: Aspose.Slides สำหรับ C++ เอกสารอ้างอิง API
description: "Differential เมื่อ true, กล่องทำหน้าที่เป็น differential (e.g., \\uD835\\uDC51\\uD835\\uDC65 ใน integrand), และรับระยะห่างแนวนอนที่เหมาะสมสำหรับ differential ทางคณิตศาสตร์. ค่าเริ่มต้น: false"
type: docs
weight: 66
url: /th/aspose.slides.mathtext/mathbox/get_differential/
---
## MathBox::get_Differential() method

Differential เมื่อ true, กล่องทำหน้าที่เป็น Differential (e.g., \\uD835\\uDC51\\uDC65 in an integrand), และได้รับระยะห่างแนวนอนที่เหมาะสมสำหรับอนุพันธ์ทางคณิตศาสตร์. ค่าเริ่มต้น: false

```cpp
bool Aspose::Slides::MathText::MathBox::get_Differential() override
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

* คลาส [MathBox](../)
* เนมสเปซ [Aspose::Slides::MathText](../../)
* ไลบรารี [Aspose.Slides](../../../)