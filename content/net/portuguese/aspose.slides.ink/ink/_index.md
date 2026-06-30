---
title: Ink
second_title: Referência da API Aspose.Sildes para .NET
description: Representa um objeto de tinta em um slide.
type: docs
weight: 7530
url: /pt/aspose.slides.ink/ink/
---
## Classe Ink

Representa um objeto de tinta em um slide.

```csharp
public class Ink : GraphicalObject, IInk
```

## Propriedades

| Nome | Descrição |
| --- | --- |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | Retorna ou define o texto alternativo associado a uma forma. Leitura/gravação String. |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | Retorna ou define o título do texto alternativo associado a uma forma. Leitura/gravação String. |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | Propriedade especifica como uma forma será renderizada no modo de exibição em preto e branco. Leitura/gravação [`BlackWhiteMode`](../../aspose.slides/blackwhitemode). |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | Retorna o número de pontos de conexão na forma. Somente leitura Int32. |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | Retorna os dados personalizados da forma. Somente leitura [`ICustomData`](../../aspose.slides/icustomdata). |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | Retorna o objeto EffectFormat que contém efeitos de pixel aplicados a uma forma. Nota: pode retornar null para certos tipos de formas que não possuem propriedades de efeito. Somente leitura [`IEffectFormat`](../../aspose.slides/ieffectformat). |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | Retorna o objeto FillFormat que contém propriedades de preenchimento para uma forma. Nota: pode retornar null para certos tipos de formas que não possuem propriedades de preenchimento. Somente leitura [`IFillFormat`](../../aspose.slides/ifillformat). |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | Retorna ou define as propriedades da moldura da forma. Leitura/gravação [`IShapeFrame`](../../aspose.slides/ishapeframe). |
| [GraphicalObjectLock](../../aspose.slides/graphicalobject/graphicalobjectlock) { get; } | Retorna os bloqueios da forma. Somente leitura [`IGraphicalObjectLock`](../../aspose.slides/igraphicalobjectlock). |
| [Height](../../aspose.slides/shape/height) { get; set; } | Obtém ou define a altura da forma, medida em pontos. Leitura/gravação Single. |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | Determina se a forma está oculta. Leitura/gravação Boolean. |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | Retorna ou define o hiperlink definido para clique do mouse. Leitura/gravação [`IHyperlink`](../../aspose.slides/ihyperlink). |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | Retorna o gerenciador de hiperlinks. Somente leitura [`IHyperlinkManager`](../../aspose.slides/ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | Retorna ou define o hiperlink definido para passar o mouse sobre. Leitura/gravação [`IHyperlink`](../../aspose.slides/ihyperlink). |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | Obtém ou define a opção “Marcar como decorativo”. Leitura/gravação Boolean. |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | Determina se a forma está agrupada. Somente leitura Boolean. |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | Determina se a forma é TextHolder_PPT. Somente leitura Boolean. |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | Retorna o objeto LineFormat que contém propriedades de formatação de linha para uma forma. Nota: pode retornar null para certos tipos de formas que não possuem propriedades de linha. Somente leitura [`ILineFormat`](../../aspose.slides/ilineformat). |
| [Name](../../aspose.slides/shape/name) { get; set; } | Retorna ou define o nome de uma forma. Não pode ser nulo. Use uma string vazia se necessário. Leitura/gravação String. |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | Retorna um identificador exclusivo com escopo de slide que permanece constante durante a vida útil da forma e permite que o PowerPoint ou código de interop faça referência confiável à forma a partir de qualquer ponto no documento. Somente leitura UInt32. Veja também [`UniqueId`](../../aspose.slides/shape/uniqueid). |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | Retorna o objeto GroupShape pai se a forma estiver agrupada. Caso contrário, retorna null. Somente leitura [`IGroupShape`](../../aspose.slides/igroupshape). |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | Retorna o espaço reservado para uma forma. Retorna null se a forma não possuir espaço reservado. Somente leitura [`IPlaceholder`](../../aspose.slides/iplaceholder). |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | Retorna a apresentação pai de um slide. Somente leitura [`IPresentation`](../../aspose.slides/ipresentation). |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | Retorna ou define as propriedades brutas da moldura da forma. Leitura/gravação [`IShapeFrame`](../../aspose.slides/ishapeframe). |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | Retorna ou define o número de graus que a forma especificada é rotacionada ao redor do eixo z. Um valor positivo indica rotação no sentido horário; um valor negativo indica rotação no sentido anti-horário. Leitura/gravação Single. |
| [ShapeLock](../../aspose.slides/graphicalobject/shapelock) { get; } | Retorna os bloqueios da forma. Somente leitura [`IGraphicalObjectLock`](../../aspose.slides/igraphicalobjectlock). (2 propriedades) |
| [Slide](../../aspose.slides/shape/slide) { get; } | Retorna o slide pai de uma forma. Somente leitura [`IBaseSlide`](../../aspose.slides/ibaseslide). |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | Retorna o objeto ThreeDFormat que contém propriedades de efeito 3D para uma forma. Nota: pode retornar null para certos tipos de formas que não possuem propriedades 3D. Somente leitura [`IThreeDFormat`](../../aspose.slides/ithreedformat). |
| [Traces](../../aspose.slides.ink/ink/traces) { get; } | Obtém todos os rastros contidos no elemento IInk [`IInkTrace`](../iinktrace). Somente leitura. |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | Retorna um identificador interno com escopo de apresentação destinado ao uso por complementos ou outro código. Como esse valor pode ser reatribuído pelo usuário ou programaticamente, não deve ser tratado como uma chave única persistente. Somente leitura UInt32. Veja também [`OfficeInteropShapeId`](../../aspose.slides/shape/officeinteropshapeid). |
| [Width](../../aspose.slides/shape/width) { get; set; } | Obtém ou define a largura da forma, medida em pontos. Leitura/gravação Single. |
| [X](../../aspose.slides/shape/x) { get; set; } | Obtém ou define a coordenada x do canto superior esquerdo da forma, medida em pontos. Leitura/gravação Single. |
| [Y](../../aspose.slides/shape/y) { get; set; } | Obtém ou define a coordenada y do canto superior esquerdo da forma, medida em pontos. Leitura/gravação Single. |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | Retorna a posição de uma forma na ordem Z. Shapes[0] retorna a forma mais ao fundo da ordem Z, e Shapes[Shapes.Count - 1] retorna a forma mais à frente da ordem Z. Somente leitura Int32. |
| static [InkEffectImages](../../aspose.slides.ink/ink/inkeffectimages) { get; } | Obtém a coleção de imagens personalizadas usadas para simular efeitos visuais para pincéis de tinta. Essas imagens são usadas ao renderizar tinta com valores específicos de [`InkEffectType`](../inkeffecttype), como Galaxy, Rainbow, etc. Ao fornecer suas próprias imagens, você pode controlar como cada efeito de tinta aparece. |

## Métodos

| Nome | Descrição |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | adiciona um novo espaço reservado se não houver e define as propriedades do espaço reservado para o especificado. |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | Retorna uma forma de espaço reservado básica (forma do layout e/ou slide mestre da qual a forma atual é herdada). Retorna null se a forma atual não for herdada. |
| [GetImage](../../aspose.slides/shape/getimage)() | Retorna a miniatura da forma. O tipo ShapeThumbnailBounds.Shape é usado por padrão. |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | Retorna a miniatura da forma. |
| [GetVisualBounds](../../aspose.slides/shape/getvisualbounds)() | Obtém os limites visuais da forma calculados a partir de seu conteúdo renderizado. |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | Define que esta forma não é um espaço reservado. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | Salva o conteúdo da Forma como arquivo SVG. |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | Salva o conteúdo da Forma como arquivo SVG. |

### Veja Também

* classe [GraphicalObject](../../aspose.slides/graphicalobject)
* interface [IInk](../iink)
* espaço de nomes [Aspose.Slides.Ink](../../aspose.slides.ink)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->