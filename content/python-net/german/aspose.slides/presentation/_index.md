---
title: Presentation class
second_title: Aspose.Slides für Python via .NET API-Referenz
description: 
type: docs
url: /de/aspose.slides/presentation/
---
## Presentation Klasse

Stellt eine Microsoft PowerPoint-Präsentation dar.

The Presentation type exposes the following members:

## Konstruktoren

| Konstruktor | Beschreibung |
| :- | :- |
| [`__init__(self)`](/slides/python-net/de/aspose.slides/presentation/__init__/#) | Dieser Konstruktor erstellt eine neue Präsentation von Grund auf.<br/>            Erstellte Präsentation hat eine leere Folie. |
| [`__init__(self, load_options)`](/slides/python-net/de/aspose.slides/presentation/__init__/#loadoptions) | Dieser Konstruktor erstellt eine neue Präsentation von Grund auf.<br/>            Erstellte Präsentation hat eine leere Folie. |
| [`__init__(self, stream)`](/slides/python-net/de/aspose.slides/presentation/__init__/#iorawiobase) | Dieser Konstruktor ist der primäre Mechanismus zum Lesen einer vorhandenen Presentation. |
| [`__init__(self, stream, load_options)`](/slides/python-net/de/aspose.slides/presentation/__init__/#iorawiobase-loadoptions) | Dieser Konstruktor ist der primäre Mechanismus zum Lesen einer vorhandenen Presentation. |
| [`__init__(self, file)`](/slides/python-net/de/aspose.slides/presentation/__init__/#str) | Dieser Konstruktor erhält einen Quelldateipfad, von dem<br/>             der Inhalt der Presentation gelesen wird. |
| [`__init__(self, file, load_options)`](/slides/python-net/de/aspose.slides/presentation/__init__/#str-loadoptions) | Dieser Konstruktor erhält einen Quelldateipfad, von dem<br/>            der Inhalt der Presentation gelesen wird. |

## Eigenschaften

| Eigenschaft | Beschreibung |
| :- | :- |
| [`current_date_time`](/slides/python-net/de/aspose.slides/presentation/current_date_time/) | Gibt Datum und Uhrzeit zurück oder legt sie fest, die den Inhalt von datetime-Feldern ersetzen.<br/>            Standardmäßig die Erstellungszeit dieses Presentation-Objekts.<br/>            Lesen/Schreiben **System.DateTime**. |
| [`header_footer_manager`](/slides/python-net/de/aspose.slides/presentation/header_footer_manager/) | Gibt den aktuellen HeaderFooter-Manager zurück.<br/>            Nur-Lesen [`IPresentationHeaderFooterManager`](/slides/python-net/de/aspose.slides/ipresentationheaderfootermanager). |
| [`protection_manager`](/slides/python-net/de/aspose.slides/presentation/protection_manager/) | Gibt den Berechtigungsmanager für diese Präsentation zurück.<br/>            Nur-Lesen [`IProtectionManager`](/slides/python-net/de/aspose.slides/iprotectionmanager). |
| [`slides`](/slides/python-net/de/aspose.slides/presentation/slides/) | Gibt eine Liste aller in der Präsentation definierten Folien zurück.<br/de/>            Nur-Lesen [`ISlideCollection`](/slides/python-net/de/aspose.slides/islidecollection). |
| [`sections`](/slides/python-net/de/aspose.slides/presentation/sections/) | Gibt eine Liste aller in der Präsentation definierten Folienabschnitte zurück.<br/>            Nur-Lesen [`ISectionCollection`](/slides/python-net/de/aspose.slides/isectioncollection). |
| [`slide_size`](/slides/python-net/de/aspose.slides/presentation/slide_size/) | Gibt das Foliengrößen-Objekt zurück.<br/>            Nur-Lesen [`ISlideSize`](/slides/python-net/de/aspose.slides/islidesize). |
| [`notes_size`](/slides/python-net/de/aspose.slides/presentation/notes_size/) | Gibt das Notizfoliengrößen-Objekt zurück.<br/>            Nur-Lesen [`INotesSize`](/slides/python-net/de/aspose.slides/inotessize). |
| [`layout_slides`](/slides/python-net/de/aspose.slides/presentation/layout_slides/) | Gibt eine Liste aller in der Präsentation definierten Layoutfolien zurück.<br/>            Nur-Lesen [`IGlobalLayoutSlideCollection`](/slides/python-net/de/aspose.slides/igloballayoutslidecollection). |
| [`masters`](/slides/python-net/de/aspose.slides/presentation/masters/) | Gibt eine Liste aller in der Präsentation definierten Masterfolien zurück.<br/>            Nur-Lesen [`IMasterSlideCollection`](/slides/python-net/de/aspose.slides/imasterslidecollection). |
| [`master_notes_slide_manager`](/slides/python-net/de/aspose.slides/presentation/master_notes_slide_manager/) | Gibt den Notiz-Master-Manager zurück.<br/>            Nur-Lesen [`IMasterNotesSlideManager`](/slides/python-net/de/aspose.slides/imasternotesslidemanager). |
| [`master_handout_slide_manager`](/slides/python-net/de/aspose.slides/presentation/master_handout_slide_manager/) | Gibt den Handzettel-Master-Manager zurück.<br/>            Nur-Lesen [`IMasterHandoutSlideManager`](/slides/python-net/de/aspose.slides/imasterhandoutslidemanager). |
| [`fonts_manager`](/slides/python-net/de/aspose.slides/presentation/fonts_manager/) | Gibt den Schriftarten-Manager zurück.<br/>            Nur-Lesen [`IFontsManager`](/slides/python-net/de/aspose.slides/ifontsmanager). |
| [`default_text_style`](/slides/python-net/de/aspose.slides/presentation/default_text_style/) | Gibt den Standardschriftstil für Formen zurück.<br/>            Nur-Lesen [`ITextStyle`](/slides/python-net/de/aspose.slides/itextstyle). |
| [`comment_authors`](/slides/python-net/de/aspose.slides/presentation/comment_authors/) | Gibt die Sammlung der Kommentarautoren zurück.<br/>            Nur-Lesen [`ICommentAuthorCollection`](/slides/python-net/de/aspose.slides/icommentauthorcollection). |
| [`document_properties`](/slides/python-net/de/aspose.slides/presentation/document_properties/) | Gibt das DocumentProperties-Objekt zurück, das Standard- und benutzerdefinierte Dokumenteigenschaften enthält.<br/>            Nur-Lesen [`IDocumentProperties`](/slides/python-net/de/aspose.slides/idocumentproperties). |
| [`images`](/slides/python-net/de/aspose.slides/presentation/images/) | Gibt die Sammlung aller Bilder in der Präsentation zurück.<br/>            Nur-Lesen [`IImageCollection`](/slides/python-net/de/aspose.slides/iimagecollection). |
| [`audios`](/slides/python-net/de/aspose.slides/presentation/audios/) | Gibt die Sammlung aller eingebetteten Audiodateien in der Präsentation zurück.<br/>            Nur-Lesen [`IAudioCollection`](/slides/python-net/de/aspose.slides/iaudiocollection). |
| [`videos`](/slides/python-net/de/aspose.slides/presentation/videos/) | Gibt die Sammlung aller eingebetteten Videodateien in der Präsentation zurück.<br/>            Nur-Lesen [`IVideoCollection`](/slides/python-net/de/aspose.slides/ivideocollection). |
| [`slide_show_settings`](/slides/python-net/de/aspose.slides/presentation/slide_show_settings/) | Gibt die Diaschau-Einstellungen für die Präsentation zurück. |
| [`digital_signatures`](/slides/python-net/de/aspose.slides/presentation/digital_signatures/) | Gibt die Sammlung der Signaturen zurück, die zum Signieren der Präsentation verwendet werden.<br/>            Nur-Lesen [`IDigitalSignatureCollection`](/slides/python-net/de/aspose.slides/idigitalsignaturecollection). |
| [`custom_data`](/slides/python-net/de/aspose.slides/presentation/custom_data/) | Gibt die benutzerdefinierten Daten der Präsentation zurück.<br/>            Nur-Lesen [`ICustomData`](/slides/python-net/de/aspose.slides/icustomdata). |
| [`all_custom_xml_parts`](/slides/python-net/de/aspose.slides/presentation/all_custom_xml_parts/) | Gibt alle benutzerdefinierten Datenabschnitte in der Präsentation zurück.<br/>            Nur-Lesen [`ICustomXmlPart`](/slides/python-net/de/aspose.slides/icustomxmlpart)[]. |
| [`vba_project`](/slides/python-net/de/aspose.slides/presentation/vba_project/) | Gibt das VBA-Projekt mit Präsentationsmakros zurück oder legt es fest.<br/>            Lesen/Schreiben [`IVbaProject`](/slides/python-net/de/aspose.slides.vba/ivbaproject). |
| [`hyperlink_queries`](/slides/python-net/de/aspose.slides/presentation/hyperlink_queries/) | Bietet einfachen Zugriff auf alle Hyperlinks in allen Präsentationsfolien (nicht in Master-, Layout- oder Notizfolien).<br/>            Nur-Lesen [`IHyperlinkQueries`](/slides/python-net/de/aspose.slides/ihyperlinkqueries). |
| [`view_properties`](/slides/python-net/de/aspose.slides/presentation/view_properties/) | Gibt die Präsentationsweiten Ansichtseigenschaften zurück.<br/>            Nur-Lesen [`IViewProperties`](/slides/python-net/de/aspose.slides/iviewproperties). |
| [`first_slide_number`](/slides/python-net/de/aspose.slides/presentation/first_slide_number/) | Stellt die Nummer der ersten Folie in der Präsentation dar |
| [`sensitivity_labels`](/slides/python-net/de/aspose.slides/presentation/sensitivity_labels/) | Gibt die Sammlung der auf das Präsentationsdokument angewendeten Sensitivitätslabels zurück.<br/>            Nur-Lesen [`ISensitivityLabelCollection`](/slides/python-net/de/aspose.slides/isensitivitylabelcollection). |
| [`source_format`](/slides/python-net/de/aspose.slides/presentation/source_format/) | Gibt Informationen darüber zurück, aus welchem Format die Präsentation geladen wurde.<br/>            Nur-Lesen [`SourceFormat`](/slides/python-net/de/aspose.slides/sourceformat). |
| [`master_theme`](/slides/python-net/de/aspose.slides/presentation/master_theme/) | Gibt das Master-Thema zurück.<br/>            Nur-Lesen [`IMasterTheme`](/slides/python-net/de/aspose.slides.theme/imastertheme). |
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
| [`get_images(self, options, image_size)`](/slides/python-net/de/aspose.slides/presentation/get_images/#asposeslidesexportirenderingoptions-asposepydrawingsize) | Gibt Thumbnail-Image-Objekte für alle Folien einer Präsentation mit angegebenen Abmessungen zurück. |
| [`get_images(self, options, slides, image_size)`](/slides/python-net/de/aspose.slides/presentation/get_images/#asposeslidesexportirenderingoptions-listint-asposepydrawingsize) | Gibt Thumbnail-Image-Objekte für angegebene Folien einer Präsentation mit angegebenen Abmessungen zurück. |
| [`highlight_text(self, text, highlight_color)`](/slides/python-net/de/aspose.slides/presentation/highlight_text/#str-asposepydrawingcolor) | Hebt alle Treffer des Beispieltextes mit der angegebenen Farbe hervor. |
| [`highlight_text(self, text, highlight_color, options, callback)`](/slides/python-net/de/aspose.slides/presentation/highlight_text/#str-asposepydrawingcolor-itextsearchoptions-ifindresultcallback) | Hebt alle Treffer des Beispieltextes mit der angegebenen Farbe hervor. |
| [`get_slide_by_id(self, id)`](/slides/python-net/de/aspose.slides/presentation/get_slide_by_id/#int) | Gibt eine Slide, MasterSlide oder LayoutSlide anhand der Id zurück. |
| [`join_portions_with_same_formatting(self)`](/slides/python-net/de/aspose.slides/presentation/join_portions_with_same_formatting/#) | Führt Runs mit derselben Formatierung in allen Absätzen in allen zulässigen Formen in allen Folien zusammen. |
| [`highlight_regex(self, regex, highlight_color)`](/slides/python-net/de/aspose.slides/presentation/highlight_regex/#str-asposepydrawingcolor) | Hebt alle Treffer des regulären Ausdrucks mit der angegebenen Farbe hervor. |
| [`replace_text(self, old_text, new_text, options, callback)`](/slides/python-net/de/aspose.slides/presentation/replace_text/#str-str-itextsearchoptions-ifindresultcallback) | Ersetzt alle Vorkommen des angegebenen Textes durch einen anderen angegebenen Text. |
| [`replace_regex(self, regex, new_text)`](/slides/python-net/de/aspose.slides/presentation/replace_regex/#str-str) | Ersetzt alle Treffer des regulären Ausdrucks durch die angegebene Zeichenfolge. |

### Siehe auch
* Modul [`aspose.slides`](/slides/python-net/de/aspose.slides)
* Bibliothek [`Aspose.Slides`](/slides/python-net)