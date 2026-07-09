---
title: IShapeCollection
second_title: Aspose.Sildes för .NET API-referens
description: Representerar en samling former.
type: docs
weight: 6980
url: /sv/aspose.slides/ishapecollection/
---
## IShapeCollection gränssnitt

Representerar en samling former.

```csharp
public interface IShapeCollection : IGenericCollection<IShape>
```

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [Item](../../aspose.slides/ishapecollection/item) { get; } | Hämtar elementet på angivet index. Endast läsning [`IShape`](../ishape). |
| [ParentGroup](../../aspose.slides/ishapecollection/parentgroup) { get; } | Hämtar föräldragrppsobjektet för samlingen av former. Endast läsning [`IGroupShape`](../igroupshape). |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [AddAudioFrameCD](../../aspose.slides/ishapecollection/addaudioframecd)(float, float, float, float) | Skapar en ny ljudram kopplad till ett CD-spår och lägger till den i slutet av formsamlingen. |
| [AddAudioFrameEmbedded](../../aspose.slides/ishapecollection/addaudioframeembedded#addaudioframeembedded)(float, float, float, float, IAudio) | Skapar en ny ljudram och lägger till den i slutet av formsamlingen med ett befintligt ljudobjekt från Presentation.Audios-listan. |
| [AddAudioFrameEmbedded](../../aspose.slides/ishapecollection/addaudioframeembedded#addaudioframeembedded_1)(float, float, float, float, Stream) | Skapar en ny ljudram med en inbäddad WAV-fil och lägger till den i slutet av formsamlingen. Den inbäddade ljudfilen läggs till i Presentation.Audios-samlingen. |
| [AddAudioFrameLinked](../../aspose.slides/ishapecollection/addaudioframelinked)(float, float, float, float, string) | Skapar en ny ljudram kopplad till en extern ljudfil och lägger till den i slutet av formsamlingen. |
| [AddAutoShape](../../aspose.slides/ishapecollection/addautoshape#addautoshape)(ShapeType, float, float, float, float) | Skapar en ny autoform med standardformatering och lägger till den i slutet av formsamlingen. |
| [AddAutoShape](../../aspose.slides/ishapecollection/addautoshape#addautoshape_1)(ShapeType, float, float, float, float, bool) | Skapar en ny autoform och lägger till den i slutet av formsamlingen, eventuellt med standardmallformat. |
| [AddChart](../../aspose.slides/ishapecollection/addchart#addchart)(ChartType, float, float, float, float) | Skapar ett nytt diagram, initierar det med exempeldata för serier och inställningar, och lägger till det i slutet av formsamlingen. |
| [AddChart](../../aspose.slides/ishapecollection/addchart#addchart_1)(ChartType, float, float, float, float, bool) | Skapar ett nytt diagram, initierar det med exempeldata för serier och inställningar, och lägger till det i slutet av formsamlingen. |
| [AddClone](../../aspose.slides/ishapecollection/addclone#addclone)(IShape) | Skapar en kopia av den angivna formen och lägger till den i slutet av formsamlingen. Den klonade formen behåller originalets position och storlek. |
| [AddClone](../../aspose.slides/ishapecollection/addclone#addclone_1)(IShape, float, float) | Skapar en kopia av den angivna formen och lägger till den i slutet av formsamlingen. Den nya formen behåller bredden och höjden på *sourceShape*. |
| [AddClone](../../aspose.slides/ishapecollection/addclone#addclone_2)(IShape, float, float, float, float) | Skapar en kopia av den angivna formen och lägger till den i slutet av formsamlingen. |
| [AddConnector](../../aspose.slides/ishapecollection/addconnector#addconnector)(ShapeType, float, float, float, float) | Skapar en ny anslutningsform med standardmallstil och lägger till den i slutet av formsamlingen. |
| [AddConnector](../../aspose.slides/ishapecollection/addconnector#addconnector_1)(ShapeType, float, float, float, float, bool) | Skapar en ny anslutningsform och lägger till den i slutet av formsamlingen, eventuellt med standardmallstil. |
| [AddGroupShape](../../aspose.slides/ishapecollection/addgroupshape#addgroupshape)() | Skapar en ny tom gruppform och lägger till den i slutet av formsamlingen. Gruppens ram anpassas automatiskt för att rymma alla former som läggs till. |
| [AddGroupShape](../../aspose.slides/ishapecollection/addgroupshape#addgroupshape_1)(ISvgImage, float, float, float, float) | Skapar en ny gruppform, konverterar den angivna SVG-bilden till enskilda former och lägger till den resulterande gruppen i slutet av formsamlingen. |
| [AddMathShape](../../aspose.slides/ishapecollection/addmathshape)(float, float, float, float) | Skapar en ny rektangulär autoform för att innehålla matematiskt innehåll och lägger till den i slutet av formsamlingen. |
| [AddOleObjectFrame](../../aspose.slides/ishapecollection/addoleobjectframe#addoleobjectframe)(float, float, float, float, IOleEmbeddedDataInfo) | Skapar en ny OLE-objektram och lägger till den i slutet av formsamlingen. |
| [AddOleObjectFrame](../../aspose.slides/ishapecollection/addoleobjectframe#addoleobjectframe_1)(float, float, float, float, string, string) | Skapar en ny OLE-objektram och lägger till den i slutet av formsamlingen. |
| [AddPictureFrame](../../aspose.slides/ishapecollection/addpictureframe)(ShapeType, float, float, float, float, IPPImage) | Skapar en ny bildram som innehåller den angivna bilden och lägger till den i slutet av formsamlingen. |
| [AddSectionZoomFrame](../../aspose.slides/ishapecollection/addsectionzoomframe#addsectionzoomframe)(float, float, float, float, ISection) | Skapar en ny Section Zoom-ram och lägger till den i slutet av formsamlingen. |
| [AddSectionZoomFrame](../../aspose.slides/ishapecollection/addsectionzoomframe#addsectionzoomframe_1)(float, float, float, float, ISection, IPPImage) | Skapar en ny Section Zoom-ram med en fördefinierad bild och lägger till den i slutet av formsamlingen. |
| [AddSmartArt](../../aspose.slides/ishapecollection/addsmartart)(float, float, float, float, SmartArtLayoutType) | Skapar ett SmartArt-diagram och lägger till det i slutet av formsamlingen. |
| [AddSummaryZoomFrame](../../aspose.slides/ishapecollection/addsummaryzoomframe)(float, float, float, float) | Skapar en ny Summary Zoom-ram och lägger till den i slutet av formsamlingen. |
| [AddTable](../../aspose.slides/ishapecollection/addtable)(float, float, double[], double[]) | Skapar en ny tabell och lägger till den i slutet av formsamlingen. |
| [AddVideoFrame](../../aspose.slides/ishapecollection/addvideoframe#addvideoframe)(float, float, float, float, IVideo) | Skapar en ny video-ram och lägger till den i slutet av formsamlingen. |
| [AddVideoFrame](../../aspose.slides/ishapecollection/addvideoframe#addvideoframe_1)(float, float, float, float, string) | Skapar en ny video-ram och lägger till den i slutet av formsamlingen. |
| [AddZoomFrame](../../aspose.slides/ishapecollection/addzoomframe#addzoomframe)(float, float, float, float, ISlide) | Skapar en ny Zoom-ram och lägger till den i slutet av formsamlingen. |
| [AddZoomFrame](../../aspose.slides/ishapecollection/addzoomframe#addzoomframe_1)(float, float, float, float, ISlide, IPPImage) | Skapar en ny Zoom-ram och lägger till den i slutet av formsamlingen. |
| [Clear](../../aspose.slides/ishapecollection/clear)() | Tar bort alla former från formsamlingen. |
| [IndexOf](../../aspose.slides/ishapecollection/indexof)(IShape) | Returnerar det nollbaserade indexet för den första förekomsten av den angivna formen i samlingen. |
| [InsertAudioFrameCD](../../aspose.slides/ishapecollection/insertaudioframecd)(int, float, float, float, float) | Skapar en ny ljudram kopplad till ett CD-spår och infogar den i formsamlingen på det angivna indexet. |
| [InsertAudioFrameEmbedded](../../aspose.slides/ishapecollection/insertaudioframeembedded#insertaudioframeembedded)(int, float, float, float, float, IAudio) | Skapar en ny ljudram och infogar den i formsamlingen på det angivna indexet med ett befintligt ljudobjekt från Presentation.Audios-listan. |
| [InsertAudioFrameEmbedded](../../aspose.slides/ishapecollection/insertaudioframeembedded#insertaudioframeembedded_1)(int, float, float, float, float, Stream) | Skapar en ny ljudram med en inbäddad WAV-fil och infogar den i formsamlingen på det angivna indexet. Den inbäddade ljudfilen läggs till i Presentation.Audios-samlingen. |
| [InsertAudioFrameLinked](../../aspose.slides/ishapecollection/insertaudioframelinked)(int, float, float, float, float, string) | Skapar en ny ljudram kopplad till en extern ljudfil och infogar den i formsamlingen på det angivna indexet. |
| [InsertAutoShape](../../aspose.slides/ishapecollection/insertautoshape#insertautoshape)(int, ShapeType, float, float, float, float) | Skapar en ny autoform och infogar den i formsamlingen på det angivna indexet med standardmallformat. |
| [InsertAutoShape](../../aspose.slides/ishapecollection/insertautoshape#insertautoshape_1)(int, ShapeType, float, float, float, float, bool) | Skapar en ny autoform och infogar den i formsamlingen på det angivna indexet, eventuellt med standardmallstil. |
| [InsertChart](../../aspose.slides/ishapecollection/insertchart#insertchart)(ChartType, float, float, float, float, int) | Skapar ett nytt diagram, initierar det med exempeldata för serier och inställningar, och infogar det i formsamlingen på det angivna indexet. |
| [InsertChart](../../aspose.slides/ishapecollection/insertchart#insertchart_1)(ChartType, float, float, float, float, int, bool) | Skapar ett nytt diagram, initierar det med exempeldata för serier och inställningar, och infogar det i formsamlingen på det angivna indexet. |
| [InsertClone](../../aspose.slides/ishapecollection/insertclone#insertclone)(int, IShape) | Skapar en kopia av den angivna formen och infogar den i formsamlingen på det angivna indexet. Den klonade formen behåller originalets position och storlek. |
| [InsertClone](../../aspose.slides/ishapecollection/insertclone#insertclone_1)(int, IShape, float, float) | Skapar en kopia av den angivna formen och infogar den i formsamlingen på det angivna indexet. Den nya formen behåller bredden och höjden på *sourceShape*. |
| [InsertClone](../../aspose.slides/ishapecollection/insertclone#insertclone_2)(int, IShape, float, float, float, float) | Skapar en kopia av den angivna formen och infogar den i formsamlingen på det angivna indexet. |
| [InsertConnector](../../aspose.slides/ishapecollection/insertconnector#insertconnector)(int, ShapeType, float, float, float, float) | Skapar en ny anslutningsform och infogar den i formsamlingen på det angivna indexet med standardmallstil. |
| [InsertConnector](../../aspose.slides/ishapecollection/insertconnector#insertconnector_1)(int, ShapeType, float, float, float, float, bool) | Skapar en ny anslutningsform och infogar den i formsamlingen på det angivna indexet, eventuellt med standardmallstil. |
| [InsertGroupShape](../../aspose.slides/ishapecollection/insertgroupshape)(int) | Skapar en ny tom gruppform och infogar den i formsamlingen på det angivna indexet. Gruppens ram anpassas automatiskt för att rymma alla former som läggs till. |
| [InsertOleObjectFrame](../../aspose.slides/ishapecollection/insertoleobjectframe#insertoleobjectframe)(int, float, float, float, float, IOleEmbeddedDataInfo) | Skapar en ny OLE-objektram och infogar den i formsamlingen på det angivna indexet. |
| [InsertOleObjectFrame](../../aspose.slides/ishapecollection/insertoleobjectframe#insertoleobjectframe_1)(int, float, float, float, float, string, string) | Skapar en ny OLE-objektram och infogar den i formsamlingen på det angivna indexet. |
| [InsertPictureFrame](../../aspose.slides/ishapecollection/insertpictureframe)(int, ShapeType, float, float, float, float, IPPImage) | Skapar en ny bildram som innehåller den angivna bilden och infogar den i formsamlingen på det angivna indexet. |
| [InsertSectionZoomFrame](../../aspose.slides/ishapecollection/insertsectionzoomframe#insertsectionzoomframe)(int, float, float, float, float, ISection) | Skapar en ny Section Zoom-ram och infogar den i formsamlingen på det angivna indexet. |
| [InsertSectionZoomFrame](../../aspose.slides/ishapecollection/insertsectionzoomframe#insertsectionzoomframe_1)(int, float, float, float, float, ISection, IPPImage) | Skapar en ny Section Zoom-ram med en fördefinierad bild och infogar den i formsamlingen på det angivna indexet. |
| [InsertSummaryZoomFrame](../../aspose.slides/ishapecollection/insertsummaryzoomframe)(int, float, float, float, float) | Skapar en ny Summary Zoom-ram och infogar den i formsamlingen på det angivna indexet. |
| [InsertTable](../../aspose.slides/ishapecollection/inserttable)(int, float, float, double[], double[]) | Skapar en ny tabell och infogar den i formsamlingen på det angivna indexet. |
| [InsertVideoFrame](../../aspose.slides/ishapecollection/insertvideoframe)(int, float, float, float, float, string) | Skapar en ny video-ram och infogar den i formsamlingen på det angivna indexet. |
| [InsertZoomFrame](../../aspose.slides/ishapecollection/insertzoomframe#insertzoomframe)(int, float, float, float, float, ISlide) | Skapar en ny Zoom-ram och infogar den i formsamlingen på det angivna indexet. |
| [InsertZoomFrame](../../aspose.slides/ishapecollection/insertzoomframe#insertzoomframe_1)(int, float, float, float, float, ISlide, IPPImage) | Skapar en ny Zoom-ram med en fördefinierad bild och infogar den i formsamlingen på det angivna indexet. |
| [Remove](../../aspose.slides/ishapecollection/remove)(IShape) | Tar bort den första förekomsten av den angivna formen från formsamlingen. |
| [RemoveAt](../../aspose.slides/ishapecollection/removeat)(int) | Tar bort formen på det angivna indexet från formsamlingen. |
| [Reorder](../../aspose.slides/ishapecollection/reorder#reorder)(int, IShape) | Flyttar den angivna formen till en ny position inom formsamlingen. |
| [Reorder](../../aspose.slides/ishapecollection/reorder#reorder_1)(int, params IShape[]) | Flyttar de angivna formerna inom formsamlingen, placerar dem med början på det angivna indexet. |
| [ToArray](../../aspose.slides/ishapecollection/toarray#toarray)() | Skapar och returnerar en array som innehåller alla former. |
| [ToArray](../../aspose.slides/ishapecollection/toarray#toarray_1)(int, int) | Skapar och returnerar en array som innehåller alla former i det angivna intervallet. |

### Se även

* gränssnitt [IGenericCollection&lt;T&gt;](../igenericcollection-1)
* gränssnitt [IShape](../ishape)
* namnrymd [Aspose.Slides](../../aspose.slides)
* samling [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->