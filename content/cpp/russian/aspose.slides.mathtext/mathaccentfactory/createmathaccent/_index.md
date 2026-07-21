---
title: CreateMathAccent()
second_title: Справочник API Aspose.Slides для C++
description: Создает математический акцент, применяемый к указанному математическому элементу со значением символа акцента по умолчанию
type: docs
weight: 1
url: /ru/aspose.slides.mathtext/mathaccentfactory/createmathaccent/
---
## MathAccentFactory::CreateMathAccent(System::SharedPtr\<IMathElement\>) метод

Создает математический акцент, применяемый к указанному математическому элементу с значением символа акцента по умолчанию

```cpp
System::SharedPtr<IMathAccent> Aspose::Slides::MathText::MathAccentFactory::CreateMathAccent(System::SharedPtr<IMathElement> element) override
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | математический элемент, к которому применяется акцент |

### Возвращаемое значение

новый математический акцент

## MathAccentFactory::CreateMathAccent(System::SharedPtr\<IMathElement\>, char16_t) метод

Создает математический акцент, применяемый к указанному математическому элементу

```cpp
System::SharedPtr<IMathAccent> Aspose::Slides::MathText::MathAccentFactory::CreateMathAccent(System::SharedPtr<IMathElement> element, char16_t accentCharacter) override
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | математический элемент, к которому применяется акцент |
| accentCharacter | char16_t | символ акцента |

### Возвращаемое значение

новый математический акцент

## См. также

* Тип [SharedPtr](../../../system/sharedptr/)
* Класс [IMathAccent](../../imathaccent/)
* Класс [IMathElement](../../imathelement/)
* Класс [MathAccentFactory](../)
* Пространство имён [Aspose::Slides::MathText](../../)
* Библиотека [Aspose.Slides](../../../)