---
title: PortionFormat
second_title: Aspose.Slides für .NET-API-Referenz
description: Diese Klasse enthält die TextteilFormatierungseigenschaften. nicht wieIPortionFormatEffectiveData./iportionformateffectivedata  alle Eigenschaften dieser Klasse sind beschreibbar.
type: docs
weight: 8790
url: /de/aspose.slides/portionformat/
---
## PortionFormat class

Diese Klasse enthält die Textteil-Formatierungseigenschaften. nicht wie[`IPortionFormatEffectiveData`](../iportionformateffectivedata) , alle Eigenschaften dieser Klasse sind beschreibbar.

```csharp
public class PortionFormat : BasePortionFormat, IPortionFormat
```

## Konstrukteure

| Name | Beschreibung |
| --- | --- |
| [PortionFormat](portionformat)() | Initialisiert eine neue Instanz von[`PortionFormat`](../portionformat) Klasse. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [AlternativeLanguageId](../../aspose.slides/baseportionformat/alternativelanguageid) { get; set; } | Gibt die ID einer alternativen Sprache zurück oder setzt sie. Lesen/SchreibenString . |
| [AsIPresentationComponent](../../aspose.slides/pviobject/asipresentationcomponent) { get; } | Ermöglicht das Abrufen der Basis-IPPresentationComponent-Schnittstelle. Schreibgeschützt[`IPresentationComponent`](../ipresentationcomponent) . |
| [BookmarkId](../../aspose.slides/portionformat/bookmarkid) { get; set; } | Gibt die Lesezeichenkennung zurück oder setzt sie. Lesen/SchreibenString . |
| [ComplexScriptFont](../../aspose.slides/baseportionformat/complexscriptfont) { get; set; } | Gibt die Schriftartinformationen für komplexe Skripte zurück oder legt sie fest. Null bedeutet, dass die Schriftart nicht definiert ist und vom Master geerbt werden sollte. Lesen/Schreiben[`IFontData`](../ifontdata) . |
| [EastAsianFont](../../aspose.slides/baseportionformat/eastasianfont) { get; set; } | Gibt die Informationen für ostasiatische Schriftarten zurück oder legt sie fest. Null bedeutet, dass die Schriftart nicht definiert ist und vom Master geerbt werden sollte. Lesen/Schreiben[`IFontData`](../ifontdata) . |
| [EffectFormat](../../aspose.slides/baseportionformat/effectformat) { get; } | Gibt die Text-EffectFormat-Eigenschaften zurück. Keine Vererbung angewendet. Schreibgeschützt[`IEffectFormat`](../ieffectformat) . |
| [Escapement](../../aspose.slides/baseportionformat/escapement) { get; set; } | Gibt den hochgestellten oder tiefgestellten Text zurück oder legt ihn fest. Wert von -100 % (tiefgestellt) bis 100 % (hochgestellt).  **float.NaN** bedeutet, dass der Wert nicht definiert ist und vom Master geerbt werden sollte. Lesen/SchreibenSingle . |
| [FillFormat](../../aspose.slides/baseportionformat/fillformat) { get; } | Gibt die Text-FillFormat-Eigenschaften zurück. Keine Vererbung angewendet. Schreibgeschützt[`IFillFormat`](../ifillformat) . |
| [FontBold](../../aspose.slides/baseportionformat/fontbold) { get; set; } | Bestimmt, ob die Schriftart fett ist. Keine Vererbung angewendet. Lesen/Schreiben[`NullableBool`](../nullablebool) . |
| [FontHeight](../../aspose.slides/baseportionformat/fontheight) { get; set; } | Gibt die Schrifthöhe eines Abschnitts zurück oder legt sie fest.  **float.NaN**bedeutet, dass die Höhe nicht definiert ist und vom Master geerbt werden sollte. Lesen/SchreibenSingle . |
| [FontItalic](../../aspose.slides/baseportionformat/fontitalic) { get; set; } | Bestimmt, ob die Schriftart kursiv ist. Keine Vererbung angewendet. Lesen/Schreiben[`NullableBool`](../nullablebool) . |
| [FontUnderline](../../aspose.slides/baseportionformat/fontunderline) { get; set; } | Gibt den Textunterstreichungstyp zurück oder legt ihn fest. Keine Vererbung angewendet. Lesen/Schreiben[`TextUnderlineType`](../textunderlinetype) . |
| [HighlightColor](../../aspose.slides/baseportionformat/highlightcolor) { get; } | Gibt die Farbe zurück, die zum Hervorheben eines Textes verwendet wird. Keine Vererbung angewendet. Schreibgeschützt[`IColorFormat`](../icolorformat) . |
| [HyperlinkClick](../../aspose.slides/portionformat/hyperlinkclick) { get; set; } | Gibt den für Mausklick definierten Hyperlink zurück oder setzt ihn. Lesen/Schreiben[`IHyperlink`](../ihyperlink) . |
| [HyperlinkManager](../../aspose.slides/portionformat/hyperlinkmanager) { get; } | Hyperlink-Manager. Schreibgeschützt[`IHyperlinkManager`](../ihyperlinkmanager) . |
| [HyperlinkMouseOver](../../aspose.slides/portionformat/hyperlinkmouseover) { get; set; } | Gibt den für Mouseover definierten Hyperlink zurück oder setzt ihn. Lesen/Schreiben[`IHyperlink`](../ihyperlink) . |
| [IsHardUnderlineFill](../../aspose.slides/baseportionformat/ishardunderlinefill) { get; set; } | Legt fest, ob der Unterstreichungsstil eigene FillFormat-Eigenschaften hat oder von den FillFormat-Eigenschaften des Textes erbt. Lesen/Schreiben[`NullableBool`](../nullablebool) . |
| [IsHardUnderlineLine](../../aspose.slides/baseportionformat/ishardunderlineline) { get; set; } | Legt fest, ob der Unterstreichungsstil eigene LineFormat-Eigenschaften hat oder von den LineFormat-Eigenschaften des Textes erbt. Lesen/Schreiben[`NullableBool`](../nullablebool) . |
| [KerningMinimalSize](../../aspose.slides/baseportionformat/kerningminimalsize) { get; set; } | Gibt die minimale Schriftgröße zurück oder setzt sie, für die Kerning eingeschaltet werden soll.  **float.NaN** bedeutet, dass der Wert nicht definiert ist und vom Master geerbt werden sollte. Lesen/SchreibenSingle . |
| [Kumimoji](../../aspose.slides/baseportionformat/kumimoji) { get; set; } | Legt fest, ob die Zahlen Text ignorieren sollen, der für die östliche Sprache spezifisch ist, vertikales Textlayout. Keine Vererbung angewendet. Lesen/Schreiben[`NullableBool`](../nullablebool) . |
| [LanguageId](../../aspose.slides/baseportionformat/languageid) { get; set; } | Gibt die ID einer Korrektursprache zurück oder legt sie fest. Wird zur Prüfung von Rechtschreibung und Grammatik verwendet. Lesen/SchreibenString . |
| [LatinFont](../../aspose.slides/baseportionformat/latinfont) { get; set; } | Gibt die lateinische Schriftinformation zurück oder setzt sie. Null bedeutet, dass die Schrift nicht definiert ist und vom Master geerbt werden sollte. Lesen/Schreiben[`IFontData`](../ifontdata) . |
| [LineFormat](../../aspose.slides/baseportionformat/lineformat) { get; } | Gibt die LineFormat-Eigenschaften für die Textgliederung zurück. Keine Vererbung angewendet. Schreibgeschützt[`ILineFormat`](../ilineformat) . |
| [NormaliseHeight](../../aspose.slides/baseportionformat/normaliseheight) { get; set; } | Legt fest, ob die Höhe eines Textes normalisiert werden soll. Keine Vererbung angewendet. Lesen/Schreiben[`NullableBool`](../nullablebool) . |
| [ProofDisabled](../../aspose.slides/baseportionformat/proofdisabled) { get; set; } | Legt fest, ob der Text nicht geprooft werden soll. Keine Vererbung angewendet. Lesen/Schreiben[`NullableBool`](../nullablebool) . |
| [SmartTagClean](../../aspose.slides/portionformat/smarttagclean) { get; set; } | Legt fest, ob das Smarttag bereinigt werden soll. Keine Vererbung angewendet. Lesen/SchreibenBoolean . |
| [Spacing](../../aspose.slides/baseportionformat/spacing) { get; set; } | Gibt den Abstand zwischen den Zeichen zurück oder legt ihn fest.  **float.NaN** bedeutet, dass der Wert nicht definiert ist und vom Master geerbt werden sollte. Lesen/SchreibenSingle . |
| [StrikethroughType](../../aspose.slides/baseportionformat/strikethroughtype) { get; set; } | Gibt den Durchstreichungstyp eines Textes zurück oder setzt ihn. Keine Vererbung angewendet. Lesen/Schreiben[`TextStrikethroughType`](../textstrikethroughtype) . |
| [SymbolFont](../../aspose.slides/baseportionformat/symbolfont) { get; set; } | Gibt die symbolische Schriftinformation zurück oder setzt sie. Null bedeutet, dass die Schrift nicht definiert ist und vom Master geerbt werden sollte. Lesen/Schreiben[`IFontData`](../ifontdata) . |
| [TextCapType](../../aspose.slides/baseportionformat/textcaptype) { get; set; } | Gibt die Art der Textgroßschreibung zurück oder legt sie fest. Keine Vererbung angewendet. Lesen/Schreiben[`TextCapType`](../textcaptype) . |
| [UnderlineFillFormat](../../aspose.slides/baseportionformat/underlinefillformat) { get; } | Gibt die FillFormat-Eigenschaften der Unterstreichungslinie zurück. Keine Vererbung angewendet. Schreibgeschützt[`IFillFormat`](../ifillformat) . |
| [UnderlineLineFormat](../../aspose.slides/baseportionformat/underlinelineformat) { get; } | Gibt die LineFormat-Eigenschaften zurück, die zum Umreißen der Unterstreichungslinie verwendet werden. Keine Vererbung angewendet. Schreibgeschützt[`ILineFormat`](../ilineformat) . |

