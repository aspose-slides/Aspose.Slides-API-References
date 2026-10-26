---
title: IAudio class
second_title: Aspose.Slides per Python via .NET Riferimento API
description: 
type: docs
url: /it/aspose.slides/iaudio/
---
## IAudio classe

Rappresenta un file audio incorporato.

Il tipo IAudio espone i seguenti membri:

## Proprietà

| Proprietà | Descrizione |
| :- | :- |
| [`content_type`](/slides/python-net/it/aspose.slides/iaudio/content_type/) | Restituisce un tipo MIME di un audio, codificato in [`IAudio.binary_data`](/slides/python-net/it/aspose.slides/iaudio/binary_data).<br/>            Solo lettura **str**. |
| [`binary_data`](/slides/python-net/it/aspose.slides/iaudio/binary_data/) | Restituisce la copia dei dati di un audio. In caso di grande quantità di dati, considerare <br/>            l'uso del metodo [`IAudio.get_stream`](/slides/python-net/it/aspose.slides/iaudio/get_stream) per evitare il caricamento non necessario dei dati dell'audio<br/>            in memoria o anche OutOfMemoryException.<br/>            Solo lettura **int**[]. |

## Metodi

| Metodo | Descrizione |
| :- | :- |
| [`get_stream(self)`](/slides/python-net/it/aspose.slides/iaudio/get_stream/#) | Restituisce Stream stream per la lettura.<br/>            Usare 'using' o chiudere lo stream dopo l'uso. |


### Vedi anche
* modulo [`aspose.slides`](/slides/python-net/it/aspose.slides)
* libreria [`Aspose.Slides`](/slides/python-net)