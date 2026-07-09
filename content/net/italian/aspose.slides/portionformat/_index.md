---
title: PortionFormat
second_title: Riferimento API di Aspose.Sildes per .NET
description: Questa classe contiene le proprietà di formattazione della porzione di testo. A differenza di IPortionFormatEffectiveData./iportionformateffectivedata tutte le proprietà di questa classe sono scrivibili.
type: docs
weight: 9490
url: /it/aspose.slides/portionformat/
---
## PortionFormat classe

Questa classe contiene le proprietà di formattazione della porzione di testo. A differenza di [`IPortionFormatEffectiveData`](../iportionformateffectivedata), tutte le proprietà di questa classe sono scrivibili.

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
| [AlternativeLanguageId](../../aspose.slides/baseportionformat/alternativelanguageid) { get; set; } | Restituisce o imposta l'Id di una lingua alternativa. Lettura/Scrittura String. |
| [AsIPresentationComponent](../../aspose.slides/pviobject/asipresentationcomponent) { get; } | Consente di ottenere l'interfaccia base IPresentationComponent. Solo lettura [`IPresentationComponent`](../ipresentationcomponent). |
| [BookmarkId](../../aspose.slides/portionformat/bookmarkid) { get; set; } | Restituisce o imposta l'identificatore del segnalibro. Lettura/Scrittura String. |
| [ComplexScriptFont](../../aspose.slides/baseportionformat/complexscriptfont) { get; set; } | Restituisce o imposta le informazioni sul font per script complessi. Null indica che il font non è definito e dovrebbe essere ereditato dal Master. Lettura/Scrittura [`IFontData`](../ifontdata). |
| [EastAsianFont](../../aspose.slides/baseportionformat/eastasianfont) { get; set; } | Restituisce o imposta le informazioni sul font East Asian. Null indica che il font non è definito e dovrebbe essere ereditato dal Master. Lettura/Scrittura [`IFontData`](../ifontdata). |
| [EffectFormat](../../aspose.slides/baseportionformat/effectformat) { get; } | Restituisce le proprietà EffectFormat del testo. Nessuna ereditarietà applicata. Solo lettura [`IEffectFormat`](../ieffectformat). |
| [Escapement](../../aspose.slides/baseportionformat/escapement) { get; set; } | Restituisce o imposta il testo in apice o pedice. Valore da -100% (pedice) a 100% (apice). **float.NaN** indica valore non definito e dovrebbe essere ereditato dal Master. Lettura/Scrittura Single. |
| [FillFormat](../../aspose.slides/baseportionformat/fillformat) { get; } | Restituisce le proprietà FillFormat del testo. Nessuna ereditarietà applicata. Solo lettura [`IFillFormat`](../ifillformat). |
| [FontBold](../../aspose.slides/baseportionformat/fontbold) { get; set; } | Determina se il font è in grassetto. Nessuna ereditarietà applicata. Lettura/Scrittura [`NullableBool`](../nullablebool). |
| [FontHeight](../../aspose.slides/baseportionformat/fontheight) { get; set; } | Restituisce o imposta l'altezza del font di una porzione. **float.NaN** indica altezza non definita e dovrebbe essere ereditata dal Master. Lettura/Scrittura Single. |
| [FontItalic](../../aspose.slides/baseportionformat/fontitalic) { get; set; } | Determina se il font è corsivo. Nessuna ereditarietà applicata. Lettura/Scrittura [`NullableBool`](../nullablebool). |
| [FontUnderline](../../aspose.slides/baseportionformat/fontunderline) { get; set; } | Restituisce o imposta il tipo di sottolineatura del testo. Nessuna ereditarietà applicata. Lettura/Scrittura [`TextUnderlineType`](../textunderlinetype). |
| [HighlightColor](../../aspose.slides/baseportionformat/highlightcolor) { get; } | Restituisce il colore usato per evidenziare il testo. Nessuna ereditarietà applicata. Solo lettura [`IColorFormat`](../icolorformat). |
| [HyperlinkClick](../../aspose.slides/portionformat/hyperlinkclick) { get; set; } | Restituisce o imposta l'ipervincolo definito per il click del mouse. Lettura/Scrittura [`IHyperlink`](../ihyperlink). |
| [HyperlinkManager](../../aspose.slides/portionformat/hyperlinkmanager) { get; } | Gestore degli ipervincoli. Solo lettura [`IHyperlinkManager`](../ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/portionformat/hyperlinkmouseover) { get; set; } | Restituisce o imposta l'ipervincolo definito per il passaggio del mouse. Lettura/Scrittura [`IHyperlink`](../ihyperlink). |
| [IsHardUnderlineFill](../../aspose.slides/baseportionformat/ishardunderlinefill) { get; set; } | Determina se lo stile di sottolineatura possiede proprie proprietà FillFormat o le eredita dalle proprietà FillFormat del testo. Lettura/Scrittura [`NullableBool`](../nullablebool). |
| [IsHardUnderlineLine](../../aspose.slides/baseportionformat/ishardunderlineline) { get; set; } | Determina se lo stile di sottolineatura possiede proprie proprietà LineFormat o le eredita dalle proprietà LineFormat del testo. Lettura/Scrittura [`NullableBool`](../nullablebool). |
| [KerningMinimalSize](../../aspose.slides/baseportionformat/kerningminimalsize) { get; set; } | Restituisce o imposta la dimensione minima del font per cui il kerning deve essere attivato. **float.NaN** indica valore non definito e dovrebbe essere ereditato dal Master. Lettura/Scrittura Single. |
| [Kumimoji](../../aspose.slides/baseportionformat/kumimoji) { get; set; } | Determina se i numeri devono ignorare il layout verticale del testo specifico per lingue dell'Est. Nessuna ereditarietà applicata. Lettura/Scrittura [`NullableBool`](../nullablebool). |
| [LanguageId](../../aspose.slides/baseportionformat/languageid) { get; set; } | Restituisce o imposta l'Id di una lingua di correzione. Usato per il controllo ortografico e grammaticale. Lettura/Scrittura String. |
| [LatinFont](../../aspose.slides/baseportionformat/latinfont) { get; set; } | Restituisce o imposta le informazioni sul font Latin. Null indica che il font non è definito e dovrebbe essere ereditato dal Master. Lettura/Scrittura [`IFontData`](../ifontdata). |
| [LineFormat](../../aspose.slides/baseportionformat/lineformat) { get; } | Restituisce le proprietà LineFormat per il contorno del testo. Nessuna ereditarietà applicata. Solo lettura [`ILineFormat`](../ilineformat). |
| [NormaliseHeight](../../aspose.slides/baseportionformat/normaliseheight) { get; set; } | Determina se l'altezza del testo deve essere normalizzata. Nessuna ereditarietà applicata. Lettura/Scrittura [`NullableBool`](../nullablebool). |
| [ProofDisabled](../../aspose.slides/baseportionformat/proofdisabled) { get; set; } | Determina se il testo non deve essere corretto. Nessuna ereditarietà applicata. Lettura/Scrittura [`NullableBool`](../nullablebool). |
| [SmartTagClean](../../aspose.slides/portionformat/smarttagclean) { get; set; } | Determina se il smart tag deve essere pulito. Nessuna ereditarietà applicata. Lettura/Scrittura Boolean. |
| [Spacing](../../aspose.slides/baseportionformat/spacing) { get; set; } | Restituisce o imposta l'incremento della spaziatura intercarattere. **float.NaN** indica valore non definito e dovrebbe essere ereditato dal Master. Lettura/Scrittura Single. |
| [SpellCheck](../../aspose.slides/baseportionformat/spellcheck) { get; set; } | Ottiene o imposta un valore che indica se il controllo ortografico è abilitato per la porzione di testo. Quando questa proprietà è impostata su false, i controlli ortografici per gli elementi di testo sono soppressi. Quando impostata su true, il controllo ortografico è consentito. Valore predefinito è `false`. |
| [StrikethroughType](../../aspose.slides/baseportionformat/strikethroughtype) { get; set; } | Restituisce o imposta il tipo di barrato del testo. Nessuna ereditarietà applicata. Lettura/Scrittura [`TextStrikethroughType`](../textstrikethroughtype). |
| [SymbolFont](../../aspose.slides/baseportionformat/symbolfont) { get; set; } | Restituisce o imposta le informazioni sul font simbolico. Null indica che il font non è definito e dovrebbe essere ereditato dal Master. Lettura/Scrittura [`IFontData`](../ifontdata). |
| [TextCapType](../../aspose.slides/baseportionformat/textcaptype) { get; set; } | Restituisce o imposta il tipo di capitalizzazione del testo. Nessuna ereditarietà applicata. Lettura/Scrittura [`TextCapType`](../textcaptype). |
| [UnderlineFillFormat](../../aspose.slides/baseportionformat/underlinefillformat) { get; } | Restituisce le proprietà FillFormat della linea di sottolineatura. Nessuna ereditarietà applicata. Solo lettura [`IFillFormat`](../ifillformat). |
| [UnderlineLineFormat](../../aspose.slides/baseportionformat/underlinelineformat) { get; } | Restituisce le proprietà LineFormat usate per contornare la linea di sottolineatura. Nessuna ereditarietà applicata. Solo lettura [`ILineFormat`](../ilineformat). |

