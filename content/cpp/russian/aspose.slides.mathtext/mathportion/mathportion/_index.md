---
title: MathPortion()
second_title: Справочник API Aspose.Slides для C++
description: Инициализирует новый экземпляр класса MathPortion.
type: docs
weight: 14
url: /ru/aspose.slides.mathtext/mathportion/mathportion/
---
## MathPortion::MathPortion() конструктор

Инициализирует новый экземпляр класса [MathPortion](../).

```cpp
Aspose::Slides::MathText::MathPortion::MathPortion()
```

## Примечания

Пример:
```cpp
auto pres = System::MakeObject<Presentation>();
auto shape = pres->get_Slides()->idx_get(0)->get_Shapes()->AddMathShape(0.0f, 0.0f, 300.0f, 50.0f);
auto paragraph = shape->get_TextFrame()->get_Paragraphs()->idx_get(0);
auto mathPortion = System::MakeObject<MathPortion>();
paragraph->get_Portions()->Add(mathPortion);
```

## См. также

* Класс [MathPortion](../)
* Пространство имён [Aspose::Slides::MathText](../../)
* Библиотека [Aspose.Slides](../../../)