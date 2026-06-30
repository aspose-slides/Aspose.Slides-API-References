---
title: PortionFormat
second_title: Aspose.Sildes .NET API-referencia
description: Ez az osztály a szövegrész formázási tulajdonságait tartalmazza. Az IPortionFormatEffectiveData./iportionformateffectivedata-vel ellentétben ennek az osztálynak az összes tulajdonsága írható.
type: docs
weight: 9470
url: /hu/aspose.slides/portionformat/
---
## PortionFormat osztály

Ez az osztály a szövegrész formázási tulajdonságait tartalmazza. A [`IPortionFormatEffectiveData`](../iportionformateffectivedata)-tól eltérően, ennek az osztálynak az összes tulajdonsága írható.

```csharp
public sealed class PortionFormat : BasePortionFormat, IPortionFormat
```

## Konstruktorok

| Name | Description |
| --- | --- |
| [PortionFormat](portionformat)() | Új példányt hoz létre a [`PortionFormat`](../portionformat) osztályból. |

## Tulajdonságok

| Name | Description |
| --- | --- |
| [AlternativeLanguageId](../../aspose.slides/baseportionformat/alternativelanguageid) { get; set; } | Visszaadja vagy beállítja egy alternatív nyelv azonosítóját. Olvasás/írás String. |
| [AsIPresentationComponent](../../aspose.slides/pviobject/asipresentationcomponent) { get; } | Lehetővé teszi a base IPresentationComponent interfész lekérését. Csak olvasható [`IPresentationComponent`](../ipresentationcomponent). |
| [BookmarkId](../../aspose.slides/portionformat/bookmarkid) { get; set; } | Visszaadja vagy beállítja a könyvjelző azonosítóját. Olvasás/írás String. |
| [ComplexScriptFont](../../aspose.slides/baseportionformat/complexscriptfont) { get; set; } | Visszaadja vagy beállítja a komplexírás betűtípusinformációt. Null azt jelenti, hogy a betűtípus nincs meghatározva, és a Mesterből öröklődik. Olvasás/írás [`IFontData`](../ifontdata). |
| [EastAsianFont](../../aspose.slides/baseportionformat/eastasianfont) { get; set; } | Visszaadja vagy beállítja a kelet-ázsiai betűtípusinformációt. Null azt jelenti, hogy a betűtípus nincs meghatározva, és a Mesterből öröklődik. Olvasás/írás [`IFontData`](../ifontdata). |
| [EffectFormat](../../aspose.slides/baseportionformat/effectformat) { get; } | Visszaadja a szöveg EffectFormat tulajdonságait. Nem alkalmazódik öröklődés. Csak olvasható [`IEffectFormat`](../ieffectformat). |
| [Escapement](../../aspose.slides/baseportionformat/escapement) { get; set; } | Visszaadja vagy beállítja a felső- vagy alsó index szöveget. Érték -100 % (alsó index) és 100 % (felső index) között. **float.NaN** azt jelenti, hogy az érték nincs meghatározva, és a Mesterből öröklődik. Olvasás/írás Single. |
| [FillFormat](../../aspose.slides/baseportionformat/fillformat) { get; } | Visszaadja a szöveg FillFormat tulajdonságait. Nem alkalmazódik öröklődés. Csak olvasható [`IFillFormat`](../ifillformat). |
| [FontBold](../../aspose.slides/baseportionformat/fontbold) { get; set; } | Meghatározza, hogy a betűk legyenek félkövér. Nem alkalmazódik öröklődés. Olvasás/írás [`NullableBool`](../nullablebool). |
| [FontHeight](../../aspose.slides/baseportionformat/fontheight) { get; set; } | Visszaadja vagy beállítja egy rész betűmagasságát. **float.NaN** azt jelenti, hogy a magasság nincs meghatározva, és a Mesterből öröklődik. Olvasás/írás Single. |
| [FontItalic](../../aspose.slides/baseportionformat/fontitalic) { get; set; } | Meghatározza, hogy a betű dőlt legyen-e. Nem alkalmazódik öröklődés. Olvasás/írás [`NullableBool`](../nullablebool). |
| [FontUnderline](../../aspose.slides/baseportionformat/fontunderline) { get; set; } | Visszaadja vagy beállítja a szöveg aláhúzás típusát. Nem alkalmazódik öröklődés. Olvasás/írás [`TextUnderlineType`](../textunderlinetype). |
| [HighlightColor](../../aspose.slides/baseportionformat/highlightcolor) { get; } | Visszaadja a szöveg kiemeléséhez használt színt. Nem alkalmazódik öröklődés. Csak olvasható [`IColorFormat`](../icolorformat). |
| [HyperlinkClick](../../aspose.slides/portionformat/hyperlinkclick) { get; set; } | Visszaadja vagy beállítja az egérkattintásra definiált hiperhivatkozást. Olvasás/írás [`IHyperlink`](../ihyperlink). |
| [HyperlinkManager](../../aspose.slides/portionformat/hyperlinkmanager) { get; } | Hiperhivatkozások kezelője. Csak olvasható [`IHyperlinkManager`](../ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/portionformat/hyperlinkmouseover) { get; set; } | Visszaadja vagy beállítja az egér fölé mozgatáskor definiált hiperhivatkozást. Olvasás/írás [`IHyperlink`](../ihyperlink). |
| [IsHardUnderlineFill](../../aspose.slides/baseportionformat/ishardunderlinefill) { get; set; } | Meghatározza, hogy az aláhúzás stílusa saját FillFormat tulajdonságokkal rendelkezzen-e, vagy a szöveg FillFormat tulajdonságaiból öröklődjön. Olvasás/írás [`NullableBool`](../nullablebool). |
| [IsHardUnderlineLine](../../aspose.slides/baseportionformat/ishardunderlineline) { get; set; } | Meghatározza, hogy az aláhúzás stílusa saját LineFormat tulajdonságokkal rendelkezzen-e, vagy a szöveg LineFormat tulajdonságaiból öröklődjön. Olvasás/írás [`NullableBool`](../nullablebool). |
| [KerningMinimalSize](../../aspose.slides/baseportionformat/kerningminimalsize) { get; set; } | Visszaadja vagy beállítja a minimális betűméretet, amelynél a kerningnek be kell kapcsolódnia. **float.NaN** azt jelenti, hogy az érték nincs meghatározva, és a Mesterből öröklődik. Olvasás/írás Single. |
| [Kumimoji](../../aspose.slides/baseportionformat/kumimoji) { get; set; } | Meghatározza, hogy a számok figyelmen kívül hagyják-e a keleti nyelv specifikus függőleges elrendezést. Nem alkalmazódik öröklődés. Olvasás/írás [`NullableBool`](../nullablebool). |
| [LanguageId](../../aspose.slides/baseportionformat/languageid) { get; set; } | Visszaadja vagy beállítja egy helyesírási nyelv azonosítóját. A helyesírás- és nyelvtani ellenőrzéshez használják. Olvasás/írás String. |
| [LatinFont](../../aspose.slides/baseportionformat/latinfont) { get; set; } | Visszaadja vagy beállítja a latin betűtípusinformációt. Null azt jelenti, hogy a betűtípus nincs meghatározva, és a Mesterből öröklődik. Olvasás/írás [`IFontData`](../ifontdata). |
| [LineFormat](../../aspose.slides/baseportionformat/lineformat) { get; } | Visszaadja a szöveg körvonalazásához tartozó LineFormat tulajdonságokat. Nem alkalmazódik öröklődés. Csak olvasható [`ILineFormat`](../ilineformat). |
| [NormaliseHeight](../../aspose.slides/baseportionformat/normaliseheight) { get; set; } | Meghatározza, hogy a szöveg magassága normalizálva legyen-e. Nem alkalmazódik öröklődés. Olvasás/írás [`NullableBool`](../nullablebool). |
| [ProofDisabled](../../aspose.slides/baseportionformat/proofdisabled) { get; set; } | Meghatározza, hogy a szöveg ne legyen helyesírás-ellenőrzés alatt. Nem alkalmazódik öröklődés. Olvasás/írás [`NullableBool`](../nullablebool). |
| [SmartTagClean](../../aspose.slides/portionformat/smarttagclean) { get; set; } | Meghatározza, hogy az okoscímke legyen-e tisztítva. Nem alkalmazódik öröklődés. Olvasás/írás Boolean. |
| [Spacing](../../aspose.slides/baseportionformat/spacing) { get; set; } | Visszaadja vagy beállítja a karakterek közötti távolság növelését. **float.NaN** azt jelenti, hogy az érték nincs meghatározva, és a Mesterből öröklődik. Olvasás/írás Single. |
| [SpellCheck](../../aspose.slides/baseportionformat/spellcheck) { get; set; } | Meghatározza, hogy a helyesírás-ellenőrzés be legyen-e kapcsolva a szövegrészhez. Ha ez a tulajdonság false értékre van állítva, a helyesírás-ellenőrzés elmarad a szövegelemeknél. Ha true, a helyesírás-ellenőrzés megengedett. Alapértelmezett érték `false`. |
| [StrikethroughType](../../aspose.slides/baseportionformat/strikethroughtype) { get; set; } | Visszaadja vagy beállítja a szöveg áthúzás típusát. Nem alkalmazódik öröklődés. Olvasás/írás [`TextStrikethroughType`](../textstrikethroughtype). |
| [SymbolFont](../../aspose.slides/baseportionformat/symbolfont) { get; set; } | Visszaadja vagy beállítja a szimbolikus betűtípusinformációt. Null azt jelenti, hogy a betűtípus nincs meghatározva, és a Mesterből öröklődik. Olvasás/írás [`IFontData`](../ifontdata). |
| [TextCapType](../../aspose.slides/baseportionformat/textcaptype) { get; set; } | Visszaadja vagy beállítja a szöveg nagybetűs írásmódját. Nem alkalmazódik öröklődés. Olvasás/írás [`TextCapType`](../textcaptype). |
| [UnderlineFillFormat](../../aspose.slides/baseportionformat/underlinefillformat) { get; } | Visszaadja az aláhúzás vonal FillFormat tulajdonságait. Nem alkalmazódik öröklődés. Csak olvasható [`IFillFormat`](../ifillformat). |
| [UnderlineLineFormat](../../aspose.slides/baseportionformat/underlinelineformat) { get; } | Visszaadja az aláhúzás vonalat körülvevő LineFormat tulajdonságait. Nem alkalmazódik öröklődés. Csak olvasható [`ILineFormat`](../ilineformat). |

