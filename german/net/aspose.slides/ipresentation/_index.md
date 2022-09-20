---
title: IPresentation
second_title: Aspose.Slides für .NET-API-Referenz
description: Präsentationsdokument
type: docs
weight: 6220
url: /de/net/aspose.slides/ipresentation/
---
## IPresentation interface

Präsentationsdokument

```csharp
public interface IPresentation : IDisposable, IPresentationComponent
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [AllCustomXmlParts](../../aspose.slides/ipresentation/allcustomxmlparts) { get; } | Gibt alle benutzerdefinierten Datenteile in der Präsentation zurück. Schreibgeschützt[`ICustomXmlPart`](../icustomxmlpart) []. |
| [AsIDisposable](../../aspose.slides/ipresentation/asidisposable) { get; } | Gibt IDisposable-Schnittstelle zurück. SchreibgeschütztIDisposable . |
| [AsIPresentationComponent](../../aspose.slides/ipresentation/asipresentationcomponent) { get; } | Ermöglicht das Abrufen der Basis-IPPresentationComponent-Schnittstelle. Schreibgeschützt[`IPresentationComponent`](../ipresentationcomponent) . |
| [Audios](../../aspose.slides/ipresentation/audios) { get; } | Gibt die Sammlung aller eingebetteten Audiodateien in der Präsentation zurück. Schreibgeschützt[`IAudioCollection`](../iaudiocollection) . |
| [CommentAuthors](../../aspose.slides/ipresentation/commentauthors) { get; } | Gibt die Sammlung von Kommentaren zurück. Schreibgeschützt[`ICommentAuthorCollection`](../icommentauthorcollection) . |
| [CurrentDateTime](../../aspose.slides/ipresentation/currentdatetime) { get; set; } | Gibt Datum und Uhrzeit zurück oder legt sie fest, die den Inhalt der datetime-Felder ersetzen. Uhrzeit der standardmäßigen Erstellung dieses Präsentationsobjekts. Lesen/SchreibenDateTime . |
| [CustomData](../../aspose.slides/ipresentation/customdata) { get; } | Gibt die benutzerdefinierten Daten der Präsentation zurück. Schreibgeschützt[`ICustomData`](../icustomdata) . |
| [DefaultTextStyle](../../aspose.slides/ipresentation/defaulttextstyle) { get; } | Gibt den Standardtextstil für Formen zurück. Schreibgeschützt[`ITextStyle`](../itextstyle) . |
| [DigitalSignatures](../../aspose.slides/ipresentation/digitalsignatures) { get; } | Gibt die Sammlung von Signaturen zurück, die zum Signieren der Präsentation verwendet wurden. Schreibgeschützt[`IDigitalSignatureCollection`](../idigitalsignaturecollection) . |
| [DocumentProperties](../../aspose.slides/ipresentation/documentproperties) { get; } | Gibt das DocumentProperties-Objekt zurück, das standardmäßige und benutzerdefinierte Dokumenteigenschaften enthält. Schreibgeschützt[`IDocumentProperties`](../idocumentproperties) . |
| [FirstSlideNumber](../../aspose.slides/ipresentation/firstslidenumber) { get; set; } | Repräsentiert die erste Foliennummer in der Präsentation. Lesen/SchreibenInt32 . |
| [FontsManager](../../aspose.slides/ipresentation/fontsmanager) { get; } | Gibt den Schriftarten-Manager zurück. Schreibgeschützt[`IFontsManager`](../ifontsmanager) . |
| [HeaderFooterManager](../../aspose.slides/ipresentation/headerfootermanager) { get; } | Gibt den HeaderFooter-Manager der Präsentation zurück. Schreibgeschützt[`IPresentationHeaderFooterManager`](../ipresentationheaderfootermanager) . |
| [HyperlinkQueries](../../aspose.slides/ipresentation/hyperlinkqueries) { get; } | Bietet einfachen Zugriff auf alle Hyperlinks, die in allen Präsentationsfolien enthalten sind (nicht in Master-, Layout- und Notizenfolien). Schreibgeschützt[`IHyperlinkQueries`](../ihyperlinkqueries) . |
| [Images](../../aspose.slides/ipresentation/images) { get; } | Gibt die Sammlung aller Bilder in der Präsentation zurück. Schreibgeschützt[`IImageCollection`](../iimagecollection) . |
| [LayoutSlides](../../aspose.slides/ipresentation/layoutslides) { get; } | Gibt eine Liste aller Layoutfolien zurück, die in der Präsentation definiert sind. Schreibgeschützt[`IGlobalLayoutSlideCollection`](../igloballayoutslidecollection) . |
| [MasterHandoutSlideManager](../../aspose.slides/ipresentation/masterhandoutslidemanager) { get; } | Gibt Handout-Master-Manager zurück. Schreibgeschützt[`IMasterHandoutSlideManager`](../imasterhandoutslidemanager) . |
| [MasterNotesSlideManager](../../aspose.slides/ipresentation/masternotesslidemanager) { get; } | Gibt den Notes-Master-Manager zurück. Schreibgeschützt[`IMasterNotesSlideManager`](../imasternotesslidemanager) . |
| [Masters](../../aspose.slides/ipresentation/masters) { get; } | Gibt eine Liste aller Masterfolien zurück, die in der Präsentation definiert sind. Schreibgeschützt[`IMasterSlideCollection`](../imasterslidecollection) . |
| [MasterTheme](../../aspose.slides/ipresentation/mastertheme) { get; } | Gibt das Hauptthema der Präsentation zurück. Schreibgeschützt[`IMasterTheme`](../../aspose.slides.theme/imastertheme) . |
| [NotesSize](../../aspose.slides/ipresentation/notessize) { get; } | Gibt das Notizen-Foliengrößenobjekt zurück. Schreibgeschützt[`INotesSize`](../inotessize) . |
| [ProtectionManager](../../aspose.slides/ipresentation/protectionmanager) { get; } | Ruft den Manager der Berechtigungen für diese Präsentation ab. Schreibgeschützt[`IProtectionManager`](../iprotectionmanager) . |
| [Sections](../../aspose.slides/ipresentation/sections) { get; } | Gibt eine Liste aller Folienabschnitte zurück, die in der Präsentation definiert sind. Schreibgeschützt[`ISectionCollection`](../isectioncollection) . |
| [Slides](../../aspose.slides/ipresentation/slides) { get; } | Gibt eine Liste aller Folien zurück, die in der Präsentation definiert sind. Schreibgeschützt[`ISlideCollection`](../islidecollection) . |
| [SlideSize](../../aspose.slides/ipresentation/slidesize) { get; } | Gibt das Foliengrößenobjekt zurück. Schreibgeschützt[`ISlideSize`](../islidesize) . |
| [SourceFormat](../../aspose.slides/ipresentation/sourceformat) { get; } | Gibt Informationen darüber zurück, aus welchem Format die Präsentation geladen wurde. Schreibgeschützt[`SourceFormat`](./sourceformat) . |
| [VbaProject](../../aspose.slides/ipresentation/vbaproject) { get; set; } | Ruft VBA-Projekt mit Präsentationsmakros ab. Lesen/Schreiben[`IVbaProject`](../../aspose.slides.vba/ivbaproject) . |
| [Videos](../../aspose.slides/ipresentation/videos) { get; } | Gibt die Sammlung aller eingebetteten Videodateien in der Präsentation zurück. Schreibgeschützt[`IVideoCollection`](../ivideocollection) . |
| [ViewProperties](../../aspose.slides/ipresentation/viewproperties) { get; } | Ruft die Eigenschaften der präsentationsweiten Ansicht ab. Schreibgeschützt[`IViewProperties`](../iviewproperties) . |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [GetSlideById](../../aspose.slides/ipresentation/getslidebyid)(uint) | Gibt eine Folie, MasterSlide oder LayoutSlide nach ID zurück. |
| [GetThumbnails](../../aspose.slides/ipresentation/getthumbnails#getthumbnails_6)(IRenderingOptions) | Gibt ein Thumbnail-Bitmap-Objekt für alle Folien einer Präsentation zurück. |
| [GetThumbnails](../../aspose.slides/ipresentation/getthumbnails#getthumbnails_7)(IRenderingOptions, int[]) | Gibt ein Thumbnail-Bitmap-Objekt für bestimmte Folien einer Präsentation zurück. |
| [GetThumbnails](../../aspose.slides/ipresentation/getthumbnails#getthumbnails_11)(IRenderingOptions, Size) | Gibt ein Thumbnail-Bitmap-Objekt für alle Folien einer Präsentation mit angegebener Größe zurück. |
| [GetThumbnails](../../aspose.slides/ipresentation/getthumbnails#getthumbnails_10)(IRenderingOptions, float, float) | Gibt ein Thumbnail-Bitmap-Objekt für alle Folien einer Präsentation mit benutzerdefinierter Skalierung zurück. |
| [GetThumbnails](../../aspose.slides/ipresentation/getthumbnails#getthumbnails_9)(IRenderingOptions, int[], Size) | Gibt ein Thumbnail-Bitmap-Objekt für angegebene Folien einer Präsentation mit angegebener Größe zurück. |
| [GetThumbnails](../../aspose.slides/ipresentation/getthumbnails#getthumbnails_8)(IRenderingOptions, int[], float, float) | Gibt ein Thumbnail-Bitmap-Objekt für bestimmte Folien einer Präsentation mit benutzerdefinierter Skalierung zurück. |
| [JoinPortionsWithSameFormatting](../../aspose.slides/ipresentation/joinportionswithsameformatting)() | Verbindet Läufe mit derselben Formatierung in allen Absätzen in allen akzeptablen Formen auf allen Folien. |
| [Print](../../aspose.slides/ipresentation/print#print)() | Druckt die gesamte Präsentation auf dem Standarddrucker. |
| [Print](../../aspose.slides/ipresentation/print#print_1)(PrinterSettings) | Druckt die Präsentation gemäß den angegebenen Druckereinstellungen, unter Verwendung des Standarddruckcontrollers (ohne Benutzeroberfläche). |
| [Print](../../aspose.slides/ipresentation/print#print_3)(string) | Drucken Sie die gesamte Präsentation auf dem angegebenen Drucker, unter Verwendung des Standarddruckcontrollers (ohne Benutzeroberfläche). |
| [Print](../../aspose.slides/ipresentation/print#print_2)(PrinterSettings, string) | Druckt das Dokument gemäß den angegebenen Druckereinstellungen unter Verwendung des Standarddruckcontrollers (ohne Benutzeroberfläche) und eines Präsentationsnamens. |
| [Save](../../aspose.slides/ipresentation/save#save)(IXamlOptions) | Speichert alle Folien einer Präsentation in einem Satz von Dateien, die XAML-Markup darstellen. |
| [Save](../../aspose.slides/ipresentation/save#save_1)(Stream, SaveFormat) | Speichert alle Folien einer Präsentation in einem Stream im angegebenen Format. |
| [Save](../../aspose.slides/ipresentation/save#save_5)(string, SaveFormat) | Speichert alle Folien einer Präsentation in eine Datei mit dem angegebenen Format. |
| [Save](../../aspose.slides/ipresentation/save#save_3)(Stream, int[], SaveFormat) | Speichert bestimmte Folien einer Präsentation in einem Stream im angegebenen Format. |
| [Save](../../aspose.slides/ipresentation/save#save_2)(Stream, SaveFormat, ISaveOptions) | Speichert alle Folien einer Präsentation in einem Stream im angegebenen Format und mit zusätzlichen Optionen. |
| [Save](../../aspose.slides/ipresentation/save#save_9)(string, int[], SaveFormat) | Speichert bestimmte Folien einer Präsentation in einer Datei mit dem angegebenen Format. |
| [Save](../../aspose.slides/ipresentation/save#save_6)(string, SaveFormat, ISaveOptions) | Speichert alle Folien einer Präsentation in eine Datei mit dem angegebenen Format und mit zusätzlichen Optionen. |
| [Save](../../aspose.slides/ipresentation/save#save_4)(Stream, int[], SaveFormat, ISaveOptions) | Speichert bestimmte Folien einer Präsentation in einem Stream im angegebenen Format. |
| [Save](../../aspose.slides/ipresentation/save#save_10)(string, int[], SaveFormat, ISaveOptions) | Speichert bestimmte Folien einer Präsentation in einer Datei mit dem angegebenen Format. |
| [Save](../../aspose.slides/ipresentation/save#save_8)(string, SaveFormat, HttpResponse, bool) | Sendet die Präsentation an den Client-Browser. Diese Methode fehlt in ClientProfile-Versionen von Aspose.Slide. |
| [Save](../../aspose.slides/ipresentation/save#save_7)(string, SaveFormat, ISaveOptions, HttpResponse, bool) | Sendet die Präsentation an den Client-Browser. Diese Methode fehlt in ClientProfile-Versionen von Aspose.Slide. |

### Siehe auch

* interface [IPresentationComponent](../ipresentationcomponent)
* namensraum [Aspose.Slides](../../aspose.slides)
* Montage [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
