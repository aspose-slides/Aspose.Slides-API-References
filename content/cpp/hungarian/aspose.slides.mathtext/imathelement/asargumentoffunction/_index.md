---
title: AsArgumentOfFunction()
second_title: Aspose.Slides C++ API referencia
description: Megadott függvényt vesz fel, amely ezt a példányt argumentumként használja
type: docs
weight: 66
url: /hu/aspose.slides.mathtext/imathelement/asargumentoffunction/
---
## IMathElement::AsArgumentOfFunction(System::SharedPtr\<IMathElement\>) method

Megadott függvényt vesz fel, amely ezt a példányt argumentumként használja

```cpp
virtual System::SharedPtr<IMathFunction> Aspose::Slides::MathText::IMathElement::AsArgumentOfFunction(System::SharedPtr<IMathElement> functionName)=0
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| functionName | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../)\> | Függvény neve |

### Visszatérési érték

Új matematikai elem típusa [IMathFunction](../../imathfunction/)
## Megjegyzések

Példa: 
```cpp
auto functionName = System::MakeObject<MathematicalText>(u"sin");
auto functionArg = System::MakeObject<MathematicalText>(u"x");
auto func = functionArg->AsArgumentOfFunction(functionName);
```

## IMathElement::AsArgumentOfFunction(System::String) method

Megadott függvényt vesz fel, amely ezt a példányt argumentumként használja

```cpp
virtual System::SharedPtr<IMathFunction> Aspose::Slides::MathText::IMathElement::AsArgumentOfFunction(System::String functionName)=0
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| functionName | [System::String](../../../system/string/) | Függvény neve |

### Visszatérési érték

Új matematikai elem típusa [IMathFunction](../../imathfunction/)
## Megjegyzések

Példa: 
```cpp
auto functionArg = System::MakeObject<MathematicalText>(u"x");
auto func = functionArg->AsArgumentOfFunction(u"cos");
```

## IMathElement::AsArgumentOfFunction(MathFunctionsOfOneArgument) method

Megadott függvényt vesz fel, amely ezt a példányt argumentumként használja

```cpp
virtual System::SharedPtr<IMathFunction> Aspose::Slides::MathText::IMathElement::AsArgumentOfFunction(MathFunctionsOfOneArgument functionType)=0
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| functionType | [MathFunctionsOfOneArgument](../../mathfunctionsofoneargument/) | A gyakori egy argumentumú függvények egyike |

### Visszatérési érték

Új matematikai elem típusa [IMathFunction](../../imathfunction/)
## Megjegyzések

Példa: 
```cpp
auto functionArg = System::MakeObject<MathematicalText>(u"x");
auto func = functionArg->AsArgumentOfFunction(MathFunctionsOfOneArgument::ArcSin);
```

## IMathElement::AsArgumentOfFunction(MathFunctionsOfTwoArguments, System::SharedPtr\<IMathElement\>) method

Megadott függvényt vesz fel, amely ezt a példányt argumentumként használja, valamint egy meghatározott további argumentumot

```cpp
virtual System::SharedPtr<IMathFunction> Aspose::Slides::MathText::IMathElement::AsArgumentOfFunction(MathFunctionsOfTwoArguments functionType, System::SharedPtr<IMathElement> additionalArgument)=0
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| functionType | [MathFunctionsOfTwoArguments](../../mathfunctionsoftwoarguments/) | A két argumentumú gyakori függvények egyike: Log, Lim, Min, Max |
| additionalArgument | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../)\> | A függvény típusától függő további argumentum |

### Visszatérési érték

Új matematikai elem típusa [IMathFunction](../../imathfunction/)
## Megjegyzések

Példa: 
```cpp
auto functionArg = System::MakeObject<MathematicalText>(u"x");
auto logarithmBase = System::MakeObject<MathematicalText>(u"5");
auto func = functionArg->AsArgumentOfFunction(MathFunctionsOfTwoArguments::Log, logarithmBase);
// Visszaadja az 'x' logaritmusát a '5' alapra
```

## IMathElement::AsArgumentOfFunction(MathFunctionsOfTwoArguments, System::String) method

Megadott függvényt vesz fel, amely ezt a példányt argumentumként használja, valamint egy meghatározott további argumentumot

```cpp
virtual System::SharedPtr<IMathFunction> Aspose::Slides::MathText::IMathElement::AsArgumentOfFunction(MathFunctionsOfTwoArguments functionType, System::String additionalArgument)=0
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| functionType | [MathFunctionsOfTwoArguments](../../mathfunctionsoftwoarguments/) | A két argumentumú gyakori függvények egyike: Log, Lim, Min, Max |
| additionalArgument | [System::String](../../../system/string/) | A függvény típusától függő további argumentum |

### Visszatérési érték

Új matematikai elem típusa [IMathFunction](../../imathfunction/)
## Megjegyzések

Példa: 
```cpp
auto functionArg = System::MakeObject<MathematicalText>(u"x");
auto func = functionArg->AsArgumentOfFunction(MathFunctionsOfTwoArguments::Log, u"5");
// Visszaadja az 'x' logaritmusát a '5' alapra
```

## Lásd még

* Enum [MathFunctionsOfOneArgument](../../mathfunctionsofoneargument/)
* Enum [MathFunctionsOfTwoArguments](../../mathfunctionsoftwoarguments/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [IMathFunction](../../imathfunction/)
* Osztály [IMathElement](../)
* Osztály [String](../../../system/string/)
* Névtér [Aspose::Slides::MathText](../../)
* Könyvtár [Aspose.Slides](../../../)