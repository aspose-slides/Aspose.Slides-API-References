---
title: PortionFormat
second_title: Aspose.Slides für .NET API-Referenz
description: Diese Klasse enthält die Eigenschaften der Textportionenformatierung. Im Gegensatz zu IPortionFormatEffectiveData../iportionformateffectivedata sind alle Eigenschaften dieser Klasse beschreibbar.
type: docs
weight: 9220
url: /de/aspose.slides/portionformat/
---

## PortionFormat-Klasse

Diese Klasse enthält die Eigenschaften der Textportionenformatierung. Im Gegensatz zu [`IPortionFormatEffectiveData`](../iportionformateffectivedata) sind alle Eigenschaften dieser Klasse beschreibbar.

```csharp
public sealed class PortionFormat : BasePortionFormat, IPortionFormat
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [PortionFormat](portionformat)() | Initialisiert eine neue Instanz der [`PortionFormat`](../portionformat)-Klasse. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [AlternativeLanguageId](../../aspose.slides/baseportionformat/alternativelanguageid) { get; set; } | Gibt die Id einer alternativen Sprache zurück oder setzt sie. Lese-/schreibbarer String. |
| [AsIPresentationComponent](../../aspose.slides/pviobject/asipresentationcomponent) { get; } | Ermöglicht das Abrufen der Basisschnittstelle IPresentationComponent. Nur lesbar [`IPresentationComponent`](../ipresentationcomponent). |
| [BookmarkId](../../aspose.slides/portionformat/bookmarkid) { get; set; } | Gibt die Kennung des Lesezeichens zurück oder setzt sie. Lese-/schreibbarer String. |
| [ComplexScriptFont](../../aspose.slides/baseportionformat/complexscriptfont) { get; set; } | Gibt die Informationen zur komplexen Schriftart zurück oder setzt sie. Null bedeutet, dass die Schriftart undefiniert ist und vom Master übernommen werden sollte. Lese-/schreibbarer [`IFontData`](../ifontdata). |
| [EastAsianFont](../../aspose.slides/baseportionformat/eastasianfont) { get; set; } | Gibt die Informationen zur ostasiatischen Schriftart zurück oder setzt sie. Null bedeutet, dass die Schriftart undefiniert ist und vom Master übernommen werden sollte. Lese-/schreibbarer [`IFontData`](../ifontdata). |
| [EffectFormat](../../aspose.slides/baseportionformat/effectformat) { get; } | Gibt die Eigenschaften des Text-Effektformats zurück. Keine Vererbung angewendet. Nur lesbar [`IEffectFormat`](../ieffectformat). |
| [Escapement](../../aspose.slides/baseportionformat/escapement) { get; set; } | Gibt den Hoch- oder Tiefstellungstext zurück oder setzt ihn. Wert von -100 % (Tiefstellung) bis 100 % (Hochstellung). **float.NaN** bedeutet, dass der Wert undefiniert ist und vom Master übernommen werden sollte. Lese-/schreibbarer Single. |
| [FillFormat](../../aspose.slides/baseportionformat/fillformat) { get; } | Gibt die Eigenschaften des Text-Füllformats zurück. Keine Vererbung angewendet. Nur lesbar [`IFillFormat`](../ifillformat). |
| [FontBold](../../aspose.slides/baseportionformat/fontbold) { get; set; } | Bestimmt, ob die Schriftart fett ist. Keine Vererbung angewendet. Lese-/schreibbarer [`NullableBool`](../nullablebool). |
| [FontHeight](../../aspose.slides/baseportionformat/fontheight) { get; set; } | Gibt die Schriftgröße einer Portion zurück oder setzt sie. **float.NaN** bedeutet, dass die Größe undefiniert ist und vom Master übernommen werden sollte. Lese-/schreibbarer Single. |
| [FontItalic](../../aspose.slides/baseportionformat/fontitalic) { get; set; } | Bestimmt, ob die Schriftart kursiv ist. Keine Vererbung angewendet. Lese-/schreibbarer [`NullableBool`](../nullablebool). |
| [FontUnderline](../../aspose.slides/baseportionformat/fontunderline) { get; set; } | Gibt den Typ der Textunterstreichung zurück oder setzt ihn. Keine Vererbung angewendet. Lese-/schreibbarer [`TextUnderlineType`](../textunderlinetype). |
| [HighlightColor](../../aspose.slides/baseportionformat/highlightcolor) { get; } | Gibt die Farbe zurück, die zum Hervorheben eines Textes verwendet wird. Keine Vererbung angewendet. Nur lesbar [`IColorFormat`](../icolorformat). |
| [HyperlinkClick](../../aspose.slides/portionformat/hyperlinkclick) { get; set; } | Gibt den für Mausklick definierten Hyperlink zurück oder setzt ihn. Lese-/schreibbarer [`IHyperlink`](../ihyperlink). |
| [HyperlinkManager](../../aspose.slides/portionformat/hyperlinkmanager) { get; } | Hyperlink-Manager. Nur lesbar [`IHyperlinkManager`](../ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/portionformat/hyperlinkmouseover) { get; set; } | Gibt den für Mouseover definierten Hyperlink zurück oder setzt ihn. Lese-/schreibbarer [`IHyperlink`](../ihyperlink). |
| [IsHardUnderlineFill](../../aspose.slides/baseportionformat/ishardunderlinefill) { get; set; } | Bestimmt, ob der Unterstreichungsstil eigene Füllformat-Eigenschaften hat oder sie von den Füllformat-Eigenschaften des Textes übernimmt. Lese-/schreibbarer [`NullableBool`](../nullablebool). |
| [IsHardUnderlineLine](../../aspose.slides/baseportionformat/ishardunderlineline) { get; set; } | Bestimmt, ob der Unterstreichungsstil eigene Linienformat-Eigenschaften hat oder sie von den Linienformat-Eigenschaften des Textes übernimmt. Lese-/schreibbarer [`NullableBool`](../nullablebool). |
| [KerningMinimalSize](../../aspose.slides/baseportionformat/kerningminimalsize) { get; set; } | Gibt die minimale Schriftgröße zurück oder setzt sie, für die das Kerning aktiviert werden sollte. **float.NaN** bedeutet, dass der Wert undefiniert ist und vom Master übernommen werden sollte. Lese-/schreibbarer Single. |
| [Kumimoji](../../aspose.slides/baseportionformat/kumimoji) { get; set; } | Bestimmt, ob die Zahlen das vertikale Layout der östlichen Sprache ignorieren sollen. Keine Vererbung angewendet. Lese-/schreibbarer [`NullableBool`](../nullablebool). |
| [LanguageId](../../aspose.slides/baseportionformat/languageid) { get; set; } | Gibt die Id einer Korrektursprache zurück oder setzt sie. Wird zur Überprüfung von Rechtschreibung und Grammatik verwendet. Lese-/schreibbarer String. |
| [LatinFont](../../aspose.slides/baseportionformat/latinfont) { get; set; } | Gibt die Informationen zur lateinischen Schriftart zurück oder setzt sie. Null bedeutet, dass die Schriftart undefiniert ist und vom Master übernommen werden sollte. Lese-/schreibbarer [`IFontData`](../ifontdata). |
| [LineFormat](../../aspose.slides/baseportionformat/lineformat) { get; } | Gibt die Linienformat-Eigenschaften für die Textumrissgebung zurück. Keine Vererbung angewendet. Nur lesbar [`ILineFormat`](../ilineformat). |
| [NormaliseHeight](../../aspose.slides/baseportionformat/normaliseheight) { get; set; } | Bestimmt, ob die Höhe eines Textes normalisiert werden soll. Keine Vererbung angewendet. Lese-/schreibbarer [`NullableBool`](../nullablebool). |
| [ProofDisabled](../../aspose.slides/baseportionformat/proofdisabled) { get; set; } | Bestimmt, ob der Text nicht korrigiert werden sollte. Keine Vererbung angewendet. Lese-/schreibbarer [`NullableBool`](../nullablebool). |
| [SmartTagClean](../../aspose.slides/portionformat/smarttagclean) { get; set; } | Bestimmt, ob der Smart Tag bereinigt werden soll. Keine Vererbung angewendet. Lese-/schreibbarer Boolean. |
| [Spacing](../../aspose.slides/baseportionformat/spacing) { get; set; } | Gibt den Abstand zwischen den Zeichen zurück oder setzt ihn. **float.NaN** bedeutet, dass der Wert undefiniert ist und vom Master übernommen werden sollte. Lese-/schreibbarer Single. |
| [StrikethroughType](../../aspose.slides/baseportionformat/strikethroughtype) { get; set; } | Gibt den Typ der Durchstreichung eines Textes zurück oder setzt ihn. Keine Vererbung angewendet. Lese-/schreibbarer [`TextStrikethroughType`](../textstrikethroughtype). |
| [SymbolFont](../../aspose.slides/baseportionformat/symbolfont) { get; set; } | Gibt die Informationen zur symbolischen Schriftart zurück oder setzt sie. Null bedeutet, dass die Schriftart undefiniert ist und vom Master übernommen werden sollte. Lese-/schreibbarer [`IFontData`](../ifontdata). |
| [TextCapType](../../aspose.slides/baseportionformat/textcaptype) { get; set; } | Gibt den Typ der Textgroßschreibung zurück oder setzt ihn. Keine Vererbung angewendet. Lese-/schreibbarer [`TextCapType`](../textcaptype). |
| [UnderlineFillFormat](../../aspose.slides/baseportionformat/underlinefillformat) { get; } | Gibt die Füllformat-Eigenschaften der Unterstreichungslinie zurück. Keine Vererbung angewendet. Nur lesbar [`IFillFormat`](../ifillformat). |
| [UnderlineLineFormat](../../aspose.slides/baseportionformat/underlinelineformat) { get; } | Gibt die Linienformat-Eigenschaften zurück, die zum Umreißen der Unterstreichungslinie verwendet werden. Keine Vererbung angewendet. Nur lesbar [`ILineFormat`](../ilineformat). |

## Methoden

| Name | Beschreibung |
| --- | --- |
| override [Equals](../../aspose.slides/pviobject/equals)(object) | Vergleicht mit dem angegebenen Objekt. |
| [GetEffective](../../aspose.slides/portionformat/geteffective)() | Holt die effektiven Formatierungsdaten der Portion mit der angewendeten Vererbung. |
| override [GetHashCode](../../aspose.slides/pviobject/gethashcode)() | Gibt den Hash-Code zurück. |

### Bemerkungen

Diese Klasse wird verwendet, um die Eigenschaften der Textportionenformatierung zurückzugeben und zu manipulieren, die für die jeweilige Portion definiert sind. Das bedeutet, dass bei der Abfrage von Werten keine Vererbung angewendet wird, sodass man in den meisten Fällen Werte erhält, die "undefiniert" bedeuten.

Um die effektiven Formatierungsparameterwerte einschließlich der vererbten Werte zu erhalten, müssen Sie die Methode [`GetEffective`](./geteffective) verwenden, die eine Instanz von [`IPortionFormatEffectiveData`](../iportionformateffectivedata) zurückgibt.

### Beispiele

Die folgenden Beispiele zeigen, wie man die lateinische Schriftart für eine Portion eines Absatzes in einer PowerPoint-Präsentation zuweist.

```csharp
[C#]
//Instantiate a presentation object that represents a presentation file
using (Presentation pres = new Presentation("demo.pptx"))
{
IAutoShape shape = pres.Slides[0].Shapes.AddAutoShape(ShapeType.Rectangle, 10, 10, 100, 100);
Paragraph paragraph = new Paragraph();
Portion portion = new Portion("Theme text format");
paragraph.Portions.Add(portion);
shape.TextFrame.Paragraphs.Add(paragraph);
// Aspose.Slides verwendet diese speziellen Identifikatoren (ähnlich denen, die in PowerPoint verwendet werden):
// +mn-lt - Textschriftart Latein (Minor Latin Font)
// +mj-lt - Überschrift Schriftart Latein (Major Latin Font)
// +mn-ea - Textschriftart Ostasiatisch (Minor East Asian Font)
// +mj-ea - Textschriftart Ostasiatisch (Minor East Asian Font)
portion.PortionFormat.LatinFont = new FontData("+mn-lt");
}
```

### Siehe auch

* Klasse [BasePortionFormat](../baseportionformat)
* Schnittstelle [IPortionFormat](../iportionformat)
* Namespace [Aspose.Slides](../../aspose.slides)
* Assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->