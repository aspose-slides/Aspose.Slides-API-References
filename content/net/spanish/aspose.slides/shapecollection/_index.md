---
title: ShapeCollection
second_title: Referencia de API de Aspose.Sildes para .NET
description: Representa una colección de formas.
type: docs
weight: 9860
url: /es/aspose.slides/shapecollection/
---
## ShapeCollection clase

Representa una colección de formas.

```csharp
public sealed class ShapeCollection : DomObject<GroupShape>, IShapeCollection
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [Count](../../aspose.slides/shapecollection/count) { get; } | Obtiene el número de elementos realmente contenidos en la colección. Solo lectura Int32. |
| [IsSynchronized](../../aspose.slides/shapecollection/issynchronized) { get; } | Devuelve un valor que indica si el acceso a la colección está sincronizado (seguro para subprocesos). Solo lectura Boolean. |
| [Item](../../aspose.slides/shapecollection/item) { get; } | Obtiene el elemento en el índice especificado. Solo lectura [`IShape`](../ishape). |
| [ParentGroup](../../aspose.slides/shapecollection/parentgroup) { get; } | Obtiene el objeto de forma de grupo padre para la colección de formas. Solo lectura [`IGroupShape`](../igroupshape). |
| [SyncRoot](../../aspose.slides/shapecollection/syncroot) { get; } | Devuelve una raíz de sincronización. Solo lectura Object. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [AddAudioFrameCD](../../aspose.slides/shapecollection/addaudioframecd)(float, float, float, float) | Crea un nuevo marco de audio vinculado a una pista de CD y lo agrega al final de la colección de formas. |
| [AddAudioFrameEmbedded](../../aspose.slides/shapecollection/addaudioframeembedded#addaudioframeembedded)(float, float, float, float, IAudio) | Crea un nuevo marco de audio y lo agrega al final de la colección de formas usando un objeto de audio existente de la lista Presentation.Audios. |
| [AddAudioFrameEmbedded](../../aspose.slides/shapecollection/addaudioframeembedded#addaudioframeembedded_1)(float, float, float, float, Stream) | Crea un nuevo marco de audio con un archivo WAV incrustado y lo agrega al final de la colección de formas. El audio incrustado se agrega a la colección Presentation.Audios. |
| [AddAudioFrameLinked](../../aspose.slides/shapecollection/addaudioframelinked)(float, float, float, float, string) | Crea un nuevo marco de audio vinculado a un archivo de audio externo y lo agrega al final de la colección de formas. |
| [AddAutoShape](../../aspose.slides/shapecollection/addautoshape#addautoshape)(ShapeType, float, float, float, float) | Crea una nueva forma automática con formato predeterminado y la agrega al final de la colección de formas. |
| [AddAutoShape](../../aspose.slides/shapecollection/addautoshape#addautoshape_1)(ShapeType, float, float, float, float, bool) | Crea una nueva forma automática y la agrega al final de la colección de formas, opcionalmente inicializándola con el formato de plantilla predeterminado. |
| [AddChart](../../aspose.slides/shapecollection/addchart#addchart)(ChartType, float, float, float, float) | Crea un nuevo gráfico, lo inicializa con datos y configuraciones de serie de ejemplo, y lo agrega al final de la colección de formas. |
| [AddChart](../../aspose.slides/shapecollection/addchart#addchart_1)(ChartType, float, float, float, float, bool) | Crea un nuevo gráfico, lo inicializa con datos y configuraciones de serie de ejemplo, y lo agrega al final de la colección de formas. |
| [AddClone](../../aspose.slides/shapecollection/addclone#addclone)(IShape) | Crea una copia de la forma especificada y la agrega al final de la colección de formas. La forma clonada mantiene la posición y el tamaño del original. |
| [AddClone](../../aspose.slides/shapecollection/addclone#addclone_1)(IShape, float, float) | Crea una copia de la forma especificada y la agrega al final de la colección de formas. La nueva forma mantiene el ancho y alto del *sourceShape*. |
| [AddClone](../../aspose.slides/shapecollection/addclone#addclone_2)(IShape, float, float, float, float) | Crea una copia de la forma especificada y la agrega al final de la colección de formas. |
| [AddConnector](../../aspose.slides/shapecollection/addconnector#addconnector)(ShapeType, float, float, float, float) | Crea una nueva forma de conector con estilo de plantilla predeterminado y la agrega al final de la colección de formas. |
| [AddConnector](../../aspose.slides/shapecollection/addconnector#addconnector_1)(ShapeType, float, float, float, float, bool) | Crea una nueva forma de conector y la agrega al final de la colección de formas, aplicando opcionalmente el estilo de plantilla predeterminado. |
| [AddGroupShape](../../aspose.slides/shapecollection/addgroupshape#addgroupshape)() | Crea una nueva forma de grupo vacía y la agrega al final de la colección de formas. El marco del grupo se ajustará automáticamente para adaptarse a cualquier forma añadida. |
| [AddGroupShape](../../aspose.slides/shapecollection/addgroupshape#addgroupshape_1)(ISvgImage, float, float, float, float) | Crea una nueva forma de grupo, convierte la imagen SVG especificada en formas individuales y agrega el grupo resultante al final de la colección de formas. |
| [AddMathShape](../../aspose.slides/shapecollection/addmathshape)(float, float, float, float) | Crea una nueva forma automática de rectángulo para albergar contenido matemático y la agrega al final de la colección de formas. |
| [AddOleObjectFrame](../../aspose.slides/shapecollection/addoleobjectframe#addoleobjectframe)(float, float, float, float, IOleEmbeddedDataInfo) | Crea un nuevo marco de objeto OLE y lo agrega al final de la colección de formas. |
| [AddOleObjectFrame](../../aspose.slides/shapecollection/addoleobjectframe#addoleobjectframe_1)(float, float, float, float, string, string) | Crea un nuevo marco de objeto OLE y lo agrega al final de la colección de formas. |
| [AddPictureFrame](../../aspose.slides/shapecollection/addpictureframe)(ShapeType, float, float, float, float, IPPImage) | Crea un nuevo marco de imagen que contiene la imagen especificada y lo agrega al final de la colección de formas. |
| [AddSectionZoomFrame](../../aspose.slides/shapecollection/addsectionzoomframe#addsectionzoomframe)(float, float, float, float, ISection) | Crea un nuevo marco Section Zoom y lo agrega al final de la colección de formas. |
| [AddSectionZoomFrame](../../aspose.slides/shapecollection/addsectionzoomframe#addsectionzoomframe_1)(float, float, float, float, ISection, IPPImage) | Crea un nuevo marco Section Zoom con una imagen predefinida y lo agrega al final de la colección de formas. |
| [AddSmartArt](../../aspose.slides/shapecollection/addsmartart)(float, float, float, float, SmartArtLayoutType) | Crea un diagrama SmartArt y lo agrega al final de la colección de formas. |
| [AddSummaryZoomFrame](../../aspose.slides/shapecollection/addsummaryzoomframe)(float, float, float, float) | Crea un nuevo marco Summary Zoom y lo agrega al final de la colección de formas. |
| [AddTable](../../aspose.slides/shapecollection/addtable)(float, float, double[], double[]) | Crea una nueva tabla y la agrega al final de la colección de formas. |
| [AddVideoFrame](../../aspose.slides/shapecollection/addvideoframe#addvideoframe)(float, float, float, float, IVideo) | Crea un nuevo marco de video y lo agrega al final de la colección de formas. |
| [AddVideoFrame](../../aspose.slides/shapecollection/addvideoframe#addvideoframe_1)(float, float, float, float, string) | Crea un nuevo marco de video y lo agrega al final de la colección de formas. |
| [AddZoomFrame](../../aspose.slides/shapecollection/addzoomframe#addzoomframe)(float, float, float, float, ISlide) | Crea un nuevo marco Zoom y lo agrega al final de la colección de formas. |
| [AddZoomFrame](../../aspose.slides/shapecollection/addzoomframe#addzoomframe_1)(float, float, float, float, ISlide, IPPImage) | Crea un nuevo marco Zoom y lo agrega al final de la colección de formas. |
| [Clear](../../aspose.slides/shapecollection/clear)() | Elimina todas las formas de la colección de formas. |
| [CopyTo](../../aspose.slides/shapecollection/copyto)(Array, int) | Copia todos los elementos de la colección al array especificado. |
| [GetEnumerator](../../aspose.slides/shapecollection/getenumerator)() | Devuelve un enumerador que itera a través de la colección. |
| [IndexOf](../../aspose.slides/shapecollection/indexof)(IShape) | Devuelve el índice basado en cero de la primera ocurrencia de la forma especificada en la colección. |
| [InsertAudioFrameCD](../../aspose.slides/shapecollection/insertaudioframecd)(int, float, float, float, float) | Crea un nuevo marco de audio vinculado a una pista de CD y lo inserta en la colección de formas en el índice especificado. |
| [InsertAudioFrameEmbedded](../../aspose.slides/shapecollection/insertaudioframeembedded#insertaudioframeembedded)(int, float, float, float, float, IAudio) | Crea un nuevo marco de audio y lo inserta en la colección de formas en el índice especificado usando un objeto de audio existente de la lista Presentation.Audios. |
| [InsertAudioFrameEmbedded](../../aspose.slides/shapecollection/insertaudioframeembedded#insertaudioframeembedded_1)(int, float, float, float, float, Stream) | Crea un nuevo marco de audio con un archivo WAV incrustado y lo inserta en la colección de formas en el índice especificado. El audio incrustado se agrega a la colección Presentation.Audios. |
| [InsertAudioFrameLinked](../../aspose.slides/shapecollection/insertaudioframelinked)(int, float, float, float, float, string) | Crea un nuevo marco de audio vinculado a un archivo de audio externo y lo inserta en la colección de formas en el índice especificado. |
| [InsertAutoShape](../../aspose.slides/shapecollection/insertautoshape#insertautoshape)(int, ShapeType, float, float, float, float) | Crea una nueva forma automática y la inserta en la colección de formas en el índice especificado, aplicando el formato de plantilla predeterminado. |
| [InsertAutoShape](../../aspose.slides/shapecollection/insertautoshape#insertautoshape_1)(int, ShapeType, float, float, float, float, bool) | Crea una nueva forma automática y la inserta en la colección de formas en el índice especificado, opcionalmente inicializándola con el estilo de plantilla predeterminado. |
| [InsertChart](../../aspose.slides/shapecollection/insertchart#insertchart)(ChartType, float, float, float, float, int) | Crea un nuevo gráfico, lo inicializa con datos y configuraciones de serie de ejemplo, y lo inserta en la colección de formas en el índice especificado. |
| [InsertChart](../../aspose.slides/shapecollection/insertchart#insertchart_1)(ChartType, float, float, float, float, int, bool) | Crea un nuevo gráfico, lo inicializa con datos y configuraciones de serie de ejemplo, y lo inserta en la colección de formas en el índice especificado. |
| [InsertClone](../../aspose.slides/shapecollection/insertclone#insertclone)(int, IShape) | Crea una copia de la forma especificada y la inserta en la colección de formas en el índice especificado. La forma clonada mantiene la posición y el tamaño del original. |
| [InsertClone](../../aspose.slides/shapecollection/insertclone#insertclone_1)(int, IShape, float, float) | Crea una copia de la forma especificada y la inserta en la colección de formas en el índice especificado. La nueva forma mantiene el ancho y alto del *sourceShape*. |
| [InsertClone](../../aspose.slides/shapecollection/insertclone#insertclone_2)(int, IShape, float, float, float, float) | Crea una copia de la forma especificada y la inserta en la colección de formas en el índice especificado. |
| [InsertConnector](../../aspose.slides/shapecollection/insertconnector#insertconnector)(int, ShapeType, float, float, float, float) | Crea una nueva forma de conector y la inserta en la colección de formas en el índice especificado, aplicando el estilo de plantilla predeterminado. |
| [InsertConnector](../../aspose.slides/shapecollection/insertconnector#insertconnector_1)(int, ShapeType, float, float, float, float, bool) | Crea una nueva forma de conector y la inserta en la colección de formas en el índice especificado, aplicando opcionalmente el estilo de plantilla predeterminado. |
| [InsertGroupShape](../../aspose.slides/shapecollection/insertgroupshape)(int) | Crea una nueva forma de grupo vacía y la inserta en la colección de formas en el índice especificado. El marco del grupo se ajustará automáticamente para adaptarse a cualquier forma añadida. |
| [InsertOleObjectFrame](../../aspose.slides/shapecollection/insertoleobjectframe#insertoleobjectframe)(int, float, float, float, float, IOleEmbeddedDataInfo) | Crea un nuevo marco de objeto OLE y lo inserta en la colección de formas en el índice especificado. |
| [InsertOleObjectFrame](../../aspose.slides/shapecollection/insertoleobjectframe#insertoleobjectframe_1)(int, float, float, float, float, string, string) | Crea un nuevo marco de objeto OLE y lo inserta en la colección de formas en el índice especificado. |
| [InsertPictureFrame](../../aspose.slides/shapecollection/insertpictureframe)(int, ShapeType, float, float, float, float, IPPImage) | Crea un nuevo marco de imagen que contiene la imagen especificada y lo inserta en la colección de formas en el índice especificado. |
| [InsertSectionZoomFrame](../../aspose.slides/shapecollection/insertsectionzoomframe#insertsectionzoomframe)(int, float, float, float, float, ISection) | Crea un nuevo marco Section Zoom y lo inserta en la colección de formas en el índice especificado. |
| [InsertSectionZoomFrame](../../aspose.slides/shapecollection/insertsectionzoomframe#insertsectionzoomframe_1)(int, float, float, float, float, ISection, IPPImage) | Crea un nuevo marco Section Zoom con una imagen predefinida y lo inserta en la colección de formas en el índice especificado. |
| [InsertSummaryZoomFrame](../../aspose.slides/shapecollection/insertsummaryzoomframe)(int, float, float, float, float) | Crea un nuevo marco Summary Zoom y lo inserta en la colección de formas en el índice especificado. |
| [InsertTable](../../aspose.slides/shapecollection/inserttable)(int, float, float, double[], double[]) | Crea una nueva tabla y la inserta en la colección de formas en el índice especificado. |
| [InsertVideoFrame](../../aspose.slides/shapecollection/insertvideoframe)(int, float, float, float, float, string) | Crea un nuevo marco de video y lo inserta en la colección de formas en el índice especificado. |
| [InsertZoomFrame](../../aspose.slides/shapecollection/insertzoomframe#insertzoomframe)(int, float, float, float, float, ISlide) | Crea un nuevo marco Zoom y lo inserta en la colección de formas en el índice especificado. |
| [InsertZoomFrame](../../aspose.slides/shapecollection/insertzoomframe#insertzoomframe_1)(int, float, float, float, float, ISlide, IPPImage) | Crea un nuevo marco Zoom con una imagen predefinida y lo inserta en la colección de formas en el índice especificado. |
| [Remove](../../aspose.slides/shapecollection/remove)(IShape) | Elimina la primera ocurrencia de la forma especificada de la colección de formas. |
| [RemoveAt](../../aspose.slides/shapecollection/removeat)(int) | Elimina la forma en el índice especificado de la colección de formas. |
| [Reorder](../../aspose.slides/shapecollection/reorder#reorder)(int, IShape) | Mueve la forma especificada a una nueva posición dentro de la colección de formas. |
| [Reorder](../../aspose.slides/shapecollection/reorder#reorder_1)(int, params IShape[]) | Mueve las formas especificadas dentro de la colección de formas, colocándolas a partir del índice indicado. |
| [ToArray](../../aspose.slides/shapecollection/toarray#toarray)() | Crea y devuelve un array que contiene todas las formas. |
| [ToArray](../../aspose.slides/shapecollection/toarray#toarray_1)(int, int) | Crea y devuelve un array que contiene todas las formas en el rango especificado. |

### Ver también

* clase [DomObject&lt;TParent&gt;](../domobject-1)
* clase [GroupShape](../groupshape)
* interfaz [IShapeCollection](../ishapecollection)
* espacio de nombres [Aspose.Slides](../../aspose.slides)
* ensamblado [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->