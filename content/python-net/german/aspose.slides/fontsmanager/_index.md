---
title: FontsManager class
second_title: Aspose.Slides für Python über .NET API-Referenz
description: 
type: docs
url: /de/aspose.slides/fontsmanager/
---
## FontsManager Klasse

Verwaltert Schriftarten in der gesamten Präsentation.

Der FontsManager-Typ stellt die folgenden Mitglieder bereit:

## Eigenschaften

| Eigenschaft | Beschreibung |
| :- | :- |
| [`font_subst_rule_list`](/slides/python-net/de/aspose.slides/fontsmanager/font_subst_rule_list/) | Font substitutions to use when rendering.<br/>            Lesen/Schreiben [`IFontSubstRuleCollection`](/slides/python-net/de/aspose.slides/ifontsubstrulecollection). |
| [`font_fall_back_rules_collection`](/slides/python-net/de/aspose.slides/fontsmanager/font_fall_back_rules_collection/) | Represents a user's collection of FontFallBack rules for managing of collections of fonts for proper substitutions by fallback functionality<br/>            Lesen/Schreiben [`IFontFallBackRulesCollection`](/slides/python-net/de/aspose.slides/ifontfallbackrulescollection). |

## Methoden

| Methode | Beschreibung |
| :- | :- |
| [`get_substitutions(self)`](/slides/python-net/de/aspose.slides/fontsmanager/get_substitutions/#) | Ruft die Informationen zu Schriftarten ab, die bei der Darstellung der Präsentation ersetzt werden. |
| [`get_substitutions(self, slides)`](/slides/python-net/de/aspose.slides/fontsmanager/get_substitutions/#listint) | Ruft die Informationen zu Schriftarten ab, die bei der Darstellung der angegebenen Folien ersetzt werden. |
| [`add_embedded_font(self, font_data, embed_font_rule)`](/slides/python-net/de/aspose.slides/fontsmanager/add_embedded_font/#ifontdata-asposeslidesexportembedfontcharacters) | Fügt die eingebettete Schriftart hinzu<br/>            Beachten Sie beim Kopieren von Schriftarten, dass die meisten urheberrechtlich geschützt sind. Zuerst die Lizenz einer Schriftart ermitteln<br/>            und prüfen, ob sie frei auf einen anderen Rechner übertragen werden kann. Eine ArgumentException kann ausgelöst werden, wenn die Schriftartdaten None sind oder diese Schriftart bereits eingebettet ist. |
| [`add_embedded_font(self, font_data, embed_font_rule)`](/slides/python-net/de/aspose.slides/fontsmanager/add_embedded_font/#bytes-asposeslidesexportembedfontcharacters) | Fügt die eingebettete Schriftart hinzu<br/>            Beachten Sie beim Kopieren von Schriftarten, dass die meisten urheberrechtlich geschützt sind. Zuerst die Lizenz einer Schriftart ermitteln<br/>            und prüfen, ob sie frei auf einen anderen Rechner übertragen werden kann. Eine ArgumentException kann ausgelöst werden, wenn die Schriftartdaten None sind oder diese Schriftart bereits eingebettet ist. |
| [`replace_font(self, source_font, dest_font)`](/slides/python-net/de/aspose.slides/fontsmanager/replace_font/#ifontdata-ifontdata) | Ersetzt die Schriftart in der Präsentation |
| [`replace_font(self, subst_rule)`](/slides/python-net/de/aspose.slides/fontsmanager/replace_font/#ifontsubstrule) | Ersetzt die Schriftart in der Präsentation mithilfe der in [`FontSubstRule`](/slides/python-net/de/aspose.slides/fontsubstrule) bereitgestellten Informationen |
| [`replace_font(self, subst_rules)`](/slides/python-net/de/aspose.slides/fontsmanager/replace_font/#ifontsubstrulecollection) | Ersetzt die Schriftart in der Präsentation mithilfe der in der Sammlung von [`FontSubstRule`](/slides/python-net/de/aspose.slides/fontsubstrule) bereitgestellten Informationen |
| [`get_fonts(self)`](/slides/python-net/de/aspose.slides/fontsmanager/get_fonts/#) | Gibt die in der Präsentation verwendeten Schriftarten zurück |
| [`get_embedded_fonts(self)`](/slides/python-net/de/aspose.slides/fontsmanager/get_embedded_fonts/#) | Gibt die in der Präsentation eingebetteten Schriftarten zurück |
| [`remove_embedded_font(self, font_data)`](/slides/python-net/de/aspose.slides/fontsmanager/remove_embedded_font/#ifontdata) | Entfernt die eingebettete Schriftart |
| [`get_font_bytes(self, font_data, font_style)`](/slides/python-net/de/aspose.slides/fontsmanager/get_font_bytes/#ifontdata-fontstyletype) | Ruft das Byte-Array ab, das die Schriftartdaten für einen angegebenen Schriftsstil und Schriftartdaten darstellt. |
| [`get_font_embedding_level(self, font_bytes, font_name)`](/slides/python-net/de/aspose.slides/fontsmanager/get_font_embedding_level/#bytes-str) | Bestimmt das Einbettungsniveau einer Schriftart aus dem angegebenen Byte-Array und dem Schriftartnamen. |

### Siehe Auch
* Modul [`aspose.slides`](/slides/python-net/de/aspose.slides)
* Bibliothek [`Aspose.Slides`](/slides/python-net)