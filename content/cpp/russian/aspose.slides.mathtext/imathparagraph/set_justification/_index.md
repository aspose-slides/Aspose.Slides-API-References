---
title: set_Justification()
second_title: Справочник API Aspose.Slides для C++
description: "Выравнивание абзаца Значение по умолчанию: CenteredAsGroup"
type: docs
weight: 14
url: /ru/aspose.slides.mathtext/imathparagraph/set_justification/
---
## IMathParagraph::set_Justification(MathJustification) метод


[Paragraph](../../../aspose.slides/paragraph/) Justification Значение по умолчанию: CenteredAsGroup

```cpp
virtual void Aspose::Slides::MathText::IMathParagraph::set_Justification(MathJustification value)=0
```

## Примечания


Пример: 
```cpp
auto shape = slide->get_Shapes()->AddMathShape(x, y, width, height);
auto mathParagraph = (System::AsCast<MathPortion>(shape->get_TextFrame()->get_Paragraphs()->idx_get(0)->get_Portions()->idx_get(0)))->get_MathParagraph();
mathParagraph->set_Justification(MathJustification::LeftJustified);
```

## Смотрите также

* Перечисление [MathJustification](../../mathjustification/)
* Класс [IMathParagraph](../)
* Пространство имён [Aspose::Slides::MathText](../../)
* Библиотека [Aspose.Slides](../../../)