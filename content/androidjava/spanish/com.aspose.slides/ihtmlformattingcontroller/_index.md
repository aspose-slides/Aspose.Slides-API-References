---
title: IHtmlFormattingController
second_title: Aspose.Slides for Android via Java API Reference
description: Controls a html file generation.
type: docs
url: /es/com.aspose.slides/ihtmlformattingcontroller/
---```
public interface IHtmlFormattingController
```

Controla la generación de un archivo html.
## Métodos

| Método | Descripción |
| --- | --- |
| [writeDocumentStart(IHtmlGenerator generator, IPresentation presentation)](#writeDocumentStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-) | Se llama para escribir el encabezado del documento html. |
| [writeDocumentEnd(IHtmlGenerator generator, IPresentation presentation)](#writeDocumentEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-) | Se llama para escribir el pie del documento html. |
| [writeSlideStart(IHtmlGenerator generator, ISlide slide)](#writeSlideStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.ISlide-) | Se llama para escribir el encabezado de la diapositiva html. |
| [writeSlideEnd(IHtmlGenerator generator, ISlide slide)](#writeSlideEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.ISlide-) | Se llama para escribir el pie de la diapositiva html. |
| [writeShapeStart(IHtmlGenerator generator, IShape shape)](#writeShapeStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IShape-) | Se llama antes de renderizar la forma. |
| [writeShapeEnd(IHtmlGenerator generator, IShape shape)](#writeShapeEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IShape-) | Se llama antes de renderizar la forma. |
### writeDocumentStart(IHtmlGenerator generator, IPresentation presentation) {#writeDocumentStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-}
```
public abstract void writeDocumentStart(IHtmlGenerator generator, IPresentation presentation)
```

Se llama para escribir el encabezado del documento html. Se llama una vez por conversión de presentación.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | Objeto de salida. |
| presentation | [IPresentation](../../com.aspose.slides/ipresentation) | Presentación que se está renderizando actualmente. |

### writeDocumentEnd(IHtmlGenerator generator, IPresentation presentation) {#writeDocumentEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-}
```
public abstract void writeDocumentEnd(IHtmlGenerator generator, IPresentation presentation)
```

Se llama para escribir el pie del documento html. Se llama una vez por conversión de presentación.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | Objeto de salida. |
| presentation | [IPresentation](../../com.aspose.slides/ipresentation) | Presentación que se está renderizando actualmente. |

### writeSlideStart(IHtmlGenerator generator, ISlide slide) {#writeSlideStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.ISlide-}
```
public abstract void writeSlideStart(IHtmlGenerator generator, ISlide slide)
```

Se llama para escribir el encabezado de la diapositiva html. Se llama una vez por cada diapositiva.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | Objeto de salida. |
| slide | [ISlide](../../com.aspose.slides/islide) | Diapositiva que se está renderizando actualmente. |

### writeSlideEnd(IHtmlGenerator generator, ISlide slide) {#writeSlideEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.ISlide-}
```
public abstract void writeSlideEnd(IHtmlGenerator generator, ISlide slide)
```

Se llama para escribir el pie de la diapositiva html. Se llama una vez por cada diapositiva.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | Objeto de salida. |
| slide | [ISlide](../../com.aspose.slides/islide) | Diapositiva que se está renderizando actualmente. |

### writeShapeStart(IHtmlGenerator generator, IShape shape) {#writeShapeStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IShape-}
```
public abstract void writeShapeStart(IHtmlGenerator generator, IShape shape)
```

Se llama antes de renderizar la forma. Se llama una vez por cada forma. Si esta función escribe algo en generator, la generación de la imagen de la diapositiva actual se completará, se insertará el fragmento html añadido y se iniciará una nueva imagen sobre la anterior.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | Objeto de salida. |
| shape | [IShape](../../com.aspose.slides/ishape) | Forma que está a punto de renderizarse. |

### writeShapeEnd(IHtmlGenerator generator, IShape shape) {#writeShapeEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IShape-}
```
public abstract void writeShapeEnd(IHtmlGenerator generator, IShape shape)
```

Se llama antes de renderizar la forma. Se llama una vez por cada forma. Si esta función escribe algo en generator, la generación de la imagen de la diapositiva actual se completará, se insertará el fragmento html añadido y se iniciará una nueva imagen sobre la anterior.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | Objeto de salida. |
| shape | [IShape](../../com.aspose.slides/ishape) | Forma que se renderiza al final. |