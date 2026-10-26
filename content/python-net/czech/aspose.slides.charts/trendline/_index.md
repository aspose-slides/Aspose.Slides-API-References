---
title: Trendline class
second_title: Aspose.Slides pro Python pomocí .NET referenční příručka API
description: 
type: docs
url: /cs/aspose.slides.charts/trendline/
---
## Trendline třída

Třída představuje čáru trendu řady grafu

Typ Trendline poskytuje následující členy:

## Vlastnosti

| Vlastnost | Popis |
| :- | :- |
| [`trendline_name`](/slides/python-net/cs/aspose.slides.charts/trendline/trendline_name/) | Získává nebo nastavuje název čáry trendu.<br/>            Read/write **str**. |
| [`trendline_type`](/slides/python-net/cs/aspose.slides.charts/trendline/trendline_type/) | Získává nebo nastavuje typ čáry trendu.<br/>            Read/write [`TrendlineType`](/slides/python-net/cs/aspose.slides.charts/trendlinetype). |
| [`format`](/slides/python-net/cs/aspose.slides.charts/trendline/format/) | Reprezentuje formát čáry trendu.<br/>            Read/write [`IFormat`](/slides/python-net/cs/aspose.slides.charts/iformat). |
| [`backward`](/slides/python-net/cs/aspose.slides.charts/trendline/backward/) | Určuje počet kategorií (nebo jednotek v rozptýleném grafu), o které se čára trendu rozšiřuje před<br/>            data řady, která je trendována. V rozptýlených i nerozptýlených grafech musí být hodnota libovolná nezáporná<br/>            hodnota.<br/>            Read/write **float**. |
| [`forward`](/slides/python-net/cs/aspose.slides.charts/trendline/forward/) | Určuje počet kategorií (nebo jednotek v rozptýleném grafu), o které se čára trendu rozšiřuje za<br/>            data řady, která je trendována. V rozptýlených i nerozptýlených grafech musí být hodnota libovolná nezáporná<br/>            hodnota.<br/>            Read/write **float**. |
| [`intercept`](/slides/python-net/cs/aspose.slides.charts/trendline/intercept/) | Určuje hodnotu, kde má čára trendu protínat osu y. Tato vlastnost je podporována pouze<br/>            když je typ čáry trendu exp, linear nebo poly.<br/>            Read/write **float**. |
| [`display_equation`](/slides/python-net/cs/aspose.slides.charts/trendline/display_equation/) | Určuje, že rovnice čáry trendu je zobrazena v grafu (ve stejném popisku jako hodnota Rsquaredvalue).<br/>            Read/write **bool**. |
| [`order`](/slides/python-net/cs/aspose.slides.charts/trendline/order/) | Určuje řád polynomické čáry trendu. Je ignorováno u ostatních typů čáry trendu. Hodnota musí být mezi 2 a 6.<br/>            Read/write **int**. |
| [`period`](/slides/python-net/cs/aspose.slides.charts/trendline/period/) | Určuje periodu čáry trendu pro čáru klouzavého průměru. Je ignorováno u ostatních<br/>            variant čáry trendu. Hodnota musí být mezi 2 a 255.<br/>            Read/write **int**. |
| [`display_r_squared_value`](/slides/python-net/cs/aspose.slides.charts/trendline/display_r_squared_value/) | Určuje, že hodnota R-squared čáry trendu je zobrazena v grafu (ve stejném popisku jako rovnice).<br/>            Read/write **bool**. |
| [`related_legend_entry`](/slides/python-net/cs/aspose.slides.charts/trendline/related_legend_entry/) | Reprezentuje položku legendy související s touto čárou trendu<br/>            Read-only [`ILegendEntryProperties`](/slides/python-net/cs/aspose.slides.charts/ilegendentryproperties). |
| [`text_frame_for_overriding`](/slides/python-net/cs/aspose.slides.charts/trendline/text_frame_for_overriding/) | Může obsahovat bohatě formátovaný text. Pokud tato vlastnost není None, pak tato <br/>            hodnota formátovaného textu přepíše automaticky generovaný text popisku dat.<br/>            Automaticky generovaný text popisku dat znamená text, který spravují vlastnosti ShowSeriesName, <br/>            ShowValue, ... a je formátován pomocí vlastnosti TextFormatManager.TextFormat.<br/>            Read-only [`ITextFrame`](/slides/python-net/cs/aspose.slides/itextframe). |
| [`text_format`](/slides/python-net/cs/aspose.slides.charts/trendline/text_format/) | Vrací formát textu.<br/>            Read-only [`IChartTextFormat`](/slides/python-net/cs/aspose.slides.charts/icharttextformat). |
| [`chart`](/slides/python-net/cs/aspose.slides.charts/trendline/chart/) | Vrací nadřazený graf.<br/>            Read-only [`IChart`](/slides/python-net/cs/aspose.slides.charts/ichart). |
| [`slide`](/slides/python-net/cs/aspose.slides.charts/trendline/slide/) |  |
| [`presentation`](/slides/python-net/cs/aspose.slides.charts/trendline/presentation/) |  |

## Metody

| Metoda | Popis |
| :- | :- |
| [`add_text_frame_for_overriding(self, text)`](/slides/python-net/cs/aspose.slides.charts/trendline/add_text_frame_for_overriding/#str) | Inicializuje TextFrameForOverriding textem v parametru "text".<br/>            Pokud je TextFrameForOverriding již inicializován, pak jednoduše změní jeho text. |

### Viz také
* modul [`aspose.slides.charts`](/slides/python-net/cs/aspose.slides.charts)
* knihovna [`Aspose.Slides`](/slides/python-net)