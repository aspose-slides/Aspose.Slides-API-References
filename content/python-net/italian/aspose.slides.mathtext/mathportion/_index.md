---
title: MathPortion class
second_title: Riferimento API Aspose.Slides per Python via .NET
description: 
type: docs
url: /it/aspose.slides.mathtext/mathportion/
---
## MathPortion classe

Rappresenta una porzione con contesto matematico al suo interno.

**Inheritance:**[`MathPortion`](/slides/python-net/it/aspose.slides.mathtext/mathportion) → [`Portion`](/slides/python-net/it/aspose.slides/portion)

Il tipo MathPortion espone i seguenti membri:

## Costruttori

| Constructor | Description |
| :- | :- |
| [`__init__(self)`](/slides/python-net/it/aspose.slides.mathtext/mathportion/__init__/#) | Inizializza una nuova istanza della classe MathPortion. |

## Proprietà

| Property | Description |
| :- | :- |
| [`portion_format`](/slides/python-net/it/aspose.slides.mathtext/mathportion/portion_format/) | Restituisce l'oggetto di formattazione che contiene le proprietà di formattazione impostate esplicitamente della porzione di testo senza alcuna ereditarietà applicata.<br/>            Sola lettura [`IPortionFormat`](/slides/python-net/it/aspose.slides/iportionformat). |
| [`text`](/slides/python-net/it/aspose.slides.mathtext/mathportion/text/) | Ottiene o imposta il testo semplice di una porzione.<br/>            Lettura/scrittura **str**. |
| [`field`](/slides/python-net/it/aspose.slides.mathtext/mathportion/field/) | Restituisce un campo di questa porzione.<br/>            Sola lettura [`IField`](/slides/python-net/it/aspose.slides/ifield). |
| [`math_paragraph`](/slides/python-net/it/aspose.slides.mathtext/mathportion/math_paragraph/) | Paragrafo matematico |
| [`slide`](/slides/python-net/it/aspose.slides.mathtext/mathportion/slide/) |  |
| [`presentation`](/slides/python-net/it/aspose.slides.mathtext/mathportion/presentation/) |  |

## Metodi

| Method | Description |
| :- | :- |
| [`add_field(self, field_type)`](/slides/python-net/it/aspose.slides.mathtext/mathportion/add_field/#ifieldtype) | Converte questa porzione nel campo aggiornato automaticamente. |
| [`add_field(self, internal_string)`](/slides/python-net/it/aspose.slides.mathtext/mathportion/add_field/#str) | Converte questa porzione nel campo aggiornato automaticamente. |
| [`remove_field(self)`](/slides/python-net/it/aspose.slides.mathtext/mathportion/remove_field/#) | Converte questa porzione di campo nella porzione semplice. |
| [`get_rect(self)`](/slides/python-net/it/aspose.slides.mathtext/mathportion/get_rect/#) | Ottiene le coordinate del rettangolo che delimita la porzione. Il rettangolo include tutte le linee di<br/>             testo nella porzione, incluse quelle vuote. |
| [`get_coordinates(self)`](/slides/python-net/it/aspose.slides.mathtext/mathportion/get_coordinates/#) | Ottiene le coordinate dell'inizio della porzione. La coordinata X del punto rappresenta l'inizio della porzione dal primo carattere, inclusa la sporgenza laterale sinistra. La coordinata Y include la sporgenza superiore. |

### Vedi anche
* classe [`MathPortion`](/slides/python-net/it/aspose.slides.mathtext/mathportion)
* classe [`Portion`](/slides/python-net/it/aspose.slides/portion)
* modulo [`aspose.slides.mathtext`](/slides/python-net/it/aspose.slides.mathtext)
* libreria [`Aspose.Slides`](/slides/python-net)