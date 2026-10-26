---
title: Delay()
second_title: Aspose.Slides för C++ API-referens
description: Skapar en uppgift som slutförs efter en tidsfördröjning.
type: docs
weight: 105
url: /sv/system.threading.tasks/delay/
---
## System::Threading::Tasks::Delay(int32_t) function


Skapar en uppgift som slutförs efter en tidsfördröjning.

```cpp
TaskPtr System::Threading::Tasks::Delay(int32_t millisecondsDelay)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| millisecondsDelay | **int32_t** | Antalet millisekunder att vänta innan den returnerade uppgiften slutförs, eller -1 för att vänta på obestämd tid. |

### Returvärde

En uppgift som representerar tidsfördröjningen.

## System::Threading::Tasks::Delay(int32_t, const CancellationToken\&) function


Skapar en uppgift som slutförs efter en tidsfördröjning och kan avbrytas.

```cpp
TaskPtr System::Threading::Tasks::Delay(int32_t millisecondsDelay, const CancellationToken &cancellationToken)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| millisecondsDelay | **int32_t** | Antalet millisekunder att vänta innan den returnerade uppgiften slutförs, eller -1 för att vänta på obestämd tid. |
| cancellationToken | const [CancellationToken](../../system.threading/cancellationtoken/)\& | Avbokningstoken som kan användas för att avbryta fördröjningen. |

### Returvärde

En uppgift som representerar tidsfördröjningen.

## Se även

* Typedef [TaskPtr](../../system/taskptr/)
* Klass [CancellationToken](../../system.threading/cancellationtoken/)
* Namnrymd [System::Threading::Tasks](../)
* Bibliotek [Aspose.Slides](../../)