---
title: InkBrush
second_title: Aspose.Slides pro Java API Reference
description: Reprezentuje objekt inkBrush.
type: docs
url: /cs/com.aspose.slides/inkbrush/
---
**Dědičnost:**
java.lang.Object

**Všechny implementované rozhraní:**
[com.aspose.slides.IInkBrush](../../com.aspose.slides/iinkbrush)
```
public class InkBrush implements IInkBrush
```

Reprezentuje objekt inkBrush.
## Metody

| Metoda | Popis |
| --- | --- |
| [getColor()](#getColor--) | Získá nebo nastaví barvu štětce pro čáru. |
| [setColor(Color value)](#setColor-java.awt.Color-) | Získá nebo nastaví barvu štětce pro čáru. |
| [getSize()](#getSize--) | Získá nebo nastaví velikost štětce pro čáru v bodech. |
| [setSize(Dimension2D value)](#setSize-java.awt.geom.Dimension2D-) | Získá nebo nastaví velikost štětce pro čáru v bodech. |
| [getInkEffect()](#getInkEffect--) | Získá typ efektu ink (např. Galaxy, Gold, Silver), který definuje vizuální styl ink tahu. |

### getColor() {#getColor--}
```
public final Color getColor()
```

Získá nebo nastaví barvu štětce pro čáru.

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

**Vrací:**
java.awt.Color
### setColor(Color value) {#setColor-java.awt.Color-}
```
public final void setColor(Color value)
```

Získá nebo nastaví barvu štětce pro čáru.

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

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | java.awt.Color |  |

### getSize() {#getSize--}
```
public final Dimension2D getSize()
```

Získá nebo nastaví velikost štětce pro čáru v bodech.

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

**Vrací:**
java.awt.geom.Dimension2D
### setSize(Dimension2D value) {#setSize-java.awt.geom.Dimension2D-}
```
public final void setSize(Dimension2D value)
```

Získá nebo nastaví velikost štětce pro čáru v bodech.

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

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | java.awt.geom.Dimension2D |  |

### getInkEffect() {#getInkEffect--}
```
public final int getInkEffect()
```

Získá typ efektu ink (např. Galaxy, Gold, Silver), který definuje vizuální styl ink tahu. Hodnota je načtena z vlastnosti štětce "inkEffects". Pokud není specifikován rozpoznaný efekt, [InkEffectType.NotDefined](../../com.aspose.slides/inkeffecttype\#NotDefined) je vrácena.

**Vrací:**
int