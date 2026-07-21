---
title: MathBorderBox()
second_title: Aspose.Slides для C++: справочник API
description: Создает элемент MathBorderBox с прямоугольной рамкой
type: docs
weight: 222
url: /ru/aspose.slides.mathtext/mathborderbox/mathborderbox/
---
## MathBorderBox::MathBorderBox(System::SharedPtr\<IMathElement\>) конструктор


Создает элемент [MathBorderBox](../) с прямоугольной рамкой

```cpp
Aspose::Slides::MathText::MathBorderBox::MathBorderBox(System::SharedPtr<IMathElement> element)
```


### Arguments

| Параметр | Тип | Описание |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Базовый элемент, к которому применяется коробка-рамка. Может быть null. |
## Примечания



Пример: 
```cpp
auto borderBox = System::MakeObject<MathBorderBox>(System::MakeObject<MathematicalText>(u"x"));
```

## MathBorderBox::MathBorderBox(System::SharedPtr\<IMathElement\>, bool, bool, bool, bool, bool, bool, bool, bool) конструктор


Создает элемент [MathBorderBox](../)

```cpp
Aspose::Slides::MathText::MathBorderBox::MathBorderBox(System::SharedPtr<IMathElement> element, bool hideTop, bool hideBottom, bool hideLeft, bool hideRight, bool strikethroughHorizontal, bool strikethroughVertical, bool strikethroughBottomLeftToTopRight, bool strikethroughTopLeftToBottomRight)
```


### Arguments

| Параметр | Тип | Описание |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Базовый элемент, к которому применяется коробка-рамка |
| hideTop | **bool** | Скрыть верхний край |
| hideBottom | **bool** | Скрыть нижний край |
| hideLeft | **bool** | Скрыть левый край |
| hideRight | **bool** | Скрыть правый край |
| strikethroughHorizontal | **bool** | Перечеркнуть горизонтально |
| strikethroughVertical | **bool** | Перечеркнуть вертикально |
| strikethroughBottomLeftToTopRight | **bool** | Перечеркнуть снизу слева вверх направо |
| strikethroughTopLeftToBottomRight | **bool** | Перечеркнуть сверху слева вниз направо |
## Примечания



Пример: 
```cpp
auto borderBox = System::MakeObject<MathBorderBox>(System::MakeObject<MathematicalText>(u"x"), true, true, true, false, true, true, true, true);
```

## См. также

* Типовое определение [SharedPtr](../../../system/sharedptr/)
* Класс [IMathElement](../../imathelement/)
* Класс [MathBorderBox](../)
* Пространство имён [Aspose::Slides::MathText](../../)
* Библиотека [Aspose.Slides](../../../)