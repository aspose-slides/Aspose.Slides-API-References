---
title: Function()
second_title: Aspose.Slides для C++ справочник API
description: Принимает функцию аргумента, используя данный экземпляр в качестве имени функции
type: docs
weight: 40
url: /ru/aspose.slides.mathtext/mathelementbase/function/
---
## MathElementBase::Function(System::SharedPtr\<IMathElement\>) метод

Принимает функцию аргумента, используя данный экземпляр в качестве имени функции

```cpp
System::SharedPtr<IMathFunction> Aspose::Slides::MathText::MathElementBase::Function(System::SharedPtr<IMathElement> functionArgument) override
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| functionArgument | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Аргумент функции |

### Возвращаемое значение

Новый математический элемент типа [IMathFunction](../../imathfunction/)

## Примечания

Пример: 
```cpp
auto functionName = System::MakeObject<MathematicalText>(u"sin");
auto functionArg = System::MakeObject<MathematicalText>(u"x");
auto func = functionName->Function(functionArg);
```

## MathElementBase::Function(System::String) метод

Принимает функцию аргумента, используя данный экземпляр в качестве имени функции

```cpp
System::SharedPtr<IMathFunction> Aspose::Slides::MathText::MathElementBase::Function(System::String functionArgument) override
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| functionArgument | [System::String](../../../system/string/) | Аргумент функции |

### Возвращаемое значение

Новый математический элемент типа [IMathFunction](../../imathfunction/)

## Примечания

Пример: 
```cpp
auto functionName = System::MakeObject<MathematicalText>(u"sin");
auto func = functionName->Function(u"x");
```

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Класс [IMathFunction](../../imathfunction/)
* Класс [IMathElement](../../imathelement/)
* Класс [MathElementBase](../)
* Класс [String](../../../system/string/)
* Пространство имён [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)