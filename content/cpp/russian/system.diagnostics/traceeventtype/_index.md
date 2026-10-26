---
title: TraceEventType
second_title: Справочник API Aspose.Slides для C++
description: Определяет тип события, которое вызвало трассировку.
type: docs
weight: 157
url: /ru/system.diagnostics/traceeventtype/
---
## TraceEventType enum

Определяет тип события, которое вызвало трассировку.

```cpp
enum class TraceEventType
```

### Значения

| Имя | Значение | Описание |
| --- | --- | --- |
| Critical | 1 | Фатальная ошибка или сбой приложения. |
| Error | 2 | Восстанавливаемая ошибка. |
| Warning | 4 | Некритическая проблема. |
| Information | 8 | Информационное сообщение. |
| Verbose | 16 | Трассировка отладки. |
| Start | 256 | Начало логической операции. |
| Stop | 512 | Завершение логической операции. |
| Suspend | 1024 | Приостановка логической операции. |
| Resume | 2048 | Возобновление логической операции. |
| Transfer | 4096 | Изменение идентичности корреляции. |

## См. также

* Namespace [System::Diagnostics](../)
* Library [Aspose.Slides](../../)