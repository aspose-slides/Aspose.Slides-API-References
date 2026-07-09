---
title: IBasePortionFormatEffectiveData
second_title: Aspose.Sildes a .NET API referenciája
description: Alap interfész a hatékony szövegrész formázási tulajdonságokat tartalmazó immutable objektumok számára.
type: docs
weight: 5320
url: /hu/aspose.slides/ibaseportionformateffectivedata/
---
## IBasePortionFormatEffectiveData interfész

Az immutable objektumok alap interfésze, amelyek hatékony szövegrész formázási tulajdonságokat tartalmaznak.

```csharp
public interface IBasePortionFormatEffectiveData
```

## Tulajdonságok

| Név | Leírás |
| --- | --- |
| [AlternativeLanguageId](../../aspose.slides/ibaseportionformateffectivedata/alternativelanguageid) { get; } | Visszaadja a helyettesítő nyelv Id-értékét. Csak olvasható String. |
| [ComplexScriptFont](../../aspose.slides/ibaseportionformateffectivedata/complexscriptfont) { get; } | Visszaadja a komplex írásrendszer betűtípus információit. Csak olvasható [`IFontData`](../ifontdata). |
| [EastAsianFont](../../aspose.slides/ibaseportionformateffectivedata/eastasianfont) { get; } | Visszaadja az kelet-ázsiai betűtípus információkat. Csak olvasható [`IFontData`](../ifontdata). |
| [EffectFormat](../../aspose.slides/ibaseportionformateffectivedata/effectformat) { get; } | Visszaadja a szöveg EffectFormat tulajdonságait. Csak olvasható [`IEffectFormatEffectiveData`](../ieffectformateffectivedata). |
| [Escapement](../../aspose.slides/ibaseportionformateffectivedata/escapement) { get; } | Visszaadja a felső vagy alsó indexű szöveget. Érték -100% (alsó index) és 100% (felső index) között. Csak olvasható Single. |
| [FillFormat](../../aspose.slides/ibaseportionformateffectivedata/fillformat) { get; } | Visszaadja a szöveg FillFormat tulajdonságait. Csak olvasható [`IFillFormatEffectiveData`](../ifillformateffectivedata). |
| [FontBold](../../aspose.slides/ibaseportionformateffectivedata/fontbold) { get; } | Megállapítja, hogy a betűtípus félkövér-e. Csak olvasható Boolean. |
| [FontHeight](../../aspose.slides/ibaseportionformateffectivedata/fontheight) { get; } | Visszaadja a szövegrész betűméretét pontban. Csak olvasható Single. |
| [FontItalic](../../aspose.slides/ibaseportionformateffectivedata/fontitalic) { get; } | Megállapítja, hogy a betűtípus dőlt-e. Csak olvasható Boolean. |
| [FontUnderline](../../aspose.slides/ibaseportionformateffectivedata/fontunderline) { get; } | Visszaadja a szöveg aláhúzás típusát. Csak olvasható [`TextUnderlineType`](../textunderlinetype). |
| [HighlightColor](../../aspose.slides/ibaseportionformateffectivedata/highlightcolor) { get; } | Visszaadja a szöveg kiemeléséhez használt színt. Csak olvasható Color. |
| [IsHardUnderlineFill](../../aspose.slides/ibaseportionformateffectivedata/ishardunderlinefill) { get; } | Megállapítja, hogy az aláhúzási stílus saját FillFormat tulajdonságokkal rendelkezik-e, vagy örökli a szöveg FillFormat tulajdonságait. Csak olvasható Boolean. |
| [IsHardUnderlineLine](../../aspose.slides/ibaseportionformateffectivedata/ishardunderlineline) { get; } | Megállapítja, hogy az aláhúzási stílus saját LineFormat tulajdonságokkal rendelkezik-e, vagy örökli a szöveg LineFormat tulajdonságait. Csak olvasható Boolean. |
| [KerningMinimalSize](../../aspose.slides/ibaseportionformateffectivedata/kerningminimalsize) { get; } | Visszaadja a legkisebb betűméretet, amelynél a kerning bekapcsolandó. Csak olvasható Single. |
| [Kumimoji](../../aspose.slides/ibaseportionformateffectivedata/kumimoji) { get; } | Megállapítja, hogy a számok figyelmen kívül hagyják-e a szöveg kelet-ázsiai nyelvspecifikus függőleges elrendezését. Csak olvasható Boolean. |
| [LanguageId](../../aspose.slides/ibaseportionformateffectivedata/languageid) { get; } | Visszaadja egy nyelv Id-értékét. Csak olvasható String. |
| [LatinFont](../../aspose.slides/ibaseportionformateffectivedata/latinfont) { get; } | Visszaadja a latin betűtípus információkat. Csak olvasható [`IFontData`](../ifontdata). |
| [LineFormat](../../aspose.slides/ibaseportionformateffectivedata/lineformat) { get; } | Visszaadja a szöveg körvonalazáshoz szükséges LineFormat tulajdonságokat. Csak olvasható [`ILineFormatEffectiveData`](../ilineformateffectivedata). |
| [NormaliseHeight](../../aspose.slides/ibaseportionformateffectivedata/normaliseheight) { get; } | Megállapítja, hogy a szöveg magassága normalizálva legyen-e. Csak olvasható Boolean. |
| [ProofDisabled](../../aspose.slides/ibaseportionformateffectivedata/proofdisabled) { get; } | Megállapítja, hogy a szöveget ne ellenőrizze-e helyesírási szempontból. Csak olvasható Boolean. |
| [SmartTagClean](../../aspose.slides/ibaseportionformateffectivedata/smarttagclean) { get; } | Megállapítja, hogy az intelligens címke legyen-e megtisztítva. Csak olvasható Boolean. |
| [Spacing](../../aspose.slides/ibaseportionformateffectivedata/spacing) { get; } | Visszaadja a karakterek közötti távolság növekedését pontban. Csak olvasható Single. |
| [StrikethroughType](../../aspose.slides/ibaseportionformateffectivedata/strikethroughtype) { get; } | Visszaadja a szöveg áthúzás típusát. Csak olvasható [`TextStrikethroughType`](../textstrikethroughtype). |
| [SymbolFont](../../aspose.slides/ibaseportionformateffectivedata/symbolfont) { get; } | Visszaadja a szimbolikus betűtípus információkat. Csak olvasható [`IFontData`](../ifontdata). |
| [TextCapType](../../aspose.slides/ibaseportionformateffectivedata/textcaptype) { get; } | Visszaadja a szöveg nagybetűsítés típusát. Csak olvasható [`TextCapType`](../textcaptype). |
| [UnderlineFillFormat](../../aspose.slides/ibaseportionformateffectivedata/underlinefillformat) { get; } | Visszaadja az aláhúzási vonal FillFormat tulajdonságait. Csak olvasható [`IFillFormatEffectiveData`](../ifillformateffectivedata). |
| [UnderlineLineFormat](../../aspose.slides/ibaseportionformateffectivedata/underlinelineformat) { get; } | Visszaadja a vonalat körvonalazó LineFormat tulajdonságokat. Csak olvasható [`ILineFormatEffectiveData`](../ilineformateffectivedata). |

### Kapcsolódó

* névtér [Aspose.Slides](../../aspose.slides)
* összeállítás [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->