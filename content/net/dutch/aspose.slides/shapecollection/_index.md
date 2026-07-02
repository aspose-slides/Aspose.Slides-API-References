---
title: ShapeCollection
second_title: Aspose.Slides voor .NET API-referentie
description: Stelt een collectie van shapes voor.
type: docs
weight: 9860
url: /nl/aspose.slides/shapecollection/
---
## ShapeCollection klasse

Stelt een collectie van shapes voor.

```csharp
public sealed class ShapeCollection : DomObject<GroupShape>, IShapeCollection
```

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [Count](../../aspose.slides/shapecollection/count) { get; } | Haalt het aantal elementen op dat daadwerkelijk in de collectie zit. Alleen-lezen Int32. |
| [IsSynchronized](../../aspose.slides/shapecollection/issynchronized) { get; } | Retourneert een waarde die aangeeft of de toegang tot de collectie gesynchroniseerd is (thread-safe). Alleen-lezen Boolean. |
| [Item](../../aspose.slides/shapecollection/item) { get; } | Haalt het element op op de opgegeven index. Alleen-lezen [`IShape`](../ishape). |
| [ParentGroup](../../aspose.slides/shapecollection/parentgroup) { get; } | Haalt het bovenliggende groep-shape-object op voor de shapes-collectie. Alleen-lezen [`IGroupShape`](../igroupshape). |
| [SyncRoot](../../aspose.slides/shapecollection/syncroot) { get; } | Retourneert een synchronisatiewortel. Alleen-lezen Object. |

## Methoden

