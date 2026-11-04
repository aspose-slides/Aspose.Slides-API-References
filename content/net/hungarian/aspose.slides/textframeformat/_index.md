---
title: TextFrameFormat
second_title: Aspose.Sildes .NET API-referencia
description: Tartalmazza a TextFrames formatTextFrameFormatting tulajdonságait.
type: docs
weight: 10980
url: /hu/aspose.slides/textframeformat/
---
## TextFrameFormat osztály

Tartalmazza a TextFrame formatTextFrameFormatting tulajdonságait.

```csharp
public sealed class TextFrameFormat : PVIObject, IChartTextBlockFormat, ITextFrameFormat
```

## Konstruktorok

| Név | Leírás |
| --- | --- |
| [TextFrameFormat](textframeformat)() | Új példányt hoz létre a [`TextFrameFormat`](../textframeformat) osztályból. |

## Tulajdonságok

| Név | Leírás |
| --- | --- |
| [AnchoringType](../../aspose.slides/textframeformat/anchoringtype) { get; set; } | Visszaadja vagy beállítja a függőleges rögzítési szöveget egy TextFrame-ben. Olvasás/írás [`TextAnchorType`](../textanchortype). |
| [AsIPresentationComponent](../../aspose.slides/pviobject/asipresentationcomponent) { get; } | Lehetővé teszi a base IPresentationComponent interfész lekérését. Csak olvasható [`IPresentationComponent`](../ipresentationcomponent). |
| [AutofitType](../../aspose.slides/textframeformat/autofittype) { get; set; } | Visszaadja vagy beállítja a szöveg autofit módját. Olvasás/írás [`TextAutofitType`](../textautofittype). |
| [CenterText](../../aspose.slides/textframeformat/centertext) { get; set; } | Ha NullableBool.True, akkor a szöveget vízszintesen középre kell helyezni a keretben. Olvasás/írás [`NullableBool`](../nullablebool). |
| [ColumnCount](../../aspose.slides/textframeformat/columncount) { get; set; } | Visszaadja vagy beállítja az oszlopok számát a szövegterületen. Ennek az értéknek pozitív számnak kell lennie. Egyébként az érték nulla lesz. A 0 érték meghatározatlan értéket jelent. Olvasás/írás Int32. |
| [ColumnSpacing](../../aspose.slides/textframeformat/columnspacing) { get; set; } | Visszaadja vagy beállítja a szövegoszlopok közti távolságot a szövegterületen (pontban). Ez csak akkor érvényes, ha több mint 1 oszlop van. Ennek az értéknek pozitív számnak kell lennie. Egyébként az érték nulla lesz. Olvasás/írás Double. |
| [KeepTextFlat](../../aspose.slides/textframeformat/keeptextflat) { get; set; } | Beállítható, hogy a szöveg sík maradjon még akkor is, ha 3-D forgatás hatása alkalmazva lett. Olvasás/írás Boolean. |
| [MarginBottom](../../aspose.slides/textframeformat/marginbottom) { get; set; } | Visszaadja vagy beállítja az alsó margót (pontban) egy TextFrame-ben. Olvasás/írás Double. |
| [MarginLeft](../../aspose.slides/textframeformat/marginleft) { get; set; } | Visszaadja vagy beállítja a bal margót (pontban) egy TextFrame-ben. Olvasás/írás Double. |
| [MarginRight](../../aspose.slides/textframeformat/marginright) { get; set; } | Visszaadja vagy beállítja a jobb margót (pontban) egy TextFrame-ben. Olvasás/írás Double. |
| [MarginTop](../../aspose.slides/textframeformat/margintop) { get; set; } | Visszaadja vagy beállítja a felső margót (pontban) egy TextFrame-ben. Olvasás/írás Double. |
| [RotationAngle](../../aspose.slides/textframeformat/rotationangle) { get; set; } | Meghatározza a szövegre a keretben alkalmazott egyéni forgatást. Ha nincs megadva, a hozzátartozó alakzat forgatása lesz használva. Ha meg van adva, akkor ez függetlenül alkalmazásra kerül az alakzattól. Az eredő vizuális szövegfordulás értéke ebből a tulajdonságból és az előre definiált függőleges típusból, a TextVerticalType tulajdonságból származik. Olvasás/írás Single. |
| [TextVerticalType](../../aspose.slides/textframeformat/textverticaltype) { get; set; } | Meghatározza a szöveg orientációját. Az eredő vizuális szövegfordulás értéke ebből a tulajdonságból és a RotationAngle tulajdonság egyéni szögéből származik. Olvasás/írás [`TextVerticalType`](../textverticaltype). |
| [ThreeDFormat](../../aspose.slides/textframeformat/threedformat) { get; } | Visszaadja a ThreeDFormat objektumot, amely a szöveg 3D hatás tulajdonságait képviseli. Csak olvasható [`IThreeDFormat`](../ithreedformat). |
| [Transform](../../aspose.slides/textframeformat/transform) { get; set; } | Beállítható vagy lekérhető a szöveg körbefuttatását meghatározó alakzat. Olvasás/írás [`TextShapeType`](../textshapetype). |
| [WrapText](../../aspose.slides/textframeformat/wraptext) { get; set; } | **True**, ha a szöveg a TextFrame margóinál van körbefuttatva. Olvasás/írás [`NullableBool`](../nullablebool). |

## Metódusok

| Név | Leírás |
| --- | --- |
| override [Equals](../../aspose.slides/pviobject/equals)(object) | Összehasonlítja a megadott objektummal. |
| [GetEffective](../../aspose.slides/textframeformat/geteffective)() | Lekéri a hatékony szövegkeret formázási adatokat az öröklődés alkalmazásával. |
| override [GetHashCode](../../aspose.slides/pviobject/gethashcode)() | Visszaadja a hash kódot. |

### Lásd még

* osztály [PVIObject](../pviobject)
* interfész [IChartTextBlockFormat](../../aspose.slides.charts/icharttextblockformat)
* interfész [ITextFrameFormat](../itextframeformat)
* névtér [Aspose.Slides](../../aspose.slides)
* összeállítás [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->