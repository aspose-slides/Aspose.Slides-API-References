---
title: TimerQueue
second_title: Aspose.Slides för C++ API-referens
description: Kö som hanterar Timer-objekt. Detta är bara en implementation. Timer-objekt registrerar sig själva där, du behöver inte göra det för att använda dem – använd Timer-klassens API istället. Detta är en singleton-typ med minneshantering som sker via åtkomstfunktion(er). Du bör aldrig skapa instanser av den direkt.
type: docs
weight: 261
url: /sv/system.threading/timerqueue/
---
## TimerQueue klass

Kö som hanterar [Timer](../timer/)-objekt. Detta är bara en implementation. [Timer](../timer/)-objekt registrerar sig själva där, du behöver inte göra det för att använda dem - använd [Timer](../timer/) klass API istället. Detta är en singleton-typ med minneshantering som sker via åtkomstfunktion(er). Du bör aldrig skapa instanser av den direkt.

```cpp
class TimerQueue
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| **bool** [Add](./add/)([Timer](../timer/) *) | Registrerar timer i kö. |
| **bool** [Delete](./delete/)([Timer](../timer/) *) | Tar bort timer från kö. |
| static [TimerQueue](./)\& [GetInstance](./getinstance/)() | Implementationsingleton. |
| static void [JoinWorkerThread](./joinworkerthread/)() | Går med i arbets-tråden. Väntar oändligt om det behövs. |
| void [operator=](./operator_equal/)(const [TimerQueue](./)\&) | Ingen kopiering. |
|  [TimerQueue](./timerqueue/)(const [TimerQueue](./)\&) | Ingen kopiering. |

## Se även

* Namnrymd [System::Threading](../)
* Bibliotek [Aspose.Slides](../../)