---
title: ShapeCollection
second_title: Aspose.Sildes for .NET API-referentie
description: Representeert een collectie van vormen.
type: docs
weight: 9860
url: /nl/aspose.slides/shapecollection/
---
## ShapeCollection klasse

Representeert een collectie van vormen.

```csharp
public sealed class ShapeCollection : DomObject<GroupShape>, IShapeCollection
```

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [Count](../../aspose.slides/shapecollection/count) { get; } | Geeft het aantal elementen dat daadwerkelijk in de collectie is opgenomen. Alleen-lezen Int32. |
| [IsSynchronized](../../aspose.slides/shapecollection/issynchronized) { get; } | Retourneert een waarde die aangeeft of de toegang tot de collectie gesynchroniseerd is (thread-safe). Alleen-lezen Boolean. |
| [Item](../../aspose.slides/shapecollection/item) { get; } | Haalt het element op op de opgegeven index. Alleen-lezen [`IShape`](../ishape). |
| [ParentGroup](../../aspose.slides/shapecollection/parentgroup) { get; } | Haalt het bovenliggende groepsvormobject op voor de vormencollectie. Alleen-lezen [`IGroupShape`](../igroupshape). |
| [SyncRoot](../../aspose.slides/shapecollection/syncroot) { get; } | Retourneert een synchronisatiewortel. Alleen-lezen Object. |

## Methoden

