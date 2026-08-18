---
title: IInkBrush
second_title: Aspose.Slides for Java API Reference
description: Represents trace brush.
type: docs
url: /tr/com.aspose.slides/iinkbrush/
---```
public interface IInkBrush
```

İz fırçasını temsil eder.
## Metodlar

| Metod | Açıklama |
| --- | --- |
| [getColor()](#getColor--) | Satır için fırça rengini alır veya ayarlar. |
| [setColor(Color value)](#setColor-java.awt.Color-) | Satır için fırça rengini alır veya ayarlar. |
| [getSize()](#getSize--) | Satır için fırça boyutunu nokta cinsinden alır veya ayarlar. |
| [setSize(Dimension2D value)](#setSize-java.awt.geom.Dimension2D-) | Satır için fırça boyutunu nokta cinsinden alır veya ayarlar. |
| [getInkEffect()](#getInkEffect--) | Mürekkep vuruşunun görsel stilini tanımlayan mürekkep efekti türünü (ör. Galaxy, Gold, Silver) alır. |
### getColor() {#getColor--}
```
public abstract Color getColor()
```

Satır için fırça rengini alır veya ayarlar.

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


**Döndürür:**
java.awt.Color
### setColor(Color value) {#setColor-java.awt.Color-}
```
public abstract void setColor(Color value)
```

Satır için fırça rengini alır veya ayarlar.

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


**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | java.awt.Color |  |
### getSize() {#getSize--}
```
public abstract Dimension2D getSize()
```

Satır için fırça boyutunu nokta cinsinden alır veya ayarlar.

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


**Döndürür:**
java.awt.geom.Dimension2D
### setSize(Dimension2D value) {#setSize-java.awt.geom.Dimension2D-}
```
public abstract void setSize(Dimension2D value)
```

Satır için fırça boyutunu nokta cinsinden alır veya ayarlar.

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

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | java.awt.geom.Dimension2D |  |
### getInkEffect() {#getInkEffect--}
```
public abstract int getInkEffect()
```

Mürekkep vuruşunun görsel stilini tanımlayan mürekkep efekti türünü (ör. Galaxy, Gold, Silver) alır. Değer, fırça özelliği “inkEffects”ten ayrıştırılır. Tanınan bir efekt belirtilmezse [InkEffectType.NotDefined](../../com.aspose.slides/inkeffecttype\#NotDefined) döndürülür.

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

**Döndürür:**
int