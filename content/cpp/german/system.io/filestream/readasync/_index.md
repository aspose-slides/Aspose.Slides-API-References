---
title: ReadAsync()
second_title: Aspose.Slides für C++ API-Referenz
description: Liest asynchron eine Sequenz von Bytes aus dem aktuellen Stream, verschiebt die Position im Stream um die Anzahl der gelesenen Bytes und überwacht Abbruchanforderungen.
type: docs
weight: 196
url: /de/system.io/filestream/readasync/
---
## FileStream::ReadAsync(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t, const Threading::CancellationToken\&) Methode

Liest asynchron eine Sequenz von Bytes aus dem aktuellen Stream, verschiebt die Position im Stream um die Anzahl der gelesenen Bytes und überwacht Abbruchanforderungen.

```cpp
RTaskPtr<int32_t> System::IO::FileStream::ReadAsync(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count, const Threading::CancellationToken &cancellationToken) override
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Das Byte-Array, in das die gelesenen Bytes geschrieben werden. |
| offset | **int32_t** | Eine nullbasierte Position in **buffer**, an der das Schreiben beginnt. |
| count | **int32_t** | Die Anzahl der zu lesenden Bytes. |
| cancellationToken | const [Threading::CancellationToken](../../../system.threading/cancellationtoken/)\& | Das Token, das auf Abbruchanforderungen überwacht wird. |

### Rückgabewert

Eine Aufgabe, die den asynchronen Lesevorgang darstellt. Der Wert des TResult-Parameters enthält die Gesamtzahl der in das Puffer gelesenen Bytes. Der Ergebniswert kann kleiner sein als die angeforderte Anzahl von Bytes, wenn die aktuell verfügbare Byte-Anzahl kleiner ist als die angeforderte, oder er kann 0 (null) sein, wenn das Ende des Streams erreicht wurde.

## Siehe auch

* Typedef [RTaskPtr](../../../system/rtaskptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Klasse [CancellationToken](../../../system.threading/cancellationtoken/)
* Klasse [FileStream](../)
* Namensraum [System::IO](../../)
* Library [Aspose.Slides](../../../)