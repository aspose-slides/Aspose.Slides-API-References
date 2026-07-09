---
title: IShapeCollection
second_title: Aspose.Slides voor .NET API-referentie
description: Vertegenwoordigt een verzameling vormen.
type: docs
weight: 6980
url: /nl/aspose.slides/ishapecollection/
---
## IShapeCollection interface

Vertegenwoordigt een verzameling vormen.

```csharp
public interface IShapeCollection : IGenericCollection<IShape>
```

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [Item](../../aspose.slides/ishapecollection/item) { get; } | Haalt het element op op de opgegeven index. Alleen-lezen [`IShape`](../ishape). |
| [ParentGroup](../../aspose.slides/ishapecollection/parentgroup) { get; } | Haalt het bovenliggende groepvormobject op voor de vormverzameling. Alleen-lezen [`IGroupShape`](../igroupshape). |

## Methoden

| Naam | Beschrijving |
| --- | --- |
| [AddAudioFrameCD](../../aspose.slides/ishapecollection/addaudioframecd)(float, float, float, float) | Maakt een nieuw audioframe gekoppeld aan een cd-track en voegt het toe aan het einde van de vormverzameling. |
| [AddAudioFrameEmbedded](../../aspose.slides/ishapecollection/addaudioframeembedded#addaudioframeembedded)(float, float, float, float, IAudio) | Maakt een nieuw audioframe en voegt het toe aan het einde van de vormverzameling met een bestaand audio-object uit de Presentation.Audios-lijst. |
| [AddAudioFrameEmbedded](../../aspose.slides/ishapecollection/addaudioframeembedded#addaudioframeembedded_1)(float, float, float, float, Stream) | Maakt een nieuw audioframe met een ingesloten WAV-bestand en voegt het toe aan het einde van de vormverzameling. Het ingesloten audio-bestand wordt toegevoegd aan de Presentation.Audios-collectie. |
| [AddAudioFrameLinked](../../aspose.slides/ishapecollection/addaudioframelinked)(float, float, float, float, string) | Maakt een nieuw audioframe gekoppeld aan een extern audio-bestand en voegt het toe aan het einde van de vormverzameling. |
| [AddAutoShape](../../aspose.slides/ishapecollection/addautoshape#addautoshape)(ShapeType, float, float, float, float) | Maakt een nieuwe autoshape met standaardopmaak en voegt deze toe aan het einde van de vormverzameling. |
| [AddAutoShape](../../aspose.slides/ishapecollection/addautoshape#addautoshape_1)(ShapeType, float, float, float, float, bool) | Maakt een nieuwe autoshape en voegt deze toe aan het einde van de vormverzameling, eventueel initialiserend met de standaard sjabloonopmaak. |
| [AddChart](../../aspose.slides/ishapecollection/addchart#addchart)(ChartType, float, float, float, float) | Maakt een nieuw diagram, initialiseert het met voorbeeldreeksgegevens en instellingen, en voegt het toe aan het einde van de vormverzameling. |
| [AddChart](../../aspose.slides/ishapecollection/addchart#addchart_1)(ChartType, float, float, float, float, bool) | Maakt een nieuw diagram, initialiseert het met voorbeeldreeksgegevens en instellingen, en voegt het toe aan het einde van de vormverzameling, eventueel met standaard sjablooninstellingen. |
| [AddClone](../../aspose.slides/ishapecollection/addclone#addclone)(IShape) | Maakt een kopie van de opgegeven vorm en voegt deze toe aan het einde van de vormverzameling. De gekloonde vorm behoudt de positie en grootte van het origineel. |
| [AddClone](../../aspose.slides/ishapecollection/addclone#addclone_1)(IShape, float, float) | Maakt een kopie van de opgegeven vorm en voegt deze toe aan het einde van de vormverzameling. De nieuwe vorm behoudt de breedte en hoogte van de *sourceShape*. |
| [AddClone](../../aspose.slides/ishapecollection/addclone#addclone_2)(IShape, float, float, float, float) | Maakt een kopie van de opgegeven vorm en voegt deze toe aan het einde van de vormverzameling. |
| [AddConnector](../../aspose.slides/ishapecollection/addconnector#addconnector)(ShapeType, float, float, float, float) | Maakt een nieuwe verbindingsvorm met standaard sjabloonstyling en voegt deze toe aan het einde van de vormverzameling. |
| [AddConnector](../../aspose.slides/ishapecollection/addconnector#addconnector_1)(ShapeType, float, float, float, float, bool) | Maakt een nieuwe verbindingsvorm en voegt deze toe aan het einde van de vormverzameling, eventueel met standaard sjabloonstyling. |
| [AddGroupShape](../../aspose.slides/ishapecollection/addgroupshape#addgroupshape)() | Maakt een nieuwe lege groepsvorm en voegt deze toe aan het einde van de vormverzameling. Het frame van de groep past zich automatisch aan om alle toegevoegde vormen te bevatten. |
| [AddGroupShape](../../aspose.slides/ishapecollection/addgroupshape#addgroupshape_1)(ISvgImage, float, float, float, float) | Maakt een nieuwe groepsvorm, converteert de opgegeven SVG-afbeelding naar afzonderlijke vormen, en voegt de resulterende groep toe aan het einde van de vormverzameling. |
| [AddMathShape](../../aspose.slides/ishapecollection/addmathshape)(float, float, float, float) | Maakt een nieuwe rechthoekige autoshape voor wiskundige inhoud en voegt deze toe aan het einde van de vormverzameling. |
| [AddOleObjectFrame](../../aspose.slides/ishapecollection/addoleobjectframe#addoleobjectframe)(float, float, float, float, IOleEmbeddedDataInfo) | Maakt een nieuw OLE-objectframe en voegt het toe aan het einde van de vormverzameling. |
| [AddOleObjectFrame](../../aspose.slides/ishapecollection/addoleobjectframe#addoleobjectframe_1)(float, float, float, float, string, string) | Maakt een nieuw OLE-objectframe en voegt het toe aan het einde van de vormverzameling. |
| [AddPictureFrame](../../aspose.slides/ishapecollection/addpictureframe)(ShapeType, float, float, float, float, IPPImage) | Maakt een nieuw afbeeldingsframe met de opgegeven afbeelding en voegt het toe aan het einde van de vormverzameling. |
| [AddSectionZoomFrame](../../aspose.slides/ishapecollection/addsectionzoomframe#addsectionzoomframe)(float, float, float, float, ISection) | Maakt een nieuw Section-Zoom-frame en voegt het toe aan het einde van de vormverzameling. |
| [AddSectionZoomFrame](../../aspose.slides/ishapecollection/addsectionzoomframe#addsectionzoomframe_1)(float, float, float, float, ISection, IPPImage) | Maakt een nieuw Section-Zoom-frame met een vooraf gedefinieerde afbeelding en voegt het toe aan het einde van de vormverzameling. |
| [AddSmartArt](../../aspose.slides/ishapecollection/addsmartart)(float, float, float, float, SmartArtLayoutType) | Maakt een SmartArt-diagram en voegt het toe aan het einde van de vormverzameling. |
| [AddSummaryZoomFrame](../../aspose.slides/ishapecollection/addsummaryzoomframe)(float, float, float, float) | Maakt een nieuw Samenvatting-Zoom-frame en voegt het toe aan het einde van de vormverzameling. |
| [AddTable](../../aspose.slides/ishapecollection/addtable)(float, float, double[], double[]) | Maakt een nieuwe tabel en voegt deze toe aan het einde van de vormverzameling. |
| [AddVideoFrame](../../aspose.slides/ishapecollection/addvideoframe#addvideoframe)(float, float, float, float, IVideo) | Maakt een nieuw videoframe en voegt het toe aan het einde van de vormverzameling. |
| [AddVideoFrame](../../aspose.slides/ishapecollection/addvideoframe#addvideoframe_1)(float, float, float, float, string) | Maakt een nieuw videoframe en voegt het toe aan het einde van de vormverzameling. |
| [AddZoomFrame](../../aspose.slides/ishapecollection/addzoomframe#addzoomframe)(float, float, float, float, ISlide) | Maakt een nieuw Zoom-frame en voegt het toe aan het einde van de vormverzameling. |
| [AddZoomFrame](../../aspose.slides/ishapecollection/addzoomframe#addzoomframe_1)(float, float, float, float, ISlide, IPPImage) | Maakt een nieuw Zoom-frame met een vooraf gedefinieerde afbeelding en voegt het toe aan het einde van de vormverzameling. |
| [Clear](../../aspose.slides/ishapecollection/clear)() | Verwijdert alle vormen uit de vormverzameling. |
| [IndexOf](../../aspose.slides/ishapecollection/indexof)(IShape) | Retourneert de nulgebaseerde index van de eerste voorkoming van de opgegeven vorm in de verzameling. |
| [InsertAudioFrameCD](../../aspose.slides/ishapecollection/insertaudioframecd)(int, float, float, float, float) | Maakt een nieuw audioframe gekoppeld aan een cd-track en voegt het in de vormverzameling in op de opgegeven index. |
| [InsertAudioFrameEmbedded](../../aspose.slides/ishapecollection/insertaudioframeembedded#insertaudioframeembedded)(int, float, float, float, float, IAudio) | Maakt een nieuw audioframe en voegt het in de vormverzameling in op de opgegeven index met een bestaand audio-object uit de Presentation.Audios-lijst. |
| [InsertAudioFrameEmbedded](../../aspose.slides/ishapecollection/insertaudioframeembedded#insertaudioframeembedded_1)(int, float, float, float, float, Stream) | Maakt een nieuw audioframe met een ingesloten WAV-bestand en voegt het in de vormverzameling in op de opgegeven index. Het ingesloten audio-bestand wordt toegevoegd aan de Presentation.Audios-collectie. |
| [InsertAudioFrameLinked](../../aspose.slides/ishapecollection/insertaudioframelinked)(int, float, float, float, float, string) | Maakt een nieuw audioframe gekoppeld aan een extern audio-bestand en voegt het in de vormverzameling in op de opgegeven index. |
| [InsertAutoShape](../../aspose.slides/ishapecollection/insertautoshape#insertautoshape)(int, ShapeType, float, float, float, float) | Maakt een nieuwe autoshape en voegt deze in de vormverzameling in op de opgegeven index, met standaard sjabloonopmaak. |
| [InsertAutoShape](../../aspose.slides/ishapecollection/insertautoshape#insertautoshape_1)(int, ShapeType, float, float, float, float, bool) | Maakt een nieuwe autoshape en voegt deze in de vormverzameling in op de opgegeven index, eventueel met standaard sjabloonstyling. |
| [InsertChart](../../aspose.slides/ishapecollection/insertchart#insertchart)(ChartType, float, float, float, float, int) | Maakt een nieuw diagram, initialiseert het met voorbeeldreeksgegevens en instellingen, en voegt het in de vormverzameling in op de opgegeven index. |
| [InsertChart](../../aspose.slides/ishapecollection/insertchart#insertchart_1)(ChartType, float, float, float, float, int, bool) | Maakt een nieuw diagram, initialiseert het met voorbeeldreeksgegevens en instellingen, en voegt het in de vormverzameling in op de opgegeven index, eventueel met standaard sjabloonstyling. |
| [InsertClone](../../aspose.slides/ishapecollection/insertclone#insertclone)(int, IShape) | Maakt een kopie van de opgegeven vorm en voegt deze in de vormverzameling in op de opgegeven index. De gekloonde vorm behoudt de positie en grootte van het origineel. |
| [InsertClone](../../aspose.slides/ishapecollection/insertclone#insertclone_1)(int, IShape, float, float) | Maakt een kopie van de opgegeven vorm en voegt deze in de vormverzameling in op de opgegeven index. De nieuwe vorm behoudt de breedte en hoogte van de *sourceShape*. |
| [InsertClone](../../aspose.slides/ishapecollection/insertclone#insertclone_2)(int, IShape, float, float, float, float) | Maakt een kopie van de opgegeven vorm en voegt deze in de vormverzameling in op de opgegeven index. |
| [InsertConnector](../../aspose.slides/ishapecollection/insertconnector#insertconnector)(int, ShapeType, float, float, float, float) | Maakt een nieuwe verbindingsvorm en voegt deze in de vormverzameling in op de opgegeven index, met standaard sjabloonstyling. |
| [InsertConnector](../../aspose.slides/ishapecollection/insertconnector#insertconnector_1)(int, ShapeType, float, float, float, float, bool) | Maakt een nieuwe verbindingsvorm en voegt deze in de vormverzameling in op de opgegeven index, eventueel met standaard sjabloonstyling. |
| [InsertGroupShape](../../aspose.slides/ishapecollection/insertgroupshape)(int) | Maakt een nieuwe lege groepsvorm en voegt deze in de vormverzameling in op de opgegeven index. Het frame van de groep past zich automatisch aan om alle toegevoegde vormen te bevatten. |
| [InsertOleObjectFrame](../../aspose.slides/ishapecollection/insertoleobjectframe#insertoleobjectframe)(int, float, float, float, float, IOleEmbeddedDataInfo) | Maakt een nieuw OLE-objectframe en voegt het in de vormverzameling in op de opgegeven index. |
| [InsertOleObjectFrame](../../aspose.slides/ishapecollection/insertoleobjectframe#insertoleobjectframe_1)(int, float, float, float, float, string, string) | Maakt een nieuw OLE-objectframe en voegt het in de vormverzameling in op de opgegeven index. |
| [InsertPictureFrame](../../aspose.slides/ishapecollection/insertpictureframe)(int, ShapeType, float, float, float, float, IPPImage) | Maakt een nieuw afbeeldingsframe met de opgegeven afbeelding en voegt het in de vormverzameling op de opgegeven index. |
| [InsertSectionZoomFrame](../../aspose.slides/ishapecollection/insertsectionzoomframe#insertsectionzoomframe)(int, float, float, float, float, ISection) | Maakt een nieuw Section-Zoom-frame en voegt het in de vormverzameling op de opgegeven index. |
| [InsertSectionZoomFrame](../../aspose.slides/ishapecollection/insertsectionzoomframe#insertsectionzoomframe_1)(int, float, float, float, float, ISection, IPPImage) | Maakt een nieuw Section-Zoom-frame met een vooraf gedefinieerde afbeelding en voegt het in de vormverzameling op de opgegeven index. |
| [InsertSummaryZoomFrame](../../aspose.slides/ishapecollection/insertsummaryzoomframe)(int, float, float, float, float) | Maakt een nieuw Samenvatting-Zoom-frame en voegt het in de vormverzameling op de opgegeven index. |
| [InsertTable](../../aspose.slides/ishapecollection/inserttable)(int, float, float, double[], double[]) | Maakt een nieuwe tabel en voegt deze in de vormverzameling op de opgegeven index. |
| [InsertVideoFrame](../../aspose.slides/ishapecollection/insertvideoframe)(int, float, float, float, float, string) | Maakt een nieuw videoframe en voegt het in de vormverzameling op de opgegeven index. |
| [InsertZoomFrame](../../aspose.slides/ishapecollection/insertzoomframe#insertzoomframe)(int, float, float, float, float, ISlide) | Maakt een nieuw Zoom-frame en voegt het in de vormverzameling op de opgegeven index. |
| [InsertZoomFrame](../../aspose.slides/ishapecollection/insertzoomframe#insertzoomframe_1)(int, float, float, float, float, ISlide, IPPImage) | Maakt een nieuw Zoom-frame met een vooraf gedefinieerde afbeelding en voegt het in de vormverzameling op de opgegeven index. |
| [Remove](../../aspose.slides/ishapecollection/remove)(IShape) | Verwijdert de eerste voorkoming van de opgegeven vorm uit de vormverzameling. |
| [RemoveAt](../../aspose.slides/ishapecollection/removeat)(int) | Verwijdert de vorm op de opgegeven index uit de vormverzameling. |
| [Reorder](../../aspose.slides/ishapecollection/reorder#reorder)(int, IShape) | Verplaatst de opgegeven vorm naar een nieuwe positie binnen de vormverzameling. |
| [Reorder](../../aspose.slides/ishapecollection/reorder#reorder_1)(int, params IShape[]) | Verplaatst de opgegeven vormen binnen de vormverzameling, beginnend op de opgegeven index. |
| [ToArray](../../aspose.slides/ishapecollection/toarray#toarray)() | Maakt en retourneert een array die alle vormen bevat. |
| [ToArray](../../aspose.slides/ishapecollection/toarray#toarray_1)(int, int) | Maakt en retourneert een array die alle vormen in het opgegeven bereik bevat. |

### Zie ook

* interface [IGenericCollection&lt;T&gt;](../igenericcollection-1)
* interface [IShape](../ishape)
* namespace [Aspose.Slides](../../aspose.slides)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->