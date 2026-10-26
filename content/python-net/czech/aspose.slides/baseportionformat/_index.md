---
title: BasePortionFormat class
second_title: Aspose.Slides pro Python prostřednictvím .NET API Reference
description: 
type: docs
url: /cs/aspose.slides/baseportionformat/
---
## BasePortionFormat třída

Společné vlastnosti formátování textových částí.

**Dědičnost:**[`BasePortionFormat`](/slides/python-net/cs/aspose.slides/baseportionformat) → [`PVIObject`](/slides/python-net/cs/aspose.slides/pviobject)

Typ BasePortionFormat vystavuje následující členy:

## Vlastnosti

| Property | Description |
| :- | :- |
| [`line_format`](/slides/python-net/cs/aspose.slides/baseportionformat/line_format/) | Vrací vlastnosti LineFormat pro obrys textu. Není použita dědičnost.<br/>            Pouze pro čtení [`ILineFormat`](/slides/python-net/cs/aspose.slides/ilineformat). |
| [`fill_format`](/slides/python-net/cs/aspose.slides/baseportionformat/fill_format/) | Vrací vlastnosti FillFormat textu. Není použita dědičnost.<br/>            Pouze pro čtení [`IFillFormat`](/slides/python-net/cs/aspose.slides/ifillformat). |
| [`effect_format`](/slides/python-net/cs/aspose.slides/baseportionformat/effect_format/) | Vrací vlastnosti EffectFormat textu. Není použita dědičnost.<br/>            Pouze pro čtení [`IEffectFormat`](/slides/python-net/cs/aspose.slides/ieffectformat). |
| [`highlight_color`](/slides/python-net/cs/aspose.slides/baseportionformat/highlight_color/) | Vrací barvu používanou pro zvýraznění textu. Není použita dědičnost.<br/>            Pouze pro čtení [`IColorFormat`](/slides/python-net/cs/aspose.slides/icolorformat). |
| [`underline_line_format`](/slides/python-net/cs/aspose.slides/baseportionformat/underline_line_format/) | Vrací vlastnosti LineFormat použité k obrysování podtržené čáry. Není použita dědičnost.<br/>            Pouze pro čtení [`ILineFormat`](/slides/python-net/cs/aspose.slides/ilineformat). |
| [`underline_fill_format`](/slides/python-net/cs/aspose.slides/baseportionformat/underline_fill_format/) | Vrací vlastnosti FillFormat podtržené čáry. Není použita dědičnost.<br/>            Pouze pro čtení [`IFillFormat`](/slides/python-net/cs/aspose.slides/ifillformat). |
| [`font_bold`](/slides/python-net/cs/aspose.slides/baseportionformat/font_bold/) | Určuje, zda je písmo tučné. Není použita dědičnost.<br/>            Čtení/Zápis [`NullableBool`](/slides/python-net/cs/aspose.slides/nullablebool). |
| [`font_italic`](/slides/python-net/cs/aspose.slides/baseportionformat/font_italic/) | Určuje, zda je písmo kurzívou. Není použita dědičnost.<br/>            Čtení/Zápis [`NullableBool`](/slides/python-net/cs/aspose.slides/nullablebool). |
| [`kumimoji`](/slides/python-net/cs/aspose.slides/baseportionformat/kumimoji/) | Určuje, zda čísla mají ignorovat specifické svislé rozložení textu pro východoasijské jazyky. Není použita dědičnost.<br/>            Čtení/Zápis [`NullableBool`](/slides/python-net/cs/aspose.slides/nullablebool). |
| [`normalise_height`](/slides/python-net/cs/aspose.slides/baseportionformat/normalise_height/) | Určuje, zda má být výška textu normalizována. Není použita dědičnost.<br/>            Čtení/Zápis [`NullableBool`](/slides/python-net/cs/aspose.slides/nullablebool). |
| [`proof_disabled`](/slides/python-net/cs/aspose.slides/baseportionformat/proof_disabled/) | Určuje, zda text nemá být kontrolován pravopisem. Není použita dědičnost.<br/>            Čtení/Zápis [`NullableBool`](/slides/python-net/cs/aspose.slides/nullablebool). |
| [`font_underline`](/slides/python-net/cs/aspose.slides/baseportionformat/font_underline/) | Vrací nebo nastavuje typ podtržení textu. Není použita dědičnost.<br/>            Čtení/Zápis [`TextUnderlineType`](/slides/python-net/cs/aspose.slides/textunderlinetype). |
| [`text_cap_type`](/slides/python-net/cs/aspose.slides/baseportionformat/text_cap_type/) | Vrací nebo nastavuje typ kapitalizace textu. Není použita dědičnost.<br/>            Čtení/Zápis [`TextCapType`](/slides/python-net/cs/aspose.slides/textcaptype). |
| [`strikethrough_type`](/slides/python-net/cs/aspose.slides/baseportionformat/strikethrough_type/) | Vrací nebo nastavuje typ přeškrtnutí textu. Není použita dědičnost.<br/>            Čtení/Zápis [`TextStrikethroughType`](/slides/python-net/cs/aspose.slides/textstrikethroughtype). |
| [`is_hard_underline_line`](/slides/python-net/cs/aspose.slides/baseportionformat/is_hard_underline_line/) | Určuje, zda styl podtržení má vlastní vlastnosti LineFormat nebo je dědí<br/>            z vlastností LineFormat textu.<br/>            Čtení/Zápis [`NullableBool`](/slides/python-net/cs/aspose.slides/nullablebool). |
| [`is_hard_underline_fill`](/slides/python-net/cs/aspose.slides/baseportionformat/is_hard_underline_fill/) | Určuje, zda styl podtržení má vlastní vlastnosti FillFormat nebo je dědí<br/>            z vlastností FillFormat textu.<br/>            Čtení/Zápis [`NullableBool`](/slides/python-net/cs/aspose.slides/nullablebool). |
| [`font_height`](/slides/python-net/cs/aspose.slides/baseportionformat/font_height/) | Vrací nebo nastavuje výšku písma části.<br/>            **float.NaN**  znamená, že výška není definována a měla by být zděděna z Masteru.<br/>            Čtení/Zápis **float**. |
| [`latin_font`](/slides/python-net/cs/aspose.slides/baseportionformat/latin_font/) | Vrací nebo nastavuje informace o latinském písmu.<br/>            Null znamená, že písmo není definováno a mělo by být zděděno z Masteru.<br/>            Čtení/Zápis [`IFontData`](/slides/python-net/cs/aspose.slides/ifontdata). |
| [`east_asian_font`](/slides/python-net/cs/aspose.slides/baseportionformat/east_asian_font/) | Vrací nebo nastavuje informace o východoasijském písmu.<br/>            Null znamená, že písmo není definováno a mělo by být zděděno z Masteru.<br/>            Čtení/Zápis [`IFontData`](/slides/python-net/cs/aspose.slides/ifontdata). |
| [`complex_script_font`](/slides/python-net/cs/aspose.slides/baseportionformat/complex_script_font/) | Vrací nebo nastavuje informace o písmu pro složité skripty.<br/>            Null znamená, že písmo není definováno a mělo by být zděděno z Masteru.<br/>            Čtení/Zápis [`IFontData`](/slides/python-net/cs/aspose.slides/ifontdata). |
| [`symbol_font`](/slides/python-net/cs/aspose.slides/baseportionformat/symbol_font/) | Vrací nebo nastavuje informace o symbolickém písmu.<br/>            Null znamená, že písmo není definováno a mělo by být zděděno z Masteru.<br/>            Čtení/Zápis [`IFontData`](/slides/python-net/cs/aspose.slides/ifontdata). |
| [`escapement`](/slides/python-net/cs/aspose.slides/baseportionformat/escapement/) | Vrací nebo nastavuje text jako horní nebo dolní index.<br/>            Hodnota od -100 % (dolní index) do 100 % (horní index).<br/>            **float.NaN**  znamená, že hodnota není definována a měla by být zděděna z Masteru.<br/>            Čtení/Zápis **float**. |
| [`kerning_minimal_size`](/slides/python-net/cs/aspose.slides/baseportionformat/kerning_minimal_size/) | Vrací nebo nastavuje minimální velikost písma, pro kterou by mělo být zapnuto podřazení.<br/>            **float.NaN**  znamená, že hodnota není definována a měla by být zděděna z Masteru.<br/>            Čtení/Zápis **float**. |
| [`language_id`](/slides/python-net/cs/aspose.slides/baseportionformat/language_id/) | Vrací nebo nastavuje Id jazyka pro kontrolu pravopisu. Používá se pro kontrolu pravopisu a gramatiky.<br/>            Čtení/Zápis **str**. |
| [`alternative_language_id`](/slides/python-net/cs/aspose.slides/baseportionformat/alternative_language_id/) | Vrací nebo nastavuje Id alternativního jazyka.<br/>            Čtení/Zápis **str**. |
| [`spacing`](/slides/python-net/cs/aspose.slides/baseportionformat/spacing/) | Vrací nebo nastavuje přírůstek mezery mezi znaky.<br/>            **float.NaN**  znamená, že hodnota není definována a měla by být zděděna z Masteru.<br/>            Čtení/Zápis **float**. |
| [`spell_check`](/slides/python-net/cs/aspose.slides/baseportionformat/spell_check/) | Získá nebo nastaví hodnotu určující, zda je pro část textu povolena kontrola pravopisu.<br/>            Když je tato vlastnost nastavena na false, kontroly pravopisu pro textové prvky jsou potlačeny.<br/>            Když je nastavena na true, kontrola pravopisu je povolena.<br/>            Výchozí hodnota je `false`. |
| [`slide`](/slides/python-net/cs/aspose.slides/baseportionformat/slide/) |  |
| [`presentation`](/slides/python-net/cs/aspose.slides/baseportionformat/presentation/) |  |

### Viz také
* třída [`BasePortionFormat`](/slides/python-net/cs/aspose.slides/baseportionformat)
* třída [`PVIObject`](/slides/python-net/cs/aspose.slides/pviobject)
* modul [`aspose.slides`](/slides/python-net/cs/aspose.slides)
* knihovna [`Aspose.Slides`](/slides/python-net)