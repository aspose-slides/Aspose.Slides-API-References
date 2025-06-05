---
title: BasePortionFormat
second_title: Aspose.Slides für .NET API Referenz
description: Gemeinsame Textabschnittsformatierungs-Eigenschaften.
type: docs
weight: 890
url: /de/aspose.slides/baseportionformat/
---

## BasePortionFormat Klasse

Gemeinsame Textabschnittsformatierungs-Eigenschaften.

```csharp
public abstract class BasePortionFormat : PVIObject, IBasePortionFormat
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [AlternativeLanguageId](../../aspose.slides/baseportionformat/alternativelanguageid) { get; set; } | Gibt die ID einer alternativen Sprache zurück oder setzt sie. Lese-/Schreibzugriff String. |
| [AsIPresentationComponent](../../aspose.slides/pviobject/asipresentationcomponent) { get; } | Ermöglicht den Zugriff auf die Basisschnittstelle IPresentationComponent. Nur-Lese [`IPresentationComponent`](../ipresentationcomponent). |
| [ComplexScriptFont](../../aspose.slides/baseportionformat/complexscriptfont) { get; set; } | Gibt die Informationen zur Schriftart für komplexe Schriftarten zurück oder setzt diese. Null bedeutet, dass die Schriftart undefiniert ist und vom Master geerbt werden sollte. Lese-/Schreibzugriff [`IFontData`](../ifontdata). |
| [EastAsianFont](../../aspose.slides/baseportionformat/eastasianfont) { get; set; } | Gibt die Informationen zur Schriftart für ostasiatische Schriften zurück oder setzt diese. Null bedeutet, dass die Schriftart undefiniert ist und vom Master geerbt werden sollte. Lese-/Schreibzugriff [`IFontData`](../ifontdata). |
| [EffectFormat](../../aspose.slides/baseportionformat/effectformat) { get; } | Gibt die Text-Effektformatierungs-Eigenschaften zurück. Keine Vererbung angewendet. Nur-Lese [`IEffectFormat`](../ieffectformat). |
| [Escapement](../../aspose.slides/baseportionformat/escapement) { get; set; } | Gibt den Hoch- oder Tiefstellungstext zurück oder setzt ihn. Werte von -100% (Tiefstellung) bis 100% (Hochstellung). **float.NaN** bedeutet, dass der Wert undefiniert ist und vom Master geerbt werden sollte. Lese-/Schreibzugriff Single. |
| [FillFormat](../../aspose.slides/baseportionformat/fillformat) { get; } | Gibt die FillFormat-Eigenschaften des Textes zurück. Keine Vererbung angewendet. Nur-Lese [`IFillFormat`](../ifillformat). |
| [FontBold](../../aspose.slides/baseportionformat/fontbold) { get; set; } | Bestimmt, ob die Schriftart fett ist. Keine Vererbung angewendet. Lese-/Schreibzugriff [`NullableBool`](../nullablebool). |
| [FontHeight](../../aspose.slides/baseportionformat/fontheight) { get; set; } | Gibt die Schriftart-Höhe eines Abschnitts zurück oder setzt sie. **float.NaN** bedeutet, dass die Höhe undefiniert ist und vom Master geerbt werden sollte. Lese-/Schreibzugriff Single. |
| [FontItalic](../../aspose.slides/baseportionformat/fontitalic) { get; set; } | Bestimmt, ob die Schriftart kursiv ist. Keine Vererbung angewendet. Lese-/Schreibzugriff [`NullableBool`](../nullablebool). |
| [FontUnderline](../../aspose.slides/baseportionformat/fontunderline) { get; set; } | Gibt den Unterstreichungsstil des Textes zurück oder setzt ihn. Keine Vererbung angewendet. Lese-/Schreibzugriff [`TextUnderlineType`](../textunderlinetype). |
| [HighlightColor](../../aspose.slides/baseportionformat/highlightcolor) { get; } | Gibt die Farbe zurück, die zum Hervorheben eines Textes verwendet wird. Keine Vererbung angewendet. Nur-Lese [`IColorFormat`](../icolorformat). |
| [IsHardUnderlineFill](../../aspose.slides/baseportionformat/ishardunderlinefill) { get; set; } | Bestimmt, ob der Unterstreichungsstil eigene FillFormat-Eigenschaften hat oder sie von den FillFormat-Eigenschaften des Textes erbt. Lese-/Schreibzugriff [`NullableBool`](../nullablebool). |
| [IsHardUnderlineLine](../../aspose.slides/baseportionformat/ishardunderlineline) { get; set; } | Bestimmt, ob der Unterstreichungsstil eigene LineFormat-Eigenschaften hat oder sie von den LineFormat-Eigenschaften des Textes erbt. Lese-/Schreibzugriff [`NullableBool`](../nullablebool). |
| [KerningMinimalSize](../../aspose.slides/baseportionformat/kerningminimalsize) { get; set; } | Gibt die minimale Schriftgröße zurück oder setzt sie, für die Kerning aktiviert sein sollte. **float.NaN** bedeutet, dass der Wert undefiniert ist und vom Master geerbt werden sollte. Lese-/Schreibzugriff Single. |
| [Kumimoji](../../aspose.slides/baseportionformat/kumimoji) { get; set; } | Bestimmt, ob die Zahlen das spezifische vertikale Layout für östliche Sprachen ignorieren sollten. Keine Vererbung angewendet. Lese-/Schreibzugriff [`NullableBool`](../nullablebool). |
| [LanguageId](../../aspose.slides/baseportionformat/languageid) { get; set; } | Gibt die ID einer Prüfungs- bzw. Korrektursprache zurück oder setzt sie. Wird zur Rechtschreib- und Grammatikprüfung verwendet. Lese-/Schreibzugriff String. |
| [LatinFont](../../aspose.slides/baseportionformat/latinfont) { get; set; } | Gibt die Informationen zur Lateinschriftart zurück oder setzt diese. Null bedeutet, dass die Schriftart undefiniert ist und vom Master geerbt werden sollte. Lese-/Schreibzugriff [`IFontData`](../ifontdata). |
| [LineFormat](../../aspose.slides/baseportionformat/lineformat) { get; } | Gibt die LineFormat-Eigenschaften für die Textkonturierung zurück. Keine Vererbung angewendet. Nur-Lese [`ILineFormat`](../ilineformat). |
| [NormaliseHeight](../../aspose.slides/baseportionformat/normaliseheight) { get; set; } | Bestimmt, ob die Höhe eines Textes normalisiert werden sollte. Keine Vererbung angewendet. Lese-/Schreibzugriff [`NullableBool`](../nullablebool). |
| [ProofDisabled](../../aspose.slides/baseportionformat/proofdisabled) { get; set; } | Bestimmt, ob der Text nicht geprüft werden sollte. Keine Vererbung angewendet. Lese-/Schreibzugriff [`NullableBool`](../nullablebool). |
| [Spacing](../../aspose.slides/baseportionformat/spacing) { get; set; } | Gibt den interkarakterlichen Abstandsinkrement zurück oder setzt ihn. **float.NaN** bedeutet, dass der Wert undefiniert ist und vom Master geerbt werden sollte. Lese-/Schreibzugriff Single. |
| [StrikethroughType](../../aspose.slides/baseportionformat/strikethroughtype) { get; set; } | Gibt den Durchstreichungsstil eines Textes zurück oder setzt ihn. Keine Vererbung angewendet. Lese-/Schreibzugriff [`TextStrikethroughType`](../textstrikethroughtype). |
| [SymbolFont](../../aspose.slides/baseportionformat/symbolfont) { get; set; } | Gibt die Informationen zur Symbolschriftart zurück oder setzt diese. Null bedeutet, dass die Schriftart undefiniert ist und vom Master geerbt werden sollte. Lese-/Schreibzugriff [`IFontData`](../ifontdata). |
| [TextCapType](../../aspose.slides/baseportionformat/textcaptype) { get; set; } | Gibt den Typ der Textformatierung in Großbuchstaben zurück oder setzt ihn. Keine Vererbung angewendet. Lese-/Schreibzugriff [`TextCapType`](../textcaptype). |
| [UnderlineFillFormat](../../aspose.slides/baseportionformat/underlinefillformat) { get; } | Gibt die FillFormat-Eigenschaften der Unterstreichungslinie zurück. Keine Vererbung angewendet. Nur-Lese [`IFillFormat`](../ifillformat). |
| [UnderlineLineFormat](../../aspose.slides/baseportionformat/underlinelineformat) { get; } | Gibt die LineFormat-Eigenschaften zurück, die zum Konturieren der Unterstreichungslinie verwendet werden. Keine Vererbung angewendet. Nur-Lese [`ILineFormat`](../ilineformat). |

## Methoden

| Name | Beschreibung |
| --- | --- |
| override [Equals](../../aspose.slides/pviobject/equals)(object) | Vergleicht mit dem angegebenen Objekt. |
| override [GetHashCode](../../aspose.slides/pviobject/gethashcode)() | Gibt den Hash-Code zurück. |

### Siehe Auch

* Klasse [PVIObject](../pviobject)
* Schnittstelle [IBasePortionFormat](../ibaseportionformat)
* Namespace [Aspose.Slides](../../aspose.slides)
* Assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->