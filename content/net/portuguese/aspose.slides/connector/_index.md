---
title: Connector
second_title: Referência da API Aspose.Sildes para .NET
description: Representa um conector.
type: docs
weight: 2650
url: /pt/aspose.slides/connector/
---
## Connector classe

Representa um conector.

```csharp
public class Connector : GeometryShape, IConnector
```

## Propriedades

| Nome | Descrição |
| --- | --- |
| [Adjustments](../../aspose.slides/geometryshape/adjustments) { get; } | Retorna uma coleção de valores de ajuste do shape. Somente leitura [`IAdjustValueCollection`](../iadjustvaluecollection). |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | Retorna ou define o texto alternativo associado a um shape. Leitura/gravação String. |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | Retorna ou define o título do texto alternativo associado a um shape. Leitura/gravação String. |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | Propriedade que especifica como um shape será renderizado no modo de exibição preto e branco. Leitura/gravação [`BlackWhiteMode`](../blackwhitemode). |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | Retorna o número de pontos de conexão no shape. Somente leitura Int32. |
| [ConnectorLock](../../aspose.slides/connector/connectorlock) { get; } | Retorna os bloqueios do conector. Somente leitura [`IConnectorLock`](../iconnectorlock). |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | Retorna os dados personalizados do shape. Somente leitura [`ICustomData`](../icustomdata). |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | Retorna o objeto EffectFormat que contém efeitos de pixel aplicados a um shape. Observação: pode retornar nulo para certos tipos de shapes que não possuem propriedades de efeito. Somente leitura [`IEffectFormat`](../ieffectformat). |
| [EndShapeConnectedTo](../../aspose.slides/connector/endshapeconnectedto) { get; set; } | Retorna ou define o shape ao qual o final do conector será anexado. Leitura/gravação [`IShape`](../ishape). |
| [EndShapeConnectionSiteIndex](../../aspose.slides/connector/endshapeconnectionsiteindex) { get; set; } | Retorna ou define o índice do ponto de conexão para o shape final. Leitura/gravação UInt32. |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | Retorna o objeto FillFormat que contém propriedades de formatação de preenchimento para um shape. Observação: pode retornar nulo para certos tipos de shapes que não possuem propriedades de preenchimento. Somente leitura [`IFillFormat`](../ifillformat). |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | Retorna ou define as propriedades da moldura do shape. Leitura/gravação [`IShapeFrame`](../ishapeframe). |
| [Height](../../aspose.slides/shape/height) { get; set; } | Obtém ou define a altura do shape, medida em pontos. Leitura/gravação Single. |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | Determina se o shape está oculto. Leitura/gravação Boolean. |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | Retorna ou define o hyperlink definido para clique do mouse. Leitura/gravação [`IHyperlink`](../ihyperlink). |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | Retorna o gerenciador de hyperlink. Somente leitura [`IHyperlinkManager`](../ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | Retorna ou define o hyperlink definido para passar o mouse sobre. Leitura/gravação [`IHyperlink`](../ihyperlink). |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | Obtém ou define a opção 'Marcar como decorativo'. Leitura/gravação Boolean. |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | Determina se o shape está agrupado. Somente leitura Boolean. |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | Determina se o shape é TextHolder_PPT. Somente leitura Boolean. |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | Retorna o objeto LineFormat que contém propriedades de formatação de linha para um shape. Observação: pode retornar nulo para certos tipos de shapes que não possuem propriedades de linha. Somente leitura [`ILineFormat`](../ilineformat). |
| [Name](../../aspose.slides/shape/name) { get; set; } | Retorna ou define o nome de um shape. Deve ser não nulo. Use uma string vazia se necessário. Leitura/gravação String. |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | Retorna um identificador exclusivo de escopo de slide que permanece constante durante a vida útil do shape e permite que o PowerPoint ou código interop faça referência ao shape de forma confiável de qualquer lugar no documento. Somente leitura UInt32. Veja também [`UniqueId`](../shape/uniqueid). |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | Retorna o objeto GroupShape pai se o shape estiver agrupado. Caso contrário, retorna nulo. Somente leitura [`IGroupShape`](../igroupshape). |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | Retorna o placeholder de um shape. Retorna nulo se o shape não possuir placeholder. Somente leitura [`IPlaceholder`](../iplaceholder). |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | Retorna a apresentação pai de um slide. Somente leitura [`IPresentation`](../ipresentation). |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | Retorna ou define as propriedades brutas da moldura do shape. Leitura/gravação [`IShapeFrame`](../ishapeframe). |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | Retorna ou define o número de graus que o shape especificado é girado ao redor do eixo z. Um valor positivo indica rotação no sentido horário; um valor negativo indica rotação no sentido anti-horário. Leitura/gravação Single. |
| [ShapeLock](../../aspose.slides/connector/shapelock) { get; } | Retorna os bloqueios do shape. Somente leitura [`IConnectorLock`](../iconnectorlock). (2 propriedades) |
| [ShapeStyle](../../aspose.slides/geometryshape/shapestyle) { get; } | Retorna o objeto de estilo do shape. Somente leitura [`IShapeStyle`](../ishapestyle). |
| override [ShapeType](../../aspose.slides/connector/shapetype) { get; set; } | Retorna ou define o tipo AutoShape. Leitura/gravação [`ShapeType`](../shapetype). |
| [Slide](../../aspose.slides/shape/slide) { get; } | Retorna o slide pai de um shape. Somente leitura [`IBaseSlide`](../ibaseslide). |
| [StartShapeConnectedTo](../../aspose.slides/connector/startshapeconnectedto) { get; set; } | Retorna ou define o shape ao qual o início do conector será anexado. Leitura/gravação [`IShape`](../ishape). |
| [StartShapeConnectionSiteIndex](../../aspose.slides/connector/startshapeconnectionsiteindex) { get; set; } | Retorna ou define o índice do ponto de conexão para o shape de início. Leitura/gravação UInt32. |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | Retorna o objeto ThreeDFormat que contém propriedades de efeito 3D para um shape. Observação: pode retornar nulo para certos tipos de shapes que não possuem propriedades 3D. Somente leitura [`IThreeDFormat`](../ithreedformat). |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | Retorna um identificador interno de escopo de apresentação destinado ao uso por complementos ou outro código. Como esse valor pode ser reatribuído pelo usuário ou programaticamente, não deve ser tratado como uma chave única persistente. Somente leitura UInt32. Veja também [`OfficeInteropShapeId`](../shape/officeinteropshapeid). |
| [Width](../../aspose.slides/shape/width) { get; set; } | Obtém ou define a largura do shape, medida em pontos. Leitura/gravação Single. |
| [X](../../aspose.slides/shape/x) { get; set; } | Obtém ou define a coordenada x do canto superior esquerdo do shape, medida em pontos. Leitura/gravação Single. |
| [Y](../../aspose.slides/shape/y) { get; set; } | Obtém ou define a coordenada y do canto superior esquerdo do shape, medida em pontos. Leitura/gravação Single. |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | Retorna a posição de um shape na ordem z. Shapes[0] retorna o shape na parte traseira da ordem z, e Shapes[Shapes.Count - 1] retorna o shape na parte dianteira da ordem z. Somente leitura Int32. |

## Métodos

| Nome | Descrição |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | Adiciona um novo placeholder se não houver e define as propriedades do placeholder para um especificado. |
| [CreateShapeElements](../../aspose.slides/geometryshape/createshapeelements)() | Cria e retorna um array dos elementos do shape. |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | Retorna um shape placeholder básico (shape do layout e/ou slide mestre do qual o shape atual é herdado). Retorna nulo se o shape atual não for herdado. |
| [GetGeometryPaths](../../aspose.slides/geometryshape/getgeometrypaths)() | Retorna a cópia do caminho do shape de geometria. As coordenadas são relativas ao canto superior esquerdo do shape. |
| [GetImage](../../aspose.slides/shape/getimage)() | Retorna a miniatura do shape. O tipo ShapeThumbnailBounds.Shape para limites da miniatura do shape é usado por padrão. |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | Retorna a miniatura do shape. |
| [GetVisualBounds](../../aspose.slides/shape/getvisualbounds)() | Obtém os limites visuais do shape calculados a partir do seu conteúdo renderizado. |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | Define que este shape não é um placeholder. |
| [Reroute](../../aspose.slides/connector/reroute)() | Redireciona o conector para que ele siga o caminho mais curto possível entre os shapes que conecta. |
| [SetGeometryPath](../../aspose.slides/geometryshape/setgeometrypath)(IGeometryPath) | Atualiza a geometria do shape a partir do objeto [`IGeometryPath`](../igeometrypath). As coordenadas devem ser relativas ao canto superior esquerdo do shape. Altera o tipo do shape ([`ShapeType`](../geometryshape/shapetype)) para Custom. |
| [SetGeometryPaths](../../aspose.slides/geometryshape/setgeometrypaths)(IGeometryPath[]) | Atualiza a geometria do shape a partir de um array de [`IGeometryPath`](../igeometrypath). As coordenadas devem ser relativas ao canto superior esquerdo do shape. Altera o tipo do shape ([`ShapeType`](../geometryshape/shapetype)) para Custom. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | Salva o conteúdo do Shape como arquivo SVG. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | Salva o conteúdo do Shape como arquivo SVG. |

### Veja Também

* classe [GeometryShape](../geometryshape)
* interface [IConnector](../iconnector)
* namespace [Aspose.Slides](../../aspose.slides)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->