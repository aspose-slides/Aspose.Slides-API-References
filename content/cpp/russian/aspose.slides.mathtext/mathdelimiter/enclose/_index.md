---
title: Enclose()
second_title: Справочник API Aspose.Slides для C++
description: Обрамляет математический элемент указанными символами, такими как скобки или другими символами в качестве рамки
type: docs
weight: 170
url: /ru/aspose.slides.mathtext/mathdelimiter/enclose/
---
## MathDelimiter::Enclose(char16_t, char16_t) метод


Обрамляет математический элемент указанными символами, такими как скобки или другими символами в качестве рамки

```cpp
System::SharedPtr<IMathDelimiter> Aspose::Slides::MathText::MathDelimiter::Enclose(char16_t beginningCharacter, char16_t endingCharacter) override
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| beginningCharacter | char16_t | Начальный символ (обычно левая скобка) |
| endingCharacter | char16_t | Конечный символ (обычно правая скобка) |

### Возвращаемое значение

Если *beginningCharacter* и *endingCharacter* равны null, соответствующим свойствам присваиваются только значения и новый объект не создаётся (возвращается этот экземпляр). В противном случае возвращается новый математический элемент типа Delimiter, который включает указанные символы в качестве рамки и этот экземпляр [MathDelimiter](../) помещён внутрь.
## Примечания



Пример: 
```cpp
auto innerDelimiter = System::ExplicitCast<IMathElement>(System::MakeObject<MathematicalText>(u"x")->Join(u",y"))->Enclose(u'{', u'}');
auto outerDelimiter = innerDelimiter->Enclose(u'[', u']');
```

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Класс [IMathDelimiter](../../imathdelimiter/)
* Класс [MathDelimiter](../)
* Пространство имён [Aspose::Slides::MathText](../../)
* Библиотека [Aspose.Slides](../../../)