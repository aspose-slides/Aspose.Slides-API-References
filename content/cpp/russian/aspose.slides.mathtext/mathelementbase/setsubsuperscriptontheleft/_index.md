---
title: SetSubSuperscriptOnTheLeft()
second_title: Aspose.Slides для C++ справочник API
description: Создаёт нижний и верхний индексы слева
type: docs
weight: 105
url: /ru/aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft/
---
## MathElementBase::SetSubSuperscriptOnTheLeft(System::SharedPtr\<IMathElement\>, System::SharedPtr\<IMathElement\>) method

Создаёт нижний и верхний индексы слева

```cpp
System::SharedPtr<IMathLeftSubSuperscriptElement> Aspose::Slides::MathText::MathElementBase::SetSubSuperscriptOnTheLeft(System::SharedPtr<IMathElement> subscript, System::SharedPtr<IMathElement> superscript) override
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| subscript | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Подстрочный индекс (нижний индекс слева) |
| superscript | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Надстрочный индекс (верхний индекс слева) |

### Возвращаемое значение

Новый элемент математического выражения типа [IMathLeftSubSuperscriptElement](../../imathleftsubsuperscriptelement/)
## Примечания



Пример: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"N");
auto subscript = System::MakeObject<MathematicalText>(u"i");
auto superscript = System::MakeObject<MathematicalText>(u"j");
auto leftSubsuperscript = baseElement->SetSubSuperscriptOnTheLeft(subscript, superscript);
```

## MathElementBase::SetSubSuperscriptOnTheLeft(System::String, System::String) method

Создаёт нижний и верхний индексы слева

```cpp
System::SharedPtr<IMathLeftSubSuperscriptElement> Aspose::Slides::MathText::MathElementBase::SetSubSuperscriptOnTheLeft(System::String subscript, System::String superscript) override
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| subscript | [System::String](../../../system/string/) | Подстрочный индекс (нижний индекс слева) |
| superscript | [System::String](../../../system/string/) | Надстрочный индекс (верхний индекс слева) |

### Возвращаемое значение

Новый элемент математического выражения типа [IMathLeftSubSuperscriptElement](../../imathleftsubsuperscriptelement/)
## Примечания



Пример: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"N");
auto leftSubsuperscript = baseElement->SetSubSuperscriptOnTheLeft(u"i", u"j");
```

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Класс [IMathLeftSubSuperscriptElement](../../imathleftsubsuperscriptelement/)
* Класс [IMathElement](../../imathelement/)
* Класс [MathElementBase](../)
* Класс [String](../../../system/string/)
* Пространство имён [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)