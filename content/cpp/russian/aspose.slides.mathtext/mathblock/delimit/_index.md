---
title: Delimit()
second_title: Справочник API Aspose.Slides для C++
description: Разделяет дочерние элементы с помощью символа-разделителя (без скобок)
type: docs
weight: 209
url: /ru/aspose.slides.mathtext/mathblock/delimit/
---
## MathBlock::Delimit(char16_t) метод


Разделяет дочерние элементы с помощью символа-разделителя (без скобок)

```cpp
System::SharedPtr<IMathDelimiter> Aspose::Slides::MathText::MathBlock::Delimit(char16_t separatorCharacter) override
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| separatorCharacter | char16_t | Символ-разделитель |

### Возвращаемое значение

Математический элемент типа [IMathDelimiter](../../imathdelimiter/)
## Примечания



Пример: 
```cpp
auto mathBlock = System::MakeObject<MathematicalText>(u"x")->Join(u"y");
auto delimiterElement = mathBlock->Delimit(u'|');
```

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IMathDelimiter](../../imathdelimiter/)
* Class [MathBlock](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)