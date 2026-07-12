---
title: IInkBrush
second_title: Aspose.Slides for Android via Java API Reference
description: Representa el pincel de trazo.
type: docs
url: /es/com.aspose.slides/iinkbrush/
---```
public interface IInkBrush
```

Representa el pincel de trazo.
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
public abstract Integer getColor()
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
public abstract void setColor(Integer value)
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
public abstract SizeF getSize()
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
public abstract void setSize(SizeF value)
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
public abstract int getInkEffect()
```


Obtiene el tipo de efecto de tinta (p. ej., Galaxy, Gold, Silver) que define el estilo visual del trazo de tinta. El valor se analiza a partir de la propiedad del pincel "inkEffects". Si no se especifica ningún efecto reconocido, [InkEffectType.NotDefined](../../com.aspose.slides/inkeffecttype\#NotDefined) se devuelve.

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