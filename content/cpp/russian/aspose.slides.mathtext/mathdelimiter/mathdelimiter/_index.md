---
title: MathDelimiter()
second_title: Справка API Aspose.Slides для C++
description: Инициализирует MathDelimiter указанным элементом в качестве единственного базового аргумента
type: docs
weight: 144
url: /ru/aspose.slides.mathtext/mathdelimiter/mathdelimiter/
---
## MathDelimiter::MathDelimiter(System::SharedPtr\<IMathElement\>) конструктор


Инициализирует [MathDelimiter](../) указанным элементом в качестве единственного базового аргумента

```cpp
Aspose::Slides::MathText::MathDelimiter::MathDelimiter(System::SharedPtr<IMathElement> element)
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Базовый элемент, к которому применяется разделитель. Может быть null. |
## Примечания



Пример: 
```cpp
auto element = System::MakeObject<MathematicalText>(u"x");
auto delimiter = System::MakeObject<MathDelimiter>(element);
```

## Смотрите также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Класс [IMathElement](../../imathelement/)
* Класс [MathDelimiter](../)
* Пространство имен [Aspose::Slides::MathText](../../)
* Библиотека [Aspose.Slides](../../../)