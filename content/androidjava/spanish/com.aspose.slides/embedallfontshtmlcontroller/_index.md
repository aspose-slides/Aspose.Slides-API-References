---
title: EmbedAllFontsHtmlController
second_title: Referencia de API Java de Aspose.Slides para Android
description: La clase controladora de formato a utilizar para incrustar todas las fuentes de la presentación en formato WOFF.
type: docs
url: /es/com.aspose.slides/embedallfontshtmlcontroller/
---
**Herencia:**
java.lang.Object

**Todas las interfaces implementadas:**
[com.aspose.slides.IHtmlFormattingController](../../com.aspose.slides/ihtmlformattingcontroller)
```
public class EmbedAllFontsHtmlController implements IHtmlFormattingController
```

La clase controladora de formato a utilizar para incrustar todas las fuentes de la presentación en formato WOFF.

## Constructores

| Constructor | Descripción |
| --- | --- |
| [EmbedAllFontsHtmlController()](#EmbedAllFontsHtmlController--) | Crea una nueva instancia |
| [EmbedAllFontsHtmlController(String[] fontNameExcludeList)](#EmbedAllFontsHtmlController-java.lang.String---) | Crea una nueva instancia |

## Métodos

| Método | Descripción |
| --- | --- |
| [writeDocumentStart(IHtmlGenerator generator, IPresentation presentation)](#writeDocumentStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-) | Se llama para escribir el encabezado del documento html. |
| [writeDocumentEnd(IHtmlGenerator generator, IPresentation presentation)](#writeDocumentEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-) | Se llama para escribir el pie del documento html. |
| [writeSlideStart(IHtmlGenerator generator, ISlide slide)](#writeSlideStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.ISlide-) | Se llama para escribir el encabezado de la diapositiva html. |
| [writeSlideEnd(IHtmlGenerator generator, ISlide slide)](#writeSlideEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.ISlide-) | Se llama para escribir el pie de la diapositiva html. |
| [writeShapeStart(IHtmlGenerator generator, IShape shape)](#writeShapeStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IShape-) | Se llama antes de renderizar la forma. |
| [writeShapeEnd(IHtmlGenerator generator, IShape shape)](#writeShapeEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IShape-) | Se llama antes de renderizar la forma. |
| [writeAllFonts(IHtmlGenerator generator, IPresentation presentation)](#writeAllFonts-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-) | Escribe todas las fuentes contenidas en [Presentation](../../com.aspose.slides/presentation). |
| [writeFont(IHtmlGenerator generator, IFontData originalFont, IFontData substitutedFont, String fontStyle, String fontWeight, byte[] fontData)](#writeFont-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IFontData-com.aspose.slides.IFontData-java.lang.String-java.lang.String-byte---) | Escribe datos como base64 dentro del propio documento HTML |

### EmbedAllFontsHtmlController() {#EmbedAllFontsHtmlController--}
```
public EmbedAllFontsHtmlController()
```

Crea una nueva instancia

### EmbedAllFontsHtmlController(String[] fontNameExcludeList) {#EmbedAllFontsHtmlController-java.lang.String---}
```
public EmbedAllFontsHtmlController(String[] fontNameExcludeList)
```

Crea una nueva instancia

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| fontNameExcludeList | java.lang.String[] | Fuentes a excluir de la incrustación |

### writeDocumentStart(IHtmlGenerator generator, IPresentation presentation) {#writeDocumentStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-}
```
public void writeDocumentStart(IHtmlGenerator generator, IPresentation presentation)
```

Se llama para escribir el encabezado del documento html. Se llama una vez por conversión de presentación.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | Objeto de salida. |
| presentation | [IPresentation](../../com.aspose.slides/ipresentation) | Presentación que se está renderizando actualmente. |

### writeDocumentEnd(IHtmlGenerator generator, IPresentation presentation) {#writeDocumentEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-}
```
public void writeDocumentEnd(IHtmlGenerator generator, IPresentation presentation)
```

Se llama para escribir el pie del documento html. Se llama una vez por conversión de presentación.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | Objeto de salida. |
| presentation | [IPresentation](../../com.aspose.slides/ipresentation) | Presentación que se está renderizando actualmente. |

### writeSlideStart(IHtmlGenerator generator, ISlide slide) {#writeSlideStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.ISlide-}
```
public void writeSlideStart(IHtmlGenerator generator, ISlide slide)
```

Se llama para escribir el encabezado de la diapositiva html. Se llama una vez por cada diapositiva.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | Objeto de salida. |
| slide | [ISlide](../../com.aspose.slides/islide) | Diapositiva que se está renderizando actualmente. |

### writeSlideEnd(IHtmlGenerator generator, ISlide slide) {#writeSlideEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.ISlide-}
```
public void writeSlideEnd(IHtmlGenerator generator, ISlide slide)
```

Se llama para escribir el pie de la diapositiva html. Se llama una vez por cada diapositiva.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | Objeto de salida. |
| slide | [ISlide](../../com.aspose.slides/islide) | Diapositiva que se está renderizando actualmente. |

### writeShapeStart(IHtmlGenerator generator, IShape shape) {#writeShapeStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IShape-}
```
public void writeShapeStart(IHtmlGenerator generator, IShape shape)
```

Se llama antes de renderizar la forma. Se llama una vez por cada forma. Si esta función escribe algo en el generador, la generación de la imagen de la diapositiva actual se finalizará, se insertará el fragmento html añadido y se iniciará una nueva imagen sobre la anterior.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | Objeto de salida. |
| shape | [IShape](../../com.aspose.slides/ishape) | Forma que está a punto de renderizarse. |

### writeShapeEnd(IHtmlGenerator generator, IShape shape) {#writeShapeEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IShape-}
```
public void writeShapeEnd(IHtmlGenerator generator, IShape shape)
```

Se llama antes de renderizar la forma. Se llama una vez por cada forma. Si esta función escribe algo en el generador, la generación de la imagen de la diapositiva actual se finalizará, se insertará el fragmento html añadido y se iniciará una nueva imagen sobre la anterior.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | Objeto de salida. |
| shape | [IShape](../../com.aspose.slides/ishape) | Forma que se renderiza al final. |

### writeAllFonts(IHtmlGenerator generator, IPresentation presentation) {#writeAllFonts-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-}
```
public void writeAllFonts(IHtmlGenerator generator, IPresentation presentation)
```

Escribe todas las fuentes contenidas en [Presentation](../../com.aspose.slides/presentation).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | Objeto de salida. |
| presentation | [IPresentation](../../com.aspose.slides/ipresentation) | Presentación que se está renderizando actualmente. |

### writeFont(IHtmlGenerator generator, IFontData originalFont, IFontData substitutedFont, String fontStyle, String fontWeight, byte[] fontData) {#writeFont-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IFontData-com.aspose.slides.IFontData-java.lang.String-java.lang.String-byte---}
```
public void writeFont(IHtmlGenerator generator, IFontData originalFont, IFontData substitutedFont, String fontStyle, String fontWeight, byte[] fontData)
```

Escribe datos como base64 dentro del propio documento HTML

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) | Generador HTML |
| originalFont | [IFontData](../../com.aspose.slides/ifontdata) | Fuente a serializar |
| substitutedFont | [IFontData](../../com.aspose.slides/ifontdata) | Fuente sustituida (si ocurrió sustitución de fuente), null en caso contrario |
| fontStyle | java.lang.String | Estilo de fuente |
| fontWeight | java.lang.String | Peso de fuente |
| fontData | byte[] | Datos de fuente |