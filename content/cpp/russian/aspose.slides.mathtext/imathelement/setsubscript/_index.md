---
title: SetSubscript()
second_title: Aspose.Slides для C++ справочник API
description: Создаёт подстрочный индекс
type: docs
weight: 79
url: /ru/aspose.slides.mathtext/imathelement/setsubscript/
---
## IMathElement::SetSubscript(System::SharedPtr\<IMathElement\>) метод


Создаёт подстрочный индекс

```cpp
virtual System::SharedPtr<IMathSubscriptElement> Aspose::Slides::MathText::IMathElement::SetSubscript(System::SharedPtr<IMathElement> subscript)=0
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| subscript | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../)\> | Подстрочный индекс (нижний индекс справа) |

### Возвращаемое значение

Новый математический элемент типа [IMathSubscriptElement](../../imathsubscriptelement/)
## Примечания



Пример: 
```cpp
auto element = System::MakeObject<MathematicalText>(u"N");
auto index = System::MakeObject<MathematicalText>(u"i");
auto subscript = element->SetSubscript(index);
```

## IMathElement::SetSubscript(System::String) метод


Создаёт подстрочный индекс

```cpp
virtual System::SharedPtr<IMathSubscriptElement> Aspose::Slides::MathText::IMathElement::SetSubscript(System::String subscript)=0
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| subscript | [System::String](../../../system/string/) | Подстрочный индекс (нижний индекс справа) |

### Возвращаемое значение

Новый математический элемент типа [IMathSubscriptElement](../../imathsubscriptelement/)
## Примечания



Пример: 
```cpp
auto element = System::MakeObject<MathematicalText>(u"N");
auto subscript = element->SetSubscript(u"i");
```

## См. также

* Тип [SharedPtr](../../../system/sharedptr/)
* Класс [IMathSubscriptElement](../../imathsubscriptelement/)
* Класс [IMathElement](../)
* Класс [String](../../../system/string/)
* Пространство имён [Aspose::Slides::MathText](../../)
* Библиотека [Aspose.Slides](../../../)