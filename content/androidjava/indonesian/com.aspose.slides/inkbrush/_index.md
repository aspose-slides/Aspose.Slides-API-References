---
title: InkBrush
second_title: Aspose.Slides untuk Android melalui Referensi API Java
description: Mewakili objek inkBrush.
type: docs
url: /id/com.aspose.slides/inkbrush/
---
**Pewarisan:**
java.lang.Object

**Semua Antarmuka yang Diimplementasikan:**
[com.aspose.slides.IInkBrush](../../com.aspose.slides/iinkbrush)
```
public class InkBrush implements IInkBrush
```

Mewakili objek inkBrush.
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getColor()](#getColor--) | Mendapatkan atau mengatur warna kuas untuk sebuah garis. |
| [setColor(Integer value)](#setColor-java.lang.Integer-) | Mendapatkan atau mengatur warna kuas untuk sebuah garis. |
| [getSize()](#getSize--) | Mendapatkan atau mengatur ukuran kuas untuk sebuah garis dalam satuan poin. |
| [setSize(SizeF value)](#setSize-com.aspose.slides.android.SizeF-) | Mendapatkan atau mengatur ukuran kuas untuk sebuah garis dalam satuan poin. |
| [getInkEffect()](#getInkEffect--) | Mendapatkan tipe efek tinta (misalnya, Galaxy, Gold, Silver) yang menentukan gaya visual goresan tinta. |
### getColor() {#getColor--}
```
public final Integer getColor()
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
public final void setColor(Integer value)
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
public final SizeF getSize()
```


Mendapatkan atau mengatur ukuran kuas untuk sebuah garis dalam satuan poin.

--------------------

> ```
> Contoh:
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
public final void setSize(SizeF value)
```


Mendapatkan atau mengatur ukuran kuas untuk sebuah garis dalam satuan poin.

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
public final int getInkEffect()
```


Mendapatkan tipe efek tinta (misalnya, Galaxy, Gold, Silver) yang menentukan gaya visual goresan tinta. Nilai diurai dari properti kuas "inkEffects". Jika tidak ada efek yang dikenali, [InkEffectType.NotDefined](../../com.aspose.slides/inkeffecttype\#NotDefined) dikembalikan.

**Mengembalikan:**
int