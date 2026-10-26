---
title: ToLatex()
second_title: Aspose.Slides C++ के लिए API संदर्भ
description: LaTeX प्रारूप में गणितीय समीकरण प्राप्त करता है
type: docs
weight: 40
url: /hi/aspose.slides.mathtext/imathparagraph/tolatex/
---
## IMathParagraph::ToLatex() विधि

LaTeX प्रारूप में गणितीय समीकरण प्राप्त करता है

```cpp
virtual System::String Aspose::Slides::MathText::IMathParagraph::ToLatex()=0
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
* क्लास [IMathParagraph](../)
* नेमस्पेस [Aspose::Slides::MathText](../../)
* लाइब्रेरी [Aspose.Slides](../../../)