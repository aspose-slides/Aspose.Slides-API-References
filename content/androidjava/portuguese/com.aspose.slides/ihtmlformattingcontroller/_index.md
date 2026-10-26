---
title: IHtmlFormattingController
second_title: Aspose.Slides for Android via Java API Reference
description: Controls a html file generation.
type: docs
url: /pt/com.aspose.slides/ihtmlformattingcontroller/
---```
public interface IHtmlFormattingController
```

Controla a geração de um arquivo html.
## Métodos

| Método | Descrição |
| --- | --- |
| [writeDocumentStart(IHtmlGenerator generator, IPresentation presentation)](#writeDocumentStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-) | Chamado para escrever o cabeçalho do documento html. |
| [writeDocumentEnd(IHtmlGenerator generator, IPresentation presentation)](#writeDocumentEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-) | Chamado para escrever o rodapé do documento html. |
| [writeSlideStart(IHtmlGenerator generator, ISlide slide)](#writeSlideStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.ISlide-) | Chamado para escrever o cabeçalho do slide html. |
| [writeSlideEnd(IHtmlGenerator generator, ISlide slide)](#writeSlideEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.ISlide-) | Chamado para escrever o rodapé do slide html. |
| [writeShapeStart(IHtmlGenerator generator, IShape shape)](#writeShapeStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IShape-) | Chamado antes da renderização da shape. |
| [writeShapeEnd(IHtmlGenerator generator, IShape shape)](#writeShapeEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IShape-) | Chamado antes da renderização da shape. |
### writeDocumentStart(IHtmlGenerator generator, IPresentation presentation) {#writeDocumentStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-}
```
public abstract void writeDocumentStart(IHtmlGenerator generator, IPresentation presentation)
```

Chamado para escrever o cabeçalho do documento html. Chamado uma vez por conversão de apresentação.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | Objeto de saída. |
| presentation | [IPresentation](../../com.aspose.slides/ipresentation) | Apresentação que está sendo renderizada no momento. |

### writeDocumentEnd(IHtmlGenerator generator, IPresentation presentation) {#writeDocumentEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-}
```
public abstract void writeDocumentEnd(IHtmlGenerator generator, IPresentation presentation)
```

Chamado para escrever o rodapé do documento html. Chamado uma vez por conversão de apresentação.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | Objeto de saída. |
| presentation | [IPresentation](../../com.aspose.slides/ipresentation) | Apresentação que está sendo renderizada no momento. |

### writeSlideStart(IHtmlGenerator generator, ISlide slide) {#writeSlideStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.ISlide-}
```
public abstract void writeSlideStart(IHtmlGenerator generator, ISlide slide)
```

Chamado para escrever o cabeçalho do slide html. Chamado uma vez por cada slide.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | Objeto de saída. |
| slide | [ISlide](../../com.aspose.slides/islide) | Slide que está sendo renderizado no momento. |

### writeSlideEnd(IHtmlGenerator generator, ISlide slide) {#writeSlideEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.ISlide-}
```
public abstract void writeSlideEnd(IHtmlGenerator generator, ISlide slide)
```

Chamado para escrever o rodapé do slide html. Chamado uma vez por cada slide.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | Objeto de saída. |
| slide | [ISlide](../../com.aspose.slides/islide) | Slide que está sendo renderizado no momento. |

### writeShapeStart(IHtmlGenerator generator, IShape shape) {#writeShapeStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IShape-}
```
public abstract void writeShapeStart(IHtmlGenerator generator, IShape shape)
```

Chamado antes da renderização da shape. Chamado uma vez por cada shape. Se esta função escrever algo no generator, a geração da imagem do slide atual será finalizada, o fragmento html adicionado será inserido e uma nova imagem será iniciada sobre a anterior.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | Objeto de saída. |
| shape | [IShape](../../com.aspose.slides/ishape) | Shape que está prestes a ser renderizado. |

### writeShapeEnd(IHtmlGenerator generator, IShape shape) {#writeShapeEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IShape-}
```
public abstract void writeShapeEnd(IHtmlGenerator generator, IShape shape)
```

Chamado antes da renderização da shape. Chamado uma vez por cada shape. Se esta função escrever algo no generator, a geração da imagem do slide atual será finalizada, o fragmento html adicionado será inserido e uma nova imagem será iniciada sobre a anterior.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | Objeto de saída. |
| shape | [IShape](../../com.aspose.slides/ishape) | Shape que foi renderizada por último. |