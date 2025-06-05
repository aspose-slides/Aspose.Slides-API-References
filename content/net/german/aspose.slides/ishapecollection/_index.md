---
title: IShapeCollection
second_title: Aspose.Slides für .NET API-Referenz
description: Stellt eine Sammlung von Formen dar.
type: docs
weight: 6760
url: /de/aspose.slides/ishapecollection/
---

## IShapeCollection-Schnittstelle

Stellt eine Sammlung von Formen dar.

```csharp
public interface IShapeCollection : IGenericCollection<IShape>
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [Item](../../aspose.slides/ishapecollection/item) { get; } | Gibt das Element am angegebenen Index zurück. Nur lesbar [`IShape`](../ishape). |
| [ParentGroup](../../aspose.slides/ishapecollection/parentgroup) { get; } | Gibt das übergeordnete GroupShape-Objekt für eine Formensammlung zurück. Nur lesbar [`IGroupShape`](../igroupshape). |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [AddAudioFrameCD](../../aspose.slides/ishapecollection/addaudioframecd)(float, float, float, float) | Fügt einen AudioFrame mit CD am Ende der Sammlung hinzu. |
| [AddAudioFrameEmbedded](../../aspose.slides/ishapecollection/addaudioframeembedded#addaudioframeembedded)(float, float, float, float, IAudio) | Fügt einen neuen AudioFrame mit eingebettetem Audiofile am Ende einer Sammlung hinzu. Es verwendet die Audiodatei aus der Liste Präsentation.Audios. |
| [AddAudioFrameEmbedded](../../aspose.slides/ishapecollection/addaudioframeembedded#addaudioframeembedded_1)(float, float, float, float, Stream) | Fügt einen neuen AudioFrame mit eingebettetem Audiofile am Ende einer Sammlung hinzu. Die eingebettete Audiodatei kann nur WAV sein. Es fügt neue Audios zur Liste Präsentation.Audios hinzu. |
| [AddAudioFrameLinked](../../aspose.slides/ishapecollection/addaudioframelinked)(float, float, float, float, string) | Fügt einen neuen AudioFrame mit verlinktem Audiofile am Ende einer Sammlung hinzu. |
| [AddAutoShape](../../aspose.slides/ishapecollection/addautoshape#addautoshape)(ShapeType, float, float, float, float) | Erstellt eine neue AutoShape, passt sie vom Standardtemplate an und fügt sie am Ende der Sammlung hinzu. |
| [AddAutoShape](../../aspose.slides/ishapecollection/addautoshape#addautoshape_1)(ShapeType, float, float, float, float, bool) | Erstellt eine neue AutoShape und fügt sie am Ende der Sammlung hinzu. |
| [AddChart](../../aspose.slides/ishapecollection/addchart#addchart)(ChartType, float, float, float, float) | Erstellt ein neues Diagramm, initialisiert es mit Beispielseriendaten und Einstellungen und fügt es am Ende der Sammlung hinzu. |
| [AddChart](../../aspose.slides/ishapecollection/addchart#addchart_1)(ChartType, float, float, float, float, bool) | Erstellt ein neues Diagramm und fügt es am Ende der Sammlung hinzu. |
| [AddClone](../../aspose.slides/ishapecollection/addclone#addclone)(IShape) | Fügt eine Kopie einer angegebenen Form am Ende der Sammlung hinzu. X, Y, Breite und Höhe der neuen Form entsprechen X, Y, Breite und Höhe der *sourceShape*. |
| [AddClone](../../aspose.slides/ishapecollection/addclone#addclone_1)(IShape, float, float) | Fügt eine Kopie einer angegebenen Form am Ende der Sammlung hinzu. Breite und Höhe der neuen Form entsprechen Breite und Höhe der *sourceShape*. |
| [AddClone](../../aspose.slides/ishapecollection/addclone#addclone_2)(IShape, float, float, float, float) | Fügt eine Kopie einer angegebenen Form am Ende der Sammlung hinzu. |
| [AddConnector](../../aspose.slides/ishapecollection/addconnector#addconnector)(ShapeType, float, float, float, float) | Erstellt einen neuen Connector, passt ihn vom Standardtemplate an und fügt ihn am Ende der Sammlung hinzu. |
| [AddConnector](../../aspose.slides/ishapecollection/addconnector#addconnector_1)(ShapeType, float, float, float, float, bool) | Erstellt einen neuen Connector und fügt ihn am Ende der Sammlung hinzu. |
| [AddGroupShape](../../aspose.slides/ishapecollection/addgroupshape#addgroupshape)() | Erstellt eine neue GroupShape und fügt sie am Ende der Sammlung hinzu. Die Größe und Position des GroupShape-Rahmens werden auf den Inhalt angepasst, wenn neue Formen in die GroupShape eingefügt werden. |
| [AddGroupShape](../../aspose.slides/ishapecollection/addgroupshape#addgroupshape_1)(ISvgImage, float, float, float, float) | Erstellt eine neue GroupShape, füllt sie mit konvertierten Formen aus SVG und fügt sie am Ende der Sammlung hinzu. |
| [AddMathShape](../../aspose.slides/ishapecollection/addmathshape)(float, float, float, float) | Erstellt eine neue AutoShape vom Typ Rechteck, um mathematische Inhalte darin unterzubringen, und fügt sie am Ende der Sammlung hinzu. |
| [AddOleObjectFrame](../../aspose.slides/ishapecollection/addoleobjectframe#addoleobjectframe)(float, float, float, float, IOleEmbeddedDataInfo) | Fügt ein neues OLE-Objekt am Ende einer Sammlung hinzu. |
| [AddOleObjectFrame](../../aspose.slides/ishapecollection/addoleobjectframe#addoleobjectframe_1)(float, float, float, float, string, string) | Fügt ein neues OLE-Objekt am Ende einer Sammlung hinzu. |
| [AddPictureFrame](../../aspose.slides/ishapecollection/addpictureframe)(ShapeType, float, float, float, float, IPPImage) | Erstellt einen neuen PictureFrame und fügt ihn am Ende der Sammlung hinzu. |
| [AddSectionZoomFrame](../../aspose.slides/ishapecollection/addsectionzoomframe#addsectionzoomframe)(float, float, float, float, ISection) | Fügt ein neues Abschnitts-Zoom-Objekt am Ende einer Sammlung hinzu. |
| [AddSectionZoomFrame](../../aspose.slides/ishapecollection/addsectionzoomframe#addsectionzoomframe_1)(float, float, float, float, ISection, IPPImage) | Fügt ein neues Abschnitts-Zoom-Objekt am Ende einer Sammlung mit einem vordefinierten Bild hinzu. |
| [AddSmartArt](../../aspose.slides/ishapecollection/addsmartart)(float, float, float, float, SmartArtLayoutType) | Fügt ein SmartArt-Diagramm hinzu. |
| [AddSummaryZoomFrame](../../aspose.slides/ishapecollection/addsummaryzoomframe)(float, float, float, float) | Fügt ein neues Zusammenfassungs-Zoom-Objekt am Ende einer Sammlung hinzu. |
| [AddTable](../../aspose.slides/ishapecollection/addtable)(float, float, double[], double[]) | Erstellt eine neue Tabelle und fügt sie am Ende der Sammlung hinzu. |
| [AddVideoFrame](../../aspose.slides/ishapecollection/addvideoframe#addvideoframe)(float, float, float, float, IVideo) | Fügt einen neuen VideoFrame am Ende einer Sammlung hinzu. |
| [AddVideoFrame](../../aspose.slides/ishapecollection/addvideoframe#addvideoframe_1)(float, float, float, float, string) | Fügt einen neuen VideoFrame am Ende einer Sammlung hinzu. |
| [AddZoomFrame](../../aspose.slides/ishapecollection/addzoomframe#addzoomframe)(float, float, float, float, ISlide) | Fügt ein neues Zoom-Objekt am Ende einer Sammlung hinzu. |
| [AddZoomFrame](../../aspose.slides/ishapecollection/addzoomframe#addzoomframe_1)(float, float, float, float, ISlide, IPPImage) | Fügt ein neues Zoom-Objekt am Ende einer Sammlung hinzu. |
| [Clear](../../aspose.slides/ishapecollection/clear)() | Entfernt alle Formen aus der Sammlung. |
| [IndexOf](../../aspose.slides/ishapecollection/indexof)(IShape) | Gibt den nullbasierten Index des ersten Vorkommens einer Form in der Sammlung zurück. |
| [InsertAudioFrameCD](../../aspose.slides/ishapecollection/insertaudioframecd)(int, float, float, float, float) | Fügt einen AudioFrame mit CD ein. |
| [InsertAudioFrameEmbedded](../../aspose.slides/ishapecollection/insertaudioframeembedded#insertaudioframeembedded)(int, float, float, float, float, IAudio) | Fügt einen AudioFrame mit eingebettetem Audiofile ein. Es verwendet die Audiodatei aus der Liste Präsentation.Audios. |
| [InsertAudioFrameEmbedded](../../aspose.slides/ishapecollection/insertaudioframeembedded#insertaudioframeembedded_1)(int, float, float, float, float, Stream) | Fügt einen AudioFrame mit eingebettetem Audiofile ein. Die eingebettete Audiodatei kann nur WAV sein. Es fügt neue Audios zur Liste Präsentation.Audios hinzu. |
| [InsertAudioFrameLinked](../../aspose.slides/ishapecollection/insertaudioframelinked)(int, float, float, float, float, string) | Erstellt einen neuen AudioFrame mit verlinktem Audiofile und fügt ihn an einer angegebenen Stelle in der Sammlung ein. |
| [InsertAutoShape](../../aspose.slides/ishapecollection/insertautoshape#insertautoshape)(int, ShapeType, float, float, float, float) | Erstellt eine neue AutoShape, passt sie vom Standardtemplate an und fügt sie an der angegebenen Stelle in der Sammlung ein. Hinweis: Der Typ der Form wird durch den Parameter shapeType bestimmt. |
| [InsertAutoShape](../../aspose.slides/ishapecollection/insertautoshape#insertautoshape_1)(int, ShapeType, float, float, float, float, bool) | Erstellt eine neue AutoShape und fügt sie an der angegebenen Stelle in der Sammlung ein. Hinweis: Der Typ der Form wird durch den Parameter shapeType bestimmt. |
| [InsertChart](../../aspose.slides/ishapecollection/insertchart#insertchart)(ChartType, float, float, float, float, int) | Erstellt ein neues Diagramm, initialisiert es mit Beispielseriendaten und Einstellungen und fügt es an der angegebenen Stelle in der Sammlung ein. |
| [InsertChart](../../aspose.slides/ishapecollection/insertchart#insertchart_1)(ChartType, float, float, float, float, int, bool) | Erstellt ein neues Diagramm und fügt es an der angegebenen Stelle in der Sammlung ein. |
| [InsertClone](../../aspose.slides/ishapecollection/insertclone#insertclone)(int, IShape) | Fügt eine Kopie einer angegebenen Form an der angegebenen Stelle in der Sammlung ein. X, Y, Breite und Höhe der neuen Form entsprechen X, Y, Breite und Höhe der *sourceShape*. |
| [InsertClone](../../aspose.slides/ishapecollection/insertclone#insertclone_1)(int, IShape, float, float) | Fügt eine Kopie einer angegebenen Form an der angegebenen Stelle in der Sammlung ein. Breite und Höhe der neuen Form entsprechen Breite und Höhe der *sourceShape*. |
| [InsertClone](../../aspose.slides/ishapecollection/insertclone#insertclone_2)(int, IShape, float, float, float, float) | Fügt eine Kopie einer angegebenen Form an der angegebenen Stelle in der Sammlung ein. |
| [InsertConnector](../../aspose.slides/ishapecollection/insertconnector#insertconnector)(int, ShapeType, float, float, float, float) | Erstellt einen neuen Connector, passt ihn vom Standardtemplate an und fügt ihn an der angegebenen Stelle in der Sammlung ein. |
| [InsertConnector](../../aspose.slides/ishapecollection/insertconnector#insertconnector_1)(int, ShapeType, float, float, float, float, bool) | Erstellt einen neuen Connector und fügt ihn an der angegebenen Stelle in der Sammlung ein. |
| [InsertGroupShape](../../aspose.slides/ishapecollection/insertgroupshape)(int) | Erstellt eine neue GroupShape und fügt sie an der angegebenen Stelle in der Sammlung ein. Die Größe und Position des GroupShape-Rahmens werden auf den Inhalt angepasst, wenn neue Formen in die GroupShape eingefügt werden. |
| [InsertOleObjectFrame](../../aspose.slides/ishapecollection/insertoleobjectframe#insertoleobjectframe)(int, float, float, float, float, IOleEmbeddedDataInfo) | Erstellt ein neues OLE-Objekt und fügt es an der angegebenen Stelle in einer Sammlung ein. |
| [InsertOleObjectFrame](../../aspose.slides/ishapecollection/insertoleobjectframe#insertoleobjectframe_1)(int, float, float, float, float, string, string) | Erstellt ein neues OLE-Objekt und fügt es an der angegebenen Stelle in einer Sammlung ein. |
| [InsertPictureFrame](../../aspose.slides/ishapecollection/insertpictureframe)(int, ShapeType, float, float, float, float, IPPImage) | Erstellt einen neuen PictureFrame und fügt ihn an der angegebenen Stelle in der Sammlung ein. |
| [InsertSectionZoomFrame](../../aspose.slides/ishapecollection/insertsectionzoomframe#insertsectionzoomframe)(int, float, float, float, float, ISection) | Erstellt ein neues Abschnitts-Zoom-Objekt und fügt es an der angegebenen Stelle in einer Sammlung ein. |
| [InsertSectionZoomFrame](../../aspose.slides/ishapecollection/insertsectionzoomframe#insertsectionzoomframe_1)(int, float, float, float, float, ISection, IPPImage) | Erstellt ein neues Abschnitts-Zoom-Objekt und fügt es an der angegebenen Stelle in einer Sammlung ein. |
| [InsertSummaryZoomFrame](../../aspose.slides/ishapecollection/insertsummaryzoomframe)(int, float, float, float, float) | Erstellt ein neues Zusammenfassungs-Zoom-Objekt und fügt es an der angegebenen Stelle in einer Sammlung ein. |
| [InsertTable](../../aspose.slides/ishapecollection/inserttable)(int, float, float, double[], double[]) | Erstellt eine neue Tabelle und fügt sie an der angegebenen Stelle in der Sammlung ein. |
| [InsertVideoFrame](../../aspose.slides/ishapecollection/insertvideoframe)(int, float, float, float, float, string) | Erstellt einen neuen VideoFrame und fügt ihn an der angegebenen Stelle in einer Sammlung ein. |
| [InsertZoomFrame](../../aspose.slides/ishapecollection/insertzoomframe#insertzoomframe)(int, float, float, float, float, ISlide) | Erstellt ein neues Zoom-Objekt und fügt es an der angegebenen Stelle in einer Sammlung ein. |
| [InsertZoomFrame](../../aspose.slides/ishapecollection/insertzoomframe#insertzoomframe_1)(int, float, float, float, float, ISlide, IPPImage) | Erstellt ein neues Zoom-Objekt und fügt es an der angegebenen Stelle in einer Sammlung ein. |
| [Remove](../../aspose.slides/ishapecollection/remove)(IShape) | Entfernt das erste Vorkommen einer bestimmten Form aus der Sammlung. |
| [RemoveAt](../../aspose.slides/ishapecollection/removeat)(int) | Entfernt das Element am angegebenen Index der Sammlung. |
| [Reorder](../../aspose.slides/ishapecollection/reorder#reorder)(int, IShape) | Verschiebt eine Form aus der Sammlung an die angegebene Position. |
| [Reorder](../../aspose.slides/ishapecollection/reorder#reorder_1)(int, params IShape[]) | Verschiebt Formen aus der Sammlung an die angegebene Position. Die Formen werden ab dem angegebenen Index in der Reihenfolge platziert, in der sie in der Liste erscheinen. |
| [ToArray](../../aspose.slides/ishapecollection/toarray#toarray)() | Erstellt und gibt ein Array mit allen Formen zurück. |
| [ToArray](../../aspose.slides/ishapecollection/toarray#toarray_1)(int, int) | Erstellt und gibt ein Array mit allen Formen aus dem angegebenen Bereich zurück. |

### Siehe auch

* Schnittstelle [IGenericCollection&lt;T&gt;](../igenericcollection-1)
* Schnittstelle [IShape](../ishape)
* Namespace [Aspose.Slides](../../aspose.slides)
* Assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->