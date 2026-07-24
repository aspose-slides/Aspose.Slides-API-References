---
title: Write()
second_title: Aspose.Slides für C++ API Referenz
description: Schreibt den angegebenen Teilbereich von Bytes aus dem angegebenen Byte-Array in den Stream.
type: docs
weight: 209
url: /de/system.net.sockets/networkstream/write/
---
## NetworkStream::Write(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) Methode

Schreibt den angegebenen Teilbereich von Bytes aus dem angegebenen Byte-Array in den Stream.

```cpp
void System::Net::Sockets::NetworkStream::Write(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t size) override
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Das Array, das die zu schreibenden Bytes enthält. |
| offset | **int32_t** | Der Offset in Bytes im angegebenen Array. |
| size | **int32_t** | Die Anzahl der Elemente im zu schreibenden Teilbereich. |

## NetworkStream::Write(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) Methode

Schreibt den angegebenen Teilbereich von Bytes aus dem angegebenen Byte-Array in den Stream.

```cpp
void System::Net::Sockets::NetworkStream::Write(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t size) override
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<**uint8_t**\>\& | Die Array-Ansicht, die die zu schreibenden Bytes enthält |
| offset | **int32_t** | Ein 0-basierter Index des Elements in **buffer**, bei dem der zu schreibende Teilbereich beginnt |
| size | **int32_t** | Die Anzahl der Elemente im zu schreibenden Teilbereich |

## Siehe auch

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Klasse [NetworkStream](../)
* Namensraum [System::Net::Sockets](../../)
* Bibliothek [Aspose.Slides](../../../)