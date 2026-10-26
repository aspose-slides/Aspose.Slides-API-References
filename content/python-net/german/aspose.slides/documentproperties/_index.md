---
title: DocumentProperties class
second_title: Aspose.Slides für Python über .NET API-Referenz
description: 
type: docs
url: /de/aspose.slides/documentproperties/
---
## DocumentProperties Klasse

Stellt die Eigenschaften einer Präsentation dar.

Der Typ DocumentProperties stellt die folgenden Member bereit:

## Konstruktoren

| Konstruktor | Beschreibung |
| :- | :- |
| [`__init__(self)`](/slides/python-net/de/aspose.slides/documentproperties/__init__/#) | Initialisiert eine neue Instanz der Klasse [`DocumentProperties`](/slides/python-net/de/aspose.slides/documentproperties). |

## Eigenschaften

| Eigenschaft | Beschreibung |
| :- | :- |
| [`app_version`](/slides/python-net/de/aspose.slides/documentproperties/app_version/) | Gibt die App-Version zurück.<br/>            Nur lesend **str**. |
| [`name_of_application`](/slides/python-net/de/aspose.slides/documentproperties/name_of_application/) | Gibt den Namen der Anwendung zurück oder legt ihn fest.<br/>            Lesen/Schreiben **str**. |
| [`company`](/slides/python-net/de/aspose.slides/documentproperties/company/) | Gibt die Firmen-Eigenschaft zurück oder legt sie fest.<br/>            Lesen/Schreiben **str**. |
| [`manager`](/slides/python-net/de/aspose.slides/documentproperties/manager/) | Gibt die Manager-Eigenschaft zurück oder legt sie fest.<br/>            Lesen/Schreiben **str**. |
| [`presentation_format`](/slides/python-net/de/aspose.slides/documentproperties/presentation_format/) | Gibt das beabsichtigte Format einer Präsentation zurück oder legt es fest.<br/>            Lesen/Schreiben **str**. |
| [`shared_doc`](/slides/python-net/de/aspose.slides/documentproperties/shared_doc/) | Ermittelt, ob die Präsentation zwischen mehreren Personen geteilt wird.<br/>            Lesen/Schreiben **bool**. |
| [`application_template`](/slides/python-net/de/aspose.slides/documentproperties/application_template/) | Gibt die Vorlage einer Anwendung zurück oder legt sie fest.<br/>            Lesen/Schreiben **str**. |
| [`total_editing_time`](/slides/python-net/de/aspose.slides/documentproperties/total_editing_time/) | Gesamte Bearbeitungszeit einer Präsentation.<br/>            Lesen/Schreiben **System.TimeSpan**. |
| [`title`](/slides/python-net/de/aspose.slides/documentproperties/title/) | Gibt den Titel einer Präsentation zurück oder legt ihn fest.<br/>            Lesen/Schreiben **str**. |
| [`subject`](/slides/python-net/de/aspose.slides/documentproperties/subject/) | Gibt den Betreff einer Präsentation zurück oder legt ihn fest.<br/>            Lesen/Schreiben **str**. |
| [`author`](/slides/python-net/de/aspose.slides/documentproperties/author/) | Gibt den Autor einer Präsentation zurück oder legt ihn fest.<br/>            Lesen/Schreiben **str**. |
| [`keywords`](/slides/python-net/de/aspose.slides/documentproperties/keywords/) | Gibt die Schlüsselwörter einer Präsentation zurück oder legt sie fest.<br/>            Lesen/Schreiben **str**. |
| [`comments`](/slides/python-net/de/aspose.slides/documentproperties/comments/) | Gibt die Kommentare einer Präsentation zurück oder legt sie fest.<br/>            Lesen/Schreiben **str**. |
| [`category`](/slides/python-net/de/aspose.slides/documentproperties/category/) | Gibt die Kategorie einer Präsentation zurück oder legt sie fest.<br/>            Lesen/Schreiben **str**. |
| [`created_time`](/slides/python-net/de/aspose.slides/documentproperties/created_time/) | Gibt das Erstellungsdatum einer Präsentation zurück.<br/>            Werte sind in UTC.<br/>            Lesen/Schreiben **System.DateTime**. |
| [`last_saved_time`](/slides/python-net/de/aspose.slides/documentproperties/last_saved_time/) | Gibt das Datum zurück, an dem eine Präsentation zuletzt geändert wurde.<br/>            Werte sind in UTC.<br/>            Nur lesend im Fall von Presentation.DocumentProperties (da es intern während des Speicherprozesses des IPresentation-Objekts aktualisiert wird). <br/>            Kann über die von Methode [`IPresentationInfo.read_document_properties`](/slides/python-net/de/aspose.slides/ipresentationinfo/read_document_properties) zurückgegebene DocumentProperties-Instanz geändert werden.<br/>            Siehe das Beispiel in der Methodenzusammenfassung von **Aspose.Slides.IPresentationInfo.UpdateDocumentProperties(Aspose.Slide**. |
| [`last_printed`](/slides/python-net/de/aspose.slides/documentproperties/last_printed/) | Gibt das Datum zurück, an dem eine Präsentation zuletzt gedruckt wurde.<br/>            Lesen/Schreiben **System.DateTime**. |
| [`last_saved_by`](/slides/python-net/de/aspose.slides/documentproperties/last_saved_by/) | Gibt den Namen der zuletzt die Präsentation bearbeitenden Person zurück oder legt ihn fest.<br/>            Lesen/Schreiben **str**. |
| [`revision_number`](/slides/python-net/de/aspose.slides/documentproperties/revision_number/) | Gibt die Revisionsnummer der Präsentation zurück oder legt sie fest.<br/>            Lesen/Schreiben **int**. |
| [`content_status`](/slides/python-net/de/aspose.slides/documentproperties/content_status/) | Gibt den Inhaltsstatus einer Präsentation zurück oder legt ihn fest.<br/>            Lesen/Schreiben **str**. |
| [`content_type`](/slides/python-net/de/aspose.slides/documentproperties/content_type/) | Gibt den Inhaltstyp einer Präsentation zurück oder legt ihn fest.<br/>            Lesen/Schreiben **str**. |
| [`hyperlink_base`](/slides/python-net/de/aspose.slides/documentproperties/hyperlink_base/) | Gibt die Dokument-Eigenschaft HyperlinkBase zurück oder legt sie fest.<br/>            Lesen/Schreiben **str**. |
| [`count_of_custom_properties`](/slides/python-net/de/aspose.slides/documentproperties/count_of_custom_properties/) | Gibt die Anzahl der tatsächlich in einer Sammlung enthaltenen benutzerdefinierten Eigenschaften zurück.<br/>            Nur lesend **int**. |
| [`scale_crop`](/slides/python-net/de/aspose.slides/documentproperties/scale_crop/) | Gibt den Anzeigemodus der Dokument-Vorschaubildes an.<br/>            Setzen Sie dieses Element auf **true**, um die Skalierung des Dokument-Vorschaubildes an die Anzeige zu aktivieren.<br/>            Setzen Sie dieses Element auf **false**, um das Zuschneiden des Dokument-Vorschaubildes zu aktivieren, sodass nur Abschnitte angezeigt werden, die zur Anzeige passen.<br/>            Lesen/Schreiben **bool**. |
| [`links_up_to_date`](/slides/python-net/de/aspose.slides/documentproperties/links_up_to_date/) | Gibt an, ob Hyperlinks in einem Dokument aktuell sind.<br/>            Setzen Sie dieses Element auf **true**, um anzuzeigen, dass Hyperlinks aktualisiert sind.<br/>            Setzen Sie dieses Element auf **false**, um anzuzeigen, dass Hyperlinks veraltet sind.<br/>            Lesen/Schreiben **bool**. |
| [`hyperlinks_changed`](/slides/python-net/de/aspose.slides/documentproperties/hyperlinks_changed/) | Gibt an, dass ein oder mehrere Hyperlinks in diesem Teil ausschließlich von einem Ersteller in diesem Teil aktualisiert wurden.<br/>            Der nächste Ersteller, der dieses Dokument öffnet, soll die Hyperlink-Beziehungen mit den in diesem Teil angegebenen neuen Hyperlinks aktualisieren.<br/>            Lesen/Schreiben **bool**. |
| [`slides`](/slides/python-net/de/aspose.slides/documentproperties/slides/) | Gibt die Gesamtzahl der Folien in einem Präsentationsdokument zurück.<br/de/>            Nur lesend **int**. |
| [`hidden_slides`](/slides/python-net/de/aspose.slides/documentproperties/hidden_slides/) | Gibt die Anzahl versteckter Folien in einem Präsentationsdokument zurück.<br/>            Nur lesend **int**. |
| [`notes`](/slides/python-net/de/aspose.slides/documentproperties/notes/) | Gibt die Anzahl der Folien in einer Präsentation zurück, die Notizen enthalten.<br/>            Nur lesend **int**. |
| [`paragraphs`](/slides/python-net/de/aspose.slides/documentproperties/paragraphs/) | Gibt die Gesamtzahl der im Dokument gefundenen Absätze zurück, falls zutreffend.<br/>            Nur lesend **int**. |
| [`words`](/slides/python-net/de/aspose.slides/documentproperties/words/) | Gibt die Gesamtzahl der im Dokument enthaltenen Wörter zurück.<br/>            Nur lesend **int**. |
| [`multimedia_clips`](/slides/python-net/de/aspose.slides/documentproperties/multimedia_clips/) | Gibt die Gesamtzahl der im Dokument vorhandenen Ton- oder Videoclips zurück.<br/>            Nur lesend **int**. |
| [`titles_of_parts`](/slides/python-net/de/aspose.slides/documentproperties/titles_of_parts/) | Gibt den Titel jedes Dokumententeils an.<br/>            Diese Teile sind keine Dokumententeile, sondern konzeptuelle Darstellungen von Dokumentabschnitten.<br/>            Nur lesend **List[str]**. |
| [`heading_pairs`](/slides/python-net/de/aspose.slides/documentproperties/heading_pairs/) | Gibt die Gruppierung von Dokumententeilen und die Anzahl der Teile in jeder Gruppe an.<br/>            Nur lesend **List[IHeadingPair]**. |

## Methoden

| Methode | Beschreibung |
| :- | :- |
| [`get_custom_property_value(self, name, value)`](/slides/python-net/de/aspose.slides/documentproperties/get_custom_property_value/#str-any) | Ruft einen benannten booleschen Wert aus den benutzerdefinierten Eigenschaften ab. |
| [`get_custom_property_value(self, name, value)`](/slides/python-net/de/aspose.slides/documentproperties/get_custom_property_value/#str-any) | Ruft einen benannten ganzzahligen Wert aus den benutzerdefinierten Eigenschaften ab. |
| [`get_custom_property_value(self, name, value)`](/slides/python-net/de/aspose.slides/documentproperties/get_custom_property_value/#str-any) | Ruft einen benannten DateTime-Wert aus den benutzerdefinierten Eigenschaften ab. |
| [`get_custom_property_value(self, name, value)`](/slides/python-net/de/aspose.slides/documentproperties/get_custom_property_value/#str-any) | Ruft einen benannten Zeichenkettenwert aus den benutzerdefinierten Eigenschaften ab. |
| [`get_custom_property_value(self, name, value)`](/slides/python-net/de/aspose.slides/documentproperties/get_custom_property_value/#str-any) |  |
| [`get_custom_property_value(self, name, value)`](/slides/python-net/de/aspose.slides/documentproperties/get_custom_property_value/#str-any) |  |
| [`set_custom_property_value(self, name, value)`](/slides/python-net/de/aspose.slides/documentproperties/set_custom_property_value/#str-bool) | Setzt eine benannte boolesche benutzerdefinierte Eigenschaft. |
| [`set_custom_property_value(self, name, value)`](/slides/python-net/de/aspose.slides/documentproperties/set_custom_property_value/#str-int) | Setzt eine benannte ganzzahlige benutzerdefinierte Eigenschaft. |
| [`set_custom_property_value(self, name, value)`](/slides/python-net/de/aspose.slides/documentproperties/set_custom_property_value/#str-datetime) | Setzt eine benannte DateTime-benutzerdefinierte Eigenschaft. |
| [`set_custom_property_value(self, name, value)`](/slides/python-net/de/aspose.slides/documentproperties/set_custom_property_value/#str-str) | Setzt eine benannte Zeichenketten-benutzerdefinierte Eigenschaft. |
| [`set_custom_property_value(self, name, value)`](/slides/python-net/de/aspose.slides/documentproperties/set_custom_property_value/#str-float) | Setzt eine benannte Float-benutzerdefinierte Eigenschaft. |
| [`set_custom_property_value(self, name, value)`](/slides/python-net/de/aspose.slides/documentproperties/set_custom_property_value/#str-float) | Setzt eine benannte Double-benutzerdefinierte Eigenschaft. |
| [`get_custom_property_name(self, index)`](/slides/python-net/de/aspose.slides/documentproperties/get_custom_property_name/#int) | Gibt einen benutzerdefinierten Eigenschaftsnamen am angegebenen Index zurück. |
| [`remove_custom_property(self, name)`](/slides/python-net/de/aspose.slides/documentproperties/remove_custom_property/#str) | Entfernt eine benutzerdefinierte Eigenschaft, die mit einem angegebenen Namen verknüpft ist. |
| [`contains_custom_property(self, name)`](/slides/python-net/de/aspose.slides/documentproperties/contains_custom_property/#str) | Prüft das Vorhandensein einer benutzerdefinierten Eigenschaft mit einem angegebenen Namen. |
| [`clear_custom_properties(self)`](/slides/python-net/de/aspose.slides/documentproperties/clear_custom_properties/#) | Entfernt alle benutzerdefinierten Eigenschaften. |
| [`get_sensitivity_labels(self)`](/slides/python-net/de/aspose.slides/documentproperties/get_sensitivity_labels/#) | Ruft ein Array von Sensitivitätskennzeichnungen aus den benutzerdefinierten Dokumenteneigenschaften ab (Microsoft Information Protection SDK Metadata). |
| [`clear_built_in_properties(self)`](/slides/python-net/de/aspose.slides/documentproperties/clear_built_in_properties/#) | Löscht und setzt Standardwerte für alle integrierten Eigenschaften. |
| [`clone(self)`](/slides/python-net/de/aspose.slides/documentproperties/clone/#) | Klont das aktuelle Objekt |
| [`clone_t(self)`](/slides/python-net/de/aspose.slides/documentproperties/clone_t/#) | Klont das aktuelle Objekt |

### Siehe auch
* Klasse [`DocumentProperties`](/slides/python-net/de/aspose.slides/documentproperties)
* Modul [`aspose.slides`](/slides/python-net/de/aspose.slides)
* Bibliothek [`Aspose.Slides`](/slides/python-net)