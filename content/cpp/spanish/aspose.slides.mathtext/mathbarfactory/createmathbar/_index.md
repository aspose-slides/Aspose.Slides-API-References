---
title: CreateMathBar()
second_title: Referencia de API de Aspose.Slides para C++
description: Crear una barra matemática aplicándola al elemento
type: docs
weight: 1
url: /es/aspose.slides.mathtext/mathbarfactory/createmathbar/
---
## MathBarFactory::CreateMathBar(System::SharedPtr\<IMathElement\>) método


Crear una barra matemática aplicándola al elemento

```cpp
System::SharedPtr<IMathBar> Aspose::Slides::MathText::MathBarFactory::CreateMathBar(System::SharedPtr<IMathElement> element) override
```


### Parámetros

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | elemento matemático al que aplicar la barra |

### Valor devuelto

nuevo elemento de barra matemática

## MathBarFactory::CreateMathBar(System::SharedPtr\<IMathElement\>, MathTopBotPositions) método


Crear una barra matemática aplicándola al elemento

```cpp
System::SharedPtr<IMathBar> Aspose::Slides::MathText::MathBarFactory::CreateMathBar(System::SharedPtr<IMathElement> element, MathTopBotPositions position) override
```


### Parámetros

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Elemento matemático al que aplicar la barra |
| position | [MathTopBotPositions](../../mathtopbotpositions/) | Posición de la barra |

### Valor devuelto

nuevo elemento de barra matemática

## Ver también

* Enum [MathTopBotPositions](../../mathtopbotpositions/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [IMathBar](../../imathbar/)
* Clase [IMathElement](../../imathelement/)
* Clase [MathBarFactory](../)
* Espacio de nombres [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)