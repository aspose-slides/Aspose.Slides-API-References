---
title: Function()
second_title: Aspose.Slides für C++ API-Referenz
description: Nimmt eine Funktion eines Arguments, wobei diese Instanz als Funktionsname verwendet wird
type: docs
weight: 40
url: /de/aspose.slides.mathtext/mathelementbase/function/
---
## MathElementBase::Function(System::SharedPtr\<IMathElement\>) Methode


Nimmt eine Funktion eines Arguments, wobei diese Instanz als Funktionsname verwendet wird

```cpp
System::SharedPtr<IMathFunction> Aspose::Slides::MathText::MathElementBase::Function(System::SharedPtr<IMathElement> functionArgument) override
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| functionArgument | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Ein Argument der Funktion |

### Rückgabewert

Neues mathematisches Element vom Typ [IMathFunction](../../imathfunction/)
## Bemerkungen



Beispiel: 
```cpp
auto functionName = System::MakeObject<MathematicalText>(u"sin");
auto functionArg = System::MakeObject<MathematicalText>(u"x");
auto func = functionName->Function(functionArg);
```

## MathElementBase::Function(System::String) Methode


Nimmt eine Funktion eines Arguments, wobei diese Instanz als Funktionsname verwendet wird

```cpp
System::SharedPtr<IMathFunction> Aspose::Slides::MathText::MathElementBase::Function(System::String functionArgument) override
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| functionArgument | [System::String](../../../system/string/) | Ein Argument der Funktion |

### Rückgabewert

Neues mathematisches Element vom Typ [IMathFunction](../../imathfunction/)
## Bemerkungen



Beispiel: 
```cpp
auto functionName = System::MakeObject<MathematicalText>(u"sin");
auto func = functionName->Function(u"x");
```

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IMathFunction](../../imathfunction/)
* Klasse [IMathElement](../../imathelement/)
* Klasse [MathElementBase](../)
* Klasse [String](../../../system/string/)
* Namensraum [Aspose::Slides::MathText](../../)
* Bibliothek [Aspose.Slides](../../../)