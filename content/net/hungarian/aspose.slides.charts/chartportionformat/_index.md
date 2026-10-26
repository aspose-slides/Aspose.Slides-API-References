---
title: ChartPortionFormat
second_title: Aspose.Sildes .NET API referencia
description: Ez az osztály tartalmazza a diagramokban használt diagramrész formázási tulajdonságait. Az IPortionFormatEffectiveData../aspose.slides/iportionformateffectivedata-tól eltérően ennek az osztálynak az összes tulajdonsága írható.
type: docs
weight: 1430
url: /hu/aspose.slides.charts/chartportionformat/
---
## ChartPortionFormat osztály

Ez az osztály a diagramrészek formázási tulajdonságait tartalmazza, amelyeket diagramokban használnak. A [`IPortionFormatEffectiveData`](../../aspose.slides/iportionformateffectivedata)-tól eltérően az osztály összes tulajdonsága írható.

```csharp
public sealed class ChartPortionFormat : BasePortionFormat, IChartPortionFormat
```

## Tulajdonságok

| Név | Leírás |
| --- | --- |
| [AlternativeLanguageId](../../aspose.slides/baseportionformat/alternativelanguageid) { get; set; } | Visszaadja vagy beállítja egy alternatív nyelv azonosítóját. Olvasás/írás String. |
| [AsIPresentationComponent](../../aspose.slides/pviobject/asipresentationcomponent) { get; } | Lehetővé teszi a base IPresentationComponent interfész lekérését. Csak olvasható [`IPresentationComponent`](../../aspose.slides/ipresentationcomponent). |
| [ComplexScriptFont](../../aspose.slides/baseportionformat/complexscriptfont) { get; set; } | Visszaadja vagy beállítja a komplex szkript betűtípus információt. A Null azt jelenti, hogy a betűtípus nincs definiálva, és a Masterből kell öröklődni. Olvasás/írás [`IFontData`](../../aspose.slides/ifontdata). |
| [EastAsianFont](../../aspose.slides/baseportionformat/eastasianfont) { get; set; } | Visszaadja vagy beállítja a kelet-ázsiai betűtípus információt. A Null azt jelenti, hogy a betűtípus nincs definiálva, és a Masterből kell öröklődni. Olvasás/írás [`IFontData`](../../aspose.slides/ifontdata). |
| [EffectFormat](../../aspose.slides/baseportionformat/effectformat) { get; } | Visszaadja a szöveg EffectFormat tulajdonságait. Nincs öröklődés. Csak olvasható [`IEffectFormat`](../../aspose.slides/ieffectformat). |
| [Escapement](../../aspose.slides/baseportionformat/escapement) { get; set; } | Visszaadja vagy beállítja a felső vagy alsó indexű szöveget. Az érték -100% (alsó index) és 100% (felső index) között van. **float.NaN** azt jelenti, hogy az érték nincs definiálva, és a Masterből kell öröklődni. Olvasás/írás Single. |
| [FillFormat](../../aspose.slides/baseportionformat/fillformat) { get; } | Visszaadja a szöveg FillFormat tulajdonságait. Nincs öröklődés. Csak olvasható [`IFillFormat`](../../aspose.slides/ifillformat). |
| [FontBold](../../aspose.slides/baseportionformat/fontbold) { get; set; } | Megadja, hogy a betűtípus félkövér-e. Nincs öröklődés. Olvasás/írás [`NullableBool`](../../aspose.slides/nullablebool). |
| [FontHeight](../../aspose.slides/baseportionformat/fontheight) { get; set; } | Visszaadja vagy beállítja egy rész betűmagasságát. **float.NaN** azt jelenti, hogy a magasság nincs definiálva, és a Masterből kell öröklődni. Olvasás/írás Single. |
| [FontItalic](../../aspose.slides/baseportionformat/fontitalic) { get; set; } | Megadja, hogy a betűtípus dőlt-e. Nincs öröklődés. Olvasás/írás [`NullableBool`](../../aspose.slides/nullablebool). |
| [FontUnderline](../../aspose.slides/baseportionformat/fontunderline) { get; set; } | Visszaadja vagy beállítja a szöveg aláhúzási típusát. Nincs öröklődés. Olvasás/írás [`TextUnderlineType`](../../aspose.slides/textunderlinetype). |
| [HighlightColor](../../aspose.slides/baseportionformat/highlightcolor) { get; } | Visszaadja a szöveg kiemeléséhez használt színt. Nincs öröklődés. Csak olvasható [`IColorFormat`](../../aspose.slides/icolorformat). |
| [IsHardUnderlineFill](../../aspose.slides/baseportionformat/ishardunderlinefill) { get; set; } | Megadja, hogy az aláhúzás stílusának saját FillFormat tulajdonságai vannak-e, vagy örökli a szöveg FillFormat tulajdonságait. Olvasás/írás [`NullableBool`](../../aspose.slides/nullablebool). |
| [IsHardUnderlineLine](../../aspose.slides/baseportionformat/ishardunderlineline) { get; set; } | Megadja, hogy az aláhúzás stílusának saját LineFormat tulajdonságai vannak-e, vagy örökli a szöveg LineFormat tulajdonságait. Olvasás/írás [`NullableBool`](../../aspose.slides/nullablebool). |
| [KerningMinimalSize](../../aspose.slides/baseportionformat/kerningminimalsize) { get; set; } | Visszaadja vagy beállítja a minimális betűméretet, amelynél a kerningnek be kell kapcsolódnia. **float.NaN** azt jelenti, hogy az érték nincs definiálva, és a Masterből kell öröklődni. Olvasás/írás Single. |
| [Kumimoji](../../aspose.slides/baseportionformat/kumimoji) { get; set; } | Megadja, hogy a számok figyelmen kívül hagyják-e a szöveg keleti nyelvspecifikus függőleges elrendezését. Nincs öröklődés. Olvasás/írás [`NullableBool`](../../aspose.slides/nullablebool). |
| [LanguageId](../../aspose.slides/baseportionformat/languageid) { get; set; } | Visszaadja vagy beállítja egy helyesírási nyelv azonosítóját. A helyesírás és nyelvtan ellenőrzéséhez használják. Olvasás/írás String. |
| [LatinFont](../../aspose.slides/baseportionformat/latinfont) { get; set; } | Visszaadja vagy beállítja a latin betűtípus információt. A Null azt jelenti, hogy a betűtípus nincs definiálva, és a Masterből kell öröklődni. Olvasás/írás [`IFontData`](../../aspose.slides/ifontdata). |
| [LineFormat](../../aspose.slides/baseportionformat/lineformat) { get; } | Visszaadja a szöveg körvonalazáshoz szükséges LineFormat tulajdonságokat. Nincs öröklődés. Csak olvasható [`ILineFormat`](../../aspose.slides/ilineformat). |
| [NormaliseHeight](../../aspose.slides/baseportionformat/normaliseheight) { get; set; } | Megadja, hogy a szöveg magasságát normalizálni kell-e. Nincs öröklődés. Olvasás/írás [`NullableBool`](../../aspose.slides/nullablebool). |
| [ProofDisabled](../../aspose.slides/baseportionformat/proofdisabled) { get; set; } | Megadja, hogy a szöveget nem kell-e helyesírással ellenőrizni. Nincs öröklődés. Olvasás/írás [`NullableBool`](../../aspose.slides/nullablebool). |
| [Spacing](../../aspose.slides/baseportionformat/spacing) { get; set; } | Visszaadja vagy beállítja a karakterek közötti távolság növekményét. **float.NaN** azt jelenti, hogy az érték nincs definiálva, és a Masterből kell öröklődni. Olvasás/írás Single. |
| [SpellCheck](../../aspose.slides/baseportionformat/spellcheck) { get; set; } | Beállítja vagy lekéri, hogy a helyesírás-ellenőrzés engedélyezett-e a szövegrészhez. Ha ez a tulajdonság false, a szövegelemek helyesírás-ellenőrzése el van nyomva. Ha true, a helyesírás-ellenőrzés engedélyezett. Az alapértelmezett érték `false`. |
| [StrikethroughType](../../aspose.slides/baseportionformat/strikethroughtype) { get; set; } | Visszaadja vagy beállítja a szöveg áthúzási típusát. Nincs öröklődés. Olvasás/írás [`TextStrikethroughType`](../../aspose.slides/textstrikethroughtype). |
| [SymbolFont](../../aspose.slides/baseportionformat/symbolfont) { get; set; } | Visszaadja vagy beállítja a szimbolikus betűtípus információt. A Null azt jelenti, hogy a betűtípus nincs definiálva, és a Masterből kell öröklődni. Olvasás/írás [`IFontData`](../../aspose.slides/ifontdata). |
| [TextCapType](../../aspose.slides/baseportionformat/textcaptype) { get; set; } | Visszaadja vagy beállítja a szöveg nagybetűs/kisbetűs típusát. Nincs öröklődés. Olvasás/írás [`TextCapType`](../../aspose.slides/textcaptype). |
| [UnderlineFillFormat](../../aspose.slides/baseportionformat/underlinefillformat) { get; } | Visszaadja az aláhúzási vonal FillFormat tulajdonságait. Nincs öröklődés. Csak olvasható [`IFillFormat`](../../aspose.slides/ifillformat). |
| [UnderlineLineFormat](../../aspose.slides/baseportionformat/underlinelineformat) { get; } | Visszaadja a vonalat körvonalazó LineFormat tulajdonságokat. Nincs öröklődés. Csak olvasható [`ILineFormat`](../../aspose.slides/ilineformat). |

## Metódusok

| Név | Leírás |
| --- | --- |
| override [Equals](../../aspose.slides/pviobject/equals)(object) | Összehasonlítja a megadott objektummal. |
| override [GetHashCode](../../aspose.slides/pviobject/gethashcode)() | Visszaadja a hash kódot. |

### Megjegyzés

Ez az osztály a szövegrész formázási tulajdonságainak visszaadására és módosítására szolgál, amelyek a konkrét részhez vannak definiálva. Ez azt jelenti, hogy értékek lekérdezésekor nincs öröklődés alkalmazva, így a legtöbb esetben olyan értékeket kapunk, amelyek jelentése „nem definiált”.

Az effektív formázási paraméterértékek, beleértve az örökölt értékeket, lekéréséhez a [`GetEffective`](../../aspose.slides/portionformat/geteffective) metódust kell használni, amely egy [`IPortionFormatEffectiveData`](../../aspose.slides/iportionformateffectivedata) példányt ad vissza.

### Lásd még

* osztály [BasePortionFormat](../../aspose.slides/baseportionformat)
* interfész [IChartPortionFormat](../ichartportionformat)
* névtér [Aspose.Slides.Charts](../../aspose.slides.charts)
* összeállítás [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->