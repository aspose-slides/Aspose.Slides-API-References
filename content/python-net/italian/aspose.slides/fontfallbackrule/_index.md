---
title: FontFallBackRule class
second_title: Aspose.Slides per Python via .NET Riferimento API
description: 
type: docs
url: /it/aspose.slides/fontfallbackrule/
---
## FontFallBackRule classe

Rappresenta la regola di fallback del carattere

Il tipo FontFallBackRule espone i seguenti membri:

## Costruttori

| Costruttore | Descrizione |
| :- | :- |
| [`__init__(self, start_index, end_index, font_names)`](/slides/python-net/it/aspose.slides/fontfallbackrule/__init__/#int-int-str) | Crea una nuova istanza. |
| [`__init__(self, start_index, end_index, font_names)`](/slides/python-net/it/aspose.slides/fontfallbackrule/__init__/#int-int-liststr) | Crea una nuova istanza. |

## Proprietà

| Proprietà | Descrizione |
| :- | :- |
| [`range_start_index`](/slides/python-net/it/aspose.slides/fontfallbackrule/range_start_index/) | Restituisce il primo indice dell'intervallo unicode continuo. |
| [`range_end_index`](/slides/python-net/it/aspose.slides/fontfallbackrule/range_end_index/) | Restituisce l'ultimo indice dell'intervallo unicode continuo. |
| [`count`](/slides/python-net/it/aspose.slides/fontfallbackrule/count/) | Restituisce il numero di font effettivamente definiti per l'intervallo.<br/>            Solo lettura **int**. |

Restituisce il nome del font all'indice specificato.
            Solo lettura [`IFontFallBackRule`](/slides/python-net/it/aspose.slides/ifontfallbackrule).

## Indicizzatore

| Nome | Descrizione |
| :- | :- |
| [`[index]`](/slides/python-net/it/aspose.slides/fontfallbackrule/__getitem__/) |  |

## Metodi

| Metodo | Descrizione |
| :- | :- |
| [`add_fall_back_fonts(self, font_name)`](/slides/python-net/it/aspose.slides/fontfallbackrule/add_fall_back_fonts/#str) | Aggiunge un nuovo font (o più) alla lista di font FallBack. |
| [`add_fall_back_fonts(self, font_names)`](/slides/python-net/it/aspose.slides/fontfallbackrule/add_fall_back_fonts/#liststr) | Aggiunge nuovi font alla lista di font FallBack. |
| [`to_array(self)`](/slides/python-net/it/aspose.slides/fontfallbackrule/to_array/#) | Crea e restituisce un array con tutti i font FallBack per questa regola. |
| [`to_array(self, start_index, count)`](/slides/python-net/it/aspose.slides/fontfallbackrule/to_array/#int-int) | Crea e restituisce un array con tutti i font FallBack dall'intervallo specificato nella lista. |
| [`clear(self)`](/slides/python-net/it/aspose.slides/fontfallbackrule/clear/#) | Rimuove tutti i font dall'elenco. |
| [`remove(self, font_name)`](/slides/python-net/it/aspose.slides/fontfallbackrule/remove/#str) | Rimuove la prima occorrenza di un font FallBack specifico dall'elenco. |
| [`remove_at(self, index)`](/slides/python-net/it/aspose.slides/fontfallbackrule/remove_at/#int) | Rimuove il font FallBack all'indice specificato dell'elenco. |
| [`index_of(self, font_name)`](/slides/python-net/it/aspose.slides/fontfallbackrule/index_of/#str) | Restituisce un indice della regola specificata nella raccolta. |


### Vedi anche
* classe [`IFontFallBackRule`](/slides/python-net/it/aspose.slides/ifontfallbackrule)
* modulo [`aspose.slides`](/slides/python-net/it/aspose.slides)
* libreria [`Aspose.Slides`](/slides/python-net)