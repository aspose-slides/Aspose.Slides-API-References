---
title: Presentation class
second_title: Aspose.Slides für Python über .NET API-Referenz
description: 
type: docs
url: /de/aspose.slides/presentation/
---
## Presentation-Klasse

Stellt eine Microsoft PowerPoint-Präsentation dar.

Der Presentation-Typ stellt die folgenden Mitglieder bereit:

## Konstruktoren

| Konstruktor | Beschreibung |
| :- | :- |
| [`__init__(self)`](/slides/python-net/de/aspose.slides/presentation/__init__/#) | Dieser Konstruktor erstellt eine neue Präsentation von Grund auf.<br/>            Die erstellte Präsentation enthält eine leere Folie. |
| [`__init__(self, load_options)`](/slides/python-net/de/aspose.slides/presentation/__init__/#loadoptions) | Dieser Konstruktor erstellt eine neue Präsentation von Grund auf.<br/>            Die erstellte Präsentation enthält eine leere Folie. |
| [`__init__(self, stream)`](/slides/python-net/de/aspose.slides/presentation/__init__/#iorawiobase) | Dieser Konstruktor ist der primäre Mechanismus zum Lesen einer vorhandenen Presentation. |
| [`__init__(self, stream, load_options)`](/slides/python-net/de/aspose.slides/presentation/__init__/#iorawiobase-loadoptions) | Dieser Konstruktor ist der primäre Mechanismus zum Lesen einer vorhandenen Presentation. |
| [`__init__(self, file)`](/slides/python-net/de/aspose.slides/presentation/__init__/#str) | Dieser Konstruktor erhält einen Quelldateipfad, von dem<br/>             der Inhalt der Presentation gelesen wird. |
| [`__init__(self, file, load_options)`](/slides/python-net/de/aspose.slides/presentation/__init__/#str-loadoptions) | Dieser Konstruktor erhält einen Quelldateipfad, von dem<br/>            der Inhalt der Presentation gelesen wird. |

## Eigenschaften

| Eigenschaft | Beschreibung |
| :- | :- |
| [`current_date_time`](/slides/python-net/de/aspose.slides/presentation/current_date_time/) | Gibt Datum und Uhrzeit zurück oder setzt sie, die den Inhalt von Datums-Uhrzeit-Feldern ersetzen.<br/>            Standardmäßig die Erstellungszeit dieses Presentation-Objekts.<br/>            Lese/Schreib **System.DateTime**. |
| [`header_footer_manager`](/slides/python-net/de/aspose.slides/presentation/header_footer_manager/) | Gibt den aktuellen HeaderFooter-Manager zurück.<br/>            Nur lesbar [`IPresentationHeaderFooterManager`](/slides/python-net/de/aspose.slides/ipresentationheaderfootermanager). |
| [`protection_manager`](/slides/python-net/de/aspose.slides/presentation/protection_manager/) | Ermittelt den Manager der Berechtigungen für diese Präsentation.<br/>            Nur lesbar [`IProtectionManager`](/slides/python-net/de/aspose.slides/iprotectionmanager). |
| [`slides`](/slides/python-net/de/aspose.slides/presentation/slides/) | Gibt eine Liste aller im Dokument definierten Folien zurück.<br/de/>            Nur lesbar [`ISlideCollection`](/slides/python-net/de/aspose.slides/islidecollection). |
| [`sections`](/slides/python-net/de/aspose.slides/presentation/sections/) | Gibt eine Liste aller im Dokument definierten Folienabschnitte zurück.<br/>            Nur lesbar [`ISectionCollection`](/slides/python-net/de/aspose.slides/isectioncollection). |
| [`slide_size`](/slides/python-net/de/aspose.slides/presentation/slide_size/) | Gibt das Foliengrößen-Objekt zurück.<br/>            Nur lesbar [`ISlideSize`](/slides/python-net/de/aspose.slides/islidesize). |
| [`notes_size`](/slides/python-net/de/aspose.slides/presentation/notes_size/) | Gibt das Notizfolien-Größen-Objekt zurück.<br/>            Nur lesbar [`INotesSize`](/slides/python-net/de/aspose.slides/inotessize). |
| [`layout_slides`](/slides/python-net/de/aspose.slides/presentation/layout_slides/) | Gibt eine Liste aller im Dokument definierten Layout-Folien zurück.<br/>            Nur lesbar [`IGlobalLayoutSlideCollection`](/slides/python-net/de/aspose.slides/igloballayoutslidecollection). |
| [`masters`](/slides/python-net/de/aspose.slides/presentation/masters/) | Gibt eine Liste aller im Dokument definierten Master-Folien zurück.<br/>            Nur lesbar [`IMasterSlideCollection`](/slides/python-net/de/aspose.slides/imasterslidecollection). |
| [`master_notes_slide_manager`](/slides/python-net/de/aspose.slides/presentation/master_notes_slide_manager/) | Gibt den Notizen-Master-Manager zurück.<br/>            Nur lesbar [`IMasterNotesSlideManager`](/slides/python-net/de/aspose.slides/imasternotesslidemanager). |
| [`master_handout_slide_manager`](/slides/python-net/de/aspose.slides/presentation/master_handout_slide_manager/) | Gibt den Handzettel-Master-Manager zurück.<br/>            Nur lesbar [`IMasterHandoutSlideManager`](/slides/python-net/de/aspose.slides/imasterhandoutslidemanager). |
| [`fonts_manager`](/slides/python-net/de/aspose.slides/presentation/fonts_manager/) | Gibt den Schriften-Manager zurück.<br/>            Nur lesbar [`IFontsManager`](/slides/python-net/de/aspose.slides/ifontsmanager). |
| [`default_text_style`](/slides/python-net/de/aspose.slides/presentation/default_text_style/) | Gibt den Standard-Textstil für Formen zurück.<br/>            Nur lesbar [`ITextStyle`](/slides/python-net/de/aspose.slides/itextstyle). |
| [`comment_authors`](/slides/python-net/de/aspose.slides/presentation/comment_authors/) | Gibt die Sammlung der Kommentar-Autoren zurück.<br/>            Nur lesbar [`ICommentAuthorCollection`](/slides/python-net/de/aspose.slides/icommentauthorcollection). |
| [`document_properties`](/slides/python-net/de/aspose.slides/presentation/document_properties/) | Gibt das DocumentProperties-Objekt zurück, das Standard- und benutzerdefinierte Dokumenteneigenschaften enthält.<br/>            Nur lesbar [`IDocumentProperties`](/slides/python-net/de/aspose.slides/idocumentproperties). |
| [`images`](/slides/python-net/de/aspose.slides/presentation/images/) | Gibt die Sammlung aller Bilder in der Präsentation zurück.<br/>            Nur lesbar [`IImageCollection`](/slides/python-net/de/aspose.slides/iimagecollection). |
| [`audios`](/slides/python-net/de/aspose.slides/presentation/audios/) | Gibt die Sammlung aller eingebetteten Audiodateien in der Präsentation zurück.<br/>            Nur lesbar [`IAudioCollection`](/slides/python-net/de/aspose.slides/iaudiocollection). |
| [`videos`](/slides/python-net/de/aspose.slides/presentation/videos/) | Gibt die Sammlung aller eingebetteten Videodateien in der Präsentation zurück.<br/>            Nur lesbar [`IVideoCollection`](/slides/python-net/de/aspose.slides/ivideocollection). |
| [`slide_show_settings`](/slides/python-net/de/aspose.slides/presentation/slide_show_settings/) | Gibt die Diashow-Einstellungen für die Präsentation zurück. |
| [`digital_signatures`](/slides/python-net/de/aspose.slides/presentation/digital_signatures/) | Gibt die Sammlung von Signaturen zurück, die zum Signieren der Präsentation verwendet werden.<br/>            Nur lesbar [`IDigitalSignatureCollection`](/slides/python-net/de/aspose.slides/idigitalsignaturecollection). |
| [`custom_data`](/slides/python-net/de/aspose.slides/presentation/custom_data/) | Gibt die benutzerdefinierten Daten der Präsentation zurück.<br/>            Nur lesbar [`ICustomData`](/slides/python-net/de/aspose.slides/icustomdata). |
| [`all_custom_xml_parts`](/slides/python-net/de/aspose.slides/presentation/all_custom_xml_parts/) | Gibt alle benutzerdefinierten Datenparts in der Präsentation zurück.<br/>            Nur lesbar [`ICustomXmlPart`](/slides/python-net/de/aspose.slides/icustomxmlpart)[]. |
| [`vba_project`](/slides/python-net/de/aspose.slides/presentation/vba_project/) | Ruft das VBA-Projekt mit Präsentations-Makros ab oder setzt es.<br/>            Lese/Schreib [`IVbaProject`](/slides/python-net/de/aspose.slides.vba/ivbaproject). |
| [`hyperlink_queries`](/slides/python-net/de/aspose.slides/presentation/hyperlink_queries/) | Bietet einfachen Zugriff auf alle Hyperlinks in allen Präsentations-Folien (nicht in Master-, Layout- oder Notizfolien).<br/>            Nur lesbar [`IHyperlinkQueries`](/slides/python-net/de/aspose.slides/ihyperlinkqueries). |
| [`view_properties`](/slides/python-net/de/aspose.slides/presentation/view_properties/) | Ruft die präsentationsweiten Ansichtseigenschaften ab.<br/>            Nur lesbar [`IViewProperties`](/slides/python-net/de/aspose.slides/iviewproperties). |
| [`first_slide_number`](/slides/python-net/de/aspose.slides/presentation/first_slide_number/) | Stellt die erste Foliennummer in der Präsentation dar |
| [`sensitivity_labels`](/slides/python-net/de/aspose.slides/presentation/sensitivity_labels/) | Gibt die Sammlung von Sensitivitätskennzeichnungen zurück, die auf das Präsentationsdokument angewendet wurden.<br/>            Nur lesbar [`ISensitivityLabelCollection`](/slides/python-net/de/aspose.slides/isensitivitylabelcollection). |
| [`source_format`](/slides/python-net/de/aspose.slides/presentation/source_format/) | Gibt Informationen darüber zurück, aus welchem Format die Präsentation geladen wurde.<br/>            Nur lesbar [`SourceFormat`](/slides/python-net/de/aspose.slides/sourceformat). |
| [`master_theme`](/slides/python-net/de/aspose.slides/presentation/master_theme/) | Gibt das Master-Theme zurück.<br/>            Nur lesbar [`IMasterTheme`](/slides/python-net/de/aspose.slides.theme/imastertheme). |
| [`presentation`](/slides/python-net/de/aspose.slides/presentation/presentation/) |  |

## Methoden

| Methode | Beschreibung |
| :- | :- |
| [`save(self, fname, format)`](/slides/python-net/de/aspose.slides/presentation/save/#str-asposeslidesexportsaveformat) | Speichert alle Folien einer Präsentation in einer Datei im angegebenen Format. |
| [`save(self, stream, format)`](/slides/python-net/de/aspose.slides/presentation/save/#iorawiobase-asposeslidesexportsaveformat) | Speichert alle Folien einer Präsentation in einen Stream im angegebenen Format. |
| [`save(self, fname, format, options)`](/slides/python-net/de/aspose.slides/presentation/save/#str-asposeslidesexportsaveformat-asposeslidesexportisaveoptions) |  |
| [`save(self, stream, format, options)`](/slides/python-net/de/aspose.slides/presentation/save/#iorawiobase-asposeslidesexportsaveformat-asposeslidesexportisaveoptions) | Speichert alle Folien einer Präsentation in einen Stream im angegebenen Format und mit zusätzlichen Optionen. |
| [`save(self, options)`](/slides/python-net/de/aspose.slides/presentation/save/#asposeslidesexportxamlixamloptions) | Speichert alle Folien einer Präsentation in einer Menge von Dateien, die XAML-Markup darstellen. |
| [`save(self, fname, slides, format)`](/slides/python-net/de/aspose.slides/presentation/save/#str-listint-asposeslidesexportsaveformat) | Speichert angegebene Folien einer Präsentation in einer Datei im angegebenen Format unter Beibehaltung der Seitennummer. |
| [`save(self, fname, slides, format, options)`](/slides/python-net/de/aspose.slides/presentation/save/#str-listint-asposeslidesexportsaveformat-asposeslidesexportisaveoptions) | Speichert angegebene Folien einer Präsentation in einer Datei im angegebenen Format unter Beibehaltung der Seitennummer. |
| [`save(self, stream, slides, format)`](/slides/python-net/de/aspose.slides/presentation/save/#iorawiobase-listint-asposeslidesexportsaveformat) | Speichert angegebene Folien einer Präsentation in einen Stream im angegebenen Format unter Beibehaltung der Seitennummer. |
| [`save(self, stream, slides, format, options)`](/slides/python-net/de/aspose.slides/presentation/save/#iorawiobase-listint-asposeslidesexportsaveformat-asposeslidesexportisaveoptions) | Speichert angegebene Folien einer Präsentation in einen Stream im angegebenen Format unter Beibehaltung der Seitennummer. |
| [`get_images(self, options)`](/slides/python-net/de/aspose.slides/presentation/get_images/#asposeslidesexportirenderingoptions) | Gibt Image-Objekte für alle Folien einer Präsentation zurück. |
| [`get_images(self, options, slides)`](/slides/python-net/de/aspose.slides/presentation/get_images/#asposeslidesexportirenderingoptions-listint) | Gibt Thumbnail-Image-Objekte für angegebene Folien einer Präsentation zurück. |
| [`get_images(self, options, scale_x, scale_y)`](/slides/python-net/de/aspose.slides/presentation/get_images/#asposeslidesexportirenderingoptions-float-float) | Gibt Thumbnail-Image-Objekte für alle Folien einer Präsentation mit benutzerdefinierter Skalierung zurück. |
| [`get_images(self, options, slides, scale_x, scale_y)`](/slides/python-net/de/aspose.slides/presentation/get_images/#asposeslidesexportirenderingoptions-listint-float-float) | Gibt Thumbnail-Image-Objekte für angegebene Folien einer Präsentation mit benutzerdefinierter Skalierung zurück. |
| [`get_images(self, options, image_size)`](/slides/python-net/de/aspose.slides/presentation/get_images/#asposeslidesexportirenderingoptions-asposeslidessize) | Gibt Thumbnail-Image-Objekte für alle Folien einer Präsentation mit angegebener Größe zurück. |
| [`get_images(self, options, slides, image_size)`](/slides/python-net/de/aspose.slides/presentation/get_images/#asposeslidesexportirenderingoptions-listint-asposeslidessize) | Gibt Thumbnail-Image-Objekte für angegebene Folien einer Präsentation mit angegebener Größe zurück. |
| [`highlight_text(self, text, highlight_color)`](/slides/python-net/de/aspose.slides/presentation/highlight_text/#str-asposeslidescolor) | Hebt alle Treffer des Beispieltexts mit der angegebenen Farbe hervor. |
| [`highlight_text(self, text, highlight_color, options, callback)`](/slides/python-net/de/aspose.slides/presentation/highlight_text/#str-asposeslidescolor-itextsearchoptions-ifindresultcallback) | Hebt alle Treffer des Beispieltexts mit der angegebenen Farbe hervor. |
| [`get_slide_by_id(self, id)`](/slides/python-net/de/aspose.slides/presentation/get_slide_by_id/#int) | Gibt eine Slide, MasterSlide oder LayoutSlide anhand der Id zurück. |
| [`join_portions_with_same_formatting(self)`](/slides/python-net/de/aspose.slides/presentation/join_portions_with_same_formatting/#) | Verbindet Runs mit gleicher Formatierung in allen Absätzen in allen zulässigen Formen in allen Folien. |
| [`highlight_regex(self, regex, highlight_color)`](/slides/python-net/de/aspose.slides/presentation/highlight_regex/#str-asposeslidescolor) | Hebt alle Treffer des regulären Ausdrucks mit der angegebenen Farbe hervor. |
| [`replace_text(self, old_text, new_text, options, callback)`](/slides/python-net/de/aspose.slides/presentation/replace_text/#str-str-itextsearchoptions-ifindresultcallback) | Ersetzt alle Vorkommen des angegebenen Textes durch einen anderen angegebenen Text. |
| [`replace_regex(self, regex, new_text)`](/slides/python-net/de/aspose.slides/presentation/replace_regex/#str-str) | Ersetzt alle Treffer des regulären Ausdrucks durch die angegebene Zeichenfolge. |

### Siehe auch
* Modul [`aspose.slides`](/slides/python-net/de/aspose.slides)
* Bibliothek [`Aspose.Slides`](/slides/python-net)