---
title: Compress
second_title: Aspose.Slides for Java API Reference
description: Represents a group of methods intended to compress .
type: docs
url: /com.aspose.slides/compress/
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
## Constructors

| Constructor | Description |
| --- | --- |
| [Compress()](#Compress--) |  |
## Methods

| Method | Description |
| --- | --- |
| [compressPresentation(Presentation presentation)](#compressPresentation-com.aspose.slides.Presentation-) | Reduces the size of a presentation by applying all available compression steps:

 *  Removes unused master slides \#removeUnusedMasterSlides(Presentation).removeUnusedMasterSlides(Presentation).
 *  Removes unused layout slides \#removeUnusedLayoutSlides(Presentation).removeUnusedLayoutSlides(Presentation).
 *  Keeps only the glyphs actually used in embedded fonts \#compressEmbeddedFonts(Presentation).compressEmbeddedFonts(Presentation).
 *  Reduces picture resolution to 150 DPI and deletes cropped areas of pictures \#compressImages(IPresentation,int).compressImages(IPresentation,int). |
| [removeUnusedMasterSlides(Presentation pres)](#removeUnusedMasterSlides-com.aspose.slides.Presentation-) | Makes compression of the [Presentation](../../com.aspose.slides/presentation) by removing unused master slides. |
| [removeUnusedLayoutSlides(Presentation pres)](#removeUnusedLayoutSlides-com.aspose.slides.Presentation-) | Makes compression of the [Presentation](../../com.aspose.slides/presentation) by removing unused layout slides. |
| [compressEmbeddedFonts(Presentation pres)](#compressEmbeddedFonts-com.aspose.slides.Presentation-) | Makes compression of the [Presentation](../../com.aspose.slides/presentation) by removing unused characters from embedded fonts. |
| [compressImages(IPresentation presentation, int resolution)](#compressImages-com.aspose.slides.IPresentation-int-) | Reduces the resolution of pictures in the presentation and deletes their cropped areas, similar to PowerPoint's "Compress Pictures" applied to all pictures. |
### Compress() {#Compress--}
```
public Compress()
```


### compressPresentation(Presentation presentation) {#compressPresentation-com.aspose.slides.Presentation-}
```
public static void compressPresentation(Presentation presentation)
```


Reduces the size of a presentation by applying all available compression steps:

 *  Removes unused master slides \#removeUnusedMasterSlides(Presentation).removeUnusedMasterSlides(Presentation).
 *  Removes unused layout slides \#removeUnusedLayoutSlides(Presentation).removeUnusedLayoutSlides(Presentation).
 *  Keeps only the glyphs actually used in embedded fonts \#compressEmbeddedFonts(Presentation).compressEmbeddedFonts(Presentation).
 *  Reduces picture resolution to 150 DPI and deletes cropped areas of pictures \#compressImages(IPresentation,int).compressImages(IPresentation,int).

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

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| presentation | [Presentation](../../com.aspose.slides/presentation) | The presentation to compress.

--------------------

To customize compression, for example to use a different picture resolution or to skip a step, call the methods listed above individually instead of this one. Cropped areas of pictures are removed permanently and cannot be restored in PowerPoint. |

### removeUnusedMasterSlides(Presentation pres) {#removeUnusedMasterSlides-com.aspose.slides.Presentation-}
```
public static void removeUnusedMasterSlides(Presentation pres)
```


Makes compression of the [Presentation](../../com.aspose.slides/presentation) by removing unused master slides.

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
| Parameter | Type | Description |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | The presentation instance |

### removeUnusedLayoutSlides(Presentation pres) {#removeUnusedLayoutSlides-com.aspose.slides.Presentation-}
```
public static void removeUnusedLayoutSlides(Presentation pres)
```


Makes compression of the [Presentation](../../com.aspose.slides/presentation) by removing unused layout slides.

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
| Parameter | Type | Description |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | The presentation instance |

### compressEmbeddedFonts(Presentation pres) {#compressEmbeddedFonts-com.aspose.slides.Presentation-}
```
public static void compressEmbeddedFonts(Presentation pres)
```


Makes compression of the [Presentation](../../com.aspose.slides/presentation) by removing unused characters from embedded fonts.

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
| Parameter | Type | Description |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | The presentation instance |

### compressImages(IPresentation presentation, int resolution) {#compressImages-com.aspose.slides.IPresentation-int-}
```
public static void compressImages(IPresentation presentation, int resolution)
```


Reduces the resolution of pictures in the presentation and deletes their cropped areas, similar to PowerPoint's "Compress Pictures" applied to all pictures. Pictures on slides, layout slides and master slides are processed, including pictures inside group shapes and picture fills of shapes.

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

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| presentation | [IPresentation](../../com.aspose.slides/ipresentation) | The presentation to process. |
| resolution | int | Target resolution relative to the size at which each picture is displayed. [PicturesCompression.DocumentResolution](../../com.aspose.slides/picturescompression\#DocumentResolution) leaves pictures unchanged.

--------------------

Pictures already at or below the target resolution are left unchanged; pictures are never upscaled.

Not processed: slide backgrounds, table cell fills, charts, SmartArt, GIF images (to preserve animation), SVG and metafile (EMF/WMF) images.

Cropped areas are removed permanently and cannot be restored in PowerPoint. |

