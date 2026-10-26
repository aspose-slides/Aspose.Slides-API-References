---
title: PortionFormat
second_title: Aspose.Slides .NET API Referencia
description: Ez az osztály a szövegrész formázási tulajdonságait tartalmazza. Az IPortionFormatEffectiveData./iportionformateffectivedata-tól eltérően, ennek az osztálynak az összes tulajdonsága írható.
type: docs
weight: 9490
url: /hu/aspose.slides/portionformat/
---
## PortionFormat osztály

Ez az osztály tartalmazza a szövegrész formázási tulajdonságait. A [`IPortionFormatEffectiveData`](../iportionformateffectivedata)-tól eltérően, ennek az osztálynak az összes tulajdonsága írható.

```csharp
public sealed class PortionFormat : BasePortionFormat, IPortionFormat
```

## Konstruktorok

| Név | Leírás |
| --- | --- |
| [PortionFormat](portionformat)() | Inicializál egy új példányt a [`PortionFormat`](../portionformat) osztályból. |

## Tulajdonságok

| Név | Leírás |
| --- | --- |
| [AlternativeLanguageId](../../aspose.slides/baseportionformat/alternativelanguageid) { get; set; } | Visszaadja vagy beállítja egy alternatív nyelv azonosítóját. Olvasás/írás String. |
| [AsIPresentationComponent](../../aspose.slides/pviobject/asipresentationcomponent) { get; } | Lehetővé teszi a base IPresentationComponent interfész lekérését. Csak olvasás [`IPresentationComponent`](../ipresentationcomponent). |
| [BookmarkId](../../aspose.slides/portionformat/bookmarkid) { get; set; } | Visszaadja vagy beállítja a könyvjelző azonosítóját. Olvasás/írás String. |
| [ComplexScriptFont](../../aspose.slides/baseportionformat/complexscriptfont) { get; set; } | Visszaadja vagy beállítja a komplex írásrendszer betűtípus információt. A Null azt jelenti, hogy a betűtípus nincs meghatározva, és a Masterből kell öröklődni. Olvasás/írás [`IFontData`](../ifontdata). |
| [EastAsianFont](../../aspose.slides/baseportionformat/eastasianfont) { get; set; } | Visszaadja vagy beállítja a kelet-ázsiai betűtípus információt. A Null azt jelenti, hogy a betűtípus nincs meghatározva, és a Masterből kell öröklődni. Olvasás/írás [`IFontData`](../ifontdata). |
| [EffectFormat](../../aspose.slides/baseportionformat/effectformat) { get; } | Visszaadja a szöveg EffectFormat tulajdonságait. Nincs öröklődés. Csak olvasás [`IEffectFormat`](../ieffectformat). |
| [Escapement](../../aspose.slides/baseportionformat/escapement) { get; set; } | Visszaadja vagy beállítja a felső vagy alsó indexű szöveget. Az érték -100% (alsó index) és 100% (felső index) között van. **float.NaN** azt jelenti, hogy az érték nincs meghatározva, és a Masterből kell öröklődni. Olvasás/írás Single. |
| [FillFormat](../../aspose.slides/baseportionformat/fillformat) { get; } | Visszaadja a szöveg FillFormat tulajdonságait. Nincs öröklődés. Csak olvasás [`IFillFormat`](../ifillformat). |
| [FontBold](../../aspose.slides/baseportionformat/fontbold) { get; set; } | Megállapítja, hogy a betűtípus félkövér-e. Nincs öröklődés. Olvasás/írás [`NullableBool`](../nullablebool). |
| [FontHeight](../../aspose.slides/baseportionformat/fontheight) { get; set; } | Visszaadja vagy beállítja egy rész betűmagasságát. **float.NaN** azt jelenti, hogy a magasság nincs meghatározva, és a Masterből kell öröklődni. Olvasás/írás Single. |
| [FontItalic](../../aspose.slides/baseportionformat/fontitalic) { get; set; } | Megállapítja, hogy a betűtípus dőlt-e. Nincs öröklődés. Olvasás/írás [`NullableBool`](../nullablebool). |
| [FontUnderline](../../aspose.slides/baseportionformat/fontunderline) { get; set; } | Visszaadja vagy beállítja a szöveg aláhúzási típusát. Nincs öröklődés. Olvasás/írás [`TextUnderlineType`](../textunderlinetype). |
| [HighlightColor](../../aspose.slides/baseportionformat/highlightcolor) { get; } | Visszaadja a szöveg kiemeléséhez használt színt. Nincs öröklődés. Csak olvasás [`IColorFormat`](../icolorformat). |
| [HyperlinkClick](../../aspose.slides/portionformat/hyperlinkclick) { get; set; } | Visszaadja vagy beállítja az egérkattintásra definiált hiperhivatkozást. Olvasás/írás [`IHyperlink`](../ihyperlink). |
| [HyperlinkManager](../../aspose.slides/portionformat/hyperlinkmanager) { get; } | Hiperhivatkozások kezelője. Csak olvasás [`IHyperlinkManager`](../ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/portionformat/hyperlinkmouseover) { get; set; } | Visszaadja vagy beállítja az egér fölé mozgatására definiált hiperhivatkozást. Olvasás/írás [`IHyperlink`](../ihyperlink). |
| [IsHardUnderlineFill](../../aspose.slides/baseportionformat/ishardunderlinefill) { get; set; } | Megállapítja, hogy az aláhúzás stílusnak saját FillFormat tulajdonságai vannak-e, vagy a szöveg FillFormat tulajdonságaiból örököl. Olvasás/írás [`NullableBool`](../nullablebool). |
| [IsHardUnderlineLine](../../aspose.slides/baseportionformat/ishardunderlineline) { get; set; } | Megállapítja, hogy az aláhúzás stílusnak saját LineFormat tulajdonságai vannak-e, vagy a szöveg LineFormat tulajdonságaiból örököl. Olvasás/írás [`NullableBool`](../nullablebool). |
| [KerningMinimalSize](../../aspose.slides/baseportionformat/kerningminimalsize) { get; set; } | Visszaadja vagy beállítja a minimális betűméretet, amelynél a kerningnek be kellene kapcsolnia. **float.NaN** azt jelenti, hogy az érték nincs meghatározva, és a Masterből kell öröklődni. Olvasás/írás Single. |
| [Kumimoji](../../aspose.slides/baseportionformat/kumimoji) { get; set; } | Megállapítja, hogy a számok figyelmen kívül hagyják-e a szöveg kelet-ázsiai nyelvspecifikus függőleges elrendezését. Nincs öröklődés. Olvasás/írás [`NullableBool`](../nullablebool). |
| [LanguageId](../../aspose.slides/baseportionformat/languageid) { get; set; } | Visszaadja vagy beállítja egy helyesírási nyelv azonosítóját. Helyesírás és nyelvtan ellenőrzéséhez használják. Olvasás/írás String. |
| [LatinFont](../../aspose.slides/baseportionformat/latinfont) { get; set; } | Visszaadja vagy beállítja a latin betűtípus információt. A Null azt jelenti, hogy a betűtípus nincs meghatározva, és a Masterből kell öröklődni. Olvasás/írás [`IFontData`](../ifontdata). |
| [LineFormat](../../aspose.slides/baseportionformat/lineformat) { get; } | Visszaadja a szöveg körvonalazásához szükséges LineFormat tulajdonságokat. Nincs öröklődés. Csak olvasás [`ILineFormat`](../ilineformat). |
| [NormaliseHeight](../../aspose.slides/baseportionformat/normaliseheight) { get; set; } | Megállapítja, hogy a szöveg magasságát normalizálni kell-e. Nincs öröklődés. Olvasás/írás [`NullableBool`](../nullablebool). |
| [ProofDisabled](../../aspose.slides/baseportionformat/proofdisabled) { get; set; } | Megállapítja, hogy a szöveget ne ellenőrizzék helyesírásra. Nincs öröklődés. Olvasás/írás [`NullableBool`](../nullablebool). |
| [SmartTagClean](../../aspose.slides/portionformat/smarttagclean) { get; set; } | Megállapítja, hogy az okos címkét tisztítani kell-e. Nincs öröklődés. Olvasás/írás Boolean. |
| [Spacing](../../aspose.slides/baseportionformat/spacing) { get; set; } | Visszaadja vagy beállítja a karakterek közötti távolság növekményét. **float.NaN** azt jelenti, hogy az érték nincs meghatározva, és a Masterből kell öröklődni. Olvasás/írás Single. |
| [SpellCheck](../../aspose.slides/baseportionformat/spellcheck) { get; set; } | Beállítja vagy visszaadja, hogy a helyesírás-ellenőrzés engedélyezett-e a szövegrészhez. Ha ez a tulajdonság false, a helyesírás-ellenőrzés a szövegelemekhez elnyomásra kerül. Ha true, a helyesírás-ellenőrzés engedélyezett. Az alapértelmezett érték `false`. |
| [StrikethroughType](../../aspose.slides/baseportionformat/strikethroughtype) { get; set; } | Visszaadja vagy beállítja a szöveg áthúzási típusát. Nincs öröklődés. Olvasás/írás [`TextStrikethroughType`](../textstrikethroughtype). |
| [SymbolFont](../../aspose.slides/baseportionformat/symbolfont) { get; set; } | Visszaadja vagy beállítja a szimbolikus betűtípus információt. A Null azt jelenti, hogy a betűtípus nincs meghatározva, és a Masterből kell öröklődni. Olvasás/írás [`IFontData`](../ifontdata). |
| [TextCapType](../../aspose.slides/baseportionformat/textcaptype) { get; set; } | Visszaadja vagy beállítja a szöveg nagybetűsítés típusát. Nincs öröklődés. Olvasás/írás [`TextCapType`](../textcaptype). |
| [UnderlineFillFormat](../../aspose.slides/baseportionformat/underlinefillformat) { get; } | Visszaadja az aláhúzás vonal FillFormat tulajdonságait. Nincs öröklődés. Csak olvasás [`IFillFormat`](../ifillformat). |
| [UnderlineLineFormat](../../aspose.slides/baseportionformat/underlinelineformat) { get; } | Visszaadja a LineFormat tulajdonságokat, amelyeket az aláhúzás vonal körvonalazásához használnak. Nincs öröklődés. Csak olvasás [`ILineFormat`](../ilineformat). |

