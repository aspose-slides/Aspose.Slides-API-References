---
title: IFontsManager class
second_title: Aspose.Slides dla Pythona – referencja API .NET
description: 
type: docs
url: /pl/aspose.slides/ifontsmanager/
---
## IFontsManager klasa

Zarządza czcionkami w całej prezentacji.

Typ IFontsManager udostępnia następujące elementy:

## Właściwości

| Właściwość | Opis |
| :- | :- |
| [`font_subst_rule_list`](/slides/python-net/pl/aspose.slides/ifontsmanager/font_subst_rule_list/) | Zastąpienia czcionek używane podczas renderowania<br/>            Odczyt/zapis [`IFontSubstRuleCollection`](/slides/python-net/pl/aspose.slides/ifontsubstrulecollection). |
| [`font_fall_back_rules_collection`](/slides/python-net/pl/aspose.slides/ifontsmanager/font_fall_back_rules_collection/) | Reprezentuje kolekcję reguł FontFallBack użytkownika służącą do zarządzania zbiorami czcionek w celu prawidłowych zastąpień za pomocą funkcjonalności odzyskiwania<br/>            Odczyt/zapis [`IFontFallBackRulesCollection`](/slides/python-net/pl/aspose.slides/ifontfallbackrulescollection). |

## Metody

| Metoda | Opis |
| :- | :- |
| [`get_substitutions(self)`](/slides/python-net/pl/aspose.slides/ifontsmanager/get_substitutions/#) | Pobiera informacje o czcionkach, które zostaną zastąpione podczas renderowania prezentacji. |
| [`get_substitutions(self, slides)`](/slides/python-net/pl/aspose.slides/ifontsmanager/get_substitutions/#listint) | Pobiera informacje o czcionkach, które zostaną zastąpione podczas renderowania określonych slajdów. |
| [`add_embedded_font(self, font_data, embed_font_rule)`](/slides/python-net/pl/aspose.slides/ifontsmanager/add_embedded_font/#ifontdata-asposeslidesexportembedfontcharacters) | Dodaje osadzoną czcionkę.<br/>            Pamiętaj, że większość czcionek jest objęta prawami autorskimi. Najpierw znajdź licencję <br/>            czcionki i upewnij się, że może być ona swobodnie przeniesiona na inny komputer. ArgumentException może być rzucony, jeśli dane czcionki są None lub czcionka jest już osadzona |
| [`add_embedded_font(self, font_data, embed_font_rule)`](/slides/python-net/pl/aspose.slides/ifontsmanager/add_embedded_font/#bytes-asposeslidesexportembedfontcharacters) | Dodaje osadzoną czcionkę.<br/>            Pamiętaj, że większość czcionek jest objęta prawami autorskimi. Najpierw znajdź licencję <br/>            czcionki i upewnij się, że może być ona swobodnie przeniesiona na inny komputer. ArgumentException może być rzucony, jeśli dane czcionki są None lub czcionka jest już osadzona |
| [`replace_font(self, source_font, dest_font)`](/slides/python-net/pl/aspose.slides/ifontsmanager/replace_font/#ifontdata-ifontdata) | Zastąp czcionkę w prezentacji |
| [`replace_font(self, subst_rule)`](/slides/python-net/pl/aspose.slides/ifontsmanager/replace_font/#ifontsubstrule) | Zastąp czcionkę w prezentacji, używając informacji podanych w [`IFontSubstRule`](/slides/python-net/pl/aspose.slides/ifontsubstrule) |
| [`replace_font(self, subst_rules)`](/slides/python-net/pl/aspose.slides/ifontsmanager/replace_font/#ifontsubstrulecollection) | Zastąp czcionkę w prezentacji, używając informacji podanych w zbiorze [`IFontSubstRule`](/slides/python-net/pl/aspose.slides/ifontsubstrule) |
| [`get_fonts(self)`](/slides/python-net/pl/aspose.slides/ifontsmanager/get_fonts/#) | Zwraca czcionki użyte w prezentacji |
| [`get_embedded_fonts(self)`](/slides/python-net/pl/aspose.slides/ifontsmanager/get_embedded_fonts/#) | Zwraca czcionki osadzone w prezentacji |
| [`remove_embedded_font(self, font_data)`](/slides/python-net/pl/aspose.slides/ifontsmanager/remove_embedded_font/#ifontdata) | Usuwa osadzoną czcionkę |
| [`get_font_bytes(self, font_data, font_style)`](/slides/python-net/pl/aspose.slides/ifontsmanager/get_font_bytes/#ifontdata-fontstyletype) | Pobiera tablicę bajtów reprezentującą dane czcionki dla określonego stylu czcionki i danych czcionki. |
| [`get_font_embedding_level(self, font_bytes, font_name)`](/slides/python-net/pl/aspose.slides/ifontsmanager/get_font_embedding_level/#bytes-str) | Określa poziom osadzania czcionki na podstawie podanej tablicy bajtów i nazwy czcionki. |

### Zobacz także
* moduł [`aspose.slides`](/slides/python-net/pl/aspose.slides)
* biblioteka [`Aspose.Slides`](/slides/python-net)