---
title: InkBrush
second_title: Aspose.Slides için Java API Referansı
description: Bir inkBrush nesnesini temsil eder.
type: docs
url: /tr/com.aspose.slides/inkbrush/
---
**Kalıtım:**
java.lang.Object

**Uygulanan Tüm Arabirimler:**
[com.aspose.slides.IInkBrush](../../com.aspose.slides/iinkbrush)
```
public class InkBrush implements IInkBrush
```

Bir inkBrush nesnesini temsil eder.
## Metotlar

| Metod | Açıklama |
| --- | --- |
| [getColor()](#getColor--) | Bir satır için fırça rengini alır veya ayarlar. |
| [setColor(Color value)](#setColor-java.awt.Color-) | Bir satır için fırça rengini alır veya ayarlar. |
| [getSize()](#getSize--) | Bir satır için fırça boyutunu puan cinsinden alır veya ayarlar. |
| [setSize(Dimension2D value)](#setSize-java.awt.geom.Dimension2D-) | Bir satır için fırça boyutunu puan cinsinden alır veya ayarlar. |
| [getInkEffect()](#getInkEffect--) | İnk vuruşunun görsel stilini tanımlayan ink efekti türünü (ör. Galaxy, Gold, Silver) alır. |
### getColor() {#getColor--}
```
public final Color getColor()
```

Bir satır için fırça rengini alır veya ayarlar.

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
public final void setColor(Color value)
```

Bir satır için fırça rengini alır veya ayarlar.

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
public final Dimension2D getSize()
```

Bir satır için fırça boyutunu puan cinsinden alır veya ayarlar.

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
public final void setSize(Dimension2D value)
```

Bir satır için fırça boyutunu puan cinsinden alır veya ayarlar.

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
public final int getInkEffect()
```

Ink efekti türünü (ör. Galaxy, Gold, Silver) alır ve bu, ink vuruşunun görsel stilini tanımlar. Değer, fırça özelliği "inkEffects" üzerinden ayrıştırılır. Tanınan bir efekt belirtilmemişse, [InkEffectType.NotDefined](../../com.aspose.slides/inkeffecttype\#NotDefined) döndürülür.

**Döndürür:**
int