## Methoden

| Name | Beschreibung |
| --- | --- |
| override [Equals](../../aspose.slides/pviobject/equals)(object) | Vergleicht mit angegebenem Objekt. |
| [GetEffective](../../aspose.slides/portionformat/geteffective)() | Ruft effektive Teilformatierungsdaten mit angewendeter Vererbung ab. |
| override [GetHashCode](../../aspose.slides/pviobject/gethashcode)() | Gibt Hash-Code zurück. |

### Bemerkungen

Diese Klasse wird verwendet, um Formatierungseigenschaften von Textabschnitten, die für den bestimmten Abschnitt definiert sind, zurückzugeben und zu manipulieren. Dies bedeutet, dass beim Abrufen von Werten keine Vererbung angewendet wird, sodass Sie in den meisten Fällen Werte erhalten, die "undefiniert" bedeuten.

Um die effektiven Formatierungsparameterwerte einschließlich geerbter Werte zu erhalten, müssen Sie verwenden[`GetEffective`](./geteffective) Methode , die a zurückgibt[`IPortionFormatEffectiveData`](../iportionformateffectivedata) Beispiel.

### Siehe auch

* class [BasePortionFormat](../baseportionformat)
* interface [IPortionFormat](../iportionformat)
* namensraum [Aspose.Slides](../../aspose.slides)
* Montage [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
