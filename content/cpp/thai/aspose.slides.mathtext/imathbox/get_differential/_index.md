---
title: get_Differential()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: "อนุพันธ์. เมื่อเป็น true, กล่องทำหน้าที่เป็นอนุพันธ์ (เช่น \\uD835\\uDC51\\uD835\\uDC65 ในอินทิกรัล), และได้รับการจัดระยะห่างตามแนวนอนที่เหมาะสมสำหรับอนุพันธ์ทางคณิตศาสตร์. ค่าเริ่มต้น: false"
type: docs
weight: 66
url: /th/aspose.slides.mathtext/imathbox/get_differential/
---
## IMathBox::get_Differential() เมธอด


อนุพันธ์. เมื่อเป็น true, กล่องทำหน้าที่เป็นอนุพันธ์ (เช่น \\uD835\\uDC51\\uDC65 ในตัวอินเทกรัล), และรับการจัดระยะห่างในแนวนอนที่เหมาะสมสำหรับอนุพันธ์ทางคณิตศาสตร์. ค่าเริ่มต้น: false

```cpp
virtual bool Aspose::Slides::MathText::IMathBox::get_Differential()=0
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
* ไลบรารี [Aspose.Slides](../../../)