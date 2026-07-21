---
title: Enclose()
second_title: Aspose.Slides для C++ справочник API
description: Обрамляет дочерние элементы этого блока указанными символами, такими как скобки, и разделяет их символом-разделителем
type: docs
weight: 14
url: /ru/aspose.slides.mathtext/imathblock/enclose/
---
## IMathBlock::Enclose(char16_t, char16_t, char16_t) метод

Обрамляет дочерние элементы этого блока указанными символами, такими как скобки, и разделяет их символом-разделителем

```cpp
virtual System::SharedPtr<IMathDelimiter> Aspose::Slides::MathText::IMathBlock::Enclose(char16_t beginningCharacter, char16_t endingCharacter, char16_t separatorCharacter)=0
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| beginningCharacter | char16_t | Начальный символ (обычно левая скобка) |
| endingCharacter | char16_t | Конечный символ (обычно правая скобка) |
| separatorCharacter | char16_t | Символ-разделитель |

### Возвращаемое значение

Элемент математики типа [IMathDelimiter](../../imathdelimiter/), включающий указанные символы в качестве рамки и разделителя

## Примечания

Пример:
```cpp
auto mathBlock = System::MakeObject<MathematicalText>(u"x")->Join(u"y");
auto delimiterElement = mathBlock->Enclose(u'{', u'}', u'%');
```

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IMathDelimiter](../../imathdelimiter/)
* Class [IMathBlock](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)