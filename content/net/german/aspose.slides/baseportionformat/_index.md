---
title: BasePortionFormat
second_title: Aspose.Sildes für .NET API-Referenz
description: Gemeinsame Eigenschaften zur Formatierung von Textabschnitten.
type: docs
weight: 970
url: /de/aspose.slides/baseportionformat/
---
## BasePortionFormat Klasse

Gemeinsame Textabschnitt-Formatierungseigenschaften.

```csharp
public abstract class BasePortionFormat : PVIObject, IBasePortionFormat
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [AlternativeLanguageId](../../aspose.slides/baseportionformat/alternativelanguageid) { get; set; } | Gibt die Id einer alternativen Sprache zurück oder legt sie fest. Lese/Schreiben String. |
| [AsIPresentationComponent](../../aspose.slides/pviobject/asipresentationcomponent) { get; } | Ermöglicht das Abrufen der Basis-IPresentationComponent-Schnittstelle. Nur lesend [`IPresentationComponent`](../ipresentationcomponent). |
| [ComplexScriptFont](../../aspose.slides/baseportionformat/complexscriptfont) { get; set; } | Gibt die Schriftinformationen für komplexe Skripte zurück oder legt sie fest. Null bedeutet, dass die Schriftart undefiniert ist und vom Master geerbt werden soll. Lese/Schreiben [`IFontData`](../ifontdata). |
| [EastAsianFont](../../aspose.slides/baseportionformat/eastasianfont) { get; set; } | Gibt die Schriftinformationen für ostasiatische Schriften zurück oder legt sie fest. Null bedeutet, dass die Schriftart undefiniert ist und vom Master geerbt werden soll. Lese/Schreiben [`IFontData`](../ifontdata). |
| [EffectFormat](../../aspose.slides/baseportionformat/effectformat) { get; } | Gibt die EffectFormat-Eigenschaften des Textes zurück. Keine Vererbung angewendet. Nur lesend [`IEffectFormat`](../ieffectformat). |
| [Escapement](../../aspose.slides/baseportionformat/escapement) { get; set; } | Gibt den hoch- oder tiefgestellten Text zurück oder legt ihn fest. Wert von -100 % (tiefgestellt) bis 100 % (hochgestellt). **float.NaN** bedeutet, dass der Wert undefiniert ist und vom Master geerbt werden soll. Lese/Schreiben Single. |
| [FillFormat](../../aspose.slides/baseportionformat/fillformat) { get; } | Gibt die FillFormat-Eigenschaften des Textes zurück. Keine Vererbung angewendet. Nur lesend [`IFillFormat`](../ifillformat). |
| [FontBold](../../aspose.slides/baseportionformat/fontbold) { get; set; } | Bestimmt, ob die Schrift fett ist. Keine Vererbung angewendet. Lese/Schreiben [`NullableBool`](../nullablebool). |
| [FontHeight](../../aspose.slides/baseportionformat/fontheight) { get; set; } | Gibt die Schriftgröße eines Abschnitts zurück oder legt sie fest. **float.NaN** bedeutet, dass die Höhe undefiniert ist und vom Master geerbt werden soll. Lese/Schreiben Single. |
| [FontItalic](../../aspose.slides/baseportionformat/fontitalic) { get; set; } | Bestimmt, ob die Schrift kursiv ist. Keine Vererbung angewendet. Lese/Schreiben [`NullableBool`](../nullablebool). |
| [FontUnderline](../../aspose.slides/baseportionformat/fontunderline) { get; set; } | Gibt den Unterstreichungsstil des Textes zurück oder legt ihn fest. Keine Vererbung angewendet. Lese/Schreiben [`TextUnderlineType`](../textunderlinetype). |
| [HighlightColor](../../aspose.slides/baseportionformat/highlightcolor) { get; } | Gibt die zum Hervorheben von Text verwendete Farbe zurück. Keine Vererbung angewendet. Nur lesend [`IColorFormat`](../icolorformat). |
| [IsHardUnderlineFill](../../aspose.slides/baseportionformat/ishardunderlinefill) { get; set; } | Bestimmt, ob der Unterstreichungsstil eigene FillFormat-Eigenschaften hat oder sie von den FillFormat-Eigenschaften des Textes erbt. Lese/Schreiben [`NullableBool`](../nullablebool). |
| [IsHardUnderlineLine](../../aspose.slides/baseportionformat/ishardunderlineline) { get; set; } | Bestimmt, ob der Unterstreichungsstil eigene LineFormat-Eigenschaften hat oder sie von den LineFormat-Eigenschaften des Textes erbt. Lese/Schreiben [`NullableBool`](../nullablebool). |
| [KerningMinimalSize](../../aspose.slides/baseportionformat/kerningminimalsize) { get; set; } | Gibt die minimale Schriftgröße zurück oder legt sie fest, bei der die Unterschneidung aktiviert werden soll. **float.NaN** bedeutet, dass der Wert undefiniert ist und vom Master geerbt werden soll. Lese/Schreiben Single. |
| [Kumimoji](../../aspose.slides/baseportionformat/kumimoji) { get; set; } | Bestimmt, ob die Zahlen das länderspezifische vertikale Layout des ostasiatischen Textes ignorieren sollen. Keine Vererbung angewendet. Lese/Schreiben [`NullableBool`](../nullablebool). |
| [LanguageId](../../aspose.slides/baseportionformat/languageid) { get; set; } | Gibt die Id einer Korrektursprache zurück oder legt sie fest. Wird zur Rechtschreib- und Grammatikprüfung verwendet. Lese/Schreiben String. |
| [LatinFont](../../aspose.slides/baseportionformat/latinfont) { get; set; } | Gibt die Schriftinformationen für Latein zurück oder legt sie fest. Null bedeutet, dass die Schriftart undefiniert ist und vom Master geerbt werden soll. Lese/Schreiben [`IFontData`](../ifontdata). |
| [LineFormat](../../aspose.slides/baseportionformat/lineformat) { get; } | Gibt die LineFormat-Eigenschaften für die Textumrandung zurück. Keine Vererbung angewendet. Nur lesend [`ILineFormat`](../ilineformat). |
| [NormaliseHeight](../../aspose.slides/baseportionformat/normaliseheight) { get; set; } | Bestimmt, ob die Höhe eines Textes normalisiert werden soll. Keine Vererbung angewendet. Lese/Schreiben [`NullableBool`](../nullablebool). |
| [ProofDisabled](../../aspose.slides/baseportionformat/proofdisabled) { get; set; } | Bestimmt, ob der Text nicht geprüft werden soll. Keine Vererbung angewendet. Lese/Schreiben [`NullableBool`](../nullablebool). |
| [Spacing](../../aspose.slides/baseportionformat/spacing) { get; set; } | Gibt die Erhöhung des Zwischenzeichnungsabstands zurück oder legt sie fest. **float.NaN** bedeutet, dass der Wert undefiniert ist und vom Master geerbt werden soll. Lese/Schreiben Single. |
| [SpellCheck](../../aspose.slides/baseportionformat/spellcheck) { get; set; } | Gibt einen Wert zurück oder legt ihn fest, der angibt, ob die Rechtschreibprüfung für den Textabschnitt aktiviert ist. Wenn diese Eigenschaft auf false gesetzt ist, werden Rechtschreibprüfungen für Textelemente unterdrückt. Wenn sie auf true gesetzt ist, ist die Rechtschreibprüfung erlaubt. Standardwert ist `false`. |
| [StrikethroughType](../../aspose.slides/baseportionformat/strikethroughtype) { get; set; } | Gibt den Durchstreichungstyp eines Textes zurück oder legt ihn fest. Keine Vererbung angewendet. Lese/Schreiben [`TextStrikethroughType`](../textstrikethroughtype). |
| [SymbolFont](../../aspose.slides/baseportionformat/symbolfont) { get; set; } | Gibt die symbolischen Schriftinformationen zurück oder legt sie fest. Null bedeutet, dass die Schriftart undefiniert ist und vom Master geerbt werden soll. Lese/Schreiben [`IFontData`](../ifontdata). |
| [TextCapType](../../aspose.slides/baseportionformat/textcaptype) { get; set; } | Gibt die Schreibweise des Textes zurück oder legt sie fest. Keine Vererbung angewendet. Lese/Schreiben [`TextCapType`](../textcaptype). |
| [UnderlineFillFormat](../../aspose.slides/baseportionformat/underlinefillformat) { get; } | Gibt die FillFormat-Eigenschaften der Unterstreichungslinie zurück. Keine Vererbung angewendet. Nur lesend [`IFillFormat`](../ifillformat). |
| [UnderlineLineFormat](../../aspose.slides/baseportionformat/underlinelineformat) { get; } | Gibt die LineFormat-Eigenschaften zurück, die zum Umranden der Unterstreichungslinie verwendet werden. Keine Vererbung angewendet. Nur lesend [`ILineFormat`](../ilineformat). |

## Methoden

| Name | Beschreibung |
| --- | --- |
| override [Equals](../../aspose.slides/pviobject/equals)(object) | Vergleicht mit dem angegebenen Objekt. |
| override [GetHashCode](../../aspose.slides/pviobject/gethashcode)() | Gibt den Hashcode zurück. |

### Siehe auch

* Klasse [PVIObject](../pviobject)
* Schnittstelle [IBasePortionFormat](../ibaseportionformat)
* Namensraum [Aspose.Slides](../../aspose.slides)
* Assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->