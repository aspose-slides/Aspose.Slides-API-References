---
title: IPresentation
second_title: Aspose.Slides für .NET API-Referenz
description: Präsentationsdokument
type: docs
weight: 6550
url: /de/aspose.slides/ipresentation/
---

## IPresentation-Schnittstelle

Präsentationsdokument

```csharp
public interface IPresentation : IDisposable, IPresentationComponent
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [AllCustomXmlParts](../../aspose.slides/ipresentation/allcustomxmlparts) { get; } | Gibt alle benutzerdefinierten Daten in der Präsentation zurück. Nur Lesezugriff [`ICustomXmlPart`](../icustomxmlpart)[]. |
| [AsIDisposable](../../aspose.slides/ipresentation/asidisposable) { get; } | Gibt die IDisposable-Schnittstelle zurück. Nur Lesezugriff IDisposable. |
| [AsIPresentationComponent](../../aspose.slides/ipresentation/asipresentationcomponent) { get; } | Ermöglicht den Zugriff auf die Basis-IPresentationComponent-Schnittstelle. Nur Lesezugriff [`IPresentationComponent`](../ipresentationcomponent). |
| [Audios](../../aspose.slides/ipresentation/audios) { get; } | Gibt die Sammlung aller eingebetteten Audiodateien in der Präsentation zurück. Nur Lesezugriff [`IAudioCollection`](../iaudiocollection). |
| [CommentAuthors](../../aspose.slides/ipresentation/commentauthors) { get; } | Gibt die Sammlung der Autoren von Kommentaren zurück. Nur Lesezugriff [`ICommentAuthorCollection`](../icommentauthorcollection). |
| [CurrentDateTime](../../aspose.slides/ipresentation/currentdatetime) { get; set; } | Gibt das Datum und die Uhrzeit zurück oder setzt sie, die den Inhalt der Datumsfeld ersetzen wird. Standardmäßig die Zeit dieser Präsentationsobjekterstellung. Lese-/Schreibzugriff DateTime. |
| [CustomData](../../aspose.slides/ipresentation/customdata) { get; } | Gibt die benutzerdefinierten Daten der Präsentation zurück. Nur Lesezugriff [`ICustomData`](../icustomdata). |
| [DefaultTextStyle](../../aspose.slides/ipresentation/defaulttextstyle) { get; } | Gibt den Standardtextstil für Formen zurück. Nur Lesezugriff [`ITextStyle`](../itextstyle). |
| [DigitalSignatures](../../aspose.slides/ipresentation/digitalsignatures) { get; } | Gibt die Sammlung der Signaturen zurück, die verwendet werden, um die Präsentation zu unterzeichnen. Nur Lesezugriff [`IDigitalSignatureCollection`](../idigitalsignaturecollection). |
| [DocumentProperties](../../aspose.slides/ipresentation/documentproperties) { get; } | Gibt das DocumentProperties-Objekt zurück, das Standard- und benutzerdefinierte Dokumenteigenschaften enthält. Nur Lesezugriff [`IDocumentProperties`](../idocumentproperties). |
| [FirstSlideNumber](../../aspose.slides/ipresentation/firstslidenumber) { get; set; } | Stellt die erste Foliennummer in der Präsentation dar. Lese-/Schreibzugriff Int32. |
| [FontsManager](../../aspose.slides/ipresentation/fontsmanager) { get; } | Gibt den Schriftartenmanager zurück. Nur Lesezugriff [`IFontsManager`](../ifontsmanager). |
| [HeaderFooterManager](../../aspose.slides/ipresentation/headerfootermanager) { get; } | Gibt den HeaderFooter-Manager der Präsentation zurück. Nur Lesezugriff [`IPresentationHeaderFooterManager`](../ipresentationheaderfootermanager). |
| [HyperlinkQueries](../../aspose.slides/ipresentation/hyperlinkqueries) { get; } | Bietet einfachen Zugriff auf alle Hyperlinks, die in allen Präsentationsfolien enthalten sind (nicht in Master-, Layout- oder Notizenfolien). Nur Lesezugriff [`IHyperlinkQueries`](../ihyperlinkqueries). |
| [Images](../../aspose.slides/ipresentation/images) { get; } | Gibt die Sammlung aller Bilder in der Präsentation zurück. Nur Lesezugriff [`IImageCollection`](../iimagecollection). |
| [LayoutSlides](../../aspose.slides/ipresentation/layoutslides) { get; } | Gibt eine Liste aller Layoutfolien zurück, die in der Präsentation definiert sind. Nur Lesezugriff [`IGlobalLayoutSlideCollection`](../igloballayoutslidecollection). |
| [MasterHandoutSlideManager](../../aspose.slides/ipresentation/masterhandoutslidemanager) { get; } | Gibt den Handout-Master-Manager zurück. Nur Lesezugriff [`IMasterHandoutSlideManager`](../imasterhandoutslidemanager). |
| [MasterNotesSlideManager](../../aspose.slides/ipresentation/masternotesslidemanager) { get; } | Gibt den Notizen-Master-Manager zurück. Nur Lesezugriff [`IMasterNotesSlideManager`](../imasternotesslidemanager). |
| [Masters](../../aspose.slides/ipresentation/masters) { get; } | Gibt eine Liste aller Masterfolien zurück, die in der Präsentation definiert sind. Nur Lesezugriff [`IMasterSlideCollection`](../imasterslidecollection). |
| [MasterTheme](../../aspose.slides/ipresentation/mastertheme) { get; } | Gibt das Master-Theme der Präsentation zurück. Nur Lesezugriff [`IMasterTheme`](../../aspose.slides.theme/imastertheme). |
| [NotesSize](../../aspose.slides/ipresentation/notessize) { get; } | Gibt das Notizfolien-Größenobjekt zurück. Nur Lesezugriff [`INotesSize`](../inotessize). |
| [ProtectionManager](../../aspose.slides/ipresentation/protectionmanager) { get; } | Ermöglicht den Zugriff auf den Manager der Berechtigungen für diese Präsentation. Nur Lesezugriff [`IProtectionManager`](../iprotectionmanager). |
| [Sections](../../aspose.slides/ipresentation/sections) { get; } | Gibt eine Liste aller Folienabschnitte zurück, die in der Präsentation definiert sind. Nur Lesezugriff [`ISectionCollection`](../isectioncollection). |
| [Slides](../../aspose.slides/ipresentation/slides) { get; } | Gibt eine Liste aller Folien zurück, die in der Präsentation definiert sind. Nur Lesezugriff [`ISlideCollection`](../islidecollection). |
| [SlideSize](../../aspose.slides/ipresentation/slidesize) { get; } | Gibt das Foliengrößenobjekt zurück. Nur Lesezugriff [`ISlideSize`](../islidesize). |
| [SourceFormat](../../aspose.slides/ipresentation/sourceformat) { get; } | Gibt Informationen darüber zurück, aus welchem Format die Präsentation geladen wurde. Nur Lesezugriff [`SourceFormat`](./sourceformat). |
| [VbaProject](../../aspose.slides/ipresentation/vbaproject) { get; set; } | Ermöglicht den Zugriff auf das VBA-Projekt mit Präsentationsmakros. Lese-/Schreibzugriff [`IVbaProject`](../../aspose.slides.vba/ivbaproject). |
| [Videos](../../aspose.slides/ipresentation/videos) { get; } | Gibt die Sammlung aller eingebetteten Videodateien in der Präsentation zurück. Nur Lesezugriff [`IVideoCollection`](../ivideocollection). |
| [ViewProperties](../../aspose.slides/ipresentation/viewproperties) { get; } | Ermöglicht den Zugriff auf die präsentationsweiten Ansichtseigenschaften. Nur Lesezugriff [`IViewProperties`](../iviewproperties). |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [GetImages](../../aspose.slides/ipresentation/getimages#getimages)(IRenderingOptions) | Gibt ein Thumbnail-Bildobjekt für alle Folien einer Präsentation zurück. |
| [GetImages](../../aspose.slides/ipresentation/getimages#getimages_1)(IRenderingOptions, int[]) | Gibt ein Thumbnail-Bitmap-Objekt für bestimmte Folien einer Präsentation zurück. |
| [GetImages](../../aspose.slides/ipresentation/getimages#getimages_5)(IRenderingOptions, Size) | Gibt ein Thumbnail-Bildobjekt für alle Folien einer Präsentation mit angegebener Größe zurück. |
| [GetImages](../../aspose.slides/ipresentation/getimages#getimages_4)(IRenderingOptions, float, float) | Gibt ein Thumbnail-Bildobjekt für alle Folien einer Präsentation mit benutzerdefinierter Skalierung zurück. |
| [GetImages](../../aspose.slides/ipresentation/getimages#getimages_3)(IRenderingOptions, int[], Size) | Gibt ein Thumbnail-Bildobjekt für bestimmte Folien einer Präsentation mit angegebener Größe zurück. |
| [GetImages](../../aspose.slides/ipresentation/getimages#getimages_2)(IRenderingOptions, int[], float, float) | Gibt ein Thumbnail-Bildobjekt für bestimmte Folien einer Präsentation mit benutzerdefinierter Skalierung zurück. |
| [GetSlideById](../../aspose.slides/ipresentation/getslidebyid)(uint) | Gibt eine Folie, MasterFolie oder LayoutFolie nach ID zurück. |
| [HighlightRegex](../../aspose.slides/ipresentation/highlightregex)(Regex, Color, IFindResultCallback) | Hebt alle Übereinstimmungen des regulären Ausdrucks mit der angegebenen Farbe hervor. |
| [HighlightText](../../aspose.slides/ipresentation/highlighttext#highlighttext)(string, Color) | Hebt alle Übereinstimmungen des Beispieltextes mit der angegebenen Farbe hervor. |
| [HighlightText](../../aspose.slides/ipresentation/highlighttext#highlighttext_1)(string, Color, ITextSearchOptions, IFindResultCallback) | Hebt alle Übereinstimmungen des Beispieltextes mit der angegebenen Farbe hervor. |
| [JoinPortionsWithSameFormatting](../../aspose.slides/ipresentation/joinportionswithsameformatting)() | Verbindet Textabschnitte mit gleichem Format in allen Absätzen in allen akzeptablen Formen in allen Folien. |
| [ReplaceRegex](../../aspose.slides/ipresentation/replaceregex)(Regex, string, IFindResultCallback) | Ersetzt alle Übereinstimmungen des regulären Ausdrucks durch den angegebenen String. |
| [ReplaceText](../../aspose.slides/ipresentation/replacetext)(string, string, ITextSearchOptions, IFindResultCallback) | Ersetzt alle Vorkommen des angegebenen Textes durch einen anderen angegebenen Text. |
| [Save](../../aspose.slides/ipresentation/save#save)(IXamlOptions) | Speichert alle Folien einer Präsentation in einer Reihe von Dateien, die XAML-Markup darstellen. |
| [Save](../../aspose.slides/ipresentation/save#save_1)(Stream, SaveFormat) | Speichert alle Folien einer Präsentation in einem Stream im angegebenen Format. |
| [Save](../../aspose.slides/ipresentation/save#save_5)(string, SaveFormat) | Speichert alle Folien einer Präsentation in einer Datei im angegebenen Format. |
| [Save](../../aspose.slides/ipresentation/save#save_3)(Stream, int[], SaveFormat) | Speichert bestimmte Folien einer Präsentation in einem Stream im angegebenen Format. |
| [Save](../../aspose.slides/ipresentation/save#save_2)(Stream, SaveFormat, ISaveOptions) | Speichert alle Folien einer Präsentation in einem Stream im angegebenen Format und mit zusätzlichen Optionen. |
| [Save](../../aspose.slides/ipresentation/save#save_7)(string, int[], SaveFormat) | Speichert bestimmte Folien einer Präsentation in einer Datei im angegebenen Format. |
| [Save](../../aspose.slides/ipresentation/save#save_6)(string, SaveFormat, ISaveOptions) | Speichert alle Folien einer Präsentation in einer Datei im angegebenen Format und mit zusätzlichen Optionen. |
| [Save](../../aspose.slides/ipresentation/save#save_4)(Stream, int[], SaveFormat, ISaveOptions) | Speichert bestimmte Folien einer Präsentation in einem Stream im angegebenen Format. |
| [Save](../../aspose.slides/ipresentation/save#save_8)(string, int[], SaveFormat, ISaveOptions) | Speichert bestimmte Folien einer Präsentation in einer Datei im angegebenen Format. |

### Siehe auch

* Schnittstelle [IPresentationComponent](../ipresentationcomponent)
* Namespace [Aspose.Slides](../../aspose.slides)
* Assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->