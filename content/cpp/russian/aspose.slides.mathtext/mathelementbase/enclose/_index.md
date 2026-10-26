---
title: Enclose()
second_title: Aspose.Slides для C++ справка по API
description: Обрамляет математический элемент в скобки
type: docs
weight: 27
url: /ru/aspose.slides.mathtext/mathelementbase/enclose/
---
## MathElementBase::Enclose() метод


Обрамляет математический элемент в скобки

```cpp
System::SharedPtr<IMathDelimiter> Aspose::Slides::MathText::MathElementBase::Enclose() override
```


### Возвращаемое значение

Математический элемент типа [IMathDelimiter](../../imathdelimiter/), который включает скобки
## Замечания



Пример: 
```cpp
auto element = System::MakeObject<MathematicalText>(u"x");
auto delimiter = element->Enclose();
```

## MathElementBase::Enclose(char16_t, char16_t) метод


Обрамляет математический элемент в указанные символы, такие как скобки или другие символы

```cpp
System::SharedPtr<IMathDelimiter> Aspose::Slides::MathText::MathElementBase::Enclose(char16_t beginningCharacter, char16_t endingCharacter) override
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| beginningCharacter | char16_t | Начальный символ (обычно левая скобка) |
| endingCharacter | char16_t | Конечный символ (обычно правая скобка) |

### Возвращаемое значение

Математический элемент типа [IMathDelimiter](../../imathdelimiter/), который включает указанные символы как обрамление
## Замечания



Пример: 
```cpp
auto element = System::MakeObject<MathematicalText>(u"x");
auto delimiter = element->Enclose(u'[', u']');
```

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Класс [IMathDelimiter](../../imathdelimiter/)
* Класс [MathElementBase](../)
* Пространство имён [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)