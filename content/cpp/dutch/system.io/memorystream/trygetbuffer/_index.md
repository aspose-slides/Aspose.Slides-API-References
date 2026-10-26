---
title: TryGetBuffer()
second_title: Aspose.Slides voor C++ API-referentie
description: Retourneert de array van ongetekende bytes waaruit deze stream is gemaakt.
type: docs
weight: 170
url: /nl/system.io/memorystream/trygetbuffer/
---
## MemoryStream::TryGetBuffer(ArraySegment\<uint8_t\>\&) method

Retourneert de array van ongetekende bytes waaruit deze stream is gemaakt.

```cpp
bool System::IO::MemoryStream::TryGetBuffer(ArraySegment<uint8_t> &buffer)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| buffer | [ArraySegment](../../../system/arraysegment/)\<**uint8_t**\>\& | byte-array - out-parameter. Wanneer deze methode true retourneert, het byte-arraysegment waaruit deze stream is gemaakt; wanneer deze methode false retourneert, wordt deze parameter op default gezet. |

### Retourwaarde

True als de conversie is geslaagd.

## Zie ook

* Class [ArraySegment](../../../system/arraysegment/)
* Class [MemoryStream](../)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)