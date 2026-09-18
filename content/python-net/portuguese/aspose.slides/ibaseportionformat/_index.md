---
title: IBasePortionFormat class
second_title: Aspose.Slides para Python via .NET Referência de API
description: 
type: docs
url: /pt/aspose.slides/ibaseportionformat/
---
## IBasePortionFormat classe

Esta classe contém as propriedades de formatação da porção de texto. Ao contrário de [`IPortionFormatEffectiveData`](/slides/python-net/pt/aspose.slides/iportionformateffectivedata), todas as propriedades desta classe são graváveis.

O tipo IBasePortionFormat expõe os seguintes membros:

## Propriedades

| Propriedade | Descrição |
| :- | :- |
| [`line_format`](/slides/python-net/pt/aspose.slides/ibaseportionformat/line_format/) | Retorna as propriedades LineFormat para contorno de texto. Nenhuma herança aplicada.<br/>            Somente leitura [`ILineFormat`](/slides/python-net/pt/aspose.slides/ilineformat). |
| [`fill_format`](/slides/python-net/pt/aspose.slides/ibaseportionformat/fill_format/) | Retorna as propriedades FillFormat do texto. Nenhuma herança aplicada.<br/>            Somente leitura [`IFillFormat`](/slides/python-net/pt/aspose.slides/ifillformat). |
| [`effect_format`](/slides/python-net/pt/aspose.slides/ibaseportionformat/effect_format/) | Retorna as propriedades EffectFormat do texto. Nenhuma herança aplicada.<br/>            Somente leitura [`IEffectFormat`](/slides/python-net/pt/aspose.slides/ieffectformat). |
| [`highlight_color`](/slides/python-net/pt/aspose.slides/ibaseportionformat/highlight_color/) | Retorna a cor usada para realçar um texto. Nenhuma herança aplicada.<br/>            Somente leitura [`IColorFormat`](/slides/python-net/pt/aspose.slides/icolorformat). |
| [`underline_line_format`](/slides/python-net/pt/aspose.slides/ibaseportionformat/underline_line_format/) | Retorna as propriedades LineFormat usadas para contornar a linha de sublinhado. Nenhuma herança aplicada.<br/>            Somente leitura [`ILineFormat`](/slides/python-net/pt/aspose.slides/ilineformat). |
| [`underline_fill_format`](/slides/python-net/pt/aspose.slides/ibaseportionformat/underline_fill_format/) | Retorna as propriedades FillFormat da linha de sublinhado. Nenhuma herança aplicada.<br/>            Somente leitura [`IFillFormat`](/slides/python-net/pt/aspose.slides/ifillformat). |
| [`font_bold`](/slides/python-net/pt/aspose.slides/ibaseportionformat/font_bold/) | Determina se a fonte está em negrito. Nenhuma herança aplicada.<br/>            Leitura/gravação [`NullableBool`](/slides/python-net/pt/aspose.slides/nullablebool). |
| [`font_italic`](/slides/python-net/pt/aspose.slides/ibaseportionformat/font_italic/) | Determina se a fonte está itálica. Nenhuma herança aplicada.<br/>            Leitura/gravação [`NullableBool`](/slides/python-net/pt/aspose.slides/nullablebool). |
| [`kumimoji`](/slides/python-net/pt/aspose.slides/ibaseportionformat/kumimoji/) | Determina se os números devem ignorar o layout vertical de texto específico de idiomas orientais. Nenhuma herança aplicada.<br/>            Leitura/gravação [`NullableBool`](/slides/python-net/pt/aspose.slides/nullablebool). |
| [`normalise_height`](/slides/python-net/pt/aspose.slides/ibaseportionformat/normalise_height/) | Determina se a altura de um texto deve ser normalizada. Nenhuma herança aplicada.<br/>            Leitura/gravação [`NullableBool`](/slides/python-net/pt/aspose.slides/nullablebool). |
| [`proof_disabled`](/slides/python-net/pt/aspose.slides/ibaseportionformat/proof_disabled/) | Determina se o texto não deve ser verificado ortograficamente. Nenhuma herança aplicada.<br/>            Leitura/gravação [`NullableBool`](/slides/python-net/pt/aspose.slides/nullablebool). |
| [`font_underline`](/slides/python-net/pt/aspose.slides/ibaseportionformat/font_underline/) | Retorna ou define o tipo de sublinhado do texto. Nenhuma herança aplicada.<br/>            Leitura/gravação [`TextUnderlineType`](/slides/python-net/pt/aspose.slides/textunderlinetype). |
| [`text_cap_type`](/slides/python-net/pt/aspose.slides/ibaseportionformat/text_cap_type/) | Retorna ou define o tipo de capitalização do texto. Nenhuma herança aplicada.<br/>            Leitura/gravação [`TextCapType`](/slides/python-net/pt/aspose.slides/textcaptype). |
| [`strikethrough_type`](/slides/python-net/pt/aspose.slides/ibaseportionformat/strikethrough_type/) | Retorna ou define o tipo de tachado do texto. Nenhuma herança aplicada.<br/>            Leitura/gravação [`TextStrikethroughType`](/slides/python-net/pt/aspose.slides/textstrikethroughtype). |
| [`is_hard_underline_line`](/slides/python-net/pt/aspose.slides/ibaseportionformat/is_hard_underline_line/) | Determina se o estilo de sublinhado tem propriedades LineFormat próprias ou as herda<br/>            das propriedades LineFormat do texto.<br/>            Leitura/gravação [`NullableBool`](/slides/python-net/pt/aspose.slides/nullablebool). |
| [`is_hard_underline_fill`](/slides/python-net/pt/aspose.slides/ibaseportionformat/is_hard_underline_fill/) | Determina se o estilo de sublinhado tem propriedades FillFormat próprias ou as herda<br/>            das propriedades FillFormat do texto.<br/>            Leitura/gravação [`NullableBool`](/slides/python-net/pt/aspose.slides/nullablebool). |
| [`font_height`](/slides/python-net/pt/aspose.slides/ibaseportionformat/font_height/) | Retorna ou define a altura da fonte de uma porção.<br/>            **float.NaN**  significa que a altura está indefinida e deve ser herdada do Mestre.<br/>            Leitura/gravação **float**. |
| [`latin_font`](/slides/python-net/pt/aspose.slides/ibaseportionformat/latin_font/) | Retorna ou define as informações da fonte Latina.<br/>            Null significa que a fonte está indefinida e deve ser herdada do Mestre.<br/>            Leitura/gravação [`IFontData`](/slides/python-net/pt/aspose.slides/ifontdata). |
| [`east_asian_font`](/slides/python-net/pt/aspose.slides/ibaseportionformat/east_asian_font/) | Retorna ou define as informações da fonte do Leste Asiático.<br/>            Null significa que a fonte está indefinida e deve ser herdada do Mestre.<br/>            Leitura/gravação [`IFontData`](/slides/python-net/pt/aspose.slides/ifontdata). |
| [`complex_script_font`](/slides/python-net/pt/aspose.slides/ibaseportionformat/complex_script_font/) | Retorna ou define as informações da fonte de script complexo.<br/>            Null significa que a fonte está indefinida e deve ser herdada do Mestre.<br/>            Leitura/gravação [`IFontData`](/slides/python-net/pt/aspose.slides/ifontdata). |
| [`symbol_font`](/slides/python-net/pt/aspose.slides/ibaseportionformat/symbol_font/) | Retorna ou define as informações da fonte simbólica.<br/>            Null significa que a fonte está indefinida e deve ser herdada do Mestre.<br/>            Leitura/gravação [`IFontData`](/slides/python-net/pt/aspose.slides/ifontdata). |
| [`escapement`](/slides/python-net/pt/aspose.slides/ibaseportionformat/escapement/) | Retorna ou define o texto sobrescrito ou subscrito.<br/>            Valor de -100% (subscrito) a 100% (sobrescrito).<br/>            **float.NaN**  significa que o valor está indefinido e deve ser herdado do Mestre.<br/>            Leitura/gravação **float**. |
| [`kerning_minimal_size`](/slides/python-net/pt/aspose.slides/ibaseportionformat/kerning_minimal_size/) | Retorna ou define o tamanho mínimo da fonte, para o qual o kerning deve ser ativado.<br/>            **float.NaN**  significa que o valor está indefinido e deve ser herdado do Mestre.<br/>            Leitura/gravação **float**. |
| [`language_id`](/slides/python-net/pt/aspose.slides/ibaseportionformat/language_id/) | Retorna ou define o Id de um idioma de verificação. Usado para checar ortografia e gramática.<br/>            Leitura/gravação **str**. |
| [`alternative_language_id`](/slides/python-net/pt/aspose.slides/ibaseportionformat/alternative_language_id/) | Retorna ou define o Id de um idioma alternativo.<br/>            Leitura/gravação **str**. |
| [`spacing`](/slides/python-net/pt/aspose.slides/ibaseportionformat/spacing/) | Retorna ou define o incremento de espaçamento entre caracteres.<br/>            **float.NaN**  significa que o valor está indefinido e deve ser herdado do Mestre.<br/>            Leitura/gravação **float**. |
| [`spell_check`](/slides/python-net/pt/aspose.slides/ibaseportionformat/spell_check/) | Obtém ou define um valor que indica se a verificação ortográfica está habilitada para a porção de texto.<br/>            Quando esta propriedade é definida como false, as verificações ortográficas para elementos de texto são suprimidas.<br/>            Quando definida como true, a verificação ortográfica é permitida.<br/>            O valor padrão é `false`. |


### Observações

Esta classe é usada para retornar e manipular as propriedades de formatação de porção de texto definidas para a porção específica. Isso significa que
            nenhuma herança é aplicada ao obter valores, portanto, na maioria dos casos você receberá valores significando "indefinido".


Para obter os valores efetivos dos parâmetros de formatação, incluindo os herdados, você precisa usar o método [`IPortionFormat.get_effective`](/slides/python-net/pt/aspose.slides/iportionformat/get_effective) 
            que retorna uma instância [`IPortionFormatEffectiveData`](/slides/python-net/pt/aspose.slides/iportionformateffectivedata).


### Veja Também
* classe [`IPortionFormatEffectiveData`](/slides/python-net/pt/aspose.slides/iportionformateffectivedata)
* módulo [`aspose.slides`](/slides/python-net/pt/aspose.slides)
* biblioteca [`Aspose.Slides`](/slides/python-net)