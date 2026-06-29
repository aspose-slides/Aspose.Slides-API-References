---
title: ShapeCollection
second_title: Referência da API Aspose.Sildes para .NET
description: Representa uma coleção de formas.
type: docs
weight: 9840
url: /pt/aspose.slides/shapecollection/
---
## ShapeCollection classe

Representa uma coleção de formas.

```csharp
public sealed class ShapeCollection : DomObject<GroupShape>, IShapeCollection
```

## Propriedades

| Nome | Descrição |
| --- | --- |
| [Count](../../aspose.slides/shapecollection/count) { get; } | Obtém o número de elementos realmente contidos na coleção. Somente leitura Int32. |
| [IsSynchronized](../../aspose.slides/shapecollection/issynchronized) { get; } | Retorna um valor que indica se o acesso à coleção é sincronizado (thread-safe). Somente leitura Boolean. |
| [Item](../../aspose.slides/shapecollection/item) { get; } | Obtém o elemento no índice especificado. Somente leitura [`IShape`](../ishape). |
| [ParentGroup](../../aspose.slides/shapecollection/parentgroup) { get; } | Obtém o objeto de forma de grupo pai para a coleção de formas. Somente leitura [`IGroupShape`](../igroupshape). |
| [SyncRoot](../../aspose.slides/shapecollection/syncroot) { get; } | Retorna a raiz de sincronização. Somente leitura Object. |

## Métodos

