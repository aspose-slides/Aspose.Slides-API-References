---
title: Read()
second_title: Aspose.Slides für C++ API-Referenz
description: Liest Daten aus dem Stream.
type: docs
weight: 14
url: /de/system.security.cryptography/cryptostream/read/
---
## CryptoStream::Read(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) Methode

Liest Daten aus dem Stream.

```cpp
int32_t System::Security::Cryptography::CryptoStream::Read(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count) override
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Ziel-Datenpuffer. |
| offset | **int32_t** | Versatz im Zielpuffer. |
| count | **int32_t** | Anzahl der zu lesenden Bytes. |

### Rückgabewert

Tatsächlich gelesene Byteanzahl.

## CryptoStream::Read(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) Methode

Liest Daten aus dem Stream.

```cpp
int32_t System::Security::Cryptography::CryptoStream::Read(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t count) override
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<**uint8_t**\>\& | Ziel-Datenpuffer. |
| offset | **int32_t** | Versatz im Zielpuffer. |
| count | **int32_t** | Anzahl der zu lesenden Bytes. |

### Rückgabewert

Tatsächlich gelesene Byteanzahl.

## Siehe auch

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Klasse [CryptoStream](../)
* Namensraum [System::Security::Cryptography](../../)
* Bibliothek [Aspose.Slides](../../../)