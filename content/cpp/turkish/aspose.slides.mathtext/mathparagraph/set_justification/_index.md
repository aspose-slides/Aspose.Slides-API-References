---
title: set_Justification()
second_title: Aspose.Slides for C++ API Referansı
description: "Paragraf Hizalama Varsayılan değer: CenteredAsGroup"
type: docs
weight: 14
url: /tr/aspose.slides.mathtext/mathparagraph/set_justification/
---
## MathParagraph::set_Justification(MathJustification) metodu


[Paragraph](../../../aspose.slides/paragraph/) Justification Varsayılan değer: CenteredAsGroup

```cpp
void Aspose::Slides::MathText::MathParagraph::set_Justification(MathJustification value) override
```

## Açıklamalar


Örnek: 
```cpp
auto shape = slide->get_Shapes()->AddMathShape(x, y, width, height);
auto mathParagraph = (System::AsCast<MathPortion>(shape->get_TextFrame()->get_Paragraphs()->idx_get(0)->get_Portions()->idx_get(0)))->get_MathParagraph();
mathParagraph->set_Justification(MathJustification::LeftJustified);
```

## Ayrıca Bakınız

* Enum [MathJustification](../../mathjustification/)
* Sınıf [MathParagraph](../)
* Ad Alanı [Aspose::Slides::MathText](../../)
* Kütüphane [Aspose.Slides](../../../)