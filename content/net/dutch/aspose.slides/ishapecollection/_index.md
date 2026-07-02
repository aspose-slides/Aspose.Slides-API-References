---
title: IShapeCollection
second_title: Aspose.Sildes voor .NET API-referentie
description: Representeert een verzameling vormen.
type: docs
weight: 6980
url: /nl/aspose.slides/ishapecollection/
---
## IShapeCollection interface

Representeert een verzameling vormen.

```csharp
public interface IShapeCollection : IGenericCollection<IShape>
```

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [Item](../../aspose.slides/ishapecollection/item) { get; } | Haalt het element op op de opgegeven index. Alleen-lezen [`IShape`](../ishape). |
| [ParentGroup](../../aspose.slides/ishapecollection/parentgroup) { get; } | Haalt het bovenliggende groepvormobject op voor de vormenverzameling. Alleen-lezen [`IGroupShape`](../igroupshape). |

## Methoden

| Naam | Beschrijving |
| --- | --- |
| [AddAudioFrameCD](../../aspose.slides/ishapecollection/addaudioframecd)(float, float, float, float) | Maakt een nieuw audio-frame gekoppeld aan een cd-track en voegt het toe aan het einde van de vormenverzameling. |
| [AddAudioFrameEmbedded](../../aspose.slides/ishapecollection/addaudioframeembedded#addaudioframeembedded)(float, float, float, float, IAudio) | Maakt een nieuw audio-frame en voegt het toe aan het einde van de vormenverzameling met een bestaand audio-object uit de Presentation.Audios-lijst. |
| [AddAudioFrameEmbedded](../../aspose.slides/ishapecollection/addaudioframeembedded#addaudioframeembedded_1)(float, float, float, float, Stream) | Maakt een nieuw audio-frame met een ingesloten WAV-bestand en voegt het toe aan het einde van de vormenverzameling. Het ingesloten audio-bestand wordt toegevoegd aan de Presentation.Audios-verzameling. |
| [AddAudioFrameLinked](../../aspose.slides/ishapecollection/addaudioframelinked)(float, float, float, float, string) | Maakt een nieuw audio-frame gekoppeld aan een extern audiobestand en voegt het toe aan het einde van de vormenverzameling. |
| [AddAutoShape](../../aspose.slides/ishapecollection/addautoshape#addautoshape)(ShapeType, float, float, float, float) | Maakt een nieuwe auto-vorm met standaardopmaak en voegt deze toe aan het einde van de vormenverzameling. |
| [AddAutoShape](../../aspose.slides/ishapecollection/addautoshape#addautoshape_1)(ShapeType, float, float, float, float, bool) | Maakt een nieuwe auto-vorm en voegt deze toe aan het einde van de vormenverzameling, eventueel met standaard-templates opmaak. |
| [AddChart](../../aspose.slides/ishapecollection/addchart#addchart)(ChartType, float, float, float, float) | Maakt een nieuw diagram, initialiseert met voorbeeld-seriedata en instellingen, en voegt het toe aan het einde van de vormenverzameling. |
| [AddChart](../../aspose.slides/ishapecollection/addchart#addchart_1)(ChartType, float, float, float, float, bool) | Maakt een nieuw diagram, initialiseert met voorbeeld-seriedata en instellingen, en voegt het toe aan het einde van de vormenverzameling. |
| [AddClone](../../aspose.slides/ishapecollection/addclone#addclone)(IShape) | Maakt een kopie van de opgegeven vorm en voegt deze toe aan het einde van de vormenverzameling. De gekloonde vorm behoudt de positie en grootte van het origineel. |
| [AddClone](../../aspose.slides/ishapecollection/addclone#addclone_1)(IShape, float, float) | Maakt een kopie van de opgegeven vorm en voegt deze toe aan het einde van de vormenverzameling. De nieuwe vorm behoudt de breedte en hoogte van de *sourceShape*. |
| [AddClone](../../aspose.slides/ishapecollection/addclone#addclone_2)(IShape, float, float, float, float) | Maakt een kopie van de opgegeven vorm en voegt deze toe aan het einde van de vormenverzameling. |
| [AddConnector](../../aspose.slides/ishapecollection/addconnector#addconnector)(ShapeType, float, float, float, float) | Maakt een nieuw verbindingsvorm met standaard-template-styling en voegt deze toe aan het einde van de vormenverzameling. |
| [AddConnector](../../aspose.slides/ishapecollection/addconnector#addconnector_1)(ShapeType, float, float, float, float, bool) | Maakt een nieuw verbindingsvorm en voegt deze toe aan het einde van de vormenverzameling, eventueel met standaard-template-styling. |
| [AddGroupShape](../../aspose.slides/ishapecollection/addgroupshape#addgroupshape)() | Maakt een nieuwe lege groepvorm en voegt deze toe aan het einde van de vormenverzameling. Het frame van de groep past zich automatisch aan om alle toegevoegde vormen te bevatten. |
| [AddGroupShape](../../aspose.slides/ishapecollection/addgroupshape#addgroupshape_1)(ISvgImage, float, float, float, float) | Maakt een nieuwe groepvorm, converteert de opgegeven SVG-afbeelding naar individuele vormen, en voegt de resulterende groep toe aan het einde van de vormenverzameling. |
| [AddMathShape](../../aspose.slides/ishapecollection/addmathshape)(float, float, float, float) | Maakt een nieuw rechthoekig auto-vorm om wiskundige inhoud te hosten en voegt deze toe aan het einde van de vormenverzameling. |
| [AddOleObjectFrame](../../aspose.slides/ishapecollection/addoleobjectframe#addoleobjectframe)(float, float, float, float, IOleEmbeddedDataInfo) | Maakt een nieuw OLE-objectframe en voegt dit toe aan het einde van de vormenverzameling. |
| [AddOleObjectFrame](../../aspose.slides/ishapecollection/addoleobjectframe#addoleobjectframe_1)(float, float, float, float, string, string) | Maakt een nieuw OLE-objectframe en voegt dit toe aan het einde van de vormenverzameling. |
| [AddPictureFrame](../../aspose.slides/ishapecollection/addpictureframe)(ShapeType, float, float, float, float, IPPImage) | Maakt een nieuw afbeeldingsframe met de opgegeven afbeelding en voegt dit toe aan het einde van de vormenverzameling. |
| [AddSectionZoomFrame](../../aspose.slides/ishapecollection/addsectionzoomframe#addsectionzoomframe)(float, float, float, float, ISection) | Maakt een nieuw Section-Zoom-frame en voegt dit toe aan het einde van de vormenverzameling. |
| [AddSectionZoomFrame](../../aspose.slides/ishapecollection/addsectionzoomframe#addsectionzoomframe_1)(float, float, float, float, ISection, IPPImage) | Maakt een nieuw Section-Zoom-frame met een vooraf gedefinieerde afbeelding en voegt dit toe aan het einde van de vormenverzameling. |
| [AddSmartArt](../../aspose.slides/ishapecollection/addsmartart)(float, float, float, float, SmartArtLayoutType) | Maakt een nieuw SmartArt-diagram en voegt dit toe aan het einde van de vormenverzameling. |
| [AddSummaryZoomFrame](../../aspose.slides/ishapecollection/addsummaryzoomframe)(float, float, float, float) | Maakt een nieuw Samenvatting-Zoom-frame en voegt dit toe aan het einde van de vormenverzameling. |
| [AddTable](../../aspose.slides/ishapecollection/addtable)(float, float, double[], double[]) | Maakt een nieuwe tabel en voegt deze toe aan het einde van de vormenverzameling. |
| [AddVideoFrame](../../aspose.slides/ishapecollection/addvideoframe#addvideoframe)(float, float, float, float, IVideo) | Maakt een nieuw video-frame en voegt dit toe aan het einde van de vormenverzameling. |
| [AddVideoFrame](../../aspose.slides/ishapecollection/addvideoframe#addvideoframe_1)(float, float, float, float, string) | Maakt een nieuw video-frame en voegt dit toe aan het einde van de vormenverzameling. |
| [AddZoomFrame](../../aspose.slides/ishapecollection/addzoomframe#addzoomframe)(float, float, float, float, ISlide) | Maakt een nieuw Zoom-frame en voegt dit toe aan het einde van de vormenverzameling. |
| [AddZoomFrame](../../aspose.slides/ishapecollection/addzoomframe#addzoomframe_1)(float, float, float, float, ISlide, IPPImage) | Maakt een nieuw Zoom-frame en voegt dit toe aan het einde van de vormenverzameling. |
| [Clear](../../aspose.slides/ishapecollection/clear)() | Verwijdert alle vormen uit de vormenverzameling. |
| [IndexOf](../../aspose.slides/ishapecollection/indexof)(IShape) | Retourneert de nulgebaseerde index van de eerste keer dat de opgegeven vorm in de collectie voorkomt. |
| [InsertAudioFrameCD](../../aspose.slides/ishapecollection/insertaudioframecd)(int, float, float, float, float) | Maakt een nieuw audio-frame gekoppeld aan een cd-track en voegt het in op de opgegeven index in de vormenverzameling. |
| [InsertAudioFrameEmbedded](../../aspose.slides/ishapecollection/insertaudioframeembedded#insertaudioframeembedded)(int, float, float, float, float, IAudio) | Maakt een nieuw audio-frame en voegt het in op de opgegeven index in de vormenverzameling met een bestaand audio-object uit de Presentation.Audios-lijst. |
| [InsertAudioFrameEmbedded](../../aspose.slides/ishapecollection/insertaudioframeembedded#insertaudioframeembedded_1)(int, float, float, float, float, Stream) | Maakt een nieuw audio-frame met een ingesloten WAV-bestand en voegt het in op de opgegeven index in de vormenverzameling. Het ingesloten audio-bestand wordt toegevoegd aan de Presentation.Audios-verzameling. |
| [InsertAudioFrameLinked](../../aspose.slides/ishapecollection/insertaudioframelinked)(int, float, float, float, float, string) | Maakt een nieuw audio-frame gekoppeld aan een extern audiobestand en voegt het in op de opgegeven index in de vormenverzameling. |
| [InsertAutoShape](../../aspose.slides/ishapecollection/insertautoshape#insertautoshape)(int, ShapeType, float, float, float, float) | Maakt een nieuwe auto-vorm en voegt deze in op de opgegeven index in de vormenverzameling met standaard-template-opmaak. |
| [InsertAutoShape](../../aspose.slides/ishapecollection/insertautoshape#insertautoshape_1)(int, ShapeType, float, float, float, float, bool) | Maakt een nieuwe auto-vorm en voegt deze in op de opgegeven index in de vormenverzameling, eventueel met standaard-template-styling. |
| [InsertChart](../../aspose.slides/ishapecollection/insertchart#insertchart)(ChartType, float, float, float, float, int) | Maakt een nieuw diagram, initialiseert met voorbeeld-seriedata en instellingen, en voegt het in op de opgegeven index in de vormenverzameling. |
| [InsertChart](../../aspose.slides/ishapecollection/insertchart#insertchart_1)(ChartType, float, float, float, float, int, bool) | Maakt een nieuw diagram, initialiseert met voorbeeld-seriedata en instellingen, en voegt het in op de opgegeven index in de vormenverzameling. |
| [InsertClone](../../aspose.slides/ishapecollection/insertclone#insertclone)(int, IShape) | Maakt een kopie van de opgegeven vorm en voegt deze in op de opgegeven index in de vormenverzameling. De gekloonde vorm behoudt de positie en grootte van het origineel. |
| [InsertClone](../../aspose.slides/ishapecollection/insertclone#insertclone_1)(int, IShape, float, float) | Maakt een kopie van de opgegeven vorm en voegt deze in op de opgegeven index in de vormenverzameling. De nieuwe vorm behoudt de breedte en hoogte van de *sourceShape*. |
| [InsertClone](../../aspose.slides/ishapecollection/insertclone#insertclone_2)(int, IShape, float, float, float, float) | Maakt een kopie van de opgegeven vorm en voegt deze in op de opgegeven index in de vormenverzameling. |
| [InsertConnector](../../aspose.slides/ishapecollection/insertconnector#insertconnector)(int, ShapeType, float, float, float, float) | Maakt een nieuw verbindingsvorm en voegt deze in op de opgegeven index in de vormenverzameling met standaard-template-styling. |
| [InsertConnector](../../aspose.slides/ishapecollection/insertconnector#insertconnector_1)(int, ShapeType, float, float, float, float, bool) | Maakt een nieuw verbindingsvorm en voegt deze in op de opgegeven index in de vormenverzameling, eventueel met standaard-template-styling. |
| [InsertGroupShape](../../aspose.slides/ishapecollection/insertgroupshape)(int) | Maakt een nieuwe lege groepvorm en voegt deze in op de opgegeven index in de vormenverzameling. Het frame van de groep past zich automatisch aan om alle toegevoegde vormen te bevatten. |
| [InsertOleObjectFrame](../../aspose.slides/ishapecollection/insertoleobjectframe#insertoleobjectframe)(int, float, float, float, float, IOleEmbeddedDataInfo) | Maakt een nieuw OLE-objectframe en voegt dit in op de opgegeven index in de vormenverzameling. |
| [InsertOleObjectFrame](../../aspose.slides/ishapecollection/insertoleobjectframe#insertoleobjectframe_1)(int, float, float, float, float, string, string) | Maakt een nieuw OLE-objectframe en voegt dit in op de opgegeven index in de vormenverzameling. |
| [InsertPictureFrame](../../aspose.slides/ishapecollection/insertpictureframe)(int, ShapeType, float, float, float, float, IPPImage) | Maakt een nieuw afbeeldingsframe met de opgegeven afbeelding en voegt dit in op de opgegeven index in de vormenverzameling. |
| [InsertSectionZoomFrame](../../aspose.slides/ishapecollection/insertsectionzoomframe#insertsectionzoomframe)(int, float, float, float, float, ISection) | Maakt een nieuw Section-Zoom-frame en voegt dit in op de opgegeven index in de vormenverzameling. |
| [InsertSectionZoomFrame](../../aspose.slides/ishapecollection/insertsectionzoomframe#insertsectionzoomframe_1)(int, float, float, float, float, ISection, IPPImage) | Maakt een nieuw Section-Zoom-frame met een vooraf gedefinieerde afbeelding en voegt dit in op de opgegeven index in de vormenverzameling. |
| [InsertSummaryZoomFrame](../../aspose.slides/ishapecollection/insertsummaryzoomframe)(int, float, float, float, float) | Maakt een nieuw Samenvatting-Zoom-frame en voegt dit in op de opgegeven index in de vormenverzameling. |
| [InsertTable](../../aspose.slides/ishapecollection/inserttable)(int, float, float, double[], double[]) | Maakt een nieuwe tabel en voegt deze in op de opgegeven index in de vormenverzameling. |
| [InsertVideoFrame](../../aspose.slides/ishapecollection/insertvideoframe)(int, float, float, float, float, string) | Maakt een nieuw video-frame en voegt dit in op de opgegeven index in de vormenverzameling. |
| [InsertZoomFrame](../../aspose.slides/ishapecollection/insertzoomframe#insertzoomframe)(int, float, float, float, float, ISlide) | Maakt een nieuw Zoom-frame en voegt dit in op de opgegeven index in de vormenverzameling. |
| [InsertZoomFrame](../../aspose.slides/ishapecollection/insertzoomframe#insertzoomframe_1)(int, float, float, float, float, ISlide, IPPImage) | Maakt een nieuw Zoom-frame met een vooraf gedefinieerde afbeelding en voegt dit in op de opgegeven index in de vormenverzameling. |
| [Remove](../../aspose.slides/ishapecollection/remove)(IShape) | Verwijdert de eerste verschijning van de opgegeven vorm uit de vormenverzameling. |
| [RemoveAt](../../aspose.slides/ishapecollection/removeat)(int) | Verwijdert de vorm op de opgegeven index uit de vormenverzameling. |
| [Reorder](../../aspose.slides/ishapecollection/reorder#reorder)(int, IShape) | Verplaatst de opgegeven vorm naar een nieuwe positie binnen de vormenverzameling. |
| [Reorder](../../aspose.slides/ishapecollection/reorder#reorder_1)(int, params IShape[]) | Verplaatst de opgegeven vormen binnen de vormenverzameling, beginnend bij de opgegeven index. |
| [ToArray](../../aspose.slides/ishapecollection/toarray#toarray)() | Maakt en retourneert een array die alle vormen bevat. |
| [ToArray](../../aspose.slides/ishapecollection/toarray#toarray_1)(int, int) | Maakt en retourneert een array die alle vormen in het opgegeven bereik bevat. |

### Zie ook

* interface [IGenericCollection&lt;T&gt;](../igenericcollection-1)
* interface [IShape](../ishape)
* namespace [Aspose.Slides](../../aspose.slides)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->