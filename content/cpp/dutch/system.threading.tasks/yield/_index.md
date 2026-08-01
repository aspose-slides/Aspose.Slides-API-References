---
title: Yield()
second_title: Aspose.Slides voor C++ API-referentie
description: Maakt een awaitable taak die asynchroon teruggeeft aan de huidige context wanneer er op gewacht wordt.
type: docs
weight: 222
url: /nl/system.threading.tasks/yield/
---
## System::Threading::Tasks::Yield() functie

Maakt een awaitable taak die asynchroon teruggeeft aan de huidige context wanneer er op gewacht wordt.

```cpp
Runtime::CompilerServices::YieldAwaitable System::Threading::Tasks::Yield()
```

### Returnwaarde

Een YieldAwaitable die kan worden awaited om controle af te staan.
## Opmerkingen


Deze methode is handig om een asynchrone methode te dwingen controle af te staan, zodat ander wachtend werk kan worden verwerkt voordat wordt voortgezet.
## Zie ook

* Klasse [YieldAwaitable](../../system.runtime.compilerservices/yieldawaitable/)
* Naamruimte [System::Threading::Tasks](../)
* Bibliotheek [Aspose.Slides](../../)