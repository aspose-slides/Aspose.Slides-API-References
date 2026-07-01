---
title: ShapeCollection
second_title: Aspose.Sildes pro .NET – API reference
description: Reprezentuje kolekci tvarů.
type: docs
weight: 9840
url: /cs/aspose.slides/shapecollection/
---
## ShapeCollection třída

Represents a collection of shapes.

```csharp
public sealed class ShapeCollection : DomObject<GroupShape>, IShapeCollection
```

## Vlastnosti

| Název | Popis |
| --- | --- |
| [Count](../../aspose.slides/shapecollection/count) { get; } | Získá počet skutečně obsažených prvků ve sbírce. Jen pro čtení Int32. |
| [IsSynchronized](../../aspose.slides/shapecollection/issynchronized) { get; } | Vrací hodnotu indikující, zda je přístup ke sbírce synchronizován (vláknově bezpečný). Jen pro čtení Boolean. |
| [Item](../../aspose.slides/shapecollection/item) { get; } | Získá prvek na zadaném indexu. Jen pro čtení [`IShape`](../ishape). |
| [ParentGroup](../../aspose.slides/shapecollection/parentgroup) { get; } | Získá nadřazený objekt skupiny tvarů pro sbírku tvarů. Jen pro čtení [`IGroupShape`](../igroupshape). |
| [SyncRoot](../../aspose.slides/shapecollection/syncroot) { get; } | Vrací synchronizační kořen. Jen pro čtení Object. |

## Metody

