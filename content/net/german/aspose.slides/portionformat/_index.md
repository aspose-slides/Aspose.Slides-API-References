---
title: PortionFormat
second_title: Aspose.Sildes für .NET API Referenz
description: Diese Klasse enthält die Eigenschaften der Formatierung von Textportionen. Im Gegensatz zu IPortionFormatEffectiveData../iportionformateffectivedata sind alle Eigenschaften dieser Klasse beschreibbar.
type: docs
weight: 9220
url: /de/aspose.slides/portionformat/
---

## PortionFormat-Klasse

Diese Klasse enthält die Eigenschaften der Formatierung von Textportionen. Im Gegensatz zu [`IPortionFormatEffectiveData`](../iportionformateffectivedata) sind alle Eigenschaften dieser Klasse beschreibbar.

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
| [AlternativeLanguageId](../../aspose.slides/baseportionformat/alternativelanguageid) { get; set; } | Gibt die ID einer alternativen Sprache zurück oder setzt sie. Lese-/Schreib-String. |
| [AsIPresentationComponent](../../aspose.slides/pviobject/asipresentationcomponent) { get; } | Ermöglicht den Zugriff auf die basale IPresentationComponent-Schnittstelle. Nur lesbar [`IPresentationComponent`](../ipresentationcomponent). |
| [BookmarkId](../../aspose.slides/portionformat/bookmarkid) { get; set; } | Gibt die ID eines Lesezeichens zurück oder setzt sie. Lese-/Schreib-String. |
| [ComplexScriptFont](../../aspose.slides/baseportionformat/complexscriptfont) { get; set; } | Gibt die Informationen zur Schriftart für komplexe Skripte zurück oder setzt sie. Null bedeutet, dass die Schriftart undefiniert ist und vom Master geerbt werden sollte. Lese-/Schreib- [`IFontData`](../ifontdata). |
| [EastAsianFont](../../aspose.slides/baseportionformat/eastasianfont) { get; set; } | Gibt die Informationen zur Ostasiatischen Schriftart zurück oder setzt sie. Null bedeutet, dass die Schriftart undefiniert ist und vom Master geerbt werden sollte. Lese-/Schreib- [`IFontData`](../ifontdata). |
| [EffectFormat](../../aspose.slides/baseportionformat/effectformat) { get; } | Gibt die Eigenschaften der Text-Effektformatierung zurück. Keine Vererbung angewendet. Nur lesbar [`IEffectFormat`](../ieffectformat). |
| [Escapement](../../aspose.slides/baseportionformat/escapement) { get; set; } | Gibt den Über- oder Untertext zurück oder setzt ihn. Werte von -100% (Untertext) bis 100% (Übertext). **float.NaN** bedeutet, dass der Wert undefiniert ist und vom Master geerbt werden sollte. Lese-/Schreib- Einzelwert. |
| [FillFormat](../../aspose.slides/baseportionformat/fillformat) { get; } | Gibt die Eigenschaften der Text-Füllformatierung zurück. Keine Vererbung angewendet. Nur lesbar [`IFillFormat`](../ifillformat). |
| [FontBold](../../aspose.slides/baseportionformat/fontbold) { get; set; } | Bestimmt, ob die Schriftart fett ist. Keine Vererbung angewendet. Lese-/Schreib- [`NullableBool`](../nullablebool). |
| [FontHeight](../../aspose.slides/baseportionformat/fontheight) { get; set; } | Gibt die Schriftart-Höhe einer Portion zurück oder setzt sie. **float.NaN** bedeutet, dass die Höhe undefiniert ist und vom Master geerbt werden sollte. Lese-/Schreib- Einzelwert. |
| [FontItalic](../../aspose.slides/baseportionformat/fontitalic) { get; set; } | Bestimmt, ob die Schriftart kursiv ist. Keine Vererbung angewendet. Lese-/Schreib- [`NullableBool`](../nullablebool). |
| [FontUnderline](../../aspose.slides/baseportionformat/fontunderline) { get; set; } | Gibt den Typ der Textunterstreichung zurück oder setzt ihn. Keine Vererbung angewendet. Lese-/Schreib- [`TextUnderlineType`](../textunderlinetype). |
| [HighlightColor](../../aspose.slides/baseportionformat/highlightcolor) { get; } | Gibt die Farbe zurück, die zum Hervorheben von Text verwendet wird. Keine Vererbung angewendet. Nur lesbar [`IColorFormat`](../icolorformat). |
| [HyperlinkClick](../../aspose.slides/portionformat/hyperlinkclick) { get; set; } | Gibt den für den Mausklick definierten Hyperlink zurück oder setzt ihn. Lese-/Schreib- [`IHyperlink`](../ihyperlink). |
| [HyperlinkManager](../../aspose.slides/portionformat/hyperlinkmanager) { get; } | Hyperlink-Manager. Nur lesbar [`IHyperlinkManager`](../ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/portionformat/hyperlinkmouseover) { get; set; } | Gibt den für den Mouseover definierten Hyperlink zurück oder setzt ihn. Lese-/Schreib- [`IHyperlink`](../ihyperlink). |
| [IsHardUnderlineFill](../../aspose.slides/baseportionformat/ishardunderlinefill) { get; set; } | Bestimmt, ob der Unterstreichungsstil eigene Füllformatierungs-Eigenschaften hat oder sie von den Füllformatierungs-Eigenschaften des Textes erbt. Lese-/Schreib- [`NullableBool`](../nullablebool). |
| [IsHardUnderlineLine](../../aspose.slides/baseportionformat/ishardunderlineline) { get; set; } | Bestimmt, ob der Unterstreichungsstil eigene Linienformatierungs-Eigenschaften hat oder sie von den Linienformatierungs-Eigenschaften des Textes erbt. Lese-/Schreib- [`NullableBool`](../nullablebool). |
| [KerningMinimalSize](../../aspose.slides/baseportionformat/kerningminimalsize) { get; set; } | Gibt die minimale Schriftgröße zurück oder setzt sie, für die das kerning aktiviert werden soll. **float.NaN** bedeutet, dass der Wert undefiniert ist und vom Master geerbt werden sollte. Lese-/Schreib- Einzelwert. |
| [Kumimoji](../../aspose.slides/baseportionformat/kumimoji) { get; set; } | Bestimmt, ob die Zahlen das vertikale Layout von Text in östlichen Sprachen ignorieren sollten. Keine Vererbung angewendet. Lese-/Schreib- [`NullableBool`](../nullablebool). |
| [LanguageId](../../aspose.slides/baseportionformat/languageid) { get; set; } | Gibt die ID einer Korrekturlesesprache zurück oder setzt sie. Wird zum Überprüfen von Rechtschreibung und Grammatik verwendet. Lese-/Schreib-String. |
| [LatinFont](../../aspose.slides/baseportionformat/latinfont) { get; set; } | Gibt die Informationen zur lateinischen Schriftart zurück oder setzt sie. Null bedeutet, dass die Schriftart undefiniert ist und vom Master geerbt werden sollte. Lese-/Schreib- [`IFontData`](../ifontdata). |
| [LineFormat](../../aspose.slides/baseportionformat/lineformat) { get; } | Gibt die Eigenschaften der Linienformatierung für die Textrahmung zurück. Keine Vererbung angewendet. Nur lesbar [`ILineFormat`](../ilineformat). |
| [NormaliseHeight](../../aspose.slides/baseportionformat/normaliseheight) { get; set; } | Bestimmt, ob die Höhe eines Texts normalisiert werden sollte. Keine Vererbung angewendet. Lese-/Schreib- [`NullableBool`](../nullablebool). |
| [ProofDisabled](../../aspose.slides/baseportionformat/proofdisabled) { get; set; } | Bestimmt, ob der Text nicht korrigiert werden sollte. Keine Vererbung angewendet. Lese-/Schreib- [`NullableBool`](../nullablebool). |
| [SmartTagClean](../../aspose.slides/portionformat/smarttagclean) { get; set; } | Bestimmt, ob das Smart-Tag bereinigt werden sollte. Keine Vererbung angewendet. Lese-/Schreib-Boolesch. |
| [Spacing](../../aspose.slides/baseportionformat/spacing) { get; set; } | Gibt den Abstand zwischen den Zeichen zurück oder setzt ihn. **float.NaN** bedeutet, dass der Wert undefiniert ist und vom Master geerbt werden sollte. Lese-/Schreib- Einzelwert. |
| [StrikethroughType](../../aspose.slides/baseportionformat/strikethroughtype) { get; set; } | Gibt den Durchstreichungs-Typ eines Texts zurück oder setzt ihn. Keine Vererbung angewendet. Lese-/Schreib- [`TextStrikethroughType`](../textstrikethroughtype). |
| [SymbolFont](../../aspose.slides/baseportionformat/symbolfont) { get; set; } | Gibt die Informationen zur symbolischen Schriftart zurück oder setzt sie. Null bedeutet, dass die Schriftart undefiniert ist und vom Master geerbt werden sollte. Lese-/Schreib- [`IFontData`](../ifontdata). |
| [TextCapType](../../aspose.slides/baseportionformat/textcaptype) { get; set; } | Gibt den Typ der Text-Kapitalisierung zurück oder setzt ihn. Keine Vererbung angewendet. Lese-/Schreib- [`TextCapType`](../textcaptype). |
| [UnderlineFillFormat](../../aspose.slides/baseportionformat/underlinefillformat) { get; } | Gibt die Eigenschaften der Füllformatierung der Unterstreichungslinie zurück. Keine Vererbung angewendet. Nur lesbar [`IFillFormat`](../ifillformat). |
| [UnderlineLineFormat](../../aspose.slides/baseportionformat/underlinelineformat) { get; } | Gibt die Eigenschaften der Linienformatierung zurück, die verwendet werden, um die Unterstreichungslinie zu umreißen. Keine Vererbung angewendet. Nur lesbar [`ILineFormat`](../ilineformat). |

