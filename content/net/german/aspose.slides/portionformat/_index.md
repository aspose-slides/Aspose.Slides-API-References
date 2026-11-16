---
title: PortionFormat
second_title: Aspose.Sildes für .NET API-Referenz
description: Diese Klasse enthält die Formatierungseigenschaften von Textabschnitten. Im Gegensatz zu IPortionFormatEffectiveData./iportionformateffectivedata sind alle Eigenschaften dieser Klasse schreibbar.
type: docs
weight: 9510
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
| [PortionFormat](portionformat)() | Initialisiert eine neue Instanz der Klasse [`PortionFormat`](../portionformat). |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [AlternativeLanguageId](../../aspose.slides/baseportionformat/alternativelanguageid) { get; set; } | Gibt die Id einer alternativen Sprache zurück oder legt sie fest. Lesen/Schreiben String. |
| [AsIPresentationComponent](../../aspose.slides/pviobject/asipresentationcomponent) { get; } | Ermöglicht das Abrufen der Basis-IPresentationComponent-Schnittstelle. Nur lesbar [`IPresentationComponent`](../ipresentationcomponent). |
| [BookmarkId](../../aspose.slides/portionformat/bookmarkid) { get; set; } | Gibt die Lesezeichen-Kennung zurück oder legt sie fest. Lesen/Schreiben String. |
| [ComplexScriptFont](../../aspose.slides/baseportionformat/complexscriptfont) { get; set; } | Gibt die Schriftinformationen für komplexe Skripte zurück oder legt sie fest. null bedeutet, dass die Schriftart undefiniert ist und vom Master geerbt werden sollte. Lesen/Schreiben [`IFontData`](../ifontdata). |
| [EastAsianFont](../../aspose.slides/baseportionformat/eastasianfont) { get; set; } | Gibt die ostasiatischen Schriftinformationen zurück oder legt sie fest. null bedeutet, dass die Schriftart undefiniert ist und vom Master geerbt werden sollte. Lesen/Schreiben [`IFontData`](../ifontdata). |
| [EffectFormat](../../aspose.slides/baseportionformat/effectformat) { get; } | Gibt die EffectFormat-Eigenschaften des Textes zurück. Keine Vererbung angewendet. Nur lesbar [`IEffectFormat`](../ieffectformat). |
| [Escapement](../../aspose.slides/baseportionformat/escapement) { get; set; } | Gibt den hoch- oder tiefgestellten Text zurück oder legt ihn fest. Wert von -100 % (Tiefstellung) bis 100 % (Hochstellung). **float.NaN** bedeutet, dass der Wert undefiniert ist und vom Master geerbt werden sollte. Lesen/Schreiben Single. |
| [FillFormat](../../aspose.slides/baseportionformat/fillformat) { get; } | Gibt die FillFormat-Eigenschaften des Textes zurück. Keine Vererbung angewendet. Nur lesbar [`IFillFormat`](../ifillformat). |
| [FontBold](../../aspose.slides/baseportionformat/fontbold) { get; set; } | Bestimmt, ob die Schriftart fett ist. Keine Vererbung angewendet. Lesen/Schreiben [`NullableBool`](../nullablebool). |
| [FontHeight](../../aspose.slides/baseportionformat/fontheight) { get; set; } | Gibt die Schriftgröße eines Abschnitts zurück oder legt sie fest. **float.NaN** bedeutet, dass die Höhe undefiniert ist und vom Master geerbt werden sollte. Lesen/Schreiben Single. |
| [FontItalic](../../aspose.slides/baseportionformat/fontitalic) { get; set; } | Bestimmt, ob die Schriftart kursiv ist. Keine Vererbung angewendet. Lesen/Schreiben [`NullableBool`](../nullablebool). |
| [FontUnderline](../../aspose.slides/baseportionformat/fontunderline) { get; set; } | Gibt den Unterstreichungs-Typ des Textes zurück oder legt ihn fest. Keine Vererbung angewendet. Lesen/Schreiben [`TextUnderlineType`](../textunderlinetype). |
| [HighlightColor](../../aspose.slides/baseportionformat/highlightcolor) { get; } | Gibt die zum Hervorheben von Text verwendete Farbe zurück. Keine Vererbung angewendet. Nur lesbar [`IColorFormat`](../icolorformat). |
| [HyperlinkClick](../../aspose.slides/portionformat/hyperlinkclick) { get; set; } | Gibt den für einen Maus-Klick definierten Hyperlink zurück oder legt ihn fest. Lesen/Schreiben [`IHyperlink`](../ihyperlink). |
| [HyperlinkManager](../../aspose.slides/portionformat/hyperlinkmanager) { get; } | Hyperlink-Manager. Nur lesbar [`IHyperlinkManager`](../ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/portionformat/hyperlinkmouseover) { get; set; } | Gibt den für Maus-Überfahren definierten Hyperlink zurück oder legt ihn fest. Lesen/Schreiben [`IHyperlink`](../ihyperlink). |
| [IsHardUnderlineFill](../../aspose.slides/baseportionformat/ishardunderlinefill) { get; set; } | Bestimmt, ob der Unterstreichungsstil eigene FillFormat-Eigenschaften hat oder sie von den FillFormat-Eigenschaften des Textes erbt. Lesen/Schreiben [`NullableBool`](../nullablebool). |
| [IsHardUnderlineLine](../../aspose.slides/baseportionformat/ishardunderlineline) { get; set; } | Bestimmt, ob der Unterstreichungsstil eigene LineFormat-Eigenschaften hat oder sie von den LineFormat-Eigenschaften des Textes erbt. Lesen/Schreiben [`NullableBool`](../nullablebool). |
| [KerningMinimalSize](../../aspose.slides/baseportionformat/kerningminimalsize) { get; set; } | Gibt die minimale Schriftgröße zurück oder legt sie fest, für die Kerning aktiviert werden soll. **float.NaN** bedeutet, dass der Wert undefiniert ist und vom Master geerbt werden sollte. Lesen/Schreiben Single. |
| [Kumimoji](../../aspose.slides/baseportionformat/kumimoji) { get; set; } | Bestimmt, ob die Zahlen das speziell für östliche Sprachen definierte vertikale Layout des Textes ignorieren sollen. Keine Vererbung angewendet. Lesen/Schreiben [`NullableBool`](../nullablebool). |
| [LanguageId](../../aspose.slides/baseportionformat/languageid) { get; set; } | Gibt die Id einer Korrektursprache zurück oder legt sie fest. Wird zur Rechtschreib- und Grammatikprüfung verwendet. Lesen/Schreiben String. |
| [LatinFont](../../aspose.slides/baseportionformat/latinfont) { get; set; } | Gibt die lateinischen Schriftinformationen zurück oder legt sie fest. null bedeutet, dass die Schriftart undefiniert ist und vom Master geerbt werden sollte. Lesen/Schreiben [`IFontData`](../ifontdata). |
| [LineFormat](../../aspose.slides/baseportionformat/lineformat) { get; } | Gibt die LineFormat-Eigenschaften für die Textkontur zurück. Keine Vererbung angewendet. Nur lesbar [`ILineFormat`](../ilineformat). |
| [NormaliseHeight](../../aspose.slides/baseportionformat/normaliseheight) { get; set; } | Bestimmt, ob die Text-Höhe normalisiert werden soll. Keine Vererbung angewendet. Lesen/Schreiben [`NullableBool`](../nullablebool). |
| [ProofDisabled](../../aspose.slides/baseportionformat/proofdisabled) { get; set; } | Bestimmt, ob der Text nicht geprüft werden soll. Keine Vererbung angewendet. Lesen/Schreiben [`NullableBool`](../nullablebool). |
| [SmartTagClean](../../aspose.slides/portionformat/smarttagclean) { get; set; } | Bestimmt, ob das Smart-Tag bereinigt werden soll. Keine Vererbung angewendet. Lesen/Schreiben Boolean. |
| [Spacing](../../aspose.slides/baseportionformat/spacing) { get; set; } | Gibt die Erhöhung des Zeichenabstands zurück oder legt sie fest. **float.NaN** bedeutet, dass der Wert undefiniert ist und vom Master geerbt werden sollte. Lesen/Schreiben Single. |
| [SpellCheck](../../aspose.slides/baseportionformat/spellcheck) { get; set; } | Gibt an oder legt fest, ob die Rechtschreibprüfung für den Textabschnitt aktiviert ist. Wenn diese Eigenschaft auf false gesetzt ist, werden Rechtschreibprüfungen für Textelemente unterdrückt. Wenn sie auf true gesetzt ist, ist die Rechtschreibprüfung erlaubt. Der Standardwert ist `false`. |
| [StrikethroughType](../../aspose.slides/baseportionformat/strikethroughtype) { get; set; } | Gibt den Durchstreichungs-Typ eines Textes zurück oder legt ihn fest. Keine Vererbung angewendet. Lesen/Schreiben [`TextStrikethroughType`](../textstrikethroughtype). |
| [SymbolFont](../../aspose.slides/baseportionformat/symbolfont) { get; set; } | Gibt die symbolischen Schriftinformationen zurück oder legt sie fest. null bedeutet, dass die Schriftart undefiniert ist und vom Master geerbt werden sollte. Lesen/Schreiben [`IFontData`](../ifontdata). |
| [TextCapType](../../aspose.slides/baseportionformat/textcaptype) { get; set; } | Gibt die Art der Groß-/Kleinschreibung des Textes zurück oder legt sie fest. Keine Vererbung angewendet. Lesen/Schreiben [`TextCapType`](../textcaptype). |
| [UnderlineFillFormat](../../aspose.slides/baseportionformat/underlinefillformat) { get; } | Gibt die FillFormat-Eigenschaften der Unterstreichungs-Linie zurück. Keine Vererbung angewendet. Nur lesbar [`IFillFormat`](../ifillformat). |
| [UnderlineLineFormat](../../aspose.slides/baseportionformat/underlinelineformat) { get; } | Gibt die LineFormat-Eigenschaften zurück, die zum Umranden der Unterstreichungs-Linie verwendet werden. Keine Vererbung angewendet. Nur lesbar [`ILineFormat`](../ilineformat). |

