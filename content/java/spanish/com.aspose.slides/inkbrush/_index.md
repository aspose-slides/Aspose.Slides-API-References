---
title: InkBrush
second_title: Referencia de API de Aspose.Slides para Java
description: Representa un objeto inkBrush.
type: docs
url: /es/com.aspose.slides/inkbrush/
---
**Herencia:**  
java.lang.Object

**Todas las interfaces implementadas:**  
[com.aspose.slides.IInkBrush](../../com.aspose.slides/iinkbrush)  
```
public class InkBrush implements IInkBrush
```

Representa un objeto inkBrush.
## Métodos

| Method | Description |
| --- | --- |
| [getColor()](#getColor--) | Obtiene o establece el color del pincel para una línea. |
| [setColor(Color value)](#setColor-java.awt.Color-) | Obtiene o establece el color del pincel para una línea. |
| [getSize()](#getSize--) | Obtiene o establece el tamaño del pincel para una línea en puntos. |
| [setSize(Dimension2D value)](#setSize-java.awt.geom.Dimension2D-) | Obtiene o establece el tamaño del pincel para una línea en puntos. |
| [getInkEffect()](#getInkEffect--) | Obtiene el tipo de efecto de tinta (p. ej., Galaxy, Gold, Silver) que define el estilo visual del trazo de tinta. |

### getColor() {#getColor--}
```
public final Color getColor()
```

Obtiene o establece el color del pincel para una línea.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      IInk ink = (IInk)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      IInkTrace[] traces = ink.getTraces();
>      IInkBrush brush = traces[0].getBrush();
>      Color brushColor = brush.getColor();
>      brush.setColor(Color.RED);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Devuelve:**
java.awt.Color
### setColor(Color value) {#setColor-java.awt.Color-}
```
public final void setColor(Color value)
```

Obtiene o establece el color del pincel para una línea.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      IInk ink = (IInk)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      IInkTrace[] traces = ink.getTraces();
>      IInkBrush brush = traces[0].getBrush();
>      Color brushColor = brush.getColor();
>      brush.setColor(Color.RED);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parámetros:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.awt.Color |  |

### getSize() {#getSize--}
```
public final Dimension2D getSize()
```

Obtiene o establece el tamaño del pincel para una línea en puntos.

--------------------

> ```
> Ejemplo:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      IInk ink = (IInk)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      IInkTrace[] traces = ink.getTraces();
>      IInkBrush brush = traces[0].getBrush();
>      Dimension2D brushSize = brush.getSize();
>      brush.setSize(new Dimension(5, 10));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Devuelve:**
java.awt.geom.Dimension2D
### setSize(Dimension2D value) {#setSize-java.awt.geom.Dimension2D-}
```
public final void setSize(Dimension2D value)
```

Obtiene o establece el tamaño del pincel para una línea en puntos.

--------------------

> ```
> Ejemplo:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      IInk ink = (IInk)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      IInkTrace[] traces = ink.getTraces();
>      IInkBrush brush = traces[0].getBrush();
>      Dimension2D brushSize = brush.getSize();
>      brush.setSize(new Dimension(5, 10));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parámetros:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.awt.geom.Dimension2D |  |

### getInkEffect() {#getInkEffect--}
```
public final int getInkEffect()
```

Obtiene el tipo de efecto de tinta (p. ej., Galaxy, Gold, Silver) que define el estilo visual del trazo de tinta. El valor se analiza a partir de la propiedad del pincel "inkEffects". Si no se especifica ningún efecto reconocido, [InkEffectType.NotDefined](../../com.aspose.slides/inkeffecttype\#NotDefined) se devuelve.

**Devuelve:**
int