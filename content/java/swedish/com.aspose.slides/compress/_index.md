---
title: Compress
second_title: Aspose.Slides för Java API-referens
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

| Konstruktor | Beskrivning |
| --- | --- |
| [Compress()](#Compress--) |  |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [compressPresentation(Presentation presentation)](#compressPresentation-com.aspose.slides.Presentation-) | Minskar storleken på en presentation genom att tillämpa alla tillgängliga komprimeringssteg:

 *  Tar bort oanvända masterbilder \#removeUnusedMasterSlides(Presentation).removeUnusedMasterSlides(Presentation).
 *  Tar bort oanvända layoutbilder \#removeUnusedLayoutSlides(Presentation).removeUnusedLayoutSlides(Presentation).
 *  Behåller endast de glyfer som faktiskt används i inbäddade teckensnitt \#compressEmbeddedFonts(Presentation).compressEmbeddedFonts(Presentation).
 *  Minskar bildens upplösning till 150 DPI och tar bort beskurna områden i bilder \#compressImages(IPresentation,int).compressImages(IPresentation,int). |
| [removeUnusedMasterSlides(Presentation pres)](#removeUnusedMasterSlides-com.aspose.slides.Presentation-) | Komprimerar [Presentation](../../com.aspose.slides/presentation) genom att ta bort oanvända masterbilder. |
| [removeUnusedLayoutSlides(Presentation pres)](#removeUnusedLayoutSlides-com.aspose.slides.Presentation-) | Komprimerar [Presentation](../../com.aspose.slides/presentation) genom att ta bort oanvända layoutbilder. |
| [compressEmbeddedFonts(Presentation pres)](#compressEmbeddedFonts-com.aspose.slides.Presentation-) | Komprimerar [Presentation](../../com.aspose.slides/presentation) genom att ta bort oanvända tecken från inbäddade teckensnitt. |
| [compressImages(IPresentation presentation, int resolution)](#compressImages-com.aspose.slides.IPresentation-int-) | Minskar upplösningen på bilder i presentationen och tar bort deras beskurna områden, liknande PowerPoints "Compress Pictures" som tillämpas på alla bilder. |
### Compress() {#Compress--}
```
public Compress()
```


### compressPresentation(Presentation presentation) {#compressPresentation-com.aspose.slides.Presentation-}
```
public static void compressPresentation(Presentation presentation)
```


Minskar storleken på en presentation genom att tillämpa alla tillgängliga komprimeringssteg:

 *  Tar bort oanvända masterbilder \#removeUnusedMasterSlides(Presentation).removeUnusedMasterSlides(Presentation).
 *  Tar bort oanvända layoutbilder \#removeUnusedLayoutSlides(Presentation).removeUnusedLayoutSlides(Presentation).
 *  Behåller endast de glyfer som faktiskt används i inbäddade teckensnitt \#compressEmbeddedFonts(Presentation).compressEmbeddedFonts(Presentation).
 *  Minskar bildens upplösning till 150 DPI och tar bort beskurna områden i bilder \#compressImages(IPresentation,int).compressImages(IPresentation,int).

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

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| presentation | [Presentation](../../com.aspose.slides/presentation) | Presentation som ska komprimeras.

--------------------

För att anpassa komprimeringen, till exempel för att använda en annan bildupplösning eller hoppa över ett steg, anropa metoderna som listas ovan individuellt istället för den här. Beskurna bildområden tas bort permanent och kan inte återställas i PowerPoint. |

### removeUnusedMasterSlides(Presentation pres) {#removeUnusedMasterSlides-com.aspose.slides.Presentation-}
```
public static void removeUnusedMasterSlides(Presentation pres)
```


Komprimerar [Presentation](../../com.aspose.slides/presentation) genom att ta bort oanvända masterbilder.

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


Komprimerar [Presentation](../../com.aspose.slides/presentation) genom att ta bort oanvända layoutbilder.

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


Komprimerar [Presentation](../../com.aspose.slides/presentation) genom att ta bort oanvända tecken från inbäddade teckensnitt.

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

### compressImages(IPresentation presentation, int resolution) {#compressImages-com.aspose.slides.IPresentation-int-}
```
public static void compressImages(IPresentation presentation, int resolution)
```


Minskar upplösningen på bilder i presentationen och tar bort deras beskurna områden, liknande PowerPoints "Compress Pictures" som tillämpas på alla bilder. Bilder på bildspel, layoutbilder och masterbilder bearbetas, inklusive bilder inuti gruppformer och bildfyllningar av former.

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

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| presentation | [IPresentation](../../com.aspose.slides/ipresentation) | Presentationen att bearbeta. |
| resolution | int | Måluplösning relativt den storlek vid vilken varje bild visas. [PicturesCompression.DocumentResolution](../../com.aspose.slides/picturescompression\#DocumentResolution) lämnar bilder oförändrade.

--------------------

Bilder som redan är på eller under måluplösningen lämnas oförändrade; bilder förstoras aldrig.

Inte bearbetade: bildbakgrunder, tabellcellfyllningar, diagram, SmartArt, GIF-bilder (för att bevara animation), SVG- och metafilbilder (EMF/WMF).

Beskurna områden tas bort permanent och kan inte återställas i PowerPoint. |