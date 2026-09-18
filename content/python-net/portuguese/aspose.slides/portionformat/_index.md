---
title: PortionFormat class
second_title: Aspose.Slides para Python via .NET Referência de API
description: 
type: docs
url: /pt/aspose.slides/portionformat/
---
## PortionFormat classe

Esta classe contém as propriedades de formatação de porção de texto. Ao contrário de [`IPortionFormatEffectiveData`](/slides/python-net/pt/aspose.slides/iportionformateffectivedata), todas as propriedades desta classe são graváveis.

**Herança:**[`PortionFormat`](/slides/python-net/pt/aspose.slides/portionformat) → [`BasePortionFormat`](/slides/python-net/pt/aspose.slides/baseportionformat) → [`PVIObject`](/slides/python-net/pt/aspose.slides/pviobject)

O tipo PortionFormat expõe os seguintes membros:

## Construtores

| Construtor | Descrição |
| :- | :- |
| [`__init__(self)`](/slides/python-net/pt/aspose.slides/portionformat/__init__/#) | Inicializa uma nova instância da classe [`PortionFormat`](/slides/python-net/pt/aspose.slides/portionformat). |

## Propriedades

| Propriedade | Descrição |
| :- | :- |
| [`line_format`](/slides/python-net/pt/aspose.slides/portionformat/line_format/) | Retorna as propriedades LineFormat para contorno de texto. Nenhuma herança aplicada.<br/>            Somente leitura [`ILineFormat`](/slides/python-net/pt/aspose.slides/ilineformat). |
| [`fill_format`](/slides/python-net/pt/aspose.slides/portionformat/fill_format/) | Retorna as propriedades FillFormat do texto. Nenhuma herança aplicada.<br/>            Somente leitura [`IFillFormat`](/slides/python-net/pt/aspose.slides/ifillformat). |
| [`effect_format`](/slides/python-net/pt/aspose.slides/portionformat/effect_format/) | Retorna as propriedades EffectFormat do texto. Nenhuma herança aplicada.<br/>            Somente leitura [`IEffectFormat`](/slides/python-net/pt/aspose.slides/ieffectformat). |
| [`highlight_color`](/slides/python-net/pt/aspose.slides/portionformat/highlight_color/) | Retorna a cor usada para realçar um texto. Nenhuma herança aplicada.<br/>            Somente leitura [`IColorFormat`](/slides/python-net/pt/aspose.slides/icolorformat). |
| [`underline_line_format`](/slides/python-net/pt/aspose.slides/portionformat/underline_line_format/) | Retorna as propriedades LineFormat usadas para contornar a linha de sublinhado. Nenhuma herança aplicada.<br/>            Somente leitura [`ILineFormat`](/slides/python-net/pt/aspose.slides/ilineformat). |
| [`underline_fill_format`](/slides/python-net/pt/aspose.slides/portionformat/underline_fill_format/) | Retorna as propriedades FillFormat da linha de sublinhado. Nenhuma herança aplicada.<br/>            Somente leitura [`IFillFormat`](/slides/python-net/pt/aspose.slides/ifillformat). |
| [`font_bold`](/slides/python-net/pt/aspose.slides/portionformat/font_bold/) | Determina se a fonte está em negrito. Nenhuma herança aplicada.<br/>            Leitura/Gravação [`NullableBool`](/slides/python-net/pt/aspose.slides/nullablebool). |
| [`font_italic`](/slides/python-net/pt/aspose.slides/portionformat/font_italic/) | Determina se a fonte está em itálico. Nenhuma herança aplicada.<br/>            Leitura/Gravação [`NullableBool`](/slides/python-net/pt/aspose.slides/nullablebool). |
| [`kumimoji`](/slides/python-net/pt/aspose.slides/portionformat/kumimoji/) | Determina se os números devem ignorar o layout de texto vertical específico de idioma oriental. Nenhuma herança aplicada.<br/>            Leitura/Gravação [`NullableBool`](/slides/python-net/pt/aspose.slides/nullablebool). |
| [`normalise_height`](/slides/python-net/pt/aspose.slides/portionformat/normalise_height/) | Determina se a altura de um texto deve ser normalizada. Nenhuma herança aplicada.<br/>            Leitura/Gravação [`NullableBool`](/slides/python-net/pt/aspose.slides/nullablebool). |
| [`proof_disabled`](/slides/python-net/pt/aspose.slides/portionformat/proof_disabled/) | Determina se o texto não deve ser revisado. Nenhuma herança aplicada.<br/>            Leitura/Gravação [`NullableBool`](/slides/python-net/pt/aspose.slides/nullablebool). |
| [`font_underline`](/slides/python-net/pt/aspose.slides/portionformat/font_underline/) | Retorna ou define o tipo de sublinhado de texto. Nenhuma herança aplicada.<br/>            Leitura/Gravação [`TextUnderlineType`](/slides/python-net/pt/aspose.slides/textunderlinetype). |
| [`text_cap_type`](/slides/python-net/pt/aspose.slides/portionformat/text_cap_type/) | Retorna ou define o tipo de capitalização de texto. Nenhuma herança aplicada.<br/>            Leitura/Gravação [`TextCapType`](/slides/python-net/pt/aspose.slides/textcaptype). |
| [`strikethrough_type`](/slides/python-net/pt/aspose.slides/portionformat/strikethrough_type/) | Retorna ou define o tipo de tachado de um texto. Nenhuma herança aplicada.<br/>            Leitura/Gravação [`TextStrikethroughType`](/slides/python-net/pt/aspose.slides/textstrikethroughtype). |
| [`is_hard_underline_line`](/slides/python-net/pt/aspose.slides/portionformat/is_hard_underline_line/) | Determina se o estilo de sublinhado possui propriedades LineFormat próprias ou herda-as das propriedades LineFormat do texto.<br/>            Leitura/Gravação [`NullableBool`](/slides/python-net/pt/aspose.slides/nullablebool). |
| [`is_hard_underline_fill`](/slides/python-net/pt/aspose.slides/portionformat/is_hard_underline_fill/) | Determina se o estilo de sublinhado possui propriedades FillFormat próprias ou herda-as das propriedades FillFormat do texto.<br/>            Leitura/Gravação [`NullableBool`](/slides/python-net/pt/aspose.slides/nullablebool). |
| [`font_height`](/slides/python-net/pt/aspose.slides/portionformat/font_height/) | Retorna ou define a altura da fonte de uma porção.<br/>            **float.NaN**  significa que a altura está indefinida e deve ser herdada do Master.<br/>            Leitura/Gravação **float**. |
| [`latin_font`](/slides/python-net/pt/aspose.slides/portionformat/latin_font/) | Retorna ou define as informações da fonte Latina.<br/>            Null significa que a fonte está indefinida e deve ser herdada do Master.<br/>            Leitura/Gravação [`IFontData`](/slides/python-net/pt/aspose.slides/ifontdata). |
| [`east_asian_font`](/slides/python-net/pt/aspose.slides/portionformat/east_asian_font/) | Retorna ou define as informações da fonte do Leste Asiático.<br/>            Null significa que a fonte está indefinida e deve ser herdada do Master.<br/>            Leitura/Gravação [`IFontData`](/slides/python-net/pt/aspose.slides/ifontdata). |
| [`complex_script_font`](/slides/python-net/pt/aspose.slides/portionformat/complex_script_font/) | Retorna ou define as informações da fonte de script complexo.<br/>            Null significa que a fonte está indefinida e deve ser herdada do Master.<br/>            Leitura/Gravação [`IFontData`](/slides/python-net/pt/aspose.slides/ifontdata). |
| [`symbol_font`](/slides/python-net/pt/aspose.slides/portionformat/symbol_font/) | Retorna ou define as informações da fonte simbólica.<br/>            Null significa que a fonte está indefinida e deve ser herdada do Master.<br/>            Leitura/Gravação [`IFontData`](/slides/python-net/pt/aspose.slides/ifontdata). |
| [`escapement`](/slides/python-net/pt/aspose.slides/portionformat/escapement/) | Retorna ou define o texto sobrescrito ou subscrito.<br/>            Valor de -100% (subscrito) a 100% (sobrescrito).<br/>            **float.NaN**  significa que o valor está indefinido e deve ser herdado do Master.<br/>            Leitura/Gravação **float**. |
| [`kerning_minimal_size`](/slides/python-net/pt/aspose.slides/portionformat/kerning_minimal_size/) | Retorna ou define o tamanho mínimo da fonte, para o qual o kerning deve ser ativado.<br/>            **float.NaN**  significa que o valor está indefinido e deve ser herdado do Master.<br/>            Leitura/Gravação **float**. |
| [`language_id`](/slides/python-net/pt/aspose.slides/portionformat/language_id/) | Retorna ou define o Id de um idioma de revisão. Usado para verificação ortográfica e gramatical.<br/>            Leitura/Gravação **str**. |
| [`alternative_language_id`](/slides/python-net/pt/aspose.slides/portionformat/alternative_language_id/) | Retorna ou define o Id de um idioma alternativo.<br/>            Leitura/Gravação **str**. |
| [`spacing`](/slides/python-net/pt/aspose.slides/portionformat/spacing/) | Retorna ou define o incremento de espaçamento entre caracteres.<br/>            **float.NaN**  significa que o valor está indefinido e deve ser herdado do Master.<br/>            Leitura/Gravação **float**. |
| [`spell_check`](/slides/python-net/pt/aspose.slides/portionformat/spell_check/) | Obtém ou define um valor que indica se a verificação ortográfica está habilitada para a porção de texto.<br/>            Quando esta propriedade está definida como false, as verificações ortográficas para elementos de texto são suprimidas.<br/>            Quando definido como true, a verificação ortográfica é permitida.<br/>            Valor padrão é `false`. |
| [`bookmark_id`](/slides/python-net/pt/aspose.slides/portionformat/bookmark_id/) | Retorna ou define o identificador de marcador.<br/>            Leitura/Gravação **str**. |
| [`smart_tag_clean`](/slides/python-net/pt/aspose.slides/portionformat/smart_tag_clean/) | Determina se a smart tag deve ser limpa. Nenhuma herança aplicada.<br/>            Leitura/Gravação **bool**. |
| [`hyperlink_click`](/slides/python-net/pt/aspose.slides/portionformat/hyperlink_click/) | Retorna ou define o hyperlink definido para clique do mouse.<br/>            Leitura/Gravação [`IHyperlink`](/slides/python-net/pt/aspose.slides/ihyperlink). |
| [`hyperlink_mouse_over`](/slides/python-net/pt/aspose.slides/portionformat/hyperlink_mouse_over/) | Retorna ou define o hyperlink definido para passar o mouse.<br/>            Leitura/Gravação [`IHyperlink`](/slides/python-net/pt/aspose.slides/ihyperlink). |
| [`hyperlink_manager`](/slides/python-net/pt/aspose.slides/portionformat/hyperlink_manager/) | Gerenciador de hyperlinks.<br/>            Somente leitura [`IHyperlinkManager`](/slides/python-net/pt/aspose.slides/ihyperlinkmanager). |
| [`slide`](/slides/python-net/pt/aspose.slides/portionformat/slide/) |  |
| [`presentation`](/slides/python-net/pt/aspose.slides/portionformat/presentation/) |  |

## Métodos

| Método | Descrição |
| :- | :- |
| [`get_effective(self)`](/slides/python-net/pt/aspose.slides/portionformat/get_effective/#) | Obtém os dados de formatação de porção efetivos com a herança aplicada. |

### Observações

Esta classe é usada para retornar e manipular as propriedades de formatação de porção de texto definidas para a porção específica. Isso significa que nenhuma herança é aplicada ao obter valores, portanto, na maioria dos casos você receberá valores significando "indefinido".

Para obter os valores dos parâmetros de formatação efetivos, incluindo os herdados, você precisa usar o método [`PortionFormat.get_effective`](/slides/python-net/pt/aspose.slides/portionformat/get_effective) que retorna uma instância [`IPortionFormatEffectiveData`](/slides/python-net/pt/aspose.slides/iportionformateffectivedata).

### Veja também
* classe [`BasePortionFormat`](/slides/python-net/pt/aspose.slides/baseportionformat)
* classe [`IPortionFormatEffectiveData`](/slides/python-net/pt/aspose.slides/iportionformateffectivedata)
* classe [`PortionFormat`](/slides/python-net/pt/aspose.slides/portionformat)
* classe [`PVIObject`](/slides/python-net/pt/aspose.slides/pviobject)
* módulo [`aspose.slides`](/slides/python-net/pt/aspose.slides)
* biblioteca [`Aspose.Slides`](/slides/python-net)