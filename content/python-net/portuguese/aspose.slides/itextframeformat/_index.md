---
title: ITextFrameFormat class
second_title: Referência da API Aspose.Slides para Python via .NET
description: 
type: docs
url: /pt/aspose.slides/itextframeformat/
---
## ITextFrameFormat classe

Contém as propriedades de formatação do TextFrame.

O tipo ITextFrameFormat expõe os seguintes membros:

## Propriedades

| Propriedade | Descrição |
| :- | :- |
| [`text_style`](/slides/python-net/pt/aspose.slides/itextframeformat/text_style/) | Retorna o estilo do texto.<br/>            Somente leitura [`ITextStyle`](/slides/python-net/pt/aspose.slides/itextstyle). |
| [`margin_left`](/slides/python-net/pt/aspose.slides/itextframeformat/margin_left/) | Retorna ou define a margem esquerda (pontos) em um TextFrame.<br/>            Leitura/gravação **float**. |
| [`margin_right`](/slides/python-net/pt/aspose.slides/itextframeformat/margin_right/) | Retorna ou define a margem direita (pontos) em um TextFrame.<br/>            Leitura/gravação **float**. |
| [`margin_top`](/slides/python-net/pt/aspose.slides/itextframeformat/margin_top/) | Retorna ou define a margem superior (pontos) em um TextFrame.<br/>            Leitura/gravação **float**. |
| [`margin_bottom`](/slides/python-net/pt/aspose.slides/itextframeformat/margin_bottom/) | Retorna ou define a margem inferior (pontos) em um TextFrame.<br/>            Leitura/gravação **float**. |
| [`wrap_text`](/slides/python-net/pt/aspose.slides/itextframeformat/wrap_text/) | **True** se o texto for quebrado nas margens do TextFrame.<br/>            Leitura/gravação [`NullableBool`](/slides/python-net/pt/aspose.slides/nullablebool). |
| [`anchoring_type`](/slides/python-net/pt/aspose.slides/itextframeformat/anchoring_type/) | Retorna ou define o texto de âncora vertical em um TextFrame.<br/>            Leitura/gravação [`TextAnchorType`](/slides/python-net/pt/aspose.slides/textanchortype). |
| [`center_text`](/slides/python-net/pt/aspose.slides/itextframeformat/center_text/) | Se NullableBool.True então o texto deve ser centralizado horizontalmente na caixa.<br/>            Leitura/gravação [`NullableBool`](/slides/python-net/pt/aspose.slides/nullablebool). |
| [`text_vertical_type`](/slides/python-net/pt/aspose.slides/itextframeformat/text_vertical_type/) | Determina a orientação do texto.<br/>            O valor resultante da rotação visual do texto resumido a partir desta propriedade e do ângulo personalizado<br/>            na propriedade RotationAngle.<br/>            Leitura/gravação [`TextVerticalType`](/slides/python-net/pt/aspose.slides/textverticaltype). |
| [`autofit_type`](/slides/python-net/pt/aspose.slides/itextframeformat/autofit_type/) | Retorna ou define o modo de ajuste automático do texto.<br/>            Leitura/gravação [`TextAutofitType`](/slides/python-net/pt/aspose.slides/textautofittype). |
| [`column_count`](/slides/python-net/pt/aspose.slides/itextframeformat/column_count/) | Retorna ou define o número de colunas na área de texto.<br/>            Este valor deve ser um número positivo. Caso contrário, o valor será definido como zero. <br/>            Valor 0 significa valor indefinido.<br/>            Leitura/gravação **int**. |
| [`column_spacing`](/slides/python-net/pt/aspose.slides/itextframeformat/column_spacing/) | Retorna ou define o espaço entre colunas de texto na área de texto (em pontos). Isso deve ser aplicado apenas <br/>            quando há mais de 1 coluna presente.<br/>            Este valor deve ser um número positivo. Caso contrário, o valor será definido como zero. <br/>            Leitura/gravação **float**. |
| [`three_d_format`](/slides/python-net/pt/aspose.slides/itextframeformat/three_d_format/) | Retorna o objeto ThreeDFormat que representa as propriedades de efeito 3d para um texto.<br/>            Somente leitura [`IThreeDFormat`](/slides/python-net/pt/aspose.slides/ithreedformat). |
| [`keep_text_flat`](/slides/python-net/pt/aspose.slides/itextframeformat/keep_text_flat/) | Retorna ou define a manutenção do texto fora da cena 3D totalmente.<br/>            Leitura/gravação **bool**. |
| [`rotation_angle`](/slides/python-net/pt/aspose.slides/itextframeformat/rotation_angle/) | Especifica a rotação personalizada que está sendo aplicada ao texto dentro da caixa delimitadora. Se não<br/>            for especificado, a rotação da forma associada é usada. Se for especificado, então isto é<br/>            aplicado independentemente da forma. Ou seja, a forma pode ter uma rotação aplicada <br/>            além da rotação aplicada ao próprio texto.<br/>            O valor resultante da rotação visual do texto resumido a partir desta propriedade e do tipo vertical pré-definido na propriedade TextVerticalType.<br/>            Leitura/gravação **float**. |
| [`transform`](/slides/python-net/pt/aspose.slides/itextframeformat/transform/) | Retorna ou define a forma de quebra de texto.<br/>            Leitura/gravação [`TextShapeType`](/slides/python-net/pt/aspose.slides/textshapetype). |

## Métodos

| Método | Descrição |
| :- | :- |
| [`get_effective(self)`](/slides/python-net/pt/aspose.slides/itextframeformat/get_effective/#) | Obtém os dados de formatação efetiva do quadro de texto com a herança aplicada. |

### Veja Também
* módulo [`aspose.slides`](/slides/python-net/pt/aspose.slides)
* biblioteca [`Aspose.Slides`](/slides/python-net)