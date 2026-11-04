---
title: IBasePortionFormat
second_title: Aspose.Sildes für .NET API-Referenz
description: Diese Klasse enthält die Formatierungseigenschaften von Textabschnitten. Im Gegensatz zu IPortionFormatEffectiveData./iportionformateffectivedata sind alle Eigenschaften dieser Klasse beschreibbar.
type: docs
weight: 5330
url: /de/aspose.slides/ibaseportionformat/
---
## IBasePortionFormat Schnittstelle

Diese Klasse enthält die Formatierungseigenschaften von Textabschnitten. Im Gegensatz zu [`IPortionFormatEffectiveData`](../iportionformateffectivedata) sind alle Eigenschaften dieser Klasse beschreibbar.

```csharp
public interface IBasePortionFormat
```

## Eigenschaften

| Name | Description |
| --- | --- |
| [AlternativeLanguageId](../../aspose.slides/ibaseportionformat/alternativelanguageid) { get; set; } | Gibt die Id einer alternativen Sprache zurück oder setzt sie. Lese-/Schreib-String. |
| [ComplexScriptFont](../../aspose.slides/ibaseportionformat/complexscriptfont) { get; set; } | Gibt die Schriftartinformationen für komplexe Skripte zurück oder setzt sie. Null bedeutet, dass die Schriftart undefiniert ist und vom Master geerbt werden sollte. Lese-/Schreib-[`IFontData`](../ifontdata). |
| [EastAsianFont](../../aspose.slides/ibaseportionformat/eastasianfont) { get; set; } | Gibt die East Asian-Schriftartinformationen zurück oder setzt sie. Null bedeutet, dass die Schriftart undefiniert ist und vom Master geerbt werden sollte. Lese-/Schreib-[`IFontData`](../ifontdata). |
| [EffectFormat](../../aspose.slides/ibaseportionformat/effectformat) { get; } | Gibt die EffectFormat-Eigenschaften des Textes zurück. Keine Vererbung angewendet. Nur-Lese-[`IEffectFormat`](../ieffectformat). |
| [Escapement](../../aspose.slides/ibaseportionformat/escapement) { get; set; } | Gibt den hoch- oder tiefgestellten Text zurück oder setzt ihn. Wert von -100 % (tiefgestellt) bis 100 % (hochgestellt). **float.NaN** bedeutet, dass der Wert undefiniert ist und vom Master geerbt werden sollte. Lese-/Schreib-Single. |
| [FillFormat](../../aspose.slides/ibaseportionformat/fillformat) { get; } | Gibt die FillFormat-Eigenschaften des Textes zurück. Keine Vererbung angewendet. Nur-Lese-[`IFillFormat`](../ifillformat). |
| [FontBold](../../aspose.slides/ibaseportionformat/fontbold) { get; set; } | Bestimmt, ob die Schrift fett ist. Keine Vererbung angewendet. Lese-/Schreib-[`NullableBool`](../nullablebool). |
| [FontHeight](../../aspose.slides/ibaseportionformat/fontheight) { get; set; } | Gibt die Schriftgröße eines Abschnitts zurück oder setzt sie. **float.NaN** bedeutet, dass die Höhe undefiniert ist und vom Master geerbt werden sollte. Lese-/Schreib-Single. |
| [FontItalic](../../aspose.slides/ibaseportionformat/fontitalic) { get; set; } | Bestimmt, ob die Schrift kursiv ist. Keine Vererbung angewendet. Lese-/Schreib-[`NullableBool`](../nullablebool). |
| [FontUnderline](../../aspose.slides/ibaseportionformat/fontunderline) { get; set; } | Gibt den Unterstreichungstyp des Textes zurück oder setzt ihn. Keine Vererbung angewendet. Lese-/Schreib-[`TextUnderlineType`](../textunderlinetype). |
| [HighlightColor](../../aspose.slides/ibaseportionformat/highlightcolor) { get; } | Gibt die Farbe zurück, die zum Hervorheben eines Textes verwendet wird. Keine Vererbung angewendet. Nur-Lese-[`IColorFormat`](../icolorformat). |
| [IsHardUnderlineFill](../../aspose.slides/ibaseportionformat/ishardunderlinefill) { get; set; } | Bestimmt, ob der Unterstreichungsstil eigene FillFormat-Eigenschaften hat oder diese von den FillFormat-Eigenschaften des Textes erbt. Lese-/Schreib-[`NullableBool`](../nullablebool). |
| [IsHardUnderlineLine](../../aspose.slides/ibaseportionformat/ishardunderlineline) { get; set; } | Bestimmt, ob der Unterstreichungsstil eigene LineFormat-Eigenschaften hat oder diese von den LineFormat-Eigenschaften des Textes erbt. Lese-/Schreib-[`NullableBool`](../nullablebool). |
| [KerningMinimalSize](../../aspose.slides/ibaseportionformat/kerningminimalsize) { get; set; } | Gibt die minimale Schriftgröße zurück oder setzt sie, für die Kerning aktiviert werden soll. **float.NaN** bedeutet, dass der Wert undefiniert ist und vom Master geerbt werden sollte. Lese-/Schreib-Single. |
| [Kumimoji](../../aspose.slides/ibaseportionformat/kumimoji) { get; set; } | Bestimmt, ob die Zahlen das textorientierte vertikale Layout für östliche Sprachen ignorieren sollen. Keine Vererbung angewendet. Lese-/Schreib-[`NullableBool`](../nullablebool). |
| [LanguageId](../../aspose.slides/ibaseportionformat/languageid) { get; set; } | Gibt die Id einer Korrektursprache zurück oder setzt sie. Wird zur Rechtschreib- und Grammatikprüfung verwendet. Lese-/Schreib-String. |
| [LatinFont](../../aspose.slides/ibaseportionformat/latinfont) { get; set; } | Gibt die Schriftartinformationen für Latein zurück oder setzt sie. Null bedeutet, dass die Schriftart undefiniert ist und vom Master geerbt werden sollte. Lese-/Schreib-[`IFontData`](../ifontdata). |
| [LineFormat](../../aspose.slides/ibaseportionformat/lineformat) { get; } | Gibt die LineFormat-Eigenschaften für die Textumrandung zurück. Keine Vererbung angewendet. Nur-Lese-[`ILineFormat`](../ilineformat). |
| [NormaliseHeight](../../aspose.slides/ibaseportionformat/normaliseheight) { get; set; } | Bestimmt, ob die Höhe eines Textes normalisiert werden soll. Keine Vererbung angewendet. Lese-/Schreib-[`NullableBool`](../nullablebool). |
| [ProofDisabled](../../aspose.slides/ibaseportionformat/proofdisabled) { get; set; } | Bestimmt, ob der Text nicht geprüft werden soll. Keine Vererbung angewendet. Lese-/Schreib-[`NullableBool`](../nullablebool). |
| [Spacing](../../aspose.slides/ibaseportionformat/spacing) { get; set; } | Gibt die Erhöhung des Zeichenabstands zurück oder setzt sie. **float.NaN** bedeutet, dass der Wert undefiniert ist und vom Master geerbt werden sollte. Lese-/Schreib-Single. |
| [SpellCheck](../../aspose.slides/ibaseportionformat/spellcheck) { get; set; } | Gibt an, ob die Rechtschreibprüfung für den Textabschnitt aktiviert ist, bzw. setzt diesen Wert. Wenn diese Eigenschaft auf false gesetzt ist, werden Rechtschreibprüfungen für Textelemente unterdrückt. Wenn sie auf true gesetzt ist, ist die Rechtschreibprüfung erlaubt. Standardwert ist `false`. |
| [StrikethroughType](../../aspose.slides/ibaseportionformat/strikethroughtype) { get; set; } | Gibt den Durchstreichungstyp eines Textes zurück oder setzt ihn. Keine Vererbung angewendet. Lese-/Schreib-[`TextStrikethroughType`](../textstrikethroughtype). |
| [SymbolFont](../../aspose.slides/ibaseportionformat/symbolfont) { get; set; } | Gibt die Symbolschriftartinformationen zurück oder setzt sie. Null bedeutet, dass die Schriftart undefiniert ist und vom Master geerbt werden sollte. Lese-/Schreib-[`IFontData`](../ifontdata). |
| [TextCapType](../../aspose.slides/ibaseportionformat/textcaptype) { get; set; } | Gibt den Typ der Textschreibung zurück oder setzt ihn. Keine Vererbung angewendet. Lese-/Schreib-[`TextCapType`](../textcaptype). |
| [UnderlineFillFormat](../../aspose.slides/ibaseportionformat/underlinefillformat) { get; } | Gibt die FillFormat-Eigenschaften der Unterstreichungslinie zurück. Keine Vererbung angewendet. Nur-Lese-[`IFillFormat`](../ifillformat). |
| [UnderlineLineFormat](../../aspose.slides/ibaseportionformat/underlinelineformat) { get; } | Gibt die LineFormat-Eigenschaften zurück, die zum Umranden der Unterstreichungslinie verwendet werden. Keine Vererbung angewendet. Nur-Lese-[`ILineFormat`](../ilineformat). |

### Hinweise

Diese Klasse wird verwendet, um die für einen bestimmten Abschnitt definierten Formatierungseigenschaften des Textabschnitts zurückzugeben und zu manipulieren. Das bedeutet, dass beim Abrufen von Werten keine Vererbung angewendet wird, sodass Sie in den meisten Fällen Werte erhalten, die „undefiniert“ bedeuten.

Um die effektiven Formatierungsparameterwerte einschließlich vererbter Werte zu erhalten, müssen Sie die [`GetEffective`](../iportionformat/geteffective)-Methode verwenden, die eine [`IPortionFormatEffectiveData`](../iportionformateffectivedata)-Instanz zurückgibt.

### Siehe auch

* Namespace [Aspose.Slides](../../aspose.slides)
* Assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->