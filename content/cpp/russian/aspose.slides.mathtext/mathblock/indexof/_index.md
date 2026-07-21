---
title: IndexOf()
second_title: Справка API Aspose.Slides для C++
description: Определяет индекс конкретного математического элемента в коллекции.
type: docs
weight: 144
url: /ru/aspose.slides.mathtext/mathblock/indexof/
---
## MathBlock::IndexOf(System::SharedPtr\<IMathElement\>) метод


Определяет индекс определённого математического элемента в коллекции.

```cpp
int32_t Aspose::Slides::MathText::MathBlock::IndexOf(System::SharedPtr<IMathElement> item) override
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| item | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Элемент, который нужно найти в коллекции. |

### Возвращаемое значение

Индекс *item*, если он найден в коллекции; иначе -1.
## Примечания



Пример: 
```cpp
auto mathBlock = System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"x"));
auto plusElement = System::MakeObject<MathematicalText>(u"+");
mathBlock->Add(plusElement);
mathBlock->Add(System::MakeObject<MathRadical>(System::MakeObject<MathematicalText>(u"x"), System::MakeObject<MathematicalText>(u"3")));
int32_t index = mathBlock->IndexOf(plusElement);
```

## Смотрите также

* Тип [SharedPtr](../../../system/sharedptr/)
* Класс [IMathElement](../../imathelement/)
* Класс [MathBlock](../)
* Пространство имён [Aspose::Slides::MathText](../../)
* Библиотека [Aspose.Slides](../../../)