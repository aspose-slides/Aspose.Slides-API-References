---
title: IPortionFormat class
second_title: Riferimento API Aspose.Slides per Python tramite .NET
description: 
type: docs
url: /it/aspose.slides/iportionformat/
---
## IPortionFormat classe

Questa classe contiene le proprietà di formattazione della porzione di testo. A differenza di [`IPortionFormatEffectiveData`](/slides/python-net/it/aspose.slides/iportionformateffectivedata), tutte le proprietà di questa classe sono modificabili.

Il tipo IPortionFormat espone i seguenti membri:

## Proprietà

| Proprietà | Descrizione |
| :- | :- |
| [`bookmark_id`](/slides/python-net/it/aspose.slides/iportionformat/bookmark_id/) | Restituisce o imposta l'identificatore del segnalibro.<br/>            Lettura/Scrittura **str**. |
| [`smart_tag_clean`](/slides/python-net/it/aspose.slides/iportionformat/smart_tag_clean/) | Determina se il smart tag deve essere pulito. Nessuna ereditarietà applicata.<br/>            Lettura/Scrittura **bool**. |
| [`line_format`](/slides/python-net/it/aspose.slides/iportionformat/line_format/) |  |
| [`fill_format`](/slides/python-net/it/aspose.slides/iportionformat/fill_format/) |  |
| [`effect_format`](/slides/python-net/it/aspose.slides/iportionformat/effect_format/) |  |
| [`highlight_color`](/slides/python-net/it/aspose.slides/iportionformat/highlight_color/) |  |
| [`underline_line_format`](/slides/python-net/it/aspose.slides/iportionformat/underline_line_format/) |  |
| [`underline_fill_format`](/slides/python-net/it/aspose.slides/iportionformat/underline_fill_format/) |  |
| [`font_bold`](/slides/python-net/it/aspose.slides/iportionformat/font_bold/) |  |
| [`font_italic`](/slides/python-net/it/aspose.slides/iportionformat/font_italic/) |  |
| [`kumimoji`](/slides/python-net/it/aspose.slides/iportionformat/kumimoji/) |  |
| [`normalise_height`](/slides/python-net/it/aspose.slides/iportionformat/normalise_height/) |  |
| [`proof_disabled`](/slides/python-net/it/aspose.slides/iportionformat/proof_disabled/) |  |
| [`font_underline`](/slides/python-net/it/aspose.slides/iportionformat/font_underline/) |  |
| [`text_cap_type`](/slides/python-net/it/aspose.slides/iportionformat/text_cap_type/) |  |
| [`strikethrough_type`](/slides/python-net/it/aspose.slides/iportionformat/strikethrough_type/) |  |
| [`is_hard_underline_line`](/slides/python-net/it/aspose.slides/iportionformat/is_hard_underline_line/) |  |
| [`is_hard_underline_fill`](/slides/python-net/it/aspose.slides/iportionformat/is_hard_underline_fill/) |  |
| [`font_height`](/slides/python-net/it/aspose.slides/iportionformat/font_height/) |  |
| [`latin_font`](/slides/python-net/it/aspose.slides/iportionformat/latin_font/) |  |
| [`east_asian_font`](/slides/python-net/it/aspose.slides/iportionformat/east_asian_font/) |  |
| [`complex_script_font`](/slides/python-net/it/aspose.slides/iportionformat/complex_script_font/) |  |
| [`symbol_font`](/slides/python-net/it/aspose.slides/iportionformat/symbol_font/) |  |
| [`escapement`](/slides/python-net/it/aspose.slides/iportionformat/escapement/) |  |
| [`kerning_minimal_size`](/slides/python-net/it/aspose.slides/iportionformat/kerning_minimal_size/) |  |
| [`language_id`](/slides/python-net/it/aspose.slides/iportionformat/language_id/) |  |
| [`alternative_language_id`](/slides/python-net/it/aspose.slides/iportionformat/alternative_language_id/) |  |
| [`spacing`](/slides/python-net/it/aspose.slides/iportionformat/spacing/) |  |
| [`spell_check`](/slides/python-net/it/aspose.slides/iportionformat/spell_check/) |  |
| [`hyperlink_click`](/slides/python-net/it/aspose.slides/iportionformat/hyperlink_click/) |  |
| [`hyperlink_mouse_over`](/slides/python-net/it/aspose.slides/iportionformat/hyperlink_mouse_over/) |  |
| [`hyperlink_manager`](/slides/python-net/it/aspose.slides/iportionformat/hyperlink_manager/) |  |

## Metodi

| Metodo | Descrizione |
| :- | :- |
| [`get_effective(self)`](/slides/python-net/it/aspose.slides/iportionformat/get_effective/#) | Ottiene i dati di formattazione della porzione effettiva con l'ereditarietà applicata. |


### Osservazioni

Questa classe è utilizzata per restituire e manipolare le proprietà di formattazione della porzione di testo definite per la specifica porzione. Ciò significa che
            non viene applicata alcuna ereditarietà quando si ottengono i valori, quindi nella maggior parte dei casi otterrete valori che significano "non definito".


Per ottenere i valori dei parametri di formattazione effettivi, inclusi quelli ereditati, è necessario utilizzare il metodo [`IPortionFormat.get_effective`](/slides/python-net/it/aspose.slides/iportionformat/get_effective) 
            che restituisce un'istanza [`IPortionFormatEffectiveData`](/slides/python-net/it/aspose.slides/iportionformateffectivedata).


### Vedi anche
* classe [`IPortionFormatEffectiveData`](/slides/python-net/it/aspose.slides/iportionformateffectivedata)
* modulo [`aspose.slides`](/slides/python-net/it/aspose.slides)
* libreria [`Aspose.Slides`](/slides/python-net)