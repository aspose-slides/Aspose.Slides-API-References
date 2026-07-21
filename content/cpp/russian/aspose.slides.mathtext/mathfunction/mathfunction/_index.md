---
title: MathFunction()
second_title: Aspose.Slides для C++ – справочник API
description: Создаёт новый экземпляр класса MathFunction.
type: docs
weight: 27
url: /ru/aspose.slides.mathtext/mathfunction/mathfunction/
---
## MathFunction::MathFunction(System::SharedPtr\<IMathElement\>, System::SharedPtr\<IMathElement\>) constructor

Создает новый экземпляр класса [MathFunction](../).

```cpp
Aspose::Slides::MathText::MathFunction::MathFunction(System::SharedPtr<IMathElement> funcName, System::SharedPtr<IMathElement> baseArgument)
```

## Remarks

Пример: 
```cpp
auto func = System::MakeObject<MathFunction>(System::MakeObject<MathematicalText>(u"sin"), System::MakeObject<MathematicalText>(u"x"));
```

## MathFunction::MathFunction(System::String, System::SharedPtr\<IMathElement\>) constructor

Создает новый экземпляр класса [MathFunction](../).

```cpp
Aspose::Slides::MathText::MathFunction::MathFunction(System::String funcName, System::SharedPtr<IMathElement> baseArgument)
```

## Remarks

Пример: 
```cpp
auto func = System::MakeObject<MathFunction>(u"sin", System::MakeObject<MathematicalText>(u"x"));
```

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IMathElement](../../imathelement/)
* Class [MathFunction](../)
* Class [String](../../../system/string/)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)