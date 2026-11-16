---
title: IBasePortionFormat
second_title: Aspose.Sildes pro .NET – referenční příručka API
description: Tato třída obsahuje vlastnosti formátování textového úseku. Na rozdíl od IPortionFormatEffectiveData./iportionformateffectivedata jsou všechny vlastnosti této třídy zapisovatelné.
type: docs
weight: 5330
url: /cs/aspose.slides/ibaseportionformat/
---
## IBasePortionFormat rozhraní

Tato třída obsahuje vlastnosti formátování textového úseku. Na rozdíl od [`IPortionFormatEffectiveData`](../iportionformateffectivedata) jsou všechny vlastnosti této třídy zapisovatelné.

```csharp
public interface IBasePortionFormat
```

## Vlastnosti

| Název | Popis |
| --- | --- |
| [AlternativeLanguageId](../../aspose.slides/ibaseportionformat/alternativelanguageid) { get; set; } | Vrací nebo nastavuje Id alternativního jazyka. Čtení/zápis String. |
| [ComplexScriptFont](../../aspose.slides/ibaseportionformat/complexscriptfont) { get; set; } | Vrací nebo nastavuje informace o písmu složitého skriptu. Null znamená, že písmo není definováno a mělo by být zděděno z hlavního objektu. Čtení/zápis [`IFontData`](../ifontdata). |
| [EastAsianFont](../../aspose.slides/ibaseportionformat/eastasianfont) { get; set; } | Vrací nebo nastavuje informace o východoasijském písmu. Null znamená, že písmo není definováno a mělo by být zděděno z hlavního objektu. Čtení/zápis [`IFontData`](../ifontdata). |
| [EffectFormat](../../aspose.slides/ibaseportionformat/effectformat) { get; } | Vrací vlastnosti EffectFormat textu. Žádné dědictví se neuplatňuje. Pouze pro čtení [`IEffectFormat`](../ieffectformat). |
| [Escapement](../../aspose.slides/ibaseportionformat/escapement) { get; set; } | Vrací nebo nastavuje text horního nebo dolního indexu. Hodnota od -100 % (dolní index) do 100 % (horní index). **float.NaN** znamená, že hodnota není definována a měla by být zděděna z hlavního objektu. Čtení/zápis Single. |
| [FillFormat](../../aspose.slides/ibaseportionformat/fillformat) { get; } | Vrací vlastnosti FillFormat textu. Žádné dědictví se neuplatňuje. Pouze pro čtení [`IFillFormat`](../ifillformat). |
| [FontBold](../../aspose.slides/ibaseportionformat/fontbold) { get; set; } | Určuje, zda je písmo tučné. Žádné dědictví se neuplatňuje. Čtení/zápis [`NullableBool`](../nullablebool). |
| [FontHeight](../../aspose.slides/ibaseportionformat/fontheight) { get; set; } | Vrací nebo nastavuje výšku písma úseku. **float.NaN** znamená, že výška není definována a měla by být zděděna z hlavního objektu. Čtení/zápis Single. |
| [FontItalic](../../aspose.slides/ibaseportionformat/fontitalic) { get; set; } | Určuje, zda je písmo kurzívou. Žádné dědictví se neuplatňuje. Čtení/zápis [`NullableBool`](../nullablebool). |
| [FontUnderline](../../aspose.slides/ibaseportionformat/fontunderline) { get; set; } | Vrací nebo nastavuje typ podtržení textu. Žádné dědictví se neuplatňuje. Čtení/zápis [`TextUnderlineType`](../textunderlinetype). |
| [HighlightColor](../../aspose.slides/ibaseportionformat/highlightcolor) { get; } | Vrací barvu použitou pro zvýraznění textu. Žádné dědictví se neuplatňuje. Pouze pro čtení [`IColorFormat`](../icolorformat). |
| [IsHardUnderlineFill](../../aspose.slides/ibaseportionformat/ishardunderlinefill) { get; set; } | Určuje, zda má styl podtržení vlastní vlastnosti FillFormat nebo je zdědí z vlastností FillFormat textu. Čtení/zápis [`NullableBool`](../nullablebool). |
| [IsHardUnderlineLine](../../aspose.slides/ibaseportionformat/ishardunderlineline) { get; set; } | Určuje, zda má styl podtržení vlastní vlastnosti LineFormat nebo je zdědí z vlastností LineFormat textu. Čtení/zápis [`NullableBool`](../nullablebool). |
| [KerningMinimalSize](../../aspose.slides/ibaseportionformat/kerningminimalsize) { get; set; } | Vrací nebo nastavuje minimální velikost písma, při které se má zapnout kerning. **float.NaN** znamená, že hodnota není definována a měla by být zděděna z hlavního objektu. Čtení/zápis Single. |
| [Kumimoji](../../aspose.slides/ibaseportionformat/kumimoji) { get; set; } | Určuje, zda mají čísla ignorovat specifické vertikální rozvržení východních jazyků textu. Žádné dědictví se neuplatňuje. Čtení/zápis [`NullableBool`](../nullablebool). |
| [LanguageId](../../aspose.slides/ibaseportionformat/languageid) { get; set; } | Vrací nebo nastavuje Id jazykové kontroly pravopisu. Používá se pro kontrolu pravopisu a gramatiky. Čtení/zápis String. |
| [LatinFont](../../aspose.slides/ibaseportionformat/latinfont) { get; set; } | Vrací nebo nastavuje informace o latinském písmu. Null znamená, že písmo není definováno a mělo by být zděděno z hlavního objektu. Čtení/zápis [`IFontData`](../ifontdata). |
| [LineFormat](../../aspose.slides/ibaseportionformat/lineformat) { get; } | Vrací vlastnosti LineFormat pro obrysování textu. Žádné dědictví se neuplatňuje. Pouze pro čtení [`ILineFormat`](../ilineformat). |
| [NormaliseHeight](../../aspose.slides/ibaseportionformat/normaliseheight) { get; set; } | Určuje, zda má být výška textu normalizována. Žádné dědictví se neuplatňuje. Čtení/zápis [`NullableBool`](../nullablebool). |
| [ProofDisabled](../../aspose.slides/ibaseportionformat/proofdisabled) { get; set; } | Určuje, zda text nemá být kontrolován. Žádné dědictví se neuplatňuje. Čtení/zápis [`NullableBool`](../nullablebool). |
| [Spacing](../../aspose.slides/ibaseportionformat/spacing) { get; set; } | Vrací nebo nastavuje přírůstek mezery mezi znaky. **float.NaN** znamená, že hodnota není definována a měla by být zděděna z hlavního objektu. Čtení/zápis Single. |
| [SpellCheck](../../aspose.slides/ibaseportionformat/spellcheck) { get; set; } | Získává nebo nastavuje hodnotu určující, zda je pro úsek textu povolena kontrola pravopisu. Když je tato vlastnost nastavena na false, kontrola pravopisu pro textové prvky je potlačena. Když je nastavena na true, kontrola pravopisu je povolena. Výchozí hodnota je `false`. |
| [StrikethroughType](../../aspose.slides/ibaseportionformat/strikethroughtype) { get; set; } | Vrací nebo nastavuje typ přeškrtnutí textu. Žádné dědictví se neuplatňuje. Čtení/zápis [`TextStrikethroughType`](../textstrikethroughtype). |
| [SymbolFont](../../aspose.slides/ibaseportionformat/symbolfont) { get; set; } | Vrací nebo nastavuje informace o symbolickém písmu. Null znamená, že písmo není definováno a mělo by být zděděno z hlavního objektu. Čtení/zápis [`IFontData`](../ifontdata). |
| [TextCapType](../../aspose.slides/ibaseportionformat/textcaptype) { get; set; } | Vrací nebo nastavuje typ kapitalizace textu. Žádné dědictví se neuplatňuje. Čtení/zápis [`TextCapType`](../textcaptype). |
| [UnderlineFillFormat](../../aspose.slides/ibaseportionformat/underlinefillformat) { get; } | Vrací vlastnosti FillFormat podtržité čáry. Žádné dědictví se neuplatňuje. Pouze pro čtení [`IFillFormat`](../ifillformat). |
| [UnderlineLineFormat](../../aspose.slides/ibaseportionformat/underlinelineformat) { get; } | Vrací vlastnosti LineFormat použité k obrysování podtržité čáry. Žádné dědictví se neuplatňuje. Pouze pro čtení [`ILineFormat`](../ilineformat). |

### Poznámky

Tato třída se používá k vracení a manipulaci s vlastnostmi formátování textového úseku definovanými pro konkrétní úsek. To znamená, že při získávání hodnot se nepoužije žádné dědictví, takže ve většině případů získáte hodnoty označující „nedefinováno“.

Pro získání efektivních hodnot parametrů formátování včetně zděděných je třeba použít metodu [`GetEffective`](../iportionformat/geteffective), která vrací instanci [`IPortionFormatEffectiveData`](../iportionformateffectivedata).

### Viz také

* jmenný prostor [Aspose.Slides](../../aspose.slides)
* sestavení [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->