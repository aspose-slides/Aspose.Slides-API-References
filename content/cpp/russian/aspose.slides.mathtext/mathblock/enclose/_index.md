---
title: Enclose()
second_title: Справочник API Aspose.Slides для C++
description: Обрамляет дочерние элементы этого блока указанными символами, например, скобками или другими символами
type: docs
weight: 222
url: /ru/aspose.slides.mathtext/mathblock/enclose/
---
## MathBlock::Enclose(char16_t, char16_t) метод


Обрамляет дочерние элементы этого блока указанными символами, например, скобками или другими символами

```cpp
System::SharedPtr<IMathDelimiter> Aspose::Slides::MathText::MathBlock::Enclose(char16_t beginningCharacter, char16_t endingCharacter) override
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| beginningCharacter | char16_t | Начальный символ (обычно левая скобка) |
| endingCharacter | char16_t | Конечный символ (обычно правая скобка) |

### Возвращаемое значение

Элемент математического типа [IMathDelimiter](../../imathdelimiter/), который включает указанные символы в качестве рамки
## Примечания



Пример: 
```cpp
auto block = System::MakeObject<MathematicalText>(u"x")->Join(u"+y");
auto delimiter = System::ExplicitCast<IMathElement>(block)->Enclose(u'[', u']');
```

## MathBlock::Enclose(char16_t, char16_t, char16_t) метод


Обрамляет дочерние элементы этого блока указанными символами, например, скобками или другими, и разделяет их разделительным символом

```cpp
System::SharedPtr<IMathDelimiter> Aspose::Slides::MathText::MathBlock::Enclose(char16_t beginningCharacter, char16_t endingCharacter, char16_t separatorCharacter) override
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| beginningCharacter | char16_t | Начальный символ (обычно левая скобка) |
| endingCharacter | char16_t | Конечный символ (обычно правая скобка) |
| separatorCharacter | char16_t | Разделительный символ |

### Возвращаемое значение

Элемент математического типа [IMathDelimiter](../../imathdelimiter/), который включает указанные символы в качестве рамки и разделителя
## Примечания



Пример: 
```cpp
auto mathBlock = System::MakeObject<MathematicalText>(u"x")->Join(u"y");
auto delimiterElement = mathBlock->Enclose(u'{', u'}', u'%');
```

## Смотрите также

* Тип [SharedPtr](../../../system/sharedptr/)
* Класс [IMathDelimiter](../../imathdelimiter/)
* Класс [MathBlock](../)
* Пространство имён [Aspose::Slides::MathText](../../)
* Библиотека [Aspose.Slides](../../../)