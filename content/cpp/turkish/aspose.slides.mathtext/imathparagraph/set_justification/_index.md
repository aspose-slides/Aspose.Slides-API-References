---
title: set_Justification()
second_title: Aspose.Slides for C++ API Referansı
description: "Paragraf Hizalama Varsayılan değer: CenteredAsGroup"
type: docs
weight: 14
url: /tr/aspose.slides.mathtext/imathparagraph/set_justification/
---
## IMathParagraph::set_Justification(MathJustification) metot


[Paragraph](../../../aspose.slides/paragraph/) Justification Varsayılan değer: CenteredAsGroup

```cpp
virtual void Aspose::Slides::MathText::IMathParagraph::set_Justification(MathJustification value)=0
```

## Açıklamalar


Örnek: 
```cpp
auto shape = slide->get_Shapes()->AddMathShape(x, y, width, height);
auto mathParagraph = (System::AsCast<MathPortion>(shape->get_TextFrame()->get_Paragraphs()->idx_get(0)->get_Portions()->idx_get(0)))->get_MathParagraph();
mathParagraph->set_Justification(MathJustification::LeftJustified);
```

## İlgili

* Enum [MathJustification](../../mathjustification/)
* Sınıf [IMathParagraph](../)
* Ad alanı [Aspose::Slides::MathText](../../)
* Kütüphane [Aspose.Slides](../../../)