## Metódusok

| Name | Description |
| --- | --- |
| override [Equals](../../aspose.slides/pviobject/equals)(object) | Összehasonlítja a megadott objektummal. |
| [GetEffective](../../aspose.slides/portionformat/geteffective)() | Megkapja a rész hatékony formázási adatait a öröklődéssel együtt. |
| override [GetHashCode](../../aspose.slides/pviobject/gethashcode)() | Visszaadja a hash kódot. |

### Megjegyzések

Ez az osztály a konkrét részhez definiált szövegrész formázási tulajdonságok visszaadására és manipulálására szolgál. Ez azt jelenti, hogy értékek lekérésekor nem alkalmazódik öröklődés, ezért a legtöbb esetben „nincs meghatározva” értéket kapunk.

A hatékony formázási paraméterek, beleértve az örökölt értékeket, megszerzéséhez használni kell a [`GetEffective`](./geteffective) metódust, amely egy [`IPortionFormatEffectiveData`](../iportionformateffectivedata) példányt ad vissza.

### Példák

Az alábbi példa azt mutatja, hogyan lehet a Latin betűtípust egy PowerPoint előadás Paragraph részéhez hozzárendelni.

```csharp
[C#]
//Példányosít egy Presentation objektumot, amely egy prezentációs fájlt képvisel
using (Presentation pres = new Presentation("demo.pptx"))
{
IAutoShape shape = pres.Slides[0].Shapes.AddAutoShape(ShapeType.Rectangle, 10, 10, 100, 100);
Paragraph paragraph = new Paragraph();
Portion portion = new Portion("Theme text format");
paragraph.Portions.Add(portion);
shape.TextFrame.Paragraphs.Add(paragraph);
//Az Aspose.Slides ezeket a speciális azonosítókat használja (hasonlóan a PowerPoint-ban használtakhoz):
//+mn-lt - Test betűtípusa Latin (Kisebb Latin betűtípus)
//+mj-lt - Fejléc betűtípusa Latin (Fő Latin betűtípus)
//+mn-ea - Test betűtípusa Kelet-Ázsiai (Kisebb Kelet-Ázsiai betűtípus)
//+mj-ea - Test betűtípusa Kelet-Ázsiai (Kisebb Kelet-Ázsiai betűtípus)
portion.PortionFormat.LatinFont = new FontData("+mn-lt");
}
```

### Lásd még

* osztály [BasePortionFormat](../baseportionformat)
* interfész [IPortionFormat](../iportionformat)
* névtér [Aspose.Slides](../../aspose.slides)
* összeállítás [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->