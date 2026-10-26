---
title: ToLatex()
second_title: Referensi API Aspose.Slides untuk C++
description: Mendapatkan persamaan matematis dalam format LaTeX
type: docs
weight: 40
url: /id/aspose.slides.mathtext/imathparagraph/tolatex/
---
## IMathParagraph::ToLatex() metode

Mendapatkan persamaan matematis dalam format LaTeX

```cpp
virtual System::String Aspose::Slides::MathText::IMathParagraph::ToLatex()=0
```

## Catatan


Contoh: 
```cpp
System::SharedPtr<IAutoShape> shape = slide->get_Shapes()->AddMathShape(x, y, width, height);
System::SharedPtr<IMathParagraph> mathParagraph = (System::AsCast<MathPortion>(shape->get_TextFrame()->get_Paragraph(0)->get_Portion(0)))->get_MathParagraph();
mathParagraph->Add(System::MakeObject<MathematicalText>(u"a")->Join(u"+")->Join(System::MakeObject<MathematicalText>(u"b")->Join(u"=")->Join(System::MakeObject<MathematicalText>(u"c"))));
System::String mathLatex = mathParagraph->ToLatex();
```

## Lihat Juga

* Kelas [String](../../../system/string/)
* Kelas [IMathParagraph](../)
* Ruang nama [Aspose::Slides::MathText](../../)
* Perpustakaan [Aspose.Slides](../../../)