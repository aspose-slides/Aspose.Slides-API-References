---
title: PortionFormat
second_title: Aspose.Sildes pro .NET referenci API
description: Tato třída obsahuje vlastnosti formátování textových segmentů. Na rozdíl od IPortionFormatEffectiveData./iportionformateffectivedata jsou všechny vlastnosti této třídy zapisovatelné.
type: docs
weight: 9470
url: /cs/aspose.slides/portionformat/
---
## PortionFormat třída

Tato třída obsahuje vlastnosti formátování textových segmentů. Na rozdíl od [`IPortionFormatEffectiveData`](../iportionformateffectivedata) jsou všechny vlastnosti této třídy zapisovatelné.

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
| [AlternativeLanguageId](../../aspose.slides/baseportionformat/alternativelanguageid) { get; set; } | Vrací nebo nastavuje Id alternativního jazyka. Číst/Zapisovat String. |
| [AsIPresentationComponent](../../aspose.slides/pviobject/asipresentationcomponent) { get; } | Umožňuje získat základní rozhraní IPresentationComponent. Pouze pro čtení [`IPresentationComponent`](../ipresentationcomponent). |
| [BookmarkId](../../aspose.slides/portionformat/bookmarkid) { get; set; } | Vrací nebo nastavuje identifikátor záložky. Číst/Zapisovat String. |
| [ComplexScriptFont](../../aspose.slides/baseportionformat/complexscriptfont) { get; set; } | Vrací nebo nastavuje informace o komplexním skriptu písma. Null znamená, že písmo není definováno a mělo by být zděděno z Masteru. Číst/Zapisovat [`IFontData`](../ifontdata). |
| [EastAsianFont](../../aspose.slides/baseportionformat/eastasianfont) { get; set; } | Vrací nebo nastavuje informace o východoasijském písmu. Null znamená, že písmo není definováno a mělo by být zděděno z Masteru. Číst/Zapisovat [`IFontData`](../ifontdata). |
| [EffectFormat](../../aspose.slides/baseportionformat/effectformat) { get; } | Vrací vlastnosti textu EffectFormat. Dědictví se nepoužívá. Pouze pro čtení [`IEffectFormat`](../ieffectformat). |
| [Escapement](../../aspose.slides/baseportionformat/escapement) { get; set; } | Vrací nebo nastavuje text jako horní nebo dolní index. Hodnota od -100 % (dolní index) do 100 % (horní index). **float.NaN** znamená, že hodnota není definována a měla by být zděděna z Masteru. Číst/Zapisovat Single. |
| [FillFormat](../../aspose.slides/baseportionformat/fillformat) { get; } | Vrací vlastnosti FillFormat textu. Dědictví se nepoužívá. Pouze pro čtení [`IFillFormat`](../ifillformat). |
| [FontBold](../../aspose.slides/baseportionformat/fontbold) { get; set; } | Určuje, zda je písmo tučné. Dědictví se nepoužívá. Číst/Zapisovat [`NullableBool`](../nullablebool). |
| [FontHeight](../../aspose.slides/baseportionformat/fontheight) { get; set; } | Vrací nebo nastavuje výšku písma segmentu. **float.NaN** znamená, že výška není definována a měla by být zděděna z Masteru. Číst/Zapisovat Single. |
| [FontItalic](../../aspose.slides/baseportionformat/fontitalic) { get; set; } | Určuje, zda je písmo kurzívou. Dědictví se nepoužívá. Číst/Zapisovat [`NullableBool`](../nullablebool). |
| [FontUnderline](../../aspose.slides/baseportionformat/fontunderline) { get; set; } | Vrací nebo nastavuje typ podtržení textu. Dědictví se nepoužívá. Číst/Zapisovat [`TextUnderlineType`](../textunderlinetype). |
| [HighlightColor](../../aspose.slides/baseportionformat/highlightcolor) { get; } | Vrací barvu použitou pro zvýraznění textu. Dědictví se nepoužívá. Pouze pro čtení [`IColorFormat`](../icolorformat). |
| [HyperlinkClick](../../aspose.slides/portionformat/hyperlinkclick) { get; set; } | Vrací nebo nastavuje hyperodkaz definovaný pro kliknutí myší. Číst/Zapisovat [`IHyperlink`](../ihyperlink). |
| [HyperlinkManager](../../aspose.slides/portionformat/hyperlinkmanager) { get; } | Správce hyperodkazů. Pouze pro čtení [`IHyperlinkManager`](../ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/portionformat/hyperlinkmouseover) { get; set; } | Vrací nebo nastavuje hyperodkaz definovaný pro přejetí myší. Číst/Zapisovat [`IHyperlink`](../ihyperlink). |
| [IsHardUnderlineFill](../../aspose.slides/baseportionformat/ishardunderlinefill) { get; set; } | Určuje, zda má styl podtržení vlastní vlastnosti FillFormat nebo zda je zděděn z vlastností FillFormat textu. Číst/Zapisovat [`NullableBool`](../nullablebool). |
| [IsHardUnderlineLine](../../aspose.slides/baseportionformat/ishardunderlineline) { get; set; } | Určuje, zda má styl podtržení vlastní vlastnosti LineFormat nebo zda je zděděn z vlastností LineFormat textu. Číst/Zapisovat [`NullableBool`](../nullablebool). |
| [KerningMinimalSize](../../aspose.slides/baseportionformat/kerningminimalsize) { get; set; } | Vrací nebo nastavuje minimální velikost písma, při které má být zapnuté kerning. **float.NaN** znamená, že hodnota není definována a měla by být zděděna z Masteru. Číst/Zapisovat Single. |
| [Kumimoji](../../aspose.slides/baseportionformat/kumimoji) { get; set; } | Určuje, zda mají čísla ignorovat specifické vertikální uspořádání textu východoasijských jazyků. Dědictví se nepoužívá. Číst/Zapisovat [`NullableBool`](../nullablebool). |
| [LanguageId](../../aspose.slides/baseportionformat/languageid) { get; set; } | Vrací nebo nastavuje Id jazykové kontroly. Používá se pro kontrolu pravopisu a gramatiky. Číst/Zapisovat String. |
| [LatinFont](../../aspose.slides/baseportionformat/latinfont) { get; set; } | Vrací nebo nastavuje informace o latinském písmu. Null znamená, že písmo není definováno a mělo by být zděděno z Masteru. Číst/Zapisovat [`IFontData`](../ifontdata). |
| [LineFormat](../../aspose.slides/baseportionformat/lineformat) { get; } | Vrací vlastnosti LineFormat pro obrysování textu. Dědictví se nepoužívá. Pouze pro čtení [`ILineFormat`](../ilineformat). |
| [NormaliseHeight](../../aspose.slides/baseportionformat/normaliseheight) { get; set; } | Určuje, zda má být výška textu normalizována. Dědictví se nepoužívá. Číst/Zapisovat [`NullableBool`](../nullablebool). |
| [ProofDisabled](../../aspose.slides/baseportionformat/proofdisabled) { get; set; } | Určuje, zda text nemá být kontrolován. Dědictví se nepoužívá. Číst/Zapisovat [`NullableBool`](../nullablebool). |
| [SmartTagClean](../../aspose.slides/portionformat/smarttagclean) { get; set; } | Určuje, zda má být chytrá značka vyčištěna. Dědictví se nepoužívá. Číst/Zapisovat Boolean. |
| [Spacing](../../aspose.slides/baseportionformat/spacing) { get; set; } | Vrací nebo nastavuje přírůstek mezery mezi znaky. **float.NaN** znamená, že hodnota není definována a měla by být zděděna z Masteru. Číst/Zapisovat Single. |
| [SpellCheck](../../aspose.slides/baseportionformat/spellcheck) { get; set; } | Získává nebo nastavuje hodnotu určující, zda je pro část textu povolena kontrola pravopisu. Když je tato vlastnost nastavena na false, kontrola pravopisu pro textové prvky je potlačena. Když je nastavena na true, kontrola pravopisu je povolena. Výchozí hodnota je `false`. |
| [StrikethroughType](../../aspose.slides/baseportionformat/strikethroughtype) { get; set; } | Vrací nebo nastavuje typ přeškrtnutí textu. Dědictví se nepoužívá. Číst/Zapisovat [`TextStrikethroughType`](../textstrikethroughtype). |
| [SymbolFont](../../aspose.slides/baseportionformat/symbolfont) { get; set; } | Vrací nebo nastavuje informace o symbolickém písmu. Null znamená, že písmo není definováno a mělo by být zděděno z Masteru. Číst/Zapisovat [`IFontData`](../ifontdata). |
| [TextCapType](../../aspose.slides/baseportionformat/textcaptype) { get; set; } | Vrací nebo nastavuje typ kapitalizace textu. Dědictví se nepoužívá. Číst/Zapisovat [`TextCapType`](../textcaptype). |
| [UnderlineFillFormat](../../aspose.slides/baseportionformat/underlinefillformat) { get; } | Vrací vlastnosti FillFormat podtržžové čáry. Dědictví se nepoužívá. Pouze pro čtení [`IFillFormat`](../ifillformat). |
| [UnderlineLineFormat](../../aspose.slides/baseportionformat/underlinelineformat) { get; } | Vrací vlastnosti LineFormat použité k obrysování podtržné čáry. Dědictví se nepoužívá. Pouze pro čtení [`ILineFormat`](../ilineformat). |

