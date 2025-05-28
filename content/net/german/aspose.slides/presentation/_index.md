---
title: Präsentation
second_title: Aspose.Slides für .NET API Referenz
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
| [Presentation](presentation#constructor_4)(string) | Dieser Konstruktor erhält einen Dateipfad, aus dem der Inhalt der Präsentation gelesen wird. |
| [Presentation](presentation#constructor_3)(Stream, LoadOptions) | Dieser Konstruktor ist der primäre Mechanismus zum Lesen einer vorhandenen Präsentation. |
| [Presentation](presentation#constructor_5)(string, LoadOptions) | Dieser Konstruktor erhält einen Dateipfad, aus dem der Inhalt der Präsentation gelesen wird. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [AllCustomXmlParts](../../aspose.slides/presentation/allcustomxmlparts) { get; } | Gibt alle benutzerdefinierten Datenparts in der Präsentation zurück. Nur-Lese [`ICustomXmlPart`](../icustomxmlpart)[]. |
| [Audios](../../aspose.slides/presentation/audios) { get; } | Gibt die Sammlung aller eingebetteten Audiodateien in der Präsentation zurück. Nur-Lese [`IAudioCollection`](../iaudiocollection). |
| [CommentAuthors](../../aspose.slides/presentation/commentauthors) { get; } | Gibt die Sammlung der Kommentarautoren zurück. Nur-Lese [`ICommentAuthorCollection`](../icommentauthorcollection). |
| [CurrentDateTime](../../aspose.slides/presentation/currentdatetime) { get; set; } | Gibt das Datum und die Uhrzeit zurück oder setzt sie, die den Inhalt der Datumsfeld ersetzen. Zeitpunkt der Erstellung dieses Präsentationsobjekts standardmäßig. Lese-/Schreibzugriff DateTime. |
| [CustomData](../../aspose.slides/presentation/customdata) { get; } | Gibt die benutzerdefinierten Daten der Präsentation zurück. Nur-Lese [`ICustomData`](../icustomdata). |
| [DefaultTextStyle](../../aspose.slides/presentation/defaulttextstyle) { get; } | Gibt den Standardtextstil für Formen zurück. Nur-Lese [`ITextStyle`](../itextstyle). |
| [DigitalSignatures](../../aspose.slides/presentation/digitalsignatures) { get; } | Gibt die Sammlung der Signaturen zurück, die zur Signierung der Präsentation verwendet werden. Nur-Lese [`IDigitalSignatureCollection`](../idigitalsignaturecollection). |
| [DocumentProperties](../../aspose.slides/presentation/documentproperties) { get; } | Gibt das DocumentProperties-Objekt zurück, das Standard- und benutzerdefinierte Dokumenteigenschaften enthält. Nur-Lese [`IDocumentProperties`](../idocumentproperties). |
| [FirstSlideNumber](../../aspose.slides/presentation/firstslidenumber) { get; set; } | Stellt die erste Foliennummer in der Präsentation dar. |
| [FontsManager](../../aspose.slides/presentation/fontsmanager) { get; } | Gibt den Schriftartenmanager zurück. Nur-Lese [`IFontsManager`](../ifontsmanager). |
| [HeaderFooterManager](../../aspose.slides/presentation/headerfootermanager) { get; } | Gibt den aktuellen HeaderFooter-Manager zurück. Nur-Lese [`IPresentationHeaderFooterManager`](../ipresentationheaderfootermanager). |
| [HyperlinkQueries](../../aspose.slides/presentation/hyperlinkqueries) { get; } | Bietet einfachen Zugriff auf alle Hyperlinks, die in allen Präsentationsfolien enthalten sind (nicht in Master-, Layout- und Notizfolien). Nur-Lese [`IHyperlinkQueries`](../ihyperlinkqueries). |
| [Images](../../aspose.slides/presentation/images) { get; } | Gibt die Sammlung aller Bilder in der Präsentation zurück. Nur-Lese [`IImageCollection`](../iimagecollection). |
| [LayoutSlides](../../aspose.slides/presentation/layoutslides) { get; } | Gibt eine Liste aller Layoutfolien zurück, die in der Präsentation definiert sind. Nur-Lese [`IGlobalLayoutSlideCollection`](../igloballayoutslidecollection). |
| [MasterHandoutSlideManager](../../aspose.slides/presentation/masterhandoutslidemanager) { get; } | Gibt den Handout-Master-Manager zurück. Nur-Lese [`IMasterHandoutSlideManager`](../imasterhandoutslidemanager). |
| [MasterNotesSlideManager](../../aspose.slides/presentation/masternotesslidemanager) { get; } | Gibt den Notizen-Master-Manager zurück. Nur-Lese [`IMasterNotesSlideManager`](../imasternotesslidemanager). |
| [Masters](../../aspose.slides/presentation/masters) { get; } | Gibt eine Liste aller Masterfolien zurück, die in der Präsentation definiert sind. Nur-Lese [`IMasterSlideCollection`](../imasterslidecollection). |
| [MasterTheme](../../aspose.slides/presentation/mastertheme) { get; } | Gibt das Masterthema zurück. Nur-Lese [`IMasterTheme`](../../aspose.slides.theme/imastertheme). |
| [NotesSize](../../aspose.slides/presentation/notessize) { get; } | Gibt das Objekt der Notizgrößefolie zurück. Nur-Lese [`INotesSize`](../inotessize). |
| [ProtectionManager](../../aspose.slides/presentation/protectionmanager) { get; } | Gibt den Manager der Berechtigungen für diese Präsentation zurück. Nur-Lese [`IProtectionManager`](../iprotectionmanager). |
| [Sections](../../aspose.slides/presentation/sections) { get; } | Gibt eine Liste aller Folienabschnitte zurück, die in der Präsentation definiert sind. Nur-Lese [`ISectionCollection`](../isectioncollection). |
| [Slides](../../aspose.slides/presentation/slides) { get; } | Gibt eine Liste aller Folien zurück, die in der Präsentation definiert sind. Nur-Lese [`ISlideCollection`](../islidecollection). |
| [SlideShowSettings](../../aspose.slides/presentation/slideshowsettings) { get; } | Gibt die Diashow-Einstellungen für die Präsentation zurück. |
| [SlideSize](../../aspose.slides/presentation/slidesize) { get; } | Gibt das Foliengrößenobjekt zurück. Nur-Lese [`ISlideSize`](../islidesize). |
| [SourceFormat](../../aspose.slides/presentation/sourceformat) { get; } | Gibt Informationen darüber zurück, aus welchem Format die Präsentation geladen wurde. Nur-Lese [`SourceFormat`](../sourceformat). |
| [VbaProject](../../aspose.slides/presentation/vbaproject) { get; set; } | Gibt das VBA-Projekt mit Präsentationsmakros zurück oder setzt es. Lese-/Schreibzugriff [`IVbaProject`](../../aspose.slides.vba/ivbaproject). |
| [Videos](../../aspose.slides/presentation/videos) { get; } | Gibt die Sammlung aller eingebetteten Videodateien in der Präsentation zurück. Nur-Lese [`IVideoCollection`](../ivideocollection). |
| [ViewProperties](../../aspose.slides/presentation/viewproperties) { get; } | Gibt die präsentierenweiten Ansichtseigenschaften zurück. Nur-Lese [`IViewProperties`](../iviewproperties). |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [Dispose](../../aspose.slides/presentation/dispose)() | Gibt alle Ressourcen frei, die von diesem Präsentationsobjekt verwendet werden. |
| [GetImages](../../aspose.slides/presentation/getimages#getimages)(IRenderingOptions) | Gibt ein Image-Objekt für alle Folien einer Präsentation zurück. |
| [GetImages](../../aspose.slides/presentation/getimages#getimages_1)(IRenderingOptions, int[]) | Gibt ein Thumbnail-Image-Objekt für die angegebenen Folien einer Präsentation zurück. |
| [GetImages](../../aspose.slides/presentation/getimages#getimages_5)(IRenderingOptions, Size) | Gibt ein Thumbnail-Image-Objekt für alle Folien einer Präsentation mit der angegebenen Größe zurück. |
| [GetImages](../../aspose.slides/presentation/getimages#getimages_4)(IRenderingOptions, float, float) | Gibt ein Thumbnail-Image-Objekt für alle Folien einer Präsentation mit benutzerdefiniertem Skalieren zurück. |
| [GetImages](../../aspose.slides/presentation/getimages#getimages_3)(IRenderingOptions, int[], Size) | Gibt ein Thumbnail-Image-Objekt für die angegebenen Folien einer Präsentation mit der angegebenen Größe zurück. |
| [GetImages](../../aspose.slides/presentation/getimages#getimages_2)(IRenderingOptions, int[], float, float) | Gibt ein Thumbnail-Image-Objekt für die angegebenen Folien einer Präsentation mit benutzerdefiniertem Skalieren zurück. |
| [GetSlideById](../../aspose.slides/presentation/getslidebyid)(uint) | Gibt eine Folie, MasterSlide oder LayoutSlide nach Id zurück. |
| [HighlightRegex](../../aspose.slides/presentation/highlightregex)(Regex, Color, IFindResultCallback) | Hebt alle Übereinstimmungen des regulären Ausdrucks mit der angegebenen Farbe hervor. |
| [HighlightText](../../aspose.slides/presentation/highlighttext#highlighttext)(string, Color) | Hebt alle Übereinstimmungen des Beispieltextes mit der angegebenen Farbe hervor. |
| [HighlightText](../../aspose.slides/presentation/highlighttext#highlighttext_1)(string, Color, ITextSearchOptions, IFindResultCallback) | Hebt alle Übereinstimmungen des Beispieltextes mit der angegebenen Farbe hervor. |
| [JoinPortionsWithSameFormatting](../../aspose.slides/presentation/joinportionswithsameformatting)() | Fügt Absätze mit der gleichen Formatierung in allen akzeptablen Formen in allen Folien zusammen. |
| [ReplaceRegex](../../aspose.slides/presentation/replaceregex)(Regex, string, IFindResultCallback) | Ersetzt alle Übereinstimmungen des regulären Ausdrucks mit der angegebenen Zeichenfolge. |
| [ReplaceText](../../aspose.slides/presentation/replacetext)(string, string, ITextSearchOptions, IFindResultCallback) | Ersetzt alle Vorkommen des angegebenen Textes durch einen anderen angegebenen Text. |
| [Save](../../aspose.slides/presentation/save#save)(IXamlOptions) | Speichert alle Folien einer Präsentation in einer Menge von Dateien, die die XAML-Markup darstellen. |
| [Save](../../aspose.slides/presentation/save#save_1)(Stream, SaveFormat) | Speichert alle Folien einer Präsentation in einem Stream im angegebenen Format. |
| [Save](../../aspose.slides/presentation/save#save_5)(string, SaveFormat) | Speichert alle Folien einer Präsentation in einer Datei im angegebenen Format. |
| [Save](../../aspose.slides/presentation/save#save_3)(Stream, int[], SaveFormat) | Speichert die angegebenen Folien einer Präsentation in einem Stream im angegebenen Format mit Seitenzahlbeibehaltung. |
| [Save](../../aspose.slides/presentation/save#save_2)(Stream, SaveFormat, ISaveOptions) | Speichert alle Folien einer Präsentation in einem Stream im angegebenen Format und mit zusätzlichen Optionen. |
| [Save](../../aspose.slides/presentation/save#save_7)(string, int[], SaveFormat) | Speichert die angegebenen Folien einer Präsentation in einer Datei im angegebenen Format mit Seitenzahlbeibehaltung. |
| [Save](../../aspose.slides/presentation/save#save_6)(string, SaveFormat, ISaveOptions) |  |
| [Save](../../aspose.slides/presentation/save#save_4)(Stream, int[], SaveFormat, ISaveOptions) | Speichert die angegebenen Folien einer Präsentation in einem Stream im angegebenen Format mit Seitenzahlbeibehaltung. |
| [Save](../../aspose.slides/presentation/save#save_8)(string, int[], SaveFormat, ISaveOptions) | Speichert die angegebenen Folien einer Präsentation in einer Datei im angegebenen Format mit Seitenzahlbeibehaltung. |

### Beispiele

Das folgende Beispiel zeigt, wie man eine PowerPoint-Präsentation erstellt.

```csharp
[C#]
// Erstellen Sie ein Präsentationsobjekt, das eine Präsentationsdatei darstellt
using (Presentation presentation = new Presentation())
{
    // Holen Sie sich die erste Folie
    ISlide slide = presentation.Slides[0];
    // Fügen Sie eine Autoform vom Typ Linie hinzu
    slide.Shapes.AddAutoShape(ShapeType.Line, 50, 150, 300, 0);
	// Speichern Sie die Präsentationsdatei.
    presentation.Save("NewPresentation_out.pptx", SaveFormat.Pptx);
}
```

Das folgende Beispiel zeigt, wie man eine Präsentation öffnet und speichert.

```csharp
[C#]
// Laden Sie eine beliebige unterstützte Datei in die Präsentation, z. B. ppt, pptx, odp usw.
using (Presentation presentation = new Presentation("Sample.odp"))
{
	// Speichern Sie die Präsentationsdatei.
	presentation.Save("OutputPresenation.pptx", SaveFormat.Pptx);
}
```

### Siehe auch

* interface [IPresentation](../ipresentation)
* namespace [Aspose.Slides](../../aspose.slides)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->