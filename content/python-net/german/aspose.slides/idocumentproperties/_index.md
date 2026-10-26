---
title: IDocumentProperties class
second_title: Aspose.Slides für Python über .NET API-Referenz
description: 
type: docs
url: /de/aspose.slides/idocumentproperties/
---
## IDocumentProperties Klasse

Stellt Eigenschaften einer Präsentation dar.

Der Typ IDocumentProperties stellt die folgenden Member bereit:

## Eigenschaften

| Eigenschaft | Beschreibung |
| :- | :- |
| [`app_version`](/slides/python-net/de/aspose.slides/idocumentproperties/app_version/) | Gibt die App-Version zurück.<br/>            Nur lesbar **str**. |
| [`name_of_application`](/slides/python-net/de/aspose.slides/idocumentproperties/name_of_application/) | Gibt den Namen der Anwendung zurück oder legt ihn fest.<br/>            Lesen/Schreiben **str**. |
| [`company`](/slides/python-net/de/aspose.slides/idocumentproperties/company/) | Gibt die Unternehmens-Eigenschaft zurück oder legt sie fest.<br/>            Lesen/Schreiben **str**. |
| [`manager`](/slides/python-net/de/aspose.slides/idocumentproperties/manager/) | Gibt die Manager-Eigenschaft zurück oder legt sie fest.<br/>            Lesen/Schreiben **str**. |
| [`presentation_format`](/slides/python-net/de/aspose.slides/idocumentproperties/presentation_format/) | Gibt das beabsichtigte Format einer Präsentation zurück oder legt es fest.<br/>            Lesen/Schreiben **str**. |
| [`shared_doc`](/slides/python-net/de/aspose.slides/idocumentproperties/shared_doc/) | Bestimmt, ob die Präsentation zwischen mehreren Personen geteilt wird.<br/>            Lesen/Schreiben **bool**. |
| [`application_template`](/slides/python-net/de/aspose.slides/idocumentproperties/application_template/) | Gibt die Vorlage einer Anwendung zurück oder legt sie fest.<br/>            Lesen/Schreiben **str**. |
| [`total_editing_time`](/slides/python-net/de/aspose.slides/idocumentproperties/total_editing_time/) | Gesamte Bearbeitungszeit einer Präsentation.<br/>            Lesen/Schreiben **System.TimeSpan**. |
| [`title`](/slides/python-net/de/aspose.slides/idocumentproperties/title/) | Gibt den Titel einer Präsentation zurück oder legt ihn fest.<br/>            Lesen/Schreiben **str**. |
| [`subject`](/slides/python-net/de/aspose.slides/idocumentproperties/subject/) | Gibt den Betreff einer Präsentation zurück oder legt ihn fest.<br/>            Lesen/Schreiben **str**. |
| [`author`](/slides/python-net/de/aspose.slides/idocumentproperties/author/) | Gibt den Autor einer Präsentation zurück oder legt ihn fest.<br/>            Lesen/Schreiben **str**. |
| [`keywords`](/slides/python-net/de/aspose.slides/idocumentproperties/keywords/) | Gibt die Schlüsselwörter einer Präsentation zurück oder legt sie fest.<br/>            Lesen/Schreiben **str**. |
| [`comments`](/slides/python-net/de/aspose.slides/idocumentproperties/comments/) | Gibt die Kommentare einer Präsentation zurück oder legt sie fest.<br/>            Lesen/Schreiben **str**. |
| [`category`](/slides/python-net/de/aspose.slides/idocumentproperties/category/) | Gibt die Kategorie einer Präsentation zurück oder legt sie fest.<br/>            Lesen/Schreiben **str**. |
| [`created_time`](/slides/python-net/de/aspose.slides/idocumentproperties/created_time/) | Gibt das Datum zurück, an dem eine Präsentation erstellt wurde.<br/>            Werte sind in UTC.<br/>            Lesen/Schreiben **System.DateTime**. |
| [`last_saved_time`](/slides/python-net/de/aspose.slides/idocumentproperties/last_saved_time/) | Gibt das Datum zurück, an dem eine Präsentation zuletzt geändert wurde.<br/>            Werte sind in UTC.<br/>            Nur lesbar im Falle von Presentation.DocumentProperties (weil es intern während des Speichervorgangs des IPresentation-Objekts aktualisiert wird).<br/>            Kann über die DocumentProperties-Instanz geändert werden, die durch die Methode [`IPresentationInfo.read_document_properties`](/slides/python-net/de/aspose.slides/ipresentationinfo/read_document_properties) zurückgegeben wird.<br/>            Siehe das Beispiel in der **Aspose.Slides.IPresentationInfo.UpdateDocumentProperties(Aspose.Slide**-Methodenzusammenfassung. |
| [`last_printed`](/slides/python-net/de/aspose.slides/idocumentproperties/last_printed/) | Gibt das Datum zurück, an dem eine Präsentation zuletzt gedruckt wurde.<br/>            Lesen/Schreiben **System.DateTime**. |
| [`last_saved_by`](/slides/python-net/de/aspose.slides/idocumentproperties/last_saved_by/) | Gibt den Namen der letzten Person zurück, die eine Präsentation geändert hat, oder legt ihn fest.<br/>            Lesen/Schreiben **str**. |
| [`revision_number`](/slides/python-net/de/aspose.slides/idocumentproperties/revision_number/) | Gibt die Versionsnummer der Präsentation zurück oder legt sie fest.<br/>            Lesen/Schreiben **int**. |
| [`content_status`](/slides/python-net/de/aspose.slides/idocumentproperties/content_status/) | Gibt den Inhaltsstatus einer Präsentation zurück oder legt ihn fest.<br/>            Lesen/Schreiben **str**. |
| [`content_type`](/slides/python-net/de/aspose.slides/idocumentproperties/content_type/) | Gibt den Inhaltstyp einer Präsentation zurück oder legt ihn fest.<br/>            Lesen/Schreiben **str**. |
| [`hyperlink_base`](/slides/python-net/de/aspose.slides/idocumentproperties/hyperlink_base/) | Gibt die HyperlinkBase-Dokumenteneigenschaft zurück oder legt sie fest.<br/>            Lesen/Schreiben **str**. |
| [`scale_crop`](/slides/python-net/de/aspose.slides/idocumentproperties/scale_crop/) | Gibt den Anzeigemodus der Dokument-Miniatur an.<br/>            Setzen Sie dieses Element auf **true**, um das Skalieren der Dokument-Miniatur an die Anzeige zu aktivieren.<br/>            Setzen Sie dieses Element auf **false**, um das Beschneiden der Dokument-Miniatur zu aktivieren, sodass nur Abschnitte angezeigt werden, die in die Anzeige passen.<br/>            Lesen/Schreiben **bool**. |
| [`links_up_to_date`](/slides/python-net/de/aspose.slides/idocumentproperties/links_up_to_date/) | Gibt an, ob Hyperlinks in einem Dokument aktuell sind.<br/>            Setzen Sie dieses Element auf **true**, um anzuzeigen, dass Hyperlinks aktualisiert wurden.<br/>            Setzen Sie dieses Element auf **false**, um anzuzeigen, dass Hyperlinks veraltet sind.<br/>            Lesen/Schreiben **bool**. |
| [`hyperlinks_changed`](/slides/python-net/de/aspose.slides/idocumentproperties/hyperlinks_changed/) | Gibt an, dass ein oder mehrere Hyperlinks in diesem Teil ausschließlich von einem Produzenten in diesem Teil aktualisiert wurden.<br/>            Der nächste Produzent, der dieses Dokument öffnet, soll die Hyperlink-Beziehungen mit den in diesem Teil angegebenen neuen Hyperlinks aktualisieren.<br/>            Lesen/Schreiben **bool**. |
| [`slides`](/slides/python-net/de/aspose.slides/idocumentproperties/slides/) | Gibt die Gesamtanzahl der Folien in einem Präsentationsdokument an.<br/de/>            Nur lesbar **int**. |
| [`hidden_slides`](/slides/python-net/de/aspose.slides/idocumentproperties/hidden_slides/) | Gibt die Anzahl der ausgeblendeten Folien in einem Präsentationsdokument an.<br/>            Nur lesbar **int**. |
| [`notes`](/slides/python-net/de/aspose.slides/idocumentproperties/notes/) | Gibt die Anzahl der Folien in einer Präsentation mit Notizen an.<br/>            Nur lesbar **int**. |
| [`paragraphs`](/slides/python-net/de/aspose.slides/idocumentproperties/paragraphs/) | Gibt die Gesamtanzahl der Absätze im Dokument an, falls zutreffend.<br/>            Nur lesbar **int**. |
| [`words`](/slides/python-net/de/aspose.slides/idocumentproperties/words/) | Gibt die Gesamtanzahl der Wörter im Dokument an.<br/>            Nur lesbar **int**. |
| [`multimedia_clips`](/slides/python-net/de/aspose.slides/idocumentproperties/multimedia_clips/) | Gibt die Gesamtanzahl der Ton- oder Videoclips im Dokument an.<br/>            Nur lesbar **int**. |
| [`titles_of_parts`](/slides/python-net/de/aspose.slides/idocumentproperties/titles_of_parts/) | Gibt den Titel jedes Dokumentteils an.<br/>            Diese Teile sind keine Dokumentteile, sondern konzeptionelle Darstellungen von Dokumentabschnitten.<br/>            Nur lesbar **List[str]**. |
| [`heading_pairs`](/slides/python-net/de/aspose.slides/idocumentproperties/heading_pairs/) | Gibt die Gruppierung von Dokumentteilen und die Anzahl der Teile in jeder Gruppe an.<br/>            Nur lesbar **List[IHeadingPair]**. |
| [`count_of_custom_properties`](/slides/python-net/de/aspose.slides/idocumentproperties/count_of_custom_properties/) | Gibt die Anzahl der tatsächlich in einer Sammlung enthaltenen benutzerdefinierten Eigenschaften zurück.<br/>            Nur lesbar **int**. |

## Methoden

| Methode | Beschreibung |
| :- | :- |
| [`get_custom_property_value(self, name, value)`](/slides/python-net/de/aspose.slides/idocumentproperties/get_custom_property_value/#str-any) | Ruft einen benannten booleschen Wert aus den benutzerdefinierten Eigenschaften ab. |
| [`get_custom_property_value(self, name, value)`](/slides/python-net/de/aspose.slides/idocumentproperties/get_custom_property_value/#str-any) | Ruft einen benannten Ganzzahlwert aus den benutzerdefinierten Eigenschaften ab. |
| [`get_custom_property_value(self, name, value)`](/slides/python-net/de/aspose.slides/idocumentproperties/get_custom_property_value/#str-any) | Ruft einen benannten DateTime-Wert aus den benutzerdefinierten Eigenschaften ab. |
| [`get_custom_property_value(self, name, value)`](/slides/python-net/de/aspose.slides/idocumentproperties/get_custom_property_value/#str-any) | Ruft einen benannten Zeichenkettenwert aus den benutzerdefinierten Eigenschaften ab. |
| [`get_custom_property_value(self, name, value)`](/slides/python-net/de/aspose.slides/idocumentproperties/get_custom_property_value/#str-any) |  |
| [`get_custom_property_value(self, name, value)`](/slides/python-net/de/aspose.slides/idocumentproperties/get_custom_property_value/#str-any) |  |
| [`set_custom_property_value(self, name, value)`](/slides/python-net/de/aspose.slides/idocumentproperties/set_custom_property_value/#str-bool) | Setzt eine benannte boolesche benutzerdefinierte Eigenschaft. |
| [`set_custom_property_value(self, name, value)`](/slides/python-net/de/aspose.slides/idocumentproperties/set_custom_property_value/#str-int) | Setzt eine benannte ganzzahlige benutzerdefinierte Eigenschaft. |
| [`set_custom_property_value(self, name, value)`](/slides/python-net/de/aspose.slides/idocumentproperties/set_custom_property_value/#str-datetime) | Setzt eine benannte DateTime-benutzerdefinierte Eigenschaft. |
| [`set_custom_property_value(self, name, value)`](/slides/python-net/de/aspose.slides/idocumentproperties/set_custom_property_value/#str-str) | Setzt eine benannte Zeichenketten-benutzerdefinierte Eigenschaft. |
| [`set_custom_property_value(self, name, value)`](/slides/python-net/de/aspose.slides/idocumentproperties/set_custom_property_value/#str-float) | Setzt eine benannte Float-benutzerdefinierte Eigenschaft. |
| [`set_custom_property_value(self, name, value)`](/slides/python-net/de/aspose.slides/idocumentproperties/set_custom_property_value/#str-float) | Setzt eine benannte Double-benutzerdefinierte Eigenschaft. |
| [`get_custom_property_name(self, index)`](/slides/python-net/de/aspose.slides/idocumentproperties/get_custom_property_name/#int) | Gibt einen benutzerdefinierten Eigenschaftsnamen am angegebenen Index zurück. |
| [`remove_custom_property(self, name)`](/slides/python-net/de/aspose.slides/idocumentproperties/remove_custom_property/#str) | Entfernt eine benutzerdefinierte Eigenschaft, die mit einem angegebenen Namen verknüpft ist. |
| [`contains_custom_property(self, name)`](/slides/python-net/de/aspose.slides/idocumentproperties/contains_custom_property/#str) | Prüft das Vorhandensein einer benutzerdefinierten Eigenschaft mit einem angegebenen Namen. |
| [`clear_custom_properties(self)`](/slides/python-net/de/aspose.slides/idocumentproperties/clear_custom_properties/#) | Entfernt alle benutzerdefinierten Eigenschaften. |
| [`clear_built_in_properties(self)`](/slides/python-net/de/aspose.slides/idocumentproperties/clear_built_in_properties/#) | Löscht und setzt Standardwerte für alle integrierten Eigenschaften. |
| [`get_sensitivity_labels(self)`](/slides/python-net/de/aspose.slides/idocumentproperties/get_sensitivity_labels/#) | Gibt ein Array von Sensitivitäts-Labels aus den benutzerdefinierten Dokumenteigenschaften zurück (Microsoft Information Protection SDK-Metadaten). |

### Siehe auch
* Modul [`aspose.slides`](/slides/python-net/de/aspose.slides)
* Bibliothek [`Aspose.Slides`](/slides/python-net)