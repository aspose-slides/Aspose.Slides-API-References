---
title: IndexOf()
second_title: Справочник API Aspose.Slides для C++
description: Определяет индекс конкретного математического элемента в коллекции.
type: docs
weight: 40
url: /ru/aspose.slides.mathtext/imathelementcollection/indexof/
---
## IMathElementCollection::IndexOf(System::SharedPtr\<IMathElement\>) метод

Определяет индекс конкретного математического элемента в коллекции.

```cpp
virtual int32_t Aspose::Slides::MathText::IMathElementCollection::IndexOf(System::SharedPtr<IMathElement> item)=0
```

### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| item | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Элемент, который нужно найти в коллекции. |

### Возвращаемое значение

Индекс *item*, если он найден в коллекции; в противном случае -1.
## Примечания



Пример: 
```cpp
auto collection = System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"x"));
auto plusElement = System::MakeObject<MathematicalText>(u"+");
collection->Add(plusElement);
collection->Add(System::MakeObject<MathRadical>(System::MakeObject<MathematicalText>(u"x"), System::MakeObject<MathematicalText>(u"3")));
int32_t index = collection->IndexOf(plusElement);
```

## См. также

* Тип [SharedPtr](../../../system/sharedptr/)
* Класс [IMathElement](../../imathelement/)
* Класс [IMathElementCollection](../)
* Пространство имён [Aspose::Slides::MathText](../../)
* Библиотека [Aspose.Slides](../../../)