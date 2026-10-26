---
title: Function()
second_title: Aspose.Slides for C++ API Referenciája
description: Egy argumentummal rendelkező függvényt vesz fel, az aktuális példányt használva függvénynévként
type: docs
weight: 40
url: /hu/aspose.slides.mathtext/mathelementbase/function/
---
## MathElementBase::Function(System::SharedPtr\<IMathElement\>) metódus


Függvényt vesz fel egy argumentummal, amely az aktuális példányt használja függvénynévként

```cpp
System::SharedPtr<IMathFunction> Aspose::Slides::MathText::MathElementBase::Function(System::SharedPtr<IMathElement> functionArgument) override
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| functionArgument | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | A függvény argumentuma |

### Visszatérési érték

Új matematikai elem típusa [IMathFunction](../../imathfunction/)
## Megjegyzések



Példa: 
```cpp
auto functionName = System::MakeObject<MathematicalText>(u"sin");
auto functionArg = System::MakeObject<MathematicalText>(u"x");
auto func = functionName->Function(functionArg);
```

## MathElementBase::Function(System::String) metódus


Függvényt vesz fel egy argumentummal, amely az aktuális példányt használja függvénynévként

```cpp
System::SharedPtr<IMathFunction> Aspose::Slides::MathText::MathElementBase::Function(System::String functionArgument) override
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| functionArgument | [System::String](../../../system/string/) | A függvény argumentuma |

### Visszatérési érték

Új matematikai elem típusa [IMathFunction](../../imathfunction/)
## Megjegyzések



Példa: 
```cpp
auto functionName = System::MakeObject<MathematicalText>(u"sin");
auto func = functionName->Function(u"x");
```

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [IMathFunction](../../imathfunction/)
* Osztály [IMathElement](../../imathelement/)
* Osztály [MathElementBase](../)
* Osztály [String](../../../system/string/)
* Névtér [Aspose::Slides::MathText](../../)
* Könyvtár [Aspose.Slides](../../../)