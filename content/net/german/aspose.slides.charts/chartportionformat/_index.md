---
title: ChartPortionFormat
second_title: Aspose.Slides für .NET-API-Referenz
description: Diese Klasse enthält die Formatierungseigenschaften des Diagrammteils die in Diagrammen verwendet werden. AndersIPortionFormatEffectiveData../aspose.slides/iportionformateffectivedata  alle Eigenschaften dieser Klasse sind beschreibbar.
type: docs
weight: 1310
url: /de/aspose.slides.charts/chartportionformat/
---
## ChartPortionFormat class

Diese Klasse enthält die Formatierungseigenschaften des Diagrammteils, die in Diagrammen verwendet werden. Anders[`IPortionFormatEffectiveData`](../../aspose.slides/iportionformateffectivedata) , alle Eigenschaften dieser Klasse sind beschreibbar.

```csharp
public class ChartPortionFormat : BasePortionFormat, IChartPortionFormat
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [AlternativeLanguageId](../../aspose.slides/baseportionformat/alternativelanguageid) { get; set; } | Gibt die ID einer alternativen Sprache zurück oder setzt sie. Lesen/SchreibenString . |
| [AsIPresentationComponent](../../aspose.slides/pviobject/asipresentationcomponent) { get; } | Ermöglicht das Abrufen der Basis-IPPresentationComponent-Schnittstelle. Schreibgeschützt[`IPresentationComponent`](../../aspose.slides/ipresentationcomponent) . |
| [ComplexScriptFont](../../aspose.slides/baseportionformat/complexscriptfont) { get; set; } | Gibt die Schriftartinformationen für komplexe Skripte zurück oder legt sie fest. Null bedeutet, dass die Schriftart nicht definiert ist und vom Master geerbt werden sollte. Lesen/Schreiben[`IFontData`](../../aspose.slides/ifontdata) . |
| [EastAsianFont](../../aspose.slides/baseportionformat/eastasianfont) { get; set; } | Gibt die Informationen für ostasiatische Schriftarten zurück oder legt sie fest. Null bedeutet, dass die Schriftart nicht definiert ist und vom Master geerbt werden sollte. Lesen/Schreiben[`IFontData`](../../aspose.slides/ifontdata) . |
| [EffectFormat](../../aspose.slides/baseportionformat/effectformat) { get; } | Gibt die Text-EffectFormat-Eigenschaften zurück. Keine Vererbung angewendet. Schreibgeschützt[`IEffectFormat`](../../aspose.slides/ieffectformat) . |
| [Escapement](../../aspose.slides/baseportionformat/escapement) { get; set; } | Gibt den hochgestellten oder tiefgestellten Text zurück oder legt ihn fest. Wert von -100 % (tiefgestellt) bis 100 % (hochgestellt).  **float.NaN** bedeutet, dass der Wert nicht definiert ist und vom Master geerbt werden sollte. Lesen/SchreibenSingle . |
| [FillFormat](../../aspose.slides/baseportionformat/fillformat) { get; } | Gibt die Text-FillFormat-Eigenschaften zurück. Keine Vererbung angewendet. Schreibgeschützt[`IFillFormat`](../../aspose.slides/ifillformat) . |
| [FontBold](../../aspose.slides/baseportionformat/fontbold) { get; set; } | Bestimmt, ob die Schriftart fett ist. Keine Vererbung angewendet. Lesen/Schreiben[`NullableBool`](../../aspose.slides/nullablebool) . |
| [FontHeight](../../aspose.slides/baseportionformat/fontheight) { get; set; } | Gibt die Schrifthöhe eines Abschnitts zurück oder legt sie fest.  **float.NaN**bedeutet, dass die Höhe nicht definiert ist und vom Master geerbt werden sollte. Lesen/SchreibenSingle . |
| [FontItalic](../../aspose.slides/baseportionformat/fontitalic) { get; set; } | Bestimmt, ob die Schriftart kursiv ist. Keine Vererbung angewendet. Lesen/Schreiben[`NullableBool`](../../aspose.slides/nullablebool) . |
| [FontUnderline](../../aspose.slides/baseportionformat/fontunderline) { get; set; } | Gibt den Textunterstreichungstyp zurück oder legt ihn fest. Keine Vererbung angewendet. Lesen/Schreiben[`TextUnderlineType`](../../aspose.slides/textunderlinetype) . |
| [HighlightColor](../../aspose.slides/baseportionformat/highlightcolor) { get; } | Gibt die Farbe zurück, die zum Hervorheben eines Textes verwendet wird. Keine Vererbung angewendet. Schreibgeschützt[`IColorFormat`](../../aspose.slides/icolorformat) . |
| [IsHardUnderlineFill](../../aspose.slides/baseportionformat/ishardunderlinefill) { get; set; } | Legt fest, ob der Unterstreichungsstil eigene FillFormat-Eigenschaften hat oder von den FillFormat-Eigenschaften des Textes erbt. Lesen/Schreiben[`NullableBool`](../../aspose.slides/nullablebool) . |
| [IsHardUnderlineLine](../../aspose.slides/baseportionformat/ishardunderlineline) { get; set; } | Legt fest, ob der Unterstreichungsstil eigene LineFormat-Eigenschaften hat oder von den LineFormat-Eigenschaften des Textes erbt. Lesen/Schreiben[`NullableBool`](../../aspose.slides/nullablebool) . |
| [KerningMinimalSize](../../aspose.slides/baseportionformat/kerningminimalsize) { get; set; } | Gibt die minimale Schriftgröße zurück oder setzt sie, für die Kerning eingeschaltet werden soll.  **float.NaN** bedeutet, dass der Wert nicht definiert ist und vom Master geerbt werden sollte. Lesen/SchreibenSingle . |
| [Kumimoji](../../aspose.slides/baseportionformat/kumimoji) { get; set; } | Legt fest, ob die Zahlen Text ignorieren sollen, der für die östliche Sprache spezifisch ist, vertikales Textlayout. Keine Vererbung angewendet. Lesen/Schreiben[`NullableBool`](../../aspose.slides/nullablebool) . |
| [LanguageId](../../aspose.slides/baseportionformat/languageid) { get; set; } | Gibt die ID einer Korrektursprache zurück oder legt sie fest. Wird zur Prüfung von Rechtschreibung und Grammatik verwendet. Lesen/SchreibenString . |
| [LatinFont](../../aspose.slides/baseportionformat/latinfont) { get; set; } | Gibt die lateinische Schriftinformation zurück oder setzt sie. Null bedeutet, dass die Schrift nicht definiert ist und vom Master geerbt werden sollte. Lesen/Schreiben[`IFontData`](../../aspose.slides/ifontdata) . |
| [LineFormat](../../aspose.slides/baseportionformat/lineformat) { get; } | Gibt die LineFormat-Eigenschaften für die Textgliederung zurück. Keine Vererbung angewendet. Schreibgeschützt[`ILineFormat`](../../aspose.slides/ilineformat) . |
| [NormaliseHeight](../../aspose.slides/baseportionformat/normaliseheight) { get; set; } | Legt fest, ob die Höhe eines Textes normalisiert werden soll. Keine Vererbung angewendet. Lesen/Schreiben[`NullableBool`](../../aspose.slides/nullablebool) . |
| [ProofDisabled](../../aspose.slides/baseportionformat/proofdisabled) { get; set; } | Legt fest, ob der Text nicht geprooft werden soll. Keine Vererbung angewendet. Lesen/Schreiben[`NullableBool`](../../aspose.slides/nullablebool) . |
| [Spacing](../../aspose.slides/baseportionformat/spacing) { get; set; } | Gibt den Abstand zwischen den Zeichen zurück oder legt ihn fest.  **float.NaN** bedeutet, dass der Wert nicht definiert ist und vom Master geerbt werden sollte. Lesen/SchreibenSingle . |
| [StrikethroughType](../../aspose.slides/baseportionformat/strikethroughtype) { get; set; } | Gibt den Durchstreichungstyp eines Textes zurück oder setzt ihn. Keine Vererbung angewendet. Lesen/Schreiben[`TextStrikethroughType`](../../aspose.slides/textstrikethroughtype) . |
| [SymbolFont](../../aspose.slides/baseportionformat/symbolfont) { get; set; } | Gibt die symbolische Schriftinformation zurück oder setzt sie. Null bedeutet, dass die Schrift nicht definiert ist und vom Master geerbt werden sollte. Lesen/Schreiben[`IFontData`](../../aspose.slides/ifontdata) . |
| [TextCapType](../../aspose.slides/baseportionformat/textcaptype) { get; set; } | Gibt die Art der Textgroßschreibung zurück oder legt sie fest. Keine Vererbung angewendet. Lesen/Schreiben[`TextCapType`](../../aspose.slides/textcaptype) . |
| [UnderlineFillFormat](../../aspose.slides/baseportionformat/underlinefillformat) { get; } | Gibt die FillFormat-Eigenschaften der Unterstreichungslinie zurück. Keine Vererbung angewendet. Schreibgeschützt[`IFillFormat`](../../aspose.slides/ifillformat) . |
| [UnderlineLineFormat](../../aspose.slides/baseportionformat/underlinelineformat) { get; } | Gibt die LineFormat-Eigenschaften zurück, die zum Umreißen der Unterstreichungslinie verwendet werden. Keine Vererbung angewendet. Schreibgeschützt[`ILineFormat`](../../aspose.slides/ilineformat) . |

## Methoden

| Name | Beschreibung |
| --- | --- |
| override [Equals](../../aspose.slides/pviobject/equals)(object) | Vergleicht mit angegebenem Objekt. |
| override [GetHashCode](../../aspose.slides/pviobject/gethashcode)() | Gibt Hash-Code zurück. |

### Bemerkungen

Diese Klasse wird verwendet, um Textabschnitts-formatierungs -Eigenschaften, die für den bestimmten Abschnitt definiert sind, zurückzugeben und zu manipulieren. Dies bedeutet, dass beim Abrufen von Werten keine Vererbung angewendet wird, sodass Sie in den meisten Fällen Werte erhalten, die "undefiniert" bedeuten.

Um die effektiven Formatierungsparameterwerte zu erhalten, einschließlich geerbt, müssen Sie verwenden[`GetEffective`](../../aspose.slides/portionformat/geteffective) method , die a zurückgibt[`IPortionFormatEffectiveData`](../../aspose.slides/iportionformateffectivedata) Beispiel.

### Siehe auch

* class [BasePortionFormat](../../aspose.slides/baseportionformat)
* interface [IChartPortionFormat](../ichartportionformat)
* namensraum [Aspose.Slides.Charts](../../aspose.slides.charts)
* Montage [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
