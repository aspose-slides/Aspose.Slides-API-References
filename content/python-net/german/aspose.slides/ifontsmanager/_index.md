---
title: IFontsManager class
second_title: Aspose.Slides für Python über .NET API-Referenz
description: 
type: docs
url: /de/aspose.slides/ifontsmanager/
---
## IFontsManager Klasse

Verwaltet Schriftarten über die gesamte Präsentation.

Der IFontsManager Typ stellt die folgenden Member bereit:

## Eigenschaften

| Eigenschaft | Beschreibung |
| :- | :- |
| [`font_subst_rule_list`](/slides/python-net/de/aspose.slides/ifontsmanager/font_subst_rule_list/) | Schriftart-Substitutionen, die beim Rendern verwendet werden<br/>            Lesen/Schreiben [`IFontSubstRuleCollection`](/slides/python-net/de/aspose.slides/ifontsubstrulecollection). |
| [`font_fall_back_rules_collection`](/slides/python-net/de/aspose.slides/ifontsmanager/font_fall_back_rules_collection/) | Repräsentiert die Sammlung von FontFallBack-Regeln eines Benutzers zur Verwaltung von Schriftsammlungen für korrekte Substitutionen durch Fallback-Funktionalität<br/>            Lesen/Schreiben [`IFontFallBackRulesCollection`](/slides/python-net/de/aspose.slides/ifontfallbackrulescollection). |
| [`prefer_registered_fonts_over_embedded`](/slides/python-net/de/aspose.slides/ifontsmanager/prefer_registered_fonts_over_embedded/) | Gibt an, ob registrierte Schriftarten gegenüber eingebetteten Schriftarten mit demselben Schriftartnamen und Stil bevorzugt werden sollen.<br/>            Wenn aktiviert, werden passende eingebettete Schriftarten während des Exports vorübergehend durch entsprechende registrierte Schriftarten ersetzt. |

## Methoden

| Methode | Beschreibung |
| :- | :- |
| [`get_substitutions(self)`](/slides/python-net/de/aspose.slides/ifontsmanager/get_substitutions/#) | Ruft die Informationen über Schriftarten ab, die beim Rendern der Präsentation ersetzt werden. |
| [`get_substitutions(self, slides)`](/slides/python-net/de/aspose.slides/ifontsmanager/get_substitutions/#listint) | Ruft die Informationen über Schriftarten ab, die beim Rendern der angegebenen Folien ersetzt werden. |
| [`add_embedded_font(self, font_data, embed_font_rule)`](/slides/python-net/de/aspose.slides/ifontsmanager/add_embedded_font/#ifontdata-asposeslidesexportembedfontcharacters) | Fügt die eingebettete Schriftart hinzu.<br/>            Beachten Sie, dass beim Kopieren von Schriftarten die meisten urheberrechtlich geschützt sind. Finden Sie zuerst die Lizenz einer Schriftart <br/>            im Voraus und prüfen Sie, ob sie frei auf einen anderen Rechner übertragen werden kann. Eine ArgumentException kann ausgelöst werden, wenn die Schriftartdaten None sind oder die Schriftart bereits eingebettet ist. |
| [`add_embedded_font(self, font_data, embed_font_rule)`](/slides/python-net/de/aspose.slides/ifontsmanager/add_embedded_font/#bytes-asposeslidesexportembedfontcharacters) | Fügt die eingebettete Schriftart hinzu<br/>            Beachten Sie, dass beim Hinzufügen von Schriftarten die meisten urheberrechtlich geschützt sind. Finden Sie zuerst die Lizenz einer Schriftart <br/>            im Voraus und prüfen Sie, ob sie frei auf einen anderen Rechner übertragen werden kann. Eine ArgumentException kann ausgelöst werden, wenn die Schriftartdaten None sind oder die Schriftart bereits eingebettet ist. |
| [`replace_font(self, source_font, dest_font)`](/slides/python-net/de/aspose.slides/ifontsmanager/replace_font/#ifontdata-ifontdata) | Ersetzt Schriftart in der Präsentation |
| [`replace_font(self, subst_rule)`](/slides/python-net/de/aspose.slides/ifontsmanager/replace_font/#ifontsubstrule) | Ersetzt Schriftart in der Präsentation mithilfe der in [`IFontSubstRule`](/slides/python-net/de/aspose.slides/ifontsubstrule) bereitgestellten Informationen |
| [`replace_font(self, subst_rules)`](/slides/python-net/de/aspose.slides/ifontsmanager/replace_font/#ifontsubstrulecollection) | Ersetzt Schriftart in der Präsentation mithilfe der in der Sammlung von [`IFontSubstRule`](/slides/python-net/de/aspose.slides/ifontsubstrule) bereitgestellten Informationen |
| [`get_fonts(self)`](/slides/python-net/de/aspose.slides/ifontsmanager/get_fonts/#) | Gibt die in der Präsentation verwendeten Schriftarten zurück |
| [`get_embedded_fonts(self)`](/slides/python-net/de/aspose.slides/ifontsmanager/get_embedded_fonts/#) | Gibt die in der Präsentation eingebetteten Schriftarten zurück |
| [`remove_embedded_font(self, font_data)`](/slides/python-net/de/aspose.slides/ifontsmanager/remove_embedded_font/#ifontdata) | Entfernt die eingebettete Schriftart |
| [`get_font_bytes(self, font_data, font_style)`](/slides/python-net/de/aspose.slides/ifontsmanager/get_font_bytes/#ifontdata-fontstyletype) | Ruft das Byte-Array ab, das die Schriftartdaten für einen angegebenen Schriftstil und Schriftartdaten darstellt. |
| [`get_font_embedding_level(self, font_bytes, font_name)`](/slides/python-net/de/aspose.slides/ifontsmanager/get_font_embedding_level/#bytes-str) | Bestimmt das Einbettungslevel einer Schriftart aus dem angegebenen Byte-Array und dem Schriftartnamen. |

### Siehe auch
* Modul [`aspose.slides`](/slides/python-net/de/aspose.slides)
* Bibliothek [`Aspose.Slides`](/slides/python-net)