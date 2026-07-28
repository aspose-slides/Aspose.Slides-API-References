---
title: AsArgumentOfFunction()
second_title: Aspose.Slides C++ API referencia
description: Megadott függvényt vesz, amelyhez ezt a példányt argumentumként használja
type: docs
weight: 53
url: /hu/aspose.slides.mathtext/mathelementbase/asargumentoffunction/
---
## MathElementBase::AsArgumentOfFunction(System::SharedPtr\<IMathElement\>) method

Megadott függvényt vesz, amelyhez ezt a példányt argumentumként használja

```cpp
System::SharedPtr<IMathFunction> Aspose::Slides::MathText::MathElementBase::AsArgumentOfFunction(System::SharedPtr<IMathElement> functionName) override
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| functionName | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Function name |

### Visszatérési érték

Új matematikai elem típusa [IMathFunction](../../imathfunction/)

## Megjegyzések

Példa: 
```cpp
auto functionName = System::MakeObject<MathematicalText>(u"sin");
auto functionArg = System::MakeObject<MathematicalText>(u"x");
auto func = functionArg->AsArgumentOfFunction(functionName);
```

## MathElementBase::AsArgumentOfFunction(System::String) method

Megadott függvényt vesz, amelyhez ezt a példányt argumentumként használja

```cpp
System::SharedPtr<IMathFunction> Aspose::Slides::MathText::MathElementBase::AsArgumentOfFunction(System::String functionName) override
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| functionName | [System::String](../../../system/string/) | Function name |

### Visszatérési érték

Új matematikai elem típusa [IMathFunction](../../imathfunction/)

## Megjegyzések

Példa: 
```cpp
auto functionArg = System::MakeObject<MathematicalText>(u"x");
auto func = functionArg->AsArgumentOfFunction(u"cos");
```

## MathElementBase::AsArgumentOfFunction(MathFunctionsOfOneArgument) method

Megadott függvényt vesz, amelyhez ezt a példányt argumentumként használja

```cpp
System::SharedPtr<IMathFunction> Aspose::Slides::MathText::MathElementBase::AsArgumentOfFunction(MathFunctionsOfOneArgument functionType) override
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| functionType | [MathFunctionsOfOneArgument](../../mathfunctionsofoneargument/) | Az egy argumentumú gyakori függvénytípusok egyike |

### Visszatérési érték

Új matematikai elem típusa [IMathFunction](../../imathfunction/)

## Megjegyzések

Példa: 
```cpp
auto functionName = System::MakeObject<MathematicalText>(u"sin");
auto functionArg = System::MakeObject<MathematicalText>(u"x");
auto func = functionArg->AsArgumentOfFunction(functionName);
```

## MathElementBase::AsArgumentOfFunction(MathFunctionsOfTwoArguments, System::SharedPtr\<IMathElement\>) method

Megadott függvényt vesz, amelyhez ezt a példányt argumentumként használja, és megadott további argumentummal

```cpp
System::SharedPtr<IMathFunction> Aspose::Slides::MathText::MathElementBase::AsArgumentOfFunction(MathFunctionsOfTwoArguments functionType, System::SharedPtr<IMathElement> additionalArgument) override
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| functionType | [MathFunctionsOfTwoArguments](../../mathfunctionsoftwoarguments/) | Két argumentumú gyakori függvénytípusok egyike: Log, Lim, Min, Max |
| additionalArgument | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | A függvény típusától függő további argumentum |

### Visszatérési érték

Új matematikai elem típusa [IMathFunction](../../imathfunction/)

## Megjegyzések

Példa: 
```cpp
auto functionArg = System::MakeObject<MathematicalText>(u"x");
auto logarithmBase = System::MakeObject<MathematicalText>(u"5");
auto func = functionArg->AsArgumentOfFunction(MathFunctionsOfTwoArguments::Log, logarithmBase);
// Visszaadja az 'x' logaritmusát az '5' alapra
```

## MathElementBase::AsArgumentOfFunction(MathFunctionsOfTwoArguments, System::String) method

Megadott függvényt vesz, amelyhez ezt a példányt argumentumként használja, és megadott további argumentummal

```cpp
System::SharedPtr<IMathFunction> Aspose::Slides::MathText::MathElementBase::AsArgumentOfFunction(MathFunctionsOfTwoArguments functionType, System::String additionalArgument) override
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| functionType | [MathFunctionsOfTwoArguments](../../mathfunctionsoftwoarguments/) | Két argumentumú gyakori függvénytípusok egyike: Log, Lim, Min, Max |
| additionalArgument | [System::String](../../../system/string/) | A függvény típusától függő további argumentum |

### Visszatérési érték

Új matematikai elem típusa [IMathFunction](../../imathfunction/)

## Megjegyzések

Példa: 
```cpp
auto functionArg = System::MakeObject<MathematicalText>(u"x");
auto func = functionArg->AsArgumentOfFunction(MathFunctionsOfTwoArguments::Log, u"5");
// Visszaadja az 'x' logaritmusát az '5' alapra
```

## Lásd még

* Enum [MathFunctionsOfOneArgument](../../mathfunctionsofoneargument/)
* Enum [MathFunctionsOfTwoArguments](../../mathfunctionsoftwoarguments/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IMathFunction](../../imathfunction/)
* Class [IMathElement](../../imathelement/)
* Class [MathElementBase](../)
* Class [String](../../../system/string/)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)