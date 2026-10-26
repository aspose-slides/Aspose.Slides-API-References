---
title: get_Justification()
second_title: อ้างอิง API ของ Aspose.Slides for C++
description: "Paragraph Justification ค่าเริ่มต้น: CenteredAsGroup"
type: docs
weight: 1
url: /th/aspose.slides.mathtext/mathparagraph/get_justification/
---
## MathParagraph::get_Justification() เมธอด


[Paragraph](../../../aspose.slides/paragraph/) การจัดตำแหน่ง ค่าเริ่มต้น: CenteredAsGroup

```cpp
MathJustification Aspose::Slides::MathText::MathParagraph::get_Justification() override
```

## หมายเหตุ

ตัวอย่าง:
```cpp
auto shape = slide->get_Shapes()->AddMathShape(x, y, width, height);
auto mathParagraph = (System::AsCast<MathPortion>(shape->get_TextFrame()->get_Paragraphs()->idx_get(0)->get_Portions()->idx_get(0)))->get_MathParagraph();
mathParagraph->set_Justification(MathJustification::LeftJustified);
```

## ดูเพิ่มเติม

* Enum [MathJustification](../../mathjustification/)
* คลาส [MathParagraph](../)
* เนมสเปซ [Aspose::Slides::MathText](../../)
* ไลบรารี [Aspose.Slides](../../../)