---
title: PortionFormat
second_title: Aspose.Slides pro .NET – reference API
description: Tato třída obsahuje vlastnosti formátování textových částí. Na rozdíl od IPortionFormatEffectiveData./iportionformateffectivedata jsou všechny vlastnosti této třídy zapisovatelné.
type: docs
weight: 9490
url: /cs/aspose.slides/portionformat/
---
## PortionFormat třída

Tato třída obsahuje vlastnosti formátování textových částí. Na rozdíl od [`IPortionFormatEffectiveData`](../iportionformateffectivedata) jsou všechny vlastnosti této třídy zapisovatelné.

```csharp
public sealed class PortionFormat : BasePortionFormat, IPortionFormat
```

## Konstruktory

| Název | Popis |
| --- | --- |
| [PortionFormat](portionformat)() | Inicializuje novou instanci třídy [`PortionFormat`](../portionformat). |

## Vlastnosti

| Název | Popis |
| --- | --- |
| [AlternativeLanguageId](../../aspose.slides/baseportionformat/alternativelanguageid) { get; set; } | Vrací nebo nastavuje Id alternativního jazyka. Číst/zapisovat String. |
| [AsIPresentationComponent](../../aspose.slides/pviobject/asipresentationcomponent) { get; } | Umožňuje získat základní rozhraní IPresentationComponent. Pouze pro čtení [`IPresentationComponent`](../ipresentationcomponent). |
| [BookmarkId](../../aspose.slides/portionformat/bookmarkid) { get; set; } | Vrací nebo nastavuje identifikátor záložky. Číst/zapisovat String. |
| [ComplexScriptFont](../../aspose.slides/baseportionformat/complexscriptfont) { get; set; } | Vrací nebo nastavuje informace o fontu pro komplexní skript. Null znamená, že písmo není definováno a mělo by být zděděno z Master. Číst/zapisovat [`IFontData`](../ifontdata). |
| [EastAsianFont](../../aspose.slides/baseportionformat/eastasianfont) { get; set; } | Vrací nebo nastavuje informace o fontu pro východoasijské písmo. Null znamená, že písmo není definováno a mělo by být zděděno z Master. Číst/zapisovat [`IFontData`](../ifontdata). |
| [EffectFormat](../../aspose.slides/baseportionformat/effectformat) { get; } | Vrací vlastnosti textu EffectFormat. Nedědí se. Pouze pro čtení [`IEffectFormat`](../ieffectformat). |
| [Escapement](../../aspose.slides/baseportionformat/escapement) { get; set; } | Vrací nebo nastavuje text horního nebo dolního indexu. Hodnota od -100 % (dolní index) do 100 % (horní index). **float.NaN** znamená, že hodnota není definována a měla by být zděděna z Master. Číst/zapisovat Single. |
| [FillFormat](../../aspose.slides/baseportionformat/fillformat) { get; } | Vrací vlastnosti textu FillFormat. Nedědí se. Pouze pro čtení [`IFillFormat`](../ifillformat). |
| [FontBold](../../aspose.slides/baseportionformat/fontbold) { get; set; } | Určuje, zda je písmo tučné. Nedědí se. Číst/zapisovat [`NullableBool`](../nullablebool). |
| [FontHeight](../../aspose.slides/baseportionformat/fontheight) { get; set; } | Vrací nebo nastavuje výšku písma části. **float.NaN** znamená, že výška není definována a měla by být zděděna z Master. Číst/zapisovat Single. |
| [FontItalic](../../aspose.slides/baseportionformat/fontitalic) { get; set; } | Určuje, zda je písmo kurzíva. Nedědí se. Číst/zapisovat [`NullableBool`](../nullablebool). |
| [FontUnderline](../../aspose.slides/baseportionformat/fontunderline) { get; set; } | Vrací nebo nastavuje typ podtržení textu. Nedědí se. Číst/zapisovat [`TextUnderlineType`](../textunderlinetype). |
| [HighlightColor](../../aspose.slides/baseportionformat/highlightcolor) { get; } | Vrací barvu použité k zvýraznění textu. Nedědí se. Pouze pro čtení [`IColorFormat`](../icolorformat). |
| [HyperlinkClick](../../aspose.slides/portionformat/hyperlinkclick) { get; set; } | Vrací nebo nastavuje hyperodkaz definovaný pro kliknutí myší. Číst/zapisovat [`IHyperlink`](../ihyperlink). |
| [HyperlinkManager](../../aspose.slides/portionformat/hyperlinkmanager) { get; } | Správce hyperodkazů. Pouze pro čtení [`IHyperlinkManager`](../ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/portionformat/hyperlinkmouseover) { get; set; } | Vrací nebo nastavuje hyperodkaz definovaný pro přejetí myší. Číst/zapisovat [`IHyperlink`](../ihyperlink). |
| [IsHardUnderlineFill](../../aspose.slides/baseportionformat/ishardunderlinefill) { get; set; } | Určuje, zda má styl podtržení vlastní vlastnosti FillFormat nebo dědí je z vlastností FillFormat textu. Číst/zapisovat [`NullableBool`](../nullablebool). |
| [IsHardUnderlineLine](../../aspose.slides/baseportionformat/ishardunderlineline) { get; set; } | Určuje, zda má styl podtržení vlastní vlastnosti LineFormat nebo dědí je z vlastností LineFormat textu. Číst/zapisovat [`NullableBool`](../nullablebool). |
| [KerningMinimalSize](../../aspose.slides/baseportionformat/kerningminimalsize) { get; set; } | Vrací nebo nastavuje minimální velikost písma, při které se má zapnout kerning. **float.NaN** znamená, že hodnota není definována a měla by být zděděna z Master. Číst/zapisovat Single. |
| [Kumimoji](../../aspose.slides/baseportionformat/kumimoji) { get; set; } | Určuje, zda čísla mají ignorovat specifické vertikální rozložení východního jazyka textu. Nedědí se. Číst/zapisovat [`NullableBool`](../nullablebool). |
| [LanguageId](../../aspose.slides/baseportionformat/languageid) { get; set; } | Vrací nebo nastavuje Id jazykové kontroly pravopisu. Používá se pro kontrolu pravopisu a gramatiky. Číst/zapisovat String. |
| [LatinFont](../../aspose.slides/baseportionformat/latinfont) { get; set; } | Vrací nebo nastavuje informace o latinském fontu. Null znamená, že písmo není definováno a mělo by být zděděno z Master. Číst/zapisovat [`IFontData`](../ifontdata). |
| [LineFormat](../../aspose.slides/baseportionformat/lineformat) { get; } | Vrací vlastnosti LineFormat pro obrysování textu. Nedědí se. Pouze pro čtení [`ILineFormat`](../ilineformat). |
| [NormaliseHeight](../../aspose.slides/baseportionformat/normaliseheight) { get; set; } | Určuje, zda má být výška textu normalizována. Nedědí se. Číst/zapisovat [`NullableBool`](../nullablebool). |
| [ProofDisabled](../../aspose.slides/baseportionformat/proofdisabled) { get; set; } | Určuje, zda text nemá být kontrolován. Nedědí se. Číst/zapisovat [`NullableBool`](../nullablebool). |
| [SmartTagClean](../../aspose.slides/portionformat/smarttagclean) { get; set; } | Určuje, zda má být inteligentní značka vyčištěna. Nedědí se. Číst/zapisovat Boolean. |
| [Spacing](../../aspose.slides/baseportionformat/spacing) { get; set; } | Vrací nebo nastavuje přírůstek mezery mezi znaky. **float.NaN** znamená, že hodnota není definována a měla by být zděděna z Master. Číst/zapisovat Single. |
| [SpellCheck](../../aspose.slides/baseportionformat/spellcheck) { get; set; } | Vrací nebo nastavuje hodnotu určující, zda je pro část textu povolena kontrola pravopisu. Když je tato vlastnost nastavena na false, kontrola pravopisu pro textové prvky je potlačena. Když je nastavena na true, kontrola pravopisu je povolena. Výchozí hodnota je `false`. |
| [StrikethroughType](../../aspose.slides/baseportionformat/strikethroughtype) { get; set; } | Vrací nebo nastavuje typ přeškrtnutí textu. Nedědí se. Číst/zapisovat [`TextStrikethroughType`](../textstrikethroughtype). |
| [SymbolFont](../../aspose.slides/baseportionformat/symbolfont) { get; set; } | Vrací nebo nastavuje informace o symbolickém fontu. Null znamená, že písmo není definováno a mělo by být zděděno z Master. Číst/zapisovat [`IFontData`](../ifontdata). |
| [TextCapType](../../aspose.slides/baseportionformat/textcaptype) { get; set; } | Vrací nebo nastavuje typ kapitalizace textu. Nedědí se. Číst/zapisovat [`TextCapType`](../textcaptype). |
| [UnderlineFillFormat](../../aspose.slides/baseportionformat/underlinefillformat) { get; } | Vrací vlastnosti FillFormat podtržité čáry. Nedědí se. Pouze pro čtení [`IFillFormat`](../ifillformat). |
| [UnderlineLineFormat](../../aspose.slides/baseportionformat/underlinelineformat) { get; } | Vrací vlastnosti LineFormat použité k obrysování podtržité čáry. Nedědí se. Pouze pro čtení [`ILineFormat`](../ilineformat). |

