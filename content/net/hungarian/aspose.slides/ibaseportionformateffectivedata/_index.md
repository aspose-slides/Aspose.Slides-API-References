---
title: IBasePortionFormatEffectiveData
second_title: Aspose.Sildes .NET API referencia
description: Alap interfész a változtathatatlan objektumokhoz, amelyek hatékony szövegrész formázási tulajdonságokat tartalmaznak.
type: docs
weight: 5300
url: /hu/aspose.slides/ibaseportionformateffectivedata/
---
## IBasePortionFormatEffectiveData interfész

Alap interfész a változatlan objektumokhoz, amelyek hatékony szövegrész formázási tulajdonságokat tartalmaznak.

```csharp
public interface IBasePortionFormatEffectiveData
```

## Tulajdonságok

| Név | Leírás |
| --- | --- |
| [AlternativeLanguageId](../../aspose.slides/ibaseportionformateffectivedata/alternativelanguageid) { get; } | Visszaadja egy alternatív nyelv azonosítóját. Csak olvasható String. |
| [ComplexScriptFont](../../aspose.slides/ibaseportionformateffectivedata/complexscriptfont) { get; } | Visszaadja a komplex írásrendszer betűtípus információját. Csak olvasható [`IFontData`](../ifontdata). |
| [EastAsianFont](../../aspose.slides/ibaseportionformateffectivedata/eastasianfont) { get; } | Visszaadja a Kelet-ázsiai betűtípus információt. Csak olvasható [`IFontData`](../ifontdata). |
| [EffectFormat](../../aspose.slides/ibaseportionformateffectivedata/effectformat) { get; } | Visszaadja a szöveg EffectFormat tulajdonságait. Csak olvasható [`IEffectFormatEffectiveData`](../ieffectformateffectivedata). |
| [Escapement](../../aspose.slides/ibaseportionformateffectivedata/escapement) { get; } | Visszaadja a felső vagy alsó indexű szöveget. Érték -100% (alsó index) és 100% (felső index) között. Csak olvasható Single. |
| [FillFormat](../../aspose.slides/ibaseportionformateffectivedata/fillformat) { get; } | Visszaadja a szöveg FillFormat tulajdonságait. Csak olvasható [`IFillFormatEffectiveData`](../ifillformateffectivedata). |
| [FontBold](../../aspose.slides/ibaseportionformateffectivedata/fontbold) { get; } | Megállapítja, hogy a betűtipus félkövér-e. Csak olvasható Boolean. |
| [FontHeight](../../aspose.slides/ibaseportionformateffectivedata/fontheight) { get; } | Visszaadja a szövegrész betűmagasságát pontban. Csak olvasható Single. |
| [FontItalic](../../aspose.slides/ibaseportionformateffectivedata/fontitalic) { get; } | Megállapítja, hogy a betűtipus dőlt-e. Csak olvasható Boolean. |
| [FontUnderline](../../aspose.slides/ibaseportionformateffectivedata/fontunderline) { get; } | Visszaadja a szöveg aláhúzás típusát. Csak olvasható [`TextUnderlineType`](../textunderlinetype). |
| [HighlightColor](../../aspose.slides/ibaseportionformateffectivedata/highlightcolor) { get; } | Visszaadja a szöveg kiemeléséhez használt színt. Csak olvasható Color. |
| [IsHardUnderlineFill](../../aspose.slides/ibaseportionformateffectivedata/ishardunderlinefill) { get; } | Megállapítja, hogy az aláhúzási stílus rendelkezik saját FillFormat tulajdonságokkal, vagy örökli azokat a szöveg FillFormat tulajdonságaiból. Csak olvasható Boolean. |
| [IsHardUnderlineLine](../../aspose.slides/ibaseportionformateffectivedata/ishardunderlineline) { get; } | Megállapítja, hogy az aláhúzási stílus rendelkezik saját LineFormat tulajdonságokkal, vagy örökli azokat a szöveg LineFormat tulajdonságaiból. Csak olvasható Boolean. |
| [KerningMinimalSize](../../aspose.slides/ibaseportionformateffectivedata/kerningminimalsize) { get; } | Visszaadja a minimális betűméretet, amelynél a kerningnek be kell kapcsolódnia. Csak olvasható Single. |
| [Kumimoji](../../aspose.slides/ibaseportionformateffectivedata/kumimoji) { get; } | Megállapítja, hogy a számok figyelmen kívül hagyják-e a szöveg keleti nyelvspecifikus függőleges elrendezését. Csak olvasható Boolean. |
| [LanguageId](../../aspose.slides/ibaseportionformateffectivedata/languageid) { get; } | Visszaadja egy nyelv azonosítóját. Csak olvasható String. |
| [LatinFont](../../aspose.slides/ibaseportionformateffectivedata/latinfont) { get; } | Visszaadja a latin betűtípus információt. Csak olvasható [`IFontData`](../ifontdata). |
| [LineFormat](../../aspose.slides/ibaseportionformateffectivedata/lineformat) { get; } | Visszaadja a szöveg körvonalazásához szükséges LineFormat tulajdonságokat. Csak olvasható [`ILineFormatEffectiveData`](../ilineformateffectivedata). |
| [NormaliseHeight](../../aspose.slides/ibaseportionformateffectivedata/normaliseheight) { get; } | Megállapítja, hogy a szöveg magassága normalizálva legyen-e. Csak olvasható Boolean. |
| [ProofDisabled](../../aspose.slides/ibaseportionformateffectivedata/proofdisabled) { get; } | Megállapítja, hogy a szöveget ne kelljen lektorálni. Csak olvasható Boolean. |
| [SmartTagClean](../../aspose.slides/ibaseportionformateffectivedata/smarttagclean) { get; } | Megállapítja, hogy az okos címke legyen-e megtisztítva. Csak olvasható Boolean. |
| [Spacing](../../aspose.slides/ibaseportionformateffectivedata/spacing) { get; } | Visszaadja a karakterek közötti távolság növekményét pontban. Csak olvasható Single. |
| [StrikethroughType](../../aspose.slides/ibaseportionformateffectivedata/strikethroughtype) { get; } | Visszaadja a szöveg áthúzási típusát. Csak olvasható [`TextStrikethroughType`](../textstrikethroughtype). |
| [SymbolFont](../../aspose.slides/ibaseportionformateffectivedata/symbolfont) { get; } | Visszaadja a szimbolikus betűtípus információt. Csak olvasható [`IFontData`](../ifontdata). |
| [TextCapType](../../aspose.slides/ibaseportionformateffectivedata/textcaptype) { get; } | Visszaadja a szöveg nagybetűs írás típusát. Csak olvasható [`TextCapType`](../textcaptype). |
| [UnderlineFillFormat](../../aspose.slides/ibaseportionformateffectivedata/underlinefillformat) { get; } | Visszaadja az aláhúzási vonal FillFormat tulajdonságait. Csak olvasható [`IFillFormatEffectiveData`](../ifillformateffectivedata). |
| [UnderlineLineFormat](../../aspose.slides/ibaseportionformateffectivedata/underlinelineformat) { get; } | Visszaadja az aláhúzási vonal körvonalazásához használt LineFormat tulajdonságokat. Csak olvasható [`ILineFormatEffectiveData`](../ilineformateffectivedata). |

### Lásd még

* névtér [Aspose.Slides](../../aspose.slides)
* összeállítás [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->