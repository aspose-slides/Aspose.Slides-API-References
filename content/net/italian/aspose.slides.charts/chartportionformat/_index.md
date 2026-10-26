---
title: ChartPortionFormat
second_title: Aspose.Sildes per .NET Riferimento API
description: Questa classe contiene le proprietà di formattazione della porzione di grafico utilizzate nei grafici. A differenza di IPortionFormatEffectiveData../aspose.slides/iportionformateffectivedata tutte le proprietà di questa classe sono scrivibili.
type: docs
weight: 1430
url: /it/aspose.slides.charts/chartportionformat/
---
## ChartPortionFormat classe

Questa classe contiene le proprietà di formattazione della porzione di grafico utilizzate nei grafici. A differenza di [`IPortionFormatEffectiveData`](../../aspose.slides/iportionformateffectivedata), tutte le proprietà di questa classe sono scrivibili.

```csharp
public sealed class ChartPortionFormat : BasePortionFormat, IChartPortionFormat
```

## Proprietà

| Name | Description |
| --- | --- |
| [AlternativeLanguageId](../../aspose.slides/baseportionformat/alternativelanguageid) { get; set; } | Restituisce o imposta l'Id di una lingua alternativa. Lettura/scrittura String. |
| [AsIPresentationComponent](../../aspose.slides/pviobject/asipresentationcomponent) { get; } | Consente di ottenere l'interfaccia base IPresentationComponent. Sola lettura [`IPresentationComponent`](../../aspose.slides/ipresentationcomponent). |
| [ComplexScriptFont](../../aspose.slides/baseportionformat/complexscriptfont) { get; set; } | Restituisce o imposta le informazioni sul font per script complessi. Null indica che il font non è definito e deve essere ereditato dal Master. Lettura/scrittura [`IFontData`](../../aspose.slides/ifontdata). |
| [EastAsianFont](../../aspose.slides/baseportionformat/eastasianfont) { get; set; } | Restituisce o imposta le informazioni sul font East Asian. Null indica che il font non è definito e deve essere ereditato dal Master. Lettura/scrittura [`IFontData`](../../aspose.slides/ifontdata). |
| [EffectFormat](../../aspose.slides/baseportionformat/effectformat) { get; } | Restituisce le proprietà EffectFormat del testo. Nessuna ereditarietà applicata. Sola lettura [`IEffectFormat`](../../aspose.slides/ieffectformat). |
| [Escapement](../../aspose.slides/baseportionformat/escapement) { get; set; } | Restituisce o imposta il testo in apice o pedice. Valore da -100% (pedice) a 100% (apice). **float.NaN** indica che il valore non è definito e deve essere ereditato dal Master. Lettura/scrittura Single. |
| [FillFormat](../../aspose.slides/baseportionformat/fillformat) { get; } | Restituisce le proprietà FillFormat del testo. Nessuna ereditarietà applicata. Sola lettura [`IFillFormat`](../../aspose.slides/ifillformat). |
| [FontBold](../../aspose.slides/baseportionformat/fontbold) { get; set; } | Determina se il font è grassetto. Nessuna ereditarietà applicata. Lettura/scrittura [`NullableBool`](../../aspose.slides/nullablebool). |
| [FontHeight](../../aspose.slides/baseportionformat/fontheight) { get; set; } | Restituisce o imposta l'altezza del font di una porzione. **float.NaN** indica che l'altezza non è definita e deve essere ereditata dal Master. Lettura/scrittura Single. |
| [FontItalic](../../aspose.slides/baseportionformat/fontitalic) { get; set; } | Determina se il font è in corsivo. Nessuna ereditarietà applicata. Lettura/scrittura [`NullableBool`](../../aspose.slides/nullablebool). |
| [FontUnderline](../../aspose.slides/baseportionformat/fontunderline) { get; set; } | Restituisce o imposta il tipo di sottolineatura del testo. Nessuna ereditarietà applicata. Lettura/scrittura [`TextUnderlineType`](../../aspose.slides/textunderlinetype). |
| [HighlightColor](../../aspose.slides/baseportionformat/highlightcolor) { get; } | Restituisce il colore usato per evidenziare un testo. Nessuna ereditarietà applicata. Sola lettura [`IColorFormat`](../../aspose.slides/icolorformat). |
| [IsHardUnderlineFill](../../aspose.slides/baseportionformat/ishardunderlinefill) { get; set; } | Determina se lo stile di sottolineatura ha proprie proprietà FillFormat o le eredita dalle proprietà FillFormat del testo. Lettura/scrittura [`NullableBool`](../../aspose.slides/nullablebool). |
| [IsHardUnderlineLine](../../aspose.slides/baseportionformat/ishardunderlineline) { get; set; } | Determina se lo stile di sottolineatura ha proprie proprietà LineFormat o le eredita dalle proprietà LineFormat del testo. Lettura/scrittura [`NullableBool`](../../aspose.slides/nullablebool). |
| [KerningMinimalSize](../../aspose.slides/baseportionformat/kerningminimalsize) { get; set; } | Restituisce o imposta la dimensione minima del font per cui il kerning deve essere attivato. **float.NaN** indica che il valore non è definito e deve essere ereditato dal Master. Lettura/scrittura Single. |
| [Kumimoji](../../aspose.slides/baseportionformat/kumimoji) { get; set; } | Determina se i numeri devono ignorare il layout verticale del testo specifico per le lingue orientali. Nessuna ereditarietà applicata. Lettura/scrittura [`NullableBool`](../../aspose.slides/nullablebool). |
| [LanguageId](../../aspose.slides/baseportionformat/languageid) { get; set; } | Restituisce o imposta l'Id di una lingua di correzione. Usato per il controllo ortografico e grammaticale. Lettura/scrittura String. |
| [LatinFont](../../aspose.slides/baseportionformat/latinfont) { get; set; } | Restituisce o imposta le informazioni sul font Latino. Null indica che il font non è definito e deve essere ereditato dal Master. Lettura/scrittura [`IFontData`](../../aspose.slides/ifontdata). |
| [LineFormat](../../aspose.slides/baseportionformat/lineformat) { get; } | Restituisce le proprietà LineFormat per il contorno del testo. Nessuna ereditarietà applicata. Sola lettura [`ILineFormat`](../../aspose.slides/ilineformat). |
| [NormaliseHeight](../../aspose.slides/baseportionformat/normaliseheight) { get; set; } | Determina se l'altezza del testo deve essere normalizzata. Nessuna ereditarietà applicata. Lettura/scrittura [`NullableBool`](../../aspose.slides/nullablebool). |
| [ProofDisabled](../../aspose.slides/baseportionformat/proofdisabled) { get; set; } | Determina se il testo non deve essere corretto. Nessuna ereditarietà applicata. Lettura/scrittura [`NullableBool`](../../aspose.slides/nullablebool). |
| [Spacing](../../aspose.slides/baseportionformat/spacing) { get; set; } | Restituisce o imposta l'incremento dell'interspazio tra caratteri. **float.NaN** indica che il valore non è definito e deve essere ereditato dal Master. Lettura/scrittura Single. |
| [SpellCheck](../../aspose.slides/baseportionformat/spellcheck) { get; set; } | Ottiene o imposta un valore che indica se il controllo ortografico è abilitato per la porzione di testo. Quando questa proprietà è impostata su false, i controlli ortografici per gli elementi di testo sono soppressi. Quando impostata su true, il controllo ortografico è consentito. Il valore predefinito è `false`. |
| [StrikethroughType](../../aspose.slides/baseportionformat/strikethroughtype) { get; set; } | Restituisce o imposta il tipo di barrato del testo. Nessuna ereditarietà applicata. Lettura/scrittura [`TextStrikethroughType`](../../aspose.slides/textstrikethroughtype). |
| [SymbolFont](../../aspose.slides/baseportionformat/symbolfont) { get; set; } | Restituisce o imposta le informazioni sul font simbolico. Null indica che il font non è definito e deve essere ereditato dal Master. Lettura/scrittura [`IFontData`](../../aspose.slides/ifontdata). |
| [TextCapType](../../aspose.slides/baseportionformat/textcaptype) { get; set; } | Restituisce o imposta il tipo di capitalizzazione del testo. Nessuna ereditarietà applicata. Lettura/scrittura [`TextCapType`](../../aspose.slides/textcaptype). |
| [UnderlineFillFormat](../../aspose.slides/baseportionformat/underlinefillformat) { get; } | Restituisce le proprietà FillFormat della linea di sottolineatura. Nessuna ereditarietà applicata. Sola lettura [`IFillFormat`](../../aspose.slides/ifillformat). |
| [UnderlineLineFormat](../../aspose.slides/baseportionformat/underlinelineformat) { get; } | Restituisce le proprietà LineFormat usate per contornare la linea di sottolineatura. Nessuna ereditarietà applicata. Sola lettura [`ILineFormat`](../../aspose.slides/ilineformat). |

## Metodi

| Name | Description |
| --- | --- |
| override [Equals](../../aspose.slides/pviobject/equals)(object) | Confronta con l'oggetto specificato. |
| override [GetHashCode](../../aspose.slides/pviobject/gethashcode)() | Restituisce il codice hash. |

### Osservazioni

Questa classe è usata per restituire e manipolare le proprietà di formattazione della porzione di testo definite per la porzione specifica. Ciò significa che nessuna ereditarietà viene applicata quando si ottengono i valori, quindi nella maggior parte dei casi otterrete valori che significano "non definito".

Per ottenere i valori effettivi dei parametri di formattazione inclusa l'ereditarietà è necessario utilizzare il metodo [`GetEffective`](../../aspose.slides/portionformat/geteffective) che restituisce un'istanza [`IPortionFormatEffectiveData`](../../aspose.slides/iportionformateffectivedata).

### Vedi anche

* classe [BasePortionFormat](../../aspose.slides/baseportionformat)
* interfaccia [IChartPortionFormat](../ichartportionformat)
* spazio dei nomi [Aspose.Slides.Charts](../../aspose.slides.charts)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->