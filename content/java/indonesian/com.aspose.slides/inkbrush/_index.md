---
title: InkBrush
second_title: Referensi API Aspose.Slides untuk Java
description: Mewakili objek inkBrush.
type: docs
url: /id/com.aspose.slides/inkbrush/
---
**Pewarisan:**
java.lang.Object

**Semua Interface yang Diimplementasikan:**
[com.aspose.slides.IInkBrush](../../com.aspose.slides/iinkbrush)
```
public class InkBrush implements IInkBrush
```

Mewakili objek inkBrush.
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getColor()](#getColor--) | Mendapatkan atau mengatur warna kuas untuk sebuah garis. |
| [setColor(Color value)](#setColor-java.awt.Color-) | Mendapatkan atau mengatur warna kuas untuk sebuah garis. |
| [getSize()](#getSize--) | Mendapatkan atau mengatur ukuran kuas untuk sebuah garis dalam poin. |
| [setSize(Dimension2D value)](#setSize-java.awt.geom.Dimension2D-) | Mendapatkan atau mengatur ukuran kuas untuk sebuah garis dalam poin. |
| [getInkEffect()](#getInkEffect--) | Mendapatkan tipe efek tinta (misalnya, Galaxy, Gold, Silver) yang menentukan gaya visual goresan tinta. |
### getColor() {#getColor--}
```
public final Color getColor()
```


Mendapatkan atau mengatur warna kuas untuk sebuah garis.

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

**Mengembalikan:**
java.awt.Color
### setColor(Color value) {#setColor-java.awt.Color-}
```
public final void setColor(Color value)
```


Mendapatkan atau mengatur warna kuas untuk sebuah garis.

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

**Parameter:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| value | java.awt.Color |  |

### getSize() {#getSize--}
```
public final Dimension2D getSize()
```


Mendapatkan atau mengatur ukuran kuas untuk sebuah garis dalam poin.

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

**Mengembalikan:**
java.awt.geom.Dimension2D
### setSize(Dimension2D value) {#setSize-java.awt.geom.Dimension2D-}
```
public final void setSize(Dimension2D value)
```


Mendapatkan atau mengatur ukuran kuas untuk sebuah garis dalam poin.

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

**Parameter:**
| Parameter | Type | Deskripsi |
| --- | --- | --- |
| value | java.awt.geom.Dimension2D |  |

### getInkEffect() {#getInkEffect--}
```
public final int getInkEffect()
```


Mendapatkan tipe efek tinta (misalnya, Galaxy, Gold, Silver) yang menentukan gaya visual goresan tinta. Nilai diparsir dari properti brush "inkEffects". Jika tidak ada efek yang dikenali yang ditentukan, [InkEffectType.NotDefined](../../com.aspose.slides/inkeffecttype\#NotDefined) dikembalikan.

**Mengembalikan:**
int