---
title: Delay()
second_title: Aspose.Slides voor C++ API-referentie
description: Maakt een taak die wordt voltooid na een tijdvertraging.
type: docs
weight: 105
url: /nl/system.threading.tasks/delay/
---
## System::Threading::Tasks::Delay(int32_t) functie

Maakt een taak die wordt voltooid na een tijdvertraging.

```cpp
TaskPtr System::Threading::Tasks::Delay(int32_t millisecondsDelay)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| millisecondsDelay | **int32_t** | Het aantal milliseconden om te wachten voordat de geretourneerde taak wordt voltooid, of -1 om onbeperkt te wachten. |

### Retourwaarde

Een taak die de tijdvertraging vertegenwoordigt.

## System::Threading::Tasks::Delay(int32_t, const CancellationToken\&) functie

Maakt een taak die wordt voltooid na een tijdvertraging en kan worden geannuleerd.

```cpp
TaskPtr System::Threading::Tasks::Delay(int32_t millisecondsDelay, const CancellationToken &cancellationToken)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| millisecondsDelay | **int32_t** | Het aantal milliseconden om te wachten voordat de geretourneerde taak wordt voltooid, of -1 om onbeperkt te wachten. |
| cancellationToken | const [CancellationToken](../../system.threading/cancellationtoken/)\& | Het annulerings-token dat kan worden gebruikt om de vertraging te annuleren. |

### Retourwaarde

Een taak die de tijdvertraging vertegenwoordigt.

## Zie ook

* Typedef [TaskPtr](../../system/taskptr/)
* Klasse [CancellationToken](../../system.threading/cancellationtoken/)
* Namespace [System::Threading::Tasks](../)
* Bibliotheek [Aspose.Slides](../../)