---
title: CreateMathAccent()
second_title: Aspose.Slides для C++ – справочник API
description: Создает математический акцент, применяемый к указанному математическому элементу, используя значение символа акцента по умолчанию
type: docs
weight: 1
url: /ru/aspose.slides.mathtext/imathaccentfactory/createmathaccent/
---
## IMathAccentFactory::CreateMathAccent(System::SharedPtr\<IMathElement\>) метод

Создает математический акцент, применяемый к указанному математическому элементу, используя значение символа акцента по умолчанию

```cpp
virtual System::SharedPtr<IMathAccent> Aspose::Slides::MathText::IMathAccentFactory::CreateMathAccent(System::SharedPtr<IMathElement> element)=0
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | математический элемент, к которому применяется акцент |

### Возвращаемое значение

новый математический акцент

## IMathAccentFactory::CreateMathAccent(System::SharedPtr\<IMathElement\>, char16_t) метод

Создает математический акцент, применяемый к указанному математическому элементу

```cpp
virtual System::SharedPtr<IMathAccent> Aspose::Slides::MathText::IMathAccentFactory::CreateMathAccent(System::SharedPtr<IMathElement> element, char16_t accentCharacter)=0
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | математический элемент, к которому применяется акцент |
| accentCharacter | char16_t | символ акцента |

### Возвращаемое значение

новый математический акцент

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Класс [IMathAccent](../../imathaccent/)
* Класс [IMathElement](../../imathelement/)
* Класс [IMathAccentFactory](../)
* Пространство имён [Aspose::Slides::MathText](../../)
* Библиотека [Aspose.Slides](../../../)