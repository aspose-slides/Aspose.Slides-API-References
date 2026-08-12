---
title: ToLatex()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: LaTeX फ़ॉर्मेट में गणितीय समीकरण प्राप्त करता है
type: docs
weight: 183
url: /hi/aspose.slides.mathtext/mathparagraph/tolatex/
---
## MathParagraph::ToLatex() विधि


LaTeX फ़ॉर्मेट में गणितीय समीकरण प्राप्त करता है

```cpp
System::String Aspose::Slides::MathText::MathParagraph::ToLatex() override
```

## टिप्पणियाँ


उदाहरण: 
```cpp
System::SharedPtr<IAutoShape> shape = slide->get_Shapes()->AddMathShape(x, y, width, height);
System::SharedPtr<IMathParagraph> mathParagraph = (System::AsCast<MathPortion>(shape->get_TextFrame()->get_Paragraph(0)->get_Portion(0)))->get_MathParagraph();
mathParagraph->Add(System::MakeObject<MathematicalText>(u"a")->Join(u"+")->Join(System::MakeObject<MathematicalText>(u"b")->Join(u"=")->Join(System::MakeObject<MathematicalText>(u"c"))));
System::String mathLatex = mathParagraph->ToLatex();
```

## संबंधित देखें

* क्लास [String](../../../system/string/)
* क्लास [MathParagraph](../)
* नामस्थान [Aspose::Slides::MathText](../../)
* लाइब्रेरी [Aspose.Slides](../../../)