---
title: IBasePortionFormatEffectiveData
second_title: Aspose.Sildes .NET API-referencia
description: Alap interfész azoknak a módosíthatatlan objektumoknak, amelyek hatékony szövegrész formázási tulajdonságokat tartalmaznak.
type: docs
weight: 5340
url: /hu/aspose.slides/ibaseportionformateffectivedata/
---
## IBasePortionFormatEffectiveData interfész

Base interface for immutable objects which contain effective text portion formatting properties.

```csharp
public interface IBasePortionFormatEffectiveData
```

## Tulajdonságok

| Név | Leírás |
| --- | --- |
| [AlternativeLanguageId](../../aspose.slides/ibaseportionformateffectivedata/alternativelanguageid) { get; } | Visszaadja egy alternatív nyelv azonosítóját. Csak olvasható String. |
| [ComplexScriptFont](../../aspose.slides/ibaseportionformateffectivedata/complexscriptfont) { get; } | Visszaadja a komplex írásrendszer betűtípusinformációját. Csak olvasható [`IFontData`](../ifontdata). |
| [EastAsianFont](../../aspose.slides/ibaseportionformateffectivedata/eastasianfont) { get; } | Visszaadja az kelet-ázsiai betűtípusinformációt. Csak olvasható [`IFontData`](../ifontdata). |
| [EffectFormat](../../aspose.slides/ibaseportionformateffectivedata/effectformat) { get; } | Visszaadja a szöveg EffectFormat tulajdonságait. Csak olvasható [`IEffectFormatEffectiveData`](../ieffectformateffectivedata). |
| [Escapement](../../aspose.slides/ibaseportionformateffectivedata/escapement) { get; } | Visszaadja a felső- vagy alsóindex szöveget. Érték -100 % (alsóindex) és 100 % (felsőindex) között. Csak olvasható Single. |
| [FillFormat](../../aspose.slides/ibaseportionformateffectivedata/fillformat) { get; } | Visszaadja a szöveg FillFormat tulajdonságait. Csak olvasható [`IFillFormatEffectiveData`](../ifillformateffectivedata). |
| [FontBold](../../aspose.slides/ibaseportionformateffectivedata/fontbold) { get; } | Megállapítja, hogy a betűtípus félkövér-e. Csak olvasható Boolean. |
| [FontHeight](../../aspose.slides/ibaseportionformateffectivedata/fontheight) { get; } | Visszaadja a szövegrész betűmagasságát pontban. Csak olvasható Single. |
| [FontItalic](../../aspose.slides/ibaseportionformateffectivedata/fontitalic) { get; } | Megállapítja, hogy a betűtípus dőlt-e. Csak olvasható Boolean. |
| [FontUnderline](../../aspose.slides/ibaseportionformateffectivedata/fontunderline) { get; } | Visszaadja a szöveg aláhúzás típusát. Csak olvasható [`TextUnderlineType`](../textunderlinetype). |
| [HighlightColor](../../aspose.slides/ibaseportionformateffectivedata/highlightcolor) { get; } | Visszaadja a szöveg kiemeléséhez használt színt. Csak olvasható Color. |
| [IsHardUnderlineFill](../../aspose.slides/ibaseportionformateffectivedata/ishardunderlinefill) { get; } | Megállapítja, hogy az aláhúzás stílusának saját FillFormat tulajdonságai vannak-e, vagy örökli a szöveg FillFormat tulajdonságait. Csak olvasható Boolean. |
| [IsHardUnderlineLine](../../aspose.slides/ibaseportionformateffectivedata/ishardunderlineline) { get; } | Megállapítja, hogy az aláhúzás stílusának saját LineFormat tulajdonságai vannak-e, vagy örökli a szöveg LineFormat tulajdonságait. Csak olvasható Boolean. |
| [KerningMinimalSize](../../aspose.slides/ibaseportionformateffectivedata/kerningminimalsize) { get; } | Visszaadja a minimális betűméretet, amelynél a kötésnek be kell kapcsolódnia. Csak olvasható Single. |
| [Kumimoji](../../aspose.slides/ibaseportionformateffectivedata/kumimoji) { get; } | Megállapítja, hogy a számok figyelmen kívül hagyják-e a szöveg kelet-ázsiai nyelvspecifikus függőleges elrendezését. Csak olvasható Boolean. |
| [LanguageId](../../aspose.slides/ibaseportionformateffectivedata/languageid) { get; } | Visszaadja egy nyelv azonosítóját. Csak olvasható String. |
| [LatinFont](../../aspose.slides/ibaseportionformateffectivedata/latinfont) { get; } | Visszaadja a latin betűtípus információt. Csak olvasható [`IFontData`](../ifontdata). |
| [LineFormat](../../aspose.slides/ibaseportionformateffectivedata/lineformat) { get; } | Visszaadja a szöveg körvonalazásához tartozó LineFormat tulajdonságokat. Csak olvasható [`ILineFormatEffectiveData`](../ilineformateffectivedata). |
| [NormaliseHeight](../../aspose.slides/ibaseportionformateffectivedata/normaliseheight) { get; } | Megállapítja, hogy a szöveg magasságát normalizálni kell-e. Csak olvasható Boolean. |
| [ProofDisabled](../../aspose.slides/ibaseportionformateffectivedata/proofdisabled) { get; } | Megállapítja, hogy a szöveget ne kell-e ellenőrizni. Csak olvasható Boolean. |
| [SmartTagClean](../../aspose.slides/ibaseportionformateffectivedata/smarttagclean) { get; } | Megállapítja, hogy az intelligens címke törlésre kerüljön-e. Csak olvasható Boolean. |
| [Spacing](../../aspose.slides/ibaseportionformateffectivedata/spacing) { get; } | Visszaadja a karakterek közti távolság növekményét pontban. Csak olvasható Single. |
| [StrikethroughType](../../aspose.slides/ibaseportionformateffectivedata/strikethroughtype) { get; } | Visszaadja a szöveg áthúzás típusát. Csak olvasható [`TextStrikethroughType`](../textstrikethroughtype). |
| [SymbolFont](../../aspose.slides/ibaseportionformateffectivedata/symbolfont) { get; } | Visszaadja a szimbolikus betűtípus információt. Csak olvasható [`IFontData`](../ifontdata). |
| [TextCapType](../../aspose.slides/ibaseportionformateffectivedata/textcaptype) { get; } | Visszaadja a szöveg nagybetűsítési típusát. Csak olvasható [`TextCapType`](../textcaptype). |
| [UnderlineFillFormat](../../aspose.slides/ibaseportionformateffectivedata/underlinefillformat) { get; } | Visszaadja az aláhúzási vonal FillFormat tulajdonságait. Csak olvasható [`IFillFormatEffectiveData`](../ifillformateffectivedata). |
| [UnderlineLineFormat](../../aspose.slides/ibaseportionformateffectivedata/underlinelineformat) { get; } | Visszaadja az aláhúzási vonal körvonalazásához használt LineFormat tulajdonságokat. Csak olvasható [`ILineFormatEffectiveData`](../ilineformateffectivedata). |

### Lásd még

* névtér [Aspose.Slides](../../aspose.slides)
* összeállítás [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->