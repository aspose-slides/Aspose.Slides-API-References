---
title: CreateMathLimit()
second_title: Referencia de API de Aspose.Slides para C++
description: Crea IMathLimit
type: docs
weight: 1
url: /es/aspose.slides.mathtext/mathlimitfactory/createmathlimit/
---
## MathLimitFactory::CreateMathLimit(System::SharedPtr\<IMathElement\>, System::SharedPtr\<IMathElement\>, bool) método


Crea [IMathLimit](../../imathlimit/)

```cpp
System::SharedPtr<IMathLimit> Aspose::Slides::MathText::MathLimitFactory::CreateMathLimit(System::SharedPtr<IMathElement> baseArg, System::SharedPtr<IMathElement> limit, bool upperLimit) override
```


### Parámetros

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| baseArg | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | argumento base para aplicar el límite |
| limit | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | elemento límite |
| upperLimit | **bool** | Establece la posición del límite en la parte superior |

### Valor devuelto

nuevo límite matemático

## MathLimitFactory::CreateMathLimit(System::SharedPtr\<IMathElement\>, System::SharedPtr\<IMathElement\>) método


Crea [IMathLimit](../../imathlimit/) con límite en la parte inferior

```cpp
System::SharedPtr<IMathLimit> Aspose::Slides::MathText::MathLimitFactory::CreateMathLimit(System::SharedPtr<IMathElement> baseArg, System::SharedPtr<IMathElement> limit) override
```


### Parámetros

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| baseArg | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | argumento base para aplicar el límite |
| limit | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | elemento límite |

### Valor devuelto

nuevo límite matemático

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [IMathLimit](../../imathlimit/)
* Clase [IMathElement](../../imathelement/)
* Clase [MathLimitFactory](../)
* Espacio de nombres [Aspose::Slides::MathText](../../)
* Biblioteca [Aspose.Slides](../../../)