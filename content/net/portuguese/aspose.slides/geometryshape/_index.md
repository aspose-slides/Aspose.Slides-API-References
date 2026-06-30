---
title: GeometryShape
second_title: Referência da API Aspose.Slides para .NET
description: Representa a classe base para todas as formas geométricas.
type: docs
weight: 4950
url: /pt/aspose.slides/geometryshape/
---
## classe GeometryShape

Representa a classe base para todas as formas geométricas.

```csharp
public abstract class GeometryShape : Shape, IGeometryShape
```

## Propriedades

| Nome | Descrição |
| --- | --- |
| [Adjustments](../../aspose.slides/geometryshape/adjustments) { get; } | Retorna uma coleção dos valores de ajuste da forma. Somente leitura [`IAdjustValueCollection`](../iadjustvaluecollection). |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | Retorna ou define o texto alternativo associado à forma. Leitura/gravação String. |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | Retorna ou define o título do texto alternativo associado à forma. Leitura/gravação String. |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | A propriedade especifica como a forma será renderizada no modo de exibição em preto e branco. Leitura/gravação [`BlackWhiteMode`](../blackwhitemode). |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | Retorna o número de pontos de conexão na forma. Somente leitura Int32. |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | Retorna os dados personalizados da forma. Somente leitura [`ICustomData`](../icustomdata). |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | Retorna o objeto EffectFormat que contém efeitos de pixel aplicados a uma forma. Observação: pode retornar null para certos tipos de formas que não possuem propriedades de efeito. Somente leitura [`IEffectFormat`](../ieffectformat). |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | Retorna o objeto FillFormat que contém propriedades de preenchimento para uma forma. Observação: pode retornar null para certos tipos de formas que não possuem propriedades de preenchimento. Somente leitura [`IFillFormat`](../ifillformat). |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | Retorna ou define as propriedades da moldura da forma. Leitura/gravação [`IShapeFrame`](../ishapeframe). |
| [Height](../../aspose.slides/shape/height) { get; set; } | Obtém ou define a altura da forma, medida em pontos. Leitura/gravação Single. |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | Determina se a forma está oculta. Leitura/gravação Boolean. |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | Retorna ou define o hiperlink definido para clique do mouse. Leitura/gravação [`IHyperlink`](../ihyperlink). |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | Retorna o gerenciador de hiperlinks. Somente leitura [`IHyperlinkManager`](../ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | Retorna ou define o hiperlink definido para mouse over. Leitura/gravação [`IHyperlink`](../ihyperlink). |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | Obtém ou define a opção “Marcar como decorativo”. Leitura/gravação Boolean. |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | Determina se a forma está agrupada. Somente leitura Boolean. |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | Determina se a forma é TextHolder_PPT. Somente leitura Boolean. |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | Retorna o objeto LineFormat que contém propriedades de formatação de linha para uma forma. Observação: pode retornar null para certos tipos de formas que não possuem propriedades de linha. Somente leitura [`ILineFormat`](../ilineformat). |
| [Name](../../aspose.slides/shape/name) { get; set; } | Retorna ou define o nome de uma forma. Não pode ser nulo. Use uma string vazia se necessário. Leitura/gravação String. |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | Retorna um identificador exclusivo no escopo do slide que permanece constante durante a vida da forma e permite que o PowerPoint ou código interop faça referência confiável à forma a partir de qualquer ponto do documento. Somente leitura UInt32. Veja também [`UniqueId`](../shape/uniqueid). |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | Retorna o objeto GroupShape pai se a forma estiver agrupada. Caso contrário, retorna null. Somente leitura [`IGroupShape`](../igroupshape). |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | Retorna o placeholder da forma. Retorna null se a forma não possuir placeholder. Somente leitura [`IPlaceholder`](../iplaceholder). |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | Retorna a apresentação pai de um slide. Somente leitura [`IPresentation`](../ipresentation). |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | Retorna ou define as propriedades brutas da moldura da forma. Leitura/gravação [`IShapeFrame`](../ishapeframe). |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | Retorna ou define o número de graus que a forma especificada está girada em torno do eixo z. Um valor positivo indica rotação no sentido horário; um valor negativo indica rotação no sentido anti-horário. Leitura/gravação Single. |
| [ShapeLock](../../aspose.slides/shape/shapelock) { get; } | Retorna os bloqueios da forma. Somente leitura [`IBaseShapeLock`](../ibaseshapelock). |
| [ShapeStyle](../../aspose.slides/geometryshape/shapestyle) { get; } | Retorna o objeto de estilo da forma. Somente leitura [`IShapeStyle`](../ishapestyle). |
| virtual [ShapeType](../../aspose.slides/geometryshape/shapetype) { get; set; } | Retorna ou define o tipo de predefinição de geometria. Observação: ao alterar o valor, todos os valores de ajuste serão redefinidos para seus valores padrão. Leitura/gravação [`ShapeType`](../shapetype). |
| [Slide](../../aspose.slides/shape/slide) { get; } | Retorna o slide pai da forma. Somente leitura [`IBaseSlide`](../ibaseslide). |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | Retorna o objeto ThreeDFormat que contém propriedades de efeito 3D para uma forma. Observação: pode retornar null para certos tipos de formas que não possuem propriedades 3D. Somente leitura [`IThreeDFormat`](../ithreedformat). |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | Retorna um identificador interno no escopo da apresentação destinado ao uso por complementos ou outro código. Como esse valor pode ser reatribuído pelo usuário ou programaticamente, não deve ser tratado como uma chave única persistente. Somente leitura UInt32. Veja também [`OfficeInteropShapeId`](../shape/officeinteropshapeid). |
| [Width](../../aspose.slides/shape/width) { get; set; } | Obtém ou define a largura da forma, medida em pontos. Leitura/gravação Single. |
| [X](../../aspose.slides/shape/x) { get; set; } | Obtém ou define a coordenada x do canto superior esquerdo da forma, medida em pontos. Leitura/gravação Single. |
| [Y](../../aspose.slides/shape/y) { get; set; } | Obtém ou define a coordenada y do canto superior esquerdo da forma, medida em pontos. Leitura/gravação Single. |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | Retorna a posição de uma forma na ordem z. Shapes[0] retorna a forma mais ao fundo da ordem z, e Shapes[Shapes.Count - 1] retorna a forma mais à frente da ordem z. Somente leitura Int32. |

## Métodos

| Nome | Descrição |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | Adiciona um novo placeholder se não houver e define as propriedades do placeholder para um especificado. |
| [CreateShapeElements](../../aspose.slides/geometryshape/createshapeelements)() | Cria e retorna um array dos elementos da forma. |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | Retorna uma forma placeholder básica (forma do layout e/ou do slide mestre da qual a forma atual é herdada). Retorna null se a forma atual não for herdada. |
| [GetGeometryPaths](../../aspose.slides/geometryshape/getgeometrypaths)() | Retorna a cópia do caminho da forma geométrica. As coordenadas são relativas ao canto superior esquerdo da forma. |
| [GetImage](../../aspose.slides/shape/getimage)() | Retorna a miniatura da forma. O tipo ShapeThumbnailBounds.Shape é usado por padrão. |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | Retorna a miniatura da forma. |
| [GetVisualBounds](../../aspose.slides/shape/getvisualbounds)() | Obtém os limites visuais da forma calculados a partir do seu conteúdo renderizado. |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | Define que esta forma não é um placeholder. |
| [SetGeometryPath](../../aspose.slides/geometryshape/setgeometrypath)(IGeometryPath) | Atualiza a geometria da forma a partir do objeto [`IGeometryPath`](../igeometrypath). As coordenadas devem ser relativas ao canto superior esquerdo da forma. Altera o tipo da forma ([`ShapeType`](./shapetype)) para Custom. |
| [SetGeometryPaths](../../aspose.slides/geometryshape/setgeometrypaths)(IGeometryPath[]) | Atualiza a geometria da forma a partir de um array de [`IGeometryPath`](../igeometrypath). As coordenadas devem ser relativas ao canto superior esquerdo da forma. Altera o tipo da forma ([`ShapeType`](./shapetype)) para Custom. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | Salva o conteúdo da Shape como arquivo SVG. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | Salva o conteúdo da Shape como arquivo SVG. |

### Veja Também

* class [Shape](../shape)
* interface [IGeometryShape](../igeometryshape)
* namespace [Aspose.Slides](../../aspose.slides)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->