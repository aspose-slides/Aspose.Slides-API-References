---
title: Contains()
second_title: Aspose.Slides для C++ справочник API
description: Определяет, содержит ли коллекция конкретное значение.
type: docs
weight: 79
url: /ru/aspose.slides.mathtext/imathelementcollection/contains/
---
## IMathElementCollection::Contains(System::SharedPtr\<IMathElement\>) метод


Определяет, содержит ли коллекция конкретное значение.

```cpp
virtual bool Aspose::Slides::MathText::IMathElementCollection::Contains(System::SharedPtr<IMathElement> item)=0
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| item | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Объект, который необходимо найти в коллекции. |

### Возвращаемое значение

true, если *item* найден в коллекции; в противном случае — false.
## Примечания



Пример: 
```cpp
auto collection = System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"x"));
auto plusElement = System::MakeObject<MathematicalText>(u"+");
collection->Add(plusElement);
collection->Add(System::MakeObject<MathRadical>(System::MakeObject<MathematicalText>(u"x"), System::MakeObject<MathematicalText>(u"3")));
bool contains = collection->Contains(plusElement);
```

## Смотрите также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Класс [IMathElement](../../imathelement/)
* Класс [IMathElementCollection](../)
* Пространство имён [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)