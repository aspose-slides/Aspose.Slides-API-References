---
title: Read()
second_title: Aspose.Slides voor C++ API-referentie
description: Leest gegevens van de stroom.
type: docs
weight: 14
url: /nl/system.security.cryptography/cryptostream/read/
---
## CryptoStream::Read(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) method

Leest gegevens van de stroom.

```cpp
int32_t System::Security::Cryptography::CryptoStream::Read(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count) override
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Doelgegevensbuffer. |
| offset | **int32_t** | Offset in doelbuffer. |
| count | **int32_t** | Aantal bytes om te lezen. |

### Retourwaarde

Werkelijk gelezen aantal bytes.

## CryptoStream::Read(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) method

Leest gegevens van de stroom.

```cpp
int32_t System::Security::Cryptography::CryptoStream::Read(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t count) override
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<**uint8_t**\>\& | Doelgegevensbuffer. |
| offset | **int32_t** | Offset in doelbuffer. |
| count | **int32_t** | Aantal bytes om te lezen. |

### Retourwaarde

Werkelijk gelezen aantal bytes.

## Zie ook

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Klasse [CryptoStream](../)
* Naamruimte [System::Security::Cryptography](../../)
* Bibliotheek [Aspose.Slides](../../../)