---
title: ToLatex()
second_title: Справочник API Aspose.Slides для C++
description: Получает математическое уравнение в формате LaTeX
type: docs
weight: 40
url: /ru/aspose.slides.mathtext/imathparagraph/tolatex/
---
## IMathParagraph::ToLatex() метод


Получает математическое уравнение в формате LaTeX

```cpp
virtual System::String Aspose::Slides::MathText::IMathParagraph::ToLatex()=0
```

## Примечания


Пример:
```cpp
System::SharedPtr<IAutoShape> shape = slide->get_Shapes()->AddMathShape(x, y, width, height);
System::SharedPtr<IMathParagraph> mathParagraph = (System::AsCast<MathPortion>(shape->get_TextFrame()->get_Paragraph(0)->get_Portion(0)))->get_MathParagraph();
mathParagraph->Add(System::MakeObject<MathematicalText>(u"a")->Join(u"+")->Join(System::MakeObject<MathematicalText>(u"b")->Join(u"=")->Join(System::MakeObject<MathematicalText>(u"c"))));
System::String mathLatex = mathParagraph->ToLatex();
```

## См. также

* Класс [String](../../../system/string/)
* Класс [IMathParagraph](../)
* Пространство имён [Aspose::Slides::MathText](../../)
* Библиотека [Aspose.Slides](../../../)