---
title: IBasePortionFormat
second_title: Aspose.Sildes .NET API hivatkozás
description: Ez az osztály tartalmazza a szövegrész formázási tulajdonságait. Az IPortionFormatEffectiveData./iportionformateffectivedata-tól eltérően, ennek az osztálynak az összes tulajdonsága írható.
type: docs
weight: 5310
url: /hu/aspose.slides/ibaseportionformat/
---
## IBasePortionFormat interfész

This class contains the text portion formatting properties. Unlike [`IPortionFormatEffectiveData`](../iportionformateffectivedata), all properties of this class are writeable.

```csharp
public interface IBasePortionFormat
```

## Tulajdonságok

| Név | Leírás |
| --- | --- |
| [AlternativeLanguageId](../../aspose.slides/ibaseportionformat/alternativelanguageid) { get; set; } | Visszaadja vagy beállítja egy alternatív nyelv azonosítóját. Olvasás/írás String. |
| [ComplexScriptFont](../../aspose.slides/ibaseportionformat/complexscriptfont) { get; set; } | Visszaadja vagy beállítja a komplex szkript betűtípus információt. Null azt jelenti, hogy a betűtípus nincs definiálva, és a Mesterből kell örökölni. Olvasás/írás [`IFontData`](../ifontdata). |
| [EastAsianFont](../../aspose.slides/ibaseportionformat/eastasianfont) { get; set; } | Visszaadja vagy beállítja a keleti ázsiai betűtípus információt. Null azt jelenti, hogy a betűtípus nincs definiálva, és a Mesterből kell örökölni. Olvasás/írás [`IFontData`](../ifontdata). |
| [EffectFormat](../../aspose.slides/ibaseportionformat/effectformat) { get; } | Visszaadja a szöveg EffectFormat tulajdonságait. Nincs öröklődés alkalmazva. Csak olvasás [`IEffectFormat`](../ieffectformat). |
| [Escapement](../../aspose.slides/ibaseportionformat/escapement) { get; set; } | Visszaadja vagy beállítja a felső vagy alsó indexű szöveget. Érték -100% (alsó index) és 100% (felső index) között. **float.NaN** azt jelenti, hogy az érték nincs definiálva, és a Mesterből kell örökölni. Olvasás/írás Single. |
| [FillFormat](../../aspose.slides/ibaseportionformat/fillformat) { get; } | Visszaadja a szöveg FillFormat tulajdonságait. Nincs öröklődés alkalmazva. Csak olvasás [`IFillFormat`](../ifillformat). |
| [FontBold](../../aspose.slides/ibaseportionformat/fontbold) { get; set; } | Meghatározza, hogy a betűtípus félkövér-e. Nincs öröklődés alkalmazva. Olvasás/írás [`NullableBool`](../nullablebool). |
| [FontHeight](../../aspose.slides/ibaseportionformat/fontheight) { get; set; } | Visszaadja vagy beállítja egy részlet betűmagasságát. **float.NaN** azt jelenti, hogy a magasság nincs definiálva, és a Mesterből kell örökölni. Olvasás/írás Single. |
| [FontItalic](../../aspose.slides/ibaseportionformat/fontitalic) { get; set; } | Meghatározza, hogy a betűtípus dőlt-e. Nincs öröklődés alkalmazva. Olvasás/írás [`NullableBool`](../nullablebool). |
| [FontUnderline](../../aspose.slides/ibaseportionformat/fontunderline) { get; set; } | Visszaadja vagy beállítja a szöveg aláhúzási típusát. Nincs öröklődés alkalmazva. Olvasás/írás [`TextUnderlineType`](../textunderlinetype). |
| [HighlightColor](../../aspose.slides/ibaseportionformat/highlightcolor) { get; } | Visszaadja a szöveg kiemeléséhez használt színt. Nincs öröklődés alkalmazva. Csak olvasás [`IColorFormat`](../icolorformat). |
| [IsHardUnderlineFill](../../aspose.slides/ibaseportionformat/ishardunderlinefill) { get; set; } | Meghatározza, hogy az aláhúzási stílus saját FillFormat tulajdonságokkal rendelkezik-e, vagy a szöveg FillFormat tulajdonságaiból örököl. Olvasás/írás [`NullableBool`](../nullablebool). |
| [IsHardUnderlineLine](../../aspose.slides/ibaseportionformat/ishardunderlineline) { get; set; } | Meghatározza, hogy az aláhúzási stílus saját LineFormat tulajdonságokkal rendelkezik-e, vagy a szöveg LineFormat tulajdonságaiból örököl. Olvasás/írás [`NullableBool`](../nullablebool). |
| [KerningMinimalSize](../../aspose.slides/ibaseportionformat/kerningminimalsize) { get; set; } | Visszaadja vagy beállítja a minimális betűméretet, amelynél a kernelést be kell kapcsolni. **float.NaN** azt jelenti, hogy az érték nincs definiálva, és a Mesterből kell örökölni. Olvasás/írás Single. |
| [Kumimoji](../../aspose.slides/ibaseportionformat/kumimoji) { get; set; } | Meghatározza, hogy a számok figyelmen kívül hagyják-e a szöveg keleti nyelv-specifikus függőleges elrendezését. Nincs öröklődés alkalmazva. Olvasás/írás [`NullableBool`](../nullablebool). |
| [LanguageId](../../aspose.slides/ibaseportionformat/languageid) { get; set; } | Visszaadja vagy beállítja egy lektorálási nyelv azonosítóját. Helyesírás- és nyelvtanellenőrzés céljából használatos. Olvasás/írás String. |
| [LatinFont](../../aspose.slides/ibaseportionformat/latinfont) { get; set; } | Visszaadja vagy beállítja a latin betűtípus információt. Null azt jelenti, hogy a betűtípus nincs definiálva, és a Mesterből kell örökölni. Olvasás/írás [`IFontData`](../ifontdata). |
| [LineFormat](../../aspose.slides/ibaseportionformat/lineformat) { get; } | Visszaadja a szöveg kontúrjának LineFormat tulajdonságait. Nincs öröklődés alkalmazva. Csak olvasás [`ILineFormat`](../ilineformat). |
| [NormaliseHeight](../../aspose.slides/ibaseportionformat/normaliseheight) { get; set; } | Meghatározza, hogy a szöveg magassága normalizálva legyen-e. Nincs öröklődés alkalmazva. Olvasás/írás [`NullableBool`](../nullablebool). |
| [ProofDisabled](../../aspose.slides/ibaseportionformat/proofdisabled) { get; set; } | Meghatározza, hogy a szöveget ne kelljen lektorálni. Nincs öröklődés alkalmazva. Olvasás/írás [`NullableBool`](../nullablebool). |
| [Spacing](../../aspose.slides/ibaseportionformat/spacing) { get; set; } | Visszaadja vagy beállítja a karakterközök közti növekedést. **float.NaN** azt jelenti, hogy az érték nincs definiálva, és a Mesterből kell örökölni. Olvasás/írás Single. |
| [SpellCheck](../../aspose.slides/ibaseportionformat/spellcheck) { get; set; } | Visszaadja vagy beállítja, hogy a helyesírás-ellenőrzés engedélyezve van-e a szövegrészhez. Ha ez a tulajdonság false, a helyesírás-ellenőrzés a szövegelemeknél le van tiltva. Ha true, a helyesírás-ellenőrzés engedélyezett. Alapértelmezett érték `false`. |
| [StrikethroughType](../../aspose.slides/ibaseportionformat/strikethroughtype) { get; set; } | Visszaadja vagy beállítja a szöveg áthúzási típusát. Nincs öröklődés alkalmazva. Olvasás/írás [`TextStrikethroughType`](../textstrikethroughtype). |
| [SymbolFont](../../aspose.slides/ibaseportionformat/symbolfont) { get; set; } | Visszaadja vagy beállítja a szimbolikus betűtípus információt. Null azt jelenti, hogy a betűtípus nincs definiálva, és a Mesterből kell örökölni. Olvasás/írás [`IFontData`](../ifontdata). |
| [TextCapType](../../aspose.slides/ibaseportionformat/textcaptype) { get; set; } | Visszaadja vagy beállítja a szöveg nagybetűsítésének típusát. Nincs öröklődés alkalmazva. Olvasás/írás [`TextCapType`](../textcaptype). |
| [UnderlineFillFormat](../../aspose.slides/ibaseportionformat/underlinefillformat) { get; } | Visszaadja az aláhúzás vonalának FillFormat tulajdonságait. Nincs öröklődés alkalmazva. Csak olvasás [`IFillFormat`](../ifillformat). |
| [UnderlineLineFormat](../../aspose.slides/ibaseportionformat/underlinelineformat) { get; } | Visszaadja az aláhúzás vonalának kontúrjához használt LineFormat tulajdonságait. Nincs öröklődés alkalmazva. Csak olvasás [`ILineFormat`](../ilineformat). |

### Megjegyzések

Ez az osztály a konkrét szövegrészhez definiált formázási tulajdonságok visszaadására és módosítására szolgál. Ez azt jelenti, hogy értékek lekérésekor nincs öröklődés, így a legtöbb esetben „nem definiált” értékek kapunk.

Az öröklött értékeket is tartalmazó tényleges formázási paraméterekért a [`GetEffective`](../iportionformat/geteffective) metódust kell használni, amely egy [`IPortionFormatEffectiveData`](../iportionformateffectivedata) példányt ad vissza.

### Lásd még

* névtér [Aspose.Slides](../../aspose.slides)
* összeállítás [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->