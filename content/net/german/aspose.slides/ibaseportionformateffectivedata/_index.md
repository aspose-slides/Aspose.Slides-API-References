---
title: IBasePortionFormatEffectiveData
second_title: Aspose.Slides für .NET API-Referenz
description: Basisinterface für unveränderliche Objekte, die effektive Eigenschaften der Textformatierung enthalten.
type: docs
weight: 5120
url: /de/aspose.slides/ibaseportionformateffectivedata/
---

## IBasePortionFormatEffectiveData-Interface

Basisinterface für unveränderliche Objekte, die effektive Eigenschaften der Textformatierung enthalten.

```csharp
public interface IBasePortionFormatEffectiveData
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [AlternativeLanguageId](../../aspose.slides/ibaseportionformateffectivedata/alternativelanguageid) { get; } | Gibt die ID einer alternativen Sprache zurück. Nur lesbarer String. |
| [ComplexScriptFont](../../aspose.slides/ibaseportionformateffectivedata/complexscriptfont) { get; } | Gibt die Informationen zur Schriftart für komplexe Schriftzeichen zurück. Nur lesbar [`IFontData`](../ifontdata). |
| [EastAsianFont](../../aspose.slides/ibaseportionformateffectivedata/eastasianfont) { get; } | Gibt die Informationen zur ostasiatischen Schriftart zurück. Nur lesbar [`IFontData`](../ifontdata). |
| [EffectFormat](../../aspose.slides/ibaseportionformateffectivedata/effectformat) { get; } | Gibt die Eigenschaften des textuellen EffectFormat zurück. Nur lesbar [`IEffectFormatEffectiveData`](../ieffectformateffectivedata). |
| [Escapement](../../aspose.slides/ibaseportionformateffectivedata/escapement) { get; } | Gibt den Hoch- oder Tiefgestellt-Text zurück. Wert von -100 % (tiefgestellt) bis 100 % (hochgestellt). Nur lesbar Single. |
| [FillFormat](../../aspose.slides/ibaseportionformateffectivedata/fillformat) { get; } | Gibt die Eigenschaften des textlichen FillFormat zurück. Nur lesbar [`IFillFormatEffectiveData`](../ifillformateffectivedata). |
| [FontBold](../../aspose.slides/ibaseportionformateffectivedata/fontbold) { get; } | Bestimmt, ob die Schriftart fett ist. Nur lesbar Boolean. |
| [FontHeight](../../aspose.slides/ibaseportionformateffectivedata/fontheight) { get; } | Gibt die Schriftgröße eines Abschnitts zurück. Nur lesbar Single. |
| [FontItalic](../../aspose.slides/ibaseportionformateffectivedata/fontitalic) { get; } | Bestimmt, ob die Schriftart kursiv ist. Nur lesbar Boolean. |
| [FontUnderline](../../aspose.slides/ibaseportionformateffectivedata/fontunderline) { get; } | Gibt den Typ der Textunterstreichung zurück. Nur lesbar [`TextUnderlineType`](../textunderlinetype). |
| [HighlightColor](../../aspose.slides/ibaseportionformateffectivedata/highlightcolor) { get; } | Gibt die Farbe zurück, die verwendet wird, um einen Text hervorzuheben. Nur lesbar Color. |
| [IsHardUnderlineFill](../../aspose.slides/ibaseportionformateffectivedata/ishardunderlinefill) { get; } | Bestimmt, ob der Unterstreichungsstil eigene FillFormat-Eigenschaften hat oder diese von den FillFormat-Eigenschaften des Textes erbt. Nur lesbar Boolean. |
| [IsHardUnderlineLine](../../aspose.slides/ibaseportionformateffectivedata/ishardunderlineline) { get; } | Bestimmt, ob der Unterstreichungsstil eigene LineFormat-Eigenschaften hat oder diese von den LineFormat-Eigenschaften des Textes erbt. Nur lesbar Boolean. |
| [KerningMinimalSize](../../aspose.slides/ibaseportionformateffectivedata/kerningminimalsize) { get; } | Gibt die minimale Schriftgröße zurück, bei der das Kerning aktiviert werden sollte. Nur lesbar Single. |
| [Kumimoji](../../aspose.slides/ibaseportionformateffectivedata/kumimoji) { get; } | Bestimmt, ob die Zahlen das sprachspezifische vertikale Layout von Text der östlichen Sprache ignorieren sollen. Nur lesbar Boolean. |
| [LanguageId](../../aspose.slides/ibaseportionformateffectivedata/languageid) { get; } | Gibt die ID einer Sprache zurück. Nur lesbarer String. |
| [LatinFont](../../aspose.slides/ibaseportionformateffectivedata/latinfont) { get; } | Gibt die Informationen zur lateinischen Schriftart zurück. Nur lesbar [`IFontData`](../ifontdata). |
| [LineFormat](../../aspose.slides/ibaseportionformateffectivedata/lineformat) { get; } | Gibt die LineFormat-Eigenschaften für die Umrisszeichnung des Textes zurück. Nur lesbar [`ILineFormatEffectiveData`](../ilineformateffectivedata). |
| [NormaliseHeight](../../aspose.slides/ibaseportionformateffectivedata/normaliseheight) { get; } | Bestimmt, ob die Höhe eines Textes normalisiert werden soll. Nur lesbar Boolean. |
| [ProofDisabled](../../aspose.slides/ibaseportionformateffectivedata/proofdisabled) { get; } | Bestimmt, ob der Text nicht geprüft werden sollte. Nur lesbar Boolean. |
| [SmartTagClean](../../aspose.slides/ibaseportionformateffectivedata/smarttagclean) { get; } | Bestimmt, ob der Smart Tag bereinigt werden soll. Nur lesbar Boolean. |
| [Spacing](../../aspose.slides/ibaseportionformateffectivedata/spacing) { get; } | Gibt den Abstand zwischen Zeichen zurück. Nur lesbar Single. |
| [StrikethroughType](../../aspose.slides/ibaseportionformateffectivedata/strikethroughtype) { get; } | Gibt den Typ der Durchstreichung eines Textes zurück. Nur lesbar [`TextStrikethroughType`](../textstrikethroughtype). |
| [SymbolFont](../../aspose.slides/ibaseportionformateffectivedata/symbolfont) { get; } | Gibt die Informationen zur symbolischen Schriftart zurück. Nur lesbar [`IFontData`](../ifontdata). |
| [TextCapType](../../aspose.slides/ibaseportionformateffectivedata/textcaptype) { get; } | Gibt den Typ der Textgroßschreibung zurück. Nur lesbar [`TextCapType`](../textcaptype). |
| [UnderlineFillFormat](../../aspose.slides/ibaseportionformateffectivedata/underlinefillformat) { get; } | Gibt die Eigenschaften des FillFormat der Unterstreichungslinie zurück. Nur lesbar [`IFillFormatEffectiveData`](../ifillformateffectivedata). |
| [UnderlineLineFormat](../../aspose.slides/ibaseportionformateffectivedata/underlinelineformat) { get; } | Gibt die LineFormat-Eigenschaften zurück, die verwendet werden, um die Unterstreichungslinie zu umreißen. Nur lesbar [`ILineFormatEffectiveData`](../ilineformateffectivedata). |

### Siehe auch

* Namespace [Aspose.Slides](../../aspose.slides)
* Assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->