---
title: InterruptionToken class
second_title: Riferimento API Aspose.Slides per Python via .NET
description: 
type: docs
url: /it/aspose.slides/interruptiontoken/
---
## InterruptionToken classe

Questa classe rappresenta il token da utilizzare per segnalare ai task a lunga esecuzione se è stata richiesta l'interruzione.

Il tipo InterruptionToken espone i seguenti membri:

## Proprietà

| Proprietà | Descrizione |
| :- | :- |
| [`none`](/slides/python-net/it/aspose.slides/interruptiontoken/none/) | Rappresenta un token di interruzione vuoto.<br/>            Le operazioni a lunga esecuzione non verranno mai interrotte tramite [`InterruptionTokenSource.interrupt`](/slides/python-net/it/aspose.slides/interruptiontokensource/interrupt)<br/>            quando si utilizza questo token. |
| [`is_interruption_requested`](/slides/python-net/it/aspose.slides/interruptiontoken/is_interruption_requested/) | Restituisce **bool**.true se l'interruzione è stata richiesta. |

## Metodi

| Metodo | Descrizione |
| :- | :- |
| [`throw_if_interruption_requested(self)`](/slides/python-net/it/aspose.slides/interruptiontoken/throw_if_interruption_requested/#) | Lancia un OperationCanceledException se<br/>            l'interruzione è stata richiesta. |


### Vedi anche
* modulo [`aspose.slides`](/slides/python-net/it/aspose.slides)
* libreria [`Aspose.Slides`](/slides/python-net)