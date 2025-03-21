---
title: MathBorderBox
second_title: Referencia de la API de Aspose.Slides para .NET
description: Crea el elemento MathBorderBox con borde rectangular
type: docs
weight: 10
url: /es/aspose.slides.mathtext/mathborderbox/mathborderbox/
---
## MathBorderBox(IMathElement) {#constructor}

Crea el elemento MathBorderBox con borde rectangular

```csharp
public MathBorderBox(IMathElement element)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| element | IMathElement | El elemento base al que se aplica el cuadro de borde. Puede ser nulo. |

### Ejemplos

Ejemplo:

```csharp
[C#]
MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
```

### Ver también

* interface [IMathElement](../../imathelement)
* class [MathBorderBox](../../mathborderbox)
* espacio de nombres [Aspose.Slides.MathText](../../mathborderbox)
* asamblea [Aspose.Slides](../../../)

---

## MathBorderBox(IMathElement, bool, bool, bool, bool, bool, bool, bool, bool) {#constructor_1}

Crea el elemento MathBorderBox

```csharp
public MathBorderBox(IMathElement element, bool hideTop, bool hideBottom, bool hideLeft, 
    bool hideRight, bool strikethroughHorizontal, bool strikethroughVertical, 
    bool strikethroughBottomLeftToTopRight, bool strikethroughTopLeftToBottomRight)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| element | IMathElement | El elemento base al que se aplica el cuadro de borde |
| hideTop | Boolean | Ocultar borde superior |
| hideBottom | Boolean | Ocultar borde inferior |
| hideLeft | Boolean | Ocultar borde izquierdo |
| hideRight | Boolean | Ocultar borde derecho |
| strikethroughHorizontal | Boolean | Tachado horizontal |
| strikethroughVertical | Boolean | Vertical tachado |
| strikethroughBottomLeftToTopRight | Boolean | Tachado de abajo a la izquierda a arriba a la derecha |
| strikethroughTopLeftToBottomRight | Boolean | Tachado de arriba a la izquierda a abajo a la derecha |

### Ejemplos

Ejemplo:

```csharp
[C#]
MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"), true, true, true, false, true, true, true, true)
```

### Ver también

* interface [IMathElement](../../imathelement)
* class [MathBorderBox](../../mathborderbox)
* espacio de nombres [Aspose.Slides.MathText](../../mathborderbox)
* asamblea [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
