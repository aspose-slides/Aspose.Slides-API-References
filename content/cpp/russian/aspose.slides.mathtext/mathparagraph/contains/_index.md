---
title: Contains()
second_title: Справочник API Aspose.Slides для C++
description: Определяет, содержит ли коллекция заданное значение.
type: docs
weight: 118
url: /ru/aspose.slides.mathtext/mathparagraph/contains/
---
## MathParagraph::Contains(System::SharedPtr\<IMathBlock\>) метод

Определяет, содержит ли коллекция заданное значение.

```cpp
bool Aspose::Slides::MathText::MathParagraph::Contains(System::SharedPtr<IMathBlock> mathBlock) override
```

### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| mathBlock | [System::SharedPtr](../../../system/sharedptr/)\<[IMathBlock](../../imathblock/)\> | Объект, который необходимо найти в коллекции. |

### Возвращаемое значение

true, если *mathBlock* найден в коллекции; иначе — false.
## Примечания



Пример: 
```cpp
auto shape = slide->get_Shapes()->AddMathShape(x, y, width, height);
auto mathParagraph = (System::AsCast<MathPortion>(shape->get_TextFrame()->get_Paragraphs()->idx_get(0)->get_Portions()->idx_get(0)))->get_MathParagraph();
auto block = System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"y"));
mathParagraph->Add(block);
bool contains = mathParagraph->Contains(block);
```

## Смотрите также

* Тип [SharedPtr](../../../system/sharedptr/)
* Класс [IMathBlock](../../imathblock/)
* Класс [MathParagraph](../)
* Пространство имён [Aspose::Slides::MathText](../../)
* Библиотека [Aspose.Slides](../../../)