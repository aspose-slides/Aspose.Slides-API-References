---
title: IShapeCollection
second_title: Aspose.Sildes para .NET Referência da API
description: Representa uma coleção de formas.
type: docs
weight: 6980
url: /pt/aspose.slides/ishapecollection/
---
## IShapeCollection interface

Representa uma coleção de formas.

```csharp
public interface IShapeCollection : IGenericCollection<IShape>
```

## Propriedades

| Nome | Descrição |
| --- | --- |
| [Item](../../aspose.slides/ishapecollection/item) { get; } | Obtém o elemento no índice especificado. Somente leitura [`IShape`](../ishape). |
| [ParentGroup](../../aspose.slides/ishapecollection/parentgroup) { get; } | Obtém o objeto de forma de grupo pai para a coleção de formas. Somente leitura [`IGroupShape`](../igroupshape). |

## Métodos

| Nome | Descrição |
| --- | --- |
| [AddAudioFrameCD](../../aspose.slides/ishapecollection/addaudioframecd)(float, float, float, float) | Cria um novo quadro de áudio vinculado a uma faixa de CD e o adiciona ao final da coleção de formas. |
| [AddAudioFrameEmbedded](../../aspose.slides/ishapecollection/addaudioframeembedded#addaudioframeembedded)(float, float, float, float, IAudio) | Cria um novo quadro de áudio e o adiciona ao final da coleção de formas usando um objeto de áudio existente da lista Presentation.Audios. |
| [AddAudioFrameEmbedded](../../aspose.slides/ishapecollection/addaudioframeembedded#addaudioframeembedded_1)(float, float, float, float, Stream) | Cria um novo quadro de áudio com um arquivo WAV incorporado e o adiciona ao final da coleção de formas. O áudio incorporado é adicionado à coleção Presentation.Audios. |
| [AddAudioFrameLinked](../../aspose.slides/ishapecollection/addaudioframelinked)(float, float, float, float, string) | Cria um novo quadro de áudio vinculado a um arquivo de áudio externo e o adiciona ao final da coleção de formas. |
| [AddAutoShape](../../aspose.slides/ishapecollection/addautoshape#addautoshape)(ShapeType, float, float, float, float) | Cria uma nova forma automática com formatação padrão e a adiciona ao final da coleção de formas. |
| [AddAutoShape](../../aspose.slides/ishapecollection/addautoshape#addautoshape_1)(ShapeType, float, float, float, float, bool) | Cria uma nova forma automática e a adiciona ao final da coleção de formas, opcionalmente inicializando-a com formatação padrão do modelo. |
| [AddChart](../../aspose.slides/ishapecollection/addchart#addchart)(ChartType, float, float, float, float) | Cria um novo gráfico, inicializa-o com dados e configurações de série de exemplo, e o adiciona ao final da coleção de formas. |
| [AddChart](../../aspose.slides/ishapecollection/addchart#addchart_1)(ChartType, float, float, float, float, bool) | Cria um novo gráfico, inicializa-o com dados e configurações de série de exemplo, e o adiciona ao final da coleção de formas. |
| [AddClone](../../aspose.slides/ishapecollection/addclone#addclone)(IShape) | Cria uma cópia da forma especificada e a adiciona ao final da coleção de formas. A forma clonada mantém a posição e o tamanho originais. |
| [AddClone](../../aspose.slides/ishapecollection/addclone#addclone_1)(IShape, float, float) | Cria uma cópia da forma especificada e a adiciona ao final da coleção de formas. A nova forma mantém a largura e a altura da *sourceShape*. |
| [AddClone](../../aspose.slides/ishapecollection/addclone#addclone_2)(IShape, float, float, float, float) | Cria uma cópia da forma especificada e a adiciona ao final da coleção de formas. |
| [AddConnector](../../aspose.slides/ishapecollection/addconnector#addconnector)(ShapeType, float, float, float, float) | Cria uma nova forma de conector com estilo de modelo padrão e a adiciona ao final da coleção de formas. |
| [AddConnector](../../aspose.slides/ishapecollection/addconnector#addconnector_1)(ShapeType, float, float, float, float, bool) | Cria uma nova forma de conector e a adiciona ao final da coleção de formas, opcionalmente aplicando o estilo padrão do modelo. |
| [AddGroupShape](../../aspose.slides/ishapecollection/addgroupshape#addgroupshape)() | Cria uma nova forma de grupo vazia e a adiciona ao final da coleção de formas. O quadro do grupo será ajustado automaticamente para acomodar quaisquer formas adicionadas. |
| [AddGroupShape](../../aspose.slides/ishapecollection/addgroupshape#addgroupshape_1)(ISvgImage, float, float, float, float) | Cria uma nova forma de grupo, converte a imagem SVG especificada em formas individuais e adiciona o grupo resultante ao final da coleção de formas. |
| [AddMathShape](../../aspose.slides/ishapecollection/addmathshape)(float, float, float, float) | Cria uma nova forma automática de retângulo para hospedar conteúdo matemático e a adiciona ao final da coleção de formas. |
| [AddOleObjectFrame](../../aspose.slides/ishapecollection/addoleobjectframe#addoleobjectframe)(float, float, float, float, IOleEmbeddedDataInfo) | Cria um novo quadro de objeto OLE e o adiciona ao final da coleção de formas. |
| [AddOleObjectFrame](../../aspose.slides/ishapecollection/addoleobjectframe#addoleobjectframe_1)(float, float, float, float, string, string) | Cria um novo quadro de objeto OLE e o adiciona ao final da coleção de formas. |
| [AddPictureFrame](../../aspose.slides/ishapecollection/addpictureframe)(ShapeType, float, float, float, float, IPPImage) | Cria um novo quadro de imagem contendo a imagem especificada e o adiciona ao final da coleção de formas. |
| [AddSectionZoomFrame](../../aspose.slides/ishapecollection/addsectionzoomframe#addsectionzoomframe)(float, float, float, float, ISection) | Cria um novo quadro de Section Zoom e o adiciona ao final da coleção de formas. |
| [AddSectionZoomFrame](../../aspose.slides/ishapecollection/addsectionzoomframe#addsectionzoomframe_1)(float, float, float, float, ISection, IPPImage) | Cria um novo quadro de Section Zoom com uma imagem predefinida e o adiciona ao final da coleção de formas. |
| [AddSmartArt](../../aspose.slides/ishapecollection/addsmartart)(float, float, float, float, SmartArtLayoutType) | Cria um diagrama SmartArt e o adiciona ao final da coleção de formas. |
| [AddSummaryZoomFrame](../../aspose.slides/ishapecollection/addsummaryzoomframe)(float, float, float, float) | Cria um novo quadro de Summary Zoom e o adiciona ao final da coleção de formas. |
| [AddTable](../../aspose.slides/ishapecollection/addtable)(float, float, double[], double[]) | Cria uma nova tabela e a adiciona ao final da coleção de formas. |
| [AddVideoFrame](../../aspose.slides/ishapecollection/addvideoframe#addvideoframe)(float, float, float, float, IVideo) | Cria um novo quadro de vídeo e o adiciona ao final da coleção de formas. |
| [AddVideoFrame](../../aspose.slides/ishapecollection/addvideoframe#addvideoframe_1)(float, float, float, float, string) | Cria um novo quadro de vídeo e o adiciona ao final da coleção de formas. |
| [AddZoomFrame](../../aspose.slides/ishapecollection/addzoomframe#addzoomframe)(float, float, float, float, ISlide) | Cria um novo quadro de Zoom e o adiciona ao final da coleção de formas. |
| [AddZoomFrame](../../aspose.slides/ishapecollection/addzoomframe#addzoomframe_1)(float, float, float, float, ISlide, IPPImage) | Cria um novo quadro de Zoom e o adiciona ao final da coleção de formas. |
| [Clear](../../aspose.slides/ishapecollection/clear)() | Remove todas as formas da coleção de formas. |
| [IndexOf](../../aspose.slides/ishapecollection/indexof)(IShape) | Retorna o índice baseado em zero da primeira ocorrência da forma especificada na coleção. |
| [InsertAudioFrameCD](../../aspose.slides/ishapecollection/insertaudioframecd)(int, float, float, float, float) | Cria um novo quadro de áudio vinculado a uma faixa de CD e o insere na coleção de formas no índice especificado. |
| [InsertAudioFrameEmbedded](../../aspose.slides/ishapecollection/insertaudioframeembedded#insertaudioframeembedded)(int, float, float, float, float, IAudio) | Cria um novo quadro de áudio e o insere na coleção de formas no índice especificado usando um objeto de áudio existente da lista Presentation.Audios. |
| [InsertAudioFrameEmbedded](../../aspose.slides/ishapecollection/insertaudioframeembedded#insertaudioframeembedded_1)(int, float, float, float, float, Stream) | Cria um novo quadro de áudio com um arquivo WAV incorporado e o insere na coleção de formas no índice especificado. O áudio incorporado é adicionado à coleção Presentation.Audios. |
| [InsertAudioFrameLinked](../../aspose.slides/ishapecollection/insertaudioframelinked)(int, float, float, float, float, string) | Cria um novo quadro de áudio vinculado a um arquivo de áudio externo e o insere na coleção de formas no índice especificado. |
| [InsertAutoShape](../../aspose.slides/ishapecollection/insertautoshape#insertautoshape)(int, ShapeType, float, float, float, float) | Cria uma nova forma automática e a insere na coleção de formas no índice especificado, aplicando a formatação padrão do modelo. |
| [InsertAutoShape](../../aspose.slides/ishapecollection/insertautoshape#insertautoshape_1)(int, ShapeType, float, float, float, float, bool) | Cria uma nova forma automática e a insere na coleção de formas no índice especificado, opcionalmente inicializando-a com o estilo padrão do modelo. |
| [InsertChart](../../aspose.slides/ishapecollection/insertchart#insertchart)(ChartType, float, float, float, float, int) | Cria um novo gráfico, inicializa-o com dados e configurações de série de exemplo, e o insere na coleção de formas no índice especificado. |
| [InsertChart](../../aspose.slides/ishapecollection/insertchart#insertchart_1)(ChartType, float, float, float, float, int, bool) | Cria um novo gráfico, inicializa-o com dados e configurações de série de exemplo, e o insere na coleção de formas no índice especificado. |
| [InsertClone](../../aspose.slides/ishapecollection/insertclone#insertclone)(int, IShape) | Cria uma cópia da forma especificada e a insere na coleção de formas no índice especificado. A forma clonada mantém a posição e o tamanho originais. |
| [InsertClone](../../aspose.slides/ishapecollection/insertclone#insertclone_1)(int, IShape, float, float) | Cria uma cópia da forma especificada e a insere na coleção de formas no índice especificado. A nova forma mantém a largura e a altura da *sourceShape*. |
| [InsertClone](../../aspose.slides/ishapecollection/insertclone#insertclone_2)(int, IShape, float, float, float, float) | Cria uma cópia da forma especificada e a insere na coleção de formas no índice especificado. |
| [InsertConnector](../../aspose.slides/ishapecollection/insertconnector#insertconnector)(int, ShapeType, float, float, float, float) | Cria uma nova forma de conector e a insere na coleção de formas no índice especificado, aplicando o estilo padrão do modelo. |
| [InsertConnector](../../aspose.slides/ishapecollection/insertconnector#insertconnector_1)(int, ShapeType, float, float, float, float, bool) | Cria uma nova forma de conector e a insere na coleção de formas no índice especificado, opcionalmente aplicando o estilo padrão do modelo. |
| [InsertGroupShape](../../aspose.slides/ishapecollection/insertgroupshape)(int) | Cria uma nova forma de grupo vazia e a insere na coleção de formas no índice especificado. O quadro do grupo será ajustado automaticamente para acomodar quaisquer formas adicionadas. |
| [InsertOleObjectFrame](../../aspose.slides/ishapecollection/insertoleobjectframe#insertoleobjectframe)(int, float, float, float, float, IOleEmbeddedDataInfo) | Cria um novo quadro de objeto OLE e o insere na coleção de formas no índice especificado. |
| [InsertOleObjectFrame](../../aspose.slides/ishapecollection/insertoleobjectframe#insertoleobjectframe_1)(int, float, float, float, float, string, string) | Cria um novo quadro de objeto OLE e o insere na coleção de formas no índice especificado. |
| [InsertPictureFrame](../../aspose.slides/ishapecollection/insertpictureframe)(int, ShapeType, float, float, float, float, IPPImage) | Cria um novo quadro de imagem contendo a imagem especificada e o insere na coleção de formas no índice especificado. |
| [InsertSectionZoomFrame](../../aspose.slides/ishapecollection/insertsectionzoomframe#insertsectionzoomframe)(int, float, float, float, float, ISection) | Cria um novo quadro de Section Zoom e o insere na coleção de formas no índice especificado. |
| [InsertSectionZoomFrame](../../aspose.slides/ishapecollection/insertsectionzoomframe#insertsectionzoomframe_1)(int, float, float, float, float, ISection, IPPImage) | Cria um novo quadro de Section Zoom com uma imagem predefinida e o insere na coleção de formas no índice especificado. |
| [InsertSummaryZoomFrame](../../aspose.slides/ishapecollection/insertsummaryzoomframe)(int, float, float, float, float) | Cria um novo quadro de Summary Zoom e o insere na coleção de formas no índice especificado. |
| [InsertTable](../../aspose.slides/ishapecollection/inserttable)(int, float, float, double[], double[]) | Cria uma nova tabela e a insere na coleção de formas no índice especificado. |
| [InsertVideoFrame](../../aspose.slides/ishapecollection/insertvideoframe)(int, float, float, float, float, string) | Cria um novo quadro de vídeo e o insere na coleção de formas no índice especificado. |
| [InsertZoomFrame](../../aspose.slides/ishapecollection/insertzoomframe#insertzoomframe)(int, float, float, float, float, ISlide) | Cria um novo quadro de Zoom e o insere na coleção de formas no índice especificado. |
| [InsertZoomFrame](../../aspose.slides/ishapecollection/insertzoomframe#insertzoomframe_1)(int, float, float, float, float, ISlide, IPPImage) | Cria um novo quadro de Zoom com uma imagem predefinida e o insere na coleção de formas no índice especificado. |
| [Remove](../../aspose.slides/ishapecollection/remove)(IShape) | Remove a primeira ocorrência da forma especificada da coleção de formas. |
| [RemoveAt](../../aspose.slides/ishapecollection/removeat)(int) | Remove a forma no índice especificado da coleção de formas. |
| [Reorder](../../aspose.slides/ishapecollection/reorder#reorder)(int, IShape) | Move a forma especificada para uma nova posição dentro da coleção de formas. |
| [Reorder](../../aspose.slides/ishapecollection/reorder#reorder_1)(int, params IShape[]) | Move as formas especificadas dentro da coleção de formas, posicionando-as a partir do índice fornecido. |
| [ToArray](../../aspose.slides/ishapecollection/toarray#toarray)() | Cria e devolve um array que contém todas as formas. |
| [ToArray](../../aspose.slides/ishapecollection/toarray#toarray_1)(int, int) | Cria e devolve um array que contém todas as formas no intervalo especificado. |

### Veja Também

* interface [IGenericCollection&lt;T&gt;](../igenericcollection-1)
* interface [IShape](../ishape)
* namespace [Aspose.Slides](../../aspose.slides)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->