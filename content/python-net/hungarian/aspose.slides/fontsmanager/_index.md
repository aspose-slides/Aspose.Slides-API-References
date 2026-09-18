---
title: FontsManager class
second_title: Aspose.Slides a Pythonhoz .NET API referencia
description: 
type: docs
url: /hu/aspose.slides/fontsmanager/
---
## FontsManager osztály

A betűtípusok kezelését végzi a teljes bemutatóban.

A FontsManager típus a következő tagokat tartalmazza:

## Tulajdonságok

| Property | Description |
| :- | :- |
| [`font_subst_rule_list`](/slides/python-net/hu/aspose.slides/fontsmanager/font_subst_rule_list/) | Font substitutions to use when rendering.<br/>            Olvasás/írás [`IFontSubstRuleCollection`](/slides/python-net/hu/aspose.slides/ifontsubstrulecollection). |
| [`font_fall_back_rules_collection`](/slides/python-net/hu/aspose.slides/fontsmanager/font_fall_back_rules_collection/) | Represents a user's collection of FontFallBack rules for managing of collections of fonts for proper substitutions by fallback functionality<br/>            Olvasás/írás [`IFontFallBackRulesCollection`](/slides/python-net/hu/aspose.slides/ifontfallbackrulescollection). |

## Módszerek

| Method | Description |
| :- | :- |
| [`get_substitutions(self)`](/slides/python-net/hu/aspose.slides/fontsmanager/get_substitutions/#) | Gets the information about fonts that will be replaced on the presentation's rendering. |
| [`get_substitutions(self, slides)`](/slides/python-net/hu/aspose.slides/fontsmanager/get_substitutions/#listint) | Gets the information about fonts that will be replaced during rendering of the specified slides. |
| [`add_embedded_font(self, font_data, embed_font_rule)`](/slides/python-net/hu/aspose.slides/fontsmanager/add_embedded_font/#ifontdata-asposeslidesexportembedfontcharacters) | Adds the embedded font<br/>            Tartsa szem előtt, hogy a legtöbb betűtípus szerzői jogvédelem alatt áll. Először keresse meg a betűtípus licencét, és ellenőrizze, hogy szabadon áthelyezhető-e egy másik gépre. ArgumentException kivétel léphet fel, ha a betűtípus adatai None értékűek vagy a betűtípus már be van ágyazva |
| [`add_embedded_font(self, font_data, embed_font_rule)`](/slides/python-net/hu/aspose.slides/fontsmanager/add_embedded_font/#bytes-asposeslidesexportembedfontcharacters) | Adds the embedded font<br/>            Tartsa szem előtt, hogy a legtöbb betűtípus szerzői jogvédelem alatt áll. Először keresse meg a betűtípus licencét, és ellenőrizze, hogy szabadon áthelyezhető-e egy másik gépre. ArgumentException kivétel léphet fel, ha a betűtípus adatai None értékűek vagy a betűtípus már be van ágyazva |
| [`replace_font(self, source_font, dest_font)`](/slides/python-net/hu/aspose.slides/fontsmanager/replace_font/#ifontdata-ifontdata) | Replace font in presentation |
| [`replace_font(self, subst_rule)`](/slides/python-net/hu/aspose.slides/fontsmanager/replace_font/#ifontsubstrule) | Replace font in presentation using information provided in [`FontSubstRule`](/slides/python-net/hu/aspose.slides/fontsubstrule) |
| [`replace_font(self, subst_rules)`](/slides/python-net/hu/aspose.slides/fontsmanager/replace_font/#ifontsubstrulecollection) | Replace font in presentation using information provided in collection of [`FontSubstRule`](/slides/python-net/hu/aspose.slides/fontsubstrule) |
| [`get_fonts(self)`](/slides/python-net/hu/aspose.slides/fontsmanager/get_fonts/#) | Returns the fonts used in the presentation |
| [`get_embedded_fonts(self)`](/slides/python-net/hu/aspose.slides/fontsmanager/get_embedded_fonts/#) | Returns the fonts embedded in the presentation |
| [`remove_embedded_font(self, font_data)`](/slides/python-net/hu/aspose.slides/fontsmanager/remove_embedded_font/#ifontdata) | Removes the embedded font |
| [`get_font_bytes(self, font_data, font_style)`](/slides/python-net/hu/aspose.slides/fontsmanager/get_font_bytes/#ifontdata-fontstyletype) | Retrieves the byte array representing the font data for a specified font style and font data. |
| [`get_font_embedding_level(self, font_bytes, font_name)`](/slides/python-net/hu/aspose.slides/fontsmanager/get_font_embedding_level/#bytes-str) | Determines the embedding level of a font from the given byte array and font name. |

### Lásd még
* modul [`aspose.slides`](/slides/python-net/hu/aspose.slides)
* könyvtár [`Aspose.Slides`](/slides/python-net)