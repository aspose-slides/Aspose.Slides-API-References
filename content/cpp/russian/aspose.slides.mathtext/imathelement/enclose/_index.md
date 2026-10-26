---
title: Enclose()
second_title: Aspose.Slides для C++ — справочник API
description: Обрамляет математический элемент в скобки
type: docs
weight: 40
url: /ru/aspose.slides.mathtext/imathelement/enclose/
---
## IMathElement::Enclose() метод


Обрамляет математический элемент в скобки

```cpp
virtual System::SharedPtr<IMathDelimiter> Aspose::Slides::MathText::IMathElement::Enclose()=0
```


### Возвращаемое значение

Математический элемент типа [IMathDelimiter](../../imathdelimiter/) который включает скобки
## Примечания



Пример: 
```cpp
auto element = System::MakeObject<MathematicalText>(u"x");
auto delimiter = element->Enclose();
```

## IMathElement::Enclose(char16_t, char16_t) метод


Обрамляет этот элемент указанными символами, такими как скобки или другими символами, в качестве обрамления

```cpp
virtual System::SharedPtr<IMathDelimiter> Aspose::Slides::MathText::IMathElement::Enclose(char16_t beginningCharacter, char16_t endingCharacter)=0
```


### Параметры

| Parameter | Type | Description |
| --- | --- | --- |
| beginningCharacter | char16_t | Начальный символ (обычно левая скобка) |
| endingCharacter | char16_t | Конечный символ (обычно правая скобка) |

### Возвращаемое значение

Математический элемент типа [IMathDelimiter](../../imathdelimiter/) который включает указанные символы в качестве обрамления
## Примечания



Пример: 
```cpp
auto element = System::MakeObject<MathematicalText>(u"x");
auto delimiter = element->Enclose(u'[', u']');
```

## Смотрите также

* Тип [SharedPtr](../../../system/sharedptr/)
* Класс [IMathDelimiter](../../imathdelimiter/)
* Класс [IMathElement](../)
* Простейство имён [Aspose::Slides::MathText](../../)
* Библиотека [Aspose.Slides](../../../)