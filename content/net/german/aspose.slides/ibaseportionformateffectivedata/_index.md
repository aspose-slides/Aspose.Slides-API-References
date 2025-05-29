---
title: IBasePortionFormatEffectiveData
second_title: Aspose.Sildes für .NET API-Referenz
description: Basisinterface für unveränderliche Objekte, die effektive Formatierungseigenschaften für Textteile enthalten.
type: docs
weight: 5120
url: /de/aspose.slides/ibaseportionformateffectivedata/
---

## IBasePortionFormatEffectiveData-Schnittstelle

Basisinterface für unveränderliche Objekte, die effektive Formatierungseigenschaften für Textteile enthalten.

```csharp
public interface IBasePortionFormatEffectiveData
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [AlternativeLanguageId](../../aspose.slides/ibaseportionformateffectivedata/alternativelanguageid) { get; } | Gibt die Id einer alternativen Sprache zurück. Nur Lese-String. |
| [ComplexScriptFont](../../aspose.slides/ibaseportionformateffectivedata/complexscriptfont) { get; } | Gibt die Informationen zur komplexen Schriftart zurück. Nur Lese- [`IFontData`](../ifontdata). |
| [EastAsianFont](../../aspose.slides/ibaseportionformateffectivedata/eastasianfont) { get; } | Gibt die Informationen zur ostasiatischen Schriftart zurück. Nur Lese- [`IFontData`](../ifontdata). |
| [EffectFormat](../../aspose.slides/ibaseportionformateffectivedata/effectformat) { get; } | Gibt die Eigenschaften des Text-EffectFormat zurück. Nur Lese- [`IEffectFormatEffectiveData`](../ieffectformateffectivedata). |
| [Escapement](../../aspose.slides/ibaseportionformateffectivedata/escapement) { get; } | Gibt den Hoch- oder Tiefgestellt-Text zurück. Wert von -100% (Tiefgestellt) bis 100% (Hochgestellt). Nur Lese- Single. |
| [FillFormat](../../aspose.slides/ibaseportionformateffectivedata/fillformat) { get; } | Gibt die Eigenschaften des Text-FillFormat zurück. Nur Lese- [`IFillFormatEffectiveData`](../ifillformateffectivedata). |
| [FontBold](../../aspose.slides/ibaseportionformateffectivedata/fontbold) { get; } | Bestimmt, ob die Schriftart fett ist. Nur Lese- Boolean. |
| [FontHeight](../../aspose.slides/ibaseportionformateffectivedata/fontheight) { get; } | Gibt die Schriftart-Höhe eines Textteils zurück. Nur Lese- Single. |
| [FontItalic](../../aspose.slides/ibaseportionformateffectivedata/fontitalic) { get; } | Bestimmt, ob die Schriftart kursiv ist. Nur Lese- Boolean. |
| [FontUnderline](../../aspose.slides/ibaseportionformateffectivedata/fontunderline) { get; } | Gibt den Typ der Textunterstreichung zurück. Nur Lese- [`TextUnderlineType`](../textunderlinetype). |
| [HighlightColor](../../aspose.slides/ibaseportionformateffectivedata/highlightcolor) { get; } | Gibt die Farbe zurück, die verwendet wird, um einen Text hervorzuheben. Nur Lese- Color. |
| [IsHardUnderlineFill](../../aspose.slides/ibaseportionformateffectivedata/ishardunderlinefill) { get; } | Bestimmt, ob der Stil der Unterstreichung eigene FillFormat-Eigenschaften hat oder diese von den FillFormat-Eigenschaften des Textes erbt. Nur Lese- Boolean. |
| [IsHardUnderlineLine](../../aspose.slides/ibaseportionformateffectivedata/ishardunderlineline) { get; } | Bestimmt, ob der Stil der Unterstreichung eigene LineFormat-Eigenschaften hat oder diese von den LineFormat-Eigenschaften des Textes erbt. Nur Lese- Boolean. |
| [KerningMinimalSize](../../aspose.slides/ibaseportionformateffectivedata/kerningminimalsize) { get; } | Gibt die minimale Schriftgröße zurück, bei der Kerning aktiviert werden sollte. Nur Lese- Single. |
| [Kumimoji](../../aspose.slides/ibaseportionformateffectivedata/kumimoji) { get; } | Bestimmt, ob die Zahlen die vertikale Textanordnung spezifisch für ostasiatische Sprachen ignorieren sollten. Nur Lese- Boolean. |
| [LanguageId](../../aspose.slides/ibaseportionformateffectivedata/languageid) { get; } | Gibt die Id einer Sprache zurück. Nur Lese- String. |
| [LatinFont](../../aspose.slides/ibaseportionformateffectivedata/latinfont) { get; } | Gibt die Informationen zur lateinischen Schriftart zurück. Nur Lese- [`IFontData`](../ifontdata). |
| [LineFormat](../../aspose.slides/ibaseportionformateffectivedata/lineformat) { get; } | Gibt die LineFormat-Eigenschaften für Textumriss zurück. Nur Lese- [`ILineFormatEffectiveData`](../ilineformateffectivedata). |
| [NormaliseHeight](../../aspose.slides/ibaseportionformateffectivedata/normaliseheight) { get; } | Bestimmt, ob die Höhe eines Textes normalisiert werden sollte. Nur Lese- Boolean. |
| [ProofDisabled](../../aspose.slides/ibaseportionformateffectivedata/proofdisabled) { get; } | Bestimmt, ob der Text nicht überprüft werden sollte. Nur Lese- Boolean. |
| [SmartTagClean](../../aspose.slides/ibaseportionformateffectivedata/smarttagclean) { get; } | Bestimmt, ob der Smart Tag bereinigt werden sollte. Nur Lese- Boolean. |
| [Spacing](../../aspose.slides/ibaseportionformateffectivedata/spacing) { get; } | Gibt den Interzeichenabstand zurück. Nur Lese- Single. |
| [StrikethroughType](../../aspose.slides/ibaseportionformateffectivedata/strikethroughtype) { get; } | Gibt den Typ der Durchstreichung eines Textes zurück. Nur Lese- [`TextStrikethroughType`](../textstrikethroughtype). |
| [SymbolFont](../../aspose.slides/ibaseportionformateffectivedata/symbolfont) { get; } | Gibt die Informationen zur symbolischen Schriftart zurück. Nur Lese- [`IFontData`](../ifontdata). |
| [TextCapType](../../aspose.slides/ibaseportionformateffectivedata/textcaptype) { get; } | Gibt den Typ der Textgroßschreibung zurück. Nur Lese- [`TextCapType`](../textcaptype). |
| [UnderlineFillFormat](../../aspose.slides/ibaseportionformateffectivedata/underlinefillformat) { get; } | Gibt die FillFormat-Eigenschaften der unterstrichenen Linie zurück. Nur Lese- [`IFillFormatEffectiveData`](../ifillformateffectivedata). |
| [UnderlineLineFormat](../../aspose.slides/ibaseportionformateffectivedata/underlinelineformat) { get; } | Gibt die LineFormat-Eigenschaften zurück, die zur Umrisslinie der Unterstreichung verwendet werden. Nur Lese- [`ILineFormatEffectiveData`](../ilineformateffectivedata). |

### Siehe auch

* namespace [Aspose.Slides](../../aspose.slides)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->