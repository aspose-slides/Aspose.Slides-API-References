---
title: IFontsManager class
second_title: Aspose.Slides für Python über .NET API-Referenz
description: 
type: docs
url: /de/aspose.slides/ifontsmanager/
---
## IFontsManager Klasse

Verwaltet Schriftarten in der gesamten Präsentation.

Der IFontsManager Typ stellt die folgenden Mitglieder bereit:

## Eigenschaften

| Eigenschaft | Beschreibung |
| :- | :- |
| [`font_subst_rule_list`](/slides/python-net/de/aspose.slides/ifontsmanager/font_subst_rule_list/) | Schriftartenersetzungen, die beim Rendern verwendet werden<br/> Lese-/Schreib [`IFontSubstRuleCollection`](/slides/python-net/de/aspose.slides/ifontsubstrulecollection). |
| [`font_fall_back_rules_collection`](/slides/python-net/de/aspose.slides/ifontsmanager/font_fall_back_rules_collection/) | Stellt eine Benutzersammlung von FontFallBack-Regeln zur Verwaltung von Schriftartensammlungen für korrekte Ersetzungen durch die Fallback-Funktionalität dar<br/> Lese-/Schreib [`IFontFallBackRulesCollection`](/slides/python-net/de/aspose.slides/ifontfallbackrulescollection). |

## Methoden

| Methode | Beschreibung |
| :- | :- |
| [`get_substitutions(self)`](/slides/python-net/de/aspose.slides/ifontsmanager/get_substitutions/#) | Ermittelt die Informationen über Schriftarten, die bei der Darstellung der Präsentation ersetzt werden. |
| [`get_substitutions(self, slides)`](/slides/python-net/de/aspose.slides/ifontsmanager/get_substitutions/#listint) | Ermittelt die Informationen über Schriftarten, die beim Rendern der angegebenen Folien ersetzt werden. |
| [`add_embedded_font(self, font_data, embed_font_rule)`](/slides/python-net/de/aspose.slides/ifontsmanager/add_embedded_font/#ifontdata-asposeslidesexportembedfontcharacters) | Fügt die eingebettete Schriftart hinzu.<br/> Beachten Sie beim Kopieren von Schriftarten, dass die meisten Schriftarten urheberrechtlich geschützt sind. Ermitteln Sie zunächst die Lizenz einer Schriftart und überprüfen Sie, ob sie frei auf einen anderen Rechner übertragen werden kann. Eine ArgumentException kann ausgelöst werden, wenn die Schriftartdaten None sind oder diese Schriftart bereits eingebettet ist. |
| [`add_embedded_font(self, font_data, embed_font_rule)`](/slides/python-net/de/aspose.slides/ifontsmanager/add_embedded_font/#bytes-asposeslidesexportembedfontcharacters) | Fügt die eingebettete Schriftart hinzu<br/> Beachten Sie beim Hinzufügen von Schriftarten, dass die meisten Schriftarten urheberrechtlich geschützt sind. Ermitteln Sie zunächst die Lizenz einer Schriftart und überprüfen Sie, ob sie frei auf einen anderen Rechner übertragen werden kann. Eine ArgumentException kann ausgelöst werden, wenn die Schriftartdaten None sind oder diese Schriftart bereits eingebettet ist. |
| [`replace_font(self, source_font, dest_font)`](/slides/python-net/de/aspose.slides/ifontsmanager/replace_font/#ifontdata-ifontdata) | Ersetzt die Schriftart in der Präsentation |
| [`replace_font(self, subst_rule)`](/slides/python-net/de/aspose.slides/ifontsmanager/replace_font/#ifontsubstrule) | Ersetzt die Schriftart in der Präsentation mithilfe der in [`IFontSubstRule`](/slides/python-net/de/aspose.slides/ifontsubstrule) bereitgestellten Informationen |
| [`replace_font(self, subst_rules)`](/slides/python-net/de/aspose.slides/ifontsmanager/replace_font/#ifontsubstrulecollection) | Ersetzt die Schriftart in der Präsentation mithilfe der in der Sammlung von [`IFontSubstRule`](/slides/python-net/de/aspose.slides/ifontsubstrule) bereitgestellten Informationen |
| [`get_fonts(self)`](/slides/python-net/de/aspose.slides/ifontsmanager/get_fonts/#) | Gibt die in der Präsentation verwendeten Schriftarten zurück |
| [`get_embedded_fonts(self)`](/slides/python-net/de/aspose.slides/ifontsmanager/get_embedded_fonts/#) | Gibt die in der Präsentation eingebetteten Schriftarten zurück |
| [`remove_embedded_font(self, font_data)`](/slides/python-net/de/aspose.slides/ifontsmanager/remove_embedded_font/#ifontdata) | Entfernt die eingebettete Schriftart |
| [`get_font_bytes(self, font_data, font_style)`](/slides/python-net/de/aspose.slides/ifontsmanager/get_font_bytes/#ifontdata-fontstyletype) | Ruft das Byte-Array ab, das die Schriftartdaten für einen angegebenen Schriftstil und Schriftartdaten darstellt. |
| [`get_font_embedding_level(self, font_bytes, font_name)`](/slides/python-net/de/aspose.slides/ifontsmanager/get_font_embedding_level/#bytes-str) | Bestimmt die Einbettungsstufe einer Schriftart aus dem angegebenen Byte-Array und dem Schriftartnamen. |

### Siehe Auch
* Modul [`aspose.slides`](/slides/python-net/de/aspose.slides)
* Bibliothek [`Aspose.Slides`](/slides/python-net)