---
title: ShapeCollection
second_title: Aspose.Slides für .NET API Referenz
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
| [Count](../../aspose.slides/shapecollection/count) { get; } | Gibt die Anzahl der tatsächlich in der Sammlung enthaltenen Elemente zurück. Nur lesbarer Int32. |
| [IsSynchronized](../../aspose.slides/shapecollection/issynchronized) { get; } | Gibt einen Wert zurück, der angibt, ob der Zugriff auf die Sammlung synchronisiert ist (thread-sicher). Nur lesbarer Boolean. |
| [Item](../../aspose.slides/shapecollection/item) { get; } | Gibt das Element am angegebenen Index zurück. Nur lesbar [`IShape`](../ishape). |
| [ParentGroup](../../aspose.slides/shapecollection/parentgroup) { get; } | Gibt das übergeordnete GroupShape-Objekt für eine Sammlung von Formen zurück. Nur lesbar [`IGroupShape`](../igroupshape). |
| [SyncRoot](../../aspose.slides/shapecollection/syncroot) { get; } | Gibt eine Synchronisierungswurzel zurück. Nur lesbares Objekt. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [AddAudioFrameCD](../../aspose.slides/shapecollection/addaudioframecd)(float, float, float, float) | Fügt ein AudioFrame mit CD am Ende der Sammlung hinzu. |
| [AddAudioFrameEmbedded](../../aspose.slides/shapecollection/addaudioframeembedded#addaudioframeembedded)(float, float, float, float, IAudio) | Fügt ein neues AudioFrame mit eingebettetem Audiofile am Ende einer Sammlung hinzu. Es verwendet die Audiodatei aus der Presentation.Audios-Liste. |
| [AddAudioFrameEmbedded](../../aspose.slides/shapecollection/addaudioframeembedded#addaudioframeembedded_1)(float, float, float, float, Stream) | Fügt ein neues AudioFrame mit eingebettetem Audiofile am Ende einer Sammlung hinzu. Das eingebettete Audiofile kann nur ein WAV sein. Es fügt neues Audio in die Presentation.Audios-Liste ein. |
| [AddAudioFrameLinked](../../aspose.slides/shapecollection/addaudioframelinked)(float, float, float, float, string) | Fügt ein neues AudioFrame mit verknüpftem Audiofile am Ende einer Sammlung hinzu. |
| [AddAutoShape](../../aspose.slides/shapecollection/addautoshape#addautoshape)(ShapeType, float, float, float, float) | Erstellt eine neue AutoShape, passt sie vom Standardtemplate an und fügt sie am Ende der Sammlung hinzu. |
| [AddAutoShape](../../aspose.slides/shapecollection/addautoshape#addautoshape_1)(ShapeType, float, float, float, float, bool) | Erstellt eine neue AutoShape und fügt sie am Ende der Sammlung hinzu. |
| [AddChart](../../aspose.slides/shapecollection/addchart#addchart)(ChartType, float, float, float, float) | Erstellt ein neues Diagramm, initialisiert es mit Beispieldaten und -einstellungen und fügt es am Ende der Sammlung hinzu. |
| [AddChart](../../aspose.slides/shapecollection/addchart#addchart_1)(ChartType, float, float, float, float, bool) | Erstellt ein neues Diagramm und fügt es am Ende der Sammlung hinzu. |
| [AddClone](../../aspose.slides/shapecollection/addclone#addclone)(IShape) | Fügt eine Kopie einer bestimmten Form am Ende der Sammlung hinzu. X, Y, Breite und Höhe der neuen Form entsprechen X, Y, Breite und Höhe der *sourceShape*. |
| [AddClone](../../aspose.slides/shapecollection/addclone#addclone_1)(IShape, float, float) | Fügt eine Kopie einer bestimmten Form am Ende der Sammlung hinzu. Breite und Höhe der neuen Form entsprechen Breite und Höhe der *sourceShape*. |
| [AddClone](../../aspose.slides/shapecollection/addclone#addclone_2)(IShape, float, float, float, float) | Fügt eine Kopie einer bestimmten Form am Ende der Sammlung hinzu. |
| [AddConnector](../../aspose.slides/shapecollection/addconnector#addconnector)(ShapeType, float, float, float, float) | Erstellt einen neuen Connector, passt ihn vom Standardtemplate an und fügt ihn am Ende der Sammlung hinzu. |
| [AddConnector](../../aspose.slides/shapecollection/addconnector#addconnector_1)(ShapeType, float, float, float, float, bool) | Erstellt einen neuen Connector und fügt ihn am Ende der Sammlung hinzu. |
| [AddGroupShape](../../aspose.slides/shapecollection/addgroupshape#addgroupshape)() | Erstellt eine neue GroupShape und fügt sie am Ende der Sammlung hinzu. Die Größe und Position des GroupShape-Rahmens wird an den Inhalt angepasst, wenn eine neue Form in die GroupShape eingefügt wird. |
| [AddGroupShape](../../aspose.slides/shapecollection/addgroupshape#addgroupshape_1)(ISvgImage, float, float, float, float) | Erstellt eine neue GroupShape, füllt sie mit konvertierten Formen aus SVG und fügt sie am Ende der Sammlung hinzu. |
| [AddMathShape](../../aspose.slides/shapecollection/addmathshape)(float, float, float, float) | Erstellt eine neue Autoshape, die vom Standardtemplate für mathematischen Inhalt angepasst ist, und fügt sie am Ende der Sammlung hinzu. |
| [AddOleObjectFrame](../../aspose.slides/shapecollection/addoleobjectframe#addoleobjectframe)(float, float, float, float, IOleEmbeddedDataInfo) | Fügt ein neues OLE-Objekt am Ende einer Sammlung hinzu. |
| [AddOleObjectFrame](../../aspose.slides/shapecollection/addoleobjectframe#addoleobjectframe_1)(float, float, float, float, string, string) | Fügt ein neues OLE-Objekt am Ende einer Sammlung hinzu. |
| [AddPictureFrame](../../aspose.slides/shapecollection/addpictureframe)(ShapeType, float, float, float, float, IPPImage) | Erstellt einen neuen PictureFrame und fügt ihn am Ende der Sammlung hinzu. |
| [AddSectionZoomFrame](../../aspose.slides/shapecollection/addsectionzoomframe#addsectionzoomframe)(float, float, float, float, ISection) | Fügt ein neues Section Zoom-Objekt am Ende einer Sammlung hinzu. |
| [AddSectionZoomFrame](../../aspose.slides/shapecollection/addsectionzoomframe#addsectionzoomframe_1)(float, float, float, float, ISection, IPPImage) | Fügt ein neues Section Zoom-Objekt am Ende einer Sammlung mit einem vordefinierten Bild hinzu. |
| [AddSmartArt](../../aspose.slides/shapecollection/addsmartart)(float, float, float, float, SmartArtLayoutType) | Fügt ein SmartArt-Diagramm hinzu. |
| [AddSummaryZoomFrame](../../aspose.slides/shapecollection/addsummaryzoomframe)(float, float, float, float) | Fügt ein neues Summary Zoom-Objekt am Ende einer Sammlung hinzu. |
| [AddTable](../../aspose.slides/shapecollection/addtable)(float, float, double[], double[]) | Erstellt eine neue Tabelle und fügt sie am Ende der Sammlung hinzu. |
| [AddVideoFrame](../../aspose.slides/shapecollection/addvideoframe#addvideoframe)(float, float, float, float, IVideo) | Fügt einen neuen VideoFrame am Ende einer Sammlung hinzu. |
| [AddVideoFrame](../../aspose.slides/shapecollection/addvideoframe#addvideoframe_1)(float, float, float, float, string) | Fügt einen neuen VideoFrame am Ende einer Sammlung hinzu. |
| [AddZoomFrame](../../aspose.slides/shapecollection/addzoomframe#addzoomframe)(float, float, float, float, ISlide) | Fügt ein neues Zoom-Objekt am Ende einer Sammlung hinzu. |
| [AddZoomFrame](../../aspose.slides/shapecollection/addzoomframe#addzoomframe_1)(float, float, float, float, ISlide, IPPImage) | Fügt ein neues Zoom-Objekt am Ende einer Sammlung hinzu. |
| [Clear](../../aspose.slides/shapecollection/clear)() | Entfernt alle Formen aus der Sammlung. |
| [CopyTo](../../aspose.slides/shapecollection/copyto)(Array, int) | Kopiert alle Elemente aus der Sammlung in das angegebene Array. |
| [GetEnumerator](../../aspose.slides/shapecollection/getenumerator)() | Gibt einen Enumerator zurück, der durch die Sammlung iteriert. |
| [IndexOf](../../aspose.slides/shapecollection/indexof)(IShape) | Gibt den nullbasierten Index des ersten Vorkommens einer Form in der Sammlung zurück. |
| [InsertAudioFrameCD](../../aspose.slides/shapecollection/insertaudioframecd)(int, float, float, float, float) | Fügt ein AudioFrame mit CD ein. |
| [InsertAudioFrameEmbedded](../../aspose.slides/shapecollection/insertaudioframeembedded#insertaudioframeembedded)(int, float, float, float, float, IAudio) | Fügt ein AudioFrame mit eingebettetem Audiofile ein. Es verwendet die Audiodatei aus der Presentation.Audios-Liste. |
| [InsertAudioFrameEmbedded](../../aspose.slides/shapecollection/insertaudioframeembedded#insertaudioframeembedded_1)(int, float, float, float, float, Stream) | Fügt ein AudioFrame mit eingebettetem Audiofile ein. Das eingebettete Audiofile kann nur ein WAV sein. |
| [InsertAudioFrameLinked](../../aspose.slides/shapecollection/insertaudioframelinked)(int, float, float, float, float, string) | Erstellt ein neues AudioFrame mit verknüpftem Audiofile und fügt es an der angegebenen Stelle in die Sammlung ein. |
| [InsertAutoShape](../../aspose.slides/shapecollection/insertautoshape#insertautoshape)(int, ShapeType, float, float, float, float) | Erstellt eine neue AutoShape, passt sie vom Standardtemplate an und fügt sie an der angegebenen Stelle in die Sammlung ein. Hinweis: Der Typ der Form wird durch den Parameter shapeType bestimmt. |
| [InsertAutoShape](../../aspose.slides/shapecollection/insertautoshape#insertautoshape_1)(int, ShapeType, float, float, float, float, bool) | Erstellt eine neue AutoShape und fügt sie an der angegebenen Stelle in die Sammlung ein. Hinweis: Der Typ der Form wird durch den Parameter shapeType bestimmt. |
| [InsertChart](../../aspose.slides/shapecollection/insertchart#insertchart)(ChartType, float, float, float, float, int) | Erstellt ein neues Diagramm, initialisiert es mit Beispieldaten und -einstellungen und fügt es an der angegebenen Position in die Sammlung ein. |
| [InsertChart](../../aspose.slides/shapecollection/insertchart#insertchart_1)(ChartType, float, float, float, float, int, bool) | Erstellt ein neues Diagramm und fügt es an der angegebenen Position in die Sammlung ein. |
| [InsertClone](../../aspose.slides/shapecollection/insertclone#insertclone)(int, IShape) | Fügt eine Kopie einer bestimmten Form an einer bestimmten Position in die Sammlung ein. X, Y, Breite und Höhe der neuen Form entsprechen X, Y, Breite und Höhe der *sourceShape*. |
| [InsertClone](../../aspose.slides/shapecollection/insertclone#insertclone_1)(int, IShape, float, float) | Fügt eine Kopie einer bestimmten Form an einer bestimmten Position in die Sammlung ein. Breite und Höhe der neuen Form entsprechen Breite und Höhe der *sourceShape*. |
| [InsertClone](../../aspose.slides/shapecollection/insertclone#insertclone_2)(int, IShape, float, float, float, float) | Fügt eine Kopie einer bestimmten Form an einer bestimmten Position in die Sammlung ein. |
| [InsertConnector](../../aspose.slides/shapecollection/insertconnector#insertconnector)(int, ShapeType, float, float, float, float) | Erstellt einen neuen Connector, passt ihn vom Standardtemplate an und fügt ihn an der angegebenen Stelle in die Sammlung ein. |
| [InsertConnector](../../aspose.slides/shapecollection/insertconnector#insertconnector_1)(int, ShapeType, float, float, float, float, bool) | Erstellt einen neuen Connector und fügt ihn an der angegebenen Stelle in die Sammlung ein. |
| [InsertGroupShape](../../aspose.slides/shapecollection/insertgroupshape)(int) | Erstellt eine neue GroupShape und fügt sie an der angegebenen Stelle in die Sammlung ein. Die Größe und Position des GroupShape-Rahmens wird an den Inhalt angepasst, wenn eine neue Form in die GroupShape eingefügt wird. |
| [InsertOleObjectFrame](../../aspose.slides/shapecollection/insertoleobjectframe#insertoleobjectframe)(int, float, float, float, float, IOleEmbeddedDataInfo) | Erstellt ein neues OLE-Objekt und fügt es an der angegebenen Stelle in die Sammlung ein. |
| [InsertOleObjectFrame](../../aspose.slides/shapecollection/insertoleobjectframe#insertoleobjectframe_1)(int, float, float, float, float, string, string) | Erstellt ein neues OLE-Objekt und fügt es an der angegebenen Stelle in die Sammlung ein. |
| [InsertPictureFrame](../../aspose.slides/shapecollection/insertpictureframe)(int, ShapeType, float, float, float, float, IPPImage) | Erstellt einen neuen PictureFrame und fügt ihn an der angegebenen Stelle in die Sammlung ein. |
| [InsertSectionZoomFrame](../../aspose.slides/shapecollection/insertsectionzoomframe#insertsectionzoomframe)(int, float, float, float, float, ISection) | Erstellt ein neues Section Zoom-Objekt und fügt es an der angegebenen Stelle in die Sammlung ein. |
| [InsertSectionZoomFrame](../../aspose.slides/shapecollection/insertsectionzoomframe#insertsectionzoomframe_1)(int, float, float, float, float, ISection, IPPImage) | Erstellt ein neues Section Zoom-Objekt und fügt es an der angegebenen Stelle in die Sammlung ein. |
| [InsertSummaryZoomFrame](../../aspose.slides/shapecollection/insertsummaryzoomframe)(int, float, float, float, float) | Erstellt ein neues Summary Zoom-Objekt und fügt es an der angegebenen Stelle in die Sammlung ein. |
| [InsertTable](../../aspose.slides/shapecollection/inserttable)(int, float, float, double[], double[]) | Erstellt eine neue Tabelle und fügt sie an der angegebenen Stelle in die Sammlung ein. |
| [InsertVideoFrame](../../aspose.slides/shapecollection/insertvideoframe)(int, float, float, float, float, string) | Erstellt einen neuen VideoFrame und fügt ihn an der angegebenen Stelle in die Sammlung ein. |
| [InsertZoomFrame](../../aspose.slides/shapecollection/insertzoomframe#insertzoomframe)(int, float, float, float, float, ISlide) | Erstellt ein neues Zoom-Objekt und fügt es an der angegebenen Stelle in die Sammlung ein. |
| [InsertZoomFrame](../../aspose.slides/shapecollection/insertzoomframe#insertzoomframe_1)(int, float, float, float, float, ISlide, IPPImage) | Erstellt ein neues Zoom-Objekt und fügt es an der angegebenen Stelle in die Sammlung ein. |
| [Remove](../../aspose.slides/shapecollection/remove)(IShape) | Entfernt das erste Vorkommen einer bestimmten Form aus der Sammlung. |
| [RemoveAt](../../aspose.slides/shapecollection/removeat)(int) | Entfernt das Element am angegebenen Index der Sammlung. |
| [Reorder](../../aspose.slides/shapecollection/reorder#reorder)(int, IShape) | Verschiebt eine Form aus der Sammlung an die angegebene Position. |
| [Reorder](../../aspose.slides/shapecollection/reorder#reorder_1)(int, params IShape[]) | Verschiebt Formen aus der Sammlung an die angegebene Position. Die Formen werden beginnend ab dem Index in der Reihenfolge platziert, in der sie in der Liste erscheinen. |
| [ToArray](../../aspose.slides/shapecollection/toarray#toarray)() | Erstellt und gibt ein Array mit allen Formen darin zurück. |
| [ToArray](../../aspose.slides/shapecollection/toarray#toarray_1)(int, int) | Erstellt und gibt ein Array mit allen Formen aus dem angegebenen Bereich zurück. Ein Index der ersten zurückzugebenden Form. Eine Anzahl von Formen, die zurückgegeben werden sollen. |

### Siehe auch

* Klasse [DomObject&lt;TParent&gt;](../domobject-1)
* Klasse [GroupShape](../groupshape)
* Schnittstelle [IShapeCollection](../ishapecollection)
* Namespace [Aspose.Slides](../../aspose.slides)
* Assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->