---
title: ToLatex()
second_title: Aspose.Slides για C++ Αναφορά API
description: Λαμβάνει μαθηματική εξίσωση σε μορφή LaTeX
type: docs
weight: 40
url: /el/aspose.slides.mathtext/imathparagraph/tolatex/
---
## IMathParagraph::ToLatex() μέθοδος


Λαμβάνει μαθηματική εξίσωση σε μορφή LaTeX

```cpp
virtual System::String Aspose::Slides::MathText::IMathParagraph::ToLatex()=0
```

## Παρατηρήσεις


Παράδειγμα: 
```cpp
System::SharedPtr<IAutoShape> shape = slide->get_Shapes()->AddMathShape(x, y, width, height);
System::SharedPtr<IMathParagraph> mathParagraph = (System::AsCast<MathPortion>(shape->get_TextFrame()->get_Paragraph(0)->get_Portion(0)))->get_MathParagraph();
mathParagraph->Add(System::MakeObject<MathematicalText>(u"a")->Join(u"+")->Join(System::MakeObject<MathematicalText>(u"b")->Join(u"=")->Join(System::MakeObject<MathematicalText>(u"c"))));
System::String mathLatex = mathParagraph->ToLatex();
```

## Δείτε επίσης

* Κλάση [String](../../../system/string/)
* Κλάση [IMathParagraph](../)
* Χώρος ονομάτων [Aspose::Slides::MathText](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)