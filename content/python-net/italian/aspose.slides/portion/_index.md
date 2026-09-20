---
title: Portion class
second_title: Riferimento API Aspose.Slides per Python via .NET
description: 
type: docs
url: /it/aspose.slides/portion/
---
## Portion classe

Rappresenta una porzione di testo all'interno di un paragrafo di testo.

Il tipo Portion espone i seguenti membri:

## Costruttori

| Costruttore | Descrizione |
| :- | :- |
| [`__init__(self)`](/slides/python-net/it/aspose.slides/portion/__init__/#) | Initializes a new instance of the Portion class. |
| [`__init__(self, str)`](/slides/python-net/it/aspose.slides/portion/__init__/#str) | Initializes a new instance of the Portion class. |
| [`__init__(self, portion)`](/slides/python-net/it/aspose.slides/portion/__init__/#portion) | Initializes a new instance of the Portion class. |

## Proprietà

| Proprietà | Descrizione |
| :- | :- |
| [`portion_format`](/slides/python-net/it/aspose.slides/portion/portion_format/) | Restituisce l'oggetto di formattazione che contiene le proprietà di formattazione impostate esplicitamente della porzione di testo senza ereditarietà applicata.<br/>            Solo lettura [`IPortionFormat`](/slides/python-net/it/aspose.slides/iportionformat). |
| [`text`](/slides/python-net/it/aspose.slides/portion/text/) | Ottiene o imposta il testo semplice di una porzione.<br/>            Lettura/scrittura **str**. |
| [`field`](/slides/python-net/it/aspose.slides/portion/field/) | Restituisce un campo di questa porzione.<br/>            Solo lettura [`IField`](/slides/python-net/it/aspose.slides/ifield). |
| [`slide`](/slides/python-net/it/aspose.slides/portion/slide/) |  |
| [`presentation`](/slides/python-net/it/aspose.slides/portion/presentation/) |  |

## Metodi

| Metodo | Descrizione |
| :- | :- |
| [`add_field(self, field_type)`](/slides/python-net/it/aspose.slides/portion/add_field/#ifieldtype) | Converte questa porzione nel campo aggiornato automaticamente. |
| [`add_field(self, internal_string)`](/slides/python-net/it/aspose.slides/portion/add_field/#str) | Converte questa porzione nel campo aggiornato automaticamente. |
| [`remove_field(self)`](/slides/python-net/it/aspose.slides/portion/remove_field/#) | Converte questa porzione di campo nella porzione semplice. |
| [`get_rect(self)`](/slides/python-net/it/aspose.slides/portion/get_rect/#) | Ottiene le coordinate del rettangolo che delimitano la porzione. Il rettangolo include tutte le righe di<br/>             testo nella porzione, incluse quelle vuote. |
| [`get_coordinates(self)`](/slides/python-net/it/aspose.slides/portion/get_coordinates/#) | Ottiene le coordinate dell'inizio della porzione. La coordinata X del punto rappresenta l'inizio della porzione dal primo carattere includendo il margine laterale sinistro. La coordinata Y include il margine superiore. |


### Vedi anche
* modulo [`aspose.slides`](/slides/python-net/it/aspose.slides)
* libreria [`Aspose.Slides`](/slides/python-net)