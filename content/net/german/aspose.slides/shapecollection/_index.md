---
title: ShapeCollection
second_title: Aspose.Slides für .NET API-Referenz
description: Stellt eine Sammlung von Formen dar.
type: docs
weight: 9550
url: /de/aspose.slides/shapecollection/
---

## ShapeCollection-Klasse

Stellt eine Sammlung von Formen dar.

```csharp
public sealed class ShapeCollection : DomObject<GroupShape>, IShapeCollection
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [Count](../../aspose.slides/shapecollection/count) { get; } | Gibt die Anzahl der tatsächlich in der Sammlung enthaltenen Elemente zurück. Nur-Lese Int32. |
| [IsSynchronized](../../aspose.slides/shapecollection/issynchronized) { get; } | Gibt einen Wert zurück, der angibt, ob der Zugriff auf die Sammlung synchronisiert (thread-sicher) ist. Nur-Lese Boolean. |
| [Item](../../aspose.slides/shapecollection/item) { get; } | Gibt das Element am angegebenen Index zurück. Nur-Lese [`IShape`](../ishape). |
| [ParentGroup](../../aspose.slides/shapecollection/parentgroup) { get; } | Gibt das übergeordnete GroupShape-Objekt für eine Formensammlung zurück. Nur-Lese [`IGroupShape`](../igroupshape). |
| [SyncRoot](../../aspose.slides/shapecollection/syncroot) { get; } | Gibt eine Synchronisierungswurzel zurück. Nur-Lese Object. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [AddAudioFrameCD](../../aspose.slides/shapecollection/addaudioframecd)(float, float, float, float) | Fügt ein AudioFrame mit CD an das Ende der Sammlung hinzu. |
| [AddAudioFrameEmbedded](../../aspose.slides/shapecollection/addaudioframeembedded#addaudioframeembedded)(float, float, float, float, IAudio) | Fügt ein neues Audio-Frame mit einer eingebetteten Audiodatei am Ende einer Sammlung hinzu. Es verwendet die Audiodatei aus der Liste Presentation.Audios. |
| [AddAudioFrameEmbedded](../../aspose.slides/shapecollection/addaudioframeembedded#addaudioframeembedded_1)(float, float, float, float, Stream) | Fügt ein neues Audio-Frame mit einer eingebetteten Audiodatei am Ende einer Sammlung hinzu. Die eingebettete Audiodatei kann nur WAV sein. Es fügt neue Audio in die Liste Presentation.Audios ein. |
| [AddAudioFrameLinked](../../aspose.slides/shapecollection/addaudioframelinked)(float, float, float, float, string) | Fügt ein neues Audio-Frame mit einer verlinkten Audiodatei an das Ende der Sammlung hinzu. |
| [AddAutoShape](../../aspose.slides/shapecollection/addautoshape#addautoshape)(ShapeType, float, float, float, float) | Erstellt eine neue Autoform, passt sie vom Standard-Template an und fügt sie an das Ende der Sammlung hinzu. |
| [AddAutoShape](../../aspose.slides/shapecollection/addautoshape#addautoshape_1)(ShapeType, float, float, float, float, bool) | Erstellt eine neue Autoform und fügt sie an das Ende der Sammlung hinzu. |
| [AddChart](../../aspose.slides/shapecollection/addchart#addchart)(ChartType, float, float, float, float) | Erstellt ein neues Diagramm, initialisiert es mit Beispielseriendaten und Einstellungen und fügt es an das Ende der Sammlung hinzu. |
| [AddChart](../../aspose.slides/shapecollection/addchart#addchart_1)(ChartType, float, float, float, float, bool) | Erstellt ein neues Diagramm und fügt es an das Ende der Sammlung hinzu. |
| [AddClone](../../aspose.slides/shapecollection/addclone#addclone)(IShape) | Fügt eine Kopie einer angegebenen Form an das Ende der Sammlung hinzu. X, Y, Breite und Höhe der neuen Form sind gleich X, Y, Breite und Höhe der *sourceShape*. |
| [AddClone](../../aspose.slides/shapecollection/addclone#addclone_1)(IShape, float, float) | Fügt eine Kopie einer angegebenen Form an das Ende der Sammlung hinzu. Breite und Höhe der neuen Form sind gleich Breite und Höhe der *sourceShape*. |
| [AddClone](../../aspose.slides/shapecollection/addclone#addclone_2)(IShape, float, float, float, float) | Fügt eine Kopie einer angegebenen Form an das Ende der Sammlung hinzu. |
| [AddConnector](../../aspose.slides/shapecollection/addconnector#addconnector)(ShapeType, float, float, float, float) | Erstellt einen neuen Connector, passt ihn vom Standard-Template an und fügt ihn an das Ende der Sammlung hinzu. |
| [AddConnector](../../aspose.slides/shapecollection/addconnector#addconnector_1)(ShapeType, float, float, float, float, bool) | Erstellt einen neuen Connector und fügt ihn an das Ende der Sammlung hinzu. |
| [AddGroupShape](../../aspose.slides/shapecollection/addgroupshape#addgroupshape)() | Erstellt ein neues GroupShape und fügt es an das Ende der Sammlung hinzu. Die Größe und Position des GroupShape-Rahmens werden an den Inhalt angepasst, wenn eine neue Form in das GroupShape eingefügt wird. |
| [AddGroupShape](../../aspose.slides/shapecollection/addgroupshape#addgroupshape_1)(ISvgImage, float, float, float, float) | Erstellt ein neues GroupShape, füllt es mit konvertierten Formen aus SVG und fügt es an das Ende der Sammlung hinzu. |
| [AddMathShape](../../aspose.slides/shapecollection/addmathshape)(float, float, float, float) | Erstellt eine neue Autoform, die aus dem Standard-Template für mathematische Inhalte angepasst ist und fügt sie an das Ende der Sammlung hinzu. |
| [AddOleObjectFrame](../../aspose.slides/shapecollection/addoleobjectframe#addoleobjectframe)(float, float, float, float, IOleEmbeddedDataInfo) | Fügt ein neues OLE-Objekt am Ende einer Sammlung hinzu. |
| [AddOleObjectFrame](../../aspose.slides/shapecollection/addoleobjectframe#addoleobjectframe_1)(float, float, float, float, string, string) | Fügt ein neues OLE-Objekt am Ende einer Sammlung hinzu. |
| [AddPictureFrame](../../aspose.slides/shapecollection/addpictureframe)(ShapeType, float, float, float, float, IPPImage) | Erstellt einen neuen PictureFrame und fügt ihn an das Ende der Sammlung hinzu. |
| [AddSectionZoomFrame](../../aspose.slides/shapecollection/addsectionzoomframe#addsectionzoomframe)(float, float, float, float, ISection) | Fügt ein neues Abschnitts-Zoom-Objekt an das Ende einer Sammlung hinzu. |
| [AddSectionZoomFrame](../../aspose.slides/shapecollection/addsectionzoomframe#addsectionzoomframe_1)(float, float, float, float, ISection, IPPImage) | Fügt ein neues Abschnitts-Zoom-Objekt an das Ende einer Sammlung mit einem vordefinierten Bild hinzu. |
| [AddSmartArt](../../aspose.slides/shapecollection/addsmartart)(float, float, float, float, SmartArtLayoutType) | Fügt ein SmartArt-Diagramm hinzu. |
| [AddSummaryZoomFrame](../../aspose.slides/shapecollection/addsummaryzoomframe)(float, float, float, float) | Fügt ein neues Zusammenfassungs-Zoom-Objekt an das Ende einer Sammlung hinzu. |
| [AddTable](../../aspose.slides/shapecollection/addtable)(float, float, double[], double[]) | Erstellt eine neue Tabelle und fügt sie an das Ende der Sammlung hinzu. |
| [AddVideoFrame](../../aspose.slides/shapecollection/addvideoframe#addvideoframe)(float, float, float, float, IVideo) | Fügt ein neues Video-Frame am Ende einer Sammlung hinzu. |
| [AddVideoFrame](../../aspose.slides/shapecollection/addvideoframe#addvideoframe_1)(float, float, float, float, string) | Fügt ein neues Video-Frame am Ende einer Sammlung hinzu. |
| [AddZoomFrame](../../aspose.slides/shapecollection/addzoomframe#addzoomframe)(float, float, float, float, ISlide) | Fügt ein neues Zoom-Objekt an das Ende einer Sammlung hinzu. |
| [AddZoomFrame](../../aspose.slides/shapecollection/addzoomframe#addzoomframe_1)(float, float, float, float, ISlide, IPPImage) | Fügt ein neues Zoom-Objekt an das Ende einer Sammlung hinzu. |
| [Clear](../../aspose.slides/shapecollection/clear)() | Entfernt alle Formen aus der Sammlung. |
| [CopyTo](../../aspose.slides/shapecollection/copyto)(Array, int) | Kopiert alle Elemente aus der Sammlung in das angegebene Array. |
| [GetEnumerator](../../aspose.slides/shapecollection/getenumerator)() | Gibt einen Enumerator zurück, der durch die Sammlung iteriert. |
| [IndexOf](../../aspose.slides/shapecollection/indexof)(IShape) | Gibt den nullbasierten Index des ersten Vorkommens einer Form in der Sammlung zurück. |
| [InsertAudioFrameCD](../../aspose.slides/shapecollection/insertaudioframecd)(int, float, float, float, float) | Fügt ein AudioFrame mit CD ein. |
| [InsertAudioFrameEmbedded](../../aspose.slides/shapecollection/insertaudioframeembedded#insertaudioframeembedded)(int, float, float, float, float, IAudio) | Fügt ein AudioFrame mit eingebetteter Audiodatei ein. Es verwendet die Audiodatei aus der Liste Presentation.Audios. |
| [InsertAudioFrameEmbedded](../../aspose.slides/shapecollection/insertaudioframeembedded#insertaudioframeembedded_1)(int, float, float, float, float, Stream) | Fügt ein AudioFrame mit eingebetteter Audiodatei ein. Die eingebettete Audiodatei kann nur WAV sein. |
| [InsertAudioFrameLinked](../../aspose.slides/shapecollection/insertaudioframelinked)(int, float, float, float, float, string) | Erstellt ein neues Audio-Frame mit verlinkter Audiodatei und fügt es an einer bestimmten Stelle in der Sammlung ein. |
| [InsertAutoShape](../../aspose.slides/shapecollection/insertautoshape#insertautoshape)(int, ShapeType, float, float, float, float) | Erstellt eine neue Autoform, passt sie vom Standard-Template an und fügt sie an eine bestimmte Stelle in der Sammlung ein. Hinweis: Der Typ der Form wird durch den Parameter shapeType bestimmt. |
| [InsertAutoShape](../../aspose.slides/shapecollection/insertautoshape#insertautoshape_1)(int, ShapeType, float, float, float, float, bool) | Erstellt eine neue Autoform und fügt sie an eine bestimmte Stelle in der Sammlung ein. Hinweis: Der Typ der Form wird durch den Parameter shapeType bestimmt. |
| [InsertChart](../../aspose.slides/shapecollection/insertchart#insertchart)(ChartType, float, float, float, float, int) | Erstellt ein neues Diagramm, initialisiert es mit Beispielseriendaten und Einstellungen und fügt es an die angegebene Position in der Sammlung ein. |
| [InsertChart](../../aspose.slides/shapecollection/insertchart#insertchart_1)(ChartType, float, float, float, float, int, bool) | Erstellt ein neues Diagramm und fügt es an die angegebene Position in der Sammlung ein. |
| [InsertClone](../../aspose.slides/shapecollection/insertclone#insertclone)(int, IShape) | Fügt eine Kopie einer angegebenen Form an eine angegebene Position in der Sammlung ein. X, Y, Breite und Höhe der neuen Form sind gleich X, Y, Breite und Höhe der *sourceShape*. |
| [InsertClone](../../aspose.slides/shapecollection/insertclone#insertclone_1)(int, IShape, float, float) | Fügt eine Kopie einer angegebenen Form an eine angegebene Position in der Sammlung ein. Breite und Höhe der neuen Form sind gleich Breite und Höhe der *sourceShape*. |
| [InsertClone](../../aspose.slides/shapecollection/insertclone#insertclone_2)(int, IShape, float, float, float, float) | Fügt eine Kopie einer angegebenen Form an eine angegebene Position in der Sammlung ein. |
| [InsertConnector](../../aspose.slides/shapecollection/insertconnector#insertconnector)(int, ShapeType, float, float, float, float) | Erstellt einen neuen Connector, passt ihn vom Standard-Template an und fügt ihn an eine bestimmte Position in der Sammlung ein. |
| [InsertConnector](../../aspose.slides/shapecollection/insertconnector#insertconnector_1)(int, ShapeType, float, float, float, float, bool) | Erstellt einen neuen Connector und fügt ihn an eine bestimmte Position in der Sammlung ein. |
| [InsertGroupShape](../../aspose.slides/shapecollection/insertgroupshape)(int) | Erstellt ein neues GroupShape und fügt es an eine bestimmte Position in der Sammlung ein. Die Größe und Position des GroupShape-Rahmens werden an den Inhalt angepasst, wenn eine neue Form in das GroupShape eingefügt wird. |
| [InsertOleObjectFrame](../../aspose.slides/shapecollection/insertoleobjectframe#insertoleobjectframe)(int, float, float, float, float, IOleEmbeddedDataInfo) | Erstellt ein neues OLE-Objekt und fügt es an einer bestimmten Position in der Sammlung ein. |
| [InsertOleObjectFrame](../../aspose.slides/shapecollection/insertoleobjectframe#insertoleobjectframe_1)(int, float, float, float, float, string, string) | Erstellt ein neues OLE-Objekt und fügt es an einer bestimmten Position in der Sammlung ein. |
| [InsertPictureFrame](../../aspose.slides/shapecollection/insertpictureframe)(int, ShapeType, float, float, float, float, IPPImage) | Erstellt einen neuen PictureFrame und fügt ihn an eine bestimmte Position in der Sammlung ein. |
| [InsertSectionZoomFrame](../../aspose.slides/shapecollection/insertsectionzoomframe#insertsectionzoomframe)(int, float, float, float, float, ISection) | Erstellt ein neues Abschnitts-Zoom-Objekt und fügt es an eine bestimmte Position in der Sammlung ein. |
| [InsertSectionZoomFrame](../../aspose.slides/shapecollection/insertsectionzoomframe#insertsectionzoomframe_1)(int, float, float, float, float, ISection, IPPImage) | Erstellt ein neues Abschnitts-Zoom-Objekt und fügt es an eine bestimmte Position in der Sammlung ein. |
| [InsertSummaryZoomFrame](../../aspose.slides/shapecollection/insertsummaryzoomframe)(int, float, float, float, float) | Erstellt ein neues Zusammenfassungs-Zoom-Objekt und fügt es an eine bestimmte Position in der Sammlung ein. |
| [InsertTable](../../aspose.slides/shapecollection/inserttable)(int, float, float, double[], double[]) | Erstellt eine neue Tabelle und fügt sie an eine bestimmte Position in der Sammlung ein. |
| [InsertVideoFrame](../../aspose.slides/shapecollection/insertvideoframe)(int, float, float, float, float, string) | Erstellt ein neues Video-Frame und fügt es an eine bestimmte Position in der Sammlung ein. |
| [InsertZoomFrame](../../aspose.slides/shapecollection/insertzoomframe#insertzoomframe)(int, float, float, float, float, ISlide) | Erstellt ein neues Zoom-Objekt und fügt es an eine bestimmte Position in der Sammlung ein. |
| [InsertZoomFrame](../../aspose.slides/shapecollection/insertzoomframe#insertzoomframe_1)(int, float, float, float, float, ISlide, IPPImage) | Erstellt ein neues Zoom-Objekt und fügt es an eine bestimmte Position in der Sammlung ein. |
| [Remove](../../aspose.slides/shapecollection/remove)(IShape) | Entfernt das erste Vorkommen einer bestimmten Form aus der Sammlung. |
| [RemoveAt](../../aspose.slides/shapecollection/removeat)(int) | Entfernt das Element am angegebenen Index der Sammlung. |
| [Reorder](../../aspose.slides/shapecollection/reorder#reorder)(int, IShape) | Verschiebt eine Form in der Sammlung an die angegebene Position. |
| [Reorder](../../aspose.slides/shapecollection/reorder#reorder_1)(int, params IShape[]) | Verschiebt Formen aus der Sammlung an die angegebene Position. Die Formen werden ab dem angegebenen Index in der Reihenfolge platziert, in der sie in der Liste erscheinen. |
| [ToArray](../../aspose.slides/shapecollection/toarray#toarray)() | Erstellt und gibt ein Array mit allen Formen zurück. |
| [ToArray](../../aspose.slides/shapecollection/toarray#toarray_1)(int, int) | Erstellt und gibt ein Array mit allen Formen aus dem angegebenen Bereich zurück. Ein Index der ersten zurückzugebenden Form. Eine Anzahl von Formen, die zurückgegeben werden sollen. |

### Siehe auch

* class [DomObject&lt;TParent&gt;](../domobject-1)
* class [GroupShape](../groupshape)
* interface [IShapeCollection](../ishapecollection)
* namespace [Aspose.Slides](../../aspose.slides)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->