---
title: IMathBorderBox
second_title: Referencia de API de Aspose.Slides para .NET
description: Dibuja un borde rectangular u otro alrededor del IMathElement.
type: docs
weight: 7920
url: /es/aspose.slides.mathtext/imathborderbox/
---

## Interfaz IMathBorderBox

Dibuja un borde rectangular u otro alrededor del IMathElement.

```csharp
public interface IMathBorderBox : IMathElement
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [AsIMathElement](../../aspose.slides.mathtext/imathborderbox/asimathelement) { get; } | Permite obtener la interfaz base IMathElement [`IMathElement`](../imathelement) |
| [Base](../../aspose.slides.mathtext/imathborderbox/base) { get; } | Argumento base |
| [HideBottom](../../aspose.slides.mathtext/imathborderbox/hidebottom) { get; set; } | Ocultar borde inferior (el valor predeterminado es falso) - especifica el estado oculto o visible del borde inferior de la caja de borde. |
| [HideLeft](../../aspose.slides.mathtext/imathborderbox/hideleft) { get; set; } | Ocultar borde izquierdo (el valor predeterminado es falso) - especifica el estado oculto o visible del borde izquierdo de la caja de borde. |
| [HideRight](../../aspose.slides.mathtext/imathborderbox/hideright) { get; set; } | Ocultar borde derecho (el valor predeterminado es falso) - especifica el estado oculto o visible del borde derecho de la caja de borde. |
| [HideTop](../../aspose.slides.mathtext/imathborderbox/hidetop) { get; set; } | Ocultar borde superior (el valor predeterminado es falso) - especifica el estado oculto o visible del borde superior de la caja de borde. |
| [StrikethroughBottomLeftToTopRight](../../aspose.slides.mathtext/imathborderbox/strikethroughbottomlefttotopright) { get; set; } | Línea de tachado de esquina inferior izquierda a esquina superior derecha (el valor predeterminado es falso). Especifica el estado oculto o visible de una línea diagonal de tachado desde la esquina inferior izquierda hasta la esquina superior derecha de la caja de borde. |
| [StrikethroughHorizontal](../../aspose.slides.mathtext/imathborderbox/strikethroughhorizontal) { get; set; } | Línea de tachado horizontal (el valor predeterminado es falso) - especifica el estado oculto o visible de una línea horizontal de tachado. |
| [StrikethroughTopLeftToBottomRight](../../aspose.slides.mathtext/imathborderbox/strikethroughtoplefttobottomright) { get; set; } | Línea de tachado de esquina superior izquierda a esquina inferior derecha (el valor predeterminado es falso). Especifica el estado oculto o visible de una línea diagonal de tachado desde la esquina superior izquierda hasta la esquina inferior derecha de la caja de borde. |
| [StrikethroughVertical](../../aspose.slides.mathtext/imathborderbox/strikethroughvertical) { get; set; } | Línea de tachado vertical (el valor predeterminado es falso) - especifica el estado oculto o visible de una línea vertical de tachado. |

### Ejemplos

Ejemplo:

```csharp
[C#]
IMathBorderBox borderBox = new MathematicalText("x+y+z").ToBorderBox();
```

### Ver También

* interfaz [IMathElement](../imathelement)
* espacio de nombres [Aspose.Slides.MathText](../../aspose.slides.mathtext)
* ensamblaje [Aspose.Slides](../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->