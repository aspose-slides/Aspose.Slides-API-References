---
title: PortionFormat class
second_title: Aspose.Slides pro Python přes .NET API Reference
description: 
type: docs
url: /cs/aspose.slides/portionformat/
---
## PortionFormat třída

Tato třída obsahuje vlastnosti formátování textových částí. Na rozdíl od [`IPortionFormatEffectiveData`](/slides/python-net/cs/aspose.slides/iportionformateffectivedata) jsou všechny vlastnosti této třídy zapisovatelné.

**Dědičnost:**[`PortionFormat`](/slides/python-net/cs/aspose.slides/portionformat) → [`BasePortionFormat`](/slides/python-net/cs/aspose.slides/baseportionformat) → [`PVIObject`](/slides/python-net/cs/aspose.slides/pviobject)

Typ PortionFormat obsahuje následující členy:

## Konstruktory

| Konstruktor | Popis |
| :- | :- |
| [`__init__(self)`](/slides/python-net/cs/aspose.slides/portionformat/__init__/#) | Inicializuje novou instanci třídy [`PortionFormat`](/slides/python-net/cs/aspose.slides/portionformat). |

## Vlastnosti

| Vlastnost | Popis |
| :- | :- |
| [`line_format`](/slides/python-net/cs/aspose.slides/portionformat/line_format/) | Vrací vlastnosti LineFormat pro obrys textu. Nepoužívá se dědičnost.<br/>            Pouze pro čtení [`ILineFormat`](/slides/python-net/cs/aspose.slides/ilineformat). |
| [`fill_format`](/slides/python-net/cs/aspose.slides/portionformat/fill_format/) | Vrací vlastnosti FillFormat textu. Nepoužívá se dědičnost.<br/>            Pouze pro čtení [`IFillFormat`](/slides/python-net/cs/aspose.slides/ifillformat). |
| [`effect_format`](/slides/python-net/cs/aspose.slides/portionformat/effect_format/) | Vrací vlastnosti EffectFormat textu. Nepoužívá se dědičnost.<br/>            Pouze pro čtení [`IEffectFormat`](/slides/python-net/cs/aspose.slides/ieffectformat). |
| [`highlight_color`](/slides/python-net/cs/aspose.slides/portionformat/highlight_color/) | Vrací barvu použitou pro zvýraznění textu. Nepoužívá se dědičnost.<br/>            Pouze pro čtení [`IColorFormat`](/slides/python-net/cs/aspose.slides/icolorformat). |
| [`underline_line_format`](/slides/python-net/cs/aspose.slides/portionformat/underline_line_format/) | Vrací vlastnosti LineFormat použité k obrysu podtržité čáry. Nepoužívá se dědičnost.<br/>            Pouze pro čtení [`ILineFormat`](/slides/python-net/cs/aspose.slides/ilineformat). |
| [`underline_fill_format`](/slides/python-net/cs/aspose.slides/portionformat/underline_fill_format/) | Vrací vlastnosti FillFormat podtržité čáry. Nepoužívá se dědičnost.<br/>            Pouze pro čtení [`IFillFormat`](/slides/python-net/cs/aspose.slides/ifillformat). |
| [`font_bold`](/slides/python-net/cs/aspose.slides/portionformat/font_bold/) | Určuje, zda je písmo tučné. Nepoužívá se dědičnost.<br/>            Čtení/zápis [`NullableBool`](/slides/python-net/cs/aspose.slides/nullablebool). |
| [`font_italic`](/slides/python-net/cs/aspose.slides/portionformat/font_italic/) | Určuje, zda je písmo kurzívou. Nepoužívá se dědičnost.<br/>            Čtení/zápis [`NullableBool`](/slides/python-net/cs/aspose.slides/nullablebool). |
| [`kumimoji`](/slides/python-net/cs/aspose.slides/portionformat/kumimoji/) | Určuje, zda mají čísla ignorovat specifické svislé rozložení textu pro východoasijské jazyky. Nepoužívá se dědičnost.<br/>            Čtení/zápis [`NullableBool`](/slides/python-net/cs/aspose.slides/nullablebool). |
| [`normalise_height`](/slides/python-net/cs/aspose.slides/portionformat/normalise_height/) | Určuje, zda by výška textu měla být normalizována. Nepoužívá se dědičnost.<br/>            Čtení/zápis [`NullableBool`](/slides/python-net/cs/aspose.slides/nullablebool). |
| [`proof_disabled`](/slides/python-net/cs/aspose.slides/portionformat/proof_disabled/) | Určuje, zda by text neměl být kontrolován pravopisem. Nepoužívá se dědičnost.<br/>            Čtení/zápis [`NullableBool`](/slides/python-net/cs/aspose.slides/nullablebool). |
| [`font_underline`](/slides/python-net/cs/aspose.slides/portionformat/font_underline/) | Vrací nebo nastavuje typ podtržení textu. Nepoužívá se dědičnost.<br/>            Čtení/zápis [`TextUnderlineType`](/slides/python-net/cs/aspose.slides/textunderlinetype). |
| [`text_cap_type`](/slides/python-net/cs/aspose.slides/portionformat/text_cap_type/) | Vrací nebo nastavuje typ kapitalizace textu. Nepoužívá se dědičnost.<br/>            Čtení/zápis [`TextCapType`](/slides/python-net/cs/aspose.slides/textcaptype). |
| [`strikethrough_type`](/slides/python-net/cs/aspose.slides/portionformat/strikethrough_type/) | Vrací nebo nastavuje typ přeškrtnutí textu. Nepoužívá se dědičnost.<br/>            Čtení/zápis [`TextStrikethroughType`](/slides/python-net/cs/aspose.slides/textstrikethroughtype). |
| [`is_hard_underline_line`](/slides/python-net/cs/aspose.slides/portionformat/is_hard_underline_line/) | Určuje, zda styl podtržení má vlastní vlastnosti LineFormat nebo je dědí<br/>            z vlastností LineFormat textu.<br/>            Čtení/zápis [`NullableBool`](/slides/python-net/cs/aspose.slides/nullablebool). |
| [`is_hard_underline_fill`](/slides/python-net/cs/aspose.slides/portionformat/is_hard_underline_fill/) | Určuje, zda styl podtržení má vlastní vlastnosti FillFormat nebo je dědí<br/>            z vlastností FillFormat textu.<br/>            Čtení/zápis [`NullableBool`](/slides/python-net/cs/aspose.slides/nullablebool). |
| [`font_height`](/slides/python-net/cs/aspose.slides/portionformat/font_height/) | Vrací nebo nastavuje výšku písma části.<br/>            **float.NaN**  znamená, že výška není definována a měla by být zděděna z Masteru.<br/>            Čtení/zápis **float**. |
| [`latin_font`](/slides/python-net/cs/aspose.slides/portionformat/latin_font/) | Vrací nebo nastavuje informace o latinském písmu.<br/>            Null znamená, že písmo není definováno a mělo by být zděděno z Masteru.<br/>            Čtení/zápis [`IFontData`](/slides/python-net/cs/aspose.slides/ifontdata). |
| [`east_asian_font`](/slides/python-net/cs/aspose.slides/portionformat/east_asian_font/) | Vrací nebo nastavuje informace o východoasijském písmu.<br/>            Null znamená, že písmo není definováno a mělo by být zděděno z Masteru.<br/>            Čtení/zápis [`IFontData`](/slides/python-net/cs/aspose.slides/ifontdata). |
| [`complex_script_font`](/slides/python-net/cs/aspose.slides/portionformat/complex_script_font/) | Vrací nebo nastavuje informace o písmu pro složité skripty.<br/>            Null znamená, že písmo není definováno a mělo by být zděděno z Masteru.<br/>            Čtení/zápis [`IFontData`](/slides/python-net/cs/aspose.slides/ifontdata). |
| [`symbol_font`](/slides/python-net/cs/aspose.slides/portionformat/symbol_font/) | Vrací nebo nastavuje informace o symbolickém písmu.<br/>            Null znamená, že písmo není definováno a mělo by být zděděno z Masteru.<br/>            Čtení/zápis [`IFontData`](/slides/python-net/cs/aspose.slides/ifontdata). |
| [`escapement`](/slides/python-net/cs/aspose.slides/portionformat/escapement/) | Vrací nebo nastavuje text jako horní či dolní index.<br/>            Hodnota od -100 % (dolní index) do 100 % (horní index).<br/>            **float.NaN**  znamená, že hodnota není definována a měla by být zděděna z Masteru.<br/>            Čtení/zápis **float**. |
| [`kerning_minimal_size`](/slides/python-net/cs/aspose.slides/portionformat/kerning_minimal_size/) | Vrací nebo nastavuje minimální velikost písma, pro kterou by mělo být zapnuto kerning.<br/>            **float.NaN**  znamená, že hodnota není definována a měla by být zděděna z Masteru.<br/>            Čtení/zápis **float**. |
| [`language_id`](/slides/python-net/cs/aspose.slides/portionformat/language_id/) | Vrací nebo nastavuje ID jazyka pro kontrolu. Používá se pro kontrolu pravopisu a gramatiky.<br/>            Čtení/zápis **str**. |
| [`alternative_language_id`](/slides/python-net/cs/aspose.slides/portionformat/alternative_language_id/) | Vrací nebo nastavuje ID alternativního jazyka.<br/>            Čtení/zápis **str**. |
| [`spacing`](/slides/python-net/cs/aspose.slides/portionformat/spacing/) | Vrací nebo nastavuje přírůstek mezery mezi znaky.<br/>            **float.NaN**  znamená, že hodnota není definována a měla by být zděděna z Masteru.<br/>            Čtení/zápis **float**. |
| [`spell_check`](/slides/python-net/cs/aspose.slides/portionformat/spell_check/) | Získá nebo nastaví hodnotu označující, zda je pro část textu povolena kontrola pravopisu.<br/>            Když je tato vlastnost nastavena na false, kontroly pravopisu pro textové prvky jsou potlačeny.<br/>            Když je nastavena na true, kontrola pravopisu je povolena.<br/>            Výchozí hodnota je `false`. |
| [`bookmark_id`](/slides/python-net/cs/aspose.slides/portionformat/bookmark_id/) | Vrací nebo nastavuje identifikátor záložky.<br/>            Čtení/zápis **str**. |
| [`smart_tag_clean`](/slides/python-net/cs/aspose.slides/portionformat/smart_tag_clean/) | Určuje, zda by měl být inteligentní štítek vyčištěn. Nepoužívá se dědičnost.<br/>            Čtení/zápis **bool**. |
| [`hyperlink_click`](/slides/python-net/cs/aspose.slides/portionformat/hyperlink_click/) | Vrací nebo nastavuje hyperodkaz definovaný pro kliknutí myší.<br/>            Čtení/zápis [`IHyperlink`](/slides/python-net/cs/aspose.slides/ihyperlink). |
| [`hyperlink_mouse_over`](/slides/python-net/cs/aspose.slides/portionformat/hyperlink_mouse_over/) | Vrací nebo nastavuje hyperodkaz definovaný pro najetí myší.<br/>            Čtení/zápis [`IHyperlink`](/slides/python-net/cs/aspose.slides/ihyperlink). |
| [`hyperlink_manager`](/slides/python-net/cs/aspose.slides/portionformat/hyperlink_manager/) | Správce hyperodkazů.<br/>            Pouze pro čtení [`IHyperlinkManager`](/slides/python-net/cs/aspose.slides/ihyperlinkmanager). |
| [`slide`](/slides/python-net/cs/aspose.slides/portionformat/slide/) |  |
| [`presentation`](/slides/python-net/cs/aspose.slides/portionformat/presentation/) |  |

## Metody

| Metoda | Popis |
| :- | :- |
| [`get_effective(self)`](/slides/python-net/cs/aspose.slides/portionformat/get_effective/#) | Získá efektivní data formátování částí s aplikovanou dědičností. |

### Poznámky

Tato třída se používá k vracení a manipulaci s vlastnostmi formátování textových částí definovanými pro konkrétní část. To znamená, že
            při získávání hodnot se nepoužívá dědičnost, takže ve většině případů získáte hodnoty znamenající „nedefinováno“.

Chcete-li získat efektivní hodnoty parametrů formátování včetně zděděných, musíte použít metodu [`PortionFormat.get_effective`](/slides/python-net/cs/aspose.slides/portionformat/get_effective),
            která vrací instanci [`IPortionFormatEffectiveData`](/slides/python-net/cs/aspose.slides/iportionformateffectivedata).

### Viz také
* třída [`BasePortionFormat`](/slides/python-net/cs/aspose.slides/baseportionformat)
* třída [`IPortionFormatEffectiveData`](/slides/python-net/cs/aspose.slides/iportionformateffectivedata)
* třída [`PortionFormat`](/slides/python-net/cs/aspose.slides/portionformat)
* třída [`PVIObject`](/slides/python-net/cs/aspose.slides/pviobject)
* modul [`aspose.slides`](/slides/python-net/cs/aspose.slides)
* knihovna [`Aspose.Slides`](/slides/python-net)