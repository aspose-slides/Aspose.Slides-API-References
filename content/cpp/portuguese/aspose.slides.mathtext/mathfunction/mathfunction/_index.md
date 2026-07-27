---
title: MathFunction()
second_title: Referência da API Aspose.Slides para C++
description: Inicializa uma nova instância da classe MathFunction.
type: docs
weight: 27
url: /pt/aspose.slides.mathtext/mathfunction/mathfunction/
---
## MathFunction::MathFunction(System::SharedPtr\<IMathElement\>, System::SharedPtr\<IMathElement\>) construtor


Inicializa uma nova instância da classe [MathFunction](../).

```cpp
Aspose::Slides::MathText::MathFunction::MathFunction(System::SharedPtr<IMathElement> funcName, System::SharedPtr<IMathElement> baseArgument)
```

## Observações


Exemplo: 
```cpp
auto func = System::MakeObject<MathFunction>(System::MakeObject<MathematicalText>(u"sin"), System::MakeObject<MathematicalText>(u"x"));
```

## MathFunction::MathFunction(System::String, System::SharedPtr\<IMathElement\>) construtor


Inicializa uma nova instância da classe [MathFunction](../).

```cpp
Aspose::Slides::MathText::MathFunction::MathFunction(System::String funcName, System::SharedPtr<IMathElement> baseArgument)
```

## Observações


Exemplo: 
```cpp
auto func = System::MakeObject<MathFunction>(u"sin", System::MakeObject<MathematicalText>(u"x"));
```

## Veja Também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IMathElement](../../imathelement/)
* Classe [MathFunction](../)
* Classe [String](../../../system/string/)
* Namespace [Aspose::Slides::MathText](../../)
* Biblioteca [Aspose.Slides](../../../)