---
title: ToBorderBox()
second_title: Aspose.Slides для C++ Справочник API
description: Размещает этот элемент в border-box
type: docs
weight: 261
url: /ru/aspose.slides.mathtext/imathelement/toborderbox/
---
## IMathElement::ToBorderBox() метод

Размещает этот элемент в border-box

```cpp
virtual System::SharedPtr<IMathBorderBox> Aspose::Slides::MathText::IMathElement::ToBorderBox()=0
```


### Возвращаемое значение

Border-box с размещённым внутри этим элементом
## Замечания



Пример: 
```cpp
auto borderBox = System::MakeObject<MathematicalText>(u"x+y+z")->ToBorderBox();
```

## IMathElement::ToBorderBox(bool, bool, bool, bool, bool, bool, bool, bool) метод


Размещает этот элемент в border-box

```cpp
virtual System::SharedPtr<IMathBorderBox> Aspose::Slides::MathText::IMathElement::ToBorderBox(bool hideTop, bool hideBottom, bool hideLeft, bool hideRight, bool strikethroughHorizontal, bool strikethroughVertical, bool strikethroughBottomLeftToTopRight, bool strikethroughTopLeftToBottomRight)=0
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| hideTop | **bool** | Скрыть верхний край |
| hideBottom | **bool** | Скрыть нижний край |
| hideLeft | **bool** | Скрыть левый край |
| hideRight | **bool** | Скрыть правый край |
| strikethroughHorizontal | **bool** | Горизонтальное перечёркивание border-box |
| strikethroughVertical | **bool** | Вертикальное перечёркивание border-box |
| strikethroughBottomLeftToTopRight | **bool** | Перечёркивание border-box от нижнего левого к верхнему правому |
| strikethroughTopLeftToBottomRight | **bool** | Перечёркивание border-box от верхнего левого к нижнему правому |

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
* Класс [IMathElement](../)
* Пространство имен [Aspose::Slides::MathText](../../)
* Библиотека [Aspose.Slides](../../../)