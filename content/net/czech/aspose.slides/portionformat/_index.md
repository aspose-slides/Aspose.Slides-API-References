---
title: PortionFormat
second_title: Aspose.Sildes pro .NET API Reference
description: Tato třída obsahuje vlastnosti formátování textových částí. Na rozdíl od IPortionFormatEffectiveData./iportionformateffectivedata jsou všechny vlastnosti této třídy zapisovatelné.
type: docs
weight: 9510
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
| [AlternativeLanguageId](../../aspose.slides/baseportionformat/alternativelanguageid) { get; set; } | Vrátí nebo nastaví Id alternativního jazyka. Čtení/zápis String. |
| [AsIPresentationComponent](../../aspose.slides/pviobject/asipresentationcomponent) { get; } | Umožňuje získat základní rozhraní IPresentationComponent. Pouze pro čtení [`IPresentationComponent`](../ipresentationcomponent). |
| [BookmarkId](../../aspose.slides/portionformat/bookmarkid) { get; set; } | Vrátí nebo nastaví identifikátor záložky. Čtení/zápis String. |
| [ComplexScriptFont](../../aspose.slides/baseportionformat/complexscriptfont) { get; set; } | Vrátí nebo nastaví informace o písmu pro složité skripty. Null znamená, že písmo není definováno a mělo by být zděděno z Master. Čtení/zápis [`IFontData`](../ifontdata). |
| [EastAsianFont](../../aspose.slides/baseportionformat/eastasianfont) { get; set; } | Vrátí nebo nastaví informace o písmu pro východoasijské jazyky. Null znamená, že písmo není definováno a mělo by být zděděno z Master. Čtení/zápis [`IFontData`](../ifontdata). |
| [EffectFormat](../../aspose.slides/baseportionformat/effectformat) { get; } | Vrátí vlastnosti EffectFormat textu. Nedědí se. Pouze pro čtení [`IEffectFormat`](../ieffectformat). |
| [Escapement](../../aspose.slides/baseportionformat/escapement) { get; set; } | Vrátí nebo nastaví text jako horní index nebo dolní index. Hodnota od -100% (dolní index) do 100% (horní index). **float.NaN** znamená, že hodnota není definována a měla by být zděděna z Master. Čtení/zápis Single. |
| [FillFormat](../../aspose.slides/baseportionformat/fillformat) { get; } | Vrátí vlastnosti FillFormat textu. Nedědí se. Pouze pro čtení [`IFillFormat`](../ifillformat). |
| [FontBold](../../aspose.slides/baseportionformat/fontbold) { get; set; } | Určuje, zda je písmo tučné. Nedědí se. Čtení/zápis [`NullableBool`](../nullablebool). |
| [FontHeight](../../aspose.slides/baseportionformat/fontheight) { get; set; } | Vrátí nebo nastaví výšku písma části. **float.NaN** znamená, že výška není definována a měla by být zděděna z Master. Čtení/zápis Single. |
| [FontItalic](../../aspose.slides/baseportionformat/fontitalic) { get; set; } | Určuje, zda je písmo itallic. Nedědí se. Čtení/zápis [`NullableBool`](../nullablebool). |
| [FontUnderline](../../aspose.slides/baseportionformat/fontunderline) { get; set; } | Vrátí nebo nastaví typ podtržení textu. Nedědí se. Čtení/zápis [`TextUnderlineType`](../textunderlinetype). |
| [HighlightColor](../../aspose.slides/baseportionformat/highlightcolor) { get; } | Vrátí barvu použitou k zvýraznění textu. Nedědí se. Pouze pro čtení [`IColorFormat`](../icolorformat). |
| [HyperlinkClick](../../aspose.slides/portionformat/hyperlinkclick) { get; set; } | Vrátí nebo nastaví hypertextový odkaz definovaný pro kliknutí myší. Čtení/zápis [`IHyperlink`](../ihyperlink). |
| [HyperlinkManager](../../aspose.slides/portionformat/hyperlinkmanager) { get; } | Správce hypertextových odkazů. Pouze pro čtení [`IHyperlinkManager`](../ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/portionformat/hyperlinkmouseover) { get; set; } | Vrátí nebo nastaví hypertextový odkaz definovaný pro přechod myší. Čtení/zápis [`IHyperlink`](../ihyperlink). |
| [IsHardUnderlineFill](../../aspose.slides/baseportionformat/ishardunderlinefill) { get; set; } | Určuje, zda má styl podtržení vlastní vlastnosti FillFormat nebo je dědí z vlastností FillFormat textu. Čtení/zápis [`NullableBool`](../nullablebool). |
| [IsHardUnderlineLine](../../aspose.slides/baseportionformat/ishardunderlineline) { get; set; } | Určuje, zda má styl podtržení vlastní vlastnosti LineFormat nebo je dědí z vlastností LineFormat textu. Čtení/zápis [`NullableBool`](../nullablebool). |
| [KerningMinimalSize](../../aspose.slides/baseportionformat/kerningminimalsize) { get; set; } | Vrátí nebo nastaví minimální velikost písma, pro kterou by měl být zapnut kerning. **float.NaN** znamená, že hodnota není definována a měla by být zděděna z Master. Čtení/zápis Single. |
| [Kumimoji](../../aspose.slides/baseportionformat/kumimoji) { get; set; } | Určuje, zda mají čísla ignorovat specifické svislé rozložení textu pro východoasijské jazyky. Nedědí se. Čtení/zápis [`NullableBool`](../nullablebool). |
| [LanguageId](../../aspose.slides/baseportionformat/languageid) { get; set; } | Vrátí nebo nastaví Id jazykové kontroly. Používá se pro kontrolu pravopisu a grammatiky. Čtení/zápis String. |
| [LatinFont](../../aspose.slides/baseportionformat/latinfont) { get; set; } | Vrátí nebo nastaví informace o latinském písmu. Null znamená, že písmo není definováno a mělo by být zděděno z Master. Čtení/zápis [`IFontData`](../ifontdata). |
| [LineFormat](../../aspose.slides/baseportionformat/lineformat) { get; } | Vrátí vlastnosti LineFormat pro obrys textu. Nedědí se. Pouze pro čtení [`ILineFormat`](../ilineformat). |
| [NormaliseHeight](../../aspose.slides/baseportionformat/normaliseheight) { get; set; } | Určuje, zda má být výška textu normalizována. Nedědí se. Čtení/zápis [`NullableBool`](../nullablebool). |
| [ProofDisabled](../../aspose.slides/baseportionformat/proofdisabled) { get; set; } | Určuje, zda text nemá být kontrolován. Nedědí se. Čtení/zápis [`NullableBool`](../nullablebool). |
| [SmartTagClean](../../aspose.slides/portionformat/smarttagclean) { get; set; } | Určuje, zda má být inteligentní značka vyčištěna. Nedědí se. Čtení/zápis Boolean. |
| [Spacing](../../aspose.slides/baseportionformat/spacing) { get; set; } | Vrátí nebo nastaví přírůstek mezery mezi znaky. **float.NaN** znamená, že hodnota není definována a měla by být zděděna z Master. Čtení/zápis Single. |
| [SpellCheck](../../aspose.slides/baseportionformat/spellcheck) { get; set; } | Získá nebo nastaví hodnotu určující, zda je pro část textu povolena kontrola pravopisu. Pokud je tato vlastnost nastavena na false, kontroly pravopisu pro textové prvky jsou potlačeny. Pokud je nastavena na true, kontrola pravopisu je povolena. Výchozí hodnota je `false`. |
| [StrikethroughType](../../aspose.slides/baseportionformat/strikethroughtype) { get; set; } | Vrátí nebo nastaví typ přeškrtnutí textu. Nedědí se. Čtení/zápis [`TextStrikethroughType`](../textstrikethroughtype). |
| [SymbolFont](../../aspose.slides/baseportionformat/symbolfont) { get; set; } | Vrátí nebo nastaví informace o symbolickém písmu. Null znamená, že písmo není definováno a mělo by být zděděno z Master. Čtení/zápis [`IFontData`](../ifontdata). |
| [TextCapType](../../aspose.slides/baseportionformat/textcaptype) { get; set; } | Vrátí nebo nastaví typ kapitalizace textu. Nedědí se. Čtení/zápis [`TextCapType`](../textcaptype). |
| [UnderlineFillFormat](../../aspose.slides/baseportionformat/underlinefillformat) { get; } | Vrátí vlastnosti FillFormat podtržité čáry. Nedědí se. Pouze pro čtení [`IFillFormat`](../ifillformat). |
| [UnderlineLineFormat](../../aspose.slides/baseportionformat/underlinelineformat) { get; } | Vrátí vlastnosti LineFormat použité pro obrys podtržené čáry. Nedědí se. Pouze pro čtení [`ILineFormat`](../ilineformat). |

