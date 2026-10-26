---
title: SlideImageFormat
second_title: Riferimento API di Aspose.Slides per Java
description: Determina il formato in cui l'immagine della diapositiva sarà salvata per l'esportazione della presentazione in HTML.
type: docs
url: /it/com.aspose.slides/slideimageformat/
---
**Ereditarietà:**
java.lang.Object

**Tutte le interfacce implementate:**
[com.aspose.slides.ISlideImageFormat](../../com.aspose.slides/islideimageformat)
```
public class SlideImageFormat implements ISlideImageFormat
```

Determina il formato in cui l'immagine della diapositiva sarà salvata per l'esportazione della presentazione in HTML.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [SlideImageFormat()](#SlideImageFormat--) |  |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [svg(SVGOptions options)](#svg-com.aspose.slides.SVGOptions-) | Le diapositive devono essere convertite in formato SVG. |
| [bitmap(float scale, int imageFormat)](#bitmap-float-int-) | Le diapositive devono essere convertite in un'immagine raster. |
### SlideImageFormat() {#SlideImageFormat--}
```
public SlideImageFormat()
```


### svg(SVGOptions options) {#svg-com.aspose.slides.SVGOptions-}
```
public static SlideImageFormat svg(SVGOptions options)
```


Le diapositive devono essere convertite in formato SVG.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| options | [SVGOptions](../../com.aspose.slides/svgoptions) | Opzioni per l'esportazione SVG. |

**Restituisce:**
[SlideImageFormat](../../com.aspose.slides/slideimageformat) - L'oggetto [SlideImageFormat](../../com.aspose.slides/slideimageformat).
### bitmap(float scale, int imageFormat) {#bitmap-float-int-}
```
public static SlideImageFormat bitmap(float scale, int imageFormat)
```


Le diapositive devono essere convertite in un'immagine raster.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| scale | float | Il fattore di scala dell'immagine di output. |
| imageFormat | int | Il formato dell'immagine risultante (ad es., PNG, JPEG). |

**Restituisce:**
[SlideImageFormat](../../com.aspose.slides/slideimageformat) -