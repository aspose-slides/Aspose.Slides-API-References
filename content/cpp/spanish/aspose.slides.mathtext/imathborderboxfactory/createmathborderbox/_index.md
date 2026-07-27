---
title: CreateMathBorderBox()
second_title: Referencia de la API de Aspose.Slides para C++
description: Crear una caja de borde matemática aplicándola al elemento
type: docs
weight: 1
url: /es/aspose.slides.mathtext/imathborderboxfactory/createmathborderbox/
---
## IMathBorderBoxFactory::CreateMathBorderBox(System::SharedPtr\<IMathElement\>) método

Crea una caja de borde matemática aplicándola al elemento

```cpp
virtual System::SharedPtr<IMathBorderBox> Aspose::Slides::MathText::IMathBorderBoxFactory::CreateMathBorderBox(System::SharedPtr<IMathElement> element)=0
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | elemento matemático al que se aplica la caja de borde |

### Valor devuelto

nuevo elemento de caja de borde

## IMathBorderBoxFactory::CreateMathBorderBox(System::SharedPtr\<IMathElement\>, bool, bool, bool, bool, bool, bool, bool, bool) método

Crea una caja de borde matemática aplicándola al elemento

```cpp
virtual System::SharedPtr<IMathBorderBox> Aspose::Slides::MathText::IMathBorderBoxFactory::CreateMathBorderBox(System::SharedPtr<IMathElement> element, bool hideTop, bool hideBottom, bool hideLeft, bool hideRight, bool strikethroughHorizontal, bool strikethroughVertical, bool strikethroughBottomLeftToTopRight, bool strikethroughTopLeftToBottomRight)=0
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | elemento matemático al que se aplica la caja de borde |
| hideTop | **bool** | Ocultar borde superior |
| hideBottom | **bool** | Ocultar borde inferior |
| hideLeft | **bool** | Ocultar borde izquierdo |
| hideRight | **bool** | Ocultar borde derecho |
| strikethroughHorizontal | **bool** | Tachado horizontal de la caja de borde |
| strikethroughVertical | **bool** | Tachado vertical de la caja de borde |
| strikethroughBottomLeftToTopRight | **bool** | Tachado de la caja de borde de abajo-izquierda a arriba-derecha |
| strikethroughTopLeftToBottomRight | **bool** | Tachado de la caja de borde de arriba-izquierda a abajo-derecha |

### Valor devuelto

nuevo elemento de caja de borde

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [IMathBorderBox](../../imathborderbox/)
* Clase [IMathElement](../../imathelement/)
* Clase [IMathBorderBoxFactory](../)
* Espacio de nombres [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)