---
title: IShapeCollection
second_title: Aspose.Sildes para .NET API Reference
description: Representa una colección de formas.
type: docs
weight: 6760
url: /es/aspose.slides/ishapecollection/
---

## Interfaz IShapeCollection

Representa una colección de formas.

```csharp
public interface IShapeCollection : IGenericCollection<IShape>
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [Item](../../aspose.slides/ishapecollection/item) { get; } | Obtiene el elemento en el índice especificado. Solo lectura [`IShape`](../ishape). |
| [ParentGroup](../../aspose.slides/ishapecollection/parentgroup) { get; } | Devuelve el objeto GroupShape padre para una colección de formas. Solo lectura [`IGroupShape`](../igroupshape). |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [AddAudioFrameCD](../../aspose.slides/ishapecollection/addaudioframecd)(float, float, float, float) | Agrega un AudioFrame con CD al final de la colección. |
| [AddAudioFrameEmbedded](../../aspose.slides/ishapecollection/addaudioframeembedded#addaudioframeembedded)(float, float, float, float, IAudio) | Agrega un nuevo marco de audio con un archivo de audio incrustado al final de una colección. Utiliza el archivo de audio de la lista Presentation.Audios. |
| [AddAudioFrameEmbedded](../../aspose.slides/ishapecollection/addaudioframeembedded#addaudioframeembedded_1)(float, float, float, float, Stream) | Agrega un nuevo marco de audio con un archivo de audio incrustado al final de una colección. El archivo de audio incrustado solo puede ser un WAV. Agrega un nuevo audio a la lista Presentation.Audios. |
| [AddAudioFrameLinked](../../aspose.slides/ishapecollection/addaudioframelinked)(float, float, float, float, string) | Agrega un nuevo marco de audio con un archivo de audio vinculado al final de una colección. |
| [AddAutoShape](../../aspose.slides/ishapecollection/addautoshape#addautoshape)(ShapeType, float, float, float, float) | Crea una nueva AutoShape, la ajusta desde la plantilla predeterminada y la agrega al final de la colección. |
| [AddAutoShape](../../aspose.slides/ishapecollection/addautoshape#addautoshape_1)(ShapeType, float, float, float, float, bool) | Crea una nueva AutoShape y la agrega al final de la colección. |
| [AddChart](../../aspose.slides/ishapecollection/addchart#addchart)(ChartType, float, float, float, float) | Crea un nuevo gráfico, lo inicializa con datos de series de ejemplo y configuraciones, y lo agrega al final de la colección. |
| [AddChart](../../aspose.slides/ishapecollection/addchart#addchart_1)(ChartType, float, float, float, float, bool) | Crea un nuevo gráfico y lo agrega al final de la colección. |
| [AddClone](../../aspose.slides/ishapecollection/addclone#addclone)(IShape) | Agrega una copia de una forma especificada al final de la colección. X, Y, Width y Height de la nueva forma son iguales a X, Y, Width y Height de la *sourceShape*. |
| [AddClone](../../aspose.slides/ishapecollection/addclone#addclone_1)(IShape, float, float) | Agrega una copia de una forma especificada al final de la colección. Width y Height de la nueva forma son iguales a Width y Height de la *sourceShape*. |
| [AddClone](../../aspose.slides/ishapecollection/addclone#addclone_2)(IShape, float, float, float, float) | Agrega una copia de una forma especificada al final de la colección. |
| [AddConnector](../../aspose.slides/ishapecollection/addconnector#addconnector)(ShapeType, float, float, float, float) | Crea un nuevo conector, lo ajusta desde la plantilla predeterminada y lo agrega al final de la colección. |
| [AddConnector](../../aspose.slides/ishapecollection/addconnector#addconnector_1)(ShapeType, float, float, float, float, bool) | Crea un nuevo conector y lo agrega al final de la colección. |
| [AddGroupShape](../../aspose.slides/ishapecollection/addgroupshape#addgroupshape)() | Crea un nuevo GroupShape y lo agrega al final de la colección. El tamaño y la posición del marco de GroupShape se ajustarán al contenido cuando se agregue una nueva forma al GroupShape. |
| [AddGroupShape](../../aspose.slides/ishapecollection/addgroupshape#addgroupshape_1)(ISvgImage, float, float, float, float) | Crea un nuevo GroupShape, lo llena con formas convertidas de SVG y lo agrega al final de la colección. |
| [AddMathShape](../../aspose.slides/ishapecollection/addmathshape)(float, float, float, float) | Crea una nueva AutoShape del tipo Rectángulo para albergar contenido matemático en su interior y la agrega al final de la colección. |
| [AddOleObjectFrame](../../aspose.slides/ishapecollection/addoleobjectframe#addoleobjectframe)(float, float, float, float, IOleEmbeddedDataInfo) | Agrega un nuevo objeto OLE al final de una colección. |
| [AddOleObjectFrame](../../aspose.slides/ishapecollection/addoleobjectframe#addoleobjectframe_1)(float, float, float, float, string, string) | Agrega un nuevo objeto OLE al final de una colección. |
| [AddPictureFrame](../../aspose.slides/ishapecollection/addpictureframe)(ShapeType, float, float, float, float, IPPImage) | Crea un nuevo PictureFrame y lo agrega al final de la colección. |
| [AddSectionZoomFrame](../../aspose.slides/ishapecollection/addsectionzoomframe#addsectionzoomframe)(float, float, float, float, ISection) | Agrega un nuevo objeto de zoom de sección al final de una colección. |
| [AddSectionZoomFrame](../../aspose.slides/ishapecollection/addsectionzoomframe#addsectionzoomframe_1)(float, float, float, float, ISection, IPPImage) | Agrega un nuevo objeto de zoom de sección al final de una colección con una imagen predefinida. |
| [AddSmartArt](../../aspose.slides/ishapecollection/addsmartart)(float, float, float, float, SmartArtLayoutType) | Agrega un diagrama SmartArt. |
| [AddSummaryZoomFrame](../../aspose.slides/ishapecollection/addsummaryzoomframe)(float, float, float, float) | Agrega un nuevo objeto de resumen de zoom al final de una colección. |
| [AddTable](../../aspose.slides/ishapecollection/addtable)(float, float, double[], double[]) | Crea una nueva tabla y la agrega al final de la colección. |
| [AddVideoFrame](../../aspose.slides/ishapecollection/addvideoframe#addvideoframe)(float, float, float, float, IVideo) | Agrega un nuevo marco de video al final de una colección. |
| [AddVideoFrame](../../aspose.slides/ishapecollection/addvideoframe#addvideoframe_1)(float, float, float, float, string) | Agrega un nuevo marco de video al final de una colección. |
| [AddZoomFrame](../../aspose.slides/ishapecollection/addzoomframe#addzoomframe)(float, float, float, float, ISlide) | Agrega un nuevo objeto de zoom al final de una colección. |
| [AddZoomFrame](../../aspose.slides/ishapecollection/addzoomframe#addzoomframe_1)(float, float, float, float, ISlide, IPPImage) | Agrega un nuevo objeto de zoom al final de una colección. |
| [Clear](../../aspose.slides/ishapecollection/clear)() | Elimina todas las formas de la colección. |
| [IndexOf](../../aspose.slides/ishapecollection/indexof)(IShape) | Devuelve el índice basado en cero de la primera ocurrencia de una forma en la colección. |
| [InsertAudioFrameCD](../../aspose.slides/ishapecollection/insertaudioframecd)(int, float, float, float, float) | Inserta un AudioFrame con CD. |
| [InsertAudioFrameEmbedded](../../aspose.slides/ishapecollection/insertaudioframeembedded#insertaudioframeembedded)(int, float, float, float, float, IAudio) | Inserta un AudioFrame con un archivo de audio incrustado. Utiliza el archivo de audio de la lista Presentation.Audios. |
| [InsertAudioFrameEmbedded](../../aspose.slides/ishapecollection/insertaudioframeembedded#insertaudioframeembedded_1)(int, float, float, float, float, Stream) | Inserta un AudioFrame con un archivo de audio incrustado. El sonido del archivo de audio incrustado puede ser solo un WAV. Agrega nuevo audio a la lista Presentation.Audios. |
| [InsertAudioFrameLinked](../../aspose.slides/ishapecollection/insertaudioframelinked)(int, float, float, float, float, string) | Crea un nuevo marco de audio con un archivo de audio vinculado e inserta en una colección en el índice especificado. |
| [InsertAutoShape](../../aspose.slides/ishapecollection/insertautoshape#insertautoshape)(int, ShapeType, float, float, float, float) | Crea una nueva AutoShape, la ajusta desde la plantilla predeterminada e inserta en la colección en el índice especificado. Nota: el tipo de la forma se determinará por el parámetro shapeType. |
| [InsertAutoShape](../../aspose.slides/ishapecollection/insertautoshape#insertautoshape_1)(int, ShapeType, float, float, float, float, bool) | Crea una nueva AutoShape e inserta en la colección en el índice especificado. Nota: el tipo de la forma se determinará por el parámetro shapeType. |
| [InsertChart](../../aspose.slides/ishapecollection/insertchart#insertchart)(ChartType, float, float, float, float, int) | Crea un nuevo gráfico, lo inicializa con datos de series de ejemplo y configuraciones, e inserta en la posición especificada en la colección. |
| [InsertChart](../../aspose.slides/ishapecollection/insertchart#insertchart_1)(ChartType, float, float, float, float, int, bool) | Crea un nuevo gráfico e inserta en la posición especificada en la colección. |
| [InsertClone](../../aspose.slides/ishapecollection/insertclone#insertclone)(int, IShape) | Inserta una copia de una forma especificada en la posición especificada de la colección. X, Y, Width y Height de la nueva forma son iguales a X, Y, Width y Height de la *sourceShape*. |
| [InsertClone](../../aspose.slides/ishapecollection/insertclone#insertclone_1)(int, IShape, float, float) | Inserta una copia de una forma especificada en la posición especificada de la colección. Width y Height de la nueva forma son iguales a Width y Height de la *sourceShape*. |
| [InsertClone](../../aspose.slides/ishapecollection/insertclone#insertclone_2)(int, IShape, float, float, float, float) | Inserta una copia de una forma especificada en la posición especificada de la colección. |
| [InsertConnector](../../aspose.slides/ishapecollection/insertconnector#insertconnector)(int, ShapeType, float, float, float, float) | Crea un nuevo conector, lo ajusta desde la plantilla predeterminada e inserta en la colección en el índice especificado. |
| [InsertConnector](../../aspose.slides/ishapecollection/insertconnector#insertconnector_1)(int, ShapeType, float, float, float, float, bool) | Crea un nuevo conector e inserta en la colección en el índice especificado. |
| [InsertGroupShape](../../aspose.slides/ishapecollection/insertgroupshape)(int) | Crea un nuevo GroupShape e inserta en la colección en el índice especificado. El tamaño y la posición del marco de GroupShape se ajustarán al contenido cuando se agregue una nueva forma al GroupShape. |
| [InsertOleObjectFrame](../../aspose.slides/ishapecollection/insertoleobjectframe#insertoleobjectframe)(int, float, float, float, float, IOleEmbeddedDataInfo) | Crea un nuevo objeto OLE e inserta en una colección en el índice especificado. |
| [InsertOleObjectFrame](../../aspose.slides/ishapecollection/insertoleobjectframe#insertoleobjectframe_1)(int, float, float, float, float, string, string) | Crea un nuevo objeto OLE e inserta en una colección en el índice especificado. |
| [InsertPictureFrame](../../aspose.slides/ishapecollection/insertpictureframe)(int, ShapeType, float, float, float, float, IPPImage) | Crea un nuevo PictureFrame e inserta en la colección en el índice especificado. |
| [InsertSectionZoomFrame](../../aspose.slides/ishapecollection/insertsectionzoomframe#insertsectionzoomframe)(int, float, float, float, float, ISection) | Crea un nuevo objeto de zoom de sección e inserta en una colección en el índice especificado. |
| [InsertSectionZoomFrame](../../aspose.slides/ishapecollection/insertsectionzoomframe#insertsectionzoomframe_1)(int, float, float, float, float, ISection, IPPImage) | Crea un nuevo objeto de zoom de sección e inserta en una colección en el índice especificado. |
| [InsertSummaryZoomFrame](../../aspose.slides/ishapecollection/insertsummaryzoomframe)(int, float, float, float, float) | Crea un nuevo objeto de resumen de zoom e inserta en una colección en el índice especificado. |
| [InsertTable](../../aspose.slides/ishapecollection/inserttable)(int, float, float, double[], double[]) | Crea una nueva tabla e inserta en la colección en el índice especificado. |
| [InsertVideoFrame](../../aspose.slides/ishapecollection/insertvideoframe)(int, float, float, float, float, string) | Crea un nuevo marco de video e inserta en una colección en el índice especificado. |
| [InsertZoomFrame](../../aspose.slides/ishapecollection/insertzoomframe#insertzoomframe)(int, float, float, float, float, ISlide) | Crea un nuevo objeto de zoom e inserta en una colección en el índice especificado. |
| [InsertZoomFrame](../../aspose.slides/ishapecollection/insertzoomframe#insertzoomframe_1)(int, float, float, float, float, ISlide, IPPImage) | Crea un nuevo objeto de zoom e inserta en una colección en el índice especificado. |
| [Remove](../../aspose.slides/ishapecollection/remove)(IShape) | Elimina la primera ocurrencia de una forma específica de la colección. |
| [RemoveAt](../../aspose.slides/ishapecollection/removeat)(int) | Elimina el elemento en el índice especificado de la colección. |
| [Reorder](../../aspose.slides/ishapecollection/reorder#reorder)(int, IShape) | Mueve una forma de la colección a la posición especificada. |
| [Reorder](../../aspose.slides/ishapecollection/reorder#reorder_1)(int, params IShape[]) | Mueve formas de la colección a la posición especificada. Las formas se colocarán comenzando desde el índice en el orden en que aparecen en la lista. |
| [ToArray](../../aspose.slides/ishapecollection/toarray#toarray)() | Crea y devuelve un arreglo con todas las formas en él. |
| [ToArray](../../aspose.slides/ishapecollection/toarray#toarray_1)(int, int) | Crea y devuelve un arreglo con todas las formas del rango especificado en él. |

### Ver También

* interfaz [IGenericCollection&lt;T&gt;](../igenericcollection-1)
* interfaz [IShape](../ishape)
* espacio de nombres [Aspose.Slides](../../aspose.slides)
* ensamblado [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->