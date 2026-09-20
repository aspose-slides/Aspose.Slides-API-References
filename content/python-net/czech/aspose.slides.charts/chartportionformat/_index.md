---
title: ChartPortionFormat class
second_title: Aspose.Slides pro Python pomocí .NET API
description: 
type: docs
url: /cs/aspose.slides.charts/chartportionformat/
---
## ChartPortionFormat třída

Tato třída obsahuje vlastnosti formátování částí grafu používané v grafech.
            Na rozdíl od [`IPortionFormatEffectiveData`](/slides/python-net/cs/aspose.slides/iportionformateffectivedata) jsou všechny vlastnosti této třídy zapisovatelné.

**Dědění:**[`ChartPortionFormat`](/slides/python-net/cs/aspose.slides.charts/chartportionformat) → [`BasePortionFormat`](/slides/python-net/cs/aspose.slides/baseportionformat) → [`PVIObject`](/slides/python-net/cs/aspose.slides/pviobject)

Typ ChartPortionFormat zpřístupňuje následující členy:

## Vlastnosti

| Property | Description |
| :- | :- |
| [`line_format`](/slides/python-net/cs/aspose.slides.charts/chartportionformat/line_format/) | Vrací vlastnosti LineFormat pro obrys textu. Nedědí se.<br/>            Pouze ke čtení [`ILineFormat`](/slides/python-net/cs/aspose.slides/ilineformat). |
| [`fill_format`](/slides/python-net/cs/aspose.slides.charts/chartportionformat/fill_format/) | Vrací vlastnosti FillFormat textu. Nedědí se.<br/>            Pouze ke čtení [`IFillFormat`](/slides/python-net/cs/aspose.slides/ifillformat). |
| [`effect_format`](/slides/python-net/cs/aspose.slides.charts/chartportionformat/effect_format/) | Vrací vlastnosti EffectFormat textu. Nedědí se.<br/>            Pouze ke čtení [`IEffectFormat`](/slides/python-net/cs/aspose.slides/ieffectformat). |
| [`highlight_color`](/slides/python-net/cs/aspose.slides.charts/chartportionformat/highlight_color/) | Vrací barvu použitou k zvýraznění textu. Nedědí se.<br/>            Pouze ke čtení [`IColorFormat`](/slides/python-net/cs/aspose.slides/icolorformat). |
| [`underline_line_format`](/slides/python-net/cs/aspose.slides.charts/chartportionformat/underline_line_format/) | Vrací vlastnosti LineFormat použité k obrysování podtržítka. Nedědí se.<br/>            Pouze ke čtení [`ILineFormat`](/slides/python-net/cs/aspose.slides/ilineformat). |
| [`underline_fill_format`](/slides/python-net/cs/aspose.slides.charts/chartportionformat/underline_fill_format/) | Vrací vlastnosti FillFormat podtržítka. Nedědí se.<br/>            Pouze ke čtení [`IFillFormat`](/slides/python-net/cs/aspose.slides/ifillformat). |
| [`font_bold`](/slides/python-net/cs/aspose.slides.charts/chartportionformat/font_bold/) | Určuje, zda je písmo tučné. Nedědí se.<br/>            Čtení/zápis [`NullableBool`](/slides/python-net/cs/aspose.slides/nullablebool). |
| [`font_italic`](/slides/python-net/cs/aspose.slides.charts/chartportionformat/font_italic/) | Určuje, zda je písmo kurzívou. Nedědí se.<br/>            Čtení/zápis [`NullableBool`](/slides/python-net/cs/aspose.slides/nullablebool). |
| [`kumimoji`](/slides/python-net/cs/aspose.slides.charts/chartportionformat/kumimoji/) | Určuje, zda mají čísla ignorovat specifické svislé rozvržení textu východoasijských jazyků. Nedědí se.<br/>            Čtení/zápis [`NullableBool`](/slides/python-net/cs/aspose.slides/nullablebool). |
| [`normalise_height`](/slides/python-net/cs/aspose.slides.charts/chartportionformat/normalise_height/) | Určuje, zda má být výška textu normalizována. Nedědí se.<br/>            Čtení/zápis [`NullableBool`](/slides/python-net/cs/aspose.slides/nullablebool). |
| [`proof_disabled`](/slides/python-net/cs/aspose.slides.charts/chartportionformat/proof_disabled/) | Určuje, zda text nemá být kontrolován pravopisem. Nedědí se.<br/>            Čtení/zápis [`NullableBool`](/slides/python-net/cs/aspose.slides/nullablebool). |
| [`font_underline`](/slides/python-net/cs/aspose.slides.charts/chartportionformat/font_underline/) | Vrací nebo nastavuje typ podtržení textu. Nedědí se.<br/>            Čtení/zápis [`TextUnderlineType`](/slides/python-net/cs/aspose.slides/textunderlinetype). |
| [`text_cap_type`](/slides/python-net/cs/aspose.slides.charts/chartportionformat/text_cap_type/) | Vrací nebo nastavuje typ kapitalizace textu. Nedědí se.<br/>            Čtení/zápis [`TextCapType`](/slides/python-net/cs/aspose.slides/textcaptype). |
| [`strikethrough_type`](/slides/python-net/cs/aspose.slides.charts/chartportionformat/strikethrough_type/) | Vrací nebo nastavuje typ přeškrtnutí textu. Nedědí se.<br/>            Čtení/zápis [`TextStrikethroughType`](/slides/python-net/cs/aspose.slides/textstrikethroughtype). |
| [`is_hard_underline_line`](/slides/python-net/cs/aspose.slides.charts/chartportionformat/is_hard_underline_line/) | Určuje, zda má styl podtržení vlastní vlastnosti LineFormat nebo je dědí<br/>            z vlastností LineFormat textu.<br/>            Čtení/zápis [`NullableBool`](/slides/python-net/cs/aspose.slides/nullablebool). |
| [`is_hard_underline_fill`](/slides/python-net/cs/aspose.slides.charts/chartportionformat/is_hard_underline_fill/) | Určuje, zda má styl podtržení vlastní vlastnosti FillFormat nebo je dědí<br/>            z vlastností FillFormat textu.<br/>            Čtení/zápis [`NullableBool`](/slides/python-net/cs/aspose.slides/nullablebool). |
| [`font_height`](/slides/python-net/cs/aspose.slides.charts/chartportionformat/font_height/) | Vrací nebo nastavuje výšku písma části.<br/>            **float.NaN**  znamená, že výška není definována a měla by být zděděna z Masteru.<br/>            Čtení/zápis **float**. |
| [`latin_font`](/slides/python-net/cs/aspose.slides.charts/chartportionformat/latin_font/) | Vrací nebo nastavuje informace o latinském písmu.<br/>            Null znamená, že písmo není definováno a mělo by být zděděno z Masteru.<br/>            Čtení/zápis [`IFontData`](/slides/python-net/cs/aspose.slides/ifontdata). |
| [`east_asian_font`](/slides/python-net/cs/aspose.slides.charts/chartportionformat/east_asian_font/) | Vrací nebo nastavuje informace o východoasijském písmu.<br/>            Null znamená, že písmo není definováno a mělo by být zděděno z Masteru.<br/>            Čtení/zápis [`IFontData`](/slides/python-net/cs/aspose.slides/ifontdata). |
| [`complex_script_font`](/slides/python-net/cs/aspose.slides.charts/chartportionformat/complex_script_font/) | Vrací nebo nastavuje informace o písmu složitých skriptů.<br/>            Null znamená, že písmo není definováno a mělo by být zděděno z Masteru.<br/>            Čtení/zápis [`IFontData`](/slides/python-net/cs/aspose.slides/ifontdata). |
| [`symbol_font`](/slides/python-net/cs/aspose.slides.charts/chartportionformat/symbol_font/) | Vrací nebo nastavuje informace o symbolickém písmu.<br/>            Null znamená, že písmo není definováno a mělo by být zděděno z Masteru.<br/>            Čtení/zápis [`IFontData`](/slides/python-net/cs/aspose.slides/ifontdata). |
| [`escapement`](/slides/python-net/cs/aspose.slides.charts/chartportionformat/escapement/) | Vrací nebo nastavuje text jako horní index nebo dolní index.<br/>            Hodnota od -100 % (dolní index) do 100 % (horní index).<br/>            **float.NaN**  znamená, že hodnota není definována a měla by být zděděna z Masteru.<br/>            Čtení/zápis **float**. |
| [`kerning_minimal_size`](/slides/python-net/cs/aspose.slides.charts/chartportionformat/kerning_minimal_size/) | Vrací nebo nastavuje minimální velikost písma, při které se má zapnout kerning.<br/>            **float.NaN**  znamená, že hodnota není definována a měla by být zděděna z Masteru.<br/>            Čtení/zápis **float**. |
| [`language_id`](/slides/python-net/cs/aspose.slides.charts/chartportionformat/language_id/) | Vrací nebo nastavuje Id jazykové kontroly. Používá se pro kontrolu pravopisu a gramatiky.<br/>            Čtení/zápis **str**. |
| [`alternative_language_id`](/slides/python-net/cs/aspose.slides.charts/chartportionformat/alternative_language_id/) | Vrací nebo nastavuje Id alternativního jazyka.<br/>            Čtení/zápis **str**. |
| [`spacing`](/slides/python-net/cs/aspose.slides.charts/chartportionformat/spacing/) | Vrací nebo nastavuje přírůstek mezery mezi znaky.<br/>            **float.NaN**  znamená, že hodnota není definována a měla by být zděděna z Masteru.<br/>            Čtení/zápis **float**. |
| [`spell_check`](/slides/python-net/cs/aspose.slides.charts/chartportionformat/spell_check/) | Získá nebo nastaví hodnotu určující, zda je pro část textu povolena kontrola pravopisu.<br/>            Když je tato vlastnost nastavena na false, kontrola pravopisu pro textové prvky je potlačena.<br/>            Když je nastavena na true, kontrola pravopisu je povolena.<br/>            Výchozí hodnota je `false`. |
| [`slide`](/slides/python-net/cs/aspose.slides.charts/chartportionformat/slide/) |  |
| [`presentation`](/slides/python-net/cs/aspose.slides.charts/chartportionformat/presentation/) |  |

### Poznámky

Tato třída se používá k získání a manipulaci s formátováním částí textu
            definovaným pro konkrétní část. To znamená, že
            při získávání hodnot se neaplikuje dědění, takže ve většině případů
            získáte hodnoty označující „nedefinováno“.

Aby bylo možné získat efektivní hodnoty parametrů formátování včetně
            zděděných, je třeba použít metodu [`PortionFormat.get_effective`](/slides/python-net/cs/aspose.slides/portionformat/get_effective)
            která vrací instance [`IPortionFormatEffectiveData`](/slides/python-net/cs/aspose.slides/iportionformateffectivedata).

### Viz také
* třída [`BasePortionFormat`](/slides/python-net/cs/aspose.slides/baseportionformat)
* třída [`ChartPortionFormat`](/slides/python-net/cs/aspose.slides.charts/chartportionformat)
* třída [`IPortionFormatEffectiveData`](/slides/python-net/cs/aspose.slides/iportionformateffectivedata)
* třída [`PVIObject`](/slides/python-net/cs/aspose.slides/pviobject)
* modul [`aspose.slides.charts`](/slides/python-net/cs/aspose.slides.charts)
* knihovna [`Aspose.Slides`](/slides/python-net)