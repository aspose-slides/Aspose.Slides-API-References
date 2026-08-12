---
title: MathPortion()
second_title: Aspose.Slides สำหรับ C++ เอกสารอ้างอิง API
description: สร้างอินสแตนซ์ใหม่ของคลาส MathPortion.
type: docs
weight: 14
url: /th/aspose.slides.mathtext/mathportion/mathportion/
---
## MathPortion::MathPortion() คอนสตรัคเตอร์


สร้างอินสแตนซ์ใหม่ของคลาส [MathPortion](../).

```cpp
Aspose::Slides::MathText::MathPortion::MathPortion()
```

## หมายเหตุ


ตัวอย่าง:
```cpp
auto pres = System::MakeObject<Presentation>();
auto shape = pres->get_Slides()->idx_get(0)->get_Shapes()->AddMathShape(0.0f, 0.0f, 300.0f, 50.0f);
auto paragraph = shape->get_TextFrame()->get_Paragraphs()->idx_get(0);
auto mathPortion = System::MakeObject<MathPortion>();
paragraph->get_Portions()->Add(mathPortion);
```

## ดูเพิ่มเติม

* คลาส [MathPortion](../)
* เนมสเปซ [Aspose::Slides::MathText](../../)
* ไลบรารี [Aspose.Slides](../../../)