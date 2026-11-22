---
title: DataLabel class
second_title: Aspose.Slides pro Python prostřednictvím .NET API Reference
description: 
type: docs
url: /cs/aspose.slides.charts/datalabel/
---
## DataLabel třída

Představuje popisky řady.

Typ DataLabel poskytuje následující členy:

## Konstruktory

| Konstruktor | Popis |
| :- | :- |
| [`__init__(self, parent_immediate)`](/slides/python-net/cs/aspose.slides.charts/datalabel/__init__/#ichartdatapoint) | Vytvoří novou instanci třídy DataLabel. |

## Vlastnosti

| Vlastnost | Popis |
| :- | :- |
| [`chart`](/slides/python-net/cs/aspose.slides.charts/datalabel/chart/) | Vrací nadřazený graf.<br/>            Pouze pro čtení [`IChart`](/slides/python-net/cs/aspose.slides.charts/ichart). |
| [`is_visible`](/slides/python-net/cs/aspose.slides.charts/datalabel/is_visible/) | False znamená, že popisek dat není viditelný (a tak jsou všechny příznaky Show*- (ShowValue, ...) nastaveny na false).<br/>            Pouze pro čtení **bool**. |
| [`text_frame_for_overriding`](/slides/python-net/cs/aspose.slides.charts/datalabel/text_frame_for_overriding/) | Může obsahovat bohatě formátovaný text. Pokud tato vlastnost není None, pak tato <br/>            hodnota formátovaného textu přepíše automaticky generovaný text popisku dat.<br/>            Automaticky generovaný text popisku dat znamená text spravovaný pomocí vlastností ShowSeriesName, <br/>            ShowValue, ... a formátovaný pomocí vlastnosti TextFormatManager.TextFormat.<br/>            Pouze pro čtení [`ITextFrame`](/slides/python-net/cs/aspose.slides/itextframe). |
| [`text_format`](/slides/python-net/cs/aspose.slides.charts/datalabel/text_format/) | Vrací formát textu.<br/>            Pouze pro čtení [`IChartTextFormat`](/slides/python-net/cs/aspose.slides.charts/icharttextformat). |
| [`x`](/slides/python-net/cs/aspose.slides.charts/datalabel/x/) | Vrací nebo nastavuje souřadnici x titulku jako podíl šířky grafu.<br/>            Čtení/Zápis **float**. |
| [`y`](/slides/python-net/cs/aspose.slides.charts/datalabel/y/) | Vrací nebo nastavuje souřadnici y titulku jako podíl výšky grafu.<br/>            Čtení/Zápis **float**. |
| [`width`](/slides/python-net/cs/aspose.slides.charts/datalabel/width/) | Vrací nebo nastavuje šířku titulku jako podíl šířky grafu.<br/>            Čtení/Zápis **float**. |
| [`height`](/slides/python-net/cs/aspose.slides.charts/datalabel/height/) | Vrací nebo nastavuje výšku titulku jako podíl výšky grafu.<br/>            Čtení/Zápis **float**. |
| [`right`](/slides/python-net/cs/aspose.slides.charts/datalabel/right/) | Vpravo.<br/>            Pouze pro čtení **float**. |
| [`bottom`](/slides/python-net/cs/aspose.slides.charts/datalabel/bottom/) | Dole.<br/>            Pouze pro čtení **float**. |
| [`data_label_format`](/slides/python-net/cs/aspose.slides.charts/datalabel/data_label_format/) | Vrací formát popisku dat.<br/>            Pouze pro čtení [`IDataLabelFormat`](/slides/python-net/cs/aspose.slides.charts/idatalabelformat). |
| [`value_from_cell`](/slides/python-net/cs/aspose.slides.charts/datalabel/value_from_cell/) | Získá nebo nastaví buňku dat sešitu. Používá se, pokud je vlastnost IDataLabelFormat.ShowLabelValueFromCell nastavena na true. |
| [`label_shape_type`](/slides/python-net/cs/aspose.slides.charts/datalabel/label_shape_type/) | Získá nebo nastaví typ tvaru popisku dat.<br/>             Vrací [`ShapeType.NOT_DEFINED`](/slides/python-net/cs/aspose.slides/shapetype/NOT_DEFINED), pokud není tvar definován. |
| [`actual_x`](/slides/python-net/cs/aspose.slides.charts/datalabel/actual_x/) | Určuje skutečnou polohu x (vlevo) prvku grafu relativně k levému hornímu rohu grafu.<br/>            Zavolejte metodu IChart.ValidateChartLayout() před získáním skutečných hodnot. <br/>            Čtení **float**. |
| [`actual_y`](/slides/python-net/cs/aspose.slides.charts/datalabel/actual_y/) | Určuje skutečný horní okraj prvku grafu relativně k levému hornímu rohu grafu.<br/>            Zavolejte metodu IChart.ValidateChartLayout() před získáním skutečných hodnot. <br/>            Čtení **float**. |
| [`actual_width`](/slides/python-net/cs/aspose.slides.charts/datalabel/actual_width/) | Určuje skutečnou šířku prvku grafu. Zavolejte metodu IChart.ValidateChartLayout() před získáním skutečných hodnot. <br/>            Čtení **float**. |
| [`actual_height`](/slides/python-net/cs/aspose.slides.charts/datalabel/actual_height/) | Určuje skutečnou výšku prvku grafu. Zavolejte metodu IChart.ValidateChartLayout() před získáním skutečných hodnot. <br/>            Čtení **float**. |
| [`slide`](/slides/python-net/cs/aspose.slides.charts/datalabel/slide/) |  |
| [`presentation`](/slides/python-net/cs/aspose.slides.charts/datalabel/presentation/) |  |

## Metody

| Metoda | Popis |
| :- | :- |
| [`hide(self)`](/slides/python-net/cs/aspose.slides.charts/datalabel/hide/#) | Skryje popisek dat nastavením všech příznaků Show*- (ShowValue, ...) do stavu false.<br/>            IsVisible bude po tomto nastavení false. |
| [`get_actual_label_text(self)`](/slides/python-net/cs/aspose.slides.charts/datalabel/get_actual_label_text/#) | Vrací aktuální text popisku na základě nastavení DataLabelFormat nebo hodnoty TextFrameForOverriding.Text. |
| [`add_text_frame_for_overriding(self, text)`](/slides/python-net/cs/aspose.slides.charts/datalabel/add_text_frame_for_overriding/#str) | Inicializuje TextFrameForOverriding textem v parametru "text".<br/>            Pokud je TextFrameForOverriding již inicializováno, jednoduše změní jeho text. |

### Viz také
* modul [`aspose.slides.charts`](/slides/python-net/cs/aspose.slides.charts)
* knihovna [`Aspose.Slides`](/slides/python-net)