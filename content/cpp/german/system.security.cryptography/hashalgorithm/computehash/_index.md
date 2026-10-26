---
title: ComputeHash()
second_title: Aspose.Slides für C++ API-Referenz
description: Hasht Puffer.
type: docs
weight: 14
url: /de/system.security.cryptography/hashalgorithm/computehash/
---
## HashAlgorithm::ComputeHash(const ArrayPtr\<uint8_t\>\&) method

Hasht Puffer.

```cpp
ArrayPtr<uint8_t> System::Security::Cryptography::HashAlgorithm::ComputeHash(const ArrayPtr<uint8_t> &buffer)
```

### Arguments

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Quellpuffer. |

### Return Value

Berechneter Hashwert.

## HashAlgorithm::ComputeHash(const ArrayPtr\<uint8_t\>\&, int, int) method

Hasht Pufferabschnitt.

```cpp
ArrayPtr<uint8_t> System::Security::Cryptography::HashAlgorithm::ComputeHash(const ArrayPtr<uint8_t> &buffer, int offset, int count)
```

### Arguments

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Quellpuffer. |
| offset | int | Offset im Quellpuffer. |
| count | int | Anzahl der Bytes, die aus dem Quellpuffer verwendet werden. |

### Return Value

Berechneter Hashwert.

## HashAlgorithm::ComputeHash(SharedPtr\<IO::Stream\> const\&) method

Liest den Stream bis zum Ende und berechnet den Hash für die gelesenen Daten.

```cpp
ArrayPtr<uint8_t> System::Security::Cryptography::HashAlgorithm::ComputeHash(SharedPtr<IO::Stream> const &inputStream)
```

### Arguments

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| inputStream | [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\> const\& | Stream, aus dem Daten gelesen werden. |

### Return Value

Berechneter Hashwert für die gesamten Stream-Daten.

## See Also

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [HashAlgorithm](../)
* Klasse [Stream](../../../system.io/stream/)
* Namensraum [System::Security::Cryptography](../../)
* Bibliothek [Aspose.Slides](../../../)