| Naam | Beschrijving |
| --- | --- |
| [AddAudioFrameCD](../../aspose.slides/shapecollection/addaudioframecd)(float, float, float, float) | Maakt een nieuw audio-frame gekoppeld aan een cd-track en voegt het toe aan het einde van de vormencollectie. |
| [AddAudioFrameEmbedded](../../aspose.slides/shapecollection/addaudioframeembedded#addaudioframeembedded)(float, float, float, float, IAudio) | Maakt een nieuw audio-frame en voegt het toe aan het einde van de vormencollectie met een bestaand audio-object uit de Presentation.Audios-lijst. |
| [AddAudioFrameEmbedded](../../aspose.slides/shapecollection/addaudioframeembedded#addaudioframeembedded_1)(float, float, float, float, Stream) | Maakt een nieuw audio-frame met een ingesloten WAV-bestand en voegt het toe aan het einde van de vormencollectie. Het ingesloten audio-object wordt toegevoegd aan de Presentation.Audios-collectie. |
| [AddAudioFrameLinked](../../aspose.slides/shapecollection/addaudioframelinked)(float, float, float, float, string) | Maakt een nieuw audio-frame gekoppeld aan een extern audio-bestand en voegt het toe aan het einde van de vormencollectie. |
| [AddAutoShape](../../aspose.slides/shapecollection/addautoshape#addautoshape)(ShapeType, float, float, float, float) | Maakt een nieuwe auto-vorm met standaardopmaak en voegt deze toe aan het einde van de vormencollectie. |
| [AddAutoShape](../../aspose.slides/shapecollection/addautoshape#addautoshape_1)(ShapeType, float, float, float, float, bool) | Maakt een nieuwe auto-vorm en voegt deze toe aan het einde van de vormencollectie, eventueel met standaard-template-opmaak. |
| [AddChart](../../aspose.slides/shapecollection/addchart#addchart)(ChartType, float, float, float, float) | Maakt een nieuw diagram, initialiseert het met voorbeeld-seriedata en instellingen, en voegt het toe aan het einde van de vormencollectie. |
| [AddChart](../../aspose.slides/shapecollection/addchart#addchart_1)(ChartType, float, float, float, float, bool) | Maakt een nieuw diagram, initialiseert het met voorbeeld-seriedata en instellingen, en voegt het toe aan het einde van de vormencollectie. |
| [AddClone](../../aspose.slides/shapecollection/addclone#addclone)(IShape) | Maakt een kopie van de opgegeven vorm en voegt deze toe aan het einde van de vormencollectie. De gekloonde vorm behoudt de positie en grootte van het origineel. |
| [AddClone](../../aspose.slides/shapecollection/addclone#addclone_1)(IShape, float, float) | Maakt een kopie van de opgegeven vorm en voegt deze toe aan het einde van de vormencollectie. De nieuwe vorm behoudt de breedte en hoogte van de *sourceShape*. |
| [AddClone](../../aspose.slides/shapecollection/addclone#addclone_2)(IShape, float, float, float, float) | Maakt een kopie van de opgegeven vorm en voegt deze toe aan het einde van de vormencollectie. |
| [AddConnector](../../aspose.slides/shapecollection/addconnector#addconnector)(ShapeType, float, float, float, float) | Maakt een nieuw verbindingsvorm met standaard-template-styling en voegt het toe aan het einde van de vormencollectie. |
| [AddConnector](../../aspose.slides/shapecollection/addconnector#addconnector_1)(ShapeType, float, float, float, float, bool) | Maakt een nieuw verbindingsvorm en voegt het toe aan het einde van de vormencollectie, eventueel met standaard-template-styling. |
| [AddGroupShape](../../aspose.slides/shapecollection/addgroupshape#addgroupshape)() | Maakt een nieuwe lege groepsvorm en voegt deze toe aan het einde van de vormencollectie. Het frame van de groep wordt automatisch aangepast aan alle toegevoegde vormen. |
| [AddGroupShape](../../aspose.slides/shapecollection/addgroupshape#addgroupshape_1)(ISvgImage, float, float, float, float) | Maakt een nieuwe groepsvorm, zet de opgegeven SVG-afbeelding om in individuele vormen, en voegt de resulterende groep toe aan het einde van de vormencollectie. |
| [AddMathShape](../../aspose.slides/shapecollection/addmathshape)(float, float, float, float) | Maakt een nieuw rechthoekig auto-vorm om wiskundige inhoud te hosten en voegt deze toe aan het einde van de vormencollectie. |
| [AddOleObjectFrame](../../aspose.slides/shapecollection/addoleobjectframe#addoleobjectframe)(float, float, float, float, IOleEmbeddedDataInfo) | Maakt een nieuw OLE-object-frame en voegt het toe aan het einde van de vormencollectie. |
| [AddOleObjectFrame](../../aspose.slides/shapecollection/addoleobjectframe#addoleobjectframe_1)(float, float, float, float, string, string) | Maakt een nieuw OLE-object-frame en voegt het toe aan het einde van de vormencollectie. |
| [AddPictureFrame](../../aspose.slides/shapecollection/addpictureframe)(ShapeType, float, float, float, float, IPPImage) | Maakt een nieuw afbeelding-frame met de opgegeven afbeelding en voegt het toe aan het einde van de vormencollectie. |
| [AddSectionZoomFrame](../../aspose.slides/shapecollection/addsectionzoomframe#addsectionzoomframe)(float, float, float, float, ISection) | Maakt een nieuw Sectie-Zoom-frame en voegt het toe aan het einde van de vormencollectie. |
| [AddSectionZoomFrame](../../aspose.slides/shapecollection/addsectionzoomframe#addsectionzoomframe_1)(float, float, float, float, ISection, IPPImage) | Maakt een nieuw Sectie-Zoom-frame met een vooraf gedefinieerde afbeelding en voegt het toe aan het einde van de vormencollectie. |
| [AddSmartArt](../../aspose.slides/shapecollection/addsmartart)(float, float, float, float, SmartArtLayoutType) | Maakt een nieuw SmartArt-diagram en voegt het toe aan het einde van de vormencollectie. |
| [AddSummaryZoomFrame](../../aspose.slides/shapecollection/addsummaryzoomframe)(float, float, float, float) | Maakt een nieuw Samenvatting-Zoom-frame en voegt het toe aan het einde van de vormencollectie. |
| [AddTable](../../aspose.slides/shapecollection/addtable)(float, float, double[], double[]) | Maakt een nieuwe tabel en voegt deze toe aan het einde van de vormencollectie. |
| [AddVideoFrame](../../aspose.slides/shapecollection/addvideoframe#addvideoframe)(float, float, float, float, IVideo) | Maakt een nieuw video-frame en voegt het toe aan het einde van de vormencollectie. |
| [AddVideoFrame](../../aspose.slides/shapecollection/addvideoframe#addvideoframe_1)(float, float, float, float, string) | Maakt een nieuw video-frame en voegt het toe aan het einde van de vormencollectie. |
| [AddZoomFrame](../../aspose.slides/shapecollection/addzoomframe#addzoomframe)(float, float, float, float, ISlide) | Maakt een nieuw Zoom-frame en voegt het toe aan het einde van de vormencollectie. |
| [AddZoomFrame](../../aspose.slides/shapecollection/addzoomframe#addzoomframe_1)(float, float, float, float, ISlide, IPPImage) | Maakt een nieuw Zoom-frame en voegt het toe aan het einde van de vormencollectie. |
| [Clear](../../aspose.slides/shapecollection/clear)() | Verwijdert alle vormen uit de vormencollectie. |
| [CopyTo](../../aspose.slides/shapecollection/copyto)(Array, int) | Kopieert alle elementen uit de collectie naar de opgegeven array. |
| [GetEnumerator](../../aspose.slides/shapecollection/getenumerator)() | Retourneert een enumerator die door de collectie iterereert. |
| [IndexOf](../../aspose.slides/shapecollection/indexof)(IShape) | Retourneert de nul-gebaseerde index van de eerste voorkomen van de opgegeven vorm in de collectie. |
| [InsertAudioFrameCD](../../aspose.slides/shapecollection/insertaudioframecd)(int, float, float, float, float) | Maakt een nieuw audio-frame gekoppeld aan een cd-track en voegt het in op de opgegeven index in de vormencollectie. |
| [InsertAudioFrameEmbedded](../../aspose.slides/shapecollection/insertaudioframeembedded#insertaudioframeembedded)(int, float, float, float, float, IAudio) | Maakt een nieuw audio-frame en voegt het in op de opgegeven index in de vormencollectie met een bestaand audio-object uit de Presentation.Audios-lijst. |
| [InsertAudioFrameEmbedded](../../aspose.slides/shapecollection/insertaudioframeembedded#insertaudioframeembedded_1)(int, float, float, float, float, Stream) | Maakt een nieuw audio-frame met een ingesloten WAV-bestand en voegt het in op de opgegeven index in de vormencollectie. Het ingesloten audio-object wordt toegevoegd aan de Presentation.Audios-collectie. |
| [InsertAudioFrameLinked](../../aspose.slides/shapecollection/insertaudioframelinked)(int, float, float, float, float, string) | Maakt een nieuw audio-frame gekoppeld aan een extern audio-bestand en voegt het in op de opgegeven index in de vormencollectie. |
| [InsertAutoShape](../../aspose.slides/shapecollection/insertautoshape#insertautoshape)(int, ShapeType, float, float, float, float) | Maakt een nieuw auto-vorm en voegt het in op de opgegeven index in de vormencollectie met standaard-template-opmaak. |
| [InsertAutoShape](../../aspose.slides/shapecollection/insertautoshape#insertautoshape_1)(int, ShapeType, float, float, float, float, bool) | Maakt een nieuw auto-vorm en voegt het in op de opgegeven index in de vormencollectie, eventueel met standaard-template-styling. |
| [InsertChart](../../aspose.slides/shapecollection/insertchart#insertchart)(ChartType, float, float, float, float, int) | Maakt een nieuw diagram, initialiseert het met voorbeeld-seriedata en instellingen, en voegt het in op de opgegeven index in de vormencollectie. |
| [InsertChart](../../aspose.slides/shapecollection/insertchart#insertchart_1)(ChartType, float, float, float, float, int, bool) | Maakt een nieuw diagram, initialiseert het met voorbeeld-seriedata en instellingen, en voegt het in op de opgegeven index in de vormencollectie. |
| [InsertClone](../../aspose.slides/shapecollection/insertclone#insertclone)(int, IShape) | Maakt een kopie van de opgegeven vorm en voegt deze in op de opgegeven index in de vormencollectie. De gekloonde vorm behoudt de positie en grootte van het origineel. |
| [InsertClone](../../aspose.slides/shapecollection/insertclone#insertclone_1)(int, IShape, float, float) | Maakt een kopie van de opgegeven vorm en voegt deze in op de opgegeven index in de vormencollectie. De nieuwe vorm behoudt de breedte en hoogte van de *sourceShape*. |
| [InsertClone](../../aspose.slides/shapecollection/insertclone#insertclone_2)(int, IShape, float, float, float, float) | Maakt een kopie van de opgegeven vorm en voegt deze in op de opgegeven index in de vormencollectie. |
| [InsertConnector](../../aspose.slides/shapecollection/insertconnector#insertconnector)(int, ShapeType, float, float, float, float) | Maakt een nieuw verbindingsvorm en voegt het in op de opgegeven index in de vormencollectie met standaard-template-styling. |
| [InsertConnector](../../aspose.slides/shapecollection/insertconnector#insertconnector_1)(int, ShapeType, float, float, float, float, bool) | Maakt een nieuw verbindingsvorm en voegt het in op de opgegeven index in de vormencollectie, eventueel met standaard-template-styling. |
| [InsertGroupShape](../../aspose.slides/shapecollection/insertgroupshape)(int) | Maakt een nieuwe lege groepsvorm en voegt deze in op de opgegeven index in de vormencollectie. Het frame van de groep wordt automatisch aangepast aan alle toegevoegde vormen. |
| [InsertOleObjectFrame](../../aspose.slides/shapecollection/insertoleobjectframe#insertoleobjectframe)(int, float, float, float, float, IOleEmbeddedDataInfo) | Maakt een nieuw OLE-object-frame en voegt het in op de opgegeven index in de vormencollectie. |
| [InsertOleObjectFrame](../../aspose.slides/shapecollection/insertoleobjectframe#insertoleobjectframe_1)(int, float, float, float, float, string, string) | Maakt een nieuw OLE-object-frame en voegt het in op de opgegeven index in de vormencollectie. |
| [InsertPictureFrame](../../aspose.slides/shapecollection/insertpictureframe)(int, ShapeType, float, float, float, float, IPPImage) | Maakt een nieuw afbeelding-frame met de opgegeven afbeelding en voegt het in op de opgegeven index in de vormencollectie. |
| [InsertSectionZoomFrame](../../aspose.slides/shapecollection/insertsectionzoomframe#insertsectionzoomframe)(int, float, float, float, float, ISection) | Maakt een nieuw Sectie-Zoom-frame en voegt het in op de opgegeven index in de vormencollectie. |
| [InsertSectionZoomFrame](../../aspose.slides/shapecollection/insertsectionzoomframe#insertsectionzoomframe_1)(int, float, float, float, float, ISection, IPPImage) | Maakt een nieuw Sectie-Zoom-frame met een vooraf gedefinieerde afbeelding en voegt het in op de opgegeven index in de vormencollectie. |
| [InsertSummaryZoomFrame](../../aspose.slides/shapecollection/insertsummaryzoomframe)(int, float, float, float, float) | Maakt een nieuw Samenvatting-Zoom-frame en voegt het in op de opgegeven index in de vormencollectie. |
| [InsertTable](../../aspose.slides/shapecollection/inserttable)(int, float, float, double[], double[]) | Maakt een nieuwe tabel en voegt deze in op de opgegeven index in de vormencollectie. |
| [InsertVideoFrame](../../aspose.slides/shapecollection/insertvideoframe)(int, float, float, float, float, string) | Maakt een nieuw video-frame en voegt het in op de opgegeven index in de vormencollectie. |
| [InsertZoomFrame](../../aspose.slides/shapecollection/insertzoomframe#insertzoomframe)(int, float, float, float, float, ISlide) | Maakt een nieuw Zoom-frame en voegt het in op de opgegeven index in de vormencollectie. |
| [InsertZoomFrame](../../aspose.slides/shapecollection/insertzoomframe#insertzoomframe_1)(int, float, float, float, float, ISlide, IPPImage) | Maakt een nieuw Zoom-frame met een vooraf gedefinieerde afbeelding en voegt het in op de opgegeven index in de vormencollectie. |
| [Remove](../../aspose.slides/shapecollection/remove)(IShape) | Verwijdert het eerste voorkomen van de opgegeven vorm uit de vormencollectie. |
| [RemoveAt](../../aspose.slides/shapecollection/removeat)(int) | Verwijdert de vorm op de opgegeven index uit de vormencollectie. |
| [Reorder](../../aspose.slides/shapecollection/reorder#reorder)(int, IShape) | Verplaatst de opgegeven vorm naar een nieuwe positie binnen de vormencollectie. |
| [Reorder](../../aspose.slides/shapecollection/reorder#reorder_1)(int, params IShape[]) | Verplaatst de opgegeven vormen binnen de vormencollectie, beginnend op de opgegeven index. |
| [ToArray](../../aspose.slides/shapecollection/toarray#toarray)() | Maakt een array die alle vormen bevat en retourneert. |
| [ToArray](../../aspose.slides/shapecollection/toarray#toarray_1)(int, int) | Maakt een array die alle vormen in het opgegeven bereik bevat en retourneert. |

### Zie ook

* klasse [DomObject&lt;TParent&gt;](../domobject-1)
* klasse [GroupShape](../groupshape)
* interface [IShapeCollection](../ishapecollection)
* naamruimte [Aspose.Slides](../../aspose.slides)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->