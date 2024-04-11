---
title: IPortionFormat
second_title: Aspose.Slides for Python via .NET API Reference
description: 
type: docs
url: /aspose.slides/iportionformat/
---


IPortionFormat class

This class contains the text portion formatting properties. Unlike [`IPortionFormatEffectiveData`](/slides/python-net/aspose.slides/iportionformateffectivedata), all properties of this class are writeable.

The IPortionFormat type exposes the following members:

## Properties

| Property | Description |
| :- | :- |
| [bookmark_id](/slides/python-net/aspose.slides/iportionformat/bookmark_id/) | Returns or sets bookmark identifier.<br/>            Read/write .NET type System.String. |
| [smart_tag_clean](/slides/python-net/aspose.slides/iportionformat/smart_tag_clean/) | Determines whether the smart tag should be cleaned. No inheritance applied.<br/>            Read/write .NET type System.Boolean. |
| [as_i_base_portion_format](/slides/python-net/aspose.slides/iportionformat/as_i_base_portion_format/) | Returns IBasePortionFormat interface.<br/>            Read-only [`IBasePortionFormat`](/slides/python-net/aspose.slides/ibaseportionformat). |
| [as_i_hyperlink_container](/slides/python-net/aspose.slides/iportionformat/as_i_hyperlink_container/) | Allows to get base IHyperlinkContainer interface.<br/>            Read-only [`IHyperlinkContainer`](/slides/python-net/aspose.slides/ihyperlinkcontainer). |
| [line_format](/slides/python-net/aspose.slides/iportionformat/line_format/) |  |
| [fill_format](/slides/python-net/aspose.slides/iportionformat/fill_format/) |  |
| [effect_format](/slides/python-net/aspose.slides/iportionformat/effect_format/) |  |
| [highlight_color](/slides/python-net/aspose.slides/iportionformat/highlight_color/) |  |
| [underline_line_format](/slides/python-net/aspose.slides/iportionformat/underline_line_format/) |  |
| [underline_fill_format](/slides/python-net/aspose.slides/iportionformat/underline_fill_format/) |  |
| [font_bold](/slides/python-net/aspose.slides/iportionformat/font_bold/) |  |
| [font_italic](/slides/python-net/aspose.slides/iportionformat/font_italic/) |  |
| [kumimoji](/slides/python-net/aspose.slides/iportionformat/kumimoji/) |  |
| [normalise_height](/slides/python-net/aspose.slides/iportionformat/normalise_height/) |  |
| [proof_disabled](/slides/python-net/aspose.slides/iportionformat/proof_disabled/) |  |
| [font_underline](/slides/python-net/aspose.slides/iportionformat/font_underline/) |  |
| [text_cap_type](/slides/python-net/aspose.slides/iportionformat/text_cap_type/) |  |
| [strikethrough_type](/slides/python-net/aspose.slides/iportionformat/strikethrough_type/) |  |
| [is_hard_underline_line](/slides/python-net/aspose.slides/iportionformat/is_hard_underline_line/) |  |
| [is_hard_underline_fill](/slides/python-net/aspose.slides/iportionformat/is_hard_underline_fill/) |  |
| [font_height](/slides/python-net/aspose.slides/iportionformat/font_height/) |  |
| [latin_font](/slides/python-net/aspose.slides/iportionformat/latin_font/) |  |
| [east_asian_font](/slides/python-net/aspose.slides/iportionformat/east_asian_font/) |  |
| [complex_script_font](/slides/python-net/aspose.slides/iportionformat/complex_script_font/) |  |
| [symbol_font](/slides/python-net/aspose.slides/iportionformat/symbol_font/) |  |
| [escapement](/slides/python-net/aspose.slides/iportionformat/escapement/) |  |
| [kerning_minimal_size](/slides/python-net/aspose.slides/iportionformat/kerning_minimal_size/) |  |
| [language_id](/slides/python-net/aspose.slides/iportionformat/language_id/) |  |
| [alternative_language_id](/slides/python-net/aspose.slides/iportionformat/alternative_language_id/) |  |
| [spacing](/slides/python-net/aspose.slides/iportionformat/spacing/) |  |
| [hyperlink_click](/slides/python-net/aspose.slides/iportionformat/hyperlink_click/) |  |
| [hyperlink_mouse_over](/slides/python-net/aspose.slides/iportionformat/hyperlink_mouse_over/) |  |
| [hyperlink_manager](/slides/python-net/aspose.slides/iportionformat/hyperlink_manager/) |  |

## Methods

| Method | Description |
| :- | :- |
| [get_effective](/slides/python-net/aspose.slides/iportionformat/get_effective/#/) | Gets effective portion formatting data with the inheritance applied. |


### Remarks

This class is used to return and manipulate text portion formatting properties defined for the particular portion. This means that
            no inheritance is applied when getting values so for the majority of cases you will get values meaning "undefined".


In order to get the effective formatting parameter values including inherited you need to use [`IPortionFormat.get_effective`](/slides/python-net/aspose.slides/iportionformat/get_effective) method 
            which returns a [`IPortionFormatEffectiveData`](/slides/python-net/aspose.slides/iportionformateffectivedata) instance.

