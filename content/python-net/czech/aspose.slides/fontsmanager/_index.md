---
title: FontsManager class
second_title: Aspose.Slides pro Python pomocí .NET API Reference
description: 
type: docs
url: /cs/aspose.slides/fontsmanager/
---
## FontsManager třída

Manages fonts across the presentation.

The FontsManager type exposes the following members:

## Vlastnosti

| Vlastnost | Popis |
| :- | :- |
| [`font_subst_rule_list`](/slides/python-net/cs/aspose.slides/fontsmanager/font_subst_rule_list/) | Náhrady fontů, které se použijí při vykreslování.<br/>            Číst/Zapisovat [`IFontSubstRuleCollection`](/slides/python-net/cs/aspose.slides/ifontsubstrulecollection). |
| [`font_fall_back_rules_collection`](/slides/python-net/cs/aspose.slides/fontsmanager/font_fall_back_rules_collection/) | Reprezentuje uživatelovu sbírku pravidel FontFallBack pro správu kolekcí fontů pro správné náhrady pomocí funkce fallback<br/>            Číst/Zapisovat [`IFontFallBackRulesCollection`](/slides/python-net/cs/aspose.slides/ifontfallbackrulescollection). |
| [`prefer_registered_fonts_over_embedded`](/slides/python-net/cs/aspose.slides/fontsmanager/prefer_registered_fonts_over_embedded/) | Určuje, zda by registrované fonty měly mít přednost před vloženými fonty se stejným názvem a stylem.<br/>            Když je povoleno, odpovídající vložené fonty jsou během exportu dočasně nahrazeny příslušnými registrovanými fonty. |

## Metody

| Metoda | Popis |
| :- | :- |
| [`get_substitutions(self)`](/slides/python-net/cs/aspose.slides/fontsmanager/get_substitutions/#) | Získá informace o fontech, které budou nahrazeny při vykreslování prezentace. |
| [`get_substitutions(self, slides)`](/slides/python-net/cs/aspose.slides/fontsmanager/get_substitutions/#listint) | Získá informace o fontech, které budou nahrazeny při vykreslování specifikovaných snímků. |
| [`add_embedded_font(self, font_data, embed_font_rule)`](/slides/python-net/cs/aspose.slides/fontsmanager/add_embedded_font/#ifontdata-asposeslidesexportembedfontcharacters) | Přidá vložený font<br/>            Mějte na paměti, že většina fontů je chráněna autorským právem. Nejprve najděte licenci <br/>            fontu předem a ověřte, že lze svobodně přenést na jiný stroj. Může být vyhozena výjimka ArgumentException, pokud jsou data fontu None nebo je tento font již vložen. |
| [`add_embedded_font(self, font_data, embed_font_rule)`](/slides/python-net/cs/aspose.slides/fontsmanager/add_embedded_font/#bytes-asposeslidesexportembedfontcharacters) | Přidá vložený font<br/>            Mějte na paměti, že většina fontů je chráněna autorským právem. Nejprve najděte licenci <br/>            fontu předem a ověřte, že lze svobodně přenést na jiný stroj. Může být vyhozena výjimka ArgumentException, pokud jsou data fontu None nebo je tento font již vložen. |
| [`replace_font(self, source_font, dest_font)`](/slides/python-net/cs/aspose.slides/fontsmanager/replace_font/#ifontdata-ifontdata) | Nahradit font v prezentaci |
| [`replace_font(self, subst_rule)`](/slides/python-net/cs/aspose.slides/fontsmanager/replace_font/#ifontsubstrule) | Nahradit font v prezentaci pomocí informací poskytnutých v [`FontSubstRule`](/slides/python-net/cs/aspose.slides/fontsubstrule) |
| [`replace_font(self, subst_rules)`](/slides/python-net/cs/aspose.slides/fontsmanager/replace_font/#ifontsubstrulecollection) | Nahradit font v prezentaci pomocí informací poskytnutých ve sbírce [`FontSubstRule`](/slides/python-net/cs/aspose.slides/fontsubstrule) |
| [`get_fonts(self)`](/slides/python-net/cs/aspose.slides/fontsmanager/get_fonts/#) | Vrací fonty použité v prezentaci |
| [`get_embedded_fonts(self)`](/slides/python-net/cs/aspose.slides/fontsmanager/get_embedded_fonts/#) | Vrací fonty vložené v prezentaci |
| [`remove_embedded_font(self, font_data)`](/slides/python-net/cs/aspose.slides/fontsmanager/remove_embedded_font/#ifontdata) | Odstraní vložený font |
| [`get_font_bytes(self, font_data, font_style)`](/slides/python-net/cs/aspose.slides/fontsmanager/get_font_bytes/#ifontdata-fontstyletype) | Načte pole bajtů představující data fontu pro zadaný styl a data fontu. |
| [`get_font_embedding_level(self, font_bytes, font_name)`](/slides/python-net/cs/aspose.slides/fontsmanager/get_font_embedding_level/#bytes-str) | Určuje úroveň vkládání fontu z daného pole bajtů a názvu fontu. |

### Viz také
* modul [`aspose.slides`](/slides/python-net/cs/aspose.slides)
* knihovna [`Aspose.Slides`](/slides/python-net)