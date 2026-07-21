---
title: Add()
second_title: Справочник API Aspose.Slides для C++
description: Добавляет IMathBlock в конец коллекции.
type: docs
weight: 92
url: /ru/aspose.slides.mathtext/mathparagraph/add/
---
## MathParagraph::Add(System::SharedPtr\<IMathBlock\>) метод

Добавляет [IMathBlock](../../imathblock/) в конец коллекции.

```cpp
void Aspose::Slides::MathText::MathParagraph::Add(System::SharedPtr<IMathBlock> mathBlock) override
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| mathBlock | [System::SharedPtr](../../../system/sharedptr/)\<[IMathBlock](../../imathblock/)\> | Математический блок, который будет добавлен в конец коллекции |

## Примечания


Пример: 
```cpp
auto shape = slide->get_Shapes()->AddMathShape(x, y, width, height);
auto mathParagraph = (System::AsCast<MathPortion>(shape->get_TextFrame()->get_Paragraphs()->idx_get(0)->get_Portions()->idx_get(0)))->get_MathParagraph();
mathParagraph->Add(System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"x")));
```

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Класс [IMathBlock](../../imathblock/)
* Класс [MathParagraph](../)
* Пространство имён [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)