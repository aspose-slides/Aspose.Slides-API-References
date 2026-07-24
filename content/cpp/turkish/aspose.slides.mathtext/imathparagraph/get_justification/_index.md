---
title: get_Justification()
second_title: Aspose.Slides C++ için API Referansı
description: "Paragraph Justification Varsayılan değer: CenteredAsGroup"
type: docs
weight: 1
url: /tr/aspose.slides.mathtext/imathparagraph/get_justification/
---
## IMathParagraph::get_Justification() metodu


[Paragraph](../../../aspose.slides/paragraph/) Justification Varsayılan değer: CenteredAsGroup

```cpp
virtual MathJustification Aspose::Slides::MathText::IMathParagraph::get_Justification()=0
```

## Açıklamalar


Örnek: 
```cpp
auto shape = slide->get_Shapes()->AddMathShape(x, y, width, height);
auto mathParagraph = (System::AsCast<MathPortion>(shape->get_TextFrame()->get_Paragraphs()->idx_get(0)->get_Portions()->idx_get(0)))->get_MathParagraph();
mathParagraph->set_Justification(MathJustification::LeftJustified);
```

## Diğer Bağlantılar

* Enum [MathJustification](../../mathjustification/)
* Sınıf [IMathParagraph](../)
* Ad alanı [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)