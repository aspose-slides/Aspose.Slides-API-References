---
title: IShapeCollection
second_title: Referencia de API de Aspose.Slides para Android a través de Java
description: Representa una colección de formas.
type: docs
url: /es/com.aspose.slides/ishapecollection/
---
**Todas las interfaces implementadas:**
com.aspose.slides.IGenericCollection
```
public interface IShapeCollection extends IGenericCollection<IShape>
```

Representa una colección de formas.
## Métodos

| Método | Descripción |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Obtiene el elemento en el índice especificado. |
| [getParentGroup()](#getParentGroup--) | Obtiene el objeto de forma de grupo padre para la colección de formas. |
| [addChart(int type, float x, float y, float width, float height)](#addChart-int-float-float-float-float-) | Crea un nuevo gráfico, lo inicializa con datos de series de ejemplo y configuraciones, y lo agrega al final de la colección de formas. |
| [addChart(int type, float x, float y, float width, float height, boolean initWithSample)](#addChart-int-float-float-float-float-boolean-) | Crea un nuevo gráfico, lo inicializa con datos de series de ejemplo y configuraciones, y lo agrega al final de la colección de formas. |
| [addSmartArt(float x, float y, float width, float height, int layoutType)](#addSmartArt-float-float-float-float-int-) | Crea un diagrama SmartArt y lo agrega al final de la colección de formas. |
| [insertChart(int type, float x, float y, float width, float height, int index)](#insertChart-int-float-float-float-float-int-) | Crea un nuevo gráfico, lo inicializa con datos de series de ejemplo y configuraciones, e lo inserta en la colección de formas en el índice especificado. |
| [insertChart(int type, float x, float y, float width, float height, int index, boolean initWithSample)](#insertChart-int-float-float-float-float-int-boolean-) | Crea un nuevo gráfico, lo inicializa con datos de series de ejemplo y configuraciones, e lo inserta en la colección de formas en el índice especificado. |
| [addOleObjectFrame(float x, float y, float width, float height, IOleEmbeddedDataInfo dataInfo)](#addOleObjectFrame-float-float-float-float-com.aspose.slides.IOleEmbeddedDataInfo-) | Crea un nuevo marco de objeto OLE y lo agrega al final de la colección de formas. |
| [addOleObjectFrame(float x, float y, float width, float height, String className, String path)](#addOleObjectFrame-float-float-float-float-java.lang.String-java.lang.String-) | Crea un nuevo marco de objeto OLE y lo agrega al final de la colección de formas. |
| [insertOleObjectFrame(int index, float x, float y, float width, float height, IOleEmbeddedDataInfo dataInfo)](#insertOleObjectFrame-int-float-float-float-float-com.aspose.slides.IOleEmbeddedDataInfo-) | Crea un nuevo marco de objeto OLE y lo inserta en la colección de formas en el índice especificado. |
| [insertOleObjectFrame(int index, float x, float y, float width, float height, String className, String path)](#insertOleObjectFrame-int-float-float-float-float-java.lang.String-java.lang.String-) | Crea un nuevo marco de objeto OLE y lo inserta en la colección de formas en el índice especificado. |
| [addZoomFrame(float x, float y, float width, float height, ISlide slide)](#addZoomFrame-float-float-float-float-com.aspose.slides.ISlide-) | Crea un nuevo marco de Zoom y lo agrega al final de la colección de formas. |
| [addZoomFrame(float x, float y, float width, float height, ISlide slide, IPPImage image)](#addZoomFrame-float-float-float-float-com.aspose.slides.ISlide-com.aspose.slides.IPPImage-) | Crea un nuevo marco de Zoom y lo agrega al final de la colección de formas. |
| [insertZoomFrame(int index, float x, float y, float width, float height, ISlide slide)](#insertZoomFrame-int-float-float-float-float-com.aspose.slides.ISlide-) | Crea un nuevo marco de Zoom y lo inserta en la colección de formas en el índice especificado. |
| [insertZoomFrame(int index, float x, float y, float width, float height, ISlide slide, IPPImage image)](#insertZoomFrame-int-float-float-float-float-com.aspose.slides.ISlide-com.aspose.slides.IPPImage-) | Crea un nuevo marco de Zoom con una imagen predefinida y lo inserta en la colección de formas en el índice especificado. |
| [addSectionZoomFrame(float x, float y, float width, float height, ISection section)](#addSectionZoomFrame-float-float-float-float-com.aspose.slides.ISection-) | Crea un nuevo marco de Zoom de sección y lo agrega al final de la colección de formas. |
| [addSectionZoomFrame(float x, float y, float width, float height, ISection section, IPPImage image)](#addSectionZoomFrame-float-float-float-float-com.aspose.slides.ISection-com.aspose.slides.IPPImage-) | Crea un nuevo marco de Zoom de sección con una imagen predefinida y lo agrega al final de la colección de formas. |
| [insertSectionZoomFrame(int index, float x, float y, float width, float height, ISection section)](#insertSectionZoomFrame-int-float-float-float-float-com.aspose.slides.ISection-) | Crea un nuevo marco de Zoom de sección y lo inserta en la colección de formas en el índice especificado. |
| [insertSectionZoomFrame(int index, float x, float y, float width, float height, ISection section, IPPImage image)](#insertSectionZoomFrame-int-float-float-float-float-com.aspose.slides.ISection-com.aspose.slides.IPPImage-) | Crea un nuevo marco de Zoom de sección con una imagen predefinida y lo inserta en la colección de formas en el índice especificado. |
| [addSummaryZoomFrame(float x, float y, float width, float height)](#addSummaryZoomFrame-float-float-float-float-) | Crea un nuevo marco de Zoom resumido y lo agrega al final de la colección de formas. |
| [insertSummaryZoomFrame(int index, float x, float y, float width, float height)](#insertSummaryZoomFrame-int-float-float-float-float-) | Crea un nuevo marco de Zoom resumido y lo inserta en la colección de formas en el índice especificado. |
| [addVideoFrame(float x, float y, float width, float height, String fname)](#addVideoFrame-float-float-float-float-java.lang.String-) | Crea un nuevo marco de vídeo y lo agrega al final de la colección de formas. |
| [addVideoFrame(float x, float y, float width, float height, IVideo video)](#addVideoFrame-float-float-float-float-com.aspose.slides.IVideo-) | Crea un nuevo marco de vídeo y lo agrega al final de la colección de formas. |
| [insertVideoFrame(int index, float x, float y, float width, float height, String fname)](#insertVideoFrame-int-float-float-float-float-java.lang.String-) | Crea un nuevo marco de vídeo y lo inserta en la colección de formas en el índice especificado. |
| [addAudioFrameCD(float x, float y, float width, float height)](#addAudioFrameCD-float-float-float-float-) | Crea un nuevo marco de audio vinculado a una pista de CD y lo agrega al final de la colección de formas. |
| [insertAudioFrameCD(int index, float x, float y, float width, float height)](#insertAudioFrameCD-int-float-float-float-float-) | Crea un nuevo marco de audio vinculado a una pista de CD y lo inserta en la colección de formas en el índice especificado. |
| [addAudioFrameLinked(float x, float y, float width, float height, String fname)](#addAudioFrameLinked-float-float-float-float-java.lang.String-) | Crea un nuevo marco de audio vinculado a un archivo de audio externo y lo agrega al final de la colección de formas. |
| [insertAudioFrameLinked(int index, float x, float y, float width, float height, String fname)](#insertAudioFrameLinked-int-float-float-float-float-java.lang.String-) | Crea un nuevo marco de audio vinculado a un archivo de audio externo y lo inserta en la colección de formas en el índice especificado. |
| [addAudioFrameEmbedded(float x, float y, float width, float height, InputStream audio_stream)](#addAudioFrameEmbedded-float-float-float-float-java.io.InputStream-) | Crea un nuevo marco de audio con un archivo WAV incrustado y lo agrega al final de la colección de formas. |
| [addAudioFrameEmbedded(float x, float y, float width, float height, IAudio audio)](#addAudioFrameEmbedded-float-float-float-float-com.aspose.slides.IAudio-) | Crea un nuevo marco de audio y lo agrega al final de la colección de formas usando un objeto de audio existente de la lista Presentation.Audios. |
| [insertAudioFrameEmbedded(int index, float x, float y, float width, float height, InputStream audio_stream)](#insertAudioFrameEmbedded-int-float-float-float-float-java.io.InputStream-) | Crea un nuevo marco de audio con un archivo WAV incrustado y lo inserta en la colección de formas en el índice especificado. |
| [insertAudioFrameEmbedded(int index, float x, float y, float width, float height, IAudio audio)](#insertAudioFrameEmbedded-int-float-float-float-float-com.aspose.slides.IAudio-) | Crea un nuevo marco de audio y lo inserta en la colección de formas en el índice especificado usando un objeto de audio existente de la lista Presentation.Audios. |
| [indexOf(IShape shape)](#indexOf-com.aspose.slides.IShape-) | Devuelve el índice basado en cero de la primera aparición de la forma especificada en la colección. |
| [toArray()](#toArray--) | Crea y devuelve una matriz que contiene todas las formas. |
| [toArray(int startIndex, int count)](#toArray-int-int-) | Crea y devuelve una matriz que contiene todas las formas en el rango especificado. |
| [reorder(int index, IShape shape)](#reorder-int-com.aspose.slides.IShape-) | Mueve la forma especificada a una nueva posición dentro de la colección de formas. |
| [reorder(int index, IShape[] shapes)](#reorder-int-com.aspose.slides.IShape...-) | Mueve las formas especificadas dentro de la colección de formas, colocándolas a partir del índice proporcionado. |
| [addAutoShape(int shapeType, float x, float y, float width, float height)](#addAutoShape-int-float-float-float-float-) | Crea una nueva forma automática con formato predeterminado y la agrega al final de la colección de formas. |
| [addAutoShape(int shapeType, float x, float y, float width, float height, boolean createFromTemplate)](#addAutoShape-int-float-float-float-float-boolean-) | Crea una nueva forma automática y la agrega al final de la colección de formas, opcionalmente inicializándola con el formato predeterminado de la plantilla. |
| [addMathShape(float x, float y, float width, float height)](#addMathShape-float-float-float-float-) | Crea una nueva forma automática rectangular para alojar contenido matemático y la agrega al final de la colección de formas. |
| [insertAutoShape(int index, int shapeType, float x, float y, float width, float height)](#insertAutoShape-int-int-float-float-float-float-) | Crea una nueva forma automática y la inserta en la colección de formas en el índice especificado, aplicando el formato predeterminado de la plantilla. |
| [insertAutoShape(int index, int shapeType, float x, float y, float width, float height, boolean createFromTemplate)](#insertAutoShape-int-int-float-float-float-float-boolean-) | Crea una nueva forma automática y la inserta en la colección de formas en el índice especificado, opcionalmente inicializándola con el estilo predeterminado de la plantilla. |
| [addGroupShape()](#addGroupShape--) | Crea una nueva forma de grupo vacía y la agrega al final de la colección de formas. |
| [addGroupShape(ISvgImage svgImage, float x, float y, float width, float height)](#addGroupShape-com.aspose.slides.ISvgImage-float-float-float-float-) | Crea una nueva forma de grupo, convierte la imagen SVG especificada en formas individuales y agrega el grupo resultante al final de la colección de formas. |
| [insertGroupShape(int index)](#insertGroupShape-int-) | Crea una nueva forma de grupo vacía y la inserta en la colección de formas en el índice especificado. |
| [addConnector(int shapeType, float x, float y, float width, float height)](#addConnector-int-float-float-float-float-) | Crea una nueva forma conectora con estilo predeterminado de la plantilla y la agrega al final de la colección de formas. |
| [addConnector(int shapeType, float x, float y, float width, float height, boolean createFromTemplate)](#addConnector-int-float-float-float-float-boolean-) | Crea una nueva forma conectora y la agrega al final de la colección de formas, opcionalmente aplicando el estilo predeterminado de la plantilla. |
| [insertConnector(int index, int shapeType, float x, float y, float width, float height)](#insertConnector-int-int-float-float-float-float-) | Crea una nueva forma conectora y la inserta en la colección de formas en el índice especificado, aplicando el estilo predeterminado de la plantilla. |
| [insertConnector(int index, int shapeType, float x, float y, float width, float height, boolean createFromTemplate)](#insertConnector-int-int-float-float-float-float-boolean-) | Crea una nueva forma conectora y la inserta en la colección de formas en el índice especificado, opcionalmente aplicando el estilo predeterminado de la plantilla. |
| [addPictureFrame(int shapeType, float x, float y, float width, float height, IPPImage image)](#addPictureFrame-int-float-float-float-float-com.aspose.slides.IPPImage-) | Crea un nuevo marco de imagen que contiene la imagen especificada y lo agrega al final de la colección de formas. |
| [insertPictureFrame(int index, int shapeType, float x, float y, float width, float height, IPPImage image)](#insertPictureFrame-int-int-float-float-float-float-com.aspose.slides.IPPImage-) | Crea un nuevo marco de imagen que contiene la imagen especificada y lo inserta en la colección de formas en el índice especificado. |
| [addTable(float x, float y, double[] columnWidths, double[] rowHeights)](#addTable-float-float-double---double---) | Crea una nueva tabla y la agrega al final de la colección de formas. |
| [insertTable(int index, float x, float y, double[] columnWidths, double[] rowHeights)](#insertTable-int-float-float-double---double---) | Crea una nueva tabla y la inserta en la colección de formas en el índice especificado. |
| [removeAt(int index)](#removeAt-int-) | Elimina la forma en el índice especificado de la colección de formas. |
| [remove(IShape shape)](#remove-com.aspose.slides.IShape-) | Elimina la primera aparición de la forma especificada de la colección de formas. |
| [clear()](#clear--) | Elimina todas las formas de la colección de formas. |
| [addClone(IShape sourceShape, float x, float y, float width, float height)](#addClone-com.aspose.slides.IShape-float-float-float-float-) | Crea una copia de la forma especificada y la agrega al final de la colección de formas. |
| [addClone(IShape sourceShape, float x, float y)](#addClone-com.aspose.slides.IShape-float-float-) | Crea una copia de la forma especificada y la agrega al final de la colección de formas. |
| [addClone(IShape sourceShape)](#addClone-com.aspose.slides.IShape-) | Crea una copia de la forma especificada y la agrega al final de la colección de formas. |
| [insertClone(int index, IShape sourceShape, float x, float y, float width, float height)](#insertClone-int-com.aspose.slides.IShape-float-float-float-float-) | Crea una copia de la forma especificada y la inserta en la colección de formas en el índice especificado. |
| [insertClone(int index, IShape sourceShape, float x, float y)](#insertClone-int-com.aspose.slides.IShape-float-float-) | Crea una copia de la forma especificada y la inserta en la colección de formas en el índice especificado. |
| [insertClone(int index, IShape sourceShape)](#insertClone-int-com.aspose.slides.IShape-) | Crea una copia de la forma especificada y la inserta en la colección de formas en el índice especificado. |

### get_Item(int index) {#get-Item-int-}
```
public abstract IShape get_Item(int index)
```

Obtiene el elemento en el índice especificado. Solo lectura [IShape](../../com.aspose.slides/ishape).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index | int |  |

**Devuelve:**
[IShape](../../com.aspose.slides/ishape)

### getParentGroup() {#getParentGroup--}
```
public abstract IGroupShape getParentGroup()
```

Obtiene el objeto de forma de grupo padre para la colección de formas. Solo lectura [IGroupShape](../../com.aspose.slides/igroupshape).

**Devuelve:**
[IGroupShape](../../com.aspose.slides/igroupshape)

### addChart(int type, float x, float y, float width, float height) {#addChart-int-float-float-float-float-}
```
public abstract IChart addChart(int type, float x, float y, float width, float height)
```

Crea un nuevo gráfico, lo inicializa con datos de series de ejemplo y configuraciones, y lo agrega al final de la colección de formas.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| type | int | El tipo de gráfico a agregar. |
| x | float | La coordenada x del nuevo gráfico, en puntos. |
| y | float | La coordenada y del nuevo gráfico, en puntos. |
| width | float | El ancho del gráfico, en puntos. |
| height | float | La altura del gráfico, en puntos. |

**Devuelve:**
[IChart](../../com.aspose.slides/ichart) - El nuevo [IChart](../../com.aspose.slides/ichart).

### addChart(int type, float x, float y, float width, float height, boolean initWithSample) {#addChart-int-float-float-float-float-boolean-}
```
public abstract IChart addChart(int type, float x, float y, float width, float height, boolean initWithSample)
```

Crea un nuevo gráfico, lo inicializa con datos de series de ejemplo y configuraciones, y lo agrega al final de la colección de formas.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| type | int | El tipo de gráfico a agregar. |
| x | float | La coordenada x del nuevo gráfico, en puntos. |
| y | float | La coordenada y del nuevo gráfico, en puntos. |
| width | float | El ancho del gráfico, en puntos. |
| height | float | La altura del gráfico, en puntos. |
| initWithSample | boolean | Verdadero para inicializar el nuevo gráfico con datos de series de ejemplo y configuraciones; falso para crear el gráfico sin series y solo con configuraciones mínimas, lo que acelera la creación. |

**Devuelve:**
[IChart](../../com.aspose.slides/ichart) - El nuevo [IChart](../../com.aspose.slides/ichart).

### addSmartArt(float x, float y, float width, float height, int layoutType) {#addSmartArt-float-float-float-float-int-}
```
public abstract ISmartArt addSmartArt(float x, float y, float width, float height, int layoutType)
```

Crea un diagrama SmartArt y lo agrega al final de la colección de formas.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>       ISlide slide = pres.getSlides().get_Item(0);
>       ISmartArt smart = slide.getShapes().addSmartArt(0, 0, 400, 400, SmartArtLayoutType.BasicBlockList);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| x | float | La coordenada x del marco del diagrama, en puntos. |
| y | float | La coordenada y del marco del diagrama, en puntos. |
| width | float | El ancho del marco del diagrama, en puntos. |
| height | float | La altura del marco del diagrama, en puntos. |
| layoutType | int | El tipo de diseño de SmartArt. |

**Devuelve:**
[ISmartArt](../../com.aspose.slides/ismartart) - El nuevo [ISmartArt](../../com.aspose.slides/ismartart).

### insertChart(int type, float x, float y, float width, float height, int index) {#insertChart-int-float-float-float-float-int-}
```
public abstract IChart insertChart(int type, float x, float y, float width, float height, int index)
```

Crea un nuevo gráfico, lo inicializa con datos de series de ejemplo y configuraciones, y lo inserta en la colección de formas en el índice especificado.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| type | int | El tipo de gráfico a crear. |
| x | float | La coordenada x del nuevo gráfico, en puntos. |
| y | float | La coordenada y del nuevo gráfico, en puntos. |
| width | float | El ancho del nuevo gráfico, en puntos. |
| height | float | La altura del nuevo gráfico, en puntos. |
| index | int | El índice basado en cero donde insertar el nuevo gráfico en la colección de formas. |

**Devuelve:**
[IChart](../../com.aspose.slides/ichart) - El nuevo [IChart](../../com.aspose.slides/ichart).

### insertChart(int type, float x, float y, float width, float height, int index, boolean initWithSample) {#insertChart-int-float-float-float-float-int-boolean-}
```
public abstract IChart insertChart(int type, float x, float y, float width, float height, int index, boolean initWithSample)
```

Crea un nuevo gráfico, lo inicializa con datos de series de ejemplo y configuraciones, y lo inserta en la colección de formas en el índice especificado.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| type | int | El tipo de gráfico a crear. |
| x | float | La coordenada x del nuevo gráfico, en puntos. |
| y | float | La coordenada y del nuevo gráfico, en puntos. |
| width | float | El ancho del nuevo gráfico, en puntos. |
| height | float | La altura del nuevo gráfico, en puntos. |
| index | int | El índice basado en cero donde insertar el nuevo gráfico en la colección de formas. |
| initWithSample | boolean | Verdadero para inicializar el nuevo gráfico con datos de series de ejemplo y configuraciones; falso para crear el gráfico sin series y solo con configuraciones mínimas, lo que acelera la creación. |

**Devuelve:**
[IChart](../../com.aspose.slides/ichart) - El nuevo [IChart](../../com.aspose.slides/ichart).

### addOleObjectFrame(float x, float y, float width, float height, IOleEmbeddedDataInfo dataInfo) {#addOleObjectFrame-float-float-float-float-com.aspose.slides.IOleEmbeddedDataInfo-}
```
public abstract IOleObjectFrame addOleObjectFrame(float x, float y, float width, float height, IOleEmbeddedDataInfo dataInfo)
```

Crea un nuevo marco de objeto OLE y lo agrega al final de la colección de formas.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| x | float | La coordenada x del nuevo marco OLE, en puntos. |
| y | float | La coordenada y del nuevo marco OLE, en puntos. |
| width | float | El ancho del nuevo marco OLE, en puntos. |
| height | float | La altura del nuevo marco OLE, en puntos. |
| dataInfo | [IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo) | La información de datos OLE incrustada ([IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo)). |

**Devuelve:**
[IOleObjectFrame](../../com.aspose.slides/ioleobjectframe) - El nuevo [IOleObjectFrame](../../com.aspose.slides/ioleobjectframe).

### addOleObjectFrame(float x, float y, float width, float height, String className, String path) {#addOleObjectFrame-float-float-float-float-java.lang.String-java.lang.String-}
```
public abstract IOleObjectFrame addOleObjectFrame(float x, float y, float width, float height, String className, String path)
```

Crea un nuevo marco de objeto OLE y lo agrega al final de la colección de formas.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| x | float | La coordenada x del nuevo marco OLE, en puntos. |
| y | float | La coordenada y del nuevo marco OLE, en puntos. |
| width | float | El ancho del nuevo marco OLE, en puntos. |
| height | float | La altura del nuevo marco OLE, en puntos. |
| className | java.lang.String | El nombre de clase del objeto OLE. |
| path | java.lang.String | La ruta al archivo vinculado.

Esta ruta se almacena literalmente en la presentación. Si se especifica una ruta relativa, el archivo será inaccesible al abrir la presentación desde otro directorio. |

**Devuelve:**
[IOleObjectFrame](../../com.aspose.slides/ioleobjectframe) - El nuevo [IOleObjectFrame](../../com.aspose.slides/ioleobjectframe).

### insertOleObjectFrame(int index, float x, float y, float width, float height, IOleEmbeddedDataInfo dataInfo) {#insertOleObjectFrame-int-float-float-float-float-com.aspose.slides.IOleEmbeddedDataInfo-}
```
public abstract IOleObjectFrame insertOleObjectFrame(int index, float x, float y, float width, float height, IOleEmbeddedDataInfo dataInfo)
```

Crea un nuevo marco de objeto OLE y lo inserta en la colección de formas en el índice especificado.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index | int | El índice basado en cero donde insertar el marco de objeto OLE. |
| x | float | La coordenada x del nuevo marco OLE, en puntos. |
| y | float | La coordenada y del nuevo marco OLE, en puntos. |
| width | float | El ancho del nuevo marco OLE, en puntos. |
| height | float | La altura del nuevo marco OLE, en puntos. |
| dataInfo | [IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo) | La información de datos OLE incrustada ([IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo)). |

**Devuelve:**
[IOleObjectFrame](../../com.aspose.slides/ioleobjectframe) - El nuevo [IOleObjectFrame](../../com.aspose.slides/ioleobjectframe).

### insertOleObjectFrame(int index, float x, float y, float width, float height, String className, String path) {#insertOleObjectFrame-int-float-float-float-float-java.lang.String-java.lang.String-}
```
public abstract IOleObjectFrame insertOleObjectFrame(int index, float x, float y, float width, float height, String className, String path)
```

Crea un nuevo marco de objeto OLE y lo inserta en la colección de formas en el índice especificado.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index | int | El índice basado en cero donde insertar el marco de objeto OLE. |
| x | float | La coordenada x del nuevo marco OLE, en puntos. |
| y | float | La coordenada y del nuevo marco OLE, en puntos. |
| width | float | El ancho del nuevo marco OLE, en puntos. |
| height | float | La altura del nuevo marco OLE, en puntos. |
| className | java.lang.String | El nombre de clase del objeto OLE. |
| path | java.lang.String | La ruta al archivo vinculado.

Esta ruta se almacena literalmente en la presentación. Si se especifica una ruta relativa, el archivo será inaccesible al abrir la presentación desde otro directorio. |

**Devuelve:**
[IOleObjectFrame](../../com.aspose.slides/ioleobjectframe) - El nuevo [IOleObjectFrame](../../com.aspose.slides/ioleobjectframe).

### addZoomFrame(float x, float y, float width, float height, ISlide slide) {#addZoomFrame-float-float-float-float-com.aspose.slides.ISlide-}
```
public abstract IZoomFrame addZoomFrame(float x, float y, float width, float height, ISlide slide)
```

Crea un nuevo marco de Zoom y lo agrega al final de la colección de formas.

--------------------

> ```
> Este ejemplo muestra cómo agregar un objeto Zoom al final de una colección
>  (suponiendo que hay al menos dos diapositivas en la presentación "Presentation.pptx"):
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addZoomFrame(150, 20, 50, 50, pres.getSlides().get_Item(1));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| x | float | La coordenada x del nuevo marco de Zoom, en puntos. |
| y | float | La coordenada y del nuevo marco de Zoom, en puntos. |
| width | float | El ancho del nuevo marco de Zoom, en puntos. |
| height | float | La altura del nuevo marco de Zoom, en puntos. |
| slide | [ISlide](../../com.aspose.slides/islide) | La [ISlide](../../com.aspose.slides/islide) referenciada por el marco de Zoom; debe pertenecer a esta presentación. |

**Devuelve:**
[IZoomFrame](../../com.aspose.slides/izoomframe) - El nuevo [IZoomFrame](../../com.aspose.slides/izoomframe).

### addZoomFrame(float x, float y, float width, float height, ISlide slide, IPPImage image) {#addZoomFrame-float-float-float-float-com.aspose.slides.ISlide-com.aspose.slides.IPPImage-}
```
public abstract IZoomFrame addZoomFrame(float x, float y, float width, float height, ISlide slide, IPPImage image)
```

Crea un nuevo marco de Zoom y lo agrega al final de la colección de formas.

--------------------

> ```
> Este ejemplo muestra cómo agregar un objeto Zoom al final de una colección
>  (asuma que hay al menos dos diapositivas en la presentación "Presentation.pptx"):
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      IPPImage image = pres.getImages().addImage(imageBytes);
>      IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addZoomFrame(150, 20, 50, 50, pres.getSlides().get_Item(1), image);
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| x | float | La coordenada x del nuevo marco de Zoom, en puntos. |
| y | float | La coordenada y del nuevo marco de Zoom, en puntos. |
| width | float | El ancho del nuevo marco de Zoom, en puntos. |
| height | float | La altura del nuevo marco de Zoom, en puntos. |
| slide | [ISlide](../../com.aspose.slides/islide) | La [ISlide](../../com.aspose.slides/islide) referenciada por el marco de Zoom; debe pertenecer a esta presentación. |
| image | [IPPImage](../../com.aspose.slides/ippimage) | La imagen para la diapositiva referenciada [IPPImage](../../com.aspose.slides/ippimage). |

**Devuelve:**
[IZoomFrame](../../com.aspose.slides/izoomframe) - El nuevo [IZoomFrame](../../com.aspose.slides/izoomframe).

### insertZoomFrame(int index, float x, float y, float width, float height, ISlide slide) {#insertZoomFrame-int-float-float-float-float-com.aspose.slides.ISlide-}
```
public abstract IZoomFrame insertZoomFrame(int index, float x, float y, float width, float height, ISlide slide)
```

Crea un nuevo marco de Zoom y lo inserta en la colección de formas en el índice especificado.

--------------------

> ```
> Este ejemplo muestra la creación e inserción de un objeto Zoom en el índice especificado de una colección
>  (suponga que hay al menos dos diapositivas en la presentación "Presentation.pptx"):
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().insertZoomFrame(2, 150, 20, 50, 50, pres.getSlides().get_Item(1));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index | int | El índice basado en cero donde insertar el marco de Zoom. |
| x | float | La coordenada x del nuevo marco de Zoom, en puntos. |
| y | float | La coordenada y del nuevo marco de Zoom, en puntos. |
| width | float | El ancho del nuevo marco de Zoom, en puntos. |
| height | float | La altura del nuevo marco de Zoom, en puntos. |
| slide | [ISlide](../../com.aspose.slides/islide) | La [ISlide](../../com.aspose.slides/islide) referenciada por el marco de Zoom. |

**Devuelve:**
[IZoomFrame](../../com.aspose.slides/izoomframe) - El nuevo [IZoomFrame](../../com.aspose.slides/izoomframe).

### insertZoomFrame(int index, float x, float y, float width, float height, ISlide slide, IPPImage image) {#insertZoomFrame-int-float-float-float-float-com.aspose.slides.ISlide-com.aspose.slides.IPPImage-}
```
public abstract IZoomFrame insertZoomFrame(int index, float x, float y, float width, float height, ISlide slide, IPPImage image)
```

Crea un nuevo marco de Zoom con una imagen predefinida y lo inserta en la colección de formas en el índice especificado.

--------------------

> ```
> Este ejemplo muestra la creación e inserción de un objeto Zoom en el índice especificado de una colección
>  (asuma que hay al menos dos diapositivas en la presentación "Presentation.pptx"):
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      IPPImage image = pres.getImages().addImage(imageBytes);
>      IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().insertZoomFrame(2, 150, 20, 50, 50, pres.getSlides().get_Item(1), image);
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index | int | El índice basado en cero donde insertar el marco de Zoom. |
| x | float | La coordenada x del nuevo marco de Zoom, en puntos. |
| y | float | La coordenada y del nuevo marco de Zoom, en puntos. |
| width | float | El ancho del nuevo marco de Zoom, en puntos. |
| height | float | La altura del nuevo marco de Zoom, en puntos. |
| slide | [ISlide](../../com.aspose.slides/islide) | La [ISlide](../../com.aspose.slides/islide) referenciada por el marco de Zoom. |
| image | [IPPImage](../../com.aspose.slides/ippimage) | La imagen para la diapositiva referenciada [IPPImage](../../com.aspose.slides/ippimage). |

**Devuelve:**
[IZoomFrame](../../com.aspose.slides/izoomframe) - El nuevo [IZoomFrame](../../com.aspose.slides/izoomframe).

### addSectionZoomFrame(float x, float y, float width, float height, ISection section) {#addSectionZoomFrame-float-float-float-float-com.aspose.slides.ISection-}
```
public abstract ISectionZoomFrame addSectionZoomFrame(float x, float y, float width, float height, ISection section)
```

Crea un nuevo marco de Zoom de sección y lo agrega al final de la colección de formas.

--------------------

> ```
> Este ejemplo muestra cómo agregar un objeto Section Zoom al final de una colección
>  (suponga que hay al menos dos secciones en la presentación "Presentation.pptx"):
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      ISectionZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addSectionZoomFrame(150, 20, 50, 50, pres.getSections().get_Item(1));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| x | float | La coordenada x del nuevo marco de Zoom de sección, en puntos. |
| y | float | La coordenada y del nuevo marco de Zoom de sección, en puntos. |
| width | float | El ancho del nuevo marco de Zoom de sección, en puntos. |
| height | float | La altura del nuevo marco de Zoom de sección, en puntos. |
| section | [ISection](../../com.aspose.slides/isection) | La [ISection](../../com.aspose.slides/isection) referenciada por el marco de Zoom de sección; debe pertenecer a esta presentación y contener al menos una diapositiva. |

**Devuelve:**
[ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe) - El nuevo [ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe).

### addSectionZoomFrame(float x, float y, float width, float height, ISection section, IPPImage image) {#addSectionZoomFrame-float-float-float-float-com.aspose.slides.ISection-com.aspose.slides.IPPImage-}
```
public abstract ISectionZoomFrame addSectionZoomFrame(float x, float y, float width, float height, ISection section, IPPImage image)
```

Crea un nuevo marco de Zoom de sección con una imagen predefinida y lo agrega al final de la colección de formas.

--------------------

> ```
> Este ejemplo muestra cómo agregar un objeto Section Zoom al final de una colección
>  (suponga que hay al menos dos secciones en la presentación "Presentation.pptx"):
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      FileInputStream fos = null;
>      try {
>          fos = new FileInputStream("image.png");
>          IPPImage image = pres.getImages().addImage(fos);
>          ISectionZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addSectionZoomFrame(150, 20, 50, 50, pres.getSections().get_Item(1), image);
>      } finally {
>          if (fos != null) fos.close();
>      }
>  } catch (IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| x | float | La coordenada x del nuevo marco de Zoom de sección, en puntos. |
| y | float | La coordenada y del nuevo marco de Zoom de sección, en puntos. |
| width | float | El ancho del nuevo marco de Zoom de sección, en puntos. |
| height | float | La altura del nuevo marco de Zoom de sección, en puntos. |
| section | [ISection](../../com.aspose.slides/isection) | La [ISection](../../com.aspose.slides/isection) referenciada por el marco de Zoom de sección; debe pertenecer a esta presentación y contener al menos una diapositiva. |
| image | [IPPImage](../../com.aspose.slides/ippimage) | La [IPPImage](../../com.aspose.slides/ippimage) a mostrar dentro del marco de Zoom de sección. |

**Devuelve:**
[ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe) - El nuevo [ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe).

### insertSectionZoomFrame(int index, float x, float y, float width, float height, ISection section) {#insertSectionZoomFrame-int-float-float-float-float-com.aspose.slides.ISection-}
```
public abstract ISectionZoomFrame insertSectionZoomFrame(int index, float x, float y, float width, float height, ISection section)
```

Crea un nuevo marco de Zoom de sección y lo inserta en la colección de formas en el índice especificado.

--------------------

> ```
> Este ejemplo muestra la creación e inserción de un objeto Section Zoom en el índice especificado de una colección
>  (suponga que hay al menos dos secciones en la presentación "Presentation.pptx"):
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      ISectionZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().insertSectionZoomFrame(2, 150, 20, 50, 50, pres.getSections().get_Item(1));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index | int | El índice basado en cero donde insertar el marco de Zoom de sección. |
| x | float | La coordenada x del nuevo marco de Zoom de sección, en puntos. |
| y | float | La coordenada y del nuevo marco de Zoom de sección, en puntos. |
| width | float | El ancho del nuevo marco de Zoom de sección, en puntos. |
| height | float | La altura del nuevo marco de Zoom de sección, en puntos. |
| section | [ISection](../../com.aspose.slides/isection) | La [ISection](../../com.aspose.slides/isection) referenciada por el marco de Zoom de sección; debe pertenecer a esta presentación y contener al menos una diapositiva. |

**Devuelve:**
[ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe) - El nuevo [ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe).

### insertSectionZoomFrame(int index, float x, float y, float width, float height, ISection section, IPPImage image) {#insertSectionZoomFrame-int-float-float-float-float-com.aspose.slides.ISection-com.aspose.slides.IPPImage-}
```
public abstract ISectionZoomFrame insertSectionZoomFrame(int index, float x, float y, float width, float height, ISection section, IPPImage image)
```

Crea un nuevo marco de Zoom de sección con una imagen predefinida y lo inserta en la colección de formas en el índice especificado.

--------------------

> ```
> Este ejemplo muestra la creación e inserción de un objeto Section Zoom en el índice especificado de una colección
>  (asuma que hay al menos dos secciones en la presentación "Presentation.pptx"):
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      FileInputStream fos = null;
>      try {
>          fos = new FileInputStream("image.png");
>          IPPImage image = pres.getImages().addImage(fos);
>          ISectionZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().insertSectionZoomFrame(2, 150, 20, 50, 50, pres.getSections().get_Item(1), image);
>      } finally {
>          if (fos != null) fos.close();
>      }
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index | int | El índice basado en cero donde insertar el marco de Zoom de sección. |
| x | float | La coordenada x del nuevo marco de Zoom de sección, en puntos. |
| y | float | La coordenada y del nuevo marco de Zoom de sección, en puntos. |
| width | float | El ancho del nuevo marco de Zoom de sección, en puntos. |
| height | float | La altura del nuevo marco de Zoom de sección, en puntos. |
| section | [ISection](../../com.aspose.slides/isection) | La [ISection](../../com.aspose.slides/isection) referenciada por el marco de Zoom de sección; debe pertenecer a esta presentación y contener al menos una diapositiva. |
| image | [IPPImage](../../com.aspose.slides/ippimage) | La imagen a mostrar dentro del marco de Zoom de sección. |

**Devuelve:**
[ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe) - El nuevo [ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe).

### addSummaryZoomFrame(float x, float y, float width, float height) {#addSummaryZoomFrame-float-float-float-float-}
```
public abstract ISummaryZoomFrame addSummaryZoomFrame(float x, float y, float width, float height)
```

Crea un nuevo marco de Zoom resumido y lo agrega al final de la colección de formas.

--------------------

> ```
> Este ejemplo muestra cómo agregar un objeto Summary Zoom al final de una colección
>  (suponga que hay al menos dos secciones en la presentación "Presentation.pptx"):
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      ISummaryZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addSummaryZoomFrame(150, 20, 500, 250);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| x | float | La coordenada x del nuevo marco de Zoom resumido, en puntos. |
| y | float | La coordenada y del nuevo marco de Zoom resumido, en puntos. |
| width | float | El ancho del nuevo marco de Zoom resumido, en puntos. |
| height | float | La altura del nuevo marco de Zoom resumido, en puntos. |

Este método crea un marco de Zoom resumido que agrega enlaces de resumen para todas las secciones de la presentación.

**Devuelve:**
[ISummaryZoomFrame](../../com.aspose.slides/isummaryzoomframe) - El nuevo [ISummaryZoomFrame](../../com.aspose.slides/isummaryzoomframe).

### insertSummaryZoomFrame(int index, float x, float y, float width, float height) {#insertSummaryZoomFrame-int-float-float-float-float-}
```
public abstract ISummaryZoomFrame insertSummaryZoomFrame(int index, float x, float y, float width, float height)
```

Crea un nuevo marco de Zoom resumido y lo inserta en la colección de formas en el índice especificado.

--------------------

> ```
> Este ejemplo muestra la creación e inserción de un objeto Summary Zoom en el índice especificado de una colección
>  (suponga que hay al menos dos secciones en la presentación "Presentation.pptx"):
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      ISummaryZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().insertSummaryZoomFrame(2, 150, 20, 50, 50);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index | int | El índice basado en cero donde insertar el marco de Zoom resumido. |
| x | float | La coordenada x del nuevo marco de Zoom resumido, en puntos. |
| y | float | La coordenada y del nuevo marco de Zoom resumido, en puntos. |
| width | float | El ancho del nuevo marco de Zoom resumido, en puntos. |
| height | float | La altura del nuevo marco de Zoom resumido, en puntos. |

Este método crea un marco de Zoom resumido que agrega enlaces de resumen para todas las secciones de la presentación.

**Devuelve:**
[ISummaryZoomFrame](../../com.aspose.slides/isummaryzoomframe) - El nuevo [ISummaryZoomFrame](../../com.aspose.slides/isummaryzoomframe).

### addVideoFrame(float x, float y, float width, float height, String fname) {#addVideoFrame-float-float-float-float-java.lang.String-}
```
public abstract IVideoFrame addVideoFrame(float x, float y, float width, float height, String fname)
```

Crea un nuevo marco de vídeo y lo agrega al final de la colección de formas.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| x | float | La coordenada x del nuevo marco de vídeo, en puntos. |
| y | float | La coordenada y del nuevo marco de vídeo, en puntos. |
| width | float | El ancho del nuevo marco de vídeo, en puntos. |
| height | float | La altura del nuevo marco de vídeo, en puntos. |
| fname | java.lang.String | La ruta o nombre del archivo de vídeo a incrustar. |

**Devuelve:**
[IVideoFrame](../../com.aspose.slides/ivideoframe) - El nuevo [IVideoFrame](../../com.aspose.slides/ivideoframe).

### addVideoFrame(float x, float y, float width, float height, IVideo video) {#addVideoFrame-float-float-float-float-com.aspose.slides.IVideo-}
```
public abstract IVideoFrame addVideoFrame(float x, float y, float width, float height, IVideo video)
```

Crea un nuevo marco de vídeo y lo agrega al final de la colección de formas.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| x | float | La coordenada x del nuevo marco de vídeo, en puntos. |
| y | float | La coordenada y del nuevo marco de vídeo, en puntos. |
| width | float | El ancho del nuevo marco de vídeo, en puntos. |
| height | float | La altura del nuevo marco de vídeo, en puntos. |
| video | [IVideo](../../com.aspose.slides/ivideo) | El [IVideo](../../com.aspose.slides/ivideo) a incrustar en el marco de vídeo. |

**Devuelve:**
[IVideoFrame](../../com.aspose.slides/ivideoframe) - El nuevo [IVideoFrame](../../com.aspose.slides/ivideoframe).

### insertVideoFrame(int index, float x, float y, float width, float height, String fname) {#insertVideoFrame-int-float-float-float-float-java.lang.String-}
```
public abstract IVideoFrame insertVideoFrame(int index, float x, float y, float width, float height, String fname)
```

Crea un nuevo marco de vídeo y lo inserta en la colección de formas en el índice especificado.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index | int | El índice basado en cero donde insertar el marco de vídeo. |
| x | float | La coordenada x del nuevo marco de vídeo, en puntos. |
| y | float | La coordenada y del nuevo marco de vídeo, en puntos. |
| width | float | El ancho del nuevo marco de vídeo, en puntos. |
| height | float | La altura del nuevo marco de vídeo, en puntos. |
| fname | java.lang.String | La ruta o nombre del archivo de vídeo a incrustar. |

**Devuelve:**
[IVideoFrame](../../com.aspose.slides/ivideoframe) - El nuevo [IVideoFrame](../../com.aspose.slides/ivideoframe).

### addAudioFrameCD(float x, float y, float width, float height) {#addAudioFrameCD-float-float-float-float-}
```
public abstract IAudioFrame addAudioFrameCD(float x, float y, float width, float height)
```

Crea un nuevo marco de audio vinculado a una pista de CD y lo agrega al final de la colección de formas.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| x | float | La coordenada x del nuevo marco de audio, en puntos. |
| y | float | La coordenada y del nuevo marco de audio, en puntos. |
| width | float | El ancho del nuevo marco de audio, en puntos. |
| height | float | La altura del nuevo marco de audio, en puntos. |

**Devuelve:**
[IAudioFrame](../../com.aspose.slides/iaudioframe) - El nuevo [IAudioFrame](../../com.aspose.slides/iaudioframe).

### insertAudioFrameCD(int index, float x, float y, float width, float height) {#insertAudioFrameCD-int-float-float-float-float-}
```
public abstract IAudioFrame insertAudioFrameCD(int index, float x, float y, float width, float height)
```

Crea un nuevo marco de audio vinculado a una pista de CD y lo inserta en la colección de formas en el índice especificado.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index | int | El índice basado en cero donde insertar el marco de audio. |
| x | float | La coordenada x del nuevo marco de audio, en puntos. |
| y | float | La coordenada y del nuevo marco de audio, en puntos. |
| width | float | El ancho del nuevo marco de audio, en puntos. |
| height | float | La altura del nuevo marco de audio, en puntos. |

**Devuelve:**
[IAudioFrame](../../com.aspose.slides/iaudioframe) - El nuevo [IAudioFrame](../../com.aspose.slides/iaudioframe).

### addAudioFrameLinked(float x, float y, float width, float height, String fname) {#addAudioFrameLinked-float-float-float-float-java.lang.String-}
```
public abstract IAudioFrame addAudioFrameLinked(float x, float y, float width, float height, String fname)
```

Crea un nuevo marco de audio vinculado a un archivo de audio externo y lo agrega al final de la colección de formas.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| x | float | La coordenada x del nuevo marco de audio, en puntos. |
| y | float | La coordenada y del nuevo marco de audio, en puntos. |
| width | float | El ancho del nuevo marco de audio, en puntos. |
| height | float | La altura del nuevo marco de audio, en puntos. |
| fname | java.lang.String | La ruta o nombre del archivo de audio externo a vincular. |

**Devuelve:**
[IAudioFrame](../../com.aspose.slides/iaudioframe) - El nuevo [IAudioFrame](../../com.aspose.slides/iaudioframe).

### insertAudioFrameLinked(int index, float x, float y, float width, float height, String fname) {#insertAudioFrameLinked-int-float-float-float-float-java.lang.String-}
```
public abstract IAudioFrame insertAudioFrameLinked(int index, float x, float y, float width, float height, String fname)
```

Crea un nuevo marco de audio vinculado a un archivo de audio externo y lo inserta en la colección de formas en el índice especificado.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index | int | El índice basado en cero donde insertar el marco de audio. |
| x | float | La coordenada x del nuevo marco de audio, en puntos. |
| y | float | La coordenada y del nuevo marco de audio, en puntos. |
| width | float | El ancho del nuevo marco de audio, en puntos. |
| height | float | La altura del nuevo marco de audio, en puntos. |
| fname | java.lang.String | La ruta o nombre del archivo de audio externo a vincular. |

**Devuelve:**
[IAudioFrame](../../com.aspose.slides/iaudioframe) - El nuevo [IAudioFrame](../../com.aspose.slides/iaudioframe).

### addAudioFrameEmbedded(float x, float y, float width, float height, InputStream audio_stream) {#addAudioFrameEmbedded-float-float-float-float-java.io.InputStream-}
```
public abstract IAudioFrame addAudioFrameEmbedded(float x, float y, float width, float height, InputStream audio_stream)
```

Crea un nuevo marco de audio con un archivo WAV incrustado y lo agrega al final de la colección de formas. El audio incrustado se agrega a la colección Presentation.Audios.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| x | float | La coordenada x del nuevo marco de audio, en puntos. |
| y | float | La coordenada y del nuevo marco de audio, en puntos. |
| width | float | El ancho del nuevo marco de audio, en puntos. |
| height | float | La altura del nuevo marco de audio, en puntos. |
| audio_stream | java.io.InputStream | Un flujo de entrada que contiene datos de audio WAV para incrustar. |

**Devuelve:**
[IAudioFrame](../../com.aspose.slides/iaudioframe) - El nuevo [IAudioFrame](../../com.aspose.slides/iaudioframe).

### addAudioFrameEmbedded(float x, float y, float width, float height, IAudio audio) {#addAudioFrameEmbedded-float-float-float-float-com.aspose.slides.IAudio-}
```
public abstract IAudioFrame addAudioFrameEmbedded(float x, float y, float width, float height, IAudio audio)
```

Crea un nuevo marco de audio y lo agrega al final de la colección de formas usando un objeto de audio existente de la lista Presentation.Audios.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| x | float | La coordenada x del nuevo marco de audio, en puntos. |
| y | float | La coordenada y del nuevo marco de audio, en puntos. |
| width | float | El ancho del nuevo marco de audio, en puntos. |
| height | float | La altura del nuevo marco de audio, en puntos. |
| audio | [IAudio](../../com.aspose.slides/iaudio) | Una instancia [IAudio](../../com.aspose.slides/iaudio) de la colección Presentation.Audios. |

**Devuelve:**
[IAudioFrame](../../com.aspose.slides/iaudioframe) - El nuevo [IAudioFrame](../../com.aspose.slides/iaudioframe).

### insertAudioFrameEmbedded(int index, float x, float y, float width, float height, InputStream audio_stream) {#insertAudioFrameEmbedded-int-float-float-float-float-java.io.InputStream-}
```
public abstract IAudioFrame insertAudioFrameEmbedded(int index, float x, float y, float width, float height, InputStream audio_stream)
```

Crea un nuevo marco de audio con un archivo WAV incrustado y lo inserta en la colección de formas en el índice especificado. El audio incrustado se agrega a la colección Presentation.Audios.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index | int | El índice basado en cero donde insertar el marco de audio. |
| x | float | La coordenada x del nuevo marco de audio, en puntos. |
| y | float | La coordenada y del nuevo marco de audio, en puntos. |
| width | float | El ancho del nuevo marco de audio, en puntos. |
| height | float | La altura del nuevo marco de audio, en puntos. |
| audio_stream | java.io.InputStream | Un flujo de entrada que contiene datos de audio WAV para incrustar. |

**Devuelve:**
[IAudioFrame](../../com.aspose.slides/iaudioframe) - El nuevo [IAudioFrame](../../com.aspose.slides/iaudioframe).

### insertAudioFrameEmbedded(int index, float x, float y, float width, float height, IAudio audio) {#insertAudioFrameEmbedded-int-float-float-float-float-com.aspose.slides.IAudio-}
```
public abstract IAudioFrame insertAudioFrameEmbedded(int index, float x, float y, float width, float height, IAudio audio)
```

Crea un nuevo marco de audio y lo inserta en la colección de formas en el índice especificado usando un objeto de audio existente de la lista Presentation.Audios.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index | int | El índice basado en cero donde insertar el marco de audio. |
| x | float | La coordenada x del nuevo marco de audio, en puntos. |
| y | float | La coordenada y del nuevo marco de audio, en puntos. |
| width | float | El ancho del nuevo marco de audio, en puntos. |
| height | float | La altura del nuevo marco de audio, en puntos. |
| audio | [IAudio](../../com.aspose.slides/iaudio) | Una instancia [IAudio](../../com.aspose.slides/iaudio) de la colección Presentation.Audios para incrustar. |

**Devuelve:**
[IAudioFrame](../../com.aspose.slides/iaudioframe) - El nuevo [IAudioFrame](../../com.aspose.slides/iaudioframe).

### indexOf(IShape shape) {#indexOf-com.aspose.slides.IShape-}
```
public abstract int indexOf(IShape shape)
```

Devuelve el índice basado en cero de la primera aparición de la forma especificada en la colección.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| shape | [IShape](../../com.aspose.slides/ishape) | La forma a localizar en la colección. |

**Devuelve:**
int - El índice basado en cero de la primera aparición de la forma en la colección de formas si se encuentra; de lo contrario, \\u20131.

### toArray() {#toArray--}
```
public abstract IShape[] toArray()
```

Crea y devuelve una matriz que contiene todas las formas.

**Devuelve:**
com.aspose.slides.IShape[] - Una matriz de objetos [IShape](../../com.aspose.slides/ishape).

### toArray(int startIndex, int count) {#toArray-int-int-}
```
public abstract IShape[] toArray(int startIndex, int count)
```

Crea y devuelve una matriz que contiene todas las formas en el rango especificado.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| startIndex | int | El índice de la primera forma a devolver. |
| count | int | El número de formas a devolver. |

**Devuelve:**
com.aspose.slides.IShape[] - Una matriz de objetos [IShape](../../com.aspose.slides/ishape).

### reorder(int index, IShape shape) {#reorder-int-com.aspose.slides.IShape-}
```
public abstract void reorder(int index, IShape shape)
```

Mueve la forma especificada a una nueva posición dentro de la colección de formas.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index | int | El índice objetivo basado en cero donde se colocará la forma. |
| shape | [IShape](../../com.aspose.slides/ishape) | La [IShape](../../com.aspose.slides/ishape) a mover dentro de la colección. |

### reorder(int index, IShape[] shapes) {#reorder-int-com.aspose.slides.IShape...-}
```
public abstract void reorder(int index, IShape[] shapes)
```

Mueve las formas especificadas dentro de la colección de formas, colocándolas a partir del índice proporcionado.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index | int | El índice objetivo basado en cero donde se colocará la primera forma especificada; las formas posteriores siguen en el orden proporcionado. |
| shapes | [IShape\[\]](../../com.aspose.slides/ishape) | Una o más instancias [IShape](../../com.aspose.slides/ishape) a mover dentro de la colección. |

### addAutoShape(int shapeType, float x, float y, float width, float height) {#addAutoShape-int-float-float-float-float-}
```
public abstract IAutoShape addAutoShape(int shapeType, float x, float y, float width, float height)
```

Crea una nueva forma automática con formato predeterminado y la agrega al final de la colección de formas.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| shapeType | int | El [ShapeType](../../com.aspose.slides/shapetype) de la forma automática a agregar. |
| x | float | La coordenada x del marco de la forma, en puntos. |
| y | float | La coordenada y del marco de la forma, en puntos. |
| width | float | El ancho del marco de la forma, en puntos. |
| height | float | La altura del marco de la forma, en puntos. |

**Devuelve:**
[IAutoShape](../../com.aspose.slides/iautoshape) - La nueva [IAutoShape](../../com.aspose.slides/iautoshape).

### addAutoShape(int shapeType, float x, float y, float width, float height, boolean createFromTemplate) {#addAutoShape-int-float-float-float-float-boolean-}
```
public abstract IAutoShape addAutoShape(int shapeType, float x, float y, float width, float height, boolean createFromTemplate)
```

Crea una nueva forma automática y la agrega al final de la colección de formas, opcionalmente inicializándola con el formato predeterminado de la plantilla.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| shapeType | int | El [ShapeType](../../com.aspose.slides/shapetype) de la forma automática a agregar. |
| x | float | La coordenada x del marco de la forma, en puntos. |
| y | float | La coordenada y del marco de la forma, en puntos. |
| width | float | El ancho del marco de la forma, en puntos. |
| height | float | La altura del marco de la forma, en puntos. |
| createFromTemplate | boolean | Verdadero para aplicar el estilo predeterminado de la plantilla (estilo simple, texto centrado y nombre no vacío) a la nueva forma; falso para crear la forma con todas sus propiedades establecidas a sus valores predeterminados. |

**Devuelve:**
[IAutoShape](../../com.aspose.slides/iautoshape) - La nueva [IAutoShape](../../com.aspose.slides/iautoshape).

### addMathShape(float x, float y, float width, float height) {#addMathShape-float-float-float-float-}
```
public abstract IAutoShape addMathShape(float x, float y, float width, float height)
```

Crea una nueva forma automática rectangular para alojar contenido matemático y la agrega al final de la colección de formas.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| x | float | La coordenada x del marco de la forma, en puntos. |
| y | float | La coordenada y del marco de la forma, en puntos. |
| width | float | El ancho del marco de la forma, en puntos. |
| height | float | La altura del marco de la forma, en puntos. |

**Devuelve:**
[IAutoShape](../../com.aspose.slides/iautoshape) - La nueva [IAutoShape](../../com.aspose.slides/iautoshape).

### insertAutoShape(int index, int shapeType, float x, float y, float width, float height) {#insertAutoShape-int-int-float-float-float-float-}
```
public abstract IAutoShape insertAutoShape(int index, int shapeType, float x, float y, float width, float height)
```

Crea una nueva forma automática y la inserta en la colección de formas en el índice especificado, aplicando el formato predeterminado de la plantilla.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index | int | El índice basado en cero donde insertar la nueva forma automática. |
| shapeType | int | El [ShapeType](../../com.aspose.slides/shapetype) de la forma automática a insertar. |
| x | float | La coordenada x del marco de la forma, en puntos. |
| y | float | La coordenada y del marco de la forma, en puntos. |
| width | float | El ancho del marco de la forma, en puntos. |
| height | float | La altura del marco de la forma, en puntos. |

**Devuelve:**
[IAutoShape](../../com.aspose.slides/iautoshape) - La nueva [IAutoShape](../../com.aspose.slides/iautoshape).

### insertAutoShape(int index, int shapeType, float x, float y, float width, float height, boolean createFromTemplate) {#insertAutoShape-int-int-float-float-float-float-boolean-}
```
public abstract IAutoShape insertAutoShape(int index, int shapeType, float x, float y, float width, float height, boolean createFromTemplate)
```

Crea una nueva forma automática y la inserta en la colección de formas en el índice especificado, opcionalmente inicializándola con el estilo predeterminado de la plantilla.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index | int | El índice basado en cero donde insertar la forma automática. |
| shapeType | int | El [ShapeType](../../com.aspose.slides/shapetype) de la forma automática a insertar. |
| x | float | La coordenada x del marco de la forma, en puntos. |
| y | float | La coordenada y del marco de la forma, en puntos. |
| width | float | El ancho del marco de la forma, en puntos. |
| height | float | La altura del marco de la forma, en puntos. |
| createFromTemplate | boolean | Verdadero para aplicar el estilo predeterminado de la plantilla (incluido un nombre no vacío, estilo simple y texto centrado); falso para crear la forma con todas sus propiedades establecidas a sus valores predeterminados. |

**Devuelve:**
[IAutoShape](../../com.aspose.slides/iautoshape) - La nueva [IAutoShape](../../com.aspose.slides/iautoshape).

### addGroupShape() {#addGroupShape--}
```
public abstract IGroupShape addGroupShape()
```

Crea una nueva forma de grupo vacía y la agrega al final de la colección de formas. El marco del grupo se ajustará automáticamente para encajar cualquier forma añadida.

**Devuelve:**
[IGroupShape](../../com.aspose.slides/igroupshape) - La nueva [IGroupShape](../../com.aspose.slides/igroupshape).

### addGroupShape(ISvgImage svgImage, float x, float y, float width, float height) {#addGroupShape-com.aspose.slides.ISvgImage-float-float-float-float-}
```
public abstract IGroupShape addGroupShape(ISvgImage svgImage, float x, float y, float width, float height)
```

Crea una nueva forma de grupo, convierte la imagen SVG especificada en formas individuales y agrega el grupo resultante al final de la colección de formas.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| svgImage | [ISvgImage](../../com.aspose.slides/isvgimage) | El [ISvgImage](../../com.aspose.slides/isvgimage) que contiene contenido vectorial para convertir en formas. |
| x | float | La coordenada x del marco del grupo, en puntos. |
| y | float | La coordenada y del marco del grupo, en puntos. |
| width | float | El ancho del marco del grupo, en puntos. |
| height | float | La altura del marco del grupo, en puntos. |

**Devuelve:**
[IGroupShape](../../com.aspose.slides/igroupshape) - La nueva [IGroupShape](../../com.aspose.slides/igroupshape).

### insertGroupShape(int index) {#insertGroupShape-int-}
```
public abstract IGroupShape insertGroupShape(int index)
```

Crea una nueva forma de grupo vacía y la inserta en la colección de formas en el índice especificado. El marco del grupo se ajustará automáticamente para encajar cualquier forma añadida.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index | int | El índice basado en cero donde insertar la forma de grupo. |

**Devuelve:**
[IGroupShape](../../com.aspose.slides/igroupshape) - La nueva [IGroupShape](../../com.aspose.slides/igroupshape).

### addConnector(int shapeType, float x, float y, float width, float height) {#addConnector-int-float-float-float-float-}
```
public abstract IConnector addConnector(int shapeType, float x, float y, float width, float height)
```

Crea una nueva forma conectora con estilo predeterminado de la plantilla y la agrega al final de la colección de formas.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| shapeType | int | El [ShapeType](../../com.aspose.slides/shapetype) de la forma conectora a agregar. |
| x | float | La coordenada x del marco del conector, en puntos. |
| y | float | La coordenada y del marco del conector, en puntos. |
| width | float | El ancho del marco del conector, en puntos. |
| height | float | La altura del marco del conector, en puntos. |

**Devuelve:**
[IConnector](../../com.aspose.slides/iconnector) - La nueva [IConnector](../../com.aspose.slides/iconnector).

### addConnector(int shapeType, float x, float y, float width, float height, boolean createFromTemplate) {#addConnector-int-float-float-float-float-boolean-}
```
public abstract IConnector addConnector(int shapeType, float x, float y, float width, float height, boolean createFromTemplate)
```

Crea una nueva forma conectora y la agrega al final de la colección de formas, opcionalmente aplicando el estilo predeterminado de la plantilla.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| shapeType | int | El [ShapeType](../../com.aspose.slides/shapetype) de la forma conectora a crear. |
| x | float | La coordenada x del marco del conector, en puntos. |
| y | float | La coordenada y del marco del conector, en puntos. |
| width | float | El ancho del marco del conector, en puntos. |
| height | float | La altura del marco del conector, en puntos. |
| createFromTemplate | boolean | Verdadero para aplicar el estilo predeterminado de la plantilla (nombre no vacío, estilo simple); falso para crear el conector con valores de propiedad predeterminados. |

**Devuelve:**
[IConnector](../../com.aspose.slides/iconnector) - La nueva [IConnector](../../com.aspose.slides/iconnector).

### insertConnector(int index, int shapeType, float x, float y, float width, float height) {#insertConnector-int-int-float-float-float-float-}
```
public abstract IConnector insertConnector(int index, int shapeType, float x, float y, float width, float height)
```

Crea una nueva forma conectora y la inserta en la colección de formas en el índice especificado, aplicando el estilo predeterminado de la plantilla.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index | int | El índice basado en cero donde insertar la forma conectora. |
| shapeType | int | El [ShapeType](../../com.aspose.slides/shapetype) de la forma conectora a insertar. |
| x | float | La coordenada x del marco del conector, en puntos. |
| y | float | La coordenada y del marco del conector, en puntos. |
| width | float | El ancho del marco del conector, en puntos. |
| height | float | La altura del marco del conector, en puntos. |

**Devuelve:**
[IConnector](../../com.aspose.slides/iconnector) - La nueva [IConnector](../../com.aspose.slides/iconnector).

### insertConnector(int index, int shapeType, float x, float y, float width, float height, boolean createFromTemplate) {#insertConnector-int-int-float-float-float-float-boolean-}
```
public abstract IConnector insertConnector(int index, int shapeType, float x, float y, float width, float height, boolean createFromTemplate)
```

Crea una nueva forma conectora y la inserta en la colección de formas en el índice especificado, opcionalmente aplicando el estilo predeterminado de la plantilla.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index | int | El índice basado en cero donde insertar la forma conectora. |
| shapeType | int | El [ShapeType](../../com.aspose.slides/shapetype) de la forma conectora a insertar. |
| x | float | La coordenada x del marco del conector, en puntos. |
| y | float | La coordenada y del marco del conector, en puntos. |
| width | float | El ancho del marco del conector, en puntos. |
| height | float | La altura del marco del conector, en puntos. |
| createFromTemplate | boolean | Verdadero para aplicar el estilo predeterminado de la plantilla (nombre no vacío, estilo simple); falso para crear el conector con valores de propiedad predeterminados. |

**Devuelve:**
[IConnector](../../com.aspose.slides/iconnector) - La nueva [IConnector](../../com.aspose.slides/iconnector).

### addPictureFrame(int shapeType, float x, float y, float width, float height, IPPImage image) {#addPictureFrame-int-float-float-float-float-com.aspose.slides.IPPImage-}
```
public abstract IPictureFrame addPictureFrame(int shapeType, float x, float y, float width, float height, IPPImage image)
```

Crea un nuevo marco de imagen que contiene la imagen especificada y lo agrega al final de la colección de formas.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| shapeType | int | Especifica el tipo de forma contenido en [ShapeType](../../com.aspose.slides/shapetype), excepto para todos los tipos de líneas:

ShapeType.Line,

ShapeType.StraightConnector1,

ShapeType.BentConnector2,

ShapeType.BentConnector3,

ShapeType.BentConnector4,

ShapeType.BentConnector5,

ShapeType.CurvedConnector2,

ShapeType.CurvedConnector3,

ShapeType.CurvedConnector4,

ShapeType.CurvedConnector5. |
| x | float | La coordenada x del marco de imagen, en puntos. |
| y | float | La coordenada y del marco de imagen, en puntos. |
| width | float | El ancho del marco de imagen, en puntos. |
| height | float | La altura del marco de imagen, en puntos. |
| image | [IPPImage](../../com.aspose.slides/ippimage) | La [IPPImage](../../com.aspose.slides/ippimage) a mostrar en el marco de imagen. |

**Devuelve:**
[IPictureFrame](../../com.aspose.slides/ipictureframe) - El nuevo [IPictureFrame](../../com.aspose.slides/ipictureframe).

### insertPictureFrame(int index, int shapeType, float x, float y, float width, float height, IPPImage image) {#insertPictureFrame-int-int-float-float-float-float-com.aspose.slides.IPPImage-}
```
public abstract IPictureFrame insertPictureFrame(int index, int shapeType, float x, float y, float width, float height, IPPImage image)
```

Crea un nuevo marco de imagen que contiene la imagen especificada y lo inserta en la colección de formas en el índice especificado.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index | int | El índice basado en cero donde insertar el marco de imagen. |
| shapeType | int | Especifica el tipo de forma contenido en [ShapeType](../../com.aspose.slides/shapetype), excepto para todos los tipos de líneas:

ShapeType.Line,

ShapeType.StraightConnector1,

ShapeType.BentConnector2,

ShapeType.BentConnector3,

ShapeType.BentConnector4,

ShapeType.BentConnector5,

ShapeType.CurvedConnector2,

ShapeType.CurvedConnector3,

ShapeType.CurvedConnector4,

ShapeType.CurvedConnector5. |
| x | float | La coordenada x del marco de imagen, en puntos. |
| y | float | La coordenada y del marco de imagen, en puntos. |
| width | float | El ancho del marco de imagen, en puntos. |
| height | float | La altura del marco de imagen, en puntos. |
| image | [IPPImage](../../com.aspose.slides/ippimage) | La [IPPImage](../../com.aspose.slides/ippimage) a mostrar en el marco de imagen. |

**Devuelve:**
[IPictureFrame](../../com.aspose.slides/ipictureframe) - El nuevo [IPictureFrame](../../com.aspose.slides/ipictureframe).

### addTable(float x, float y, double[] columnWidths, double[] rowHeights) {#addTable-float-float-double---double---}
```
public abstract ITable addTable(float x, float y, double[] columnWidths, double[] rowHeights)
```

Crea una nueva tabla y la agrega al final de la colección de formas.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| x | float | La coordenada x de la tabla, en puntos. |
| y | float | La coordenada y de la tabla, en puntos. |
| columnWidths | double[] | Una matriz de dobles que representa los anchos de las columnas de la tabla, en puntos. |
| rowHeights | double[] | Una matriz de dobles que representa las alturas de las filas de la tabla, en puntos. |

**Devuelve:**
[ITable](../../com.aspose.slides/itable) - La nueva [ITable](../../com.aspose.slides/itable).

### insertTable(int index, float x, float y, double[] columnWidths, double[] rowHeights) {#insertTable-int-float-float-double---double---}
```
public abstract ITable insertTable(int index, float x, float y, double[] columnWidths, double[] rowHeights)
```

Crea una nueva tabla y la inserta en la colección de formas en el índice especificado.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index | int | El índice basado en cero donde insertar la tabla. |
| x | float | La coordenada x de la tabla, en puntos. |
| y | float | La coordenada y de la tabla, en puntos. |
| columnWidths | double[] | Una matriz de dobles que representa los anchos de las columnas de la tabla, en puntos. |
| rowHeights | double[] | Una matriz de dobles que representa las alturas de las filas de la tabla, en puntos. |

**Devuelve:**
[ITable](../../com.aspose.slides/itable) - La nueva [ITable](../../com.aspose.slides/itable).

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

Elimina la forma en el índice especificado de la colección de formas.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index | int | El índice basado en cero de la forma a eliminar. |

### remove(IShape shape) {#remove-com.aspose.slides.IShape-}
```
public abstract void remove(IShape shape)
```

Elimina la primera aparición de la forma especificada de la colección de formas.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| shape | [IShape](../../com.aspose.slides/ishape) | La [IShape](../../com.aspose.slides/ishape) a eliminar. |

### clear() {#clear--}
```
public abstract void clear()
```

Elimina todas las formas de la colección de formas.

### addClone(IShape sourceShape, float x, float y, float width, float height) {#addClone-com.aspose.slides.IShape-float-float-float-float-}
```
public abstract IShape addClone(IShape sourceShape, float x, float y, float width, float height)
```

Crea una copia de la forma especificada y la agrega al final de la colección de formas.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| sourceShape | [IShape](../../com.aspose.slides/ishape) | La forma a clonar. |
| x | float | La coordenada x del marco de la forma clonada, en puntos. |
| y | float | La coordenada y del marco de la forma clonada, en puntos. |
| width | float | El ancho del marco de la forma clonada, en puntos. |
| height | float | La altura del marco de la forma clonada, en puntos. |

**Devuelve:**
[IShape](../../com.aspose.slides/ishape) - La nueva [IShape](../../com.aspose.slides/ishape).

### addClone(IShape sourceShape, float x, float y) {#addClone-com.aspose.slides.IShape-float-float-}
```
public abstract IShape addClone(IShape sourceShape, float x, float y)
```

Crea una copia de la forma especificada y la agrega al final de la colección de formas. La nueva forma conserva el ancho y la altura de la sourceShape.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| sourceShape | [IShape](../../com.aspose.slides/ishape) | La [IShape](../../com.aspose.slides/ishape) a clonar. |
| x | float | La coordenada x del marco de la forma clonada, en puntos. |
| y | float | La coordenada y del marco de la forma clonada, en puntos. |

**Devuelve:**
[IShape](../../com.aspose.slides/ishape) - La nueva [IShape](../../com.aspose.slides/ishape).

### addClone(IShape sourceShape) {#addClone-com.aspose.slides.IShape-}
```
public abstract IShape addClone(IShape sourceShape)
```

Crea una copia de la forma especificada y la agrega al final de la colección de formas. La forma clonada conserva la posición y el tamaño originales.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| sourceShape | [IShape](../../com.aspose.slides/ishape) | La [IShape](../../com.aspose.slides/ishape) a clonar. |

**Devuelve:**
[IShape](../../com.aspose.slides/ishape) - La nueva [IShape](../../com.aspose.slides/ishape).

### insertClone(int index, IShape sourceShape, float x, float y, float width, float height) {#insertClone-int-com.aspose.slides.IShape-float-float-float-float-}
```
public abstract IShape insertClone(int index, IShape sourceShape, float x, float y, float width, float height)
```

Crea una copia de la forma especificada y la inserta en la colección de formas en el índice especificado.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index | int | El índice basado en cero donde insertar la forma clonada. |
| sourceShape | [IShape](../../com.aspose.slides/ishape) | La [IShape](../../com.aspose.slides/ishape) a clonar. |
| x | float | La coordenada x del marco de la forma clonada, en puntos. |
| y | float | La coordenada y del marco de la forma clonada, en puntos. |
| width | float | El ancho del marco de la forma clonada, en puntos. |
| height | float | La altura del marco de la forma clonada, en puntos. |

**Devuelve:**
[IShape](../../com.aspose.slides/ishape) - La nueva [IShape](../../com.aspose.slides/ishape).

### insertClone(int index, IShape sourceShape, float x, float y) {#insertClone-int-com.aspose.slides.IShape-float-float-}
```
public abstract IShape insertClone(int index, IShape sourceShape, float x, float y)
```

Crea una copia de la forma especificada y la inserta en la colección de formas en el índice especificado. La nueva forma conserva el ancho y la altura de la sourceShape.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index | int | El índice basado en cero donde insertar la forma clonada. |
| sourceShape | [IShape](../../com.aspose.slides/ishape) | La [IShape](../../com.aspose.slides/ishape) a clonar. |
| x | float | La coordenada x del marco de la forma clonada, en puntos. |
| y | float | La coordenada y del marco de la forma clonada, en puntos. |

**Devuelve:**
[IShape](../../com.aspose.slides/ishape) - La nueva [IShape](../../com.aspose.slides/ishape).

### insertClone(int index, IShape sourceShape) {#insertClone-int-com.aspose.slides.IShape-}
```
public abstract IShape insertClone(int index, IShape sourceShape)
```

Crea una copia de la forma especificada y la inserta en la colección de formas en el índice especificado. La forma clonada conserva la posición y el tamaño originales.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index | int | El índice basado en cero donde insertar la forma clonada. |
| sourceShape | [IShape](../../com.aspose.slides/ishape) | La [IShape](../../com.aspose.slides/ishape) a clonar. |

**Devuelve:**
[IShape](../../com.aspose.slides/ishape) - La nueva [IShape](../../com.aspose.slides/ishape).