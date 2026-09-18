---
title: ITextFrameFormat class
second_title: Aspose.Slides a Python számára .NET API-referencia
description: 
type: docs
url: /hu/aspose.slides/itextframeformat/
---
## ITextFrameFormat osztály

Tartalmazza a TextFrame formázási tulajdonságait.

Az ITextFrameFormat típus a következő tagokat teszi elérhetővé:

## Tulajdonságok

| Tulajdonság | Leírás |
| :- | :- |
| [`text_style`](/slides/python-net/hu/aspose.slides/itextframeformat/text_style/) | Visszaadja a szöveg stílusát.<br/>            Csak olvasható [`ITextStyle`](/slides/python-net/hu/aspose.slides/itextstyle). |
| [`margin_left`](/slides/python-net/hu/aspose.slides/itextframeformat/margin_left/) | Visszaadja vagy beállítja a bal margót (pontokban) egy TextFrame-ben.<br/>            Olvasás/írás **float**. |
| [`margin_right`](/slides/python-net/hu/aspose.slides/itextframeformat/margin_right/) | Visszaadja vagy beállítja a jobb margót (pontokban) egy TextFrame-ben.<br/>            Olvasás/írás **float**. |
| [`margin_top`](/slides/python-net/hu/aspose.slides/itextframeformat/margin_top/) | Visszaadja vagy beállítja a felső margót (pontokban) egy TextFrame-ben.<br/>            Olvasás/írás **float**. |
| [`margin_bottom`](/slides/python-net/hu/aspose.slides/itextframeformat/margin_bottom/) | Visszaadja vagy beállítja az alsó margót (pontokban) egy TextFrame-ben.<br/>            Olvasás/írás **float**. |
| [`wrap_text`](/slides/python-net/hu/aspose.slides/itextframeformat/wrap_text/) | **True** ha a szöveget a TextFrame margóinál sortördelik.<br/>            Olvasás/írás [`NullableBool`](/slides/python-net/hu/aspose.slides/nullablebool). |
| [`anchoring_type`](/slides/python-net/hu/aspose.slides/itextframeformat/anchoring_type/) | Visszaadja vagy beállítja a függőleges horgony szöveget egy TextFrame-ben.<br/>            Olvasás/írás [`TextAnchorType`](/slides/python-net/hu/aspose.slides/textanchortype). |
| [`center_text`](/slides/python-net/hu/aspose.slides/itextframeformat/center_text/) | Ha NullableBool.True, akkor a szöveget vízszintesen kell középre helyezni a dobozban.<br/>            Olvasás/írás [`NullableBool`](/slides/python-net/hu/aspose.slides/nullablebool). |
| [`text_vertical_type`](/slides/python-net/hu/aspose.slides/itextframeformat/text_vertical_type/) | Meghatározza a szöveg tájolását.<br/>            A vizuális szövegforgatás eredő értékét ebben a tulajdonságban és az egyéni szögben, amely a RotationAngle tulajdonságban van összegzi.<br/>            Olvasás/írás [`TextVerticalType`](/slides/python-net/hu/aspose.slides/textverticaltype). |
| [`autofit_type`](/slides/python-net/hu/aspose.slides/itextframeformat/autofit_type/) | Visszaadja vagy beállítja a szöveg automatikus kitöltési módját.<br/>            Olvasás/írás [`TextAutofitType`](/slides/python-net/hu/aspose.slides/textautofittype). |
| [`column_count`](/slides/python-net/hu/aspose.slides/itextframeformat/column_count/) | Visszaadja vagy beállítja az oszlopok számát a szövegterületen.<br/>            Ennek az értéknek pozitív számnak kell lennie. Ellenkező esetben az érték 0-ra lesz állítva. <br/>            A 0 érték meghatározatlan értéket jelent.<br/>            Olvasás/írás **int**. |
| [`column_spacing`](/slides/python-net/hu/aspose.slides/itextframeformat/column_spacing/) | Visszaadja vagy beállítja a szövegoszlopok közti távolságot a szövegterületen (pontokban). Ennek csak akkor kell érvényesülnie, <br/>            ha egynél több oszlop van jelen.<br/>            Ennek az értéknek pozitív számnak kell lennie. Ellenkező esetben az érték 0-ra lesz állítva. <br/>            Olvasás/írás **float**. |
| [`three_d_format`](/slides/python-net/hu/aspose.slides/itextframeformat/three_d_format/) | Visszaadja a ThreeDFormat objektumot, amely a szöveg 3D hatásának tulajdonságait képviseli.<br/>            Csak olvasható [`IThreeDFormat`](/slides/python-net/hu/aspose.slides/ithreedformat). |
| [`keep_text_flat`](/slides/python-net/hu/aspose.slides/itextframeformat/keep_text_flat/) | Visszaadja vagy beállítja, hogy a szöveg teljesen ki legyen zárva a 3D jelenetből.<br/>            Olvasás/írás **bool**. |
| [`rotation_angle`](/slides/python-net/hu/aspose.slides/itextframeformat/rotation_angle/) | Megadja a szövegre a határoló keretben alkalmazott egyéni forgatást. Ha nincs<br/>            megadva, akkor a kísérő alakzat forgatása kerül felhasználásra. Ha meg van adva, akkor ez<br/>            függetlenül az alakzattól kerül alkalmazásra. Azaz az alakzat kaphat forgatást, <br/>            miközben a szöveg is saját forgatást kap.<br/>            A vizuális szövegforgatás eredő értékét ebben a tulajdonságban és az előre definiált<br/>            függőleges típusban a TextVerticalType tulajdonságban összegzi.<br/>            Olvasás/írás **float**. |
| [`transform`](/slides/python-net/hu/aspose.slides/itextframeformat/transform/) | Visszaadja vagy beállítja a szöveg körbefuttatás alakzatát.<br/>            Olvasás/írás [`TextShapeType`](/slides/python-net/hu/aspose.slides/textshapetype). |

## Metódusok

| Metódus | Leírás |
| :- | :- |
| [`get_effective(self)`](/slides/python-net/hu/aspose.slides/itextframeformat/get_effective/#) | Visszaadja az öröklődés alkalmazásával kapott hatékony szövegkeret formázási adatokat. |

### Lásd még
* modul [`aspose.slides`](/slides/python-net/hu/aspose.slides)
* könyvtár [`Aspose.Slides`](/slides/python-net)