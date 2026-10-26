---
title: Video class
second_title: Riferimento API Aspose.Slides per Python via .NET
description: 
type: docs
url: /it/aspose.slides/video/
---
## Classe Video

Rappresenta un'immagine incorporata in una presentazione.

Il tipo Video espone i seguenti membri:

## Proprietà

| Proprietà | Descrizione |
| :- | :- |
| [`content_type`](/slides/python-net/it/aspose.slides/video/content_type/) | Restituisce un tipo MIME di un video, codificato in [`Video.binary_data`](/slides/python-net/it/aspose.slides/video/binary_data).<br/>            Solo lettura **str**. |
| [`binary_data`](/slides/python-net/it/aspose.slides/video/binary_data/) | Restituisce una copia dei dati audio. In caso di grande quantità di dati, considerare l'uso di <br/>            [`Video.get_stream`](/slides/python-net/it/aspose.slides/video/get_stream) metodo per evitare il caricamento non necessario dei dati video in memoria <br/>            o anche OutOfMemoryException.<br/>            Solo lettura **int**[]. |

## Metodi

| Metodo | Descrizione |
| :- | :- |
| [`get_stream(self)`](/slides/python-net/it/aspose.slides/video/get_stream/#) | Restituisce lo stream Stream per la lettura.<br/>            Usa 'using' o chiudi lo stream dopo l'uso. |


### Vedi anche
* modulo [`aspose.slides`](/slides/python-net/it/aspose.slides)
* libreria [`Aspose.Slides`](/slides/python-net)