---
title: Compress
second_title: Aspose.Slides Androidra a Java API-referencia segítségével
description: Egy olyan módszercsoportot ábrázol, amely a tömörítésre szolgál.
type: docs
url: /hu/com.aspose.slides/compress/
---
**Öröklés:**
java.lang.Object
```
public class Compress
```

Ábrázol egy módszercsoportot, amely a [Presentation](../../com.aspose.slides/presentation) tömörítésére szolgál.

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
## Konstruktorok

| Konstruktor | Leírás |
| --- | --- |
| [Compress()](#Compress--) |  |
## Metódusok

| Metódus | Leírás |
| --- | --- |
| [removeUnusedMasterSlides(Presentation pres)](#removeUnusedMasterSlides-com.aspose.slides.Presentation-) | Tömöríti a [Presentation](../../com.aspose.slides/presentation)-t azáltal, hogy eltávolítja a nem használt mester diaképeket. |
| [removeUnusedLayoutSlides(Presentation pres)](#removeUnusedLayoutSlides-com.aspose.slides.Presentation-) | Tömöríti a [Presentation](../../com.aspose.slides/presentation)-t azáltal, hogy eltávolítja a nem használt elrendezés diaképeket. |
| [compressEmbeddedFonts(Presentation pres)](#compressEmbeddedFonts-com.aspose.slides.Presentation-) | Tömöríti a [Presentation](../../com.aspose.slides/presentation)-t azáltal, hogy eltávolítja a beágyazott betűtípusokból a nem használt karaktereket. |
### Compress() {#Compress--}
```
public Compress()
```


### removeUnusedMasterSlides(Presentation pres) {#removeUnusedMasterSlides-com.aspose.slides.Presentation-}
```
public static void removeUnusedMasterSlides(Presentation pres)
```


Tömöríti a [Presentation](../../com.aspose.slides/presentation)-t azáltal, hogy eltávolítja a nem használt mester diaképeket.

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

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | A prezentáció példánya |

### removeUnusedLayoutSlides(Presentation pres) {#removeUnusedLayoutSlides-com.aspose.slides.Presentation-}
```
public static void removeUnusedLayoutSlides(Presentation pres)
```


Tömöríti a [Presentation](../../com.aspose.slides/presentation)-t azáltal, hogy eltávolítja a nem használt elrendezés diaképeket.

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

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | A prezentáció példánya |

### compressEmbeddedFonts(Presentation pres) {#compressEmbeddedFonts-com.aspose.slides.Presentation-}
```
public static void compressEmbeddedFonts(Presentation pres)
```


Tömöríti a [Presentation](../../com.aspose.slides/presentation)-t azáltal, hogy eltávolítja a beágyazott betűtípusokból a nem használt karaktereket.

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

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | A prezentáció példánya |