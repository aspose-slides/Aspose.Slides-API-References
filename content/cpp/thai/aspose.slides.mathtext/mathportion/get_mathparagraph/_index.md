---
title: get_MathParagraph()
second_title: Aspose.Slides สำหรับการอ้างอิง API ของ C++
description: ย่อหน้าคณิตศาสตร์
type: docs
weight: 1
url: /th/aspose.slides.mathtext/mathportion/get_mathparagraph/
---
## MathPortion::get_MathParagraph() เมธอด

ย่อหน้าคณิตศาสตร์

```cpp
System::SharedPtr<IMathParagraph> Aspose::Slides::MathText::MathPortion::get_MathParagraph() override
```

## หมายเหตุ

ตัวอย่าง:
```cpp
auto pres = System::MakeObject<Presentation>();
auto shape = pres->get_Slides()->idx_get(0)->get_Shapes()->AddMathShape(0.0f, 0.0f, 300.0f, 50.0f);
auto mathParagraph = (System::AsCast<MathPortion>(shape->get_TextFrame()->get_Paragraphs()->idx_get(0)->get_Portions()->idx_get(0)))->get_MathParagraph();
mathParagraph->Add(System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"x+y")));
```

## ดูเพิ่มเติม

* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [IMathParagraph](../../imathparagraph/)
* คลาส [MathPortion](../)
* เนมสเปซ [Aspose::Slides::MathText](../../)
* ไลบรารี [Aspose.Slides](../../../)