---
title: InkBrush
second_title: Aspose.Slides for Java API Referenciája
description: Egy inkBrush objektumot reprezentál.
type: docs
url: /hu/com.aspose.slides/inkbrush/
---
**Öröklés:**
java.lang.Object

**Minden megvalósított interfész:**
[com.aspose.slides.IInkBrush](../../com.aspose.slides/iinkbrush)
```
public class InkBrush implements IInkBrush
```

Az inkBrush objektumot reprezentálja.

## Metódusok

| Metódus | Leírás |
| --- | --- |
| [getColor()](#getColor--) | Lekéri vagy beállítja a vonal ecsetszínét. |
| [setColor(Color value)](#setColor-java.awt.Color-) | Lekéri vagy beállítja a vonal ecsetszínét. |
| [getSize()](#getSize--) | Lekéri vagy beállítja a vonal ecsetméretét pontokban. |
| [setSize(Dimension2D value)](#setSize-java.awt.geom.Dimension2D-) | Lekéri vagy beállítja a vonal ecsetméretét pontokban. |
| [getInkEffect()](#getInkEffect--) | Lekéri a tintaeffektus típusát (pl. Galaxy, Gold, Silver), amely meghatározza a tollvonás vizuális stílusát. |

### getColor() {#getColor--}
```
public final Color getColor()
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

**Visszatérési érték:**
java.awt.Color

### setColor(Color value) {#setColor-java.awt.Color-}
```
public final void setColor(Color value)
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
public final Dimension2D getSize()
```

Lekéri vagy beállítja a vonal ecsetméretét pontokban.

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

**Visszatérési érték:**
java.awt.geom.Dimension2D

### setSize(Dimension2D value) {#setSize-java.awt.geom.Dimension2D-}
```
public final void setSize(Dimension2D value)
```

Lekéri vagy beállítja a vonal ecsetméretét pontokban.

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
public final int getInkEffect()
```

Lekéri a tintaeffektus típusát (pl. Galaxy, Gold, Silver), amely meghatározza a tollvonás vizuális stílusát. Az érték a brush „inkEffects” tulajdonságából kerül beolvasásra. Ha nincs felismert effektus megadva, akkor [InkEffectType.NotDefined](../../com.aspose.slides/inkeffecttype\#NotDefined) kerül visszaadásra.

**Visszatérési érték:**
int