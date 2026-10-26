---
title: ToLatex()
second_title: Aspose.Slides C++ API referenciája
description: Megkapja a matematikai egyenletet LaTeX formátumban
type: docs
weight: 40
url: /hu/aspose.slides.mathtext/imathparagraph/tolatex/
---
## IMathParagraph::ToLatex() metódus

Megkapja a matematikai egyenletet LaTeX formátumban

```cpp
virtual System::String Aspose::Slides::MathText::IMathParagraph::ToLatex()=0
```

## Megjegyzések

Példa: 
```cpp
System::SharedPtr<IAutoShape> shape = slide->get_Shapes()->AddMathShape(x, y, width, height);
System::SharedPtr<IMathParagraph> mathParagraph = (System::AsCast<MathPortion>(shape->get_TextFrame()->get_Paragraph(0)->get_Portion(0)))->get_MathParagraph();
mathParagraph->Add(System::MakeObject<MathematicalText>(u"a")->Join(u"+")->Join(System::MakeObject<MathematicalText>(u"b")->Join(u"=")->Join(System::MakeObject<MathematicalText>(u"c"))));
System::String mathLatex = mathParagraph->ToLatex();
```

## Lásd még

* Osztály [String](../../../system/string/)
* Osztály [IMathParagraph](../)
* Névtér [Aspose::Slides::MathText](../../)
* Könyvtár [Aspose.Slides](../../../)