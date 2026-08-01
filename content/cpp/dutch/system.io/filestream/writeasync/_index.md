---
title: WriteAsync()
second_title: Aspose.Slides voor C++ API-referentie
description: Schrijft asynchroon een reeks bytes naar de huidige stream, verplaatst de huidige positie in deze stream met het aantal geschreven bytes, en houdt annuleringsverzoeken in de gaten.
type: docs
weight: 261
url: /nl/system.io/filestream/writeasync/
---
## FileStream::WriteAsync(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t, const Threading::CancellationToken\&) method

Schrijft asynchroon een reeks bytes naar de huidige stream, verplaatst de huidige positie in deze stream met het aantal geschreven bytes, en houdt annuleringsverzoeken in de gaten.

```cpp
TaskPtr System::IO::FileStream::WriteAsync(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count, const Threading::CancellationToken &cancellationToken) override
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | De array die de te schrijven bytes bevat. |
| offset | **int32_t** | Een 0-gebaseerde index van het element in **buffer** waarop het te schrijven subbereik begint. |
| count | **int32_t** | Het aantal elementen in het te schrijven subbereik. |
| cancellationToken | const [Threading::CancellationToken](../../../system.threading/cancellationtoken/)\& | Het token om annuleringsverzoeken te monitoren. |

### Retourwaarde

Een taak die de asynchrone schrijfoperatie vertegenwoordigt.

## Zie ook

* Typedef [TaskPtr](../../../system/taskptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Klasse [CancellationToken](../../../system.threading/cancellationtoken/)
* Klasse [FileStream](../)
* Naamruimte [System::IO](../../)
* Bibliotheek [Aspose.Slides](../../../)