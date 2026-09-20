---
title: IVideo class
second_title: Riferimento API di Aspose.Slides per Python via .NET
description: 
type: docs
url: /it/aspose.slides/ivideo/
---
## IVideo classe

Rappresenta un video incorporato in una presentazione.

Il tipo IVideo espone i seguenti membri:

## Proprietà

| Proprietà | Descrizione |
| :- | :- |
| [`content_type`](/slides/python-net/it/aspose.slides/ivideo/content_type/) | Restituisce un tipo MIME di un video, codificato in [`IVideo.binary_data`](/slides/python-net/it/aspose.slides/ivideo/binary_data).<br/>            Solo lettura **str**. |
| [`binary_data`](/slides/python-net/it/aspose.slides/ivideo/binary_data/) | Restituisce una copia dei dati audio. In caso di grande quantità di dati, considerare l'uso del <br/>            metodo [`IVideo.get_stream`](/slides/python-net/it/aspose.slides/ivideo/get_stream) per evitare il caricamento non necessario dei dati del video in memoria <br/>            o addirittura un OutOfMemoryException.<br/>            Solo lettura **int**[]. |

## Metodi

| Metodo | Descrizione |
| :- | :- |
| [`get_stream(self)`](/slides/python-net/it/aspose.slides/ivideo/get_stream/#) | Restituisce lo stream Stream per la lettura.<br/>            Usa 'using' o chiudi lo stream dopo l'uso. |


### Vedi anche
* modulo [`aspose.slides`](/slides/python-net/it/aspose.slides)
* libreria [`Aspose.Slides`](/slides/python-net)