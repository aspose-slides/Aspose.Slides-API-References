---
title: Remove()
second_title: Aspose.Slides для C++ справочник API
description: Удаляет первое вхождение конкретного объекта из коллекции.
type: docs
weight: 92
url: /ru/aspose.slides.mathtext/imathelementcollection/remove/
---
## IMathElementCollection::Remove(System::SharedPtr\<IMathElement\>) method

Удаляет первое вхождение указанного объекта из коллекции.

```cpp
virtual bool Aspose::Slides::MathText::IMathElementCollection::Remove(System::SharedPtr<IMathElement> item)=0
```

### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| item | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Объект, который необходимо удалить из коллекции. |

### Возвращаемое значение

true, если *item* был успешно удалён из коллекции; в противном случае — false. Этот метод также возвращает false, если *item* не найден в исходной коллекции.

## Примечания

Пример: 
```cpp
auto collection = System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"x"));
auto plusElement = System::MakeObject<MathematicalText>(u"+");
collection->Add(plusElement);
collection->Add(System::MakeObject<MathRadical>(System::MakeObject<MathematicalText>(u"x"), System::MakeObject<MathematicalText>(u"3")));
collection->Remove(plusElement);
```

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Класс [IMathElement](../../imathelement/)
* Класс [IMathElementCollection](../)
* Пространство имён [Aspose::Slides::MathText](../../)
* Библиотека [Aspose.Slides](../../../)