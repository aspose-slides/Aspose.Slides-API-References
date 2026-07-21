---
title: get_Justification()
second_title: Справочник API Aspose.Slides для C++
description: "Выравнивание абзаца Значение по умолчанию: CenteredAsGroup"
type: docs
weight: 1
url: /ru/aspose.slides.mathtext/imathparagraph/get_justification/
---
## IMathParagraph::get_Justification() метод


[Paragraph](../../../aspose.slides/paragraph/) Justification Значение по умолчанию: CenteredAsGroup

```cpp
virtual MathJustification Aspose::Slides::MathText::IMathParagraph::get_Justification()=0
```

## Примечание


Пример:
```cpp
auto shape = slide->get_Shapes()->AddMathShape(x, y, width, height);
auto mathParagraph = (System::AsCast<MathPortion>(shape->get_TextFrame()->get_Paragraphs()->idx_get(0)->get_Portions()->idx_get(0)))->get_MathParagraph();
mathParagraph->set_Justification(MathJustification::LeftJustified);
```

## См. также

* Перечисление [MathJustification](../../mathjustification/)
* Класс [IMathParagraph](../)
* Пространство имён [Aspose::Slides::MathText](../../)
* Библиотека [Aspose.Slides](../../../)