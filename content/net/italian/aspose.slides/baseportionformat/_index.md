---
title: BasePortionFormat
second_title: Riferimento API Aspose.Sildes per .NET
description: Proprietà comuni di formattazione delle parti di testo.
type: docs
weight: 970
url: /it/aspose.slides/baseportionformat/
---
## BasePortionFormat classe

Proprietà comuni di formattazione delle parti di testo.

```csharp
public abstract class BasePortionFormat : PVIObject, IBasePortionFormat
```

## Proprietà

| Name | Description |
| --- | --- |
| [AlternativeLanguageId](../../aspose.slides/baseportionformat/alternativelanguageid) { get; set; } | Restituisce o imposta l'Id di una lingua alternativa. Lettura/scrittura String. |
| [AsIPresentationComponent](../../aspose.slides/pviobject/asipresentationcomponent) { get; } | Consente di ottenere l'interfaccia base IPresentationComponent. Solo lettura [`IPresentationComponent`](../ipresentationcomponent). |
| [ComplexScriptFont](../../aspose.slides/baseportionformat/complexscriptfont) { get; set; } | Restituisce o imposta le informazioni del font per script complessi. Null significa che il font non è definito e dovrebbe essere ereditato dal Master. Lettura/scrittura [`IFontData`](../ifontdata). |
| [EastAsianFont](../../aspose.slides/baseportionformat/eastasianfont) { get; set; } | Restituisce o imposta le informazioni del font East Asian. Null significa che il font non è definito e dovrebbe essere ereditato dal Master. Lettura/scrittura [`IFontData`](../ifontdata). |
| [EffectFormat](../../aspose.slides/baseportionformat/effectformat) { get; } | Restituisce le proprietà EffectFormat del testo. Nessuna ereditarietà applicata. Solo lettura [`IEffectFormat`](../ieffectformat). |
| [Escapement](../../aspose.slides/baseportionformat/escapement) { get; set; } | Restituisce o imposta il testo in apice o pedice. Valore da -100% (pedice) a 100% (apice). **float.NaN** significa che il valore non è definito e dovrebbe essere ereditato dal Master. Lettura/scrittura Single. |
| [FillFormat](../../aspose.slides/baseportionformat/fillformat) { get; } | Restituisce le proprietà FillFormat del testo. Nessuna ereditarietà applicata. Solo lettura [`IFillFormat`](../ifillformat). |
| [FontBold](../../aspose.slides/baseportionformat/fontbold) { get; set; } | Determina se il font è grassetto. Nessuna ereditarietà applicata. Lettura/scrittura [`NullableBool`](../nullablebool). |
| [FontHeight](../../aspose.slides/baseportionformat/fontheight) { get; set; } | Restituisce o imposta l'altezza del font di una parte. **float.NaN** significa che l'altezza non è definita e dovrebbe essere ereditata dal Master. Lettura/scrittura Single. |
| [FontItalic](../../aspose.slides/baseportionformat/fontitalic) { get; set; } | Determina se il font è corsivo. Nessuna ereditarietà applicata. Lettura/scrittura [`NullableBool`](../nullablebool). |
| [FontUnderline](../../aspose.slides/baseportionformat/fontunderline) { get; set; } | Restituisce o imposta il tipo di sottolineatura del testo. Nessuna ereditarietà applicata. Lettura/scrittura [`TextUnderlineType`](../textunderlinetype). |
| [HighlightColor](../../aspose.slides/baseportionformat/highlightcolor) { get; } | Restituisce il colore usato per evidenziare un testo. Nessuna ereditarietà applicata. Solo lettura [`IColorFormat`](../icolorformat). |
| [IsHardUnderlineFill](../../aspose.slides/baseportionformat/ishardunderlinefill) { get; set; } | Determina se lo stile di sottolineatura ha proprie proprietà FillFormat o le eredita dalle proprietà FillFormat del testo. Lettura/scrittura [`NullableBool`](../nullablebool). |
| [IsHardUnderlineLine](../../aspose.slides/baseportionformat/ishardunderlineline) { get; set; } | Determina se lo stile di sottolineatura ha proprie proprietà LineFormat o le eredita dalle proprietà LineFormat del testo. Lettura/scrittura [`NullableBool`](../nullablebool). |
| [KerningMinimalSize](../../aspose.slides/baseportionformat/kerningminimalsize) { get; set; } | Restituisce o imposta la dimensione minima del carattere per la quale il kerning dovrebbe essere attivato. **float.NaN** significa che il valore non è definito e dovrebbe essere ereditato dal Master. Lettura/scrittura Single. |
| [Kumimoji](../../aspose.slides/baseportionformat/kumimoji) { get; set; } | Determina se i numeri devono ignorare il layout verticale del testo specifico delle lingue orientali. Nessuna ereditarietà applicata. Lettura/scrittura [`NullableBool`](../nullablebool). |
| [LanguageId](../../aspose.slides/baseportionformat/languageid) { get; set; } | Restituisce o imposta l'Id di una lingua di correzione. Usato per il controllo ortografico e grammaticale. Lettura/scrittura String. |
| [LatinFont](../../aspose.slides/baseportionformat/latinfont) { get; set; } | Restituisce o imposta le informazioni del font latino. Null significa che il font non è definito e dovrebbe essere ereditato dal Master. Lettura/scrittura [`IFontData`](../ifontdata). |
| [LineFormat](../../aspose.slides/baseportionformat/lineformat) { get; } | Restituisce le proprietà LineFormat per il contorno del testo. Nessuna ereditarietà applicata. Solo lettura [`ILineFormat`](../ilineformat). |
| [NormaliseHeight](../../aspose.slides/baseportionformat/normaliseheight) { get; set; } | Determina se l'altezza di un testo deve essere normalizzata. Nessuna ereditarietà applicata. Lettura/scrittura [`NullableBool`](../nullablebool). |
| [ProofDisabled](../../aspose.slides/baseportionformat/proofdisabled) { get; set; } | Determina se il testo non deve essere corretto. Nessuna ereditarietà applicata. Lettura/scrittura [`NullableBool`](../nullablebool). |
| [Spacing](../../aspose.slides/baseportionformat/spacing) { get; set; } | Restituisce o imposta l'incremento della spaziatura intercarattere. **float.NaN** significa che il valore non è definito e dovrebbe essere ereditato dal Master. Lettura/scrittura Single. |
| [SpellCheck](../../aspose.slides/baseportionformat/spellcheck) { get; set; } | Ottiene o imposta un valore che indica se il controllo ortografico è abilitato per la parte di testo. Quando questa proprietà è impostata su false, i controlli ortografici per gli elementi di testo sono soppressi. Quando impostata su true, il controllo ortografico è consentito. Il valore predefinito è `false`. |
| [StrikethroughType](../../aspose.slides/baseportionformat/strikethroughtype) { get; set; } | Restituisce o imposta il tipo di barrato del testo. Nessuna ereditarietà applicata. Lettura/scrittura [`TextStrikethroughType`](../textstrikethroughtype). |
| [SymbolFont](../../aspose.slides/baseportionformat/symbolfont) { get; set; } | Restituisce o imposta le informazioni del font simbolico. Null significa che il font non è definito e dovrebbe essere ereditato dal Master. Lettura/scrittura [`IFontData`](../ifontdata). |
| [TextCapType](../../aspose.slides/baseportionformat/textcaptype) { get; set; } | Restituisce o imposta il tipo di capitalizzazione del testo. Nessuna ereditarietà applicata. Lettura/scrittura [`TextCapType`](../textcaptype). |
| [UnderlineFillFormat](../../aspose.slides/baseportionformat/underlinefillformat) { get; } | Restituisce le proprietà FillFormat della linea di sottolineatura. Nessuna ereditarietà applicata. Solo lettura [`IFillFormat`](../ifillformat). |
| [UnderlineLineFormat](../../aspose.slides/baseportionformat/underlinelineformat) { get; } | Restituisce le proprietà LineFormat usate per delineare la linea di sottolineatura. Nessuna ereditarietà applicata. Solo lettura [`ILineFormat`](../ilineformat). |

## Metodi

| Name | Description |
| --- | --- |
| override [Equals](../../aspose.slides/pviobject/equals)(object) | Confronta con l'oggetto specificato. |
| override [GetHashCode](../../aspose.slides/pviobject/gethashcode)() | Restituisce il codice hash. |

### Vedi anche

* classe [PVIObject](../pviobject)
* interfaccia [IBasePortionFormat](../ibaseportionformat)
* spazio dei nomi [Aspose.Slides](../../aspose.slides)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->