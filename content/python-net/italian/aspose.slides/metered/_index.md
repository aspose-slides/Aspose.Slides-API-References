---
title: Metered class
second_title: Riferimento API di Aspose.Slides per Python via .NET
description: 
type: docs
url: /it/aspose.slides/metered/
---
## Metered classe

Fornisce metodi per impostare la chiave a consumo.

Il tipo Metered espone i seguenti membri:

## Costruttori

| Costruttore | Descrizione |
| :- | :- |
| [`__init__(self)`](/slides/python-net/it/aspose.slides/metered/__init__/#) | Inizializza una nuova istanza di questa classe. |

## Metodi

| Metodo | Descrizione |
| :- | :- |
| [`set_metered_key(self, public_key, private_key)`](/slides/python-net/it/aspose.slides/metered/set_metered_key/#str-str) | Imposta la chiave pubblica e privata a consumo.<br/>Se acquisti una licenza a consumo, all’avvio dell’applicazione, questa API dovrebbe essere chiamata; normalmente è sufficiente.<br/>Tuttavia, se il caricamento dei dati di consumo fallisce continuamente e supera le 24 ore, la licenza verrà impostata allo stato di valutazione,<br/>per evitare questo caso, dovresti controllare regolarmente lo stato della licenza; se è in stato di valutazione, chiama nuovamente questa API. |
| [`get_consumption_quantity()`](/slides/python-net/it/aspose.slides/metered/get_consumption_quantity/#) | Restituisce la dimensione del file di consumo |
| [`get_consumption_credit()`](/slides/python-net/it/aspose.slides/metered/get_consumption_credit/#) | Restituisce il credito di consumo |
| [`get_product_name(self)`](/slides/python-net/it/aspose.slides/metered/get_product_name/#) |  |
| [`is_metered_licensed()`](/slides/python-net/it/aspose.slides/metered/is_metered_licensed/#) | Verifica se metered è licenziato |


### Vedi anche
* modulo [`aspose.slides`](/slides/python-net/it/aspose.slides)
* libreria [`Aspose.Slides`](/slides/python-net)