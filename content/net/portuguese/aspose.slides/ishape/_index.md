---
title: IShape
second_title: Referência da API Aspose.Sildes para .NET
description: Representa uma forma em um slide.
type: docs
weight: 6930
url: /pt/aspose.slides/ishape/
---
## interface IShape

Representa uma forma em um slide.

```csharp
public interface IShape : IHyperlinkContainer, ISlideComponent
```

## Propriedades

| Nome | Descrição |
| --- | --- |
| [AlternativeText](../../aspose.slides/ishape/alternativetext) { get; set; } | Obtém ou define o texto alternativo associado a uma forma. Leitura/Gravação String. |
| [AlternativeTextTitle](../../aspose.slides/ishape/alternativetexttitle) { get; set; } | Obtém ou define o título do texto alternativo associado a uma forma. Leitura/Gravação String. |
| [AsIHyperlinkContainer](../../aspose.slides/ishape/asihyperlinkcontainer) { get; } | Permite obter a interface base IHyperlinkContainer. Somente leitura [`IHyperlinkContainer`](../ihyperlinkcontainer). |
| [AsISlideComponent](../../aspose.slides/ishape/asislidecomponent) { get; } | Permite obter a interface base ISlideComponent. Somente leitura [`ISlideComponent`](../islidecomponent). |
| [BlackWhiteMode](../../aspose.slides/ishape/blackwhitemode) { get; set; } | Propriedade que especifica como uma forma será renderizada no modo de exibição em preto e branco. Leitura/Gravação [`BlackWhiteMode`](../blackwhitemode). |
| [ConnectionSiteCount](../../aspose.slides/ishape/connectionsitecount) { get; } | Obtém o número de pontos de conexão na forma. Somente leitura Int32. |
| [CustomData](../../aspose.slides/ishape/customdata) { get; } | Obtém os dados personalizados da forma. Somente leitura [`ICustomData`](../icustomdata). |
| [EffectFormat](../../aspose.slides/ishape/effectformat) { get; } | Obtém o objeto EffectFormat que contém efeitos de pixel aplicados a uma forma. Somente leitura [`IEffectFormat`](../ieffectformat). |
| [FillFormat](../../aspose.slides/ishape/fillformat) { get; } | Obtém o objeto FillFormat que contém as propriedades de formatação de preenchimento para uma forma. Somente leitura [`IFillFormat`](../ifillformat). |
| [Frame](../../aspose.slides/ishape/frame) { get; set; } | Obtém ou define as propriedades da moldura da forma. Leitura/Gravação [`IShapeFrame`](../ishapeframe). |
| [Height](../../aspose.slides/ishape/height) { get; set; } | Obtém ou define a altura da forma, medida em pontos. Leitura/Gravação Single. |
| [Hidden](../../aspose.slides/ishape/hidden) { get; set; } | Determina se a forma está oculta. Leitura/Gravação Boolean. |
| [IsDecorative](../../aspose.slides/ishape/isdecorative) { get; set; } | Obtém ou define a opção 'Marcar como decorativo'. Leitura/Gravação Boolean. |
| [IsGrouped](../../aspose.slides/ishape/isgrouped) { get; } | Determina se a forma está agrupada. Somente leitura Boolean. |
| [IsTextHolder](../../aspose.slides/ishape/istextholder) { get; } | Determina se a forma é TextHolder. Somente leitura Boolean. |
| [LineFormat](../../aspose.slides/ishape/lineformat) { get; } | Obtém o objeto LineFormat que contém as propriedades de formatação de linha para uma forma. Somente leitura [`ILineFormat`](../ilineformat). |
| [Name](../../aspose.slides/ishape/name) { get; set; } | Obtém ou define o nome de uma forma. Leitura/Gravação String. |
| [OfficeInteropShapeId](../../aspose.slides/ishape/officeinteropshapeid) { get; } | Obtém um identificador exclusivo com escopo de slide que permanece constante durante a vida útil da forma e permite que o PowerPoint ou código de interop referencie a forma de forma confiável a partir de qualquer lugar no documento. Somente leitura UInt32. Veja também [`UniqueId`](./uniqueid). |
| [ParentGroup](../../aspose.slides/ishape/parentgroup) { get; } | Obtém o objeto GroupShape pai se a forma estiver agrupada. Caso contrário, retorna nulo. Somente leitura [`IGroupShape`](../igroupshape). |
| [Placeholder](../../aspose.slides/ishape/placeholder) { get; } | Obtém o placeholder de uma forma. Somente leitura [`IPlaceholder`](../iplaceholder). |
| [RawFrame](../../aspose.slides/ishape/rawframe) { get; set; } | Obtém ou define as propriedades brutas da moldura da forma. Leitura/Gravação [`IShapeFrame`](../ishapeframe). |
| [Rotation](../../aspose.slides/ishape/rotation) { get; set; } | Obtém ou define o número de graus que a forma especificada está rotacionada ao redor do eixo z. Um valor positivo indica rotação no sentido horário; um valor negativo indica rotação no sentido anti-horário. Leitura/Gravação Single. |
| [ShapeLock](../../aspose.slides/ishape/shapelock) { get; } | Obtém os bloqueios da forma. Somente leitura [`IBaseShapeLock`](../ibaseshapelock). |
| [ThreeDFormat](../../aspose.slides/ishape/threedformat) { get; } | Obtém o objeto ThreeDFormat que contém as propriedades de formatação de linha para uma forma. Somente leitura [`IThreeDFormat`](../ithreedformat). |
| [UniqueId](../../aspose.slides/ishape/uniqueid) { get; } | Obtém um identificador interno com escopo de apresentação destinado ao uso por complementos ou outro código. Como esse valor pode ser reatribuído pelo usuário ou programaticamente, ele não deve ser tratado como uma chave única persistente. Somente leitura UInt32. Veja também [`OfficeInteropShapeId`](./officeinteropshapeid). |
| [Width](../../aspose.slides/ishape/width) { get; set; } | Obtém ou define a largura da forma, medida em pontos. Leitura/Gravação Single. |
| [X](../../aspose.slides/ishape/x) { get; set; } | Obtém ou define a coordenada x do canto superior esquerdo da forma, medida em pontos. Leitura/Gravação Single. |
| [Y](../../aspose.slides/ishape/y) { get; set; } | Obtém ou define a coordenada y do canto superior esquerdo da forma, medida em pontos. Leitura/Gravação Single. |
| [ZOrderPosition](../../aspose.slides/ishape/zorderposition) { get; } | Obtém a posição de uma forma na ordem z. Shapes[0] retorna a forma na parte de trás da ordem z, e Shapes[Shapes.Count - 1] retorna a forma na frente da ordem z. Somente leitura Int32. |

