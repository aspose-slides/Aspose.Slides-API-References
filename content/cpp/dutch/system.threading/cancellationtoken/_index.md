---
title: CancellationToken
second_title: Aspose.Slides voor C++ API-referentie
description: Zendt een melding door dat bewerkingen geannuleerd moeten worden. Deze klasse biedt een mechanisme voor coöperatieve annulering tussen threads, waardoor één thread de andere kan informeren dat een bewerking geannuleerd moet worden.
type: docs
weight: 14
url: /nl/system.threading/cancellationtoken/
---
## CancellationToken klasse

Zendt een melding door dat bewerkingen geannuleerd moeten worden. Deze klasse biedt een mechanisme voor coöperatieve annulering tussen threads, waardoor één thread de andere kan informeren dat een bewerking geannuleerd moet worden.

```cpp
class CancellationToken : public System::Details::BoxableObjectBase
```

## Methoden

| Method | Description |
| --- | --- |
|  [CancellationToken](./cancellationtoken/)() | Standaardconstructor. |
| **bool** [get_CanBeCanceled](./get_canbecanceled/)() const | Bepaalt of dit token in de geannuleerde status kan verkeren. |
| **bool** [get_IsCancellationRequested](./get_iscancellationrequested/)() const | Bepaalt of annulering voor dit token is aangevraagd. |
| static [CancellationToken](./) [get_None](./get_none/)() | Retourneert een lege [System::Threading::CancellationToken](./) waarde. |
| [CancellationTokenRegistration](../cancellationtokenregistration/) [Register](./register/)(const [Action](../../system/action/)<>\&) const | Registreert een callback die wordt aangeroepen wanneer annulering wordt aangevraagd. |
| void [ThrowIfCancellationRequested](./throwifcancellationrequested/)() const | Gooit een OperationCanceledException als annulering is aangevraagd. |

## Opmerkingen

Een [CancellationToken](./) kan alleen worden geannuleerd via de gekoppelde [CancellationTokenSource](../cancellationtokensource/). 

## Zie ook

* Naamruimte [System::Threading](../)
* Bibliotheek [Aspose.Slides](../../)