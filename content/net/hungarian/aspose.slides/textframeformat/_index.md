---
title: TextFrameFormat
second_title: Aspose.Sildes .NET API referencia
description: Tartalmazza a TextFrames formatTextFrameFormatting tulajdonságait.
type: docs
weight: 10960
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
| [AnchoringType](../../aspose.slides/textframeformat/anchoringtype) { get; set; } | Visszaadja vagy beállítja a függőleges horgony szöveget egy TextFrame-ben. Olvasás/írás [`TextAnchorType`](../textanchortype). |
| [AsIPresentationComponent](../../aspose.slides/pviobject/asipresentationcomponent) { get; } | Lehetővé teszi a base IPresentationComponent interfész lekérését. Csak olvasható [`IPresentationComponent`](../ipresentationcomponent). |
| [AutofitType](../../aspose.slides/textframeformat/autofittype) { get; set; } | Visszaadja vagy beállítja a szöveg automatikus illesztési módját. Olvasás/írás [`TextAutofitType`](../textautofittype). |
| [CenterText](../../aspose.slides/textframeformat/centertext) { get; set; } | Ha NullableBool.True, akkor a szövegnek vízszintesen központosítva kell lennie a keretben. Olvasás/írás [`NullableBool`](../nullablebool). |
| [ColumnCount](../../aspose.slides/textframeformat/columncount) { get; set; } | Visszaadja vagy beállítja az oszlopok számát a szövegterületen. Ennek az értéknek pozitív számnak kell lennie. Ellenkező esetben az érték 0-ra lesz beállítva. A 0 érték határozatlan értéket jelent. Olvasás/írás Int32. |
| [ColumnSpacing](../../aspose.slides/textframeformat/columnspacing) { get; set; } | Visszaadja vagy beállítja a szövegoszlopok közötti távolságot a szövegterületen (pontban). Ez csak akkor érvényes, ha több mint 1 oszlop van jelen. Ennek az értéknek pozitív számnak kell lennie. Ellenkező esetben az érték 0-ra lesz beállítva. Olvasás/írás Double. |
| [KeepTextFlat](../../aspose.slides/textframeformat/keeptextflat) { get; set; } | Beállítja vagy lekéri, hogy a szöveg sík maradjon még akkor is, ha 3D forgatási effektus lett alkalmazva. Olvasás/írás Boolean. |
| [MarginBottom](../../aspose.slides/textframeformat/marginbottom) { get; set; } | Visszaadja vagy beállítja az alsó margót (pontban) egy TextFrame-ben. Olvasás/írás Double. |
| [MarginLeft](../../aspose.slides/textframeformat/marginleft) { get; set; } | Visszaadja vagy beállítja a bal margót (pontban) egy TextFrame-ben. Olvasás/írás Double. |
| [MarginRight](../../aspose.slides/textframeformat/marginright) { get; set; } | Visszaadja vagy beállítja a jobb margót (pontban) egy TextFrame-ben. Olvasás/írás Double. |
| [MarginTop](../../aspose.slides/textframeformat/margintop) { get; set; } | Visszaadja vagy beállítja a felső margót (pontban) egy TextFrame-ben. Olvasás/írás Double. |
| [RotationAngle](../../aspose.slides/textframeformat/rotationangle) { get; set; } | Megadja az egyedi forgatást, amely a szövegre vonatkozik a keretben. Ha nincs megadva, akkor a kísérő alakzat forgatása lesz használva. Ha meg van adva, akkor ez függetlenül alkalmazódik az alakzattól. Azaz az alakzat forgatása mellett a szövegnek is lehet forgatása. A vizuális szöveg forgatásának eredő értéke ebből a tulajdonságból és a TextVerticalType előre definiált függőleges típus kombinációja adja meg. Olvasás/írás Single. |
| [TextVerticalType](../../aspose.slides/textframeformat/textverticaltype) { get; set; } | Meghatározza a szöveg orientációját. A vizuális szöveg forgatásának eredő értéke ebből a tulajdonságból és a RotationAngle egyedi szögből származik. Olvasás/írás [`TextVerticalType`](../textverticaltype). |
| [ThreeDFormat](../../aspose.slides/textframeformat/threedformat) { get; } | Visszaadja a ThreeDFormat objektumot, amely a szöveg 3D effektus tulajdonságait képviseli. Csak olvasható [`IThreeDFormat`](../ithreedformat). |
| [Transform](../../aspose.slides/textframeformat/transform) { get; set; } | Visszaadja vagy beállítja a szövegcsomagoló alakzatot. Olvasás/írás [`TextShapeType`](../textshapetype). |
| [WrapText](../../aspose.slides/textframeformat/wraptext) { get; set; } | **True** ha a szöveg a TextFrame margóinál van csomagolva. Olvasás/írás [`NullableBool`](../nullablebool). |

## Módszerek

| Név | Leírás |
| --- | --- |
| override [Equals](../../aspose.slides/pviobject/equals)(object) | Összehasonlítja a megadott objektummal. |
| [GetEffective](../../aspose.slides/textframeformat/geteffective)() | Lekéri a hatékony szövegdoboz formázási adatokat az öröklődés alkalmazásával. |
| override [GetHashCode](../../aspose.slides/pviobject/gethashcode)() | Visszaadja a hash kódot. |

### Lásd még

* osztály [PVIObject](../pviobject)
* interfész [IChartTextBlockFormat](../../aspose.slides.charts/icharttextblockformat)
* interfész [ITextFrameFormat](../itextframeformat)
* névtér [Aspose.Slides](../../aspose.slides)
* összeállítás [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->