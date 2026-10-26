---
title: IPresentation class
second_title: Aspose.Slides für Python über .NET API-Referenz
description: 
type: docs
url: /de/aspose.slides/ipresentation/
---
## IPresentation class

Präsentationsdokument

Der IPresentation-Typ stellt die folgenden Mitglieder bereit:

## Eigenschaften

| Property | Description |
| :- | :- |
| [`current_date_time`](/slides/python-net/de/aspose.slides/ipresentation/current_date_time/) | Gibt Datum und Uhrzeit zurück oder setzt sie, die den Inhalt von datetime-Feldern ersetzen.<br/>            Standardmäßig die Erstellungszeit dieses Presentation-Objekts.<br/>            Lese/Schreiben **System.DateTime**. |
| [`header_footer_manager`](/slides/python-net/de/aspose.slides/ipresentation/header_footer_manager/) | Gibt den HeaderFooter-Manager der Präsentation zurück.<br/>            Nur-Lesen [`IPresentationHeaderFooterManager`](/slides/python-net/de/aspose.slides/ipresentationheaderfootermanager). |
| [`protection_manager`](/slides/python-net/de/aspose.slides/ipresentation/protection_manager/) | Gibt den Manager der Berechtigungen für diese Präsentation zurück.<br/>            Nur-Lesen [`IProtectionManager`](/slides/python-net/de/aspose.slides/iprotectionmanager). |
| [`slides`](/slides/python-net/de/aspose.slides/ipresentation/slides/) | Gibt eine Liste aller Folien zurück, die in der Präsentation definiert sind.<br/de/>            Nur-Lesen [`ISlideCollection`](/slides/python-net/de/aspose.slides/islidecollection). |
| [`sections`](/slides/python-net/de/aspose.slides/ipresentation/sections/) | Gibt eine Liste aller Folienabschnitte zurück, die in der Präsentation definiert sind.<br/>            Nur-Lesen [`ISectionCollection`](/slides/python-net/de/aspose.slides/isectioncollection). |
| [`slide_size`](/slides/python-net/de/aspose.slides/ipresentation/slide_size/) | Gibt das Foliengrößen-Objekt zurück.<br/>            Nur-Lesen [`ISlideSize`](/slides/python-net/de/aspose.slides/islidesize). |
| [`notes_size`](/slides/python-net/de/aspose.slides/ipresentation/notes_size/) | Gibt das Notizfoliengrößen-Objekt zurück.<br/>            Nur-Lesen [`INotesSize`](/slides/python-net/de/aspose.slides/inotessize). |
| [`layout_slides`](/slides/python-net/de/aspose.slides/ipresentation/layout_slides/) | Gibt eine Liste aller Layout-Folien zurück, die in der Präsentation definiert sind.<br/>            Nur-Lesen [`IGlobalLayoutSlideCollection`](/slides/python-net/de/aspose.slides/igloballayoutslidecollection). |
| [`masters`](/slides/python-net/de/aspose.slides/ipresentation/masters/) | Gibt eine Liste aller Master-Folien zurück, die in der Präsentation definiert sind.<br/>            Nur-Lesen [`IMasterSlideCollection`](/slides/python-net/de/aspose.slides/imasterslidecollection). |
| [`master_notes_slide_manager`](/slides/python-net/de/aspose.slides/ipresentation/master_notes_slide_manager/) | Gibt den Notiz-Master-Manager zurück.<br/>            Nur-Lesen [`IMasterNotesSlideManager`](/slides/python-net/de/aspose.slides/imasternotesslidemanager). |
| [`master_handout_slide_manager`](/slides/python-net/de/aspose.slides/ipresentation/master_handout_slide_manager/) | Gibt den Handzettel-Master-Manager zurück.<br/>            Nur-Lesen [`IMasterHandoutSlideManager`](/slides/python-net/de/aspose.slides/imasterhandoutslidemanager). |
| [`fonts_manager`](/slides/python-net/de/aspose.slides/ipresentation/fonts_manager/) | Gibt den Schriftarten-Manager zurück.<br/>            Nur-Lesen [`IFontsManager`](/slides/python-net/de/aspose.slides/ifontsmanager). |
| [`default_text_style`](/slides/python-net/de/aspose.slides/ipresentation/default_text_style/) | Gibt den Standard-Textstil für Formen zurück.<br/>            Nur-Lesen [`ITextStyle`](/slides/python-net/de/aspose.slides/itextstyle). |
| [`comment_authors`](/slides/python-net/de/aspose.slides/ipresentation/comment_authors/) | Gibt die Sammlung der Kommentar-Autoren zurück.<br/>            Nur-Lesen [`ICommentAuthorCollection`](/slides/python-net/de/aspose.slides/icommentauthorcollection). |
| [`document_properties`](/slides/python-net/de/aspose.slides/ipresentation/document_properties/) | Gibt das DocumentProperties-Objekt zurück, das Standard- und benutzerdefinierte Dokument-Eigenschaften enthält.<br/>            Nur-Lesen [`IDocumentProperties`](/slides/python-net/de/aspose.slides/idocumentproperties). |
| [`images`](/slides/python-net/de/aspose.slides/ipresentation/images/) | Gibt die Sammlung aller Bilder in der Präsentation zurück.<br/>            Nur-Lesen [`IImageCollection`](/slides/python-net/de/aspose.slides/iimagecollection). |
| [`audios`](/slides/python-net/de/aspose.slides/ipresentation/audios/) | Gibt die Sammlung aller eingebetteten Audiodateien in der Präsentation zurück.<br/>            Nur-Lesen [`IAudioCollection`](/slides/python-net/de/aspose.slides/iaudiocollection). |
| [`videos`](/slides/python-net/de/aspose.slides/ipresentation/videos/) | Gibt die Sammlung aller eingebetteten Videodateien in der Präsentation zurück.<br/>            Nur-Lesen [`IVideoCollection`](/slides/python-net/de/aspose.slides/ivideocollection). |
| [`custom_data`](/slides/python-net/de/aspose.slides/ipresentation/custom_data/) | Gibt die benutzerdefinierten Daten der Präsentation zurück.<br/>            Nur-Lesen [`ICustomData`](/slides/python-net/de/aspose.slides/icustomdata). |
| [`vba_project`](/slides/python-net/de/aspose.slides/ipresentation/vba_project/) | Gibt das VBA-Projekt mit Präsentations-Makros zurück.<br/>            Lese/Schreiben [`IVbaProject`](/slides/python-net/de/aspose.slides.vba/ivbaproject). |
| [`source_format`](/slides/python-net/de/aspose.slides/ipresentation/source_format/) | Gibt Informationen darüber zurück, aus welchem Format die Präsentation geladen wurde.<br/>            Nur-Lesen [`IPresentation.source_format`](/slides/python-net/de/aspose.slides/ipresentation/source_format). |
| [`master_theme`](/slides/python-net/de/aspose.slides/ipresentation/master_theme/) | Gibt das Master-Theme der Präsentation zurück.<br/>            Nur-Lesen [`IMasterTheme`](/slides/python-net/de/aspose.slides.theme/imastertheme). |
| [`hyperlink_queries`](/slides/python-net/de/aspose.slides/ipresentation/hyperlink_queries/) | Stellt einfachen Zugriff auf alle Hyperlinks bereit, die in allen Präsentations-Folien enthalten sind (nicht in Master-, Layout- oder Notiz-Folien).<br/>            Nur-Lesen [`IHyperlinkQueries`](/slides/python-net/de/aspose.slides/ihyperlinkqueries). |
| [`view_properties`](/slides/python-net/de/aspose.slides/ipresentation/view_properties/) | Gibt die präsentationsweiten Ansichtseigenschaften zurück.<br/>            Nur-Lesen [`IViewProperties`](/slides/python-net/de/aspose.slides/iviewproperties). |
| [`first_slide_number`](/slides/python-net/de/aspose.slides/ipresentation/first_slide_number/) | Stellt die Nummer der ersten Folie in der Präsentation dar.<br/>            Lese/Schreiben **int**. |
| [`all_custom_xml_parts`](/slides/python-net/de/aspose.slides/ipresentation/all_custom_xml_parts/) | Gibt alle benutzerdefinierten Daten-Teile in der Präsentation zurück.<br/>            Nur-Lesen [`ICustomXmlPart`](/slides/python-net/de/aspose.slides/icustomxmlpart)[]. |
| [`digital_signatures`](/slides/python-net/de/aspose.slides/ipresentation/digital_signatures/) | Gibt die Sammlung von Signaturen zurück, die zum Signieren der Präsentation verwendet werden.<br/>            Nur-Lesen [`IDigitalSignatureCollection`](/slides/python-net/de/aspose.slides/idigitalsignaturecollection). |
| [`sensitivity_labels`](/slides/python-net/de/aspose.slides/ipresentation/sensitivity_labels/) | Gibt die Sammlung von Sensitivitäts-Labels zurück, die auf das Präsentations-Dokument angewendet wurden.<br/>            Nur-Lesen [`ISensitivityLabelCollection`](/slides/python-net/de/aspose.slides/isensitivitylabelcollection). |
| [`presentation`](/slides/python-net/de/aspose.slides/ipresentation/presentation/) |  |

