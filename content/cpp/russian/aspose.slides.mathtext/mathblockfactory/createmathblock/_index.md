---
title: CreateMathBlock()
second_title: Aspose.Slides для C++ справочник API
description: Создать математический блок
type: docs
weight: 1
url: /ru/aspose.slides.mathtext/mathblockfactory/createmathblock/
---
## MathBlockFactory::CreateMathBlock() метод

Создать математический блок

```cpp
System::SharedPtr<IMathBlock> Aspose::Slides::MathText::MathBlockFactory::CreateMathBlock() override
```

### Возвращаемое значение

новый математический блок

## MathBlockFactory::CreateMathBlock(System::SharedPtr\<IMathElement\>) метод

Создать математический блок и разместить в нём элемент

```cpp
System::SharedPtr<IMathBlock> Aspose::Slides::MathText::MathBlockFactory::CreateMathBlock(System::SharedPtr<IMathElement> mathElement) override
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| mathElement | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Элемент математики |

### Возвращаемое значение

новый математический блок

## MathBlockFactory::CreateMathBlock(System::SharedPtr\<IMathElementCollection\>) метод

Создать математический блок и разместить в нём элементы

```cpp
System::SharedPtr<IMathBlock> Aspose::Slides::MathText::MathBlockFactory::CreateMathBlock(System::SharedPtr<IMathElementCollection> mathElements) override
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| mathElements | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElementCollection](../../imathelementcollection/)\> | Элементы математики |

### Возвращаемое значение

новый математический блок

## См. также

* Тип [SharedPtr](../../../system/sharedptr/)
* Класс [IMathBlock](../../imathblock/)
* Класс [MathBlockFactory](../)
* Класс [IMathElement](../../imathelement/)
* Класс [IMathElementCollection](../../imathelementcollection/)
* Пространство имён [Aspose::Slides::MathText](../../)
* Библиотека [Aspose.Slides](../../../)