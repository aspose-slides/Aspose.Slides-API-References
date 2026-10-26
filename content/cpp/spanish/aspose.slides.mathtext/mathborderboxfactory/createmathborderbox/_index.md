---
title: CreateMathBorderBox()
second_title: Referencia de la API de Aspose.Slides para C++
description: Crea una caja de borde matemática aplicándola al elemento
type: docs
weight: 1
url: /es/aspose.slides.mathtext/mathborderboxfactory/createmathborderbox/
---
## MathBorderBoxFactory::CreateMathBorderBox(System::SharedPtr\<IMathElement\>) method

Crea una caja de borde matemática aplicándola al elemento

```cpp
System::SharedPtr<IMathBorderBox> Aspose::Slides::MathText::MathBorderBoxFactory::CreateMathBorderBox(System::SharedPtr<IMathElement> element) override
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | elemento matemático al que aplicar la caja de borde |

### Valor devuelto

nuevo elemento de caja de borde

## MathBorderBoxFactory::CreateMathBorderBox(System::SharedPtr\<IMathElement\>, bool, bool, bool, bool, bool, bool, bool, bool) method

Crea una caja de borde matemática aplicándola al elemento

```cpp
System::SharedPtr<IMathBorderBox> Aspose::Slides::MathText::MathBorderBoxFactory::CreateMathBorderBox(System::SharedPtr<IMathElement> element, bool hideTop, bool hideBottom, bool hideLeft, bool hideRight, bool strikethroughHorizontal, bool strikethroughVertical, bool strikethroughBottomLeftToTopRight, bool strikethroughTopLeftToBottomRight) override
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | elemento matemático al que aplicar la caja de borde |
| hideTop | **bool** | Ocultar borde superior |
| hideBottom | **bool** | Ocultar borde inferior |
| hideLeft | **bool** | Ocultar borde izquierdo |
| hideRight | **bool** | Ocultar borde derecho |
| strikethroughHorizontal | **bool** | Tachado horizontal del borde de caja |
| strikethroughVertical | **bool** | Tachado vertical del borde de caja |
| strikethroughBottomLeftToTopRight | **bool** | Tachado diagonal inferior-izquierda a superior-derecha del borde de caja |
| strikethroughTopLeftToBottomRight | **bool** | Tachado diagonal superior-izquierda a inferior-derecha del borde de caja |

### Valor devuelto

nuevo elemento de caja de borde

## Véase también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IMathBorderBox](../../imathborderbox/)
* Class [IMathElement](../../imathelement/)
* Class [MathBorderBoxFactory](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)