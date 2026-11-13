---
title: Compress
second_title: Aspose.Slides pro Java – referenční příručka API
description: Představuje skupinu metod určených ke kompresi .
type: docs
url: /cs/com.aspose.slides/compress/
---
**Inheritance:**
java.lang.Object
```
public class Compress
```

Represents a group of methods intended to compress [Presentation](../../com.aspose.slides/presentation).

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
| [compressPresentation(Presentation presentation)](#compressPresentation-com.aspose.slides.Presentation-) | Zmenšuje velikost prezentace aplikací všech dostupných kroků komprese:

 *  Odstraní nepoužité hlavní snímky \#removeUnusedMasterSlides(Presentation).removeUnusedMasterSlides(Presentation).
 *  Odstraní nepoužité rozložení snímků \#removeUnusedLayoutSlides(Presentation).removeUnusedLayoutSlides(Presentation).
 *  Zachová pouze glyfy skutečně použité v vložených fontech \#compressEmbeddedFonts(Presentation).compressEmbeddedFonts(Presentation).
 *  Sníží rozlišení obrázků na 150 DPI a smaže oříznuté oblasti obrázků \#compressImages(IPresentation,int).compressImages(IPresentation,int). |
| [removeUnusedMasterSlides(Presentation pres)](#removeUnusedMasterSlides-com.aspose.slides.Presentation-) | Provádí kompresi [Presentation](../../com.aspose.slides/presentation) odstraněním nepoužitých hlavních snímků. |
| [removeUnusedLayoutSlides(Presentation pres)](#removeUnusedLayoutSlides-com.aspose.slides.Presentation-) | Provádí kompresi [Presentation](../../com.aspose.slides/presentation) odstraněním nepoužitých rozložení snímků. |
| [compressEmbeddedFonts(Presentation pres)](#compressEmbeddedFonts-com.aspose.slides.Presentation-) | Provádí kompresi [Presentation](../../com.aspose.slides/presentation) odstraněním nepoužitých znaků z vložených fontů. |
| [compressImages(IPresentation presentation, int resolution)](#compressImages-com.aspose.slides.IPresentation-int-) | Sníží rozlišení obrázků v prezentaci a smaže jejich oříznuté oblasti, podobně jako funkce „Compress Pictures“ v PowerPointu použita na všechny obrázky. |
### Compress() {#Compress--}
```
public Compress()
```


### compressPresentation(Presentation presentation) {#compressPresentation-com.aspose.slides.Presentation-}
```
public static void compressPresentation(Presentation presentation)
```


Zmenšuje velikost prezentace aplikací všech dostupných kroků komprese:

 *  Odstraní nepoužité hlavní snímky \#removeUnusedMasterSlides(Presentation).removeUnusedMasterSlides(Presentation).
 *  Odstraní nepoužité rozložení snímků \#removeUnusedLayoutSlides(Presentation).removeUnusedLayoutSlides(Presentation).
 *  Zachová pouze glyfy skutečně použité v vložených fontech \#compressEmbeddedFonts(Presentation).compressEmbeddedFonts(Presentation).
 *  Sníží rozlišení obrázků na 150 DPI a smaže oříznuté oblasti obrázků \#compressImages(IPresentation,int).compressImages(IPresentation,int).

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

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| presentation | [Presentation](../../com.aspose.slides/presentation) | Prezentace k kompresi.

--------------------

Pro přizpůsobení komprese, například pro použití jiného rozlišení obrázků nebo pro přeskočení kroku, zavolejte výše uvedené metody jednotlivě místo této. Oříznuté oblasti obrázků jsou trvale odstraněny a nelze je v PowerPointu obnovit. |

### removeUnusedMasterSlides(Presentation pres) {#removeUnusedMasterSlides-com.aspose.slides.Presentation-}
```
public static void removeUnusedMasterSlides(Presentation pres)
```


Provádí kompresi [Presentation](../../com.aspose.slides/presentation) odstraněním nepoužitých hlavních snímků.

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


Provádí kompresi [Presentation](../../com.aspose.slides/presentation) odstraněním nepoužitých rozložení snímků.

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      Compress.removeUnusedLayoutSlides(pres);
> 
>      pres.save("pres-out.pptx", SaveFormat.Pptx);
>  finally {
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


Provádí kompresi [Presentation](../../com.aspose.slides/presentation) odstraněním nepoužitých znaků z vložených fontů.

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

### compressImages(IPresentation presentation, int resolution) {#compressImages-com.aspose.slides.IPresentation-int-}
```
public static void compressImages(IPresentation presentation, int resolution)
```


Sníží rozlišení obrázků v prezentaci a smaže jejich oříznuté oblasti, podobně jako funkce „Compress Pictures“ v PowerPointu použita na všechny obrázky. Obrázky na snímcích, rozložení snímků a hlavních snímcích jsou zpracovány, včetně obrázků ve skupinových tvarech a výplní obrázků tvarů.

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

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| presentation | [IPresentation](../../com.aspose.slides/ipresentation) | Prezentace k zpracování. |
| resolution | int | Cílové rozlišení vzhledem k velikosti, v které je každý obrázek zobrazován. [PicturesCompression.DocumentResolution](../../com.aspose.slides/picturescompression\#DocumentResolution) ponechává obrázky beze změny.

--------------------

Obrázky již na cílovém rozlišení nebo pod ním jsou ponechány beze změny; obrázky nejsou nikdy zvětšovány.

Není zpracováno: pozadí snímků, výplně buněk tabulek, grafy, SmartArt, GIF obrázky (pro zachování animace), SVG a metafily (EMF/WMF).

Oříznuté oblasti obrázků jsou trvale odstraněny a nelze je v PowerPointu obnovit. |