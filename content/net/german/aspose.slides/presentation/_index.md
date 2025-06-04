---
title: Presentation
second_title: Aspose.Slides für .NET API-Referenz
description: Stellt eine Microsoft PowerPoint-Präsentation dar.
type: docs
weight: 9320
url: /de/aspose.slides/presentation/
---

## Präsentation Klasse

Stellt eine Microsoft PowerPoint-Präsentation dar.

```csharp
public sealed class Presentation : IPresentation
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [Presentation](presentation#constructor)() | Dieser Konstruktor erstellt eine neue Präsentation von Grund auf. Die erstellte Präsentation hat eine leere Folie. |
| [Presentation](presentation#constructor_1)(LoadOptions) | Dieser Konstruktor erstellt eine neue Präsentation von Grund auf. Die erstellte Präsentation hat eine leere Folie. |
| [Presentation](presentation#constructor_2)(Stream) | Dieser Konstruktor ist der primäre Mechanismus zum Lesen einer vorhandenen Präsentation. |
| [Presentation](presentation#constructor_4)(string) | Dieser Konstruktor erhält einen Quell-Dateipfad, aus dem die Inhalte der Präsentation gelesen werden. |
| [Presentation](presentation#constructor_3)(Stream, LoadOptions) | Dieser Konstruktor ist der primäre Mechanismus zum Lesen einer vorhandenen Präsentation. |
| [Presentation](presentation#constructor_5)(string, LoadOptions) | Dieser Konstruktor erhält einen Quell-Dateipfad, aus dem die Inhalte der Präsentation gelesen werden. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [AllCustomXmlParts](../../aspose.slides/presentation/allcustomxmlparts) { get; } | Gibt alle benutzerdefinierten Datenteile in der Präsentation zurück. Nur-lesend [`ICustomXmlPart`](../icustomxmlpart)[]. |
| [Audios](../../aspose.slides/presentation/audios) { get; } | Gibt die Sammlung aller eingebetteten Audiodateien in der Präsentation zurück. Nur-lesend [`IAudioCollection`](../iaudiocollection). |
| [CommentAuthors](../../aspose.slides/presentation/commentauthors) { get; } | Gibt die Sammlung der Kommentarauthoren zurück. Nur-lesend [`ICommentAuthorCollection`](../icommentauthorcollection). |
| [CurrentDateTime](../../aspose.slides/presentation/currentdatetime) { get; set; } | Gibt das Datum und die Uhrzeit zurück oder setzt sie, die den Inhalt von Datums- und Zeitfeldern ersetzen. Zeit der Erstellung dieses Präsentationsobjekts standardmäßig. Schreib-/lesbar DateTime. |
| [CustomData](../../aspose.slides/presentation/customdata) { get; } | Gibt die benutzerdefinierten Daten der Präsentation zurück. Nur-lesend [`ICustomData`](../icustomdata). |
| [DefaultTextStyle](../../aspose.slides/presentation/defaulttextstyle) { get; } | Gibt den Standardtextstil für Formen zurück. Nur-lesend [`ITextStyle`](../itextstyle). |
| [DigitalSignatures](../../aspose.slides/presentation/digitalsignatures) { get; } | Gibt die Sammlung der Signaturen zurück, die zur Signierung der Präsentation verwendet werden. Nur-lesend [`IDigitalSignatureCollection`](../idigitalsignaturecollection). |
| [DocumentProperties](../../aspose.slides/presentation/documentproperties) { get; } | Gibt das DocumentProperties-Objekt zurück, das Standard- und benutzerdefinierte Dokumenteigenschaften enthält. Nur-lesend [`IDocumentProperties`](../idocumentproperties). |
| [FirstSlideNumber](../../aspose.slides/presentation/firstslidenumber) { get; set; } | Stellt die erste Foliennummer in der Präsentation dar. |
| [FontsManager](../../aspose.slides/presentation/fontsmanager) { get; } | Gibt den Schriftarten-Manager zurück. Nur-lesend [`IFontsManager`](../ifontsmanager). |
| [HeaderFooterManager](../../aspose.slides/presentation/headerfootermanager) { get; } | Gibt den aktuellen HeaderFooter-Manager zurück. Nur-lesend [`IPresentationHeaderFooterManager`](../ipresentationheaderfootermanager). |
| [HyperlinkQueries](../../aspose.slides/presentation/hyperlinkqueries) { get; } | Bietet einfachen Zugriff auf alle Hyperlinks, die in allen Folien der Präsentation enthalten sind (nicht in Master-, Layout- oder Notizfolien). Nur-lesend [`IHyperlinkQueries`](../ihyperlinkqueries). |
| [Images](../../aspose.slides/presentation/images) { get; } | Gibt die Sammlung aller Bilder in der Präsentation zurück. Nur-lesend [`IImageCollection`](../iimagecollection). |
| [LayoutSlides](../../aspose.slides/presentation/layoutslides) { get; } | Gibt eine Liste aller Layoutfolien zurück, die in der Präsentation definiert sind. Nur-lesend [`IGlobalLayoutSlideCollection`](../igloballayoutslidecollection). |
| [MasterHandoutSlideManager](../../aspose.slides/presentation/masterhandoutslidemanager) { get; } | Gibt den Handout-Master-Manager zurück. Nur-lesend [`IMasterHandoutSlideManager`](../imasterhandoutslidemanager). |
| [MasterNotesSlideManager](../../aspose.slides/presentation/masternotesslidemanager) { get; } | Gibt den Notizen-Master-Manager zurück. Nur-lesend [`IMasterNotesSlideManager`](../imasternotesslidemanager). |
| [Masters](../../aspose.slides/presentation/masters) { get; } | Gibt eine Liste aller Masterfolien zurück, die in der Präsentation definiert sind. Nur-lesend [`IMasterSlideCollection`](../imasterslidecollection). |
| [MasterTheme](../../aspose.slides/presentation/mastertheme) { get; } | Gibt das Masterthema zurück. Nur-lesend [`IMasterTheme`](../../aspose.slides.theme/imastertheme). |
| [NotesSize](../../aspose.slides/presentation/notessize) { get; } | Gibt das Objekt für die Größe der Notizfolie zurück. Nur-lesend [`INotesSize`](../inotessize). |
| [ProtectionManager](../../aspose.slides/presentation/protectionmanager) { get; } | Gibt den Manager der Berechtigungen für diese Präsentation zurück. Nur-lesend [`IProtectionManager`](../iprotectionmanager). |
| [Sections](../../aspose.slides/presentation/sections) { get; } | Gibt eine Liste aller Folienabschnitte zurück, die in der Präsentation definiert sind. Nur-lesend [`ISectionCollection`](../isectioncollection). |
| [Slides](../../aspose.slides/presentation/slides) { get; } | Gibt eine Liste aller Folien zurück, die in der Präsentation definiert sind. Nur-lesend [`ISlideCollection`](../islidecollection). |
| [SlideShowSettings](../../aspose.slides/presentation/slideshowsettings) { get; } | Gibt die Einstellungen für die Bildschirmpräsentation der Präsentation zurück. |
| [SlideSize](../../aspose.slides/presentation/slidesize) { get; } | Gibt das Foliengrößenobjekt zurück. Nur-lesend [`ISlideSize`](../islidesize). |
| [SourceFormat](../../aspose.slides/presentation/sourceformat) { get; } | Gibt Informationen darüber zurück, aus welchem Format die Präsentation geladen wurde. Nur-lesend [`SourceFormat`](../sourceformat). |
| [VbaProject](../../aspose.slides/presentation/vbaproject) { get; set; } | Gibt das VBA-Projekt mit Makros der Präsentation zurück oder setzt es. Schreib-/lesbar [`IVbaProject`](../../aspose.slides.vba/ivbaproject). |
| [Videos](../../aspose.slides/presentation/videos) { get; } | Gibt die Sammlung aller eingebetteten Videodateien in der Präsentation zurück. Nur-lesend [`IVideoCollection`](../ivideocollection). |
| [ViewProperties](../../aspose.slides/presentation/viewproperties) { get; } | Gibt die präsentationsweiten Anzeigeeigenschaften zurück. Nur-lesend [`IViewProperties`](../iviewproperties). |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [Dispose](../../aspose.slides/presentation/dispose)() | Gibt alle Ressourcen frei, die von diesem Präsentationsobjekt verwendet werden. |
| [GetImages](../../aspose.slides/presentation/getimages#getimages)(IRenderingOptions) | Gibt ein Bildobjekt für alle Folien einer Präsentation zurück. |
| [GetImages](../../aspose.slides/presentation/getimages#getimages_1)(IRenderingOptions, int[]) | Gibt ein Thumbnail-Bildobjekt für die angegebenen Folien einer Präsentation zurück. |
| [GetImages](../../aspose.slides/presentation/getimages#getimages_5)(IRenderingOptions, Size) | Gibt ein Thumbnail-Bildobjekt für alle Folien einer Präsentation mit der angegebenen Größe zurück. |
| [GetImages](../../aspose.slides/presentation/getimages#getimages_4)(IRenderingOptions, float, float) | Gibt ein Thumbnail-Bildobjekt für alle Folien einer Präsentation mit benutzerdefinierter Skalierung zurück. |
| [GetImages](../../aspose.slides/presentation/getimages#getimages_3)(IRenderingOptions, int[], Size) | Gibt ein Thumbnail-Bildobjekt für die angegebenen Folien einer Präsentation mit der angegebenen Größe zurück. |
| [GetImages](../../aspose.slides/presentation/getimages#getimages_2)(IRenderingOptions, int[], float, float) | Gibt ein Thumbnail-Bildobjekt für die angegebenen Folien einer Präsentation mit benutzerdefinierter Skalierung zurück. |
| [GetSlideById](../../aspose.slides/presentation/getslidebyid)(uint) | Gibt eine Folie, Masterfolie oder Layoutfolie nach Id zurück. |
| [HighlightRegex](../../aspose.slides/presentation/highlightregex)(Regex, Color, IFindResultCallback) | Hebt alle Übereinstimmungen der regulären Ausdruck mit der angegebenen Farbe hervor. |
| [HighlightText](../../aspose.slides/presentation/highlighttext#highlighttext)(string, Color) | Hebt alle Übereinstimmungen des Beispieltextes mit der angegebenen Farbe hervor. |
| [HighlightText](../../aspose.slides/presentation/highlighttext#highlighttext_1)(string, Color, ITextSearchOptions, IFindResultCallback) | Hebt alle Übereinstimmungen des Beispieltextes mit der angegebenen Farbe hervor. |
| [JoinPortionsWithSameFormatting](../../aspose.slides/presentation/joinportionswithsameformatting)() | Verbindet Abschnitte mit demselben Format in allen Absätzen in allen akzeptablen Formen in allen Folien. |
| [ReplaceRegex](../../aspose.slides/presentation/replaceregex)(Regex, string, IFindResultCallback) | Ersetzt alle Übereinstimmungen des regulären Ausdrucks durch den angegebenen String. |
| [ReplaceText](../../aspose.slides/presentation/replacetext)(string, string, ITextSearchOptions, IFindResultCallback) | Ersetzt alle Vorkommen des angegebenen Textes durch einen anderen angegebenen Text. |
| [Save](../../aspose.slides/presentation/save#save)(IXamlOptions) | Speichert alle Folien einer Präsentation in einer Reihe von Dateien, die XAML-Markup darstellen. |
| [Save](../../aspose.slides/presentation/save#save_1)(Stream, SaveFormat) | Speichert alle Folien einer Präsentation in einem Stream im angegebenen Format. |
| [Save](../../aspose.slides/presentation/save#save_5)(string, SaveFormat) | Speichert alle Folien einer Präsentation in einer Datei mit dem angegebenen Format. |
| [Save](../../aspose.slides/presentation/save#save_3)(Stream, int[], SaveFormat) | Speichert die angegebenen Folien einer Präsentation in einem Stream im angegebenen Format mit Seitenzahlenbeibehaltung. |
| [Save](../../aspose.slides/presentation/save#save_2)(Stream, SaveFormat, ISaveOptions) | Speichert alle Folien einer Präsentation in einem Stream im angegebenen Format und mit zusätzlichen Optionen. |
| [Save](../../aspose.slides/presentation/save#save_7)(string, int[], SaveFormat) | Speichert die angegebenen Folien einer Präsentation in einer Datei mit dem angegebenen Format und mit Seitenzahlenbeibehaltung. |
| [Save](../../aspose.slides/presentation/save#save_6)(string, SaveFormat, ISaveOptions) |  |
| [Save](../../aspose.slides/presentation/save#save_4)(Stream, int[], SaveFormat, ISaveOptions) | Speichert die angegebenen Folien einer Präsentation in einem Stream im angegebenen Format mit Seitenzahlenbeibehaltung. |
| [Save](../../aspose.slides/presentation/save#save_8)(string, int[], SaveFormat, ISaveOptions) | Speichert die angegebenen Folien einer Präsentation in einer Datei mit dem angegebenen Format und mit Seitenzahlenbeibehaltung. |

### Beispiele

Das folgende Beispiel zeigt, wie man eine PowerPoint-Präsentation erstellt.

```csharp
[C#]
// Erstellen Sie ein Präsentationsobjekt, das eine Präsentationsdatei darstellt
using (Presentation presentation = new Presentation())
{
    // Holen Sie die erste Folie
    ISlide slide = presentation.Slides[0];
    // Fügen Sie eine Autoshape vom Typ Linie hinzu
    slide.Shapes.AddAutoShape(ShapeType.Line, 50, 150, 300, 0);
	// Speichern Sie die Präsentationsdatei.
    presentation.Save("NewPresentation_out.pptx", SaveFormat.Pptx);
}
```

Das folgende Beispiel zeigt, wie man eine Präsentation öffnet und speichert.

```csharp
[C#]
// Laden Sie eine unterstützte Datei in die Präsentation, z.B. ppt, pptx, odp usw.
using (Presentation presentation = new Presentation("Sample.odp"))
{
	// Speichern Sie die Präsentationsdatei.
	presentation.Save("OutputPresentation.pptx", SaveFormat.Pptx);
}
```

### Siehe auch

* interface [IPresentation](../ipresentation)
* namespace [Aspose.Slides](../../aspose.slides)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->