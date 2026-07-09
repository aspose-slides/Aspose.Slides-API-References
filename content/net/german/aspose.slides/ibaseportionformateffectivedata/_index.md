---
title: IBasePortionFormatEffectiveData
second_title: Aspose.Sildes für .NET API-Referenz
description: Basisschnittstelle für unveränderliche Objekte, die effektive Textabschnitt-Formatierungseigenschaften enthalten.
type: docs
weight: 5320
url: /de/aspose.slides/ibaseportionformateffectivedata/
---
## IBasePortionFormatEffectiveData Schnittstelle

Base-Interface für unveränderliche Objekte, die effektive Text-Abschnitt-Formatierungseigenschaften enthalten.

```csharp
public interface IBasePortionFormatEffectiveData
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [AlternativeLanguageId](../../aspose.slides/ibaseportionformateffectivedata/alternativelanguageid) { get; } | Gibt die Id einer alternativen Sprache zurück. Nur-Lesen String. |
| [ComplexScriptFont](../../aspose.slides/ibaseportionformateffectivedata/complexscriptfont) { get; } | Gibt die Informationen zur komplexen Skript-Schriftart zurück. Nur-Lesen [`IFontData`](../ifontdata). |
| [EastAsianFont](../../aspose.slides/ibaseportionformateffectivedata/eastasianfont) { get; } | Gibt die Informationen zur ostasiatischen Schriftart zurück. Nur-Lesen [`IFontData`](../ifontdata). |
| [EffectFormat](../../aspose.slides/ibaseportionformateffectivedata/effectformat) { get; } | Gibt die Effektformat-Eigenschaften des Textes zurück. Nur-Lesen [`IEffectFormatEffectiveData`](../ieffectformateffectivedata). |
| [Escapement](../../aspose.slides/ibaseportionformateffectivedata/escapement) { get; } | Gibt den hoch- oder tiefgestellten Text zurück. Wert von -100 % (tiefgestellt) bis 100 % (hochgestellt). Nur-Lesen Single. |
| [FillFormat](../../aspose.slides/ibaseportionformateffectivedata/fillformat) { get; } | Gibt die FillFormat-Eigenschaften des Textes zurück. Nur-Lesen [`IFillFormatEffectiveData`](../ifillformateffectivedata). |
| [FontBold](../../aspose.slides/ibaseportionformateffectivedata/fontbold) { get; } | Bestimmt, ob die Schrift fett ist. Nur-Lesen Boolean. |
| [FontHeight](../../aspose.slides/ibaseportionformateffectivedata/fontheight) { get; } | Gibt die Schriftgröße des Textabschnitts in Punkten zurück. Nur-Lesen Single. |
| [FontItalic](../../aspose.slides/ibaseportionformateffectivedata/fontitalic) { get; } | Bestimmt, ob die Schrift kursiv ist. Nur-Lesen Boolean. |
| [FontUnderline](../../aspose.slides/ibaseportionformateffectivedata/fontunderline) { get; } | Gibt den Unterstreichungs-Typ des Textes zurück. Nur-Lesen [`TextUnderlineType`](../textunderlinetype). |
| [HighlightColor](../../aspose.slides/ibaseportionformateffectivedata/highlightcolor) { get; } | Gibt die Farbe zurück, die zum Hervorheben von Text verwendet wird. Nur-Lesen Color. |
| [IsHardUnderlineFill](../../aspose.slides/ibaseportionformateffectivedata/ishardunderlinefill) { get; } | Bestimmt, ob der Unterstreichungsstil eigene FillFormat-Eigenschaften hat oder sie von den FillFormat-Eigenschaften des Textes erbt. Nur-Lesen Boolean. |
| [IsHardUnderlineLine](../../aspose.slides/ibaseportionformateffectivedata/ishardunderlineline) { get; } | Bestimmt, ob der Unterstreichungsstil eigene LineFormat-Eigenschaften hat oder sie von den LineFormat-Eigenschaften des Textes erbt. Nur-Lesen Boolean. |
| [KerningMinimalSize](../../aspose.slides/ibaseportionformateffectivedata/kerningminimalsize) { get; } | Gibt die minimale Schriftgröße zurück, bei der Kerning aktiviert werden soll. Nur-Lesen Single. |
| [Kumimoji](../../aspose.slides/ibaseportionformateffectivedata/kumimoji) { get; } | Bestimmt, ob Zahlen die sprachspezifische vertikale Textanordnung für östliche Sprachen ignorieren sollen. Nur-Lesen Boolean. |
| [LanguageId](../../aspose.slides/ibaseportionformateffectivedata/languageid) { get; } | Gibt die Id einer Sprache zurück. Nur-Lesen String. |
| [LatinFont](../../aspose.slides/ibaseportionformateffectivedata/latinfont) { get; } | Gibt die Informationen zur lateinischen Schriftart zurück. Nur-Lesen [`IFontData`](../ifontdata). |
| [LineFormat](../../aspose.slides/ibaseportionformateffectivedata/lineformat) { get; } | Gibt die LineFormat-Eigenschaften für die Textumrandung zurück. Nur-Lesen [`ILineFormatEffectiveData`](../ilineformateffectivedata). |
| [NormaliseHeight](../../aspose.slides/ibaseportionformateffectivedata/normaliseheight) { get; } | Bestimmt, ob die Höhe eines Textes normalisiert werden soll. Nur-Lesen Boolean. |
| [ProofDisabled](../../aspose.slides/ibaseportionformateffectivedata/proofdisabled) { get; } | Bestimmt, ob der Text nicht geprüft werden soll. Nur-Lesen Boolean. |
| [SmartTagClean](../../aspose.slides/ibaseportionformateffectivedata/smarttagclean) { get; } | Bestimmt, ob das SmartTag bereinigt werden soll. Nur-Lesen Boolean. |
| [Spacing](../../aspose.slides/ibaseportionformateffectivedata/spacing) { get; } | Gibt die Erhöhung des Zeichenabstands in Punkten zurück. Nur-Lesen Single. |
| [StrikethroughType](../../aspose.slides/ibaseportionformateffectivedata/strikethroughtype) { get; } | Gibt den Durchstreichungs-Typ eines Textes zurück. Nur-Lesen [`TextStrikethroughType`](../textstrikethroughtype). |
| [SymbolFont](../../aspose.slides/ibaseportionformateffectivedata/symbolfont) { get; } | Gibt die Informationen zur symbolischen Schriftart zurück. Nur-Lesen [`IFontData`](../ifontdata). |
| [TextCapType](../../aspose.slides/ibaseportionformateffectivedata/textcaptype) { get; } | Gibt die Art der Textschreibung zurück. Nur-Lesen [`TextCapType`](../textcaptype). |
| [UnderlineFillFormat](../../aspose.slides/ibaseportionformateffectivedata/underlinefillformat) { get; } | Gibt die FillFormat-Eigenschaften der Unterstreichungs-Linie zurück. Nur-Lesen [`IFillFormatEffectiveData`](../ifillformateffectivedata). |
| [UnderlineLineFormat](../../aspose.slides/ibaseportionformateffectivedata/underlinelineformat) { get; } | Gibt die LineFormat-Eigenschaften zurück, die zur Umrandung der Unterstreichungs-Linie verwendet werden. Nur-Lesen [`ILineFormatEffectiveData`](../ilineformateffectivedata). |

### Siehe auch

* Namensraum [Aspose.Slides](../../aspose.slides)
* Assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->