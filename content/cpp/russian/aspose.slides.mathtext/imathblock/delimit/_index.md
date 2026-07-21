---
title: Delimit()
second_title: Справочник API Aspose.Slides для C++
description: Разделяет все дочерние элементы символом-разделителем (без скобок)
type: docs
weight: 1
url: /ru/aspose.slides.mathtext/imathblock/delimit/
---
## IMathBlock::Delimit(char16_t) метод

Разделяет все дочерние элементы символом-разделителем (без скобок)

```cpp
virtual System::SharedPtr<IMathDelimiter> Aspose::Slides::MathText::IMathBlock::Delimit(char16_t separatorCharacter)=0
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| separatorCharacter | char16_t | Символ, используемый в качестве разделителя |

### Возвращаемое значение

Экземпляр элемента [IMathDelimiter](../../imathdelimiter/)

## Замечания



Пример: 
```cpp
auto mathBlock = System::MakeObject<MathematicalText>(u"x")->Join(u"y");
auto delimiterElement = mathBlock->Delimit(u'|');
```

## Смотрите также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Класс [IMathDelimiter](../../imathdelimiter/)
* Класс [IMathBlock](../)
* Пространство имён [Aspose::Slides::MathText](../../)
* Библиотека [Aspose.Slides](../../../)