---
title: ChartPortionFormat
second_title: Aspose.Slides für .NET API Referenz
description: Diese Klasse enthält die Formatierungseigenschaften für Diagrammabschnitte, die in Diagrammen verwendet werden. Im Gegensatz zu IPortionFormatEffectiveData../aspose.slides/iportionformateffectivedata sind alle Eigenschaften dieser Klasse schreibbar.
type: docs
weight: 1350
url: /de/aspose.slides.charts/chartportionformat/
---

## ChartPortionFormat-Klasse

Diese Klasse enthält die Formatierungseigenschaften für Diagrammabschnitte, die in Diagrammen verwendet werden. Im Gegensatz zu [`IPortionFormatEffectiveData`](../../aspose.slides/iportionformateffectivedata) sind alle Eigenschaften dieser Klasse schreibbar.

```csharp
public sealed class ChartPortionFormat : BasePortionFormat, IChartPortionFormat
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [AlternativeLanguageId](../../aspose.slides/baseportionformat/alternativelanguageid) { get; set; } | Gibt die ID einer alternativen Sprache zurück oder setzt sie. Lese-/Schreibzeichenfolge. |
| [AsIPresentationComponent](../../aspose.slides/pviobject/asipresentationcomponent) { get; } | Ermöglicht den Zugriff auf die Basis-IPresentationComponent-Schnittstelle. Schreibgeschützt [`IPresentationComponent`](../../aspose.slides/ipresentationcomponent). |
| [ComplexScriptFont](../../aspose.slides/baseportionformat/complexscriptfont) { get; set; } | Gibt die Informationen zur komplexen Schriftart zurück oder setzt sie. Null bedeutet, dass die Schriftart undefiniert ist und vom Master geerbt werden sollte. Lese-/Schreib [`IFontData`](../../aspose.slides/ifontdata). |
| [EastAsianFont](../../aspose.slides/baseportionformat/eastasianfont) { get; set; } | Gibt die Informationen zur ostasiatischen Schriftart zurück oder setzt sie. Null bedeutet, dass die Schriftart undefiniert ist und vom Master geerbt werden sollte. Lese-/Schreib [`IFontData`](../../aspose.slides/ifontdata). |
| [EffectFormat](../../aspose.slides/baseportionformat/effectformat) { get; } | Gibt die Texteigenschaften von EffectFormat zurück. Es wird keine Vererbung angewendet. Schreibgeschützt [`IEffectFormat`](../../aspose.slides/ieffectformat). |
| [Escapement](../../aspose.slides/baseportionformat/escapement) { get; set; } | Gibt den Hochgestellt- oder Tiefgestellt-Text zurück oder setzt ihn. Wert von -100 % (Tiefgestellt) bis 100 % (Hochgestellt). **float.NaN** bedeutet, dass der Wert undefiniert ist und vom Master geerbt werden sollte. Lese-/Schreib Geschoss. |
| [FillFormat](../../aspose.slides/baseportionformat/fillformat) { get; } | Gibt die Füllformatierungs-Eigenschaften für den Text zurück. Es wird keine Vererbung angewendet. Schreibgeschützt [`IFillFormat`](../../aspose.slides/ifillformat). |
| [FontBold](../../aspose.slides/baseportionformat/fontbold) { get; set; } | Bestimmt, ob die Schriftart fett ist. Es wird keine Vererbung angewendet. Lese-/Schreib [`NullableBool`](../../aspose.slides/nullablebool). |
| [FontHeight](../../aspose.slides/baseportionformat/fontheight) { get; set; } | Gibt die Schriftgrößenhöhe eines Abschnitts zurück oder setzt sie. **float.NaN** bedeutet, dass die Höhe undefiniert ist und vom Master geerbt werden sollte. Lese-/Schreib Geschoss. |
| [FontItalic](../../aspose.slides/baseportionformat/fontitalic) { get; set; } | Bestimmt, ob die Schriftart kursiv ist. Es wird keine Vererbung angewendet. Lese-/Schreib [`NullableBool`](../../aspose.slides/nullablebool). |
| [FontUnderline](../../aspose.slides/baseportionformat/fontunderline) { get; set; } | Gibt den Unterstreichungstyp des Textes zurück oder setzt ihn. Es wird keine Vererbung angewendet. Lese-/Schreib [`TextUnderlineType`](../../aspose.slides/textunderlinetype). |
| [HighlightColor](../../aspose.slides/baseportionformat/highlightcolor) { get; } | Gibt die Farbe zurück, die verwendet wird, um einen Text hervorzuheben. Es wird keine Vererbung angewendet. Schreibgeschützt [`IColorFormat`](../../aspose.slides/icolorformat). |
| [IsHardUnderlineFill](../../aspose.slides/baseportionformat/ishardunderlinefill) { get; set; } | Bestimmt, ob der Unterstreichungsstil eigene Füllformatierungs-Eigenschaften hat oder sie von den Füllformatierungs-Eigenschaften des Textes erbt. Lese-/Schreib [`NullableBool`](../../aspose.slides/nullablebool). |
| [IsHardUnderlineLine](../../aspose.slides/baseportionformat/ishardunderlineline) { get; set; } | Bestimmt, ob der Unterstreichungsstil eigene Linienformatierungs-Eigenschaften hat oder sie von den Linienformatierungs-Eigenschaften des Textes erbt. Lese-/Schreib [`NullableBool`](../../aspose.slides/nullablebool). |
| [KerningMinimalSize](../../aspose.slides/baseportionformat/kerningminimalsize) { get; set; } | Gibt die minimale Schriftgröße zurück oder setzt sie, bei der das Kerning aktiviert werden soll. **float.NaN** bedeutet, dass der Wert undefiniert ist und vom Master geerbt werden sollte. Lese-/Schreib Geschoss. |
| [Kumimoji](../../aspose.slides/baseportionformat/kumimoji) { get; set; } | Bestimmt, ob die Zahlen den spezifischen vertikalen Text-Layout der ostasiatischen Sprache ignorieren sollen. Es wird keine Vererbung angewendet. Lese-/Schreib [`NullableBool`](../../aspose.slides/nullablebool). |
| [LanguageId](../../aspose.slides/baseportionformat/languageid) { get; set; } | Gibt die ID einer Korrektursprache zurück oder setzt sie. Wird zur Überprüfung von Rechtschreibung und Grammatik verwendet. Lese-/Schreib Zeichenfolge. |
| [LatinFont](../../aspose.slides/baseportionformat/latinfont) { get; set; } | Gibt die Informationen zur lateinischen Schriftart zurück oder setzt sie. Null bedeutet, dass die Schriftart undefiniert ist und vom Master geerbt werden sollte. Lese-/Schreib [`IFontData`](../../aspose.slides/ifontdata). |
| [LineFormat](../../aspose.slides/baseportionformat/lineformat) { get; } | Gibt die Linienformatierungs-Eigenschaften für die Textkonturen zurück. Es wird keine Vererbung angewendet. Schreibgeschützt [`ILineFormat`](../../aspose.slides/ilineformat). |
| [NormaliseHeight](../../aspose.slides/baseportionformat/normaliseheight) { get; set; } | Bestimmt, ob die Höhe eines Textes normalisiert werden soll. Es wird keine Vererbung angewendet. Lese-/Schreib [`NullableBool`](../../aspose.slides/nullablebool). |
| [ProofDisabled](../../aspose.slides/baseportionformat/proofdisabled) { get; set; } | Bestimmt, ob der Text nicht geprüft werden soll. Es wird keine Vererbung angewendet. Lese-/Schreib [`NullableBool`](../../aspose.slides/nullablebool). |
| [Spacing](../../aspose.slides/baseportionformat/spacing) { get; set; } | Gibt die Zunahme zwischen den Zeichenabständen zurück oder setzt sie. **float.NaN** bedeutet, dass der Wert undefiniert ist und vom Master geerbt werden sollte. Lese-/Schreib Geschoss. |
| [StrikethroughType](../../aspose.slides/baseportionformat/strikethroughtype) { get; set; } | Gibt den Typ der Durchstreichung eines Textes zurück oder setzt ihn. Es wird keine Vererbung angewendet. Lese-/Schreib [`TextStrikethroughType`](../../aspose.slides/textstrikethroughtype). |
| [SymbolFont](../../aspose.slides/baseportionformat/symbolfont) { get; set; } | Gibt die Informationen zur symbolischen Schriftart zurück oder setzt sie. Null bedeutet, dass die Schriftart undefiniert ist und vom Master geerbt werden sollte. Lese-/Schreib [`IFontData`](../../aspose.slides/ifontdata). |
| [TextCapType](../../aspose.slides/baseportionformat/textcaptype) { get; set; } | Gibt den Typ der Textapitalisierung zurück oder setzt ihn. Es wird keine Vererbung angewendet. Lese-/Schreib [`TextCapType`](../../aspose.slides/textcaptype). |
| [UnderlineFillFormat](../../aspose.slides/baseportionformat/underlinefillformat) { get; } | Gibt die Füllformatierungs-Eigenschaften der Unterstreichungslinie zurück. Es wird keine Vererbung angewendet. Schreibgeschützt [`IFillFormat`](../../aspose.slides/ifillformat). |
| [UnderlineLineFormat](../../aspose.slides/baseportionformat/underlinelineformat) { get; } | Gibt die Linienformatierungs-Eigenschaften zurück, die verwendet werden, um die Unterstreichungslinie zu umreißen. Es wird keine Vererbung angewendet. Schreibgeschützt [`ILineFormat`](../../aspose.slides/ilineformat). |

## Methoden

| Name | Beschreibung |
| --- | --- |
| override [Equals](../../aspose.slides/pviobject/equals)(object) | Vergleicht mit dem angegebenen Objekt. |
| override [GetHashCode](../../aspose.slides/pviobject/gethashcode)() | Gibt den Hash-Code zurück. |

### Bemerkungen

Diese Klasse wird verwendet, um die für den bestimmten Abschnitt definierten Formatierungseigenschaften zurückzugeben und zu manipulieren. Dies bedeutet, dass keine Vererbung angewendet wird, wenn Werte abgerufen werden, sodass Sie in den meisten Fällen Werte erhalten, die "undefiniert" bedeuten.

Um die effektiven Formatierungsparameterwerte einschließlich der geerbten Werte zu erhalten, müssen Sie die Methode [`GetEffective`](../../aspose.slides/portionformat/geteffective) verwenden, die eine Instanz von [`IPortionFormatEffectiveData`](../../aspose.slides/iportionformateffectivedata) zurückgibt.

### Siehe auch

* Klasse [BasePortionFormat](../../aspose.slides/baseportionformat)
* Schnittstelle [IChartPortionFormat](../ichartportionformat)
* Namespace [Aspose.Slides.Charts](../../aspose.slides.charts)
* Assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->