---
title: BasePortionFormat
second_title: Aspose.Sildes .NET API hivatkozás
description: Általános szövegrész formázási tulajdonságok.
type: docs
weight: 950
url: /hu/aspose.slides/baseportionformat/
---
## BasePortionFormat osztály

Közös szövegrész formázási tulajdonságok.

```csharp
public abstract class BasePortionFormat : PVIObject, IBasePortionFormat
```

## Tulajdonságok

| Név | Leírás |
| --- | --- |
| [AlternativeLanguageId](../../aspose.slides/baseportionformat/alternativelanguageid) { get; set; } | Visszaadja vagy beállítja egy alternatív nyelv azonosítóját. Olvasás/írás String. |
| [AsIPresentationComponent](../../aspose.slides/pviobject/asipresentationcomponent) { get; } | Lehetővé teszi a base IPresentationComponent interfész lekérését. Csak olvasható [`IPresentationComponent`](../ipresentationcomponent). |
| [ComplexScriptFont](../../aspose.slides/baseportionformat/complexscriptfont) { get; set; } | Visszaadja vagy beállítja a komplex írásrendszer betűtípus információt. A Null azt jelenti, hogy a betűtípus nincs definiálva, és a Mesterből kell örökölni. Olvasás/írás [`IFontData`](../ifontdata). |
| [EastAsianFont](../../aspose.slides/baseportionformat/eastasianfont) { get; set; } | Visszaadja vagy beállítja a kelet-ázsiai betűtípus információt. A Null azt jelenti, hogy a betűtípus nincs definiálva, és a Mesterből kell örökölni. Olvasás/írás [`IFontData`](../ifontdata). |
| [EffectFormat](../../aspose.slides/baseportionformat/effectformat) { get; } | Visszaadja a szöveg EffectFormat tulajdonságait. Nem alkalmazott öröklődés. Csak olvasható [`IEffectFormat`](../ieffectformat). |
| [Escapement](../../aspose.slides/baseportionformat/escapement) { get; set; } | Visszaadja vagy beállítja a felső- vagy alsóindex szöveget. Az érték -100% (alsóindex) és 100% (felsőindex) között van. **float.NaN** azt jelenti, hogy az érték nincs definiálva, és a Mesterből kell örökölni. Olvasás/írás Single. |
| [FillFormat](../../aspose.slides/baseportionformat/fillformat) { get; } | Visszaadja a szöveg FillFormat tulajdonságait. Nem alkalmazott öröklődés. Csak olvasható [`IFillFormat`](../ifillformat). |
| [FontBold](../../aspose.slides/baseportionformat/fontbold) { get; set; } | Megadja, hogy a betűtípus félkövér-e. Nem alkalmazott öröklődés. Olvasás/írás [`NullableBool`](../nullablebool). |
| [FontHeight](../../aspose.slides/baseportionformat/fontheight) { get; set; } | Visszaadja vagy beállítja egy rész betűmagasságát. **float.NaN** azt jelenti, hogy a magasság nincs definiálva, és a Mesterből kell örökölni. Olvasás/írás Single. |
| [FontItalic](../../aspose.slides/baseportionformat/fontitalic) { get; set; } | Megadja, hogy a betű dőlt-e. Nem alkalmazott öröklődés. Olvasás/írás [`NullableBool`](../nullablebool). |
| [FontUnderline](../../aspose.slides/baseportionformat/fontunderline) { get; set; } | Visszaadja vagy beállítja a szöveg aláhúzás típusát. Nem alkalmazott öröklődés. Olvasás/írás [`TextUnderlineType`](../textunderlinetype). |
| [HighlightColor](../../aspose.slides/baseportionformat/highlightcolor) { get; } | Visszaadja a szöveg kiemeléséhez használt színt. Nem alkalmazott öröklődés. Csak olvasható [`IColorFormat`](../icolorformat). |
| [IsHardUnderlineFill](../../aspose.slides/baseportionformat/ishardunderlinefill) { get; set; } | Megadja, hogy az aláhúzás stílus saját FillFormat tulajdonságokkal rendelkezik-e, vagy örökli azokat a szöveg FillFormat tulajdonságaitól. Olvasás/írás [`NullableBool`](../nullablebool). |
| [IsHardUnderlineLine](../../aspose.slides/baseportionformat/ishardunderlineline) { get; set; } | Megadja, hogy az aláhúzás stílus saját LineFormat tulajdonságokkal rendelkezik-e, vagy örökli azokat a szöveg LineFormat tulajdonságaitól. Olvasás/írás [`NullableBool`](../nullablebool). |
| [KerningMinimalSize](../../aspose.slides/baseportionformat/kerningminimalsize) { get; set; } | Visszaadja vagy beállítja a legkisebb betűméretet, amelynél a kerninget be kell kapcsolni. **float.NaN** azt jelenti, hogy az érték nincs definiálva, és a Mesterből kell örökölni. Olvasás/írás Single. |
| [Kumimoji](../../aspose.slides/baseportionformat/kumimoji) { get; set; } | Megadja, hogy a számok figyelmen kívül hagyják-e a szöveg kelet-nyugat-specifikus függőleges elrendezését. Nem alkalmazott öröklődés. Olvasás/írás [`NullableBool`](../nullablebool). |
| [LanguageId](../../aspose.slides/baseportionformat/languageid) { get; set; } | Visszaadja vagy beállítja egy helyesírási nyelv azonosítóját. Helyesírás- és nyelvtan-ellenőrzéshez használatos. Olvasás/írás String. |
| [LatinFont](../../aspose.slides/baseportionformat/latinfont) { get; set; } | Visszaadja vagy beállítja a latin betűtípus információt. A Null azt jelenti, hogy a betűtípus nincs definiálva, és a Mesterből kell örökölni. Olvasás/írás [`IFontData`](../ifontdata). |
| [LineFormat](../../aspose.slides/baseportionformat/lineformat) { get; } | Visszaadja a szöveg körvonalazásához használt LineFormat tulajdonságokat. Nem alkalmazott öröklődés. Csak olvasható [`ILineFormat`](../ilineformat). |
| [NormaliseHeight](../../aspose.slides/baseportionformat/normaliseheight) { get; set; } | Megadja, hogy a szöveg magasságát normalizálni kell-e. Nem alkalmazott öröklődés. Olvasás/írás [`NullableBool`](../nullablebool). |
| [ProofDisabled](../../aspose.slides/baseportionformat/proofdisabled) { get; set; } | Megadja, hogy a szöveget ne kell-e helyesírási ellenőrzésnek alávetni. Nem alkalmazott öröklődés. Olvasás/írás [`NullableBool`](../nullablebool). |
| [Spacing](../../aspose.slides/baseportionformat/spacing) { get; set; } | Visszaadja vagy beállítja a karakterek közötti távolság növekedését. **float.NaN** azt jelenti, hogy az érték nincs definiálva, és a Mesterből kell örökölni. Olvasás/írás Single. |
| [SpellCheck](../../aspose.slides/baseportionformat/spellcheck) { get; set; } | Lekéri vagy beállítja azt az értéket, amely jelzi, hogy a helyesírás-ellenőrzés engedélyezett-e a szövegrészhez. Ha ez a tulajdonság false, a szövegelemek helyesírás-ellenőrzése le van tiltva. Ha true, a helyesírás-ellenőrzés engedélyezett. Alapértelmezett érték a `false`. |
| [StrikethroughType](../../aspose.slides/baseportionformat/strikethroughtype) { get; set; } | Visszaadja vagy beállítja a szöveg áthúzás típusát. Nem alkalmazott öröklődés. Olvasás/írás [`TextStrikethroughType`](../textstrikethroughtype). |
| [SymbolFont](../../aspose.slides/baseportionformat/symbolfont) { get; set; } | Visszaadja vagy beállítja a szimbolikus betűtípus információt. A Null azt jelenti, hogy a betűtípus nincs definiálva, és a Mesterből kell örökölni. Olvasás/írás [`IFontData`](../ifontdata). |
| [TextCapType](../../aspose.slides/baseportionformat/textcaptype) { get; set; } | Visszaadja vagy beállítja a szöveg nagybetűs formázásának típusát. Nem alkalmazott öröklődés. Olvasás/írás [`TextCapType`](../textcaptype). |
| [UnderlineFillFormat](../../aspose.slides/baseportionformat/underlinefillformat) { get; } | Visszaadja az aláhúzási vonal FillFormat tulajdonságait. Nem alkalmazott öröklődés. Csak olvasható [`IFillFormat`](../ifillformat). |
| [UnderlineLineFormat](../../aspose.slides/baseportionformat/underlinelineformat) { get; } | Visszaadja a vonalat körvonalazó LineFormat tulajdonságokat. Nem alkalmazott öröklődés. Csak olvasható [`ILineFormat`](../ilineformat). |

## Metódusok

| Név | Leírás |
| --- | --- |
| override [Equals](../../aspose.slides/pviobject/equals)(object) | Összehasonlítja a megadott objektummal. |
| override [GetHashCode](../../aspose.slides/pviobject/gethashcode)() | Visszaadja a hash kódot. |

### Lásd még

* osztály [PVIObject](../pviobject)
* interfész [IBasePortionFormat](../ibaseportionformat)
* névtér [Aspose.Slides](../../aspose.slides)
* összeállítás [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->