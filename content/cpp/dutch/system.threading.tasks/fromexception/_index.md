---
title: FromException()
second_title: Aspose.Slides voor C++ API-referentie
description: Maakt een taak die is voltooid met een opgegeven uitzondering.
type: docs
weight: 131
url: /nl/system.threading.tasks/fromexception/
---
## System::Threading::Tasks::FromException(const Exception\&) functie


Maakt een taak die is voltooid met een opgegeven uitzondering.

```cpp
TaskPtr System::Threading::Tasks::FromException(const Exception &exception)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| exception | const [Exception](../../system/exception/)\& | De uitzondering waarmee de taak moet worden voltooid. |

### Retourwaarde

Een defecte taak.

## System::Threading::Tasks::FromException(const Exception\&) functie


Maakt een taak die is voltooid met een opgegeven uitzondering en resulttype.

```cpp
template<typename TResult> RTaskPtr<TResult> System::Threading::Tasks::FromException(const Exception &exception)
```


### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| TResult | Het type van het resultaat van de taak. |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| exception | const [Exception](../../system/exception/)\& | De uitzondering waarmee de taak moet worden voltooid. |

### Retourwaarde

Een defecte taak met het opgegeven resulttype.

## Zie ook

* Typedef [TaskPtr](../../system/taskptr/)
* Typedef [Exception](../../system/exception/)
* Typedef [RTaskPtr](../../system/rtaskptr/)
* Namespace [System::Threading::Tasks](../)
* Library [Aspose.Slides](../../)