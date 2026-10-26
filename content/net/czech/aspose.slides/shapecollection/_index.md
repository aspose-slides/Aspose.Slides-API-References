---
title: ShapeCollection
second_title: Aspose.Sildes pro .NET – reference API
description: Představuje kolekci tvarů.
type: docs
weight: 9860
url: /cs/aspose.slides/shapecollection/
---
## ShapeCollection třída

Představuje kolekci tvarů.

```csharp
public sealed class ShapeCollection : DomObject<GroupShape>, IShapeCollection
```

## Vlastnosti

| Název | Popis |
| --- | --- |
| [Count](../../aspose.slides/shapecollection/count) { get; } | Získá počet skutečně obsažených prvků v kolekci. Jen pro čtení Int32. |
| [IsSynchronized](../../aspose.slides/shapecollection/issynchronized) { get; } | Vrátí hodnotu, která určuje, zda je přístup ke kolekci synchronizován (vláknově bezpečný). Jen pro čtení Boolean. |
| [Item](../../aspose.slides/shapecollection/item) { get; } | Získá prvek na zadaném indexu. Jen pro čtení [`IShape`](../ishape). |
| [ParentGroup](../../aspose.slides/shapecollection/parentgroup) { get; } | Získá objekt nadřazeného skupinového tvaru pro kolekci tvarů. Jen pro čtení [`IGroupShape`](../igroupshape). |
| [SyncRoot](../../aspose.slides/shapecollection/syncroot) { get; } | Vrátí kořen synchronizace. Jen pro čtení Object. |

## Metody

