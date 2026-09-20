---
title: ChartTitle class
second_title: Aspose.Slides pro Python přes .NET API Reference
description: 
type: docs
url: /cs/aspose.slides.charts/charttitle/
---
## ChartTitle třída

Representuje vlastnosti názvu grafu.

Typ ChartTitle poskytuje následující členy:

## Vlastnosti

| Property | Description |
| :- | :- |
| [`x`](/slides/python-net/cs/aspose.slides.charts/charttitle/x/) | Vrací nebo nastavuje souřadnici x názvu jako zlomek šířky grafu.<br/>            Pouze pro čtení **float**. |
| [`y`](/slides/python-net/cs/aspose.slides.charts/charttitle/y/) | Vrací nebo nastavuje souřadnici y názvu jako zlomek výšky grafu.<br/>            Pouze pro čtení **float**. |
| [`width`](/slides/python-net/cs/aspose.slides.charts/charttitle/width/) | Vrací nebo nastavuje šířku názvu jako zlomek šířky grafu.<br/>            Pouze pro čtení **float**. |
| [`height`](/slides/python-net/cs/aspose.slides.charts/charttitle/height/) | Vrací nebo nastavuje výšku názvu jako zlomek výšky grafu.<br/>            Pouze pro čtení **float**. |
| [`right`](/slides/python-net/cs/aspose.slides.charts/charttitle/right/) | Vpravo.<br/>            Pouze pro čtení **float**. |
| [`bottom`](/slides/python-net/cs/aspose.slides.charts/charttitle/bottom/) | Dole.<br/>            Pouze pro čtení **float**. |
| [`overlay`](/slides/python-net/cs/aspose.slides.charts/charttitle/overlay/) | Určuje, zda ostatní prvky grafu mohou překrývat název.<br/>            Čtení/zápis **bool**. |
| [`format`](/slides/python-net/cs/aspose.slides.charts/charttitle/format/) | Vrací styl výplně, čáry a efektu názvu.<br/>            Pouze pro čtení [`IFormat`](/slides/python-net/cs/aspose.slides.charts/iformat). |
| [`text_frame_for_overriding`](/slides/python-net/cs/aspose.slides.charts/charttitle/text_frame_for_overriding/) | Může obsahovat bohatě formátovaný text. Pokud tato vlastnost není None, pak tato <br/>            hodnota formátovaného textu přepíše automaticky generovaný text.<br/>            Automaticky generovaný text je implicitní vlastnost popisku dat, zobrazovací <br/>            štítek jednotky hodnotové osy, názvu osy, názvu grafu, popisku trendové čáry.<br/>            Automaticky generovaný text je formátován pomocí vlastnosti IFormattedTextContainer.TextFormat.<br/>            Pouze pro čtení [`ITextFrame`](/slides/python-net/cs/aspose.slides/itextframe). |
| [`text_format`](/slides/python-net/cs/aspose.slides.charts/charttitle/text_format/) | Vrací formát textu.<br/>            Pouze pro čtení [`IChartTextFormat`](/slides/python-net/cs/aspose.slides.charts/icharttextformat). |
| [`actual_x`](/slides/python-net/cs/aspose.slides.charts/charttitle/actual_x/) | Určuje skutečnou souřadnici x (levá) grafického prvku relativně k levému hornímu rohu grafu.<br/>            Předtím zavolejte metodu IChart.ValidateChartLayout() pro získání skutečných hodnot.<br/>            Čtení **float**. |
| [`actual_y`](/slides/python-net/cs/aspose.slides.charts/charttitle/actual_y/) | Určuje skutečnou souřadnici y (horní) grafického prvku relativně k levému hornímu rohu grafu.<br/>            Předtím zavolejte metodu IChart.ValidateChartLayout() pro získání skutečných hodnot.<br/>            Čtení **float**. |
| [`actual_width`](/slides/python-net/cs/aspose.slides.charts/charttitle/actual_width/) | Určuje skutečnou šířku grafického prvku. Předtím zavolejte metodu IChart.ValidateChartLayout() pro získání skutečných hodnot.<br/>            Čtení **float**. |
| [`actual_height`](/slides/python-net/cs/aspose.slides.charts/charttitle/actual_height/) | Určuje skutečnou výšku grafického prvku. Předtím zavolejte metodu IChart.ValidateChartLayout() pro získání skutečných hodnot.<br/>            Čtení **float**. |
| [`chart`](/slides/python-net/cs/aspose.slides.charts/charttitle/chart/) | Vrací nadřazený graf.<br/>            Pouze pro čtení [`IChart`](/slides/python-net/cs/aspose.slides.charts/ichart). |
| [`slide`](/slides/python-net/cs/aspose.slides.charts/charttitle/slide/) |  |
| [`presentation`](/slides/python-net/cs/aspose.slides.charts/charttitle/presentation/) |  |

## Metody

| Method | Description |
| :- | :- |
| [`add_text_frame_for_overriding(self, text)`](/slides/python-net/cs/aspose.slides.charts/charttitle/add_text_frame_for_overriding/#str) | Inicializuje TextFrameForOverriding textem v parametru "text".<br/>            Pokud je TextFrameForOverriding již inicializován, pak jednoduše změní jeho text. |

### Viz také
* modul [`aspose.slides.charts`](/slides/python-net/cs/aspose.slides.charts)
* knihovna [`Aspose.Slides`](/slides/python-net)