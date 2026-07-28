---
title: Function()
second_title: Aspose.Slides C++ API referencia
description: Egy argumentummal rendelkező függvényt vesz fel, a jelen példányt használva függvénynévként
type: docs
weight: 53
url: /hu/aspose.slides.mathtext/imathelement/function/
---
## IMathElement::Function(System::SharedPtr\<IMathElement\>) metódus

Egy argumentummal rendelkező függvényt vesz fel, a jelen példányt használva függvénynévként

```cpp
virtual System::SharedPtr<IMathFunction> Aspose::Slides::MathText::IMathElement::Function(System::SharedPtr<IMathElement> functionArgument)=0
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| functionArgument | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../)\> | A függvény argumentuma |

### Visszatérési érték

Új matematikai elem a(z) [IMathFunction](../../imathfunction/) típusú

## Megjegyzések

Példa:
```cpp
auto functionName = System::MakeObject<MathematicalText>(u"sin");
auto functionArg = System::MakeObject<MathematicalText>(u"x");
auto func = functionName->Function(functionArg);
```

## IMathElement::Function(System::String) metódus

Egy argumentummal rendelkező függvényt vesz fel, a jelen példányt használva függvénynévként

```cpp
virtual System::SharedPtr<IMathFunction> Aspose::Slides::MathText::IMathElement::Function(System::String functionArgument)=0
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| functionArgument | [System::String](../../../system/string/) | A függvény argumentuma |

### Visszatérési érték

Új matematikai elem a(z) [IMathFunction](../../imathfunction/) típusú

## Megjegyzések

Példa:
```cpp
auto functionName = System::MakeObject<MathematicalText>(u"sin");
auto func = functionName->Function(u"x");
```

## Lásd még

* Típusdefiníció [SharedPtr](../../../system/sharedptr/)
* Osztály [IMathFunction](../../imathfunction/)
* Osztály [IMathElement](../)
* Osztály [String](../../../system/string/)
* Névtere [Aspose::Slides::MathText](../../)
* Könyvtár [Aspose.Slides](../../../)