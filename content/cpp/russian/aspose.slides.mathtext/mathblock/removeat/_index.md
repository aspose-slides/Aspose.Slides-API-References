---
title: RemoveAt()
second_title: Справочник API Aspose.Slides для C++
description: Удаляет элемент с указанным индексом в коллекции.
type: docs
weight: 170
url: /ru/aspose.slides.mathtext/mathblock/removeat/
---
## MathBlock::RemoveAt(int32_t) метод

Удаляет элемент с указанным индексом в коллекции.

```cpp
void Aspose::Slides::MathText::MathBlock::RemoveAt(int32_t index) override
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| index | **int32_t** | Нулевой индекс элемента, который нужно удалить. |

## Примечания



Пример: 
```cpp
auto mathBlock = System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"x"));
auto plusElement = System::MakeObject<MathematicalText>(u"+");
mathBlock->Add(plusElement);
mathBlock->Insert(0, System::MakeObject<MathRadical>(System::MakeObject<MathematicalText>(u"x"), System::MakeObject<MathematicalText>(u"3")));
mathBlock->RemoveAt(2);
```

## См. также

* Класс [MathBlock](../)
* Пространство имён [Aspose::Slides::MathText](../../)
* Библиотека [Aspose.Slides](../../../)