## Methoden

| Method | Description |
| :- | :- |
| [`save(self, fname, format)`](/slides/python-net/de/aspose.slides/ipresentation/save/#str-asposeslidesexportsaveformat) | Speichert alle Folien einer Präsentation in einer Datei mit dem angegebenen Format. |
| [`save(self, stream, format)`](/slides/python-net/de/aspose.slides/ipresentation/save/#iorawiobase-asposeslidesexportsaveformat) | Speichert alle Folien einer Präsentation in einen Stream im angegebenen Format. |
| [`save(self, fname, format, options)`](/slides/python-net/de/aspose.slides/ipresentation/save/#str-asposeslidesexportsaveformat-asposeslidesexportisaveoptions) | Speichert alle Folien einer Präsentation in einer Datei mit dem angegebenen Format und mit zusätzlichen Optionen. |
| [`save(self, stream, format, options)`](/slides/python-net/de/aspose.slides/ipresentation/save/#iorawiobase-asposeslidesexportsaveformat-asposeslidesexportisaveoptions) | Speichert alle Folien einer Präsentation in einen Stream im angegebenen Format und mit zusätzlichen Optionen. |
| [`save(self, fname, slides, format)`](/slides/python-net/de/aspose.slides/ipresentation/save/#str-listint-asposeslidesexportsaveformat) | Speichert die angegebenen Folien einer Präsentation in einer Datei mit dem angegebenen Format. |
| [`save(self, fname, slides, format, options)`](/slides/python-net/de/aspose.slides/ipresentation/save/#str-listint-asposeslidesexportsaveformat-asposeslidesexportisaveoptions) | Speichert die angegebenen Folien einer Präsentation in einer Datei mit dem angegebenen Format. |
| [`save(self, stream, slides, format)`](/slides/python-net/de/aspose.slides/ipresentation/save/#iorawiobase-listint-asposeslidesexportsaveformat) | Speichert die angegebenen Folien einer Präsentation in einen Stream im angegebenen Format. |
| [`save(self, stream, slides, format, options)`](/slides/python-net/de/aspose.slides/ipresentation/save/#iorawiobase-listint-asposeslidesexportsaveformat-asposeslidesexportisaveoptions) | Speichert die angegebenen Folien einer Präsentation in einen Stream im angegebenen Format. |
| [`save(self, options)`](/slides/python-net/de/aspose.slides/ipresentation/save/#asposeslidesexportxamlixamloptions) | Speichert alle Folien einer Präsentation in einer Menge von Dateien, die XAML-Markup darstellen. |
| [`get_images(self, options)`](/slides/python-net/de/aspose.slides/ipresentation/get_images/#asposeslidesexportirenderingoptions) | Gibt Thumbnail-Bildobjekte für alle Folien einer Präsentation zurück. |
| [`get_images(self, options, slides)`](/slides/python-net/de/aspose.slides/ipresentation/get_images/#asposeslidesexportirenderingoptions-listint) | Gibt Thumbnail-Bitmap-Objekte für die angegebenen Folien einer Präsentation zurück. |
| [`get_images(self, options, scale_x, scale_y)`](/slides/python-net/de/aspose.slides/ipresentation/get_images/#asposeslidesexportirenderingoptions-float-float) | Gibt Thumbnail-Bildobjekte für alle Folien einer Präsentation mit benutzerdefiniertem Skalieren zurück. |
| [`get_images(self, options, slides, scale_x, scale_y)`](/slides/python-net/de/aspose.slides/ipresentation/get_images/#asposeslidesexportirenderingoptions-listint-float-float) | Gibt Thumbnail-Bildobjekte für die angegebenen Folien einer Präsentation mit benutzerdefiniertem Skalieren zurück. |
| [`get_images(self, options, image_size)`](/slides/python-net/de/aspose.slides/ipresentation/get_images/#asposeslidesexportirenderingoptions-asposeslidessize) | Gibt Thumbnail-Bildobjekte für alle Folien einer Präsentation mit angegebener Größe zurück. |
| [`get_images(self, options, slides, image_size)`](/slides/python-net/de/aspose.slides/ipresentation/get_images/#asposeslidesexportirenderingoptions-listint-asposeslidessize) | Gibt Thumbnail-Bildobjekte für die angegebenen Folien einer Präsentation mit angegebener Größe zurück. |
| [`highlight_text(self, text, highlight_color)`](/slides/python-net/de/aspose.slides/ipresentation/highlight_text/#str-asposeslidescolor) | Hebt alle Übereinstimmungen des Beispieltexts mit der angegebenen Farbe hervor. |
| [`highlight_text(self, text, highlight_color, options, callback)`](/slides/python-net/de/aspose.slides/ipresentation/highlight_text/#str-asposeslidescolor-itextsearchoptions-ifindresultcallback) | Hebt alle Übereinstimmungen des Beispieltexts mit der angegebenen Farbe hervor. |
| [`get_slide_by_id(self, id)`](/slides/python-net/de/aspose.slides/ipresentation/get_slide_by_id/#int) | Gibt eine Folie, MasterFolien- oder LayoutFolien-Instanz anhand der Id zurück. |
| [`join_portions_with_same_formatting(self)`](/slides/python-net/de/aspose.slides/ipresentation/join_portions_with_same_formatting/#) | Fügt Lauf-Abschnitte mit gleicher Formatierung in allen Absätzen in allen zulässigen Formen in allen Folien zusammen. |
| [`highlight_regex(self, regex, highlight_color)`](/slides/python-net/de/aspose.slides/ipresentation/highlight_regex/#str-asposeslidescolor) | Hebt alle Übereinstimmungen des regulären Ausdrucks mit der angegebenen Farbe hervor. |
| [`replace_text(self, old_text, new_text, options, callback)`](/slides/python-net/de/aspose.slides/ipresentation/replace_text/#str-str-itextsearchoptions-ifindresultcallback) | Ersetzt alle Vorkommen des angegebenen Textes durch einen anderen angegebenen Text. |
| [`replace_regex(self, regex, new_text)`](/slides/python-net/de/aspose.slides/ipresentation/replace_regex/#str-str) | Ersetzt alle Übereinstimmungen des regulären Ausdrucks durch die angegebene Zeichenkette. |


### Siehe auch
* Modul [`aspose.slides`](/slides/python-net/de/aspose.slides)
* Bibliothek [`Aspose.Slides`](/slides/python-net)