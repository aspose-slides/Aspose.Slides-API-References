---
title: set_Justification()
second_title: Aspose.Slides สำหรับ C++ เอกสารอ้างอิง API
description: "การจัดแนวย่อหน้า ค่าเริ่มต้น: CenteredAsGroup"
type: docs
weight: 14
url: /th/aspose.slides.mathtext/imathparagraph/set_justification/
---
## IMathParagraph::set_Justification(MathJustification) เมธอด


[Paragraph](../../../aspose.slides/paragraph/) Justification ค่าเริ่มต้น: CenteredAsGroup

```cpp
virtual void Aspose::Slides::MathText::IMathParagraph::set_Justification(MathJustification value)=0
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
* คลาส [IMathParagraph](../)
* เนมสเปซ [Aspose::Slides::MathText](../../)
* ไลบรารี [Aspose.Slides](../../../)