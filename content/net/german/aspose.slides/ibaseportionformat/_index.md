---
title: IBasePortionFormat
second_title: Aspose.Sildes für .NET API-Referenz
description: Diese Klasse enthält die Formatierungseigenschaften des Textabschnitts. Im Gegensatz zu IPortionFormatEffectiveData./iportionformateffectivedata sind alle Eigenschaften dieser Klasse schreibbar.
type: docs
weight: 5310
url: /de/aspose.slides/ibaseportionformat/
---
## IBasePortionFormat Schnittstelle

Diese Klasse enthält die Formatierungseigenschaften des Textabschnitts. Im Gegensatz zu [`IPortionFormatEffectiveData`](../iportionformateffectivedata) sind alle Eigenschaften dieser Klasse schreibbar.

```csharp
public interface IBasePortionFormat
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [AlternativeLanguageId](../../aspose.slides/ibaseportionformat/alternativelanguageid) { get; set; } | Gibt die Id einer alternativen Sprache zurück oder setzt sie. Lese/Schreiben String. |
| [ComplexScriptFont](../../aspose.slides/ibaseportionformat/complexscriptfont) { get; set; } | Gibt die Informationen zur komplexen Skript-Schriftart zurück oder setzt sie. Null bedeutet, dass die Schriftart nicht definiert ist und vom Master geerbt werden soll. Lese/Schreiben [`IFontData`](../ifontdata). |
| [EastAsianFont](../../aspose.slides/ibaseportionformat/eastasianfont) { get; set; } | Gibt die Informationen zur ostasiatischen Schriftart zurück oder setzt sie. Null bedeutet, dass die Schriftart nicht definiert ist und vom Master geerbt werden soll. Lese/Schreiben [`IFontData`](../ifontdata). |
| [EffectFormat](../../aspose.slides/ibaseportionformat/effectformat) { get; } | Gibt die EffectFormat-Eigenschaften des Textes zurück. Keine Vererbung angewendet. Nur-Lesen [`IEffectFormat`](../ieffectformat). |
| [Escapement](../../aspose.slides/ibaseportionformat/escapement) { get; set; } | Gibt den hoch- oder tiefgestellten Text zurück oder setzt ihn. Wert von -100 % (tiefgestellt) bis 100 % (hochgestellt). **float.NaN** bedeutet, dass der Wert nicht definiert ist und vom Master geerbt werden soll. Lese/Schreiben Single. |
| [FillFormat](../../aspose.slides/ibaseportionformat/fillformat) { get; } | Gibt die FillFormat-Eigenschaften des Textes zurück. Keine Vererbung angewendet. Nur-Lesen [`IFillFormat`](../ifillformat). |
| [FontBold](../../aspose.slides/ibaseportionformat/fontbold) { get; set; } | Bestimmt, ob die Schrift fett ist. Keine Vererbung angewendet. Lese/Schreiben [`NullableBool`](../nullablebool). |
| [FontHeight](../../aspose.slides/ibaseportionformat/fontheight) { get; set; } | Gibt die Schriftgröße eines Abschnitts zurück oder setzt sie. **float.NaN** bedeutet, dass die Höhe nicht definiert ist und vom Master geerbt werden soll. Lese/Schreiben Single. |
| [FontItalic](../../aspose.slides/ibaseportionformat/fontitalic) { get; set; } | Bestimmt, ob die Schrift kursiv ist. Keine Vererbung angewendet. Lese/Schreiben [`NullableBool`](../nullablebool). |
| [FontUnderline](../../aspose.slides/ibaseportionformat/fontunderline) { get; set; } | Gibt den Unterstreichungstyp des Textes zurück oder setzt ihn. Keine Vererbung angewendet. Lese/Schreiben [`TextUnderlineType`](../textunderlinetype). |
| [HighlightColor](../../aspose.slides/ibaseportionformat/highlightcolor) { get; } | Gibt die Farbe zurück, die zum Hervorheben eines Textes verwendet wird. Keine Vererbung angewendet. Nur-Lesen [`IColorFormat`](../icolorformat). |
| [IsHardUnderlineFill](../../aspose.slides/ibaseportionformat/ishardunderlinefill) { get; set; } | Bestimmt, ob der Unterstreichungsstil eigene FillFormat-Eigenschaften hat oder sie von den FillFormat-Eigenschaften des Textes erbt. Lese/Schreiben [`NullableBool`](../nullablebool). |
| [IsHardUnderlineLine](../../aspose.slides/ibaseportionformat/ishardunderlineline) { get; set; } | Bestimmt, ob der Unterstreichungsstil eigene LineFormat-Eigenschaften hat oder sie von den LineFormat-Eigenschaften des Textes erbt. Lese/Schreiben [`NullableBool`](../nullablebool). |
| [KerningMinimalSize](../../aspose.slides/ibaseportionformat/kerningminimalsize) { get; set; } | Gibt die minimale Schriftgröße zurück oder setzt sie, bei der Kerning aktiviert werden soll. **float.NaN** bedeutet, dass der Wert nicht definiert ist und vom Master geerbt werden soll. Lese/Schreiben Single. |
| [Kumimoji](../../aspose.slides/ibaseportionformat/kumimoji) { get; set; } | Bestimmt, ob die Zahlen das vertikale Layout für östliche Sprachen ignorieren sollen. Keine Vererbung angewendet. Lese/Schreiben [`NullableBool`](../nullablebool). |
| [LanguageId](../../aspose.slides/ibaseportionformat/languageid) { get; set; } | Gibt die Id einer Prüfsprachen zurück oder setzt sie. Wird zur Rechtschreib- und Grammatikprüfung verwendet. Lese/Schreiben String. |
| [LatinFont](../../aspose.slides/ibaseportionformat/latinfont) { get; set; } | Gibt die Informationen zur lateinischen Schriftart zurück oder setzt sie. Null bedeutet, dass die Schriftart nicht definiert ist und vom Master geerbt werden soll. Lese/Schreiben [`IFontData`](../ifontdata). |
| [LineFormat](../../aspose.slides/ibaseportionformat/lineformat) { get; } | Gibt die LineFormat-Eigenschaften für die Textumrandung zurück. Keine Vererbung angewendet. Nur-Lesen [`ILineFormat`](../ilineformat). |
| [NormaliseHeight](../../aspose.slides/ibaseportionformat/normaliseheight) { get; set; } | Bestimmt, ob die Höhe des Textes normalisiert werden soll. Keine Vererbung angewendet. Lese/Schreiben [`NullableBool`](../nullablebool). |
| [ProofDisabled](../../aspose.slides/ibaseportionformat/proofdisabled) { get; set; } | Bestimmt, ob der Text nicht geprüft werden soll. Keine Vererbung angewendet. Lese/Schreiben [`NullableBool`](../nullablebool). |
| [Spacing](../../aspose.slides/ibaseportionformat/spacing) { get; set; } | Gibt die Erhöhung des Zeichenabstandes zurück oder setzt sie. **float.NaN** bedeutet, dass der Wert nicht definiert ist und vom Master geerbt werden soll. Lese/Schreiben Single. |
| [SpellCheck](../../aspose.slides/ibaseportionformat/spellcheck) { get; set; } | Gibt einen Wert zurück oder legt fest, ob die Rechtschreibprüfung für den Textabschnitt aktiviert ist. Wenn diese Eigenschaft auf false gesetzt ist, werden Rechtschreibprüfungen für Textelemente unterdrückt. Wenn sie auf true gesetzt ist, ist die Rechtschreibprüfung erlaubt. Standardwert ist `false`. |
| [StrikethroughType](../../aspose.slides/ibaseportionformat/strikethroughtype) { get; set; } | Gibt den Durchstreichungstyp eines Textes zurück oder setzt ihn. Keine Vererbung angewendet. Lese/Schreiben [`TextStrikethroughType`](../textstrikethroughtype). |
| [SymbolFont](../../aspose.slides/ibaseportionformat/symbolfont) { get; set; } | Gibt die Informationen zur symbolischen Schriftart zurück oder setzt sie. Null bedeutet, dass die Schriftart nicht definiert ist und vom Master geerbt werden soll. Lese/Schreiben [`IFontData`](../ifontdata). |
| [TextCapType](../../aspose.slides/ibaseportionformat/textcaptype) { get; set; } | Gibt die Art der Textschreibweise zurück oder setzt sie. Keine Vererbung angewendet. Lese/Schreiben [`TextCapType`](../textcaptype). |
| [UnderlineFillFormat](../../aspose.slides/ibaseportionformat/underlinefillformat) { get; } | Gibt die FillFormat-Eigenschaften der Unterstreichungslinie zurück. Keine Vererbung angewendet. Nur-Lesen [`IFillFormat`](../ifillformat). |
| [UnderlineLineFormat](../../aspose.slides/ibaseportionformat/underlinelineformat) { get; } | Gibt die LineFormat-Eigenschaften zurück, die zum Umranden der Unterstreichungslinie verwendet werden. Keine Vererbung angewendet. Nur-Lesen [`ILineFormat`](../ilineformat). |

### Anmerkungen

Diese Klasse wird verwendet, um die für den jeweiligen Abschnitt definierten Formatierungseigenschaften des Textabschnitts zurückzugeben und zu bearbeiten. Das bedeutet, dass beim Abrufen von Werten keine Vererbung angewendet wird, sodass Sie in den meisten Fällen Werte erhalten, die „undefiniert“ bedeuten.

Um die effektiven Formatierungsparameterwerte einschließlich geerbter Werte zu erhalten, müssen Sie die Methode [`GetEffective`](../iportionformat/geteffective) verwenden, die eine [`IPortionFormatEffectiveData`](../iportionformateffectivedata)-Instanz zurückgibt.

### Siehe auch

* Namensraum [Aspose.Slides](../../aspose.slides)
* Assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->