## Metodi

| Nome | Descrizione |
| --- | --- |
| override [Equals](../../aspose.slides/pviobject/equals)(object) | Confronta con l'oggetto specificato. |
| [GetEffective](../../aspose.slides/portionformat/geteffective)() | Ottiene i dati di formattazione della porzione efficace con l'ereditarietà applicata. |
| override [GetHashCode](../../aspose.slides/pviobject/gethashcode)() | Restituisce il codice hash. |

### Note

Questa classe è usata per restituire e manipolare le proprietà di formattazione della porzione di testo definite per la porzione specifica. Ciò significa che nessuna ereditarietà è applicata quando si ottengono i valori, quindi nella maggior parte dei casi otterrete valori che indicano “non definito”.

Per ottenere i valori dei parametri di formattazione effettivi, inclusi quelli ereditati, è necessario usare il metodo [`GetEffective`](./geteffective) che restituisce un'istanza [`IPortionFormatEffectiveData`](../iportionformateffectivedata).

### Esempi

Il seguente esempio mostra come assegnare il font latino a una porzione di Paragraph di una presentazione PowerPoint.

```csharp
[C#]
//Instanziare un oggetto Presentation che rappresenta un file di presentazione
using (Presentation pres = new Presentation("demo.pptx"))
{
IAutoShape shape = pres.Slides[0].Shapes.AddAutoShape(ShapeType.Rectangle, 10, 10, 100, 100);
Paragraph paragraph = new Paragraph();
Portion portion = new Portion("Theme text format");
paragraph.Portions.Add(portion);
shape.TextFrame.Paragraphs.Add(paragraph);
// Aspose.Slides utilizza questi identificatori speciali (simili a quelli usati in PowerPoint):
// +mn-lt - Font del corpo Latin (Font Latin Minore)
// +mj-lt - Font dell'intestazione Latin (Font Latin Maggiore)
// +mn-ea - Font del corpo East Asian (Font East Asian Minore)
// +mj-ea - Font del corpo East Asian (Font East Asian Minore)
portion.PortionFormat.LatinFont = new FontData("+mn-lt");
}
```

### Vedi anche

* classe [BasePortionFormat](../baseportionformat)
* interfaccia [IPortionFormat](../iportionformat)
* namespace [Aspose.Slides](../../aspose.slides)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->