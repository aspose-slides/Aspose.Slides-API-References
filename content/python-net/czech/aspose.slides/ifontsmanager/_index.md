---
title: IFontsManager class
second_title: Aspose.Slides pro Python přes .NET API Reference
description: 
type: docs
url: /cs/aspose.slides/ifontsmanager/
---
## IFontsManager třída

Manages fonts across the presentation.

The IFontsManager type exposes the following members:

## Vlastnosti

| Vlastnost | Popis |
| :- | :- |
| [`font_subst_rule_list`](/slides/python-net/cs/aspose.slides/ifontsmanager/font_subst_rule_list/) | Náhrady písem používané při vykreslování<br/>            Číst/zapisovat [`IFontSubstRuleCollection`](/slides/python-net/cs/aspose.slides/ifontsubstrulecollection). |
| [`font_fall_back_rules_collection`](/slides/python-net/cs/aspose.slides/ifontsmanager/font_fall_back_rules_collection/) | Representuje uživatelovu kolekci pravidel FontFallBack pro správu kolekcí písem pro správné náhrady pomocí funkce záložního písma<br/>            Číst/zapisovat [`IFontFallBackRulesCollection`](/slides/python-net/cs/aspose.slides/ifontfallbackrulescollection). |
| [`prefer_registered_fonts_over_embedded`](/slides/python-net/cs/aspose.slides/ifontsmanager/prefer_registered_fonts_over_embedded/) | Určuje, zda mají být registrovaná písma upřednostněna před vloženými písmy se stejným názvem a stylem.<br/>            Pokud je povoleno, odpovídající vložená písma jsou při exportu dočasně nahrazena příslušnými registrovanými písmy. |

## Metody

| Metoda | Popis |
| :- | :- |
| [`get_substitutions(self)`](/slides/python-net/cs/aspose.slides/ifontsmanager/get_substitutions/#) | Získá informace o písmenech, která budou nahrazena při vykreslování prezentace. |
| [`get_substitutions(self, slides)`](/slides/python-net/cs/aspose.slides/ifontsmanager/get_substitutions/#listint) | Získá informace o písmenech, která budou nahrazena při vykreslování určených snímků. |
| [`add_embedded_font(self, font_data, embed_font_rule)`](/slides/python-net/cs/aspose.slides/ifontsmanager/add_embedded_font/#ifontdata-asposeslidesexportembedfontcharacters) | Přidá vložené písmo.<br/>            Mějte na paměti, že většina písem je chráněna autorským právem. Nejprve najděte licenci <br/>            písma a ověřte, že lze volně přenést na jiný počítač. Může být vyvolána ArgumentException, pokud jsou data písma None nebo je toto písmo již vloženo |
| [`add_embedded_font(self, font_data, embed_font_rule)`](/slides/python-net/cs/aspose.slides/ifontsmanager/add_embedded_font/#bytes-asposeslidesexportembedfontcharacters) | Přidá vložené písmo.<br/>            Mějte na paměti, že většina písem je chráněna autorským právem. Nejprve najděte licenci <br/>            písma a ověřte, že lze volně přenést na jiný počítač. Může být vyvolána ArgumentException, pokud jsou data písma None nebo je toto písmo již vloženo |
| [`replace_font(self, source_font, dest_font)`](/slides/python-net/cs/aspose.slides/ifontsmanager/replace_font/#ifontdata-ifontdata) | Nahradí písmo v prezentaci |
| [`replace_font(self, subst_rule)`](/slides/python-net/cs/aspose.slides/ifontsmanager/replace_font/#ifontsubstrule) | Nahradí písmo v prezentaci pomocí informací poskytnutých v [`IFontSubstRule`](/slides/python-net/cs/aspose.slides/ifontsubstrule) |
| [`replace_font(self, subst_rules)`](/slides/python-net/cs/aspose.slides/ifontsmanager/replace_font/#ifontsubstrulecollection) | Nahradí písmo v prezentaci pomocí informací poskytnutých ve sbírce [`IFontSubstRule`](/slides/python-net/cs/aspose.slides/ifontsubstrule) |
| [`get_fonts(self)`](/slides/python-net/cs/aspose.slides/ifontsmanager/get_fonts/#) | Vrátí písma použitá v prezentaci |
| [`get_embedded_fonts(self)`](/slides/python-net/cs/aspose.slides/ifontsmanager/get_embedded_fonts/#) | Vrátí písma vložená v prezentaci |
| [`remove_embedded_font(self, font_data)`](/slides/python-net/cs/aspose.slides/ifontsmanager/remove_embedded_font/#ifontdata) | Odstraní vložené písmo |
| [`get_font_bytes(self, font_data, font_style)`](/slides/python-net/cs/aspose.slides/ifontsmanager/get_font_bytes/#ifontdata-fontstyletype) | Získá pole bajtů představující data písma pro zadaný styl písma a data písma. |
| [`get_font_embedding_level(self, font_bytes, font_name)`](/slides/python-net/cs/aspose.slides/ifontsmanager/get_font_embedding_level/#bytes-str) | Určuje úroveň vložení písma z daného pole bajtů a názvu písma. |


### Viz také
* modul [`aspose.slides`](/slides/python-net/cs/aspose.slides)
* knihovna [`Aspose.Slides`](/slides/python-net)