---
title: EmbeddedWoffFontsHtmlController
second_title: Aspose.Slides para Android mediante la referencia de API Java
description: La clase del controlador de formato que se usa para incrustar fuentes en formato WOFF
type: docs
url: /es/com.aspose.slides/embeddedwofffontshtmlcontroller/
---
**Herencia:**
java.lang.Object

**Todas las interfaces implementadas:**
[com.aspose.slides.IEmbeddedWoffFontsHtmlController](../../com.aspose.slides/iembeddedwofffontshtmlcontroller)
```
public class EmbeddedWoffFontsHtmlController implements IEmbeddedWoffFontsHtmlController
```

La clase del controlador de formato que se utiliza para incrustar fuentes en formato WOFF

## Constructores

| Constructor | Descripción |
| --- | --- |
| [EmbeddedWoffFontsHtmlController()](#EmbeddedWoffFontsHtmlController--) | Crea una nueva instancia. |
| [EmbeddedWoffFontsHtmlController(IHtmlFormattingController controller)](#EmbeddedWoffFontsHtmlController-com.aspose.slides.IHtmlFormattingController-) | Crea una nueva instancia. |
## Métodos

| Método | Descripción |
| --- | --- |
| [writeDocumentStart(IHtmlGenerator generator, IPresentation presentation)](#writeDocumentStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-) |  |
| [writeDocumentEnd(IHtmlGenerator generator, IPresentation presentation)](#writeDocumentEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-) |  |
| [writeSlideStart(IHtmlGenerator generator, ISlide slide)](#writeSlideStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.ISlide-) |  |
| [writeSlideEnd(IHtmlGenerator generator, ISlide slide)](#writeSlideEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.ISlide-) |  |
| [writeShapeStart(IHtmlGenerator generator, IShape shape)](#writeShapeStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IShape-) |  |
| [writeShapeEnd(IHtmlGenerator generator, IShape shape)](#writeShapeEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IShape-) |  |
### EmbeddedWoffFontsHtmlController() {#EmbeddedWoffFontsHtmlController--}
```
public EmbeddedWoffFontsHtmlController()
```


Crea una nueva instancia.

### EmbeddedWoffFontsHtmlController(IHtmlFormattingController controller) {#EmbeddedWoffFontsHtmlController-com.aspose.slides.IHtmlFormattingController-}
```
public EmbeddedWoffFontsHtmlController(IHtmlFormattingController controller)
```


Crea una nueva instancia.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| controller | [IHtmlFormattingController](../../com.aspose.slides/ihtmlformattingcontroller) | Controlador de formato HTML. |

### writeDocumentStart(IHtmlGenerator generator, IPresentation presentation) {#writeDocumentStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-}
```
public final void writeDocumentStart(IHtmlGenerator generator, IPresentation presentation)
```


Se llama para escribir el encabezado del documento html. Se llama una vez por conversión de presentación.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) |  |
| presentation | [IPresentation](../../com.aspose.slides/ipresentation) |  |

### writeDocumentEnd(IHtmlGenerator generator, IPresentation presentation) {#writeDocumentEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-}
```
public final void writeDocumentEnd(IHtmlGenerator generator, IPresentation presentation)
```


Se llama para escribir el pie del documento html. Se llama una vez por conversión de presentación.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) |  |
| presentation | [IPresentation](../../com.aspose.slides/ipresentation) |  |

### writeSlideStart(IHtmlGenerator generator, ISlide slide) {#writeSlideStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.ISlide-}
```
public final void writeSlideStart(IHtmlGenerator generator, ISlide slide)
```


Se llama para escribir el encabezado de la diapositiva html. Se llama una vez por cada diapositiva.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) |  |
| slide | [ISlide](../../com.aspose.slides/islide) |  |

### writeSlideEnd(IHtmlGenerator generator, ISlide slide) {#writeSlideEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.ISlide-}
```
public final void writeSlideEnd(IHtmlGenerator generator, ISlide slide)
```


Se llama para escribir el pie de la diapositiva html. Se llama una vez por cada diapositiva.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) |  |
| slide | [ISlide](../../com.aspose.slides/islide) |  |

### writeShapeStart(IHtmlGenerator generator, IShape shape) {#writeShapeStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IShape-}
```
public final void writeShapeStart(IHtmlGenerator generator, IShape shape)
```


Se llama antes del renderizado de la shape. Se llama una vez por cada shape. Si esta función escribe algo en generator, la generación de la imagen de la diapositiva actual se terminará, se insertará el fragmento html añadido y se iniciará una nueva imagen encima de la anterior.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) |  |
| shape | [IShape](../../com.aspose.slides/ishape) |  |

### writeShapeEnd(IHtmlGenerator generator, IShape shape) {#writeShapeEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IShape-}
```
public final void writeShapeEnd(IHtmlGenerator generator, IShape shape)
```


Se llama antes del renderizado de la shape. Se llama una vez por cada shape. Si esta función escribe algo en generator, la generación de la imagen de la diapositiva actual se terminará, se insertará el fragmento html añadido y se iniciará una nueva imagen encima de la anterior.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) |  |
| shape | [IShape](../../com.aspose.slides/ishape) |  |