---
title: InterruptionToken class
second_title: Aspose.Slides dla Pythona za pośrednictwem referencji API .NET
description:
type: docs
url: /pl/aspose.slides/interruptiontoken/
---
## InterruptionToken klasa

Ta klasa reprezentuje token używany do sygnalizowania długotrwałym zadaniom, czy przerwanie zostało żądane.

Typ InterruptionToken udostępnia następujące elementy:

## Właściwości

| Property | Opis |
| :- | :- |
| [`none`](/slides/python-net/pl/aspose.slides/interruptiontoken/none/) | Reprezentuje pusty token przerwania.<br/>            Operacje długotrwałe nigdy nie będą przerwane za pomocą [`InterruptionTokenSource.interrupt`](/slides/python-net/pl/aspose.slides/interruptiontokensource/interrupt)<br/>            przy użyciu tego tokenu. |
| [`is_interruption_requested`](/slides/python-net/pl/aspose.slides/interruptiontoken/is_interruption_requested/) | Zwraca **bool**.true jeśli przerwanie zostało żądane. |

## Metody

| Method | Opis |
| :- | :- |
| [`throw_if_interruption_requested(self)`](/slides/python-net/pl/aspose.slides/interruptiontoken/throw_if_interruption_requested/#) | Rzuca wyjątek OperationCanceledException, jeśli<br/>            przerwanie zostało żądane. |

### Zobacz także
* moduł [`aspose.slides`](/slides/python-net/pl/aspose.slides)
* biblioteka [`Aspose.Slides`](/slides/python-net)