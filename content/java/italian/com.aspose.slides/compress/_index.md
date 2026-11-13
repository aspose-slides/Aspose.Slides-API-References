---
title: Compress
second_title: Riferimento API di Aspose.Slides per Java
description: Rappresenta un gruppo di metodi destinati a comprimere .
type: docs
url: /it/com.aspose.slides/compress/
---
**Inheritance:**
java.lang.Object
```
public class Compress
```

Rappresenta un gruppo di metodi destinati a comprimere [Presentation](../../com.aspose.slides/presentation).

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
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [Compress()](#Compress--) |  |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [compressPresentation(Presentation presentation)](#compressPresentation-com.aspose.slides.Presentation-) | Riduce le dimensioni di una presentazione applicando tutti i passaggi di compressione disponibili:

 *  Rimuove le master slide inutilizzate \#removeUnusedMasterSlides(Presentation).removeUnusedMasterSlides(Presentation).
 *  Rimuove le slide di layout inutilizzate \#removeUnusedLayoutSlides(Presentation).removeUnusedLayoutSlides(Presentation).
 *  Mantiene solo i glifi realmente usati nei caratteri incorporati \#compressEmbeddedFonts(Presentation).compressEmbeddedFonts(Presentation).
 *  Riduce la risoluzione delle immagini a 150 DPI ed elimina le aree ritagliate delle immagini \#compressImages(IPresentation,int).compressImages(IPresentation,int). |
| [removeUnusedMasterSlides(Presentation pres)](#removeUnusedMasterSlides-com.aspose.slides.Presentation-) | Esegue la compressione del [Presentation](../../com.aspose.slides/presentation) rimuovendo le master slide inutilizzate. |
| [removeUnusedLayoutSlides(Presentation pres)](#removeUnusedLayoutSlides-com.aspose.slides.Presentation-) | Esegue la compressione del [Presentation](../../com.aspose.slides/presentation) rimuovendo le slide di layout inutilizzate. |
| [compressEmbeddedFonts(Presentation pres)](#compressEmbeddedFonts-com.aspose.slides.Presentation-) | Esegue la compressione del [Presentation](../../com.aspose.slides/presentation) rimuovendo i caratteri inutilizzati dai caratteri incorporati. |
| [compressImages(IPresentation presentation, int resolution)](#compressImages-com.aspose.slides.IPresentation-int-) | Riduce la risoluzione delle immagini nella presentazione ed elimina le loro aree ritagliate, similmente a "Compress Pictures" di PowerPoint applicato a tutte le immagini. |
### Compress() {#Compress--}
```
public Compress()
```


### compressPresentation(Presentation presentation) {#compressPresentation-com.aspose.slides.Presentation-}
```
public static void compressPresentation(Presentation presentation)
```


Riduce le dimensioni di una presentazione applicando tutti i passaggi di compressione disponibili:

 *  Rimuove le master slide inutilizzate \#removeUnusedMasterSlides(Presentation).removeUnusedMasterSlides(Presentation).
 *  Rimuove le slide di layout inutilizzate \#removeUnusedLayoutSlides(Presentation).removeUnusedLayoutSlides(Presentation).
 *  Mantiene solo i glifi realmente usati nei caratteri incorporati \#compressEmbeddedFonts(Presentation).compressEmbeddedFonts(Presentation).
 *  Riduce la risoluzione delle immagini a 150 DPI ed elimina le aree ritagliate delle immagini \#compressImages(IPresentation,int).compressImages(IPresentation,int).

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

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| presentation | [Presentation](../../com.aspose.slides/presentation) | La presentazione da comprimere.

--------------------

Per personalizzare la compressione, ad esempio per utilizzare una risoluzione delle immagini diversa o per saltare un passaggio, chiamare i metodi elencati sopra singolarmente anziché questo. Le aree ritagliate delle immagini sono rimosse definitivamente e non possono essere ripristinate in PowerPoint. |

### removeUnusedMasterSlides(Presentation pres) {#removeUnusedMasterSlides-com.aspose.slides.Presentation-}
```
public static void removeUnusedMasterSlides(Presentation pres)
```


Esegue la compressione del [Presentation](../../com.aspose.slides/presentation) rimuovendo le master slide inutilizzate.

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

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | L'istanza della presentazione |

### removeUnusedLayoutSlides(Presentation pres) {#removeUnusedLayoutSlides-com.aspose.slides.Presentation-}
```
public static void removeUnusedLayoutSlides(Presentation pres)
```


Esegue la compressione del [Presentation](../../com.aspose.slides/presentation) rimuovendo le slide di layout inutilizzate.

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

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | L'istanza della presentazione |

### compressEmbeddedFonts(Presentation pres) {#compressEmbeddedFonts-com.aspose.slides.Presentation-}
```
public static void compressEmbeddedFonts(Presentation pres)
```


Esegue la compressione del [Presentation](../../com.aspose.slides/presentation) rimuovendo i caratteri inutilizzati dai caratteri incorporati.

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

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | L'istanza della presentazione |

### compressImages(IPresentation presentation, int resolution) {#compressImages-com.aspose.slides.IPresentation-int-}
```
public static void compressImages(IPresentation presentation, int resolution)
```


Riduce la risoluzione delle immagini nella presentazione ed elimina le loro aree ritagliate, similmente a "Compress Pictures" di PowerPoint applicato a tutte le immagini. Vengono elaborate le immagini presenti su slide, slide di layout e master slide, comprese le immagini all'interno di forme raggruppate e i riempimenti immagine delle forme.

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

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| presentation | [IPresentation](../../com.aspose.slides/ipresentation) | La presentazione da elaborare. |
| resolution | int | Risoluzione target relativa alle dimensioni con cui ciascuna immagine viene visualizzata. [PicturesCompression.DocumentResolution](../../com.aspose.slides/picturescompression\#DocumentResolution) lascia le immagini inalterate.

Le immagini già alla risoluzione target o inferiore rimangono inalterate; le immagini non vengono mai ingrandite.

Non elaborate: sfondi delle slide, riempimenti delle celle delle tabelle, grafici, SmartArt, immagini GIF (per preservare l'animazione), immagini SVG e metafile (EMF/WMF).

Le aree ritagliate sono rimosse definitivamente e non possono essere ripristinate in PowerPoint. |