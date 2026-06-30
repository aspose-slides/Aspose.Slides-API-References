---
title: LegacyDiagram
second_title: Aspose.Sildes para .NET Referência da API
description: Representa um objeto de diagrama legado.
type: docs
weight: 7650
url: /pt/aspose.slides/legacydiagram/
---
## LegacyDiagram classe

Representa um objeto de diagrama antigo.

```csharp
public class LegacyDiagram : GraphicalObject, ILegacyDiagram
```

## Propriedades

| Nome | Descrição |
| --- | --- |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | Obtém ou define o texto alternativo associado a uma forma. Leitura/gravação String. |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | Obtém ou define o título do texto alternativo associado a uma forma. Leitura/gravação String. |
| [AsIGraphicalObject](../../aspose.slides/legacydiagram/asigraphicalobject) { get; } | Permite obter a interface base IGraphicalObject. Somente leitura [`IGraphicalObject`](../igraphicalobject). |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | Propriedade que especifica como uma forma será renderizada no modo de exibição em preto e branco. Leitura/gravação [`BlackWhiteMode`](../blackwhitemode). |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | Obtém o número de pontos de conexão na forma. Somente leitura Int32. |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | Obtém os dados personalizados da forma. Somente leitura [`ICustomData`](../icustomdata). |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | Obtém o objeto EffectFormat que contém efeitos de pixel aplicados a uma forma. Observação: pode retornar null para determinados tipos de formas que não possuem propriedades de efeito. Somente leitura [`IEffectFormat`](../ieffectformat). |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | Obtém o objeto FillFormat que contém propriedades de formatação de preenchimento para uma forma. Observação: pode retornar null para determinados tipos de formas que não possuem propriedades de preenchimento. Somente leitura [`IFillFormat`](../ifillformat). |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | Obtém ou define as propriedades da moldura da forma. Leitura/gravação [`IShapeFrame`](../ishapeframe). |
| [GraphicalObjectLock](../../aspose.slides/graphicalobject/graphicalobjectlock) { get; } | Obtém os bloqueios da forma. Somente leitura [`IGraphicalObjectLock`](../igraphicalobjectlock). |
| [Height](../../aspose.slides/shape/height) { get; set; } | Obtém ou define a altura da forma, medida em pontos. Leitura/gravação Single. |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | Determina se a forma está oculta. Leitura/gravação Boolean. |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | Obtém ou define o hiperlink definido para clique do mouse. Leitura/gravação [`IHyperlink`](../ihyperlink). |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | Obtém o gerenciador de hiperlink. Somente leitura [`IHyperlinkManager`](../ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | Obtém ou define o hiperlink definido para mouse over. Leitura/gravação [`IHyperlink`](../ihyperlink). |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | Obtém ou define a opção 'Marcar como decorativo'. Leitura/gravação Boolean. |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | Determina se a forma está agrupada. Somente leitura Boolean. |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | Determina se a forma é TextHolder_PPT. Somente leitura Boolean. |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | Obtém o objeto LineFormat que contém propriedades de formatação de linha para uma forma. Observação: pode retornar null para determinados tipos de formas que não possuem propriedades de linha. Somente leitura [`ILineFormat`](../ilineformat). |
| [Name](../../aspose.slides/shape/name) { get; set; } | Obtém ou define o nome de uma forma. Não pode ser nulo. Use uma string vazia se necessário. Leitura/gravação String. |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | Obtém um identificador único de escopo de slide que permanece constante durante a vida útil da forma e permite que o PowerPoint ou código interop referencie a forma de forma confiável a partir de qualquer ponto do documento. Somente leitura UInt32. Veja também [`UniqueId`](../shape/uniqueid). |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | Obtém o objeto GroupShape pai se a forma estiver agrupada. Caso contrário, retorna null. Somente leitura [`IGroupShape`](../igroupshape). |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | Obtém o placeholder de uma forma. Retorna null se a forma não possuir placeholder. Somente leitura [`IPlaceholder`](../iplaceholder). |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | Obtém a apresentação pai de um slide. Somente leitura [`IPresentation`](../ipresentation). |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | Obtém ou define as propriedades brutas da moldura da forma. Leitura/gravação [`IShapeFrame`](../ishapeframe). |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | Obtém ou define o número de graus que a forma especificada está rotacionada ao redor do eixo z. Um valor positivo indica rotação no sentido horário; um valor negativo indica rotação no sentido anti-horário. Leitura/gravação Single. |
| [ShapeLock](../../aspose.slides/graphicalobject/shapelock) { get; } | Obtém os bloqueios da forma. Somente leitura [`IGraphicalObjectLock`](../igraphicalobjectlock). (2 propriedades) |
| [Slide](../../aspose.slides/shape/slide) { get; } | Obtém o slide pai de uma forma. Somente leitura [`IBaseSlide`](../ibaseslide). |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | Obtém o objeto ThreeDFormat que contém propriedades de efeito 3D para uma forma. Observação: pode retornar null para determinados tipos de formas que não possuem propriedades 3D. Somente leitura [`IThreeDFormat`](../ithreedformat). |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | Obtém um identificador interno, de escopo de apresentação, destinado ao uso por complementos ou outro código. Como esse valor pode ser reatribuído pelo usuário ou programaticamente, não deve ser tratado como uma chave única persistente. Somente leitura UInt32. Veja também [`OfficeInteropShapeId`](../shape/officeinteropshapeid). |
| [Width](../../aspose.slides/shape/width) { get; set; } | Obtém ou define a largura da forma, medida em pontos. Leitura/gravação Single. |
| [X](../../aspose.slides/shape/x) { get; set; } | Obtém ou define a coordenada x do canto superior esquerdo da forma, medida em pontos. Leitura/gravação Single. |
| [Y](../../aspose.slides/shape/y) { get; set; } | Obtém ou define a coordenada y do canto superior esquerdo da forma, medida em pontos. Leitura/gravação Single. |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | Obtém a posição de uma forma na ordem Z. Shapes[0] retorna a forma mais ao fundo da ordem Z, e Shapes[Shapes.Count - 1] retorna a forma mais ao frente da ordem Z. Somente leitura Int32. |

## Métodos

| Nome | Descrição |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | Adiciona um novo placeholder se não houver e define as propriedades do placeholder para um especificado. |
| [ConvertToGroupShape](../../aspose.slides/legacydiagram/converttogroupshape)() | Converte diagrama legado em um group shape editável. O objeto GroupShape criado é adicionado ao group shape pai na mesma posição. |
| [ConvertToSmartArt](../../aspose.slides/legacydiagram/converttosmartart)() | Converte diagrama legado em um objeto SmartArt editável. O objeto SmartArt criado é adicionado ao group shape pai na mesma posição. |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | Retorna uma forma placeholder básica (forma do layout e/ou slide mestre da qual a forma atual é herdada). Retorna null se a forma atual não for herdada. |
| [GetImage](../../aspose.slides/shape/getimage)() | Retorna a miniatura da forma. O tipo ShapeThumbnailBounds.Shape de limites da miniatura da forma é usado por padrão. |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | Retorna a miniatura da forma. |
| [GetVisualBounds](../../aspose.slides/shape/getvisualbounds)() | Obtém os limites visuais da forma calculados a partir do seu conteúdo renderizado. |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | Define que esta forma não é um placeholder. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | Salva o conteúdo da Shape como arquivo SVG. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | Salva o conteúdo da Shape como arquivo SVG. |

### Ver Também

* classe [GraphicalObject](../graphicalobject)
* interface [ILegacyDiagram](../ilegacydiagram)
* namespace [Aspose.Slides](../../aspose.slides)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->