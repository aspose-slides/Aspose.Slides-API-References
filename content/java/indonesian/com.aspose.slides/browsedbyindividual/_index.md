---
title: BrowsedByIndividual
second_title: Referensi API Aspose.Slides untuk Java
description: Ditelusuri per jendela individu
type: docs
url: /id/com.aspose.slides/browsedbyindividual/
---
**Pewarisan:**
java.lang.Object, [com.aspose.slides.SlideShowType](../../com.aspose.slides/slideshowtype)
```
public class BrowsedByIndividual extends SlideShowType
```

Ditelusuri oleh individu (jendela)

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      pres.getSlideShowSettings().setSlideShowType(new BrowsedByIndividual());
>      pres.save("pres.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```
## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [BrowsedByIndividual()](#BrowsedByIndividual--) | Menginisialisasi instance baru dari kelas BrowsedByIndividual. |
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getShowScrollbar()](#getShowScrollbar--) | Tampilkan Bilah Gulir di Jendela |
| [setShowScrollbar(boolean value)](#setShowScrollbar-boolean-) | Tampilkan Bilah Gulir di Jendela |
### BrowsedByIndividual() {#BrowsedByIndividual--}
```
public BrowsedByIndividual()
```


Menginisialisasi instance baru dari kelas BrowsedByIndividual.

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      pres.getSlideShowSettings().setSlideShowType(new BrowsedByIndividual());
>      pres.save("pres.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

### getShowScrollbar() {#getShowScrollbar--}
```
public final boolean getShowScrollbar()
```


Tampilkan Bilah Gulir di Jendela

**Mengembalikan:**
boolean
### setShowScrollbar(boolean value) {#setShowScrollbar-boolean-}
```
public final void setShowScrollbar(boolean value)
```


Tampilkan Bilah Gulir di Jendela

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | boolean |  |