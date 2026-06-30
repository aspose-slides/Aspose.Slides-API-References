---
title: PictureFrame
second_title: Referência da API Aspose.Sildes para .NET
description: Representa um quadro com uma imagem dentro.
type: docs
weight: 9390
url: /pt/aspose.slides/pictureframe/
---
## PictureFrame classe

Representa um quadro com uma imagem dentro.

```csharp
public class PictureFrame : GeometryShape, IPictureFrame
```

## Propriedades

| Name | Description |
| --- | --- |
| [Adjustments](../../aspose.slides/geometryshape/adjustments) { get; } | Retorna uma coleção de valores de ajuste da forma. Somente leitura [`IAdjustValueCollection`](../iadjustvaluecollection). |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | Retorna ou define o texto alternativo associado a uma forma. Leitura/Gravação String. |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | Retorna ou define o título do texto alternativo associado a uma forma. Leitura/Gravação String. |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | A propriedade especifica como uma forma será renderizada no modo de exibição em preto e branco. Leitura/Gravação [`BlackWhiteMode`](../blackwhitemode). |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | Retorna o número de pontos de conexão na forma. Somente leitura Int32. |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | Retorna os dados personalizados da forma. Somente leitura [`ICustomData`](../icustomdata). |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | Retorna o objeto EffectFormat que contém efeitos de pixel aplicados a uma forma. Observação: pode retornar nulo para certos tipos de formas que não possuem propriedades de efeito. Somente leitura [`IEffectFormat`](../ieffectformat). |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | Retorna o objeto FillFormat que contém propriedades de formatação de preenchimento para uma forma. Observação: pode retornar nulo para certos tipos de formas que não possuem propriedades de preenchimento. Somente leitura [`IFillFormat`](../ifillformat). |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | Retorna ou define as propriedades da moldura da forma. Leitura/Gravação [`IShapeFrame`](../ishapeframe). |
| [Height](../../aspose.slides/shape/height) { get; set; } | Obtém ou define a altura da forma, medida em pontos. Leitura/Gravação Single. |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | Determina se a forma está oculta. Leitura/Gravação Boolean. |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | Retorna ou define o hyperlink definido para clique do mouse. Leitura/Gravação [`IHyperlink`](../ihyperlink). |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | Retorna o gerenciador de hyperlinks. Somente leitura [`IHyperlinkManager`](../ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | Retorna ou define o hyperlink definido para mouse sobre. Leitura/Gravação [`IHyperlink`](../ihyperlink). |
| [IsCameo](../../aspose.slides/pictureframe/iscameo) { get; } | Determina se o PictureFrame é um objeto Cameo ou não. Somente leitura Boolean. |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | Obtém ou define a opção 'Marcar como decorativo'. Leitura/Gravação Boolean. |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | Determina se a forma está agrupada. Somente leitura Boolean. |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | Determina se a forma é TextHolder_PPT. Somente leitura Boolean. |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | Retorna o objeto LineFormat que contém propriedades de formatação de linha para uma forma. Observação: pode retornar nulo para certos tipos de formas que não possuem propriedades de linha. Somente leitura [`ILineFormat`](../ilineformat). |
| [Name](../../aspose.slides/shape/name) { get; set; } | Retorna ou define o nome de uma forma. Deve ser não nulo. Use string vazia se necessário. Leitura/Gravação String. |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | Retorna um identificador único limitado ao slide que permanece constante durante a vida útil da forma e permite que o PowerPoint ou código interop referenciem a forma de forma confiável de qualquer lugar no documento. Somente leitura UInt32. Veja também [`UniqueId`](../shape/uniqueid). |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | Retorna o objeto GroupShape pai se a forma estiver agrupada. Caso contrário, retorna nulo. Somente leitura [`IGroupShape`](../igroupshape). |
| [PictureFormat](../../aspose.slides/pictureframe/pictureformat) { get; } | Retorna o objeto PictureFillFormat para uma moldura de imagem. Somente leitura [`IPictureFillFormat`](../ipicturefillformat). |
| [PictureFrameLock](../../aspose.slides/pictureframe/pictureframelock) { get; } | Retorna os bloqueios da forma. Somente leitura [`IPictureFrameLock`](../ipictureframelock). |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | Retorna o placeholder para uma forma. Retorna nulo se a forma não tem placeholder. Somente leitura [`IPlaceholder`](../iplaceholder). |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | Retorna a apresentação pai de um slide. Somente leitura [`IPresentation`](../ipresentation). |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | Retorna ou define as propriedades brutas da moldura da forma. Leitura/Gravação [`IShapeFrame`](../ishapeframe). |
| [RelativeScaleHeight](../../aspose.slides/pictureframe/relativescaleheight) { get; set; } | Retorna ou define a escala de altura (relativa ao tamanho original da imagem) da moldura da imagem. Valor 1,0 corresponde a 100%. Leitura/Gravação Single. |
| [RelativeScaleWidth](../../aspose.slides/pictureframe/relativescalewidth) { get; set; } | Retorna ou define a escala de largura (relativa ao tamanho original da imagem) da moldura da imagem. Valor 1,0 corresponde a 100%. Leitura/Gravação Single. |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | Retorna ou define o número de graus que a forma especificada é girada ao redor do eixo z. Um valor positivo indica rotação no sentido horário; um valor negativo indica rotação no sentido anti-horário. Leitura/Gravação Single. |
| [ShapeLock](../../aspose.slides/pictureframe/shapelock) { get; } | Retorna os bloqueios da forma. Somente leitura [`IPictureFrameLock`](../ipictureframelock). (2 propriedades) |
| [ShapeStyle](../../aspose.slides/geometryshape/shapestyle) { get; } | Retorna o objeto de estilo da forma. Somente leitura [`IShapeStyle`](../ishapestyle). |
| override [ShapeType](../../aspose.slides/pictureframe/shapetype) { get; set; } | Retorna ou define o tipo AutoShape para um PictureFrame. Existem todos os itens permitidos do conjunto [`ShapeType`](../shapetype), exceto todos os tipos de linhas: |
| [Slide](../../aspose.slides/shape/slide) { get; } | Retorna o slide pai de uma forma. Somente leitura [`IBaseSlide`](../ibaseslide). |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | Retorna o objeto ThreeDFormat que contém propriedades de efeito 3D para uma forma. Observação: pode retornar nulo para certos tipos de formas que não possuem propriedades 3D. Somente leitura [`IThreeDFormat`](../ithreedformat). |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | Retorna um identificador interno, limitado à apresentação, destinado ao uso por complementos ou outro código. Como esse valor pode ser reatribuído pelo usuário ou programaticamente, não deve ser tratado como uma chave única persistente. Somente leitura UInt32. Veja também [`OfficeInteropShapeId`](../shape/officeinteropshapeid). |
| [Width](../../aspose.slides/shape/width) { get; set; } | Obtém ou define a largura da forma, medida em pontos. Leitura/Gravação Single. |
| [X](../../aspose.slides/shape/x) { get; set; } | Obtém ou define a coordenada x do canto superior esquerdo da forma, medida em pontos. Leitura/Gravação Single. |
| [Y](../../aspose.slides/shape/y) { get; set; } | Obtém ou define a coordenada y do canto superior esquerdo da forma, medida em pontos. Leitura/Gravação Single. |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | Retorna a posição de uma forma na ordem Z. Shapes[0] retorna a forma no fundo da ordem Z, e Shapes[Shapes.Count - 1] retorna a forma na frente da ordem Z. Somente leitura Int32. |

## Métodos

| Name | Description |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | Adiciona um novo placeholder se não houver e define as propriedades do placeholder para um especificado. |
| [CreateShapeElements](../../aspose.slides/geometryshape/createshapeelements)() | Cria e retorna um array dos elementos da forma. |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | Retorna uma forma placeholder básica (forma do layout e/ou slide mestre da qual a forma atual é herdada). Retorna nulo se a forma atual não for herdada. |
| [GetGeometryPaths](../../aspose.slides/geometryshape/getgeometrypaths)() | Retorna a cópia do caminho da forma geométrica. As coordenadas são relativas ao canto superior esquerdo da forma. |
| [GetImage](../../aspose.slides/shape/getimage)() | Retorna a miniatura da forma. O tipo ShapeThumbnailBounds.Shape é usado por padrão para os limites da miniatura da forma. |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | Retorna a miniatura da forma. |
| [GetVisualBounds](../../aspose.slides/shape/getvisualbounds)() | Obtém os limites visuais da forma calculados a partir do seu conteúdo renderizado. |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | Define que esta forma não é um placeholder. |
| [SetGeometryPath](../../aspose.slides/geometryshape/setgeometrypath)(IGeometryPath) | Atualiza a geometria da forma a partir do objeto [`IGeometryPath`](../igeometrypath). As coordenadas devem ser relativas ao canto superior esquerdo da forma. Altera o tipo da forma ([`ShapeType`](../geometryshape/shapetype)) para Custom. |
| [SetGeometryPaths](../../aspose.slides/geometryshape/setgeometrypaths)(IGeometryPath[]) | Atualiza a geometria da forma a partir de um array de [`IGeometryPath`](../igeometrypath). As coordenadas devem ser relativas ao canto superior esquerdo da forma. Altera o tipo da forma ([`ShapeType`](../geometryshape/shapetype)) para Custom. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | Salva o conteúdo da Shape como arquivo SVG. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | Salva o conteúdo da Shape como arquivo SVG. |

### Exemplos

Os exemplos a seguir mostram como alterar a miniatura do Audio Frame Thumbnail.

```csharp
[C#]
using (var presentation = new Presentation())
{
    var slide = presentation.Slides[0];
    // Adiciona um quadro de áudio ao slide com posição e tamanho especificados.
    var audioStream = new FileStream("sample2.mp3", FileMode.Open, FileAccess.Read);
    var audioFrame = slide.Shapes.AddAudioFrameEmbedded(150, 100, 50, 50, audioStream);
    audioStream.Dispose();
    // Adiciona uma imagem aos recursos da apresentação.
    var imageStream = File.OpenRead("eagle.jpeg");
    var audioImage = presentation.Images.AddImage(imageStream);
    imageStream.Dispose();
    // Define a imagem para o quadro de áudio.
    audioFrame.PictureFormat.Picture.Image = audioImage;
	//Salva a apresentação modificada no disco
    presentation.Save("example_out.pptx", SaveFormat.Pptx);
}
```

### Ver Também

* classe [GeometryShape](../geometryshape)
* interface [IPictureFrame](../ipictureframe)
* espaço de nomes [Aspose.Slides](../../aspose.slides)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->