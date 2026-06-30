---
title: LayoutSlide
second_title: Referência da API Aspose.Sildes para .NET
description: Representa um slide de layout.
type: docs
weight: 7620
url: /pt/aspose.slides/layoutslide/
---
## LayoutSlide classe

Representa um slide de layout.

```csharp
public sealed class LayoutSlide : BaseSlide, ILayoutSlide
```

## Propriedades

| Nome | Descrição |
| --- | --- |
| [Background](../../aspose.slides/baseslide/background) { get; } | Retorna o fundo do slide. Somente leitura [`IBackground`](../ibackground). |
| [Controls](../../aspose.slides/baseslide/controls) { get; } | Retorna a coleção de controles ActiveX em um slide. Somente leitura [`IControlCollection`](../icontrolcollection). |
| [CustomData](../../aspose.slides/baseslide/customdata) { get; } | Retorna os dados personalizados do slide. Somente leitura [`ICustomData`](../icustomdata). |
| [DrawingGuides](../../aspose.slides/layoutslide/drawingguides) { get; } | Retorna uma coleção de guias de desenho para o slide de layout. Somente leitura [`IDrawingGuidesCollection`](../idrawingguidescollection) |
| [HasDependingSlides](../../aspose.slides/layoutslide/hasdependingslides) { get; } | Retorna true se existir ao menos um slide que dependa deste slide de layout. Somente leitura Boolean. |
| [HeaderFooterManager](../../aspose.slides/layoutslide/headerfootermanager) { get; } | Retorna o gerenciador HeaderFooter do slide de layout. Somente leitura [`ILayoutSlideHeaderFooterManager`](../ilayoutslideheaderfootermanager). |
| [HyperlinkQueries](../../aspose.slides/baseslide/hyperlinkqueries) { get; } | Fornece acesso fácil aos hyperlinks contidos. Somente leitura [`IHyperlinkQueries`](../ihyperlinkqueries). |
| [LayoutType](../../aspose.slides/layoutslide/layouttype) { get; } | Retorna o tipo de layout deste slide de layout. Somente leitura [`SlideLayoutType`](../slidelayouttype). |
| [MasterSlide](../../aspose.slides/layoutslide/masterslide) { get; set; } | Retorna ou define o slide mestre para um layout. Leitura/gravação [`IMasterSlide`](../imasterslide). |
| virtual [Name](../../aspose.slides/baseslide/name) { get; set; } | Retorna ou define o nome de um slide. Leitura/gravação String. |
| [PlaceholderManager](../../aspose.slides/layoutslide/placeholdermanager) { get; } | Retorna o gerenciador de placeholders do slide de layout. Somente leitura [`ILayoutPlaceholderManager`](../ilayoutplaceholdermanager). |
| [Presentation](../../aspose.slides/baseslide/presentation) { get; } | Retorna a interface IPresentation. Somente leitura [`IPresentation`](../ipresentation). |
| [Shapes](../../aspose.slides/baseslide/shapes) { get; } | Retorna as formas de um slide. Somente leitura [`IShapeCollection`](../ishapecollection). |
| override [ShowMasterShapes](../../aspose.slides/layoutslide/showmastershapes) { get; set; } | Especifica se as formas no slide mestre devem ser exibidas nos slides ou não. Leitura/gravação Boolean. |
| [SlideId](../../aspose.slides/baseslide/slideid) { get; } | Retorna o ID de um slide. Somente leitura UInt32. |
| virtual [SlideShowTransition](../../aspose.slides/baseslide/slideshowtransition) { get; } | Retorna o objeto Transition que contém informações sobre como o slide especificado avança durante a apresentação. Somente leitura [`ISlideShowTransition`](../islideshowtransition). |
| [ThemeManager](../../aspose.slides/layoutslide/thememanager) { get; } | Retorna o gerenciador de tema de substituição. Somente leitura [`IOverrideThemeManager`](../../aspose.slides.theme/ioverridethememanager). |
| [Timeline](../../aspose.slides/baseslide/timeline) { get; } | Retorna o objeto da linha do tempo de animação. Somente leitura [`IAnimationTimeLine`](../ianimationtimeline). |

## Métodos

| Nome | Descrição |
| --- | --- |
| [CreateThemeEffective](../../aspose.slides/baseslide/createthemeeffective)() | Retorna um tema efetivo para este slide. |
| [Equals](../../aspose.slides/baseslide/equals)(IBaseSlide) | Determina se as duas instâncias IBaseSlide são iguais. O valor retornado é calculado com base na estrutura do slide e no conteúdo estático. Dois slides são iguais se todas as formas, estilos, textos, animações e outras configurações etc. forem iguais. A comparação não leva em conta valores de identificadores únicos, por exemplo SlideId, e conteúdo dinâmico, por exemplo o valor da data atual em Date Placeholder. |
| [FindShapeByAltText](../../aspose.slides/baseslide/findshapebyalttext)(string) | Encontra a primeira ocorrência de uma forma com o texto alternativo especificado. |
| [GetDependingSlides](../../aspose.slides/layoutslide/getdependingslides)() | Retorna um array com todos os slides que dependem deste slide de layout. |
| virtual [JoinPortionsWithSameFormatting](../../aspose.slides/baseslide/joinportionswithsameformatting)() | Mescla execuções com a mesma formatação em todos os parágrafos de todas as formas aceitáveis. |
| virtual [JoinPortionsWithSameFormatting](../../aspose.slides/baseslide/joinportionswithsameformatting)(IShapeCollection) | Mescla execuções com a mesma formatação em todos os parágrafos de todas as formas aceitáveis. |
| [Remove](../../aspose.slides/layoutslide/remove)() | Remove o layout da apresentação. |

### Veja Também

* classe [BaseSlide](../baseslide)
* interface [ILayoutSlide](../ilayoutslide)
* espaço de nomes [Aspose.Slides](../../aspose.slides)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->