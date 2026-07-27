---
title: AsArgumentOfFunction()
second_title: Referencia de la API de Aspose.Slides para C++
description: Toma la función especificada usando esta instancia como argumento
type: docs
weight: 53
url: /es/aspose.slides.mathtext/mathelementbase/asargumentoffunction/
---
## MathElementBase::AsArgumentOfFunction(System::SharedPtr\<IMathElement\>) método

Toma la función especificada usando esta instancia como argumento

```cpp
System::SharedPtr<IMathFunction> Aspose::Slides::MathText::MathElementBase::AsArgumentOfFunction(System::SharedPtr<IMathElement> functionName) override
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| functionName | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Nombre de la función |

### Valor devuelto

Nuevo elemento matemático de tipo [IMathFunction](../../imathfunction/)

## Observaciones



Ejemplo: 
```cpp
auto functionName = System::MakeObject<MathematicalText>(u"sin");
auto functionArg = System::MakeObject<MathematicalText>(u"x");
auto func = functionArg->AsArgumentOfFunction(functionName);
```

## MathElementBase::AsArgumentOfFunction(System::String) método


Toma la función especificada usando esta instancia como argumento

```cpp
System::SharedPtr<IMathFunction> Aspose::Slides::MathText::MathElementBase::AsArgumentOfFunction(System::String functionName) override
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| functionName | [System::String](../../../system/string/) | Nombre de la función |

### Valor devuelto

Nuevo elemento matemático de tipo [IMathFunction](../../imathfunction/)

## Observaciones



Ejemplo: 
```cpp
auto functionArg = System::MakeObject<MathematicalText>(u"x");
auto func = functionArg->AsArgumentOfFunction(u"cos");
```

## MathElementBase::AsArgumentOfFunction(MathFunctionsOfOneArgument) método


Toma la función especificada usando esta instancia como argumento

```cpp
System::SharedPtr<IMathFunction> Aspose::Slides::MathText::MathElementBase::AsArgumentOfFunction(MathFunctionsOfOneArgument functionType) override
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| functionType | [MathFunctionsOfOneArgument](../../mathfunctionsofoneargument/) | Uno de los tipos de función comunes de un argumento |

### Valor devuelto

Nuevo elemento matemático de tipo [IMathFunction](../../imathfunction/)

## Observaciones



Ejemplo: 
```cpp
auto functionName = System::MakeObject<MathematicalText>(u"sin");
auto functionArg = System::MakeObject<MathematicalText>(u"x");
auto func = functionArg->AsArgumentOfFunction(functionName);
```

## MathElementBase::AsArgumentOfFunction(MathFunctionsOfTwoArguments, System::SharedPtr\<IMathElement\>) método


Toma la función especificada usando esta instancia como argumento y el argumento adicional especificado

```cpp
System::SharedPtr<IMathFunction> Aspose::Slides::MathText::MathElementBase::AsArgumentOfFunction(MathFunctionsOfTwoArguments functionType, System::SharedPtr<IMathElement> additionalArgument) override
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| functionType | [MathFunctionsOfTwoArguments](../../mathfunctionsoftwoarguments/) | Uno de los tipos de función comunes de dos argumentos: Log, Lim, Min, Max |
| additionalArgument | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Argumento adicional dependiendo del tipo de función |

### Valor devuelto

Nuevo elemento matemático de tipo [IMathFunction](../../imathfunction/)

## Observaciones



Ejemplo: 
```cpp
auto functionArg = System::MakeObject<MathematicalText>(u"x");
auto logarithmBase = System::MakeObject<MathematicalText>(u"5");
auto func = functionArg->AsArgumentOfFunction(MathFunctionsOfTwoArguments::Log, logarithmBase);
// Devuelve el logaritmo de 'x' a la base '5'
```

## MathElementBase::AsArgumentOfFunction(MathFunctionsOfTwoArguments, System::String) método


Toma la función especificada usando esta instancia como argumento y el argumento adicional especificado

```cpp
System::SharedPtr<IMathFunction> Aspose::Slides::MathText::MathElementBase::AsArgumentOfFunction(MathFunctionsOfTwoArguments functionType, System::String additionalArgument) override
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| functionType | [MathFunctionsOfTwoArguments](../../mathfunctionsoftwoarguments/) | Uno de los tipos de función comunes de dos argumentos: Log, Lim, Min, Max |
| additionalArgument | [System::String](../../../system/string/) | Argumento adicional dependiendo del tipo de función |

### Valor devuelto

Nuevo elemento matemático de tipo [IMathFunction](../../imathfunction/)

## Observaciones



Ejemplo: 
```cpp
auto functionArg = System::MakeObject<MathematicalText>(u"x");
auto func = functionArg->AsArgumentOfFunction(MathFunctionsOfTwoArguments::Log, u"5");
// Devuelve el logaritmo de 'x' a la base '5'
```

## Ver también

* Enum [MathFunctionsOfOneArgument](../../mathfunctionsofoneargument/)
* Enum [MathFunctionsOfTwoArguments](../../mathfunctionsoftwoarguments/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IMathFunction](../../imathfunction/)
* Class [IMathElement](../../imathelement/)
* Class [MathElementBase](../)
* Class [String](../../../system/string/)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)