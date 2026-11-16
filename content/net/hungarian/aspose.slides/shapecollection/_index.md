---
title: ShapeCollection
second_title: Aspose.Sildes .NET API referencia
description: A formák gyűjteményét képviseli.
type: docs
weight: 9880
url: /hu/aspose.slides/shapecollection/
---
## ShapeCollection osztály

A formák gyűjteményét képviseli.

```csharp
public sealed class ShapeCollection : DomObject<GroupShape>, IShapeCollection
```

## Tulajdonságok

| Név | Leírás |
| --- | --- |
| [Count](../../aspose.slides/shapecollection/count) { get; } | A gyűjteményben ténylegesen található elemek számát adja vissza. Csak olvasható Int32. |
| [IsSynchronized](../../aspose.slides/shapecollection/issynchronized) { get; } | Visszaad egy értéket, amely azt jelzi, hogy a gyűjteményhez való hozzáférés szinkronizált (szálbiztos). Csak olvasható Boolean. |
| [Item](../../aspose.slides/shapecollection/item) { get; } | A megadott indexnél lévő elemet adja vissza. Csak olvasható [`IShape`](../ishape). |
| [ParentGroup](../../aspose.slides/shapecollection/parentgroup) { get; } | A formagyűjtemény szülőcsoport-forma objektumát adja vissza. Csak olvasható [`IGroupShape`](../igroupshape). |
| [SyncRoot](../../aspose.slides/shapecollection/syncroot) { get; } | Visszaad egy szinkronizációs gyökérobjektumot. Csak olvasható Object. |

## Módszerek

