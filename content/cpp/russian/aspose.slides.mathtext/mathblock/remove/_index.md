---
title: Remove()
second_title: Aspose.Slides для C++: справочник API
description: Удаляет первое вхождение конкретного объекта из коллекции.
type: docs
weight: 131
url: /ru/aspose.slides.mathtext/mathblock/remove/
---
## MathBlock::Remove(System::SharedPtr\<IMathElement\>) метод

Удаляет первое вхождение указанного объекта из коллекции.

```cpp
bool Aspose::Slides::MathText::MathBlock::Remove(System::SharedPtr<IMathElement> item) override
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| item | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Объект, который необходимо удалить из коллекции. |

### Возвращаемое значение

true, если *item* был успешно удалён из коллекции; иначе — false. Этот метод также возвращает false, если *item* не найден в исходной коллекции.

## Примечания

Пример: 
```cpp
auto mathBlock = System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"x"));
auto plusElement = System::MakeObject<MathematicalText>(u"+");
mathBlock->Add(plusElement);
mathBlock->Add(System::MakeObject<MathRadical>(System::MakeObject<MathematicalText>(u"x"), System::MakeObject<MathematicalText>(u"3")));
mathBlock->Remove(plusElement);
```

## Смотрите также

* typedef [SharedPtr](../../../system/sharedptr/)
* Класс [IMathElement](../../imathelement/)
* Класс [MathBlock](../)
* Пространство имён [Aspose::Slides::MathText](../../)
* Библиотека [Aspose.Slides](../../../)