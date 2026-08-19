---
title: IInkBrush
second_title: Aspose.Slides untuk Referensi API Java
description: Mewakili kuas jejak.
type: docs
url: /id/com.aspose.slides/iinkbrush/
---```
public interface IInkBrush
```

Mewakili kuas jejak.
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getColor()](#getColor--) | Mendapatkan atau mengatur warna kuas untuk sebuah garis. |
| [setColor(Color value)](#setColor-java.awt.Color-) | Mendapatkan atau mengatur warna kuas untuk sebuah garis. |
| [getSize()](#getSize--) | Mendapatkan atau mengatur ukuran kuas untuk sebuah garis dalam poin. |
| [setSize(Dimension2D value)](#setSize-java.awt.geom.Dimension2D-) | Mendapatkan atau mengatur ukuran kuas untuk sebuah garis dalam poin. |
| [getInkEffect()](#getInkEffect--) | Mendapatkan tipe efek tinta (mis., Galaxy, Gold, Silver) yang menentukan gaya visual goresan tinta. |
### getColor() {#getColor--}
```
public abstract Color getColor()
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
public abstract void setColor(Color value)
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
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | java.awt.Color |  |

### getSize() {#getSize--}
```
public abstract Dimension2D getSize()
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
public abstract void setSize(Dimension2D value)
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
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | java.awt.geom.Dimension2D |  |

### getInkEffect() {#getInkEffect--}
```
public abstract int getInkEffect()
```

Mendapatkan tipe efek tinta (mis., Galaxy, Gold, Silver) yang menentukan gaya visual goresan tinta. Nilai diurai dari properti kuas "inkEffects". Jika tidak ada efek yang dikenali, [InkEffectType.NotDefined](../../com.aspose.slides/inkeffecttype\#NotDefined) dikembalikan.

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

**Mengembalikan:**
int