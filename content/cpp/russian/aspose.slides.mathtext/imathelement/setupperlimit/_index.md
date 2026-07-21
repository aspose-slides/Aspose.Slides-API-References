---
title: SetUpperLimit()
second_title: Aspose.Slides для C++: справочник API
description: Принимает верхний предел
type: docs
weight: 144
url: /ru/aspose.slides.mathtext/imathelement/setupperlimit/
---
## IMathElement::SetUpperLimit(System::SharedPtr\<IMathElement\>) метод


Принимает верхний предел

```cpp
virtual System::SharedPtr<IMathLimit> Aspose::Slides::MathText::IMathElement::SetUpperLimit(System::SharedPtr<IMathElement> limit)=0
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| limit | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../)\> | limit |

### Возвращаемое значение

Новый экземпляр типа [IMathLimit](../../imathlimit/)
## Примечания



Пример: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"y");
auto limitValue = System::MakeObject<MathematicalText>(u"y?>1");
auto limitElement = baseElement->SetUpperLimit(limitValue);
```

## IMathElement::SetUpperLimit(System::String) метод


Принимает верхний предел

```cpp
virtual System::SharedPtr<IMathLimit> Aspose::Slides::MathText::IMathElement::SetUpperLimit(System::String limit)=0
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
auto baseElement = System::MakeObject<MathematicalText>(u"y");
auto limitElement = baseElement->SetUpperLimit(u"y?>1");
```

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Класс [IMathLimit](../../imathlimit/)
* Класс [IMathElement](../)
* Класс [String](../../../system/string/)
* Пространство имён [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)