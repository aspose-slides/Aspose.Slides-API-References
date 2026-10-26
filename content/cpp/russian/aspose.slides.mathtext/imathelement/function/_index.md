---
title: Function()
second_title: Справочник API Aspose.Slides для C++
description: Принимает функцию аргумента, используя этот экземпляр в качестве имени функции
type: docs
weight: 53
url: /ru/aspose.slides.mathtext/imathelement/function/
---
## IMathElement::Function(System::SharedPtr\<IMathElement\>) метод


Принимает функцию аргумента, используя этот экземпляр в качестве имени функции

```cpp
virtual System::SharedPtr<IMathFunction> Aspose::Slides::MathText::IMathElement::Function(System::SharedPtr<IMathElement> functionArgument)=0
```


### Параметры

| Parameter | Type | Description |
| --- | --- | --- |
| functionArgument | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../)\> | Аргумент функции |

### Возвращаемое значение

Новый элемент математики типа [IMathFunction](../../imathfunction/)
## Замечания



Пример: 
```cpp
auto functionName = System::MakeObject<MathematicalText>(u"sin");
auto functionArg = System::MakeObject<MathematicalText>(u"x");
auto func = functionName->Function(functionArg);
```

## IMathElement::Function(System::String) метод


Принимает функцию аргумента, используя этот экземпляр в качестве имени функции

```cpp
virtual System::SharedPtr<IMathFunction> Aspose::Slides::MathText::IMathElement::Function(System::String functionArgument)=0
```


### Параметры

| Parameter | Type | Description |
| --- | --- | --- |
| functionArgument | [System::String](../../../system/string/) | Аргумент функции |

### Возвращаемое значение

Новый элемент математики типа [IMathFunction](../../imathfunction/)
## Замечания



Пример: 
```cpp
auto functionName = System::MakeObject<MathematicalText>(u"sin");
auto func = functionName->Function(u"x");
```

## См. также

* Тип [SharedPtr](../../../system/sharedptr/)
* Класс [IMathFunction](../../imathfunction/)
* Класс [IMathElement](../)
* Класс [String](../../../system/string/)
* Пространство имён [Aspose::Slides::MathText](../../)
* Библиотека [Aspose.Slides](../../../)