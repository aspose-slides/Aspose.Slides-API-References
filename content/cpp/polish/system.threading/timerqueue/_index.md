---
title: TimerQueue
second_title: Odwołanie API Aspose.Slides dla C++
description: Kolejka obsługująca obiekty Timer. To tylko implementacja. Obiekty Timer rejestrują się tam same, nie musisz tego robić, aby je używać – użyj API klasy Timer zamiast tego. Jest to typ singleton z zarządzaniem pamięcią realizowanym przez funkcję(e) dostępowe. Nigdy nie powinieneś tworzyć jego instancji bezpośrednio.
type: docs
weight: 261
url: /pl/system.threading/timerqueue/
---
## TimerQueue klasa

Kolejka obsługująca obiekty [Timer](../timer/). To tylko implementacja. [Timer](../timer/) obiekty rejestrują się tam same, nie musisz tego robić, aby je używać – użyj API klasy [Timer](../timer/) zamiast tego. Jest to typ singleton z zarządzaniem pamięcią realizowanym przez funkcję(e) dostępowe. Nigdy nie powinieneś tworzyć jego instancji bezpośrednio.

```cpp
class TimerQueue
```

## Metody

| Metoda | Opis |
| --- | --- |
| **bool** [Add](./add/)([Timer](../timer/) *) | Rejestruje timer w kolejce. |
| **bool** [Delete](./delete/)([Timer](../timer/) *) | Usuwa timer z kolejki. |
| static [TimerQueue](./)\& [GetInstance](./getinstance/)() | Singleton implementacji. |
| static void [JoinWorkerThread](./joinworkerthread/)() | Łączy wątek pracownika. Czeka w nieskończoność, jeśli jest to wymagane. |
| void [operator=](./operator_equal/)(const [TimerQueue](./)\&) | Brak kopiowania. |
|  [TimerQueue](./timerqueue/)(const [TimerQueue](./)\&) | Brak kopiowania. |
## Zobacz także

* Przestrzeń nazw [System::Threading](../)
* Biblioteka [Aspose.Slides](../../)