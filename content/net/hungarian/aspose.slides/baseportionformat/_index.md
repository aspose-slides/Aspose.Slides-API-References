---
title: BasePortionFormat
second_title: Aspose.Sildes .NET API hivatkozás
description: Általános szövegrész formázási tulajdonságok.
type: docs
weight: 970
url: /hu/aspose.slides/baseportionformat/
---
## BasePortionFormat osztály

Általános szövegrész formázási tulajdonságok.

```csharp
public abstract class BasePortionFormat : PVIObject, IBasePortionFormat
```

## Tulajdonságok

| Név | Leírás |
| --- | --- |
| [AlternativeLanguageId](../../aspose.slides/baseportionformat/alternativelanguageid) { get; set; } | Visszaadja vagy beállítja egy alternatív nyelv azonosítóját. Olvasás/írás String. |
| [AsIPresentationComponent](../../aspose.slides/pviobject/asipresentationcomponent) { get; } | Lehetővé teszi a base IPresentationComponent interfész lekérését. Csak olvasható [`IPresentationComponent`](../ipresentationcomponent). |
| [ComplexScriptFont](../../aspose.slides/baseportionformat/complexscriptfont) { get; set; } | Visszaadja vagy beállítja a komplex írásrendszer betűtípus-információkat. A Null azt jelenti, hogy a betűtípus nincs meghatározva és a Masterből kell öröklődni. Olvasás/írás [`IFontData`](../ifontdata). |
| [EastAsianFont](../../aspose.slides/baseportionformat/eastasianfont) { get; set; } | Visszaadja vagy beállítja a kelet-ázsiai betűtípus-információkat. A Null azt jelenti, hogy a betűtípus nincs meghatározva és a Masterből kell öröklődni. Olvasás/írás [`IFontData`](../ifontdata). |
| [EffectFormat](../../aspose.slides/baseportionformat/effectformat) { get; } | Visszaadja a szöveg EffectFormat tulajdonságait. Nincs öröklődés. Csak olvasható [`IEffectFormat`](../ieffectformat). |
| [Escapement](../../aspose.slides/baseportionformat/escapement) { get; set; } | Visszaadja vagy beállítja a felső vagy alsó index szöveget. Az érték -100% (alsó index) és 100% (felső index) között van. **float.NaN** azt jelenti, hogy az érték nincs meghatározva és a Masterből kell öröklődni. Olvasás/írás Single. |
| [FillFormat](../../aspose.slides/baseportionformat/fillformat) { get; } | Visszaadja a szöveg FillFormat tulajdonságait. Nincs öröklődés. Csak olvasható [`IFillFormat`](../ifillformat). |
| [FontBold](../../aspose.slides/baseportionformat/fontbold) { get; set; } | Meghatározza, hogy a betűtípus félkövér-e. Nincs öröklődés. Olvasás/írás [`NullableBool`](../nullablebool). |
| [FontHeight](../../aspose.slides/baseportionformat/fontheight) { get; set; } | Visszaadja vagy beállítja egy rész betűmagasságát. **float.NaN** azt jelenti, hogy a magasság nincs meghatározva és a Masterből kell öröklődni. Olvasás/írás Single. |
| [FontItalic](../../aspose.slides/baseportionformat/fontitalic) { get; set; } | Meghatározza, hogy a betűtípus dőlt-e. Nincs öröklődés. Olvasás/írás [`NullableBool`](../nullablebool). |
| [FontUnderline](../../aspose.slides/baseportionformat/fontunderline) { get; set; } | Visszaadja vagy beállítja a szöveg aláhúzási típusát. Nincs öröklődés. Olvasás/írás [`TextUnderlineType`](../textunderlinetype). |
| [HighlightColor](../../aspose.slides/baseportionformat/highlightcolor) { get; } | Visszaadja a szöveg kiemeléséhez használt színt. Nincs öröklődés. Csak olvasható [`IColorFormat`](../icolorformat). |
| [IsHardUnderlineFill](../../aspose.slides/baseportionformat/ishardunderlinefill) { get; set; } | Meghatározza, hogy az aláhúzási stílus saját FillFormat tulajdonságokkal rendelkezik-e, vagy örökli őket a szöveg FillFormat tulajdonságaiból. Olvasás/írás [`NullableBool`](../nullablebool). |
| [IsHardUnderlineLine](../../aspose.slides/baseportionformat/ishardunderlineline) { get; set; } | Meghatározza, hogy az aláhúzási stílus saját LineFormat tulajdonságokkal rendelkezik-e, vagy örökli őket a szöveg LineFormat tulajdonságaiból. Olvasás/írás [`NullableBool`](../nullablebool). |
| [KerningMinimalSize](../../aspose.slides/baseportionformat/kerningminimalsize) { get; set; } | Visszaadja vagy beállítja a minimális betűméretet, amelyhez a karakterköz (kerning) bekapcsolandó. **float.NaN** azt jelenti, hogy az érték nincs meghatározva és a Masterből kell öröklődni. Olvasás/írás Single. |
| [Kumimoji](../../aspose.slides/baseportionformat/kumimoji) { get; set; } | Meghatározza, hogy a számok figyelmen kívül hagyják-e a szöveg keleti nyelvre jellemző függőleges elrendezést. Nincs öröklődés. Olvasás/írás [`NullableBool`](../nullablebool). |
| [LanguageId](../../aspose.slides/baseportionformat/languageid) { get; set; } | Visszaadja vagy beállítja egy helyesírási nyelv azonosítóját. A helyesírás- és nyelvtani ellenőrzéshez használatos. Olvasás/írás String. |
| [LatinFont](../../aspose.slides/baseportionformat/latinfont) { get; set; } | Visszaadja vagy beállítja a latin betűtípus-információkat. A Null azt jelenti, hogy a betűtípus nincs meghatározva és a Masterből kell öröklődni. Olvasás/írás [`IFontData`](../ifontdata). |
| [LineFormat](../../aspose.slides/baseportionformat/lineformat) { get; } | Visszaadja a szöveg körvonalazásához szükséges LineFormat tulajdonságokat. Nincs öröklődés. Csak olvasható [`ILineFormat`](../ilineformat). |
| [NormaliseHeight](../../aspose.slides/baseportionformat/normaliseheight) { get; set; } | Meghatározza, hogy a szöveg magasságát normalizálni kell-e. Nincs öröklődés. Olvasás/írás [`NullableBool`](../nullablebool). |
| [ProofDisabled](../../aspose.slides/baseportionformat/proofdisabled) { get; set; } | Meghatározza, hogy a szöveget ne kell-e helyesen ellenőrizni. Nincs öröklődés. Olvasás/írás [`NullableBool`](../nullablebool). |
| [Spacing](../../aspose.slides/baseportionformat/spacing) { get; set; } | Visszaadja vagy beállítja a karakterek közti távolság növekményét. **float.NaN** azt jelenti, hogy az érték nincs meghatározva és a Masterből kell öröklődni. Olvasás/írás Single. |
| [SpellCheck](../../aspose.slides/baseportionformat/spellcheck) { get; set; } | Megadja vagy állítja be, hogy engedélyezett-e a helyesírás-ellenőrzés a szövegrészhez. Ha a tulajdonság hamisra van állítva, a szövegelemek helyesírás-ellenőrzése le van tiltva. Ha igazra állítja, a helyesírás-ellenőrzés engedélyezett. Az alapértelmezett érték `false`. |
| [StrikethroughType](../../aspose.slides/baseportionformat/strikethroughtype) { get; set; } | Visszaadja vagy beállítja a szöveg áthúzási típusát. Nincs öröklődés. Olvasás/írás [`TextStrikethroughType`](../textstrikethroughtype). |
| [SymbolFont](../../aspose.slides/baseportionformat/symbolfont) { get; set; } | Visszaadja vagy beállítja a szimbolikus betűtípus-információkat. A Null azt jelenti, hogy a betűtípus nincs meghatározva és a Masterből kell öröklődni. Olvasás/írás [`IFontData`](../ifontdata). |
| [TextCapType](../../aspose.slides/baseportionformat/textcaptype) { get; set; } | Visszaadja vagy beállítja a szöveg nagybetűs írásmódjának típusát. Nincs öröklődés. Olvasás/írás [`TextCapType`](../textcaptype). |
| [UnderlineFillFormat](../../aspose.slides/baseportionformat/underlinefillformat) { get; } | Visszaadja az aláhúzási vonal FillFormat tulajdonságait. Nincs öröklődés. Csak olvasható [`IFillFormat`](../ifillformat). |
| [UnderlineLineFormat](../../aspose.slides/baseportionformat/underlinelineformat) { get; } | Visszaadja az aláhúzási vonal körvonalazásához használt LineFormat tulajdonságokat. Nincs öröklődés. Csak olvasható [`ILineFormat`](../ilineformat). |

## Módszerek

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