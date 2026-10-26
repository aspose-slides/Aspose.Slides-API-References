---
title: TextFrameFormat class
second_title: Aspose.Slides para Python via .NET Referência da API
description: 
type: docs
url: /pt/aspose.slides/textframeformat/
---
## TextFrameFormat classe

Contém as propriedades formatTextFrameFormatting do TextFrame.

**Herança:**[`TextFrameFormat`](/slides/python-net/pt/aspose.slides/textframeformat) → [`PVIObject`](/slides/python-net/pt/aspose.slides/pviobject)

O tipo TextFrameFormat expõe os seguintes membros:

## Construtores

| Construtor | Descrição |
| :- | :- |
| [`__init__(self)`](/slides/python-net/pt/aspose.slides/textframeformat/__init__/#) | Inicializa uma nova instância da classe [`TextFrameFormat`](/slides/python-net/pt/aspose.slides/textframeformat). |

## Propriedades

| Propriedade | Descrição |
| :- | :- |
| [`three_d_format`](/slides/python-net/pt/aspose.slides/textframeformat/three_d_format/) | Retorna o objeto ThreeDFormat que representa as propriedades de efeito 3d para um texto.<br/>            Somente leitura [`IThreeDFormat`](/slides/python-net/pt/aspose.slides/ithreedformat). |
| [`margin_left`](/slides/python-net/pt/aspose.slides/textframeformat/margin_left/) | Retorna ou define a margem esquerda (pontos) em um TextFrame.<br/>            Leitura/gravação **float**. |
| [`margin_right`](/slides/python-net/pt/aspose.slides/textframeformat/margin_right/) | Retorna ou define a margem direita (pontos) em um TextFrame.<br/>            Leitura/gravação **float**. |
| [`margin_top`](/slides/python-net/pt/aspose.slides/textframeformat/margin_top/) | Retorna ou define a margem superior (pontos) em um TextFrame.<br/>            Leitura/gravação **float**. |
| [`margin_bottom`](/slides/python-net/pt/aspose.slides/textframeformat/margin_bottom/) | Retorna ou define a margem inferior (pontos) em um TextFrame.<br/>            Leitura/gravação **float**. |
| [`wrap_text`](/slides/python-net/pt/aspose.slides/textframeformat/wrap_text/) | **True** se o texto for ajustado nas margens do TextFrame.<br/>            Leitura/gravação [`NullableBool`](/slides/python-net/pt/aspose.slides/nullablebool). |
| [`anchoring_type`](/slides/python-net/pt/aspose.slides/textframeformat/anchoring_type/) | Retorna ou define o texto de âncora vertical em um TextFrame.<br/>            Leitura/gravação [`TextAnchorType`](/slides/python-net/pt/aspose.slides/textanchortype). |
| [`center_text`](/slides/python-net/pt/aspose.slides/textframeformat/center_text/) | Se NullableBool.True então o texto deve ser centralizado horizontalmente na caixa.<br/>            Leitura/gravação [`NullableBool`](/slides/python-net/pt/aspose.slides/nullablebool). |
| [`text_vertical_type`](/slides/python-net/pt/aspose.slides/textframeformat/text_vertical_type/) | Determina a orientação do texto.<br/>            O valor resultante da rotação visual do texto resumido a partir desta propriedade e do ângulo personalizado<br/>            na propriedade RotationAngle.<br/>            Leitura/gravação [`TextVerticalType`](/slides/python-net/pt/aspose.slides/textverticaltype). |
| [`autofit_type`](/slides/python-net/pt/aspose.slides/textframeformat/autofit_type/) | Retorna ou define o modo de ajuste automático do texto.<br/>            Leitura/gravação [`TextAutofitType`](/slides/python-net/pt/aspose.slides/textautofittype). |
| [`column_count`](/slides/python-net/pt/aspose.slides/textframeformat/column_count/) | Retorna ou define o número de colunas na área de texto.<br/>            Este valor deve ser um número positivo. Caso contrário, o valor será definido como zero.<br/>            Valor 0 significa valor indefinido.<br/>            Leitura/gravação **int**. |
| [`column_spacing`](/slides/python-net/pt/aspose.slides/textframeformat/column_spacing/) | Retorna ou define o espaço entre as colunas de texto na área de texto (em pontos). Isso deve ser aplicado apenas <br/>            quando houver mais de 1 coluna presente.<br/>            Este valor deve ser um número positivo. Caso contrário, o valor será definido como zero.<br/>            Leitura/gravação **float**. |
| [`rotation_angle`](/slides/python-net/pt/aspose.slides/textframeformat/rotation_angle/) | Especifica a rotação personalizada que está sendo aplicada ao texto dentro da caixa delimitadora. Se não<br/>            for especificada, a rotação da forma associada será usada. Se for especificada, então isso será<br/>            aplicado independentemente da forma. Ou seja, a forma pode ter uma rotação aplicada em<br/>            adição à rotação aplicada ao próprio texto.<br/>            O valor resultante da rotação visual do texto resumido a partir desta propriedade e do tipo<br/>            vertical predefinido na propriedade TextVerticalType.<br/>            Leitura/gravação **float**. |
| [`transform`](/slides/python-net/pt/aspose.slides/textframeformat/transform/) | Obtém ou define a forma de quebra de texto.<br/>            Leitura/gravação [`TextShapeType`](/slides/python-net/pt/aspose.slides/textshapetype). |
| [`keep_text_flat`](/slides/python-net/pt/aspose.slides/textframeformat/keep_text_flat/) | Obtém ou define a manutenção do texto plano mesmo se um efeito de Rotação 3-D foi aplicado.<br/>            Leitura/gravação **bool**. |
| [`slide`](/slides/python-net/pt/aspose.slides/textframeformat/slide/) |  |
| [`presentation`](/slides/python-net/pt/aspose.slides/textframeformat/presentation/) |  |
| [`text_style`](/slides/python-net/pt/aspose.slides/textframeformat/text_style/) |  |

## Métodos

| Método | Descrição |
| :- | :- |
| [`get_effective(self)`](/slides/python-net/pt/aspose.slides/textframeformat/get_effective/#) | Obtém os dados efetivos de formatação do quadro de texto com a herança aplicada. |

### Veja Também
* classe [`PVIObject`](/slides/python-net/pt/aspose.slides/pviobject)
* classe [`TextFrameFormat`](/slides/python-net/pt/aspose.slides/textframeformat)
* módulo [`aspose.slides`](/slides/python-net/pt/aspose.slides)
* biblioteca [`Aspose.Slides`](/slides/python-net)