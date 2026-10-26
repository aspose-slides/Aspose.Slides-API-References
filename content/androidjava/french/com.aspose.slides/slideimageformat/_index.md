---
title: SlideImageFormat
second_title: Aspose.Slides pour Android via la référence de l'API Java
description: Détermine le format dans lequel l'image de la diapositive sera enregistrée pour la présentation lors de l'export HTML.
type: docs
url: /fr/com.aspose.slides/slideimageformat/
---
**Héritage:**  
java.lang.Object

**Toutes les interfaces implémentées:**  
[com.aspose.slides.ISlideImageFormat](../../com.aspose.slides/islideimageformat)  
```
public class SlideImageFormat implements ISlideImageFormat
```

Détermine le format dans lequel l’image de la diapositive sera enregistrée pour la présentation lors de l’export HTML.  

## Constructeurs

| Constructeur | Description |
| --- | --- |
| [SlideImageFormat()](#SlideImageFormat--) |  |

## Méthodes

| Méthode | Description |
| --- | --- |
| [svg(SVGOptions options)](#svg-com.aspose.slides.SVGOptions-) | Les diapositives doivent être converties au format SVG. |
| [bitmap(float scale, int imageFormat)](#bitmap-float-int-) | Les diapositives doivent être converties en image raster. |

### SlideImageFormat() {#SlideImageFormat--}
```
public SlideImageFormat()
```

### svg(SVGOptions options) {#svg-com.aspose.slides.SVGOptions-}
```
public static SlideImageFormat svg(SVGOptions options)
```

Les diapositives doivent être converties au format SVG.

**Paramètres:**  
| Paramètre | Type | Description |
| --- | --- | --- |
| options | [SVGOptions](../../com.aspose.slides/svgoptions) | Options pour l’export SVG. |

**Renvoie:**  
[SlideImageFormat](../../com.aspose.slides/slideimageformat) - L’objet [SlideImageFormat](../../com.aspose.slides/slideimageformat).

### bitmap(float scale, int imageFormat) {#bitmap-float-int-}
```
public static SlideImageFormat bitmap(float scale, int imageFormat)
```

Les diapositives doivent être converties en image raster.

**Paramètres:**  
| Paramètre | Type | Description |
| --- | --- | --- |
| scale | float | Le facteur par lequel redimensionner l’image de sortie. |
| imageFormat | int | Le format de l’image résultante (par ex., PNG, JPEG). |

**Renvoie:**  
[SlideImageFormat](../../com.aspose.slides/slideimageformat) -