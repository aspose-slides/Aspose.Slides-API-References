---
title: IFontsManager class
second_title: Aspose.Slides pro Python přes .NET API
description: 
type: docs
url: /cs/aspose.slides/ifontsmanager/
---
## IFontsManager třída

Spravuje písma napříč prezentací.

Typ IFontsManager vystavuje následující členy:

## Vlastnosti

| Vlastnost | Popis |
| :- | :- |
| [`font_subst_rule_list`](/slides/python-net/cs/aspose.slides/ifontsmanager/font_subst_rule_list/) | Náhrady písem k použití při vykreslování<br/>            Čtení/zápis [`IFontSubstRuleCollection`](/slides/python-net/cs/aspose.slides/ifontsubstrulecollection). |
| [`font_fall_back_rules_collection`](/slides/python-net/cs/aspose.slides/ifontsmanager/font_fall_back_rules_collection/) | Představuje kolekci pravidel FontFallBack uživatele pro správu sbírek písem pro správné náhrady pomocí funkce fallback<br/>            Čtení/zápis [`IFontFallBackRulesCollection`](/slides/python-net/cs/aspose.slides/ifontfallbackrulescollection). |

## Metody

| Metoda | Popis |
| :- | :- |
| [`get_substitutions(self)`](/slides/python-net/cs/aspose.slides/ifontsmanager/get_substitutions/#) | Získá informace o písmech, která budou nahrazena při vykreslování prezentace. |
| [`get_substitutions(self, slides)`](/slides/python-net/cs/aspose.slides/ifontsmanager/get_substitutions/#listint) | Získá informace o písmech, která budou nahrazena během vykreslování určených snímků. |
| [`add_embedded_font(self, font_data, embed_font_rule)`](/slides/python-net/cs/aspose.slides/ifontsmanager/add_embedded_font/#ifontdata-asposeslidesexportembedfontcharacters) | Přidá vložené písmo.<br/>            Mějte na paměti při kopírování jakýchkoli písem, že většina písem je chráněna autorským právem. Nejprve najděte licenci <br/>            písma a ověřte, že může být volně převáděna na jiný počítač. ArgumentException může být vyvolána, pokud jsou data písma None nebo je toto písmo již vloženo |
| [`add_embedded_font(self, font_data, embed_font_rule)`](/slides/python-net/cs/aspose.slides/ifontsmanager/add_embedded_font/#bytes-asposeslidesexportembedfontcharacters) | Přidá vložené písmo<br/>            Mějte na paměti při přidávání jakýchkoli písem, že většina písem je chráněna autorským právem. Nejprve najděte licenci <br/>            písma a ověřte, že může být volně převáděna na jiný počítač. ArgumentException může být vyvolána, pokud jsou data písma None nebo je toto písmo již vloženo |
| [`replace_font(self, source_font, dest_font)`](/slides/python-net/cs/aspose.slides/ifontsmanager/replace_font/#ifontdata-ifontdata) | Nahradit písmo v prezentaci |
| [`replace_font(self, subst_rule)`](/slides/python-net/cs/aspose.slides/ifontsmanager/replace_font/#ifontsubstrule) | Nahradit písmo v prezentaci pomocí informací poskytnutých v [`IFontSubstRule`](/slides/python-net/cs/aspose.slides/ifontsubstrule) |
| [`replace_font(self, subst_rules)`](/slides/python-net/cs/aspose.slides/ifontsmanager/replace_font/#ifontsubstrulecollection) | Nahradit písmo v prezentaci pomocí informací poskytnutých ve sbírce [`IFontSubstRule`](/slides/python-net/cs/aspose.slides/ifontsubstrule) |
| [`get_fonts(self)`](/slides/python-net/cs/aspose.slides/ifontsmanager/get_fonts/#) | Vrací písma použitá v prezentaci |
| [`get_embedded_fonts(self)`](/slides/python-net/cs/aspose.slides/ifontsmanager/get_embedded_fonts/#) | Vrací písma vložená v prezentaci |
| [`remove_embedded_font(self, font_data)`](/slides/python-net/cs/aspose.slides/ifontsmanager/remove_embedded_font/#ifontdata) | Odstraní vložené písmo |
| [`get_font_bytes(self, font_data, font_style)`](/slides/python-net/cs/aspose.slides/ifontsmanager/get_font_bytes/#ifontdata-fontstyletype) | Načte pole bajtů představující data písma pro zadaný styl písma a data písma. |
| [`get_font_embedding_level(self, font_bytes, font_name)`](/slides/python-net/cs/aspose.slides/ifontsmanager/get_font_embedding_level/#bytes-str) | Určuje úroveň vložení písma z daného pole bajtů a názvu písma. |

### Viz také
* modul [`aspose.slides`](/slides/python-net/cs/aspose.slides)
* knihovna [`Aspose.Slides`](/slides/python-net)