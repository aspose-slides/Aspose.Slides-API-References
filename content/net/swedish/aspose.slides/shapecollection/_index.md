---
title: ShapeCollection
second_title: Aspose.Sildes för .NET API-referens
description: Representerar en samling former.
type: docs
weight: 9840
url: /sv/aspose.slides/shapecollection/
---
## ShapeCollection klass

Representerar en samling former.

```csharp
public sealed class ShapeCollection : DomObject<GroupShape>, IShapeCollection
```

## Egenskaper

| Name | Description |
| --- | --- |
| [Count](../../aspose.slides/shapecollection/count) { get; } | Hämtar antalet element som faktiskt finns i samlingen. Skrivskyddad Int32. |
| [IsSynchronized](../../aspose.slides/shapecollection/issynchronized) { get; } | Returnerar ett värde som indikerar om åtkomst till samlingen är synkroniserad (trådsäker). Skrivskyddad Boolean. |
| [Item](../../aspose.slides/shapecollection/item) { get; } | Hämtar elementet på det angivna indexet. Skrivskyddad [`IShape`](../ishape). |
| [ParentGroup](../../aspose.slides/shapecollection/parentgroup) { get; } | Hämtar det överordnade gruppform-objektet för samlingen av former. Skrivskyddad [`IGroupShape`](../igroupshape). |
| [SyncRoot](../../aspose.slides/shapecollection/syncroot) { get; } | Returnerar ett synkroniseringsrot. Skrivskyddad Object. |

## Metoder

