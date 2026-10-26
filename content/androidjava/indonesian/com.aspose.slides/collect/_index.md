---
title: Collect
second_title: Aspose.Slides untuk Android melalui Referensi API Java
description: Mewakili sekumpulan metode yang dimaksudkan untuk mengumpulkan objek model dari berbagai tipe .
type: docs
url: /id/com.aspose.slides/collect/
---
**Pewarisan:**
java.lang.Object
```
public class Collect
```

Mewakili sekumpulan metode yang dimaksudkan untuk mengumpulkan objek model dari berbagai tipe dari [Presentation](../../com.aspose.slides/presentation).

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      for (IShape shape : Collect.shapes(pres))
>      {
>          // ... ubah format shape atau properti lainnya
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [Collect()](#Collect--) |  |
## Metode

| Metode | Deskripsi |
| --- | --- |
| [shapes(Presentation pres)](#shapes-com.aspose.slides.Presentation-) | Mengumpulkan semua instance dari [Shape](../../com.aspose.slides/shape) di [Presentation](../../com.aspose.slides/presentation). |
### Collect() {#Collect--}
```
public Collect()
```


### shapes(Presentation pres) {#shapes-com.aspose.slides.Presentation-}
```
public static System.Collections.Generic.IGenericEnumerable<Shape> shapes(Presentation pres)
```


Mengumpulkan semua instance dari [Shape](../../com.aspose.slides/shape) di [Presentation](../../com.aspose.slides/presentation).

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      for (IShape shape : Collect.shapes(pres))
>      {
>          // jika shape adalah AutoShape, tambahkan border hitam solid
>          if (shape instanceof AutoShape)
>          {
>              AutoShape autoShape = (AutoShape)shape;
>              autoShape.getLineFormat().setStyle(LineStyle.Single);
>              autoShape.getLineFormat().setWidth(10f);
>              autoShape.getLineFormat().getFillFormat().setFillType(FillType.Solid);
>              autoShape.getLineFormat().getFillFormat().getSolidFillColor().setColor(Color.black);
>          }
>      }
>      pres.save("pres-out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | Presentasi untuk mengumpulkan bentuk |

**Mengembalikan:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable<com.aspose.slides.Shape> - Koleksi semua bentuk yang terdapat dalam presentasi