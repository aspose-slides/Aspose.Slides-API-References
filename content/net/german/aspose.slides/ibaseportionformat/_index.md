---
title: IBasePortionFormat
second_title: Aspose.Slides für .NET API-Referenz
description: Diese Klasse enthält die Eigenschaften zur Formatierung des Textanteils. Im Gegensatz zu IPortionFormatEffectiveData../iportionformateffectivedata sind alle Eigenschaften dieser Klasse schreibbar.
type: docs
weight: 5110
url: /de/aspose.slides/ibaseportionformat/
---

## IBasePortionFormat-Interface

Diese Klasse enthält die Eigenschaften zur Formatierung des Textanteils. Im Gegensatz zu [`IPortionFormatEffectiveData`](../iportionformateffectivedata) sind alle Eigenschaften dieser Klasse schreibbar.

```csharp
public interface IBasePortionFormat
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [AlternativeLanguageId](../../aspose.slides/ibaseportionformat/alternativelanguageid) { get; set; } | Gibt die ID einer alternativen Sprache zurück oder setzt sie. Lese-/Schreib-String. |
| [ComplexScriptFont](../../aspose.slides/ibaseportionformat/complexscriptfont) { get; set; } | Gibt die Informationen zur komplexen Skript-Schrift zurück oder setzt sie. Null bedeutet, dass die Schrift undefiniert ist und vom Master geerbt werden sollte. Lese-/Schreib- [`IFontData`](../ifontdata). |
| [EastAsianFont](../../aspose.slides/ibaseportionformat/eastasianfont) { get; set; } | Gibt die Informationen zur Schriftart für Ostasiatische Schriftzeichen zurück oder setzt sie. Null bedeutet, dass die Schrift undefiniert ist und vom Master geerbt werden sollte. Lese-/Schreib- [`IFontData`](../ifontdata). |
| [EffectFormat](../../aspose.slides/ibaseportionformat/effectformat) { get; } | Gibt die Eigenschaften des Text-EffectFormat zurück. Keine Vererbung angewendet. Nur Lese- [`IEffectFormat`](../ieffectformat). |
| [Escapement](../../aspose.slides/ibaseportionformat/escapement) { get; set; } | Gibt den Text im Hoch- oder Tiefformat zurück oder setzt ihn. Wert von -100% (Tief) bis 100% (Hoch). **float.NaN** bedeutet, dass der Wert undefiniert ist und vom Master geerbt werden sollte. Lese-/Schreib- Single. |
| [FillFormat](../../aspose.slides/ibaseportionformat/fillformat) { get; } | Gibt die Eigenschaften des Text-FillFormat zurück. Keine Vererbung angewendet. Nur Lese- [`IFillFormat`](../ifillformat). |
| [FontBold](../../aspose.slides/ibaseportionformat/fontbold) { get; set; } | Bestimmt, ob die Schrift fett ist. Keine Vererbung angewendet. Lese-/Schreib- [`NullableBool`](../nullablebool). |
| [FontHeight](../../aspose.slides/ibaseportionformat/fontheight) { get; set; } | Gibt die Schriftgröße eines Anteils zurück oder setzt sie. **float.NaN** bedeutet, dass die Höhe undefiniert ist und vom Master geerbt werden sollte. Lese-/Schreib- Single. |
| [FontItalic](../../aspose.slides/ibaseportionformat/fontitalic) { get; set; } | Bestimmt, ob die Schrift kursiv ist. Keine Vererbung angewendet. Lese-/Schreib- [`NullableBool`](../nullablebool). |
| [FontUnderline](../../aspose.slides/ibaseportionformat/fontunderline) { get; set; } | Gibt den Unterstreichungstyp des Textes zurück oder setzt ihn. Keine Vererbung angewendet. Lese-/Schreib- [`TextUnderlineType`](../textunderlinetype). |
| [HighlightColor](../../aspose.slides/ibaseportionformat/highlightcolor) { get; } | Gibt die Farbe zurück, die zur Hervorhebung eines Textes verwendet wird. Keine Vererbung angewendet. Nur Lese- [`IColorFormat`](../icolorformat). |
| [IsHardUnderlineFill](../../aspose.slides/ibaseportionformat/ishardunderlinefill) { get; set; } | Bestimmt, ob der Unterstreichungsstil eigene FillFormat-Eigenschaften hat oder diese von den FillFormat-Eigenschaften des Textes erbt. Lese-/Schreib- [`NullableBool`](../nullablebool). |
| [IsHardUnderlineLine](../../aspose.slides/ibaseportionformat/ishardunderlineline) { get; set; } | Bestimmt, ob der Unterstreichungsstil eigene LineFormat-Eigenschaften hat oder diese von den LineFormat-Eigenschaften des Textes erbt. Lese-/Schreib- [`NullableBool`](../nullablebool). |
| [KerningMinimalSize](../../aspose.slides/ibaseportionformat/kerningminimalsize) { get; set; } | Gibt die minimale Schriftgröße zurück oder setzt sie, für die das Kerning aktiviert werden sollte. **float.NaN** bedeutet, dass der Wert undefiniert ist und vom Master geerbt werden sollte. Lese-/Schreib- Single. |
| [Kumimoji](../../aspose.slides/ibaseportionformat/kumimoji) { get; set; } | Bestimmt, ob die Zahlen das östlichsprachenspezifische vertikale Textlayout ignorieren sollen. Keine Vererbung angewendet. Lese-/Schreib- [`NullableBool`](../nullablebool). |
| [LanguageId](../../aspose.slides/ibaseportionformat/languageid) { get; set; } | Gibt die ID einer Prüfungs-Sprache zurück oder setzt sie. Wird zur Überprüfung von Rechtschreibung und Grammatik verwendet. Lese-/Schreib-String. |
| [LatinFont](../../aspose.slides/ibaseportionformat/latinfont) { get; set; } | Gibt die Informationen zur lateinischen Schriftart zurück oder setzt sie. Null bedeutet, dass die Schrift undefiniert ist und vom Master geerbt werden sollte. Lese-/Schreib- [`IFontData`](../ifontdata). |
| [LineFormat](../../aspose.slides/ibaseportionformat/lineformat) { get; } | Gibt die LineFormat-Eigenschaften für die Textumrandung zurück. Keine Vererbung angewendet. Nur Lese- [`ILineFormat`](../ilineformat). |
| [NormaliseHeight](../../aspose.slides/ibaseportionformat/normaliseheight) { get; set; } | Bestimmt, ob die Höhe eines Textes normalisiert werden soll. Keine Vererbung angewendet. Lese-/Schreib- [`NullableBool`](../nullablebool). |
| [ProofDisabled](../../aspose.slides/ibaseportionformat/proofdisabled) { get; set; } | Bestimmt, ob der Text nicht geprüft werden sollte. Keine Vererbung angewendet. Lese-/Schreib- [`NullableBool`](../nullablebool). |
| [Spacing](../../aspose.slides/ibaseportionformat/spacing) { get; set; } | Gibt den Abstand zwischen den Zeichen zurück oder setzt ihn. **float.NaN** bedeutet, dass der Wert undefiniert ist und vom Master geerbt werden sollte. Lese-/Schreib- Single. |
| [StrikethroughType](../../aspose.slides/ibaseportionformat/strikethroughtype) { get; set; } | Gibt den Durchstreichungstyp eines Textes zurück oder setzt ihn. Keine Vererbung angewendet. Lese-/Schreib- [`TextStrikethroughType`](../textstrikethroughtype). |
| [SymbolFont](../../aspose.slides/ibaseportionformat/symbolfont) { get; set; } | Gibt die Informationen zur symbolischen Schriftart zurück oder setzt sie. Null bedeutet, dass die Schrift undefiniert ist und vom Master geerbt werden sollte. Lese-/Schreib- [`IFontData`](../ifontdata). |
| [TextCapType](../../aspose.slides/ibaseportionformat/textcaptype) { get; set; } | Gibt den Typ der Textkapitalisierung zurück oder setzt ihn. Keine Vererbung angewendet. Lese-/Schreib- [`TextCapType`](../textcaptype). |
| [UnderlineFillFormat](../../aspose.slides/ibaseportionformat/underlinefillformat) { get; } | Gibt die FillFormat-Eigenschaften der Unterstreichungslinie zurück. Keine Vererbung angewendet. Nur Lese- [`IFillFormat`](../ifillformat). |
| [UnderlineLineFormat](../../aspose.slides/ibaseportionformat/underlinelineformat) { get; } | Gibt die LineFormat-Eigenschaften zurück, die zur Umrandung der Unterstreichungslinie verwendet werden. Keine Vererbung angewendet. Nur Lese- [`ILineFormat`](../ilineformat). |

### Anmerkungen

Diese Klasse wird verwendet, um die Eigenschaften der Textanteilsformatierung zurückzugeben und zu manipulieren, die für den bestimmten Anteil definiert sind. Das bedeutet, dass bei der Abfrage der Werte keine Vererbung angewendet wird, sodass Sie in den meisten Fällen Werte erhalten, die "undefiniert" bedeuten.

Um die effektiven Formatierungsparameterwerte, einschließlich der vererbten, zu erhalten, müssen Sie die Methode [`GetEffective`](../iportionformat/geteffective) verwenden, die eine Instanz von [`IPortionFormatEffectiveData`](../iportionformateffectivedata) zurückgibt.

### Siehe Auch

* Namespace [Aspose.Slides](../../aspose.slides)
* Assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->