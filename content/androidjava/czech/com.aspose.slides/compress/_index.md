---
title: Compress
second_title: Aspose.Slides pro Android pomocí Java API Reference
description: Představuje skupinu metod určených ke kompresi.
type: docs
url: /cs/com.aspose.slides/compress/
---
**Dědičnost:**
java.lang.Object
```
public class Compress
```

Představuje skupinu metod určených ke kompresi [Presentation](../../com.aspose.slides/presentation).

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

| Konstruktor | Popis |
| --- | --- |
| [Compress()](#Compress--) |  |
## Metody

| Metoda | Popis |
| --- | --- |
| [removeUnusedMasterSlides(Presentation pres)](#removeUnusedMasterSlides-com.aspose.slides.Presentation-) | Provádí kompresi [Presentation](../../com.aspose.slides/presentation) odstraněním nepoužívaných hlavních snímků. |
| [removeUnusedLayoutSlides(Presentation pres)](#removeUnusedLayoutSlides-com.aspose.slides.Presentation-) | Provádí kompresi [Presentation](../../com.aspose.slides/presentation) odstraněním nepoužívaných rozložení snímků. |
| [compressEmbeddedFonts(Presentation pres)](#compressEmbeddedFonts-com.aspose.slides.Presentation-) | Provádí kompresi [Presentation](../../com.aspose.slides/presentation) odstraněním nepoužívaných znaků z vložených fontů. |
### Compress() {#Compress--}
```
public Compress()
```


### removeUnusedMasterSlides(Presentation pres) {#removeUnusedMasterSlides-com.aspose.slides.Presentation-}
```
public static void removeUnusedMasterSlides(Presentation pres)
```


Provádí kompresi [Presentation](../../com.aspose.slides/presentation) odstraněním nepoužívaných hlavních snímků.

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
| Parametr | Typ | Popis |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | Instance prezentace |

### removeUnusedLayoutSlides(Presentation pres) {#removeUnusedLayoutSlides-com.aspose.slides.Presentation-}
```
public static void removeUnusedLayoutSlides(Presentation pres)
```


Provádí kompresi [Presentation](../../com.aspose.slides/presentation) odstraněním nepoužívaných rozložení snímků.

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
| Parametr | Typ | Popis |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | Instance prezentace |

### compressEmbeddedFonts(Presentation pres) {#compressEmbeddedFonts-com.aspose.slides.Presentation-}
```
public static void compressEmbeddedFonts(Presentation pres)
```


Provádí kompresi [Presentation](../../com.aspose.slides/presentation) odstraněním nepoužívaných znaků z vložených fontů.

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
| Parametr | Typ | Popis |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | Instance prezentace |