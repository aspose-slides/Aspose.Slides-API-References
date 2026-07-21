---
title: SetSubSuperscriptOnTheLeft()
second_title: Справочник API Aspose.Slides для C++
description: Создает нижний и верхний индексы слева
type: docs
weight: 118
url: /ru/aspose.slides.mathtext/imathelement/setsubsuperscriptontheleft/
---
## IMathElement::SetSubSuperscriptOnTheLeft(System::SharedPtr\<IMathElement\>, System::SharedPtr\<IMathElement\>) метод

Создает нижний и верхний индексы слева

```cpp
virtual System::SharedPtr<IMathLeftSubSuperscriptElement> Aspose::Slides::MathText::IMathElement::SetSubSuperscriptOnTheLeft(System::SharedPtr<IMathElement> subscript, System::SharedPtr<IMathElement> superscript)=0
```

### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| subscript | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../)\> | Нижний индекс (нижний индекс слева) |
| superscript | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../)\> | Верхний индекс (верхний индекс слева) |

### Возвращаемое значение

Новый элемент формулы типа [IMathLeftSubSuperscriptElement](../../imathleftsubsuperscriptelement/)

## Примечания

Example: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"N");
auto subscript = System::MakeObject<MathematicalText>(u"i");
auto superscript = System::MakeObject<MathematicalText>(u"j");
auto leftSubsuperscript = baseElement->SetSubSuperscriptOnTheLeft(subscript, superscript);
```

## IMathElement::SetSubSuperscriptOnTheLeft(System::String, System::String) метод

Создает нижний и верхний индексы слева

```cpp
virtual System::SharedPtr<IMathLeftSubSuperscriptElement> Aspose::Slides::MathText::IMathElement::SetSubSuperscriptOnTheLeft(System::String subscript, System::String superscript)=0
```

### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| subscript | [System::String](../../../system/string/) | Нижний индекс (нижний индекс слева) |
| superscript | [System::String](../../../system/string/) | Верхний индекс (верхний индекс слева) |

### Возвращаемое значение

Новый элемент формулы типа [IMathLeftSubSuperscriptElement](../../imathleftsubsuperscriptelement/)

## Примечания

Example: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"N");
auto leftSubsuperscript = baseElement->SetSubSuperscriptOnTheLeft(u"i", u"j");
```

## См. также

* Тип [SharedPtr](../../../system/sharedptr/)
* Класс [IMathLeftSubSuperscriptElement](../../imathleftsubsuperscriptelement/)
* Класс [IMathElement](../)
* Класс [String](../../../system/string/)
* Пространство имён [Aspose::Slides::MathText](../../)
* Библиотека [Aspose.Slides](../../../)