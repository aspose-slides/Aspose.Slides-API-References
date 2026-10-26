---
title: IParagraphFormat class
second_title: Aspose.Slides pro Python přes .NET referenci API
description: 
type: docs
url: /cs/aspose.slides/iparagraphformat/
---
## IParagraphFormat třída

Tato třída obsahuje vlastnosti formátování odstavce. Na rozdíl od [`IParagraphFormatEffectiveData`](/slides/python-net/cs/aspose.slides/iparagraphformateffectivedata) jsou všechny vlastnosti této třídy zapisovatelné.

Typ IParagraphFormat poskytuje následující členy:

## Vlastnosti

| Vlastnost | Popis |
| :- | :- |
| [`bullet`](/slides/python-net/cs/aspose.slides/iparagraphformat/bullet/) | Vrací formát odrážky odstavce.<br/>            Jen pro čtení [`IBulletFormat`](/slides/python-net/cs/aspose.slides/ibulletformat). |
| [`depth`](/slides/python-net/cs/aspose.slides/iparagraphformat/depth/) | Vrací nebo nastavuje hloubku odstavce.<br/>            Hodnota 0 znamená nedefinovanou hodnotu.<br/>            Čtení/zápis **int**. |
| [`alignment`](/slides/python-net/cs/aspose.slides/iparagraphformat/alignment/) | Vrací nebo nastavuje zarovnání textu v odstavci bez dědičnosti.<br/>            Čtení/zápis [`TextAlignment`](/slides/python-net/cs/aspose.slides/textalignment). |
| [`space_within`](/slides/python-net/cs/aspose.slides/iparagraphformat/space_within/) | Vrací nebo nastavuje množství prostoru mezi základními řádky v odstavci. Kladná hodnota znamená procenta, záporná – velikost v bodech. Není použita dědičnost.<br/>            Čtení/zápis **float**. |
| [`space_before`](/slides/python-net/cs/aspose.slides/iparagraphformat/space_before/) | Vrací nebo nastavuje množství prostoru před první řádkou v odstavci bez dědičnosti.<br/>            Kladná hodnota uvádí procento velikosti písma, které má bílý prostor mít.<br/>            Záporná hodnota udává velikost bílého prostoru v bodech.<br/>            Čtení/zápis **float**. |
| [`space_after`](/slides/python-net/cs/aspose.slides/iparagraphformat/space_after/) | Vrací nebo nastavuje množství prostoru za poslední řádkou v odstavci bez dědičnosti.<br/>            Kladná hodnota uvádí procento velikosti písma, které má bílý prostor mít.<br/>            Záporná hodnota udává velikost bílého prostoru v bodech.<br/>            Čtení/zápis **float**. |
| [`east_asian_line_break`](/slides/python-net/cs/aspose.slides/iparagraphformat/east_asian_line_break/) | Určuje, zda se v odstavci používá východoasijský zalomení řádku. Není použita dědičnost.<br/>            Čtení/zápis [`NullableBool`](/slides/python-net/cs/aspose.slides/nullablebool). |
| [`right_to_left`](/slides/python-net/cs/aspose.slides/iparagraphformat/right_to_left/) | Určuje, zda se v odstavci používá psaní zprava doleva. Není použita dědičnost.<br/>            Čtení/zápis [`NullableBool`](/slides/python-net/cs/aspose.slides/nullablebool). |
| [`latin_line_break`](/slides/python-net/cs/aspose.slides/iparagraphformat/latin_line_break/) | Určuje, zda se v odstavci používá latinské zalomení řádku. Není použita dědičnost.<br/>            Čtení/zápis [`NullableBool`](/slides/python-net/cs/aspose.slides/nullablebool). |
| [`hanging_punctuation`](/slides/python-net/cs/aspose.slides/iparagraphformat/hanging_punctuation/) | Určuje, zda se v odstavci používá zavěšená interpunkce. Není použita dědičnost.<br/>            Čtení/zápis [`NullableBool`](/slides/python-net/cs/aspose.slides/nullablebool). |
| [`margin_left`](/slides/python-net/cs/aspose.slides/iparagraphformat/margin_left/) | Vrací nebo nastavuje levý okraj v odstavci bez dědičnosti.<br/>            Čtení/zápis **float**. |
| [`margin_right`](/slides/python-net/cs/aspose.slides/iparagraphformat/margin_right/) | Vrací nebo nastavuje pravý okraj v odstavci bez dědičnosti.<br/>            Čtení/zápis **float**. |
| [`indent`](/slides/python-net/cs/aspose.slides/iparagraphformat/indent/) | Vrací nebo nastavuje první řádkovou odsazení/zavěšenou odsazení odstavce bez dědičnosti. Zavěšené odsazení lze definovat zápornými hodnotami.<br/>            Čtení/zápis **float**. |
| [`default_tab_size`](/slides/python-net/cs/aspose.slides/iparagraphformat/default_tab_size/) | Vrací nebo nastavuje výchozí velikost tabulátoru bez dědičnosti.<br/>            Čtení/zápis **float**. |
| [`tabs`](/slides/python-net/cs/aspose.slides/iparagraphformat/tabs/) | Vrací tabulátory odstavce. Není použita dědičnost.<br/>            Jen pro čtení [`ITabCollection`](/slides/python-net/cs/aspose.slides/itabcollection). |
| [`font_alignment`](/slides/python-net/cs/aspose.slides/iparagraphformat/font_alignment/) | Vrací nebo nastavuje zarovnání písma v odstavci bez dědičnosti.<br/>            Čtení/zápis [`FontAlignment`](/slides/python-net/cs/aspose.slides/fontalignment). |
| [`default_portion_format`](/slides/python-net/cs/aspose.slides/iparagraphformat/default_portion_format/) | Vrací výchozí formát části odstavce. Není použita dědičnost.<br/>            Jen pro čtení [`IPortionFormat`](/slides/python-net/cs/aspose.slides/iportionformat). |

## Metody

| Metoda | Popis |
| :- | :- |
| [`get_effective(self)`](/slides/python-net/cs/aspose.slides/iparagraphformat/get_effective/#) | Získá efektivní data formátování odstavce s aplikovanou dědičností. |

### Poznámky

Třída se používá k vracení a manipulaci s vlastnostmi formátování odstavce definovanými pro konkrétní odstavec. To znamená, že
            při získávání hodnot není použita žádná dědičnost, takže ve většině případů získáte hodnoty znamenající „nedefinováno“.


Pro získání efektivních hodnot parametrů formátování včetně zděděných je třeba použít metodu [`IParagraphFormat.get_effective`](/slides/python-net/cs/aspose.slides/iparagraphformat/get_effective) 
            která vrací instance [`IParagraphFormatEffectiveData`](/slides/python-net/cs/aspose.slides/iparagraphformateffectivedata).

### Viz také
* třída [`IParagraphFormatEffectiveData`](/slides/python-net/cs/aspose.slides/iparagraphformateffectivedata)
* modul [`aspose.slides`](/slides/python-net/cs/aspose.slides)
* knihovna [`Aspose.Slides`](/slides/python-net)