---
title: get_Justification()
second_title: Aspose.Slides for C++ API Referansı
description: "Paragraph Justification Varsayılan değer: CenteredAsGroup"
type: docs
weight: 1
url: /tr/aspose.slides.mathtext/mathparagraph/get_justification/
---
## MathParagraph::get_Justification() yöntemi


[Paragraph](../../../aspose.slides/paragraph/) Justification Varsayılan değer: CenteredAsGroup

```cpp
MathJustification Aspose::Slides::MathText::MathParagraph::get_Justification() override
```

## Açıklamalar


Örnek: 
```cpp
auto shape = slide->get_Shapes()->AddMathShape(x, y, width, height);
auto mathParagraph = (System::AsCast<MathPortion>(shape->get_TextFrame()->get_Paragraphs()->idx_get(0)->get_Portions()->idx_get(0)))->get_MathParagraph();
mathParagraph->set_Justification(MathJustification::LeftJustified);
```

## Bakınız

* Enum [MathJustification](../../mathjustification/)
* Sınıf [MathParagraph](../)
* Ad alanı [Aspose::Slides::MathText](../../)
* Kütüphane [Aspose.Slides](../../../)