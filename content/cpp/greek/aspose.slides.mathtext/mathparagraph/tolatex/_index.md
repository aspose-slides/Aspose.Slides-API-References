---
title: ToLatex()
second_title: Aspose.Slides για C++ Αναφορά API
description: Λαμβάνει μαθηματική εξίσωση σε μορφή LaTeX
type: docs
weight: 183
url: /el/aspose.slides.mathtext/mathparagraph/tolatex/
---
## MathParagraph::ToLatex() μέθοδος

Λαμβάνει μαθηματική εξίσωση σε μορφή LaTeX

```cpp
System::String Aspose::Slides::MathText::MathParagraph::ToLatex() override
```

## Σχόλια

Παράδειγμα:
```cpp
System::SharedPtr<IAutoShape> shape = slide->get_Shapes()->AddMathShape(x, y, width, height);
System::SharedPtr<IMathParagraph> mathParagraph = (System::AsCast<MathPortion>(shape->get_TextFrame()->get_Paragraph(0)->get_Portion(0)))->get_MathParagraph();
mathParagraph->Add(System::MakeObject<MathematicalText>(u"a")->Join(u"+")->Join(System::MakeObject<MathematicalText>(u"b")->Join(u"=")->Join(System::MakeObject<MathematicalText>(u"c"))));
System::String mathLatex = mathParagraph->ToLatex();
```

## Δείτε επίσης

* Κλάση [String](../../../system/string/)
* Κλάση [MathParagraph](../)
* Χώρος ονομάτων [Aspose::Slides::MathText](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)