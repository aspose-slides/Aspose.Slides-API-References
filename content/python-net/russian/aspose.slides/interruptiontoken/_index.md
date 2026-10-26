---
title: InterruptionToken class
second_title: Aspose.Slides для Python через .NET справочник API
description: 
type: docs
url: /ru/aspose.slides/interruptiontoken/
---
## InterruptionToken класс

Этот класс представляет токен, используемый для сигнализации длительным задачам о том, запрошено ли прерывание.

Тип InterruptionToken раскрывает следующие члены:

## Свойства

| Свойство | Описание |
| :- | :- |
| [`none`](/slides/python-net/ru/aspose.slides/interruptiontoken/none/) | Представляет пустой токен прерывания.<br/>            Длительные операции никогда не будут прерваны через [`InterruptionTokenSource.interrupt`](/slides/python-net/ru/aspose.slides/interruptiontokensource/interrupt)<br/>            при использовании этого токена. |
| [`is_interruption_requested`](/slides/python-net/ru/aspose.slides/interruptiontoken/is_interruption_requested/) | Возвращает **bool**.true если прерывание было запрошено. |

## Методы

| Метод | Описание |
| :- | :- |
| [`throw_if_interruption_requested(self)`](/slides/python-net/ru/aspose.slides/interruptiontoken/throw_if_interruption_requested/#) | Выбрасывает OperationCanceledException, если<br/>            прерывание было запрошено. |

### См. также
* модуль [`aspose.slides`](/slides/python-net/ru/aspose.slides)
* библиотека [`Aspose.Slides`](/slides/python-net)