| Naam | Beschrijving |
| --- | --- |
| [AddAudioFrameCD](../../aspose.slides/shapecollection/addaudioframecd)(float, float, float, float) | Maakt een nieuw audioframe gekoppeld aan een cd-track en voegt het toe aan het einde van de shape-collectie. |
| [AddAudioFrameEmbedded](../../aspose.slides/shapecollection/addaudioframeembedded#addaudioframeembedded)(float, float, float, float, IAudio) | Maakt een nieuw audioframe en voegt het toe aan het einde van de shape-collectie met gebruik van een bestaand audio-object uit de Presentation.Audios-lijst. |
| [AddAudioFrameEmbedded](../../aspose.slides/shapecollection/addaudioframeembedded#addaudioframeembedded_1)(float, float, float, float, Stream) | Maakt een nieuw audioframe met een ingebed WAV-bestand en voegt het toe aan het einde van de shape-collectie. Het ingebedde audio-bestand wordt toegevoegd aan de Presentation.Audios-collectie. |
| [AddAudioFrameLinked](../../aspose.slides/shapecollection/addaudioframelinked)(float, float, float, float, string) | Maakt een nieuw audioframe gekoppeld aan een extern audiobestand en voegt het toe aan het einde van de shape-collectie. |
| [AddAutoShape](../../aspose.slides/shapecollection/addautoshape#addautoshape)(ShapeType, float, float, float, float) | Maakt een nieuwe autoshape met standaardopmaak en voegt deze toe aan het einde van de shape-collectie. |
| [AddAutoShape](../../aspose.slides/shapecollection/addautoshape#addautoshape_1)(ShapeType, float, float, float, float, bool) | Maakt een nieuwe autoshape en voegt deze toe aan het einde van de shape-collectie, eventueel geïnitieerd met de standaard template-opmaak. |
| [AddChart](../../aspose.slides/shapecollection/addchart#addchart)(ChartType, float, float, float, float) | Maakt een nieuw diagram, initialiseert het met voorbeeld-seriedata en instellingen, en voegt het toe aan het einde van de shape-collectie. |
| [AddChart](../../aspose.slides/shapecollection/addchart#addchart_1)(ChartType, float, float, float, float, bool) | Maakt een nieuw diagram, initialiseert het met voorbeeld-seriedata en instellingen, en voegt het toe aan het einde van de shape-collectie. |
| [AddClone](../../aspose.slides/shapecollection/addclone#addclone)(IShape) | Maakt een kopie van de opgegeven shape en voegt deze toe aan het einde van de shape-collectie. De gekloonde shape behoudt de positie en grootte van het origineel. |
| [AddClone](../../aspose.slides/shapecollection/addclone#addclone_1)(IShape, float, float) | Maakt een kopie van de opgegeven shape en voegt deze toe aan het einde van de shape-collectie. De nieuwe shape behoudt de breedte en hoogte van de *sourceShape*. |
| [AddClone](../../aspose.slides/shapecollection/addclone#addclone_2)(IShape, float, float, float, float) | Maakt een kopie van de opgegeven shape en voegt deze toe aan het einde van de shape-collectie. |
| [AddConnector](../../aspose.slides/shapecollection/addconnector#addconnector)(ShapeType, float, float, float, float) | Maakt een nieuwe connector-shape met standaard template-styling en voegt deze toe aan het einde van de shape-collectie. |
| [AddConnector](../../aspose.slides/shapecollection/addconnector#addconnector_1)(ShapeType, float, float, float, float, bool) | Maakt een nieuwe connector-shape en voegt deze toe aan het einde van de shape-collectie, eventueel met standaard template-styling. |
| [AddGroupShape](../../aspose.slides/shapecollection/addgroupshape#addgroupshape)() | Maakt een nieuwe lege groep-shape en voegt deze toe aan het einde van de shape-collectie. Het frame van de groep wordt automatisch aangepast om toegevoegde shapes te bevatten. |
| [AddGroupShape](../../aspose.slides/shapecollection/addgroupshape#addgroupshape_1)(ISvgImage, float, float, float, float) | Maakt een nieuwe groep-shape, converteert de opgegeven SVG-afbeelding naar individuele shapes, en voegt de resulterende groep toe aan het einde van de shape-collectie. |
| [AddMathShape](../../aspose.slides/shapecollection/addmathshape)(float, float, float, float) | Maakt een nieuwe rechthoek-autoshape voor wiskundige inhoud en voegt deze toe aan het einde van de shape-collectie. |
| [AddOleObjectFrame](../../aspose.slides/shapecollection/addoleobjectframe#addoleobjectframe)(float, float, float, float, IOleEmbeddedDataInfo) | Maakt een nieuw OLE-objectframe en voegt het toe aan het einde van de shape-collectie. |
| [AddOleObjectFrame](../../aspose.slides/shapecollection/addoleobjectframe#addoleobjectframe_1)(float, float, float, float, string, string) | Maakt een nieuw OLE-objectframe en voegt het toe aan het einde van de shape-collectie. |
| [AddPictureFrame](../../aspose.slides/shapecollection/addpictureframe)(ShapeType, float, float, float, float, IPPImage) | Maakt een nieuw afbeelding-frame met de opgegeven afbeelding en voegt het toe aan het einde van de shape-collectie. |
| [AddSectionZoomFrame](../../aspose.slides/shapecollection/addsectionzoomframe#addsectionzoomframe)(float, float, float, float, ISection) | Maakt een nieuw Section Zoom-frame en voegt het toe aan het einde van de shape-collectie. |
| [AddSectionZoomFrame](../../aspose.slides/shapecollection/addsectionzoomframe#addsectionzoomframe_1)(float, float, float, float, ISection, IPPImage) | Maakt een nieuw Section Zoom-frame met een vooraf gedefinieerde afbeelding en voegt het toe aan het einde van de shape-collectie. |
| [AddSmartArt](../../aspose.slides/shapecollection/addsmartart)(float, float, float, float, SmartArtLayoutType) | Maakt een SmartArt-diagram en voegt het toe aan het einde van de shape-collectie. |
| [AddSummaryZoomFrame](../../aspose.slides/shapecollection/addsummaryzoomframe)(float, float, float, float) | Maakt een nieuw Summary Zoom-frame en voegt het toe aan het einde van de shape-collectie. |
| [AddTable](../../aspose.slides/shapecollection/addtable)(float, float, double[], double[]) | Maakt een nieuwe tabel en voegt deze toe aan het einde van de shape-collectie. |
| [AddVideoFrame](../../aspose.slides/shapecollection/addvideoframe#addvideoframe)(float, float, float, float, IVideo) | Maakt een nieuw video-frame en voegt het toe aan het einde van de shape-collectie. |
| [AddVideoFrame](../../aspose.slides/shapecollection/addvideoframe#addvideoframe_1)(float, float, float, float, string) | Maakt een nieuw video-frame en voegt het toe aan het einde van de shape-collectie. |
| [AddZoomFrame](../../aspose.slides/shapecollection/addzoomframe#addzoomframe)(float, float, float, float, ISlide) | Maakt een nieuw Zoom-frame en voegt het toe aan het einde van de shape-collectie. |
| [AddZoomFrame](../../aspose.slides/shapecollection/addzoomframe#addzoomframe_1)(float, float, float, float, ISlide, IPPImage) | Maakt een nieuw Zoom-frame en voegt het toe aan het einde van de shape-collectie. |
| [Clear](../../aspose.slides/shapecollection/clear)() | Verwijdert alle shapes uit de shape-collectie. |
| [CopyTo](../../aspose.slides/shapecollection/copyto)(Array, int) | Kopieert alle elementen van de collectie naar de opgegeven array. |
| [GetEnumerator](../../aspose.slides/shapecollection/getenumerator)() | Retourneert een enumerator die door de collectie iterereert. |
| [IndexOf](../../aspose.slides/shapecollection/indexof)(IShape) | Retourneert de nulgebaseerde index van de eerste instantie van de opgegeven shape in de collectie. |
| [InsertAudioFrameCD](../../aspose.slides/shapecollection/insertaudioframecd)(int, float, float, float, float) | Maakt een nieuw audioframe gekoppeld aan een cd-track en voegt het in de shape-collectie in op de opgegeven index. |
| [InsertAudioFrameEmbedded](../../aspose.slides/shapecollection/insertaudioframeembedded#insertaudioframeembedded)(int, float, float, float, float, IAudio) | Maakt een nieuw audioframe en voegt het in de shape-collectie in op de opgegeven index met gebruik van een bestaand audio-object uit de Presentation.Audios-lijst. |
| [InsertAudioFrameEmbedded](../../aspose.slides/shapecollection/insertaudioframeembedded#insertaudioframeembedded_1)(int, float, float, float, float, Stream) | Maakt een nieuw audioframe met een ingebed WAV-bestand en voegt het in de shape-collectie in op de opgegeven index. Het ingebedde audio-bestand wordt toegevoegd aan de Presentation.Audios-collectie. |
| [InsertAudioFrameLinked](../../aspose.slides/shapecollection/insertaudioframelinked)(int, float, float, float, float, string) | Maakt een nieuw audioframe gekoppeld aan een extern audiobestand en voegt het in de shape-collectie in op de opgegeven index. |
| [InsertAutoShape](../../aspose.slides/shapecollection/insertautoshape#insertautoshape)(int, ShapeType, float, float, float, float) | Maakt een nieuwe autoshape en voegt deze in de shape-collectie in op de opgegeven index, met toepassing van standaard template-opmaak. |
| [InsertAutoShape](../../aspose.slides/shapecollection/insertautoshape#insertautoshape_1)(int, ShapeType, float, float, float, float, bool) | Maakt een nieuwe autoshape en voegt deze in de shape-collectie in op de opgegeven index, eventueel geïnitieerd met de standaard template-styling. |
| [InsertChart](../../aspose.slides/shapecollection/insertchart#insertchart)(ChartType, float, float, float, float, int) | Maakt een nieuw diagram, initialiseert het met voorbeeld-seriedata en instellingen, en voegt het in de shape-collectie in op de opgegeven index. |
| [InsertChart](../../aspose.slides/shapecollection/insertchart#insertchart_1)(ChartType, float, float, float, float, int, bool) | Maakt een nieuw diagram, initialiseert het met voorbeeld-seriedata en instellingen, en voegt het in de shape-collectie in op de opgegeven index. |
| [InsertClone](../../aspose.slides/shapecollection/insertclone#insertclone)(int, IShape) | Maakt een kopie van de opgegeven shape en voegt deze in de shape-collectie in op de opgegeven index. De gekloonde shape behoudt de positie en grootte van het origineel. |
| [InsertClone](../../aspose.slides/shapecollection/insertclone#insertclone_1)(int, IShape, float, float) | Maakt een kopie van de opgegeven shape en voegt deze in de shape-collectie in op de opgegeven index. De nieuwe shape behoudt de breedte en hoogte van de *sourceShape*. |
| [InsertClone](../../aspose.slides/shapecollection/insertclone#insertclone_2)(int, IShape, float, float, float, float) | Maakt een kopie van de opgegeven shape en voegt deze in de shape-collectie in op de opgegeven index. |
| [InsertConnector](../../aspose.slides/shapecollection/insertconnector#insertconnector)(int, ShapeType, float, float, float, float) | Maakt een nieuwe connector-shape en voegt deze in de shape-collectie in op de opgegeven index, met toepassing van standaard template-styling. |
| [InsertConnector](../../aspose.slides/shapecollection/insertconnector#insertconnector_1)(int, ShapeType, float, float, float, float, bool) | Maakt een nieuwe connector-shape en voegt deze in de shape-collectie in op de opgegeven index, eventueel met standaard template-styling. |
| [InsertGroupShape](../../aspose.slides/shapecollection/insertgroupshape)(int) | Maakt een nieuwe lege groep-shape en voegt deze in de shape-collectie in op de opgegeven index. Het frame van de groep wordt automatisch aangepast om toegevoegde shapes te bevatten. |
| [InsertOleObjectFrame](../../aspose.slides/shapecollection/insertoleobjectframe#insertoleobjectframe)(int, float, float, float, float, IOleEmbeddedDataInfo) | Maakt een nieuw OLE-objectframe en voegt het in de shape-collectie in op de opgegeven index. |
| [InsertOleObjectFrame](../../aspose.slides/shapecollection/insertoleobjectframe#insertoleobjectframe_1)(int, float, float, float, float, string, string) | Maakt een nieuw OLE-objectframe en voegt het in de shape-collectie in op de opgegeven index. |
| [InsertPictureFrame](../../aspose.slides/shapecollection/insertpictureframe)(int, ShapeType, float, float, float, float, IPPImage) | Maakt een nieuw afbeelding-frame met de opgegeven afbeelding en voegt het in de shape-collectie in op de opgegeven index. |
| [InsertSectionZoomFrame](../../aspose.slides/shapecollection/insertsectionzoomframe#insertsectionzoomframe)(int, float, float, float, float, ISection) | Maakt een nieuw Section Zoom-frame en voegt het in de shape-collectie in op de opgegeven index. |
| [InsertSectionZoomFrame](../../aspose.slides/shapecollection/insertsectionzoomframe#insertsectionzoomframe_1)(int, float, float, float, float, ISection, IPPImage) | Maakt een nieuw Section Zoom-frame met een vooraf gedefinieerde afbeelding en voegt het in de shape-collectie in op de opgegeven index. |
| [InsertSummaryZoomFrame](../../aspose.slides/shapecollection/insertsummaryzoomframe)(int, float, float, float, float) | Maakt een nieuw Summary Zoom-frame en voegt het in de shape-collectie in op de opgegeven index. |
| [InsertTable](../../aspose.slides/shapecollection/inserttable)(int, float, float, double[], double[]) | Maakt een nieuwe tabel en voegt deze in de shape-collectie in op de opgegeven index. |
| [InsertVideoFrame](../../aspose.slides/shapecollection/insertvideoframe)(int, float, float, float, float, string) | Maakt een nieuw video-frame en voegt het in de shape-collectie in op de opgegeven index. |
| [InsertZoomFrame](../../aspose.slides/shapecollection/insertzoomframe#insertzoomframe)(int, float, float, float, float, ISlide) | Maakt een nieuw Zoom-frame en voegt het in de shape-collectie in op de opgegeven index. |
| [InsertZoomFrame](../../aspose.slides/shapecollection/insertzoomframe#insertzoomframe_1)(int, float, float, float, float, ISlide, IPPImage) | Maakt een nieuw Zoom-frame met een vooraf gedefinieerde afbeelding en voegt het in de shape-collectie in op de opgegeven index. |
| [Remove](../../aspose.slides/shapecollection/remove)(IShape) | Verwijdert de eerste instantie van de opgegeven shape uit de shape-collectie. |
| [RemoveAt](../../aspose.slides/shapecollection/removeat)(int) | Verwijdert de shape op de opgegeven index uit de shape-collectie. |
| [Reorder](../../aspose.slides/shapecollection/reorder#reorder)(int, IShape) | Verplaatst de opgegeven shape naar een nieuwe positie binnen de shape-collectie. |
| [Reorder](../../aspose.slides/shapecollection/reorder#reorder_1)(int, params IShape[]) | Verplaatst de opgegeven shapes binnen de shape-collectie, beginnend vanaf de opgegeven index. |
| [ToArray](../../aspose.slides/shapecollection/toarray#toarray)() | Maakt en retourneert een array die alle shapes bevat. |
| [ToArray](../../aspose.slides/shapecollection/toarray#toarray_1)(int, int) | Maakt en retourneert een array die alle shapes in het opgegeven bereik bevat. |

### Zie ook

* klasse [DomObject&lt;TParent&gt;](../domobject-1)
* klasse [GroupShape](../groupshape)
* interface [IShapeCollection](../ishapecollection)
* naamruimte [Aspose.Slides](../../aspose.slides)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->