---
title: ChartTitle class
second_title: Aspose.Slides Pythonhoz .NET API hivatkozás
description: 
type: docs
url: /hu/aspose.slides.charts/charttitle/
---
## ChartTitle osztály

A diagram címtulajdonságait képviseli.

A ChartTitle típus a következő tagokat tartalmazza:

## Tulajdonságok

| Property | Description |
| :- | :- |
| [`x`](/slides/python-net/hu/aspose.slides.charts/charttitle/x/) | Visszaadja vagy beállítja a cím x koordinátáját a diagram szélességének tört részeként.<br/>            Olvasás/írás **float**. |
| [`y`](/slides/python-net/hu/aspose.slides.charts/charttitle/y/) | Visszaadja vagy beállítja a cím y koordinátáját a diagram magasságának tört részeként.<br/>            Olvasás/írás **float**. |
| [`width`](/slides/python-net/hu/aspose.slides.charts/charttitle/width/) | Visszaadja vagy beállítja a cím szélességét a diagram szélességének tört részeként.<br/>            Olvasás/írás **float**. |
| [`height`](/slides/python-net/hu/aspose.slides.charts/charttitle/height/) | Visszaadja vagy beállítja a cím magasságát a diagram magasságának tört részeként.<br/>            Olvasás/írás **float**. |
| [`right`](/slides/python-net/hu/aspose.slides.charts/charttitle/right/) | Jobb.<br/>            Csak olvasható **float**. |
| [`bottom`](/slides/python-net/hu/aspose.slides.charts/charttitle/bottom/) | Alul.<br/>            Csak olvasható **float**. |
| [`overlay`](/slides/python-net/hu/aspose.slides.charts/charttitle/overlay/) | Meghatározza, hogy a diagram többi eleme átfedheti-e a címet.<br/>            Olvasás/írás **bool**. |
| [`format`](/slides/python-net/hu/aspose.slides.charts/charttitle/format/) | Visszaadja a cím kitöltés, vonal és effektus stílusait.<br/>            Csak olvasható [`IFormat`](/slides/python-net/hu/aspose.slides.charts/iformat). |
| [`text_frame_for_overriding`](/slides/python-net/hu/aspose.slides.charts/charttitle/text_frame_for_overriding/) | Gazdag formázott szöveget tartalmazhat. Ha ez a tulajdonság nem None, akkor ez a <br/>            formázott szövegérték felülírja az automatikusan generált szöveget.<br/>            Az automatikusan generált szöveg egy implicit tulajdonság a data label, a display <br/>            unit label of the value axis, a axis title, a chart title, a label of the trendline számára.<br/>            Az automatikusan generált szöveget az IFormattedTextContainer.TextFormat tulajdonság formázza.<br/>            Csak olvasható [`ITextFrame`](/slides/python-net/hu/aspose.slides/itextframe). |
| [`text_format`](/slides/python-net/hu/aspose.slides.charts/charttitle/text_format/) | Visszaadja a szövegformátumot.<br/>            Csak olvasható [`IChartTextFormat`](/slides/python-net/hu/aspose.slides.charts/icharttextformat). |
| [`actual_x`](/slides/python-net/hu/aspose.slides.charts/charttitle/actual_x/) | Megrendeli az elem tényleges x helyzetét (bal) a diagram bal felső sarkához képest.<br/>            Hívja meg az IChart.ValidateChartLayout() metódust a tényleges értékek lekéréséhez. <br/>            Olvas **float**. |
| [`actual_y`](/slides/python-net/hu/aspose.slides.charts/charttitle/actual_y/) | Megrendeli az elem tényleges felső pozícióját a diagram bal felső sarkához képest.<br/>            Hívja meg az IChart.ValidateChartLayout() metódust a tényleges értékek lekéréséhez. <br/>            Olvas **float**. |
| [`actual_width`](/slides/python-net/hu/aspose.slides.charts/charttitle/actual_width/) | Megrendeli a diagram elem tényleges szélességét. Hívja meg az IChart.ValidateChartLayout() metódust a tényleges értékek lekéréséhez. <br/>            Olvas **float**. |
| [`actual_height`](/slides/python-net/hu/aspose.slides.charts/charttitle/actual_height/) | Megrendeli a diagram elem tényleges magasságát. Hívja meg az IChart.ValidateChartLayout() metódust a tényleges értékek lekéréséhez. <br/>            Olvas **float**. |
| [`chart`](/slides/python-net/hu/aspose.slides.charts/charttitle/chart/) | Visszaadja a szülő diagramot.<br/>            Csak olvasható [`IChart`](/slides/python-net/hu/aspose.slides.charts/ichart). |
| [`slide`](/slides/python-net/hu/aspose.slides.charts/charttitle/slide/) |  |
| [`presentation`](/slides/python-net/hu/aspose.slides.charts/charttitle/presentation/) |  |

## Módszerek

| Method | Description |
| :- | :- |
| [`add_text_frame_for_overriding(self, text)`](/slides/python-net/hu/aspose.slides.charts/charttitle/add_text_frame_for_overriding/#str) | Inicializálja a TextFrameForOverriding elemet a "text" paraméterrel.<br/>            Ha a TextFrameForOverriding már inicializálva van, akkor egyszerűen módosítja annak szövegét. |


### Lásd még
* modul [`aspose.slides.charts`](/slides/python-net/hu/aspose.slides.charts)
* könyvtár [`Aspose.Slides`](/slides/python-net)