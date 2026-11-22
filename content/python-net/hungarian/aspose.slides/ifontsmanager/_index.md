---
title: IFontsManager class
second_title: Aspose.Slides a Pythonhoz a .NET API referencián keresztül
description: 
type: docs
url: /hu/aspose.slides/ifontsmanager/
---
## IFontsManager osztály

Kezeli a betűtípusokat a prezentációban.

Az IFontsManager típus a következő tagokat tartalmazza:

## Tulajdonságok

| Tulajdonság | Leírás |
| :- | :- |
| [`font_subst_rule_list`](/slides/python-net/hu/aspose.slides/ifontsmanager/font_subst_rule_list/) | Betűtípushelyettesítések, amelyeket a renderelés során használni kell<br/>            Olvasás/írás [`IFontSubstRuleCollection`](/slides/python-net/hu/aspose.slides/ifontsubstrulecollection). |
| [`font_fall_back_rules_collection`](/slides/python-net/hu/aspose.slides/ifontsmanager/font_fall_back_rules_collection/) | A felhasználó FontFallBack szabályok gyűjteményét képviseli a betűtípus-gyűjtemények kezelésére a megfelelő helyettesítések érdekében a fallback funkcióval<br/>            Olvasás/írás [`IFontFallBackRulesCollection`](/slides/python-net/hu/aspose.slides/ifontfallbackrulescollection). |
| [`prefer_registered_fonts_over_embedded`](/slides/python-net/hu/aspose.slides/ifontsmanager/prefer_registered_fonts_over_embedded/) | Megadja, hogy a regisztrált betűtípusok előnyben részesítendők legyenek-e a beágyazott betűtípusokkal szemben, amelyek ugyanazzal a betűtípusnévvel és stílussal rendelkeznek.<br/>            Ha engedélyezve van, a megfelelő beágyazott betűtípusok átmenetileg a megfelelő regisztrált betűtípusokkal lesznek helyettesítve az exportálás során. |

## Módszerek

| Módszer | Leírás |
| :- | :- |
| [`get_substitutions(self)`](/slides/python-net/hu/aspose.slides/ifontsmanager/get_substitutions/#) | Lekéri az információkat a betűtípusokról, amelyeket a prezentáció renderelése során cserélni fognak. |
| [`get_substitutions(self, slides)`](/slides/python-net/hu/aspose.slides/ifontsmanager/get_substitutions/#listint) | Lekéri az információkat a betűtípusokról, amelyeket a megadott diák renderelése során cserélni fognak. |
| [`add_embedded_font(self, font_data, embed_font_rule)`](/slides/python-net/hu/aspose.slides/ifontsmanager/add_embedded_font/#ifontdata-asposeslidesexportembedfontcharacters) | Hozzáadja a beágyazott betűtípust.<br/>            Gondoljunk arra, hogy a legtöbb betűtípus szerzői jogvédelem alatt áll. Először keressük meg a betűtípus licencét <br/>            előre, és ellenőrizzük, hogy szabadon átvihető-e egy másik gépre. ArgumentException dobható, ha a betűtípus adatai None vagy a betűtípus már be van ágyazva |
| [`add_embedded_font(self, font_data, embed_font_rule)`](/slides/python-net/hu/aspose.slides/ifontsmanager/add_embedded_font/#bytes-asposeslidesexportembedfontcharacters) | Hozzáadja a beágyazott betűtípust<br/>            Gondoljunk arra, hogy a legtöbb betűtípus szerzői jogvédelem alatt áll. Először keressük meg a betűtípus licencét <br/>            előre, és ellenőrizzük, hogy szabadon átvihető-e egy másik gépre. ArgumentException dobható, ha a betűtípus adatai None vagy a betűtípus már be van ágyazva |
| [`replace_font(self, source_font, dest_font)`](/slides/python-net/hu/aspose.slides/ifontsmanager/replace_font/#ifontdata-ifontdata) | Betűtípus cseréje a prezentációban |
| [`replace_font(self, subst_rule)`](/slides/python-net/hu/aspose.slides/ifontsmanager/replace_font/#ifontsubstrule) | Betűtípus cseréje a prezentációban a(z) [`IFontSubstRule`](/slides/python-net/hu/aspose.slides/ifontsubstrule)-ben megadott információk felhasználásával |
| [`replace_font(self, subst_rules)`](/slides/python-net/hu/aspose.slides/ifontsmanager/replace_font/#ifontsubstrulecollection) | Betűtípus cseréje a prezentációban a(z) [`IFontSubstRule`](/slides/python-net/hu/aspose.slides/ifontsubstrule) gyűjteményben megadott információk felhasználásával |
| [`get_fonts(self)`](/slides/python-net/hu/aspose.slides/ifontsmanager/get_fonts/#) | Visszaadja a prezentációban használt betűtípusokat |
| [`get_embedded_fonts(self)`](/slides/python-net/hu/aspose.slides/ifontsmanager/get_embedded_fonts/#) | Visszaadja a prezentációba beágyazott betűtípusokat |
| [`remove_embedded_font(self, font_data)`](/slides/python-net/hu/aspose.slides/ifontsmanager/remove_embedded_font/#ifontdata) | Eltávolítja a beágyazott betűtípust |
| [`get_font_bytes(self, font_data, font_style)`](/slides/python-net/hu/aspose.slides/ifontsmanager/get_font_bytes/#ifontdata-fontstyletype) | Lekéri a megadott betűtípus stílushoz és betűtípusadataihoz tartozó bájttömböt. |
| [`get_font_embedding_level(self, font_bytes, font_name)`](/slides/python-net/hu/aspose.slides/ifontsmanager/get_font_embedding_level/#bytes-str) | Meghatározza egy betűtípus beágyazási szintjét a megadott bájttömb és betűtípusnév alapján. |

### Lásd még
* modul [`aspose.slides`](/slides/python-net/hu/aspose.slides)
* könyvtár [`Aspose.Slides`](/slides/python-net)