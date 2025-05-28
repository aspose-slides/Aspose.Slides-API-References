---
title: ShapeCollection
second_title: Aspose.Slides für .NET-API-Referenz
description: Stellt eine Sammlung von Formen dar.
type: docs
weight: 9110
url: /de/aspose.slides/shapecollection/
---
## ShapeCollection class

Stellt eine Sammlung von Formen dar.

```csharp
public sealed class ShapeCollection : DomObject<GroupShape>, IShapeCollection
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [Count](../../aspose.slides/shapecollection/count) { get; } | Ruft die Anzahl der tatsächlich in der Sammlung enthaltenen Elemente ab. SchreibgeschütztInt32 . |
| [IsSynchronized](../../aspose.slides/shapecollection/issynchronized) { get; } | Gibt einen Wert zurück, der angibt, ob der Zugriff auf die Sammlung synchronisiert (threadsicher) ist. SchreibgeschütztBoolean . |
| [Item](../../aspose.slides/shapecollection/item) { get; } | Ruft das Element am angegebenen Index ab. Schreibgeschützt[`IShape`](../ishape) . |
| [ParentGroup](../../aspose.slides/shapecollection/parentgroup) { get; } | Gibt das übergeordnete GroupShape-Objekt für eine Formensammlung zurück. Schreibgeschützt[`IGroupShape`](../igroupshape) . |
| [SyncRoot](../../aspose.slides/shapecollection/syncroot) { get; } | Gibt einen Synchronisationsstamm zurück. SchreibgeschütztObject . |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [AddAudioFrameCD](../../aspose.slides/shapecollection/addaudioframecd)(float, float, float, float) | Fügt einen AudioFrame mit CD am Ende der Sammlung hinzu. |
| [AddAudioFrameEmbedded](../../aspose.slides/shapecollection/addaudioframeembedded#addaudioframeembedded)(float, float, float, float, IAudio) | Fügt einen neuen Audioframe mit eingebetteter Audiodatei am Ende einer Sammlung hinzu. Es verwendet eine Audiodatei aus der Presentation.Audios-Liste. |
| [AddAudioFrameEmbedded](../../aspose.slides/shapecollection/addaudioframeembedded#addaudioframeembedded_1)(float, float, float, float, Stream) | Fügt am Ende einer Sammlung einen neuen Audioframe mit eingebetteter Audiodatei hinzu. Eingebettete Audiodatei kann nur eine WAV-Datei sein. Fügt neues Audio zur Presentation.Audios-Liste hinzu. |
| [AddAudioFrameLinked](../../aspose.slides/shapecollection/addaudioframelinked)(float, float, float, float, string) | Fügt einen neuen Audioframe mit verknüpfter Audiodatei am Ende einer Sammlung hinzu. |
| [AddAutoShape](../../aspose.slides/shapecollection/addautoshape#addautoshape)(ShapeType, float, float, float, float) | Erstellt eine neue AutoForm, stimmt sie anhand der Standardvorlage ab und fügt sie am Ende der Sammlung hinzu. |
| [AddAutoShape](../../aspose.slides/shapecollection/addautoshape#addautoshape_1)(ShapeType, float, float, float, float, bool) | Erstellt eine neue AutoForm und fügt sie am Ende der Sammlung hinzu. |
| [AddChart](../../aspose.slides/shapecollection/addchart#addchart)(ChartType, float, float, float, float) | Erstellt ein neues Diagramm, initialisiert es mit Beispielseriendaten und -einstellungen und fügt es am Ende der Sammlung hinzu. |
| [AddChart](../../aspose.slides/shapecollection/addchart#addchart_1)(ChartType, float, float, float, float, bool) | Erstellt ein neues Diagramm und fügt es am Ende der Sammlung hinzu. |
| [AddClone](../../aspose.slides/shapecollection/addclone#addclone)(IShape) | Fügt eine Kopie einer bestimmten Form am Ende der Sammlung hinzu. X, Y, Breite und Höhe der neuen Form sind gleich X, Y, Breite und Höhe der*sourceShape* . |
| [AddClone](../../aspose.slides/shapecollection/addclone#addclone_1)(IShape, float, float) | Fügt eine Kopie einer bestimmten Form am Ende der Sammlung hinzu. Breite und Höhe der neuen Form sind gleich Breite und Höhe der*sourceShape* . |
| [AddClone](../../aspose.slides/shapecollection/addclone#addclone_2)(IShape, float, float, float, float) | Fügt eine Kopie einer bestimmten Form am Ende der Sammlung hinzu. |
| [AddConnector](../../aspose.slides/shapecollection/addconnector#addconnector)(ShapeType, float, float, float, float) | Erstellt einen neuen Connector, optimiert ihn anhand der Standardvorlage und fügt ihn am Ende der Sammlung hinzu. |
| [AddConnector](../../aspose.slides/shapecollection/addconnector#addconnector_1)(ShapeType, float, float, float, float, bool) | Erstellt einen neuen Connector und fügt ihn am Ende der Sammlung hinzu. |
| [AddGroupShape](../../aspose.slides/shapecollection/addgroupshape#addgroupshape)() | Erstellt eine neue GroupShape und fügt sie am Ende der Sammlung hinzu. Größe und Position des GroupShape-Rahmens werden an den Inhalt angepasst, wenn eine neue Form zur GroupShape hinzugefügt wird. |
| [AddGroupShape](../../aspose.slides/shapecollection/addgroupshape#addgroupshape_1)(ISvgImage, float, float, float, float) | Erstellt eine neue GroupShape, füllt sie mit konvertierten Formen aus SVG und fügt sie am Ende der Sammlung hinzu. |
| [AddMathShape](../../aspose.slides/shapecollection/addmathshape)(float, float, float, float) | Erstellt eine neue Autoshape, die von der Standardvorlage auf mathematische Inhalte abgestimmt ist, und fügt sie am Ende der Sammlung hinzu. |
| [AddOleObjectFrame](../../aspose.slides/shapecollection/addoleobjectframe#addoleobjectframe)(float, float, float, float, IOleEmbeddedDataInfo) | Fügt ein neues OLE-Objekt am Ende einer Sammlung hinzu. |
| [AddOleObjectFrame](../../aspose.slides/shapecollection/addoleobjectframe#addoleobjectframe_1)(float, float, float, float, string, string) | Fügt ein neues OLE-Objekt am Ende einer Sammlung hinzu. |
| [AddPictureFrame](../../aspose.slides/shapecollection/addpictureframe)(ShapeType, float, float, float, float, IPPImage) | Erstellt einen neuen PictureFrame und fügt ihn am Ende der Sammlung hinzu. |
| [AddSectionZoomFrame](../../aspose.slides/shapecollection/addsectionzoomframe#addsectionzoomframe)(float, float, float, float, ISection) | Fügt ein neues Abschnitts-Zoom-Objekt am Ende einer Sammlung hinzu. |
| [AddSectionZoomFrame](../../aspose.slides/shapecollection/addsectionzoomframe#addsectionzoomframe_1)(float, float, float, float, ISection, IPPImage) | Fügt ein neues Abschnitts-Zoom-Objekt am Ende einer Sammlung mit einem vordefinierten Bild hinzu. |
| [AddSmartArt](../../aspose.slides/shapecollection/addsmartart)(float, float, float, float, SmartArtLayoutType) | SmartArt-Diagramm hinzufügen. |
| [AddSummaryZoomFrame](../../aspose.slides/shapecollection/addsummaryzoomframe)(float, float, float, float) | Fügt ein neues Zusammenfassungs-Zoom-Objekt am Ende einer Sammlung hinzu. |
| [AddTable](../../aspose.slides/shapecollection/addtable)(float, float, double[], double[]) | Erstellt eine neue Tabelle und fügt sie am Ende der Sammlung hinzu. |
| [AddVideoFrame](../../aspose.slides/shapecollection/addvideoframe#addvideoframe)(float, float, float, float, IVideo) | Fügt einen neuen Videoframe am Ende einer Sammlung hinzu. |
| [AddVideoFrame](../../aspose.slides/shapecollection/addvideoframe#addvideoframe_1)(float, float, float, float, string) | Fügt einen neuen Videoframe am Ende einer Sammlung hinzu. |
| [AddZoomFrame](../../aspose.slides/shapecollection/addzoomframe#addzoomframe)(float, float, float, float, ISlide) | Fügt ein neues Zoom-Objekt am Ende einer Sammlung hinzu. |
| [AddZoomFrame](../../aspose.slides/shapecollection/addzoomframe#addzoomframe_1)(float, float, float, float, ISlide, IPPImage) | Fügt ein neues Zoom-Objekt am Ende einer Sammlung hinzu. |
| [Clear](../../aspose.slides/shapecollection/clear)() | Entfernt alle Formen aus der Sammlung. |
| [CopyTo](../../aspose.slides/shapecollection/copyto)(Array, int) | Kopiert alle Elemente aus der Sammlung in das angegebene Array. |
| [GetEnumerator](../../aspose.slides/shapecollection/getenumerator)() | Gibt einen Enumerator zurück, der die Sammlung durchläuft. |
| [IndexOf](../../aspose.slides/shapecollection/indexof)(IShape) | Gibt den nullbasierten Index des ersten Vorkommens einer Form in der Sammlung zurück. |
| [InsertAudioFrameCD](../../aspose.slides/shapecollection/insertaudioframecd)(int, float, float, float, float) | Fügen Sie einen AudioFrame mit CD ein. |
| [InsertAudioFrameEmbedded](../../aspose.slides/shapecollection/insertaudioframeembedded#insertaudioframeembedded)(int, float, float, float, float, IAudio) | Fügt einen AudioFrame mit eingebetteter Audiodatei ein. Es verwendet eine Audiodatei aus der Presentation.Audios-Liste. |
| [InsertAudioFrameEmbedded](../../aspose.slides/shapecollection/insertaudioframeembedded#insertaudioframeembedded_1)(int, float, float, float, float, Stream) | Fügen Sie einen AudioFrame mit eingebetteter Audiodatei ein. Eingebetteter Audiodatei-Sound kann nur WAV sein. |
| [InsertAudioFrameLinked](../../aspose.slides/shapecollection/insertaudioframelinked)(int, float, float, float, float, string) | Erstellt einen neuen Audioframe mit verknüpfter Audiodatei und fügt ihn am angegebenen Index in eine Sammlung ein. |
| [InsertAutoShape](../../aspose.slides/shapecollection/insertautoshape#insertautoshape)(int, ShapeType, float, float, float, float) | Erstellt eine neue AutoForm, stimmt sie aus der Standardvorlage ab und fügt sie in die Sammlung am angegebenen Index ein. Hinweis: Der Typ der Form wird durch den Parameter shapeType bestimmt. |
| [InsertAutoShape](../../aspose.slides/shapecollection/insertautoshape#insertautoshape_1)(int, ShapeType, float, float, float, float, bool) | Erstellt eine neue AutoForm und fügt sie am angegebenen Index in die Sammlung ein. Hinweis: Der Typ der Form wird durch den Parameter shapeType bestimmt. |
| [InsertChart](../../aspose.slides/shapecollection/insertchart#insertchart)(ChartType, float, float, float, float, int) | Erstellt ein neues Diagramm, initialisiert es mit Probenseriendaten und -einstellungen und fügt es an der angegebenen Position in der Sammlung ein. |
| [InsertChart](../../aspose.slides/shapecollection/insertchart#insertchart_1)(ChartType, float, float, float, float, int, bool) | Erstellt ein neues Diagramm und fügt es an der angegebenen Position in der Sammlung ein. |
| [InsertClone](../../aspose.slides/shapecollection/insertclone#insertclone)(int, IShape) | Fügt eine Kopie einer bestimmten Form an der angegebenen Position der Sammlung ein. X, Y, Breite und Höhe der neuen Form sind gleich X, Y, Breite und Höhe der*sourceShape* . |
| [InsertClone](../../aspose.slides/shapecollection/insertclone#insertclone_1)(int, IShape, float, float) | Fügt eine Kopie einer bestimmten Form an der angegebenen Position der Sammlung ein. Breite und Höhe der neuen Form sind gleich Breite und Höhe der*sourceShape* . |
| [InsertClone](../../aspose.slides/shapecollection/insertclone#insertclone_2)(int, IShape, float, float, float, float) | Fügt eine Kopie einer angegebenen Form an der angegebenen Position der Sammlung ein. |
| [InsertConnector](../../aspose.slides/shapecollection/insertconnector#insertconnector)(int, ShapeType, float, float, float, float) | Erstellt einen neuen Connector, optimiert ihn anhand der Standardvorlage und fügt ihn am angegebenen Index in die Sammlung ein. |
| [InsertConnector](../../aspose.slides/shapecollection/insertconnector#insertconnector_1)(int, ShapeType, float, float, float, float, bool) | Erstellt einen neuen Connector und fügt ihn am angegebenen Index in die Sammlung ein. |
| [InsertGroupShape](../../aspose.slides/shapecollection/insertgroupshape)(int) | Erstellt eine neue GroupShape und fügt sie am angegebenen Index in die Sammlung ein. Größe und Position des GroupShape-Rahmens werden an den Inhalt angepasst, wenn der GroupShape eine neue Form hinzugefügt wird. |
| [InsertOleObjectFrame](../../aspose.slides/shapecollection/insertoleobjectframe#insertoleobjectframe)(int, float, float, float, float, IOleEmbeddedDataInfo) | Erstellt ein neues OLE-Objekt und fügt es am angegebenen Index in eine Sammlung ein. |
| [InsertOleObjectFrame](../../aspose.slides/shapecollection/insertoleobjectframe#insertoleobjectframe_1)(int, float, float, float, float, string, string) | Erstellt ein neues OLE-Objekt und fügt es am angegebenen Index in eine Sammlung ein. |
| [InsertPictureFrame](../../aspose.slides/shapecollection/insertpictureframe)(int, ShapeType, float, float, float, float, IPPImage) | Erstellt einen neuen PictureFrame und fügt ihn am angegebenen Index in die Sammlung ein. |
| [InsertSectionZoomFrame](../../aspose.slides/shapecollection/insertsectionzoomframe#insertsectionzoomframe)(int, float, float, float, float, ISection) | Erstellt ein neues Abschnitts-Zoom-Objekt und fügt es am angegebenen Index in eine Sammlung ein. |
| [InsertSectionZoomFrame](../../aspose.slides/shapecollection/insertsectionzoomframe#insertsectionzoomframe_1)(int, float, float, float, float, ISection, IPPImage) | Erstellt ein neues Abschnitts-Zoom-Objekt und fügt es am angegebenen Index in eine Sammlung ein. |
| [InsertSummaryZoomFrame](../../aspose.slides/shapecollection/insertsummaryzoomframe)(int, float, float, float, float) | Erstellt ein neues Zusammenfassungs-Zoom-Objekt und fügt es am angegebenen Index in eine Sammlung ein. |
| [InsertTable](../../aspose.slides/shapecollection/inserttable)(int, float, float, double[], double[]) | Erstellt eine neue Tabelle und fügt sie am angegebenen Index in die Sammlung ein. |
| [InsertVideoFrame](../../aspose.slides/shapecollection/insertvideoframe)(int, float, float, float, float, string) | Erstellt einen neuen Videoframe und fügt ihn am angegebenen Index in eine Sammlung ein. |
| [InsertZoomFrame](../../aspose.slides/shapecollection/insertzoomframe#insertzoomframe)(int, float, float, float, float, ISlide) | Erstellt ein neues Zoom-Objekt und fügt es am angegebenen Index in eine Sammlung ein. |
| [InsertZoomFrame](../../aspose.slides/shapecollection/insertzoomframe#insertzoomframe_1)(int, float, float, float, float, ISlide, IPPImage) | Erstellt ein neues Zoom-Objekt und fügt es am angegebenen Index in eine Sammlung ein. |
| [Remove](../../aspose.slides/shapecollection/remove)(IShape) | Entfernt das erste Vorkommen einer bestimmten Form aus der Sammlung. |
| [RemoveAt](../../aspose.slides/shapecollection/removeat)(int) | Entfernt das Element am angegebenen Index der Sammlung. |
| [Reorder](../../aspose.slides/shapecollection/reorder#reorder)(int, IShape) | Verschiebt eine Form aus der Sammlung an die angegebene Position. |
| [Reorder](../../aspose.slides/shapecollection/reorder#reorder_1)(int, params IShape[]) | Verschiebt Formen aus der Sammlung an die angegebene Position. Formen werden ab dem Index in der Reihenfolge platziert, in der sie in der Liste erscheinen. |
| [ToArray](../../aspose.slides/shapecollection/toarray#toarray)() | Erstellt ein Array mit allen darin enthaltenen Formen und gibt es zurück. |
| [ToArray](../../aspose.slides/shapecollection/toarray#toarray_1)(int, int) | Erstellt ein Array mit allen Shapes aus dem angegebenen Bereich und gibt es zurück. Ein Index einer ersten zurückzugebenden Form.Eine Reihe von Formen, die zurückgegeben werden sollen. |

### Siehe auch

* class [DomObject&lt;TParent&gt;](../domobject-1)
* class [GroupShape](../groupshape)
* interface [IShapeCollection](../ishapecollection)
* namensraum [Aspose.Slides](../../aspose.slides)
* Montage [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
