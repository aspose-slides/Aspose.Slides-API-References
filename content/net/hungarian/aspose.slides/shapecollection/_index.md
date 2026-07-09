---
title: ShapeCollection
second_title: Aspose.Sildes .NET API Referenciához
description: A alakzatok gyűjteményét képviseli.
type: docs
weight: 9860
url: /hu/aspose.slides/shapecollection/
---
## ShapeCollection osztály

Represents a collection of shapes.

```csharp
public sealed class ShapeCollection : DomObject<GroupShape>, IShapeCollection
```

## Tulajdonságok

| Név | Leírás |
| --- | --- |
| [Count](../../aspose.slides/shapecollection/count) { get; } | A ténylegesen a gyűjteményben szereplő elemek számát adja vissza. Csak olvasható Int32. |
| [IsSynchronized](../../aspose.slides/shapecollection/issynchronized) { get; } | Visszaad egy értéket, amely jelzi, hogy a gyűjteményhez való hozzáférés szinkronizált (szálbiztos). Csak olvasható Boolean. |
| [Item](../../aspose.slides/shapecollection/item) { get; } | Az adott indexű elemet adja vissza. Csak olvasható [`IShape`](../ishape). |
| [ParentGroup](../../aspose.slides/shapecollection/parentgroup) { get; } | A shape gyűjtemény szülő csoport alak objektumát adja vissza. Csak olvasható [`IGroupShape`](../igroupshape). |
| [SyncRoot](../../aspose.slides/shapecollection/syncroot) { get; } | Szinkronizációs gyökérpontot ad vissza. Csak olvasható Object. |

## Módszerek

