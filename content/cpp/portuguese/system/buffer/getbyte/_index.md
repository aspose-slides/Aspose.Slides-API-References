---
title: GetByte()
second_title: Referência da API Aspose.Slides para C++
description: Interpreta o array tipado especificado como um array de bytes bruto e recupera o valor do byte no deslocamento de byte especificado.
type: docs
weight: 27
url: /pt/system/buffer/getbyte/
---
## Buffer::GetByte(const SharedPtr\<Array\<T\>\>\&, int) método

Interpreta o array tipado especificado como um array de bytes bruto e recupera o valor de byte no deslocamento de byte especificado.

```cpp
template<typename T> static uint8_t System::Buffer::GetByte(const SharedPtr<Array<T>> &array, int index)
```

### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| T | O tipo dos elementos do array |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| array | const [SharedPtr](../../sharedptr/)\<[Array](../../array/)\<T\>\>\& | O array alvo |
| index | int | Deslocamento baseado em zero do byte a ser recuperado |

### Valor de retorno

O valor de byte no índice especificado

## Buffer::GetByte(const System::Details::ArrayView\<T\>\&, int) método

Interpreta o array tipado especificado como um array de bytes bruto e recupera o valor de byte no deslocamento de byte especificado.

```cpp
template<typename T> static uint8_t System::Buffer::GetByte(const System::Details::ArrayView<T> &array, int index)
```

### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| T | O tipo dos elementos da visualização do array |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| array | const System::Details::ArrayView\<T\>\& | A visualização do array alvo |
| index | int | Deslocamento baseado em zero do byte a ser recuperado |

### Valor de retorno

O valor de byte no índice especificado

## Buffer::GetByte(const System::Details::StackArray\<T, N\>\&, int) método

Interpreta o array tipado especificado como um array de bytes bruto e recupera o valor de byte no deslocamento de byte especificado.

```cpp
template<typename T,std::size_t> static uint8_t System::Buffer::GetByte(const System::Details::StackArray<T, N> &array, int index)
```

### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| T | O tipo dos elementos do array de pilha |
| N | O tamanho do array de pilha |

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| array | const System::Details::StackArray\<T, N\>\& | O array de pilha alvo |
| index | int | Deslocamento baseado em zero do byte a ser recuperado |

### Valor de retorno

O valor de byte no índice especificado

## Veja também

* Typedef [SharedPtr](../../sharedptr/)
* Classe [Array](../../array/)
* Classe [Buffer](../)
* Namespace [System](../../)
* Biblioteca [Aspose.Slides](../../../)