---
title: IPresentation
second_title: Aspose.Sildes für .NET API-Referenz
description: Präsentationsdokument
type: docs
weight: 6750
url: /de/aspose.slides/ipresentation/
---
## IPresentation Schnittstelle

Präsentationsdokument

```csharp
public interface IPresentation : IDisposable, IPresentationComponent
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [AllCustomXmlParts](../../aspose.slides/ipresentation/allcustomxmlparts) { get; } | Gibt alle benutzerdefinierten Datenteile in der Präsentation zurück. Nur-Lesen [`ICustomXmlPart`](../icustomxmlpart)[]. |
| [AsIDisposable](../../aspose.slides/ipresentation/asidisposable) { get; } | Gibt die IDisposable-Schnittstelle zurück. Nur-Lesen IDisposable. |
| [AsIPresentationComponent](../../aspose.slides/ipresentation/asipresentationcomponent) { get; } | Ermöglicht das Abrufen der Basis-IPresentationComponent-Schnittstelle. Nur-Lesen [`IPresentationComponent`](../ipresentationcomponent). |
| [Audios](../../aspose.slides/ipresentation/audios) { get; } | Gibt die Sammlung aller eingebetteten Audiodateien in der Präsentation zurück. Nur-Lesen [`IAudioCollection`](../iaudiocollection). |
| [CommentAuthors](../../aspose.slides/ipresentation/commentauthors) { get; } | Gibt die Sammlung der Kommentarautoren zurück. Nur-Lesen [`ICommentAuthorCollection`](../icommentauthorcollection). |
| [CurrentDateTime](../../aspose.slides/ipresentation/currentdatetime) { get; set; } | Gibt das Datum und die Uhrzeit zurück oder setzt sie, die den Inhalt von Datums-Uhrzeit-Felder ersetzen. Standardmäßig die Erstellungszeit dieses Presentation-Objekts. Lesen/Schreiben DateTime. |
| [CustomData](../../aspose.slides/ipresentation/customdata) { get; } | Gibt die benutzerdefinierten Daten der Präsentation zurück. Nur-Lesen [`ICustomData`](../icustomdata). |
| [DefaultTextStyle](../../aspose.slides/ipresentation/defaulttextstyle) { get; } | Gibt den Standard-Textstil für Formen zurück. Nur-Lesen [`ITextStyle`](../itextstyle). |
| [DigitalSignatures](../../aspose.slides/ipresentation/digitalsignatures) { get; } | Gibt die Sammlung der Signaturen zurück, die zum Signieren der Präsentation verwendet werden. Nur-Lesen [`IDigitalSignatureCollection`](../idigitalsignaturecollection). |
| [DocumentProperties](../../aspose.slides/ipresentation/documentproperties) { get; } | Gibt das DocumentProperties-Objekt zurück, das Standard- und benutzerdefinierte Dokumenteigenschaften enthält. Nur-Lesen [`IDocumentProperties`](../idocumentproperties). |
| [FirstSlideNumber](../../aspose.slides/ipresentation/firstslidenumber) { get; set; } | Stellt die erste Foliennummer in der Präsentation dar. Lesen/Schreiben Int32. |
| [FontsManager](../../aspose.slides/ipresentation/fontsmanager) { get; } | Gibt den Schriftarten-Manager zurück. Nur-Lesen [`IFontsManager`](../ifontsmanager). |
| [HeaderFooterManager](../../aspose.slides/ipresentation/headerfootermanager) { get; } | Gibt den HeaderFooter-Manager der Präsentation zurück. Nur-Lesen [`IPresentationHeaderFooterManager`](../ipresentationheaderfootermanager). |
| [HyperlinkQueries](../../aspose.slides/ipresentation/hyperlinkqueries) { get; } | Bietet einfachen Zugriff auf alle Hyperlinks, die in allen Präsentationsfolien enthalten sind (nicht in Master-, Layout- oder Notizfolien). Nur-Lesen [`IHyperlinkQueries`](../ihyperlinkqueries). |
| [Images](../../aspose.slides/ipresentation/images) { get; } | Gibt die Sammlung aller Bilder in der Präsentation zurück. Nur-Lesen [`IImageCollection`](../iimagecollection). |
| [LayoutSlides](../../aspose.slides/ipresentation/layoutslides) { get; } | Gibt eine Liste aller Layout-Folien zurück, die in der Präsentation definiert sind. Nur-Lesen [`IGlobalLayoutSlideCollection`](../igloballayoutslidecollection). |
| [MasterHandoutSlideManager](../../aspose.slides/ipresentation/masterhandoutslidemanager) { get; } | Gibt den Handout-Master-Manager zurück. Nur-Lesen [`IMasterHandoutSlideManager`](../imasterhandoutslidemanager). |
| [MasterNotesSlideManager](../../aspose.slides/ipresentation/masternotesslidemanager) { get; } | Gibt den Notizen-Master-Manager zurück. Nur-Lesen [`IMasterNotesSlideManager`](../imasternotesslidemanager). |
| [Masters](../../aspose.slides/ipresentation/masters) { get; } | Gibt eine Liste aller Master-Folien zurück, die in der Präsentation definiert sind. Nur-Lesen [`IMasterSlideCollection`](../imasterslidecollection). |
| [MasterTheme](../../aspose.slides/ipresentation/mastertheme) { get; } | Gibt das Master-Design der Präsentation zurück. Nur-Lesen [`IMasterTheme`](../../aspose.slides.theme/imastertheme). |
| [NotesSize](../../aspose.slides/ipresentation/notessize) { get; } | Gibt das Notizfolien-Größenobjekt zurück. Nur-Lesen [`INotesSize`](../inotessize). |
| [ProtectionManager](../../aspose.slides/ipresentation/protectionmanager) { get; } | Gibt den Manager der Berechtigungen für diese Präsentation zurück. Nur-Lesen [`IProtectionManager`](../iprotectionmanager). |
| [Sections](../../aspose.slides/ipresentation/sections) { get; } | Gibt eine Liste aller Folienabschnitte zurück, die in der Präsentation definiert sind. Nur-Lesen [`ISectionCollection`](../isectioncollection). |
| [SensitivityLabels](../../aspose.slides/ipresentation/sensitivitylabels) { get; } | Gibt die Sammlung der Sensitivitäts-Labels zurück, die auf das Präsentationsdokument angewendet wurden. Nur-Lesen [`ISensitivityLabelCollection`](../isensitivitylabelcollection). |
| [Slides](../../aspose.slides/ipresentation/slides) { get; } | Gibt eine Liste aller Folien zurück, die in der Präsentation definiert sind. Nur-Lesen [`ISlideCollection`](../islidecollection). |
| [SlideSize](../../aspose.slides/ipresentation/slidesize) { get; } | Gibt das Folien-Größenobjekt zurück. Nur-Lesen [`ISlideSize`](../islidesize). |
| [SourceFormat](../../aspose.slides/ipresentation/sourceformat) { get; } | Gibt Informationen darüber zurück, aus welchem Format die Präsentation geladen wurde. Nur-Lesen [`SourceFormat`](./sourceformat). |
| [VbaProject](../../aspose.slides/ipresentation/vbaproject) { get; set; } | Gibt das VBA-Projekt mit Präsentations-Makros zurück. Lesen/Schreiben [`IVbaProject`](../../aspose.slides.vba/ivbaproject). |
| [Videos](../../aspose.slides/ipresentation/videos) { get; } | Gibt die Sammlung aller eingebetteten Videodateien in der Präsentation zurück. Nur-Lesen [`IVideoCollection`](../ivideocollection). |
| [ViewProperties](../../aspose.slides/ipresentation/viewproperties) { get; } | Gibt die Präsentations-weiten Ansicht-Eigenschaften zurück. Nur-Lesen [`IViewProperties`](../iviewproperties). |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [GetImages](../../aspose.slides/ipresentation/getimages#getimages)(IRenderingOptions) | Gibt Thumbnail-Image-Objekte für alle Folien einer Präsentation zurück. |
| [GetImages](../../aspose.slides/ipresentation/getimages#getimages_1)(IRenderingOptions, int[]) | Gibt Thumbnail-Bitmap-Objekte für die angegebenen Folien einer Präsentation zurück. |
| [GetImages](../../aspose.slides/ipresentation/getimages#getimages_5)(IRenderingOptions, Size) | Gibt Thumbnail-Image-Objekte für alle Folien einer Präsentation mit angegebener Größe zurück. |
| [GetImages](../../aspose.slides/ipresentation/getimages#getimages_4)(IRenderingOptions, float, float) | Gibt Thumbnail-Image-Objekte für alle Folien einer Präsentation mit benutzerdefinierter Skalierung zurück. |
| [GetImages](../../aspose.slides/ipresentation/getimages#getimages_3)(IRenderingOptions, int[], Size) | Gibt Thumbnail-Image-Objekte für die angegebenen Folien einer Präsentation mit angegebener Größe zurück. |
| [GetImages](../../aspose.slides/ipresentation/getimages#getimages_2)(IRenderingOptions, int[], float, float) | Gibt Thumbnail-Image-Objekte für die angegebenen Folien einer Präsentation mit benutzerdefinierter Skalierung zurück. |
| [GetSlideById](../../aspose.slides/ipresentation/getslidebyid)(uint) | Gibt eine Folie, MasterSlide oder LayoutSlide anhand der Id zurück. |
| [HighlightRegex](../../aspose.slides/ipresentation/highlightregex)(Regex, Color, IFindResultCallback) | Hebt alle Treffer des regulären Ausdrucks mit der angegebenen Farbe hervor. |
| [HighlightText](../../aspose.slides/ipresentation/highlighttext#highlighttext)(string, Color) | Hebt alle Treffer des Beispieltexts mit der angegebenen Farbe hervor. |
| [HighlightText](../../aspose.slides/ipresentation/highlighttext#highlighttext_1)(string, Color, ITextSearchOptions, IFindResultCallback) | Hebt alle Treffer des Beispieltexts mit der angegebenen Farbe hervor. |
| [JoinPortionsWithSameFormatting](../../aspose.slides/ipresentation/joinportionswithsameformatting)() | Verbindet Runs mit derselben Formatierung in allen Absätzen in allen zulässigen Formen in allen Folien. |
| [ReplaceRegex](../../aspose.slides/ipresentation/replaceregex)(Regex, string, IFindResultCallback) | Ersetzt alle Treffer des regulären Ausdrucks durch die angegebene Zeichenfolge. |
| [ReplaceText](../../aspose.slides/ipresentation/replacetext)(string, string, ITextSearchOptions, IFindResultCallback) | Ersetzt alle Vorkommen des angegebenen Textes durch einen anderen angegebenen Text. |
| [Save](../../aspose.slides/ipresentation/save#save)(IXamlOptions) | Speichert alle Folien einer Präsentation in einer Menge von Dateien, die XAML-Markup darstellen. |
| [Save](../../aspose.slides/ipresentation/save#save_1)(Stream, SaveFormat) | Speichert alle Folien einer Präsentation in einen Stream im angegebenen Format. |
| [Save](../../aspose.slides/ipresentation/save#save_5)(string, SaveFormat) | Speichert alle Folien einer Präsentation in einer Datei mit dem angegebenen Format. |
| [Save](../../aspose.slides/ipresentation/save#save_3)(Stream, int[], SaveFormat) | Speichert die angegebenen Folien einer Präsentation in einen Stream im angegebenen Format. |
| [Save](../../aspose.slides/ipresentation/save#save_2)(Stream, SaveFormat, ISaveOptions) | Speichert alle Folien einer Präsentation in einen Stream im angegebenen Format und mit zusätzlichen Optionen. |
| [Save](../../aspose.slides/ipresentation/save#save_7)(string, int[], SaveFormat) | Speichert die angegebenen Folien einer Präsentation in einer Datei mit dem angegebenen Format. |
| [Save](../../aspose.slides/ipresentation/save#save_6)(string, SaveFormat, ISaveOptions) | Speichert alle Folien einer Präsentation in einer Datei mit dem angegebenen Format und mit zusätzlichen Optionen. |
| [Save](../../aspose.slides/ipresentation/save#save_4)(Stream, int[], SaveFormat, ISaveOptions) | Speichert die angegebenen Folien einer Präsentation in einen Stream im angegebenen Format. |
| [Save](../../aspose.slides/ipresentation/save#save_8)(string, int[], SaveFormat, ISaveOptions) | Speichert die angegebenen Folien einer Präsentation in einer Datei mit dem angegebenen Format. |

### Siehe auch

* Schnittstelle [IPresentationComponent](../ipresentationcomponent)
* Namensraum [Aspose.Slides](../../aspose.slides)
* Assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->