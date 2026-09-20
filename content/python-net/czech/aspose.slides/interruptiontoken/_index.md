---
title: InterruptionToken class
second_title: Aspose.Slides pro Python přes .NET API referenci
description: 
type: docs
url: /cs/aspose.slides/interruptiontoken/
---
## InterruptionToken třída

Tato třída představuje token, který se používá k signalizaci dlouhodobých úloh, zda bylo požadováno přerušení.

Typ InterruptionToken uvádí následující členy:

## Vlastnosti

| Vlastnost | Popis |
| :- | :- |
| [`none`](/slides/python-net/cs/aspose.slides/interruptiontoken/none/) | Zastupuje prázdný token přerušení.<br/>            Dlouho běžící operace nebudou nikdy přerušeny pomocí [`InterruptionTokenSource.interrupt`](/slides/python-net/cs/aspose.slides/interruptiontokensource/interrupt)<br/>            při použití tohoto tokenu. |
| [`is_interruption_requested`](/slides/python-net/cs/aspose.slides/interruptiontoken/is_interruption_requested/) | Vrací **bool**.true pokud bylo požadováno přerušení. |

## Metody

| Metoda | Popis |
| :- | :- |
| [`throw_if_interruption_requested(self)`](/slides/python-net/cs/aspose.slides/interruptiontoken/throw_if_interruption_requested/#) | Vyvolá výjimku OperationCanceledException, pokud<br/>            bylo požadováno přerušení. |

### Viz také
* modul [`aspose.slides`](/slides/python-net/cs/aspose.slides)
* knihovna [`Aspose.Slides`](/slides/python-net)