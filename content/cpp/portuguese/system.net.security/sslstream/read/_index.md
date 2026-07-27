---
title: Read()
second_title: Referência da API Aspose.Slides para C++
description: Lê o número especificado de bytes do fluxo e grava-os no array de bytes especificado.
type: docs
weight: 391
url: /pt/system.net.security/sslstream/read/
---
## SslStream::Read(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) método


Lê o número especificado de bytes do fluxo e grava-os no array de bytes especificado.

```cpp
int32_t System::Net::Security::SslStream::Read(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count) override
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | O array de bytes onde serão gravados os bytes lidos |
| offset | **int32_t** | Uma posição baseada em zero em **buffer** onde começar a gravação |
| count | **int32_t** | O número de bytes a ler |

### Valor de Retorno

O número de bytes lidos

## SslStream::Read(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) método


Lê o número especificado de bytes do fluxo e grava-os no array de bytes especificado.

```cpp
int32_t System::Net::Security::SslStream::Read(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t count) override
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<**uint8_t**\>\& | O array de bytes onde serão gravados os bytes lidos |
| offset | **int32_t** | Uma posição baseada em zero em **buffer** onde começar a gravação |
| count | **int32_t** | O número de bytes a ler |

### Valor de Retorno

O número de bytes lidos

## Veja Também

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Classe [SslStream](../)
* Namespace [System::Net::Security](../../)
* Biblioteca [Aspose.Slides](../../../)