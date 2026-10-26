---
title: CreateMathBlock()
second_title: Aspose.Slides для C++ справочник API
description: Создать блок формул
type: docs
weight: 1
url: /ru/aspose.slides.mathtext/imathblockfactory/createmathblock/
---
## IMathBlockFactory::CreateMathBlock() метод

Создать блок формул

```cpp
virtual System::SharedPtr<IMathBlock> Aspose::Slides::MathText::IMathBlockFactory::CreateMathBlock()=0
```

### Возвращаемое значение

новый блок формул

## IMathBlockFactory::CreateMathBlock(System::SharedPtr\<IMathElement\>) метод

Создать блок формул и разместить в нём элемент

```cpp
virtual System::SharedPtr<IMathBlock> Aspose::Slides::MathText::IMathBlockFactory::CreateMathBlock(System::SharedPtr<IMathElement> mathElement)=0
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| mathElement | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Элемент формулы |

### Возвращаемое значение

новый блок формул

## IMathBlockFactory::CreateMathBlock(System::SharedPtr\<IMathElementCollection\>) метод

Создать блок формул и разместить в нём элементы

```cpp
virtual System::SharedPtr<IMathBlock> Aspose::Slides::MathText::IMathBlockFactory::CreateMathBlock(System::SharedPtr<IMathElementCollection> mathElements)=0
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| mathElements | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElementCollection](../../imathelementcollection/)\> | элементы формулы |

### Возвращаемое значение

новый блок формул

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Класс [IMathBlock](../../imathblock/)
* Класс [IMathBlockFactory](../)
* Класс [IMathElement](../../imathelement/)
* Класс [IMathElementCollection](../../imathelementcollection/)
* Пространство имён [Aspose::Slides::MathText](../../)
* Библиотека [Aspose.Slides](../../../)