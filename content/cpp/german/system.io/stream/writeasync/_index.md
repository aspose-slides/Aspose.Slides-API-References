---
title: WriteAsync()
second_title: Aspose.Slides für C++ API-Referenz
description: Schreibt asynchron eine Sequenz von Bytes in den aktuellen Stream, erhöht die aktuelle Position in diesem Stream um die Anzahl der geschriebenen Bytes und überwacht Abbruchanforderungen.
type: docs
weight: 66
url: /de/system.io/stream/writeasync/
---
## Stream::WriteAsync(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t, const Threading::CancellationToken\&) Methode

Schreibt asynchron eine Sequenz von Bytes in den aktuellen Stream, erhöht die aktuelle Position in diesem Stream um die Anzahl der geschriebenen Bytes und überwacht Abbruchanforderungen.

```cpp
virtual TaskPtr System::IO::Stream::WriteAsync(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count, const Threading::CancellationToken &cancellationToken)
```

### Argumente

| Parameter | Type | Beschreibung |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Das Array, das die zu schreibenden Bytes enthält. |
| offset | **int32_t** | Ein 0-basierter Index des Elements in **buffer**, an dem der zu schreibende Teilbereich beginnt. |
| count | **int32_t** | Die Anzahl der Elemente im zu schreibenden Teilbereich. |
| cancellationToken | const [Threading::CancellationToken](../../../system.threading/cancellationtoken/)\& | Das Token, das auf Abbruchanforderungen überwacht wird. |

### Rückgabewert

Eine Aufgabe, die den asynchronen Schreibvorgang repräsentiert.

## Stream::WriteAsync(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) Methode

Schreibt asynchron eine Sequenz von Bytes in den aktuellen Stream, erhöht die aktuelle Position in diesem Stream um die Anzahl der geschriebenen Bytes und überwacht Abbruchanforderungen.

```cpp
TaskPtr System::IO::Stream::WriteAsync(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count)
```

### Argumente

| Parameter | Type | Beschreibung |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Das Array, das die zu schreibenden Bytes enthält. |
| offset | **int32_t** | Ein 0-basierter Index des Elements in **buffer**, an dem der zu schreibende Teilbereich beginnt. |
| count | **int32_t** | Die Anzahl der Elemente im zu schreibenden Teilbereich. |

### Rückgabewert

Eine Aufgabe, die den asynchronen Schreibvorgang repräsentiert.

## Siehe auch

* Typedef [TaskPtr](../../../system/taskptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Klasse [CancellationToken](../../../system.threading/cancellationtoken/)
* Klasse [Stream](../)
* Namensraum [System::IO](../../)
* Bibliothek [Aspose.Slides](../../../)