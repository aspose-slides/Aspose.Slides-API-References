---
title: Read()
second_title: Referência da API Aspose.Slides para C++
description: Lê o número especificado de bytes do fluxo e grava-os no array de bytes especificado.
type: docs
weight: 196
url: /pt/system.net.sockets/networkstream/read/
---
## NetworkStream::Read(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) método


Lê o número especificado de bytes do fluxo e grava-os no array de bytes especificado.

```cpp
int32_t System::Net::Sockets::NetworkStream::Read(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t size) override
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | O array de bytes onde os bytes lidos serão gravados. |
| offset | **int32_t** | O deslocamento em bytes no array especificado. |
| size | **int32_t** | O número de bytes a ler. |

### Valor de Retorno

O número de bytes lidos.

## NetworkStream::Read(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) método


Lê o número especificado de bytes do fluxo e grava-os no array de bytes especificado.

```cpp
int32_t System::Net::Sockets::NetworkStream::Read(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t size) override
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<**uint8_t**\>\& | A visualização do array de bytes para onde gravar os bytes lidos |
| offset | **int32_t** | Uma posição baseada em zero em **buffer** onde iniciar a gravação |
| size | **int32_t** | O número de bytes a ler |

### Valor de Retorno

O número de bytes lidos

## Ver também

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Classe [NetworkStream](../)
* Espaço de nomes [System::Net::Sockets](../../)
* Library [Aspose.Slides](../../../)