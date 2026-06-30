---
title: TextFrameFormat
second_title: Aspose.Sildes a .NET API-referencia
description: Tartalmazza a TextFrames formatTextFrameFormatting tulajdonságait.
type: docs
weight: 10940
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
| [TextFrameFormat](textframeformat)() | Új példányt hoz létre a(z) [`TextFrameFormat`](../textframeformat) osztályból. |

## Tulajdonságok

| Név | Leírás |
| --- | --- |
| [AnchoringType](../../aspose.slides/textframeformat/anchoringtype) { get; set; } | Visszaadja vagy beállítja a függőleges rögzítő szöveget egy TextFrame-ben. Olvasás/írás [`TextAnchorType`](../textanchortype). |
| [AsIPresentationComponent](../../aspose.slides/pviobject/asipresentationcomponent) { get; } | Lehetővé teszi a base IPresentationComponent interfész lekérését. Csak olvasás [`IPresentationComponent`](../ipresentationcomponent). |
| [AutofitType](../../aspose.slides/textframeformat/autofittype) { get; set; } | Visszaadja vagy beállítja a szöveg automata kitöltési módját. Olvasás/írás [`TextAutofitType`](../textautofittype). |
| [CenterText](../../aspose.slides/textframeformat/centertext) { get; set; } | Ha NullableBool.True, akkor a szöveget vízszintesen középre kell helyezni a keretben. Olvasás/írás [`NullableBool`](../nullablebool). |
| [ColumnCount](../../aspose.slides/textframeformat/columncount) { get; set; } | Visszaadja vagy beállítja az oszlopok számát a szövegterületen. Ennek az értéknek pozitív számnak kell lennie. Ellenkező esetben az érték nullára lesz beállítva. A 0 érték nem meghatározott értéket jelent. Olvasás/írás Int32. |
| [ColumnSpacing](../../aspose.slides/textframeformat/columnspacing) { get; set; } | Visszaadja vagy beállítja a szövegoszlopok közti távolságot a szövegterületen (pontban). Ez csak akkor alkalmazandó, ha egynél több oszlop van jelen. Ennek az értéknek pozitív számnak kell lennie. Ellenkező esetben az érték nullára lesz beállítva. Olvasás/írás Double. |
| [KeepTextFlat](../../aspose.slides/textframeformat/keeptextflat) { get; set; } | Beállítja vagy lekéri, hogy a szöveg sík maradjon még akkor is, ha 3-D forgatási hatás lett alkalmazva. Olvasás/írás Boolean. |
| [MarginBottom](../../aspose.slides/textframeformat/marginbottom) { get; set; } | Visszaadja vagy beállítja az alsó margót (pontban) egy TextFrame-ben. Olvasás/írás Double. |
| [MarginLeft](../../aspose.slides/textframeformat/marginleft) { get; set; } | Visszaadja vagy beállítja a bal margót (pontban) egy TextFrame-ben. Olvasás/írás Double. |
| [MarginRight](../../aspose.slides/textframeformat/marginright) { get; set; } | Visszaadja vagy beállítja a jobb margót (pontban) egy TextFrame-ben. Olvasás/írás Double. |
| [MarginTop](../../aspose.slides/textframeformat/margintop) { get; set; } | Visszaadja vagy beállítja a felső margót (pontban) egy TextFrame-ben. Olvasás/írás Double. |
| [RotationAngle](../../aspose.slides/textframeformat/rotationangle) { get; set; } | Megadja a szövegre a keretben alkalmazott egyéni forgatást. Ha nincs megadva, akkor a társított alakzat forgatása lesz használva. Ha meg van adva, akkor ez függetlenül a forma forgatásától kerül alkalmazásra. Tehát a forma kaphat forgatást, és a szöveg is kaphat forgatást. A vizuális szöveg forgatásának eredő értékét ez a tulajdonság és a TextVerticalType előre definiált függőleges típusa összegzi. Olvasás/írás Single. |
| [TextVerticalType](../../aspose.slides/textframeformat/textverticaltype) { get; set; } | Meghatározza a szöveg tájolását. A vizuális szöveg forgatásának eredő értékét ez a tulajdonság és a RotationAngle egyéni szöge összegzi. Olvasás/írás [`TextVerticalType`](../textverticaltype). |
| [ThreeDFormat](../../aspose.slides/textframeformat/threedformat) { get; } | Visszaadja a ThreeDFormat objektumot, amely a szöveg 3D hatás tulajdonságait képviseli. Csak olvasás [`IThreeDFormat`](../ithreedformat). |
| [Transform](../../aspose.slides/textframeformat/transform) { get; set; } | Beállítja vagy lekéri a szöveg körbefuttatásához használt alakzatot. Olvasás/írás [`TextShapeType`](../textshapetype). |
| [WrapText](../../aspose.slides/textframeformat/wraptext) { get; set; } | **True**, ha a szöveg a TextFrame margóinál van körbefuttatva. Olvasás/írás [`NullableBool`](../nullablebool). |

## Módszerek

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