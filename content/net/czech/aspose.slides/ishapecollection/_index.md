---
title: IShapeCollection
second_title: Aspose.Sildes pro .NET API Reference
description: Representuje kolekci tvarů.
type: docs
weight: 6960
url: /cs/aspose.slides/ishapecollection/
---
## IShapeCollection rozhraní

Represents a collection of shapes.

```csharp
public interface IShapeCollection : IGenericCollection<IShape>
```

## Vlastnosti

| Name | Description |
| --- | --- |
| [Item](../../aspose.slides/ishapecollection/item) { get; } | Získá prvek na zadaném indexu. Pouze pro čtení [`IShape`](../ishape). |
| [ParentGroup](../../aspose.slides/ishapecollection/parentgroup) { get; } | Získá objekt rodičovské skupiny tvarů pro sbírku tvarů. Pouze pro čtení [`IGroupShape`](../igroupshape). |

## Metody

| Name | Description |
| --- | --- |
| [AddAudioFrameCD](../../aspose.slides/ishapecollection/addaudioframecd)(float, float, float, float) | Vytvoří nový audio rámec propojený s CD stopou a přidá jej na konec sbírky tvarů. |
| [AddAudioFrameEmbedded](../../aspose.slides/ishapecollection/addaudioframeembedded#addaudioframeembedded)(float, float, float, float, IAudio) | Vytvoří nový audio rámec a přidá jej na konec sbírky tvarů pomocí existujícího audio objektu ze seznamu Presentation.Audios. |
| [AddAudioFrameEmbedded](../../aspose.slides/ishapecollection/addaudioframeembedded#addaudioframeembedded_1)(float, float, float, float, Stream) | Vytvoří nový audio rámec s vloženým WAV souborem a přidá jej na konec sbírky tvarů. Vložený audio je přidán do sbírky Presentation.Audios. |
| [AddAudioFrameLinked](../../aspose.slides/ishapecollection/addaudioframelinked)(float, float, float, float, string) | Vytvoří nový audio rámec propojený s externím audio souborem a přidá jej na konec sbírky tvarů. |
| [AddAutoShape](../../aspose.slides/ishapecollection/addautoshape#addautoshape)(ShapeType, float, float, float, float) | Vytvoří nový automatický tvar s výchozím formátováním a přidá jej na konec sbírky tvarů. |
| [AddAutoShape](../../aspose.slides/ishapecollection/addautoshape#addautoshape_1)(ShapeType, float, float, float, float, bool) | Vytvoří nový automatický tvar a přidá jej na konec sbírky tvarů, volitelně jej inicializuje výchozím formátováním šablony. |
| [AddChart](../../aspose.slides/ishapecollection/addchart#addchart)(ChartType, float, float, float, float) | Vytvoří nový graf, inicializuje jej ukázkovými daty řad a nastaveními a přidá jej na konec sbírky tvarů. |
| [AddChart](../../aspose.slides/ishapecollection/addchart#addchart_1)(ChartType, float, float, float, float, bool) | Vytvoří nový graf, inicializuje jej ukázkovými daty řad a nastaveními a přidá jej na konec sbírky tvarů. |
| [AddClone](../../aspose.slides/ishapecollection/addclone#addclone)(IShape) | Vytvoří kopii zadaného tvaru a přidá ji na konec sbírky tvarů. Zkopírovaný tvar zachovává původní polohu a velikost. |
| [AddClone](../../aspose.slides/ishapecollection/addclone#addclone_1)(IShape, float, float) | Vytvoří kopii zadaného tvaru a přidá ji na konec sbírky tvarů. Nový tvar zachovává šířku a výšku *sourceShape*. |
| [AddClone](../../aspose.slides/ishapecollection/addclone#addclone_2)(IShape, float, float, float, float) | Vytvoří kopii zadaného tvaru a přidá ji na konec sbírky tvarů. |
| [AddConnector](../../aspose.slides/ishapecollection/addconnector#addconnector)(ShapeType, float, float, float, float) | Vytvoří nový konektorový tvar s výchozím stylováním šablony a přidá jej na konec sbírky tvarů. |
| [AddConnector](../../aspose.slides/ishapecollection/addconnector#addconnector_1)(ShapeType, float, float, float, float, bool) | Vytvoří nový konektorový tvar a přidá jej na konec sbírky tvarů, volitelně použije výchozí stylování šablony. |
| [AddGroupShape](../../aspose.slides/ishapecollection/addgroupshape#addgroupshape)() | Vytvoří novou prázdnou skupinu tvarů a přidá ji na konec sbírky tvarů. Rámec skupiny se automaticky upraví, aby pojmul všechny přidané tvary. |
| [AddGroupShape](../../aspose.slides/ishapecollection/addgroupshape#addgroupshape_1)(ISvgImage, float, float, float, float) | Vytvoří novou skupinu tvarů, převede zadaný SVG obrázek na jednotlivé tvary a přidá výslednou skupinu na konec sbírky tvarů. |
| [AddMathShape](../../aspose.slides/ishapecollection/addmathshape)(float, float, float, float) | Vytvoří nový automatický obdélníkový tvar pro matematický obsah a přidá jej na konec sbírky tvarů. |
| [AddOleObjectFrame](../../aspose.slides/ishapecollection/addoleobjectframe#addoleobjectframe)(float, float, float, float, IOleEmbeddedDataInfo) | Vytvoří nový OLE objektový rámec a přidá jej na konec sbírky tvarů. |
| [AddOleObjectFrame](../../aspose.slides/ishapecollection/addoleobjectframe#addoleobjectframe_1)(float, float, float, float, string, string) | Vytvoří nový OLE objektový rámec a přidá jej na konec sbírky tvarů. |
| [AddPictureFrame](../../aspose.slides/ishapecollection/addpictureframe)(ShapeType, float, float, float, float, IPPImage) | Vytvoří nový rámeček s obrázkem obsahujícím zadaný obrázek a přidá jej na konec sbírky tvarů. |
| [AddSectionZoomFrame](../../aspose.slides/ishapecollection/addsectionzoomframe#addsectionzoomframe)(float, float, float, float, ISection) | Vytvoří nový snímek Zoom sekce a přidá jej na konec sbírky tvarů. |
| [AddSectionZoomFrame](../../aspose.slides/ishapecollection/addsectionzoomframe#addsectionzoomframe_1)(float, float, float, float, ISection, IPPImage) | Vytvoří nový snímek Zoom sekce s předdefinovaným obrázkem a přidá jej na konec sbírky tvarů. |
| [AddSmartArt](../../aspose.slides/ishapecollection/addsmartart)(float, float, float, float, SmartArtLayoutType) | Vytvoří diagram SmartArt a přidá jej na konec sbírky tvarů. |
| [AddSummaryZoomFrame](../../aspose.slides/ishapecollection/addsummaryzoomframe)(float, float, float, float) | Vytvoří nový rámeček souhrnu Zoom a přidá jej na konec sbírky tvarů. |
| [AddTable](../../aspose.slides/ishapecollection/addtable)(float, float, double[], double[]) | Vytvoří novou tabulku a přidá ji na konec sbírky tvarů. |
| [AddVideoFrame](../../aspose.slides/ishapecollection/addvideoframe#addvideoframe)(float, float, float, float, IVideo) | Vytvoří nový video rámec a přidá jej na konec sbírky tvarů. |
| [AddVideoFrame](../../aspose.slides/ishapecollection/addvideoframe#addvideoframe_1)(float, float, float, float, string) | Vytvoří nový video rámec a přidá jej na konec sbírky tvarů. |
| [AddZoomFrame](../../aspose.slides/ishapecollection/addzoomframe#addzoomframe)(float, float, float, float, ISlide) | Vytvoří nový Zoom rámec a přidá jej na konec sbírky tvarů. |
| [AddZoomFrame](../../aspose.slides/ishapecollection/addzoomframe#addzoomframe_1)(float, float, float, float, ISlide, IPPImage) | Vytvoří nový Zoom rámec a přidá jej na konec sbírky tvarů. |
| [Clear](../../aspose.slides/ishapecollection/clear)() | Odstraní všechny tvary ze sbírky tvarů. |
| [IndexOf](../../aspose.slides/ishapecollection/indexof)(IShape) | Vrací index (od nuly) prvního výskytu zadaného tvaru ve sbírce. |
| [InsertAudioFrameCD](../../aspose.slides/ishapecollection/insertaudioframecd)(int, float, float, float, float) | Vytvoří nový audio rámec propojený s CD stopou a vloží jej do sbírky tvarů na zadaný index. |
| [InsertAudioFrameEmbedded](../../aspose.slides/ishapecollection/insertaudioframeembedded#insertaudioframeembedded)(int, float, float, float, float, IAudio) | Vytvoří nový audio rámec a vloží jej do sbírky tvarů na zadaný index pomocí existujícího audio objektu ze seznamu Presentation.Audios. |
| [InsertAudioFrameEmbedded](../../aspose.slides/ishapecollection/insertaudioframeembedded#insertaudioframeembedded_1)(int, float, float, float, float, Stream) | Vytvoří nový audio rámec s vloženým WAV souborem a vloží jej do sbírky tvarů na zadaný index. Vložený audio je přidán do sbírky Presentation.Audios. |
| [InsertAudioFrameLinked](../../aspose.slides/ishapecollection/insertaudioframelinked)(int, float, float, float, float, string) | Vytvoří nový audio rámec propojený s externím audio souborem a vloží jej do sbírky tvarů na zadaný index. |
| [InsertAutoShape](../../aspose.slides/ishapecollection/insertautoshape#insertautoshape)(int, ShapeType, float, float, float, float) | Vytvoří nový automatický tvar a vloží jej do sbírky tvarů na zadaný index s výchozím formátováním šablony. |
| [InsertAutoShape](../../aspose.slides/ishapecollection/insertautoshape#insertautoshape_1)(int, ShapeType, float, float, float, float, bool) | Vytvoří nový automatický tvar a vloží jej do sbírky tvarů na zadaný index, volitelně jej inicializuje výchozím stylováním šablony. |
| [InsertChart](../../aspose.slides/ishapecollection/insertchart#insertchart)(ChartType, float, float, float, float, int) | Vytvoří nový graf, inicializuje jej ukázkovými daty řad a nastaveními a vloží jej do sbírky tvarů na zadaný index. |
| [InsertChart](../../aspose.slides/ishapecollection/insertchart#insertchart_1)(ChartType, float, float, float, float, int, bool) | Vytvoří nový graf, inicializuje jej ukázkovými daty řad a nastaveními a vloží jej do sbírky tvarů na zadaný index. |
| [InsertClone](../../aspose.slides/ishapecollection/insertclone#insertclone)(int, IShape) | Vytvoří kopii zadaného tvaru a vloží ji do sbírky tvarů na zadaný index. Zkopírovaný tvar zachovává původní polohu a velikost. |
| [InsertClone](../../aspose.slides/ishapecollection/insertclone#insertclone_1)(int, IShape, float, float) | Vytvoří kopii zadaného tvaru a vloží ji do sbírky tvarů na zadaný index. Nový tvar zachová šířku a výšku *sourceShape*. |
| [InsertClone](../../aspose.slides/ishapecollection/insertclone#insertclone_2)(int, IShape, float, float, float, float) | Vytvoří kopii zadaného tvaru a vloží ji do sbírky tvarů na zadaný index. |
| [InsertConnector](../../aspose.slides/ishapecollection/insertconnector#insertconnector)(int, ShapeType, float, float, float, float) | Vytvoří nový konektorový tvar a vloží jej do sbírky tvarů na zadaný index s výchozím stylováním šablony. |
| [InsertConnector](../../aspose.slides/ishapecollection/insertconnector#insertconnector_1)(int, ShapeType, float, float, float, float, bool) | Vytvoří nový konektorový tvar a vloží jej do sbírky tvarů na zadaný index, volitelně použije výchozí stylování šablony. |
| [InsertGroupShape](../../aspose.slides/ishapecollection/insertgroupshape)(int) | Vytvoří novou prázdnou skupinu tvarů a vloží ji do sbírky tvarů na zadaný index. Rámec skupiny se automaticky upraví, aby pojmul všechny přidané tvary. |
| [InsertOleObjectFrame](../../aspose.slides/ishapecollection/insertoleobjectframe#insertoleobjectframe)(int, float, float, float, float, IOleEmbeddedDataInfo) | Vytvoří nový OLE objektový rámec a vloží jej do sbírky tvarů na zadaný index. |
| [InsertOleObjectFrame](../../aspose.slides/ishapecollection/insertoleobjectframe#insertoleobjectframe_1)(int, float, float, float, float, string, string) | Vytvoří nový OLE objektový rámec a vloží jej do sbírky tvarů na zadaný index. |
| [InsertPictureFrame](../../aspose.slides/ishapecollection/insertpictureframe)(int, ShapeType, float, float, float, float, IPPImage) | Vytvoří nový rámeček s obrázkem obsahujícím zadaný obrázek a vloží jej do sbírky tvarů na zadaný index. |
| [InsertSectionZoomFrame](../../aspose.slides/ishapecollection/insertsectionzoomframe#insertsectionzoomframe)(int, float, float, float, float, ISection) | Vytvoří nový snímek Zoom sekce a vloží jej do sbírky tvarů na zadaný index. |
| [InsertSectionZoomFrame](../../aspose.slides/ishapecollection/insertsectionzoomframe#insertsectionzoomframe_1)(int, float, float, float, float, ISection, IPPImage) | Vytvoří nový snímek Zoom sekce s předdefinovaným obrázkem a vloží jej do sbírky tvarů na zadaný index. |
| [InsertSummaryZoomFrame](../../aspose.slides/ishapecollection/insertsummaryzoomframe)(int, float, float, float, float) | Vytvoří nový rámeček souhrnu Zoom a vloží jej do sbírky tvarů na zadaný index. |
| [InsertTable](../../aspose.slides/ishapecollection/inserttable)(int, float, float, double[], double[]) | Vytvoří novou tabulku a vloží ji do sbírky tvarů na zadaný index. |
| [InsertVideoFrame](../../aspose.slides/ishapecollection/insertvideoframe)(int, float, float, float, float, string) | Vytvoří nový video rámec a vloží jej do sbírky tvarů na zadaný index. |
| [InsertZoomFrame](../../aspose.slides/ishapecollection/insertzoomframe#insertzoomframe)(int, float, float, float, float, ISlide) | Vytvoří nový Zoom rámec a vloží jej do sbírky tvarů na zadaný index. |
| [InsertZoomFrame](../../aspose.slides/ishapecollection/insertzoomframe#insertzoomframe_1)(int, float, float, float, float, ISlide, IPPImage) | Vytvoří nový Zoom rámec s předdefinovaným obrázkem a vloží jej do sbírky tvarů na zadaný index. |
| [Remove](../../aspose.slides/ishapecollection/remove)(IShape) | Odstraní první výskyt zadaného tvaru ze sbírky tvarů. |
| [RemoveAt](../../aspose.slides/ishapecollection/removeat)(int) | Odstraní tvar na zadaném indexu ze sbírky tvarů. |
| [Reorder](../../aspose.slides/ishapecollection/reorder#reorder)(int, IShape) | Přesune zadaný tvar na novou pozici ve sbírce tvarů. |
| [Reorder](../../aspose.slides/ishapecollection/reorder#reorder_1)(int, params IShape[]) | Přesune zadané tvary ve sbírce tvarů a umístí je počínaje daným indexem. |
| [ToArray](../../aspose.slides/ishapecollection/toarray#toarray)() | Vytvoří a vrátí pole obsahující všechny tvary. |
| [ToArray](../../aspose.slides/ishapecollection/toarray#toarray_1)(int, int) | Vytvoří a vrátí pole obsahující všechny tvary v zadaném rozsahu. |

### Viz také

* interface [IGenericCollection&lt;T&gt;](../igenericcollection-1)
* interface [IShape](../ishape)
* namespace [Aspose.Slides](../../aspose.slides)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->