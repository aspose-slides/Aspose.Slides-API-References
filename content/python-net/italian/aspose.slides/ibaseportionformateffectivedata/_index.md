---
title: IBasePortionFormatEffectiveData class
second_title: Riferimento API Aspose.Slides per Python tramite .NET
description: 
type: docs
url: /it/aspose.slides/ibaseportionformateffectivedata/
---
## IBasePortionFormatEffectiveData classe

Interfaccia base per oggetti immutabili che contengono le proprietà di formattazione efficace delle porzioni di testo.

Il tipo IBasePortionFormatEffectiveData espone i seguenti membri:

## Proprietà

| Proprietà | Descrizione |
| :- | :- |
| [`line_format`](/slides/python-net/it/aspose.slides/ibaseportionformateffectivedata/line_format/) | Restituisce le proprietà LineFormat per il contorno del testo.<br/>            Solo lettura [`ILineFormatEffectiveData`](/slides/python-net/it/aspose.slides/ilineformateffectivedata). |
| [`fill_format`](/slides/python-net/it/aspose.slides/ibaseportionformateffectivedata/fill_format/) | Restituisce le proprietà FillFormat del testo.<br/>            Solo lettura [`IFillFormatEffectiveData`](/slides/python-net/it/aspose.slides/ifillformateffectivedata). |
| [`effect_format`](/slides/python-net/it/aspose.slides/ibaseportionformateffectivedata/effect_format/) | Restituisce le proprietà EffectFormat del testo.<br/>            Solo lettura [`IEffectFormatEffectiveData`](/slides/python-net/it/aspose.slides/ieffectformateffectivedata). |
| [`highlight_color`](/slides/python-net/it/aspose.slides/ibaseportionformateffectivedata/highlight_color/) | Restituisce il colore usato per evidenziare un testo.<br/>            Solo lettura [`Color`](/slides/python-net/it/aspose.slides/color). |
| [`underline_line_format`](/slides/python-net/it/aspose.slides/ibaseportionformateffectivedata/underline_line_format/) | Restituisce le proprietà LineFormat usate per delineare la linea di sottolineatura.<br/>            Solo lettura [`ILineFormatEffectiveData`](/slides/python-net/it/aspose.slides/ilineformateffectivedata). |
| [`underline_fill_format`](/slides/python-net/it/aspose.slides/ibaseportionformateffectivedata/underline_fill_format/) | Restituisce le proprietà FillFormat della linea di sottolineatura.<br/>            Solo lettura [`IFillFormatEffectiveData`](/slides/python-net/it/aspose.slides/ifillformateffectivedata). |
| [`font_bold`](/slides/python-net/it/aspose.slides/ibaseportionformateffectivedata/font_bold/) | Determina se il carattere è in grassetto.<br/>            Solo lettura **bool**. |
| [`font_italic`](/slides/python-net/it/aspose.slides/ibaseportionformateffectivedata/font_italic/) | Determina se il carattere è corsivo.<br/>            Solo lettura **bool**. |
| [`kumimoji`](/slides/python-net/it/aspose.slides/ibaseportionformateffectivedata/kumimoji/) | Determina se i numeri devono ignorare la disposizione verticale del testo specifica per le lingue orientali.<br/>            Solo lettura **bool**. |
| [`normalise_height`](/slides/python-net/it/aspose.slides/ibaseportionformateffectivedata/normalise_height/) | Determina se l'altezza del testo deve essere normalizzata.<br/>            Solo lettura **bool**. |
| [`proof_disabled`](/slides/python-net/it/aspose.slides/ibaseportionformateffectivedata/proof_disabled/) | Determina se il testo non deve essere corretto.<br/>            Solo lettura **bool**. |
| [`font_underline`](/slides/python-net/it/aspose.slides/ibaseportionformateffectivedata/font_underline/) | Restituisce il tipo di sottolineatura del testo.<br/>            Solo lettura [`TextUnderlineType`](/slides/python-net/it/aspose.slides/textunderlinetype). |
| [`text_cap_type`](/slides/python-net/it/aspose.slides/ibaseportionformateffectivedata/text_cap_type/) | Restituisce il tipo di capitalizzazione del testo.<br/>            Solo lettura [`TextCapType`](/slides/python-net/it/aspose.slides/textcaptype). |
| [`strikethrough_type`](/slides/python-net/it/aspose.slides/ibaseportionformateffectivedata/strikethrough_type/) | Restituisce il tipo di barrato del testo.<br/>            Solo lettura [`TextStrikethroughType`](/slides/python-net/it/aspose.slides/textstrikethroughtype). |
| [`smart_tag_clean`](/slides/python-net/it/aspose.slides/ibaseportionformateffectivedata/smart_tag_clean/) | Determina se il tag intelligente deve essere pulito.<br/>            Solo lettura **bool**. |
| [`is_hard_underline_line`](/slides/python-net/it/aspose.slides/ibaseportionformateffectivedata/is_hard_underline_line/) | Determina se lo stile di sottolineatura ha proprie proprietà LineFormat o le eredita<br/>            dalle proprietà LineFormat del testo.<br/>            Solo lettura **bool**. |
| [`is_hard_underline_fill`](/slides/python-net/it/aspose.slides/ibaseportionformateffectivedata/is_hard_underline_fill/) | Determina se lo stile di sottolineatura ha proprie proprietà FillFormat o le eredita<br/>            dalle proprietà FillFormat del testo.<br/>            Solo lettura **bool**. |
| [`font_height`](/slides/python-net/it/aspose.slides/ibaseportionformateffectivedata/font_height/) | Restituisce l'altezza del carattere della porzione di testo, in punti.<br/>            Solo lettura **float**. |
| [`latin_font`](/slides/python-net/it/aspose.slides/ibaseportionformateffectivedata/latin_font/) | Restituisce le informazioni sul carattere latino.<br/>            Solo lettura [`IFontData`](/slides/python-net/it/aspose.slides/ifontdata). |
| [`east_asian_font`](/slides/python-net/it/aspose.slides/ibaseportionformateffectivedata/east_asian_font/) | Restituisce le informazioni sul carattere dell'Est asiatico.<br/>            Solo lettura [`IFontData`](/slides/python-net/it/aspose.slides/ifontdata). |
| [`complex_script_font`](/slides/python-net/it/aspose.slides/ibaseportionformateffectivedata/complex_script_font/) | Restituisce le informazioni sul carattere a script complesso.<br/>            Solo lettura [`IFontData`](/slides/python-net/it/aspose.slides/ifontdata). |
| [`symbol_font`](/slides/python-net/it/aspose.slides/ibaseportionformateffectivedata/symbol_font/) | Restituisce le informazioni sul carattere simbolico.<br/>            Solo lettura [`IFontData`](/slides/python-net/it/aspose.slides/ifontdata). |
| [`escapement`](/slides/python-net/it/aspose.slides/ibaseportionformateffectivedata/escapement/) | Restituisce il testo in apice o pedice.<br/>            Valore da -100% (pedice) a 100% (apice).<br/>            Solo lettura **float**. |
| [`kerning_minimal_size`](/slides/python-net/it/aspose.slides/ibaseportionformateffectivedata/kerning_minimal_size/) | Restituisce la dimensione minima del carattere, per la quale il kerning dovrebbe essere attivato.<br/>            Solo lettura **float**. |
| [`language_id`](/slides/python-net/it/aspose.slides/ibaseportionformateffectivedata/language_id/) | Restituisce l'Id di una lingua.<br/>            Solo lettura **str**. |
| [`alternative_language_id`](/slides/python-net/it/aspose.slides/ibaseportionformateffectivedata/alternative_language_id/) | Restituisce l'Id di una lingua alternativa.<br/>            Solo lettura **str**. |
| [`spacing`](/slides/python-net/it/aspose.slides/ibaseportionformateffectivedata/spacing/) | Restituisce l'incremento di spaziatura intercarattere, in punti.<br/>            Solo lettura **float**. |

### Vedi anche
* modulo [`aspose.slides`](/slides/python-net/it/aspose.slides)
* libreria [`Aspose.Slides`](/slides/python-net)