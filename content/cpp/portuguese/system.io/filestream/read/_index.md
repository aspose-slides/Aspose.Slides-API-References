---
title: Read()
second_title: Referência da API Aspose.Slides para C++
description: Lê o número especificado de bytes do fluxo e os grava no array de bytes especificado.
type: docs
weight: 183
url: /pt/system.io/filestream/read/
---
## FileStream::Read(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) método


Lê o número especificado de bytes do fluxo e os grava no array de bytes especificado.

```cpp
int32_t System::IO::FileStream::Read(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count) override
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | O array de bytes para onde escrever os bytes lidos. |
| offset | **int32_t** | Uma posição baseada em 0 em **buffer** para começar a escrever. |
| count | **int32_t** | O número de bytes a ler. |

### Valor de Retorno

O número de bytes lidos.

## FileStream::Read(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) método


Lê o número especificado de bytes do fluxo e os grava no array de bytes especificado.

```cpp
int32_t System::IO::FileStream::Read(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t count) override
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<**uint8_t**\>\& | A visualização do array de bytes para onde escrever os bytes lidos. |
| offset | **int32_t** | Uma posição baseada em 0 em **buffer** para começar a escrever. |
| count | **int32_t** | O número de bytes a ler. |

### Valor de Retorno

O número de bytes lidos.

## Veja Também

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [FileStream](../)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)