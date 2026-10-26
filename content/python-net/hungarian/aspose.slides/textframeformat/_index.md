---
title: TextFrameFormat class
second_title: Aspose.Slides Python számára .NET API hivatkozás
description: 
type: docs
url: /hu/aspose.slides/textframeformat/
---
## TextFrameFormat osztály

A TextFrame formatTextFrameFormatting tulajdonságait tartalmazza.

**Inheritance:**[`TextFrameFormat`](/slides/python-net/hu/aspose.slides/textframeformat) → [`PVIObject`](/slides/python-net/hu/aspose.slides/pviobject)

A TextFrameFormat típus a következő tagokat tartalmazza:

## Konstruktorok

| Konstruktor | Leírás |
| :- | :- |
| [`__init__(self)`](/slides/python-net/hu/aspose.slides/textframeformat/__init__/#) | Új példányt inicializál a [`TextFrameFormat`](/slides/python-net/hu/aspose.slides/textframeformat) osztályból. |

## Tulajdonságok

| Tulajdonság | Leírás |
| :- | :- |
| [`three_d_format`](/slides/python-net/hu/aspose.slides/textframeformat/three_d_format/) | Visszaadja a ThreeDFormat objektumot, amely a szöveg 3d effect tulajdonságait képviseli.<br/>            Csak olvasható [`IThreeDFormat`](/slides/python-net/hu/aspose.slides/ithreedformat). |
| [`margin_left`](/slides/python-net/hu/aspose.slides/textframeformat/margin_left/) | Visszaadja vagy beállítja a bal margót (pont) a TextFrame-ben.<br/>            Olvasás/írás **float**. |
| [`margin_right`](/slides/python-net/hu/aspose.slides/textframeformat/margin_right/) | Visszaadja vagy beállítja a jobb margót (pont) a TextFrame-ben.<br/>            Olvasás/írás **float**. |
| [`margin_top`](/slides/python-net/hu/aspose.slides/textframeformat/margin_top/) | Visszaadja vagy beállítja a felső margót (pont) a TextFrame-ben.<br/>            Olvasás/írás **float**. |
| [`margin_bottom`](/slides/python-net/hu/aspose.slides/textframeformat/margin_bottom/) | Visszaadja vagy beállítja az alsó margót (pont) a TextFrame-ben.<br/>            Olvasás/írás **float**. |
| [`wrap_text`](/slides/python-net/hu/aspose.slides/textframeformat/wrap_text/) | **True** ha a szöveg a TextFrame margóiban tördelődik.<br/>            Olvasás/írás [`NullableBool`](/slides/python-net/hu/aspose.slides/nullablebool). |
| [`anchoring_type`](/slides/python-net/hu/aspose.slides/textframeformat/anchoring_type/) | Visszaadja vagy beállítja a függőleges rögzítést a TextFrame-ben.<br/>            Olvasás/írás [`TextAnchorType`](/slides/python-net/hu/aspose.slides/textanchortype). |
| [`center_text`](/slides/python-net/hu/aspose.slides/textframeformat/center_text/) | Ha NullableBool.True, akkor a szöveget vízszintesen középre kell helyezni a dobozban.<br/>            Olvasás/írás [`NullableBool`](/slides/python-net/hu/aspose.slides/nullablebool). |
| [`text_vertical_type`](/slides/python-net/hu/aspose.slides/textframeformat/text_vertical_type/) | Meghatározza a szöveg tájolását.<br/>            A vizuális szövegforgatás eredő értéke, amely ebből a tulajdonságból és a RotationAngle egyéni szögből származik.<br/>            Olvasás/írás [`TextVerticalType`](/slides/python-net/hu/aspose.slides/textverticaltype). |
| [`autofit_type`](/slides/python-net/hu/aspose.slides/textframeformat/autofit_type/) | Visszaadja vagy beállítja a szöveg autofit módját.<br/>            Olvasás/írás [`TextAutofitType`](/slides/python-net/hu/aspose.slides/textautofittype). |
| [`column_count`](/slides/python-net/hu/aspose.slides/textframeformat/column_count/) | Visszaadja vagy beállítja az oszlopok számát a szövegterületen.<br/>            Ennek az értéknek pozitív számnak kell lennie. Ellenkező esetben az érték 0-ra lesz beállítva. <br/>            A 0 érték undefined value.<br/>            Olvasás/írás **int**. |
| [`column_spacing`](/slides/python-net/hu/aspose.slides/textframeformat/column_spacing/) | Visszaadja vagy beállítja a szövegoszlopok közti távolságot a szövegterületen (pontban). Ez csak akkor alkalmazandó, <br/>            ha több mint 1 oszlop van jelen.<br/>            Ennek az értéknek pozitív számnak kell lennie. Ellenkező esetben az érték 0-ra lesz beállítva. <br/>            Olvasás/írás **float**. |
| [`rotation_angle`](/slides/python-net/hu/aspose.slides/textframeformat/rotation_angle/) | Egyedi forgást meghatároz, amely a szövegre a határoló keretben alkalmazandó. Ha nincs megadva,<br/>            akkor a kísérő alakzat forgása lesz használva. Ha meg van adva, akkor ez függetlenül az alakzattól kerül alkalmazásra. Vagyis az alakzat rendelkezhet forgással a szöveg saját forgása mellett.<br/>            A vizuális szövegforgatás eredő értéke, amely ebből a tulajdonságból és a TextVerticalType előre meghatározott függőleges típusból származik.<br/>            Olvasás/írás **float**. |
| [`transform`](/slides/python-net/hu/aspose.slides/textframeformat/transform/) | Visszaadja vagy beállítja a szövegtördelés alakzatát.<br/>            Olvasás/írás [`TextShapeType`](/slides/python-net/hu/aspose.slides/textshapetype). |
| [`keep_text_flat`](/slides/python-net/hu/aspose.slides/textframeformat/keep_text_flat/) | Visszaadja vagy beállítja, hogy a szöveg lapos maradjon akkor is, ha 3-D forgatási hatás van alkalmazva.<br/>            Olvasás/írás **bool**. |
| [`slide`](/slides/python-net/hu/aspose.slides/textframeformat/slide/) |  |
| [`presentation`](/slides/python-net/hu/aspose.slides/textframeformat/presentation/) |  |
| [`text_style`](/slides/python-net/hu/aspose.slides/textframeformat/text_style/) |  |

## Metódusok

| Metódus | Leírás |
| :- | :- |
| [`get_effective(self)`](/slides/python-net/hu/aspose.slides/textframeformat/get_effective/#) | Lekéri a hatékony szövegkeret formázási adatokat, az öröklődés alkalmazásával. |


### Lásd még
* osztály [`PVIObject`](/slides/python-net/hu/aspose.slides/pviobject)
* osztály [`TextFrameFormat`](/slides/python-net/hu/aspose.slides/textframeformat)
* modul [`aspose.slides`](/slides/python-net/hu/aspose.slides)
* könyvtár [`Aspose.Slides`](/slides/python-net)