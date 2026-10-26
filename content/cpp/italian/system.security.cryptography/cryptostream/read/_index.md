---
title: Read()
second_title: Aspose.Slides per C++ API Reference
description: Legge i dati dallo stream.
type: docs
weight: 14
url: /it/system.security.cryptography/cryptostream/read/
---
## CryptoStream::Read(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) metodo

Legge i dati dallo stream.

```cpp
int32_t System::Security::Cryptography::CryptoStream::Read(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count) override
```

### Argomenti

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Buffer di destinazione dei dati. |
| offset | **int32_t** | Offset nel buffer di destinazione. |
| count | **int32_t** | Numero di byte da leggere. |

### Valore di ritorno

Numero di byte effettivamente letti.

## CryptoStream::Read(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) metodo

Legge i dati dallo stream.

```cpp
int32_t System::Security::Cryptography::CryptoStream::Read(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t count) override
```

### Argomenti

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<**uint8_t**\>\& | Buffer di destinazione dei dati. |
| offset | **int32_t** | Offset nel buffer di destinazione. |
| count | **int32_t** | Numero di byte da leggere. |

### Valore di ritorno

Numero di byte effettivamente letti.

## Vedi anche

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Classe [CryptoStream](../)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.Slides](../../../)