## Métodos

| Nome | Descrição |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/ishape/addplaceholder)(IPlaceholder) | Adiciona um novo placeholder se não houver um e define as propriedades do placeholder para um especificado. |
| [GetBasePlaceholder](../../aspose.slides/ishape/getbaseplaceholder)() | Retorna uma forma placeholder básica (forma do layout e/ou slide mestre da qual a forma atual é herdada). Retorna nulo se a forma atual não for herdada. |
| [GetImage](../../aspose.slides/ishape/getimage#getimage)() | Retorna a miniatura da forma. O tipo ShapeThumbnailBounds.Shape de limites da miniatura da forma é usado por padrão. |
| [GetImage](../../aspose.slides/ishape/getimage#getimage_1)(ShapeThumbnailBounds, float, float) | Retorna a miniatura da forma. |
| [RemovePlaceholder](../../aspose.slides/ishape/removeplaceholder)() | Define que esta forma não é um placeholder. |
| [WriteAsSvg](../../aspose.slides/ishape/writeassvg#writeassvg)(Stream) | Salva o conteúdo da Forma como arquivo SVG. |
| [WriteAsSvg](../../aspose.slides/ishape/writeassvg#writeassvg_1)(Stream, ISVGOptions) | Salva o conteúdo da Forma como arquivo SVG. |

### Ver também

* interface [IHyperlinkContainer](../ihyperlinkcontainer)
* interface [ISlideComponent](../islidecomponent)
* namespace [Aspose.Slides](../../aspose.slides)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->