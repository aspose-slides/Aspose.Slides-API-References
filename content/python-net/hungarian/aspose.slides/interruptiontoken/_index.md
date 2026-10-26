---
title: InterruptionToken class
second_title: Aspose.Slides a Pythonhoz .NET-en keresztül API referencia
description: 
type: docs
url: /hu/aspose.slides/interruptiontoken/
---
## InterruptionToken osztály

Ez az osztály azt a tokent reprezentálja, amelyet a hosszú futású feladatok megszakítási kérésének jelzésére használnak.

Az InterruptionToken típus a következő tagokat tartalmazza:

## Tulajdonságok

| Tulajdonság | Leírás |
| :- | :- |
| [`none`](/slides/python-net/hu/aspose.slides/interruptiontoken/none/) | Üres megszakítási tokent reprezentál.<br/>            Hosszú futású műveletek soha nem lesznek megszakítva a [`InterruptionTokenSource.interrupt`](/slides/python-net/hu/aspose.slides/interruptiontokensource/interrupt)<br/>            amikor ezt a tokent használják. |
| [`is_interruption_requested`](/slides/python-net/hu/aspose.slides/interruptiontoken/is_interruption_requested/) | Visszaad **bool**.true értéket, ha a megszakításra kérés történt. |

## Metódusok

| Metódus | Leírás |
| :- | :- |
| [`throw_if_interruption_requested(self)`](/slides/python-net/hu/aspose.slides/interruptiontoken/throw_if_interruption_requested/#) | OperationCanceledException kivételt dob, ha<br/>            megszakításra kérték. |

### Lásd még
* modul [`aspose.slides`](/slides/python-net/hu/aspose.slides)
* könyvtár [`Aspose.Slides`](/slides/python-net)