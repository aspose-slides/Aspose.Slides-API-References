---
title: ShapeCollection
second_title: Aspose.Sildes für .NET API-Referenz
description: Stellt eine Sammlung von Formen dar.
type: docs
weight: 9860
url: /de/aspose.slides/shapecollection/
---
## ShapeCollection Klasse

Stellt eine Sammlung von Formen dar.

```csharp
public sealed class ShapeCollection : DomObject<GroupShape>, IShapeCollection
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [Count](../../aspose.slides/shapecollection/count) { get; } | Ruft die tatsächlich in der Sammlung enthaltene Anzahl von Elementen ab. Nur-Lesen Int32. |
| [IsSynchronized](../../aspose.slides/shapecollection/issynchronized) { get; } | Gibt einen Wert zurück, der angibt, ob der Zugriff auf die Sammlung synchronisiert (Thread-sicher) ist. Nur-Lesen Boolean. |
| [Item](../../aspose.slides/shapecollection/item) { get; } | Ruft das Element am angegebenen Index ab. Nur-Lesen [`IShape`](../ishape). |
| [ParentGroup](../../aspose.slides/shapecollection/parentgroup) { get; } | Ruft das übergeordnete Gruppierungsformen-Objekt für die Formen-Sammlung ab. Nur-Lesen [`IGroupShape`](../igroupshape). |
| [SyncRoot](../../aspose.slides/shapecollection/syncroot) { get; } | Gibt die Synchronisationswurzel zurück. Nur-Lesen Object. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [AddAudioFrameCD](../../aspose.slides/shapecollection/addaudioframecd)(float, float, float, float) | Erstellt einen neuen Audio-Frame, der mit einer CD-Spur verknüpft ist, und fügt ihn am Ende der Formen-Sammlung hinzu. |
| [AddAudioFrameEmbedded](../../aspose.slides/shapecollection/addaudioframeembedded#addaudioframeembedded)(float, float, float, float, IAudio) | Erstellt einen neuen Audio-Frame und fügt ihn am Ende der Formen-Sammlung hinzu, wobei ein vorhandenes Audio-Objekt aus der Presentation.Audios-Liste verwendet wird. |
| [AddAudioFrameEmbedded](../../aspose.slides/shapecollection/addaudioframeembedded#addaudioframeembedded_1)(float, float, float, float, Stream) | Erstellt einen neuen Audio-Frame mit einer eingebetteten WAV-Datei und fügt ihn am Ende der Formen-Sammlung hinzu. Der eingebettete Audio-Clip wird zur Presentation.Audios-Sammlung hinzugefügt. |
| [AddAudioFrameLinked](../../aspose.slides/shapecollection/addaudioframelinked)(float, float, float, float, string) | Erstellt einen neuen Audio-Frame, der mit einer externen Audiodatei verknüpft ist, und fügt ihn am Ende der Formen-Sammlung hinzu. |
| [AddAutoShape](../../aspose.slides/shapecollection/addautoshape#addautoshape)(ShapeType, float, float, float, float) | Erstellt eine neue Auto-Form mit Standardformatierung und fügt sie am Ende der Formen-Sammlung hinzu. |
| [AddAutoShape](../../aspose.slides/shapecollection/addautoshape#addautoshape_1)(ShapeType, float, float, float, float, bool) | Erstellt eine neue Auto-Form und fügt sie am Ende der Formen-Sammlung hinzu, optional mit Standard-Vorlagenformatierung initialisiert. |
| [AddChart](../../aspose.slides/shapecollection/addchart#addchart)(ChartType, float, float, float, float) | Erstellt ein neues Diagramm, initialisiert es mit Beispiel-Seriendaten und -Einstellungen und fügt es am Ende der Formen-Sammlung hinzu. |
| [AddChart](../../aspose.slides/shapecollection/addchart#addchart_1)(ChartType, float, float, float, float, bool) | Erstellt ein neues Diagramm, initialisiert es mit Beispiel-Seriendaten und -Einstellungen und fügt es am Ende der Formen-Sammlung hinzu. |
| [AddClone](../../aspose.slides/shapecollection/addclone#addclone)(IShape) | Erstellt eine Kopie der angegebenen Form und fügt sie am Ende der Formen-Sammlung hinzu. Die geklonte Form behält Position und Größe des Originals bei. |
| [AddClone](../../aspose.slides/shapecollection/addclone#addclone_1)(IShape, float, float) | Erstellt eine Kopie der angegebenen Form und fügt sie am Ende der Formen-Sammlung hinzu. Die neue Form übernimmt die Breite und Höhe der *sourceShape*. |
| [AddClone](../../aspose.slides/shapecollection/addclone#addclone_2)(IShape, float, float, float, float) | Erstellt eine Kopie der angegebenen Form und fügt sie am Ende der Formen-Sammlung hinzu. |
| [AddConnector](../../aspose.slides/shapecollection/addconnector#addconnector)(ShapeType, float, float, float, float) | Erstellt eine neue Verbindungslinie mit Standard-Vorlagenstil und fügt sie am Ende der Formen-Sammlung hinzu. |
| [AddConnector](../../aspose.slides/shapecollection/addconnector#addconnector_1)(ShapeType, float, float, float, float, bool) | Erstellt eine neue Verbindungslinie und fügt sie am Ende der Formen-Sammlung hinzu, optional mit Standard-Vorlagenstil. |
| [AddGroupShape](../../aspose.slides/shapecollection/addgroupshape#addgroupshape)() | Erstellt eine neue leere Gruppierungsform und fügt sie am Ende der Formen-Sammlung hinzu. Der Rahmen der Gruppe passt sich automatisch an alle hinzugefügten Formen an. |
| [AddGroupShape](../../aspose.slides/shapecollection/addgroupshape#addgroupshape_1)(ISvgImage, float, float, float, float) | Erstellt eine neue Gruppierungsform, konvertiert das angegebene SVG-Bild in einzelne Formen und fügt die resultierende Gruppe am Ende der Formen-Sammlung hinzu. |
| [AddMathShape](../../aspose.slides/shapecollection/addmathshape)(float, float, float, float) | Erstellt eine neue Rechteck-Auto-Form für mathematischen Inhalt und fügt sie am Ende der Formen-Sammlung hinzu. |
| [AddOleObjectFrame](../../aspose.slides/shapecollection/addoleobjectframe#addoleobjectframe)(float, float, float, float, IOleEmbeddedDataInfo) | Erstellt einen neuen OLE-Objekt-Frame und fügt ihn am Ende der Formen-Sammlung hinzu. |
| [AddOleObjectFrame](../../aspose.slides/shapecollection/addoleobjectframe#addoleobjectframe_1)(float, float, float, float, string, string) | Erstellt einen neuen OLE-Objekt-Frame und fügt ihn am Ende der Formen-Sammlung hinzu. |
| [AddPictureFrame](../../aspose.slides/shapecollection/addpictureframe)(ShapeType, float, float, float, float, IPPImage) | Erstellt einen neuen Bild-Frame, der das angegebene Bild enthält, und fügt ihn am Ende der Formen-Sammlung hinzu. |
| [AddSectionZoomFrame](../../aspose.slides/shapecollection/addsectionzoomframe#addsectionzoomframe)(float, float, float, float, ISection) | Erstellt einen neuen Section-Zoom-Frame und fügt ihn am Ende der Formen-Sammlung hinzu. |
| [AddSectionZoomFrame](../../aspose.slides/shapecollection/addsectionzoomframe#addsectionzoomframe_1)(float, float, float, float, ISection, IPPImage) | Erstellt einen neuen Section-Zoom-Frame mit vordefiniertem Bild und fügt ihn am Ende der Formen-Sammlung hinzu. |
| [AddSmartArt](../../aspose.slides/shapecollection/addsmartart)(float, float, float, float, SmartArtLayoutType) | Erstellt ein SmartArt-Diagramm und fügt es am Ende der Formen-Sammlung hinzu. |
| [AddSummaryZoomFrame](../../aspose.slides/shapecollection/addsummaryzoomframe)(float, float, float, float) | Erstellt einen neuen Summary-Zoom-Frame und fügt ihn am Ende der Formen-Sammlung hinzu. |
| [AddTable](../../aspose.slides/shapecollection/addtable)(float, float, double[], double[]) | Erstellt eine neue Tabelle und fügt sie am Ende der Formen-Sammlung hinzu. |
| [AddVideoFrame](../../aspose.slides/shapecollection/addvideoframe#addvideoframe)(float, float, float, float, IVideo) | Erstellt einen neuen Video-Frame und fügt ihn am Ende der Formen-Sammlung hinzu. |
| [AddVideoFrame](../../aspose.slides/shapecollection/addvideoframe#addvideoframe_1)(float, float, float, float, string) | Erstellt einen neuen Video-Frame und fügt ihn am Ende der Formen-Sammlung hinzu. |
| [AddZoomFrame](../../aspose.slides/shapecollection/addzoomframe#addzoomframe)(float, float, float, float, ISlide) | Erstellt einen neuen Zoom-Frame und fügt ihn am Ende der Formen-Sammlung hinzu. |
| [AddZoomFrame](../../aspose.slides/shapecollection/addzoomframe#addzoomframe_1)(float, float, float, float, ISlide, IPPImage) | Erstellt einen neuen Zoom-Frame und fügt ihn am Ende der Formen-Sammlung hinzu. |
| [Clear](../../aspose.slides/shapecollection/clear)() | Entfernt alle Formen aus der Formen-Sammlung. |
| [CopyTo](../../aspose.slides/shapecollection/copyto)(Array, int) | Kopiert alle Elemente aus der Sammlung in das angegebene Array. |
| [GetEnumerator](../../aspose.slides/shapecollection/getenumerator)() | Gibt einen Enumerator zurück, der die Sammlung durchläuft. |
| [IndexOf](../../aspose.slides/shapecollection/indexof)(IShape) | Gibt den nullbasierten Index des ersten Vorkommens der angegebenen Form in der Sammlung zurück. |
| [InsertAudioFrameCD](../../aspose.slides/shapecollection/insertaudioframecd)(int, float, float, float, float) | Erstellt einen neuen Audio-Frame, der mit einer CD-Spur verknüpft ist, und fügt ihn an der angegebenen Position in die Formen-Sammlung ein. |
| [InsertAudioFrameEmbedded](../../aspose.slides/shapecollection/insertaudioframeembedded#insertaudioframeembedded)(int, float, float, float, float, IAudio) | Erstellt einen neuen Audio-Frame und fügt ihn an der angegebenen Position in die Formen-Sammlung ein, wobei ein vorhandenes Audio-Objekt aus der Presentation.Audios-Liste verwendet wird. |
| [InsertAudioFrameEmbedded](../../aspose.slides/shapecollection/insertaudioframeembedded#insertaudioframeembedded_1)(int, float, float, float, float, Stream) | Erstellt einen neuen Audio-Frame mit einer eingebetteten WAV-Datei und fügt ihn an der angegebenen Position in die Formen-Sammlung ein. Der eingebettete Audio-Clip wird zur Presentation.Audios-Sammlung hinzugefügt. |
| [InsertAudioFrameLinked](../../aspose.slides/shapecollection/insertaudioframelinked)(int, float, float, float, float, string) | Erstellt einen neuen Audio-Frame, der mit einer externen Audiodatei verknüpft ist, und fügt ihn an der angegebenen Position in die Formen-Sammlung ein. |
| [InsertAutoShape](../../aspose.slides/shapecollection/insertautoshape#insertautoshape)(int, ShapeType, float, float, float, float) | Erstellt eine neue Auto-Form und fügt sie an der angegebenen Position in die Formen-Sammlung ein, wobei die Standard-Vorlagenformatierung angewendet wird. |
| [InsertAutoShape](../../aspose.slides/shapecollection/insertautoshape#insertautoshape_1)(int, ShapeType, float, float, float, float, bool) | Erstellt eine neue Auto-Form und fügt sie an der angegebenen Position in die Formen-Sammlung ein, optional mit Standard-Vorlagenstil initialisiert. |
| [InsertChart](../../aspose.slides/shapecollection/insertchart#insertchart)(ChartType, float, float, float, float, int) | Erstellt ein neues Diagramm, initialisiert es mit Beispiel-Seriendaten und -Einstellungen und fügt es an der angegebenen Position in die Formen-Sammlung ein. |
| [InsertChart](../../aspose.slides/shapecollection/insertchart#insertchart_1)(ChartType, float, float, float, float, int, bool) | Erstellt ein neues Diagramm, initialisiert es mit Beispiel-Seriendaten und -Einstellungen und fügt es an der angegebenen Position in die Formen-Sammlung ein. |
| [InsertClone](../../aspose.slides/shapecollection/insertclone#insertclone)(int, IShape) | Erstellt eine Kopie der angegebenen Form und fügt sie an der angegebenen Position in die Formen-Sammlung ein. Die geklonte Form behält Position und Größe des Originals bei. |
| [InsertClone](../../aspose.slides/shapecollection/insertclone#insertclone_1)(int, IShape, float, float) | Erstellt eine Kopie der angegebenen Form und fügt sie an der angegebenen Position in die Formen-Sammlung ein. Die neue Form übernimmt die Breite und Höhe der *sourceShape*. |
| [InsertClone](../../aspose.slides/shapecollection/insertclone#insertclone_2)(int, IShape, float, float, float, float) | Erstellt eine Kopie der angegebenen Form und fügt sie an der angegebenen Position in die Formen-Sammlung ein. |
| [InsertConnector](../../aspose.slides/shapecollection/insertconnector#insertconnector)(int, ShapeType, float, float, float, float) | Erstellt eine neue Verbindungslinie und fügt sie an der angegebenen Position in die Formen-Sammlung ein, wobei die Standard-Vorlagenstil angewendet wird. |
| [InsertConnector](../../aspose.slides/shapecollection/insertconnector#insertconnector_1)(int, ShapeType, float, float, float, float, bool) | Erstellt eine neue Verbindungslinie und fügt sie an der angegebenen Position in die Formen-Sammlung ein, optional mit Standard-Vorlagenstil. |
| [InsertGroupShape](../../aspose.slides/shapecollection/insertgroupshape)(int) | Erstellt eine neue leere Gruppierungsform und fügt sie an der angegebenen Position in die Formen-Sammlung ein. Der Rahmen der Gruppe passt sich automatisch an alle hinzugefügten Formen an. |
| [InsertOleObjectFrame](../../aspose.slides/shapecollection/insertoleobjectframe#insertoleobjectframe)(int, float, float, float, float, IOleEmbeddedDataInfo) | Erstellt einen neuen OLE-Objekt-Frame und fügt ihn an der angegebenen Position in die Formen-Sammlung ein. |
| [InsertOleObjectFrame](../../aspose.slides/shapecollection/insertoleobjectframe#insertoleobjectframe_1)(int, float, float, float, float, string, string) | Erstellt einen neuen OLE-Objekt-Frame und fügt ihn an der angegebenen Position in die Formen-Sammlung ein. |
| [InsertPictureFrame](../../aspose.slides/shapecollection/insertpictureframe)(int, ShapeType, float, float, float, float, IPPImage) | Erstellt einen neuen Bild-Frame, der das angegebene Bild enthält, und fügt ihn an der angegebenen Position in die Formen-Sammlung ein. |
| [InsertSectionZoomFrame](../../aspose.slides/shapecollection/insertsectionzoomframe#insertsectionzoomframe)(int, float, float, float, float, ISection) | Erstellt einen neuen Section-Zoom-Frame und fügt ihn an der angegebenen Position in die Formen-Sammlung ein. |
| [InsertSectionZoomFrame](../../aspose.slides/shapecollection/insertsectionzoomframe#insertsectionzoomframe_1)(int, float, float, float, float, ISection, IPPImage) | Erstellt einen neuen Section-Zoom-Frame mit vordefiniertem Bild und fügt ihn an der angegebenen Position in die Formen-Sammlung ein. |
| [InsertSummaryZoomFrame](../../aspose.slides/shapecollection/insertsummaryzoomframe)(int, float, float, float, float) | Erstellt einen neuen Summary-Zoom-Frame und fügt ihn an der angegebenen Position in die Formen-Sammlung ein. |
| [InsertTable](../../aspose.slides/shapecollection/inserttable)(int, float, float, double[], double[]) | Erstellt eine neue Tabelle und fügt sie an der angegebenen Position in die Formen-Sammlung ein. |
| [InsertVideoFrame](../../aspose.slides/shapecollection/insertvideoframe)(int, float, float, float, float, string) | Erstellt einen neuen Video-Frame und fügt ihn an der angegebenen Position in die Formen-Sammlung ein. |
| [InsertZoomFrame](../../aspose.slides/shapecollection/insertzoomframe#insertzoomframe)(int, float, float, float, float, ISlide) | Erstellt einen neuen Zoom-Frame und fügt ihn an der angegebenen Position in die Formen-Sammlung ein. |
| [InsertZoomFrame](../../aspose.slides/shapecollection/insertzoomframe#insertzoomframe_1)(int, float, float, float, float, ISlide, IPPImage) | Erstellt einen neuen Zoom-Frame mit vordefiniertem Bild und fügt ihn an der angegebenen Position in die Formen-Sammlung ein. |
| [Remove](../../aspose.slides/shapecollection/remove)(IShape) | Entfernt das erste Vorkommen der angegebenen Form aus der Formen-Sammlung. |
| [RemoveAt](../../aspose.slides/shapecollection/removeat)(int) | Entfernt die Form an der angegebenen Position aus der Formen-Sammlung. |
| [Reorder](../../aspose.slides/shapecollection/reorder#reorder)(int, IShape) | Verschiebt die angegebene Form an eine neue Position innerhalb der Formen-Sammlung. |
| [Reorder](../../aspose.slides/shapecollection/reorder#reorder_1)(int, params IShape[]) | Verschiebt die angegebenen Formen innerhalb der Formen-Sammlung und platziert sie beginnend ab dem angegebenen Index. |
| [ToArray](../../aspose.slides/shapecollection/toarray#toarray)() | Erstellt und gibt ein Array zurück, das alle Formen enthält. |
| [ToArray](../../aspose.slides/shapecollection/toarray#toarray_1)(int, int) | Erstellt und gibt ein Array zurück, das alle Formen im angegebenen Bereich enthält. |

### Siehe auch

* Klasse [DomObject&lt;TParent&gt;](../domobject-1)
* Klasse [GroupShape](../groupshape)
* Schnittstelle [IShapeCollection](../ishapecollection)
* Namensraum [Aspose.Slides](../../aspose.slides)
* Assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->