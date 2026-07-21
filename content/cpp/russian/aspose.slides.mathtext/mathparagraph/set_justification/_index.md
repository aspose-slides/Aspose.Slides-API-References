---
title: set_Justification()
second_title: Справка API Aspose.Slides для C++
description: "Выравнивание абзаца Значение по умолчанию: CenteredAsGroup"
type: docs
weight: 14
url: /ru/aspose.slides.mathtext/mathparagraph/set_justification/
---
## MathParagraph::set_Justification(MathJustification) метод


[Paragraph](../../../aspose.slides/paragraph/) Выравнивание Значение по умолчанию: CenteredAsGroup

```cpp
void Aspose::Slides::MathText::MathParagraph::set_Justification(MathJustification value) override
```

## Примечания


Пример:
```cpp
auto shape = slide->get_Shapes()->AddMathShape(x, y, width, height);
auto mathParagraph = (System::AsCast<MathPortion>(shape->get_TextFrame()->get_Paragraphs()->idx_get(0)->get_Portions()->idx_get(0)))->get_MathParagraph();
mathParagraph->set_Justification(MathJustification::LeftJustified);
```

## См. также

* Перечисление [MathJustification](../../mathjustification/)
* Класс [MathParagraph](../)
* Пространство имён [Aspose::Slides::MathText](../../)
* Библиотека [Aspose.Slides](../../../)