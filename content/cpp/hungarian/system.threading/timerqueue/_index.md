---
title: TimerQueue
second_title: Aspose.Slides C++ API referenciája
description: Sor, amely Timer objektumokat kezel. Ez csak egy megvalósítás. A Timer objektumok maguktól regisztrálják magukat, nem kell így tenni a használatukhoz - használja helyette a Timer osztály API-ját. Ez egy singleton típus, a memóriakezelést hozzáférési függvény(ek) végzik. Soha ne hozzon létre közvetlenül példányokat ebből.
type: docs
weight: 261
url: /hu/system.threading/timerqueue/
---
## TimerQueue osztály

Queue that handles [Timer](../timer/) objects. This is just an implementation. [Timer](../timer/) objects register there by themselves, you don't have to do so to use them - use [Timer](../timer/) osztály API instead. This is a singleton típus with memory management done by access function(s). You should never create instances of it directly.

```cpp
class TimerQueue
```

## Metódusok

| Metódus | Leírás |
| --- | --- |
| **bool** [Add](./add/)([Timer](../timer/) *) | Regisztrál egy időzítőt a sorba. |
| **bool** [Delete](./delete/)([Timer](../timer/) *) | Törli az időzítőt a sorból. |
| static [TimerQueue](./)\& [GetInstance](./getinstance/)() | Implementációs singleton. |
| static void [JoinWorkerThread](./joinworkerthread/)() | Csatlakozik a munkaszálhoz. Szükség esetén végtelenül vár. |
| void [operator=](./operator_equal/)(const [TimerQueue](./)\&) | Nincs másolás. |
|  [TimerQueue](./timerqueue/)(const [TimerQueue](./)\&) | Nincs másolás. |

## Lásd még

* Névterület [System::Threading](../)
* Könyvtár [Aspose.Slides](../../)