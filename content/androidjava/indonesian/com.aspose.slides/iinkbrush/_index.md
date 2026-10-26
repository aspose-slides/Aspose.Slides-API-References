---
title: IInkBrush
second_title: Aspose.Slides for Android via Java API Reference
description: Represents trace brush.
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
| [setColor(Integer value)](#setColor-java.lang.Integer-) | Mendapatkan atau mengatur warna kuas untuk sebuah garis. |
| [getSize()](#getSize--) | Mendapatkan atau mengatur ukuran kuas untuk sebuah garis dalam titik. |
| [setSize(SizeF value)](#setSize-com.aspose.slides.android.SizeF-) | Mendapatkan atau mengatur ukuran kuas untuk sebuah garis dalam titik. |
| [getInkEffect()](#getInkEffect--) | Mendapatkan tipe efek tinta (misalnya, Galaxy, Gold, Silver) yang menentukan gaya visual goresan tinta. |
### getColor() {#getColor--}
```
public abstract Integer getColor()
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
java.lang.Integer
### setColor(Integer value) {#setColor-java.lang.Integer-}
```
public abstract void setColor(Integer value)
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
| value | java.lang.Integer |  |

### getSize() {#getSize--}
```
public abstract SizeF getSize()
```

Mendapatkan atau mengatur ukuran kuas untuk sebuah garis dalam titik.

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


**Mengembalikan:**
[SizeF](../../com.aspose.slides.android/sizef)
### setSize(SizeF value) {#setSize-com.aspose.slides.android.SizeF-}
```
public abstract void setSize(SizeF value)
```

Mendapatkan atau mengatur ukuran kuas untuk sebuah garis dalam titik.

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

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [SizeF](../../com.aspose.slides.android/sizef) |  |

### getInkEffect() {#getInkEffect--}
```
public abstract int getInkEffect()
```

Mendapatkan tipe efek tinta (misalnya, Galaxy, Gold, Silver) yang menentukan gaya visual goresan tinta. Nilai diparsing dari properti kuas "inkEffects". Jika tidak ada efek yang dikenali, [InkEffectType.NotDefined](../../com.aspose.slides/inkeffecttype\#NotDefined) dikembalikan.

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