---
title: SetSubscript()
second_title: Справочник API Aspose.Slides для C++
description: Создает субскрипт
type: docs
weight: 66
url: /ru/aspose.slides.mathtext/mathelementbase/setsubscript/
---
## MathElementBase::SetSubscript(System::SharedPtr\<IMathElement\>) метод


Создает субскрипт

```cpp
System::SharedPtr<IMathSubscriptElement> Aspose::Slides::MathText::MathElementBase::SetSubscript(System::SharedPtr<IMathElement> subscript) override
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| subscript | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Субскрипт (нижний индекс справа) |

### Возвращаемое значение

Новый математический элемент типа [IMathSubscriptElement](../../imathsubscriptelement/)
## Примечания



Пример: 
```cpp
auto element = System::MakeObject<MathematicalText>(u"N");
auto index = System::MakeObject<MathematicalText>(u"i");
auto subscript = element->SetSubscript(index);
```

## MathElementBase::SetSubscript(System::String) метод


Создает субскрипт

```cpp
System::SharedPtr<IMathSubscriptElement> Aspose::Slides::MathText::MathElementBase::SetSubscript(System::String subscript) override
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| subscript | [System::String](../../../system/string/) | Субскрипт (нижний индекс справа) |

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
* Класс [IMathElement](../../imathelement/)
* Класс [MathElementBase](../)
* Класс [String](../../../system/string/)
* Пространство имен [Aspose::Slides::MathText](../../)
* Библиотека [Aspose.Slides](../../../)