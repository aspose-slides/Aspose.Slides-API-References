---
title: Delay()
second_title: Aspose.Slides pro C++ – referenční příručka API
description: Vytvoří úlohu, která se dokončí po časovém zpoždění.
type: docs
weight: 105
url: /cs/system.threading.tasks/delay/
---
## System::Threading::Tasks::Delay(int32_t) funkce

Vytvoří úlohu, která se dokončí po časovém zpoždění.

```cpp
TaskPtr System::Threading::Tasks::Delay(int32_t millisecondsDelay)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| millisecondsDelay | **int32_t** | Počet milisekund, po které se má čekat před dokončením vrácené úlohy, nebo -1 pro čekání neurčitě. |

### Návratová hodnota

Úloha, která představuje časové zpoždění.

## System::Threading::Tasks::Delay(int32_t, const CancellationToken\&) funkce

Vytvoří úlohu, která se dokončí po časovém zpoždění a může být zrušena.

```cpp
TaskPtr System::Threading::Tasks::Delay(int32_t millisecondsDelay, const CancellationToken &cancellationToken)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| millisecondsDelay | **int32_t** | Počet milisekund, po které se má čekat před dokončením vrácené úlohy, nebo -1 pro čekání neurčitě. |
| cancellationToken | const [CancellationToken](../../system.threading/cancellationtoken/)\& | Zrušovací token, který lze použít ke zrušení zpoždění. |

### Návratová hodnota

Úloha, která představuje časové zpoždění.

## Viz také

* Typedef [TaskPtr](../../system/taskptr/)
* Třída [CancellationToken](../../system.threading/cancellationtoken/)
* Jmenný prostor [System::Threading::Tasks](../)
* Knihovna [Aspose.Slides](../../)