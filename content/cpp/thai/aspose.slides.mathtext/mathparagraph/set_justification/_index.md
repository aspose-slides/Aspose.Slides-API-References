---
title: set_Justification()
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: "Paragraph Justification ค่าเริ่มต้น: CenteredAsGroup"
type: docs
weight: 14
url: /th/aspose.slides.mathtext/mathparagraph/set_justification/
---
## MathParagraph::set_Justification(MathJustification) เมธอด

[Paragraph](../../../aspose.slides/paragraph/) Justification ค่าเริ่มต้น: CenteredAsGroup

```cpp
void Aspose::Slides::MathText::MathParagraph::set_Justification(MathJustification value) override
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
* Library [Aspose.Slides](../../../)