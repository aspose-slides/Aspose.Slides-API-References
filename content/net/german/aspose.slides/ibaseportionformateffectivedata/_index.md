---
title: IBasePortionFormatEffectiveData
second_title: Aspose.Sildes für .NET API-Referenz
description: Basisschnittstelle für unveränderliche Objekte, die effektive Textabschnitt-Formatierungseigenschaften enthalten.
type: docs
weight: 5340
url: /de/aspose.slides/ibaseportionformateffectivedata/
---
## IBasePortionFormatEffectiveData Schnittstelle

Basis-Schnittstelle für unveränderliche Objekte, die effektive Textabschnitt-Formatierungseigenschaften enthalten.

```csharp
public interface IBasePortionFormatEffectiveData
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [AlternativeLanguageId](../../aspose.slides/ibaseportionformateffectivedata/alternativelanguageid) { get; } | Gibt die Id einer alternativen Sprache zurück. Nur lesbar String. |
| [ComplexScriptFont](../../aspose.slides/ibaseportionformateffectivedata/complexscriptfont) { get; } | Gibt die Informationen zur komplexen Schriftart zurück. Nur lesbar [`IFontData`](../ifontdata). |
| [EastAsianFont](../../aspose.slides/ibaseportionformateffectivedata/eastasianfont) { get; } | Gibt die Informationen zur ostasiatischen Schriftart zurück. Nur lesbar [`IFontData`](../ifontdata). |
| [EffectFormat](../../aspose.slides/ibaseportionformateffectivedata/effectformat) { get; } | Gibt die Text EffectFormat Eigenschaften zurück. Nur lesbar [`IEffectFormatEffectiveData`](../ieffectformateffectivedata). |
| [Escapement](../../aspose.slides/ibaseportionformateffectivedata/escapement) { get; } | Gibt den hoch- oder tiefgestellten Text zurück. Wert von -100 % (tiefgestellt) bis 100 % (hochgestellt). Nur lesbar Single. |
| [FillFormat](../../aspose.slides/ibaseportionformateffectivedata/fillformat) { get; } | Gibt die Text FillFormat Eigenschaften zurück. Nur lesbar [`IFillFormatEffectiveData`](../ifillformateffectivedata). |
| [FontBold](../../aspose.slides/ibaseportionformateffectivedata/fontbold) { get; } | Bestimmt, ob die Schrift fett ist. Nur lesbar Boolean. |
| [FontHeight](../../aspose.slides/ibaseportionformateffectivedata/fontheight) { get; } | Gibt die Schriftgröße des Textabschnitts in Punkt zurück. Nur lesbar Single. |
| [FontItalic](../../aspose.slides/ibaseportionformateffectivedata/fontitalic) { get; } | Bestimmt, ob die Schrift kursiv ist. Nur lesbar Boolean. |
| [FontUnderline](../../aspose.slides/ibaseportionformateffectivedata/fontunderline) { get; } | Gibt den Textunterstreichungstyp zurück. Nur lesbar [`TextUnderlineType`](../textunderlinetype). |
| [HighlightColor](../../aspose.slides/ibaseportionformateffectivedata/highlightcolor) { get; } | Gibt die Farbe zurück, die zum Hervorheben eines Textes verwendet wird. Nur lesbar Color. |
| [IsHardUnderlineFill](../../aspose.slides/ibaseportionformateffectivedata/ishardunderlinefill) { get; } | Bestimmt, ob der Unterstreichungsstil eigene FillFormat-Eigenschaften hat oder sie von den FillFormat-Eigenschaften des Textes erbt. Nur lesbar Boolean. |
| [IsHardUnderlineLine](../../aspose.slides/ibaseportionformateffectivedata/ishardunderlineline) { get; } | Bestimmt, ob der Unterstreichungsstil eigene LineFormat-Eigenschaften hat oder sie von den LineFormat-Eigenschaften des Textes erbt. Nur lesbar Boolean. |
| [KerningMinimalSize](../../aspose.slides/ibaseportionformateffectivedata/kerningminimalsize) { get; } | Gibt die minimale Schriftgröße zurück, für die Kerning aktiviert werden soll. Nur lesbar Single. |
| [Kumimoji](../../aspose.slides/ibaseportionformateffectivedata/kumimoji) { get; } | Bestimmt, ob die Zahlen das östlichsprachenspezifische vertikale Textlayout ignorieren sollen. Nur lesbar Boolean. |
| [LanguageId](../../aspose.slides/ibaseportionformateffectivedata/languageid) { get; } | Gibt die Id einer Sprache zurück. Nur lesbar String. |
| [LatinFont](../../aspose.slides/ibaseportionformateffectivedata/latinfont) { get; } | Gibt die Informationen zur lateinischen Schriftart zurück. Nur lesbar [`IFontData`](../ifontdata). |
| [LineFormat](../../aspose.slides/ibaseportionformateffectivedata/lineformat) { get; } | Gibt die LineFormat-Eigenschaften für die Textumrandung zurück. Nur lesbar [`ILineFormatEffectiveData`](../ilineformateffectivedata). |
| [NormaliseHeight](../../aspose.slides/ibaseportionformateffectivedata/normaliseheight) { get; } | Bestimmt, ob die Höhe eines Textes normalisiert werden soll. Nur lesbar Boolean. |
| [ProofDisabled](../../aspose.slides/ibaseportionformateffectivedata/proofdisabled) { get; } | Bestimmt, ob der Text nicht geprüft werden soll. Nur lesbar Boolean. |
| [SmartTagClean](../../aspose.slides/ibaseportionformateffectivedata/smarttagclean) { get; } | Bestimmt, ob das Smart-Tag bereinigt werden soll. Nur lesbar Boolean. |
| [Spacing](../../aspose.slides/ibaseportionformateffectivedata/spacing) { get; } | Gibt die Zwischenzeichenabstandserhöhung in Punkt zurück. Nur lesbar Single. |
| [StrikethroughType](../../aspose.slides/ibaseportionformateffectivedata/strikethroughtype) { get; } | Gibt den Durchstreichtyp eines Textes zurück. Nur lesbar [`TextStrikethroughType`](../textstrikethroughtype). |
| [SymbolFont](../../aspose.slides/ibaseportionformateffectivedata/symbolfont) { get; } | Gibt die Informationen zur symbolischen Schriftart zurück. Nur lesbar [`IFontData`](../ifontdata). |
| [TextCapType](../../aspose.slides/ibaseportionformateffectivedata/textcaptype) { get; } | Gibt die Art der Textschreibung zurück. Nur lesbar [`TextCapType`](../textcaptype). |
| [UnderlineFillFormat](../../aspose.slides/ibaseportionformateffectivedata/underlinefillformat) { get; } | Gibt die FillFormat-Eigenschaften der Unterstreichungslinie zurück. Nur lesbar [`IFillFormatEffectiveData`](../ifillformateffectivedata). |
| [UnderlineLineFormat](../../aspose.slides/ibaseportionformateffectivedata/underlinelineformat) { get; } | Gibt die LineFormat-Eigenschaften zurück, die zum Umranden der Unterstreichungslinie verwendet werden. Nur lesbar [`ILineFormatEffectiveData`](../ilineformateffectivedata). |

### Siehe auch

* Namensraum [Aspose.Slides](../../aspose.slides)
* Assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->