---
title: Radical()
second_title: Aspose.Slides для C++ справочник API
description: Указывает математический корень заданной степени от указанного аргумента.
type: docs
weight: 118
url: /ru/aspose.slides.mathtext/mathelementbase/radical/
---
## MathElementBase::Radical(System::SharedPtr\<IMathElement\>) метод

Указывает математический корень заданной степени от указанного аргумента.

```cpp
System::SharedPtr<IMathRadical> Aspose::Slides::MathText::MathElementBase::Radical(System::SharedPtr<IMathElement> degree) override
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| degree | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Аргумент функции Radical |

### Возвращаемое значение

Новый экземпляр типа [IMathRadical](../../imathradical/)

## Примечания

Пример: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"2px");
auto degree = System::MakeObject<MathematicalText>(u"y");
auto radical = baseElement->Radical(degree);
```

## MathElementBase::Radical(System::String) метод

Указывает математический корень заданной степени от указанного аргумента.

```cpp
System::SharedPtr<IMathRadical> Aspose::Slides::MathText::MathElementBase::Radical(System::String degree) override
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| degree | [System::String](../../../system/string/) | Аргумент функции Radical |

### Возвращаемое значение

Новый экземпляр типа [IMathRadical](../../imathradical/)

## Примечания

Пример: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"2px");
auto radical = baseElement->Radical(u"3");
```

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Класс [IMathRadical](../../imathradical/)
* Класс [IMathElement](../../imathelement/)
* Класс [MathElementBase](../)
* Класс [String](../../../system/string/)
* Пространство имён [Aspose::Slides::MathText](../../)
* Библиотека [Aspose.Slides](../../../)