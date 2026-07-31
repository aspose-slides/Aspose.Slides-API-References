---
title: get_Justification()
second_title: Referensi API Aspose.Slides untuk C++
description: "Justifikasi Paragraf Nilai default: CenteredAsGroup"
type: docs
weight: 1
url: /id/aspose.slides.mathtext/mathparagraph/get_justification/
---
## MathParagraph::get_Justification() metode

[Paragraph](../../../aspose.slides/paragraph/) Justification Nilai default: CenteredAsGroup

```cpp
MathJustification Aspose::Slides::MathText::MathParagraph::get_Justification() override
```

## Catatan

Contoh: 
```cpp
auto shape = slide->get_Shapes()->AddMathShape(x, y, width, height);
auto mathParagraph = (System::AsCast<MathPortion>(shape->get_TextFrame()->get_Paragraphs()->idx_get(0)->get_Portions()->idx_get(0)))->get_MathParagraph();
mathParagraph->set_Justification(MathJustification::LeftJustified);
```

## Lihat Juga

* Enum [MathJustification](../../mathjustification/)
* Kelas [MathParagraph](../)
* Ruang nama [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)