---
title: Presentation
second_title: Aspose.Sildes für .NET API-Referenz
description: Stellt eine Microsoft PowerPoint-Präsentation dar.
type: docs
weight: 9590
url: /de/aspose.slides/presentation/
---
## Presentation Klasse

Stellt eine Microsoft PowerPoint-Präsentation dar.

```csharp
public sealed class Presentation : IPresentation
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [Presentation](presentation#constructor)() | Dieser Konstruktor erstellt eine neue Präsentation von Grund auf. Die erstellte Präsentation enthält eine leere Folie. |
| [Presentation](presentation#constructor_1)(LoadOptions) | Dieser Konstruktor erstellt eine neue Präsentation von Grund auf. Die erstellte Präsentation enthält eine leere Folie. |
| [Presentation](presentation#constructor_2)(Stream) | Dieser Konstruktor ist der primäre Mechanismus zum Lesen einer vorhandenen Presentation. |
| [Presentation](presentation#constructor_4)(string) | Dieser Konstruktor erhält einen Quelldateipfad, von dem der Inhalt der Presentation gelesen wird. |
| [Presentation](presentation#constructor_3)(Stream, LoadOptions) | Dieser Konstruktor ist der primäre Mechanismus zum Lesen einer vorhandenen Presentation. |
| [Presentation](presentation#constructor_5)(string, LoadOptions) | Dieser Konstruktor erhält einen Quelldateipfad, von dem der Inhalt der Presentation gelesen wird. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [AllCustomXmlParts](../../aspose.slides/presentation/allcustomxmlparts) { get; } | Gibt alle benutzerdefinierten Daten-Teile in der Präsentation zurück. Nur lesbar [`ICustomXmlPart`](../icustomxmlpart)[]. |
| [Audios](../../aspose.slides/presentation/audios) { get; } | Gibt die Sammlung aller eingebetteten Audiodateien in der Präsentation zurück. Nur lesbar [`IAudioCollection`](../iaudiocollection). |
| [CommentAuthors](../../aspose.slides/presentation/commentauthors) { get; } | Gibt die Sammlung der Kommentarautoren zurück. Nur lesbar [`ICommentAuthorCollection`](../icommentauthorcollection). |
| [CurrentDateTime](../../aspose.slides/presentation/currentdatetime) { get; set; } | Gibt Datum und Uhrzeit zurück oder setzt sie, die den Inhalt von Datums-Zeit-Feldern ersetzen. Standardmäßig die Erstellungszeit dieses Presentation-Objekts. Lesen/Schreiben DateTime. |
| [CustomData](../../aspose.slides/presentation/customdata) { get; } | Gibt die benutzerdefinierten Daten der Präsentation zurück. Nur lesbar [`ICustomData`](../icustomdata). |
| [DefaultTextStyle](../../aspose.slides/presentation/defaulttextstyle) { get; } | Gibt den Standard-Textstil für Shapes zurück. Nur lesbar [`ITextStyle`](../itextstyle). |
| [DigitalSignatures](../../aspose.slides/presentation/digitalsignatures) { get; } | Gibt die Sammlung der Signaturen zurück, die zum Signieren der Präsentation verwendet werden. Nur lesbar [`IDigitalSignatureCollection`](../idigitalsignaturecollection). |
| [DocumentProperties](../../aspose.slides/presentation/documentproperties) { get; } | Gibt das DocumentProperties-Objekt zurück, das Standard- und benutzerdefinierte Dokumenteigenschaften enthält. Nur lesbar [`IDocumentProperties`](../idocumentproperties). |
| [FirstSlideNumber](../../aspose.slides/presentation/firstslidenumber) { get; set; } | Stellt die Nummer der ersten Folie in der Präsentation dar |
| [FontsManager](../../aspose.slides/presentation/fontsmanager) { get; } | Gibt den Font-Manager zurück. Nur lesbar [`IFontsManager`](../ifontsmanager). |
| [HeaderFooterManager](../../aspose.slides/presentation/headerfootermanager) { get; } | Gibt den aktuellen HeaderFooter-Manager zurück. Nur lesbar [`IPresentationHeaderFooterManager`](../ipresentationheaderfootermanager). |
| [HyperlinkQueries](../../aspose.slides/presentation/hyperlinkqueries) { get; } | Bietet einfachen Zugriff auf alle Hyperlinks, die in allen Folien der Präsentation enthalten sind (nicht in Master-, Layout- oder Notizfolien). Nur lesbar [`IHyperlinkQueries`](../ihyperlinkqueries). |
| [Images](../../aspose.slides/presentation/images) { get; } | Gibt die Sammlung aller Bilder in der Präsentation zurück. Nur lesbar [`IImageCollection`](../iimagecollection). |
| [LayoutSlides](../../aspose.slides/presentation/layoutslides) { get; } | Gibt eine Liste aller Layout-Folien zurück, die in der Präsentation definiert sind. Nur lesbar [`IGlobalLayoutSlideCollection`](../igloballayoutslidecollection). |
| [MasterHandoutSlideManager](../../aspose.slides/presentation/masterhandoutslidemanager) { get; } | Gibt den Handout-Master-Manager zurück. Nur lesbar [`IMasterHandoutSlideManager`](../imasterhandoutslidemanager). |
| [MasterNotesSlideManager](../../aspose.slides/presentation/masternotesslidemanager) { get; } | Gibt den Notizen-Master-Manager zurück. Nur lesbar [`IMasterNotesSlideManager`](../imasternotesslidemanager). |
| [Masters](../../aspose.slides/presentation/masters) { get; } | Gibt eine Liste aller Master-Folien zurück, die in der Präsentation definiert sind. Nur lesbar [`IMasterSlideCollection`](../imasterslidecollection). |
| [MasterTheme](../../aspose.slides/presentation/mastertheme) { get; } | Gibt das Master-Theme zurück. Nur lesbar [`IMasterTheme`](../../aspose.slides.theme/imastertheme). |
| [NotesSize](../../aspose.slides/presentation/notessize) { get; } | Gibt das Notizen-Folien-Größenobjekt zurück. Nur lesbar [`INotesSize`](../inotessize). |
| [ProtectionManager](../../aspose.slides/presentation/protectionmanager) { get; } | Gibt den Manager für die Berechtigungen dieser Präsentation zurück. Nur lesbar [`IProtectionManager`](../iprotectionmanager). |
| [Sections](../../aspose.slides/presentation/sections) { get; } | Gibt eine Liste aller Folienabschnitte zurück, die in der Präsentation definiert sind. Nur lesbar [`ISectionCollection`](../isectioncollection). |
| [SensitivityLabels](../../aspose.slides/presentation/sensitivitylabels) { get; } | Gibt die Sammlung der Sensitivitäts-Labels zurück, die auf das Präsentationsdokument angewendet wurden. Nur lesbar [`ISensitivityLabelCollection`](../isensitivitylabelcollection). |
| [Slides](../../aspose.slides/presentation/slides) { get; } | Gibt eine Liste aller Folien zurück, die in der Präsentation definiert sind. Nur lesbar [`ISlideCollection`](../islidecollection). |
| [SlideShowSettings](../../aspose.slides/presentation/slideshowsettings) { get; } | Gibt die Einstellungen der Bildschirmpräsentation für die Präsentation zurück. |
| [SlideSize](../../aspose.slides/presentation/slidesize) { get; } | Gibt das Folien-Größenobjekt zurück. Nur lesbar [`ISlideSize`](../islidesize). |
| [SourceFormat](../../aspose.slides/presentation/sourceformat) { get; } | Gibt Informationen darüber zurück, aus welchem Format die Präsentation geladen wurde. Nur lesbar [`SourceFormat`](../sourceformat). |
| [VbaProject](../../aspose.slides/presentation/vbaproject) { get; set; } | Gibt das VBA-Projekt mit Präsentations-Makros zurück oder setzt es. Lesen/Schreiben [`IVbaProject`](../../aspose.slides.vba/ivbaproject). |
| [Videos](../../aspose.slides/presentation/videos) { get; } | Gibt die Sammlung aller eingebetteten Videodateien in der Präsentation zurück. Nur lesbar [`IVideoCollection`](../ivideocollection). |
| [ViewProperties](../../aspose.slides/presentation/viewproperties) { get; } | Gibt die Präsentations-weiten Ansichtseigenschaften zurück. Nur lesbar [`IViewProperties`](../iviewproperties). |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [Dispose](../../aspose.slides/presentation/dispose)() | Gibt alle von diesem Presentation-Objekt genutzten Ressourcen frei. |
| [GetImages](../../aspose.slides/presentation/getimages#getimages)(IRenderingOptions) | Gibt Bild-Objekte für alle Folien einer Präsentation zurück. |
| [GetImages](../../aspose.slides/presentation/getimages#getimages_1)(IRenderingOptions, int[]) | Gibt Thumbnail-Bild-Objekte für die angegebenen Folien einer Präsentation zurück. |
| [GetImages](../../aspose.slides/presentation/getimages#getimages_5)(IRenderingOptions, Size) | Gibt Thumbnail-Bild-Objekte für alle Folien einer Präsentation mit der angegebenen Größe zurück. |
| [GetImages](../../aspose.slides/presentation/getimages#getimages_4)(IRenderingOptions, float, float) | Gibt Thumbnail-Bild-Objekte für alle Folien einer Präsentation mit benutzerdefinierter Skalierung zurück. |
| [GetImages](../../aspose.slides/presentation/getimages#getimages_3)(IRenderingOptions, int[], Size) | Gibt Thumbnail-Bild-Objekte für die angegebenen Folien einer Präsentation mit der angegebenen Größe zurück. |
| [GetImages](../../aspose.slides/presentation/getimages#getimages_2)(IRenderingOptions, int[], float, float) | Gibt Thumbnail-Bild-Objekte für die angegebenen Folien einer Präsentation mit benutzerdefinierter Skalierung zurück. |
| [GetSlideById](../../aspose.slides/presentation/getslidebyid)(uint) | Gibt eine Slide, MasterSlide oder LayoutSlide anhand der Id zurück. |
| [HighlightRegex](../../aspose.slides/presentation/highlightregex)(Regex, Color, IFindResultCallback) | Hebt alle Treffer des regulären Ausdrucks mit der angegebenen Farbe hervor. |
| [HighlightText](../../aspose.slides/presentation/highlighttext#highlighttext)(string, Color) | Hebt alle Treffer des Beispieltextes mit der angegebenen Farbe hervor. |
| [HighlightText](../../aspose.slides/presentation/highlighttext#highlighttext_1)(string, Color, ITextSearchOptions, IFindResultCallback) | Hebt alle Treffer des Beispieltextes mit der angegebenen Farbe hervor. |
| [JoinPortionsWithSameFormatting](../../aspose.slides/presentation/joinportionswithsameformatting)() | Führt Lauftext-Abschnitte mit gleicher Formatierung in allen Absätzen aller geeigneten Shapes in allen Folien zusammen. |
| [ReplaceRegex](../../aspose.slides/presentation/replaceregex)(Regex, string, IFindResultCallback) | Ersetzt alle Treffer des regulären Ausdrucks durch die angegebene Zeichenkette. |
| [ReplaceText](../../aspose.slides/presentation/replacetext)(string, string, ITextSearchOptions, IFindResultCallback) | Ersetzt alle Vorkommen des angegebenen Textes durch einen anderen angegebenen Text. |
| [Save](../../aspose.slides/presentation/save#save)(IXamlOptions) | Speichert alle Folien einer Präsentation in einer Menge von Dateien, die XAML-Markup darstellen. |
| [Save](../../aspose.slides/presentation/save#save_1)(Stream, SaveFormat) | Speichert alle Folien einer Präsentation in einen Stream im angegebenen Format. |
| [Save](../../aspose.slides/presentation/save#save_5)(string, SaveFormat) | Speichert alle Folien einer Präsentation in eine Datei mit dem angegebenen Format. |
| [Save](../../aspose.slides/presentation/save#save_3)(Stream, int[], SaveFormat) | Speichert die angegebenen Folien einer Präsentation in einen Stream im angegebenen Format und behält die Seitenzahlen bei. |
| [Save](../../aspose.slides/presentation/save#save_2)(Stream, SaveFormat, ISaveOptions) | Speichert alle Folien einer Präsentation in einen Stream im angegebenen Format und mit zusätzlichen Optionen. |
| [Save](../../aspose.slides/presentation/save#save_7)(string, int[], SaveFormat) | Speichert die angegebenen Folien einer Präsentation in eine Datei mit dem angegebenen Format und behält die Seitenzahlen bei. |
| [Save](../../aspose.slides/presentation/save#save_6)(string, SaveFormat, ISaveOptions) |  |
| [Save](../../aspose.slides/presentation/save#save_4)(Stream, int[], SaveFormat, ISaveOptions) | Speichert die angegebenen Folien einer Präsentation in einen Stream im angegebenen Format und behält die Seitenzahlen bei. |
| [Save](../../aspose.slides/presentation/save#save_8)(string, int[], SaveFormat, ISaveOptions) | Speichert die angegebenen Folien einer Präsentation in eine Datei mit dem angegebenen Format und behält die Seitenzahlen bei. |

### Beispiele

Das folgende Beispiel zeigt, wie man eine PowerPoint-Präsentation erstellt.

```csharp
[C#]
// Instanziiere ein Presentation-Objekt, das eine Präsentationsdatei darstellt
using (Presentation presentation = new Presentation())
{
    // Hole die erste Folie
    ISlide slide = presentation.Slides[0];
    // Füge eine Autoform vom Typ Linie hinzu
    slide.Shapes.AddAutoShape(ShapeType.Line, 50, 150, 300, 0);
	// Speichere die Präsentationsdatei.
    presentation.Save("NewPresentation_out.pptx", SaveFormat.Pptx);
}
```

Das folgende Beispiel zeigt, wie man eine Presentation öffnet und speichert.

```csharp
[C#]
// Lade jede unterstützte Datei in Presentation, z.B. ppt, pptx, odp usw.
using (Presentation presentation = new Presentation("Sample.odp"))
{
	// Speichere die Präsentationsdatei.
	presentation.Save("OutputPresenation.pptx", SaveFormat.Pptx);
}
```

### Siehe auch

* Schnittstelle [IPresentation](../ipresentation)
* Namensraum [Aspose.Slides](../../aspose.slides)
* Assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->