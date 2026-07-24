---
title: ReadAsync()
second_title: Aspose.Slides für C++ API-Referenz
description: Liest asynchron eine Sequenz von Bytes aus dem aktuellen Stream, verschiebt die Position im Stream um die Anzahl der gelesenen Bytes und überwacht Abbruchanfragen.
type: docs
weight: 40
url: /de/system.io/stream/readasync/
---
## Stream::ReadAsync(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t, const Threading::CancellationToken\&) Methode

Liest asynchron eine Sequenz von Bytes aus dem aktuellen Stream, verschiebt die Position im Stream um die Anzahl der gelesenen Bytes und überwacht Abbruchanfragen.

```cpp
virtual RTaskPtr<int32_t> System::IO::Stream::ReadAsync(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count, const Threading::CancellationToken &cancellationToken)
```

### Argumente

| Parameter | Type | Beschreibung |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Das Byte-Array, in das die gelesenen Bytes geschrieben werden. |
| offset | **int32_t** | Eine 0-basierte Position in **buffer**, an der das Schreiben beginnen soll. |
| count | **int32_t** | Die Anzahl der zu lesenden Bytes. |
| cancellationToken | const [Threading::CancellationToken](../../../system.threading/cancellationtoken/)\& | Das Token, das auf Abbruchanfragen überwacht wird. |

### Rückgabewert

Ein Task, der die asynchrone Leseoperation repräsentiert. Der Wert des TResult-Parameters enthält die Gesamtzahl der in den Puffer gelesenen Bytes. Der Ergebniswert kann kleiner sein als die angeforderte Anzahl von Bytes, wenn die aktuell verfügbaren Bytes weniger als die angeforderte Menge sind, oder er kann 0 (null) sein, wenn das Ende des Streams erreicht wurde.

## Stream::ReadAsync(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) Methode

Liest asynchron eine Sequenz von Bytes aus dem aktuellen Stream, verschiebt die Position im Stream um die Anzahl der gelesenen Bytes und überwacht Abbruchanfragen.

```cpp
RTaskPtr<int32_t> System::IO::Stream::ReadAsync(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count)
```

### Argumente

| Parameter | Type | Beschreibung |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Das Byte-Array, in das die gelesenen Bytes geschrieben werden. |
| offset | **int32_t** | Eine 0-basierte Position in **buffer**, an der das Schreiben beginnen soll. |
| count | **int32_t** | Die Anzahl der zu lesenden Bytes. |

### Rückgabewert

Ein Task, der die asynchrone Leseoperation repräsentiert. Der Wert des TResult-Parameters enthält die Gesamtzahl der in den Puffer gelesenen Bytes. Der Ergebniswert kann kleiner sein als die angeforderte Anzahl von Bytes, wenn die aktuell verfügbaren Bytes weniger als die angeforderte Menge sind, oder er kann 0 (null) sein, wenn das Ende des Streams erreicht wurde.

## Siehe auch

* Typedef [RTaskPtr](../../../system/rtaskptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Klasse [CancellationToken](../../../system.threading/cancellationtoken/)
* Klasse [Stream](../)
* Namensraum [System::IO](../../)
* Bibliothek [Aspose.Slides](../../../)