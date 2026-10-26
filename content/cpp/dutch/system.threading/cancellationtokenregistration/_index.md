---
title: CancellationTokenRegistration
second_title: Aspose.Slides voor C++ API-referentie
description: Stelt een registratie voor een annulerings-tokencallback voor.
type: docs
weight: 27
url: /nl/system.threading/cancellationtokenregistration/
---
## CancellationTokenRegistration klasse

Stelt een registratie voor een annulerings-tokencallback voor.

```cpp
class CancellationTokenRegistration
```

## Methoden

| Methode | Beschrijving |
| --- | --- |
| void [Dispose](./dispose/)() | Verwijdert de registratie en verwijdert de callback uit de gekoppelde [CancellationTokenSource](../cancellationtokensource/). Na het aanroepen van deze methode zal de geregistreerde callback niet meer worden aangeroepen wanneer de gekoppelde [CancellationTokenSource](../cancellationtokensource/) wordt geannuleerd. |

## Opmerkingen

Deze klasse maakt het mogelijk een callback van een annulerings-token af te melden. Wanneer verwijderd, verwijdert het de callback uit de gekoppelde [CancellationTokenSource](../cancellationtokensource/). Deze klasse mag niet direct worden gemaakt - hij wordt geretourneerd door [CancellationToken](../cancellationtoken/) registratie-methoden.

## Zie ook

* Namespace [System::Threading](../)
* Bibliotheek [Aspose.Slides](../../)