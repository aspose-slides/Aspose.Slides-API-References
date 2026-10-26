---
title: SetLowerLimit()
second_title: Справочник API Aspose.Slides для C++
description: Принимает нижний предел
type: docs
weight: 157
url: /ru/aspose.slides.mathtext/imathelement/setlowerlimit/
---
## IMathElement::SetLowerLimit(System::SharedPtr\<IMathElement\>) метод

Принимает нижний предел

```cpp
virtual System::SharedPtr<IMathLimit> Aspose::Slides::MathText::IMathElement::SetLowerLimit(System::SharedPtr<IMathElement> limit)=0
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| limit | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../)\> | limit |

### Возвращаемое значение

Новый экземпляр типа [IMathLimit](../../imathlimit/)

## Замечания

Пример: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"lim");
auto limitValue = System::MakeObject<MathematicalText>(u"\U0001d45b→∞");
auto limitElement = baseElement->SetLowerLimit(limitValue);
```

## IMathElement::SetLowerLimit(System::String) метод

Придает нижний предел

```cpp
virtual System::SharedPtr<IMathLimit> Aspose::Slides::MathText::IMathElement::SetLowerLimit(System::String limit)=0
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| limit | [System::String](../../../system/string/) | limit |

### Возвращаемое значение

Новый экземпляр типа [IMathLimit](../../imathlimit/)

## Замечания

Пример: 
```cpp
System::SharedPtr<IMathElement> baseElement = System::MakeObject<MathematicalText>(u"lim");
auto limitElement = baseElement->SetLowerLimit(u"\U0001d45b→∞");
```

## См. также

* Типовое определение [SharedPtr](../../../system/sharedptr/)
* Класс [IMathLimit](../../imathlimit/)
* Класс [IMathElement](../)
* Класс [String](../../../system/string/)
* Пространство имён [Aspose::Slides::MathText](../../)
* Библиотека [Aspose.Slides](../../../)