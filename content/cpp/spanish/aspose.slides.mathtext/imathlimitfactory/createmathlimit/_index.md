---
title: CreateMathLimit()
second_title: Referencia de la API de Aspose.Slides para C++
description: Crea IMathLimit
type: docs
weight: 1
url: /es/aspose.slides.mathtext/imathlimitfactory/createmathlimit/
---
## IMathLimitFactory::CreateMathLimit(System::SharedPtr\<IMathElement\>, System::SharedPtr\<IMathElement\>, bool) metodo


Crea [IMathLimit](../../imathlimit/)

```cpp
virtual System::SharedPtr<IMathLimit> Aspose::Slides::MathText::IMathLimitFactory::CreateMathLimit(System::SharedPtr<IMathElement> baseArg, System::SharedPtr<IMathElement> limit, bool upperLimit)=0
```


### Argumentos

| Parametro | Tipo | Descripcion |
| --- | --- | --- |
| baseArg | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Argumento base para aplicar el limite |
| limit | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Elemento limite |
| upperLimit | **bool** | Establece la ubicacion del limite en la parte superior |

### Valor devuelto

nuevo limite matematico

## IMathLimitFactory::CreateMathLimit(System::SharedPtr\<IMathElement\>, System::SharedPtr\<IMathElement\>) metodo


Crea [IMathLimit](../../imathlimit/) con limite en la parte inferior

```cpp
virtual System::SharedPtr<IMathLimit> Aspose::Slides::MathText::IMathLimitFactory::CreateMathLimit(System::SharedPtr<IMathElement> baseArg, System::SharedPtr<IMathElement> limit)=0
```


### Argumentos

| Parametro | Tipo | Descripcion |
| --- | --- | --- |
| baseArg | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Argumento base para aplicar el limite |
| limit | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Elemento limite |

### Valor devuelto

nuevo limite matematico

## Ver tambien

* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [IMathLimit](../../imathlimit/)
* Clase [IMathElement](../../imathelement/)
* Clase [IMathLimitFactory](../)
* Espacio de nombres [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)