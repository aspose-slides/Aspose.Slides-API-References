---
title: Compress
second_title: Aspose.Slides Java API referencia
description: Egy olyan metóduscsoportot képvisel, amelynek célja a tömörítés.
type: docs
url: /hu/com.aspose.slides/compress/
---
**Öröklődés:**
java.lang.Object
```
public class Compress
```

Egy olyan metóduscsoportot képvisel, amelynek célja a [Presentation](../../com.aspose.slides/presentation) tömörítése.

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
| [compressPresentation(Presentation presentation)](#compressPresentation-com.aspose.slides.Presentation-) | Egy prezentáció méretét csökkenti az összes elérhető tömörítési lépés alkalmazásával:

 *  Eltávolítja a nem használt minta-diákat \#removeUnusedMasterSlides(Presentation).removeUnusedMasterSlides(Presentation).
 *  Eltávolítja a nem használt elrendezés-diákat \#removeUnusedLayoutSlides(Presentation).removeUnusedLayoutSlides(Presentation).
 *  Csak a beágyazott betűtípusokban ténylegesen használt glifeket tartja meg \#compressEmbeddedFonts(Presentation).compressEmbeddedFonts(Presentation).
 *  150 DPI-re csökkenti a képek felbontását és törli a képek levágott részeit \#compressImages(IPresentation,int).compressImages(IPresentation,int). |
| [removeUnusedMasterSlides(Presentation pres)](#removeUnusedMasterSlides-com.aspose.slides.Presentation-) | A [Presentation](../../com.aspose.slides/presentation) tömörítését végzi úgy, hogy eltávolítja a nem használt minta-diákat. |
| [removeUnusedLayoutSlides(Presentation pres)](#removeUnusedLayoutSlides-com.aspose.slides.Presentation-) | A [Presentation](../../com.aspose.slides/presentation) tömörítését végzi úgy, hogy eltávolítja a nem használt elrendezés-diákat. |
| [compressEmbeddedFonts(Presentation pres)](#compressEmbeddedFonts-com.aspose.slides.Presentation-) | A [Presentation](../../com.aspose.slides/presentation) tömörítését végzi úgy, hogy eltávolítja a beágyazott betűtípusokból a nem használt karaktereket. |
| [compressImages(IPresentation presentation, int resolution)](#compressImages-com.aspose.slides.IPresentation-int-) | Csökkenti a prezentációban lévő képek felbontását és törli a levágott részeiket, hasonlóan a PowerPoint „Compress Pictures” funkciójához, amely minden képre alkalmazva van. |
### Compress() {#Compress--}
```
public Compress()
```


### compressPresentation(Presentation presentation) {#compressPresentation-com.aspose.slides.Presentation-}
```
public static void compressPresentation(Presentation presentation)
```


Egy prezentáció méretét csökkenti az összes elérhető tömörítési lépés alkalmazásával:

 *  Eltávolítja a nem használt minta-diákat \#removeUnusedMasterSlides(Presentation).removeUnusedMasterSlides(Presentation).
 *  Eltávolítja a nem használt elrendezés-diákat \#removeUnusedLayoutSlides(Presentation).removeUnusedLayoutSlides(Presentation).
 *  Csak a beágyazott betűtípusokban ténylegesen használt glifeket tartja meg \#compressEmbeddedFonts(Presentation).compressEmbeddedFonts(Presentation).
 *  150 DPI-re csökkenti a képek felbontását és törli a levágott részeit \#compressImages(IPresentation,int).compressImages(IPresentation,int).

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      Compress.compressPresentation(pres);
> 
>      pres.save("pres-out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| presentation | [Presentation](../../com.aspose.slides/presentation) | A tömörítendő prezentáció. |

--------------------

A tömörítés testreszabásához, például más kép felbontás használatához vagy egy lépés kihagyásához, hívja meg a fent felsorolt metódusokat egyenként ehelyett. A képek levágott részei véglegesen eltávolításra kerülnek és a PowerPointban nem állíthatók vissza. |

### removeUnusedMasterSlides(Presentation pres) {#removeUnusedMasterSlides-com.aspose.slides.Presentation-}
```
public static void removeUnusedMasterSlides(Presentation pres)
```


A [Presentation](../../com.aspose.slides/presentation) tömörítését végzi úgy, hogy eltávolítja a nem használt minta-diákat.

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


A [Presentation](../../com.aspose.slides/presentation) tömörítését végzi úgy, hogy eltávolítja a nem használt elrendezés-diákat.

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


A [Presentation](../../com.aspose.slides/presentation) tömörítését végzi úgy, hogy eltávolítja a beágyazott betűtípusokból a nem használt karaktereket.

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

### compressImages(IPresentation presentation, int resolution) {#compressImages-com.aspose.slides.IPresentation-int-}
```
public static void compressImages(IPresentation presentation, int resolution)
```


Csökkenti a prezentációban lévő képek felbontását és törli a levágott részeiket, hasonlóan a PowerPoint "Compress Pictures" funkciójához, amely minden képre alkalmazva van. A diákon, elrendezés-diákon és minta-diákon lévő képek feldolgozásra kerülnek, beleértve a csoportos alakzatokban lévő képeket és az alakzatok képkitöltéseit.

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      Compress.compressImages(pres, PicturesCompression.Dpi150);
> 
>      pres.save("pres-out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| presentation | [IPresentation](../../com.aspose.slides/ipresentation) | A feldolgozandó prezentáció. |
| resolution | int | Cél felbontás a kép megjelenítési méretéhez viszonyítva. [PicturesCompression.DocumentResolution](../../com.aspose.slides/picturescompression\#DocumentResolution) változatlanul hagyja a képeket. |

A már a cél felbontásnál vagy annál alacsonyabb felbontású képek változatlanul maradnak; a képeket soha nem nagyítják fel.

Nem kerül feldolgozásra: dia háttér, táblázat cella kitöltések, diagramok, SmartArt, GIF képek (az animáció megőrzése érdekében), SVG és metafájl (EMF/WMF) képek.

A levágott területek véglegesen eltávolításra kerülnek és a PowerPointban nem állíthatók helyre. |