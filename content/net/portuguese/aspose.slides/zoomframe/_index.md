---
title: ZoomFrame
second_title: Referência da API Aspose.Sildes para .NET
description: Representa um objeto Slide Zoom em um slide.
type: docs
weight: 11820
url: /pt/aspose.slides/zoomframe/
---
## ZoomFrame classe

Representa um objeto Slide Zoom em um slide.

```csharp
public class ZoomFrame : ZoomObject, IZoomFrame
```

## Propriedades

| Nome | Descrição |
| --- | --- |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | Retorna ou define o texto alternativo associado a uma forma. Leitura/gravação String. |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | Retorna ou define o título do texto alternativo associado a uma forma. Leitura/gravação String. |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | A propriedade especifica como uma forma será renderizada no modo de exibição em preto e branco. Leitura/gravação [`BlackWhiteMode`](../blackwhitemode). |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | Retorna o número de pontos de conexão na forma. Somente leitura Int32. |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | Retorna os dados personalizados da forma. Somente leitura [`ICustomData`](../icustomdata). |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | Retorna o objeto EffectFormat que contém efeitos de pixel aplicados a uma forma. Nota: pode retornar null para certos tipos de formas que não possuem propriedades de efeito. Somente leitura [`IEffectFormat`](../ieffectformat). |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | Retorna o objeto FillFormat que contém propriedades de formatação de preenchimento para uma forma. Nota: pode retornar null para certos tipos de formas que não possuem propriedades de preenchimento. Somente leitura [`IFillFormat`](../ifillformat). |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | Retorna ou define as propriedades da moldura da forma. Leitura/gravação [`IShapeFrame`](../ishapeframe). |
| [GraphicalObjectLock](../../aspose.slides/graphicalobject/graphicalobjectlock) { get; } | Retorna os bloqueios da forma. Somente leitura [`IGraphicalObjectLock`](../igraphicalobjectlock). |
| [Height](../../aspose.slides/shape/height) { get; set; } | Obtém ou define a altura da forma, medida em pontos. Leitura/gravação Single. |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | Determina se a forma está oculta. Leitura/gravação Boolean. |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | Retorna ou define o hyperlink definido para clique do mouse. Leitura/gravação [`IHyperlink`](../ihyperlink). |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | Retorna o gerenciador de hyperlink. Somente leitura [`IHyperlinkManager`](../ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | Retorna ou define o hyperlink definido para mouse over. Leitura/gravação [`IHyperlink`](../ihyperlink). |
| [ImageType](../../aspose.slides/zoomobject/imagetype) { get; set; } | Obtém ou define o tipo de imagem de um objeto zoom. Leitura/gravação [`ZoomImageType`](../zoomimagetype). Valor padrão: Preview |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | Obtém ou define a opção “Marcar como decorativo”. Leitura/gravação Boolean. |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | Determina se a forma está agrupada. Somente leitura Boolean. |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | Determina se a forma é TextHolder_PPT. Somente leitura Boolean. |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | Retorna o objeto LineFormat que contém propriedades de formatação de linha para uma forma. Nota: pode retornar null para certos tipos de formas que não possuem propriedades de linha. Somente leitura [`ILineFormat`](../ilineformat). |
| [Name](../../aspose.slides/shape/name) { get; set; } | Retorna ou define o nome de uma forma. Deve ser não nulo. Use string vazia se necessário. Leitura/gravação String. |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | Retorna um identificador exclusivo de escopo de slide que permanece constante durante a vida útil da forma e permite que o PowerPoint ou código interop referencie a forma de forma confiável a partir de qualquer lugar do documento. Somente leitura UInt32. Veja também [`UniqueId`](../shape/uniqueid). |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | Retorna o objeto GroupShape pai se a forma estiver agrupada. Caso contrário, retorna null. Somente leitura [`IGroupShape`](../igroupshape). |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | Retorna o placeholder de uma forma. Retorna null se a forma não tiver placeholder. Somente leitura [`IPlaceholder`](../iplaceholder). |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | Retorna a apresentação pai de um slide. Somente leitura [`IPresentation`](../ipresentation). |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | Obtém ou define as propriedades brutas do quadro da forma. Leitura/gravação [`IShapeFrame`](../ishapeframe). |
| [ReturnToParent](../../aspose.slides/zoomobject/returntoparent) { get; set; } | Obtém ou define o comportamento de navegação na apresentação de slides. Leitura/gravação Boolean. Valor padrão: false |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | Retorna ou define o número de graus que a forma especificada está rotacionada ao redor do eixo z. Um valor positivo indica rotação no sentido horário; um valor negativo indica rotação no sentido anti-horário. Leitura/gravação Single. |
| [ShapeLock](../../aspose.slides/graphicalobject/shapelock) { get; } | Retorna os bloqueios da forma. Somente leitura [`IGraphicalObjectLock`](../igraphicalobjectlock). (2 propriedades) |
| [ShowBackground](../../aspose.slides/zoomobject/showbackground) { get; set; } | Obtém ou define o valor que especifica se o Zoom usará o fundo do slide de destino. Leitura/gravação Boolean. Valor padrão: true |
| [Slide](../../aspose.slides/shape/slide) { get; } | Retorna o slide pai de uma forma. Somente leitura [`IBaseSlide`](../ibaseslide). |
| [TargetSlide](../../aspose.slides/zoomframe/targetslide) { get; set; } | Obtém ou define o objeto slide ao qual o objeto Slide Zoom está vinculado. Leitura/gravação [`ISlide`](../islide). |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | Retorna o objeto ThreeDFormat que contém propriedades de efeito 3D para uma forma. Nota: pode retornar null para certos tipos de formas que não possuem propriedades 3D. Somente leitura [`IThreeDFormat`](../ithreedformat). |
| [TransitionDuration](../../aspose.slides/zoomobject/transitionduration) { get; set; } | Obtém ou define a duração da transição entre Zoom e slide. Leitura/gravação Single. Valor padrão: 1.0f |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | Retorna um identificador interno, de escopo de apresentação, destinado ao uso por add-ins ou outro código. Como esse valor pode ser reatribuído pelo usuário ou programaticamente, não deve ser tratado como uma chave única persistente. Somente leitura UInt32. Veja também [`OfficeInteropShapeId`](../shape/officeinteropshapeid). |
| [Width](../../aspose.slides/shape/width) { get; set; } | Obtém ou define a largura da forma, medida em pontos. Leitura/gravação Single. |
| [X](../../aspose.slides/shape/x) { get; set; } | Obtém ou define a coordenada x do canto superior esquerdo da forma, medida em pontos. Leitura/gravação Single. |
| [Y](../../aspose.slides/shape/y) { get; set; } | Obtém ou define a coordenada y do canto superior esquerdo da forma, medida em pontos. Leitura/gravação Single. |
| [ZoomImage](../../aspose.slides/zoomobject/zoomimage) { get; set; } | Obtém ou define a imagem para o objeto zoom. Leitura/gravação [`IPPImage`](../ippimage). |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | Retorna a posição de uma forma na ordem Z. Shapes[0] devolve a forma mais ao fundo da ordem Z, e Shapes[Shapes.Count - 1] devolve a forma mais à frente da ordem Z. Somente leitura Int32. |

## Métodos

| Nome | Descrição |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | adiciona um novo placeholder se não houver e define as propriedades do placeholder para o especificado. |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | retorna um shape placeholder básico (shape do layout e/ou do slide mestre do qual o shape atual é herdado). Retorna null se o shape atual não for herdado. |
| [GetImage](../../aspose.slides/shape/getimage)() | retorna a miniatura do shape. O tipo ShapeThumbnailBounds.Shape de limites da miniatura do shape é usado por padrão. |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | retorna a miniatura do shape. |
| [GetVisualBounds](../../aspose.slides/shape/getvisualbounds)() | obtém os limites visuais do shape calculados a partir do seu conteúdo renderizado. |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | define que este shape não é um placeholder. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | salva o conteúdo do Shape como arquivo SVG. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | salva o conteúdo do Shape como arquivo SVG. |

### Ver Também

* classe [ZoomObject](../zoomobject)
* interface [IZoomFrame](../izoomframe)
* namespace [Aspose.Slides](../../aspose.slides)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->