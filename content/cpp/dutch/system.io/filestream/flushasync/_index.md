---
title: FlushAsync()
second_title: Aspose.Slides voor C++ API-referentie
description: Verwijdert asynchroon alle buffers voor deze stream, zorgt ervoor dat gebufferde gegevens naar het onderliggende apparaat worden geschreven, en bewaakt annuleringsverzoeken.
type: docs
weight: 157
url: /nl/system.io/filestream/flushasync/
---
## FileStream::FlushAsync(const Threading::CancellationToken\&) methode

Verwijdert asynchroon alle buffers voor deze stroom, zorgt ervoor dat gebufferde gegevens naar het onderliggende apparaat worden geschreven, en bewaakt annuleringsverzoeken.

```cpp
TaskPtr System::IO::FileStream::FlushAsync(const Threading::CancellationToken &cancellationToken) override
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| cancellationToken | const [Threading::CancellationToken](../../../system.threading/cancellationtoken/)\& | Het token om annuleringsverzoeken te bewaken. |

### Retourwaarde

Een taak die de asynchrone flush-operatie vertegenwoordigt.

## Zie ook

* Typedef [TaskPtr](../../../system/taskptr/)
* Klasse [CancellationToken](../../../system.threading/cancellationtoken/)
* Klasse [FileStream](../)
* Namespace [System::IO](../../)
* Bibliotheek [Aspose.Slides](../../../)