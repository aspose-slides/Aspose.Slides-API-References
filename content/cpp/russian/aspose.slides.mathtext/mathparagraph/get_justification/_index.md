---
title: get_Justification()
second_title: Aspose.Slides для C++ справочник API
description: "Выравнивание абзаца Значение по умолчанию: CenteredAsGroup"
type: docs
weight: 1
url: /ru/aspose.slides.mathtext/mathparagraph/get_justification/
---
## MathParagraph::get_Justification() метод

[Paragraph](../../../aspose.slides/paragraph/) Justification Значение по умолчанию: CenteredAsGroup

```cpp
MathJustification Aspose::Slides::MathText::MathParagraph::get_Justification() override
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