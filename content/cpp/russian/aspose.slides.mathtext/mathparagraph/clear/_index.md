---
title: Clear()
second_title: Aspose.Slides для C++ справочник API
description: Удаляет все элементы из коллекции.
type: docs
weight: 79
url: /ru/aspose.slides.mathtext/mathparagraph/clear/
---
## MathParagraph::Clear() метод


Удаляет все элементы из коллекции.

```cpp
void Aspose::Slides::MathText::MathParagraph::Clear() override
```

## Примечания


Пример: 
```cpp
auto shape = slide->get_Shapes()->AddMathShape(x, y, width, height);
auto mathParagraph = (System::AsCast<MathPortion>(shape->get_TextFrame()->get_Paragraphs()->idx_get(0)->get_Portions()->idx_get(0)))->get_MathParagraph();
mathParagraph->Add(System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"block1")));
mathParagraph->Add(System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"block2")));
mathParagraph->Clear();
```

## Смотрите также

* Класс [MathParagraph](../)
* Пространство имён [Aspose::Slides::MathText](../../)
* Библиотека [Aspose.Slides](../../../)