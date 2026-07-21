---
title: Delimit()
second_title: Aspose.Slides для C++ справочник API
description: Разделяет аргументы, используя указанный символ разделителя
type: docs
weight: 144
url: /ru/aspose.slides.mathtext/imathdelimiter/delimit/
---
## IMathDelimiter::Delimit(char16_t) метод

Разделяет аргументы, используя указанный символ-разделитель

```cpp
virtual System::SharedPtr<IMathDelimiter> Aspose::Slides::MathText::IMathDelimiter::Delimit(char16_t separatorCharacter)=0
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| separatorCharacter | char16_t | символ-разделитель |

### Возвращаемое значение

Этот объект после применения символа-разделителя
## Примечания



Пример: 
```cpp
auto delimiter = System::ExplicitCast<IMathElement>(System::MakeObject<MathematicalText>(u"x")->Join(u"y"))->Enclose();
delimiter->Delimit(u'|');
```

## Смотрите также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IMathDelimiter](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)