---
title: StreamWrapper class
second_title: Riferimento API Aspose.Slides per Python tramite .NET
description: 
type: docs
url: /it/aspose.slides/streamwrapper/
---
## StreamWrapper classe

Aspose.IO.Stream wrapper for COM interface.

The StreamWrapper type exposes the following members:

## Proprietà

| Property | Description |
| :- | :- |
| [`stream`](/slides/python-net/it/aspose.slides/streamwrapper/stream/) | Ottiene un flusso.<br/>            Sola lettura **io.RawIOBase**. |
| [`can_read`](/slides/python-net/it/aspose.slides/streamwrapper/can_read/) | Ottiene un valore che indica se il flusso corrente supporta la lettura.<br/>            Sola lettura **bool**. |
| [`can_seek`](/slides/python-net/it/aspose.slides/streamwrapper/can_seek/) | Ottiene un valore che indica se il flusso corrente supporta la ricerca.<br/>            Sola lettura **bool**. |
| [`can_write`](/slides/python-net/it/aspose.slides/streamwrapper/can_write/) | Ottiene un valore che indica se il flusso corrente supporta la scrittura.<br/>            Sola lettura **bool**. |
| [`length`](/slides/python-net/it/aspose.slides/streamwrapper/length/) | Ottiene la lunghezza in byte del flusso.<br/>            Sola lettura **int**. |
| [`position`](/slides/python-net/it/aspose.slides/streamwrapper/position/) | Ottiene o imposta la posizione nel flusso corrente.<br/>            Sola lettura **int**. |

## Metodi

| Method | Description |
| :- | :- |
| [`close(self)`](/slides/python-net/it/aspose.slides/streamwrapper/close/#) | Chiude il flusso corrente e rilascia tutte le risorse. |
| [`flush(self)`](/slides/python-net/it/aspose.slides/streamwrapper/flush/#) | Svuota tutti i buffer per questo flusso e fa sì che i dati memorizzati vengano scritti sul dispositivo sottostante. |
| [`read(self, buffer, offset, count)`](/slides/python-net/it/aspose.slides/streamwrapper/read/#bytes-int-int) | Legge una sequenza di byte dal flusso corrente e avanza la posizione nel flusso del numero di byte letti. |
| [`read_byte(self)`](/slides/python-net/it/aspose.slides/streamwrapper/read_byte/#) | Legge un byte dal flusso e avanza la posizione nel flusso di un byte, o restituisce -1 se è alla fine del flusso. |
| [`seek(self, offset, origin)`](/slides/python-net/it/aspose.slides/streamwrapper/seek/#int-systemioseekorigin) | Imposta la posizione nel flusso corrente |
| [`write(self, buffer, offset, count)`](/slides/python-net/it/aspose.slides/streamwrapper/write/#bytes-int-int) | scrive una sequenza di byte nel flusso corrente e avanza la posizione corrente in questo flusso del numero di byte scritti. |
| [`write_byte(self, value)`](/slides/python-net/it/aspose.slides/streamwrapper/write_byte/#int) | Scrive un byte nella posizione corrente del flusso e avanza la posizione nel flusso di un byte. |


### Vedi anche
* modulo [`aspose.slides`](/slides/python-net/it/aspose.slides)
* libreria [`Aspose.Slides`](/slides/python-net)