---
title: FontsManager class
second_title: Aspose.Slides dla Pythona przez .NET - odniesienie API
description: 
type: docs
url: /pl/aspose.slides/fontsmanager/
---
## FontsManager klasa

Zarządza czcionkami w całej prezentacji.

Typ FontsManager udostępnia następujące elementy:

## Właściwości

| Właściwość | Opis |
| :- | :- |
| [`font_subst_rule_list`](/slides/python-net/pl/aspose.slides/fontsmanager/font_subst_rule_list/) | Zastąpienia czcionek używane podczas renderowania.<br/>            Odczyt/zapis [`IFontSubstRuleCollection`](/slides/python-net/pl/aspose.slides/ifontsubstrulecollection). |
| [`font_fall_back_rules_collection`](/slides/python-net/pl/aspose.slides/fontsmanager/font_fall_back_rules_collection/) | Reprezentuje kolekcję reguł FontFallBack użytkownika służącą do zarządzania zestawami czcionek w celu prawidłowych zastąpień przez funkcję awaryjną.<br/>            Odczyt/zapis [`IFontFallBackRulesCollection`](/slides/python-net/pl/aspose.slides/ifontfallbackrulescollection). |
| [`prefer_registered_fonts_over_embedded`](/slides/python-net/pl/aspose.slides/fontsmanager/prefer_registered_fonts_over_embedded/) | Określa, czy zarejestrowane czcionki powinny mieć pierwszeństwo przed osadzonymi czcionkami o tej samej nazwie i stylu.<br/>            Gdy włączone, dopasowane czcionki osadzone są tymczasowo zamieniane na odpowiednie czcionki zarejestrowane podczas eksportu. |

## Metody

| Metoda | Opis |
| :- | :- |
| [`get_substitutions(self)`](/slides/python-net/pl/aspose.slides/fontsmanager/get_substitutions/#) | Pobiera informacje o czcionkach, które zostaną zastąpione podczas renderowania prezentacji. |
| [`get_substitutions(self, slides)`](/slides/python-net/pl/aspose.slides/fontsmanager/get_substitutions/#listint) | Pobiera informacje o czcionkach, które zostaną zastąpione podczas renderowania określonych slajdów. |
| [`add_embedded_font(self, font_data, embed_font_rule)`](/slides/python-net/pl/aspose.slides/fontsmanager/add_embedded_font/#ifontdata-asposeslidesexportembedfontcharacters) | Dodaje czcionkę osadzoną<br/>            Pamiętaj, że większość czcionek jest objęta prawami autorskimi. Najpierw znajdź licencję czcionki i zweryfikuj, czy może być swobodnie przenoszona na inny komputer. ArgumentException może zostać rzucony, jeśli dane czcionki są None lub ta czcionka jest już osadzona |
| [`add_embedded_font(self, font_data, embed_font_rule)`](/slides/python-net/pl/aspose.slides/fontsmanager/add_embedded_font/#bytes-asposeslidesexportembedfontcharacters) | Dodaje czcionkę osadzoną<br/>            Pamiętaj, że większość czcionek jest objęta prawami autorskimi. Najpierw znajdź licencję czcionki i zweryfikuj, czy może być swobodnie przenoszona na inny komputer. ArgumentException może zostać rzucony, jeśli dane czcionki są None lub ta czcionka jest już osadzona |
| [`replace_font(self, source_font, dest_font)`](/slides/python-net/pl/aspose.slides/fontsmanager/replace_font/#ifontdata-ifontdata) | Zastępuje czcionkę w prezentacji |
| [`replace_font(self, subst_rule)`](/slides/python-net/pl/aspose.slides/fontsmanager/replace_font/#ifontsubstrule) | Zastępuje czcionkę w prezentacji przy użyciu informacji podanych w [`FontSubstRule`](/slides/python-net/pl/aspose.slides/fontsubstrule) |
| [`replace_font(self, subst_rules)`](/slides/python-net/pl/aspose.slides/fontsmanager/replace_font/#ifontsubstrulecollection) | Zastępuje czcionkę w prezentacji przy użyciu informacji podanych w kolekcji [`FontSubstRule`](/slides/python-net/pl/aspose.slides/fontsubstrule) |
| [`get_fonts(self)`](/slides/python-net/pl/aspose.slides/fontsmanager/get_fonts/#) | Zwraca czcionki użyte w prezentacji |
| [`get_embedded_fonts(self)`](/slides/python-net/pl/aspose.slides/fontsmanager/get_embedded_fonts/#) | Zwraca czcionki osadzone w prezentacji |
| [`remove_embedded_font(self, font_data)`](/slides/python-net/pl/aspose.slides/fontsmanager/remove_embedded_font/#ifontdata) | Usuwa czcionkę osadzoną |
| [`get_font_bytes(self, font_data, font_style)`](/slides/python-net/pl/aspose.slides/fontsmanager/get_font_bytes/#ifontdata-fontstyletype) | Pobiera tablicę bajtów reprezentującą dane czcionki dla określonego stylu i danych czcionki. |
| [`get_font_embedding_level(self, font_bytes, font_name)`](/slides/python-net/pl/aspose.slides/fontsmanager/get_font_embedding_level/#bytes-str) | Określa poziom osadzenia czcionki na podstawie podanej tablicy bajtów i nazwy czcionki. |


### Zobacz także
* moduł [`aspose.slides`](/slides/python-net/pl/aspose.slides)
* biblioteka [`Aspose.Slides`](/slides/python-net)