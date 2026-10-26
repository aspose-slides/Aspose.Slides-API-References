---
title: Function()
second_title: Aspose.Slides für C++ API-Referenz
description: Nimmt eine Funktion eines Arguments, wobei diese Instanz als Funktionsname verwendet wird
type: docs
weight: 53
url: /de/aspose.slides.mathtext/imathelement/function/
---
## IMathElement::Function(System::SharedPtr\<IMathElement\>) Methode

Nimmt eine Funktion eines Arguments, wobei diese Instanz als Funktionsname verwendet wird.

```cpp
virtual System::SharedPtr<IMathFunction> Aspose::Slides::MathText::IMathElement::Function(System::SharedPtr<IMathElement> functionArgument)=0
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| functionArgument | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../)\> | Ein Argument der Funktion |

### Rückgabewert

Neues Mathelement vom Typ [IMathFunction](../../imathfunction/)

## Bemerkungen



Beispiel: 
```cpp
auto functionName = System::MakeObject<MathematicalText>(u"sin");
auto functionArg = System::MakeObject<MathematicalText>(u"x");
auto func = functionName->Function(functionArg);
```

## IMathElement::Function(System::String) Methode

Nimmt eine Funktion eines Arguments, wobei diese Instanz als Funktionsname verwendet wird.

```cpp
virtual System::SharedPtr<IMathFunction> Aspose::Slides::MathText::IMathElement::Function(System::String functionArgument)=0
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| functionArgument | [System::String](../../../system/string/) | Ein Argument der Funktion |

### Rückgabewert

Neues Mathelement vom Typ [IMathFunction](../../imathfunction/)

## Bemerkungen



Beispiel: 
```cpp
auto functionName = System::MakeObject<MathematicalText>(u"sin");
auto func = functionName->Function(u"x");
```

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IMathFunction](../../imathfunction/)
* Klasse [IMathElement](../)
* Klasse [String](../../../system/string/)
* Namensraum [Aspose::Slides::MathText](../../)
* Bibliothek [Aspose.Slides](../../../)