## Metody

| Název | Popis |
| --- | --- |
| override [Equals](../../aspose.slides/pviobject/equals)(object) | Porovná s určeným objektem. |
| [GetEffective](../../aspose.slides/portionformat/geteffective)() | Získá efektivní data formátování části s použitým děděním. |
| override [GetHashCode](../../aspose.slides/pviobject/gethashcode)() | Vrátí hash kód. |

### Poznámky

Tato třída se používá k vracení a manipulaci s vlastnostmi formátování textové části definovanými pro konkrétní část. To znamená, že při získávání hodnot se nedědí, takže ve většině případů získáte hodnoty označující „nedefinováno“.

Pro získání efektivních hodnot parametrů formátování včetně zděděných je třeba použít metodu [`GetEffective`](./geteffective), která vrací instanci [`IPortionFormatEffectiveData`](../iportionformateffectivedata).

### Příklady

Následující příklady ukazují, jak přiřadit latinské písmo k části odstavce v prezentaci PowerPoint.

```csharp
[C#]
//Vytvořte objekt prezentace, který představuje soubor prezentace
using (Presentation pres = new Presentation("demo.pptx"))
{
IAutoShape shape = pres.Slides[0].Shapes.AddAutoShape(ShapeType.Rectangle, 10, 10, 100, 100);
Paragraph paragraph = new Paragraph();
Portion portion = new Portion("Theme text format");
paragraph.Portions.Add(portion);
shape.TextFrame.Paragraphs.Add(paragraph);
// Aspose.Slides používá tyto speciální identifikátory (podobně jako v PowerPointu):
// +mn-lt - Písmo těla Latin (menší latinské písmo)
// +mj-lt - Písmo nadpisu Latin (větší latinské písmo)
// +mn-ea - Písmo těla East Asian (menší východoasijské písmo)
// +mj-ea - Písmo těla East Asian (menší východoasijské písmo)
portion.PortionFormat.LatinFont = new FontData("+mn-lt");
}
```

### Viz také

* třída [BasePortionFormat](../baseportionformat)
* rozhraní [IPortionFormat](../iportionformat)
* jmenný prostor [Aspose.Slides](../../aspose.slides)
* sestavení [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->