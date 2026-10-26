---
title: Read()
second_title: Referência da API Aspose.Slides para C++
description: Lê o número especificado de bytes do fluxo subjacente e grava-os no array de bytes especificado.
type: docs
weight: 53
url: /pt/system.io/bufferedstream/read/
---
## BufferedStream::Read(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) método


Lê o número especificado de bytes do fluxo subjacente e grava-os no array de bytes especificado.

```cpp
virtual int32_t System::IO::BufferedStream::Read(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count) override
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | O array de bytes onde gravar os bytes lidos |
| offset | **int32_t** | Uma posição baseada em zero em **buffer** onde começar a gravar |
| count | **int32_t** | O número de bytes a ler |

### Valor de Retorno

O número de bytes lidos

## BufferedStream::Read(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) método


Lê o número especificado de bytes do fluxo subjacente e grava-os no array de bytes especificado.

```cpp
virtual int32_t System::IO::BufferedStream::Read(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t count) override
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<**uint8_t**\>\& | O array de bytes onde gravar os bytes lidos |
| offset | **int32_t** | Uma posição baseada em zero em **buffer** onde começar a gravar |
| count | **int32_t** | O número de bytes a ler |

### Valor de Retorno

O número de bytes lidos

## Veja Também

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [BufferedStream](../)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)