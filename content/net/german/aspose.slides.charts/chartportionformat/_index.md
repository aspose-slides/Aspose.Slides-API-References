---
title: ChartPortionFormat
second_title: Aspose.Sildes für .NET API-Referenz
description: Diese Klasse enthält die Diagramm-Portion-Formatierungseigenschaften, die in Diagrammen verwendet werden. Im Gegensatz zu IPortionFormatEffectiveData../aspose.slides/iportionformateffectivedata sind alle Eigenschaften dieser Klasse schreibbar.
type: docs
weight: 1440
url: /de/aspose.slides.charts/chartportionformat/
---
## ChartPortionFormat Klasse

Diese Klasse enthält die Chart-Portion-Formatierungseigenschaften, die in Diagrammen verwendet werden. Im Gegensatz zu [`IPortionFormatEffectiveData`](../../aspose.slides/iportionformateffectivedata) sind alle Eigenschaften dieser Klasse schreibbar.

```csharp
public sealed class ChartPortionFormat : BasePortionFormat, IChartPortionFormat
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [AlternativeLanguageId](../../aspose.slides/baseportionformat/alternativelanguageid) { get; set; } | Gibt die Id einer alternativen Sprache zurück oder setzt sie. Lese-/Schreib String. |
| [AsIPresentationComponent](../../aspose.slides/pviobject/asipresentationcomponent) { get; } | Ermöglicht das Abrufen der Basis-IPresentationComponent-Schnittstelle. Nur-Lese [`IPresentationComponent`](../../aspose.slides/ipresentationcomponent). |
| [ComplexScriptFont](../../aspose.slides/baseportionformat/complexscriptfont) { get; set; } | Gibt die komplexe Skript-Schriftartinformation zurück oder setzt sie. Null bedeutet, dass die Schriftart nicht definiert ist und vom Master geerbt werden sollte. Lese-/Schreib [`IFontData`](../../aspose.slides/ifontdata). |
| [EastAsianFont](../../aspose.slides/baseportionformat/eastasianfont) { get; set; } | Gibt die ostasiatische Schriftartinformation zurück oder setzt sie. Null bedeutet, dass die Schriftart nicht definiert ist und vom Master geerbt werden sollte. Lese-/Schreib [`IFontData`](../../aspose.slides/ifontdata). |
| [EffectFormat](../../aspose.slides/baseportionformat/effectformat) { get; } | Gibt die Text-EffectFormat-Eigenschaften zurück. Keine Vererbung angewendet. Nur-Lese [`IEffectFormat`](../../aspose.slides/ieffectformat). |
| [Escapement](../../aspose.slides/baseportionformat/escapement) { get; set; } | Gibt den hoch- oder tiefgestellten Text zurück oder setzt ihn. Wertebereich von -100 % (tiefgestellt) bis 100 % (hochgestellt). **float.NaN** bedeutet, dass der Wert undefiniert ist und vom Master geerbt werden sollte. Lese-/Schreib Single. |
| [FillFormat](../../aspose.slides/baseportionformat/fillformat) { get; } | Gibt die Text-FillFormat-Eigenschaften zurück. Keine Vererbung angewendet. Nur-Lese [`IFillFormat`](../../aspose.slides/ifillformat). |
| [FontBold](../../aspose.slides/baseportionformat/fontbold) { get; set; } | Bestimmt, ob die Schriftart fett ist. Keine Vererbung angewendet. Lese-/Schreib [`NullableBool`](../../aspose.slides/nullablebool). |
| [FontHeight](../../aspose.slides/baseportionformat/fontheight) { get; set; } | Gibt die Schriftgradhöhe einer Portion zurück oder setzt sie. **float.NaN** bedeutet, dass die Höhe undefiniert ist und vom Master geerbt werden sollte. Lese-/Schreib Single. |
| [FontItalic](../../aspose.slides/baseportionformat/fontitalic) { get; set; } | Bestimmt, ob die Schriftart kursiv ist. Keine Vererbung angewendet. Lese-/Schreib [`NullableBool`](../../aspose.slides/nullablebool). |
| [FontUnderline](../../aspose.slides/baseportionformat/fontunderline) { get; set; } | Gibt den Textunterstreichungs-Typ zurück oder setzt ihn. Keine Vererbung angewendet. Lese-/Schreib [`TextUnderlineType`](../../aspose.slides/textunderlinetype). |
| [HighlightColor](../../aspose.slides/baseportionformat/highlightcolor) { get; } | Gibt die Farbe zurück, die zum Hervorheben eines Textes verwendet wird. Keine Vererbung angewendet. Nur-Lese [`IColorFormat`](../../aspose.slides/icolorformat). |
| [IsHardUnderlineFill](../../aspose.slides/baseportionformat/ishardunderlinefill) { get; set; } | Bestimmt, ob der Unterstreichungsstil eigene FillFormat-Eigenschaften hat oder sie von den FillFormat-Eigenschaften des Textes erbt. Lese-/Schreib [`NullableBool`](../../aspose.slides/nullablebool). |
| [IsHardUnderlineLine](../../aspose.slides/baseportionformat/ishardunderlineline) { get; set; } | Bestimmt, ob der Unterstreichungsstil eigene LineFormat-Eigenschaften hat oder sie von den LineFormat-Eigenschaften des Textes erbt. Lese-/Schreib [`NullableBool`](../../aspose.slides/nullablebool). |
| [KerningMinimalSize](../../aspose.slides/baseportionformat/kerningminimalsize) { get; set; } | Gibt die minimale Schriftgröße zurück oder setzt sie, bei der Kerning aktiviert werden soll. **float.NaN** bedeutet, dass der Wert undefiniert ist und vom Master geerbt werden sollte. Lese-/Schreib Single. |
| [Kumimoji](../../aspose.slides/baseportionformat/kumimoji) { get; set; } | Bestimmt, ob die Zahlen das sprachspezifische vertikale Textlayout im Osten ignorieren sollen. Keine Vererbung angewendet. Lese-/Schreib [`NullableBool`](../../aspose.slides/nullablebool). |
| [LanguageId](../../aspose.slides/baseportionformat/languageid) { get; set; } | Gibt die Id einer Korrektursprache zurück oder setzt sie. Wird zur Rechtschreib- und Grammatikprüfung verwendet. Lese-/Schreib String. |
| [LatinFont](../../aspose.slides/baseportionformat/latinfont) { get; set; } | Gibt die lateinische Schriftartinformation zurück oder setzt sie. Null bedeutet, dass die Schriftart nicht definiert ist und vom Master geerbt werden sollte. Lese-/Schreib [`IFontData`](../../aspose.slides/ifontdata). |
| [LineFormat](../../aspose.slides/baseportionformat/lineformat) { get; } | Gibt die LineFormat-Eigenschaften für die Textkontur zurück. Keine Vererbung angewendet. Nur-Lese [`ILineFormat`](../../aspose.slides/ilineformat). |
| [NormaliseHeight](../../aspose.slides/baseportionformat/normaliseheight) { get; set; } | Bestimmt, ob die Höhe eines Textes normalisiert werden soll. Keine Vererbung angewendet. Lese-/Schreib [`NullableBool`](../../aspose.slides/nullablebool). |
| [ProofDisabled](../../aspose.slides/baseportionformat/proofdisabled) { get; set; } | Bestimmt, ob der Text nicht korrekturgelesen werden soll. Keine Vererbung angewendet. Lese-/Schreib [`NullableBool`](../../aspose.slides/nullablebool). |
| [Spacing](../../aspose.slides/baseportionformat/spacing) { get; set; } | Gibt die Erhöhung des Zeichenabstands zurück oder setzt sie. **float.NaN** bedeutet, dass der Wert undefiniert ist und vom Master geerbt werden sollte. Lese-/Schreib Single. |
| [SpellCheck](../../aspose.slides/baseportionformat/spellcheck) { get; set; } | Gibt einen Wert zurück oder setzt ihn, der angibt, ob die Rechtschreibprüfung für die Textportion aktiviert ist. Wenn diese Eigenschaft auf false gesetzt ist, werden Rechtschreibprüfungen für Textelemente unterdrückt. Wenn sie auf true gesetzt ist, ist die Rechtschreibprüfung zulässig. Standardwert ist `false`. |
| [StrikethroughType](../../aspose.slides/baseportionformat/strikethroughtype) { get; set; } | Gibt den Durchstreichungs-Typ eines Textes zurück oder setzt ihn. Keine Vererbung angewendet. Lese-/Schreib [`TextStrikethroughType`](../../aspose.slides/textstrikethroughtype). |
| [SymbolFont](../../aspose.slides/baseportionformat/symbolfont) { get; set; } | Gibt die symbolische Schriftartinformation zurück oder setzt sie. Null bedeutet, dass die Schriftart nicht definiert ist und vom Master geerbt werden sollte. Lese-/Schreib [`IFontData`](../../aspose.slides/ifontdata). |
| [TextCapType](../../aspose.slides/baseportionformat/textcaptype) { get; set; } | Gibt die Art der Textkapitalisierung zurück oder setzt sie. Keine Vererbung angewendet. Lese-/Schreib [`TextCapType`](../../aspose.slides/textcaptype). |
| [UnderlineFillFormat](../../aspose.slides/baseportionformat/underlinefillformat) { get; } | Gibt die FillFormat-Eigenschaften der Unterstreichungslinie zurück. Keine Vererbung angewendet. Nur-Lese [`IFillFormat`](../../aspose.slides/ifillformat). |
| [UnderlineLineFormat](../../aspose.slides/baseportionformat/underlinelineformat) { get; } | Gibt die LineFormat-Eigenschaften zurück, die zum Umranden der Unterstreichungslinie verwendet werden. Keine Vererbung angewendet. Nur-Lese [`ILineFormat`](../../aspose.slides/ilineformat). |

## Methoden

| Name | Beschreibung |
| --- | --- |
| override [Equals](../../aspose.slides/pviobject/equals)(object) | Vergleicht mit dem angegebenen Objekt. |
| override [GetHashCode](../../aspose.slides/pviobject/gethashcode)() | Gibt den Hashcode zurück. |

### Anmerkungen

Diese Klasse wird verwendet, um die für den jeweiligen Abschnitt definierten Text-Portions-Formatierungseigenschaften zurückzugeben und zu manipulieren. Das bedeutet, dass bei der Abfrage von Werten keine Vererbung angewendet wird, sodass in den meisten Fällen Werte zurückgeliefert werden, die „undefined“ bedeuten.

Um die effektiven Formatierungsparameterwerte einschließlich geerbter Werte zu erhalten, müssen Sie die Methode [`GetEffective`](../../aspose.slides/portionformat/geteffective) verwenden, die eine [`IPortionFormatEffectiveData`](../../aspose.slides/iportionformateffectivedata)-Instanz zurückgibt.

### Siehe auch

* Klasse [BasePortionFormat](../../aspose.slides/baseportionformat)
* Schnittstelle [IChartPortionFormat](../ichartportionformat)
* Namensraum [Aspose.Slides.Charts](../../aspose.slides.charts)
* Assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->