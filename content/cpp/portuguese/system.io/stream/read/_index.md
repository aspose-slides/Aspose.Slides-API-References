---
title: Read()
second_title: Referência da API Aspose.Slides para C++
description: Lê o número especificado de bytes do fluxo e grava-os no array de bytes especificado.
type: docs
weight: 27
url: /pt/system.io/stream/read/
---
## Stream::Read(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) método


Lê o número especificado de bytes do fluxo e grava-os no array de bytes especificado.

```cpp
virtual int32_t System::IO::Stream::Read(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count)=0
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | O array de bytes para onde escrever os bytes lidos |
| offset | **int32_t** | Uma posição baseada em zero em **buffer** para iniciar a escrita |
| count | **int32_t** | O número de bytes a ler |

### Valor de Retorno

O número de bytes lidos

## Stream::Read(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) método


Lê o número especificado de bytes do fluxo e grava-os no array de bytes especificado.

```cpp
virtual int32_t System::IO::Stream::Read(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t count)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<**uint8_t**\>\& | A visualização do array de bytes para onde escrever os bytes lidos |
| offset | **int32_t** | Uma posição baseada em zero em **buffer** para iniciar a escrita |
| count | **int32_t** | O número de bytes a ler |

### Valor de Retorno

O número de bytes lidos

## Stream::Read(const System::Details::StackArray\<uint8_t, N\>\&, int32_t, int32_t) método


Lê o número especificado de bytes do fluxo e grava-os no array de bytes especificado.

```cpp
template<std::size_t> int32_t System::IO::Stream::Read(const System::Details::StackArray<uint8_t, N> &buffer, int32_t offset, int32_t count)
```


### Parâmetros de Modelo

| Parâmetro | Descrição |
| --- | --- |
| N | O tamanho do array de pilha |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| buffer | const System::Details::StackArray\<**uint8_t**, N\>\& | O array de pilha de bytes para onde escrever os bytes lidos |
| offset | **int32_t** | Uma posição baseada em zero em **buffer** para iniciar a escrita |
| count | **int32_t** | O número de bytes a ler |

### Valor de Retorno

O número de bytes lidos

## Stream::Read(const System::Span\<uint8_t\>\&) método


Lê o número especificado de bytes do fluxo e grava-os no span de bytes especificado.

```cpp
virtual int32_t System::IO::Stream::Read(const System::Span<uint8_t> &buffer)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| buffer | const [System::Span](../../../system/span/)\<**uint8_t**\>\& | O span de bytes para onde escrever os bytes lidos |

### Valor de Retorno

O número de bytes lidos

## Veja Também

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Classe [Stream](../)
* Classe [Span](../../../system/span/)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)