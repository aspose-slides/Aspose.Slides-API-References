---
title: DataLabel class
second_title: Aspose.Slides pro Python přes .NET referenci API
description: 
type: docs
url: /cs/aspose.slides.charts/datalabel/
---
## DataLabel třída

Reprezentuje popisky řady.

Typ DataLabel obsahuje následující členy:

## Konstruktory

| Konstruktor | Popis |
| :- | :- |
| [`__init__(self, parent_immediate)`](/slides/python-net/cs/aspose.slides.charts/datalabel/__init__/#ichartdatapoint) | Vytvoří novou instanci třídy DataLabel. |

## Vlastnosti

| Vlastnost | Popis |
| :- | :- |
| [`chart`](/slides/python-net/cs/aspose.slides.charts/datalabel/chart/) | Vrací nadřazený graf.<br/>            Pouze pro čtení [`IChart`](/slides/python-net/cs/aspose.slides.charts/ichart). |
| [`is_visible`](/slides/python-net/cs/aspose.slides.charts/datalabel/is_visible/) | False znamená, že popisek dat není viditelný (a všechny příznaky Show*- (ShowValue, ...) jsou false).<br/>            Pouze pro čtení **bool**. |
| [`text_frame_for_overriding`](/slides/python-net/cs/aspose.slides.charts/datalabel/text_frame_for_overriding/) | Může obsahovat bohatě formátovaný text. Pokud tato vlastnost není None, pak tato <br/>            hodnota formátovaného textu přepíše automaticky generovaný text popisku dat.<br/>            Automaticky generovaný text popisku dat znamená text spravovaný vlastnostmi ShowSeriesName, <br/>            ShowValue, ... a formátovaný pomocí vlastnosti TextFormatManager.TextFormat.<br/>            Pouze pro čtení [`ITextFrame`](/slides/python-net/cs/aspose.slides/itextframe). |
| [`text_format`](/slides/python-net/cs/aspose.slides.charts/datalabel/text_format/) | Vrací formát textu.<br/>            Pouze pro čtení [`IChartTextFormat`](/slides/python-net/cs/aspose.slides.charts/icharttextformat). |
| [`x`](/slides/python-net/cs/aspose.slides.charts/datalabel/x/) | Vrací nebo nastavuje souřadnici x nadpisu jako podíl šířky grafu.<br/>            Čtení/zápis **float**. |
| [`y`](/slides/python-net/cs/aspose.slides.charts/datalabel/y/) | Vrací nebo nastavuje souřadnici y nadpisu jako podíl výšky grafu.<br/>            Čtení/zápis **float**. |
| [`width`](/slides/python-net/cs/aspose.slides.charts/datalabel/width/) | Vrací nebo nastavuje šířku nadpisu jako podíl šířky grafu.<br/>            Čtení/zápis **float**. |
| [`height`](/slides/python-net/cs/aspose.slides.charts/datalabel/height/) | Vrací nebo nastavuje výšku nadpisu jako podíl výšky grafu.<br/>            Čtení/zápis **float**. |
| [`right`](/slides/python-net/cs/aspose.slides.charts/datalabel/right/) | Vpravo.<br/>            Pouze pro čtení **float**. |
| [`bottom`](/slides/python-net/cs/aspose.slides.charts/datalabel/bottom/) | Dole.<br/>            Pouze pro čtení **float**. |
| [`data_label_format`](/slides/python-net/cs/aspose.slides.charts/datalabel/data_label_format/) | Vrací formát popisku dat.<br/>            Pouze pro čtení [`IDataLabelFormat`](/slides/python-net/cs/aspose.slides.charts/idatalabelformat). |
| [`value_from_cell`](/slides/python-net/cs/aspose.slides.charts/datalabel/value_from_cell/) | Získá nebo nastaví buňku dat sešitu. Používá se, pokud je vlastnost IDataLabelFormat.ShowLabelValueFromCell rovna true. |
| [`actual_x`](/slides/python-net/cs/aspose.slides.charts/datalabel/actual_x/) | Určuje skutečnou polohu x (levý okraj) elementu grafu vzhledem k levému hornímu rohu grafu.<br/>            Před voláním zavolejte metodu IChart.ValidateChartLayout() pro získání aktuálních hodnot.<br/>            Čtení **float**. |
| [`actual_y`](/slides/python-net/cs/aspose.slides.charts/datalabel/actual_y/) | Určuje skutečný horní okraj elementu grafu vzhledem k levému hornímu rohu grafu.<br/>            Před voláním zavolejte metodu IChart.ValidateChartLayout() pro získání aktuálních hodnot.<br/>            Čtení **float**. |
| [`actual_width`](/slides/python-net/cs/aspose.slides.charts/datalabel/actual_width/) | Určuje skutečnou šířku elementu grafu. Před voláním zavolejte metodu IChart.ValidateChartLayout() pro získání aktuálních hodnot.<br/>            Čtení **float**. |
| [`actual_height`](/slides/python-net/cs/aspose.slides.charts/datalabel/actual_height/) | Určuje skutečnou výšku elementu grafu. Před voláním zavolejte metodu IChart.ValidateChartLayout() pro získání aktuálních hodnot.<br/>            Čtení **float**. |
| [`slide`](/slides/python-net/cs/aspose.slides.charts/datalabel/slide/) |  |
| [`presentation`](/slides/python-net/cs/aspose.slides.charts/datalabel/presentation/) |  |

## Metody

| Metoda | Popis |
| :- | :- |
| [`hide(self)`](/slides/python-net/cs/aspose.slides.charts/datalabel/hide/#) | Skryje popisek dat nastavením všech příznaků Show*- (ShowValue, ...) na false.<br/>            IsVisible bude po této operaci false. |
| [`get_actual_label_text(self)`](/slides/python-net/cs/aspose.slides.charts/datalabel/get_actual_label_text/#) | Vrací aktuální text popisku založený na nastaveních DataLabelFormat nebo hodnotě TextFrameForOverriding.Text. |
| [`add_text_frame_for_overriding(self, text)`](/slides/python-net/cs/aspose.slides.charts/datalabel/add_text_frame_for_overriding/#str) | Inicializuje TextFrameForOverriding pomocí textu v parametru "text".<br/>            Pokud je TextFrameForOverriding již inicializován, jednoduše změní jeho text. |

### Viz také
* modul [`aspose.slides.charts`](/slides/python-net/cs/aspose.slides.charts)
* knihovna [`Aspose.Slides`](/slides/python-net)