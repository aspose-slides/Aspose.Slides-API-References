---
title: InkBrush
second_title: Aspose.Slides para Android a través de la referencia de API Java
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

| Método | Descripción |
| --- | --- |
| [getColor()](#getColor--) | Obtiene o establece el color del pincel para una línea. |
| [setColor(Integer value)](#setColor-java.lang.Integer-) | Obtiene o establece el color del pincel para una línea. |
| [getSize()](#getSize--) | Obtiene o establece el tamaño del pincel para una línea en puntos. |
| [setSize(SizeF value)](#setSize-com.aspose.slides.android.SizeF-) | Obtiene o establece el tamaño del pincel para una línea en puntos. |
| [getInkEffect()](#getInkEffect--) | Obtiene el tipo de efecto de tinta (p. ej., Galaxy, Gold, Silver) que define el estilo visual del trazo de tinta. |
### getColor() {#getColor--}
```
public final Integer getColor()
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
java.lang.Integer
### setColor(Integer value) {#setColor-java.lang.Integer-}
```
public final void setColor(Integer value)
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
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | java.lang.Integer |  |

### getSize() {#getSize--}
```
public final SizeF getSize()
```


Obtiene o establece el tamaño del pincel para una línea en puntos.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      IInk ink = (IInk)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      IInkTrace[] traces = ink.getTraces();
>      IInkBrush brush = traces[0].getBrush();
>      SizeF brushSize = brush.getSize();
>      brush.setSize(new com.aspose.slides.android.Size(5, 10));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Devuelve:**
[SizeF](../../com.aspose.slides.android/sizef)
### setSize(SizeF value) {#setSize-com.aspose.slides.android.SizeF-}
```
public final void setSize(SizeF value)
```


Obtiene o establece el tamaño del pincel para una línea en puntos.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      IInk ink = (IInk)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      IInkTrace[] traces = ink.getTraces();
>      IInkBrush brush = traces[0].getBrush();
>      SizeF brushSize = brush.getSize();
>      brush.setSize(new com.aspose.slides.android.Size(5, 10));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [SizeF](../../com.aspose.slides.android/sizef) |  |

### getInkEffect() {#getInkEffect--}
```
public final int getInkEffect()
```


Obtiene el tipo de efecto de tinta (p. ej., Galaxy, Gold, Silver) que define el estilo visual del trazo de tinta. El valor se analiza a partir de la propiedad del pincel "inkEffects". Si no se especifica ningún efecto reconocido, [InkEffectType.NotDefined](../../com.aspose.slides/inkeffecttype\#NotDefined) se devuelve.

**Devuelve:**
int