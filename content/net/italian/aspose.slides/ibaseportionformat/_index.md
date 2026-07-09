---
title: IBasePortionFormat
second_title: Riferimento API Aspose.Sildes per .NET
description: Questa classe contiene le proprietà di formattazione della porzione di testo. A differenza di IPortionFormatEffectiveData./iportionformateffectivedata tutte le proprietà di questa classe sono scrivibili.
type: docs
weight: 5310
url: /it/aspose.slides/ibaseportionformat/
---
## IBasePortionFormat interfaccia

Questa classe contiene le proprietà di formattazione della porzione di testo. A differenza di [`IPortionFormatEffectiveData`](../iportionformateffectivedata), tutte le proprietà di questa classe sono scrivibili.

```csharp
public interface IBasePortionFormat
```

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [AlternativeLanguageId](../../aspose.slides/ibaseportionformat/alternativelanguageid) { get; set; } | Restituisce o imposta l'Id di una lingua alternativa. Lettura/Scrittura String. |
| [ComplexScriptFont](../../aspose.slides/ibaseportionformat/complexscriptfont) { get; set; } | Restituisce o imposta le informazioni sul carattere per script complessi. Null significa che il font è indefinito e dovrebbe essere ereditato dal Master. Lettura/Scrittura [`IFontData`](../ifontdata). |
| [EastAsianFont](../../aspose.slides/ibaseportionformat/eastasianfont) { get; set; } | Restituisce o imposta le informazioni sul carattere per le lingue dell'Est asiatico. Null significa che il font è indefinito e dovrebbe essere ereditato dal Master. Lettura/Scrittura [`IFontData`](../ifontdata). |
| [EffectFormat](../../aspose.slides/ibaseportionformat/effectformat) { get; } | Restituisce le proprietà EffectFormat del testo. Nessuna ereditarietà applicata. Solo lettura [`IEffectFormat`](../ieffectformat). |
| [Escapement](../../aspose.slides/ibaseportionformat/escapement) { get; set; } | Restituisce o imposta il testo in apice o pedice. Valore da -100% (pedice) a 100% (apice). **float.NaN** indica valore indefinito e dovrebbe essere ereditato dal Master. Lettura/Scrittura Single. |
| [FillFormat](../../aspose.slides/ibaseportionformat/fillformat) { get; } | Restituisce le proprietà FillFormat del testo. Nessuna ereditarietà applicata. Solo lettura [`IFillFormat`](../ifillformat). |
| [FontBold](../../aspose.slides/ibaseportionformat/fontbold) { get; set; } | Determina se il carattere è grassetto. Nessuna ereditarietà applicata. Lettura/Scrittura [`NullableBool`](../nullablebool). |
| [FontHeight](../../aspose.slides/ibaseportionformat/fontheight) { get; set; } | Restituisce o imposta l'altezza del carattere di una porzione. **float.NaN** indica altezza indefinita e dovrebbe essere ereditata dal Master. Lettura/Scrittura Single. |
| [FontItalic](../../aspose.slides/ibaseportionformat/fontitalic) { get; set; } | Determina se il carattere è italico. Nessuna ereditarietà applicata. Lettura/Scrittura [`NullableBool`](../nullablebool). |
| [FontUnderline](../../aspose.slides/ibaseportionformat/fontunderline) { get; set; } | Restituisce o imposta il tipo di sottolineatura del testo. Nessuna ereditarietà applicata. Lettura/Scrittura [`TextUnderlineType`](../textunderlinetype). |
| [HighlightColor](../../aspose.slides/ibaseportionformat/highlightcolor) { get; } | Restituisce il colore usato per evidenziare un testo. Nessuna ereditarietà applicata. Solo lettura [`IColorFormat`](../icolorformat). |
| [IsHardUnderlineFill](../../aspose.slides/ibaseportionformat/ishardunderlinefill) { get; set; } | Determina se lo stile di sottolineatura ha proprie proprietà FillFormat o le eredita dalle proprietà FillFormat del testo. Lettura/Scrittura [`NullableBool`](../nullablebool). |
| [IsHardUnderlineLine](../../aspose.slides/ibaseportionformat/ishardunderlineline) { get; set; } | Determina se lo stile di sottolineatura ha proprie proprietà LineFormat o le eredita dalle proprietà LineFormat del testo. Lettura/Scrittura [`NullableBool`](../nullablebool). |
| [KerningMinimalSize](../../aspose.slides/ibaseportionformat/kerningminimalsize) { get; set; } | Restituisce o imposta la dimensione minima del carattere per la quale il kerning deve essere attivato. **float.NaN** indica valore indefinito e dovrebbe essere ereditato dal Master. Lettura/Scrittura Single. |
| [Kumimoji](../../aspose.slides/ibaseportionformat/kumimoji) { get; set; } | Determina se i numeri devono ignorare il layout verticale del testo specifico per lingua orientale. Nessuna ereditarietà applicata. Lettura/Scrittura [`NullableBool`](../nullablebool). |
| [LanguageId](../../aspose.slides/ibaseportionformat/languageid) { get; set; } | Restituisce o imposta l'Id di una lingua di correzione. Usato per il controllo ortografico e grammaticale. Lettura/Scrittura String. |
| [LatinFont](../../aspose.slides/ibaseportionformat/latinfont) { get; set; } | Restituisce o imposta le informazioni sul carattere latino. Null significa che il font è indefinito e dovrebbe essere ereditato dal Master. Lettura/Scrittura [`IFontData`](../ifontdata). |
| [LineFormat](../../aspose.slides/ibaseportionformat/lineformat) { get; } | Restituisce le proprietà LineFormat per il contorno del testo. Nessuna ereditarietà applicata. Solo lettura [`ILineFormat`](../ilineformat). |
| [NormaliseHeight](../../aspose.slides/ibaseportionformat/normaliseheight) { get; set; } | Determina se l'altezza del testo deve essere normalizzata. Nessuna ereditarietà applicata. Lettura/Scrittura [`NullableBool`](../nullablebool). |
| [ProofDisabled](../../aspose.slides/ibaseportionformat/proofdisabled) { get; set; } | Determina se il testo non deve essere corretto. Nessuna ereditarietà applicata. Lettura/Scrittura [`NullableBool`](../nullablebool). |
| [Spacing](../../aspose.slides/ibaseportionformat/spacing) { get; set; } | Restituisce o imposta l'incremento della spaziatura intercarattere. **float.NaN** indica valore indefinito e dovrebbe essere ereditato dal Master. Lettura/Scrittura Single. |
| [SpellCheck](../../aspose.slides/ibaseportionformat/spellcheck) { get; set; } | Ottiene o imposta un valore che indica se il controllo ortografico è abilitato per la porzione di testo. Quando questa proprietà è impostata su false, i controlli ortografici per gli elementi di testo sono soppressi. Quando impostata su true, il controllo ortografico è consentito. Il valore predefinito è `false`. |
| [StrikethroughType](../../aspose.slides/ibaseportionformat/strikethroughtype) { get; set; } | Restituisce o imposta il tipo di barrato del testo. Nessuna ereditarietà applicata. Lettura/Scrittura [`TextStrikethroughType`](../textstrikethroughtype). |
| [SymbolFont](../../aspose.slides/ibaseportionformat/symbolfont) { get; set; } | Restituisce o imposta le informazioni sul carattere simbolico. Null significa che il font è indefinito e dovrebbe essere ereditato dal Master. Lettura/Scrittura [`IFontData`](../ifontdata). |
| [TextCapType](../../aspose.slides/ibaseportionformat/textcaptype) { get; set; } | Restituisce o imposta il tipo di capitalizzazione del testo. Nessuna ereditarietà applicata. Lettura/Scrittura [`TextCapType`](../textcaptype). |
| [UnderlineFillFormat](../../aspose.slides/ibaseportionformat/underlinefillformat) { get; } | Restituisce le proprietà FillFormat della linea di sottolineatura. Nessuna ereditarietà applicata. Solo lettura [`IFillFormat`](../ifillformat). |
| [UnderlineLineFormat](../../aspose.slides/ibaseportionformat/underlinelineformat) { get; } | Restituisce le proprietà LineFormat usate per contornare la linea di sottolineatura. Nessuna ereditarietà applicata. Solo lettura [`ILineFormat`](../ilineformat). |

### Osservazioni

Questa classe è usata per restituire e manipolare le proprietà di formattazione della porzione di testo definite per la specifica porzione. Ciò significa che nessuna ereditarietà è applicata quando si ottengono i valori, quindi nella maggior parte dei casi si otterranno valori che indicano “non definito”.

Per ottenere i valori dei parametri di formattazione effettivi, inclusi quelli ereditati, è necessario utilizzare il metodo [`GetEffective`](../iportionformat/geteffective) che restituisce un'istanza [`IPortionFormatEffectiveData`](../iportionformateffectivedata).

### Vedi anche

* spazio dei nomi [Aspose.Slides](../../aspose.slides)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->