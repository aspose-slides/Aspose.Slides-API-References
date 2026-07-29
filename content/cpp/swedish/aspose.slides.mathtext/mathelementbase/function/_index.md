---
title: Function()
second_title: Aspose.Slides för C++ API-referens
description: Tar en funktion av ett argument med den här instansen som funktionsnamn
type: docs
weight: 40
url: /sv/aspose.slides.mathtext/mathelementbase/function/
---
## MathElementBase::Function(System::SharedPtr\<IMathElement\>) metod


Tar en funktion av ett argument med den här instansen som funktionsnamn

```cpp
System::SharedPtr<IMathFunction> Aspose::Slides::MathText::MathElementBase::Function(System::SharedPtr<IMathElement> functionArgument) override
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| functionArgument | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Ett argument till funktionen |

### Returvärde

Nytt matematiskt element av typen [IMathFunction](../../imathfunction/)
## Anmärkningar



Exempel: 
```cpp
auto functionName = System::MakeObject<MathematicalText>(u"sin");
auto functionArg = System::MakeObject<MathematicalText>(u"x");
auto func = functionName->Function(functionArg);
```

## MathElementBase::Function(System::String) metod


Tar en funktion av ett argument med den här instansen som funktionsnamn

```cpp
System::SharedPtr<IMathFunction> Aspose::Slides::MathText::MathElementBase::Function(System::String functionArgument) override
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| functionArgument | [System::String](../../../system/string/) | Ett argument till funktionen |

### Returvärde

Nytt matematiskt element av typen [IMathFunction](../../imathfunction/)
## Anmärkningar



Exempel: 
```cpp
auto functionName = System::MakeObject<MathematicalText>(u"sin");
auto func = functionName->Function(u"x");
```

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [IMathFunction](../../imathfunction/)
* Klass [IMathElement](../../imathelement/)
* Klass [MathElementBase](../)
* Klass [String](../../../system/string/)
* Namnrymd [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)