---
title: IDataLabel class
second_title: Aspose.Slides para Python via .NET Referência da API
description: 
type: docs
url: /pt/aspose.slides.charts/idatalabel/
---
## IDataLabel classe

Representa rótulos de série.

O tipo IDataLabel expõe os seguintes membros:

## Propriedades

| Propriedade | Descrição |
| :- | :- |
| [`is_visible`](/slides/python-net/pt/aspose.slides.charts/idatalabel/is_visible/) | False significa que o rótulo de dados não está visível (e, portanto, todas as flags Show*- (ShowValue, ...) são falsas).<br/>            Somente leitura **bool**. |
| [`data_label_format`](/slides/python-net/pt/aspose.slides.charts/idatalabel/data_label_format/) | Retorna o formato do rótulo de dados.<br/>            Somente leitura [`IDataLabelFormat`](/slides/python-net/pt/aspose.slides.charts/idatalabelformat). |
| [`value_from_cell`](/slides/python-net/pt/aspose.slides.charts/idatalabel/value_from_cell/) | Obtém ou define a célula de dados da planilha. Aplicado se a propriedade IDataLabelFormat.ShowLabelValueFromCell for verdadeira. |
| [`x`](/slides/python-net/pt/aspose.slides.charts/idatalabel/x/) |  |
| [`y`](/slides/python-net/pt/aspose.slides.charts/idatalabel/y/) |  |
| [`width`](/slides/python-net/pt/aspose.slides.charts/idatalabel/width/) |  |
| [`height`](/slides/python-net/pt/aspose.slides.charts/idatalabel/height/) |  |
| [`right`](/slides/python-net/pt/aspose.slides.charts/idatalabel/right/) |  |
| [`bottom`](/slides/python-net/pt/aspose.slides.charts/idatalabel/bottom/) |  |
| [`chart`](/slides/python-net/pt/aspose.slides.charts/idatalabel/chart/) |  |
| [`slide`](/slides/python-net/pt/aspose.slides.charts/idatalabel/slide/) |  |
| [`presentation`](/slides/python-net/pt/aspose.slides.charts/idatalabel/presentation/) |  |
| [`text_frame_for_overriding`](/slides/python-net/pt/aspose.slides.charts/idatalabel/text_frame_for_overriding/) |  |
| [`text_format`](/slides/python-net/pt/aspose.slides.charts/idatalabel/text_format/) |  |
| [`actual_x`](/slides/python-net/pt/aspose.slides.charts/idatalabel/actual_x/) |  |
| [`actual_y`](/slides/python-net/pt/aspose.slides.charts/idatalabel/actual_y/) |  |
| [`actual_width`](/slides/python-net/pt/aspose.slides.charts/idatalabel/actual_width/) |  |
| [`actual_height`](/slides/python-net/pt/aspose.slides.charts/idatalabel/actual_height/) |  |

## Métodos

| Método | Descrição |
| :- | :- |
| [`hide(self)`](/slides/python-net/pt/aspose.slides.charts/idatalabel/hide/#) | Oculta o rótulo de dados definindo todas as flags Show*- (ShowValue, ...) para o estado falso.<br/>            IsVisible será falso após isso. |
| [`get_actual_label_text(self)`](/slides/python-net/pt/aspose.slides.charts/idatalabel/get_actual_label_text/#) | Retorna o texto real do rótulo com base nas configurações de DataLabelFormat ou no valor TextFrameForOverriding.Text. |
| [`add_text_frame_for_overriding(self, text)`](/slides/python-net/pt/aspose.slides.charts/idatalabel/add_text_frame_for_overriding/#str) |  |


### Ver Também
* módulo [`aspose.slides.charts`](/slides/python-net/pt/aspose.slides.charts)
* biblioteca [`Aspose.Slides`](/slides/python-net)