---
title: TryGetBuffer()
second_title: Aspose.Slides für C++ API-Referenz
description: Gibt das Array von vorzeichenlosen Bytes zurück, aus dem dieser Stream erstellt wurde.
type: docs
weight: 170
url: /de/system.io/memorystream/trygetbuffer/
---
## MemoryStream::TryGetBuffer(ArraySegment\<uint8_t\>\&) Methode

Gibt das Array von vorzeichenlosen Bytes zurück, aus dem dieser Stream erstellt wurde.

```cpp
bool System::IO::MemoryStream::TryGetBuffer(ArraySegment<uint8_t> &buffer)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| buffer | [ArraySegment](../../../system/arraysegment/)\<**uint8_t**\>\& | Byte-Array - Ausgabewert. Wenn diese Methode true zurückgibt, ist das Byte-Array-Segment, aus dem dieser Stream erstellt wurde; wenn diese Methode false zurückgibt, wird dieser Parameter auf den Standardwert gesetzt. |

### Rückgabewert

True, wenn die Konvertierung erfolgreich war.

## Siehe auch

* Klasse [ArraySegment](../../../system/arraysegment/)
* Klasse [MemoryStream](../)
* Namensraum [System::IO](../../)
* Bibliothek [Aspose.Slides](../../../)