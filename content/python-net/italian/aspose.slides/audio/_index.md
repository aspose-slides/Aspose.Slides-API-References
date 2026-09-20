---
title: Audio class
second_title: Riferimento API di Aspose.Slides per Python via .NET
description: 
type: docs
url: /it/aspose.slides/audio/
---
## Audio classe

Rappresenta un file audio incorporato.

Il tipo Audio espone i seguenti membri:

## Proprietà

| Property | Description |
| :- | :- |
| [`content_type`](/slides/python-net/it/aspose.slides/audio/content_type/) | Restituisce un tipo MIME di un audio, codificato in [`Audio.binary_data`](/slides/python-net/it/aspose.slides/audio/binary_data).<br/>            Solo lettura **str**. |
| [`binary_data`](/slides/python-net/it/aspose.slides/audio/binary_data/) | Restituisce la copia dei dati di un audio. In caso di grandi quantità di dati considerare <br/>            l'uso del metodo [`Audio.get_stream`](/slides/python-net/it/aspose.slides/audio/get_stream) per evitare il caricamento inutile dei dati dell'audio<br/>            in memoria o addirittura un OutOfMemoryException.<br/>            Solo lettura **int**[]. |

## Metodi

| Method | Description |
| :- | :- |
| [`get_stream(self)`](/slides/python-net/it/aspose.slides/audio/get_stream/#) | Restituisce lo stream Stream per la lettura.<br/>            Utilizzare 'using' o chiudere lo stream dopo l'uso. |


### Vedi anche
* modulo [`aspose.slides`](/slides/python-net/it/aspose.slides)
* libreria [`Aspose.Slides`](/slides/python-net)