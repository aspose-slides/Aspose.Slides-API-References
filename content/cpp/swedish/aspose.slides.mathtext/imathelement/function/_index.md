---
title: Function()
second_title: Aspose.Slides för C++ API-referens
description: Tar en funktion av ett argument där denna instans används som funktionsnamn
type: docs
weight: 53
url: /sv/aspose.slides.mathtext/imathelement/function/
---
## IMathElement::Function(System::SharedPtr\<IMathElement\>) metod

Tar en funktion av ett argument där den här instansen används som funktionsnamn

```cpp
virtual System::SharedPtr<IMathFunction> Aspose::Slides::MathText::IMathElement::Function(System::SharedPtr<IMathElement> functionArgument)=0
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| functionArgument | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../)\> | Ett argument till funktionen |

### Returvärde

Nytt matematiskt element av typen [IMathFunction](../../imathfunction/)
## Anmärkningar



Exempel: 
```cpp
auto functionName = System::MakeObject<MathematicalText>(u"sin");
auto functionArg = System::MakeObject<MathematicalText>(u"x");
auto func = functionName->Function(functionArg);
```

## IMathElement::Function(System::String) metod

Tar en funktion av ett argument där den här instansen används som funktionsnamn

```cpp
virtual System::SharedPtr<IMathFunction> Aspose::Slides::MathText::IMathElement::Function(System::String functionArgument)=0
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

## Se också

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [IMathFunction](../../imathfunction/)
* Klass [IMathElement](../)
* Klass [String](../../../system/string/)
* Namnrymd [Aspose::Slides::MathText](../../)
* Bibliotek [Aspose.Slides](../../../)