## Metódusok

| Név | Leírás |
| --- | --- |
| override [Equals](../../aspose.slides/pviobject/equals)(object) | Összehasonlítja a megadott objektummal. |
| [GetEffective](../../aspose.slides/portionformat/geteffective)() | Lekéri a hatékony részformázási adatokat az alkalmazott öröklődéssel. |
| override [GetHashCode](../../aspose.slides/pviobject/gethashcode)() | Visszaadja a hash kódot. |

### Megjegyzések

Ez az osztály a szövegrész formázási tulajdonságainak visszaadására és módosítására szolgál, amelyek egy adott részhez vannak definiálva. Ez azt jelenti, hogy az értékek lekérésekor nincs öröklődés, ezért a legtöbb esetben olyan értékeket kapunk, amelyek jelentése „nem definiált”.

Az örökölt értékeket is tartalmazó hatékony formázási paraméterek lekéréséhez a [`GetEffective`](./geteffective) metódust kell használni, amely egy [`IPortionFormatEffectiveData`](../iportionformateffectivedata) példányt ad vissza.

### Példák

A következő példák bemutatják, hogyan kell a latin betűtípust a PowerPoint prezentáció egy bekezdésének részéhez hozzárendelni.

```csharp
[C#]
// Egy prezentáció objektum példányosítása, amely egy prezentációs fájlt képvisel
using (Presentation pres = new Presentation("demo.pptx"))
{
IAutoShape shape = pres.Slides[0].Shapes.AddAutoShape(ShapeType.Rectangle, 10, 10, 100, 100);
Paragraph paragraph = new Paragraph();
Portion portion = new Portion("Theme text format");
paragraph.Portions.Add(portion);
shape.TextFrame.Paragraphs.Add(paragraph);
// Az Aspose.Slides ezeket a speciális azonosítókat használja (hasonlóan a PowerPoint-hoz):
// +mn-lt - Test betűtípus Latin (Kisebb Latin betűtípus)
// +mj-lt - Címsor betűtípus Latin (Nagy Latin betűtípus)
// +mn-ea - Test betűtípus Kelet-Ázsiai (Kisebb Kelet-Ázsiai betűtípus)
// +mj-ea - Test betűtípus Kelet-Ázsiai (Kisebb Kelet-Ázsiai betűtípus)
portion.PortionFormat.LatinFont = new FontData("+mn-lt");
}
```

### Lásd még

* osztály [BasePortionFormat](../baseportionformat)
* interfész [IPortionFormat](../iportionformat)
* névtér [Aspose.Slides](../../aspose.slides)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->