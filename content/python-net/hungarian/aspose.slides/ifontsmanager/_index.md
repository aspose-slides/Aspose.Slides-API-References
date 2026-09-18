---
title: IFontsManager class
second_title: Aspose.Slides for Python via .NET API Referencia
description: 
type: docs
url: /hu/aspose.slides/ifontsmanager/
---
## IFontsManager osztály

Kezeli a betűtípusokat a prezentációban.

Az IFontsManager típus a következő tagokat teszi közzé:

## Tulajdonságok

| Property | Description |
| :- | :- |
| [`font_subst_rule_list`](/slides/python-net/hu/aspose.slides/ifontsmanager/font_subst_rule_list/) | Betűtípushelyettesítések, amelyeket a renderelés során használni kell<br/>            Olvasás/írás [`IFontSubstRuleCollection`](/slides/python-net/hu/aspose.slides/ifontsubstrulecollection). |
| [`font_fall_back_rules_collection`](/slides/python-net/hu/aspose.slides/ifontsmanager/font_fall_back_rules_collection/) | A felhasználó FontFallBack szabályainak gyűjteménye a betűtípusok gyűjteményeinek megfelelő helyettesítésének kezeléséhez<br/>            Olvasás/írás [`IFontFallBackRulesCollection`](/slides/python-net/hu/aspose.slides/ifontfallbackrulescollection). |

## Módszerek

| Method | Description |
| :- | :- |
| [`get_substitutions(self)`](/slides/python-net/hu/aspose.slides/ifontsmanager/get_substitutions/#) | Lekéri a betűtípusokról a prezentáció renderelése során cserélendő információkat. |
| [`get_substitutions(self, slides)`](/slides/python-net/hu/aspose.slides/ifontsmanager/get_substitutions/#listint) | Lekéri a betűtípusokra vonatkozó információkat, amelyeket a megadott diák renderelése során cserélnek. |
| [`add_embedded_font(self, font_data, embed_font_rule)`](/slides/python-net/hu/aspose.slides/ifontsmanager/add_embedded_font/#ifontdata-asposeslidesexportembedfontcharacters) | Hozzáadja a beágyazott betűtípust.<br/>            Ne feledje, hogy a legtöbb betűtípus szerzői jogvédelem alatt áll a másoláskor. Először keresse meg a betűtípus licencét <br/>            és ellenőrizze, hogy szabadon átvihető-e egy másik gépre. ArgumentException dobható, ha a betűtípus adat None, vagy a betűtípus már be van ágyazva |
| [`add_embedded_font(self, font_data, embed_font_rule)`](/slides/python-net/hu/aspose.slides/ifontsmanager/add_embedded_font/#bytes-asposeslidesexportembedfontcharacters) | Hozzáadja a beágyazott betűtípust.<br/>            Ne feledje, hogy a legtöbb betűtípus szerzői jogvédelem alatt áll a hozzáadáskor. Először keresse meg a betűtípus licencét <br/>            és ellenőrizze, hogy szabadon átvihető-e egy másik gépre. ArgumentException dobható, ha a betűtípus adat None, vagy a betűtípus már be van ágyazva |
| [`replace_font(self, source_font, dest_font)`](/slides/python-net/hu/aspose.slides/ifontsmanager/replace_font/#ifontdata-ifontdata) | Betűtípus cseréje a prezentációban |
| [`replace_font(self, subst_rule)`](/slides/python-net/hu/aspose.slides/ifontsmanager/replace_font/#ifontsubstrule) | Betűtípus cseréje a prezentációban a [`IFontSubstRule`](/slides/python-net/hu/aspose.slides/ifontsubstrule)-ben megadott információk alapján |
| [`replace_font(self, subst_rules)`](/slides/python-net/hu/aspose.slides/ifontsmanager/replace_font/#ifontsubstrulecollection) | Betűtípus cseréje a prezentációban a [`IFontSubstRule`](/slides/python-net/hu/aspose.slides/ifontsubstrule) gyűjteményben megadott információk alapján |
| [`get_fonts(self)`](/slides/python-net/hu/aspose.slides/ifontsmanager/get_fonts/#) | Visszaadja a prezentációban használt betűtípusokat |
| [`get_embedded_fonts(self)`](/slides/python-net/hu/aspose.slides/ifontsmanager/get_embedded_fonts/#) | Visszaadja a prezentációba beágyazott betűtípusokat |
| [`remove_embedded_font(self, font_data)`](/slides/python-net/hu/aspose.slides/ifontsmanager/remove_embedded_font/#ifontdata) | Eltávolítja a beágyazott betűtípust |
| [`get_font_bytes(self, font_data, font_style)`](/slides/python-net/hu/aspose.slides/ifontsmanager/get_font_bytes/#ifontdata-fontstyletype) | Lekéri a megadott betűtípus stílushoz és betűtípus adathoz tartozó byte tömböt, amely a betűtípus adatot ábrázolja. |
| [`get_font_embedding_level(self, font_bytes, font_name)`](/slides/python-net/hu/aspose.slides/ifontsmanager/get_font_embedding_level/#bytes-str) | Meghatározza a betűtípus beágyazási szintjét a megadott byte tömbből és betűtípus nevéből. |


### Lásd még
* modul [`aspose.slides`](/slides/python-net/hu/aspose.slides)
* könyvtár [`Aspose.Slides`](/slides/python-net)