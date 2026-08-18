---
title: IInkBrush
second_title: Aspose.Slides for Java API Reference
description: Represents trace brush.
type: docs
url: /es/com.aspose.slides/iinkbrush/
---```
public interface IInkBrush
```

Representa un pincel de trazo.
## Métodos

| Método | Descripción |
| --- | --- |
| [getColor()](#getColor--) | Obtiene o establece el color del pincel para una línea. |
| [setColor(Color value)](#setColor-java.awt.Color-) | Obtiene o establece el color del pincel para una línea. |
| [getSize()](#getSize--) | Obtiene o establece el tamaño del pincel para una línea en puntos. |
| [setSize(Dimension2D value)](#setSize-java.awt.geom.Dimension2D-) | Obtiene o establece el tamaño del pincel para una línea en puntos. |
| [getInkEffect()](#getInkEffect--) | Obtiene el tipo de efecto de tinta (p. ej., Galaxy, Gold, Silver) que define el estilo visual del trazo de tinta. |
### getColor() {#getColor--}
```
public abstract Color getColor()
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
public abstract void setColor(Color value)
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
| value | java.awt.Color |  |
### getSize() {#getSize--}
```
public abstract Dimension2D getSize()
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
public abstract void setSize(Dimension2D value)
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
>      Dimension2D brushSize = brush.getSize();
>      brush.setSize(new Dimension(5, 10));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | java.awt.geom.Dimension2D |  |
### getInkEffect() {#getInkEffect--}
```
public abstract int getInkEffect()
```

Obtiene el tipo de efecto de tinta (p. ej., Galaxy, Gold, Silver) que define el estilo visual del trazo de tinta. El valor se analiza a partir de la propiedad del pincel "inkEffects". Si no se especifica ningún efecto reconocido, se devuelve [InkEffectType.NotDefined](../../com.aspose.slides/inkeffecttype\#NotDefined).

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      Ink ink = (Ink) pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      IInkBrush brush = ink.getTraces()[0].getBrush();
>      System.out.println("InkEffects = " + brush.getInkEffect());
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Devuelve:**  
int