## Methoden

| Name | Beschreibung |
| --- | --- |
| override [Equals](../../aspose.slides/pviobject/equals)(object) | Vergleicht mit dem angegebenen Objekt. |
| [GetEffective](../../aspose.slides/portionformat/geteffective)() | Ermittelt die effektiven Formatierungsdaten des Abschnitts mit angewandter Vererbung. |
| override [GetHashCode](../../aspose.slides/pviobject/gethashcode)() | Gibt den Hashcode zurück. |

### Anmerkungen

Diese Klasse wird verwendet, um die für den jeweiligen Abschnitt definierten Formatierungseigenschaften zurückzugeben und zu manipulieren. Das bedeutet, dass beim Abrufen von Werten keine Vererbung angewendet wird, sodass Sie in den meisten Fällen Werte erhalten, die „undefiniert“ bedeuten.

Um die effektiven Formatierungsparameterwerte einschließlich der vererbten zu erhalten, müssen Sie die Methode [`GetEffective`](./geteffective) verwenden, die eine Instanz von [`IPortionFormatEffectiveData`](../iportionformateffectivedata) zurückgibt.

### Beispiele

Das folgende Beispiel zeigt, wie man die lateinische Schrift einer Paragraph-Abschnitt einer PowerPoint-Präsentation zuweist.

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
// Aspose.Slides verwendet diese speziellen Bezeichner (ähnlich denen, die in PowerPoint verwendet werden):
// +mn-lt - Body-Schriftart Latin (Kleinere Latin-Schrift)
// +mj-lt - Überschrift-Schriftart Latin (Haupt-Latin-Schrift)
// +mn-ea - Body-Schriftart Ostasiatisch (Kleinere Ostasiatische Schrift)
// +mj-ea - Body-Schriftart Ostasiatisch (Kleinere Ostasiatische Schrift)
portion.PortionFormat.LatinFont = new FontData("+mn-lt");
}
```

### Siehe auch

* Klasse [BasePortionFormat](../baseportionformat)
* Schnittstelle [IPortionFormat](../iportionformat)
* Namensraum [Aspose.Slides](../../aspose.slides)
* Assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->