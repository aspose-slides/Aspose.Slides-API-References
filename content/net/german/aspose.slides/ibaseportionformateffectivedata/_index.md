---
title: IBasePortionFormatEffectiveData
second_title: Aspose.Slides für .NET-API-Referenz
description: Basisschnittstelle für unveränderliche Objekte die effektive Textteilformatierungseigenschaften enthalten.
type: docs
weight: 4870
url: /de/aspose.slides/ibaseportionformateffectivedata/
---
## IBasePortionFormatEffectiveData interface

Basisschnittstelle für unveränderliche Objekte, die effektive Textteilformatierungseigenschaften enthalten.

```csharp
public interface IBasePortionFormatEffectiveData
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [AlternativeLanguageId](../../aspose.slides/ibaseportionformateffectivedata/alternativelanguageid) { get; } | Gibt die ID einer alternativen Sprache zurück. SchreibgeschütztString . |
| [ComplexScriptFont](../../aspose.slides/ibaseportionformateffectivedata/complexscriptfont) { get; } | Gibt die Schriftartinformationen für komplexe Skripte zurück. Schreibgeschützt[`IFontData`](../ifontdata) . |
| [EastAsianFont](../../aspose.slides/ibaseportionformateffectivedata/eastasianfont) { get; } | Gibt die Informationen zu ostasiatischen Schriftarten zurück. Schreibgeschützt[`IFontData`](../ifontdata) . |
| [EffectFormat](../../aspose.slides/ibaseportionformateffectivedata/effectformat) { get; } | Gibt die Eigenschaften des Texteffektformats zurück. Schreibgeschützt[`IEffectFormatEffectiveData`](../ieffectformateffectivedata) . |
| [Escapement](../../aspose.slides/ibaseportionformateffectivedata/escapement) { get; } | Gibt den hochgestellten oder tiefgestellten Text zurück. Wert von -100 % (tiefgestellt) bis 100 % (hochgestellt). SchreibgeschütztSingle . |
| [FillFormat](../../aspose.slides/ibaseportionformateffectivedata/fillformat) { get; } | Gibt die Text-FillFormat-Eigenschaften zurück. Schreibgeschützt[`IFillFormatEffectiveData`](../ifillformateffectivedata) . |
| [FontBold](../../aspose.slides/ibaseportionformateffectivedata/fontbold) { get; } | Legt fest, ob die Schriftart fett ist. SchreibgeschütztBoolean . |
| [FontHeight](../../aspose.slides/ibaseportionformateffectivedata/fontheight) { get; } | Gibt die Schrifthöhe eines Teils zurück. SchreibgeschütztSingle . |
| [FontItalic](../../aspose.slides/ibaseportionformateffectivedata/fontitalic) { get; } | Legt fest, ob die Schriftart kursiv ist. SchreibgeschütztBoolean . |
| [FontUnderline](../../aspose.slides/ibaseportionformateffectivedata/fontunderline) { get; } | Gibt den Typ der Textunterstreichung zurück. Schreibgeschützt[`TextUnderlineType`](../textunderlinetype) . |
| [HighlightColor](../../aspose.slides/ibaseportionformateffectivedata/highlightcolor) { get; } | Gibt die Farbe zurück, die verwendet wird, um einen Text hervorzuheben. SchreibgeschütztColor . |
| [IsHardUnderlineFill](../../aspose.slides/ibaseportionformateffectivedata/ishardunderlinefill) { get; } | Legt fest, ob der Unterstreichungsstil eigene FillFormat-Eigenschaften hat oder von den FillFormat-Eigenschaften des Textes erbt. SchreibgeschütztBoolean . |
| [IsHardUnderlineLine](../../aspose.slides/ibaseportionformateffectivedata/ishardunderlineline) { get; } | Legt fest, ob der Unterstreichungsstil eigene LineFormat-Eigenschaften hat oder von den LineFormat-Eigenschaften des Textes erbt. SchreibgeschütztBoolean . |
| [KerningMinimalSize](../../aspose.slides/ibaseportionformateffectivedata/kerningminimalsize) { get; } | Gibt die minimale Schriftgröße zurück, für die Kerning eingeschaltet werden soll. Read-onlySingle . |
| [Kumimoji](../../aspose.slides/ibaseportionformateffectivedata/kumimoji) { get; } | Legt fest, ob die Zahlen Text ignorieren sollen. Das vertikale Textlayout ist spezifisch für die östliche Sprache. SchreibgeschütztBoolean . |
| [LanguageId](../../aspose.slides/ibaseportionformateffectivedata/languageid) { get; } | Gibt die ID einer Sprache zurück. SchreibgeschütztString . |
| [LatinFont](../../aspose.slides/ibaseportionformateffectivedata/latinfont) { get; } | Gibt die lateinische Schriftartinfo zurück. Schreibgeschützt[`IFontData`](../ifontdata) . |
| [LineFormat](../../aspose.slides/ibaseportionformateffectivedata/lineformat) { get; } | Gibt die LineFormat-Eigenschaften für die Textgliederung zurück. Schreibgeschützt[`ILineFormatEffectiveData`](../ilineformateffectivedata) . |
| [NormaliseHeight](../../aspose.slides/ibaseportionformateffectivedata/normaliseheight) { get; } | Legt fest, ob die Höhe eines Textes normalisiert werden soll. Read-onlyBoolean . |
| [ProofDisabled](../../aspose.slides/ibaseportionformateffectivedata/proofdisabled) { get; } | Legt fest, ob der Text nicht geprüft werden soll. SchreibgeschütztBoolean . |
| [SmartTagClean](../../aspose.slides/ibaseportionformateffectivedata/smarttagclean) { get; } | Legt fest, ob das Smarttag bereinigt werden soll. SchreibgeschütztBoolean . |
| [Spacing](../../aspose.slides/ibaseportionformateffectivedata/spacing) { get; } | Gibt den Abstand zwischen den Zeichen zurück. SchreibgeschütztSingle . |
| [StrikethroughType](../../aspose.slides/ibaseportionformateffectivedata/strikethroughtype) { get; } | Gibt den durchgestrichenen Typ eines Textes zurück. Schreibgeschützt[`TextStrikethroughType`](../textstrikethroughtype) . |
| [SymbolFont](../../aspose.slides/ibaseportionformateffectivedata/symbolfont) { get; } | Gibt die Symbolschriftinfo zurück. Schreibgeschützt[`IFontData`](../ifontdata) . |
| [TextCapType](../../aspose.slides/ibaseportionformateffectivedata/textcaptype) { get; } | Gibt die Art der Textgroßschreibung zurück. Schreibgeschützt[`TextCapType`](../textcaptype) . |
| [UnderlineFillFormat](../../aspose.slides/ibaseportionformateffectivedata/underlinefillformat) { get; } | Gibt die FillFormat-Eigenschaften der Unterstreichungslinie zurück. Schreibgeschützt[`IFillFormatEffectiveData`](../ifillformateffectivedata) . |
| [UnderlineLineFormat](../../aspose.slides/ibaseportionformateffectivedata/underlinelineformat) { get; } | Gibt die LineFormat-Eigenschaften zurück, die zum Umreißen der Unterstreichungslinie verwendet werden. Schreibgeschützt[`ILineFormatEffectiveData`](../ilineformateffectivedata) . |

### Siehe auch

* namensraum [Aspose.Slides](../../aspose.slides)
* Montage [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
