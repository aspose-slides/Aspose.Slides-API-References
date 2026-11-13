---
title: Compress
second_title: Aspose.Slides dla Java – Odniesienie API
description: Reprezentuje grupę metod przeznaczonych do kompresji .
type: docs
url: /pl/com.aspose.slides/compress/
---
**Dziedziczenie:**
java.lang.Object
```
public class Compress
```

Reprezentuje grupę metod przeznaczonych do kompresji [Presentation](../../com.aspose.slides/presentation).

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

| Konstruktor | Opis |
| --- | --- |
| [Compress()](#Compress--) |  |
## Metody

| Metoda | Opis |
| --- | --- |
| [compressPresentation(Presentation presentation)](#compressPresentation-com.aspose.slides.Presentation-) | Zmniejsza rozmiar prezentacji, stosując wszystkie dostępne kroki kompresji:

 *  Usuwa nieużywane slajdy wzorcowe \#removeUnusedMasterSlides(Presentation).removeUnusedMasterSlides(Presentation).
 *  Usuwa nieużywane slajdy układu \#removeUnusedLayoutSlides(Presentation).removeUnusedLayoutSlides(Presentation).
 *  Zachowuje tylko glify faktycznie użyte w osadzonych czcionkach \#compressEmbeddedFonts(Presentation).compressEmbeddedFonts(Presentation).
 *  Zmniejsza rozdzielczość obrazów do 150 DPI i usuwa przycięte fragmenty obrazów \#compressImages(IPresentation,int).compressImages(IPresentation,int). |
| [removeUnusedMasterSlides(Presentation pres)](#removeUnusedMasterSlides-com.aspose.slides.Presentation-) | Komprejuje [Presentation](../../com.aspose.slides/presentation) poprzez usunięcie nieużywanych slajdów wzorcowych. |
| [removeUnusedLayoutSlides(Presentation pres)](#removeUnusedLayoutSlides-com.aspose.slides.Presentation-) | Komprejuje [Presentation](../../com.aspose.slides/presentation) poprzez usunięcie nieużywanych slajdów układu. |
| [compressEmbeddedFonts(Presentation pres)](#compressEmbeddedFonts-com.aspose.slides.Presentation-) | Komprejuje [Presentation](../../com.aspose.slides/presentation) poprzez usunięcie nieużywanych znaków z osadzonych czcionek. |
| [compressImages(IPresentation presentation, int resolution)](#compressImages-com.aspose.slides.IPresentation-int-) | Zmniejsza rozdzielczość obrazów w prezentacji i usuwa ich przycięte fragmenty, podobnie jak funkcja "Compress Pictures" w PowerPoint zastosowana do wszystkich obrazów. |
### Compress() {#Compress--}
```
public Compress()
```


### compressPresentation(Presentation presentation) {#compressPresentation-com.aspose.slides.Presentation-}
```
public static void compressPresentation(Presentation presentation)
```


Zmniejsza rozmiar prezentacji, stosując wszystkie dostępne kroki kompresji:

 *  Usuwa nieużywane slajdy wzorcowe \#removeUnusedMasterSlides(Presentation).removeUnusedMasterSlides(Presentation).
 *  Usuwa nieużywane slajdy układu \#removeUnusedLayoutSlides(Presentation).removeUnusedLayoutSlides(Presentation).
 *  Zachowuje tylko glify faktycznie użyte w osadzonych czcionkach \#compressEmbeddedFonts(Presentation).compressEmbeddedFonts(Presentation).
 *  Zmniejsza rozdzielczość obrazów do 150 DPI i usuwa przycięte fragmenty obrazów \#compressImages(IPresentation,int).compressImages(IPresentation,int).

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
| Parametr | Typ | Opis |
| --- | --- | --- |
| presentation | [Presentation](../../com.aspose.slides/presentation) | Prezentacja do skompresowania.

--------------------

Aby dostosować kompresję, na przykład użyć innej rozdzielczości obrazu lub pominąć krok, wywołaj wymienione powyżej metody indywidualnie zamiast tej. Przycięte fragmenty obrazów są usuwane trwale i nie mogą być przywrócone w PowerPoint. |

### removeUnusedMasterSlides(Presentation pres) {#removeUnusedMasterSlides-com.aspose.slides.Presentation-}
```
public static void removeUnusedMasterSlides(Presentation pres)
```


Komprejuje [Presentation](../../com.aspose.slides/presentation) poprzez usunięcie nieużywanych slajdów wzorcowych.

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
| Parametr | Typ | Opis |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | Instancja prezentacji |

### removeUnusedLayoutSlides(Presentation pres) {#removeUnusedLayoutSlides-com.aspose.slides.Presentation-}
```
public static void removeUnusedLayoutSlides(Presentation pres)
```


Komprejuje [Presentation](../../com.aspose.slides/presentation) poprzez usunięcie nieużywanych slajdów układu.

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
| Parametr | Typ | Opis |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | Instancja prezentacji |

### compressEmbeddedFonts(Presentation pres) {#compressEmbeddedFonts-com.aspose.slides.Presentation-}
```
public static void compressEmbeddedFonts(Presentation pres)
```


Komprejuje [Presentation](../../com.aspose.slides/presentation) poprzez usunięcie nieużywanych znaków z osadzonych czcionek.

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
| Parametr | Typ | Opis |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | Instancja prezentacji |

### compressImages(IPresentation presentation, int resolution) {#compressImages-com.aspose.slides.IPresentation-int-}
```
public static void compressImages(IPresentation presentation, int resolution)
```


Zmniejsza rozdzielczość obrazów w prezentacji i usuwa ich przycięte fragmenty, podobnie jak funkcja "Compress Pictures" w PowerPoint zastosowana do wszystkich obrazów. Obrazy na slajdach, slajdach układu i slajdach wzorcowych są przetwarzane, w tym obrazy wewnątrz grup kształtów oraz wypełnienia obrazami kształtów.

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
| Parametr | Typ | Opis |
| --- | --- | --- |
| presentation | [IPresentation](../../com.aspose.slides/ipresentation) | Prezentacja do przetworzenia. |
| resolution | int | Docelowa rozdzielczość względem rozmiaru, w jakim każdy obraz jest wyświetlany. [PicturesCompression.DocumentResolution](../../com.aspose.slides/picturescompression\#DocumentResolution) pozostawia obrazy niezmienione. |

Obrazy już posiadające rozdzielczość równą lub niższą od docelowej pozostają niezmienione; obrazy nigdy nie są powiększane.

Nie przetwarzane: tło slajdów, wypełnienia komórek tabel, wykresy, SmartArt, obrazy GIF (aby zachować animację), obrazy SVG i metafile (EMF/WMF).

Przycięte fragmenty są usuwane trwale i nie mogą być przywrócone w PowerPoint. |