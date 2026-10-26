---
title: Function()
second_title: Referencia de API de Aspose.Slides para C++
description: Toma una función de un argumento usando esta instancia como nombre de la función
type: docs
weight: 40
url: /es/aspose.slides.mathtext/mathelementbase/function/
---
## MathElementBase::Function(System::SharedPtr\<IMathElement\>) método


Toma una función de un argumento usando esta instancia como nombre de la función

```cpp
System::SharedPtr<IMathFunction> Aspose::Slides::MathText::MathElementBase::Function(System::SharedPtr<IMathElement> functionArgument) override
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| functionArgument | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Un argumento de la función |

### Valor de retorno

New math element of type [IMathFunction](../../imathfunction/)
## Observaciones



Ejemplo: 
```cpp
auto functionName = System::MakeObject<MathematicalText>(u"sin");
auto functionArg = System::MakeObject<MathematicalText>(u"x");
auto func = functionName->Function(functionArg);
```

## MathElementBase::Function(System::String) método


Toma una función de un argumento usando esta instancia como nombre de la función

```cpp
System::SharedPtr<IMathFunction> Aspose::Slides::MathText::MathElementBase::Function(System::String functionArgument) override
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| functionArgument | [System::String](../../../system/string/) | Un argumento de la función |

### Valor de retorno

New math element of type [IMathFunction](../../imathfunction/)
## Observaciones



Ejemplo: 
```cpp
auto functionName = System::MakeObject<MathematicalText>(u"sin");
auto func = functionName->Function(u"x");
```

## Ver también

* Definición de tipo [SharedPtr](../../../system/sharedptr/)
* Clase [IMathFunction](../../imathfunction/)
* Clase [IMathElement](../../imathelement/)
* Clase [MathElementBase](../)
* Clase [String](../../../system/string/)
* Espacio de nombres [Aspose::Slides::MathText](../../)
* Biblioteca [Aspose.Slides](../../../)