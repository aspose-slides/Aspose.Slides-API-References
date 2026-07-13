---
title: Compress
second_title: Aspose.Slides för Android via Java API-referens
description: Representerar en grupp metoder avsedda att komprimera .
type: docs
url: /sv/com.aspose.slides/compress/
---
**Arv:**
java.lang.Object
```
public class Compress
```

Representerar en grupp metoder avsedda att komprimera [Presentation](../../com.aspose.slides/presentation).

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
## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
| [Compress()](#Compress--) |  |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [removeUnusedMasterSlides(Presentation pres)](#removeUnusedMasterSlides-com.aspose.slides.Presentation-) | Komprimerar [Presentation](../../com.aspose.slides/presentation) genom att ta bort oanvända masterslides. |
| [removeUnusedLayoutSlides(Presentation pres)](#removeUnusedLayoutSlides-com.aspose.slides.Presentation-) | Komprimerar [Presentation](../../com.aspose.slides/presentation) genom att ta bort oanvända layoutslides. |
| [compressEmbeddedFonts(Presentation pres)](#compressEmbeddedFonts-com.aspose.slides.Presentation-) | Komprimerar [Presentation](../../com.aspose.slides/presentation) genom att ta bort oanvända tecken från inbäddade typsnitt. |
### Compress() {#Compress--}
```
public Compress()
```


### removeUnusedMasterSlides(Presentation pres) {#removeUnusedMasterSlides-com.aspose.slides.Presentation-}
```
public static void removeUnusedMasterSlides(Presentation pres)
```


Komprimerar [Presentation](../../com.aspose.slides/presentation) genom att ta bort oanvända masterslides.

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

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | Presentationens instans |

### removeUnusedLayoutSlides(Presentation pres) {#removeUnusedLayoutSlides-com.aspose.slides.Presentation-}
```
public static void removeUnusedLayoutSlides(Presentation pres)
```


Komprimerar [Presentation](../../com.aspose.slides/presentation) genom att ta bort oanvända layoutslides.

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

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | Presentationens instans |

### compressEmbeddedFonts(Presentation pres) {#compressEmbeddedFonts-com.aspose.slides.Presentation-}
```
public static void compressEmbeddedFonts(Presentation pres)
```


Komprimerar [Presentation](../../com.aspose.slides/presentation) genom att ta bort oanvända tecken från inbäddade typsnitt.

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

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | Presentationens instans |