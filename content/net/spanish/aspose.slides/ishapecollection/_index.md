---
title: IShapeCollection
second_title: Aspose.Sildes para .NET Referencia de API
description: Representa una colección de formas.
type: docs
weight: 6980
url: /es/aspose.slides/ishapecollection/
---
## IShapeCollection interfaz

Representa una colección de formas.

```csharp
public interface IShapeCollection : IGenericCollection<IShape>
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [Item](../../aspose.slides/ishapecollection/item) { get; } | Obtiene el elemento en el índice especificado. Solo lectura [`IShape`](../ishape). |
| [ParentGroup](../../aspose.slides/ishapecollection/parentgroup) { get; } | Obtiene el objeto de forma de grupo principal para la colección de formas. Solo lectura [`IGroupShape`](../igroupshape). |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [AddAudioFrameCD](../../aspose.slides/ishapecollection/addaudioframecd)(float, float, float, float) | Crea un nuevo marco de audio vinculado a una pista de CD y lo agrega al final de la colección de formas. |
| [AddAudioFrameEmbedded](../../aspose.slides/ishapecollection/addaudioframeembedded#addaudioframeembedded)(float, float, float, float, IAudio) | Crea un nuevo marco de audio y lo agrega al final de la colección de formas usando un objeto de audio existente de la lista Presentation.Audios. |
| [AddAudioFrameEmbedded](../../aspose.slides/ishapecollection/addaudioframeembedded#addaudioframeembedded_1)(float, float, float, float, Stream) | Crea un nuevo marco de audio con un archivo WAV incrustado y lo agrega al final de la colección de formas. El audio incrustado se agrega a la colección Presentation.Audios. |
| [AddAudioFrameLinked](../../aspose.slides/ishapecollection/addaudioframelinked)(float, float, float, float, string) | Crea un nuevo marco de audio vinculado a un archivo de audio externo y lo agrega al final de la colección de formas. |
| [AddAutoShape](../../aspose.slides/ishapecollection/addautoshape#addautoshape)(ShapeType, float, float, float, float) | Crea una nueva autoforma con formato predeterminado y la agrega al final de la colección de formas. |
| [AddAutoShape](../../aspose.slides/ishapecollection/addautoshape#addautoshape_1)(ShapeType, float, float, float, float, bool) | Crea una nueva autoforma y la agrega al final de la colección de formas, opcionalmente inicializándola con el formato de plantilla predeterminado. |
| [AddChart](../../aspose.slides/ishapecollection/addchart#addchart)(ChartType, float, float, float, float) | Crea un nuevo gráfico, lo inicializa con datos y configuraciones de series de ejemplo, y lo agrega al final de la colección de formas. |
| [AddChart](../../aspose.slides/ishapecollection/addchart#addchart_1)(ChartType, float, float, float, float, bool) | Crea un nuevo gráfico, lo inicializa con datos y configuraciones de series de ejemplo, y lo agrega al final de la colección de formas. |
| [AddClone](../../aspose.slides/ishapecollection/addclone#addclone)(IShape) | Crea una copia de la forma especificada y la agrega al final de la colección de formas. La forma clonada conserva la posición y el tamaño originales. |
| [AddClone](../../aspose.slides/ishapecollection/addclone#addclone_1)(IShape, float, float) | Crea una copia de la forma especificada y la agrega al final de la colección de formas. La nueva forma conserva el ancho y alto de la *sourceShape*. |
| [AddClone](../../aspose.slides/ishapecollection/addclone#addclone_2)(IShape, float, float, float, float) | Crea una copia de la forma especificada y la agrega al final de la colección de formas. |
| [AddConnector](../../aspose.slides/ishapecollection/addconnector#addconnector)(ShapeType, float, float, float, float) | Crea una nueva forma conector con estilo de plantilla predeterminado y la agrega al final de la colección de formas. |
| [AddConnector](../../aspose.slides/ishapecollection/addconnector#addconnector_1)(ShapeType, float, float, float, float, bool) | Crea una nueva forma conector y la agrega al final de la colección de formas, opcionalmente aplicando el estilo de plantilla predeterminado. |
| [AddGroupShape](../../aspose.slides/ishapecollection/addgroupshape#addgroupshape)() | Crea un nuevo grupo de formas vacío y lo agrega al final de la colección de formas. El marco del grupo se ajustará automáticamente para encajar las formas que se añadan. |
| [AddGroupShape](../../aspose.slides/ishapecollection/addgroupshape#addgroupshape_1)(ISvgImage, float, float, float, float) | Crea un nuevo grupo de formas, convierte la imagen SVG especificada en formas individuales y agrega el grupo resultante al final de la colección de formas. |
| [AddMathShape](../../aspose.slides/ishapecollection/addmathshape)(float, float, float, float) | Crea una nueva autoforma rectangular para alojar contenido matemático y la agrega al final de la colección de formas. |
| [AddOleObjectFrame](../../aspose.slides/ishapecollection/addoleobjectframe#addoleobjectframe)(float, float, float, float, IOleEmbeddedDataInfo) | Crea un nuevo marco de objeto OLE y lo agrega al final de la colección de formas. |
| [AddOleObjectFrame](../../aspose.slides/ishapecollection/addoleobjectframe#addoleobjectframe_1)(float, float, float, float, string, string) | Crea un nuevo marco de objeto OLE y lo agrega al final de la colección de formas. |
| [AddPictureFrame](../../aspose.slides/ishapecollection/addpictureframe)(ShapeType, float, float, float, float, IPPImage) | Crea un nuevo marco de imagen que contiene la imagen especificada y lo agrega al final de la colección de formas. |
| [AddSectionZoomFrame](../../aspose.slides/ishapecollection/addsectionzoomframe#addsectionzoomframe)(float, float, float, float, ISection) | Crea un nuevo marco Section Zoom y lo agrega al final de la colección de formas. |
| [AddSectionZoomFrame](../../aspose.slides/ishapecollection/addsectionzoomframe#addsectionzoomframe_1)(float, float, float, float, ISection, IPPImage) | Crea un nuevo marco Section Zoom con una imagen predefinida y lo agrega al final de la colección de formas. |
| [AddSmartArt](../../aspose.slides/ishapecollection/addsmartart)(float, float, float, float, SmartArtLayoutType) | Crea un diagrama SmartArt y lo agrega al final de la colección de formas. |
| [AddSummaryZoomFrame](../../aspose.slides/ishapecollection/addsummaryzoomframe)(float, float, float, float) | Crea un nuevo marco Summary Zoom y lo agrega al final de la colección de formas. |
| [AddTable](../../aspose.slides/ishapecollection/addtable)(float, float, double[], double[]) | Crea una nueva tabla y la agrega al final de la colección de formas. |
| [AddVideoFrame](../../aspose.slides/ishapecollection/addvideoframe#addvideoframe)(float, float, float, float, IVideo) | Crea un nuevo marco de video y lo agrega al final de la colección de formas. |
| [AddVideoFrame](../../aspose.slides/ishapecollection/addvideoframe#addvideoframe_1)(float, float, float, float, string) | Crea un nuevo marco de video y lo agrega al final de la colección de formas. |
| [AddZoomFrame](../../aspose.slides/ishapecollection/addzoomframe#addzoomframe)(float, float, float, float, ISlide) | Crea un nuevo marco Zoom y lo agrega al final de la colección de formas. |
| [AddZoomFrame](../../aspose.slides/ishapecollection/addzoomframe#addzoomframe_1)(float, float, float, float, ISlide, IPPImage) | Crea un nuevo marco Zoom y lo agrega al final de la colección de formas. |
| [Clear](../../aspose.slides/ishapecollection/clear)() | Elimina todas las formas de la colección de formas. |
| [IndexOf](../../aspose.slides/ishapecollection/indexof)(IShape) | Devuelve el índice basado en cero de la primera aparición de la forma especificada en la colección. |
| [InsertAudioFrameCD](../../aspose.slides/ishapecollection/insertaudioframecd)(int, float, float, float, float) | Crea un nuevo marco de audio vinculado a una pista de CD y lo inserta en la colección de formas en el índice especificado. |
| [InsertAudioFrameEmbedded](../../aspose.slides/ishapecollection/insertaudioframeembedded#insertaudioframeembedded)(int, float, float, float, float, IAudio) | Crea un nuevo marco de audio y lo inserta en la colección de formas en el índice especificado usando un objeto de audio existente de la lista Presentation.Audios. |
| [InsertAudioFrameEmbedded](../../aspose.slides/ishapecollection/insertaudioframeembedded#insertaudioframeembedded_1)(int, float, float, float, float, Stream) | Crea un nuevo marco de audio con un archivo WAV incrustado y lo inserta en la colección de formas en el índice especificado. El audio incrustado se agrega a la colección Presentation.Audios. |
| [InsertAudioFrameLinked](../../aspose.slides/ishapecollection/insertaudioframelinked)(int, float, float, float, float, string) | Crea un nuevo marco de audio vinculado a un archivo de audio externo y lo inserta en la colección de formas en el índice especificado. |
| [InsertAutoShape](../../aspose.slides/ishapecollection/insertautoshape#insertautoshape)(int, ShapeType, float, float, float, float) | Crea una nueva autoforma e inserta en la colección de formas en el índice especificado, aplicando el formato de plantilla predeterminado. |
| [InsertAutoShape](../../aspose.slides/ishapecollection/insertautoshape#insertautoshape_1)(int, ShapeType, float, float, float, float, bool) | Crea una nueva autoforma e inserta en la colección de formas en el índice especificado, opcionalmente inicializándola con el estilo de plantilla predeterminado. |
| [InsertChart](../../aspose.slides/ishapecollection/insertchart#insertchart)(ChartType, float, float, float, float, int) | Crea un nuevo gráfico, lo inicializa con datos y configuraciones de series de ejemplo, y lo inserta en la colección de formas en el índice especificado. |
| [InsertChart](../../aspose.slides/ishapecollection/insertchart#insertchart_1)(ChartType, float, float, float, float, int, bool) | Crea un nuevo gráfico, lo inicializa con datos y configuraciones de series de ejemplo, y lo inserta en la colección de formas en el índice especificado. |
| [InsertClone](../../aspose.slides/ishapecollection/insertclone#insertclone)(int, IShape) | Crea una copia de la forma especificada y la inserta en la colección de formas en el índice especificado. La forma clonada conserva la posición y el tamaño originales. |
| [InsertClone](../../aspose.slides/ishapecollection/insertclone#insertclone_1)(int, IShape, float, float) | Crea una copia de la forma especificada y la inserta en la colección de formas en el índice especificado. La nueva forma conserva el ancho y alto de la *sourceShape*. |
| [InsertClone](../../aspose.slides/ishapecollection/insertclone#insertclone_2)(int, IShape, float, float, float, float) | Crea una copia de la forma especificada y la inserta en la colección de formas en el índice especificado. |
| [InsertConnector](../../aspose.slides/ishapecollection/insertconnector#insertconnector)(int, ShapeType, float, float, float, float) | Crea una nueva forma conector e inserta en la colección de formas en el índice especificado, aplicando el estilo de plantilla predeterminado. |
| [InsertConnector](../../aspose.slides/ishapecollection/insertconnector#insertconnector_1)(int, ShapeType, float, float, float, float, bool) | Crea una nueva forma conector e inserta en la colección de formas en el índice especificado, opcionalmente aplicando el estilo de plantilla predeterminado. |
| [InsertGroupShape](../../aspose.slides/ishapecollection/insertgroupshape)(int) | Crea un nuevo grupo de formas vacío e inserta en la colección de formas en el índice especificado. El marco del grupo se ajustará automáticamente para encajar las formas que se añadan. |
| [InsertOleObjectFrame](../../aspose.slides/ishapecollection/insertoleobjectframe#insertoleobjectframe)(int, float, float, float, float, IOleEmbeddedDataInfo) | Crea un nuevo marco de objeto OLE e inserta en la colección de formas en el índice especificado. |
| [InsertOleObjectFrame](../../aspose.slides/ishapecollection/insertoleobjectframe#insertoleobjectframe_1)(int, float, float, float, float, string, string) | Crea un nuevo marco de objeto OLE e inserta en la colección de formas en el índice especificado. |
| [InsertPictureFrame](../../aspose.slides/ishapecollection/insertpictureframe)(int, ShapeType, float, float, float, float, IPPImage) | Crea un nuevo marco de imagen que contiene la imagen especificada e inserta en la colección de formas en el índice especificado. |
| [InsertSectionZoomFrame](../../aspose.slides/ishapecollection/insertsectionzoomframe#insertsectionzoomframe)(int, float, float, float, float, ISection) | Crea un nuevo marco Section Zoom e inserta en la colección de formas en el índice especificado. |
| [InsertSectionZoomFrame](../../aspose.slides/ishapecollection/insertsectionzoomframe#insertsectionzoomframe_1)(int, float, float, float, float, ISection, IPPImage) | Crea un nuevo marco Section Zoom con una imagen predefinida e inserta en la colección de formas en el índice especificado. |
| [InsertSummaryZoomFrame](../../aspose.slides/ishapecollection/insertsummaryzoomframe)(int, float, float, float, float) | Crea un nuevo marco Summary Zoom e inserta en la colección de formas en el índice especificado. |
| [InsertTable](../../aspose.slides/ishapecollection/inserttable)(int, float, float, double[], double[]) | Crea una nueva tabla e inserta en la colección de formas en el índice especificado. |
| [InsertVideoFrame](../../aspose.slides/ishapecollection/insertvideoframe)(int, float, float, float, float, string) | Crea un nuevo marco de video e inserta en la colección de formas en el índice especificado. |
| [InsertZoomFrame](../../aspose.slides/ishapecollection/insertzoomframe#insertzoomframe)(int, float, float, float, float, ISlide) | Crea un nuevo marco Zoom e inserta en la colección de formas en el índice especificado. |
| [InsertZoomFrame](../../aspose.slides/ishapecollection/insertzoomframe#insertzoomframe_1)(int, float, float, float, float, ISlide, IPPImage) | Crea un nuevo marco Zoom con una imagen predefinida e inserta en la colección de formas en el índice especificado. |
| [Remove](../../aspose.slides/ishapecollection/remove)(IShape) | Elimina la primera aparición de la forma especificada de la colección de formas. |
| [RemoveAt](../../aspose.slides/ishapecollection/removeat)(int) | Elimina la forma en el índice especificado de la colección de formas. |
| [Reorder](../../aspose.slides/ishapecollection/reorder#reorder)(int, IShape) | Mueve la forma especificada a una nueva posición dentro de la colección de formas. |
| [Reorder](../../aspose.slides/ishapecollection/reorder#reorder_1)(int, params IShape[]) | Mueve las formas especificadas dentro de la colección de formas, colocándolas a partir del índice indicado. |
| [ToArray](../../aspose.slides/ishapecollection/toarray#toarray)() | Crea y devuelve una matriz que contiene todas las formas. |
| [ToArray](../../aspose.slides/ishapecollection/toarray#toarray_1)(int, int) | Crea y devuelve una matriz que contiene todas las formas en el rango especificado. |

### Ver también

* interfaz [IGenericCollection&lt;T&gt;](../igenericcollection-1)
* interfaz [IShape](../ishape)
* espacio de nombres [Aspose.Slides](../../aspose.slides)
* ensamblado [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->