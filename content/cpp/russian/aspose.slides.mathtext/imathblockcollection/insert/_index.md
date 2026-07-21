---
title: Insert()
second_title: Справочник API Aspose.Slides для C++
description: Вставляет IMathBlock в коллекцию по указанному индексу.
type: docs
weight: 27
url: /ru/aspose.slides.mathtext/imathblockcollection/insert/
---
## IMathBlockCollection::Insert(int32_t, System::SharedPtr\<IMathBlock\>) метод

Вставляет [IMathBlock](../../imathblock/) в коллекцию по указанному индексу.

```cpp
virtual void Aspose::Slides::MathText::IMathBlockCollection::Insert(int32_t index, System::SharedPtr<IMathBlock> item)=0
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| index | **int32_t** | Нулевой индекс, в котором элемент должен быть вставлен. |
| item | [System::SharedPtr](../../../system/sharedptr/)\<[IMathBlock](../../imathblock/)\> | Объект [IMathBlock](../../imathblock/) для вставки. |
## Примечания



Пример: 
```cpp
auto blockCollection = System::MakeObject<MathParagraph>();
auto block = System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"y"));
blockCollection->Insert(0, block);
```

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Класс [IMathBlock](../../imathblock/)
* Класс [IMathBlockCollection](../)
* Пространство имён [Aspose::Slides::MathText](../../)
* Библиотека [Aspose.Slides](../../../)