---
title: ChartPortionFormat
second_title: Aspose.Sildes .NET API referencia
description: Ez az osztály tartalmazza a diagramokban használt diagramrész formázási tulajdonságokat. Az IPortionFormatEffectiveData../aspose.slides/iportionformateffectivedata-tól eltérően ennek az osztálynak minden tulajdonsága írható.
type: docs
weight: 1410
url: /hu/aspose.slides.charts/chartportionformat/
---
## ChartPortionFormat osztály

Ez az osztály a diagramokban használt diagramrészformázási tulajdonságokat tartalmazza. A [`IPortionFormatEffectiveData`](../../aspose.slides/iportionformateffectivedata)-től eltérően ennek az osztálynak minden tulajdonsága írható.

```csharp
public sealed class ChartPortionFormat : BasePortionFormat, IChartPortionFormat
```

## Tulajdonságok

| Név | Leírás |
| --- | --- |
| [AlternativeLanguageId](../../aspose.slides/baseportionformat/alternativelanguageid) { get; set; } | Visszaadja vagy beállítja egy alternatív nyelv azonosítóját. Olvasás/írás String. |
| [AsIPresentationComponent](../../aspose.slides/pviobject/asipresentationcomponent) { get; } | Lehetővé teszi a base IPresentationComponent interfész lekérését. Csak olvasható [`IPresentationComponent`](../../aspose.slides/ipresentationcomponent). |
| [ComplexScriptFont](../../aspose.slides/baseportionformat/complexscriptfont) { get; set; } | Visszaadja vagy beállítja a komplex írásjel betűtípusinformációt. Null azt jelenti, hogy a betűtípus nincs definiálva, és a Mesterből kell örökölni. Olvasás/írás [`IFontData`](../../aspose.slides/ifontdata). |
| [EastAsianFont](../../aspose.slides/baseportionformat/eastasianfont) { get; set; } | Visszaadja vagy beállítja a Kelet-Ázsiai betűtípusinformációt. Null azt jelenti, hogy a betűtípus nincs definiálva, és a Mesterből kell örökölni. Olvasás/írás [`IFontData`](../../aspose.slides/ifontdata). |
| [EffectFormat](../../aspose.slides/baseportionformat/effectformat) { get; } | Visszaadja a szöveg EffectFormat tulajdonságait. Nincs öröklődés. Csak olvasható [`IEffectFormat`](../../aspose.slides/ieffectformat). |
| [Escapement](../../aspose.slides/baseportionformat/escapement) { get; set; } | Visszaadja vagy beállítja a felső vagy alsó indexű szöveget. Az érték -100 % (alsó index) és 100 % (felső index) között van. **float.NaN** azt jelenti, hogy az érték nincs definiálva, és a Mesterből kell örökölni. Olvasás/írás Single. |
| [FillFormat](../../aspose.slides/baseportionformat/fillformat) { get; } | Visszaadja a szöveg FillFormat tulajdonságait. Nincs öröklődés. Csak olvasható [`IFillFormat`](../../aspose.slides/ifillformat). |
| [FontBold](../../aspose.slides/baseportionformat/fontbold) { get; set; } | Megállapítja, hogy a betűtípus félkövér-e. Nincs öröklődés. Olvasás/írás [`NullableBool`](../../aspose.slides/nullablebool). |
| [FontHeight](../../aspose.slides/baseportionformat/fontheight) { get; set; } | Visszaadja vagy beállítja egy rész betűmagasságát. **float.NaN** azt jelenti, hogy a magasság nincs definiálva, és a Mesterből kell örökölni. Olvasás/írás Single. |
| [FontItalic](../../aspose.slides/baseportionformat/fontitalic) { get; set; } | Megállapítja, hogy a betűtípus dőlt-e. Nincs öröklődés. Olvasás/írás [`NullableBool`](../../aspose.slides/nullablebool). |
| [FontUnderline](../../aspose.slides/baseportionformat/fontunderline) { get; set; } | Visszaadja vagy beállítja a szöveg aláhúzási típusát. Nincs öröklődés. Olvasás/írás [`TextUnderlineType`](../../aspose.slides/textunderlinetype). |
| [HighlightColor](../../aspose.slides/baseportionformat/highlightcolor) { get; } | Visszaadja a szöveg kiemeléséhez használt színt. Nincs öröklődés. Csak olvasható [`IColorFormat`](../../aspose.slides/icolorformat). |
| [IsHardUnderlineFill](../../aspose.slides/baseportionformat/ishardunderlinefill) { get; set; } | Meghatározza, hogy az aláhúzás stílus saját FillFormat tulajdonságokkal rendelkezik-e, vagy a szöveg FillFormat tulajdonságaiból örököl. Olvasás/írás [`NullableBool`](../../aspose.slides/nullablebool). |
| [IsHardUnderlineLine](../../aspose.slides/baseportionformat/ishardunderlineline) { get; set; } | Meghatározza, hogy az aláhúzás stílus saját LineFormat tulajdonságokkal rendelkezik-e, vagy a szöveg LineFormat tulajdonságaiból örököl. Olvasás/írás [`NullableBool`](../../aspose.slides/nullablebool). |
| [KerningMinimalSize](../../aspose.slides/baseportionformat/kerningminimalsize) { get; set; } | Visszaadja vagy beállítja a legkisebb betűméretet, amelynél a kerningnek be kell kapcsolódnia. **float.NaN** azt jelenti, hogy az érték nincs definiálva, és a Mesterből kell örökölni. Olvasás/írás Single. |
| [Kumimoji](../../aspose.slides/baseportionformat/kumimoji) { get; set; } | Meghatározza, hogy a számok figyelmen kívül hagyják-e a kelet-ázsiai nyelvspecifikus függőleges szövegelrendezést. Nincs öröklődés. Olvasás/írás [`NullableBool`](../../aspose.slides/nullablebool). |
| [LanguageId](../../aspose.slides/baseportionformat/languageid) { get; set; } | Visszaadja vagy beállítja egy helyesírási nyelv azonosítóját. Helyesírás- és nyelvtan-ellenőrzéshez használatos. Olvasás/írás String. |
| [LatinFont](../../aspose.slides/baseportionformat/latinfont) { get; set; } | Visszaadja vagy beállítja a latin betűtípusinformációt. Null azt jelenti, hogy a betűtípus nincs definiálva, és a Mesterből kell örökölni. Olvasás/írás [`IFontData`](../../aspose.slides/ifontdata). |
| [LineFormat](../../aspose.slides/baseportionformat/lineformat) { get; } | Visszaadja a szöveg körvonalazásához használt LineFormat tulajdonságokat. Nincs öröklődés. Csak olvasható [`ILineFormat`](../../aspose.slides/ilineformat). |
| [NormaliseHeight](../../aspose.slides/baseportionformat/normaliseheight) { get; set; } | Meghatározza, hogy a szöveg magassága normalizálva legyen-e. Nincs öröklődés. Olvasás/írás [`NullableBool`](../../aspose.slides/nullablebool). |
| [ProofDisabled](../../aspose.slides/baseportionformat/proofdisabled) { get; set; } | Meghatározza, hogy a szöveget ne kelljen helyesírási ellenőrzésnek alávetni. Nincs öröklődés. Olvasás/írás [`NullableBool`](../../aspose.slides/nullablebool). |
| [Spacing](../../aspose.slides/baseportionformat/spacing) { get; set; } | Visszaadja vagy beállítja a karakterközti távolság növelését. **float.NaN** azt jelenti, hogy az érték nincs definiálva, és a Mesterből kell örökölni. Olvasás/írás Single. |
| [SpellCheck](../../aspose.slides/baseportionformat/spellcheck) { get; set; } | Megadja, hogy a helyesírás-ellenőrzés engedélyezve van-e a szövegrészre vonatkozóan. Ha a tulajdonság értéke false, a helyesírás-ellenőrzés el lesz nyomva. Ha true, a helyesírás-ellenőrzés megengedett. Alapértelmezett érték a `false`. |
| [StrikethroughType](../../aspose.slides/baseportionformat/strikethroughtype) { get; set; } | Visszaadja vagy beállítja a szöveg áthúzási típusát. Nincs öröklődés. Olvasás/írás [`TextStrikethroughType`](../../aspose.slides/textstrikethroughtype). |
| [SymbolFont](../../aspose.slides/baseportionformat/symbolfont) { get; set; } | Visszaadja vagy beállítja a szimbolikus betűtípusinformációt. Null azt jelenti, hogy a betűtípus nincs definiálva, és a Mesterből kell örökölni. Olvasás/írás [`IFontData`](../../aspose.slides/ifontdata). |
| [TextCapType](../../aspose.slides/baseportionformat/textcaptype) { get; set; } | Visszaadja vagy beállítja a szöveg nagybetűsítés típusát. Nincs öröklődés. Olvasás/írás [`TextCapType`](../../aspose.slides/textcaptype). |
| [UnderlineFillFormat](../../aspose.slides/baseportionformat/underlinefillformat) { get; } | Visszaadja az aláhúzás vonal FillFormat tulajdonságait. Nincs öröklődés. Csak olvasható [`IFillFormat`](../../aspose.slides/ifillformat). |
| [UnderlineLineFormat](../../aspose.slides/baseportionformat/underlinelineformat) { get; } | Visszaadja a vonal körvonalazásához használt LineFormat tulajdonságokat. Nincs öröklődés. Csak olvasható [`ILineFormat`](../../aspose.slides/ilineformat). |

## Módszerek

| Név | Leírás |
| --- | --- |
| override [Equals](../../aspose.slides/pviobject/equals)(object) | Összehasonlítja a megadott objektummal. |
| override [GetHashCode](../../aspose.slides/pviobject/gethashcode)() | Visszaadja a hash kódot. |

### Megjegyzések

Ez az osztály a szövegrész formázási tulajdonságainak visszaadására és módosítására szolgál, amelyek az adott részhez vannak definiálva. Ez azt jelenti, hogy értékek lekérésekor nincs öröklődés, így a legtöbb esetben „nem definiált” értékeket kap.

A hatékony formázási paraméterértékek, beleértve az örökölt értékeket, lekéréséhez a [`GetEffective`](../../aspose.slides/portionformat/geteffective) metódust kell használni, amely egy [`IPortionFormatEffectiveData`](../../aspose.slides/iportionformateffectivedata) példányt ad vissza.

### Lásd még

* osztály [BasePortionFormat](../../aspose.slides/baseportionformat)
* interfész [IChartPortionFormat](../ichartportionformat)
* névtér [Aspose.Slides.Charts](../../aspose.slides.charts)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->