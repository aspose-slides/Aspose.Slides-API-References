---
title: RemoveAt()
second_title: Aspose.Slides для C++ справочника API
description: Удаляет элемент с указанным индексом в коллекции.
type: docs
weight: 53
url: /ru/aspose.slides.mathtext/imathblockcollection/removeat/
---
## IMathBlockCollection::RemoveAt(int32_t) метод

Удаляет элемент с указанным индексом в коллекции.

```cpp
virtual void Aspose::Slides::MathText::IMathBlockCollection::RemoveAt(int32_t index)=0
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| index | **int32_t** | Нулевой индекс элемента, который следует удалить. |
## Примечания



Пример: 
```cpp
auto blockCollection = System::MakeObject<MathParagraph>();
auto block = System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"y"));
blockCollection->Add(block);
blockCollection->RemoveAt(0);
```

## Смотрите также

* Класс [IMathBlockCollection](../)
* Пространство имён [Aspose::Slides::MathText](../../)
* Библиотека [Aspose.Slides](../../../)