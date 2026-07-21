---
title: CreateMathematicalText()
second_title: Aspose.Slides для C++ справочник API
description: Создать пустой элемент математического текста
type: docs
weight: 1
url: /ru/aspose.slides.mathtext/imathematicaltextfactory/createmathematicaltext/
---
## IMathematicalTextFactory::CreateMathematicalText() метод

Создать пустой элемент математического текста

```cpp
virtual System::SharedPtr<IMathematicalText> Aspose::Slides::MathText::IMathematicalTextFactory::CreateMathematicalText()=0
```

### Возвращаемое значение

новый Mathematical Text

## IMathematicalTextFactory::CreateMathematicalText(char16_t) метод

Создать элемент математического текста со указанным значением

```cpp
virtual System::SharedPtr<IMathematicalText> Aspose::Slides::MathText::IMathematicalTextFactory::CreateMathematicalText(char16_t mathSymbol)=0
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| mathSymbol | char16_t | один символ, используемый в качестве текстового значения |

### Возвращаемое значение

новый Mathematical Text

## IMathematicalTextFactory::CreateMathematicalText(System::String) метод

Создать пустой элемент математического текста с указанным значением

```cpp
virtual System::SharedPtr<IMathematicalText> Aspose::Slides::MathText::IMathematicalTextFactory::CreateMathematicalText(System::String mathText)=0
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| mathText | [System::String](../../../system/string/) | текстовое значение |

### Возвращаемое значение

новый Mathematical Text

## IMathematicalTextFactory::CreateMathematicalText(System::String, System::SharedPtr\<IPortionFormat\>) метод

Создать пустой элемент математического текста с указанным значением и свойствами форматирования

```cpp
virtual System::SharedPtr<IMathematicalText> Aspose::Slides::MathText::IMathematicalTextFactory::CreateMathematicalText(System::String mathText, System::SharedPtr<IPortionFormat> portionFormat)=0
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| mathText | [System::String](../../../system/string/) | текстовое значение |
| portionFormat | [System::SharedPtr](../../../system/sharedptr/)\<[IPortionFormat](../../../aspose.slides/iportionformat/)\> | настройки формата текста |

### Возвращаемое значение

новый Mathematical Text

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Класс [IMathematicalText](../../imathematicaltext/)
* Класс [IMathematicalTextFactory](../)
* Класс [String](../../../system/string/)
* Класс [IPortionFormat](../../../aspose.slides/iportionformat/)
* Пространство имён [Aspose::Slides::MathText](../../)
* Библиотека [Aspose.Slides](../../../)