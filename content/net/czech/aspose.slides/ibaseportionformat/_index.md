---
title: IBasePortionFormat
second_title: Aspose.Sildes pro .NET API Reference
description: Tato třída obsahuje vlastnosti formátování textových částí. Na rozdíl od IPortionFormatEffectiveData./iportionformateffectivedata jsou všechny vlastnosti této třídy zapisovatelné.
type: docs
weight: 5310
url: /cs/aspose.slides/ibaseportionformat/
---
## IBasePortionFormat rozhraní

Tato třída obsahuje vlastnosti formátování textových částí. Na rozdíl od [`IPortionFormatEffectiveData`](../iportionformateffectivedata) jsou všechny vlastnosti této třídy zapisovatelné.

```csharp
public interface IBasePortionFormat
```

## Vlastnosti

| Název | Popis |
| --- | --- |
| [AlternativeLanguageId](../../aspose.slides/ibaseportionformat/alternativelanguageid) { get; set; } | Vrací nebo nastavuje Id alternativního jazyka. Čtení/Zápis String. |
| [ComplexScriptFont](../../aspose.slides/ibaseportionformat/complexscriptfont) { get; set; } | Vrací nebo nastavuje informace o fontu složitého skriptu. Null znamená, že font není definován a měl by být zděděn z Masteru. Čtení/Zápis [`IFontData`](../ifontdata). |
| [EastAsianFont](../../aspose.slides/ibaseportionformat/eastasianfont) { get; set; } | Vrací nebo nastavuje informace o fontu pro východoasijské jazyky. Null znamená, že font není definován a měl by být zděděn z Masteru. Čtení/Zápis [`IFontData`](../ifontdata). |
| [EffectFormat](../../aspose.slides/ibaseportionformat/effectformat) { get; } | Vrací vlastnosti EffectFormat textu. Není použito dědění. Pouze pro čtení [`IEffectFormat`](../ieffectformat). |
| [Escapement](../../aspose.slides/ibaseportionformat/escapement) { get; set; } | Vrací nebo nastavuje text jako horní nebo dolní index. Hodnota od -100 % (dolní index) do 100 % (horní index). **float.NaN** znamená, že hodnota není definována a měla by být zděděna z Masteru. Čtení/Zápis Single. |
| [FillFormat](../../aspose.slides/ibaseportionformat/fillformat) { get; } | Vrací vlastnosti FillFormat textu. Není použito dědění. Pouze pro čtení [`IFillFormat`](../ifillformat). |
| [FontBold](../../aspose.slides/ibaseportionformat/fontbold) { get; set; } | Určuje, zda je font tučný. Není použito dědění. Čtení/Zápis [`NullableBool`](../nullablebool). |
| [FontHeight](../../aspose.slides/ibaseportionformat/fontheight) { get; set; } | Vrací nebo nastavuje výšku fontu části. **float.NaN** znamená, že výška není definována a měla by být zděděna z Masteru. Čtení/Zápis Single. |
| [FontItalic](../../aspose.slides/ibaseportionformat/fontitalic) { get; set; } | Určuje, zda je font kurzívou. Není použito dědění. Čtení/Zápis [`NullableBool`](../nullablebool). |
| [FontUnderline](../../aspose.slides/ibaseportionformat/fontunderline) { get; set; } | Vrací nebo nastavuje typ podtržení textu. Není použito dědění. Čtení/Zápis [`TextUnderlineType`](../textunderlinetype). |
| [HighlightColor](../../aspose.slides/ibaseportionformat/highlightcolor) { get; } | Vrací barvu použité pro zvýraznění textu. Není použito dědění. Pouze pro čtení [`IColorFormat`](../icolorformat). |
| [IsHardUnderlineFill](../../aspose.slides/ibaseportionformat/ishardunderlinefill) { get; set; } | Určuje, zda má styl podtržení vlastní vlastnosti FillFormat nebo je dědí z vlastností FillFormat textu. Čtení/Zápis [`NullableBool`](../nullablebool). |
| [IsHardUnderlineLine](../../aspose.slides/ibaseportionformat/ishardunderlineline) { get; set; } | Určuje, zda má styl podtržení vlastní vlastnosti LineFormat nebo je dědí z vlastností LineFormat textu. Čtení/Zápis [`NullableBool`](../nullablebool). |
| [KerningMinimalSize](../../aspose.slides/ibaseportionformat/kerningminimalsize) { get; set; } | Vrací nebo nastavuje minimální velikost fontu, při které má být zapnuto kerning. **float.NaN** znamená, že hodnota není definována a měla by být zděděna z Masteru. Čtení/Zápis Single. |
| [Kumimoji](../../aspose.slides/ibaseportionformat/kumimoji) { get; set; } | Určuje, zda mají čísla ignorovat specifické svislé rozvržení textu pro východoasijské jazyky. Není použito dědění. Čtení/Zápis [`NullableBool`](../nullablebool). |
| [LanguageId](../../aspose.slides/ibaseportionformat/languageid) { get; set; } | Vrací nebo nastavuje Id jazykové kontroly. Používá se pro kontrolu pravopisu a gramatiky. Čtení/Zápis String. |
| [LatinFont](../../aspose.slides/ibaseportionformat/latinfont) { get; set; } | Vrací nebo nastavuje informace o latině fontu. Null znamená, že font není definován a měl by být zděděn z Masteru. Čtení/Zápis [`IFontData`](../ifontdata). |
| [LineFormat](../../aspose.slides/ibaseportionformat/lineformat) { get; } | Vrací vlastnosti LineFormat pro obrys textu. Není použito dědění. Pouze pro čtení [`ILineFormat`](../ilineformat). |
| [NormaliseHeight](../../aspose.slides/ibaseportionformat/normaliseheight) { get; set; } | Určuje, zda má být výška textu normalizována. Není použito dědění. Čtení/Zápis [`NullableBool`](../nullablebool). |
| [ProofDisabled](../../aspose.slides/ibaseportionformat/proofdisabled) { get; set; } | Určuje, zda text nemá být kontrolován. Není použito dědění. Čtení/Zápis [`NullableBool`](../nullablebool). |
| [Spacing](../../aspose.slides/ibaseportionformat/spacing) { get; set; } | Vrací nebo nastavuje přírůstek mezery mezi znaky. **float.NaN** znamená, že hodnota není definována a měla by být zděděna z Masteru. Čtení/Zápis Single. |
| [SpellCheck](../../aspose.slides/ibaseportionformat/spellcheck) { get; set; } | Vrací nebo nastavuje hodnotu určující, zda je pro část textu povolena kontrola pravopisu. Pokud je tato vlastnost nastavena na false, kontrola pravopisu pro textové prvky je potlačena. Pokud je nastavena na true, kontrola pravopisu je povolena. Výchozí hodnota je `false`. |
| [StrikethroughType](../../aspose.slides/ibaseportionformat/strikethroughtype) { get; set; } | Vrací nebo nastavuje typ přeškrtnutí textu. Není použito dědění. Čtení/Zápis [`TextStrikethroughType`](../textstrikethroughtype). |
| [SymbolFont](../../aspose.slides/ibaseportionformat/symbolfont) { get; set; } | Vrací nebo nastavuje informace o symbolickém fontu. Null znamená, že font není definován a měl by být zděděn z Masteru. Čtení/Zápis [`IFontData`](../ifontdata). |
| [TextCapType](../../aspose.slides/ibaseportionformat/textcaptype) { get; set; } | Vrací nebo nastavuje typ kapitalizace textu. Není použito dědění. Čtení/Zápis [`TextCapType`](../textcaptype). |
| [UnderlineFillFormat](../../aspose.slides/ibaseportionformat/underlinefillformat) { get; } | Vrací vlastnosti FillFormat podtržené čáry. Není použito dědění. Pouze pro čtení [`IFillFormat`](../ifillformat). |
| [UnderlineLineFormat](../../aspose.slides/ibaseportionformat/underlinelineformat) { get; } | Vrací vlastnosti LineFormat použité pro obrys podtržené čáry. Není použito dědění. Pouze pro čtení [`ILineFormat`](../ilineformat). |

### Poznámky

Tato třída se používá k získání a manipulaci s vlastnostmi formátování textové části definovanými pro konkrétní část. To znamená, že při získávání hodnot není použito dědění, takže ve většině případů získáte hodnoty označující „nedefinováno“.

Aby bylo možné získat efektivní hodnoty parametrů formátování včetně zděděných, je třeba použít metodu [`GetEffective`](../iportionformat/geteffective), která vrací instanci [`IPortionFormatEffectiveData`](../iportionformateffectivedata).

### Viz také

* jmenný prostor [Aspose.Slides](../../aspose.slides)
* sestavení [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->