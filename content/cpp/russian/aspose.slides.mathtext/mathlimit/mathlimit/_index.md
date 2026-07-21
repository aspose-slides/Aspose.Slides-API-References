---
title: MathLimit()
second_title: Справочник API Aspose.Slides для C++
description: Инициализирует новый экземпляр класса MathLimit.
type: docs
weight: 53
url: /ru/aspose.slides.mathtext/mathlimit/mathlimit/
---
## MathLimit::MathLimit(System::SharedPtr\<IMathElement\>, System::SharedPtr\<IMathElement\>, bool) конструктор

Инициализирует новый экземпляр класса [MathLimit](../).

```cpp
Aspose::Slides::MathText::MathLimit::MathLimit(System::SharedPtr<IMathElement> baseArg, System::SharedPtr<IMathElement> limit, bool upperLimit)
```

## Замечания

Пример: 
```cpp
auto limitElement = System::MakeObject<MathLimit>(System::MakeObject<MathematicalText>(u"lim"), System::MakeObject<MathematicalText>(u"\U0001d45b→∞"), false);
```

## MathLimit::MathLimit(System::SharedPtr\<IMathElement\>, System::SharedPtr\<IMathElement\>) конструктор

Инициализирует новый экземпляр класса [MathLimit](../) с нижним пределом

```cpp
Aspose::Slides::MathText::MathLimit::MathLimit(System::SharedPtr<IMathElement> baseArg, System::SharedPtr<IMathElement> limit)
```

## Замечания

Пример: 
```cpp
auto limitElement = System::MakeObject<MathLimit>(System::MakeObject<MathematicalText>(u"lim"), System::MakeObject<MathematicalText>(u"\U0001d45b→∞"));
```

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Класс [IMathElement](../../imathelement/)
* Класс [MathLimit](../)
* Пространство имён [Aspose::Slides::MathText](../../)
* Библиотека [Aspose.Slides](../../../)