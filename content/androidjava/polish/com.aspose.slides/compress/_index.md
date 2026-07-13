---
title: Compress
second_title: Aspose.Slides dla Androida poprzez referencję API Java
description: Reprezentuje grupę metod przeznaczonych do kompresji.
type: docs
url: /pl/com.aspose.slides/compress/
---
**Dziedziczenie:**
java.lang.Object
```
public class Compress
```

Reprezentuje grupę metod przeznaczonych do kompresji [Presentation](../../com.aspose.slides/presentation).

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      Compress.removeUnusedMasterSlides(pres);
> 
>      pres.save("pres-out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```
## Konstruktory

| Konstruktor | Opis |
| --- | --- |
| [Compress()](#Compress--) |  |
## Metody

| Metoda | Opis |
| --- | --- |
| [removeUnusedMasterSlides(Presentation pres)](#removeUnusedMasterSlides-com.aspose.slides.Presentation-) | Wykonuje kompresję [Presentation](../../com.aspose.slides/presentation) poprzez usunięcie nieużywanych slajdów master. |
| [removeUnusedLayoutSlides(Presentation pres)](#removeUnusedLayoutSlides-com.aspose.slides.Presentation-) | Wykonuje kompresję [Presentation](../../com.aspose.slides/presentation) poprzez usunięcie nieużywanych slajdów układu. |
| [compressEmbeddedFonts(Presentation pres)](#compressEmbeddedFonts-com.aspose.slides.Presentation-) | Wykonuje kompresję [Presentation](../../com.aspose.slides/presentation) poprzez usunięcie nieużywanych znaków z osadzonych czcionek. |
### Compress() {#Compress--}
```
public Compress()
```


### removeUnusedMasterSlides(Presentation pres) {#removeUnusedMasterSlides-com.aspose.slides.Presentation-}
```
public static void removeUnusedMasterSlides(Presentation pres)
```


Wykonuje kompresję [Presentation](../../com.aspose.slides/presentation) poprzez usunięcie nieużywanych slajdów master.

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      Compress.removeUnusedMasterSlides(pres);
> 
>      pres.save("pres-out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | Instancja prezentacji |

### removeUnusedLayoutSlides(Presentation pres) {#removeUnusedLayoutSlides-com.aspose.slides.Presentation-}
```
public static void removeUnusedLayoutSlides(Presentation pres)
```


Wykonuje kompresję [Presentation](../../com.aspose.slides/presentation) poprzez usunięcie nieużywanych slajdów układu.

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      Compress.removeUnusedLayoutSlides(pres);
> 
>      pres.save("pres-out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | Instancja prezentacji |

### compressEmbeddedFonts(Presentation pres) {#compressEmbeddedFonts-com.aspose.slides.Presentation-}
```
public static void compressEmbeddedFonts(Presentation pres)
```


Wykonuje kompresję [Presentation](../../com.aspose.slides/presentation) poprzez usunięcie nieużywanych znaków z osadzonych czcionek.

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      Compress.compressEmbeddedFonts(pres);
> 
>      pres.save("pres-out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | Instancja prezentacji |