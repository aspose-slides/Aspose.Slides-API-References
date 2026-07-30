---
title: MathFunction()
second_title: Riferimento API di Aspose.Slides per C++
description: Inizializza una nuova istanza della classe MathFunction.
type: docs
weight: 27
url: /it/aspose.slides.mathtext/mathfunction/mathfunction/
---
## MathFunction::MathFunction(System::SharedPtr\<IMathElement\>, System::SharedPtr\<IMathElement\>) constructor

Inizializza una nuova istanza della classe [MathFunction](../).

```cpp
Aspose::Slides::MathText::MathFunction::MathFunction(System::SharedPtr<IMathElement> funcName, System::SharedPtr<IMathElement> baseArgument)
```

## Osservazioni

Esempio: 
```cpp
auto func = System::MakeObject<MathFunction>(System::MakeObject<MathematicalText>(u"sin"), System::MakeObject<MathematicalText>(u"x"));
```

## MathFunction::MathFunction(System::String, System::SharedPtr\<IMathElement\>) constructor

Inizializza una nuova istanza della classe [MathFunction](../).

```cpp
Aspose::Slides::MathText::MathFunction::MathFunction(System::String funcName, System::SharedPtr<IMathElement> baseArgument)
```

## Osservazioni

Esempio: 
```cpp
auto func = System::MakeObject<MathFunction>(u"sin", System::MakeObject<MathematicalText>(u"x"));
```

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IMathElement](../../imathelement/)
* Classe [MathFunction](../)
* Classe [String](../../../system/string/)
* Namespace [Aspose::Slides::MathText](../../)
* Libreria [Aspose.Slides](../../../)