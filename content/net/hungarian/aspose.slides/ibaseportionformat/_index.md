---
title: IBasePortionFormat
second_title: Aspose.Sildes .NET API referencia
description: Ez az osztály a szöveg részlet formázási tulajdonságait tartalmazza. Az IPortionFormatEffectiveData./iportionformateffectivedata-tól eltérően ennek az osztálynak az összes tulajdonsága írható.
type: docs
weight: 5330
url: /hu/aspose.slides/ibaseportionformat/
---
## IBasePortionFormat interfész

Ez az osztály a szöveg részlet formázási tulajdonságait tartalmazza. A [`IPortionFormatEffectiveData`](../iportionformateffectivedata)-tól eltérően ennek az osztálynak az összes tulajdonsága írható.

```csharp
public interface IBasePortionFormat
```

## Tulajdonságok

| Név | Leírás |
| --- | --- |
| [AlternativeLanguageId](../../aspose.slides/ibaseportionformat/alternativelanguageid) { get; set; } | Visszaadja vagy beállítja egy alternatív nyelv azonosítóját. Olvasás/írás String. |
| [ComplexScriptFont](../../aspose.slides/ibaseportionformat/complexscriptfont) { get; set; } | Visszaadja vagy beállítja a komplex írásrendszer betűtípus-információit. A Null azt jelenti, hogy a betűtípus nincs definiálva, és a Mesterből kell örökölni. Olvasás/írás [`IFontData`](../ifontdata). |
| [EastAsianFont](../../aspose.slides/ibaseportionformat/eastasianfont) { get; set; } | Visszaadja vagy beállítja az kelet-ázsiai betűtípus-információkat. A Null azt jelenti, hogy a betűtípus nincs definiálva, és a Mesterből kell örökölni. Olvasás/írás [`IFontData`](../ifontdata). |
| [EffectFormat](../../aspose.slides/ibaseportionformat/effectformat) { get; } | Visszaadja a szöveg EffectFormat tulajdonságait. Nincs öröklődés. Csak olvasható [`IEffectFormat`](../ieffectformat). |
| [Escapement](../../aspose.slides/ibaseportionformat/escapement) { get; set; } | Visszaadja vagy beállítja a felső vagy alsó indexű szöveget. Az érték -100 % (alsó index) és 100 % (felső index) között lehet. A **float.NaN** azt jelenti, hogy az érték nincs definiálva, és a Mesterből kell örökölni. Olvasás/írás Single. |
| [FillFormat](../../aspose.slides/ibaseportionformat/fillformat) { get; } | Visszaadja a szöveg FillFormat tulajdonságait. Nincs öröklődés. Csak olvasható [`IFillFormat`](../ifillformat). |
| [FontBold](../../aspose.slides/ibaseportionformat/fontbold) { get; set; } | Meghatározza, hogy a betűtípus félkövér-e. Nincs öröklődés. Olvasás/írás [`NullableBool`](../nullablebool). |
| [FontHeight](../../aspose.slides/ibaseportionformat/fontheight) { get; set; } | Visszaadja vagy beállítja egy részlet betűmagasságát. A **float.NaN** azt jelenti, hogy a magasság nincs definiálva, és a Mesterből kell örökölni. Olvasás/írás Single. |
| [FontItalic](../../aspose.slides/ibaseportionformat/fontitalic) { get; set; } | Meghatározza, hogy a betűtípus dőlött-e. Nincs öröklődés. Olvasás/írás [`NullableBool`](../nullablebool). |
| [FontUnderline](../../aspose.slides/ibaseportionformat/fontunderline) { get; set; } | Visszaadja vagy beállítja a szöveg aláhúzás típusát. Nincs öröklődés. Olvasás/írás [`TextUnderlineType`](../textunderlinetype). |
| [HighlightColor](../../aspose.slides/ibaseportionformat/highlightcolor) { get; } | Visszaadja a szöveg kiemeléséhez használt színt. Nincs öröklődés. Csak olvasható [`IColorFormat`](../icolorformat). |
| [IsHardUnderlineFill](../../aspose.slides/ibaseportionformat/ishardunderlinefill) { get; set; } | Meghatározza, hogy az aláhúzás stílus saját FillFormat tulajdonságokkal rendelkezik-e, vagy örökli a szöveg FillFormat tulajdonságait. Olvasás/írás [`NullableBool`](../nullablebool). |
| [IsHardUnderlineLine](../../aspose.slides/ibaseportionformat/ishardunderlineline) { get; set; } | Meghatározza, hogy az aláhúzás stílus saját LineFormat tulajdonságokkal rendelkezik-e, vagy örökli a szöveg LineFormat tulajdonságait. Olvasás/írás [`NullableBool`](../nullablebool). |
| [KerningMinimalSize](../../aspose.slides/ibaseportionformat/kerningminimalsize) { get; set; } | Visszaadja vagy beállítja a minimális betűméretet, amelynél a kerningnek be kell kapcsolódnia. A **float.NaN** azt jelenti, hogy az érték nincs definiálva, és a Mesterből kell örökölni. Olvasás/írás Single. |
| [Kumimoji](../../aspose.slides/ibaseportionformat/kumimoji) { get; set; } | Meghatározza, hogy a számok figyelmen kívül hagyják-e a szöveg keleti nyelvre jellemző függőleges elrendezést. Nincs öröklődés. Olvasás/írás [`NullableBool`](../nullablebool). |
| [LanguageId](../../aspose.slides/ibaseportionformat/languageid) { get; set; } | Visszaadja vagy beállítja egy helyesírási nyelv azonosítóját. A helyesírás- és nyelvtanellenőrzéshez használják. Olvasás/írás String. |
| [LatinFont](../../aspose.slides/ibaseportionformat/latinfont) { get; set; } | Visszaadja vagy beállítja a latin betűtípus-információkat. A Null azt jelenti, hogy a betűtípus nincs definiálva, és a Mesterből kell örökölni. Olvasás/írás [`IFontData`](../ifontdata). |
| [LineFormat](../../aspose.slides/ibaseportionformat/lineformat) { get; } | Visszaadja a szöveg körvonalazásához tartozó LineFormat tulajdonságokat. Nincs öröklődés. Csak olvasható [`ILineFormat`](../ilineformat). |
| [NormaliseHeight](../../aspose.slides/ibaseportionformat/normaliseheight) { get; set; } | Meghatározza, hogy a szöveg magasságát normalizálni kell-e. Nincs öröklődés. Olvasás/írás [`NullableBool`](../nullablebool). |
| [ProofDisabled](../../aspose.slides/ibaseportionformat/proofdisabled) { get; set; } | Meghatározza, hogy a szöveget ne kell-e helyesírással ellenőrizni. Nincs öröklődés. Olvasás/írás [`NullableBool`](../nullablebool). |
| [Spacing](../../aspose.slides/ibaseportionformat/spacing) { get; set; } | Visszaadja vagy beállítja a karakterközök növekedését. A **float.NaN** azt jelenti, hogy az érték nincs definiálva, és a Mesterből kell örökölni. Olvasás/írás Single. |
| [SpellCheck](../../aspose.slides/ibaseportionformat/spellcheck) { get; set; } | Meghatározza, hogy a helyesírás-ellenőrzés engedélyezett-e a szövegrészhez. Ha ez a tulajdonság hamis, a szövegelemek helyesírás-ellenőrzése el van nyomva. Ha igaz, a helyesírás-ellenőrzés megengedett. Az alapérték `false`. |
| [StrikethroughType](../../aspose.slides/ibaseportionformat/strikethroughtype) { get; set; } | Visszaadja vagy beállítja a szöveg áthúzási típusát. Nincs öröklődés. Olvasás/írás [`TextStrikethroughType`](../textstrikethroughtype). |
| [SymbolFont](../../aspose.slides/ibaseportionformat/symbolfont) { get; set; } | Visszaadja vagy beállítja a szimbolikus betűtípus-információkat. A Null azt jelenti, hogy a betűtípus nincs definiálva, és a Mesterből kell örökölni. Olvasás/írás [`IFontData`](../ifontdata). |
| [TextCapType](../../aspose.slides/ibaseportionformat/textcaptype) { get; set; } | Visszaadja vagy beállítja a szöveg nagybetűsítésének típusát. Nincs öröklődés. Olvasás/írás [`TextCapType`](../textcaptype). |
| [UnderlineFillFormat](../../aspose.slides/ibaseportionformat/underlinefillformat) { get; } | Visszaadja az aláhúzás vonal FillFormat tulajdonságait. Nincs öröklődés. Csak olvasható [`IFillFormat`](../ifillformat). |
| [UnderlineLineFormat](../../aspose.slides/ibaseportionformat/underlinelineformat) { get; } | Visszaadja a LineFormat tulajdonságokat, amelyek az aláhúzás vonal körvonalazásához használatosak. Nincs öröklődés. Csak olvasható [`ILineFormat`](../ilineformat). |

### Megjegyzések

Ez az osztály a meghatározott részlethez definiált szövegrész formázási tulajdonságok visszaadására és módosítására szolgál. Ez azt jelenti, hogy értékek lekérdezésekor nincs öröklődés, ezért a legtöbb esetben olyan értékeket kap, amelyek „nem definiáltak” jelentésűek.

A hatékony formázási paraméterértékek, beleértve az örökölt értékeket, lekéréséhez a [`GetEffective`](../iportionformat/geteffective) metódust kell használni, amely egy [`IPortionFormatEffectiveData`](../iportionformateffectivedata) példányt ad vissza.

### Lásd még

* névtér [Aspose.Slides](../../aspose.slides)
* összeállítás [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->