---
title: IBasePortionFormatEffectiveData class
second_title: Aspose.Slides para Python via .NET Referência de API
description: 
type: docs
url: /pt/aspose.slides/ibaseportionformateffectivedata/
---
## IBasePortionFormatEffectiveData classe

Base interface for immutable objects which contain effective text portion formatting properties.

The IBasePortionFormatEffectiveData type exposes the following members:

## Propriedades

| Propriedade | Descrição |
| :- | :- |
| [`line_format`](/slides/python-net/pt/aspose.slides/ibaseportionformateffectivedata/line_format/) | Retorna as propriedades LineFormat para contorno de texto.<br/>            Somente leitura [`ILineFormatEffectiveData`](/slides/python-net/pt/aspose.slides/ilineformateffectivedata). |
| [`fill_format`](/slides/python-net/pt/aspose.slides/ibaseportionformateffectivedata/fill_format/) | Retorna as propriedades FillFormat do texto.<br/>            Somente leitura [`IFillFormatEffectiveData`](/slides/python-net/pt/aspose.slides/ifillformateffectivedata). |
| [`effect_format`](/slides/python-net/pt/aspose.slides/ibaseportionformateffectivedata/effect_format/) | Retorna as propriedades EffectFormat do texto.<br/>            Somente leitura [`IEffectFormatEffectiveData`](/slides/python-net/pt/aspose.slides/ieffectformateffectivedata). |
| [`highlight_color`](/slides/python-net/pt/aspose.slides/ibaseportionformateffectivedata/highlight_color/) | Retorna a cor usada para destacar um texto.<br/>            Somente leitura **aspose.slides.Color**. |
| [`underline_line_format`](/slides/python-net/pt/aspose.slides/ibaseportionformateffectivedata/underline_line_format/) | Retorna as propriedades LineFormat usadas para contornar a linha de sublinhado.<br/>            Somente leitura [`ILineFormatEffectiveData`](/slides/python-net/pt/aspose.slides/ilineformateffectivedata). |
| [`underline_fill_format`](/slides/python-net/pt/aspose.slides/ibaseportionformateffectivedata/underline_fill_format/) | Retorna as propriedades FillFormat da linha de sublinhado.<br/>            Somente leitura [`IFillFormatEffectiveData`](/slides/python-net/pt/aspose.slides/ifillformateffectivedata). |
| [`font_bold`](/slides/python-net/pt/aspose.slides/ibaseportionformateffectivedata/font_bold/) | Determina se a fonte está em negrito.<br/>            Somente leitura **bool**. |
| [`font_italic`](/slides/python-net/pt/aspose.slides/ibaseportionformateffectivedata/font_italic/) | Determina se a fonte está em itálico.<br/>            Somente leitura **bool**. |
| [`kumimoji`](/slides/python-net/pt/aspose.slides/ibaseportionformateffectivedata/kumimoji/) | Determina se os números devem ignorar o layout de texto vertical específico de idiomas orientais.<br/>            Somente leitura **bool**. |
| [`normalise_height`](/slides/python-net/pt/aspose.slides/ibaseportionformateffectivedata/normalise_height/) | Determina se a altura de um texto deve ser normalizada.<br/>            Somente leitura **bool**. |
| [`proof_disabled`](/slides/python-net/pt/aspose.slides/ibaseportionformateffectivedata/proof_disabled/) | Determina se o texto não deve ser revisado.<br/>            Somente leitura **bool**. |
| [`font_underline`](/slides/python-net/pt/aspose.slides/ibaseportionformateffectivedata/font_underline/) | Retorna o tipo de sublinhado do texto.<br/>            Somente leitura [`TextUnderlineType`](/slides/python-net/pt/aspose.slides/textunderlinetype). |
| [`text_cap_type`](/slides/python-net/pt/aspose.slides/ibaseportionformateffectivedata/text_cap_type/) | Retorna o tipo de capitalização do texto.<br/>            Somente leitura [`TextCapType`](/slides/python-net/pt/aspose.slides/textcaptype). |
| [`strikethrough_type`](/slides/python-net/pt/aspose.slides/ibaseportionformateffectivedata/strikethrough_type/) | Retorna o tipo de tachado de um texto.<br/>            Somente leitura [`TextStrikethroughType`](/slides/python-net/pt/aspose.slides/textstrikethroughtype). |
| [`smart_tag_clean`](/slides/python-net/pt/aspose.slides/ibaseportionformateffectivedata/smart_tag_clean/) | Determina se a smart tag deve ser limpa.<br/>            Somente leitura **bool**. |
| [`is_hard_underline_line`](/slides/python-net/pt/aspose.slides/ibaseportionformateffectivedata/is_hard_underline_line/) | Determina se o estilo de sublinhado possui próprias propriedades LineFormat ou as herda das propriedades LineFormat do texto.<br/>            Somente leitura **bool**. |
| [`is_hard_underline_fill`](/slides/python-net/pt/aspose.slides/ibaseportionformateffectivedata/is_hard_underline_fill/) | Determina se o estilo de sublinhado possui próprias propriedades FillFormat ou as herda das propriedades FillFormat do texto.<br/>            Somente leitura **bool**. |
| [`font_height`](/slides/python-net/pt/aspose.slides/ibaseportionformateffectivedata/font_height/) | Retorna a altura da fonte da parte do texto, em pontos.<br/>            Somente leitura **float**. |
| [`latin_font`](/slides/python-net/pt/aspose.slides/ibaseportionformateffectivedata/latin_font/) | Retorna as informações da fonte latina.<br/>            Somente leitura [`IFontData`](/slides/python-net/pt/aspose.slides/ifontdata). |
| [`east_asian_font`](/slides/python-net/pt/aspose.slides/ibaseportionformateffectivedata/east_asian_font/) | Retorna as informações da fonte Leste Asiático.<br/>            Somente leitura [`IFontData`](/slides/python-net/pt/aspose.slides/ifontdata). |
| [`complex_script_font`](/slides/python-net/pt/aspose.slides/ibaseportionformateffectivedata/complex_script_font/) | Retorna as informações da fonte de script complexo.<br/>            Somente leitura [`IFontData`](/slides/python-net/pt/aspose.slides/ifontdata). |
| [`symbol_font`](/slides/python-net/pt/aspose.slides/ibaseportionformateffectivedata/symbol_font/) | Retorna as informações da fonte simbólica.<br/>            Somente leitura [`IFontData`](/slides/python-net/pt/aspose.slides/ifontdata). |
| [`escapement`](/slides/python-net/pt/aspose.slides/ibaseportionformateffectivedata/escapement/) | Retorna o texto sobrescrito ou subscrito.<br/>            Valor de -100% (subscrito) a 100% (sobrescrito).<br/>            Somente leitura **float**. |
| [`kerning_minimal_size`](/slides/python-net/pt/aspose.slides/ibaseportionformateffectivedata/kerning_minimal_size/) | Retorna o tamanho mínimo da fonte, para o qual o kerning deve ser ativado.<br/>            Somente leitura **float**. |
| [`language_id`](/slides/python-net/pt/aspose.slides/ibaseportionformateffectivedata/language_id/) | Retorna o Id de um idioma.<br/>            Somente leitura **str**. |
| [`alternative_language_id`](/slides/python-net/pt/aspose.slides/ibaseportionformateffectivedata/alternative_language_id/) | Retorna o Id de um idioma alternativo.<br/>            Somente leitura **str**. |
| [`spacing`](/slides/python-net/pt/aspose.slides/ibaseportionformateffectivedata/spacing/) | Retorna o incremento de espaçamento intercaractere, em pontos.<br/>            Somente leitura **float**. |

### Veja Também
* módulo [`aspose.slides`](/slides/python-net/pt/aspose.slides)
* biblioteca [`Aspose.Slides`](/slides/python-net)