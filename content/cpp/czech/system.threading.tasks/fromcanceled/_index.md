---
title: FromCanceled()
second_title: Aspose.Slides pro C++ API reference
description: Vytvoří úlohu, která byla dokončena kvůli zrušení se zadaným tokenem.
type: docs
weight: 118
url: /cs/system.threading.tasks/fromcanceled/
---
## System::Threading::Tasks::FromCanceled(const CancellationToken\&) funkce

Vytvoří úlohu, která byla dokončena z důvodu zrušení se zadaným tokenem.

```cpp
TaskPtr System::Threading::Tasks::FromCanceled(const CancellationToken &cancellationToken)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| cancellationToken | const [CancellationToken](../../system.threading/cancellationtoken/)\& | Token pro zrušení, který způsobil zrušení úlohy. |

### Návratová hodnota

Zrušená úloha.

## Viz také

* Typedef [TaskPtr](../../system/taskptr/)
* Třída [CancellationToken](../../system.threading/cancellationtoken/)
* Jmenný prostor [System::Threading::Tasks](../)
* Knihovna [Aspose.Slides](../../)