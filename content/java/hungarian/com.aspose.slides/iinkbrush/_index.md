---
title: IInkBrush
second_title: Aspose.Slides for Java API-referencia
description: A nyomvonal ecsetet képviseli.
type: docs
url: /hu/com.aspose.slides/iinkbrush/
---```
public interface IInkBrush
```

A nyomvonal ecsetet képviseli.
## Metódusok

| Metódus | Leírás |
| --- | --- |
| [getColor()](#getColor--) | Lekéri vagy beállítja a vonal ecsetszínét. |
| [setColor(Color value)](#setColor-java.awt.Color-) | Lekéri vagy beállítja a vonal ecsetszínét. |
| [getSize()](#getSize--) | Lekéri vagy beállítja a vonal ecsetméretét pontban. |
| [setSize(Dimension2D value)](#setSize-java.awt.geom.Dimension2D-) | Lekéri vagy beállítja a vonal ecsetméretét pontban. |
| [getInkEffect()](#getInkEffect--) | Lekéri az tintaeffektus típusát (pl. Galaxy, Gold, Silver), amely meghatározza a tinta vonal vizuális stílusát. |

### getColor() {#getColor--}
```
public abstract Color getColor()
```

Lekéri vagy beállítja a vonal ecsetszínét.

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

**Visszatér:**  
java.awt.Color

### setColor(Color value) {#setColor-java.awt.Color-}
```
public abstract void setColor(Color value)
```

Lekéri vagy beállítja a vonal ecsetszínét.

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

**Paraméterek:**  
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | java.awt.Color |  |

### getSize() {#getSize--}
```
public abstract Dimension2D getSize()
```

Lekéri vagy beállítja a vonal ecsetméretét pontban.

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

**Visszatér:**  
java.awt.geom.Dimension2D

### setSize(Dimension2D value) {#setSize-java.awt.geom.Dimension2D-}
```
public abstract void setSize(Dimension2D value)
```

Lekéri vagy beállítja a vonal ecsetméretét pontban.

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

**Paraméterek:**  
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | java.awt.geom.Dimension2D |  |

### getInkEffect() {#getInkEffect--}
```
public abstract int getInkEffect()
```

Lekéri a tintaeffektus típusát (pl. Galaxy, Gold, Silver), amely meghatározza a tinta vonal vizuális stílusát. Az érték a "inkEffects" ecset tulajdonságból kerül beolvasásra. Ha nincs felismerhető effektus megadva, [InkEffectType.NotDefined](../../com.aspose.slides/inkeffecttype\#NotDefined) kerül visszaadásra.

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

**Visszatér:**  
int