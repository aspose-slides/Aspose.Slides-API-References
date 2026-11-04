---
title: IShapeCollection
second_title: Aspose.Sildes .NET API Referenciája
description: A formák gyűjteményét képviseli.
type: docs
weight: 7000
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
| [Item](../../aspose.slides/ishapecollection/item) { get; } | Lekéri a megadott indexű elemet. Csak olvasható [`IShape`](../ishape). |
| [ParentGroup](../../aspose.slides/ishapecollection/parentgroup) { get; } | Lekéri a shape collection szülő csoport alakzat objektumát. Csak olvasható [`IGroupShape`](../igroupshape). |

## Módszerek

| Név | Leírás |
| --- | --- |
| [AddAudioFrameCD](../../aspose.slides/ishapecollection/addaudioframecd)(float, float, float, float) | Létrehoz egy új audio keretet, amely CD-sávra hivatkozik, és hozzáadja a shape collection végéhez. |
| [AddAudioFrameEmbedded](../../aspose.slides/ishapecollection/addaudioframeembedded#addaudioframeembedded)(float, float, float, float, IAudio) | Létrehoz egy új audio keretet, és a Presentation.Audios listából származó meglévő audio objektumot felhasználva hozzáadja a shape collection végéhez. |
| [AddAudioFrameEmbedded](../../aspose.slides/ishapecollection/addaudioframeembedded#addaudioframeembedded_1)(float, float, float, float, Stream) | Létrehoz egy új audio keretet beágyazott WAV fájllal, és hozzáadja a shape collection végéhez. A beágyazott audio a Presentation.Audios gyűjteményhez kerül hozzáadásra. |
| [AddAudioFrameLinked](../../aspose.slides/ishapecollection/addaudioframelinked)(float, float, float, float, string) | Létrehoz egy új audio keretet, amely egy külső audio fájlra hivatkozik, és hozzáadja a shape collection végéhez. |
| [AddAutoShape](../../aspose.slides/ishapecollection/addautoshape#addautoshape)(ShapeType, float, float, float, float) | Létrehoz egy új automatikus alakzatot alapértelmezett formázással, és hozzáadja a shape collection végéhez. |
| [AddAutoShape](../../aspose.slides/ishapecollection/addautoshape#addautoshape_1)(ShapeType, float, float, float, float, bool) | Létrehoz egy új automatikus alakzatot, és hozzáadja a shape collection végéhez, opcionálisan alapértelmezett sablonformázással inicializálva. |
| [AddChart](../../aspose.slides/ishapecollection/addchart#addchart)(ChartType, float, float, float, float) | Létrehoz egy új diagramot, mintasorozat adatokat és beállításokat alkalmazva inicializálja, és hozzáadja a shape collection végéhez. |
| [AddChart](../../aspose.slides/ishapecollection/addchart#addchart_1)(ChartType, float, float, float, float, bool) | Létrehoz egy új diagramot, mintasorozat adatokat és beállításokat alkalmazva inicializálja, és hozzáadja a shape collection végéhez. |
| [AddClone](../../aspose.slides/ishapecollection/addclone#addclone)(IShape) | Létrehozza a megadott alakzat másolatát, és hozzáadja a shape collection végéhez. A klónozott alakzat megtartja az eredeti pozícióját és méretét. |
| [AddClone](../../aspose.slides/ishapecollection/addclone#addclone_1)(IShape, float, float) | Létrehozza a megadott alakzat másolatát, és hozzáadja a shape collection végéhez. Az új alakzat megtartja a *sourceShape* szélességét és magasságát. |
| [AddClone](../../aspose.slides/ishapecollection/addclone#addclone_2)(IShape, float, float, float, float) | Létrehozza a megadott alakzat másolatát, és hozzáadja a shape collection végéhez. |
| [AddConnector](../../aspose.slides/ishapecollection/addconnector#addconnector)(ShapeType, float, float, float, float) | Létrehoz egy új összekötő alakzatot alapértelmezett sablonstílussal, és hozzáadja a shape collection végéhez. |
| [AddConnector](../../aspose.slides/ishapecollection/addconnector#addconnector_1)(ShapeType, float, float, float, float, bool) | Létrehoz egy új összekötő alakzatot, és hozzáadja a shape collection végéhez, opcionálisan alapértelmezett sablonstílust alkalmazva. |
| [AddGroupShape](../../aspose.slides/ishapecollection/addgroupshape#addgroupshape)() | Létrehoz egy új üres csoport alakzatot, és hozzáadja a shape collection végéhez. A csoport kerete automatikusan igazodik a hozzáadott alakzatokhoz. |
| [AddGroupShape](../../aspose.slides/ishapecollection/addgroupshape#addgroupshape_1)(ISvgImage, float, float, float, float) | Létrehoz egy új csoport alakzatot, a megadott SVG képet egyedi alakzatokká alakítja, és az eredményül kapott csoportot hozzáadja a shape collection végéhez. |
| [AddMathShape](../../aspose.slides/ishapecollection/addmathshape)(float, float, float, float) | Létrehoz egy új téglalap automatikus alakzatot matematikai tartalom megjelenítésére, és hozzáadja a shape collection végéhez. |
| [AddOleObjectFrame](../../aspose.slides/ishapecollection/addoleobjectframe#addoleobjectframe)(float, float, float, float, IOleEmbeddedDataInfo) | Létrehoz egy új OLE objektum keretet, és hozzáadja a shape collection végéhez. |
| [AddOleObjectFrame](../../aspose.slides/ishapecollection/addoleobjectframe#addoleobjectframe_1)(float, float, float, float, string, string) | Létrehoz egy új OLE objektum keretet, és hozzáadja a shape collection végéhez. |
| [AddPictureFrame](../../aspose.slides/ishapecollection/addpictureframe)(ShapeType, float, float, float, float, IPPImage) | Létrehoz egy új képkeretet a megadott képpel, és hozzáadja a shape collection végéhez. |
| [AddSectionZoomFrame](../../aspose.slides/ishapecollection/addsectionzoomframe#addsectionzoomframe)(float, float, float, float, ISection) | Létrehoz egy új Section Zoom keretet, és hozzáadja a shape collection végéhez. |
| [AddSectionZoomFrame](../../aspose.slides/ishapecollection/addsectionzoomframe#addsectionzoomframe_1)(float, float, float, float, ISection, IPPImage) | Létrehoz egy új Section Zoom keretet előre definiált képpel, és hozzáadja a shape collection végéhez. |
| [AddSmartArt](../../aspose.slides/ishapecollection/addsmartart)(float, float, float, float, SmartArtLayoutType) | Létrehoz egy SmartArt diagramot, és hozzáadja a shape collection végéhez. |
| [AddSummaryZoomFrame](../../aspose.slides/ishapecollection/addsummaryzoomframe)(float, float, float, float) | Létrehoz egy új Summary Zoom keretet, és hozzáadja a shape collection végéhez. |
| [AddTable](../../aspose.slides/ishapecollection/addtable)(float, float, double[], double[]) | Létrehoz egy új táblázatot, és hozzáadja a shape collection végéhez. |
| [AddVideoFrame](../../aspose.slides/ishapecollection/addvideoframe#addvideoframe)(float, float, float, float, IVideo) | Létrehoz egy új videó keretet, és hozzáadja a shape collection végéhez. |
| [AddVideoFrame](../../aspose.slides/ishapecollection/addvideoframe#addvideoframe_1)(float, float, float, float, string) | Létrehoz egy új videó keretet, és hozzáadja a shape collection végéhez. |
| [AddZoomFrame](../../aspose.slides/ishapecollection/addzoomframe#addzoomframe)(float, float, float, float, ISlide) | Létrehoz egy új Zoom keretet, és hozzáadja a shape collection végéhez. |
| [AddZoomFrame](../../aspose.slides/ishapecollection/addzoomframe#addzoomframe_1)(float, float, float, float, ISlide, IPPImage) | Létrehoz egy új Zoom keretet, és hozzáadja a shape collection végéhez. |
| [Clear](../../aspose.slides/ishapecollection/clear)() | Eltávolítja az összes alakzatot a shape collection-ből. |
| [IndexOf](../../aspose.slides/ishapecollection/indexof)(IShape) | Visszaadja a megadott alakzat első előfordulásának nullától induló indexét a gyűjteményben. |
| [InsertAudioFrameCD](../../aspose.slides/ishapecollection/insertaudioframecd)(int, float, float, float, float) | Létrehoz egy új audio keretet CD-sávra hivatkozva, és a megadott indexnél beszúrja a shape collection-be. |
| [InsertAudioFrameEmbedded](../../aspose.slides/ishapecollection/insertaudioframeembedded#insertaudioframeembedded)(int, float, float, float, float, IAudio) | Létrehoz egy új audio keretet, és a Presentation.Audios listából származó meglévő audio objektumot felhasználva a megadott indexnél beszúrja a shape collection-be. |
| [InsertAudioFrameEmbedded](../../aspose.slides/ishapecollection/insertaudioframeembedded#insertaudioframeembedded_1)(int, float, float, float, float, Stream) | Létrehoz egy új audio keretet beágyazott WAV fájllal, és a megadott indexnél beszúrja a shape collection-be. A beágyazott audio a Presentation.Audios gyűjteményhez kerül hozzáadásra. |
| [InsertAudioFrameLinked](../../aspose.slides/ishapecollection/insertaudioframelinked)(int, float, float, float, float, string) | Létrehoz egy új audio keretet, amely egy külső audio fájlra hivatkozik, és a megadott indexnél beszúrja a shape collection-be. |
| [InsertAutoShape](../../aspose.slides/ishapecollection/insertautoshape#insertautoshape)(int, ShapeType, float, float, float, float) | Létrehoz egy új automatikus alakzatot, és a megadott indexnél beszúrja a shape collection-be, alapértelmezett sablonformázást alkalmazva. |
| [InsertAutoShape](../../aspose.slides/ishapecollection/insertautoshape#insertautoshape_1)(int, ShapeType, float, float, float, float, bool) | Létrehoz egy új automatikus alakzatot, és a megadott indexnél beszúrja a shape collection-be, opcionálisan alapértelmezett sablonstílus alkalmazásával. |
| [InsertChart](../../aspose.slides/ishapecollection/insertchart#insertchart)(ChartType, float, float, float, float, int) | Létrehoz egy új diagramot, mintasorozat adatokat és beállításokat alkalmazva inicializálja, és a megadott indexnél beszúrja a shape collection-be. |
| [InsertChart](../../aspose.slides/ishapecollection/insertchart#insertchart_1)(ChartType, float, float, float, float, int, bool) | Létrehoz egy új diagramot, mintasorozat adatokat és beállításokat alkalmazva inicializálja, és a megadott indexnél beszúrja a shape collection-be. |
| [InsertClone](../../aspose.slides/ishapecollection/insertclone#insertclone)(int, IShape) | Létrehozza a megadott alakzat másolatát, és a megadott indexnél beszúrja a shape collection-be. A klónozott alakzat megtartja az eredeti pozícióját és méretét. |
| [InsertClone](../../aspose.slides/ishapecollection/insertclone#insertclone_1)(int, IShape, float, float) | Létrehozza a megadott alakzat másolatát, és a megadott indexnél beszúrja a shape collection-be. Az új alakzat megtartja a *sourceShape* szélességét és magasságát. |
| [InsertClone](../../aspose.slides/ishapecollection/insertclone#insertclone_2)(int, IShape, float, float, float, float) | Létrehozza a megadott alakzat másolatát, és a megadott indexnél beszúrja a shape collection-be. |
| [InsertConnector](../../aspose.slides/ishapecollection/insertconnector#insertconnector)(int, ShapeType, float, float, float, float) | Létrehoz egy új összekötő alakzatot, és a megadott indexnél beszúrja a shape collection-be, alapértelmezett sablonstílus alkalmazásával. |
| [InsertConnector](../../aspose.slides/ishapecollection/insertconnector#insertconnector_1)(int, ShapeType, float, float, float, float, bool) | Létrehoz egy új összekötő alakzatot, és a megadott indexnél beszúrja a shape collection-be, opcionálisan alapértelmezett sablonstílust alkalmazva. |
| [InsertGroupShape](../../aspose.slides/ishapecollection/insertgroupshape)(int) | Létrehoz egy új üres csoport alakzatot, és a megadott indexnél beszúrja a shape collection-be. A csoport kerete automatikusan igazodik a hozzáadott alakzatokhoz. |
| [InsertOleObjectFrame](../../aspose.slides/ishapecollection/insertoleobjectframe#insertoleobjectframe)(int, float, float, float, float, IOleEmbeddedDataInfo) | Létrehoz egy új OLE objektum keretet, és a megadott indexnél beszúrja a shape collection-be. |
| [InsertOleObjectFrame](../../aspose.slides/ishapecollection/insertoleobjectframe#insertoleobjectframe_1)(int, float, float, float, float, string, string) | Létrehoz egy új OLE objektum keretet, és a megadott indexnél beszúrja a shape collection-be. |
| [InsertPictureFrame](../../aspose.slides/ishapecollection/insertpictureframe)(int, ShapeType, float, float, float, float, IPPImage) | Létrehoz egy új képkeretet a megadott képpel, és a megadott indexnél beszúrja a shape collection-be. |
| [InsertSectionZoomFrame](../../aspose.slides/ishapecollection/insertsectionzoomframe#insertsectionzoomframe)(int, float, float, float, float, ISection) | Létrehoz egy új Section Zoom keretet, és a megadott indexnél beszúrja a shape collection-be. |
| [InsertSectionZoomFrame](../../aspose.slides/ishapecollection/insertsectionzoomframe#insertsectionzoomframe_1)(int, float, float, float, float, ISection, IPPImage) | Létrehoz egy új Section Zoom keretet előre definiált képpel, és a megadott indexnél beszúrja a shape collection-be. |
| [InsertSummaryZoomFrame](../../aspose.slides/ishapecollection/insertsummaryzoomframe)(int, float, float, float, float) | Létrehoz egy új Summary Zoom keretet, és a megadott indexnél beszúrja a shape collection-be. |
| [InsertTable](../../aspose.slides/ishapecollection/inserttable)(int, float, float, double[], double[]) | Létrehoz egy új táblázatot, és a megadott indexnél beszúrja a shape collection-be. |
| [InsertVideoFrame](../../aspose.slides/ishapecollection/insertvideoframe)(int, float, float, float, float, string) | Létrehoz egy új videó keretet, és a megadott indexnél beszúrja a shape collection-be. |
| [InsertZoomFrame](../../aspose.slides/ishapecollection/insertzoomframe#insertzoomframe)(int, float, float, float, float, ISlide) | Létrehoz egy új Zoom keretet, és a megadott indexnél beszúrja a shape collection-be. |
| [InsertZoomFrame](../../aspose.slides/ishapecollection/insertzoomframe#insertzoomframe_1)(int, float, float, float, float, ISlide, IPPImage) | Létrehoz egy új Zoom keretet előre definiált képpel, és a megadott indexnél beszúrja a shape collection-be. |
| [Remove](../../aspose.slides/ishapecollection/remove)(IShape) | Eltávolítja a megadott alakzat első előfordulását a shape collection-ből. |
| [RemoveAt](../../aspose.slides/ishapecollection/removeat)(int) | Eltávolítja a shape collection-ben a megadott indexnél lévő alakzatot. |
| [Reorder](../../aspose.slides/ishapecollection/reorder#reorder)(int, IShape) | Áthelyezi a megadott alakzatot egy új pozícióba a shape collection-ben. |
| [Reorder](../../aspose.slides/ishapecollection/reorder#reorder_1)(int, params IShape[]) | Áthelyezi a megadott alakzatokat a shape collection-ben, a megadott indexnél kezdve. |
| [ToArray](../../aspose.slides/ishapecollection/toarray#toarray)() | Létrehoz és visszaad egy tömböt, amely az összes alakzatot tartalmazza. |
| [ToArray](../../aspose.slides/ishapecollection/toarray#toarray_1)(int, int) | Létrehoz és visszaad egy tömböt, amely a megadott tartományban lévő összes alakzatot tartalmazza. |

### Lásd még

* interfész [IGenericCollection&lt;T&gt;](../igenericcollection-1)
* interfész [IShape](../ishape)
* névtér [Aspose.Slides](../../aspose.slides)
* összeállítás [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->