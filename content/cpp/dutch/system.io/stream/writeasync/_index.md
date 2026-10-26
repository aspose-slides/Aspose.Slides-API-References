---
title: WriteAsync()
second_title: Aspose.Slides voor C++ API-referentie
description: Schrijft asynchroon een reeks bytes naar de huidige stream, verplaatst de huidige positie in deze stream met het aantal geschreven bytes, en bewaakt annuleringsverzoeken.
type: docs
weight: 66
url: /nl/system.io/stream/writeasync/
---
## Stream::WriteAsync(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t, const Threading::CancellationToken\&) methode

Schrijft asynchroon een reeks bytes naar de huidige stream, verplaatst de huidige positie in deze stream met het aantal geschreven bytes, en bewaakt annuleringsverzoeken.

```cpp
virtual TaskPtr System::IO::Stream::WriteAsync(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count, const Threading::CancellationToken &cancellationToken)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | De array die de te schrijven bytes bevat. |
| offset | **int32_t** | Een 0-gebaseerde index van het elemnet in **buffer** waarop het subbereik dat geschreven moet worden begint. |
| count | **int32_t** | Het aantal elementen in het subbereik dat geschreven moet worden. |
| cancellationToken | const [Threading::CancellationToken](../../../system.threading/cancellationtoken/)\& | Het token om annuleringsverzoeken te bewaken. |

### Retourwaarde

Een taak die de asynchrone schrijfoperatie vertegenwoordigt.

## Stream::WriteAsync(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) methode

Schrijft asynchroon een reeks bytes naar de huidige stream, verplaatst de huidige positie in deze stream met het aantal geschreven bytes, en bewaakt annuleringsverzoeken.

```cpp
TaskPtr System::IO::Stream::WriteAsync(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | De array die de te schrijven bytes bevat. |
| offset | **int32_t** | Een 0-gebaseerde index van het elemnet in **buffer** waarop het subbereik dat geschreven moet worden begint. |
| count | **int32_t** | Het aantal elementen in het subbereik dat geschreven moet worden. |

### Retourwaarde

Een taak die de asynchrone schrijfoperatie vertegenwoordigt.

## Zie ook

* Typedef [TaskPtr](../../../system/taskptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Klasse [CancellationToken](../../../system.threading/cancellationtoken/)
* Klasse [Stream](../)
* Namespace [System::IO](../../)
* Bibliotheek [Aspose.Slides](../../../)