---
title: FlushAsync()
second_title: Aspose.Slides voor C++ API-referentie
description: Leegt asynchroon alle buffers voor deze stream, zorgt ervoor dat alle gebufferde gegevens naar het onderliggende apparaat worden geschreven, en monitort annuleringsverzoeken.
type: docs
weight: 118
url: /nl/system.io/stream/flushasync/
---
## Stream::FlushAsync(const Threading::CancellationToken\&) methode


Leegt asynchroon alle buffers voor deze stream, zorgt ervoor dat alle gebufferde gegevens naar het onderliggende apparaat worden geschreven, en monitort annuleringsverzoeken.

```cpp
virtual TaskPtr System::IO::Stream::FlushAsync(const Threading::CancellationToken &cancellationToken)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| cancellationToken | const [Threading::CancellationToken](../../../system.threading/cancellationtoken/)\& | Het token om annuleringsverzoeken te monitoren. |

### Retourwaarde

Een taak die de asynchrone flush-operatie vertegenwoordigt.

## Stream::FlushAsync() methode


Leegt asynchroon alle buffers voor deze stream, zorgt ervoor dat alle gebufferde gegevens naar het onderliggende apparaat worden geschreven, en monitort annuleringsverzoeken.

```cpp
TaskPtr System::IO::Stream::FlushAsync()
```


### Retourwaarde

Een taak die de asynchrone flush-operatie vertegenwoordigt.

## Zie ook

* Typedef [TaskPtr](../../../system/taskptr/)
* Klasse [CancellationToken](../../../system.threading/cancellationtoken/)
* Klasse [Stream](../)
* Namespace [System::IO](../../)
* Bibliotheek [Aspose.Slides](../../../)