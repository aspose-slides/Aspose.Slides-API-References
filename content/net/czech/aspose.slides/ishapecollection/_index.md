---
title: IShapeCollection
second_title: Aspose.Sildes pro .NET API Reference
description: Reprezentuje kolekci tvarů.
type: docs
weight: 6980
url: /cs/aspose.slides/ishapecollection/
---
## IShapeCollection rozhraní

Represents a collection of shapes.

```csharp
public interface IShapeCollection : IGenericCollection<IShape>
```

## Vlastnosti

| Název | Popis |
| --- | --- |
| [Item](../../aspose.slides/ishapecollection/item) { get; } | Vrací prvek na zadaném indexu. Pouze pro čtení [`IShape`](../ishape). |
| [ParentGroup](../../aspose.slides/ishapecollection/parentgroup) { get; } | Vrací objekt nadřazeného skupinového tvaru pro kolekci tvarů. Pouze pro čtení [`IGroupShape`](../igroupshape). |

## Metody

| Název | Popis |
| --- | --- |
| [AddAudioFrameCD](../../aspose.slides/ishapecollection/addaudioframecd)(float, float, float, float) | Vytvoří nový audio rámec propojený s CD stopou a přidá jej na konec kolekce tvarů. |
| [AddAudioFrameEmbedded](../../aspose.slides/ishapecollection/addaudioframeembedded#addaudioframeembedded)(float, float, float, float, IAudio) | Vytvoří nový audio rámec a přidá jej na konec kolekce tvarů pomocí existujícího audio objektu ze seznamu Presentation.Audios. |
| [AddAudioFrameEmbedded](../../aspose.slides/ishapecollection/addaudioframeembedded#addaudioframeembedded_1)(float, float, float, float, Stream) | Vytvoří nový audio rámec s vloženým souborem WAV a přidá jej na konec kolekce tvarů. Vložený audio soubor je přidán do kolekce Presentation.Audios. |
| [AddAudioFrameLinked](../../aspose.slides/ishapecollection/addaudioframelinked)(float, float, float, float, string) | Vytvoří nový audio rámec propojený s externím audio souborem a přidá jej na konec kolekce tvarů. |
| [AddAutoShape](../../aspose.slides/ishapecollection/addautoshape#addautoshape)(ShapeType, float, float, float, float) | Vytvoří nový automatický tvar s výchozím formátováním a přidá jej na konec kolekce tvarů. |
| [AddAutoShape](../../aspose.slides/ishapecollection/addautoshape#addautoshape_1)(ShapeType, float, float, float, float, bool) | Vytvoří nový automatický tvar a přidá jej na konec kolekce tvarů, volitelně jej inicializuje s výchozím formátováním šablony. |
| [AddChart](../../aspose.slides/ishapecollection/addchart#addchart)(ChartType, float, float, float, float) | Vytvoří nový graf, inicializuje jej s ukázkovými daty řad a nastaveními a přidá jej na konec kolekce tvarů. |
| [AddChart](../../aspose.slides/ishapecollection/addchart#addchart_1)(ChartType, float, float, float, float, bool) | Vytvoří nový graf, inicializuje jej s ukázkovými daty řad a nastaveními a přidá jej na konec kolekce tvarů, volitelně. |
| [AddClone](../../aspose.slides/ishapecollection/addclone#addclone)(IShape) | Vytvoří kopii zadaného tvaru a přidá ji na konec kolekce tvarů. Klonovaný tvar si zachová původní pozici a velikost. |
| [AddClone](../../aspose.slides/ishapecollection/addclone#addclone_1)(IShape, float, float) | Vytvoří kopii zadaného tvaru a přidá ji na konec kolekce tvarů. Nový tvar si zachová šířku a výšku *sourceShape*. |
| [AddClone](../../aspose.slides/ishapecollection/addclone#addclone_2)(IShape, float, float, float, float) | Vytvoří kopii zadaného tvaru a přidá ji na konec kolekce tvarů. |
| [AddConnector](../../aspose.slides/ishapecollection/addconnector#addconnector)(ShapeType, float, float, float, float) | Vytvoří nový spojovací tvar s výchozím stylováním šablony a přidá jej na konec kolekce tvarů. |
| [AddConnector](../../aspose.slides/ishapecollection/addconnector#addconnector_1)(ShapeType, float, float, float, float, bool) | Vytvoří nový spojovací tvar a přidá jej na konec kolekce tvarů, volitelně použije výchozí stylování šablony. |
| [AddGroupShape](../../aspose.slides/ishapecollection/addgroupshape#addgroupshape)() | Vytvoří nový prázdný skupinový tvar a přidá jej na konec kolekce tvarů. Rám skupiny se automaticky přizpůsobí jakémukoli přidanému tvaru. |
| [AddGroupShape](../../aspose.slides/ishapecollection/addgroupshape#addgroupshape_1)(ISvgImage, float, float, float, float) | Vytvoří nový skupinový tvar, převede zadaný SVG obrázek na jednotlivé tvary a přidá vzniklou skupinu na konec kolekce tvarů. |
| [AddMathShape](../../aspose.slides/ishapecollection/addmathshape)(float, float, float, float) | Vytvoří nový obdélníkový automatický tvar pro matematický obsah a přidá jej na konec kolekce tvarů. |
| [AddOleObjectFrame](../../aspose.slides/ishapecollection/addoleobjectframe#addoleobjectframe)(float, float, float, float, IOleEmbeddedDataInfo) | Vytvoří nový rám OLE objektu a přidá jej na konec kolekce tvarů. |
| [AddOleObjectFrame](../../aspose.slides/ishapecollection/addoleobjectframe#addoleobjectframe_1)(float, float, float, float, string, string) | Vytvoří nový rám OLE objektu a přidá jej na konec kolekce tvarů. |
| [AddPictureFrame](../../aspose.slides/ishapecollection/addpictureframe)(ShapeType, float, float, float, float, IPPImage) | Vytvoří nový rámeček obrázku obsahující zadaný obrázek a přidá jej na konec kolekce tvarů. |
| [AddSectionZoomFrame](../../aspose.slides/ishapecollection/addsectionzoomframe#addsectionzoomframe)(float, float, float, float, ISection) | Vytvoří nový rámec zoomu sekce a přidá jej na konec kolekce tvarů. |
| [AddSectionZoomFrame](../../aspose.slides/ishapecollection/addsectionzoomframe#addsectionzoomframe_1)(float, float, float, float, ISection, IPPImage) | Vytvoří nový rámec zoomu sekce s předdefinovaným obrázkem a přidá jej na konec kolekce tvarů. |
| [AddSmartArt](../../aspose.slides/ishapecollection/addsmartart)(float, float, float, float, SmartArtLayoutType) | Vytvoří diagram SmartArt a přidá jej na konec kolekce tvarů. |
| [AddSummaryZoomFrame](../../aspose.slides/ishapecollection/addsummaryzoomframe)(float, float, float, float) | Vytvoří nový rámec Summary Zoom a přidá jej na konec kolekce tvarů. |
| [AddTable](../../aspose.slides/ishapecollection/addtable)(float, float, double[], double[]) | Vytvoří novou tabulku a přidá ji na konec kolekce tvarů. |
| [AddVideoFrame](../../aspose.slides/ishapecollection/addvideoframe#addvideoframe)(float, float, float, float, IVideo) | Vytvoří nový video rámec a přidá jej na konec kolekce tvarů. |
| [AddVideoFrame](../../aspose.slides/ishapecollection/addvideoframe#addvideoframe_1)(float, float, float, float, string) | Vytvoří nový video rámec a přidá jej na konec kolekce tvarů. |
| [AddZoomFrame](../../aspose.slides/ishapecollection/addzoomframe#addzoomframe)(float, float, float, float, ISlide) | Vytvoří nový Zoom rámec a přidá jej na konec kolekce tvarů. |
| [AddZoomFrame](../../aspose.slides/ishapecollection/addzoomframe#addzoomframe_1)(float, float, float, float, ISlide, IPPImage) | Vytvoří nový Zoom rámec a přidá jej na konec kolekce tvarů. |
| [Clear](../../aspose.slides/ishapecollection/clear)() | Odstraní všechny tvary z kolekce tvarů. |
| [IndexOf](../../aspose.slides/ishapecollection/indexof)(IShape) | Vrací index (od nuly) první výskyt zadaného tvaru ve sbírce. |
| [InsertAudioFrameCD](../../aspose.slides/ishapecollection/insertaudioframecd)(int, float, float, float, float) | Vytvoří nový audio rámec propojený s CD stopou a vloží jej do kolekce tvarů na zadaný index. |
| [InsertAudioFrameEmbedded](../../aspose.slides/ishapecollection/insertaudioframeembedded#insertaudioframeembedded)(int, float, float, float, float, IAudio) | Vytvoří nový audio rámec a vloží jej do kolekce tvarů na zadaný index pomocí existujícího audio objektu ze seznamu Presentation.Audios. |
| [InsertAudioFrameEmbedded](../../aspose.slides/ishapecollection/insertaudioframeembedded#insertaudioframeembedded_1)(int, float, float, float, float, Stream) | Vytvoří nový audio rámec s vloženým WAV souborem a vloží jej do kolekce tvarů na zadaný index. Vložený audio soubor je přidán do kolekce Presentation.Audios. |
| [InsertAudioFrameLinked](../../aspose.slides/ishapecollection/insertaudioframelinked)(int, float, float, float, float, string) | Vytvoří nový audio rámec propojený s externím audio souborem a vloží jej do kolekce tvarů na zadaný index. |
| [InsertAutoShape](../../aspose.slides/ishapecollection/insertautoshape#insertautoshape)(int, ShapeType, float, float, float, float) | Vytvoří nový automatický tvar a vloží jej do kolekce tvarů na zadaný index, použije výchozí formátování šablony. |
| [InsertAutoShape](../../aspose.slides/ishapecollection/insertautoshape#insertautoshape_1)(int, ShapeType, float, float, float, float, bool) | Vytvoří nový automatický tvar a vloží jej do kolekce tvarů na zadaný index, volitelně jej inicializuje s výchozím stylováním šablony. |
| [InsertChart](../../aspose.slides/ishapecollection/insertchart#insertchart)(ChartType, float, float, float, float, int) | Vytvoří nový graf, inicializuje jej s ukázkovými daty řad a nastaveními a vloží jej do kolekce tvarů na zadaný index. |
| [InsertChart](../../aspose.slides/ishapecollection/insertchart#insertchart_1)(ChartType, float, float, float, float, int, bool) | Vytvoří nový graf, inicializuje jej s ukázkovými daty řad a nastaveními a vloží jej do kolekce tvarů na zadaný index. |
| [InsertClone](../../aspose.slides/ishapecollection/insertclone#insertclone)(int, IShape) | Vytvoří kopii zadaného tvaru a vloží ji do kolekce tvarů na zadaný index. Klonovaný tvar si zachová původní pozici a velikost. |
| [InsertClone](../../aspose.slides/ishapecollection/insertclone#insertclone_1)(int, IShape, float, float) | Vytvoří kopii zadaného tvaru a vloží ji do kolekce tvarů na zadaný index. Nový tvar si zachová šířku a výšku *sourceShape*. |
| [InsertClone](../../aspose.slides/ishapecollection/insertclone#insertclone_2)(int, IShape, float, float, float, float) | Vytvoří kopii zadaného tvaru a vloží ji do kolekce tvarů na zadaný index. |
| [InsertConnector](../../aspose.slides/ishapecollection/insertconnector#insertconnector)(int, ShapeType, float, float, float, float) | Vytvoří nový spojovací tvar a vloží jej do kolekce tvarů na zadaný index, použije výchozí stylování šablony. |
| [InsertConnector](../../aspose.slides/ishapecollection/insertconnector#insertconnector_1)(int, ShapeType, float, float, float, float, bool) | Vytvoří nový spojovací tvar a vloží jej do kolekce tvarů na zadaný index, volitelně použije výchozí stylování šablony. |
| [InsertGroupShape](../../aspose.slides/ishapecollection/insertgroupshape)(int) | Vytvoří nový prázdný skupinový tvar a vloží jej do kolekce tvarů na zadaný index. Rám skupiny se automaticky přizpůsobí jakémukoli přidanému tvaru. |
| [InsertOleObjectFrame](../../aspose.slides/ishapecollection/insertoleobjectframe#insertoleobjectframe)(int, float, float, float, float, IOleEmbeddedDataInfo) | Vytvoří nový rám OLE objektu a vloží jej do kolekce tvarů na zadaný index. |
| [InsertOleObjectFrame](../../aspose.slides/ishapecollection/insertoleobjectframe#insertoleobjectframe_1)(int, float, float, float, float, string, string) | Vytvoří nový rám OLE objektu a vloží jej do kolekce tvarů na zadaný index. |
| [InsertPictureFrame](../../aspose.slides/ishapecollection/insertpictureframe)(int, ShapeType, float, float, float, float, IPPImage) | Vytvoří nový rámeček obrázku obsahující zadaný obrázek a vloží jej do kolekce tvarů na zadaný index. |
| [InsertSectionZoomFrame](../../aspose.slides/ishapecollection/insertsectionzoomframe#insertsectionzoomframe)(int, float, float, float, float, ISection) | Vytvoří nový rámec zoomu sekce a vloží jej do kolekce tvarů na zadaný index. |
| [InsertSectionZoomFrame](../../aspose.slides/ishapecollection/insertsectionzoomframe#insertsectionzoomframe_1)(int, float, float, float, float, ISection, IPPImage) | Vytvoří nový rámec zoomu sekce s předdefinovaným obrázkem a vloží jej do kolekce tvarů na zadaný index. |
| [InsertSummaryZoomFrame](../../aspose.slides/ishapecollection/insertsummaryzoomframe)(int, float, float, float, float) | Vytvoří nový rámec Summary Zoom a vloží jej do kolekce tvarů na zadaný index. |
| [InsertTable](../../aspose.slides/ishapecollection/inserttable)(int, float, float, double[], double[]) | Vytvoří novou tabulku a vloží ji do kolekce tvarů na zadaný index. |
| [InsertVideoFrame](../../aspose.slides/ishapecollection/insertvideoframe)(int, float, float, float, float, string) | Vytvoří nový video rámec a vloží jej do kolekce tvarů na zadaný index. |
| [InsertZoomFrame](../../aspose.slides/ishapecollection/insertzoomframe#insertzoomframe)(int, float, float, float, float, ISlide) | Vytvoří nový Zoom rámec a vloží jej do kolekce tvarů na zadaný index. |
| [InsertZoomFrame](../../aspose.slides/ishapecollection/insertzoomframe#insertzoomframe_1)(int, float, float, float, float, ISlide, IPPImage) | Vytvoří nový Zoom rámec s předdefinovaným obrázkem a vloží jej do kolekce tvarů na zadaný index. |
| [Remove](../../aspose.slides/ishapecollection/remove)(IShape) | Odstraní první výskyt zadaného tvaru z kolekce tvarů. |
| [RemoveAt](../../aspose.slides/ishapecollection/removeat)(int) | Odstraní tvar na zadaném indexu z kolekce tvarů. |
| [Reorder](../../aspose.slides/ishapecollection/reorder#reorder)(int, IShape) | Přesune zadaný tvar na novou pozici v rámci kolekce tvarů. |
| [Reorder](../../aspose.slides/ishapecollection/reorder#reorder_1)(int, params IShape[]) | Přesune zadané tvary v kolekci tvarů, umístí je počínaje zadaným indexem. |
| [ToArray](../../aspose.slides/ishapecollection/toarray#toarray)() | Vytvoří a vrátí pole obsahující všechny tvary. |
| [ToArray](../../aspose.slides/ishapecollection/toarray#toarray_1)(int, int) | Vytvoří a vrátí pole obsahující všechny tvary ve zvoleném rozsahu. |

### Viz také

* rozhraní [IGenericCollection&lt;T&gt;](../igenericcollection-1)
* rozhraní [IShape](../ishape)
* jmenný prostor [Aspose.Slides](../../aspose.slides)
* sestavení [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->