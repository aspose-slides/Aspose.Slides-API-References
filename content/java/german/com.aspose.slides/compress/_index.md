---
title: Compress
second_title: Aspose.Slides für Java API-Referenz
description: Stellt eine Gruppe von Methoden dar, die dazu bestimmt sind, zu komprimieren.
type: docs
url: /de/com.aspose.slides/compress/
---
**Vererbung:**
java.lang.Object
```
public class Compress
```

Stellt eine Gruppe von Methoden dar, die dazu bestimmt sind, [Presentation](../../com.aspose.slides/presentation) zu komprimieren.

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
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [Compress()](#Compress--) |  |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [removeUnusedMasterSlides(Presentation pres)](#removeUnusedMasterSlides-com.aspose.slides.Presentation-) | Komprimiert [Presentation](../../com.aspose.slides/presentation), indem nicht verwendete Masterfolien entfernt werden. |
| [removeUnusedLayoutSlides(Presentation pres)](#removeUnusedLayoutSlides-com.aspose.slides.Presentation-) | Komprimiert [Presentation](../../com.aspose.slides/presentation), indem nicht verwendete Layoutfolien entfernt werden. |
| [compressEmbeddedFonts(Presentation pres)](#compressEmbeddedFonts-com.aspose.slides.Presentation-) | Komprimiert [Presentation](../../com.aspose.slides/presentation), indem nicht verwendete Zeichen aus eingebetteten Schriften entfernt werden. |
### Compress() {#Compress--}
```
public Compress()
```

### removeUnusedMasterSlides(Presentation pres) {#removeUnusedMasterSlides-com.aspose.slides.Presentation-}
```
public static void removeUnusedMasterSlides(Presentation pres)
```

Komprimiert [Presentation](../../com.aspose.slides/presentation), indem nicht verwendete Masterfolien entfernt werden.

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

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | Die Präsentationsinstanz |

### removeUnusedLayoutSlides(Presentation pres) {#removeUnusedLayoutSlides-com.aspose.slides.Presentation-}
```
public static void removeUnusedLayoutSlides(Presentation pres)
```

Komprimiert [Presentation](../../com.aspose.slides/presentation), indem nicht verwendete Layoutfolien entfernt werden.

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

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | Die Präsentationsinstanz |

### compressEmbeddedFonts(Presentation pres) {#compressEmbeddedFonts-com.aspose.slides.Presentation-}
```
public static void compressEmbeddedFonts(Presentation pres)
```

Komprimiert [Presentation](../../com.aspose.slides/presentation), indem nicht verwendete Zeichen aus eingebetteten Schriften entfernt werden.

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

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | Die Präsentationsinstanz |