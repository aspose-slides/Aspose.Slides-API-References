---
title: ChartPortionFormat
second_title: Aspose.Slides für .NET API-Referenz
description: Diese Klasse enthält die Formatierungseigenschaften für Chartanteile, die in Diagrammen verwendet werden. Im Gegensatz zu IPortionFormatEffectiveData../aspose.slides/iportionformateffectivedata sind alle Eigenschaften dieser Klasse beschreibbar.
type: docs
weight: 1350
url: /de/aspose.slides.charts/chartportionformat/
---

## ChartPortionFormat-Klasse

Diese Klasse enthält die Formatierungseigenschaften für Chartanteile, die in Diagrammen verwendet werden. Im Gegensatz zu [`IPortionFormatEffectiveData`](../../aspose.slides/iportionformateffectivedata) sind alle Eigenschaften dieser Klasse beschreibbar.

```csharp
public sealed class ChartPortionFormat : BasePortionFormat, IChartPortionFormat
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [AlternativeLanguageId](../../aspose.slides/baseportionformat/alternativelanguageid) { get; set; } | Gibt die ID einer alternativen Sprache zurück oder setzt sie. Lese-/Schreibzugriff String. |
| [AsIPresentationComponent](../../aspose.slides/pviobject/asipresentationcomponent) { get; } | Ermöglicht den Zugriff auf die grundlegende IPresentationComponent-Schnittstelle. Nur-Lese [`IPresentationComponent`](../../aspose.slides/ipresentationcomponent). |
| [ComplexScriptFont](../../aspose.slides/baseportionformat/complexscriptfont) { get; set; } | Gibt die Informationen zur Schriftart für komplexe Skripte zurück oder setzt diese. Null bedeutet, dass die Schriftart nicht definiert ist und vom Master geerbt werden sollte. Lese-/Schreibzugriff [`IFontData`](../../aspose.slides/ifontdata). |
| [EastAsianFont](../../aspose.slides/baseportionformat/eastasianfont) { get; set; } | Gibt die Informationen zur Schriftart für ostasiatische Schriftzeichen zurück oder setzt diese. Null bedeutet, dass die Schriftart nicht definiert ist und vom Master geerbt werden sollte. Lese-/Schreibzugriff [`IFontData`](../../aspose.slides/ifontdata). |
| [EffectFormat](../../aspose.slides/baseportionformat/effectformat) { get; } | Gibt die Eigenschaften des Effekts für Text zurück. Keine Vererbung angewendet. Nur-Lese [`IEffectFormat`](../../aspose.slides/ieffectformat). |
| [Escapement](../../aspose.slides/baseportionformat/escapement) { get; set; } | Gibt den Wert für hochgestellten oder tiefgestellten Text zurück oder setzt ihn. Wert von -100 % (tiefgestellt) bis 100 % (hochgestellt). **float.NaN** bedeutet, dass der Wert nicht definiert ist und vom Master geerbt werden sollte. Lese-/Schreibzugriff Single. |
| [FillFormat](../../aspose.slides/baseportionformat/fillformat) { get; } | Gibt die Eigenschaften des Füllformats für den Text zurück. Keine Vererbung angewendet. Nur-Lese [`IFillFormat`](../../aspose.slides/ifillformat). |
| [FontBold](../../aspose.slides/baseportionformat/fontbold) { get; set; } | Bestimmt, ob die Schriftart fett ist. Keine Vererbung angewendet. Lese-/Schreibzugriff [`NullableBool`](../../aspose.slides/nullablebool). |
| [FontHeight](../../aspose.slides/baseportionformat/fontheight) { get; set; } | Gibt die Schriftartgröße eines Anteils zurück oder setzt sie. **float.NaN** bedeutet, dass die Höhe nicht definiert ist und vom Master geerbt werden sollte. Lese-/Schreibzugriff Single. |
| [FontItalic](../../aspose.slides/baseportionformat/fontitalic) { get; set; } | Bestimmt, ob die Schriftart kursiv ist. Keine Vererbung angewendet. Lese-/Schreibzugriff [`NullableBool`](../../aspose.slides/nullablebool). |
| [FontUnderline](../../aspose.slides/baseportionformat/fontunderline) { get; set; } | Gibt den Typ der Unterstreichung für den Text zurück oder setzt ihn. Keine Vererbung angewendet. Lese-/Schreibzugriff [`TextUnderlineType`](../../aspose.slides/textunderlinetype). |
| [HighlightColor](../../aspose.slides/baseportionformat/highlightcolor) { get; } | Gibt die zum Hervorheben eines Textes verwendete Farbe zurück. Keine Vererbung angewendet. Nur-Lese [`IColorFormat`](../../aspose.slides/icolorformat). |
| [IsHardUnderlineFill](../../aspose.slides/baseportionformat/ishardunderlinefill) { get; set; } | Bestimmt, ob der Stil der Unterstreichung eigene Eigenschaften für das Füllformat hat oder diese von den Füllformateigenschaften des Textes erbt. Lese-/Schreibzugriff [`NullableBool`](../../aspose.slides/nullablebool). |
| [IsHardUnderlineLine](../../aspose.slides/baseportionformat/ishardunderlineline) { get; set; } | Bestimmt, ob der Stil der Unterstreichung eigene Eigenschaften für das Linienformat hat oder diese von den Linienformateigenschaften des Textes erbt. Lese-/Schreibzugriff [`NullableBool`](../../aspose.slides/nullablebool). |
| [KerningMinimalSize](../../aspose.slides/baseportionformat/kerningminimalsize) { get; set; } | Gibt die minimale Schriftgröße zurück oder setzt sie, für die das Kerning aktiviert werden sollte. **float.NaN** bedeutet, dass der Wert nicht definiert ist und vom Master geerbt werden sollte. Lese-/Schreibzugriff Single. |
| [Kumimoji](../../aspose.slides/baseportionformat/kumimoji) { get; set; } | Bestimmt, ob die Zahlen das östliche sprachenspezifische vertikale Layout des Textes ignorieren sollten. Keine Vererbung angewendet. Lese-/Schreibzugriff [`NullableBool`](../../aspose.slides/nullablebool). |
| [LanguageId](../../aspose.slides/baseportionformat/languageid) { get; set; } | Gibt die ID einer Korrekturlesen-Sprache zurück oder setzt sie. Wird zum Überprüfen von Rechtschreibung und Grammatik verwendet. Lese-/Schreibzugriff String. |
| [LatinFont](../../aspose.slides/baseportionformat/latinfont) { get; set; } | Gibt die Informationen zur lateinischen Schriftart zurück oder setzt sie. Null bedeutet, dass die Schriftart nicht definiert ist und vom Master geerbt werden sollte. Lese-/Schreibzugriff [`IFontData`](../../aspose.slides/ifontdata). |
| [LineFormat](../../aspose.slides/baseportionformat/lineformat) { get; } | Gibt die LineFormat-Eigenschaften für die Textkonturierung zurück. Keine Vererbung angewendet. Nur-Lese [`ILineFormat`](../../aspose.slides/ilineformat). |
| [NormaliseHeight](../../aspose.slides/baseportionformat/normaliseheight) { get; set; } | Bestimmt, ob die Höhe eines Textes normalisiert werden sollte. Keine Vererbung angewendet. Lese-/Schreibzugriff [`NullableBool`](../../aspose.slides/nullablebool). |
| [ProofDisabled](../../aspose.slides/baseportionformat/proofdisabled) { get; set; } | Bestimmt, ob der Text nicht korrekturgelesen werden soll. Keine Vererbung angewendet. Lese-/Schreibzugriff [`NullableBool`](../../aspose.slides/nullablebool). |
| [Spacing](../../aspose.slides/baseportionformat/spacing) { get; set; } | Gibt den Abstand zwischen den Zeichen zurück oder setzt ihn. **float.NaN** bedeutet, dass der Wert nicht definiert ist und vom Master geerbt werden sollte. Lese-/Schreibzugriff Single. |
| [StrikethroughType](../../aspose.slides/baseportionformat/strikethroughtype) { get; set; } | Gibt den Strichtyp eines Textes zurück oder setzt ihn. Keine Vererbung angewendet. Lese-/Schreibzugriff [`TextStrikethroughType`](../../aspose.slides/textstrikethroughtype). |
| [SymbolFont](../../aspose.slides/baseportionformat/symbolfont) { get; set; } | Gibt die Informationen zur symbolischen Schriftart zurück oder setzt sie. Null bedeutet, dass die Schriftart nicht definiert ist und vom Master geerbt werden sollte. Lese-/Schreibzugriff [`IFontData`](../../aspose.slides/ifontdata). |
| [TextCapType](../../aspose.slides/baseportionformat/textcaptype) { get; set; } | Gibt den Typ der Textcapitalisierung zurück oder setzt ihn. Keine Vererbung angewendet. Lese-/Schreibzugriff [`TextCapType`](../../aspose.slides/textcaptype). |
| [UnderlineFillFormat](../../aspose.slides/baseportionformat/underlinefillformat) { get; } | Gibt die Füllformat-Eigenschaften der unterstrichenen Linie zurück. Keine Vererbung angewendet. Nur-Lese [`IFillFormat`](../../aspose.slides/ifillformat). |
| [UnderlineLineFormat](../../aspose.slides/baseportionformat/underlinelineformat) { get; } | Gibt die LineFormat-Eigenschaften zurück, die zur Konturierung der unterstrichenen Linie verwendet werden. Keine Vererbung angewendet. Nur-Lese [`ILineFormat`](../../aspose.slides/ilineformat). |

## Methoden

| Name | Beschreibung |
| --- | --- |
| override [Equals](../../aspose.slides/pviobject/equals)(object) | Vergleicht mit dem angegebenen Objekt. |
| override [GetHashCode](../../aspose.slides/pviobject/gethashcode)() | Gibt den Hashcode zurück. |

### Anmerkungen

Diese Klasse wird verwendet, um die Formatierungseigenschaften von Textanteilen zurückzugeben und zu manipulieren, die für den bestimmten Anteil definiert sind. Dies bedeutet, dass keine Vererbung angewendet wird, wenn Werte abgerufen werden, sodass Sie in den meisten Fällen Werte erhalten, die "nicht definiert" bedeuten.

Um die effektiven Formatierungsparameterwerte, einschließlich der geerbten, zu erhalten, müssen Sie die Methode [`GetEffective`](../../aspose.slides/portionformat/geteffective) verwenden, die eine Instanz von [`IPortionFormatEffectiveData`](../../aspose.slides/iportionformateffectivedata) zurückgibt.

### Siehe auch

* Klasse [BasePortionFormat](../../aspose.slides/baseportionformat)
* Schnittstelle [IChartPortionFormat](../ichartportionformat)
* Namespace [Aspose.Slides.Charts](../../aspose.slides.charts)
* Assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->