| Název | Popis |
| --- | --- |
| [AddAudioFrameCD](../../aspose.slides/shapecollection/addaudioframecd)(float, float, float, float) | Vytvoří nový audio rámeček propojený s CD stopou a přidá jej na konec kolekce tvarů. |
| [AddAudioFrameEmbedded](../../aspose.slides/shapecollection/addaudioframeembedded#addaudioframeembedded)(float, float, float, float, IAudio) | Vytvoří nový audio rámeček a přidá jej na konec kolekce tvarů pomocí existujícího audio objektu ze seznamu Presentation.Audios. |
| [AddAudioFrameEmbedded](../../aspose.slides/shapecollection/addaudioframeembedded#addaudioframeembedded_1)(float, float, float, float, Stream) | Vytvoří nový audio rámeček s vloženým souborem WAV a přidá jej na konec kolekce tvarů. Vložený audio soubor je přidán do kolekce Presentation.Audios. |
| [AddAudioFrameLinked](../../aspose.slides/shapecollection/addaudioframelinked)(float, float, float, float, string) | Vytvoří nový audio rámeček propojený s externím audio souborem a přidá jej na konec kolekce tvarů. |
| [AddAutoShape](../../aspose.slides/shapecollection/addautoshape#addautoshape)(ShapeType, float, float, float, float) | Vytvoří nový automatický tvar s výchozím formátováním a přidá jej na konec kolekce tvarů. |
| [AddAutoShape](../../aspose.slides/shapecollection/addautoshape#addautoshape_1)(ShapeType, float, float, float, float, bool) | Vytvoří nový automatický tvar a přidá jej na konec kolekce tvarů, volitelně jej inicializuje výchozím formátováním šablony. |
| [AddChart](../../aspose.slides/shapecollection/addchart#addchart)(ChartType, float, float, float, float) | Vytvoří nový graf, inicializuje jej ukázkovými daty řady a nastaveními a přidá jej na konec kolekce tvarů. |
| [AddChart](../../aspose.slides/shapecollection/addchart#addchart_1)(ChartType, float, float, float, float, bool) | Vytvoří nový graf, inicializuje jej ukázkovými daty řady a nastaveními a přidá jej na konec kolekce tvarů. |
| [AddClone](../../aspose.slides/shapecollection/addclone#addclone)(IShape) | Vytvoří kopii zadaného tvaru a přidá ji na konec kolekce tvarů. Klonovaný tvar zachovává původní polohu a velikost. |
| [AddClone](../../aspose.slides/shapecollection/addclone#addclone_1)(IShape, float, float) | Vytvoří kopii zadaného tvaru a přidá ji na konec kolekce tvarů. Nový tvar zachovává šířku a výšku *sourceShape*. |
| [AddClone](../../aspose.slides/shapecollection/addclone#addclone_2)(IShape, float, float, float, float) | Vytvoří kopii zadaného tvaru a přidá ji na konec kolekce tvarů. |
| [AddConnector](../../aspose.slides/shapecollection/addconnector#addconnector)(ShapeType, float, float, float, float) | Vytvoří nový spojovací tvar s výchozím stylováním šablony a přidá jej na konec kolekce tvarů. |
| [AddConnector](../../aspose.slides/shapecollection/addconnector#addconnector_1)(ShapeType, float, float, float, float, bool) | Vytvoří nový spojovací tvar a přidá jej na konec kolekce tvarů, volitelně použije výchozí stylování šablony. |
| [AddGroupShape](../../aspose.slides/shapecollection/addgroupshape#addgroupshape)() | Vytvoří nový prázdný skupinový tvar a přidá jej na konec kolekce tvarů. Rám skupiny se automaticky přizpůsobí tak, aby pojmul všechny přidané tvary. |
| [AddGroupShape](../../aspose.slides/shapecollection/addgroupshape#addgroupshape_1)(ISvgImage, float, float, float, float) | Vytvoří nový skupinový tvar, převede zadaný SVG obrázek na jednotlivé tvary a přidá vzniklou skupinu na konec kolekce tvarů. |
| [AddMathShape](../../aspose.slides/shapecollection/addmathshape)(float, float, float, float) | Vytvoří nový obdélníkový automatický tvar pro matematický obsah a přidá jej na konec kolekce tvarů. |
| [AddOleObjectFrame](../../aspose.slides/shapecollection/addoleobjectframe#addoleobjectframe)(float, float, float, float, IOleEmbeddedDataInfo) | Vytvoří nový OLE objektový rám a přidá jej na konec kolekce tvarů. |
| [AddOleObjectFrame](../../aspose.slides/shapecollection/addoleobjectframe#addoleobjectframe_1)(float, float, float, float, string, string) | Vytvoří nový OLE objektový rám a přidá jej na konec kolekce tvarů. |
| [AddPictureFrame](../../aspose.slides/shapecollection/addpictureframe)(ShapeType, float, float, float, float, IPPImage) | Vytvoří nový obrazový rám obsahující zadaný obrázek a přidá jej na konec kolekce tvarů. |
| [AddSectionZoomFrame](../../aspose.slides/shapecollection/addsectionzoomframe#addsectionzoomframe)(float, float, float, float, ISection) | Vytvoří nový rámeček Section Zoom a přidá jej na konec kolekce tvarů. |
| [AddSectionZoomFrame](../../aspose.slides/shapecollection/addsectionzoomframe#addsectionzoomframe_1)(float, float, float, float, ISection, IPPImage) | Vytvoří nový rámeček Section Zoom s předdefinovaným obrázkem a přidá jej na konec kolekce tvarů. |
| [AddSmartArt](../../aspose.slides/shapecollection/addsmartart)(float, float, float, float, SmartArtLayoutType) | Vytvoří diagram SmartArt a přidá jej na konec kolekce tvarů. |
| [AddSummaryZoomFrame](../../aspose.slides/shapecollection/addsummaryzoomframe)(float, float, float, float) | Vytvoří nový rámeček Summary Zoom a přidá jej na konec kolekce tvarů. |
| [AddTable](../../aspose.slides/shapecollection/addtable)(float, float, double[], double[]) | Vytvoří novou tabulku a přidá ji na konec kolekce tvarů. |
| [AddVideoFrame](../../aspose.slides/shapecollection/addvideoframe#addvideoframe)(float, float, float, float, IVideo) | Vytvoří nový video rámeček a přidá jej na konec kolekce tvarů. |
| [AddVideoFrame](../../aspose.slides/shapecollection/addvideoframe#addvideoframe_1)(float, float, float, float, string) | Vytvoří nový video rámeček a přidá jej na konec kolekce tvarů. |
| [AddZoomFrame](../../aspose.slides/shapecollection/addzoomframe#addzoomframe)(float, float, float, float, ISlide) | Vytvoří nový Zoom rámeček a přidá jej na konec kolekce tvarů. |
| [AddZoomFrame](../../aspose.slides/shapecollection/addzoomframe#addzoomframe_1)(float, float, float, float, ISlide, IPPImage) | Vytvoří nový Zoom rámeček a přidá jej na konec kolekce tvarů. |
| [Clear](../../aspose.slides/shapecollection/clear)() | Odstraní všechny tvary z kolekce tvarů. |
| [CopyTo](../../aspose.slides/shapecollection/copyto)(Array, int) | Zkopíruje všechny prvky z kolekce do zadaného pole. |
| [GetEnumerator](../../aspose.slides/shapecollection/getenumerator)() | Vrátí enumerátor, který prochází kolekcí. |
| [IndexOf](../../aspose.slides/shapecollection/indexof)(IShape) | Vrátí nulový index první výskytu zadaného tvaru v kolekci. |
| [InsertAudioFrameCD](../../aspose.slides/shapecollection/insertaudioframecd)(int, float, float, float, float) | Vytvoří nový audio rámeček propojený s CD stopou a vloží jej do kolekce tvarů na zadaný index. |
| [InsertAudioFrameEmbedded](../../aspose.slides/shapecollection/insertaudioframeembedded#insertaudioframeembedded)(int, float, float, float, float, IAudio) | Vytvoří nový audio rámeček a vloží jej do kolekce tvarů na zadaný index pomocí existujícího audio objektu ze seznamu Presentation.Audios. |
| [InsertAudioFrameEmbedded](../../aspose.slides/shapecollection/insertaudioframeembedded#insertaudioframeembedded_1)(int, float, float, float, float, Stream) | Vytvoří nový audio rámeček s vloženým souborem WAV a vloží jej do kolekce tvarů na zadaný index. Vložený audio soubor je přidán do kolekce Presentation.Audios. |
| [InsertAudioFrameLinked](../../aspose.slides/shapecollection/insertaudioframelinked)(int, float, float, float, float, string) | Vytvoří nový audio rámeček propojený s externím audio souborem a vloží jej do kolekce tvarů na zadaný index. |
| [InsertAutoShape](../../aspose.slides/shapecollection/insertautoshape#insertautoshape)(int, ShapeType, float, float, float, float) | Vytvoří nový automatický tvar a vloží jej do kolekce tvarů na zadaný index, použije výchozí formátování šablony. |
| [InsertAutoShape](../../aspose.slides/shapecollection/insertautoshape#insertautoshape_1)(int, ShapeType, float, float, float, float, bool) | Vytvoří nový automatický tvar a vloží jej do kolekce tvarů na zadaný index, volitelně jej inicializuje výchozím stylováním šablony. |
| [InsertChart](../../aspose.slides/shapecollection/insertchart#insertchart)(ChartType, float, float, float, float, int) | Vytvoří nový graf, inicializuje jej ukázkovými daty řady a nastaveními a vloží jej do kolekce tvarů na zadaný index. |
| [InsertChart](../../aspose.slides/shapecollection/insertchart#insertchart_1)(ChartType, float, float, float, float, int, bool) | Vytvoří nový graf, inicializuje jej ukázkovými daty řady a nastaveními a vloží jej do kolekce tvarů na zadaný index. |
| [InsertClone](../../aspose.slides/shapecollection/insertclone#insertclone)(int, IShape) | Vytvoří kopii zadaného tvaru a vloží ji do kolekce tvarů na zadaný index. Klonovaný tvar zachovává původní polohu a velikost. |
| [InsertClone](../../aspose.slides/shapecollection/insertclone#insertclone_1)(int, IShape, float, float) | Vytvoří kopii zadaného tvaru a vloží ji do kolekce tvarů na zadaný index. Nový tvar zachovává šířku a výšku *sourceShape*. |
| [InsertClone](../../aspose.slides/shapecollection/insertclone#insertclone_2)(int, IShape, float, float, float, float) | Vytvoří kopii zadaného tvaru a vloží ji do kolekce tvarů na zadaný index. |
| [InsertConnector](../../aspose.slides/shapecollection/insertconnector#insertconnector)(int, ShapeType, float, float, float, float) | Vytvoří nový spojovací tvar a vloží jej do kolekce tvarů na zadaný index, použije výchozí stylování šablony. |
| [InsertConnector](../../aspose.slides/shapecollection/insertconnector#insertconnector_1)(int, ShapeType, float, float, float, float, bool) | Vytvoří nový spojovací tvar a vloží jej do kolekce tvarů na zadaný index, volitelně použije výchozí stylování šablony. |
| [InsertGroupShape](../../aspose.slides/shapecollection/insertgroupshape)(int) | Vytvoří nový prázdný skupinový tvar a vloží jej do kolekce tvarů na zadaný index. Rám skupiny se automaticky přizpůsobí tak, aby pojmul všechny přidané tvary. |
| [InsertOleObjectFrame](../../aspose.slides/shapecollection/insertoleobjectframe#insertoleobjectframe)(int, float, float, float, float, IOleEmbeddedDataInfo) | Vytvoří nový OLE objektový rám a vloží jej do kolekce tvarů na zadaný index. |
| [InsertOleObjectFrame](../../aspose.slides/shapecollection/insertoleobjectframe#insertoleobjectframe_1)(int, float, float, float, float, string, string) | Vytvoří nový OLE objektový rám a vloží jej do kolekce tvarů na zadaný index. |
| [InsertPictureFrame](../../aspose.slides/shapecollection/insertpictureframe)(int, ShapeType, float, float, float, float, IPPImage) | Vytvoří nový obrazový rám obsahující zadaný obrázek a vloží jej do kolekce tvarů na zadaný index. |
| [InsertSectionZoomFrame](../../aspose.slides/shapecollection/insertsectionzoomframe#insertsectionzoomframe)(int, float, float, float, float, ISection) | Vytvoří nový rámeček Section Zoom a vloží jej do kolekce tvarů na zadaný index. |
| [InsertSectionZoomFrame](../../aspose.slides/shapecollection/insertsectionzoomframe#insertsectionzoomframe_1)(int, float, float, float, float, ISection, IPPImage) | Vytvoří nový rámeček Section Zoom s předdefinovaným obrázkem a vloží jej do kolekce tvarů na zadaný index. |
| [InsertSummaryZoomFrame](../../aspose.slides/shapecollection/insertsummaryzoomframe)(int, float, float, float, float) | Vytvoří nový rámeček Summary Zoom a vloží jej do kolekce tvarů na zadaný index. |
| [InsertTable](../../aspose.slides/shapecollection/inserttable)(int, float, float, double[], double[]) | Vytvoří novou tabulku a vloží ji do kolekce tvarů na zadaný index. |
| [InsertVideoFrame](../../aspose.slides/shapecollection/insertvideoframe)(int, float, float, float, float, string) | Vytvoří nový video rámeček a vloží jej do kolekce tvarů na zadaný index. |
| [InsertZoomFrame](../../aspose.slides/shapecollection/insertzoomframe#insertzoomframe)(int, float, float, float, float, ISlide) | Vytvoří nový Zoom rámeček a vloží jej do kolekce tvarů na zadaný index. |
| [InsertZoomFrame](../../aspose.slides/shapecollection/insertzoomframe#insertzoomframe_1)(int, float, float, float, float, ISlide, IPPImage) | Vytvoří nový Zoom rámeček s předdefinovaným obrázkem a vloží jej do kolekce tvarů na zadaný index. |
| [Remove](../../aspose.slides/shapecollection/remove)(IShape) | Odstraní první výskyt zadaného tvaru z kolekce tvarů. |
| [RemoveAt](../../aspose.slides/shapecollection/removeat)(int) | Odstraní tvar na zadaném indexu z kolekce tvarů. |
| [Reorder](../../aspose.slides/shapecollection/reorder#reorder)(int, IShape) | Přesune zadaný tvar na novou pozici v kolekci tvarů. |
| [Reorder](../../aspose.slides/shapecollection/reorder#reorder_1)(int, params IShape[]) | Přesune zadané tvary v kolekci tvarů a umístí je počínaje daným indexem. |
| [ToArray](../../aspose.slides/shapecollection/toarray#toarray)() | Vytvoří a vrátí pole obsahující všechny tvary. |
| [ToArray](../../aspose.slides/shapecollection/toarray#toarray_1)(int, int) | Vytvoří a vrátí pole obsahující všechny tvary v zadaném rozsahu. |

### Viz také

* třída [DomObject&lt;TParent&gt;](../domobject-1)
* třída [GroupShape](../groupshape)
* rozhraní [IShapeCollection](../ishapecollection)
* jmenný prostor [Aspose.Slides](../../aspose.slides)
* sestavení [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->