---
title: Slide
second_title: Referência da API Aspose.Sildes for .NET
description: Representa um slide em uma apresentação.
type: docs
weight: 9940
url: /pt/aspose.slides/slide/
---
## Classe Slide

Representa um slide em uma apresentação.

```csharp
public sealed class Slide : BaseSlide, ISlide
```

## Propriedades

| Nome | Descrição |
| --- | --- |
| [Background](../../aspose.slides/baseslide/background) { get; } | Retorna o plano de fundo do slide. Somente leitura [`IBackground`](../ibackground). |
| [Controls](../../aspose.slides/baseslide/controls) { get; } | Retorna a coleção de controles ActiveX em um slide. Somente leitura [`IControlCollection`](../icontrolcollection). |
| [CustomData](../../aspose.slides/baseslide/customdata) { get; } | Retorna os dados personalizados do slide. Somente leitura [`ICustomData`](../icustomdata). |
| [HeaderFooterManager](../../aspose.slides/slide/headerfootermanager) { get; } | Retorna o gerenciador HeaderFooter do slide. Somente leitura [`ISlideHeaderFooterManager`](../islideheaderfootermanager). |
| [Hidden](../../aspose.slides/slide/hidden) { get; set; } | Determina se o slide especificado está oculto durante a apresentação de slides. Leitura/gravação Boolean. |
| [HyperlinkQueries](../../aspose.slides/baseslide/hyperlinkqueries) { get; } | Fornece acesso fácil aos hiperlinks contidos. Somente leitura [`IHyperlinkQueries`](../ihyperlinkqueries). |
| [LayoutSlide](../../aspose.slides/slide/layoutslide) { get; set; } | Retorna ou define o slide de layout para o slide atual. Leitura/gravação [`ILayoutSlide`](../ilayoutslide). |
| virtual [Name](../../aspose.slides/baseslide/name) { get; set; } | Retorna ou define o nome de um slide. Leitura/gravação String. |
| [NotesSlideManager](../../aspose.slides/slide/notesslidemanager) { get; } | Permite acessar o slide de notas, adicioná-lo e removê-lo. Somente leitura [`INotesSlideManager`](../inotesslidemanager). |
| [Presentation](../../aspose.slides/baseslide/presentation) { get; } | Retorna a interface IPresentation. Somente leitura [`IPresentation`](../ipresentation). |
| [Shapes](../../aspose.slides/baseslide/shapes) { get; } | Retorna as formas de um slide. Somente leitura [`IShapeCollection`](../ishapecollection). |
| override [ShowMasterShapes](../../aspose.slides/slide/showmastershapes) { get; set; } | Especifica se as formas no slide mestre devem ser mostradas nos slides ou não. Leitura/gravação Boolean. |
| [SlideId](../../aspose.slides/baseslide/slideid) { get; } | Retorna o ID de um slide. Somente leitura UInt32. |
| [SlideNumber](../../aspose.slides/slide/slidenumber) { get; set; } | Retorna um número de slide. O índice do slide na coleção [`Slides`](../presentation/slides) é sempre igual a SlideNumber - Presentation.FirstSlideNumber. Leitura/gravação Int32. |
| virtual [SlideShowTransition](../../aspose.slides/baseslide/slideshowtransition) { get; } | Retorna o objeto Transition que contém informações sobre como o slide especificado avança durante a apresentação de slides. Somente leitura [`ISlideShowTransition`](../islideshowtransition). |
| [ThemeManager](../../aspose.slides/slide/thememanager) { get; } | Retorna o gerenciador de tema de substituição. Somente leitura [`IOverrideThemeManager`](../../aspose.slides.theme/ioverridethememanager). |
| [Timeline](../../aspose.slides/baseslide/timeline) { get; } | Retorna o objeto de linha de tempo de animação. Somente leitura [`IAnimationTimeLine`](../ianimationtimeline). |

## Métodos

| Nome | Descrição |
| --- | --- |
| [CreateThemeEffective](../../aspose.slides/baseslide/createthemeeffective)() | Retorna um tema efetivo para este slide. |
| [Equals](../../aspose.slides/baseslide/equals)(IBaseSlide) | Determina se as duas instâncias IBaseSlide são iguais. O valor retornado é calculado com base na estrutura do slide e no conteúdo estático. Dois slides são iguais se todas as formas, estilos, textos, animações e outras configurações, etc., forem iguais. A comparação não leva em conta valores de identificadores únicos, por exemplo SlideId, e conteúdo dinâmico, por exemplo o valor da data atual no Marcador de Data. |
| [FindShapeByAltText](../../aspose.slides/baseslide/findshapebyalttext)(string) | Encontra a primeira ocorrência de uma forma com o texto alternativo especificado. |
| [GetImage](../../aspose.slides/slide/getimage#getimage)() | Retorna um objeto Thumbnail Image (20% do tamanho real). |
| [GetImage](../../aspose.slides/slide/getimage#getimage_1)(IRenderingOptions) | Retorna um objeto Thumbnail Image. |
| [GetImage](../../aspose.slides/slide/getimage#getimage_4)(ITiffOptions) | Retorna um objeto de imagem tiff Thumbnail com os parâmetros especificados. |
| [GetImage](../../aspose.slides/slide/getimage#getimage_6)(Size) | Retorna um objeto Thumbnail Image com o tamanho especificado. |
| [GetImage](../../aspose.slides/slide/getimage#getimage_5)(float, float) | Retorna um objeto Thumbnail Image com escala personalizada. |
| [GetImage](../../aspose.slides/slide/getimage#getimage_3)(IRenderingOptions, Size) | Retorna um objeto Thumbnail Image com o tamanho especificado. |
| [GetImage](../../aspose.slides/slide/getimage#getimage_2)(IRenderingOptions, float, float) | Retorna um objeto Thumbnail Image com escala personalizada. |
| [GetSlideComments](../../aspose.slides/slide/getslidecomments)(ICommentAuthor) | Retorna todos os comentários do slide adicionados por um autor específico. |
| override [JoinPortionsWithSameFormatting](../../aspose.slides/slide/joinportionswithsameformatting#joinportionswithsameformatting)() | Mescla execuções com a mesma formatação em todos os parágrafos em todas as formas aceitáveis. |
| virtual [JoinPortionsWithSameFormatting](../../aspose.slides/baseslide/joinportionswithsameformatting)(IShapeCollection) | Mescla execuções com a mesma formatação em todos os parágrafos em todas as formas aceitáveis. |
| [Remove](../../aspose.slides/slide/remove)() | Remove o slide da apresentação. |
| [Reset](../../aspose.slides/slide/reset)() | Redefine a posição, tamanho e formatação de cada forma que possui um protótipo no LayoutSlide. |
| [WriteAsEmf](../../aspose.slides/slide/writeasemf)(Stream) | Salva o conteúdo do slide como um arquivo EMF. |
| [WriteAsSvg](../../aspose.slides/slide/writeassvg#writeassvg)(Stream) | Salva o conteúdo do slide como um arquivo SVG. |
| [WriteAsSvg](../../aspose.slides/slide/writeassvg#writeassvg_1)(Stream, ISVGOptions) | Salva o conteúdo do slide como um arquivo SVG. |

### Ver também

* classe [BaseSlide](../baseslide)
* interface [ISlide](../islide)
* namespace [Aspose.Slides](../../aspose.slides)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->