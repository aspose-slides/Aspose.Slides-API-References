---
title: IStreamWrapper class
second_title: Riferimento API Aspose.Slides per Python via .NET
description: 
type: docs
url: /it/aspose.slides/istreamwrapper/
---
## IStreamWrapper classe

Wrapper Aspose.IO.Stream per interfaccia COM.

Il tipo IStreamWrapper espone i seguenti membri:

## Proprietà

| Property | Description |
| :- | :- |
| [`stream`](/slides/python-net/it/aspose.slides/istreamwrapper/stream/) | Recupera un flusso.<br/>            sola lettura **io.RawIOBase**. |
| [`can_read`](/slides/python-net/it/aspose.slides/istreamwrapper/can_read/) | Recupera un valore che indica se il flusso corrente supporta la lettura.<br/>            sola lettura **bool**. |
| [`can_seek`](/slides/python-net/it/aspose.slides/istreamwrapper/can_seek/) | Recupera un valore che indica se il flusso corrente supporta la ricerca.<br/>            sola lettura **bool**. |
| [`can_write`](/slides/python-net/it/aspose.slides/istreamwrapper/can_write/) | Recupera un valore che indica se il flusso corrente supporta la scrittura.<br/>            sola lettura **bool**. |
| [`length`](/slides/python-net/it/aspose.slides/istreamwrapper/length/) | Recupera la lunghezza in byte del flusso.<br/>            sola lettura **int**. |
| [`position`](/slides/python-net/it/aspose.slides/istreamwrapper/position/) | Recupera la posizione all'interno del flusso corrente.<br/>            sola lettura **int**. |

## Metodi

| Method | Description |
| :- | :- |
| [`close(self)`](/slides/python-net/it/aspose.slides/istreamwrapper/close/#) | Chiude il flusso corrente e rilascia tutte le risorse. |
| [`flush(self)`](/slides/python-net/it/aspose.slides/istreamwrapper/flush/#) | Svuota tutti i buffer per questo flusso e fa sì che i dati in buffer vengano scritti sul dispositivo sottostante. |
| [`read(self, buffer, offset, count)`](/slides/python-net/it/aspose.slides/istreamwrapper/read/#bytes-int-int) | Legge una sequenza di byte dal flusso corrente e avanza la posizione nel flusso del numero di byte letti. |
| [`read_byte(self)`](/slides/python-net/it/aspose.slides/istreamwrapper/read_byte/#) | Legge un byte dal flusso e avanza la posizione nel flusso di un byte, oppure restituisce -1 se è alla fine del flusso. |
| [`seek(self, offset, origin)`](/slides/python-net/it/aspose.slides/istreamwrapper/seek/#int-systemioseekorigin) | Imposta la posizione all'interno del flusso corrente |
| [`write(self, buffer, offset, count)`](/slides/python-net/it/aspose.slides/istreamwrapper/write/#bytes-int-int) | scrive una sequenza di byte nel flusso corrente e avanza la posizione corrente in questo flusso del numero di byte scritti. |
| [`write_byte(self, value)`](/slides/python-net/it/aspose.slides/istreamwrapper/write_byte/#int) | Scrive un byte nella posizione corrente del flusso e avanza la posizione nel flusso di un byte. |

### Vedi anche
* modulo [`aspose.slides`](/slides/python-net/it/aspose.slides)
* libreria [`Aspose.Slides`](/slides/python-net)