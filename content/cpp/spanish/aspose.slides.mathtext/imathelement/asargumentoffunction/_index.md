---
title: AsArgumentOfFunction()
second_title: Referencia de la API de Aspose.Slides para C++
description: Toma la función especificada usando esta instancia como argumento
type: docs
weight: 66
url: /es/aspose.slides.mathtext/imathelement/asargumentoffunction/
---
## IMathElement::AsArgumentOfFunction(System::SharedPtr\<IMathElement\>) método


Toma la función especificada usando esta instancia como argumento

```cpp
virtual System::SharedPtr<IMathFunction> Aspose::Slides::MathText::IMathElement::AsArgumentOfFunction(System::SharedPtr<IMathElement> functionName)=0
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| functionName | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../)\> | Nombre de la función |

### Valor devuelto

Nuevo elemento matemático del tipo [IMathFunction](../../imathfunction/)
## Comentarios



Ejemplo: 
```cpp
auto functionName = System::MakeObject<MathematicalText>(u"sin");
auto functionArg = System::MakeObject<MathematicalText>(u"x");
auto func = functionArg->AsArgumentOfFunction(functionName);
```

## IMathElement::AsArgumentOfFunction(System::String) método


Toma la función especificada usando esta instancia como argumento

```cpp
virtual System::SharedPtr<IMathFunction> Aspose::Slides::MathText::IMathElement::AsArgumentOfFunction(System::String functionName)=0
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| functionName | [System::String](../../../system/string/) | Nombre de la función |

### Valor devuelto

Nuevo elemento matemático del tipo [IMathFunction](../../imathfunction/)
## Comentarios



Ejemplo: 
```cpp
auto functionArg = System::MakeObject<MathematicalText>(u"x");
auto func = functionArg->AsArgumentOfFunction(u"cos");
```

## IMathElement::AsArgumentOfFunction(MathFunctionsOfOneArgument) método


Toma la función especificada usando esta instancia como argumento

```cpp
virtual System::SharedPtr<IMathFunction> Aspose::Slides::MathText::IMathElement::AsArgumentOfFunction(MathFunctionsOfOneArgument functionType)=0
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| functionType | [MathFunctionsOfOneArgument](../../mathfunctionsofoneargument/) | Uno de los tipos de función común de un argumento |

### Valor devuelto

Nuevo elemento matemático del tipo [IMathFunction](../../imathfunction/)
## Comentarios



Ejemplo: 
```cpp
auto functionArg = System::MakeObject<MathematicalText>(u"x");
auto func = functionArg->AsArgumentOfFunction(MathFunctionsOfOneArgument::ArcSin);
```

## IMathElement::AsArgumentOfFunction(MathFunctionsOfTwoArguments, System::SharedPtr\<IMathElement\>) método


Toma la función especificada usando esta instancia como argumento y el argumento adicional especificado

```cpp
virtual System::SharedPtr<IMathFunction> Aspose::Slides::MathText::IMathElement::AsArgumentOfFunction(MathFunctionsOfTwoArguments functionType, System::SharedPtr<IMathElement> additionalArgument)=0
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| functionType | [MathFunctionsOfTwoArguments](../../mathfunctionsoftwoarguments/) | Uno de los tipos de función común de dos argumentos: Log, Lim, Min, Max |
| additionalArgument | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../)\> | Argumento adicional dependiendo del tipo de función |

### Valor devuelto

Nuevo elemento matemático del tipo [IMathFunction](../../imathfunction/)
## Comentarios



Ejemplo: 
```cpp
auto functionArg = System::MakeObject<MathematicalText>(u"x");
auto logarithmBase = System::MakeObject<MathematicalText>(u"5");
auto func = functionArg->AsArgumentOfFunction(MathFunctionsOfTwoArguments::Log, logarithmBase);
// Devuelve el logaritmo de 'x' a la base '5'
```

## IMathElement::AsArgumentOfFunction(MathFunctionsOfTwoArguments, System::String) método


Toma la función especificada usando esta instancia como argumento y el argumento adicional especificado

```cpp
virtual System::SharedPtr<IMathFunction> Aspose::Slides::MathText::IMathElement::AsArgumentOfFunction(MathFunctionsOfTwoArguments functionType, System::String additionalArgument)=0
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| functionType | [MathFunctionsOfTwoArguments](../../mathfunctionsoftwoarguments/) | Uno de los tipos de función común de dos argumentos: Log, Lim, Min, Max |
| additionalArgument | [System::String](../../../system/string/) | Argumento adicional dependiendo del tipo de función |

### Valor devuelto

Nuevo elemento matemático del tipo [IMathFunction](../../imathfunction/)
## Comentarios



Ejemplo: 
```cpp
auto functionArg = System::MakeObject<MathematicalText>(u"x");
auto func = functionArg->AsArgumentOfFunction(MathFunctionsOfTwoArguments::Log, u"5");
// Devuelve el logaritmo de 'x' a la base '5'
```

## Ver también

* Enumeración [MathFunctionsOfOneArgument](../../mathfunctionsofoneargument/)
* Enumeración [MathFunctionsOfTwoArguments](../../mathfunctionsoftwoarguments/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [IMathFunction](../../imathfunction/)
* Clase [IMathElement](../)
* Clase [String](../../../system/string/)
* Espacio de nombres [Aspose::Slides::MathText](../../)
* Biblioteca [Aspose.Slides](../../../)