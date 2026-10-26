---
title: SetLowerLimit()
second_title: Aspose.Slides для C++ справочник API
description: Принимает нижний предел
type: docs
weight: 144
url: /ru/aspose.slides.mathtext/mathelementbase/setlowerlimit/
---
## MathElementBase::SetLowerLimit(System::SharedPtr\<IMathElement\>) метод


Принимает нижний предел

```cpp
System::SharedPtr<IMathLimit> Aspose::Slides::MathText::MathElementBase::SetLowerLimit(System::SharedPtr<IMathElement> limit) override
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| limit | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | limit |

### Возвращаемое значение

Новый экземпляр типа [IMathLimit](../../imathlimit/)
## Примечания



Пример: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"lim");
auto limitValue = System::MakeObject<MathematicalText>(u"\U0001d45b→∞");
auto limitElement = baseElement->SetLowerLimit(limitValue);
```

## MathElementBase::SetLowerLimit(System::String) метод


Принимает нижний предел

```cpp
System::SharedPtr<IMathLimit> Aspose::Slides::MathText::MathElementBase::SetLowerLimit(System::String limit) override
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| limit | [System::String](../../../system/string/) | limit |

### Возвращаемое значение

Новый экземпляр типа [IMathLimit](../../imathlimit/)
## Примечания



Пример: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"lim");
auto limitElement = baseElement->SetLowerLimit(u"\U0001d45b→∞");
```

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Класс [IMathLimit](../../imathlimit/)
* Класс [IMathElement](../../imathelement/)
* Класс [MathElementBase](../)
* Класс [String](../../../system/string/)
* Пространство имён [Aspose::Slides::MathText](../../)
* Библиотека [Aspose.Slides](../../../)