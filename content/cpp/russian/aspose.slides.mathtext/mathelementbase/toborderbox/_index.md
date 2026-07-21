---
title: ToBorderBox()
second_title: Справочник API Aspose.Slides для C++
description: Помещает этот элемент в border-box
type: docs
weight: 248
url: /ru/aspose.slides.mathtext/mathelementbase/toborderbox/
---
## MathElementBase::ToBorderBox() метод

Помещает этот элемент в border-box

```cpp
System::SharedPtr<IMathBorderBox> Aspose::Slides::MathText::MathElementBase::ToBorderBox() override
```

### Возвращаемое значение

Border-box с размещённым внутри этим элементом
## Замечания

Пример: 
```cpp
auto borderBox = System::MakeObject<MathematicalText>(u"x+y+z")->ToBorderBox();
```

## MathElementBase::ToBorderBox(bool, bool, bool, bool, bool, bool, bool, bool) метод

Помещает этот элемент в border-box

```cpp
System::SharedPtr<IMathBorderBox> Aspose::Slides::MathText::MathElementBase::ToBorderBox(bool hideTop, bool hideBottom, bool hideLeft, bool hideRight, bool strikethroughHorizontal, bool strikethroughVertical, bool strikethroughBottomLeftToTopRight, bool strikethroughTopLeftToBottomRight) override
```

### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| hideTop | **bool** | Скрыть верхний край |
| hideBottom | **bool** | Скрыть нижний край |
| hideLeft | **bool** | Скрыть левый край |
| hideRight | **bool** | Скрыть правый край |
| strikethroughHorizontal | **bool** | Горизонтальная линия пересечения border-box |
| strikethroughVertical | **bool** | Вертикальная линия пересечения border-box |
| strikethroughBottomLeftToTopRight | **bool** | Линия пересечения border-box из нижнего левого в верхний правый |
| strikethroughTopLeftToBottomRight | **bool** | Линия пересечения border-box из верхнего левого в нижний правый |

### Возвращаемое значение

Border-box с размещённым внутри этим элементом
## Замечания

Пример: 
```cpp
auto borderBox = System::MakeObject<MathematicalText>(u"x+y+z")->ToBorderBox(false, false, true, true, false, false, false, false);
```

## См. также

* Тип [SharedPtr](../../../system/sharedptr/)
* Класс [IMathBorderBox](../../imathborderbox/)
* Класс [MathElementBase](../)
* Пространство имен [Aspose::Slides::MathText](../../)
* Библиотека [Aspose.Slides](../../../)