---
title: ShapeCollection
second_title: Referencia de la API de Aspose.Slides para .NET
description: Representa una colección de formas.
type: docs
weight: 9080
url: /es/aspose.slides/shapecollection/
---
## ShapeCollection class

Representa una colección de formas.

```csharp
public sealed class ShapeCollection : DomObject<GroupShape>, IShapeCollection
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [Count](../../aspose.slides/shapecollection/count) { get; } | Obtiene el número de elementos realmente contenidos en la colección. Solo lecturaInt32 . |
| [IsSynchronized](../../aspose.slides/shapecollection/issynchronized) { get; } | Devuelve un valor que indica si el acceso a la colección está sincronizado (seguro para subprocesos). Solo lecturaBoolean . |
| [Item](../../aspose.slides/shapecollection/item) { get; } | Obtiene el elemento en el índice especificado. Solo lectura[`IShape`](../ishape) . |
| [ParentGroup](../../aspose.slides/shapecollection/parentgroup) { get; } | Devuelve el objeto GroupShape principal para una colección de formas. Solo lectura[`IGroupShape`](../igroupshape) . |
| [SyncRoot](../../aspose.slides/shapecollection/syncroot) { get; } | Devuelve una raíz de sincronización. Solo lecturaObject . |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [AddAudioFrameCD](../../aspose.slides/shapecollection/addaudioframecd)(float, float, float, float) | Agrega un AudioFrame con CD al final de la colección. |
| [AddAudioFrameEmbedded](../../aspose.slides/shapecollection/addaudioframeembedded#addaudioframeembedded)(float, float, float, float, IAudio) | Agrega un nuevo cuadro de audio con un archivo de audio incrustado al final de una colección. Utiliza un archivo de audio de la lista Presentation.Audios. |
| [AddAudioFrameEmbedded](../../aspose.slides/shapecollection/addaudioframeembedded#addaudioframeembedded_1)(float, float, float, float, Stream) | Agrega un nuevo cuadro de audio con un archivo de audio incrustado al final de una colección. El archivo de audio incrustado puede ser solo WAV. Agrega audio nuevo a la lista Presentation.Audios. |
| [AddAudioFrameLinked](../../aspose.slides/shapecollection/addaudioframelinked)(float, float, float, float, string) | Agrega un nuevo cuadro de audio con un archivo de audio vinculado al final de una colección. |
| [AddAutoShape](../../aspose.slides/shapecollection/addautoshape#addautoshape)(ShapeType, float, float, float, float) | Crea una nueva autoforma, la ajusta desde la plantilla predeterminada y la agrega al final de la colección. |
| [AddAutoShape](../../aspose.slides/shapecollection/addautoshape#addautoshape_1)(ShapeType, float, float, float, float, bool) | Crea una nueva autoforma y la agrega al final de la colección. |
| [AddChart](../../aspose.slides/shapecollection/addchart#addchart)(ChartType, float, float, float, float) | Crea un nuevo gráfico, lo inicializa con datos y configuraciones de series de muestra y lo agrega al final de la colección. |
| [AddChart](../../aspose.slides/shapecollection/addchart#addchart_1)(ChartType, float, float, float, float, bool) | Crea un nuevo Gráfico y lo agrega al final de la colección. |
| [AddClone](../../aspose.slides/shapecollection/addclone#addclone)(IShape) | Agrega una copia de una forma especificada al final de la colección. X, Y, Ancho y Alto de la nueva forma son iguales a X, Y, Ancho y Alto de la*sourceShape* . |
| [AddClone](../../aspose.slides/shapecollection/addclone#addclone_1)(IShape, float, float) | Agrega una copia de una forma especificada al final de la colección. El ancho y el alto de la nueva forma son iguales al ancho y el alto de la*sourceShape* . |
| [AddClone](../../aspose.slides/shapecollection/addclone#addclone_2)(IShape, float, float, float, float) | Agrega una copia de una forma específica al final de la colección. |
| [AddConnector](../../aspose.slides/shapecollection/addconnector#addconnector)(ShapeType, float, float, float, float) | Crea un nuevo conector, lo ajusta desde la plantilla predeterminada y lo agrega al final de la colección. |
| [AddConnector](../../aspose.slides/shapecollection/addconnector#addconnector_1)(ShapeType, float, float, float, float, bool) | Crea un nuevo conector y lo agrega al final de la colección. |
| [AddGroupShape](../../aspose.slides/shapecollection/addgroupshape#addgroupshape)() | Crea una nueva forma de grupo y la agrega al final de la colección. El tamaño y la posición del marco de la forma de grupo se adaptarán al contenido cuando se agregue una nueva forma a la forma de grupo. |
| [AddGroupShape](../../aspose.slides/shapecollection/addgroupshape#addgroupshape_1)(ISvgImage, float, float, float, float) | Crea un nuevo GroupShape, lo llena con formas convertidas de SVG y lo agrega al final de la colección. |
| [AddMathShape](../../aspose.slides/shapecollection/addmathshape)(float, float, float, float) | Crea una nueva autoforma ajustada desde la plantilla predeterminada al contenido matemático y la agrega al final de la colección. |
| [AddOleObjectFrame](../../aspose.slides/shapecollection/addoleobjectframe#addoleobjectframe)(float, float, float, float, IOleEmbeddedDataInfo) | Agrega un nuevo objeto OLE al final de una colección. |
| [AddOleObjectFrame](../../aspose.slides/shapecollection/addoleobjectframe#addoleobjectframe_1)(float, float, float, float, string, string) | Agrega un nuevo objeto OLE al final de una colección. |
| [AddPictureFrame](../../aspose.slides/shapecollection/addpictureframe)(ShapeType, float, float, float, float, IPPImage) | Crea un nuevo PictureFrame y lo agrega al final de la colección. |
| [AddSectionZoomFrame](../../aspose.slides/shapecollection/addsectionzoomframe#addsectionzoomframe)(float, float, float, float, ISection) | Agrega un nuevo objeto Zoom de sección al final de una colección. |
| [AddSectionZoomFrame](../../aspose.slides/shapecollection/addsectionzoomframe#addsectionzoomframe_1)(float, float, float, float, ISection, IPPImage) | Agrega un nuevo objeto Zoom de sección al final de una colección con una imagen predefinida. |
| [AddSmartArt](../../aspose.slides/shapecollection/addsmartart)(float, float, float, float, SmartArtLayoutType) | Agregar diagrama SmartArt. |
| [AddSummaryZoomFrame](../../aspose.slides/shapecollection/addsummaryzoomframe)(float, float, float, float) | Agrega un nuevo objeto Zoom de resumen al final de una colección. |
| [AddTable](../../aspose.slides/shapecollection/addtable)(float, float, double[], double[]) | Crea una nueva Tabla y la agrega al final de la colección. |
| [AddVideoFrame](../../aspose.slides/shapecollection/addvideoframe#addvideoframe)(float, float, float, float, IVideo) | Agrega un nuevo cuadro de video al final de una colección. |
| [AddVideoFrame](../../aspose.slides/shapecollection/addvideoframe#addvideoframe_1)(float, float, float, float, string) | Agrega un nuevo cuadro de video al final de una colección. |
| [AddZoomFrame](../../aspose.slides/shapecollection/addzoomframe#addzoomframe)(float, float, float, float, ISlide) | Agrega un nuevo objeto Zoom al final de una colección. |
| [AddZoomFrame](../../aspose.slides/shapecollection/addzoomframe#addzoomframe_1)(float, float, float, float, ISlide, IPPImage) | Agrega un nuevo objeto Zoom al final de una colección. |
| [Clear](../../aspose.slides/shapecollection/clear)() | Elimina todas las formas de la colección. |
| [CopyTo](../../aspose.slides/shapecollection/copyto)(Array, int) | Copia todos los elementos de la colección a la matriz especificada. |
| [GetEnumerator](../../aspose.slides/shapecollection/getenumerator)() | Devuelve un enumerador que itera a través de la colección. |
| [IndexOf](../../aspose.slides/shapecollection/indexof)(IShape) | Devuelve el índice de base cero de la primera aparición de una forma en la colección. |
| [InsertAudioFrameCD](../../aspose.slides/shapecollection/insertaudioframecd)(int, float, float, float, float) | Inserta un AudioFrame con CD. |
| [InsertAudioFrameEmbedded](../../aspose.slides/shapecollection/insertaudioframeembedded#insertaudioframeembedded)(int, float, float, float, float, IAudio) | Inserta un AudioFrame con un archivo de audio incrustado. Utiliza un archivo de audio de Presentation.Audios list. |
| [InsertAudioFrameEmbedded](../../aspose.slides/shapecollection/insertaudioframeembedded#insertaudioframeembedded_1)(int, float, float, float, float, Stream) | Inserte un AudioFrame con un archivo de audio incrustado. El sonido del archivo de audio incrustado solo puede ser WAV. |
| [InsertAudioFrameLinked](../../aspose.slides/shapecollection/insertaudioframelinked)(int, float, float, float, float, string) | Crea un nuevo cuadro de audio con un archivo de audio vinculado y lo inserta en una colección en el índice especificado. |
| [InsertAutoShape](../../aspose.slides/shapecollection/insertautoshape#insertautoshape)(int, ShapeType, float, float, float, float) | Crea una nueva autoforma, la ajusta a partir de la plantilla predeterminada y la inserta en la colección en el índice especificado. Nota: el tipo de forma estará determinado por el parámetro shapeType. |
| [InsertAutoShape](../../aspose.slides/shapecollection/insertautoshape#insertautoshape_1)(int, ShapeType, float, float, float, float, bool) | Crea una nueva autoforma y la inserta en la colección en el índice especificado. Nota: el tipo de forma estará determinado por el parámetro shapeType. |
| [InsertChart](../../aspose.slides/shapecollection/insertchart#insertchart)(ChartType, float, float, float, float, int) | Crea un nuevo gráfico, lo inicializa con datos y configuraciones de series de muestra y lo inserta en la posición especificada en la colección. |
| [InsertChart](../../aspose.slides/shapecollection/insertchart#insertchart_1)(ChartType, float, float, float, float, int, bool) | Crea un nuevo Gráfico y lo inserta en la posición especificada en la colección. |
| [InsertClone](../../aspose.slides/shapecollection/insertclone#insertclone)(int, IShape) | Inserta una copia de una forma especificada en la posición especificada de la colección. X, Y, Ancho y Alto de la nueva forma son iguales a X, Y, Ancho y Alto de la*sourceShape* . |
| [InsertClone](../../aspose.slides/shapecollection/insertclone#insertclone_1)(int, IShape, float, float) | Inserta una copia de una forma especificada en la posición especificada de la colección. El ancho y el alto de la nueva forma son iguales al ancho y el alto de la*sourceShape* . |
| [InsertClone](../../aspose.slides/shapecollection/insertclone#insertclone_2)(int, IShape, float, float, float, float) | Inserta una copia de una forma especificada en la posición especificada de la colección. |
| [InsertConnector](../../aspose.slides/shapecollection/insertconnector#insertconnector)(int, ShapeType, float, float, float, float) | Crea un nuevo conector, lo ajusta desde la plantilla predeterminada y lo inserta en la colección en el índice especificado. |
| [InsertConnector](../../aspose.slides/shapecollection/insertconnector#insertconnector_1)(int, ShapeType, float, float, float, float, bool) | Crea un nuevo conector y lo inserta en la colección en el índice especificado. |
| [InsertGroupShape](../../aspose.slides/shapecollection/insertgroupshape)(int) | Crea un nuevo GroupShape y lo inserta en la colección en el índice especificado. El tamaño y la posición del marco de GroupShape se adaptarán al contenido cuando se agregue una nueva forma al GroupShape. |
| [InsertOleObjectFrame](../../aspose.slides/shapecollection/insertoleobjectframe#insertoleobjectframe)(int, float, float, float, float, IOleEmbeddedDataInfo) | Crea un nuevo objeto OLE y lo inserta en una colección en el índice especificado. |
| [InsertOleObjectFrame](../../aspose.slides/shapecollection/insertoleobjectframe#insertoleobjectframe_1)(int, float, float, float, float, string, string) | Crea un nuevo objeto OLE y lo inserta en una colección en el índice especificado. |
| [InsertPictureFrame](../../aspose.slides/shapecollection/insertpictureframe)(int, ShapeType, float, float, float, float, IPPImage) | Crea un nuevo PictureFrame y lo inserta en la colección en el índice especificado. |
| [InsertSectionZoomFrame](../../aspose.slides/shapecollection/insertsectionzoomframe#insertsectionzoomframe)(int, float, float, float, float, ISection) | Crea un nuevo objeto Zoom de sección y lo inserta en una colección en el índice especificado. |
| [InsertSectionZoomFrame](../../aspose.slides/shapecollection/insertsectionzoomframe#insertsectionzoomframe_1)(int, float, float, float, float, ISection, IPPImage) | Crea un nuevo objeto Zoom de sección y lo inserta en una colección en el índice especificado. |
| [InsertSummaryZoomFrame](../../aspose.slides/shapecollection/insertsummaryzoomframe)(int, float, float, float, float) | Crea un nuevo objeto Zoom de resumen y lo inserta en una colección en el índice especificado. |
| [InsertTable](../../aspose.slides/shapecollection/inserttable)(int, float, float, double[], double[]) | Crea una nueva tabla y la inserta en la colección en el índice especificado. |
| [InsertVideoFrame](../../aspose.slides/shapecollection/insertvideoframe)(int, float, float, float, float, string) | Crea un nuevo cuadro de video y lo inserta en una colección en el índice especificado. |
| [InsertZoomFrame](../../aspose.slides/shapecollection/insertzoomframe#insertzoomframe)(int, float, float, float, float, ISlide) | Crea un nuevo objeto Zoom y lo inserta en una colección en el índice especificado. |
| [InsertZoomFrame](../../aspose.slides/shapecollection/insertzoomframe#insertzoomframe_1)(int, float, float, float, float, ISlide, IPPImage) | Crea un nuevo objeto Zoom y lo inserta en una colección en el índice especificado. |
| [Remove](../../aspose.slides/shapecollection/remove)(IShape) | Elimina la primera aparición de una forma específica de la colección. |
| [RemoveAt](../../aspose.slides/shapecollection/removeat)(int) | Elimina el elemento en el índice especificado de la colección. |
| [Reorder](../../aspose.slides/shapecollection/reorder#reorder)(int, IShape) | Mueve una forma de la colección a la posición especificada. |
| [Reorder](../../aspose.slides/shapecollection/reorder#reorder_1)(int, params IShape[]) | Mueve las formas de la colección a la posición especificada. Las formas se colocarán comenzando desde el índice en el orden en que aparecen en la lista. |
| [ToArray](../../aspose.slides/shapecollection/toarray#toarray)() | Crea y devuelve una matriz con todas las formas en ella. |
| [ToArray](../../aspose.slides/shapecollection/toarray#toarray_1)(int, int) | Crea y devuelve una matriz con todas las formas del rango especificado. Un índice de una primera forma para devolver.Una serie de formas para volver. |

### Ver también

* class [DomObject&lt;TParent&gt;](../domobject-1)
* class [GroupShape](../groupshape)
* interface [IShapeCollection](../ishapecollection)
* espacio de nombres [Aspose.Slides](../../aspose.slides)
* asamblea [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
