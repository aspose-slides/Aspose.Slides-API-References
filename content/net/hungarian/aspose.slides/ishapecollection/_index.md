---
title: IShapeCollection
second_title: Aspose.Sildes a .NET-hez API hivatkozás
description: A formák gyűjteményét képviseli.
type: docs
weight: 6980
url: /hu/aspose.slides/ishapecollection/
---
## IShapeCollection interfész

A formák gyűjteményét képviseli.

```csharp
public interface IShapeCollection : IGenericCollection<IShape>
```

## Tulajdonságok

| Név | Leírás |
| --- | --- |
| [Item](../../aspose.slides/ishapecollection/item) { get; } | Lekéri az adott indexen lévő elemet. Csak olvasható [`IShape`](../ishape). |
| [ParentGroup](../../aspose.slides/ishapecollection/parentgroup) { get; } | Lekéri a formák gyűjteményéhez tartozó szülő csoport alakzat objektumot. Csak olvasható [`IGroupShape`](../igroupshape). |

## Metódusok

| Név | Leírás |
| --- | --- |
| [AddAudioFrameCD](../../aspose.slides/ishapecollection/addaudioframecd)(float, float, float, float) | Új audio keretet hoz létre, amely egy CD sávra hivatkozik, és a forma gyűjtemény végéhez adja hozzá. |
| [AddAudioFrameEmbedded](../../aspose.slides/ishapecollection/addaudioframeembedded#addaudioframeembedded)(float, float, float, float, IAudio) | Új audio keretet hoz létre, és a Presentation.Audios listából származó meglévő audio objektumot felhasználva adja hozzá a forma gyűjtemény végéhez. |
| [AddAudioFrameEmbedded](../../aspose.slides/ishapecollection/addaudioframeembedded#addaudioframeembedded_1)(float, float, float, float, Stream) | Új audio keretet hoz létre egy beágyazott WAV fájllal, és a forma gyűjtemény végéhez adja hozzá. A beágyazott audio a Presentation.Audios gyűjteményhez kerül. |
| [AddAudioFrameLinked](../../aspose.slides/ishapecollection/addaudioframelinked)(float, float, float, float, string) | Új audio keretet hoz létre egy külső audio fájlra hivatkozva, és a forma gyűjtemény végéhez adja hozzá. |
| [AddAutoShape](../../aspose.slides/ishapecollection/addautoshape#addautoshape)(ShapeType, float, float, float, float) | Új automatikus alakzatot hoz létre alapértelmezett formázással, és a forma gyűjtemény végéhez adja hozzá. |
| [AddAutoShape](../../aspose.slides/ishapecollection/addautoshape#addautoshape_1)(ShapeType, float, float, float, float, bool) | Új automatikus alakzatot hoz létre, és a forma gyűjtemény végéhez adja hozzá, opcionálisan alapértelmezett sablon formázással inicializálva. |
| [AddChart](../../aspose.slides/ishapecollection/addchart#addchart)(ChartType, float, float, float, float) | Új diagramot hoz létre, minta sorozat adatokat és beállításokat alkalmaz, és a forma gyűjtemény végéhez adja hozzá. |
| [AddChart](../../aspose.slides/ishapecollection/addchart#addchart_1)(ChartType, float, float, float, float, bool) | Új diagramot hoz létre, minta sorozat adatokat és beállításokat alkalmaz, és a forma gyűjtemény végéhez adja hozzá. |
| [AddClone](../../aspose.slides/ishapecollection/addclone#addclone)(IShape) | Létrehozza a megadott alakzat másolatát, és a forma gyűjtemény végéhez adja hozzá. A klónozott alakzat megtartja az eredeti pozícióját és méretét. |
| [AddClone](../../aspose.slides/ishapecollection/addclone#addclone_1)(IShape, float, float) | Létrehozza a megadott alakzat másolatát, és a forma gyűjtemény végéhez adja hozzá. Az új alakzat megtartja a *sourceShape* szélességét és magasságát. |
| [AddClone](../../aspose.slides/ishapecollection/addclone#addclone_2)(IShape, float, float, float, float) | Létrehozza a megadott alakzat másolatát, és a forma gyűjtemény végéhez adja hozzá. |
| [AddConnector](../../aspose.slides/ishapecollection/addconnector#addconnector)(ShapeType, float, float, float, float) | Új csatlakozó alakzatot hoz létre alapértelmezett sablon stílussal, és a forma gyűjtemény végéhez adja hozzá. |
| [AddConnector](../../aspose.slides/ishapecollection/addconnector#addconnector_1)(ShapeType, float, float, float, float, bool) | Új csatlakozó alakzatot hoz létre, és a forma gyűjtemény végéhez adja hozzá, opcionálisan alapértelmezett sablon stílust alkalmazva. |
| [AddGroupShape](../../aspose.slides/ishapecollection/addgroupshape#addgroupshape)() | Új üres csoport alakzatot hoz létre, és a forma gyűjtemény végéhez adja hozzá. A csoport kerete automatikusan igazodik az ahhoz hozzáadott alakzatokhoz. |
| [AddGroupShape](../../aspose.slides/ishapecollection/addgroupshape#addgroupshape_1)(ISvgImage, float, float, float, float) | Új csoport alakzatot hoz létre, átalakítja a megadott SVG képet önálló alakzatokká, és a keletkezett csoportot a forma gyűjtemény végéhez adja hozzá. |
| [AddMathShape](../../aspose.slides/ishapecollection/addmathshape)(float, float, float, float) | Új automatikus téglalap alakzatot hoz létre matematikai tartalom megjelenítéséhez, és a forma gyűjtemény végéhez adja hozzá. |
| [AddOleObjectFrame](../../aspose.slides/ishapecollection/addoleobjectframe#addoleobjectframe)(float, float, float, float, IOleEmbeddedDataInfo) | Új OLE objektum keretet hoz létre, és a forma gyűjtemény végéhez adja hozzá. |
| [AddOleObjectFrame](../../aspose.slides/ishapecollection/addoleobjectframe#addoleobjectframe_1)(float, float, float, float, string, string) | Új OLE objektum keretet hoz létre, és a forma gyűjtemény végéhez adja hozzá. |
| [AddPictureFrame](../../aspose.slides/ishapecollection/addpictureframe)(ShapeType, float, float, float, float, IPPImage) | Új kép keretet hoz létre a megadott képpel, és a forma gyűjtemény végéhez adja hozzá. |
| [AddSectionZoomFrame](../../aspose.slides/ishapecollection/addsectionzoomframe#addsectionzoomframe)(float, float, float, float, ISection) | Új Section Zoom keretet hoz létre, és a forma gyűjtemény végéhez adja hozzá. |
| [AddSectionZoomFrame](../../aspose.slides/ishapecollection/addsectionzoomframe#addsectionzoomframe_1)(float, float, float, float, ISection, IPPImage) | Új Section Zoom keretet hoz létre előre definiált képpel, és a forma gyűjtemény végéhez adja hozzá. |
| [AddSmartArt](../../aspose.slides/ishapecollection/addsmartart)(float, float, float, float, SmartArtLayoutType) | SmartArt diagramot hoz létre, és a forma gyűjtemény végéhez adja hozzá. |
| [AddSummaryZoomFrame](../../aspose.slides/ishapecollection/addsummaryzoomframe)(float, float, float, float) | Új Summary Zoom keretet hoz létre, és a forma gyűjtemény végéhez adja hozzá. |
| [AddTable](../../aspose.slides/ishapecollection/addtable)(float, float, double[], double[]) | Új táblázatot hoz létre, és a forma gyűjtemény végéhez adja hozzá. |
| [AddVideoFrame](../../aspose.slides/ishapecollection/addvideoframe#addvideoframe)(float, float, float, float, IVideo) | Új videó keretet hoz létre, és a forma gyűjtemény végéhez adja hozzá. |
| [AddVideoFrame](../../aspose.slides/ishapecollection/addvideoframe#addvideoframe_1)(float, float, float, float, string) | Új videó keretet hoz létre, és a forma gyűjtemény végéhez adja hozzá. |
| [AddZoomFrame](../../aspose.slides/ishapecollection/addzoomframe#addzoomframe)(float, float, float, float, ISlide) | Új Zoom keretet hoz létre, és a forma gyűjtemény végéhez adja hozzá. |
| [AddZoomFrame](../../aspose.slides/ishapecollection/addzoomframe#addzoomframe_1)(float, float, float, float, ISlide, IPPImage) | Új Zoom keretet hoz létre, és a forma gyűjtemény végéhez adja hozzá. |
| [Clear](../../aspose.slides/ishapecollection/clear)() | Eltávolítja az összes alakzatot a forma gyűjteményből. |
| [IndexOf](../../aspose.slides/ishapecollection/indexof)(IShape) | Visszaadja a megadott alakzat első előfordulásának nullától induló indexét a gyűjteményben. |
| [InsertAudioFrameCD](../../aspose.slides/ishapecollection/insertaudioframecd)(int, float, float, float, float) | Új audio keretet hoz létre, amely egy CD sávra hivatkozik, és a megadott indexen szúrja be a forma gyűjteménybe. |
| [InsertAudioFrameEmbedded](../../aspose.slides/ishapecollection/insertaudioframeembedded#insertaudioframeembedded)(int, float, float, float, float, IAudio) | Új audio keretet hoz létre, és a meglévő audio objektumot felhasználva szúrja be a forma gyűjteménybe a megadott indexen. |
| [InsertAudioFrameEmbedded](../../aspose.slides/ishapecollection/insertaudioframeembedded#insertaudioframeembedded_1)(int, float, float, float, float, Stream) | Új audio keretet hoz létre beágyazott WAV fájllal, és a megadott indexen szúrja be a forma gyűjteménybe. A beágyazott audio a Presentation.Audios gyűjteményhez kerül. |
| [InsertAudioFrameLinked](../../aspose.slides/ishapecollection/insertaudioframelinked)(int, float, float, float, float, string) | Új audio keretet hoz létre egy külső audio fájlra hivatkozva, és a megadott indexen szúrja be a forma gyűjteménybe. |
| [InsertAutoShape](../../aspose.slides/ishapecollection/insertautoshape#insertautoshape)(int, ShapeType, float, float, float, float) | Új automatikus alakzatot hoz létre, és a megadott indexen szúrja be a forma gyűjteménybe, alapértelmezett sablon formázással. |
| [InsertAutoShape](../../aspose.slides/ishapecollection/insertautoshape#insertautoshape_1)(int, ShapeType, float, float, float, float, bool) | Új automatikus alakzatot hoz létre, és a megadott indexen szúrja be a forma gyűjteménybe, opcionálisan alapértelmezett sablon stílussal. |
| [InsertChart](../../aspose.slides/ishapecollection/insertchart#insertchart)(ChartType, float, float, float, float, int) | Új diagramot hoz létre, minta sorozat adatokat és beállításokat alkalmaz, és a megadott indexen szúrja be a forma gyűjteménybe. |
| [InsertChart](../../aspose.slides/ishapecollection/insertchart#insertchart_1)(ChartType, float, float, float, float, int, bool) | Új diagramot hoz létre, minta sorozat adatokat és beállításokat alkalmaz, és a megadott indexen szúrja be a forma gyűjteménybe. |
| [InsertClone](../../aspose.slides/ishapecollection/insertclone#insertclone)(int, IShape) | Létrehozza a megadott alakzat másolatát, és a megadott indexen szúrja be a forma gyűjteménybe. A klónozott alakzat megtartja az eredeti pozícióját és méretét. |
| [InsertClone](../../aspose.slides/ishapecollection/insertclone#insertclone_1)(int, IShape, float, float) | Létrehozza a megadott alakzat másolatát, és a megadott indexen szúrja be a forma gyűjteménybe. Az új alakzat megtartja a *sourceShape* szélességét és magasságát. |
| [InsertClone](../../aspose.slides/ishapecollection/insertclone#insertclone_2)(int, IShape, float, float, float, float) | Létrehozza a megadott alakzat másolatát, és a megadott indexen szúrja be a forma gyűjteménybe. |
| [InsertConnector](../../aspose.slides/ishapecollection/insertconnector#insertconnector)(int, ShapeType, float, float, float, float) | Új csatlakozó alakzatot hoz létre, és a megadott indexen szúrja be a forma gyűjteménybe, alapértelmezett sablon stílussal. |
| [InsertConnector](../../aspose.slides/ishapecollection/insertconnector#insertconnector_1)(int, ShapeType, float, float, float, float, bool) | Új csatlakozó alakzatot hoz létre, és a megadott indexen szúrja be a forma gyűjteménybe, opcionálisan alapértelmezett sablon stílussal. |
| [InsertGroupShape](../../aspose.slides/ishapecollection/insertgroupshape)(int) | Új üres csoport alakzatot hoz létre, és a megadott indexen szúrja be a forma gyűjteménybe. A csoport kerete automatikusan igazodik az ahhoz hozzáadott alakzatokhoz. |
| [InsertOleObjectFrame](../../aspose.slides/ishapecollection/insertoleobjectframe#insertoleobjectframe)(int, float, float, float, float, IOleEmbeddedDataInfo) | Új OLE objektum keretet hoz létre, és a megadott indexen szúrja be a forma gyűjteménybe. |
| [InsertOleObjectFrame](../../aspose.slides/ishapecollection/insertoleobjectframe#insertoleobjectframe_1)(int, float, float, float, float, string, string) | Új OLE objektum keretet hoz létre, és a megadott indexen szúrja be a forma gyűjteménybe. |
| [InsertPictureFrame](../../aspose.slides/ishapecollection/insertpictureframe)(int, ShapeType, float, float, float, float, IPPImage) | Új kép keretet hoz létre a megadott képpel, és a megadott indexen szúrja be a forma gyűjteménybe. |
| [InsertSectionZoomFrame](../../aspose.slides/ishapecollection/insertsectionzoomframe#insertsectionzoomframe)(int, float, float, float, float, ISection) | Új Section Zoom keretet hoz létre, és a megadott indexen szúrja be a forma gyűjteménybe. |
| [InsertSectionZoomFrame](../../aspose.slides/ishapecollection/insertsectionzoomframe#insertsectionzoomframe_1)(int, float, float, float, float, ISection, IPPImage) | Új Section Zoom keretet hoz létre előre definiált képpel, és a megadott indexen szúrja be a forma gyűjteménybe. |
| [InsertSummaryZoomFrame](../../aspose.slides/ishapecollection/insertsummaryzoomframe)(int, float, float, float, float) | Új Summary Zoom keretet hoz létre, és a megadott indexen szúrja be a forma gyűjteménybe. |
| [InsertTable](../../aspose.slides/ishapecollection/inserttable)(int, float, float, double[], double[]) | Új táblázatot hoz létre, és a megadott indexen szúrja be a forma gyűjteménybe. |
| [InsertVideoFrame](../../aspose.slides/ishapecollection/insertvideoframe)(int, float, float, float, float, string) | Új videó keretet hoz létre, és a megadott indexen szúrja be a forma gyűjteménybe. |
| [InsertZoomFrame](../../aspose.slides/ishapecollection/insertzoomframe#insertzoomframe)(int, float, float, float, float, ISlide) | Új Zoom keretet hoz létre, és a megadott indexen szúrja be a forma gyűjteménybe. |
| [InsertZoomFrame](../../aspose.slides/ishapecollection/insertzoomframe#insertzoomframe_1)(int, float, float, float, float, ISlide, IPPImage) | Új Zoom keretet hoz létre előre definiált képpel, és a megadott indexen szúrja be a forma gyűjteménybe. |
| [Remove](../../aspose.slides/ishapecollection/remove)(IShape) | Eltávolítja a megadott alakzat első előfordulását a forma gyűjteményből. |
| [RemoveAt](../../aspose.slides/ishapecollection/removeat)(int) | Eltávolítja a megadott indexen lévő alakzatot a forma gyűjteményből. |
| [Reorder](../../aspose.slides/ishapecollection/reorder#reorder)(int, IShape) | Áthelyezi a megadott alakzatot egy új pozícióba a forma gyűjteményen belül. |
| [Reorder](../../aspose.slides/ishapecollection/reorder#reorder_1)(int, params IShape[]) | Áthelyezi a megadott alakzatokat a forma gyűjteményben, a megadott indexnél kezdve helyezi el őket. |
| [ToArray](../../aspose.slides/ishapecollection/toarray#toarray)() | Létrehoz és visszaad egy tömböt, amely az összes alakzatot tartalmazza. |
| [ToArray](../../aspose.slides/ishapecollection/toarray#toarray_1)(int, int) | Létrehoz és visszaad egy tömböt, amely a megadott tartományban lévő összes alakzatot tartalmazza. |

### Lásd még

* interfész [IGenericCollection&lt;T&gt;](../igenericcollection-1)
* interfész [IShape](../ishape)
* névtér [Aspose.Slides](../../aspose.slides)
* összeállítás [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->