| Nome | Descrição |
| --- | --- |
| [AddAudioFrameCD](../../aspose.slides/shapecollection/addaudioframecd)(float, float, float, float) | Cria um novo quadro de áudio vinculado a uma faixa de CD e o adiciona ao final da coleção de formas. |
| [AddAudioFrameEmbedded](../../aspose.slides/shapecollection/addaudioframeembedded#addaudioframeembedded)(float, float, float, float, IAudio) | Cria um novo quadro de áudio e o adiciona ao final da coleção de formas usando um objeto de áudio existente da lista Presentation.Audios. |
| [AddAudioFrameEmbedded](../../aspose.slides/shapecollection/addaudioframeembedded#addaudioframeembedded_1)(float, float, float, float, Stream) | Cria um novo quadro de áudio com um arquivo WAV incorporado e o adiciona ao final da coleção de formas. O áudio incorporado é adicionado à coleção Presentation.Audios. |
| [AddAudioFrameLinked](../../aspose.slides/shapecollection/addaudioframelinked)(float, float, float, float, string) | Cria um novo quadro de áudio vinculado a um arquivo de áudio externo e o adiciona ao final da coleção de formas. |
| [AddAutoShape](../../aspose.slides/shapecollection/addautoshape#addautoshape)(ShapeType, float, float, float, float) | Cria uma nova forma automática com formatação padrão e a adiciona ao final da coleção de formas. |
| [AddAutoShape](../../aspose.slides/shapecollection/addautoshape#addautoshape_1)(ShapeType, float, float, float, float, bool) | Cria uma nova forma automática e a adiciona ao final da coleção de formas, opcionalmente inicializando-a com a formatação padrão do modelo. |
| [AddChart](../../aspose.slides/shapecollection/addchart#addchart)(ChartType, float, float, float, float) | Cria um novo gráfico, inicializa-o com dados e configurações de séries de exemplo, e o adiciona ao final da coleção de formas. |
| [AddChart](../../aspose.slides/shapecollection/addchart#addchart_1)(ChartType, float, float, float, float, bool) | Cria um novo gráfico, inicializa-o com dados e configurações de séries de exemplo, e o adiciona ao final da coleção de formas. |
| [AddClone](../../aspose.slides/shapecollection/addclone#addclone)(IShape) | Cria uma cópia da forma especificada e a adiciona ao final da coleção de formas. A forma clonada mantém a posição e o tamanho original. |
| [AddClone](../../aspose.slides/shapecollection/addclone#addclone_1)(IShape, float, float) | Cria uma cópia da forma especificada e a adiciona ao final da coleção de formas. A nova forma mantém a largura e a altura da *sourceShape*. |
| [AddClone](../../aspose.slides/shapecollection/addclone#addclone_2)(IShape, float, float, float, float) | Cria uma cópia da forma especificada e a adiciona ao final da coleção de formas. |
| [AddConnector](../../aspose.slides/shapecollection/addconnector#addconnector)(ShapeType, float, float, float, float) | Cria uma nova forma de conector com estilo padrão do modelo e a adiciona ao final da coleção de formas. |
| [AddConnector](../../aspose.slides/shapecollection/addconnector#addconnector_1)(ShapeType, float, float, float, float, bool) | Cria uma nova forma de conector e a adiciona ao final da coleção de formas, opcionalmente aplicando o estilo padrão do modelo. |
| [AddGroupShape](../../aspose.slides/shapecollection/addgroupshape#addgroupshape)() | Cria uma nova forma de grupo vazia e a adiciona ao final da coleção de formas. A moldura do grupo será ajustada automaticamente para acomodar quaisquer formas adicionadas a ele. |
| [AddGroupShape](../../aspose.slides/shapecollection/addgroupshape#addgroupshape_1)(ISvgImage, float, float, float, float) | Cria uma nova forma de grupo, converte a imagem SVG especificada em formas individuais e adiciona o grupo resultante ao final da coleção de formas. |
| [AddMathShape](../../aspose.slides/shapecollection/addmathshape)(float, float, float, float) | Cria uma nova forma automática retangular para hospedar conteúdo matemático e a adiciona ao final da coleção de formas. |
| [AddOleObjectFrame](../../aspose.slides/shapecollection/addoleobjectframe#addoleobjectframe)(float, float, float, float, IOleEmbeddedDataInfo) | Cria um novo quadro de objeto OLE e o adiciona ao final da coleção de formas. |
| [AddOleObjectFrame](../../aspose.slides/shapecollection/addoleobjectframe#addoleobjectframe_1)(float, float, float, float, string, string) | Cria um novo quadro de objeto OLE e o adiciona ao final da coleção de formas. |
| [AddPictureFrame](../../aspose.slides/shapecollection/addpictureframe)(ShapeType, float, float, float, float, IPPImage) | Cria um novo quadro de imagem contendo a imagem especificada e o adiciona ao final da coleção de formas. |
| [AddSectionZoomFrame](../../aspose.slides/shapecollection/addsectionzoomframe#addsectionzoomframe)(float, float, float, float, ISection) | Cria um novo quadro de Zoom de Seção e o adiciona ao final da coleção de formas. |
| [AddSectionZoomFrame](../../aspose.slides/shapecollection/addsectionzoomframe#addsectionzoomframe_1)(float, float, float, float, ISection, IPPImage) | Cria um novo quadro de Zoom de Seção com uma imagem predefinida e o adiciona ao final da coleção de formas. |
| [AddSmartArt](../../aspose.slides/shapecollection/addsmartart)(float, float, float, float, SmartArtLayoutType) | Cria um diagrama SmartArt e o adiciona ao final da coleção de formas. |
| [AddSummaryZoomFrame](../../aspose.slides/shapecollection/addsummaryzoomframe)(float, float, float, float) | Cria um novo quadro de Zoom de Resumo e o adiciona ao final da coleção de formas. |
| [AddTable](../../aspose.slides/shapecollection/addtable)(float, float, double[], double[]) | Cria uma nova tabela e a adiciona ao final da coleção de formas. |
| [AddVideoFrame](../../aspose.slides/shapecollection/addvideoframe#addvideoframe)(float, float, float, float, IVideo) | Cria um novo quadro de vídeo e o adiciona ao final da coleção de formas. |
| [AddVideoFrame](../../aspose.slides/shapecollection/addvideoframe#addvideoframe_1)(float, float, float, float, string) | Cria um novo quadro de vídeo e o adiciona ao final da coleção de formas. |
| [AddZoomFrame](../../aspose.slides/shapecollection/addzoomframe#addzoomframe)(float, float, float, float, ISlide) | Cria um novo quadro de Zoom e o adiciona ao final da coleção de formas. |
| [AddZoomFrame](../../aspose.slides/shapecollection/addzoomframe#addzoomframe_1)(float, float, float, float, ISlide, IPPImage) | Cria um novo quadro de Zoom e o adiciona ao final da coleção de formas. |
| [Clear](../../aspose.slides/shapecollection/clear)() | Remove todas as formas da coleção de formas. |
| [CopyTo](../../aspose.slides/shapecollection/copyto)(Array, int) | Copia todos os elementos da coleção para o array especificado. |
| [GetEnumerator](../../aspose.slides/shapecollection/getenumerator)() | Retorna um enumerador que itera sobre a coleção. |
| [IndexOf](../../aspose.slides/shapecollection/indexof)(IShape) | Retorna o índice baseado em zero da primeira ocorrência da forma especificada na coleção. |
| [InsertAudioFrameCD](../../aspose.slides/shapecollection/insertaudioframecd)(int, float, float, float, float) | Cria um novo quadro de áudio vinculado a uma faixa de CD e o insere na coleção de formas no índice especificado. |
| [InsertAudioFrameEmbedded](../../aspose.slides/shapecollection/insertaudioframeembedded#insertaudioframeembedded)(int, float, float, float, float, IAudio) | Cria um novo quadro de áudio e o insere na coleção de formas no índice especificado usando um objeto de áudio existente da lista Presentation.Audios. |
| [InsertAudioFrameEmbedded](../../aspose.slides/shapecollection/insertaudioframeembedded#insertaudioframeembedded_1)(int, float, float, float, float, Stream) | Cria um novo quadro de áudio com um arquivo WAV incorporado e o insere na coleção de formas no índice especificado. O áudio incorporado é adicionado à coleção Presentation.Audios. |
| [InsertAudioFrameLinked](../../aspose.slides/shapecollection/insertaudioframelinked)(int, float, float, float, float, string) | Cria um novo quadro de áudio vinculado a um arquivo de áudio externo e o insere na coleção de formas no índice especificado. |
| [InsertAutoShape](../../aspose.slides/shapecollection/insertautoshape#insertautoshape)(int, ShapeType, float, float, float, float) | Cria uma nova forma automática e a insere na coleção de formas no índice especificado, aplicando a formatação padrão do modelo. |
| [InsertAutoShape](../../aspose.slides/shapecollection/insertautoshape#insertautoshape_1)(int, ShapeType, float, float, float, float, bool) | Cria uma nova forma automática e a insere na coleção de formas no índice especificado, opcionalmente inicializando-a com o estilo padrão do modelo. |
| [InsertChart](../../aspose.slides/shapecollection/insertchart#insertchart)(ChartType, float, float, float, float, int) | Cria um novo gráfico, inicializa-o com dados e configurações de séries de exemplo, e o insere na coleção de formas no índice especificado. |
| [InsertChart](../../aspose.slides/shapecollection/insertchart#insertchart_1)(ChartType, float, float, float, float, int, bool) | Cria um novo gráfico, inicializa-o com dados e configurações de séries de exemplo, e o insere na coleção de formas no índice especificado. |
| [InsertClone](../../aspose.slides/shapecollection/insertclone#insertclone)(int, IShape) | Cria uma cópia da forma especificada e a insere na coleção de formas no índice especificado. A forma clonada mantém a posição e o tamanho original. |
| [InsertClone](../../aspose.slides/shapecollection/insertclone#insertclone_1)(int, IShape, float, float) | Cria uma cópia da forma especificada e a insere na coleção de formas no índice especificado. A nova forma mantém a largura e a altura da *sourceShape*. |
| [InsertClone](../../aspose.slides/shapecollection/insertclone#insertclone_2)(int, IShape, float, float, float, float) | Cria uma cópia da forma especificada e a insere na coleção de formas no índice especificado. |
| [InsertConnector](../../aspose.slides/shapecollection/insertconnector#insertconnector)(int, ShapeType, float, float, float, float) | Cria uma nova forma de conector e a insere na coleção de formas no índice especificado, aplicando o estilo padrão do modelo. |
| [InsertConnector](../../aspose.slides/shapecollection/insertconnector#insertconnector_1)(int, ShapeType, float, float, float, float, bool) | Cria uma nova forma de conector e a insere na coleção de formas no índice especificado, opcionalmente aplicando o estilo padrão do modelo. |
| [InsertGroupShape](../../aspose.slides/shapecollection/insertgroupshape)(int) | Cria uma nova forma de grupo vazia e a insere na coleção de formas no índice especificado. A moldura do grupo será ajustada automaticamente para acomodar quaisquer formas adicionadas a ele. |
| [InsertOleObjectFrame](../../aspose.slides/shapecollection/insertoleobjectframe#insertoleobjectframe)(int, float, float, float, float, IOleEmbeddedDataInfo) | Cria um novo quadro de objeto OLE e o insere na coleção de formas no índice especificado. |
| [InsertOleObjectFrame](../../aspose.slides/shapecollection/insertoleobjectframe#insertoleobjectframe_1)(int, float, float, float, float, string, string) | Cria um novo quadro de objeto OLE e o insere na coleção de formas no índice especificado. |
| [InsertPictureFrame](../../aspose.slides/shapecollection/insertpictureframe)(int, ShapeType, float, float, float, float, IPPImage) | Cria um novo quadro de imagem contendo a imagem especificada e o insere na coleção de formas no índice especificado. |
| [InsertSectionZoomFrame](../../aspose.slides/shapecollection/insertsectionzoomframe#insertsectionzoomframe)(int, float, float, float, float, ISection) | Cria um novo quadro de Zoom de Seção e o insere na coleção de formas no índice especificado. |
| [InsertSectionZoomFrame](../../aspose.slides/shapecollection/insertsectionzoomframe#insertsectionzoomframe_1)(int, float, float, float, float, ISection, IPPImage) | Cria um novo quadro de Zoom de Seção com uma imagem predefinida e o insere na coleção de formas no índice especificado. |
| [InsertSummaryZoomFrame](../../aspose.slides/shapecollection/insertsummaryzoomframe)(int, float, float, float, float) | Cria um novo quadro de Zoom de Resumo e o insere na coleção de formas no índice especificado. |
| [InsertTable](../../aspose.slides/shapecollection/inserttable)(int, float, float, double[], double[]) | Cria uma nova tabela e a insere na coleção de formas no índice especificado. |
| [InsertVideoFrame](../../aspose.slides/shapecollection/insertvideoframe)(int, float, float, float, float, string) | Cria um novo quadro de vídeo e o insere na coleção de formas no índice especificado. |
| [InsertZoomFrame](../../aspose.slides/shapecollection/insertzoomframe#insertzoomframe)(int, float, float, float, float, ISlide) | Cria um novo quadro de Zoom e o insere na coleção de formas no índice especificado. |
| [InsertZoomFrame](../../aspose.slides/shapecollection/insertzoomframe#insertzoomframe_1)(int, float, float, float, float, ISlide, IPPImage) | Cria um novo quadro de Zoom com uma imagem predefinida e o insere na coleção de formas no índice especificado. |
| [Remove](../../aspose.slides/shapecollection/remove)(IShape) | Remove a primeira ocorrência da forma especificada da coleção de formas. |
| [RemoveAt](../../aspose.slides/shapecollection/removeat)(int) | Remove a forma no índice especificado da coleção de formas. |
| [Reorder](../../aspose.slides/shapecollection/reorder#reorder)(int, IShape) | Move a forma especificada para uma nova posição dentro da coleção de formas. |
| [Reorder](../../aspose.slides/shapecollection/reorder#reorder_1)(int, params IShape[]) | Move as formas especificadas dentro da coleção de formas, posicionando-as a partir do índice fornecido. |
| [ToArray](../../aspose.slides/shapecollection/toarray#toarray)() | Cria e retorna um array que contém todas as formas. |
| [ToArray](../../aspose.slides/shapecollection/toarray#toarray_1)(int, int) | Cria e retorna um array que contém todas as formas no intervalo especificado. |

### Veja Também

* classe [DomObject&lt;TParent&gt;](../domobject-1)
* classe [GroupShape](../groupshape)
* interface [IShapeCollection](../ishapecollection)
* namespace [Aspose.Slides](../../aspose.slides)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->