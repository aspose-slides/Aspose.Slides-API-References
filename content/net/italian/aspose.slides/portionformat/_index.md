---
title: PortionFormat
second_title: Riferimento API Aspose.Sildes per .NET
description: Questa classe contiene le proprietà di formattazione della porzione di testo. A differenza di IPortionFormatEffectiveData./iportionformateffectivedata, tutte le proprietà di questa classe sono modificabili.
type: docs
weight: 9470
url: /it/aspose.slides/portionformat/
---
## PortionFormat classe

Questa classe contiene le proprietà di formattazione della porzione di testo. A differenza di [`IPortionFormatEffectiveData`](../iportionformateffectivedata), tutte le proprietà di questa classe sono modificabili.

```csharp
public sealed class PortionFormat : BasePortionFormat, IPortionFormat
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [PortionFormat](portionformat)() | Inizializza una nuova istanza della classe [`PortionFormat`](../portionformat). |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [AlternativeLanguageId](../../aspose.slides/baseportionformat/alternativelanguageid) { get; set; } | Restituisce o imposta l'Id di una lingua alternativa. Lettura/scrittura String. |
| [AsIPresentationComponent](../../aspose.slides/pviobject/asipresentationcomponent) { get; } | Consente di ottenere l'interfaccia base IPresentationComponent. Sola lettura [`IPresentationComponent`](../ipresentationcomponent). |
| [BookmarkId](../../aspose.slides/portionformat/bookmarkid) { get; set; } | Restituisce o imposta l'identificatore del segnalibro. Lettura/scrittura String. |
| [ComplexScriptFont](../../aspose.slides/baseportionformat/complexscriptfont) { get; set; } | Restituisce o imposta le informazioni sul carattere script complesso. Null indica che il carattere non è definito e dovrebbe essere ereditato dal Master. Lettura/scrittura [`IFontData`](../ifontdata). |
| [EastAsianFont](../../aspose.slides/baseportionformat/eastasianfont) { get; set; } | Restituisce o imposta le informazioni sul carattere dell'Est asiatico. Null indica che il carattere non è definito e dovrebbe essere ereditato dal Master. Lettura/scrittura [`IFontData`](../ifontdata). |
| [EffectFormat](../../aspose.slides/baseportionformat/effectformat) { get; } | Restituisce le proprietà EffectFormat del testo. Nessuna ereditarietà applicata. Sola lettura [`IEffectFormat`](../ieffectformat). |
| [Escapement](../../aspose.slides/baseportionformat/escapement) { get; set; } | Restituisce o imposta il testo in apice o pedice. Valore da -100% (pedice) a 100% (apice). **float.NaN** indica che il valore non è definito e dovrebbe essere ereditato dal Master. Lettura/scrittura Single. |
| [FillFormat](../../aspose.slides/baseportionformat/fillformat) { get; } | Restituisce le proprietà FillFormat del testo. Nessuna ereditarietà applicata. Sola lettura [`IFillFormat`](../ifillformat). |
| [FontBold](../../aspose.slides/baseportionformat/fontbold) { get; set; } | Determina se il carattere è grassetto. Nessuna ereditarietà applicata. Lettura/scrittura [`NullableBool`](../nullablebool). |
| [FontHeight](../../aspose.slides/baseportionformat/fontheight) { get; set; } | Restituisce o imposta l'altezza del carattere di una porzione. **float.NaN** indica che l'altezza non è definita e dovrebbe essere ereditata dal Master. Lettura/scrittura Single. |
| [FontItalic](../../aspose.slides/baseportionformat/fontitalic) { get; set; } | Determina se il carattere è corsivo. Nessuna ereditarietà applicata. Lettura/scrittura [`NullableBool`](../nullablebool). |
| [FontUnderline](../../aspose.slides/baseportionformat/fontunderline) { get; set; } | Restituisce o imposta il tipo di sottolineatura del testo. Nessuna ereditarietà applicata. Lettura/scrittura [`TextUnderlineType`](../textunderlinetype). |
| [HighlightColor](../../aspose.slides/baseportionformat/highlightcolor) { get; } | Restituisce il colore usato per evidenziare un testo. Nessuna ereditarietà applicata. Sola lettura [`IColorFormat`](../icolorformat). |
| [HyperlinkClick](../../aspose.slides/portionformat/hyperlinkclick) { get; set; } | Restituisce o imposta il collegamento ipertestuale definito per il click del mouse. Lettura/scrittura [`IHyperlink`](../ihyperlink). |
| [HyperlinkManager](../../aspose.slides/portionformat/hyperlinkmanager) { get; } | Gestore dei collegamenti ipertestuali. Sola lettura [`IHyperlinkManager`](../ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/portionformat/hyperlinkmouseover) { get; set; } | Restituisce o imposta il collegamento ipertestuale definito per il passaggio del mouse. Lettura/scrittura [`IHyperlink`](../ihyperlink). |
| [IsHardUnderlineFill](../../aspose.slides/baseportionformat/ishardunderlinefill) { get; set; } | Determina se lo stile di sottolineatura ha proprie proprietà FillFormat o le eredita dalle proprietà FillFormat del testo. Lettura/scrittura [`NullableBool`](../nullablebool). |
| [IsHardUnderlineLine](../../aspose.slides/baseportionformat/ishardunderlineline) { get; set; } | Determina se lo stile di sottolineatura ha proprie proprietà LineFormat o le eredita dalle proprietà LineFormat del testo. Lettura/scrittura [`NullableBool`](../nullablebool). |
| [KerningMinimalSize](../../aspose.slides/baseportionformat/kerningminimalsize) { get; set; } | Restituisce o imposta la dimensione minima del carattere per cui il kerning deve essere attivato. **float.NaN** indica che il valore non è definito e dovrebbe essere ereditato dal Master. Lettura/scrittura Single. |
| [Kumimoji](../../aspose.slides/baseportionformat/kumimoji) { get; set; } | Determina se i numeri devono ignorare il layout verticale del testo specifico per le lingue dell'Est. Nessuna ereditarietà applicata. Lettura/scrittura [`NullableBool`](../nullablebool). |
| [LanguageId](../../aspose.slides/baseportionformat/languageid) { get; set; } | Restituisce o imposta l'Id di una lingua di correzione. Usata per il controllo ortografico e grammaticale. Lettura/scrittura String. |
| [LatinFont](../../aspose.slides/baseportionformat/latinfont) { get; set; } | Restituisce o imposta le informazioni sul carattere latino. Null indica che il carattere non è definito e dovrebbe essere ereditato dal Master. Lettura/scrittura [`IFontData`](../ifontdata). |
| [LineFormat](../../aspose.slides/baseportionformat/lineformat) { get; } | Restituisce le proprietà LineFormat per il contorno del testo. Nessuna ereditarietà applicata. Sola lettura [`ILineFormat`](../ilineformat). |
| [NormaliseHeight](../../aspose.slides/baseportionformat/normaliseheight) { get; set; } | Determina se l'altezza di un testo dovrebbe essere normalizzata. Nessuna ereditarietà applicata. Lettura/scrittura [`NullableBool`](../nullablebool). |
| [ProofDisabled](../../aspose.slides/baseportionformat/proofdisabled) { get; set; } | Determina se il testo non dovrebbe essere corretto. Nessuna ereditarietà applicata. Lettura/scrittura [`NullableBool`](../nullablebool). |
| [SmartTagClean](../../aspose.slides/portionformat/smarttagclean) { get; set; } | Determina se il tag intelligente dovrebbe essere pulito. Nessuna ereditarietà applicata. Lettura/scrittura Boolean. |
| [Spacing](../../aspose.slides/baseportionformat/spacing) { get; set; } | Restituisce o imposta l'incremento della spaziatura intercarattere. **float.NaN** indica che il valore non è definito e dovrebbe essere ereditato dal Master. Lettura/scrittura Single. |
| [SpellCheck](../../aspose.slides/baseportionformat/spellcheck) { get; set; } | Ottiene o imposta un valore che indica se il controllo ortografico è abilitato per la porzione di testo. Quando questa proprietà è impostata su false, i controlli ortografici per gli elementi di testo sono soppressi. Quando è impostata su true, il controllo ortografico è consentito. Il valore predefinito è `false`. |
| [StrikethroughType](../../aspose.slides/baseportionformat/strikethroughtype) { get; set; } | Restituisce o imposta il tipo di barrato di un testo. Nessuna ereditarietà applicata. Lettura/scrittura [`TextStrikethroughType`](../textstrikethroughtype). |
| [SymbolFont](../../aspose.slides/baseportionformat/symbolfont) { get; set; } | Restituisce o imposta le informazioni sul carattere simbolico. Null indica che il carattere non è definito e dovrebbe essere ereditato dal Master. Lettura/scrittura [`IFontData`](../ifontdata). |
| [TextCapType](../../aspose.slides/baseportionformat/textcaptype) { get; set; } | Restituisce o imposta il tipo di capitalizzazione del testo. Nessuna ereditarietà applicata. Lettura/scrittura [`TextCapType`](../textcaptype). |
| [UnderlineFillFormat](../../aspose.slides/baseportionformat/underlinefillformat) { get; } | Restituisce le proprietà FillFormat della linea di sottolineatura. Nessuna ereditarietà applicata. Sola lettura [`IFillFormat`](../ifillformat). |
| [UnderlineLineFormat](../../aspose.slides/baseportionformat/underlinelineformat) { get; } | Restituisce le proprietà LineFormat usate per contornare la linea di sottolineatura. Nessuna ereditarietà applicata. Sola lettura [`ILineFormat`](../ilineformat). |

## Metodi

| Nome | Descrizione |
| --- | --- |
| override [Equals](../../aspose.slides/pviobject/equals)(object) | Confronta con l'oggetto specificato. |
| [GetEffective](../../aspose.slides/portionformat/geteffective)() | Ottiene i dati di formattazione della porzione efficaci con l'ereditarietà applicata. |
| override [GetHashCode](../../aspose.slides/pviobject/gethashcode)() | Restituisce il codice hash. |

### Osservazioni

Questa classe è utilizzata per restituire e manipolare le proprietà di formattazione della porzione di testo definite per la specifica porzione. Ciò significa che nessuna ereditarietà è applicata quando si ottengono i valori, quindi nella maggior parte dei casi si otterranno valori che indicano "non definito".

Per ottenere i valori dei parametri di formattazione efficaci includendo quelli ereditati è necessario utilizzare il metodo [`GetEffective`](./geteffective) che restituisce un'istanza di [`IPortionFormatEffectiveData`](../iportionformateffectivedata).

### Esempi

Il seguente esempio mostra come assegnare il carattere latino a una porzione di Paragraph di una Presentazione PowerPoint.

```csharp
[C#]
//Instanzia un oggetto presentation che rappresenta un file di presentazione
using (Presentation pres = new Presentation("demo.pptx"))
{
IAutoShape shape = pres.Slides[0].Shapes.AddAutoShape(ShapeType.Rectangle, 10, 10, 100, 100);
Paragraph paragraph = new Paragraph();
Portion portion = new Portion("Theme text format");
paragraph.Portions.Add(portion);
shape.TextFrame.Paragraphs.Add(paragraph);
// Aspose.Slides utilizza questi identificatori speciali (simili a quelli usati in PowerPoint):
// +mn-lt - Font latino del corpo (Font latino minore)
// +mj-lt -Font latino dell'intestazione (Font latino maggiore)
// +mn-ea - Font dell'Est asiatico del corpo (Font dell'Est asiatico minore)
// +mj-ea - Font dell'Est asiatico del corpo (Font dell'Est asiatico minore)
portion.PortionFormat.LatinFont = new FontData("+mn-lt");
}
```

### Vedi anche

* classe [BasePortionFormat](../baseportionformat)
* interfaccia [IPortionFormat](../iportionformat)
* spazio dei nomi [Aspose.Slides](../../aspose.slides)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->