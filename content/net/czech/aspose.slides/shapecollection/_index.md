---
title: ShapeCollection
second_title: Aspose.Slides pro .NET - referenční příručka API
description: Representuje kolekci tvarů.
type: docs
weight: 9880
url: /cs/aspose.slides/shapecollection/
---
## ShapeCollection třída

Representuje kolekci tvarů.

```csharp
public sealed class ShapeCollection : DomObject<GroupShape>, IShapeCollection
```

## Vlastnosti

| Název | Popis |
| --- | --- |
| [Count](../../aspose.slides/shapecollection/count) { get; } | Získává počet prvků skutečně obsažených v kolekci. Pouze pro čtení Int32. |
| [IsSynchronized](../../aspose.slides/shapecollection/issynchronized) { get; } | Vrací hodnotu indikující, zda je přístup ke kolekci synchronizován (vláknově bezpečný). Pouze pro čtení Boolean. |
| [Item](../../aspose.slides/shapecollection/item) { get; } | Získává prvek na zadaném indexu. Pouze pro čtení [`IShape`](../ishape). |
| [ParentGroup](../../aspose.slides/shapecollection/parentgroup) { get; } | Získává objekt nadřazeného skupinového tvaru pro kolekci tvarů. Pouze pro čtení [`IGroupShape`](../igroupshape). |
| [SyncRoot](../../aspose.slides/shapecollection/syncroot) { get; } | Vrací kořen synchronizace. Pouze pro čtení Object. |

## Metody

