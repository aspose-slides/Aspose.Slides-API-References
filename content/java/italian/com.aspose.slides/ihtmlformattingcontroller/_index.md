---
title: IHtmlFormattingController
second_title: Aspose.Slides for Java API Reference
description: Controls a html file generation.
type: docs
url: /it/com.aspose.slides/ihtmlformattingcontroller/
---```
public interface IHtmlFormattingController
```

Controlla la generazione di un file html.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [writeDocumentStart(IHtmlGenerator generator, IPresentation presentation)](#writeDocumentStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-) | Called to write html document header. |
| [writeDocumentEnd(IHtmlGenerator generator, IPresentation presentation)](#writeDocumentEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-) | Called to write html document footer. |
| [writeSlideStart(IHtmlGenerator generator, ISlide slide)](#writeSlideStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.ISlide-) | Called to write html slide header. |
| [writeSlideEnd(IHtmlGenerator generator, ISlide slide)](#writeSlideEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.ISlide-) | Called to write html slide footer. |
| [writeShapeStart(IHtmlGenerator generator, IShape shape)](#writeShapeStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IShape-) | Called before shape's rendering. |
| [writeShapeEnd(IHtmlGenerator generator, IShape shape)](#writeShapeEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IShape-) | Called before shape's rendering. |
### writeDocumentStart(IHtmlGenerator generator, IPresentation presentation) {#writeDocumentStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-}
```
public abstract void writeDocumentStart(IHtmlGenerator generator, IPresentation presentation)
```


Called to write html document header. Called once per presentation conversion.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | Oggetto di output. |
| presentation | [IPresentation](../../com.aspose.slides/ipresentation) | Presentazione che è attualmente renderizzata. |

### writeDocumentEnd(IHtmlGenerator generator, IPresentation presentation) {#writeDocumentEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-}
```
public abstract void writeDocumentEnd(IHtmlGenerator generator, IPresentation presentation)
```


Called to write html document footer. Called once per presentation conversion.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | Oggetto di output. |
| presentation | [IPresentation](../../com.aspose.slides/ipresentation) | Presentazione che è attualmente renderizzata. |

### writeSlideStart(IHtmlGenerator generator, ISlide slide) {#writeSlideStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.ISlide-}
```
public abstract void writeSlideStart(IHtmlGenerator generator, ISlide slide)
```


Called to write html slide header. Called once per each of slides.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | Oggetto di output. |
| slide | [ISlide](../../com.aspose.slides/islide) | Diapositiva che è attualmente renderizzata. |

### writeSlideEnd(IHtmlGenerator generator, ISlide slide) {#writeSlideEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.ISlide-}
```
public abstract void writeSlideEnd(IHtmlGenerator generator, ISlide slide)
```


Called to write html slide footer. Called once per each of slides.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | Oggetto di output. |
| slide | [ISlide](../../com.aspose.slides/islide) | Diapositiva che è attualmente renderizzata. |

### writeShapeStart(IHtmlGenerator generator, IShape shape) {#writeShapeStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IShape-}
```
public abstract void writeShapeStart(IHtmlGenerator generator, IShape shape)
```


Called before shape's rendering. Called once per each of shape. If this function writes anything to generator, current slide image generation will be finished, added html fragment inserted and new image will be started atop of the previous.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | Oggetto di output. |
| shape | [IShape](../../com.aspose.slides/ishape) | Forma che sta per essere renderizzata. |

### writeShapeEnd(IHtmlGenerator generator, IShape shape) {#writeShapeEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IShape-}
```
public abstract void writeShapeEnd(IHtmlGenerator generator, IShape shape)
```


Called before shape's rendering. Called once per each of shape. If this function writes anything to generator, current slide image generation will be finished, added html fragment inserted and new image will be started atop of the previous.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | Oggetto di output. |
| shape | [IShape](../../com.aspose.slides/ishape) | Forma che è stata renderizzata per ultima. |