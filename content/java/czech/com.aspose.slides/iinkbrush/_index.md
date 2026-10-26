---
title: IInkBrush
second_title: Aspose.Slides for Java API Reference
description: Represents trace brush.
type: docs
url: /cs/com.aspose.slides/iinkbrush/
---```
public interface IInkBrush
```

Reprezentuje kreslicí štětec.
## Metody

| Metoda | Popis |
| --- | --- |
| [getColor()](#getColor--) | Získá nebo nastaví barvu štětce pro čáru. |
| [setColor(Color value)](#setColor-java.awt.Color-) | Získá nebo nastaví barvu štětce pro čáru. |
| [getSize()](#getSize--) | Získá nebo nastaví velikost štětce pro čáru v bodech. |
| [setSize(Dimension2D value)](#setSize-java.awt.geom.Dimension2D-) | Získá nebo nastaví velikost štětce pro čáru v bodech. |
| [getInkEffect()](#getInkEffect--) | Získá typ efektu inkoustu (např. Galaxy, Gold, Silver), který určuje vizuální styl tahů inkoustu. |
### getColor() {#getColor--}
```
public abstract Color getColor()
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
public abstract void setColor(Color value)
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
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.awt.Color |  |

### getSize() {#getSize--}
```
public abstract Dimension2D getSize()
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
public abstract void setSize(Dimension2D value)
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
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.awt.geom.Dimension2D |  |

### getInkEffect() {#getInkEffect--}
```
public abstract int getInkEffect()
```


Získá typ efektu inkoustu (např. Galaxy, Gold, Silver), který určuje vizuální styl tahů inkoustu. Hodnota je parsována z vlastnosti štětce "inkEffects". Pokud není zadán rozpoznaný efekt, [InkEffectType.NotDefined](../../com.aspose.slides/inkeffecttype\#NotDefined) je vrácena.

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

**Vrací:**
int