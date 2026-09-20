---
title: ParagraphFormat class
second_title: Aspose.Slides pro Python pomocí .NET API Reference
description: 
type: docs
url: /cs/aspose.slides/paragraphformat/
---
## ParagraphFormat třída

Tato třída obsahuje vlastnosti formátování odstavců. Na rozdíl od [`IParagraphFormatEffectiveData`](/slides/python-net/cs/aspose.slides/iparagraphformateffectivedata) jsou všechny vlastnosti této třídy zapisovatelné.

**Dědičnost:**[`ParagraphFormat`](/slides/python-net/cs/aspose.slides/paragraphformat) → [`PVIObject`](/slides/python-net/cs/aspose.slides/pviobject)

Typ ParagraphFormat obsahuje následující členy:

## Konstruktory

| Konstruktor | Popis |
| :- | :- |
| [`__init__(self)`](/slides/python-net/cs/aspose.slides/paragraphformat/__init__/#) | Inicializuje novou instanci třídy [`ParagraphFormat`](/slides/python-net/cs/aspose.slides/paragraphformat). |

## Vlastnosti

| Vlastnost | Popis |
| :- | :- |
| [`alignment`](/slides/python-net/cs/aspose.slides/paragraphformat/alignment/) | Vrací nebo nastavuje zarovnání textu v odstavci bez dědičnosti.<br/>            Číst/zapisovat [`TextAlignment`](/slides/python-net/cs/aspose.slides/textalignment). |
| [`space_within`](/slides/python-net/cs/aspose.slides/paragraphformat/space_within/) | Vrací nebo nastavuje množství mezery mezi základními řádky v odstavci. Kladná hodnota znamená procenta, záporná – velikost v bodech. Není použita dědičnost.<br/>            Číst/zapisovat **float**. |
| [`space_before`](/slides/python-net/cs/aspose.slides/paragraphformat/space_before/) | Vrací nebo nastavuje množství mezery před první řádkou v odstavci bez dědičnosti.<br/>            Kladná hodnota udává procento velikosti písma, kterou by měla bílá mezera mít.<br/>            Záporná hodnota udává velikost bílé mezery v bodech.<br/>            Číst/zapisovat **float**. |
| [`space_after`](/slides/python-net/cs/aspose.slides/paragraphformat/space_after/) | Vrací nebo nastavuje množství mezery za poslední řádkou v odstavci bez dědičnosti.<br/>            Kladná hodnota udává procento velikosti písma, kterou by měla bílá mezera mít.<br/>            Záporná hodnota udává velikost bílé mezery v bodech.<br/>            Číst/zapisovat **float**. |
| [`east_asian_line_break`](/slides/python-net/cs/aspose.slides/paragraphformat/east_asian_line_break/) | Určuje, zda se v odstavci používá východoasijské zalomení řádku. Není použita dědičnost.<br/>            Číst/zapisovat [`NullableBool`](/slides/python-net/cs/aspose.slides/nullablebool). |
| [`right_to_left`](/slides/python-net/cs/aspose.slides/paragraphformat/right_to_left/) | Určuje, zda se v odstavci používá zápis zprava doleva. Není použita dědičnost.<br/>            Číst/zapisovat [`NullableBool`](/slides/python-net/cs/aspose.slides/nullablebool). |
| [`latin_line_break`](/slides/python-net/cs/aspose.slides/paragraphformat/latin_line_break/) | Určuje, zda se v odstavci používá latinské zalomení řádku. Není použita dědičnost.<br/>            Číst/zapisovat [`NullableBool`](/slides/python-net/cs/aspose.slides/nullablebool). |
| [`hanging_punctuation`](/slides/python-net/cs/aspose.slides/paragraphformat/hanging_punctuation/) | Určuje, zda se v odstavci používá zavěšená interpunkce. Není použita dědičnost.<br/>            Číst/zapisovat [`NullableBool`](/slides/python-net/cs/aspose.slides/nullablebool). |
| [`margin_left`](/slides/python-net/cs/aspose.slides/paragraphformat/margin_left/) | Vrací nebo nastavuje levý okraj v odstavci bez dědičnosti.<br/>            Číst/zapisovat **float**. |
| [`margin_right`](/slides/python-net/cs/aspose.slides/paragraphformat/margin_right/) | Vrací nebo nastavuje pravý okraj v odstavci bez dědičnosti.<br/>            Číst/zapisovat **float**. |
| [`indent`](/slides/python-net/cs/aspose.slides/paragraphformat/indent/) | Vrací nebo nastavuje první řádkový odsazení / zavěšený odsazení odstavce bez dědičnosti. Zavěšený odsazení lze definovat zápornými hodnotami.<br/>            Číst/zapisovat **float**. |
| [`default_tab_size`](/slides/python-net/cs/aspose.slides/paragraphformat/default_tab_size/) | Vrací nebo nastavuje výchozí velikost tabulátoru bez dědičnosti.<br/>            Číst/zapisovat **float**. |
| [`tabs`](/slides/python-net/cs/aspose.slides/paragraphformat/tabs/) | Vrací tabulátory odstavce. Není použita dědičnost.<br/>            Pouze pro čtení [`ITabCollection`](/slides/python-net/cs/aspose.slides/itabcollection). |
| [`font_alignment`](/slides/python-net/cs/aspose.slides/paragraphformat/font_alignment/) | Vrací nebo nastavuje zarovnání písma v odstavci bez dědičnosti.<br/>            Číst/zapisovat [`FontAlignment`](/slides/python-net/cs/aspose.slides/fontalignment). |
| [`slide`](/slides/python-net/cs/aspose.slides/paragraphformat/slide/) |  |
| [`presentation`](/slides/python-net/cs/aspose.slides/paragraphformat/presentation/) |  |
| [`bullet`](/slides/python-net/cs/aspose.slides/paragraphformat/bullet/) |  |
| [`depth`](/slides/python-net/cs/aspose.slides/paragraphformat/depth/) |  |
| [`default_portion_format`](/slides/python-net/cs/aspose.slides/paragraphformat/default_portion_format/) |  |

## Metody

| Metoda | Popis |
| :- | :- |
| [`get_effective(self)`](/slides/python-net/cs/aspose.slides/paragraphformat/get_effective/#) | Získá efektivní data formátování odstavce s aplikovanou dědičností. |


### Poznámky

Tato třída se používá k vracení a manipulaci s vlastnostmi formátování odstavců definovanými pro konkrétní odstavec. To znamená, že
            při získávání hodnot se nepoužije dědičnost, takže ve většině případů získáte hodnoty označující „nedefinované“.

Pro získání efektivních hodnot parametrů formátování včetně zděděných je třeba použít metodu [`ParagraphFormat.get_effective`](/slides/python-net/cs/aspose.slides/paragraphformat/get_effective),
            která vrací instanci [`IParagraphFormatEffectiveData`](/slides/python-net/cs/aspose.slides/iparagraphformateffectivedata).


### Viz také
* třída [`IParagraphFormatEffectiveData`](/slides/python-net/cs/aspose.slides/iparagraphformateffectivedata)
* třída [`ParagraphFormat`](/slides/python-net/cs/aspose.slides/paragraphformat)
* třída [`PVIObject`](/slides/python-net/cs/aspose.slides/pviobject)
* modul [`aspose.slides`](/slides/python-net/cs/aspose.slides)
* knihovna [`Aspose.Slides`](/slides/python-net)