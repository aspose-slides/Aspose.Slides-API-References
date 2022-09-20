---
title: IBasePortionFormat
second_title: Aspose.Slides für .NET-API-Referenz
description: Diese Klasse enthält die TextteilFormatierungseigenschaften. nicht wieIPortionFormatEffectiveData./iportionformateffectivedata  alle Eigenschaften dieser Klasse sind beschreibbar.
type: docs
weight: 4860
url: /de/net/aspose.slides/ibaseportionformat/
---
## IBasePortionFormat interface

Diese Klasse enthält die Textteil-Formatierungseigenschaften. nicht wie[`IPortionFormatEffectiveData`](../iportionformateffectivedata) , alle Eigenschaften dieser Klasse sind beschreibbar.

```csharp
public interface IBasePortionFormat
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [AlternativeLanguageId](../../aspose.slides/ibaseportionformat/alternativelanguageid) { get; set; } | Gibt die ID einer alternativen Sprache zurück oder setzt sie. Lesen/SchreibenString . |
| [ComplexScriptFont](../../aspose.slides/ibaseportionformat/complexscriptfont) { get; set; } | Gibt die Schriftartinformationen für komplexe Skripte zurück oder legt sie fest. Null bedeutet, dass die Schriftart nicht definiert ist und vom Master geerbt werden sollte. Lesen/Schreiben[`IFontData`](../ifontdata) . |
| [EastAsianFont](../../aspose.slides/ibaseportionformat/eastasianfont) { get; set; } | Gibt die Informationen für ostasiatische Schriftarten zurück oder legt sie fest. Null bedeutet, dass die Schriftart nicht definiert ist und vom Master geerbt werden sollte. Lesen/Schreiben[`IFontData`](../ifontdata) . |
| [EffectFormat](../../aspose.slides/ibaseportionformat/effectformat) { get; } | Gibt die Text-EffectFormat-Eigenschaften zurück. Keine Vererbung angewendet. Schreibgeschützt[`IEffectFormat`](../ieffectformat) . |
| [Escapement](../../aspose.slides/ibaseportionformat/escapement) { get; set; } | Gibt den hochgestellten oder tiefgestellten Text zurück oder legt ihn fest. Wert von -100 % (tiefgestellt) bis 100 % (hochgestellt).  **float.NaN** bedeutet, dass der Wert nicht definiert ist und vom Master geerbt werden sollte. Lesen/SchreibenSingle . |
| [FillFormat](../../aspose.slides/ibaseportionformat/fillformat) { get; } | Gibt die Text-FillFormat-Eigenschaften zurück. Keine Vererbung angewendet. Schreibgeschützt[`IFillFormat`](../ifillformat) . |
| [FontBold](../../aspose.slides/ibaseportionformat/fontbold) { get; set; } | Bestimmt, ob die Schriftart fett ist. Keine Vererbung angewendet. Lesen/Schreiben[`NullableBool`](../nullablebool) . |
| [FontHeight](../../aspose.slides/ibaseportionformat/fontheight) { get; set; } | Gibt die Schrifthöhe eines Abschnitts zurück oder legt sie fest.  **float.NaN**bedeutet, dass die Höhe nicht definiert ist und vom Master geerbt werden sollte. Lesen/SchreibenSingle . |
| [FontItalic](../../aspose.slides/ibaseportionformat/fontitalic) { get; set; } | Bestimmt, ob die Schriftart kursiv ist. Keine Vererbung angewendet. Lesen/Schreiben[`NullableBool`](../nullablebool) . |
| [FontUnderline](../../aspose.slides/ibaseportionformat/fontunderline) { get; set; } | Gibt den Textunterstreichungstyp zurück oder legt ihn fest. Keine Vererbung angewendet. Lesen/Schreiben[`TextUnderlineType`](../textunderlinetype) . |
| [HighlightColor](../../aspose.slides/ibaseportionformat/highlightcolor) { get; } | Gibt die Farbe zurück, die zum Hervorheben eines Textes verwendet wird. Keine Vererbung angewendet. Schreibgeschützt[`IColorFormat`](../icolorformat) . |
| [IsHardUnderlineFill](../../aspose.slides/ibaseportionformat/ishardunderlinefill) { get; set; } | Legt fest, ob der Unterstreichungsstil eigene FillFormat-Eigenschaften hat oder von den FillFormat-Eigenschaften des Textes erbt. Lesen/Schreiben[`NullableBool`](../nullablebool) . |
| [IsHardUnderlineLine](../../aspose.slides/ibaseportionformat/ishardunderlineline) { get; set; } | Legt fest, ob der Unterstreichungsstil eigene LineFormat-Eigenschaften hat oder von den LineFormat-Eigenschaften des Textes erbt. Lesen/Schreiben[`NullableBool`](../nullablebool) . |
| [KerningMinimalSize](../../aspose.slides/ibaseportionformat/kerningminimalsize) { get; set; } | Gibt die minimale Schriftgröße zurück oder setzt sie, für die Kerning eingeschaltet werden soll.  **float.NaN** bedeutet, dass der Wert nicht definiert ist und vom Master geerbt werden sollte. Lesen/SchreibenSingle . |
| [Kumimoji](../../aspose.slides/ibaseportionformat/kumimoji) { get; set; } | Legt fest, ob die Zahlen Text ignorieren sollen, der für die östliche Sprache spezifisch ist, vertikales Textlayout. Keine Vererbung angewendet. Lesen/Schreiben[`NullableBool`](../nullablebool) . |
| [LanguageId](../../aspose.slides/ibaseportionformat/languageid) { get; set; } | Gibt die ID einer Korrektursprache zurück oder legt sie fest. Wird zur Prüfung von Rechtschreibung und Grammatik verwendet. Lesen/SchreibenString . |
| [LatinFont](../../aspose.slides/ibaseportionformat/latinfont) { get; set; } | Gibt die lateinische Schriftinformation zurück oder setzt sie. Null bedeutet, dass die Schrift nicht definiert ist und vom Master geerbt werden sollte. Lesen/Schreiben[`IFontData`](../ifontdata) . |
| [LineFormat](../../aspose.slides/ibaseportionformat/lineformat) { get; } | Gibt die LineFormat-Eigenschaften für die Textgliederung zurück. Keine Vererbung angewendet. Schreibgeschützt[`ILineFormat`](../ilineformat) . |
| [NormaliseHeight](../../aspose.slides/ibaseportionformat/normaliseheight) { get; set; } | Legt fest, ob die Höhe eines Textes normalisiert werden soll. Keine Vererbung angewendet. Lesen/Schreiben[`NullableBool`](../nullablebool) . |
| [ProofDisabled](../../aspose.slides/ibaseportionformat/proofdisabled) { get; set; } | Legt fest, ob der Text nicht geprooft werden soll. Keine Vererbung angewendet. Lesen/Schreiben[`NullableBool`](../nullablebool) . |
| [Spacing](../../aspose.slides/ibaseportionformat/spacing) { get; set; } | Gibt den Abstand zwischen den Zeichen zurück oder legt ihn fest.  **float.NaN** bedeutet, dass der Wert nicht definiert ist und vom Master geerbt werden sollte. Lesen/SchreibenSingle . |
| [StrikethroughType](../../aspose.slides/ibaseportionformat/strikethroughtype) { get; set; } | Gibt den Durchstreichungstyp eines Textes zurück oder setzt ihn. Keine Vererbung angewendet. Lesen/Schreiben[`TextStrikethroughType`](../textstrikethroughtype) . |
| [SymbolFont](../../aspose.slides/ibaseportionformat/symbolfont) { get; set; } | Gibt die symbolische Schriftinformation zurück oder setzt sie. Null bedeutet, dass die Schrift nicht definiert ist und vom Master geerbt werden sollte. Lesen/Schreiben[`IFontData`](../ifontdata) . |
| [TextCapType](../../aspose.slides/ibaseportionformat/textcaptype) { get; set; } | Gibt die Art der Textgroßschreibung zurück oder legt sie fest. Keine Vererbung angewendet. Lesen/Schreiben[`TextCapType`](../textcaptype) . |
| [UnderlineFillFormat](../../aspose.slides/ibaseportionformat/underlinefillformat) { get; } | Gibt die FillFormat-Eigenschaften der Unterstreichungslinie zurück. Keine Vererbung angewendet. Schreibgeschützt[`IFillFormat`](../ifillformat) . |
| [UnderlineLineFormat](../../aspose.slides/ibaseportionformat/underlinelineformat) { get; } | Gibt die LineFormat-Eigenschaften zurück, die zum Umreißen der Unterstreichungslinie verwendet werden. Keine Vererbung angewendet. Schreibgeschützt[`ILineFormat`](../ilineformat) . |

### Bemerkungen

Diese Klasse wird verwendet, um Formatierungseigenschaften von Textabschnitten, die für den bestimmten Abschnitt definiert sind, zurückzugeben und zu manipulieren. Dies bedeutet, dass beim Abrufen von Werten keine Vererbung angewendet wird, sodass Sie in den meisten Fällen Werte erhalten, die "undefiniert" bedeuten.

Um die effektiven Formatierungsparameterwerte einschließlich geerbter Werte zu erhalten, müssen Sie verwenden[`GetEffective`](../iportionformat/geteffective) Methode , die a zurückgibt[`IPortionFormatEffectiveData`](../iportionformateffectivedata) Beispiel.

### Siehe auch

* namensraum [Aspose.Slides](../../aspose.slides)
* Montage [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
