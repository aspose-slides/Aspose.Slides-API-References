---
title: Radical()
second_title: Справочник API Aspose.Slides для C++
description: Указывает математический корень заданной степени из указанного аргумента.
type: docs
weight: 131
url: /ru/aspose.slides.mathtext/imathelement/radical/
---
## IMathElement::Radical(System::SharedPtr\<IMathElement\>) метод

Указывает математический корень заданной степени по указанному аргументу.

```cpp
virtual System::SharedPtr<IMathRadical> Aspose::Slides::MathText::IMathElement::Radical(System::SharedPtr<IMathElement> degree)=0
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| degree | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../)\> | Аргумент Radical |

### Возвращаемое значение

Новый экземпляр типа [IMathRadical](../../imathradical/)
## Примечания



Пример: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"2px");
auto degree = System::MakeObject<MathematicalText>(u"y");
auto radical = baseElement->Radical(degree);
```

## IMathElement::Radical(System::String) метод

Указывает математический корень заданной степени по указанному аргументу.

```cpp
virtual System::SharedPtr<IMathRadical> Aspose::Slides::MathText::IMathElement::Radical(System::String degree)=0
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| degree | [System::String](../../../system/string/) | Аргумент Radical |

### Возвращаемое значение

Новый экземпляр типа [IMathRadical](../../imathradical/)
## Примечания



Пример: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"2px");
auto radical = baseElement->Radical(u"3");
```

## См. также

* Типовое определение [SharedPtr](../../../system/sharedptr/)
* Класс [IMathRadical](../../imathradical/)
* Класс [IMathElement](../)
* Класс [String](../../../system/string/)
* Пространство имён [Aspose::Slides::MathText](../../)
* Библиотека [Aspose.Slides](../../../)