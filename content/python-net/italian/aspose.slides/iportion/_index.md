---
title: IPortion class
second_title: Riferimento API di Aspose.Slides per Python via .NET
description: 
type: docs
url: /it/aspose.slides/iportion/
---
## IPortion classe

Rappresenta una porzione di testo all'interno di un paragrafo di testo.

Il tipo IPortion espone i seguenti membri:

## Proprietà

| Property | Description |
| :- | :- |
| [`portion_format`](/slides/python-net/it/aspose.slides/iportion/portion_format/) | Restituisce l'oggetto di formattazione che contiene le proprietà di formattazione impostate esplicitamente della porzione di testo senza ereditarietà applicata.<br/>            Solo lettura [`IPortionFormat`](/slides/python-net/it/aspose.slides/iportionformat). |
| [`text`](/slides/python-net/it/aspose.slides/iportion/text/) | Ottiene o imposta il testo semplice di una porzione.<br/>            Lettura/scrittura **str**. |
| [`field`](/slides/python-net/it/aspose.slides/iportion/field/) | Restituisce un campo di questa porzione.<br/>            Solo lettura [`IField`](/slides/python-net/it/aspose.slides/ifield). |
| [`slide`](/slides/python-net/it/aspose.slides/iportion/slide/) |  |
| [`presentation`](/slides/python-net/it/aspose.slides/iportion/presentation/) |  |

## Metodi

| Method | Description |
| :- | :- |
| [`add_field(self, field_type)`](/slides/python-net/it/aspose.slides/iportion/add_field/#ifieldtype) | Converte questa porzione nel campo aggiornato automaticamente. |
| [`add_field(self, internal_string)`](/slides/python-net/it/aspose.slides/iportion/add_field/#str) | Converte questa porzione nel campo aggiornato automaticamente. |
| [`remove_field(self)`](/slides/python-net/it/aspose.slides/iportion/remove_field/#) | Converte questa porzione di campo nella porzione semplice. |
| [`get_rect(self)`](/slides/python-net/it/aspose.slides/iportion/get_rect/#) | Ottieni le coordinate del rettangolo che delimita la porzione. Il rettangolo include tutte le righe di<br/>            testo nella porzione, incluse quelle vuote. |
| [`get_coordinates(self)`](/slides/python-net/it/aspose.slides/iportion/get_coordinates/#) | Ottieni le coordinate dell'inizio della porzione. La coordinata X del punto rappresenta l'inizio della porzione dal primo carattere includendo la sporgenza laterale sinistra. La coordinata Y include la sporgenza superiore. |


### Vedi anche
* modulo [`aspose.slides`](/slides/python-net/it/aspose.slides)
* libreria [`Aspose.Slides`](/slides/python-net)