## Methoden

| Name | Beschreibung |
| --- | --- |
| override [Equals](../../aspose.slides/pviobject/equals)(object) | Vergleicht mit dem angegebenen Objekt. |
| [GetEffective](../../aspose.slides/portionformat/geteffective)() | Holt die effektiven Formatierungsdaten der Portion mit angewendeter Vererbung. |
| override [GetHashCode](../../aspose.slides/pviobject/gethashcode)() | Gibt den Hash-Code zurück. |

### Anmerkungen

Diese Klasse wird verwendet, um die Formatiereigenschaften von Textportionen zurückzugeben und zu manipulieren, die für die jeweilige Portion definiert sind. Das bedeutet, dass keine Vererbung angewendet wird, wenn Werte abgerufen werden, sodass in den meisten Fällen Werte zurückgegeben werden, die "undefiniert" bedeuten.

Um die effektiven Formatierungsparameterwerte einschließlich vererbter zu erhalten, müssen Sie die Methode [`GetEffective`](./geteffective) verwenden, die eine Instanz von [`IPortionFormatEffectiveData`](../iportionformateffectivedata) zurückgibt.

### Beispiele

Die folgenden Beispiele zeigen, wie man die lateinische Schriftart einem Abschnitt eines Absatzes in einer PowerPoint-Präsentation zuweist.

```csharp
[C#]
//Instanziieren Sie ein Präsentationsobjekt, das eine Präsentationsdatei darstellt
using (Presentation pres = new Presentation("demo.pptx"))
{
IAutoShape shape = pres.Slides[0].Shapes.AddAutoShape(ShapeType.Rectangle, 10, 10, 100, 100);
Paragraph paragraph = new Paragraph();
Portion portion = new Portion("Theme text format");
paragraph.Portions.Add(portion);
shape.TextFrame.Paragraphs.Add(paragraph);
// Aspose.Slides verwendet diese speziellen Identifikatoren (ähnlich wie die in PowerPoint verwendeten):
// +mn-lt - Body Font Latin (Minor Latin Font)
// +mj-lt -Heading Font Latin (Major Latin Font)
// +mn-ea - Body Font East Asian (Minor East Asian Font)
// +mj-ea - Body Font East Asian (Minor East Asian Font)
portion.PortionFormat.LatinFont = new FontData("+mn-lt");
}
```

### Siehe auch

* Klasse [BasePortionFormat](../baseportionformat)
* Schnittstelle [IPortionFormat](../iportionformat)
* Namensraum [Aspose.Slides](../../aspose.slides)
* Assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generiert von xmldocmd für Aspose.Slides.dll -->