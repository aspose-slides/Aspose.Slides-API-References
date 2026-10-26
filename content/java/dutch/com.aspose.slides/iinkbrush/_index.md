---
title: IInkBrush
second_title: Aspose.Slides for Java API Reference
description: Stelt een traceerborstel voor.
type: docs
url: /nl/com.aspose.slides/iinkbrush/
---```
public interface IInkBrush
```

Stelt een traceerborstel voor.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getColor()](#getColor--) | Haalt de kleur van de borstel op of stelt deze in voor een lijn. |
| [setColor(Color value)](#setColor-java.awt.Color-) | Haalt de kleur van de borstel op of stelt deze in voor een lijn. |
| [getSize()](#getSize--) | Haalt de grootte van de borstel op of stelt deze in voor een lijn in punten. |
| [setSize(Dimension2D value)](#setSize-java.awt.geom.Dimension2D-) | Haalt de grootte van de borstel op of stelt deze in voor een lijn in punten. |
| [getInkEffect()](#getInkEffect--) | Haalt het inkt-effecttype op (bijv. Galaxy, Gold, Silver) dat de visuele stijl van de inktstreep bepaalt. |

### getColor() {#getColor--}
```
public abstract Color getColor()
```

Haalt de kleur van de borstel op of stelt deze in voor een lijn.

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

**Retour:**  
java.awt.Color
### setColor(Color value) {#setColor-java.awt.Color-}
```
public abstract void setColor(Color value)
```

Haalt de kleur van de borstel op of stelt deze in voor een lijn.

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

**Parameters:**  
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | java.awt.Color |  |

### getSize() {#getSize--}
```
public abstract Dimension2D getSize()
```

Haalt de grootte van de borstel op of stelt deze in voor een lijn in punten.

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

**Retour:**  
java.awt.geom.Dimension2D
### setSize(Dimension2D value) {#setSize-java.awt.geom.Dimension2D-}
```
public abstract void setSize(Dimension2D value)
```

Haalt de grootte van de borstel op of stelt deze in voor een lijn in punten.

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

**Parameters:**  
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | java.awt.geom.Dimension2D |  |

### getInkEffect() {#getInkEffect--}
```
public abstract int getInkEffect()
```

Haalt het inkt-effecttype op (bijv. Galaxy, Gold, Silver) dat de visuele stijl van de inktstreep bepaalt. De waarde wordt geparseerd vanuit de borstel-eigenschap "inkEffects". Als geen herkend effect is gespecificeerd, wordt [InkEffectType.NotDefined](../../com.aspose.slides/inkeffecttype\#NotDefined) geretourneerd.

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

**Retour:**  
int