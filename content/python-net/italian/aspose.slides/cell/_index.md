---
title: Cell class
second_title: Riferimento API di Aspose.Slides per Python via .NET
description: 
type: docs
url: /it/aspose.slides/cell/
---
## Classe Cell

Rappresenta una cella di una tabella.

Il tipo Cell espone i seguenti membri:

## Proprietà

| Proprietà | Descrizione |
| :- | :- |
| [`offset_x`](/slides/python-net/it/aspose.slides/cell/offset_x/) | Restituisce una distanza dal lato sinistro di una tabella al lato sinistro di una cella.<br/>            Solo lettura **float**. |
| [`offset_y`](/slides/python-net/it/aspose.slides/cell/offset_y/) | Restituisce una distanza dal lato superiore di una tabella al lato superiore di una cella.<br/>            Solo lettura **float**. |
| [`first_row_index`](/slides/python-net/it/aspose.slides/cell/first_row_index/) | Restituisce l'indice della prima riga coperta dalla cella.<br/>            Solo lettura **int**. |
| [`first_column_index`](/slides/python-net/it/aspose.slides/cell/first_column_index/) | Restituisce l'indice della prima colonna coperta dalla cella.<br/>            Solo lettura **int**. |
| [`width`](/slides/python-net/it/aspose.slides/cell/width/) | Restituisce la larghezza della cella.<br/>            Solo lettura **float**. |
| [`height`](/slides/python-net/it/aspose.slides/cell/height/) | Restituisce l'altezza della cella.<br/>            Solo lettura **float**. |
| [`minimal_height`](/slides/python-net/it/aspose.slides/cell/minimal_height/) | Restituisce l'altezza minima di una cella.<br/>            Questa è la somma delle altezze minime di tutte le righe coperte dalla cella.<br/>            Solo lettura **float**. |
| [`margin_left`](/slides/python-net/it/aspose.slides/cell/margin_left/) | Restituisce o imposta il margine sinistro in un TextFrame.<br/>            Lettura/scrittura **float**. |
| [`margin_right`](/slides/python-net/it/aspose.slides/cell/margin_right/) | Restituisce o imposta il margine destro in un TextFrame.<br/>            Lettura/scrittura **float**. |
| [`margin_top`](/slides/python-net/it/aspose.slides/cell/margin_top/) | Restituisce o imposta il margine superiore in un TextFrame.<br/>            Lettura/scrittura **float**. |
| [`margin_bottom`](/slides/python-net/it/aspose.slides/cell/margin_bottom/) | Restituisce o imposta il margine inferiore in un TextFrame.<br/>            Lettura/scrittura **float**. |
| [`text_vertical_type`](/slides/python-net/it/aspose.slides/cell/text_vertical_type/) | Restituisce o imposta il tipo di testo verticale.<br/>            Lettura/scrittura [`TextVerticalType`](/slides/python-net/it/aspose.slides/textverticaltype). |
| [`text_anchor_type`](/slides/python-net/it/aspose.slides/cell/text_anchor_type/) | Restituisce o imposta il tipo di ancoraggio del testo.<br/>            Lettura/scrittura [`TextAnchorType`](/slides/python-net/it/aspose.slides/textanchortype). |
| [`anchor_center`](/slides/python-net/it/aspose.slides/cell/anchor_center/) | Determina se la casella di testo è centrata all'interno di una cella.<br/>            Lettura/scrittura **bool**. |
| [`first_row`](/slides/python-net/it/aspose.slides/cell/first_row/) | Ottiene la prima riga della cella.<br/>            Solo lettura [`IRow`](/slides/python-net/it/aspose.slides/irow). |
| [`first_column`](/slides/python-net/it/aspose.slides/cell/first_column/) | Ottiene la prima colonna della cella.<br/>            Solo lettura [`IColumn`](/slides/python-net/it/aspose.slides/icolumn). |
| [`col_span`](/slides/python-net/it/aspose.slides/cell/col_span/) | Restituisce il numero di colonne della griglia nella griglia della tabella padre<br/>            che deve essere coperto dalla cella corrente. Questa proprietà consente alle celle<br/>            di apparire fuse, poiché si estendono sui confini verticali<br/>            di altre celle nella tabella.<br/>            Solo lettura **int**. |
| [`row_span`](/slides/python-net/it/aspose.slides/cell/row_span/) | Restituisce il numero di righe che una cella fusa occupa. Questo è usato in combinazione<br/>            con l'attributo vMerge su altre celle per specificare la cella iniziale<br/>            di una fusione orizzontale.<br/>            Solo lettura **int**. |
| [`text_frame`](/slides/python-net/it/aspose.slides/cell/text_frame/) | Restituisce il frame di testo di una cella.<br/>            Solo lettura [`ITextFrame`](/slides/python-net/it/aspose.slides/itextframe). |
| [`table`](/slides/python-net/it/aspose.slides/cell/table/) | Restituisce l'oggetto Table padre per una cella.<br/>            Solo lettura [`ITable`](/slides/python-net/it/aspose.slides/itable). |
| [`is_merged_cell`](/slides/python-net/it/aspose.slides/cell/is_merged_cell/) | Restituisce true se la cella è fusa con qualche cella aggiustata, false altrimenti.<br/>            Solo lettura **bool**. |
| [`cell_format`](/slides/python-net/it/aspose.slides/cell/cell_format/) | Restituisce l'oggetto CellFormat che contiene le proprietà di formattazione per questa cella.<br/>            Solo lettura [`ICellFormat`](/slides/python-net/it/aspose.slides/icellformat). |
| [`slide`](/slides/python-net/it/aspose.slides/cell/slide/) | Restituisce la slide padre di una cella.<br/>            Solo lettura [`IBaseSlide`](/slides/python-net/it/aspose.slides/ibaseslide). |
| [`presentation`](/slides/python-net/it/aspose.slides/cell/presentation/) | Restituisce la presentazione padre di una cella.<br/>            Solo lettura [`IPresentation`](/slides/python-net/it/aspose.slides/ipresentation). |

## Metodi

| Metodo | Descrizione |
| :- | :- |
| [`split_by_col_span(self, index)`](/slides/python-net/it/aspose.slides/cell/split_by_col_span/#int) | Divide la cella in due celle per indice di colonna. |
| [`split_by_row_span(self, index)`](/slides/python-net/it/aspose.slides/cell/split_by_row_span/#int) | Divide la cella in due celle per indice di riga. |
| [`split_by_height(self, height)`](/slides/python-net/it/aspose.slides/cell/split_by_height/#float) | Divide la cella per altezza. |
| [`split_by_width(self, width)`](/slides/python-net/it/aspose.slides/cell/split_by_width/#float) | Divide la cella per larghezza. |

### Vedi anche
* modulo [`aspose.slides`](/slides/python-net/it/aspose.slides)
* libreria [`Aspose.Slides`](/slides/python-net)