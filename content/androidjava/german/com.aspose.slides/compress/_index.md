---
title: Compress
second_title: Aspose.Slides für Android über Java API Referenz
description: Stellt eine Gruppe von Methoden dar, die zum Komprimieren bestimmt sind.
type: docs
url: /de/com.aspose.slides/compress/
---
**Vererbung:**
java.lang.Object
```
public class Compress
```

Stellt eine Gruppe von Methoden dar, die zum Komprimieren von [Presentation](../../com.aspose.slides/presentation) vorgesehen sind.

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
| [removeUnusedMasterSlides(Presentation pres)](#removeUnusedMasterSlides-com.aspose.slides.Presentation-) | Führt die Komprimierung des [Presentation](../../com.aspose.slides/presentation) durch, indem nicht verwendete Masterfolien entfernt werden. |
| [removeUnusedLayoutSlides(Presentation pres)](#removeUnusedLayoutSlides-com.aspose.slides.Presentation-) | Führt die Komprimierung des [Presentation](../../com.aspose.slides/presentation) durch, indem nicht verwendete Layoutfolien entfernt werden. |
| [compressEmbeddedFonts(Presentation pres)](#compressEmbeddedFonts-com.aspose.slides.Presentation-) | Führt die Komprimierung des [Presentation](../../com.aspose.slides/presentation) durch, indem nicht verwendete Zeichen aus eingebetteten Schriftarten entfernt werden. |

### Compress() {#Compress--}
```
public Compress()
```

### removeUnusedMasterSlides(Presentation pres) {#removeUnusedMasterSlides-com.aspose.slides.Presentation-}
```
public static void removeUnusedMasterSlides(Presentation pres)
```

Führt die Komprimierung des [Presentation](../../com.aspose.slides/presentation) durch, indem nicht verwendete Masterfolien entfernt werden.

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

Führt die Komprimierung des [Presentation](../../com.aspose.slides/presentation) durch, indem nicht verwendete Layoutfolien entfernt werden.

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

Führt die Komprimierung des [Presentation](../../com.aspose.slides/presentation) durch, indem nicht verwendete Zeichen aus eingebetteten Schriftarten entfernt werden.

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