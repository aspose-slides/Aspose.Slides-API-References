---
title: DataLabel class
second_title: Aspose.Slides for Python via .NET API-referencia
description: 
type: docs
url: /hu/aspose.slides.charts/datalabel/
---
## DataLabel osztály

Képviseli egy sorozat címkéit.

A DataLabel típus a következő tagokat teszi közzé:

## Konstruktorok

| Konstruktor | Leírás |
| :- | :- |
| [`__init__(self, parent_immediate)`](/slides/python-net/hu/aspose.slides.charts/datalabel/__init__/#ichartdatapoint) | Létrehozza a DataLabel osztály egy új példányát. |

## Tulajdonságok

| Tulajdonság | Leírás |
| :- | :- |
| [`chart`](/slides/python-net/hu/aspose.slides.charts/datalabel/chart/) | Visszaadja a szülő diagramot.<br/>            Csak olvasható [`IChart`](/slides/python-net/hu/aspose.slides.charts/ichart). |
| [`is_visible`](/slides/python-net/hu/aspose.slides.charts/datalabel/is_visible/) | A False azt jelenti, hogy az adatcímke nem látható (és ezért minden Show*-flag (ShowValue, ...) hamis).<br/>            Csak olvasható **bool**. |
| [`text_frame_for_overriding`](/slides/python-net/hu/aspose.slides.charts/datalabel/text_frame_for_overriding/) | Tartalmazhat gazdag formázott szöveget. Ha ez a tulajdonság nem None, akkor ez a <br/>            formázott szövegérték felülírja az adatcímke automatikusan generált szövegét.<br/>            Az adatcímke automatikusan generált szövege azt a szöveget jelenti, amelyet a ShowSeriesName, <br/>            ShowValue, ... tulajdonságok kezelnek, és a TextFormatManager.TextFormat tulajdonsággal formáznak.<br/>            Csak olvasható [`ITextFrame`](/slides/python-net/hu/aspose.slides/itextframe). |
| [`text_format`](/slides/python-net/hu/aspose.slides.charts/datalabel/text_format/) | Visszaadja a szövegformátumot.<br/>            Csak olvasható [`IChartTextFormat`](/slides/python-net/hu/aspose.slides.charts/icharttextformat). |
| [`x`](/slides/python-net/hu/aspose.slides.charts/datalabel/x/) | Visszaadja vagy beállítja a cím x koordinátáját a diagram szélességének történt arányában.<br/>            Olvasás/írás **float**. |
| [`y`](/slides/python-net/hu/aspose.slides.charts/datalabel/y/) | Visszaadja vagy beállítja a cím y koordinátáját a diagram magasságának történt arányában.<br/>            Olvasás/írás **float**. |
| [`width`](/slides/python-net/hu/aspose.slides.charts/datalabel/width/) | Visszaadja vagy beállítja a cím szélességét a diagram szélességének történt arányában.<br/>            Olvasás/írás **float**. |
| [`height`](/slides/python-net/hu/aspose.slides.charts/datalabel/height/) | Visszaadja vagy beállítja a cím magasságát a diagram magasságának történt arányában.<br/>            Olvasás/írás **float**. |
| [`right`](/slides/python-net/hu/aspose.slides.charts/datalabel/right/) | Jobb.<br/>            Csak olvasható **float**. |
| [`bottom`](/slides/python-net/hu/aspose.slides.charts/datalabel/bottom/) | Alsó.<br/>            Csak olvasható **float**. |
| [`data_label_format`](/slides/python-net/hu/aspose.slides.charts/datalabel/data_label_format/) | Visszaadja az adatcímke formátumát.<br/>            Csak olvasható [`IDataLabelFormat`](/slides/python-net/hu/aspose.slides.charts/idatalabelformat). |
| [`value_from_cell`](/slides/python-net/hu/aspose.slides.charts/datalabel/value_from_cell/) | Lekéri vagy beállítja a munkafüzet adatcelláját. Alkalmazva, ha az IDataLabelFormat.ShowLabelValueFromCell tulajdonság igaz. |
| [`actual_x`](/slides/python-net/hu/aspose.slides.charts/datalabel/actual_x/) | Meghatározza a diagram elem tényleges x helyzetét (bal) a diagram bal felső sarkához képest.<br/>            Hívja meg az IChart.ValidateChartLayout() metódust előtte a tényleges értékek lekéréséhez. <br/>            Olvasható **float**. |
| [`actual_y`](/slides/python-net/hu/aspose.slides.charts/datalabel/actual_y/) | Meghatározza a diagram elem tényleges felső helyzetét a diagram bal felső sarkához képest.<br/>            Hívja meg az IChart.ValidateChartLayout() metódust előtte a tényleges értékek lekéréséhez. <br/>            Olvasható **float**. |
| [`actual_width`](/slides/python-net/hu/aspose.slides.charts/datalabel/actual_width/) | Meghatározza a diagram elem tényleges szélességét. Hívja meg az IChart.ValidateChartLayout() metódust előtte a tényleges értékek lekéréséhez. <br/>            Olvasható **float**. |
| [`actual_height`](/slides/python-net/hu/aspose.slides.charts/datalabel/actual_height/) | Meghatározza a diagram elem tényleges magasságát. Hívja meg az IChart.ValidateChartLayout() metódust előtte a tényleges értékek lekéréséhez. <br/>            Olvasható **float**. |
| [`slide`](/slides/python-net/hu/aspose.slides.charts/datalabel/slide/) |  |
| [`presentation`](/slides/python-net/hu/aspose.slides.charts/datalabel/presentation/) |  |

## Módszerek

| Módszer | Leírás |
| :- | :- |
| [`hide(self)`](/slides/python-net/hu/aspose.slides.charts/datalabel/hide/#) | Elrejti az adatcímkét az összes Show*-flag (ShowValue, ...) hamis állapotra állításával.<br/>            Az IsVisible ezután hamis lesz. |
| [`get_actual_label_text(self)`](/slides/python-net/hu/aspose.slides.charts/datalabel/get_actual_label_text/#) | Visszaadja a tényleges címke szövegét a DataLabelFormat beállítások vagy a TextFrameForOverriding.Text értéke alapján. |
| [`add_text_frame_for_overriding(self, text)`](/slides/python-net/hu/aspose.slides.charts/datalabel/add_text_frame_for_overriding/#str) | Inicializálja a TextFrameForOverriding-ot a "text" paraméter szövegével.<br/>            Ha a TextFrameForOverriding már inicializálva van, akkor egyszerűen megváltoztatja a szövegét. |


### Lásd még
* modul [`aspose.slides.charts`](/slides/python-net/hu/aspose.slides.charts)
* könyvtár [`Aspose.Slides`](/slides/python-net)