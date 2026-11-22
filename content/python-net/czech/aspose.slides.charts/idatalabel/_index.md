---
title: IDataLabel class
second_title: Aspose.Slides pro Python přes .NET API Reference
description: 
type: docs
url: /cs/aspose.slides.charts/idatalabel/
---
## IDataLabel třída

Reprezentuje popisky řady.

Typ IDataLabel obsahuje následující členy:

## Vlastnosti

| Vlastnost | Popis |
| :- | :- |
| [`is_visible`](/slides/python-net/cs/aspose.slides.charts/idatalabel/is_visible/) | False znamená, že popisek dat není viditelný (a tedy všechny příznaky Show*-flags (ShowValue, ...) jsou nastaveny na false).<br/>            Read-only **bool**. |
| [`data_label_format`](/slides/python-net/cs/aspose.slides.charts/idatalabel/data_label_format/) | Vrací formát popisku dat.<br/>            Read-only [`IDataLabelFormat`](/slides/python-net/cs/aspose.slides.charts/idatalabelformat). |
| [`value_from_cell`](/slides/python-net/cs/aspose.slides.charts/idatalabel/value_from_cell/) | Získá nebo nastaví buňku dat sešitu. Použije se, pokud je vlastnost IDataLabelFormat.ShowLabelValueFromCell nastavena na true. |
| [`label_shape_type`](/slides/python-net/cs/aspose.slides.charts/idatalabel/label_shape_type/) | Získá nebo nastaví typ tvaru popisku dat.<br/>             Vrací [`ShapeType.NOT_DEFINED`](/slides/python-net/cs/aspose.slides/shapetype/NOT_DEFINED), pokud není definován žádný tvar. |
| [`x`](/slides/python-net/cs/aspose.slides.charts/idatalabel/x/) |  |
| [`y`](/slides/python-net/cs/aspose.slides.charts/idatalabel/y/) |  |
| [`width`](/slides/python-net/cs/aspose.slides.charts/idatalabel/width/) |  |
| [`height`](/slides/python-net/cs/aspose.slides.charts/idatalabel/height/) |  |
| [`right`](/slides/python-net/cs/aspose.slides.charts/idatalabel/right/) |  |
| [`bottom`](/slides/python-net/cs/aspose.slides.charts/idatalabel/bottom/) |  |
| [`chart`](/slides/python-net/cs/aspose.slides.charts/idatalabel/chart/) |  |
| [`slide`](/slides/python-net/cs/aspose.slides.charts/idatalabel/slide/) |  |
| [`presentation`](/slides/python-net/cs/aspose.slides.charts/idatalabel/presentation/) |  |
| [`text_frame_for_overriding`](/slides/python-net/cs/aspose.slides.charts/idatalabel/text_frame_for_overriding/) |  |
| [`text_format`](/slides/python-net/cs/aspose.slides.charts/idatalabel/text_format/) |  |
| [`actual_x`](/slides/python-net/cs/aspose.slides.charts/idatalabel/actual_x/) |  |
| [`actual_y`](/slides/python-net/cs/aspose.slides.charts/idatalabel/actual_y/) |  |
| [`actual_width`](/slides/python-net/cs/aspose.slides.charts/idatalabel/actual_width/) |  |
| [`actual_height`](/slides/python-net/cs/aspose.slides.charts/idatalabel/actual_height/) |  |

## Metody

| Metoda | Popis |
| :- | :- |
| [`hide(self)`](/slides/python-net/cs/aspose.slides.charts/idatalabel/hide/#) | Skryje popisek dat nastavením všech příznaků Show*-flags (ShowValue, ...) do stavu false.<br/>            IsVisible bude po tomto nastavení false. |
| [`get_actual_label_text(self)`](/slides/python-net/cs/aspose.slides.charts/idatalabel/get_actual_label_text/#) | Vrátí aktuální text popisku na základě nastavení DataLabelFormat nebo hodnoty TextFrameForOverriding.Text. |
| [`add_text_frame_for_overriding(self, text)`](/slides/python-net/cs/aspose.slides.charts/idatalabel/add_text_frame_for_overriding/#str) |  |

### Viz také
* modul [`aspose.slides.charts`](/slides/python-net/cs/aspose.slides.charts)
* knihovna [`Aspose.Slides`](/slides/python-net)