| Název | Popis |
| --- | --- |
| [AddAudioFrameCD](../../aspose.slides/shapecollection/addaudioframecd)(float, float, float, float) | Vytvoří nový zvukový rámec propojený s CD stopou a přidá jej na konec sbírky tvarů. |
| [AddAudioFrameEmbedded](../../aspose.slides/shapecollection/addaudioframeembedded#addaudioframeembedded)(float, float, float, float, IAudio) | Vytvoří nový zvukový rámec a přidá jej na konec sbírky tvarů pomocí existujícího zvukového objektu ze seznamu Presentation.Audios. |
| [AddAudioFrameEmbedded](../../aspose.slides/shapecollection/addaudioframeembedded#addaudioframeembedded_1)(float, float, float, float, Stream) | Vytvoří nový zvukový rámec s vloženým WAV souborem a přidá jej na konec sbírky tvarů. Vložený zvuk je přidán do sbírky Presentation.Audios. |
| [AddAudioFrameLinked](../../aspose.slides/shapecollection/addaudioframelinked)(float, float, float, float, string) | Vytvoří nový zvukový rámec propojený s externím zvukovým souborem a přidá jej na konec sbírky tvarů. |
| [AddAutoShape](../../aspose.slides/shapecollection/addautoshape#addautoshape)(ShapeType, float, float, float, float) | Vytvoří nový automatický tvar s výchozím formátováním a přidá jej na konec sbírky tvarů. |
| [AddAutoShape](../../aspose.slides/shapecollection/addautoshape#addautoshape_1)(ShapeType, float, float, float, float, bool) | Vytvoří nový automatický tvar a přidá jej na konec sbírky tvarů, volitelně jej inicializuje výchozím formátováním šablony. |
| [AddChart](../../aspose.slides/shapecollection/addchart#addchart)(ChartType, float, float, float, float) | Vytvoří nový diagram, inicializuje jej ukázkovými daty řad a nastaveními a přidá jej na konec sbírky tvarů. |
| [AddChart](../../aspose.slides/shapecollection/addchart#addchart_1)(ChartType, float, float, float, float, bool) | Vytvoří nový diagram, inicializuje jej ukázkovými daty řad a nastaveními a přidá jej na konec sbírky tvarů. |
| [AddClone](../../aspose.slides/shapecollection/addclone#addclone)(IShape) | Vytvoří kopii zadaného tvaru a přidá ji na konec sbírky tvarů. Klonovaný tvar zachovává původní pozici a velikost. |
| [AddClone](../../aspose.slides/shapecollection/addclone#addclone_1)(IShape, float, float) | Vytvoří kopii zadaného tvaru a přidá ji na konec sbírky tvarů. Nový tvar zachovává šířku a výšku *sourceShape*. |
| [AddClone](../../aspose.slides/shapecollection/addclone#addclone_2)(IShape, float, float, float, float) | Vytvoří kopii zadaného tvaru a přidá ji na konec sbírky tvarů. |
| [AddConnector](../../aspose.slides/shapecollection/addconnector#addconnector)(ShapeType, float, float, float, float) | Vytvoří nový spojovací tvar s výchozím stylem šablony a přidá jej na konec sbírky tvarů. |
| [AddConnector](../../aspose.slides/shapecollection/addconnector#addconnector_1)(ShapeType, float, float, float, float, bool) | Vytvoří nový spojovací tvar a přidá jej na konec sbírky tvarů, volitelně použije výchozí styl šablony. |
| [AddGroupShape](../../aspose.slides/shapecollection/addgroupshape#addgroupshape)() | Vytvoří nový prázdný skupinový tvar a přidá jej na konec sbírky tvarů. Rám skupiny se automaticky přizpůsobí jakémukoli přidanému tvaru. |
| [AddGroupShape](../../aspose.slides/shapecollection/addgroupshape#addgroupshape_1)(ISvgImage, float, float, float, float) | Vytvoří nový skupinový tvar, převede zadaný SVG obrázek na jednotlivé tvary a přidá vzniklou skupinu na konec sbírky tvarů. |
| [AddMathShape](../../aspose.slides/shapecollection/addmathshape)(float, float, float, float) | Vytvoří nový obdélníkový automatický tvar pro umístění matematického obsahu a přidá jej na konec sbírky tvarů. |
| [AddOleObjectFrame](../../aspose.slides/shapecollection/addoleobjectframe#addoleobjectframe)(float, float, float, float, IOleEmbeddedDataInfo) | Vytvoří nový OLE objektový rámec a přidá jej na konec sbírky tvarů. |
| [AddOleObjectFrame](../../aspose.slides/shapecollection/addoleobjectframe#addoleobjectframe_1)(float, float, float, float, string, string) | Vytvoří nový OLE objektový rámec a přidá jej na konec sbírky tvarů. |
| [AddPictureFrame](../../aspose.slides/shapecollection/addpictureframe)(ShapeType, float, float, float, float, IPPImage) | Vytvoří nový obrázkový rámec obsahující zadaný obrázek a přidá jej na konec sbírky tvarů. |
| [AddSectionZoomFrame](../../aspose.slides/shapecollection/addsectionzoomframe#addsectionzoomframe)(float, float, float, float, ISection) | Vytvoří nový rámec Section Zoom a přidá jej na konec sbírky tvarů. |
| [AddSectionZoomFrame](../../aspose.slides/shapecollection/addsectionzoomframe#addsectionzoomframe_1)(float, float, float, float, ISection, IPPImage) | Vytvoří nový rámec Section Zoom s předdefinovaným obrázkem a přidá jej na konec sbírky tvarů. |
| [AddSmartArt](../../aspose.slides/shapecollection/addsmartart)(float, float, float, float, SmartArtLayoutType) | Vytvoří diagram SmartArt a přidá jej na konec sbírky tvarů. |
| [AddSummaryZoomFrame](../../aspose.slides/shapecollection/addsummaryzoomframe)(float, float, float, float) | Vytvoří nový rámec Summary Zoom a přidá jej na konec sbírky tvarů. |
| [AddTable](../../aspose.slides/shapecollection/addtable)(float, float, double[], double[]) | Vytvoří novou tabulku a přidá ji na konec sbírky tvarů. |
| [AddVideoFrame](../../aspose.slides/shapecollection/addvideoframe#addvideoframe)(float, float, float, float, IVideo) | Vytvoří nový video rámec a přidá jej na konec sbírky tvarů. |
| [AddVideoFrame](../../aspose.slides/shapecollection/addvideoframe#addvideoframe_1)(float, float, float, float, string) | Vytvoří nový video rámec a přidá jej na konec sbírky tvarů. |
| [AddZoomFrame](../../aspose.slides/shapecollection/addzoomframe#addzoomframe)(float, float, float, float, ISlide) | Vytvoří nový Zoom rámec a přidá jej na konec sbírky tvarů. |
| [AddZoomFrame](../../aspose.slides/shapecollection/addzoomframe#addzoomframe_1)(float, float, float, float, ISlide, IPPImage) | Vytvoří nový Zoom rámec a přidá jej na konec sbírky tvarů. |
| [Clear](../../aspose.slides/shapecollection/clear)() | Odstraní všechny tvary ze sbírky tvarů. |
| [CopyTo](../../aspose.slides/shapecollection/copyto)(Array, int) | Zkopíruje všechny prvky ze sbírky do zadaného pole. |
| [GetEnumerator](../../aspose.slides/shapecollection/getenumerator)() | Vrací enumerátor, který prochází sbírkou. |
| [IndexOf](../../aspose.slides/shapecollection/indexof)(IShape) | Vrací nulový index první výskytu zadaného tvaru v sbírce. |
| [InsertAudioFrameCD](../../aspose.slides/shapecollection/insertaudioframecd)(int, float, float, float, float) | Vytvoří nový zvukový rámec propojený s CD stopou a vloží jej do sbírky tvarů na zadaný index. |
| [InsertAudioFrameEmbedded](../../aspose.slides/shapecollection/insertaudioframeembedded#insertaudioframeembedded)(int, float, float, float, float, IAudio) | Vytvoří nový zvukový rámec a vloží jej do sbírky tvarů na zadaný index pomocí existujícího zvukového objektu ze seznamu Presentation.Audios. |
| [InsertAudioFrameEmbedded](../../aspose.slides/shapecollection/insertaudioframeembedded#insertaudioframeembedded_1)(int, float, float, float, float, Stream) | Vytvoří nový zvukový rámec s vloženým WAV souborem a vloží jej do sbírky tvarů na zadaný index. Vložený zvuk je přidán do sbírky Presentation.Audios. |
| [InsertAudioFrameLinked](../../aspose.slides/shapecollection/insertaudioframelinked)(int, float, float, float, float, string) | Vytvoří nový zvukový rámec propojený s externím zvukovým souborem a vloží jej do sbírky tvarů na zadaný index. |
| [InsertAutoShape](../../aspose.slides/shapecollection/insertautoshape#insertautoshape)(int, ShapeType, float, float, float, float) | Vytvoří nový automatický tvar a vloží jej do sbírky tvarů na zadaný index, použije výchozí formátování šablony. |
| [InsertAutoShape](../../aspose.slides/shapecollection/insertautoshape#insertautoshape_1)(int, ShapeType, float, float, float, float, bool) | Vytvoří nový automatický tvar a vloží jej do sbírky tvarů na zadaný index, volitelně jej inicializuje výchozím stylem šablony. |
| [InsertChart](../../aspose.slides/shapecollection/insertchart#insertchart)(ChartType, float, float, float, float, int) | Vytvoří nový diagram, inicializuje jej ukázkovými daty řad a nastaveními a vloží jej do sbírky tvarů na zadaný index. |
| [InsertChart](../../aspose.slides/shapecollection/insertchart#insertchart_1)(ChartType, float, float, float, float, int, bool) | Vytvoří nový diagram, inicializuje jej ukázkovými daty řad a nastaveními a vloží jej do sbírky tvarů na zadaný index. |
| [InsertClone](../../aspose.slides/shapecollection/insertclone#insertclone)(int, IShape) | Vytvoří kopii zadaného tvaru a vloží ji do sbírky tvarů na zadaný index. Klonovaný tvar zachovává původní pozici a velikost. |
| [InsertClone](../../aspose.slides/shapecollection/insertclone#insertclone_1)(int, IShape, float, float) | Vytvoří kopii zadaného tvaru a vloží ji do sbírky tvarů na zadaný index. Nový tvar zachovává šířku a výšku *sourceShape*. |
| [InsertClone](../../aspose.slides/shapecollection/insertclone#insertclone_2)(int, IShape, float, float, float, float) | Vytvoří kopii zadaného tvaru a vloží ji do sbírky tvarů na zadaný index. |
| [InsertConnector](../../aspose.slides/shapecollection/insertconnector#insertconnector)(int, ShapeType, float, float, float, float) | Vytvoří nový spojovací tvar a vloží jej do sbírky tvarů na zadaný index, použije výchozí styl šablony. |
| [InsertConnector](../../aspose.slides/shapecollection/insertconnector#insertconnector_1)(int, ShapeType, float, float, float, float, bool) | Vytvoří nový spojovací tvar a vloží jej do sbírky tvarů na zadaný index, volitelně použije výchozí styl šablony. |
| [InsertGroupShape](../../aspose.slides/shapecollection/insertgroupshape)(int) | Vytvoří nový prázdný skupinový tvar a vloží jej do sbírky tvarů na zadaný index. Rám skupiny se automaticky přizpůsobí jakémukoli přidanému tvaru. |
| [InsertOleObjectFrame](../../aspose.slides/shapecollection/insertoleobjectframe#insertoleobjectframe)(int, float, float, float, float, IOleEmbeddedDataInfo) | Vytvoří nový OLE objektový rámec a vloží jej do sbírky tvarů na zadaný index. |
| [InsertOleObjectFrame](../../aspose.slides/shapecollection/insertoleobjectframe#insertoleobjectframe_1)(int, float, float, float, float, string, string) | Vytvoří nový OLE objektový rámec a vloží jej do sbírky tvarů na zadaný index. |
| [InsertPictureFrame](../../aspose.slides/shapecollection/insertpictureframe)(int, ShapeType, float, float, float, float, IPPImage) | Vytvoří nový obrázkový rámec obsahující zadaný obrázek a vloží jej do sbírky tvarů na zadaný index. |
| [InsertSectionZoomFrame](../../aspose.slides/shapecollection/insertsectionzoomframe#insertsectionzoomframe)(int, float, float, float, float, ISection) | Vytvoří nový rámec Section Zoom a vloží jej do sbírky tvarů na zadaný index. |
| [InsertSectionZoomFrame](../../aspose.slides/shapecollection/insertsectionzoomframe#insertsectionzoomframe_1)(int, float, float, float, float, ISection, IPPImage) | Vytvoří nový rámec Section Zoom s předdefinovaným obrázkem a vloží jej do sbírky tvarů na zadaný index. |
| [InsertSummaryZoomFrame](../../aspose.slides/shapecollection/insertsummaryzoomframe)(int, float, float, float, float) | Vytvoří nový rámec Summary Zoom a vloží jej do sbírky tvarů na zadaný index. |
| [InsertTable](../../aspose.slides/shapecollection/inserttable)(int, float, float, double[], double[]) | Vytvoří novou tabulku a vloží ji do sbírky tvarů na zadaný index. |
| [InsertVideoFrame](../../aspose.slides/shapecollection/insertvideoframe)(int, float, float, float, float, string) | Vytvoří nový video rámec a vloží jej do sbírky tvarů na zadaný index. |
| [InsertZoomFrame](../../aspose.slides/shapecollection/insertzoomframe#insertzoomframe)(int, float, float, float, float, ISlide) | Vytvoří nový Zoom rámec a vloží jej do sbírky tvarů na zadaný index. |
| [InsertZoomFrame](../../aspose.slides/shapecollection/insertzoomframe#insertzoomframe_1)(int, float, float, float, float, ISlide, IPPImage) | Vytvoří nový Zoom rámec s předdefinovaným obrázkem a vloží jej do sbírky tvarů na zadaný index. |
| [Remove](../../aspose.slides/shapecollection/remove)(IShape) | Odstraní první výskyt zadaného tvaru ze sbírky tvarů. |
| [RemoveAt](../../aspose.slides/shapecollection/removeat)(int) | Odstraní tvar na zadaném indexu ze sbírky tvarů. |
| [Reorder](../../aspose.slides/shapecollection/reorder#reorder)(int, IShape) | Přesune zadaný tvar na novou pozici ve sbírce tvarů. |
| [Reorder](../../aspose.slides/shapecollection/reorder#reorder_1)(int, params IShape[]) | Přesune zadané tvary ve sbírce tvarů, umístí je počínaje daným indexem. |
| [ToArray](../../aspose.slides/shapecollection/toarray#toarray)() | Vytvoří a vrátí pole obsahující všechny tvary. |
| [ToArray](../../aspose.slides/shapecollection/toarray#toarray_1)(int, int) | Vytvoří a vrátí pole obsahující všechny tvary v zadaném rozsahu. |

### Viz také

* třída [DomObject&lt;TParent&gt;](../domobject-1)
* třída [GroupShape](../groupshape)
* rozhraní [IShapeCollection](../ishapecollection)
* jmenný prostor [Aspose.Slides](../../aspose.slides)
* sestavení [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->