| Név | Leírás |
| --- | --- |
| [AddAudioFrameCD](../../aspose.slides/shapecollection/addaudioframecd)(float, float, float, float) | Új audio keretet hoz létre, amely egy CD-sávra hivatkozik, és a forma gyűjtemény végére adja hozzá. |
| [AddAudioFrameEmbedded](../../aspose.slides/shapecollection/addaudioframeembedded#addaudioframeembedded)(float, float, float, float, IAudio) | Új audio keretet hoz létre, és a Presentation.Audios listában lévő meglévő audio objektumot felhasználva a forma gyűjtemény végére adja hozzá. |
| [AddAudioFrameEmbedded](../../aspose.slides/shapecollection/addaudioframeembedded#addaudioframeembedded_1)(float, float, float, float, Stream) | Új audio keretet hoz létre beágyazott WAV fájllal, és a forma gyűjtemény végére adja hozzá. A beágyazott audio a Presentation.Audios gyűjteményhez kerül. |
| [AddAudioFrameLinked](../../aspose.slides/shapecollection/addaudioframelinked)(float, float, float, float, string) | Új audio keretet hoz létre, amely egy külső audio fájlra hivatkozik, és a forma gyűjtemény végére adja hozzá. |
| [AddAutoShape](../../aspose.slides/shapecollection/addautoshape#addautoshape)(ShapeType, float, float, float, float) | Új automatikus formát hoz létre alapértelmezett formázással, és a forma gyűjtemény végére adja hozzá. |
| [AddAutoShape](../../aspose.slides/shapecollection/addautoshape#addautoshape_1)(ShapeType, float, float, float, float, bool) | Új automatikus formát hoz létre, és a forma gyűjtemény végére adja hozzá, opcionálisan alapértelmezett sablonformázással inicializálva. |
| [AddChart](../../aspose.slides/shapecollection/addchart#addchart)(ChartType, float, float, float, float) | Új diagramot hoz létre, minta sorozat adatakkal és beállításokkal inicializálja, majd a forma gyűjtemény végére adja hozzá. |
| [AddChart](../../aspose.slides/shapecollection/addchart#addchart_1)(ChartType, float, float, float, float, bool) | Új diagramot hoz létre, minta sorozat adatakkal és beállításokkal inicializálja, majd a forma gyűjtemény végére adja hozzá. |
| [AddClone](../../aspose.slides/shapecollection/addclone#addclone)(IShape) | Létrehoz egy másolatot a megadott formáról, és a forma gyűjtemény végére adja hozzá. A klónozott forma megtartja az eredeti pozícióját és méretét. |
| [AddClone](../../aspose.slides/shapecollection/addclone#addclone_1)(IShape, float, float) | Létrehoz egy másolatot a megadott formáról, és a forma gyűjtemény végére adja hozzá. Az új forma megtartja a *sourceShape* szélességét és magasságát. |
| [AddClone](../../aspose.slides/shapecollection/addclone#addclone_2)(IShape, float, float, float, float) | Létrehoz egy másolatot a megadott formáról, és a forma gyűjtemény végére adja hozzá. |
| [AddConnector](../../aspose.slides/shapecollection/addconnector#addconnector)(ShapeType, float, float, float, float) | Új csatlakozó formát hoz létre alapértelmezett sablonstílussal, és a forma gyűjtemény végére adja hozzá. |
| [AddConnector](../../aspose.slides/shapecollection/addconnector#addconnector_1)(ShapeType, float, float, float, float, bool) | Új csatlakozó formát hoz létre, és a forma gyűjtemény végére adja hozzá, opcionálisan alapértelmezett sablonstílust alkalmazva. |
| [AddGroupShape](../../aspose.slides/shapecollection/addgroupshape#addgroupshape)() | Új üres csoportformát hoz létre, és a forma gyűjtemény végére adja hozzá. A csoport kerete automatikusan igazodik a hozzáadott formákhoz. |
| [AddGroupShape](../../aspose.slides/shapecollection/addgroupshape#addgroupshape_1)(ISvgImage, float, float, float, float) | Új csoportformát hoz létre, a megadott SVG képet egyedi formákká alakítja, és a keletkezett csoportot a forma gyűjtemény végére adja hozzá. |
| [AddMathShape](../../aspose.slides/shapecollection/addmathshape)(float, float, float, float) | Új téglalap alakú automatikus formát hoz létre matematikai tartalom tárolására, és a forma gyűjtemény végére adja hozzá. |
| [AddOleObjectFrame](../../aspose.slides/shapecollection/addoleobjectframe#addoleobjectframe)(float, float, float, float, IOleEmbeddedDataInfo) | Új OLE objektumkeretet hoz létre, és a forma gyűjtemény végére adja hozzá. |
| [AddOleObjectFrame](../../aspose.slides/shapecollection/addoleobjectframe#addoleobjectframe_1)(float, float, float, float, string, string) | Új OLE objektumkeretet hoz létre, és a forma gyűjtemény végére adja hozzá. |
| [AddPictureFrame](../../aspose.slides/shapecollection/addpictureframe)(ShapeType, float, float, float, float, IPPImage) | Új képkeretet hoz létre, amely a megadott képet tartalmazza, és a forma gyűjtemény végére adja hozzá. |
| [AddSectionZoomFrame](../../aspose.slides/shapecollection/addsectionzoomframe#addsectionzoomframe)(float, float, float, float, ISection) | Új Section Zoom keretet hoz létre, és a forma gyűjtemény végére adja hozzá. |
| [AddSectionZoomFrame](../../aspose.slides/shapecollection/addsectionzoomframe#addsectionzoomframe_1)(float, float, float, float, ISection, IPPImage) | Új Section Zoom keretet hoz létre előre meghatározott képpel, és a forma gyűjtemény végére adja hozzá. |
| [AddSmartArt](../../aspose.slides/shapecollection/addsmartart)(float, float, float, float, SmartArtLayoutType) | SmartArt diagramot hoz létre, és a forma gyűjtemény végére adja hozzá. |
| [AddSummaryZoomFrame](../../aspose.slides/shapecollection/addsummaryzoomframe)(float, float, float, float) | Új Summary Zoom keretet hoz létre, és a forma gyűjtemény végére adja hozzá. |
| [AddTable](../../aspose.slides/shapecollection/addtable)(float, float, double[], double[]) | Új táblát hoz létre, és a forma gyűjtemény végére adja hozzá. |
| [AddVideoFrame](../../aspose.slides/shapecollection/addvideoframe#addvideoframe)(float, float, float, float, IVideo) | Új videó keretet hoz létre, és a forma gyűjtemény végére adja hozzá. |
| [AddVideoFrame](../../aspose.slides/shapecollection/addvideoframe#addvideoframe_1)(float, float, float, float, string) | Új videó keretet hoz létre, és a forma gyűjtemény végére adja hozzá. |
| [AddZoomFrame](../../aspose.slides/shapecollection/addzoomframe#addzoomframe)(float, float, float, float, ISlide) | Új Zoom keretet hoz létre, és a forma gyűjtemény végére adja hozzá. |
| [AddZoomFrame](../../aspose.slides/shapecollection/addzoomframe#addzoomframe_1)(float, float, float, float, ISlide, IPPImage) | Új Zoom keretet hoz létre, és a forma gyűjtemény végére adja hozzá. |
| [Clear](../../aspose.slides/shapecollection/clear)() | Eltávolítja az összes formát a forma gyűjteményből. |
| [CopyTo](../../aspose.slides/shapecollection/copyto)(Array, int) | Átmásolja a gyűjtemény összes elemét a megadott tömbbe. |
| [GetEnumerator](../../aspose.slides/shapecollection/getenumerator)() | Visszaad egy enumerátort, amely végigiterál a gyűjteményen. |
| [IndexOf](../../aspose.slides/shapecollection/indexof)(IShape) | Visszaadja a megadott forma első előfordulásának nulláról induló indexét a gyűjteményben. |
| [InsertAudioFrameCD](../../aspose.slides/shapecollection/insertaudioframecd)(int, float, float, float, float) | Új audio keretet hoz létre, amely egy CD-sávra hivatkozik, és a megadott indexnél szúrja be a forma gyűjteménybe. |
| [InsertAudioFrameEmbedded](../../aspose.slides/shapecollection/insertaudioframeembedded#insertaudioframeembedded)(int, float, float, float, float, IAudio) | Új audio keretet hoz létre, és a Presentation.Audios listában lévő meglévő audio objektumot felhasználva a megadott indexnél szúrja be a forma gyűjteménybe. |
| [InsertAudioFrameEmbedded](../../aspose.slides/shapecollection/insertaudioframeembedded#insertaudioframeembedded_1)(int, float, float, float, float, Stream) | Új audio keretet hoz létre beágyazott WAV fájllal, és a megadott indexnél szúrja be a forma gyűjteménybe. A beágyazott audio a Presentation.Audios gyűjteményhez kerül. |
| [InsertAudioFrameLinked](../../aspose.slides/shapecollection/insertaudioframelinked)(int, float, float, float, float, string) | Új audio keretet hoz létre, amely egy külső audio fájlra hivatkozik, és a megadott indexnél szúrja be a forma gyűjteménybe. |
| [InsertAutoShape](../../aspose.slides/shapecollection/insertautoshape#insertautoshape)(int, ShapeType, float, float, float, float) | Új automatikus formát hoz létre, és a megadott indexnél szúrja be a forma gyűjteménybe, alapértelmezett sablonformázást alkalmazva. |
| [InsertAutoShape](../../aspose.slides/shapecollection/insertautoshape#insertautoshape_1)(int, ShapeType, float, float, float, float, bool) | Új automatikus formát hoz létre, és a megadott indexnél szúrja be a forma gyűjteménybe, opcionálisan alapértelmezett sablonstílussal inicializálva. |
| [InsertChart](../../aspose.slides/shapecollection/insertchart#insertchart)(ChartType, float, float, float, float, int) | Új diagramot hoz létre, minta sorozat adatokat és beállításokat inicializál, majd a megadott indexnél szúrja be a forma gyűjteménybe. |
| [InsertChart](../../aspose.slides/shapecollection/insertchart#insertchart_1)(ChartType, float, float, float, float, int, bool) | Új diagramot hoz létre, minta sorozat adatokat és beállításokat inicializál, majd a megadott indexnél szúrja be a forma gyűjteménybe. |
| [InsertClone](../../aspose.slides/shapecollection/insertclone#insertclone)(int, IShape) | Létrehoz egy másolatot a megadott formáról, és a megadott indexnél szúrja be a forma gyűjteménybe. A klónozott forma megtartja az eredeti pozícióját és méretét. |
| [InsertClone](../../aspose.slides/shapecollection/insertclone#insertclone_1)(int, IShape, float, float) | Létrehoz egy másolatot a megadott formáról, és a megadott indexnél szúrja be a forma gyűjteménybe. Az új forma megtartja a *sourceShape* szélességét és magasságát. |
| [InsertClone](../../aspose.slides/shapecollection/insertclone#insertclone_2)(int, IShape, float, float, float, float) | Létrehoz egy másolatot a megadott formáról, és a megadott indexnél szúrja be a forma gyűjteménybe. |
| [InsertConnector](../../aspose.slides/shapecollection/insertconnector#insertconnector)(int, ShapeType, float, float, float, float) | Új csatlakozó formát hoz létre, és a megadott indexnél szúrja be a forma gyűjteménybe, alapértelmezett sablonstílust alkalmazva. |
| [InsertConnector](../../aspose.slides/shapecollection/insertconnector#insertconnector_1)(int, ShapeType, float, float, float, float, bool) | Új csatlakozó formát hoz létre, és a megadott indexnél szúrja be a forma gyűjteménybe, opcionálisan alapértelmezett sablonstílust alkalmazva. |
| [InsertGroupShape](../../aspose.slides/shapecollection/insertgroupshape)(int) | Új üres csoportformát hoz létre, és a megadott indexnél szúrja be a forma gyűjteménybe. A csoport kerete automatikusan igazodik a hozzáadott formákhoz. |
| [InsertOleObjectFrame](../../aspose.slides/shapecollection/insertoleobjectframe#insertoleobjectframe)(int, float, float, float, float, IOleEmbeddedDataInfo) | Új OLE objektumkeretet hoz létre, és a megadott indexnél szúrja be a forma gyűjteménybe. |
| [InsertOleObjectFrame](../../aspose.slides/shapecollection/insertoleobjectframe#insertoleobjectframe_1)(int, float, float, float, float, string, string) | Új OLE objektumkeretet hoz létre, és a megadott indexnél szúrja be a forma gyűjteménybe. |
| [InsertPictureFrame](../../aspose.slides/shapecollection/insertpictureframe)(int, ShapeType, float, float, float, float, IPPImage) | Új képkeretet hoz létre, amely a megadott képet tartalmazza, és a megadott indexnél szúrja be a forma gyűjteménybe. |
| [InsertSectionZoomFrame](../../aspose.slides/shapecollection/insertsectionzoomframe#insertsectionzoomframe)(int, float, float, float, float, ISection) | Új Section Zoom keretet hoz létre, és a megadott indexnél szúrja be a forma gyűjteménybe. |
| [InsertSectionZoomFrame](../../aspose.slides/shapecollection/insertsectionzoomframe#insertsectionzoomframe_1)(int, float, float, float, float, ISection, IPPImage) | Új Section Zoom keretet hoz létre előre meghatározott képpel, és a megadott indexnél szúrja be a forma gyűjteménybe. |
| [InsertSummaryZoomFrame](../../aspose.slides/shapecollection/insertsummaryzoomframe)(int, float, float, float, float) | Új Summary Zoom keretet hoz létre, és a megadott indexnél szúrja be a forma gyűjteménybe. |
| [InsertTable](../../aspose.slides/shapecollection/inserttable)(int, float, float, double[], double[]) | Új táblát hoz létre, és a megadott indexnél szúrja be a forma gyűjteménybe. |
| [InsertVideoFrame](../../aspose.slides/shapecollection/insertvideoframe)(int, float, float, float, float, string) | Új videó keretet hoz létre, és a megadott indexnél szúrja be a forma gyűjteménybe. |
| [InsertZoomFrame](../../aspose.slides/shapecollection/insertzoomframe#insertzoomframe)(int, float, float, float, float, ISlide) | Új Zoom keretet hoz létre, és a megadott indexnél szúrja be a forma gyűjteménybe. |
| [InsertZoomFrame](../../aspose.slides/shapecollection/insertzoomframe#insertzoomframe_1)(int, float, float, float, float, ISlide, IPPImage) | Új Zoom keretet hoz létre előre meghatározott képpel, és a megadott indexnél szúrja be a forma gyűjteménybe. |
| [Remove](../../aspose.slides/shapecollection/remove)(IShape) | Eltávolítja a megadott forma első előfordulását a forma gyűjteményből. |
| [RemoveAt](../../aspose.slides/shapecollection/removeat)(int) | Eltávolítja a megadott indexnél lévő formát a forma gyűjteményből. |
| [Reorder](../../aspose.slides/shapecollection/reorder#reorder)(int, IShape) | A megadott formát egy új pozícióba helyezi a forma gyűjteményen belül. |
| [Reorder](../../aspose.slides/shapecollection/reorder#reorder_1)(int, params IShape[]) | A megadott formákat a forma gyűjteményben áthelyezi, a megadott indexnél kezdve helyezi el őket. |
| [ToArray](../../aspose.slides/shapecollection/toarray#toarray)() | Létrehoz és visszaad egy tömböt, amely az összes formát tartalmazza. |
| [ToArray](../../aspose.slides/shapecollection/toarray#toarray_1)(int, int) | Létrehoz és visszaad egy tömböt, amely a megadott tartományban lévő összes formát tartalmazza. |

### Lásd még

* osztály [DomObject&lt;TParent&gt;](../domobject-1)
* osztály [GroupShape](../groupshape)
* interfész [IShapeCollection](../ishapecollection)
* névtér [Aspose.Slides](../../aspose.slides)
* összeállítás [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->