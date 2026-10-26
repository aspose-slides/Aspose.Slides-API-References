---
title: PortionFormat
second_title: Aspose.Sildes für .NET API-Referenz
description: Diese Klasse enthält die Textabschnitt-Formatierungseigenschaften. Im Gegensatz zu IPortionFormatEffectiveData./iportionformateffectivedata sind alle Eigenschaften dieser Klasse schreibbar.
type: docs
weight: 9490
url: /de/aspose.slides/portionformat/
---
## PortionFormat Klasse

Diese Klasse enthält die Formatierungseigenschaften von Textabschnitten. Im Gegensatz zu [`IPortionFormatEffectiveData`](../iportionformateffectivedata) sind alle Eigenschaften dieser Klasse schreibbar.

```csharp
public sealed class PortionFormat : BasePortionFormat, IPortionFormat
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [PortionFormat](portionformat)() | Initialisiert eine neue Instanz der [`PortionFormat`](../portionformat) Klasse. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [AlternativeLanguageId](../../aspose.slides/baseportionformat/alternativelanguageid) { get; set; } | Gibt die Id einer alternativen Sprache zurück oder legt sie fest. Lesen/Schreiben String. |
| [AsIPresentationComponent](../../aspose.slides/pviobject/asipresentationcomponent) { get; } | Ermöglicht das Abrufen der Basis-IPresentationComponent-Schnittstelle. Nur Lesen [`IPresentationComponent`](../ipresentationcomponent). |
| [BookmarkId](../../aspose.slides/portionformat/bookmarkid) { get; set; } | Gibt die Lesezeichen-ID zurück oder legt sie fest. Lesen/Schreiben String. |
| [ComplexScriptFont](../../aspose.slides/baseportionformat/complexscriptfont) { get; set; } | Gibt die Schriftartinformationen für komplexe Skripte zurück oder legt sie fest. Null bedeutet, dass die Schriftart undefiniert ist und vom Master geerbt werden soll. Lesen/Schreiben [`IFontData`](../ifontdata). |
| [EastAsianFont](../../aspose.slides/baseportionformat/eastasianfont) { get; set; } | Gibt die ostasiatischen Schriftartinformationen zurück oder legt sie fest. Null bedeutet, dass die Schriftart undefiniert ist und vom Master geerbt werden soll. Lesen/Schreiben [`IFontData`](../ifontdata). |
| [EffectFormat](../../aspose.slides/baseportionformat/effectformat) { get; } | Gibt die EffectFormat-Eigenschaften des Textes zurück. Keine Vererbung angewendet. Nur Lesen [`IEffectFormat`](../ieffectformat). |
| [Escapement](../../aspose.slides/baseportionformat/escapement) { get; set; } | Gibt den hoch- oder tiefgestellten Text zurück oder legt ihn fest. Wert von -100 % (Tiefstellung) bis 100 % (Hochstellung). **float.NaN** bedeutet, dass der Wert undefiniert ist und vom Master geerbt werden soll. Lesen/Schreiben Single. |
| [FillFormat](../../aspose.slides/baseportionformat/fillformat) { get; } | Gibt die FillFormat-Eigenschaften des Textes zurück. Keine Vererbung angewendet. Nur Lesen [`IFillFormat`](../ifillformat). |
| [FontBold](../../aspose.slides/baseportionformat/fontbold) { get; set; } | Bestimmt, ob die Schriftart fett (bold) ist. Keine Vererbung angewendet. Lesen/Schreiben [`NullableBool`](../nullablebool). |
| [FontHeight](../../aspose.slides/baseportionformat/fontheight) { get; set; } | Gibt die Schriftgröße eines Abschnitts zurück oder legt sie fest. **float.NaN** bedeutet, dass die Höhe undefiniert ist und vom Master geerbt werden soll. Lesen/Schreiben Single. |
| [FontItalic](../../aspose.slides/baseportionformat/fontitalic) { get; set; } | Bestimmt, ob die Schrift kursiv ist. Keine Vererbung angewendet. Lesen/Schreiben [`NullableBool`](../nullablebool). |
| [FontUnderline](../../aspose.slides/baseportionformat/fontunderline) { get; set; } | Gibt den Unterstreichungs-Typ des Textes zurück oder legt ihn fest. Keine Vererbung angewendet. Lesen/Schreiben [`TextUnderlineType`](../textunderlinetype). |
| [HighlightColor](../../aspose.slides/baseportionformat/highlightcolor) { get; } | Gibt die Farbe zurück, die zum Hervorheben von Text verwendet wird. Keine Vererbung angewendet. Nur Lesen [`IColorFormat`](../icolorformat). |
| [HyperlinkClick](../../aspose.slides/portionformat/hyperlinkclick) { get; set; } | Gibt den für Mausklick definierten Hyperlink zurück oder legt ihn fest. Lesen/Schreiben [`IHyperlink`](../ihyperlink). |
| [HyperlinkManager](../../aspose.slides/portionformat/hyperlinkmanager) { get; } | Hyperlink-Verwalter. Nur Lesen [`IHyperlinkManager`](../ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/portionformat/hyperlinkmouseover) { get; set; } | Gibt den für Maus-Überfahren definierten Hyperlink zurück oder legt ihn fest. Lesen/Schreiben [`IHyperlink`](../ihyperlink). |
| [IsHardUnderlineFill](../../aspose.slides/baseportionformat/ishardunderlinefill) { get; set; } | Bestimmt, ob der Unterstreichungsstil eigene FillFormat-Eigenschaften hat oder diese von den FillFormat-Eigenschaften des Textes erbt. Lesen/Schreiben [`NullableBool`](../nullablebool). |
| [IsHardUnderlineLine](../../aspose.slides/baseportionformat/ishardunderlineline) { get; set; } | Bestimmt, ob der Unterstreichungsstil eigene LineFormat-Eigenschaften hat oder diese von den LineFormat-Eigenschaften des Textes erbt. Lesen/Schreiben [`NullableBool`](../nullablebool). |
| [KerningMinimalSize](../../aspose.slides/baseportionformat/kerningminimalsize) { get; set; } | Gibt die minimale Schriftgröße zurück, ab der Kerning aktiviert werden soll, oder legt sie fest. **float.NaN** bedeutet, dass der Wert undefiniert ist und vom Master geerbt werden soll. Lesen/Schreiben Single. |
| [Kumimoji](../../aspose.slides/baseportionformat/kumimoji) { get; set; } | Bestimmt, ob Zahlen das für ostasiatische Sprachen spezifische vertikale Textlayout ignorieren sollen. Keine Vererbung angewendet. Lesen/Schreiben [`NullableBool`](../nullablebool). |
| [LanguageId](../../aspose.slides/baseportionformat/languageid) { get; set; } | Gibt die Id einer Korrektursprache zurück oder legt sie fest. Wird zur Rechtschreib- und Grammatikprüfung verwendet. Lesen/Schreiben String. |
| [LatinFont](../../aspose.slides/baseportionformat/latinfont) { get; set; } | Gibt die lateinischen Schriftartinformationen zurück oder legt sie fest. Null bedeutet, dass die Schriftart undefiniert ist und vom Master geerbt werden soll. Lesen/Schreiben [`IFontData`](../ifontdata). |
| [LineFormat](../../aspose.slides/baseportionformat/lineformat) { get; } | Gibt die LineFormat-Eigenschaften für die Textumrandung zurück. Keine Vererbung angewendet. Nur Lesen [`ILineFormat`](../ilineformat). |
| [NormaliseHeight](../../aspose.slides/baseportionformat/normaliseheight) { get; set; } | Bestimmt, ob die Höhe eines Textes normalisiert werden soll. Keine Vererbung angewendet. Lesen/Schreiben [`NullableBool`](../nullablebool). |
| [ProofDisabled](../../aspose.slides/baseportionformat/proofdisabled) { get; set; } | Bestimmt, ob der Text nicht geprüft werden soll. Keine Vererbung angewendet. Lesen/Schreiben [`NullableBool`](../nullablebool). |
| [SmartTagClean](../../aspose.slides/portionformat/smarttagclean) { get; set; } | Bestimmt, ob das Smart-Tag bereinigt werden soll. Keine Vererbung angewendet. Lesen/Schreiben Boolean. |
| [Spacing](../../aspose.slides/baseportionformat/spacing) { get; set; } | Gibt den Abstandszuwachs zwischen Zeichen zurück oder legt ihn fest. **float.NaN** bedeutet, dass der Wert undefiniert ist und vom Master geerbt werden soll. Lesen/Schreiben Single. |
| [SpellCheck](../../aspose.slides/baseportionformat/spellcheck) { get; set; } | Gibt an, ob die Rechtschreibprüfung für den Textabschnitt aktiviert ist, oder legt diesen Wert fest. Wenn diese Eigenschaft auf false gesetzt ist, werden Rechtschreibprüfungen für Textelemente unterdrückt. Wenn sie auf true gesetzt ist, ist die Rechtschreibprüfung erlaubt. Standardwert ist `false`. |
| [StrikethroughType](../../aspose.slides/baseportionformat/strikethroughtype) { get; set; } | Gibt den Durchstreichungs-Typ eines Textes zurück oder legt ihn fest. Keine Vererbung angewendet. Lesen/Schreiben [`TextStrikethroughType`](../textstrikethroughtype). |
| [SymbolFont](../../aspose.slides/baseportionformat/symbolfont) { get; set; } | Gibt die symbolischen Schriftartinformationen zurück oder legt sie fest. Null bedeutet, dass die Schriftart undefiniert ist und vom Master geerbt werden soll. Lesen/Schreiben [`IFontData`](../ifontdata). |
| [TextCapType](../../aspose.slides/baseportionformat/textcaptype) { get; set; } | Gibt den Typ der Groß-/Kleinschreibung des Textes zurück oder legt ihn fest. Keine Vererbung angewendet. Lesen/Schreiben [`TextCapType`](../textcaptype). |
| [UnderlineFillFormat](../../aspose.slides/baseportionformat/underlinefillformat) { get; } | Gibt die FillFormat-Eigenschaften der Unterstreichungslinie zurück. Keine Vererbung angewendet. Nur Lesen [`IFillFormat`](../ifillformat). |
| [UnderlineLineFormat](../../aspose.slides/baseportionformat/underlinelineformat) { get; } | Gibt die LineFormat-Eigenschaften zurück, die zum Umranden der Unterstreichungslinie verwendet werden. Keine Vererbung angewendet. Nur Lesen [`ILineFormat`](../ilineformat). |

## Methoden

| Name | Beschreibung |
| --- | --- |
| override [Equals](../../aspose.slides/pviobject/equals)(object) | Vergleicht mit dem angegebenen Objekt. |
| [GetEffective](../../aspose.slides/portionformat/geteffective)() | Ermittelt die wirksamen Abschnittsformatierungsdaten mit angewandter Vererbung. |
| override [GetHashCode](../../aspose.slides/pviobject/gethashcode)() | Gibt den Hashcode zurück. |

### Hinweise

Diese Klasse wird verwendet, um die für einen bestimmten Abschnitt definierten Textabschnitt-Formatierungseigenschaften zurückzugeben und zu manipulieren. Das bedeutet, dass beim Abrufen von Werten keine Vererbung angewendet wird, sodass Sie in den meisten Fällen Werte erhalten, die „undefiniert“ bedeuten.

Um die wirksamen Formatierungsparameterwerte einschließlich vererbter Werte zu erhalten, müssen Sie die Methode [`GetEffective`](./geteffective) verwenden, die eine [`IPortionFormatEffectiveData`](../iportionformateffectivedata)-Instanz zurückgibt.

### Beispiele

Das folgende Beispiel zeigt, wie die lateinische Schriftart einem Abschnitt eines Paragraphen in einer PowerPoint-Präsentation zugewiesen wird.

```csharp
[C#]
//Instanziert ein Präsentationsobjekt, das eine Präsentationsdatei repräsentiert
using (Presentation pres = new Presentation("demo.pptx"))
{
IAutoShape shape = pres.Slides[0].Shapes.AddAutoShape(ShapeType.Rectangle, 10, 10, 100, 100);
Paragraph paragraph = new Paragraph();
Portion portion = new Portion("Theme text format");
paragraph.Portions.Add(portion);
shape.TextFrame.Paragraphs.Add(paragraph);
// Aspose.Slides verwendet diese speziellen Bezeichner (ähnlich denen, die in PowerPoint verwendet werden):
// +mn-lt - Body-Schriftart Latin (Minor Latin Schriftart)
// +mj-lt - Heading-Schriftart Latin (Major Latin Schriftart)
// +mn-ea - Body-Schriftart East Asian (Minor East Asian Schriftart)
// +mj-ea - Body-Schriftart East Asian (Minor East Asian Schriftart)
portion.PortionFormat.LatinFont = new FontData("+mn-lt");
}
```

### Siehe auch

* Klasse [BasePortionFormat](../baseportionformat)
* Schnittstelle [IPortionFormat](../iportionformat)
* Namensraum [Aspose.Slides](../../aspose.slides)
* Assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->