---
title: PortionFormat class
second_title: Aspose.Slides per Python via .NET Riferimento API
description: 
type: docs
url: /it/aspose.slides/portionformat/
---
## PortionFormat classe

Questa classe contiene le proprietà di formattazione della porzione di testo. A differenza di [`IPortionFormatEffectiveData`](/slides/python-net/it/aspose.slides/iportionformateffectivedata), tutte le proprietà di questa classe sono scrivibili.

**Eredità:**[`PortionFormat`](/slides/python-net/it/aspose.slides/portionformat) → [`BasePortionFormat`](/slides/python-net/it/aspose.slides/baseportionformat) → [`PVIObject`](/slides/python-net/it/aspose.slides/pviobject)

Il tipo PortionFormat espone i seguenti membri:

## Costruttori

| Costruttore | Descrizione |
| :- | :- |
| [`__init__(self)`](/slides/python-net/it/aspose.slides/portionformat/__init__/#) | Inizializza una nuova istanza della classe [`PortionFormat`](/slides/python-net/it/aspose.slides/portionformat). |

## Proprietà

| Proprietà | Descrizione |
| :- | :- |
| [`line_format`](/slides/python-net/it/aspose.slides/portionformat/line_format/) | Restituisce le proprietà LineFormat per il contorno del testo. Nessuna eredità applicata.<br/>            Solo lettura [`ILineFormat`](/slides/python-net/it/aspose.slides/ilineformat). |
| [`fill_format`](/slides/python-net/it/aspose.slides/portionformat/fill_format/) | Restituisce le proprietà FillFormat del testo. Nessuna eredità applicata.<br/>            Solo lettura [`IFillFormat`](/slides/python-net/it/aspose.slides/ifillformat). |
| [`effect_format`](/slides/python-net/it/aspose.slides/portionformat/effect_format/) | Restituisce le proprietà EffectFormat del testo. Nessuna eredità applicata.<br/>            Solo lettura [`IEffectFormat`](/slides/python-net/it/aspose.slides/ieffectformat). |
| [`highlight_color`](/slides/python-net/it/aspose.slides/portionformat/highlight_color/) | Restituisce il colore usato per evidenziare un testo. Nessuna eredità applicata.<br/>            Solo lettura [`IColorFormat`](/slides/python-net/it/aspose.slides/icolorformat). |
| [`underline_line_format`](/slides/python-net/it/aspose.slides/portionformat/underline_line_format/) | Restituisce le proprietà LineFormat usate per delineare la linea di sottolineatura. Nessuna eredità applicata.<br/>            Solo lettura [`ILineFormat`](/slides/python-net/it/aspose.slides/ilineformat). |
| [`underline_fill_format`](/slides/python-net/it/aspose.slides/portionformat/underline_fill_format/) | Restituisce le proprietà FillFormat della linea di sottolineatura. Nessuna eredità applicata.<br/>            Solo lettura [`IFillFormat`](/slides/python-net/it/aspose.slides/ifillformat). |
| [`font_bold`](/slides/python-net/it/aspose.slides/portionformat/font_bold/) | Determina se il font è grassetto. Nessuna eredità applicata.<br/>            Lettura/scrittura [`NullableBool`](/slides/python-net/it/aspose.slides/nullablebool). |
| [`font_italic`](/slides/python-net/it/aspose.slides/portionformat/font_italic/) | Determina se il font è corsivo. Nessuna eredità applicata.<br/>            Lettura/scrittura [`NullableBool`](/slides/python-net/it/aspose.slides/nullablebool). |
| [`kumimoji`](/slides/python-net/it/aspose.slides/portionformat/kumimoji/) | Determina se i numeri devono ignorare l'impostazione di layout verticale del testo specifico per le lingue orientali. Nessuna eredità applicata.<br/>            Lettura/scrittura [`NullableBool`](/slides/python-net/it/aspose.slides/nullablebool). |
| [`normalise_height`](/slides/python-net/it/aspose.slides/portionformat/normalise_height/) | Determina se l'altezza di un testo deve essere normalizzata. Nessuna eredità applicata.<br/>            Lettura/scrittura [`NullableBool`](/slides/python-net/it/aspose.slides/nullablebool). |
| [`proof_disabled`](/slides/python-net/it/aspose.slides/portionformat/proof_disabled/) | Determina se il testo non deve essere revisionato. Nessuna eredità applicata.<br/>            Lettura/scrittura [`NullableBool`](/slides/python-net/it/aspose.slides/nullablebool). |
| [`font_underline`](/slides/python-net/it/aspose.slides/portionformat/font_underline/) | Restituisce o imposta il tipo di sottolineatura del testo. Nessuna eredità applicata.<br/>            Lettura/scrittura [`TextUnderlineType`](/slides/python-net/it/aspose.slides/textunderlinetype). |
| [`text_cap_type`](/slides/python-net/it/aspose.slides/portionformat/text_cap_type/) | Restituisce o imposta il tipo di capitalizzazione del testo. Nessuna eredità applicata.<br/>            Lettura/scrittura [`TextCapType`](/slides/python-net/it/aspose.slides/textcaptype). |
| [`strikethrough_type`](/slides/python-net/it/aspose.slides/portionformat/strikethrough_type/) | Restituisce o imposta il tipo di barrato del testo. Nessuna eredità applicata.<br/>            Lettura/scrittura [`TextStrikethroughType`](/slides/python-net/it/aspose.slides/textstrikethroughtype). |
| [`is_hard_underline_line`](/slides/python-net/it/aspose.slides/portionformat/is_hard_underline_line/) | Determina se lo stile di sottolineatura ha proprie proprietà LineFormat o le eredita<br/>            dalle proprietà LineFormat del testo.<br/>            Lettura/scrittura [`NullableBool`](/slides/python-net/it/aspose.slides/nullablebool). |
| [`is_hard_underline_fill`](/slides/python-net/it/aspose.slides/portionformat/is_hard_underline_fill/) | Determina se lo stile di sottolineatura ha proprie proprietà FillFormat o le eredita<br/>            dalle proprietà FillFormat del testo.<br/>            Lettura/scrittura [`NullableBool`](/slides/python-net/it/aspose.slides/nullablebool). |
| [`font_height`](/slides/python-net/it/aspose.slides/portionformat/font_height/) | Restituisce o imposta l'altezza del font di una porzione.<br/>            **float.NaN**  indica che l'altezza non è definita e dovrebbe essere ereditata dal Master.<br/>            Lettura/scrittura **float**. |
| [`latin_font`](/slides/python-net/it/aspose.slides/portionformat/latin_font/) | Restituisce o imposta le informazioni sul font latino.<br/>            Null indica che il font non è definito e dovrebbe essere ereditato dal Master.<br/>            Lettura/scrittura [`IFontData`](/slides/python-net/it/aspose.slides/ifontdata). |
| [`east_asian_font`](/slides/python-net/it/aspose.slides/portionformat/east_asian_font/) | Restituisce o imposta le informazioni sul font dell'Est asiatico.<br/>            Null indica che il font non è definito e dovrebbe essere ereditato dal Master.<br/>            Lettura/scrittura [`IFontData`](/slides/python-net/it/aspose.slides/ifontdata). |
| [`complex_script_font`](/slides/python-net/it/aspose.slides/portionformat/complex_script_font/) | Restituisce o imposta le informazioni sul font per script complessi.<br/>            Null indica che il font non è definito e dovrebbe essere ereditato dal Master.<br/>            Lettura/scrittura [`IFontData`](/slides/python-net/it/aspose.slides/ifontdata). |
| [`symbol_font`](/slides/python-net/it/aspose.slides/portionformat/symbol_font/) | Restituisce o imposta le informazioni sul font simbolico.<br/>            Null indica che il font non è definito e dovrebbe essere ereditato dal Master.<br/>            Lettura/scrittura [`IFontData`](/slides/python-net/it/aspose.slides/ifontdata). |
| [`escapement`](/slides/python-net/it/aspose.slides/portionformat/escapement/) | Restituisce o imposta il testo in apice o pedice.<br/>            Valore da -100% (pedice) a 100% (apice).<br/>            **float.NaN**  indica che il valore non è definito e dovrebbe essere ereditato dal Master.<br/>            Lettura/scrittura **float**. |
| [`kerning_minimal_size`](/slides/python-net/it/aspose.slides/portionformat/kerning_minimal_size/) | Restituisce o imposta la dimensione minima del font, per la quale il kerning deve essere attivato.<br/>            **float.NaN**  indica che il valore non è definito e dovrebbe essere ereditato dal Master.<br/>            Lettura/scrittura **float**. |
| [`language_id`](/slides/python-net/it/aspose.slides/portionformat/language_id/) | Restituisce o imposta l'Id di una lingua di correzione. Usato per il controllo ortografico e grammaticale.<br/>            Lettura/scrittura **str**. |
| [`alternative_language_id`](/slides/python-net/it/aspose.slides/portionformat/alternative_language_id/) | Restituisce o imposta l'Id di una lingua alternativa.<br/>            Lettura/scrittura **str**. |
| [`spacing`](/slides/python-net/it/aspose.slides/portionformat/spacing/) | Restituisce o imposta l'incremento della spaziatura intercarattere.<br/>            **float.NaN**  indica che il valore non è definito e dovrebbe essere ereditato dal Master.<br/>            Lettura/scrittura **float**. |
| [`spell_check`](/slides/python-net/it/aspose.slides/portionformat/spell_check/) | Ottiene o imposta un valore che indica se il controllo ortografico è abilitato per la porzione di testo.<br/>            Quando questa proprietà è impostata a false, i controlli ortografici per gli elementi di testo sono soppressi.<br/>            Quando impostata a true, il controllo ortografico è consentito.<br/>            Il valore predefinito è `false`. |
| [`bookmark_id`](/slides/python-net/it/aspose.slides/portionformat/bookmark_id/) | Restituisce o imposta l'identificatore del segnalibro.<br/>            Lettura/scrittura **str**. |
| [`smart_tag_clean`](/slides/python-net/it/aspose.slides/portionformat/smart_tag_clean/) | Determina se il tag intelligente deve essere pulito. Nessuna eredità applicata.<br/>            Lettura/scrittura **bool**. |
| [`hyperlink_click`](/slides/python-net/it/aspose.slides/portionformat/hyperlink_click/) | Restituisce o imposta il collegamento ipertestuale definito per il click del mouse.<br/>            Lettura/scrittura [`IHyperlink`](/slides/python-net/it/aspose.slides/ihyperlink). |
| [`hyperlink_mouse_over`](/slides/python-net/it/aspose.slides/portionformat/hyperlink_mouse_over/) | Restituisce o imposta il collegamento ipertestuale definito per il passaggio del mouse.<br/>            Lettura/scrittura [`IHyperlink`](/slides/python-net/it/aspose.slides/ihyperlink). |
| [`hyperlink_manager`](/slides/python-net/it/aspose.slides/portionformat/hyperlink_manager/) | Gestore dei collegamenti ipertestuali.<br/>            Solo lettura [`IHyperlinkManager`](/slides/python-net/it/aspose.slides/ihyperlinkmanager). |
| [`slide`](/slides/python-net/it/aspose.slides/portionformat/slide/) |  |
| [`presentation`](/slides/python-net/it/aspose.slides/portionformat/presentation/) |  |

## Metodi

| Metodo | Descrizione |
| :- | :- |
| [`get_effective(self)`](/slides/python-net/it/aspose.slides/portionformat/get_effective/#) | Ottiene i dati di formattazione della porzione effettiva con l'ereditarietà applicata. |

### Osservazioni

Questa classe è usata per restituire e manipolare le proprietà di formattazione della porzione di testo definite per la specifica porzione. Ciò significa che
            nessuna eredità è applicata quando si ottengono i valori, quindi nella maggior parte dei casi si otterranno valori che indicano "non definito".

Per ottenere i valori dei parametri di formattazione effective includendo quelli ereditati è necessario utilizzare il metodo [`PortionFormat.get_effective`](/slides/python-net/it/aspose.slides/portionformat/get_effective) 
            che restituisce un'istanza [`IPortionFormatEffectiveData`](/slides/python-net/it/aspose.slides/iportionformateffectivedata).

### Vedi anche
* classe [`BasePortionFormat`](/slides/python-net/it/aspose.slides/baseportionformat)
* classe [`IPortionFormatEffectiveData`](/slides/python-net/it/aspose.slides/iportionformateffectivedata)
* classe [`PortionFormat`](/slides/python-net/it/aspose.slides/portionformat)
* classe [`PVIObject`](/slides/python-net/it/aspose.slides/pviobject)
* modulo [`aspose.slides`](/slides/python-net/it/aspose.slides)
* libreria [`Aspose.Slides`](/slides/python-net)