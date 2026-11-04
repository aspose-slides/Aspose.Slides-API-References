---
title: PortionFormat
second_title: Aspose.Sildes .NET API referencia
description: Ez az osztály tartalmazza a szövegrészlet formázási tulajdonságait. Az IPortionFormatEffectiveData./iportionformateffectivedata-tól eltérően az osztály minden tulajdonsága írható.
type: docs
weight: 9510
url: /hu/aspose.slides/portionformat/
---
## PortionFormat osztály

Ez az osztály a szövegrészlet formázási tulajdonságokat tartalmazza. A [`IPortionFormatEffectiveData`](../iportionformateffectivedata)-tól eltérően az osztály összes tulajdonsága írható.

```csharp
public sealed class PortionFormat : BasePortionFormat, IPortionFormat
```

## Konstruktorok

| Név | Leírás |
| --- | --- |
| [PortionFormat](portionformat)() | Initializes a new instance of [`PortionFormat`](../portionformat) class. |

## Tulajdonságok

| Név | Leírás |
| --- | --- |
| [AlternativeLanguageId](../../aspose.slides/baseportionformat/alternativelanguageid) { get; set; } | Visszaadja vagy beállítja egy alternatív nyelv azonosítóját. Olvasás/írás String. |
| [AsIPresentationComponent](../../aspose.slides/pviobject/asipresentationcomponent) { get; } | Lehetővé teszi a bazális IPresentationComponent interfész lekérését. Csak olvasható [`IPresentationComponent`](../ipresentationcomponent). |
| [BookmarkId](../../aspose.slides/portionformat/bookmarkid) { get; set; } | Visszaadja vagy beállítja a könyvjelző azonosítót. Olvasás/írás String. |
| [ComplexScriptFont](../../aspose.slides/baseportionformat/complexscriptfont) { get; set; } | Visszaadja vagy beállítja a komplex írásrendszer betűtípus információkat. A Null azt jelenti, hogy a betűtípus nincs meghatározva, és a Mesterből kell örökölni. Olvasás/írás [`IFontData`](../ifontdata). |
| [EastAsianFont](../../aspose.slides/baseportionformat/eastasianfont) { get; set; } | Visszaadja vagy beállítja a Kelet-Ázsiai betűtípus információkat. A Null azt jelenti, hogy a betűtípus nincs meghatározva, és a Mesterből kell örökölni. Olvasás/írás [`IFontData`](../ifontdata). |
| [EffectFormat](../../aspose.slides/baseportionformat/effectformat) { get; } | Visszaadja a szöveg EffectFormat tulajdonságait. Nincs öröklődés. Csak olvasható [`IEffectFormat`](../ieffectformat). |
| [Escapement](../../aspose.slides/baseportionformat/escapement) { get; set; } | Visszaadja vagy beállítja a felső- vagy alsó indexú szöveget. Az érték -100% (alsó index) és 100% (felső index) között van. **float.NaN** azt jelenti, hogy az érték nincs meghatározva, és a Mesterből kell örökölni. Olvasás/írás Single. |
| [FillFormat](../../aspose.slides/baseportionformat/fillformat) { get; } | Visszaadja a szöveg FillFormat tulajdonságait. Nincs öröklődés. Csak olvasható [`IFillFormat`](../ifillformat). |
| [FontBold](../../aspose.slides/baseportionformat/fontbold) { get; set; } | Megállapítja, hogy a betűtípus félkövér-e. Nincs öröklődés. Olvasás/írás [`NullableBool`](../nullablebool). |
| [FontHeight](../../aspose.slides/baseportionformat/fontheight) { get; set; } | Visszaadja vagy beállítja egy részlet betűmagasságát. **float.NaN** azt jelenti, hogy a magasság nincs meghatározva, és a Mesterből kell örökölni. Olvasás/írás Single. |
| [FontItalic](../../aspose.slides/baseportionformat/fontitalic) { get; set; } | Megállapítja, hogy a betűtípus dőlt-e. Nincs öröklődés. Olvasás/írás [`NullableBool`](../nullablebool). |
| [FontUnderline](../../aspose.slides/baseportionformat/fontunderline) { get; set; } | Visszaadja vagy beállítja a szöveg aláhúzás típusát. Nincs öröklődés. Olvasás/írás [`TextUnderlineType`](../textunderlinetype). |
| [HighlightColor](../../aspose.slides/baseportionformat/highlightcolor) { get; } | Visszaadja a szöveg kiemeléséhez használt színt. Nincs öröklődés. Csak olvasható [`IColorFormat`](../icolorformat). |
| [HyperlinkClick](../../aspose.slides/portionformat/hyperlinkclick) { get; set; } | Visszaadja vagy beállítja az egérkattintásra definiált hiperhivatkozást. Olvasás/írás [`IHyperlink`](../ihyperlink). |
| [HyperlinkManager](../../aspose.slides/portionformat/hyperlinkmanager) { get; } | Hiperhivatkozások kezelője. Csak olvasható [`IHyperlinkManager`](../ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/portionformat/hyperlinkmouseover) { get; set; } | Visszaadja vagy beállítja az egér ráhúzására definiált hiperhivatkozást. Olvasás/írás [`IHyperlink`](../ihyperlink). |
| [IsHardUnderlineFill](../../aspose.slides/baseportionformat/ishardunderlinefill) { get; set; } | Megállapítja, hogy az aláhúzás stílusának saját FillFormat tulajdonságai vannak-e, vagy a szöveg FillFormat tulajdonságaiból örököl. Olvasás/írás [`NullableBool`](../nullablebool). |
| [IsHardUnderlineLine](../../aspose.slides/baseportionformat/ishardunderlineline) { get; set; } | Megállapítja, hogy az aláhúzás stílusának saját LineFormat tulajdonságai vannak-e, vagy a szöveg LineFormat tulajdonságaiból örököl. Olvasás/írás [`NullableBool`](../nullablebool). |
| [KerningMinimalSize](../../aspose.slides/baseportionformat/kerningminimalsize) { get; set; } | Visszaadja vagy beállítja a minimális betűméretet, amelynél a kerninget be kell kapcsolni. **float.NaN** azt jelenti, hogy az érték nincs meghatározva, és a Mesterből kell örökölni. Olvasás/írás Single. |
| [Kumimoji](../../aspose.slides/baseportionformat/kumimoji) { get; set; } | Megállapítja, hogy a számok figyelmen kívül hagyják-e a kelet-ázsiai nyelvspecifikus függőleges szövegelrendezést. Nincs öröklődés. Olvasás/írás [`NullableBool`](../nullablebool). |
| [LanguageId](../../aspose.slides/baseportionformat/languageid) { get; set; } | Visszaadja vagy beállítja egy helyesírási nyelv azonosítóját. A helyesírás- és nyelvtani ellenőrzéshez használják. Olvasás/írás String. |
| [LatinFont](../../aspose.slides/baseportionformat/latinfont) { get; set; } | Visszaadja vagy beállítja a latin betűtípus információkat. A Null azt jelenti, hogy a betűtípus nincs meghatározva, és a Mesterből kell örökölni. Olvasás/írás [`IFontData`](../ifontdata). |
| [LineFormat](../../aspose.slides/baseportionformat/lineformat) { get; } | Visszaadja a szöveg körvonalazásához tartozó LineFormat tulajdonságokat. Nincs öröklődés. Csak olvasható [`ILineFormat`](../ilineformat). |
| [NormaliseHeight](../../aspose.slides/baseportionformat/normaliseheight) { get; set; } | Megállapítja, hogy a szöveg magasságát normalizálni kell-e. Nincs öröklődés. Olvasás/írás [`NullableBool`](../nullablebool). |
| [ProofDisabled](../../aspose.slides/baseportionformat/proofdisabled) { get; set; } | Megállapítja, hogy a szöveg ne legyen ellenőrizve. Nincs öröklődés. Olvasás/írás [`NullableBool`](../nullablebool). |
| [SmartTagClean](../../aspose.slides/portionformat/smarttagclean) { get; set; } | Megállapítja, hogy a smart tag-et törölni kell-e. Nincs öröklődés. Olvasás/írás Boolean. |
| [Spacing](../../aspose.slides/baseportionformat/spacing) { get; set; } | Visszaadja vagy beállítja a karakterközi távolság növekményét. **float.NaN** azt jelenti, hogy az érték nincs meghatározva, és a Mesterből kell örökölni. Olvasás/írás Single. |
| [SpellCheck](../../aspose.slides/baseportionformat/spellcheck) { get; set; } | Lekérdezi vagy beállítja azt az értéket, amely azt jelzi, hogy a helyesírás-ellenőrzés engedélyezett-e a szövegrészlethez. Ha ez a tulajdonság hamisra van állítva, a szövegelemek helyesírás-ellenőrzése le van tiltva. Igazra állítva a helyesírás-ellenőrzés engedélyezett. Az alapértelmezett érték `false`. |
| [StrikethroughType](../../aspose.slides/baseportionformat/strikethroughtype) { get; set; } | Visszaadja vagy beállítja a szöveg áthúzási típusát. Nincs öröklődés. Olvasás/írás [`TextStrikethroughType`](../textstrikethroughtype). |
| [SymbolFont](../../aspose.slides/baseportionformat/symbolfont) { get; set; } | Visszaadja vagy beállítja a szimbolikus betűtípus információkat. A Null azt jelenti, hogy a betűtípus nincs meghatározva, és a Mesterből kell örökölni. Olvasás/írás [`IFontData`](../ifontdata). |
| [TextCapType](../../aspose.slides/baseportionformat/textcaptype) { get; set; } | Visszaadja vagy beállítja a szöveg nagybetűs átalakításának típusát. Nincs öröklődés. Olvasás/írás [`TextCapType`](../textcaptype). |
| [UnderlineFillFormat](../../aspose.slides/baseportionformat/underlinefillformat) { get; } | Visszaadja az aláhúzó vonal FillFormat tulajdonságait. Nincs öröklődés. Csak olvasható [`IFillFormat`](../ifillformat). |
| [UnderlineLineFormat](../../aspose.slides/baseportionformat/underlinelineformat) { get; } | Visszaadja a vonal kiemeléséhez használt LineFormat tulajdonságokat. Nincs öröklődés. Csak olvasható [`ILineFormat`](../ilineformat). |

