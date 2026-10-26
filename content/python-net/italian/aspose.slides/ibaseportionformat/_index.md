---
title: IBasePortionFormat class
second_title: Riferimento API Aspose.Slides per Python via .NET
description: 
type: docs
url: /it/aspose.slides/ibaseportionformat/
---
## IBasePortionFormat classe

Questa classe contiene le proprietà di formattazione della porzione di testo. A differenza di [`IPortionFormatEffectiveData`](/slides/python-net/it/aspose.slides/iportionformateffectivedata), tutte le proprietà di questa classe sono scrivibili.

Il tipo IBasePortionFormat espone i seguenti membri:

## Proprietà

| Property | Description |
| :- | :- |
| [`line_format`](/slides/python-net/it/aspose.slides/ibaseportionformat/line_format/) | Restituisce le proprietà LineFormat per il contorno del testo. Nessuna eredità applicata.<br/>            Sola lettura [`ILineFormat`](/slides/python-net/it/aspose.slides/ilineformat). |
| [`fill_format`](/slides/python-net/it/aspose.slides/ibaseportionformat/fill_format/) | Restituisce le proprietà FillFormat del testo. Nessuna eredità applicata.<br/>            Sola lettura [`IFillFormat`](/slides/python-net/it/aspose.slides/ifillformat). |
| [`effect_format`](/slides/python-net/it/aspose.slides/ibaseportionformat/effect_format/) | Restituisce le proprietà EffectFormat del testo. Nessuna eredità applicata.<br/>            Sola lettura [`IEffectFormat`](/slides/python-net/it/aspose.slides/ieffectformat). |
| [`highlight_color`](/slides/python-net/it/aspose.slides/ibaseportionformat/highlight_color/) | Restituisce il colore usato per evidenziare un testo. Nessuna eredità applicata.<br/>            Sola lettura [`IColorFormat`](/slides/python-net/it/aspose.slides/icolorformat). |
| [`underline_line_format`](/slides/python-net/it/aspose.slides/ibaseportionformat/underline_line_format/) | Restituisce le proprietà LineFormat usate per il contorno della linea di sottolineatura. Nessuna eredità applicata.<br/>            Sola lettura [`ILineFormat`](/slides/python-net/it/aspose.slides/ilineformat). |
| [`underline_fill_format`](/slides/python-net/it/aspose.slides/ibaseportionformat/underline_fill_format/) | Restituisce le proprietà FillFormat della linea di sottolineatura. Nessuna eredità applicata.<br/>            Sola lettura [`IFillFormat`](/slides/python-net/it/aspose.slides/ifillformat). |
| [`font_bold`](/slides/python-net/it/aspose.slides/ibaseportionformat/font_bold/) | Determina se il carattere è in grassetto. Nessuna eredità applicata.<br/>            Lettura/scrittura [`NullableBool`](/slides/python-net/it/aspose.slides/nullablebool). |
| [`font_italic`](/slides/python-net/it/aspose.slides/ibaseportionformat/font_italic/) | Determina se il carattere è corsivo. Nessuna eredità applicata.<br/>            Lettura/scrittura [`NullableBool`](/slides/python-net/it/aspose.slides/nullablebool). |
| [`kumimoji`](/slides/python-net/it/aspose.slides/ibaseportionformat/kumimoji/) | Determina se i numeri devono ignorare il layout verticale del testo specifico per le lingue orientali. Nessuna eredità applicata.<br/>            Lettura/scrittura [`NullableBool`](/slides/python-net/it/aspose.slides/nullablebool). |
| [`normalise_height`](/slides/python-net/it/aspose.slides/ibaseportionformat/normalise_height/) | Determina se l'altezza di un testo deve essere normalizzata. Nessuna eredità applicata.<br/>            Lettura/scrittura [`NullableBool`](/slides/python-net/it/aspose.slides/nullablebool). |
| [`proof_disabled`](/slides/python-net/it/aspose.slides/ibaseportionformat/proof_disabled/) | Determina se il testo non deve essere corretto. Nessuna eredità applicata.<br/>            Lettura/scrittura [`NullableBool`](/slides/python-net/it/aspose.slides/nullablebool). |
| [`font_underline`](/slides/python-net/it/aspose.slides/ibaseportionformat/font_underline/) | Restituisce o imposta il tipo di sottolineatura del testo. Nessuna eredità applicata.<br/>            Lettura/scrittura [`TextUnderlineType`](/slides/python-net/it/aspose.slides/textunderlinetype). |
| [`text_cap_type`](/slides/python-net/it/aspose.slides/ibaseportionformat/text_cap_type/) | Restituisce o imposta il tipo di capitalizzazione del testo. Nessuna eredità applicata.<br/>            Lettura/scrittura [`TextCapType`](/slides/python-net/it/aspose.slides/textcaptype). |
| [`strikethrough_type`](/slides/python-net/it/aspose.slides/ibaseportionformat/strikethrough_type/) | Restituisce o imposta il tipo di barrato del testo. Nessuna eredità applicata.<br/>            Lettura/scrittura [`TextStrikethroughType`](/slides/python-net/it/aspose.slides/textstrikethroughtype). |
| [`is_hard_underline_line`](/slides/python-net/it/aspose.slides/ibaseportionformat/is_hard_underline_line/) | Determina se lo stile di sottolineatura ha proprie proprietà LineFormat o le eredita dalle proprietà LineFormat del testo.<br/>            Lettura/scrittura [`NullableBool`](/slides/python-net/it/aspose.slides/nullablebool). |
| [`is_hard_underline_fill`](/slides/python-net/it/aspose.slides/ibaseportionformat/is_hard_underline_fill/) | Determina se lo stile di sottolineatura ha proprie proprietà FillFormat o le eredita dalle proprietà FillFormat del testo.<br/>            Lettura/scrittura [`NullableBool`](/slides/python-net/it/aspose.slides/nullablebool). |
| [`font_height`](/slides/python-net/it/aspose.slides/ibaseportionformat/font_height/) | Restituisce o imposta l'altezza del carattere di una porzione.<br/>            **float.NaN** indica che l'altezza è indefinita e dovrebbe essere ereditata dal Master.<br/>            Lettura/scrittura **float**. |
| [`latin_font`](/slides/python-net/it/aspose.slides/ibaseportionformat/latin_font/) | Restituisce o imposta le informazioni sul carattere Latin.<br/>            Null indica che il carattere è indefinito e dovrebbe essere ereditato dal Master.<br/>            Lettura/scrittura [`IFontData`](/slides/python-net/it/aspose.slides/ifontdata). |
| [`east_asian_font`](/slides/python-net/it/aspose.slides/ibaseportionformat/east_asian_font/) | Restituisce o imposta le informazioni sul carattere East Asian.<br/>            Null indica che il carattere è indefinito e dovrebbe essere ereditato dal Master.<br/>            Lettura/scrittura [`IFontData`](/slides/python-net/it/aspose.slides/ifontdata). |
| [`complex_script_font`](/slides/python-net/it/aspose.slides/ibaseportionformat/complex_script_font/) | Restituisce o imposta le informazioni sul carattere complex script.<br/>            Null indica che il carattere è indefinito e dovrebbe essere ereditato dal Master.<br/>            Lettura/scrittura [`IFontData`](/slides/python-net/it/aspose.slides/ifontdata). |
| [`symbol_font`](/slides/python-net/it/aspose.slides/ibaseportionformat/symbol_font/) | Restituisce o imposta le informazioni sul carattere symbolic.<br/>            Null indica che il carattere è indefinito e dovrebbe essere ereditato dal Master.<br/>            Lettura/scrittura [`IFontData`](/slides/python-net/it/aspose.slides/ifontdata). |
| [`escapement`](/slides/python-net/it/aspose.slides/ibaseportionformat/escapement/) | Restituisce o imposta il testo in apice o pedice.<br/>            Valore da -100% (pedice) a 100% (apice).<br/>            **float.NaN** indica che il valore è indefinito e dovrebbe essere ereditato dal Master.<br/>            Lettura/scrittura **float**. |
| [`kerning_minimal_size`](/slides/python-net/it/aspose.slides/ibaseportionformat/kerning_minimal_size/) | Restituisce o imposta la dimensione minima del carattere, per la quale il kerning dovrebbe essere attivato.<br/>            **float.NaN** indica che il valore è indefinito e dovrebbe essere ereditato dal Master.<br/>            Lettura/scrittura **float**. |
| [`language_id`](/slides/python-net/it/aspose.slides/ibaseportionformat/language_id/) | Restituisce o imposta l'Id di una lingua di correzione. Usato per il controllo ortografico e grammaticale.<br/>            Lettura/scrittura **str**. |
| [`alternative_language_id`](/slides/python-net/it/aspose.slides/ibaseportionformat/alternative_language_id/) | Restituisce o imposta l'Id di una lingua alternativa.<br/>            Lettura/scrittura **str**. |
| [`spacing`](/slides/python-net/it/aspose.slides/ibaseportionformat/spacing/) | Restituisce o imposta l'incremento della spaziatura intercarattere.<br/>            **float.NaN** indica che il valore è indefinito e dovrebbe essere ereditato dal Master.<br/>            Lettura/scrittura **float**. |
| [`spell_check`](/slides/python-net/it/aspose.slides/ibaseportionformat/spell_check/) | Ottiene o imposta un valore che indica se il controllo ortografico è abilitato per la porzione di testo.<br/>            Quando questa proprietà è impostata su false, i controlli ortografici per gli elementi di testo sono soppressi.<br/>            Quando impostata su true, il controllo ortografico è consentito.<br/>            Il valore predefinito è `false`. |

### Osservazioni

Questa classe è usata per restituire e manipolare le proprietà di formattazione della porzione di testo definite per la porzione specifica. Ciò significa che non viene applicata alcuna eredità durante il recupero dei valori, quindi nella maggior parte dei casi otterrai valori che indicano "non definito".

Per ottenere i valori effettivi dei parametri di formattazione, inclusi quelli ereditati, è necessario utilizzare il metodo [`IPortionFormat.get_effective`](/slides/python-net/it/aspose.slides/iportionformat/get_effective) che restituisce un'istanza [`IPortionFormatEffectiveData`](/slides/python-net/it/aspose.slides/iportionformateffectivedata).

### Vedi anche
* classe [`IPortionFormatEffectiveData`](/slides/python-net/it/aspose.slides/iportionformateffectivedata)
* modulo [`aspose.slides`](/slides/python-net/it/aspose.slides)
* libreria [`Aspose.Slides`](/slides/python-net)