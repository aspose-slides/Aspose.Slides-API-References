---
title: FontsManager class
second_title: Aspose.Slides pro Python přes .NET referenci API
description: 
type: docs
url: /cs/aspose.slides/fontsmanager/
---
## FontsManager třída

Spravuje písma v celé prezentaci.

Typ FontsManager poskytuje následující členy:

## Vlastnosti

| Vlastnost | Popis |
| :- | :- |
| [`font_subst_rule_list`](/slides/python-net/cs/aspose.slides/fontsmanager/font_subst_rule_list/) | Náhrady písem použité při vykreslování.<br/>            Číst/zapisovat [`IFontSubstRuleCollection`](/slides/python-net/cs/aspose.slides/ifontsubstrulecollection). |
| [`font_fall_back_rules_collection`](/slides/python-net/cs/aspose.slides/fontsmanager/font_fall_back_rules_collection/) | Představuje kolekci pravidel FontFallBack uživatele pro správu sbírek písem a jejich správné nahrazování pomocí funkce náhradního písma<br/>            Číst/zapisovat [`IFontFallBackRulesCollection`](/slides/python-net/cs/aspose.slides/ifontfallbackrulescollection). |

## Metody

| Metoda | Popis |
| :- | :- |
| [`get_substitutions(self)`](/slides/python-net/cs/aspose.slides/fontsmanager/get_substitutions/#) | Získá informace o písmech, která budou nahrazena při vykreslování prezentace. |
| [`get_substitutions(self, slides)`](/slides/python-net/cs/aspose.slides/fontsmanager/get_substitutions/#listint) | Získá informace o písmech, která budou nahrazena při vykreslování určených snímků. |
| [`add_embedded_font(self, font_data, embed_font_rule)`](/slides/python-net/cs/aspose.slides/fontsmanager/add_embedded_font/#ifontdata-asposeslidesexportembedfontcharacters) | Přidá vložené písmo<br/>            Mějte na paměti, že většina písem je chráněna autorským právem. Nejprve zjistěte licenci písma a ověřte, že může být volně přeneseno na jiný počítač. ArgumentException může být vyvolána, pokud jsou data písma None nebo je toto písmo již vloženo |
| [`add_embedded_font(self, font_data, embed_font_rule)`](/slides/python-net/cs/aspose.slides/fontsmanager/add_embedded_font/#bytes-asposeslidesexportembedfontcharacters) | Přidá vložené písmo<br/>            Mějte na paměti, že většina písem je chráněna autorským právem. Nejprve zjistěte licenci písma a ověřte, že může být volně přeneseno na jiný počítač. ArgumentException může být vyvolána, pokud jsou data písma None nebo je toto písmo již vloženo |
| [`replace_font(self, source_font, dest_font)`](/slides/python-net/cs/aspose.slides/fontsmanager/replace_font/#ifontdata-ifontdata) | Nahradit písmo v prezentaci |
| [`replace_font(self, subst_rule)`](/slides/python-net/cs/aspose.slides/fontsmanager/replace_font/#ifontsubstrule) | Nahradit písmo v prezentaci pomocí informací poskytnutých v [`FontSubstRule`](/slides/python-net/cs/aspose.slides/fontsubstrule) |
| [`replace_font(self, subst_rules)`](/slides/python-net/cs/aspose.slides/fontsmanager/replace_font/#ifontsubstrulecollection) | Nahradit písmo v prezentaci pomocí informací poskytnutých ve sbírce [`FontSubstRule`](/slides/python-net/cs/aspose.slides/fontsubstrule) |
| [`get_fonts(self)`](/slides/python-net/cs/aspose.slides/fontsmanager/get_fonts/#) | Vrací písma použité v prezentaci |
| [`get_embedded_fonts(self)`](/slides/python-net/cs/aspose.slides/fontsmanager/get_embedded_fonts/#) | Vrací písma vložená v prezentaci |
| [`remove_embedded_font(self, font_data)`](/slides/python-net/cs/aspose.slides/fontsmanager/remove_embedded_font/#ifontdata) | Odstraní vložené písmo |
| [`get_font_bytes(self, font_data, font_style)`](/slides/python-net/cs/aspose.slides/fontsmanager/get_font_bytes/#ifontdata-fontstyletype) | Načte pole bajtů představující data písma pro zadaný styl písma a data písma. |
| [`get_font_embedding_level(self, font_bytes, font_name)`](/slides/python-net/cs/aspose.slides/fontsmanager/get_font_embedding_level/#bytes-str) | Určuje úroveň vkládání písma z daného pole bajtů a názvu písma. |


### Viz také
* modul [`aspose.slides`](/slides/python-net/cs/aspose.slides)
* knihovna [`Aspose.Slides`](/slides/python-net)