## Metody

| Název | Popis |
| --- | --- |
| override [Equals](../../aspose.slides/pviobject/equals)(object) | Porovnává s určeným objektem. |
| [GetEffective](../../aspose.slides/portionformat/geteffective)() | Získává efektivní data formátování segmentu s aplikovaným děděním. |
| override [GetHashCode](../../aspose.slides/pviobject/gethashcode)() | Vrací hash kód. |

### Poznámky

Tato třída se používá k vracení a manipulaci s vlastnostmi formátování textového segmentu definovanými pro konkrétní segment. To znamená, že při získávání hodnot se nepoužije dědictví, takže ve většině případů získáte hodnoty označující „nedefinováno“.

Pro získání efektivních hodnot parametrů formátování včetně zděděných je nutné použít metodu [`GetEffective`](./geteffective), která vrací instance [`IPortionFormatEffectiveData`](../iportionformateffectivedata).

### Příklady

Následující příklad ukazuje, jak přiřadit latinské písmo k segmentu odstavce v PowerPoint prezentaci.

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
//Aspose.Slides používá tyto speciální identifikátory (podobně jako v PowerPointu):
//+mn-lt - Tělo písmo Latin (menší latinské písmo)
//+mj-lt - Nadpisové písmo Latin (větší latinské písmo)
//+mn-ea - Tělo písmo East Asian (menší východoasijské písmo)
//+mj-ea - Tělo písmo East Asian (menší východoasijské písmo)
portion.PortionFormat.LatinFont = new FontData("+mn-lt");
}
```

### Viz také

* třída [BasePortionFormat](../baseportionformat)
* rozhraní [IPortionFormat](../iportionformat)
* jmenný prostor [Aspose.Slides](../../aspose.slides)
* sestavení [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->