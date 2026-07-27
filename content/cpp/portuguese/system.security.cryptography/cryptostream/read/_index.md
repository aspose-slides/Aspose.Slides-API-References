---
title: Read()
second_title: Referência da API Aspose.Slides para C++
description: Lê dados do fluxo.
type: docs
weight: 14
url: /pt/system.security.cryptography/cryptostream/read/
---
## CryptoStream::Read(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) method

Lê dados do fluxo.

```cpp
int32_t System::Security::Cryptography::CryptoStream::Read(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count) override
```

### Argumentos

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Buffer de dados de destino. |
| offset | **int32_t** | Deslocamento no buffer de destino. |
| count | **int32_t** | Número de bytes a ler. |

### Valor de Retorno

Número de bytes realmente lidos.

## CryptoStream::Read(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) method

Lê dados do fluxo.

```cpp
int32_t System::Security::Cryptography::CryptoStream::Read(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t count) override
```

### Argumentos

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<**uint8_t**\>\& | Buffer de dados de destino. |
| offset | **int32_t** | Deslocamento no buffer de destino. |
| count | **int32_t** | Número de bytes a ler. |

### Valor de Retorno

Número de bytes realmente lidos.

## Veja Também

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [CryptoStream](../)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.Slides](../../../)