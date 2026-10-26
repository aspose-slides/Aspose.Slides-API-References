---
title: TimerQueue
second_title: Aspose.Slides voor C++ API-referentie
description: Wachtrij die Timer objecten afhandelt. Dit is slechts een implementatie. Timer objecten registreren zich daar zelf, je hoeft dat niet te doen om ze te gebruiken - gebruik in plaats daarvan de Timer klasse API. Dit is een singletontype met geheugemanagement uitgevoerd door toegangsfunctie(s). Je moet nooit direct instanties ervan maken.
type: docs
weight: 261
url: /nl/system.threading/timerqueue/
---
## TimerQueue klasse

Wachtrij die [Timer](../timer/) objecten afhandelt. Dit is slechts een implementatie. [Timer](../timer/) objecten registreren zich daar zelf, je hoeft dat niet te doen om ze te gebruiken - gebruik in plaats daarvan de [Timer](../timer/) klasse API. Dit is een singletontype met geheugemanagement uitgevoerd door toegangsfunctie(s). Je moet nooit direct instanties ervan maken.

```cpp
class TimerQueue
```

## Methoden

| Method | Description |
| --- | --- |
| **bool** [Add](./add/)([Timer](../timer/) *) | Registreert timer in de wachtrij. |
| **bool** [Delete](./delete/)([Timer](../timer/) *) | Verwijdert timer uit de wachtrij. |
| static [TimerQueue](./)\& [GetInstance](./getinstance/)() | Implementatie singleton. |
| static void [JoinWorkerThread](./joinworkerthread/)() | Voegt zich bij werkthread. Wacht oneindig indien nodig. |
| void [operator=](./operator_equal/)(const [TimerQueue](./)\&) | Geen kopiëren. |
|  [TimerQueue](./timerqueue/)(const [TimerQueue](./)\&) | Geen kopiëren. |
## Zie ook

* Naamruimte [System::Threading](../)
* Bibliotheek [Aspose.Slides](../../)