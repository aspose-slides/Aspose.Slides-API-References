---
title: TextFrameFormat
second_title: Referência da API Aspose.Sildes para .NET
description: Contém as propriedades formatTextFrameFormatting dos TextFrames.
type: docs
weight: 10940
url: /pt/aspose.slides/textframeformat/
---
## TextFrameFormat classe

Contém as propriedades formatTextFrameFormatting do TextFrame.

```csharp
public sealed class TextFrameFormat : PVIObject, IChartTextBlockFormat, ITextFrameFormat
```

## Construtores

| Nome | Descrição |
| --- | --- |
| [TextFrameFormat](textframeformat)() | Inicializa uma nova instância da classe [`TextFrameFormat`](../textframeformat). |

## Propriedades

| Nome | Descrição |
| --- | --- |
| [AnchoringType](../../aspose.slides/textframeformat/anchoringtype) { get; set; } | Retorna ou define o texto de âncora vertical em um TextFrame. Leitura/Gravação [`TextAnchorType`](../textanchortype). |
| [AsIPresentationComponent](../../aspose.slides/pviobject/asipresentationcomponent) { get; } | Permite obter a interface base IPresentationComponent. Somente leitura [`IPresentationComponent`](../ipresentationcomponent). |
| [AutofitType](../../aspose.slides/textframeformat/autofittype) { get; set; } | Retorna ou define o modo de ajuste automático do texto. Leitura/Gravação [`TextAutofitType`](../textautofittype). |
| [CenterText](../../aspose.slides/textframeformat/centertext) { get; set; } | Se NullableBool.True, o texto deve ser centralizado horizontalmente na caixa. Leitura/Gravação [`NullableBool`](../nullablebool). |
| [ColumnCount](../../aspose.slides/textframeformat/columncount) { get; set; } | Retorna ou define o número de colunas na área de texto. Este valor deve ser um número positivo. Caso contrário, o valor será definido como zero. Valor 0 significa valor indefinido. Leitura/Gravação Int32. |
| [ColumnSpacing](../../aspose.slides/textframeformat/columnspacing) { get; set; } | Retorna ou define o espaço entre colunas de texto na área de texto (em pontos). Isso deve ser aplicado somente quando houver mais de 1 coluna presente. Este valor deve ser um número positivo. Caso contrário, o valor será definido como zero. Leitura/Gravação Double. |
| [KeepTextFlat](../../aspose.slides/textframeformat/keeptextflat) { get; set; } | Obtém ou define a manutenção do texto plano mesmo se um efeito de Rotação 3-D foi aplicado. Leitura/Gravação Boolean. |
| [MarginBottom](../../aspose.slides/textframeformat/marginbottom) { get; set; } | Retorna ou define a margem inferior (pontos) em um TextFrame. Leitura/Gravação Double. |
| [MarginLeft](../../aspose.slides/textframeformat/marginleft) { get; set; } | Retorna ou define a margem esquerda (pontos) em um TextFrame. Leitura/Gravação Double. |
| [MarginRight](../../aspose.slides/textframeformat/marginright) { get; set; } | Retorna ou define a margem direita (pontos) em um TextFrame. Leitura/Gravação Double. |
| [MarginTop](../../aspose.slides/textframeformat/margintop) { get; set; } | Retorna ou define a margem superior (pontos) em um TextFrame. Leitura/Gravação Double. |
| [RotationAngle](../../aspose.slides/textframeformat/rotationangle) { get; set; } | Especifica a rotação personalizada que é aplicada ao texto dentro da caixa delimitadora. Se não for especificada, a rotação da forma associada é usada. Se for especificada, ela é aplicada independentemente da forma. Ou seja, a forma pode ter uma rotação aplicada além da rotação aplicada ao próprio texto. O valor resultante da rotação visual do texto resumido a partir desta propriedade e do tipo vertical predefinido na propriedade TextVerticalType. Leitura/Gravação Single. |
| [TextVerticalType](../../aspose.slides/textframeformat/textverticaltype) { get; set; } | Determina a orientação do texto. O valor resultante da rotação visual do texto resumido a partir desta propriedade e do ângulo personalizado na propriedade RotationAngle. Leitura/Gravação [`TextVerticalType`](../textverticaltype). |
| [ThreeDFormat](../../aspose.slides/textframeformat/threedformat) { get; } | Retorna o objeto ThreeDFormat que representa as propriedades de efeito 3d para um texto. Somente leitura [`IThreeDFormat`](../ithreedformat). |
| [Transform](../../aspose.slides/textframeformat/transform) { get; set; } | Obtém ou define a forma de quebra de linha do texto. Leitura/Gravação [`TextShapeType`](../textshapetype). |
| [WrapText](../../aspose.slides/textframeformat/wraptext) { get; set; } | **True** se o texto for quebrado nas margens do TextFrame. Leitura/Gravação [`NullableBool`](../nullablebool). |

## Métodos

| Nome | Descrição |
| --- | --- |
| sobrescreve [Equals](../../aspose.slides/pviobject/equals)(object) | Compara com o objeto especificado. |
| [GetEffective](../../aspose.slides/textframeformat/geteffective)() | Obtém os dados efetivos de formatação do quadro de texto com a herança aplicada. |
| sobrescreve [GetHashCode](../../aspose.slides/pviobject/gethashcode)() | Retorna o código hash. |

### Veja Também

* classe [PVIObject](../pviobject)
* interface [IChartTextBlockFormat](../../aspose.slides.charts/icharttextblockformat)
* interface [ITextFrameFormat](../itextframeformat)
* espaço de nomes [Aspose.Slides](../../aspose.slides)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->