---
title: BasePortionFormat
second_title: Aspose.Slides für .NET API Referenz
description: Allgemeine Eigenschaften der Textformatierung von Teilen.
type: docs
weight: 890
url: /de/aspose.slides/baseportionformat/
---

## BasePortionFormat-Klasse

Allgemeine Eigenschaften der Textformatierung von Teilen.

```csharp
public abstract class BasePortionFormat : PVIObject, IBasePortionFormat
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [AlternativeLanguageId](../../aspose.slides/baseportionformat/alternativelanguageid) { get; set; } | Gibt die ID einer alternativen Sprache zurück oder setzt sie. Lese-/Schreib-Zeichenfolge. |
| [AsIPresentationComponent](../../aspose.slides/pviobject/asipresentationcomponent) { get; } | Ermöglicht den Zugriff auf die Basis-IPresentationComponent-Schnittstelle. Nur-Lese [`IPresentationComponent`](../ipresentationcomponent). |
| [ComplexScriptFont](../../aspose.slides/baseportionformat/complexscriptfont) { get; set; } | Gibt die Informationen zur Schriftart für komplexe Skripte zurück oder setzt sie. Null bedeutet, dass die Schriftart undefiniert ist und von der Master-Formate geerbt werden sollte. Lese-/Schreib [`IFontData`](../ifontdata). |
| [EastAsianFont](../../aspose.slides/baseportionformat/eastasianfont) { get; set; } | Gibt die Informationen zur Schriftart für ostasiatische Sprachen zurück oder setzt sie. Null bedeutet, dass die Schriftart undefiniert ist und von der Master-Formate geerbt werden sollte. Lese-/Schreib [`IFontData`](../ifontdata). |
| [EffectFormat](../../aspose.slides/baseportionformat/effectformat) { get; } | Gibt die Effektformat-Eigenschaften des Textes zurück. Keine Vererbung angewendet. Nur-Lese [`IEffectFormat`](../ieffectformat). |
| [Escapement](../../aspose.slides/baseportionformat/escapement) { get; set; } | Gibt den Hochgestellt- oder Tiefgestellt-Text zurück oder setzt ihn. Wert von -100% (Tiefgestellt) bis 100% (Hochgestellt). **float.NaN** bedeutet, dass der Wert undefiniert ist und von der Master-Formate geerbt werden sollte. Lese-/Schreib Einfach. |
| [FillFormat](../../aspose.slides/baseportionformat/fillformat) { get; } | Gibt die Füllformat-Eigenschaften des Textes zurück. Keine Vererbung angewendet. Nur-Lese [`IFillFormat`](../ifillformat). |
| [FontBold](../../aspose.slides/baseportionformat/fontbold) { get; set; } | Bestimmt, ob die Schriftart fett ist. Keine Vererbung angewendet. Lese-/Schreib [`NullableBool`](../nullablebool). |
| [FontHeight](../../aspose.slides/baseportionformat/fontheight) { get; set; } | Gibt die Schriftgröße eines Teils zurück oder setzt sie. **float.NaN** bedeutet, dass die Höhe undefiniert ist und von der Master-Formate geerbt werden sollte. Lese-/Schreib Einfach. |
| [FontItalic](../../aspose.slides/baseportionformat/fontitalic) { get; set; } | Bestimmt, ob die Schriftart kursiv ist. Keine Vererbung angewendet. Lese-/Schreib [`NullableBool`](../nullablebool). |
| [FontUnderline](../../aspose.slides/baseportionformat/fontunderline) { get; set; } | Gibt den Typ der Textunterstreichung zurück oder setzt ihn. Keine Vererbung angewendet. Lese-/Schreib [`TextUnderlineType`](../textunderlinetype). |
| [HighlightColor](../../aspose.slides/baseportionformat/highlightcolor) { get; } | Gibt die Farbe zurück, die zum Hervorheben eines Textes verwendet wird. Keine Vererbung angewendet. Nur-Lese [`IColorFormat`](../icolorformat). |
| [IsHardUnderlineFill](../../aspose.slides/baseportionformat/ishardunderlinefill) { get; set; } | Bestimmt, ob der Unterstreichungsstil eigene Füllformat-Eigenschaften hat oder sie von den Füllformat-Eigenschaften des Textes erbt. Lese-/Schreib [`NullableBool`](../nullablebool). |
| [IsHardUnderlineLine](../../aspose.slides/baseportionformat/ishardunderlineline) { get; set; } | Bestimmt, ob der Unterstreichungsstil eigene Linienformat-Eigenschaften hat oder sie von den Linienformat-Eigenschaften des Textes erbt. Lese-/Schreib [`NullableBool`](../nullablebool). |
| [KerningMinimalSize](../../aspose.slides/baseportionformat/kerningminimalsize) { get; set; } | Gibt die minimale Schriftgröße zurück oder setzt sie, für die die Schriftkerning aktiviert sein sollte. **float.NaN** bedeutet, dass der Wert undefiniert ist und von der Master-Formate geerbt werden sollte. Lese-/Schreib Einfach. |
| [Kumimoji](../../aspose.slides/baseportionformat/kumimoji) { get; set; } | Bestimmt, ob die Zahlen das spezifische vertikale Layout von Ostasiatischen Sprachen ignorieren sollen. Keine Vererbung angewendet. Lese-/Schreib [`NullableBool`](../nullablebool). |
| [LanguageId](../../aspose.slides/baseportionformat/languageid) { get; set; } | Gibt die ID einer Prüfungsprache zurück oder setzt sie. Wird zur Überprüfung von Rechtschreibung und Grammatik verwendet. Lese-/Schreib Zeichenfolge. |
| [LatinFont](../../aspose.slides/baseportionformat/latinfont) { get; set; } | Gibt die Informationen zur lateinischen Schriftart zurück oder setzt sie. Null bedeutet, dass die Schriftart undefiniert ist und von der Master-Formate geerbt werden sollte. Lese-/Schreib [`IFontData`](../ifontdata). |
| [LineFormat](../../aspose.slides/baseportionformat/lineformat) { get; } | Gibt die Linienformat-Eigenschaften für die Textumriss zurück. Keine Vererbung angewendet. Nur-Lese [`ILineFormat`](../ilineformat). |
| [NormaliseHeight](../../aspose.slides/baseportionformat/normaliseheight) { get; set; } | Bestimmt, ob die Höhe eines Textes normalisiert werden soll. Keine Vererbung angewendet. Lese-/Schreib [`NullableBool`](../nullablebool). |
| [ProofDisabled](../../aspose.slides/baseportionformat/proofdisabled) { get; set; } | Bestimmt, ob der Text nicht überprüft werden soll. Keine Vererbung angewendet. Lese-/Schreib [`NullableBool`](../nullablebool). |
| [Spacing](../../aspose.slides/baseportionformat/spacing) { get; set; } | Gibt den Abstand zwischen den Zeichen zurück oder setzt ihn. **float.NaN** bedeutet, dass der Wert undefiniert ist und von der Master-Formate geerbt werden sollte. Lese-/Schreib Einfach. |
| [StrikethroughType](../../aspose.slides/baseportionformat/strikethroughtype) { get; set; } | Gibt den Typ der Durchstreichung eines Textes zurück oder setzt ihn. Keine Vererbung angewendet. Lese-/Schreib [`TextStrikethroughType`](../textstrikethroughtype). |
| [SymbolFont](../../aspose.slides/baseportionformat/symbolfont) { get; set; } | Gibt die symbolische Schriftart-Informationen zurück oder setzt sie. Null bedeutet, dass die Schriftart undefiniert ist und von der Master-Formate geerbt werden sollte. Lese-/Schreib [`IFontData`](../ifontdata). |
| [TextCapType](../../aspose.slides/baseportionformat/textcaptype) { get; set; } | Gibt den Typ der Textkapitalisierung zurück oder setzt ihn. Keine Vererbung angewendet. Lese-/Schreib [`TextCapType`](../textcaptype). |
| [UnderlineFillFormat](../../aspose.slides/baseportionformat/underlinefillformat) { get; } | Gibt die Füllformat-Eigenschaften der Unterstreichungslinie zurück. Keine Vererbung angewendet. Nur-Lese [`IFillFormat`](../ifillformat). |
| [UnderlineLineFormat](../../aspose.slides/baseportionformat/underlinelineformat) { get; } | Gibt die Linienformat-Eigenschaften zurück, die zum Umriss der Unterstreichungslinie verwendet werden. Keine Vererbung angewendet. Nur-Lese [`ILineFormat`](../ilineformat). |

## Methoden

| Name | Beschreibung |
| --- | --- |
| override [Equals](../../aspose.slides/pviobject/equals)(object) | Vergleicht mit dem angegebenen Objekt. |
| override [GetHashCode](../../aspose.slides/pviobject/gethashcode)() | Gibt den Hash-Code zurück. |

### Siehe auch

* Klasse [PVIObject](../pviobject)
* Schnittstelle [IBasePortionFormat](../ibaseportionformat)
* Namensraum [Aspose.Slides](../../aspose.slides)
* Assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->