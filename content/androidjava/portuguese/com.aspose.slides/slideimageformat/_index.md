---
title: SlideImageFormat
second_title: Aspose.Slides para Android via Referência da API Java
description: Determina o formato no qual a imagem do slide será salva para a exportação da apresentação em HTML.
type: docs
url: /pt/com.aspose.slides/slideimageformat/
---
**Herança:**
java.lang.Object

**Todas as interfaces implementadas:**
[com.aspose.slides.ISlideImageFormat](../../com.aspose.slides/islideimageformat)
```
public class SlideImageFormat implements ISlideImageFormat
```

Determina o formato no qual a imagem do slide será salva para a exportação da apresentação em HTML.
## Construtores

| Construtor | Descrição |
| --- | --- |
| [SlideImageFormat()](#SlideImageFormat--) |  |
## Métodos

| Método | Descrição |
| --- | --- |
| [svg(SVGOptions options)](#svg-com.aspose.slides.SVGOptions-) | Os slides devem ser convertidos para o formato SVG. |
| [bitmap(float scale, int imageFormat)](#bitmap-float-int-) | Os slides devem ser convertidos para uma imagem raster. |
### SlideImageFormat() {#SlideImageFormat--}
```
public SlideImageFormat()
```


### svg(SVGOptions options) {#svg-com.aspose.slides.SVGOptions-}
```
public static SlideImageFormat svg(SVGOptions options)
```


Os slides devem ser convertidos para o formato SVG.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| options | [SVGOptions](../../com.aspose.slides/svgoptions) | Opções para exportação SVG. |

**Retorna:**
[SlideImageFormat](../../com.aspose.slides/slideimageformat) - O objeto [SlideImageFormat](../../com.aspose.slides/slideimageformat).
### bitmap(float scale, int imageFormat) {#bitmap-float-int-}
```
public static SlideImageFormat bitmap(float scale, int imageFormat)
```


Os slides devem ser convertidos para uma imagem raster.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| scale | float | O fator pelo qual dimensionar a imagem de saída. |
| imageFormat | int | O formato da imagem resultante (por exemplo, PNG, JPEG). |

**Retorna:**
[SlideImageFormat](../../com.aspose.slides/slideimageformat) -