| Név | Leírás |
| --- | --- |
| [AddAudioFrameCD](../../aspose.slides/shapecollection/addaudioframecd)(float, float, float, float) | Új audio keretet hoz létre egy CD sávra hivatkozva, és a shape gyűjtemény végéhez adja. |
| [AddAudioFrameEmbedded](../../aspose.slides/shapecollection/addaudioframeembedded#addaudioframeembedded)(float, float, float, float, IAudio) | Új audio keretet hoz létre, és a shape gyűjtemény végéhez adja, a Presentation.Audios listából származó meglévő audio objektumot használva. |
| [AddAudioFrameEmbedded](../../aspose.slides/shapecollection/addaudioframeembedded#addaudioframeembedded_1)(float, float, float, float, Stream) | Új audio keretet hoz létre egy beágyazott WAV fájllal, és a shape gyűjtemény végéhez adja. A beágyazott audio a Presentation.Audios gyűjteményhez kerül. |
| [AddAudioFrameLinked](../../aspose.slides/shapecollection/addaudioframelinked)(float, float, float, float, string) | Új audio keretet hoz létre egy külső audio fájlra hivatkozva, és a shape gyűjtemény végéhez adja. |
| [AddAutoShape](../../aspose.slides/shapecollection/addautoshape#addautoshape)(ShapeType, float, float, float, float) | Új automatikus alakzatot hoz létre alapértelmezett formázással, és a shape gyűjtemény végéhez adja. |
| [AddAutoShape](../../aspose.slides/shapecollection/addautoshape#addautoshape_1)(ShapeType, float, float, float, float, bool) | Új automatikus alakzatot hoz létre, és a shape gyűjtemény végéhez adja, opcionálisan alapértelmezett sablonformázással inicializálva. |
| [AddChart](../../aspose.slides/shapecollection/addchart#addchart)(ChartType, float, float, float, float) | Új diagramot hoz létre, mintapéldány adat- és beállításokkal inicializálja, és a shape gyűjtemény végéhez adja. |
| [AddChart](../../aspose.slides/shapecollection/addchart#addchart_1)(ChartType, float, float, float, float, bool) | Új diagramot hoz létre, mintapéldány adat- és beállításokkal inicializálja, és a shape gyűjtemény végéhez adja. |
| [AddClone](../../aspose.slides/shapecollection/addclone#addclone)(IShape) | Létrehozza a megadott alakzat másolatát, és a shape gyűjtemény végéhez adja. A klónozott alakzat megtartja az eredeti helyzetét és méretét. |
| [AddClone](../../aspose.slides/shapecollection/addclone#addclone_1)(IShape, float, float) | Létrehozza a megadott alakzat másolatát, és a shape gyűjtemény végéhez adja. Az új alakzat megtartja a *sourceShape* szélességét és magasságát. |
| [AddClone](../../aspose.slides/shapecollection/addclone#addclone_2)(IShape, float, float, float, float) | Létrehozza a megadott alakzat másolatát, és a shape gyűjtemény végéhez adja. |
| [AddConnector](../../aspose.slides/shapecollection/addconnector#addconnector)(ShapeType, float, float, float, float) | Új csatlakozó alakzatot hoz létre alapértelmezett sablonstílussal, és a shape gyűjtemény végéhez adja. |
| [AddConnector](../../aspose.slides/shapecollection/addconnector#addconnector_1)(ShapeType, float, float, float, float, bool) | Új csatlakozó alakzatot hoz létre, és a shape gyűjtemény végéhez adja, opcionálisan alapértelmezett sablonstílust alkalmazva. |
| [AddGroupShape](../../aspose.slides/shapecollection/addgroupshape#addgroupshape)() | Új üres csoport alakzatot hoz létre, és a shape gyűjtemény végéhez adja. A csoport kerete automatikusan igazodik a hozzáadott alakzatokhoz. |
| [AddGroupShape](../../aspose.slides/shapecollection/addgroupshape#addgroupshape_1)(ISvgImage, float, float, float, float) | Új csoport alakzatot hoz létre, a megadott SVG képet egyedi alakzatokká konvertálja, és a keletkezett csoportot a shape gyűjtemény végéhez adja. |
| [AddMathShape](../../aspose.slides/shapecollection/addmathshape)(float, float, float, float) | Új téglalap automatikus alakzatot hoz létre matematikai tartalom megjelenítésére, és a shape gyűjtemény végéhez adja. |
| [AddOleObjectFrame](../../aspose.slides/shapecollection/addoleobjectframe#addoleobjectframe)(float, float, float, float, IOleEmbeddedDataInfo) | Új OLE objektum keretet hoz létre, és a shape gyűjtemény végéhez adja. |
| [AddOleObjectFrame](../../aspose.slides/shapecollection/addoleobjectframe#addoleobjectframe_1)(float, float, float, float, string, string) | Új OLE objektum keretet hoz létre, és a shape gyűjtemény végéhez adja. |
| [AddPictureFrame](../../aspose.slides/shapecollection/addpictureframe)(ShapeType, float, float, float, float, IPPImage) | Új képkeretet hoz létre a megadott képpel, és a shape gyűjtemény végéhez adja. |
| [AddSectionZoomFrame](../../aspose.slides/shapecollection/addsectionzoomframe#addsectionzoomframe)(float, float, float, float, ISection) | Új Section Zoom keretet hoz létre, és a shape gyűjtemény végéhez adja. |
| [AddSectionZoomFrame](../../aspose.slides/shapecollection/addsectionzoomframe#addsectionzoomframe_1)(float, float, float, float, ISection, IPPImage) | Új Section Zoom keretet hoz létre előre definiált képpel, és a shape gyűjtemény végéhez adja. |
| [AddSmartArt](../../aspose.slides/shapecollection/addsmartart)(float, float, float, float, SmartArtLayoutType) | Új SmartArt diagramot hoz létre, és a shape gyűjtemény végéhez adja. |
| [AddSummaryZoomFrame](../../aspose.slides/shapecollection/addsummaryzoomframe)(float, float, float, float) | Új Summary Zoom keretet hoz létre, és a shape gyűjtemény végéhez adja. |
| [AddTable](../../aspose.slides/shapecollection/addtable)(float, float, double[], double[]) | Új táblázatot hoz létre, és a shape gyűjtemény végéhez adja. |
| [AddVideoFrame](../../aspose.slides/shapecollection/addvideoframe#addvideoframe)(float, float, float, float, IVideo) | Új video keretet hoz létre, és a shape gyűjtemény végéhez adja. |
| [AddVideoFrame](../../aspose.slides/shapecollection/addvideoframe#addvideoframe_1)(float, float, float, float, string) | Új video keretet hoz létre, és a shape gyűjtemény végéhez adja. |
| [AddZoomFrame](../../aspose.slides/shapecollection/addzoomframe#addzoomframe)(float, float, float, float, ISlide) | Új Zoom keretet hoz létre, és a shape gyűjtemény végéhez adja. |
| [AddZoomFrame](../../aspose.slides/shapecollection/addzoomframe#addzoomframe_1)(float, float, float, float, ISlide, IPPImage) | Új Zoom keretet hoz létre, és a shape gyűjtemény végéhez adja. |
| [Clear](../../aspose.slides/shapecollection/clear)() | Eltávolítja az összes alakzatot a shape gyűjteményből. |
| [CopyTo](../../aspose.slides/shapecollection/copyto)(Array, int) | A gyűjtemény összes elemét a megadott tömbbe másolja. |
| [GetEnumerator](../../aspose.slides/shapecollection/getenumerator)() | Visszaad egy enumerátort, amely a gyűjteményen iterál. |
| [IndexOf](../../aspose.slides/shapecollection/indexof)(IShape) | Visszaadja a megadott alakzat első előfordulásának nullától kezdődő indexét a gyűjteményben. |
| [InsertAudioFrameCD](../../aspose.slides/shapecollection/insertaudioframecd)(int, float, float, float, float) | Új audio keretet hoz létre egy CD sávra hivatkozva, és a megadott indexnél a shape gyűjteménybe illeszti. |
| [InsertAudioFrameEmbedded](../../aspose.slides/shapecollection/insertaudioframeembedded#insertaudioframeembedded)(int, float, float, float, float, IAudio) | Új audio keretet hoz létre, és a megadott indexnél a shape gyűjteménybe illeszti, a Presentation.Audios listából származó meglévő audio objektumot használva. |
| [InsertAudioFrameEmbedded](../../aspose.slides/shapecollection/insertaudioframeembedded#insertaudioframeembedded_1)(int, float, float, float, float, Stream) | Új audio keretet hoz létre egy beágyazott WAV fájllal, és a megadott indexnél a shape gyűjteménybe illeszti. A beágyazott audio a Presentation.Audios gyűjteményhez kerül. |
| [InsertAudioFrameLinked](../../aspose.slides/shapecollection/insertaudioframelinked)(int, float, float, float, float, string) | Új audio keretet hoz létre egy külső audio fájlra hivatkozva, és a megadott indexnél a shape gyűjteménybe illeszti. |
| [InsertAutoShape](../../aspose.slides/shapecollection/insertautoshape#insertautoshape)(int, ShapeType, float, float, float, float) | Új automatikus alakzatot hoz létre, és a megadott indexnél a shape gyűjteménybe illeszti, alapértelmezett sablonformázással. |
| [InsertAutoShape](../../aspose.slides/shapecollection/insertautoshape#insertautoshape_1)(int, ShapeType, float, float, float, float, bool) | Új automatikus alakzatot hoz létre, és a megadott indexnél a shape gyűjteménybe illeszti, opcionálisan alapértelmezett sablonstílussal. |
| [InsertChart](../../aspose.slides/shapecollection/insertchart#insertchart)(ChartType, float, float, float, float, int) | Új diagramot hoz létre, mintapéldány adat- és beállításokkal inicializálja, és a megadott indexnél a shape gyűjteménybe illeszti. |
| [InsertChart](../../aspose.slides/shapecollection/insertchart#insertchart_1)(ChartType, float, float, float, float, int, bool) | Új diagramot hoz létre, mintapéldány adat- és beállításokkal inicializálja, és a megadott indexnél a shape gyűjteménybe illeszti. |
| [InsertClone](../../aspose.slides/shapecollection/insertclone#insertclone)(int, IShape) | Létrehozza a megadott alakzat másolatát, és a megadott indexnél a shape gyűjteménybe illeszti. A klónozott alakzat megtartja az eredeti helyzetét és méretét. |
| [InsertClone](../../aspose.slides/shapecollection/insertclone#insertclone_1)(int, IShape, float, float) | Létrehozza a megadott alakzat másolatát, és a megadott indexnél a shape gyűjteménybe illeszti. Az új alakzat megtartja a *sourceShape* szélességét és magasságát. |
| [InsertClone](../../aspose.slides/shapecollection/insertclone#insertclone_2)(int, IShape, float, float, float, float) | Létrehozza a megadott alakzat másolatát, és a megadott indexnél a shape gyűjteménybe illeszti. |
| [InsertConnector](../../aspose.slides/shapecollection/insertconnector#insertconnector)(int, ShapeType, float, float, float, float) | Új csatlakozó alakzatot hoz létre, és a megadott indexnél a shape gyűjteménybe illeszti, alapértelmezett sablonstílussal. |
| [InsertConnector](../../aspose.slides/shapecollection/insertconnector#insertconnector_1)(int, ShapeType, float, float, float, float, bool) | Új csatlakozó alakzatot hoz létre, és a megadott indexnél a shape gyűjteménybe illeszti, opcionálisan alapértelmezett sablonstílust alkalmazva. |
| [InsertGroupShape](../../aspose.slides/shapecollection/insertgroupshape)(int) | Új üres csoport alakzatot hoz létre, és a megadott indexnél a shape gyűjteményhez adja. A csoport kerete automatikusan igazodik a hozzáadott alakzatokhoz. |
| [InsertOleObjectFrame](../../aspose.slides/shapecollection/insertoleobjectframe#insertoleobjectframe)(int, float, float, float, float, IOleEmbeddedDataInfo) | Új OLE objektum keretet hoz létre, és a megadott indexnél a shape gyűjteménybe illeszti. |
| [InsertOleObjectFrame](../../aspose.slides/shapecollection/insertoleobjectframe#insertoleobjectframe_1)(int, float, float, float, float, string, string) | Új OLE objektum keretet hoz létre, és a megadott indexnél a shape gyűjteménybe illeszti. |
| [InsertPictureFrame](../../aspose.slides/shapecollection/insertpictureframe)(int, ShapeType, float, float, float, float, IPPImage) | Új képkeretet hoz létre a megadott képpel, és a megadott indexnél a shape gyűjteménybe illeszti. |
| [InsertSectionZoomFrame](../../aspose.slides/shapecollection/insertsectionzoomframe#insertsectionzoomframe)(int, float, float, float, float, ISection) | Új Section Zoom keretet hoz létre, és a megadott indexnél a shape gyűjteménybe illeszti. |
| [InsertSectionZoomFrame](../../aspose.slides/shapecollection/insertsectionzoomframe#insertsectionzoomframe_1)(int, float, float, float, float, ISection, IPPImage) | Új Section Zoom keretet hoz létre előre definiált képpel, és a megadott indexnél a shape gyűjteménybe illeszti. |
| [InsertSummaryZoomFrame](../../aspose.slides/shapecollection/insertsummaryzoomframe)(int, float, float, float, float) | Új Summary Zoom keretet hoz létre, és a megadott indexnél a shape gyűjteménybe illeszti. |
| [InsertTable](../../aspose.slides/shapecollection/inserttable)(int, float, float, double[], double[]) | Új táblázatot hoz létre, és a megadott indexnél a shape gyűjteménybe illeszti. |
| [InsertVideoFrame](../../aspose.slides/shapecollection/insertvideoframe)(int, float, float, float, float, string) | Új video keretet hoz létre, és a megadott indexnél a shape gyűjteménybe illeszti. |
| [InsertZoomFrame](../../aspose.slides/shapecollection/insertzoomframe#insertzoomframe)(int, float, float, float, float, ISlide) | Új Zoom keretet hoz létre, és a megadott indexnél a shape gyűjteménybe illeszti. |
| [InsertZoomFrame](../../aspose.slides/shapecollection/insertzoomframe#insertzoomframe_1)(int, float, float, float, float, ISlide, IPPImage) | Új Zoom keretet hoz létre előre definiált képpel, és a megadott indexnél a shape gyűjteménybe illeszti. |
| [Remove](../../aspose.slides/shapecollection/remove)(IShape) | Eltávolítja a megadott alakzat első előfordulását a shape gyűjteményből. |
| [RemoveAt](../../aspose.slides/shapecollection/removeat)(int) | Eltávolítja a megadott indexű alakzatot a shape gyűjteményből. |
| [Reorder](../../aspose.slides/shapecollection/reorder#reorder)(int, IShape) | Áthelyezi a megadott alakzatot egy új pozícióba a shape gyűjteményben. |
| [Reorder](../../aspose.slides/shapecollection/reorder#reorder_1)(int, params IShape[]) | Áthelyezi a megadott alakzatokat a shape gyűjteményben, a megadott indexnél kezdi őket elhelyezni. |
| [ToArray](../../aspose.slides/shapecollection/toarray#toarray)() | Létrehoz és visszaad egy tömböt, amely az összes alakzatot tartalmazza. |
| [ToArray](../../aspose.slides/shapecollection/toarray#toarray_1)(int, int) | Létrehoz és visszaad egy tömböt, amely a megadott tartományban lévő összes alakzatot tartalmazza. |

### Lásd még

* osztály [DomObject&lt;TParent&gt;](../domobject-1)
* osztály [GroupShape](../groupshape)
* interfész [IShapeCollection](../ishapecollection)
* névtér [Aspose.Slides](../../aspose.slides)
* összeállítás [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->