---
title: IBasePortionFormat
second_title: Aspose.Sildes .NET API Referencia
description: Ez az osztály tartalmazza a szövegrész formázási tulajdonságait. Az IPortionFormatEffectiveData./iportionformateffectivedata-tól eltérően, az osztály összes tulajdonsága írható.
type: docs
weight: 5290
url: /hu/aspose.slides/ibaseportionformat/
---
## IBasePortionFormat interfész

Ez az osztály tartalmazza a szövegrész formázási tulajdonságait. A [`IPortionFormatEffectiveData`](../iportionformateffectivedata)-tól eltérően, az osztály összes tulajdonsága írható.

```csharp
public interface IBasePortionFormat
```

## Tulajdonságok

| Név | Leírás |
| --- | --- |
| [AlternativeLanguageId](../../aspose.slides/ibaseportionformat/alternativelanguageid) { get; set; } | Visszaadja vagy beállítja egy alternatív nyelv azonosítóját. Olvasás/írás String. |
| [ComplexScriptFont](../../aspose.slides/ibaseportionformat/complexscriptfont) { get; set; } | Visszaadja vagy beállítja a komplex írásrendszer betűtípus információját. A Null azt jelenti, hogy a betűtípus nincs definiálva, és a Mesterből kell örökölni. Olvasás/írás [`IFontData`](../ifontdata). |
| [EastAsianFont](../../aspose.slides/ibaseportionformat/eastasianfont) { get; set; } | Visszaadja vagy beállítja a kelet-ázsiai betűtípus információját. A Null azt jelenti, hogy a betűtípus nincs definiálva, és a Mesterből kell örökölni. Olvasás/írás [`IFontData`](../ifontdata). |
| [EffectFormat](../../aspose.slides/ibaseportionformat/effectformat) { get; } | Visszaadja a szöveg EffectFormat tulajdonságait. Nincs öröklődés alkalmazva. Csak olvasás [`IEffectFormat`](../ieffectformat). |
| [Escapement](../../aspose.slides/ibaseportionformat/escapement) { get; set; } | Visszaadja vagy beállítja a felső vagy alsó indexű szöveget. Az érték -100% (alsó index) és 100% (felső index) között van. **float.NaN** azt jelenti, hogy az érték nincs definiálva, és a Mesterből kell örökölni. Olvasás/írás Single. |
| [FillFormat](../../aspose.slides/ibaseportionformat/fillformat) { get; } | Visszaadja a szöveg FillFormat tulajdonságait. Nincs öröklődés alkalmazva. Csak olvasás [`IFillFormat`](../ifillformat). |
| [FontBold](../../aspose.slides/ibaseportionformat/fontbold) { get; set; } | Megállapítja, hogy a betűtípus félkövér-e. Nincs öröklődés alkalmazva. Olvasás/írás [`NullableBool`](../nullablebool). |
| [FontHeight](../../aspose.slides/ibaseportionformat/fontheight) { get; set; } | Visszaadja vagy beállítja egy rész betűmagasságát. **float.NaN** azt jelenti, hogy a magasság nincs definiálva, és a Mesterből kell örökölni. Olvasás/írás Single. |
| [FontItalic](../../aspose.slides/ibaseportionformat/fontitalic) { get; set; } | Megállapítja, hogy a betűtípus dőlt-e. Nincs öröklődés alkalmazva. Olvasás/írás [`NullableBool`](../nullablebool). |
| [FontUnderline](../../aspose.slides/ibaseportionformat/fontunderline) { get; set; } | Visszaadja vagy beállítja a szöveg aláhúzás típusát. Nincs öröklődés alkalmazva. Olvasás/írás [`TextUnderlineType`](../textunderlinetype). |
| [HighlightColor](../../aspose.slides/ibaseportionformat/highlightcolor) { get; } | Visszaadja a szöveg kiemeléséhez használt színt. Nincs öröklődés alkalmazva. Csak olvasás [`IColorFormat`](../icolorformat). |
| [IsHardUnderlineFill](../../aspose.slides/ibaseportionformat/ishardunderlinefill) { get; set; } | Megállapítja, hogy az aláhúzás stílusnak saját FillFormat tulajdonságai vannak-e, vagy a szöveg FillFormat tulajdonságaiból örököl. Olvasás/írás [`NullableBool`](../nullablebool). |
| [IsHardUnderlineLine](../../aspose.slides/ibaseportionformat/ishardunderlineline) { get; set; } | Megállapítja, hogy az aláhúzás stílusnak saját LineFormat tulajdonságai vannak-e, vagy a szöveg LineFormat tulajdonságaiból örököl. Olvasás/írás [`NullableBool`](../nullablebool). |
| [KerningMinimalSize](../../aspose.slides/ibaseportionformat/kerningminimalsize) { get; set; } | Megállapítja a minimális betűméretet, amelynél a távközelítés (kerning) be kell legyen kapcsolva. **float.NaN** azt jelenti, hogy az érték nincs definiálva, és a Mesterből kell örökölni. Olvasás/írás Single. |
| [Kumimoji](../../aspose.slides/ibaseportionformat/kumimoji) { get; set; } | Megállapítja, hogy a számok figyelmen kívül hagyják-e a szöveg kelet-ázsiai nyelvspecifikus függőleges elrendezését. Nincs öröklődés alkalmazva. Olvasás/írás [`NullableBool`](../nullablebool). |
| [LanguageId](../../aspose.slides/ibaseportionformat/languageid) { get; set; } | Visszaadja vagy beállítja egy helyesírási nyelv azonosítóját. A helyesírás és nyelvtan ellenőrzéséhez használatos. Olvasás/írás String. |
| [LatinFont](../../aspose.slides/ibaseportionformat/latinfont) { get; set; } | Visszaadja vagy beállítja a latin betűtípus információját. A Null azt jelenti, hogy a betűtípus nincs definiálva, és a Mesterből kell örökölni. Olvasás/írás [`IFontData`](../ifontdata). |
| [LineFormat](../../aspose.slides/ibaseportionformat/lineformat) { get; } | Visszaadja a szöveg körvonalazásához szükséges LineFormat tulajdonságokat. Nincs öröklődés alkalmazva. Csak olvasás [`ILineFormat`](../ilineformat). |
| [NormaliseHeight](../../aspose.slides/ibaseportionformat/normaliseheight) { get; set; } | Megállapítja, hogy a szöveg magasságát normalizálni kell-e. Nincs öröklődés alkalmazva. Olvasás/írás [`NullableBool`](../nullablebool). |
| [ProofDisabled](../../aspose.slides/ibaseportionformat/proofdisabled) { get; set; } | Megállapítja, hogy a szöveget ne kell-e helyesírás ellenőrizni. Nincs öröklődés alkalmazva. Olvasás/írás [`NullableBool`](../nullablebool). |
| [Spacing](../../aspose.slides/ibaseportionformat/spacing) { get; set; } | Visszaadja vagy beállítja a karakterek közti távolság növekményét. **float.NaN** azt jelenti, hogy az érték nincs definiálva, és a Mesterből kell örökölni. Olvasás/írás Single. |
| [SpellCheck](../../aspose.slides/ibaseportionformat/spellcheck) { get; set; } | Lekérdezi vagy beállítja, hogy a helyesírás-ellenőrzés engedélyezve van-e a szövegrészhez. Ha ez a tulajdonság hamisra (`false`) van állítva, a szövegelemek helyesírás-ellenőrzése elnyomásra kerül. Ha igazra (`true`) van állítva, a helyesírás-ellenőrzés engedélyezett. Alapértelmezett érték a `false`. |
| [StrikethroughType](../../aspose.slides/ibaseportionformat/strikethroughtype) { get; set; } | Visszaadja vagy beállítja a szöveg áthúzott típusát. Nincs öröklődés alkalmazva. Olvasás/írás [`TextStrikethroughType`](../textstrikethroughtype). |
| [SymbolFont](../../aspose.slides/ibaseportionformat/symbolfont) { get; set; } | Visszaadja vagy beállítja a szimbolikus betűtípus információt. A Null azt jelenti, hogy a betűtípus nincs definiálva, és a Mesterből kell örökölni. Olvasás/írás [`IFontData`](../ifontdata). |
| [TextCapType](../../aspose.slides/ibaseportionformat/textcaptype) { get; set; } | Visszaadja vagy beállítja a szöveg nagybetűsítés típusát. Nincs öröklődés alkalmazva. Olvasás/írás [`TextCapType`](../textcaptype). |
| [UnderlineFillFormat](../../aspose.slides/ibaseportionformat/underlinefillformat) { get; } | Visszaadja az aláhúzási vonal FillFormat tulajdonságait. Nincs öröklődés alkalmazva. Csak olvasás [`IFillFormat`](../ifillformat). |
| [UnderlineLineFormat](../../aspose.slides/ibaseportionformat/underlinelineformat) { get; } | Visszaadja a vonalat körvonalazó LineFormat tulajdonságait. Nincs öröklődés alkalmazva. Csak olvasás [`ILineFormat`](../ilineformat). |

### Megjegyzések

Ez az osztály a konkrét részhez definiált szövegrész formázási tulajdonságok visszaadására és manipulálására szolgál. Ez azt jelenti, hogy az értékek lekérdezésekor nincs öröklődés alkalmazva, így a legtöbb esetben az értékek „nem definiált” jelentéssel bírnak.

Az örökölt értékeket is magában foglaló hatékony formázási paraméterértékek lekéréséhez a [`GetEffective`](../iportionformat/geteffective) metódust kell használni, amely egy [`IPortionFormatEffectiveData`](../iportionformateffectivedata) példányt ad vissza.

### Lásd még

* névtér [Aspose.Slides](../../aspose.slides)
* összeállítás [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->