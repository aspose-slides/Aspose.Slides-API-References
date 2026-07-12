---
title: ResponsiveHtmlController
second_title: Aspose.Slides para Android vía Referencia de API Java
description: Controlador HTML Responsivo
type: docs
url: /es/com.aspose.slides/responsivehtmlcontroller/
---
**Herencia:**
java.lang.Object

**Todas las interfaces implementadas:**
[com.aspose.slides.IResponsiveHtmlController](../../com.aspose.slides/iresponsivehtmlcontroller)
```
public class ResponsiveHtmlController implements IResponsiveHtmlController
```

Responsive HTML Controller
## Constructores

| Constructor | Descripción |
| --- | --- |
| [ResponsiveHtmlController()](#ResponsiveHtmlController--) | Crea una nueva instancia |
| [ResponsiveHtmlController(IHtmlFormattingController controller)](#ResponsiveHtmlController-com.aspose.slides.IHtmlFormattingController-) | Crea una nueva instancia |
## Métodos

| Método | Descripción |
| --- | --- |
| [writeDocumentStart(IHtmlGenerator generator, IPresentation presentation)](#writeDocumentStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-) |  |
| [writeDocumentEnd(IHtmlGenerator generator, IPresentation presentation)](#writeDocumentEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-) |  |
| [writeSlideStart(IHtmlGenerator generator, ISlide slide)](#writeSlideStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.ISlide-) |  |
| [writeSlideEnd(IHtmlGenerator generator, ISlide slide)](#writeSlideEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.ISlide-) |  |
| [writeShapeStart(IHtmlGenerator generator, IShape shape)](#writeShapeStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IShape-) |  |
| [writeShapeEnd(IHtmlGenerator generator, IShape shape)](#writeShapeEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IShape-) |  |
### ResponsiveHtmlController() {#ResponsiveHtmlController--}
```
public ResponsiveHtmlController()
```

Crea una nueva instancia

### ResponsiveHtmlController(IHtmlFormattingController controller) {#ResponsiveHtmlController-com.aspose.slides.IHtmlFormattingController-}
```
public ResponsiveHtmlController(IHtmlFormattingController controller)
```

Crea una nueva instancia

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| controller | [IHtmlFormattingController](../../com.aspose.slides/ihtmlformattingcontroller) | controlador de formato HTML |

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

Se llama antes del renderizado de shape. Se llama una vez por cada shape. Si esta función escribe algo en generator, la generación de la imagen de la diapositiva actual terminará, se insertará el fragmento html añadido y se iniciará una nueva imagen sobre la anterior.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) |  |
| shape | [IShape](../../com.aspose.slides/ishape) |  |

### writeShapeEnd(IHtmlGenerator generator, IShape shape) {#writeShapeEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IShape-}
```
public final void writeShapeEnd(IHtmlGenerator generator, IShape shape)
```

Se llama antes del renderizado de shape. Se llama una vez por cada shape. Si esta función escribe algo en generator, la generación de la imagen de la diapositiva actual terminará, se insertará el fragmento html añadido y se iniciará una nueva imagen sobre la anterior.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) |  |
| shape | [IShape](../../com.aspose.slides/ishape) |  |