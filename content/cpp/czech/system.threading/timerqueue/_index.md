---
title: TimerQueue
second_title: Aspose.Slides pro API referenci C++
description: Fronta, která zpracovává objekty Timer. Jedná se pouze o implementaci. Objektům Timer se tam registrují samy, nemusíte tak učinit, abyste je používali - použijte místo toho API třídy Timer. Jedná se o typ singleton s řízením paměti prováděným přístupovou funkcí (funkcemi). Neměli byste vytvářet jeho instance přímo.
type: docs
weight: 261
url: /cs/system.threading/timerqueue/
---
## TimerQueue třída


Fronta, která zpracovává objekty [Timer](../timer/). Jedná se pouze o implementaci. [Timer](../timer/) objects register there by themselves, you don't have to do so to use them - use [Timer](../timer/) class API instead. This is a singleton type with memory management done by access function(s). You should never create instances of it directly.

```cpp
class TimerQueue
```

## Metody

| Metoda | Popis |
| --- | --- |
| **bool** [Add](./add/)([Timer](../timer/) *) | Zaregistruje časovač do fronty. |
| **bool** [Delete](./delete/)([Timer](../timer/) *) | Odstraní časovač z fronty. |
| static [TimerQueue](./)\& [GetInstance](./getinstance/)() | Implementační singleton. |
| static void [JoinWorkerThread](./joinworkerthread/)() | Připojí pracovní vlákno. Čeká nekonečně, pokud je to požadováno. |
| void [operator=](./operator_equal/)(const [TimerQueue](./)\&) | Bez kopírování. |
|  [TimerQueue](./timerqueue/)(const [TimerQueue](./)\&) | Bez kopírování. |

## Viz také

* Jmenný prostor [System::Threading](../)
* Knihovna [Aspose.Slides](../../)