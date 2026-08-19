---
title: Ink
second_title: Referensi API Aspose.Slides untuk Java
description: Mewakili objek tinta pada slide.
type: docs
url: /id/com.aspose.slides/ink/
---
**Pewarisan:**
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape), [com.aspose.slides.GraphicalObject](../../com.aspose.slides/graphicalobject)

**Semua Antarmuka yang Diimplementasikan:**
[com.aspose.slides.IInk](../../com.aspose.slides/iink)
```
public class Ink extends GraphicalObject implements IInk
```

Mewakili objek tinta pada slide.
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getTraces()](#getTraces--) | Mendapatkan semua jejak yang terdapat dalam elemen IInk [IInkTrace](../../com.aspose.slides/iinktrace). |
| [getInkEffectImages()](#getInkEffectImages--) | Mendapatkan koleksi gambar kustom yang digunakan untuk mensimulasikan efek visual untuk kuas tinta. |
### getTraces() {#getTraces--}
```
public final IInkTrace[] getTraces()
```

Mendapatkan semua jejak yang terdapat dalam elemen IInk [IInkTrace](../../com.aspose.slides/iinktrace). Hanya-baca.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      IInk ink = (IInk)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      IInkTrace[] traces = ink.getTraces();
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Mengembalikan:**
com.aspose.slides.IInkTrace[]
### getInkEffectImages() {#getInkEffectImages--}
```
public static System.Collections.Generic.Dictionary<Integer,IImage> getInkEffectImages()
```

Mendapatkan koleksi gambar kustom yang digunakan untuk mensimulasikan efek visual untuk kuas tinta. Gambar-gambar ini digunakan saat merender tinta dengan nilai [InkEffectType](../../com.aspose.slides/inkeffecttype) tertentu, seperti Galaxy, Rainbow, dll. Dengan menyediakan gambar Anda sendiri, Anda dapat mengontrol bagaimana setiap efek tinta muncul.

--------------------

> ```
> IImage image = Images.fromFile("image.png");
>  ink.getInkEffectImages().addItem(InkEffectType.Galaxy, image);
> ```


--------------------

Properti ini memungkinkan mengganti tekstur efek tinta default dengan yang didefinisikan pengguna, yang sangat berguna ketika aset default dibatasi oleh lisensi atau tidak tersedia saat runtime. Setiap entri dalam kamus harus mengaitkan nilai [InkEffectType](../../com.aspose.slides/inkeffecttype) dengan objek [IImage](../../com.aspose.slides/iimage) yang sesuai (mis., Bitmap, atau antarmuka gambar Aspose).

**Mengembalikan:**
com.aspose.ms.System.Collections.Generic.Dictionary<java.lang.Integer,com.aspose.slides.IImage>