| Název | Popis |
| --- | --- |
| [AddAudioFrameCD](../../aspose.slides/shapecollection/addaudioframecd)(float, float, float, float) | Vytváří nový audio rámec propojený s CD stopou a přidává jej na konec kolekce tvarů. |
| [AddAudioFrameEmbedded](../../aspose.slides/shapecollection/addaudioframeembedded#addaudioframeembedded)(float, float, float, float, IAudio) | Vytváří nový audio rámec a přidává jej na konec kolekce tvarů pomocí existujícího audio objektu ze seznamu Presentation.Audios. |
| [AddAudioFrameEmbedded](../../aspose.slides/shapecollection/addaudioframeembedded#addaudioframeembedded_1)(float, float, float, float, Stream) | Vytváří nový audio rámec s vloženým WAV souborem a přidává jej na konec kolekce tvarů. Vložený audio soubor je přidán do kolekce Presentation.Audios. |
| [AddAudioFrameLinked](../../aspose.slides/shapecollection/addaudioframelinked)(float, float, float, float, string) | Vytváří nový audio rámec propojený s externím audio souborem a přidává jej na konec kolekce tvarů. |
| [AddAutoShape](../../aspose.slides/shapecollection/addautoshape#addautoshape)(ShapeType, float, float, float, float) | Vytváří nový automatický tvar s výchozím formátováním a přidává jej na konec kolekce tvarů. |
| [AddAutoShape](../../aspose.slides/shapecollection/addautoshape#addautoshape_1)(ShapeType, float, float, float, float, bool) | Vytváří nový automatický tvar a přidává jej na konec kolekce tvarů, volitelně jej inicializuje výchozím formátováním šablony. |
| [AddChart](../../aspose.slides/shapecollection/addchart#addchart)(ChartType, float, float, float, float) | Vytváří nový graf, inicializuje jej vzorovými daty řad a nastavením a přidává jej na konec kolekce tvarů. |
| [AddChart](../../aspose.slides/shapecollection/addchart#addchart_1)(ChartType, float, float, float, float, bool) | Vytváří nový graf, inicializuje jej vzorovými daty řad a nastavením, a přidává jej na konec kolekce tvarů. |
| [AddClone](../../aspose.slides/shapecollection/addclone#addclone)(IShape) | Vytváří kopii zadaného tvaru a přidává ji na konec kolekce tvarů. Klonovaný tvar zachovává původní pozici a velikost. |
| [AddClone](../../aspose.slides/shapecollection/addclone#addclone_1)(IShape, float, float) | Vytváří kopii zadaného tvaru a přidává ji na konec kolekce tvarů. Nový tvar zachovává šířku a výšku *sourceShape*. |
| [AddClone](../../aspose.slides/shapecollection/addclone#addclone_2)(IShape, float, float, float, float) | Vytváří kopii zadaného tvaru a přidává ji na konec kolekce tvarů. |
| [AddConnector](../../aspose.slides/shapecollection/addconnector#addconnector)(ShapeType, float, float, float, float) | Vytváří nový spojovací tvar s výchozím stylem šablony a přidává jej na konec kolekce tvarů. |
| [AddConnector](../../aspose.slides/shapecollection/addconnector#addconnector_1)(ShapeType, float, float, float, float, bool) | Vytváří nový spojovací tvar a přidává jej na konec kolekce tvarů, volitelně aplikuje výchozí styl šablony. |
| [AddGroupShape](../../aspose.slides/shapecollection/addgroupshape#addgroupshape)() | Vytváří nový prázdný skupinový tvar a přidává jej na konec kolekce tvarů. Rám skupiny se automaticky přizpůsobí tak, aby pojmul všechny přidané tvary. |
| [AddGroupShape](../../aspose.slides/shapecollection/addgroupshape#addgroupshape_1)(ISvgImage, float, float, float, float) | Vytváří nový skupinový tvar, převádí zadaný SVG obrázek na jednotlivé tvary a přidává vzniklou skupinu na konec kolekce tvarů. |
| [AddMathShape](../../aspose.slides/shapecollection/addmathshape)(float, float, float, float) | Vytváří nový obdélníkový automatický tvar pro matematický obsah a přidává jej na konec kolekce tvarů. |
| [AddOleObjectFrame](../../aspose.slides/shapecollection/addoleobjectframe#addoleobjectframe)(float, float, float, float, IOleEmbeddedDataInfo) | Vytváří nový OLE objektový rámec a přidává jej na konec kolekce tvarů. |
| [AddOleObjectFrame](../../aspose.slides/shapecollection/addoleobjectframe#addoleobjectframe_1)(float, float, float, float, string, string) | Vytváří nový OLE objektový rámec a přidává jej na konec kolekce tvarů. |
| [AddPictureFrame](../../aspose.slides/shapecollection/addpictureframe)(ShapeType, float, float, float, float, IPPImage) | Vytváří nový rámec obrázku obsahující zadaný obrázek a přidává jej na konec kolekce tvarů. |
| [AddSectionZoomFrame](../../aspose.slides/shapecollection/addsectionzoomframe#addsectionzoomframe)(float, float, float, float, ISection) | Vytváří nový Section Zoom rámec a přidává jej na konec kolekce tvarů. |
| [AddSectionZoomFrame](../../aspose.slides/shapecollection/addsectionzoomframe#addsectionzoomframe_1)(float, float, float, float, ISection, IPPImage) | Vytváří nový Section Zoom rámec s předdefinovaným obrázkem a přidává jej na konec kolekce tvarů. |
| [AddSmartArt](../../aspose.slides/shapecollection/addsmartart)(float, float, float, float, SmartArtLayoutType) | Vytváří SmartArt diagram a přidává jej na konec kolekce tvarů. |
| [AddSummaryZoomFrame](../../aspose.slides/shapecollection/addsummaryzoomframe)(float, float, float, float) | Vytváří nový Summary Zoom rámec a přidává jej na konec kolekce tvarů. |
| [AddTable](../../aspose.slides/shapecollection/addtable)(float, float, double[], double[]) | Vytváří novou tabulku a přidává ji na konec kolekce tvarů. |
| [AddVideoFrame](../../aspose.slides/shapecollection/addvideoframe#addvideoframe)(float, float, float, float, IVideo) | Vytváří nový video rámec a přidává jej na konec kolekce tvarů. |
| [AddVideoFrame](../../aspose.slides/shapecollection/addvideoframe#addvideoframe_1)(float, float, float, float, string) | Vytváří nový video rámec a přidává jej na konec kolekce tvarů. |
| [AddZoomFrame](../../aspose.slides/shapecollection/addzoomframe#addzoomframe)(float, float, float, float, ISlide) | Vytváří nový Zoom rámec a přidává jej na konec kolekce tvarů. |
| [AddZoomFrame](../../aspose.slides/shapecollection/addzoomframe#addzoomframe_1)(float, float, float, float, ISlide, IPPImage) | Vytváří nový Zoom rámec a přidává jej na konec kolekce tvarů. |
| [Clear](../../aspose.slides/shapecollection/clear)() | Odstraňuje všechny tvary z kolekce tvarů. |
| [CopyTo](../../aspose.slides/shapecollection/copyto)(Array, int) | Kopíruje všechny prvky z kolekce do zadaného pole. |
| [GetEnumerator](../../aspose.slides/shapecollection/getenumerator)() | Vrací enumerátor, který prochází kolekcí. |
| [IndexOf](../../aspose.slides/shapecollection/indexof)(IShape) | Vrací nulově založený index první výskytu zadaného tvaru v kolekci. |
| [InsertAudioFrameCD](../../aspose.slides/shapecollection/insertaudioframecd)(int, float, float, float, float) | Vytváří nový audio rámec propojený s CD stopou a vloží jej do kolekce tvarů na zadaný index. |
| [InsertAudioFrameEmbedded](../../aspose.slides/shapecollection/insertaudioframeembedded#insertaudioframeembedded)(int, float, float, float, float, IAudio) | Vytváří nový audio rámec a vloží jej do kolekce tvarů na zadaný index pomocí existujícího audio objektu ze seznamu Presentation.Audios. |
| [InsertAudioFrameEmbedded](../../aspose.slides/shapecollection/insertaudioframeembedded#insertaudioframeembedded_1)(int, float, float, float, float, Stream) | Vytváří nový audio rámec s vloženým WAV souborem a vloží jej do kolekce tvarů na zadaný index. Vložený audio soubor je přidán do kolekce Presentation.Audios. |
| [InsertAudioFrameLinked](../../aspose.slides/shapecollection/insertaudioframelinked)(int, float, float, float, float, string) | Vytváří nový audio rámec propojený s externím audio souborem a vloží jej do kolekce tvarů na zadaný index. |
| [InsertAutoShape](../../aspose.slides/shapecollection/insertautoshape#insertautoshape)(int, ShapeType, float, float, float, float) | Vytváří nový automatický tvar a vloží jej do kolekce tvarů na zadaný index s výchozím formátováním šablony. |
| [InsertAutoShape](../../aspose.slides/shapecollection/insertautoshape#insertautoshape_1)(int, ShapeType, float, float, float, float, bool) | Vytváří nový automatický tvar a vloží jej do kolekce tvarů na zadaný index, volitelně jej inicializuje výchozím stylem šablony. |
| [InsertChart](../../aspose.slides/shapecollection/insertchart#insertchart)(ChartType, float, float, float, float, int) | Vytváří nový graf, inicializuje jej vzorovými daty řad a nastavením a vloží jej do kolekce tvarů na zadaný index. |
| [InsertChart](../../aspose.slides/shapecollection/insertchart#insertchart_1)(ChartType, float, float, float, float, int, bool) | Vytváří nový graf, inicializuje jej vzorovými daty řad a nastavením a vloží jej do kolekce tvarů na zadaný index. |
| [InsertClone](../../aspose.slides/shapecollection/insertclone#insertclone)(int, IShape) | Vytváří kopii zadaného tvaru a vloží ji do kolekce tvarů na zadaný index. Klonovaný tvar zachovává původní pozici a velikost. |
| [InsertClone](../../aspose.slides/shapecollection/insertclone#insertclone_1)(int, IShape, float, float) | Vytváří kopii zadaného tvaru a vloží ji do kolekce tvarů na zadaný index. Nový tvar zachovává šířku a výšku *sourceShape*. |
| [InsertClone](../../aspose.slides/shapecollection/insertclone#insertclone_2)(int, IShape, float, float, float, float) | Vytváří kopii zadaného tvaru a vloží ji do kolekce tvarů na zadaný index. |
| [InsertConnector](../../aspose.slides/shapecollection/insertconnector#insertconnector)(int, ShapeType, float, float, float, float) | Vytváří nový spojovací tvar a vloží jej do kolekce tvarů na zadaný index s výchozím stylem šablony. |
| [InsertConnector](../../aspose.slides/shapecollection/insertconnector#insertconnector_1)(int, ShapeType, float, float, float, float, bool) | Vytváří nový spojovací tvar a vloží jej do kolekce tvarů na zadaný index, volitelně aplikuje výchozí styl šablony. |
| [InsertGroupShape](../../aspose.slides/shapecollection/insertgroupshape)(int) | Vytváří nový prázdný skupinový tvar a vloží jej do kolekce tvarů na zadaný index. Rám skupiny se automaticky přizpůsobí tak, aby pojmul všechny přidané tvary. |
| [InsertOleObjectFrame](../../aspose.slides/shapecollection/insertoleobjectframe#insertoleobjectframe)(int, float, float, float, float, IOleEmbeddedDataInfo) | Vytváří nový OLE objektový rámec a vloží jej do kolekce tvarů na zadaný index. |
| [InsertOleObjectFrame](../../aspose.slides/shapecollection/insertoleobjectframe#insertoleobjectframe_1)(int, float, float, float, float, string, string) | Vytváří nový OLE objektový rámec a vloží jej do kolekce tvarů na zadaný index. |
| [InsertPictureFrame](../../aspose.slides/shapecollection/insertpictureframe)(int, ShapeType, float, float, float, float, IPPImage) | Vytváří nový rámec obrázku obsahující zadaný obrázek a vloží jej do kolekce tvarů na zadaný index. |
| [InsertSectionZoomFrame](../../aspose.slides/shapecollection/insertsectionzoomframe#insertsectionzoomframe)(int, float, float, float, float, ISection) | Vytváří nový Section Zoom rámec a vloží jej do kolekce tvarů na zadaný index. |
| [InsertSectionZoomFrame](../../aspose.slides/shapecollection/insertsectionzoomframe#insertsectionzoomframe_1)(int, float, float, float, float, ISection, IPPImage) | Vytváří nový Section Zoom rámec s předdefinovaným obrázkem a vloží jej do kolekce tvarů na zadaný index. |
| [InsertSummaryZoomFrame](../../aspose.slides/shapecollection/insertsummaryzoomframe)(int, float, float, float, float) | Vytváří nový Summary Zoom rámec a vloží jej do kolekce tvarů na zadaný index. |
| [InsertTable](../../aspose.slides/shapecollection/inserttable)(int, float, float, double[], double[]) | Vytváří novou tabulku a vloží ji do kolekce tvarů na zadaný index. |
| [InsertVideoFrame](../../aspose.slides/shapecollection/insertvideoframe)(int, float, float, float, float, string) | Vytváří nový video rámec a vloží jej do kolekce tvarů na zadaný index. |
| [InsertZoomFrame](../../aspose.slides/shapecollection/insertzoomframe#insertzoomframe)(int, float, float, float, float, ISlide) | Vytváří nový Zoom rámec a vloží jej do kolekce tvarů na zadaný index. |
| [InsertZoomFrame](../../aspose.slides/shapecollection/insertzoomframe#insertzoomframe_1)(int, float, float, float, float, ISlide, IPPImage) | Vytváří nový Zoom rámec s předdefinovaným obrázkem a vloží jej do kolekce tvarů na zadaný index. |
| [Remove](../../aspose.slides/shapecollection/remove)(IShape) | Odstraňuje první výskyt zadaného tvaru z kolekce tvarů. |
| [RemoveAt](../../aspose.slides/shapecollection/removeat)(int) | Odstraňuje tvar na zadaném indexu z kolekce tvarů. |
| [Reorder](../../aspose.slides/shapecollection/reorder#reorder)(int, IShape) | Přesouvá zadaný tvar na novou pozici v rámci kolekce tvarů. |
| [Reorder](../../aspose.slides/shapecollection/reorder#reorder_1)(int, params IShape[]) | Přesouvá zadané tvary v kolekci tvarů, umisťuje je počínaje daným indexem. |
| [ToArray](../../aspose.slides/shapecollection/toarray#toarray)() | Vytváří a vrací pole obsahující všechny tvary. |
| [ToArray](../../aspose.slides/shapecollection/toarray#toarray_1)(int, int) | Vytváří a vrací pole obsahující všechny tvary ve zadaném rozsahu. |

### Viz také

* třída [DomObject&lt;TParent&gt;](../domobject-1)
* třída [GroupShape](../groupshape)
* rozhraní [IShapeCollection](../ishapecollection)
* jmenný prostor [Aspose.Slides](../../aspose.slides)
* sestavení [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->