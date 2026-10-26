---
title: Function()
second_title: Referencia de la API de Aspose.Slides para C++
description: Toma una función de un argumento usando esta instancia como el nombre de la función
type: docs
weight: 53
url: /es/aspose.slides.mathtext/imathelement/function/
---
## IMathElement::Function(System::SharedPtr\<IMathElement\>) método

Toma una función de un argumento usando esta instancia como el nombre de la función

```cpp
virtual System::SharedPtr<IMathFunction> Aspose::Slides::MathText::IMathElement::Function(System::SharedPtr<IMathElement> functionArgument)=0
```

### Parámetros

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| functionArgument | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../)\> | Un argumento de la función |

### Valor devuelto

Nuevo elemento matemático de tipo [IMathFunction](../../imathfunction/)

## Observaciones

Ejemplo: 
```cpp
auto functionName = System::MakeObject<MathematicalText>(u"sin");
auto functionArg = System::MakeObject<MathematicalText>(u"x");
auto func = functionName->Function(functionArg);
```

## IMathElement::Function(System::String) método

Toma una función de un argumento usando esta instancia como el nombre de la función

```cpp
virtual System::SharedPtr<IMathFunction> Aspose::Slides::MathText::IMathElement::Function(System::String functionArgument)=0
```

### Parámetros

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| functionArgument | [System::String](../../../system/string/) | Un argumento de la función |

### Valor devuelto

Nuevo elemento matemático de tipo [IMathFunction](../../imathfunction/)

## Observaciones

Ejemplo: 
```cpp
auto functionName = System::MakeObject<MathematicalText>(u"sin");
auto func = functionName->Function(u"x");
```

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [IMathFunction](../../imathfunction/)
* Clase [IMathElement](../)
* Clase [String](../../../system/string/)
* Espacio de nombres [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)