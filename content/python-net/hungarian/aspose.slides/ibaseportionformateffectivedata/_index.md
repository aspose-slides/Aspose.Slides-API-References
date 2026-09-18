---
title: IBasePortionFormatEffectiveData class
second_title: Aspose.Slides a Pythonhoz .NET-en keresztül API-referencia
description: 
type: docs
url: /hu/aspose.slides/ibaseportionformateffectivedata/
---
## IBasePortionFormatEffectiveData class

Az immutable objektumok alapvető interfésze, amelyek hatékony szövegrészlet-formázási tulajdonságokat tartalmaznak.

Az IBasePortionFormatEffectiveData típus a következő tagokat teszi elérhetővé:

## Properties

| Tulajdonság | Leírás |
| :- | :- |
| [`line_format`](/slides/python-net/hu/aspose.slides/ibaseportionformateffectivedata/line_format/) | Returns the LineFormat properties for text outlining.<br/>            Read-only [`ILineFormatEffectiveData`](/slides/python-net/hu/aspose.slides/ilineformateffectivedata). |
| [`fill_format`](/slides/python-net/hu/aspose.slides/ibaseportionformateffectivedata/fill_format/) | Returns the text FillFormat properties.<br/>            Read-only [`IFillFormatEffectiveData`](/slides/python-net/hu/aspose.slides/ifillformateffectivedata). |
| [`effect_format`](/slides/python-net/hu/aspose.slides/ibaseportionformateffectivedata/effect_format/) | Returns the text EffectFormat properties.<br/>            Read-only [`IEffectFormatEffectiveData`](/slides/python-net/hu/aspose.slides/ieffectformateffectivedata). |
| [`highlight_color`](/slides/python-net/hu/aspose.slides/ibaseportionformateffectivedata/highlight_color/) | Returns the color used to highlight a text.<br/>            Read-only **aspose.slides.Color**. |
| [`underline_line_format`](/slides/python-net/hu/aspose.slides/ibaseportionformateffectivedata/underline_line_format/) | Returns the LineFormat properties used to outline underline line.<br/>            Read-only [`ILineFormatEffectiveData`](/slides/python-net/hu/aspose.slides/ilineformateffectivedata). |
| [`underline_fill_format`](/slides/python-net/hu/aspose.slides/ibaseportionformateffectivedata/underline_fill_format/) | Returns the underline line FillFormat properties.<br/>            Read-only [`IFillFormatEffectiveData`](/slides/python-net/hu/aspose.slides/ifillformateffectivedata). |
| [`font_bold`](/slides/python-net/hu/aspose.slides/ibaseportionformateffectivedata/font_bold/) | Megállapítja, hogy a betűkészlet félkövér-e.<br/>            Read-only **bool**. |
| [`font_italic`](/slides/python-net/hu/aspose.slides/ibaseportionformateffectivedata/font_italic/) | Megállapítja, hogy a betűkészlet dőlt-e.<br/>            Read-only **bool**. |
| [`kumimoji`](/slides/python-net/hu/aspose.slides/ibaseportionformateffectivedata/kumimoji/) | Megállapítja, hogy a számok figyelmen kívül hagyják-e a szöveg keleti nyelv-specifikus függőleges elrendezését.<br/>            Read-only **bool**. |
| [`normalise_height`](/slides/python-net/hu/aspose.slides/ibaseportionformateffectivedata/normalise_height/) | Megállapítja, hogy a szöveg magassága normalizálandó-e.<br/>            Read-only **bool**. |
| [`proof_disabled`](/slides/python-net/hu/aspose.slides/ibaseportionformateffectivedata/proof_disabled/) | Megállapítja, hogy a szöveget ne kell-e lektorálni.<br/>            Read-only **bool**. |
| [`font_underline`](/slides/python-net/hu/aspose.slides/ibaseportionformateffectivedata/font_underline/) | Returns the text underline type.<br/>            Read-only [`TextUnderlineType`](/slides/python-net/hu/aspose.slides/textunderlinetype). |
| [`text_cap_type`](/slides/python-net/hu/aspose.slides/ibaseportionformateffectivedata/text_cap_type/) | Returns the type of text capitalization.<br/>            Read-only [`TextCapType`](/slides/python-net/hu/aspose.slides/textcaptype). |
| [`strikethrough_type`](/slides/python-net/hu/aspose.slides/ibaseportionformateffectivedata/strikethrough_type/) | Returns the strikethrough type of a text.<br/>            Read-only [`TextStrikethroughType`](/slides/python-net/hu/aspose.slides/textstrikethroughtype). |
| [`smart_tag_clean`](/slides/python-net/hu/aspose.slides/ibaseportionformateffectivedata/smart_tag_clean/) | Megállapítja, hogy az intelligens címkét tisztítani kell-e.<br/>            Read-only **bool**. |
| [`is_hard_underline_line`](/slides/python-net/hu/aspose.slides/ibaseportionformateffectivedata/is_hard_underline_line/) | Megállapítja, hogy az aláhúzás stílusa rendelkezik-e saját LineFormat tulajdonságokkal, vagy örökli azokat a szöveg LineFormat tulajdonságaitól.<br/>            Read-only **bool**. |
| [`is_hard_underline_fill`](/slides/python-net/hu/aspose.slides/ibaseportionformateffectivedata/is_hard_underline_fill/) | Megállapítja, hogy az aláhúzás stílusa rendelkezik-e saját FillFormat tulajdonságokkal, vagy örökli azokat a szöveg FillFormat tulajdonságaitól.<br/>            Read-only **bool**. |
| [`font_height`](/slides/python-net/hu/aspose.slides/ibaseportionformateffectivedata/font_height/) | Returns the font height of the text portion, in points.<br/>            Read-only **float**. |
| [`latin_font`](/slides/python-net/hu/aspose.slides/ibaseportionformateffectivedata/latin_font/) | Returns the Latin font info.<br/>            Read-only [`IFontData`](/slides/python-net/hu/aspose.slides/ifontdata). |
| [`east_asian_font`](/slides/python-net/hu/aspose.slides/ibaseportionformateffectivedata/east_asian_font/) | Returns the East Asian font info.<br/>            Read-only [`IFontData`](/slides/python-net/hu/aspose.slides/ifontdata). |
| [`complex_script_font`](/slides/python-net/hu/aspose.slides/ibaseportionformateffectivedata/complex_script_font/) | Returns the complex script font info.<br/>            Read-only [`IFontData`](/slides/python-net/hu/aspose.slides/ifontdata). |
| [`symbol_font`](/slides/python-net/hu/aspose.slides/ibaseportionformateffectivedata/symbol_font/) | Returns the symbolic font info.<br/>            Read-only [`IFontData`](/slides/python-net/hu/aspose.slides/ifontdata). |
| [`escapement`](/slides/python-net/hu/aspose.slides/ibaseportionformateffectivedata/escapement/) | Returns the superscript or subscript text.<br/>            Value from -100% (subscript) to 100% (superscript).<br/>            Read-only **float**. |
| [`kerning_minimal_size`](/slides/python-net/hu/aspose.slides/ibaseportionformateffectivedata/kerning_minimal_size/) | Returns the minimal font size, for which kerning should be switched on.<br/>            Read-only **float**. |
| [`language_id`](/slides/python-net/hu/aspose.slides/ibaseportionformateffectivedata/language_id/) | Returns the Id of a language.<br/>            Read-only **str**. |
| [`alternative_language_id`](/slides/python-net/hu/aspose.slides/ibaseportionformateffectivedata/alternative_language_id/) | Returns the Id of an alternative language.<br/>            Read-only **str**. |
| [`spacing`](/slides/python-net/hu/aspose.slides/ibaseportionformateffectivedata/spacing/) | Returns the intercharacter spacing increment, in points.<br/>            Read-only **float**. |


### See Also
* modul [`aspose.slides`](/slides/python-net/hu/aspose.slides)
* könyvtár [`Aspose.Slides`](/slides/python-net)