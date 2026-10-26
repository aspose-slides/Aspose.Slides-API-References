---
title: MasterSlide
second_title: Aspose.Sildes para .NET Referência da API
description: Representa um slide mestre em uma apresentação.
type: docs
weight: 8030
url: /pt/aspose.slides/masterslide/
---
## MasterSlide classe

Represents a master slide in a presentation.

```csharp
public class MasterSlide : BaseSlide, IMasterSlide
```

## Propriedades

| Nome | Descrição |
| --- | --- |
| [Background](../../aspose.slides/baseslide/background) { get; } | Retorna o plano de fundo do slide. Somente leitura [`IBackground`](../ibackground). |
| [BodyStyle](../../aspose.slides/masterslide/bodystyle) { get; } | Retorna o estilo de um texto de corpo. Somente leitura [`ITextStyle`](../itextstyle). |
| [Controls](../../aspose.slides/baseslide/controls) { get; } | Retorna a coleção de controles ActiveX em um slide. Somente leitura [`IControlCollection`](../icontrolcollection). |
| [CustomData](../../aspose.slides/baseslide/customdata) { get; } | Retorna os dados personalizados do slide. Somente leitura [`ICustomData`](../icustomdata). |
| [DrawingGuides](../../aspose.slides/masterslide/drawingguides) { get; } | Retorna uma coleção de guias de desenho para o slide mestre. Somente leitura [`IDrawingGuidesCollection`](../idrawingguidescollection) |
| [HasDependingSlides](../../aspose.slides/masterslide/hasdependingslides) { get; } | Retorna true se existir ao menos um slide que dependa deste slide mestre. Somente leitura Boolean. |
| [HeaderFooterManager](../../aspose.slides/masterslide/headerfootermanager) { get; } | Retorna o gerenciador HeaderFooter do slide mestre. Somente leitura [`IMasterSlideHeaderFooterManager`](../imasterslideheaderfootermanager). |
| [HyperlinkQueries](../../aspose.slides/baseslide/hyperlinkqueries) { get; } | Fornece acesso fácil aos hyperlinks contidos. Somente leitura [`IHyperlinkQueries`](../ihyperlinkqueries). |
| [LayoutSlides](../../aspose.slides/masterslide/layoutslides) { get; } | Retorna a coleção de slides de layout filho para este slide mestre. Somente leitura [`IMasterLayoutSlideCollection`](../imasterlayoutslidecollection). |
| override [Name](../../aspose.slides/masterslide/name) { get; set; } | Retorna ou define o nome de um slide mestre. Leitura/gravação String. |
| [OtherStyle](../../aspose.slides/masterslide/otherstyle) { get; } | Retorna o estilo de outro texto. Somente leitura [`ITextStyle`](../itextstyle). |
| [Presentation](../../aspose.slides/baseslide/presentation) { get; } | Retorna a interface IPresentation. Somente leitura [`IPresentation`](../ipresentation). |
| [Preserve](../../aspose.slides/masterslide/preserve) { get; set; } | Determina se o mestre correspondente é excluído quando todos os slides que o seguem são excluídos. Observação: Aspose.Slides nunca removerá nenhum mestre não usado por conta própria; para realmente remover mestres não usados, chame [`RemoveUnused`](../masterslidecollection/removeunused). Leitura/gravação Boolean. |
| [Shapes](../../aspose.slides/baseslide/shapes) { get; } | Retorna as formas de um slide. Somente leitura [`IShapeCollection`](../ishapecollection). |
| override [ShowMasterShapes](../../aspose.slides/masterslide/showmastershapes) { get; set; } | Especifica se as formas no slide mestre devem ser exibidas nos slides ou não. Para o próprio slide mestre, esta propriedade sempre retorna `false`. Leitura/gravação Boolean. |
| [SlideId](../../aspose.slides/baseslide/slideid) { get; } | Retorna o ID de um slide. Somente leitura UInt32. |
| virtual [SlideShowTransition](../../aspose.slides/baseslide/slideshowtransition) { get; } | Retorna o objeto Transition que contém informações sobre como o slide especificado avança durante uma apresentação. Somente leitura [`ISlideShowTransition`](../islideshowtransition). |
| [ThemeManager](../../aspose.slides/masterslide/thememanager) { get; } | Retorna o gerenciador de tema. Somente leitura [`IMasterThemeManager`](../../aspose.slides.theme/imasterthememanager). |
| [Timeline](../../aspose.slides/baseslide/timeline) { get; } | Retorna o objeto de linha do tempo de animação. Somente leitura [`IAnimationTimeLine`](../ianimationtimeline). |
| [TitleStyle](../../aspose.slides/masterslide/titlestyle) { get; } | Retorna o estilo de um texto de título. Somente leitura [`ITextStyle`](../itextstyle). |

## Métodos

| Nome | Descrição |
| --- | --- |
| [ApplyExternalThemeToDependingSlides](../../aspose.slides/masterslide/applyexternalthemetodependingslides)(string) | Cria um novo slide mestre baseado no atual, aplicando um tema externo a ele e aplica o slide mestre criado a todos os slides dependentes. |
| [CreateThemeEffective](../../aspose.slides/baseslide/createthemeeffective)() | Retorna um tema efetivo para este slide. |
| [Equals](../../aspose.slides/baseslide/equals)(IBaseSlide) | Determina se as duas instâncias IBaseSlide são iguais. O valor retornado é calculado com base na estrutura do slide e no conteúdo estático. Dois slides são iguais se todas as formas, estilos, textos, animações e outras configurações, etc., são iguais. A comparação não considera valores de identificadores únicos, por exemplo SlideId, e conteúdo dinâmico, por exemplo valor de data atual em Date Placeholder. |
| [FindShapeByAltText](../../aspose.slides/baseslide/findshapebyalttext)(string) | Encontra a primeira ocorrência de uma forma com o texto alternativo especificado. |
| [GetDependingSlides](../../aspose.slides/masterslide/getdependingslides)() | Retorna um array com todos os slides que dependem deste slide mestre. |
| virtual [JoinPortionsWithSameFormatting](../../aspose.slides/baseslide/joinportionswithsameformatting)() | Mescla runs com a mesma formatação em todos os parágrafos de todas as formas aceitáveis. |
| virtual [JoinPortionsWithSameFormatting](../../aspose.slides/baseslide/joinportionswithsameformatting)(IShapeCollection) | Mescla runs com a mesma formatação em todos os parágrafos em todas as formas aceitáveis. |

### Ver também

* classe [BaseSlide](../baseslide)
* interface [IMasterSlide](../imasterslide)
* namespace [Aspose.Slides](../../aspose.slides)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->