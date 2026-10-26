---
title: MathBox()
second_title: Справочник API Aspose.Slides для C++
description: Инициализирует MathBox указанным элементом в качестве аргумента
type: docs
weight: 144
url: /ru/aspose.slides.mathtext/mathbox/mathbox/
---
## MathBox::MathBox(System::SharedPtr\<IMathElement\>) конструктор


Инициализирует [MathBox](../) указанным элементом в качестве аргумента

```cpp
Aspose::Slides::MathText::MathBox::MathBox(System::SharedPtr<IMathElement> element)
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Базовый элемент, к которому применяется коробка. Может быть null. |
## Примечания



Пример: 
```cpp
auto box = System::MakeObject<MathBox>(System::MakeObject<MathematicalText>(u"=="));
```

## См. также

* Типовое определение [SharedPtr](../../../system/sharedptr/)
* Класс [IMathElement](../../imathelement/)
* Класс [MathBox](../)
* Пространство имён [Aspose::Slides::MathText](../../)
* Библиотека [Aspose.Slides](../../../)