## Metody

| Název | Popis |
| --- | --- |
| override [Equals](../../aspose.slides/pviobject/equals)(object) | Porovnává s určeným objektem. |
| [GetEffective](../../aspose.slides/portionformat/geteffective)() | Získá efektivní data formátování části s použitým děděním. |
| override [GetHashCode](../../aspose.slides/pviobject/gethashcode)() | Vrací hash kód. |

### Poznámky

Tato třída se používá k vracení a manipulaci s vlastnostmi formátování textové části definovanými pro konkrétní část. To znamená, že při získávání hodnot se nepoužije dědictví, takže ve většině případů získáte hodnoty znamenající „nedefinováno“.

Pro získání efektivních hodnot parametrů formátování včetně zděděných je třeba použít metodu [`GetEffective`](./geteffective), která vrací instanci [`IPortionFormatEffectiveData`](../iportionformateffectivedata).

### Příklady

Následující příklady ukazují, jak přiřadit latinský font k části odstavce prezentace PowerPoint.

```csharp
[C#]
// Vytvořte objekt prezentace, který reprezentuje soubor prezentace
using (Presentation pres = new Presentation("demo.pptx"))
{
IAutoShape shape = pres.Slides[0].Shapes.AddAutoShape(ShapeType.Rectangle, 10, 10, 100, 100);
Paragraph paragraph = new Paragraph();
Portion portion = new Portion("Theme text format");
paragraph.Portions.Add(portion);
shape.TextFrame.Paragraphs.Add(paragraph);
// Aspose.Slides používá tyto speciální identifikátory (podobně jako v PowerPointu):
// +mn-lt - Tělo písma Latin (menší Latin font)
// +mj-lt - Nadpisové písmo Latin (hlavní Latin font)
// +mn-ea - Tělo písma Východní Asie (menší Východní asijské písmo)
// +mj-ea - Tělo písma Východní Asie (menší Východní asijské písmo)
portion.PortionFormat.LatinFont = new FontData("+mn-lt");
}
```

### Viz také

* třída [BasePortionFormat](../baseportionformat)
* rozhraní [IPortionFormat](../iportionformat)
* jmenný prostor [Aspose.Slides](../../aspose.slides)
* sestavení [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->