---
title: DataLabel class
second_title: Aspose.Slides a Pythonhoz .NET API referencián keresztül
description: 
type: docs
url: /hu/aspose.slides.charts/datalabel/
---
## DataLabel osztály

Egy sorozat címkéit ábrázolja.

A DataLabel típus a következő tagokat tartalmazza:

## Konstruktorok

| Konstruktor | Leírás |
| :- | :- |
| [`__init__(self, parent_immediate)`](/slides/python-net/hu/aspose.slides.charts/datalabel/__init__/#ichartdatapoint) | Új DataLabel osztálypéldányt hoz létre. |

## Tulajdonságok

| Tulajdonság | Leírás |
| :- | :- |
| [`chart`](/slides/python-net/hu/aspose.slides.charts/datalabel/chart/) | Visszaadja a szülő diagramot.<br/>            Csak olvasható [`IChart`](/slides/python-net/hu/aspose.slides.charts/ichart). |
| [`is_visible`](/slides/python-net/hu/aspose.slides.charts/datalabel/is_visible/) | A hamis azt jelenti, hogy az adatcímke nem látható (és ezért minden Show*-jelző (ShowValue, ...) hamis).<br/>            Csak olvasható **bool**. |
| [`text_frame_for_overriding`](/slides/python-net/hu/aspose.slides.charts/datalabel/text_frame_for_overriding/) | Tartalmazhat gazdag formázott szöveget. Ha ez a tulajdonság nincs None értéken, akkor ez a <br/>            formázott szövegérték felülírja az adatcímke automatikusan generált szövegét.<br/>            Az adatcímke automatikusan generált szövege azt a szöveget jelenti, amelyet a ShowSeriesName, <br/>            ShowValue, … tulajdonságok kezelnek, és a TextFormatManager.TextFormat tulajdonsággal formázzák.<br/>            Csak olvasható [`ITextFrame`](/slides/python-net/hu/aspose.slides/itextframe). |
| [`text_format`](/slides/python-net/hu/aspose.slides.charts/datalabel/text_format/) | Visszaadja a szövegformátumot.<br/>            Csak olvasható [`IChartTextFormat`](/slides/python-net/hu/aspose.slides.charts/icharttextformat). |
| [`x`](/slides/python-net/hu/aspose.slides.charts/datalabel/x/) | Visszaadja vagy beállítja egy cím x koordinátáját a diagram szélességének hányadosaként.<br/>            Olvasás/írás **float**. |
| [`y`](/slides/python-net/hu/aspose.slides.charts/datalabel/y/) | Visszaadja vagy beállítja egy cím y koordinátáját a diagram magasságának hányadosaként.<br/>            Olvasás/írás **float**. |
| [`width`](/slides/python-net/hu/aspose.slides.charts/datalabel/width/) | Visszaadja vagy beállítja egy cím szélességét a diagram szélességének hányadosaként.<br/>            Olvasás/írás **float**. |
| [`height`](/slides/python-net/hu/aspose.slides.charts/datalabel/height/) | Visszaadja vagy beállítja egy cím magasságát a diagram magasságának hányadosaként.<br/>            Olvasás/írás **float**. |
| [`right`](/slides/python-net/hu/aspose.slides.charts/datalabel/right/) | Jobb.<br/>            Csak olvasható **float**. |
| [`bottom`](/slides/python-net/hu/aspose.slides.charts/datalabel/bottom/) | Alsó.<br/>            Csak olvasható **float**. |
| [`data_label_format`](/slides/python-net/hu/aspose.slides.charts/datalabel/data_label_format/) | Visszaadja az adatcímke formátumát.<br/>            Csak olvasható [`IDataLabelFormat`](/slides/python-net/hu/aspose.slides.charts/idatalabelformat). |
| [`value_from_cell`](/slides/python-net/hu/aspose.slides.charts/datalabel/value_from_cell/) | Megkapja vagy beállítja a munkafüzet adatcelláját. Alkalmazva, ha az IDataLabelFormat.ShowLabelValueFromCell tulajdonság igaz. |
| [`label_shape_type`](/slides/python-net/hu/aspose.slides.charts/datalabel/label_shape_type/) | Megkapja vagy beállítja az adatcímke alakzat típusát.<br/>             Visszaadja a [`ShapeType.NOT_DEFINED`](/slides/python-net/hu/aspose.slides/shapetype/NOT_DEFINED) értéket, ha nincs alakzat definiálva. |
| [`actual_x`](/slides/python-net/hu/aspose.slides.charts/datalabel/actual_x/) | Megadja a diagram elem tényleges x helyzetét (bal), a diagram bal felső sarkához képest.<br/>            Hívja meg az IChart.ValidateChartLayout() metódust a tényleges értékek lekéréséhez. <br/>            Olvas **float**. |
| [`actual_y`](/slides/python-net/hu/aspose.slides.charts/datalabel/actual_y/) | Megadja a diagram elem tényleges felső pozícióját a diagram bal felső sarkához képest.<br/>            Hívja meg az IChart.ValidateChartLayout() metódust a tényleges értékek lekéréséhez. <br/>            Olvas **float**. |
| [`actual_width`](/slides/python-net/hu/aspose.slides.charts/datalabel/actual_width/) | Megadja a diagram elem tényleges szélességét. Hívja meg az IChart.ValidateChartLayout() metódust a tényleges értékek lekéréséhez. <br/>            Olvas **float**. |
| [`actual_height`](/slides/python-net/hu/aspose.slides.charts/datalabel/actual_height/) | Megadja a diagram elem tényleges magasságát. Hívja meg az IChart.ValidateChartLayout() metódust a tényleges értékek lekéréséhez. <br/>            Olvas **float**. |
| [`slide`](/slides/python-net/hu/aspose.slides.charts/datalabel/slide/) |  |
| [`presentation`](/slides/python-net/hu/aspose.slides.charts/datalabel/presentation/) |  |

## Metódusok

| Metódus | Leírás |
| :- | :- |
| [`hide(self)`](/slides/python-net/hu/aspose.slides.charts/datalabel/hide/#) | Elrejti az adatcímkét az összes Show*-jelző (ShowValue, ...) hamis állapotra állításával.<br/>            Az IsVisible ezután hamis lesz. |
| [`get_actual_label_text(self)`](/slides/python-net/hu/aspose.slides.charts/datalabel/get_actual_label_text/#) | Visszaadja a tényleges címkeszöveget a DataLabelFormat beállítások vagy a TextFrameForOverriding.Text érték alapján. |
| [`add_text_frame_for_overriding(self, text)`](/slides/python-net/hu/aspose.slides.charts/datalabel/add_text_frame_for_overriding/#str) | Inicializálja a TextFrameForOverriding-et a "text" paraméterben megadott szöveggel.<br/>            Ha a TextFrameForOverriding már inicializálva van, akkor egyszerűen megváltoztatja a szövegét. |

### Lásd még
* modul [`aspose.slides.charts`](/slides/python-net/hu/aspose.slides.charts)
* könyvtár [`Aspose.Slides`](/slides/python-net)