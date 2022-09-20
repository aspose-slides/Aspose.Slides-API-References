---
title: Presentation
second_title: Aspose.Slides für .NET-API-Referenz
description: Stellt eine Microsoft PowerPointPräsentation dar.
type: docs
weight: 8890
url: /de/net/aspose.slides/presentation/
---
## Presentation class

Stellt eine Microsoft PowerPoint-Präsentation dar.

```csharp
public sealed class Presentation : IPresentation
```

## Konstrukteure

| Name | Beschreibung |
| --- | --- |
| [Presentation](presentation#constructor)() | Dieser Konstruktor erstellt eine neue Präsentation von Grund auf neu. Die erstellte Präsentation hat eine leere Folie. |
| [Presentation](presentation#constructor_1)(LoadOptions) | Dieser Konstruktor erstellt eine neue Präsentation von Grund auf neu. Die erstellte Präsentation hat eine leere Folie. |
| [Presentation](presentation#constructor_2)(Stream) | Dieser Konstruktor ist der primäre Mechanismus zum Lesen einer vorhandenen Präsentation. |
| [Presentation](presentation#constructor_4)(string) | Dieser Konstruktor erhält einen Quelldateipfad, aus dem der Inhalt der Präsentation gelesen wird. |
| [Presentation](presentation#constructor_3)(Stream, LoadOptions) | Dieser Konstruktor ist der primäre Mechanismus zum Lesen einer vorhandenen Präsentation. |
| [Presentation](presentation#constructor_5)(string, LoadOptions) | Dieser Konstruktor erhält einen Quelldateipfad, aus dem der Inhalt der Präsentation gelesen wird. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [AllCustomXmlParts](../../aspose.slides/presentation/allcustomxmlparts) { get; } | Gibt alle benutzerdefinierten Datenteile in der Präsentation zurück. Schreibgeschützt[`ICustomXmlPart`](../icustomxmlpart) []. |
| [Audios](../../aspose.slides/presentation/audios) { get; } | Gibt die Sammlung aller eingebetteten Audiodateien in der Präsentation zurück. Schreibgeschützt[`IAudioCollection`](../iaudiocollection) . |
| [CommentAuthors](../../aspose.slides/presentation/commentauthors) { get; } | Gibt die Sammlung von Kommentaren zurück. Schreibgeschützt[`ICommentAuthorCollection`](../icommentauthorcollection) . |
| [CurrentDateTime](../../aspose.slides/presentation/currentdatetime) { get; set; } | Gibt Datum und Uhrzeit zurück oder legt sie fest, die den Inhalt der datetime-Felder ersetzen. Uhrzeit der standardmäßigen Erstellung dieses Präsentationsobjekts. Lesen/SchreibenDateTime . |
| [CustomData](../../aspose.slides/presentation/customdata) { get; } | Gibt die benutzerdefinierten Daten der Präsentation zurück. Schreibgeschützt[`ICustomData`](../icustomdata) . |
| [DefaultTextStyle](../../aspose.slides/presentation/defaulttextstyle) { get; } | Gibt den Standardtextstil für Formen zurück. Schreibgeschützt[`ITextStyle`](../itextstyle) . |
| [DigitalSignatures](../../aspose.slides/presentation/digitalsignatures) { get; } | Gibt die Sammlung von Signaturen zurück, die zum Signieren der Präsentation verwendet wurden. Schreibgeschützt[`IDigitalSignatureCollection`](../idigitalsignaturecollection) . |
| [DocumentProperties](../../aspose.slides/presentation/documentproperties) { get; } | Gibt das DocumentProperties-Objekt zurück, das standardmäßige und benutzerdefinierte Dokumenteigenschaften enthält. Schreibgeschützt[`IDocumentProperties`](../idocumentproperties) . |
| [FirstSlideNumber](../../aspose.slides/presentation/firstslidenumber) { get; set; } | Stellt die erste Foliennummer in der Präsentation dar |
| [FontsManager](../../aspose.slides/presentation/fontsmanager) { get; } | Gibt den Schriftarten-Manager zurück. Schreibgeschützt[`IFontsManager`](../ifontsmanager) . |
| [HeaderFooterManager](../../aspose.slides/presentation/headerfootermanager) { get; } | Gibt den tatsächlichen HeaderFooter-Manager zurück. Schreibgeschützt[`IPresentationHeaderFooterManager`](../ipresentationheaderfootermanager) . |
| [HyperlinkQueries](../../aspose.slides/presentation/hyperlinkqueries) { get; } | Bietet einfachen Zugriff auf alle Hyperlinks, die in allen Präsentationsfolien enthalten sind (nicht in Master-, Layout- und Notizenfolien). Schreibgeschützt[`IHyperlinkQueries`](../ihyperlinkqueries) . |
| [Images](../../aspose.slides/presentation/images) { get; } | Gibt die Sammlung aller Bilder in der Präsentation zurück. Schreibgeschützt[`IImageCollection`](../iimagecollection) . |
| [LayoutSlides](../../aspose.slides/presentation/layoutslides) { get; } | Gibt eine Liste aller Layoutfolien zurück, die in der Präsentation definiert sind. Schreibgeschützt[`IGlobalLayoutSlideCollection`](../igloballayoutslidecollection) . |
| [MasterHandoutSlideManager](../../aspose.slides/presentation/masterhandoutslidemanager) { get; } | Gibt Handout-Master-Manager zurück. Schreibgeschützt[`IMasterHandoutSlideManager`](../imasterhandoutslidemanager) . |
| [MasterNotesSlideManager](../../aspose.slides/presentation/masternotesslidemanager) { get; } | Gibt den Notes-Master-Manager zurück. Schreibgeschützt[`IMasterNotesSlideManager`](../imasternotesslidemanager) . |
| [Masters](../../aspose.slides/presentation/masters) { get; } | Gibt eine Liste aller Masterfolien zurück, die in der Präsentation definiert sind. Schreibgeschützt[`IMasterSlideCollection`](../imasterslidecollection) . |
| [MasterTheme](../../aspose.slides/presentation/mastertheme) { get; } | Gibt Masterdesign zurück. Schreibgeschützt[`IMasterTheme`](../../aspose.slides.theme/imastertheme) . |
| [NotesSize](../../aspose.slides/presentation/notessize) { get; } | Gibt das Notizen-Foliengrößenobjekt zurück. Schreibgeschützt[`INotesSize`](../inotessize) . |
| [ProtectionManager](../../aspose.slides/presentation/protectionmanager) { get; } | Ruft den Manager der Berechtigungen für diese Präsentation ab. Schreibgeschützt[`IProtectionManager`](../iprotectionmanager) . |
| [Sections](../../aspose.slides/presentation/sections) { get; } | Gibt eine Liste aller Folienabschnitte zurück, die in der Präsentation definiert sind. Schreibgeschützt[`ISectionCollection`](../isectioncollection) . |
| [Slides](../../aspose.slides/presentation/slides) { get; } | Gibt eine Liste aller Folien zurück, die in der Präsentation definiert sind. Schreibgeschützt[`ISlideCollection`](../islidecollection) . |
| [SlideShowSettings](../../aspose.slides/presentation/slideshowsettings) { get; } | Gibt die Diashow-Einstellungen für die Präsentation zurück. |
| [SlideSize](../../aspose.slides/presentation/slidesize) { get; } | Gibt das Foliengrößenobjekt zurück. Schreibgeschützt[`ISlideSize`](../islidesize) . |
| [SourceFormat](../../aspose.slides/presentation/sourceformat) { get; } | Gibt Informationen darüber zurück, aus welchem Format die Präsentation geladen wurde. Schreibgeschützt[`SourceFormat`](../sourceformat) . |
| [VbaProject](../../aspose.slides/presentation/vbaproject) { get; set; } | Ruft VBA-Projekt mit Präsentationsmakros ab oder legt es fest. Lesen/Schreiben[`IVbaProject`](../../aspose.slides.vba/ivbaproject) . |
| [Videos](../../aspose.slides/presentation/videos) { get; } | Gibt die Sammlung aller eingebetteten Videodateien in der Präsentation zurück. Schreibgeschützt[`IVideoCollection`](../ivideocollection) . |
| [ViewProperties](../../aspose.slides/presentation/viewproperties) { get; } | Ruft die Eigenschaften der präsentationsweiten Ansicht ab. Schreibgeschützt[`IViewProperties`](../iviewproperties) . |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [Dispose](../../aspose.slides/presentation/dispose)() | Gibt alle Ressourcen frei, die von diesem Präsentationsobjekt verwendet werden. |
| [GetSlideById](../../aspose.slides/presentation/getslidebyid)(uint) | Gibt eine Folie, MasterSlide oder LayoutSlide nach ID zurück. |
| [GetThumbnails](../../aspose.slides/presentation/getthumbnails#getthumbnails_6)(IRenderingOptions) | Gibt ein Thumbnail-Bitmap-Objekt für alle Folien einer Präsentation zurück. |
| [GetThumbnails](../../aspose.slides/presentation/getthumbnails#getthumbnails_7)(IRenderingOptions, int[]) | Gibt ein Thumbnail-Bitmap-Objekt für bestimmte Folien einer Präsentation zurück. |
| [GetThumbnails](../../aspose.slides/presentation/getthumbnails#getthumbnails_11)(IRenderingOptions, Size) | Gibt ein Thumbnail-Bitmap-Objekt für alle Folien einer Präsentation mit angegebener Größe zurück. |
| [GetThumbnails](../../aspose.slides/presentation/getthumbnails#getthumbnails_10)(IRenderingOptions, float, float) | Gibt ein Thumbnail-Bitmap-Objekt für alle Folien einer Präsentation mit benutzerdefinierter Skalierung zurück. |
| [GetThumbnails](../../aspose.slides/presentation/getthumbnails#getthumbnails_9)(IRenderingOptions, int[], Size) | Gibt ein Thumbnail-Bitmap-Objekt für angegebene Folien einer Präsentation mit angegebener Größe zurück. |
| [GetThumbnails](../../aspose.slides/presentation/getthumbnails#getthumbnails_8)(IRenderingOptions, int[], float, float) | Gibt ein Thumbnail-Bitmap-Objekt für bestimmte Folien einer Präsentation mit benutzerdefinierter Skalierung zurück. |
| [JoinPortionsWithSameFormatting](../../aspose.slides/presentation/joinportionswithsameformatting)() | Verbindet Läufe mit derselben Formatierung in allen Absätzen in allen akzeptablen Formen auf allen Folien. |
| [Print](../../aspose.slides/presentation/print#print)() | Druckt die gesamte Präsentation auf dem Standarddrucker. |
| [Print](../../aspose.slides/presentation/print#print_1)(PrinterSettings) | Druckt die Präsentation gemäß den angegebenen Druckereinstellungen, unter Verwendung des Standarddruckcontrollers (ohne Benutzeroberfläche). |
| [Print](../../aspose.slides/presentation/print#print_3)(string) | Drucken Sie die gesamte Präsentation auf dem angegebenen Drucker, unter Verwendung des Standarddruckcontrollers (ohne Benutzeroberfläche). |
| [Print](../../aspose.slides/presentation/print#print_2)(PrinterSettings, string) | Druckt das Dokument gemäß den angegebenen Druckereinstellungen unter Verwendung des Standarddruckcontrollers (ohne Benutzeroberfläche) und eines Präsentationsnamens. |
| [Save](../../aspose.slides/presentation/save#save)(IXamlOptions) | Speichert alle Folien einer Präsentation in einem Satz von Dateien, die XAML-Markup darstellen. |
| [Save](../../aspose.slides/presentation/save#save_1)(Stream, SaveFormat) | Speichert alle Folien einer Präsentation in einem Stream im angegebenen Format. |
| [Save](../../aspose.slides/presentation/save#save_5)(string, SaveFormat) | Speichert alle Folien einer Präsentation in eine Datei mit dem angegebenen Format. |
| [Save](../../aspose.slides/presentation/save#save_3)(Stream, int[], SaveFormat) | Speichert bestimmte Folien einer Präsentation in einem Stream im angegebenen Format unter Beibehaltung der Seitenzahl. |
| [Save](../../aspose.slides/presentation/save#save_2)(Stream, SaveFormat, ISaveOptions) | Speichert alle Folien einer Präsentation in einem Stream im angegebenen Format und mit zusätzlichen Optionen. |
| [Save](../../aspose.slides/presentation/save#save_9)(string, int[], SaveFormat) | Speichert bestimmte Folien einer Präsentation in einer Datei mit dem angegebenen Format unter Beibehaltung der Seitenzahl. |
| [Save](../../aspose.slides/presentation/save#save_6)(string, SaveFormat, ISaveOptions) | Speichert alle Folien einer Präsentation in eine Datei mit dem angegebenen Format und mit zusätzlichen Optionen. |
| [Save](../../aspose.slides/presentation/save#save_4)(Stream, int[], SaveFormat, ISaveOptions) | Speichert bestimmte Folien einer Präsentation in einem Stream im angegebenen Format unter Beibehaltung der Seitenzahl. |
| [Save](../../aspose.slides/presentation/save#save_10)(string, int[], SaveFormat, ISaveOptions) | Speichert bestimmte Folien einer Präsentation in einer Datei mit dem angegebenen Format unter Beibehaltung der Seitenzahl. |
| [Save](../../aspose.slides/presentation/save#save_8)(string, SaveFormat, HttpResponse, bool) | Sendet die Präsentation an den Client-Browser. Diese Methode fehlt in ClientProfile-Versionen von Aspose.Slide. |
| [Save](../../aspose.slides/presentation/save#save_7)(string, SaveFormat, ISaveOptions, HttpResponse, bool) | Sendet die Präsentation an den Client-Browser. Diese Methode fehlt in ClientProfile-Versionen von Aspose.Slide. |

### Siehe auch

* interface [IPresentation](../ipresentation)
* namensraum [Aspose.Slides](../../aspose.slides)
* Montage [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
