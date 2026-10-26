---
title: Trendline class
second_title: Aspose.Slides a Pythonhoz a .NET-en keresztül API hivatkozás
description: 
type: docs
url: /hu/aspose.slides.charts/trendline/
---
## Trendline osztály

Az osztály a diagram sorozat trendvonalát képviseli

A Trendline típus a következő tagokat teszi elérhetővé:

## Tulajdonságok

| Property | Description |
| :- | :- |
| [`trendline_name`](/slides/python-net/hu/aspose.slides.charts/trendline/trendline_name/) | A trendvonal nevét adja vissza vagy állítja be.<br/>            Read/write **str**. |
| [`trendline_type`](/slides/python-net/hu/aspose.slides.charts/trendline/trendline_type/) | A trendvonal típusát adja vissza vagy állítja be.<br/>            Read/write [`TrendlineType`](/slides/python-net/hu/aspose.slides.charts/trendlinetype). |
| [`format`](/slides/python-net/hu/aspose.slides.charts/trendline/format/) | A trendvonal formátumát képviseli.<br/>            Read/write [`IFormat`](/slides/python-net/hu/aspose.slides.charts/iformat). |
| [`backward`](/slides/python-net/hu/aspose.slides.charts/trendline/backward/) | Meghatározza a kategóriák (vagy egységek egy szórt diagramon) számát, amelyet a trendvonal a trendelt sorozat adatainak előtt kiterjeszt.<br/>            Szórt és nem szórt diagramok esetén az értéknek nem negatívnak kell lennie.<br/>            Read/write **float**. |
| [`forward`](/slides/python-net/hu/aspose.slides.charts/trendline/forward/) | Meghatározza a kategóriák (vagy egységek egy szórt diagramon) számát, amelyet a trendvonal a trendelt sorozat adatainak után kiterjeszt.<br/>            Szórt és nem szórt diagramok esetén az értéknek nem negatívnak kell lennie.<br/>            Read/write **float**. |
| [`intercept`](/slides/python-net/hu/aspose.slides.charts/trendline/intercept/) | Meghatározza azt az értéket, ahol a trendvonal metszi az y tengelyt.<br/>            Ez a tulajdonság csak akkor támogatott, amikor a trendvonal típusa exp, linear vagy poly.<br/>            Read/write **float**. |
| [`display_equation`](/slides/python-net/hu/aspose.slides.charts/trendline/display_equation/) | Meghatározza, hogy a trendvonal egyenlete megjelenik-e a diagramon (az Rsquaredvalue-vel azonos címkén).<br/>            Read/write **bool**. |
| [`order`](/slides/python-net/hu/aspose.slides.charts/trendline/order/) | Meghatározza a polinomiális trendvonal rendjét. Más trendvonal típusok esetén figyelmen kívül marad. Az értéknek 2 és 6 között kell lennie.<br/>            Read/write **int**. |
| [`period`](/slides/python-net/hu/aspose.slides.charts/trendline/period/) | Meghatározza a trendvonal periódusát egy mozgó átlag trendvonal esetén.<br/>            Más trendvonal változatok esetén figyelmen kívül marad. Az értéknek 2 és 255 között kell lennie.<br/>            Read/write **int**. |
| [`display_r_squared_value`](/slides/python-net/hu/aspose.slides.charts/trendline/display_r_squared_value/) | Meghatározza, hogy a trendvonal R-négyzet értéke megjelenik-e a diagramon (az egyenlettel azonos címkén).<br/>            Read/write **bool**. |
| [`related_legend_entry`](/slides/python-net/hu/aspose.slides.charts/trendline/related_legend_entry/) | A trendvonalhoz kapcsolódó jelmagyarázat bejegyzést képviseli.<br/>            Read-only [`ILegendEntryProperties`](/slides/python-net/hu/aspose.slides.charts/ilegendentryproperties). |
| [`text_frame_for_overriding`](/slides/python-net/hu/aspose.slides.charts/trendline/text_frame_for_overriding/) | Tartalmazhat gazdag formázott szöveget.<br/>            Ha ez a tulajdonság nem None, akkor ez a formázott szöveg felülírja az adatcímke automatikusan generált szövegét.<br/>            Az adatcímke automatikusan generált szövege olyan szöveget jelent, amelyet a ShowSeriesName, ShowValue, ... tulajdonságok kezelnek, és amely a TextFormatManager.TextFormat tulajdonsággal van formázva.<br/>            Read-only [`ITextFrame`](/slides/python-net/hu/aspose.slides/itextframe). |
| [`text_format`](/slides/python-net/hu/aspose.slides.charts/trendline/text_format/) | Visszaadja a szövegformátumot.<br/>            Read-only [`IChartTextFormat`](/slides/python-net/hu/aspose.slides.charts/icharttextformat). |
| [`chart`](/slides/python-net/hu/aspose.slides.charts/trendline/chart/) | Visszaadja a szülő diagramot.<br/>            Read-only [`IChart`](/slides/python-net/hu/aspose.slides.charts/ichart). |
| [`slide`](/slides/python-net/hu/aspose.slides.charts/trendline/slide/) |  |
| [`presentation`](/slides/python-net/hu/aspose.slides.charts/trendline/presentation/) |  |

## Metódusok

| Method | Description |
| :- | :- |
| [`add_text_frame_for_overriding(self, text)`](/slides/python-net/hu/aspose.slides.charts/trendline/add_text_frame_for_overriding/#str) | Inicializálja a TextFrameForOverriding objektumot a "text" paraméterben megadott szöveggel.<br/>            Ha a TextFrameForOverriding már inicializálva van, akkor egyszerűen módosítja a szövegét. |

### Lásd még
* modul [`aspose.slides.charts`](/slides/python-net/hu/aspose.slides.charts)
* könyvtár [`Aspose.Slides`](/slides/python-net)