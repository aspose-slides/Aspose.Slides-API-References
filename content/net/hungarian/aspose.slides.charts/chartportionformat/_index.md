---
title: ChartPortionFormat
second_title: Aspose.Slides .NET API hivatkozása
description: Ez az osztály a diagramokban használt diagramrész formázási tulajdonságait tartalmazza. Az IPortionFormatEffectiveData../aspose.slides/iportionformateffectivedata-tól eltérően az osztály összes tulajdonsága írható.
type: docs
weight: 1440
url: /hu/aspose.slides.charts/chartportionformat/
---
## ChartPortionFormat osztály

Ez az osztály tartalmazza a diagram részformázási tulajdonságait, amelyeket diagramokban használnak. A [`IPortionFormatEffectiveData`](../../aspose.slides/iportionformateffectivedata)-tól eltérően ennek az osztálynak az összes tulajdonsága írható.

```csharp
public sealed class ChartPortionFormat : BasePortionFormat, IChartPortionFormat
```

## Tulajdonságok

| Name | Description |
| --- | --- |
| [AlternativeLanguageId](../../aspose.slides/baseportionformat/alternativelanguageid) { get; set; } | Visszaadja vagy beállítja egy alternatív nyelv azonosítóját. Olvasás/írás String. |
| [AsIPresentationComponent](../../aspose.slides/pviobject/asipresentationcomponent) { get; } | Lehetővé teszi az alap IPresentationComponent interfész lekérését. Csak olvasható [`IPresentationComponent`](../../aspose.slides/ipresentationcomponent). |
| [ComplexScriptFont](../../aspose.slides/baseportionformat/complexscriptfont) { get; set; } | Visszaadja vagy beállítja a komplex írásrendszer betűtípus-információt. A null azt jelenti, hogy a betűtípus nincs definiálva, és a Mesterből kell öröklődni. Olvasás/írás [`IFontData`](../../aspose.slides/ifontdata). |
| [EastAsianFont](../../aspose.slides/baseportionformat/eastasianfont) { get; set; } | Visszaadja vagy beállítja a kelet-ázsiai betűtípus-információt. A null azt jelenti, hogy a betűtípus nincs definiálva, és a Mesterből kell öröklődni. Olvasás/írás [`IFontData`](../../aspose.slides/ifontdata). |
| [EffectFormat](../../aspose.slides/baseportionformat/effectformat) { get; } | Visszaadja a szöveg EffectFormat tulajdonságait. Nincs öröklődés. Csak olvasható [`IEffectFormat`](../../aspose.slides/ieffectformat). |
| [Escapement](../../aspose.slides/baseportionformat/escapement) { get; set; } | Visszaadja vagy beállítja a felső vagy alsó indexű szöveget. Az érték -100% (alsó index) és 100% (felső index) között van. **float.NaN** azt jelenti, hogy az érték nincs definiálva, és a Mesterből kell öröklődni. Olvasás/írás Single. |
| [FillFormat](../../aspose.slides/baseportionformat/fillformat) { get; } | Visszaadja a szöveg FillFormat tulajdonságait. Nincs öröklődés. Csak olvasható [`IFillFormat`](../../aspose.slides/ifillformat). |
| [FontBold](../../aspose.slides/baseportionformat/fontbold) { get; set; } | Megállapítja, hogy a betűtípus félkövér-e. Nincs öröklődés. Olvasás/írás [`NullableBool`](../../aspose.slides/nullablebool). |
| [FontHeight](../../aspose.slides/baseportionformat/fontheight) { get; set; } | Visszaadja vagy beállítja egy rész betűmagasságát. **float.NaN** azt jelenti, hogy a magasság nincs definiálva, és a Mesterből kell öröklődni. Olvasás/írás Single. |
| [FontItalic](../../aspose.slides/baseportionformat/fontitalic) { get; set; } | Megállapítja, hogy a betűtípus dőlt-e. Nincs öröklődés. Olvasás/írás [`NullableBool`](../../aspose.slides/nullablebool). |
| [FontUnderline](../../aspose.slides/baseportionformat/fontunderline) { get; set; } | Visszaadja vagy beállítja a szöveg aláhúzás típusát. Nincs öröklődés. Olvasás/írás [`TextUnderlineType`](../../aspose.slides/textunderlinetype). |
| [HighlightColor](../../aspose.slides/baseportionformat/highlightcolor) { get; } | Visszaadja a szöveg kiemelésére használt színt. Nincs öröklődés. Csak olvasható [`IColorFormat`](../../aspose.slides/icolorformat). |
| [IsHardUnderlineFill](../../aspose.slides/baseportionformat/ishardunderlinefill) { get; set; } | Megállapítja, hogy az aláhúzás stílusa saját FillFormat tulajdonságokkal rendelkezik-e, vagy a szöveg FillFormat tulajdonságaiból örököl. Olvasás/írás [`NullableBool`](../../aspose.slides/nullablebool). |
| [IsHardUnderlineLine](../../aspose.slides/baseportionformat/ishardunderlineline) { get; set; } | Megállapítja, hogy az aláhúzás stílusa saját LineFormat tulajdonságokkal rendelkezik-e, vagy a szöveg LineFormat tulajdonságaiból örököl. Olvasás/írás [`NullableBool`](../../aspose.slides/nullablebool). |
| [KerningMinimalSize](../../aspose.slides/baseportionformat/kerningminimalsize) { get; set; } | Visszaadja vagy beállítja a minimális betűméretet, amelynél a kerningnek be kell kapcsolódnia. **float.NaN** azt jelenti, hogy az érték nincs definiálva, és a Mesterből kell öröklődni. Olvasás/írás Single. |
| [Kumimoji](../../aspose.slides/baseportionformat/kumimoji) { get; set; } | Megállapítja, hogy a számok figyelmen kívül hagyják-e a szöveg keleti nyelvspecifikus függőleges elrendezését. Nincs öröklődés. Olvasás/írás [`NullableBool`](../../aspose.slides/nullablebool). |
| [LanguageId](../../aspose.slides/baseportionformat/languageid) { get; set; } | Visszaadja vagy beállítja egy nyelvhelyességi nyelv azonosítóját. Helyesírás- és nyelvtan-ellenőrzéshez használják. Olvasás/írás String. |
| [LatinFont](../../aspose.slides/baseportionformat/latinfont) { get; set; } | Visszaadja vagy beállítja a latin betűtípus-információt. A null azt jelenti, hogy a betűtípus nincs definiálva, és a Mesterből kell öröklődni. Olvasás/írás [`IFontData`](../../aspose.slides/ifontdata). |
| [LineFormat](../../aspose.slides/baseportionformat/lineformat) { get; } | Visszaadja a szöveg körvonalazásához szükséges LineFormat tulajdonságokat. Nincs öröklődés. Csak olvasható [`ILineFormat`](../../aspose.slides/ilineformat). |
| [NormaliseHeight](../../aspose.slides/baseportionformat/normaliseheight) { get; set; } | Megállapítja, hogy a szöveg magasságát normalizálni kell-e. Nincs öröklődés. Olvasás/írás [`NullableBool`](../../aspose.slides/nullablebool). |
| [ProofDisabled](../../aspose.slides/baseportionformat/proofdisabled) { get; set; } | Megállapítja, hogy a szöveget ne ellenőrizze-e nyelvhelyességi ellenőrzéssel. Nincs öröklődés. Olvasás/írás [`NullableBool`](../../aspose.slides/nullablebool). |
| [Spacing](../../aspose.slides/baseportionformat/spacing) { get; set; } | Visszaadja vagy beállítja a karakterek közti távolság növekedését. **float.NaN** azt jelenti, hogy az érték nincs definiálva, és a Mesterből kell öröklődni. Olvasás/írás Single. |
| [SpellCheck](../../aspose.slides/baseportionformat/spellcheck) { get; set; } | Lekéri vagy beállítja, hogy a szövegrésznél engedélyezve van-e a helyesírás-ellenőrzés. Ha ez a tulajdonság false, a szövegelemek helyesírás-ellenőrzése le van tiltva. Ha true, a helyesírás-ellenőrzés megengedett. Alapértelmezett érték `false`. |
| [StrikethroughType](../../aspose.slides/baseportionformat/strikethroughtype) { get; set; } | Visszaadja vagy beállítja a szöveg áthúzási típusát. Nincs öröklődés. Olvasás/írás [`TextStrikethroughType`](../../aspose.slides/textstrikethroughtype). |
| [SymbolFont](../../aspose.slides/baseportionformat/symbolfont) { get; set; } | Visszaadja vagy beállítja a szimbolikus betűtípus-információt. A null azt jelenti, hogy a betűtípus nincs definiálva, és a Mesterből kell öröklődni. Olvasás/írás [`IFontData`](../../aspose.slides/ifontdata). |
| [TextCapType](../../aspose.slides/baseportionformat/textcaptype) { get; set; } | Visszaadja vagy beállítja a szöveg nagybetűsítés típusát. Nincs öröklődés. Olvasás/írás [`TextCapType`](../../aspose.slides/textcaptype). |
| [UnderlineFillFormat](../../aspose.slides/baseportionformat/underlinefillformat) { get; } | Visszaadja az aláhúzási vonal FillFormat tulajdonságait. Nincs öröklődés. Csak olvasható [`IFillFormat`](../../aspose.slides/ifillformat). |
| [UnderlineLineFormat](../../aspose.slides/baseportionformat/underlinelineformat) { get; } | Visszaadja az aláhúzási vonal körvonalazásához használt LineFormat tulajdonságokat. Nincs öröklődés. Csak olvasható [`ILineFormat`](../../aspose.slides/ilineformat). |

## Metódusok

| Name | Description |
| --- | --- |
| override [Equals](../../aspose.slides/pviobject/equals)(object) | Összehasonlítja a megadott objektummal. |
| override [GetHashCode](../../aspose.slides/pviobject/gethashcode)() | Visszaadja a hash kódot. |

### Megjegyzések

Ez az osztály a konkrét részhez definiált szövegrészformázási tulajdonságok lekérésére és módosítására szolgál. Ez azt jelenti, hogy az értékek lekérdezésekor nem alkalmazódik öröklődés, ezért a legtöbb esetben az értékeket „nem definiáltnak” tekintik.

Az örökölt értékeket is tartalmazó hatékony formázási paraméterértékek lekéréséhez a [`GetEffective`](../../aspose.slides/portionformat/geteffective) metódust kell használni, amely egy [`IPortionFormatEffectiveData`](../../aspose.slides/iportionformateffectivedata) példányt ad vissza.

### Lásd még

* osztály [BasePortionFormat](../../aspose.slides/baseportionformat)
* interfész [IChartPortionFormat](../ichartportionformat)
* névtér [Aspose.Slides.Charts](../../aspose.slides.charts)
* összeállítás [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->