---
title: CreateMathBorderBox()
second_title: Aspose.Slides для C++ - справочник API
description: Создать математическую рамку, применяя к элементу
type: docs
weight: 1
url: /ru/aspose.slides.mathtext/mathborderboxfactory/createmathborderbox/
---
## MathBorderBoxFactory::CreateMathBorderBox(System::SharedPtr\<IMathElement\>) метод


Создать математическую рамку, применяя к элементу

```cpp
System::SharedPtr<IMathBorderBox> Aspose::Slides::MathText::MathBorderBoxFactory::CreateMathBorderBox(System::SharedPtr<IMathElement> element) override
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | математический элемент, к которому применяется рамка |

### Возвращаемое значение

новый элемент рамки

## MathBorderBoxFactory::CreateMathBorderBox(System::SharedPtr\<IMathElement\>, bool, bool, bool, bool, bool, bool, bool, bool) метод


Создать математическую рамку, применяя к элементу

```cpp
System::SharedPtr<IMathBorderBox> Aspose::Slides::MathText::MathBorderBoxFactory::CreateMathBorderBox(System::SharedPtr<IMathElement> element, bool hideTop, bool hideBottom, bool hideLeft, bool hideRight, bool strikethroughHorizontal, bool strikethroughVertical, bool strikethroughBottomLeftToTopRight, bool strikethroughTopLeftToBottomRight) override
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | математический элемент, к которому применяется рамка |
| hideTop | **bool** | Скрыть верхний край |
| hideBottom | **bool** | Скрыть нижний край |
| hideLeft | **bool** | Скрыть левый край |
| hideRight | **bool** | Скрыть правый край |
| strikethroughHorizontal | **bool** | Зачёркивание рамки по горизонтали |
| strikethroughVertical | **bool** | Зачёркивание рамки по вертикали |
| strikethroughBottomLeftToTopRight | **bool** | Зачёркивание рамки снизу-слева вверх-справа |
| strikethroughTopLeftToBottomRight | **bool** | Зачёркивание рамки сверху-слева вниз-справа |

### Возвращаемое значение

новый элемент рамки

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Класс [IMathBorderBox](../../imathborderbox/)
* Класс [IMathElement](../../imathelement/)
* Класс [MathBorderBoxFactory](../)
* Пространство имён [Aspose::Slides::MathText](../../)
* Библиотека [Aspose.Slides](../../../)