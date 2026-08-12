---
title: set_Differential()
second_title: Aspose.Slides สำหรับอ้างอิง API ของ C++
description: "Differential เมื่อเป็น true, กล่องทำหน้าที่เป็น differential (เช่น \\uD835\\uDC51\\uD835\\uDC65 ใน integrand) และรับการเว้นระยะแนวนอนที่เหมาะสมสำหรับ differential ทางคณิตศาสตร์. Default: false"
type: docs
weight: 79
url: /th/aspose.slides.mathtext/mathbox/set_differential/
---
## MathBox::set_Differential(bool) เมธอด

Differential เมื่อเป็น true, กล่องทำหน้าที่เป็น differential (เช่น \\uD835\\uDC51\\uDC65 ใน integrand) และได้รับการเว้นระยะแนวนอนที่เหมาะสมสำหรับ differential ทางคณิตศาสตร์. Default: false

```cpp
void Aspose::Slides::MathText::MathBox::set_Differential(bool value) override
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