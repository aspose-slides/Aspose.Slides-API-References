---
title: IShapeCollection
second_title: Aspose.Sildes .NET API referencia
description: A formákat tartalmazó gyűjteményt képviseli.
type: docs
weight: 6960
url: /hu/aspose.slides/ishapecollection/
---
## IShapeCollection interfész

Represents a collection of shapes.

```csharp
public interface IShapeCollection : IGenericCollection<IShape>
```

## Tulajdonságok

| Név | Leírás |
| --- | --- |
| [Item](../../aspose.slides/ishapecollection/item) { get; } | Visszaadja az elemet a megadott indexben. Csak olvasható [`IShape`](../ishape). |
| [ParentGroup](../../aspose.slides/ishapecollection/parentgroup) { get; } | Visszaadja a shapes gyűjtemény szülő csoport alakzat objektumát. Csak olvasható [`IGroupShape`](../igroupshape). |

## Metódusok

| Név | Leírás |
| --- | --- |
| [AddAudioFrameCD](../../aspose.slides/ishapecollection/addaudioframecd)(float, float, float, float) | Új audio keretet hoz létre, amely egy CD sávhoz kapcsolódik, és a shape gyűjtemény végére adja hozzá. |
| [AddAudioFrameEmbedded](../../aspose.slides/ishapecollection/addaudioframeembedded#addaudioframeembedded)(float, float, float, float, IAudio) | Új audio keretet hoz létre, és a shape gyűjtemény végére adja hozzá a Presentation.Audios listából származó meglévő audio objektum használatával. |
| [AddAudioFrameEmbedded](../../aspose.slides/ishapecollection/addaudioframeembedded#addaudioframeembedded_1)(float, float, float, float, Stream) | Új audio keretet hoz létre beágyazott WAV fájllal, és a shape gyűjtemény végére adja hozzá. A beágyazott audio a Presentation.Audios gyűjteményhez kerül. |
| [AddAudioFrameLinked](../../aspose.slides/ishapecollection/addaudioframelinked)(float, float, float, float, string) | Új audio keretet hoz létre, amely egy külső audio fájlhoz kapcsolódik, és a shape gyűjtemény végére adja hozzá. |
| [AddAutoShape](../../aspose.slides/ishapecollection/addautoshape#addautoshape)(ShapeType, float, float, float, float) | Új automatikus alakzatot hoz létre alapértelmezett formázással, és a shape gyűjtemény végére adja hozzá. |
| [AddAutoShape](../../aspose.slides/ishapecollection/addautoshape#addautoshape_1)(ShapeType, float, float, float, float, bool) | Új automatikus alakzatot hoz létre, és a shape gyűjtemény végére adja hozzá, opcionálisan alapértelmezett sablonformázással inicializálva. |
| [AddChart](../../aspose.slides/ishapecollection/addchart#addchart)(ChartType, float, float, float, float) | Új diagramot hoz létre, mintapéldány sorozat adatával és beállításaival inicializálja, majd a shape gyűjtemény végére adja hozzá. |
| [AddChart](../../aspose.slides/ishapecollection/addchart#addchart_1)(ChartType, float, float, float, float, bool) | Új diagramot hoz létre, mintapéldány sorozat adatával és beállításaival inicializálja, majd a shape gyűjtemény végére adja hozzá. |
| [AddClone](../../aspose.slides/ishapecollection/addclone#addclone)(IShape) | Létrehozza a megadott alakzat másolatát, és a shape gyűjtemény végére adja hozzá. A klónozott alakzat megtartja az eredeti pozícióját és méretét. |
| [AddClone](../../aspose.slides/ishapecollection/addclone#addclone_1)(IShape, float, float) | Létrehozza a megadott alakzat másolatát, és a shape gyűjtemény végére adja hozzá. Az új alakzat megtartja a *sourceShape* szélességét és magasságát. |
| [AddClone](../../aspose.slides/ishapecollection/addclone#addclone_2)(IShape, float, float, float, float) | Létrehozza a megadott alakzat másolatát, és a shape gyűjtemény végére adja hozzá. |
| [AddConnector](../../aspose.slides/ishapecollection/addconnector#addconnector)(ShapeType, float, float, float, float) | Új csatlakozó alakzatot hoz létre alapértelmezett sablonstílussal, és a shape gyűjtemény végére adja hozzá. |
| [AddConnector](../../aspose.slides/ishapecollection/addconnector#addconnector_1)(ShapeType, float, float, float, float, bool) | Új csatlakozó alakzatot hoz létre és a shape gyűjtemény végére adja hozzá, opcionálisan alapértelmezett sablonstílust alkalmazva. |
| [AddGroupShape](../../aspose.slides/ishapecollection/addgroupshape#addgroupshape)() | Új üres csoport alakzatot hoz létre, és a shape gyűjtemény végére adja hozzá. A csoport kerete automatikusan alkalmazkodik a hozzáadott alakzatokhoz. |
| [AddGroupShape](../../aspose.slides/ishapecollection/addgroupshape#addgroupshape_1)(ISvgImage, float, float, float, float) | Új csoport alakzatot hoz létre, átalakítja a megadott SVG képet egyedi alakzatokká, és a kapott csoportot a shape gyűjtemény végére adja hozzá. |
| [AddMathShape](../../aspose.slides/ishapecollection/addmathshape)(float, float, float, float) | Új négyszögletes automatikus alakzatot hoz létre matematikai tartalom megjelenítéséhez, és a shape gyűjtemény végére adja hozzá. |
| [AddOleObjectFrame](../../aspose.slides/ishapecollection/addoleobjectframe#addoleobjectframe)(float, float, float, float, IOleEmbeddedDataInfo) | Új OLE objektum keretet hoz létre, és a shape gyűjtemény végére adja hozzá. |
| [AddOleObjectFrame](../../aspose.slides/ishapecollection/addoleobjectframe#addoleobjectframe_1)(float, float, float, float, string, string) | Új OLE objektum keretet hoz létre, és a shape gyűjtemény végére adja hozzá. |
| [AddPictureFrame](../../aspose.slides/ishapecollection/addpictureframe)(ShapeType, float, float, float, float, IPPImage) | Új képkeretet hoz létre a megadott képpel, és a shape gyűjtemény végére adja hozzá. |
| [AddSectionZoomFrame](../../aspose.slides/ishapecollection/addsectionzoomframe#addsectionzoomframe)(float, float, float, float, ISection) | Új Section Zoom keretet hoz létre, és a shape gyűjtemény végére adja hozzá. |
| [AddSectionZoomFrame](../../aspose.slides/ishapecollection/addsectionzoomframe#addsectionzoomframe_1)(float, float, float, float, ISection, IPPImage) | Új Section Zoom keretet hoz létre előre meghatározott képpel, és a shape gyűjtemény végére adja hozzá. |
| [AddSmartArt](../../aspose.slides/ishapecollection/addsmartart)(float, float, float, float, SmartArtLayoutType) | SmartArt diagramot hoz létre, és a shape gyűjtemény végére adja hozzá. |
| [AddSummaryZoomFrame](../../aspose.slides/ishapecollection/addsummaryzoomframe)(float, float, float, float) | Új Summary Zoom keretet hoz létre, és a shape gyűjtemény végére adja hozzá. |
| [AddTable](../../aspose.slides/ishapecollection/addtable)(float, float, double[], double[]) | Új táblázatot hoz létre, és a shape gyűjtemény végére adja hozzá. |
| [AddVideoFrame](../../aspose.slides/ishapecollection/addvideoframe#addvideoframe)(float, float, float, float, IVideo) | Új video keretet hoz létre, és a shape gyűjtemény végére adja hozzá. |
| [AddVideoFrame](../../aspose.slides/ishapecollection/addvideoframe#addvideoframe_1)(float, float, float, float, string) | Új video keretet hoz létre, és a shape gyűjtemény végére adja hozzá. |
| [AddZoomFrame](../../aspose.slides/ishapecollection/addzoomframe#addzoomframe)(float, float, float, float, ISlide) | Új Zoom keretet hoz létre, és a shape gyűjtemény végére adja hozzá. |
| [AddZoomFrame](../../aspose.slides/ishapecollection/addzoomframe#addzoomframe_1)(float, float, float, float, ISlide, IPPImage) | Új Zoom keretet hoz létre, és a shape gyűjtemény végére adja hozzá. |
| [Clear](../../aspose.slides/ishapecollection/clear)() | Eltávolítja az összes alakzatot a shape gyűjteményből. |
| [IndexOf](../../aspose.slides/ishapecollection/indexof)(IShape) | Visszaadja a megadott alakzat első előfordulásának nullától induló indexét a gyűjteményben. |
| [InsertAudioFrameCD](../../aspose.slides/ishapecollection/insertaudioframecd)(int, float, float, float, float) | Új audio keretet hoz létre, amely egy CD sávhoz kapcsolódik, és a shape gyűjtemény megadott indexére illeszti be. |
| [InsertAudioFrameEmbedded](../../aspose.slides/ishapecollection/insertaudioframeembedded#insertaudioframeembedded)(int, float, float, float, float, IAudio) | Új audio keretet hoz létre, és a shape gyűjtemény megadott indexére illeszti be a Presentation.Audios listából származó meglévő audio objektum használatával. |
| [InsertAudioFrameEmbedded](../../aspose.slides/ishapecollection/insertaudioframeembedded#insertaudioframeembedded_1)(int, float, float, float, float, Stream) | Új audio keretet hoz létre beágyazott WAV fájllal, és a shape gyűjtemény megadott indexére illeszti be. A beágyazott audio a Presentation.Audios gyűjteményhez kerül. |
| [InsertAudioFrameLinked](../../aspose.slides/ishapecollection/insertaudioframelinked)(int, float, float, float, float, string) | Új audio keretet hoz létre, amely egy külső audio fájlhoz kapcsolódik, és a shape gyűjtemény megadott indexére illeszti be. |
| [InsertAutoShape](../../aspose.slides/ishapecollection/insertautoshape#insertautoshape)(int, ShapeType, float, float, float, float) | Új automatikus alakzatot hoz létre, és a shape gyűjtemény megadott indexére illeszti be, alapértelmezett sablonformázást alkalmazva. |
| [InsertAutoShape](../../aspose.slides/ishapecollection/insertautoshape#insertautoshape_1)(int, ShapeType, float, float, float, float, bool) | Új automatikus alakzatot hoz létre, és a shape gyűjtemény megadott indexére illeszti be, opcionálisan alapértelmezett sablonstílussal inicializálva. |
| [InsertChart](../../aspose.slides/ishapecollection/insertchart#insertchart)(ChartType, float, float, float, float, int) | Új diagramot hoz létre, mintapéldány sorozatadatokkal és beállításokkal inicializálja, majd a shape gyűjtemény megadott indexére illeszti be. |
| [InsertChart](../../aspose.slides/ishapecollection/insertchart#insertchart_1)(ChartType, float, float, float, float, int, bool) | Új diagramot hoz létre, mintapéldány sorozatadatokkal és beállításokkal inicializálja, majd a shape gyűjtemény megadott indexére illeszti be. |
| [InsertClone](../../aspose.slides/ishapecollection/insertclone#insertclone)(int, IShape) | Létrehozza a megadott alakzat másolatát, és a shape gyűjtemény megadott indexére illeszti be. A klónozott alakzat megtartja az eredeti pozícióját és méretét. |
| [InsertClone](../../aspose.slides/ishapecollection/insertclone#insertclone_1)(int, IShape, float, float) | Létrehozza a megadott alakzat másolatát, és a shape gyűjtemény megadott indexére illeszti be. Az új alakzat megtartja a *sourceShape* szélességét és magasságát. |
| [InsertClone](../../aspose.slides/ishapecollection/insertclone#insertclone_2)(int, IShape, float, float, float, float) | Létrehozza a megadott alakzat másolatát, és a shape gyűjtemény megadott indexére illeszti be. |
| [InsertConnector](../../aspose.slides/ishapecollection/insertconnector#insertconnector)(int, ShapeType, float, float, float, float) | Új csatlakozó alakzatot hoz létre, és a shape gyűjtemény megadott indexére illeszti be, alapértelmezett sablonstílust alkalmazva. |
| [InsertConnector](../../aspose.slides/ishapecollection/insertconnector#insertconnector_1)(int, ShapeType, float, float, float, float, bool) | Új csatlakozó alakzatot hoz létre, és a shape gyűjtemény megadott indexére illeszti be, opcionálisan alapértelmezett sablonstílust alkalmazva. |
| [InsertGroupShape](../../aspose.slides/ishapecollection/insertgroupshape)(int) | Új üres csoport alakzatot hoz létre, és a shape gyűjtemény megadott indexére illeszti be. A csoport kerete automatikusan alkalmazkodik a hozzáadott alakzatokhoz. |
| [InsertOleObjectFrame](../../aspose.slides/ishapecollection/insertoleobjectframe#insertoleobjectframe)(int, float, float, float, float, IOleEmbeddedDataInfo) | Új OLE objektum keretet hoz létre, és a shape gyűjtemény megadott indexére illeszti be. |
| [InsertOleObjectFrame](../../aspose.slides/ishapecollection/insertoleobjectframe#insertoleobjectframe_1)(int, float, float, float, float, string, string) | Új OLE objektum keretet hoz létre, és a shape gyűjtemény megadott indexére illeszti be. |
| [InsertPictureFrame](../../aspose.slides/ishapecollection/insertpictureframe)(int, ShapeType, float, float, float, float, IPPImage) | Új képkeretet hoz létre a megadott képpel, és a shape gyűjtemény megadott indexére illeszti be. |
| [InsertSectionZoomFrame](../../aspose.slides/ishapecollection/insertsectionzoomframe#insertsectionzoomframe)(int, float, float, float, float, ISection) | Új Section Zoom keretet hoz létre, és a shape gyűjtemény megadott indexére illeszti be. |
| [InsertSectionZoomFrame](../../aspose.slides/ishapecollection/insertsectionzoomframe#insertsectionzoomframe_1)(int, float, float, float, float, ISection, IPPImage) | Új Section Zoom keretet hoz létre előre meghatározott képpel, és a shape gyűjtemény megadott indexére illeszti be. |
| [InsertSummaryZoomFrame](../../aspose.slides/ishapecollection/insertsummaryzoomframe)(int, float, float, float, float) | Új Summary Zoom keretet hoz létre, és a shape gyűjtemény megadott indexére illeszti be. |
| [InsertTable](../../aspose.slides/ishapecollection/inserttable)(int, float, float, double[], double[]) | Új táblázatot hoz létre, és a shape gyűjtemény megadott indexére illeszti be. |
| [InsertVideoFrame](../../aspose.slides/ishapecollection/insertvideoframe)(int, float, float, float, float, string) | Új video keretet hoz létre, és a shape gyűjtemény megadott indexére illeszti be. |
| [InsertZoomFrame](../../aspose.slides/ishapecollection/insertzoomframe#insertzoomframe)(int, float, float, float, float, ISlide) | Új Zoom keretet hoz létre, és a shape gyűjtemény megadott indexére illeszti be. |
| [InsertZoomFrame](../../aspose.slides/ishapecollection/insertzoomframe#insertzoomframe_1)(int, float, float, float, float, ISlide, IPPImage) | Új Zoom keretet hoz létre előre meghatározott képpel, és a shape gyűjtemény megadott indexére illeszti be. |
| [Remove](../../aspose.slides/ishapecollection/remove)(IShape) | Eltávolítja a megadott alakzat első előfordulását a shape gyűjteményből. |
| [RemoveAt](../../aspose.slides/ishapecollection/removeat)(int) | Eltávolítja a megadott indexű alakzatot a shape gyűjteményből. |
| [Reorder](../../aspose.slides/ishapecollection/reorder#reorder)(int, IShape) | Áthelyezi a megadott alakzatot a shape gyűjteményen belül egy új pozícióba. |
| [Reorder](../../aspose.slides/ishapecollection/reorder#reorder_1)(int, params IShape[]) | Áthelyezi a megadott alakzatokat a shape gyűjteményen belül, a megadott indexnél kezdve helyezi el őket. |
| [ToArray](../../aspose.slides/ishapecollection/toarray#toarray)() | Létrehozza és visszaad egy tömböt, amely az összes alakzatot tartalmazza. |
| [ToArray](../../aspose.slides/ishapecollection/toarray#toarray_1)(int, int) | Létrehozza és visszaad egy tömböt, amely a megadott tartományban lévő összes alakzatot tartalmazza. |

### Lásd még

* interfész [IGenericCollection&lt;T&gt;](../igenericcollection-1)
* interfész [IShape](../ishape)
* névtér [Aspose.Slides](../../aspose.slides)
* összeállítás [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->