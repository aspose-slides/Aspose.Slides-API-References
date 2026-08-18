---
title: Compress
second_title: Aspose.Slides a Java API hivatkozása
description: Olyan módszercsoportot képvisel, amely a tömörítésre szolgál.
type: docs
url: /hu/com.aspose.slides/compress/
---
**Öröklés:**
java.lang.Object
```
public class Compress
```

Olyan módszercsoportot képvisel, amely a [Presentation](../../com.aspose.slides/presentation) tömörítésére szolgál.

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
| [removeUnusedMasterSlides(Presentation pres)](#removeUnusedMasterSlides-com.aspose.slides.Presentation-) | A [Presentation](../../com.aspose.slides/presentation) tömörítését végzi felhasználatlan mesterdiák eltávolításával. |
| [removeUnusedLayoutSlides(Presentation pres)](#removeUnusedLayoutSlides-com.aspose.slides.Presentation-) | A [Presentation](../../com.aspose.slides/presentation) tömörítését végzi felhasználatlan elrendezési diákok eltávolításával. |
| [compressEmbeddedFonts(Presentation pres)](#compressEmbeddedFonts-com.aspose.slides.Presentation-) | A [Presentation](../../com.aspose.slides/presentation) tömörítését végzi a beágyazott betűtípusokból származó felhasználatlan karakterek eltávolításával. |
### Compress() {#Compress--}
```
public Compress()
```

### removeUnusedMasterSlides(Presentation pres) {#removeUnusedMasterSlides-com.aspose.slides.Presentation-}
```
public static void removeUnusedMasterSlides(Presentation pres)
```

A [Presentation](../../com.aspose.slides/presentation) tömörítését végzi felhasználatlan mesterdiák eltávolításával.

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

A [Presentation](../../com.aspose.slides/presentation) tömörítését végzi felhasználatlan elrendezési diákok eltávolításával.

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

A [Presentation](../../com.aspose.slides/presentation) tömörítését végzi a beágyazott betűtípusokból származó felhasználatlan karakterek eltávolításával.

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