| Name | Description |
| --- | --- |
| [AddAudioFrameCD](../../aspose.slides/shapecollection/addaudioframecd)(float, float, float, float) | Skapar en ny ljudram länkad till ett CD-spår och lägger till den i slutet av formsamlingen. |
| [AddAudioFrameEmbedded](../../aspose.slides/shapecollection/addaudioframeembedded#addaudioframeembedded)(float, float, float, float, IAudio) | Skapar en ny ljudram och lägger till den i slutet av formsamlingen med ett befintligt ljudobjekt från Presentation.Audios-listan. |
| [AddAudioFrameEmbedded](../../aspose.slides/shapecollection/addaudioframeembedded#addaudioframeembedded_1)(float, float, float, float, Stream) | Skapar en ny ljudram med en inbäddad WAV-fil och lägger till den i slutet av formsamlingen. Den inbäddade ljudfilen läggs till i Presentation.Audios-samlingen. |
| [AddAudioFrameLinked](../../aspose.slides/shapecollection/addaudioframelinked)(float, float, float, float, string) | Skapar en ny ljudram länkad till en extern ljudfil och lägger till den i slutet av formsamlingen. |
| [AddAutoShape](../../aspose.slides/shapecollection/addautoshape#addautoshape)(ShapeType, float, float, float, float) | Skapar en ny autoshape med standardformatering och lägger till den i slutet av formsamlingen. |
| [AddAutoShape](../../aspose.slides/shapecollection/addautoshape#addautoshape_1)(ShapeType, float, float, float, float, bool) | Skapar en ny autoshape och lägger till den i slutet av formsamlingen, alternativt initierar den med standardmallformatering. |
| [AddChart](../../aspose.slides/shapecollection/addchart#addchart)(ChartType, float, float, float, float) | Skapar ett nytt diagram, initierar det med exempeldata för serier och inställningar, och lägger till det i slutet av formsamlingen. |
| [AddChart](../../aspose.slides/shapecollection/addchart#addchart_1)(ChartType, float, float, float, float, bool) | Skapar ett nytt diagram, initierar det med exempeldata för serier och inställningar, och lägger till det i slutet av formsamlingen. |
| [AddClone](../../aspose.slides/shapecollection/addclone#addclone)(IShape) | Skapar en kopia av den angivna formen och lägger till den i slutet av formsamlingen. Den klonade formen behåller originalets position och storlek. |
| [AddClone](../../aspose.slides/shapecollection/addclone#addclone_1)(IShape, float, float) | Skapar en kopia av den angivna formen och lägger till den i slutet av formsamlingen. Den nya formen behåller bredden och höjden på *sourceShape*. |
| [AddClone](../../aspose.slides/shapecollection/addclone#addclone_2)(IShape, float, float, float, float) | Skapar en kopia av den angivna formen och lägger till den i slutet av formsamlingen. |
| [AddConnector](../../aspose.slides/shapecollection/addconnector#addconnector)(ShapeType, float, float, float, float) | Skapar en ny kopplingsform med standardmallstil och lägger till den i slutet av formsamlingen. |
| [AddConnector](../../aspose.slides/shapecollection/addconnector#addconnector_1)(ShapeType, float, float, float, float, bool) | Skapar en ny kopplingsform och lägger till den i slutet av formsamlingen, alternativt tillämpar standardmallstil. |
| [AddGroupShape](../../aspose.slides/shapecollection/addgroupshape#addgroupshape)() | Skapar en ny tom gruppform och lägger till den i slutet av formsamlingen. Gruppens ram justeras automatiskt för att passa alla former som läggs till. |
| [AddGroupShape](../../aspose.slides/shapecollection/addgroupshape#addgroupshape_1)(ISvgImage, float, float, float, float) | Skapar en ny gruppform, konverterar den angivna SVG-bilden till individuella former, och lägger till den resulterande gruppen i slutet av formsamlingen. |
| [AddMathShape](../../aspose.slides/shapecollection/addmathshape)(float, float, float, float) | Skapar en ny rektangulär autoshape för att innehålla matematikinnehåll och lägger till den i slutet av formsamlingen. |
| [AddOleObjectFrame](../../aspose.slides/shapecollection/addoleobjectframe#addoleobjectframe)(float, float, float, float, IOleEmbeddedDataInfo) | Skapar en ny OLE-objektram och lägger till den i slutet av formsamlingen. |
| [AddOleObjectFrame](../../aspose.slides/shapecollection/addoleobjectframe#addoleobjectframe_1)(float, float, float, float, string, string) | Skapar en ny OLE-objektram och lägger till den i slutet av formsamlingen. |
| [AddPictureFrame](../../aspose.slides/shapecollection/addpictureframe)(ShapeType, float, float, float, float, IPPImage) | Skapar en ny bildram som innehåller den angivna bilden och lägger till den i slutet av formsamlingen. |
| [AddSectionZoomFrame](../../aspose.slides/shapecollection/addsectionzoomframe#addsectionzoomframe)(float, float, float, float, ISection) | Skapar en ny Section Zoom-ram och lägger till den i slutet av formsamlingen. |
| [AddSectionZoomFrame](../../aspose.slides/shapecollection/addsectionzoomframe#addsectionzoomframe_1)(float, float, float, float, ISection, IPPImage) | Skapar en ny Section Zoom-ram med en fördefinierad bild och lägger till den i slutet av formsamlingen. |
| [AddSmartArt](../../aspose.slides/shapecollection/addsmartart)(float, float, float, float, SmartArtLayoutType) | Skapar ett SmartArt-diagram och lägger till det i slutet av formsamlingen. |
| [AddSummaryZoomFrame](../../aspose.slides/shapecollection/addsummaryzoomframe)(float, float, float, float) | Skapar en ny Summary Zoom-ram och lägger till den i slutet av formsamlingen. |
| [AddTable](../../aspose.slides/shapecollection/addtable)(float, float, double[], double[]) | Skapar en ny tabell och lägger till den i slutet av formsamlingen. |
| [AddVideoFrame](../../aspose.slides/shapecollection/addvideoframe#addvideoframe)(float, float, float, float, IVideo) | Skapar en ny videoram och lägger till den i slutet av formsamlingen. |
| [AddVideoFrame](../../aspose.slides/shapecollection/addvideoframe#addvideoframe_1)(float, float, float, float, string) | Skapar en ny videoram och lägger till den i slutet av formsamlingen. |
| [AddZoomFrame](../../aspose.slides/shapecollection/addzoomframe#addzoomframe)(float, float, float, float, ISlide) | Skapar en ny Zoom-ram och lägger till den i slutet av formsamlingen. |
| [AddZoomFrame](../../aspose.slides/shapecollection/addzoomframe#addzoomframe_1)(float, float, float, float, ISlide, IPPImage) | Skapar en ny Zoom-ram och lägger till den i slutet av formsamlingen. |
| [Clear](../../aspose.slides/shapecollection/clear)() | Tar bort alla former från formsamlingen. |
| [CopyTo](../../aspose.slides/shapecollection/copyto)(Array, int) | Kopierar alla element från samlingen till den angivna arrayen. |
| [GetEnumerator](../../aspose.slides/shapecollection/getenumerator)() | Returnerar en enumerator som itererar genom samlingen. |
| [IndexOf](../../aspose.slides/shapecollection/indexof)(IShape) | Returnerar det nollbaserade indexet för den första förekomsten av den angivna formen i samlingen. |
| [InsertAudioFrameCD](../../aspose.slides/shapecollection/insertaudioframecd)(int, float, float, float, float) | Skapar en ny ljudram länkad till ett CD-spår och infogar den i formsamlingen på det angivna indexet. |
| [InsertAudioFrameEmbedded](../../aspose.slides/shapecollection/insertaudioframeembedded#insertaudioframeembedded)(int, float, float, float, float, IAudio) | Skapar en ny ljudram och infogar den i formsamlingen på det angivna indexet med ett befintligt ljudobjekt från Presentation.Audios-listan. |
| [InsertAudioFrameEmbedded](../../aspose.slides/shapecollection/insertaudioframeembedded#insertaudioframeembedded_1)(int, float, float, float, float, Stream) | Skapar en ny ljudram med en inbäddad WAV-fil och infogar den i formsamlingen på det angivna indexet. Den inbäddade ljudfilen läggs till i Presentation.Audios-samlingen. |
| [InsertAudioFrameLinked](../../aspose.slides/shapecollection/insertaudioframelinked)(int, float, float, float, float, string) | Skapar en ny ljudram länkad till en extern ljudfil och infogar den i formsamlingen på det angivna indexet. |
| [InsertAutoShape](../../aspose.slides/shapecollection/insertautoshape#insertautoshape)(int, ShapeType, float, float, float, float) | Skapar en ny autoshape och infogar den i formsamlingen på det angivna indexet, med standardmallformatering. |
| [InsertAutoShape](../../aspose.slides/shapecollection/insertautoshape#insertautoshape_1)(int, ShapeType, float, float, float, float, bool) | Skapar en ny autoshape och infogar den i formsamlingen på det angivna indexet, alternativt initierar den med standardmallstil. |
| [InsertChart](../../aspose.slides/shapecollection/insertchart#insertchart)(ChartType, float, float, float, float, int) | Skapar ett nytt diagram, initierar det med exempeldata för serier och inställningar, och infogar det i formsamlingen på det angivna indexet. |
| [InsertChart](../../aspose.slides/shapecollection/insertchart#insertchart_1)(ChartType, float, float, float, float, int, bool) | Skapar ett nytt diagram, initierar det med exempeldata för serier och inställningar, och infogar det i formsamlingen på det angivna indexet. |
| [InsertClone](../../aspose.slides/shapecollection/insertclone#insertclone)(int, IShape) | Skapar en kopia av den angivna formen och infogar den i formsamlingen på det angivna indexet. Den klonade formen behåller originalets position och storlek. |
| [InsertClone](../../aspose.slides/shapecollection/insertclone#insertclone_1)(int, IShape, float, float) | Skapar en kopia av den angivna formen och infogar den i formsamlingen på det angivna indexet. Den nya formen behåller bredden och höjden på *sourceShape*. |
| [InsertClone](../../aspose.slides/shapecollection/insertclone#insertclone_2)(int, IShape, float, float, float, float) | Skapar en kopia av den angivna formen och infogar den i formsamlingen på det angivna indexet. |
| [InsertConnector](../../aspose.slides/shapecollection/insertconnector#insertconnector)(int, ShapeType, float, float, float, float) | Skapar en ny kopplingsform och infogar den i formsamlingen på det angivna indexet, med standardmallstil. |
| [InsertConnector](../../aspose.slides/shapecollection/insertconnector#insertconnector_1)(int, ShapeType, float, float, float, float, bool) | Skapar en ny kopplingsform och infogar den i formsamlingen på det angivna indexet, alternativt tillämpar standardmallstil. |
| [InsertGroupShape](../../aspose.slides/shapecollection/insertgroupshape)(int) | Skapar en ny tom gruppform och infogar den i formsamlingen på det angivna indexet. Gruppens ram justeras automatiskt för att passa alla former som läggs till. |
| [InsertOleObjectFrame](../../aspose.slides/shapecollection/insertoleobjectframe#insertoleobjectframe)(int, float, float, float, float, IOleEmbeddedDataInfo) | Skapar en ny OLE-objektram och infogar den i formsamlingen på det angivna indexet. |
| [InsertOleObjectFrame](../../aspose.slides/shapecollection/insertoleobjectframe#insertoleobjectframe_1)(int, float, float, float, float, string, string) | Skapar en ny OLE-objektram och infogar den i formsamlingen på det angivna indexet. |
| [InsertPictureFrame](../../aspose.slides/shapecollection/insertpictureframe)(int, ShapeType, float, float, float, float, IPPImage) | Skapar en ny bildram som innehåller den angivna bilden och infogar den i formsamlingen på det angivna indexet. |
| [InsertSectionZoomFrame](../../aspose.slides/shapecollection/insertsectionzoomframe#insertsectionzoomframe)(int, float, float, float, float, ISection) | Skapar en ny Section Zoom-ram och infogar den i formsamlingen på det angivna indexet. |
| [InsertSectionZoomFrame](../../aspose.slides/shapecollection/insertsectionzoomframe#insertsectionzoomframe_1)(int, float, float, float, float, ISection, IPPImage) | Skapar en ny Section Zoom-ram med en fördefinierad bild och infogar den i formsamlingen på det angivna indexet. |
| [InsertSummaryZoomFrame](../../aspose.slides/shapecollection/insertsummaryzoomframe)(int, float, float, float, float) | Skapar en ny Summary Zoom-ram och infogar den i formsamlingen på det angivna indexet. |
| [InsertTable](../../aspose.slides/shapecollection/inserttable)(int, float, float, double[], double[]) | Skapar en ny tabell och infogar den i formsamlingen på det angivna indexet. |
| [InsertVideoFrame](../../aspose.slides/shapecollection/insertvideoframe)(int, float, float, float, float, string) | Skapar en ny videoram och infogar den i formsamlingen på det angivna indexet. |
| [InsertZoomFrame](../../aspose.slides/shapecollection/insertzoomframe#insertzoomframe)(int, float, float, float, float, ISlide) | Skapar en ny Zoom-ram och infogar den i formsamlingen på det angivna indexet. |
| [InsertZoomFrame](../../aspose.slides/shapecollection/insertzoomframe#insertzoomframe_1)(int, float, float, float, float, ISlide, IPPImage) | Skapar en ny Zoom-ram med en fördefinierad bild och infogar den i formsamlingen på det angivna indexet. |
| [Remove](../../aspose.slides/shapecollection/remove)(IShape) | Tar bort den första förekomsten av den angivna formen från formsamlingen. |
| [RemoveAt](../../aspose.slides/shapecollection/removeat)(int) | Tar bort formen på det angivna indexet från formsamlingen. |
| [Reorder](../../aspose.slides/shapecollection/reorder#reorder)(int, IShape) | Flyttar den angivna formen till en ny position inom formsamlingen. |
| [Reorder](../../aspose.slides/shapecollection/reorder#reorder_1)(int, params IShape[]) | Flyttar de angivna formerna inom formsamlingen, placerar dem med start från det angivna indexet. |
| [ToArray](../../aspose.slides/shapecollection/toarray#toarray)() | Skapar och returnerar en array som innehåller alla former. |
| [ToArray](../../aspose.slides/shapecollection/toarray#toarray_1)(int, int) | Skapar och returnerar en array som innehåller alla former i det angivna intervallet. |

### Se också

* klass [DomObject&lt;TParent&gt;](../domobject-1)
* klass [GroupShape](../groupshape)
* gränssnitt [IShapeCollection](../ishapecollection)
* namnrymd [Aspose.Slides](../../aspose.slides)
* samling [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->