## Metódusok

| Név | Leírás |
| --- | --- |
| override [Equals](../../aspose.slides/pviobject/equals)(object) | Összehasonlítja a megadott objektummal. |
| [GetEffective](../../aspose.slides/portionformat/geteffective)() | Lekéri az alkalmazott öröklődéssel ellátott hatékony részletformázási adatokat. |
| override [GetHashCode](../../aspose.slides/pviobject/gethashcode)() | Visszaadja a hash kódot. |

### Megjegyzések

Ez az osztály arra szolgál, hogy visszaadja és manipulálja a konkrét részlethez meghatározott szöveg részletformázási tulajdonságokat. Ez azt jelenti, hogy az értékek lekérésekor nincs öröklődés alkalmazva, így a legtöbb esetben olyan értékeket kapunk, amelyek "nem definiált" jelentést hordoznak. Az öröklődő értékeket is tartalmazó hatékony formázási paraméterek lekéréséhez a [`GetEffective`](./geteffective) metódust kell használni, amely egy [`IPortionFormatEffectiveData`](../iportionformateffectivedata) példányt ad vissza.

### Példák

A következő példák bemutatják, hogyan rendelhetünk latin betűtípust egy Paragraph részlethez egy PowerPoint előadásban.

```csharp
[C#]
//Példányosít egy prezentáció objektumot, amely egy prezentáció fájlt képvisel
using (Presentation pres = new Presentation("demo.pptx"))
{
IAutoShape shape = pres.Slides[0].Shapes.AddAutoShape(ShapeType.Rectangle, 10, 10, 100, 100);
Paragraph paragraph = new Paragraph();
Portion portion = new Portion("Theme text format");
paragraph.Portions.Add(portion);
shape.TextFrame.Paragraphs.Add(paragraph);
//Az Aspose.Slides ezeket a speciális azonosítókat használja (hasonlóan a PowerPointban használtakhoz):
//+mn-lt - Törzsbetű Latin (Kisebb Latin betűtípus)
//+mj-lt - Címsor betűtípusa Latin (Nagy Latin betűtípus)
//+mn-ea - Törzsbetű Kelet-Ázsiai (Kisebb Kelet-Ázsiai betűtípus)
//+mj-ea - Törzsbetű Kelet-Ázsiai (Kisebb Kelet-Ázsiai betűtípus)
portion.PortionFormat.LatinFont = new FontData("+mn-lt");
}
```

### Lásd még

* osztály [BasePortionFormat](../baseportionformat)
* interfész [IPortionFormat](../iportionformat)
* névtér [Aspose.Slides](../../aspose.slides)
* összeállítás [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->