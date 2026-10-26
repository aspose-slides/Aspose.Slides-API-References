---
title: IBasePortionFormat class
second_title: Aspose.Slides pro Python prostřednictvím .NET API Reference
description: 
type: docs
url: /cs/aspose.slides/ibaseportionformat/
---
## IBasePortionFormat třída

Tato třída obsahuje vlastnosti formátování textových částí. Na rozdíl od [`IPortionFormatEffectiveData`](/slides/python-net/cs/aspose.slides/iportionformateffectivedata) jsou všechny vlastnosti této třídy zapisovatelné.

Typ IBasePortionFormat vystavuje následující členy:

## Vlastnosti

| Vlastnost | Popis |
| :- | :- |
| [`line_format`](/slides/python-net/cs/aspose.slides/ibaseportionformat/line_format/) | Vrací vlastnosti LineFormat pro obrys textu. Není použito dědění.<br/>            Pouze pro čtení [`ILineFormat`](/slides/python-net/cs/aspose.slides/ilineformat). |
| [`fill_format`](/slides/python-net/cs/aspose.slides/ibaseportionformat/fill_format/) | Vrací vlastnosti FillFormat textu. Není použito dědění.<br/>            Pouze pro čtení [`IFillFormat`](/slides/python-net/cs/aspose.slides/ifillformat). |
| [`effect_format`](/slides/python-net/cs/aspose.slides/ibaseportionformat/effect_format/) | Vrací vlastnosti EffectFormat textu. Není použito dědění.<br/>            Pouze pro čtení [`IEffectFormat`](/slides/python-net/cs/aspose.slides/ieffectformat). |
| [`highlight_color`](/slides/python-net/cs/aspose.slides/ibaseportionformat/highlight_color/) | Vrací barvu použité pro zvýraznění textu. Není použito dědění.<br/>            Pouze pro čtení [`IColorFormat`](/slides/python-net/cs/aspose.slides/icolorformat). |
| [`underline_line_format`](/slides/python-net/cs/aspose.slides/ibaseportionformat/underline_line_format/) | Vrací vlastnosti LineFormat použité pro obrys podtržení. Není použito dědění.<br/>            Pouze pro čtení [`ILineFormat`](/slides/python-net/cs/aspose.slides/ilineformat). |
| [`underline_fill_format`](/slides/python-net/cs/aspose.slides/ibaseportionformat/underline_fill_format/) | Vrací vlastnosti FillFormat podtržené čáry. Není použito dědění.<br/>            Pouze pro čtení [`IFillFormat`](/slides/python-net/cs/aspose.slides/ifillformat). |
| [`font_bold`](/slides/python-net/cs/aspose.slides/ibaseportionformat/font_bold/) | Určuje, zda je písmo tučné. Není použito dědění.<br/>            Čtení/Zápis [`NullableBool`](/slides/python-net/cs/aspose.slides/nullablebool). |
| [`font_italic`](/slides/python-net/cs/aspose.slides/ibaseportionformat/font_italic/) | Určuje, zda je písmo kurzívou. Není použito dědění.<br/>            Čtení/Zápis [`NullableBool`](/slides/python-net/cs/aspose.slides/nullablebool). |
| [`kumimoji`](/slides/python-net/cs/aspose.slides/ibaseportionformat/kumimoji/) | Určuje, zda mají čísla ignorovat specifické svislé rozložení textu pro východní jazyky. Není použito dědění.<br/>            Čtení/Zápis [`NullableBool`](/slides/python-net/cs/aspose.slides/nullablebool). |
| [`normalise_height`](/slides/python-net/cs/aspose.slides/ibaseportionformat/normalise_height/) | Určuje, zda má být výška textu normalizována. Není použito dědění.<br/>            Čtení/Zápis [`NullableBool`](/slides/python-net/cs/aspose.slides/nullablebool). |
| [`proof_disabled`](/slides/python-net/cs/aspose.slides/ibaseportionformat/proof_disabled/) | Určuje, zda text nemá být kontrolován pravopisem. Není použito dědění.<br/>            Čtení/Zápis [`NullableBool`](/slides/python-net/cs/aspose.slides/nullablebool). |
| [`font_underline`](/slides/python-net/cs/aspose.slides/ibaseportionformat/font_underline/) | Vrací nebo nastavuje typ podtržení textu. Není použito dědění.<br/>            Čtení/Zápis [`TextUnderlineType`](/slides/python-net/cs/aspose.slides/textunderlinetype). |
| [`text_cap_type`](/slides/python-net/cs/aspose.slides/ibaseportionformat/text_cap_type/) | Vrací nebo nastavuje typ kapitalizace textu. Není použito dědění.<br/>            Čtení/Zápis [`TextCapType`](/slides/python-net/cs/aspose.slides/textcaptype). |
| [`strikethrough_type`](/slides/python-net/cs/aspose.slides/ibaseportionformat/strikethrough_type/) | Vrací nebo nastavuje typ přeškrtnutí textu. Není použito dědění.<br/>            Čtení/Zápis [`TextStrikethroughType`](/slides/python-net/cs/aspose.slides/textstrikethroughtype). |
| [`is_hard_underline_line`](/slides/python-net/cs/aspose.slides/ibaseportionformat/is_hard_underline_line/) | Určuje, zda styl podtržení má vlastní vlastnosti LineFormat nebo je dědí z vlastností LineFormat textu.<br/>            Čtení/Zápis [`NullableBool`](/slides/python-net/cs/aspose.slides/nullablebool). |
| [`is_hard_underline_fill`](/slides/python-net/cs/aspose.slides/ibaseportionformat/is_hard_underline_fill/) | Určuje, zda styl podtržení má vlastní vlastnosti FillFormat nebo je dědí z vlastností FillFormat textu.<br/>            Čtení/Zápis [`NullableBool`](/slides/python-net/cs/aspose.slides/nullablebool). |
| [`font_height`](/slides/python-net/cs/aspose.slides/ibaseportionformat/font_height/) | Vrací nebo nastavuje výšku písma části.<br/>            **float.NaN**  znamená, že výška není definována a měla by být zděděna z Masteru.<br/>            Čtení/Zápis **float**. |
| [`latin_font`](/slides/python-net/cs/aspose.slides/ibaseportionformat/latin_font/) | Vrací nebo nastavuje informace o latině písma.<br/>            Null znamená, že písmo není definováno a mělo by být zděděno z Masteru.<br/>            Čtení/Zápis [`IFontData`](/slides/python-net/cs/aspose.slides/ifontdata). |
| [`east_asian_font`](/slides/python-net/cs/aspose.slides/ibaseportionformat/east_asian_font/) | Vrací nebo nastavuje informace o východoasijském písmu.<br/>            Null znamená, že písmo není definováno a mělo by být zděděno z Masteru.<br/>            Čtení/Zápis [`IFontData`](/slides/python-net/cs/aspose.slides/ifontdata). |
| [`complex_script_font`](/slides/python-net/cs/aspose.slides/ibaseportionformat/complex_script_font/) | Vrací nebo nastavuje informace o písmech pro složité skripty.<br/>            Null znamená, že písmo není definováno a mělo by být zděděno z Masteru.<br/>            Čtení/Zápis [`IFontData`](/slides/python-net/cs/aspose.slides/ifontdata). |
| [`symbol_font`](/slides/python-net/cs/aspose.slides/ibaseportionformat/symbol_font/) | Vrací nebo nastavuje informace o symbolickém písmu.<br/>            Null znamená, že písmo není definováno a mělo by být zděděno z Masteru.<br/>            Čtení/Zápis [`IFontData`](/slides/python-net/cs/aspose.slides/ifontdata). |
| [`escapement`](/slides/python-net/cs/aspose.slides/ibaseportionformat/escapement/) | Vrací nebo nastavuje horní nebo dolní index textu.<br/>            Hodnota v rozmezí -100 % (dolní index) až 100 % (horní index).<br/>            **float.NaN**  znamená, že hodnota není definována a měla by být zděděna z Masteru.<br/>            Čtení/Zápis **float**. |
| [`kerning_minimal_size`](/slides/python-net/cs/aspose.slides/ibaseportionformat/kerning_minimal_size/) | Vrací nebo nastavuje minimální velikost písma, pro kterou se má zapnout kerning.<br/>            **float.NaN**  znamená, že hodnota není definována a měla by být zděděna z Masteru.<br/>            Čtení/Zápis **float**. |
| [`language_id`](/slides/python-net/cs/aspose.slides/ibaseportionformat/language_id/) | Vrací nebo nastavuje Id jazyka pro korekturu. Používá se pro kontrolu pravopisu a gramatiky.<br/>            Čtení/Zápis **str**. |
| [`alternative_language_id`](/slides/python-net/cs/aspose.slides/ibaseportionformat/alternative_language_id/) | Vrací nebo nastavuje Id alternativního jazyka.<br/>            Čtení/Zápis **str**. |
| [`spacing`](/slides/python-net/cs/aspose.slides/ibaseportionformat/spacing/) | Vrací nebo nastavuje přírůstek mezery mezi znaky.<br/>            **float.NaN**  znamená, že hodnota není definována a měla by být zděděna z Masteru.<br/>            Čtení/Zápis **float**. |
| [`spell_check`](/slides/python-net/cs/aspose.slides/ibaseportionformat/spell_check/) | Získá nebo nastaví hodnotu určující, zda je pro část textu povolena kontrola pravopisu. Když je tato vlastnost nastavena na false, kontrola pravopisu pro textové elementy je potlačena.<br/>            Když je nastavena na true, kontrola pravopisu je povolena.<br/>            Výchozí hodnota je `false`. |

### Poznámky

Tato třída se používá k vracení a manipulaci s vlastnostmi formátování textové části definovanými pro konkrétní část. To znamená, že
            žádné dědění není použito při získávání hodnot, takže ve většině případů získáte hodnoty označující „nedefinováno“.


Pro získání efektivních hodnot parametrů formátování včetně děděných je nutné použít metodu [`IPortionFormat.get_effective`](/slides/python-net/cs/aspose.slides/iportionformat/get_effective)
            která vrací instanci [`IPortionFormatEffectiveData`](/slides/python-net/cs/aspose.slides/iportionformateffectivedata).

### Viz také
* třída [`IPortionFormatEffectiveData`](/slides/python-net/cs/aspose.slides/iportionformateffectivedata)
* modul [`aspose.slides`](/slides/python-net/cs/aspose.slides)
* knihovna [`Aspose.Slides`](/slides/python-net)