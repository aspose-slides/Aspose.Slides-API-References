---
title: ICell class
second_title: Riferimento API di Aspose.Slides per Python via .NET
description: 
type: docs
url: /it/aspose.slides/icell/
---
## ICell classe

Rappresenta una cella in una tabella.

Il tipo ICell espone i seguenti membri:

## Proprietà

| Property | Description |
| :- | :- |
| [`offset_x`](/slides/python-net/it/aspose.slides/icell/offset_x/) | Restituisce una distanza dal lato sinistro di una tabella al lato sinistro di una cella.<br/>            Solo lettura **float**. |
| [`offset_y`](/slides/python-net/it/aspose.slides/icell/offset_y/) | Restituisce una distanza dal lato superiore di una tabella al lato superiore di una cella.<br/>            Solo lettura **float**. |
| [`first_row_index`](/slides/python-net/it/aspose.slides/icell/first_row_index/) | Restituisce l'indice della prima riga coperta dalla cella.<br/>            Solo lettura **int**. |
| [`first_column_index`](/slides/python-net/it/aspose.slides/icell/first_column_index/) | Restituisce l'indice della prima colonna coperta dalla cella.<br/>            Solo lettura **int**. |
| [`width`](/slides/python-net/it/aspose.slides/icell/width/) | Restituisce la larghezza della cella.<br/>            Solo lettura **float**. |
| [`height`](/slides/python-net/it/aspose.slides/icell/height/) | Restituisce l'altezza della cella.<br/>            Solo lettura **float**. |
| [`minimal_height`](/slides/python-net/it/aspose.slides/icell/minimal_height/) | Restituisce l'altezza minima di una cella.<br/>            Questa è la somma delle altezze minime di tutte le righe coperte dalla cella.<br/>            Solo lettura **float**. |
| [`margin_left`](/slides/python-net/it/aspose.slides/icell/margin_left/) | Restituisce o imposta il margine sinistro in un TextFrame.<br/>            Lettura/scrittura **float**. |
| [`margin_right`](/slides/python-net/it/aspose.slides/icell/margin_right/) | Restituisce o imposta il margine destro in un TextFrame.<br/>            Lettura/scrittura **float**. |
| [`margin_top`](/slides/python-net/it/aspose.slides/icell/margin_top/) | Restituisce o imposta il margine superiore in un TextFrame.<br/>            Lettura/scrittura **float**. |
| [`margin_bottom`](/slides/python-net/it/aspose.slides/icell/margin_bottom/) | Restituisce o imposta il margine inferiore in un TextFrame.<br/>            Lettura/scrittura **float**. |
| [`text_vertical_type`](/slides/python-net/it/aspose.slides/icell/text_vertical_type/) | Restituisce o imposta il tipo di testo verticale.<br/>            Lettura/scrittura [`TextVerticalType`](/slides/python-net/it/aspose.slides/textverticaltype). |
| [`text_anchor_type`](/slides/python-net/it/aspose.slides/icell/text_anchor_type/) | Restituisce o imposta il tipo di ancoraggio del testo.<br/>            Lettura/scrittura [`TextAnchorType`](/slides/python-net/it/aspose.slides/textanchortype). |
| [`anchor_center`](/slides/python-net/it/aspose.slides/icell/anchor_center/) | Determina se la casella di testo è centrata all'interno di una cella.<br/>            Lettura/scrittura **bool**. |
| [`first_column`](/slides/python-net/it/aspose.slides/icell/first_column/) | Ottiene la prima colonna della cella.<br/>            Solo lettura [`IColumn`](/slides/python-net/it/aspose.slides/icolumn). |
| [`first_row`](/slides/python-net/it/aspose.slides/icell/first_row/) | Ottiene la prima riga della cella.<br/>            Solo lettura [`IRow`](/slides/python-net/it/aspose.slides/irow). |
| [`col_span`](/slides/python-net/it/aspose.slides/icell/col_span/) | Restituisce il numero di colonne della griglia della tabella padre che devono essere coperte dalla cella corrente. Questa proprietà consente alle celle di avere l'aspetto di essere unite, poiché si estendono attraverso i confini verticali di altre celle nella tabella.<br/>            Solo lettura **int**. |
| [`row_span`](/slides/python-net/it/aspose.slides/icell/row_span/) | Restituisce il numero di righe che una cella unita occupa. Questo è usato in combinazione<br/>            con l'attributo vMerge su altre celle per specificare la cella iniziale<br/>            di una fusione orizzontale.<br/>            Solo lettura **int**. |
| [`text_frame`](/slides/python-net/it/aspose.slides/icell/text_frame/) | Restituisce il frame di testo di una cella.<br/>            Solo lettura [`ITextFrame`](/slides/python-net/it/aspose.slides/itextframe). |
| [`table`](/slides/python-net/it/aspose.slides/icell/table/) | Restituisce l'oggetto Table genitore di una cella.<br/>            Solo lettura [`ITable`](/slides/python-net/it/aspose.slides/itable). |
| [`is_merged_cell`](/slides/python-net/it/aspose.slides/icell/is_merged_cell/) | Restituisce true se la cella è unita a qualsiasi cella aggiustata, false altrimenti.<br/>            Solo lettura **bool**. |
| [`cell_format`](/slides/python-net/it/aspose.slides/icell/cell_format/) | Restituisce l'oggetto CellFormat che contiene le proprietà di formattazione per questa cella.<br/>            Solo lettura [`ICellFormat`](/slides/python-net/it/aspose.slides/icellformat). |
| [`slide`](/slides/python-net/it/aspose.slides/icell/slide/) |  |
| [`presentation`](/slides/python-net/it/aspose.slides/icell/presentation/) |  |

## Metodi

| Method | Description |
| :- | :- |
| [`split_by_col_span(self, index)`](/slides/python-net/it/aspose.slides/icell/split_by_col_span/#int) | Divide la cella in due celle per indice di colonna. |
| [`split_by_row_span(self, index)`](/slides/python-net/it/aspose.slides/icell/split_by_row_span/#int) | Divide la cella in due celle per indice di riga. |
| [`split_by_height(self, height)`](/slides/python-net/it/aspose.slides/icell/split_by_height/#float) | Divide la cella per altezza. |
| [`split_by_width(self, width)`](/slides/python-net/it/aspose.slides/icell/split_by_width/#float) | Divide la cella per larghezza. |


### Vedi anche
* modulo [`aspose.slides`](/slides/python-net/it/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)