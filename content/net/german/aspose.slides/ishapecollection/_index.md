---
title: IShapeCollection
second_title: Aspose.Sildes für .NET API-Referenz
description: Stellt eine Sammlung von Formen dar.
type: docs
weight: 7000
url: /de/aspose.slides/ishapecollection/
---
## IShapeCollection Schnittstelle

Stellt eine Sammlung von Formen dar.

```csharp
public interface IShapeCollection : IGenericCollection<IShape>
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [Item](../../aspose.slides/ishapecollection/item) { get; } | Ruft das Element am angegebenen Index ab. Nur lesbar [`IShape`](../ishape). |
| [ParentGroup](../../aspose.slides/ishapecollection/parentgroup) { get; } | Ruft das übergeordnete Gruppenform-Objekt für die Formsammlung ab. Nur lesbar [`IGroupShape`](../igroupshape). |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [AddAudioFrameCD](../../aspose.slides/ishapecollection/addaudioframecd)(float, float, float, float) | Erstellt einen neuen Audio-Frame, der mit einer CD-Spur verknüpft ist, und fügt ihn am Ende der Formsammlung hinzu. |
| [AddAudioFrameEmbedded](../../aspose.slides/ishapecollection/addaudioframeembedded#addaudioframeembedded)(float, float, float, float, IAudio) | Erstellt einen neuen Audio-Frame und fügt ihn am Ende der Formsammlung hinzu, wobei ein vorhandenes Audio-Objekt aus der Presentation.Audios-Liste verwendet wird. |
| [AddAudioFrameEmbedded](../../aspose.slides/ishapecollection/addaudioframeembedded#addaudioframeembedded_1)(float, float, float, float, Stream) | Erstellt einen neuen Audio-Frame mit einer eingebetteten WAV-Datei und fügt ihn am Ende der Formsammlung hinzu. Der eingebettete Audio-Clip wird zur Presentation.Audios-Sammlung hinzugefügt. |
| [AddAudioFrameLinked](../../aspose.slides/ishapecollection/addaudioframelinked)(float, float, float, float, string) | Erstellt einen neuen Audio-Frame, der mit einer externen Audiodatei verknüpft ist, und fügt ihn am Ende der Formsammlung hinzu. |
| [AddAutoShape](../../aspose.slides/ishapecollection/addautoshape#addautoshape)(ShapeType, float, float, float, float) | Erstellt eine neue Autoform mit Standardformatierung und fügt sie am Ende der Formsammlung hinzu. |
| [AddAutoShape](../../aspose.slides/ishapecollection/addautoshape#addautoshape_1)(ShapeType, float, float, float, float, bool) | Erstellt eine neue Autoform und fügt sie am Ende der Formsammlung hinzu, wobei optional die Standardvorlagenformatierung verwendet wird. |
| [AddChart](../../aspose.slides/ishapecollection/addchart#addchart)(ChartType, float, float, float, float) | Erstellt ein neues Diagramm, initialisiert es mit Beispieldaten und -einstellungen und fügt es am Ende der Formsammlung hinzu. |
| [AddChart](../../aspose.slides/ishapecollection/addchart#addchart_1)(ChartType, float, float, float, float, bool) | Erstellt ein neues Diagramm, initialisiert es mit Beispieldaten und -einstellungen und fügt es am Ende der Formsammlung hinzu. |
| [AddClone](../../aspose.slides/ishapecollection/addclone#addclone)(IShape) | Erstellt eine Kopie der angegebenen Form und fügt sie am Ende der Formsammlung hinzu. Die geklonte Form behält die Position und Größe des Originals bei. |
| [AddClone](../../aspose.slides/ishapecollection/addclone#addclone_1)(IShape, float, float) | Erstellt eine Kopie der angegebenen Form und fügt sie am Ende der Formsammlung hinzu. Die neue Form behält Breite und Höhe der *sourceShape* bei. |
| [AddClone](../../aspose.slides/ishapecollection/addclone#addclone_2)(IShape, float, float, float, float) | Erstellt eine Kopie der angegebenen Form und fügt sie am Ende der Formsammlung hinzu. |
| [AddConnector](../../aspose.slides/ishapecollection/addconnector#addconnector)(ShapeType, float, float, float, float) | Erstellt eine neue Verbindungslinie mit Standardvorlagen-Styling und fügt sie am Ende der Formsammlung hinzu. |
| [AddConnector](../../aspose.slides/ishapecollection/addconnector#addconnector_1)(ShapeType, float, float, float, float, bool) | Erstellt eine neue Verbindungslinie und fügt sie am Ende der Formsammlung hinzu, optional mit Standardvorlagen-Styling. |
| [AddGroupShape](../../aspose.slides/ishapecollection/addgroupshape#addgroupshape)() | Erstellt eine neue leere Gruppierungsform und fügt sie am Ende der Formsammlung hinzu. Der Rahmen der Gruppe passt sich automatisch an die hinzugefügten Formen an. |
| [AddGroupShape](../../aspose.slides/ishapecollection/addgroupshape#addgroupshape_1)(ISvgImage, float, float, float, float) | Erstellt eine neue Gruppierungsform, konvertiert das angegebene SVG-Bild in einzelne Formen und fügt die entstehende Gruppe am Ende der Formsammlung hinzu. |
| [AddMathShape](../../aspose.slides/ishapecollection/addmathshape)(float, float, float, float) | Erstellt eine neue rechteckige Autoform für mathematischen Inhalt und fügt sie am Ende der Formsammlung hinzu. |
| [AddOleObjectFrame](../../aspose.slides/ishapecollection/addoleobjectframe#addoleobjectframe)(float, float, float, float, IOleEmbeddedDataInfo) | Erstellt einen neuen OLE-Objekt-Frame und fügt ihn am Ende der Formsammlung hinzu. |
| [AddOleObjectFrame](../../aspose.slides/ishapecollection/addoleobjectframe#addoleobjectframe_1)(float, float, float, float, string, string) | Erstellt einen neuen OLE-Objekt-Frame und fügt ihn am Ende der Formsammlung hinzu. |
| [AddPictureFrame](../../aspose.slides/ishapecollection/addpictureframe)(ShapeType, float, float, float, float, IPPImage) | Erstellt einen neuen Bild-Frame, der das angegebene Bild enthält, und fügt ihn am Ende der Formsammlung hinzu. |
| [AddSectionZoomFrame](../../aspose.slides/ishapecollection/addsectionzoomframe#addsectionzoomframe)(float, float, float, float, ISection) | Erstellt einen neuen Section-Zoom-Frame und fügt ihn am Ende der Formsammlung hinzu. |
| [AddSectionZoomFrame](../../aspose.slides/ishapecollection/addsectionzoomframe#addsectionzoomframe_1)(float, float, float, float, ISection, IPPImage) | Erstellt einen neuen Section-Zoom-Frame mit einem vordefinierten Bild und fügt ihn am Ende der Formsammlung hinzu. |
| [AddSmartArt](../../aspose.slides/ishapecollection/addsmartart)(float, float, float, float, SmartArtLayoutType) | Erstellt ein SmartArt-Diagramm und fügt es am Ende der Formsammlung hinzu. |
| [AddSummaryZoomFrame](../../aspose.slides/ishapecollection/addsummaryzoomframe)(float, float, float, float) | Erstellt einen neuen Summary-Zoom-Frame und fügt ihn am Ende der Formsammlung hinzu. |
| [AddTable](../../aspose.slides/ishapecollection/addtable)(float, float, double[], double[]) | Erstellt eine neue Tabelle und fügt sie am Ende der Formsammlung hinzu. |
| [AddVideoFrame](../../aspose.slides/ishapecollection/addvideoframe#addvideoframe)(float, float, float, float, IVideo) | Erstellt einen neuen Video-Frame und fügt ihn am Ende der Formsammlung hinzu. |
| [AddVideoFrame](../../aspose.slides/ishapecollection/addvideoframe#addvideoframe_1)(float, float, float, float, string) | Erstellt einen neuen Video-Frame und fügt ihn am Ende der Formsammlung hinzu. |
| [AddZoomFrame](../../aspose.slides/ishapecollection/addzoomframe#addzoomframe)(float, float, float, float, ISlide) | Erstellt einen neuen Zoom-Frame und fügt ihn am Ende der Formsammlung hinzu. |
| [AddZoomFrame](../../aspose.slides/ishapecollection/addzoomframe#addzoomframe_1)(float, float, float, float, ISlide, IPPImage) | Erstellt einen neuen Zoom-Frame und fügt ihn am Ende der Formsammlung hinzu. |
| [Clear](../../aspose.slides/ishapecollection/clear)() | Entfernt alle Formen aus der Formsammlung. |
| [IndexOf](../../aspose.slides/ishapecollection/indexof)(IShape) | Gibt den nullbasierten Index des ersten Vorkommens der angegebenen Form in der Sammlung zurück. |
| [InsertAudioFrameCD](../../aspose.slides/ishapecollection/insertaudioframecd)(int, float, float, float, float) | Erstellt einen neuen Audio-Frame, der mit einer CD-Spur verknüpft ist, und fügt ihn an der angegebenen Position in die Formsammlung ein. |
| [InsertAudioFrameEmbedded](../../aspose.slides/ishapecollection/insertaudioframeembedded#insertaudioframeembedded)(int, float, float, float, float, IAudio) | Erstellt einen neuen Audio-Frame und fügt ihn an der angegebenen Position in die Formsammlung ein, wobei ein vorhandenes Audio-Objekt aus der Presentation.Audios-Liste verwendet wird. |
| [InsertAudioFrameEmbedded](../../aspose.slides/ishapecollection/insertaudioframeembedded#insertaudioframeembedded_1)(int, float, float, float, float, Stream) | Erstellt einen neuen Audio-Frame mit einer eingebetteten WAV-Datei und fügt ihn an der angegebenen Position in die Formsammlung ein. Der eingebettete Audio-Clip wird zur Presentation.Audios-Sammlung hinzugefügt. |
| [InsertAudioFrameLinked](../../aspose.slides/ishapecollection/insertaudioframelinked)(int, float, float, float, float, string) | Erstellt einen neuen Audio-Frame, der mit einer externen Audiodatei verknüpft ist, und fügt ihn an der angegebenen Position in die Formsammlung ein. |
| [InsertAutoShape](../../aspose.slides/ishapecollection/insertautoshape#insertautoshape)(int, ShapeType, float, float, float, float) | Erstellt eine neue Autoform und fügt sie an der angegebenen Position in die Formsammlung ein, wobei die Standardvorlagenformatierung angewendet wird. |
| [InsertAutoShape](../../aspose.slides/ishapecollection/insertautoshape#insertautoshape_1)(int, ShapeType, float, float, float, float, bool) | Erstellt eine neue Autoform und fügt sie an der angegebenen Position in die Formsammlung ein, optional mit Standardvorlagen-Styling. |
| [InsertChart](../../aspose.slides/ishapecollection/insertchart#insertchart)(ChartType, float, float, float, float, int) | Erstellt ein neues Diagramm, initialisiert es mit Beispieldaten und -einstellungen und fügt es an der angegebenen Position in die Formsammlung ein. |
| [InsertChart](../../aspose.slides/ishapecollection/insertchart#insertchart_1)(ChartType, float, float, float, float, int, bool) | Erstellt ein neues Diagramm, initialisiert es mit Beispieldaten und -einstellungen und fügt es an der angegebenen Position in die Formsammlung ein. |
| [InsertClone](../../aspose.slides/ishapecollection/insertclone#insertclone)(int, IShape) | Erstellt eine Kopie der angegebenen Form und fügt sie an der angegebenen Position in die Formsammlung ein. Die geklonte Form behält die Position und Größe des Originals bei. |
| [InsertClone](../../aspose.slides/ishapecollection/insertclone#insertclone_1)(int, IShape, float, float) | Erstellt eine Kopie der angegebenen Form und fügt sie an der angegebenen Position in die Formsammlung ein. Die neue Form behält Breite und Höhe der *sourceShape* bei. |
| [InsertClone](../../aspose.slides/ishapecollection/insertclone#insertclone_2)(int, IShape, float, float, float, float) | Erstellt eine Kopie der angegebenen Form und fügt sie an der angegebenen Position in die Formsammlung ein. |
| [InsertConnector](../../aspose.slides/ishapecollection/insertconnector#insertconnector)(int, ShapeType, float, float, float, float) | Erstellt eine neue Verbindungslinie und fügt sie an der angegebenen Position in die Formsammlung ein, wobei die Standardvorlagen-Styling angewendet wird. |
| [InsertConnector](../../aspose.slides/ishapecollection/insertconnector#insertconnector_1)(int, ShapeType, float, float, float, float, bool) | Erstellt eine neue Verbindungslinie und fügt sie an der angegebenen Position in die Formsammlung ein, optional mit Standardvorlagen-Styling. |
| [InsertGroupShape](../../aspose.slides/ishapecollection/insertgroupshape)(int) | Erstellt eine neue leere Gruppierungsform und fügt sie an der angegebenen Position in die Formsammlung ein. Der Rahmen der Gruppe passt sich automatisch an die hinzugefügten Formen an. |
| [InsertOleObjectFrame](../../aspose.slides/ishapecollection/insertoleobjectframe#insertoleobjectframe)(int, float, float, float, float, IOleEmbeddedDataInfo) | Erstellt einen neuen OLE-Objekt-Frame und fügt ihn an der angegebenen Position in die Formsammlung ein. |
| [InsertOleObjectFrame](../../aspose.slides/ishapecollection/insertoleobjectframe#insertoleobjectframe_1)(int, float, float, float, float, string, string) | Erstellt einen neuen OLE-Objekt-Frame und fügt ihn an der angegebenen Position in die Formsammlung ein. |
| [InsertPictureFrame](../../aspose.slides/ishapecollection/insertpictureframe)(int, ShapeType, float, float, float, float, IPPImage) | Erstellt einen neuen Bild-Frame, der das angegebene Bild enthält, und fügt ihn an der angegebenen Position in die Formsammlung ein. |
| [InsertSectionZoomFrame](../../aspose.slides/ishapecollection/insertsectionzoomframe#insertsectionzoomframe)(int, float, float, float, float, ISection) | Erstellt einen neuen Section-Zoom-Frame und fügt ihn an der angegebenen Position in die Formsammlung ein. |
| [InsertSectionZoomFrame](../../aspose.slides/ishapecollection/insertsectionzoomframe#insertsectionzoomframe_1)(int, float, float, float, float, ISection, IPPImage) | Erstellt einen neuen Section-Zoom-Frame mit einem vordefinierten Bild und fügt ihn an der angegebenen Position in die Formsammlung ein. |
| [InsertSummaryZoomFrame](../../aspose.slides/ishapecollection/insertsummaryzoomframe)(int, float, float, float, float) | Erstellt einen neuen Summary-Zoom-Frame und fügt ihn an der angegebenen Position in die Formsammlung ein. |
| [InsertTable](../../aspose.slides/ishapecollection/inserttable)(int, float, float, double[], double[]) | Erstellt eine neue Tabelle und fügt sie an der angegebenen Position in die Formsammlung ein. |
| [InsertVideoFrame](../../aspose.slides/ishapecollection/insertvideoframe)(int, float, float, float, float, string) | Erstellt einen neuen Video-Frame und fügt ihn an der angegebenen Position in die Formsammlung ein. |
| [InsertZoomFrame](../../aspose.slides/ishapecollection/insertzoomframe#insertzoomframe)(int, float, float, float, float, ISlide) | Erstellt einen neuen Zoom-Frame und fügt ihn an der angegebenen Position in die Formsammlung ein. |
| [InsertZoomFrame](../../aspose.slides/ishapecollection/insertzoomframe#insertzoomframe_1)(int, float, float, float, float, ISlide, IPPImage) | Erstellt einen neuen Zoom-Frame mit einem vordefinierten Bild und fügt ihn an der angegebenen Position in die Formsammlung ein. |
| [Remove](../../aspose.slides/ishapecollection/remove)(IShape) | Entfernt das erste Vorkommen der angegebenen Form aus der Formsammlung. |
| [RemoveAt](../../aspose.slides/ishapecollection/removeat)(int) | Entfernt die Form an dem angegebenen Index aus der Formsammlung. |
| [Reorder](../../aspose.slides/ishapecollection/reorder#reorder)(int, IShape) | Verschiebt die angegebene Form an eine neue Position innerhalb der Formsammlung. |
| [Reorder](../../aspose.slides/ishapecollection/reorder#reorder_1)(int, params IShape[]) | Verschiebt die angegebenen Formen innerhalb der Formsammlung und platziert sie beginnend ab dem angegebenen Index. |
| [ToArray](../../aspose.slides/ishapecollection/toarray#toarray)() | Erstellt und gibt ein Array zurück, das alle Formen enthält. |
| [ToArray](../../aspose.slides/ishapecollection/toarray#toarray_1)(int, int) | Erstellt und gibt ein Array zurück, das alle Formen im angegebenen Bereich enthält. |

### Siehe auch

* Schnittstelle [IGenericCollection&lt;T&gt;](../igenericcollection-1)
* Schnittstelle [IShape](../ishape)
* Namespace [Aspose.Slides](../../aspose.slides)
* Assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->