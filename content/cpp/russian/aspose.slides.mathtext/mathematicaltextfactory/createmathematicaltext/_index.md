---
title: CreateMathematicalText()
second_title: Справочник API Aspose.Slides для C++
description: Создать пустой элемент математического текста
type: docs
weight: 1
url: /ru/aspose.slides.mathtext/mathematicaltextfactory/createmathematicaltext/
---
## MathematicalTextFactory::CreateMathematicalText() метод


Создать пустой элемент математического текста

```cpp
System::SharedPtr<IMathematicalText> Aspose::Slides::MathText::MathematicalTextFactory::CreateMathematicalText() override
```


### Возвращаемое значение

новый Mathematical Text

## MathematicalTextFactory::CreateMathematicalText(char16_t) метод


Создать элемент математического текста со указанным значением

```cpp
System::SharedPtr<IMathematicalText> Aspose::Slides::MathText::MathematicalTextFactory::CreateMathematicalText(char16_t mathSymbol) override
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| mathSymbol | char16_t | один символ, используемый как значение текста |

### Возвращаемое значение

новый Mathematical Text

## MathematicalTextFactory::CreateMathematicalText(System::String) метод


Создать пустой элемент математического текста со указанным значением

```cpp
System::SharedPtr<IMathematicalText> Aspose::Slides::MathText::MathematicalTextFactory::CreateMathematicalText(System::String mathText) override
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| mathText | [System::String](../../../system/string/) | значение текста |

### Возвращаемое значение

новый Mathematical Text

## MathematicalTextFactory::CreateMathematicalText(System::String, System::SharedPtr\<IPortionFormat\>) метод


Создать пустой элемент математического текста с указанным значением и свойствами форматирования

```cpp
System::SharedPtr<IMathematicalText> Aspose::Slides::MathText::MathematicalTextFactory::CreateMathematicalText(System::String mathText, System::SharedPtr<IPortionFormat> portionFormat) override
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| mathText | [System::String](../../../system/string/) | значение текста |
| portionFormat | [System::SharedPtr](../../../system/sharedptr/)\<[IPortionFormat](../../../aspose.slides/iportionformat/)\> | настройки формата текста |

### Возвращаемое значение

новый Mathematical Text

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Класс [IMathematicalText](../../imathematicaltext/)
* Класс [MathematicalTextFactory](../)
* Класс [String](../../../system/string/)
* Класс [IPortionFormat](../../../aspose.slides/iportionformat/)
* Пространство имён [Aspose::Slides::MathText](../../)
* Библиотека [Aspose.Slides](../../../)