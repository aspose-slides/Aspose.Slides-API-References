---
title: Compress
second_title: Aspose.Slides voor Android via Java API-referentie
description: Stelt een groep methoden voor die bedoeld zijn om te comprimeren.
type: docs
url: /nl/com.aspose.slides/compress/
---
**Erfenis:**
java.lang.Object
```
public class Compress
```

Stelt een groep methoden voor die bedoeld zijn om [Presentation](../../com.aspose.slides/presentation) te comprimeren.

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
## Constructoren

| Constructor | Beschrijving |
| --- | --- |
| [Compress()](#Compress--) |  |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [removeUnusedMasterSlides(Presentation pres)](#removeUnusedMasterSlides-com.aspose.slides.Presentation-) | Voert compressie uit van de [Presentation](../../com.aspose.slides/presentation) door ongebruikte masterslides te verwijderen. |
| [removeUnusedLayoutSlides(Presentation pres)](#removeUnusedLayoutSlides-com.aspose.slides.Presentation-) | Voert compressie uit van de [Presentation](../../com.aspose.slides/presentation) door ongebruikte layoutslides te verwijderen. |
| [compressEmbeddedFonts(Presentation pres)](#compressEmbeddedFonts-com.aspose.slides.Presentation-) | Voert compressie uit van de [Presentation](../../com.aspose.slides/presentation) door ongebruikte tekens uit ingesloten lettertypen te verwijderen. |
### Compress() {#Compress--}
```
public Compress()
```


### removeUnusedMasterSlides(Presentation pres) {#removeUnusedMasterSlides-com.aspose.slides.Presentation-}
```
public static void removeUnusedMasterSlides(Presentation pres)
```


Voert compressie uit van de [Presentation](../../com.aspose.slides/presentation) door ongebruikte masterslides te verwijderen.

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

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | De presentatie-instantie |

### removeUnusedLayoutSlides(Presentation pres) {#removeUnusedLayoutSlides-com.aspose.slides.Presentation-}
```
public static void removeUnusedLayoutSlides(Presentation pres)
```


Voert compressie uit van de [Presentation](../../com.aspose.slides/presentation) door ongebruikte layoutslides te verwijderen.

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

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | De presentatie-instantie |

### compressEmbeddedFonts(Presentation pres) {#compressEmbeddedFonts-com.aspose.slides.Presentation-}
```
public static void compressEmbeddedFonts(Presentation pres)
```


Voert compressie uit van de [Presentation](../../com.aspose.slides/presentation) door ongebruikte tekens uit ingesloten lettertypen te verwijderen.

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

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | De presentatie-instantie |