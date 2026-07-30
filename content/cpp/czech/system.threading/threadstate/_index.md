---
title: ThreadState
second_title: Aspose.Slides pro C++ – reference API
description: Stav vlákna.
type: docs
weight: 326
url: /cs/system.threading/threadstate/
---
## ThreadState výčet

Stav vlákna.

```cpp
enum ThreadState
```

### Hodnoty

| Název | Hodnota | Popis |
| --- | --- | --- |
| Running | 0 | [Thread](../thread/) běží. |
| StopRequested | 1 | [Thread](../thread/) zastavení je požadováno. |
| SuspendRequested | 2 | [Thread](../thread/) pozastavení je požadováno. |
| Background | 4 | Vlákno je spuštěno na pozadí. |
| Unstarted | 8 | [Thread](../thread/) není spuštěn. |
| Stopped | 16 | [Thread](../thread/) je zastaven. |
| WaitSleepJoin | 32 | [Thread](../thread/) čeká na připojení. |
| Suspended | 64 | [Thread](../thread/) je pozastaven. |
| AbortRequested | 128 | [Thread](../thread/) zrušení je požadováno. |
| Aborted | 256 | [Thread](../thread/) byl zrušen. |

## Viz také

* Jmenný prostor [System::Threading](../)
* Knihovna [Aspose.Slides](../../)